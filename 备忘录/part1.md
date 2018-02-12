# Part 1

为了描述四个州的能源状况，首先我们需要定义一个描述能源整体状况的的指标。能源由于与经济、环境关系密切，因而，经济和环境在我们考虑能源状况时变得不容忽视

所以我们研究了论文【《能源-经济-环境（3E）系统协调度评价模型研究》】，并综合考虑。对于能源方面，我们采用能源总消耗量和清洁能源消耗占所有能源消耗的比例；对于经济方面，我们采用各个州的GDP以及各个州的人均GDP；对于环境方面，我们采用二氧化碳排放量和温度两种数据。最终这些数据被整合表示我们清洁能源状况的指标。
对于各方面里两种数据的权重，我们采用主成分分析法和层次分析法结合的方法综合确定，这样既可以表达决策者的主观意愿，又避免了主观意愿和实际情况的偏差，同时充分利用原始数据的信息。基于经验，我们设主观权重和客观权重具同等重要，则每种指标权重为

Wti=0.5Wsi+0.5Woi(小写为下标）

To describe the energy situation of the four states, first, we need to define an indicator that describes the overall condition of energy.Energy is closely related to the economy and the environment. therefore, the impact of economic and environment can not be ignored as we consider the condition of energy.
So we study the paper \cite{} and take it into consideration. For energy, we use total energy consumption and clean energy consumption as a proportion of total energy consumption; For economy, we use the GDP of each state and real GDP per capita of each state; For the environment, we use carbon dioxide emissions and temperature data. Finally, these data are integrated to represent our indicators of clean energy.

For the weight of the two kinds of data in all aspects, we use the method of principal component analysis and analytic hierarchy process to determine synthetically. This process can not only express the subjective will of policy makers, but also avoid the deviation of subjective wishes and the actual situation. In addtion, the original data can be fully utilized.Based on experience, we assume that subjective weights and objective weights are equally important, then the weight of each  indicator is

$ W_{ti} = 0.5 W_{si} + 0.5 W_{oi} $

首先我们对六种数据做标准化处理。我们采用极差法来进行标准化处理，公式如下

First, we standardize on the six kinds of data. The way We use to standardize is the range-method . Formulas are as follows:

For positive indicators,
<!-- 公式1 -->
$ Y_i = \frac{X_i - X_{min}}{X_{max} - X_{min}} $

For negative indicators,
<!-- 公式2 -->
$ Y_i = \frac{X_{max} - X_i}{X_{max} - X_{min}} $

所以最终能源、经济和环境各方面的计算公式如下

Therefore, the final calculation formula of energy, economy and environment is as follows.
<!-- 公式3 -->
$ E = \sum^{n}_{I=1} W_{ti} Y_{i} $

我们假定能源、经济与环境对我们的指标有同等的重要程度，因此公式为

We assume that energy, economy and environment are equally important to our indicators, so the formula is
<!-- 公式4 -->
$ E^{*} = \frac{E_e + E_c + E_v}{3} $

该指标越大，证明清洁能源状况越好。其中，由于二氧化碳排放量为正值，所以实际计算中要取反处理。

The larger this indicator, the better the clean energy condition. Among them, as the reason of that carbon dioxide emissions is positive, the actual calculation need to take the opposite treatment.

我们对各州1980-2009年的能源状况指标进行统计，做出不同州能源状况指标的的时间序列图

We make a statistical analysis of the energy status indicators of each state from 1980 to 2009, and make the figure of comprehensive energy status indicator time series in different states, as shown below.
<!-- 图    各州综合能源状况指标时间序列图 -->

我们可以看到，开始处由于经济的快速增长，指标不断增大。但由于二氧化碳排放量对环境因素影响，在1987年左右各州的指标开始减小。之后随着可持续发展的观念增强，各个州提出自己的新能源政策，指标开始增大。这里可以看到德克萨斯州和新墨西哥州由于大力发展新能源，它们的指标增大速度相对比较明显。
另外，由于各州有大量的数据会影响州间的异同，我们通过做出不同州的时间序列图，分别分析了四个州的可再生能源状况。

As we can see, the beginning of the rapid economic growth leads to the indicator increasing. However, due to the impact of carbon dioxide emissions on  environmental factors, the indicators of all states began to decrease around 1987. Then, with the concept of sustainable development strengthened, each state proposed its own new energy policy and the indicator began to increase. As we can see in Texas and New Mexico, because of their energetic efforts to develop new energy sources, their indicators were increasing at a relatively faster rate.
Moreover, since there is a large amount of data in each state that affects the similarities and differences between the states, we analyze the renewable energy condition in each of the four states by making time series diagram of different states.

AZ

我们对亚利桑那州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We plot the development trends of various renewable energy categories in Arizona over the past 50 years in \ref{}.
<!-- 图    亚利桑那州各类可再生能源时间序列图 -->

可以看到亚利桑那州水电能源发展较早，并且在所有可再生能源中占有相当高的比例，木材和废物品次之。其他的可再生能源基本在上世纪8、90年代开始发展，其中燃料乙醇和太阳能发展迅速，截止到2009年，燃料乙醇的消耗量超过木材和废物品，成为第二大消耗可再生能源。
分析亚利桑那州的地理和气候可以发现，亚利桑那州有充沛的太阳能资源，平均每年有300个晴天。但由于光伏能源成本长期较高，所以在经历了初期的快速增长后，增长速度逐渐变缓。目前光伏能源成本估计在0.15-0.25美元/千瓦时，并没有太好的发展。
【http://www1.eere.energy.gov/solar/myths.html】
而亚利桑那州的风能发展虽然缓慢，但是发展前景较好。因为Located near the eastern edge of Mogollon Rim, eastern Arizona and eastern Arizona are geographically superior and resource-rich. There are also good wind resources on the edges and ridges across the state.
【www.eere.energy.gov/windandhydro/windpoweringamerica/maps_template.asp?stateab=az】

As we can see, hydropower in Arizona is growing earlier and occupies a significant proportion of all renewable energy sources, followed by wood and waste products. Other renewable energy sources began to develop in the 1980s and 1990s. It is is notable that fuel ethanol and solar power are developing rapidly. By 2009, fuel ethanol consumption exceeded that of wood and waste, making it the second largest consumption of renewable energy.

An analysis of Arizona's geography and climate shows that Arizona has abundant solar energy resources, averaging 300 sunny days a year. However, due to the long-term high cost of photovoltaic energy, the growth rate has gradually slowed down after the initial rapid growth. The current cost of photovoltaic energy is estimated at 0.15-0.25 dollars / kWh, so the development is not satisfactory.

【http://www1.eere.energy.gov/solar/myths.html】

Although the wind energy in Arizona is developing slowly, its development prospects are good. Located near the eastern edge of Mogollon Rim, eastern Arizona and eastern Arizona are geographically superior and resource-rich. There are also good wind resources on the edges and ridges across the state

【www.eere.energy.gov/windandhydro/windpoweringamerica/maps_template.asp?stateab=az】

CA 

我们对加利福尼亚州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We plot the development trends of various renewable energy categories in California over the past 50 years in figure.\ref{}.

<!-- 图    CA州各类可再生能源时间序列图 -->

通过图表可以发现加利福尼亚州的可再生能源消耗总量巨大。各类可再生能源消耗与亚利桑那州类似，也是水电能源占所有可再生能源最高比例，然后是木材和废品。其他的的可再生能源也是从上个世纪80、90年代开始发展，其中燃料乙醇发展最为迅速。不同于其他能源的是加利福尼亚州的地热能发展较早，且消耗量较大。
分析加利福尼亚州的地理状况，可以看到加利福尼亚州州东部，尤其是东南端和东北端是一片沙漠，所以可能蕴含较多的地热能。另外由于人口数量众多，所以导致消耗的能源也非常多。

The figure shows that California's total renewable energy consumption is huge. All types of renewable energy consumption is similar to that in Arizona, where hydropower accounts for the highest share of all renewable energy sources, followed by wood and waste. Other renewable energy sources began to develop in the 1980s and 1990s. It is is notable that fuel ethanol is developing fastest. Unlike other sources of energy, California's geothermal energy has grown earlier and is consumed much more.

After analyzing the state of California, we can see it clear that the eastern part of California, especially the southern tip and the northeast end is a desert, so there may be more geothermal energy. In addition, due to the large population, there are also many energy consumption.

NM

我们对新墨西哥州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We plot the development trends of various renewable energy categories in New Mexico over the past 50 years in figure.\ref{}.

<!-- 图    新墨西哥州各类可再生能源时间序列图 -->

可以看到该州的总可再生能源消耗较少，2005年以前可再生能源中消耗所占比例最大的是木材和废品。风能在2005年以后发展迅速，一跃成为最大消耗可再生能源。

As we can see, the state's total renewable energy consumption is less. By 2005, the largest share of renewable energy was wood and waste. Wind energy has grown rapidly since 2005, making it the biggest consumption of renewable energy.

TX

我们对德克萨斯州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示
We plot the development trends of various renewable energy categories in Texas over the past 50 years in figure.\ref{}.

<!-- 图    德克萨斯州各类可再生能源时间序列图 -->

可以看到该州的可再生能源总量消耗较少，2005年以前可再生能源中消耗所占比例最大的是木材和废品。风能在2005年以后发展迅速，一跃成为最大消耗可再生能源。 
可以看到在风能和木材和废品使用的情况上，德克萨斯州与新墨西哥非常相似。
分析德克萨斯州的数据发现，目前德克萨斯州是美国风能发电量最大的州，而且该数值还在不断增长，这得益于该州制定的renewables portfolio standard (RPS)，RPS迫使电力供应商大规模并积极主动地使用风能和其它可再生能源发电
【The renewables portfolio standard in Texas: an early assessment】

It can be seen that Texas is very much like New Mexico in the use of wind energy and wood and waste.After analysis of Texas data, we find that at present Texas is the largest state in the United States with the highest wind energy generation. What supers us is taht the wind energy consumptiion has been increased so fast in past ten years. The paper \cite{} shows that the reason is the state's renewables portfolio standard (RPS), which forces RPS Power suppliers proactively use large-scale wind and other renewable energy to generate electricity.

【The renewables portfolio standard in Texas: an early assessment】


总结

对上面所有图表进行比较可以发现，亚利桑那州和加利福尼亚州较为相似，而新墨西哥州和德克萨斯州较为相似。亚利桑那州和加利福尼亚的可再生能源中，水电能源占有很大比例；新墨西哥州和德克萨斯州的可再生能源中，风能占有很大比例。由于不同州的地理和气候等因素不同，亚利桑那主要发展太阳能，加利福尼亚州主要发展地热能，新墨西哥州和德克萨斯州主要发展风能。另外每个州的的燃料乙醇能源都有一定的发展。

summary

A comparison of all the figures above shows that Arizona and California are similar, while new Mexico and Texas are similar. Renewable energy sources in Arizona and California account for a large proportion of renewable energy. Wind energy in New Mexico and Texas accounts for a large proportion of renewable energy. As the result of the difference between different states in geography and climate, Arizona mainly develops solar energy while California, imainly developing geothermal energy,  New Mexico and Texas mainly developing wind energy.In addition, each state's fuel ethanol energy has a certain development.


# part 1 C

# 灰度关联分析

## 简介

灰色系统理论提出了对各子系统进行灰色关联度分析的概念，意图透过一定的方法，去寻求系统中各子系统（或因素）之间的数值关系。因此，灰色关联度分析对于一个系统发展变化态势提供了量化的度量，非常适合动态历程分析。

Gray system theory puts forward the concept of analyzing the gray relational degree of each subsystem. It intends to seek the numerical relationship among the subsystems (or factors) in the system through certain methods.
Therefore, gray relational analysis provides a quantitative measure of a system development trend and is very suitable for dynamic history analysis.
【https://baike.baidu.com/item/%E7%81%B0%E8%89%B2%E5%85%B3%E8%81%94%E5%88%86%E6%9E%90%E6%B3%95/8602076?fr=aladdin】

## 计算步骤

确定反映系统行为特征的参考数列和影响系统行为的比较数列。
反映系统行为特征的数据数列，称为参考数列。影响系统行为的因素组成的数据数列，称比较数列。

Identify reference sequences that reflect system behavior characteristics and comparison sequences that affect system behavior.
The sequence of data that reflects the behavior of the system is called the reference sequence. Factors affecting the behavior of the system composed of data series, is called the comparison sequence.

获得参考数列和比较数列以后，要对参考数列和比较数列进行无量纲化处理。
由于系统中各因素的物理意义不同，导致数据的量纲也不一定相同，不便于比较，或在比较时难以得到正确的结论。因此在进行灰色关联度分析时，一般都要进行无量纲化的数据处理。

After obtaining the reference sequence and the comparison sequence, the reference sequence and the comparison sequences should be treated dimensionless.
Due to the different physical meaning of each factor in the system, the dimensionality of the data is not necessarily the same, which is not convenient for comparison, or it is difficult to get the correct conclusion in comparison. Therefore, in the analysis of grey relational degree, it is generally necessary to conduct dimensionless data processing.

选取参考数列
$ x_0 = \{x_0(k) | k=1,2,\cdots,n \} = (x_0(1), x_0(2), \cdots, x_0(n))$ 

Select reference sequence
$ x_0 = \{x_0(k) | k=1,2,\cdots,n \} = (x_0(1), x_0(2), \cdots, x_0(n))$ 


假设有m个比较数列
$ x_i = \{x_i(k) | k=1,2,\cdots,n\} = (x_i(1), x_i(2), \cdots, x_i(n)), i = 1,2,\cdots,m $ 
其中k表示时刻，总共有n个时刻。

Suppose there are m number of comparisons
$ x_i = \{x_i(k) | k=1,2,\cdots,n\} = (x_i(1), x_i(2), \cdots, x_i(n)), i = 1,2,\cdots,m $ 
Where k represents the moment, a total of n moments.

在计算关联系数前，先对比较数列进行无量纲化处理。常见的无量纲化方法有均值化法和初始化法。
我们采用的是初始化法：

$ x_i(k) = \frac{x_i'(k)}{\frac{1}{m} \sum\limits_{k=1}^m x'i(k)}  i = 0,1,\cdots,k $
这里 $x_i'(k)$ 表示刚筛选出的比较数列。 $x_i(k)$ 是处理后的新比较数列。

Before calculating the correlation coefficient, the comparison sequence need to be treated dimensionless. The common dimensionless methods are average method and initialization method.
What we use is the initialization method.
Here $ x_i '(k) $ indicates the comparison sequence just screened. $ x_i (k) $ is the new processed comparison sequence.

之后可以计算出参考数列与比较数列的灰色关联系数$r_i(k)$, 所谓关联系数，实质上是曲线间几何形状的差别程度。因此曲线间差值大小，可作为关联程度的衡量尺度。对于一个参考数列 $x_0$ 有若干个比较数列$x_1, x_2, \cdots, x_m$，各比较数列与参考数列在各个时刻（即曲线中的各点）的关联系数$r_i(k)$可由下列公式算出：其中 ρ为分辨系数，一般在0~1之间，通常取0.5。

After that, the gray correlation coefficient $r_i(k)$ between the reference sequence and the comparison sequence can be calculated.
The so-called correlation coefficient, is substantially between degree of difference curve geometry. Therefore, the size of the difference between the curves can be used as a measure of the degree of association
For a reference sequence $ x_0 $, there are several comparison sequences $ x_1, x_2, \ cdots, x_m $. The correlation coefficient $ r_i (k) $ of each comparison sequence and the reference sequence at each moment (ie, points in the curve) can be calculated by following formula: Where $\rho$ is the resolution coefficient, generally between 0 to 1, usually take 0.5.


$ r_i(k) = \frac{\min\limits_{i} \min\limits_{k}| x_0(k) - x_i(k)| + \rho \times \min\limits_{i} \min\limits_{k}| x_0(k) - x_i(k)|}{|x_0(k) - x_i(k)| + \rho \times \min\limits_{i} \min\limits_{k}| x_0(k) - x_i(k)|} $
$ k = 1,2,\cdots, k $


该式子中 $\min\limits_{i} \min\limits_{k}| x_0(k) - x_i(k)|, \max\limits_{i} \max\limits_{k}| x_0(k) - x_i(k)|$ 分别为两级最小差及两级最大差。
式中$\rho$ 为分辨系数, 一般在(0, 1)内取值，若 $\rho$越小，关联系数间的差异就越大，区分能力就越强。通常取0.5。

In the formula, $ \ min \ limits_ {i} \ min \ limits_ {k} | x_0 (k) - x_i (k) |, max \ limits_ {i} \ max \ limits_ {k} - x_i (k) | $ are the minimum difference between the two levels and the maximum difference between the two levels.
Where $ \ rho $ is the resolution coefficient, which is usually taken as (0, 1). The smaller the $ \ rho $, the greater the difference between the correlation coefficients and the stronger the ability to distinguish. Usually take 0.5.

式中定义的关联系数是描述比较数列与参考数列在某时刻关联程度的一种指标，由于各个时刻都有一个关联数，因此信息比较分散导致不便于比较，为此我们给出公式计算比较数列与参考数列的关联度

The correlation coefficients defined in the formula describe an indicator of the correlation degree between the comparison sequence and the reference sequence at a certain time. Since there is an association number at each moment, the information is more scattered and it is not convenient to compare. Therefore, we give the formula to calculate the correlation between the comparison sequence and the reference sequence:

$ r_i = \frac{1}{n}\sum\limits_{k=1}^{n}r_i(k) $

根据该式计算出各个比较数列的关联度并排序。

According to the formula to calculate the relevance of each comparison series and sort.

[https://www.jianshu.com/p/4ceb9a516890?from=timeline]
[https://wenku.baidu.com/view/73609ecff12d2af90342e65a.html]


为了方便后面问题的进一步处理，我们先使用灰度关联分析，将所有的州选取相同的关联指标。首先我们选取了其中5个在所有州中都出现了的指标，然后将每个州的得到的十个主要影响指标赋予权值，根据与综合评价指标的关联度从大到小进行排序，我们从中挑选了除了上述5个指标以外最大的三个指标。所以最后我们决定采用以下8个指标:

PAPRB  NAMPB  NNTCB  FFTCB  TETCB  PATCB  HTCB  WWTCB

In order to facilitate the further processing of the following problems, we use gray relational analysis, selecting the same relevant indicators for each state here.
First of all, we select five indicators that appear in all the states, and then assign the weights of the ten main influence indicators in each state, and sort them according to their relevance to the comprehensive evaluation indicators. We pick the largest of the three indicators other than the five mentioned above. So in the end we decide to adopt the following eight indicators:

PAPRB  NAMPB  NNTCB  FFTCB  TETCB  PATCB  HTCB  WWTCB

然后我们对四个州的指标使用了Topsis法进行了评价，其原理为【DPS数据处理系统——实验设计、统计分析及模型优化】。
设有n个评价对象、m个评价指标，原始数据可以写成为矩阵

Then we evaluated the indicators of the four states using the Topsis method, which is based on the principle【DPS数据处理系统——实验设计、统计分析及模型优化】.

There are n evaluation objects, m evaluation indicators. The original data can be written as a matrix:

$ \mathbf{X} = (X_{ij})_{nm} $.
    
对高优、低优指标分别进行归一化变换，即

The high-quality, low-quality indicators are normalized transformation, that is

$ Z_{ij} = \frac{X_{ij}}{\sqrt{\sum\limits_{i=1}^{n}X_{ij}^2}} $.
    
归一化得到矩阵，

After normalizing, weget the matrix

$ \mathbf{Z} = (Z_{ij})_{nm} $.

其各列最大、最小值构成的最优、最差向量分别记为：

The maximum and minimum of each column constitute the best and worst vector respectively as:

$ \mathbf{Z^+} = (Z_{max1}, Z_{max2}, \cdots, Z_{maxm})$,
$ \mathbf{Z^-} = (Z_{min1}, Z_{min2}, \cdots, Z_{minm})$.

第i个评价对象与与最优、最差方案的距离分别为：

The distance between the i-th evaluation object and the optimal scheme and the worst scheme is as follows:

$ D_i^+ = \sqrt{ \sum\limits_{j=1}^m (Z_{maxj} - Z_{ij})^2 } $,
$ D_i^- = \sqrt{ \sum\limits_{j=1}^m (Z_{minj} - Z_{ij})^2 } $.


第i个评价对象与最优方案的接近程度Ci为：

The approximate degree of the i-th evaluation object and the optimal scheme is $Ci$:

$ C_i = D_i^- / (D_i^+ + D_i^-) $.
    
这里我们使用了DPS工具进行了处理，最后的结果为

Here we use the DPS tool for processing, and the final result is as follows.
    
<!-- 表  各州Topsis评价的结果 -->

如表所示,也就是说通过我们的评判标准，我们得出德克赛斯州是清洁能源状况最好的州。

As the table shows, by our standards, we conclude that Texas is the best state for clean energy.

## D


关于预测2025年和2050年的能源配置问题，我们主要考虑了总体能源评价、能源生产和消耗的差值两种指标来描述。
能源生产和消耗的差值为

In terms of forecasting energy profile in 2025 and 2050, we mainly consider overall energy assessment, and the difference value between energy production and consumption.

The difference between energy production and consumption is

$ S = PR - PC $

其中PR为能源生产，PC为能源消耗。该值代表该州该能源的富余程度，值大于0说明该州能源生产值大于消耗值，可以向其他州出口能源；值小于0说明该州能源消耗量大于生产量，需要从其他州进口能源。

where PR is energy production and PC is energy consumption. This value represents the level of the state's surplus of energy, the value greater than zero indicates that the state's energy production value is greater than the consumption value, and the state can export energy to other states. Value less than zero indicates that the state energy consumption is greater than the production, and the state need to import energy from other states.

关于预测模型，我们采用灰色预测模型

For the prediction model, we use the gray prediction model.

## 灰色预测
