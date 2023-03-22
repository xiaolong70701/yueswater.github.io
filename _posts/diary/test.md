# 大標題

## 副標題

### 次標題

#### 小標題

##### H5 標題

###### H6 標題

- 列點 1
- 列點 2
- 列點 3
- 列點 4

數學模式：
$$
\begin{align}
E\left[e^{tX}\right]&=\frac{\lambda}{2}\int_{\mathbb R}e^{tx}e^{-\lambda|x-\mu|}\,dx
\\\\&=\frac{1}{2}\int_{\mathbb R}\exp\left[t\left(\mu+\frac{y}{\lambda}\right)-|y|\right]\,dy\qquad\qquad,\,\small\text{ substituting }\lambda(x-\mu)=y
\\\\&=\frac{e^{\mu t}}{2}\int_{\mathbb R}e^{ty/\lambda-|y|}\,dy
\\\\&=\frac{e^{\mu t}}{2}\left[\int_{-\infty}^0 e^{y(1+t/\lambda)}\,dy+\int_0^\infty e^{-y(1-t/\lambda)}\,dy\right]
\\\\&=\frac{e^{\mu t}}{2}\left[\underbrace{\int_0^\infty e^{-z(1+t/\lambda)}\,dz}_{\text{ converges for }1+\frac{t}{\lambda}>0}+\underbrace{\int_0^\infty e^{-y(1-t/\lambda)}\,dy}_{\text{ converges for }1-\frac{t}{\lambda}>0}\right]
\\\\&=\frac{e^{\mu t}}{2}\left[\frac{1}{1+\frac{t}{\lambda}}+\frac{1}{1-\frac{t}{\lambda}}\right]\qquad\qquad\qquad,\,|t|<\lambda
\end{align}
$$


