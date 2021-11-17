## 介绍

Handshake is a UTXO-based blockchain protocol which manages the registration,
renewal and transfer of DNS top-level domains (TLDs). Our naming protocol
differs from its predecessors in that it has no concept of namespacing or
subdomains at the consensus layer. Its purpose is _not_ to replace DNS,
but to replace the root zone file and the root servers.

Handshake 是一种基于未使用的交易输出（UTXO）的区块链协议，旨在管理 DNS 顶级域名的注册，更新以及转移。
我们的命名协议区别于以往命名的协议，在共识层上没有命名空间和子域名的概念。
它的目的不是取代 DNS，而是取代根 ZONE 文件和根服务器。

The full node daemon, [hsd](https://github.com/handshake-org/hsd),
is written in Javascript and is a fork of [bcoin](https://bcoin.io). By
running a full node, you can participate in securing the network and
serving the root zone file embedded in the blockchain.

完整节点守护进程 [hsd](https://github.com/handshake-org/hsd) 使用 Javascript 编程语言实现，
它是 [bcoin](https://bcoin.io) 的一个分叉。
通过运行一个完整的节点，您可以参与保护网络安全及将根 ZONE 文件嵌入到区块链中。

We also have a light client, [hnsd](https://github.com/handshake-org/hnsd),
which is written in C. It can verify blockchain data and serve provable
resource records without having the resource requirements of a full node.
It also acts as an authoritative name server over the Handshake root zone,
and a recursive name server pointed at the authoritative name server.

我们也用 C 语言实现了一个轻客户端 [hnsd](https://github.com/handshake-org/hnsd)，
它可以验证区块链数据并提供可证明的资源记录，而不需要完整节点的资源需求。
它还充当 Handshake 根区域上的权威名称服务器，以及指向权威名称服务器的递归名称服务器。

By installing and/or contributing to Handshake, you are participating in a
decentralized open platform owned by the commons.

通过安装 Handshake 或是对 Handshake 作出贡献，你将参与到一个由所有人共同拥有的去中心化的开放平台。

### 源代码

The latest source code is available on
[GitHub](https://github.com/handshake-org) under the
[MIT license](https://opensource.org/licenses/mit-license.php).

最新的源代码以 [MIT 协议](https://opensource.org/licenses/mit-license.php)在
[GitHub](https://github.com/handshake-org) 开源。

### 代币

Handshake utilizes a utility coin system for name registration.
Handshake depends on the free and open source community to take ownership
and decentralize the system [https://handshake.org](https://handshake.org).

Handshake 使用功能代币系统进行名称注册。Handshake 依赖于自由和开源社区来获得所有权并实现去中心化系统
[https://handshake.org](https://handshake.org)。

### 开发者社区

-   IRC: irc.freenode.net: #handshake.
-   Telegram: [Handshake Dev Chat](https://t.me/hns_tech).
