# 智能合约简介


智能合约的概念于1994年由[Nick Szabo][1]首次提出，并随着以太坊的发布和流行被广泛应用。智能合约原意为“由数字化方式传播、执行、验证的计算机合约代码”，在区块链的大背景下，智能合约（下面都特指区块链智能合约）指的是在区块链上由全网共同见证和执行的程序代码。

智能合约和传统计算机程序最大的区别在于其执行结果的认可度。传统计算机程序的执行结果没有建立在共识机制上，所以其结果不必然被其他实体信任。举例来说，一个中心化的网络游戏永远无法向用户证明其某种物品掉落概率的设定数值是多少。智能合约的代码保存、运算（或验证）则是由全网节点共识后的结果，因此其业务逻辑、执行结果都是可信且确认得到其他参与方认可的。

智能合约的优势或者说把业务逻辑放到区块链上执行的优势主要有两点：

 - 可信，便于用户使用
 - 开放，便于开发者协作，形成生态

目前最流行的智能合约可以说是ERC20/ERC721资产合约和ICO众筹合约了。其中资产合约将资产总量、产权等信息完全公开且交由持有人操作，极大地提升了业务的可信度。此外，资产合约的开放性使得任何人都可以基于其制作新的智能合约与之交互，例如对赌合约、衍生品合约等。

相对来说，智能合约也有一些缺点。例如不易调试、不能自动执行（需要主动发起调用）、出现错误难以修改等。自智能合约流行以来，累计出现的合约漏洞粗略估计已经造成数亿美金的损失。因此，开发者在正式发布智能合约前应该使用安全合约框架并经过充分的测试。

[1]: https://www.wikiwand.com/zh-hans/Nick_Szabo