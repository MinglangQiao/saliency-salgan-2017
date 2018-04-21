#### 1. unsample layer是怎么实现的？

#### 2. sigmoid形式？
https://baike.baidu.com/item/Sigmoid%E5%87%BD%E6%95%B0/7981407?fr=aladdin

#### 2.1 softmax的形式？
https://www.zhihu.com/question/23765351

#### 3. Conv-Scratch 是什么？

#### 4. MSE aim at maximizing the PSNR?

#### 5. 交叉熵， binary cross entropies (BCE)的定义？
[这个讲得好](https://hit-scir.gitbooks.io/neural-networks-and-deep-learning-zh_cn/content/chap3/c3s1.html)

<a href="https://www.codecogs.com/eqnedit.php?latex=C&space;=&space;-\frac{1}{N}\sum_{x}[ylna&space;&plus;&space;(1-y)ln(1-a)]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C&space;=&space;-\frac{1}{N}\sum_{x}[ylna&space;&plus;&space;(1-y)ln(1-a)]" title="C = -\frac{1}{N}\sum_{x}[ylna + (1-y)ln(1-a)]" /></a>

这里a是网络的实际输出值，y是我们期待的输出值，实际上就是我们给的监督数据的值（label/groundtruth），比如我们期望y是1， 在实际计算时就令y=1.加和符号覆盖了所有的训练输入 x
