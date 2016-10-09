# **Exercise 04**
## *作业要求*
- 尝试用Python画图
- 编写一个python程序，求解两个粒子的衰变问题

## *摘要*
 - 使用Python来设计程序。
 - 运用数值方法计算A、N的值，并改变初始条件，观察稳定时A、B的状况
 - 将数值方法所得的结果与解方程的精确结果进行比较，测试程序的优缺之处
 - 本文论述了这些问题的想法，程序，和结果。

## *介绍*
 - Problem 1.5 
 Consider again a decay problem with two types of nuclei A and B, but now suppose that nuclei of type A decay into ones of type B, while nucleiof type B decay into ones of type A. Strictly speaking, this is not a "decay" process, since it is possible for the type B nuclei to turn back into type A nuclei. A better analogy would be a reasonance in which a system can tunnel or move back and forth between two states A and B which have equal energies. The corresponding rate equations are                        $\frac{dN_A}{dt} = \frac{N_B}{\tau} - \frac{N_A}{\tau}$ 

    $\frac{dN_B}{dt} = \frac{N_A}{\tau} - \frac{N_B}{\tau}$
where for simplicity we have assumed that the two types of decay are characterized by the same time constant  $\tau $ .Solve this system of equations for the numbers of nuclei,${N}_A$ and ${N}_B$ ,as functions of time .Consider different initial conditions, such as ${N}_A$=100,${N}_B$=0 etc., and take $\tau $=1s.Show that your numerical results are consistent with the idea that the system reaches a steady state which ${N}_A$ and ${N}_B$ are constant.In such a steady state, the time derivatives$\frac{\mathrm{d} {N}_A}{\mathrm{d} t}$ and $\frac{\mathrm{d} {N}_B}{\mathrm{d} t}$should vanish.


### 程序
 - [Exercise 02 ](https://github.com/cat316874/computationalphysics_N2015335550054/blob/master/Exercise02.py)


### 结果
 - 图1:
 ![Exercise 02 ] (https://github.com/cat316874/computationalphysics_N2015335550054/blob/master/Exercise%2002.PNG)
 


---

## *结论*
 - 生涩的完成了作业，还是有很多不懂，需要通过练习加强。
 - 需要和大神多多交流长知识。
 - 在写作完成python程序后发现自己写的程序闪退，不能稳定存在，便在网上寻找答案，最终的解决方案是加了一行代码raw_input(），如此之后稳定运行。


## *致谢*
  - 非常感谢老师的悉心教导，不厌其烦的给我们讲基本概念与知识，老师辛苦了。同时由衷的感谢江俊和马士全以及张然同学，借鉴和模仿了很多他的内容，以他们为标榜.特别是张然大神教我如何插入公式，太完美了。最后安慰下自己，撞大运一样的完成了第4次作业。 
