在本节中，我们将学习更多关于函数的输入和输出。

### 多个命名输出
函数可以返回多个值，并且这些值可以被命名并给这些名称赋值。

`returnMany` 函数（第6行）展示了如何返回多个值。你经常会需要返回多个值。例如，可能是一个收集各种函数输出并在单个函数调用中返回它们的函数。

`named` 函数（第19行）展示了如何为返回值命名。
给返回值命名有助于提高合约的可读性。 命名的返回值可以更容易跟踪这些数值及其被返回的顺序。您还可以将数值分配到名称上。

`assigned` 函数（第33行）展示了如何将数值分配到名称上。当您将数值分配到名称时，您可以省略 `return` 语句并逐一地进行分配。

### 解构赋值
您可以使用解构赋值来拆开不同变量中存储的数据。

`destructingAssigments` 函数（第49行）将 `returnMany` 函数的结果赋给新定义的局部变量 `i`、`b` 和 `j`（第60行）。

### 输入和输出限制
对于合约函数的输入和输出参数，有一些限制和最佳实践。

[Mappings] 不能用作公开可见的合约函数的传入参数或返回参数。
来自<a href="https://docs.soliditylang.org/en/latest/types.html#mapping-types" target="_blank">Solidity 文档</a>.

数组可以用作参数，如在函数`arrayInput`（第71行）中所示。数组也可以用作返回参数，如在函数`arrayOutput`（第76行）中所示。

由于燃气消耗有限制，您必须谨慎使用任意大小的数组。使用非常大的数组作为输入可能会导致燃气成本过高而失败，但使用较小的数组便能够执行。

<a href="https://www.youtube.com/watch?v=je7dWT6bEZM" target="_blank">Watch a video tutorial on Function Outputs</a>.

## ⭐️ 作业
创建一个名为`returnTwo`的新函数，在不使用return语句的情况下返回值`-2`和`true`。