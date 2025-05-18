<div style="float: left; width: 64%; padding: 1%;">

## 二、积分的基本性质

<ul>

**常理（定积分的性质）**：以下除特别声明者外，均设 $ f(x) $ 与 $ g(x) $ 在所讨论的区间上可积，则

1. $ \int_a^b f(x) \, \mathrm{d} x = -\int_b^a f(x) \, \mathrm{d} x $
2. $ \int_a^a f(x) \, \mathrm{d} x = 0 $
3. $ \int_a^b [f(x) \pm g(x)] \, \mathrm{d} x = \int_a^b f(x) \, \mathrm{d} x \pm \int_a^b g(x) \, \mathrm{d} x $
4. $ \int_a^b k f(x) \, \mathrm{d} x = k \int_a^b f(x) \, \mathrm{d} x $，$ k $ 为常数
5. $ \int_a^b f(x) \, \mathrm{d} x = \int_a^c f(x) \, \mathrm{d} x + \int_c^b f(x) \, \mathrm{d} x $
6. 若 $ f(x) \leq g(x), a \leq b $，则 $ \int_a^b f(x) \, \mathrm{d} x \leq \int_a^b g(x) \, \mathrm{d} x $
7. 若 $ f(x) $ 与 $ g(x) $ 在区间 $ [a, b] $ 上连续，$ f(x) \leq g(x) $，且至少存在点 $ x_1, a \leq x_1 \leq b $，使 $ f(x_1) < g(x_1) $，则 $ \int_a^b f(x) \, \mathrm{d} x < \int_a^b g(x) \, \mathrm{d} x $
8. $ \left| \int_a^b f(x) \, \mathrm{d} x \right| \leq \int_a^b |f(x)| \, \mathrm{d} x $（$ a \leq b $）
9. 加强的积分中值定理：设 $ f(x) $ 在 $ [a, b] $ 上连续，则至少存在一点 $ \xi \in (a, b) $ 使

$$
\int_a^b f(x) \, \mathrm{d} x = f(\xi) (b - a)
$$

**注**：性质（6）与（7）称为定积分的不等式性质，常用的是（7）。

**常理（定积分存在定理）**：

1. 设 $ f(x) $ 在 $ [a, b] $ 上连续，则 $ \int_a^b f(x) \, \mathrm{d} x $ 存在。
2. 设 $ f(x) $ 在 $ [a, b] $ 上有界，且只有有限个间断点，则 $ \int_a^b f(x) \, \mathrm{d} x $ 存在。

**注**：还有其他一些条件可保证定积分存在，但这些不在考试大纲之内。

**变续（原函数存在定理）**：设 $ f(x) $ 在 $ [a, b] $ 上连续，则在 $ [a, b] $ 上必存在原函数。

**注**：
1. 如果 $ f(x) $ 在 $ [a, b] $ 上有定义，但不连续，那么 $ f(x) $ 在 $ [a, b] $ 上就不一定保证存在原函数。如：$ f(x) $ 在 $ [a, b] $ 上有第一类间断点，则 $ f(x) $ 在 $ [a, b] $ 上一定没有原函数。
2. 初等函数在其定义区间上连续，因此一定存在此区间上的原函数，但其原函数不一定为初等函数。例如 $ \int \mathrm{e}^{x^2} \, \mathrm{d} x \cdot \int \sin x^2 \, \mathrm{d} x \cdot \int \frac{\sin x}{x} \, \mathrm{d} x \cdot \int \frac{1}{\ln x} \, \mathrm{d} x $ 等存在。但都不能表示成初等函数。
3. 设 $ f(x) $ 不连续，则原函数存在与否与定积分存在与否可以各不相干。

**变义（变上限的定积分）**：设 $ f(x) $ 在 $ [a, b] $ 上可积，对 $ x \in [a, b] $，$ f(x) $ 在 $ [a, x] $ 上可积。于是

$$
\Phi(x) = \int_a^x f(t) \, \mathrm{d} t, x \in [a, b]
$$

定义了一个以 $ x $ 为自变量的函数，称为变上限的定积分。

类似，变下限的定积分 $ \Phi(x) = \int_x^b f(t) \, \mathrm{d} t, x \in [a, b] $。

变上限的定积分和变下限的定积分统称为变限积分。

**变续（变上限函数与变积分的关系）**：设 $ f(x) $ 在 $ [a, b] $ 上连续，则 $ \left( \int_a^x f(t) \, \mathrm{d} t \right)' = f(x), x \in [a, b] $。

由此可知，$ \int_a^x f(t) \, \mathrm{d} t $ 是 $ f(x) $ 的一个原函数，从而 $ \int f(x) \, \mathrm{d} x = \int_a^x f(t) \, \mathrm{d} t + C $。

**注**：如果 $ f(x) $ 在 $ [a, b] $ 上除点 $ x = x_0 \in (a, b) $ 外均连续，而在 $ x = x_0 $ 处 $ f(x) $ 有跳跃间断点：

$$
\lim_{x \to x_0^-} f(x) = f(x_0^-), \lim_{x \to x_0^+} f(x) = f(x_0^+), f(x_0^-) \neq f(x_0^+)
$$

记

$$
F(x) = \int_c^x f(t) \, \mathrm{d} t
$$

不论 $ c $ 是否等于 $ x_0 $，均有结论：

1. $ F(x) $ 在 $ [a, b] $ 上连续；
2. $ F'(x) = f(x) $，当 $ x \in [a, b] $，但 $ x \neq x_0 $；
3. $ F'(x_0^-) = f(x_0^-), F'(x_0^+) = f(x_0^+) $。

**变续（牛顿-莱布尼茨定理）**：设 $ f(x) $ 在 $ [a, b] $ 上连续，$ F(x) $ 是 $ f(x) $ 的一个原函数，则

$$
\int_a^b f(x) \, \mathrm{d} x = \left. F(x) \right|_a^b = F(b) - F(a)
$$

</ul>

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
