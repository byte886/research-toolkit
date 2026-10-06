---
name: web-research-toolkit
description: 网络调研与公开网页数据采集的统一编排技能，**是所有调研诉求的唯一统一入口**。做资料搜集、市场/政策/行业/竞品调研、网页批量采集或转结构化(JSON/表格)、事实核查与信源溯源、网页变更监控、土地成交/挂牌等房地产数据采集时使用；**重点决策或自身能力不足的问题需"多源群策群力"（外部 Chrome 分别问 Gemini/ChatGPT/Claude/Grok/DeepSeek/豆包/元宝等多家 AI 交叉验证）时使用**；含生财有术(scys-mcp)站内付费圈内容检索。按任务特征路由取数通道，**按调研类型路由总表（research-router）匹配 15 类调研类型**，按需求层级（L1 轻量速查/L2 标准调研/L3 深度决策）选择调研力度，并固化"界定→选源→采集→交叉核验→结构化溯源→交付"标准流程；**执行任何调研任务时本 Agent 自己也必须按此技能分层路由**。
compatibility: "跨平台：scripts 仅用 Python 标准库与云端取数 API，不依赖操作系统专有能力；已在 macOS 实测，其余平台遇路径/编码/本机代理差异就地适配，无需按 OS 拦截停跑"
---

# 网络调研工具箱（web-research-toolkit）

## 平台适用
- 本技能方法论与脚本**跨平台**：scripts 只用 Python 标准库（urllib/json/socket/subprocess 等）与云端取数 API（Jina/Exa/Firecrawl），不调用任何操作系统专有能力。
- 已在 macOS 实测；其余平台未专门实测，遇路径、编码、本机代理端口差异就地适配，**不按操作系统拦截停跑**。
- 本机代理按候选端口探测、不写死；浏览器 cookie 复用只是可选增强，缺失时回退云端通道，不作为硬依赖。

统一编排"从公开网络取数 → 核验 → 结构化 → 溯源交付"。本技能不重复实现搜索引擎，核心价值是**选对通道、走对流程、留好证据**。

## 何时用 / 反触发

**用我**：资料搜集与汇总、市场/政策/行业/竞品调研、网页批量抓取、网页转 JSON/表格或提取固定字段、事实核查与信源溯源、网页变更监控、土地成交/挂牌等房地产评估数据采集、生财有术站内付费圈资料检索、**重点决策或能力不足问题的多源群策群力调研（L3 层，见 `references/multi-agent-consultation.md`）**。

**调研力度分层**：L1 轻量速查（≤10min，不启动多源）→ L2 标准调研（30-60min，搜索引擎+2-3家 AI+交叉核验）→ L3 深度决策（1-2h，完整多源机制）。**任何调研请求先查 `references/research-router.md` 匹配 15 类调研类型（层级/渠道/流程/交付一表定）**；拿不准按 L2 起步，证据冲突或信息不足再升级。详见 `references/multi-agent-consultation.md` 第一节。

**不用我（边界）**：视频/音频字幕与抖音、B 站等媒体下载 → 走 `multiplatform-media-fetch`；需可视化点击、人工登录、验证码 → 走浏览器自动化技能（登录交用户接管）；中国法规规范性文件的条文级检索 → 走 `pkulaw-legal-data` 技能；金融行情/财报、医疗、企业内部检索各有垂直技能，本技能只路由到它们、不重复实现。

## 标准流程（7 步，按序）

界定问题与交付物 → 拆子问题列信源清单（优先一手/官方源）→ 按下表选通道采集 → 关键事实≥2 个独立来源交叉核验、冲突保留两说 → 结构化入库（每条必带 `sourceUrl+fetchedAt+信源等级`）→ 只基于已核验证据下结论、不足标"待核实" → 交付逐条附源、需要沉淀时按项目 AGENTS 规则询问是否归档。

> 完整 SOP、反幻觉清单、房地产评估专项清单见 `references/research-workflow.md`；信源分级与结构化模板见 `references/source-schema.md`；**调研类型路由总表（所有调研诉求的唯一入口）见 `references/research-router.md`**；**策略选择与组合用法（S1-S10 组件/四种决策模式/升级回退/群策元决策）见 `references/strategy-selection.md`**；**多源群策群力（L3 深度决策）见 `references/multi-agent-consultation.md`**；**完整渠道目录（九大类 80+ 渠道：搜索引擎/国内外对话助手/AI搜索引擎/学术/垂直数据源/社交社区/自定义）见 `references/channel-directory.md`**；**行业特定词库与查询包见 `references/industry-packs.md`（已含珠宝营销×AI 包）**。

## 取数通道路由（先选通道再动手）

| 要做什么 | 用什么 | 读哪篇 |
| --- | --- | --- |
| 通道总览、决策树选型、网络分流 | —（先选通道再动手） | `channel-selection.md` |
| 不知信息在哪、探索性问题、少量事实、要最新动态 | 内置联网搜索（一次并行 ≤3 query） | `channels-detail.md` §3.1 |
| 学术/金融/医疗/企业内部垂直检索 | 对应垂直检索技能；中国大陆法规走 pkulaw-legal-data | `channels-detail.md` §3.2 |
| 已知 URL 要全文、在线 PDF、大陆 gov.cn 政府站 | web.fetch（分页读完，不受本机代理影响） | `channels-detail.md` §3.3 |
| 整站批量、JS 动态页、固定字段 JSON、变更监控 | Firecrawl（脚本 `scripts/fc_scrape.py`，按 credit 计费） | `firecrawl-guide.md` |
| 英文/海外资料、语义"找相似"、Reddit 讨论线索 | Exa 语义搜索（`scripts/exa_search.py`，免 key、直连） | `channels-detail.md` §3.6 |
| 海外已知页 web.fetch/Firecrawl 都读不下 | Jina Reader（`scripts/jina_read.py`，走代理） | `channels-detail.md` §3.7 |
| 生财有术站内私有资料（精华帖/项目库/航海手册/圈友/足迹） | scys-mcp 连接器（需会员+OAuth，默认只读） | `scys-mcp-guide.md` |
| 政策/红头文件权威库与五级分层找法 | policy-source-map | `policy-source-map.md` |

> 通道总览表、决策树、各通道实测边界见 `channel-selection.md`；网络分流与"先英后中"检索语言策略见 `network-and-language.md`；实测台账与待接入清单见 `field-test-notes.md`。
> 成本原则：能用低成本通道解决就不上重通道；要穷尽/结构化/反复更新才上 Firecrawl。

## 溯源硬规则（不可违反，入口当场生效）

1. 每个事实性结论可追溯到具体 URL；关键事实多源交叉并标注信源等级（官方/权威/专业/自媒体）。
2. 数字、日期、价格必须来自来源或可复现计算，否则标"待核实"；**禁止编造来源、数值、链接**。
3. 每条结构化记录必含 `sourceUrl、sourceName、sourceTier、fetchedAt`；评估数据另需可回源核验。
4. 抓取失败、被反爬、内容为空要**如实报告**，不得用旧快照或臆测填充；区分"已查证/一方称/未核实"。
5. 只采集公开信息，遵守目标站点条款与个人信息保护法，不采集个人敏感信息。
6. **AI 结构化结果是初稿不是终稿**：入库前必过校验门（合理区间、单位按 `*_raw` 复算、相邻字段错位检查、客观字段以程序为准）。

## 能力与扩展位（迭代登记处）

**已就位**：内置联网搜索 + 垂直检索路由；web.fetch 精读（含大陆 gov.cn 兜底）；Firecrawl 单页（Markdown/JSON，keyless 实测可用）；Exa 英文语义搜索、Jina 海外网页兜底、gh/RSS/V2EX 均已实测；国内外网络分流；生财有术 scys-mcp 搜读+AI 亦仁全管线（详见 `scys-mcp-guide.md`）；**多源群策群力机制（L3 深度决策，5 家 AI 实测，含渠道矩阵/差异化模板/浏览器执行要点/更新机制）**；**完整渠道目录（九大类 80+ 渠道，2026-10 多源验证）**；**策略选择层（四种决策模式 + S1-S10 可组合策略组件 + 十种 AI 协作模式 + 群策元决策）**；**行业包机制（已含珠宝营销×AI 包 v1：中英词库+15 条查询模板+渠道补充）**。

**扩展位**（具备条件后启用，先在 `field-test-notes.md` 登记实测再使用）：Firecrawl key（Crawl/Map/批量 Extract/Monitor、MCP 接入）；中国土地市场网/公共资源交易中心/挂牌平台适配器；定时采集+快照 diff；社交 UGC 平台（小红书/Twitter/Reddit 读帖/公众号，启用前置与封号风险见 `field-test-notes.md` §待接入）；**行业包扩容（珠宝包向 300 中+300 英关键词+50 组模板远期目标迭代，其他行业按需建包）**。

> 新增任何取数能力，先写进 `channel-selection.md` 的通道表，再在流程中使用，保持单一权威清单。
