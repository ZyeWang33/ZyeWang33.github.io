$$C_{i}^{(n)}=\frac{(-1)^{n-i}}{i !(n-i) ! n} \int_{0}^{n} \prod_{\substack{j=0 \\ j \neq i}}^{n}(t-j) d t$$考虑
$$
F_i(t)=\frac{(-1)^{n-i}}{i !(n-i) ! n} \prod_{\substack{j=0 \\ j \neq i}}^n(t-j)
$$

显然,对$\forall t \in 0,1,2,\ldots,n$,只有$t = i$时，$F_i(t)\neq 0$
$$
\begin{align}
F_i(i)&=\frac{(-1)^{n-i}}{i !(n-i) ! n} \prod_{\substack{j=0 \\ j \neq i}}^n(i-j) \\
&=\frac{(-1)^{n-i}}{i !(n-i) ! n}i!\prod_{\substack{j=i+1 \\ j \neq i}}^n(i-j)\\

&=\frac{(-1)^{n-i}}{(n-i) ! n}(-1)^{n-i}(n-i)!\\

&=\frac{1}{n}

\end{align}
$$
$\sum\limits_{i=0}^nF_i(t)$是一个$n$ 次多项式,当$t = 0,1,2,3,\ldots,n$共$n+1$个点时，多项式值都是$\frac{1}{n}$
由代数基本定理，这显然是不可能的,所以这个多项式只能恒为常数$\frac{1}{n}$
则
$$
\begin{aligned}

\sum_{i=0}^{n} C_{i}^{(n)} &= \sum_{i=0}^n\int_{0}^nF_i(t)dt\\

&=\int_{0}^n\sum_{i=0}^nF_i(t)dt\\

&=\int_{0}^n\frac{1}{n}dt\\

&=1

\end{aligned}
$$
