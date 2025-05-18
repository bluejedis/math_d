<div style="float: left; width: 64%; padding: 1%;">

## 三、  <span style="color: Gold;">- </span>的计算

<ul>

### 1. 四则运算法则

<ul>

若 $\lim f(x)=a, \lim g(x)=b$, 则  
(1) $\lim [f(x) \pm g(x)]=\lim f(x) \pm \lim g(x)=a \pm b$.  
(2) $\lim [f(x) g(x)]=\lim f(x) \cdot \lim g(x)=a b$.  
(3) $\lim \frac{f(x)}{g(x)}=\frac{\lim f(x)}{\lim g(x)}=\frac{a}{b}(b \neq 0)$.

【注】  
（1）定理的条件不能忽略。  
（2）加、减、乘法则可推广至有限多个 <span style="color: LightSkyBlue;">~</span>的情形。  
结论:  
(1) $\lim c f(x)=c \lim f(x)=c a \quad(c$ 为常数$)$.  
(2) $\lim [f(x)]^{n}=[\lim f(x)]^{n}=a^{n}$  
(3) $\lim [f(x)]^{\frac{1}{n}}=[\lim f(x)]^{\frac{1}{n}}=a^{\frac{1}{n}} \quad n$ 是正整数.

【注】  
（1）存在 $\pm$ 不存在 $=$ 不存在；  
（2）不存在 $\pm$ 不存在 $=$ 不一定；  
（3）存在 $\times(\div)$ 不存在 $=$ 不一定；  
（4）不存在 $\times(\div)$ 不存在 $=$ 不一定。  

常用的结论:  
(1) $\lim f(x)=A \neq 0 \Rightarrow \lim f(x) g(x)=A \lim g(x)$.  
即：  <span style="color: Gold;">- </span>非零的因子的  <span style="color: Gold;">- </span>可先求出来。  
(2) $\lim \frac{f(x)}{g(x)}$ 存在, $\lim g(x)=0 \Rightarrow \lim f(x)=0$.  
(3) $\lim \frac{f(x)}{g(x)}=A \neq 0, \lim f(x)=0 \Rightarrow \lim g(x)=0$.  
(4) 若 $f(x)=a_{0} x^{n}+a_{1} x^{n-1}+\cdots+a_{n}(n \geqslant 1)$, 则 $\lim _{x \rightarrow x_{0}} f(x)=f\left(x_{0}\right) ; \lim _{x \rightarrow \infty} f(x)=\infty$.  
(5) 设有理分式 <span style="color: LightSkyBlue;">~</span> $F(x)=\frac{P(x)}{Q(x)}, P(x), Q(x)$ 是多项式,  
若 $Q\left(x_{0}\right) \neq 0$, 则 $\lim _{x \rightarrow x_{0}} F(x)=\frac{P\left(x_{0}\right)}{Q\left(x_{0}\right)}$.  
(6) $\lim _{x \rightarrow \infty} \frac{a_{0} x^{m}+a_{1} x^{m-1}+\cdots+a_{m}}{b_{0} x^{n}+b_{1} x^{n-1}+\cdots+b_{n}}=\left\{\begin{array}{ll}0, & m<n, \\ \infty, & m>n, \\ \frac{a_{0}}{b_{0}}, & m=n .\end{array}\right.$  
(7) $\lim _{x \rightarrow 0} \frac{a^{x}-1}{x}=\ln a$.  
(8) $\lim _{x \rightarrow \infty} \sqrt[n]{n}=1, \lim _{x \rightarrow \infty} \sqrt[n]{a}=1(a>0)$.  
(9) $\lim _{x \rightarrow \infty} \mathrm{e}^{a x}= \begin{cases}0, & a<0, \\ +\infty, & a>0, \\ 1, & a=0 .\end{cases}$

</ul>

### 2. 两个重要  <span style="color: Gold;">- </span>

<ul>

(1) 第一重要  <span style="color: Gold;">- </span>: $\lim _{x \rightarrow 0} \frac{\sin x}{x}=1$.  
推广: $\lim \frac{\sin \alpha}{\alpha}=1$ ($\alpha$ 为无穷小量).  
由第一重要  <span style="color: Gold;">- </span>可得以下  <span style="color: Gold;">- </span>结果:  
$\lim _{x \rightarrow 0} \frac{\tan x}{x}=1, \lim _{x \rightarrow 0} \frac{\arcsin x}{x}=1, \lim _{x \rightarrow 0} \frac{\arctan x}{x}=1, \lim _{x \rightarrow 0} \frac{1-\cos x}{x^{2}}=\frac{1}{2}, \lim _{x \rightarrow 0} \frac{\sin \alpha x}{x}=\alpha, \lim _{x \rightarrow 0} \frac{\sin \alpha x}{\sin \beta x}=\frac{\alpha}{\beta}(\beta \neq 0, \alpha, \beta$ 为常数$)$.  

(2) 第二重要  <span style="color: Gold;">- </span>: $\lim _{n \rightarrow \infty}\left(1+\frac{1}{n}\right)^{n}=\mathrm{e}, \lim _{x \rightarrow \infty}\left(1+\frac{1}{x}\right)^{x}=\mathrm{e}, \lim _{x \rightarrow 0}(1+x)^{\frac{1}{x}}=\mathrm{e}$.  
推广: $\lim (1+\alpha)^{\frac{1}{\alpha}}=\mathrm{e} \quad (\alpha$ 为无穷小量$)$  
由第二重要  <span style="color: Gold;">- </span>可得以下  <span style="color: Gold;">- </span>结果:  
$$
\lim _{x \rightarrow \infty}\left(1-\frac{1}{x}\right)^{x}=\frac{1}{\mathrm{e}}, \lim _{x \rightarrow \infty}\left(1+\frac{a}{x}\right)^{b x}=\mathrm{e}^{a b}, \lim _{x \rightarrow \infty}\left(1+\frac{a}{x}\right)^{b x+c}=\mathrm{e}^{a b}
$$

“1$^{\infty}$”型  <span style="color: Gold;">- </span>常用结论:  
若 $\lim \alpha(x)=0, \lim \beta(x)=\infty$, 且 $\lim \alpha(x) \beta(x)=A$, 则  
$$
\lim [1+\alpha(x)]^{\beta(x)}=\mathrm{e}^{A}
$$

可以归纳为以下三步：  
（1）写标准形式：原式 $=\lim [1+\alpha(x)]^{\beta(x)}$.  
(2) 求  <span style="color: Gold;">- </span>: $\lim \alpha(x) \beta(x)=A$.  
(3) 写结果: 原式 $=\mathrm{e}^{A}$.  

【注】  
（1）第一重要  <span style="color: Gold;">- </span>是 $\frac{0}{0}$ 型，第二重要  <span style="color: Gold;">- </span>是 $1^{\infty}$ 型。  
（2）利用第一重要  <span style="color: Gold;">- </span>求  <span style="color: Gold;">- </span>的题目，有时也可用洛必达法则。  
（3）幂指 <span style="color: LightSkyBlue;">~</span> $1^{\infty}$ 型求  <span style="color: Gold;">- </span>，可利用第二重要  <span style="color: Gold;">- </span>来求。

</ul>

### 3. 等价无穷小替换

<ul>

**定理**：在某一变化过程下, 设 $f_{1}(x) \sim f_{2}(x), g_{1}(x) \sim g_{2}(x)$, 且 $\lim \frac{f_{2}(x)}{g_{2}(x)}$ 存在, 则  
$$
\lim \frac{f_{1}(x)}{g_{1}(x)}=\lim \frac{f_{2}(x)}{g_{2}(x)}
$$

【注】  
（1）对分子或分母中的一个或几个无穷小因子作等价替换。  
(2) 可推广:  
$$
\begin{aligned}
& \lim \frac{f_{1}(x)}{g_{1}(x)}=\lim \frac{f_{2}(x)}{g_{2}(x)}=\lim \frac{f_{1}(x)}{g_{2}(x)}=\lim \frac{f_{2}(x)}{g_{1}(x)} \\
& \lim \frac{f_{1}(x) h(x)}{g_{1}(x)}=\lim \frac{f_{2}(x) h(x)}{g_{2}(x)}=\lim \frac{f_{1}(x) h(x)}{g_{2}(x)}=\lim \frac{f_{2}(x) h(x)}{g_{1}(x)} \\
& \lim \frac{f_{1}(x)}{g_{1}(x) h(x)}=\lim \frac{f_{2}(x)}{g_{2}(x) h(x)}=\lim \frac{f_{1}(x)}{g_{2}(x) h(x)}=\lim \frac{f_{2}(x)}{g_{1}(x) h(x)} \\
& \lim f_{1}(x) h(x)=\lim f_{2}(x) h(x)
\end{aligned}
$$
（3）和差关系在满足一定条件下可以作等价替换。  
若 $\lim \frac{f_{1}(x)}{g_{1}(x)}=A \neq 1$, 则 $\lim \left[f_{1}(x)-g_{1}(x)\right]=\lim \left[f_{2}(x)-g_{2}(x)\right]$,  
若 $\lim \frac{f_{1}(x)}{g_{1}(x)}=A \neq-1$, 则 $\lim \left[f_{1}(x)+g_{1}(x)\right]=\lim \left[f_{2}(x)+g_{2}(x)\right]$.  

常用的等价无穷小：  
当 $x \rightarrow 0$ 时,  
$$
\begin{aligned}
& \sin x \sim x, \quad \tan x \sim x, \quad \arcsin x \sim x, \quad \arctan x \sim x, \\
& 1-\cos x \sim \frac{1}{2} x^{2}, \quad \ln (1+x) \sim x, \quad \mathrm{e}^{x}-1 \sim x, \quad a^{x}-1 \sim x \ln a, \\
& (1+x)^{a}-1 \sim a x(a \neq 0), \quad \sqrt[n]{1+x}-1 \sim \frac{1}{n} x, \quad \sqrt{1+x}-\sqrt{1-x} \sim x, \\
& x-\sin x \sim \frac{1}{6} x^{3}, \quad \tan x-x \sim \frac{1}{3} x^{3}, \quad x-\ln (1+x) \sim \frac{1}{2} x^{2}, \\
& \arcsin x-x \sim \frac{1}{6} x^{3}, \quad x-\arctan x \sim \frac{1}{3} x^{3}.
\end{aligned}
$$

【注】上述等价无穷小中的 $x$ 换为无穷小量 $\alpha(x)$, 等价关系照样成立。  

推广：当 $\alpha(x)$ 是无穷小时，  
$$
\begin{aligned}
& \sin \alpha(x) \sim \alpha(x), \quad \tan \alpha(x) \sim \alpha(x), \quad \arcsin \alpha(x) \sim \alpha(x), \\
& \arctan \alpha(x) \sim \alpha(x), \quad 1-\cos \alpha(x) \sim \frac{1}{2}[\alpha(x)]^{2}, \\
& \ln [1+\alpha(x)] \sim \alpha(x), \quad \mathrm{e}^{\alpha(x)}-1 \sim \alpha(x), \\
& [1+\alpha(x)]^{k}-1 \sim k \alpha(x)(k \neq 0), \quad \sqrt[n]{1+\alpha(x)}-1 \sim \frac{1}{n} \alpha(x).
\end{aligned}
$$

</ul>

### 4. 洛必达法则

<ul>

**洛必达法则**：  
若  
（1）$\lim _{x \rightarrow x_{0}} f(x)=\lim _{x \rightarrow x_{0}} g(x)=0$（或 $\infty$）；  
（2）$f(x)$ 和 $g(x)$ 在 $x_{0}$ 的某去心邻域内可导，且 $g^{\prime}(x) \neq 0$；  
（3）$\lim _{x \rightarrow x_{0}} \frac{f^{\prime}(x)}{g^{\prime}(x)}$ 存在（或为 $\infty$），  
则 $\lim _{x \rightarrow x_{0}} \frac{f(x)}{g(x)}=\lim _{x \rightarrow x_{0}} \frac{f^{\prime}(x)}{g^{\prime}(x)}$。  

【注】  
（1）洛必达法则适用类型：  
洛必达法则可用来求七种类型未定式的  <span style="color: Gold;">- </span>，即 $\frac{0}{0}, \frac{\infty}{\infty}, \infty \pm \infty, 0 \cdot \infty, 1^{\infty}, \infty^{0}, 0^{0}$，其中前两种 $\frac{0}{0}, \frac{\infty}{\infty}$ 可以直接用洛必达法则，后五种均可化为前两种。  
- $0 \cdot \infty \xlongequal{\text{化为商的形式}} \frac{0}{\infty} \text{ 或 } \frac{\infty}{\infty}$  
- $\infty \pm \infty \xlongequal{\text{通分或有理化}} \frac{0}{0} \text{ 或 } \frac{\infty}{\infty}$  
- $1^{\infty}, \infty^{0}, 0^{0} \xlongequal{\text{取指数 } \mathrm{e}^{\ln}} 0 \cdot \infty \xlongequal{\text{化商}} \frac{0}{\infty} \text{ 或 } \frac{\infty}{\infty}$  
（2）使用洛必达法则应该注意的几个问题：  
（1）使用洛必达法则之前，应该先检验其条件是否满足；  
（2）使用洛必达法则之后，如果问题仍然是未定型  <span style="color: Gold;">- </span>，且仍符合洛必达法则条件，可以再次使用洛必达法则；  
（3）如果“$\frac{0}{0}$”型或“$\frac{\infty}{\infty}$”型  <span style="color: Gold;">- </span>中的 <span style="color: LightSkyBlue;">~</span>含有  <span style="color: Gold;">- </span>非零的因子，可以单独求  <span style="color: Gold;">- </span>，不必参与洛必达法则运算，以简化运算；  
（4）如果能进行等价无穷小量替换或恒等变形配合洛必达法则使用，也可以简化运算；  
（5）当 $x \rightarrow x_{0}^{+}, x_{0}^{-}, +\infty, -\infty$ 时，有类似洛必达法则的形式。

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
