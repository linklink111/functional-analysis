# functional-analysis
functional-analysis

赋范空间最简单的例子是一维空间 X=K ，其中$||x|| =|x|$.空间 C(T)，C_0(T)，C_e(T)设 T 是距离空间.用 C(T)来表示 T上所有有界连续的K 值函数.它是关于逐点定义的加法和数乘运算的线性空间.

x = sup{| x(t) | : x \in T}, x \in C(T) 
定义了C(T)上的范数，它被称为上确界范数.

C_0(T)是所有x \in C(T)有如下特性元素的集合：对每个\epsilon>0，都有一个依赖于x 和 \epsilon 的T的紧子集S，使得| x(t)| <\epsilon，对所有 t \not \in S.所有x \in C(T)有以下特性元素的集合用C_e(T)来表示:存在依赖于x的T的紧子集S，使得对所有t \not \in S，x(t)=0. 空间C_0(T)和 C_e(T)都是C(T)的子空间.

设T是赋有离散距离的自然数集，则C(T)是K中所有有界序列{x(n)}的集合.这个空间用l^{infty} 来表示，它的范数是

||x||_{infty} = sup_{n \geq 1} |x(n)|, x \in l^{infty}
