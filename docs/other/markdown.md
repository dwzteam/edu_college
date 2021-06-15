## Markdown 数学公式

我们在用 markdown 写文档时有时候少不了需要插入一些公式，然而 markdown 公式输入远没有 word 这么直观，有很多复杂的格式和符号的英语缩写需要记忆，经常是刚用完，过几天不用又都忘记了，因此在这里将数学公式的 Latex 编辑方式做一个整理，以方便自己和读者今后使用。

-   [markdown 支持数学公式插件 docsify-katex](https://upupming.site/docsify-katex/docs/#/supported)
-   [markdown 数学公式语法](https://www.jianshu.com/p/26774d03ba1f)
-   [markdown 数学公式速查 1](https://blog.csdn.net/jyfu2_12/article/details/79207643)
-   [markdown 数学公式速查 2](https://zhenglei.blog.csdn.net/article/details/111057967)
-   [maths-symbols.pdf](https://mirrors.tuna.tsinghua.edu.cn/CTAN/info/symbols/math/maths-symbols.pdf)

> ### 数学公式示例

$\frac{d}{dx}e^{ax}=ae^{ax}\quad \sum_{i=1}^{n}{(X_i - \overline{X})^2}$

$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$

$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$

$\left(\LARGE{AB}\right)$

> ### 行间公式
>
> 使用两个`$`包含公式可以独立一行

$$\frac{d}{dx}e^{ax}=ae^{ax}\quad \sum_{i=1}^{n}{(X_i - \overline{X})^2}$$

> ### 分数，平方

| 算式                 | markdownm            |
| -------------------- | -------------------- |
| $\frac{7x+5}{1+y^2}$ | `\frac{7x+5}{1+y^2}` |
| $\frac{a}{b}$        | `\frac{a}{b}`        |

> ### 下标

| 算式    | markdownm |
| ------- | --------- |
| $z=z_l$ | `z=z_l`   |

> ### 省略号

| 算式     | markdownm |
| -------- | --------- |
| $\cdots$ | `\cdots`  |

> ### 开根号

| 算式                   | markdownm              |
| ---------------------- | ---------------------- |
| $\sqrt{2}+\sqrt[n]{3}$ | `\sqrt{2}+\sqrt[n]{3}` |
| $\sqrt{4}$             | `\sqrt{4}`             |

> ### 矢量

| 算式                      | markdownm                 |
| ------------------------- | ------------------------- |
| $\vec{a} \cdot \vec{b}=0$ | `\vec{a} \cdot \vec{b}=0` |

> ### 微积分

| 算式                 | markdownm            |
| -------------------- | -------------------- |
| $\int ^2_3 x^2 {d}x$ | `\int ^2_3 x^2 {d}x` |
| $\iint$              | `\iint`              |
| $\iiint$             | `\iiint`             |
| $\oint$              | `\oint`              |
| $\mathrm{d}$         | `\mathrm{d}`         |
| $\prime$             | `\prime`             |
| $\lim$               | `\lim`               |
| $\infty$             | `\infty`             |
| $\partial$           | `\partial`           |
| $\sum$               | `\sum`               |

> ### 极限

| 算式                           | markdownm                      |
| ------------------------------ | ------------------------------ |
| $\lim_{n\rightarrow+\infty} n$ | `\lim_{n\rightarrow+\infty} n` |

> ### 累加

| 算式                 | markdownm            |
| -------------------- | -------------------- |
| $\sum \frac{1}{i^2}$ | `\sum \frac{1}{i^2}` |

> ### 累乘

| 算式                  | markdownm             |
| --------------------- | --------------------- |
| $\prod \frac{1}{i^2}$ | `\prod \frac{1}{i^2}` |

> ### 给公式编号，如: (1)
>
> `$$e^{i\theta}=cos\theta+\sin\theta i\tag{1}$$` > $$e^{i\theta}=cos\theta+\sin\theta i\tag{1}$$

> ### 矩阵

```
$$
\begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix} \tag{1}
$$
```

$$
\begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix} \tag{1}
$$

> ### 带括号的矩阵

```
$$
\left[
\begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix} \right]\tag{2}
$$
```

$$
\left[
\begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix} \right]\tag{2}
$$

> ### 三角函数
>
> | 算式   | markdownm |
> | ------ | --------- |
> | $\sin$ | `\sin`    |

> ### 对数函数
>
> | 算式          | markdownm     |
> | ------------- | ------------- |
> | $\ln15$       | `\ln15`       |
> | $\log_2^{10}$ | `\log_2^{10}` |
> | $\lg7$        | `\lg7`        |

> ### 关系运算符
>
> | 算式     | markdownm |
> | -------- | --------- |
> | $\pm$    | `\pm`     |
> | $\times$ | `\times`  |
> | $\div$   | `\div`    |
> | $\sum$   | `\sum`    |
> | $\prod$  | `\prod`   |
> | $\neq$   | `\neq`    |
> | $\leq$   | `\leq`    |
> | $\geq$   | `\geq`    |

> ### 括号
>
> | 算式                                                                        | markdownm                                                         |
> | --------------------------------------------------------------------------- | ----------------------------------------------------------------- |
> | 大括号: $\lbrace a+x \rbrace$                                               | `\lbrace a+x \rbrace`                                             |
> | 尖括号: $\langle x \rangle$                                                 | `\langle x \rangle`                                               |
> | 上取整: $\lceil \frac{x}{2} \rceil$                                         | `\lceil \frac{x}{2} \rceil`                                       |
> | 下取整: $\lfloor x \rfloor$                                                 | `\lfloor x \rfloor`                                               |
> | 原始括号: $\lbrace \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1} \rbrace$            | `\lbrace \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1} \rbrace`            |
> | 全包括号: $\left\lbrace \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1} \right\rbrace$ | `\left\lbrace \sum_{i=0}^{n}i^{2}=\frac{2a}{x^2+1} \right\rbrace` |

## [各种表达式](https://blog.csdn.net/qq_18150255/article/details/88040858)

### text 文字表达

$$
z = \overbrace{
   \underbrace{x}_\text{real} + i
   \underbrace{y}_\text{imaginary}
  }^\text{complex number}
$$

### 分段函数

$$
f(x) = \left\{
  \begin{array}{lr}
    x^2 & : x < 0 \\
    x^3 & : x \ge 0
  \end{array}
\right.
$$

$$
u(x) =
  \begin{cases}
   \exp{x} & \text{if } x \geq 0 \\
   1       & \text{if } x < 0
  \end{cases}
$$

### 方程组

$$
\left\{
\begin{aligned}
    a_1x+b_1y+c_1z=d_1 \\
    a_2x+b_2y+c_2z=d_2 \\
    a_3x+c_3z=d_3
\end{aligned}
\right.
$$

$$
\left\{
\begin{array}{lr}
    a_1x+b_1y+c_1z=d_1 　& ①\\
    a_2x+b_2y+c_2z=d_2 　& ②\\
    a_3x+c_3z=d_3　& ③
\end{array}
\right.
$$

### 线性模型

$$
h(\theta) = \sum_{j = 0} ^n \theta_j x_j
$$

### 均方误差

$$
J(\theta) = \frac{1}{2m}\sum_{i = 0} ^m(y^i - h_\theta (x^i))^2
$$

### 批量梯度下降

$$
\frac{\partial J(\theta)}{\partial\theta_j}=-\frac1m\sum_{i=0}^m(y^i-h_\theta(x^i))x^i_j
$$

### 推导过程

$$
\begin{aligned}
\frac{\partial J(\theta)}{\partial\theta_j}
& = -\frac1m\sum_{i=0}^m(y^i-h_\theta(x^i)) \frac{\partial}{\partial\theta_j}(y^i-h_\theta(x^i)) \\
& = -\frac1m\sum_{i=0}^m(y^i-h_\theta(x^i)) \frac{\partial}{\partial\theta_j}(\sum_{j=0}^n\theta_jx_j^i-y^i) \\
& = -\frac1m\sum_{i=0}^m(y^i-h_\theta(x^i))x^i_j
\end{aligned}
$$

### case 环境的使用

$$
a =
   \begin{cases}
     \int x\, \mathrm{d} x\\
     b^2
   \end{cases}
$$

### 带方框的等式

$$
\begin{aligned}
 \boxed{x^2+y^2 = z^2}
\end{aligned}
$$

### 求极限

$$
\begin{aligned}
  \lim_{a\to \infty} \tfrac{1}{a}
\end{aligned}
$$

$$
\begin{aligned}
   \lim\nolimits_{a\to \infty} \tfrac{1}{a}
\end{aligned}
$$

### 求积分

$$
\begin{aligned}
   \int_a^b x^2  \mathrm{d} x
\end{aligned}
$$

$$
\begin{aligned}
   \int\limits_a^b x^2  \mathrm{d} x
\end{aligned}
$$

### 求累加

$$
\begin{aligned}
   \sum\nolimits' C_n
\end{aligned}
$$

$$
\begin{aligned}
   \sum_{n=1}\nolimits' C_n
\end{aligned}
$$

### 开根号

$$
\sqrt x * \sqrt[3] x * \sqrt[-1] x
$$

### 省略号的使用

$$
{1+2+3+\ldots+n}
$$

### 其他格式

$\tbinom{n}{k}$
$\binom{n}{k}$
$\dbinom{n}{k}$
${n\brace k}$
${n\choose k}$
${n\brack k}$

​

## Markdown 特殊符号

| 符号   | 说明           | 对应编码   | 英文怎么说             |
| ------ | -------------- | ---------- | ---------------------- |
| &      | AND 符号       | `&amp;`    | ampersand              |
| &lt;   | 小于           | `&lt;`     | little                 |
| &gt;   | 大于           | `&gt;`     | great                  |
| &nbsp; | 空格           | `&nbsp;`   | number space           |
| ¿      | 倒问号         | `&iquest;` | inverted question      |
| ?      | 问号           | `&quest;`  | question               |
| «      | 左书名号       | `&laquo;`  | left angle quote       |
| »      | 右书名号       | `&raquo;`  | right angle quote      |
| "      | 引号           | `&quot;`   | quote                  |
| ‘      | 左单引号       | `&lsquo;`  | left single quote      |
| ’      | 右单引号       | `&rsquo;`  | right single quote     |
| “      | 左双引号       | `&ldquo;`  | left double quote      |
| ”      | 右双引号       | `&rdquo;`  | right double quote     |
| ¶      | 段落符号       | `&para;`   | paragraph              |
| §      | 章节符         | `&sect;`   | section                |
| ×      | 乘号           | `&times;`  | times                  |
| ÷      | 除号           | `&divide;` | divide                 |
| ±      | 加减号         | `&plusmn;` | plus minus             |
| ƒ      | function       | `&fnof;`   | 还没查到               |
| √      | 根号           | `&radic;`  | radic                  |
| ∞      | 无穷大         | `&infin;`  | infinite               |
| °      | 度             | `&deg;`    | degree                 |
| ≠      | 不等号         | `&ne;`     | ne                     |
| ≡      | 恒等于         | `&equiv;`  | equivalent             |
| ≤      | 小于等于       | `&le;`     | less than or equal to  |
| ≥      | 大于等于       | `&ge;`     | great than or equal to |
| ⊥      | 垂直符号       | `&perp;`   | perpendicular          |
| ←      | 左箭头         | `&larr;`   | left arrow             |
| →      | 右箭头         | `&rarr;`   | right arrow            |
| ↑      | 上箭头         | `&uarr;`   | up arrow               |
| ↓      | 下箭头         | `&darr;`   | down arrow             |
| ↔      | 水平箭头       | `&harr;`   | horizontal arrow       |
| ↕      | 竖直箭头       | `&varr;`   | vertical arrow         |
| ⇐      | 双线左箭头     | `&lArr;`   | left arrow             |
| ⇒      | 双线右箭头     | `&rArr;`   | right arrow            |
| ⇑      | 双线上箭头     | `&uArr;`   | up arrow               |
| ⇓      | 双线上箭头     | `&dArr;`   | down arrow             |
| ⇔      | 双线水平双箭头 | `&hArr;`   | horizontal arrow       |
| ⇕      | 双线竖直箭头   | `&vArr;`   | vertical arrow         |
| ♠      | 黑桃           | `&spades;` | spades                 |
| ♥      | 红桃           | `&hearts;` | hearts                 |
| ♣      | 梅花           | `&clubs;`  | club                   |
| ♦      | 方块           | `&diams;`  | diamonds               |
| ©      | 版权           | `&copy;`   | copy right             |
| ®      | 注册商标       | `&reg;`    | registration           |
| ™      | 商标           | `&trade;`  | trade                  |
| ¥      | 人民币         | `&yen;`    |
| €      | 欧元           | `&euro;`   | euro                   |
| ¢      | 美分           | `&cent;`   | cent                   |
| £      | 英磅           | `&pound;`  | pound                  |
| ⊕      |                | `&oplus;`  |
| ½      | 二分之一       | `&frac12;` | fraction               |
| ¼      | 四分之一       | `&frac14;` | fraction               |
| ‰      | 千分符号       | `&permil;` | per mille              |
| ∴      | 所以           | `&there4;` | there fore             |
| π      | 圆周率         | `&pi;`     |
| ¹      | 商标 1         | `&sup1;`   | super 1                |
| α      | alpha          | `&alpha;`  | alpha                  |
| β      | beta           | `&beta;`   | beta                   |
| γ      | gamma          | `&gamma;`  | gamma                  |
| δ      | delta          | `&delta;`  | delta                  |
| θ      | theta          | `&theta;`  | theta                  |
| λ      | lambda         | `&lambda;` | lambda                 |
| σ      | sigma          | `&sigma;`  | sigma                  |
| τ      | tau            | `&tau;`    | tau                    |
