
Assignment2
==========

**参考研报：**<br>
20120510-光大证券-技术指标系列(五)：CCI的顺势而为

**1. 回测数据来源**<br>
万得 Wind

**2. 回测样本**<br>
沪深300指数数据（2005-01-01至2023-03-17）

**3. 策略**<br>
顺势指标CCI由唐纳德拉姆伯特所创，是通过测量股价的波动是否已超出其正
常范围，来预测股价变化趋势的技术分析指标。 
由于选用的计算周期不同，顺势指标CCI也包括日CCI指标、周CCI指标、年CCI
指标以及分钟CCI指标等很多种类型。经常被用于股市研判的是日CCI指标和周
CCI指标。<br>

CCI 指标没有运行区域的限制，在正无穷和负无穷之间变化，但是，和所有其
它没有运行区域限制的指标不一样的是，它有一个相对的技术参照区域：+100
和-100。按照指标分析的常用思路，CCI 指标的运行区间也分为三类：+100 以
上为超买区，-100 以下为超卖区，+100 到-100 之间为震荡区。 

**4. 策略信号**<br>
上穿 100 买，下穿-100 卖
参数分别为 n = 20 和 n = 27
计算策略信号并赋值给持仓，并计算持仓

**4. 计算指标并进行回测**<br>
**计算以下指标变化情况：**<br>
持仓收益<br>
持仓胜负<br>
累计持仓收益<br>
回撤<br>
超额收益

**并输出结果：**<br>
累计收益 <br>
多仓次数 <br>
多仓胜率<br>
多仓平均持有期<br>
空仓次数<br>
空仓胜率<br>
空仓平均持有期<br>
日胜率<br>
最大回撤<br>
年化收益/最大回撤<br>
年化收益<br>
年化标准差<br>
年化夏普 

**5. 多种情况的结果**(红色为沪深三百，蓝色为CCI策略）

A:研报原时间段（2005-09-01至2012-09-01） N=20
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/A1.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/A2.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/A3.png)

B:研报原时间段（2005-09-01至2012-09-01） N=27
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/B1.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/B2.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/B3.png)

C:研报后至今（2012-09-01至2023-03-17） N=20
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/C1.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/C2.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/C3.png)

D:全局（2005-01至今） N=20
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/D1.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/D2.png)
![image](https://github.com/algo23-Shuairui/Assignment1/blob/main/IMG/D3.png)



