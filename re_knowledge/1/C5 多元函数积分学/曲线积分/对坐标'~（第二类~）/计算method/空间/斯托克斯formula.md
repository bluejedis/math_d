<div style="float: left; width: 64%; padding: 1%;">

#### (2) 斯托克斯公式
<ul>

设 $L$ 为空间分段光滑的有向闭曲线，$\Sigma$ 是以 $L$ 为边界的分片光滑曲面，$L$ 的方向与 $\Sigma$ 的法方向符合右手法则，函数 $P, Q, R$ 在 $\Sigma$ 上具有一阶连续偏导数，则有

$$
\begin{aligned}
& \oint_{L} P(x, y, z) \mathrm{d} x+Q(x, y, z) \mathrm{d} y+R(x, y, z) \mathrm{d} z \\
& =\iint_{L}\left|\begin{array}{ccc}
\cos \alpha & \cos \beta & \cos \gamma \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
P & Q & R
\end{array}\right| \mathrm{d} S \\
& =\iint_{L}\left(\frac{\partial R}{\partial y}-\frac{\partial Q}{\partial z}\right) \mathrm{d} y \mathrm{~d} z+\left(\frac{\partial P}{\partial z}-\frac{\partial R}{\partial x}\right) \mathrm{d} z \mathrm{~d} x+\left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right) \mathrm{d} x \mathrm{~d} y
\end{aligned}
$$
</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
