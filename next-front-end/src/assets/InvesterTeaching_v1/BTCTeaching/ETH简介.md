# 以太坊(ETH)简介
　　ETH是什么币？ETH币全称Ethereum，中文名称以太坊，ETH是一个开源的有智能合约功能的公共区块链平台。通过其专用加密货币以太币（Ether，又称“以太币”）提供去中心化的虚拟机（称为“以太虚拟机”Ethereum Virtual Machine）来处理点对点合约。

　　以太坊的概念首次在2013至2014年间由程序员Vitalik Buterin，受比特币启发后提出，大意为“下一代加密货币与去中心化应用平台”，在2014年通过ICO众筹得以开始发展。

　　截至2018年2月，以太币是市值第二高的加密货币，仅次于比特币。

### ETH特点
相较于较大多数其他加密货币或区块链技术，以太坊的特点包括下列：

* 智能合约（smart contract）：存储在区块链上的程序，由各节点运行，需要运行程序的人支付手续费给节点的矿工或权益人。

* 代币（tokens）：智能合约可以创造代币供分布式应用程序使用。分布式应用程序的代币化让用户、投资者以及管理者的利益一致。代币也可以用来进行首次代币发行。

* 叔块（uncle block）：将因为速度较慢而未及时被收入母链的较短区块链并入，以提升交易量。使用的是有向无环图的相关技术。

* 权益证明（proof-of-stake）：相较于工作量证明更有效率，可节省大量在挖矿时浪费的电脑资源，并避免特殊应用集成电路造成网络中心化。（测试中）

* 支链（Plasma）：用较小的分支区块链运算，只将最后结果写入主链，可提升供单位时间的工作量。（尚未实现）

* 状态通道（state channels）：原理类似比特币的闪雷网络，可提升交易速度、降低区块链的负担，并提高可扩展性。尚未实现，开发团队包括雷电网络（Raiden Network）和移动性网络（Liquidity Network）。

* 分片（sharding）：减少每个节点所需纪录的数据量，并通过平行运算提升效率（尚未实现）。


### 起源

　　以太坊最初由 Vitalik Buterin 在2013年提出。Vitalik 本是一名参与比特币社区的程序员，曾向比特币核心开发人员主张比特币平台应该要有个更完善的编程语言让人开发程序，但未得到他们的同意，因此决定开发一个新的平台作此用途:88。Buterin 认为很多程序都可以用类似比特币的原理来达成进一步的发展。Buterin 在2013年写下了《以太坊白皮书》，说明了建造去中心化程序的目标。然后2014年通过网络公开募资得到开发的资金，投资人用比特币向基金会购买以太币。

　　最初以太坊程序是由一间位在瑞士的公司 Ethereum Switzerland GmbH 开发，之后转移至一个非营利机构“以太坊基金会”（Ethereum Foundation）。

　　在平台开始发展的最初，有人称赞以太坊的科技创新，但也有人质疑其安全和可扩展性。

1. 激活：边境

　　以太坊的公共区块链在2015年7月30日引导。最初的以太坊版本称为边境（Frontier，也有“前锋”的意思），用的是工作量证明（proof-of-work）的算法，但未来预期会转换成权益证明（proof-of-stake）:32。

2. 硬分叉

　　自最初版本以来，以太坊网络成功进行了数次硬分叉。第一次分叉调整了未来挖矿的难度，确保未来的用户会有转换至权益证明的动机。目前第五个分叉正在开发中。

3. 第二次分叉：家园

　　2016年春季进行了第二次分叉，发布了第一个稳定版本，称作“家园”（Homestead）。

4. 第三次分叉：DAO和区块链分叉

　　2016年六月，以太坊上的一个去中心化自治组织 The DAO 被骇，造成市值五千万美元的以太币被移动到只有该黑客可以控制的“分身DAO”。因为程序不允许黑客立即提取这些以太币，以太坊用户有时间讨论如何处理此事，考虑的方案包括取回以太币和关闭DAO，而DAO去中心化的本质也表示没有中央权力可以立即反应，而需要用户的共识。最后在2016年7月20日，以太坊进行硬分叉，作出一个向后不兼容的改变，让所有的以太币（包括被移动的）回归原处，而不接受此改变的区块链则成为古典以太坊（Ethereum Classic）。这是第一次有主流区块链为了补偿投资人，而通过分叉来更动交易记录。

　　在这次分叉之后，造成了在两个区块链之间进行重放攻击的可能，加上其他网络攻击，让以太坊和古典以太坊又各自进行了数次分叉来避免攻击。

5. 第四次分叉：减重和防DDoS

　　2016年11月底进行了第四次的分叉。这次分叉为区块链减重（de-bloat），并加入一些避免网络攻击的设计。因为沟通疏失，这次分叉短暂造成以太坊的两个主要客户端程序 Parity 和 Geth 失去共识而产生意外的分叉，但问题在数小时内即被找出并修正。

　　以太坊区块链上的代币称为以太币（Ether），代码为ETH，可在许多加密货币的外汇市场上交易，它也是以太坊上用来支付交易手续费和运算服务的媒介 。

　　以太币对其他实体货币的汇率可能在短时间内大幅变化，例如 The DAO 被骇时，对美元的汇率从 $21.50 跌至 $15。

　　Buterin 在 2016 年 4 月售出手上持有的四分之一以太币，造成一些人质疑，而他本人则说这是理财上很合理的分散风险，并引用前比特币开发员 Gavin Andresen 说这一切都还只是一场实验，仍有失败的可能。

### 智能合约

　　主条目：智能合约

　　以太坊最重要的技术贡献就是智能合约。智能合约是存储在区块链上的程序，可以协助和验证合约的谈判和运行。以太坊的智能合约可以数种用图灵完备的编程语言写成。纽约时报称以太坊平台是一台由众多用户构成的网络来运转的公用电脑，并用以太币来分配和支付这台电脑的使用权。经济学人则说明智能合约可以让众多组织的数据库得以用低廉的成本交互，并且让用户写下精密的合约，功能之一是产生去中心化自治组织，也就是一间只是由以太坊合约构成的虚拟公司。

　　因为合约内容公开，合约可以证明其宣称的功能是真实的，例如虚拟赌场可以证明它是公平的。另一方面，合约的公开性也表示如果合约中有漏洞，任何人都可以立刻看到，而修正程序可能会需要一些时间。The DAO 就是一个例子，无法即时阻止。

　　智能合约的许多细节仍在研究中，包括如何验证合约的功能。微软研究院的报告指出要写出完善的合约可能非常困难，讨论了微软开发的一些可以用来验证合约的工具，并提到如果大规模分析各个已发布的合约，可能发现找出大量的漏洞。报告也说可以证明Solidity程序和以太虚拟机编码的等同性。

### 构建不可阻挡的应用程序

　　以太坊是一个分散的平台，运行智能合约：完全按照程序运行的应用程序，没有任何停机，审查，欺诈或第三方干扰的可能性。

　　这些应用程序运行在定制的 区块链上，这是一个非常强大的共享全局基础架构，可以移动价值并代表财产的所有权。

　　这使开发商能够创建市场，存储债务或承诺的登记，根据过去很久的指示(如遗嘱或期货合约)和许多其他尚未发明的东西转移资金，所有这些都没有中间人或交易对手风险。

　　该项目于2014年8月由世界各地的粉丝通过以太预售进行自助式预防。它由瑞士非盈利组织以太坊基金会开发，由全球 知名人士提供。

　　在传统的服务器体系结构中，每个应用程序都必须建立自己的服务器，在孤立的孤岛中运行自己的代码，从而使数据共享变得困难。如果单个应用受到威胁或脱机，许多用户和其他应用都会受到影响。

　　在区块链中，任何人都可以设置一个节点，复制所有节点的必要数据以达成协议，并由用户和应用程序开发人员进行补偿。这允许用户数据保持私密，并且应用程序可以像互联网一样分散。

### 聪明的钱，智能钱包

　　在 复仇钱包 是通往上复仇blockchain分布式应用。它允许您保存和保护以太坊上构建的以太网和其他加密资产，以及编写，部署和使用智能合约。

　　学习Solidity，一种智能合约的新语言

　　设计并发布您自己的加密货币

　　创建可交易的数字令牌，可用作货币，资产的表示，虚拟共享，成员证明或任何事物。这些令牌使用标准硬币API，因此您的合同将自动与使用此标准的任何钱包，其他合同或交易所兼容。

　　流通中的令牌总数可以设置为简单的固定数量，也可以根据任何已编程的规则集进行波动。
