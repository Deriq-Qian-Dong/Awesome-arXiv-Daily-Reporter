# Bootstrap Your Own Context Length 

**Title (ZH)**: 自我生成情境长度 

**Authors**: Liang Wang, Nan Yang, Xingxing Zhang, Xiaolong Huang, Furu Wei  

**Link**: [PDF](https://arxiv.org/pdf/2412.18860)  

**Abstract**: We introduce a bootstrapping approach to train long-context language models by exploiting their short-context capabilities only. Our method utilizes a simple agent workflow to synthesize diverse long-context instruction tuning data, thereby eliminating the necessity for manual data collection and annotation. The proposed data synthesis workflow requires only a short-context language model, a text retriever, and a document collection, all of which are readily accessible within the open-source ecosystem. Subsequently, language models are fine-tuned using the synthesized data to extend their context lengths. In this manner, we effectively transfer the short-context capabilities of language models to long-context scenarios through a bootstrapping process. We conduct experiments with the open-source Llama-3 family of models and demonstrate that our method can successfully extend the context length to up to 1M tokens, achieving superior performance across various benchmarks. 

**Abstract (ZH)**: 我们提出了一种通过利用短语境语言模型的能力来训练长语境语言模型的bootstrapping方法。该方法利用简单的代理工作流合成长语境指令调整数据，从而消除了手动数据收集和标注的需求。所提出的数据合成工作流仅需要一个短语境语言模型、一个文本检索器和一个文档集合，这些资源在开源生态系统中都很容易获得。随后，使用合成数据对语言模型进行微调，以扩展其上下文长度。通过这种方式，我们有效地通过bootstrapping过程将语言模型的短语境能力转移到长语境场景中。我们使用开源Llama-3模型家族进行了实验，并展示了我们的方法能够将上下文长度扩展至多达100万词，且在各种基准测试中表现出更优的性能。 

---
# xSRL: Safety-Aware Explainable Reinforcement Learning -- Safety as a Product of Explainability 

**Title (ZH)**: xSRL：具有解释性的安全强化学习——解释性即安全 

**Authors**: Risal Shahriar Shefin, Md Asifur Rahman, Thai Le, Sarra Alqahtani  

**Link**: [PDF](https://arxiv.org/pdf/2412.19311)  

**Abstract**: Reinforcement learning (RL) has shown great promise in simulated environments, such as games, where failures have minimal consequences. However, the deployment of RL agents in real-world systems such as autonomous vehicles, robotics, UAVs, and medical devices demands a higher level of safety and transparency, particularly when facing adversarial threats. Safe RL algorithms have been developed to address these concerns by optimizing both task performance and safety constraints. However, errors are inevitable, and when they occur, it is essential that the RL agents can also explain their actions to human operators. This makes trust in the safety mechanisms of RL systems crucial for effective deployment. Explainability plays a key role in building this trust by providing clear, actionable insights into the agent's decision-making process, ensuring that safety-critical decisions are well understood. While machine learning (ML) has seen significant advances in interpretability and visualization, explainability methods for RL remain limited. Current tools fail to address the dynamic, sequential nature of RL and its needs to balance task performance with safety constraints over time. The re-purposing of traditional ML methods, such as saliency maps, is inadequate for safety-critical RL applications where mistakes can result in severe consequences. To bridge this gap, we propose xSRL, a framework that integrates both local and global explanations to provide a comprehensive understanding of RL agents' behavior. xSRL also enables developers to identify policy vulnerabilities through adversarial attacks, offering tools to debug and patch agents without retraining. Our experiments and user studies demonstrate xSRL's effectiveness in increasing safety in RL systems, making them more reliable and trustworthy for real-world deployment. Code is available at this https URL. 

**Abstract (ZH)**: 强化学习（RL）在模拟环境中，如游戏中，已经显示出了巨大的潜力，而在这些环境中，失败的后果可以忽略不计。然而，当将RL代理部署到自动驾驶车辆、机器人、无人机和医疗设备等现实系统中时，对安全性和透明度的要求更高，特别是在面对敌对威胁时。为应对这些挑战，已经开发出了安全RL算法，通过优化任务性能和安全约束来提高系统安全性。尽管如此，错误是不可避免的，当它们发生时，至关重要的是，RL代理能够向人类操作员解释其行为。因此，对于RL系统安全机制的信任对于有效的部署至关重要。可解释性在建立这种信任方面发挥着关键作用，它通过提供清晰且可操作的洞察来解释代理的决策过程，确保关键的安全决策易于理解。虽然机器学习（ML）在可解释性和可视化方面取得了显著进展，但目前的RL解释工具仍然有限。现有的工具未能解决RL的动态性和序列性特点，也无法平衡任务性能与时间上的安全约束。传统的ML方法，例如显著性图，对于需要安全决策的RL应用来说远远不足，因为错误可能会导致严重后果。为解决这一问题，我们提出了一种名为xSRL的框架，该框架整合了局部和全局解释，以全面理解RL代理的行为。xSRL还使开发人员能够通过敌对攻击识别策略漏洞，并通过提供调试和修复代理的工具而无需重新训练来增强代理。通过实验和用户研究，我们展示了xSRL在提高RL系统安全性方面的有效性，使它们在实际部署中更加可靠和可信赖。相关代码可通过以下链接获取：[此链接处]。 

---
# Hierarchical Multi-agent Meta-Reinforcement Learning for Cross-channel Bidding 

**Title (ZH)**: 多代理层次元强化学习在跨渠道竞价中的应用 

**Authors**: Shenghong He, Chao Yu  

**Link**: [PDF](https://arxiv.org/pdf/2412.19064)  

**Abstract**: Real-time bidding (RTB) plays a pivotal role in online advertising ecosystems. Advertisers employ strategic bidding to optimize their advertising impact while adhering to various financial constraints, such as the return-on-investment (ROI) and cost-per-click (CPC). Primarily focusing on bidding with fixed budget constraints, traditional approaches cannot effectively manage the dynamic budget allocation problem where the goal is to achieve global optimization of bidding performance across multiple channels with a shared budget. In this paper, we propose a hierarchical multi-agent reinforcement learning framework for multi-channel bidding optimization. In this framework, the top-level strategy applies a CPC constrained diffusion model to dynamically allocate budgets among the channels according to their distinct features and complex interdependencies, while the bottom-level strategy adopts a state-action decoupled actor-critic method to address the problem of extrapolation errors in offline learning caused by out-of-distribution actions and a context-based meta-channel knowledge learning method to improve the state representation capability of the policy based on the shared knowledge among different channels. Comprehensive experiments conducted on a large scale real-world industrial dataset from the Meituan ad bidding platform demonstrate that our method achieves a state-of-the-art performance. 

**Abstract (ZH)**: 实时竞价（RTB）在在线广告生态系统中扮演着至关重要的角色。广告商借助战略性竞价来优化广告效果，同时遵守各种财政约束，如投资回报率（ROI）和每点击成本（CPC）。主要关注固定预算约束下的竞价，传统的竞价方法并不能有效解决预算动态分配问题，即如何在多个渠道共享预算的情况下实现竞标性能的全局最优化。本文提出了一种分层多agent强化学习框架，用于多渠道竞价优化。在该框架中，顶层策略采用CPC约束扩散模型，根据各个渠道的独特特征和复杂的相互依赖关系动态分配预算；底层策略采用状态-动作解耦的actor-critic方法，以解决离线学习中由于非分布动作导致的外推误差问题，并通过基于共享知识的元渠道知识学习方法来提升策略的状态表示能力。在美团广告竞价平台提供的大规模真实工业数据集上进行全面实验表明，本方法达到了最先进的性能。 

---
# TravelAgent: Generative Agents in the Built Environment 

**Title (ZH)**: TravelAgent: 建筑环境中的生成代理 

**Authors**: Ariel Noyman, Kai Hu, Kent Larson  

**Link**: [PDF](https://arxiv.org/pdf/2412.18985)  

**Abstract**: Understanding human behavior in built environments is critical for designing functional, user centered urban spaces. Traditional approaches, such as manual observations, surveys, and simplified simulations, often fail to capture the complexity and dynamics of real world behavior. To address these limitations, we introduce TravelAgent, a novel simulation platform that models pedestrian navigation and activity patterns across diverse indoor and outdoor environments under varying contextual and environmental conditions. TravelAgent leverages generative agents integrated into 3D virtual environments, enabling agents to process multimodal sensory inputs and exhibit human-like decision-making, behavior, and adaptation. Through experiments, including navigation, wayfinding, and free exploration, we analyze data from 100 simulations comprising 1898 agent steps across diverse spatial layouts and agent archetypes, achieving an overall task completion rate of 76%. Using spatial, linguistic, and sentiment analyses, we show how agents perceive, adapt to, or struggle with their surroundings and assigned tasks. Our findings highlight the potential of TravelAgent as a tool for urban design, spatial cognition research, and agent-based modeling. We discuss key challenges and opportunities in deploying generative agents for the evaluation and refinement of spatial designs, proposing TravelAgent as a new paradigm for simulating and understanding human experiences in built environments. 

**Abstract (ZH)**: 理解在建成环境中的人类行为对于设计功能性和以用户为中心的城市空间至关重要。传统方法，如手动观察、问卷调查和简化的模拟，往往无法捕捉到现实世界行为的复杂性和动力性。为解决这些局限性，我们引入了TravelAgent，这是一个新型的模拟平台，能够在不同情境和环境条件下模拟行人导航和活动模式，涵盖多样化的室内和室外环境。TravelAgent 利用集成到三维虚拟环境中的生成性代理，使代理能够处理多模态感知输入并通过类人的决策、行为和适应性进行表现。通过导航、路径识别和自由探索等实验，我们分析了100次模拟（包含1898个代理步）所产生的数据，涵盖了不同的空间布局和代理类型，最终完成任务的整体率为76%。利用空间分析、语言分析和情感分析，我们展示了代理如何感知、适应或应对环境及分配的任务。我们的研究结果表明，TravelAgent 作为城市设计、空间认知研究和基于代理的建模工具的潜力。我们讨论了在评估和优化空间设计时部署生成性代理的关键挑战和机遇，提出TravelAgent作为模拟和理解建成环境中人类体验的新范式。 

---
# EC-Diffuser: Multi-Object Manipulation via Entity-Centric Behavior Generation 

**Title (ZH)**: EC-Diffuser：基于实体中心的行为生成实现多对象操作 

**Authors**: Carl Qi, Dan Haramati, Tal Daniel, Aviv Tamar, Amy Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.18907)  

**Abstract**: Object manipulation is a common component of everyday tasks, but learning to manipulate objects from high-dimensional observations presents significant challenges. These challenges are heightened in multi-object environments due to the combinatorial complexity of the state space as well as of the desired behaviors. While recent approaches have utilized large-scale offline data to train models from pixel observations, achieving performance gains through scaling, these methods struggle with compositional generalization in unseen object configurations with constrained network and dataset sizes. To address these issues, we propose a novel behavioral cloning (BC) approach that leverages object-centric representations and an entity-centric Transformer with diffusion-based optimization, enabling efficient learning from offline image data. Our method first decomposes observations into an object-centric representation, which is then processed by our entity-centric Transformer that computes attention at the object level, simultaneously predicting object dynamics and the agent's actions. Combined with the ability of diffusion models to capture multi-modal behavior distributions, this results in substantial performance improvements in multi-object tasks and, more importantly, enables compositional generalization. We present BC agents capable of zero-shot generalization to tasks with novel compositions of objects and goals, including larger numbers of objects than seen during training. We provide video rollouts on our webpage: this https URL. 

**Abstract (ZH)**: 物体操作是日常任务中的常见组成部分，但从高维度观测中学习操作物体面临着显著挑战。在多物体环境中，这些挑战更为突出，因为状态空间和目标行为之间的组合复杂度增加。尽管最近的方法利用大规模离线数据从像素观测中训练模型，并通过规模扩大实现性能提升，但这些方法在受限的网络和数据集规模下，在未见物体配置中实现组合式泛化方面仍然存在困难。为了解决这些问题，我们提出了一种新颖的行为克隆（Behavioral Cloning, BC）方法，该方法利用了以物体为中心的表示和实体为中心的Transformer，结合基于扩散的优化，从而能够有效从离线图像数据中进行学习。我们的方法首先将观测分解为以物体为中心的表示，然后通过我们的实体为中心的Transformer处理这些表示，在物体级别计算注意力的同时预测物体动力学和代理的行动。结合扩散模型能够捕捉多模态行为分布的能力，这在多物体任务中实现了显著的性能提升，并且更为重要的是，能够实现组合式泛化。我们展示了能够在新组成的物体和目标下实现零样本泛化的效果，包括在训练中未见过更多的物体数量。我们已经在网页上提供了视频滚动播放：this https URL。 

---
# GAI: Generative Agents for Innovation 

**Title (ZH)**: GAI：生成式代理促进创新 

**Authors**: Masahiro Sato  

**Link**: [PDF](https://arxiv.org/pdf/2412.18899)  

**Abstract**: This study examines whether collective reasoning among generative agents can facilitate novel and coherent thinking that leads to innovation. To achieve this, it proposes GAI, a new LLM-empowered framework designed for reflection and interaction among multiple generative agents to replicate the process of innovation. The core of the GAI framework lies in an architecture that dynamically processes the internal states of agents and a dialogue scheme specifically tailored to facilitate analogy-driven innovation. The framework's functionality is evaluated using Dyson's invention of the bladeless fan as a case study, assessing the extent to which the core ideas of the innovation can be replicated through a set of fictional technical documents. The experimental results demonstrate that models with internal states significantly outperformed those without, achieving higher average scores and lower variance. Notably, the model with five heterogeneous agents equipped with internal states successfully replicated the key ideas underlying the Dyson's invention. This indicates that the internal state enables agents to refine their ideas, resulting in the construction and sharing of more coherent and comprehensive concepts. 

**Abstract (ZH)**: 本研究探讨集体生成代理间的集体推理是否能促进新颖且连贯的思考，进而推动创新。为此，本文提出了GAI（Generative Agent Innovation）框架，这是一种以大型语言模型（LLM）为基础的新框架，旨在促进多个生成代理间的反思和交互，复制创新过程。GAI框架的核心在于一种动态处理代理内部状态的架构，以及一种专门为促进类比驱动的创新而精心设计的对话方案。框架的功能性通过采用戴森公司发明的无叶风扇作为案例研究进行评估，评估在一组虚构的技术文件中复制创新核心理念的程度。实验结果表明，具有内部状态的模型显著优于没有内部状态的模型，获得了更高的平均评分和更低的变异性。值得注意的是，配备有内部状态的五个异构代理成功复制了戴森发明的关键理念。这表明内部状态使代理能够细化和精炼其理念，从而在构建和分享更多连贯和全面的概念方面取得成效。 

---
# Agents on the Bench: Large Language Model Based Multi Agent Framework for Trustworthy Digital Justice 

**Title (ZH)**: 《审判席上的代理人：基于大型语言模型的多代理系统框架，以实现可信赖的数字正义》

此标题翻译遵循了学术规范，保持了原文的核心意思，并用中文学术界常用的表达方式进行了适当调整。 

**Authors**: Cong Jiang, Xiaolei Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.18697)  

**Abstract**: The justice system has increasingly employed AI techniques to enhance efficiency, yet limitations remain in improving the quality of decision-making, particularly regarding transparency and explainability needed to uphold public trust in legal AI. To address these challenges, we propose a large language model based multi-agent framework named AgentsBench, which aims to simultaneously improve both efficiency and quality in judicial decision-making. Our approach leverages multiple LLM-driven agents that simulate the collaborative deliberation and decision making process of a judicial bench. We conducted experiments on legal judgment prediction task, and the results show that our framework outperforms existing LLM based methods in terms of performance and decision quality. By incorporating these elements, our framework reflects real-world judicial processes more closely, enhancing accuracy, fairness, and society consideration. AgentsBench provides a more nuanced and realistic methods of trustworthy AI decision-making, with strong potential for application across various case types and legal scenarios. 

**Abstract (ZH)**: 司法系统正越来越多地采用人工智能技术以提高效率，然而在提高决策质量方面仍存在局限，尤其是在透明性和可解释性方面，这是维护公众对法律人工智能的信任所需的重要方面。为应对这些挑战，我们提出了一种基于大型语言模型的多代理框架，名为AgentsBench，旨在同时提高司法决策的效率和质量。我们的方法利用多个由大型语言模型驱动的代理，模拟司法庭的协作讨论和决策过程。我们进行了法律判决预测任务的实验，结果表明，与现有的基于大型语言模型的方法相比，我们的框架在性能和决策质量上表现更优。通过这些元素，我们的框架更接近于真实的司法流程，提高了准确性、公平性和社会考量。AgentsBench 提供了一种更为细致和现实的可信赖人工智能决策方法，适用于各种案件类型和法律情境，具有较大的应用潜力。 

---
# Scalable Hierarchical Reinforcement Learning for Hyper Scale Multi-Robot Task Planning 

**Title (ZH)**: 面向超大规模多机器人任务规划的可扩展分层强化学习方法 

**Authors**: Xuan Zhou, Xiang Shi, Lele Zhang, Chen Chen, Hongbo Li, Lin Ma, Fang Deng, Jie Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.19538)  

**Abstract**: To improve the efficiency of warehousing system and meet huge customer orders, we aim to solve the challenges of dimension disaster and dynamic properties in hyper scale multi-robot task planning (MRTP) for robotic mobile fulfillment system (RMFS). Existing research indicates that hierarchical reinforcement learning (HRL) is an effective method to reduce these challenges. Based on that, we construct an efficient multi-stage HRL-based multi-robot task planner for hyper scale MRTP in RMFS, and the planning process is represented with a special temporal graph topology. To ensure optimality, the planner is designed with a centralized architecture, but it also brings the challenges of scaling up and generalization that require policies to maintain performance for various unlearned scales and maps. To tackle these difficulties, we first construct a hierarchical temporal attention network (HTAN) to ensure basic ability of handling inputs with unfixed lengths, and then design multi-stage curricula for hierarchical policy learning to further improve the scaling up and generalization ability while avoiding catastrophic forgetting. Additionally, we notice that policies with hierarchical structure suffer from unfair credit assignment that is similar to that in multi-agent reinforcement learning, inspired of which, we propose a hierarchical reinforcement learning algorithm with counterfactual rollout baseline to improve learning performance. Experimental results demonstrate that our planner outperform other state-of-the-art methods on various MRTP instances in both simulated and real-world RMFS. Also, our planner can successfully scale up to hyper scale MRTP instances in RMFS with up to 200 robots and 1000 retrieval racks on unlearned maps while keeping superior performance over other methods. 

**Abstract (ZH)**: 为了提高仓储系统的效率并满足大量客户订单的需求，我们旨在解决大规模多机器人任务规划（MRTP）中高维尺寸灾难与动态属性的挑战。现有的研究表明，层次强化学习（HRL）是一种有效的方法来减轻这些挑战。基于此，我们构建了一个高效多层次HRL多机器人任务规划器，以应对RMFS中的大规模MRTP问题，并将规划过程表示为一种特殊的时序图拓扑结构。为了保证最优性，规划器采用了集中式架构，但这也带来了规模扩展和泛化的挑战，需要政策能够在各种未学习的规模和地图上保持性能。为了解决这些困难，我们首先构建了一个层次时间注意力网络（HTAN），以确保能够处理输入长度不定的情况；然后设计了多层次课程来进一步提高规模扩展和泛化能力，同时避免灾难性遗忘。此外，我们注意到具有层次结构的策略在贡献归因方面存在类似多智能体强化学习的问题，因此受此启发，我们提出了一种带有反事实展开基线的层次强化学习算法，以提高学习性能。实验结果表明，我们的规划器在模拟和实际仓储系统中的多种MRTP实例中，优于其他最先进的方法。此外，我们的规划器能够成功扩展到拥有200个机器人和1000个取货货架的大型MRTP实例，并保持优于其他方法的出色性能。 

---
# Mobile Robots through Task-Based Human Instructions using Incremental Curriculum Learning 

**Title (ZH)**: 基于任务的人类指令通过增量课程学习引导的移动机器人控制 

**Authors**: Muhammad A. Muttaqien, Ayanori Yorozu, Akihisa Ohya  

**Link**: [PDF](https://arxiv.org/pdf/2412.19159)  

**Abstract**: This paper explores the integration of incremental curriculum learning (ICL) with deep reinforcement learning (DRL) techniques to facilitate mobile robot navigation through task-based human instruction. By adopting a curriculum that mirrors the progressive complexity encountered in human learning, our approach systematically enhances robots' ability to interpret and execute complex instructions over time. We explore the principles of DRL and its synergy with ICL, demonstrating how this combination not only improves training efficiency but also equips mobile robots with the generalization capability required for navigating through dynamic indoor environments. Empirical results indicate that robots trained with our ICL-enhanced DRL framework outperform those trained without curriculum learning, highlighting the benefits of structured learning progressions in robotic training. 

**Abstract (ZH)**: 本文探讨了将增量课程学习（Incremental Curriculum Learning, ICL）与深度强化学习（Deep Reinforcement Learning, DRL）技术结合，以通过任务导向的人类指令促进移动机器人导航。通过采用一个反映人类学习中逐渐增加复杂性的课程，我们的方法系统地增强了机器人随着时间推移解析和执行复杂指令的能力。我们研究了DRL的基本原理及其与ICL的协同作用，证明了这种组合不仅提高了训练效率，还为机器人提供了在动态室内环境中导航所需的一般化能力。实验证明，使用我们的ICL增强DRL框架进行训练的机器人在导航性能上优于未使用课程学习训练的机器人，突显了在机器人训练中结构化学习进程的重要性。 

---
# HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs 

**Title (ZH)**: HuatuoGPT-o1：面向医学复杂推理的大型语言模型探究 

**Authors**: Junying Chen, Zhenyang Cai, Ke Ji, Xidong Wang, Wanlong Liu, Rongsheng Wang, Jianye Hou, Benyou Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.18925)  

**Abstract**: The breakthrough of OpenAI o1 highlights the potential of enhancing reasoning to improve LLM. Yet, most research in reasoning has focused on mathematical tasks, leaving domains like medicine underexplored. The medical domain, though distinct from mathematics, also demands robust reasoning to provide reliable answers, given the high standards of healthcare. However, verifying medical reasoning is challenging, unlike those in mathematics. To address this, we propose verifiable medical problems with a medical verifier to check the correctness of model outputs. This verifiable nature enables advancements in medical reasoning through a two-stage approach: (1) using the verifier to guide the search for a complex reasoning trajectory for fine-tuning LLMs, (2) applying reinforcement learning (RL) with verifier-based rewards to enhance complex reasoning further. Finally, we introduce HuatuoGPT-o1, a medical LLM capable of complex reasoning, which outperforms general and medical-specific baselines using only 40K verifiable problems. Experiments show complex reasoning improves medical problem-solving and benefits more from RL. We hope our approach inspires advancements in reasoning across medical and other specialized domains. 

**Abstract (ZH)**: OpenAI o1的突破凸显了增强推理能力以提高大语言模型性能的潜力。然而，大多数关于推理的研究主要集中在数学任务上，而医学领域等其他领域则未得到充分探索。尽管医学与数学领域不同，但医学同样需要强大的推理能力以提供可靠的答案，因为医疗服务的标准非常高。然而，医学推理的验证比数学领域的验证更具挑战性。为解决这一问题，我们提出了一种带有医学验证器的可验证医学问题，以检查模型输出的正确性。这种可验证性通过两阶段方法促进了医学推理的进步：（1）使用验证器指导复杂的推理轨迹搜索，以微调大语言模型；（2）利用基于验证器的奖励强化学习（RL）来进一步增强复杂的推理能力。最后，我们介绍了HuatuoGPT-o1，这是一种能够进行复杂推理的医学大语言模型，仅使用40,000个可验证问题便超越了一般和专门针对医学问题的基准模型。实验结果显示，复杂的推理能够提高医学问题的解决能力，并且更受益于强化学习。我们希望我们的方法能够激励跨医学和其他专门领域中的推理进步。 

---
# Diverse and Effective Red Teaming with Auto-generated Rewards and Multi-step Reinforcement Learning 

**Title (ZH)**: 使用自动生成奖励和多步强化学习的多样化和有效的红队演练 

**Authors**: Alex Beutel, Kai Xiao, Johannes Heidecke, Lilian Weng  

**Link**: [PDF](https://arxiv.org/pdf/2412.18693)  

**Abstract**: Automated red teaming can discover rare model failures and generate challenging examples that can be used for training or evaluation. However, a core challenge in automated red teaming is ensuring that the attacks are both diverse and effective. Prior methods typically succeed in optimizing either for diversity or for effectiveness, but rarely both. In this paper, we provide methods that enable automated red teaming to generate a large number of diverse and successful attacks.
Our approach decomposes the task into two steps: (1) automated methods for generating diverse attack goals and (2) generating effective attacks for those goals. While we provide multiple straightforward methods for generating diverse goals, our key contributions are to train an RL attacker that both follows those goals and generates diverse attacks for those goals. First, we demonstrate that it is easy to use a large language model (LLM) to generate diverse attacker goals with per-goal prompts and rewards, including rule-based rewards (RBRs) to grade whether the attacks are successful for the particular goal. Second, we demonstrate how training the attacker model with multi-step RL, where the model is rewarded for generating attacks that are different from past attempts further increases diversity while remaining effective. We use our approach to generate both prompt injection attacks and prompts that elicit unsafe responses. In both cases, we find that our approach is able to generate highly-effective and considerably more diverse attacks than past general red-teaming approaches. 

**Abstract (ZH)**: 自动化红队演练可以发现罕见的模型故障并生成具有挑战性的实例，这些实例可用于训练或评估。然而，自动化红队演练的核心挑战在于确保攻击既多样化又有效。以往的方法通常在优化多样性和有效性之间取得成功，但很少两者兼顾。在本文中，我们提供了一种方法，使自动化红队演练能够生成大量多样且成功的攻击。

我们的方法将任务分解为两个步骤：（1）生成多样化的攻击目标的自动化方法；（2）为这些目标生成有效的攻击。尽管我们提供了多种简单的方法来生成多样化的目标，但我们的关键贡献在于训练一个深度强化学习（RL）攻击者，该攻击者不仅遵循这些目标，还为每个目标生成多样化的攻击。首先，我们证明使用大型语言模型（LLMs）通过每个目标的提示和奖励（包括基于规则的奖励RBR，以评估攻击是否针对特定目标成功）来生成多样化的攻击者目标是很容易的。其次，我们展示通过使用多步强化学习训练攻击模型，其中模型因其生成的攻击与过去尝试不同而得到奖励，在保持有效性的同时还能增加多样性。我们使用我们的方法生成了注入提示攻击以及引发不安全响应的提示。在两种情况下，我们发现我们的方法生成的攻击不仅更为有效，且在多样性方面也明显优于以往的一般红队方法。 

---
# A Grounded Observer Framework for Establishing Guardrails for Foundation Models in Socially Sensitive Domains 

**Title (ZH)**: 面向社会敏感领域基础模型的守门人框架的接地观察者范式 

**Authors**: Rebecca Ramnauth, Dražen Brščić, Brian Scassellati  

**Link**: [PDF](https://arxiv.org/pdf/2412.18639)  

**Abstract**: As foundation models increasingly permeate sensitive domains such as healthcare, finance, and mental health, ensuring their behavior meets desired outcomes and social expectations becomes critical. Given the complexities of these high-dimensional models, traditional techniques for constraining agent behavior, which typically rely on low-dimensional, discrete state and action spaces, cannot be directly applied. Drawing inspiration from robotic action selection techniques, we propose the grounded observer framework for constraining foundation model behavior that offers both behavioral guarantees and real-time variability. This method leverages real-time assessment of low-level behavioral characteristics to dynamically adjust model actions and provide contextual feedback. To demonstrate this, we develop a system capable of sustaining contextually appropriate, casual conversations ("small talk"), which we then apply to a robot for novel, unscripted interactions with humans. Finally, we discuss potential applications of the framework for other social contexts and areas for further research. 

**Abstract (ZH)**: 随着基础模型越来越多地渗透到医疗保健、金融和心理健康等敏感领域，确保其行为符合预期结果和社会期望变得愈发重要。考虑到这些高维度模型的复杂性，传统用于限制代理行为的方法，通常依赖于低维度的离散状态和动作空间，已无法直接应用。借鉴机器人动作选择技术，我们提出了一个基于环境观察者的框架，以确保基础模型的行为不仅具有行为保证，还能提供实时的动态调整和情境反馈。该方法通过实时评估低层次的行为特征，动态调整模型的动作，并提供反馈。为了证明这一点，我们开发了一个系统，能够进行适量的、非正式对话（即“闲聊”），并将这一系统应用于机器人，使之能够与人类进行新颖的、未安排脚本的互动。最后，我们讨论了该框架在其他社会情境中的潜在应用，并指出了进一步研究的领域。 

---
# AgreeMate: Teaching LLMs to Haggle 

**Title (ZH)**: AgreeMate：教学超大规模语言模型进行讨价还价 

**Authors**: Ainesh Chatterjee, Samuel Miller, Nithin Parepally  

**Link**: [PDF](https://arxiv.org/pdf/2412.18690)  

**Abstract**: We introduce AgreeMate, a framework for training Large Language Models (LLMs) to perform strategic price negotiations through natural language. We apply recent advances to a negotiation setting where two agents (i.e. buyer or seller) use natural language to bargain on goods using coarse actions. Specifically, we present the performance of Large Language Models when used as agents within a decoupled (modular) bargaining architecture. We demonstrate that using prompt engineering, fine-tuning, and chain-of-thought prompting enhances model performance, as defined by novel metrics. We use attention probing to show model attention to semantic relationships between tokens during negotiations. 

**Abstract (ZH)**: 我们将介绍AgreeMate框架，该框架旨在通过自然语言训练大规模语言模型（LLMs）进行战略性价格谈判。我们应用了最近的进展，将这种谈判设置应用于两个代理（买家或卖家）使用自然语言通过粗略行动来进行商品交易的情境。具体而言，我们展示了在解耦（模块化）的协商架构中，当大规模语言模型作为代理使用时的性能表现。我们证明了通过提示工程、微调和链式思考提示可以提升模型性能，而这种提升利用了新的性能指标进行定义。我们采用注意力探针来展示模型在谈判过程中对词汇间语义关系的注意力。 

---