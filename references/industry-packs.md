---
type: Reference
title: 行业扩展包（industry packs）
description: 鉴藏总域各行业词库/查询模板/垂类调研源/渠道补充包。已建：jewelry-ai（主）、jadeite（主）、ceramics（备选）、furniture（正式）；候选：painting-calligraphy / watches / spirits / agarwood-incense / western-antiques
tags: [industry-packs, heritage, 行业包, 珠宝, 翡翠, 陶瓷, 家具, 书画, 腕表, 名酒, 沉香, 西洋古董]
sources:
  - id: salone-2026
    resource: https://areapress.salonemilano.it/26_april_26_en/Final_Press_Release_Salone_del_Mobile_Milano_2026_ZH.pdf
    title: Salone del Mobile.Milano 2026 官方终稿
  - id: shangpu-furniture
    resource: https://survey.shangpu-china.com/uploadfile/202601/795fead3832ec46.pdf
    title: 尚普咨询 2026 年 1~10 月成套家具市场洞察报告
  - id: sothebys-distilled
    resource: https://www.sothebys.com/en/digital-catalogues/distilled-whisky-moutai-hk1612
    title: 苏富比香港 Distilled | Whisky + Moutai 烈酒拍卖
  - id: xinhua-agarwood
    resource: https://indices.cnfin.com/jgzs/wenzixiangqingye/detail/20260518/4414070_1.html
    title: 新华指数中国沉香价格指数（2026-04 月报）
  - id: thepaper-guardian-2025
    resource: https://www.thepaper.cn/newsDetail_forward_30904564
    title: 中国嘉德 2025 春拍总成交 16 亿（澎湃）
generated: { by: "doubao/okf-wiki", at: "2026-10-07T12:00:00+08:00" }
status: draft
stale_after: "2026-12-31T23:59:59+08:00"
version: v2
---

# 行业扩展包（industry packs）

> 不同行业有特定词汇、渠道和查询需求。按需建包，包与包独立、可复用。
> **如何建新包**：复制本文件的包结构（词库/查询模板/渠道补充/待验证项），登记在"已建包"清单；词库按四维分类（行业/AI技术/营销场景/信号意图），来源标注四档（已查证/经搜索补充/一方说法/未经核实）。**有文化/地域体系差异的品类**：先按"通用维度：文明体系细分"的四步法建体系矩阵，再填词库与模板。
> **总域**：以下包属于**鉴藏总域（heritage）**——鉴宝+收藏，覆盖珠宝/翡翠/古玩·古董/家具/东方·西方收藏体系。

## 已建包

| 包 | 行业 | 鉴藏子域 | 状态 | 主要资产 |
|---|---|---|---|---|
| jewelry-ai | 珠宝营销 × 珠宝AI | heritage/01_jewelry | **当前主包** v3（2026-10-06） | 中文词库 40+ / 英文词库 30+ / 查询模板 15 条 / 渠道补充 / 珠宝特定调研源 8 组 / 按文明·市场体系细分 8 体系（通用维度实例） |
| jadeite | 翡翠 | heritage/02_jadeite | **当前主包** v1（2026-10-06） | 产业带+产地双维度（帕敢/瑞丽公盘/揭阳·平洲·四会）/ 中英词库 / 查询模板 6 条 / 待验证 3 项 |
| ceramics | 陶瓷 × 瓷器 | heritage/03_ceramics | **正式包 v1（2026-10-07 用户拍板转正式，含陶瓷手串品类）** | 体系细分 5 组（艺术瓷/产业瓷/日本/欧洲/伊斯兰）+ **陶瓷手串专组（瓷珠文玩线）** / 中英词库 / 查询模板 6+2 条 / 专属源（佛山陶博会·醴陵瓷博会·雅昌拍卖） |
| antiques | 古玩·古董（杂项器物总包） | heritage/03_antiques | **正式包 v1（2026-10-07 用户拍板转正式）** | 杂项器物支线（鼻烟壶/铜器/漆器/竹木牙角/文房/高古玉）+ 宗教艺术支线（佛造像/唐卡）+ 文人收藏支线（古籍/碑帖）；陶瓷支线指针→ceramics 包 |
| furniture | 家具 × 家居 | heritage/04_furniture | **正式包 v1（2026-10-07 由示范段升级）** | 六体系双轨（收藏轨=明清古典拍卖 / 消费轨=新中式·北欧·日式·意式·美式）/ 中文词库 60+ / 英文词库 49 / 查询模板 12 条 / 家具特定调研源 8 组 / 待验证 6 项 |
| painting-calligraphy | 书画/字画 | heritage/07_painting | **正式包 v1（2026-10-07 用户拍板转正式）** | 四体系（古代/近现代/当代水墨/书法墨迹）/ 中英词库 / 查询模板 5 条 / 拍行·雅昌专属源 / 待验证 3 项 |
| watches | 腕表/钟表收藏 | heritage/08_watches | **正式包 v1（2026-10-07 用户拍板转正式）** | 四体系（瑞士制表/独立制表/德日表/古董表）/ 中英词库 / 查询模板 5 条 / Chrono24·Phillips 专属源 / 待验证 2 项 |
| spirits | 名酒收藏（茅台×威士忌） | heritage/09_spirits | **正式包 v1（2026-10-07 用户拍板转正式）** | 双体系（中国陈年白酒 × 苏格兰·日本威士忌）/ 中英词库 / 查询模板 5 条 / 苏富比 Distilled·老酒专场专属源 / 待验证 2 项 |
| agarwood-incense | 沉香/香道 | heritage/10_agarwood | **正式包 v1（2026-10-07 用户拍板转正式）** | 三体系（中国香道/日本香道/中东 Oud）/ 中英词库 / 查询模板 5 条 / **新华指数官方价格指数** / 待验证 4 项 |
| western-antiques | 西洋古董·欧洲装饰艺术 | heritage/06_western | **正式包 v1（2026-10-07 用户拍板转正式，补位西方体系）** | 三体系（欧洲银器/装饰艺术·古董家具/外销艺术品）/ 中英词库 / 查询模板 4 条 / 博物馆特展·1stdibs 专属源 / 待验证 2 项 |

> **当前主线（2026-10-07 用户拍板：10 个行业包全部正式）**：鉴藏总域下**已建 10 个行业包全部转正式**——珠宝/翡翠（主包）、陶瓷/古玩·古董（正式，含陶瓷手串与杂项器物）、家具（正式）、书画/腕表/名酒/沉香/西洋古董（正式）；各包对应监控仓 `场景应用/<行业>/` 场景实例已建。东方/西方体系（05/06）中 06 已由西洋古董补位。待验证项随监控实测回填。

### 主包使用指引

1. **命中即优先**：调研/监控诉求涉及珠宝、翡翠 → 直接用对应包（体系矩阵→专属源→词库→模板），不走泛搜索。
2. **驱动监控**：主包的中英词库与查询模板可直接供监控仓（trend-radar）渠道矩阵与监控对象使用——监控"查什么"从包内体系矩阵取，监控"怎么查"从包内模板取。
3. **回填迭代**：每次调研/监控产生的新高频词、新来源、模板实测结果（哪个操作符失效）→ 回填对应包，标来源档位与日期。
4. **跨包复用**：主包共享通用维度与渠道目录；翡翠的鉴定分级（NGTC）与珠宝包鉴定行复用，陶瓷古瓷拍卖复用古玩体系（嘉德/保利/雅昌），不重复维护。

---

## 通用维度：按文明/市场体系细分（所有包共用的方法论）

> **适用判断**：凡**有强烈文化/地域体系差异的消费品类**（家具/服装/陶瓷/茶/香/纺织/灯具/工艺品/珠宝/古玩……）都适用本维度——"XX"不是一个统一市场，调研先定位体系，再用体系专属源。无体系差异的品类（如纯功能件）不需要。

**四步法**：① 识别体系（有哪些文化/地域分支）→ ② 定各体系市场逻辑（消费动机/产业带/交易方式）→ ③ 找各体系专属调研源（协会/展会/市场/行业媒体/鉴定机构）→ ④ 建"定位速查"（先答我在哪个体系）。

**适用品类清单**（示例体系，建包时按四步法细化专属源）：

| 品类 | 典型体系分支 |
|---|---|
| **家具** | 中式(明清古典·新中式)/ 日式(和风·侘寂·Japandi)/ 北欧(丹麦现代)/ 意大利(高端设计)/ 美式(传统·现代)/ 伊斯兰(阿拉伯·波斯) |
| 服装/服饰 | 汉服/和服/印度纱丽/中东长袍/西方高定/非洲织物 |
| 陶瓷/瓷器 | 中国五大名窑/日本有田烧·九谷烧/欧洲 Meissen·Wedgwood·Limoges/中东 |
| 茶/茶器 | 中国茶/日本茶道/英式下午茶/摩洛哥薄荷茶 |
| 香/香水 | 中国香道/日本香道/中东焚香/西方香水 |
| 纺织品/地毯 | 波斯地毯/土耳其/中国丝绸/印度纱丽/北欧织物 |
| 灯具 | 中式宫灯/欧式水晶灯/日式纸灯/北欧极简灯 |
| 工艺品 | 刺绣/漆器/景泰蓝/木雕/银器 |
| 建筑/室内设计 | 东方园林/日式/北欧/地中海/伊斯兰 |
| 珠宝/古玩 | 见下（jewelry-ai 包 §6 实例） |

### 家具（已建正式包，见文末 `## 包：furniture`）

> 原"示范：家具"段已于 2026-10-07 升级为正式包（六体系双轨：收藏轨=明清古典拍卖 / 消费轨=新中式·北欧·日式·意式·美式日常家具），正文见文末。本通用维度表仅保留体系分支速览：中式(明清古典·新中式)/ 日式(和风·侘寂·Japandi)/ 北欧(丹麦现代)/ 意大利(高端设计)/ 美式(传统·现代)/ 伊斯兰(阿拉伯·波斯)。

---

## 包：jewelry-ai（珠宝营销 × 珠宝AI）

> v1 由"多 AI 群策群力"（Gemini/ChatGPT/Claude/Grok/DeepSeek）+ 监控仓《搜索方法论 v2》合并沉淀；v2（2026-10-06）新增"珠宝特定调研源"8 组（Rapaport 价格指数/培育钻数据/拍卖趋势/产业带批发市场/行业媒体/鉴定机构/黄金价格/香港贸易）；v3（2026-10-06）新增"按文明/市场体系细分"8 体系（中华/印度/日本/东南亚/中东/西方/古埃及古物/古玩收藏，各带专属调研源与市场逻辑，2026-10 多源验证）。
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

### 6. 按文明/市场体系细分（珠宝实例 · 通用方法论见本文件"通用维度"章节）

> **核心认知**：珠宝按文化体系分 7 大体系，材质/工艺/市场逻辑/调研源完全不同。**调研先定位体系**，再用对应专属源——用"通用珠宝"词库搜遍所有体系会漏掉体系专有信息源。

| 体系 | 代表品类/工艺 | 市场逻辑 | 专属调研源（强需求） | 社交/媒体主渠道 |
|---|---|---|---|---|
| **中华体系** | 翡翠/和田玉/黄金(古法金·花丝·錾刻)/淡水珍珠/苗银/景泰蓝/点翠 | 黄金保值+婚嫁刚需(三金)+直播电商+水贝产业带 | 水贝批发市场 / NGTC / 中国黄金报 / 宝玉石周刊 / 上海金交所 | 抖音 / 小红书 / 得物 / 视频号 |
| **印度体系** | Kundan/Meenakari 镶嵌 / 苏拉特钻石加工 / 斋浦尔彩宝 / 孟买金饰 | 宗教+婚礼+黄金储蓄；全球最大钻石切割(90%)与彩宝加工中心 | **GJEPC**（政府背书出口注册商清单）/ **IIJS 展会**（孟买旗舰 B2B）/ 苏拉特·斋浦尔产业带 / Grand View 印度珠宝报告(2025: 8.69 千亿卢比→2033: 14.2 千亿, CAGR 6.5%) | Instagram / LinkedIn(出口商) / X |
| **日本体系** | Akoya 珍珠 / Mikimoto / TASAKI / 和风金工 / 簪 | 珍珠高端+精工+内敛审美；Akoya 供给限制+日元弱势影响价格 | Mikimoto·TASAKI 官方 / Mordor·Ken Research 珍珠报告(亚太 2025 $6.2B→2031 $13.5B, CAGR 13.8%) / CIBJO 珍珠报告 / GIA 珍珠产业文献 | Instagram(品牌美学) / X |
| **东南亚体系** | 缅甸翡翠(帕敢)/ 曼谷彩宝加工 / 越南银饰 / 印尼银器 | 原料产地+加工中心 | 曼谷 GIT(泰国宝石学院) / 曼谷产业带 / 缅甸翡翠矿区动态 | Instagram / TikTok / Facebook(本地) |
| **中东/伊斯兰** | 黄金投资饰 / 迪拜黄金街 / 高净值定制 | 黄金投资属性+免税市场+宗教规范 | 迪拜黄金街 / GIA 中东 / JCK 中东报道 | Instagram(奢侈品) / LinkedIn |
| **西方体系** | 钻石订婚戒(bridal)/ 高级珠宝(Cartier·VCA·Tiffany)/ Art Deco·Georgian 时期 | 品牌溢价+订婚文化+时尚趋势 | Rapaport / JCK / 苏富比·佳士得 / De Beers 动态 / GIA | Instagram / Pinterest / Reddit(r/EngagementRings) |
| **古埃及/地中海古物** | 圣甲虫 / 荷鲁斯之眼 / 费昂斯琉璃 / 黄金面具 | 古董收藏+博物馆/仿古市场 | 大英博物馆·卢浮宫藏品研究 / 苏富比古物部 / 学术期刊 | Instagram(博物馆) / Reddit 古物版 |
| **古玩/古董体系**（跨文明收藏投资向） | 高古玉/明清玉/老银/蜜蜡天珠/藏饰/瓷器杂项 | 收藏投资+鉴定断代+拍卖市场 | **嘉德·保利·西泠·朵云轩**（2025 文物艺术品成交：嘉德 28.4 亿/市占 22.1%、保利 23.7 亿/18.4%、西泠 11.8 亿）/ **雅昌艺术网**(auction.artron.net 拍卖图录) / 潘家园 / 古玉研习社(7see.com) | 抖音鉴宝 / 小红书收藏圈 / 贴吧 |

**定位速查**（先答"我在哪个体系"再用专属源）：
- 门店卖黄金/翡翠 → 中华体系 → 水贝 / NGTC / 中国黄金报
- 做钻石贸易/对接加工 → 印度体系(供给) + 西方体系(消费) → GJEPC / Rapaport / 苏富比
- 珍珠品类 → 日本体系 → Mikimoto / Mordor 珍珠报告
- 古董收藏/古玩 → 古玩体系 → 嘉德·保利 / 雅昌 / 潘家园
- 仿古埃及风格 → 古物体系 → 博物馆馆藏研究 / 苏富比古物部

> ⚠️ 合规提示（古玩体系特有）：正规拍行（嘉德/保利/西泠）不收前期费用、只在成交后收佣金；"送拍要先交费"的机构是典型骗局（2023 年北京市监通报查处 37 家，涉案超 1.2 亿）——调研古玩渠道时优先官方拍行，勿信主动联系收前期费的"代拍"。

### 7. 待验证/待扩容（诚实标注）

- 词库 v1 为核心版，离 300+300 远期目标差一个量级；随每期监控使用把新增高频词回填本包（每周）
- 各模板"实测可用性"（哪个操作符在哪个工具不生效）执行时记录，回写本节
- 数字人/口播/真人出镜类内容的风控边界（Seedance 2.0 系列暂不支持真人人脸正脸/口播）——涉及视频生成时注意

---

## 包：ceramics（陶瓷 × 瓷器 · 鉴藏总域 03_ceramics）

> v1（2026-10-06 建包）；**v2（2026-10-07 用户拍板转正式 + 新增"陶瓷手串"品类）**。按通用四步法建体系矩阵；陶瓷手串=瓷珠文玩线（茶器衍生+文玩佩戴），与珠宝"手串/串珠"（金银/翡翠/玛瑙珠串=装饰佩戴线）、沉香"手串客群"（木质香珠=香道盘玩线）交叉不重复，三者材质与消费场景不同。

### 1. 体系细分（通用四步法）

| 体系 | 代表 | 专属调研源（强需求） | 主渠道 |
|---|---|---|---|
| **中华 · 艺术瓷/名窑** | 景德镇(青花·粉彩·颜色釉)/醴陵(釉下五彩) | 景德镇国际陶瓷博览会 / 醴陵国际陶瓷产业博览会（2026-09-29~10-03）/ 智研咨询工艺陶瓷报告 / 雅昌·嘉德·保利（古瓷拍卖） | 抖音(开窑/手作) / 小红书(茶器) |
| **中华 · 日用瓷/产业瓷** | 潮州(日用瓷·智能卫浴·出口)/佛山(建筑陶瓷·卫浴) | **佛山陶博会/CERAMBATH**（第44届 893 家企业·50 万㎡·3 万款新品；第45届 2026-10）/ 潮州陶瓷产业协会 / 广交会(140 届 2026-10) | 抖音 / 1688 / 广交会线上 |
| **陶瓷手串（瓷珠文玩线）** | 青花瓷珠/汝窑珠/钧窑珠/建盏珠/紫砂珠/粉彩珠/瓷烧珠/老瓷片珠 | 景德镇珠坊源头（1688）/ 抖音文玩手串直播 / 文玩电商（得物·微拍堂）/ 雅昌（老瓷片珠收藏） | 抖音(手串直播) / 小红书(手串种草) / 1688(源头) |
| **日本体系** | 有田烧/九谷烧/备前烧 | 日本陶瓷协会 / IFFT / 京瓷·香兰社等品牌体系 | Instagram / X |
| **欧洲体系** | Meissen/Wedgwood/Limoges | 品牌官方 / 苏富比·佳士得（欧洲瓷器拍卖）/ 博物馆馆藏 | Instagram / Pinterest |
| **伊斯兰** | 伊兹尼克陶 | 博物馆馆藏 / 学术期刊 | Instagram |

### 2. 核心词库

- **中文**：陶瓷、瓷器、景德镇、青花瓷、粉彩、颜色釉、釉下五彩、醴陵、潮州瓷、日用瓷、艺术瓷、茶器、建盏、汝窑、官窑、哥窑、钧窑、定窑、五大名窑、古瓷、瓷片、开窑、柴窑、气窑、贴花、手绘
- **中文（陶瓷手串专组）**：陶瓷珠、瓷珠、青花珠、汝窑珠、钧窑珠、建盏珠、紫砂珠、粉彩珠、瓷烧珠、陶瓷手串、老瓷片珠、碎瓷珠、瓷片项链、珠坊、瓷珠源头
- **英文**：ceramics, porcelain, china ware, jingdezhen, celadon, blue and white, famille rose, kiln, glaze, tea ware, antique porcelain, Meissen, Wedgwood, Limoges, Arita, Kutani
- **英文（陶瓷手串专组）**：ceramic bead bracelet, porcelain beads, jingdezhen beads, celadon beads, kiln-fired beads, ceramic mala, porcelain bead necklace

### 3. 查询模板（6+2 条）

| 监控问题 | 查询串 |
|---|---|
| 名窑/艺术瓷动态 | `(景德镇 OR 醴陵 OR 汝窑) (陶瓷 OR 瓷器 OR 茶器) (新品 OR 市场 OR 拍卖) 2026` |
| 产业带/出口 | `(潮州 OR 佛山) (陶瓷 OR 卫浴) (出口 OR 产业 OR 博览会) 2026` |
| 古瓷拍卖 | `(瓷器 OR 陶瓷) (拍卖 OR 成交) (嘉德 OR 保利 OR 苏富比) 2026` |
| 茶器/文玩趋势 | `(建盏 OR 紫砂 OR 茶器) (趋势 OR 收藏 OR 市场) 2026` |
| 海外市场 | `(porcelain OR ceramics OR jingdezhen) (market OR auction OR trend) 2026` |
| 展会情报 | `(陶瓷博览会 OR CERAMBATH OR 醴陵) (2026 OR 展销)` |
| **陶瓷手串行情/市场** | `(陶瓷珠 OR 瓷珠 OR 青花珠) 手串 (市场 OR 价格 OR 直播 OR 文玩) 2026` |
| **陶瓷手串海外/收藏** | `(ceramic bead OR porcelain bead) (bracelet OR jewelry OR market) after:2025-06-01` |

### 4. 渠道补充（陶瓷手串特有）

- **国内**：抖音（文玩手串直播：开窑珠坊/手工瓷珠主播）；小红书（手串种草/佩戴分享）；1688（景德镇·潮州珠坊源头厂，按"陶瓷珠/瓷珠"检索）；微拍堂/得物（文玩电商）；雅昌（老瓷片珠/古董珠收藏拍场）
- **海外**：Instagram / Pinterest（ceramic bead 手工珠饰趋势）；Etsy（手工瓷珠商家，供货源/定价参照）
- **边界**：与珠宝包"手串/串珠"（金银/翡翠/玛瑙=装饰佩戴线）交叉不重复；与沉香包"手串客群"（木质香珠=香道盘玩线）交叉不重复——陶瓷手串定位瓷珠文玩线（茶器衍生+文玩佩戴），关键词各自维护

### 5. 待验证/待扩容（陶瓷手串）

- 陶瓷手串市场规模/头部主播名单暂无权威数据源（🟡，直播电商口径待实测）
- 1688 珠坊源头厂清单与价格锚点待录入（⚪）
- 老瓷片珠收藏拍场数据（雅昌检索实测）待回填

---

## 包：antiques（古玩·古董 · 鉴藏总域 03_antiques · 杂项器物总包）

> v1（2026-10-07 用户拍板转正式）。古玩·古董总包=**杂项器物支线**（本包正文）+ 陶瓷支线（指针→ceramics 包，不重复）+ 宗教艺术支线（佛造像/唐卡，拍行同嘉德·保利·匡时）+ 文人收藏支线（古籍/碑帖）。此前标"不重复建包"的文玩杂项（鼻烟壶/铜器/漆器/竹木牙角/文房）**并入本包杂项器物支线，不再丢弃**。

### 1. 体系细分（杂项器物四步法）

| 体系 | 代表 | 市场逻辑 | 专属调研源（强需求） | 主渠道 |
|---|---|---|---|---|
| **鼻烟壶** | 料器/玻璃、陶瓷、玉石、珐琅、竹木鼻烟壶 | 经典古玩门类，材质跨度大、藏家客群与珠宝/沉香重叠 | 嘉德/保利/西泠"文房雅玩"专场 / 雅昌（鼻烟壶图录）/ 潘家园 | 抖音鉴宝 / 小红书收藏圈 |
| **宋代及历代器物** | 高古玉/明清玉（复用 jewelry 古玩体系）、铜器（青铜/宣德炉）、漆器（剔红）、竹木牙角 | 收藏投资+断代鉴定；拍行与藏家共享古玩生态 | 嘉德/保利"瓷杂"专场 / 雅昌 / 华夏收藏网 | 抖音鉴宝 / 贴吧 / 知乎 |
| **文房器物** | 笔筒、砚台、印章、镇纸、臂搁 | 文人收藏、小众高价、印学社群 | 西泠印社拍卖 / 朵云轩 / 荣宝斋 | 微信 / 知乎 |
| **宗教艺术**（支线） | 汉传/藏传佛造像、唐卡 | 三体系（汉传/藏传/尼藏）真实存在，拍行共享 | 嘉德/保利/匡时佛教艺术专场 | 抖音 / 小红书 |
| **文人收藏**（支线） | 古籍善本、碑帖 | 学术性强、流动性低 | 西泠/嘉德古籍专场 | 微信 / 知乎 |

### 2. 核心词库

- **中文**：鼻烟壶、烟壶、料器、玻璃鼻烟壶、珐琅鼻烟壶、陶瓷鼻烟壶、玉石鼻烟壶、铜器、青铜器、宣德炉、铜炉、漆器、剔红、犀皮漆、竹木牙角、竹雕、牙雕、核雕、文房、笔筒、砚台、端砚、印章、田黄、鸡血石、镇纸、臂搁、高古玉、明清玉、香炉、佛造像、唐卡、古籍善本、碑帖、拓片
- **英文**：snuff bottle, inside-painted snuff bottle, enamel snuff bottle, archaic jade, bronze vessel, bronze censer, lacquerware, carved lacquer, bamboo carving, ivory carving, literati objects, inkstone, duan inkstone, seals, field yellow stone, censer, buddhist sculpture, thangka, rare books, rubbings

### 3. 查询模板（4+ 条）

| 监控问题 | 查询串 |
|---|---|
| 鼻烟壶行情/收藏 | `(鼻烟壶 OR 料器) (拍卖 OR 收藏 OR 鉴定) 2026` |
| 高古玉/文房器物 | `(高古玉 OR 宋代玉器 OR 文房 OR 笔筒 OR 砚台) (市场 OR 拍卖 OR 行情) 2026` |
| 铜器/漆器杂项 | `(宣德炉 OR 铜器 OR 漆器 OR 剔红) (拍卖 OR 收藏 OR 行情) 2026` |
| 海外杂项拍场 | `(snuff bottle OR archaic jade OR lacquerware) (auction OR market) after:2025-06-01` |
| 宗教艺术/文人支线 | `(佛造像 OR 唐卡 OR 古籍善本) (拍卖 OR 专场 OR 成交) 2026` |

### 4. 渠道补充（杂项特有）

- 嘉德/保利/西泠"瓷杂""文房雅玩"专场（拍行官网图录）；雅昌艺术网（auction.artron.net，杂项成交可回溯）；华夏收藏网（cang.com）；潘家园/琉璃厂（线下市场）；抖音鉴宝（杂项鉴定号）；小红书收藏圈（鼻烟壶/文房种草）；贴吧（古玩杂项吧）
- **复用不重复**：古瓷→ceramics 包；玉器→jewelry 包古玩体系；通用社交选型→channel-directory §9.3

### 5. 待验证/待扩容（杂项）

- 鼻烟壶专场成交数据/头部藏家名单待录入（🟡）
- 宋代器物各门类（铜器/漆器/竹木牙角）市场规模无统一权威数据（⚪）
- 抖音杂项鉴宝头部账号清单待实测

---

## 包：jadeite（翡翠）

> v1（2026-10-06）：三主包之一。翡翠核心是"产地+产业带"体系（不同于珠宝的文明体系）。

### 1. 体系细分（产业带 + 产地双维度）

| 环节/体系 | 代表 | 专属调研源（强需求） | 数据要点 |
|---|---|---|---|
| **原石产地** | 缅甸帕敢（老坑料）/ 木姐口岸 | 缅甸公盘动态 / 矿区新闻（减产·封矿） | 帕敢浅层优质矿源枯竭，开采深入地下数百米 |
| **进口/公盘** | 云南瑞丽(姐告)/盈江/平洲 | **缅甸珠宝公盘**（2026-07 首次落地瑞丽，60 年首出国门）/ 平洲珠宝玉器协会 / 瑞丽市宝玉石协会 | 95% 缅甸翡翠经云南口岸入华；德宏经营户 4.5 万+/从业 10 万+；2025 瑞丽珠宝直播销售 115.9 亿(+16.3%) |
| **加工集散** | 揭阳阳美(亚洲玉都)/平洲/四会 | 揭阳玉都（pzyq.org 平洲协会）/ 四会玉器城 / 博研咨询 2026 翡翠报告 | 缅甸中高档原料 ~80% 流向揭阳；全国 90%+ 中高档翡翠饰品产自揭阳，年交易 300 亿+；平洲+盈江占国内缅料公盘 53%+ |
| **鉴定/分级** | NGTC / 国检翡翠分级 | NGTC 官方 | 种水色分级标准（冰种/玻璃种/帝王绿等术语） |
| **消费/直播** | 抖音翡翠直播 / 淘宝直播 | 飞瓜·蝉妈妈（翡翠品类）/ 抖音电商翡翠类目 | 直播是翡翠主要成交场景 |

### 2. 核心词库

- **中文**：翡翠、玉石、缅甸玉、帕敢、老坑、种水、玻璃种、冰种、糯种、豆种、帝王绿、阳绿、飘花、紫罗兰、春带彩、满绿、翠根、公盘、赌石、明料、半明料、毛料、揭阳、阳美、平洲、四会、瑞丽、姐告、直播、镶嵌、蛋面、手镯、观音、佛公
- **英文**：jadeite, jade, Burmese jade, nephrite, rough jade, jadeite boulder, jade market, jade auction, imperial green, ice jade, glass jade

### 3. 查询模板（6 条）

| 监控问题 | 查询串 |
|---|---|
| 公盘/原料动态 | `(翡翠 OR 玉) (公盘 OR 毛料 OR 原料) (缅甸 OR 瑞丽 OR 平洲) 2026` |
| 产业带动态 | `(揭阳 OR 阳美 OR 平洲 OR 四会 OR 瑞丽) 翡翠 (加工 OR 产业 OR 直播) 2026` |
| 市场/价格 | `(翡翠) (市场 OR 行情 OR 价格 OR 下跌 OR 回暖) 2026` |
| 直播/电商 | `(翡翠) 直播 (销售额 OR 增长 OR 案例) 2026` |
| 拍卖/收藏 | `(翡翠 OR 玉器) (拍卖 OR 成交) (嘉德 OR 保利 OR 苏富比) 2026` |
| 矿区/供给 | `(缅甸 OR 帕敢) (翡翠 OR 玉石) (矿区 OR 封矿 OR 减产) 2026` |

### 4. 待验证/待扩容

- 翡翠价格指数（目前无统一权威指数，行情靠公盘+市场新闻跟踪——待确认是否有新指数源）
- 揭阳/平洲/瑞丽各市场最新规模数据随公盘与年报更新
- 翡翠直播品类数据（飞瓜/蝉妈妈口径）待实测

---

## 包：furniture（家具 × 家居 · 鉴藏总域 04_furniture）

> v1（2026-10-07）：由"示范：家具（用户点名，已展开）"段升级为完整行业包。结构对齐 jewelry-ai 包。
> **总域定位**：家具是"消费零售轨"（新中式/北欧/日式/意大利/美式日常家具）与"收藏投资轨"（明清古典家具/黄花梨/紫檀拍卖）双轨品类，调研先定位体系与轨道，再用专属源。
> 来源标注四档：✅已查证（官方一手可回源）｜🔶经搜索补充（≥2 独立来源互证）｜🟡一方说法（单源降档）｜⚪未经核实（单列待查）。

### 1. 体系细分表（六体系，双轨定位）

| 体系 | 代表（品牌 / 产区 / 风格） | 市场逻辑 | 专属调研源（强需求） | 主渠道 |
|---|---|---|---|---|
| **中式 · 明清古典**（收藏轨） | 黄花梨/紫檀/红木家具；苏作/京作/广作；产区：福建仙游、浙江东阳、河北涞水（大城）、广东中山大涌 | 收藏投资+保值叙事+材质断代；交易走拍卖与红木市场；产业带在 CNFA 产业集群名单内 ✅ https://www.cnfa.com.cn/aboutcolonys.html?ord=asc | 雅昌艺术网拍卖图录 / 嘉德·保利古典家具专场 / 仙游·东阳红木产业带协会 | 抖音（红木鉴宝/工厂探店）/ 小红书（新中式美学） |
| **中式 · 新中式**（消费轨） | 梵几、上下 ShangXia、吱音等；现代简约+明式线条 | 国潮消费+年轻客群+全屋定制；产业带：江西南康（2025 营收 2900 亿元、全国最大实木基地 ✅ https://wap.chinanews.com/wap/detail/chs/zw/10629648.shtml ）；中式风格占成套家具偏好 15% ✅（尚普 PDF，见下） | CNFA / CISS·Furniture China / 南康家具博览会 / 雅昌（古典端） | 抖音 / 小红书 |
| **日式**（和风 · 侘寂 · Japandi） | MUJI、Karimoku、天童木工；静冈/旭川产区 | 极简收纳+原木；日本家具市场 2026 $23.57B→2031 $26.51B CAGR 2.38% ✅ https://www.mordorintelligence.com/industry-reports/japan-furniture-market ；Japandi 为欧美跨界趋势 | Interior Lifestyle Tokyo（2026-06-10~12，460 展商 ✅ https://interiorlifestyle-tokyo.jp.messefrankfurt.com/tokyo/en/facts-figures.html ）/ JAPAN FURNITURE SHOW（2026-11-03 ✅ https://japanfurniture.jp/en/ ） | Instagram / X / 小红书 |
| **北欧**（丹麦现代） | Fritz Hansen、HAY、Muuto、Artek、&Tradition | 设计品牌溢价+经典款长尾；北欧风格占成套家具偏好 22% ✅（尚普 PDF） | Stockholm Furniture Fair（下届 2027-02 🟡 https://globalwood.org/fair/fair.htm ）/ Salone del Mobile 北欧馆 / 品牌官方 | Instagram / Pinterest |
| **意大利**（高端设计） | B&B Italia、Poltrona Frau、Cassina、Flexform、Minotti；Brianza 产区 | 设计驱动+Made in Italy 溢价；意大利家具市场 2026 $16.74B→2031 $19.86B CAGR 3.48% ✅ https://www.mordorintelligence.com/industry-reports/italy-home-furniture-market | **Salone del Mobile.Milano**（2026 第 64 届 4.21~26，316,342 参观者/167 国，1,900 品牌 ✅ https://areapress.salonemilano.it/26_april_26_en/Final_Press_Release_Salone_del_Mobile_Milano_2026_ZH.pdf ）/ Pambianco / Mordor | Instagram / Dezeen / Pinterest |
| **美式** | Ethan Allen、Restoration Hardware、Arhaus、Ashley | 北美 B2B 贸易展主导；美式风格占成套家具偏好 12% ✅（尚普 PDF） | **High Point Market**（Fall 2026：10.17~21 ✅ https://www.highpointmarket.org/about ；Spring 04-25~29 🔶）/ Furniture Today | Instagram / Pinterest / Facebook |
| **伊斯兰** | 中东高净值奢华室内定制；波斯/阿拉伯纹样 | 高净值+视觉奢华+免税转口；迪拜为设计转口枢纽 | Dubai Design Week / INDEX Dubai（⚠️ 2026/2027 档期未核实 ⚪） | Instagram / LinkedIn |

> **中国消费风格分布基准**（尚普咨询《2026 年 1~10 月成套家具市场洞察报告》✅ https://survey.shangpu-china.com/uploadfile/202601/795fead3832ec46.pdf ）：现代简约 32% > 北欧 22% > 中式 15% > 美式 12% > 工业风 5% > 复古 3%。**线上渠道结构（同 PDF）**：抖音 27.6 亿元占 ~65%、天猫 ~21%、京东 ~6%——抖音为家具线上第一渠道 ✅。
> **中国产业地位**：世界第一大家具生产国、出口国、消费国 ✅ https://www.cnfa.com.cn/infonews36.html 。

### 2. 核心词库（四维分类）

**中文（60+）**
- A 行业词：家具、实木家具、板式家具、软体家具、沙发、床垫、红木、黄花梨、紫檀、新中式、北欧风、日式侘寂、中古风、美式、全屋定制、整装、产业带、南康、乐从、厚街、蠡口、家博会、名家具展、米兰展、高点展
- B AI/技术词：AI 设计、AIGC、3D 云设计、酷家乐、三维家、虚拟样板间、AR 摆场、数字人直播、AI 渲染、家居 3D 建模、空间设计、AI 生成图、智能体、大模型、电商素材生成
- C 营销场景词：直播带货、抖音家具、小红书种草、门店获客、同城流量、私域、投流、爆款、新品发布、联名、全屋定制套餐、以旧换新、整装套餐、案例复盘
- D 信号/意图词：拍卖成交、行情、价格、财报、展会报告、白皮书、市场规模、趋势、数据、增长、融资、战略合作、出口、关税、环保 ENF 级、E0 级

**英文（49，统一小写命名）**
- A industry：furniture, home furniture, solid wood furniture, upholstery, sofa, mattress, chinese antique furniture, huanghuali, new chinese style, japandi, wabi-sabi, scandinavian design, danish modern, italian furniture, mid-century modern, home decor, interior design
- B ai-tech：ai design, generative ai, 3d room planner, ar furniture placement, virtual staging, digital human, ai rendering, room visualization, ai generated imagery, spatial design, ai agent
- C marketing：furniture marketing, livestream commerce, seeding, dtc furniture, showroom, influencer, e-commerce, product launch, case study
- D signal：market report, trend, auction result, sales, earnings, pilot, partnership, trade fair, high point market, salone del mobile, market size, growth forecast

### 3. 查询模板（12 条，直接粘贴）

| 监控问题 | 查询串 |
|---|---|
| 国内产业动态 | `(家具 OR 家居) (产业 OR 工厂 OR 出口 OR 关税) 2026` |
| 产业带动态 | `(南康 OR 乐从 OR 厚街 OR 蠡口 OR 崇州) (家具 OR 产业) 2026` |
| 国内展会情报 | `(CIFF OR 家博会 OR "Furniture China" OR 名家具展) (2026 OR 2027) (时间 OR 回顾 OR 新品)` |
| 海外展会情报 | `(Salone del Mobile OR "High Point Market") (2026 OR 2027) (visitors OR exhibitors OR trend)` |
| 拍卖收藏行情 | `(黄花梨 OR 紫檀 OR 明清家具 OR 古典家具) (拍卖 OR 成交) (嘉德 OR 保利 OR 苏富比) 2026` |
| 海外风格趋势 | `(furniture OR "home decor") (trend OR style OR collection) after:2026-01-01` |
| AI/数字化应用 | `(家具 OR 家居) (AI OR 数字人 OR 3D云设计 OR AR摆场) (案例 OR 落地) -招聘 -培训` |
| 价格行情 | `(家具 OR 红木 OR 木材) (价格 OR 行情 OR 涨跌) 2026` |
| 直播电商动态 | `(家具 OR 家居) 直播 (抖音 OR 带货 OR GMV OR 案例) 2026` |
| 风格趋势（新中式/Japandi） | `(新中式 OR 中古风 OR Japandi OR 侘寂) (家具 OR 家居) (趋势 OR 品牌) 2026` |
| 行业报告 | `(furniture OR 家具) (market OR report OR 趋势) filetype:pdf 2026` |
| 海外 AI 落地 | `(furniture OR "home furnishing") (AI OR "artificial intelligence" OR "virtual staging") (case study OR launch) after:2025-06-01` |

### 4. 渠道补充（家具特有）

**国内**：协会=中国家具协会 CNFA ✅ https://www.cnfa.com.cn/ ；展会=CIFF 上海（2026-09-05~08 虹桥，21 万㎡/1,200+ 品牌 ✅ https://www.ciff-sh.com/ ）、Furniture China（第 31 届 2026-09-08~11 浦东 SNIEC ✅ https://reg.furniture-china.cn/zh-cn/user/login ）、东莞名家具展（厚街）、成都国际家具工业展、广州定制家居展（每年 3 月 ✅ http://www.chfgz.com ）；媒体=家具在线、家居邦、77 度、戴蓓 Talk、泛家居圈、大材研究 ✅ https://www.cbdfair-sh.com/Cn/Index/listView/catid/21.html ；数据=蝉妈妈/飞瓜/新红（家具类目）、巨量算数、尚普/博研公开报告（二手机构，降档引用）。
**海外**：展会=Salone del Mobile（4 月）/ High Point Market（4 月、10 月）/ Interior Lifestyle Tokyo（6 月）/ Stockholm Furniture Fair（2 月）/ INDEX Dubai（中东）；媒体=Dezeen（✅ https://www.dezeen.com/design/furniture/ ）、Furniture Today、Interior Design、Wallpaper*、Pambianco；拍卖=国内嘉德·保利·西泠（古典家具专场）、海外苏富比·佳士得（Chinese furniture，如 Christie's 2026-04 石头书屋藏中国家具专题 ✅）；结构性判断：家具行业无类似 Rapaport 的全球统一权威机构，以展会主办方+行业媒体为核心数据源（🟡）。

### 5. 家具特定调研源（8 组）

| 调研目标 | 专有源（主） | 用途/证据 |
|---|---|---|
| 古典家具拍卖行情 | 嘉德·保利古典家具专场 + 雅昌图录 | 嘉德 2026 春拍"澄怀"专场 9487 万元/成交率 72% ✅ https://m.thepaper.cn/newsDetail_forward_33341969 ；保利 2026 春拍明黄花梨榻 2507 万元 ✅ https://amma.artron.net/observation_shownews.php?newid=1152438 |
| 产业带/货源动态 | CNFA 产业集群页 + 南康/乐从/厚街/蠡口新闻 | CNFA 名录（玉环/宁津/崇州/南康/普兰店+蠡口/厚街流通市场）✅；南康 2025 营收 2900 亿 ✅ |
| 展会风向 | 五大展会官方页 | 展前新品预告+展后媒体回顾=风格风向标；Salone 2026 官方终稿 ✅ |
| 海外市场规模 | Mordor Intelligence 国家报告 | 意大利 $16.74B→$19.86B ✅；日本 $23.57B→$26.51B ✅ |
| 线上渠道结构 | 尚普咨询成套家具 PDF | 抖音占 ~65%/天猫 ~21%/京东 ~6% ✅——抖音=家具线上第一渠道的直接证据 |
| 行业媒体 | Dezeen（海外）/ 家具在线·家居邦·77 度（国内） | 品牌新品、材料创新、产业带动态 |
| 红木鉴定/行情 | 雅昌艺搜拍品库（按"黄花梨"检索） | 实时拍品估价/成交=材质行情指针；嘉德秋拍黄花梨拍品在列 ✅ https://artso.artron.net/auction/search_auction.php?keyword=黄花梨 |
| AI 数字化落地 | 酷家乐/三维家 + 抖音电商学习中心 | 家具 AI 落地在"3D 云设计/AR 摆场/数字人直播"三场景（案例数待实测 🟡） |

### 6. 待验证/待扩容

1. Japandi "$4.2B/+23%" 仅单源（designsignal.ai 🟡）且与 Grand View 转引（CAGR 8.7%/2030 $15.6B 🟡）口径矛盾——引用必须降档，建议弃用或找原始报告回填
2. "西点展"名称/档期未确认（疑 WestEdge Design Fair ⚪）
3. INDEX Dubai / Dubai Design Week 2026/2027 档期未核实 ⚪
4. 家具无统一权威价格指数（同翡翠），行情靠拍卖+产业带新闻+报告跟踪 🟡
5. 国内家具电商大盘数据（如 5820 亿元/占零售 43.6%）来自博研咨询转引稿 🟡，不作精确引用
6. 词库/模板为核心 v1，随监控回填（中古家具/以旧换新/全屋智能等）

### 7. 家具场景×渠道匹配建议

| 场景 | 国内主 | 国内次 | 海外主 | 海外次 | 理由 |
|---|---|---|---|---|---|
| 新品趋势监控 | 小红书（购买决策引擎） | 抖音（发现引擎）；微信公众号 | Pinterest（高意图长尾，§9.3.2 家居行指定主渠道） | Instagram；Dezeen/ArchDaily | 家具重视觉决策：海外先 Pinterest 存图再 IG 看品牌；国内小红书种草实景图 |
| 价格行情 | 抖音（线上成交数据密） | 微信；知乎（避坑讨论=价格敏感度信号） | X（木材/关税实时） | Reddit（r/furniture） | 价格要"数据+情绪"双轨：抖音占线上 ~65% ✅ 尚普 PDF；海外宏观实时性要求高 |
| 产业带动态 | 抖音（工厂探店/源头直播） | 微信（协会通告）；脉脉 | LinkedIn（B2B 出口决策者） | Facebook（本地社区） | 产业带=B2B 供给侧情报；海外对接买家属 B2B（§9.3.2 B2B 行） |
| 拍卖收藏 | 雅昌/嘉德·保利官网 | 抖音（鉴宝/拍卖切片）；微信公众号 | 苏富比/佳士得官网 | Instagram（拍行账号） | 收藏轨成交信息靠拍行官网+雅昌（§5），社交只做传播面 |
| 海外风格风向 | 小红书（本土化译介） | B站（家居改造长视频） | Pinterest + Instagram | Dezeen；YouTube | 视觉趋势采集：Pinterest 主渠道；日式体系加 X（日本渗透率极高 §9.3.1） |
| AI/数字化落地 | 抖音（数字人直播案例） | 小红书（AI 出图对比）；B站（教程） | LinkedIn（家具 SaaS/3D 工具厂商）+ Reddit | X；YouTube | AI 落地=B2B 工具+营销案例混合：国内案例在抖音/小红书，海外工具厂商在 LinkedIn |

---

## 包：painting-calligraphy（书画/字画 · 07_painting）

> v1（2026-10-07 用户拍板转正式）。中国艺术品拍卖第一大品类，高净值藏家与珠宝客群同源。详细论证见调研中间件 `supplement-industries.md` §2（监控仓 01_渠道矩阵/行业细分表 §3.6、场景应用/painting/）。

- **市场锚点**：嘉德 2025 春拍总成交 16 亿 ✅ https://www.thepaper.cn/newsDetail_forward_30904564 ；保利 2025 春拍书画板块 +74.5%、傅抱石《柳溪仕女》2415 万 ✅ http://epaper.zqrb.cn/html/2025-10/18/content_1189493.htm
- **四体系**：中国古代书画（嘉德古代夜场/故宫上博馆藏研究）/ 中国近现代书画（保利/荣宝斋，收藏投资主战场）/ 当代水墨（ART021/画廊周）/ 书法墨迹（西泠印社/朵云轩）
- **词库要点**：书画、字画、国画、古代书画、近现代书画、张大千、齐白石、傅抱石、册页、手卷、立轴、信札、碑帖、荣宝斋、西泠印社、嘉德、保利、雅昌；英文 Chinese painting / calligraphy / handscroll / evening sale / provenance / hammer price
- **查询模板**：`(书画 OR 字画 OR 国画) (拍卖 OR 成交) (嘉德 OR 保利 OR 西泠) 2026`；`(张大千 OR 齐白石 OR 傅抱石) (拍卖 OR 成交 OR 千万) 2026`；`(书画) (真伪 OR 作伪 OR 鉴定) 2026`
- **渠道匹配**：拍场成交→雅昌/拍行官网；鉴伪舆情→抖音鉴宝+知乎+Reddit(r/ChineseArt)；当代水墨→小红书+B站+Instagram+Artsy
- **待验证**：全年字画市场规模 128.6 亿（豆丁转引 AMMA 🟡 待以 AMMA 年报替换）

## 包：watches（腕表/钟表收藏 · 08_watches）

> v1（2026-10-07 用户拍板转正式）。硬奢回收增速最猛赛道，与珠宝共享"鉴定-回收-保值"叙事。详细论证见 `supplement-industries.md` §3（监控仓行业细分表 §3.7、场景应用/watches/）。

- **市场锚点**：2025 国内腕表回收约 491 亿、CAGR~30.5% 🔶 https://finance.sina.com.cn/tjhz/2026-09-15/doc-inirwmwe3680394.shtml.md ；2026H1 全球二手腕表 105 亿美元 +37.2% 🔶（同源）
- **四体系**：瑞士高级制表（劳力士/百达翡丽/爱彼，WatchBox/得物/腕表之家）/ 独立制表（F.P.Journe/GPHG/Only Watch）/ 德日表（Grand Seiko，X 日本表圈）/ 古董表怀表（拍行钟表部）
- **词库要点**：腕表、劳力士、百达翡丽、爱彼、江诗丹顿、理查德米勒、独立制表、Grand Seiko、二手表、回收、保值、公价、溢价、绿水鬼、鹦鹉螺；英文 wristwatch / Rolex / Patek Philippe / pre-owned / resale / secondary market / Chrono24
- **查询模板**：`(腕表 OR 名表) (行情 OR 价格 OR 涨跌) (劳力士 OR 百达翡丽) 2026`；`(watch OR Rolex OR Patek) (auction OR Sotheby's OR Christie's) after:2025-06-01`；`(independent watch OR GPHG OR Only Watch) 2026`
- **渠道匹配**：二级行情→腕表之家+得物+Chrono24+WatchBox；鉴定讨论→知乎+Reddit(r/Watches)；顶级拍场→Phillips+Sotheby's 钟表部
- **待验证**：Chrono24 价格指数免费可得性与查询语法 🟡；劳力士二手指数较 2022 峰值回落约 30% 仅单源 🟡

## 包：spirits（名酒收藏 · 09_spirits）

> v1（2026-10-07 用户拍板转正式）。中国陈年白酒 × 苏格兰/日本威士忌双体系，天然套用东方/西方框架；市场正处分化期（老酒量价齐跌 vs 顶级威士忌创纪录），监控价值最高。详细论证见 `supplement-industries.md` §4（监控仓行业细分表 §3.8、场景应用/spirits/）。

- **市场锚点**：苏富比香港 Distilled 2025 首拍 942 组/2000+ 瓶创香港烈酒拍卖纪录 ✅ https://www.sothebys.com/en/digital-catalogues/distilled-whisky-moutai-hk1612 ；嘉德春拍 576 瓶茅台 532 万港元 ✅ https://jiu.ifeng.com/c/8iRQd7vwp47 ；陈年茅台(30)得物破发一度 -25% ✅ https://news.qingdaonews.com/qingdao/2026-05/20/content_23735437.htm ；2026H1 日本威士忌指数回调 10.6% 🔶 https://scotchwhiskyinvestments.com/en/whisky-half-year-update-2026
- **双体系**：中国陈年白酒（嘉德/保利/西泠老酒专场+阿里/京东拍卖+得物行情）/ 苏格兰·日本威士忌（苏富比 Distilled+Scotch Whisky Investments 指数+Whisky Auctioneer）/ 干邑雅文邑（拍行附属品类）
- **词库要点**：茅台、陈年茅台、老酒、五粮液、威士忌、麦卡伦、山崎、轻井泽、干邑、路易十三、原箱、生肖酒、破发、量价齐跌；英文 whisky / Macallan / Yamazaki / Moutai / aged baijiu / investment whisky / single cask / hammer price
- **查询模板**：`(茅台 OR 老酒) (拍卖 OR 行情 OR 价格) 2026`；`(茅台 OR 年份酒) (得物 OR 破发 OR 倒挂) 2026`；`(whisky OR Macallan OR Yamazaki) (auction OR record) after:2025-06-01`
- **渠道匹配**：白酒→得物+阿里/京东拍卖+抖音酒商直播（国内市场封闭）；威士忌→Instagram+Sotheby's+Reddit(r/Scotch)+Telegram
- **待验证**：老酒市场规模 89.4 亿（豆丁 🟡 待替换）；茅台价格锚点需按电商平台实时核对

## 包：agarwood-incense（沉香/香道 · 10_agarwood）

> v1（2026-10-07 用户拍板转正式）。少有的官方挂牌价格指数品类（新华指数），手串客群与珠宝门店直接重叠。详细论证见 `supplement-industries.md` §5（监控仓行业细分表 §3.9、场景应用/agarwood/）。

- **市场锚点**：新华指数"中国沉香价格指数"——2026-04 中国沉香（手串）电商价格指数 730.80 点、均价 417.12 元/件 ✅ https://indices.cnfin.com/jgzs/wenzixiangqingye/detail/20260518/4414070_1.html ；2026-08 海南沉香（手串）制品指数单月 +19.23% ✅ https://m.cnfin.com/cy-lb/zixun/20260929/4476228_1.html ；全产业链超 300 亿、年增速 ~20% 🔶 http://news.qq.com/rain/a/20260421A01QP600
- **三体系**：中国香道/海南沉香（新华指数/澄迈香世界/抖音直播）/ 日本香道（伽罗/名香，外部可达性弱 🟡）/ 中东 Oud（agarwood.com 参考价 🟡）
- **词库要点**：沉香、海南沉、莞香、奇楠、伽罗、线香、盘香、香道、手串、惠安系、星洲系、芽庄、富森红土；英文 agarwood / oud / aloeswood / kyara / incense / agarwood bracelet / oud oil
- **查询模板**：`(沉香) (价格指数 OR 行情 OR 价格) 2026`；`(海南 OR 莞香 OR 芽庄) (沉香 OR 结香) 2026`；`(agarwood OR oud) (price OR market) 2026`
- **渠道匹配**：行情→新华指数+agarwood.com；直播电商→抖音+小红书+TikTok（中东）；香道文化→微信公众号+小红书+B站
- **待验证**：香产业分会准确名称 🟡；狭义市场 127.6 亿（中国经济新闻网 🟡）；日本/中东外部可达性待实测

## 包：western-antiques（西洋古董·欧洲装饰艺术 · 06_western）

> v1（2026-10-07 用户拍板转正式）。补位总域"西方体系"入口（原 05/06 待建包框架），与珠宝包第 7 体系（古埃及/地中海古物）形成同域对照。详细论证见 `supplement-industries.md` §6（监控仓行业细分表 §3.5、场景应用/western-antiques/）。

- **市场锚点**：杭州博物馆×梁毅博物馆西方银器展 80 套（18-20 世纪）✅ https://www.liangyimuseum.com/_files/ugd/c40d14_c2033b39b7e7491daacfc3debc4f3a84.pdf ；长沙博物馆清代外销精品展 ✅ http://wlgd.changsha.gov.cn/fwms/whhdxx/zlhdyg/202511/t20251103_12041557.html ；瑞典 Täby 拍卖行"欧洲私藏·亚洲艺术品"专场 ✅ https://m-news.artron.net/20251013/n1144828.html
- **三体系**：欧洲银器（伯明翰银戳/洛可可/梁毅博物馆/华夏收藏网）/ 装饰艺术·古董家具（Sotheby's/Christie's 装饰艺术部+Bonhams）/ 外销艺术品（十三行/回流叙事/博物馆特展）
- **词库要点**：西洋古董、欧洲古董、银器、伯明翰银戳、洛可可、维多利亚、古董家具、外销瓷、外销银器、广州十三行、Art Deco；英文 European antique / silverware / sterling silver / hallmarks / decorative arts / export ware / 1stdibs
- **查询模板**：`(西洋古董 OR 欧洲古董 OR 银器) (展览 OR 拍卖 OR 收藏) 2026`；`(silverware OR decorative arts) (auction OR Sotheby's) after:2025-06-01`；`(外销 OR 十三行) (银器 OR 回流 OR 展) 2026`
- **渠道匹配**：展讯学术→微信公众号+知乎+IG+Pinterest；零售探店→抖音+小红书+Instagram+1stdibs；海外拍场→Sotheby's/Christie's/Bonhams+Antiques Trade Gazette
- **待验证**：国内西洋古董市场规模无权威数据 🟡；1stdibs 查询语法待实测
