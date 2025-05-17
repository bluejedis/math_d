<div style="float: left; width: 64%; padding: 1%;">

### 欧拉方程

<ul>

方程

$$
x^{2} \frac{\mathrm{d}^{2} y}{\mathrm{~d} x^{2}}+a_{1} x \frac{\mathrm{~d} y}{\mathrm{~d} x}+a_{2} y=f(x)
$$

称为欧拉方程，其中 $a_{1}$ 与 $a_{2}$ 为已知常数，$f(x)$ 为 $x$ 的已知函数。它的解法是：  
若 $x>0$，命 $x=\mathrm{e}^{t}$ 作变量代换，有 $t=\ln x$，从而 $\frac{\mathrm{d} t}{\mathrm{~d} x}=\frac{1}{x}$，

$$
\begin{gathered}
\frac{\mathrm{d} y}{\mathrm{~d} x}=\frac{\mathrm{d} y}{\mathrm{~d} t} \cdot \frac{\mathrm{d} t}{\mathrm{~d} x}=\frac{1}{x} \frac{\mathrm{d} y}{\mathrm{~d} t} \\
\frac{\mathrm{~d}^{2} y}{\mathrm{~d} x^{2}}=\frac{\mathrm{d}}{\mathrm{~d} x}\left(\frac{1}{x} \frac{\mathrm{d} y}{\mathrm{~d} t}\right)=-\frac{1}{x^{2}} \frac{\mathrm{d} y}{\mathrm{~d} t}+\frac{1}{x} \frac{\mathrm{d}}{\mathrm{~d} x}\left(\frac{\mathrm{d} y}{\mathrm{~d} t}\right)=-\frac{1}{x^{2}} \frac{\mathrm{d} y}{\mathrm{~d} t}+\frac{1}{x^{2}} \frac{\mathrm{d}^{2} y}{\mathrm{~d} t^{2}}
\end{gathered}
$$

方程（8）化为 $\frac{\mathrm{d}^{2} y}{\mathrm{~d} t^{2}}+\left(a_{1}-1\right) \frac{\mathrm{d} y}{\mathrm{~d} t}+a_{2} y=f\left(\mathrm{e}^{t}\right)$，它是常系数线性微分方程，解之再还原为 $x$ 便可。  
若 $x<0$，命 $x=-\mathrm{e}^{t}$，可依类似处理。

</ul>

</ul>

</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
