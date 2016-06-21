# RotorAS-2D



RotorAS-2D (all speed) ，版本号：1.2.3。

包含以下功能：

1. 前处理——结构网格生成、非结构网格生成以及混合网格生成；

   结构网格：代数法法向推进，泊松方程光顺；非结构网格：阵面推进法。

2. 求解器——基于密度，可用于全速域流场求解计算；

   空间离散：JST格式、Roe格式；时间离散：统一采用双时间步法，隐式推进；离散方程组求解方法：LU-SGS。

   湍流模型：SA 和 k-omg SST。

   不可压缩计算采用预处理技术，动态计算采用动网格技术。

3. 后处理——压力分布和力（矩）系数或者迟滞回线计算；

链接：http://cfder.club/
