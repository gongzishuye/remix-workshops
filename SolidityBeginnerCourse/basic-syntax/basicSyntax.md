在本节中，我们将创建我们的第一个智能合约。该合约仅包含一个字符串，其中包含值"Hello World!"。

在第一行中，我们应指定要使用的许可证。您可以在此处找到非常全的许可证列表：<a href="https://spdx.org/licenses/" target="_blank">https://spdx.org/licenses/</a>.

使用`pragma`关键字（第3行），我们指定Solidity版本，编译器应使用该版本。在这种情况下，它应大于或等于`0.8.3`但小于`0.9.0`。

我们用关键字`contract`定义了一个合约，并为其命名，在本例中为`HelloWorld`（第5行）。

在合约内部，我们定义了一个状态变量`greet`，其中包含字符串`"Hello World!"`（第6行）。

Solidity是一种静态类型语言，这意味着您需要在声明变量时指定变量类型。 在这种情况下，`greet`是一个`string`。

我们还定义了变量的可见性，它指定从哪里可以访问它。 在这种情况下，它是`public`类型的变量，在合约内外都可以访问。

如果您不理解可见性、数据类型或状态变量等概念，不要担心。我们将在接下来的章节中详细讲解.

为了帮助您理解代码，我们将所有后续章节链接到 Solidity 示例合约的<a href="https://www.youtube.com/channel/UCJWh7F3AFyQ_x01VKzr9eyA" target="_blank">创建者</a>制作的视频教程。

<a href="https://www.youtube.com/watch?v=g_t0Td4Kr6M" target="_blank">观看有关基本语法的视频教程。</a>.

## ⭐️ 作业
1. 删除 HelloWorld 合约及其内容。
2. 创建一个名为 "MyContract" 的新合约。
3. 该合约应具有名为 "name" 的公共状态变量，类型为字符串。
4. 将值 "Alice" 分配给您的新变量。