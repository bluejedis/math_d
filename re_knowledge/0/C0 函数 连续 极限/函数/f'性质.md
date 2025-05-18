<div style="float: left; width: 64%; padding: 1%;">

## 二、 <span style="color: LightSkyBlue;">~</span>的性质

<ul>

### 1. 单调性

<ul>

设 <span style="color: LightSkyBlue;">~</span> $y = f(x)$ 在某区间 $I$ 上有定义，如果对于区间 $I$ 上任意两点 $x_1 < x_2$ 恒有 $f(x_1) < f(x_2)$ (或 $f(x_1) > f(x_2)$)，则称 $y = f(x)$ 在该区间内单调增加 (或单调减少)。

**[注]**  <span style="color: LightSkyBlue;">~</span>的单调性主要是利用单调性的定义和二阶导数的正负进行判别。

</ul>

### 2. 奇偶性

<ul>

设 <span style="color: LightSkyBlue;">~</span> $y = f(x)$ 的定义域 $D$ 关于原点对称 (即若 $x \in D$，则有 $-x \in D$)，如果对于任一 $x \in D$，恒有

$$ f(-x) = f(x) $$

则称 $f(x)$ 为 $D$ 上的偶 <span style="color: LightSkyBlue;">~</span>；如果对于任一 $x \in D$，恒有

$$ f(-x) = -f(x) $$

则称 $f(x)$ 为 $D$ 上的奇 <span style="color: LightSkyBlue;">~</span>。

**[注]**  
(1) 奇 <span style="color: LightSkyBlue;">~</span>的图形关于坐标原点对称；偶 <span style="color: LightSkyBlue;">~</span>的图形关于 $y$ 轴对称。  
(2) 奇 <span style="color: LightSkyBlue;">~</span>的代数和仍为奇 <span style="color: LightSkyBlue;">~</span>，偶 <span style="color: LightSkyBlue;">~</span>的代数和仍为偶 <span style="color: LightSkyBlue;">~</span>。  
(3) 偶 <span style="color: LightSkyBlue;">~</span>奇 <span style="color: LightSkyBlue;">~</span>之积为偶 <span style="color: LightSkyBlue;">~</span>，奇 <span style="color: LightSkyBlue;">~</span>偶 <span style="color: LightSkyBlue;">~</span>之积为奇 <span style="color: LightSkyBlue;">~</span>。  
(4) 两个偶 <span style="color: LightSkyBlue;">~</span>的积，商仍为偶 <span style="color: LightSkyBlue;">~</span>，两个奇 <span style="color: LightSkyBlue;">~</span>的积，商为偶 <span style="color: LightSkyBlue;">~</span>。  
(5) 一个奇 <span style="color: LightSkyBlue;">~</span>与一个偶 <span style="color: LightSkyBlue;">~</span>的积、商为奇 <span style="color: LightSkyBlue;">~</span>。  
(6) 奇偶性的判断：定义法、运算性质。  
(7) 奇 <span style="color: LightSkyBlue;">~</span> $f(x)$ 若在 $x = 0$ 处有定义，则 $f(0) = 0$。  
(8) $\sin x, \tan x, \arcsin x, \arctan x, \ln \frac{1-x}{1+x}, \ln(x+\sqrt{1+x^2}), e^{\frac{1}{x}-1}, f(x) - f(-x)$ 都是奇 <span style="color: LightSkyBlue;">~</span>；$x^2, |x|, \cos x, f(x) + f(-x)$ 都是偶 <span style="color: LightSkyBlue;">~</span>。

</ul>

### 3. 周期性

<ul>

若存在实数 $T > 0$，对于任意 $x$，恒有 $f(x+T) = f(x)$，则称 $y = f(x)$ 为以 $T$ 为周期的周期 <span style="color: LightSkyBlue;">~</span>。使得上述关系式成立的最小正数 $T$ 称为 $f(x)$ 的最小正周期，简称为 <span style="color: LightSkyBlue;">~</span> $f(x)$ 的周期。

**[注]**  
(1) $\sin x$ 和 $\cos x$ 以 $2\pi$ 为周期，$\sin 2x$ 以 $\pi$ 为周期，$\tan x$，$\cot x$ 以 $\pi$ 为周期。  
(2) 若 $f(x)$ 以 $T$ 为周期，则 $f(ax+b)$ 以 $\frac{T}{|a|}$ 为周期。  
(3) $f(x), g(x)$ 均以 $T$ 为周期，则 $f(x) \pm g(x)$ 也以 $T$ 为周期。  
(4) $f(x), g(x)$ 分别以 $T_1, T_2$ 为周期，则 $f(x) \pm g(x)$ 的周期为 $T_1, T_2$ 的最小公倍数。  
(5) 周期性的判定：定义法、周期 <span style="color: LightSkyBlue;">~</span>的运算性质。

</ul>

### 4. 有界性

<ul>

设 $y = f(x)$ 在集合 $X$ 上有定义。若存在 $M > 0$，使得对任意的 $x \in X$，恒有 $|f(x)| \leq M$，则称 $f(x)$ 在 $X$ 上为有界 <span style="color: LightSkyBlue;">~</span>。否则称 $f(x)$ 在 $X$ 上为无界 <span style="color: LightSkyBlue;">~</span>。即：如果对任意的 $M > 0$，至少存在一个 $x_0 \in X$，使得 $|f(x_0)| > M$，则 $f(x)$ 为 $X$ 上的无界 <span style="color: LightSkyBlue;">~</span>。

**[注]**  
(1) 如果 <span style="color: LightSkyBlue;">~</span>恒项 $x$ 的范围，而说“$f(x)$ 为有界 <span style="color: LightSkyBlue;">~</span>”，是指 $f(x)$ 在其定义域上为有界 <span style="color: LightSkyBlue;">~</span>。  
(2)  <span style="color: LightSkyBlue;">~</span>有界的定义也可表述为：如果存在常数 $M_1$ 和 $M_2$，使得对任意 $x \in X$，恒有 $M_1 \leq f(x) \leq M_2$，则称 $f(x)$ 在 $X$ 上有界，若别称 $M_1$ 和 $M_2$ 为 $f(x)$ 在 $X$ 上的一个下界和上界。  
(3) 常见的有界 <span style="color: LightSkyBlue;">~</span>：  
$$ |\sin x| \leq 1, |\cos x| \leq 1, |\arcsin x| \leq \frac{\pi}{2}, 0 \leq \arccos x \leq \pi, |\arctan x| \leq \frac{\pi}{2} $$

</ul>

</ul>

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
