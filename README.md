# Love-Ethereum

----------------------------------------------------------------------------------------

# 区块链学习

------------------------------------------------------------------------------------------

## 版本说明

* [Frontier](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Frontier.md)

  简单的介绍区块链基础知识，通过阅读此版本可以对区块链技术有个初步的认知。
  
* [Homestead](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Homestead.md)

  介绍以太坊项目，并对涉及到的区块链核心技术点进行介绍和分析。

* [Metropolis](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Metropolis.md)

  该本版主要是关于智能合约和Dapp
  
* [Serenlity](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Serenlity.md)
  
  以太坊源码分析

-------------------------------------------------------------------------------------------


# Project progress

## 阅读和整理区块链资料, 制作Frontier ---- 已完成
  
* 已完成Frontier版本,目前正在以太坊私有链上测试和部署 LBJ Token的功能.

* 已完成LBJ　Token的功能测试，LBJ　可以部署在以太坊主网上。

 [点击直达](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Frontier.md)

----------------------------------------------------------------------------------------------------------------------------

## 以太坊私有链上测试和部署一些经典的智能合约 ----进行中

### Solidity

* [Solidity官方文档翻译](https://github.com/xianfeng92/Solidity-Docs)

### Web3 Api

* [Web3 Api](https://github.com/xianfeng92/Web3js-Doc)

### 经典的智能合约案例

* 基于区块链的投票　－－Ballot
* 盲拍 -- Blind Auction
* 权限控制　－－　AccessControl

### 智能合约设计模式

* CD（Controller-Data）模式

### Dapp

* [NBASTAR](https://github.com/xianfeng92/NBASTAR)

* [dog-shop](https://github.com/xianfeng92/dog-shop)


### Dapp开发利器－Truffle

* [Truffle技术文档翻译](https://github.com/xianfeng92/Truffle-Docs)


 [点击直达](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Metropolis.md)
 
----------------------------------------------------------------------------------------------------------------------------

## P2P网络




----------------------------------------------------------------------------------------------------------------------------

## 可信之石(共识算法) ----进行中

在一个分布式系统中，如何保证集群中所有节点中的数据完全相同并且能够对某个提案（Proposal）达成一致是分布式系统正常工作的核心问题，而共识算法就是用来保证分布式系统一致性的方法。无论是 Bitcoin、Ethereum 还是 EOS，作为一个分布式网络，首先需要解决分布式一致性的问题，也就是所有的节点如何对同一个提案或者值达成共识，这一问题在一个所有节点都是可以被信任的分布式集群中都是一个比较难以解决的问题，更不用说存在拜占庭节点的区块链网络中了。


* [共识算法介绍](https://github.com/xianfeng92/Love-Ethereum/blob/master/DistributedSystem/ConsensusAlgorithm.md)

* [Paxos](https://github.com/xianfeng92/Love-Ethereum/blob/master/DistributedSystem/paxos.md)

* [PBFT](https://github.com/xianfeng92/Love-Ethereum/blob/master/DistributedSystem/pbft.md)

* [Proof of Stake FAQs](https://github.com/ethereum/wiki/wiki/Proof-of-Stake-FAQs)


----------------------------------------------------------------------------------------------------------------------------


## 以太坊源码的分析 ---- 进行中

* 目前主要是阅读一些以太坊源码解读的文章

下面的文章主要是CSDN上的一个teaspring的技术专栏里面关于以太坊源代码分析的文章，文章写的超级好，强烈推荐！

* [区块和交易，合约和虚拟机](https://blog.csdn.net/teaspring/article/details/75389151)
* [数据的呈现和组织，缓存和更新](https://blog.csdn.net/teaspring/article/details/75390210)
* [挖矿和共识算法的奥秘](https://blog.csdn.net/teaspring/article/details/78050274)
* [Clique共识算法](https://ethfans.org/posts/Clique-Consensus-Algorithm)
* [ 椭圆曲线密码学和以太坊中的椭圆曲线数字签名算法应用](https://blog.csdn.net/teaspring/article/details/77834360)
* [从钱包到客户端](https://blog.csdn.net/teaspring/article/details/78350888)


 [点击直达](https://github.com/xianfeng92/Love-Ethereum/blob/master/version/Serenlity.md)


----------------------------------------------------------------------------------------------------------------------------

## [Ethresear](https://ethresear.ch/) ---- 进行中

### Sharding

以太坊仍处于初级阶段。现在，它不具备安全性和可扩展性。以太坊和web3期望建设的——一个安全、易用、由一套共同的经济协议约束、可供数十亿人使用的分布式互联网，仍处于发展阶段，直到关键基础设施建成之后才能实现。致力于构建此 __基础架构__ 并扩大以太坊容量的项目通常称为扩容方案。它们有许多不同的形式，并且常常互相兼容或互补。这里我们将主要介绍以太坊关于解决扩容问题的“第1层”和“第2层”解决方案。

* [Sharding FAQ 英文版](https://github.com/ethereum/wiki/wiki/Sharding-FAQs)

* [Sharding FAQ 中文版](https://github.com/xianfeng92/Love-Ethereum/blob/master/notes/ShardingFAQ.md)
 
* [Cross-shard contract yanking](https://github.com/xianfeng92/Love-Ethereum/blob/master/notes/%E8%B7%A8%E5%88%86%E7%89%87%E5%90%88%E7%BA%A6yanking.md)

* [Cross-links between main chain and shards](https://ethresear.ch/t/cross-links-between-main-chain-and-shards/1860)
 
### Casper

### Plasma

### Economics

### Applications

-------------------------------------------------------------------------------------------

# IPFS ----进行中

星际文件系统IPFS（InterPlanetary File System）是一个面向全球的、点对点的分布式版本文件系统，目标是为了补充（甚至是取代）目前统治互联网的超文本传输协议（HTTP），将所有具有相同文件系统的计算设备连接在一起。

* [IPFS基本介绍](https://github.com/xianfeng92/Love-Ethereum/blob/master/notes/IPFS.md)
* [IPFS基本操作](https://github.com/xianfeng92/Love-Ethereum/blob/master/notes/IPFSCommand.md)
* [IPFS项目中的使用](https://github.com/xianfeng92/Love-Ethereum/blob/master/notes/IPFSBlockchain.md)

## Vickrey auction

* [Vickreyauction](https://github.com/xianfeng92/Love-Ethereum/tree/master/Vickreyauction)


# 大事件

## 6月10号EOS主网成功上线
      
      未来已来,只是尚未流行!

这里引用EOS官方的话：

Finally, the moment we have all been working for. After nearly a year long development process and community involvement, we have lift-off! The ideas on a whitepaper are brought to life thanks to all the contribution by a large community of well-wishers!
Together we present EOS, a crypto-economic solution for securing life, liberty, property, and justice for all. Along with other crypto platforms we move toward the same end goal: minimizing corruption and maximizing freedom in society.

"The greatness of a community is most accurately measured by the compassionate actions of its members." 

- Coretta Scott King

--------------------------------------------------------------------------------------------


# 参与贡献

区块链技术自身仍在快速发展中，生态环境也在蓬勃成长。欢迎 [参与维护项目](https://github.com/xianfeng92/Love-Ethereum/blob/master/contribute.md)。


---------------------------------------------------------------------------------------------















