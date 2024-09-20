# 笔记

## 基本运算

### ln

$$
\ln(ab) = \ln a + \ln b
$$

$$
\ln\left(\frac{a}{b}\right) = \ln a - \ln b
$$

$$
\ln(a^b) = b \ln a
$$


## 结论

$$
\begin{aligned}
&\textcircled{1}x\to0\text{ 时,}\ln\left(x+\sqrt{x^{2}+1}\right)\sim x . \\
&\textcircled{2}\left[\ln\left(x+\sqrt{x^{2}+1}\right)\right]^{\prime}=\frac{1}{\sqrt{x^{2}+1}} , \text{于是}\int\frac{1}{\sqrt{x^{2}+1}}\mathrm{d}x=\ln\left(x+\sqrt{x^{2}+1}\right)+C . \\
&\textcircled{3}\text{由于}y=\ln\left(x+\sqrt{x^2+1}\right)\text{是奇函数,于是}\int_{-1}^{1}\left[\ln\left(x+\sqrt{x^2+1}\right)+x^2\right]\mathrm{d}x=\int_{-1}^{1}x^2\mathrm{d}x=\frac{2}{3}
\end{aligned}
$$

### 反双曲正弦函数&双曲正弦函数
函数$y=\ln\left(x+\sqrt{x^2+1}\right)$叫作反双曲正弦函数，其图像如图 I-3(a)所示 .函数 $y=\frac{\mathrm{e}^x-\mathrm{e}^{-x}}2$
叫作双曲正弦函数，其图像如图 1-3(b)所示 .考生应记住这两个函数的图像.

![](https://storage.simpletex.cn/view/f71ZkwHDolAkEwnS9ZxKE818riy7lRKIc)


### 双曲余弦函数
$(2)y=\frac{\mathrm{e}^x+\mathrm{e}^{-x}}{2}$叫作双曲余弦函数，其图像如图 1-4所示，它是偶函数，是一种特殊的悬链线，约翰·伯努利解决了这个问题那不是抛物线$y=x^2$,而是悬链线$y=\frac\alpha2\left(\mathrm{e}^{\frac x\alpha}+\mathrm{e}^{\frac x\alpha}\right)$,取$a=1$,便是此例.

![](https://storage.simpletex.cn/view/fXB9PaFt2dX0l5raFc9xkRXYepPdcg5oC)

### 求他们的反函数
$$
y=\ln(x+\sqrt{x^{2}+1})\\-y=-\ln(x+\sqrt{x^{2}+1})\\-y=\ln\frac{(x-\sqrt{x^{2}+1})}{(x+\sqrt{x^{2}+1})(x-\sqrt{x^{2}+1})}\\-y=\ln\frac{(\sqrt{x^{2}+1}-x)}{1}\\e^{y}=x+\sqrt{x^{2}+1}\textcircled{1}\\e^{-y}=\sqrt{x^{2}+1}-x\textcircled{2}\\\textcircled{1}-\textcircled{2}\Rightarrow e^{y}-e^{-y}=2x\Rightarrow x=\frac{e^{y}-e^{-y}}{2}
$$


### 隐函数

设方程$F(x,y)=0$ ,若当$x$ 取某区间内的任一值时，总有满足该方程的唯一的值$y$存在，则称方程$F(x,y)=0$在上述区间内确定了一个隐函数$y= y( x)$ .
如$x+y^3-1=0$ 就表示一个隐函数，且可显化为$y=\sqrt[3]{1-x};$再如$\sin(xy)=\ln\frac{x+e}{y}+1$ 也表示一个隐函数，但不易显化.
一般来说，由$F(x,y)=0$ 所确定的隐函数求 $y(x_0)$,若代人$x_0$易求出$y(x_0)$,则直接求之；若不易求出$y(x_0)$,则用观察法.如：


$$
\textcircled{1}\text{设函数}y=y(x)\text{由方程}\ln y-\frac{x}{y}+x=0\text{确定,当}x=2\text{时,}y(2)=1\\\textcircled{2}\text{设函数}y=y(x)\text{由方程}\ln y+\mathrm{e}^{y-1}=\frac{x}{2}\text{确定,当}x=2\text{时,}y(2)=1
$$

## 思路

碰到 ln 想到负号

复合函数$f(x)g(x)$可以当作运算符

## 注意

平方后开根号是绝对值
$$
\sqrt{u^{2}}=|u|
$$

