<div style="float: left; width: 64%; padding: 1%;">

<span style="color: LightSkyBlue;">~</span> : <span style="color: LightSkyBlue;">函数</span>
<span style="color: Gold;">- </span> :  <span style="color: Gold;">极限</span>
<span style="color: SlateBlue;">^</span> : <span style="color: SlateBlue;">连续性</span>
</ul>

# 0  <span style="color: LightSkyBlue;">函数</span>

<ul>

## 一、 <span style="color: LightSkyBlue;">~</span>的概念及常见 <span style="color: LightSkyBlue;">~</span>

<ul>

### 1.  <span style="color: LightSkyBlue;">~</span>概念

<ul> 

设 $x$ 和 $y$ 是两个变量, $D$ 是一个给定的非空数集。如果对于每个 $x \in D$，按照一定的对应法则 $f$ 总有一个确定的数值 $y$ 和它对应，则称 $y$ 是 $x$ 的 <span style="color: LightSkyBlue;">~</span>，记为
$$
y=f(x), x \in D
$$
其中 $x$ 称为自变量, $y$ 称为因变量, $D$ 称为 <span style="color: LightSkyBlue;">~</span>的定义域, 记作 $D_{f}$，即 $D_{f}=D$。 <span style="color: LightSkyBlue;">~</span>值 $f(x)$ 的全体所构成的集合称为 <span style="color: LightSkyBlue;">~</span> $f$ 的值域, 记作 $R_{f}$ 或 $f(D)$，即
$$
R_{f}=f(D)=\{y \mid y=f(x), x \in D\}
$$

【注】  
（1） <span style="color: LightSkyBlue;">~</span>有两个基本要素：定义域、对应法则（或称依赖关系）。当两个 <span style="color: LightSkyBlue;">~</span>的定义域与对应法则完全相同时，它们就是同一 <span style="color: LightSkyBlue;">~</span>。  
（2）要求 <span style="color: LightSkyBlue;">~</span>的定义域，应牢记以下结论：  
分式的分母不为 $0$, $\sqrt[m]{x}(x \geqslant 0)$, $\log _{x} x(x>0)$。  
$\tan x, \sec x\left(x \neq k \pi+\frac{\pi}{2}\right) ; \cot x, \csc x(x \neq k \pi)$。  
$\arcsin x, \arccos x(-1 \leqslant x \leqslant 1)$。

</ul>

### 2. 分段 <span style="color: LightSkyBlue;">~</span>

<ul>

有些 <span style="color: LightSkyBlue;">~</span>，对其定义域内自变量不同的取值，其对应法则不能用一个统一的数学表达式表示，而要用两个或两个以上的数学式子表示，这类 <span style="color: LightSkyBlue;">~</span>称为分段 <span style="color: LightSkyBlue;">~</span>。

【注】 分段 <span style="color: LightSkyBlue;">~</span>虽然用多个解析式表示，但它是一个 <span style="color: LightSkyBlue;">~</span>，而不是多个 <span style="color: LightSkyBlue;">~</span>。

例如：  
（1） <span style="color: LightSkyBlue;">~</span> $f(x)=\left\{\begin{array}{ll}\frac{\sin x}{x}, & x<0, \\ x^{2}+1, & x \geqslant 0\end{array}\right.$ 为分段 <span style="color: LightSkyBlue;">~</span>, 其定义域为 $(-\infty,+\infty)$。  
（2） <span style="color: LightSkyBlue;">~</span> $f(x)=2-\left|1-x^{2}\right|$ 也是分段 <span style="color: LightSkyBlue;">~</span>，可化为
$$
f(x)=2-\left|1-x^{2}\right|=\left\{\begin{array}{lr}
3-x^{2}, & x<-1 \\
1+x^{2}, & -1 \leqslant x \leqslant 1 \\
3-x^{2}, & x>1
\end{array}\right.
$$
（3） <span style="color: LightSkyBlue;">~</span> $f(x)=\max \left\{x, x^{2}\right\}$ 也是分段 <span style="color: LightSkyBlue;">~</span>，可化为
$$
f(x)=\max \left\{x, x^{2}\right\}=\left\{\begin{array}{ll}
x^{2}, & x \leqslant 0 \\
x, & 0<x<1 \\
x^{2}, & x \geqslant 1
\end{array}\right.
$$
（4）符号 <span style="color: LightSkyBlue;">~</span>也是分段 <span style="color: LightSkyBlue;">~</span>
$$
y=\operatorname{sgn} x=\left\{\begin{array}{cl}
-1, & x<0 \\
0, & x=0 \\
1, & x>0
\end{array}\right.
$$
（5）取整 <span style="color: LightSkyBlue;">~</span> $y=[x]$ 也是分段 <span style="color: LightSkyBlue;">~</span>。  
$[x]$ 表示不超过 $x$ 的最大整数。  
【评注】 分段 <span style="color: LightSkyBlue;">~</span>常见于上述五种形式的 <span style="color: LightSkyBlue;">~</span>。

</ul>

### 3. 复合 <span style="color: LightSkyBlue;">~</span>

<ul>

设 <span style="color: LightSkyBlue;">~</span> $y=f(u)$ 的定义域为 $D_{f}$,  <span style="color: LightSkyBlue;">~</span> $u=g(x)$ 的定义域为 $D_{g}$, 值域为 $R_{g}$, 若 $D_{f} \cap R_{g} \neq \varnothing$, 则称 <span style="color: LightSkyBlue;">~</span> $y=f[g(x)]$ 为 <span style="color: LightSkyBlue;">~</span> $y=f(u)$ 与 $u=g(x)$ 的复合 <span style="color: LightSkyBlue;">~</span>。它的定义域为 $\left\{x \mid x \in D_{g}, g(x) \in D_{f}\right\}$。

【注】 不是任何两个 <span style="color: LightSkyBlue;">~</span>都可以复合, 如 $y=f(u)=\ln u, u=g(x)=\sin x-1$，就不能复合, 这是由于 $D_{f}=(0,+\infty), R_{g}=[-2,0], D_{f} \cap R_{g}=\varnothing$。

</ul>

### 4. 反 <span style="color: LightSkyBlue;">~</span>

<ul>

设 <span style="color: LightSkyBlue;">~</span> $y=f(x)$ 的定义域为 $D$, 值域为 $R_{y}$。若对任意 $y \in R_{y}$, 有唯一确定的 $x \in D$, 使得 $y=f(x)$, 则记为 $x=f^{-1}(y)$, 称其为 <span style="color: LightSkyBlue;">~</span> $y=f(x)$ 的反 <span style="color: LightSkyBlue;">~</span>。

【注】  
（1）不是每个 <span style="color: LightSkyBlue;">~</span>都有反 <span style="color: LightSkyBlue;">~</span>。如 $y=x^{3}$ 有反 <span style="color: LightSkyBlue;">~</span>，而 $y=x^{2}$ 没有反 <span style="color: LightSkyBlue;">~</span>。  
（2）单调 <span style="color: LightSkyBlue;">~</span>一定有反 <span style="color: LightSkyBlue;">~</span>，但反之则不然，如 $f(x)=\left\{\begin{array}{cc}x, & 0 \leqslant x<1, \\ 3-x, & 1 \leqslant x \leqslant 2\end{array}\right.$ 有反 <span style="color: LightSkyBlue;">~</span>, 但不单调。  
(3) 通常将 $y=f(x)$ 的反 <span style="color: LightSkyBlue;">~</span> $x=f^{-1}(y)$ 写成 $y=f^{-1}(x)$。在同一直角坐标系中, $y=f(x)$ 和 $x=f^{-1}(y)$ 的图形重合, $y=f(x)$ 和 $y=f^{-1}(x)$ 的图形关于直线 $y=x$ 对称。  
(4) $y=f(x)$ 和 $y=f^{-1}(x)$ 的定义域和值域互换。  
(5) $f^{-1}[f(x)]=x, f\left[f^{-1}(x)\right]=x$。

</ul>

### 5. 初等 <span style="color: LightSkyBlue;">~</span>

<ul>

将幂 <span style="color: LightSkyBlue;">~</span>、指数 <span style="color: LightSkyBlue;">~</span>、对数 <span style="color: LightSkyBlue;">~</span>、三角 <span style="color: LightSkyBlue;">~</span>及反三角 <span style="color: LightSkyBlue;">~</span>统称为基本初等 <span style="color: LightSkyBlue;">~</span>。

#### 幂 <span style="color: LightSkyBlue;">~</span> $y=x^{\mu}(\mu$ 为实数$

(1) 幂 <span style="color: LightSkyBlue;">~</span> $y=x^{\mu}$ 的定义域和值域取决于 $\mu$ 的取值, 当 $x>0$ 时, $y=x^{\mu}$ 都有定义。  
(2) 常见幂 <span style="color: LightSkyBlue;">~</span>: $y=x, y=x^{2}, y=x^{3}, y=\sqrt{x}, y=\sqrt[3]{x}, y=\frac{1}{x}$。

#### 指数 <span style="color: LightSkyBlue;">~</span> $y=a^{x}(a>0, a \neq 1)$

(1) 定义域: $(-\infty,+\infty)$, 值域: $(0,+\infty)$。  
(2) 单调性: 当 $a>1$ 时, $y=a^{x}$ 单调增加; 当 $0<a<1$ 时, $y=a^{x}$ 单调减少。  
(3) 常见指数 <span style="color: LightSkyBlue;">~</span>: $y=\mathrm{e}^{x}$, 单调增加, $\lim _{x \rightarrow-\infty} \mathrm{e}^{x}=0, \lim _{x \rightarrow+\infty} \mathrm{e}^{x}=+\infty$。

#### 对数 <span style="color: LightSkyBlue;">~</span> $y=\log _{a} x(a>0, a \neq 1)$

(1) 定义域: $(0,+\infty)$, 值域: $(-\infty,+\infty)$。  
(2) 单调性: 当 $a>1$ 时, $y=\log _{a} x$ 单调增加; 当 $0<a<1$ 时, $y=\log _{a} x$ 单调减少。  
(3) 常见对数 <span style="color: LightSkyBlue;">~</span>: $y=\ln x$, 单调增加, $\lim _{x \rightarrow 0^{+}} \ln x=-\infty, \lim _{x \rightarrow+\infty} \ln x=+\infty$。

#### 三角 <span style="color: LightSkyBlue;">~</span> $y=\sin x, y=\cos x, y=\tan x, y=\cot x, y=\sec x, y=\csc x$

(1) 正弦 <span style="color: LightSkyBlue;">~</span> $\sin x$ 与余弦 <span style="color: LightSkyBlue;">~</span> $\cos x$  
   - 定义域: $(-\infty,+\infty)$, 值域: $[-1,1]$。  
   - 奇偶性: $\sin x$ 是奇 <span style="color: LightSkyBlue;">~</span>, $\cos x$ 是偶 <span style="color: LightSkyBlue;">~</span>。  
   - 周期性: $\sin x$ 和 $\cos x$ 都以 $2\pi$ 为周期。  
   - 有界性: $|\sin x| \leqslant 1, |\cos x| \leqslant 1$。  
   - 关系式: $\sin^{2} x + \cos^{2} x = 1$。  
(2) 正切 <span style="color: LightSkyBlue;">~</span> $\tan x$ 与余切 <span style="color: LightSkyBlue;">~</span> $\cot x$  
   - 定义域: $\tan x$ 的定义域为 $D=\left\{x \mid x \neq k \pi+\frac{\pi}{2}, k \in \mathbf{Z}\right\}$; $\cot x$ 的定义域为 $D=\left\{x \mid x \neq k \pi, k \in \mathbf{Z}\right\}$。  
   - 奇偶性: $\tan x$ 和 $\cot x$ 都是奇 <span style="color: LightSkyBlue;">~</span>。  
   - 周期性: $\tan x$ 和 $\cot x$ 都以 $\pi$ 为周期。  
   - 关系式: $\tan x=\frac{\sin x}{\cos x}, \cot x=\frac{\cos x}{\sin x}, \cot x=\frac{1}{\tan x}$。  
(3) 正割 <span style="color: LightSkyBlue;">~</span> $\sec x$ 与余割 <span style="color: LightSkyBlue;">~</span> $\csc x$  
   - 定义域: $\sec x$ 的定义域为 $D=\left\{x \mid x \neq k \pi+\frac{\pi}{2}, k \in \mathbf{Z}\right\}$; $\csc x$ 的定义域为 $D=\{x \mid x \neq k \pi, k \in \mathbf{Z}\}$。  
   - 奇偶性: $\sec x$ 是偶 <span style="color: LightSkyBlue;">~</span>， $\csc x$ 是奇 <span style="color: LightSkyBlue;">~</span>。  
   - 周期性: $\sec x$ 和 $\csc x$ 都以 $2\pi$ 为周期。  
   - 关系式: $\sec x=\frac{1}{\cos x}, \csc x=\frac{1}{\sin x}$;  
     $$
     \sec^{2} x=1+\tan^{2} x, \csc^{2} x=1+\cot^{2} x
     $$

#### 反三角 <span style="color: LightSkyBlue;">~</span> $y=\arcsin x, y=\arccos x, y=\arctan x, y=\operatorname{arccot} x$

(1) 反正弦 <span style="color: LightSkyBlue;">~</span> $\arcsin x$ 与反余弦 <span style="color: LightSkyBlue;">~</span> $\arccos x$  
   - 定义域: $[-1,1]$。值域: $\arcsin x$ 的值域为 $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$， $\arccos x$ 的值域为 $[0, \pi]$。  
   - 单调性: $\arcsin x$ 单调增加, $\arccos x$ 单调减少。  
   - 奇偶性: $\arcsin x$ 是奇 <span style="color: LightSkyBlue;">~</span>。  
   - 有界性: $|\arcsin x| \leqslant \frac{\pi}{2}, 0 \leqslant \arccos x \leqslant \pi$。  
   - 关系式: $\arcsin x+\arccos x=\frac{\pi}{2}, x \in[-1,1]$。  
(2) 反正切 <span style="color: LightSkyBlue;">~</span> $\arctan x$ 与反余切 <span style="color: LightSkyBlue;">~</span> $\operatorname{arccot} x$  
   - 定义域: $(-\infty,+\infty)$, 值域: $\arctan x$ 的值域为 $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right), \operatorname{arccot} x$ 的值域为 $(0, \pi)$。  
   - 单调性: $\arctan x$ 单调增加, $\operatorname{arccot} x$ 单调减少。  
   - 奇偶性: $\arctan x$ 是奇 <span style="color: LightSkyBlue;">~</span>。  
   - 有界性: $|\arctan x|<\frac{\pi}{2}, 0<\operatorname{arccot} x<\pi$。  
   - 关系式: $\arctan x+\operatorname{arccot} x=\frac{\pi}{2}$。  

变义由常数和基本初等 <span style="color: LightSkyBlue;">~</span>经过有限次四则运算和有限次的 <span style="color: LightSkyBlue;">~</span>复合所构成并可用一个式子表示的 <span style="color: LightSkyBlue;">~</span>，称为初等 <span style="color: LightSkyBlue;">~</span>。

</ul>

### 6. 隐 <span style="color: LightSkyBlue;">~</span>

<ul>

设有关系式 $F(x, y)=0$，若 $\forall x \in D$，存在唯一确定的 $y$ 满足 $F(x, y)=0$ 与 $x$ 相对应，由此确定的 $y$ 与 $x$ 的 <span style="color: LightSkyBlue;">~</span>关系 $y=y(x)$ 称为由方程 $F(x, y)=0$ 所确定的隐 <span style="color: LightSkyBlue;">~</span>。

</ul>

### 7. 参数方程确定的 <span style="color: LightSkyBlue;">~</span>

<ul>

由 $\left\{\begin{array}{l}x=\varphi(t), \\ y=\psi(t), \alpha \leqslant t \leqslant \beta \end{array}\right.$ 确定的 <span style="color: LightSkyBlue;">~</span> $y=f(x), a \leqslant x \leqslant b$。

</ul>

### 8. 幂指 <span style="color: LightSkyBlue;">~</span>

<ul>

$$
y=u(x)^{\nu(x)}, \text{ 其中 } u(x)>0.
$$

幂指 <span style="color: LightSkyBlue;">~</span>的讨论常利用恒等式
$$
u(x)^{\nu(x)}=\mathrm{e}^{\nu(x) \ln u(x)}.
$$

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
