<div style="float: left; width: 64%; padding: 1%;">

## 二、🌟向量的运算

<ul>

（以 $\mathbf{R}^{3}$ 为例）记 $a=\left(a_{1}, a_{2}, a_{3}\right), b=\left(b_{1}, b_{2}, b_{3}\right), c=\left(c_{1}, c_{2}, c_{3}\right)$，则

1. **向量的加减运算**：

   $$
   a \pm b=\left(a_{1} \pm b_{1}\right) i+\left(a_{2} \pm b_{2}\right) j+\left(a_{3} \pm b_{3}\right) k
   $$

2. **数乘运算**：

   $$
   \lambda a=\lambda a_{1} i+\lambda a_{2} j+\lambda a_{3} k
   $$

3. **数量积**：

   - 代数表示：

     $$
     a \cdot b=a_{1} b_{1}+a_{2} b_{2}+a_{3} b_{3}
     $$

   - 几何表示：

     $$
     a \cdot b=|a| |b| \cos \theta
     $$

   - 运算规律：
     - 交换律：$a \cdot b=b \cdot a$
     - 分配律：$a \cdot(b+c)=a \cdot b+a \cdot c$

   - 几何应用：
     - 求模：$|a|=\sqrt{a \cdot a}$
     - 求夹角：$\cos \theta=\frac{a \cdot b}{|a||b|}$
     - 判定两向量垂直：$\boldsymbol{a} \perp \boldsymbol{b} \Leftrightarrow \boldsymbol{a} \cdot \boldsymbol{b}=0$

4. 🌟**向量积**：

   - 代数表示：

     $$
     \boldsymbol{a} \times \boldsymbol{b}=\left|\begin{array}{ccc}i & j & k \\ a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3}\end{array}\right|
     $$

   - 运算规律：

     $$
     \boldsymbol{a} \times \boldsymbol{b}=-(b \times \boldsymbol{a})
     $$

     $$
     a \times(b+c)=a \times b+a \times c
     $$

   - 几何应用：
     - 求同时垂直于 $a$ 和 $b$ 的向量：$a \times b$
     - 求以 $a$ 和 $b$ 为邻边的平行四边形面积：$S=|\boldsymbol{a} \times \boldsymbol{b}|$
     - 判定两向量平行：$\boldsymbol{a} // \boldsymbol{b} \Leftrightarrow \boldsymbol{a} \times \boldsymbol{b}=\mathbf{0}$

5. **混合积**：

   $$
   (\boldsymbol{a} \boldsymbol{b} \boldsymbol{c})=(\boldsymbol{a} \times \boldsymbol{b}) \cdot \boldsymbol{c}=\left|\begin{array}{lll}a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3} \\ c_{1} & c_{2} & c_{3}\end{array}\right|
   $$

   - 运算规律：

     $$
     (\boldsymbol{a} \boldsymbol{b} \boldsymbol{c})=(\boldsymbol{b} \boldsymbol{c} \boldsymbol{a})=(\boldsymbol{c} \boldsymbol{a} \boldsymbol{b})
     $$

     $$
     (\boldsymbol{a} \boldsymbol{b} \boldsymbol{c})=-(a c b)
     $$

   - 几何应用：
     - 求以 $\boldsymbol{a}, \boldsymbol{b}, \boldsymbol{c}$ 为棱的平行六面体体积：$V_{\text{平行六面体}}=|(\boldsymbol{a} \boldsymbol{b} \boldsymbol{c})|$
     - 判定三向量共面：$\boldsymbol{a}, \boldsymbol{b}, \boldsymbol{c}$ 共面 $\Leftrightarrow (\boldsymbol{a} \boldsymbol{b} \boldsymbol{c})=0$

</ul>

</ul>
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
