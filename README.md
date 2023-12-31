This repository serves as an organization for articles discussed in the reading group of the [Intelligent Decision Games and Digital Eonomic Advancements-Anhui Province Key Laboratory for Philosophy and Social Science](http://team.ustc.edu.cn/yunchougongxueshe/en/index.htm)(**IDEALab**). It contains articles along with accompanying slides that provide an introduction to the background and motivation. If you are interested in collaborating or discussing further, please feel free to contact me via tangle@mail.ustc.edu.cn.

##### 🔥 Updated 2023-11-22

##### ⚠ Notion: Please remember to always seek the owner's permission before making any changes to their repository.
##### 💡 Tips: If you need to download files, I recommend cloning the repository via SSH link. Directly downloading the zip file can be inconvenient when it comes to updating.


# Table of Contents 

* [Group Robust Optimization-Logistics](#dro-logistics)

* [Group Cooperative Games-OM](#cgt-om)

* [Group Cooperative Games-ALG](#cgt-alg)

* [Group Service & Scheduling](#service-&-scheduling)

* [Group Reinforcement Learning](#rl)

* [Reading Group](#reading-group)

# dro-logistics

## 2023

1. IJOC, 2023 (label: DRO chance constraint) [Distributionally Robust Chance-Constrained p-Hub Center Problem](https://pubsonline.informs.org/doi/full/10.1287/ijoc.2022.0113)(这篇文章考虑了一种p-hub转运设施选址的背景，针对以往研究都是满足正态分布且不同节点对之间相互独立的假设，提出了分布式鲁棒机会约束处理上述不足。文章在相互独立的情况下对机会约束的模型重构；以及联合分布下用经验分布抽样来近似求解). Reporter: Yao Wang.

2. SSRN, 2022 (label: VRPSD) [Solving Large-Scale Vehicle Routing Problems with
Unsplit Demands via Limited Information](https://ssrn.com/abstract=4271787)(这篇文章考虑了大规模的动态VRP问题，作者创新性地对动态的Bin Packing问题进行了改进，并且采用全新的double partitioning方法。本文还对带有overlapping的VRP问题性质进行了分析，得到了很好的渐进性结论) Reporter: Zheng Tan. [[note]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/dro-Logistics/20231014_note.pdf)

# cgt-om

## 2023

1. JPE, 2000(label: Auction) [Putting auction theory to work: the simultaneous ascending auction](https://www.journals.uchicago.edu/doi/abs/10.1086/262118) (回顾经济理论在 "同时递增拍卖 "最初设计和后来改进中的应用，该拍卖最初是为美国出售无线电频谱许可证而开发的，并分析了拍卖的一些能力和局限性、各种详细规则的作用、引入组合竞价的可能性，以及将拍卖适用于以收入而非效率为主要目标的销售的一些考虑因素。) Reporter: Yuqing Sun.



# cgt-alg

## 2023

1. IJOC, 2023 (label:Grand coalition stability) Stabilizing Grand Cooperation via Cost Adjustment: An Inverse Optimization Approach(提出了稳定大联盟的一种新的工具，属于逆优化问题的成本调整，证明了Np-难和可行性条件，并提出基于两种线性规划重构的求解算法。). Reporter: Junzhe Zhao. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/cgt-alg/20231011_slides.pptx) 

2. JOC, 2016 (label:cooperative games) Computing Near-Optimal Stable Cost Allocations for Cooperative Games by Lagrangian Relaxation(这篇论文提出了一个基于拉格朗日松弛来解决空核联盟成本分摊下稳定性的新的通用框架，并在两个设施选址博弈中展示了新方法的优越性). Reporter: Chaoyang Guo.
[[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/cgt-alg/20231018_slides_guo.pptx) [[note]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/cgt-alg/20231018_note_guo.pdf)

3. OR, 2020 (label:coopeartive games) Simultaneous Penalization and Subsidization for
Stabilizing Grand Cooperation(这篇文章提出了稳定大联盟的惩罚-补贴函数，分析函数的性质，并提出两种算法去构造惩罚补贴函数。给出 w(z)的两种有效求解方法。最后将其应用到并行机调度博弈中。) Reporter: Chengcheng Yu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/cgt-alg/20231025_slides.pdf)

4. MP, 2010 (label: IM game, cost allocation, OCAP) New techniques for cost sharing in combinatorial optimization games（本文定义了一类常见的合作博弈——整数规划博弈。对于该博弈，本文研究的是其对应的最优成本分摊问题。在理论上，本文发现了整数规划博弈的最优成本分摊问题的等价问题；在算法上，本文针对该问题提出了三种求解算法：基于列生成的算法、基于行生成的算法、基于行生成和列生成的算法。）Reporter: Xiangbin Liao [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/cgt-alg/20231108_slides.pptx)

# service-&-scheduling

1. NRL, 2019 (label:assemble-to-order)[Integrating decisions with advance supply information in an assemble-to-order system](https://onlinelibrary.wiley.com/doi/10.1002/nav.21881)（这篇论文研究了定期检查的多产品多零件的ATO模型，通过场景树将预先供应信息集成进模型中，并开发了MOBCA的启发式方法求解最优零件分配策略）reporter: Jingzhao Xu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/service-&-scheduling/20231015_slides_xu.pptx)

2. DSS, 2022 (Label: Crowdfunding)[Exploring investors' expectancies and its impact on project funding success likelihood in crowdfunding by using text analytics and Bayesian networks](https://doi.org/10.1016/j.dss.2021.113695)(这篇论文通过实证分析和贝叶斯网络判析影响众筹成功性的因素。) Reporter: Jiali Zhu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/service-&-scheduling/20231015_slides_zhu.pptx)

3. MKSC, 2013 (Label: Retention) [Correcting Audience Externalities in Television Advertising](https://doi.org/10.1287/mksc.2013.0807)(这篇论文基于动态规划算法和VCG拍卖机制，研究了观众留存率情况下的广告选择、排序与定价问题) Reporter: Qiuwei Guo. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/service-&-scheduling/20231105_slides_guo.pptx)

4. TRE, 2023 (Label: Territory planning,Rolling horizon method) [Experience-based territory planning and driver assignment with predicted demand and driver present condition](https://www.sciencedirect.com/science/article/pii/S1366554523000248)(这篇论文通过考虑司机的学习因素与预期的需求数据，设计了针对领域规划（TPP）问题的两阶段滚动优化算法。) Reporter: Zexi Li. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/service-&-scheduling/20231105_slides_li.pptx)

5. MS, 2020 (Label: DID) [Value of High-Quality Logistics: Evidence from a Clash Between SF Express and Alibaba](https://doi.org/10.1287/mnsc.2019.3411)(这篇论文通过两种双重差分法判析影响优秀物流质量的因素。) Reporter: Jialli Zhu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/service-&-scheduling/20231119_slides_zhu.pptx)

6. NRL,2015 (label:assemble-to-order)[Optimal FCFS Allocation Rules for Periodic-Review Assemble-To-Order Systems](https://onlinelibrary.wiley.com/doi/10.1002/nav.21620)（这篇论文研究了定期检查、先到先服务的ATO模型最优零件分配策略，通过研究remnant stock的影响细化库存持有成本的讨论，并研发了一种迭代算法求解该模型）reporter ：Jingzhao Xu

# rl

## 2023


1. IEEE Transactions on Intelligent Transportation Systems, 2021 (Label: reinforcement learning)[A Reinforcement Learning Approach for Rebalancing Electric Vehicle Sharing Systems
](https://ieeexplore.ieee.org/abstract/document/9457206)(这篇论文提出了一种用于可移动电动汽车共享系统(FFEVSS)再平衡的强化学习方法，学到的策略可以大大减少重新平衡网络所需的时间。) Reporter: Shuyu Li.

2. arXiv, 2023 (Label: VRP, RL) [Too Big, so Fail? -- Enabling Neural Construction Methods to Solve Large-Scale Routing Problems](https://arxiv.org/abs/2309.17089v1)(这篇论文通过使用R&R思想，将大规模VRP问题拆分成模型训练规模类似的小规模问题来提高总体的求解效果) Reporter: Jackie Zheng.

3. arxiv, 2023 (Label: Irregular BPP) [Learning based 2D Irregular Shape Packing](https://arxiv.org/abs/2309.10329)(这篇文章利用提前组合的方式，将IBPP转化为矩形的BPP问题，采用机器学习方法求解) Reporter: Xiang Li.

4. TII, 2022 (label: FJSP, GNN) [Flexible Job Shop Scheduling via Graph Neural Network and Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/9826438/) (针对Flexible的特点改进析取图，使用HGNN有效提取特征，具备规模泛化能力)  Reporter: Kuan Xu.

5. EJOR, 2023 (Label: Stochastic requests) [Solving large-scale dynamic vehicle routing problems with stochastic requests](https://doi.org/10.1016/j.ejor.2022.07.015)(这篇论文研究了随机客户请求的DVRP，将其建模为一个多阶段优化问题，利用近似方法与最优接受和分配决策规则结合，得到了高效的在线调度策略。) Reporter: Shuyu Li.

# reading-group

## 2023

### Jul

1. POMS, 2022 [Data-driven platelet inventory management under uncertainty in the remaining shelf life of units](https://onlinelibrary.wiley.com/doi/10.1111/poms.13795)(使用ERM和Robust方法进行医院血小板周期性库存决策，主要特点在于血小板保质期较短，并且在医疗场景中缺货惩罚较高). <u>Reporter: Chengcheng Yu.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230718_slides.pdf) 

### Aug

1. OR, 2023 [An Exponential Cone Programming Approach for Managing Electric Vehicle Charging](https://pubsonline.informs.org/doi/abs/10.1287/opre.2023.2460)(使用指数锥规划近似方法研究电动车充电服务商的定价-调度问题，效果优于SAA和DRO). <u>Reporter: Menghang Wang.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230802_slides.pdf)
2. MS, 2023 [Optimal Robust Policy for Feature-Based Newsvendor](https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2023.4810)(在基于特征的报童问题(feature-based newsvendor)中提出Shapley Extension方法，相比现有的机器学习方法显著改善模型样本外表现，在小样本情形更为明显). <u>Reporter: Zheng Tan.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230805/slides.pdf) [[sm]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230805/sm.zip)
3. MS, 2020 [Multiplayer Allocations in the Presence of Diminishing Marginal Contributions: Cooperative Game Analysis and Applications in Management Science](https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2020.3709)(基于经济学概念在合作博弈中提出ADMC性质，给出了ADMC Games核心存在的充分必要条件，研究其Shapley值性质和空核情形的最小核，最后在code-sharing game等场景进行具体的分析). <u>Reporter: Zixiang Wu.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230808_slides.pdf)
4. OR, 2022 [Transparency and Control in Platforms for Networked Markets](https://pubsonline.informs.org/doi/10.1287/opre.2021.2244)(对三种不同的平台设计进行建模和分析：开放访问，受控分配，以及歧视性访问。基于网络化的Cournot竞争模型作为分析的基础，文章为每种设计提供了最坏情况下的效率损失界限。). <u>Reporter: Yuqing Sun.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230818_slides.pdf)
5. MS, 2020 [High-Performance Practice Processes](https://pubsonline.informs.org/doi/10.1287/mnsc.2019.3286)(基于动态规划对运动员训练过程进行建模，同时考虑训练强度带来的正负效用，针对模型的4种情况分析相应的最优训练策略，最后使用真实马拉松训练数据进行模拟。). <u>Reporter: Qiuwei Guo.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230826_slides.pdf)
6. EJOR, 2023 [Inverse optimization of integer programming games for parameter
estimation arising from competitive retail location selection](https://www.sciencedirect.com/science/article/pii/S0377221723005131)(假设已有的 retailers 为最优选址决策，建模为整数规划博弈（满足近似纳什均衡），使用逆优化的方法来进行用户的偏好（品牌、距离、便利性等）参数估计，新的 retailer 基于此进行选址。). <u>Reporter: Chengcheng Yu.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230829_slides.pdf)


### Sep

1. OR, 2022 (label: Distributionally Robust Losses) [Distributionally Robust Losses for Latent Covariate Mixtures](https://pubsonline.informs.org/doi/10.1287/opre.2022.2363)(使用marginal loss方法计算机器学习的损失函数，从而保障minority子集的预测精度). <u>Reporter: Zheng Tan.</u> [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230909/slides.pdf) [[code]](https://github.com/hsnamkoong/marginal-dro) [[sm]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230909/sm.pdf)

2. M&SOM, 2023 (label: 3PL & crowdsourcing of bicycle network rebalance) [Vehicle Rebalancing in a Shared Micromobility System
with Rider Crowdsourcing](https://pubsonline.informs.org/doi/abs/10.1287/msom.2023.1199)(使用network建模方式及启发式算法探讨3PL和众包策略在单车投放和再平衡问题上的影响). Reporter: Menghang Wang. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230911_slides.pdf)

3. MS, 2021 (label: Social learning) [Reviews and Self-Selection Bias with Operational Implications](https://pubsonline.informs.org/doi/10.1287/mnsc.2020.3892)(这篇论文为消费者购买决策开发了一个简洁的选择模型，并且表明当消费者混淆事前先天偏好的产品或服务与事后的体验和服务质量时会导致一种上升的偏差，对于利基产品来说这种偏差更为明显). Reporter: Yuqing Sun. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230920_slides_syq.pdf)

4. TRB, 2022 (label: Information) [Shall firms withhold exact waiting time information from their customers? A transport example](https://www.sciencedirect.com/science/article/abs/pii/S019126152200162X)(这篇论文探讨了运输公司在选择信息策略方面的影响，例如广告精确的时间表或平均间隔时间，以及这些策略如何影响乘客需求和整体福祉，特别关注需求率曲线在等待时间中的作用). Reporter: Zixiang Wu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20230920_slides_wzx.pdf)

### Oct

1. OR, 2020 (Label: Small data) [Ambulance Emergency Response Optimization in Developing Countries](https://pubsonline.informs.org/doi/10.1287/opre.2019.1969)(这篇论文研究了在中低收入国家（LMIC）的急救数据缺乏的背景下，采用数据驱动的方法来对医疗紧急救护车进行响应优化。) Reporter: Chengcheng Yu. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20231004_slides_ycc.pdf)

2. POM, 2020 (Label: Project scheduling) [Project Evaluation and Selection with Task Failures](https://onlinelibrary.wiley.com/doi/10.1111/poms.13107)(这篇论文考虑了项目的风险随阶段性任务完成而递减的特性，建立了一个最大化项目期望净收益的0-1指数和模型，并基于近似法和启发式法的bound求解方法设计了分支定界精确求解算法。) Reporter: Qiuwei Guo. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20231004_slides_gqw.pdf)


### Nov

1. TRB, 2023 Cost allocation of cooperative autonomous truck platooning:
Efficiency and stability analysis(该研究探讨了合作自动驾驶卡车（AT）平台在运营商之间的成本分摊。). Reporter: Junzhe Zhao. [[Slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20231102_slides_zhao.pdf)

2. EJOR,2019-A fuzzy cooperative game theoretic approach for multinational water resource spatiotemporal allocation（该研究讨论了跨国水资源时空分配的一种模糊合作博弈方法）
Reporter:Haoyang Li. [[slides]](https://github.com/ZhengTanUSTC/IDEALab-ReadingGroup/blob/main/files/reading-group/2023/20231102_slides_li.pptx)




### 📢 Suggestions to reporters:

- 选择文献阶段，汇报者选定后发一个label在群内，包含文章所属研究范围。一篇文章需要明确一个唯一的label，*比如说 EJOR, 2023 [Inverse optimization of integer programming games for parameter estimation arising from competitive retail location selection ](https://www.sciencedirect.com/science/article/pii/S0377221723005131)的label虽然和inverse optimization, integer programming games都相关，但是inverse optimization只是方法，核心贡献集中在后者；* 
  - 自己讲述的论文尽量控制在1-2个相同的label范围内，和自己的研究问题相关；
  - 综合性较强的论文，我们开设一个“others” label用来存放，但是选择这个label进行汇报的同学需要格外小心地面对质疑；
  - 选题的目标为，在汇报次数足够多后，可以把自己的汇报内容归类，问及文章之间的联系时必须很清楚；
- 准备阶段，严格控制slides页数在15页以内。从以下几个方面有偏向性地选择：文章作者信息，文章的背景和贡献，建模方法，关键性的结论，实验；
  - 避免“套路化”介绍。如VRP文章，大部分不需要特别详细地介绍variable, model的含义；
  - 避免技术的堆叠。尽量让其他人能听懂；
  - 顺便浏览一些相关文献，可以作简要的介绍。*如介绍DRO newsvendor的时候提到adjustable DRO，下次分享甚至可以直接讲这一篇；*
- 汇报阶段，汇报slides的时间控制在20min之内，先用较为通俗的语句讲述slides，随后再进行文章正文的讲述，再进行最后的讨论；
- 结束阶段，所有相关的资料都可分享到github仓库里。

### 👂 Suggestions to listeners:

- 开始前花10-20min大概浏览一遍文章。