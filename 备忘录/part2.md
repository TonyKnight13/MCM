A

基于我们在Part1中的预测结果，我们发现各州之间能源分布不均衡。亚利桑那州和加利福尼亚州对能源的消耗远远大于生产，而新墨西哥州和德克萨斯州的能源生产又远远大于消耗。所以我们考虑如果四个州能实现能源互补，能源充沛的州将能源输送给能源不充沛的州，使得四个州的能源分布相对均衡。同时能源消耗量大的州服以相应的报酬给能源输出州，可以给能源丰富的州带来经济效益，使得总体经济效益达到提高。这样不但提高了资源的利用率，同时带来了平均的经济效益。所以我们的总体目标为使得四个州的能源情况变得更加均衡，并且经济效益达到相对最优。

Based on our prediction results in Part1, we found that the energy distribution among states was unbalanced. Arizona and California consume far more energy than they produce, while new Mexico and Texas produce far more energy than they consume.
So we consider that if four states can achieve energy complementarity, energy-rich states will send energy to less energy-intensive states, and the energy distribution of the four states will be relatively balanced. At the same time, the state uniform with large energy consumption will be paid to the energy export state, which will bring economic benefits to the energy-rich states and improve the overall economic benefits.
This not only improves the utilization of resources, but also brings the average economic benefit. So our overall goal is to make the energy situation of the four states more balanced and the economic benefits to be relatively optimal.


对此，我们提出以下优化模型。我们的优化变量设为各州间的能源传输量，

For this, we propose the following optimization model. Our optimization variable is set as energy transfer between states,

$ T_e(i,i) $,
$ T_s(i,j) $,

其中$i$表示某个州，$T_e$代表可再生能源的传输，$T_s$表示总能源的传输。

Where $i$ represents a state, $T_e$represents the transmission of renewable energy, and $T_s$represents the transmission of total energy.

我们将优化目标定为四个州使用的可再生能源比例尽量均衡。换句话说，四个州的使用的可再生能源的方差最小

We aim to optimize the proportion of renewable energy used in four states. In other words, the four states have the smallest variance in renewable energy,

$ min(\sigma^2(\frac{E_c(i)}{S_c(i)})) $.

我们使州内能源传输为0，相同两州之间传输互为相反数，所以我们设置的运输约束条件为

We make the energy transfer within the state zero, and the energy transfer between the two states is the opposite of each other. So we set the transport constraint conditions

$ T_e(i,i) = 0 $,
$ T_e(i,j) = -T_e(j,i) $,
$ T_S(i,i) = 0 $,
$ T_s(i,j) = -T_s(j,i) $.

同时根据我们的预测，四个州生总体产的再生能源大于四个州总体的对可再生能源的消耗，但是总能源消耗略大于生产，需要从其他地方进口。能量约束为：

At the same time, according to our forecasts, the total renewable energy produced by the four states is greater than the total renewable energy consumption of the four states, but the total energy consumption is slightly larger than that of production and needs to be imported from other places. Energy constraints are:

$ E_p(i) > E_c(i) $,
$ S_p(i) > S_c(i) $,
$ \sum\limits_{i}S_c(i) < \sum\limits_{i}S_p(i) $.
<!-- 感觉公式写不太对 -->

B

针对目标和我们模型求解的结果，并针对短期和长期目标，共提出了以下4个措施
到2025年的短期措施：
1.德克萨斯州和新墨西哥州将多余的可再生能源传输给亚利桑那州和加利福尼亚州。
2.加大可再生能源的传输，而减少化石等不可再生能源的传输。
到2050年的长期措施：
1.各州在现在能源状况的基础上继续大力发展可再生能源。
2.可以适当扩大合作的州的数量，以实现更优的计划。

In response to the objective and the results of our model solution, and for short-term goals and long-term goals, the following four measures were proposed.

Short-term measures until 2025:
1. Texas and New Mexico transfer excess renewable energy to Arizona and California.
2. Increase the transmission of renewable energy and reduce the transmission of non-renewable energy such as fossil fuels.

Long-term measures until 2050:
1. The states continue to vigorously develop renewable energy based on the current energy situation.
2. The states can approprately expand the number of cooperating states in order to achieve better project.


<!-- The following three measures are proposed according to the results of our goal and our model

1. Texas and New Mexico transfer excess renewable energy to Arizona and California.
2. The states continue to vigorously develop renewable energy based on the current energy situation.
3. Increase the transmission of renewable energy, and reduce the transmission of non-renewable energy such as fossil.  -->