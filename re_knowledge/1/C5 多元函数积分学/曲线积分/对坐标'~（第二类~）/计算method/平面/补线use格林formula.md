<div style="float: left; width: 64%; padding: 1%;">

**补线用格林公式**

利用线积分与路径无关

(1) 线积分与路径无关的判定

常理 设函数 $P(x, y), Q(x, y)$ 在单连通域 $D$ 上有一阶连续偏导数，则以下四条等价：

(1) 线积分 $\int_{L} P \mathrm{~d} x+Q \mathrm{~d} y$ 与路径无关；  
(2) $\oint_{L} P \mathrm{~d} x+Q \mathrm{~d} y=0$，其中 $L$ 为 $D$ 中任一分段光滑闭曲线；  
(3) $\frac{\partial P}{\partial y}=\frac{\partial Q}{\partial x}, \forall(x, y) \in D$；  
(4) $P(x, y) \mathrm{d} x+Q(x, y) \mathrm{d} y=\mathrm{d} F(x, y)$。

(2) 计算

(1) 改换路径计算 一般是沿平行于坐标轴的直线积分。

$$
\begin{aligned}
& \int_{\left(x_{1}, y_{1}\right)}^{\left(x_{2}, y_{2}\right)} P \mathrm{~d} x+Q \mathrm{~d} y=\int_{x_{1}}^{x_{2}} P\left(x, y_{1}\right) \mathrm{d} x+\int_{y_{1}}^{y_{2}} Q\left(x_{2}, y\right) \mathrm{d} y \text { 或 } \\
& \int_{\left(x_{1}, y_{1}\right)}^{\left(x_{2}, y_{2}\right)} P \mathrm{~d} x+Q \mathrm{~d} y=\int_{y_{1}}^{y_{2}} Q\left(x_{1}, y\right) \mathrm{d} y+\int_{x_{1}}^{x_{2}} P\left(x, y_{2}\right) \mathrm{d} x
\end{aligned}
$$

(2) 利用原函数计算

设 $P \mathrm{~d} x+Q \mathrm{~d} y=\mathrm{d} F(x, y)$，即 $F(x, y)$ 为 $P \mathrm{~d} x+Q \mathrm{~d} y$ 的原函数，则

$$
\int_{\left(x_{1}, y_{1}\right)}^{\left(x_{2}, y_{2}\right)} P \mathrm{~d} x+Q \mathrm{~d} y=F\left(x_{2}, y_{2}\right)-F\left(x_{1}, y_{1}\right)
$$

求原函数方法：偏积分；凑微分。

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
