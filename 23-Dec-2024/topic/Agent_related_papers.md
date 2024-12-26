# Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration 

**Title (ZH)**: 协作 Gym：一个促进和评估人-代理协作的框架 

**Authors**: Yijia Shao, Vinay Samuel, Yucheng Jiang, John Yang, Diyi Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15701)  

**Abstract**: Recent advancements in language models (LMs) have sparked growing interest in developing LM agents. While fully autonomous agents could excel in many scenarios, numerous use cases inherently require them to collaborate with humans due to humans' latent preferences, domain expertise, or need for control. To facilitate the study of human-agent collaboration, we present Collaborative Gym (Co-Gym), a general framework enabling asynchronous, tripartite interaction among agents, humans, and task environments. We instantiate Co-Gym with three representative tasks in both simulated and real-world conditions, and propose an evaluation framework that assesses both the collaboration outcomes and processes. Our findings reveal that collaborative agents consistently outperform their fully autonomous counterparts in task performance within those delivered cases, achieving win rates of 86% in Travel Planning, 74% in Tabular Analysis, and 66% in Related Work when evaluated by real users. However, our study also highlights significant challenges in developing collaborative agents, requiring advancements in core aspects of intelligence -- communication capabilities, situational awareness, and balancing autonomy and human control. 

**Abstract (ZH)**: 近年来语言模型（LMs）的发展激发了对LM代理的研究兴趣。虽然完全自主的代理在许多场景中表现出色，但许多应用案例由于人类潜在的偏好、专业知识或控制需求，自然需要它们与人类协作。为了促进人机协作的研究，我们提出了协作健身房（Co-Gym），这是一种使代理、人类和任务环境能够在异步三元交互中协同工作的通用框架。我们通过模拟和真实世界条件下的三种代表性任务实例化了Co-Gym，并提出了一种评估框架，以评估合作结果和过程。我们的研究成果表明，在这些案例中，合作代理在任务性能上始终优于完全自主的代理，其中在旅行规划任务中达到了86%的胜率，在表格分析任务中达到了74%的胜率，在相关工作任务中达到了66%的胜率，这些评估结果来自于真实用户。然而，我们的研究也指出了开发协作代理面临的重大挑战，要求在核心智能方面取得进步——包括沟通能力、情境感知以及自主性和人类控制之间的平衡。 

---
# AIR: Unifying Individual and Cooperative Exploration in Collective Multi-Agent Reinforcement Learning 

**Title (ZH)**: AIR：整合个体与合作探索的集体多智能体强化学习 

**Authors**: Guangchong Zhou, Zeren Zhang, Guoliang Fan  

**Link**: [PDF](https://arxiv.org/pdf/2412.15700)  

**Abstract**: Exploration in cooperative multi-agent reinforcement learning (MARL) remains challenging for value-based agents due to the absence of an explicit policy. Existing approaches include individual exploration based on uncertainty towards the system and collective exploration through behavioral diversity among agents. However, the introduction of additional structures often leads to reduced training efficiency and infeasible integration of these methods. In this paper, we propose Adaptive exploration via Identity Recognition~(AIR), which consists of two adversarial components: a classifier that recognizes agent identities from their trajectories, and an action selector that adaptively adjusts the mode and degree of exploration. We theoretically prove that AIR can facilitate both individual and collective exploration during training, and experiments also demonstrate the efficiency and effectiveness of AIR across various tasks. 

**Abstract (ZH)**: 探索在协同多智能体强化学习（MARL）中的应用对于基于值的方法仍然具有挑战性，主要是由于缺乏明确的策略。现有方法包括基于系统不确定性进行个体探索以及通过智能体行为多样性进行集体探索。然而，引入额外结构往往会导致训练效率降低，并且难以将这些方法进行有效集成。在本文中，我们提出了一种基于身份识别的自适应探索（Adaptive Exploration via Identity Recognition，简称AIR）方法，该方法由两个对抗组件组成：用于从轨迹中识别智能体身份的分类器，以及能够自适应调整探索模式和程度的动作选择器。我们从理论上证明了AIR能够在训练过程中促进个体和集体探索，并通过实验验证了AIR在各种任务上的高效性和有效性。 

---
# Understanding Individual Agent Importance in Multi-Agent System via Counterfactual Reasoning 

**Title (ZH)**: 通过反事实推理理解多智能体系统中个体智能体的重要性 

**Authors**: Chen Jianming, Wang Yawen, Wang Junjie, Xie Xiaofei, Hu jun, Wang Qing, Xu Fanjiang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15619)  

**Abstract**: Explaining multi-agent systems (MAS) is urgent as these systems become increasingly prevalent in various applications. Previous work has proveided explanations for the actions or states of agents, yet falls short in understanding the black-boxed agent's importance within a MAS and the overall team strategy. To bridge this gap, we propose EMAI, a novel agent-level explanation approach that evaluates the individual agent's importance. Inspired by counterfactual reasoning, a larger change in reward caused by the randomized action of agent indicates its higher importance. We model it as a MARL problem to capture interactions across agents. Utilizing counterfactual reasoning, EMAI learns the masking agents to identify important agents. Specifically, we define the optimization function to minimize the reward difference before and after action randomization and introduce sparsity constraints to encourage the exploration of more action randomization of agents during training. The experimental results in seven multi-agent tasks demonstratee that EMAI achieves higher fidelity in explanations than baselines and provides more effective guidance in practical applications concerning understanding policies, launching attacks, and patching policies. 

**Abstract (ZH)**: 随着多代理系统（MAS）在各种应用中的逐渐普及，对其进行解释变得尤为紧迫。 previous研究虽然已经提供了对代理行为或状态的解释，但尚未充分理解黑盒代理在MAS中的重要性及其整体团队策略。为弥补这一差距，我们提出了EMAI，一种新颖的代理级别解释方法，用于评估个体代理的重要程度。受到反事实推理的启发，当代理的随机化动作导致奖励值更大变化时，表明其重要性更高。我们将其建模为一个多代理强化学习（MARL）问题，以捕捉代理间的交互。利用反事实推理，EMAI学习掩蔽代理以识别重要代理。具体地，我们定义优化函数以最小化随机化动作前后奖励值的差异，并引入稀疏性约束，鼓励在训练过程中更多地探索代理的随机化动作。在七个多代理任务中的实验结果表明，EMAI在解释的准确性上优于基线方法，并在理解策略、发起攻击和修补策略等实际应用方面提供了更有效的指导。 

---
# Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage 

**Title (ZH)**: 多模态代理调整：构建以VLearning Model为驱动的高效工具使用代理 

**Authors**: Zhi Gao, Bofei Zhang, Pengxiang Li, Xiaojian Ma, Tao Yuan, Yue Fan, Yuwei Wu, Yunde Jia, Song-Chun Zhu, Qing Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.15606)  

**Abstract**: The advancement of large language models (LLMs) prompts the development of multi-modal agents, which are used as a controller to call external tools, providing a feasible way to solve practical tasks. In this paper, we propose a multi-modal agent tuning method that automatically generates multi-modal tool-usage data and tunes a vision-language model (VLM) as the controller for powerful tool-usage reasoning. To preserve the data quality, we prompt the GPT-4o mini model to generate queries, files, and trajectories, followed by query-file and trajectory verifiers. Based on the data synthesis pipeline, we collect the MM-Traj dataset that contains 20K tasks with trajectories of tool usage. Then, we develop the T3-Agent via \underline{T}rajectory \underline{T}uning on VLMs for \underline{T}ool usage using MM-Traj. Evaluations on the GTA and GAIA benchmarks show that the T3-Agent consistently achieves improvements on two popular VLMs: MiniCPM-V-8.5B and {Qwen2-VL-7B}, which outperforms untrained VLMs by $20\%$, showing the effectiveness of the proposed data synthesis pipeline, leading to high-quality data for tool-usage capabilities. 

**Abstract (ZH)**: 大语言模型（LLMs）的发展推动了多模态代理（MMA）的应用，这些代理作为控制器调用外部工具，提供了解决实际任务的有效途径。本文提出了一种多模态代理调优方法，该方法可以自动生成多模态工具使用数据，并调优视图-语言模型（VLM）作为控制器，以增强工具使用推理能力。为了保证数据质量，我们使用GPT-4o mini模型生成查询、文件和轨迹，之后通过查询文件和轨迹验证器进行验证。基于数据合成管道，我们收集了包含20,000个任务和工具使用轨迹的MM-Traj数据集。然后，我们开发了T3-Agent，即通过轨迹调优VLM进行工具使用，利用MM-Traj数据集。在GTA和GAIA基准测试上的评估表明，T3-Agent能够持续提升两种流行的VLM：MiniCPM-V-8.5B和Qwen2-VL-7B的性能，未调优的VLM的性能提升了20%，证明了所提出的数据合成管道的有效性，从而为工具使用能力提供了高质量的数据。 

---
# Investigating Relational State Abstraction in Collaborative MARL 

**Title (ZH)**: 探究协作多智能体强化学习中的关系状态抽象 

**Authors**: Sharlin Utke, Jeremie Houssineau, Giovanni Montana  

**Link**: [PDF](https://arxiv.org/pdf/2412.15388)  

**Abstract**: This paper explores the impact of relational state abstraction on sample efficiency and performance in collaborative Multi-Agent Reinforcement Learning. The proposed abstraction is based on spatial relationships in environments where direct communication between agents is not allowed, leveraging the ubiquity of spatial reasoning in real-world multi-agent scenarios. We introduce MARC (Multi-Agent Relational Critic), a simple yet effective critic architecture incorporating spatial relational inductive biases by transforming the state into a spatial graph and processing it through a relational graph neural network. The performance of MARC is evaluated across six collaborative tasks, including a novel environment with heterogeneous agents. We conduct a comprehensive empirical analysis, comparing MARC against state-of-the-art MARL baselines, demonstrating improvements in both sample efficiency and asymptotic performance, as well as its potential for generalization. Our findings suggest that a minimal integration of spatial relational inductive biases as abstraction can yield substantial benefits without requiring complex designs or task-specific engineering. This work provides insights into the potential of relational state abstraction to address sample efficiency, a key challenge in MARL, offering a promising direction for developing more efficient algorithms in spatially complex environments. 

**Abstract (ZH)**: 本文探讨了关系状态抽象对协作多智能体强化学习中样本效率和性能的影响。所提出的关系抽象基于环境中智能体之间不允许直接通信的情况，利用了现实世界多智能体场景中空间推理的普适性。我们引入了MARC（多智能体关系评论家）架构，这是一种简单而有效的评论家架构，通过将状态转换为空间图并通过关系图神经网络处理来结合空间关系的归纳偏置。我们通过六个协作任务对MARC的性能进行了评估，包括一个新颖的包含异质智能体的环境。我们进行了全面的经验分析，将MARC与最新的多智能体强化学习（MARL）基线进行对比，展示了样本效率和渐近性能的改进，以及其潜在的泛化能力。研究结果表明，最小程度地整合空间关系的归纳偏置作为一种抽象方式，可以在不需复杂设计或任务特定工程的情况下带来显著益处。这项工作为理解关系状态抽象在解决MARL中的样本效率问题（这是MARL中的关键挑战）上的潜力提供了见解，并为在空间复杂环境中开发更高效的算法指明了有希望的方向。 

---
# Deep reinforcement learning with time-scale invariant memory 

**Title (ZH)**: 时间尺度不变记忆的深度强化学习 

**Authors**: Md Rysul Kabir, James Mochizuki-Freeman, Zoran Tiganj  

**Link**: [PDF](https://arxiv.org/pdf/2412.15292)  

**Abstract**: The ability to estimate temporal relationships is critical for both animals and artificial agents. Cognitive science and neuroscience provide remarkable insights into behavioral and neural aspects of temporal credit assignment. In particular, scale invariance of learning dynamics, observed in behavior and supported by neural data, is one of the key principles that governs animal perception: proportional rescaling of temporal relationships does not alter the overall learning efficiency. Here we integrate a computational neuroscience model of scale invariant memory into deep reinforcement learning (RL) agents. We first provide a theoretical analysis and then demonstrate through experiments that such agents can learn robustly across a wide range of temporal scales, unlike agents built with commonly used recurrent memory architectures such as LSTM. This result illustrates that incorporating computational principles from neuroscience and cognitive science into deep neural networks can enhance adaptability to complex temporal dynamics, mirroring some of the core properties of human learning. 

**Abstract (ZH)**: 估计时间关系的能力对动物和人工代理来说都是至关重要的。认知科学和神经科学为行为和神经层面的时间归因提供了深刻的理解。特别是，行为中观察到的学习动态的尺度不变性，得到了神经数据的支持，这是动物感知的关键原则之一：时间关系的成比例调整不会改变整体学习效率。本文将尺度不变记忆的计算神经科学模型整合到深度强化学习（RL）代理中。首先，我们进行理论分析，然后通过实验表明，这种代理能够在广泛的时序尺度上稳健地学习，这与使用常见循环记忆架构（如LSTM）构建的代理的表现不同。这一结果表明，在深度神经网络中融入来自神经科学和认知科学的计算原理可以增强对复杂时序动态的适应性，类似于人类学习的一些核心特性。 

---
# Towards Interpretable Radiology Report Generation via Concept Bottlenecks using a Multi-Agentic RAG 

**Title (ZH)**: 通过多智能体 Retrieval-Augmented Generation (RAG) 中的概念瓶颈实现可解释的放射学报告生成 

**Authors**: Hasan Md Tusfiqur Alam, Devansh Srivastav, Md Abdul Kadir, Daniel Sonntag  

**Link**: [PDF](https://arxiv.org/pdf/2412.16086)  

**Abstract**: Deep learning has advanced medical image classification, but interpretability challenges hinder its clinical adoption. This study enhances interpretability in Chest X-ray (CXR) classification by using concept bottleneck models (CBMs) and a multi-agent Retrieval-Augmented Generation (RAG) system for report generation. By modeling relationships between visual features and clinical concepts, we create interpretable concept vectors that guide a multi-agent RAG system to generate radiology reports, enhancing clinical relevance, explainability, and transparency. Evaluation of the generated reports using an LLM-as-a-judge confirmed the interpretability and clinical utility of our model's outputs. On the COVID-QU dataset, our model achieved 81% classification accuracy and demonstrated robust report generation performance, with five key metrics ranging between 84% and 90%. This interpretable multi-agent framework bridges the gap between high-performance AI and the explainability required for reliable AI-driven CXR analysis in clinical settings. 

**Abstract (ZH)**: 深度学习技术的进步促进了医学图像分类，但其可解释性不足限制了其临床应用。本研究通过使用概念瓶颈模型（CBMs）和多智能体检索增强生成（RAG）系统，增强了胸部X光（CXR）分类的可解释性。通过建模视觉特征与临床概念之间的关系，我们创建了可解释的概念向量，这些向量指导多智能体RAG系统生成放射学报告，从而增强了临床相关性、可解释性和透明度。利用语言模型作为评委进行生成报告的评估，证实了我们模型输出的可解释性和临床实用性。在COVID-QU数据集中，我们的模型实现了81%的分类准确率，并展示了稳健的报告生成性能，五个关键指标的范围在84%到90%之间。这种可解释的多智能体框架填补了高性能AI与临床环境中可靠AI驱动CXR分析所需可解释性之间的空白。 

---
# Tacit Learning with Adaptive Information Selection for Cooperative Multi-Agent Reinforcement Learning 

**Title (ZH)**: 自适应信息选择的隐式学习在协同多agent强化学习中的应用 

**Authors**: Lunjun Liu, Weilai Jiang, Yaonan Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15639)  

**Abstract**: In multi-agent reinforcement learning (MARL), the centralized training with decentralized execution (CTDE) framework has gained widespread adoption due to its strong performance. However, the further development of CTDE faces two key challenges. First, agents struggle to autonomously assess the relevance of input information for cooperative tasks, impairing their decision-making abilities. Second, in communication-limited scenarios with partial observability, agents are unable to access global information, restricting their ability to collaborate effectively from a global perspective. To address these challenges, we introduce a novel cooperative MARL framework based on information selection and tacit learning. In this framework, agents gradually develop implicit coordination during training, enabling them to infer the cooperative behavior of others in a discrete space without communication, relying solely on local information. Moreover, we integrate gating and selection mechanisms, allowing agents to adaptively filter information based on environmental changes, thereby enhancing their decision-making capabilities. Experiments on popular MARL benchmarks show that our framework can be seamlessly integrated with state-of-the-art algorithms, leading to significant performance improvements. 

**Abstract (ZH)**: 在多智能体强化学习（MARL）中，集中训练与分散执行（CTDE）框架因其强大的性能而得到了广泛应用。然而，CTDE的进一步发展面临两个主要挑战。首先，智能体难以自主评估输入信息的相关性，影响其决策能力。其次，在通信受限和部分可观测的情景下，智能体无法获取全局信息，限制了它们从全局视角进行有效协作的能力。为了解决这些挑战，我们提出了一种基于信息选择和默会学习的新型合作MARL框架。在该框架中，智能体在训练过程中逐步发展出隐性的协调能力，能够在不进行通信的情况下，仅依靠局部信息推断出其他智能体的合作行为。此外，我们引入了门控和选择机制，使智能体能够根据环境变化自适应地筛选信息，从而提高其决策能力。通过对流行的MARL基准测试的实验表明，我们的框架可以无缝集成到最先进的算法中，从而显著提升性能。 

---
# VLM-RL: A Unified Vision Language Models and Reinforcement Learning Framework for Safe Autonomous Driving 

**Title (ZH)**: VLM-RL：统一的视觉语言模型与强化学习框架以实现安全自动驾驶 

**Authors**: Zilin Huang, Zihao Sheng, Yansong Qu, Junwei You, Sikai Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15544)  

**Abstract**: In recent years, reinforcement learning (RL)-based methods for learning driving policies have gained increasing attention in the autonomous driving community and have achieved remarkable progress in various driving scenarios. However, traditional RL approaches rely on manually engineered rewards, which require extensive human effort and often lack generalizability. To address these limitations, we propose \textbf{VLM-RL}, a unified framework that integrates pre-trained Vision-Language Models (VLMs) with RL to generate reward signals using image observation and natural language goals. The core of VLM-RL is the contrasting language goal (CLG)-as-reward paradigm, which uses positive and negative language goals to generate semantic rewards. We further introduce a hierarchical reward synthesis approach that combines CLG-based semantic rewards with vehicle state information, improving reward stability and offering a more comprehensive reward signal. Additionally, a batch-processing technique is employed to optimize computational efficiency during training. Extensive experiments in the CARLA simulator demonstrate that VLM-RL outperforms state-of-the-art baselines, achieving a 10.5\% reduction in collision rate, a 104.6\% increase in route completion rate, and robust generalization to unseen driving scenarios. Furthermore, VLM-RL can seamlessly integrate almost any standard RL algorithms, potentially revolutionizing the existing RL paradigm that relies on manual reward engineering and enabling continuous performance improvements. The demo video and code can be accessed at: this https URL. 

**Abstract (ZH)**: 近年来，基于强化学习（RL）的驾驶策略学习方法在自动驾驶领域获得了越来越多的关注，并在各种驾驶场景中取得了显著进展。然而，传统的RL方法依赖于手工设计的奖励函数，这需要大量的人力投入，并且往往缺乏泛化能力。为了解决这些局限性，我们提出了\textbf{VLM-RL}，一种综合了预训练的视觉语言模型（VLM）与强化学习的统一框架，通过图像观测和自然语言目标来生成奖励信号。VLM-RL的核心是对比语言目标（CLG）作为奖励的范式，使用正负语言目标来生成语义奖励。此外，我们还引入了一种分层奖励合成方法，将基于CLG的语义奖励与车辆状态信息结合，提高了奖励的稳定性，并提供了更全面的奖励信号。同时，我们采用批处理技术以优化训练过程中的计算效率。通过在CARLA模拟器中进行广泛实验，我们发现VLM-RL在最新基线方法中表现更优，实现了碰撞率降低10.5%，路线完成率提高104.6%，并且在未见过的驾驶场景中具备强大的泛化能力。此外，VLM-RL几乎可以无缝集成任何标准的RL算法，有潜力革命性地改变依赖于手工设计奖励的传统RL框架，并促进持续的性能改进。视频演示和代码可以在以下链接访问：this https URL。 

---
# Generalized Back-Stepping Experience Replay in Sparse-Reward Environments 

**Title (ZH)**: 广义回步经验回放应用于稀疏奖励环境 

**Authors**: Guwen Lyu, Masahiro Sato  

**Link**: [PDF](https://arxiv.org/pdf/2412.15525)  

**Abstract**: Back-stepping experience replay (BER) is a reinforcement learning technique that can accelerate learning efficiency in reversible environments. BER trains an agent with generated back-stepping transitions of collected experiences and normal forward transitions. However, the original algorithm is designed for a dense-reward environment that does not require complex exploration, limiting the BER technique to demonstrate its full potential. Herein, we propose an enhanced version of BER called Generalized BER (GBER), which extends the original algorithm to sparse-reward environments, particularly those with complex structures that require the agent to explore. GBER improves the performance of BER by introducing relabeling mechanism and applying diverse sampling strategies. We evaluate our modified version, which is based on a goal-conditioned deep deterministic policy gradient offline learning algorithm, across various maze navigation environments. The experimental results indicate that the GBER algorithm can significantly boost the performance and stability of the baseline algorithm in various sparse-reward environments, especially those with highly structural symmetricity. 

**Abstract (ZH)**: 自返经验重放（BER）是一种强化学习技术，可以在可逆环境中加速学习效率。BER通过使用生成的反向过渡和收集的经验的正向过渡来训练智能体。然而，原始算法设计用于奖励密集的环境，不需要复杂的探索，这限制了BER技术的潜力。为了解决这一问题，我们提出了一种增强版本的BER，称为广义自返经验重放（GBER）。GBER将原始算法扩展到稀疏奖励环境，特别是那些复杂结构需要智能体进行探索的环境。GBER通过引入重新标签机制并应用多样化的采样策略来提高BER的性能。我们基于目标条件的深度确定性策略梯度的离线学习算法对修改后的GBER进行了评估，并在多种迷宫导航环境中进行了测试。实验结果表明，GBER算法在各种稀疏奖励环境中可以显著提升基线算法的性能和稳定性，特别是在高度结构对称性环境中表现尤为明显。 

---
# AI-Enhanced Sensemaking: Exploring the Design of a Generative AI-Based Assistant to Support Genetic Professionals 

**Title (ZH)**: AI增强的情报分析：探索基于生成式人工智能助手的设计以支持基因专业人士 

**Authors**: Angela Mastrianni, Hope Twede, Aleksandra Sarcevic, Jeremiah Wander, Christina Austin-Tse, Scott Saponas, Heidi Rehm, Ashley Mae Conard, Amanda K. Hall  

**Link**: [PDF](https://arxiv.org/pdf/2412.15444)  

**Abstract**: Generative AI has the potential to transform knowledge work, but further research is needed to understand how knowledge workers envision using and interacting with generative AI. We investigate the development of generative AI tools to support domain experts in knowledge work, examining task delegation and the design of human-AI interactions. Our research focused on designing a generative AI assistant to aid genetic professionals in analyzing whole genome sequences (WGS) and other clinical data for rare disease diagnosis. Through interviews with 17 genetics professionals, we identified current challenges in WGS analysis. We then conducted co-design sessions with six genetics professionals to determine tasks that could be supported by an AI assistant and considerations for designing interactions with the AI assistant. From our findings, we identified sensemaking as both a current challenge in WGS analysis and a process that could be supported by AI. We contribute an understanding of how domain experts envision interacting with generative AI in their knowledge work, a detailed empirical study of WGS analysis, and three design considerations for using generative AI to support domain experts in sensemaking during knowledge work.
CCS CONCEPTS: Human-centered computing, Human-computer interaction, Empirical studies in HCI
Additional Keywords and Phrases: whole genome sequencing, generative AI, large language models, knowledge work, sensemaking, co-design, rare disease
Contact Author: Angela Mastrianni (This work was done during the author's internship at Microsoft Research)
Ashley Mae Conard and Amanda K. Hall contributed equally 

**Abstract (ZH)**: 生成式AI有潜力重塑知识工作，但尚需进一步研究，以了解知识工作者如何设想使用和与生成式AI互动。我们探讨了生成式AI工具在支持领域专家进行知识工作方面的发展，关注任务委托和人机交互设计。我们的研究重点在于设计一个生成式AI助手，以帮助遗传专业人员分析全基因组序列（WGS）和其他临床数据，用于罕见病诊断。通过与17名遗传专业人士的访谈，我们确定了当前WGS分析中的难题。随后，我们与六名遗传专业人士进行了共同设计研讨会，以确定可以由AI助手支持的任务以及与AI助手进行交互时需要考虑的因素。根据我们的发现，我们确定了意义建构既是当前WGS分析中的一个难题，也是 khả năng由AI支持的过程。我们的贡献包括对领域专家如何在其知识工作中与生成式AI互动的见解、对WGS分析的详细实证研究，以及三条使用生成式AI支持领域专家在知识工作中进行意义建构的设计建议。

CCS概念：以人为中心的计算，人机交互，人机交互中的实证研究

附加关键词和短语：全基因组测序，生成式AI，大型语言模型，知识工作，意义建构，共同设计，罕见病

联系作者：安吉拉·马斯特里亚尼（本研究是在作者在微软研究实习期间完成的）
阿什莉·梅·康铎和阿曼达·K·霍尔贡献相当 

---
# Tree-of-Code: A Tree-Structured Exploring Framework for End-to-End Code Generation and Execution in Complex Task Handling 

**Title (ZH)**: 代码树：一种用于复杂任务处理中端到端代码生成与执行的树状探索框架 

**Authors**: Ziyi Ni, Yifan Li, Ning Yang, Dou Shen, Pin Lv, Daxiang Dong  

**Link**: [PDF](https://arxiv.org/pdf/2412.15305)  

**Abstract**: Solving complex reasoning tasks is a key real-world application of agents. Thanks to the pretraining of Large Language Models (LLMs) on code data, recent approaches like CodeAct successfully use code as LLM agents' action, achieving good results. However, CodeAct greedily generates the next action's code block by relying on fragmented thoughts, resulting in inconsistency and instability. Moreover, CodeAct lacks action-related ground-truth (GT), making its supervision signals and termination conditions questionable in multi-turn interactions. To address these issues, we first introduce a simple yet effective end-to-end code generation paradigm, CodeProgram, which leverages code's systematic logic to align with global reasoning and enable cohesive problem-solving. Then, we propose Tree-of-Code (ToC), which self-grows CodeProgram nodes based on the executable nature of the code and enables self-supervision in a GT-free scenario. Experimental results on two datasets using ten popular zero-shot LLMs show ToC remarkably boosts accuracy by nearly 20% over CodeAct with less than 1/4 turns. Several LLMs even perform better on one-turn CodeProgram than on multi-turn CodeAct. To further investigate the trade-off between efficacy and efficiency, we test different ToC tree sizes and exploration mechanisms. We also highlight the potential of ToC's end-to-end data generation for supervised and reinforced fine-tuning. 

**Abstract (ZH)**: 解决复杂推理任务是智能体在现实世界中的关键应用之一。得益于大型语言模型（LLMs）在代码数据上的预训练，近年来像CodeAct这样的方法成功地将代码作为LLM智能体的动作，取得了良好的效果。然而，CodeAct依赖于片段化的想法来贪婪地生成下一个动作的代码块，这导致了不一致性和不稳定性的出现。此外，CodeAct缺乏与动作相关的真实标注（Ground Truth, GT），使得其在多轮交互中的监督信号和终止条件存在疑问。为了解决这些问题，我们首先引入了一种简单而有效的端到端代码生成范式——CodeProgram，该范式利用代码的系统逻辑来与全局推理对齐，从而实现连贯的问题解决。然后，我们提出了基于可执行性的CodeProgram节点自我增长方法——Tree-of-Code（ToC），并在无需真实标注的场景中实现自我监督。在两个数据集上使用十种流行的零样本LLM进行的实验结果显示，ToC在不到四分之一的轮次中比CodeAct提高了近20%的准确性。甚至有几种LLM在单轮次CodeProgram上的表现优于多轮次CodeAct。为了进一步探索效能与效率之间的权衡，我们测试了不同大小的ToC树以及探索机制。我们还强调了ToC端到端数据生成在监督训练和强化调优方面的潜在价值。 

---
# Memory-Augmented Agent Training for Business Document Understanding 

**Title (ZH)**: 基于记忆增强代理训练的商业文档理解 

**Authors**: Jiale Liu, Yifan Zeng, Malte Højmark-Bertelsen, Marie Normann Gadeberg, Huazheng Wang, Qingyun Wu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15274)  

**Abstract**: Traditional enterprises face significant challenges in processing business documents, where tasks like extracting transport references from invoices remain largely manual despite their crucial role in logistics operations. While Large Language Models offer potential automation, their direct application to specialized business domains often yields unsatisfactory results. We introduce Matrix (Memory-Augmented agent Training through Reasoning and Iterative eXploration), a novel paradigm that enables LLM agents to progressively build domain expertise through experience-driven memory refinement and iterative learning. To validate this approach, we collaborate with one of the world's largest logistics companies to create a dataset of Universal Business Language format invoice documents, focusing on the task of transport reference extraction. Experiments demonstrate that Matrix outperforms prompting a single LLM by 30.3%, vanilla LLM agent by 35.2%. We further analyze the metrics of the optimized systems and observe that the agent system requires less API calls, fewer costs and can analyze longer documents on average. Our methods establish a new approach to transform general-purpose LLMs into specialized business tools through systematic memory enhancement in document processing tasks. 

**Abstract (ZH)**: 传统企业在处理商务文档时面临着显著的挑战，尽管发票中提取运输参考编号等任务在物流运营中至关重要，但这些任务仍然主要依赖人工完成。尽管大型语言模型具备潜在的自动化能力，但直接应用于专门的商业领域时，往往效果不尽如人意。我们提出了一种名为Matrix（记忆增强代理训练通过推理与迭代探索）的新型范式，该范式通过基于经验的记忆精炼和迭代学习，使大型语言模型代理能够逐步构建特定领域的专业知识。为了验证这一方法，我们与世界上最大的物流公司之一合作，创建了一个通用商务语言格式的发票文档数据集，专注于运输参考编号的提取任务。实验结果显示，Matrix在性能上比仅通过提示单个大型语言模型高出30.3%，比原始的大型语言模型代理高出35.2%。我们进一步分析了优化系统的指标，并发现代理系统所需的API调用次数较少、成本更低，并且能够平均分析更长的文档。我们的方法为通过系统性的文档处理任务中增强记忆，将通用型大型语言模型转变为专门的商业工具建立了新的途径。 

---
# On the Structural Memory of LLM Agents 

**Title (ZH)**: 大型语言模型代理的结构性记忆研究 

**Authors**: Ruihong Zeng, Jinyuan Fang, Siwei Liu, Zaiqiao Meng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15266)  

**Abstract**: Memory plays a pivotal role in enabling large language model~(LLM)-based agents to engage in complex and long-term interactions, such as question answering (QA) and dialogue systems. While various memory modules have been proposed for these tasks, the impact of different memory structures across tasks remains insufficiently explored. This paper investigates how memory structures and memory retrieval methods affect the performance of LLM-based agents. Specifically, we evaluate four types of memory structures, including chunks, knowledge triples, atomic facts, and summaries, along with mixed memory that combines these components. In addition, we evaluate three widely used memory retrieval methods: single-step retrieval, reranking, and iterative retrieval. Extensive experiments conducted across four tasks and six datasets yield the following key insights: (1) Different memory structures offer distinct advantages, enabling them to be tailored to specific tasks; (2) Mixed memory structures demonstrate remarkable resilience in noisy environments; (3) Iterative retrieval consistently outperforms other methods across various scenarios. Our investigation aims to inspire further research into the design of memory systems for LLM-based agents. 

**Abstract (ZH)**: 记忆在使基于大型语言模型（LLM）的代理能够进行复杂和长期的交互（如问题回答和对话系统）中发挥着关键作用。虽然为这些任务提出的各种记忆模块已经取得了显著进展，但不同记忆结构在不同任务中的影响仍然没有得到充分探索。本文探讨了记忆结构和记忆检索方法如何影响LLM代理的性能。具体来说，我们评估了四种类型的记忆结构，包括片段、知识三元组、原子事实和摘要，以及它们的混合记忆结构。此外，我们还评估了三种广泛使用的记忆检索方法：单步检索、再排序和迭代检索。通过对四个任务和六个数据集进行广泛实验，我们得出了以下关键见解：（1）不同的记忆结构提供了各自的优势，使其能够适应特定任务；（2）混合记忆结构在嘈杂环境中表现出色；（3）迭代检索方法在各种场景中始终优于其他方法。我们的研究旨在激发进一步探索用于LLM代理的记忆系统设计的研究。 

---
# AgentPS: Agentic Process Supervision for Multi-modal Content Quality Assurance through Multi-round QA 

**Title (ZH)**: AgentPS：代理过程监督在多模态内容质量保障中的多轮问答方法 

**Authors**: Gorden Liu, Yu Sun, Ruixiao Sun, Xin Dong, Hongyu Xiong  

**Link**: [PDF](https://arxiv.org/pdf/2412.15251)  

**Abstract**: The advanced processing and reasoning capabilities of multimodal large language models (MLLMs) have driven substantial progress in vision-language (VL) understanding tasks. However, while effective for tasks governed by straightforward logic, MLLMs often encounter challenges when reasoning over complex, interdependent logic structures. To address this limitation, we introduce \textit{AgentPS}, a novel framework that integrates Agentic Process Supervision into MLLMs via multi-round question answering during fine-tuning. \textit{AgentPS} demonstrates significant performance improvements over baseline MLLMs on proprietary TikTok datasets, due to its integration of process supervision and structured sequential reasoning. Furthermore, we show that replacing human-annotated labels with LLM-generated labels retains much of the performance gain, highlighting the framework's practical scalability in industrial applications. These results position \textit{AgentPS} as a highly effective and efficient architecture for multimodal classification tasks. Its adaptability and scalability, especially when enhanced by automated annotation generation, make it a powerful tool for handling large-scale, real-world challenges. 

**Abstract (ZH)**: 多模态大语言模型（MLLMs）的高级处理和推理能力推动了视觉语言（VL）理解任务的显著进展。然而，这类模型在处理复杂互动的逻辑结构时往往遇到挑战。为此，我们提出了一种名为AgentPS的新框架，通过微调期间多轮问答集成代理过程监督。AgentPS在专用的TikTok数据集上展示了显著的性能提升，这得益于其结合了过程监督和结构化顺序推理。进一步的研究表明，用大语言模型生成的标签替代人工标注的标签仍能保持大部分的性能提升，突显了该框架在工业应用层面的实用可扩展性。这些结果将AgentPS定位为一种在多模态分类任务中高效且有效的架构。其适应性与可扩展性，特别是在增强自动化标注生成时，使其成为应对大规模真实世界挑战的强大工具。 

---
# Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an "AI Therapist" 

**Title (ZH)**: 基于脚本的对话策略规划：为大规模语言模型驱动的对话代理设计“AI治疗师”基本架构 

**Authors**: Robert Wasenmüller, Kevin Hilbert, Christoph Benzmüller  

**Link**: [PDF](https://arxiv.org/pdf/2412.15242)  

**Abstract**: Large Language Model (LLM)-Powered Conversational Agents have the potential to provide users with scaled behavioral healthcare support, and potentially even deliver full-scale "AI therapy'" in the future. While such agents can already conduct fluent and proactive emotional support conversations, they inherently lack the ability to (a) consistently and reliably act by predefined rules to align their conversation with an overarching therapeutic concept and (b) make their decision paths inspectable for risk management and clinical evaluation -- both essential requirements for an "AI Therapist".
In this work, we introduce a novel paradigm for dialog policy planning in conversational agents enabling them to (a) act according to an expert-written "script" that outlines the therapeutic approach and (b) explicitly transition through a finite set of states over the course of the conversation. The script acts as a deterministic component, constraining the LLM's behavior in desirable ways and establishing a basic architecture for an AI Therapist.
We implement two variants of Script-Based Dialog Policy Planning using different prompting techniques and synthesize a total of 100 conversations with LLM-simulated patients. The results demonstrate the feasibility of this new technology and provide insights into the efficiency and effectiveness of different implementation variants. 

**Abstract (ZH)**: 大语言模型（LLM）驱动的对话代理有可能为用户提供扩展的行为健康支持，并且未来甚至可以提供全面的“AI疗法”。虽然这些代理已经能够进行流畅、积极的情感支持对话，但它们仍然存在无法（a）始终一致地按照预定义规则行动，以使对话与整体治疗概念保持一致，以及（b）使决策路径可检查，以便风险管理与临床评估的问题——这两者是“AI疗法”所必需的要求。

在本研究中，我们提出了一个用于对话策略规划的新范式，使对话代理能够（a）根据专家编写的“剧本”进行行动，该剧本概述了治疗方法，以及（b）在对话过程中明确地通过一组有限状态。该剧本作为确定性的组成部分，限制了LLM的行为，并奠定了“AI疗法”基本架构的基础。

我们使用不同的提示技术实现了两种基于剧本的对话策略规划变体，并使用LLM模拟的患者合成了共计100次对话。实验结果证明了该新方法的可行性，并提供了不同实施变体的效率与有效性见解。 

---
# CareBot: A Pioneering Full-Process Open-Source Medical Language Model 

**Title (ZH)**: CareBot：一种先锋性的全流程开源医疗语言模型 

**Authors**: Lulu Zhao, Weihao Zeng, Xiaofeng Shi, Hua Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2412.15236)  

**Abstract**: Recently, both closed-source LLMs and open-source communities have made significant strides, outperforming humans in various general domains. However, their performance in specific professional domains such as medicine, especially within the open-source community, remains suboptimal due to the complexity of medical knowledge. In this paper, we propose CareBot, a bilingual medical LLM, which leverages a comprehensive approach integrating continuous pre-training (CPT), supervised fine-tuning (SFT), and reinforcement learning with human feedback (RLHF). Our novel two-stage CPT method, comprising Stable CPT and Boost CPT, effectively bridges the gap between general and domain-specific data, facilitating a smooth transition from pre-training to fine-tuning and enhancing domain knowledge progressively. We also introduce DataRater, a model designed to assess data quality during CPT, ensuring that the training data is both accurate and relevant. For SFT, we develope a large and diverse bilingual dataset, along with ConFilter, a metric to enhance multi-turn dialogue quality, which is crucial to improving the model's ability to handle more complex dialogues. The combination of high-quality data sources and innovative techniques significantly improves CareBot's performance across a range of medical applications. Our rigorous evaluations on Chinese and English benchmarks confirm CareBot's effectiveness in medical consultation and education. These advancements not only address current limitations in medical LLMs but also set a new standard for developing effective and reliable open-source models in the medical domain. We will open-source the datasets and models later, contributing valuable resources to the research community. 

**Abstract (ZH)**: 近年来，闭源大语言模型和开源社区均取得了显著进展，在多个通用领域已超越人类。然而，它们在特定专业领域，尤其是医学领域中的表现仍欠佳，这主要是由于医学知识的复杂性。本文提出CareBot，一种双语医学大语言模型，它结合了连续预训练（CPT）、监督微调（SFT）和基于人类反馈的强化学习（RLHF）的全面方法。我们的创新双阶段CPT方法，包括稳定预训练（Stable CPT）和增强预训练（Boost CPT），有效地弥合了通用数据与领域特定数据之间的差距，促进从预训练到微调的平滑过渡，并逐级增强领域知识。此外，我们还引入了DataRater模型，用于评估CPT过程中的数据质量，确保训练数据既准确又相关。对于SFT，我们开发了一个大型且多样化的双语数据集，并引入了ConFilter指标，以提高多轮对话质量，这对于提高模型处理复杂对话的能力至关重要。高质量数据资源和创新技术的组合显著提升了CareBot在多种医学应用中的性能。我们在中文和英文基准上的严格评估证实了CareBot在医学咨询和教育方面的效果。这些进展不仅解决了当前医学大语言模型的限制，还为在医学领域开发有效且可靠开源模型树立了新的标准。我们将后续开源数据集和模型，为研究社区贡献宝贵的资源。 

---
# Learning-by-teaching with ChatGPT: The effect of teachable ChatGPT agent on programming education 

**Title (ZH)**: 使用ChatGPT进行教学：可教ChatGPT代理对学生编程教育效果的影响 

**Authors**: Angxuan Chen, Yuang Wei, Huixiao Le, Yan Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15226)  

**Abstract**: This study investigates the potential of using ChatGPT as a teachable agent to support students' learning by teaching process, specifically in programming education. While learning by teaching is an effective pedagogical strategy for promoting active learning, traditional teachable agents have limitations, particularly in facilitating natural language dialogue. Our research explored whether ChatGPT, with its ability to engage learners in natural conversations, can support this process. The findings reveal that interacting with ChatGPT improves students' knowledge gains and programming abilities, particularly in writing readable and logically sound code. However, it had limited impact on developing learners' error-correction skills, likely because ChatGPT tends to generate correct code, reducing opportunities for students to practice debugging. Additionally, students' self-regulated learning (SRL) abilities improved, suggesting that teaching ChatGPT fosters learners' higher self-efficacy and better implementation of SRL strategies. This study discussed the role of natural dialogue in fostering socialized learning by teaching, and explored ChatGPT's specific contributions in supporting students' SRL through the learning by teaching process. Overall, the study highlights ChatGPT's potential as a teachable agent, offering insights for future research on ChatGPT-supported education. 

**Abstract (ZH)**: 本研究探讨了将ChatGPT作为一种可教代理，通过教学过程支持学生学习的潜力，特别是在编程教育领域。虽然通过教学是一种促进主动学习的有效教学策略，但传统的可教代理存在局限性，特别是在促进自然语言对话方面。我们的研究探索了ChatGPT是否能够利用其进行自然对话的能力支持这一过程。研究结果表明，与ChatGPT互动可以提高学生的学习知识和编程能力，特别是在编写可读且逻辑正确的代码方面。然而，它在培养学生的错误校正技能方面的影响有限，这可能是因为ChatGPT倾向于生成正确的代码，减少了学生练习调试的机会。此外，学生自我调节学习（SRL）的能力得到了提高，表明教授ChatGPT能够增强学生的自我效能感，并更好地实施SRL策略。本研究讨论了自然对话在通过教学促进社会化学习中的作用，并探讨了ChatGPT在支持学生通过教学过程实现SRL方面的具体贡献。总体而言，本研究强调了ChatGPT作为可教代理的潜力，并为未来关于ChatGPT支持教育的研究提供了见解。 

---
# A Survey on Large Language Model-based Agents for Statistics and Data Science 

**Title (ZH)**: 基于大规模语言模型的代理在统计学和数据科学领域的研究综述 

**Authors**: Maojun Sun, Ruijian Han, Binyan Jiang, Houduo Qi, Defeng Sun, Yancheng Yuan, Jian Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14222)  

**Abstract**: In recent years, data science agents powered by Large Language Models (LLMs), known as "data agents," have shown significant potential to transform the traditional data analysis paradigm. This survey provides an overview of the evolution, capabilities, and applications of LLM-based data agents, highlighting their role in simplifying complex data tasks and lowering the entry barrier for users without related expertise. We explore current trends in the design of LLM-based frameworks, detailing essential features such as planning, reasoning, reflection, multi-agent collaboration, user interface, knowledge integration, and system design, which enable agents to address data-centric problems with minimal human intervention. Furthermore, we analyze several case studies to demonstrate the practical applications of various data agents in real-world scenarios. Finally, we identify key challenges and propose future research directions to advance the development of data agents into intelligent statistical analysis software. 

**Abstract (ZH)**: 近年来，由大规模语言模型（LLMs）驱动的数据科学代理，即“数据代理”，展示了显著的潜力，以变革传统的数据分析范式。本文综述了基于LLM的数据代理的演变、能力和应用，强调了它们在简化复杂数据任务以及降低无相关专业知识用户的学习门槛方面的作用。我们探讨了基于LLM的框架当前的设计趋势，并详细介绍了诸如规划、推理、反思、多代理协作、用户界面、知识集成和系统设计等关键特性，这些特性使代理能够最大限度地减少人力干预解决数据驱动的问题。此外，我们分析了几例案例研究，展示了各种数据代理在实际场景中的应用。最后，我们识别了关键挑战，并提出了未来的研究方向，以推动数据代理的发展，使其成为智能统计分析软件。 

---
# Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework 

**Title (ZH)**: 在多代理框架内的多目标方法减轻大型语言模型中的社会偏见 

**Authors**: Zhenjie Xu, Wenqing Chen, Yi Tang, Xuanying Li, Cheng Hu, Zhixuan Chu, Kui Ren, Zibin Zheng, Zhichao Lu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15504)  

**Abstract**: Natural language processing (NLP) has seen remarkable advancements with the development of large language models (LLMs). Despite these advancements, LLMs often produce socially biased outputs. Recent studies have mainly addressed this problem by prompting LLMs to behave ethically, but this approach results in unacceptable performance degradation. In this paper, we propose a multi-objective approach within a multi-agent framework (MOMA) to mitigate social bias in LLMs without significantly compromising their performance. The key idea of MOMA involves deploying multiple agents to perform causal interventions on bias-related contents of the input questions, breaking the shortcut connection between these contents and the corresponding answers. Unlike traditional debiasing techniques leading to performance degradation, MOMA substantially reduces bias while maintaining accuracy in downstream tasks. Our experiments conducted on two datasets and two models demonstrate that MOMA reduces bias scores by up to 87.7%, with only a marginal performance degradation of up to 6.8% in the BBQ dataset. Additionally, it significantly enhances the multi-objective metric icat in the StereoSet dataset by up to 58.1%. Code will be made available at this https URL. 

**Abstract (ZH)**: 自然语言处理（NLP）随着大型语言模型（LLMs）的发展取得了显著进展。尽管取得了这些进展，但LLMs常常产生社会偏见的输出。近期的研究主要通过促使LLMs表现得更加伦理来解决这一问题，但这种做法会导致性能显著下降。本文提出了一种多目标方法（MOMA），在多智能体框架内减轻LLMs中的社会偏见，而不显著牺牲其性能。MOMA的核心思想是部署多个智能体对输入问题中的偏见相关内容进行因果干预，从而打破这些内容与相应答案之间的捷径连接。与传统去偏方法导致的性能下降不同，MOMA在大幅减少偏见的同时，能够维持下游任务的准确性。我们在两个数据集和两个模型上进行的实验表明，MOMA在BBQ数据集上仅导致至多6.8%的轻微性能下降，同时将偏见分数降低至高达87.7%。此外，MOMA还在StereoSet数据集上显著提高了多目标指标icat，提高幅度高达58.1%。代码将在以下链接处开源：this https URL。 

---
# Advanced ingestion process powered by LLM parsing for RAG system 

**Title (ZH)**: 基于LLM解析的高级检索过程用于 Retrieval-Augmented Generation 系统 

**Authors**: Arnau Perez, Xavier Vizcaino  

**Link**: [PDF](https://arxiv.org/pdf/2412.15262)  

**Abstract**: Retrieval Augmented Generation (RAG) systems struggle with processing multimodal documents of varying structural complexity. This paper introduces a novel multi-strategy parsing approach using LLM-powered OCR to extract content from diverse document types, including presentations and high text density files both scanned or not. The methodology employs a node-based extraction technique that creates relationships between different information types and generates context-aware metadata. By implementing a Multimodal Assembler Agent and a flexible embedding strategy, the system enhances document comprehension and retrieval capabilities. Experimental evaluations across multiple knowledge bases demonstrate the approach's effectiveness, showing improvements in answer relevancy and information faithfulness. 

**Abstract (ZH)**: 基于检索增强生成（RAG）系统在处理结构复杂度各异的多模态文档方面存在挑战。本文介绍了一种新颖的多策略解析方法，利用大型语言模型（LLM）驱动的光学字符识别（OCR）技术，从不同类型的文件中提取内容，包括演示文稿和高文本密度文件（无论是扫描还是未扫描）。该方法采用基于节点的提取技术，创建不同类型信息之间的关系，并生成上下文感知的元数据。通过实施多模态组装代理和灵活的嵌入策略，系统增强了文档理解和检索能力。在多个知识库上的实验评估表明，该方法的有效性，在回答相关性和信息忠实性方面表现出改进。 

---