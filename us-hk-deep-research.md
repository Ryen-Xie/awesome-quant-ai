# 美股 / 港股 深度研究资源库

> 重点：**纳斯达克七姐妹**（AAPL / MSFT / GOOGL / AMZN / NVDA / META / TSLA）
> 回答一个问题：**想认真搞懂一家公司（比如 Alphabet），到底该看什么、去哪儿看、用什么工具把十年数据拉出来。**
> 本文只放入口与方法，不搬内容；一手数据全部指向官方源。

---

## 为什么要单独研究这七家

七姐妹合计约占 S&P 500 总市值的 **34%–35%**，研究这七家等于研究美股大盘本身。它们的共同特征是：现金流引擎极强、资本开支极重、叙事高度依赖 AI。

| 公司 | 代码 | 市值（估） | Forward P/E | 2026 YTD | 真正的现金牛 | 2026 的核心叙事 |
|---|---|---|---|---|---|---|
| 英伟达 | NVDA | ~$4.92T | 24.2x | +50% | 数据中心 GPU + 网络 + CUDA | AI 基建周期的“卖铲人”，看订单能见度与毛利率 |
| 微软 | MSFT | ~$3.14T | 30.5x | +0.3% | Azure + Office/Copilot 订阅 | AI 变现最均衡的一家，看 Azure 增速与 Copilot 付费渗透 |
| 苹果 | AAPL | ~$3.95T | 31.2x | +5% | 服务业务（App Store/订阅/授权） | 几乎不烧 AI 资本开支，靠生态与定价权守住 FCF |
| 亚马逊 | AMZN | ~$2.66T | 28.7x | +14% | AWS + 广告 | AWS 加速 + 自研芯片 + 广告三引擎，FCF 被资本开支吃掉 |
| 谷歌 | GOOGL | ~$4.13T | 22.1x | +81% | 搜索广告 + YouTube + Cloud | 搜索被 AI 重构的“生死题”，云与 Gemini 是第二曲线 |
| Meta | META | ~$1.74T | 23.8x | +18% | 全家桶广告 | 广告效率 + AI 推荐，Reality Labs 持续失血 |
| 特斯拉 | TSLA | ~$1.29T | 95.4x | -0.8% | 整车 + 能源 + 服务 | 汽车主业利润率坍缩，估值靠 Robotaxi/FSD 期权 |

> ⚠️ 上表市值/P/E/YTD 为第三方站点（TECHi）的 2026-03 快照推算，**仅作量级参考**，做决策前请回 SEC 与官方财报核对。

---

## 一、单股深研的“四层结构”（以 Alphabet 为例走一遍）

### 第 1 层：一手文件（不可替代）

| 文件 | 去哪拿 | 看什么 |
|---|---|---|
| 10-K（年报） | [SEC EDGAR · CIK 0001652044](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001652044&type=10-K) | 收入拆分、风险因素（Item 1A）、分部利润、回购与股本 |
| 10-Q（季报） | 同上，type=10-Q | 季度环比、递延收入、资本开支节奏 |
| 8-K（重大事项） | 同上，type=8-K | 高管变动、并购、监管处罚 |
| 代理声明 DEF 14A | 同上 | 高管薪酬结构（激励指向哪个业务） |
| 投资者关系页 | [abc.xyz/investor](https://abc.xyz/investor/) | 财报 PPT、股东信、电话会录音与逐字稿 |

**Alphabet FY2025 的关键数字（来自 10-K）**：

- 总收入 **$402.8B**（+15%）
- 广告 **$294.7B**：Search & other $224.5B、YouTube 广告 $40.4B、Network $29.8B
- 订阅/平台/设备 **$48.0B**；Google Cloud **$58.7B**；Other Bets **$1.5B**
- 分部经营利润：Google Services **$139.4B**、Cloud **$13.9B**（2024 为 $6.1B）、Other Bets **-$7.5B**、Alphabet-level **-$16.8B**

**Q4 2025 电话会（口径变化最密集的地方）**：Services 收入 +14% 至 $95.5B；Search +17% 至 $63.1B；YouTube 广告 +9% 至 $11.4B（受 2024 大选高基数拖累）；Cloud +48% 至 $17.7B，Cloud 经营利润 $5.3B、同比翻倍以上，经营利润率从 17.5% 抬升。

### 第 2 层：十年视角（把三条 S 曲线分开看）

1. **搜索广告（2004–2022）**：单一引擎，毛利率 55%+，是“印钞机”阶段。
2. **云与订阅（2018–2024）**：从烧钱到盈利，Cloud 经营利润率转正并快速抬升，是“第二引擎”。
3. **AI 重构（2023– ）**：搜索被 AI Overviews / AI Mode 改写，资本开支跳升，短期压 FCF、长期决定入口归属。

> 研究要点不是“今年赚多少”，而是**三条曲线的交班是否顺利**：搜索的现金流能否撑住 AI 的资本开支，云的利润率能否继续抬。

### 第 3 层：十年数据（自己拉，不靠别人总结）

| 指标 | 为什么看 | 去哪拉 |
|---|---|---|
| 毛利率 / 经营利润率 10 年曲线 | 判断护城河是在变强还是变弱 | Macrotrends（免费 10 年图） |
| ROIC / ROE | 资本回报是否被资本开支稀释 | TIKR、stockanalysis.com |
| 自由现金流与 CapEx 之比 | AI 时代的生死指标 | 10-K 现金流量表 |
| 分部收入占比变化 | 看业务结构迁移 | 10-K 分部附注 |
| 股本与回购 | 每股口径是否被稀释 | 10-K 权益变动表 |

### 第 4 层：二手深度与反方观点

- **商业模式拆解**：[FourWeekMBA · Google Business Model](https://fourweekmba.com/google-business-model/)（分业务收入树 + 利润率瀑布图）
- **公司档案与分部财务**：[FirmsWorld · Alphabet](https://firmsworld.com/alphabet-inc/)
- **卖方研报**：Bamsec / Seeking Alpha / 各投行 IR 纪要
- **反方**：每年专门找一篇 bear case（监管拆分、搜索份额流失、AI 资本开支回报率），否则容易陷入确认偏误

---

## 二、七家公司研究入口（一键直达）

| 公司 | 投资者关系 | 10-K 归档（SEC EDGAR） | 研究重点 |
|---|---|---|---|
| 苹果 AAPL | [investor.apple.com](https://investor.apple.com/) | [CIK 0000320193](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000320193&type=10-K) | 服务业务毛利率、iPhone 换机周期、AI CapEx 极低带来的 FCF 优势 |
| 微软 MSFT | [microsoft.com/investor](https://www.microsoft.com/en-us/investor) | [CIK 0000789019](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000789019&type=10-K) | Azure 增速与 AI 贡献拆分、Copilot 付费席位、OpenAI 投资的会计影响 |
| 谷歌 GOOGL | [abc.xyz/investor](https://abc.xyz/investor/) | [CIK 0001652044](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001652044&type=10-K) | 搜索广告是否被 AI 分流、Cloud 利润率、Other Bets（Waymo）亏损 |
| 亚马逊 AMZN | [ir.aboutamazon.com](https://ir.aboutamazon.com/) | [CIK 0001018724](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001018724&type=10-K) | AWS 增速与利润率、自研芯片、广告增速、FCF 转负的原因 |
| 英伟达 NVDA | [investor.nvidia.com](https://investor.nvidia.com/) | [CIK 0001045810](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001045810&type=10-K) | 数据中心收入结构、客户集中度（前几大客户占比）、毛利率可持续性、库存与订单 |
| Meta META | [investor.atmeta.com](https://investor.atmeta.com/) | [CIK 0001326801](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001326801&type=10-K) | 广告单价与展示量、Reality Labs 亏损、AI 推荐带来的时长提升 |
| 特斯拉 TSLA | [ir.tesla.com](https://ir.tesla.com/) | [CIK 0001318605](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001318605&type=10-K) | 汽车毛利率（剔除积分）、单车成本、能源业务、FSD 递延收入 |

> 技巧：EDGAR 页面把 `type=10-K` 改成 `type=10-Q`、`type=8-K`、`type=DEF 14A` 就能直接切换到对应文件流；`count=40` 可一次拉更多。

---

## 三、数据平台选型（免费 → 付费）

| 平台 | 覆盖 | 历史长度 | 价格 | 适合谁 |
|---|---|---|---|---|
| **SEC EDGAR** | 美股全部申报文件 + XBRL | 1993 至今 | 免费 | 所有人，**一手数据唯一权威源** |
| [Macrotrends](https://www.macrotrends.net/) | 美股财务比率 | 10 年+图表 | 免费 | 快速判断护城河趋势（毛利率/净利率曲线） |
| [stockanalysis.com](https://stockanalysis.com/) | 美股/部分国际 | 10 年财报、估值 | 免费 | 拉三表 + 估值倍数的轻量工作台 |
| [TIKR](https://www.tikr.com/) | 10 万+ 全球股票 | 免费 1 年，Pro 20–30 年 | $0 / $24.95 / $54.95 每月 | 想在一页里对照“数字 + 电话会原文” |
| [Bamsec](https://www.bamsec.com/) | 美股申报文件 + 逐字稿检索 | 长 | 付费 | 专业选手，关键词跨公司检索原文 |
| [Quartr](https://www.quartr.com/) | 全球电话会录音/逐字稿 | 长 | 免费+付费 | 通勤时听管理层口径 |
| [Koyfin](https://www.koyfin.com/) | 全球宏观+个股 | 长 | 免费+付费 | 做同业对比与宏观叠加 |
| [companiesmarketcap](https://companiesmarketcap.com/) | 全球市值排名 | — | 免费 | 看市值位次与历史排名变化 |
| 雪球 / 富途 / 老虎 | A股/港股/美股 | 中 | 免费+付费 | 中文界面 + 港股通数据 |

> ⚠️ 注意：alphacrew、techi 这类“AI 一键买卖评级”站点可以当信息源扫一眼，**不能当研究结论**，它们不给假设、不给估值模型、不给可复现路径。

---

## 四、港股专属地图（和美股不是一套玩法）

### 一手源：披露易 HKEXnews

- 官网：[www.hkexnews.hk](https://www.hkexnews.hk/)——港股信息披露的**唯一官方入口**。
- 含：公告、通函、**年报/中报/季报**、ESG 资料、月报表、**权益披露（5% 以上须披露）**、CCASS 持股、新股资料。
- 规则：主板与 GEM 公司发年报/中报/财报时，必须登载于披露易，且**公司网站需至少保留 5 年**；公告发布时段为交易日 6:00–23:00。
- 用法：用「进阶搜寻」按标题关键词筛（如输入“盈利警告”“正面盈利预告”），比逐家翻快得多。

### 港股研究的 6 个特殊变量（美股没有的）

| 变量 | 为什么重要 | 去哪看 |
|---|---|---|
| **南向资金 / 港股通持股** | A股资金定价权，直接影响流动性 | 披露易「沪深港通持股纪录」、富途/ Wind |
| **CCASS 持股** | 看清筹码在谁手里（券商席位 vs 机构） | 披露易 CCASS 搜寻 |
| **沽空比率** | 港股沽空数据公开，是情绪与拥挤度指标 | HKEX 每日沽空报告 |
| **AH 溢价** | 同一家公司 A/H 两地价差，是套利与情绪的温度计 | 恒生 AH 溢价指数 |
| **供股 / 配股 / 老千股** | 港股独有的股本稀释风险 | 披露易「供股」「配售」公告 |
| **会计准则差异** | HKFRS/IFRS vs US GAAP，利润口径不完全可比 | 年报会计政策附注 |

### 港股数据工具

- `akshare`：港股行情与财务接口（免费）
- `easyquotation`：新浪 / **腾讯港股** / 集思录 实时行情
- `yfinance`：`0700.HK` 这类后缀可直接拉港股
- 富途 OpenAPI / 老虎 API：券商级行情与交易（需开户）
- 双重上市 / ADR：如 9988.HK 与 BABA，注意汇率与投票权结构差异

---

## 五、GitHub 工具清单（按用途分）

### 5.1 抓一手文件 / 解析财报（最硬的一层）

| 项目 | Star | 用途 |
|---|---|---|
| [dgunning/edgartools](https://github.com/dgunning/edgartools) | 2.9k | Python 读 10-K/8-K/XBRL/13F，**最好用的 EDGAR 工具** |
| [sec-edgar/sec-edgar](https://github.com/sec-edgar/sec-edgar) | 1.4k | 批量下载全部公司定期报告 |
| [jadchaar/sec-edgar-downloader](https://github.com/jadchaar/sec-edgar-downloader) | 0.7k | 按 ticker 精准下载申报文件 |
| [alphanome-ai/sec-parser](https://github.com/alphanome-ai/sec-parser) | 0.3k | 把 10-K HTML 解析成语义树 |
| [datasets/edgar](https://github.com/datasets/edgar) | 0.4k | EDGAR 数据集的整理版 |
| [SEC-API-io/sec-api-python](https://github.com/SEC-API-io/sec-api-python) | 0.3k | 官方风格 SDK，2000 万+ 文件 |
| [lukerosiak/pysec](https://github.com/lukerosiak/pysec) | 0.3k | 解析 XBRL 财务数据 |

### 5.2 单股深度研究 / 权益研究 Agent（直接看别人的“研报模板”）

| 项目 | Star | 用途 |
|---|---|---|
| [quant-sentiment-ai/claude-equity-research](https://github.com/quant-sentiment-ai/claude-equity-research) | 0.8k | Claude Code 插件，机构级权益研究工作流 |
| [juanjuandog/FinSight-AI](https://github.com/juanjuandog/FinSight-AI) | 0.6k | 带证据链与版本化报告的 AI 研报 Agent |
| [rollingSirius/equity-research-skill](https://github.com/rollingSirius/equity-research-skill) | 0.5k | **九章式单股深度**框架，最接近“深度研究 SOP” |
| [agentii-ai/agentii-investment-intelligence](https://github.com/agentii-ai/agentii-investment-intelligence) | 0.2k | 25 个投研 skill，含 SEC/XBRL |
| [Buptropz/equity-research-tutor](https://github.com/Buptropz/equity-research-tutor) | 0.1k | 官方财报证据 + DCF 估值的本地学习工作台 |
| [webleon/tech-earnings-deepdive-openclaw-skill](https://github.com/webleon/tech-earnings-deepdive-openclaw-skill) | 32 | **科技股财报深挖 16 模块**（七姐妹适配度高） |
| [willpowerju-lgtm/3-statement-ultra-for-finance](https://github.com/willpowerju-lgtm/3-statement-ultra-for-finance) | 89 | 三表联动财务模型生成 |
| [stockvaluation-io/stockvaluation_io](https://github.com/stockvaluation-io/stockvaluation_io) | 37 | 本地 DCF 估值 MCP 工作流 |
| [kbhujbal/AlphaAnalyst-open-source-autonomous-equity-research-agent](https://github.com/kbhujbal/AlphaAnalyst-open-source-autonomous-equity-research-agent) | 51 | 输入 ticker 输出含 DCF 的研报 memo |

### 5.3 财报问答 / RAG（把 10-K 变成可检索知识库）

| 项目 | Star | 用途 |
|---|---|---|
| [Mattral/filing-qa](https://github.com/Mattral/filing-qa) | 91 | 10-K/10-Q 问答，**答案带引用** |
| [rmr2024/finextract](https://github.com/rmr2024/finextract) | 24 | 专治 LLM 从 10-K 抽数字的幻觉 |
| [ben-james-h/sec_RAG_basic_analysis](https://github.com/ben-james-h/sec_RAG_basic_analysis) | — | 直接就是**七姐妹 10-K 的 RAG 分析** |
| [daniel3303/Equibles](https://github.com/daniel3303/Equibles) | 0.2k | 自托管金融数据 MCP（SEC/XBRL/13F） |
| [signal8ai/signal8-mcp](https://github.com/signal8ai/signal8-mcp) | 0.4k | 给 AI agent 的 SEC 情报 MCP |

### 5.4 筛选器与行情数据

| 项目 | Star | 用途 |
|---|---|---|
| [deepentropy/tvscreener](https://github.com/deepentropy/tvscreener) | 1.8k | TradingView 筛选器 API（美股/港股全覆盖） |
| [xang1234/stock-screener](https://github.com/xang1234/stock-screener) | 0.4k | CANSLIM/Minervini 选股，**支持 12 个市场含港股** |
| [rreichel3/US-Stock-Symbols](https://github.com/rreichel3/US-Stock-Symbols) | 0.6k | 全量 NASDAQ/NYSE/AMEX 代码表 |
| [JerBouma/FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) | 9.6k | 30 万+ 标的数据库（股票/ETF/指数） |
| [Nasdaq/data-link-python](https://github.com/Nasdaq/data-link-python) | 0.6k | Nasdaq 官方数据接口 |
| [simonlin212/global-stock-data](https://github.com/simonlin212/global-stock-data) | 1.9k | 美股/全球数据包，**官方源优先、零鉴权** |

### 5.5 中文生态：A股/港股/美股一起做

| 项目 | Star | 用途 |
|---|---|---|
| [simonlin212/Vibe-Research](https://github.com/simonlin212/Vibe-Research) | 3.7k | **A股/美股/港股投研工作台**，168 个数据端点，支持 Claude Code/Codex |
| [ArvinLovegood/go-stock](https://github.com/ArvinLovegood/go-stock) | 8.2k | AI 股票分析/选股，支持 A股/港股/美股，数据本地保留 |
| [wbh604/UZI-Skill](https://github.com/wbh604/UZI-Skill) | 7.6k | 22 维数据 × 180 条规则 × 17 种机构分析方法，覆盖 A/港/美 |
| [shidenggui/easyquotation](https://github.com/shidenggui/easyquotation) | 5.5k | 新浪/腾讯（港股）/集思录 实时行情 |
| [TNT-Likely/PanWatch](https://github.com/TNT-Likely/PanWatch) | 2.5k | 基于 TradingAgents 的 A/港/美盯盘 |
| [GrinZero/ccass-monitor](https://github.com/GrinZero/ccass-monitor) | 7 | **监控港股 CCASS 机构筹码** |

### 5.6 机构持仓（13F）

| 项目 | Star | 用途 |
|---|---|---|
| [toddwschneider/sec-13f-filings](https://github.com/toddwschneider/sec-13f-filings) | 0.4k | 13F 数据的友好查看方式 |
| [leftmove/wallstreetlocal](https://github.com/leftmove/wallstreetlocal) | 0.5k | 追踪美国大型基金经理持仓 |
| [AlphaGBM/investment-masters](https://github.com/AlphaGBM/investment-masters) | 0.6k | 15 位大师方法论 + 13F 跟随 |
| [Jakeschincariol/trader-skill](https://github.com/Jakeschincariol/trader-skill) | 1.9k | 11 个 Claude skill，复制信任的投资者 + 盯新闻/国会交易 |

---

## 六、可复制的「单股深研 7 天 SOP」

| 天 | 动作 | 产出 |
|---|---|---|
| D1 | 拉 3 份 10-K（最新 / 5 年前 / 10 年前）+ 最新 10-Q | 一张收入结构演变表 |
| D2 | 读最近 8 个季度电话会逐字稿，只记“口径变化” | 管理层说法变化清单 |
| D3 | Macrotrends/TIKR 拉 10 年毛利率、经营利润率、ROIC、CapEx/FCF | 一张 10 年趋势图 |
| D4 | 拆分部：每块业务的增速、利润率、资本占用 | 分部 SOTP 表 |
| D5 | 竞争与 TAM：对手对比 + 份额变化 | 竞争格局一页纸 |
| D6 | 估值：反向 DCF（当前价格隐含了什么增长） | 隐含假设表 |
| D7 | 写 bear case 与三个可证伪的跟踪指标 | 一页投资 memo |

> 判断标准：如果你不能用三句话说出“这家公司靠什么赚钱、护城河在哪、什么会让它崩”，说明还没研究完。

---

## 七、避坑

1. **AI 一键评级不等于研究**：没有假设、没有模型、没有可复现路径，不能作为决策依据。
2. **七姐妹 ≈ 35% 的 S&P 500**：把它们当“分散化”是错觉，七家同涨同跌的相关性极高。
3. **市值/P/E 快照会过期**：任何第三方站点数字都要回 10-K / 10-Q 复核。
4. **non-GAAP 调整**：七姐妹普遍用 non-GAAP 强调利润，务必看 GAAP 与 SBC（股权激励）的真实成本。
5. **CapEx 与 FCF 的背离**：AI 时代看“经营现金流 - 资本开支”，而不是只看净利润。
6. **港股会计口径**：HKFRS 与 US GAAP 不可直接比，ADR 还要看汇率与投票权结构。
7. **披露易才是港股一手源**：雪球/富途的财务数据可能有滞后或口径差异，关键数字回原文。

---

## 免责声明

本文为公开信息索引与研究方法整理，**不构成任何投资建议**。所有数据请以公司公告与监管文件为准。
