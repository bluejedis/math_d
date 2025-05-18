<div style="float: left; width: 64%; padding: 1%;">

## 一、反常积分

<ul>

**变义（无穷区间上的反常积分）**：设 $ f(x) $ 在 $ [a, +\infty) $ 上连续，称

$$
\int_a^{+\infty} f(x) \, \mathrm{d} x = \lim_{b \to +\infty} \int_a^b f(x) \, \mathrm{d} x
$$

为 $ f(x) $ 在 $ [a, +\infty) $ 上的反常积分。若右边极限存在，称此反常积分收敛；若该极限不存在，称此反常积分发散。

类似地可以定义 $ \int_{-\infty}^b f(x) \, \mathrm{d} x = \lim_{a \to -\infty} \int_a^b f(x) \, \mathrm{d} x $ 及 $ \int_{-\infty}^{+\infty} f(x) \, \mathrm{d} x = \int_{-\infty}^c f(x) \, \mathrm{d} x + \int_c^{+\infty} f(x) \, \mathrm{d} x $（其中 $ c \in (-\infty, +\infty) $），在后一式中，只要右边两个反常积分至少有一个不存在，就说反常积分 $ \int_{-\infty}^{+\infty} f(x) \, \mathrm{d} x $ 发散。

**变义（无界函数的反常积分）**：设 $ f(x) $ 在区间 $ [a, b) $ 上连续，且 $ \lim_{x \to b^-} f(x) = \infty $，称

$$
\int_a^b f(x) \, \mathrm{d} x = \lim_{\substack{g \to b^- \\ a \to a}} \int_a^b f(x) \, \mathrm{d} x
$$

为 $ f(x) $ 在区间 $ [a, b) $ 上的反常积分（也称广义积分），若右边极限存在，则称此反常积分收敛；若该极限不存在，称此反常积分发散。使 $ f(x) \to \infty $ 的点 $ b $ 称为 $ f(x) $ 的奇点（也称广义点）。

若点 $ a $ 为 $ f(x) $ 的奇点，类似地可以定义

$$
\int_a^b f(x) \, \mathrm{d} x = \lim_{a \to a^+} \int_a^b f(x) \, \mathrm{d} x
$$

若点 $ a $ 与 $ b $ 都是奇点，则应分成

$$
\int_a^b f(x) \, \mathrm{d} x = \int_a^{x_0} f(x) \, \mathrm{d} x + \int_{x_0}^b f(x) \, \mathrm{d} x, a < x_0 < b
$$

若两个反常积分中至少有一个不存在，就说反常积分 $ \int_a^b f(x) \, \mathrm{d} x $ 不存在（发散）。

若在开区间 $ (a, b) $ 内部点 $ c $ 为奇点，则反常积分定义为

$$
\int_a^b f(x) \, \mathrm{d} x = \int_a^c f(x) \, \mathrm{d} x + \int_c^b f(x) \, \mathrm{d} x
$$

右边两个反常积分中若至少有一个不存在，则称此反常积分发散。

只要一看积分限有 $ \infty $，便知这是无穷区间上的反常积分。所以此类反常积分是容易识别的。无界函数的反常积分就较难识别了。

一般是看被积函数是否有使其分母为零的点。但这句话既不必要，也不充分。例如 $ \int_0^1 \ln x \, \mathrm{d} x $，被积函数没有"分母"，而 $ x = 0 $ 是它的奇点，所以该积分是反常积分。又如

$$
\int_0^1 \frac{1}{x^2} \mathrm{e}^{-\frac{1}{x}} \, \mathrm{d} x
$$

的下限 $ x = 0 $，使分母为 0，但却不是反常积分。这是因为

$$
\lim_{x \to 0^+} \frac{1}{x^2} \mathrm{e}^{-\frac{1}{x}} = \lim_{x \to 0^+} \frac{\frac{1}{x^2}}{\mathrm{e}^{\frac{1}{x}}} = \lim_{x \to 0^+} \frac{-\frac{2}{x^3}}{-\frac{1}{x^2}} \mathrm{e}^{\frac{1}{x}} = \lim_{x \to 0^+} \frac{\frac{2}{x}}{\mathrm{e}^{\frac{1}{x}}} = \lim_{x \to 0^+} \frac{-\frac{2}{x^2}}{-\frac{1}{x^2}} \mathrm{e}^{\frac{1}{x}} = \lim_{x \to 0^+} 2 \mathrm{e}^{-\frac{1}{x}} = 0
$$

所以 $ \int_0^1 \frac{1}{x^2} \mathrm{e}^{-\frac{1}{x}} \, \mathrm{d} x $ 不是反常积分。

话虽如此，但被积函数的分母为零仍是重要的识别标志。不但要看积分的上、下限处，还要看区间内部是否有使 $ f(x) \to \infty $ 的点。

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
