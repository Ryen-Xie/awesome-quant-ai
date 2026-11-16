# Awesome Quant & AI Finance

> **AI × 量化 × 金融 × 策略 × 投资的 GitHub 高星项目合集**
> 只做索引，不搬运代码。所有条目均为公开开源仓库，点名字直接跳转。
> 星标为 2026-11-16 快照（GitHub API 实时抓取）；表格里的徽章会自己更新。

一份给中文用户用的「找轮子地图」：先看你要干什么（研究 / 回测 / 实盘 / 纯学习），再按分类进。

---

## 目录

- [0. 总榜 TOP 30](#0-总榜-top-30按星标)
- [1. AI / LLM Agent 投研](#1-ai--llm-agent-投研最热也最需要警惕)
- [2. AI 量化研究 / 因子挖掘](#2-ai-量化研究--因子挖掘)
- [3. 回测与交易框架](#3-回测与交易框架)
- [4. 数据层](#4-数据层)
- [5. 组合优化与风险](#5-组合优化与风险)
- [6. 因子分析与统计工具](#6-因子分析与统计工具)
- [7. 教程 / 学习资料](#7-教程--学习资料)
- [8. 权威 Awesome 索引](#8-权威-awesome-索引)
- [9. 机构工具箱](#9-机构工具箱)
- [10. 四条学习/落地路线](#10-四条学习落地路线)
- [11. 避坑清单](#11-避坑清单比选框架更重要)

---

## 0. 总榜 TOP 30（按星标）

| 项目 | Star | 类型 | 一句话 |
|---|---|---|---|
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | ![stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat-square&logo=github) | LLM 多智能体 | 模拟交易公司：分析师 → 多空辩论 → 交易员 → 风控/基金经理 |
| [openbq-org/OpenBB](https://github.com/openbq-org/OpenBB) | ![stars](https://img.shields.io/github/stars/openbq-org/OpenBB?style=flat-square&logo=github) | 数据终端 | 开源版「彭博终端」，行情/基本面/宏观统一入口 |
| [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | ![stars](https://img.shields.io/github/stars/ZhuLinsen/daily_stock_analysis?style=flat-square&logo=github) | LLM 应用 | 多市场股票分析 + 新闻 + 决策看板 + 定时推送 |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | ![stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund?style=flat-square&logo=github) | LLM 多智能体 | 用投资大师「人格」组一支 AI 对冲基金，仅回测不下单 |
| [freqtrade/freqtrade](https://github.com/freqtrade/freqtrade) | ![stars](https://img.shields.io/github/stars/freqtrade/freqtrade?style=flat-square&logo=github) | 加密实盘 | 最成熟的加密机器人，内置 FreqAI |
| [microsoft/qlib](https://github.com/microsoft/qlib) | ![stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat-square&logo=github) | AI 量化平台 | 数据处理 → 模型 → 回测 → 组合优化全链路 |
| [vnpy/vnpy](https://github.com/vnpy/vnpy) | ![stars](https://img.shields.io/github/stars/vnpy/vnpy?style=flat-square&logo=github) | 全栈平台 | 国内量化首选，CTP/期货/券商实盘接口最全 |
| [ccxt/ccxt](https://github.com/ccxt/ccxt) | ![stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat-square&logo=github) | 交易网关 | 100+ 加密交易所统一 API |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | ![stars](https://img.shields.io/github/stars/HKUDS/Vibe-Trading?style=flat-square&logo=github) | LLM 智能体 | 自然语言提想法 → 拉数据/回测/出报告，支持 A股/港股 |
| [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) | ![stars](https://img.shields.io/github/stars/Fincept-Corporation/FinceptTerminal?style=flat-square&logo=github) | 数据终端 | 桌面级金融终端（行情/分析/投研） |
| [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN) | ![stars](https://img.shields.io/github/stars/hsliuping/TradingAgents-CN?style=flat-square&logo=github) | LLM 多智能体 | TradingAgents 中文增强版，接 A股数据源 |
| [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | ![stars](https://img.shields.io/github/stars/nautechsystems/nautilus_trader?style=flat-square&logo=github) | 生产级引擎 | Rust 写的确定性事件驱动引擎 |
| [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) | ![stars](https://img.shields.io/github/stars/wilsonfreitas/awesome-quant?style=flat-square&logo=github) | 资源索引 | 量化库/数据/论文总索引，找轮子第一站 |
| [ranaroussi/yfinance](https://github.com/ranaroussi/yfinance) | ![stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat-square&logo=github) | 数据 | 雅虎财经行情/财报抓取 |
| [mementum/backtrader](https://github.com/mementum/backtrader) | ![stars](https://img.shields.io/github/stars/mementum/backtrader?style=flat-square&logo=github) | 回测 | 经典事件驱动回测（**已事实停更**） |
| [akfamily/akshare](https://github.com/akfamily/akshare) | ![stars](https://img.shields.io/github/stars/akfamily/akshare?style=flat-square&logo=github) | 数据 | A股/期货/宏观免费数据接口，中文生态最强 |
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | ![stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat-square&logo=github) | 全栈引擎 | 多资产回测 + 实盘，云平台配套 |
| [stefan-jansen/machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading) | ![stars](https://img.shields.io/github/stars/stefan-jansen/machine-learning-for-trading?style=flat-square&logo=github) | 教程+代码 | 《Machine Learning for Trading》第 3 版全部代码 |
| [AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | ![stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square&logo=github) | 金融大模型 | 金融 LLM 微调（LoRA，单卡可训） |
| [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot) | ![stars](https://img.shields.io/github/stars/hummingbot/hummingbot?style=flat-square&logo=github) | 做市/高频 | 加密做市与套利机器人框架 |
| [bbfamily/abu](https://github.com/bbfamily/abu) | ![stars](https://img.shields.io/github/stars/bbfamily/abu?style=flat-square&logo=github) | 综合系统 | 阿布量化：股票/期货/期权/比特币一套架构 |
| [UFund-Me/Qbot](https://github.com/UFund-Me/Qbot) | ![stars](https://img.shields.io/github/stars/UFund-Me/Qbot?style=flat-square&logo=github) | AI 量化 | 可完全本地部署的 AI 量化研究平台 |
| [AI4Finance-Foundation/FinRL](https://github.com/AI4Finance-Foundation/FinRL) | ![stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square&logo=github) | 强化学习 | 深度强化学习交易的开山框架 |
| [waditu/tushare](https://github.com/waditu/tushare) | ![stars](https://img.shields.io/github/stars/waditu/tushare?style=flat-square&logo=github) | 数据 | 老牌 A股数据（需积分，维护弱） |
| [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) | ![stars](https://img.shields.io/github/stars/paperswithbacktest/awesome-systematic-trading?style=flat-square&logo=github) | 资源索引 | 系统化交易的库/策略/书/博客索引 |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | ![stars](https://img.shields.io/github/stars/microsoft/RD-Agent?style=flat-square&logo=github) | LLM 自动化研发 | 用 Agent 自动做因子挖掘与模型迭代 |
| [myhhub/stock](https://github.com/myhhub/stock) | ![stars](https://img.shields.io/github/stars/myhhub/stock?style=flat-square&logo=github) | A股工具 | 数据+指标+筹码+形态+选股+回测一条龙 |
| [goldmansachs/gs-quant](https://github.com/goldmansachs/gs-quant) | ![stars](https://img.shields.io/github/stars/goldmansachs/gs-quant?style=flat-square&logo=github) | 机构工具箱 | 高盛开源的量化金融工具包 |
| [OpenByteInc/QuantDinger](https://github.com/OpenByteInc/QuantDinger) | ![stars](https://img.shields.io/github/stars/OpenByteInc/QuantDinger?style=flat-square&logo=github) | Agentic OS | 自托管的「AI 交易操作系统」 |
| [quantopian/zipline](https://github.com/quantopian/zipline) | ![stars](https://img.shields.io/github/stars/quantopian/zipline?style=flat-square&logo=github) | 回测 | Quantopian 老引擎（**已停更，用 zipline-reloaded**） |
| [je-suis-tm/quant-trading](https://github.com/je-suis-tm/quant-trading) | ![stars](https://img.shields.io/github/stars/je-suis-tm/quant-trading?style=flat-square&logo=github) | 策略合集 | 20+ 具体策略 notebook（VIX/配对/期权…） |

---

## 1. AI / LLM Agent 投研（最热，也最需要警惕）

| 项目 | Star | 定位 |
|---|---|---|
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 122.8k | 多 Agent 投研决策框架，事实上的行业参考实现 |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | 64.7k | 投资大师人格基金，教学价值 > 实战 |
| [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | 72.7k | LLM 驱动的多市场分析 + 自动推送 |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | 38.4k | 港大出品，自然语言 → 策略 → 回测 → 报告，支持 A股 |
| [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN) | 33.0k | 中文/A股增强版 |
| [AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | 21.6k | 金融 LLM 微调框架 |
| [OpenByteInc/QuantDinger](https://github.com/OpenByteInc/QuantDinger) | 13.8k | Agentic Trading OS，自托管 |
| [AI4Finance-Foundation/FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | 8.4k | LLM Agent 自动写研报 |
| [simonlin1212/TradingAgents-astock](https://github.com/simonlin1212/TradingAgents-astock) | 4.0k | 7 位分析师 + A股特色数据（龙虎榜/游资/解禁） |
| [ginlix-ai/LangAlpha](https://github.com/ginlix-ai/LangAlpha) | 2.3k | 「Claude Code for Financial Market」风格 |
| [wquguru/nof0](https://github.com/wquguru/nof0) | 2.8k | LLM 交易竞技场（Alpha Arena 复现） |
| [KylinMountain/TradingAgents-AShare](https://github.com/KylinMountain/TradingAgents-AShare) | 0.9k | 15 Agent 机构协作模拟，全流程可视化 |
| [pipiku915/FinMem-LLM-StockTrading](https://github.com/pipiku915/FinMem-LLM-StockTrading) | 1.0k | 分层记忆 + 角色设计的 LLM 交易 Agent（论文配套） |
| [LLMQuant/awesome-trading-agents](https://github.com/LLMQuant/awesome-trading-agents) | 1.0k | LLM 交易 Agent / MCP server 索引 |

> ⚠️ 这批项目**几乎都没有公开的实盘业绩**，README 多数写明「仅供研究/教育，不构成投资建议」。价值在 Agent 编排范式与工程样板，不是收益承诺。

---

## 2. AI 量化研究 / 因子挖掘

| 项目 | Star | 说明 |
|---|---|---|
| [microsoft/qlib](https://github.com/microsoft/qlib) | 50.3k | 数据层 + 模型层 + 回测 + 组合优化，A股官方数据集 |
| [UFund-Me/Qbot](https://github.com/UFund-Me/Qbot) | 18.8k | 本地部署 AI 量化研究平台 |
| [AI4Finance-Foundation/FinRL](https://github.com/AI4Finance-Foundation/FinRL) | 17.1k | 深度强化学习交易框架 |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | 15.4k | LLM 驱动的自动因子挖掘与模型迭代 |
| [LLMQuant/quant-wiki](https://github.com/LLMQuant/quant-wiki) | 4.5k | 中文开源量化知识库 |
| [edtechre/pybroker](https://github.com/edtechre/pybroker) | 3.7k | 面向机器学习策略的回测框架 |
| [LLMQuant/quant-mind](https://github.com/LLMQuant/quant-mind) | 3.1k | agent-native 量化知识抽取与检索 |
| [TradeMaster-NTU/TradeMaster](https://github.com/TradeMaster-NTU/TradeMaster) | 3.1k | 强化学习量化交易平台（论文配套） |
| [Barca0412/Introduction-to-Quantitative-Finance](https://github.com/Barca0412/Introduction-to-Quantitative-Finance) | 1.9k | **中文最佳入门路径**：多因子框架 + 经典资料 + AI/LLM 论文清单 |
| [leoncuhk/awesome-quant-ai](https://github.com/leoncuhk/awesome-quant-ai) | 0.7k | AI 量化精选索引 |
| [RndmVariableQ/AlphaAgent](https://github.com/RndmVariableQ/AlphaAgent) | — | KDD 2025，LLM 驱动的自动因子挖掘 |
| [nshen7/alpha-gfn](https://github.com/nshen7/alpha-gfn) | — | GFlowNet 挖 alpha 因子 |
| [cn-vhql/FactorHub](https://github.com/cn-vhql/FactorHub) | 0.4k | 开源因子分析平台 |
| [marketneutral/alphatools](https://github.com/marketneutral/alphatools) | 0.5k | Python 量化研究工具集 |

---

## 3. 回测与交易框架

### 3.1 A股 / 期货（国内实盘）

| 项目 | Star | 说明 |
|---|---|---|
| [vnpy/vnpy](https://github.com/vnpy/vnpy) | 46.4k | 全栈平台，CTP 等实盘接口最全 |
| [yutiansut/QUANTAXIS](https://github.com/yutiansut/QUANTAXIS) | 11.4k | 数据/回测/模拟/交易/多账户，纯本地 |
| [ricequant/rqalpha](https://github.com/ricequant/rqalpha) | 6.9k | 米筐开源回测引擎，可扩展可替换 |
| [wondertrader/wondertrader](https://github.com/wondertrader/wondertrader) | 6.4k | C++ 一站式量化研发交易框架 |
| [fasiondog/hikyuu](https://github.com/fasiondog/hikyuu) | 3.7k | C++/Python 高性能策略分析框架 |

### 3.2 多资产 / 生产级

| 项目 | Star | 说明 |
|---|---|---|
| [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | 31.6k | Rust 原生、确定性事件驱动，机构级执行 |
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | 22.6k | 股票/期权/期货/外汇/加密，回测+实盘 |
| [StockSharp/StockSharp](https://github.com/StockSharp/StockSharp) | 11.1k | C# 算法交易平台 |
| [barter-rs/barter-rs](https://github.com/barter-rs/barter-rs) | 2.4k | Rust 事件驱动交易生态 |

### 3.3 快速回测 / 参数扫描

| 项目 | Star | 说明 |
|---|---|---|
| [polakowo/vectorbt](https://github.com/polakowo/vectorbt) | 9.9k | 向量化引擎，秒级跑上千组参数（⚠️ Commons Clause，禁止商业转售） |
| [kernc/backtesting.py](https://github.com/kernc/backtesting.py) | 9.2k | 轻量事件驱动，最适合验证单个策略（AGPL-3.0） |
| [mementum/backtrader](https://github.com/mementum/backtrader) | 23.8k | 经典框架，教程最多，但 2024-08 后停更 |
| [Lumiwealth/lumibot](https://github.com/Lumiwealth/lumibot) | 2.2k | 回测/纸盘/实盘统一，带 AI agents |
| [coding-kitties/investing-algorithm-framework](https://github.com/coding-kitties/investing-algorithm-framework) | 2.2k | 开发→回测→部署完整框架 |
| [stefan-jansen/zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded) | 2.0k | zipline 的活跃维护分支 |

### 3.4 加密

| 项目 | Star | 说明 |
|---|---|---|
| [freqtrade/freqtrade](https://github.com/freqtrade/freqtrade) | 56.9k | 加密机器人首选，含 FreqAI |
| [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot) | 21.2k | 做市与套利 |
| [jesse-ai/jesse](https://github.com/jesse-ai/jesse) | 8.8k | 干净的策略开发框架 |
| [Drakkar-Software/OctoBot](https://github.com/Drakkar-Software/OctoBot) | 7.0k | AI/网格/DCA/TradingView 策略 |
| [Superalgos/Superalgos](https://github.com/Superalgos/Superalgos) | 5.8k | 可视化加密交易平台 |
| [nkaz001/hftbacktest](https://github.com/nkaz001/hftbacktest) | 5.1k | 高频/做市回测，含订单簿撮合 |

---

## 4. 数据层

> 策略的命门。框架可以换，数据不能凑合。

| 项目 | Star | 覆盖 |
|---|---|---|
| [openbq-org/OpenBB](https://github.com/openbq-org/OpenBB) | 75.5k | 多源聚合终端 |
| [ccxt/ccxt](https://github.com/ccxt/ccxt) | 44.9k | 加密 100+ 交易所统一 API |
| [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) | 33.9k | 桌面金融终端 |
| [ranaroussi/yfinance](https://github.com/ranaroussi/yfinance) | 25.9k | 美股/全球，免费但不稳定 |
| [akfamily/akshare](https://github.com/akfamily/akshare) | 23.4k | A股/期货/期权/宏观/另类数据 |
| [waditu/tushare](https://github.com/waditu/tushare) | 15.5k | A股，质量稳但需积分 |
| [myhhub/stock](https://github.com/myhhub/stock) | 15.2k | A股数据+指标+选股+回测 |
| [shidenggui/easytrader](https://github.com/shidenggui/easytrader) | 10.3k | 同花顺/miniqmt/雪球自动化下单 |
| [1nchaos/adata](https://github.com/1nchaos/adata) | 5.4k | 专注 A股，纯开源 |
| [TA-Lib/ta-lib-python](https://github.com/TA-Lib/ta-lib-python) | 12.4k | 技术指标计算（C 加速） |

---

## 5. 组合优化与风险

| 项目 | Star | 说明 |
|---|---|---|
| [PyPortfolio/PyPortfolioOpt](https://github.com/PyPortfolio/PyPortfolioOpt) | 6.2k | 均值方差 / Black-Litterman / HRP，最常用 |
| [dcajasn/Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) | 4.6k | 风险平价与风险度量最全 |
| [skfolio/skfolio](https://github.com/skfolio/skfolio) | 2.6k | sklearn 风格，含因子模型与交叉验证 |
| [cvxgrp/cvxportfolio](https://github.com/cvxgrp/cvxportfolio) | 1.3k | 凸优化，含交易成本与约束建模 |
| [NVIDIA-AI-Blueprints/portfolio-optimization](https://github.com/NVIDIA-AI-Blueprints/portfolio-optimization) | 0.5k | GPU 加速（cuOpt）组合优化 |
| [convexfi/riskparity.py](https://github.com/convexfi/riskparity.py) | 0.3k | 快速风险平价组合 |

---

## 6. 因子分析与统计工具

| 项目 | Star | 说明 |
|---|---|---|
| [TA-Lib/ta-lib-python](https://github.com/TA-Lib/ta-lib-python) | 12.4k | 技术指标标准库 |
| [waditu/czsc](https://github.com/waditu/czsc) | 6.6k | 缠论/技术分析信号，Rust 加速 |
| [hudson-and-thames/mlfinlab](https://github.com/hudson-and-thames/mlfinlab) | 5.0k | Lopez de Prado 方法论实现（2023 后停更） |
| [quantopian/alphalens](https://github.com/quantopian/alphalens) | 4.5k | 因子 IC / 分层回测标准工具 |
| [joshyattridge/smart-money-concepts](https://github.com/joshyattridge/smart-money-concepts) | 2.2k | ICT / SMC 价格行为概念 |
| [fracdiff/fracdiff](https://github.com/fracdiff/fracdiff) | 0.3k | 分数阶差分，做平稳化特征 |

---

## 7. 教程 / 学习资料

> 这是 GitHub 上 star 最密集的区域，也是最容易「看了很多、什么也没做」的区域。

| 项目 | Star | 说明 |
|---|---|---|
| [stefan-jansen/machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading) | 21.8k | 从数据到实盘的完整书稿代码，**最推荐的自学主线** |
| [je-suis-tm/quant-trading](https://github.com/je-suis-tm/quant-trading) | 11.3k | 20+ 具体策略 notebook |
| [huseinzol05/Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) | 9.5k | 各类 ML/DL 预测模型与交易机器人合集 |
| [Rockyzsu/stock](https://github.com/Rockyzsu/stock) | 9.0k | 《30 天掌握量化交易》中文系列 |
| [cantaro86/Financial-Models-Numerical-Methods](https://github.com/cantaro86/Financial-Models-Numerical-Methods) | 7.5k | 数值方法 + 衍生品定价 + 风险模型，notebook 交互 |
| [firmai/financial-machine-learning](https://github.com/firmai/financial-machine-learning) | 8.8k | 金融 ML 工具与论文索引 |
| [PacktPublishing/Hands-On-Machine-Learning-for-Algorithmic-Trading](https://github.com/PacktPublishing/Hands-On-Machine-Learning-for-Algorithmic-Trading) | 2.0k | 书配套代码 |
| [robertmartin8/MachineLearningStocks](https://github.com/robertmartin8/MachineLearningStocks) | 2.0k | sklearn 选股入门 |
| [Barca0412/Introduction-to-Quantitative-Finance](https://github.com/Barca0412/Introduction-to-Quantitative-Finance) | 1.9k | 中文 AI+金融入门与资料收录 |
| [dwcoder/QuantitativePrimer](https://github.com/dwcoder/QuantitativePrimer) | 1.6k | 量化面试指南（数学+编程+智力题） |
| [LongOnly/Quantitative-Notebooks](https://github.com/LongOnly/Quantitative-Notebooks) | 1.4k | 教学型 notebook 合集 |
| [dingran/quant-notes](https://github.com/dingran/quant-notes) | 1.0k | 量化面试准备笔记 |
| [quantrocket-codeload/quant-finance-lectures](https://github.com/quantrocket-codeload/quant-finance-lectures) | 0.7k | Quantopian 讲义重制版 |
| [MarcosCarreira/DermanPapers](https://github.com/MarcosCarreira/DermanPapers) | 0.5k | Emanuel Derman 经典论文复现 |
| [charliedream1/ai_quant_trade](https://github.com/charliedream1/ai_quant_trade) | — | 中文 AI 操盘手：因子/ML/DL/RL/高频/C++ 部署 |

---

## 8. 权威 Awesome 索引

| 项目 | Star | 侧重 |
|---|---|---|
| [wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) | 30.7k | 全球量化库总索引（含 C++/R/Julia） |
| [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) | 15.4k | 系统化交易：库+策略+书+博客 |
| [firmai/financial-machine-learning](https://github.com/firmai/financial-machine-learning) | 8.8k | 金融 ML 工具与论文 |
| [georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) | 6.8k | LLM / 深度学习在金融 |
| [thuquant/awesome-quant](https://github.com/thuquant/awesome-quant) | 5.7k | **中国量化资源索引**（A股数据/券商研报/公众号） |
| [wangzhe3224/awesome-systematic-trading](https://github.com/wangzhe3224/awesome-systematic-trading) | 5.4k | 系统化交易精选 |
| [grananqvist/Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading) | 4.1k | ML 交易资源 |
| [cbailes/awesome-deep-trading](https://github.com/cbailes/awesome-deep-trading) | 2.1k | 深度学习交易资源 |
| [LLMQuant/awesome-trading-agents](https://github.com/LLMQuant/awesome-trading-agents) | 1.0k | LLM 交易 Agent 索引 |

---

## 9. 机构工具箱

| 项目 | Star | 说明 |
|---|---|---|
| [goldmansachs/gs-quant](https://github.com/goldmansachs/gs-quant) | 14.2k | 高盛量化金融工具包 |
| [google/tf-quant-finance](https://github.com/google/tf-quant-finance) | 5.6k | TensorFlow 高性能量化金融 |
| [avhz/RustQuant](https://github.com/avhz/RustQuant) | 1.8k | Rust 量化金融库 |
| [jsmidt/QuantPy](https://github.com/jsmidt/QuantPy) | 1.1k | Python 量化框架 |

---

## 10. 四条学习/落地路线

### A. 零基础但想真的做出策略（3 个月）

```
akshare 取数 → pandas 清洗 → backtesting.py 单策略
→ alphalens 因子检验 → qlib 多因子(LightGBM) → PyPortfolioOpt 权重
```
全程对照 `machine-learning-for-trading` 的 notebook。

### B. A股 / 期货实盘

`vnpy` 一条路走到底（vnpy_ctp → 模拟盘 → 小资金实盘）；研究端用 `qlib` 或 `rqalpha`。**别在实盘框架里做因子研究。**

### C. 加密

`ccxt`（对接）+ `freqtrade`（策略/回测/实盘/FreqAI）+ `hftbacktest`（若要高频做市）。

### D. AI / LLM Agent 研究

先读 `TradingAgents` 的架构（多空辩论 + 风控环节最值得借鉴）→ 再看 `Vibe-Trading` 的 A股/港股落地 → 用 `RD-Agent` 做因子自动化。自己实验必须加 **walk-forward + 交易成本 + 样本外**。

---

## 11. 避坑清单（比选框架更重要）

1. **过拟合**：一次扫几千组参数（vectorbt 式）必须配 walk-forward / purged K-fold，否则最优参数只是噪声。
2. **前视偏差**：财报要用「公告日」对齐而非「报告期」；LLM 项目尤其容易在 prompt 里塞未来信息。
3. **幸存者偏差**：股票池要用当时可交易成分股，不是今天的成分股。
4. **成本建模**：A股印花税+佣金+冲击成本，加密手续费+资金费率，不扣等于自欺。
5. **LLM 交易项目没有实盘业绩**：把它当研究工具，不当印钞机。
6. **停更识别**：`backtrader`(2024-08)、`zipline`(2024-02)、`tushare`(2024-03)、`mlfinlab`(2023-10) 均在事实停更区间。
7. **许可证**：`vectorbt` 开源版带 Commons Clause（禁止商业转售），`backtesting.py` 是 AGPL-3.0。做商业产品前先读 LICENSE。
8. **数据单一风险**：yfinance 免费但会限流/改接口，生产环境至少双源交叉校验。

---

## 维护

```bash
# 看某主题最新的头部项目
curl -s "https://api.github.com/search/repositories?q=topic:quantitative-finance&sort=stars&order=desc&per_page=20"

# 只看最近 30 天有提交的高星项目（过滤死仓库）
curl -s "https://api.github.com/search/repositories?q=quantitative+finance+pushed:>2026-10-16&sort=stars&order=desc"
```

常用搜索词：`quantitative finance`、`algorithmic trading`、`backtesting`、`LLM agent trading`、`financial machine learning`、`topic:quantitative-finance`、`topic:algorithmic-trading`、`量化交易`。

---

## 免责声明

本仓库仅为公开资源的索引与整理，**不构成任何投资建议**。所有项目版权归原作者所有；使用前请自行阅读对应仓库的 LICENSE 与风险声明。金融交易有风险，实盘前请充分回测与模拟。
