# 项目历史

Decred基于2013年4月在Bitcointalk论坛上提出的[Memcoin2加密货币提案](https://decred.org/research/mackenzie2013.pdf)。用户tacotime提出了这种新的加密货币，与另一位Bitcointalk用户_ingsoe和Jake Yocom-Piatt合作，将Memcoin2的混合工作量证明（PoW）/权益证明（PoS）共识系统实现为一个新项目，称为Decred。

这种混合共识系统的主要创新在于它创建了一个PoS治理机制，用户可以选择将其硬币暂时锁定以参加彩票（用户可以选择将dcr暂时冻结，以便参加彩票。这意味着用户必须将一定数量的数字货币存入一个特殊的账户，以便有机会成为共识系统中的验证者，从而有机会赚取奖励。这种冻结数字货币的行为通常被称为“抵押”）。这些用户被称为利益相关者。每个区块会选出多个彩票获胜者参与共识系统，通过投票来决定关于Decred的决策，直接将主权交到利益相关者手中。

相比之下，每个纯PoW加密货币必须主要依赖于其矿工的治理决策，因为他们是唯一执行共识系统并提供其安全性的人。然而，Decred依赖于其利益相关者和矿工共同决定共识和安全性。最终结果是，Decred的混合PoW / PoS共识系统比纯PoW系统更加公平和安全。

Decred的代码是基于[btcsuite代码库](https://github.com/btcsuite/)构建的，这是一种使用Go语言编写的Bitcoin的另一种完整节点实现，由Company 0 , LLC编写。尽管Decred基于Bitcoin的代码，但它是一种独立的加密货币，而不是“Bitcoin分叉”。这项工作始于2014年2月，并在Company 0, LLC的协助下一直持续到2016年2月的主网上线。

## 空投和预挖

在[2016年2月的发布中](https://docs.decred.org/advanced/premine/)，Decred使用了一种创新的空投和小型预挖来引导Decred网络的PoS部分，建立潜在项目贡献者的广泛网络，并为发布前的早期开发人员的工作提供补偿。考虑到分发的必要性，决定采用这种过程是公平、透明的，且从一开始就产生了显著的去中心化。

## 链上治理

自2016年2月21日挖掘第4,096个区块以来，每个Decred区块都至少包含3个彩票（或称为选票）的投票，以批准前一个区块的内容。2017年7月9日，票务的第一次共识投票结束，批准了允许在Decred网络上部署闪电网络功能的更改。

## Politeia

Politeia 于 2018 年 10 月 15 日作为 Decred 的链下提案讨论和投票网站启动，第一次提案投票于 2018 年 11 月 9 日结束。使用 Politeia 构建了承包商管理系统（CMS），自 2019 年 4 月以来，承包商致力于 Decred 项目一直在使用该系统提交发票。这会创建一个无法伪造或篡改的承包商和管理员之间互动的可靠记录。第二种类型的提案是 2020 年添加的提案征求书 (RFP)，允许分两个阶段进行，即在感兴趣的各方提交符合其标准的提案之前，首先批准总体计划。第[一份 RFP 提案](https://proposals.decred.org/record/0917c1d)于 2020 年 9 月 25 日完成，所有候选提案均被拒绝。Politeia 是在基于 git 的后端启动的，该后端带有审查令牌以确保审查的透明度，并于 2021 年 3 月升级[为](https://github.com/decred/politeia/pull/1180)使用[Trillian 日志](https://transparency.dev/)以提高可扩展性和灵活性。

## Decred 时间表

| 日期               | 里程碑                                                                                                                             |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| 2015 年 12 月 15 日 | [Decred 在 bitcointalk 上宣布](https://bitcointalk.org/index.php?topic=1290358.0)                                                   |
| 2016 年 1 月 1 日   | [空投审核完成](https://forum.decred.org/threads/airdrop-rundown.313/)                                                                 |
| 2016 年 2 月 8 日   | [Decred 主网启动](https://explorer.dcrdata.org/block/298e5cc3d985bfe7f81dc135f360abe089edd4396b86d2de66b0cef42b21d980)              |
| 2016 年 2 月 12 日  | [初始权益池发布](https://forum.decred.org/threads/testnet-stake-pool-is-live.626/)                                                     |
| 2016 年 2 月 21 日  | [第一个 PoS 投票包含在区块 4096 中](https://explorer.dcrdata.org/block/00000000000013722f8e5a8af9cf55492e9237e77d29da98695e65fd13033625)   |
| 2016 年 12 月 26 日 | [首次发布适用于 Linux/OSX 的 Decrediton GUI 钱包](https://forum.decred.org/threads/dd-20-v0-7-0-12-26-16.4702/#post-23300)                |
| 2017 年 6 月 14 日  | [最初的 dcrtime 版本](https://blog.decred.org/2017/06/14/dcrtime-Blockchain-based-Timestamps/)                                       |
| 2017 年 7 月 9 日   | [加密货币历史上第一次共识投票改变 Decred 的股权难度算法](https://blog.decred.org/2017/04/03/A-New-Ticket-Price-Algorithm/)                             |
| 2017 年 10 月 19 日 | [支持 Decred、比特币和莱特币的原子交换工具](https://blog.decred.org/2017/09/20/On-Chain-Atomic-Swaps/)                                           |
| 2017 年 10 月 25 日 | [Politeia 宣布](https://blog.decred.org/2017/10/25/Politeia-Proposals-in-a-Timestamped-Filesystem/)                               |
| 2018 年 6 月 9 日   | [DEX 提案发布](https://blog.decred.org/2018/06/05/A-New-Kind-of-DEX/)                                                               |
| 2018 年 9 月 21 日  | [dcrwallet 的初始 SPV 版本](https://github.com/decred/decred-binaries/releases/tag/v1.3.0)                                           |
| 2018 年 10 月 15 日 | [Politeia 在主网上线](https://blog.decred.org/2018/10/15/Politeia-in-Production/)                                                    |
| 2019 年 5 月 9 日   | [闪电网络支持在主网上激活](https://github.com/decred/dcps/blob/master/dcp-0004/dcp-0004.mediawiki)                                          |
| 2019 年 8 月 28 日  | [第一个 CoinShuffle++ 混币在主网上线](https://blog.decred.org/2019/08/28/Iterating-Privacy/)                                              |
| 2019 年 9 月 25 日  | [dcrpool矿池软件初版](https://blog.decred.org/2019/09/25/Introducing-Dcrpool/)                                                        |
| 2019 年 12 月 16 日 | [Decred 软件 v1.5.0 发布](https://github.com/decred/decred-binaries/releases/tag/v1.5.0)                                            |
| 2020 年 2 月 14 日  | [DCP0005 获得批准，启用块头承诺，允许更安全的简化支付验证 (SPV) 钱包](https://github.com/decred/dcps/blob/master/dcp-0005/dcp-0005.mediawiki)             |
| 2021 年 1 月 25 日  | [发布 Decred 软件 v1.6.0，包含第一个 DCRDEX 版本](https://github.com/decred/decred-binaries/releases/tag/v1.6.0)                            |
| 2021 年 4 月 9 日   | [DCP0006获批，启用去中心化金库](https://github.com/decred/dcps/blob/master/dcp-0006/dcp-0006.mediawiki)                                    |
| 2021 年 12 月 28 日 | [从去中心化金库 (tspend) 支付给承包商的第一笔款项](https://dcrdata.decred.org/tx/f57f2f35abcfc58cb8d45da6315982610203c1335ee0d68b36240f22c24a557a) |
| 2022 年 1 月 24 日  | [Decred 软件 v1.7.0 发布](https://github.com/decred/decred-binaries/releases/tag/v1.7.0)                                            |
| 2022 年 4 月 10 日  | [批准 DCP0007（修复资金漏洞）、DCP0008（显式版本升级）、DCP0009（自动票据撤销）和 DCP0010（更改 PoW/PoS 补贴拆分）](https://voting.decred.org/)                      |


