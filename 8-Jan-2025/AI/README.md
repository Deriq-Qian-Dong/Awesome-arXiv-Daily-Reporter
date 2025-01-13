# PPTAgent: Generating and Evaluating Presentations Beyond Text-to-Slides 

**Title (ZH)**: PPTAgent：超越文本生图的幻灯片生成与评估 

**Authors**: Hao Zheng, Xinyan Guan, Hao Kong, Jia Zheng, Hongyu Lin, Yaojie Lu, Ben He, Xianpei Han, Le Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.03936)  

**Abstract**: Automatically generating presentations from documents is a challenging task that requires balancing content quality, visual design, and structural coherence. Existing methods primarily focus on improving and evaluating the content quality in isolation, often overlooking visual design and structural coherence, which limits their practical applicability. To address these limitations, we propose PPTAgent, which comprehensively improves presentation generation through a two-stage, edit-based approach inspired by human workflows. PPTAgent first analyzes reference presentations to understand their structural patterns and content schemas, then drafts outlines and generates slides through code actions to ensure consistency and alignment. To comprehensively evaluate the quality of generated presentations, we further introduce PPTEval, an evaluation framework that assesses presentations across three dimensions: Content, Design, and Coherence. Experiments show that PPTAgent significantly outperforms traditional automatic presentation generation methods across all three dimensions. The code and data are available at this https URL. 

**Abstract (ZH)**: 将下面的论文内容或标题翻译成中文：

将文档自动转换为演示文稿是一项具有挑战性的任务，需要平衡内容质量、视觉设计和结构一致性。现有方法主要集中在孤立地提高和评估内容质量，往往忽略了视觉设计和结构一致性，这限制了它们的实际应用。为了解决这些局限性，我们提出了PPTAgent，该方法通过借鉴人类工作流程的两阶段编辑方法，全面改进演示文稿生成。PPTAgent首先分析参考演示文稿以理解其结构模式和内容结构，然后通过代码操作草拟大纲并生成幻灯片，以确保一致性和对齐。为了全面评估生成演示文稿的质量，我们进一步引入了PPTEval这一评估框架，该框架从内容、设计和一致性三个维度评估演示文稿。实验结果表明，PPTAgent在所有三个维度上显著优于传统的自动化演示文稿生成方法。代码和数据可在以下链接处获取：this https URL。 

---
# Dolphin: Closed-loop Open-ended Auto-research through Thinking, Practice, and Feedback 

**Title (ZH)**: Dolphin：通过思考、实践和反馈实现的闭环开放式自动研究 

**Authors**: Jiakang Yuan, Xiangchao Yan, Botian Shi, Tao Chen, Wanli Ouyang, Bo Zhang, Lei Bai, Yu Qiao, Bowen Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2501.03916)  

**Abstract**: The scientific research paradigm is undergoing a profound transformation owing to the development of Artificial Intelligence (AI). Recent works demonstrate that various AI-assisted research methods can largely improve research efficiency by improving data analysis, accelerating computation, and fostering novel idea generation. To further move towards the ultimate goal (i.e., automatic scientific research), in this paper, we propose Dolphin, the first closed-loop open-ended auto-research framework to further build the entire process of human scientific research. Dolphin can generate research ideas, perform experiments, and get feedback from experimental results to generate higher-quality ideas. More specifically, Dolphin first generates novel ideas based on relevant papers which are ranked by the topic and task attributes. Then, the codes are automatically generated and debugged with the exception-traceback-guided local code structure. Finally, Dolphin automatically analyzes the results of each idea and feeds the results back to the next round of idea generation. Experiments are conducted on the benchmark datasets of different topics and results show that Dolphin can generate novel ideas continuously and complete the experiment in a loop. We highlight that Dolphin can automatically propose methods that are comparable to the state-of-the-art in some tasks such as 2D image classification and 3D point classification. 

**Abstract (ZH)**: 由于人工智能（AI）的发展，科学研究范式正经历着深刻的转变。 recent研究表明，各种AI辅助研究方法能够显著提高研究效率，通过改进数据分析、加速计算和激发新思想生成。为了进一步朝终极目标（即自动科学研究）迈进，本文提出Dolphin，这是一个第一个闭环开放式自动研究框架，进一步构建了整个人类科学研究过程。Dolphin可以生成研究想法、执行实验，并从实验结果中获得反馈以生成更高质量的想法。具体而言，Dolphin首先基于按主题和任务属性排序的相关文献生成新颖的想法。然后，代码会自动生成并调试，采用异常跟踪引导的局部代码结构。最后，Dolphin会自动分析每个想法的结果，并将结果反馈给下一轮想法生成。我们在不同主题的基准数据集上进行了实验，结果显示Dolphin能够连续生成新颖的想法并形成闭环。我们强调，在某些任务如2D图像分类和3D点分类中，Dolphin可以自动提出与最先进的方法相当的方法。 

---
# Neural DNF-MT: A Neuro-symbolic Approach for Learning Interpretable and Editable Policies 

**Title (ZH)**: 神经DNF-MT：一种用于学习可解释且可编辑策略的神经符号方法 

**Authors**: Kexin Gu Baugh, Luke Dickens, Alessandra Russo  

**Link**: [PDF](https://arxiv.org/pdf/2501.03888)  

**Abstract**: Although deep reinforcement learning has been shown to be effective, the model's black-box nature presents barriers to direct policy interpretation. To address this problem, we propose a neuro-symbolic approach called neural DNF-MT for end-to-end policy learning. The differentiable nature of the neural DNF-MT model enables the use of deep actor-critic algorithms for training. At the same time, its architecture is designed so that trained models can be directly translated into interpretable policies expressed as standard (bivalent or probabilistic) logic programs. Moreover, additional layers can be included to extract abstract features from complex observations, acting as a form of predicate invention. The logic representations are highly interpretable, and we show how the bivalent representations of deterministic policies can be edited and incorporated back into a neural model, facilitating manual intervention and adaptation of learned policies. We evaluate our approach on a range of tasks requiring learning deterministic or stochastic behaviours from various forms of observations. Our empirical results show that our neural DNF-MT model performs at the level of competing black-box methods whilst providing interpretable policies. 

**Abstract (ZH)**: 尽管深度强化学习已显示出其有效性，但模型的黑箱性质给直接策略解析带来了障碍。为解决这一问题，我们提出了一种神经符号方法——神经DNF-MT，用于端到端策略学习。神经DNF-MT模型的可微性质使其能够运用深度演员-评论家算法进行训练。同时，其架构设计使得训练后的模型可以直接翻译为可解析的策略，这些策略以标准逻辑程序（二值或概率逻辑程序）的形式表达。此外，还可以添加额外的层来从复杂观测中提取抽象特征，起到谓词发明的作用。逻辑表示高度可解析，并展示了如何编辑确定性策略的二值表示并将其重新整合回神经模型中，从而促进对学习策略的手动干预和调整。我们在涉及从各种观测形式学习确定性或随机行为的各种任务中评估了我们的方法。我们的实证结果表明，我们的神经DNF-MT模型在性能上与竞争的黑箱方法相当，同时提供了可解析的策略。 

---
# Online Reinforcement Learning-Based Dynamic Adaptive Evaluation Function for Real-Time Strategy Tasks 

**Title (ZH)**: 基于在线强化学习的动态自适应评价函数实时策略任务研究 

**Authors**: Weilong Yang, Jie Zhang, Xunyun Liu, Yanqing Ye  

**Link**: [PDF](https://arxiv.org/pdf/2501.03824)  

**Abstract**: Effective evaluation of real-time strategy tasks requires adaptive mechanisms to cope with dynamic and unpredictable environments. This study proposes a method to improve evaluation functions for real-time responsiveness to battle-field situation changes, utilizing an online reinforcement learning-based dynam-ic weight adjustment mechanism within the real-time strategy game. Building on traditional static evaluation functions, the method employs gradient descent in online reinforcement learning to update weights dynamically, incorporating weight decay techniques to ensure stability. Additionally, the AdamW optimizer is integrated to adjust the learning rate and decay rate of online reinforcement learning in real time, further reducing the dependency on manual parameter tun-ing. Round-robin competition experiments demonstrate that this method signifi-cantly enhances the application effectiveness of the Lanchester combat model evaluation function, Simple evaluation function, and Simple Sqrt evaluation function in planning algorithms including IDABCD, IDRTMinimax, and Port-folio AI. The method achieves a notable improvement in scores, with the en-hancement becoming more pronounced as the map size increases. Furthermore, the increase in evaluation function computation time induced by this method is kept below 6% for all evaluation functions and planning algorithms. The pro-posed dynamic adaptive evaluation function demonstrates a promising approach for real-time strategy task evaluation. 

**Abstract (ZH)**: 实时策略任务的有效评估需要适应性机制以应对动态和不可预测的环境。本研究提出了一种方法，通过在实时策略游戏中利用基于在线强化学习的动态权重调整机制，以改进评价函数，提高对战场情况变化的实时响应能力。在传统静态评价函数的基础上，该方法利用在线强化学习中的梯度下降技术动态更新权重，并结合权重衰减技术确保稳定性。此外，该方法还整合了AdamW优化器来实时调整在线强化学习的学习率和衰减速率，进一步减少对外部人工参数调整的依赖。轮循对战实验表明，该方法显著提高了Lanchester战斗模型评价函数、Simple评价函数和Simple Sqrt评价函数在IDABCD、IDRTMinimax和Portfolio AI等规划算法中的应用效果。随着地图规模的增加，评价函数得分的提升更为明显。同时，该方法引入的评价函数计算时间增加保持在所有评价函数和规划算法的6%以下。提出的动态适应性评价函数为实时策略任务的评估提供了一种有前景的方法。 

---
# Neural Deconstruction Search for Vehicle Routing Problems 

**Title (ZH)**: 车辆路径问题的神经分解搜索 

**Authors**: André Hottung, Paula Wong-Chung, Kevin Tierney  

**Link**: [PDF](https://arxiv.org/pdf/2501.03715)  

**Abstract**: Autoregressive construction approaches generate solutions to vehicle routing problems in a step-by-step fashion, leading to high-quality solutions that are nearing the performance achieved by handcrafted, operations research techniques. In this work, we challenge the conventional paradigm of sequential solution construction and introduce an iterative search framework where solutions are instead deconstructed by a neural policy. Throughout the search, the neural policy collaborates with a simple greedy insertion algorithm to rebuild the deconstructed solutions. Our approach surpasses the performance of state-of-the-art operations research methods across three challenging vehicle routing problems of various problem sizes. 

**Abstract (ZH)**: 自回归构建方法逐步骤生成车辆路径问题的解，从而产生接近手工设计和运筹学技术性能的高质量解。本工作挑战了传统的顺序解构建 paradigm，并引入了一种迭代搜索框架，其中解决方案是由神经策略分解的。在整个搜索过程中，神经策略与一个简单的贪心插入算法合作，重新构建分解的解决方案。我们的方法在三个具有不同问题规模的具有挑战性的车辆路径问题上超过了现有最佳的运筹学方法的性能。 

---
# STContext: A Multifaceted Dataset for Developing Context-aware Spatio-temporal Crowd Mobility Prediction Models 

**Title (ZH)**: STContext：一种多维度数据集，用于开发情境感知的时空人群流动性预测模型 

**Authors**: Liyue Chen, Jiangyi Fang, Tengfei Liu, Fangyuan Gao, Leye Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03583)  

**Abstract**: In smart cities, context-aware spatio-temporal crowd flow prediction (STCFP) models leverage contextual features (e.g., weather) to identify unusual crowd mobility patterns and enhance prediction accuracy. However, the best practice for incorporating contextual features remains unclear due to inconsistent usage of contextual features in different papers. Developing a multifaceted dataset with rich types of contextual features and STCFP scenarios is crucial for establishing a principled context modeling paradigm. Existing open crowd flow datasets lack an adequate range of contextual features, which poses an urgent requirement to build a multifaceted dataset to fill these research gaps. To this end, we create STContext, a multifaceted dataset for developing context-aware STCFP models. Specifically, STContext provides nine spatio-temporal datasets across five STCFP scenarios and includes ten contextual features, including weather, air quality index, holidays, points of interest, road networks, etc. Besides, we propose a unified workflow for incorporating contextual features into deep STCFP methods, with steps including feature transformation, dependency modeling, representation fusion, and training strategies. Through extensive experiments, we have obtained several useful guidelines for effective context modeling and insights for future research. The STContext is open-sourced at this https URL. 

**Abstract (ZH)**: 在智慧城市中，基于上下文的空间-时间人群流动预测（STCFP）模型通过利用上下文特征（如天气）来识别不寻常的人群移动模式，从而提升预测准确性。然而，不同论文中上下文特征的使用不一致，使得如何最佳地整合上下文特征的方法仍然不够清晰。为了建立一个基于原则的上下文建模范式，开发包含丰富类型上下文特征和STCFP场景的多维度数据集至关重要。目前的公开人群流动数据集缺乏足够的上下文特征类型，这迫切需要建立一个多维度数据集来填补这些研究空白。为此，我们创建了STContext，一个用于开发上下文感知STCFP模型的多维度数据集。具体而言，STContext提供了覆盖五个STCFP场景的九个空间-时间数据集，并包括十种上下文特征，如天气、空气质量指数、节假日、兴趣点、道路网络等。此外，我们提出了一种统一的工作流，用于将上下文特征整合到深度STCFP方法中，工作流包含特征转换、依赖建模、表示融合和训练策略等步骤。通过广泛实验，我们获得了若干有效上下文建模的指南，并为未来的研究提供了见解。STContext已在以下链接对外开放：[此链接](这个链接请替换为实际链接)。 

---
# SenseRAG: Constructing Environmental Knowledge Bases with Proactive Querying for LLM-Based Autonomous Driving 

**Title (ZH)**: SenseRAG：通过主动查询构建环境知识库以支持基于大语言模型的自动驾驶 

**Authors**: Xuewen Luo, Fan Ding, Fengze Yang, Yang Zhou, Junnyong Loo, Hwa Hui Tew, Chenxi Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03535)  

**Abstract**: This study addresses the critical need for enhanced situational awareness in autonomous driving (AD) by leveraging the contextual reasoning capabilities of large language models (LLMs). Unlike traditional perception systems that rely on rigid, label-based annotations, it integrates real-time, multimodal sensor data into a unified, LLMs-readable knowledge base, enabling LLMs to dynamically understand and respond to complex driving environments. To overcome the inherent latency and modality limitations of LLMs, a proactive Retrieval-Augmented Generation (RAG) is designed for AD, combined with a chain-of-thought prompting mechanism, ensuring rapid and context-rich understanding. Experimental results using real-world Vehicle-to-everything (V2X) datasets demonstrate significant improvements in perception and prediction performance, highlighting the potential of this framework to enhance safety, adaptability, and decision-making in next-generation AD systems. 

**Abstract (ZH)**: 本文通过利用大规模语言模型（LLMs）的上下文推理能力，解决了自动驾驶（AD）中增强态势感知的关键需求。不同于依赖于刚性标签注释的传统感知系统，本文将实时的多模态传感器数据整合进一个统一的、LLMs可读的知识库中，使LLMs能够动态地理解和应对复杂的驾驶环境。为了克服LLMs固有的延迟和模态限制，本文为AD设计了一种前瞻性的检索增强生成（RAG）方法，并结合了一种链式思考提示机制，确保快速且富有上下文的理解。使用实际的车辆到一切（V2X）数据集的实验结果表明，在感知和预测性能方面取得了显著的改进，突显了该框架在提升下一代AD系统的安全性、适应性和决策能力方面的潜力。 

---
# From Aleatoric to Epistemic: Exploring Uncertainty Quantification Techniques in Artificial Intelligence 

**Title (ZH)**: 从偶然性到主观不确定性：探索人工智能中的不确定性量化技术 

**Authors**: Tianyang Wang, Yunze Wang, Jun Zhou, Benji Peng, Xinyuan Song, Charles Zhang, Xintian Sun, Qian Niu, Junyu Liu, Silin Chen, Keyu Chen, Ming Li, Pohsun Feng, Ziqian Bi, Ming Liu, Yichao Zhang, Cheng Fei, Caitlyn Heqi Yin, Lawrence KQ Yan  

**Link**: [PDF](https://arxiv.org/pdf/2501.03282)  

**Abstract**: Uncertainty quantification (UQ) is a critical aspect of artificial intelligence (AI) systems, particularly in high-risk domains such as healthcare, autonomous systems, and financial technology, where decision-making processes must account for uncertainty. This review explores the evolution of uncertainty quantification techniques in AI, distinguishing between aleatoric and epistemic uncertainties, and discusses the mathematical foundations and methods used to quantify these uncertainties. We provide an overview of advanced techniques, including probabilistic methods, ensemble learning, sampling-based approaches, and generative models, while also highlighting hybrid approaches that integrate domain-specific knowledge. Furthermore, we examine the diverse applications of UQ across various fields, emphasizing its impact on decision-making, predictive accuracy, and system robustness. The review also addresses key challenges such as scalability, efficiency, and integration with explainable AI, and outlines future directions for research in this rapidly developing area. Through this comprehensive survey, we aim to provide a deeper understanding of UQ's role in enhancing the reliability, safety, and trustworthiness of AI systems. 

**Abstract (ZH)**: 不确定性量化（UQ）是人工智能（AI）系统的一个关键方面，特别是在医疗保健、自主系统和金融科技等高风险领域中，决策过程中必须考虑到不确定性。本文综述了AI中不确定性量化技术的发展，区分了 aleatoric（统计）不确定性与 epistemic（知识）不确定性，并讨论了量化这些不确定性的数学基础和方法。我们概述了先进的技术，包括概率方法、集成学习、采样方法和生成模型，同时也强调了结合领域特定知识的混合方法。此外，我们探讨了UQ在不同领域的广泛应用，强调其对决策、预测准确性以及系统鲁棒性的影响。本文还讨论了关键挑战，如可扩展性、效率及其与可解释AI的集成，并指出了该快速发展的研究领域的未来方向。通过这一全面的综述，我们旨在提供关于UQ在增强AI系统可靠性、安全性和可信度方面作用的更深入理解。 

---
# Advanced Displacement Magnitude Prediction in Multi-Material Architected Lattice Structure Beams Using Physics Informed Neural Network Architecture 

**Title (ZH)**: 使用物理感知神经网络架构在多材料架构格子结构梁中进行高级位移幅度预测 

**Authors**: Akshansh Mishra  

**Link**: [PDF](https://arxiv.org/pdf/2501.03254)  

**Abstract**: This paper proposes an innovative method for predicting deformation in architected lattice structures that combines Physics-Informed Neural Networks (PINNs) with finite element analysis. A thorough study was carried out on FCC-based lattice beams utilizing five different materials (Structural Steel, AA6061, AA7075, Ti6Al4V, and Inconel 718) under varied edge loads (1000-10000 N). The PINN model blends data-driven learning with physics-based limitations via a proprietary loss function, resulting in much higher prediction accuracy than linear regression. PINN outperforms linear regression, achieving greater R-square (0.7923 vs 0.5686) and lower error metrics (MSE: 0.00017417 vs 0.00036187). Among the materials examined, AA6061 had the highest displacement sensitivity (0.1014 mm at maximum load), while Inconel718 had better structural stability. 

**Abstract (ZH)**: 本文提出了一种将物理信息神经网络（PINNs）与有限元分析相结合的创新方法，用于预测架构晶格结构的变形。在面心立方（FCC）基晶格梁上进行了详尽的研究，采用了五种不同的材料（结构钢、AA6061、AA7075、Ti6Al4V 和 Inconel718），并施加了不同边缘载荷（1000-10000 N）。PINN 模型通过专用的损失函数将数据驱动的学习与基于物理的限制相结合，从而比线性回归显示出更高的预测精度。与线性回归相比，PINN 性能更优，其决定系数 R 平方值更高（0.7923 对比 0.5686），且误差指标更低（均方误差 MSE：0.00017417 对比 0.00036187）。在这几种材料中，AA6061 的位移敏感性最高，在最大载荷下位移为 0.1014 mm，而 Inconel718 则表现出更好的结构稳定性。 

---
# Video-of-Thought: Step-by-Step Video Reasoning from Perception to Cognition 

**Title (ZH)**: 思维视频：从感知到认知的逐步视频推理 

**Authors**: Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Meishan Zhang, Mong-Li Lee, Wynne Hsu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03230)  

**Abstract**: Existing research of video understanding still struggles to achieve in-depth comprehension and reasoning in complex videos, primarily due to the under-exploration of two key bottlenecks: fine-grained spatial-temporal perceptive understanding and cognitive-level video scene comprehension. This paper bridges the gap by presenting a novel solution. We first introduce a novel video Multimodal Large Language Model (MLLM), MotionEpic, which achieves fine-grained pixel-level spatial-temporal video grounding by integrating video spatial-temporal scene graph (STSG) representation. Building upon MotionEpic, we then develop a Video-of-Thought (VoT) reasoning framework. VoT inherits the Chain-of-Thought (CoT) core, breaking down a complex task into simpler and manageable sub-problems, and addressing them step-by-step from a low-level pixel perception to high-level cognitive interpretation. Extensive experiments across various complex video QA benchmarks demonstrate that our overall framework strikingly boosts existing state-of-the-art. To our knowledge, this is the first attempt at successfully implementing the CoT technique for achieving human-level video reasoning, where we show great potential in extending it to a wider range of video understanding scenarios. Project is open at this https URL 

**Abstract (ZH)**: 现有的视频理解研究在实现对复杂视频的深入理解和推理方面仍然面临挑战，主要原因是忽视了两个关键瓶颈：精细化的空间-时间感知理解和认知级别的视频场景理解。本文通过提出一种新颖的解决方案来弥补这一差距。我们首先介绍了一种新颖的视频多模态大型语言模型（MLLM），名为MotionEpic，该模型通过集成视频空间-时间场景图（STSG）表示，实现了精细化的像素级空间-时间视频接地。在此基础上，我们进一步开发了一种视频思维（VoT）推理框架。VoT继承了链式思维（CoT）的核心理念，将复杂任务细分为更简单且可管理的子问题，并从低层次的像素感知逐步过渡到高层次的认知解释。广泛实验结果表明，我们提出的整体框架显著提升了现有最先进的方法。据我们所知，这是首次尝试成功实施CoT技术以实现人类级别的视频推理，在各种复杂的视频问答基准测试中展示了巨大潜力，我们展示了将其扩展到更广泛的视频理解场景的巨大可能性。该项目的代码已开源，可以访问此链接：[请在此处添加链接] 

---
# VLM-driven Behavior Tree for Context-aware Task Planning 

**Title (ZH)**: 基于VLM的上下文感知任务规划行为树 

**Authors**: Naoki Wake, Atsushi Kanehira, Jun Takamatsu, Kazuhiro Sasabuchi, Katsushi Ikeuchi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03968)  

**Abstract**: The use of Large Language Models (LLMs) for generating Behavior Trees (BTs) has recently gained attention in the robotics community, yet remains in its early stages of development. In this paper, we propose a novel framework that leverages Vision-Language Models (VLMs) to interactively generate and edit BTs that address visual conditions, enabling context-aware robot operations in visually complex environments. A key feature of our approach lies in the conditional control through self-prompted visual conditions. Specifically, the VLM generates BTs with visual condition nodes, where conditions are expressed as free-form text. Another VLM process integrates the text into its prompt and evaluates the conditions against real-world images during robot execution. We validated our framework in a real-world cafe scenario, demonstrating both its feasibility and limitations. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）用于生成行为树（BTs）在机器人领域引起了关注，但这一领域仍处于早期发展阶段。本文提出了一种新颖的框架，该框架利用视觉语言模型（VLMs）交互生成和编辑能够处理视觉条件的行为树，从而在视觉复杂环境中实现具有情境感知能力的机器人操作。我们方法的关键特点在于通过自我提示的视觉条件进行条件控制。具体来说，VLM 生成带有视觉条件节点的行为树，其中条件以自由形式的文本表达。另一个 VLM 过程将文本融入其提示中，并在机器人执行过程中针对真实世界的图像评估条件。我们已经在现实世界的咖啡店场景中验证了该框架，展示了其可行性及其局限性。 

---
# Localizing AI: Evaluating Open-Weight Language Models for Languages of Baltic States 

**Title (ZH)**: 本地化人工智能：评估波罗的海国家开源权重语言模型 

**Authors**: Jurgita Kapočiūtė-Dzikienė, Toms Bergmanis, Mārcis Pinnis  

**Link**: [PDF](https://arxiv.org/pdf/2501.03952)  

**Abstract**: Although large language models (LLMs) have transformed our expectations of modern language technologies, concerns over data privacy often restrict the use of commercially available LLMs hosted outside of EU jurisdictions. This limits their application in governmental, defence, and other data-sensitive sectors. In this work, we evaluate the extent to which locally deployable open-weight LLMs support lesser-spoken languages such as Lithuanian, Latvian, and Estonian. We examine various size and precision variants of the top-performing multilingual open-weight models, Llama~3, Gemma~2, Phi, and NeMo, on machine translation, multiple-choice question answering, and free-form text generation. The results indicate that while certain models like Gemma~2 perform close to the top commercially available models, many LLMs struggle with these languages. Most surprisingly, however, we find that these models, while showing close to state-of-the-art translation performance, are still prone to lexical hallucinations with errors in at least 1 in 20 words for all open-weight multilingual LLMs. 

**Abstract (ZH)**: 尽管大规模语言模型（LLMs）已经改变了我们对现代语言技术的期望，但在欧盟司法管辖范围之外托管的商用LLMs的数据隐私问题往往限制了其使用。这限制了它们在政府、国防和其他数据敏感领域中的应用。本研究评估了可本地部署的开放权重LLMs在支持较少使用的语言（如立陶宛语、拉脱维亚语和爱沙尼亚语）方面的程度。我们对表现最佳的多语言开放权重模型Llama~3、Gemma~2、Phi和NeMo的不同大小和精度变体进行了机器翻译、多项选择题问答和自由文本生成的测试。结果表明，虽然某些模型（如Gemma~2）的表现接近商用顶级模型，但许多LLMs在这些语言上表现不佳。然而，出人意料的是，尽管这些模型在翻译性能上接近最先进水平，但所有开放权重多语言LLMs在至少五分之一的词语上仍会出现词级幻觉错误。 

---
# Synthetic Data Privacy Metrics 

**Title (ZH)**: 合成数据隐私度量 

**Authors**: Amy Steier, Lipika Ramaswamy, Andre Manoel, Alexa Haushalter  

**Link**: [PDF](https://arxiv.org/pdf/2501.03941)  

**Abstract**: Recent advancements in generative AI have made it possible to create synthetic datasets that can be as accurate as real-world data for training AI models, powering statistical insights, and fostering collaboration with sensitive datasets while offering strong privacy guarantees. Effectively measuring the empirical privacy of synthetic data is an important step in the process. However, while there is a multitude of new privacy metrics being published every day, there currently is no standardization. In this paper, we review the pros and cons of popular metrics that include simulations of adversarial attacks. We also review current best practices for amending generative models to enhance the privacy of the data they create (e.g. differential privacy). 

**Abstract (ZH)**: 近年来，生成式人工智能的发展使得创建合成数据集成为可能，这些数据集在训练AI模型、提供统计洞察以及使用敏感数据促进协作等方面可以达到与真实世界数据相当的准确性，并且能够提供强大的隐私保障。在合成数据中有效测量实际隐私是这一过程中的一个重要步骤。然而，尽管每天都会有大量的新隐私度量标准被提出，目前仍然缺乏标准化。在本文中，我们将回顾包括模拟对抗性攻击在内的流行度量标准的优点和缺点。我们还将回顾目前增强生成模型以提高所创建数据隐私性的最佳实践（例如差分隐私）。 

---
# Not all tokens are created equal: Perplexity Attention Weighted Networks for AI generated text detection 

**Title (ZH)**: 并非所有词元 đều平等：困惑度加权注意力网络在检测AI生成的文本中的应用 

**Authors**: Pablo Miralles-González, Javier Huertas-Tato, Alejandro Martín, David Camacho  

**Link**: [PDF](https://arxiv.org/pdf/2501.03940)  

**Abstract**: The rapid advancement in large language models (LLMs) has significantly enhanced their ability to generate coherent and contextually relevant text, raising concerns about the misuse of AI-generated content and making it critical to detect it. However, the task remains challenging, particularly in unseen domains or with unfamiliar LLMs. Leveraging LLM next-token distribution outputs offers a theoretically appealing approach for detection, as they encapsulate insights from the models' extensive pre-training on diverse corpora. Despite its promise, zero-shot methods that attempt to operationalize these outputs have met with limited success. We hypothesize that one of the problems is that they use the mean to aggregate next-token distribution metrics across tokens, when some tokens are naturally easier or harder to predict and should be weighted differently. Based on this idea, we propose the Perplexity Attention Weighted Network (PAWN), which uses the last hidden states of the LLM and positions to weight the sum of a series of features based on metrics from the next-token distribution across the sequence length. Although not zero-shot, our method allows us to cache the last hidden states and next-token distribution metrics on disk, greatly reducing the training resource requirements. PAWN shows competitive and even better performance in-distribution than the strongest baselines (fine-tuned LMs) with a fraction of their trainable parameters. Our model also generalizes better to unseen domains and source models, with smaller variability in the decision boundary across distribution shifts. It is also more robust to adversarial attacks, and if the backbone has multilingual capabilities, it presents decent generalization to languages not seen during supervised training, with LLaMA3-1B reaching a mean macro-averaged F1 score of 81.46% in cross-validation with nine languages. 

**Abstract (ZH)**: 大语言模型（LLMs）的快速发展极大地提升了其生成连贯且上下文相关文本的能力，这引发了对AI生成内容滥用的担忧，使其检测变得至关重要。然而，这一任务仍然具有挑战性，尤其是在未见过的领域或未见过的LLM上。利用LLM的下一个标记分布输出提供了一种理论上吸引人的检测方法，因为这些输出包含了模型在大量异构语料上的预训练洞察。尽管这种方法具有潜力，但试图将这些输出操作化的零样本方法取得的成果有限。我们假设其中一个问题是它们使用均值来聚合下一个标记分布度量，而某些标记天然更容易或更难预测，应该赋予不同的权重。基于这一想法，我们提出了 perplexity 注意加权网络（PAWN），它使用LLM的最后隐藏状态和位置来根据序列长度内下一个标记分布的度量加权一系列特征的总和。虽然不是零样本方法，但我们的方法允许我们在硬盘上缓存最后的隐藏状态和下一个标记分布度量，极大地减少了训练资源需求。PAWN在分布同域内的性能与最强基线（微调LM）相当，甚至优于这些基线模型的部分可训练参数。我们的模型在未见过的领域和源模型上表现出更好的泛化能力，决策边界的变异性在分布变化时较小。此外，它对对抗攻击也更加稳健，如果骨干网络具备多语言能力，它也能在监督训练中未见过的语言上表现出良好的泛化能力，例如，LLaMA3-1B在九种语言上的交叉验证中达到了平均宏平均F1分数81.46%。 

---
# Exploring the Potential of Large Language Models in Public Transportation: San Antonio Case Study 

**Title (ZH)**: 探索大型语言模型在公共交通领域的潜力：以圣安东尼奥市为案例的研究 

**Authors**: Ramya Jonnala, Gongbo Liang, Jeong Yang, Izzat Alsmadi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03904)  

**Abstract**: The integration of large language models (LLMs) into public transit systems presents a transformative opportunity to enhance urban mobility. This study explores the potential of LLMs to revolutionize public transportation management within the context of San Antonio's transit system. Leveraging the capabilities of LLMs in natural language processing and data analysis, we investigate their capabilities to optimize route planning, reduce wait times, and provide personalized travel assistance. By utilizing the General Transit Feed Specification (GTFS) and other relevant data, this research aims to demonstrate how LLMs can potentially improve resource allocation, elevate passenger satisfaction, and inform data-driven decision-making in transit operations. A comparative analysis of different ChatGPT models was conducted to assess their ability to understand transportation information, retrieve relevant data, and provide comprehensive responses. Findings from this study suggest that while LLMs hold immense promise for public transit, careful engineering and fine-tuning are essential to realizing their full potential. San Antonio serves as a case study to inform the development of LLM-powered transit systems in other urban environments. 

**Abstract (ZH)**: 将大型语言模型（LLMs）整合到公共交通系统中，为提升城市出行提供了变革性机会。本研究探索了LLMs在圣安东尼奥公共交通系统管理中革新管理的可能性。借助LLMs在自然语言处理和数据分析方面的能力，我们研究了它们优化路线规划、减少等待时间以及提供个性化出行辅助的能力。通过利用通用公共交通数据格式（GTFS）和其他相关数据，本研究旨在证明LLMs如何可能改善资源分配、提升乘客满意度，并促进基于数据的决策制定。对不同ChatGPT模型进行了比较分析，以评估它们理解交通信息、检索相关数据以及提供全面回答的能力。本研究的发现表明，尽管LLMs在公共交通领域具有巨大潜力，但精细的工程设计和调优是实现其全部潜力的关键。圣安东尼奥充当其他城市环境中LLM驱动的公共交通系统开发的案例研究。 

---
# Explainable Reinforcement Learning via Temporal Policy Decomposition 

**Title (ZH)**: 通过时间策略分解实现可解释的强化学习 

**Authors**: Franco Ruggeri, Alessio Russo, Rafia Inam, Karl Henrik Johansson  

**Link**: [PDF](https://arxiv.org/pdf/2501.03902)  

**Abstract**: We investigate the explainability of Reinforcement Learning (RL) policies from a temporal perspective, focusing on the sequence of future outcomes associated with individual actions. In RL, value functions compress information about rewards collected across multiple trajectories and over an infinite horizon, allowing a compact form of knowledge representation. However, this compression obscures the temporal details inherent in sequential decision-making, presenting a key challenge for interpretability. We present Temporal Policy Decomposition (TPD), a novel explainability approach that explains individual RL actions in terms of their Expected Future Outcome (EFO). These explanations decompose generalized value functions into a sequence of EFOs, one for each time step up to a prediction horizon of interest, revealing insights into when specific outcomes are expected to occur. We leverage fixed-horizon temporal difference learning to devise an off-policy method for learning EFOs for both optimal and suboptimal actions, enabling contrastive explanations consisting of EFOs for different state-action pairs. Our experiments demonstrate that TPD generates accurate explanations that (i) clarify the policy's future strategy and anticipated trajectory for a given action and (ii) improve understanding of the reward composition, facilitating fine-tuning of the reward function to align with human expectations. 

**Abstract (ZH)**: 我们从时间维度上探究强化学习（RL）策略的可解释性，重点关注与个体行动相关的未来结果序列。在RL中，价值函数通过压缩来自多个轨迹并在无限时限内收集的奖励信息，实现知识表示的紧凑形式。然而，这种压缩隐藏了顺序决策中固有的时间细节，这是可解释性中的一个关键挑战。我们提出了一种新的解释方法——时间策略分解（TPD），这种方法根据其预期未来结果（EFO）来解释个体RL行动。这些解释将概括性价值函数分解为一系列EFO，每一项对应的是一系列时间步，直到感兴趣的预测时限，揭示了特定结果预期发生的时间点。我们利用固定时限的时间差分学习，设计了一种用于学习最优和次优行动的EFO的离策方法，从而能够对不同的状态-行动对提供对比式的解释。我们的实验表明，TPD生成了准确的解释，这些解释能够（i）阐明给定行动的策略及其预期轨迹，并（ii）提高对奖励结构的理解，从而有助于更精细地调整奖励函数，使其与人类期望一致。 

---
# LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token 

**Title (ZH)**: LLaVA-Mini：高效的一视窗大规模多模态模型 

**Authors**: Shaolei Zhang, Qingkai Fang, Zhe Yang, Yang Feng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03895)  

**Abstract**: The advent of real-time large multimodal models (LMMs) like GPT-4o has sparked considerable interest in efficient LMMs. LMM frameworks typically encode visual inputs into vision tokens (continuous representations) and integrate them and textual instructions into the context of large language models (LLMs), where large-scale parameters and numerous context tokens (predominantly vision tokens) result in substantial computational overhead. Previous efforts towards efficient LMMs always focus on replacing the LLM backbone with smaller models, while neglecting the crucial issue of token quantity. In this paper, we introduce LLaVA-Mini, an efficient LMM with minimal vision tokens. To achieve a high compression ratio of vision tokens while preserving visual information, we first analyze how LMMs understand vision tokens and find that most vision tokens only play a crucial role in the early layers of LLM backbone, where they mainly fuse visual information into text tokens. Building on this finding, LLaVA-Mini introduces modality pre-fusion to fuse visual information into text tokens in advance, thereby facilitating the extreme compression of vision tokens fed to LLM backbone into one token. LLaVA-Mini is a unified large multimodal model that can support the understanding of images, high-resolution images, and videos in an efficient manner. Experiments across 11 image-based and 7 video-based benchmarks demonstrate that LLaVA-Mini outperforms LLaVA-v1.5 with just 1 vision token instead of 576. Efficiency analyses reveal that LLaVA-Mini can reduce FLOPs by 77%, deliver low-latency responses within 40 milliseconds, and process over 10,000 frames of video on the GPU hardware with 24GB of memory. 

**Abstract (ZH)**: 实时大规模多模态模型（LMMs）如GPT-4o的出现引起了人们对高效LMMs的兴趣。LMM框架通常将视觉输入编码为视觉标记（连续表示），并将它们与文本指令整合进大型语言模型（LLMs）的上下文中，其中大规模参数和大量上下文标记（主要是视觉标记）导致了显著的计算开销。以往针对高效LMMs的努力主要集中于用较小的模型替换LLM主干，而忽视了标记数量的关键问题。在本文中，我们提出了LLaVA-Mini，这是一种具有最小视觉标记的高效LMM。为了在保持视觉信息的同时实现视觉标记的高压缩比，我们首先分析了LMMs如何理解视觉标记，并发现大多数视觉标记主要在LLM主干的早期层中起关键作用，在此过程中，它们主要将视觉信息融合到文本标记中。基于这一发现，LLaVA-Mini 引入了模态前融合，提前将视觉信息融合到文本标记中，从而实现了向LLM主干提供的视觉标记极端压缩到一个标记。LLaVA-Mini 是一个统一的大规模多模态模型，可以高效地支持对图像、高分辨率图像和视频的理解。在11个基于图像和7个基于视频的基准测试中进行的实验表明，与使用576个视觉标记的LLaVA-v1.5相比，仅使用1个视觉标记的LLaVA-Mini表现出色。效率分析表明，LLaVA-Mini 可以将FLOPs减少77%，在40毫秒内提供低延迟响应，并在具有24GB内存的GPU硬件上处理超过10,000帧的视频。 

---
# CL3DOR: Contrastive Learning for 3D Large Multimodal Models via Odds Ratio on High-Resolution Point Clouds 

**Title (ZH)**: CL3DOR：基于高分辨率点云上的优势比对比学习的大规模多模态3D模型 

**Authors**: Keonwoo Kim, Yeongjae Cho, Taebaek Hwang, Minsoo Jo, Sangdo Han  

**Link**: [PDF](https://arxiv.org/pdf/2501.03879)  

**Abstract**: Recent research has demonstrated that Large Language Models (LLMs) are not limited to text-only tasks but can also function as multimodal models across various modalities, including audio, images, and videos. In particular, research on 3D Large Multimodal Models (3D LMMs) is making notable strides, driven by the potential of processing higher-dimensional data like point clouds. However, upon closer examination, we find that the visual and textual content within each sample of existing training datasets lacks both high informational granularity and clarity, which serve as a bottleneck for precise cross-modal understanding. To address these issues, we propose CL3DOR, Contrastive Learning for 3D large multimodal models via Odds ratio on high-Resolution point clouds, designed to ensure greater specificity and clarity in both visual and textual content. Specifically, we increase the density of point clouds per object and construct informative hard negative responses in the training dataset to penalize unwanted responses. To leverage hard negative responses, we incorporate the odds ratio as an auxiliary term for contrastive learning into the conventional language modeling loss. CL3DOR achieves state-of-the-art performance in 3D scene understanding and reasoning benchmarks. Additionally, we demonstrate the effectiveness of CL3DOR's key components through extensive experiments. 

**Abstract (ZH)**: 近年来的研究表明，大型语言模型（LLMs）不仅局限于文本任务，还可以作为多种模态模型在音频、图像和视频等各种模态中发挥作用。特别是，关于3D大型多模态模型（3D LMMs）的研究已经取得了显著进展，这得益于处理高维度数据（如点云）的潜力。然而，进一步观察发现，现有训练数据集中每个样本中的视觉和文本内容缺乏高的信息粒度和清晰度，这成为实现精确跨模态理解的瓶颈。为了解决这些问题，我们提出了CL3DOR——一种基于点云高分辨率的似然比对比学习方法，旨在提高视觉和文本内容的特异性和清晰度。具体而言，我们增加了每个对象的点云密度，并在训练数据集中构建了信息性的“硬负样本”响应，以削弱不希望得到的响应。为了利用这些“硬负样本”响应，我们将似然比引入传统的语言建模损失中作为辅助项进行对比学习。CL3DOR在3D场景理解和推理基准测试中实现了最先进的性能。此外，我们通过广泛的实验展示了CL3DOR关键组件的有效性。 

---
# Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control 

**Title (ZH)**: 作为着色器的扩散：面向3D的视频扩散技术以实现多功能视频生成控制 

**Authors**: Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03847)  

**Abstract**: Diffusion models have demonstrated impressive performance in generating high-quality videos from text prompts or images. However, precise control over the video generation process, such as camera manipulation or content editing, remains a significant challenge. Existing methods for controlled video generation are typically limited to a single control type, lacking the flexibility to handle diverse control demands. In this paper, we introduce Diffusion as Shader (DaS), a novel approach that supports multiple video control tasks within a unified architecture. Our key insight is that achieving versatile video control necessitates leveraging 3D control signals, as videos are fundamentally 2D renderings of dynamic 3D content. Unlike prior methods limited to 2D control signals, DaS leverages 3D tracking videos as control inputs, making the video diffusion process inherently 3D-aware. This innovation allows DaS to achieve a wide range of video controls by simply manipulating the 3D tracking videos. A further advantage of using 3D tracking videos is their ability to effectively link frames, significantly enhancing the temporal consistency of the generated videos. With just 3 days of fine-tuning on 8 H800 GPUs using less than 10k videos, DaS demonstrates strong control capabilities across diverse tasks, including mesh-to-video generation, camera control, motion transfer, and object manipulation. 

**Abstract (ZH)**: 扩散模型在从文本提示或图像生成高质量视频方面已经展示了令人印象深刻的性能。然而，精确控制视频生成过程，例如相机操作或内容编辑，仍然是一个重大的挑战。现有可控视频生成的方法通常仅限于单一类型的控制，缺乏处理多样化控制需求的灵活性。本文介绍了一种新的方法——以扩散为着色器（Diffusion as Shader，简称DaS），该方法在一个统一架构中支持多种视频控制任务。我们得出的关键见解是，实现多功能的视频控制需要利用三维控制信号，因为视频本质上是动态三维内容的二维渲染。与之前仅限于二维控制信号的方法不同，DaS 使用三维跟踪视频作为控制输入，使视频扩散过程本质上具有三维意识。这一创新使得DaS 仅通过操控三维跟踪视频就可以实现广泛的视频控制。使用三维跟踪视频的另一个优势是，它们能够有效地链接帧，显著提高了生成视频的时间一致性。通过在8块H800 GPU上进行不到三天的微调，使用不到10,000个视频，DaS 在多种任务中展示了强大的控制能力，包括网格到视频的生成、相机控制、运动转移和对象操作。 

---
# SCC-YOLO: An Improved Object Detector for Assisting in Brain Tumor Diagnosis 

**Title (ZH)**: SCC-YOLO：一种改进的物体检测器，用于辅助脑肿瘤诊断 

**Authors**: Runci Bai  

**Link**: [PDF](https://arxiv.org/pdf/2501.03836)  

**Abstract**: Brain tumors can result in neurological dysfunction, alterations in cognitive and psychological states, increased intracranial pressure, and the occurrence of seizures, thereby presenting a substantial risk to human life and health. The You Only Look Once(YOLO) series models have demonstrated superior accuracy in object detection for medical imaging. In this paper, we develop a novel SCC-YOLO architecture by integrating the SCConv attention mechanism into YOLOv9. The SCConv module reconstructs an efficient convolutional module by reducing spatial and channel redundancy among features, thereby enhancing the learning of image features. We investigate the impact of intergrating different attention mechanisms with the YOLOv9 model on brain tumor image detection using both the Br35H dataset and our self-made dataset(Brain_Tumor_Dataset). Experimental results show that on the Br35H dataset, SCC-YOLO achieved a 0.3% improvement in mAp50 compared to YOLOv9, while on our self-made dataset, SCC-YOLO exhibited a 0.5% improvement over YOLOv9. SCC-YOLO has reached state-of-the-art performance in brain tumor detection. Source code is available at : this https URL 

**Abstract (ZH)**: 脑肿瘤可能导致神经功能障碍、认知和心理状态改变、颅内压升高，以及癫痫发作，从而对人类生命和健康构成重大风险。You Only Look Once (YOLO) 系列模型已经在医学影像中的目标检测方面展示了卓越的准确性。在本文中，我们通过将 SCConv 注意机制整合到 YOLOv9 中，开发了一种新颖的 SCC-YOLO 架构。SCConv 模块通过减少特征间的空间和通道冗余来重构一个高效的卷积模块，从而增强图像特征的学习。我们使用 Br35H 数据集和我们自制的数据集（Brain_Tumor_Dataset）对将不同注意力机制与 YOLOv9 模型结合使用对脑肿瘤图像检测的影响进行了研究。实验结果显示，与 YOLOv9 相比，SCC-YOLO 在 Br35H 数据集上的 mAp50 提高了 0.3%，而在我们自制的数据集上则提高了 0.5%。SCC-YOLO 在脑肿瘤检测方面达到了当前最先进水平。源代码可在以下链接获取：this https URL 

---
# TACLR: A Scalable and Efficient Retrieval-based Method for Industrial Product Attribute Value Identification 

**Title (ZH)**: TACLR：一种可扩展且高效的基于检索的方法，用于工业产品属性值识别 

**Authors**: Yindu Su, Huike Zou, Lin Sun, Ting Zhang, Haiyang Yang, Liyu Chen, David Lo, Qingheng Zhang, Shuguang Han, Jufeng Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.03835)  

**Abstract**: Product Attribute Value Identification (PAVI) involves identifying attribute values from product profiles, a key task for improving product search, recommendations, and business analytics on e-commerce platforms. However, existing PAVI methods face critical challenges, such as inferring implicit values, handling out-of-distribution (OOD) values, and producing normalized outputs. To address these limitations, we introduce Taxonomy-Aware Contrastive Learning Retrieval (TACLR), the first retrieval-based method for PAVI. TACLR formulates PAVI as an information retrieval task by encoding product profiles and candidate values into embeddings and retrieving values based on their similarity to the item embedding. It leverages contrastive training with taxonomy-aware hard negative sampling and employs adaptive inference with dynamic thresholds. TACLR offers three key advantages: (1) it effectively handles implicit and OOD values while producing normalized outputs; (2) it scales to thousands of categories, tens of thousands of attributes, and millions of values; and (3) it supports efficient inference for high-load industrial scenarios. Extensive experiments on proprietary and public datasets validate the effectiveness and efficiency of TACLR. Moreover, it has been successfully deployed in a real-world e-commerce platform, processing millions of product listings daily while supporting dynamic, large-scale attribute taxonomies. 

**Abstract (ZH)**: 产品属性值识别（PAVI）涉及从产品描述中识别属性值，这是提高电子商务平台上产品搜索、推荐和商业分析的关键任务。然而，现有的PAVI方法面临着严峻的挑战，如推断隐含值、处理未见过域（OOD）值以及生成归一化输出。为了解决这些局限性，我们引入了基于检索的Taxonomy-Aware Contrastive Learning Retrieval (TACLR)，这是首个针对PAVI的检索方法。TACLR将PAVI表述为信息检索任务，通过对产品描述和候选值进行编码，并基于与项目嵌入的相似性检索值。该方法采用基于分类税则的对比训练和困难负样本，并采用适应性推理和动态阈值。TACLR具有三个关键优势：（1）它有效处理隐含值和OOD值，并生成归一化输出；（2）它能够扩展到数千个类别、数十万个属性和数百万个值；（3）它支持高负载工业场景下的高效推理。广泛的实验表明，TACLR在有效性和效率方面都表现出色，并且已在真实的电子商务平台上成功部署，每日处理数百万个产品列表，同时支持动态和大规模的属性分类。 

---
# Three-dimensional attention Transformer for state evaluation in real-time strategy games 

**Title (ZH)**: 实时策略游戏中基于三维注意力变换器的状态评估 

**Authors**: Yanqing Ye, Weilong Yang, Kai Qiu, Jie Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03832)  

**Abstract**: Situation assessment in Real-Time Strategy (RTS) games is crucial for understanding decision-making in complex adversarial environments. However, existing methods remain limited in processing multi-dimensional feature information and temporal dependencies. Here we propose a tri-dimensional Space-Time-Feature Transformer (TSTF Transformer) architecture, which efficiently models battlefield situations through three independent but cascaded modules: spatial attention, temporal attention, and feature attention. On a dataset comprising 3,150 adversarial experiments, the 8-layer TSTF Transformer demonstrates superior performance: achieving 58.7% accuracy in the early game (~4% progress), significantly outperforming the conventional Timesformer's 41.8%; reaching 97.6% accuracy in the mid-game (~40% progress) while maintaining low performance variation (standard deviation 0.114). Meanwhile, this architecture requires fewer parameters (4.75M) compared to the baseline model (5.54M). Our study not only provides new insights into situation assessment in RTS games but also presents an innovative paradigm for Transformer-based multi-dimensional temporal modeling. 

**Abstract (ZH)**: 在即时战略（RTS）游戏中，态势评估对于理解在复杂对抗环境中的决策至关重要。然而，现有的方法在处理多维特征信息和时间依赖性方面仍然有限。在这里，我们提出了一个三维空间-时间-特征变换器（Tri- dimensional Space-Time-Feature Transformer, TSTF Transformer）架构，该架构通过三个独立但相互连接的模块高效地建模战场态势：空间注意力、时间注意力和特征注意力。在包含3150个对抗实验的数据集上，8层TSTF Transformer展示了卓越的性能：在游戏初期（约4%进度）准确率达到58.7%，显著优于传统TimeSformer的41.8%；在游戏中期（约40%进度）准确率达到97.6%，同时保持低性能波动（标准偏差0.114）。同时，该架构所需的参数数量（4.75M）比基线模型（5.54M）少。我们的研究表明，不仅为RTS游戏中的态势评估提供了新的见解，还为基于Transformer的多维时间建模提出了创新的范式。 

---
# Deep Sylvester Posterior Inference for Adaptive Compressed Sensing in Ultrasound Imaging 

**Title (ZH)**: 深度塞尔维斯特后验推断在超声成像中自适应压缩感知的应用 

**Authors**: Simon W. Penninga, Hans van Gorp, Ruud J.G. van Sloun  

**Link**: [PDF](https://arxiv.org/pdf/2501.03825)  

**Abstract**: Ultrasound images are commonly formed by sequential acquisition of beam-steered scan-lines. Minimizing the number of required scan-lines can significantly enhance frame rate, field of view, energy efficiency, and data transfer speeds. Existing approaches typically use static subsampling schemes in combination with sparsity-based or, more recently, deep-learning-based recovery. In this work, we introduce an adaptive subsampling method that maximizes intrinsic information gain in-situ, employing a Sylvester Normalizing Flow encoder to infer an approximate Bayesian posterior under partial observation in real-time. Using the Bayesian posterior and a deep generative model for future observations, we determine the subsampling scheme that maximizes the mutual information between the subsampled observations, and the next frame of the video. We evaluate our approach using the EchoNet cardiac ultrasound video dataset and demonstrate that our active sampling method outperforms competitive baselines, including uniform and variable-density random sampling, as well as equidistantly spaced scan-lines, improving mean absolute reconstruction error by 15%. Moreover, posterior inference and the sampling scheme generation are performed in just 0.015 seconds (66Hz), making it fast enough for real-time 2D ultrasound imaging applications. 

**Abstract (ZH)**: 超声图像通常通过顺序获取扫描线来形成。减少所需的扫描线数量可以显著提高帧率、视野、能量效率和数据传输速度。现有方法通常使用静态子抽样方案，结合稀疏恢复或最近的深度学习恢复方法。在这项工作中，我们引入了一种自适应子抽样方法，能够在获取过程中最大化内在信息增益，采用Sylvester正规范形编码器在部分观察下实时推断近似贝叶斯后验概率。通过贝叶斯后验概率和一个用于未来观察的深度生成模型，我们确定了能够最大化子采样观测与视频下一帧之间互信息的子抽样方案。我们使用回声网心脏超声视频数据集对我们的方法进行了评估，并证明了我们的主动采样方法在均方绝对重建误差上比竞争基线（包括均匀和可变密度随机采样，以及等间距扫描线）提高了15%。此外，后验概率推断和采样方案生成仅需0.015秒（66Hz），使其足以适用于实时2D超声成像应用。 

---
# Self-Adaptive ERP: Embedding NLP into Petri-Net creation and Model Matching 

**Title (ZH)**: 自适应企业资源规划系统：将自然语言处理嵌入Petri网构建与模型匹配 

**Authors**: Ahmed Maged, Gamal Kassem  

**Link**: [PDF](https://arxiv.org/pdf/2501.03795)  

**Abstract**: Enterprise Resource Planning (ERP) consultants play a vital role in customizing systems to meet specific business needs by processing large amounts of data and adapting functionalities. However, the process is resource-intensive, time-consuming, and requires continuous adjustments as business demands evolve. This research introduces a Self-Adaptive ERP Framework that automates customization using enterprise process models and system usage analysis. It leverages Artificial Intelligence (AI) & Natural Language Processing (NLP) for Petri nets to transform business processes into adaptable models, addressing both structural and functional matching. The framework, built using Design Science Research (DSR) and a Systematic Literature Review (SLR), reduces reliance on manual adjustments, improving ERP customization efficiency and accuracy while minimizing the need for consultants. 

**Abstract (ZH)**: 企业资源规划（ERP）咨询师在通过处理大量数据和调整功能来定制系统以满足特定业务需求方面发挥着关键作用。然而，这一过程资源密集、耗时，并且需要随着业务需求的变化而持续调整。本研究引入了一种自适应ERP框架，该框架利用企业流程模型和系统使用分析自动完成定制。该框架利用人工智能（AI）和自然语言处理（NLP）将Petri网转化为可适应的模型，以解决结构和功能匹配问题。该框架采用设计科学方法研究（Design Science Research, DSR）和系统文献综述（Systematic Literature Review, SLR）开发，减少了对手动调整的依赖，提高了ERP定制的效率和准确性，同时减少了对咨询师的需求。 

---
# SelectiveFinetuning: Enhancing Transfer Learning in Sleep Staging through Selective Domain Alignment 

**Title (ZH)**: 选择性微调：通过选择性领域对齐增强睡眠阶段划分中的迁移学习 

**Authors**: Siyuan Zhao, Chenyu Liu, Yi Ding, Xinliang Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2501.03764)  

**Abstract**: In practical sleep stage classification, a key challenge is the variability of EEG data across different subjects and environments. Differences in physiology, age, health status, and recording conditions can lead to domain shifts between data. These domain shifts often result in decreased model accuracy and reliability, particularly when the model is applied to new data with characteristics different from those it was originally trained on, which is a typical manifestation of negative transfer. To address this, we propose SelectiveFinetuning in this paper. Our method utilizes a pretrained Multi Resolution Convolutional Neural Network (MRCNN) to extract EEG features, capturing the distinctive characteristics of different sleep stages. To mitigate the effect of domain shifts, we introduce a domain aligning mechanism that employs Earth Mover Distance (EMD) to evaluate and select source domain data closely matching the target domain. By finetuning the model with selective source data, our SelectiveFinetuning enhances the model's performance on target domain that exhibits domain shifts compared to the data used for training. Experimental results show that our method outperforms existing baselines, offering greater robustness and adaptability in practical scenarios where data distributions are often unpredictable. 

**Abstract (ZH)**: 在实际的睡眠阶段分类中，一个关键挑战是不同受试者和环境下的EEG数据的变异性。生理差异、年龄、健康状况和记录条件的不同可能导致数据领域之间的转换。这些领域转换往往会导致模型的准确性和可靠性降低，尤其是在将模型应用于之前未见过的数据时更为明显，这是负迁移的一种典型表现。为了解决这个问题，本文提出了SelectiveFinetuning方法。我们的方法利用预训练的多分辨率卷积神经网络（MRCNN）提取EEG特征，捕捉不同睡眠阶段的独特特征。为减轻领域转换的影响，我们引入了一种领域对齐机制，利用Wasserstein距离（EMD）评估和选择与目标领域匹配度高的源领域数据。通过使用选择性源数据微调模型，SelectiveFinetuning方法能够提升在表现出领域转换的目标领域中的模型性能，相比用于训练的数据。实验结果表明，我们的方法在现有基线方法中表现出更出色的鲁棒性和适应性，在数据分布往往不可预测的实际场景中尤为显著。 

---
# Self-adaptive vision-language model for 3D segmentation of pulmonary artery and vein 

**Title (ZH)**: 自适应视觉-语言模型在肺动脉和静脉的三维分割中的应用 

**Authors**: Xiaotong Guo, Deqian Yang, Dan Wang, Haochen Zhao, Yuan Li, Zhilin Sui, Tao Zhou, Lijun Zhang, Yanda Meng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03722)  

**Abstract**: Accurate segmentation of pulmonary structures iscrucial in clinical diagnosis, disease study, and treatment planning. Significant progress has been made in deep learning-based segmentation techniques, but most require much labeled data for training. Consequently, developing precise segmentation methods that demand fewer labeled datasets is paramount in medical image analysis. The emergence of pre-trained vision-language foundation models, such as CLIP, recently opened the door for universal computer vision tasks. Exploiting the generalization ability of these pre-trained foundation models on downstream tasks, such as segmentation, leads to unexpected performance with a relatively small amount of labeled data. However, exploring these models for pulmonary artery-vein segmentation is still limited. This paper proposes a novel framework called Language-guided self-adaptive Cross-Attention Fusion Framework. Our method adopts pre-trained CLIP as a strong feature extractor for generating the segmentation of 3D CT scans, while adaptively aggregating the cross-modality of text and image representations. We propose a s pecially designed adapter module to fine-tune pre-trained CLIP with a self-adaptive learning strategy to effectively fuse the two modalities of embeddings. We extensively validate our method on a local dataset, which is the largest pulmonary artery-vein CT dataset to date and consists of 718 labeled data in total. The experiments show that our method outperformed other state-of-the-art methods by a large margin. Our data and code will be made publicly available upon acceptance. 

**Abstract (ZH)**: 准确的肺部结构分割对于临床诊断、疾病研究和治疗计划至关重要。基于深度学习的分割技术取得了显著进展，但大多数方法需要大量的标注数据进行训练。因此，开发少标注数据需求的精确分割方法在医学图像分析中至关重要。近年来，预训练的跨模态基础模型，如CLIP，的出现为通用计算机视觉任务打开了大门。利用这些预训练基础模型在下游任务，如分割中的泛化能力，可以取得相对较小的标注数据量但令人惊讶的性能。然而，探索这些模型用于肺动脉-静脉分割仍然有限。本文提出了一种名为语言引导自适应交叉注意力融合框架的新框架。我们的方法采用预训练的CLIP作为强特征提取器，用于生成3D CT扫描的分割结果，并自适应地聚合文本和图像表示的跨模态信息。我们提出了一种特别设计的适配器模块，使用自适应学习策略微调预训练的CLIP，以有效融合两种嵌入表示。我们广泛验证了该方法，使用目前最大的肺动脉-静脉CT数据集进行验证，该数据集包含718个标注数据。实验结果显示，该方法在所有当前最先进的方法中表现出了显著的优势。论文的数据和代码将在接受后公开提供。 

---
# Materialist: Physically Based Editing Using Single-Image Inverse Rendering 

**Title (ZH)**: 材料主义：基于物理的单图像逆渲染编辑 

**Authors**: Lezhong Wang, Duc Minh Tran, Ruiqi Cui, Thomson TG, Manmohan Chandraker, Jeppe Revall Frisvad  

**Link**: [PDF](https://arxiv.org/pdf/2501.03717)  

**Abstract**: To perform image editing based on single-view, inverse physically based rendering, we present a method combining a learning-based approach with progressive differentiable rendering. Given an image, our method leverages neural networks to predict initial material properties. Progressive differentiable rendering is then used to optimize the environment map and refine the material properties with the goal of closely matching the rendered result to the input image. We require only a single image while other inverse rendering methods based on the rendering equation require multiple views. In comparison to single-view methods that rely on neural renderers, our approach achieves more realistic light material interactions, accurate shadows, and global illumination. Furthermore, with optimized material properties and illumination, our method enables a variety of tasks, including physically based material editing, object insertion, and relighting. We also propose a method for material transparency editing that operates effectively without requiring full scene geometry. Compared with methods based on Stable Diffusion, our approach offers stronger interpretability and more realistic light refraction based on empirical results. 

**Abstract (ZH)**: 基于单视角的逆物理渲染图像编辑，我们提出了一种结合基于学习的方法与分步可微渲染的方法。给定一张图像，我们的方法利用神经网络预测初始材质属性。随后，采用分步可微渲染对环境贴图进行优化，并根据目标不断细化材质属性，力求使渲染结果与输入图像高度一致。与其他基于辐射度方程的多视图逆渲染方法相比，我们仅需要一张图像即可完成任务。相比于依赖神经渲染器的单视角方法，我们的方法实现了更逼真的光照材质交互、更准确的阴影以及全局光照效果。通过优化材质属性和照明条件，我们的方法可用于物理基础材质编辑、物体插入和重新照明等多种任务。此外，我们还提出了一种用于材质透明度编辑的方法，该方法在不需要完整场景几何的情况下也能有效工作。实验结果表明，与基于Stable Diffusion的方法相比，我们的方法更具可解释性，并且基于实证结果能够提供更加逼真的光折射效果。 

---
# Unsupervised Speech Segmentation: A General Approach Using Speech Language Models 

**Title (ZH)**: 无监督语音分割：使用语音语言模型的通用方法 

**Authors**: Avishai Elmakies, Omri Abend, Yossi Adi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03711)  

**Abstract**: In this paper, we introduce an unsupervised approach for Speech Segmentation, which builds on previously researched approaches, e.g., Speaker Diarization, while being applicable to an inclusive set of acoustic-semantic distinctions, paving a path towards a general Unsupervised Speech Segmentation approach. Unlike traditional speech and audio segmentation, which mainly focuses on spectral changes in the input signal, e.g., phone segmentation, our approach tries to segment the spoken utterance into chunks with differing acoustic-semantic styles, focusing on acoustic-semantic information that does not translate well into text, e.g., emotion or speaker. While most Speech Segmentation tasks only handle one style change, e.g., emotion diarization, our approach tries to handle multiple acoustic-semantic style changes. Leveraging recent advances in Speech Language Models (SLMs), we propose a simple unsupervised method to segment a given speech utterance. We empirically demonstrate the effectiveness of the proposed approach by considering several setups. Results suggest that the proposed method is superior to the evaluated baselines on boundary detection, segment purity, and over-segmentation. Code is available at this https URL. 

**Abstract (ZH)**: 本文介绍了一种无监督的语音分割方法，该方法借鉴了先前研究的方法，如说话人聚类（Speaker Diarization），同时适用于一系列声学-语义区分，为通用的无监督语音分割方法铺平了道路。与传统的语音和音频分割主要关注输入信号的频谱变化，例如音素分割不同，我们的方法尝试将口头陈述分割成具有不同声学-语义风格的片段，重点关注难以转换为文本的声学-语义信息，例如情绪或说话人。大多数语音分割任务仅处理一种风格变化，例如情绪聚类，而我们的方法试图处理多种声学-语义风格变化。利用近期在语音语言模型（Speech Language Models, SLMs）方面的进展，我们提出了一种简单的无监督方法来分割给定的语音片段。通过考虑多种实验设置，我们实证证明了所提出方法的有效性。结果表明，所提出的方法在边界检测、片段纯净度和过度分割方面优于评估的基线方法。代码可通过以下链接获得：this https URL。 

---
# AuxDepthNet: Real-Time Monocular 3D Object Detection with Depth-Sensitive Features 

**Title (ZH)**: AuxDepthNet：具有深度敏感特征的实时单目三维对象检测 

**Authors**: Ruochen Zhang, Hyeung-Sik Choi, Dongwook Jung, Phan Huy Nam Anh, Sang-Ki Jeong, Zihao Zhu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03700)  

**Abstract**: Monocular 3D object detection is a challenging task in autonomous systems due to the lack of explicit depth information in single-view images. Existing methods often depend on external depth estimators or expensive sensors, which increase computational complexity and hinder real-time performance. To overcome these limitations, we propose AuxDepthNet, an efficient framework for real-time monocular 3D object detection that eliminates the reliance on external depth maps or pre-trained depth models. AuxDepthNet introduces two key components: the Auxiliary Depth Feature (ADF) module, which implicitly learns depth-sensitive features to improve spatial reasoning and computational efficiency, and the Depth Position Mapping (DPM) module, which embeds depth positional information directly into the detection process to enable accurate object localization and 3D bounding box regression. Leveraging the DepthFusion Transformer architecture, AuxDepthNet globally integrates visual and depth-sensitive features through depth-guided interactions, ensuring robust and efficient detection. Extensive experiments on the KITTI dataset show that AuxDepthNet achieves state-of-the-art performance, with $\text{AP}_{3D}$ scores of 24.72\% (Easy), 18.63\% (Moderate), and 15.31\% (Hard), and $\text{AP}_{\text{BEV}}$ scores of 34.11\% (Easy), 25.18\% (Moderate), and 21.90\% (Hard) at an IoU threshold of 0.7. 

**Abstract (ZH)**: 单目3D物体检测是自主系统中的一个具有挑战性的任务，因为单视图图像缺少显式的深度信息。现有方法通常依赖于外部深度估计器或昂贵的传感器，这增加了计算复杂度并阻碍了实时性能。为克服这些局限，我们提出了一种高效框架——AuxDepthNet，该框架能够在实时条件下进行单目3D物体检测，并消除了对外部深度图或预训练深度模型的依赖。AuxDepthNet 引入了两个关键组件：辅助深度特征（ADF）模块，该模块隐式学习深度敏感特征以提高空间推理能力和计算效率；深度位置映射（DPM）模块，该模块直接将深度位置信息嵌入到检测过程中，以实现准确的物体定位和3D边框回归。利用DepthFusion Transformer 架构，AuxDepthNet 通过深度引导的交互全局整合了视觉和深度敏感特征，确保了稳健且高效的检测。在KITTI数据集上的广泛实验表明，AuxDepthNet 达到了最先进的性能，其中3D检测（$\text{AP}_{3D}$）分数在 Easy、Moderate 和 Hard 情况下分别为 24.72%、18.63% 和 15.31%，贝叶斯逆透视视角检测（$\text{AP}_{\text{BEV}}$）分数在 0.7 的 IoU 阈值下分别为 34.11%、25.18% 和 21.90%。 

---
# Exploring Molecule Generation Using Latent Space Graph Diffusion 

**Title (ZH)**: 探索使用潜在空间图扩散进行分子生成 

**Authors**: Prashanth Pombala, Gerrit Grossmann, Verena Wolf  

**Link**: [PDF](https://arxiv.org/pdf/2501.03696)  

**Abstract**: Generating molecular graphs is a challenging task due to their discrete nature and the competitive objectives involved. Diffusion models have emerged as SOTA approaches in data generation across various modalities. For molecular graphs, graph neural networks (GNNs) as a diffusion backbone have achieved impressive results. Latent space diffusion, where diffusion occurs in a low-dimensional space via an autoencoder, has demonstrated computational efficiency. However, the literature on latent space diffusion for molecular graphs is scarce, and no commonly accepted best practices exist. In this work, we explore different approaches and hyperparameters, contrasting generative flow models (denoising diffusion, flow matching, heat dissipation) and architectures (GNNs and E(3)-equivariant GNNs). Our experiments reveal a high sensitivity to the choice of approach and design decisions. Code is made available at this http URL. 

**Abstract (ZH)**: 生成分子图是一项具有挑战性的任务，因为它们具有离散性质且涉及竞争性目标。扩散模型已成为多种模态数据生成的SOTA（当前最佳）方法。对于分子图而言，图神经网络（GNNs）作为扩散模型的基础骨架已经取得了显著的成果。在潜在空间扩散中，通过自动编码器在低维空间中进行扩散，已经展示了计算效率。然而，有关分子图潜在空间扩散的文献较为稀缺，并且尚未有广为接受的最佳实践。在本文中，我们探索了不同的方法和超参数，将生成流模型（去噪扩散、流匹配、热耗散）与架构（GNNs和E(3)-不变图神经网络）进行对比。我们的实验表明，方法和设计决策的选择极为敏感。代码可在以下网址获取：[这里填写网址]。 

---
# MAJL: A Model-Agnostic Joint Learning Framework for Music Source Separation and Pitch Estimation 

**Title (ZH)**: MAJL：一种模型无关的联合学习框架，用于音乐源分离和音高估计 

**Authors**: Haojie Wei, Jun Yuan, Rui Zhang, Quanyu Dai, Yueguo Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.03689)  

**Abstract**: Music source separation and pitch estimation are two vital tasks in music information retrieval. Typically, the input of pitch estimation is obtained from the output of music source separation. Therefore, existing methods have tried to perform these two tasks simultaneously, so as to leverage the mutually beneficial relationship between both tasks. However, these methods still face two critical challenges that limit the improvement of both tasks: the lack of labeled data and joint learning optimization. To address these challenges, we propose a Model-Agnostic Joint Learning (MAJL) framework for both tasks. MAJL is a generic framework and can use variant models for each task. It includes a two-stage training method and a dynamic weighting method named Dynamic Weights on Hard Samples (DWHS), which addresses the lack of labeled data and joint learning optimization, respectively. Experimental results on public music datasets show that MAJL outperforms state-of-the-art methods on both tasks, with significant improvements of 0.92 in Signal-to-Distortion Ratio (SDR) for music source separation and 2.71% in Raw Pitch Accuracy (RPA) for pitch estimation. Furthermore, comprehensive studies not only validate the effectiveness of each component of MAJL, but also indicate the great generality of MAJL in adapting to different model architectures. 

**Abstract (ZH)**: 音乐源分离和音高估计是音乐信息检索中的两个关键任务。通常，音高估计的输入是从音乐源分离的输出中获得的。因此，现有的方法试图同时进行这两个任务，以便充分利用两者之间的相互促进关系。然而，这些方法仍然面临两个关键挑战，限制了两个任务的改进：缺乏标注数据和联合学习优化。为应对这些挑战，我们提出了一种模型无关的联合学习（Model-Agnostic Joint Learning, MAJL）框架，用于这两个任务。MAJL 是一个通用框架，可以为每个任务使用不同的模型。该框架包含两种训练方法和一种动态权重方法——Hard Samples 动态加权（Dynamic Weights on Hard Samples, DWHS），分别解决缺乏标注数据和联合学习优化的问题。在公开音乐数据集上的实验结果表明，MAJL 在两个任务上的性能均优于现有最佳方法，音乐源分离的信号与失真比（Signal-to-Distortion Ratio, SDR）提高了 0.92，音高估计的原始音高准确率（Raw Pitch Accuracy, RPA）提高了 2.71%。此外，全面的研究不仅验证了 MAJL 每个组件的有效性，而且还表明 MAJL 在适应不同模型结构方面具有极大的通用性。 

---
# SLAM: Towards Efficient Multilingual Reasoning via Selective Language Alignment 

**Title (ZH)**: SLAM：通过选择性语言对齐实现高效的多语言推理 

**Authors**: Yuchun Fan, Yongyu Mu, Yilin Wang, Lei Huang, Junhao Ruan, Bei Li, Tong Xiao, Shujian Huang, Xiaocheng Feng, Jingbo Zhu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03681)  

**Abstract**: Despite the significant improvements achieved by large language models (LLMs) in English reasoning tasks, these models continue to struggle with multilingual reasoning. Recent studies leverage a full-parameter and two-stage training paradigm to teach models to first understand non-English questions and then reason. However, this method suffers from both substantial computational resource computing and catastrophic forgetting. The fundamental cause is that, with the primary goal of enhancing multilingual comprehension, an excessive number of irrelevant layers and parameters are tuned during the first stage. Given our findings that the representation learning of languages is merely conducted in lower-level layers, we propose an efficient multilingual reasoning alignment approach that precisely identifies and fine-tunes the layers responsible for handling multilingualism. Experimental results show that our method, SLAM, only tunes 6 layers' feed-forward sub-layers including 6.5-8% of all parameters within 7B and 13B LLMs, achieving superior average performance than all strong baselines across 10 languages. Meanwhile, SLAM only involves one training stage, reducing training time by 4.1-11.9 compared to the two-stage method. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）在英语推理任务上取得了显著的进步，但这些模型在多语言推理方面仍然表现不佳。近期的研究利用全参数和两阶段训练范式来教导模型首先理解非英语问题，然后进行推理。然而，这种方法在计算资源和灾难性遗忘两个方面都存在问题。其根本原因是，在旨在增强多语言理解的主要目标下，在第一阶段过度调优了大量与多语言处理不相关的层和参数。鉴于我们的发现，语言表示学习仅在较低层级的层中进行，我们提出了一种高效的多语言推理对齐方法，该方法能够精确识别并调整负责处理多语言性的层。实验结果表明，我们的方法（SLAM）仅调整了7B和13B LLM中的6层前馈子层，包括所有参数的6.5%-8%，在10种语言上的平均表现均优于所有强基线方法。同时，SLAM仅包括一个训练阶段，相较两阶段方法，训练时间减少了4.1%-11.9%。 

---
# SALE-Based Offline Reinforcement Learning with Ensemble Q-Networks 

**Title (ZH)**: 基于SALE的离线强化学习方法：集成Q网络 

**Authors**: Zheng Chun  

**Link**: [PDF](https://arxiv.org/pdf/2501.03676)  

**Abstract**: In this work, we build upon the offline reinforcement learning algorithm TD7, which incorporates State-Action Learned Embeddings (SALE) and LAP, and propose a model-free actor-critic algorithm that integrates ensemble Q-networks and a gradient diversity penalty from EDAC. The ensemble Q-networks effectively address the challenge of out-of-distribution actions by introducing penalties that guide the actor network to focus on in-distribution actions. Meanwhile, the gradient diversity penalty encourages diverse Q-value gradients, further suppressing overestimation for out-of-distribution actions. Additionally, our method retains an adjustable behavior cloning (BC) term that directs the actor network toward dataset actions during early training stages, while gradually reducing its influence as the precision of the Q-ensemble improves. These enhancements work synergistically to improve training stability and accuracy. Experimental results on the D4RL MuJoCo benchmarks demonstrate that our algorithm achieves superior convergence speed, stability, and performance compared to existing methods. 

**Abstract (ZH)**: 在本研究中，我们基于集成SALE（State-Action Learned Embeddings）和LAP（Learned Augmentation Policy）的离线强化学习算法TD7，提出了一种模型无关的演员-评论家算法，该算法集成了集成Q网络和来自EDAC（Ensemble Diversity and Confidence）的梯度多样性惩罚。这些集成的Q网络通过引入惩罚项来指导演员网络关注内部分布的动作，从而有效解决了处理外分布动作的挑战。同时，梯度多样性惩罚促进了多样化的Q值梯度，进一步抑制了对外分布动作的过度估计。此外，该方法保留了一个可调节的行为克隆（BC）项，在训练早期阶段引导演员网络朝数据集动作发展，而随着Q集成的精度提高，其影响逐渐减弱。这些改进措施协同作用，提高了训练的稳定性和准确性。实验结果表明，在D4RL MuJoCo基准测试中，本算法在收敛速度、稳定性和性能方面优于现有方法。 

---
# Action Quality Assessment via Hierarchical Pose-guided Multi-stage Contrastive Regression 

**Title (ZH)**: 基于层次姿势引导多阶段对比回归的动作质量评估 

**Authors**: Mengshi Qi, Hao Ye, Jiaxuan Peng, Huadong Ma  

**Link**: [PDF](https://arxiv.org/pdf/2501.03674)  

**Abstract**: Action Quality Assessment (AQA), which aims at automatic and fair evaluation of athletic performance, has gained increasing attention in recent years. However, athletes are often in rapid movement and the corresponding visual appearance variances are subtle, making it challenging to capture fine-grained pose differences and leading to poor estimation performance. Furthermore, most common AQA tasks, such as diving in sports, are usually divided into multiple sub-actions, each of which contains different durations. However, existing methods focus on segmenting the video into fixed frames, which disrupts the temporal continuity of sub-actions resulting in unavoidable prediction errors. To address these challenges, we propose a novel action quality assessment method through hierarchically pose-guided multi-stage contrastive regression. Firstly, we introduce a multi-scale dynamic visual-skeleton encoder to capture fine-grained spatio-temporal visual and skeletal features. Then, a procedure segmentation network is introduced to separate different sub-actions and obtain segmented features. Afterwards, the segmented visual and skeletal features are both fed into a multi-modal fusion module as physics structural priors, to guide the model in learning refined activity similarities and variances. Finally, a multi-stage contrastive learning regression approach is employed to learn discriminative representations and output prediction results. In addition, we introduce a newly-annotated FineDiving-Pose Dataset to improve the current low-quality human pose labels. In experiments, the results on FineDiving and MTL-AQA datasets demonstrate the effectiveness and superiority of our proposed approach. Our source code and dataset are available at this https URL. 

**Abstract (ZH)**: 动作质量评估（AQA），旨在实现对运动员表现的自动且公平评价，近年来引起了越来越多的关注。然而，运动员往往处于快速移动状态，相应的视觉外观变化微妙，这使得捕捉动作间的微小差异变得极具挑战性，从而导致估计性能不佳。此外，大多数常见的AQA任务，如体育中的跳水，通常被划分为多个子动作，每个子动作具有不同的持续时间。然而，现有方法专注于将视频分割成固定帧，这打断了子动作的时间连续性，导致不可避免的预测误差。为应对这些挑战，我们提出了一种通过分层动作导向多阶段对比回归的新颖动作质量评估方法。首先，我们引入多尺度动态视觉骨架编码器，以捕获精细的空间-时间视觉和骨架特征。然后，引入一个程序分割网络以分离不同的子动作并获取分割特征。接着，将分割的视觉和骨架特征同时输入多模态融合模块，作为物理结构先验，以引导模型学习精细的活动相似性和差异。最后，采用多阶段对比学习回归方法来学习判别性表示并输出预测结果。此外，我们引入了一个新标注的FineDiving-Pose数据集，以提高当前低质量的人体姿态标签。在实验中，对FineDiving和MTL-AQA数据集的结果表明了我们提出方法的有效性和优越性。我们的源代码和数据集可以在以下链接获取：[这里插入实际链接]。 

---
# A Diversity-Enhanced Knowledge Distillation Model for Practical Math Word Problem Solving 

**Title (ZH)**: 一种增强多样性的知识精炼模型：实用数学文字问题求解 

**Authors**: Yi Zhang, Guangyou Zhou, Zhiwen Xie, Jinjin Ma, Jimmy Xiangji Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03670)  

**Abstract**: Math Word Problem (MWP) solving is a critical task in natural language processing, has garnered significant research interest in recent years. Various recent studies heavily rely on Seq2Seq models and their extensions (e.g., Seq2Tree and Graph2Tree) to generate mathematical equations. While effective, these models struggle to generate diverse but counterpart solution equations, limiting their generalization across various math problem scenarios. In this paper, we introduce a novel Diversity-enhanced Knowledge Distillation (DivKD) model for practical MWP solving. Our approach proposes an adaptive diversity distillation method, in which a student model learns diverse equations by selectively transferring high-quality knowledge from a teacher model. Additionally, we design a diversity prior-enhanced student model to better capture the diversity distribution of equations by incorporating a conditional variational auto-encoder. Extensive experiments on {four} MWP benchmark datasets demonstrate that our approach achieves higher answer accuracy than strong baselines while maintaining high efficiency for practical applications. 

**Abstract (ZH)**: 数学文字问题（MWP）求解是自然语言处理中的一个关键任务，在近年来引起了显著的研究兴趣。各种最近的研究高度依赖于Seq2Seq模型及其扩展（如Seq2Tree和Graph2Tree）来生成数学方程。尽管这些模型有效，但它们在生成多样的且对应的解答方程方面存在局限性，限制了其在不同数学问题情境下的泛化能力。在本文中，我们提出了一种新颖的增强多样性知识蒸馏（DivKD）模型，以实现实际的MWP求解。我们的方法提出了一种自适应多样性蒸馏方法，其中学生模型通过有选择地从教师模型转移高质量知识来学习多样化的方程。此外，我们设计了一种增强多样性先验的学生模型，通过引入条件变分自编码器更好地捕捉方程的多样性分布。在四个MWP基准数据集上的广泛实验表明，我们的方法在保持高效的同时，实现了高于强基线的更高答案准确性。 

---
# Effective and Efficient Mixed Precision Quantization of Speech Foundation Models 

**Title (ZH)**: 有效的高效语音基础模型混合精度量化方法 

**Authors**: Haoning Xu, Zhaoqing Li, Zengrui Jin, Huimeng Wang, Youjun Chen, Guinan Li, Mengzhe Geng, Shujie Hu, Jiajun Deng, Xunying Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03643)  

**Abstract**: This paper presents a novel mixed-precision quantization approach for speech foundation models that tightly integrates mixed-precision learning and quantized model parameter estimation into one single model compression stage. Experiments conducted on LibriSpeech dataset with fine-tuned wav2vec2.0-base and HuBERT-large models suggest the resulting mixed-precision quantized models increased the lossless compression ratio by factors up to 1.7x and 1.9x over the respective uniform-precision and two-stage mixed-precision quantized baselines that perform precision learning and model parameters quantization in separate and disjointed stages, while incurring no statistically word error rate (WER) increase over the 32-bit full-precision models. The system compression time of wav2vec2.0-base and HuBERT-large models is reduced by up to 1.9 and 1.5 times over the two-stage mixed-precision baselines, while both produce lower WERs. The best-performing 3.5-bit mixed-precision quantized HuBERT-large model produces a lossless compression ratio of 8.6x over the 32-bit full-precision system. 

**Abstract (ZH)**: 本文提出了一种新颖的混合精度量化方法，将混合精度学习和量化模型参数估计紧密结合，在单一模型压缩阶段进行。实验使用LibriSpeech数据集和微调后的wav2vec2.0-base以及HuBERT-large模型表明，所得的混合精度量化模型在无损压缩比上分别比单一精度和两阶段混合精度量化baseline提高了1.7倍和1.9倍，同时与32位全精度模型相比，没有显著增加单词错误率（WER）。与两阶段混合精度基线相比，wav2vec2.0-base和HuBERT-large模型的系统压缩时间分别减少了1.9倍和1.5倍，同时两者均具有更低的WER。性能最佳的3.5位混合精度量化HuBERT-large模型在无损压缩比上达到了32位全精度系统的8.6倍。 

---
# MHGNet: Multi-Heterogeneous Graph Neural Network for Traffic Prediction 

**Title (ZH)**: MHGNet：多异构图神经网络在交通预测中的应用 

**Authors**: Mei Wu, Yiqian Lin, Tianfan Jiang, Wenchao Weng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03635)  

**Abstract**: In recent years, traffic flow prediction has played a crucial role in the management of intelligent transportation systems. However, traditional forecasting methods often model non-Euclidean low-dimensional traffic data as a simple graph with single-type nodes and edges, failing to capture similar trends among nodes of the same type. To address this limitation, this paper proposes MHGNet, a novel framework for modeling spatiotemporal multi-heterogeneous graphs. Within this framework, the STD Module decouples single-pattern traffic data into multi-pattern traffic data through feature mappings of timestamp embedding matrices and node embedding matrices. Subsequently, the Node Clusterer leverages the Euclidean distance between nodes and different types of limit points to perform clustering with O(N) time complexity. The nodes within each cluster undergo residual subgraph convolution within the spatiotemporal fusion subgraphs generated by the DSTGG Module, followed by processing in the SIE Module for node repositioning and redistribution of weights. To validate the effectiveness of MHGNet, this paper conducts extensive ablation studies and quantitative evaluations on four widely used benchmarks, demonstrating its superior performance. 

**Abstract (ZH)**: 近年来，交通流量预测在智能交通系统的管理中发挥着至关重要的作用。然而，传统的预测方法往往将非欧几里得低维交通数据简化为单一类型节点和边的简单图，未能捕捉到相同类型节点之间的相似趋势。为解决这一局限性，本文提出了一种新的框架——MHGNet，用于建模时空多异构图。在该框架中，STD模块通过时间戳嵌入矩阵和节点嵌入矩阵的特征映射，将单一模式的交通数据分解为多模式的交通数据。随后，节点聚类器利用节点之间的欧几里得距离以及不同类型的极限点进行聚类，其时间复杂度为O(N)。每个聚类内的节点在由DSTGG模块生成的时空融合子图中进行残差子图卷积，然后在SIE模块中进行节点重定位和权重重新分布处理。为验证MHGNet的有效性，本文在四个广泛使用的基准数据集上进行了详尽的消融研究和定量评估，展示了其优越性能。 

---
# RecKG: Knowledge Graph for Recommender Systems 

**Title (ZH)**: RecKG：推荐系统中的知识图谱 

**Authors**: Junhyuk Kwon, Seokho Ahn, Young-Duk Seo  

**Link**: [PDF](https://arxiv.org/pdf/2501.03598)  

**Abstract**: Knowledge graphs have proven successful in integrating heterogeneous data across various domains. However, there remains a noticeable dearth of research on their seamless integration among heterogeneous recommender systems, despite knowledge graph-based recommender systems garnering extensive research attention. This study aims to fill this gap by proposing RecKG, a standardized knowledge graph for recommender systems. RecKG ensures the consistent representation of entities across different datasets, accommodating diverse attribute types for effective data integration. Through a meticulous examination of various recommender system datasets, we select attributes for RecKG, ensuring standardized formatting through consistent naming conventions. By these characteristics, RecKG can seamlessly integrate heterogeneous data sources, enabling the discovery of additional semantic information within the integrated knowledge graph. We apply RecKG to standardize real-world datasets, subsequently developing an application for RecKG using a graph database. Finally, we validate RecKG's achievement in interoperability through a qualitative evaluation between RecKG and other studies. 

**Abstract (ZH)**: 知识图谱已在多个领域中成功地实现了异构数据的整合。然而，在异构推荐系统之间无缝整合的知识图谱研究仍然存在明显的不足，尽管基于知识图谱的推荐系统受到了广泛的研究关注。本研究旨在通过提出RecKG，一种标准化的知识图谱，填补这一空白。RecKG确保了不同数据集中的实体具有一致的表示，能够适应多种属性类型，从而有效实现数据整合。通过详细检查各种推荐系统数据集，我们为RecKG选择适当的属性，并通过一致的命名规范确保标准化的格式化。凭借这些特性，RecKG可以无缝地整合异构数据源，在整合的知识图谱中发现额外的语义信息。我们应用RecKG对实际数据集进行标准化，并随后使用图数据库开发RecKG的应用。最后，通过与其它研究的定性评价，验证RecKG在互操作性方面的成就。 

---
# Cosmos World Foundation Model Platform for Physical AI 

**Title (ZH)**: 宇宙世界基础模型平台：用于物理人工智能 

**Authors**: NVIDIA, Niket Agarwal, Arslan Ali, Maciej Bala, Yogesh Balaji, Erik Barker, Tiffany Cai, Prithvijit Chattopadhyay, Yongxin Chen, Yin Cui, Yifan Ding, Daniel Dworakowski, Jiaojiao Fan, Michele Fenzi, Francesco Ferroni, Sanja Fidler, Dieter Fox, Songwei Ge, Yunhao Ge, Jinwei Gu, Siddharth Gururani, Ethan He, Jiahui Huang, Jacob Huffman, Pooya Jannaty, Jingyi Jin, Seung Wook Kim, Gergely Klár, Grace Lam, Shiyi Lan, Laura Leal-Taixe, Anqi Li, Zhaoshuo Li, Chen-Hsuan Lin, Tsung-Yi Lin, Huan Ling, Ming-Yu Liu, Xian Liu, Alice Luo, Qianli Ma, Hanzi Mao, Kaichun Mo, Arsalan Mousavian, Seungjun Nah, Sriharsha Niverty, David Page, Despoina Paschalidou, Zeeshan Patel, Lindsey Pavao, Morteza Ramezanali, Fitsum Reda, Xiaowei Ren, Vasanth Rao Naik Sabavat, Ed Schmerling, Stella Shi, Bartosz Stefaniak, Shitao Tang, Lyne Tchapmi, Przemek Tredak, Wei-Cheng Tseng, Jibin Varghese, Hao Wang, Haoxiang Wang, Heng Wang, Ting-Chun Wang, Fangyin Wei, Xinyue Wei, Jay Zhangjie Wu, Jiashu Xu, Wei Yang, Lin Yen-Chen, Xiaohui Zeng, Yu Zeng, Jing Zhang, Qinsheng Zhang, Yuxuan Zhang, Qingqing Zhao, Artur Zolkowski  

**Link**: [PDF](https://arxiv.org/pdf/2501.03575)  

**Abstract**: Physical AI needs to be trained digitally first. It needs a digital twin of itself, the policy model, and a digital twin of the world, the world model. In this paper, we present the Cosmos World Foundation Model Platform to help developers build customized world models for their Physical AI setups. We position a world foundation model as a general-purpose world model that can be fine-tuned into customized world models for downstream applications. Our platform covers a video curation pipeline, pre-trained world foundation models, examples of post-training of pre-trained world foundation models, and video tokenizers. To help Physical AI builders solve the most critical problems of our society, we make our platform open-source and our models open-weight with permissive licenses available via this https URL. 

**Abstract (ZH)**: 物理AI需要首先通过数字方式进行训练。它需要一个自身的数字孪生体、策略模型，以及一个世界模型，用于模仿现实世界。在本文中，我们介绍了Cosmos世界基础模型平台，以帮助开发者为其物理AI配置构建定制化世界模型。我们将世界基础模型定位为一个通用的世界模型，可以针对下游应用进行微调。我们的平台涵盖了视频编目流水线、预训练的世界基础模型、预训练世界基础模型的后训练示例以及视频词汇化工具。为了帮助物理AI开发者解决社会面临的最关键问题，我们开源了我们的平台，并通过此网址提供了宽松许可的模型权重：[链接]。 

---
# From Code to Compliance: Assessing ChatGPT's Utility in Designing an Accessible Webpage -- A Case Study 

**Title (ZH)**: 从代码到合规性：评估ChatGPT在设计无障碍网页方面的实用性——一个案例研究 

**Authors**: Ammar Ahmed, Margarida Fresco, Fredrik Forsberg, Hallvard Grotli  

**Link**: [PDF](https://arxiv.org/pdf/2501.03572)  

**Abstract**: Web accessibility ensures that individuals with disabilities can access and interact with digital content without barriers, yet a significant majority of most used websites fail to meet accessibility standards. This study evaluates ChatGPT's (GPT-4o) ability to generate and improve web pages in line with Web Content Accessibility Guidelines (WCAG). While ChatGPT can effectively address accessibility issues when prompted, its default code often lacks compliance, reflecting limitations in its training data and prevailing inaccessible web practices. Automated and manual testing revealed strengths in resolving simple issues but challenges with complex tasks, requiring human oversight and additional iterations. Unlike prior studies, we incorporate manual evaluation, dynamic elements, and use the visual reasoning capability of ChatGPT along with the prompts to fix accessibility issues. Providing screenshots alongside prompts enhances the LLM's ability to address accessibility issues by allowing it to analyze surrounding components, such as determining appropriate contrast colors. We found that effective prompt engineering, such as providing concise, structured feedback and incorporating visual aids, significantly enhances ChatGPT's performance. These findings highlight the potential and limitations of large language models for accessible web development, offering practical guidance for developers to create more inclusive websites. 

**Abstract (ZH)**: 网络无障碍确保了残疾人能够无障碍地访问和交互数字内容，然而大多数最常用网站仍未达到无障碍标准。本研究评估了ChatGPT（GPT-4o）生成和改进符合《Web内容无障碍指南》（WCAG）的网页的能力。虽然ChatGPT在被提示时能够有效解决无障碍问题，但其默认代码往往不符合规范，反映了其训练数据和普遍存在的无障碍网页实践的局限性。自动和手动测试表明，在解决简单问题方面存在优势，但在处理复杂任务方面存在挑战，需要人工监督和额外的迭代。与以前的研究不同，我们采用了手动评估、动态元素，并利用ChatGPT的视觉推理能力及其提示来修复无障碍问题。通过提供屏幕截图并随附提示，可以增强LLM修复无障碍问题的能力，因为它可以分析周围的组件，如确定合适的对比度颜色。我们发现，有效的提示工程，如提供简洁的结构化反馈和引入视觉辅助工具，显著提升了ChatGPT的表现。这些发现突显了大型语言模型在无障碍-web开发中的潜力和局限性，并为开发人员提供了创建更包容性网站的实用指导。 

---
# Applying Large Language Models in Knowledge Graph-based Enterprise Modeling: Challenges and Opportunities 

**Title (ZH)**: 基于知识图的企业建模中大型语言模型的应用：挑战与机遇 

**Authors**: Benedikt Reitemeyer, Hans-Georg Fill  

**Link**: [PDF](https://arxiv.org/pdf/2501.03566)  

**Abstract**: The role of large language models (LLMs) in enterprise modeling has recently started to shift from academic research to that of industrial applications. Thereby, LLMs represent a further building block for the machine-supported generation of enterprise models. In this paper we employ a knowledge graph-based approach for enterprise modeling and investigate the potential benefits of LLMs in this context. In addition, the findings of an expert survey and ChatGPT-4o-based experiments demonstrate that LLM-based model generations exhibit minimal variability, yet remain constrained to specific tasks, with reliability declining for more intricate tasks. The survey results further suggest that the supervision and intervention of human modeling experts are essential to ensure the accuracy and integrity of the generated models. 

**Abstract (ZH)**: 大型语言模型（LLMs）在企业建模中的作用已经从学术研究转向工业应用。因此，LLMs 成为了机器支持的企业建模的一个进一步组成部分。本文采用基于知识图谱的方法进行企业建模，并探讨LLMs在此情境下的潜在益处。此外，专家调查和基于ChatGPT-4的实验证明，基于LLMs的模型生成表现出较低的变异度，但在面对复杂任务时仍会受到限制，可靠性也随之下降。调查结果进一步表明，在生成模型的准确性与完整性方面，人类建模专家的监督与干预是必不可少的。 

---
# Rethinking Adversarial Attacks in Reinforcement Learning from Policy Distribution Perspective 

**Title (ZH)**: 从策略分布视角重新思考强化学习中的对抗攻击 

**Authors**: Tianyang Duan, Zongyuan Zhang, Zheng Lin, Yue Gao, Ling Xiong, Yong Cui, Hongbin Liang, Xianhao Chen, Heming Cui, Dong Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03562)  

**Abstract**: Deep Reinforcement Learning (DRL) suffers from uncertainties and inaccuracies in the observation signal in realworld applications. Adversarial attack is an effective method for evaluating the robustness of DRL agents. However, existing attack methods targeting individual sampled actions have limited impacts on the overall policy distribution, particularly in continuous action spaces. To address these limitations, we propose the Distribution-Aware Projected Gradient Descent attack (DAPGD). DAPGD uses distribution similarity as the gradient perturbation input to attack the policy network, which leverages the entire policy distribution rather than relying on individual samples. We utilize the Bhattacharyya distance in DAPGD to measure policy similarity, enabling sensitive detection of subtle but critical differences between probability distributions. Our experiment results demonstrate that DAPGD achieves SOTA results compared to the baselines in three robot navigation tasks, achieving an average 22.03% higher reward drop compared to the best baseline. 

**Abstract (ZH)**: 深度强化学习（DRL）在实际应用中面临着观察信号的不确定性与不准确性。对抗攻击是一种评估DRL智能体鲁棒性的有效方法。然而，现有的针对单个采样动作的攻击方法对整体策略分布的影响有限，特别是在连续动作空间中。为解决这些问题，我们提出了分布感知的投影梯度下降攻击（DAPGD）。DAPGD使用策略分布相似性作为梯度扰动输入，攻击策略网络，而不是依赖于个别样本。我们利用Bhattacharyya距离在DAPGD中衡量策略相似性，能够敏感地检测概率分布之间细微但关键的差异。我们的实验结果表明，与基线方法相比，DAPGD在三个机器人导航任务中取得了SOTA结果，平均实现了22.03%更高的奖励下降。 

---
# KG-TRICK: Unifying Textual and Relational Information Completion of Knowledge for Multilingual Knowledge Graphs 

**Title (ZH)**: KG-TRICK：多语言知识图谱中的文本和关系信息集成补全 

**Authors**: Zelin Zhou, Simone Conia, Daniel Lee, Min Li, Shenglei Huang, Umar Farooq Minhas, Saloni Potdar, Henry Xiao, Yunyao Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.03560)  

**Abstract**: Multilingual knowledge graphs (KGs) provide high-quality relational and textual information for various NLP applications, but they are often incomplete, especially in non-English languages. Previous research has shown that combining information from KGs in different languages aids either Knowledge Graph Completion (KGC), the task of predicting missing relations between entities, or Knowledge Graph Enhancement (KGE), the task of predicting missing textual information for entities. Although previous efforts have considered KGC and KGE as independent tasks, we hypothesize that they are interdependent and mutually beneficial. To this end, we introduce KG-TRICK, a novel sequence-to-sequence framework that unifies the tasks of textual and relational information completion for multilingual KGs. KG-TRICK demonstrates that: i) it is possible to unify the tasks of KGC and KGE into a single framework, and ii) combining textual information from multiple languages is beneficial to improve the completeness of a KG. As part of our contributions, we also introduce WikiKGE10++, the largest manually-curated benchmark for textual information completion of KGs, which features over 25,000 entities across 10 diverse languages. 

**Abstract (ZH)**: 多语言知识图谱（KGs）为各种自然语言处理（NLP）应用提供了高质量的关联和文本信息，但它们通常不完整，特别是在非英语语言方面。先前的研究表明，结合不同语言知识图谱中的信息有助于知识图谱补全（KGC）任务，即预测实体之间缺失的关系，或者有助于知识图谱增强（KGE）任务，即预测实体缺失的文本信息。尽管先前的努力将KGC和KGE视为独立任务，但我们假设它们相互依赖且互有裨益。为此，我们提出了KG-TRICK，这是一种新颖的序列到序列框架，旨在统一多语言知识图谱中文字和关系信息补全的任务。KG-TRICK表明：i) 可以将KGC和KGE的任务统一到一个框架中，ii) 结合多语言的文本信息对于提高知识图谱的完整性是有益的。作为我们贡献的一部分，我们还提出了WikiKGE10++，这是一个针对知识图谱文本信息补全的最大的手工收集基准，涵盖了10种不同语言的超过25,000个实体。 

---
# PromptGuard: Soft Prompt-Guided Unsafe Content Moderation for Text-to-Image Models 

**Title (ZH)**: PromptGuard：软提示引导的内容审核技术在文本转图像模型中的应用 

**Authors**: Lingzhi Yuan, Xinfeng Li, Chejian Xu, Guanhong Tao, Xiaojun Jia, Yihao Huang, Wei Dong, Yang Liu, XiaoFeng Wang, Bo Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.03544)  

**Abstract**: Text-to-image (T2I) models have been shown to be vulnerable to misuse, particularly in generating not-safe-for-work (NSFW) content, raising serious ethical concerns. In this work, we present PromptGuard, a novel content moderation technique that draws inspiration from the system prompt mechanism in large language models (LLMs) for safety alignment. Unlike LLMs, T2I models lack a direct interface for enforcing behavioral guidelines. Our key idea is to optimize a safety soft prompt that functions as an implicit system prompt within the T2I model's textual embedding space. This universal soft prompt (P*) directly moderates NSFW inputs, enabling safe yet realistic image generation without altering the inference efficiency or requiring proxy models. Extensive experiments across three datasets demonstrate that PromptGuard effectively mitigates NSFW content generation while preserving high-quality benign outputs. PromptGuard achieves 7.8 times faster than prior content moderation methods, surpassing eight state-of-the-art defenses with an optimal unsafe ratio down to 5.84%. 

**Abstract (ZH)**: 文本到图像（Text-to-Image, T2I）模型已被证明容易被滥用，特别是在生成不适合工作场所（Not Safe For Work, NSFW）的内容时，引发了严重的伦理问题。本文中，我们提出了一种名为PromptGuard的新颖内容审核技术，该技术借鉴了大型语言模型（Large Language Models, LLMs）系统提示机制的安全对齐理念。与LLMs不同，T2I模型缺乏直接的接口来强制执行行为准则。我们的核心想法是优化一个安全软提示（P*），该软提示作为T2I模型文本嵌入空间内的隐式系统提示，对NSFW输入进行直接审核，从而实现出安全的且具真实感的图像生成，同时不改变推理效率或需要代理模型。通过在三个数据集上的广泛实验表明，PromptGuard有效减少了NSFW内容的生成，同时保留了高质量的良性输出。PromptGuard在速度上比之前的内容审核方法快7.8倍，超越了八个最先进的防御方法，最低不安全比率降至5.84%。 

---
# Deep Learning within Tabular Data: Foundations, Challenges, Advances and Future Directions 

**Title (ZH)**: 在表格数据中应用深度学习：基础、挑战、进展及未来方向 

**Authors**: Weijieying Ren, Tianxiang Zhao, Yuqing Huang, Vasant Honavar  

**Link**: [PDF](https://arxiv.org/pdf/2501.03540)  

**Abstract**: Tabular data remains one of the most prevalent data types across a wide range of real-world applications, yet effective representation learning for this domain poses unique challenges due to its irregular patterns, heterogeneous feature distributions, and complex inter-column dependencies. This survey provides a comprehensive review of state-of-the-art techniques in tabular data representation learning, structured around three foundational design elements: training data, neural architectures, and learning objectives. Unlike prior surveys that focus primarily on either architecture design or learning strategies, we adopt a holistic perspective that emphasizes the universality and robustness of representation learning methods across diverse downstream tasks. We examine recent advances in data augmentation and generation, specialized neural network architectures tailored to tabular data, and innovative learning objectives that enhance representation quality. Additionally, we highlight the growing influence of self-supervised learning and the adaptation of transformer-based foundation models for tabular data. Our review is based on a systematic literature search using rigorous inclusion criteria, encompassing 127 papers published since 2020 in top-tier conferences and journals. Through detailed analysis and comparison, we identify emerging trends, critical gaps, and promising directions for future research, aiming to guide the development of more generalizable and effective tabular data representation methods. 

**Abstract (ZH)**: 在广泛的实际应用中，表格数据仍然是最常见的数据类型之一，但有效进行表格数据表示学习却面临着独特挑战，这主要是由于其不规则模式、异质特征分布以及复杂的跨列依赖关系。本文综述了表格数据表示学习的前沿技术，按照三个基础设计元素：训练数据、神经架构和学习目标进行结构化。与以往仅聚焦于架构设计或学习策略的综述不同，我们采用了一个整体视角，强调表示学习方法在不同下游任务中的普适性和鲁棒性。我们考察了近期在数据增广和生成方面的进展、专为表格数据设计的特殊神经网络架构，以及能够提升表示质量的创新学习目标。此外，我们还强调了自监督学习日益增长的影响以及基于转换器的基础模型在表格数据中的应用。本文综述基于系统性的文献搜索，涵盖自2020年以来在顶级会议和期刊上发表的127篇论文。通过详细的分析和比较，我们确定了新兴趋势、关键空白和未来研究的前景方向，旨在指导开发更通用和有效的表格数据表示方法。 

---
# Vocal Tract Length Warped Features for Spoken Keyword Spotting 

**Title (ZH)**: 声腔长度归一化特征在口头关键词识别中的应用 

**Authors**: Achintya kr. Sarkar, Priyanka Dwivedi, Zheng-Hua Tan  

**Link**: [PDF](https://arxiv.org/pdf/2501.03523)  

**Abstract**: In this paper, we propose several methods that incorporate vocal tract length (VTL) warped features for spoken keyword spotting (KWS). The first method, VTL-independent KWS, involves training a single deep neural network (DNN) that utilizes VTL features with various warping factors. During training, a specific VTL feature is randomly selected per epoch, allowing the exploration of VTL variations. During testing, the VTL features with different warping factors of a test utterance are scored against the DNN and combined with equal weight. In the second method scores the conventional features of a test utterance (without VTL warping) against the DNN. The third method, VTL-concatenation KWS, concatenates VTL warped features to form high-dimensional features for KWS. Evaluations carried out on the English Google Command dataset demonstrate that the proposed methods improve the accuracy of KWS. 

**Abstract (ZH)**: 在本文中，我们提出了一种结合声带长度（Vocal Tract Length, VTL）变形特征的方法，用于语音关键词识别（Keyword Spotting, KWS）。首先，方法一“VTL独立的KWS”涉及训练一个单一的深度神经网络（Deep Neural Network, DNN），该网络利用具有不同变形因子的VTL特征进行训练。在训练过程中，每轮次随机选择一个特定的VTL特征，以探索VTL的变化。而在测试阶段，测试语音的具有不同变形因子的VTL特征分别与DNN进行评分，并以等权重组合。其次，方法二对测试语音（不包含VTL变形）的常规特征进行评分，然后与DNN进行对比。最后，方法三“VTL拼接的KWS”将VTL变形特征拼接起来，形成高维特征用于KWS。在英语Google Command数据集上的评估表明，所提出的方法能提高关键词识别的准确性。 

---
# Can Deep Learning Trigger Alerts from Mobile-Captured Images? 

**Title (ZH)**: 深度学习能从移动设备拍摄的图片中触发警报吗？ 

**Authors**: Pritisha Sarkar, Duranta Durbaar Vishal Saha, Mousumi Saha  

**Link**: [PDF](https://arxiv.org/pdf/2501.03499)  

**Abstract**: Our research presents a comprehensive approach to leveraging mobile camera image data for real-time air quality assessment and recommendation. We develop a regression-based Convolutional Neural Network model and tailor it explicitly for air quality prediction by exploiting the inherent relationship between output parameters. As a result, the Mean Squared Error of 0.0077 and 0.0112 obtained for 2 and 5 pollutants respectively outperforms existing models. Furthermore, we aim to verify the common practice of augmenting the original dataset with a view to introducing more variation in the training phase. It is one of our most significant contributions that our experimental results demonstrate minimal accuracy differences between the original and augmented datasets. Finally, a real-time, user-friendly dashboard is implemented which dynamically displays the Air Quality Index and pollutant values derived from captured mobile camera images. Users' health conditions are considered to recommend whether a location is suitable based on current air quality metrics. Overall, this research contributes to verification of data augmentation techniques, CNN-based regression modelling for air quality prediction, and user-centric air quality monitoring through mobile technology. The proposed system offers practical solutions for individuals to make informed environmental health and well-being decisions. 

**Abstract (ZH)**: 我们的研究提出了一种全面的方法，利用移动相机图像数据进行实时空气质量评估与推荐。我们开发了一个基于回归的卷积神经网络模型，并通过利用输出参数的固有关系，专门针对空气质量预测进行了调整。结果表明，对于2种和5种污染物，我们分别获得了均方误差0.0077和0.0112，这优于现有的模型。此外，我们致力于验证一种常见的做法，即将原始数据集扩充以在训练阶段引入更多变化。这是我们最重要的贡献之一，实验结果表明，原始数据集和扩充数据集之间的准确率差异极小。最后，我们实现了一个实时、用户友好的仪表盘，该仪表盘动态显示从捕获的移动相机图像中得出的空气质量指数和污染物值。基于当前的空气质量指标，系统考虑用户的健康状况，推荐某地点是否适合居住。总体而言，这项研究为数据扩充技术的验证、基于CNN的回归模型在空气质量预测中的应用以及通过移动技术实现以用户为中心的空气质量监测做出贡献。提出的系统为个体提供实践解决方案，以根据环境健康与福祉指标做出知情决策。 

---
# Can LLMs Design Good Questions Based on Context? 

**Title (ZH)**: 基于上下文，LLM能够设计出好的问题吗？ 

**Authors**: Yueheng Zhang, Xiaoyuan Liu, Yiyou Sun, Atheer Alharbi, Hend Alzahrani, Basel Alomair, Dawn Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.03491)  

**Abstract**: This paper evaluates questions generated by LLMs from context, comparing them to human-generated questions across six dimensions. We introduce an automated LLM-based evaluation method, focusing on aspects like question length, type, context coverage, and answerability. Our findings highlight unique characteristics of LLM-generated questions, contributing insights that can support further research in question quality and downstream applications. 

**Abstract (ZH)**: 本文从六个维度评估由大规模语言模型（LLM）生成的问题，将这些问题与人工生成的问题进行比较。我们引入了一种基于自动LLM的评估方法，重点关注诸如问题长度、类型、上下文覆盖和可回答性等方面。我们的研究结果揭示了LLM生成问题的独特特征，为后续关于问题质量的研究以及下游应用提供了宝贵的见解。 

---
# Align-Pro: A Principled Approach to Prompt Optimization for LLM Alignment 

**Title (ZH)**: Align-Pro：一种原理性的方法，用于大规模语言模型对齐的提示优化 

**Authors**: Prashant Trivedi, Souradip Chakraborty, Avinash Reddy, Vaneet Aggarwal, Amrit Singh Bedi, George K. Atia  

**Link**: [PDF](https://arxiv.org/pdf/2501.03486)  

**Abstract**: The alignment of large language models (LLMs) with human values is critical as these models become increasingly integrated into various societal and decision-making processes. Traditional methods, such as reinforcement learning from human feedback (RLHF), achieve alignment by fine-tuning model parameters, but these approaches are often computationally expensive and impractical when models are frozen or inaccessible for parameter modification. In contrast, prompt optimization is a viable alternative to RLHF for LLM alignment. While the existing literature has shown empirical promise of prompt optimization, its theoretical underpinning remains under-explored. We address this gap by formulating prompt optimization as an optimization problem and try to provide theoretical insights into the optimality of such a framework. To analyze the performance of the prompt optimization, we study theoretical suboptimality bounds and provide insights in terms of how prompt optimization depends upon the given prompter and target model. We also provide empirical validation through experiments on various datasets, demonstrating that prompt optimization can effectively align LLMs, even when parameter fine-tuning is not feasible. 

**Abstract (ZH)**: 大型语言模型（LLMs）与人类价值观的对齐至关重要，因为这些模型越来越被整合到各种社会和决策过程中。传统的对齐方法，如基于人类反馈的强化学习（RLHF），通过调整模型参数实现对齐，但在模型冻结或无法修改参数的情况下，这些方法往往计算成本高且不切实际。相比之下，提示优化是RLHF之外的一种可行的LLMs对齐方法。尽管现有文献显示提示优化具有实际应用前景，但其理论基础仍然有待深入探索。我们通过将提示优化形式化为优化问题来填补这一空白，并尝试提供该框架最优性的理论洞察。为了分析提示优化的性能，我们研究了理论次优性边界，并从提示优化依赖于给定的提示提供者和目标模型的角度提供了见解。我们还通过在各种数据集上进行的实验提供了经验验证，证明了即使参数微调不可行，提示优化也能够有效对齐LLMs。 

---
# Reading with Intent -- Neutralizing Intent 

**Title (ZH)**: 《带着目的阅读——消除意图的阅读》

这个翻译旨在忠实于原文含义，并符合学术论文的规范。如果有特定的上下文或需要更详细的解释，请告知我。 

**Authors**: Benjamin Reichman, Adar Avsian, Larry Heck  

**Link**: [PDF](https://arxiv.org/pdf/2501.03475)  

**Abstract**: Queries to large language models (LLMs) can be divided into two parts: the instruction/question and the accompanying context. The context for retrieval-augmented generation (RAG) systems in most benchmarks comes from Wikipedia or Wikipedia-like texts which are written in a neutral and factual tone. However, when RAG systems retrieve internet-based content, they encounter text with diverse tones and linguistic styles, introducing challenges for downstream tasks. The Reading with Intent task addresses this issue by evaluating how varying tones in context passages affect model performance. Building on prior work that focused on sarcasm, we extend this paradigm by constructing a dataset where context passages are transformed to $11$ distinct emotions using a better synthetic data generation approach. Using this dataset, we train an emotion translation model to systematically adapt passages to specified emotional tones. The human evaluation shows that the LLM fine-tuned to become the emotion-translator benefited from the synthetically generated data. Finally, the emotion-translator is used in the Reading with Intent task to transform the passages to a neutral tone. By neutralizing the passages, it mitigates the challenges posed by sarcastic passages and improves overall results on this task by about $3\%$. 

**Abstract (ZH)**: 大规模语言模型（LLMs）的查询可以分为两部分：指令/问题和伴随的上下文。大多数基准测试中的检索增强生成（RAG）系统的上下文来源于维基百科或类似维基百科的文本，这些文本通常以中性和事实性的方式撰写。然而，当RAG系统检索网络内容时，会遇到具有多种语调和语言风格的文本，这为下游任务带来了挑战。《意图阅读》任务通过评估上下文段落中不同语调对模型性能的影响来应对这一问题。在此基础上，我们扩展了先前专注于讽刺的研究，通过更有效的合成数据生成方法构建了一个数据集，该数据集将上下文段落转换为11种不同的情绪。利用此数据集，我们训练了一个情绪翻译模型，使其系统地将段落转换为指定的情绪语调。人类评估表明，通过合成生成的数据微调的LLM从中有益。最后，将情绪翻译器应用于《意图阅读》任务，将段落转换成中性语调。通过中性化段落，它减轻了讽刺段落带来的挑战，并在该任务上整体提高了大约3%的性能。 

---
# MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems 

**Title (ZH)**: MTRAG：一种多轮对话基准，用于评估检索增强生成系统 

**Authors**: Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-Suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.03468)  

**Abstract**: Retrieval-augmented generation (RAG) has recently become a very popular task for Large Language Models (LLMs). Evaluating them on multi-turn RAG conversations, where the system is asked to generate a response to a question in the context of a preceding conversation is an important and often overlooked task with several additional challenges. We present MTRAG: an end-to-end human-generated multi-turn RAG benchmark that reflects several real-world properties across diverse dimensions for evaluating the full RAG pipeline. MTRAG contains 110 conversations averaging 7.7 turns each across four domains for a total of 842 tasks. We also explore automation paths via synthetic data and LLM-as-a-Judge evaluation. Our human and automatic evaluations show that even state-of-the-art LLM RAG systems struggle on MTRAG. We demonstrate the need for strong retrieval and generation systems that can handle later turns, unanswerable questions, non-standalone questions, and multiple domains. MTRAG is available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）近年来已成为大型语言模型（LLMs）的一个非常流行的任务。在多轮RAG对话中评估它们——系统需要根据前一对话的背景生成对问题的回复——是一项重要但常被忽视的任务，还面临多个额外挑战。我们提出了MTRAG：一个端到端的人工生成多轮RAG基准，该基准在多个维度上反映了多种真实世界特性，用于全面评估RAG管道。MTRAG包含四个领域共110场对话，平均每场对话7.7轮，总共涵盖了842项任务。我们还探讨了通过合成数据和LLM作为裁判的评估方法来自动化的途径。我们的手动和自动评估表明，即使是当前最先进的LLM RAG系统在MTRAG上也存在困难。我们演示了需要强大的检索和生成系统来处理后续轮次、无法回答的问题、非独立的问题以及多个领域的需求。MTRAG可在以下链接获取：这个 https URL。 

---
# LHGNN: Local-Higher Order Graph Neural Networks For Audio Classification and Tagging 

**Title (ZH)**: LHGNN：局部-高阶图神经网络在音频分类和标签化中的应用 

**Authors**: Shubhr Singh, Emmanouil Benetos, Huy Phan, Dan Stowell  

**Link**: [PDF](https://arxiv.org/pdf/2501.03464)  

**Abstract**: Transformers have set new benchmarks in audio processing tasks, leveraging self-attention mechanisms to capture complex patterns and dependencies within audio data. However, their focus on pairwise interactions limits their ability to process the higher-order relations essential for identifying distinct audio objects. To address this limitation, this work introduces the Local- Higher Order Graph Neural Network (LHGNN), a graph based model that enhances feature understanding by integrating local neighbourhood information with higher-order data from Fuzzy C-Means clusters, thereby capturing a broader spectrum of audio relationships. Evaluation of the model on three publicly available audio datasets shows that it outperforms Transformer-based models across all benchmarks while operating with substantially fewer parameters. Moreover, LHGNN demonstrates a distinct advantage in scenarios lacking ImageNet pretraining, establishing its effectiveness and efficiency in environments where extensive pretraining data is unavailable. 

**Abstract (ZH)**: 变压器模型在音频处理任务中已经设定了一系列新的基准，通过自注意力机制捕获音频数据中的复杂模式和依赖关系。然而，它们对于处理关键的高阶关系的关注有限，这些高阶关系对于识别不同的音频对象至关重要。为了解决这一限制，本研究引入了局部高阶图神经网络（LHGNN），这是一种基于图的模型，通过集成局部邻域信息和模糊C均值聚类的高阶数据，从而捕获更广泛的音频关系。在三个公开的音频数据集上的评估结果表明，LHGNN在所有基准测试中均优于基于变压器的模型，并且其参数数量显著较少。此外，LHGNN在缺乏ImageNet预训练的数据环境中表现出明显的优势，证明了它在预训练数据稀缺环境中的有效性和效率。 

---
# Radar Signal Recognition through Self-Supervised Learning and Domain Adaptation 

**Title (ZH)**: 通过自我监督学习和领域适应的雷达信号识别 

**Authors**: Zi Huang, Akila Pemasiri, Simon Denman, Clinton Fookes, Terrence Martin  

**Link**: [PDF](https://arxiv.org/pdf/2501.03461)  

**Abstract**: Automatic radar signal recognition (RSR) plays a pivotal role in electronic warfare (EW), as accurately classifying radar signals is critical for informing decision-making processes. Recent advances in deep learning have shown significant potential in improving RSR performance in domains with ample annotated data. However, these methods fall short in EW scenarios where annotated RF data are scarce or impractical to obtain. To address these challenges, we introduce a self-supervised learning (SSL) method which utilises masked signal modelling and RF domain adaption to enhance RSR performance in environments with limited RF samples and labels. Specifically, we investigate pre-training masked autoencoders (MAE) on baseband in-phase and quadrature (I/Q) signals from various RF domains and subsequently transfer the learned representation to the radar domain, where annotated data are limited. Empirical results show that our lightweight self-supervised ResNet model with domain adaptation achieves up to a 17.5\% improvement in 1-shot classification accuracy when pre-trained on in-domain signals (i.e., radar signals) and up to a 16.31\% improvement when pre-trained on out-of-domain signals (i.e., comm signals), compared to its baseline without SSL. We also provide reference results for several MAE designs and pre-training strategies, establishing a new benchmark for few-shot radar signal classification. 

**Abstract (ZH)**: 自动雷达信号识别（RSR）在电子战（EW）中起着关键作用，因为准确分类雷达信号对于指导决策过程至关重要。近年来，深度学习的进步在有大量标注数据的领域显示出了显著的提升潜力。然而，在标注射频（RF）数据稀缺或难以获得的EW场景中，这些方法的表现不佳。为了解决这些挑战，我们提出了一种半监督学习（SSL）方法，该方法利用掩码信号建模和射频域适应，以增强在RF样本和标签有限环境中的RSR性能。具体而言，我们在不同RF域的本机中频（I/Q）信号上预训练掩码自编码器（MAE），然后将学到的表示转移到雷达域，该领域中的标注数据有限。实验结果表明，我们的轻量级自监督ResNet模型在本域信号（即雷达信号）上进行预训练时，1-shot分类精度提高了17.5%，而在外域信号（即通信信号）上进行预训练时，分类精度提高了16.31%，这与没有自监督学习的基线模型相比有所提升。我们还提供了几种MAE设计和预训练策略的参考结果，从而为雷达信号少量样本分类设立了新的基准。 

---
# Activating Associative Disease-Aware Vision Token Memory for LLM-Based X-ray Report Generation 

**Title (ZH)**: 基于大规模语言模型的X光报告生成中激活关联疾病意识视图令牌记忆 

**Authors**: Xiao Wang, Fuling Wang, Haowen Wang, Bo Jiang, Chuanfu Li, Yaowei Wang, Yonghong Tian, Jin Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03458)  

**Abstract**: X-ray image based medical report generation achieves significant progress in recent years with the help of the large language model, however, these models have not fully exploited the effective information in visual image regions, resulting in reports that are linguistically sound but insufficient in describing key diseases. In this paper, we propose a novel associative memory-enhanced X-ray report generation model that effectively mimics the process of professional doctors writing medical reports. It considers both the mining of global and local visual information and associates historical report information to better complete the writing of the current report. Specifically, given an X-ray image, we first utilize a classification model along with its activation maps to accomplish the mining of visual regions highly associated with diseases and the learning of disease query tokens. Then, we employ a visual Hopfield network to establish memory associations for disease-related tokens, and a report Hopfield network to retrieve report memory information. This process facilitates the generation of high-quality reports based on a large language model and achieves state-of-the-art performance on multiple benchmark datasets, including the IU X-ray, MIMIC-CXR, and Chexpert Plus. The source code of this work is released on \url{this https URL}. 

**Abstract (ZH)**: 近年来，基于X射线图像的医学报告生成在大型语言模型的帮助下取得了显著进展，然而，这些模型尚未充分利用视觉图像区域中的有效信息，导致报告在语言上是合理的，但对关键疾病的描述不足。本文提出了一种新颖的关联记忆增强的X射线报告生成模型，该模型能够有效模拟专业医生撰写医学报告的过程。它既考虑了全局和局部视觉信息的挖掘，又将历史报告信息关联起来，以更好地完成当前报告的撰写。具体来说，给定一张X射线图像，我们首先利用分类模型及其激活图来完成与疾病高度相关的视觉区域的挖掘和疾病查询标记的学习。然后，我们采用视觉霍普菲尔德网络建立与疾病相关的标记之间的记忆关联，并使用报告霍普菲尔德网络检索报告记忆信息。这一过程促进了基于大型语言模型的高质量报告生成，并在包括IU X射线、MIMIC-CXR和Chexpert Plus等多个基准数据集上达到了最先进的性能。本文的工作源代码可在此处访问：\url{此链接}。

请注意，这里的网址是用英文撰写的，实际使用时需要替换为正确的中文链接。 

---
# Optimization Learning 

**Title (ZH)**: 优化学习 

**Authors**: Pascal Van Hentenryck  

**Link**: [PDF](https://arxiv.org/pdf/2501.03443)  

**Abstract**: This article introduces the concept of optimization learning, a methodology to design optimization proxies that learn the input/output mapping of parametric optimization problems. These optimization proxies are trustworthy by design: they compute feasible solutions to the underlying optimization problems, provide quality guarantees on the returned solutions, and scale to large instances. Optimization proxies are differentiable programs that combine traditional deep learning technology with repair or completion layers to produce feasible solutions. The article shows that optimization proxies can be trained end-to-end in a self-supervised way. It presents methodologies to provide performance guarantees and to scale optimization proxies to large-scale optimization problems. The potential of optimization proxies is highlighted through applications in power systems and, in particular, real-time risk assessment and security-constrained optimal power flow. 

**Abstract (ZH)**: 本文介绍了优化学习的概念，这是一种设计优化代理的方法，用于解决参数化优化问题的输入/输出映射。这些优化代理具有设计上的可信性：它们能够计算底层优化问题的可行解，对返回的解提供质量保证，并能扩展到大规模实例。优化代理是一类可微程序，将传统的深度学习技术与修复或完成层结合，以生成可行解。本文展示了优化代理可以以自我监督的方式端到端地进行训练。本文还提出了提供性能保证和扩展优化代理的方法，使其适用于大规模优化问题。通过在电力系统中的应用，特别是实时风险评估和安全约束下的最优潮流，突显了优化代理的潜在优势。 

---
# SALT: Sales Autocompletion Linked Business Tables Dataset 

**Title (ZH)**: SALT：销售自动补全关联业务表数据集 

**Authors**: Tassilo Klein, Clemens Biehl, Margarida Costa, Andre Sres, Jonas Kolk, Johannes Hoffart  

**Link**: [PDF](https://arxiv.org/pdf/2501.03413)  

**Abstract**: Foundation models, particularly those that incorporate Transformer architectures, have demonstrated exceptional performance in domains such as natural language processing and image processing. Adapting these models to structured data, like tables, however, introduces significant challenges. These difficulties are even more pronounced when addressing multi-table data linked via foreign key, which is prevalent in the enterprise realm and crucial for empowering business use cases. Despite its substantial impact, research focusing on such linked business tables within enterprise settings remains a significantly important yet underexplored domain. To address this, we introduce a curated dataset sourced from an Enterprise Resource Planning (ERP) system, featuring extensive linked tables. This dataset is specifically designed to support research endeavors in table representation learning. By providing access to authentic enterprise data, our goal is to potentially enhance the effectiveness and applicability of models for real-world business contexts. 

**Abstract (ZH)**: 基础模型，特别是那些包含Transformer架构的模型，在自然语言处理和图像处理等领域已展现出卓越的性能。然而，将这些模型适应结构化数据，如表格，则引入了显著的挑战。特别是在处理通过外键连接的多表数据时，这种挑战更为突出，而这种多表数据在企业领域非常普遍，对于增强企业应用场景的能力至关重要。尽管其影响重大，但在企业环境中专注于此类连接的业务表的研究仍然属于一个重要但尚未充分探索的领域。为应对这一挑战，我们引入了一个来自企业资源规划(ERP)系统的精心整理的数据集，该数据集包含广泛的连接表。该数据集专为支持表格表示学习的研究而设计。通过提供真实的企业数据访问，我们的目标是有望增强模型在实际企业场景中的有效性和适用性。 

---
# BoundingDocs: a Unified Dataset for Document Question Answering with Spatial Annotations 

**Title (ZH)**: BoundingDocs：一种带有空间标注的统一文档问答数据集 

**Authors**: Simone Giovannini, Fabio Coppini, Andrea Gemelli, Simone Marinai  

**Link**: [PDF](https://arxiv.org/pdf/2501.03403)  

**Abstract**: We present a unified dataset for document Question-Answering (QA), which is obtained combining several public datasets related to Document AI and visually rich document understanding (VRDU). Our main contribution is twofold: on the one hand we reformulate existing Document AI tasks, such as Information Extraction (IE), into a Question-Answering task, making it a suitable resource for training and evaluating Large Language Models; on the other hand, we release the OCR of all the documents and include the exact position of the answer to be found in the document image as a bounding box. Using this dataset, we explore the impact of different prompting techniques (that might include bounding box information) on the performance of open-weight models, identifying the most effective approaches for document comprehension. 

**Abstract (ZH)**: 我们提供了一个统一的数据集用于文档问答（Document QA），该数据集通过结合多个与文档人工智能（Document AI）和视觉丰富文档理解（VRDU）相关的公共数据集而获得。我们的主要贡献有两个方面：一方面，我们将现有的Document AI任务，如信息抽取（IE）重新表述为问答任务，使其成为训练和评估大型语言模型的合适资源；另一方面，我们发布了所有文档的光学字符识别（OCR）结果，并包含了在文档图像中查找答案的确切位置，以边界框的形式呈现。利用这个数据集，我们探讨了不同提示技术（可能包括边界框信息）对开放权重模型性能的影响，识别出最有效的文档理解方法。 

---
# Enhanced Importance Sampling through Latent Space Exploration in Normalizing Flows 

**Title (ZH)**: 通过正则化流中的潜在空间探索增强重要性采样 

**Authors**: Liam A. Kruse, Alexandros E. Tzikas, Harrison Delecki, Mansur M. Arief, Mykel J. Kochenderfer  

**Link**: [PDF](https://arxiv.org/pdf/2501.03394)  

**Abstract**: Importance sampling is a rare event simulation technique used in Monte Carlo simulations to bias the sampling distribution towards the rare event of interest. By assigning appropriate weights to sampled points, importance sampling allows for more efficient estimation of rare events or tails of distributions. However, importance sampling can fail when the proposal distribution does not effectively cover the target distribution. In this work, we propose a method for more efficient sampling by updating the proposal distribution in the latent space of a normalizing flow. Normalizing flows learn an invertible mapping from a target distribution to a simpler latent distribution. The latent space can be more easily explored during the search for a proposal distribution, and samples from the proposal distribution are recovered in the space of the target distribution via the invertible mapping. We empirically validate our methodology on simulated robotics applications such as autonomous racing and aircraft ground collision avoidance. 

**Abstract (ZH)**: 重要性采样是一种在蒙特卡洛模拟中用于偏置采样分布以朝向感兴趣的稀有事件的技术。通过为采样点分配适当的权重，重要性采样可以更高效地估计稀有事件或分布的尾部。然而，当提议分布不能有效覆盖目标分布时，重要性采样可能会失效。本文中，我们提出了一种通过在归一化流的潜在空间中更新提议分布来实现更高效采样的方法。归一化流学习从目标分布到更简单的潜在分布的可逆映射。在寻找提议分布时，潜在空间可以更容易地被探索，并且通过可逆映射可以从提议分布中恢复目标分布空间中的样本。我们通过模拟机器人应用（如自主赛车和航空器地面碰撞避免）的实验来验证我们的方法。 

---
# Over-the-Air Fair Federated Learning via Multi-Objective Optimization 

**Title (ZH)**: 基于多目标优化的空中公平联邦学习 

**Authors**: Shayan Mohajer Hamidi, Ali Bereyhi, Saba Asaad, H. Vincent Poor  

**Link**: [PDF](https://arxiv.org/pdf/2501.03392)  

**Abstract**: In federated learning (FL), heterogeneity among the local dataset distributions of clients can result in unsatisfactory performance for some, leading to an unfair model. To address this challenge, we propose an over-the-air fair federated learning algorithm (OTA-FFL), which leverages over-the-air computation to train fair FL models. By formulating FL as a multi-objective minimization problem, we introduce a modified Chebyshev approach to compute adaptive weighting coefficients for gradient aggregation in each communication round. To enable efficient aggregation over the multiple access channel, we derive analytical solutions for the optimal transmit scalars at the clients and the de-noising scalar at the parameter server. Extensive experiments demonstrate the superiority of OTA-FFL in achieving fairness and robust performance compared to existing methods. 

**Abstract (ZH)**: 在联邦学习（FL）中，客户端本地数据集分布的异质性可能导致某些模型性能不佳，从而导致不公平的模型。为了应对这一挑战，我们提出了一种基于空中计算的公平联邦学习算法（OTA-FFL），该算法利用空中计算来训练公平的FL模型。通过将FL形式化为一个多目标最小化问题，我们引入了修改后的Chebyshev方法来计算每个通信轮次中梯度聚合的自适应权重系数。为了在多址信道中实现高效的聚合，我们推导出了客户端和参数服务器处最优传输标量以及去噪标量的解析解。广泛的实验结果表明，相比于现有方法，OTA-FFL在实现公平性和鲁棒性能方面具有优越性。 

---
# Existential Crisis: A Social Robot's Reason for Being 

**Title (ZH)**: 存在危机：社会机器人的存在意义 

**Authors**: Dora Medgyesy, Joella Galas, Julian van Pol, Rustam Eynaliyev, Thijs Vollebregt  

**Link**: [PDF](https://arxiv.org/pdf/2501.03376)  

**Abstract**: As Robots become ever more important in our daily lives there's growing need for understanding how they're perceived by people. This study aims to investigate how the user perception of robots is influenced by displays of personality. Using LLMs and speech to text technology, we designed a within-subject study to compare two conditions: a personality-driven robot and a purely task-oriented, personality-neutral robot. Twelve participants, recruited from Socially Intelligent Robotics course at Vrije Universiteit Amsterdam, interacted with a robot Nao tasked with asking them a set of medical questions under both conditions. After completing both interactions, the participants completed a user experience questionnaire measuring their emotional states and robot perception using standardized questionnaires from the SRI and Psychology literature. 

**Abstract (ZH)**: 随着机器人在我们日常生活中变得越来越重要，了解人们对其的认知变得越来越必要。本研究旨在探讨机器人的个性展示如何影响用户的感知。通过使用大型语言模型（LLMs）和语音转文本技术，我们设计了一项单被试实验，比较了两种条件下的情况：一种是有个性特性的机器人和一种完全以任务为导向、无个性特征的机器人。来自荷兰自由大学（Vrije Universiteit Amsterdam）“社交智能机器人”课程的12名参与者，在两种条件下与一个名为Nao的机器人进行了互动，该机器人被要求向他们提出一系列医疗问题。在完成这两种互动后，参与者完成了用户体验问卷，通过SRI和心理学文献中的标准化问卷来测量他们的情绪状态和对机器人的感知。 

---
# License Plate Images Generation with Diffusion Models 

**Title (ZH)**: 使用扩散模型生成车牌图像 

**Authors**: Mariia Shpir, Nadiya Shvai, Amir Nakib  

**Link**: [PDF](https://arxiv.org/pdf/2501.03374)  

**Abstract**: Despite the evident practical importance of license plate recognition (LPR), corresponding research is limited by the volume of publicly available datasets due to privacy regulations such as the General Data Protection Regulation (GDPR). To address this challenge, synthetic data generation has emerged as a promising approach. In this paper, we propose to synthesize realistic license plates (LPs) using diffusion models, inspired by recent advances in image and video generation. In our experiments a diffusion model was successfully trained on a Ukrainian LP dataset, and 1000 synthetic images were generated for detailed analysis. Through manual classification and annotation of the generated images, we performed a thorough study of the model output, such as success rate, character distributions, and type of failures. Our contributions include experimental validation of the efficacy of diffusion models for LP synthesis, along with insights into the characteristics of the generated data. Furthermore, we have prepared a synthetic dataset consisting of 10,000 LP images, publicly available at this https URL. Conducted experiments empirically confirm the usefulness of synthetic data for the LPR task. Despite the initial performance gap between the model trained with real and synthetic data, the expansion of the training data set with pseudolabeled synthetic data leads to an improvement in LPR accuracy by 3% compared to baseline. 

**Abstract (ZH)**: 尽管车牌识别（LPR）具有显而易见的实用重要性，但由于隐私法规（如通用数据保护条例GDPR）的限制，相应的研究受到公开可用数据集规模的限制。为应对这一挑战，合成数据生成已成为一种有前景的方法。本文提出了一种使用扩散模型合成现实车牌（LP）的方法，受到了图像和视频生成领域最新进展的启发。在实验中，我们成功地在乌克兰车牌数据集上训练了一个扩散模型，并生成了1000张合成图像进行详细分析。通过人工分类和标注生成的图像，我们对模型输出进行了全面研究，包括成功率、字符分布以及失败类型等。我们的贡献包括实验验证扩散模型在车牌生成任务中的有效性，以及对生成数据特性的见解。此外，我们还提供了一个包含10,000张车牌图像的合成数据集，可从以下链接下载：[这里]. 实验结果表明合成数据对于LPR任务具有实用性。尽管用真实和合成数据训练的模型在初始表现上存在差距，但通过与伪标签合成数据扩展训练数据集，LPR准确性相对基线模型提高了3%。 

---
# Advanced Machine Learning Techniques for Social Support Detection on Social Media 

**Title (ZH)**: 社交媒体中社会支持检测的高级机器学习技术 

**Authors**: Olga Kolesnikova, Moein Shahiki Tash, Zahra Ahani, Ameeta Agrawal, Raul Monroy, Grigori Sidorov  

**Link**: [PDF](https://arxiv.org/pdf/2501.03370)  

**Abstract**: The widespread use of social media highlights the need to understand its impact, particularly the role of online social support. This study uses a dataset focused on online social support, which includes binary and multiclass classifications of social support content on social media. The classification of social support is divided into three tasks. The first task focuses on distinguishing between supportive and non-supportive. The second task aims to identify whether the support is directed toward an individual or a group. The third task categorizes the specific type of social support, grouping it into categories such as Nation, LGBTQ, Black people, Women, Religion, and Other (if it does not fit into the previously mentioned categories). To address data imbalances in these tasks, we employed K-means clustering for balancing the dataset and compared the results with the original unbalanced data. Using advanced machine learning techniques, including transformers and zero-shot learning approaches with GPT3, GPT4, and GPT4-o, we predict social support levels in various contexts. The effectiveness of the dataset is evaluated using baseline models across different learning approaches, with transformer-based methods demonstrating superior performance. Additionally, we achieved a 0.4\% increase in the macro F1 score for the second task and a 0.7\% increase for the third task, compared to previous work utilizing traditional machine learning with psycholinguistic and unigram-based TF-IDF values. 

**Abstract (ZH)**: 社交媒体的广泛应用突显了理解其影响的重要性，尤其是在线社会支持的作用。本研究使用了一个专注于在线社会支持的数据集，该数据集包括社交媒体上支持内容的二分类和多分类。社会支持的分类分为三个任务。第一个任务专注于区分支持与非支持内容。第二个任务旨在识别支持是针对个人还是群体。第三个任务对具体类型的支持进行分类，将其分为国族、LGBTQ、黑人、女性、宗教和其他（如果不符合上述分类）。为了处理这些任务中的数据不平衡问题，我们采用了K-means聚类来平衡数据集，并将结果与原始的未平衡数据进行了对比。利用先进的机器学习技术，包括变压器和零样本学习方法（使用GPT3、GPT4和GPT4-o），我们预测了不同情境下的社会支持水平。通过不同的学习方法使用基线模型评估数据集的有效性，以变压器为基础的方法表现出了更优的效果。此外，我们在第二个任务中实现了0.4%的宏F1分数提高，在第三个任务中实现了0.7%的宏F1分数提高，这比之前使用传统机器学习方法（基于心理语言学和单词TF-IDF值）的工作有所改进。 

---
# FTA-FTL: A Fine-Tuned Aggregation Federated Transfer Learning Scheme for Lithology Microscopic Image Classification 

**Title (ZH)**: FTA-FTL：一种 fine-tuned 聚合联邦转移学习方案用于岩石微视图像分类 

**Authors**: Keyvan RahimiZadeh, Ahmad Taheri, Jan Baumbach, Esmael Makarian, Abbas Dehghani, Bahman Ravaei, Bahman Javadi, Amin Beheshti  

**Link**: [PDF](https://arxiv.org/pdf/2501.03349)  

**Abstract**: Lithology discrimination is a crucial activity in characterizing oil reservoirs, and processing lithology microscopic images is an essential technique for investigating fossils and minerals and geological assessment of shale oil exploration. In this way, Deep Learning (DL) technique is a powerful approach for building robust classifier models. However, there is still a considerable challenge to collect and produce a large dataset. Transfer-learning and data augmentation techniques have emerged as popular approaches to tackle this problem. Furthermore, due to different reasons, especially data privacy, individuals, organizations, and industry companies often are not willing to share their sensitive data and information. Federated Learning (FL) has emerged to train a highly accurate central model across multiple decentralized edge servers without transferring sensitive data, preserving sensitive data, and enhancing security. This study involves two phases; the first phase is to conduct Lithology microscopic image classification on a small dataset using transfer learning. In doing so, various pre-trained DL model architectures are comprehensively compared for the classification task. In the second phase, we formulated the classification task to a Federated Transfer Learning (FTL) scheme and proposed a Fine-Tuned Aggregation strategy for Federated Learning (FTA-FTL). In order to perform a comprehensive experimental study, several metrics such as accuracy, f1 score, precision, specificity, sensitivity (recall), and confusion matrix are taken into account. The results are in excellent agreement and confirm the efficiency of the proposed scheme, and show that the proposed FTA-FTL algorithm is capable enough to achieve approximately the same results obtained by the centralized implementation for Lithology microscopic images classification task. 

**Abstract (ZH)**: 岩石类型识别是表征油气藏的关键活动，处理岩石微相图像是一项研究化石、矿物以及页岩油地质评估的重要技术。因此，深度学习（DL）技术是构建稳健分类模型的有效方法。然而，收集和生成大量数据集仍然面临巨大挑战。迁移学习和数据增强技术已逐渐成为解决这一问题的流行方法。此外，由于各种原因，特别是数据隐私问题，个人、组织和工业公司往往不愿意共享其敏感数据和信息。联邦学习（FL）由此出现，可以在多个分散的边缘服务器上训练一个高精度的中央模型，而无需转移敏感数据，保护敏感数据，并增强安全性。

本研究分为两个阶段：第一阶段是在少量数据集上使用迁移学习进行岩石微相图像分类，全面比较了各类预训练DL模型架构在分类任务中的性能。第二阶段，我们将分类任务转化为联邦迁移学习（FTL）方案，并提出了一种改进的联邦学习聚合策略（FTA-FTL）。为了进行全面的实验研究，我们考虑了准确率、F1分数、精确率、特异度、召回率（敏感性）以及混淆矩阵等多个指标。研究结果表明，所提出的方案效果显著，证明了该方案的有效性，并显示出所提出的FTA-FTL算法在岩石微相图像分类任务中能够达到与集中实施相近的结果。 

---
# Analyzing Bias in Swiss Federal Supreme Court Judgments Using Facebook's Holistic Bias Dataset: Implications for Language Model Training 

**Title (ZH)**: 使用Facebook的综合性偏见数据集分析瑞士联邦最高法院判决中的偏见：对语言模型训练的影响 

**Authors**: Sabine Wehnert, Muhammet Ertas, Ernesto William De Luca  

**Link**: [PDF](https://arxiv.org/pdf/2501.03324)  

**Abstract**: Natural Language Processing (NLP) is vital for computers to process and respond accurately to human language. However, biases in training data can introduce unfairness, especially in predicting legal judgment. This study focuses on analyzing biases within the Swiss Judgment Prediction Dataset (SJP-Dataset). Our aim is to ensure unbiased factual descriptions essential for fair decision making by NLP models in legal contexts. We analyze the dataset using social bias descriptors from the Holistic Bias dataset and employ advanced NLP techniques, including attention visualization, to explore the impact of dispreferred descriptors on model predictions. The study identifies biases and examines their influence on model behavior. Challenges include dataset imbalance and token limits affecting model performance. 

**Abstract (ZH)**: 自然语言处理（NLP）对于计算机准确处理和回应人类语言至关重要。然而，训练数据中的偏见可能导致不公平性，特别是在预测法律判决方面。本研究重点关注分析瑞士判决预测数据集（SJP-Dataset）中的偏见。我们的目标是确保NLP模型在法律环境下进行公平决策所需的无偏客观描述。我们使用整体偏见数据集中的社会偏见描述符来分析数据集，并采用先进的NLP技术（包括注意力可视化），以探究不受欢迎描述符对模型预测的影响。本研究识别了偏见并探讨了它们对模型行为的影响。面临的挑战包括数据集不平衡和词汇量限制影响模型性能。 

---
# Rethinking Byzantine Robustness in Federated Recommendation from Sparse Aggregation Perspective 

**Title (ZH)**: 从稀疏聚合视角重新审视联邦推荐中的拜占庭容错性 

**Authors**: Zhongjian Zhang, Mengmei Zhang, Xiao Wang, Lingjuan Lyu, Bo Yan, Junping Du, Chuan Shi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03301)  

**Abstract**: To preserve user privacy in recommender systems, federated recommendation (FR) based on federated learning (FL) emerges, keeping the personal data on the local client and updating a model collaboratively. Unlike FL, FR has a unique sparse aggregation mechanism, where the embedding of each item is updated by only partial clients, instead of full clients in a dense aggregation of general FL. Recently, as an essential principle of FL, model security has received increasing attention, especially for Byzantine attacks, where malicious clients can send arbitrary updates. The problem of exploring the Byzantine robustness of FR is particularly critical since in the domains applying FR, e.g., e-commerce, malicious clients can be injected easily by registering new accounts. However, existing Byzantine works neglect the unique sparse aggregation of FR, making them unsuitable for our problem. Thus, we make the first effort to investigate Byzantine attacks on FR from the perspective of sparse aggregation, which is non-trivial: it is not clear how to define Byzantine robustness under sparse aggregations and design Byzantine attacks under limited knowledge/capability. In this paper, we reformulate the Byzantine robustness under sparse aggregation by defining the aggregation for a single item as the smallest execution unit. Then we propose a family of effective attack strategies, named Spattack, which exploit the vulnerability in sparse aggregation and are categorized along the adversary's knowledge and capability. Extensive experimental results demonstrate that Spattack can effectively prevent convergence and even break down defenses under a few malicious clients, raising alarms for securing FR systems. 

**Abstract (ZH)**: 为了在推荐系统中保护用户隐私，基于联邦学习（FL）的联邦推荐（FR）应运而生，将个人数据保留在本地客户端，并通过合作更新模型。与传统的密集聚合联邦学习不同，FR 具有独特的稀疏聚合机制，即每个项目的嵌入仅由部分客户端更新，而不是像通用联邦学习中的所有客户端一起更新。近年来，尤其是在联邦学习中，模型安全性越来越引起人们的关注，特别是在 Byzantine 攻击方面，其中恶意客户端可以发送任意更新。由于联邦推荐的应用领域（例如电子商务），容易通过注册新账户注入恶意客户端，因此探索 FR 的 Byzantine 抗性尤为重要。然而，现有的 Byzantine 相关工作忽视了 FR 的独特稀疏聚合机制，使得它们不适合解决当前问题。因此，我们首次从稀疏聚合的角度出发，研究 FR 中的 Byzantine 攻击，这是一个不简单的任务：在稀疏聚合下定义 Byzantine 抗性以及设计在有限知识/能力下的 Byzantine 攻击方法尚不清晰。本文重新定义了在稀疏聚合下的 Byzantine 抗性，将单个项目聚合视为最小执行单元。我们还提出了名为 Spattack 的一系列有效的攻击策略，利用稀疏聚合中的漏洞，并根据敌手的知识和能力进行分类。广泛的实验结果表明，Spattack 可以有效防止收敛，并且在少数恶意客户端的情况下甚至可以突破防御，这为保护 FR 系统发出了警报。 

---
# A Soft Sensor Method with Uncertainty-Awareness and Self-Explanation Based on Large Language Models Enhanced by Domain Knowledge Retrieval 

**Title (ZH)**: 基于领域知识检索增强的大语言模型的不确定性意识与自我解释软传感器方法 

**Authors**: Shuo Tong, Runyuan Guo, Wenqing Wang, Xueqiong Tian, Lingyun Wei, Lin Zhang, Huayong Wu, Ding Liu, Youmin Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03295)  

**Abstract**: Data-driven soft sensors are crucial in predicting key performance indicators in industrial systems. However, current methods predominantly rely on the supervised learning paradigms of parameter updating, which inherently faces challenges such as high development costs, poor robustness, training instability, and lack of interpretability. Recently, large language models (LLMs) have demonstrated significant potential across various domains, notably through In-Context Learning (ICL), which enables high-performance task execution with minimal input-label demonstrations and no prior training. This paper aims to replace supervised learning with the emerging ICL paradigm for soft sensor modeling to address existing challenges and explore new avenues for advancement. To achieve this, we propose a novel framework called the Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS), which includes the Zero-shot Auxiliary Variable Selector (LLM-ZAVS) and the Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS). The LLM-ZAVS retrieves from the Industrial Knowledge Vector Storage to enhance LLMs' domain-specific knowledge, enabling zero-shot auxiliary variable selection. In the LLM-UFSS, we utilize text-based context demonstrations of structured data to prompt LLMs to execute ICL for predicting and propose a context sample retrieval augmentation strategy to improve performance. Additionally, we explored LLMs' AIGC and probabilistic characteristics to propose self-explanation and uncertainty quantification methods for constructing a trustworthy soft sensor. Extensive experiments demonstrate that our method achieved state-of-the-art predictive performance, strong robustness, and flexibility, effectively mitigates training instability found in traditional methods. To the best of our knowledge, this is the first work to establish soft sensor utilizing LLMs. 

**Abstract (ZH)**: 数据驱动的软传感器在预测工业系统中的关键性能指标方面至关重要。然而，当前的方法主要依赖监督学习中的参数更新框架，这本身就面临着高开发成本、鲁棒性差、训练不稳定性和缺乏可解释性等挑战。近年来，大型语言模型（LLMs）在各个领域展现出了巨大的潜力，特别是通过上下文学习（In-Context Learning, ICL），能够在最少的输入-标签示范和无需先验训练的情况下实现高性能的任务执行。本文旨在利用新兴的ICL范式替换监督学习，以解决现有的挑战并探索新的发展路径。为此，我们提出了一种名为Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS)的新框架，该框架包括Zero-shot Auxiliary Variable Selector (LLM-ZAVS)和Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS)。LLM-ZAVS从工业知识向量存储中检索信息，以增强LLMs的领域特定知识，实现零样本辅助变量选择。在LLM-UFSS中，我们利用结构化数据的文本上下文示范来驱动LLMs执行ICL以进行预测，并提出了一种上下文样本检索增强策略以提高性能。此外，我们探索了LLMs的特性，包括生成式人工智能（AIGC）和概率特性，并提出了自我解释和不确定性量化方法，以构建可信的软传感器。广泛实验结果表明，我们的方法达到了最先进的预测性能、强大的鲁棒性和灵活性，有效缓解了传统方法中发现的训练稳定性问题。据我们所知，这是首次利用LLMs构建软传感器的工作。 

---
# Multi-Modal One-Shot Federated Ensemble Learning for Medical Data with Vision Large Language Model 

**Title (ZH)**: 基于视觉大型语言模型的多模态一-shot联邦集成学习在医疗数据中的应用 

**Authors**: Naibo Wang, Yuchen Deng, Shichen Fan, Jianwei Yin, See-Kiong Ng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03292)  

**Abstract**: Federated learning (FL) has attracted considerable interest in the medical domain due to its capacity to facilitate collaborative model training while maintaining data privacy. However, conventional FL methods typically necessitate multiple communication rounds, leading to significant communication overhead and delays, especially in environments with limited bandwidth. One-shot federated learning addresses these issues by conducting model training and aggregation in a single communication round, thereby reducing communication costs while preserving privacy. Among these, one-shot federated ensemble learning combines independently trained client models using ensemble techniques such as voting, further boosting performance in non-IID data scenarios. On the other hand, existing machine learning methods in healthcare predominantly use unimodal data (e.g., medical images or textual reports), which restricts their diagnostic accuracy and comprehensiveness. Therefore, the integration of multi-modal data is proposed to address these shortcomings. In this paper, we introduce FedMME, an innovative one-shot multi-modal federated ensemble learning framework that utilizes multi-modal data for medical image analysis. Specifically, FedMME capitalizes on vision large language models to produce textual reports from medical images, employs a BERT model to extract textual features from these reports, and amalgamates these features with visual features to improve diagnostic accuracy. Experimental results show that our method demonstrated superior performance compared to existing one-shot federated learning methods in healthcare scenarios across four datasets with various data distributions. For instance, it surpasses existing one-shot federated learning approaches by more than 17.5% in accuracy on the RSNA dataset when applying a Dirichlet distribution with ($\alpha$ = 0.3). 

**Abstract (ZH)**: 联邦学习（FL）在医疗领域引起了广泛关注，因为它能够促进模型协作训练的同时保持数据隐私。然而，传统的FL方法通常需要多次通信轮次，导致显著的通信开销和延迟，尤其是在带宽有限的环境中。一次性联邦学习通过在单次通信轮次中进行模型训练和聚合，解决了这些问题，从而降低了通信成本并保持了隐私性。其中，一次性联邦集成学习结合了独立训练的客户端模型，并使用投票等集成技术进一步提高了在非IID数据场景中的性能。另一方面，现有医疗领域的机器学习方法主要使用单一模态数据（如医学图像或文本报告），这限制了它们的诊断准确性和全面性。因此，提出了集成多模态数据来弥补这些不足。在本文中，我们介绍了一种名为FedMME的创新一次性多模态联邦集成学习框架，该框架利用多模态数据进行医学图像分析。具体来说，FedMME利用愿景大型语言模型从医学图像生成文本报告，采用BERT模型从这些报告中提取文本特征，并将这些特征与视觉特征结合以提高诊断准确性。实验结果表明，与医疗场景中现有的一次性联邦学习方法相比，我们的方法在四个具有不同数据分布的数据库上表现更为优越。例如，当在RSNA数据集上采用狄利克雷分布（$\alpha$ = 0.3）时，其准确率优于现有的一次性联邦学习方法的17.5%以上。 

---
# A Decision-Based Heterogenous Graph Attention Network for Multi-Class Fake News Detection 

**Title (ZH)**: 基于决策的异构图注意网络在多类别假新闻检测中的应用 

**Authors**: Batool Lakzaei, Mostafa Haghir Chehreghani, Alireza Bagheri  

**Link**: [PDF](https://arxiv.org/pdf/2501.03290)  

**Abstract**: A promising tool for addressing fake news detection is Graph Neural Networks (GNNs). However, most existing GNN-based methods rely on binary classification, categorizing news as either real or fake. Additionally, traditional GNN models use a static neighborhood for each node, making them susceptible to issues like over-squashing. In this paper, we introduce a novel model named Decision-based Heterogeneous Graph Attention Network (DHGAT) for fake news detection in a semi-supervised setting. DHGAT effectively addresses the limitations of traditional GNNs by dynamically optimizing and selecting the neighborhood type for each node in every layer. It represents news data as a heterogeneous graph where nodes (news items) are connected by various types of edges. The architecture of DHGAT consists of a decision network that determines the optimal neighborhood type and a representation network that updates node embeddings based on this selection. As a result, each node learns an optimal and task-specific computational graph, enhancing both the accuracy and efficiency of the fake news detection process. We evaluate DHGAT on the LIAR dataset, a large and challenging dataset for multi-class fake news detection, which includes news items categorized into six classes. Our results demonstrate that DHGAT outperforms existing methods, improving accuracy by approximately 4% and showing robustness with limited labeled data. 

**Abstract (ZH)**: 对抗虚假信息检测的一个有希望的工具是图神经网络（GNNs）。然而，大多数现有的GNN基方法依赖于二分类，将新闻分为真实或虚假两类。此外，传统的GNN模型使用静态邻域，使其容易受到过度挤压等问题的影响。在本文中，我们介绍了一种名为基于决策的异质图注意力网络（DHGAT）的新模型，用于半监督环境下的虚假新闻检测。DHGAT通过在每层中动态优化和选择每个节点的邻域类型，有效地解决了传统GNN的局限性。它将新闻数据表示为一个异质图，节点（新闻项）通过各种类型的边连接。DHGAT的架构包括一个决策网络，用于确定最优的邻域类型，以及一个表示网络，根据此选择来更新节点嵌入。结果，每个节点学习到一个最优且任务特定的计算图，这增强了虚假新闻检测的准确性和效率。我们使用LIAR数据集评估了DHGAT，这是一个用于多类别虚假新闻检测的大规模且具有挑战性的数据集，其中包括被分类为六类的新闻项。我们的结果表明，DHGAT在准确率上优于现有方法，提高了约4%，并且即使在有限的标记数据下也表现出强大的鲁棒性。 

---
# CodeVision: Detecting LLM-Generated Code Using 2D Token Probability Maps and Vision Models 

**Title (ZH)**: CodeVision：使用2D令牌概率图和视觉模型检测LLM生成的代码 

**Authors**: Zhenyu Xu, Victor S. Sheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03288)  

**Abstract**: The rise of large language models (LLMs) like ChatGPT has significantly improved automated code generation, enhancing software development efficiency. However, this introduces challenges in academia, particularly in distinguishing between human-written and LLM-generated code, which complicates issues of academic integrity. Existing detection methods, such as pre-trained models and watermarking, face limitations in adaptability and computational efficiency. In this paper, we propose a novel detection method using 2D token probability maps combined with vision models, preserving spatial code structures such as indentation and brackets. By transforming code into log probability matrices and applying vision models like Vision Transformers (ViT) and ResNet, we capture both content and structure for more accurate detection. Our method shows robustness across multiple programming languages and improves upon traditional detectors, offering a scalable and computationally efficient solution for identifying LLM-generated code. 

**Abstract (ZH)**: 大型语言模型（LLMs）如ChatGPT的兴起显著提升了自动代码生成的能力，提高了软件开发的效率。然而，这在学术界引入了新的挑战，尤其是在区分人类编写的代码和LLM生成的代码方面，这使得学术诚信问题复杂化。现有的检测方法，如预训练模型和水印技术，在适应性和计算效率方面存在局限性。在本文中，我们提出了一种新的检测方法，结合使用2D标记概率图和视觉模型，保留了代码的空间结构，如缩进和括号。通过将代码转换为对数概率矩阵，并应用Vision Transformers (ViT)和ResNet等视觉模型，我们能够同时捕捉内容和结构，从而提高检测的准确性。我们的方法在多种编程语言中表现出强大的鲁棒性，并且相比传统检测器有所改进，提供了一种可扩展且计算高效的解决方案，用于识别LLM生成的代码。 

---
# Revolutionizing Encrypted Traffic Classification with MH-Net: A Multi-View Heterogeneous Graph Model 

**Title (ZH)**: 用MH-Net革命性地重塑加密流量分类：一种多视图异构图模型 

**Authors**: Haozhen Zhang, Haodong Yue, Xi Xiao, Le Yu, Qing Li, Zhen Ling, Ye Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03279)  

**Abstract**: With the growing significance of network security, the classification of encrypted traffic has emerged as an urgent challenge. Traditional byte-based traffic analysis methods are constrained by the rigid granularity of information and fail to fully exploit the diverse correlations between bytes. To address these limitations, this paper introduces MH-Net, a novel approach for classifying network traffic that leverages multi-view heterogeneous traffic graphs to model the intricate relationships between traffic bytes. The essence of MH-Net lies in aggregating varying numbers of traffic bits into multiple types of traffic units, thereby constructing multi-view traffic graphs with diverse information granularities. By accounting for different types of byte correlations, such as header-payload relationships, MH-Net further endows the traffic graph with heterogeneity, significantly enhancing model performance. Notably, we employ contrastive learning in a multi-task manner to strengthen the robustness of the learned traffic unit representations. Experiments conducted on the ISCX and CIC-IoT datasets for both the packet-level and flow-level traffic classification tasks demonstrate that MH-Net achieves the best overall performance compared to dozens of SOTA methods. 

**Abstract (ZH)**: 随着网络安全性的重要性日益凸显，加密流量的分类已经成为一个迫切需要解决的挑战。传统的基于字节的流量分析方法受到信息粒度僵化的影响，无法充分利用字节之间多样的关联性。为了解决这些问题，本文提出了一种新的方法MH-Net，该方法利用多视图异构流量图来建模流量字节之间的复杂关系。MH-Net的核心在于将不同数量的流量位聚合为多种类型的流量单元，从而构建具有多种信息粒度的多视图流量图。通过考虑不同类型的字节关联性，如头部-负载关系，MH-Net进一步赋予流量图异构性，显著提高了模型的性能。值得注意的是，我们采用了多任务形式的对比学习来增强学习到的流量单元表示的鲁棒性。在ISCX和CIC-IoT数据集上的包级和流级流量分类任务实验表明，MH-Net在整体性能上优于几十种现有的最优方法。 

---
# ComMer: a Framework for Compressing and Merging User Data for Personalization 

**Title (ZH)**: ComMer：一种用于个性化压缩和合并用户数据的框架 

**Authors**: Yoel Zeldes, Amir Zait, Ilia Labzovsky, Danny Karmon, Efrat Farkash  

**Link**: [PDF](https://arxiv.org/pdf/2501.03276)  

**Abstract**: Large Language Models (LLMs) excel at a wide range of tasks, but adapting them to new data, particularly for personalized applications, poses significant challenges due to resource and computational constraints. Existing methods either rely on exposing fresh data to the model through the prompt, which is limited by context size and computationally expensive at inference time, or fine-tuning, which incurs substantial training and update costs. In this paper, we introduce ComMer - Compress and Merge - a novel framework that efficiently personalizes LLMs by compressing users' documents into compact representations, which are then merged and fed into a frozen LLM. We evaluate ComMer on two types of personalization tasks - personalized skill learning, using the tweet paraphrasing dataset and the personalized news headline generation dataset from the LaMP benchmark, and knowledge-intensive, using the PerLTQA dataset. Our experiments demonstrate that in constrained inference budget scenarios ComMer achieves superior quality in skill learning tasks, while highlighting limitations in knowledge-intensive settings due to the loss of detailed information. These results offer insights into trade-offs and potential optimizations in multi-document compression for personalization. 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种任务中表现出色，但将它们适应新的数据，尤其是针对个性化应用时，由于资源和计算限制而面临显著挑战。现有方法要么依赖通过提示向模型提供新鲜数据，这受限于上下文大小并在推理时计算成本高昂，要么依赖于微调，这涉及大量培训和更新成本。在本文中，我们引入了一种名为ComMer（Compress and Merge）的新框架，该框架通过将用户的文档压缩为紧凑表示，然后合并并输入冻结的LLM，有效地个性化了LLMs。我们对两种类型的个性化任务进行了评估：1）个人技能学习，使用推特重写数据集和个人化新闻标题生成数据集（来自LaMP基准测试的数据集）；2）知识密集型任务，使用PerLTQA数据集。我们的实验表明，在受限的推理预算场景中，ComMer在技能学习任务中实现了更高的质量，但在知识密集型设置中由于丢失了详细信息而显示出局限性。这些结果提供了多文档压缩在个性化应用中权衡和潜在优化方面的见解。 

---
# Strategic Fusion Optimizes Transformer Compression 

**Title (ZH)**: 战略融合优化变压器压缩 

**Authors**: Md Shoaibur Rahman  

**Link**: [PDF](https://arxiv.org/pdf/2501.03273)  

**Abstract**: This study investigates transformer model compression by systematically pruning its layers. We evaluated 14 pruning strategies across nine diverse datasets, including 12 strategies based on different signals obtained from layer activations, mutual information, gradients, weights, and attention. To address the limitations of single-signal strategies, we introduced two fusion strategies, linear regression and random forest, which combine individual strategies (i.e., strategic fusion), for more informed pruning decisions. Additionally, we applied knowledge distillation to mitigate any accuracy loss during layer pruning. Our results reveal that random forest strategic fusion outperforms individual strategies in seven out of nine datasets and achieves near-optimal performance in the other two. The distilled random forest surpasses the original accuracy in six datasets and mitigates accuracy drops in the remaining three. Knowledge distillation also improves the accuracy-to-size ratio by an average factor of 18.84 across all datasets. Supported by mathematical foundations and biological analogies, our findings suggest that strategically combining multiple signals can lead to efficient, high-performing transformer models for resource-constrained applications. 

**Abstract (ZH)**: 本研究系统性地探讨了变压器模型压缩方法，通过逐步剪枝其层结构来进行研究。我们对九个不同的数据集共进行了14种剪枝策略的评估，这些数据集包括12种基于层激活、互信息、梯度、权重和注意力等不同信号的剪枝策略。为了弥补单信号策略的局限性，我们引入了两种融合策略，即线性回归和随机森林，将个体策略进行组合（即策略性融合），以做出更明智的剪枝决策。此外，我们还应用了知识蒸馏方法，以减轻层剪枝过程中的准确率损失。研究结果表明，在九个数据集中，随机森林策略性融合在七个数据集中表现优于单一策略，并在另外两个数据集上接近最优性能。蒸馏后的随机森林在六个数据集中超过了原模型的准确率，并在剩余三个数据集中减少了准确率的下降。同时，在所有数据集上，知识蒸馏方法平均提高了约18.84倍的准确率与模型大小比。基于数学基础和生物学类比，我们的研究发现表明，将多种信号策略性结合可以导致在资源受限应用中高效且高性能的变压器模型。 

---
# Backdoor Token Unlearning: Exposing and Defending Backdoors in Pretrained Language Models 

**Title (ZH)**: 后门标记遗忘：暴露并防御预训练语言模型中的后门攻击 

**Authors**: Peihai Jiang, Xixiang Lyu, Yige Li, Jing Ma  

**Link**: [PDF](https://arxiv.org/pdf/2501.03272)  

**Abstract**: Supervised fine-tuning has become the predominant method for adapting large pretrained models to downstream tasks. However, recent studies have revealed that these models are vulnerable to backdoor attacks, where even a small number of malicious samples can successfully embed backdoor triggers into the model. While most existing defense methods focus on post-training backdoor defense, efficiently defending against backdoor attacks during training phase remains largely unexplored. To address this gap, we propose a novel defense method called Backdoor Token Unlearning (BTU), which proactively detects and neutralizes trigger tokens during the training stage. Our work is based on two key findings: 1) backdoor learning causes distinctive differences between backdoor token parameters and clean token parameters in word embedding layers, and 2) the success of backdoor attacks heavily depends on backdoor token parameters. The BTU defense leverages these properties to identify aberrant embedding parameters and subsequently removes backdoor behaviors using a fine-grained unlearning technique. Extensive evaluations across three datasets and four types of backdoor attacks demonstrate that BTU effectively defends against these threats while preserving the model's performance on primary tasks. Our code is available at this https URL. 

**Abstract (ZH)**: 监督微调已成为将大规模预训练模型适应下游任务的主要方法。然而，近期研究揭示了这些模型易受后门攻击的影响，即使少量恶意样本也能成功将后门触发器嵌入模型中。尽管现有大多数防御方法侧重于后训练阶段的后门防御，但在训练阶段有效防御后门攻击的研究尚未充分展开。为弥补这一空白，我们提出了一种名为后门标记遗忘（BTU，Backdoor Token Unlearning）的新防御方法，该方法在训练阶段主动检测并抑制触发器标记。我们的工作基于两个关键发现：1）后门学习导致在词嵌入层中后门标记参数与干净标记参数之间存在显著差异，2）后门攻击的成功高度依赖于后门标记参数。BTU 防御利用这些特性来识别异常的嵌入参数，并使用精细粒度的遗忘技术后续消除后门行为。对三个数据集和四种类型后门攻击的广泛评估表明，BTU 能有效地防御这些威胁同时保持模型在主要任务上的性能。我们的代码可在以下链接获取：[此处填写实际链接]。 

---
# A Semantically-Aware, Kernel-Enhanced, and Divergence-Rich Paradigm for Direct Preference Optimization 

**Title (ZH)**: 一种语义意识强、核增强且富有差异性的直接偏好优化范式 

**Authors**: Amitava Das, Suranjana Trivedy, Danush Khanna, Rajarshi Roy, Gurpreet Singh, Basab Ghosh, Yaswanth Narsupalli, Vinija Jain, Vasu Sharma, Aishwarya Naresh Reganti, Aman Chadha  

**Link**: [PDF](https://arxiv.org/pdf/2501.03271)  

**Abstract**: The rapid rise of large language models (LLMs) has unlocked many applications but also underscores the challenge of aligning them with diverse values and preferences. Direct Preference Optimization (DPO) is central to alignment but constrained by fixed divergences and limited feature transformations. We propose DPO-Kernels, which integrates kernel methods to address these issues through four key contributions: (i) Kernelized Representations with polynomial, RBF, Mahalanobis, and spectral kernels for richer transformations, plus a hybrid loss combining embedding-based and probability-based objectives; (ii) Divergence Alternatives (Jensen-Shannon, Hellinger, Renyi, Bhattacharyya, Wasserstein, and f-divergences) for greater stability; (iii) Data-Driven Selection metrics that automatically choose the best kernel-divergence pair; and (iv) a Hierarchical Mixture of Kernels for both local precision and global modeling. Evaluations on 12 datasets demonstrate state-of-the-art performance in factuality, safety, reasoning, and instruction following. Grounded in Heavy-Tailed Self-Regularization, DPO-Kernels maintains robust generalization for LLMs, offering a comprehensive resource for further alignment research. 

**Abstract (ZH)**: 大型语言模型（LLMs）的迅速崛起解锁了众多应用，同时也突显了将其与多样价值观和偏好对齐的挑战。直接偏好优化（DPO）是实现对齐的核心方法，但受限于固定的差异度量和有限的特征变换。我们提出了DPO-Kernels，通过四种关键贡献结合核方法来解决这些问题：（i）核化表示，包括多项式核、高斯核、马氏距离核和谱核，以及结合嵌入和概率目标的混合损失，以实现更丰富的变换；（ii）差异度量替代方法（如詹森-沙恩差异度、Hellinger差异度、Rényi差异度、巴特赤低差异度、Wasserstein距离和f-差异度），以提高稳定性；（iii）数据驱动选择度量，能够自动选择最佳核-差异度配对；（iv）分层核混合，同时提供局部精度和全局建模。在12个数据集上的评估结果显示，DPO-Kernels在事实性、安全性、推理和指令跟随方面都达到了最先进的性能。基于重尾自我正则化，DPO-Kernels为LLMs提供了稳健的泛化能力，并为进一步的对齐研究提供了全面的资源。 

---
# Heterogeneous Graph Pre-training Based Model for Secure and Efficient Prediction of Default Risk Propagation among Bond Issuers 

**Title (ZH)**: 基于异构图预训练的模型：债券发行人之间违约风险传播的安全高效预测 

**Authors**: Xurui Li, Xin Shan, Wenhao Yin, Haijiao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03268)  

**Abstract**: Efficient prediction of default risk for bond-issuing enterprises is pivotal for maintaining stability and fostering growth in the bond market. Conventional methods usually rely solely on an enterprise's internal data for risk assessment. In contrast, graph-based techniques leverage interconnected corporate information to enhance default risk identification for targeted bond issuers. Traditional graph techniques such as label propagation algorithm or deepwalk fail to effectively integrate a enterprise's inherent attribute information with its topological network data. Additionally, due to data scarcity and security privacy concerns between enterprises, end-to-end graph neural network (GNN) algorithms may struggle in delivering satisfactory performance for target tasks. To address these challenges, we present a novel two-stage model. In the first stage, we employ an innovative Masked Autoencoders for Heterogeneous Graph (HGMAE) to pre-train on a vast enterprise knowledge graph. Subsequently, in the second stage, a specialized classifier model is trained to predict default risk propagation probabilities. The classifier leverages concatenated feature vectors derived from the pre-trained encoder with the enterprise's task-specific feature vectors. Through the two-stage training approach, our model not only boosts the importance of unique bond characteristics for specific default prediction tasks, but also securely and efficiently leverage the global information pre-trained from other enterprises. Experimental results demonstrate that our proposed model outperforms existing approaches in predicting default risk for bond issuers. 

**Abstract (ZH)**: 债券发行企业违约风险的有效预测对于保持债券市场稳定性和促进其增长至关重要。传统方法通常仅依靠企业的内部数据进行风险评估。相比之下，基于图的技术通过利用企业之间相互联系的信息来增强对目标债券发行企业违约风险的识别能力。传统的基于图的技术，如标签传播算法或DeepWalk，难以有效整合企业的固有属性信息与其拓扑网络数据。此外，由于企业之间的数据稀缺性和安全隐私问题，端到端的图神经网络（GNN）算法可能会在执行特定任务时表现出色。为应对这些挑战，我们提出了一种新颖的两阶段模型。在第一阶段，我们使用掩码自编码器（Heterogeneous Graph，简称HGMAE）对企业知识图进行预训练。随后，在第二阶段，通过专门的分类器模型对违约风险传播概率进行预测。该分类器利用预训练编码器和企业特定任务特征向量的拼接特征向量进行学习。通过两阶段的训练方法，我们的模型不仅加强了特定违约预测任务中债券独特特征的重要性，还在保护企业和安全隐私的前提下，高效地利用了其他企业预训练的全局信息。实验证明，我们的模型在预测债券发行企业的违约风险方面优于现有方法。 

---
# LLM Content Moderation and User Satisfaction: Evidence from Response Refusals in Chatbot Arena 

**Title (ZH)**: 大语言模型内容审核与用户满意度：聊天机器人领域中拒绝对话响应的实证证据 

**Authors**: Stefan Pasch  

**Link**: [PDF](https://arxiv.org/pdf/2501.03266)  

**Abstract**: LLM safety and ethical alignment are widely discussed, but the impact of content moderation on user satisfaction remains underexplored. To address this, we analyze nearly 50,000 Chatbot Arena response-pairs using a novel fine-tuned RoBERTa model, that we trained on hand-labeled data to disentangle refusals due to ethical concerns from other refusals due to technical disabilities or lack of information. Our findings reveal a significant refusal penalty on content moderation, with users choosing ethical-based refusals roughly one-fourth as often as their preferred LLM response compared to standard responses. However, the context and phrasing play critical roles: refusals on highly sensitive prompts, such as illegal content, achieve higher win rates than less sensitive ethical concerns, and longer responses closely aligned with the prompt perform better. These results emphasize the need for nuanced moderation strategies that balance ethical safeguards with user satisfaction. Moreover, we find that the refusal penalty is notably lower in evaluations using the LLM-as-a-Judge method, highlighting discrepancies between user and automated assessments. 

**Abstract (ZH)**: 大语言模型的安全性和伦理对齐已被广泛讨论，但内容审核对用户满意度的影响尚未得到充分探索。为了解决这一问题，我们使用一种新的微调RoBERTa模型分析了近50,000个Chatbot Arena响应对，并在手动标注的数据上对该模型进行了训练，以区分由于伦理原因拒绝和由于技术限制或信息不足而拒绝的情况。我们的研究发现，内容审核带来了显著的拒绝惩罚，用户选择基于伦理的拒绝大约只有其首选大语言模型（LLM）响应的四分之一频率。然而，上下文和表述方式至关重要：在高度敏感的提示（如非法内容）上拒绝的情况，其胜出率高于较为敏感的伦理问题，而与提示紧密契合的较长响应表现更好。这些结果强调了需要在伦理保护与用户满意度之间找到微妙平衡的必要性。此外，我们发现，在LLM作为法官的方法下进行评估时，拒绝惩罚显著较低，这突显了用户评估与自动化评估之间的差异。 

---
# Optimizing Edge AI: A Comprehensive Survey on Data, Model, and System Strategies 

**Title (ZH)**: 优化边缘人工智能：关于数据、模型和系统策略的综合综述 

**Authors**: Xubin Wang, Weijia Jia  

**Link**: [PDF](https://arxiv.org/pdf/2501.03265)  

**Abstract**: The emergence of 5G and edge computing hardware has brought about a significant shift in artificial intelligence, with edge AI becoming a crucial technology for enabling intelligent applications. With the growing amount of data generated and stored on edge devices, deploying AI models for local processing and inference has become increasingly necessary. However, deploying state-of-the-art AI models on resource-constrained edge devices faces significant challenges that must be addressed. This paper presents an optimization triad for efficient and reliable edge AI deployment, including data, model, and system optimization. First, we discuss optimizing data through data cleaning, compression, and augmentation to make it more suitable for edge deployment. Second, we explore model design and compression methods at the model level, such as pruning, quantization, and knowledge distillation. Finally, we introduce system optimization techniques like framework support and hardware acceleration to accelerate edge AI workflows. Based on an in-depth analysis of various application scenarios and deployment challenges of edge AI, this paper proposes an optimization paradigm based on the data-model-system triad to enable a whole set of solutions to effectively transfer ML models, which are initially trained in the cloud, to various edge devices for supporting multiple scenarios. 

**Abstract (ZH)**: 5G和边缘计算硬件的出现为人工智能带来了重大转变，边缘人工智能（Edge AI）成为了实现智能应用的关键技术。随着生成和存储在边缘设备上的数据量不断增加，部署人工智能模型进行本地处理和推理变得越来越必要。然而，将最先进的AI模型部署到资源受限的边缘设备上面临着重大挑战，必须加以解决。本文提出了一个高效可靠的边缘人工智能部署优化三元组，包括数据、模型和系统优化三个方面。首先，我们讨论了通过数据清洗、压缩和增强来优化数据，使其更适用于边缘部署。其次，我们探讨了模型层面的模型设计和压缩方法，如剪枝、量化和知识蒸馏。最后，我们介绍了如框架支持和硬件加速等系统优化技术，以加速边缘人工智能的工作流程。基于对边缘人工智能各种应用场景及其部署挑战的深入分析，本文提出了基于数据-模型-系统三元组的优化范式，旨在有效转移在云中预先训练的机器学习模型，并支持多种边缘设备上的场景。 

---
# Bridge the Inference Gaps of Neural Processes via Expectation Maximization 

**Title (ZH)**: 通过最大期望算法弥补神经过程中的推理缺口 

**Authors**: Qi Wang, Marco Federici, Herke van Hoof  

**Link**: [PDF](https://arxiv.org/pdf/2501.03264)  

**Abstract**: The neural process (NP) is a family of computationally efficient models for learning distributions over functions. However, it suffers from under-fitting and shows suboptimal performance in practice. Researchers have primarily focused on incorporating diverse structural inductive biases, \textit{e.g.} attention or convolution, in modeling. The topic of inference suboptimality and an analysis of the NP from the optimization objective perspective has hardly been studied in earlier work. To fix this issue, we propose a surrogate objective of the target log-likelihood of the meta dataset within the expectation maximization framework. The resulting model, referred to as the Self-normalized Importance weighted Neural Process (SI-NP), can learn a more accurate functional prior and has an improvement guarantee concerning the target log-likelihood. Experimental results show the competitive performance of SI-NP over other NPs objectives and illustrate that structural inductive biases, such as attention modules, can also augment our method to achieve SOTA performance. Our code is available at \url{this https URL}. 

**Abstract (ZH)**: 神经过程（Neural Process，NP）是一类在函数分布学习上计算效率高的模型。然而，它存在过拟合不足的问题，并在实际应用中表现出次优性能。研究者们主要集中在通过引入多种结构诱导偏见（例如注意力机制或卷积），来改进模型的表现。然而，在早期的研究中，关于推断次优性的问题以及从优化目标角度对NP的分析几乎没有被探讨。为了解决这个问题，我们提出了一种在期望最大化框架下的目标对数似然的替代优化目标。由此产生的模型被称为自规范化重要性加权神经过程（Self-normalized Importance-weighted Neural Process，SI-NP），它能够学习更为准确的函数先验，并关于目标对数似然提供了改进保证。实验结果显示，SI-NP 在与其他NP目标的比较中表现出竞争性的性能，并展示了结构诱导偏见，例如注意力模块，也能增强了我们的方法以达到最优表现。我们的代码可在以下链接获取：\url{此网址}。 

---
# Navigation Variable-based Multi-objective Particle Swarm Optimization for UAV Path Planning with Kinematic Constraints 

**Title (ZH)**: 基于导航变量的多目标粒子群优化在Kinematic约束下的无人机路径规划 

**Authors**: Thi Thuy Ngan Duong, Duy-Nam Bui, Manh Duong Phung  

**Link**: [PDF](https://arxiv.org/pdf/2501.03261)  

**Abstract**: Path planning is essential for unmanned aerial vehicles (UAVs) as it determines the path that the UAV needs to follow to complete a task. This work addresses this problem by introducing a new algorithm called navigation variable-based multi-objective particle swarm optimization (NMOPSO). It first models path planning as an optimization problem via the definition of a set of objective functions that include optimality and safety requirements for UAV operation. The NMOPSO is then used to minimize those functions through Pareto optimal solutions. The algorithm features a new path representation based on navigation variables to include kinematic constraints and exploit the maneuverable characteristics of the UAV. It also includes an adaptive mutation mechanism to enhance the diversity of the swarm for better solutions. Comparisons with various algorithms have been carried out to benchmark the proposed approach. The results indicate that the NMOPSO performs better than not only other particle swarm optimization variants but also other state-of-the-art multi-objective and metaheuristic optimization algorithms. Experiments have also been conducted with real UAVs to confirm the validity of the approach for practical flights. The source code of the algorithm is available at this https URL. 

**Abstract (ZH)**: 路径规划对于无人驾驶航空器（UAV）至关重要，因为它决定了无人机需要遵循的路径以完成任务。本研究通过引入一种名为基于导航变量的多目标粒子群优化算法（NMOPSO）来解决这一问题。该算法首先通过定义一组包含无人机操作的最优性和安全性要求的目标函数，将其路径规划问题建模为优化问题。然后，使用NMOPSO通过帕累托最优解来最小化这些函数。该算法具备一种基于导航变量的新路径表示，以包含动力学约束并利用无人机的机动特性。此外，该算法还包括一个自适应变异机制，以增强种群的多样性，从而获得更好的解决方案。已经对多种算法进行了比较测试，以评估所提出方法的性能。实验结果表明，NMOPSO不仅优于其他粒子群优化变体，而且还优于其他最先进的多目标和元启发式优化算法。还对实际的无人机进行了实验，以确认该方法在实际飞行中的有效性。该算法的源代码可通过以下链接获取：这个https链接。 

---
# Toward Inclusive Educational AI: Auditing Frontier LLMs through a Multiplexity Lens 

**Title (ZH)**: 面向包容性教育人工智能：通过多重性视角审核前沿大型语言模型 

**Authors**: Abdullah Mushtaq, Muhammad Rafay Naeem, Muhammad Imran Taj, Ibrahim Ghaznavi, Junaid Qadir  

**Link**: [PDF](https://arxiv.org/pdf/2501.03259)  

**Abstract**: As large language models (LLMs) like GPT-4 and Llama 3 become integral to educational contexts, concerns are mounting over the cultural biases, power imbalances, and ethical limitations embedded within these technologies. Though generative AI tools aim to enhance learning experiences, they often reflect values rooted in Western, Educated, Industrialized, Rich, and Democratic (WEIRD) cultural paradigms, potentially sidelining diverse global perspectives. This paper proposes a framework to assess and mitigate cultural bias within LLMs through the lens of applied multiplexity. Multiplexity, inspired by Senturk et al. and rooted in Islamic and other wisdom traditions, emphasizes the coexistence of diverse cultural viewpoints, supporting a multi-layered epistemology that integrates both empirical sciences and normative values. Our analysis reveals that LLMs frequently exhibit cultural polarization, with biases appearing in both overt responses and subtle contextual cues. To address inherent biases and incorporate multiplexity in LLMs, we propose two strategies: \textit{Contextually-Implemented Multiplex LLMs}, which embed multiplex principles directly into the system prompt, influencing LLM outputs at a foundational level and independent of individual prompts, and \textit{Multi-Agent System (MAS)-Implemented Multiplex LLMs}, where multiple LLM agents, each representing distinct cultural viewpoints, collaboratively generate a balanced, synthesized response. Our findings demonstrate that as mitigation strategies evolve from contextual prompting to MAS-implementation, cultural inclusivity markedly improves, evidenced by a significant rise in the Perspectives Distribution Score (PDS) and a PDS Entropy increase from 3.25\% at baseline to 98\% with the MAS-Implemented Multiplex LLMs. Sentiment analysis further shows a shift towards positive sentiment across cultures,... 

**Abstract (ZH)**: 随着大型语言模型（LLMs）如GPT-4和Llama 3在教育场景中的广泛应用，人们越来越担心这些技术中嵌入的文化偏见、权力失衡和伦理限制。尽管生成式AI工具旨在增强学习体验，但它们往往反映了西方、受过教育、工业化、富裕和民主（WEIRD）文化范式中的价值观，可能忽视了多元全球视角。本论文提出了一种框架，通过应用多层性来评估和缓解LLMs中的文化偏见。多层性受到Senturk等人以及伊斯兰和其他智慧传统的影响，强调多元文化观点的共存，支持一种多层次的认识论，综合了实证科学和规范价值观。我们的分析表明，LLMs经常体现出文化极化现象，偏见在明示和潜隐的上下文中都存在。为了应对固有的偏见并使LLMs融入多层性，我们提出了两种策略：\textit{基于上下文的多层性LLMs（Contextually-Implemented Multiplex LLMs）}，将多层原则直接嵌入系统提示，从基础层面影响LLMs的输出，独立于个体提示；以及\textit{多智能体系统（MAS）实现的多层性LLMs（Multi-Agent System-Implemented Multiplex LLMs）}，其中多个LLMs代理，各自代表不同的文化视角，共同生成平衡的综合回应。我们的研究结果表明，随着缓解策略从上下文提示演进到MAS实现，文化包容性显著提高，这体现在观点分布分数（PDS）的大幅提升和PDS熵从基线的3.25%增加到MAS实现的多层性LLMs的98%。情感分析进一步显示，文化间的情感倾向呈现出积极转变，…… 

---
# Breaking Through the Spike: Spike Window Decoding for Accelerated and Precise Automatic Speech Recognition 

**Title (ZH)**: 突破尖峰限制：基于尖峰窗口解码的加速精准自动语音识别 

**Authors**: Wei Zhang, Tian-Hao Zhang, Chao Luo, Hui Zhou, Chao Yang, Xinyuan Qian, Xu-Cheng Yin  

**Link**: [PDF](https://arxiv.org/pdf/2501.03257)  

**Abstract**: Recently, end-to-end automatic speech recognition has become the mainstream approach in both industry and academia. To optimize system performance in specific scenarios, the Weighted Finite-State Transducer (WFST) is extensively used to integrate acoustic and language models, leveraging its capacity to implicitly fuse language models within static graphs, thereby ensuring robust recognition while also facilitating rapid error correction. However, WFST necessitates a frame-by-frame search of CTC posterior probabilities through autoregression, which significantly hampers inference speed. In this work, we thoroughly investigate the spike property of CTC outputs and further propose the conjecture that adjacent frames to non-blank spikes carry semantic information beneficial to the model. Building on this, we propose the Spike Window Decoding algorithm, which greatly improves the inference speed by making the number of frames decoded in WFST linearly related to the number of spiking frames in the CTC output, while guaranteeing the recognition performance. Our method achieves SOTA recognition accuracy with significantly accelerates decoding speed, proven across both AISHELL-1 and large-scale In-House datasets, establishing a pioneering approach for integrating CTC output with WFST. 

**Abstract (ZH)**: 近年来，端到端自动语音识别已成为工业和学术界的主流方法。为了在特定场景中优化系统性能，通常会广泛使用加权有限状态转换器（WFST）来整合声学模型和语言模型，通过在其静态图中隐式融合语言模型的能力，确保识别的鲁棒性，并同时便于快速错误修正。然而，WFST需要通过自回归方式逐帧搜索CTC后验概率，这极大地降低了推理速度。为了解决这一问题，我们深入研究了CTC输出的尖峰特性，并进一步提出相邻非空白尖峰帧携带对模型有益的语义信息的猜想。基于这一发现，我们提出了尖峰窗解码算法（Spike Window Decoding），该算法通过使WFST中解码的帧数与CTC输出中的尖峰帧数成线性关系，大大提高了推理速度，同时保证了识别性能。我们的方法在AISHELL-1和大规模内部数据集上实现了最先进的识别准确率，并显著加速了解码速度，从而为CTC输出与WFST的集成提供了一种开创性的方法。 

---
# AI-ANNE: (A) (N)eural (N)et for (E)xploration: Transferring Deep Learning Models onto Microcontrollers and Embedded Systems 

**Title (ZH)**: AI-ANNE: (A) 基于神经网络的探索方法 (N): 将深度学习模型移植到微控制器和嵌入式系统中 （E） 

**Authors**: Dennis Klinkhammer  

**Link**: [PDF](https://arxiv.org/pdf/2501.03256)  

**Abstract**: This working paper explores the integration of neural networks onto resource-constrained embedded systems like a Raspberry Pi Pico / Raspberry Pi Pico 2. A TinyML aproach transfers neural networks directly on these microcontrollers, enabling real-time, low-latency, and energy-efficient inference while maintaining data privacy. Therefore, AI-ANNE: (A) (N)eural (N)et for (E)xploration will be presented, which facilitates the transfer of pre-trained models from high-performance platforms like TensorFlow and Keras onto microcontrollers, using a lightweight programming language like MicroPython. This approach demonstrates how neural network architectures, such as neurons, layers, density and activation functions can be implemented in MicroPython in order to deal with the computational limitations of embedded systems. Based on the Raspberry Pi Pico / Raspberry Pi Pico 2, two different neural networks on microcontrollers are presented for an example of data classification. As an further application example, such a microcontroller can be used for condition monitoring, where immediate corrective measures are triggered on the basis of sensor data. Overall, this working paper presents a very easy-to-implement way of using neural networks on energy-efficient devices such as microcontrollers. This makes AI-ANNE: (A) (N)eural (N)et for (E)xploration not only suited for practical use, but also as an educational tool with clear insights into how neural networks operate. 

**Abstract (ZH)**: 这篇工作论文探讨了如何将神经网络集成到资源限制的嵌入式系统中，如Raspberry Pi Pico / Raspberry Pi Pico 2。一种TinyML方法直接将神经网络转移到这些微控制器上，从而实现实时、低延迟和能源高效的选择并推断，同时保持数据隐私。因此，本文将介绍AI-ANNE：(A) (N)eural (N)et for (E)xploration，该方法利用像MicroPython这样的轻量级编程语言将预先训练的模型从高性能平台（如TensorFlow和Keras）转移至微控制器。这种方法展示了如何在MicroPython中实现神经网络结构，例如神经元、层、密度和激活函数，以应对嵌入式系统的计算限制。基于Raspberry Pi Pico / Raspberry Pi Pico 2，本文将分别介绍两种不同的神经网络模型在微控制器上的实现，作为数据分类的示例。作为进一步的应用示例，微控制器可以用于状态监测，通过传感器数据立即触发纠正措施。总体而言，本文提供了一种非常易于实现的在能源高效设备如微控制器上使用神经网络的方法，使AI-ANNE：(A) (N)eural (N)et for (E)xploration不仅可以用于实际应用，还可以作为教育工具，让使用者深入了解神经网络的工作原理。 

---
# Machine Learning and Deep Learning Techniques used in Cybersecurity and Digital Forensics: a Review 

**Title (ZH)**: 机器学习与深度学习技术在网络安全和数字取证中的应用：一个综述 

**Authors**: Jaouhar Fattahi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03250)  

**Abstract**: In the paced realms of cybersecurity and digital forensics machine learning (ML) and deep learning (DL) have emerged as game changing technologies that introduce methods to identify stop and analyze cyber risks. This review presents an overview of the ML and DL approaches used in these fields showcasing their advantages drawbacks and possibilities. It covers a range of AI techniques used in spotting intrusions in systems and classifying malware to prevent cybersecurity attacks, detect anomalies and enhance resilience. This study concludes by highlighting areas where further research is needed and suggesting ways to create transparent and scalable ML and DL solutions that are suited to the evolving landscape of cybersecurity and digital forensics. 

**Abstract (ZH)**: 在网络安全和数字取证领域，机器学习（ML）和深度学习（DL）已成为变革性的技术，引入了识别和分析网络安全风险的方法。本综述概述了这些领域中使用的ML和DL方法，展示了它们的优势、局限性和潜在应用。它涵盖了用于检测系统入侵、分类恶意软件、预防网络安全攻击、检测异常和增强抵御能力的各种人工智能技术。本文结论部分还强调了需要进一步研究的领域，并建议了创造透明且可扩展的ML和DL解决方案的方法，以适应网络安全和数字取证领域的不断变化。 

---
# Neural networks consisting of DNA 

**Title (ZH)**: 由DNA构成的神经网络 

**Authors**: Michael te Vrugt  

**Link**: [PDF](https://arxiv.org/pdf/2501.03235)  

**Abstract**: Neural networks based on soft and biological matter constitute an interesting potential alternative to traditional implementations based on electric circuits. DNA is a particularly promising system in this context due its natural ability to store information. In recent years, researchers have started to construct neural networks that are based on DNA. In this chapter, I provide a very basic introduction to the concept of DNA neural networks, aiming at an audience that is not familiar with biochemistry. 

**Abstract (ZH)**: 基于软物质和生物材料的神经网络是传统基于电电路实现的一种有趣的可能性替代方案。DNA 作为一种在这种背景下特别有前景的系统，这归功于它天然的信息存储能力。近年来，研究人员已经开始构建基于 DNA 的神经网络。在本章中，我将提供一个非常基础的关于 DNA 神经网络概念的介绍，旨在面向对生物化学不熟悉的读者群体。 

---
# Accuracy Can Lie: On the Impact of Surrogate Model in Configuration Tuning 

**Title (ZH)**: 准确度并非全真：替代模型在配置调优中的影响研究 

**Authors**: Pengzhou Chen, Jingzhi Gong, Tao Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01876)  

**Abstract**: To ease the expensive measurements during configuration tuning, it is natural to build a surrogate model as the replacement of the system, and thereby the configuration performance can be cheaply evaluated. Yet, a stereotype therein is that the higher the model accuracy, the better the tuning result would be. This "accuracy is all" belief drives our research community to build more and more accurate models and criticize a tuner for the inaccuracy of the model used. However, this practice raises some previously unaddressed questions, e.g., Do those somewhat small accuracy improvements reported in existing work really matter much to the tuners? What role does model accuracy play in the impact of tuning quality? To answer those related questions, we conduct one of the largest-scale empirical studies to date-running over the period of 13 months 24*7-that covers 10 models, 17 tuners, and 29 systems from the existing works while under four different commonly used metrics, leading to 13,612 cases of investigation. Surprisingly, our key findings reveal that the accuracy can lie: there are a considerable number of cases where higher accuracy actually leads to no improvement in the tuning outcomes (up to 58% cases under certain setting), or even worse, it can degrade the tuning quality (up to 24% cases under certain setting). We also discover that the chosen models in most proposed tuners are sub-optimal and that the required % of accuracy change to significantly improve tuning quality varies according to the range of model accuracy. Deriving from the fitness landscape analysis, we provide in-depth discussions of the rationale behind, offering several lessons learned as well as insights for future opportunities. Most importantly, this work poses a clear message to the community: we should take one step back from the natural "accuracy is all" belief for model-based configuration tuning. 

**Abstract (ZH)**: 为简化配置调优过程中的昂贵测量，自然地可以建立一个代理模型来替代系统，从而低成本地评估配置性能。然而，一种普遍的看法是，模型的准确性越高，调优结果就越好。这种“准确性至上”的信念驱使我们的研究社区不断构建更准确的模型，并批评调优器使用的模型不够准确。然而，这种做法引发了一些以前未被注意到的问题，例如，现有的工作中报告的一些微小的准确性改进真的对调优器有很大影响吗？模型准确性在调优质量的影响中扮演什么角色？为了回答这些问题，我们进行了一项迄今为止规模最大的实证研究，为期13个月，每天24小时运行，涵盖了10种模型、17种调优器和29个系统，并采用了四种常用指标，共产生了13,612个研究案例。令人惊讶的是，我们的关键发现表明，准确性可能是欺骗性的：在某些设置下，有相当大的比例（高达58%）的情况中，更高的准确性实际上并没有改善调优结果，甚至在某些情况下降低了调优质量（高达24%的情况）。我们还发现，大多数提出的调优器选择的模型并不理想，提高调优质量所需的准确性变化比例取决于模型准确性的范围。通过适应性景观分析，我们深入探讨了背后的原因，提出了几条经验教训以及未来的机会洞见。最重要的是，这项工作向社区传递了一个明确的信息：在基于模型的配置调优中，我们应该暂时退一步，反思“准确性至上”这种自然的看法。 

---