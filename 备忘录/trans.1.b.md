# Part 1

为了描述四个州的能源状况，首先我们通过自己定义一个描述能源整体状况的的指标。能源由于与经济、环境关系密切，当我们考虑能源时，同时加入经济和环境的影响因素。

所以我们研究了论文【《能源-经济-环境（3E）系统协调度评价模型研究》】，并综合考虑。对于能源方面，我们采用能源总消耗量和清洁能源消耗占所有能源消耗的比例；对于经济方面，我们采用各个州的GDP以及各个州的人均GDP；对于环境方面，我们采用二氧化碳排放量和温度两种数据。最终这些数据被整合表示我们的指标清洁能源状况。
对于各方面里两种数据的权重，我们采用主成分分析法和层次分析法结合的方法综合确定，这样既可以表达决策者的主观意愿，又避免了主观意愿和实际情况的偏差，同时充分利用原始数据的信息。基于经验，我们设主观权重和客观权重具同等重要，则每种指标权重为

Wti=0.5Wsi+0.5Woi(小写为下标）

To describe the energy situation of the four states, we first define an indicator that describes the overall state of energy.
Energy is closely related to the economy and the environment, and when we consider energy, we add economic and environmental factors.
So we study the paper[] and took it into consideration. For energy, we use total energy consumption and clean energy consumption as a proportion of all energy consumption; For the economy, we use the GDP of each state and the per capita GDP of each state; For the environment, we use carbon dioxide emissions and temperature data. Finally, these data are integrated to represent our indicators of clean energy.

For the weight of the two kinds of data in all aspects, we use the method of principal component analysis and analytic hierarchy process to determine synthetically. This can not only express the subjective will of policy makers, but also avoid the deviation of subjective wishes and the actual situation, while making full use of the information of the original data.
Based on experience, we assume that subjective weights and objective weights are equally important, then the weight of each index is

$ W_{ti} = 0.5 W_{si} + 0.5 W_{oi} $

首先我们对六种数据做标准化处理。我们采用极差法来进行标准化处理，公式如下

First, we standardize on the six kinds of data. We use the range method to standardize. Formula is as follows:

For positive indicators,
<!-- 公式1 -->
$ Y_i = \frac{X_i - X_{min}}{X_{max} - X_{min}} $

For negative indicators,
<!-- 公式2 -->
$ Y_i = \frac{X_{max} - X_i}{X_{max} - X_{min}} $

所以最终能源、经济和环境各方面的计算公式如下

Therefore, the final calculation formula of energy, economy and environment is as follows.
<!-- 公式3 -->
$ E = \sum_\limits{i=1}^{n} W_{ti} Y_{i} $

我们假定能源、经济与环境对我们的指标有同等的重要程度，因此公式为

We assume that energy, economy and environment are equally important to our indicators, so the formula is
<!-- 公式4 -->
$ E^{*} = \frac{E_e + E_c + E_v}{3} $

该指标越大，证明清洁能源状况越好。其中，由于二氧化碳排放量为正值，所以实际计算中要取反处理。

The larger the indicator, the better the clean energy situation. Among them, due to the positive carbon dioxide emissions, so the actual calculation to take the opposite treatment.

我们对各州1980-2009年的能源状况指标进行统计，做出不同州能源状况指标的的时间序列图

We make a statistical analysis of the energy status indicators of each state from 1980 to 2009, and make the time sequence diagram of energy status indicators in different states, as shown below.
<!-- 图    各州综合能源状况指标时间序列图 -->

我们可以看到，开始处由于经济的快速增长，指标不断增大。但由于二氧化碳排放量对环境因素影响，在1987年左右各州的指标开始减小。之后随着可持续发展的观念增强，各个州提出自己的新能源政策，指标开始增大。这里可以看到德克萨斯州和新墨西哥州由于大力发展新能源，它们的指标增大速度相对比较明显。
另外，由于各州有大量的数据会影响州间的异同，我们通过做出不同州的时间序列图，分别分析了四个州的可再生能源状况。

As we can see, the beginning of the rapid economic growth, the index is increasing. But because of the environmental impact of carbon dioxide emissions, the number of states began to decline around 1987. Then, with the idea of sustainable development strengthened, each state proposed its own new energy policy, and the index began to increase. Here you can see Texas and New Mexico due to the development of new energy, their indicators of increased speed is relatively obvious.

In addition, since there is a large amount of data in each state that affects the similarities and differences between the states, we analyzed the renewable energy status in each of the four states by making time series diagram of different states.

AZ

我们对亚利桑那州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We chart the development trends of various renewable energy categories in Arizona over the past 50 years, as shown below.
<!-- 图    亚利桑那州各类可再生能源时间序列图 -->

可以看到亚利桑那州水电能源发展较早，并且在所有可再生能源中占有相当高的比例，木材和废物品次之。其他的可再生能源基本在上世纪8、90年代开始发展，其中燃料乙醇和太阳能发展迅速，截止到2009年，燃料乙醇的消耗量超过木材和废物品，成为第二大消耗可再生能源。
分析亚利桑那州的地理和气候可以发现，亚利桑那州有充沛的太阳能资源，平均每年有300个晴天。但由于光伏能源成本长期较高，所以在经历了初期的快速增长后，增长速度逐渐变缓。目前光伏能源成本估计在0.15-0.25美元/千瓦时，并没有太好的发展。
【http://www1.eere.energy.gov/solar/myths.html】
而亚利桑那州的风能发展虽然缓慢，但是发展前景较好。因为''The larger contiguous areas of good-to-excellent resource are located in northern and eastern Arizona close to the eastern edge of the Mogollon Rim. Good-to-excellent wind resources are also found on the higher rims and ridge crests throughout the state.''
【www.eere.energy.gov/windandhydro/windpoweringamerica/maps_template.asp?stateab=az】

We can see that Arizona has a relatively early development of hydropower and has a high proportion of all renewable energy, and wood and waste energy are secondary. Other renewable sources of energy began to develop in the 1980s and 1990s. Fuel ethanol and solar power are growing rapidly, and by 2009, fuel ethanol consumption exceeded wood and waste consumption, making it the second largest consumption of renewable energy.

An analysis of Arizona's geography and climate shows that Arizona has abundant solar energy resources, averaging 300 sunny days a year. However, due to the long-term high cost of photovoltaic energy, the growth rate has gradually slowed down after the initial rapid growth. The current cost of photovoltaic energy is estimated at 0.15-0.25 dollars / kWh, so the development is not satisfactory.

【http://www1.eere.energy.gov/solar/myths.html】

Although the wind energy in Arizona is developing slowly, its development prospects are good. The larger contiguous areas of good-to-excellent resource are located in northern and eastern Arizona close to the eastern edge of the Mogollon Rim. Good-to-excellent wind resources are also found on the higher rims and ridge crests throughout the state.

【www.eere.energy.gov/windandhydro/windpoweringamerica/maps_template.asp?stateab=az】

CA 

我们对加利福尼亚州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We chart the trends in various renewable energy categories in California over the past 50 years, as shown below.

<!-- 图    亚利桑那州各类可再生能源时间序列图 -->

通过图表可以发现加利福尼亚州的可再生能源消耗总量巨大。各类可再生能源消耗与亚利桑那州类似，也是水电能源占所有可再生能源最高比例，然后是木材和废品。其他的的可再生能源也是从上个世纪80、90年代开始发展，其中燃料乙醇发展最为迅速。不同于其他能源的是加利福尼亚州的地热能发展较早，且消耗量较大。
分析加利福尼亚州的地理状况，可以看到加利福尼亚州州东部，尤其是东南端和东北端是一片沙漠，所以可能蕴含较多的地热能。另外由于人口数量众多，所以导致消耗的能源也非常多。

The figure shows that California's total renewable energy consumption is huge. Renewable energy consumption is similar to Arizona's, and is the highest proportion of all renewable energy sources, followed by wood and waste. Other renewable sources of energy have been growing since the 1980s and 1990s, with fuel ethanol growing fastest. Unlike other sources of energy, California's geothermal energy has grown earlier and consumed much more.

Analyzing the state of California, you can see that the eastern part of California, especially the southern tip and the northeast end is a desert, so there may be more geothermal energy. In addition, due to the large population, there are also many energy consumption.

NM

我们对新墨西哥州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We plot the trends in various renewable energy categories in New Mexico over the past 50 years as shown below.

<!-- 图    新墨西哥州各类可再生能源时间序列图 -->

可以看到该州的总可再生能源消耗较少，2005年以前可再生能源中消耗所占比例最大的是木材和废品。风能在2005年以后发展迅速，一跃成为最大消耗可再生能源。

Can see the state's total renewable energy consumption less. By 2005, the largest share of renewable energy was wood and waste. Wind energy has grown rapidly since 2005, making it the biggest consumption of renewable energy.

TX

我们对德克萨斯州50年以来的各种可再生能源类别的发展趋势进行绘图，如下所示

We plot the trends in various renewable energy categories in Texas over the past 50 years as shown below.

<!-- 图    德克萨斯州各类可再生能源时间序列图 -->

可以看到该州的可再生能源总量消耗较少，2005年以前可再生能源中消耗所占比例最大的是木材和废品。风能在2005年以后发展迅速，一跃成为最大消耗可再生能源。 
可以看到在风能和木材和废品使用的情况上，德克萨斯州与新墨西哥非常相似。
分析德克萨斯州的数据发现，目前德克萨斯州是美国风能发电量最大的州，而且该数值还在不断增长，这得益于该州制定的renewables portfolio standard (RPS)，RPS迫使电力供应商大规模并积极主动地使用风能和其它可再生能源发电
【The renewables portfolio standard in Texas: an early assessment】

It can be seen that Texas is very much like New Mexico in the use of wind energy and wood and waste.
Analysis of Texas data found that at present Texas is the largest state in the United States with the highest wind energy generation and this value is still growing due to the state's renewables portfolio standard (RPS), which forces RPS Power suppliers proactively use large-scale wind and other renewable energy to generate electricity.

【The renewables portfolio standard in Texas: an early assessment】


总结

对上面所有图表进行比较可以发现，亚利桑那州和加利福尼亚州较为相似，而新墨西哥州和德克萨斯州较为相似。亚利桑那州和加利福尼亚的可再生能源中，水电能源占有很大比例；新墨西哥州和德克萨斯州的可再生能源中，风能占有很大比例。由于不同州的地理和气候等因素不同，亚利桑那主要发展太阳能，加利福尼亚州主要发展地热能，新墨西哥州和德克萨斯州主要发展风能。另外每个州的的燃料乙醇能源都有一定的发展。

summary

A comparison of all the figures above shows that Arizona and California are similar, while new Mexico and Texas are similar. Renewable energy sources in Arizona and California account for a large proportion of renewable energy. Wind energy in New Mexico and Texas accounts for a large proportion of renewable energy.
Due to different geography and climate in different states, Arizona mainly develops solar energy. In California, it mainly develops geothermal energy. New Mexico and Texas mainly develop wind energy.
In addition, each state's fuel ethanol energy has a certain development.