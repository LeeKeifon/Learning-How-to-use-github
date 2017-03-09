#公式符号
@(A1 文字)[Markdown使用, 总结]

CSDN-markdown编辑器支持基于MathJax编写LaTeX数学公式。

>- [中文参考网站](http://mlworks.cn/posts/introduction-to-mathjax-and-latex-expression/)
>- [原文参考网址](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

--------
>[数学符号查询](http://detexify.kirelabs.org/classify.html)

-----------

####常用公式练手：
>总的来说有几个规则：
>- `$$`为数学公式书写的**开始**
>- `\`后可以理解为是**函数**
>- `{}`可以理解为是**参数**
>- `_`用于**下标**
>

对比1：
$$\sum_{i=0}^n {i^2} = \frac{(n^2+n)(2n+1)}{6}$$
$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$
$$\sum_{i=0}^{n} {i^2} = \frac{(n^2+n)(2n+1)}{6}$$


$f(x)=3 \times x$
$\frac d{dx}x\dot x =  {\dot x}^2 +  x\ddot x$
$\frac d{dx}x\dot x =  \dot x^2 +  x\ddot x$
$\frac {d}{dx}x\dot x =  {\dot x}^2 +  x\ddot x$


$\Delta$
$\mathbb{A}$
$\{x\}$
$\vert x \vert$
$|x|$
$\Vert x \Vert$

对比2：
$\bar{x}$
$\bar {xyz}$
$\overline {xyz}$

对比3：
$\vec {x}$
$\vec {xyz}$
$\overrightarrow {xyz}$



对比2：
$\left(\frac{\sqrt{x}}{y^3}\right)$
$(\frac{\sqrt{x}}{y^3})$这样就显得太小了

对比3：
$ \frac{x}{y} $
${x \over y}$

~~[2]test~~
$$\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 
1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} 
{1+\frac{e^{-8\pi}} {1+\ldots} } } }$$ 