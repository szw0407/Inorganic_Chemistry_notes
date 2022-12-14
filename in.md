# 化学期末复习整理

## 第一、二章：化学反应中的质量、能量、方向、速率、限度

本章大部分内容和高中选修部分的化学反应原理重复。下面列举提到的知识点，并在必要处补充部分高中未提到或简化的内容。

- 计量：物质的量、摩尔质量、摩尔体积、物质的量浓度、理想气体状态方程
- 物料守恒和相关计算
- 热力学：能量守恒；体系、状态、热和功。反应热和焓变、热化学方程式、Hess定律；标准状态（用上标
  $^\ominus$
  表示）、标准摩尔生成焓
- 反应方向：吉布斯自由能变、化学反应方向的判断
- 反应速率：活化分子和活化能、化学反应速率影响因素
- 反应限度：可逆反应、平衡常数、标准平衡常数、平衡移动的影响因素（Le Chatelier定理）

## 第三章：酸碱反应和沉淀反应

### 3.1 水的解离和溶液的酸碱性

$\rm K_w^\ominus$和
$\rm pH$。此部分略。

#### 酸碱指示剂

<b>常见的指示剂变色范围</b>

| 指示剂   | 甲基橙 | 石蕊 | 酚酞 |
| ---------- | -------- | ------ | ------ |
| 酸色     | 红色   | 红色 | 无色 |
| 变色范围 | 3.1    | 5.0  | 8.2  |
| 过渡色   | 橙色   | 紫色 | 粉红 |
| 变色范围 | 4.4    | 8.0  | 10.0 |
| 碱色     | 黄色   | 蓝色 | 红色 |

### 3.2 弱电解质的解离反应

#### 解离常数

$K_a^\ominus$：酸

$K_b^\ominus$：碱

$$\rm HA \rightleftharpoons H^++A^-$$

$$
K_i^\ominus =\frac{c(H^+)\cdot c(A^-)}{c(HA)}
$$

#### 解离度

$$
\alpha=\frac{解离部分的弱电解质浓度}{未解离前弱电解质浓度} \times 100\%
$$

$$
K_a^\ominus = \frac{\lbrace c(H^+)/c^\ominus\rbrace\lbrace c(A^-)/c^\ominus\rbrace}{c(HA)/c^\ominus}=\Big(\frac{\alpha^2}{1-\alpha}\Big)\frac{c}{c^\ominus}
$$

简化一下，当
$(c/c^\ominus)/K_i^\ominus\geqslant500$
，则
$1-\alpha\approx 1$
，上式可改写为

$$
K_i^\ominus\approx\left( \frac{c}{c^\ominus}\right)\alpha^2
$$

$$
\alpha\approx\sqrt{\frac{K_i^\ominus}{c/c^\ominus}}
$$

#### 弱酸弱碱的离子浓度计算

对于HA型弱酸，其
$K^\ominus_i>>K^\ominus_w$
且其解离度不很小，则水的解离可以忽略。

解离平衡时：

$$
\begin{matrix} & HA & \rightleftharpoons & H^+& + & A^- \\
平衡浓度（mol\cdot L^{-1}） & c-x & &x & &x \end{matrix}
$$

如果：
$(c/c^\ominus)/K^\ominus_a \geqslant 500 , x\leqslant, c-x\approx c$
则

$$
K^\ominus_a=\frac{x^2}{(c-x)}\approx x^2/c
$$

$$
c(H^+)=x\approx \sqrt{c\cdot K^\ominus_a}
$$

$$
pH=-lg\sqrt{\left( \frac{c}{c^\ominus} \right) K^\ominus_a}=\frac{1}{2}\left\lbrace pK^\ominus_a+p\left( \frac {c}{c^\ominus}\right) \right\rbrace
$$

类似可得，在BOH的弱碱溶液中：

$$
c(OH^-)\approx \sqrt{(c \cdot c^\ominus)K^\ominus_b}
$$

$$
pOH=\frac 1 2 \left\lbrace pK^\ominus_b+p\left(\frac c {c^\ominus} \right)\right\rbrace
$$

$$
pH=14-pOH=14-\frac 1 2 \left\lbrace pK^\ominus_b+p\left(\frac c {c^\ominus} \right)\right\rbrace
$$

#### 多元弱酸的分步解离

分部解离存在
$K^\ominus_{a(1)}$
远小于
$K^\ominus_{a(2)}$

结论：
多元弱酸酸性强弱主要取决于
$K^\ominus_{a(1)}$

两次解离方程式相加，可以计算得到：

$$
K_a=K_{a(1)}\cdot K_{a(2)}
$$

可以认为：
$c(H^+)\approx c(HA^-)$

可以通过调节溶液的酸度，调节阴离子的浓度。

除多元弱酸外，多元弱碱如
$Al(OH)_3$ 以及少数的盐如
$\rm HgCl_2$ 、
$Hg(CN)_2$ 等，在溶液中都是分布解离的的

#### 同离子效应

根据Le Chatelier定理，在弱电解质溶液中，加入含有相同离子的强电解质，使弱电解质解离度降低的作用，称为<b>同离子效应</b>。

#### 缓冲溶液

弱酸和弱酸盐、弱碱和弱碱盐等混合，以及多元弱酸组成的两种不同酸度的盐混合溶液，可以维持自身pH在一定范围内不变。这种具有保持pH相对稳定作用的溶液称为<b>缓冲溶液</b>。

缓冲溶液都含有两种物质，一种是能抵消酸的物质，另一种是能抵消碱的物质。部分情况下如果只需要抵消
$H^+$ 或者
$OH^-$ 的一种，只需要对应加入弱酸或者弱碱盐作为缓冲剂。

### 3.3盐类水解

#### 水解反应和水解常数

一元强酸弱碱盐的水解常数：

$$
K^\ominus_h=\frac{K^\ominus_w}{K^\ominus_a}
$$

一元弱碱强酸盐的水解常数：

$$
K^\ominus_h=\frac{K^\ominus_w}{K^\ominus_b}
$$

一元弱酸弱碱盐的水解常数：

$$
K^\ominus_h=\frac{K^\ominus_w}{K^\ominus_a \cdot K^\ominus_b}
$$

盐类水解程度可以用<b>水解度</b>（h）衡量

$$
h=\rm \frac{盐水解部分的物质的量（或浓度）}{始态盐的物质的量（或浓度）}\times 100\%
$$

#### 分布水解

多元弱酸盐分布水解。和多元弱酸相似，分部解离是逐级减小的。由于
$K^\ominus_{h(2)} << K^\ominus_{h(1)}$，一般计算pH时只考虑第一次水解。

#### 水解的影响因素

- 盐类水解度大小主要取决于水解离子的本性。水解产物（弱酸或弱碱）越弱，水解度越大。
- 水解产物的难溶性和挥发性是增大水解度的重要因素之一。
- 根据平衡移动原理：一般，盐溶液浓度越小、温度越高，水解度越大；降低（或升高）pH可增大阴（阳）离子的水解度。

#### 水解的抑制和应用

1. 实验室内配置易水解的盐，加入对应的酸或碱抑制水解，避免产生碱式盐（如
$Sn(OH)Cl$ ）、酰基化物沉淀（如
$BiONO_3$ ）或者挥发性酸（如
$H_2S$）。
2. 在分析化学中，常利用盐类水解分离、鉴定、提纯物质。
3. 在生产中利用水解控制pH、提纯物质等。

### 3.4沉淀反应

#### 溶度积常数

$$K_{sp}^{\ominus}(A_mB_n)=\frac{\{c(A^{n+})\}^m\cdot\{c(B^{m-})\}^n}{(c^\ominus)^{m+n}}$$

#### 溶解度和溶度积的换算

对于AB型难溶性强电解质，计算：
$$c(A)\cdot c(B)=K^\ominus_{sp}(AB)(c^\ominus)^2$$

数值上满足：

$$s=\sqrt{K^\ominus_{sp}}\times c^\ominus$$

同理推得
$AB_2$ 型难溶性电解质溶度积和溶解度的关系：

$$s=\sqrt[3]{\frac{K^\ominus_{sp}}{4}}\times c^\ominus$$

#### 溶度积规则

根据吉布斯自由能变的判断依据：

$$\Delta_rG_m\left \lbrace \begin{array}{r}<\\=\\>\end{array} \right \rbrace 0 \left \lbrace\begin{array}{l}反应正向进行\\反应处于平衡状态\\反应逆向进行\end{array} \right .$$

<b>溶度积规则</b>：

对于以下反应

$$A_mB_n(s)\rightleftharpoons mA^{n+}+bB^{m-}$$

$$J=\{c(A^{n+})\}^m\cdot \{c(B^{m-})\}^n/(c^\ominus)^{(m+n)}$$

$$J\left \lbrace \begin{array}{r}< \\ =\\ >\end{array}\right \rbrace 0 \left \lbrace\begin{array}{l}沉淀溶解或不产生沉淀 \\ 饱和溶液，平衡态 \\ 生成沉淀\end{array} \right .$$

#### 影响沉淀反应的因素

#### 分布沉淀

#### 沉淀溶解

#### 沉淀转化

#### 沉淀应用

##### 制备难溶化合物

##### 除杂

##### 离子鉴定

##### 离子分离

## 第四章：氧化还原反应和应用电化学

### 4.1 氧化还原反应方程式配平

### 4.2 电极电势

#### 原电池的概念



### 4.3 氧化还原反应的方向和限度

### 4.4 电势图及其应用

电极电势

### 4.5 实用电池

### 4.6 电解

### 4.7 电镀

### 4.8 金属腐蚀和防腐

## 第五章：原子结构和元素周期性

### 5.1 原子和元素

### 5.2 原子轨道的近代概念

### 5.3 原子中电子的的分布

### 5.4 原子性质和周期性

## 第六章：分子结构和性质

### 6.1 键参数

### 6.2 价键理论

### 6.3 分子的几何构型

### 6.4 分子轨道理论
