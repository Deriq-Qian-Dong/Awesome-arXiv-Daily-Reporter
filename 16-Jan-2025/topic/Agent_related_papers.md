# Personality Modeling for Persuasion of Misinformation using AI Agent 

**Title (ZH)**: 使用AI代理进行错误信息的劝说个性建模 

**Authors**: Qianmin Lou, Wentao Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.08985)  

**Abstract**: The proliferation of misinformation on social media platforms has highlighted the need to understand how individual personality traits influence susceptibility to and propagation of misinformation. This study employs an innovative agent-based modeling approach to investigate the relationship between personality traits and misinformation dynamics. Using six AI agents embodying different dimensions of the Big Five personality traits (Extraversion, Agreeableness, and Neuroticism), we simulated interactions across six diverse misinformation topics. The experiment, implemented through the AgentScope framework using the GLM-4-Flash model, generated 90 unique interactions, revealing complex patterns in how personality combinations affect persuasion and resistance to misinformation. Our findings demonstrate that analytical and critical personality traits enhance effectiveness in evidence-based discussions, while non-aggressive persuasion strategies show unexpected success in misinformation correction. Notably, agents with critical traits achieved a 59.4% success rate in HIV-related misinformation discussions, while those employing non-aggressive approaches maintained consistent persuasion rates above 40% across different personality combinations. The study also revealed a non-transitive pattern in persuasion effectiveness, challenging conventional assumptions about personality-based influence. These results provide crucial insights for developing personality-aware interventions in digital environments and suggest that effective misinformation countermeasures should prioritize emotional connection and trust-building over confrontational approaches. The findings contribute to both theoretical understanding of personality-misinformation dynamics and practical strategies for combating misinformation in social media contexts. 

**Abstract (ZH)**: 社交媒体平台上虚假信息的泛滥凸显了理解个体人格特质如何影响对虚假信息的易感性和传播的重要性。本研究采用了创新性的基于代理的建模方法，探讨了人格特质与虚假信息动态之间的关系。通过六个AI代理分别代表五大人格特质的不同维度（外向性、宜人性和神经质），我们模拟了跨六个不同虚假信息主题的交互过程。实验基于AgentScope框架和GLM-4-Flash模型实施，生成了90种独特的交互模式，揭示了人格组合如何影响说服力和抵御虚假信息的复杂模式。研究结果表明，分析性和批判性的人格特质增强了基于证据的讨论的有效性，而非侵略性的说服策略在虚假信息纠正中显示出意想不到的成功。值得注意的是，具有批判性特质的代理在与HIV相关的虚假信息讨论中成功率达到59.4%，而采用非侵略性方法的代理在不同人格组合下的持续说服率保持在40%以上。研究还揭示了说服效果的非传递性模式，挑战了基于人格的影响的传统假设。这些结果为在数字环境中开发的人格意识介入措施提供了重要见解，并建议有效的虚假信息对策应优先考虑情感联系和信任建立，而非对抗性方法。研究成果不仅丰富了关于人格与虚假信息动态的理论理解，还为社交媒体环境下打击虚假信息的实用策略提供了支持。 

---
# Doc-Guided Sent2Sent++: A Sent2Sent++ Agent with Doc-Guided memory for Document-level Machine Translation 

**Title (ZH)**: 文稿导向的 Sent2Sent++：一种带有文稿导向记忆的句子到句子增强代理模型用于文档级机器翻译 

**Authors**: Jiaxin Guo, Yuanchang Luo, Daimeng Wei, Ling Zhang, Zongyao Li, Hengchao Shang, Zhiqiang Rao, Shaojun Li, Jinlong Yang, Zhanglin Wu, Hao Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.08523)  

**Abstract**: The field of artificial intelligence has witnessed significant advancements in natural language processing, largely attributed to the capabilities of Large Language Models (LLMs). These models form the backbone of Agents designed to address long-context dependencies, particularly in Document-level Machine Translation (DocMT). DocMT presents unique challenges, with quality, consistency, and fluency being the key metrics for evaluation. Existing approaches, such as Doc2Doc and Doc2Sent, either omit sentences or compromise fluency. This paper introduces Doc-Guided Sent2Sent++, an Agent that employs an incremental sentence-level forced decoding strategy \textbf{to ensure every sentence is translated while enhancing the fluency of adjacent sentences.} Our Agent leverages a Doc-Guided Memory, focusing solely on the summary and its translation, which we find to be an efficient approach to maintaining consistency. Through extensive testing across multiple languages and domains, we demonstrate that Sent2Sent++ outperforms other methods in terms of quality, consistency, and fluency. The results indicate that, our approach has achieved significant improvements in metrics such as s-COMET, d-COMET, LTCR-$1_f$, and document-level perplexity (d-ppl). The contributions of this paper include a detailed analysis of current DocMT research, the introduction of the Sent2Sent++ decoding method, the Doc-Guided Memory mechanism, and validation of its effectiveness across languages and domains. 

**Abstract (ZH)**: 人工智能领域在自然语言处理方面取得了显著进展，这主要归功于大规模语言模型（LLMs）的能力。这些模型构成了设计用于解决长时间段依赖性问题的代理的基础，特别是在文档级机器翻译（DocMT）方面。DocMT面临独特的挑战，质量、一致性和流畅性是其评价的关键指标。现有的方法如Doc2Doc和Doc2Sent要么省略句子，要么牺牲流畅性。本文介绍了Doc-Guided Sent2Sent++代理，该代理采用逐步句子级强制解码策略，以确保每个句子都能被翻译，并且通过增强相邻句子的流畅性来提升整体翻译质量。我们的代理利用Doc-Guided Memory机制，仅关注总结及其翻译，我们认为这是一种高效的方法，有助于保持一致性。通过在多种语言和领域中进行广泛的测试，我们证明Sent2Sent++在质量、一致性和流畅性方面均优于其他方法。结果表明，我们的方法在s-COMET、d-COMET、LTCR-$1_f$和文档级困惑度（d-ppl）等多项指标上取得了显著改进。本文的贡献包括对当前DocMT研究的详细分析、介绍Sent2Sent++解码方法、Doc-Guided Memory机制及其在不同语言和领域中有效性的验证。 

---
# RLHS: Mitigating Misalignment in RLHF with Hindsight Simulation 

**Title (ZH)**: RLHS：反制RLHF中未对齐问题的 hindsight 回顾模拟方法 

**Authors**: Kaiqu Liang, Haimin Hu, Ryan Liu, Thomas L. Griffiths, Jaime Fernández Fisac  

**Link**: [PDF](https://arxiv.org/pdf/2501.08617)  

**Abstract**: Generative AI systems like foundation models (FMs) must align well with human values to ensure their behavior is helpful and trustworthy. While Reinforcement Learning from Human Feedback (RLHF) has shown promise for optimizing model performance using human judgments, existing RLHF pipelines predominantly rely on immediate feedback, which can fail to accurately reflect the downstream impact of an interaction on users' utility. We demonstrate that feedback based on evaluators' foresight estimates of downstream consequences systematically induces Goodhart's Law dynamics, incentivizing misaligned behaviors like sycophancy and deception and ultimately degrading user outcomes. To alleviate this, we propose decoupling evaluation from prediction by refocusing RLHF on hindsight feedback. Our theoretical analysis reveals that conditioning evaluator feedback on downstream observations mitigates misalignment and improves expected human utility, even when these observations are simulated by the AI system itself. To leverage this insight in a practical alignment algorithm, we introduce Reinforcement Learning from Hindsight Simulation (RLHS), which first simulates plausible consequences and then elicits feedback to assess what behaviors were genuinely beneficial in hindsight. We apply RLHS to two widely-employed online and offline preference optimization methods -- Proximal Policy Optimization (PPO) and Direct Preference Optimization (DPO) -- and show empirically that misalignment is significantly reduced with both methods. Through an online human user study, we show that RLHS consistently outperforms RLHF in helping users achieve their goals and earns higher satisfaction ratings, despite being trained solely with simulated hindsight feedback. These results underscore the importance of focusing on long-term consequences, even simulated ones, to mitigate misalignment in RLHF. 

**Abstract (ZH)**: 生成式AI系统，如基础模型（FMs），必须与人类价值观很好地对齐，以确保其行为具有帮助性和可信度。虽然从人类反馈中进行强化学习（RLHF）已经显示出优化模型性能的潜力，但现有的RLHF流程主要依赖即时反馈，这可能无法准确反映交互对用户效用的下游影响。我们表明，基于评估者对下游后果预期的反馈系统会系统地导致Goodhart法则效应，激励出现不良行为如阿谀奉承和欺骗，最终损害用户成果。为解决这一问题，我们建议通过重新聚焦RLHF于后见之明反馈，从而将评估与预测脱钩。我们的理论分析表明，让评估者的反馈依赖于下游观察可以减轻不一致性和提高预期的人类效用，即使这些观察是由AI系统自身模拟的。为了在实用的对齐算法中利用这一洞察，我们引入了一种新的强化学习后见之明模拟方法（RLHS），该方法首先模拟可能的后果，然后通过获取反馈来评估哪个行为是在后见之明下真正有益的。我们用两种广泛使用的在线和离线偏好优化方法——近端策略优化（PPO）和直接偏好优化（DPO）——应用了RLHS方法，并且实验证实两者中的不一致性的减少情况都很显著。通过在线的人类用户研究，我们展示了即使仅用模拟后见之明反馈进行训练，RLHS也始终优于RLHF，更有效地帮助用户实现其目标，并获得更高的满意度评分。这些结果强调了即使在模拟情况下关注长期内部后果以减轻RLHF中不一致性的必要性。 

---
# Leveraging Large Language Models as Knowledge-Driven Agents for Reliable Retrosynthesis Planning 

**Title (ZH)**: 利用大型语言模型作为知识驱动代理进行可靠的逆合成规划 

**Authors**: Qinyu Ma, Yuhao Zhou, Jianfeng Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.08897)  

**Abstract**: Identifying reliable synthesis pathways in materials chemistry is a complex task, particularly in polymer science, due to the intricate and often non-unique nomenclature of macromolecules. To address this challenge, we propose an agent system that integrates large language models (LLMs) and knowledge graphs (KGs). By leveraging LLMs' powerful capabilities for extracting and recognizing chemical substance names, and storing the extracted data in a structured knowledge graph, our system fully automates the retrieval of relevant literatures, extraction of reaction data, database querying, construction of retrosynthetic pathway trees, further expansion through the retrieval of additional literature and recommendation of optimal reaction pathways. A novel Multi-branched Reaction Pathway Search (MBRPS) algorithm enables the exploration of all pathways, with a particular focus on multi-branched ones, helping LLMs overcome weak reasoning in multi-branched paths. This work represents the first attempt to develop a fully automated retrosynthesis planning agent tailored specially for macromolecules powered by LLMs. Applied to polyimide synthesis, our new approach constructs a retrosynthetic pathway tree with hundreds of pathways and recommends optimized routes, including both known and novel pathways, demonstrating its effectiveness and potential for broader applications. 

**Abstract (ZH)**: 在材料化学中识别可靠的合成途径是一个复杂任务，特别是在聚合物科学领域，由于高分子物质的名称复杂且往往不唯一。为了应对这一挑战，我们提出了一种结合大型语言模型（LLMs）和知识图谱（KGs）的代理系统。通过利用LLMs强大的提取和识别化学物质名称的能力，并将提取的数据存储在结构化知识图谱中，我们的系统实现了有关文献的全自动检索、反应数据的提取、数据库查询、逆向合成路径树的构建，并进一步通过检索额外文献来扩大路径范围，推荐最佳反应途径。一种新型的多分支反应路径搜索（MBRPS）算法能够探索所有可能路径，特别是对于多分支路径的探索尤为突出，帮助LLMs克服多分支路径推理的局限性。本研究代表了利用LLMs构建专门针对高分子的全自动逆向合成规划代理系统的首次尝试。应用到聚酰亚胺的合成中，我们提出的新方法构建了一个包含数百条路径的逆向合成路径树，并推荐了优化路径，包括已知和新颖路径，展示了其有效性和更广泛的应用潜力。 

---
# Application of Deep Reinforcement Learning to UAV Swarming for Ground Surveillance 

**Title (ZH)**: 将以下论文内容或标题翻译成中文，符合学术规范：

"基于深度强化学习的无人机集群地面监视应用" 

**Authors**: Raúl Arranz, David Carramiñana, Gonzalo de Miguel, Juan A. Besada, Ana M. Bernardos  

**Link**: [PDF](https://arxiv.org/pdf/2501.08655)  

**Abstract**: This paper summarizes in depth the state of the art of aerial swarms, covering both classical and new reinforcement-learning-based approaches for their management. Then, it proposes a hybrid AI system, integrating deep reinforcement learning in a multi-agent centralized swarm architecture. The proposed system is tailored to perform surveillance of a specific area, searching and tracking ground targets, for security and law enforcement applications. The swarm is governed by a central swarm controller responsible for distributing different search and tracking tasks among the cooperating UAVs. Each UAV agent is then controlled by a collection of cooperative sub-agents, whose behaviors have been trained using different deep reinforcement learning models, tailored for the different task types proposed by the swarm controller. More specifically, proximal policy optimization (PPO) algorithms were used to train the agents' behavior. In addition, several metrics to assess the performance of the swarm in this application were defined. The results obtained through simulation show that our system searches the operation area effectively, acquires the targets in a reasonable time, and is capable of tracking them continuously and consistently. 

**Abstract (ZH)**: 本文深入总结了空中集群技术的最新进展，涵盖了许多经典和基于新强化学习的方法。在此基础上，提出了一种混合人工智能系统，该系统在多智能体集中式集群架构中集成了深度强化学习。该系统针对特定区域的监控任务进行了优化，旨在搜索和跟踪地面目标，适用于安全和执法领域。集群由中央集群控制器管理，该控制器负责将不同的搜索和跟踪任务分配给协同工作的无人机。每个无人机智能体由一个由不同行为学已被训练以适应集群控制器提出的不同类型任务的合作子智能体集合控制。具体而言，使用近端策略优化（PPO）算法训练了智能体的行为。此外，还定义了一些指标来评估该应用中集群的表现。通过仿真获得的结果表明，我们的系统能够有效地搜索操作区域、在合理的时间内获取目标，并能够持续且一致地跟踪这些目标。 

---
# Networked Agents in the Dark: Team Value Learning under Partial Observability 

**Title (ZH)**: 在信息受限条件下网络化代理的价值学习：部分可观测性团队价值学习 

**Authors**: Guilherme S. Varela, Alberto Sardinha, Francisco S. Melo  

**Link**: [PDF](https://arxiv.org/pdf/2501.08778)  

**Abstract**: We propose a novel cooperative multi-agent reinforcement learning (MARL) approach for networked agents. In contrast to previous methods that rely on complete state information or joint observations, our agents must learn how to reach shared objectives under partial observability. During training, they collect individual rewards and approximate a team value function through local communication, resulting in cooperative behavior. To describe our problem, we introduce the networked dynamic partially observable Markov game framework, where agents communicate over a switching topology communication network. Our distributed method, DNA-MARL, uses a consensus mechanism for local communication and gradient descent for local computation. DNA-MARL increases the range of the possible applications of networked agents, being well-suited for real world domains that impose privacy and where the messages may not reach their recipients. We evaluate DNA-MARL across benchmark MARL scenarios. Our results highlight the superior performance of DNA-MARL over previous methods. 

**Abstract (ZH)**: 我们提出了一种新颖的协作多智能体强化学习（MARL）方法，适用于网络化智能体。与先前依赖完整状态信息或联合观测的方法不同，我们的智能体必须在部分可观测的情况下学会如何达成共享目标。在训练过程中，它们通过局部通信收集个体奖励并近似团队价值函数，从而实现协作行为。为了描述我们的问题，我们引入了网络动态部分可观测马尔可夫游戏框架，其中智能体通过切换拓扑通信网络进行沟通。我们的分布式方法DNA-MARL 使用一致性机制进行局部通信和梯度下降进行局部计算。DNA-MARL 扩展了网络化智能体的应用范围，特别适合那些具有隐私要求且消息可能无法到达接收方的真实世界领域。我们在基准MARL场景中评估了DNA-MARL。我们的结果突显了DNA-MARL相较于先前方法的优越性能。 

---
# Leveraging LLM Agents for Translating Network Configurations 

**Title (ZH)**: 利用大语言模型代理进行网络配置翻译 

**Authors**: Yunze Wei, Xiaohui Xie, Yiwei Zuo, Tianshuo Hu, Xinyi Chen, Kaiwen Chi, Yong Cui  

**Link**: [PDF](https://arxiv.org/pdf/2501.08760)  

**Abstract**: Configuration translation is a critical and frequent task in network operations. When a network device is damaged or outdated, administrators need to replace it to maintain service continuity. The replacement devices may originate from different vendors, necessitating configuration translation to ensure seamless network operation. However, translating configurations manually is a labor-intensive and error-prone process. In this paper, we propose an intent-based framework for translating network configuration with Large Language Model (LLM) Agents. The core of our approach is an Intent-based Retrieval Augmented Generation (IRAG) module that systematically splits a configuration file into fragments, extracts intents, and generates accurate translations. We also design a two-stage verification method to validate the syntax and semantics correctness of the translated configurations. We implement and evaluate the proposed method on real-world network configurations. Experimental results show that our method achieves 97.74% syntax correctness, outperforming state-of-the-art methods in translation accuracy. 

**Abstract (ZH)**: 网络配置的翻译是网络运维中一个关键且频繁的任务。当网络设备出现故障或过时，管理员需要更换设备以保持服务连续性。替换设备可能来自不同的供应商，这需要进行配置翻译以确保网络无缝运行。然而，手动翻译配置是一个劳动密集且易出错的过程。在本文中，我们提出了一种基于意图的框架，利用大型语言模型（LLM）代理进行网络配置翻译。我们方法的核心是一个基于意图的检索增强生成（IRAG）模块，该模块系统地将配置文件拆分为片段、提取意图并生成准确的翻译。我们还设计了一种两阶段验证方法，以验证翻译配置的语法和语义正确性。我们已在实际网络配置上实现了并评估了该方法。实验结果表明，我们的方法在语法正确性方面达到了97.74%，在翻译准确性方面超过了现有最先进的方法。 

---
# AutoRestTest: A Tool for Automated REST API Testing Using LLMs and MARL 

**Title (ZH)**: AutoRestTest：一种基于LLM和MARL的自动REST API测试工具 

**Authors**: Tyler Stennett, Myeongsoo Kim, Saurabh Sinha, Alessandro Orso  

**Link**: [PDF](https://arxiv.org/pdf/2501.08600)  

**Abstract**: As REST APIs have become widespread in modern web services, comprehensive testing of these APIs has become increasingly crucial. Due to the vast search space consisting of operations, parameters, and parameter values along with their complex dependencies and constraints, current testing tools suffer from low code coverage, leading to suboptimal fault detection. To address this limitation, we present a novel tool, AutoRestTest, which integrates the Semantic Operation Dependency Graph (SODG) with Multi-Agent Reinforcement Learning (MARL) and large language models (LLMs) for effective REST API testing. AutoRestTest determines operation-dependent parameters using the SODG and employs five specialized agents (operation, parameter, value, dependency, and header) to identify dependencies of operations and generate operation sequences, parameter combinations, and values. AutoRestTest provides a command-line interface and continuous telemetry on successful operation count, unique server errors detected, and time elapsed. Upon completion, AutoRestTest generates a detailed report highlighting errors detected and operations exercised. In this paper, we introduce our tool and present preliminary results. 

**Abstract (ZH)**: 随着现代网络服务中REST API变得日益普遍，全面测试这些API的重要性也逐渐提高。由于操作、参数及其参数值存在的庞大搜索空间，以及它们之间复杂的依赖关系和约束条件，当前的测试工具面临着代码覆盖率低的问题，导致故障检测效果不佳。为了解决这一限制，我们提出了一种名为AutoRestTest的新工具，该工具结合了语义操作依赖图（SODG）与多智能体强化学习（MARL）及大规模语言模型（LLMs），以实现有效的REST API测试。AutoRestTest利用SODG确定操作相关的参数，并通过五个专门的智能体（操作、参数、值、依赖关系和头部）来识别操作的依赖关系，并生成操作序列、参数组合和值。AutoRestTest提供命令行界面，并在测试成功次数、检测到的独特服务器错误和所花费时间方面提供持续的遥测数据。测试完成后，AutoRestTest生成一份详细的报告，突出显示检测到的错误和执行的操作。在本文中，我们介绍了该工具并展示了初步结果。 

---