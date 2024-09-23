# 笔记

## 基本运算


### $\ln(x)$

$$
\ln(ab) = \ln a + \ln b
,
\ln\left(\frac{a}{b}\right) = \ln a - \ln b
,
\ln(a^b) = b \ln a
$$
$$
\begin{aligned}
\text{常用公式}:\ln\sqrt{x}&=\frac{1}{2}\ln x \\ \ln\frac{1}{x}&=-\ln x \\ \ln\biggl(1+\frac{1}{x}\biggr)&=\ln\frac{x+1}{x}=\ln(x+1)-\ln x
\end{aligned}
$$

### $x^n$
$$
\begin{aligned}
a^{\alpha}\bullet a^{\beta}=a^{\alpha+\beta} , \frac{a^{\alpha}}{a^{\beta}}=a^{\alpha-\beta} , (a^{\alpha})^{\beta}=a^{\alpha\beta} , (ab)^{\alpha}=a^{\alpha}b^{\alpha} , \left(\frac{a}{b}\right)^{\alpha}=\frac{a^{\alpha}}{b^{\alpha}} 

\end{aligned}
$$


$$
\begin{aligned}
\text{常用公式}:x&=\mathrm{e}^{\ln x}(x>0)\\ u^{\nu}&=\mathrm{e}^{\ln u^{\nu}}=\mathrm{e}^{\nu\ln u}(u>0)
\end{aligned}
$$

### 重要极限公式

$\lim_{\mathrm{x}\to0^+}\mathrm{x}^\alpha\ln$x=0 其中$a>0$

$\operatorname* { lim} _{\mathbf{x} \to 0^{+ }}$ $\mathbf{x} ^{\alpha }( \ln$x$) ^\mathrm{k} = 0$ 其中$\alpha > 0$, $\mathbf{k} > 0$

$\lim _{\mathrm{x} \to + \infty }$ $x^{\alpha }e^{- \delta \mathrm{x} }$= 0 其中$\alpha > 0$, $\delta > 0$

$\lim _{\mathrm{x\to 0}}\frac {\sin \mathrm{x} }{\mathrm{x} }= 1$ $\Longrightarrow \lim _{\mathrm{\phi ( x) \to 0}}\frac {\sin \mathrm{\phi ( x) }}{\mathrm{\phi ( x) }}= 1$ 其中$\phi($x$)\neq0$

$\lim_{\mathrm{x\to0}}(1+$x$)^\frac1x=$e $\Longrightarrow \lim _\mathrm{\phi ( x) \to 0}( 1+ \phi ($x$))^\frac1{\phi(x)}=$e 其中$\phi($x$)\neq0$

$\lim_{\text{n}\to\infty}\sqrt[\text{n}]{\text{n}}=1$

$\lim _{\mathrm{n} \to \infty }\sqrt [ n] {\mathrm{a} }= 1$ (常数a>0)


### 常用等价无穷小

x$\to0$时，

$$
\sin\mathrm{x}\sim\tan\mathrm{x}\sim\arcsin\mathrm{x}\sim\arctan\mathrm{x}\sim(\mathrm{e}^\mathrm{x}-1)\sim\ln(1+\mathrm{x})\sim\mathrm{x}\:
$$
$$
\:1-\cos\mathrm{x}\sim\frac{1}{2}\mathrm{x}^2\: 
$$

$$
(1+x)^a-1\sim ax~
$$
$$
~a^x-1\sim x\ln a~(a>0,a\neq1)
$$


### $(x)\prime$基本初等函数的导数公式
$$
\begin{aligned}
(x^a) ^\prime  &=ax^{a- 1} (a为常数)
\\
( a^x) ^\prime  &= a^x\ln a
\\
(\mathrm{e}^{\mathrm{x}})^{\prime} &=\mathrm{e}^{\mathrm{x}}
\\
(\log_{\mathrm{a}}x) ^\prime  &= \frac 1{\mathrm{x} \ln \mathrm{a} } (a>0,a\neq1)
\\
(\ln x )^\prime &=\frac1x   
\\
(\sin x )^\prime &=\cos x  
\\
(\cos x )^\prime &=-\sin x  
\\
\left(\arcsin\text{x}\right)^{\prime} &=\frac1{\sqrt{1-\mathrm{x}^2}}   
\\
(\arccos x )^\prime &=-\frac1{\sqrt{1-\mathrm{x}^2}}   
\\
(\tan x )^\prime &=\sec^2 x  
\\
\left(\cot\text{x}\right)^{\prime} &=-\csc^2 x  
\\
(\arctan x )^\prime &=\frac1{1+\mathrm{x}^2}   
\\
(\operatorname{arccot} x )^\prime &=-\frac1{1+\mathrm{x}^2}   
\\
\left ( \sec \text{x}\right ) ^{\prime } &= \sec x \cdot \tan x  
\\
\left(\csc x\right)^{\prime} &=-\csc x\cdot\cot x
\\
[\ln(\mathrm x+\sqrt{\mathrm x^2+1})]' &=\dfrac{1}{\sqrt{\mathrm x^2+1}}
\\
[\ln(\mathrm x+\sqrt{\mathrm x^2-1})]' &=\dfrac{1}{\sqrt{\mathrm x^2-1}}
\end{aligned}
$$

### 高阶导数的运算
$$
\mathrm{[u\pm v]^{(n)}=u^{(n)}\pm v^{(n)}}
$$

$$
\begin{aligned}\left(\mathrm{uv}\right)^{\left(\mathrm{n}\right)}&=\mathrm{u^{(n)}v+C_n^1u^{(n-1)}v^{\prime}+C_n^2u^{(n-2)}v^{\prime\prime}+...+C_n^ku^{(n-k)}v^{(k)}+...+C_n^{n-1}u^{\prime}v^{(n-1)}+uv^{(n)}}\\&=\sum_{\mathrm{k=0}}^\mathrm{n}\mathrm{C_n^ku^{(n-k)}v^{(k)}}\end{aligned}
$$


###  $\int$ 基本积分公式


以下公式中,$\alpha$与$a$均为常数,除声明者外,$a>0$
$$
\begin{aligned}
\int\mathrm x^a\mathrm d\mathrm x&=\frac{1}{\alpha+1}\mathrm x^{\alpha+1}+\mathrm C\quad(\alpha\neq-1)
\\
\int\frac{1}{\mathrm{x}}dx&=\ln|x|+C
\\
\int a^{x}dx&=\frac {a^{x}}{\ln a}+ C\:( a> 0, a\neq1) 
\\
\int e^xdx&= e^x+ C
\\
\int\sin\mathrm{xdx}&=-\cos\mathrm{x}+\mathrm{C}
\\
\int\cos\mathrm{xdx}&=\sin\mathrm{x}+\mathrm{C}
\\
\int\tan xdx&=-\ln\cos |x|+C
\\
\int\cot\mathrm{xdx}&=\ln|\sin\mathrm{x}|+\mathrm{C}
\\
\int\sec\mathrm{xdx}&=\ln|\sec\mathrm{x}+\tan\mathrm{x}|+\mathrm{C}
\\
\int\csc\mathrm{xdx}&=\ln|\csc\mathrm{x}-\cot\mathrm{x}|+\mathrm{C}
\\
\int\sec^{2}xdx&=\tan x+C
\\
\int\csc^{2}xdx&=-\cot x+C
\\
\int\frac{1}{\mathrm{a}^{2}+\mathrm{x}^{2}}dx&=\frac1{\mathrm{a}}\arctan\frac{\mathrm{x}}{\mathrm{a}}+C
\\
\int\frac{1}{\mathrm{a}^{2}-\mathrm{x}^{2}}dx&=\frac1{2\mathrm{a}}\ln|\frac{\mathrm{a}+\mathrm{x}}{\mathrm{a}-\mathrm{x}}|+C
\\
\int\frac{1}{\sqrt{\mathrm{a}^{2}-\mathrm{x}^{2}}}dx&=\arcsin\frac{\mathrm{x}}{\mathrm{a}}+C
\\
\int\frac1{\sqrt{\mathrm{x}^2\pm\mathrm{a}^2}}\:\mathrm{dx}&=\ln|\mathrm{x}+\sqrt{\mathrm{x}^2\pm\mathrm{a}^2}|+\mathrm{C}
\end{aligned}
$$

### $\int$ 重要积分公式


$$\int_{-\infty}^{+\infty}\mathrm{~e^{-x^2}dx}=2\int_0^{+\infty}\mathrm{~e^{-x^2}dx}=\sqrt{\pi}$$

$$\int_0^{+\infty}\mathrm{x^ne^{-x}dx=n!}$$ 

$$\mathrm{\int_{-a}^af(x)dx=\int_0^a[f(x)+f(-x)]dx}$$

$$\int_0^\pi\mathrm{xf(\sin x)dx}=\frac\pi2\int_0^\pi\mathrm{f(\sin x)dx}=\pi\int_0^{\frac\pi2}\mathrm{f(\sin x)dx}$$

$$\int_\mathrm{a}^\mathrm{b}\mathrm{f(x)dx}=(\mathrm{b-a})\int_0^1\mathrm{f[a+(b-a)x]dx}$$


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

出现$\ln$时可以用$1=\ln e$来凑,也可能
$\sin^2\alpha+\cos^2\alpha=1$

$\infin \text{是两个点，要小心，因为函数唯一性}$

给出$e^x$求$a^x$要变换成$e^{x\ln a}$ ($\mathrm{e}^{x}=\sum_{n=0}^{\infty}\frac{x^{n}}{n!}$)

没思路可以尝试逆运算