<div style="float: left; width: 64%; padding: 1%;">

## 一、导数的概念及几何意义

<ul>

### 1. 导数的概念

<ul>

设函数 $ y = f(x) $ 在 $ x_0 $ 的某邻域内有定义，如果极限

$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

存在，则称 $ f(x) $ 在点 $ x_0 $ 处可导，并称此极限值为 $ f(x) $ 在点 $ x_0 $ 处的导数，记为 $ f'(x_0) $ 或 $ \left. y' \right|_{x=x_0} $ 或 $ \left. \frac{dy}{dx} \right|_{x=x_0} $。如果上述极限不存在，则称 $ f(x) $ 在点 $ x_0 $ 处不可导。

【注】常用的导数定义的等价形式有：

$$
f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0}, \quad f'(x_0) = \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h}
$$

</ul>

#### 定义（左导数）

<ul>

设函数 $ y = f(x) $ 在点 $ x_0 $ 及其某个左邻域内有定义，若左极限

$$
\lim_{\Delta x \to 0^-} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0^-} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = \lim_{x \to x_0^-} \frac{f(x) - f(x_0)}{x - x_0}
$$

存在，则称该极限值为 $ f(x) $ 在点 $ x_0 $ 处的左导数，记为 $ f'_-(x_0) $。

</ul>

#### 定义（右导数）

<ul>

设函数 $ y = f(x) $ 在点 $ x_0 $ 及其某个右邻域内有定义，若右极限

$$
\lim_{\Delta x \to 0^+} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0^+} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = \lim_{x \to x_0^+} \frac{f(x) - f(x_0)}{x - x_0}
$$

存在，则称该极限值为 $ f(x) $ 在点 $ x_0 $ 处的右导数，记为 $ f'_+(x_0) $。

$$
\begin{aligned}
\text{左导数: } f'_-(x_0) &= \lim_{\Delta x \to 0^+} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = \lim_{h \to 0^-} \frac{f(x_0 + h) - f(x_0)}{h} \\
&= \lim_{x \to x_0^+} \frac{f(x) - f(x_0)}{x - x_0}. \\
\text{右导数: } f'_+(x_0) &= \lim_{\Delta x \to 0^+} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = \lim_{h \to 0^+} \frac{f(x_0 + h) - f(x_0)}{h} \\
&= \lim_{x \to x_0^+} \frac{f(x) - f(x_0)}{x - x_0}.
\end{aligned}
$$

**定理** 函数 $ f(x) $ 在点 $ x_0 $ 处可导的充分必要条件是它在该点处左导数与右导数都存在且相等。

【注】（1）若 $ f(x) $ 在 $ x_0 $ 点的左导数 $ f'_-(x_0) $ 、右导数 $ f'_+(x_0) $ 至少有一个不存在或都存在，但不相等，则 $ f(x) $ 在 $ x_0 $ 处不可导，导数 $ f'(x_0) $ 不存在。

（2）利用此定理可判断分段函数在分段点处的导数。

</ul>

#### 定义（区间上可导及导函数）

<ul>

如果 $ y = f(x) $ 在开区间 $ (a, b) $ 内每一点都可导，则称 $ f(x) $ 在区间 $ (a, b) $ 内可导。此时对于 $ (a, b) $ 内的每一点 $ x $，都对应一个导数值 $ f'(x) $，常称 $ f'(x) $ 为 $ f(x) $ 在 $ (a, b) $ 内的导函数，简称为导数。若 $ f(x) $ 在区间 $ (a, b) $ 内可导，且 $ f'_+(a) $ 和 $ f'_-(b) $ 都存在，则称 $ f(x) $ 在区间 $ [a, b] $ 上可导。

导函数: $ f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} $.

【注】 $ f(x) $ 在 $ x_0 $ 点的导数 $ f'(x_0) $，即为导函数 $ f'(x) $ 在点 $ x_0 $ 处的函数值。即 $ \left. f'(x_0) = f'(x) \right|_{x=x_0} $.

</ul>

</ul>

### 2. 导数的几何意义

<ul>

导数 $ f'(x_0) $ 在几何上表示曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处切线的斜率。

如果函数 $ f(x) $ 在点 $ x_0 $ 处可导，则曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处必有切线，其切线方程为

$$
y - f(x_0) = f'(x_0)(x - x_0)
$$

如果 $ f'(x_0) \neq 0 $，则此曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处的法线方程为

$$
y - f(x_0) = -\frac{1}{f'(x_0)}(x - x_0)
$$

如果 $ f'(x_0) = 0 $，则曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处的切线方程为 $ y = f(x_0) $，即曲线在点 $ (x_0, f(x_0)) $ 处有水平切线。而法线方程为 $ x = x_0 $。

【注】（1）若函数 $ f(x) $ 在 $ x = x_0 $ 处可导，则曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处有切线，反之则不然。例如曲线 $ y = x^{\frac{3}{4}} $ 在点 $ (0, 0) $ 处有切线 $ x = 0 $（$ y $ 轴），但函数 $ f(x) = x^{\frac{3}{4}} $ 在 $ x = 0 $ 处不可导 $ (f'(0) = \infty) $。

（2）若函数 $ f(x) $ 在 $ x_0 $ 处连续，且 $ f'(x_0) = \infty $，则曲线 $ y = f(x) $ 在点 $ (x_0, f(x_0)) $ 处有切线，切线方程为 $ x = x_0 $。

</ul>

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
