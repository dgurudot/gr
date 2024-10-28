# **重入计数**

## 目的：

- 此设置允许您调整我们在最终下达市价单之前重试带偏移限价单的次数。

## 示例：

- 如果您的重试次数为 1，则信号将首先尝试以信号中收到的价格填写订单。
- 如果没有完成，则只有 1 次重试（基于重试计数设置，可以更改），并且它将使用 Ask 加上偏移量作为买入信号或 Bid 减去偏移量作为卖出信号。
- 一旦重试尝试用尽，就会下达市价单。