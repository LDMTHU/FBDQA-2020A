## 金融数据分析
### Python Numpy
### Matplotlib画图notebook
### Python-Pandas数据分析notebook
### Python—Seaborn库使用notebook
## 量化交易
### 多因子模型
- 因子：致使赚钱/亏钱的因素
- 因子投资发展
  - 单因子：市场（解释60%）
  - 多因子：市场、规模、价值、（动量）、（风险）、（质量）
  - 市场异常回报
  - 因子投资
- 美股因子定义
  - 大市值、小市值、高价值（Book-to-Market Ratio）、高动量（总回报）、低波动（beta）、高质量（利润）
  - EW：eqal-weighted
  - VW：value-weighted
- 因子检验方法
  - 一维零投资组合检验
### 海龟交易法
#### 趋势跟随
- 原理
  - 发现“趋势”苗头
  - 顺着趋势的方向下注
  - 遵循“截断亏损，让利润奔跑”的哲学
- 法则
  - 市场：高流动性市场
  - 头寸：N = (19*PDN+TR)/20
    - PDN = 前一日的N值
    - TR = 当日的真实波动幅度
    - 真实的波动幅度 = Max(H-L, H-PDC, PDC-L)
    - 头寸规模单位 = 账户1%/(N*每一点数所代表的美元)
  - 入市信号
    - 以20日突破为基础的短期系统
    - 以55日突破为基础的长期系统
  - 逐步建仓
    - 在突破点建立1个单位的头寸
    - 按N/2的价格间隔逐步扩大头寸
    - 直到头寸达到规模上限
  - 止损
    - 任何一笔交易的风险程度不超过账户的2%
    - 价格变动的上限就是2N
  - 退出
    - 10日反向突破退出
    - 20日反向突破退出