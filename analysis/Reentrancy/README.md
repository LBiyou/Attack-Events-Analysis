#### 前言

>  重入攻击收录： [reentrancy-attacks](https://github.com/pcaversaccio/reentrancy-attacks)
>
> 对于重入攻击的攻击模式简单概括：当一个函数对另一个不受信任的合约进行外部调用时，重入攻击就有可能发生。
>
> 目前可以将重入攻击分为三种类型
>
> 1. 单函数重入 (Single Function Reentrancy)
> 2. 跨函数重入 (Cross-Function Reentrancy)
> 3. 跨合约重入 (Cross-Contract Reentrancy)