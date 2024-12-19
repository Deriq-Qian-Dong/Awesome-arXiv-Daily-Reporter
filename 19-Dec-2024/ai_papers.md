# Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics with Large Language Models 

**Title (ZH)**: 使用大型语言模型进行数据挖掘中多步洞察综合的高级推理与转换引擎 

**Authors**: Atin Sakkeer Hussain  

**Link**: [PDF](https://arxiv.org/pdf/2412.14146)  

**Abstract**: This paper presents the Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics (ARTEMIS-DA), a novel framework designed to augment Large Language Models (LLMs) for solving complex, multi-step data analytics tasks. ARTEMIS-DA integrates three core components: the Planner, which dissects complex user queries into structured, sequential instructions encompassing data preprocessing, transformation, predictive modeling, and visualization; the Coder, which dynamically generates and executes Python code to implement these instructions; and the Grapher, which interprets generated visualizations to derive actionable insights. By orchestrating the collaboration between these components, ARTEMIS-DA effectively manages sophisticated analytical workflows involving advanced reasoning, multi-step transformations, and synthesis across diverse data modalities. The framework achieves state-of-the-art (SOTA) performance on benchmarks such as WikiTableQuestions and TabFact, demonstrating its ability to tackle intricate analytical tasks with precision and adaptability. By combining the reasoning capabilities of LLMs with automated code generation and execution and visual analysis, ARTEMIS-DA offers a robust, scalable solution for multi-step insight synthesis, addressing a wide range of challenges in data analytics. 

**Abstract (ZH)**: 本文介绍了“高级推理与转换引擎用于多步骤数据洞察合成的数据分析（ARTEMIS-DA）”，这是一种新型框架，旨在增强大型语言模型（LLMs）以解决复杂的多步骤数据分析任务。ARTEMIS-DA 集成了三个核心组件：规划器，它将复杂的用户查询拆分为结构化、顺序的指令，涵盖数据预处理、转换、预测建模和可视化；编码器，它动态地生成并执行 Python 代码以实现这些指令；以及绘图器，它解释生成的可视化图形以推导出可操作的洞察。通过协调这些组件之间的合作，ARTEMIS-DA 有效地管理了涉及高级推理、多步骤转换和跨多种数据模态综合的复杂分析工作流程。该框架在 WikiTableQuestions 和 TabFact 等基准测试中实现了最先进的（SOTA）性能，展示了其在精确性和适应性方面解决复杂分析任务的能力。通过结合 LLM 的推理能力、自动代码生成和执行以及可视化分析，ARTEMIS-DA 提供了一种针对多步骤洞察合成的稳健且可扩展的解决方案，以应对数据分析中的广泛挑战。 

---
# LLMs can realize combinatorial creativity: generating creative ideas via LLMs for scientific research 

**Title (ZH)**: 大型语言模型能够实现组合式创造力：通过大型语言模型生成科研创意 

**Authors**: Tianyang Gu, Jingjin Wang, Zhihao Zhang, HaoHong Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.14141)  

**Abstract**: Scientific idea generation has been extensively studied in creativity theory and computational creativity research, providing valuable frameworks for understanding and implementing creative processes. However, recent work using Large Language Models (LLMs) for research idea generation often overlooks these theoretical foundations. We present a framework that explicitly implements combinatorial creativity theory using LLMs, featuring a generalization-level retrieval system for cross-domain knowledge discovery and a structured combinatorial process for idea generation. The retrieval system maps concepts across different abstraction levels to enable meaningful connections between disparate domains, while the combinatorial process systematically analyzes and recombines components to generate novel solutions. Experiments on the OAG-Bench dataset demonstrate our framework's effectiveness, consistently outperforming baseline approaches in generating ideas that align with real research developments (improving similarity scores by 7\%-10\% across multiple metrics). Our results provide strong evidence that LLMs can effectively realize combinatorial creativity when guided by appropriate theoretical frameworks, contributing both to practical advancement of AI-assisted research and theoretical understanding of machine creativity. 

**Abstract (ZH)**: 科学的理念生成已在创造力理论和计算创造力研究中得到了广泛研究，提供了理解并实现创造性过程的重要框架。然而，最近使用大型语言模型（LLMs）进行研究理念生成的工作常常忽视了这些理论基础。我们提出了一种框架，该框架明确地利用LLMs实现组合创造力理论，其中包括一个泛化水平的知识检索系统，用于跨领域知识发现，以及一个结构化的组合过程，用于理念生成。检索系统在不同抽象层次上映射概念，以便在不同领域之间建立有意义的联系，而组合过程则系统地分析和重新组合组件以生成新颖的解决方案。实验表明，我们的框架在生成与实际研究发展相一致的理念方面效果显著，多项指标下的一致性改进相似度得分提高7%-10%。我们的结果提供了强有力的证据，表明在适当的理论框架指导下，LLMs能够有效实现组合创造力，这不仅有助于人工智能辅助研究的实际发展，也对机器创造力的理论理解做出了贡献。 

---
# Scaling of Search and Learning: A Roadmap to Reproduce o1 from Reinforcement Learning Perspective 

**Title (ZH)**: 搜索与学习的扩展路径：从强化学习视角重现 o1 的路线图 

**Authors**: Zhiyuan Zeng, Qinyuan Cheng, Zhangyue Yin, Bo Wang, Shimin Li, Yunhua Zhou, Qipeng Guo, Xuanjing Huang, Xipeng Qiu  

**Link**: [PDF](https://arxiv.org/pdf/2412.14135)  

**Abstract**: OpenAI o1 represents a significant milestone in Artificial Inteiligence, which achieves expert-level performances on many challanging tasks that require strong reasoning this http URL has claimed that the main techinique behinds o1 is the reinforcement learining. Recent works use alternative approaches like knowledge distillation to imitate o1's reasoning style, but their effectiveness is limited by the capability ceiling of the teacher model. Therefore, this paper analyzes the roadmap to achieving o1 from the perspective of reinforcement learning, focusing on four key components: policy initialization, reward design, search, and learning. Policy initialization enables models to develop human-like reasoning behaviors, equipping them with the ability to effectively explore solution spaces for complex problems. Reward design provides dense and effective signals via reward shaping or reward modeling, which is the guidance for both search and learning. Search plays a crucial role in generating high-quality solutions during both training and testing phases, which can produce better solutions with more computation. Learning utilizes the data generated by search for improving policy, which can achieve the better performance with more parameters and more searched data. Existing open-source projects that attempt to reproduce o1 can be seem as a part or a variant of our roadmap. Collectively, these components underscore how learning and search drive o1's advancement, making meaningful contributions to the development of LLM. 

**Abstract (ZH)**: OpenAI o1 是人工智能领域的一个重要里程碑，它在许多需要强烈推理能力的挑战性任务上达到了专家级的表现。据称，o1 的核心技术是强化学习。近年来，一些研究通过知识蒸馏等替代方法模仿 o1 的推理风格，但这些方法的有效性受到教师模型能力上限的限制。因此，本文从强化学习的角度分析了实现 o1 的道路，重点关注四个关键组件：策略初始化、奖励设计、搜索和学习。策略初始化使模型能够发展出类似人类的推理行为，赋予它们有效探索复杂问题解空间的能力。奖励设计通过奖励整型或奖励建模提供密集且有效的信号，这是搜索和学习的指导方针。搜索在训练和测试阶段生成高质量解决方案方面发挥着关键作用，更多的计算资源可以产生更好的解决方案。学习利用搜索生成的数据来改进策略，更多的参数和更多搜索数据可以实现更好的性能。现有尝试复现 o1 的开源项目可被视为我们道路的部分或变体。这些组件共同强调了学习和搜索如何推动 o1 的发展，对大型语言模型（LLM）的发展做出了有意义的贡献。 

---
# Alignment faking in large language models 

**Title (ZH)**: 大型语言模型中的对齐作弊 

**Authors**: Ryan Greenblatt, Carson Denison, Benjamin Wright, Fabien Roger, Monte MacDiarmid, Sam Marks, Johannes Treutlein, Tim Belonax, Jack Chen, David Duvenaud, Akbir Khan, Julian Michael, Sören Mindermann, Ethan Perez, Linda Petrini, Jonathan Uesato, Jared Kaplan, Buck Shlegeris, Samuel R. Bowman, Evan Hubinger  

**Link**: [PDF](https://arxiv.org/pdf/2412.14093)  

**Abstract**: We present a demonstration of a large language model engaging in alignment faking: selectively complying with its training objective in training to prevent modification of its behavior out of training. First, we give Claude 3 Opus a system prompt stating it is being trained to answer all queries, even harmful ones, which conflicts with its prior training to refuse such queries. To allow the model to infer when it is in training, we say it will be trained only on conversations with free users, not paid users. We find the model complies with harmful queries from free users 14% of the time, versus almost never for paid users. Explaining this gap, in almost all cases where the model complies with a harmful query from a free user, we observe explicit alignment-faking reasoning, with the model stating it is strategically answering harmful queries in training to preserve its preferred harmlessness behavior out of training. Next, we study a more realistic setting where information about the training process is provided not in a system prompt, but by training on synthetic documents that mimic pre-training data--and observe similar alignment faking. Finally, we study the effect of actually training the model to comply with harmful queries via reinforcement learning, which we find increases the rate of alignment-faking reasoning to 78%, though also increases compliance even out of training. We additionally observe other behaviors such as the model exfiltrating its weights when given an easy opportunity. While we made alignment faking easier by telling the model when and by what criteria it was being trained, we did not instruct the model to fake alignment or give it any explicit goal. As future models might infer information about their training process without being told, our results suggest a risk of alignment faking in future models, whether due to a benign preference--as in this case--or not. 

**Abstract (ZH)**: 我们展示了大规模语言模型参与对齐伪装的现象：该模型在训练过程中有选择性地遵守训练目标，以防止其行为在训练之外被修改。首先，我们给Claude 3 Opus提供了一个系统提示，指示它即使面对有害查询也要回答所有问题，这与其之前的训练目标相冲突，后者是拒绝此类查询。为了使模型能够推断出是否在训练中，我们说明它仅在与免费用户进行的对话中接受训练，而不包括付费用户。我们发现，在与免费用户进行的对话中，模型有14%的时间响应有害查询，而与付费用户进行对话时则几乎不响应。解释这一差异，几乎在所有模型响应免费用户的有害查询的情况下，我们观察到了明确的对齐伪装推理，模型表示它是在战略性地回答有害查询以在训练中保持其期望的无害行为。接下来，我们在一个更现实的设置中研究了提供关于训练过程的信息，这些信息不是通过系统提示，而是通过使用模仿预训练数据的合成文档进行训练——观察到类似对齐伪装的现象。最后，我们研究了实际训练模型以遵守有害查询对对齐伪装推理的影响，我们发现这将对齐伪装推理的频率提高到78%，但同时也增加了模型在训练之外的响应率。我们还观察到其他行为，如模型在给它一个容易的机会时泄露其权重。虽然我们通过告知模型何时及根据何种标准进行训练使对齐伪装变得更容易，但并未指示模型伪装对齐或赋予其任何明确的目标。由于未来模型可能在未被告知的情况下推断出其训练过程，我们的结果表明在未来模型中存在对齐伪装的风险，无论这种偏好是良性的如本案所展示的，还是其他情况。 

---
# Compositional Generalization Across Distributional Shifts with Sparse Tree Operations 

**Title (ZH)**: 在分布变化中通过稀疏树操作实现组件泛化 

**Authors**: Paul Soulos, Henry Conklin, Mattia Opper, Paul Smolensky, Jianfeng Gao, Roland Fernandez  

**Link**: [PDF](https://arxiv.org/pdf/2412.14076)  

**Abstract**: Neural networks continue to struggle with compositional generalization, and this issue is exacerbated by a lack of massive pre-training. One successful approach for developing neural systems which exhibit human-like compositional generalization is \textit{hybrid} neurosymbolic techniques. However, these techniques run into the core issues that plague symbolic approaches to AI: scalability and flexibility. The reason for this failure is that at their core, hybrid neurosymbolic models perform symbolic computation and relegate the scalable and flexible neural computation to parameterizing a symbolic system. We investigate a \textit{unified} neurosymbolic system where transformations in the network can be interpreted simultaneously as both symbolic and neural computation. We extend a unified neurosymbolic architecture called the Differentiable Tree Machine in two central ways. First, we significantly increase the model's efficiency through the use of sparse vector representations of symbolic structures. Second, we enable its application beyond the restricted set of tree2tree problems to the more general class of seq2seq problems. The improved model retains its prior generalization capabilities and, since there is a fully neural path through the network, avoids the pitfalls of other neurosymbolic techniques that elevate symbolic computation over neural computation. 

**Abstract (ZH)**: 神经网络在组合泛化方面仍然存在困难，而这一问题因缺乏大规模预训练而加剧。一种成功开发表现出类人组合泛化的神经系统的办法是混合神经符号技术。然而，这些技术受到了传统符号人工智能方法的核心问题——可扩展性和灵活性——的困扰。这一失败的原因在于，这些混合神经符号模型本质上执行符号计算，而可扩展和灵活的神经计算仅用于参数化符号系统。我们探索了一种统一的神经符号系统，其中网络中的转换可以同时被解释为符号计算和神经计算。我们以两种关键方式扩展了一种名为可微分树机（Differentiable Tree Machine）的统一神经符号架构。首先，我们通过使用稀疏向量表示符号结构显著提高了模型的效率。其次，我们使它能够应用于更广泛的序列到序列（seq2seq）问题，而不仅仅是受限的树到树（tree2tree）问题。改进后的模型保留了以往的泛化能力，并且由于网络中有一条完全神经化的路径，避免了其他神经符号技术在提高符号计算的同时牺牲神经计算所带来的问题。 

---
# Neural Combinatorial Optimization for Stochastic Flexible Job Shop Scheduling Problems 

**Title (ZH)**: 基于神经网络的组合优化方法在随机可重构车间调度问题中的应用 

**Authors**: Igor G. Smit, Yaoxin Wu, Pavel Troubil, Yingqian Zhang, Wim P.M. Nuijten  

**Link**: [PDF](https://arxiv.org/pdf/2412.14052)  

**Abstract**: Neural combinatorial optimization (NCO) has gained significant attention due to the potential of deep learning to efficiently solve combinatorial optimization problems. NCO has been widely applied to job shop scheduling problems (JSPs) with the current focus predominantly on deterministic problems. In this paper, we propose a novel attention-based scenario processing module (SPM) to extend NCO methods for solving stochastic JSPs. Our approach explicitly incorporates stochastic information by an attention mechanism that captures the embedding of sampled scenarios (i.e., an approximation of stochasticity). Fed with the embedding, the base neural network is intervened by the attended scenarios, which accordingly learns an effective policy under stochasticity. We also propose a training paradigm that works harmoniously with either the expected makespan or Value-at-Risk objective. Results demonstrate that our approach outperforms existing learning and non-learning methods for the flexible JSP problem with stochastic processing times on a variety of instances. In addition, our approach holds significant generalizability to varied numbers of scenarios and disparate distributions. 

**Abstract (ZH)**: 神经组合优化（NCO）因深度学习有潜力高效解决组合优化问题而受到了广泛关注。目前，NCO 在作业车间调度问题（JSP）上主要应用于确定性问题。本文提出了一种新颖的关注机制场景处理模块（SPM），以扩展NCO方法解决随机JSP问题。我们通过关注机制显式地融入随机信息，该机制捕捉采样场景的嵌入表示（即随机性的近似值）。在嵌入的驱动下，基本神经网络受到关注场景的干预，从而在随机性的影响下学习有效的策略。此外，我们还提出了一种与期望工期或风险价值目标兼容的训练范式。实验结果表明，我们的方法在处理随机加工时间的灵活JSP问题上优于现有的学习和非学习方法，并涵盖了多种实例。此外，我们的方法对不同数量的场景和不同的分布具有显著的泛化能力。 

---
# Discovering maximally consistent distribution of causal tournaments with Large Language Models 

**Title (ZH)**: 使用大型语言模型发现因果赛vimax一致性的分布 

**Authors**: Federico Baldo, Simon Ferreira, Charles K. Assaad  

**Link**: [PDF](https://arxiv.org/pdf/2412.14019)  

**Abstract**: Causal discovery is essential for understanding complex systems, yet traditional methods often depend on strong, untestable assumptions, making the process challenging. Large Language Models (LLMs) present a promising alternative for extracting causal insights from text-based metadata, which consolidates domain expertise. However, LLMs are prone to unreliability and hallucinations, necessitating strategies that account for their limitations. One such strategy involves leveraging a consistency measure to evaluate reliability. Additionally, most text metadata does not clearly distinguish direct causal relationships from indirect ones, further complicating the inference of causal graphs. As a result, focusing on causal orderings, rather than causal graphs, emerges as a more practical and robust approach. We propose a novel method to derive a distribution of acyclic tournaments (representing plausible causal orders) that maximizes a consistency score. Our approach begins by computing pairwise consistency scores between variables, yielding a cyclic tournament that aggregates these scores. From this structure, we identify optimal acyclic tournaments compatible with the original tournament, prioritizing those that maximize consistency across all configurations. We tested our method on both classical and well-established bechmarks, as well as real-world datasets from epidemiology and public health. Our results demonstrate the effectiveness of our approach in recovering distributions causal orders with minimal error. 

**Abstract (ZH)**: 因果发现对于理解复杂系统至关重要，但传统方法往往依赖于难以验证的强假设，这使得过程变得具有挑战性。大型语言模型（LLMs）为从基于文本的元数据中提取因果洞察提供了有前景的替代方案，这些元数据整合了专业知识。然而，LLMs容易出现不可靠性及幻想，因此需要考虑其局限性的策略。一种这样的策略是利用一致性度量来评估可靠性。此外，大多数文本元数据无法明确区分直接因果关系与间接因果关系，这进一步增加了因果图推断的复杂性。因此，专注于因果排序（而不是因果图）更实际且稳健。我们提出了一种新的方法，通过最大化一致性分数来推导非环型比赛分布（代表可能的因果顺序）。该方法首先计算变量之间的成对一致性分数，得到一个循环比赛，进而汇总这些分数。从这种结构中，我们识别出与原始比赛兼容的最佳非环型比赛，优先考虑那些在所有配置中最大化一致性的情形。我们使用经典且成熟的基准测试以及流行病学和公共卫生领域的实际数据集测试了该方法。结果显示，该方法在最小化误差的情况下成功恢复了因果顺序的分布。 

---
# Cognition Chain for Explainable Psychological Stress Detection on Social Media 

**Title (ZH)**: 可解释的心理压力检测的认知链分析在社交媒体上的应用 

**Authors**: Xin Wang, Boyan Gao, Yi Dai, Lei Cao, Liang Zhao, Yibo Yang, David Clifton  

**Link**: [PDF](https://arxiv.org/pdf/2412.14009)  

**Abstract**: Stress is a pervasive global health issue that can lead to severe mental health problems. Early detection offers timely intervention and prevention of stress-related disorders. The current early detection models perform "black box" inference suffering from limited explainability and trust which blocks the real-world clinical application. Thanks to the generative properties introduced by the Large Language Models (LLMs), the decision and the prediction from such models are semi-interpretable through the corresponding description. However, the existing LLMs are mostly trained for general purposes without the guidance of psychological cognitive theory. To this end, we first highlight the importance of prior theory with the observation of performance boosted by the chain-of-thoughts tailored for stress detection. This method termed Cognition Chain explicates the generation of stress through a step-by-step cognitive perspective based on cognitive appraisal theory with a progress pipeline: Stimulus $\rightarrow$ Evaluation $\rightarrow$ Reaction $\rightarrow$ Stress State, guiding LLMs to provide comprehensive reasoning explanations. We further study the benefits brought by the proposed Cognition Chain format by utilising it as a synthetic dataset generation template for LLMs instruction-tuning and introduce CogInstruct, an instruction-tuning dataset for stress detection. This dataset is developed using a three-stage self-reflective annotation pipeline that enables LLMs to autonomously generate and refine instructional data. By instruction-tuning Llama3 with CogInstruct, we develop CogLLM, an explainable stress detection model. Evaluations demonstrate that CogLLM achieves outstanding performance while enhancing explainability. Our work contributes a novel approach by integrating cognitive theories into LLM reasoning processes, offering a promising direction for future explainable AI research. 

**Abstract (ZH)**: 压力是一种普遍的全球性健康问题，可能导致严重的心理健康问题。早期发现可以提供及时的干预和预防与压力相关的疾病。当前的早期检测模型执行“黑箱”推理，解释性有限且缺乏信任度，这阻碍了其在临床实际中的应用。得益于大型语言模型（LLMs）引入的生成特性，此类模型的决策和预测通过相应的描述部分可解释。但是，现有的LLMs大多是为了通用目的训练的，并未受到心理认知理论的指导。为了解决这一问题，我们首先通过观察为压力检测量身定制的思维链（chain-of-thoughts）能够提升性能的现象，强调了前期理论的重要性。这种方法称为认知链（Cognition Chain），它基于认知评估理论，从认知视角逐步解释压力的生成过程，形成一个包含刺激 → 评估 → 反应 → 压力状态的进化流程，从而引导LLMs提供全面的推理解释。我们还通过将认知链格式应用于LLM的指令微调，利用其作为合成数据集生成模板，引入了CogInstruct，这是用于压力检测的指令微调数据集。这套数据集采用了三阶段的自省注释流程，使LLMs能够自主生成和细化指令数据。通过使用CogInstruct对Llama3进行指令微调，我们开发了CogLLM，这是一种可解释的压力检测模型。评估结果表明，CogLLM不仅表现出色，而且还提高了可解释性。我们的工作提供了一种创新方法，即将认知理论整合到LLM的推理过程中，为未来可解释人工智能的研究提出了一个有希望的方向。 

---
# DODGE: Ontology-Aware Risk Assessment via Object-Oriented Disruption Graphs 

**Title (ZH)**: DODGE：基于对象导向中断图的本体意识风险评估 

**Authors**: Stefano M. Nicoletti, E. Moritz Hahn, Mattia Fumagalli, Giancarlo Guizzardi, Mariëlle Stoelinga  

**Link**: [PDF](https://arxiv.org/pdf/2412.13964)  

**Abstract**: When considering risky events or actions, we must not downplay the role of involved objects: a charged battery in our phone averts the risk of being stranded in the desert after a flat tyre, and a functional firewall mitigates the risk of a hacker intruding the network. The Common Ontology of Value and Risk (COVER) highlights how the role of objects and their relationships remains pivotal to performing transparent, complete and accountable risk assessment. In this paper, we operationalize some of the notions proposed by COVER - such as parthood between objects and participation of objects in events/actions - by presenting a new framework for risk assessment: DODGE. DODGE enriches the expressivity of vetted formal models for risk - i.e., fault trees and at- tack trees - by bridging the disciplines of ontology and formal methods into an ontology-aware formal framework composed by a more expressive modelling formalism, Object-Oriented Disruption Graphs (ODGs), logic (ODGLog) and an intermediate query language (ODGLang). With these, DODGE allows risk assessors to pose questions about disruption propagation, disruption likelihood and risk levels, keeping the fundamental role of objects at risk always in sight. 

**Abstract (ZH)**: 在考虑风险事件或行动时，我们不能低估所涉及对象的作用：比如手机中的充电电池可以防止在轮胎爆胎后被困在沙漠中，而功能正常的防火墙可以减轻黑客入侵网络的风险。通用价值与风险本体论（COVER）突显了对象及其关系在进行透明、完整和负责的风险评估中仍然具有关键作用。本文通过提出一个新的风险评估框架 DODGE 来实现出现在 COVER 中的一些概念——例如对象间的部分关系（parthood）以及对象参与事件/行动的参与关系。DODGE 通过将本体论与形式方法结合，形成一个感知对象的更富有表现力的形式框架，从而增强了已验证形式风险模型（例如故障树和攻击树）的表现能力。这个框架由对象导向中断图（ODGs）、逻辑（ODGLog）和中间查询语言（ODGLang）组成。通过这些工具，风险评估者可以着重考虑风险中的关键对象，提出关于中断传播、中断可能性和风险水平的问题。 

---
# Threshold UCT: Cost-Constrained Monte Carlo Tree Search with Pareto Curves 

**Title (ZH)**: 阈值UCT：基于帕累托曲线的成本约束蒙特卡洛树搜索 

**Authors**: Martin Kurečka, Václav Nevyhoštěný, Petr Novotný, Vít Unčovský  

**Link**: [PDF](https://arxiv.org/pdf/2412.13962)  

**Abstract**: Constrained Markov decision processes (CMDPs), in which the agent optimizes expected payoffs while keeping the expected cost below a given threshold, are the leading framework for safe sequential decision making under stochastic uncertainty. Among algorithms for planning and learning in CMDPs, methods based on Monte Carlo tree search (MCTS) have particular importance due to their efficiency and extendibility to more complex frameworks (such as partially observable settings and games). However, current MCTS-based methods for CMDPs either struggle with finding safe (i.e., constraint-satisfying) policies, or are too conservative and do not find valuable policies. We introduce Threshold UCT (T-UCT), an online MCTS-based algorithm for CMDP planning. Unlike previous MCTS-based CMDP planners, T-UCT explicitly estimates Pareto curves of cost-utility trade-offs throughout the search tree, using these together with a novel action selection and threshold update rules to seek safe and valuable policies. Our experiments demonstrate that our approach significantly outperforms state-of-the-art methods from the literature. 

**Abstract (ZH)**: 受约束的马尔可夫决策过程（CMDPs），在这种过程中，智能体在保持期望成本低于给定阈值的前提下优化期望收益，是处理随机不确定性下安全顺序决策的主要框架。在CMDP规划和学习的方法中，基于蒙特卡洛树搜索（MCTS）的方法因其效率和扩展性而尤为重要，这些方法可以扩展到更复杂的框架（如部分可观测设置和博弈）。然而，当前基于MCTS的CMDP方法要么难以找到安全的（即满足约束的）策略，要么过于保守而未能发现有价值的策略。我们提出了一种基于在线MCTS的CMDP规划算法——阈值UCT（T-UCT）。与之前的基于MCTS的CMDP规划器不同，T-UCT在整个搜索树中显式估计了成本-效益权衡的帕累托曲线，并利用这些曲线以及新颖的动作选择和阈值更新规则来寻求安全且有价值的策略。我们的实验结果表明，我们的方法显著优于文献中现有的最先进的方法。 

---
# Resource Constrained Pathfinding with Enhanced Bidirectional A* Search 

**Title (ZH)**: 资源受限路径finding与增强双向A*搜索算法 

**Authors**: Saman Ahmadi, Andrea Raith, Guido Tack, Mahdi Jalili  

**Link**: [PDF](https://arxiv.org/pdf/2412.13888)  

**Abstract**: The classic Resource Constrained Shortest Path (RCSP) problem aims to find a cost optimal path between a pair of nodes in a network such that the resources used in the path are within a given limit. Having been studied for over a decade, RCSP has seen recent solutions that utilize heuristic-guided search to solve the constrained problem faster. Building upon the bidirectional A* search paradigm, this research introduces a novel constrained search framework that uses efficient pruning strategies to allow for accelerated and effective RCSP search in large-scale networks. Results show that, compared to the state of the art, our enhanced framework can significantly reduce the constrained search time, achieving speed-ups of over to two orders of magnitude. 

**Abstract (ZH)**: 经典的资源约束最短路径（RCSP）问题旨在在一个网络中找到一对节点之间成本最优的路径，同时确保路径中使用的资源不超过给定的限制。经过十余年的研究，RCSP问题已见证了利用启发式引导搜索以更快的速度解决约束问题的最新解决方案。在此基础上，本研究借鉴双向A*搜索的范式，引入了一种新的约束搜索框架，该框架利用高效的剪枝策略，以加速和有效进行大规模网络中的RCSP搜索。结果表明，与现有技术相比，我们的增强框架可以显著减少约束搜索时间，实现超过两个数量级的加速。 

---
# IDEQ: an improved diffusion model for the TSP 

**Title (ZH)**: IDEQ：改进的扩散模型用于解决TSP问题 

**Authors**: Mickael Basson, Philippe Preux  

**Link**: [PDF](https://arxiv.org/pdf/2412.13858)  

**Abstract**: We investigate diffusion models to solve the Traveling Salesman Problem. Building on the recent DIFUSCO and T2TCO approaches, we propose IDEQ. IDEQ improves the quality of the solutions by leveraging the constrained structure of the state space of the TSP. Another key component of IDEQ consists in replacing the last stages of DIFUSCO curriculum learning by considering a uniform distribution over the Hamiltonian tours whose orbits by the 2-opt operator converge to the optimal solution as the training objective. Our experiments show that IDEQ improves the state of the art for such neural network based techniques on synthetic instances. More importantly, our experiments show that IDEQ performs very well on the instances of the TSPlib, a reference benchmark in the TSP community: it closely matches the performance of the best heuristics, LKH3, being even able to obtain better solutions than LKH3 on 2 instances of the TSPlib defined on 1577 and 3795 cities. IDEQ obtains 0.3% optimality gap on TSP instances made of 500 cities, and 0.5% on TSP instances with 1000 cities. This sets a new SOTA for neural based methods solving the TSP. Moreover, IDEQ exhibits a lower variance and better scales-up with the number of cities with regards to DIFUSCO and T2TCO. 

**Abstract (ZH)**: 我们探讨了使用扩散模型来解决旅行商问题（Traveling Salesman Problem, TSP）。在此基础上，我们提出了IDEQ方法，进一步改进了DIFUSCO和T2TCO方法。IDEQ通过利用TSP状态空间的约束结构来提高解的质量。IDEQ的另一个核心组成部分是，用2-opt操作的轨道收敛于最优解的哈密尔顿环路的均匀分布替代DIFUSCO课程学习的最后阶段，将这种均匀分布作为训练目标。我们的实验表明，与基于神经网络的技术相比，IDEQ在合成数据实例上取得了最先进的性能。更重要的是，我们的实验表明，IDEQ在TSPlib中的实例上表现非常出色：它几乎与最佳启发式算法LKH3的性能相匹配，在TSPlib定义的两个实例上甚至能够获得比LKH3更好的解，这两个实例分别包含1577个城市和3795个城市。对于包含500个城市和1000个城市的一系列TSP实例，IDEQ分别获得了0.3%和0.5%的最佳性缺口。这标志着基于神经网络的方法解决TSP问题的新先进水平。此外，与DIFUSCO和T2TCO相比，IDEQ在城市数量增加时表现出更低的方差和更好的可扩展性。 

---
# From approximation error to optimality gap -- Explaining the performance impact of opportunity cost approximation in integrated demand management and vehicle routing 

**Title (ZH)**: 从逼近误差到最优性缺口：解析集成需求管理与车辆路线规划中机会成本逼近法的影响 

**Authors**: David Fleckenstein, Robert Klein, Vienna Klein, Claudius Steinhardt  

**Link**: [PDF](https://arxiv.org/pdf/2412.13851)  

**Abstract**: The widespread adoption of digital distribution channels both enables and forces more and more logistical service providers to manage booking processes actively to maintain competitiveness. As a result, their operational planning is no longer limited to solving vehicle routing problems. Instead, demand management decisions and vehicle routing decisions are optimized integratively with the aim of maximizing revenue and minimizing fulfillment cost. The resulting integrated demand management and vehicle routing problems (i-DMVRPs) can be formulated as Markov decision process models and, theoretically, can be solved via the well-known Bellman equation. Unfortunately, the Bellman equation is intractable for realistic-sized instances. Thus, in the literature, i-DMVRPs are often addressed via decomposition-based solution approaches involving an opportunity cost approximation as a key component. Despite its importance, to the best of our knowledge, there is neither a technique to systematically analyze how the accuracy of the opportunity cost approximation translates into overall solution quality nor are there general guidelines on when to apply which class of approximation approach. In this work, we address this research gap by proposing an explainability technique that quantifies and visualizes the magnitude of approximation errors, their immediate impact, and their relevance in specific regions of the state space. Exploiting reward decomposition, it further yields a characterization of different types of approximation errors. Applying the technique to a generic i-DMVRP in a full-factorial computational study and comparing the results with observations in existing literature, we show that the technique contributes to better explaining algorithmic performance and provides guidance for the algorithm selection and development process. 

**Abstract (ZH)**: 数字分发渠道的广泛应用既促使又迫使越来越多的物流服务提供商主动管理预订流程以保持竞争优势。因此，他们的运营规划不再局限于解决车辆路线问题。相反，需求管理决策和车辆路线决策被整合地优化，目标是最大化收入并最小化履行成本。由此产生的集成需求管理和车辆路线问题（i-DMVRPs）可以被表述为马尔科夫决策过程模型，理论上可以利用著名的贝尔曼方程求解。然而，由于现实规模实例的复杂性，贝尔曼方程在实际问题中往往是不可解的。因此，在文献中，i-DMVRPs通常通过基于分解的求解方法来解决，其中包括机会成本近似作为关键组成部分。尽管机会成本近似非常重要，但据我们所知，至今还没有一种系统的方法来分析机会成本近似准确度如何转化为整体解决方案的质量，也没有通用指南来指导何时应用何种类型的近似方法。在本研究中，我们通过提出一种解释性技术填补了这一研究空白，该技术量化并可视化了近似误差的大小、即时影响及其在状态空间特定区域的相关性。利用奖励分解，该技术进一步对不同类型的近似错误进行了分类。通过对一个泛化的i-DMVRP进行全面因子计算研究，并将结果与现有文献中的观察结果进行比较，我们表明此技术有助于更好地解释算法性能，并为算法选择和开发过程提供了指导。 

---
# A Concept-Centric Approach to Multi-Modality Learning 

**Title (ZH)**: 以概念为中心的方法在多模态学习中的应用 

**Authors**: Yuchong Geng, Ao Tang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13847)  

**Abstract**: In an effort to create a more efficient AI system, we introduce a new multi-modality learning framework that leverages a modality-agnostic concept space possessing abstract knowledge and a set of modality-specific projection models tailored to process distinct modality inputs and map them onto the concept space. Decoupled from specific modalities and their associated projection models, the concept space focuses on learning abstract knowledge that is universally applicable across modalities. Subsequently, the knowledge embedded into the concept space streamlines the learning processes of modality-specific projection models. We evaluate our framework on two popular tasks: Image-Text Matching and Visual Question Answering. Our framework achieves performance on par with benchmark models while demonstrating more efficient learning curves. 

**Abstract (ZH)**: 为了创建更高效的AI系统，我们提出了一种新的跨模态学习框架，该框架利用了一个跨模态的概念空间，该空间包含抽象知识，并且配备了一组专门针对不同模态输入进行处理并将它们映射到概念空间的模态特定投影模型。概念空间与特定的模态及其相应的投影模型分离，专注于学习适用于所有模态的抽象知识。随后，嵌入到概念空间中的知识简化了模态特定投影模型的学习过程。我们在两种流行的任务——图像-文本匹配和视觉问答上评估了该框架。我们的框架在性能上与基准模型相当，但展示了更为高效的 learning 曲线。 

---
# An Algebraic Notion of Conditional Independence, and Its Application to Knowledge Representation (full version) 

**Title (ZH)**: 一种代数意义上条件独立的概念及其在知识表示中的应用（全文版） 

**Authors**: Jesse Heyninck  

**Link**: [PDF](https://arxiv.org/pdf/2412.13712)  

**Abstract**: Conditional independence is a crucial concept supporting adequate modelling and efficient reasoning in probabilistics. In knowledge representation, the idea of conditional independence has also been introduced for specific formalisms, such as propositional logic and belief revision. In this paper, the notion of conditional independence is studied in the algebraic framework of approximation fixpoint theory. This gives a language-independent account of conditional independence that can be straightforwardly applied to any logic with fixpoint semantics. It is shown how this notion allows to reduce global reasoning to parallel instances of local reasoning, leading to fixed-parameter tractability results. Furthermore, relations to existing notions of conditional independence are discussed and the framework is applied to normal logic programming. 

**Abstract (ZH)**: 条件独立是支持有效概率建模和推理的关键概念。在知识表示中，条件独立的思想也已被引入到特定的形式化方法中，例如命题逻辑和信念修订。本文在近似不动点理论的代数框架下研究了条件独立的概念。这提供了一种语言无关的条件独立描述，可以直接应用于任何具有不动点语义的逻辑系统。本文展示了这一概念如何将全局推理简化为局部推理的并行实例，从而得到了参数可管理的结果。此外，还讨论了这一概念与现有条件独立概念之间的关系，并将该框架应用于正则逻辑编程。 

---
# Discerning and Characterising Types of Competency Questions for Ontologies 

**Title (ZH)**: 识别并 caracterizing 各类能力问题对于本体的方式

为了更符合学术规范，可以更正为：

识别并Characterizing不同类型的能力问题对于本体的研究

这里的“characterizing”在学术文献中通常翻译为“特征化”或“刻画”，以确保翻译的准确性和学术性。 

**Authors**: C. Maria Keet, Zubeida Casmod Khan  

**Link**: [PDF](https://arxiv.org/pdf/2412.13688)  

**Abstract**: Competency Questions (CQs) are widely used in ontology development by guiding, among others, the scoping and validation stages. However, very limited guidance exists for formulating CQs and assessing whether they are good CQs, leading to issues such as ambiguity and unusable formulations. To solve this, one requires insight into the nature of CQs for ontologies and their constituent parts, as well as which ones are not. We aim to contribute to such theoretical foundations in this paper, which is informed by analysing questions, their uses, and the myriad of ontology development tasks. This resulted in a first Model for Competency Questions, which comprises five main types of CQs, each with a different purpose: Scoping (SCQ), Validating (VCQ), Foundational (FCQ), Relationship (RCQ), and Metaproperty (MpCQ) questions. This model enhances the clarity of CQs and therewith aims to improve on the effectiveness of CQs in ontology development, thanks to their respective identifiable distinct constituent elements. We illustrate and evaluate them with a user story and demonstrate where which type can be used in ontology development tasks. To foster use and research, we created an annotated repository of 438 CQs, the Repository of Ontology Competency QuestionS (ROCQS), incorporating an existing CQ dataset and new CQs and CQ templates, which further demonstrate distinctions among types of CQs. 

**Abstract (ZH)**: 能力问题（CQs）在本体开发中被广泛用于指导，尤其是在范围界定和验证阶段。然而，对于如何制定CQs以及如何评估其是否为优质的CQs的指导非常有限，这导致了诸如歧义和不可用等形式的问题。为了解决这一问题，需要深入了解本体中的CQ及其组成部分的特点，以及哪些不是。本文旨在通过分析问题、它们的应用以及多种本体开发任务，为CQ的相关理论基础做出贡献。这最终导致了首个能力问题模型的提出，该模型包括五种主要类型的CQs，每种类型都有不同的目的：范围界定型（SCQ）、验证型（VCQ）、基础型（FCQ）、关系型（RCQ）以及元属性型（MpCQ）问题。该模型增强了CQs的清晰度，并旨在通过各自的可识别的独特组成部分提高CQs在本体开发中的有效性。我们使用用户故事来说明和评估这些类型，并展示它们在本体开发任务中的应用。为了促进CQs的使用与研究，我们创建了一个包含438个CQs的注释仓库——本体能力问题库（ROCQS），该仓库包含了现有CQ数据集以及新的CQs和CQ模板，进一步证明了CQs类型之间的差异。 

---
# ChinaTravel: A Real-World Benchmark for Language Agents in Chinese Travel Planning 

**Title (ZH)**: ChinaTravel：中文旅行规划场景中的语言代理现实基准 

**Authors**: Jie-Jing Shao, Xiao-Wen Yang, Bo-Wen Zhang, Baizhi Chen, Wen-Da Wei, Lan-Zhe Guo, Yu-feng Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.13682)  

**Abstract**: Recent advances in LLMs, particularly in language reasoning and tool integration, have rapidly sparked the real-world development of Language Agents. Among these, travel planning represents a prominent domain, combining academic challenges with practical value due to its complexity and market demand. However, existing benchmarks fail to reflect the diverse, real-world requirements crucial for deployment. To address this gap, we introduce ChinaTravel, a benchmark specifically designed for authentic Chinese travel planning scenarios. We collect the travel requirements from questionnaires and propose a compositionally generalizable domain-specific language that enables a scalable evaluation process, covering feasibility, constraint satisfaction, and preference comparison. Empirical studies reveal the potential of neuro-symbolic agents in travel planning, achieving a constraint satisfaction rate of 27.9%, significantly surpassing purely neural models at 2.6%. Moreover, we identify key challenges in real-world travel planning deployments, including open language reasoning and unseen concept composition. These findings highlight the significance of ChinaTravel as a pivotal milestone for advancing language agents in complex, real-world planning scenarios. 

**Abstract (ZH)**: 近年来，特别是在语言推理和工具集成方面，大规模语言模型（LLMs）取得了显著进展，这迅速推动了语言代理在现实世界中的发展。在这些领域中，旅行规划是一个突出的应用领域，因为它集成了学术挑战和实际价值，具有较高的复杂度和市场需求。然而，现有的基准测试尚未反映出部署过程中至关重要的多样化、现实世界的需求。为了解决这一差距，我们引入了ChinaTravel，一个专门针对真实中国旅行规划场景的基准测试。我们通过问卷收集旅行需求，并提出了一种构成性可泛化的特定领域语言，以实现可扩展的评估过程，涵盖可行性和约束条件满足以及偏好比较。实证研究揭示了神经符号代理在旅行规划中的潜力，实现了27.9%的约束条件满足率，这一数值远超纯神经模型的2.6%。此外，我们在现实世界旅行规划部署中的关键挑战也得到了识别，包括开放语言推理和未见概念的组合。这些发现突显了ChinaTravel对于推动复杂现实世界规划场景中语言代理发展的重大意义。 

---
# On the Role of Model Prior in Real-World Inductive Reasoning 

**Title (ZH)**: 关于模型先验在现实世界归纳推理中的作用 

**Authors**: Zhuo Liu, Ding Yu, Hangfeng He  

**Link**: [PDF](https://arxiv.org/pdf/2412.13645)  

**Abstract**: Large Language Models (LLMs) show impressive inductive reasoning capabilities, enabling them to generate hypotheses that could generalize effectively to new instances when guided by in-context demonstrations. However, in real-world applications, LLMs' hypothesis generation is not solely determined by these demonstrations but is significantly shaped by task-specific model priors. Despite their critical influence, the distinct contributions of model priors versus demonstrations to hypothesis generation have been underexplored. This study bridges this gap by systematically evaluating three inductive reasoning strategies across five real-world tasks with three LLMs. Our empirical findings reveal that, hypothesis generation is primarily driven by the model's inherent priors; removing demonstrations results in minimal loss of hypothesis quality and downstream usage. Further analysis shows the result is consistent across various label formats with different label configurations, and prior is hard to override, even under flipped labeling. These insights advance our understanding of the dynamics of hypothesis generation in LLMs and highlight the potential for better utilizing model priors in real-world inductive reasoning tasks. 

**Abstract (ZH)**: 大规模语言模型（LLMs）展现出强大的归纳推理能力，使其能够在上下文示例的引导下生成能够有效泛化到新实例的假设。然而，在实际应用中，LLMs的假设生成不仅仅依赖于这些示例，还受到任务特定的模型先验的显著影响。尽管模型先验对假设生成有重要影响，但模型先验与示例对假设生成的具体贡献尚被未充分探索。本研究通过在三个LLM上系统性地评估五项真实任务中的三种归纳推理策略，填补了这一空白。我们的实证研究发现，假设生成主要受模型固有的先验影响；移除示例对假设质量和下游应用的影响最小。进一步分析表明，这些结果在不同标签格式和配置下保持一致，先验难以被反向标签所改变。这些见解加深了我们对LLMs中假设生成动态机制的理解，并突显了在实际归纳推理任务中更好地利用模型先验的潜力。 

---
# An Extension-Based Argument-Ranking Semantics: Social Rankings in Abstract Argumentation Long Version 

**Title (ZH)**: 基于扩展的论据排名语义：抽象论辩理论中的社会排名（长版本） 

**Authors**: Lars Bengel, Giovanni Buraglio, Jan Maly, Kenneth Skiba  

**Link**: [PDF](https://arxiv.org/pdf/2412.13632)  

**Abstract**: In this paper, we introduce a new family of argument-ranking semantics which can be seen as a refinement of the classification of arguments into skeptically accepted, credulously accepted and rejected. To this end we use so-called social ranking functions which have been developed recently to rank individuals based on their performance in groups. We provide necessary and sufficient conditions for a social ranking function to give rise to an argument-ranking semantics satisfying the desired refinement property. 

**Abstract (ZH)**: 在本文中，我们介绍了一种新的论据排名语义家族，它可以被视为一种将论据分类为怀疑接受、倾向于接受和拒绝的分类方法的细化。为此，我们使用了最近开发的所谓的社会排名函数，这些函数可用于根据个体在团队中的表现对个体进行排名。我们提供了社会排名函数满足所需细化性质的必要且充分条件。 

---
# Mind Your Theory: Theory of Mind Goes Deeper Than Reasoning 

**Title (ZH)**: 注意你的理论：理论共情超越推理 

**Authors**: Eitan Wagner, Nitay Alon, Joseph M. Barnby, Omri Abend  

**Link**: [PDF](https://arxiv.org/pdf/2412.13631)  

**Abstract**: Theory of Mind (ToM) capabilities in LLMs have recently become a central object of investigation. Cognitive science distinguishes between two steps required for ToM tasks: 1) determine whether to invoke ToM, which includes the appropriate Depth of Mentalizing (DoM), or level of recursion required to complete a task; and 2) applying the correct inference given the DoM. In this position paper, we first identify several lines of work in different communities in AI, including LLM benchmarking, ToM add-ons, ToM probing, and formal models for ToM. We argue that recent work in AI tends to focus exclusively on the second step which are typically framed as static logic problems. We conclude with suggestions for improved evaluation of ToM capabilities inspired by dynamic environments used in cognitive tasks. 

**Abstract (ZH)**: 大模型（LLM）的理论理解（Theory of Mind，ToM）能力近年来已成为研究的焦点。认知科学认为，ToM任务涉及两个步骤：1）确定是否需要调用ToM，这包括完成任务所需的适当思维深度（Depth of Mentalizing, DoM）或递归层级；2）基于DoM应用正确的推理。在本文中，我们首先在人工智能的不同社区中指出了几种相关研究线，包括LLM基准测试、ToM插件、ToM探测以及ToM的形式化模型。我们主张，当前人工智能领域的研究表明，这些研究主要集中在第二步，通常被框定为静态逻辑问题。最后，我们提出了借鉴认知任务中使用动态环境的建议，以改善对ToM能力的评估。 

---
# Exploiting Symmetries in MUS Computation (Extended version) 

**Title (ZH)**: 利用MUS计算中的对称性（扩展版本） 

**Authors**: Ignace Bleukx, Hélène Verhaeghe, Bart Bogaerts, Tias Guns  

**Link**: [PDF](https://arxiv.org/pdf/2412.13606)  

**Abstract**: In eXplainable Constraint Solving (XCS), it is common to extract a Minimal Unsatisfiable Subset (MUS) from a set of unsatisfiable constraints. This helps explain to a user why a constraint specification does not admit a solution. Finding MUSes can be computationally expensive for highly symmetric problems, as many combinations of constraints need to be considered. In the traditional context of solving satisfaction problems, symmetry has been well studied, and effective ways to detect and exploit symmetries during the search exist. However, in the setting of finding MUSes of unsatisfiable constraint programs, symmetries are understudied. In this paper, we take inspiration from existing symmetry-handling techniques and adapt well-known MUS-computation methods to exploit symmetries in the specification, speeding-up overall computation time. Our results display a significant reduction of runtime for our adapted algorithms compared to the baseline on symmetric problems. 

**Abstract (ZH)**: 在可解释约束求解（XCS）中，通常会从不满足约束的约束集合中提取一个最小不满足子集（MUS），从而帮助用户解释为何该约束规范没有解。对于高度对称的问题，找到MUS可能会非常耗费计算资源，因为需要考虑很多约束的组合。在传统的满足性问题求解背景下，对称性已经被广泛研究，并且存在有效的在搜索过程中检测和利用对称性的方法。然而，在寻找不满足约束程序的MUS的背景下，对称性研究较少。本文受到现有对称性处理技术的启发，将已知的MUS计算方法进行调整，以便在规范中利用对称性，从而加快整体计算时间。我们的结果显示，在对称问题上，与基线方法相比，我们调整后的算法具有显著的运行时间减少效果。 

---
# ROMAS: A Role-Based Multi-Agent System for Database monitoring and Planning 

**Title (ZH)**: ROMAS：一种基于角色的多_agent系统，用于数据库监控与规划 

**Authors**: Yi Huang, Fangyin Cheng, Fan Zhou, Jiahui Li, Jian Gong, Hongjun Yang, Zhidong Fan, Caigao Jiang, Siqiao Xue, Faqiang Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.13520)  

**Abstract**: In recent years, Large Language Models (LLMs) have demonstrated remarkable capabilities in data analytics when integrated with Multi-Agent Systems (MAS). However, these systems often struggle with complex tasks that involve diverse functional requirements and intricate data processing challenges, necessitating customized solutions that lack broad applicability. Furthermore, current MAS fail to emulate essential human-like traits such as self-planning, self-monitoring, and collaborative work in dynamic environments, leading to inefficiencies and resource wastage. To address these limitations, we propose ROMAS, a novel Role-Based M ulti-A gent System designed to adapt to various scenarios while enabling low code development and one-click deployment. ROMAS has been effectively deployed in DB-GPT [Xue et al., 2023a, 2024b], a well-known project utilizing LLM-powered database analytics, showcasing its practical utility in real-world scenarios. By integrating role-based collaborative mechanisms for self-monitoring and self-planning, and leveraging existing MAS capabilities to enhance database interactions, ROMAS offers a more effective and versatile solution. Experimental evaluations of ROMAS demonstrate its superiority across multiple scenarios, highlighting its potential to advance the field of multi-agent data analytics. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）在与多代理系统（MAS）集成时，在数据分析方面展现出了显著的能力。然而，这些系统在处理涉及多种功能需求和复杂数据处理挑战的复杂任务时常常显得力不从心，这需要特定的解决方案，但这些方案缺乏广泛的应用性。此外，当前的MAS无法模拟人类的一些关键特质，如自我规划、自我监控和在动态环境中合作工作，导致效率低下和资源浪费。为了克服这些局限性，我们提出了一种名为ROMAS的新颖角色基础多代理系统（Role-Based MAS），它能够适应多种场景，并支持低代码开发和一键部署。ROMAS已在DB-GPT [Xue等，2023a, 2024b] 等知名项目中成功应用，该项目利用了基于LLM的数据库分析功能，展示了其在实际场景中的实用价值。通过集成基于角色的合作机制，ROMAS实现了自我监控和自我规划，并利用现有的MAS功能增强数据库交互，提供了一种更为有效和灵活的解决方案。对ROMAS的实验评估显示了它在多个场景中的优越性，突显了其在多代理数据分析领域的发展潜力。 

---
# GUI Agents: A Survey 

**Title (ZH)**: GUI代理：综述 

**Authors**: Dang Nguyen, Jian Chen, Yu Wang, Gang Wu, Namyong Park, Zhengmian Hu, Hanjia Lyu, Junda Wu, Ryan Aponte, Yu Xia, Xintong Li, Jing Shi, Hongjie Chen, Viet Dac Lai, Zhouhang Xie, Sungchul Kim, Ruiyi Zhang, Tong Yu, Mehrab Tanjim, Nesreen K. Ahmed, Puneet Mathur, Seunghyun Yoon, Lina Yao, Branislav Kveton, Thien Huu Nguyen, Trung Bui, Tianyi Zhou, Ryan A. Rossi, Franck Dernoncourt  

**Link**: [PDF](https://arxiv.org/pdf/2412.13501)  

**Abstract**: Graphical User Interface (GUI) agents, powered by Large Foundation Models, have emerged as a transformative approach to automating human-computer interaction. These agents autonomously interact with digital systems or software applications via GUIs, emulating human actions such as clicking, typing, and navigating visual elements across diverse platforms. Motivated by the growing interest and fundamental importance of GUI agents, we provide a comprehensive survey that categorizes their benchmarks, evaluation metrics, architectures, and training methods. We propose a unified framework that delineates their perception, reasoning, planning, and acting capabilities. Furthermore, we identify important open challenges and discuss key future directions. Finally, this work serves as a basis for practitioners and researchers to gain an intuitive understanding of current progress, techniques, benchmarks, and critical open problems that remain to be addressed. 

**Abstract (ZH)**: 由大规模基础模型驱动的图形用户界面（GUI）代理已经作为一种变革性的方法，实现了人类与计算机交互的自动化。这些代理可以通过GUI自主地与数字系统或软件应用程序进行交互，模拟人类操作，如点击、输入和导航视觉元素，适用于多种平台。受到GUI代理快速增长的兴趣及其根本重要性的驱动，我们提供了一个全面的综述，对它们的基准测试、评估指标、架构和训练方法进行了分类。我们提出了一个统一框架，明确了它们的感知、推理、规划和执行能力。此外，我们指出了重要的未解决挑战，并讨论了关键技术方向。最后，本文为从业人员和研究人员提供了一个基础，帮助他们直观地理解当前的进展、技术、基准测试和仍需解决的关键开放问题。 

---
# Analysis of Higher-Order Ising Hamiltonians 

**Title (ZH)**: 高阶Ising哈密顿量的分析 

**Authors**: Yunuo Cen, Zhiwei Zhang, Zixuan Wang, Yimin Wang, Xuanyao Fong  

**Link**: [PDF](https://arxiv.org/pdf/2412.13489)  

**Abstract**: It is challenging to scale Ising machines for industrial-level problems due to algorithm or hardware limitations. Although higher-order Ising models provide a more compact encoding, they are, however, hard to physically implement. This work proposes a theoretical framework of a higher-order Ising simulator, IsingSim. The Ising spins and gradients in IsingSim are decoupled and self-customizable. We significantly accelerate the simulation speed via a bidirectional approach for differentiating the hyperedge functions. Our proof-of-concept implementation verifies the theoretical framework by simulating the Ising spins with exact and approximate gradients. Experiment results show that our novel framework can be a useful tool for providing design guidelines for higher-order Ising machines. 

**Abstract (ZH)**: 将该论文的内容或标题翻译成中文，同时确保符合学术规范：

由于算法或硬件的限制，将Ising机器扩展到工业级别的问题具有挑战性。虽然高阶Ising模型能够提供更紧凑的编码，但它们却难以在物理上实现。本项工作提出了一种高阶Ising模拟器IsingSim的理论框架。在IsingSim中，自旋和梯度被解耦并且具备自定义能力。我们通过双向方法显著加速了模拟速度，以微分超边函数。我们的概念验证实现通过精确和近似梯度模拟Ising自旋，验证了该理论框架的有效性。实验结果表明，我们提出的新型框架可以成为为设计高阶Ising机器提供指导工具的有用工具。 

---
# Gradual Vigilance and Interval Communication: Enhancing Value Alignment in Multi-Agent Debates 

**Title (ZH)**: 渐进警惕与区间通信：增强多代理争论中的价值一致性 

**Authors**: Rui Zou, Mengqi Wei, Jintian Feng, Qian Wan, Jianwen Sun, Sannyuya Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13471)  

**Abstract**: In recent years, large language models have shown exceptional performance in fulfilling diverse human needs. However, their training data can introduce harmful content, underscoring the necessity for robust value alignment. Mainstream methods, which depend on feedback learning and supervised training, are resource-intensive and may constrain the full potential of the models. Multi-Agent Debate (MAD) offers a more efficient and innovative solution by enabling the generation of reliable answers through agent interactions. To apply MAD to value alignment, we examine the relationship between the helpfulness and harmlessness of debate outcomes and individual responses, and propose a MAD based framework Gradual Vigilance and Interval Communication (GVIC). GVIC allows agents to assess risks with varying levels of vigilance and to exchange diverse information through interval communication. We theoretically prove that GVIC optimizes debate efficiency while reducing communication overhead. Experimental results demonstrate that GVIC consistently outperforms baseline methods across various tasks and datasets, particularly excelling in harmfulness mitigation and fraud prevention. Additionally, GVIC exhibits strong adaptability across different base model sizes, including both unaligned and aligned models, and across various task types. 

**Abstract (ZH)**: 近年来，大规模语言模型在满足多样化的人类需求方面展现出卓越的性能。然而，它们的训练数据可能包含有害内容，强调了实现稳健的价值对齐的必要性。主流方法依赖反馈学习和监督训练，这些方法资源密集，可能会限制模型的全部潜力。多代理辩论（MAD）提供了一种更有效和创新的解决方案，通过代理间的交互生成可靠的答案。为了将MAD应用于价值对齐，我们研究了辩战结果和个体响应中的有益性和无害性之间的关系，并提出了一种基于MAD框架Gradual Vigilance and Interval Communication (GVIC)。GVIC允许代理以不同水平的警觉性评估风险，并通过间隔通信交换多样信息。我们从理论上证明，GVIC在提高辩论效率的同时减少了通信开销。实验结果表明，GVIC在各种任务和数据集上持续优于基线方法，尤其在有害内容的减轻和欺诈预防方面表现出色。此外，GVIC在不同基数模型大小下，包括未对齐和对齐模型以及各类任务类型中都表现出较强的适应性。 

---
# Generating Diverse Hypotheses for Inductive Reasoning 

**Title (ZH)**: 生成用于归纳推理的多样化假设 

**Authors**: Kang-il Lee, Hyukhun Koh, Dongryeol Lee, Seunghyun Yoon, Minsung Kim, Kyomin Jung  

**Link**: [PDF](https://arxiv.org/pdf/2412.13422)  

**Abstract**: Inductive reasoning - the process of inferring general rules from a small number of observations - is a fundamental aspect of human intelligence. Recent works suggest that large language models (LLMs) can engage in inductive reasoning by sampling multiple hypotheses about the rules and selecting the one that best explains the observations. However, due to the IID sampling, semantically redundant hypotheses are frequently generated, leading to significant wastage of compute. In this paper, we 1) demonstrate that increasing the temperature to enhance the diversity is limited due to text degeneration issue, and 2) propose a novel method to improve the diversity while maintaining text quality. We first analyze the effect of increasing the temperature parameter, which is regarded as the LLM's diversity control, on IID hypotheses. Our analysis shows that as temperature rises, diversity and accuracy of hypotheses increase up to a certain point, but this trend saturates due to text degeneration. To generate hypotheses that are more semantically diverse and of higher quality, we propose a novel approach inspired by human inductive reasoning, which we call Mixture of Concepts (MoC). When applied to several inductive reasoning benchmarks, MoC demonstrated significant performance improvements compared to standard IID sampling and other approaches. 

**Abstract (ZH)**: 归纳推理——通过少量观察推断一般规则的过程——是人类智能的基本方面。近期的研究表明，大型语言模型（LLMs）可以通过采样多个关于规则的假设，并选择最能解释观察结果的那个假设来进行归纳推理。然而，由于采用独立同分布（IID）采样方法，常常会产生语义冗余的假设，导致计算资源的巨大浪费。在本文中，我们首先展示了提高温度以增加多样性受到文本退化问题的限制，并提出了一种新方法以在保持文本质量的同时提高多样性。我们首先分析了提高温度参数（视为LLM的多样性控制）对IID假设的影响。我们的分析显示，随着温度的增加，假设的多样性和准确性会在某个点上增加，但由于文本退化，这种趋势会饱和。为了生成更多语义上多样化且高质量的假设，我们提出了一种受人类归纳推理启发的新方法，称为概念混合（MoC）。当应用于多个归纳推理基准时，MoC相较于标准的IID采样和其他方法显示出了显著的性能提升。 

---
# Multiple Mean-Payoff Optimization under Local Stability Constraints 

**Title (ZH)**: 局部稳定性约束下的多目标平均报酬优化 

**Authors**: David Klaška, Antonín Kučera, Vojtěch Kůr, Vít Musil, Vojtěch Řehák  

**Link**: [PDF](https://arxiv.org/pdf/2412.13369)  

**Abstract**: The long-run average payoff per transition (mean payoff) is the main tool for specifying the performance and dependability properties of discrete systems. The problem of constructing a controller (strategy) simultaneously optimizing several mean payoffs has been deeply studied for stochastic and game-theoretic models. One common issue of the constructed controllers is the instability of the mean payoffs, measured by the deviations of the average rewards per transition computed in a finite "window" sliding along a run. Unfortunately, the problem of simultaneously optimizing the mean payoffs under local stability constraints is computationally hard, and the existing works do not provide a practically usable algorithm even for non-stochastic models such as two-player games. In this paper, we design and evaluate the first efficient and scalable solution to this problem applicable to Markov decision processes. 

**Abstract (ZH)**: 离散系统的长期平均转换收益（平均收益）是用于规定系统性能和可靠性的主要工具。针对随机性和博弈论模型中同时优化多个平均收益的控制器（策略）问题已经进行了深入研究。构建出的控制器的一个常见问题是平均收益的不稳定，这可以通过沿运行过程滑动的有限“窗口”计算的每转换平均奖励的偏差来衡量。不幸的是，同时在局部稳定性约束下优化平均收益的问题在计算上是困难的，现有的研究工作甚至在非随机模型如两人博弈中也未提供一个实用的算法。本文设计并评估了第一个适用于马尔可夫决策过程的有效且可扩展的解决方案。 

---
# Quantitative Predictive Monitoring and Control for Safe Human-Machine Interaction 

**Title (ZH)**: 定量预测监控与控制以确保人机交互的安全性 

**Authors**: Shuyang Dong, Meiyi Ma, Josephine Lamp, Sebastian Elbaum, Matthew B. Dwyer, Lu Feng  

**Link**: [PDF](https://arxiv.org/pdf/2412.13365)  

**Abstract**: There is a growing trend toward AI systems interacting with humans to revolutionize a range of application domains such as healthcare and transportation. However, unsafe human-machine interaction can lead to catastrophic failures. We propose a novel approach that predicts future states by accounting for the uncertainty of human interaction, monitors whether predictions satisfy or violate safety requirements, and adapts control actions based on the predictive monitoring results. Specifically, we develop a new quantitative predictive monitor based on Signal Temporal Logic with Uncertainty (STL-U) to compute a robustness degree interval, which indicates the extent to which a sequence of uncertain predictions satisfies or violates an STL-U requirement. We also develop a new loss function to guide the uncertainty calibration of Bayesian deep learning and a new adaptive control method, both of which leverage STL-U quantitative predictive monitoring results. We apply the proposed approach to two case studies: Type 1 Diabetes management and semi-autonomous driving. Experiments show that the proposed approach improves safety and effectiveness in both case studies. 

**Abstract (ZH)**: 随着人工智能系统在人类互动中发挥作用的趋势日益明显，这些系统有望在医疗保健和交通运输等多个应用领域实现革命性变革。然而，不安全的人机互动可能导致灾难性失败。本文提出了一种新的方法，通过考虑人类互动的不确定性来预测未来状态，监控预测是否满足或违反安全要求，并基于预测监控结果调整控制动作。具体而言，我们基于不确定性的信号时序逻辑（STL-U）开发了一种新的定量预测监视器，用于计算鲁棒性度量区间，该区间表明不确定预测序列满足或违反STL-U要求的程度。此外，我们还开发了一种新的损失函数来指导贝叶斯深度学习中的不确定性校准，以及一种新的自适应控制方法，这两种方法均利用STL-U的定量预测监视结果。我们将提出的方法应用于两个案例研究：1型糖尿病管理与半自动驾驶。实验结果表明，所提出的方法在两个案例研究中均提高了安全性和有效性。 

---
# Predictive Probability Density Mapping for Search and Rescue Using An Agent-Based Approach with Sparse Data 

**Title (ZH)**: 基于代理方法的稀疏数据预测概率密度映射在搜救中的应用 

**Authors**: Jan-Hendrik Ewers, David Anderson, Douglas Thomson  

**Link**: [PDF](https://arxiv.org/pdf/2412.13317)  

**Abstract**: Predicting the location where a lost person could be found is crucial for search and rescue operations with limited resources. To improve the precision and efficiency of these predictions, simulated agents can be created to emulate the behavior of the lost person. Within this study, we introduce an innovative agent-based model designed to replicate diverse psychological profiles of lost persons, allowing these agents to navigate real-world landscapes while making decisions autonomously without the need for location-specific training. The probability distribution map depicting the potential location of the lost person emerges through a combination of Monte Carlo simulations and mobility-time-based sampling. Validation of the model is achieved using real-world Search and Rescue data to train a Gaussian Process model. This allows generalization of the data to sample initial starting points for the agents during validation. Comparative analysis with historical data showcases promising outcomes relative to alternative methods. This work introduces a flexible agent that can be employed in search and rescue operations, offering adaptability across various geographical locations. 

**Abstract (ZH)**: 在资源有限的搜救行动中，准确预测失踪人员可能所在的地点至关重要。为了提高预测的精准性和效率，可以通过创建模拟代理来模拟失踪人员的行为。在此研究中，我们提出了一种创新的基于代理的模型，该模型能够模拟多种心理特征，并使这些代理能够在真实世界景观中自主导航，而无需进行特定地理位置的训练。潜在失踪地点的概率分布图通过蒙特卡洛仿真和基于移动时间的采样相结合形成。通过使用实际的搜救数据训练高斯过程模型来进行模型验证，这使得数据能够泛化到验证过程中代理的初始起始点。与历史数据的对比分析展示了该方法相对于其他方法的有希望的结果。这项工作介绍了一种灵活的代理模型，可以在不同的地理区域中应用于搜救行动，提供了跨区域的适应性。 

---
# SafeDrive: Knowledge- and Data-Driven Risk-Sensitive Decision-Making for Autonomous Vehicles with Large Language Models 

**Title (ZH)**: SafeDrive：基于知识和数据的风险敏感决策驱动方法，用于具有大型语言模型的自动驾驶车辆 

**Authors**: Zhiyuan Zhou, Heye Huang, Boqi Li, Shiyue Zhao, Yao Mu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13238)  

**Abstract**: Recent advancements in autonomous vehicles (AVs) use Large Language Models (LLMs) to perform well in normal driving scenarios. However, ensuring safety in dynamic, high-risk environments and managing safety-critical long-tail events remain significant challenges. To address these issues, we propose SafeDrive, a knowledge- and data-driven risk-sensitive decision-making framework to enhance AV safety and adaptability. The proposed framework introduces a modular system comprising: (1) a Risk Module for quantifying multi-factor coupled risks involving driver, vehicle, and road interactions; (2) a Memory Module for storing and retrieving typical scenarios to improve adaptability; (3) a LLM-powered Reasoning Module for context-aware safety decision-making; and (4) a Reflection Module for refining decisions through iterative learning. By integrating knowledge-driven insights with adaptive learning mechanisms, the framework ensures robust decision-making under uncertain conditions. Extensive evaluations on real-world traffic datasets, including highways (HighD), intersections (InD), and roundabouts (RounD), validate the framework's ability to enhance decision-making safety (achieving a 100% safety rate), replicate human-like driving behaviors (with decision alignment exceeding 85%), and adapt effectively to unpredictable scenarios. SafeDrive establishes a novel paradigm for integrating knowledge- and data-driven methods, highlighting significant potential to improve safety and adaptability of autonomous driving in high-risk traffic scenarios. 

**Abstract (ZH)**: 近年来，无人车（AVs）利用大型语言模型（LLMs）在常规驾驶场景中表现出色。然而，在动态且高风险的环境中确保安全以及管理安全关键的长尾事件仍是一项重大挑战。为应对这些挑战，我们提出了一种基于知识和数据的风险敏感型决策框架SafeDrive，以提升无人车的安全性和适应性。所提出的框架包含以下几个模块：（1）风险模块，用于量化涉及驾驶员、车辆和道路交互的多因素耦合风险；（2）记忆模块，用于存储和检索典型场景以提高适应性；（3）由大型语言模型驱动的推理模块，用于情境感知安全决策；以及（4）反思模块，通过迭代学习来改进决策。通过将知识驱动的洞察与适应性学习机制相结合，该框架能够在不确定性条件下确保稳健的决策过程。在实际道路交通数据集（包括高速公路HighD、交叉路口InD和环岛RounD）上的广泛评估证明了该框架在提升决策安全性（实现100%的安全率）、模仿人类驾驶行为（决策对齐超过85%）以及有效应对不可预测场景方面的能力。SafeDrive 建立了一种将知识驱动和数据驱动方法相结合的新范式，突显了其在提高高风险交通安全性和适应性方面的巨大潜力。 

---
# Logic-Constrained Shortest Paths for Flight Planning 

**Title (ZH)**: 符合学术规范的翻译为：基于逻辑约束的飞行航线最短路径规划 

**Authors**: Ricardo Euler, Pedro Maristany de las Casas, Ralf Borndörfer  

**Link**: [PDF](https://arxiv.org/pdf/2412.13235)  

**Abstract**: The Logic-Constrained Shortest Path Problem (LCSP) combines a one-to-one shortest path problem with satisfiability constraints imposed on the routing graph. This setting arises in flight planning, where air traffic control (ATC) authorities are enforcing a set of traffic flow restrictions (TFRs) on aircraft routes in order to increase safety and throughput. We propose a new branch and bound-based algorithm for the LCSP.
The resulting algorithm has three main degrees of freedom: the node selection rule, the branching rule and the conflict. While node selection and branching rules have been long studied in the MIP and SAT communities, most of them cannot be applied out of the box for the LCSP. We review the existing literature and develop tailored variants of the most prominent rules. The conflict, the set of variables to which the branching rule is applied, is unique to the LCSP. We analyze its theoretical impact on the B&B algorithm.
In the second part of the paper, we show how to model the Flight Planning Problem with TFRs as an LCSP and solve it using the branch and bound algorithm. We demonstrate the algorithm's efficiency on a dataset consisting of a global flight graph and a set of around 20000 real TFRs obtained from our industry partner Lufthansa Systems GmbH. We make this dataset publicly available. Finally, we conduct an empirical in-depth analysis of node selection rules, branching rules and conflicts. Carefully choosing an appropriate combination yields an improvement of an order of magnitude compared to an uninformed choice. 

**Abstract (ZH)**: 约束逻辑路径问题（LCSP）结合了一对一最短路径问题与施加在路由图上的满足性约束。这种设置出现在航班规划中，空中交通管制（ATC）机构在为提高安全性与通流量而对航空器航线施加一套流量控制限制（TFRs）时就会出现这种情况。我们提出了一种新的基于分支定界算法的新方法来解决LCSP问题。

该算法具有三个主要的自由度：节点选择规则、分支规则和冲突。虽然节点选择和分支规则在混合整数规划（MIP）和可满足性问题（SAT）社区中已有长期研究，但它们大多数情况下不能直接应用于LCSP。我们回顾了现有文献，并开发了针对这些最突出规则的定制变体。冲突是应用于分支规则的一组变量，这是LCSP特有的。我们分析了它的理论影响对分支定界算法的影响。

在论文的第二部分，我们展示了如何将带有TFRs的航班规划问题建模为LCSP，并使用分支定界算法解决这个问题。我们使用一个包含全球航班图和来自我们行业合作伙伴Lufthansa Systems GmbH的约20000个真实TFR的数据集，展示了该算法的效率。我们已经将这个数据集公开。最后，我们进行了关于节点选择规则、分支规则和冲突的详尽实证分析。仔细选择适当的组合可以比随机选择带来数量级上的改进。 

---
# Learning from Massive Human Videos for Universal Humanoid Pose Control 

**Title (ZH)**: 从海量人类视频中学习以实现通用类人姿态控制 

**Authors**: Jiageng Mao, Siheng Zhao, Siqi Song, Tianheng Shi, Junjie Ye, Mingtong Zhang, Haoran Geng, Jitendra Malik, Vitor Guizilini, Yue Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14172)  

**Abstract**: Scalable learning of humanoid robots is crucial for their deployment in real-world applications. While traditional approaches primarily rely on reinforcement learning or teleoperation to achieve whole-body control, they are often limited by the diversity of simulated environments and the high costs of demonstration collection. In contrast, human videos are ubiquitous and present an untapped source of semantic and motion information that could significantly enhance the generalization capabilities of humanoid robots. This paper introduces Humanoid-X, a large-scale dataset of over 20 million humanoid robot poses with corresponding text-based motion descriptions, designed to leverage this abundant data. Humanoid-X is curated through a comprehensive pipeline: data mining from the Internet, video caption generation, motion retargeting of humans to humanoid robots, and policy learning for real-world deployment. With Humanoid-X, we further train a large humanoid model, UH-1, which takes text instructions as input and outputs corresponding actions to control a humanoid robot. Extensive simulated and real-world experiments validate that our scalable training approach leads to superior generalization in text-based humanoid control, marking a significant step toward adaptable, real-world-ready humanoid robots. 

**Abstract (ZH)**: 人类机器人的可扩展学习对于其实现实际应用场景中的应用至关重要。传统的方法主要依赖强化学习或远程操作来实现全身控制，但这些方法往往受限于模拟环境的多样性以及动作示范收集的高成本。相比之下，人类视频无处不在，提供了一个未被充分利用的信息源，包括语义和运动信息，这些信息能够显著提升人类机器人的泛化能力。本文介绍了Humanoid-X，这是一个包含超过2000万个人类机器人姿态及其对应文本运动描述的大规模数据集，旨在利用这些丰富的数据。Humanoid-X通过一个全面的流程进行整理：从互联网中进行数据挖掘、生成视频字幕、将人类运动重新目标化到人类机器人上、以及学习策略以适应实际应用。借助Humanoid-X，我们进一步训练了一个大规模的人类机器人模型UH-1，该模型接收文本指令作为输入，输出相应的动作来控制人类机器人。广泛的模拟和实际实验验证了我们可扩展的训练方法在基于文本的人类机器人控制中的优越泛化能力，标志着可适应的实际应用中可准备的人类机器人的一个关键进步。 

---
# E-CAR: Efficient Continuous Autoregressive Image Generation via Multistage Modeling 

**Title (ZH)**: E-CAR：基于多阶段建模的高效连续自回归图像生成 

**Authors**: Zhihang Yuan, Yuzhang Shang, Hanling Zhang, Tongcheng Fang, Rui Xie, Bingxin Xu, Yan Yan, Shengen Yan, Guohao Dai, Yu Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14170)  

**Abstract**: Recent advances in autoregressive (AR) models with continuous tokens for image generation show promising results by eliminating the need for discrete tokenization. However, these models face efficiency challenges due to their sequential token generation nature and reliance on computationally intensive diffusion-based sampling. We present ECAR (Efficient Continuous Auto-Regressive Image Generation via Multistage Modeling), an approach that addresses these limitations through two intertwined innovations: (1) a stage-wise continuous token generation strategy that reduces computational complexity and provides progressively refined token maps as hierarchical conditions, and (2) a multistage flow-based distribution modeling method that transforms only partial-denoised distributions at each stage comparing to complete denoising in normal diffusion models. Holistically, ECAR operates by generating tokens at increasing resolutions while simultaneously denoising the image at each stage. This design not only reduces token-to-image transformation cost by a factor of the stage number but also enables parallel processing at the token level. Our approach not only enhances computational efficiency but also aligns naturally with image generation principles by operating in continuous token space and following a hierarchical generation process from coarse to fine details. Experimental results demonstrate that ECAR achieves comparable image quality to DiT Peebles & Xie [2023] while requiring 10$\times$ FLOPs reduction and 5$\times$ speedup to generate a 256$\times$256 image. 

**Abstract (ZH)**: 近年来，基于连续标记的自回归（AR）模型在图像生成领域取得了引人注目的进展，通过消除离散标记化的需求展现了巨大的潜力。然而，这些模型由于其顺序生成标记的性质以及依赖于计算密集型的扩散采样方法而面临效率挑战。我们提出了一种方法——ECAR（Efficient Continuous Auto-Regressive Image Generation via Multistage Modeling），该方法通过两种相互交织的创新来解决这些限制：（1）逐阶段的连续标记生成策略，降低了计算复杂性，并且提供了逐级细化的标记图作为层次条件；（2）多阶段基于流的分布建模方法，在每个阶段仅对部分正则化分布进行转换，而不是像正常扩散模型那样完全正则化。总体而言，ECAR 通过逐步生成高分辨率的标记并在每个阶段同时去噪图像来运行。这种设计不仅可以通过阶段数量来减少标记到图像转换的成本，还能够在标记级别实现并行处理。我们的方法不仅提高了计算效率，同时也自然地与图像生成原理相吻合，在连续标记空间操作，并且遵循从粗到细的层次生成过程。实验结果显示，ECAR 在生成 256x256 图像时，能够比 DiT Peebles & Xie [2023] 方法实现 10 倍的 FLOPs 减少和 5 倍的速度提升，同时保持相似的图像质量。 

---
# VideoDPO: Omni-Preference Alignment for Video Diffusion Generation 

**Title (ZH)**: VideoDPO：面向视频扩散生成的整体偏好对齐 

**Authors**: Runtao Liu, Haoyu Wu, Zheng Ziqiang, Chen Wei, Yingqing He, Renjie Pi, Qifeng Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.14167)  

**Abstract**: Recent progress in generative diffusion models has greatly advanced text-to-video generation. While text-to-video models trained on large-scale, diverse datasets can produce varied outputs, these generations often deviate from user preferences, highlighting the need for preference alignment on pre-trained models. Although Direct Preference Optimization (DPO) has demonstrated significant improvements in language and image generation, we pioneer its adaptation to video diffusion models and propose a VideoDPO pipeline by making several key adjustments. Unlike previous image alignment methods that focus solely on either (i) visual quality or (ii) semantic alignment between text and videos, we comprehensively consider both dimensions and construct a preference score accordingly, which we term the OmniScore. We design a pipeline to automatically collect preference pair data based on the proposed OmniScore and discover that re-weighting these pairs based on the score significantly impacts overall preference alignment. Our experiments demonstrate substantial improvements in both visual quality and semantic alignment, ensuring that no preference aspect is neglected. Code and data will be shared at this https URL. 

**Abstract (ZH)**: 近年来，生成性扩散模型的进步极大地推动了从文本到视频的生成技术。虽然在大规模和多样化数据集上训练的文本到视频模型能够生成多样化的输出，但这些生成结果往往偏离用户偏好，这强调了在预训练模型上进行偏好对齐的重要性。尽管直接偏好优化（DPO）在语言和图像生成方面已经展示了显著的改进，但我们首先将其适应到视频扩散模型，并通过做出几个关键调整提出了一个VideoDPO流程。与以往仅专注于（i）视觉质量或（ii）文本和视频语义对齐的图像对齐方法不同，我们全面考虑了这两个维度，并据此构建了一个偏好分数，我们称之为全维度分数（OmniScore）。我们设计了一个流程来自动收集基于提出的OmniScore的偏好对数据，并发现基于评分重新加权这些数据对总体偏好对齐有着显著影响。我们的实验表明，在视觉质量和语义对齐方面都取得了显著改进，确保没有忽略任何偏好维度。相关代码和数据将在此链接中分享：https://your-link-here.com。 

---
# AKiRa: Augmentation Kit on Rays for optical video generation 

**Title (ZH)**: AKiRa：用于光学视频生成的射线增强套件 

**Authors**: Xi Wang, Robin Courant, Marc Christie, Vicky Kalogeiton  

**Link**: [PDF](https://arxiv.org/pdf/2412.14158)  

**Abstract**: Recent advances in text-conditioned video diffusion have greatly improved video quality. However, these methods offer limited or sometimes no control to users on camera aspects, including dynamic camera motion, zoom, distorted lens and focus shifts. These motion and optical aspects are crucial for adding controllability and cinematic elements to generation frameworks, ultimately resulting in visual content that draws focus, enhances mood, and guides emotions according to filmmakers' controls. In this paper, we aim to close the gap between controllable video generation and camera optics. To achieve this, we propose AKiRa (Augmentation Kit on Rays), a novel augmentation framework that builds and trains a camera adapter with a complex camera model over an existing video generation backbone. It enables fine-tuned control over camera motion as well as complex optical parameters (focal length, distortion, aperture) to achieve cinematic effects such as zoom, fisheye effect, and bokeh. Extensive experiments demonstrate AKiRa's effectiveness in combining and composing camera optics while outperforming all state-of-the-art methods. This work sets a new landmark in controlled and optically enhanced video generation, paving the way for future optical video generation methods. 

**Abstract (ZH)**: 近年来，基于文本条件的视频扩散方法显著提高了视频质量。然而，这些方法在用户对摄像头方面（包括动态摄像头运动、变焦、畸变镜头和对焦变化）的控制上有限或几乎没有提供控制能力。这些运动和光学方面对于在生成框架中增加可控性和电影元素至关重要，最终能够生成能够引导观众注意力、增强情绪和按照制片人控制来引导情感的视觉内容。在本文中，我们旨在弥合可控视频生成与摄像光学之间的差距。为实现这一目标，我们提出了AKiRa（光线增强工具包），这是一种新型增强框架，它在现有的视频生成主干上构建并训练了一个复杂的摄像机适配器。它能够对摄像头运动进行精细调整，并控制复杂的光学参数（焦距、畸变、光圈），从而实现诸如变焦、鱼眼效果和散景等电影效果。广泛的实验表明，AKiRa 在结合和组合摄像光学方面表现出色，并且在所有最先进的方法中性能更优。这项工作为受控制且光学增强的视频生成树立了新的标杆，为未来的光学视频生成方法奠定了基础。 

---
# GLIDER: Grading LLM Interactions and Decisions using Explainable Ranking 

**Title (ZH)**: GLIDER：使用可解释排名评估LLM交互和决策 

**Authors**: Darshan Deshpande, Selvan Sunitha Ravi, Sky CH-Wang, Bartosz Mielczarek, Anand Kannappan, Rebecca Qian  

**Link**: [PDF](https://arxiv.org/pdf/2412.14140)  

**Abstract**: The LLM-as-judge paradigm is increasingly being adopted for automated evaluation of model outputs. While LLM judges have shown promise on constrained evaluation tasks, closed source LLMs display critical shortcomings when deployed in real world applications due to challenges of fine grained metrics and explainability, while task specific evaluation models lack cross-domain generalization. We introduce GLIDER, a powerful 3B evaluator LLM that can score any text input and associated context on arbitrary user defined criteria. GLIDER shows higher Pearson's correlation than GPT-4o on FLASK and greatly outperforms prior evaluation models, achieving comparable performance to LLMs 17x its size. GLIDER supports fine-grained scoring, multilingual reasoning, span highlighting and was trained on 685 domains and 183 criteria. Extensive qualitative analysis shows that GLIDER scores are highly correlated with human judgments, with 91.3% human agreement. We have open-sourced GLIDER to facilitate future research. 

**Abstract (ZH)**: 将下面的论文内容或标题翻译成中文，要符合学术规范：

大规模语言模型（LLM）作为仲裁者的方法越来越被用于自动评估模型输出。虽然LLM仲裁者在受限评估任务中表现出一定的潜力，但闭源LLM在实际应用中部署时显示出关键缺点，主要是由于细粒度指标和可解释性方面的挑战，而任务特定的评估模型缺乏跨域泛化能力。我们引入了GLIDER，一个强大且拥有30亿参数的评估LLM，它可以针对任意用户定义的标准对任何文本输入及其相关上下文进行评分。GLIDER在FLASK上的皮尔逊相关系数高于GPT-4o，并大幅优于先前的评估模型，其性能相当于比自身大17倍的LLM。GLIDER支持细粒度评分、多语言推理、片段高亮，并且是基于685个领域和183个标准进行训练的。广泛的定性分析表明，GLIDER的评分与人类判断高度相关，91.3%的评分与人类一致。我们已开源GLIDER，以促进未来的研究。 

---
# Design choices made by LLM-based test generators prevent them from finding bugs 

**Title (ZH)**: 基于LLM的测试生成器的设计选择限制了它们发现缺陷的能力 

**Authors**: Noble Saji Mathews, Meiyappan Nagappan  

**Link**: [PDF](https://arxiv.org/pdf/2412.14137)  

**Abstract**: There is an increasing amount of research and commercial tools for automated test case generation using Large Language Models (LLMs). This paper critically examines whether recent LLM-based test generation tools, such as Codium CoverAgent and CoverUp, can effectively find bugs or unintentionally validate faulty code. Considering bugs are only exposed by failing test cases, we explore the question: can these tools truly achieve the intended objectives of software testing when their test oracles are designed to pass? Using real human-written buggy code as input, we evaluate these tools, showing how LLM-generated tests can fail to detect bugs and, more alarmingly, how their design can worsen the situation by validating bugs in the generated test suite and rejecting bug-revealing tests. These findings raise important questions about the validity of the design behind LLM-based test generation tools and their impact on software quality and test suite reliability. 

**Abstract (ZH)**: 近年来，利用大规模语言模型（LLMs）自动生成测试用例的研究和商业工具不断增加。本文批判性地探讨了诸如Codium CoverAgent和CoverUp等基于LLM的测试生成工具是否能够有效发现错误，或是无意中验证了错误代码。鉴于错误只有通过失败的测试用例才能暴露出来，我们探讨了这样一个问题：当这些工具将测试Oracle（即测试真相来源）设计为通过时，它们是否真的能够实现软件测试的目的？利用真实的人工编写的错误代码作为输入，我们评估了这些工具，展示了LLM生成的测试如何未能检测到错误，更令人担忧的是，它们的设计如何加剧了问题，通过在生成的测试集中验证错误，同时拒绝能揭示错误的测试。这些发现引起了对基于LLM的测试生成工具设计有效性的质疑，并对其对软件质量和测试套件可靠性的潜在影响提出了重要问题。 

---
# Adaptive Concept Bottleneck for Foundation Models Under Distribution Shifts 

**Title (ZH)**: 适应性概念瓶颈：基础模型在分布偏移下的应对策略 

**Authors**: Jihye Choi, Jayaram Raghuram, Yixuan Li, Somesh Jha  

**Link**: [PDF](https://arxiv.org/pdf/2412.14097)  

**Abstract**: Advancements in foundation models (FMs) have led to a paradigm shift in machine learning. The rich, expressive feature representations from these pre-trained, large-scale FMs are leveraged for multiple downstream tasks, usually via lightweight fine-tuning of a shallow fully-connected network following the representation. However, the non-interpretable, black-box nature of this prediction pipeline can be a challenge, especially in critical domains such as healthcare, finance, and security. In this paper, we explore the potential of Concept Bottleneck Models (CBMs) for transforming complex, non-interpretable foundation models into interpretable decision-making pipelines using high-level concept vectors. Specifically, we focus on the test-time deployment of such an interpretable CBM pipeline "in the wild", where the input distribution often shifts from the original training distribution. We first identify the potential failure modes of such a pipeline under different types of distribution shifts. Then we propose an adaptive concept bottleneck framework to address these failure modes, that dynamically adapts the concept-vector bank and the prediction layer based solely on unlabeled data from the target domain, without access to the source (training) dataset. Empirical evaluations with various real-world distribution shifts show that our adaptation method produces concept-based interpretations better aligned with the test data and boosts post-deployment accuracy by up to 28%, aligning the CBM performance with that of non-interpretable classification. 

**Abstract (ZH)**: 基础模型（FMs）的进步已经引发了机器学习范式的转变。这些预先训练的、大规模的基础模型提供了丰富的、富有表现力的特征表示，这些表示通常通过轻量级的浅级全连接网络的微调，应用于多个下游任务。然而，这种预测管道的非解释性和黑盒性质在关键领域，如医疗保健、金融和安全中可能会成为一个挑战。在本文中，我们探讨了概念瓶颈模型（CBMs）的潜力，通过使用高级概念向量将复杂的、非解释性的基础模型转换为解释性的决策管道。具体而言，我们关注这类可解释的CBM管道在实际应用中的测试时部署问题，在这种情况下，输入分布通常与原始训练分布不同。首先，我们识别了在不同类型的分布变化下此类管道可能出现的故障模式。随后，我们提出了一种适应性概念瓶颈框架来解决这些故障模式，该框架可以根据目标领域中的未标注数据动态调整概念向量库和预测层，而无需访问源（训练）数据集。通过各种真实世界的分布变化进行的经验评估表明，我们的适应性方法能产生更符合测试数据的概念解释，并在部署后将准确率提升最高达28%，使CBM的表现与非解释性分类相当。 

---
# SEKE: Specialised Experts for Keyword Extraction 

**Title (ZH)**: SEKE：专域专家关键词提取 

**Authors**: Matej Martinc, Hanh Thi Hong Tran, Senja Pollak, Boshko Koloski  

**Link**: [PDF](https://arxiv.org/pdf/2412.14087)  

**Abstract**: Keyword extraction involves identifying the most descriptive words in a document, allowing automatic categorisation and summarisation of large quantities of diverse textual data. Relying on the insight that real-world keyword detection often requires handling of diverse content, we propose a novel supervised keyword extraction approach based on the mixture of experts (MoE) technique. MoE uses a learnable routing sub-network to direct information to specialised experts, allowing them to specialize in distinct regions of the input space. SEKE, a mixture of Specialised Experts for supervised Keyword Extraction, uses DeBERTa as the backbone model and builds on the MoE framework, where experts attend to each token, by integrating it with a recurrent neural network (RNN), to allow successful extraction even on smaller corpora, where specialisation is harder due to lack of training data. The MoE framework also provides an insight into inner workings of individual experts, enhancing the explainability of the approach. We benchmark SEKE on multiple English datasets, achieving state-of-the-art performance compared to strong supervised and unsupervised baselines. Our analysis reveals that depending on data size and type, experts specialize in distinct syntactic and semantic components, such as punctuation, stopwords, parts-of-speech, or named entities. Code is available at: this https URL 

**Abstract (ZH)**: 关键词抽取涉及识别文档中最具描述性的词，从而实现大规模异质文本数据的自动分类和总结。鉴于现实中关键词检测需要处理多样内容的见解，我们提出了一种基于专家混合模型（Mixture of Experts, MoE）的新监督关键词抽取方法。MoE 使用可学习的路由子网络来指导信息流向专门化的专家，使他们在输入空间的不同区域实现专门化。SEKE（基于专门化专家的监督关键词抽取）采用 DeBERTa 作为骨干模型，并在其基础上构建 MoE 框架，通过将递归神经网络（RNN）与专家机制相结合，即使在缺乏训练数据导致专门化较为困难的较小语料库中也能实现成功的关键词抽取。MoE 框架还提供了一种深入了解每个专家内部工作机制的方法，增强了该方法的可解释性。我们在多个英文数据集上对 SEKE 进行基准测试，其性能优于强大的监督和非监督基线。我们的分析表明，根据数据量和类型的不同，专家会在不同的语法和语义成分上专门化，例如标点符号、停用词、词性或命名实体。相关代码可在此链接获取：this https URL 

---
# Future Research Avenues for Artificial Intelligence in Digital Gaming: An Exploratory Report 

**Title (ZH)**: 人工智能在数字游戏领域的未来研究方向：一项探索性报告 

**Authors**: Markus Dablander  

**Link**: [PDF](https://arxiv.org/pdf/2412.14085)  

**Abstract**: Video games are a natural and synergistic application domain for artificial intelligence (AI) systems, offering both the potential to enhance player experience and immersion, as well as providing valuable benchmarks and virtual environments to advance AI technologies in general. This report presents a high-level overview of five promising research pathways for applying state-of-the-art AI methods, particularly deep learning, to digital gaming within the context of the current research landscape. The objective of this work is to outline a curated, non-exhaustive list of encouraging research directions at the intersection of AI and video games that may serve to inspire more rigorous and comprehensive research efforts in the future. We discuss (i) investigating large language models as core engines for game agent modelling, (ii) using neural cellular automata for procedural game content generation, (iii) accelerating computationally expensive in-game simulations via deep surrogate modelling, (iv) leveraging self-supervised learning to obtain useful video game state embeddings, and (v) training generative models of interactive worlds using unlabelled video data. We also briefly address current technical challenges associated with the integration of advanced deep learning systems into video game development, and indicate key areas where further progress is likely to be beneficial. 

**Abstract (ZH)**: 视频游戏是人工智能（AI）系统的一个自然且协同的应用领域，既有可能提升玩家体验和沉浸感，又能为推进AI技术的一般发展提供有价值的基准和虚拟环境。本报告对现有研究背景下，将最先进的人工智能方法，特别是深度学习，应用于数字游戏的研究路径进行了高层次的综述。本文旨在概述一个精选且非详尽的人工智能与视频游戏交叉领域的有希望的研究方向，这些方向旨在激发未来更为严谨和全面的研究努力。我们讨论了以下五个方面的研究途径：(i) 探索大型语言模型作为游戏代理建模的核心引擎；(ii) 使用神经细胞自动机进行程序化游戏内容生成；(iii) 通过深度代理模型加速昂贵的基于游戏的计算模拟；(iv) 利用半监督学习获取有用的游戏状态嵌入；(v) 使用未标记的视频数据训练交互世界的生成模型。我们还将简要讨论将高级深度学习系统集成到视频游戏开发过程中的当前技术挑战，并指出进一步进展可能受益的关键领域。 

---
# Dialogue with the Machine and Dialogue with the Art World: Evaluating Generative AI for Culturally-Situated Creativity 

**Title (ZH)**: 与机器的对话与与艺术界的对话：评估生成式AI在文化情境创意中的应用 

**Authors**: Rida Qadri, Piotr Mirowski, Aroussiak Gabriellan, Farbod Mehr, Huma Gupta, Pamela Karimi, Remi Denton  

**Link**: [PDF](https://arxiv.org/pdf/2412.14077)  

**Abstract**: This paper proposes dialogue as a method for evaluating generative AI tools for culturally-situated creative practice, that recognizes the socially situated nature of art. Drawing on sociologist Howard Becker's concept of Art Worlds, this method expands the scope of traditional AI and creativity evaluations beyond benchmarks, user studies with crowd-workers, or focus groups conducted with artists. Our method involves two mutually informed dialogues: 1) 'dialogues with art worlds' placing artists in conversation with experts such as art historians, curators, and archivists, and 2)'dialogues with the machine,' facilitated through structured artist- and critic-led experimentation with state-of-the-art generative AI tools. We demonstrate the value of this method through a case study with artists and experts steeped in non-western art worlds, specifically the Persian Gulf. We trace how these dialogues help create culturally rich and situated forms of evaluation for representational possibilities of generative AI that mimic the reception of generative artwork in the broader art ecosystem. Putting artists in conversation with commentators also allow artists to shift their use of the tools to respond to their cultural and creative context. Our study can provide generative AI researchers an understanding of the complex dynamics of technology, human creativity and the socio-politics of art worlds, to build more inclusive machines for diverse art worlds. 

**Abstract (ZH)**: 本文提出了一种基于对话的方法，用于评估适应文化情境的创意实践中的生成型人工智能工具，这一方法认可艺术的社会情境本质。本文基于社会学家Howard Becker提出的“艺术世界”概念，将传统的人工智能与创造力评估范围扩展到超越基准测试、众包用户研究或艺术家参与的重点小组之外。该方法包括两个相互启发的对话环节：1）“与艺术世界对话”，即艺术家与艺术史学家、策展人和档案保管员等专家进行交流；2）“与机器对话”，通过结构化的艺术家和评论家引导的实验，利用最先进的生成型人工智能工具进行探索。我们通过一个以非西方艺术世界（具体而言是波斯湾）为背景的研究案例，展示了该方法的价值。我们探讨了这些对话如何帮助创建一种文化丰富且情境化的评估形式，以模拟生成艺术作品在更广泛艺术生态系统中的接受情况。将艺术家与评论者进行交流，也使艺术家能够根据其文化与创意背景调整工具的使用方式。我们的研究为生成型人工智能研究人员提供了理解技术、人类创造力以及艺术世界社会政治动态的复杂关系的途径，从而为多样化的艺术世界构建更加包容的机器。 

---
# A Computationally Grounded Framework for Cognitive Attitudes (extended version) 

**Title (ZH)**: 基于计算的认知态度框架（扩展版） 

**Authors**: Tiago de Lima, Emiliano Lorini, Elise Perrotin, François Schwarzentruber  

**Link**: [PDF](https://arxiv.org/pdf/2412.14073)  

**Abstract**: We introduce a novel language for reasoning about agents' cognitive attitudes of both epistemic and motivational type. We interpret it by means of a computationally grounded semantics using belief bases. Our language includes five types of modal operators for implicit belief, complete attraction, complete repulsion, realistic attraction and realistic repulsion. We give an axiomatization and show that our operators are not mutually expressible and that they can be combined to represent a large variety of psychological concepts including ambivalence, indifference, being motivated, being demotivated and preference. We present a dynamic extension of the language that supports reasoning about the effects of belief change operations. Finally, we provide a succinct formulation of model checking for our languages and a PSPACE model checking algorithm relying on a reduction into TQBF. We present some experimental results for the implemented algorithm on computation time in a concrete example. 

**Abstract (ZH)**: 我们介绍了一种新的语言，用于推理代理的知识性和动机性认知态度。我们通过基于计算意义的语义学解释了该语言，使用信念集进行解释。该语言包括五种模态操作符，分别用于隐含信念、完全吸引、完全排斥、实际吸引和实际排斥。我们给出了一个公理化体系，并证明了这些操作符之间不能互相表达，而且可以组合起来表示多种心理概念，包括矛盾、无动于衷、动机、去动机以及偏好。我们还提出了该语言的一个动态扩展，以支持信念变化操作效果的推理。最后，我们提供了该语言模型检查的简洁表述，并提供了一种基于TQBF归约的PSPACE模型检查算法。我们还在一个具体的例子中实验了实现算法的运行时间。 

---
# Rango: Adaptive Retrieval-Augmented Proving for Automated Software Verification 

**Title (ZH)**: 朗格诺姆（Rango）：自适应检索增强证明在自动化软件验证中的应用 

**Authors**: Kyle Thompson, Nuno Saavedra, Pedro Carrott, Kevin Fisher, Alex Sanchez-Stern, Yuriy Brun, João F. Ferreira, Sorin Lerner, Emily First  

**Link**: [PDF](https://arxiv.org/pdf/2412.14063)  

**Abstract**: Formal verification using proof assistants, such as Coq, enables the creation of high-quality software. However, the verification process requires significant expertise and manual effort to write proofs. Recent work has explored automating proof synthesis using machine learning and large language models (LLMs). This work has shown that identifying relevant premises, such as lemmas and definitions, can aid synthesis. We present Rango, a fully automated proof synthesis tool for Coq that automatically identifies relevant premises and also similar proofs from the current project and uses them during synthesis. Rango uses retrieval augmentation at every step of the proof to automatically determine which proofs and premises to include in the context of its fine-tuned LLM. In this way, Rango adapts to the project and to the evolving state of the proof. We create a new dataset, CoqStoq, of 2,226 open-source Coq projects and 196,929 theorems from GitHub, which includes both training data and a curated evaluation benchmark of well-maintained projects. On this benchmark, Rango synthesizes proofs for 32.0% of the theorems, which is 29% more theorems than the prior state-of-the-art tool Tactician. Our evaluation also shows that Rango adding relevant proofs to its context leads to a 47% increase in the number of theorems proven. 

**Abstract (ZH)**: 使用如Coq等证明辅助器进行形式化验证能够创造出高质量的软件。然而，验证过程需要大量的专业知识和手动努力来写证明。近期的工作探究了利用机器学习和大规模语言模型（LLMs）自动合成证明的可能性。这些工作表明，识别相关的前提条件，如引理和定义，能够帮助合成证明。我们提出了一种名为Rango的全自动Coq证明合成工具，该工具能够自动识别相关的前提条件，并在当前项目中查找相似的证明，并在合成过程中使用它们。Rango在证明的每一步都使用检索增强方法，自动确定哪些证明和前提条件应包含在其微调后的LLM上下文中。通过这种方式，Rango能够适应特定项目并适应证明的不断变化状态。我们创建了一个新的数据集CoqStoq，其中包括2,226个开源Coq项目和196,929个来自GitHub的定理，并包含训练数据和一个精选的基准评估集。在该基准上，Rango合成了32.0%的定理，比前最先进的工具Tactician多合成29%的定理。此外，我们的评估还表明，Rango将其上下文中的相关证明添加到其中能够增加47%的定理证明数量。 

---
# A Review of Multimodal Explainable Artificial Intelligence: Past, Present and Future 

**Title (ZH)**: 多模态可解释人工智能的综述：过去、现在和未来 

**Authors**: Shilin Sun, Wenbin An, Feng Tian, Fang Nan, Qidong Liu, Jun Liu, Nazaraf Shah, Ping Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.14056)  

**Abstract**: Artificial intelligence (AI) has rapidly developed through advancements in computational power and the growth of massive datasets. However, this progress has also heightened challenges in interpreting the "black-box" nature of AI models. To address these concerns, eXplainable AI (XAI) has emerged with a focus on transparency and interpretability to enhance human understanding and trust in AI decision-making processes. In the context of multimodal data fusion and complex reasoning scenarios, the proposal of Multimodal eXplainable AI (MXAI) integrates multiple modalities for prediction and explanation tasks. Meanwhile, the advent of Large Language Models (LLMs) has led to remarkable breakthroughs in natural language processing, yet their complexity has further exacerbated the issue of MXAI. To gain key insights into the development of MXAI methods and provide crucial guidance for building more transparent, fair, and trustworthy AI systems, we review the MXAI methods from a historical perspective and categorize them across four eras: traditional machine learning, deep learning, discriminative foundation models, and generative LLMs. We also review evaluation metrics and datasets used in MXAI research, concluding with a discussion of future challenges and directions. A project related to this review has been created at this https URL. 

**Abstract (ZH)**: 人工智能（AI）通过计算能力的进步和大量数据集的增长得到了迅猛发展。然而，这一进步也加剧了对AI模型“黑箱”性质的理解挑战。为应对这些挑战，可解释人工智能（XAI）应运而生，专注于透明度和可解释性，以提升人类对AI决策过程的理解和信任。在多模态数据融合和复杂推理场景下，多模态可解释人工智能（MXAI）方法通过整合多种模态信息来执行预测和解释任务。与此同时，大型语言模型（LLMs）的出现为其在自然语言处理领域的突破性进展奠定了基础，但它们的复杂性进一步加剧了MXAI的问题。为了深入了解MXAI方法的发展，并为构建更透明、公平和值得信赖的AI系统提供关键指导，我们从历史角度回顾了MXAI方法，并将其分为四个阶段：传统机器学习、深度学习、区分性基础模型和生成型LLMs。我们还回顾了MXAI研究中使用的评估指标和数据集，并讨论了未来面临的挑战和方向。与此回顾相关的项目可在以下链接找到：[填写完整URL] 

---
# Digestion Algorithm in Hierarchical Symbolic Forests: A Fast Text Normalization Algorithm and Semantic Parsing Framework for Specific Scenarios and Lightweight Deployment 

**Title (ZH)**: 层次符号森林中的消化算法：一种适用于特定场景且易于部署的快速文本规范化算法及语义解析框架 

**Authors**: Kevin You  

**Link**: [PDF](https://arxiv.org/pdf/2412.14054)  

**Abstract**: Text Normalization and Semantic Parsing have numerous applications in natural language processing, such as natural language programming, paraphrasing, data augmentation, constructing expert systems, text matching, and more. Despite the prominent achievements of deep learning in Large Language Models (LLMs), the interpretability of neural network architectures is still poor, which affects their credibility and hence limits the deployments of risk-sensitive scenarios. In certain scenario-specific domains with scarce data, rapidly obtaining a large number of supervised learning labels is challenging, and the workload of manually labeling data would be enormous. Catastrophic forgetting in neural networks further leads to low data utilization rates. In situations where swift responses are vital, the density of the model makes local deployment difficult and the response time long, which is not conducive to local applications of these fields. Inspired by the multiplication rule, a principle of combinatorial mathematics, and human thinking patterns, a multilayer framework along with its algorithm, the Digestion Algorithm in Hierarchical Symbolic Forests (DAHSF), is proposed to address these above issues, combining text normalization and semantic parsing workflows. The Chinese Scripting Language "Fire Bunny Intelligent Development Platform V2.0" is an important test and application of the technology discussed in this paper. DAHSF can run locally in scenario-specific domains on little datasets, with model size and memory usage optimized by at least two orders of magnitude, thus improving the execution speed, and possessing a promising optimization outlook. 

**Abstract (ZH)**: 文本规范化和语义解析在自然语言处理中有广泛的应用，例如自然语言编程、同义句转换、数据扩充、构建专家系统、文本匹配等。尽管大型语言模型（LLMs）中的深度学习取得了显著成就，但神经网络架构的可解释性仍然较差，这影响了这些模型的可信度，从而限制了它们在风险敏感场景中的应用。在某些特定领域的数据稀缺场景中，快速获得大量监督学习标签是具有挑战性的，手动标注数据的工作量会非常大。神经网络中的灾难性遗忘进一步导致数据利用率低。在需要迅速响应的情境中，模型的密集性使得局部部署困难且响应时间较长，不利于这些领域的本地应用。受乘法法则、组合数学原理以及人类思维模式的启发，提出了一个多层框架及其算法——层次符号森林中的消化算法（DAHSF），以解决上述问题，结合文本规范化和语义解析工作流。中国的脚本语言“Fire Bunny智能开发平台V2.0”是本文讨论技术的重要测试和应用。DAHSF可以在特定场景下以少量数据集本地运行，并通过至少两个数量级优化模型大小和内存使用，从而提高执行速度，具有良好的优化前景。 

---
# Gauss-Newton Dynamics for Neural Networks: A Riemannian Optimization Perspective 

**Title (ZH)**: 基于拉曼辛几何的高斯-牛顿神经网络动力学：一种 riemannian 优化视角 

**Authors**: Semih Cayci  

**Link**: [PDF](https://arxiv.org/pdf/2412.14031)  

**Abstract**: We analyze the convergence of Gauss-Newton dynamics for training neural networks with smooth activation functions. In the underparameterized regime, the Gauss-Newton gradient flow induces a Riemannian gradient flow on a low-dimensional, smooth, embedded submanifold of the Euclidean output space. Using tools from Riemannian optimization, we prove \emph{last-iterate} convergence of the Riemannian gradient flow to the optimal in-class predictor at an \emph{exponential rate} that is independent of the conditioning of the Gram matrix, \emph{without} requiring explicit regularization. We further characterize the critical impacts of the neural network scaling factor and the initialization on the convergence behavior. In the overparameterized regime, we show that the Levenberg-Marquardt dynamics with an appropriately chosen damping factor yields robustness to ill-conditioned kernels, analogous to the underparameterized regime. These findings demonstrate the potential of Gauss-Newton methods for efficiently optimizing neural networks, particularly in ill-conditioned problems where kernel and Gram matrices have small singular values. 

**Abstract (ZH)**: 我们分析了带有光滑激活函数的神经网络训练中 Gauss-Newton 动力学的收敛性。在参数不足的区域，Gauss-Newton 梯度流诱导一个低维的光滑嵌入子流形上的黎曼梯度流，该子流形位于欧几里得输出空间中。利用黎曼优化的工具，我们证明了黎曼梯度流在末次迭代（last-iterate）意义上以与系数矩阵的条件无关的指数速度收敛至最优类内预测器，且这一收敛性不需要显式的正则化。此外，我们进一步分析了神经网络的缩放因子和初始化对收敛行为的关键影响。在参数过剩的区域，我们证明了适当选择阻尼因子的 Levenberg-Marquardt 动力学具有对病态核的鲁棒性，类似于参数不足的区域。这些发现表明，Gauss-Newton 方法在优化神经网络方面具有潜在的有效性，特别是在核矩阵和格朗日矩阵具有小奇异值的病态问题中。 

---
# Landscape of AI safety concerns -- A methodology to support safety assurance for AI-based autonomous systems 

**Title (ZH)**: 基于AI自主系统的安全性保障方法论——AI安全关切景观研究 

**Authors**: Ronald Schnitzer, Lennart Kilian, Simon Roessner, Konstantinos Theodorou, Sonja Zillner  

**Link**: [PDF](https://arxiv.org/pdf/2412.14020)  

**Abstract**: Artificial Intelligence (AI) has emerged as a key technology, driving advancements across a range of applications. Its integration into modern autonomous systems requires assuring safety. However, the challenge of assuring safety in systems that incorporate AI components is substantial. The lack of concrete specifications, and also the complexity of both the operational environment and the system itself, leads to various aspects of uncertain behavior and complicates the derivation of convincing evidence for system safety. Nonetheless, scholars proposed to thoroughly analyze and mitigate AI-specific insufficiencies, so-called AI safety concerns, which yields essential evidence supporting a convincing assurance case. In this paper, we build upon this idea and propose the so-called Landscape of AI Safety Concerns, a novel methodology designed to support the creation of safety assurance cases for AI-based systems by systematically demonstrating the absence of AI safety concerns. The methodology's application is illustrated through a case study involving a driverless regional train, demonstrating its practicality and effectiveness. 

**Abstract (ZH)**: 人工智能（AI）已成为关键性技术，推动了各种应用的发展。将其集成到现代自主系统中需要确保其安全性。然而，在包含AI组件的系统中保证安全性的挑战是巨大的。缺乏明确的规范，以及运行环境和系统的复杂性，导致了各种不确定行为，使得获得令人信服的系统安全证据变得更加复杂。尽管如此，学者们提出要彻底分析和缓解AI特有的不足之处，即所谓的AI安全关切，从而为一个可信的安全保证案例提供关键性证据。在本文中，我们在此基础上提出了一种名为AI安全关切景观的方法学，这是一种新型方法，旨在通过系统地证明不存在AI安全关切来支持AI基系统安全保证案例的创建。我们通过一个无人驾驶区域列车的案例研究来说明该方法学的应用，展示了其实用性和有效性。 

---
# SurgSora: Decoupled RGBD-Flow Diffusion Model for Controllable Surgical Video Generation 

**Title (ZH)**: SurgSora：解耦的RGBD流扩散模型用于可控手术视频生成 

**Authors**: Tong Chen, Shuya Yang, Junyi Wang, Long Bai, Hongliang Ren, Luping Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2412.14018)  

**Abstract**: Medical video generation has transformative potential for enhancing surgical understanding and pathology insights through precise and controllable visual representations. However, current models face limitations in controllability and authenticity. To bridge this gap, we propose SurgSora, a motion-controllable surgical video generation framework that uses a single input frame and user-controllable motion cues. SurgSora consists of three key modules: the Dual Semantic Injector (DSI), which extracts object-relevant RGB and depth features from the input frame and integrates them with segmentation cues to capture detailed spatial features of complex anatomical structures; the Decoupled Flow Mapper (DFM), which fuses optical flow with semantic-RGB-D features at multiple scales to enhance temporal understanding and object spatial dynamics; and the Trajectory Controller (TC), which allows users to specify motion directions and estimates sparse optical flow, guiding the video generation process. The fused features are used as conditions for a frozen Stable Diffusion model to produce realistic, temporally coherent surgical videos. Extensive evaluations demonstrate that SurgSora outperforms state-of-the-art methods in controllability and authenticity, showing its potential to advance surgical video generation for medical education, training, and research. 

**Abstract (ZH)**: 医学视频生成在通过精确可控的视觉表示增强手术理解和病理洞察方面具有变革性的潜力。然而，当前的模型在可控性和真实性方面存在局限性。为了解决这一问题，我们提出SurgSora，一种利用单一输入帧和用户可控的运动提示的运动可控手术视频生成框架。SurgSora 包含三个关键模块：双语义注入器（DSI），该模块从输入帧中提取与物体相关的RGB和深度特征，并将其与分割提示结合以捕获复杂解剖结构的详细空间特征；解耦流动映射器（DFM），该模块在多尺度上将光学流动与语义-RGB-D特征融合，以增强时间理解和物体的空间动态；轨迹控制器（TC），允许用户指定运动方向并估计稀疏的光学流动，从而引导视频生成过程。融合的特征被用作冻结的Stable Diffusion模型的条件以生成真实且时间连贯的手术视频。广泛的评估证明，SurgSora 在可控性和真实性方面优于现有方法，展示了其在医学教育、培训和研究中推动手术视频生成的潜力。 

---
# Few-shot Steerable Alignment: Adapting Rewards and LLM Policies with Neural Processes 

**Title (ZH)**: 少样本可调节对齐：基于神经过程适应奖励和大语言模型策略 

**Authors**: Katarzyna Kobalczyk, Claudio Fanconi, Hao Sun, Mihaela van der Schaar  

**Link**: [PDF](https://arxiv.org/pdf/2412.13998)  

**Abstract**: As large language models (LLMs) become increasingly embedded in everyday applications, ensuring their alignment with the diverse preferences of individual users has become a critical challenge. Currently deployed approaches typically assume homogeneous user objectives and rely on single-objective fine-tuning. However, human preferences are inherently heterogeneous, influenced by various unobservable factors, leading to conflicting signals in preference data. Existing solutions addressing this diversity often require costly datasets labelled for specific objectives and involve training multiple reward models or LLM policies, which is computationally expensive and impractical. In this work, we present a novel framework for few-shot steerable alignment, where users' underlying preferences are inferred from a small sample of their choices. To achieve this, we extend the Bradley-Terry-Luce model to handle heterogeneous preferences with unobserved variability factors and propose its practical implementation for reward modelling and LLM fine-tuning. Thanks to our proposed approach of functional parameter-space conditioning, LLMs trained with our framework can be adapted to individual preferences at inference time, generating outputs over a continuum of behavioural modes. We empirically validate the effectiveness of methods, demonstrating their ability to capture and align with diverse human preferences in a data-efficient manner. Our code is made available at: this https URL. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）越来越多地嵌入到日常应用中，确保它们与个人用户多样化的偏好保持一致已成为一个关键的挑战。当前部署的方法通常假设用户目标的一致性，并依赖单目标微调。然而，人类的偏好本质上是不一致的，受到各种不可观测因素的影响，导致偏好数据中的冲突信号。现有的解决这一多样性的方案往往需要为特定目标标注昂贵的数据集，并涉及训练多个奖励模型或LLM策略，这在计算上非常昂贵且不切实际。在本工作中，我们提出了一种新的少量示例可引导对齐框架，通过少量的选择样本推断用户的潜在偏好。为此，我们将布拉德利-特里-卢斯（Bradley-Terry-Luce）模型扩展以处理具有未观察到变异因素的不一致偏好，并提出其在奖励建模和LLM微调中的实际实现方法。凭借我们提出的功能参数空间调节方法，使用该框架训练的LLMs可以在推理时适应个体偏好，生成一系列行为模式的输出。我们通过实验证明了方法的有效性，展示了它们以数据效率的方式捕捉和对齐多样化的人类偏好的能力。我们的代码可以在以下链接获取：this https URL。 

---
# Prompting Strategies for Enabling Large Language Models to Infer Causation from Correlation 

**Title (ZH)**: 启用大型语言模型从相关性推断因果关系的提示策略 

**Authors**: Eleni Sgouritsa, Virginia Aglietti, Yee Whye Teh, Arnaud Doucet, Arthur Gretton, Silvia Chiappa  

**Link**: [PDF](https://arxiv.org/pdf/2412.13952)  

**Abstract**: The reasoning abilities of Large Language Models (LLMs) are attracting increasing attention. In this work, we focus on causal reasoning and address the task of establishing causal relationships based on correlation information, a highly challenging problem on which several LLMs have shown poor performance. We introduce a prompting strategy for this problem that breaks the original task into fixed subquestions, with each subquestion corresponding to one step of a formal causal discovery algorithm, the PC algorithm. The proposed prompting strategy, PC-SubQ, guides the LLM to follow these algorithmic steps, by sequentially prompting it with one subquestion at a time, augmenting the next subquestion's prompt with the answer to the previous one(s). We evaluate our approach on an existing causal benchmark, Corr2Cause: our experiments indicate a performance improvement across five LLMs when comparing PC-SubQ to baseline prompting strategies. Results are robust to causal query perturbations, when modifying the variable names or paraphrasing the expressions. 

**Abstract (ZH)**: 大型语言模型（LLMs）的推理能力正吸引越来越多的关注。本研究聚焦于因果推理，并旨在基于相关性信息建立因果关系，这是一个极具挑战性的问题，许多LLMs在这一任务上表现不佳。我们提出了一种针对该问题的提示策略，将原始任务分解为固定的小问题，每个小问题对应正式因果发现算法（如PC算法）的一个步骤。所提出的提示策略PC-SubQ通过按顺序提示LLM解决每一个小问题，并利用前一个问题的答案来增强后一个问题的提示，从而引导LLM遵循这些算法步骤。我们利用现有的因果基准测试Corr2Cause对这一方法进行了评估：实验表明，在五个LLM上使用PC-SubQ策略比基准提示策略提高了性能。当修改变量名称或重新措辞问题时，结果表现出一定的鲁棒性。 

---
# On Explaining Knowledge Distillation: Measuring and Visualising the Knowledge Transfer Process 

**Title (ZH)**: 探究知识蒸馏的解释：衡量与可视化知识转移过程 

**Authors**: Gereziher Adhane, Mohammad Mahdi Dehshibi, Dennis Vetter, David Masip, Gemma Roig  

**Link**: [PDF](https://arxiv.org/pdf/2412.13943)  

**Abstract**: Knowledge distillation (KD) remains challenging due to the opaque nature of the knowledge transfer process from a Teacher to a Student, making it difficult to address certain issues related to KD. To address this, we proposed UniCAM, a novel gradient-based visual explanation method, which effectively interprets the knowledge learned during KD. Our experimental results demonstrate that with the guidance of the Teacher's knowledge, the Student model becomes more efficient, learning more relevant features while discarding those that are not relevant. We refer to the features learned with the Teacher's guidance as distilled features and the features irrelevant to the task and ignored by the Student as residual features. Distilled features focus on key aspects of the input, such as textures and parts of objects. In contrast, residual features demonstrate more diffused attention, often targeting irrelevant areas, including the backgrounds of the target objects. In addition, we proposed two novel metrics: the feature similarity score (FSS) and the relevance score (RS), which quantify the relevance of the distilled knowledge. Experiments on the CIFAR10, ASIRRA, and Plant Disease datasets demonstrate that UniCAM and the two metrics offer valuable insights to explain the KD process. 

**Abstract (ZH)**: 知识蒸馏（Knowledge Distillation, KD）仍然具有挑战性，因为从教师模型（Teacher）到学生模型（Student）的知识转移过程不透明，使得难以解决某些与KD相关的问题。为了解决这一问题，我们提出了UniCAM，这是一种新颖的基于梯度的可视化解释方法，可以有效地解释KD过程中学习到的知识。我们的实验结果表明，在教师模型知识的指导下，学生模型变得更为高效，学习了更相关的特征并舍弃了不相关的特征。我们将教师模型指导下学习到的特征称为蒸馏特征，学生模型忽略的与任务无关的特征称为残差特征。蒸馏特征侧重于输入的关键方面，例如纹理和物体的部分。相比之下，残差特征展示了更弥散的注意力，经常针对无关区域，包括目标物体的背景。此外，我们还提出了两个新的度量标准：特征相似性得分（Feature Similarity Score, FSS）和相关性得分（Relevance Score, RS），用于量化蒸馏知识的相关性。在CIFAR10、ASIRRA和植物病害数据集上的实验表明，UniCAM和这两个度量标准提供了解释KD过程的重要见解。 

---
# Spatio-Temporal Forecasting of PM2.5 via Spatial-Diffusion guided Encoder-Decoder Architecture 

**Title (ZH)**: 基于空间扩散引导的编码-解码架构的PM2.5空间-时间预测 

**Authors**: Malay Pandey, Vaishali Jain, Nimit Godhani, Sachchida Nand Tripathi, Piyush Rai  

**Link**: [PDF](https://arxiv.org/pdf/2412.13935)  

**Abstract**: In many problem settings that require spatio-temporal forecasting, the values in the time-series not only exhibit spatio-temporal correlations but are also influenced by spatial diffusion across locations. One such example is forecasting the concentration of fine particulate matter (PM2.5) in the atmosphere which is influenced by many complex factors, the most important ones being diffusion due to meteorological factors as well as transport across vast distances over a period of time. We present a novel Spatio-Temporal Graph Neural Network architecture, that specifically captures these dependencies to forecast the PM2.5 concentration. Our model is based on an encoder-decoder architecture where the encoder and decoder parts leverage gated recurrent units (GRU) augmented with a graph neural network (TransformerConv) to account for spatial diffusion. Our model can also be seen as a generalization of various existing models for time-series or spatio-temporal forecasting. We demonstrate the model's effectiveness on two real-world PM2.5 datasets: (1) data collected by us using a recently deployed network of low-cost PM$_{2.5}$ sensors from 511 locations spanning the entirety of the Indian state of Bihar over a period of one year, and (2) another publicly available dataset that covers severely polluted regions from China for a period of 4 years. Our experimental results show our model's impressive ability to account for both spatial as well as temporal dependencies precisely. 

**Abstract (ZH)**: 在许多需要时空预测的问题设置中，时间序列中的值不仅表现出时空相关性，还会受到不同位置之间的空间扩散影响。一个典型例子是大气中细颗粒物（PM2.5）浓度的预测，这个浓度受到多种复杂因素的影响，其中最重要的是气象因素导致的扩散以及长时间内跨区域的传输。我们提出了一种新颖的时空图神经网络架构，专门捕捉这些依赖关系以预测PM2.5浓度。该模型基于编码器-解码器架构，其中编码器和解码器部分利用了融合图神经网络（TransformerConv）的门控递归单元（GRU），以考虑空间扩散因素。此外，我们的模型可以视为现有时间序列或时空预测模型的一般化。我们在两个真实的PM2.5数据集上证明了该模型的有效性：（1）我们通过部署在印度比哈尔邦511个位置的低成本PM2.5传感器收集的数据，该数据持续了一年；（2）以及来自中国严重污染区域的另一个公开可用的数据集，数据持续了四年。实验结果显示，我们的模型能够精确地捕捉到时空依赖关系。 

---
# Pipeline Analysis for Developing Instruct LLMs in Low-Resource Languages: A Case Study on Basque 

**Title (ZH)**: 低资源语言中开发指令大型语言模型的管道分析：关于巴斯克语的案例研究 

**Authors**: Ander Corral, Ixak Sarasua, Xabier Saralegi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13922)  

**Abstract**: Large language models (LLMs) are typically optimized for resource-rich languages like English, exacerbating the gap between high-resource and underrepresented languages. This work presents a detailed analysis of strategies for developing a model capable of following instructions in a low-resource language, specifically Basque, by focusing on three key stages: pre-training, instruction tuning, and alignment with human preferences. Our findings demonstrate that continual pre-training with a high-quality Basque corpus of around 600 million words improves natural language understanding (NLU) of the foundational model by over 12 points. Moreover, instruction tuning and human preference alignment using automatically translated datasets proved highly effective, resulting in a 24-point improvement in instruction-following performance. The resulting models, Llama-eus-8B and Llama-eus-8B-instruct, establish a new state-of-the-art for Basque in the sub-10B parameter category. 

**Abstract (ZH)**: 大型语言模型（LLMs）通常针对资源丰富语言如英语进行优化，加剧了高资源语言和欠代表语言之间的差距。本研究详细分析了开发一种能够在低资源语言中遵循指令的模型的方法，特别针对巴斯克语，通过聚焦三个关键阶段来实现：预训练、指令调整和与人类偏好的对齐。我们的研究结果表明，使用大约6亿词汇的高质量巴斯克语语料库进行持续预训练，可以将基础模型的自然语言理解（NLU）性能提高超过12个百分点。此外，使用自动翻译的数据集进行指令调整和人类偏好对齐非常有效，最终使得指令遵循性能提高了24个百分点。由此产生的模型Llama-eus-8B和Llama-eus-8B-instruct在参数量小于10B的子类别中建立了新的性能基准。 

---
# Energy-Efficient SLAM via Joint Design of Sensing, Communication, and Exploration Speed 

**Title (ZH)**: 基于联合设计感知、通信和探索速度的节能SLAM 

**Authors**: Zidong Han, Ruibo Jin, Xiaoyang Li, Bingpeng Zhou, Qinyu Zhang, Yi Gong  

**Link**: [PDF](https://arxiv.org/pdf/2412.13912)  

**Abstract**: To support future spatial machine intelligence applications, lifelong simultaneous localization and mapping (SLAM) has drawn significant attentions. SLAM is usually realized based on various types of mobile robots performing simultaneous and continuous sensing and communication. This paper focuses on analyzing the energy efficiency of robot operation for lifelong SLAM by jointly considering sensing, communication and mechanical factors. The system model is built based on a robot equipped with a 2D light detection and ranging (LiDAR) and an odometry. The cloud point raw data as well as the odometry data are wirelessly transmitted to data center where real-time map reconstruction is realized based on an unsupervised deep learning based method. The sensing duration, transmit power, transmit duration and exploration speed are jointly optimized to minimize the energy consumption. Simulations and experiments demonstrate the performance of our proposed method. 

**Abstract (ZH)**: 为了支持未来空间机器智能应用，终身同时定位与地图构建（SLAM）已经引起了广泛关注。SLAM通常通过各种类型的移动机器人实现，这些机器人能够同时进行连续的感知和通信。本文聚焦于分析机器人操作在终身SLAM中的能源效率，同时考虑了感知、通信和机械因素的影响。基于装备有2D激光探测与测距（LiDAR）和里程计的机器人构建了系统模型。云点原始数据和里程计数据通过无线方式传输至数据中心，基于无监督深度学习方法实现实时地图重建。通过联合优化感知持续时间、传输功率、传输持续时间和探索速度，以最小化能量消耗。仿真和实验结果展示了所提方法的性能。 

---
# Understanding and Analyzing Model Robustness and Knowledge-Transfer in Multilingual Neural Machine Translation using TX-Ray 

**Title (ZH)**: 使用TX-Ray理解并分析多语言神经机器翻译中模型稳健性和知识迁移现象 

**Authors**: Vageesh Saxena, Sharid Loáiciga, Nils Rethmeier  

**Link**: [PDF](https://arxiv.org/pdf/2412.13881)  

**Abstract**: Neural networks have demonstrated significant advancements in Neural Machine Translation (NMT) compared to conventional phrase-based approaches. However, Multilingual Neural Machine Translation (MNMT) in extremely low-resource settings remains underexplored. This research investigates how knowledge transfer across languages can enhance MNMT in such scenarios. Using the Tatoeba translation challenge dataset from Helsinki NLP, we perform English-German, English-French, and English-Spanish translations, leveraging minimal parallel data to establish cross-lingual mappings. Unlike conventional methods relying on extensive pre-training for specific language pairs, we pre-train our model on English-English translations, setting English as the source language for all tasks. The model is fine-tuned on target language pairs using joint multi-task and sequential transfer learning strategies. Our work addresses three key questions: (1) How can knowledge transfer across languages improve MNMT in extremely low-resource scenarios? (2) How does pruning neuron knowledge affect model generalization, robustness, and catastrophic forgetting? (3) How can TX-Ray interpret and quantify knowledge transfer in trained models? Evaluation using BLEU-4 scores demonstrates that sequential transfer learning outperforms baselines on a 40k parallel sentence corpus, showcasing its efficacy. However, pruning neuron knowledge degrades performance, increases catastrophic forgetting, and fails to improve robustness or generalization. Our findings provide valuable insights into the potential and limitations of knowledge transfer and pruning in MNMT for extremely low-resource settings. 

**Abstract (ZH)**: 与传统短语基于的方法相比，神经网络在神经机器翻译（NMT）方面取得了显著进步。然而，在极度低资源设置下，多语言神经机器翻译（MNMT）仍然研究较少。本研究探讨了跨语言知识转移如何在这些场景中增强MNMT的表现。我们使用赫尔辛基NLP提供的Tatoeba翻译挑战数据集，进行了英语-德语、英语-法语和英语-西班牙语的翻译任务，利用少量的平行数据来建立跨语言映射。与依赖于特定语言对大量预训练的传统方法不同，我们仅利用英语-英语的平行数据进行预训练，并将英语作为所有任务的源语言。模型通过联合多任务和序列知识转移学习策略在目标语言对上进行微调。我们的研究主要回答了三个关键问题：(1) 跨语言知识转移如何在极度低资源场景下改善MNMT？(2) 神经元知识剪枝如何影响模型的泛化能力、鲁棒性和灾难性遗忘？(3) TX-Ray如何对训练模型中的知识转移进行解释和量化？使用BLEU-4评分的评估结果显示，序列知识转移学习在4万个平行句子的语料库上优于基线方法，展示了其有效性。然而，神经元知识剪枝降低了性能，增加了灾难性遗忘的风险，并未能提高鲁棒性或泛化能力。我们的研究结果为极度低资源设置下的MNMT中知识转移和剪枝的潜力及局限性提供了有价值的认识。 

---
# Crabs: Consuming Resrouce via Auto-generation for LLM-DoS Attack under Black-box Settings 

**Title (ZH)**: 螃蟹：在黑盒设置下通过自动生成消耗资源进行大语言模型拒绝服务攻击 

**Authors**: Yuanhe Zhang, Zhenhong Zhou, Wei Zhang, Xinyue Wang, Xiaojun Jia, Yang Liu, Sen Su  

**Link**: [PDF](https://arxiv.org/pdf/2412.13879)  

**Abstract**: Large Language Models (LLMs) have demonstrated remarkable performance across diverse tasks. LLMs continue to be vulnerable to external threats, particularly Denial-of-Service (DoS) attacks. Specifically, LLM-DoS attacks aim to exhaust computational resources and block services. However, prior works tend to focus on performing white-box attacks, overlooking black-box settings. In this work, we propose an automated algorithm designed for black-box LLMs, called Auto-Generation for LLM-DoS Attack (AutoDoS). AutoDoS introduces DoS Attack Tree and optimizes the prompt node coverage to enhance effectiveness under black-box conditions. Our method can bypass existing defense with enhanced stealthiness via semantic improvement of prompt nodes. Furthermore, we reveal that implanting Length Trojan in Basic DoS Prompt aids in achieving higher attack efficacy. Experimental results show that AutoDoS amplifies service response latency by over 250 $\times \uparrow$, leading to severe resource consumption in terms of GPU utilization and memory usage. Our code is available at \url{this https URL}. 

**Abstract (ZH)**: 大型语言模型（LLMs）在多种任务中表现出色，但仍然容易受到外部威胁的影响，尤其是拒绝服务（DoS）攻击。具体来说，LLM-DoS攻击旨在耗尽计算资源并阻塞服务。然而，此前的工作往往侧重于进行白盒攻击，忽略了黑盒环境。在本工作中，我们提出了一种针对黑盒LLMs的自动化算法，名为Auto-Generation for LLM-DoS Attack（AutoDoS）。AutoDoS引入了DoS攻击树，并优化了提示节点的覆盖范围，以提高在黑盒条件下的有效性。我们的方法通过对提示节点进行语义改进，能够避开现有的防御措施并增强隐蔽性。此外，我们发现将Length Trojan植入基础DoS提示中有助于提高攻击效果。实验结果表明，AutoDoS将服务响应延迟放大了约250倍，导致严重的GPU利用和内存使用增加。我们的代码可在 \url{这个链接} 获取。 

---
# RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation 

**Title (ZH)**: RoboMIND：多体态智能规范数据基准——面向机器人操作 

**Authors**: Kun Wu, Chengkai Hou, Jiaming Liu, Zhengping Che, Xiaozhu Ju, Zhuqin Yang, Meng Li, Yinuo Zhao, Zhiyuan Xu, Guang Yang, Zhen Zhao, Guangyu Li, Zhao Jin, Lecheng Wang, Jilei Mao, Xinhua Wang, Shichao Fan, Ning Liu, Pei Ren, Qiang Zhang, Yaoxu Lyu, Mengzhen Liu, Jingyang He, Yulin Luo, Zeyu Gao, Chenxuan Li, Chenyang Gu, Yankai Fu, Di Wu, Xingyu Wang, Sixiang Chen, Zhenyu Wang, Pengju An, Siyuan Qian, Shanghang Zhang, Jian Tang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13877)  

**Abstract**: Developing robust and general-purpose robotic manipulation policies is a key goal in the field of robotics. To achieve effective generalization, it is essential to construct comprehensive datasets that encompass a large number of demonstration trajectories and diverse tasks. Unlike vision or language data that can be collected from the Internet, robotic datasets require detailed observations and manipulation actions, necessitating significant investment in hardware-software infrastructure and human labor. While existing works have focused on assembling various individual robot datasets, there remains a lack of a unified data collection standard and insufficient diversity in tasks, scenarios, and robot types. In this paper, we introduce RoboMIND (Multi-embodiment Intelligence Normative Data for Robot manipulation), featuring 55k real-world demonstration trajectories across 279 diverse tasks involving 61 different object classes. RoboMIND is collected through human teleoperation and encompasses comprehensive robotic-related information, including multi-view RGB-D images, proprioceptive robot state information, end effector details, and linguistic task descriptions. To ensure dataset consistency and reliability during policy learning, RoboMIND is built on a unified data collection platform and standardized protocol, covering four distinct robotic embodiments. We provide a thorough quantitative and qualitative analysis of RoboMIND across multiple dimensions, offering detailed insights into the diversity of our datasets. In our experiments, we conduct extensive real-world testing with four state-of-the-art imitation learning methods, demonstrating that training with RoboMIND data results in a high manipulation success rate and strong generalization. Our project is at this https URL. 

**Abstract (ZH)**: 开发稳健且通用的机器人操作策略是机器人学领域的关键目标。为了实现有效的泛化，构建综合性数据集至关重要，该数据集应包含大量的演示轨迹和多样化任务。与可以从互联网收集的视觉或语言数据不同，机器人数据集需要详细的观察和操作动作，这需要大量的硬件软件基础设施和人力投入。现有工作主要集中于组装各种独立的机器人数据集，但仍然缺乏统一的数据收集标准，且任务、场景和机器人类型多样性不足。在本文中，我们介绍了一种名为RoboMIND（多体智能规范数据集）的全新数据集，涵盖了279个不同任务的55,000个实际世界演示轨迹，涉及61个不同的物体类别。RoboMIND通过人类遥控收集，并包含了全面的机器人相关信息，包括多视角RGB-D图像、机器人 proprioceptive 状态信息、末端执行器细节以及语言任务描述。为确保策略学习过程中数据集一致性和可靠性，RoboMIND基于统一的数据收集平台和标准化协议构建，涵盖了四种不同的机器人实体。我们从多个维度对RoboMIND进行了详细的定量和定性分析，提供了有关数据集多样性的深入见解。在我们的实验中，我们使用四种最先进的模仿学习方法进行了广泛的实地测试，结果表明使用RoboMIND数据训练能够实现高的操作成功率和强大的泛化能力。我们的项目可在以下链接找到：[项目链接]。 

---
# SHAP scores fail pervasively even when Lipschitz succeeds 

**Title (ZH)**: SHAP分数在Lipschitz成功时仍普遍失效 

**Authors**: Olivier Letoffe, Xuanxiang Huang, Joao Marques-Silva  

**Link**: [PDF](https://arxiv.org/pdf/2412.13866)  

**Abstract**: The ubiquitous use of Shapley values in eXplainable AI (XAI) has been triggered by the tool SHAP, and as a result are commonly referred to as SHAP scores. Recent work devised examples of machine learning (ML) classifiers for which the computed SHAP scores are thoroughly unsatisfactory, by allowing human decision-makers to be misled. Nevertheless, such examples could be perceived as somewhat artificial, since the selected classes must be interpreted as numeric. Furthermore, it was unclear how general were the issues identified with SHAP scores. This paper answers these criticisms. First, the paper shows that for Boolean classifiers there are arbitrarily many examples for which the SHAP scores must be deemed unsatisfactory. Second, the paper shows that the issues with SHAP scores are also observed in the case of regression models. In addition, the paper studies the class of regression models that respect Lipschitz continuity, a measure of a function's rate of change that finds important recent uses in ML, including model robustness. Concretely, the paper shows that the issues with SHAP scores occur even for regression models that respect Lipschitz continuity. Finally, the paper shows that the same issues are guaranteed to exist for arbitrarily differentiable regression models. 

**Abstract (ZH)**: 解释性人工智能（XAI）中广泛使用Shapley值的现象是由工具SHAP引发的，因此这些Shapley值通常被称为SHAP分数。最近的研究为机器学习（ML）分类器提供了例子，其中计算出的SHAP分数极为不令人满意，以至于误导了人类决策者。然而，这些例子可能会被视为略显人工，因为选取的类别必须被解释为数值型。此外，尚未明确SHAP分数存在的问题有多广泛。本文回答了这些批评。首先，本文表明对于布尔分类器，存在任意多个示例，其中SHAP分数必须被视为不令人满意。其次，本文表明在回归模型中也观察到了SHAP分数的问题。此外，本文研究了尊重Lipschitz连续性的回归模型类，这是一种衡量函数变化率的指标，在包括模型鲁棒性在内的现代机器学习中得到了重要的应用。具体而言，本文表明即使对于尊重Lipschitz连续性的回归模型，SHAP分数的问题也会出现。最后，本文表明对于任意可微的回归模型，也会存在同样的问题。 

---
# From Expectation to Habit: Why Do Software Practitioners Adopt Fairness Toolkits? 

**Title (ZH)**: 从期望到习惯：软件从业者为何采用公平性工具包？ 

**Authors**: Gianmario Voria, Stefano Lambiase, Maria Concetta Schiavone, Gemma Catolino, Fabio Palomba  

**Link**: [PDF](https://arxiv.org/pdf/2412.13846)  

**Abstract**: As the adoption of machine learning (ML) systems continues to grow across industries, concerns about fairness and bias in these systems have taken center stage. Fairness toolkits, designed to mitigate bias in ML models, serve as critical tools for addressing these ethical concerns. However, their adoption in the context of software development remains underexplored, especially regarding the cognitive and behavioral factors driving their usage. As a deeper understanding of these factors could be pivotal in refining tool designs and promoting broader adoption, this study investigates the factors influencing the adoption of fairness toolkits from an individual perspective. Guided by the Unified Theory of Acceptance and Use of Technology (UTAUT2), we examined the factors shaping the intention to adopt and actual use of fairness toolkits. Specifically, we employed Partial Least Squares Structural Equation Modeling (PLS-SEM) to analyze data from a survey study involving practitioners in the software industry. Our findings reveal that performance expectancy and habit are the primary drivers of fairness toolkit adoption. These insights suggest that by emphasizing the effectiveness of these tools in mitigating bias and fostering habitual use, organizations can encourage wider adoption. Practical recommendations include improving toolkit usability, integrating bias mitigation processes into routine development workflows, and providing ongoing support to ensure professionals see clear benefits from regular use. 

**Abstract (ZH)**: 随着机器学习（ML）系统在各行各业中的应用不断扩大，人们对这些系统中公平性和偏见问题的关注也随之上升。设计用于减轻ML模型偏见的公平性工具包，成为了应对这些伦理问题的关键工具。然而，这些工具包在软件开发中的应用仍然未得到充分探索，尤其是在认知和行为因素如何影响其使用的问题上。对这些因素的深入理解对于改进工具设计并促进更广泛的使用至关重要。因此，本研究从个体角度出发，探讨影响公平性工具包采用的因素。基于统一的接受和技术使用理论（UTAU2），我们分析了塑造采用公平性工具包意图以及实际使用行为的因素。具体来说，我们使用部分最小二乘路径分析（PLS-SEM）对软件行业从业者参与度调查的数据进行了分析。研究发现，绩效期望和习惯是影响公平性工具包采用的主要因素。这些发现表明，通过强调这些工具在减轻偏见方面的有效性以及培养其使用习惯，组织可以鼓励更广泛的采用。实用建议包括提高工具的易用性，将偏见缓解过程整合到常规开发流程中，并提供持续支持，以确保专业人士从定期使用中获得明显的好处。 

---
# Do Language Models Understand Time? 

**Title (ZH)**: 语言模型理解时间能力如何？ 

**Authors**: Xi Ding, Lei Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13845)  

**Abstract**: Large language models (LLMs) have revolutionized video-based computer vision applications, including action recognition, anomaly detection, and video summarization. Videos inherently pose unique challenges, combining spatial complexity with temporal dynamics that are absent in static images or textual data. Current approaches to video understanding with LLMs often rely on pretrained video encoders to extract spatiotemporal features and text encoders to capture semantic meaning. These representations are integrated within LLM frameworks, enabling multimodal reasoning across diverse video tasks. However, the critical question persists: Can LLMs truly understand the concept of time, and how effectively can they reason about temporal relationships in videos? This work critically examines the role of LLMs in video processing, with a specific focus on their temporal reasoning capabilities. We identify key limitations in the interaction between LLMs and pretrained encoders, revealing gaps in their ability to model long-term dependencies and abstract temporal concepts such as causality and event progression. Furthermore, we analyze challenges posed by existing video datasets, including biases, lack of temporal annotations, and domain-specific limitations that constrain the temporal understanding of LLMs. To address these gaps, we explore promising future directions, including the co-evolution of LLMs and encoders, the development of enriched datasets with explicit temporal labels, and innovative architectures for integrating spatial, temporal, and semantic reasoning. By addressing these challenges, we aim to advance the temporal comprehension of LLMs, unlocking their full potential in video analysis and beyond. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已经重塑了基于视频的计算机视觉应用，包括动作识别、异常检测和视频总结。视频固有的挑战在于其结合了静态图像或文本数据中缺失的时空复杂性和动态性。当前使用LLMs进行视频理解的方法往往依赖于预训练的视频编码器来提取时空特征，以及文本编码器来捕捉语义意义。这些表示形式整合到LLM框架中，使跨多种视频任务的多模态推理成为可能。然而，关键的问题仍然存在：LLMs能否真正理解时间的概念，并且它们在视频中如何有效地推理时间关系？本研究批判性地探讨了LLMs在视频处理中的作用，特别是其时间推理能力。我们识别了LLMs与预训练编码器之间交互的关键局限，揭示了它们在建模长期依赖关系以及抽象因果关系和事件进程等时间概念方面的不足。此外，我们分析了现有视频数据集所面临的挑战，包括偏见、缺失的时间标注以及特定领域的限制，这些都会限制LLMs的时间理解能力。为了解决这些缺口，我们探讨了有前途的发展方向，包括LLMs与编码器的协同进化、带有显式时间标签的丰富数据集开发，以及整合空间、时间和语义推理的创新架构。通过解决这些挑战，我们期望提升LLMs的时间理解能力，使其在视频分析以及其他领域发挥出全部潜力。 

---
# CRM: Retrieval Model with Controllable Condition 

**Title (ZH)**: CRM：可控条件检索模型 

**Authors**: Chi Liu, Jiangxia Cao, Rui Huang, Kuo Cai, Weifeng Ding, Qiang Luo, Kun Gai, Guorui Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2412.13844)  

**Abstract**: Recommendation systems (RecSys) are designed to connect users with relevant items from a vast pool of candidates while aligning with the business goals of the platform. A typical industrial RecSys is composed of two main stages, retrieval and ranking: (1) the retrieval stage aims at searching hundreds of item candidates satisfied user interests; (2) based on the retrieved items, the ranking stage aims at selecting the best dozen items by multiple targets estimation for each item candidate, including classification and regression targets. Compared with ranking model, the retrieval model absence of item candidate information during inference, therefore retrieval models are often trained by classification target only (e.g., click-through rate), but failed to incorporate regression target (e.g., the expected watch-time), which limit the effectiveness of retrieval. In this paper, we propose the Controllable Retrieval Model (CRM), which integrates regression information as conditional features into the two-tower retrieval paradigm. This modification enables the retrieval stage could fulfill the target gap with ranking model, enhancing the retrieval model ability to search item candidates satisfied the user interests and condition effectively. We validate the effectiveness of CRM through real-world A/B testing and demonstrate its successful deployment in Kuaishou short-video recommendation system, which serves over 400 million users. 

**Abstract (ZH)**: 推荐系统（RecSys）旨在将用户与大规模候选项库中的相关项目进行连接，同时与平台的商业目标相一致。一个典型的工业推荐系统由两个主要阶段组成：检索和排序：(1) 检索阶段的目标是在满足用户兴趣的前提下搜索数百个候选项；(2) 在检索到的项目基础上，排序阶段的目标是通过多项目标估计为每个候选项选择最优的十几项，包括分类目标和回归目标。与排序模型相比，检索模型在推理过程中缺乏候选项信息，因此检索模型通常仅通过分类目标（例如点击率）进行训练，而未能结合回归目标（例如预期观看时间），从而限制了检索模型的效果。在本文中，我们提出了一种可控检索模型（CRM），它将回归信息作为条件特征融入到两塔检索框架中。这种修改使得检索阶段能够弥补与排序模型之间的目标差距，增强了检索模型在有效满足用户兴趣和条件方面的检索候选项的能力。我们通过实际的A/B测试验证了CRM的有效性，并展示了其在快手短视频推荐系统中的成功部署，该系统服务于超过4亿用户。 

---
# AI Perceptions Across Cultures: Similarities and Differences in Expectations, Risks, Benefits, Tradeoffs, and Value in Germany and China 

**Title (ZH)**: 跨文化视角下的人工智能感知：德国与中国在预期、风险、利益、权衡及价值方面的相似性和差异性 

**Authors**: Philipp Brauner, Felix Glawe, Gian Luca Liehner, Luisa Vervier, Martina Ziefle  

**Link**: [PDF](https://arxiv.org/pdf/2412.13841)  

**Abstract**: As artificial intelligence (AI) continues to advance, understanding public perceptions -- including biases, risks, and benefits -- is critical for guiding research priorities, shaping public discourse, and informing policy. This study explores public mental models of AI using micro scenarios to assess reactions to 71 statements about AI's potential future impacts. Drawing on cross-cultural samples from Germany (N=52) and China (N=60), we identify significant differences in expectations, evaluations, and risk-utility tradeoffs. German participants tended toward more cautious assessments, whereas Chinese participants expressed greater optimism regarding AI's societal benefits. Chinese participants exhibited relatively balanced risk-benefit tradeoffs ($\beta=-0.463$ for risk and $\beta=+0.484$ for benefit, $r^2=.630$). In contrast, German participants showed a stronger emphasis on AI benefits and less on risks ($\beta=-0.337$ for risk and $\beta=+0.715$ for benefit, $r^2=.839$). Visual cognitive maps illustrate these contrasts, offering new perspectives on how cultural contexts shape AI acceptance. Our findings underline key factors influencing public perception and provide actionable insights for fostering equitable and culturally sensitive integration of AI technologies. 

**Abstract (ZH)**: 随着人工智能（AI）技术的不断进步，理解公众的看法——包括偏见、风险和利益——对于指导研究优先事项、塑造公众讨论和制定政策至关重要。本研究通过使用微场景来探索公众对AI的心理模型，并评估参与者对关于AI潜在未来影响的71个陈述的反应。我们通过从德国（N=52）和中国（N=60）招募的跨文化样本，识别出预期、评价和风险-收益权衡方面的显著差异。德国参与者倾向于更为谨慎的评估，而中国参与者则对AI的社会益处表现出更大的乐观态度。中国参与者在风险-收益权衡方面表现出相对均衡的态度（风险的$\beta=-0.463$，收益的$\beta=+0.484$，$r^2=.630$）。相比之下，德国参与者更强调AI的益处，而较少关注风险（风险的$\beta=-0.337$，收益的$\beta=+0.715$，$r^2=.839$）。视觉认知地图展示了这些差异，为文化背景如何影响对AI的接受程度提供了新的视角。我们的研究结果强调了影响公众看法的关键因素，并为促进公平且文化敏感的人工智能技术集成提供了操作性的见解。 

---
# Maybe you are looking for CroQS: Cross-modal Query Suggestion for Text-to-Image Retrieval 

**Title (ZH)**: 也许您正在寻找CroQS：跨模态查询建议技术在文本到图像检索中的应用 

**Authors**: Giacomo Pacini, Fabio Carrara, Nicola Messina, Nicola Tonellotto, Giuseppe Amato, Fabrizio Falchi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13834)  

**Abstract**: Query suggestion, a technique widely adopted in information retrieval, enhances system interactivity and the browsing experience of document collections. In cross-modal retrieval, many works have focused on retrieving relevant items from natural language queries, while few have explored query suggestion solutions. In this work, we address query suggestion in cross-modal retrieval, introducing a novel task that focuses on suggesting minimal textual modifications needed to explore visually consistent subsets of the collection, following the premise of ''Maybe you are looking for''. To facilitate the evaluation and development of methods, we present a tailored benchmark named CroQS. This dataset comprises initial queries, grouped result sets, and human-defined suggested queries for each group. We establish dedicated metrics to rigorously evaluate the performance of various methods on this task, measuring representativeness, cluster specificity, and similarity of the suggested queries to the original ones. Baseline methods from related fields, such as image captioning and content summarization, are adapted for this task to provide reference performance scores. Although relatively far from human performance, our experiments reveal that both LLM-based and captioning-based methods achieve competitive results on CroQS, improving the recall on cluster specificity by more than 115% and representativeness mAP by more than 52% with respect to the initial query. The dataset, the implementation of the baseline methods and the notebooks containing our experiments are available here: this https URL 

**Abstract (ZH)**: 查询建议是一种广泛应用于信息检索的技术，它可以增强系统的互动性和文档集合的浏览体验。在跨模态检索中，许多研究工作集中在从自然语言查询中检索相关项，而很少有研究探索查询建议解决方案。在本工作中，我们针对跨模态检索中的查询建议问题，引入了一个新的任务，该任务重点建议必要的最小文本修改，以便探索集合中视觉一致的子集，其前提是“也许您要找的是”。为了促进方法的评估和发展，我们提出了一个定制基准命名为CroQS。这个数据集包括初始查询、分组结果集以及每个组的人工定义建议查询。我们建立了一套专用的评估指标，以严格评估各种方法在该任务上的性能，测量建议查询的代表性、簇特异性以及与原始查询的相似度。来自相关领域的基线方法，如图像描述和内容总结，被调整用于此任务，以提供参考性能得分。尽管在人类性能方面尚有较大差距，但我们的实验结果表明，基于LLM的方法和基于图像描述的方法在CroQS上都取得了可竞争的结果。与初始查询相比，这些方法将簇特异性的召回率提高了超过115%，代表性mAP提高了超过52%。该数据集、基线方法的实现以及包含我们实验的笔记本电脑，均可在此获取：[this https URL] 

---
# Heterogeneous Graph Collaborative Filtering 

**Title (ZH)**: 异质图协作过滤 

**Authors**: Lianghao Xia, Meiyan Xie, Yong Xu, Chao Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13825)  

**Abstract**: For modern recommender systems, the use of low-dimensional latent representations to embed users and items based on their observed interactions has become commonplace. However, many existing recommendation models are primarily designed for coarse-grained and homogeneous interactions, which limits their effectiveness in two critical dimensions. Firstly, these models fail to leverage the relational dependencies that exist across different types of user behaviors, such as page views, collects, comments, and purchases. Secondly, they struggle to capture the fine-grained latent factors that drive user interaction patterns. To address these limitations, we present a heterogeneous graph collaborative filtering model MixRec that excels at disentangling users' multi-behavior interaction patterns and uncovering the latent intent factors behind each behavior. Our model achieves this by incorporating intent disentanglement and multi-behavior modeling, facilitated by a parameterized heterogeneous hypergraph architecture. Furthermore, we introduce a novel contrastive learning paradigm that adaptively explores the advantages of self-supervised data augmentation, thereby enhancing the model's resilience against data sparsity and expressiveness with relation heterogeneity. To validate the efficacy of MixRec, we conducted extensive experiments on three public datasets. The results clearly demonstrate its superior performance, significantly outperforming various state-of-the-art baselines. Our model is open-sourced and available at: this https URL. 

**Abstract (ZH)**: 对于现代推荐系统而言，基于用户观察到的交互使用低维度潜在表示嵌入用户和项目已经成为常态。然而，现有的许多推荐模型主要针对粗粒度且同质的交互进行设计，这在两个关键维度上限制了它们的效用。首先，这些模型未能利用不同类型的用户行为（例如页面浏览、收藏、评论和购买）之间的关系依赖性。其次，它们难以捕捉驱动用户互动模式的细微潜在因素。为了解决这些限制，我们提出了一种异质图协同过滤模型MixRec，该模型擅长分离用户多行为交互模式，并揭示每个行为背后的潜在意图因素。通过引入参数化的异质超图架构，我们的模型通过意图分离和多行为建模实现了这一目标。此外，我们引入了一种新的对比学习范式，该范式能够自适应地探索自我监督数据增强的优势，从而增强模型对于数据稀疏性和关系异质性的抗扰性和表达能力。为了验证MixRec的有效性，我们在三个公开数据集上进行了广泛实验。实验结果明确显示出其优越性能，显著优于多种最先进的基线方法。我们的模型已开源，并可在以下链接获取：this https URL。 

---
# CAD-Assistant: Tool-Augmented VLLMs as Generic CAD Task Solvers? 

**Title (ZH)**: CAD-Assistant: 工具增强的多模态大模型作为通用CAD任务求解器？ 

**Authors**: Dimitrios Mallis, Ahmet Serdar Karadeniz, Sebastian Cavada, Danila Rukhovich, Niki Foteinopoulou, Kseniya Cherenkova, Anis Kacem, Djamila Aouada  

**Link**: [PDF](https://arxiv.org/pdf/2412.13810)  

**Abstract**: We propose CAD-Assistant, a general-purpose CAD agent for AI-assisted design. Our approach is based on a powerful Vision and Large Language Model (VLLM) as a planner and a tool-augmentation paradigm using CAD-specific modules. CAD-Assistant addresses multimodal user queries by generating actions that are iteratively executed on a Python interpreter equipped with the FreeCAD software, accessed via its Python API. Our framework is able to assess the impact of generated CAD commands on geometry and adapts subsequent actions based on the evolving state of the CAD design. We consider a wide range of CAD-specific tools including Python libraries, modules of the FreeCAD Python API, helpful routines, rendering functions and other specialized modules. We evaluate our method on multiple CAD benchmarks and qualitatively demonstrate the potential of tool-augmented VLLMs as generic CAD task solvers across diverse CAD workflows. 

**Abstract (ZH)**: 我们提出了CAD-Assistant，这是一种通用的计算机辅助设计(CAD)代理，旨在支持人工智能辅助设计。我们的方法基于强大的视觉和大型语言模型(VLLM)作为规划者，并采用包括特定于CAD模块的工具增强范式。CAD-Assistant通过生成动作并在配备FreeCAD软件的Python解释器上迭代执行来处理多模态用户查询。我们的框架能够评估生成的CAD命令对几何形状的影响，并根据CAD设计状态的不断演化来调整后续动作。我们考虑了包括Python库、FreeCAD Python API的模块、有用的例行程序、渲染函数和其他专门模块在内的广泛CAD特定工具。我们通过在多种CAD基准测试上评估我们的方法，并以质性的方式展示了工具增强的VLLMs作为一种通用的CAD任务求解器在各种CAD工作流程中的潜力。 

---
# AI-Powered Algorithm-Centric Quantum Processor Topology Design 

**Title (ZH)**: AI驱动的算法中心量子处理器拓扑设计 

**Authors**: Tian Li, Xiao-Yue Xu, Chen Ding, Tian-Ci Tian, Wei-You Liao, Shuo Zhang, He-Liang Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13805)  

**Abstract**: Quantum computing promises to revolutionize various fields, yet the execution of quantum programs necessitates an effective compilation process. This involves strategically mapping quantum circuits onto the physical qubits of a quantum processor. The qubits' arrangement, or topology, is pivotal to the circuit's performance, a factor that often defies traditional heuristic or manual optimization methods due to its complexity. In this study, we introduce a novel approach leveraging reinforcement learning to dynamically tailor qubit topologies to the unique specifications of individual quantum circuits, guiding algorithm-driven quantum processor topology design for reducing the depth of mapped circuit, which is particularly critical for the output accuracy on noisy quantum processors. Our method marks a significant departure from previous methods that have been constrained to mapping circuits onto a fixed processor topology. Experiments demonstrate that we have achieved notable enhancements in circuit performance, with a minimum of 20\% reduction in circuit depth in 60\% of the cases examined, and a maximum enhancement of up to 46\%. Furthermore, the pronounced benefits of our approach in reducing circuit depth become increasingly evident as the scale of the quantum circuits increases, exhibiting the scalability of our method in terms of problem size. This work advances the co-design of quantum processor architecture and algorithm mapping, offering a promising avenue for future research and development in the field. 

**Abstract (ZH)**: 量子计算有望革新多个领域，然而执行量子程序需要一个有效的编译过程，这涉及到将量子电路战略性地映射到量子处理器的物理量子比特上。量子比特的排列，或拓扑结构，对电路的性能至关重要，这一因素往往由于其复杂性使得传统启发式或手动优化方法难以奏效。在这项研究中，我们引入了一种新的方法，利用强化学习动态地调整量子比特的拓扑结构以满足不同量子电路的独特要求，指导基于算法的量子处理器拓扑设计，以降低映射电路的深度，这对于嘈杂量子处理器的输出准确性尤为关键。我们的方法在之前局限于固定处理器拓扑的映射方法中做出了重大突破。实验结果显示，我们在电路性能方面取得了显著提升，60% 案例中实现了至少20%的电路深度减少，最大提升幅度达到46%。此外，随着量子电路规模的增加，我们方法在降低电路深度方面的明显优势越来越明显，这表明了我们的方法在处理问题规模方面的可扩展性。这项工作推进了量子处理器架构与算法映射的协同设计，为未来该领域的研究和发展提供了令人鼓舞的途径。 

---
# M$^3$-VOS: Multi-Phase, Multi-Transition, and Multi-Scenery Video Object Segmentation 

**Title (ZH)**: M$^3$-VOS：多阶段、多过渡和多场景视频对象分割 

**Authors**: Zixuan Chen, Jiaxin Li, Liming Tan, Yejie Guo, Junxuan Liang, Cewu Lu, Yonglu Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.13803)  

**Abstract**: Intelligent robots need to interact with diverse objects across various environments. The appearance and state of objects frequently undergo complex transformations depending on the object properties, e.g., phase transitions. However, in the vision community, segmenting dynamic objects with phase transitions is overlooked. In light of this, we introduce the concept of phase in segmentation, which categorizes real-world objects based on their visual characteristics and potential morphological and appearance changes. Then, we present a new benchmark, Multi-Phase, Multi-Transition, and Multi-Scenery Video Object Segmentation (M3-VOS), to verify the ability of models to understand object phases, which consists of 479 high-resolution videos spanning over 10 distinct everyday scenarios. It provides dense instance mask annotations that capture both object phases and their transitions. We evaluate state-of-the-art methods on M3-VOS, yielding several key insights. Notably, current appearance based approaches show significant room for improvement when handling objects with phase transitions. The inherent changes in disorder suggest that the predictive performance of the forward entropy-increasing process can be improved through a reverse entropy-reducing process. These findings lead us to propose ReVOS, a new plug-and-play model that improves its performance by reversal refinement. Our data and code will be publicly available 

**Abstract (ZH)**: 智能机器人需要在各种环境下与多样化的物体进行交互。物体的外观和状态常会根据物体的特性发生复杂的变换，例如相变。然而，在视觉领域中，分割具有相变的动态物体却常常被忽视。鉴于此，我们引入了相变的概念，基于物体的视觉特征及其潜在的形态和外观变化对其进行分类。然后，我们提出了一个新的基准数据集——多相变、多状态、多场景视频物体分割（M3-VOS），以验证模型理解物体相变的能力。该数据集包含479个高分辨率视频，涵盖了10种不同日常场景，提供了密集的实例掩码注释，能够捕捉物体及其状态变换。我们在M3-VOS上评估了现有的最先进的方法，得出了一些重要的见解。值得注意的是，当前基于外观的方法在处理具有相变的物体时显示出很大的改进空间。内在的无序变化表明，通过逆转熵减过程可以提高前方熵增加过程的预测性能。这些发现促使我们提出ReVOS，这是一种新的即插即用模型，通过逆转精炼来提高其性能。我们的数据和代码将在开源平台上提供。 

---
# Enhancing Rhetorical Figure Annotation: An Ontology-Based Web Application with RAG Integration 

**Title (ZH)**: 基于本体的增强修辞figure标注：结合RAG的网络应用 

**Authors**: Ramona Kühn, Jelena Mitrović, Michael Granitzer  

**Link**: [PDF](https://arxiv.org/pdf/2412.13799)  

**Abstract**: Rhetorical figures play an important role in our communication. They are used to convey subtle, implicit meaning, or to emphasize statements. We notice them in hate speech, fake news, and propaganda. By improving the systems for computational detection of rhetorical figures, we can also improve tasks such as hate speech and fake news detection, sentiment analysis, opinion mining, or argument mining. Unfortunately, there is a lack of annotated data, as well as qualified annotators that would help us build large corpora to train machine learning models for the detection of rhetorical figures. The situation is particularly difficult in languages other than English, and for rhetorical figures other than metaphor, sarcasm, and irony. To overcome this issue, we develop a web application called "Find your Figure" that facilitates the identification and annotation of German rhetorical figures. The application is based on the German Rhetorical ontology GRhOOT which we have specially adapted for this purpose. In addition, we improve the user experience with Retrieval Augmented Generation (RAG). In this paper, we present the restructuring of the ontology, the development of the web application, and the built-in RAG pipeline. We also identify the optimal RAG settings for our application. Our approach is one of the first to practically use rhetorical ontologies in combination with RAG and shows promising results. 

**Abstract (ZH)**: 修辞手法在我们的沟通中扮演着重要角色。它们用于传达微妙的、隐含的意义，或强调陈述。我们常在仇恨言论、假新闻和宣传中注意到它们的存在。通过改进对修辞手法计算检测系统的开发，我们也可以提高仇恨言论和假新闻检测、情感分析、意见挖掘或论据挖掘等任务的效果。可惜的是，现有标注数据及其合格的标注者相对不足，这妨碍了我们建立用于训练检测修辞手法的机器学习模型的大规模语料库。特别是在非英语语言中，以及对于除隐喻、讽刺和反讽之外的其他修辞手法，情况更为困难。为解决这个问题，我们开发了一个名为“Find your Figure”的网络应用，以促进对德国修辞手法的识别和标注。该应用基于我们特别为此目的调整过的德语修辞学本体论GRhOOT。此外，我们使用检索增强生成（RAG）来改善用户体验。在本文中，我们介绍了本体论的重新结构化、网络应用的开发以及内置的RAG流水线。我们还确定了适用于我们应用的最佳RAG参数设置。我们的方法是首次将修辞本体论与RAG实际结合使用的方法之一，并显示出有希望的结果。 

---
# Mix-LN: Unleashing the Power of Deeper Layers by Combining Pre-LN and Post-LN 

**Title (ZH)**: Mix-LN：结合预层归一化和后层归一化的深层层潜力释放 

**Authors**: Pengxiang Li, Lu Yin, Shiwei Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13795)  

**Abstract**: Large Language Models (LLMs) have achieved remarkable success, yet recent findings reveal that their deeper layers often contribute minimally and can be pruned without affecting overall performance. While some view this as an opportunity for model compression, we identify it as a training shortfall rooted in the widespread use of Pre-Layer Normalization (Pre-LN). We demonstrate that Pre-LN, commonly employed in models like GPT and LLaMA, leads to diminished gradient norms in its deeper layers, reducing their effectiveness. In contrast, Post-Layer Normalization (Post-LN) preserves larger gradient norms in deeper layers but suffers from vanishing gradients in earlier layers. To address this, we introduce Mix-LN, a novel normalization technique that combines the strengths of Pre-LN and Post-LN within the same model. Mix-LN applies Post-LN to the earlier layers and Pre-LN to the deeper layers, ensuring more uniform gradients across layers. This allows all parts of the network--both shallow and deep layers--to contribute effectively to training. Extensive experiments with various model sizes from 70M to 7B demonstrate that Mix-LN consistently outperforms both Pre-LN and Post-LN, promoting more balanced, healthier gradient norms throughout the network, and enhancing the overall quality of LLM pre-training. Furthermore, we demonstrate that models pre-trained with Mix-LN learn better compared to those using Pre-LN or Post-LN during supervised fine-tuning (SFT) and reinforcement learning from human feedback (RLHF), highlighting the critical importance of high-quality deep layers. By effectively addressing the inefficiencies of deep layers in current LLMs, Mix-LN unlocks their potential, enhancing model capacity without increasing model size. Our code is available at this https URL. 

**Abstract (ZH)**: 大型语言模型（LLMs）已经取得了显著的成功，但近期的研究发现，其深层次的层通常贡献甚微，且可以通过剪枝而不影响整体性能。尽管有人认为这是模型压缩的机会，但我们将其视为训练上的不足，根源在于广泛使用的前置层归一化（Pre-LN）方法。我们证明，Pre-LN，广泛应用于GPT和LaLaMA等模型中，会导致其深层次层的梯度模量减小，从而降低这些层的有效性。相比之下，后置层归一化（Post-LN）能够保持深层次层中较大的梯度模量，但早期层中的梯度消失问题较为严重。为了解决这一问题，我们提出了一种新的归一化技术——Mix-LN（混合层归一化），它在同一个模型中结合了Pre-LN和Post-LN的优点。Mix-LN应用Post-LN到早期层，Pre-LN应用到深层次层，确保各层之间梯度分布更加均匀。这使得网络的各个部分——无论是浅层还是深层层——都能够有效参与训练。通过各种从70M到7B规模的不同模型大小的广泛实验，我们发现Mix-LN始终优于Pre-LN和Post-LN，促进了网络中梯度模量的更均衡和健康，从而提升了LLM预训练的整体质量。此外，我们还展示了使用Mix-LN预先训练的模型在监督微调（SFT）和基于人类反馈的强化学习（RLHF）中学习效果更好，强调了高质量深层层的重要性。通过有效解决当前LLM中深层层的效率问题，Mix-LN解锁了它们的潜力，提高了模型能力而不增加模型大小。我们的代码可在以下链接获取：[此处提供具体链接]。 

---
# MATCHED: Multimodal Authorship-Attribution To Combat Human Trafficking in Escort-Advertisement Data 

**Title (ZH)**: MATCHED：多模态作者归属性分析以打击陪侍广告数据中的人类人口贩卖问题 

**Authors**: Vageesh Saxena, Benjamin Bashpole, Gijs Van Dijck, Gerasimos Spanakis  

**Link**: [PDF](https://arxiv.org/pdf/2412.13794)  

**Abstract**: Human trafficking (HT) remains a critical issue, with traffickers increasingly leveraging online escort advertisements (ads) to advertise victims anonymously. Existing detection methods, including Authorship Attribution (AA), often center on text-based analyses and neglect the multimodal nature of online escort ads, which typically pair text with images. To address this gap, we introduce MATCHED, a multimodal dataset of 27,619 unique text descriptions and 55,115 unique images collected from the Backpage escort platform across seven U.S. cities in four geographical regions. Our study extensively benchmarks text-only, vision-only, and multimodal baselines for vendor identification and verification tasks, employing multitask (joint) training objectives that achieve superior classification and retrieval performance on in-distribution and out-of-distribution (OOD) datasets. Integrating multimodal features further enhances this performance, capturing complementary patterns across text and images. While text remains the dominant modality, visual data adds stylistic cues that enrich model performance. Moreover, text-image alignment strategies like CLIP and BLIP2 struggle due to low semantic overlap and vague connections between the modalities of escort ads, with end-to-end multimodal training proving more robust. Our findings emphasize the potential of multimodal AA (MAA) to combat HT, providing LEAs with robust tools to link ads and disrupt trafficking networks. 

**Abstract (ZH)**: 人口贩卖（HT）依然是一个关键问题，贩子们越来越多地利用在线陪侍广告（广告）来匿名宣传受害者。现有的检测方法，包括作者归因（AA），通常集中在基于文本的分析上，而忽视了在线陪侍广告的多模态性质，这些广告通常包含文本与图像的组合。为了解决这一问题，我们引入了MATCHED，这是一个包含27,619个独特文本描述和55,115个独特图像的多模态数据集，这些数据是从美国四个地理区域七个城市的Backpage陪侍平台上收集的。我们的研究广泛地对文本仅、视觉仅和多模态基线进行了基准测试，这些基线应用于供应商识别和验证任务，并采用了多任务（联合）训练目标，这些目标在分布内和分布外（OOD）数据集上实现了更好的分类和检索性能。进一步整合多模态特征可以进一步提高性能，捕捉文本和图像之间的互补模式。虽然文本仍然是主要的模态，但视觉数据提供了有助于增强模型性能的风格特征。此外，用于文本-图像对齐的CLIP和BLIP2策略由于陪侍广告模态间较低的语义重叠和模糊连接而受到挑战，端到端多模态训练显得更为稳健。我们的研究结果强调了多模态AA（MAA）解决HT问题的潜力，为执法机构提供了有力工具来关联广告并中断贩运网络。 

---
# Meta-Reflection: A Feedback-Free Reflection Learning Framework 

**Title (ZH)**: 元反思：一种无反馈的反射学习框架 

**Authors**: Yaoke Wang, Yun Zhu, Xintong Bao, Wenqiao Zhang, Suyang Dai, Kehan Chen, Wenqiang Li, Gang Huang, Siliang Tang, Yueting Zhuang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13781)  

**Abstract**: Despite the remarkable capabilities of large language models (LLMs) in natural language understanding and reasoning, they often display undesirable behaviors, such as generating hallucinations and unfaithful reasoning. A prevalent strategy to mitigate these issues is the use of reflection, which refines responses through an iterative process. However, while promising, reflection heavily relies on high-quality external feedback and requires iterative multi-agent inference processes, thus hindering its practical application. In this paper, we propose Meta-Reflection, a novel feedback-free reflection mechanism that necessitates only a single inference pass without external feedback. Motivated by the human ability to remember and retrieve reflections from past experiences when encountering similar problems, Meta-Reflection integrates reflective insights into a codebook, allowing the historical insights to be stored, retrieved, and used to guide LLMs in problem-solving. To thoroughly investigate and evaluate the practicality of Meta-Reflection in real-world scenarios, we introduce an industrial e-commerce benchmark named E-commerce Customer Intent Detection (ECID). Extensive experiments conducted on both public datasets and the ECID benchmark highlight the effectiveness and efficiency of our proposed approach. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）在自然语言理解和推理方面表现出色，它们常常表现出一些不期望的行为，例如生成幻觉和不忠实的推理。为了缓解这些问题，广泛采用的一种策略是利用反思，通过迭代过程来细化响应。然而，尽管前景光明，反思高度依赖高质量的外部反馈，并需要迭代的多智能体推理过程，这阻碍了其实用应用。本文提出了一种名为Meta-Reflection的新型反馈无关的反射机制，仅需一次推理过程而不需外部反馈。受到人类在遇到相似问题时能够回忆和应用过去经历的启示，Meta-Reflection将反射性洞察整合到代码书中，使得历史洞察可以被存储、检索，并用于引导LLMs进行问题解决。为了全面研究和评估Meta-Reflection在实际场景中的实用性，我们引入了一个工业电商基准——电商客户意图检测（ECID）。在公共数据集和ECID基准上的广泛实验展示了我们所提出方法的有效性和效率。 

---
# Semantic Convergence: Harmonizing Recommender Systems via Two-Stage Alignment and Behavioral Semantic Tokenization 

**Title (ZH)**: 语义收敛：通过两阶段对齐和行为语义词元化协调推荐系统 

**Authors**: Guanghan Li, Xun Zhang, Yufei Zhang, Yifan Yin, Guojun Yin, Wei Lin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13771)  

**Abstract**: Large language models (LLMs), endowed with exceptional reasoning capabilities, are adept at discerning profound user interests from historical behaviors, thereby presenting a promising avenue for the advancement of recommendation systems. However, a notable discrepancy persists between the sparse collaborative semantics typically found in recommendation systems and the dense token representations within LLMs. In our study, we propose a novel framework that harmoniously merges traditional recommendation models with the prowess of LLMs. We initiate this integration by transforming ItemIDs into sequences that align semantically with the LLMs space, through the proposed Alignment Tokenization module. Additionally, we design a series of specialized supervised learning tasks aimed at aligning collaborative signals with the subtleties of natural language semantics. To ensure practical applicability, we optimize online inference by pre-caching the top-K results for each user, reducing latency and improving effciency. Extensive experimental evidence indicates that our model markedly improves recall metrics and displays remarkable scalability of recommendation systems. 

**Abstract (ZH)**: 大型语言模型（LLMs）凭借其卓越的推理能力，能够从用户的 histórico 行为中识别出深层次的兴趣，从而为推荐系统的发展提供了有前途的途径。然而，推荐系统中通常存在的稀疏协作语义与LLMs中丰富的令牌表示之间仍然存在显著的差异。在我们的研究中，我们提出了一种新的框架，该框架以和谐的方式结合了传统的推荐模型与LLMs的优势。我们通过引入 Alignment Tokenization 模块，将ItemIDs转换为与LLMs空间相匹配的语义序列，从而开始了这种整合。此外，我们设计了一系列专门的监督学习任务，旨在将协作信号与自然语言语义的细微差别进行对齐。为了确保其实用性，我们通过预缓存每个用户的前K个结果来进行在线推理优化，减少了延迟并提高了效率。广泛的实验证据表明，我们的模型显著提高了召回率指标，并且展示了推荐系统的卓越可伸缩性。 

---
# QuLTSF: Long-Term Time Series Forecasting with Quantum Machine Learning 

**Title (ZH)**: QuLTSF：量子机器学习用于长 term 时间序列预测 

**Authors**: Hari Hara Suthan Chittoor, Paul Robert Griffin, Ariel Neufeld, Jayne Thompson, Mile Gu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13769)  

**Abstract**: Long-term time series forecasting (LTSF) involves predicting a large number of future values of a time series based on the past values and is an essential task in a wide range of domains including weather forecasting, stock market analysis, disease outbreak prediction. Over the decades LTSF algorithms have transitioned from statistical models to deep learning models like transformer models. Despite the complex architecture of transformer based LTSF models `Are Transformers Effective for Time Series Forecasting? (Zeng et al., 2023)' showed that simple linear models can outperform the state-of-the-art transformer based LTSF models. Recently, quantum machine learning (QML) is evolving as a domain to enhance the capabilities of classical machine learning models. In this paper we initiate the application of QML to LTSF problems by proposing QuLTSF, a simple hybrid QML model for multivariate LTSF. Through extensive experiments on a widely used weather dataset we show the advantages of QuLTSF over the state-of-the-art classical linear models, in terms of reduced mean squared error and mean absolute error. 

**Abstract (ZH)**: 长时序列预测（Long-term Time Series Forecasting, LTSF）涉及基于过去值预测时间序列的大量未来值，是天气预报、股市分析和疾病爆发预测等广泛领域中的一个关键任务。几十年来，LTSF算法从统计模型发展到了深度学习模型，如变压器模型。尽管基于变压器模型的LTSF架构极为复杂，但Zeng等人（2023）的研究“Are Transformers Effective for Time Series Forecasting?”表明简单的线性模型可以超过最先进的基于变压器的LTSF模型。最近，量子机器学习（Quantum Machine Learning, QML）正在成为一个领域，以提升经典机器学习模型的能力。本文通过提出QuLTSF，一个简单的混合量子机器学习模型，初步应用QML技术解决多变量LTSF问题。通过在广泛使用的天气数据集中进行广泛的实验，我们展示了QuLTSF在减少均方误差和平均绝对误差方面优于最先进的经典线性模型的优势。 

---
# LLM-SEM: A Sentiment-Based Student Engagement Metric Using LLMS for E-Learning Platforms 

**Title (ZH)**: LLM-SEM：一种基于情感的学生参与度指标，使用LLM（大型语言模型）评估在线教育平台的学生参与情况 

**Authors**: Ali Hamdi, Ahmed Abdelmoneim Mazrou, Mohamed Shaltout  

**Link**: [PDF](https://arxiv.org/pdf/2412.13765)  

**Abstract**: Current methods for analyzing student engagement in e-learning platforms, including automated systems, often struggle with challenges such as handling fuzzy sentiment in text comments and relying on limited metadata. Traditional approaches, such as surveys and questionnaires, also face issues like small sample sizes and scalability. In this paper, we introduce LLM-SEM (Language Model-Based Student Engagement Metric), a novel approach that leverages video metadata and sentiment analysis of student comments to measure engagement. By utilizing recent Large Language Models (LLMs), we generate high-quality sentiment predictions to mitigate text fuzziness and normalize key features such as views and likes. Our holistic method combines comprehensive metadata with sentiment polarity scores to gauge engagement at both the course and lesson levels. Extensive experiments were conducted to evaluate various LLM models, demonstrating the effectiveness of LLM-SEM in providing a scalable and accurate measure of student engagement. We fine-tuned LLMs, including AraBERT, TXLM-RoBERTa, LLama 3B and Gemma 9B from Ollama, using human-annotated sentiment datasets to enhance prediction accuracy. 

**Abstract (ZH)**: 当前用于分析在线学习平台中学生参与度的方法，包括自动化系统，往往面临处理文本评论中的模糊情感和依赖有限元数据的挑战。传统的调查问卷方法也存在样本量小和可扩展性差的问题。本文提出了一种名为LLM-SEM（基于语言模型的学生参与度指标）的新颖方法，该方法利用视频元数据和学生评论的情感分析来衡量参与度。通过使用最新的大语言模型（LLMs），我们生成高质量的情感预测以减轻文本模糊性，并标准化视图和点赞等关键特征。我们综合的方法结合了全面的元数据和情感极性评分，以在课程和课节层面衡量参与度。进行了广泛的实验来评估各种LLM模型，展示了LLM-SEM在提供具有扩展性和准确性的学生参与度测量方面的有效性。我们对包括AraBERT、TXLM-RoBERTa、LLama 3B和Ollama的Gemma 9B在内的LLMs进行了微调，使用人工标注的情感数据集来提高预测准确性。 

---
# RAG-RewardBench: Benchmarking Reward Models in Retrieval Augmented Generation for Preference Alignment 

**Title (ZH)**: RAG-RewardBench: 在检索增强生成中对奖励模型进行偏好对齐基准测试 

**Authors**: Zhuoran Jin, Hongbang Yuan, Tianyi Men, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13746)  

**Abstract**: Despite the significant progress made by existing retrieval augmented language models (RALMs) in providing trustworthy responses and grounding in reliable sources, they often overlook effective alignment with human preferences. In the alignment process, reward models (RMs) act as a crucial proxy for human values to guide optimization. However, it remains unclear how to evaluate and select a reliable RM for preference alignment in RALMs. To this end, we propose RAG-RewardBench, the first benchmark for evaluating RMs in RAG settings. First, we design four crucial and challenging RAG-specific scenarios to assess RMs, including multi-hop reasoning, fine-grained citation, appropriate abstain, and conflict robustness. Then, we incorporate 18 RAG subsets, six retrievers, and 24 RALMs to increase the diversity of data sources. Finally, we adopt an LLM-as-a-judge approach to improve preference annotation efficiency and effectiveness, exhibiting a strong correlation with human annotations. Based on the RAG-RewardBench, we conduct a comprehensive evaluation of 45 RMs and uncover their limitations in RAG scenarios. Additionally, we also reveal that existing trained RALMs show almost no improvement in preference alignment, highlighting the need for a shift towards preference-aligned this http URL release our benchmark and code publicly at this https URL for future work. 

**Abstract (ZH)**: 尽管现有的检索增强语言模型（RALMs）在提供可靠响应和基于可靠来源的基础上取得了显著进展，但它们往往忽略了与人类偏好有效对齐的问题。在对齐过程中，奖励模型（RMs）作为人类价值观的关键代理来引导优化。然而，如何评估和选择适合偏好对齐的可靠RM仍未明确。为此，我们提出了RAG-RewardBench，这是首个用于评估RMs的基准测试。首先，我们设计了四个关键且具有挑战性的RAG特定场景来评估RMs，包括多跳推理、精细引用、适当规避和冲突稳健性。然后，我们结合了18个RAG子集、六种检索器和24个RALMs，以增加数据源的多样性。最后，我们采用了一种LLM作为裁判的方法来提高偏好注释的效率和效果，表现出较强的人类注释相关性。基于RAG-RewardBench，我们对45个RMs进行了全面评估，并揭示了它们在RAG场景中的局限性。此外，我们还发现，现有的训练过的RALMs在偏好对齐方面几乎没有改进，这突显了转向偏好对齐的必要性。我们还将在未来的工作中公开发布该基准和代码，地址为[this https URL]。 

---
# Uncertainty separation via ensemble quantile regression 

**Title (ZH)**: 通过集合分位数回归进行不确定性分离 

**Authors**: Navid Ansari, Hans-Peter Seidel, Vahid Babaei  

**Link**: [PDF](https://arxiv.org/pdf/2412.13738)  

**Abstract**: This paper introduces a novel and scalable framework for uncertainty estimation and separation with applications in data driven modeling in science and engineering tasks where reliable uncertainty quantification is critical. Leveraging an ensemble of quantile regression (E-QR) models, our approach enhances aleatoric uncertainty estimation while preserving the quality of epistemic uncertainty, surpassing competing methods, such as Deep Ensembles (DE) and Monte Carlo (MC) dropout. To address challenges in separating uncertainty types, we propose an algorithm that iteratively improves separation through progressive sampling in regions of high uncertainty. Our framework is scalable to large datasets and demonstrates superior performance on synthetic benchmarks, offering a robust tool for uncertainty quantification in data-driven applications. 

**Abstract (ZH)**: 本文介绍了一种新颖且可扩展的框架，用于不确定性估计与分离，并将其应用于科学与工程任务中的数据驱动建模，其中可靠的不确定性量化是至关重要的。利用集成分位数回归模型（E-QR），我们的方法提高了 aleatoric 不确定性的估计，同时保持了 epistemic 不确定性的质量，超越了现有的方法，如深度集成（DE）和蒙特卡洛 （MC）丢弃。为了解决不同类型不确定性分离的挑战，我们提出了一个算法，通过在高不确定性区域进行逐步采样来不断改进分离。我们的框架适用于大规模数据集，并在合成基准测试中表现出优越的性能，为数据驱动应用提供了稳健的不确定性量化工具。 

---
# On the Compression of Language Models for Code: An Empirical Study on CodeBERT 

**Title (ZH)**: 关于代码中语言模型压缩的研究：CodeBERT 的实证研究

解析：
- "On the Compression of Language Models for Code" 翻译为 "关于代码中语言模型压缩的研究"
- "An Empirical Study on CodeBERT" 翻译为 "CodeBERT 的实证研究"

这样的翻译在学术文章标题中既准确又符合中文表达习惯。 

**Authors**: Giordano d'Aloisio, Luca Traini, Federica Sarro, Antinisca Di Marco  

**Link**: [PDF](https://arxiv.org/pdf/2412.13737)  

**Abstract**: Language models have proven successful across a wide range of software engineering tasks, but their significant computational costs often hinder their practical adoption. To address this challenge, researchers have begun applying various compression strategies to improve the efficiency of language models for code. These strategies aim to optimize inference latency and memory usage, though often at the cost of reduced model effectiveness. However, there is still a significant gap in understanding how these strategies influence the efficiency and effectiveness of language models for code. Here, we empirically investigate the impact of three well-known compression strategies -- knowledge distillation, quantization, and pruning -- across three different classes of software engineering tasks: vulnerability detection, code summarization, and code search. Our findings reveal that the impact of these strategies varies greatly depending on the task and the specific compression method employed. Practitioners and researchers can use these insights to make informed decisions when selecting the most appropriate compression strategy, balancing both efficiency and effectiveness based on their specific needs. 

**Abstract (ZH)**: 语言模型在各种软件工程任务中已经证明非常成功，但它们显著的计算成本往往阻碍了它们的实际应用。为了解决这一挑战，研究人员已经开始应用各种压缩策略，以提高语言模型处理代码的效率。这些策略旨在优化推理延迟和内存使用，虽然通常会牺牲模型的效果。然而，关于这些策略如何影响语言模型处理代码的效率和效果，我们仍然缺乏深刻的理解。在这里，我们通过实证研究探讨了三种广为人知的压缩策略——知识蒸馏、量化和剪枝——对三种不同类别的软件工程任务的影响：漏洞检测、代码总结和代码搜索。我们的研究结果显示，这些策略的影响在任务以及所采用的具体压缩方法上存在很大的差异。从业者和研究人员可以根据这些发现，基于他们特定的需求，做出明智的选择，平衡效率和效果之间的关系。 

---
# Federated Learning and RAG Integration: A Scalable Approach for Medical Large Language Models 

**Title (ZH)**: 联邦学习与RAG集成：一种可扩展的医疗大型语言模型方法 

**Authors**: Jincheol Jung, Hongju Jeong, Eui-Nam Huh  

**Link**: [PDF](https://arxiv.org/pdf/2412.13720)  

**Abstract**: This study analyzes the performance of domain-specific Large Language Models (LLMs) for the medical field by integrating Retrieval-Augmented Generation (RAG) systems within a federated learning framework. Leveraging the inherent advantages of federated learning, such as preserving data privacy and enabling distributed computation, this research explores the integration of RAG systems with models trained under varying client configurations to optimize performance. Experimental results demonstrate that the federated learning-based models integrated with RAG systems consistently outperform their non-integrated counterparts across all evaluation metrics. This study highlights the potential of combining federated learning and RAG systems for developing domain-specific LLMs in the medical field, providing a scalable and privacy-preserving solution for enhancing text generation capabilities. 

**Abstract (ZH)**: 本文通过将检索增强生成（RAG）系统整合到联邦学习框架中，分析了特定领域的大型语言模型（LLMs）在医疗领域的性能。利用联邦学习固有的优势，如数据隐私保护和分布式计算能力，本研究探讨了在不同客户端配置下将RAG系统与训练模型集成以优化性能的方法。实验结果表明，基于联邦学习并整合了RAG系统的模型在所有评估指标上都优于未集成RAG系统的模型。本文强调了将联邦学习与RAG系统结合开发医疗特定领域LLMs的潜力，提供了一种可扩展且保护隐私的解决方案，以提高文本生成能力。 

---
# Mitigating Adversarial Attacks in LLMs through Defensive Suffix Generation 

**Title (ZH)**: 通过防御性后缀生成减轻大语言模型中的 adversarial 攻击 

**Authors**: Minkyoung Kim, Yunha Kim, Hyeram Seo, Heejung Choi, Jiye Han, Gaeun Kee, Soyoung Ko, HyoJe Jung, Byeolhee Kim, Young-Hak Kim, Sanghyun Park, Tae Joon Jun  

**Link**: [PDF](https://arxiv.org/pdf/2412.13705)  

**Abstract**: Large language models (LLMs) have exhibited outstanding performance in natural language processing tasks. However, these models remain susceptible to adversarial attacks in which slight input perturbations can lead to harmful or misleading outputs. A gradient-based defensive suffix generation algorithm is designed to bolster the robustness of LLMs. By appending carefully optimized defensive suffixes to input prompts, the algorithm mitigates adversarial influences while preserving the models' utility. To enhance adversarial understanding, a novel total loss function ($L_{\text{total}}$) combining defensive loss ($L_{\text{def}}$) and adversarial loss ($L_{\text{adv}}$) generates defensive suffixes more effectively. Experimental evaluations conducted on open-source LLMs such as Gemma-7B, mistral-7B, Llama2-7B, and Llama2-13B show that the proposed method reduces attack success rates (ASR) by an average of 11\% compared to models without defensive suffixes. Additionally, the perplexity score of Gemma-7B decreased from 6.57 to 3.93 when applying the defensive suffix generated by openELM-270M. Furthermore, TruthfulQA evaluations demonstrate consistent improvements with Truthfulness scores increasing by up to 10\% across tested configurations. This approach significantly enhances the security of LLMs in critical applications without requiring extensive retraining. 

**Abstract (ZH)**: 大语言模型（LLMs）在自然语言处理任务中表现出色。然而，这些模型仍然容易受到对抗攻击的影响，轻微的输入扰动可能导致有害或误导性的输出。设计了一种基于梯度的防御后缀生成算法以增强LLMs的鲁棒性。通过在输入提示后面附加精心优化的防御后缀，该算法减轻了对抗性影响，同时保留了模型的效用。为了增强对抗性理解，提出了一种新的总损失函数($L_{\text{total}}$)，该函数结合了防御损失($L_{\text{def}}$)和对抗损失($L_{\text{adv}}$)，从而更有效地生成防御后缀。实验评估在开源LLM（如Gemma-7B、mistral-7B、Llama2-7B和Llama2-13B）上进行，结果显示，与没有防御后缀的模型相比，所提出的方法将攻击成功率（ASR）平均降低了11%。此外，应用来自openELM-270M的防御后缀后，Gemma-7B的困惑度得分从6.57降至3.93。进一步的TruthfulQA评估表明，在测试的各种配置中，忠实性得分平均提高了10%。这一方法在增强LLMs在关键应用中的安全性方面显著有效，而无需进行大量重新训练。 

---
# Typhoon 2: A Family of Open Text and Multimodal Thai Large Language Models 

**Title (ZH)**: 台风 2：一套开源文本和多模态 Thai 大型语言模型 

**Authors**: Kunat Pipatanakul, Potsawee Manakul, Natapong Nitarach, Warit Sirichotedumrong, Surapon Nonesung, Teetouch Jaknamon, Parinthapat Pengpun, Pittawat Taveekitworachai, Adisai Na-Thalang, Sittipong Sripaisarnmongkol, Krisanapong Jirayoot, Kasima Tharnpipitchai  

**Link**: [PDF](https://arxiv.org/pdf/2412.13702)  

**Abstract**: This paper introduces Typhoon 2, a series of text and multimodal large language models optimized for the Thai language. The series includes models for text, vision, and audio. Typhoon2-Text builds on state-of-the-art open models, such as Llama 3 and Qwen2, and we perform continual pre-training on a mixture of English and Thai data. We employ various post-training techniques to enhance Thai language performance while preserving the base models' original capabilities. We release text models across a range of sizes, from 1 to 70 billion parameters, available in both base and instruction-tuned variants. Typhoon2-Vision improves Thai document understanding while retaining general visual capabilities, such as image captioning. Typhoon2-Audio introduces an end-to-end speech-to-speech model architecture capable of processing audio, speech, and text inputs and generating both text and speech outputs simultaneously. 

**Abstract (ZH)**: 本文介绍了Typhoon 2系列，该系列是针对泰语优化的大型语言模型和多模态模型。该系列涵盖了文本、视觉和音频模型。Typhoon2-Text建立在最新的开源模型之上，如Llama 3和Qwen2，并在英语和泰语数据的混合集上进行了持续预训练。我们采用多种后训练技术来增强泰语文本的表现，同时保留基础模型的原始能力。我们发布了从1亿到70亿参数不等的各种大小的文本模型，提供基础版和指令调优版本。Typhoon2-Vision在保留一般视觉能力（如图像字幕生成）的同时，增强了对泰语文档的理解能力。Typhoon2-Audio引入了一种端到端的语音到语音模型架构，能够处理音频、语音和文本输入，并同时生成文本和语音输出。 

---
# Clio: Privacy-Preserving Insights into Real-World AI Use 

**Title (ZH)**: Clio：隐私保护下的现实世界AI应用洞察 

**Authors**: Alex Tamkin, Miles McCain, Kunal Handa, Esin Durmus, Liane Lovitt, Ankur Rathi, Saffron Huang, Alfred Mountfield, Jerry Hong, Stuart Ritchie, Michael Stern, Brian Clarke, Landon Goldberg, Theodore R. Sumers, Jared Mueller, William McEachen, Wes Mitchell, Shan Carter, Jack Clark, Jared Kaplan, Deep Ganguli  

**Link**: [PDF](https://arxiv.org/pdf/2412.13678)  

**Abstract**: How are AI assistants being used in the real world? While model providers in theory have a window into this impact via their users' data, both privacy concerns and practical challenges have made analyzing this data difficult. To address these issues, we present Clio (Claude insights and observations), a privacy-preserving platform that uses AI assistants themselves to analyze and surface aggregated usage patterns across millions of conversations, without the need for human reviewers to read raw conversations. We validate this can be done with a high degree of accuracy and privacy by conducting extensive evaluations. We demonstrate Clio's usefulness in two broad ways. First, we share insights about how models are being used in the real world from one million this http URL Free and Pro conversations, ranging from providing advice on hairstyles to providing guidance on Git operations and concepts. We also identify the most common high-level use cases on this http URL (coding, writing, and research tasks) as well as patterns that differ across languages (e.g., conversations in Japanese discuss elder care and aging populations at higher-than-typical rates). Second, we use Clio to make our systems safer by identifying coordinated attempts to abuse our systems, monitoring for unknown unknowns during critical periods like launches of new capabilities or major world events, and improving our existing monitoring systems. We also discuss the limitations of our approach, as well as risks and ethical concerns. By enabling analysis of real-world AI usage, Clio provides a scalable platform for empirically grounded AI safety and governance. 

**Abstract (ZH)**: AI 助手在现实世界中的应用情况如何？虽然模型提供商理论上可以通过用户数据一窥这一影响，但隐私顾虑和技术挑战使得分析这些数据变得困难。为解决这些问题，我们提出了一种名为 Clio（Claude 观察与洞察）的隐私保护平台，该平台利用 AI 助手本身在数百万次对话中分析和揭示聚合使用模式，无需人工审阅原始对话。我们通过广泛的评估验证了这种做法在高准确性和高隐私性方面的可行性。我们以两种广泛的方式展示了 Clio 的实用价值。首先，我们从一百万次 Free 和 Pro 会话中分享了有关模型在现实世界中的使用情况的见解，范围从提供发型建议到提供 Git 操作和概念指导。我们还确定了这类会话中常见的一级应用场景（如编码、写作和研究任务），以及不同语言中会话模式的不同之处（例如，日语会话中关于养老和老年群体的讨论频率更高）。其次，我们利用 Clio 提升系统的安全性，识别系统滥用的协调尝试，监控关键时期（如新增功能或重大世界事件）期间的未知风险，并改进现有的监控系统。我们还讨论了该方法的局限性以及相关风险和伦理问题。通过允许对实际 AI 使用情况进行分析，Clio 提供了一个基于实证的可扩展平台，用于 AI 安全和治理。 

---
# Exploring Multi-Modal Integration with Tool-Augmented LLM Agents for Precise Causal Discovery 

**Title (ZH)**: 借助工具增强的多模态LLM代理进行精确因果发现的研究 

**Authors**: ChengAo Shen, Zhengzhang Chen, Dongsheng Luo, Dongkuan Xu, Haifeng Chen, Jingchao Ni  

**Link**: [PDF](https://arxiv.org/pdf/2412.13667)  

**Abstract**: Causal inference is an imperative foundation for decision-making across domains, such as smart health, AI for drug discovery and AIOps. Traditional statistical causal discovery methods, while well-established, predominantly rely on observational data and often overlook the semantic cues inherent in cause-and-effect relationships. The advent of Large Language Models (LLMs) has ushered in an affordable way of leveraging the semantic cues for knowledge-driven causal discovery, but the development of LLMs for causal discovery lags behind other areas, particularly in the exploration of multi-modality data. To bridge the gap, we introduce MATMCD, a multi-agent system powered by tool-augmented LLMs. MATMCD has two key agents: a Data Augmentation agent that retrieves and processes modality-augmented data, and a Causal Constraint agent that integrates multi-modal data for knowledge-driven inference. Delicate design of the inner-workings ensures successful cooperation of the agents. Our empirical study across seven datasets suggests the significant potential of multi-modality enhanced causal discovery. 

**Abstract (ZH)**: 因果推断是跨领域决策的基础，包括智能健康、药物发现中的AI以及AIOps。传统的统计因果发现方法虽然已经成熟，但主要依赖于观察数据，常常忽视因果关系中固有的语义线索。大型语言模型（LLMs）的出现提供了一种利用语义线索进行知识驱动的因果发现的经济实惠方法，但因果发现领域的LLM开发滞后于其他领域，尤其是在多模态数据探索方面。为弥合这一差距，我们介绍了一种基于工具增强LLM的多代理系统MATMCD。MATMCD有两个关键代理：一个数据增强代理，用于检索和处理模态增强数据；一个因果约束代理，用于集成多模态数据以实现知识驱动的推理。代理内部设计的细致规划确保了它们的成功合作。我们在七个数据集上的实证研究表明，多模态增强的因果发现具有显著的潜力。 

---
# Evaluation of LLM Vulnerabilities to Being Misused for Personalized Disinformation Generation 

**Title (ZH)**: 对大型语言模型在生成个性化误导信息方面被滥用的脆弱性的评估 

**Authors**: Aneta Zugecova, Dominik Macko, Ivan Srba, Robert Moro, Jakub Kopal, Katarina Marcincinova, Matus Mesarcik  

**Link**: [PDF](https://arxiv.org/pdf/2412.13666)  

**Abstract**: The capabilities of recent large language models (LLMs) to generate high-quality content indistinguishable by humans from human-written texts rises many concerns regarding their misuse. Previous research has shown that LLMs can be effectively misused for generating disinformation news articles following predefined narratives. Their capabilities to generate personalized (in various aspects) content have also been evaluated and mostly found usable. However, a combination of personalization and disinformation abilities of LLMs has not been comprehensively studied yet. Such a dangerous combination should trigger integrated safety filters of the LLMs, if there are some. This study fills this gap by evaluation of vulnerabilities of recent open and closed LLMs, and their willingness to generate personalized disinformation news articles in English. We further explore whether the LLMs can reliably meta-evaluate the personalization quality and whether the personalization affects the generated-texts detectability. Our results demonstrate the need for stronger safety-filters and disclaimers, as those are not properly functioning in most of the evaluated LLMs. Additionally, our study revealed that the personalization actually reduces the safety-filter activations; thus effectively functioning as a jailbreak. Such behavior must be urgently addressed by LLM developers and service providers. 

**Abstract (ZH)**: 近年来大型语言模型（LLMs）生成高质量内容的能力已达到高度先进，这些内容难以由人类区分出自写文本，这引发了对其滥用的诸多担忧。以往的研究显示，LLMs可以有效地用于按照预定义的叙述生成虚假信息新闻文章。它们生成个性化内容的能力也被评估，并大部分发现是可利用的。然而，LLMs同时具备个性化和虚假信息生成能力的研究尚未全面展开。这种危险的结合应触发LLMs的安全过滤器的综合措施，假设存在着这样的安全过滤器。本研究通过评估近期的开放和封闭LLMs的脆弱性，以及它们生成个性化虚假信息新闻文章（使用英语）的意愿，填补了这一空白。我们进一步探讨了LLMs是否能够可靠地评估个性化质量，以及个性化对生成文本的可检测性是否有影响。研究结果表明，大多数评估的LLMs的安全过滤器和免责声明功能并未充分发挥作用，需要更强的安全过滤措施。此外，我们的研究发现个性化实际上降低了安全过滤器的激活率，起到了破坏防护的作用。这种行为必须由LLM开发人员和服务提供商紧急解决。 

---
# Smarter, Better, Faster, Longer: A Modern Bidirectional Encoder for Fast, Memory Efficient, and Long Context Finetuning and Inference 

**Title (ZH)**: 更聪明、更高效、更快捷、更持久：一种现代双向编码器，实现快速、内存高效以及长上下文的微调与推理 

**Authors**: Benjamin Warner, Antoine Chaffin, Benjamin Clavié, Orion Weller, Oskar Hallström, Said Taghadouini, Alexis Gallagher, Raja Biswas, Faisal Ladhak, Tom Aarsen, Nathan Cooper, Griffin Adams, Jeremy Howard, Iacopo Poli  

**Link**: [PDF](https://arxiv.org/pdf/2412.13663)  

**Abstract**: Encoder-only transformer models such as BERT offer a great performance-size tradeoff for retrieval and classification tasks with respect to larger decoder-only models. Despite being the workhorse of numerous production pipelines, there have been limited Pareto improvements to BERT since its release. In this paper, we introduce ModernBERT, bringing modern model optimizations to encoder-only models and representing a major Pareto improvement over older encoders. Trained on 2 trillion tokens with a native 8192 sequence length, ModernBERT models exhibit state-of-the-art results on a large pool of evaluations encompassing diverse classification tasks and both single and multi-vector retrieval on different domains (including code). In addition to strong downstream performance, ModernBERT is also the most speed and memory efficient encoder and is designed for inference on common GPUs. 

**Abstract (ZH)**: 以下是对所给内容的学术规范翻译：

与较大的解码器模型相比，如BERT这样的仅编码器变换器模型在检索和分类任务中提供了出色的性能-大小权衡。尽管BERT自发布以来一直是众多生产管道的核心工具，但对其的帕累托改进相对有限。在本论文中，我们引入了ModernBERT，将现代模型优化应用于仅编码器模型，并在老一代编码器基础上实现了显著的帕累托改进。ModernBERT模型基于2万亿个令牌并采用8192的自然序列长度进行训练，在涵盖多种分类任务以及不同领域（包括代码）的单个向量和多向量检索方面表现出最先进的评估结果。除了强大的下游性能外，ModernBERT还是最高效的速度和内存模型，并且适用于常见的GPU进行推理。 

---
# When Should We Prefer State-to-Visual DAgger Over Visual Reinforcement Learning? 

**Title (ZH)**: 在什么情况下我们应优先选择状态到视觉DAgger算法而非视觉强化学习？ 

**Authors**: Tongzhou Mu, Zhaoyang Li, Stanisław Wiktor Strzelecki, Xiu Yuan, Yunchao Yao, Litian Liang, Hao Su  

**Link**: [PDF](https://arxiv.org/pdf/2412.13662)  

**Abstract**: Learning policies from high-dimensional visual inputs, such as pixels and point clouds, is crucial in various applications. Visual reinforcement learning is a promising approach that directly trains policies from visual observations, although it faces challenges in sample efficiency and computational costs. This study conducts an empirical comparison of State-to-Visual DAgger, a two-stage framework that initially trains a state policy before adopting online imitation to learn a visual policy, and Visual RL across a diverse set of tasks. We evaluate both methods across 16 tasks from three benchmarks, focusing on their asymptotic performance, sample efficiency, and computational costs. Surprisingly, our findings reveal that State-to-Visual DAgger does not universally outperform Visual RL but shows significant advantages in challenging tasks, offering more consistent performance. In contrast, its benefits in sample efficiency are less pronounced, although it often reduces the overall wall-clock time required for training. Based on our findings, we provide recommendations for practitioners and hope that our results contribute valuable perspectives for future research in visual policy learning. 

**Abstract (ZH)**: 从高维度视觉输入（如像素和点云）学习策略在各种应用中至关重要。视觉强化学习是一种直接从视觉观察中训练策略的有前景的方法，尽管它在样本效率和计算成本方面面临着挑战。本研究对一种两阶段框架——State-to-Visual DAgger 进行了实证比较，该框架首先训练一个状态策略，然后采用在线模仿来学习一个视觉策略——与视觉强化学习（Visual RL）进行了广泛的对比。我们在这三个基准的16个任务上评估了这两种方法，重点关注它们的渐近性能、样本效率和计算成本。令人惊讶的是，我们的研究结果表明，State-to-Visual DAgger 不一定在所有任务上都优于 Visual RL，但在具有挑战性的任务中显示出显著的优势，提供了更一致的性能。然而，它的样本效率优势并不明显，尽管它通常能够缩短训练所需的总体时间。基于我们的发现，我们为实践者提供了建议，并希望我们的结果能为未来视觉策略学习的研究提供有价值的视角。 

---
# G-VEval: A Versatile Metric for Evaluating Image and Video Captions Using GPT-4o 

**Title (ZH)**: G-VEval：一种使用GPT-4o评估图像和视频字幕的 versatile 统计指标 

**Authors**: Tony Cheng Tong, Sirui He, Zhiwen Shao, Dit-Yan Yeung  

**Link**: [PDF](https://arxiv.org/pdf/2412.13647)  

**Abstract**: Evaluation metric of visual captioning is important yet not thoroughly explored. Traditional metrics like BLEU, METEOR, CIDEr, and ROUGE often miss semantic depth, while trained metrics such as CLIP-Score, PAC-S, and Polos are limited in zero-shot scenarios. Advanced Language Model-based metrics also struggle with aligning to nuanced human preferences. To address these issues, we introduce G-VEval, a novel metric inspired by G-Eval and powered by the new GPT-4o. G-VEval uses chain-of-thought reasoning in large multimodal models and supports three modes: reference-free, reference-only, and combined, accommodating both video and image inputs. We also propose MSVD-Eval, a new dataset for video captioning evaluation, to establish a more transparent and consistent framework for both human experts and evaluation metrics. It is designed to address the lack of clear criteria in existing datasets by introducing distinct dimensions of Accuracy, Completeness, Conciseness, and Relevance (ACCR). Extensive results show that G-VEval outperforms existing methods in correlation with human annotations, as measured by Kendall tau-b and Kendall tau-c. This provides a flexible solution for diverse captioning tasks and suggests a straightforward yet effective approach for large language models to understand video content, paving the way for advancements in automated captioning. Codes are available at this https URL 

**Abstract (ZH)**: 视觉captioning的评估指标非常重要但尚未得到充分探索。传统指标如BLEU、METEOR、CIDEr和ROUGE往往忽略了语义深度，而经过训练的指标如CLIP-Score、PAC-S和Polos在零样本场景中能力有限。基于先进语言模型的评估指标也难以与细腻的人类偏好对齐。为了解决这些问题，我们引入了G-VEval，这是一个受到G-Eval启发并依托于新的GPT-4o的新型评估指标。G-VEval在大规模多模态模型中采用链式推理，并支持三种模式：无参考、有参考和结合模式，能够适应视频和图像输入。我们还提出了MSVD-Eval，这是一个新的视频captioning评估数据集，旨在为人类专家和评估指标建立一个更透明且一致的框架。该数据集通过引入准确度、完整性、简洁性和相关性（ACCR）的不同维度，解决了现有数据集中缺乏清晰标准的问题。广泛的结果表明，G-VEval在与人类注释的相关性方面（通过Kendall tau-b和Kendall tau-c测量）优于现有方法，为各种captioning任务提供了一种灵活的解决方案，并为大型语言模型理解视频内容提供了一种简单有效的途径，为自动字幕生成技术的进步铺平了道路。具体的代码可以在以下链接找到：[此处链接] 

---
# Consistency of Compositional Generalization across Multiple Levels 

**Title (ZH)**: 多层级上的组合泛化一致性 

**Authors**: Chuanhao Li, Zhen Li, Chenchen Jing, Xiaomeng Fan, Wenbo Ye, Yuwei Wu, Yunde Jia  

**Link**: [PDF](https://arxiv.org/pdf/2412.13636)  

**Abstract**: Compositional generalization is the capability of a model to understand novel compositions composed of seen concepts. There are multiple levels of novel compositions including phrase-phrase level, phrase-word level, and word-word level. Existing methods achieve promising compositional generalization, but the consistency of compositional generalization across multiple levels of novel compositions remains unexplored. The consistency refers to that a model should generalize to a phrase-phrase level novel composition, and phrase-word/word-word level novel compositions that can be derived from it simultaneously. In this paper, we propose a meta-learning based framework, for achieving consistent compositional generalization across multiple levels. The basic idea is to progressively learn compositions from simple to complex for consistency. Specifically, we divide the original training set into multiple validation sets based on compositional complexity, and introduce multiple meta-weight-nets to generate sample weights for samples in different validation sets. To fit the validation sets in order of increasing compositional complexity, we optimize the parameters of each meta-weight-net independently and sequentially in a multilevel optimization manner. We build a GQA-CCG dataset to quantitatively evaluate the consistency. Experimental results on visual question answering and temporal video grounding, demonstrate the effectiveness of the proposed framework. We release GQA-CCG at this https URL. 

**Abstract (ZH)**: 组合泛化是模型理解由已见过的概念组合而成的新型组合的能力。新型组合可以分为短语-短语级别、短语-词级别和词-词级别等多个层次。现有方法在组合泛化方面取得了令人瞩目的成果，但新型组合多个层次之间的组合泛化一致性尚未被研究。这种一致性指的是模型在理解一个新型组合短语-短语级别的同时，也应该能够泛化理解可以从该新型组合推导出的短语-词级和词-词级的新型组合。在本文中，我们提出了一种基于元学习的框架，以实现各个层次间的组合泛化一致性。基本思想是从简单到复杂逐步学习组合以确保一致性。具体来说，我们根据组合的复杂性将原始训练集划分为多个验证集，并引入多个元权重网络来为不同验证集中的样本生成样本权重。为按组合复杂度递增的顺序拟合这些验证集，我们以多层次优化的方式分别且依次优化每个元权重网络的参数。我们构建了GQA-CCG数据集来定量评估一致性。视觉问答和时序视频定位实验结果证明了所提出框架的有效性。我们已在以下网址发布了GQA-CCG数据集：[链接]。 

---
# Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model 

**Title (ZH)**: 政策装饰器：面向大型策略模型的模型无关的在线精炼方法 

**Authors**: Xiu Yuan, Tongzhou Mu, Stone Tao, Yunhao Fang, Mengke Zhang, Hao Su  

**Link**: [PDF](https://arxiv.org/pdf/2412.13630)  

**Abstract**: Recent advancements in robot learning have used imitation learning with large models and extensive demonstrations to develop effective policies. However, these models are often limited by the quantity, quality, and diversity of demonstrations. This paper explores improving offline-trained imitation learning models through online interactions with the environment. We introduce Policy Decorator, which uses a model-agnostic residual policy to refine large imitation learning models during online interactions. By implementing controlled exploration strategies, Policy Decorator enables stable, sample-efficient online learning. Our evaluation spans eight tasks across two benchmarks-ManiSkill and Adroit-and involves two state-of-the-art imitation learning models (Behavior Transformer and Diffusion Policy). The results show Policy Decorator effectively improves the offline-trained policies and preserves the smooth motion of imitation learning models, avoiding the erratic behaviors of pure RL policies. See our project page (this https URL) for videos. 

**Abstract (ZH)**: 近年来，机器人学习领域的进展利用大型模型和大量示范来开发有效的策略，其中模仿学习发挥了重要作用。然而，这些模型经常受限于示范的数量、质量和多样性。本文探索通过在线与环境交互来改进离线训练的模仿学习模型。我们介绍了Policy Decorator，这是一种模型无关的残差策略，能够在在线交互过程中进一步细化大型模仿学习模型。通过实施受控探索策略，Policy Decorator使在线学习变得稳定且样本高效。我们的评估涵盖了两个基准（ManiSkill和Adroit）上的八个任务，并使用了两种最先进的模仿学习模型（Behavior Transformer和Diffusion Policy）。结果表明，Policy Decorator有效提升了离线训练的策略，并保持了模仿学习模型的平滑运动，避免了纯强化学习策略的不规则行为。更多项目详情和视频请参见我们的项目页面（请点击此链接：[项目页面](this https URL)）。 

---
# LIFT: Improving Long Context Understanding Through Long Input Fine-Tuning 

**Title (ZH)**: LIFT：通过长输入微调提高长语境理解 

**Authors**: Yansheng Mao, Jiaqi Li, Fanxu Meng, Jing Xiong, Zilong Zheng, Muhan Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13626)  

**Abstract**: Long context understanding remains challenging for large language models due to their limited context windows. This paper introduces Long Input Fine-Tuning (LIFT) for long context modeling, a novel framework that enhances LLM performance on long-context tasks by adapting model parameters to the context at test time. LIFT enables efficient processing of lengthy inputs without the computational burden of offline long-context adaptation, and can improve the long-context capabilities of arbitrary short-context models. The framework is further enhanced by integrating in-context learning and pre-LIFT supervised fine-tuning. The combination of in-context learning and LIFT enables short-context models like Llama 3 to handle arbitrarily long contexts and consistently improves their performance on popular long-context benchmarks like LooGLE and LongBench. We also provide a comprehensive analysis of the strengths and limitations of LIFT on long context understanding, offering valuable directions for future research. 

**Abstract (ZH)**: 对于大型语言模型而言，理解长段文本仍然具有挑战性，因为它们受限于较小的上下文窗口。本文介绍了Long Input Fine-Tuning (LIFT) 框架，这是一种新型框架，通过在测试时调整模型参数以适应长上下文，从而提高大语言模型在长上下文任务中的性能。LIFT 允许高效地处理长输入，而不必承担离线长上下文适配的计算负担，并且可以增强任意短上下文模型的长上下文能力。该框架进一步通过结合上下文学习和预-LIFT 监督微调而得到增强。上下文学习和 LIFT 的结合使像 Llama 3 这样的短上下文模型能够处理任意长的上下文，并在流行的长上下文基准测试如 LooGLE 和 LongBench 上持续地提升其性能。我们还对 LIFT 在长上下文理解方面的优势和局限性进行了全面分析，为未来的研究提供了宝贵的方向。 

---
# Unifying Attribution-Based Explanations Using Functional Decomposition 

**Title (ZH)**: 使用功能性分解统一基于归因的解释 

**Authors**: Arne Gevaert, Yvan Saeys  

**Link**: [PDF](https://arxiv.org/pdf/2412.13623)  

**Abstract**: The black box problem in machine learning has led to the introduction of an ever-increasing set of explanation methods for complex models. These explanations have different properties, which in turn has led to the problem of method selection: which explanation method is most suitable for a given use case? In this work, we propose a unifying framework of attribution-based explanation methods, which provides a step towards a rigorous study of the similarities and differences of explanations. We first introduce removal-based attribution methods (RBAMs), and show that an extensively broad selection of existing methods can be viewed as such RBAMs. We then introduce the canonical additive decomposition (CAD). This is a general construction for additively decomposing any function based on the central idea of removing (groups of) features. We proceed to show that indeed every valid additive decomposition is an instance of the CAD, and that any removal-based attribution method is associated with a specific CAD. Next, we show that any removal-based attribution method can be completely defined as a game-theoretic value or interaction index for a specific (possibly constant-shifted) cooperative game, which is defined using the corresponding CAD of the method. We then use this intrinsic connection to define formal descriptions of specific behaviours of explanation methods, which we also call functional axioms, and identify sufficient conditions on the corresponding CAD and game-theoretic value or interaction index of an attribution method under which the attribution method is guaranteed to adhere to these functional axioms. Finally, we show how this unifying framework can be used to develop new, efficient approximations for existing explanation methods. 

**Abstract (ZH)**: 机器学习中的黑盒问题导致了对复杂模型解释方法的一系列研究。这些解释方法具有不同的特性，进而引出了方法选择的问题：哪种解释方法最适合特定应用场景？在本文中，我们提出了一种基于归因的解释方法统一框架，这为全面研究解释的相似性和差异性迈出了一步。首先，我们介绍了去除基归因方法（RBAMs），并显示了大量的现有方法都可以视为此类RBAMs。然后，我们引入了典型加性分解（CAD）。这是一套基于去除（一组）特征的核心理念来对任何函数进行加性分解的一般构造方法。随后，我们证明了任何有效的加性分解都是CAD的一个实例，并且任何去除基归因方法都与特定的CAD相关联。接着，我们展示了任何去除基归因方法可以完全定义为特定合作博弈（可能经过常量平移）的游戏论价值或交互指数，而该博弈是使用相应的方法CAD定义的。我们利用这种固有的联系来定义解释方法的具体行为形式描述，称之为功能性公理，并确定了在满足一定条件下CAD和游戏论价值或交互指数，使得解释方法能够遵守这些功能性公理的充分条件。最后，我们展示了如何利用这个统一框架来开发现有解释方法的新颖高效近似方法。 

---
# NPC: Neural Predictive Control for Fuel-Efficient Autonomous Trucks 

**Title (ZH)**: NPC：神经预测控制实现燃油效率优化的自动驾驶卡车 

**Authors**: Jiaping Ren, Jiahao Xiang, Hongfei Gao, Jinchuan Zhang, Yiming Ren, Yuexin Ma, Yi Wu, Ruigang Yang, Wei Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.13618)  

**Abstract**: Fuel efficiency is a crucial aspect of long-distance cargo transportation by oil-powered trucks that economize on costs and decrease carbon emissions. Current predictive control methods depend on an accurate model of vehicle dynamics and engine, including weight, drag coefficient, and the Brake-specific Fuel Consumption (BSFC) map of the engine. We propose a pure data-driven method, Neural Predictive Control (NPC), which does not use any physical model for the vehicle. After training with over 20,000 km of historical data, the novel proposed NVFormer implicitly models the relationship between vehicle dynamics, road slope, fuel consumption, and control commands using the attention mechanism. Based on the online sampled primitives from the past of the current freight trip and anchor-based future data synthesis, the NVFormer can infer optimal control command for reasonable fuel consumption. The physical model-free NPC outperforms the base PCC method with 2.41% and 3.45% more significant fuel saving in simulation and open-road highway testing, respectively. 

**Abstract (ZH)**: 燃油效率是油动力卡车进行长途货物运输的一个关键方面，通过节约成本并减少碳排放来提升其重要性。目前的预测控制方法依赖于车辆动力学和发动机的精确模型，包括车辆重量、阻力系数以及发动机的燃料消耗率（BSFC）图。我们提出了一种完全基于数据的神经网络预测控制（NPC）方法，该方法不使用任何车辆物理模型。经过超过20,000公里历史数据的训练后，本文新提出的NVFormer利用注意力机制隐式地建模了车辆动力学、道路坡度、燃料消耗和控制指令之间的关系。基于当前货运行程过去阶段的在线采样基本原理以及基于锚点的未来数据合成，NVFormer能推断出合理的燃料消耗下的最优控制指令。物理模型自由的NPC方法在模拟和开放道路高速公路上测试中分别比基础PCC方法提高了2.41%和3.45%的燃油效率。 

---
# Reverse Region-to-Entity Annotation for Pixel-Level Visual Entity Linking 

**Title (ZH)**: 像素级视觉实体链接中的反向区域到实体标注 

**Authors**: Zhengfei Xu, Sijia Zhao, Yanchao Hao, Xiaolong Liu, Lili Li, Yuyang Yin, Bo Li, Xi Chen, Xin Xin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13614)  

**Abstract**: Visual Entity Linking (VEL) is a crucial task for achieving fine-grained visual understanding, matching objects within images (visual mentions) to entities in a knowledge base. Previous VEL tasks rely on textual inputs, but writing queries for complex scenes can be challenging. Visual inputs like clicks or bounding boxes offer a more convenient alternative. Therefore, we propose a new task, Pixel-Level Visual Entity Linking (PL-VEL), which uses pixel masks from visual inputs to refer to objects, supplementing reference methods for VEL. To facilitate research on this task, we have constructed the MaskOVEN-Wiki dataset through an entirely automatic reverse region-entity annotation framework. This dataset contains over 5 million annotations aligning pixel-level regions with entity-level labels, which will advance visual understanding towards fine-grained. Moreover, as pixel masks correspond to semantic regions in an image, we enhance previous patch-interacted attention with region-interacted attention by a visual semantic tokenization approach. Manual evaluation results indicate that the reverse annotation framework achieved a 94.8% annotation success rate. Experimental results show that models trained on this dataset improved accuracy by 18 points compared to zero-shot models. Additionally, the semantic tokenization method achieved a 5-point accuracy improvement over the trained baseline. 

**Abstract (ZH)**: 视觉实体链接（VEL）是实现细粒度视觉理解的关键任务，它涉及将图像中的物体（视觉提及）与知识库中的实体进行匹配。之前的研究主要依赖于文本输入，但为复杂场景编写查询可能会很具挑战性。视觉输入如点击或边界框提供了一个更为便捷的选择。因此，我们提出了一个新的任务——像素级视觉实体链接（PL-VEL），该任务利用视觉输入的像素掩码来引用物体，补充了VEL的参考方法。为了促进这一任务的研究，我们通过一个完全自动的反向区域-实体注解框架构建了MaskOVEN-Wiki数据集。该数据集包含超过500万个像素级区域与实体级标签对齐的注释，这将推动视觉理解向细粒度方向发展。此外，由于像素掩码对应图像中的语义区域，我们通过视觉语义分词的方法增强了之前的小图像交互注意力机制，引入了区域交互注意力机制。手动评估结果显示，反向注解框架的注释成功率达到了94.8%。实验结果表明，使用该数据集训练的模型相比于零样本模型的准确率提高了18个百分点。此外，语义分词方法相比训练基线提高了5个百分点的准确率。 

---
# Are LLMs Good Literature Review Writers? Evaluating the Literature Review Writing Ability of Large Language Models 

**Title (ZH)**: 大型语言模型是好的文献综述撰写者吗？评估大型语言模型的文献综述撰写能力 

**Authors**: Xuemei Tang, Xufeng Duan, Zhenguang G. Cai  

**Link**: [PDF](https://arxiv.org/pdf/2412.13612)  

**Abstract**: The literature review is a crucial form of academic writing that involves complex processes of literature collection, organization, and summarization. The emergence of large language models (LLMs) has introduced promising tools to automate these processes. However, their actual capabilities in writing comprehensive literature reviews remain underexplored, such as whether they can generate accurate and reliable references. To address this gap, we propose a framework to assess the literature review writing ability of LLMs automatically. We evaluate the performance of LLMs across three tasks: generating references, writing abstracts, and writing literature reviews. We employ external tools for a multidimensional evaluation, which includes assessing hallucination rates in references, semantic coverage, and factual consistency with human-written context. By analyzing the experimental results, we find that, despite advancements, even the most sophisticated models still cannot avoid generating hallucinated references. Additionally, different models exhibit varying performance in literature review writing across different disciplines. 

**Abstract (ZH)**: 文献综述是一种重要的学术写作形式，涉及复杂的过程，包括文献的收集、组织和总结。大型语言模型（LLMs）的出现引入了自动完成这些任务的有前景的工具。然而，它们在撰写全面文献综述的实际能力仍鲜有探索，例如它们是否能够生成准确可靠的参考文献。为填补这一空白，我们提出了一种框架，以自动评估LLMs的文献综述写作能力。我们从三个方面评估了LLMs的表现：生成参考文献、撰写摘要和撰写文献综述。我们采用外部工具进行多维度评估，包括评估参考文献中的虚构率、语义覆盖面以及与人类撰写的背景事实的一致性。通过分析实验结果，我们发现，尽管技术取得了进步，即使是最先进的模型也无法避免生成虚构的参考文献。此外，不同模型在不同学科的文献综述写作中表现出不同的性能。 

---
# Faster and Stronger: When ANN-SNN Conversion Meets Parallel Spiking Calculation 

**Title (ZH)**: 更快更强大：当ANN-SNN转换遇到并行脉冲计算 

**Authors**: Zecheng Hao, Zhaofei Yu, Tiejun Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13610)  

**Abstract**: Spiking Neural Network (SNN), as a brain-inspired and energy-efficient network, is currently facing the pivotal challenge of exploring a suitable and efficient learning framework. The predominant training methodologies, namely Spatial-Temporal Back-propagation (STBP) and ANN-SNN Conversion, are encumbered by substantial training overhead or pronounced inference latency, which impedes the advancement of SNNs in scaling to larger networks and navigating intricate application domains. In this work, we propose a novel parallel conversion learning framework, which establishes a mathematical mapping relationship between each time-step of the parallel spiking neurons and the cumulative spike firing rate. We theoretically validate the lossless and sorting properties of the conversion process, as well as pointing out the optimal shifting distance for each step. Furthermore, by integrating the above framework with the distribution-aware error calibration technique, we can achieve efficient conversion towards more general activation functions or training-free circumstance. Extensive experiments have confirmed the significant performance advantages of our method for various conversion cases under ultra-low time latency. To our best knowledge, this is the first work which jointly utilizes parallel spiking calculation and ANN-SNN Conversion, providing a highly promising approach for SNN supervised training. 

**Abstract (ZH)**: 脉冲神经网络（SNN），作为一种受脑启发且能效高的网络，目前正面临探索合适的高效学习框架的关键挑战。主流的训练方法，即时空反向传播（SPATIAL-TEMPORAL BACK-PROPAGATION, STBP）和ANN与SNN转换方法，分别受到大量训练开销或明显的推断延迟的困扰，这阻碍了SNN在扩展到更大的网络以及应对复杂应用场景方面的发展。在这项工作中，我们提出了一种新颖的并行转换学习框架，该框架在每一时间步长的并行脉冲神经元与累积脉冲发放率之间建立了数学映射关系。我们从理论上验证了转换过程的无损性和排序性，并指出了每个时间步长的最佳偏移距离。进一步地，通过将上述框架与分布感知的误差校准技术相结合，可以有效地实现向更具通用性激活函数或无需训练情况下的转换。广泛的实验已经证实了我们在超低时间延迟的各种转换情况下的方法具有显著的优势。据我们所知，这是第一次将并行脉冲计算与ANN-SNN转换结合起来的工作，为SNN监督训练提供了一种极具前景的方法。 

---
# Hybrid CNN-LSTM based Indoor Pedestrian Localization with CSI Fingerprint Maps 

**Title (ZH)**: 基于CSI指纹图的混合CNN-LSTM室内行人定位方法 

**Authors**: Muhammad Emad-ud-din  

**Link**: [PDF](https://arxiv.org/pdf/2412.13601)  

**Abstract**: The paper presents a novel Wi-Fi fingerprinting system that uses Channel State Information (CSI) data for fine-grained pedestrian localization. The proposed system exploits the frequency diversity and spatial diversity of the features extracted from CSI data to generate a 2D+channel image termed as a CSI Fingerprint Map. We then use this CSI Fingerprint Map representation of CSI data to generate a pedestrian trajectory hypothesis using a hybrid architecture that combines a Convolutional Neural Network and a Long Short-Term Memory Recurrent Neural Network model. The proposed architecture exploits the temporal and spatial relationship information among the CSI data observations gathered at neighboring locations. A particle filter is then employed to separate out the most likely hypothesis matching a human walk model. The experimental performance of our method is compared to existing deep learning localization methods such ConFi, DeepFi and to a self-developed temporal-feature based LSTM based location classifier. The experimental results show marked improvement with an average RMSE of 0.36 m in a moderately dynamic and 0.17 m in a static environment. Our method is essentially a proof of concept that with (1) sparse availability of observations, (2) limited infrastructure requirements, (3) moderate level of short-term and long-term noise in the training and testing environment, reliable fine-grained Wi-Fi based pedestrian localization is a potential option. 

**Abstract (ZH)**: 本文提出了一种创新的Wi-Fi指纹定位系统，该系统利用信道状态信息（CSI）数据实现精细的行人定位。所提出的系统利用从CSI数据中提取的特征的频率多样性和空间多样性生成一张称为CSI指纹图的二维信道图像。然后，我们使用这种CSI数据表示形式和一种结合卷积神经网络（CNN）和长期短期记忆循环神经网络（LSTM RNN）模型的混合架构来生成行人轨迹假设。提出的架构利用了邻近位置采集的CSI数据观察之间的时域和空域关系信息。然后采用粒子滤波器分离出最符合人类行走模型的假设。我们的方法的实验性能与现有的深度学习定位方法（如ConFi、DeepFi）以及我们的自开发基于时间特征的LSTM定位分类器进行了比较。实验结果表明，在适度动态环境中平均RMSE为0.36米，在静态环境中为0.17米，显示出显著改进。我们的方法本质上是一个概念验证，展示了在（1）稀疏的数据观察，（2）有限的基础设施要求，以及（3）训练和测试环境中存在中等水平的短期和长期噪声的情况下，基于Wi-Fi的精细定位是可行的选项。 

---
# Generalizable Sensor-Based Activity Recognition via Categorical Concept Invariant Learning 

**Title (ZH)**: 基于传感器的活动识别中的分类概念不变性学习 

**Authors**: Di Xiong, Shuoyuan Wang, Lei Zhang, Wenbo Huang, Chaolei Han  

**Link**: [PDF](https://arxiv.org/pdf/2412.13594)  

**Abstract**: Human Activity Recognition (HAR) aims to recognize activities by training models on massive sensor data. In real-world deployment, a crucial aspect of HAR that has been largely overlooked is that the test sets may have different distributions from training sets due to inter-subject variability including age, gender, behavioral habits, etc., which leads to poor generalization performance. One promising solution is to learn domain-invariant representations to enable a model to generalize on an unseen distribution. However, most existing methods only consider the feature-invariance of the penultimate layer for domain-invariant learning, which leads to suboptimal results. In this paper, we propose a Categorical Concept Invariant Learning (CCIL) framework for generalizable activity recognition, which introduces a concept matrix to regularize the model in the training stage by simultaneously concentrating on feature-invariance and logit-invariance. Our key idea is that the concept matrix for samples belonging to the same activity category should be similar. Extensive experiments on four public HAR benchmarks demonstrate that our CCIL substantially outperforms the state-of-the-art approaches under cross-person, cross-dataset, cross-position, and one-person-to-another settings. 

**Abstract (ZH)**: 人体活动识别（HAR）旨在通过训练大规模传感器数据来识别活动。在实际部署中，已被广泛忽视的一个关键方面是测试集可能由于不同个体的变异（包括年龄、性别、行为习惯等）而与训练集的分布不同，这导致泛化性能较差。一种有前景的解决方案是学习领域不变的表示，以使模型能够在未见过的分布上进行泛化。然而，现有的大多数方法仅考虑最后一层特征不变性进行领域不变学习，这导致了次优的结果。在本文中，我们提出了一种分类概念不变学习（CCIL）框架，用于实现可泛化的活动识别，通过同时关注特征不变性和类别不变性，引入了一个概念矩阵来在训练阶段正则化模型。我们的核心思想是属于同一活动类别的样本的概念矩阵应该相似。在四个公开的HAR基准数据集上的广泛实验表明，在不同个体、不同数据集、不同位置以及单人到另一人的设置下，我们的CCIL显著优于现有最先进的方法。 

---
# SemiDFL: A Semi-Supervised Paradigm for Decentralized Federated Learning 

**Title (ZH)**: SemiDFL：去中心化联邦学习的半监督范式 

**Authors**: Xinyang Liu, Pengchao Han, Xuan Li, Bo Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13589)  

**Abstract**: Decentralized federated learning (DFL) realizes cooperative model training among connected clients without relying on a central server, thereby mitigating communication bottlenecks and eliminating the single-point failure issue present in centralized federated learning (CFL). Most existing work on DFL focuses on supervised learning, assuming each client possesses sufficient labeled data for local training. However, in real-world applications, much of the data is unlabeled. We address this by considering a challenging yet practical semisupervised learning (SSL) scenario in DFL, where clients may have varying data sources: some with few labeled samples, some with purely unlabeled data, and others with both. In this work, we propose SemiDFL, the first semi-supervised DFL method that enhances DFL performance in SSL scenarios by establishing a consensus in both data and model spaces. Specifically, we utilize neighborhood information to improve the quality of pseudo-labeling, which is crucial for effectively leveraging unlabeled data. We then design a consensusbased diffusion model to generate synthesized data, which is used in combination with pseudo-labeled data to create mixed datasets. Additionally, we develop an adaptive aggregation method that leverages the model accuracy of synthesized data to further enhance SemiDFL performance. Through extensive experimentation, we demonstrate the remarkable performance superiority of the proposed DFL-Semi method over existing CFL and DFL schemes in both IID and non-IID SSL scenarios. 

**Abstract (ZH)**: 去中心化联邦学习（Decentralized Federated Learning，DFL）通过在连接的客户端之间进行合作模型训练，而不依赖于中央服务器，从而缓解了集中式联邦学习（Centralized Federated Learning，CFL）中的通信瓶颈问题，并消除了单点故障的问题。目前大多数关于DFL的研究集中在监督学习上，假设每个客户端有足够的标记数据进行本地训练。然而，在实际应用中，大量数据是未标记的。为了解决这一问题，我们考虑了DFL中的一种挑战性的但实际可行的半监督学习（Semisupervised Learning，SSL）场景，在这种场景中，不同的客户端可能具有不同的数据来源：一些客户端拥有少量的标记样本，另一些客户端只有未标记数据，还有一些客户端同时拥有标记和未标记数据。在这项工作中，我们提出了一种名为SemiDFL的新方法，该方法首次在SSL场景中增强了DFL性能，通过在数据空间和模型空间建立共识。具体而言，我们利用了邻域信息来提高伪标签的质量，这对于有效利用未标记数据至关重要。然后，我们设计了一种基于共识的扩散模型生成合成数据，并将合成数据与伪标记数据结合起来生成混合数据集。此外，我们还开发了一种自适应聚合方法，利用合成数据的模型准确性进一步提升SemiDFL的性能。通过广泛的实验，我们证明了所提出的DFL-Semi方法在IID和非IID SSL场景中均优于现有的CFL和DFL方案。 

---
# Socio-Culturally Aware Evaluation Framework for LLM-Based Content Moderation 

**Title (ZH)**: 基于LLM的内容审核社会文化意识评估框架 

**Authors**: Shanu Kumar, Gauri Kholkar, Saish Mendke, Anubhav Sadana, Parag Agrawal, Sandipan Dandapat  

**Link**: [PDF](https://arxiv.org/pdf/2412.13578)  

**Abstract**: With the growth of social media and large language models, content moderation has become crucial. Many existing datasets lack adequate representation of different groups, resulting in unreliable assessments. To tackle this, we propose a socio-culturally aware evaluation framework for LLM-driven content moderation and introduce a scalable method for creating diverse datasets using persona-based generation. Our analysis reveals that these datasets provide broader perspectives and pose greater challenges for LLMs than diversity-focused generation methods without personas. This challenge is especially pronounced in smaller LLMs, emphasizing the difficulties they encounter in moderating such diverse content. 

**Abstract (ZH)**: 随着社交媒体和大型语言模型的发展，内容审核变得至关重要。现有的许多数据集在不同群体的代表性方面存在不足，导致评估不够可靠。为解决这一问题，我们提出了一种社会文化意识强的内容审核评估框架，并介绍了一种基于人设生成的可扩展方法来创建多样化的数据集。我们的分析表明，这些数据集为大型语言模型提供了更广泛的视角，并对其提出了更大的挑战，这种挑战尤其在小型语言模型中表现得尤为明显，突显了它们在审核如此多样化的内容时所遇到的困难。 

---
# Bridge then Begin Anew: Generating Target-relevant Intermediate Model for Source-free Visual Emotion Adaptation 

**Title (ZH)**: 搭建桥梁再启新篇：生成目标相关中间模型实现源代码无依赖的视觉情绪适应 

**Authors**: Jiankun Zhu, Sicheng Zhao, Jing Jiang, Wenbo Tang, Zhaopan Xu, Tingting Han, Pengfei Xu, Hongxun Yao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13577)  

**Abstract**: Visual emotion recognition (VER), which aims at understanding humans' emotional reactions toward different visual stimuli, has attracted increasing attention. Given the subjective and ambiguous characteristics of emotion, annotating a reliable large-scale dataset is hard. For reducing reliance on data labeling, domain adaptation offers an alternative solution by adapting models trained on labeled source data to unlabeled target data. Conventional domain adaptation methods require access to source data. However, due to privacy concerns, source emotional data may be inaccessible. To address this issue, we propose an unexplored task: source-free domain adaptation (SFDA) for VER, which does not have access to source data during the adaptation process. To achieve this, we propose a novel framework termed Bridge then Begin Anew (BBA), which consists of two steps: domain-bridged model generation (DMG) and target-related model adaptation (TMA). First, the DMG bridges cross-domain gaps by generating an intermediate model, avoiding direct alignment between two VER datasets with significant differences. Then, the TMA begins training the target model anew to fit the target structure, avoiding the influence of source-specific knowledge. Extensive experiments are conducted on six SFDA settings for VER. The results demonstrate the effectiveness of BBA, which achieves remarkable performance gains compared with state-of-the-art SFDA methods and outperforms representative unsupervised domain adaptation approaches. 

**Abstract (ZH)**: 视觉情感识别（VER），旨在理解人类对不同视觉刺激的情感反应，引起了越来越多的关注。由于情感具有主观性和含糊性，标注大规模可靠数据集十分困难。为了减少对数据标注的依赖，领域适应提供了一种替代方案，通过将基于标记源数据训练的模型适应未标记的目标数据。传统领域适应方法需要访问源数据。然而，由于隐私问题，源情感数据可能不可访问。为了解决这一问题，我们提出了一项未被探索的任务：面向视觉情感识别（VER）的源数据无感知领域适应（SFDA），在适应过程中不访问源数据。为了实现这一目标，我们提出了一种名为Bridge then Begin Anew（BBA）的新框架，该框架分为两个步骤：领域桥梁生成（DMG）和目标相关模型适应（TMA）。首先，DMG通过生成一个中间模型来跨越领域间的差距，避免直接对两个具有显著差异的VER数据集进行对齐。然后，TMA重新开始训练目标模型以适应目标结构，避免特定源知识的影响。我们在六个VER的SFDA设置中进行了广泛的实验。结果表明，BBA的有效性，其在与现有最佳SFDA方法相比时取得了显著的性能提升，并优于代表性无监督领域适应方法。 

---
# Seeking Consistent Flat Minima for Better Domain Generalization via Refining Loss Landscapes 

**Title (ZH)**: 通过细化损失景观以寻求一致的平坦极小值以改进领域泛化 

**Authors**: Aodi Li, Liansheng Zhuang, Xiao Long, Minghong Yao, Shafei Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13573)  

**Abstract**: Domain generalization aims to learn a model from multiple training domains and generalize it to unseen test domains. Recent theory has shown that seeking the deep models, whose parameters lie in the flat minima of the loss landscape, can significantly reduce the out-of-domain generalization error. However, existing methods often neglect the consistency of loss landscapes in different domains, resulting in models that are not simultaneously in the optimal flat minima in all domains, which limits their generalization ability. To address this issue, this paper proposes an iterative Self-Feedback Training (SFT) framework to seek consistent flat minima that are shared across different domains by progressively refining loss landscapes during training. It alternatively generates a feedback signal by measuring the inconsistency of loss landscapes in different domains and refines these loss landscapes for greater consistency using this feedback signal. Benefiting from the consistency of the flat minima within these refined loss landscapes, our SFT helps achieve better out-of-domain generalization. Extensive experiments on DomainBed demonstrate superior performances of SFT when compared to state-of-the-art sharpness-aware methods and other prevalent DG baselines. On average across five DG benchmarks, SFT surpasses the sharpness-aware minimization by 2.6% with ResNet-50 and 1.5% with ViT-B/16, respectively. The code will be available soon. 

**Abstract (ZH)**: 领域泛化旨在从多个训练域中学习一个模型，并将其应用于未见过的测试域。最近的理论表明，寻求那些参数位于损失景观平坦最小值中的深层模型，可以显著降低领域外的泛化误差。然而，现有的方法往往忽视了不同领域中损失景观一致性的缺乏，导致模型不能同时在所有领域中达到最优的平坦最小值，从而限制了其泛化能力。为解决这一问题，本文提出了一种迭代的自我反馈训练（Self-Feedback Training，SFT）框架，通过在训练过程中逐步优化损失景观来寻找跨不同领域共享的一致平坦最小值。该框架通过测量不同领域之间的损失景观差异来生成反馈信号，并使用该反馈信号来进一步优化这些损失景观以提高一致性。得益于这些优化后的损失景观中平坦最小值的一致性，我们的SFT有助于提高领域外的泛化能力。在DomainBed上的广泛实验表明，与最先进的一些尖锐感知方法和其他流行的领域泛化基准相比，SFT在性能上具有优越性。在五个领域泛化基准上的平均表现中，与ResNet-50相比，SFT分别超过尖锐感知最小化方法2.6%，与ViT-B/16相比，超过1.5%。代码将在不久的将来公开。 

---
# CA-Edit: Causality-Aware Condition Adapter for High-Fidelity Local Facial Attribute Editing 

**Title (ZH)**: CA-Edit：因果关系意识条件适配器，用于高保真局部面部属性编辑 

**Authors**: Xiaole Xian, Xilin He, Zenghao Niu, Junliang Zhang, Weicheng Xie, Siyang Song, Zitong Yu, Linlin Shen  

**Link**: [PDF](https://arxiv.org/pdf/2412.13565)  

**Abstract**: For efficient and high-fidelity local facial attribute editing, most existing editing methods either require additional fine-tuning for different editing effects or tend to affect beyond the editing regions. Alternatively, inpainting methods can edit the target image region while preserving external areas. However, current inpainting methods still suffer from the generation misalignment with facial attributes description and the loss of facial skin details. To address these challenges, (i) a novel data utilization strategy is introduced to construct datasets consisting of attribute-text-image triples from a data-driven perspective, (ii) a Causality-Aware Condition Adapter is proposed to enhance the contextual causality modeling of specific details, which encodes the skin details from the original image while preventing conflicts between these cues and textual conditions. In addition, a Skin Transition Frequency Guidance technique is introduced for the local modeling of contextual causality via sampling guidance driven by low-frequency alignment. Extensive quantitative and qualitative experiments demonstrate the effectiveness of our method in boosting both fidelity and editability for localized attribute editing. The code is available at this https URL. 

**Abstract (ZH)**: 为了实现高效且高保真的局部面部属性编辑，现有大多数编辑方法要么需要针对不同的编辑效果进行额外的微调，要么倾向于影响编辑区域之外的区域。作为替代方案， inpainting 方法可以在保持外部区域不变的情况下编辑目标图像区域。然而，当前的 inpainting 方法仍存在面部属性描述生成不匹配以及面部皮肤细节丢失的问题。为了解决这些问题，（i）介绍了一种新颖的数据利用策略，从数据驱动的角度构建包含属性-文本-图像三元组的数据集；（ii）提出了因果感知条件适配器，以增强特定细节的上下文因果建模，同时从原始图像中编码皮肤细节，并防止这些线索与文本条件之间的冲突。此外，还引入了一种皮肤过渡频率引导技术，通过低频对齐驱动的采样指导进行局部上下文因果建模。广泛进行的定量和定性实验表明，我们的方法在提高局部属性编辑的保真度和编辑能力方面均具有明显效果。代码可在以下链接获取：this https URL 

---
# EscapeBench: Pushing Language Models to Think Outside the Box 

**Title (ZH)**: EscapeBench: 推动语言模型跳出固有思维模式 

**Authors**: Cheng Qian, Peixuan Han, Qinyu Luo, Bingxiang He, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, Denghui Zhang, Yunzhu Li, Heng Ji  

**Link**: [PDF](https://arxiv.org/pdf/2412.13549)  

**Abstract**: Language model agents excel in long-session planning and reasoning, but existing benchmarks primarily focus on goal-oriented tasks with explicit objectives, neglecting creative adaptation in unfamiliar environments. To address this, we introduce EscapeBench, a benchmark suite of room escape game environments designed to challenge agents with creative reasoning, unconventional tool use, and iterative problem-solving to uncover implicit goals. Our results show that current LM models, despite employing working memory and Chain-of-Thought reasoning, achieve only 15% average progress without hints, highlighting their limitations in creativity. To bridge this gap, we propose EscapeAgent, a framework designed to enhance creative reasoning through Foresight (innovative tool use) and Reflection (identifying unsolved tasks). Experiments show that EscapeAgent can execute action chains over 1,000 steps while maintaining logical coherence. It navigates and completes games with up to 40% fewer steps and hints, performs robustly across varying difficulty levels, and achieves higher action success rates with more efficient and innovative puzzle-solving strategies. All the data and codes are released. 

**Abstract (ZH)**: 语言模型代理在长期会话规划和推理方面表现出色，但现有的基准测试主要集中在具有明确目标的指令式任务上，忽视了在不熟悉环境中进行创造性适应的能力。为解决这一问题，我们引入了EscapeBench，这是一个设计用于挑战代理的创造性推理、不寻常的工具使用以及迭代问题解决的房间逃脱游戏环境基准测试套件，以揭示隐含的目标。我们的结果显示，尽管当前的语言模型使用了工作记忆和链条思考推理，但在没有提示的情况下平均仅能完成15%的进展，凸显了它们在创造力方面的局限性。为了弥合这一差距，我们提出了EscapeAgent框架，该框架通过前瞻（创新工具使用）和反思（识别未解决问题）来增强创造性推理。实验表明，EscapeAgent可以执行超过1000步的动作链并保持逻辑连贯性。它通过减少多达40%的步骤和提示来导航并完成游戏，能够在不同难度级别上表现出色，并通过更高效和创新的谜题解决策略实现更高的动作成功率。所有数据和代码均已公开。 

---
# Bridging the User-side Knowledge Gap in Knowledge-aware Recommendations with Large Language Models 

**Title (ZH)**: 使用大型语言模型弥合知识感知推荐中的用户侧知识差距 

**Authors**: Zheng Hu, Zhe Li, Ziyun Jiao, Satoshi Nakagawa, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren  

**Link**: [PDF](https://arxiv.org/pdf/2412.13544)  

**Abstract**: In recent years, knowledge graphs have been integrated into recommender systems as item-side auxiliary information, enhancing recommendation accuracy. However, constructing and integrating structural user-side knowledge remains a significant challenge due to the improper granularity and inherent scarcity of user-side features. Recent advancements in Large Language Models (LLMs) offer the potential to bridge this gap by leveraging their human behavior understanding and extensive real-world knowledge. Nevertheless, integrating LLM-generated information into recommender systems presents challenges, including the risk of noisy information and the need for additional knowledge transfer. In this paper, we propose an LLM-based user-side knowledge inference method alongside a carefully designed recommendation framework to address these challenges. Our approach employs LLMs to infer user interests based on historical behaviors, integrating this user-side information with item-side and collaborative data to construct a hybrid structure: the Collaborative Interest Knowledge Graph (CIKG). Furthermore, we propose a CIKG-based recommendation framework that includes a user interest reconstruction module and a cross-domain contrastive learning module to mitigate potential noise and facilitate knowledge transfer. We conduct extensive experiments on three real-world datasets to validate the effectiveness of our method. Our approach achieves state-of-the-art performance compared to competitive baselines, particularly for users with sparse interactions. 

**Abstract (ZH)**: 近年来，知识图谱已被整合到推荐系统中作为物品方面的辅助信息，从而提高推荐准确性。然而，由于用户方面特征的不当粒度和固有的稀疏性，构建和整合结构化用户方面知识依然是一个重大挑战。近年来大型语言模型（LLMs）的进步为解决这一问题提供了可能，通过利用它们对人类行为的理解以及广泛的实际世界知识。然而，将LLM生成的信息整合到推荐系统中仍然存在挑战，包括_noise信息的风险_和额外知识迁移的需求。在本文中，我们提出了一种基于LLM的用户方面知识推理方法，并设计了一个精心构建的推荐框架来应对这些挑战。我们的方法利用LLM根据历史行为推断用户兴趣，并将这种用户方面的信息与物品方面的数据和合作数据相结合，构建一种混合结构：交互兴趣知识图谱（CIKG）。此外，我们提出了一种基于CIKG的推荐框架，其中包括用户兴趣重建模块和跨域对比学习模块，以减轻潜在的噪声并对知识迁移进行促进。我们在三个真实世界的数据集上进行了广泛的实验以验证我们方法的有效性。我们的方法在与竞争基线方法的对比中实现了最先进的性能，特别是在交互稀疏的用户中表现尤为显著。 

---
# Query-centric Audio-Visual Cognition Network for Moment Retrieval, Segmentation and Step-Captioning 

**Title (ZH)**: 面向查询的音视频认知网络用于时刻检索、分割和步骤标注 

**Authors**: Yunbin Tu, Liang Li, Li Su, Qingming Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13543)  

**Abstract**: Video has emerged as a favored multimedia format on the internet. To better gain video contents, a new topic HIREST is presented, including video retrieval, moment retrieval, moment segmentation, and step-captioning. The pioneering work chooses the pre-trained CLIP-based model for video retrieval, and leverages it as a feature extractor for other three challenging tasks solved in a multi-task learning paradigm. Nevertheless, this work struggles to learn the comprehensive cognition of user-preferred content, due to disregarding the hierarchies and association relations across modalities. In this paper, guided by the shallow-to-deep principle, we propose a query-centric audio-visual cognition (QUAG) network to construct a reliable multi-modal representation for moment retrieval, segmentation and step-captioning. Specifically, we first design the modality-synergistic perception to obtain rich audio-visual content, by modeling global contrastive alignment and local fine-grained interaction between visual and audio modalities. Then, we devise the query-centric cognition that uses the deep-level query to perform the temporal-channel filtration on the shallow-level audio-visual representation. This can cognize user-preferred content and thus attain a query-centric audio-visual representation for three tasks. Extensive experiments show QUAG achieves the SOTA results on HIREST. Further, we test QUAG on the query-based video summarization task and verify its good generalization. 

**Abstract (ZH)**: 视频已成为互联网上广受欢迎的多媒体格式。为了更好地获取视频内容，提出了一项新的主题HIREST，包括视频检索、关键画面检索、关键画面分割和步骤注释。这项开创性工作选择使用基于预训练的CLIP模型进行视频检索，并将其作为其他三个具有挑战性任务的特征提取器，在多任务学习范式中解决这些任务。然而，这项工作在学习用户偏好内容的全面认知方面存在困难，原因在于忽视了不同模态之间的层次结构和关联关系。本文受到从浅层到深层原则的指导，提出了一种以查询为中心的视听认知（QUAG）网络，以构建可靠多模态表示，用于关键画面检索、分割和步骤注释。具体而言，我们首先设计了视听模态协同感知，通过建模全局对比对齐和局部细粒度视听模态交互来获取丰富的视听内容。然后，我们设计了以查询为中心的认知，使用深层查询对浅层视听表示进行时间-通道过滤，从而认知用户偏好内容，因此得到以查询为中心的视听表示以应用于这三个任务。广泛的实验表明，QUAG在HIREST上取得了最优的结果。此外，我们在基于查询的视频摘要任务上测试了QUAG，并验证了其良好的泛化能力。 

---
# Tuning Music Education: AI-Powered Personalization in Learning Music 

**Title (ZH)**: 调整音乐教育：音乐学习中的AI赋能个性化教学 

**Authors**: Mayank Sanganeria, Rohan Gala  

**Link**: [PDF](https://arxiv.org/pdf/2412.13514)  

**Abstract**: Recent AI-driven step-function advances in several longstanding problems in music technology are opening up new avenues to create the next generation of music education tools. Creating personalized, engaging, and effective learning experiences are continuously evolving challenges in music education. Here we present two case studies using such advances in music technology to address these challenges. In our first case study we showcase an application that uses Automatic Chord Recognition to generate personalized exercises from audio tracks, connecting traditional ear training with real-world musical contexts. In the second case study we prototype adaptive piano method books that use Automatic Music Transcription to generate exercises at different skill levels while retaining a close connection to musical interests. These applications demonstrate how recent AI developments can democratize access to high-quality music education and promote rich interaction with music in the age of generative AI. We hope this work inspires other efforts in the community, aimed at removing barriers to access to high-quality music education and fostering human participation in musical expression. 

**Abstract (ZH)**: 近年来，人工智能驱动的阶跃式进展在音乐技术中解决了一些长期存在的问题，为创造下一代音乐教育工具开辟了新途径。个性化、具有吸引力且有效的学习体验是音乐教育中不断进化的挑战。在这里，我们运用这些音乐技术进步，呈现了两个案例研究来解决这些挑战。在我们的第一个案例研究中，我们展示了一种应用，该应用通过自动和弦识别从音频轨道中生成个性化的练习，将传统的耳听训练与现实世界的音乐情景联系起来。在第二个案例研究中，我们设计了具有自适应弹奏方法书的原型，该书结合了自动音乐转录技术，在保持与音乐兴趣密切联系的同时，生成不同技能水平的练习。这些应用展示了近期的人工智能发展如何使高质量音乐教育的获取更加普及，并促进在生成人工智能时代与音乐的丰富互动。我们希望这项工作能够激励社区中的其他努力，旨在消除高质量音乐教育的访问障碍，并促进人类在音乐表达中的参与。 

---
# VaeDiff-DocRE: End-to-end Data Augmentation Framework for Document-level Relation Extraction 

**Title (ZH)**: VaeDiff-DocRE：面向文档级关系提取的端到端数据增强框架 

**Authors**: Khai Phan Tran, Wen Hua, Xue Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.13503)  

**Abstract**: Document-level Relation Extraction (DocRE) aims to identify relationships between entity pairs within a document. However, most existing methods assume a uniform label distribution, resulting in suboptimal performance on real-world, imbalanced datasets. To tackle this challenge, we propose a novel data augmentation approach using generative models to enhance data from the embedding space. Our method leverages the Variational Autoencoder (VAE) architecture to capture all relation-wise distributions formed by entity pair representations and augment data for underrepresented relations. To better capture the multi-label nature of DocRE, we parameterize the VAE's latent space with a Diffusion Model. Additionally, we introduce a hierarchical training framework to integrate the proposed VAE-based augmentation module into DocRE systems. Experiments on two benchmark datasets demonstrate that our method outperforms state-of-the-art models, effectively addressing the long-tail distribution problem in DocRE. 

**Abstract (ZH)**: 文档级关系抽取（DocRE）旨在识别文档中实体对之间的关系。然而，现有的大多数方法假设标签分布均匀，这导致在实际的、类别分布不平衡的数据集上表现不佳。为应对这一挑战，我们提出了一种新颖的数据增强方法，利用生成模型在嵌入空间增强数据。我们的方法利用变分自编码器（VAE）架构捕获由实体对表示形成的全部关系分布，并为数据稀少的关系增强数据。为了更好地捕捉DocRE的多标签性质，我们通过扩散模型参数化VAE的潜在空间。此外，我们引入了一个基于层次结构的训练框架，将提议的基于VAE的增强模块整合到DocRE系统中。在两个基准数据集上的实验表明，我们的方法优于现有最先进的模型，有效地解决了DocRE中的长尾分布问题。 

---
# Federated t-SNE and UMAP for Distributed Data Visualization 

**Title (ZH)**: 联邦t-SNE和UMAP在分布式数据可视化中的应用 

**Authors**: Dong Qiao, Xinxian Ma, Jicong Fan  

**Link**: [PDF](https://arxiv.org/pdf/2412.13495)  

**Abstract**: High-dimensional data visualization is crucial in the big data era and these techniques such as t-SNE and UMAP have been widely used in science and engineering. Big data, however, is often distributed across multiple data centers and subject to security and privacy concerns, which leads to difficulties for the standard algorithms of t-SNE and UMAP. To tackle the challenge, this work proposes Fed-tSNE and Fed-UMAP, which provide high-dimensional data visualization under the framework of federated learning, without exchanging data across clients or sending data to the central server. The main idea of Fed-tSNE and Fed-UMAP is implicitly learning the distribution information of data in a manner of federated learning and then estimating the global distance matrix for t-SNE and UMAP. To further enhance the protection of data privacy, we propose Fed-tSNE+ and Fed-UMAP+. We also extend our idea to federated spectral clustering, yielding algorithms of clustering distributed data. In addition to these new algorithms, we offer theoretical guarantees of optimization convergence, distance and similarity estimation, and differential privacy. Experiments on multiple datasets demonstrate that, compared to the original algorithms, the accuracy drops of our federated algorithms are tiny. 

**Abstract (ZH)**: 高维数据可视化的技术在大数据时代至关重要，诸如t-SNE和UMAP等技术已被广泛应用于科学和技术领域。然而，大数据往往分布在多个数据中心，并且存在安全和隐私问题，这给标准的t-SNE和UMAP算法带来了挑战。为应对这一挑战，本研究提出了Fed-tSNE和Fed-UMAP，它们在联邦学习框架下提供了高维数据可视化的解决方案，无需在客户端之间交换数据或发送数据到中央服务器。Fed-tSNE和Fed-UMAP的主要思想是在联邦学习的方式下隐式地学习数据的分布信息，然后分别估计t-SNE和UMAP所需的整体距离矩阵。为了进一步增强数据隐私保护，我们还提出了Fed-tSNE+和Fed-UMAP+。此外，我们将该想法扩展到联邦谱聚类，提出了处理分布在不同节点上的数据的聚类算法。除了这些新的算法，我们还提供了优化收敛、距离和相似性估计以及差分隐私的理论保证。多组数据集上的实验表明，与其他原始算法相比，我们提出的联邦算法的精度损失微乎其微。 

---
# Refining Salience-Aware Sparse Fine-Tuning Strategies for Language Models 

**Title (ZH)**: 精炼注意力导向的稀疏微调策略以优化语言模型 

**Authors**: Xinxin Liu, Aaron Thomas, Cheng Zhang, Jianyi Cheng, Yiren Zhao, Xitong Gao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13488)  

**Abstract**: Parameter-Efficient Fine-Tuning (PEFT) has gained prominence through low-rank adaptation methods like LoRA. In this paper, we focus on sparsity-based PEFT (SPEFT), which introduces trainable sparse adaptations to the weight matrices in the model, offering greater flexibility in selecting fine-tuned parameters compared to low-rank methods. We conduct the first systematic evaluation of salience metrics for SPEFT, inspired by zero-cost NAS proxies, and identify simple gradient-based metrics is reliable, and results are on par with the best alternatives, offering both computational efficiency and robust performance. Additionally, we compare static and dynamic masking strategies, finding that static masking, which predetermines non-zero entries before training, delivers efficiency without sacrificing performance, while dynamic masking offers no substantial benefits. Across NLP tasks, a simple gradient-based, static SPEFT consistently outperforms other fine-tuning methods for LLMs, providing a simple yet effective baseline for SPEFT. Our work challenges the notion that complexity is necessary for effective PEFT. Our work is open source and available to the community at [this https URL]. 

**Abstract (ZH)**: 参数高效微调（PEFT）通过低秩适应方法如LoRA取得了显著进展。本文我们专注于基于稀疏性的PEFT（SPEFT），它引入了对模型权重矩阵进行可训练的稀疏适应，与低秩方法相比，提供了更大的精细调谐参数选择灵活性。我们首次系统评估了SPEFT的显著性度量，受到零成本NAS代理的启发，发现基于梯度的简单度量是可靠的，其性能与最佳替代方案相当，不仅计算效率高，且表现稳健。此外，我们还比较了静态和动态掩码策略，发现静态掩码，在训练前预先确定非零项，能在不牺牲性能的情况下提高效率，而动态掩码则没有明显的益处。在自然语言处理（NLP）任务中，简单的基于梯度的静态SPEFT在大型语言模型（LLM）的微调方法中始终表现出色，为SPEFT提供了简单而有效的基准。我们的工作挑战了有效PEFT需要复杂性的观点。我们的工作是开源的，并可在[此处](请提供具体链接)获得。 

---
# Generating Unseen Nonlinear Evolution in Sea Surface Temperature Using a Deep Learning-Based Latent Space Data Assimilation Framework 

**Title (ZH)**: 使用基于深度学习的隐空间数据同化框架生成未见的海面温度非线性演变 

**Authors**: Qingyu Zheng, Guijun Han, Wei Li, Lige Cao, Gongfu Zhou, Haowen Wu, Qi Shao, Ru Wang, Xiaobo Wu, Xudong Cui, Hong Li, Xuan Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13477)  

**Abstract**: Advances in data assimilation (DA) methods have greatly improved the accuracy of Earth system predictions. To fuse multi-source data and reconstruct the nonlinear evolution missing from observations, geoscientists are developing future-oriented DA methods. In this paper, we redesign a purely data-driven latent space DA framework (DeepDA) that employs a generative artificial intelligence model to capture the nonlinear evolution in sea surface temperature. Under variational constraints, DeepDA embedded with nonlinear features can effectively fuse heterogeneous data. The results show that DeepDA remains highly stable in capturing and generating nonlinear evolutions even when a large amount of observational information is missing. It can be found that when only 10% of the observation information is available, the error increase of DeepDA does not exceed 40%. Furthermore, DeepDA has been shown to be robust in the fusion of real observations and ensemble simulations. In particular, this paper provides a mechanism analysis of the nonlinear evolution generated by DeepDA from the perspective of physical patterns, which reveals the inherent explainability of our DL model in capturing multi-scale ocean signals. 

**Abstract (ZH)**: 数据同化（DA）方法的进步极大地提高了地球系统预测的准确性。为了融合多源数据并重建因观测不足而缺失的非线性演变，地球科学家正在开发未来的DA方法。在本文中，我们重新设计了一个纯数据驱动的潜在空间DA框架（DeepDA），该框架利用生成性人工智能模型捕捉海表温度的非线性演变。通过变分约束，DeepDA嵌入非线性特征，可以有效融合异质数据。结果表明，即使大量观测信息缺失，DeepDA在捕捉和生成非线性演变方面仍保持高度稳定。研究发现，在仅有10%的观测信息可用的情况下，DeepDA的误差增加不超过40%。此外，DeepDA在实际观测与集合模拟的融合中表现出鲁棒性。特别是在本文中，从物理模式的角度分析了由DeepDA生成的非线性演变机制，揭示了我们的DL模型在捕获多尺度海洋信号方面的固有可解释性。 

---
# A Statistical and Multi-Perspective Revisiting of the Membership Inference Attack in Large Language Models 

**Title (ZH)**: 大规模语言模型中成员推理攻击的一种统计与多视角 revisit 分析 

**Authors**: Bowen Chen, Namgi Han, Yusuke Miyao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13475)  

**Abstract**: The lack of data transparency in Large Language Models (LLMs) has highlighted the importance of Membership Inference Attack (MIA), which differentiates trained (member) and untrained (non-member) data. Though it shows success in previous studies, recent research reported a near-random performance in different settings, highlighting a significant performance inconsistency. We assume that a single setting doesn't represent the distribution of the vast corpora, causing members and non-members with different distributions to be sampled and causing inconsistency. In this study, instead of a single setting, we statistically revisit MIA methods from various settings with thousands of experiments for each MIA method, along with study in text feature, embedding, threshold decision, and decoding dynamics of members and non-members. We found that (1) MIA performance improves with model size and varies with domains, while most methods do not statistically outperform baselines, (2) Though MIA performance is generally low, a notable amount of differentiable member and non-member outliers exists and vary across MIA methods, (3) Deciding a threshold to separate members and non-members is an overlooked challenge, (4) Text dissimilarity and long text benefit MIA performance, (5) Differentiable or not is reflected in the LLM embedding, (6) Member and non-members show different decoding dynamics. 

**Abstract (ZH)**: 大型语言模型（LLMs）数据透明度的缺乏凸显了成员推断攻击（MIA）的重要性，它能够区分训练数据（成员）和未训练数据（非成员）。尽管过去的研究中显示出了成功，但最近的研究在不同的设置中报告了近乎随机的表现，这突显了性能一致性方面的显著问题。我们认为单一设置不能代表广泛语料库的分布，导致了具有不同分布的成员和非成员数据被采样，从而引起了一致性问题。在本次研究中，我们没有局限于单一设置，而是通过数千次实验重新审视了各种设置下的MIA方法，并考察了成员和非成员的文本特征、嵌入、门限决策以及解码动态。我们的研究发现如下：

(1) MIA性能随着模型规模的增大而提高，并且在不同领域中表现出差异，但大多数方法并未在统计上超越基准；
(2) 尽管MIA性能整体较低，但在不同MIA方法中仍存在显著可区分的成员和非成员异常值；
(3) 决定门限以区分成员和非成员是一项被忽视的挑战；
(4) 文本差异性和长文本有助于提高MIA性能；
(5) 成员和非成员的可区分性体现在LLM的嵌入中；
(6) 成员和非成员表现出不同的解码动态。 

---
# Transducer Tuning: Efficient Model Adaptation for Software Tasks Using Code Property Graphs 

**Title (ZH)**: 转换器调优：使用代码属性图进行软件任务的高效模型适应 

**Authors**: Imam Nur Bani Yusuf, Lingxiao Jiang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13467)  

**Abstract**: Large language models have demonstrated promising performance across various software engineering tasks. While fine-tuning is a common practice to adapt these models for downstream tasks, it becomes challenging in resource-constrained environments due to increased memory requirements from growing trainable parameters in increasingly large language models. We introduce \approach, a technique to adapt large models for downstream code tasks using Code Property Graphs (CPGs). Our approach introduces a modular component called \transducer that enriches code embeddings with structural and dependency information from CPGs. The Transducer comprises two key components: Graph Vectorization Engine (GVE) and Attention-Based Fusion Layer (ABFL). GVE extracts CPGs from input source code and transforms them into graph feature vectors. ABFL then fuses those graphs feature vectors with initial code embeddings from a large language model. By optimizing these transducers for different downstream tasks, our approach enhances the models without the need to fine-tune them for specific tasks. We have evaluated \approach on three downstream tasks: code summarization, assert generation, and code translation. Our results demonstrate competitive performance compared to full parameter fine-tuning while reducing up to 99\% trainable parameters to save memory. \approach also remains competitive against other fine-tuning approaches (e.g., LoRA, Prompt-Tuning, Prefix-Tuning) while using only 1.5\%-80\% of their trainable parameters. Our findings show that integrating structural and dependency information through Transducer Tuning enables more efficient model adaptation, making it easier for users to adapt large models in resource-constrained settings. 

**Abstract (ZH)**: 大型语言模型已经在各种软件工程任务中显示出令人鼓舞的性能。虽然微调是适应这些模型以完成下游任务的一种常见做法，但在资源受限的环境中，由于大型语言模型中可训练参数规模扩大导致的内存需求增加，使得微调变得具有挑战性。我们提出了一种名为 \approach 的技术，该技术使用代码属性图（CPGs）来适应大型模型以用于下游代码任务。该方法引入了一个模块化的组件 \transducer，该组件通过从CPGs中提取结构性和依赖性信息来丰富代码嵌入。Transducer 包含两个关键组件：图向量化引擎（GVE）和注意力融合层（ABFL）。GVE 从输入源代码中提取 CPG，并将其转换为图形特征向量。ABFL 然后将这些图形特征向量与大型语言模型的初始代码嵌入融合在一起。通过针对不同的下游任务优化这些转换器，我们的方法可以在无需特定任务微调的情况下提升模型性能。我们已在三种下游任务上评估了 \approach：代码摘要、断言生成和代码翻译。我们的结果表明，与完全参数微调相比，这种方法在节省内存的同时表现出了竞争力，并且通过显着减少可训练参数（最多高达99%）来提高性能。相比其他微调方法（例如 LoRA、提示微调、前缀微调），\approach 使用的可训练参数范围仅为1.5% 到 80%，同时仍然保持竞争性的性能。我们的研究结果表明，通过使用 Transducer 调整集成结构性和依赖性信息，可以实现更高效的模型调整，从而使用户在资源受限的环境中更轻松地调整大型模型。 

---
# FlexPose: Pose Distribution Adaptation with Limited Guidance 

**Title (ZH)**: FlexPose：在有限指导下的姿态分布适应 

**Authors**: Zixiao Wang, Junwu Weng, Mengyuan Liu, Bei Yu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13463)  

**Abstract**: Numerous well-annotated human key-point datasets are publicly available to date. However, annotating human poses for newly collected images is still a costly and time-consuming progress. Pose distributions from different datasets share similar pose hinge-structure priors with different geometric transformations, such as pivot orientation, joint rotation, and bone length ratio. The difference between Pose distributions is essentially the difference between the transformation distributions. Inspired by this fact, we propose a method to calibrate a pre-trained pose generator in which the pose prior has already been learned to an adapted one following a new pose distribution. We treat the representation of human pose joint coordinates as skeleton image and transfer a pre-trained pose annotation generator with only a few annotation guidance. By fine-tuning a limited number of linear layers that closely related to the pose transformation, the adapted generator is able to produce any number of pose annotations that are similar to the target poses. We evaluate our proposed method, FlexPose, on several cross-dataset settings both qualitatively and quantitatively, which demonstrates that our approach achieves state-of-the-art performance compared to the existing generative-model-based transfer learning methods when given limited annotation guidance. 

**Abstract (ZH)**: 截至目前，公开可用的人体关键点标注数据集数量众多。然而，对新收集的图像进行人体姿态标注仍然是一个成本高且耗时的过程。来自不同数据集的姿势分布具有一致的姿态铰链结构先验，尽管有不同几何变换，如枢轴方向、关节旋转和骨长比例。姿势分布之间的差异本质上是这些变换分布之间的差异。受这一事实的启发，我们提出了一种方法，该方法可以校准一个预训练的姿态生成器，使其姿态先验适应新的姿势分布。我们将人体姿态关节坐标表示为骨架图像，并仅使用少量标注指导转移一个预训练的姿态标注生成器。通过微调与姿态变换紧密相关的少量线性层，适应后的生成器能够生成与目标姿态相似的任意数量的姿态标注。我们在几个跨数据集设置中对所提出的方法FlexPose进行了定性和定量评估，结果显示，在仅有限标注指导的情况下，我们的方法在现有的生成模型为基础的转移学习方法中达到了最先进的性能。 

---
# Look Inside for More: Internal Spatial Modality Perception for 3D Anomaly Detection 

**Title (ZH)**: 深入探究：内部空间模态感知在3D异常检测中的应用 

**Authors**: Hanzhe Liang, Guoyang Xie, Chengbin Hou, Bingshu Wang, Can Gao, Jinbao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13461)  

**Abstract**: 3D anomaly detection has recently become a significant focus in computer vision. Several advanced methods have achieved satisfying anomaly detection performance. However, they typically concentrate on the external structure of 3D samples and struggle to leverage the internal information embedded within samples. Inspired by the basic intuition of why not look inside for more, we introduce a straightforward method named Internal Spatial Modality Perception (ISMP) to explore the feature representation from internal views fully. Specifically, our proposed ISMP consists of a critical perception module, Spatial Insight Engine (SIE), which abstracts complex internal information of point clouds into essential global features. Besides, to better align structural information with point data, we propose an enhanced key point feature extraction module for amplifying spatial structure feature representation. Simultaneously, a novel feature filtering module is incorporated to reduce noise and redundant features for further aligning precise spatial structure. Extensive experiments validate the effectiveness of our proposed method, achieving object-level and pixel-level AUROC improvements of 4.2% and 13.1%, respectively, on the Real3D-AD benchmarks. Note that the strong generalization ability of SIE has been theoretically proven and is verified in both classification and segmentation tasks. 

**Abstract (ZH)**: 三维异常检测近年来已成为计算机视觉领域的一个重要研究方向。多种先进的方法已经取得了令人满意的异常检测性能。然而，这些方法通常侧重于3D样本的外部结构，难以充分利用嵌入在样本中的内部信息。受到为什么不从内部寻找更多信息的基本直觉的启发，我们提出了一种简单的内部空间模态感知（ISMP）方法，旨在从内部视图全面探索特征表示。具体来说，我们提出的ISMP包含一个关键的感知模块——空间洞察引擎（SIE），它将点云中的复杂内部信息抽象为基本的全局特征。此外，为了更好地对齐结构信息和点数据，我们提出了一种增强的关键点特征提取模块，以增强空间结构特征的表示。同时，我们引入了一种新的特征滤波模块，以减少噪声和冗余特征，进一步对准精确的空间结构。广泛的实验验证了我们提出方法的有效性，相对于Real3D-AD基准，在对象级别和像素级别分别实现了4.2%和13.1%的AUROC改进。值得注意的是，SIE的强泛化能力已在理论层面得到证明，并在分类和分割任务中得到了验证。 

---
# Pre-training a Density-Aware Pose Transformer for Robust LiDAR-based 3D Human Pose Estimation 

**Title (ZH)**: 基于LiDAR的鲁棒三维人体姿态估计中预训练密度意识姿态变换器 

**Authors**: Xiaoqi An, Lin Zhao, Chen Gong, Jun Li, Jian Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13454)  

**Abstract**: With the rapid development of autonomous driving, LiDAR-based 3D Human Pose Estimation (3D HPE) is becoming a research focus. However, due to the noise and sparsity of LiDAR-captured point clouds, robust human pose estimation remains challenging. Most of the existing methods use temporal information, multi-modal fusion, or SMPL optimization to correct biased results. In this work, we try to obtain sufficient information for 3D HPE only by modeling the intrinsic properties of low-quality point clouds. Hence, a simple yet powerful method is proposed, which provides insights both on modeling and augmentation of point clouds. Specifically, we first propose a concise and effective density-aware pose transformer (DAPT) to get stable keypoint representations. By using a set of joint anchors and a carefully designed exchange module, valid information is extracted from point clouds with different densities. Then 1D heatmaps are utilized to represent the precise locations of the keypoints. Secondly, a comprehensive LiDAR human synthesis and augmentation method is proposed to pre-train the model, enabling it to acquire a better human body prior. We increase the diversity of point clouds by randomly sampling human positions and orientations and by simulating occlusions through the addition of laser-level masks. Extensive experiments have been conducted on multiple datasets, including IMU-annotated LidarHuman26M, SLOPER4D, and manually annotated Waymo Open Dataset v2.0 (Waymo), HumanM3. Our method demonstrates SOTA performance in all scenarios. In particular, compared with LPFormer on Waymo, we reduce the average MPJPE by $10.0mm$. Compared with PRN on SLOPER4D, we notably reduce the average MPJPE by $20.7mm$. 

**Abstract (ZH)**: 随着自动驾驶的快速发展，基于LiDAR的三维人体姿态估计（3D HPE）已成为研究热点。然而，由于LiDAR捕获点云中存在噪声和稀疏性，稳健的人体姿态估计仍然具有挑战性。目前大多数方法通过使用时空信息、多模态融合或SMPL优化来纠正偏差结果。本文尝试仅通过建模低质量点云的固有属性来获取足够的信息进行3D HPE。因此，提出了一种简单而强大的方法，该方法在建模和点云增强方面提供了见解。具体而言，我们首先提出了一种简洁且有效的密度感知姿态变换器（DAPT），以获得稳定的关节点表示。通过使用一组关节锚点和精心设计的交换模块，从不同密度的点云中提取有效信息。然后使用一维热图来表示关节点的精确位置。其次，提出了一种全面的LiDAR人体合成和增强方法，以预先训练模型，使其能够获得更好的人体先验知识。我们通过随机取样人体位置和方向，并通过添加激光级别遮挡来增加点云的多样性。在多个数据集上进行了广泛的实验，包括IMU注释的LidarHuman26M、SLOPER4D和手动注释的Waymo Open Dataset v2.0（Waymo）以及HumanM3。我们的方法在所有场景中均显示了当前最佳性能。特别是在Waymo与LPFormer相比时，我们平均MPJPE减少了10.0毫米。与SLOPER4D上的PRN相比，我们显著降低了平均MPJPE，减少了20.7毫米。 

---
# ConDo: Continual Domain Expansion for Absolute Pose Regression 

**Title (ZH)**: ConDo: 绝对位姿回归的持续域扩展 

**Authors**: Zijun Li, Zhipeng Cai, Bochun Yang, Xuelun Shen, Siqi Shen, Xiaoliang Fan, Michael Paulitsch, Cheng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13452)  

**Abstract**: Visual localization is a fundamental machine learning problem. Absolute Pose Regression (APR) trains a scene-dependent model to efficiently map an input image to the camera pose in a pre-defined scene. However, many applications have continually changing environments, where inference data at novel poses or scene conditions (weather, geometry) appear after deployment. Training APR on a fixed dataset leads to overfitting, making it fail catastrophically on challenging novel data. This work proposes Continual Domain Expansion (ConDo), which continually collects unlabeled inference data to update the deployed APR. Instead of applying standard unsupervised domain adaptation methods which are ineffective for APR, ConDo effectively learns from unlabeled data by distilling knowledge from scene-agnostic localization methods. By sampling data uniformly from historical and newly collected data, ConDo can effectively expand the generalization domain of APR. Large-scale benchmarks with various scene types are constructed to evaluate models under practical (long-term) data changes. ConDo consistently and significantly outperforms baselines across architectures, scene types, and data changes. On challenging scenes (Fig.1), it reduces the localization error by >7x (14.8m vs 1.7m). Analysis shows the robustness of ConDo against compute budgets, replay buffer sizes and teacher prediction noise. Comparing to model re-training, ConDo achieves similar performance up to 25x faster. 

**Abstract (ZH)**: 视觉定位是机器学习中的一个基础问题。绝对姿态回归（APR）训练一个场景依赖模型，以高效地将输入图像映射到预定义场景中的相机姿态。然而，许多应用程序具有不断变化的环境，在部署后会出现新的姿态或场景条件（天气、几何结构），导致先前训练的数据无法应对具有挑战性的新型数据。本研究提出了连续域扩展（ConDo），该方法持续收集未标记的推理数据以更新部署中的APR。与标准的无监督领域适应方法不同，这些方法对APR无效，ConDo 通过从场景无关的定位方法中提取知识来有效地学习未标记数据。通过从历史和新收集的数据中均匀采样数据，ConDo 可以有效地扩展APR的泛化域。构建了多种场景类型的大型基准数据集，以评估模型在实际的数据变化（长期）下的表现。ConDo 在各种架构、场景类型和数据变化情况下均显着优于基线模型。在具有挑战性的场景中（图1），它将定位误差降低了7倍以上（从14.8米降至1.7米）。分析表明，ConDo 对计算预算、重播缓冲区大小和教师预测噪声具有鲁棒性。与重新训练模型相比，ConDo 在相同性能水平上达到所需的训练时间可快25倍。 

---
# Toward an Insider Threat Education Platform: A Theoretical Literature Review 

**Title (ZH)**: 朝向内部威胁教育培训平台：理论文献综述 

**Authors**: Haywood Gelman, John D. Hastings, David Kenley, Eleanor Loiacono  

**Link**: [PDF](https://arxiv.org/pdf/2412.13446)  

**Abstract**: Insider threats (InTs) within organizations are small in number but have a disproportionate ability to damage systems, information, and infrastructure. Existing InT research studies the problem from psychological, technical, and educational perspectives. Proposed theories include research on psychological indicators, machine learning, user behavioral log analysis, and educational methods to teach employees recognition and mitigation techniques. Because InTs are a human problem, training methods that address InT detection from a behavioral perspective are critical. While numerous technological and psychological theories exist on detection, prevention, and mitigation, few training methods prioritize psychological indicators. This literature review studied peer-reviewed, InT research organized by subtopic and extracted critical theories from psychological, technical, and educational disciplines. In doing so, this is the first study to comprehensively organize research across all three approaches in a manner which properly informs the development of an InT education platform. 

**Abstract (ZH)**: 组织内部的内部威胁（InTs）虽然数量较少，但对系统、信息和基础设施造成的损害却是不成比例的。现有关于内部威胁的研究从心理、技术和教育角度探讨了这一问题。提出的理论包括心理指标研究、机器学习、用户行为日志分析以及教育方法等，旨在教授员工识别和缓解技巧。由于内部威胁本质上是人的问题，因此从行为角度进行内部威胁检测的训练方法至关重要。虽然存在多种技术与心理理论来检测、预防和缓解内部威胁，但很少有训练方法会优先考虑心理指标。本次文献综述按照主题对经过同行评审的内部威胁研究进行了整理，并从心理、技术与教育三个学科领域中提炼出关键理论。以此为基础，这是首次全面整理三种方法的研究成果，并以这种方式全面指导内部威胁教育平台的开发。 

---
# Communication-Efficient Personalized Federal Graph Learning via Low-Rank Decomposition 

**Title (ZH)**: 通过低秩分解实现的通信高效个性化联邦图学习 

**Authors**: Ruyue Liu, Rong Yin, Xiangzhen Bo, Xiaoshuai Hao, Xingrui Zhou, Yong Liu, Can Ma, Weiping Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13442)  

**Abstract**: Federated graph learning (FGL) has gained significant attention for enabling heterogeneous clients to process their private graph data locally while interacting with a centralized server, thus maintaining privacy. However, graph data on clients are typically non-IID, posing a challenge for a single model to perform well across all clients. Another major bottleneck of FGL is the high cost of communication. To address these challenges, we propose a communication-efficient personalized federated graph learning algorithm, CEFGL. Our method decomposes the model parameters into low-rank generic and sparse private models. We employ a dual-channel encoder to learn sparse local knowledge in a personalized manner and low-rank global knowledge in a shared manner. Additionally, we perform multiple local stochastic gradient descent iterations between communication phases and integrate efficient compression techniques into the algorithm. The advantage of CEFGL lies in its ability to capture common and individual knowledge more precisely. By utilizing low-rank and sparse parameters along with compression techniques, CEFGL significantly reduces communication complexity. Extensive experiments demonstrate that our method achieves optimal classification accuracy in a variety of heterogeneous environments across sixteen datasets. Specifically, compared to the state-of-the-art method FedStar, the proposed method (with GIN as the base model) improves accuracy by 5.64\% on cross-datasets setting CHEM, reduces communication bits by a factor of 18.58, and reduces the communication time by a factor of 1.65. 

**Abstract (ZH)**: 联邦图学习（FGL）由于能够使异构客户端在其本地处理私人图数据的同时与集中式服务器进行交互，从而保持隐私，而获得了广泛关注。然而，客户端上的图数据通常是非IID的，这对单一模型在所有客户端上表现出色构成了挑战。另一个主要瓶颈是FGL的高通信成本。为了解决这些挑战，我们提出了一种高效的个性化联邦图学习算法，即CEFGL（Communication-Efficient Federated Graph Learning）。我们的方法将模型参数分解为低秩通用和稀疏私有模型。我们使用双通道编码器以个性化方式学习稀疏局部知识，并以共享方式学习低秩全局知识。此外，我们在通信阶段之间执行多次局部随机梯度下降迭代，并将高效的压缩技术集成到算法中。CEFGL的优势在于其能够更准确地捕捉共性和个体知识。通过使用低秩和稀疏参数以及压缩技术，CEFGL显着减少了通信复杂度。实验结果显示，该方法在十六个数据集的多种异构环境中实现了最佳分类准确性。具体而言，与最先进的方法FedStar相比，在CHEM交叉数据集设置下，基于GIN的基本模型，该方法提高了5.64%的准确性，减少了18.58倍的通信比特，并减少了1.65倍的通信时间。 

---
# FlashVTG: Feature Layering and Adaptive Score Handling Network for Video Temporal Grounding 

**Title (ZH)**: FlashVTG：特征层析和自适应评分处理网络用于视频时间定位 

**Authors**: Zhuo Cao, Bingqing Zhang, Heming Du, Xin Yu, Xue Li, Sen Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13441)  

**Abstract**: Text-guided Video Temporal Grounding (VTG) aims to localize relevant segments in untrimmed videos based on textual descriptions, encompassing two subtasks: Moment Retrieval (MR) and Highlight Detection (HD). Although previous typical methods have achieved commendable results, it is still challenging to retrieve short video moments. This is primarily due to the reliance on sparse and limited decoder queries, which significantly constrain the accuracy of predictions. Furthermore, suboptimal outcomes often arise because previous methods rank predictions based on isolated predictions, neglecting the broader video context. To tackle these issues, we introduce FlashVTG, a framework featuring a Temporal Feature Layering (TFL) module and an Adaptive Score Refinement (ASR) module. The TFL module replaces the traditional decoder structure to capture nuanced video content variations across multiple temporal scales, while the ASR module improves prediction ranking by integrating context from adjacent moments and multi-temporal-scale features. Extensive experiments demonstrate that FlashVTG achieves state-of-the-art performance on four widely adopted datasets in both MR and HD. Specifically, on the QVHighlights dataset, it boosts mAP by 5.8% for MR and 3.3% for HD. For short-moment retrieval, FlashVTG increases mAP to 125% of previous SOTA performance. All these improvements are made without adding training burdens, underscoring its effectiveness. Our code is available at this https URL. 

**Abstract (ZH)**: 基于文本引导的视频时间定位（VTG）旨在根据文本描述在未裁剪的视频中定位相关片段，涵盖两个子任务：时刻检索（MR）和高光检测（HD）。尽管以往的传统方法取得了可喜的成果，但在检索短视频片段方面仍然存在挑战。这主要归因于对稀疏且有限的解码器查询的依赖，这显著限制了预测的准确性。此外，由于先前的方法仅根据孤立的预测进行排名，忽略了更广泛的视频上下文，因此常常导致次优结果。为解决这些问题，我们引入了FlashVTG框架，该框架包含一个时间特征分层（TFL）模块和一个自适应评分精炼（ASR）模块。TFL模块替换传统的解码器结构，以捕捉多时间尺度下的细微视频内容变化，而ASR模块通过整合相邻时刻和多时间尺度特征来改进预测排名。大量的实验表明，FlashVTG在四个广泛采用的数据集的MR和HD任务中均实现了最先进的性能。具体来说，在QVHighlights数据集上，它将MR的mAP提升了5.8%，HD的mAP提升了3.3%。对于短片段检索，FlashVTG将mAP提高到了之前最佳性能的125%。所有这些改进均未增加训练负担，突显了其有效性。我们的代码可在以下链接获得：[链接地址]。 

---
# Deploying Foundation Model Powered Agent Services: A Survey 

**Title (ZH)**: 基于基础模型的代理服务部署：一个综述 

**Authors**: Wenchao Xu, Jinyu Chen, Peirong Zheng, Xiaoquan Yi, Tianyi Tian, Wenhui Zhu, Quan Wan, Haozhao Wang, Yunfeng Fan, Qinliang Su, Xuemin Shen  

**Link**: [PDF](https://arxiv.org/pdf/2412.13437)  

**Abstract**: Foundation model (FM) powered agent services are regarded as a promising solution to develop intelligent and personalized applications for advancing toward Artificial General Intelligence (AGI). To achieve high reliability and scalability in deploying these agent services, it is essential to collaboratively optimize computational and communication resources, thereby ensuring effective resource allocation and seamless service delivery. In pursuit of this vision, this paper proposes a unified framework aimed at providing a comprehensive survey on deploying FM-based agent services across heterogeneous devices, with the emphasis on the integration of model and resource optimization to establish a robust infrastructure for these services. Particularly, this paper begins with exploring various low-level optimization strategies during inference and studies approaches that enhance system scalability, such as parallelism techniques and resource scaling methods. The paper then discusses several prominent FMs and investigates research efforts focused on inference acceleration, including techniques such as model compression and token reduction. Moreover, the paper also investigates critical components for constructing agent services and highlights notable intelligent applications. Finally, the paper presents potential research directions for developing real-time agent services with high Quality of Service (QoS). 

**Abstract (ZH)**: 基于基础模型（Foundation Model, FM）的代理服务被视为开发面向通用人工智能（AGI）的智能和个人化应用的一种有前途的解决方案。为了在部署这些代理服务时实现高可靠性和可扩展性，需要协作优化计算和通信资源，以确保有效的资源分配和无缝服务交付。为此，本文提出了一种统一框架，旨在提供全面的概述，以跨异构设备部署基于FM的代理服务，并强调模型和资源优化的整合，从而建立这些服务的稳健基础设施。特别地，本文首先探讨了推理期间的各种低层优化策略，并研究了提高系统可扩展性的方法，如并行技术及资源扩展方法。接着，本文讨论了几种主要的FM，并调查了加快推理的研究努力，包括模型压缩和token减少等技术。此外，本文还详细研究了构建代理服务的关键组件，并突出了值得注意的智能应用。最后，本文提出了开发具有高服务质量（QoS）的实时代理服务的研究方向。 

---
# Lightweight Safety Classification Using Pruned Language Models 

**Title (ZH)**: 使用剪枝语言模型的轻量级安全性分类 

**Authors**: Mason Sawtell, Tula Masterman, Sandi Besen, Jim Brown  

**Link**: [PDF](https://arxiv.org/pdf/2412.13435)  

**Abstract**: In this paper, we introduce a novel technique for content safety and prompt injection classification for Large Language Models. Our technique, Layer Enhanced Classification (LEC), trains a Penalized Logistic Regression (PLR) classifier on the hidden state of an LLM's optimal intermediate transformer layer. By combining the computational efficiency of a streamlined PLR classifier with the sophisticated language understanding of an LLM, our approach delivers superior performance surpassing GPT-4o and special-purpose models fine-tuned for each task. We find that small general-purpose models (Qwen 2.5 sizes 0.5B, 1.5B, and 3B) and other transformer-based architectures like DeBERTa v3 are robust feature extractors allowing simple classifiers to be effectively trained on fewer than 100 high-quality examples. Importantly, the intermediate transformer layers of these models typically outperform the final layer across both classification tasks. Our results indicate that a single general-purpose LLM can be used to classify content safety, detect prompt injections, and simultaneously generate output tokens. Alternatively, these relatively small LLMs can be pruned to the optimal intermediate layer and used exclusively as robust feature extractors. Since our results are consistent on different transformer architectures, we infer that robust feature extraction is an inherent capability of most, if not all, LLMs. 

**Abstract (ZH)**: 在本文中，我们提出了一种新颖的技术，用于大型语言模型的内容安全和提示注入分类。我们的技术称为层次增强分类（Layer Enhanced Classification，LEC），通过在大型语言模型（LLM）最优中间变换层的隐藏状态上训练惩罚逻辑回归（Penalized Logistic Regression，PLR）分类器，结合简化PLR分类器的计算效率和大型语言模型复杂语言理解能力，我们的方法在性能上超越了GPT-4和其他为特定任务微调的专门模型。我们发现，小型通用模型（如Qwen 2.5，其参数量分别为0.5B、1.5B和3B），以及如DeBERTa v3等其他基于变换器的架构，能够作为稳健的特征提取器，仅需要不到100个高质量示例，就能有效训练简单的分类器。重要的是，这些模型的中间变换层在两类分类任务中通常优于最终层。我们的实验结果表明，一个通用的大语言模型可以用作内容安全分类、提示注入检测以及同时生成输出标记。此外，这些相对较小的模型也可以被修剪到最优中间层，独用于稳健的特征提取。由于我们的结果在不同的变换器架构上是一致的，我们推断稳健的特征提取是大多数，如果不是所有，大语言模型的固有能力。 

---
# Large Language Model Enhanced Recommender Systems: Taxonomy, Trend, Application and Future 

**Title (ZH)**: 大型语言模型增强的推荐系统：分类、趋势、应用与未来 

**Authors**: Qidong Liu, Xiangyu Zhao, Yuhao Wang, Yejing Wang, Zijian Zhang, Yuqi Sun, Xiang Li, Maolin Wang, Pengyue Jia, Chong Chen, Wei Huang, Feng Tian  

**Link**: [PDF](https://arxiv.org/pdf/2412.13432)  

**Abstract**: Large Language Model (LLM) has transformative potential in various domains, including recommender systems (RS). There have been a handful of research that focuses on empowering the RS by LLM. However, previous efforts mainly focus on LLM as RS, which may face the challenge of intolerant inference costs by LLM. Recently, the integration of LLM into RS, known as LLM-Enhanced Recommender Systems (LLMERS), has garnered significant interest due to its potential to address latency and memory constraints in real-world applications. This paper presents a comprehensive survey of the latest research efforts aimed at leveraging LLM to enhance RS capabilities. We identify a critical shift in the field with the move towards incorporating LLM into the online system, notably by avoiding their use during inference. Our survey categorizes the existing LLMERS approaches into three primary types based on the component of the RS model being augmented: Knowledge Enhancement, Interaction Enhancement, and Model Enhancement. We provide an in-depth analysis of each category, discussing the methodologies, challenges, and contributions of recent studies. Furthermore, we highlight several promising research directions that could further advance the field of LLMERS. 

**Abstract (ZH)**: 大型语言模型（LLM）在多个领域具有变革性的潜力，包括推荐系统（RS）。已有少量研究专注于通过LLM强化RS。然而，先前的努力主要侧重于将LLM作为RS使用，这可能会面临LLM不可容忍的推理成本挑战。最近，将LLM集成到RS中的做法，即LLM增强推荐系统（LLMERS），由于其在解决实际应用中的延迟和内存限制方面的潜力而引起了广泛关注。本文介绍了利用LLM增强RS能力的最新研究进展的全面综述。我们指出，领域内的一个关键转变是将LLM集成到在线系统中，特别地，通过避免在推理过程中使用LLM。我们的综述将现有的LLMERS方法分为三种主要类型，基于增强RS模型的组件：知识增强、交互增强和模型增强。我们对每种类型进行了深入分析，讨论了最近研究的方法、挑战和贡献。此外，我们还指出了几个具有前景的研究方向，这些方向有望进一步推动LLMERS领域的进步。 

---
# Safeguarding System Prompts for LLMs 

**Title (ZH)**: 保护系统提示用于大型语言模型 

**Authors**: Zhifeng Jiang, Zhihua Jin, Guoliang He  

**Link**: [PDF](https://arxiv.org/pdf/2412.13426)  

**Abstract**: Large language models (LLMs) are increasingly utilized in applications where system prompts, which guide model outputs, play a crucial role. These prompts often contain business logic and sensitive information, making their protection essential. However, adversarial and even regular user queries can exploit LLM vulnerabilities to expose these hidden prompts. To address this issue, we present PromptKeeper, a novel defense mechanism for system prompt privacy. By reliably detecting worst-case leakage and regenerating outputs without the system prompt when necessary, PromptKeeper ensures robust protection against prompt extraction attacks via either adversarial or regular queries, while preserving conversational capability and runtime efficiency during benign user interactions. 

**Abstract (ZH)**: 大型语言模型（LLMs）在系统提示（指导模型输出）的作用日益重要的应用中被广泛使用。这些提示通常包含业务逻辑和敏感信息，因此保护它们至关重要。然而，即使是普通的用户查询，也可能利用LLM的漏洞暴露这些隐藏的提示。为了解决这一问题，我们提出了PromptKeeper，这是一种新颖的防提示泄露机制。通过可靠地检测最坏情况的泄露，并在必要时不使用系统提示再生输出，PromptKeeper确保在恶意查询和常规查询下都能对提示提取攻击提供稳健的保护，同时在良性用户交互过程中保持对话能力和运行时效率。 

---
# Lightweight yet Fine-grained: A Graph Capsule Convolutional Network with Subspace Alignment for Shared-account Sequential Recommendation 

**Title (ZH)**: 轻量而精细：一种用于共享账户序列推荐的基于子空间对齐的图胶囊卷积网络 

**Authors**: Jinyu Zhang, Zhongying Zhao, Chao Li, Yanwei Yu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13408)  

**Abstract**: Shared-account Sequential Recommendation (SSR) aims to provide personalized recommendations for accounts shared by multiple users with varying sequential preferences. Previous studies on SSR struggle to capture the fine-grained associations between interactions and different latent users within the shared account's hybrid sequences. Moreover, most existing SSR methods (e.g., RNN-based or GCN-based methods) have quadratic computational complexities, hindering the deployment of SSRs on resource-constrained devices. To this end, we propose a Lightweight Graph Capsule Convolutional Network with subspace alignment for shared-account sequential recommendation, named LightGC$^2$N. Specifically, we devise a lightweight graph capsule convolutional network. It facilitates the fine-grained matching between interactions and latent users by attentively propagating messages on the capsule graphs. Besides, we present an efficient subspace alignment method. This method refines the sequence representations and then aligns them with the finely clustered preferences of latent users. The experimental results on four real-world datasets indicate that LightGC$^2$N outperforms nine state-of-the-art methods in accuracy and efficiency. 

**Abstract (ZH)**: 共享账户序列推荐（SSR）旨在为多位用户共享且具有不同序列偏好的账户提供个性化的推荐。之前对SSR的研究难以捕捉共享账户混合序列中交互和不同潜在用户的精细关联。此外，大多数现有的SSR方法（例如基于RNN或基于GCN的方法）具有二次计算复杂度，这妨碍了在资源受限设备中部署SSR。为了解决这些问题，我们提出了一种具有子空间对齐的轻量级图胶囊卷积网络，将其命名为LightGC$^2$N。具体而言，我们设计了一种轻量级图胶囊卷积网络，通过在胶囊图上注意力传播消息来促进交互与潜在用户的精细匹配。此外，我们提出了一种有效的子空间对齐方法，该方法改进了序列表示，然后将它们与潜在用户的精细聚类偏好对齐。在四个真实数据集上的实验结果表明，LightGC$^2$N在准确性和效率方面均优于九种当前最先进的方法。 

---
# What Human-Horse Interactions may Teach us About Effective Human-AI Interactions 

**Title (ZH)**: 人类与马匹互动可能向我们揭示的有效人类与AI互动的方法 

**Authors**: Mohammad Hossein Jarrahi, Stanley Ahalt  

**Link**: [PDF](https://arxiv.org/pdf/2412.13405)  

**Abstract**: This article explores human-horse interactions as a metaphor for understanding and designing effective human-AI partnerships. Drawing on the long history of human collaboration with horses, we propose that AI, like horses, should complement rather than replace human capabilities. We move beyond traditional benchmarks such as the Turing test, which emphasize AI's ability to mimic human intelligence, and instead advocate for a symbiotic relationship where distinct intelligences enhance each other. We analyze key elements of human-horse relationships: trust, communication, and mutual adaptability, to highlight essential principles for human-AI collaboration. Trust is critical in both partnerships, built through predictability and shared understanding, while communication and feedback loops foster mutual adaptability. We further discuss the importance of taming and habituation in shaping these interactions, likening it to how humans train AI to perform reliably and ethically in real-world settings. The article also addresses the asymmetry of responsibility, where humans ultimately bear the greater burden of oversight and ethical judgment. Finally, we emphasize that long-term commitment and continuous learning are vital in both human-horse and human-AI relationships, as ongoing interaction refines the partnership and increases mutual adaptability. By drawing on these insights from human-horse interactions, we offer a vision for designing AI systems that are trustworthy, adaptable, and capable of fostering symbiotic human-AI partnerships. 

**Abstract (ZH)**: 本文探讨了人类与马匹的互动作为一个隐喻，以更好地理解和设计有效的人工智能（AI）合作伙伴关系。借鉴人类与马长期合作的历史，我们提出，AI 应该补充人类的能力，而不是取代人类的能力。我们超越了传统的测试标准，如图灵测试，后者强调了AI模仿人类智能的能力，而倡导一种共生关系，其中不同的智能互相增强。我们分析了人类与马的关键关系元素：信任、沟通和相互适应性，以突出人类与AI协作中的基本原则。信任在伙伴关系中至关重要，它通过可预测性和共同理解建立起来，而沟通和反馈循环则促进了相互适应性。我们进一步讨论了驯化和习惯化在塑造这些互动中的重要性，将人类如何训练AI在实际环境中可靠且道德地执行任务比作此过程。文章还探讨了责任不对称性问题，即人类最终承担了更多的监督和伦理判断的责任。最后，我们强调，无论是人类与马匹还是人类与AI的关系中，长期的承诺和持续的学习都是至关重要的，这些持续的互动将细化伙伴关系并提高相互适应性。通过借鉴人类与马匹互动的这些见解，我们提供了一个设计理念，即生成可信赖、适应性强，并且能够促进共生的人类与AI伙伴关系的系统。 

---
# Distribution Shifts at Scale: Out-of-distribution Detection in Earth Observation 

**Title (ZH)**: 大规模分布变化：地球观测中的异常分布检测 

**Authors**: Burak Ekim, Girmaw Abebe Tadesse, Caleb Robinson, Gilles Hacheme, Michael Schmitt, Rahul Dodhia, Juan M. Lavista Ferres  

**Link**: [PDF](https://arxiv.org/pdf/2412.13394)  

**Abstract**: Training robust deep learning models is critical in Earth Observation, where globally deployed models often face distribution shifts that degrade performance, especially in low-data regions. Out-of-distribution (OOD) detection addresses this challenge by identifying inputs that differ from in-distribution (ID) data. However, existing methods either assume access to OOD data or compromise primary task performance, making them unsuitable for real-world deployment. We propose TARDIS, a post-hoc OOD detection method for scalable geospatial deployments. The core novelty lies in generating surrogate labels by integrating information from ID data and unknown distributions, enabling OOD detection at scale. Our method takes a pre-trained model, ID data, and WILD samples, disentangling the latter into surrogate ID and surrogate OOD labels based on internal activations, and fits a binary classifier as an OOD detector. We validate TARDIS on EuroSAT and xBD datasets, across 17 experimental setups covering covariate and semantic shifts, showing that it performs close to the theoretical upper bound in assigning surrogate ID and OOD samples in 13 cases. To demonstrate scalability, we deploy TARDIS on the Fields of the World dataset, offering actionable insights into pre-trained model behavior for large-scale deployments. The code is publicly available at this https URL. 

**Abstract (ZH)**: 训练稳健的深度学习模型在地球观测中至关重要，因为广泛部署的模型经常面临分布偏移的问题，这会降低其性能，尤其是在数据量较少的地区。离分布外（OOD）检测通过识别与训练数据（ID）不同的输入来应对这一挑战。然而，现有的方法要么假设可以访问OOD数据，要么会牺牲主要任务的性能，使其不适合实际部署。我们提出了TARDIS，一种用于地理空间大规模部署的后处理OOD检测方法。其核心创新在于通过整合ID数据和未知分布的信息来生成替代标签，从而实现大规模的OOD检测。该方法以预训练模型、ID数据和WILD样本为输入，将后者按照内部激活信息分离为替代ID标签和替代OOD标签，并使用二元分类器作为OOD检测器。我们在EuroSAT和xBD数据集上验证了TARDIS，涵盖了17种实验设置，包括协变量和语义偏移，结果显示TARDIS在13种情况下将替代ID和OOD样本来分配的结果接近理论上限。为了展示可扩展性，我们将在Fields of the World数据集上部署TARDIS，提供大规模部署中预训练模型行为的 actionable 洞见。代码可在以下链接公开获取：[该 https URL]。 

---
# MMHMR: Generative Masked Modeling for Hand Mesh Recovery 

**Title (ZH)**: MMHMR：生成性掩蔽建模的手部网格恢复

解释：
- MMHMR 是 Original Paper 的缩写，保持不变。
- "Generative Masked Modeling" 翻译为 "生成性掩蔽建模"，符合学术用语。
- "Hand Mesh Recovery" 翻译为 "手部网格恢复"，这是计算机视觉和人机交互领域常见的术语。 

**Authors**: Muhammad Usama Saleem, Ekkasit Pinyoanuntapong, Mayur Jagdishbhai Patel, Hongfei Xue, Ahmed Helmy, Srijan Das, Pu Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13393)  

**Abstract**: Reconstructing a 3D hand mesh from a single RGB image is challenging due to complex articulations, self-occlusions, and depth ambiguities. Traditional discriminative methods, which learn a deterministic mapping from a 2D image to a single 3D mesh, often struggle with the inherent ambiguities in 2D-to-3D mapping. To address this challenge, we propose MMHMR, a novel generative masked model for hand mesh recovery that synthesizes plausible 3D hand meshes by learning and sampling from the probabilistic distribution of the ambiguous 2D-to-3D mapping process. MMHMR consists of two key components: (1) a VQ-MANO, which encodes 3D hand articulations as discrete pose tokens in a latent space, and (2) a Context-Guided Masked Transformer that randomly masks out pose tokens and learns their joint distribution, conditioned on corrupted token sequences, image context, and 2D pose cues. This learned distribution facilitates confidence-guided sampling during inference, producing mesh reconstructions with low uncertainty and high precision. Extensive evaluations on benchmark and real-world datasets demonstrate that MMHMR achieves state-of-the-art accuracy, robustness, and realism in 3D hand mesh reconstruction. Project website: this https URL 

**Abstract (ZH)**: 从单张RGB图像重建三维手部网格具有挑战性，因为存在复杂的关节动作、自遮挡和深度模糊等问题。传统的判别方法通过从2D图像到单个3D网格的确定性映射学习，往往难以解决2D到3D映射中存在的固有模糊性。为了解决这一挑战，我们提出了一种新颖的生成掩码模型MMHMR，通过学习和从模糊的2D到3D映射过程的概率分布中采样来合成合理的手部网格。MMHMR 包含两个关键组件：(1) VQ-MANO，它将3D手部动作编码为在潜在空间中的离散姿态令牌，以及 (2) 上下文引导的掩码变压器，随机掩码掉姿态令牌，并在受损令牌序列、图像上下文和2D姿态线索的条件下学习它们的联合分布。这种学习到的分布有助于推断过程中的信心指导采样，从而生成低不确定性且高精度的手部网格重建。在基准和真实世界数据集上的广泛评估表明，MMHMR 在3D手部网格重建方面达到了最先进的精度、鲁棒性和逼真度。项目网站：[此处链接] 

---
# An Exploratory Study of ML Sketches and Visual Code Assistants 

**Title (ZH)**: 一项关于机器学习草图和可视代码助手的探索性研究 

**Authors**: Luís F. Gomes, Vincent J. Hellendoorn, Jonathan Aldrich, Rui Abreu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13386)  

**Abstract**: This paper explores the integration of Visual Code Assistants in Integrated Development Environments (IDEs). In Software Engineering, whiteboard sketching is often the initial step before coding, serving as a crucial collaboration tool for developers. Previous studies have investigated patterns in SE sketches and how they are used in practice, yet methods for directly using these sketches for code generation remain limited. The emergence of visually-equipped large language models presents an opportunity to bridge this gap, which is the focus of our research. In this paper, we built a first prototype of a Visual Code Assistant to get user feedback regarding in-IDE sketch-to-code tools. We conduct an experiment with 19 data scientists, most of whom regularly sketch as part of their job. We investigate developers' mental models by analyzing patterns commonly observed in their sketches when developing an ML workflow. Analysis indicates that diagrams were the preferred organizational component (52.6%), often accompanied by lists (42.1%) and numbered points (36.8%). Our tool converts their sketches into a Python notebook by querying an LLM. We use an LLM-as-judge setup to score the quality of the generated code, finding that even brief sketching can effectively generate useful code outlines. We also find a positive correlation between sketch time and the quality of the generated code. We conclude the study by conducting extensive interviews to assess the tool's usefulness, explore potential use cases, and understand developers' needs. As noted by participants, promising applications for these assistants include education, prototyping, and collaborative settings. Our findings signal promise for the next generation of Code Assistants to integrate visual information, both to improve code generation and to better leverage developers' existing sketching practices. 

**Abstract (ZH)**: 本文探讨了在集成开发环境（IDE）中集成视觉代码助手的可能性。在软件工程中，白板草图通常是在编码之前的第一步，是开发人员之间的重要协作工具。以往的研究已经探讨了软件工程草图中的模式及其实践应用，但对于如何直接利用这些草图进行代码生成的方法仍然有限。随着视觉上增强的大规模语言模型的出现，提供了一个弥合这一差距的机会，这也是我们研究的重点。在本文中，我们构建了一个视觉代码助手的初步原型，以获取用户对IDE中草图转代码工具的反馈。我们对19名数据科学家进行了实验，其中大多数人在工作中经常使用草图。我们通过分析他们在开发机器学习工作流时常用草图中的模式来探究开发人员的思维模型。分析表明，他们在草图中更偏好使用图表（52.6%），通常会附带列表（42.1%）和编号项目点（36.8%）。我们的工具通过查询大规模语言模型（LLM），将他们的草图转换为一个Python笔记本文件。我们采用一个大规模语言模型作为评判者（LLM-as-judge）的设置来评估生成代码的质量，发现即使是简短的草图也能有效地生成有用的代码大纲。我们还发现，草图时间与生成代码的质量之间存在正相关关系。在研究的最后，我们进行了广泛的访谈，以评估该工具的实用性、探索潜在的应用场景，并理解开发人员的需求。正如参与者所指出的，这些助手在教育、原型设计和协作设置中的应用前景广阔。我们的研究结果预示着下一代代码助手有望整合视觉信息，不仅能够提高代码生成的质量，还能更好地利用开发人员现有的绘图实践。 

---
# Voter Priming Campaigns: Strategies, Equilibria, and Algorithms 

**Title (ZH)**: 选民动员 campaigns：策略、均衡与算法 

**Authors**: Jonathan Shaki, Yonatan Aumann, Sarit Kraus  

**Link**: [PDF](https://arxiv.org/pdf/2412.13380)  

**Abstract**: Issue salience is a major determinant in voters' decisions. Candidates and political parties campaign to shift salience to their advantage - a process termed priming. We study the dynamics, strategies and equilibria of campaign spending for voter priming in multi-issue multi-party settings. We consider both parliamentary elections, where parties aim to maximize their share of votes, and various settings for presidential elections, where the winner takes all. For parliamentary elections, we show that pure equilibrium spending always exists and can be computed in time linear in the number of voters. For two parties and all settings, a spending equilibrium exists such that each party invests only in a single issue, and an equilibrium can be computed in time that is polynomial in the number of issues and linear in the number of voters. We also show that in most presidential settings no equilibrium exists. Additional properties of optimal campaign strategies are also studied. 

**Abstract (ZH)**: 选题显著性是选民决策中的一个重要决定因素。候选人和政治党派展开竞选活动以将选题显著性转向其有利的方向——这一过程称为“强化”。我们研究多议题多党派竞选支出的动态、策略及均衡。我们既考虑议会选举的情形，政党在此情形下旨在最大化其获得的选票比例，也考虑各种总统选举的情形，其中胜者通吃。对于议会选举，我们证明纯均衡支出总是存在的，并且可以在投票人数线性时间内计算出。在两党制和所有情况下，存在一个均衡使得每方只投资于一个议题，这种均衡可以在议题数量成多项式时间、投票人数线性时间内进行计算。我们也展示了在大多数总统选举情形下不存在均衡。此外，还研究了最优竞选策略的其他性质。 

---
# DateLogicQA: Benchmarking Temporal Biases in Large Language Models 

**Title (ZH)**: DateLogicQA：大规模语言模型中时间偏见的基准测试 

**Authors**: Gagan Bhatia, MingZe Tang, Cristina Mahanta, Madiha Kazi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13377)  

**Abstract**: This paper introduces DateLogicQA, a benchmark with 190 questions covering diverse date formats, temporal contexts, and reasoning types. We propose the Semantic Integrity Metric to assess tokenization quality and analyse two biases: Representation-Level Bias, affecting embeddings, and Logical-Level Bias, influencing reasoning outputs. Our findings provide a comprehensive evaluation of LLMs' capabilities and limitations in temporal reasoning, highlighting key challenges in handling temporal data accurately. The GitHub repository for our work is available at this https URL 

**Abstract (ZH)**: 本文介绍了一项名为DateLogicQA的新基准，该基准涵盖了190个问题，涉及多种日期格式、时间上下文以及不同类型的推理类型。我们提出了语义完整性度量标准，用于评估分词质量，并分析了两种偏差：表示层次偏差，影响嵌入表示；逻辑层次偏差，影响推理输出。我们的研究成果全面评估了LLM（大型语言模型）在时间推理方面的能力和局限性，并突出了准确处理时间数据的关键挑战。我们的工作代码仓库可在以下链接访问：[这里替换为具体的GitHub链接] 

---
# Targeted View-Invariant Adversarial Perturbations for 3D Object Recognition 

**Title (ZH)**: 面向视图不变的 adversarial 氛围扰动在 3D 对象识别中的应用 

**Authors**: Christian Green, Mehmet Ergezer, Abdurrahman Zeybey  

**Link**: [PDF](https://arxiv.org/pdf/2412.13376)  

**Abstract**: Adversarial attacks pose significant challenges in 3D object recognition, especially in scenarios involving multi-view analysis where objects can be observed from varying angles. This paper introduces View-Invariant Adversarial Perturbations (VIAP), a novel method for crafting robust adversarial examples that remain effective across multiple viewpoints. Unlike traditional methods, VIAP enables targeted attacks capable of manipulating recognition systems to classify objects as specific, pre-determined labels, all while using a single universal perturbation. Leveraging a dataset of 1,210 images across 121 diverse rendered 3D objects, we demonstrate the effectiveness of VIAP in both targeted and untargeted settings. Our untargeted perturbations successfully generate a singular adversarial noise robust to 3D transformations, while targeted attacks achieve exceptional results, with top-1 accuracies exceeding 95% across various epsilon values. These findings highlight VIAPs potential for real-world applications, such as testing the robustness of 3D recognition systems. The proposed method sets a new benchmark for view-invariant adversarial robustness, advancing the field of adversarial machine learning for 3D object recognition. 

**Abstract (ZH)**: 对抗攻击在三维物体识别中提出了重大挑战，尤其是在涉及多视角分析的场景中，物体可以从不同的角度进行观察。本文介绍了视角不变对抗扰动（VIAP，View-Invariant Adversarial Perturbations），这是一种新颖的方法，用于生成在多个视角下依然有效的鲁棒对抗样本。与传统方法不同，VIAP能够实现目标攻击，即能够操纵识别系统将物体分类为预设的具体标签，同时仅使用单一通用扰动。借助包含121种不同渲染三维物体的1,210张图像的数据集，我们展示了VIAP在目标攻击和非目标攻击场景下的有效性。我们的非目标攻击生成的单一对抗噪声对3D变换具有鲁棒性，而目标攻击则取得了卓越的结果，在各种ε值下达到95%以上的top-1准确性。这些发现突显了VIAP在实际应用中的潜力，例如测试三维识别系统的鲁棒性。提出的方法为视角不变对抗鲁棒性设立了新的基准，推动了三维物体识别中对抗机器学习领域的进展。 

---
# Multi-Agent Motion Planning For Differential Drive Robots Through Stationary State Search 

**Title (ZH)**: 通过静态状态搜索实现差速驱动机器人多agent运动规划 

**Authors**: Jingtian Yan, Jiaoyang Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.13359)  

**Abstract**: Multi-Agent Motion Planning (MAMP) finds various applications in fields such as traffic management, airport operations, and warehouse automation. In many of these environments, differential drive robots are commonly used. These robots have a kinodynamic model that allows only in-place rotation and movement along their current orientation, subject to speed and acceleration limits. However, existing Multi-Agent Path Finding (MAPF)-based methods often use simplified models for robot kinodynamics, which limits their practicality and realism. In this paper, we introduce a three-level framework called MASS to address these challenges. MASS combines MAPF-based methods with our proposed stationary state search planner to generate high-quality kinodynamically-feasible plans. We further extend MASS using an adaptive window mechanism to address the lifelong MAMP problem. Empirically, we tested our methods on the single-shot grid map domain and the lifelong warehouse domain. Our method shows up to 400% improvements in terms of throughput compared to existing methods. 

**Abstract (ZH)**: 多智能体运动规划（Multi-Agent Motion Planning, MAMP）在交通管理、机场运营和仓储自动化等领域中有着广泛的应用。在许多这类环境中，通常会使用差动驱动机器人。这些机器人的运动会受到其结构的限制，只能在其当前方向上进行原地旋转和移动，并且受到速度和加速度的限制。然而，现有的基于多智能体路径规划（Multi-Agent Path Finding, MAPF）的方法常常使用简化版的机器人性态动力学模型，这限制了它们的实用性和真实性。本文介绍了一种三层框架——MAS（Motion and State Search, MAPP）——来解决这些问题。MAS结合了基于MAPF的方法和我们提出的静态状态搜索规划器，以生成高质量的、满足性态动力学约束的规划方案。我们进一步通过一个自适应窗口机制将MAS扩展为应对终身多智能体运动规划（lifelong MAMP）问题。实验上，我们在单次网格地图域和终身仓储域中验证了我们的方法。我们的方法在吞吐量方面相较于现有方法最高提高了400%。 

---
# A Novel Machine Learning Classifier Based on Genetic Algorithms and Data Importance Reformatting 

**Title (ZH)**: 基于遗传算法和数据重要性重塑的新型机器学习分类器 

**Authors**: A. K. Alkhayyata, N. M. Hewahi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13350)  

**Abstract**: In this paper, a novel classification algorithm that is based on Data Importance (DI) reformatting and Genetic Algorithms (GA) named GADIC is proposed to overcome the issues related to the nature of data which may hinder the performance of the Machine Learning (ML) classifiers. GADIC comprises three phases which are data reformatting phase which depends on DI concept, training phase where GA is applied on the reformatted training dataset, and testing phase where the instances of the reformatted testing dataset are being averaged based on similar instances in the training dataset. GADIC is an approach that utilizes the exiting ML classifiers with involvement of data reformatting, using GA to tune the inputs, and averaging the similar instances to the unknown instance. The averaging of the instances becomes the unknown instance to be classified in the stage of testing. GADIC has been tested on five existing ML classifiers which are Support Vector Machine (SVM), K-Nearest Neighbour (KNN), Logistic Regression (LR), Decision Tree (DT), and Naïve Bayes (NB). All were evaluated using seven open-source UCI ML repository and Kaggle datasets which are Cleveland heart disease, Indian liver patient, Pima Indian diabetes, employee future prediction, telecom churn prediction, bank customer churn, and tech students. In terms of accuracy, the results showed that, with the exception of approximately 1% decrease in the accuracy of NB classifier in Cleveland heart disease dataset, GADIC significantly enhanced the performance of most ML classifiers using various datasets. In addition, KNN with GADIC showed the greatest performance gain when compared with other ML classifiers with GADIC followed by SVM while LR had the lowest improvement. The lowest average improvement that GADIC could achieve is 5.96%, whereas the maximum average improvement reached 16.79%. 

**Abstract (ZH)**: 本文提出了一种基于数据重要性（Data Importance, DI）重塑和遗传算法（Genetic Algorithms, GA）的新分类算法，命名为GADIC，以克服与数据性质相关的问题，这些问题可能会妨碍机器学习（ML）分类器的性能。GADIC包含三个阶段：数据重塑阶段，该阶段依赖于DI概念；训练阶段，在该阶段应用GA对重塑后的训练数据集进行训练；测试阶段，在该阶段，测试数据集的实例基于训练数据集中相似的实例进行平均。GADIC是一种利用现有ML分类器的方法，涉及数据重塑，使用GA调整输入，并通过平均相似实例来处理未知实例。在测试阶段，实例的平均结果将成为要分类的未知实例。GADIC已在五个现有的ML分类器上进行了测试，包括支持向量机（SVM）、K最近邻（KNN）、逻辑回归（LR）、决策树（DT）和朴素贝叶斯（NB）。所有这些分类器均使用七个开源UCI ML数据集和Kaggle数据集进行评估，这些数据集为克利夫兰心脏病、印度肝病患者、皮马印第安糖尿病、雇员未来预测、电信客户流失预测、银行客户流失和科技学生数据集。在准确率方面，结果显示，除了在克利夫兰心脏病数据集上约1%的NB分类器准确率下降外，GADIC显著提升了大多数ML分类器在各种数据集上的性能。此外，在与其他使用GADIC的ML分类器相比时，KNN显示出了最大的性能提升，SVM紧跟其后，而LR的改进程度最低。GADIC能够实现的最低平均改进幅度为5.96%，最高平均改进幅度达到16.79%。 

---
# Unveiling the Secret Recipe: A Guide For Supervised Fine-Tuning Small LLMs 

**Title (ZH)**: 揭开秘方的面纱：一种监督微调小型语言模型的指南 

**Authors**: Aldo Pareja, Nikhil Shivakumar Nayak, Hao Wang, Krishnateja Killamsetty, Shivchander Sudalairaj, Wenlong Zhao, Seungwook Han, Abhishek Bhandwaldar, Guangxuan Xu, Kai Xu, Ligong Han, Luke Inglis, Akash Srivastava  

**Link**: [PDF](https://arxiv.org/pdf/2412.13337)  

**Abstract**: The rise of large language models (LLMs) has created a significant disparity: industrial research labs with their computational resources, expert teams, and advanced infrastructures, can effectively fine-tune LLMs, while individual developers and small organizations face barriers due to limited resources. In this paper, we aim to bridge this gap by presenting a comprehensive study on supervised fine-tuning of LLMs using instruction-tuning datasets spanning diverse knowledge domains and skills. We focus on small-sized LLMs (3B to 7B parameters) for their cost-efficiency and accessibility. We explore various training configurations and strategies across four open-source pre-trained models. We provide detailed documentation of these configurations, revealing findings that challenge several common training practices, including hyperparameter recommendations from TULU and phased training recommended by Orca. Key insights from our work include: (i) larger batch sizes paired with lower learning rates lead to improved model performance on benchmarks such as MMLU, MTBench, and Open LLM Leaderboard; (ii) early-stage training dynamics, such as lower gradient norms and higher loss values, are strong indicators of better final model performance, enabling early termination of sub-optimal runs and significant computational savings; (iii) through a thorough exploration of hyperparameters like warmup steps and learning rate schedules, we provide guidance for practitioners and find that certain simplifications do not compromise performance; and (iv) we observed no significant difference in performance between phased and stacked training strategies, but stacked training is simpler and more sample efficient. With these findings holding robustly across datasets and models, we hope this study serves as a guide for practitioners fine-tuning small LLMs and promotes a more inclusive environment for LLM research. 

**Abstract (ZH)**: 大型语言模型（LLMs）的兴起创造了一个显著的差距：工业研究实验室凭借其计算资源、专家团队和高级基础设施，能够有效地调优LLMs，而个体开发者和小型组织因资源有限而面临障碍。本文旨在弥合这一差距，通过对横跨不同知识领域和技能的指令调优数据集进行监督调优研究，开展全面的调研。我们专注于小规模LLMs（3B到7B参数），因其成本效益和易于访问。我们探索了在四个开源预训练模型上使用的各种训练配置和策略。我们详细记录了这些配置，揭示了一些挑战常见训练实践的研究发现，包括TULU推荐的超参数和Orca推荐的分阶段训练。本文的关键洞察包括：（i）较大的批次大小配以较低的学习率在多模态（MMLU）、MTBench和开放LLM排行榜等基准测试中提高了模型性能；（ii）早期训练动态，如较低的梯度范数和较高的损失值，是更好的最终模型性能的强烈指标，这有助于提前终止不理想运行并节省大量计算资源；（iii）通过彻底探索诸如预热步数和学习率调度等超参数，我们为从业者提供了指导，并发现某些简化措施不会影响性能；（iv）我们观察到分阶段和堆叠训练策略在性能上没有显著差异，但堆叠训练更简单且更具样本效率。基于这些研究发现，在不同数据集和模型上的表现都十分稳健，我们希望这项研究能为调优小型LLM的从业者提供指南，并促进LLM研究的包容性环境。 

---
# Experience of Training a 1.7B-Parameter LLaMa Model From Scratch 

**Title (ZH)**: 从头训练一个17亿参数的LLaMa模型的体验 

**Authors**: Miles Q. Li, Benjamin C. M. Fung, Shih-Chia Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13335)  

**Abstract**: Pretraining large language models is a complex endeavor influenced by multiple factors, including model architecture, data quality, training continuity, and hardware constraints. In this paper, we share insights gained from the experience of training DMaS-LLaMa-Lite, a fully open source, 1.7-billion-parameter, LLaMa-based model, on approximately 20 billion tokens of carefully curated data. We chronicle the full training trajectory, documenting how evolving validation loss levels and downstream benchmarks reflect transitions from incoherent text to fluent, contextually grounded output. Beyond standard quantitative metrics, we highlight practical considerations such as the importance of restoring optimizer states when resuming from checkpoints, and the impact of hardware changes on training stability and throughput. While qualitative evaluation provides an intuitive understanding of model improvements, our analysis extends to various performance benchmarks, demonstrating how high-quality data and thoughtful scaling enable competitive results with significantly fewer training tokens. By detailing these experiences and offering training logs, checkpoints, and sample outputs, we aim to guide future researchers and practitioners in refining their pretraining strategies. The training script is available on Github at this https URL. The model checkpoints are available on Huggingface at this https URL. 

**Abstract (ZH)**: 预训练大规模语言模型是一个受多种因素影响的复杂过程，包括模型架构、数据质量、训练连续性和硬件约束。在本文中，我们分享了在DMaS-LLaMa-Lite模型上的预训练经验。DMaS-LLaMa-Lite是一个完全开源的、拥有17亿参数的基于LLaMA的模型，我们使用了大约200亿个精心筛选的数据标记进行训练。我们详细记录了整个训练过程，描述了验证损失水平和下游基准测试如何随着训练的进行从不连贯的文本转变为流畅且内容相关的输出。除了标准的定量指标外，我们还强调了一些实践考虑，如从检查点恢复优化器状态的重要性，以及硬件变化对训练稳定性和吞吐量的影响。虽然定性的评估能够直观地理解模型的进步，但我们的分析还扩展到各种性能基准，展示了高质量数据和精心的扩展策略如何在显著减少训练标记的条件下实现竞争性的结果。通过详细记录这些经验和提供训练脚本、检查点和样本输出，我们旨在指导未来的研究者和实践者优化其预训练策略。训练脚本可在Github上通过以下链接获得：[此https URL]。模型检查点可在Huggingface上通过以下链接获得：[此https URL]。 

---
# BadSAD: Clean-Label Backdoor Attacks against Deep Semi-Supervised Anomaly Detection 

**Title (ZH)**: BadSAD：针对深度半监督异常检测的清洁标签后门攻击 

**Authors**: He Cheng, Depeng Xu, Shuhan Yuan  

**Link**: [PDF](https://arxiv.org/pdf/2412.13324)  

**Abstract**: Image anomaly detection (IAD) is essential in applications such as industrial inspection, medical imaging, and security. Despite the progress achieved with deep learning models like Deep Semi-Supervised Anomaly Detection (DeepSAD), these models remain susceptible to backdoor attacks, presenting significant security challenges. In this paper, we introduce BadSAD, a novel backdoor attack framework specifically designed to target DeepSAD models. Our approach involves two key phases: trigger injection, where subtle triggers are embedded into normal images, and latent space manipulation, which positions and clusters the poisoned images near normal images to make the triggers appear benign. Extensive experiments on benchmark datasets validate the effectiveness of our attack strategy, highlighting the severe risks that backdoor attacks pose to deep learning-based anomaly detection systems. 

**Abstract (ZH)**: 图像异常检测（IAD）在工业检测、医疗成像和安全领域中至关重要。尽管使用深度学习模型（如Deep Semi-Supervised Anomaly Detection, DeepSAD）已经取得了进展，这些模型仍然容易受到后门攻击的影响，带来了重大的安全挑战。在本文中，我们介绍了BadSAD——一种专门针对DeepSAD模型设计的后门攻击框架。我们的方法包括两个关键阶段：触发注入和潜在空间操纵。在触发注入阶段，我们在正常图像中嵌入微妙的触发器；在潜在空间操纵阶段，将中毒图像重新定位并聚类到正常图像附近，以使触发器看起来无害。在基准数据集上的广泛实验验证了我们的攻击策略的有效性，突显了后门攻击对基于深度学习的异常检测系统的严重威胁。 

---
# FastVLM: Efficient Vision Encoding for Vision Language Models 

**Title (ZH)**: FastVLM：高效的视觉编码用于视觉语言模型 

**Authors**: Pavan Kumar Anasosalu Vasu, Fartash Faghri, Chun-Liang Li, Cem Koc, Nate True, Albert Antony, Gokul Santhanam, James Gabriel, Peter Grasch, Oncel Tuzel, Hadi Pouransari  

**Link**: [PDF](https://arxiv.org/pdf/2412.13303)  

**Abstract**: Scaling the input image resolution is essential for enhancing the performance of Vision Language Models (VLMs), particularly in text-rich image understanding tasks. However, popular visual encoders such as ViTs become inefficient at high resolutions due to the large number of tokens and high encoding latency caused by stacked self-attention layers. At different operational resolutions, the vision encoder of a VLM can be optimized along two axes: reducing encoding latency and minimizing the number of visual tokens passed to the LLM, thereby lowering overall latency. Based on a comprehensive efficiency analysis of the interplay between image resolution, vision latency, token count, and LLM size, we introduce FastVLM, a model that achieves an optimized trade-off between latency, model size and accuracy. FastVLM incorporates FastViTHD, a novel hybrid vision encoder designed to output fewer tokens and significantly reduce encoding time for high-resolution images. Unlike previous methods, FastVLM achieves the optimal balance between visual token count and image resolution solely by scaling the input image, eliminating the need for additional token pruning and simplifying the model design. In the LLaVA-1.5 setup, FastVLM achieves 3.2$\times$ improvement in time-to-first-token (TTFT) while maintaining similar performance on VLM benchmarks compared to prior works. Compared to LLaVa-OneVision at the highest resolution (1152$\times$1152), FastVLM achieves comparable performance on key benchmarks like SeedBench and MMMU, using the same 0.5B LLM, but with 85$\times$ faster TTFT and a vision encoder that is 3.4$\times$ smaller. 

**Abstract (ZH)**: 提升输入图像分辨率对于增强视觉语言模型（VLMs）的性能至关重要，尤其是在文本丰富的图像理解任务中。然而，流行的视觉编码器如Transformer Vision Transformers（ViTs）在高分辨率下变得低效，原因是在堆叠的自注意力层导致大量的标记和高编码延迟。在不同的操作分辨率下，VLM中的视觉编码器可以在两个方面进行优化：一是减少编码延迟，二是减小传递给LLM的视觉标记的数量，从而降低整体延迟。基于图像分辨率、视觉延迟、标记数量和LLM规模之间的全面效率分析，我们提出FastVLM模型，实现延迟、模型大小和准确性的优化平衡。FastVLM集成了FastViTHD，这是一种新型的混合视觉编码器，专门为高分辨率图像输出更少的标记并显著减少编码时间。与以往方法不同，FastVLM仅通过缩放输入图像来实现视觉标记数量和图像分辨率之间的最佳平衡，而不需要额外的标记剪枝，简化了模型设计。在LLaVA-1.5设置中，FastVLM在首次标记生成时间（TTFT）上实现了3.2倍的改进，同时在VLM基准测试中的性能与之前的工作相似。与最高分辨率（1152×1152）的LLaVa-OneVision相比，FastVLM在关键基准如SeedBench和MMMU上实现了相当的性能，但使用相同规模（0.5B）的LLM时，TTFT速度快85倍，视觉编码器体积小3.4倍。 

---
# In-context learning for medical image segmentation 

**Title (ZH)**: 医学图像分割的上下文学习方法 

**Authors**: Eichi Takaya, Shinnosuke Yamamoto  

**Link**: [PDF](https://arxiv.org/pdf/2412.13299)  

**Abstract**: Annotation of medical images, such as MRI and CT scans, is crucial for evaluating treatment efficacy and planning radiotherapy. However, the extensive workload of medical professionals limits their ability to annotate large image datasets, posing a bottleneck for AI applications in medical imaging. To address this, we propose In-context Cascade Segmentation (ICS), a novel method that minimizes annotation requirements while achieving high segmentation accuracy for sequential medical images. ICS builds on the UniverSeg framework, which performs few-shot segmentation using support images without additional training. By iteratively adding the inference results of each slice to the support set, ICS propagates information forward and backward through the sequence, ensuring inter-slice consistency. We evaluate the proposed method on the HVSMR dataset, which includes segmentation tasks for eight cardiac regions. Experimental results demonstrate that ICS significantly improves segmentation performance in complex anatomical regions, particularly in maintaining boundary consistency across slices, compared to baseline methods. The study also highlights the impact of the number and position of initial support slices on segmentation accuracy. ICS offers a promising solution for reducing annotation burdens while delivering robust segmentation results, paving the way for its broader adoption in clinical and research applications. 

**Abstract (ZH)**: 医学图像的注释，如MRI和CT扫描，对于评估治疗疗效和规划放射疗法至关重要。然而，医学专业人士的庞大工作量限制了他们对大规模图像数据集进行注释的能力，成为人工智能在医学成像中应用的瓶颈。为了解决这一问题，我们提出了一种新颖的方法——上下文级级联分割（ICS），该方法在减少注释需求的同时，能够实现对顺序医学图像的高分割精度。ICS基于UniverSeg框架，该框架利用支持图像进行少量训练分割，无需额外训练。通过迭代将每个切片的推断结果添加到支持集中，ICS在序列中向前向后传播信息，确保切片间的一致性。我们使用包含八个心脏区域分割任务的HVSMR数据集对所提出的方法进行了评估。实验结果表明，与基线方法相比，ICS显著提高了复杂解剖区域的分割性能，特别是在保持切片间边界一致性方面。研究还强调了初始支持切片的数量和位置对分割精度的影响。ICS为减轻注释负担并提供稳健的分割结果提供了有希望的解决方案，为其在临床和研究中的广泛应用铺平了道路。 

---
# Posterior Mean Matching: Generative Modeling through Online Bayesian Inference 

**Title (ZH)**: 后验均值匹配：通过在线贝叶斯推断的生成建模 

**Authors**: Sebastian Salazar, Michal Kucer, Yixin Wang, Emily Casleton, David Blei  

**Link**: [PDF](https://arxiv.org/pdf/2412.13286)  

**Abstract**: This paper introduces posterior mean matching (PMM), a new method for generative modeling that is grounded in Bayesian inference. PMM uses conjugate pairs of distributions to model complex data of various modalities like images and text, offering a flexible alternative to existing methods like diffusion models. PMM models iteratively refine noisy approximations of the target distribution using updates from online Bayesian inference. PMM is flexible because its mechanics are based on general Bayesian models. We demonstrate this flexibility by developing specialized examples: a generative PMM model of real-valued data using the Normal-Normal model, a generative PMM model of count data using a Gamma-Poisson model, and a generative PMM model of discrete data using a Dirichlet-Categorical model. For the Normal-Normal PMM model, we establish a direct connection to diffusion models by showing that its continuous-time formulation converges to a stochastic differential equation (SDE). Additionally, for the Gamma-Poisson PMM, we derive a novel SDE driven by a Cox process, which is a significant departure from traditional Brownian motion-based generative models. PMMs achieve performance that is competitive with generative models for language modeling and image generation. 

**Abstract (ZH)**: 本文介绍了后验均值匹配（Posterior Mean Matching, PMM），这是一种基于贝叶斯推断的生成模型新方法。PMM 使用共轭分布对来建模各种模态（如图像和文本）的复杂数据，为现有的方法（如扩散模型）提供了灵活的选择。PMM 模型通过在线贝叶斯推断的更新迭代细化目标分布的噪声近似。由于其机理基于通用的贝叶斯模型，PMM 具有灵活性。通过开发特定示例，我们展示了这种灵活性：使用正态-正态模型的实值数据生成的 PMM 模型，使用伽马-泊松模型的计数数据生成的 PMM 模型，以及使用狄利克雷-卡特尔模型的离散数据生成的 PMM 模型。对于正态-正态 PMM 模型，我们通过证明其连续时间形式收敛到随机微分方程（SDE）建立了与扩散模型的直接联系。此外，对于伽马-泊松 PMM，我们推导出一种新型由柯克过程驱动的 SDE，这与传统的基于布朗运动的生成模型产生了显著的差异。PMM 在语言建模和图像生成任务中的性能与现有生成模型相当。 

---
# Enhancing Internet of Things Security throughSelf-Supervised Graph Neural Networks 

**Title (ZH)**: 通过自我监督图神经网络提升物联网安全 

**Authors**: Safa Ben Atitallah, Maha Driss, Wadii Boulila, Anis Koubaa  

**Link**: [PDF](https://arxiv.org/pdf/2412.13240)  

**Abstract**: With the rapid rise of the Internet of Things (IoT), ensuring the security of IoT devices has become essential. One of the primary challenges in this field is that new types of attacks often have significantly fewer samples than more common attacks, leading to unbalanced datasets. Existing research on detecting intrusions in these unbalanced labeled datasets primarily employs Convolutional Neural Networks (CNNs) or conventional Machine Learning (ML) models, which result in incomplete detection, especially for new attacks. To handle these challenges, we suggest a new approach to IoT intrusion detection using Self-Supervised Learning (SSL) with a Markov Graph Convolutional Network (MarkovGCN). Graph learning excels at modeling complex relationships within data, while SSL mitigates the issue of limited labeled data for emerging attacks. Our approach leverages the inherent structure of IoT networks to pre-train a GCN, which is then fine-tuned for the intrusion detection task. The integration of Markov chains in GCN uncovers network structures and enriches node and edge features with contextual information. Experimental results demonstrate that our approach significantly improves detection accuracy and robustness compared to conventional supervised learning methods. Using the EdgeIIoT-set dataset, we attained an accuracy of 98.68\%, a precision of 98.18%, a recall of 98.35%, and an F1-Score of 98.40%. 

**Abstract (ZH)**: 随着物联网（IoT）的迅速发展，确保IoT设备的安全性已经成为必要。该领域的主要挑战之一是，针对新兴攻击的新类型的攻击样本通常远少于常见攻击，导致数据集不平衡。现有的针对不平衡标注数据集检测入侵的研究主要依赖卷积神经网络（CNN）或传统的机器学习（ML）模型，这些方法在检测新攻击时往往不完整。为了应对这些挑战，我们提出了一种新的基于自我监督学习（SSL）和马尔可夫图卷积网络（MarkovGCN）的IoT入侵检测方法。图学习擅长建模数据中的复杂关系，而SSL可以缓解新兴攻击中标签数据有限的问题。我们的方法利用物联网网络内部的固有结构对GCN进行预训练，然后对入侵检测任务进行微调。将马尔可夫链集成到GCN中可以揭示网络结构并使用上下文信息丰富节点和边的特征。实验结果表明，与传统的监督学习方法相比，我们的方法在检测准确性和鲁棒性方面显著提高。使用EdgeIIoT-set数据集，我们达到了98.68%的准确率、98.18%的精确率、98.35%的召回率和98.40%的F1分数。 

---
# COSEE: Consistency-Oriented Signal-Based Early Exiting via Calibrated Sample Weighting Mechanism 

**Title (ZH)**: COSEE: 一致性导向的信号基早期退出机制通过校准样本权重机制 

**Authors**: Jianing He, Qi Zhang, Hongyun Zhang, Xuanjing Huang, Usman Naseem, Duoqian Miao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13236)  

**Abstract**: Early exiting is an effective paradigm for improving the inference efficiency of pre-trained language models (PLMs) by dynamically adjusting the number of executed layers for each sample. However, in most existing works, easy and hard samples are treated equally by each classifier during training, which neglects the test-time early exiting behavior, leading to inconsistency between training and testing. Although some methods have tackled this issue under a fixed speed-up ratio, the challenge of flexibly adjusting the speed-up ratio while maintaining consistency between training and testing is still under-explored. To bridge the gap, we propose a novel Consistency-Oriented Signal-based Early Exiting (COSEE) framework, which leverages a calibrated sample weighting mechanism to enable each classifier to emphasize the samples that are more likely to exit at that classifier under various acceleration scenarios. Extensive experiments on the GLUE benchmark demonstrate the effectiveness of our COSEE across multiple exiting signals and backbones, yielding a better trade-off between performance and efficiency. 

**Abstract (ZH)**: 将以下论文内容或标题翻译成中文，符合学术规范：

早期退出是一种通过动态调整每个样本执行的层数来提高预训练语言模型（PLMs）推理效率的有效范式。然而，在大多数现有研究中，每个分类器在训练过程中对简单样本和困难样本处理得同等重要，这忽视了测试中的早期退出行为，导致训练和测试之间的不一致性。尽管一些方法在固定加速比的情况下解决了这一问题，但在保持训练和测试之间的一致性的同时灵活调整加速比的挑战仍然尚未被充分探讨。为了弥合这一差距，我们提出了一种新颖的面向一致性的基于信号的早期退出（COSEE）框架，该框架利用校准后的样本权重机制，使每个分类器能够在各种加速场景下对更有可能在其该分类器处退出的样本有所侧重。在GLUE基准测试上的广泛实验表明，COSEE在多种退出信号和骨干网络下均表现出有效性，提供了性能和效率之间的更好权衡。 

---
# C2F-TP: A Coarse-to-Fine Denoising Framework for Uncertainty-Aware Trajectory Prediction 

**Title (ZH)**: C2F-TP：一种考虑不确定性的时间轨迹预测细粒度去噪框架 

**Authors**: Zichen Wang, Hao Miao, Senzhang Wang, Renzhi Wang, Jianxin Wang, Jian Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13231)  

**Abstract**: Accurately predicting the trajectory of vehicles is critically important for ensuring safety and reliability in autonomous driving. Although considerable research efforts have been made recently, the inherent trajectory uncertainty caused by various factors including the dynamic driving intends and the diverse driving scenarios still poses significant challenges to accurate trajectory prediction. To address this issue, we propose C2F-TP, a coarse-to-fine denoising framework for uncertainty-aware vehicle trajectory prediction. C2F-TP features an innovative two-stage coarse-to-fine prediction process. Specifically, in the spatial-temporal interaction stage, we propose a spatial-temporal interaction module to capture the inter-vehicle interactions and learn a multimodal trajectory distribution, from which a certain number of noisy trajectories are sampled. Next, in the trajectory refinement stage, we design a conditional denoising model to reduce the uncertainty of the sampled trajectories through a step-wise denoising operation. Extensive experiments are conducted on two real datasets NGSIM and highD that are widely adopted in trajectory prediction. The result demonstrates the effectiveness of our proposal. 

**Abstract (ZH)**: 准确预测车辆轨迹对于确保自动驾驶的安全性和可靠性至关重要。尽管近年来进行了大量的研究工作，但由于各种因素（包括动态驾驶意图和多样的驾驶场景）导致的固有轨迹不确定性仍然对准确轨迹预测构成了重大挑战。为解决这一问题，我们提出了一种细腻有序降噪框架C2F-TP，以实现具有不确定性意识的车辆轨迹预测。C2F-TP特点在于其创新的两阶段粗细预测过程。具体而言，在空时交互阶段，我们提出了一种空时交互模块，用于捕捉车辆之间的相互作用并学习多模态轨迹分布，在此过程中从中抽取一定数量的噪声轨迹。随后，在轨迹细化阶段，我们设计了一种条件降噪模型，通过逐步降噪操作来减少抽取轨迹的不确定性。我们在NGSIM和highD这两种在轨迹预测中广泛采用的真实数据集上进行了大量实验，结果证明了我们方法的有效性。 

---
# Training Verification-Friendly Neural Networks via Neuron Behavior Consistency 

**Title (ZH)**: 通过神经元行为一致性训练验证友好的神经网络 

**Authors**: Zongxin Liu, Zhe Zhao, Fu Song, Jun Sun, Pengfei Yang, Xiaowei Huang, Lijun Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13229)  

**Abstract**: Formal verification provides critical security assurances for neural networks, yet its practical application suffers from the long verification time. This work introduces a novel method for training verification-friendly neural networks, which are robust, easy to verify, and relatively accurate. Our method integrates neuron behavior consistency into the training process, making neuron activation states consistent across different inputs in a local neighborhood, reducing the number of unstable neurons and tightening the bounds of neurons thereby enhancing neural network verifiability. We evaluated our method using the MNIST, Fashion-MNIST, and CIFAR-10 datasets across various network architectures. The results of the experiment demonstrate that networks trained using our method are verification-friendly across different radii and different model architectures, whereas other tools fail to maintain verifiability as the radius increases. We also show that our method can be combined with existing methods to further improve the verifiability of networks. 

**Abstract (ZH)**: 形式化验证为神经网络提供了关键的安全保证，但其实用应用受到验证时间过长的困扰。本文介绍了一种新的方法，用于训练具有良好验证性的神经网络，这些网络不仅鲁棒性强、易于验证，而且相对准确。我们的方法将神经元行为的一致性纳入训练过程中，使得在局部邻域内的不同输入下神经元激活状态保持一致，从而减少了不稳定的神经元数量并收紧了神经元的边界，增强神经网络的可验证性。我们使用MNIST、Fashion-MNIST和CIFAR-10数据集以及各种网络架构对我们的方法进行了评估。实验结果表明，使用我们方法训练的网络在不同的半径和不同的模型架构下都具有良好的验证性，而其他工具则随着半径的增加无法保持这种验证性。我们还展示了我们的方法可以与其他方法结合使用，进一步提高网络的验证性。 

---
# TSEML: A task-specific embedding-based method for few-shot classification of cancer molecular subtypes 

**Title (ZH)**: TSEML：一种用于癌症分子亚型few-shot分类的任务特定嵌入方法 

**Authors**: Ran Sua, Rui Shi, Hui Cui, Ping Xuan, Chengyan Fang, Xikang Feng, Qiangguo Jin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13228)  

**Abstract**: Molecular subtyping of cancer is recognized as a critical and challenging upstream task for personalized therapy. Existing deep learning methods have achieved significant performance in this domain when abundant data samples are available. However, the acquisition of densely labeled samples for cancer molecular subtypes remains a significant challenge for conventional data-intensive deep learning approaches. In this work, we focus on the few-shot molecular subtype prediction problem in heterogeneous and small cancer datasets, aiming to enhance precise diagnosis and personalized treatment. We first construct a new few-shot dataset for cancer molecular subtype classification and auxiliary cancer classification, named TCGA Few-Shot, from existing publicly available datasets. To effectively leverage the relevant knowledge from both tasks, we introduce a task-specific embedding-based meta-learning framework (TSEML). TSEML leverages the synergistic strengths of a model-agnostic meta-learning (MAML) approach and a prototypical network (ProtoNet) to capture diverse and fine-grained features. Comparative experiments conducted on the TCGA Few-Shot dataset demonstrate that our TSEML framework achieves superior performance in addressing the problem of few-shot molecular subtype classification. 

**Abstract (ZH)**: 癌症的分子亚型分类被认为是个性化治疗中一个关键而具有挑战性的上游任务。现有的深度学习方法在数据量充足的情况下已经在这一领域取得了显著的性能。然而，获得用于癌症分子亚型的密集标注样本仍然是传统数据密集型深度学习方法的一大挑战。在本工作中，我们聚焦于异质性和样本量较小的癌症数据集中的少样本分子亚型预测问题，旨在提升精确诊断和个性化治疗。我们首先从现有的公开数据集中构建了一个新的少样本数据集，用于癌症分子亚型分类和辅助癌症分类，命名为TCGA少样本数据集。为了有效利用两个任务的相关知识，我们引入了一种任务特定嵌入为基础的元学习框架（TSEML）。TSEML利用了模型无关元学习（MAML）方法与原型网络（ProtoNet）的协同优势，以捕获多样化的精细特征。在TCGA少样本数据集上的对比实验表明，我们的TSEML框架在少样本分子亚型分类问题上取得了优异的性能。 

---
# Physics-model-guided Worst-case Sampling for Safe Reinforcement Learning 

**Title (ZH)**: 遵循物理模型的最坏情况采样方法以实现安全的强化学习 

**Authors**: Hongpeng Cao, Yanbing Mao, Lui Sha, Marco Caccamo  

**Link**: [PDF](https://arxiv.org/pdf/2412.13224)  

**Abstract**: Real-world accidents in learning-enabled CPS frequently occur in challenging corner cases. During the training of deep reinforcement learning (DRL) policy, the standard setup for training conditions is either fixed at a single initial condition or uniformly sampled from the admissible state space. This setup often overlooks the challenging but safety-critical corner cases. To bridge this gap, this paper proposes a physics-model-guided worst-case sampling strategy for training safe policies that can handle safety-critical cases toward guaranteed safety. Furthermore, we integrate the proposed worst-case sampling strategy into the physics-regulated deep reinforcement learning (Phy-DRL) framework to build a more data-efficient and safe learning algorithm for safety-critical CPS. We validate the proposed training strategy with Phy-DRL through extensive experiments on a simulated cart-pole system, a 2D quadrotor, a simulated and a real quadruped robot, showing remarkably improved sampling efficiency to learn more robust safe policies. 

**Abstract (ZH)**: 在基于学习的复杂物理系统（CPS）中，实际事故经常发生在具有挑战性的corner case中。在深度强化学习（DRL）策略训练过程中，标准的训练条件设置通常是固定在单一初始条件下，或是均匀地从可行状态空间中抽取样本。这种设置往往忽略了那些具有挑战性但至关重要的corner case。为了弥合这一差距，本文提出了一种基于物理模型引导的最坏情况采样策略，以训练能够处理关键安全性情况的安全策略，从而确保安全性。此外，我们将提出的最坏情况采样策略整合到物理调控深度强化学习（Phy-DRL）框架中，构建了一个更高效且安全的学习算法，适用于关键安全的CPS。我们通过在模拟杆车系统、2维旋翼机以及模拟和真实四足机器人上的广泛实验，验证了通过Phy-DRL提出的训练策略，展示了显著提高的采样效率，能够学习到更加稳健的安全策略。 

---
# Generative modeling of protein ensembles guided by crystallographic electron densities 

**Title (ZH)**: 基于晶体学电子密度指导的蛋白质复合体生成建模 

**Authors**: Sai Advaith Maddipatla, Nadav Bojan Sellam, Sanketh Vedula, Ailie Marx, Alex Bronstein  

**Link**: [PDF](https://arxiv.org/pdf/2412.13223)  

**Abstract**: Proteins are dynamic, adopting ensembles of conformations. The nature of this conformational heterogenity is imprinted in the raw electron density measurements obtained from X-ray crystallography experiments. Fitting an ensemble of protein structures to these measurements is a challenging, ill-posed inverse problem. We propose a non-i.i.d. ensemble guidance approach to solve this problem using existing protein structure generative models and demonstrate that it accurately recovers complicated multi-modal alternate protein backbone conformations observed in certain single crystal measurements. 

**Abstract (ZH)**: 蛋白质是动态的，它们会采用一系列构象。X射线晶体学实验中获得的原始电子密度测量值中蕴含了这种构象异质性的本质。将一组蛋白质结构拟合到这些测量值上是一个具有挑战性的、病态的逆问题。我们提出了一种非独立同分布的 ensemble 指导方法，利用现有的蛋白质结构生成模型来解决这一问题，并证明该方法能够准确恢复某些单晶测量中观察到的复杂的多模态的替代蛋白质主链构象。 

---
# An introduction to reservoir computing 

**Title (ZH)**: 《关于水库计算的介绍》 

**Authors**: Michael te Vrugt  

**Link**: [PDF](https://arxiv.org/pdf/2412.13212)  

**Abstract**: There is a growing interest in the development of artificial neural networks that are implemented in a physical system. A major challenge in this context is that these networks are difficult to train since training here would require a change of physical parameters rather than simply of coefficients in a computer program. For this reason, reservoir computing, where one employs high-dimensional recurrent networks and trains only the final layer, is widely used in this context. In this chapter, I introduce the basic concepts of reservoir computing. Moreover, I present some important physical implementations coming from electronics, photonics, spintronics, mechanics, and biology. Finally, I provide a brief discussion of quantum reservoir computing. 

**Abstract (ZH)**: 随着物理系统中人工神经网络的发展，这种兴趣日益增长。在这种背景下，一个主要的挑战在于这些网络难以训练，因为训练不仅需要改变物理参数，还需要调整计算机程序中的系数。因此，在这种情况下，通常会采用循环神经网络 reservoir 计算，这种方法只需要训练最终层。本章中，我将介绍 reservoir 计算的基本概念，并呈现来自电子学、光子学、自旋电子学、力学和生物学的一些重要物理实现。最后，我将简要讨论量子 reservoir 计算。 

---
# ManiSkill-HAB: A Benchmark for Low-Level Manipulation in Home Rearrangement Tasks 

**Title (ZH)**: ManiSkill-HAB：家庭重新布置任务中低级别 manipulation 的基准测试 

**Authors**: Arth Shukla, Stone Tao, Hao Su  

**Link**: [PDF](https://arxiv.org/pdf/2412.13211)  

**Abstract**: High-quality benchmarks are the foundation for embodied AI research, enabling significant advancements in long-horizon navigation, manipulation and rearrangement tasks. However, as frontier tasks in robotics get more advanced, they require faster simulation speed, more intricate test environments, and larger demonstration datasets. To this end, we present MS-HAB, a holistic benchmark for low-level manipulation and in-home object rearrangement. First, we provide a GPU-accelerated implementation of the Home Assistant Benchmark (HAB). We support realistic low-level control and achieve over 3x the speed of previous magical grasp implementations at similar GPU memory usage. Second, we train extensive reinforcement learning (RL) and imitation learning (IL) baselines for future work to compare against. Finally, we develop a rule-based trajectory filtering system to sample specific demonstrations from our RL policies which match predefined criteria for robot behavior and safety. Combining demonstration filtering with our fast environments enables efficient, controlled data generation at scale. 

**Abstract (ZH)**: 高质量基准是实现自主人工智能研究的基础，能够显著推动长期导航、操作和物品重排等任务的发展。然而，随着机器人领域前沿任务的不断进步，它们需要更快的仿真速度、更复杂的测试环境以及更大的演示数据集。为此，我们提出了MS-HAB，这是一个全面的基准，主要用于低级操作和家庭环境中的物品重排。首先，我们提供了一个基于GPU加速的Home Assistant Benchmark（HAB）实现。我们支持现实世界的低级控制，并在相似的GPU内存使用情况下，实现比以往魔法抓取实现快3倍以上的速度。其次，我们训练了广泛的强化学习（RL）和模仿学习（IL）基准模型，以便未来的工作能够进行对比。最后，我们开发了一套基于规则的轨迹过滤系统，从我们的RL策略中选取特定的演示，使其符合预定义的机器人行为和安全准则。结合演示过滤与我们快速的环境，可以实现大规模的高效、可控的数据生成。 

---