# 数理逻辑基础 2026 期末考试回忆版

edited by *cnszlijz*

第一题、第三题相比原题目有较多缺失部分。

第五题、第六题相对原题目有一些改动，因为不记得原题了。

第四题可能相对原题目有一些改动。

有一些不会写的符号使用了替代写法。

题目不一定代表考试时真实题目，仅供参考。

## 一、判断题

- 重言式是命题演算中所有推理逻辑的体现（？）
- 其它题忘了

## 二、使用直接证明和间接证明证明以下命题演算

$$
|-p\rightarrow(q\rightarrow\neg(p\rightarrow\neg q))
$$

## 三、A,B,C,D,E五个人参加两个科研项目，有以下几个限制条件，请通过等值变换法或主范式法找出哪些人参加哪些项目

1. 每人要么参加项目 1 要么参加项目 2

2. B 参加项目 2，当且仅当 C 和 D 有一个参加项目 2

3. 忘了

## 四、证明以下谓词演算

1. 设 x 不在 p 中自由出现

$$
|-\forall x(q\rightarrow r)\rightarrow ((p\rightarrow \exist xq)\rightarrow(p\rightarrow \exist xr))
$$

2. 设 x 不在 r,s 中自由出现

$$
\{\forall x\exist y(p(x)\rightarrow q(x,y)),\forall x\forall y(q(x,y)\rightarrow r(y)),\forall y(r(y)\rightarrow s)\}|-\exist xp\rightarrow s
$$

## 五、将下述式子化为前束范式，写出过程和结果

$$
\neg\forall x_1(\forall x_2(R_1^2(x_1,x_2)∧ \forall x_3 R_2^2(x_2,x_3))\rightarrow R_1^1(x_2))\rightarrow \forall x_1R_2^1(x_1)\\
(?)
$$

## 六、

在一个游戏中，每个在地图上的村庄要么在草原上，要么在雪原上，要么在其他地方；每个在地图上且在草原上的村庄一定有制图师小屋；每个在地图上且在雪原上的村庄一定有标记；每个在其它地方且没有标记的村庄一定没有制图师小屋；地图上存在没有标记且有制图师小屋的村庄。求证：地图上存在在草原上的村庄。
