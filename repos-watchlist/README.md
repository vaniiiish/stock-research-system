# Repos Watchlist

这里记录我已经 fork 的股票研究相关 GitHub 项目。

这些项目不是为了直接照搬交易结论，而是作为研究方法、数据框架、技术分析和 AI 投研架构的参考。

核心原则：

* 只吸收方法，不盲信荐股结论
* 社交媒体、推特、雪球、论坛只能作为线索
* 强结论必须回到公告、财报、交易所披露、客户认证、收入占比和价格验证
* 不把这些仓库当成自动交易系统
* 先作为研究资源库，后续再决定是否安装和运行代码

---

## 1. Bottleneck / 木桶效应

### [serenity-skill](https://github.com/vaniiiish/serenity-skill)

Original repo: muxuuu/serenity-skill

用途：

学习供应链瓶颈、木桶效应、预期差挖掘、证据链核验。

重点参考：

* README.md
* SKILL.md
* assets/research-prompt-pack.md

使用原则：

* 只吸收瓶颈挖掘方法
* 不盲信社交媒体荐股
* 不直接跟票
* 强结论必须回到公告、财报、客户认证、收入占比和价格验证

### [aleabito-serenity-skills](https://github.com/vaniiiish/aleabito-serenity-skills)

Original repo: lanfuli/aleabito-serenity-skills

用途：

参考 Serenity / 白毛风格的瓶颈研究方法。

使用原则：

* 只吸收方法
* 不直接跟票
* 不把网络收益率传说当作事实
* 不把推文当成强证据

---

## 2. Single Stock Dashboard / 单票看板

### [Stock-Analysis-Skill](https://github.com/vaniiiish/Stock-Analysis-Skill)

Original repo: liusai0820/Stock-Analysis-Skill

用途：

学习单只股票分析看板结构，包括：

* 基本面
* 技术面
* 估值
* 涨幅
* 风险
* 交易状态

使用原则：

* 借鉴看板结构
* 不照搬买卖建议
* 必须结合 B1 和单针下20交易过滤
* 必须检查估值、涨幅、收入占比和风险反证

---

## 3. Multi-agent Research / 多角色投研

### [TradingAgents](https://github.com/vaniiiish/TradingAgents)

Original repo: TauricResearch/TradingAgents

用途：

学习多角色投研框架：

* 基本面分析师
* 新闻分析师
* 情绪分析师
* 技术分析师
* 牛方研究员
* 熊方研究员
* 风控
* 交易员

使用原则：

* 借鉴“牛熊辩论 + 风控 + 交易员”结构
* 不急着跑代码
* 先把它转化为研究流程
* 用于提高研究完整性，而不是自动下单

### [FinRobot](https://github.com/vaniiiish/FinRobot)

Original repo: AI4Finance-Foundation/FinRobot

用途：

学习金融 AI Agent 和研报生成结构。

使用原则：

* 适合深度研报
* 不作为短线交易系统
* 可借鉴多数据源、多 Agent、多步骤研究结构

---

## 4. Data Infrastructure / 数据底座

### [tushare skills](https://github.com/vaniiiish/skills)

Original repo: waditu-tushare/skills

用途：

A股数据入口，适合以后做：

* 市场温度
* 财务数据
* 指数数据
* 股票池跟踪
* 行业筛选

注意：

* Tushare 通常需要 token
* 先作为中长期数据底座收藏
* 不急着安装运行

### [OpenBB](https://github.com/vaniiiish/OpenBB)

Original repo: OpenBB-finance/OpenBB

用途：

美股、宏观、ETF、全球风险偏好数据底座。

适合：

* 美股研究
* 全球资产观察
* 宏观数据
* 公司财务
* ETF 和行业跟踪

使用原则：

* 偏数据平台
* 不直接给买卖结论
* 适合后续做美股和全球市场雷达

### [qlib](https://github.com/vaniiiish/qlib)

Original repo: microsoft/qlib

用途：

量化研究、因子、回测框架。

注意：

* 偏专业量化
* 暂时不急着用
* 后续可用于策略验证和因子研究

### [FinRL](https://github.com/vaniiiish/FinRL)

Original repo: AI4Finance-Foundation/FinRL

用途：

强化学习交易框架。

注意：

* 暂时收藏
* 不急着接入实盘
* 后续学习自动化交易框架时再看

---

## 5. Technical Structure / 技术结构

### [chan.py](https://github.com/vaniiiish/chan.py)

Original repo: Vespa314/chan.py

用途：

缠论、多级别结构、买卖点、趋势回调辅助。

适合：

* 多级别趋势结构
* 回调确认
* 强趋势票结构判断
* B1候选筛选参考

使用原则：

* 可作为技术结构参考
* 不迷信自动信号
* 最终仍要结合大盘、板块、主线、估值和成交结构

### [czsc](https://github.com/vaniiiish/czsc)

Original repo: waditu/czsc

用途：

缠论结构识别、信号系统、交易结构辅助。

适合：

* 分型
* 笔
* 中枢
* 多级别联立
* 信号和事件框架

使用原则：

* 用来辅助结构识别
* 不把单个技术信号当作买入理由

### [ta-lib-python](https://github.com/vaniiiish/ta-lib-python)

Original repo: TA-Lib/ta-lib-python

用途：

技术指标底层库。

适合：

* MACD
* RSI
* KDJ
* 均线
* ATR
* 布林带
* K线形态

注意：

TA-Lib 只是指标库，不是交易系统。

---

## 6. How to Use These Repos

这些仓库的使用方式分三层：

### 第一层：作为研究方法参考

优先读取：

* README.md
* SKILL.md
* docs
* examples
* prompt templates

目标是提炼方法，不是马上跑代码。

### 第二层：作为 ChatGPT / 深度研究参考源

使用方式：

请读取我的 GitHub 仓库 stock-research-system，先按 prompts/stock-research-system.md 的规则，再参考 repos-watchlist 里的 serenity-skill、Stock-Analysis-Skill 和 TradingAgents，帮我做股票研究。

### 第三层：以后再决定是否安装运行

暂时不急着安装：

* OpenBB
* qlib
* FinRL
* TradingAgents
* chan.py
* czsc

先把研究流程跑通，再考虑代码化。
