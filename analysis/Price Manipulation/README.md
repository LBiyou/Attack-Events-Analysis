#### 操纵价格预言机器
攻击者透过闪电贷，瞬间抽走预言机的流动性，使受害合约取得异常的价格资讯
- 此漏洞常在 GetPrice、Swap、StackingReward、Transfer(with burn fee) 等关键功能被利用
- 根本原因: 项目方使用了不安全的预言机，或是未实现 TWAP 时间加权平均价格。