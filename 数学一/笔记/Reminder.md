# Reminder

## 高等数学

### 泰勒公式（级数）

$${\rm e}^x=\displaystyle\sum_{n=0}^{\infty}\dfrac{x^n}{n!}=1+x+\dfrac{x}{2!}+\cdots$$



$$\sin x=\displaystyle\sum_{n=0}^{\infty}(-1)^{n}\dfrac{x^{2n+1}}{(2n+1)!}=x-\dfrac{x^3}{3!}+\cdots$$



$$\cos x=\displaystyle\sum_{n=0}^{\infty}(-1)^{n}\dfrac{x^{2n}}{(2n)!}=1-\dfrac{x^2}{2!}+\cdots$$



$$-\ln(1-x)=\displaystyle\sum_{n=1}^{\infty}\dfrac{x^n}{n}=x+\dfrac{x^2}{2}+\cdots,\,-1\leqslant x<1$$



$$\ln(1+x)=\displaystyle\sum_{n=1}^{\infty}(-1)^{n-1}\dfrac{x^n}{n}=x-\dfrac{x^2}{2}+\cdots,\,-1<x\leqslant 1$$



$$\dfrac{1}{1-x}=\displaystyle\sum_{n=0}^{\infty}x^{n}=1+x+x^2+\cdots,\,-1<x<1$$



$$\dfrac{1}{1+x}=\displaystyle\sum_{n=0}^{\infty}(-1)^n x^n=1-x+x^2-\cdots,\,-1<x<1$$



$$\dfrac{1}{(1-x)^2}=\displaystyle\sum_{n=1}^{\infty}n x^{n-1}=1+2x+3x^2+\cdots,\,-1<x<1$$



$$\dfrac{x}{(1-x)^2}=\displaystyle\sum_{n=1}^{\infty}n x^{n}=x+2x^2+3x^3+\cdots,\,-1<x<1$$



$$\dfrac{x(x+1)}{(1-x)^3}=\displaystyle\sum_{n=1}^{\infty}n^2 x^{n}=x+4x^2+9x^3+\cdots,\,-1<x<1$$



$$\dfrac{{\rm e}^x+{\rm e}^{-x}}{2}=\displaystyle\sum_{n=0}^{\infty}\dfrac{x^{2n}}{(2n)!}=1+\dfrac{x^2}{2!}+\cdots$$



$$\tan x=x+\dfrac{x^3}{3}+\cdots\,(x\rightarrow0)$$



$$\arcsin x=x+\dfrac{x^3}{6}+\cdots\,(x\rightarrow0)$$



$$\arccos x=\dfrac{\pi}{2}-x-\dfrac{x^3}{6}-\cdots\,(x\rightarrow0)$$



$$\arctan x=x-\dfrac{x^3}{3}+\cdots\,(x\rightarrow0)$$



$$(1+x)^{\frac{1}{x}}={\rm e}-\dfrac{\rm e}{2}x+\cdots$$



$$Fab(n)=\dfrac{1}{\sqrt{5}}\left[\left(\dfrac{\sqrt{5}+1}{2}\right)^n+(-1)^{n-1}\left(\dfrac{\sqrt{5}+1}{2}\right)^n\right]$$，$$\displaystyle \sum_{n=1}^{\infty}Fab(n)\cdot x^n=\dfrac{x}{1-x-x^2}$$

### 求导（积分）

$$\displaystyle\int\tan x\,{\rm d}x=-\ln|\cos x|+{\rm C}$$



$$\displaystyle\int\cot x\,{\rm d}x=\ln|\sin x|+{\rm C}$$



$$\displaystyle\int\sec x\,{\rm d}x=\ln|\sec x+\tan x|+{\rm C}$$



$$\displaystyle\int\csc x\,{\rm d}x=\ln|\csc x-\cot x|+{\rm C}$$



$$\displaystyle\int\dfrac{{\rm d}x}{\sqrt{a^2-x^2}}=\arcsin\dfrac{x}{a}+{\rm C}$$



$$\displaystyle\int\dfrac{{\rm d}x}{a^2+x^2}=\dfrac{1}{a}\arctan\dfrac{x}{a}+{\rm C}$$



$$\displaystyle\int\dfrac{{\rm d}x}{\sqrt{x^2+a^2}}=\ln(x+\sqrt{x^2+a^2})+{\rm C}$$



$$\displaystyle\int\dfrac{{\rm d}x}{\sqrt{x^2-a^2}}=\ln(x+\sqrt{x^2-a^2})+{\rm C}$$



$$\displaystyle\int\dfrac{{\rm d}x}{x^2-a^2}=\dfrac{1}{2a}\ln\left|\dfrac{x-a}{x+a}\right|+{\rm C}$$



$$\displaystyle\int\sqrt{a^2-x^2}\,{\rm d}x=\dfrac{a^2}{2}\arcsin\dfrac{x}{a}+\dfrac{x}{2}\sqrt{a^2-x^2}+{\rm C}$$



### 反函数求导

$y=f(x)$ 反函数 $x=\varphi(y)$：



$$\varphi^{'}(y)=\dfrac{1}{f^{'}(x)},\,\varphi^{''}(y)=-\dfrac{f^{''}(x)}{\left[f^{'}(x)\right]^3}$$



### 曲率半径

$$k=\dfrac{|y^{''}|}{\left[1+(y^{'})^2\right]^{\frac{3}{2}}},\,R=\dfrac{1}{k}$$



### 基本不等式与其积分形式

$$\displaystyle\dfrac{n}{\frac{1}{x_1}+\frac{1}{x_2}+\cdots+\frac{1}{x_n}}\leqslant\sqrt[n]{x_1x_2\cdots x_n}\leqslant\dfrac{x_1+x_2+\cdots+x_n}{n}\leqslant\sqrt{\dfrac{x_1^2+x_2^2+\cdots+x_n^2}{n}}$$



$$\displaystyle\dfrac{b-a}{\int_a^b\dfrac{1}{f(x)}\,{\rm d}x}\leqslant{\rm e}^{\tfrac{\int_a^b\ln f(x)\,{\rm d}x}{b-a}}\leqslant\dfrac{\int_a^b f(x)\,{\rm d}x}{b-a}\leqslant\sqrt{\dfrac{\int_a^b f^2(x)\,{\rm d}x}{b-a}}$$（取 $x_i=a+\dfrac{b-a}{n}$ 即可）



积分不等式的算数平均数$\leqslant$平方平均数，在二重积分中可能会用到

### 反常积分、级数收敛

在 $1$ 附近的 $0<p<1$ 收敛（$0\rightarrow 1,\,\dfrac{1}{2}\rightarrow 1,\,1\rightarrow 2$）

$\displaystyle\int_0^1\dfrac{1}{x^p}\,{\rm d}x\Rightarrow0<p<1$ 收敛



$\displaystyle\int_1^{+\infty}\dfrac{1}{x^p}\,{\rm d}x\Rightarrow p>1$ 收敛



$\displaystyle\int_0^\frac{1}{2}\dfrac{1}{x\ln^p x}\,{\rm d}x\Rightarrow p>1$ 收敛



$\displaystyle\int_\frac{1}{2}^1\dfrac{1}{x\ln^p x}\,{\rm d}x\Rightarrow 0<p<1$ 收敛



$\displaystyle\int_1^2\dfrac{1}{x\ln^p x}\,{\rm d}x\Rightarrow 0<p<1$ 收敛



$\displaystyle\int_2^{+\infty}\dfrac{1}{x\ln^p x}\,{\rm d}x\Rightarrow p>1$ 收敛



$\displaystyle\sum_{n=1}^{\infty}\dfrac{1}{n^p}\Rightarrow p>1$ 收敛



$\displaystyle\sum_{n=1}^{\infty}\dfrac{1}{n\ln^p n}\Rightarrow p>1$ 收敛



### 一元函数积分学的几何应用

#### 面积

直角坐标：$$S=\displaystyle\int_a^b|f(x)-g(x)|\,{\rm d}x$$



极坐标：$$S=\displaystyle\int_\alpha^\beta\dfrac{1}{2}|r_2^2(\theta)-r_1^2(\theta)|\,{\rm d}\theta$$

#### 旋转体

绕 $x$ 轴：$$V_x=\displaystyle\int_a^b\pi y^2(x)\,{\rm d}x$$



绕 $x$ 轴侧面积：$$S=\int_a^b 2\pi|y(x)|\sqrt{1+(y^{'})^2}\,{\rm d}x=\int_a^b 2\pi|y(x)|\sqrt{(x^{'})^2+(y^{'})^2}\,{\rm d}t$$ （注意参数方程形式已经是 $\sqrt{(x^{'})^2+(y^{'})^2}\,{\rm d}t$ 了，就不要再在 ${\rm d}t$ 前面乘 $x^{'}$ 了）



绕 $y$ 轴：$$V_y=\displaystyle\int_a^b2\pi x|y(x)|\,{\rm d}x$$

#### 弧长

直角坐标：$$s=\displaystyle\int_a^b\sqrt{1+(y^{'})^2}\,{\rm d}x$$



极坐标：$$s=\displaystyle\int_\alpha^\beta\sqrt{r^2+(r^{'})^2}\,{\rm d}\theta$$



参数方程：$$s=\displaystyle\int_a^b\sqrt{(x^{'})^2+(y^{'})^2}\,{\rm d}t$$



### $\Gamma$ 函数

$$\displaystyle\int_{-\infty}^{+\infty} {\rm e}^{-t^2}\,{\rm d}t=\sqrt{\pi}$$



$$\displaystyle\int_{0}^{+\infty} {\rm e}^{-t^2}\,{\rm d}t=\dfrac{\sqrt{\pi}}{2}$$



$$\displaystyle\Gamma(\dfrac{1}{2})=\int_{0}^{+\infty} t^{-\frac{1}{2}}{\rm e}^{-t^2}\,{\rm d}t=\sqrt{\pi}$$



$$\displaystyle\Gamma(\dfrac{3}{2})=\dfrac{1}{2}\cdot\Gamma(\dfrac{1}{2})=\int_{0}^{+\infty} t^{\frac{1}{2}}{\rm e}^{-t^2}\,{\rm d}t=\dfrac{\sqrt{\pi}}{2}$$



### 证明连续可偏导/可微

连续可偏导：①求 $f^{'}_x$，$f^{'}_y$；②求 $\displaystyle \lim_{x\rightarrow 0,\,y\rightarrow 0}f^{'}_x$，$\displaystyle \lim_{x\rightarrow 0,\,y\rightarrow 0}f^{'}_y$

可微：① $\Delta f=f(x+\Delta x,\,y+\Delta y)-f(x,\,y)$；② $\displaystyle \lim_{\rho\rightarrow 0}\dfrac{\Delta f-\left[f^{'}_x\Delta x+f^{'}_y\Delta y\right]}{\rho}=0$ 吗？

### 多元积分隐函数求导

#### $F(x,\,y,\,z)=0$

$$\dfrac{\part z}{\part x}=-\dfrac{F_x^{'}}{F_z^{'}},\,\dfrac{\part z}{\part y}=-\dfrac{F_y^{'}}{F_z^{'}}$$

#### $F(x,\,y,\,z)=0,\,G(x,\,y,\,z)=0$

$$\dfrac{{\rm d}y}{{\rm d}x}=-\dfrac{\frac{\part(F,\,G)}{\part(z,\,x)}}{\frac{\part(F,\,G)}{\part(z,\,y)}},\,\dfrac{{\rm d}z}{{\rm d}x}=-\dfrac{\frac{\part(F,\,G)}{\part(y,\,x)}}{\frac{\part(F,\,G)}{\part(y,\,z)}}$$



### 多元函数无条件极值

$\Delta=AC-B^2>0$ 时，$A<0$ 极大，$A>0$ 极小



### 重积分换元

$$\displaystyle\iint_{D_{xy}}f(x,\,y)\,{\rm d}x{\rm d}y=\iint_{D_{uv}}f\left[x(u,\,v),\,y(u,\,v)\right]\,\left|\dfrac{\part(x,\,y)}{\part(u,\,v)}\right|\,{\rm d}u{\rm d}v$$



$$\displaystyle\iiint_{\Omega_{xyz}}f(x,\,y,\,z)\,{\rm d}x{\rm d}y{\rm d}z=\iiint_{\Omega_{uv\omega}}f\left[x(u,\,v,\,\omega),\,y(u,\,v,\,\omega),\,z(u,\,v,\,\omega)\right]\,\left|\dfrac{\part(x,\,y,\,z)}{\part(u,\,v,\,\omega)}\right|\,{\rm d}u{\rm d}v{\rm d}\omega$$



注意这是行列式的**绝对值**

### 微分方程

#### 一阶齐次微分方程

$$\displaystyle\dfrac{{\rm d}y}{{\rm d}x}=f(\dfrac{y}{x})\Rightarrow\int\dfrac{{\rm d}u}{f(u)-u}=\int\dfrac{{\rm d}x}{x}$$



$$\displaystyle\dfrac{{\rm d}x}{{\rm d}y}=f(\dfrac{x}{y})\Rightarrow\int\dfrac{{\rm d}u}{f(u)-u}=\int\dfrac{{\rm d}y}{y}$$

#### 二阶可降次微分方程

缺 $y$，即 $y^{''}=f(x,\,y^{'})\Rightarrow p^{'}=f(x,\,p)$

缺 $x$，即 $y^{''}=f(y,\,y^{'})\Rightarrow p\dfrac{{\rm d}p}{{\rm d}y}=f(y,\,p)$

#### 伯努利方程

$$\dfrac{{\rm d}y}{{\rm d}x}+py=qy^{n}\Rightarrow\dfrac{1}{1-n}\dfrac{{\rm d}z}{{\rm d}x}+pz=q\ (z=y^{1-n})$$

#### 欧拉方程

$$x^2y^{''}+pxy^{'}+qy=f(x)$$

当 $x>0$ 时，令 $x={\rm e}^t$，则

$$xy^{'}={\rm D}y=\dfrac{{\rm d}y}{{\rm d}t},\,x^2y^{''}={\rm D}({\rm D}-1)y=({\rm D}^2-{\rm D})y=\dfrac{{\rm d}^2y}{{\rm d}t^2}-\dfrac{{\rm d}y}{{\rm d}t},\,x^3y^{'''}={\rm D}({\rm D}-1)({\rm D}-2)y$$，依次类推。

当 $x<0$ 时，令 $x=-{\rm e}^t$，则

$$xy^{'}=-{\rm D}y=-\dfrac{{\rm d}y}{{\rm d}t},\,x^2y^{''}=-{\rm D}(-{\rm D}-1)y=({\rm D}^2+{\rm D})y=\dfrac{{\rm d}^2y}{{\rm d}t^2}+\dfrac{{\rm d}y}{{\rm d}t},\,x^3y^{'''}={-\rm D}(-{\rm D}-1)(-{\rm D}-2)y$$

根据做题情况来看，$x>0$ 和 $x<0$ 的解似乎是一样的

### 幂级数

1. 收敛域 $\neq$ 收敛区间
2. 普通幂级数 $\displaystyle R=\lim_{n\rightarrow\infty}\left|\dfrac{a_n}{a_{n+1}}\right|$
3. 缺项级数 $$\displaystyle \lim_{n\rightarrow\infty}\left|\dfrac{u_{n+1}}{u_n}\right|$$

### 傅里叶级数

$\displaystyle f(x)\sim \dfrac{a_0}{2}+\sum_{n=1}^{\infty}\left(a_n\cos\dfrac{n\pi x}{l}+b_n\sin\dfrac{n\pi x}{l}\right)$

$$\displaystyle a_n=\dfrac{1}{l}\int_{-l}^{l}f(x)\cos\dfrac{n\pi x}{l}\,{\rm d}x$$

$$\displaystyle b_n=\dfrac{1}{l}\int_{-l}^{l}f(x)\sin\dfrac{n\pi x}{l}\,{\rm d}x$$

### 线切面法

参数方程**：**$$\boldsymbol \tau=(x^{'}(t_0),\,y^{'}(t_0),\,z^{'}(t_0))$$

$F(x,\,y,\,z)=0,\,G(x,\,y,\,z)=0$**：**$$\boldsymbol \tau=(1,\,y^{'}(x_0),\,z^{'}(x_0))$$



参数方程**：**$$\boldsymbol n=\tau_1\times\tau_2=(x^{'}_u,\,y^{'}_u,\,z^{'}_u)\times(x^{'}_v,\,y^{'}_v,\,z^{'}_v)$$

$F(x,\,y,\,z)=0$**：**$$\boldsymbol n=(F^{'}_x\Big{|}_{P_0},\,F^{'}_y\Big{|}_{P_0},\,F^{'}_z\Big{|}_{P_0})$$

$z=f(x,\,y)$**：**$$\boldsymbol n=(f^{'}_x(x_0,\,y_0),\,f^{'}_y(x_0,\,y_0),\,-1)$$

### 旋转曲面

①垂直

②距离相等（绕坐标轴：某个坐标相等）

特别地，绕 $z$ 轴旋转，且 $x=\varphi(z),\,y=\psi(z)$，则旋转曲面 $\Gamma:\,x^2+y^2=\varphi^2(z)+\psi^2(z)$

### 直线 $L$ 在平面 $\Pi$ 上的投影

过 $L$ 作平面 $\Pi_1$，其法向量 $\boldsymbol {n_1}$ 满足 $\boldsymbol {n_1} \perp \boldsymbol s$，$\boldsymbol {n_1}\perp\boldsymbol n$，故 $\boldsymbol {n1}=\boldsymbol s\times \boldsymbol n$

在 $L$ 上取一点 $P$，用 $P$ 和 $\boldsymbol {n_1}$ 写出 $\Pi_1$ 的方程

投影直线即两平面交线，$L_{投}:\,\begin{equation}\begin{cases}\Pi\\\Pi_1\end{cases}\end{equation}$

特别地，在 $xOy$ 上的投影？直接消掉 $z$ 即可，$L_{投}:\,\begin{equation}\begin{cases}F(x,\,y)=0\\z=0\end{cases}\end{equation}$

### 点线面位置关系

#### 点-线

三维：$$d=\dfrac{|\boldsymbol {C_0M}\times \boldsymbol s|}{|\boldsymbol s|}$$

#### 线-线

异面：$$d=\dfrac{|\boldsymbol {s_1}\times \boldsymbol {s_2} \cdot \boldsymbol {P_1P_2}|}{\boldsymbol {s_1}\times \boldsymbol {s_2}}$$

其他的很显然了，这里不写

### 方向导数

$$\displaystyle \dfrac{\part u}{\part \boldsymbol l}\Big{|}_{P_0}=\lim_{\rho\rightarrow 0^{+}}\dfrac{f(x_0+\Delta x,\,y_0+\Delta y,\,z_0+\Delta z)-f(x_0,\,y_0,\,z_0)}{\rho}$$

注意这是单向的极限，和导数、偏导数不一样

### 梯度、散度、旋度

$$\boldsymbol {grad}\ u\Big{|}_{P_0}=(u^{'}_x,\,u^{'}_y,\,u^{'}_z)$$



$$div\ \boldsymbol A=\dfrac{\part P}{\part x}+\dfrac{\part Q}{\part y}+\dfrac{\part R}{\part z}$$



$$\boldsymbol {rot\ A}=\begin{vmatrix}\boldsymbol i&\boldsymbol j&\boldsymbol k\\\\\dfrac{\part}{\part x}&\dfrac{\part}{\part y}&\dfrac{\part}{\part z}\\\\P&Q&R\end{vmatrix}$$

### 曲线积分、曲面积分

$$\displaystyle \int_Lf(x,\,y)\,{\rm d}s=\int_a^b f(x,\,y)\sqrt{1+(y^{'}_x)^2}\,{\rm d}x=\cdots=\cdots$$



$$\displaystyle \iint_\Sigma f(x,\,y,\,z)\,{\rm d}S=\iint_{D_{xy}} f(x,\,y,\,z)\sqrt{1+(z^{'}_x)^2+(z^{'}_y)^2}\,{\rm d}x{\rm d}y$$



$$\displaystyle \int_LP\,{\rm d}x+Q\,{\rm d}y=\int_a^b \left(Px^{'}+Qy^{'}\right)\,{\rm d}t$$



$$\displaystyle \int_LP\,{\rm d}x+Q\,{\rm d}y+R\,{\rm d}z=\int_{L^{'}}P_1\,{\rm d}x+Q_1\,{\rm d}y$$ （消去 $z$，${\rm d}z$ 即 $z$ 对 $x,\,y$ 的全微分）



$$\displaystyle \iint_\Sigma R\,{\rm d}x{\rm d}y=\pm\iint_{D_{xy}} R\,{\rm d}x{\rm d}y$$（指向 $z$ 轴正方向取正号）



$$\displaystyle \iint_\Sigma P\,{\rm d}y{\rm d}z+Q\,{\rm d}z{\rm d}x+R\,{\rm d}x{\rm d}y=\pm\iint_{D_{xy}} \left[P\left(-\dfrac{\part z}{\part x}\right)+Q\left(-\dfrac{\part z}{\part y}\right)+R\right]\,{\rm d}x{\rm d}y$$（指向 $z$ 轴正方向取正号）



封闭曲线：二维格林公式（外逆内顺，左手在内；路径无关？）、三维斯托克斯公式（右手系；路径无关：$\boldsymbol{rot\ F}=0$）

封闭曲面：高斯公式（外侧为正）

(I)、(II)类积分转化，法向量方向与二类积分线（面）朝向一致则为正

P.S. 从物理含义出发的积分式：

1. 做功：
   1. 二维：力 $\boldsymbol{F}$，给定曲线 $L$，$L$ 上一点处的单位切向量为 $\boldsymbol\tau$： $\displaystyle\int_L \boldsymbol{F}\cdot\boldsymbol{\tau}\,{\rm d}s=\int_L P\,{\rm d}x+Q\,{\rm d}y $
   2. 三维：向量场 $\boldsymbol{A}$，给定曲线 $\Gamma$，$\Gamma$ 上一点处的单位切向量为 $\boldsymbol\tau$：$$\displaystyle\int_\Gamma \boldsymbol{A}\cdot\boldsymbol{\tau}\,{\rm d}s=\int_\Gamma P\,{\rm d}x+Q\,{\rm d}y+R\,{\rm d}z $$
2. 通量：
   1. 向量场 $\boldsymbol{A}$，给定曲面 $\Sigma$，$\Sigma$ 上一点处的单位法向量为 $\boldsymbol n$：$\displaystyle\iint_\Sigma\boldsymbol{A}\cdot\boldsymbol{n}\,{\rm d}S=\iint_\Gamma P\,{\rm d}y{\rm d}z+Q\,{\rm d}z{\rm d}x+R\,{\rm d}x{\rm d}y$

## 线性代数

### $A^{*}$

$A^{*}=|A|A^{-1},\,A^{-1}=\dfrac{A^{*}}{|A|}$

### 向量空间

坐标系变换：$$\left[\beta_1,\,\beta_2,\,\cdots,\,\beta_n\right]=\left[\alpha_1,\,\alpha_2,\,\cdots,\,\alpha_n\right]C$$

坐标变换：$$\left[x_1,\,x_2,\,\cdots,\,x_n\right]^{T}=C\left[y_1,\,y_2,\,\cdots,\,y_n\right]^{T}$$，或 $\left[x_1,\,x_2,\,\cdots,\,x_n\right]^{T}=\left[y_1,\,y_2,\,\cdots,\,y_n\right]^{T}C^{T}$

略有差异（$x=Py$，或 $x=yP^{T}$）

### $A$ 相关矩阵的特征值和特征向量

$aA+bE,\,A^{-1},\,A^{*},\,A^{n}$ 特征向量均相同（特征值不同）

$P^{-1}AP$（相似阵）特征值相同，特征向量为 $P^{-1}\alpha$

### 矩阵正定

$\Leftrightarrow$ 顺序余子式大于零（用于求解矩阵内的未知数范围）

### 矩阵的等价、相似、合同

$A$ 和 $B$ 等价 $\Leftrightarrow PAQ=B\Leftrightarrow r(A)=r(B)$

$A$ 和 $B$ 相似 $\Leftrightarrow P^{-1}AP=B$

$A$ 和 $B$ 合同 $\Leftrightarrow P^{T}AP=B\Leftrightarrow$ 正负惯性指数相同

P.S. 向量组等价：彼此可线性表示

## 概率论与数理统计

### DX

注意有些时候 $DX$ 可能比 $EX^2$ 好算：$DX=E(X-EX)^2$，尤其适用于 $f(x)$ 关于 $x=EX$ 对称的情况

### 卷积

$X,\,Y$ 不独立，$Z=X+Y$，则 $\displaystyle f_Z(z)=\int_{-\infty}^{+\infty}f(x,\,z-x)\,{\rm d}x$

$X,\,Y$ 独立，$Z=X+Y$，则 $\displaystyle f_Z(z)=\int_{-\infty}^{+\infty}f_X(x)f_Y(z-x)\,{\rm d}x$

### 矩

* $k$ 阶矩（原点矩）：$E(X^k)$
* $k$ 阶中心矩：$E([X-EX]^k)$
* $k+l$ 阶混合矩：$E(X^kY^l)$
* $k+l$ 阶混合中心矩：$E([X-EX]^k[Y-EY]^l)$
* 协方差：$Cov(X,\,Y)=1+1阶混合中心矩=E(XY)-EXEY$
* 相关系数：$\rho_{xy}=\dfrac{Cov(X,\,Y)}{\sqrt{DX}\sqrt{DY}}$
* $Cov(X,\,Y)=0\Leftrightarrow 不相关 \Leftarrow 独立$

### 大数定律与中心极限定理

* $P\{|X-EX|\geqslant\varepsilon\}\leqslant\dfrac{DX}{\varepsilon^2}$

  

* $\displaystyle DX_i\leqslant c\Rightarrow \bar{X}\overset{P}{\rightarrow}\dfrac{1}{n}\sum_{i=1}^{n} EX_i$

* $\displaystyle EX_i=\mu\Rightarrow \bar{X}\overset{P}{\rightarrow}\mu$

  

* 若 $EX=\mu,\,DX=\sigma^2$，则 $P\left\{\dfrac{\displaystyle\sum_{i=1}^{n}X_i-n\mu}{\sqrt{n}\sigma}\leqslant x\right\}=\Phi(x)$，即 $\displaystyle \sum_{i=1}^{n}X_i\sim N(n\mu,\,n\sigma^2)$

### 样本均值、样本方差

* $\displaystyle \bar{X}=\dfrac{1}{n}\sum_{n=1}^{n}X_i\qquad E\bar{X}=EX,\,D\bar{X}=\dfrac{1}{n}DX$
* $\displaystyle S^2=\dfrac{1}{n-1}\sum_{n=1}^{n}(X_i-\bar{X})^2\quad ES^2=DX$

### 抽样分布

* $X_i\sim N(0,\,1)\Rightarrow\chi^2=X_1^2+X_2^2+\cdots+X_n^2\sim\chi^{2}(n)$

  $E\chi^2=n,\,D\chi^2=2n$

* $X_i\sim N(0,\,1),\,Y\sim\chi^2(n)\Rightarrow T=\dfrac{X}{\sqrt{Y/n}}\sim t(n)$

  $t_{1-\alpha}(n)=-t_\alpha(n)$

* $X\sim\chi^2(n_1),\,Y\sim\chi^2(n_2)\Rightarrow F=\dfrac{X/n_1}{Y/n_2}\sim F(n_1,\,n_2)$

  $F_{1-\alpha}(n_1,\,n_2)=\dfrac{1}{F_\alpha(n_2,\,n_1)}$
  

### 正态总体的抽样分布

* $X\sim N(\mu,\,\sigma^2)$ 则

  $\bar{X}\sim N(\mu,\,\dfrac{\sigma^2}{n}),\,U=\dfrac{\bar{X}-\mu}{\sigma/\sqrt{n}}\sim N(0,\,1),\,T=\dfrac{\bar{X}-\mu}{S/\sqrt{n}}\sim t(n-1)$

  $\chi^2=\dfrac{(n-1)S^2}{\sigma^2}\sim \chi^2(n-1)$

* $X\sim N(\mu_1,\,\sigma_1^2),\,Y\sim N(\mu_2,\,\sigma_2^2)$ 则

  $\bar{X}-\bar{Y}\sim N(\mu_1-\mu_2,\,\dfrac{\sigma_1^2}{n_1}+\dfrac{\sigma_2^2}{n_2}),\,U=\dfrac{(\bar{X}-\bar{Y})-(\mu_1-\mu_2)}{\sqrt{\dfrac{\sigma_1^2}{n_1}+\dfrac{\sigma_2^2}{n_2}}}\sim N(0,\,1)$

  $\sigma_1=\sigma_2\Rightarrow T=\dfrac{(\bar{X}-\bar{Y})-(\mu_1-\mu_2)}{S_\omega\sqrt{\dfrac{1}{n_1}+\dfrac{1}{n_2}}}\sim t(n_1+n_2-2)\ \left(S^2_\omega=\dfrac{(n_1-1)S_1^2+(n_2-1)S_2^2}{n_1+n_2-2}\right)$

  $F=\dfrac{S_1^2/\sigma_1^2}{S_2^2/\sigma_2^2}\sim F(n_1-1,\,n_2-1)$

### 参数估计

* $T$ 是 $\theta$ 的无偏估计量，则 $ET=\theta$

* $T$ 是 $\theta$ 的一致估计量，则 $T\overset{P}\rightarrow\theta$

* 矩估计：$\bar{X}=\begin{equation}\begin{cases}x_1p_1+x_2p_2+\cdots+x_np_n\\[7pt]\displaystyle  \int_{-\infty}^{\infty}xf(x){\rm d}x\end{cases}\end{equation}$解出 $\hat{\theta}$

  若一阶矩估计方程算不出来，则使用二阶矩估计

* 最大似然估计：$L(\theta)=\begin{equation}\begin{cases}p_1^{n_1}p_2^{n_2}\cdots p_k^{n_k}\\[6pt]f(x_1)f(x_2)\cdots f(x_n)\end{cases}\end{equation}$，令 $\dfrac{{\rm d}\ln L}{{\rm d}x}=0$，解出 $\hat{\theta}$

  如果最大值不在极值点取到，则不能用最大似然估计

* 区间估计

  <img src="image\math1" alt="image-20220911164551194" style="zoom:80%;" />
  
  <img src="image\math2" alt="image-20220911164831642" style="zoom:80%;" />
  
* 有效性：方差越小越有效

### 假设检验

* $H_0$ 弃真，$H_1$ 纳伪。$H_0$ 要带等号。

* <img src="image\math3" alt="image-20220911165129041" style="zoom:80%;" />

  <img src="image\math4" alt="image-20220911165215285" style="zoom:80%;" />
