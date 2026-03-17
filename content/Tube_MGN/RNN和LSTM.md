# RNN和LSTM介绍
## 1.RNN（递归/循环神经网络）

```{figure} images/RNN_LSTM/RNN架构.png
:width: 700px
:align: center

```
最后一步的输出即为我们想要的预测值，对于反向传播，需要从当前层持续向前传播，直至到x0为止

缺点：信息会越存越多，变得不好，应该适当忘记和保存

## 2.LSTM（长短记忆网络）

```{figure} images/RNN_LSTM/lstm_1.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_2.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_3.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_4.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_5.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_6.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_7.png
:width: 700px
:align: center

```
```{figure} images/RNN_LSTM/lstm_8.png
:width: 700px
:align: center

```