---
title: EGD Finance @Price Manipulation
categories: Attack_Events_Analysis
tags:
  - Price Manipulation
date: 2024-04-01 10:00:00
---



#### 事件资讯

- 时间：*2022-08-07*

- 损失金额：*~36_044 $*

- 漏洞原因： *池子`[PancakeSwap V2:EGD-BSC-USD]`的价格被操纵，将`EGD`的价格严重拉低，使得`rew`的值变大，从而获取更多的`EGD Token`。*

```solidity
rew += quota * 1e18 / getEGDPrice();
```

#### 链上资讯

- *Chain：* BSC

- *Hacker Address：*
    - *0xee0221d76504aec40f63ad7e36855eebf5ea5edd* 【攻击账户】
    - *0x3Cb0FE8b5ac9D36F22465424412D3e76988747E6*【资金分流】
    - *0x922D672F7e6E57c6481038e3cf63C529D88bc70d* 【资金分流】
- *Attack Contract : 0xc30808d9373093fbfcec9e026457c6a9dab706a7*
- Attack Tx : *0x50da0b1b6e34bce59769157df769eb45fa11efc7d0e292900d6b0a86ae66a2b3*
- *Vulnerable Contract : 0x34bd6dba456bc31c2b3393e499fa10bed32a9370 (Proxy)*
- *Vulnerable Contract : 0x93c175439726797dcee24d08e4ac9164e88e7aee (Logic)*
- *Pair(EGD, USD)：0xa361433E409Adac1f87CDF133127585F8a93c67d [Pancake LPs (Cake-LP)]*
- *Pair(WBNB, USD)：0x16b9a82891338f9bA80E2D6970FddA79D1eb0daE [PancakeSwap: WBNB-BSC-USD]*
- 



#### 资金流向



#### 攻击流程



#### 解析攻击步骤



#### 攻击复现



#### 总结与建议







