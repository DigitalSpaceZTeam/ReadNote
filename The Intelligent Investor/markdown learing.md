# Hello, World!

一级标题
=======

二级标题
-------预览扩展
# 一级标题

## 二级标题

### 三级标题

~~段落~~

**真的**

* 无序列表
  * 嵌套无序列表
  * 嵌套无序列表
* 无序列表
* 无序列表

1. 有序列表 1
   1. 嵌套有序列表 1
   2. 嵌套有序列表 2
2. 有序列表 2
3. 有序列表 3

- [x] 已经完成的事 1
- [x] 已经完成的事 2
- [x] 已经完成的事 3
- [ ] 仍未完成的事 4
- [ ] 仍未完成的事 5
- 
| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

表格：
| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| 内容 | 内容 |

拓展语法:

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| >    | 内容 |

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| ^    | 内容 |

自动表格对齐: Shift + Alt + F


行内公式: 

单位圆 $x^2+y^2=1$

公式块:

$$
\begin{cases}
x=\rho\cos\theta \\
y=\rho\sin\theta \\
\end{cases}
$$

1. 上标和下标
上标 $x^2 + y^{12} = 1$

上标 $x_1 + y_{12} = 1$

HyperSnips 自动扩展：
xsr  =>  x^{2}

xtp  =>  x^{...}

x1  =>  x_1

xii  =>  x_i

xsb  =>  x_{...}

2. 分式
较小的行内行分数 $\frac{1}{2}$

展示型的分式 $\displaystyle\frac{x+1}{x-1}$

HyperSnips 自动扩展：

1/  =>  \frac{1}{...}

(1 + 2)/  =>  \frac{(1+2)}{...}

//  =>  \frac{...}{...}

3. 根式
开平方 $\sqrt{2}$

开 $n$ 次方 $\sqrt[n]{2}$

4. 空格
数学公式中的 空格和换行 都会在编译时 被忽略，想要实现「空格」的效果，需要用特别的命令。

紧贴 $a\!b$

没有空格 $ab$

小空格 $a\,b$

中等空格 $a\;b$

大空格 $a\ b$

quad 空格 $a\quad b$

两个 quad 空格 $a\qquad b$

累加 $\sum_{k=1}^n\frac{1}{k}  \quad  \displaystyle\sum_{k=1}^n\frac{1}{k}$

累乘 $\prod_{k=1}^n\frac{1}{k}  \quad  \displaystyle\prod_{k=1}^n\frac{1}{k}$

积分 $\displaystyle \int_0^1x{\rm d}x  \quad  \iint_{D_{xy}}  \quad  \iiint_{\Omega_{xyz}}$

6. 括号修饰
用 \left 和 \right 可以让括号适配内部大小

圆括号 $\displaystyle \left(\sum_{k=1}^{n}\frac{1}{k} \right)^2$

方括号 $\displaystyle \left[\sum_{k=1}^{n}\frac{1}{k} \right]^2$

花括号 $\displaystyle \left\{\sum_{k=1}^{n}\frac{1}{k} \right\}^2$

尖括号 $\displaystyle \left\langle\sum_{k=1}^{n}\frac{1}{k} \right\rangle^2$


HyperSnips 自动扩展：

@(  =>  \left( ... \right)

@[  =>  \left[ ... \right]

@{  =>  \left\{ ... \right\}

@<  =>  \left< ... \right>

set  =>  \{ ... \}
7. 多行算式对齐
居中:

$$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$$

左对齐:

$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$

HyperSnips 自动扩展：

ali  =>
\begin{aligned}
... \\
\end{aligned}

8. 方程组
$$
\begin{cases}
k_{11}x_1+k_{12}x_2+\cdots+k_{1n}x_n=b_1 \\
k_{21}x_1+k_{22}x_2+\cdots+k_{2n}x_n=b_2 \\
\cdots \\
k_{n1}x_1+k_{n2}x_2+\cdots+k_{nn}x_n=b_n \\
\end{cases}
$$

HyperSnips 自动扩展：

case  =>
\begin{cases}
... \\
\end{cases}
9. 矩阵
矩阵:

$$
\begin{pmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{pmatrix}

\quad

\begin{bmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{bmatrix}
$$ 

行列式: 

$$
\begin{vmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{vmatrix}
$$

HyperSnips 自动扩展：

bmat2  =>  \begin{bmatrix} ... & ... \\ ... & ... \\\end{bmatrix}

vec2  =>  \begin{pmatrix} ... \\ ... \\\end{pmatrix}
tips：按下 Tab 键可以切换到下一个位置。

HyperSnips 自动扩展：

alpha  =>  \alpha

Sigma  =>  \Sigma
11. 公式编号与引用
$$
x+2 \tag{1.2}
$$

$$
\begin{equation}
x^n+y^n=z^n
\end{equation}
$$

由公式 $(1.2)$ 可得到结论

12. 零碎的重要语法
点乘 $\cdot$, 叉乘 $\times$, 异或 $\otimes$, 直和 $\oplus$, 加减 $\pm$, 复合 $\circ$.
小于等于 $\leq$, 大于等于 $\geq$, 不等 $\neq$, 恒等 $\equiv$, 约等 $\approx$, 等价 $\cong$, 相似 $\sim$, 相似等于 $\simeq$, 点等 $\doteq$.
逻辑与 $\land$, 逻辑或 $\lor$, 逻辑非 $\lnot$, 蕴涵 $\to$, 等价 $\leftrightarrow$.
因为 $\because$, 所以 $\therefore$, 存在 $\exist$, 任意 $\forall$.
左小箭头 $\leftarrow$, 右小箭头 $\rightarrow$, 左大箭头 $\Leftarrow$, 右大箭头 $\Rightarrow$, 右长箭头 $\xrightarrow[fgh]{abcde}$.
属于 $\in$, 包含于 $\subset$, 真包含于 $\subseteq$, 交 $\cap$, 并 $\cup$, 空集 $\empty$
短向量 $\vec{x}$, 长向量 $\overrightarrow{AB}$, 上横线 $\overline{p}$.
无限 $\infty$, 极限 $\lim$, 微分 ${\rm d}$, 偏导 $\partial$, 点求导 $\dot{y}$, 点二阶导 $\ddot{y}$, 变化量 $\Delta$, 梯度 $\nabla$.
横省略 $\cdots$, 竖省略 $\vdots$, 斜省略 $\ddots$.
常见函数 $\sin$, $\cos$, $\tan$, $\arcsin$, $\arccos$, $\arctan$, $\ln$, $\log$, $\exp$.


HyperSnips 自动扩展：

**  =>  \cdot
xx  =>  \times
otimes  =>  \otimes
<=  =>  \le
!=  =>  \neq
==  =>  \equiv
~~  =>  \thickapprox
sim  =>  \sim
land  =>  \land
lor  =>  \lor
bec  =>  \because
thr  =>  \therefore
EE  =>  \exists
AA  =>  \forall
inn  =>  \in
sse  =>  \subseteq
sqs  =>  \sqsubseteq
cap  =>  \cap
cup  =>  \cup
empty  =>  \empty
oo  =>  \infty
lim  =>  \lim_{<n> \to <\infty>}
dd  =>  \mathrm{d}
part  =>  \frac{\partial <V>}{\partial <x>}
Delta  =>  \Delta
nabla  =>  \nabla
...  =>  \cdots
sin  =>  \sin

输出为 PDF
我们在右侧预览栏邮件菜单, 选择 在浏览器中打开.

![alt text](image.png)




在浏览器中右键选择 打印.

![alt text](image-1.png)




就能够 输出为 PDF 了.


![alt text](image-2.png)

s

原生快捷键
通用操作
Ctrl + C, 复制当前文本
Ctrl + V, 粘贴当前文本
Ctrl + Z, 撤销
Ctrl + Shift + Z, 反撤销
Shift + Alt + F, 整理代码
Ctrl + /, 将当前行注释 / 反注释, 当多行文本被选中时, 将多行文本注释


光标操作
Ctrl + ← 将光标向左移动一个单词
Ctrl + → 将光标向右移动一个单词
Ctrl + Alt + ↑, 向上加入一个光标
Ctrl + Alt + ↓, 向下加入一个光标
Ctrl + Alt + U, 撤销上次光标操作


界面移动
Ctrl + ↑ 向上移动当前界面
Ctrl + → 向下移动当前界面


选中操作
Shift + ← 向左选中 / 反选中一个字符(重要)
Shift + → 向右选中 / 反选中一个字符(重要)
Ctrl + Shift + ← 向左选中 / 反选中一个单词(重要)
Ctrl + Shift + → 向右选中 / 反选中一个单词(重要)
Ctrl + D当前有选中文本时, 将下一个与其相同的文本加入选中 (重要)


文本行操作
Ctrl + C当前无选中文本时, 复制当前行
Shift + Alt + ↑ 向上复制当前行, 当多行文本被选中时, 向上复制多行 (重要)
Shift + Alt + ↓ 向下复制当前行, 当多行文本被选中时, 向下复制多行 (重要)
Alt + ↑ 向上移动当前行, 当多行文本被选中时, 将当前多行文本向上移动 (重要)
Alt + ↓ 向下移动当前行, 当多行文本被选中时, 将当前多行文本向下移动 (重要)


插件增加的快捷键
Markdown 语法
Ctrl + B当前有选中文本时, 将文本加粗
Ctrl + I当前有选中文本时, 将文本变为斜体
Ctrl + M 进入数学公式模式 (加入美元符)


图片粘贴
Ctrl + Alt + V 粘贴剪贴板图片 (本地)
Ctrl + Alt + V 粘贴剪贴板图片 (图床)


光标操作
Ctrl + Alt + U 将多选光标变为单选


选中操作
Shift + Alt + ← 向左复制当前选中文本 (重要)
Shift + Alt + → 向右复制当前选中文本 (重要)
Alt + ← 向左移动当前选中文本一个字符(重要)
Alt + → 向右移动当前选中文本一个字符(重要)
Ctrl + Alt + ← 向左移动当前选中文本一个单词(重要)
Ctrl + Alt + → 向右移动当前选中文本一个单词(重要)


计算器功能
Ctrl + Shift + Alt + E 计算当前选中表达式, 用等号连接并输出
Ctrl + Shift + Alt + R 计算当前选中表达式, 并替换当前选中表达式
Ctrl + Shift + Alt + D 定义当前选中表达式, 无输出
