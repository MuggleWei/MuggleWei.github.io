---
title: "函数概念的演化"
date: 2022-01-18T00:14:02+08:00
draft: true
tags: ["数学", "数学史", "感悟"]
categories: ["数学"]
series: []
---

**集合**  
具有某种特性的事物的整体，或是一些确认对象的汇集  
* 构成集合的事物或对象称作元素  
* 集合具有**无序性**，**互异性** 和 **确定性**  

**映射**  
\\(X\\)，\\(Y\\)是两个给定的集合，若按照某种规则\\(f\\)，使得对集合\\(X\\)中的每一个元素\\(x\\)，都可以找到集合\\(Y\\)中唯一确定的元素\\(y\\)与之对应，则称\\(f\\)是集合\\(X\\)到集合\\(Y\\)的一个映射，记为:  
$$
\begin{aligned}
f: &X \rightarrow Y \newline
&x \mapsto y=f(x)
\end{aligned}
$$
* \\(y\\)称为映射f之下\\(x\\)的像
* 集合\\(X\\)称为映射\\(f\\)的定义域  
* 在映射\\(f\\)之下，\\(X\\)中元素\\(x\\)的像\\(y\\)的全体称为映射的值域

**函数**  
当\\(X\\)和\\(Y\\)是非空的数集，则映射\\(f: X \rightarrow Y \\)称为函数

---

&emsp;&emsp;上面的几个数学定义是高中初始阶段就需要学习的基本概念，一般先给学生们介绍集合及集合间的的关系，接着便是映射和函数，印象中这是十分自然的事情。然而回顾历史，**函数**这个词最早是由[莱布尼茨](https://zh.wikipedia.org/wiki/%E6%88%88%E7%89%B9%E5%BC%97%E9%87%8C%E5%BE%B7%C2%B7%E8%8E%B1%E5%B8%83%E5%B0%BC%E8%8C%A8)于1673年提出[^1]，而集合论则要等到200多年后的1874年，[康托尔](https://zh.wikipedia.org/wiki/%E6%A0%BC%E5%A5%A5%E5%B0%94%E6%A0%BC%C2%B7%E5%BA%B7%E6%89%98%E5%B0%94)发表论文"关于所有实代数数集的一个性质"[^2]才正式出现。  
&emsp;&emsp;那么在集合论出现之前的函数定义是什么样子的？ 函数是如何一步一步的发展成现在的定义的呢？  

## 函数概念的演化
&emsp;&emsp;函数的定义并非一蹴而就，由某位天才灵感一现而发明，而是随着人类在各种不同学科的发展下，在实践中提出概念，逐步升级，愈发严谨精确的一个过程。  

### 模糊的概念
&emsp;&emsp;历史上，有许多数学家，物理学家，天文学家等都用到了与现代函数类似的概念，只不过没有明确的给出一个定义。  
&emsp;&emsp;在1638年[伽利略](https://zh.wikipedia.org/wiki/%E4%BC%BD%E5%88%A9%E7%95%A5%C2%B7%E4%BC%BD%E5%88%A9%E8%8E%B1)研究同心圆的问题，有两个圆A和B，大圆A的周长是小圆B的两倍，在圆A上任取一点P，过OP做B的割线, 从而将A与B上的每个点对应了起来；同理在B上取一点Q, 用OQ及延长线来割圆A，也可以明确找到A上对应的点。虽然圆A的周长是圆B的两倍，但他们有相同数量的点。伽利略还发现了在正整数和其平方之间标准的一一对应的关系， 这(用现代术语来说)给出了自然数集合N与其真子集的双射。[^1]  

&emsp;&emsp;几乎与此同时，1637年[笛卡尔](https://zh.wikipedia.org/wiki/%E5%8B%92%E5%86%85%C2%B7%E7%AC%9B%E5%8D%A1%E5%B0%94)在《几何学》中将代数引入了几何学当中。书中提到[^3]:  
 >这些曲线上的所有的点，必定跟直线上的所有的点具有一种确定的关系，而且这种关系必须用单个的方程来表示。  
 >...  
 >用这种方法，我们总能找到足以决定曲线上所有点的一个方程  

&emsp;&emsp;这实质上是在构造曲线的过程中引入了函数的思想，只是当时尚未意识到需要提炼出明确的概念定义。  

&emsp;&emsp;到了1673年, 莱布尼茨在一封信中使用了**函数**这个词，来表示随曲线变化而改变的量, 例如曲线上一点的坐标，曲线的斜率等[^1][^4]。


### 明确的定义
&emsp;&emsp;1694年9月2日，[约翰.伯努利](https://zh.wikipedia.org/wiki/%E7%B4%84%E7%BF%B0%C2%B7%E7%99%BD%E5%8A%AA%E5%88%A9)在写给**莱布尼茨**的信中，这样描述函数[^1]:  
>由变量和常量以某种方式组合形成的另一个量  

&emsp;&emsp;1698年, **约翰.伯努利**在一篇关于等周长的论文中写下了"坐标函数"[^5]，当时**约翰.伯努利**正在研究变分法问题，函数作为解决方案出现。到1718年，他将函数描述为[^6]:  
>任何由变量和一些常量组成的表达式  

&emsp;&emsp;至此，**约翰.伯努利**对函数进行了明确的定义: ***把变量x和常量按任何方式构成的量叫做"x的函数", 表示为\\(y_x\\)***。

### 逐步演化
&emsp;&emsp;时间来到1748年，[欧拉](https://zh.wikipedia.org/wiki/%E8%90%8A%E6%98%82%E5%93%88%E5%BE%B7%C2%B7%E6%AD%90%E6%8B%89)的《无穷分析引论》出版，本书中欧拉给出函数的定义[^7]:  
>一个变量的函数是由变量和数字或常量以任何方式组成的解析表达式  

&emsp;&emsp;但是欧拉在书中并未给出解析表达式的明确定义，但基本可理解为通常的四则运算，平方，开方等。欧拉进一步将函数分为不同的类型，如代数函数和超越函数。这本书的意义是非凡的，改变了数学家们看待一些熟悉概念的方式[^1]:  
>在欧拉之前，三角量正弦、余弦、正切等被认为是与圆相连的线，而不是函数。  
>...  
>是欧拉提出了泛函的观点。   

## 引用
[^1]: O'Connor, John J.; Robertson, Edmund F., ["The function concept"](https://mathshistory.st-andrews.ac.uk/HistTopics/Functions/), MacTutor History of Mathematics archive, University of St Andrews
[^2]: Cantor, Georg (1874), "Ueber eine Eigenschaft des Inbegriffes aller reellen algebraischen Zahlen", Journal für die reine und angewandte Mathematik (in German), 1874 (77): 258–262, doi:10.1515/crll.1874.77.258, S2CID 199545885
[^3]: 笛卡尔 (2008), "笛卡儿几何", ISBN 9787301095508
[^4]: Eves dates Leibniz's first use to the year 1694 and also similarly relates the usage to "as a term to denote any quantity connected with a curve, such as the coordinates of a point on the curve, the slope of the curve, and so on"[Eves, Howard (1990). Foundations and Fundamental Concepts of Mathematics (3rd ed.). Dover. ISBN 0-486-69609-X, p. 234]
[^5]: A P Youschkevitch, The concept of function up to the middle of the 19th century, Arch. History Exact Sci. 16 (1) (1976/77), 37-85
[^6]: Eves, Howard (1990). Foundations and Fundamental Concepts of Mathematics (3rd ed.). Dover. ISBN 0-486-69609-X. p. 234
[^7]: 欧拉 (2019), "无穷分析引论"，ISBN 9787560364445
