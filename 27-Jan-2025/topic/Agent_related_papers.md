# Zep: A Temporal Knowledge Graph Architecture for Agent Memory 

**Title (ZH)**: ZEP：一种用于智能体记忆的时间知识图架构 

**Authors**: Preston Rasmussen, Pavlo Paliychuk, Travis Beauvais, Jack Ryan, Daniel Chalef  

**Link**: [PDF](https://arxiv.org/pdf/2501.13956)  

**Abstract**: We introduce Zep, a novel memory layer service for AI agents that outperforms the current state-of-the-art system, MemGPT, in the Deep Memory Retrieval (DMR) benchmark. Additionally, Zep excels in more comprehensive and challenging evaluations than DMR that better reflect real-world enterprise use cases. While existing retrieval-augmented generation (RAG) frameworks for large language model (LLM)-based agents are limited to static document retrieval, enterprise applications demand dynamic knowledge integration from diverse sources including ongoing conversations and business data. Zep addresses this fundamental limitation through its core component Graphiti -- a temporally-aware knowledge graph engine that dynamically synthesizes both unstructured conversational data and structured business data while maintaining historical relationships. In the DMR benchmark, which the MemGPT team established as their primary evaluation metric, Zep demonstrates superior performance (94.8% vs 93.4%). Beyond DMR, Zep's capabilities are further validated through the more challenging LongMemEval benchmark, which better reflects enterprise use cases through complex temporal reasoning tasks. In this evaluation, Zep achieves substantial results with accuracy improvements of up to 18.5% while simultaneously reducing response latency by 90% compared to baseline implementations. These results are particularly pronounced in enterprise-critical tasks such as cross-session information synthesis and long-term context maintenance, demonstrating Zep's effectiveness for deployment in real-world applications. 

**Abstract (ZH)**: 我们介绍了Zep，这是一种新型的内存层服务，与当前最先进的系统MemGPT在深度记忆检索（DMR）基准测试中表现更优。此外，Zep在比DMR更全面和更具挑战性的评估中表现出色，这些评估更能反映实际企业应用场景。现有的基于大型语言模型（LLM）的抽取增强生成（RAG）框架仅限于静态文档检索，而企业应用需要从各种动态知识源中进行动态集成，包括正在进行的对话和业务数据。Zep通过其核心组件Graphiti——一个能感知时间的知识图谱引擎来解决这一根本性限制。Graphiti能动态地合成未结构化的对话数据和结构化的业务数据，同时保持历史关系。在MemGPT团队建立为主要评估指标的DMR基准测试中，Zep展示了卓越的表现（94.8% vs 93.4%）。Zep的能力还在更具有挑战性的LongMemEval基准测试中得到了验证，该测试通过复杂的时序推理任务更好地反映了企业应用场景。在这种评估中，Zep的准确率提高了高达18.5%，同时将响应延迟降低了90%。这些结果在诸如会话间信息合成和长期上下文维护等关键企业任务中尤为明显，表明Zep在实际应用中的部署效果。 

---
# DRESSing Up LLM: Efficient Stylized Question-Answering via Style Subspace Editing 

**Title (ZH)**: 穿着风格：通过风格子空间编辑实现高效个性化问答 

**Authors**: Xinyu Ma, Yifeng Xu, Yang Lin, Tianlong Wang, Xu Chu, Xin Gao, Junfeng Zhao, Yasha Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.14371)  

**Abstract**: We introduce DRESS, a novel approach for generating stylized large language model (LLM) responses through representation editing. Existing methods like prompting and fine-tuning are either insufficient for complex style adaptation or computationally expensive, particularly in tasks like NPC creation or character role-playing. Our approach leverages the over-parameterized nature of LLMs to disentangle a style-relevant subspace within the model's representation space to conduct representation editing, ensuring a minimal impact on the original semantics. By applying adaptive editing strengths, we dynamically adjust the steering vectors in the style subspace to maintain both stylistic fidelity and semantic integrity. We develop two stylized QA benchmark datasets to validate the effectiveness of DRESS, and the results demonstrate significant improvements compared to baseline methods such as prompting and ITI. In short, DRESS is a lightweight, train-free solution for enhancing LLMs with flexible and effective style control, making it particularly useful for developing stylized conversational agents. Codes and benchmark datasets are available at this https URL. 

**Abstract (ZH)**: 我们引入了DRESS，这是一种通过表示编辑生成风格化大型语言模型（LLM）响应的新颖方法。现有的方法，如提示和微调，在复杂风格适应方面要么不够充分，要么在计算成本上非常昂贵，特别是在创建NPC或角色扮演等任务中。我们的方法利用了LLM的过度参数化特性，在模型的表示空间中分离出一个与风格相关的子空间，以进行表示编辑，从而确保对原始语义的最小影响。通过应用自适应编辑强度，我们可以动态调整风格子空间中的导向向量，以保持风格的真实性和语义的一致性。我们构建了两个风格化的问答基准数据集来验证DRESS的有效性，结果表明其与提示和交互式文本智能（ITI）等基线方法相比取得了显著改进。简而言之，DRESS是一种轻量级、无需训练的解决方案，用于通过灵活有效的样式控制增强LLM，使它特别适用于开发风格化的对话代理。相关代码和基准数据集可在以下链接获取：this https URL。 

---
# Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game 

**Title (ZH)**: 多代理KTO：增强大型语言模型在语言博弈中的战略互动 

**Authors**: Rong Ye, Yongxin Zhang, Yikai Zhang, Haoyu Kuang, Zhongyu Wei, Peng Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.14225)  

**Abstract**: Achieving Artificial General Intelligence (AGI) requires AI agents that can not only make stratigic decisions but also engage in flexible and meaningful communication. Inspired by Wittgenstein's language game theory in Philosophical Investigations, we propose that language agents can learn through in-context interaction rather than traditional multi-stage frameworks that separate decision-making from language expression. Using Werewolf, a social deduction game that tests language understanding, strategic interaction, and adaptability, we develop the Multi-agent Kahneman & Tversky's Optimization (MaKTO). MaKTO engages diverse models in extensive gameplay to generate unpaired desirable and unacceptable responses, then employs KTO to refine the model's decision-making process. In 9-player Werewolf games, MaKTO achieves a 61% average win rate across various models, outperforming GPT-4o and two-stage RL agents by relative improvements of 23.0% and 10.9%, respectively. Notably, MaKTO also demonstrates human-like performance, winning 60% against expert players and showing only 49% detectability in Turing-style blind tests. These results showcase MaKTO's superior decision-making, strategic adaptation, and natural language generation in complex social deduction games. 

**Abstract (ZH)**: 实现通用人工智能（AGI）需要能够不仅做出战略决策，还能进行灵活和有意义沟通的AI代理。受《哲学研究》中维特根斯坦语言游戏理论的启发，我们提出，语言代理可以通过上下文中的互动来学习，而不是通过将决策过程与语言表达分开的传统多阶段框架。使用狼人杀这一社会推理游戏来测试语言理解、策略互动和适应性，我们开发了多代理 Kahneman & Tversky's 最优化（MaKTO）。MaKTO 让多种模型参与广泛的棋盘游戏，生成令人满意的和不令人满意的响应，然后利用 KTO 优化模型的决策过程。在9人版狼人杀游戏中，MaKTO 在各种模型中实现了61%的平均胜率，分别优于GPT-4o和两阶段的强化学习代理23.0%和10.9%。值得注意的是，MaKTO 还展示了类似人类的表现，以60%的胜率击败了专家玩家，并在图灵式盲测中仅显示出49%的可辨识性。这些结果展示了MaKTO在复杂社会推理游戏中卓越的决策能力、战略适应能力和自然语言生成能力。 

---
# Communicating Activations Between Language Model Agents 

**Title (ZH)**: 语言模型代理之间的激活传播 

**Authors**: Vignav Ramesh, Kenneth Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.14082)  

**Abstract**: Communication between multiple language model (LM) agents has been shown to scale up the reasoning ability of LMs. While natural language has been the dominant medium for inter-LM communication, it is not obvious this should be the standard: not only does natural language communication incur high inference costs that scale quickly with the number of both agents and messages, but also the decoding process abstracts away too much rich information that could be otherwise accessed from the internal activations. In this work, we propose a simple technique whereby LMs communicate via activations; concretely, we pause an LM $\textit{B}$'s computation at an intermediate layer, combine its current activation with another LM $\textit{A}$'s intermediate activation via some function $\textit{f}$, then pass $\textit{f}$'s output into the next layer of $\textit{B}$ and continue the forward pass till decoding is complete. This approach scales up LMs on new tasks with zero additional parameters and data, and saves a substantial amount of compute over natural language communication. We test our method with various functional forms $\textit{f}$ on two experimental setups--multi-player coordination games and reasoning benchmarks--and find that it achieves up to $27.0\%$ improvement over natural language communication across datasets with $<$$1/4$ the compute, illustrating the superiority and robustness of activations as an alternative "language" for communication between LMs. 

**Abstract (ZH)**: 多语言模型（LM）代理之间的通信已被证明能够提高语言模型的推理能力。虽然自然语言一直是跨语言模型通信的主要媒介，但这种标准未必是必须的：自然语言通信不仅伴随着高推理成本，这种成本随着代理和消息的数量迅速增加，而且解码过程会丢失过多原本可以从内部激活中获取的丰富信息。本文中，我们提出了一种简单的方法，通过激活进行通信。具体而言，我们在语言模型 B 的一个中间层暂停其计算，将当前激活与另一个语言模型 A 的中间激活通过某种函数 f 结合，然后将 f 的输出传递给语言模型 B 的下一层，并继续前向传播直到完成解码。这种方法可以在不增加任何额外参数和数据的情况下，提高语言模型在新任务上的表现，并且通过减少计算量，相较于自然语言通信具有显著优势。我们通过不同的函数形式 f 在两种实验设置——多方协调游戏和推理基准测试中测试了该方法，并在较低计算量（少于四分之一）的情况下实现了高达 27.0% 的性能提升，这表明激活作为语言模型之间通信的另一种“语言”的优越性和鲁棒性。 

---
# Can OpenAI o1 Reason Well in Ophthalmology? A 6,990-Question Head-to-Head Evaluation Study 

**Title (ZH)**: OpenAI在眼科领域推理能力如何？一项针对6,990个问题的头对头评估研究 

**Authors**: Sahana Srinivasan, Xuguang Ai, Minjie Zou, Ke Zou, Hyunjae Kim, Thaddaeus Wai Soon Lo, Krithi Pushpanathan, Yiming Kong, Anran Li, Maxwell Singer, Kai Jin, Fares Antaki, David Ziyou Chen, Dianbo Liu, Ron A. Adelman, Qingyu Chen, Yih Chung Tham  

**Link**: [PDF](https://arxiv.org/pdf/2501.13949)  

**Abstract**: Question: What is the performance and reasoning ability of OpenAI o1 compared to other large language models in addressing ophthalmology-specific questions?
Findings: This study evaluated OpenAI o1 and five LLMs using 6,990 ophthalmological questions from MedMCQA. O1 achieved the highest accuracy (0.88) and macro-F1 score but ranked third in reasoning capabilities based on text-generation metrics. Across subtopics, o1 ranked first in ``Lens'' and ``Glaucoma'' but second to GPT-4o in ``Corneal and External Diseases'', ``Vitreous and Retina'' and ``Oculoplastic and Orbital Diseases''. Subgroup analyses showed o1 performed better on queries with longer ground truth explanations.
Meaning: O1's reasoning enhancements may not fully extend to ophthalmology, underscoring the need for domain-specific refinements to optimize performance in specialized fields like ophthalmology. 

**Abstract (ZH)**: 问题：OpenAI o1 在回答眼科特定问题时的表现及其推理能力与其它大型语言模型相比如何？

发现：本研究使用来自 MedMCQA 的 6,990 个眼科问题，对 OpenAI o1 和五种其他大型语言模型（LLM）进行了评估。o1 在准确率（0.88）和宏观 F1 分数方面表现最佳，但在基于文本生成的指标上推理能力排名第三。在子主题方面，o1 在“晶状体”和“青光眼”领域排名第一，但在“角膜和外眼疾病”、“玻璃体和视网膜疾病”以及“眼眶和眼整形疾病”领域分别被 GPT-4o 排名第二。亚组分析显示，o1 在具有较长真实解释的查询上表现更好。

意义：o1 的推理增强可能未能完全扩展到眼科领域，这强调了在专业领域如眼科进行领域特定优化的重要性，以优化性能。 

---
# Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks 

**Title (ZH)**: 使用代理AI基座语言框架减轻幻觉现象 

**Authors**: Diego Gosmar, Deborah A. Dahl  

**Link**: [PDF](https://arxiv.org/pdf/2501.13946)  

**Abstract**: Hallucinations remain a significant challenge in current Generative AI models, undermining trust in AI systems and their reliability. This study investigates how orchestrating multiple specialized Artificial Intelligent Agents can help mitigate such hallucinations, with a focus on systems leveraging Natural Language Processing (NLP) to facilitate seamless agent interactions. To achieve this, we design a pipeline that introduces over three hundred prompts, purposefully crafted to induce hallucinations, into a front-end agent. The outputs are then systematically reviewed and refined by second- and third-level agents, each employing distinct large language models and tailored strategies to detect unverified claims, incorporate explicit disclaimers, and clarify speculative content. Additionally, we introduce a set of novel Key Performance Indicators (KPIs) specifically designed to evaluate hallucination score levels. A dedicated fourth-level AI agent is employed to evaluate these KPIs, providing detailed assessments and ensuring accurate quantification of shifts in hallucination-related behaviors. A core component of this investigation is the use of the OVON (Open Voice Network) framework, which relies on universal NLP-based interfaces to transfer contextual information among agents. Through structured JSON messages, each agent communicates its assessment of the hallucination likelihood and the reasons underlying questionable content, thereby enabling the subsequent stage to refine the text without losing context. The results demonstrate that employing multiple specialized agents capable of interoperating with each other through NLP-based agentic frameworks can yield promising outcomes in hallucination mitigation, ultimately bolstering trust within the AI community. 

**Abstract (ZH)**: 幻觉仍然是当前生成型人工智能模型中的重大挑战，削弱了人们对人工智能系统及其可靠性的信任。本研究探讨了如何通过协调多个专门的人工智能代理来减轻这样的幻觉，重点关注利用自然语言处理（NLP）促进代理间无缝交互的系统。为了实现这一目标，我们设计了一条管线，将超过三百个旨在诱发幻觉的提示引入前端代理。然后，这些输出由第二级和第三级代理系统地审查和修订，每级代理使用不同的大型语言模型和定制策略来检测未验证的声明、纳入明确的免责声明，并澄清推测性内容。此外，我们引入了一组新的关键绩效指标（KPI），专门设计用于评估幻觉评分水平。一个专门的第四级AI代理用于评估这些KPI，提供详细的评估并确保幻觉相关行为变化的准确量化。本研究的核心成分为采用OVON（开放语音网络）框架，该框架依赖于基于通用NLP的接口在代理之间传递上下文信息。通过结构化的JSON消息，每个代理传达其对幻觉可能性的评估以及可疑内容的原因，从而使得后一阶段能够不丢失上下文地调整文本。研究结果表明，通过利用能够通过基于NLP的代理框架相互协作的多个专门代理，可以在幻觉减轻方面取得令人鼓舞的结果，最终增强人工智能社区的信任度。 

---
# Self-Explanation in Social AI Agents 

**Title (ZH)**: 社会人工智能代理中的自我解释 

**Authors**: Rhea Basappa, Mustafa Tekman, Hong Lu, Benjamin Faught, Sandeep Kakar, Ashok K. Goel  

**Link**: [PDF](https://arxiv.org/pdf/2501.13945)  

**Abstract**: Social AI agents interact with members of a community, thereby changing the behavior of the community. For example, in online learning, an AI social assistant may connect learners and thereby enhance social interaction. These social AI assistants too need to explain themselves in order to enhance transparency and trust with the learners. We present a method of self-explanation that uses introspection over a self-model of an AI social assistant. The self-model is captured as a functional model that specifies how the methods of the agent use knowledge to achieve its tasks. The process of generating self-explanations uses Chain of Thought to reflect on the self-model and ChatGPT to provide explanations about its functioning. We evaluate the self-explanation of the AI social assistant for completeness and correctness. We also report on its deployment in a live class. 

**Abstract (ZH)**: 社会人工智能代理与社区成员交互，从而改变社区的行为。例如，在在线学习中，一个人工智能社交助手可以连接学习者，从而增强社会互动。这些社会人工智能助手也需要进行自我解释，以提高透明度和与学习者的信任度。我们提出了一种基于自我模型进行自我解释的方法，该自我模型借鉴了人工智能社交助手的内在认知过程。自我模型被表示为一个功能性模型，规定了代理使用知识来完成任务的方法。生成自我解释的过程使用“链式思考”来反思自我模型，并使用ChatGPT来解释其运作机制。我们评估了人工智能社交助手的自我解释的完整性和准确性，并在其实际课程中进行了部署。 

---
# Hybrid Quantum-Classical Multi-Agent Pathfinding 

**Title (ZH)**: 混合量子-经典多智能体路径规划 

**Authors**: Thore Gerlach, Loong Kuan Lee, Frédéric Barbaresco, Nico Piatkowski  

**Link**: [PDF](https://arxiv.org/pdf/2501.14568)  

**Abstract**: Multi-Agent Path Finding (MAPF) focuses on determining conflict-free paths for multiple agents navigating through a shared space to reach specified goal locations. This problem becomes computationally challenging, particularly when handling large numbers of agents, as frequently encountered in practical applications like coordinating autonomous vehicles. Quantum computing (QC) is a promising candidate in overcoming such limits. However, current quantum hardware is still in its infancy and thus limited in terms of computing power and error robustness. In this work, we present the first optimal hybrid quantum-classical MAPF algorithm which is based on branch-and-cut-and-prize. QC is integrated by iteratively solving QUBO problems, based on conflict graphs. Experiments on actual quantum hardware and results on benchmark data suggest that our approach dominates previous QUBO formulations and baseline MAPF solvers. 

**Abstract (ZH)**: 多Agent路径规划（Multi-Agent Path Finding，MAPF）旨在为多个代理在共享空间中导航到指定的目标位置时确定无冲突的路径。当处理大量代理时，这一问题变得计算上更具挑战性，尤其是在实际应用中协调自动驾驶车辆时更为常见。量子计算（Quantum Computing，QC）是一种克服此类限制的有前途的候选技术。然而，当前的量子硬件仍处于初级阶段，因此在计算能力和错误鲁棒性方面受限。在本工作中，我们提出了第一个基于分支、切割和奖励的最优混合量子-经典MAPF算法。我们通过迭代解决基于冲突图的QUBO问题将QC集成进来。在实际量子硬件上的实验和基准数据上的结果表明，我们的方法优于以往的QUBO公式化方法和基准MAPF求解器。 

---
# MASTER: A Multi-Agent System with LLM Specialized MCTS 

**Title (ZH)**: MASTER：一种专门化的LLM多代理系统与MCTS结合的架构 

**Authors**: Bingzheng Gan, Yufan Zhao, Tianyi Zhang, Jing Huang, Yusu Li, Shu Xian Teo, Changwang Zhang, Wei Shi  

**Link**: [PDF](https://arxiv.org/pdf/2501.14304)  

**Abstract**: Large Language Models (LLM) are increasingly being explored for problem-solving tasks. However, their strategic planning capability is often viewed with skepticism. Recent studies have incorporated the Monte Carlo Tree Search (MCTS) algorithm to augment the planning capacity of LLM. Despite its potential, MCTS relies on extensive sampling simulations to approximate the true reward distribution, leading to two primary issues. Firstly, MCTS is effective for tasks like the Game of Go, where simulation results can yield objective rewards (e.g., 1 for a win and 0 for a loss). However, for tasks such as question answering, the result of a simulation is the answer to the question, which cannot obtain an objective reward without the ground truth. Secondly, obtaining statistically significant reward estimations typically requires a sample size exceeding 30 simulations, resulting in excessive token usage and time consumption. To address these challenges, we present Multi-Agent System with Tactical Execution and Reasoning using LLM Specialized MCTS (MASTER), a novel framework that coordinates agent recruitment and communication using LLM specialized MCTS. This system autonomously adjusts the number of agents based on task complexity and ensures focused communication among them. Comprehensive experiments across various tasks demonstrate the effectiveness of our proposed framework. It achieves 76% accuracy on HotpotQA and 80% on WebShop, setting new state-of-the-art performance on these datasets. 

**Abstract (ZH)**: 大型语言模型（LLM）越来越多地被应用于问题解决任务中。然而，人们对其战略规划能力持怀疑态度。近期的研究将蒙特卡洛树搜索（MCTS）算法引入LLM，以增强其规划能力。尽管MCTS具有潜力，但它依赖于广泛的采样模拟来近似真实的奖励分布，导致了两个主要问题。首先，MCTS在围棋等任务中表现良好，因为这些任务的模拟结果可以产生客观奖励（例如胜利计1分，失败计0分）。然而，对于诸如问答等任务，模拟的结果只是问题的答案，没有 ground truth 时很难获得客观奖励。其次，通常需要超过30次模拟来获得统计上显著的奖励估计，这会导致大量的 token 使用和时间消耗。为了解决这些问题，我们提出了一个名为 Multi-Agent System with Tactical Execution and Reasoning using LLM Specialized MCTS（MASTER）的新型框架，该框架利用LLM专项MCTS协调代理的招募和沟通。此系统根据任务复杂性自主调整代理数量，并确保它们之间的集中沟通。跨多种任务的综合实验表明，我们提出的框架具有有效性。它在HotpotQA上的准确率达到76%，在WebShop上的准确率达到80%，在这些数据集上设置了新的最先进的性能标准。 

---
# Top Ten Challenges Towards Agentic Neural Graph Databases 

**Title (ZH)**: 向着能动神经图数据库发展的十大挑战 

**Authors**: Jiaxin Bai, Zihao Wang, Yukun Zhou, Hang Yin, Weizhi Fei, Qi Hu, Zheye Deng, Jiayang Cheng, Tianshi Zheng, Hong Ting Tsang, Yisen Gao, Zhongwei Xie, Yufei Li, Lixin Fan, Binhang Yuan, Wei Wang, Lei Chen, Xiaofang Zhou, Yangqiu Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.14224)  

**Abstract**: Graph databases (GDBs) like Neo4j and TigerGraph excel at handling interconnected data but lack advanced inference capabilities. Neural Graph Databases (NGDBs) address this by integrating Graph Neural Networks (GNNs) for predictive analysis and reasoning over incomplete or noisy data. However, NGDBs rely on predefined queries and lack autonomy and adaptability. This paper introduces Agentic Neural Graph Databases (Agentic NGDBs), which extend NGDBs with three core functionalities: autonomous query construction, neural query execution, and continuous learning. We identify ten key challenges in realizing Agentic NGDBs: semantic unit representation, abductive reasoning, scalable query execution, and integration with foundation models like large language models (LLMs). By addressing these challenges, Agentic NGDBs can enable intelligent, self-improving systems for modern data-driven applications, paving the way for adaptable and autonomous data management solutions. 

**Abstract (ZH)**: 以下是经过学术规范翻译后的中文内容：

图形数据库（GDBs）如Neo4j和TigerGraph在处理互联数据方面表现出色，但在推理能力方面尚存不足。神经图形数据库（NGDBs）通过集成图神经网络（GNNs）来弥补这一不足，用于预测分析和处理不完整或嘈杂的数据。然而，NGDBs依赖预定义查询，缺乏自主性和适应性。本文提出了一种具有自主功能的神经图形数据库（Agentic NGDBs），它在NGDBs的基础上增加了三个核心功能：自主查询构建、神经查询执行和持续学习。我们识别出实现Agentic NGDBs的十个关键挑战，包括语义单元表示、归纳推理、可扩展的查询执行以及与大规模语言模型（LLMs）等基础模型的集成。通过解决这些挑战，Agentic NGDBs可以为现代数据驱动应用提供智能、自我提升的系统，从而促进适应性强的自主数据管理解决方案的发展。 

---
# Distributed Multi-Agent Coordination Using Multi-Modal Foundation Models 

**Title (ZH)**: 使用多模态基础模型进行分布式多代理协调 

**Authors**: Saaduddin Mahmud, Dorian Benhamou Goldfajn, Shlomo Zilberstein  

**Link**: [PDF](https://arxiv.org/pdf/2501.14189)  

**Abstract**: Distributed Constraint Optimization Problems (DCOPs) offer a powerful framework for multi-agent coordination but often rely on labor-intensive, manual problem construction. To address this, we introduce VL-DCOPs, a framework that takes advantage of large multimodal foundation models (LFMs) to automatically generate constraints from both visual and linguistic instructions. We then introduce a spectrum of agent archetypes for solving VL-DCOPs: from a neuro-symbolic agent that delegates some of the algorithmic decisions to an LFM, to a fully neural agent that depends entirely on an LFM for coordination. We evaluate these agent archetypes using state-of-the-art LLMs (large language models) and VLMs (vision language models) on three novel VL-DCOP tasks and compare their respective advantages and drawbacks. Lastly, we discuss how this work extends to broader frontier challenges in the DCOP literature. 

**Abstract (ZH)**: 分布式约束优化问题（DCOPs）提供了一种强大的多代理协调框架，但通常依赖于耗时的手工问题构建。为解决这一问题，我们引入了VL-DCOPs框架，利用大规模多模态基础模型（LFMs）从视觉和语言指令中自动生成约束。接着，我们提出了解决VL-DCOPs的一系列代理原型：从一种神经符号代理，它将部分算法决策委托给LFM，到一种完全依赖LFM进行协调的全神经代理。我们使用最先进的大型语言模型（LLMs）和视觉语言模型（VLMs）来评估这些代理原型，并比较各自的优缺点。最后，我们讨论了这项工作如何扩展到DCOP文献中的更广泛的前沿挑战。 

---
# An Attentive Graph Agent for Topology-Adaptive Cyber Defence 

**Title (ZH)**: 一种适应拓扑结构的注意力图代理用于网络安全防御 

**Authors**: Ilya Orson Sandoval, Isaac Symes Thompson, Vasilios Mavroudis, Chris Hicks  

**Link**: [PDF](https://arxiv.org/pdf/2501.14700)  

**Abstract**: As cyber threats grow increasingly sophisticated, reinforcement learning is emerging as a promising technique to create intelligent, self-improving defensive systems. However, most existing autonomous defensive agents have overlooked the inherent graph structure of computer networks subject to cyber attacks, potentially missing critical information. To address this gap, we developed a custom version of the Cyber Operations Research Gym (CybORG) environment that encodes the observable network state as a directed graph, utilizing realistic and interpretable low-level features. %, like number of open ports and unexpected detected connections. We leverage a Graph Attention Network (GAT) architecture to process node, edge, and global features, and modify its output to be compatible with policy gradient methods in reinforcement learning. GAT policies offer several advantages over standard approaches based on simplistic flattened state observations. They can handle the changes in network topology that occur at runtime when dynamic connections between hosts appear. Policies can be deployed to networks that differ in size to the ones seen during training, enabling a degree of generalisation inaccessible with alternative approaches. Furthermore, the graph neural network policies outputs are explainable in terms of tangible network properties, providing enhanced interpretability of defensive actions. We verify that our low-level graph observations are meaningful enough to train GAT defensive policies that are able to adapt to changing topologies. We evaluate how our trained policies perform when deployed on networks of varying sizes with the same subnetwork structure, comparing them against policies specifically trained for each network configuration. Our study contributes to the development of robust cyber defence systems that can better adapt to real-world network security challenges. 

**Abstract (ZH)**: 随着网络威胁日益复杂，强化学习正逐渐成为创建智能、自我改进防御系统的有前途的技术。然而，现有的大多数自主防御代理忽视了受网络攻击影响的计算机网络中的固有图形结构，可能导致关键信息的缺失。为解决这一问题，我们开发了一个自定义版本的Cyber Operations Research Gym（CybORG）环境，将可观察的网络状态编码为有向图，利用了现实且可解释的低层特征，例如开放端口的数量和意外检测到的连接。我们利用图形注意网络（GAT）架构来处理节点、边缘和全局特征，并修改其输出以与强化学习中的策略梯度方法兼容。与基于简化的展平状态观测的标准方法相比，GAT策略具有多种优势。它们可以处理运行时因主机之间动态连接而发生的网络拓扑变化。这些策略可以在与训练时不同的网络规模上部署，从而实现替代方法无法比拟的泛化能力。此外，图形神经网络策略的输出可以用具体的网络属性来解释，提供了对防御行动增强可解释性的提升。我们验证了我们的低层图形观察足够有意义，能够训练出能够适应拓扑变化的GAT防御策略。我们评估了所训练策略在具有不同规模但相同子网络结构的网络上的表现，并将它们与专门针对每个网络配置训练的策略进行了比较。本研究为开发能够更好地应对现实世界网络安全挑战的稳健型网络防御系统做出了贡献。 

---
# MedAgentBench: Dataset for Benchmarking LLMs as Agents in Medical Applications 

**Title (ZH)**: MedAgentBench：医疗应用中LLM作为代理的 benchmarks 数据集 

**Authors**: Yixing Jiang, Kameron C. Black, Gloria Geng, Danny Park, Andrew Y. Ng, Jonathan H. Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.14654)  

**Abstract**: Recent large language models (LLMs) have demonstrated significant advancements, particularly in their ability to serve as agents thereby surpassing their traditional role as chatbots. These agents can leverage their planning and tool utilization capabilities to address tasks specified at a high level. However, a standardized dataset to benchmark the agent capabilities of LLMs in medical applications is currently lacking, making the evaluation of LLMs on complex tasks in interactive healthcare environments challenging. To address this gap, we introduce MedAgentBench, a broad evaluation suite designed to assess the agent capabilities of large language models within medical records contexts. MedAgentBench encompasses 100 patient-specific clinically-derived tasks from 10 categories written by human physicians, realistic profiles of 100 patients with over 700,000 data elements, a FHIR-compliant interactive environment, and an accompanying codebase. The environment uses the standard APIs and communication infrastructure used in modern EMR systems, so it can be easily migrated into live EMR systems. MedAgentBench presents an unsaturated agent-oriented benchmark that current state-of-the-art LLMs exhibit some ability to succeed at. The best model (GPT-4o) achieves a success rate of 72%. However, there is still substantial space for improvement to give the community a next direction to optimize. Furthermore, there is significant variation in performance across task categories. MedAgentBench establishes this and is publicly available at this https URL , offering a valuable framework for model developers to track progress and drive continuous improvements in the agent capabilities of large language models within the medical domain. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在各个方面都显示出显著的进步，尤其是在它们作为代理的能力上，这超越了它们传统的聊天机器人角色。这些代理可以利用其规划和工具利用能力来解决高层次指定的任务。然而，在医学应用中缺乏一个标准化的数据集来评估LLM代理能力，这使得在交互式医疗环境中对LLM进行复杂任务评估变得具有挑战性。为了解决这个问题，我们介绍了MedAgentBench，一个广泛的评估套件，用于评估大型语言模型在医疗记录环境中的代理能力。MedAgentBench 包含来自10个类别、100个由人类医生编制的患者特定临床任务、100个具有超过70万个数据元素的患者真实档案、一个符合FHIR标准的互动环境和相应的代码库。该环境使用现代电子病历系统中常用的标准API和通信基础设施，因此可以轻松迁移到实时电子病历系统中。MedAgentBench 提供了一个未饱和的代理导向基准，当前最先进的LLM在某些方面表现出成功的能力。最佳模型（GPT-4o）的成功率为72%，但仍有改进空间，为社区提供下一步优化的方向。此外，不同任务类别之间的性能波动很大。MedAgentBench 建立了这一点，并在此处 https:// [网站地址] 公开提供，为模型开发者提供了一个有价值的框架，用于跟踪进度并推动大型语言模型代理能力在医学领域的持续改进。 

---
# Learning more with the same effort: how randomization improves the robustness of a robotic deep reinforcement learning agent 

**Title (ZH)**: 用同样的努力学习更多：随机化如何提高机器人深度 reinforcement 学习代理的鲁棒性 

**Authors**: Lucía Güitta-López, Jaime Boal, Álvaro J. López-López  

**Link**: [PDF](https://arxiv.org/pdf/2501.14443)  

**Abstract**: The industrial application of Deep Reinforcement Learning (DRL) is frequently slowed down because of the inability to generate the experience required to train the models. Collecting data often involves considerable time and economic effort that is unaffordable in most cases. Fortunately, devices like robots can be trained with synthetic experience thanks to virtual environments. With this approach, the sample efficiency problems of artificial agents are mitigated, but another issue arises: the need for efficiently transferring the synthetic experience into the real world (sim-to-real).
This paper analyzes the robustness of a state-of-the-art sim-to-real technique known as progressive neural networks (PNNs) and studies how adding diversity to the synthetic experience can complement it. To better understand the drivers that lead to a lack of robustness, the robotic agent is still tested in a virtual environment to ensure total control on the divergence between the simulated and real models.
The results show that a PNN-like agent exhibits a substantial decrease in its robustness at the beginning of the real training phase. Randomizing certain variables during simulation-based training significantly mitigates this issue. On average, the increase in the model's accuracy is around 25% when diversity is introduced in the training process. This improvement can be translated into a decrease in the required real experience for the same final robustness performance. Notwithstanding, adding real experience to agents should still be beneficial regardless of the quality of the virtual experience fed into the agent. 

**Abstract (ZH)**: 以下是将该内容翻译成中文，同时保持学术规范：

Deep强化学习（DRL）在工业应用中的广泛应用常常受到无法生成足够的经验数据以训练模型的限制。数据收集通常需要大量的时间和经济投入，而在大多数情况下这些投入都是不可行的。幸运的是，由于虚拟环境的支持，机器人等设备可以通过合成经验进行训练。这种方法有助于缓解人工代理的样本效率问题，但同时又产生了一个新的问题：如何高效地将合成经验转移到现实世界中（即从虚拟到现实的迁移）。

本文分析了一种名为渐进神经网络（Progressive Neural Networks, PNN）的先进仿真实现真实技术的鲁棒性，并研究了如何通过增加合成经验的多样性来补充其不足之处。为了更好地理解导致鲁棒性不足的驱动因素，机器人代理仍然在虚拟环境中进行测试，以确保对模拟与真实模型之间的差异进行全面控制。

实验结果表明，在实际训练阶段开始时，PNN 类代理的鲁棒性会出现显著下降。在基于模拟的训练中随机化某些变量可以显著缓解这一问题。在引入多样性的培训过程中，模型的准确性平均提高约25%。这种改进可以转化为在相同最终鲁棒性表现下减少所需的真实经验量。尽管如此，即使虚拟经验的质量不理想，向代理中添加真实经验仍然有益。

这段翻译保持了原文的学术风格和专业术语，同时确保了中文表达的准确性和流畅性。 

---
# Coordinating Ride-Pooling with Public Transit using Reward-Guided Conservative Q-Learning: An Offline Training and Online Fine-Tuning Reinforcement Learning Framework 

**Title (ZH)**: 使用奖励引导保守Q学习协调拼车与公共交通：一个离线训练与在线微调的强化学习框架 

**Authors**: Yulong Hu, Tingting Dong, Sen Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.14199)  

**Abstract**: This paper introduces a novel reinforcement learning (RL) framework, termed Reward-Guided Conservative Q-learning (RG-CQL), to enhance coordination between ride-pooling and public transit within a multimodal transportation network. We model each ride-pooling vehicle as an agent governed by a Markov Decision Process (MDP) and propose an offline training and online fine-tuning RL framework to learn the optimal operational decisions of the multimodal transportation systems, including rider-vehicle matching, selection of drop-off locations for passengers, and vehicle routing decisions, with improved data efficiency. During the offline training phase, we develop a Conservative Double Deep Q Network (CDDQN) as the action executor and a supervised learning-based reward estimator, termed the Guider Network, to extract valuable insights into action-reward relationships from data batches. In the online fine-tuning phase, the Guider Network serves as an exploration guide, aiding CDDQN in effectively and conservatively exploring unknown state-action pairs. The efficacy of our algorithm is demonstrated through a realistic case study using real-world data from Manhattan. We show that integrating ride-pooling with public transit outperforms two benchmark cases solo rides coordinated with transit and ride-pooling without transit coordination by 17% and 22% in the achieved system rewards, respectively. Furthermore, our innovative offline training and online fine-tuning framework offers a remarkable 81.3% improvement in data efficiency compared to traditional online RL methods with adequate exploration budgets, with a 4.3% increase in total rewards and a 5.6% reduction in overestimation errors. Experimental results further demonstrate that RG-CQL effectively addresses the challenges of transitioning from offline to online RL in large-scale ride-pooling systems integrated with transit. 

**Abstract (ZH)**: 本文介绍了一种新颖的强化学习（RL）框架，称为奖励引导保守Q学习（RG-CQL），以增强乘车共享与公共交通在多模态交通网络中的协调能力。我们将每辆乘车共享车辆视为由马尔可夫决策过程（MDP）驱动的智能体，并提出了一种离线训练和在线精细调整的RL框架，以提高多模态交通系统的最优运营决策，包括乘客与车辆配对、乘客下车地点选择以及车辆路径规划决策，同时提高了数据效率。在离线训练阶段，我们开发了一种保守的双重深度Q网络（CDDQN）作为动作执行器，并提出了一种基于监督学习的奖励估计器，即引导网络，从数据批次中提取行动-奖励关系中的有价值的见解。在在线精细调整阶段，引导网络充当探索指南，帮助CDDQN有效地、保守地探索未知的状态-行动对。通过使用来自曼哈顿的真实世界数据进行的实际案例研究，证明了该算法的有效性。结果显示，将乘车共享与公共交通相结合在实现系统奖励方面分别比单一乘车与公共交通协调以及非协调的乘车共享分别提升了17%和22%。此外，我们的创新性离线训练和在线精细调整框架在具有足够探索预算的传统在线RL方法中提供了81.3%的数据效率改进，同时总奖励增长了4.3%，错误估计减少了5.6%。实验结果进一步证明，RG-CQL有效地解决了大规模整合公共交通的乘车共享系统从离线到在线RL过渡中的挑战。 

---
# RL + Transformer = A General-Purpose Problem Solver 

**Title (ZH)**: RL + Transformer = 通用问题求解器 

**Authors**: Micah Rentschler, Jesse Roberts  

**Link**: [PDF](https://arxiv.org/pdf/2501.14176)  

**Abstract**: What if artificial intelligence could not only solve problems for which it was trained but also learn to teach itself to solve new problems (i.e., meta-learn)? In this study, we demonstrate that a pre-trained transformer fine-tuned with reinforcement learning over multiple episodes develops the ability to solve problems that it has never encountered before - an emergent ability called In-Context Reinforcement Learning (ICRL). This powerful meta-learner not only excels in solving unseen in-distribution environments with remarkable sample efficiency, but also shows strong performance in out-of-distribution environments. In addition, we show that it exhibits robustness to the quality of its training data, seamlessly stitches together behaviors from its context, and adapts to non-stationary environments. These behaviors demonstrate that an RL-trained transformer can iteratively improve upon its own solutions, making it an excellent general-purpose problem solver. 

**Abstract (ZH)**: 如果我们的人工智能不仅能解决它被训练来解决的问题，还能学会自我教学以解决新问题（即元学习），会怎样呢？在本研究中，我们展示了预训练的变换器通过多阶段强化学习微调后，能够解决它从未遇到过的新问题——这种能力被称为上下文强化学习（In-Context Reinforcement Learning, ICRL）。这种强大的元学习模型不仅在解决未见的分布内环境方面表现出非凡的样本效率，还在未见的分布外环境中也表现出较强的性能。此外，我们还证明了该模型对训练数据质量具有较强的鲁棒性，能够无缝地将上下文中的行为结合在一起，并适应非平稳环境。这些行为表明，经过强化学习训练的变换器可以逐步改进自己的解决方案，使其成为一种优秀的通用问题解决者。 

---
# Reinforcement Learning Platform for Adversarial Black-box Attacks with Custom Distortion Filters 

**Title (ZH)**: 基于自定义失真滤波器的对抗黑盒攻击强化学习平台 

**Authors**: Soumyendu Sarkar, Ashwin Ramesh Babu, Sajad Mousavi, Vineet Gundecha, Sahand Ghorbanpour, Avisek Naug, Ricardo Luna Gutierrez, Antonio Guillen  

**Link**: [PDF](https://arxiv.org/pdf/2501.14122)  

**Abstract**: We present a Reinforcement Learning Platform for Adversarial Black-box untargeted and targeted attacks, RLAB, that allows users to select from various distortion filters to create adversarial examples. The platform uses a Reinforcement Learning agent to add minimum distortion to input images while still causing misclassification by the target model. The agent uses a novel dual-action method to explore the input image at each step to identify sensitive regions for adding distortions while removing noises that have less impact on the target model. This dual action leads to faster and more efficient convergence of the attack. The platform can also be used to measure the robustness of image classification models against specific distortion types. Also, retraining the model with adversarial samples significantly improved robustness when evaluated on benchmark datasets. The proposed platform outperforms state-of-the-art methods in terms of the average number of queries required to cause misclassification. This advances trustworthiness with a positive social impact. 

**Abstract (ZH)**: 我们提出了一种用于对抗性黑盒未 targeted 和 targeted 攻击的强化学习平台，RLAB，该平台允许用户从多种扭曲滤镜中选择，以创建对抗性示例。该平台利用强化学习代理在不显著增加输入图像失真的情况下，仍能使目标模型产生误分类。代理在每一步探索输入图像时采用一种新颖的双行动方法，以识别适合添加失真的敏感区域，同时去除对目标模型影响较小的噪声。这种双行动方法导致攻击更快且更有效率地收敛。该平台还可以用于测量图像分类模型对特定失真类型的鲁棒性。此外，使用对抗性样本重新训练模型在基准数据集上的表现显著提高了模型的鲁棒性。所提出的平台在引起误分类所需的平均查询次数上优于现有方法。这促进了信任度并产生积极的社会影响。 

---
# CSAOT: Cooperative Multi-Agent System for Active Object Tracking 

**Title (ZH)**: CSAOT：协同多代理系统在活性对象追踪中的应用 

**Authors**: Hy Nguyen, Bao Pham, Hung Du, Srikanth Thudumu, Rajesh Vasa, Kon Mouzakis  

**Link**: [PDF](https://arxiv.org/pdf/2501.13994)  

**Abstract**: Object Tracking is essential for many computer vision applications, such as autonomous navigation, surveillance, and robotics. Unlike Passive Object Tracking (POT), which relies on static camera viewpoints to detect and track objects across consecutive frames, Active Object Tracking (AOT) requires a controller agent to actively adjust its viewpoint to maintain visual contact with a moving target in complex environments. Existing AOT solutions are predominantly single-agent-based, which struggle in dynamic and complex scenarios due to limited information gathering and processing capabilities, often resulting in suboptimal decision-making. Alleviating these limitations necessitates the development of a multi-agent system where different agents perform distinct roles and collaborate to enhance learning and robustness in dynamic and complex environments. Although some multi-agent approaches exist for AOT, they typically rely on external auxiliary agents, which require additional devices, making them costly. In contrast, we introduce the Collaborative System for Active Object Tracking (CSAOT), a method that leverages multi-agent deep reinforcement learning (MADRL) and a Mixture of Experts (MoE) framework to enable multiple agents to operate on a single device, thereby improving tracking performance and reducing costs. Our approach enhances robustness against occlusions and rapid motion while optimizing camera movements to extend tracking duration. We validated the effectiveness of CSAOT on various interactive maps with dynamic and stationary obstacles. 

**Abstract (ZH)**: 对象跟踪对于许多计算机视觉应用（如自主导航、监控和机器人技术）至关重要。与被动对象跟踪（POT）不同，被动对象跟踪依赖于静态摄像头视角来检测和跟踪连续帧中的对象，而主动对象跟踪（AOT）需要一个控制器代理主动调整其视角，以在复杂环境下保持与移动目标的视觉接触。现有的AOT解决方案大多基于单个代理，由于信息收集和处理能力的限制，在动态和复杂场景中通常表现不佳，导致决策效果欠佳。要解决这些限制，需要开发一个多代理系统，其中不同代理执行不同的任务并协同工作，以增强在动态和复杂环境中的学习和稳健性。虽然存在一些基于多代理的方法来实现AOT，但它们通常依赖于外部辅助代理，这需要额外的设备，从而使它们成本较高。相比之下，我们提出了一种协作的主动对象跟踪系统（CSAOT）方法，该方法利用多代理深度强化学习（MADRL）和专家混合（Mixture of Experts, MoE）框架，使多个代理能够在单个设备上协同工作，从而提高跟踪性能并降低成本。我们的方法增强了对遮挡和快速运动的鲁棒性，并优化了摄像机运动以延长跟踪时间。我们通过在具有动态和静态障碍的多种交互地图上验证CSAOT的有效性，证明了其优越性。 

---