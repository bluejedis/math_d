<div style="float: left; width: 64%; padding: 1%;">

## 二、重要几何公式与物理应用

<ul>

### 1. 平面图形面积

<ul>

（1）曲线 $ y = y_2(x) $ 与 $ y = y_1(x) \left( y_2(x) \geq y_1(x) \right) $ 及 $ x = a, x = b $ 围成的平面图形的面积

$$
S = \int_a^b \left( y_2(x) - y_1(x) \right) \, \mathrm{d} x
$$

（2）曲线 $ x = x_2(y) $ 与 $ x = x_1(y) \left( x_2(y) \geq x_1(y) \right) $ 及 $ y = c, y = d $ 围成的平面图形的面积

$$
S = \int_c^d \left( x_2(y) - x_1(y) \right) \, \mathrm{d} y
$$

（3）极坐标曲线 $ r = r(\theta) $ 介于两射线 $ \theta = \alpha $ 与 $ \theta = \beta (0 < \beta - \alpha \leq 2\pi) $ 之间的曲边扇形的面积

$$
S = \frac{1}{2} \int_\alpha^\beta r^2(\theta) \, \mathrm{d} \theta
$$

（4）由参数方程 $ \left\{ \begin{array}{l} x = x(t), \\ y = y(t), \alpha \leq t \leq \beta \end{array} \right. $ 所围成平面图形的面积为

$$
S = \int_\alpha^\beta \left| y(t) x'(t) \right| \, \mathrm{d} t \text{ 或 } S = \int_\alpha^\beta \left| x(t) y'(t) \right| \, \mathrm{d} t
$$

- 数学三只要求会计算平面图形的面积、旋转体的体积和函数的平均值。

</ul>

### 2. 旋转体体积

<ul>

（1）曲线 $ y = y(x) $ 与 $ x = a, x = b, x $ 轴围成的曲边梯形绕 $ x $ 轴旋转一周所成的旋转体体积

$$
V = \pi \int_a^b y^2(x) \, \mathrm{d} x, a < b
$$

绕 $ y $ 轴旋转一周所得旋转体体积为 $ V = 2\pi \int_a^b x y(x) \, \mathrm{d} x, (y(x) \geq 0, b \geq a \geq 0) $。

（2）曲线 $ y = y_2(x), y = y_1(x), x = a, x = b \left( y_2(x) \geq y_1(x) \geq 0 \right) $ 围成的图形绕 $ x $ 轴旋转一周所成的旋转体体积

$$
V = \pi \int_a^b \left[ y_2^2(x) - y_1^2(x) \right] \, \mathrm{d} x, a < b
$$

（3）曲线 $ y = y_2(x), y = y_1(x), x = a, x = b \left( b > a \geq 0, y_2(x) \geq y_1(x) \right) $ 围成的图形绕 $ y $ 轴旋转一周所成的旋转体体积

$$
V = 2\pi \int_a^b x \left( y_2(x) - y_1(x) \right) \, \mathrm{d} x
$$

</ul>

### 3. 函数的平均值

<ul>

设 $ x \in [a, b] $，函数 $ f(x) $ 在 $ [a, b] $ 上的平均值为

$$
\bar{f} = \frac{1}{b - a} \int_a^b f(x) \, \mathrm{d} x
$$

</ul>

### 4. 在区间 $ [a, b] $ 上平行截面面积 $ S(x) $ 为已知的立体体积

<ul>

$$
V = \int_a^b S(x) \, \mathrm{d} x, a < b
$$

</ul>

### 5. 平面曲线的弧长

<ul>

（1）参数方程曲线 $ \left\{ \begin{array}{l} x = x(t), \\ y = y(t), \alpha \leq t \leq \beta \text{ 的弧长（其中 } x'(t) \text{ 与 } y'(t) \text{ 均连续，且不同时为零）} \end{array} \right. $

$$
s = \int_\alpha^\beta \sqrt{x'^2(t) + y'^2(t)} \, \mathrm{d} t
$$

（2）直角坐标 $ y = y(x), a \leq x \leq b $ 的弧长（其中 $ y'(x) $ 连续）

$$
s = \int_a^b \sqrt{1 + y'^2(x)} \, \mathrm{d} x
$$

（3）极坐标曲线 $ r = r(\theta), \alpha \leq \theta \leq \beta $ 的弧长（其中 $ r(\theta), r'(\theta) $ 连续，且不同时为零）

$$
s = \int_\alpha^\beta \sqrt{r^2(\theta) + r'^2(\theta)} \, \mathrm{d} \theta
$$

</ul>

### 6. 旋转曲面面积

<ul>

在区间 $ [a, b] $ 上的曲线 $ y = f(x) $ 的弧段绕 $ x $ 轴旋转一周所成的旋转曲面面积

$$
S = 2\pi \int_a^b |y| \sqrt{1 + f'^2(x)} \, \mathrm{d} x, a < b
$$

**注**：
1. 若该曲线由参数方程 $ x = x(t), y = y(t), \alpha \leq t \leq \beta $ 给出，且 $ x'(t) \neq 0 $。则将式中的 $ y $ 用 $ y(t) $ 代替，$ \sqrt{1 + f'^2(x)} \, \mathrm{d} x $ 用 $ \sqrt{x'^2(t) + y'^2(t)} \, \mathrm{d} t $ 代替，上、下限为 $ t $ 的上、下限：从 $ t = \alpha $ 至 $ t = \beta $ 即可：

$$
S = 2\pi \int_\alpha^\beta |y(t)| \sqrt{x'^2(t) + y'^2(t)} \, \mathrm{d} t
$$

2. 由曲线 $ r = r(\theta) (0 \leq \alpha \leq \theta \leq \beta \leq \pi) $ 绕极轴旋转一周所生成的旋转面的侧面积为

$$
S = 2\pi \int_\alpha^\beta r(\theta) \sqrt{r^2(\theta) + r'^2(\theta)} \sin \theta \, \mathrm{d} \theta
$$

</ul>

### 7. 变力做功

<ul>

</ul>

### 8. 液体静压力

<ul>

</ul>

### 9. 引力

<ul>

</ul>

### 10. 物体的质心（形心）

<ul>

</ul>

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
