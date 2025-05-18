<div style="float: left; width: 64%; padding: 1%;">

## 四、函数的幂级数展开

<ul>

**定义** 设 $f(x)$ 在 $x=x_{0}$ 处任意阶可导，则幂级数

$$
\begin{aligned}
\sum_{n=0}^{\infty} \frac{f^{(n)}\left(x_{0}\right)}{n!}\left(x-x_{0}\right)^{n}= & f\left(x_{0}\right)+f^{\prime}\left(x_{0}\right)\left(x-x_{0}\right)+\frac{f^{\prime \prime}\left(x_{0}\right)}{2!}\left(x-x_{0}\right)^{2}+\cdots \\
& +\frac{f^{(n)}\left(x_{0}\right)}{n!}\left(x-x_{0}\right)^{n}+\cdots
\end{aligned}
$$

称为 $f(x)$ 在 $x=x_{0}$ 处的泰勒级数。  
当 $x_{0}=0$ 时，级数 $\sum_{n=0}^{\infty} \frac{f^{(n)}(0)}{n!} x^{n}=f(0)+f^{\prime}(0) x+\frac{f^{\prime \prime}(0)}{2!} x^{2}+\cdots+\frac{f^{(n)}(0)}{n!} x^{n}+\cdots$ 称为 $f(x)$ 的麦克劳林级数。

**定理**（泰勒级数的收敛）设 $f(x)$ 在 $x=x_{0}$ 处任意阶可导，则泰勒级数

$$
\sum_{n=0}^{\infty} \frac{f^{(n)}\left(x_{0}\right)}{n!}\left(x-x_{0}\right)^{n}
$$

收敛于 $f(x)$ 的充要条件是 $\lim _{n \rightarrow \infty} R_{n}(x)=0$，其中 $R_{n}(x)=\frac{f^{(n+1)}\left[x_{0}+\beta\left(x-x_{0}\right)\right]}{(n+1)!}\left(x-x_{0}\right)^{n+1}$。
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
