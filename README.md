This repository serves as an organization for articles discussed in the reading group of the [Intelligent Decision Games and Digital Eonomic Advancements-Anhui Province Key Laboratory for Philosophy and Social Science](http://team.ustc.edu.cn/yunchougongxueshe/en/index.htm)(**IDEALab**). It contains articles along with accompanying slides that provide an introduction to the background and motivation. If you are interested in collaborating or discussing further, please feel free to contact me via tangle@mail.ustc.edu.cn.

##### 🔥 Updated 2023-9-26

##### ⚠ Notion: Please remember to always seek the owner's permission before making any changes to their repository.
##### 💡 Tips: If you need to download files, I recommend cloning the repository via SSH link. Directly downloading the zip file can be inconvenient when it comes to updating.


# Table of Contents 

* [Group Robust Optimization-Logistics](#Group Robust Optimization-Logistics)

* [Group Cooperative Games-OM](#Group Cooperative Games-OM)

* [Group Cooperative Games-ALG](#Group Cooperative Games-ALG)

* [Group Service & Scheduling](#Group Service & Scheduling)

* [Group Reinforcement Learning](#Group Reinforcement Learning)

* [Reading Group](#Reading Group)

# Group Robust Optimization-Logistics

## 2023

1. IJOC, 2023 (label: DRO chance constraint) [Distributionally Robust Chance-Constrained p-Hub Center Problem](https://pubsonline.informs.org/doi/full/10.1287/ijoc.2022.0113)(这篇文章考虑了一种p-hub转运设施选址的背景，针对以往研究都是满足正太分布且不同节点对之间相互独立的假设，提出了分布式鲁棒机会约束处理上述不足。文章在相互独立的情况下对机会约束的模型重构；以及联合分布下用经验分布抽样来近似求解). Reporter: Yao Wang.

# Reading Group

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