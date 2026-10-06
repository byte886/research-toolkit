# 行业扩展包（industry packs）

> 不同行业有特定词汇、渠道和查询需求。按需建包，包与包独立、可复用。
> **如何建新包**：复制本文件的包结构（词库/查询模板/渠道补充/待验证项），登记在"已建包"清单；词库按四维分类（行业/AI技术/营销场景/信号意图），来源标注四档（已查证/经搜索补充/一方说法/未经核实）。

## 已建包

| 包 | 行业 | 状态 | 主要资产 |
|---|---|---|---|
| jewelry-ai | 珠宝营销 × 珠宝AI | v2（2026-10-06） | 中文词库 40+ / 英文词库 30+ / 查询模板 15 条 / 渠道补充 / **珠宝特定调研源 8 组** |

---

## 包：jewelry-ai（珠宝营销 × 珠宝AI）

> v1 由"多 AI 群策群力"（Gemini/ChatGPT/Claude/Grok/DeepSeek）+ 监控仓《搜索方法论 v2》合并沉淀；v2（2026-10-06）新增"珠宝特定调研源"8 组（Rapaport 价格指数/培育钻数据/拍卖趋势/产业带批发市场/行业媒体/鉴定机构/黄金价格/香港贸易）。
> 远期目标：300 中文 + 300 英文关键词 + 50 组查询模板（ChatGPT 提议）；v1 先给核心可用版，随使用迭代扩容。

### 1. 中文词库（四维分类，核心 40+）

**A. 珠宝行业词**：珠宝、黄金、钻石、翡翠、玉石、珍珠、银饰、古法金、培育钻石、培育钻、彩宝、水贝、老凤祥、周大福、周生生、老庙黄金、六福、潮宏基、菜百、梵克雅宝、卡地亚、Tiffany

**B. AI/技术词**：AI设计、AIGC、虚拟试戴、AR试戴、数字人、智能客服、个性化定制、珠宝3D建模、渲染、Midjourney、ComfyUI、Flux、Stable Diffusion、ControlNet、Lora、智能体、大模型、计算机视觉、图像生成、视频生成

**C. 营销场景词**：营销、获客、转化、私域、直播、直播带货、种草、小红书、抖音、投放、投流、会员、门店数字化、爆款、案例、复盘、联名、新品发布、门店获客

**D. 信号/意图词**：案例、数据、增长、ROI、转化率、GMV、财报、试点、融资、战略合作、白皮书、研报、价格、积分、会员体系、监管、合规、AI生成标识、广告法

### 2. 英文词库（核心 30+）

**A. 行业**：jewelry, fine jewelry, luxury jewelry, lab-grown diamond, lab grown, LGD, bridal, gemstone, gold jewelry
**B. AI/技术**：generative AI, GenAI, AI design, virtual try-on, VTO, AR try-on, computer vision, 3D generation, recommendation system, personalization, AI agent, agentic commerce
**C. 营销**：marketing, campaign, influencer, DTC, seeding, UGC, e-commerce, conversational commerce, AI stylist, AI shopping assistant
**D. 信号**：case study, pilot, beta, launch, partnership, acquisition, ROI, ROAS, conversion, sales lift, results, earnings, survey, whitepaper, funding, patent

### 3. 查询模板（15 条，直接粘贴）

| 监控问题 | 查询串 |
|---|---|
| 竞品 AI 新动作 | `(珠宝 OR 黄金 OR 翡翠) AI (案例 OR 营销 OR 视频) 2026` |
| 某品牌动态 | `("周大福" OR "老凤祥" OR "老庙") (AI OR 数字人 OR 直播) 2026` |
| 头部品牌 AI 动态（新闻稿渠道） | `(周大福 OR 老凤祥 OR 周生生 OR 六福) (AI OR 智能体 OR 数字化) (site:prnewswire.com OR site:businesswire.com OR site:36kr.com OR site:21jingji.com)` |
| 珠宝零售 AI 落地案例 | `(珠宝 OR 黄金首饰) (门店 OR 零售 OR 导购) (AI OR 智能体 OR 数字人) -招聘 -求职 -培训` |
| 行业报告 | `(珠宝 OR 黄金) (市场 OR 趋势 OR 报告) filetype:pdf 2026` |
| 抖音案例（站外） | `site:iesdouyin.com/share/video 珠宝 (直播 OR 爆款 OR 案例)` |
| 小红书笔记（收录少→深挖走 multiplatform-media-fetch） | `site:xiaohongshu.com 珠宝 AI` |
| 海外趋势 | `(jewelry OR jewellery OR diamond) (AI OR "artificial intelligence") (retail OR marketing OR e-commerce) after:2025-01-01` |
| 技术供应商情报 | `(jewelry OR 珠宝) ("AI solution" OR "AI platform" OR "smart retail") (filetype:pdf OR site:github.com)` |
| 政策合规监控 | `(珠宝 OR 黄金 OR 钻石) (AI生成 OR AIGC OR 数字人) (监管 OR 合规 OR 标识 OR 广告法)` |
| 海外案例复盘 | `(jewelry OR "fine jewelry") (AI OR "virtual try-on") (case study OR ROI OR workflow) -course -masterclass` |
| 异常词扫描（捕捉变化） | `jewelry ("pilot" OR "beta" OR "launch" OR "partnership" OR "acquisition")` |
| Google/Bing 语法 | `(珠宝AI | AI珠宝 | 智能珠宝) (营销 | 个性化 | 虚拟试戴) (报告 | 案例 | 趋势) 2024..2026 -招聘 -课程` |
| X 实时信号 | `("jewelry AI" OR "virtual try-on jewelry") (marketing OR trend OR launch) min_faves:20 since:2026-01-01 -filter:replies` |
| 工具价格 | `(即梦 OR 可灵 OR 苞米AI) (价格 OR 积分 OR 会员) 2026` |

### 4. 渠道补充（珠宝特有）

- **国内**：财联社/21财经/36氪（企业 AI 转型首发渠道）；宝玉石周刊/中国黄金报（垂直媒体）；巨潮资讯/港交所披露易（财报）；中国珠宝玉石首饰行业协会/中国黄金协会/WGC（行业数据）；抖音电商学习中心；新榜/蝉妈妈/飞瓜/巨量算数/千瓜（社媒数据）
- **海外**：JCK Magazine / National Jeweler / Rapaport / Professional Jeweller / JNA / Jewellery Business / Bangkok Gems；Business of Fashion / Vogue Business / Jing Daily（中国消费者视角）；Google Patents（专利）；TikTok Creative Center（广告趋势）
- **设计灵感**：site:zcool.com.cn 珠宝设计；Pinterest；小红书珠宝设计话题

### 5. 珠宝特定调研源（v2 新增 · 垂类专有，区别于通用社交矩阵）

> 通用社交选型（channel-directory §9.3）之外，珠宝行业还有**通用矩阵覆盖不到的专有数据源**。按调研目标直查下表（2026-10 多源验证）。

| 调研目标 | 专有源（主） | 用途/证据 |
|---|---|---|
| **钻石/裸石价格** | Rapaport（RAPI™ 价格指数+周报+月度情报报告，订阅制） | 全球基准：2 万+专业人士/100+ 国使用；1ct/0.3ct/0.5ct 分尺寸报价；培育钻对天然钻分流数据（2026-08 情报报告） |
| **培育钻市场数据** | Edahn Golan Diamond Research / StoneAlgo / Tenoris / 《培育钻石产业发展报告》 | Tenoris：培育钻占新订婚戒指 ~50%（by volume）/15-20%（by value）；中国培育钻产能占全球 63%（2025 报告：市场规模 140 亿→2030 超 1025 亿） |
| **彩宝/翡翠趋势** | 苏富比/佳士得/富艺斯在线目录 + Ministry of Gems 年度报告 | 拍卖纪录即趋势风向（Paraíba 电气石 $4.2M、克什米尔蓝宝石 $2.1M、Aga Khan 祖母绿 $8.8M）；彩色宝石连创纪录 |
| **产业带/批发市场** | 深圳水贝（全球最大批发枢纽，9000+ 企业、全国金饰 60%、铂金/K金 70%）、广州番禺（OEM/翡翠珍珠）、东莞长安（不锈钢）、曼谷（彩宝）、斋浦尔（彩宝）、诸暨（珍珠）、香港（拍卖贸易枢纽） | 找货源/产业带动态/价格波动新闻（如"水贝金价跌破 1100"）；水贝金价透明挂钩上海金交所 |
| **行业媒体（资讯）** | JCK Magazine / Rapaport News / National Jeweler / JE Insider（hkje.com 香港贸易数据）/ 中国黄金报 / 宝玉石周刊 | 行业动态一手来源；JCK Las Vegas 等展会观察（2026：K 型需求分化） |
| **鉴定/合规机构** | GIA（已整合 AGS 体系）/ IGI / NGTC（国检）/ SSEF / 古柏林 | 证书趋势（培育钻 IGI vs GIA AGS 溢价）、鉴定话术合规、培育钻分级标准 |
| **黄金价格** | 上海金交所 / LBMA / 品牌金饰克价（水贝-品牌价差） | 金饰定价/成本测算；金价波动直接影响门店（2026-10 国内品牌克价 ~1250 元/水贝 ~1061 元） |
| **香港/外贸数据** | 香港贸发局统计（JE Insider 每月转载） | 珠宝首饰类别贸易表现（出口/进口月度） |

> 使用方法：钻石价格→直查 Rapaport；彩宝趋势→拍卖目录+年度报告；产业带动态→批发市场新闻；合规→鉴定机构标准。以上均为珠宝调研**强需求渠道**，命中即指定为主渠道（对应 strategy-selection §6）。

### 6. 待验证/待扩容（诚实标注）

- 词库 v1 为核心版，离 300+300 远期目标差一个量级；随每期监控使用把新增高频词回填本包（每周）
- 各模板"实测可用性"（哪个操作符在哪个工具不生效）执行时记录，回写本节
- 数字人/口播/真人出镜类内容的风控边界（Seedance 2.0 系列暂不支持真人人脸正脸/口播）——涉及视频生成时注意
