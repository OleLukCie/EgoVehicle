# The Bitter Lesson

## Rich Sutton

### March 13, 2019

The biggest lesson that can be read from 70 years of AI research is that general methods that leverage computation are ultimately the most effective, and by a large margin. The ultimate reason for this is Moore's law, or rather its generalization of continued exponentially falling cost per unit of computation. Most AI research has been conducted as if the computation available to the agent were constant (in which case leveraging human knowledge would be one of the only ways to improve performance) but, over a slightly longer time than a typical research project, massively more computation inevitably becomes available. Seeking an improvement that makes a difference in the shorter term, researchers seek to leverage their human knowledge of the domain, but the only thing that matters in the long run is the leveraging of computation. These two need not run counter to each other, but in practice they tend to. Time spent on one is time not spent on the other. There are psychological commitments to investment in one approach or the other. And the human-knowledge approach tends to complicate methods in ways that make them less suited to taking advantage of general methods leveraging computation.  There were many examples of AI researchers' belated learning of this bitter lesson, and it is instructive to review some of the most prominent.  

In computer chess, the methods that defeated the world champion, Kasparov, in 1997, were based on massive, deep search. At the time, this was looked upon with dismay by the majority of computer-chess researchers who had pursued methods that leveraged human understanding of the special structure of chess. When a simpler, search-based approach with special hardware and software proved vastly more effective, these human-knowledge-based chess researchers were not good losers. They said that ``brute force" search may have won this time, but it was not a general strategy, and anyway it was not how people played chess. These researchers wanted methods based on human input to win and were disappointed when they did not.  

A similar pattern of research progress was seen in computer Go, only delayed by a further 20 years. Enormous initial efforts went into avoiding search by taking advantage of human knowledge, or of the special features of the game, but all those efforts proved irrelevant, or worse, once search was applied effectively at scale. Also important was the use of learning by self play to learn a value function (as it was in many other games and even in chess, although learning did not play a big role in the 1997 program that first beat a world champion). Learning by self play, and learning in general, is like search in that it enables massive computation to be brought to bear. Search and learning are the two most important classes of techniques for utilizing massive amounts of computation in AI research. In computer Go, as in computer chess, researchers' initial effort was directed towards utilizing human understanding (so that less search was needed) and only much later was much greater success had by embracing search and learning.  

In speech recognition, there was an early competition, sponsored by DARPA, in the 1970s. Entrants included a host of special methods that took advantage of human knowledge---knowledge of words, of phonemes, of the human vocal tract, etc. On the other side were newer methods that were more statistical in nature and did much more computation, based on hidden Markov models (HMMs). Again, the statistical methods won out over the human-knowledge-based methods. This led to a major change in all of natural language processing, gradually over decades, where statistics and computation came to dominate the field. The recent rise of deep learning in speech recognition is the most recent step in this consistent direction. Deep learning methods rely even less on human knowledge, and use even more computation, together with learning on huge training sets, to produce dramatically better speech recognition systems. As in the games, researchers always tried to make systems that worked the way the researchers thought their own minds worked---they tried to put that knowledge in their systems---but it proved ultimately counterproductive, and a colossal waste of researcher's time, when, through Moore's law, massive computation became available and a means was found to put it to good use.  

In computer vision, there has been a similar pattern. Early methods conceived of vision as searching for edges, or generalized cylinders, or in terms of SIFT features. But today all this is discarded. Modern deep-learning neural networks use only the notions of convolution and certain kinds of invariances, and perform much better.  

This is a big lesson. As a field, we still have not thoroughly learned it, as we are continuing to make the same kind of mistakes. To see this, and to effectively resist it, we have to understand the appeal of these mistakes. We have to learn the bitter lesson that building in how we think we think does not work in the long run. The bitter lesson is based on the historical observations that 1) AI researchers have often tried to build knowledge into their agents, 2) this always helps in the short term, and is personally satisfying to the researcher, but 3) in the long run it plateaus and even inhibits further progress, and 4) breakthrough progress eventually arrives by an opposing approach based on scaling computation by search and learning. The eventual success is tinged with bitterness, and often incompletely digested, because it is success over a favored, human-centric approach.  

One thing that should be learned from the bitter lesson is the great power of general purpose methods, of methods that continue to scale with increased computation even as the available computation becomes very great. The two methods that seem to scale arbitrarily in this way are search and learning.  

The second general point to be learned from the bitter lesson is that the actual contents of minds are tremendously, irredeemably complex; we should stop trying to find simple ways to think about the contents of minds, such as simple ways to think about space, objects, multiple agents, or symmetries. All these are part of the arbitrary, intrinsically-complex, outside world. They are not what should be built in, as their complexity is endless; instead we should build in only the meta-methods that can find and capture this arbitrary complexity. Essential to these methods is that they can find good approximations, but the search for them should be by our methods, not by us. We want AI agents that can discover like we can, not which contain what we have discovered. Building in our discoveries only makes it harder to see how the discovering process can be done.

---

# 惨痛的教训

理查德·萨顿
2019年3月13日

回顾七十年人工智能研究历程，最深刻的一大教训是：依托算力的通用方法最终具备压倒性的最优效果，优势差距极为悬殊。究其根本原因，是摩尔定律，更广义地来说，是单位计算成本持续呈指数级下降。绝大多数人工智能研究开展时，都默认智能体可调用的算力是固定不变的（在这种前提下，借用人类知识就成了提升性能为数不多的路径之一）。但只要研究周期略长于单个常规科研项目，海量算力终将唾手可得。研究人员为追求短期可见的性能提升，会着力植入自身对特定领域的人类先验知识；可放眼长期，唯一起决定性作用的只有算力的规模化运用。
两种研究路径并非必然相互冲突，但在实际落地中往往彼此掣肘。投入一种方法的时间，就无法用于另一种。科研人员会在心理上对选定的单一研究路径形成路径依赖。而且依赖人类先验知识的方案通常会让算法体系变得繁复，难以适配依托算力扩展的通用优化框架。
人工智能研究者们屡次后知后觉地领悟到这一惨痛教训，梳理几个最具代表性的案例颇具启发意义。
在国际象棋人机博弈领域，1997年击败世界冠军卡斯帕罗夫的程序，核心依靠大规模深度搜索算法。彼时绝大多数国际象棋计算机博弈研究者对此结果倍感沮丧，他们此前一直深耕依托人类对象棋规则特殊结构理解的算法。当一套依托专用软硬件、逻辑更简洁的搜索算法展现出碾压级性能时，深耕人类先验规则的这批研究者难以坦然接受。他们声称蛮力搜索只是侥幸取胜，并非通用型策略，而且人类下棋根本不会采用这种方式。这些研究者原本寄希望于基于人类经验的算法胜出，最终结果令他们大失所望。
计算机围棋领域的研究演进呈现出完全相同的规律，只是晚了整整二十年。早期科研人员投入巨量精力，试图借助人类棋理知识、围棋本身的规则特性规避大规模搜索运算。可一旦规模化高效搜索技术落地，此前所有努力都变得无关紧要，甚至走入了弯路。自博弈学习构建价值函数同样起到了关键作用（这套思路也被应用于诸多其他博弈游戏，象棋程序中也曾用到，只是1997年击败人类冠军的那套象棋程序里，学习模块并未占据核心地位）。自博弈学习乃至广义上的机器学习，和搜索算法本质相通，都能够调动海量算力完成运算。搜索与学习，是人工智能研究中撬动大规模算力最重要的两类技术范式。和象棋博弈的发展轨迹一致，围棋早期研究重心都放在嵌入人类棋理知识以缩减搜索量上，直到很久之后，拥抱搜索与学习框架才取得跨越式突破。
语音识别领域也曾上演相似的历程。上世纪70年代，美国国防部高级研究计划局（DARPA）主办过一场早期语音识别竞赛。参赛方案大多是依托人类先验知识设计的专用算法，融入了词汇、音素、人类发声器官生理结构等人工规则。另一阵营则是基于隐马尔可夫模型的统计类新算法，统计模型运算量更大。最终，统计方法再度完胜依赖人工规则的方案。
这场胜利推动自然语言处理领域在数十年间发生颠覆性变革，统计与算力逐步成为行业主流。近年深度学习在语音识别领域的兴起，正是这一发展脉络的延续。深度学习算法对人类先验知识的依赖度进一步降低，依靠更大规模算力与海量数据集训练，构建出性能大幅跃升的语音识别系统。
和博弈领域的研究误区如出一辙，研究者总想复刻自己理解的人类思考模式，把总结出的规则固化进系统，但从长远来看，这种做法收效甚微，更是对科研人力的巨大浪费。当摩尔定律带来海量算力，且配套算法能够高效调用算力时，人工内嵌规则的路径便彻底失去竞争力。
计算机视觉领域的发展轨迹别无二致。早期视觉算法以边缘检测、广义圆柱体建模、SIFT特征提取为核心思路，如今这些方法已被全面淘汰。现代深度神经网络仅依托卷积运算与特定不变性原理，就实现了远优于传统算法的效果。
这是一条至关重要的教训。整个人工智能行业至今仍未彻底吃透其中内核，还在反复重蹈覆辙。想要看清问题本质、有效规避误区，就必须理解这类错误思路为何具备吸引力。我们必须铭记这条惨痛教训：从长远来看，内嵌我们主观理解的人类思考逻辑无法走通。
该教训源于历史实践总结出四条客观规律：

1. 人工智能研究者常常试图为智能体内置人工归纳的领域知识；
2. 这种方式短期有效，也能给研究者带来成就感；
3. 长期来看性能会遭遇瓶颈，甚至阻碍后续技术迭代；
4. 突破性进展最终都会来自反向路径：依靠搜索与学习实现算力规模化扩展。
   最终技术突围的喜悦中夹杂着一丝苦涩，人们也往往无法彻底消化这份成果，因为胜利推翻的是研究者们青睐已久的、以人类认知为中心的技术路线。
   从这条惨痛教训中可以提炼出第一层核心启示：通用范式具备强大生命力，即便算力规模扩张至极大水平，这类算法依旧可以随算力同步扩展。目前来看，搜索与学习是两种能够无限随算力扩容的核心通用方法。
   第二层核心启示：人类大脑的内在认知机制复杂度极高、无法被完整拆解还原。我们不要再试图用简化模型去解构大脑认知，比如用简单框架定义空间、物体、多智能体交互、对称关系等概念。这些都属于外部客观世界自带的、具有随机性的复杂结构，本身就无穷无尽，不适合直接内嵌进系统。
   我们应当只搭建元级通用框架，让框架自主挖掘、抓取世间各类复杂规律。这类元方法的核心能力是自主生成优质近似解，由算法完成搜索拟合，而非由人类提前定义规则。我们需要的是具备自主探索能力的人工智能，而非堆砌人类已有发现成果的系统。强行内嵌人类总结的结论，只会阻碍人工智能自主探索机制的研发。