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



$(2)y=\frac{\mathrm{e}^x+\mathrm{e}^{-x}}{2}$叫作双曲余弦函数，其图像如图 1-4所示，它是偶函数，是一种特殊的悬链线，约翰·伯努利解决了这个问题那不是抛物线$y=x^2$,而是悬链线$y=\frac\alpha2\left(\mathrm{e}^{\frac x\alpha}+\mathrm{e}^{\frac x\alpha}\right)$,取$a=1$,便是此例.

![](https://storage.simpletex.cn/view/fXB9PaFt2dX0l5raFc9xkRXYepPdcg5oC)



## 思路

碰到 ln 想到负号