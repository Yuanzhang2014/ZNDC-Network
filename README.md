# ZNDC-Network
Codes and dataset for the article Yuan Zhang, Yuanqing Xia, Yufeng Zhan, and Zhongqi Sun, Zero-norm distance to controllability of linear dynamic networks, arxiv 2209.02212. 

The dataset collects several typical uncontrollable networks arising in multi-agent systems, including complete graphs, symmetric graphs, paths/lines, circles, and so on. For a network ${\cal G}=(V,E)$, its dynamics is characterized by $\dot x(t)=Ax(t)+Bu(t)$, with the corresponding state matrix $A$ satisfying $A_{ij}\ne 0$ only if the edge $(j,i)\in E$ ($i\ne j$, $i,j\in V$). Each column of $B$ in (\ref{StateSpace}) corresponds to an input/actuator node.

Codes for the greedy algorithm (Algorithm 1) and sequence convex optimization based algorithm (Algorithm 2) to find the minimum number of parameters to be perturbed to achieve controlllability are also provided. 
