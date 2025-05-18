<div style="float: left; width: 64%; padding: 1%;">

## 一、  <span style="color: Gold;">- </span>的概念与性质

<ul>

### 1. 数列的  <span style="color: Gold;">- </span>

<ul>

如果对于任意给定的 $\varepsilon>0$，总存在正整数 $N$，当 $n>N$ 时，恒有
$$
\left|x_{n}-a\right|<\varepsilon
$$
成立，则称常数 $a$ 为数列 $\left\{x_{n}\right\}$ 当 $n$ 趋于无穷时的  <span style="color: Gold;">- </span>，记为 $\lim _{n \rightarrow \infty} x_{n}=a$。

【注】  
（1）$\varepsilon$ 是用来刻画 $x_{n}$ 与 $a$ 的接近程度，$N$ 是用来刻画 $n \rightarrow \infty$ 这个  <span style="color: Gold;">- </span>过程。  
（2）$\lim _{n \rightarrow \infty} x_{n}=a$ 的几何意义是：对于 $a$ 点的任何 $\varepsilon$ 邻域即开区间 $(a-\varepsilon, a+\varepsilon)$，一定存在 $N$，当 $n>N$ 时，第 $N$ 项以后的点 $x_{n}$ 都落在开区间 $(a-\varepsilon, a+\varepsilon)$ 内，而只有有限个（最多有 $N$ 个）在这区间之外。  
（3）数列 $\left\{x_{n}\right\}$ 的  <span style="color: Gold;">- </span>是否存在，如果存在，  <span style="color: Gold;">- </span>值等于多少，与数列的前有限项无关。  
（4）如果一个数列有  <span style="color: Gold;">- </span>，也称该数列收敛，否则就称发散。  
（5）记住下列  <span style="color: Gold;">- </span>结果：  
  - $\lim _{n \rightarrow \infty} q^{n}=0(|q|<1)$  
  - $\lim _{n \rightarrow \infty} \frac{1}{n^{n}}=0(a>0)$  
（6）若数列 $\left\{x_{n}\right\}$ 收敛于 $a$，则其任一子数列也收敛于 $a$。  
定理：$\lim _{n \rightarrow \infty} x_{n}=a$ 的充分必要条件是 $\lim _{n \rightarrow \infty} x_{2 n-1}=\lim _{n \rightarrow \infty} x_{2 n}=a$。  
推论：若 $\lim _{n \rightarrow \infty} x_{2 n-1}=a, \lim _{n \rightarrow \infty} x_{2 n}=b$，且 $a \neq b$，则 $\lim _{n \rightarrow \infty} x_{n}$ 不存在。

</ul>

### 2.  <span style="color: LightSkyBlue;">~</span>的  <span style="color: Gold;">- </span>

<ul>

#### 自变量趋于无穷大时 <span style="color: LightSkyBlue;">~</span>的  <span style="color: Gold;">- </span>

<ul>

- 若对任意给定的 $\varepsilon>0$，总存在 $X>0$，当 $x>X$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 $f(x)$ 当 $x \rightarrow+\infty$ 时的  <span style="color: Gold;">- </span>，记为 $\lim _{x \rightarrow+\infty} f(x)=A$。  
- 若对任意给定的 $\varepsilon>0$，总存在 $X>0$，当 $x<-X$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 $f(x)$ 当 $x \rightarrow-\infty$ 时的  <span style="color: Gold;">- </span>，记为 $\lim _{x \rightarrow-\infty} f(x)=A$。  
- 若对任意给定的 $\varepsilon>0$，总存在 $X>0$，当 $|x|>X$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 $f(x)$ 当 $x \rightarrow \infty$ 时的  <span style="color: Gold;">- </span>，记为 $\lim _{x \rightarrow \infty} f(x)=A$。  

【注】  
（1）这里的 $x \rightarrow \infty$ 是指 $|x| \rightarrow+\infty$；而数列  <span style="color: Gold;">- </span>中的 $n \rightarrow \infty$ 是指 $n \rightarrow+\infty$。  
(2) 记住以下  <span style="color: Gold;">- </span>结果:  
  - $\lim _{x \rightarrow \infty} \frac{1}{x^{n}}=0(a>0)$。  
  - 当 $0<a<1$ 时, $\lim _{x \rightarrow+\infty} a^{x}=0, \lim _{x \rightarrow-\infty} a^{x}=+\infty$ (不存在)；  
    当 $a>1$ 时, $\lim _{x \rightarrow-\infty} a^{x}=0, \lim _{x \rightarrow+\infty} a^{x}=+\infty$ (不存在)。  
  - $\lim _{x \rightarrow-\infty} \arctan x=-\frac{\pi}{2}, \lim _{x \rightarrow+\infty} \arctan x=\frac{\pi}{2}$。  

定理：$\lim _{x \rightarrow \infty} f(x)=A$ 的充分必要条件是 $\lim _{x \rightarrow-\infty} f(x)=\lim _{x \rightarrow+\infty} f(x)=A$。  
推论：若 $\lim _{x \rightarrow+\infty} f(x), \lim _{x \rightarrow-\infty} f(x)$ 至少有一个  <span style="color: Gold;">- </span>不存在或都存在但不相等，则 $\lim _{x \rightarrow \infty} f(x)$ 不存在。

</ul>

#### 自变量趋于有限值时 <span style="color: LightSkyBlue;">~</span>的  <span style="color: Gold;">- </span>

<ul>

若对任意给定的 $\varepsilon>0$，总存在 $\delta>0$，当 $0<\left|x-x_{0}\right|<\delta$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 <span style="color: LightSkyBlue;">~</span> $f(x)$ 当 $x \rightarrow x_{0}$ 时的  <span style="color: Gold;">- </span>，记为 $\lim _{x \rightarrow x_{0}} f(x)=A$。

【注】  
(1) $\varepsilon$ 是用来刻画 $f(x)$ 与 $A$ 的接近程度, $\delta$ 是用来刻画 $x \rightarrow x_{0}$ 这个  <span style="color: Gold;">- </span>过程。  
(2) 几何意义: 对任意给定的 $\varepsilon>0$，总存在 $\hat{U}\left(x_{0}, \delta\right)$，当 $x \in \hat{U}\left(x_{0}, \delta\right)$ 时，曲线 $y=f(x)$ 夹在两直线 $y=A-\varepsilon$ 和 $y=A+\varepsilon$ 之间。  
(3) 这里 $x \rightarrow x_{0}$，但 $x \neq x_{0}$。  <span style="color: Gold;">- </span> $\lim _{x \rightarrow x_{0}} f(x)$ 是否存在，如果存在，  <span style="color: Gold;">- </span>值等于多少，与 $f(x)$ 在 $x=x_{0}$ 处有没有定义，如果有定义， <span style="color: LightSkyBlue;">~</span>值等于多少无关，只与 $x=x_{0}$ 的去心邻域 $\hat{U}\left(x_{0}, \delta\right)$  <span style="color: LightSkyBlue;">~</span>值有关。而要使 $\lim _{x \rightarrow x_{0}} f(x)$ 存在，$f(x)$ 必须在 $x=x_{0}$ 的某去心邻域 $\hat{U}\left(x_{0}, \delta\right)$ 处处有定义。

- 若对任意给定的 $\varepsilon>0$，总存在 $\delta>0$，当 $x_{0}-\delta<x<x_{0}$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 <span style="color: LightSkyBlue;">~</span> $f(x)$ 当 $x \rightarrow x_{0}^{-}$ 时的左  <span style="color: Gold;">- </span>，记为
$$
\lim _{x \rightarrow x_{0}^{-}} f(x)=A, \text{ 或 } f\left(x_{0}^{-}\right)=A, \text{ 或 } f\left(x_{0}-0\right)=A
$$
- 若对任意给定的 $\varepsilon>0$，总存在 $\delta>0$，当 $x_{0}<x<x_{0}+\delta$ 时，恒有 $|f(x)-A|<\varepsilon$，则称常数 $A$ 为 <span style="color: LightSkyBlue;">~</span> $f(x)$ 当 $x \rightarrow x_{0}^{+}$ 时的右  <span style="color: Gold;">- </span>，记为
$$
\lim _{x \rightarrow x_{0}^{+}} f(x)=A, \text{ 或 } f\left(x_{0}^{+}\right)=A, \text{ 或 } f\left(x_{0}+0\right)=A
$$

定理：$\lim _{x \rightarrow x_{0}} f(x)=A$ 的充分必要条件是 $\lim _{x \rightarrow x_{0}^{-}} f(x)=\lim _{x \rightarrow x_{0}^{+}} f(x)=A$。  
推论：若 $\lim _{x \rightarrow x_{0}^{-}} f(x), \lim _{x \rightarrow x_{0}^{+}} f(x)$ 至少有一个  <span style="color: Gold;">- </span>不存在，或都存在但不相等，则 $\lim _{x \rightarrow x_{0}} f(x)$ 不存在。

【注】需要分左、右  <span style="color: Gold;">- </span>求  <span style="color: Gold;">- </span>的问题常见有以下三种:  
(1) 分段 <span style="color: LightSkyBlue;">~</span>在分界点处的  <span style="color: Gold;">- </span>，而在该分界点两侧 <span style="color: LightSkyBlue;">~</span>表达式不同（这里也包括带有绝对值的 <span style="color: LightSkyBlue;">~</span>，如 $\lim _{x \rightarrow 0} \frac{|x|}{x}$）；  
(2) $\mathrm{e}^{\infty}$ 型  <span style="color: Gold;">- </span>（如 $\lim _{x \rightarrow 0} \mathrm{e}^{\frac{1}{x}}, \lim _{x \rightarrow \infty} \mathrm{e}^{x}, \lim _{x \rightarrow \infty} \mathrm{e}^{-x}$）；  
(3) $\arctan \infty$ 型  <span style="color: Gold;">- </span>（如 $\lim _{x \rightarrow 0} \operatorname{arctan} \frac{1}{x}, \lim _{x \rightarrow \infty} \operatorname{arctan} x$)。

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
