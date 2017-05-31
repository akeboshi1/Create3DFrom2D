#create3Dfrom2D

https://my.oschina.net/gonnavis/blog/912116

逛 TypeScript 官网时发现了一个 js canvas 做的 3D 灯光渲染效果，一看源代码，竟然是用 getContext("2d") 做的，而且代码并不长，才两百多行，当时就被震惊了！！！区区这点代码就能白手起家写出三维渲染效果？！WTF！还有这种操作？！感觉这一定是涉及非常基础、核心的 3D 相关原理的代码。虽然之前用过很多 3D 软件，也学过一点 Direct3D 和 WebGL，但是对 3D 基础知识始终是一知半解的，向量、矩阵变换等计算也不是太清楚，于是立即决定深入研究一下。
