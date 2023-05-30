在本课程的这部分中，我们将为您介绍基于区块链的代币理论。

区块链代币是由区块链技术创建的模块（就像网站对互联网），它实现了去中心化、主权独立的互联网（Web3）。

### 简介
在Web3环境下，代币表示所有权。代币可以表示任何东西的所有权：艺术品、声誉、视频游戏中的物品、公司股份、投票权或货币等。

区块链技术所具备革命性创新之处在于它允许数据以不可变（无法更改）方式公开存储。这种新形式的数据存储方式使我们能够跟踪所有权并首次实现真正可拥有数字物品。

最初发明区块链技术是为了跟踪比特币的所有权（比特币是一种去中心化数字货币和同质化代币）。

### 同质化和非同质化代币
像钱这样的资产：比特币或一美元纸钞，例如都是同质化资产。同质意味着所有资产都相同且可以互换。而像艺术品、收藏品或房屋等资产则是非同质化的，它们都不同且不能互换。

我们可以将代币分为这两种类型：同质化代币，其中所有代币都相同；以及非同质化代币（NFTs），其中每个代币都是独一无二的。

### 代币标准
一个代币的行为是在其智能合约（代币合约）中指定的。该合约可以包括转移代币或检查其总供应量等功能。

如果每个人都创建自己具有不同行为和命名惯例的代币合约，那么人们将很难构建与其他人交互的合约或应用程序。

以太坊社区已经开发了代币标准，定义了开发者如何创建可与其他合约、产品和服务进行交互（即可互操作）的代币。根据这些标准开发的合约需要包括一定数量的函数和事件。

最流行的代币标准是 ERC20 用于同质化代币和 ERC721 用于非同质化代币。在本课程中，我们将学习如何在以下章节中创建并与 ERC20 代币标准进行交互。

如果您想了解更多关于 NFT 和 ERC721 代币标准，请参阅 **Learneth NFT 课程** 。

ERC777 是一种同质化代币标准，类似于 ERC20，在保持向后兼容性时包含更高级别特性，例如hooks。请通过其 <a href="https://eips.ethereum.org/EIPS/eip-777" target="_blank">EIP（以太坊改进提案）</a>了解有关 ERC777 的更多信息。

ERC1155 是一种多代币标准，允许单个合约管理不同类型的代币，例如可同质化、非同质化或半同质化代币。请通过其 <a href="https://eips.ethereum.org/EIPS/eip-1155" target="_blank">EIP</a> 了解有关 ERC1155 的更多信息。

## ⭐️ 作业
对于这个作业，我们将通过一个简短的测验来测试您的知识。在`Quiz`合约（第4行）中，将最佳答案的编号分配给变量`question1`（第5行），`question2`（第6行），`question3`（第7行）。

### 问题1：
为什么基于区块链的代币如此具有革命性？
1. 因为人们现在可以匿名投资。
2. 因为它们代表了可拥有和转让的数字资产所有权。
3. 因为你可以使用代币进行交易而无需支付税款。

### 问题2：
社区为什么创建了代币标准？
1. 以便社区可以控制和批准所创建的代币。
2. 限制代币功能以进行安全和非恶意操作。
3. 使社区能够创建与其他合约、产品和服务互通的代币。

### Question 3:
如果您要为棒球交易卡牌游戏创建一个去中心化应用程序，其中每个棒球选手都将由一个代币表示，那么您会使用哪种标准编写该代币合约？
1. ERC20
2. ERC721