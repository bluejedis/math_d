<div style="float: left; width: 64%; padding: 1%;">

### 6. 几个十分有用的定积分公式

<ul>

1. $ \int_0^a \sqrt{a^2 - x^2} \, \mathrm{d} x = \frac{1}{4} \pi a^2, \int_{-a}^a \sqrt{a^2 - x^2} \, \mathrm{d} x = \frac{1}{2} \pi a^2 $（半圆面积）。
2. 设 $ f(x) $ 在 $ [-a, a] (a > 0) $ 上是个连续的偶函数，则

$$
\int_{-a}^a f(x) \, \mathrm{d} x = 2 \int_0^a f(x) \, \mathrm{d} x
$$

3. 设 $ f(x) $ 在 $ [-a, a] (a > 0) $ 上是个连续的奇函数，则 $ \int_{-a}^a f(x) \, \mathrm{d} x = 0 $。
4. 设 $ f(x) $ 在 $ (-\infty, +\infty) $ 内是以 $ T $ 为周期的连续函数，则对于任意的常数 $ a $，恒有

$$
\int_a^{a + T} f(x) \, \mathrm{d} x = \int_0^T f(x) \, \mathrm{d} x . \quad \int_a^{a + nT} f(x) \, \mathrm{d} x = n \int_0^T f(x) \, \mathrm{d} x (n \in \mathbf{N})
$$

5. 华里士公式：

$$
\begin{aligned}
\int_0^{\frac{\pi}{2}} \sin^n x \, \mathrm{d} x & = \int_0^{\frac{\pi}{2}} \cos^n x \, \mathrm{d} x \\
& = \begin{cases} \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{1}{2} \cdot \frac{\pi}{2}, & \text{当 } n \text{ 为正偶数，} \\ \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{2}{3}, & \text{当 } n \text{ 为大于 } 1 \text{ 的正奇数，} \\ \frac{\pi}{2}, & n = 0, \\ 1, & n = 1. \end{cases}
\end{aligned}
$$

6. $ \int_0^\pi x f(\sin x) \, \mathrm{d} x = \frac{\pi}{2} \int_0^\pi f(\sin x) \, \mathrm{d} x $（其中 $ f(x) $ 连续）。

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
