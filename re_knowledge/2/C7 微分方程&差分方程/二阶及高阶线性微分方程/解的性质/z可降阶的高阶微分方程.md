<div style="float: left; width: 64%; padding: 1%;">

### 可降阶的高阶微分方程

<ul>

1. **$y^{\prime \prime}=f(x)$ 型可降阶二阶方程**  
   做两次积分就可得到它的通解

   $$
   y=\int\left(\int f(x) \mathrm{d} x\right) \mathrm{d} x+C_{1} x+C_{2}
   $$

2. **$y^{\prime \prime}=f\left(x, y^{\prime}\right)$ 型 \{缺 $y$\} 的可降阶二阶方程**  
   命 $p=y^{\prime}, y^{\prime \prime}=\frac{\mathrm{d} p}{\mathrm{~d} x}$，从而化为

   $$
   \frac{\mathrm{d} p}{\mathrm{~d} x}=f(x, p)
   $$

   如果从它可解得 $p=\varphi\left(x, C_{1}\right)$，则得原方程的通解为 $y=\int \varphi\left(x, C_{1}\right) \mathrm{d} x+C_{2}$。

3. **$y^{\prime \prime}=f\left(y, y^{\prime}\right)$ 型 \{缺 $x$\} 的可降阶二阶方程**  
   命 $p=y^{\prime}, y^{\prime \prime}=\frac{\mathrm{d} p}{\mathrm{~d} x}=\frac{\mathrm{d} p}{\mathrm{~d} y} \cdot \frac{\mathrm{d} y}{\mathrm{~d} x}=p \frac{\mathrm{d} p}{\mathrm{~d} y}$，从而化为

   $$
   p \cdot \frac{\mathrm{d} p}{\mathrm{~d} y}=f(y, p)
   $$

   如果能解出

   $$
   p=\psi\left(y, C_{1}\right)
   $$

   再由 $p=\frac{\mathrm{d} y}{\mathrm{~d} x}$ 代入，解得

   $$
   \int \frac{\mathrm{d} y}{\psi\left(y, C_{1}\right)}=\int \mathrm{d} x+C_{2}=x+C_{2}
   $$

   做出左边积分，便得原微分方程的通解。

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
