# Infrastructure for AI Agents 

**Title (ZH)**: AI代理的基础设施 

**Authors**: Alan Chan, Kevin Wei, Sihao Huang, Nitarshan Rajkumar, Elija Perrier, Seth Lazar, Gillian K. Hadfield, Markus Anderljung  

**Link**: [PDF](https://arxiv.org/pdf/2501.10114)  

**Abstract**: Increasingly many AI systems can plan and execute interactions in open-ended environments, such as making phone calls or buying online goods. As developers grow the space of tasks that such AI agents can accomplish, we will need tools both to unlock their benefits and manage their risks. Current tools are largely insufficient because they are not designed to shape how agents interact with existing institutions (e.g., legal and economic systems) or actors (e.g., digital service providers, humans, other AI agents). For example, alignment techniques by nature do not assure counterparties that some human will be held accountable when a user instructs an agent to perform an illegal action. To fill this gap, we propose the concept of agent infrastructure: technical systems and shared protocols external to agents that are designed to mediate and influence their interactions with and impacts on their environments. Agent infrastructure comprises both new tools and reconfigurations or extensions of existing tools. For example, to facilitate accountability, protocols that tie users to agents could build upon existing systems for user authentication, such as OpenID. Just as the Internet relies on infrastructure like HTTPS, we argue that agent infrastructure will be similarly indispensable to ecosystems of agents. We identify three functions for agent infrastructure: 1) attributing actions, properties, and other information to specific agents, their users, or other actors; 2) shaping agents' interactions; and 3) detecting and remedying harmful actions from agents. We propose infrastructure that could help achieve each function, explaining use cases, adoption, limitations, and open questions. Making progress on agent infrastructure can prepare society for the adoption of more advanced agents. 

**Abstract (ZH)**: 越来越多的AI系统能够在开放环境中规划和执行交互，例如拨打电话或在线购买商品。随着开发人员扩展此类AI代理能够完成的任务范围，我们需要工具来充分利用这些技术的优势并管理其带来的风险。当前的工具远不足以满足需求，因为它们未设计用于干预代理与现有机构（如法律和经济体系）或参与者（如数字服务提供商、人类及其他AI代理）的互动方式。例如，尽管对齐技术本质上无法保证当用户指示代理执行非法行为时，其行为将被认可并承担责任。为填补这一空白，我们提出了“代理基础设施”的概念：这些技术系统和外部共享协议旨在调解和影响代理与其环境之间的互动及其影响。代理基础设施既包括新工具，也包括现有工具的重组或扩展。例如，为促进可问责性，用户与代理关联的协议可以利用现有的用户身份验证系统（如OpenID）来构建。正如互联网依赖于HTTPS等基础设施一样，我们认为代理基础设施也将成为代理生态系统中不可或缺的部分。我们识别了代理基础设施的三种功能：1) 将代理、其用户或其它参与者的行为、属性及其他信息归因；2) 影响代理的互动；3) 检测并纠正代理的有害行为。我们提出了能够实现这些功能的基础设施，并解释了其应用场景、采纳情况、局限性和开放问题。推进代理基础设施的建设可以为更先进代理的普及做好准备。 

---
# LLM Reasoner and Automated Planner: A new NPC approach 

**Title (ZH)**: 大规模语言模型推理器和自动规划器：一种新的NPC方法 

**Authors**: Israel Puerta-Merino, Jordi Sabater-Mir  

**Link**: [PDF](https://arxiv.org/pdf/2501.10106)  

**Abstract**: In domains requiring intelligent agents to emulate plausible human-like behaviour, such as formative simulations, traditional techniques like behaviour trees encounter significant challenges. Large Language Models (LLMs), despite not always yielding optimal solutions, usually offer plausible and human-like responses to a given problem. In this paper, we exploit this capability and propose a novel architecture that integrates an LLM for decision-making with a classical automated planner that can generate sound plans for that decision. The combination aims to equip an agent with the ability to make decisions in various situations, even if they were not anticipated during the design phase. 

**Abstract (ZH)**: 在需要智能代理模仿人类行为的领域，如形成性模拟中，传统方法如行为树面临重大挑战。尽管大型语言模型（LLMs）通常不能总是提供最优解，但通常能提供合理且类似人类的响应。本文利用这一能力，提出了一种新的架构，该架构将LLM用于决策制定与经典的自动规划器相结合，后者能够生成支持该决策的可信计划。此组合旨在使代理能够在各种情况下做出决策，即使这些情况在设计阶段并未预见。 

---
# ForestProtector: An IoT Architecture Integrating Machine Vision and Deep Reinforcement Learning for Efficient Wildfire Monitoring 

**Title (ZH)**: ForestProtector：一种集成机器视觉和深度强化学习的物联网架构，用于高效的森林火灾监控 

**Authors**: Kenneth Bonilla-Ormachea, Horacio Cuizaga, Edwin Salcedo, Sebastian Castro, Sergio Fernandez-Testa, Misael Mamani  

**Link**: [PDF](https://arxiv.org/pdf/2501.09926)  

**Abstract**: Early detection of forest fires is crucial to minimizing the environmental and socioeconomic damage they cause. Indeed, a fire's duration directly correlates with the difficulty and cost of extinguishing it. For instance, a fire burning for 1 minute might require 1 liter of water to extinguish, while a 2-minute fire could demand 100 liters, and a 10-minute fire might necessitate 1,000 liters. On the other hand, existing fire detection systems based on novel technologies (e.g., remote sensing, PTZ cameras, UAVs) are often expensive and require human intervention, making continuous monitoring of large areas impractical. To address this challenge, this work proposes a low-cost forest fire detection system that utilizes a central gateway device with computer vision capabilities to monitor a 360° field of view for smoke at long distances. A deep reinforcement learning agent enhances surveillance by dynamically controlling the camera's orientation, leveraging real-time sensor data (smoke levels, ambient temperature, and humidity) from distributed IoT devices. This approach enables automated wildfire monitoring across expansive areas while reducing false positives. 

**Abstract (ZH)**: 早期检测森林火灾对于最小化其造成的环境和经济社会损害至关重要。事实上，火灾的持续时间直接关系到扑灭难度和成本。例如，燃烧1分钟的火灾可能只需要1升水来扑灭，而燃烧2分钟的火灾可能需要100升水，10分钟的火灾可能需要1000升水。相比之下，基于新型技术（如遥感、PTZ摄像头、无人机）的现有火灾检测系统通常较为昂贵，并且需要人工干预，这使得对大面积区域进行连续监控变得不切实际。为应对这一挑战，本研究提出了一种低成本的森林火灾检测系统，该系统利用具有计算机视觉能力的中央网关设备，对远距离的360°视野进行监控以识别烟雾。深度强化学习代理通过动态控制摄像头的方向，利用分布式物联网设备提供的实时传感器数据（如烟雾浓度、环境温度和湿度）来增强监控。该方法能够在大面积区域内实现自动化的野火监测，并减少误报。 

---
# Agent4Edu: Generating Learner Response Data by Generative Agents for Intelligent Education Systems 

**Title (ZH)**: Agent4Edu: 生成学习者响应数据的生成型智能代理以支持智能教育系统 

**Authors**: Weibo Gao, Qi Liu, Linan Yue, Fangzhou Yao, Rui Lv, Zheng Zhang, Hao Wang, Zhenya Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.10332)  

**Abstract**: Personalized learning represents a promising educational strategy within intelligent educational systems, aiming to enhance learners' practice efficiency. However, the discrepancy between offline metrics and online performance significantly impedes their progress. To address this challenge, we introduce Agent4Edu, a novel personalized learning simulator leveraging recent advancements in human intelligence through large language models (LLMs). Agent4Edu features LLM-powered generative agents equipped with learner profile, memory, and action modules tailored to personalized learning algorithms. The learner profiles are initialized using real-world response data, capturing practice styles and cognitive factors. Inspired by human psychology theory, the memory module records practice facts and high-level summaries, integrating reflection mechanisms. The action module supports various behaviors, including exercise understanding, analysis, and response generation. Each agent can interact with personalized learning algorithms, such as computerized adaptive testing, enabling a multifaceted evaluation and enhancement of customized services. Through a comprehensive assessment, we explore the strengths and weaknesses of Agent4Edu, emphasizing the consistency and discrepancies in responses between agents and human learners. The code, data, and appendix are publicly available at this https URL. 

**Abstract (ZH)**: 个性化学习在智能教育资源系统中代表了一种有前景的教学策略，旨在提高学习者的学习效率。然而，离线指标与在线表现之间的差异严重阻碍了其进步。为解决这一挑战，我们介绍了Agent4Edu，这是一种利用大型语言模型（LLMs）近期在人类智能方面的进展的新型个性化学习模拟器。Agent4Edu 配备了由学习者概况、记忆和行为模块支持的LLM驱动生成代理，这些模块专门针对个性化学习算法进行了定制。学习者概况使用实际反应数据进行初始化，捕捉了学习者的实践风格和认知因素。该记忆模块记录了实践事实和高阶总结，并整合了反思机制。行为模块支持各种行为，包括理解练习、分析和生成响应。每个代理都可以与个性化学习算法（如计算机化自适应测试）进行交互，从而实现对定制服务的多维评估和增强。通过全面评估，我们探讨了Agent4Edu的优势和不足，强调了代理和人类学习者之间反应的一致性和差异性。相关代码、数据和附录可在以下网址公开访问：[此链接](此链接)。 

---
# Universal Actions for Enhanced Embodied Foundation Models 

**Title (ZH)**: 增强型体化基础模型的通用行动方案 

**Authors**: Jinliang Zheng, Jianxiong Li, Dongxiu Liu, Yinan Zheng, Zhihao Wang, Zhonghong Ou, Yu Liu, Jingjing Liu, Ya-Qin Zhang, Xianyuan Zhan  

**Link**: [PDF](https://arxiv.org/pdf/2501.10105)  

**Abstract**: Training on diverse, internet-scale data is a key factor in the success of recent large foundation models. Yet, using the same recipe for building embodied agents has faced noticeable difficulties. Despite the availability of many crowd-sourced embodied datasets, their action spaces often exhibit significant heterogeneity due to distinct physical embodiment and control interfaces for different robots, causing substantial challenges in developing embodied foundation models using cross-domain data. In this paper, we introduce UniAct, a new embodied foundation modeling framework operating in a tokenized Universal Action Space. Our learned universal actions capture the generic atomic behaviors across diverse robots by exploiting their shared structural features, and enable enhanced cross-domain data utilization and cross-embodiment generalizations by eliminating the notorious heterogeneity. The universal actions can be efficiently translated back to heterogeneous actionable commands by simply adding embodiment-specific details, from which fast adaptation to new robots becomes simple and straightforward. Our 0.5B instantiation of UniAct outperforms 14X larger SOTA embodied foundation models in extensive evaluations on various real-world and simulation robots, showcasing exceptional cross-embodiment control and adaptation capability, highlighting the crucial benefit of adopting universal actions. Project page: this https URL 

**Abstract (ZH)**: 在大规模互联网数据上进行训练是近期大型基础模型取得成功的关键因素。然而，使用相同的方法构建具身智能体遇到了明显的困难。尽管有许多开源的具身数据集，但由于不同机器人具有独特的物理表现形式和控制接口，其动作空间往往表现出显著的异质性，这在利用跨域数据开发具身基础模型时带来了巨大挑战。本文介绍了一种新的具身基础建模框架——UniAct，它在标记化的统一动作空间中运行。我们的学习到的通用动作捕获了不同机器人之间的一般原子行为，并通过消除 notorious 的异质性，增强了跨域数据利用和跨载体泛化的能力。可以通过简单地添加与具体机器人相关的细节，将通用动作高效地转换回异质的可执行命令，从而使得对新机器人的快速适应变得简单直接。我们的 UniAct 实例在各种真实世界和仿真机器人上的广泛评估中表现出色，超过了比其大14倍的现有最佳具身基础模型，展示了卓越的跨载体控制和适应能力，突显了采用通用动作的重要性。项目页面：[这里](this https URL) 

---
# ASTRA: A Scene-aware TRAnsformer-based model for trajectory prediction 

**Title (ZH)**: ASTRA：一种场景意识的 Transformer 基础轨迹预测模型 

**Authors**: Izzeddin Teeti, Aniket Thomas, Munish Monga, Sachin Kumar, Uddeshya Singh, Andrew Bradley, Biplab Banerjee, Fabio Cuzzolin  

**Link**: [PDF](https://arxiv.org/pdf/2501.09878)  

**Abstract**: We present ASTRA (A} Scene-aware TRAnsformer-based model for trajectory prediction), a light-weight pedestrian trajectory forecasting model that integrates the scene context, spatial dynamics, social inter-agent interactions and temporal progressions for precise forecasting. We utilised a U-Net-based feature extractor, via its latent vector representation, to capture scene representations and a graph-aware transformer encoder for capturing social interactions. These components are integrated to learn an agent-scene aware embedding, enabling the model to learn spatial dynamics and forecast the future trajectory of pedestrians. The model is designed to produce both deterministic and stochastic outcomes, with the stochastic predictions being generated by incorporating a Conditional Variational Auto-Encoder (CVAE). ASTRA also proposes a simple yet effective weighted penalty loss function, which helps to yield predictions that outperform a wide array of state-of-the-art deterministic and generative models. ASTRA demonstrates an average improvement of 27%/10% in deterministic/stochastic settings on the ETH-UCY dataset, and 26% improvement on the PIE dataset, respectively, along with seven times fewer parameters than the existing state-of-the-art model (see Figure 1). Additionally, the model's versatility allows it to generalize across different perspectives, such as Bird's Eye View (BEV) and Ego-Vehicle View (EVV). 

**Abstract (ZH)**: 我们提出了ASTRA（一种场景感知的基于Transformer的轨迹预测模型），该模型是一个轻量级的人行轨迹预测模型，能够整合场景上下文、空间动力学、社交交互以及时间进程，以实现精确的预测。我们使用了基于U-Net的特征提取器，并通过其潜在向量表示来捕获场景感知特征，并使用图感知的Transformer编码器来捕获社交交互。这些组件被集成以学习代理-场景感知嵌入，使得模型能够学习空间动力学并预测行人的未来轨迹。该模型旨在生成确定性和随机性两种结果，随机性预测通过引入条件变分自编码器（CVAE）进行生成。ASTRA还提出了一种简单而有效的加权惩罚损失函数，该函数有助于生成优于多种最先进的确定性生成模型的预测结果。在ETH-UCY数据集的确定性设置中，ASTRA的性能提高了27%，在随机设置中提高了10%；在PIE数据集上，性能提高了26%。此外，该模型的通用性使其能够在不同的视角（如鸟瞰图（BEV）和以车为参照的视角（EVV））之间进行扩展和泛化，且参数量仅为现有最先进的模型的七分之一（参见图1）。 

---
# PaSa: An LLM Agent for Comprehensive Academic Paper Search 

**Title (ZH)**: PaSa：一种全面学术论文搜索的大型语言模型代理 

**Authors**: Yichen He, Guanhua Huang, Peiyuan Feng, Yuan Lin, Yuchen Zhang, Hang Li, Weinan E  

**Link**: [PDF](https://arxiv.org/pdf/2501.10120)  

**Abstract**: We introduce PaSa, an advanced Paper Search agent powered by large language models. PaSa can autonomously make a series of decisions, including invoking search tools, reading papers, and selecting relevant references, to ultimately obtain comprehensive and accurate results for complex scholarly queries. We optimize PaSa using reinforcement learning with a synthetic dataset, AutoScholarQuery, which includes 35k fine-grained academic queries and corresponding papers sourced from top-tier AI conference publications. Additionally, we develop RealScholarQuery, a benchmark collecting real-world academic queries to assess PaSa performance in more realistic scenarios. Despite being trained on synthetic data, PaSa significantly outperforms existing baselines on RealScholarQuery, including Google, Google Scholar, Google with GPT-4 for paraphrased queries, chatGPT (search-enabled GPT-4o), GPT-o1, and PaSa-GPT-4o (PaSa implemented by prompting GPT-4o). Notably, PaSa-7B surpasses the best Google-based baseline, Google with GPT-4o, by 37.78% in recall@20 and 39.90% in recall@50. It also exceeds PaSa-GPT-4o by 30.36% in recall and 4.25% in precision. Model, datasets, and code are available at this https URL. 

**Abstract (ZH)**: 我们介绍了PaSa，这是一种由大规模语言模型驱动的高级论文搜索代理。PaSa可以自主作出一系列决策，包括调用搜索工具、阅读论文和选择相关参考文献，最终为复杂的学术查询提供全面而准确的结果。我们使用强化学习并利用一个合成数据集AutoScholarQuery来优化PaSa，该数据集包含了35,000个精细的学术查询及其相应的论文，这些论文来源于顶级人工智能会议的出版物。此外，我们还开发了RealScholarQuery基准数据集，收集了真实世界的学术查询，以更现实的场景评估PaSa的表现。尽管PaSa是基于合成数据进行训练的，但它在RealScholarQuery上的表现显著优于现有基线，包括Google、Google Scholar、使用GPT-4进行改写的Google、chatGPT（搜索功能增强的GPT-4o）、GPT-o1和PaSa-GPT-4o（基于GPT-4o实现的PaSa）。值得注意的是，PaSa-7B在召回率@20上比基于Google的最佳基线（Google与GPT-4结合）高出37.78%，在召回率@50上高出39.90%。此外，它的召回率超过了PaSa-GPT-4o 30.36%，而精确率高出4.25%。相关模型、数据集和代码可在以下网址获取。 

---
# Agent-as-Judge for Factual Summarization of Long Narratives 

**Title (ZH)**: 将下面的论文内容或标题翻译成中文，并确保符合学术规范：

**Agent-as-Judge for Factual Summarization of Long Narratives**

**作为裁判的代理：长叙事事实总结**

在这个翻译中，“Agent”是指执行某种任务或决策的实体，“as”在此处作为介词，表明角色或功能的转变，“Judge”在这里可以理解为“裁判”，指的是对事物进行判断的角色。因此，“Agent-as-Judge”可以翻译为“作为裁判的代理”。整体标题翻译时考虑到学术规范和表达的准确性，确保意思清晰、专业。 

**Authors**: Yeonseok Jeong, Minsoo Kim, Seung-won Hwang, Byung-Hak Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.09993)  

**Abstract**: Large Language Models (LLMs) have demonstrated near-human performance in summarization tasks based on traditional metrics such as ROUGE and BERTScore. However, these metrics do not adequately capture critical aspects of summarization quality, such as factual accuracy, particularly for long narratives (>100K tokens). Recent advances, such as LLM-as-a-Judge, address the limitations of metrics based on lexical similarity but still exhibit factual inconsistencies, especially in understanding character relationships and states. In this work, we introduce NarrativeFactScore, a novel "Agent-as-a-Judge" framework for evaluating and refining summaries. By leveraging a Character Knowledge Graph (CKG) extracted from input and generated summaries, NarrativeFactScore assesses the factual consistency and provides actionable guidance for refinement, such as identifying missing or erroneous facts. We demonstrate the effectiveness of NarrativeFactScore through a detailed workflow illustration and extensive validation on widely adopted benchmarks, achieving superior performance compared to competitive methods. Our results highlight the potential of agent-driven evaluation systems to improve the factual reliability of LLM-generated summaries. 

**Abstract (ZH)**: 大语言模型（LLMs）在传统评测指标如ROUGE和BERTScore的基础上，在摘要任务上已经展现出了接近人类的性能。然而，这些指标并未充分捕捉到摘要质量的关键方面，特别是对于长篇叙述（超过10万tokens）中的事实准确性。最近的进步，如LLM-as-a-Judge，解决了基于词义相似性的指标的局限性，但仍存在事实不一致的问题，特别是在理解角色关系和状态方面。在这项工作中，我们引入了NarrativeFactScore框架，这是一种新的“Agent-as-a-Judge”评估和优化摘要的方法。通过利用从输入和生成的摘要中提取的Character Knowledge Graph（CKG），NarrativeFactScore评估了事实一致性，并提供了改进的实用指导，如识别缺失或错误的事实。我们通过详尽的工作流程说明和广泛验证，在广泛使用的基准数据集上展示了NarrativeFactScore的有效性，其性能优于竞争方法。我们的结果显示，基于代理的评估系统有提高LLM生成摘要的事实可靠性的潜力。 

---