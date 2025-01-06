# Rethinking Relation Extraction: Beyond Shortcuts to Generalization with a Debiased Benchmark 

**Title (ZH)**: 重新思考关系提取：超越捷径，通过去偏差基准实现泛化的探索 

**Authors**: Liang He, Yougang Chu, Zhen Wu, Jianbing Zhang, Xinyu Dai, Jiajun Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01349)  

**Abstract**: Benchmarks are crucial for evaluating machine learning algorithm performance, facilitating comparison and identifying superior solutions. However, biases within datasets can lead models to learn shortcut patterns, resulting in inaccurate assessments and hindering real-world applicability. This paper addresses the issue of entity bias in relation extraction tasks, where models tend to rely on entity mentions rather than context. We propose a debiased relation extraction benchmark DREB that breaks the pseudo-correlation between entity mentions and relation types through entity replacement. DREB utilizes Bias Evaluator and PPL Evaluator to ensure low bias and high naturalness, providing a reliable and accurate assessment of model generalization in entity bias scenarios. To establish a new baseline on DREB, we introduce MixDebias, a debiasing method combining data-level and model training-level techniques. MixDebias effectively improves model performance on DREB while maintaining performance on the original dataset. Extensive experiments demonstrate the effectiveness and robustness of MixDebias compared to existing methods, highlighting its potential for improving the generalization ability of relation extraction models. We will release DREB and MixDebias publicly. 

**Abstract (ZH)**: 基准数据对于评估机器学习算法的性能至关重要，有助于比较并识别出更优的解决方案。然而，数据集中的偏差可能导致模型学习捷径模式，从而导致不准确的评估并阻碍其在实际中的应用。本文针对提取任务中的实体偏差问题，提出了一种名为DREB的去偏基准数据集，通过实体替换打破了实体提及与关系类型之间的伪相关性。DREB利用Bias Evaluator和PPL Evaluator确保低偏差和高自然度，提供了一个在实体偏差场景下对模型泛化能力进行可靠和准确评估的平台。为了在DREB上建立新的基线，我们提出了MixDebias，这是一种结合了数据层面和模型训练层面的技术的去偏方法。MixDebias在DREB上有效提升了模型性能，同时保持了在原始数据集上的性能表现。广泛的实验表明，与现有方法相比，MixDebias在有效性和稳健性方面更具优势，并突显了其提高关系提取模型泛化能力的潜力。我们将公开发布DREB和MixDebias。 

---
# DeepFilter: An Instrumental Baseline for Accurate and Efficient Process Monitoring 

**Title (ZH)**: DeepFilter：一种准确高效的过程监控基准方法 

**Authors**: Hao Wang, Zhichao Chen, Licheng Pan, Xiaoyu Jiang, Yichen Song, Qunshan He, Xinggao Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01342)  

**Abstract**: Effective process monitoring is increasingly vital in industrial automation for ensuring operational safety, necessitating both high accuracy and efficiency. Although Transformers have demonstrated success in various fields, their canonical form based on the self-attention mechanism is inadequate for process monitoring due to two primary limitations: (1) the step-wise correlations captured by self-attention mechanism are difficult to capture discriminative patterns in monitoring logs due to the lacking semantics of each step, thus compromising accuracy; (2) the quadratic computational complexity of self-attention hampers efficiency. To address these issues, we propose DeepFilter, a Transformer-style framework for process monitoring. The core innovation is an efficient filtering layer that excel capturing long-term and periodic patterns with reduced complexity. Equipping with the global filtering layer, DeepFilter enhances both accuracy and efficiency, meeting the stringent demands of process monitoring. Experimental results on real-world process monitoring datasets validate DeepFilter's superiority in terms of accuracy and efficiency compared to existing state-of-the-art models. 

**Abstract (ZH)**: 有效的过程监控在工业自动化中变得越来越重要，对于确保操作安全至关重要，这要求监控系统兼具高精度和高效率。虽然Transformer已经在多个领域取得了成功，但其基于自我注意力机制的标准形式在过程监控中存在两个主要局限性：（1）自我注意力机制捕捉的步骤间相关性难以在过程中识别出有区分性的模式，因为每一个步骤的语义信息不足，从而影响了精度；（2）自我注意力机制的平方时间复杂度限制了其效率。为了解决这些问题，我们提出了一种名为DeepFilter的Transformer风格框架，其核心创新在于一种高效的筛选层能够以较低的复杂度捕捉长周期和周期性模式。通过结合全局筛选层，DeepFilter在提高精度和效率方面表现出色，满足了过程监控的严格要求。实验证明，DeepFilter在真实世界的过程监控数据集上的精度和效率均优于现有最先进的模型。 

---
# Change Detection-Based Procedures for Piecewise Stationary MABs: A Modular Approach 

**Title (ZH)**: 基于变化检测的Piecewise Stationary MABs 处理程序：一种模块化方法 

**Authors**: Yu-Han Huang, Argyrios Gerogiannis, Subhonmesh Bose, Venugopal V. Veeravalli  

**Link**: [PDF](https://arxiv.org/pdf/2501.01291)  

**Abstract**: Conventional Multi-Armed Bandit (MAB) algorithms are designed for stationary environments, where the reward distributions associated with the arms do not change with time. In many applications, however, the environment is more accurately modeled as being nonstationary. In this work, piecewise stationary MAB (PS-MAB) environments are investigated, in which the reward distributions associated with a subset of the arms change at some change-points and remain stationary between change-points. Our focus is on the asymptotic analysis of PS-MABs, for which practical algorithms based on change detection (CD) have been previously proposed. Our goal is to modularize the design and analysis of such CD-based Bandit (CDB) procedures. To this end, we identify the requirements for stationary bandit algorithms and change detectors in a CDB procedure that are needed for the modularization. We assume that the rewards are sub-Gaussian. Under this assumption and a condition on the separation of the change-points, we show that the analysis of CDB procedures can indeed be modularized, so that regret bounds can be obtained in a unified manner for various combinations of change detectors and bandit algorithms. Through this analysis, we develop new modular CDB procedures that are order-optimal. We compare the performance of our modular CDB procedures with various other methods in simulations. 

**Abstract (ZH)**: 传统的多臂bandit（MAB）算法设计用于静态环境，其中与臂相关联的奖励分布不会随时间变化。然而，在许多应用场景中，环境更为准确地被视为非静态的。在这项工作中，我们研究了分段静态MAB（PS-MAB）环境，在这些环境中，一部分臂的奖励分布会在某些变化点发生改变，而在变化点之间保持不变。我们的重点是PS-MAB的渐近分析，在这种环境下，基于变化检测（CD）的实用算法已被之前提出。我们的目标是模块化这样的基于变化检测的Bandit（CDB）过程的设计和分析。为此，我们确定了CDB过程中所需的状态稳定bandit算法和变化检测器的要求，这些要求对于模块化至关重要。我们假设奖励是亚高斯的。在这一假设和变化点分离条件的条件下，我们证明了CDB过程的分析确实可以模块化，从而可以以统一的方式为各种变化检测器和bandit算法的组合获得后悔界限。通过这种分析，我们开发了新的模块化CDB过程，并且这些过程在有序意义下是最优的。我们通过仿真比较了我们的模块化CDB过程与其他方法的性能。 

---
# CultureVLM: Characterizing and Improving Cultural Understanding of Vision-Language Models for over 100 Countries 

**Title (ZH)**: CultureVLM: 表征和提升视觉语言模型在100多个国家的文化理解能力 

**Authors**: Shudong Liu, Yiqiao Jin, Cheng Li, Derek F. Wong, Qingsong Wen, Lichao Sun, Haipeng Chen, Xing Xie, Jindong Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01282)  

**Abstract**: Vision-language models (VLMs) have advanced human-AI interaction but struggle with cultural understanding, often misinterpreting symbols, gestures, and artifacts due to biases in predominantly Western-centric training data. In this paper, we construct CultureVerse, a large-scale multimodal benchmark covering 19, 682 cultural concepts, 188 countries/regions, 15 cultural concepts, and 3 question types, with the aim of characterizing and improving VLMs' multicultural understanding capabilities. Then, we propose CultureVLM, a series of VLMs fine-tuned on our dataset to achieve significant performance improvement in cultural understanding. Our evaluation of 16 models reveals significant disparities, with a stronger performance in Western concepts and weaker results in African and Asian contexts. Fine-tuning on our CultureVerse enhances cultural perception, demonstrating cross-cultural, cross-continent, and cross-dataset generalization without sacrificing performance on models' general VLM benchmarks. We further present insights on cultural generalization and forgetting. We hope that this work could lay the foundation for more equitable and culturally aware multimodal AI systems. 

**Abstract (ZH)**: 视觉语言模型（VLMs）在促进人机交互方面取得了进展，但在文化理解方面存在困难，常因训练数据偏向于西方文化而误解符号、手势和文物。本论文旨在构建CultureVerse，一个大规模多模态基准，涵盖19,682个文化概念、188个国家/地区、15个文化概念和3种问题类型，旨在表征并提升VLMs的多文化理解能力。随后，我们提出CultureVLM，一系列在我们的数据集上进行微调的VLMs，以显著提高其文化理解能力。对16种模型的评价结果表明，这些模型在西方概念理解上表现出色，但在非洲和亚洲背景下的表现较弱。在我们的CultureVerse上进行微调可以提升文化感知能力，展示了跨文化、跨洲际和跨数据集的一般化能力，而不会牺牲模型在通用VLM基准测试中的表现。我们进一步提出了关于文化一般化和遗忘的洞见。我们希望这项工作能够为更加公正和文化意识强烈的多模态AI系统的构建奠定基础。 

---
# A redescription mining framework for post-hoc explaining and relating deep learning models 

**Title (ZH)**: 一种用于后验解释和关联深度学习模型的重描述挖掘框架 

**Authors**: Matej Mihelčić, Ivan Grubišić, Miha Keber  

**Link**: [PDF](https://arxiv.org/pdf/2501.01209)  

**Abstract**: Deep learning models (DLMs) achieve increasingly high performance both on structured and unstructured data. They significantly extended applicability of machine learning to various domains. Their success in making predictions, detecting patterns and generating new data made significant impact on science and industry. Despite these accomplishments, DLMs are difficult to explain because of their enormous size. In this work, we propose a novel framework for post-hoc explaining and relating DLMs using redescriptions. The framework allows cohort analysis of arbitrary DLMs by identifying statistically significant redescriptions of neuron activations. It allows coupling neurons to a set of target labels or sets of descriptive attributes, relating layers within a single DLM or associating different DLMs. The proposed framework is independent of the artificial neural network architecture and can work with more complex target labels (e.g. multi-label or multi-target scenario). Additionally, it can emulate both pedagogical and decompositional approach to rule extraction. The aforementioned properties of the proposed framework can increase explainability and interpretability of arbitrary DLMs by providing different information compared to existing explainable-AI approaches. 

**Abstract (ZH)**: 深度学习模型（DLMs）在结构化和非结构化数据上的性能不断提高，并显著扩展了机器学习在各个领域的应用范围。它们在预测、模式检测和数据生成方面的成功对科学和工业产生了重大影响。尽管取得了这些成就，但由于其庞大的规模，DLMs难以解释。在此项工作中，我们提出了一种新的框架，用于事后解释和关联DLMs，该框架通过识别神经元激活的统计显著重新描述来实现任意DLM的群体分析。它允许将神经元与一组目标标签或描述性属性集关联起来，可以将层内关联或不同DLM进行关联。所提出的框架与人工神经网络架构无关，并且可以处理更复杂的目标标签（例如多标签或多目标场景）。此外，它还可以模拟规则提取的教育性和分解性方法。上述所提出的框架的特性可以通过提供与现有可解释AI方法不同的信息来增加任意DLM的可解释性和可理解性。 

---
# A3: Android Agent Arena for Mobile GUI Agents 

**Title (ZH)**: A3: Android代理竞技场——用于移动GUI代理的研究 

**Authors**: Yuxiang Chai, Hanhao Li, Jiayu Zhang, Liang Liu, Guozhi Wang, Shuai Ren, Siyuan Huang, Hongsheng Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.01149)  

**Abstract**: AI agents have become increasingly prevalent in recent years, driven by significant advancements in the field of large language models (LLMs). Mobile GUI agents, a subset of AI agents, are designed to autonomously perform tasks on mobile devices. While numerous studies have introduced agents, datasets, and benchmarks to advance mobile GUI agent research, many existing datasets focus on static frame evaluations and fail to provide a comprehensive platform for assessing performance on real-world, in-the-wild tasks. To address this gap, we present Android Agent Arena (A3), a novel evaluation platform. Unlike existing in-the-wild systems, A3 offers: (1) meaningful and practical tasks, such as real-time online information retrieval and operational instructions; (2) a larger, more flexible action space, enabling compatibility with agents trained on any dataset; and (3) automated business-level LLM-based evaluation process. A3 includes 21 widely used general third-party apps and 201 tasks representative of common user scenarios, providing a robust foundation for evaluating mobile GUI agents in real-world situations and a new autonomous evaluation process for less human labor and coding expertise. The project is available at \url{this https URL}. 

**Abstract (ZH)**: 近年来，随着大型语言模型（LLMs）领域的显著进步，AI代理的使用越来越普遍。移动GUI代理是AI代理的一个子类，旨在自主在移动设备上执行任务。尽管许多研究已经介绍了代理、数据集和基准来推动移动GUI代理研究，但现有许多数据集主要关注静态帧评估，未能提供一个全面的平台来评估在真实世界、自然环境中的表现。为了弥补这一差距，我们提出Android Agent Arena (A3)，一个新型的评估平台。与现有的自然环境系统不同，A3提供：（1）有意义且实用的任务，如实时在线信息检索和操作指令；（2）更大的、更具灵活性的动作空间，使任何数据集训练的代理都能兼容；（3）自动化的企业级基于LLM的评估流程。A3包括21个广泛使用的第三方通用应用程序和201个代表常见用户场景的任务，为评估移动GUI代理提供了坚实的基础，并提供了一种新的自动化评估过程，以减少人力和编程专业知识的投入。该项目可以在 \url{this https URL} 获取。 

---
# Beyond Text: Implementing Multimodal Large Language Model-Powered Multi-Agent Systems Using a No-Code Platform 

**Title (ZH)**: 超越文本：使用无代码平台实现基于大型语言模型的多模态多代理系统 

**Authors**: Cheonsu Jeong  

**Link**: [PDF](https://arxiv.org/pdf/2501.00750)  

**Abstract**: This study proposes the design and implementation of a multimodal LLM-based Multi-Agent System (MAS) leveraging a No-Code platform to address the practical constraints and significant entry barriers associated with AI adoption in enterprises. Advanced AI technologies, such as Large Language Models (LLMs), often pose challenges due to their technical complexity and high implementation costs, making them difficult for many organizations to adopt. To overcome these limitations, this research develops a No-Code-based Multi-Agent System designed to enable users without programming knowledge to easily build and manage AI systems. The study examines various use cases to validate the applicability of AI in business processes, including code generation from image-based notes, Advanced RAG-based question-answering systems, text-based image generation, and video generation using images and prompts. These systems lower the barriers to AI adoption, empowering not only professional developers but also general users to harness AI for significantly improved productivity and efficiency. By demonstrating the scalability and accessibility of No-Code platforms, this study advances the democratization of AI technologies within enterprises and validates the practical applicability of Multi-Agent Systems, ultimately contributing to the widespread adoption of AI across various industries. 

**Abstract (ZH)**: 本研究提出了一种利用无代码平台设计和实现基于多模态大型语言模型（LLM）的多代理系统（MAS），以解决企业在采用人工智能时所面临的实际限制和显著进入壁垒。先进的AI技术，如大型语言模型（LLMs），往往由于其技术复杂性和高昂的实施成本而带来挑战，使得许多组织难以采用。为克服这些限制，本研究开发了一种基于无代码的多代理系统，旨在使不具备编程知识的用户能够轻松构建和管理AI系统。研究探讨了多种应用场景来验证AI在业务流程中的适用性，包括基于图像笔记的代码生成、基于高级检索与生成（RAG）的问题回答系统、基于文本的图像生成，以及使用图像和提示生成视频系统。这些系统降低了AI的采用门槛，不仅赋能专业的开发人员，还赋能普通用户利用AI来显著提高生产力和效率。通过展示无代码平台的扩展性和可访问性，本研究推动了企业内部AI技术的民主化，并验证了多代理系统的实际适用性，最终促进了AI在各行业的广泛采用。 

---
# Grade Inflation in Generative Models 

**Title (ZH)**: 生成模型中的成绩膨胀问题 

**Authors**: Phuc Nguyen, Miao Li, Alexandra Morgan, Rima Arnaout, Ramy Arnaout  

**Link**: [PDF](https://arxiv.org/pdf/2501.00664)  

**Abstract**: Generative models hold great potential, but only if one can trust the evaluation of the data they generate. We show that many commonly used quality scores for comparing two-dimensional distributions of synthetic vs. ground-truth data give better results than they should, a phenomenon we call the "grade inflation problem." We show that the correlation score, Jaccard score, earth-mover's score, and Kullback-Leibler (relative-entropy) score all suffer grade inflation. We propose that any score that values all datapoints equally, as these do, will also exhibit grade inflation; we refer to such scores as "equipoint" scores. We introduce the concept of "equidensity" scores, and present the Eden score, to our knowledge the first example of such a score. We found that Eden avoids grade inflation and agrees better with human perception of goodness-of-fit than the equipoint scores above. We propose that any reasonable equidensity score will avoid grade inflation. We identify a connection between equidensity scores and Rényi entropy of negative order. We conclude that equidensity scores are likely to outperform equipoint scores for generative models, and for comparing low-dimensional distributions more generally. 

**Abstract (ZH)**: 生成模型具有巨大潜力，但前提是必须能够信任它们生成的数据评估。我们发现，许多常用于比较合成数据与真实数据二维分布的质量评分比它们应有的水平要高，我们称之为“分数膨胀问题”。我们证明了相关分数、Jaccard分数、Wasserstein分数以及Kullback-Leibler（相对熵）分数都存在分数膨胀现象。我们提出，任何像这些评分方法那样对所有数据点给予相同价值的评分都会出现分数膨胀；我们将此类评分称为“等点”评分。我们引入了“等密度”评分的概念，并提出了埃登分数（Eden score），据我们所知，这是首个此类评分的实例。我们发现，埃登分数避免了分数膨胀，并且在评估贴合度方面比上述等点评分更符合人类的感知。我们提出，任何合理的等密度评分都能避免分数膨胀。我们发现等密度评分与负序Rényi熵之间存在联系。我们得出结论，等密度评分可能在生成模型中表现优于等点评分，并且在更广泛的低维分布比较中也是如此。 

---
# MCP-Solver: Integrating Language Models with Constraint Programming Systems 

**Title (ZH)**: MCP-Solver：将语言模型与约束编程系统集成 

**Authors**: Stefan Szeider  

**Link**: [PDF](https://arxiv.org/pdf/2501.00539)  

**Abstract**: While Large Language Models (LLMs) perform exceptionally well at natural language tasks, they often struggle with precise formal reasoning and the rigorous specification of problems. We present MCP-Solver, a prototype implementation of the Model Context Protocol that demonstrates the potential for systematic integration between LLMs and constraint programming systems. Our implementation provides interfaces for the creation, editing, and validation of a constraint model. Through an item-based editing approach with integrated validation, the system ensures model consistency at every modification step and enables structured iterative refinement. The system handles concurrent solving sessions and maintains a persistent knowledge base of modeling insights. Initial experiments suggest that this integration can effectively combine LLMs' natural language understanding with constraint-solving capabilities. Our open-source implementation is proof of concept for integrating formal reasoning systems with LLMs through standardized protocols. While further research is needed to establish comprehensive formal guarantees, this work takes a first step toward principled integration of natural language processing with constraint-based reasoning. 

**Abstract (ZH)**: 尽管大规模语言模型（LLMs）在自然语言任务上表现出色，但它们往往在精确的形式推理和问题的严格规范上存在困难。我们提出了一种模型上下文协议（MCP-Solver）的原型实现，展示了LLMs与约束编程系统系统化集成的潜力。我们的实现提供了创建、编辑和验证约束模型的接口。通过基于项目的编辑方法并集成验证，系统在每次修改步骤中确保模型一致性，并支持结构化的迭代细化。系统能够处理并发求解会话，并保持一个持久的知识库，记录建模洞察。初步实验表明，这种集成能够有效结合LLMs的自然语言理解和求解约束问题的能力。我们开源的实现证明了通过标准化协议集成正式推理系统与LLMs的可能性。尽管还需要进一步的研究来建立全面的形式保证，但这项工作为自然语言处理与基于约束的推理的原理化集成迈出了第一步。 

---
# Extending XReason: Formal Explanations for Adversarial Detection 

**Title (ZH)**: 扩展 XReason：对抗检测的形式解释 

**Authors**: Amira Jemaa, Adnan Rashid, Sofiene Tahar  

**Link**: [PDF](https://arxiv.org/pdf/2501.00537)  

**Abstract**: Explainable Artificial Intelligence (XAI) plays an important role in improving the transparency and reliability of complex machine learning models, especially in critical domains such as cybersecurity. Despite the prevalence of heuristic interpretation methods such as SHAP and LIME, these techniques often lack formal guarantees and may produce inconsistent local explanations. To fulfill this need, few tools have emerged that use formal methods to provide formal explanations. Among these, XReason uses a SAT solver to generate formal instance-level explanation for XGBoost models. In this paper, we extend the XReason tool to support LightGBM models as well as class-level explanations. Additionally, we implement a mechanism to generate and detect adversarial examples in XReason. We evaluate the efficiency and accuracy of our approach on the CICIDS-2017 dataset, a widely used benchmark for detecting network attacks. 

**Abstract (ZH)**: 可解释的人工智能（XAI）在提高复杂机器学习模型的透明度和可靠性方面发挥着重要作用，尤其是在网络安全等关键领域。尽管存在诸如SHAP和LIME等启发式解释方法的广泛使用，但这些技术通常缺乏形式上的保证，并且可能会产生不一致的局部解释。为了解决这一需求，少数工具采用了形式化方法来提供形式化解释。其中，XReason使用SAT求解器为XGBoost模型生成形式化实例级解释。在这篇论文中，我们将XReason工具拓展，使其不仅支持LightGBM模型，还支持类级解释。此外，我们实现了一种机制来在XReason中生成和检测对抗样本。我们通过对CICIDS-2017数据集进行评估，验证了我们方法的效率和准确性，而CICIDS-2017数据集是一个广泛使用的网络攻击检测基准。 

---
# Efficient support ticket resolution using Knowledge Graphs 

**Title (ZH)**: 使用知识图谱实现高效的技术支持票务解决 

**Authors**: Sherwin Varghese, James Tian  

**Link**: [PDF](https://arxiv.org/pdf/2501.00461)  

**Abstract**: A review of over 160,000 customer cases indicates that about 90% of time is spent by the product support for solving around 10% of subset of tickets where a trivial solution may not exist. Many of these challenging cases require the support of several engineers working together within a "swarm", and some also need to go to development support as bugs. These challenging customer issues represent a major opportunity for machine learning and knowledge graph that identifies the ideal engineer / group of engineers(swarm) that can best address the solution, reducing the wait times for the customer. The concrete ML task we consider here is a learning-to-rank(LTR) task that given an incident and a set of engineers currently assigned to the incident (which might be the empty set in the non-swarming context), produce a ranked list of engineers best fit to help resolve that incident. To calculate the rankings, we may consider a wide variety of input features including the incident description provided by the customer, the affected component(s), engineer ratings of their expertise, knowledge base article text written by engineers, response to customer text written by engineers, and historic swarming data. The central hypothesis test is that by including a holistic set of contextual data around which cases an engineer has solved, we can significantly improve the LTR algorithm over benchmark models. The article proposes a novel approach of modelling Knowledge Graph embeddings from multiple data sources, including the swarm information. The results obtained proves that by incorporating this additional context, we can improve the recommendations significantly over traditional machine learning methods like TF-IDF. 

**Abstract (ZH)**: 对超过16万个客户案例的回顾表明，产品支持在解决约10%的子集案例时花费了大约90%的时间，而这些子集案例可能没有显而易见的解决方案。许多具有挑战性的案例需要多位工程师共同协作（称为“蜂群”），并且有些还需要寻求开发支持来解决代码中的缺陷。这些具有挑战性的客户问题为机器学习和知识图谱提供了一个重大机会，这些工具能够识别出最适合解决这些问题的理想工程师或工程师团队（蜂群），从而减少客户等待时间。我们在此考虑的具体机器学习任务是基于排序的机器学习（Learning-to-Rank, LTR），给定一个事件和当前分配给该事件的一组工程师（在非蜂群模式下可能是空集），生成一个最适合解决该事件的工程师排序列表。为了计算排名，我们可能考虑多种输入特征，包括客户提供的事件描述、受影响的组件、工程师的专业评级、工程师编写的知识库文章文本、工程师回复客户的文本，以及历史蜂群数据。中心假设测试是，通过包含工程师解决案例的完整上下文数据，我们可以显著提高排序算法的效果，超过基准模型。本文提出了一种新的方法，即从多个数据源（包括蜂群信息）建模知识图谱嵌入。实验结果证明，通过整合这些额外的上下文信息，可以显著提高推荐效果，超越传统的机器学习方法如TF-IDF。 

---
# Knowledge-aware equation discovery with automated background knowledge extraction 

**Title (ZH)**: 基于知识aware的方程发现与自动化背景知识提取 

**Authors**: Elizaveta Ivanchik, Alexander Hvatov  

**Link**: [PDF](https://arxiv.org/pdf/2501.00444)  

**Abstract**: In differential equation discovery algorithms, a priori expert knowledge is mainly used implicitly to constrain the form of the expected equation, making it impossible for the algorithm to truly discover equations. Instead, most differential equation discovery algorithms try to recover the coefficients for a known structure. In this paper, we describe an algorithm that allows the discovery of unknown equations using automatically or manually extracted background knowledge. Instead of imposing rigid constraints, we modify the structure space so that certain terms are likely to appear within the crossover and mutation operators. In this way, we mimic expertly chosen terms while preserving the possibility of obtaining any equation form. The paper shows that the extraction and use of knowledge allows it to outperform the SINDy algorithm in terms of search stability and robustness. Synthetic examples are given for Burgers, wave, and Korteweg--De Vries equations. 

**Abstract (ZH)**: 在差分方程发现算法中，专家先验知识主要以隐含的方式用于约束预期方程的形式，使算法无法真正发现新的方程。相反，大多数差分方程发现算法试图恢复已知结构中的系数。本文介绍了一种算法，该算法使用自动或手动提取的背景知识来发现未知的方程。这种方法不是施加严格的约束，而是通过修改结构空间，使得某些特定项在交叉和变异操作中更可能出现。这样，我们模拟了专家选择的项，同时保留了获得任何方程形式的可能性。论文表明，知识的提取和使用使该算法在搜索稳定性和鲁棒性方面优于SINDy算法。对于Burgers、波动和Korteweg-De Vries方程，给出了合成示例。 

---
# $\texttt{FORM}$: Learning Expressive and Transferable First-Order Logic Reward Machines 

**Title (ZH)**: $\texttt{FORM}$：学习表达性和可迁移的一阶逻辑奖励机器 

**Authors**: Leo Ardon, Daniel Furelos-Blanco, Roko Parać, Alessandra Russo  

**Link**: [PDF](https://arxiv.org/pdf/2501.00364)  

**Abstract**: Reward machines (RMs) are an effective approach for addressing non-Markovian rewards in reinforcement learning (RL) through finite-state machines. Traditional RMs, which label edges with propositional logic formulae, inherit the limited expressivity of propositional logic. This limitation hinders the learnability and transferability of RMs since complex tasks will require numerous states and edges. To overcome these challenges, we propose First-Order Reward Machines ($\texttt{FORM}$s), which use first-order logic to label edges, resulting in more compact and transferable RMs. We introduce a novel method for $\textbf{learning}$ $\texttt{FORM}$s and a multi-agent formulation for $\textbf{exploiting}$ them and facilitate their transferability, where multiple agents collaboratively learn policies for a shared $\texttt{FORM}$. Our experimental results demonstrate the scalability of $\texttt{FORM}$s with respect to traditional RMs. Specifically, we show that $\texttt{FORM}$s can be effectively learnt for tasks where traditional RM learning approaches fail. We also show significant improvements in learning speed and task transferability thanks to the multi-agent learning framework and the abstraction provided by the first-order language. 

**Abstract (ZH)**: 奖励机器（RMs）是一种通过有限状态机有效解决强化学习（RL）中非马尔可夫奖励问题的方法。传统的RMs通过命题逻辑公式标签化边，继承了命题逻辑的有限表达能力。这一限制阻碍了RMs的可学习性和迁移性，因为复杂任务可能需要大量状态和边。为克服这些挑战，我们提出了基于一阶逻辑的奖励机器（$\texttt{FORM}$s），通过使用一阶逻辑来标记边，从而使得RMs更加紧凑和具有迁移性。我们提出了一种新的$\textbf{学习}$$\texttt{FORM}$s的方法，并设计了一种多智能体框架来$\textbf{利用}$$\texttt{FORM}$s，并促进它们的迁移性，在这种框架中，多个智能体协作学习共享的$\texttt{FORM}$的策略。实验结果表明，$\texttt{FORM}$s相对于传统RMs具有更好的扩展性。具体而言，我们展示了$\texttt{FORM}$s可以在传统RM学习方法失败的任务中有效学习。同时，我们还展示了通过多智能体学习框架和一阶语言提供的抽象，学习速度和任务迁移性获得了显著提升。 

---
# Autonomous Alignment with Human Value on Altruism through Considerate Self-imagination and Theory of Mind 

**Title (ZH)**: 通过体贴的自我想象和理论思维实现基于利他主义的人工智能自主对齐与人类价值一致性的研究 

**Authors**: Haibo Tong, Enmeng Lum, Yinqian Sun, Zhengqiang Han, Chao Liu, Feifei Zhao, Yi Zeng  

**Link**: [PDF](https://arxiv.org/pdf/2501.00320)  

**Abstract**: With the widespread application of Artificial Intelligence (AI) in human society, enabling AI to autonomously align with human values has become a pressing issue to ensure its sustainable development and benefit to humanity. One of the most important aspects of aligning with human values is the necessity for agents to autonomously make altruistic, safe, and ethical decisions, considering and caring for human well-being. Current AI extremely pursues absolute superiority in certain tasks, remaining indifferent to the surrounding environment and other agents, which has led to numerous safety risks. Altruistic behavior in human society originates from humans' capacity for empathizing others, known as Theory of Mind (ToM), combined with predictive imaginative interactions before taking action to produce thoughtful and altruistic behaviors. Inspired by this, we are committed to endow agents with considerate self-imagination and ToM capabilities, driving them through implicit intrinsic motivations to autonomously align with human altruistic values. By integrating ToM within the imaginative space, agents keep an eye on the well-being of other agents in real time, proactively anticipate potential risks to themselves and others, and make thoughtful altruistic decisions that balance negative effects on the environment. The ancient Chinese story of Sima Guang Smashes the Vat illustrates the moral behavior of the young Sima Guang smashed a vat to save a child who had accidentally fallen into it, which is an excellent reference scenario for this paper. We design an experimental scenario similar to Sima Guang Smashes the Vat and its variants with different complexities, which reflects the trade-offs and comprehensive considerations between self-goals, altruistic rescue, and avoiding negative side effects. 

**Abstract (ZH)**: 随着人工智能（AI）在人类社会中的广泛应用，使AI能够自主与人类价值观保持一致已成为确保其可持续发展和造福人类的关键问题。与人类价值观保持一致的一个最关键方面是要求智能体能够自主作出利他、安全和道德的决策，同时考虑并关心人类的福祉。目前的AI在某些任务上追求绝对的优越性，对周围环境和其他智能体漠不关心，这导致了大量安全风险。人类社会中的利他行为源于其同理心能力，即心理理论（Theory of Mind, ToM），并且在采取行动前通过预测性的想象互动产生有思考和利他性的行为。基于此，我们致力于赋予智能体考虑周到的自我想象和ToM能力，通过隐含的内在动机引导它们自主地与人类的利他价值观保持一致。通过在想象空间中结合ToM，智能体能够实时关注其他智能体的福祉，主动预测潜在的风险，并作出权衡环境负面影响的有思考的利他性决策。中国古代故事《司马光砸缸》中的司马光为了救掉进缸里的孩子砸破了缸，这为本文提供了优秀的参考场景。我们设计了一个类似于《司马光砸缸》及其复杂度不同的变体的实验场景，反映了自我目标、救援利他以及避免负面影响之间的权衡与综合考虑。 

---
# Automatically Planning Optimal Parallel Strategy for Large Language Models 

**Title (ZH)**: 自动规划大型语言模型的理想并行策略 

**Authors**: Zongbiao Li, Xiezhao Li, Yinghao Cui, Yijun Chen, Zhixuan Gu, Yuxuan Liu, Wenbo Zhu, Fei Jia, Ke Liu, Qifeng Li, Junyao Zhan, Jiangtao Zhou, Chenxi Zhang, Qike Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00254)  

**Abstract**: The number of parameters in large-scale language models based on transformers is gradually increasing, and the scale of computing clusters is also growing. The technology of quickly mobilizing large amounts of computing resources for parallel computing is becoming increasingly important. In this paper, we propose an automatic parallel algorithm that automatically plans the parallel strategy with maximum throughput based on model and hardware information. By decoupling the training time into computation, communication, and overlap, we established a training duration simulation model. Based on this simulation model, we prune the parallel solution space to shorten the search time required. The multi-node experiment results show that the algorithm can estimate the parallel training duration in real time with an average accuracy of 96%. In our test, the recommendation strategy provided by the algorithm is always globally optimal. 

**Abstract (ZH)**: 基于变压器的大规模语言模型参数数量逐渐增加，计算集群的规模也在扩大。快速调动大量计算资源进行并行计算的技术变得越来越重要。本文提出了一种自动并行算法，该算法基于模型和硬件信息自动规划以最大吞吐量为目标的并行策略。通过将训练时间分解为计算、通信和重叠三个部分，我们建立了一个训练时长仿真模型。基于该仿真模型，我们修剪了并行解决方案空间以缩短搜索时间。多节点实验结果表明，该算法可以实时估计并行训练时长，平均准确率为96%。在我们的测试中，该算法提供的推荐策略始终是全局最优的。 

---
# Generative Emergent Communication: Large Language Model is a Collective World Model 

**Title (ZH)**: 生成性 emergent 通信：大型语言模型是一个集体世界模型 

**Authors**: Tadahiro Taniguchi, Ryo Ueda, Tomoaki Nakamura, Masahiro Suzuki, Akira Taniguchi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00226)  

**Abstract**: This study proposes a unifying theoretical framework called generative emergent communication (generative EmCom) that bridges emergent communication, world models, and large language models (LLMs) through the lens of collective predictive coding (CPC). The proposed framework formalizes the emergence of language and symbol systems through decentralized Bayesian inference across multiple agents, extending beyond conventional discriminative model-based approaches to emergent communication. This study makes the following two key contributions: First, we propose generative EmCom as a novel framework for understanding emergent communication, demonstrating how communication emergence in multi-agent reinforcement learning (MARL) can be derived from control as inference while clarifying its relationship to conventional discriminative approaches. Second, we propose a mathematical formulation showing the interpretation of LLMs as collective world models that integrate multiple agents' experiences through CPC. The framework provides a unified theoretical foundation for understanding how shared symbol systems emerge through collective predictive coding processes, bridging individual cognitive development and societal language evolution. Through mathematical formulations and discussion on prior works, we demonstrate how this framework explains fundamental aspects of language emergence and offers practical insights for understanding LLMs and developing sophisticated AI systems for improving human-AI interaction and multi-agent systems. 

**Abstract (ZH)**: 本文提出了一种统一的理论框架，称为生成性涌现通信（Generative Emergent Communication，简称Generative EmCom），该框架通过集体预测编码（Collective Predictive Coding, CPC）的视角，将涌现通信、世界模型和大型语言模型（LLMs）三者联系起来。该提出的框架通过多个代理的分布式贝叶斯推理形式化了语言和符号系统的涌现，超越了传统的判别模型方法，应用于涌现通信领域。本文做出了以下两个关键贡献：首先，我们提出生成性EmCom作为一种新的框架，用于理解涌现通信，展示了多智能体强化学习（MARL）中的通信涌现如何从控制即推理的角度推导出来，并阐明其与传统判别性方法的关系。其次，我们提供了一个数学形式化表达，将LLMs视为通过CPC整合多个代理经验的集体世界模型。该框架为理解共享符号系统如何通过集体预测编码过程涌现提供了一个统一的理论基础，将个体认知发展与社会语言进化联系起来。通过数学形式化表达和对先前工作的讨论，我们展示了该框架如何解释语言涌现的基本方面，并为理解LLMs和开发提高人机交互和多智能体系统复杂AI系统提供了实用见解。 

---
# CancerKG.ORG A Web-scale, Interactive, Verifiable Knowledge Graph-LLM Hybrid for Assisting with Optimal Cancer Treatment and Care 

**Title (ZH)**: CancerKG.ORG：一个面向Web、交互式、可验证的知识图谱-大语言模型混合系统，用于辅助优化癌症治疗和护理 

**Authors**: Michael Gubanov, Anna Pyayt, Aleksandra Karolak  

**Link**: [PDF](https://arxiv.org/pdf/2501.00223)  

**Abstract**: Here, we describe one of the first Web-scale hybrid Knowledge Graph (KG)-Large Language Model (LLM), populated with the latest peer-reviewed medical knowledge on colorectal Cancer. It is currently being evaluated to assist with both medical research and clinical information retrieval tasks at Moffitt Cancer Center, which is one of the top Cancer centers in the U.S. and in the world. Our hybrid is remarkable as it serves the user needs better than just an LLM, KG or a search-engine in isolation. LLMs as is are known to exhibit hallucinations and catastrophic forgetting as well as are trained on outdated corpora. The state of the art KGs, such as PrimeKG, cBioPortal, ChEMBL, NCBI, and other require manual curation, hence are quickly getting stale. CancerKG is unsupervised and is capable of automatically ingesting and organizing the latest medical findings. To alleviate the LLMs shortcomings, the verified KG serves as a Retrieval Augmented Generation (RAG) guardrail. CancerKG exhibits 5 different advanced user interfaces, each tailored to serve different data modalities better and more convenient for the user. 

**Abstract (ZH)**: 在这里，我们描述了一个早期的Web规模混合知识图谱（KG）-大型语言模型（LLM）系统，该系统包含了最新的同行评审的结直肠癌医学知识。目前，该系统正在莫菲特癌症中心进行评估，以辅助医学研究和临床信息检索任务。莫菲特癌症中心是美国乃至世界领先的癌症中心之一。我们的混合系统与众不同，因为它能够更好地满足用户需求，而不仅仅是单一的LLM、KG或搜索引擎。现成的LLM已知存在幻觉和灾难性遗忘问题，并且训练数据可能已过时。当今最先进的KG，如PrimeKG、cBioPortal、ChEMBL、NCBI等，也需要人工整理，因此会很快变得过时。CancerKG 是一个无需监督的系统，能够自动吸收和组织最新的医学发现。为了缓解LLM的缺点，经过验证的KG充当了检索增强生成（RAG）的护栏。CancerKG 展示了5种不同的高级用户界面，每种界面都针对不同的数据模态进行了优化，以提供更方便的用户体验。 

---
# Probabilistic Explanations for Linear Models 

**Title (ZH)**: 线性模型的概率解释 

**Authors**: Bernardo Subercaseaux, Marcelo Arenas, Kuldeep S Meel  

**Link**: [PDF](https://arxiv.org/pdf/2501.00154)  

**Abstract**: Formal XAI is an emerging field that focuses on providing explanations with mathematical guarantees for the decisions made by machine learning models. A significant amount of work in this area is centered on the computation of "sufficient reasons". Given a model $M$ and an input instance $\vec{x}$, a sufficient reason for the decision $M(\vec{x})$ is a subset $S$ of the features of $\vec{x}$ such that for any instance $\vec{z}$ that has the same values as $\vec{x}$ for every feature in $S$, it holds that $M(\vec{x}) = M(\vec{z})$. Intuitively, this means that the features in $S$ are sufficient to fully justify the classification of $\vec{x}$ by $M$. For sufficient reasons to be useful in practice, they should be as small as possible, and a natural way to reduce the size of sufficient reasons is to consider a probabilistic relaxation; the probability of $M(\vec{x}) = M(\vec{z})$ must be at least some value $\delta \in (0,1]$, for a random instance $\vec{z}$ that coincides with $\vec{x}$ on the features in $S$. Computing small $\delta$-sufficient reasons ($\delta$-SRs) is known to be a theoretically hard problem; even over decision trees--traditionally deemed simple and interpretable models--strong inapproximability results make the efficient computation of small $\delta$-SRs unlikely. We propose the notion of $(\delta, \epsilon)$-SR, a simple relaxation of $\delta$-SRs, and show that this kind of explanation can be computed efficiently over linear models. 

**Abstract (ZH)**: 正式的可解释人工智能（XAI）是一个新兴领域， focuses 于为机器学习模型所做出的决策提供具有数学保证的解释。该领域的大量工作集中于“充分原因”（sufficient reasons）的计算。给定一个模型 \(M\) 和一个输入实例 \(\vec{x}\)，\(\vec{x}\) 的一个充分原因是其特征的一个子集 \(S\)，使得对于任意具有与 \(\vec{x}\) 在 \(S\) 中的所有特征上相同值的实例 \(\vec{z}\)，都有 \(M(\vec{x}) = M(\vec{z})\)。直观上讲，这意味着 \(S\) 中的特征足以完全解释 \(M\) 对 \(\vec{x}\) 的分类。为了使充分原因在实践中有所帮助，它们应该尽可能小，一种自然的方法是考虑概率松弛：对于一个与 \(\vec{x}\) 在 \(S\) 中的所有特征上相同值的随机实例 \(\vec{z}\)，\(M(\vec{x}) = M(\vec{z})\) 的概率至少为某个值 \(\delta \in (0,1]\)。计算小的 \(\delta\) - 充分原因（\(\delta\)-SRs）是一个理论上的难题；即使是在传统上被认为是简单且可解释的决策树模型中，强有力的近似难度结果也使得小的 \(\delta\) - 充分原因的高效计算不太可能。本文提出了 \((\delta, \epsilon)\)-SR 的概念，这是一种 \(\delta\) - 充分原因的简单松弛，并证明了这种类型的解释可以高效地计算在线性模型上。 

---
# AltGen: AI-Driven Alt Text Generation for Enhancing EPUB Accessibility 

**Title (ZH)**: AltGen: 人工智能驱动的替代文字生成以增强EPUB可访问性 

**Authors**: Yixian Shen, Hang Zhang, Yanxin Shen, Lun Wang, Chuanqi Shi, Shaoshuai Du, Yiyi Tao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00113)  

**Abstract**: Digital accessibility is a cornerstone of inclusive content delivery, yet many EPUB files fail to meet fundamental accessibility standards, particularly in providing descriptive alt text for images. Alt text plays a critical role in enabling visually impaired users to understand visual content through assistive technologies. However, generating high-quality alt text at scale is a resource-intensive process, creating significant challenges for organizations aiming to ensure accessibility compliance. This paper introduces AltGen, a novel AI-driven pipeline designed to automate the generation of alt text for images in EPUB files. By integrating state-of-the-art generative models, including advanced transformer-based architectures, AltGen achieves contextually relevant and linguistically coherent alt text descriptions. The pipeline encompasses multiple stages, starting with data preprocessing to extract and prepare relevant content, followed by visual analysis using computer vision models such as CLIP and ViT. The extracted visual features are enriched with contextual information from surrounding text, enabling the fine-tuned language models to generate descriptive and accurate alt text. Validation of the generated output employs both quantitative metrics, such as cosine similarity and BLEU scores, and qualitative feedback from visually impaired users.
Experimental results demonstrate the efficacy of AltGen across diverse datasets, achieving a 97.5% reduction in accessibility errors and high scores in similarity and linguistic fidelity metrics. User studies highlight the practical impact of AltGen, with participants reporting significant improvements in document usability and comprehension. Furthermore, comparative analyses reveal that AltGen outperforms existing approaches in terms of accuracy, relevance, and scalability. 

**Abstract (ZH)**: 数字 accessibility 是包容性内容交付的基础，然而许多 EPUB 文件未能达到基本的 accessibility 标准，特别是在为图像提供描述性替代文本（alt text）方面存在不足。替代文本对于视觉障碍用户来说至关重要，因为它能够通过辅助技术帮助他们理解视觉内容。然而，在大规模生成高质量的描述性替代文本是一个资源密集型的过程，这为希望确保无障碍合规性的组织带来了重大挑战。本文介绍了 AltGen，这是一种新型的 AI 驱动的工作流程，旨在自动为 EPUB 文件中的图像生成替代文本。通过集成最先进的生成模型，包括先进的变压器架构，AltGen 实现了语境相关且语言连贯的替代文本描述。该工作流程包含多个阶段，从数据预处理开始，提取并准备相关的内容，然后使用计算机视觉模型（如 CLIP 和 ViT）进行视觉分析。提取的视觉特征通过周围的文本提供上下文信息，从而使微调的语言模型能够生成描述性和准确的替代文本。生成输出的验证既包括定量指标，如余弦相似度和 BLEU 分数，也包括来自视觉障碍用户的手动反馈。

实验结果表明，AltGen 在多种数据集上表现出色，实现了 97.5% 的无障碍错误减少，并且在相似性和语言忠实度指标上取得了高分。用户研究进一步展示了 AltGen 的实际影响，参与者报告称文档的使用性和可理解性显著提高。此外，与现有方法的比较分析表明，AltGen 在准确度、相关性和可扩展性方面表现更佳。 

---
# Object-level Visual Prompts for Compositional Image Generation 

**Title (ZH)**: 对象级视觉提示在组合图像生成中的应用 

**Authors**: Gaurav Parmar, Or Patashnik, Kuan-Chieh Wang, Daniil Ostashev, Srinivasa Narasimhan, Jun-Yan Zhu, Daniel Cohen-Or, Kfir Aberman  

**Link**: [PDF](https://arxiv.org/pdf/2501.01424)  

**Abstract**: We introduce a method for composing object-level visual prompts within a text-to-image diffusion model. Our approach addresses the task of generating semantically coherent compositions across diverse scenes and styles, similar to the versatility and expressiveness offered by text prompts. A key challenge in this task is to preserve the identity of the objects depicted in the input visual prompts, while also generating diverse compositions across different images. To address this challenge, we introduce a new KV-mixed cross-attention mechanism, in which keys and values are learned from distinct visual representations. The keys are derived from an encoder with a small bottleneck for layout control, whereas the values come from a larger bottleneck encoder that captures fine-grained appearance details. By mixing keys and values from these complementary sources, our model preserves the identity of the visual prompts while supporting flexible variations in object arrangement, pose, and composition. During inference, we further propose object-level compositional guidance to improve the method's identity preservation and layout correctness. Results show that our technique produces diverse scene compositions that preserve the unique characteristics of each visual prompt, expanding the creative potential of text-to-image generation. 

**Abstract (ZH)**: 我们提出了一种在文本到图像扩散模型中组合对象级视觉提示的方法。我们的方法旨在生成在多样场景和风格下语义连贯的组合，这与文本提示在多样性和表达力方面的灵活性和表现力相类似。在这个任务中，一个关键挑战是在保持输入视觉提示所描绘的物体身份的同时，生成不同图像中的多样化组合。为了解决这一挑战，我们引入了一种新的键值混合作注意力机制(KV-mixed cross-attention mechanism)，其中键和值分别从不同的视觉表示中学习。键来自于具有小瓶颈结构的编码器，用于布局控制，而值则来自一个较大的瓶颈编码器，用于捕捉精细的外观细节。通过将这些互补来源的键值混合，我们的模型可以保持视觉提示的身份，同时支持对象布局、姿态和组合的灵活变化。在推断过程中，我们进一步提出对象级组合引导，以提高方法的身份保留和布局准确性。实验结果显示，我们的技术能够生成多样化的场景组合，同时保留每个视觉提示的独特特征，从而扩展了文本到图像生成的创造性潜力。 

---
# Multi-Modal Video Feature Extraction for Popularity Prediction 

**Title (ZH)**: 多模态视频特征提取及其对流行度预测的应用 

**Authors**: Haixu Liu, Wenning Wang, Haoxiang Zheng, Penghao Jiang, Qirui Wang, Ruiqing Yan, Qiuzhuang Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.01422)  

**Abstract**: This work aims to predict the popularity of short videos using the videos themselves and their related features. Popularity is measured by four key engagement metrics: view count, like count, comment count, and share count. This study employs video classification models with different architectures and training methods as backbone networks to extract video modality features. Meanwhile, the cleaned video captions are incorporated into a carefully designed prompt framework, along with the video, as input for video-to-text generation models, which generate detailed text-based video content understanding. These texts are then encoded into vectors using a pre-trained BERT model. Based on the six sets of vectors mentioned above, a neural network is trained for each of the four prediction metrics. Moreover, the study conducts data mining and feature engineering based on the video and tabular data, constructing practical features such as the total frequency of hashtag appearances, the total frequency of mention appearances, video duration, frame count, frame rate, and total time online. Multiple machine learning models are trained, and the most stable model, XGBoost, is selected. Finally, the predictions from the neural network and XGBoost models are averaged to obtain the final result. 

**Abstract (ZH)**: 本文旨在利用短视频及其相关特征预测其受欢迎程度。受欢迎程度通过四个关键的参与度指标进行衡量：播放量、点赞量、评论量和分享量。本研究采用具有不同架构和训练方法的视频分类模型作为骨干网络，以提取视频模态特征。同时，经过清洗的视频字幕被整合进一个精心设计的提示框架中，与视频一起作为输入，用于生成视频到文本的模型，生成详细的基于文本的视频内容理解。这些文本随后通过预训练的BERT模型编码成向量。基于上述六组向量，分别训练了四个预测指标的神经网络。此外，本研究基于视频和表格数据进行了数据挖掘和特征工程，构建了诸如标签出现的总频率、提及出现的总频率、视频时长、帧数、帧率和上线总时长等实用特征。多种机器学习模型被训练，最终选定了稳定性最佳的XGBoost模型。最后，神经网络和XGBoost模型的预测结果被平均，获得最终预测结果。 

---
# On Unifying Video Generation and Camera Pose Estimation 

**Title (ZH)**: 统一视频生成与相机姿态估计 

**Authors**: Chun-Hao Paul Huang, Jae Shin Yoon, Hyeonho Jeong, Niloy Mitra, Duygu Ceylan  

**Link**: [PDF](https://arxiv.org/pdf/2501.01409)  

**Abstract**: Inspired by the emergent 3D capabilities in image generators, we explore whether video generators similarly exhibit 3D awareness. Using structure-from-motion (SfM) as a benchmark for 3D tasks, we investigate if intermediate features from OpenSora, a video generation model, can support camera pose estimation. We first examine native 3D awareness in video generation features by routing raw intermediate outputs to SfM-prediction modules like DUSt3R. Then, we explore the impact of fine-tuning on camera pose estimation to enhance 3D awareness. Results indicate that while video generator features have limited inherent 3D awareness, task-specific supervision significantly boosts their accuracy for camera pose estimation, resulting in competitive performance. The proposed unified model, named JOG3R, produces camera pose estimates with competitive quality without degrading video generation quality. 

**Abstract (ZH)**: 受到图像生成器中涌现的3D能力启发，我们探索视频生成器是否也表现出3D感知。我们使用结构光度学（Structure-from-Motion, SfM）作为3D任务的基准，调查OpenSora（一个视频生成模型）的中间特征是否能够支持相机姿态估计。我们首先通过将原始中间输出路由到DUSt3R等SfM预测模块来检验视频生成特征中的固有3D感知能力。然后，我们探索微调对相机姿态估计的影响，以增强3D感知。结果表明，虽然视频生成器特征本身具有有限的固有3D感知能力，但特定任务的监督显著提高了其在相机姿态估计中的准确性，从而实现了竞争力的表现。提出的统一模型JOG3R能够在保持视频生成质量的同时生成具有竞争力质量的相机姿态估计。 

---
# A Unified Hyperparameter Optimization Pipeline for Transformer-Based Time Series Forecasting Models 

**Title (ZH)**: 基于Transformer的时序预测模型统一超参数优化流程 

**Authors**: Jingjing Xu, Caesar Wu, Yuan-Fang Li, Grégoire Danoy, Pascal Bouvry  

**Link**: [PDF](https://arxiv.org/pdf/2501.01394)  

**Abstract**: Transformer-based models for time series forecasting (TSF) have attracted significant attention in recent years due to their effectiveness and versatility. However, these models often require extensive hyperparameter optimization (HPO) to achieve the best possible performance, and a unified pipeline for HPO in transformer-based TSF remains lacking. In this paper, we present one such pipeline and conduct extensive experiments on several state-of-the-art (SOTA) transformer-based TSF models. These experiments are conducted on standard benchmark datasets to evaluate and compare the performance of different models, generating practical insights and examples. Our pipeline is generalizable beyond transformer-based architectures and can be applied to other SOTA models, such as Mamba and TimeMixer, as demonstrated in our experiments. The goal of this work is to provide valuable guidance to both industry practitioners and academic researchers in efficiently identifying optimal hyperparameters suited to their specific domain applications. The code and complete experimental results are available on GitHub. 

**Abstract (ZH)**: 基于Transformer的模型在时间序列预测（TSF）方面近年来引起了广泛关注，由于其有效性和灵活性。然而，这些模型通常需要大量的超参数优化（HPO）以达到最佳性能，而统一的Transformer基TSF模型的HPO管道仍然缺乏。本文提出了一种这样的管道，并在几种最新的基于Transformer的TSF模型上进行了广泛实验。这些实验在标准基准数据集上进行，以评估和比较不同模型的性能，产生实用的见解和案例。我们的管道不仅适用于Transformer架构，还可以推广到其他最新模型（SOTA），如Mamba和TimeMixer，这一点在我们的实验中得到了验证。本工作的目标是为行业从业者和学术研究人员提供有价值的经验指导，以高效地识别适合其特定领域应用的最佳超参数。代码和完整实验结果可在GitHub上获得。 

---
# Training Medical Large Vision-Language Models with Abnormal-Aware Feedback 

**Title (ZH)**: 带有异常意识反馈的医学大规模视觉-语言模型训练 

**Authors**: Yucheng Zhou, Lingran Song, Jianbing Shen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01377)  

**Abstract**: Existing Medical Large Vision-Language Models (Med-LVLMs), which encapsulate extensive medical knowledge, demonstrate excellent capabilities in understanding medical images and responding to human queries based on these images. However, there remain challenges in visual localization in medical images, which is crucial for abnormality detection and interpretation. To address these issues, we propose a novel UMed-LVLM designed with Unveiling Medical abnormalities. Specifically, we collect a Medical Abnormalities Unveiling (MAU) dataset and propose a two-stage training method for UMed-LVLM training. To collect MAU dataset, we propose a prompt method utilizing the GPT-4V to generate diagnoses based on identified abnormal areas in medical images. Moreover, the two-stage training method includes Abnormal-Aware Instruction Tuning and Abnormal-Aware Rewarding, comprising Abnormal Localization Rewarding and Vision Relevance Rewarding. Experimental results demonstrate that our UMed-LVLM surpasses existing Med-LVLMs in identifying and understanding medical abnormality. In addition, this work shows that enhancing the abnormality detection capabilities of Med-LVLMs significantly improves their understanding of medical images and generalization capability. 

**Abstract (ZH)**: 现有的医学大型视觉语言模型（Med-LVLMs），它们整合了大量的医学知识，表现出在理解医学图像和基于这些图像回答人类查询方面出色的性能。然而，在医学图像中的视觉定位仍然是一个挑战，这对于异常检测和解释至关重要。为了解决这些问题，我们提出了一种名为UMed-LVLM的新颖模型，该模型旨在揭示医学异常。具体而言，我们收集了一个医学异常揭示（MAU）数据集，并提出了一种两阶段训练方法来训练UMed-LVLM。为了收集MAU数据集，我们提出了一种利用GPT-4V的提示方法，基于医学图像中识别出的异常区域生成诊断。此外，两阶段训练方法包括异常意识指令调优和异常意识奖励，具体包括异常定位奖励和视觉相关性奖励。实验结果表明，我们的UMed-LVLM在识别和理解医学异常方面优于现有的Med-LVLMs。此外，本研究还表明，增强Med-LVLMs的异常检测能力显著提高了它们对医学图像的理解能力和泛化能力。 

---
# ScarNet: A Novel Foundation Model for Automated Myocardial Scar Quantification from LGE in Cardiac MRI 

**Title (ZH)**: ScarNet：一种用于心脏MRI LGE自动心肌瘢痕定量的新颖基础模型 

**Authors**: Neda Tavakoli, Amir Ali Rahsepar, Brandon C. Benefield, Daming Shen, Santiago López-Tapia, Florian Schiffers, Jeffrey J. Goldberger, Christine M. Albert, Edwin Wu, Aggelos K. Katsaggelos, Daniel C. Lee, Daniel Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.01372)  

**Abstract**: Background: Late Gadolinium Enhancement (LGE) imaging is the gold standard for assessing myocardial fibrosis and scarring, with left ventricular (LV) LGE extent predicting major adverse cardiac events (MACE). Despite its importance, routine LGE-based LV scar quantification is hindered by labor-intensive manual segmentation and inter-observer variability. Methods: We propose ScarNet, a hybrid model combining a transformer-based encoder from the Medical Segment Anything Model (MedSAM) with a convolution-based U-Net decoder, enhanced by tailored attention blocks. ScarNet was trained on 552 ischemic cardiomyopathy patients with expert segmentations of myocardial and scar boundaries and tested on 184 separate patients. Results: ScarNet achieved robust scar segmentation in 184 test patients, yielding a median Dice score of 0.912 (IQR: 0.863--0.944), significantly outperforming MedSAM (median Dice = 0.046, IQR: 0.043--0.047) and nnU-Net (median Dice = 0.638, IQR: 0.604--0.661). ScarNet demonstrated lower bias (-0.63%) and coefficient of variation (4.3%) compared to MedSAM (bias: -13.31%, CoV: 130.3%) and nnU-Net (bias: -2.46%, CoV: 20.3%). In Monte Carlo simulations with noise perturbations, ScarNet achieved significantly higher scar Dice (0.892 \pm 0.053, CoV = 5.9%) than MedSAM (0.048 \pm 0.112, CoV = 233.3%) and nnU-Net (0.615 \pm 0.537, CoV = 28.7%). Conclusion: ScarNet outperformed MedSAM and nnU-Net in accurately segmenting myocardial and scar boundaries in LGE images. The model exhibited robust performance across diverse image qualities and scar patterns. 

**Abstract (ZH)**: 背景：延迟钆增强（Late Gadolinium Enhancement, LGE）成像是评估心肌纤维化和瘢痕组织的金标准，左室（LV）LGE范围预测主要不良心脏事件（Major Adverse Cardiac Events, MACE）。尽管LGE在临床中非常重要，但由于劳强度大的手动分割和观察者间变异性，常规的LGE基线疤痕量化受到阻碍。方法：我们提出了一种结合了Medical Segment Anything Model（MedSAM）的变压器基编码器和卷积基U-Net解码器的混合模型ScarNet，并通过定制的注意力模块进行了增强。该模型在包含776名缺血性心肌病患者的数据库上进行训练，其中包含专家标注的心肌和疤痕边界，并在184名独立患者上进行了测试。结果：在184名测试患者中，ScarNet实现了稳健的疤痕分割，中位Dice分数为0.912（四分位距：0.863-0.944），显著优于MedSAM（中位Dice = 0.046，四分位距：0.043-0.047）和nnU-Net（中位Dice = 0.638，四分位距：0.604-0.661）。ScarNet的偏差（-0.63%）和变异系数（4.3%）低于MedSAM（偏差：-13.31%，变异系数：130.3%）和nnU-Net（偏差：-2.46%，变异系数：20.3%）。在噪声扰动的蒙特卡洛模拟中，ScarNet比MedSAM（0.048 ± 0.112，变异系数：233.3%）和nnU-Net（0.615 ± 0.537，变异系数：28.7%）在疤痕Dice分数（0.892 ± 0.053，变异系数：5.9%）上表现更好。结论：ScarNet在LGE图像中准确分割心肌和疤痕边界方面优于MedSAM和nnU-Net。该模型在不同图像质量和疤痕模式下表现出色。 

---
# Contrastive Learning from Exploratory Actions: Leveraging Natural Interactions for Preference Elicitation 

**Title (ZH)**: 基于探索性动作的对比学习：利用自然交互进行偏好 elicitation 

**Authors**: Nathaniel Dennler, Stefanos Nikolaidis, Maja Matarić  

**Link**: [PDF](https://arxiv.org/pdf/2501.01367)  

**Abstract**: People have a variety of preferences for how robots behave. To understand and reason about these preferences, robots aim to learn a reward function that describes how aligned robot behaviors are with a user's preferences. Good representations of a robot's behavior can significantly reduce the time and effort required for a user to teach the robot their preferences. Specifying these representations -- what "features" of the robot's behavior matter to users -- remains a difficult problem; Features learned from raw data lack semantic meaning and features learned from user data require users to engage in tedious labeling processes. Our key insight is that users tasked with customizing a robot are intrinsically motivated to produce labels through exploratory search; they explore behaviors that they find interesting and ignore behaviors that are irrelevant. To harness this novel data source of exploratory actions, we propose contrastive learning from exploratory actions (CLEA) to learn trajectory features that are aligned with features that users care about. We learned CLEA features from exploratory actions users performed in an open-ended signal design activity (N=25) with a Kuri robot, and evaluated CLEA features through a second user study with a different set of users (N=42). CLEA features outperformed self-supervised features when eliciting user preferences over four metrics: completeness, simplicity, minimality, and explainability. 

**Abstract (ZH)**: 人们对机器人行为的偏好多种多样。为了理解并推断这些偏好，机器人旨在学习一个奖励函数，以描述机器人行为与用户偏好的一致性。良好的机器人行为表示可以显著减少用户向机器人传授其偏好所需的时间和努力。然而，确定这些表示——即“哪些”机器人行为特征对用户来说是重要的——仍然是一个难题。基于原始数据学习到的特征缺乏语义含义，而基于用户数据学习到的特征则需要用户进行繁琐的标注过程。我们的关键见解是，负责定制机器人的用户会出于内在动机通过探索性搜索生成标签；他们探索自己感兴趣的机器人行为，并忽略无关的行为。

为了利用这一新颖的数据源——探索性动作，我们提出了一种基于探索性动作的对比学习方法（CLEA），以学习与用户关心的特征相一致的行为轨迹特征。我们在一个开放式的信号设计活动中（N=25）使用Kuri机器人让用户执行探索性动作来学习CLEA特征，并通过第二个不同的用户研究（N=42）评估了CLEA特征。与自我监督学习特征相比，CLEA特征在四个指标（完整性、简单性、简洁性和可解释性）中均表现更优，以激发用户偏好。 

---
# ViGiL3D: A Linguistically Diverse Dataset for 3D Visual Grounding 

**Title (ZH)**: ViGiL3D：一个多语种三维视觉定位数据集 

**Authors**: Austin T. Wang, ZeMing Gong, Angel X. Chang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01366)  

**Abstract**: 3D visual grounding (3DVG) involves localizing entities in a 3D scene referred to by natural language text. Such models are useful for embodied AI and scene retrieval applications, which involve searching for objects or patterns using natural language descriptions. While recent works have focused on LLM-based scaling of 3DVG datasets, these datasets do not capture the full range of potential prompts which could be specified in the English language. To ensure that we are scaling up and testing against a useful and representative set of prompts, we propose a framework for linguistically analyzing 3DVG prompts and introduce Visual Grounding with Diverse Language in 3D (ViGiL3D), a diagnostic dataset for evaluating visual grounding methods against a diverse set of language patterns. We evaluate existing open-vocabulary 3DVG methods to demonstrate that these methods are not yet proficient in understanding and identifying the targets of more challenging, out-of-distribution prompts, toward real-world applications. 

**Abstract (ZH)**: 三维视觉定位（3DVG）涉及使用自然语言文本在三维场景中定位实体。这类模型对于实现基于体态的人工智能和场景检索应用具有重要价值，这些应用需要利用自然语言描述来搜索对象或模式。尽管近期研究主要集中在使用大型预训练语言模型（LLM）来扩展3DVG数据集，但这些数据集并不能涵盖英语中可能指定的所有范围的提示。为了确保我们在扩展和测试过程中使用的是有用且具有代表性的提示集，我们提出了一种语言分析框架，并介绍了Visual Grounding with Diverse Language in 3D（ViGiL3D），这是一个用于评估视觉定位方法的诊断数据集，涵盖了多样化的语言模式。我们对现有的开放式词汇3DVG方法进行评估，证明这些方法尚不足以理解和识别更具挑战性的、不常见的提示的目标，以适应实际应用需求。 

---
# CySecBench: Generative AI-based CyberSecurity-focused Prompt Dataset for Benchmarking Large Language Models 

**Title (ZH)**: CySecBench：基于生成AI的旨在网络安全的大语言模型基准测试提示数据集 

**Authors**: Johan Wahréus, Ahmed Mohamed Hussain, Panos Papadimitratos  

**Link**: [PDF](https://arxiv.org/pdf/2501.01335)  

**Abstract**: Numerous studies have investigated methods for jailbreaking Large Language Models (LLMs) to generate harmful content. Typically, these methods are evaluated using datasets of malicious prompts designed to bypass security policies established by LLM providers. However, the generally broad scope and open-ended nature of existing datasets can complicate the assessment of jailbreaking effectiveness, particularly in specific domains, notably cybersecurity. To address this issue, we present and publicly release CySecBench, a comprehensive dataset containing 12662 prompts specifically designed to evaluate jailbreaking techniques in the cybersecurity domain. The dataset is organized into 10 distinct attack-type categories, featuring close-ended prompts to enable a more consistent and accurate assessment of jailbreaking attempts. Furthermore, we detail our methodology for dataset generation and filtration, which can be adapted to create similar datasets in other domains. To demonstrate the utility of CySecBench, we propose and evaluate a jailbreaking approach based on prompt obfuscation. Our experimental results show that this method successfully elicits harmful content from commercial black-box LLMs, achieving Success Rates (SRs) of 65% with ChatGPT and 88% with Gemini; in contrast, Claude demonstrated greater resilience with a jailbreaking SR of 17%. Compared to existing benchmark approaches, our method shows superior performance, highlighting the value of domain-specific evaluation datasets for assessing LLM security measures. Moreover, when evaluated using prompts from a widely used dataset (i.e., AdvBench), it achieved an SR of 78.5%, higher than the state-of-the-art methods. 

**Abstract (ZH)**: Numerous 研究已经探讨了破解大型语言模型 (LLMs) 以生成有害内容的方法。通常，这些方法是通过使用设计来绕过LLM提供商制定的安全政策的恶意提示数据集进行评估的。然而，现有数据集通常范围广泛且开放式的特点，可能会在特定领域（尤其在网络安全领域）评估破解有效性方面造成复杂性。为解决这一问题，我们提出了并公开发布了CySecBench，这是一个包含12,662个专门设计用于评估网络安全领域破解技术的有效性的提示数据集。数据集被组织成10个不同的攻击类别，采用封闭式提示，以实现更一致和准确的破解尝试评估。此外，我们详细描述了数据集生成和过滤的方法，这些方法可以适应其他领域的数据集创建。为了展示CySecBench的实用性，我们提出并评估了一种基于提示混淆的破解方法。实验结果表明，该方法成功从商业黑盒LLM中引出了有害内容，使用ChatGPT的成功率为65%，使用Gemini的成功率为88%；相比之下，Claude的破解成功率仅为17%，显示出更强的抗破解能力。与现有的基准方法相比，我们的方法表现出更优的性能，强调了针对特定领域的评估数据集对于评估LLM安全措施的价值。此外，在使用广泛使用的数据集（如AdvBench）进行评估时，其成功率达到了78.5%，超过了最先进的方法。 

---
# The Prompt Alchemist: Automated LLM-Tailored Prompt Optimization for Test Case Generation 

**Title (ZH)**: 《Prompt 魔法师：面向测试案例生成的自动化大型语言模型自适应提示优化》 

**Authors**: Shuzheng Gao, Chaozheng Wang, Cuiyun Gao, Xiaoqian Jiao, Chun Yong Chong, Shan Gao, Michael Lyu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01329)  

**Abstract**: Test cases are essential for validating the reliability and quality of software applications. Recent studies have demonstrated the capability of Large Language Models (LLMs) to generate useful test cases for given source code. However, the existing work primarily relies on human-written plain prompts, which often leads to suboptimal results since the performance of LLMs can be highly influenced by the prompts. Moreover, these approaches use the same prompt for all LLMs, overlooking the fact that different LLMs might be best suited to different prompts. Given the wide variety of possible prompt formulations, automatically discovering the optimal prompt for each LLM presents a significant challenge. Although there are methods on automated prompt optimization in the natural language processing field, they are hard to produce effective prompts for the test case generation task. First, the methods iteratively optimize prompts by simply combining and mutating existing ones without proper guidance, resulting in prompts that lack diversity and tend to repeat the same errors in the generated test cases. Second, the prompts are generally lack of domain contextual knowledge, limiting LLMs' performance in the task. 

**Abstract (ZH)**: 测试用例对于验证软件应用的可靠性和质量至关重要。最近的研究表明，大型语言模型（LLMs）能够生成适用于给定源代码的有用测试用例。然而，现有的工作主要依赖于人工编写的简单提示，这往往会导致结果不尽如人意，因为LLMs的表现会受到提示的影响。此外，这些方法使用相同的提示来处理所有LLMs，忽视了不同LLMs可能最适合不同的提示这一事实。由于可能存在的提示形式种类繁多，自动发现每个LLMs的最佳提示是一个重大挑战。尽管在自然语言处理领域存在一些自动提示优化的方法，但它们对于生成测试用例的任务来说往往无效。首先，这些方法通过简单地组合和变异现有的提示来逐次优化提示，缺乏适当的引导，导致生成的提示缺乏多样性，并且倾向于在生成的测试用例中重复相同的错误。其次，这些提示通常缺乏领域上下文知识，限制了LLMs在该任务中的表现。 

---
# Understanding Difficult-to-learn Examples in Contrastive Learning: A Theoretical Framework for Spectral Contrastive Learning 

**Title (ZH)**: 对比学习中难以学习示例的理解：光谱对比学习的理论框架 

**Authors**: Yi-Ge Zhang, Jingyi Cui, Qiran Li, Yisen Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01317)  

**Abstract**: Unsupervised contrastive learning has shown significant performance improvements in recent years, often approaching or even rivaling supervised learning in various tasks. However, its learning mechanism is fundamentally different from that of supervised learning. Previous works have shown that difficult-to-learn examples (well-recognized in supervised learning as examples around the decision boundary), which are essential in supervised learning, contribute minimally in unsupervised settings. In this paper, perhaps surprisingly, we find that the direct removal of difficult-to-learn examples, although reduces the sample size, can boost the downstream classification performance of contrastive learning. To uncover the reasons behind this, we develop a theoretical framework modeling the similarity between different pairs of samples. Guided by this theoretical framework, we conduct a thorough theoretical analysis revealing that the presence of difficult-to-learn examples negatively affects the generalization of contrastive learning. Furthermore, we demonstrate that the removal of these examples, and techniques such as margin tuning and temperature scaling can enhance its generalization bounds, thereby improving performance. Empirically, we propose a simple and efficient mechanism for selecting difficult-to-learn examples and validate the effectiveness of the aforementioned methods, which substantiates the reliability of our proposed theoretical framework. 

**Abstract (ZH)**: 自监督对比学习近年来在多个任务中显示出显著的性能提升，有时甚至可以与监督学习媲美。然而，其学习机制与监督学习的基本原理截然不同。先前的研究表明，那些在监督学习中被认为靠近决策边界且难以学习的样本，在自监督学习环境中对性能的贡献非常有限。本文中，我们意外地发现，直接移除这些难以学习的样本，虽然减少了样本数量，却可以提升对比学习的下游分类性能。为了探究这一现象背后的原因，我们建立了衡量不同样本对相似性的理论框架，并以此框架为指导，进行了深入的理论分析，揭示了难以学习的样本如何对对比学习的一般化能力产生负面影响。同时，我们证明了一旦移除这些样本，并采用间跺调整和温度规一化等技术，可以改善对比学习的一般化上限，从而提高其性能。从实验上，我们提出了一种简单有效的难以学习样本的选择机制，并验证了前述方法的有效性，进一步证实了我们提出的理论框架的可靠性。 

---
# Multi-Head Explainer: A General Framework to Improve Explainability in CNNs and Transformers 

**Title (ZH)**: 多头解释器：提高卷积神经网络和变换器可解释性的通用框架 

**Authors**: Bohang Sun, Pietro Liò  

**Link**: [PDF](https://arxiv.org/pdf/2501.01311)  

**Abstract**: In this study, we introduce the Multi-Head Explainer (MHEX), a versatile and modular framework that enhances both the explainability and accuracy of Convolutional Neural Networks (CNNs) and Transformer-based models. MHEX consists of three core components: an Attention Gate that dynamically highlights task-relevant features, Deep Supervision that guides early layers to capture fine-grained details pertinent to the target class, and an Equivalent Matrix that unifies refined local and global representations to generate comprehensive saliency maps. Our approach demonstrates superior compatibility, enabling effortless integration into existing residual networks like ResNet and Transformer architectures such as BERT with minimal modifications. Extensive experiments on benchmark datasets in medical imaging and text classification show that MHEX not only improves classification accuracy but also produces highly interpretable and detailed saliency scores. 

**Abstract (ZH)**: 在本研究中，我们引入了多头解释器（MHEX），这是一个既具备解释性和准确性增强功能的多功能和模块化框架，适用于卷积神经网络（CNN）和基于变换器的模型。MHEX 包含三个核心组件：注意力门控（Attention Gate），它动态地突出显示与任务相关的特点；深度监督（Deep Supervision），它引导早期层捕捉与目标类别相关的重要细节；以及等价矩阵（Equivalent Matrix），它统一了精细的局部表示和全局表示，生成全面的显著性图。我们的方法表现出卓越的兼容性，能够轻松集成到现有的残差网络（如ResNet）和变换器架构（如BERT）中，只需少量修改即可。在医学影像和文本分类基准数据集上的广泛实验表明，MHEX 不仅提高了分类准确性，还生成了高度可解释且详细的显著性评分。 

---
# Citations and Trust in LLM Generated Responses 

**Title (ZH)**: LLM生成响应中的引用与信任问题 

**Authors**: Yifan Ding, Matthew Facciani, Amrit Poudel, Ellen Joyce, Salvador Aguinaga, Balaji Veeramani, Sanmitra Bhattacharya, Tim Weninger  

**Link**: [PDF](https://arxiv.org/pdf/2501.01303)  

**Abstract**: Question answering systems are rapidly advancing, but their opaque nature may impact user trust. We explored trust through an anti-monitoring framework, where trust is predicted to be correlated with presence of citations and inversely related to checking citations. We tested this hypothesis with a live question-answering experiment that presented text responses generated using a commercial Chatbot along with varying citations (zero, one, or five), both relevant and random, and recorded if participants checked the citations and their self-reported trust in the generated responses. We found a significant increase in trust when citations were present, a result that held true even when the citations were random; we also found a significant decrease in trust when participants checked the citations. These results highlight the importance of citations in enhancing trust in AI-generated content. 

**Abstract (ZH)**: 问答系统正在迅速发展，但其不透明的特性可能影响用户的信任度。我们从反监控的角度探讨了信任问题，认为信任与引用的存在正相关，与检查引用的行为负相关。我们通过一项现场问答实验验证了这一假设，该实验展示了使用商业聊天机器人生成的文本响应，并附有不同的引用数量（零、一或五），包括相关和随机引用，记录参与者是否检查了这些引用以及他们对生成答案的信任度。结果发现，当存在引用时，用户的信任度显著提高；即使引用是随机的，这一结果依然成立；我们还发现，当参与者检查引用时，信任度显著下降。这些结果强调了在人工智能生成内容中引用的重要性，有助于增强信任。 

---
# LEO-Split: A Semi-Supervised Split Learning Framework over LEO Satellite Networks 

**Title (ZH)**: LEO-Split：基于LEO卫星网络的半监督划分学习框架 

**Authors**: Zheng Lin, Yuxin Zhang, Zhe Chen, Zihan Fang, Cong Wu, Xianhao Chen, Yue Gao, Jun Luo  

**Link**: [PDF](https://arxiv.org/pdf/2501.01293)  

**Abstract**: Recently, the increasing deployment of LEO satellite systems has enabled various space analytics (e.g., crop and climate monitoring), which heavily relies on the advancements in deep learning (DL). However, the intermittent connectivity between LEO satellites and ground station (GS) significantly hinders the timely transmission of raw data to GS for centralized learning, while the scaled-up DL models hamper distributed learning on resource-constrained LEO satellites. Though split learning (SL) can be a potential solution to these problems by partitioning a model and offloading primary training workload to GS, the labor-intensive labeling process remains an obstacle, with intermittent connectivity and data heterogeneity being other challenges. In this paper, we propose LEO-Split, a semi-supervised (SS) SL design tailored for satellite networks to combat these challenges. Leveraging SS learning to handle (labeled) data scarcity, we construct an auxiliary model to tackle the training failure of the satellite-GS non-contact time. Moreover, we propose a pseudo-labeling algorithm to rectify data imbalances across satellites. Lastly, an adaptive activation interpolation scheme is devised to prevent the overfitting of server-side sub-model training at GS. Extensive experiments with real-world LEO satellite traces (e.g., Starlink) demonstrate that our LEO-Split framework achieves superior performance compared to state-ofthe-art benchmarks. 

**Abstract (ZH)**: 近年来，低地球轨道（LEO）卫星系统的部署不断增加，这使得各种空间分析活动（例如农作物监测和气候监测）成为可能，这些活动高度依赖于深度学习（DL）的进步。然而，LEO卫星与地面站（GS）之间的间歇性连接极大地阻碍了实时将原始数据传送到GS进行集中学习，而大规模的DL模型则使在资源受限的LEO卫星上进行分布式学习变得困难重重。虽然分割学习（SL）可以通过将模型分区并卸载主要训练任务到GS来成为解决这些问题的一种潜在方法，但繁重的手动标签过程仍然是一个障碍。此外，间歇性连接和数据异构性也是其他挑战。为应对这些挑战，本文提出了一种名为LEO-Split的半监督（SS）分割学习设计，专门针对卫星网络。利用半监督学习来处理标记数据稀缺的问题，我们构建了一个辅助模型来应对卫星与GS之间接触时间不足的训练失败问题。此外，我们提出了一种伪标签算法来纠正卫星间的数据不平衡。最后，我们设计了一种自适应激活插值方案，以防止服务器端子模型在GS上的训练过度拟合。通过使用实际的LEO卫星轨迹（例如，Starlink）进行广泛的实验，表明我们的LEO-Split框架在性能上优于现有的基准方法。 

---
# NeutraSum: A Language Model can help a Balanced Media Diet by Neutralizing News Summaries 

**Title (ZH)**: NeutraSum：语言模型可以通过中立化新闻摘要帮助实现平衡的媒体饮食 

**Authors**: Xi Luo, Junjie Liu, Sirong Wu, Yuhui Deng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01284)  

**Abstract**: Media bias in news articles arises from the political polarisation of media outlets, which can reinforce societal stereotypes and beliefs. Reporting on the same event often varies significantly between outlets, reflecting their political leanings through polarised language and focus. Although previous studies have attempted to generate bias-free summaries from multiperspective news articles, they have not effectively addressed the challenge of mitigating inherent media bias. To address this gap, we propose \textbf{NeutraSum}, a novel framework that integrates two neutrality losses to adjust the semantic space of generated summaries, thus minimising media bias. These losses, designed to balance the semantic distances across polarised inputs and ensure alignment with expert-written summaries, guide the generation of neutral and factually rich summaries. To evaluate media bias, we employ the political compass test, which maps political leanings based on economic and social dimensions. Experimental results on the Allsides dataset demonstrate that NeutraSum not only improves summarisation performance but also achieves significant reductions in media bias, offering a promising approach for neutral news summarisation. 

**Abstract (ZH)**: 新闻文章中的媒体偏见源于媒体机构的政治极化，这可以强化社会刻板印象和信念。不同媒体机构对同一事件的报道往往存在显著差异，反映出它们的政治倾向并通过极化语言和关注点来体现。尽管先前的研究尝试从多视角新闻文章中生成无偏见的摘要，但它们未能有效解决缓解固有媒体偏见的挑战。为弥补这一空白，我们提出了一种名为**NeutraSum**的新型框架，该框架结合了两种中立性损失，以调整生成摘要的语义空间，从而最小化媒体偏见。这些损失旨在平衡极化输入之间的语义距离，并确保与专家撰写的摘要保持一致，从而引导生成中立且富含事实的摘要。

为了评估媒体偏见，我们采用了极化 compass 测试，该测试基于经济和社会维度映射政治倾向。在 Allsides 数据集上的实验结果表明，NeutraSum 不仅提高了摘要性能，还实现了显著减少媒体偏见的效果，为中立新闻摘要提供了有前景的方法。 

---
# PIMAEX: Multi-Agent Exploration through Peer Incentivization 

**Title (ZH)**: PIMAEX：通过同伴激励实现多agent探索 

**Authors**: Michael Kölle, Johannes Tochtermann, Julian Schönberger, Gerhard Stenzel, Philipp Altmann, Claudia Linnhoff-Popien  

**Link**: [PDF](https://arxiv.org/pdf/2501.01266)  

**Abstract**: While exploration in single-agent reinforcement learning has been studied extensively in recent years, considerably less work has focused on its counterpart in multi-agent reinforcement learning. To address this issue, this work proposes a peer-incentivized reward function inspired by previous research on intrinsic curiosity and influence-based rewards. The \textit{PIMAEX} reward, short for Peer-Incentivized Multi-Agent Exploration, aims to improve exploration in the multi-agent setting by encouraging agents to exert influence over each other to increase the likelihood of encountering novel states. We evaluate the \textit{PIMAEX} reward in conjunction with \textit{PIMAEX-Communication}, a multi-agent training algorithm that employs a communication channel for agents to influence one another. The evaluation is conducted in the \textit{Consume/Explore} environment, a partially observable environment with deceptive rewards, specifically designed to challenge the exploration vs.\ exploitation dilemma and the credit-assignment problem. The results empirically demonstrate that agents using the \textit{PIMAEX} reward with \textit{PIMAEX-Communication} outperform those that do not. 

**Abstract (ZH)**: 近年来，单智能体强化学习中的探索已经得到了广泛研究，但在多智能体强化学习中的探索对应方面，相关研究工作相对较少。为解决这一问题，本研究提出一种受内在好奇性和基于影响奖励研究成果启发的同伴激励奖励函数。该奖励函数名为同伴激励化的多智能体探索（Peer-Incentivized Multi-Agent Exploration, \textit{PIMAEX}），旨在通过鼓励智能体相互施加影响以增加遇到新颖状态的可能性，从而改善多智能体环境中的探索。我们评估了\textit{PIMAEX}奖励与\textit{PIMAEX-Communication}多智能体训练算法的结合效果，其中\textit{PIMAEX-Communication}算法使用通信通道使智能体相互影响。评估是在\textit{Consume/Explore}环境中进行的，这一部分可观察且具有欺骗性奖励的环境，特别设计用于挑战探索与利用的矛盾以及归因问题。实验结果表明，使用\textit{PIMAEX}奖励和\textit{PIMAEX-Communication}算法的智能体表现优于未使用这些算法的智能体。 

---
# ProgCo: Program Helps Self-Correction of Large Language Models 

**Title (ZH)**: ProgCo: 程序辅助大型语言模型的自我修正 

**Authors**: Xiaoshuai Song, Yanan Wu, Weixun Wang, Jiaheng Liu, Wenbo Su, Bo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01264)  

**Abstract**: Self-Correction aims to enable large language models (LLMs) to self-verify and self-refine their initial responses without external feedback. However, LLMs often fail to effectively self-verify and generate correct feedback, further misleading refinement and leading to the failure of self-correction, especially in complex reasoning tasks. In this paper, we propose Program-driven Self-Correction (ProgCo). First, program-driven verification (ProgVe) achieves complex verification logic and extensive validation through self-generated, self-executing verification pseudo-programs. Then, program-driven refinement (ProgRe) receives feedback from ProgVe, conducts dual reflection and refinement on both responses and verification programs to mitigate misleading of incorrect feedback in complex reasoning tasks. Experiments on three instruction-following and mathematical benchmarks indicate that ProgCo achieves effective self-correction, and can be further enhance performance when combined with real program tools. 

**Abstract (ZH)**: 自我修正旨在使大型语言模型（LLMs）能够在没有外部反馈的情况下自我验证和自我完善其初始响应。然而，LLMs 经常无法有效地自我验证并生成正确的反馈，进一步导致调整失误，使得自我修正失败，特别是在复杂推理任务中。本文提出了一种程序驱动的自我修正方法（ProgCo）。首先，程序驱动的验证（ProgVe）利用自动生成并执行的验证伪程序来实现复杂的验证逻辑和广泛的验证。然后，程序驱动的调整（ProgRe）从 ProgVe 获取反馈，对响应和验证程序进行双重反思和调整，以减轻不正确的反馈对复杂推理任务的影响。在三个指令跟随和数学基准测试中的实验表明，ProgCo 能够实现有效的自我修正，并且在与实际程序工具结合使用时可以进一步提高性能。 

---
# Stealthy Backdoor Attack to Real-world Models in Android Apps 

**Title (ZH)**: Android应用中隐秘后门攻击对实际模型的影响 

**Authors**: Jiali Wei, Ming Fan, Xicheng Zhang, Wenjing Jiao, Haijun Wang, Ting Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01263)  

**Abstract**: Powered by their superior performance, deep neural networks (DNNs) have found widespread applications across various domains. Many deep learning (DL) models are now embedded in mobile apps, making them more accessible to end users through on-device DL. However, deploying on-device DL to users' smartphones simultaneously introduces several security threats. One primary threat is backdoor attacks. Extensive research has explored backdoor attacks for several years and has proposed numerous attack approaches. However, few studies have investigated backdoor attacks on DL models deployed in the real world, or they have shown obvious deficiencies in effectiveness and stealthiness. In this work, we explore more effective and stealthy backdoor attacks on real-world DL models extracted from mobile apps. Our main justification is that imperceptible and sample-specific backdoor triggers generated by DNN-based steganography can enhance the efficacy of backdoor attacks on real-world models. We first confirm the effectiveness of steganography-based backdoor attacks on four state-of-the-art DNN models. Subsequently, we systematically evaluate and analyze the stealthiness of the attacks to ensure they are difficult to perceive. Finally, we implement the backdoor attacks on real-world models and compare our approach with three baseline methods. We collect 38,387 mobile apps, extract 89 DL models from them, and analyze these models to obtain the prerequisite model information for the attacks. After identifying the target models, our approach achieves an average of 12.50% higher attack success rate than DeepPayload while better maintaining the normal performance of the models. Extensive experimental results demonstrate that our method enables more effective, robust, and stealthy backdoor attacks on real-world models. 

**Abstract (ZH)**: 得益于其卓越的表现，深度神经网络（DNNs）已在多个领域得到了广泛应用。如今，许多深度学习（DL）模型被嵌入移动应用程序中，从而通过在设备上运行的DL使它们更加易于终端用户使用。然而，将基于设备的DL部署到用户的智能手机中也带来了多种安全威胁。主要威胁之一是后门攻击。多年来，大量的研究已经探索了后门攻击，并提出了众多攻击方法。然而，很少有研究探讨了部署在真实世界中的DL模型的后门攻击，或者是其效果和隐蔽性明显不足。在此工作中，我们探索了真实世界DL模型中提取的移动应用中的更有效地和隐蔽性的后门攻击。我们的主要依据是，基于DNN的隐写术产生的不可感知且样本特定的后门触发器可以增强真实世界模型中后门攻击的效果。我们首先验证了基于隐写术的后门攻击在四种最先进的DNN模型上的有效性。随后，我们系统地评估和分析了攻击的隐蔽性以确保它们难以察觉。最后，我们在真实世界模型上实现后门攻击，并将我们的方法与三种基线方法进行了比较。我们收集了38,387个移动应用，从中提取了89个DL模型，并分析这些模型以获得攻击所需的先验模型信息。在确定目标模型后，我们的方法在攻击成功率方面比DeepPayload平均高出12.50%，同时更好地保持了模型的正常性能。大量的实验结果表明，我们的方法能够使真实世界DL模型中的后门攻击更加有效、稳健且隐蔽。 

---
# Face-Human-Bench: A Comprehensive Benchmark of Face and Human Understanding for Multi-modal Assistants 

**Title (ZH)**: Face-Human-Bench：多模态助手中人脸和人类理解的综合基准 

**Authors**: Lixiong Qin, Shilong Ou, Miaoxuan Zhang, Jiangning Wei, Yuhang Zhang, Xiaoshuai Song, Yuchen Liu, Mei Wang, Weiran Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01243)  

**Abstract**: Faces and humans are crucial elements in social interaction and are widely included in everyday photos and videos. Therefore, a deep understanding of faces and humans will enable multi-modal assistants to achieve improved response quality and broadened application scope. Currently, the multi-modal assistant community lacks a comprehensive and scientific evaluation of face and human understanding abilities. In this paper, we first propose a hierarchical ability taxonomy that includes three levels of abilities. Then, based on this taxonomy, we collect images and annotations from publicly available datasets in the face and human community and build a semi-automatic data pipeline to produce problems for the new benchmark. Finally, the obtained Face-Human-Bench comprises a development set with 900 problems and a test set with 1800 problems, supporting both English and Chinese. We conduct evaluations over 25 mainstream multi-modal large language models (MLLMs) with our Face-Human-Bench, focusing on the correlation between abilities, the impact of the relative position of targets on performance, and the impact of Chain of Thought (CoT) prompting on performance. Moreover, inspired by multi-modal agents, we also explore which abilities of MLLMs need to be supplemented by specialist models. 

**Abstract (ZH)**: 人类和面部在社交互动中至关重要，并广泛出现在日常生活中的照片和视频中。因此，对人类和面部的深刻理解将使多模态助手在响应质量和应用范围上得到增强。目前，多模态助手社区缺乏对面部和人类理解能力的全面和科学评估。本文中，我们首先提出了一种分层能力分类体系，包括三个能力层级。然后，基于此分类体系，我们从面部和人体社区的公开数据集中收集图像和标注，并构建了一种半自动数据处理管道以生成新基准的问题。最后，所获得的Face-Human-Bench包括一个包含900个问题的开发集和一个包含1800个问题的测试集，支持英文和中文。我们使用我们的Face-Human-Bench对25个主流多模态大型语言模型（MLLM）进行了评估，重点关注能力之间的相关性、目标相对位置对性能的影响以及思维链（Chain of Thought，CoT）提示对性能的影响。此外，借鉴多模态代理的研究，我们还探讨了哪些MLLM的能力需要由专门模型补充。 

---
# An Efficient Attention Mechanism for Sequential Recommendation Tasks: HydraRec 

**Title (ZH)**: 高效序列推荐任务的注意力机制：HydraRec 

**Authors**: Uzma Mushtaque  

**Link**: [PDF](https://arxiv.org/pdf/2501.01242)  

**Abstract**: Transformer based models are increasingly being used in various domains including recommender systems (RS). Pretrained transformer models such as BERT have shown good performance at language modelling. With the greater ability to model sequential tasks, variants of Encoder-only models (like BERT4Rec, SASRec etc.) have found success in sequential RS problems. Computing dot-product attention in traditional transformer models has quadratic complexity in sequence length. This is a bigger problem with RS because unlike language models, new items are added to the catalogue every day. User buying history is a dynamic sequence which depends on multiple factors. Recently, various linear attention models have tried to solve this problem by making the model linear in sequence length (token dimensions). Hydra attention is one such linear complexity model proposed for vision transformers which reduces the complexity of attention for both the number of tokens as well as model embedding dimensions. Building on the idea of Hydra attention, we introduce an efficient Transformer based Sequential RS (HydraRec) which significantly improves theoretical complexity of computing attention for longer sequences and bigger datasets while preserving the temporal context. Extensive experiments are conducted to evaluate other linear transformer-based RS models and compared with HydraRec across various evaluation metrics. HydraRec outperforms other linear attention-based models as well as dot-product based attention models when used with causal masking for sequential recommendation next item prediction tasks. For bi-directional models its performance is comparable to the BERT4Rec model with an improvement in running time. 

**Abstract (ZH)**: 基于Transformer的模型在推荐系统（RS）等各个领域中被越来越多地应用。预训练的Transformer模型，如BERT，在语言建模上已经展示了良好的性能。随着其在序列任务建模能力的增强，类似于BERT4Rec和SASRec等编码器-only模型变种在序列推荐问题上取得了成功。在传统Transformer模型中，计算点积注意力的复杂度是序列长度的二次项。在推荐系统中，这是一个更大的问题，因为与语言模型不同，新项目的加入是在每日基础上进行的。用户的购买历史是一个依赖多种因素的动态序列。最近，多种线性注意力模型尝试通过使模型在序列长度上的复杂度为线性来解决这一问题。Hydra注意力是一种为视觉Transformer提出的线性复杂度模型，它不仅降低了注意力机制对于tokens数量的复杂度，还降低了对于模型嵌入维度的复杂度。借鉴Hydra注意力的想法，我们提出了一个高效的时间序列推荐系统（HydraRec）Transformer模型，该模型极大地提高了计算注意力对于更长序列和更大数据集的理论复杂性，同时保留了时间上下文。进行了广泛的实验，评估了其他线性Transformer模型，并与HydraRec在各种评估指标上进行了比较。在使用因果掩码进行序列推荐和下一项预测任务时，HydraRec优于其他基于线性注意力的模型以及基于点积注意力的模型。对于双向模型，其性能与BERT4Rec相当，但在运行时间上有所改进。 

---
# Harnessing Multi-Agent LLMs for Complex Engineering Problem-Solving: A Framework for Senior Design Projects 

**Title (ZH)**: 利用多代理大型语言模型解决复杂工程问题：面向高级设计项目的框架 

**Authors**: Abdullah Mushtaq, Muhammad Rafay Naeem, Ibrahim Ghaznavi, Muhammad Imran Taj, Imran Hashmi, Junaid Qadir  

**Link**: [PDF](https://arxiv.org/pdf/2501.01205)  

**Abstract**: Multi-Agent Large Language Models (LLMs) are gaining significant attention for their ability to harness collective intelligence in complex problem-solving, decision-making, and planning tasks. This aligns with the concept of the wisdom of crowds, where diverse agents contribute collectively to generating effective solutions, making it particularly suitable for educational settings. Senior design projects, also known as capstone or final year projects, are pivotal in engineering education as they integrate theoretical knowledge with practical application, fostering critical thinking, teamwork, and real-world problem-solving skills. In this paper, we explore the use of Multi-Agent LLMs in supporting these senior design projects undertaken by engineering students, which often involve multidisciplinary considerations and conflicting objectives, such as optimizing technical performance while addressing ethical, social, and environmental concerns. We propose a framework where distinct LLM agents represent different expert perspectives, such as problem formulation agents, system complexity agents, societal and ethical agents, or project managers, thus facilitating a holistic problem-solving approach. This implementation leverages standard multi-agent system (MAS) concepts such as coordination, cooperation, and negotiation, incorporating prompt engineering to develop diverse personas for each agent. These agents engage in rich, collaborative dialogues to simulate human engineering teams, guided by principles from swarm AI to efficiently balance individual contributions towards a unified solution. We adapt these techniques to create a collaboration structure for LLM agents, encouraging interdisciplinary reasoning and negotiation similar to real-world senior design projects. To assess the efficacy of this framework, we collected six proposals of engineering and computer science of... 

**Abstract (ZH)**: 多智能体大型语言模型（Multi-Agent Large Language Models, MALLMs）因其在复杂问题解决、决策制定和规划任务中的集体智能应用能力而备受关注。这与“群体智慧”（wisdom of crowds）的概念相吻合，即通过多样化智能体的集体贡献来生成有效的解决方案，因此特别适用于教育环境。高级设计项目，通常被称为毕业设计或大四项目，在工程教育中具有重要意义，因为它们能够将理论知识与实践应用相结合，培养批判性思维、团队合作和解决实际问题的能力。本文探讨了MALLMs在支持工程学生进行高级设计项目中的应用，这些项目往往涉及多学科考虑和相互冲突的目标，如优化技术性能同时解决道德、社会和环境问题。我们提出了一种框架，其中不同的LLM智能体代表不同的专家视角，如问题界定智能体、系统复杂性智能体、社会伦理智能体或项目管理者，从而促进一种全面的问题解决方法。该实施利用了标准的多智能体系统（MAS）概念，如协调、合作和协商，并结合指令工程来为每个智能体开发不同的个性。这些智能体通过丰富的协作对话来模拟人类工程团队，在群体AI的原则指导下，高效地平衡个人贡献以达成统一的解决方案。我们将这些技术应用于构建LLM智能体之间的协作结构，鼓励跨学科的推理和协商，类似于现实世界中的高级设计项目。为了评估该框架的有效性，我们收集了六个工程和计算机科学领域的工程设计提案…… 

---
# Data Augmentation Techniques for Chinese Disease Name Normalization 

**Title (ZH)**: 中文翻译如下，符合学术规范：

中文标题：中文疾病名称规范化中的数据扩增技术

如果需要作为一个完整的句子表达，可以是：

该论文探讨了中文疾病名称规范化中的数据扩增技术。 

**Authors**: Wenqian Cui, Xiangling Fu, Shaohui Liu, Mingjun Gu, Xien Liu, Ji Wu, Irwin King  

**Link**: [PDF](https://arxiv.org/pdf/2501.01195)  

**Abstract**: Disease name normalization is an important task in the medical domain. It classifies disease names written in various formats into standardized names, serving as a fundamental component in smart healthcare systems for various disease-related functions. Nevertheless, the most significant obstacle to existing disease name normalization systems is the severe shortage of training data. Consequently, we present a novel data augmentation approach that includes a series of data augmentation techniques and some supporting modules to help mitigate the problem. Through extensive experimentation, we illustrate that our proposed approach exhibits significant performance improvements across various baseline models and training objectives, particularly in scenarios with limited training data 

**Abstract (ZH)**: 疾病名称规范化是医疗领域的一个重要任务。它将以多种格式书写的疾病名称归类为标准化名称，是各种疾病相关功能的智能医疗系统中的基本组成部分。然而，现有疾病名称规范化系统面临的主要挑战是缺乏足够的训练数据。因此，我们提出了一种新的数据扩增方法，其中包括一系列数据扩增技术及其支持模块，以帮助缓解这一问题。通过广泛的实验，我们表明，我们提出的这种方法在各种基线模型和训练目标下，尤其是在训练数据有限的情况下，显示出显著的性能提升。 

---
# L3D-Pose: Lifting Pose for 3D Avatars from a Single Camera in the Wild 

**Title (ZH)**: L3D-Pose：来自野生单目摄像头的3D avatar姿态估计 

**Authors**: Soumyaratna Debnath, Harish Katti, Shashikant Verma, Shanmuganathan Raman  

**Link**: [PDF](https://arxiv.org/pdf/2501.01174)  

**Abstract**: While 2D pose estimation has advanced our ability to interpret body movements in animals and primates, it is limited by the lack of depth information, constraining its application range. 3D pose estimation provides a more comprehensive solution by incorporating spatial depth, yet creating extensive 3D pose datasets for animals is challenging due to their dynamic and unpredictable behaviours in natural settings. To address this, we propose a hybrid approach that utilizes rigged avatars and the pipeline to generate synthetic datasets to acquire the necessary 3D annotations for training. Our method introduces a simple attention-based MLP network for converting 2D poses to 3D, designed to be independent of the input image to ensure scalability for poses in natural environments. Additionally, we identify that existing anatomical keypoint detectors are insufficient for accurate pose retargeting onto arbitrary avatars. To overcome this, we present a lookup table based on a deep pose estimation method using a synthetic collection of diverse actions rigged avatars perform. Our experiments demonstrate the effectiveness and efficiency of this lookup table-based retargeting approach. Overall, we propose a comprehensive framework with systematically synthesized datasets for lifting poses from 2D to 3D and then utilize this to re-target motion from wild settings onto arbitrary avatars. 

**Abstract (ZH)**: 尽管2D姿态估计在理解动物和灵长类动物的肢体动作方面取得了进展，但由于缺乏深度信息，其应用范围受到限制。3D姿态估计通过引入空间深度提供了更全面的解决方案，但由于动物在自然环境中的动态和不可预测的行为，构建广泛的3D姿态数据集颇具挑战性。为了解决这一问题，我们提出了一种混合方法，该方法利用装备式avatar和流水线生成合成数据集，以获取用于训练所需的3D注释。我们的方法引入了一个基于注意力的MLP网络，用于将2D姿态转换为3D姿态，该网络设计为与输入图像无关，以确保其在自然环境中的可扩展性。此外，我们发现现有的解剖学关键点检测器不足以实现准确的姿态重新定位到任意的avatar。为此，我们提出了一个基于深度姿态估计的查找表方法，该方法利用了一系列多样化动作的装备式avatar的合成集合。我们的实验表明，基于查找表的重新定位方法的有效性和效率。总体而言，我们提出了一种综合框架，该框架系统地生成合成数据集，将2D姿态提升到3D姿态，然后利用这种方法将野外环境中的动作重新定位到任意的avatar上。 

---
# Blind Men and the Elephant: Diverse Perspectives on Gender Stereotypes in Benchmark Datasets 

**Title (ZH)**: 盲人摸象：基准数据集中性别刻板印象的多样化视角 

**Authors**: Mahdi Zakizadeh, Mohammad Taher Pilehvar  

**Link**: [PDF](https://arxiv.org/pdf/2501.01168)  

**Abstract**: The multifaceted challenge of accurately measuring gender stereotypical bias in language models is akin to discerning different segments of a broader, unseen entity. This short paper primarily focuses on intrinsic bias mitigation and measurement strategies for language models, building on prior research that demonstrates a lack of correlation between intrinsic and extrinsic approaches. We delve deeper into intrinsic measurements, identifying inconsistencies and suggesting that these benchmarks may reflect different facets of gender stereotype. Our methodology involves analyzing data distributions across datasets and integrating gender stereotype components informed by social psychology. By adjusting the distribution of two datasets, we achieve a better alignment of outcomes. Our findings underscore the complexity of gender stereotyping in language models and point to new directions for developing more refined techniques to detect and reduce bias. 

**Abstract (ZH)**: 准确测量语言模型中的性别刻板偏见是一个复杂多面的挑战，犹如试图辨认一个更大而未见的整体的不同部分。本文主要集中在语言模型内部偏见的缓解和测量策略上，基于先前研究表明内部和外部方法之间缺乏相关性。我们更深入地探讨了内部测量方法，发现了不一致之处，并建议这些基准可能反映了性别刻板印象的不同方面。我们的方法包括分析不同数据集中的数据分布，并结合社会心理学中有关性别刻板印象的组成部分。通过调整两个数据集的数据分布，我们实现了更好的结果一致性。我们的研究结果突显了语言模型中性别刻板偏见的复杂性，并指出了开发更精细技术以检测和减少偏见的新方向。 

---
# Deep Learning in Palmprint Recognition-A Comprehensive Survey 

**Title (ZH)**: 手掌纹识别中的深度学习：一项综合回顾 

**Authors**: Chengrui Gao, Ziyuan Yang, Wei Jia, Lu Leng, Bob Zhang, Andrew Beng Jin Teoh  

**Link**: [PDF](https://arxiv.org/pdf/2501.01166)  

**Abstract**: Palmprint recognition has emerged as a prominent biometric technology, widely applied in diverse scenarios. Traditional handcrafted methods for palmprint recognition often fall short in representation capability, as they heavily depend on researchers' prior knowledge. Deep learning (DL) has been introduced to address this limitation, leveraging its remarkable successes across various domains. While existing surveys focus narrowly on specific tasks within palmprint recognition-often grounded in traditional methodologies-there remains a significant gap in comprehensive research exploring DL-based approaches across all facets of palmprint recognition. This paper bridges that gap by thoroughly reviewing recent advancements in DL-powered palmprint recognition. The paper systematically examines progress across key tasks, including region-of-interest segmentation, feature extraction, and security/privacy-oriented challenges. Beyond highlighting these advancements, the paper identifies current challenges and uncovers promising opportunities for future research. By consolidating state-of-the-art progress, this review serves as a valuable resource for researchers, enabling them to stay abreast of cutting-edge technologies and drive innovation in palmprint recognition. 

**Abstract (ZH)**: 手掌纹识别作为一种引人注目的生物识别技术，已在各种场景中得到了广泛应用。传统的手工设计方法在手掌纹识别中往往在表征能力上存在不足，因为它们高度依赖研究人员的先验知识。深度学习（DL）已被引入以解决这一局限性，利用其在各个领域的显著成功。尽管现有的综述往往重点关注手掌纹识别中的特定任务——通常基于传统方法——但在DL基础方法在手掌纹识别各个方面进行全面研究方面仍存在显著差距。本文通过全面回顾基于DL的手掌纹识别的最新进展，弥补了这一差距。本文系统地考察了关键任务的进步，包括感兴趣区域分割、特征提取以及安全/隐私方面的挑战。除了突出这些进展外，本文还指出了当前的挑战，并揭示了未来研究的潜在机会。通过整合最新的技术进展，本文的综述为研究人员提供了一项宝贵的资源，使他们能够了解最新的技术动态并推动手掌纹识别领域的创新。 

---
# TexAVi: Generating Stereoscopic VR Video Clips from Text Descriptions 

**Title (ZH)**: TexAVi: 从文本描述生成立体VR视频片段 

**Authors**: Vriksha Srihari, R. Bhavya, Shruti Jayaraman, V. Mary Anita Rajam  

**Link**: [PDF](https://arxiv.org/pdf/2501.01156)  

**Abstract**: While generative models such as text-to-image, large language models and text-to-video have seen significant progress, the extension to text-to-virtual-reality remains largely unexplored, due to a deficit in training data and the complexity of achieving realistic depth and motion in virtual environments. This paper proposes an approach to coalesce existing generative systems to form a stereoscopic virtual reality video from text.
Carried out in three main stages, we start with a base text-to-image model that captures context from an input text. We then employ Stable Diffusion on the rudimentary image produced, to generate frames with enhanced realism and overall quality. These frames are processed with depth estimation algorithms to create left-eye and right-eye views, which are stitched side-by-side to create an immersive viewing experience. Such systems would be highly beneficial in virtual reality production, since filming and scene building often require extensive hours of work and post-production effort.
We utilize image evaluation techniques, specifically Fréchet Inception Distance and CLIP Score, to assess the visual quality of frames produced for the video. These quantitative measures establish the proficiency of the proposed method.
Our work highlights the exciting possibilities of using natural language-driven graphics in fields like virtual reality simulations. 

**Abstract (ZH)**: 尽管文本到图像、大型语言模型和文本到视频生成模型已经取得了显著进展，文本到虚拟现实的扩展仍然 largely unexplored，主要是由于缺乏训练数据以及在虚拟环境中实现逼真深度和运动的复杂性。本文提出了一种方法，将现有的生成系统结合起来，生成从文本到立体虚拟现实视频。

该方法分为三个主要阶段。首先，使用基础的文本到图像模型从输入文本中捕获上下文信息。然后，使用Stable Diffusion对初步生成的图像进行处理，生成具有增强真实感和整体质量的图像帧。接着，使用深度估计算法生成左眼和右眼视图，并将这些视图并排放置，以创建沉浸式观看体验。此类系统在虚拟现实制作中将非常有帮助，因为拍摄和场景构建通常需要大量时间以及后期制作的努力。

我们利用图像评估技术，特别是Fréchet Inception Distance和CLIP Score，评估视频中生成的图像帧的视觉质量。这些量化指标展示了所提出方法的成熟度。
我们的研究突显了使用自然语言驱动的图形技术在虚拟现实模拟等领域中的激动人心的可能性。注意，"largely unexplored"在翻译中调整为“尚未充分探索”，以符合中文的学术表达方式。 

---
# Symmetries-enhanced Multi-Agent Reinforcement Learning 

**Title (ZH)**: 增强对称性多智能体强化学习 

**Authors**: Nikolaos Bousias, Stefanos Pertigkiozoglou, Kostas Daniilidis, George Pappas  

**Link**: [PDF](https://arxiv.org/pdf/2501.01136)  

**Abstract**: Multi-agent reinforcement learning has emerged as a powerful framework for enabling agents to learn complex, coordinated behaviors but faces persistent challenges regarding its generalization, scalability and sample efficiency. Recent advancements have sought to alleviate those issues by embedding intrinsic symmetries of the systems in the policy. Yet, most dynamical systems exhibit little to no symmetries to exploit. This paper presents a novel framework for embedding extrinsic symmetries in multi-agent system dynamics that enables the use of symmetry-enhanced methods to address systems with insufficient intrinsic symmetries, expanding the scope of equivariant learning to a wide variety of MARL problems. Central to our framework is the Group Equivariant Graphormer, a group-modular architecture specifically designed for distributed swarming tasks. Extensive experiments on a swarm of symmetry-breaking quadrotors validate the effectiveness of our approach, showcasing its potential for improved generalization and zero-shot scalability. Our method achieves significant reductions in collision rates and enhances task success rates across a diverse range of scenarios and varying swarm sizes. 

**Abstract (ZH)**: 多智能体强化学习作为一种使智能体能够学习复杂协调行为的强大框架，已经取得了显著进展，但它在泛化能力、可扩展性和样本效率方面仍然面临诸多挑战。近年来的研究努力通过在策略中嵌入系统固有的对称性来缓解这些问题，但大多数动态系统却没有可利用的显著对称性。本文提出了一种新颖的框架，用于在多智能体系统动力学中嵌入外在对称性，从而使增强对称性方法能够处理缺乏固有对称性的系统，从而将守恒学习的应用范围扩展到各种多智能体强化学习（MARL）问题。该框架的关键在于组守恒图卷积机(Group Equivariant Graphormer)，这是一种专门针对分布式群集任务的模块化架构。通过 Swarm 中的对称性打破四旋翼无人机实验，本文验证了该方法的有效性，展示了其在提高泛化能力和零样本可扩展性方面的潜在优势。该方法在多种场景和不同的群集规模下显著降低了碰撞率，提高了任务成功率。 

---
# Missing Data as Augmentation in the Earth Observation Domain: A Multi-View Learning Approach 

**Title (ZH)**: 地球观测领域中缺失数据作为增强的多视图学习方法 

**Authors**: Francisco Mena, Diego Arenas, Andreas Dengel  

**Link**: [PDF](https://arxiv.org/pdf/2501.01132)  

**Abstract**: Multi-view learning (MVL) leverages multiple sources or views of data to enhance machine learning model performance and robustness. This approach has been successfully used in the Earth Observation (EO) domain, where views have a heterogeneous nature and can be affected by missing data. Despite the negative effect that missing data has on model predictions, the ML literature has used it as an augmentation technique to improve model generalization, like masking the input data. Inspired by this, we introduce novel methods for EO applications tailored to MVL with missing views. Our methods integrate the combination of a set to simulate all combinations of missing views as different training samples. Instead of replacing missing data with a numerical value, we use dynamic merge functions, like average, and more complex ones like Transformer. This allows the MVL model to entirely ignore the missing views, enhancing its predictive robustness. We experiment on four EO datasets with temporal and static views, including state-of-the-art methods from the EO domain. The results indicate that our methods improve model robustness under conditions of moderate missingness, and improve the predictive performance when all views are present. The proposed methods offer a single adaptive solution to operate effectively with any combination of available views. 

**Abstract (ZH)**: 多视图学习（MVL）利用多种数据源或视图来增强机器学习模型的性能和稳健性。这种方法已在地球观测（EO）领域成功应用，其中视图具有异质性且可能会受到缺失数据的影响。尽管缺失数据会对模型预测产生负面影响，机器学习文献中却将其用作增强模型泛化能力的一种 augmentation 技术，例如通过屏蔽输入数据。受此启发，我们为适用 MVL 的 EO 应用场景引入了新颖的方法。我们的方法结合了一组视图的组合，以模拟所有缺失视图的所有组合作为不同的训练样本。而不是用数值填补缺失数据，我们使用动态合并函数，如平均值，以及更复杂的函数如 Transformer，这些函数可以让 MVL 模型完全忽略缺失视图，从而增强其预测稳健性。我们在包含时间和静态视图的四个 EO 数据集中进行了实验，包括来自 EO 领域的最先进的方法。实验结果表明，当存在中等程度的缺失数据时，我们的方法可以提高模型的稳健性，并且在所有视图均存在时可以进一步提高预测性能。所提出的方案提供了一个适应性解决方案，可以有效地处理任何可用视图的组合。 

---
# TED: Turn Emphasis with Dialogue Feature Attention for Emotion Recognition in Conversation 

**Title (ZH)**: TED：基于对话特征注意机制的语气强调在对话情绪识别中的应用 

**Authors**: Junya Ono, Hiromi Wakaki  

**Link**: [PDF](https://arxiv.org/pdf/2501.01123)  

**Abstract**: Emotion recognition in conversation (ERC) has been attracting attention by methods for modeling multi-turn contexts. The multi-turn input to a pretraining model implicitly assumes that the current turn and other turns are distinguished during the training process by inserting special tokens into the input sequence. This paper proposes a priority-based attention method to distinguish each turn explicitly by adding dialogue features into the attention mechanism, called Turn Emphasis with Dialogue (TED). It has a priority for each turn according to turn position and speaker information as dialogue features. It takes multi-head self-attention between turn-based vectors for multi-turn input and adjusts attention scores with the dialogue features. We evaluate TED on four typical benchmarks. The experimental results demonstrate that TED has high overall performance in all datasets and achieves state-of-the-art performance on IEMOCAP with numerous turns. 

**Abstract (ZH)**: 对话中的情绪识别（Emotion Recognition in Conversation, ERC）正受到越来越多的关注，特别是在使用方法来建模多轮上下文方面。多轮输入预训练模型在训练过程中隐式地假设当前轮次与其他轮次在输入序列中通过插入特殊标记是被区分开的。本文提出了一种基于优先级的注意力方法，通过将对话特征融入注意力机制中来明确区分每一轮次，这种方法被称为对话强调（Turn Emphasis with Dialogue, TED）。它根据轮次位置和说话人信息等对话特征为每一轮次赋予优先级。TED 方法在基于轮次的向量之间使用多头自注意力机制，并根据对话特征调整注意力分数。我们在四个典型的基准数据集上评估了 TED 方法。实验结果表明，TED 在所有数据集上表现出高水平的整体性能，并且在具有大量轮次的 IEMOCAP 数据集上实现了当前最先进的性能。 

---
# Retrieval-Augmented Dynamic Prompt Tuning for Incomplete Multimodal Learning 

**Title (ZH)**: 基于检索增强的动态提示调优方法用于不完整多模态学习 

**Authors**: Jian Lang, Zhangtao Cheng, Ting Zhong, Fan Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2501.01120)  

**Abstract**: Multimodal learning with incomplete modality is practical and challenging. Recently, researchers have focused on enhancing the robustness of pre-trained MultiModal Transformers (MMTs) under missing modality conditions by applying learnable prompts. However, these prompt-based methods face several limitations: (1) incomplete modalities provide restricted modal cues for task-specific inference, (2) dummy imputation for missing content causes information loss and introduces noise, and (3) static prompts are instance-agnostic, offering limited knowledge for instances with various missing conditions. To address these issues, we propose RAGPT, a novel Retrieval-AuGmented dynamic Prompt Tuning framework. RAGPT comprises three modules: (I) the multi-channel retriever, which identifies similar instances through a within-modality retrieval strategy, (II) the missing modality generator, which recovers missing information using retrieved contexts, and (III) the context-aware prompter, which captures contextual knowledge from relevant instances and generates dynamic prompts to largely enhance the MMT's robustness. Extensive experiments conducted on three real-world datasets show that RAGPT consistently outperforms all competitive baselines in handling incomplete modality problems. The code of our work and prompt-based baselines is available at this https URL. 

**Abstract (ZH)**: 不完整模态下的多模态学习既具实践性又具挑战性。最近，研究人员专注于通过应用可学习的提示来增强预训练多模态变换器（MMTs）在缺失模态条件下的鲁棒性。然而，这些基于提示的方法存在一些限制：（1）不完整的模态提供了有限的模态线索进行任务特定推理，（2）对缺失内容的虚假填充会导致信息丢失并引入噪声，（3）静态提示缺乏实例意识，对于各种缺失条件的实例提供的知识有限。为了解决这些问题，我们提出了RAGPT，一种新颖的检索增强动态提示调优框架。RAGPT 包含三个模块：（I）多通道检索器，通过在模态内检索策略来识别相似实例，（II）缺失模态生成器，使用检索到的上下文恢复缺失信息，（III）上下文感知提示器，从相关实例中捕捉上下文知识并生成动态提示，以大大增强 MMT 的鲁棒性。在三个实际数据集上进行的大量实验表明，RAGPT 一致地优于所有竞争基线，处理不完整模态问题。我们工作的代码和基于提示的基线可以从以下链接获取：this https URL。 

---
# Pruning-based Data Selection and Network Fusion for Efficient Deep Learning 

**Title (ZH)**: 基于剪枝的数据选择与网络融合以实现高效的深度学习 

**Authors**: Humaira Kousar, Hasnain Irshad Bhatti, Jaekyun Moon  

**Link**: [PDF](https://arxiv.org/pdf/2501.01118)  

**Abstract**: Efficient data selection is essential for improving the training efficiency of deep neural networks and reducing the associated annotation costs. However, traditional methods tend to be computationally expensive, limiting their scalability and real-world applicability. We introduce PruneFuse, a novel method that combines pruning and network fusion to enhance data selection and accelerate network training. In PruneFuse, the original dense network is pruned to generate a smaller surrogate model that efficiently selects the most informative samples from the dataset. Once this iterative data selection selects sufficient samples, the insights learned from the pruned model are seamlessly integrated with the dense model through network fusion, providing an optimized initialization that accelerates training. Extensive experimentation on various datasets demonstrates that PruneFuse significantly reduces computational costs for data selection, achieves better performance than baselines, and accelerates the overall training process. 

**Abstract (ZH)**: 高效的数据选择对于提高深度神经网络的训练效率并减少相关的标注成本至关重要。然而，传统的数据选择方法往往计算成本高昂，限制了其可扩展性和实际应用价值。我们提出了一种名为PruneFuse的新方法，该方法结合了剪枝和网络融合技术，以增强数据选择并加速网络训练。在PruneFuse方法中，原始的密集网络首先进行剪枝生成一个较小的代理模型，该模型能够高效地从数据集中选择最具信息性的样本。一旦迭代的数据选择过程选择了足够的样本，通过网络融合将剪枝模型中学到的知识无缝地集成到密集模型中，从而提供了一种优化的初始化方案，能够加速训练过程。在多种数据集上的广泛实验表明，PruneFuse显著降低了数据选择的计算成本，达到优于基准模型的性能，并加速了整体训练过程。 

---
# Robust COVID-19 Detection from Cough Sounds using Deep Neural Decision Tree and Forest: A Comprehensive Cross-Datasets Evaluation 

**Title (ZH)**: 使用深度神经决策树和森林进行咳嗽声音中新冠病毒 robust 检测：跨数据集综合评估 

**Authors**: Rofiqul Islam, Nihad Karim Chowdhury, Muhammad Ashad Kabir  

**Link**: [PDF](https://arxiv.org/pdf/2501.01117)  

**Abstract**: This research presents a robust approach to classifying COVID-19 cough sounds using cutting-edge machine-learning techniques. Leveraging deep neural decision trees and deep neural decision forests, our methodology demonstrates consistent performance across diverse cough sound datasets. We begin with a comprehensive extraction of features to capture a wide range of audio features from individuals, whether COVID-19 positive or negative. To determine the most important features, we use recursive feature elimination along with cross-validation. Bayesian optimization fine-tunes hyper-parameters of deep neural decision tree and deep neural decision forest models. Additionally, we integrate the SMOTE during training to ensure a balanced representation of positive and negative data. Model performance refinement is achieved through threshold optimization, maximizing the ROC-AUC score. Our approach undergoes a comprehensive evaluation in five datasets: Cambridge, Coswara, COUGHVID, Virufy, and the combined Virufy with the NoCoCoDa dataset. Consistently outperforming state-of-the-art methods, our proposed approach yields notable AUC scores of 0.97, 0.98, 0.92, 0.93, 0.99, and 0.99 across the respective datasets. Merging all datasets into a combined dataset, our method, using a deep neural decision forest classifier, achieves an AUC of 0.97. Also, our study includes a comprehensive cross-datasets analysis, revealing demographic and geographic differences in the cough sounds associated with COVID-19. These differences highlight the challenges in transferring learned features across diverse datasets and underscore the potential benefits of dataset integration, improving generalizability and enhancing COVID-19 detection from audio signals. 

**Abstract (ZH)**: 本研究提出了一种稳健的方法，使用先进的机器学习技术对 COVID-19 咳嗽声音进行分类。利用深度神经决策树和深度神经决策森林，我们的方法能够在多种咳嗽声音数据集中展现出一致的良好性能。我们首先进行了全面的特征提取，以捕获个体（无论是 COVID-19 阳性还是阴性）的广泛音频特征。为了确定最重要的特征，我们使用递归特征消除和交叉验证。贝叶斯优化技术进一步调整了深度神经决策树和深度神经决策森林模型的超参数。此外，我们在训练过程中集成了 SMOTE 技术，以确保正负数据的平衡表示。通过优化阈值来提升模型性能，并最大化ROC-AUC分数。我们的方法在五个数据集中进行了全面评估，分别为剑桥（Cambridge）、Coswara、COUGHVID、Virufy 和 NoCoCoDa 集合的组合。在这些数据集上，我们的方法在性能上始终优于最先进的方法，提出的方法在各个数据集上的AUC值分别为0.97、0.98、0.92、0.93、0.99和0.99。将所有数据集合并为一个综合数据集，使用深度神经决策森林分类器，我们的方法实现了0.97的AUC值。此外，我们的研究还包含了一个全面的数据集间分析，揭示了与 COVID-19 相关的咳嗽声音的年龄、性别和地理差异。这些差异突显了在多种数据集之间传输学习特征所面临的挑战，并强调了数据集整合的潜在好处，从而提高了模型的一般化能力，并增强了通过音频信号检测 COVID-19 的效果。 

---
# MalCL: Leveraging GAN-Based Generative Replay to Combat Catastrophic Forgetting in Malware Classification 

**Title (ZH)**: MalCL：利用基于GAN的生成性回放技术对抗恶意软件分类中的灾难性遗忘 

**Authors**: Jimin Park, AHyun Ji, Minji Park, Mohammad Saidur Rahman, Se Eun Oh  

**Link**: [PDF](https://arxiv.org/pdf/2501.01110)  

**Abstract**: Continual Learning (CL) for malware classification tackles the rapidly evolving nature of malware threats and the frequent emergence of new types. Generative Replay (GR)-based CL systems utilize a generative model to produce synthetic versions of past data, which are then combined with new data to retrain the primary model. Traditional machine learning techniques in this domain often struggle with catastrophic forgetting, where a model's performance on old data degrades over time.
In this paper, we introduce a GR-based CL system that employs Generative Adversarial Networks (GANs) with feature matching loss to generate high-quality malware samples. Additionally, we implement innovative selection schemes for replay samples based on the model's hidden representations.
Our comprehensive evaluation across Windows and Android malware datasets in a class-incremental learning scenario -- where new classes are introduced continuously over multiple tasks -- demonstrates substantial performance improvements over previous methods. For example, our system achieves an average accuracy of 55% on Windows malware samples, significantly outperforming other GR-based models by 28%. This study provides practical insights for advancing GR-based malware classification systems. The implementation is available at \url {this https URL}\footnote{The code will be made public upon the presentation of the paper}. 

**Abstract (ZH)**: 以下是将给定内容翻译成中文后的版本，符合学术规范：

持续学习（CL）在恶意软件分类中的应用解决了恶意软件威胁快速演变的性质以及新类型的频繁出现问题。基于生成重放（Generative Replay, GR）的CL系统利用生成模型生成过去的高保真数据的合成版本，然后将这些合成数据与新数据结合以重新训练主模型。该领域中的传统机器学习技术往往难以克服灾难性遗忘问题，即模型在旧数据上的性能会随时间退化。

在本文中，我们介绍了一种基于GR的CL系统，该系统使用生成对抗网络（GANs）和特征匹配损失来生成高质量的恶意软件样本。此外，我们还根据模型的隐藏表示实施了创新的重放样本选择方案。

在Windows和Android恶意软件数据集上对新类增量学习场景（新类不断引入多个任务中）的综合评估表明，与之前的方法相比，我们的系统在性能上取得了显著的提升。例如，我们的系统在Windows恶意软件样本上的平均准确率为55%，显著优于其他基于GR的模型28%。本研究为推动基于GR的恶意软件分类系统的进步提供了实际见解。实施代码可在 \url{此链接} 中获取，并在论文呈现后将公开代码。\footnote{The code will be made public upon the presentation of the paper} 

---
# BatStyler: Advancing Multi-category Style Generation for Source-free Domain Generalization 

**Title (ZH)**: BatStyler：推进无源领域泛化的多类别风格生成 

**Authors**: Xiusheng Xu, Lei Qi, Jingyang Zhou, Xin Geng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01109)  

**Abstract**: Source-Free Domain Generalization (SFDG) aims to develop a model that performs on unseen domains without relying on any source domains. However, the implementation remains constrained due to the unavailability of training data. Research on SFDG focus on knowledge transfer of multi-modal models and style synthesis based on joint space of multiple modalities, thus eliminating the dependency on source domain images. However, existing works primarily work for multi-domain and less-category configuration, but performance on multi-domain and multi-category configuration is relatively poor. In addition, the efficiency of style synthesis also deteriorates in multi-category scenarios. How to efficiently synthesize sufficiently diverse data and apply it to multi-category configuration is a direction with greater practical value. In this paper, we propose a method called BatStyler, which is utilized to improve the capability of style synthesis in multi-category scenarios. BatStyler consists of two modules: Coarse Semantic Generation and Uniform Style Generation modules. The Coarse Semantic Generation module extracts coarse-grained semantics to prevent the compression of space for style diversity learning in multi-category configuration, while the Uniform Style Generation module provides a template of styles that are uniformly distributed in space and implements parallel training. Extensive experiments demonstrate that our method exhibits comparable performance on less-category datasets, while surpassing state-of-the-art methods on multi-category datasets. 

**Abstract (ZH)**: 无源域泛化（Source-Free Domain Generalization, SFDG）的目标是在不依赖任何源域的前提下，开发一个在未见过的领域中也能有效工作的模型。然而，由于缺乏训练数据，其实施受到很大限制。SFDG的研究主要集中在多模态模型的知识迁移以及基于多种模态联合空间的风格合成，以消除对源域图像的依赖。然而，现有工作主要适用于多域和少类配置场景，在多域和多类配置场景中的表现相对较差。此外，在多类配置场景中，风格合成的效率也会下降。如何有效地合成充分多样化的数据并在多类配置中应用，是一个具有更大实际价值的方向。在本文中，我们提出了一种名为BatStyler的方法，旨在提高多类配置中的风格合成能力。BatStyler由两个模块组成：粗粒度语义生成模块和均匀风格生成模块。粗粒度语义生成模块提取粗粒度语义，以防止在多类配置中对风格多样性学习的空间压缩，而均匀风格生成模块提供了一种均匀分布的空间风格模板，并实现了并行训练。大量实验表明，我们的方法在少类数据集上展现出了可比拟的表现，而在多类数据集上的表现则超越了当前最先进的方法。 

---
# MuQ: Self-Supervised Music Representation Learning with Mel Residual Vector Quantization 

**Title (ZH)**: MuQ：基于Mel残差矢量量化的一种自我监督音乐表示学习方法 

**Authors**: Haina Zhu, Yizhi Zhou, Hangting Chen, Jianwei Yu, Ziyang Ma, Rongzhi Gu, Wei Tan, Xie Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01108)  

**Abstract**: Recent years have witnessed the success of foundation models pre-trained with self-supervised learning (SSL) in various music informatics understanding tasks, including music tagging, instrument classification, key detection, and more. In this paper, we propose a self-supervised music representation learning model for music understanding. Distinguished from previous studies adopting random projection or existing neural codec, the proposed model, named MuQ, is trained to predict tokens generated by Mel Residual Vector Quantization (Mel-RVQ). Our Mel-RVQ utilizes residual linear projection structure for Mel spectrum quantization to enhance the stability and efficiency of target extraction and lead to better performance. Experiments in a large variety of downstream tasks demonstrate that MuQ outperforms previous self-supervised music representation models with only 0.9K hours of open-source pre-training data. Scaling up the data to over 160K hours and adopting iterative training consistently improve the model performance. To further validate the strength of our model, we present MuQ-MuLan, a joint music-text embedding model based on contrastive learning, which achieves state-of-the-art performance in the zero-shot music tagging task on the MagnaTagATune dataset. Code and checkpoints are open source in this https URL. 

**Abstract (ZH)**: 近年来，通过自我监督学习（SSL）预训练的基础模型在音乐信息理解任务中取得了成功，包括音乐标记、乐器分类、调式检测等。在本文中，我们提出了一种用于音乐理解的自我监督音乐表示学习模型。不同于之前采用随机投影或现有神经编解码器的研究，我们提出的模型MuQ通过训练来预测由Mel残差向量量化（Mel-RVQ）生成的令牌。Mel-RVQ使用残差线性投影结构进行梅尔谱量化，以增强目标提取的稳定性和效率，并取得更好的性能。在大量下游任务中的实验表明，MuQ仅使用不到0.9K小时的开源预训练数据就能超越之前的自我监督音乐表示模型。通过扩大数据规模至超过160K小时并采用迭代训练，模型性能得到了持续提升。为了进一步验证模型的优势，我们提出了基于对比学习的联合音乐-文本嵌入模型MuQ-MuLan，在MagnaTagATune数据集的零样本音乐标记任务中达到了最先进的性能。代码和检查点在此公开：[链接]。 

---
# learning discriminative features from spectrograms using center loss for speech emotion recognition 

**Title (ZH)**: 使用中心损失从声谱图中学习判别特征用于语音情感识别 

**Authors**: Dongyang Dai, Zhiyong Wu, Runnan Li, Xixin Wu, Jia Jia, Helen Meng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01103)  

**Abstract**: Identifying the emotional state from speech is essential for the natural interaction of the machine with the speaker. However, extracting effective features for emotion recognition is difficult, as emotions are ambiguous. We propose a novel approach to learn discriminative features from variable length spectrograms for emotion recognition by cooperating softmax cross-entropy loss and center loss together. The softmax cross-entropy loss enables features from different emotion categories separable, and center loss efficiently pulls the features belonging to the same emotion category to their center. By combining the two losses together, the discriminative power will be highly enhanced, which leads to network learning more effective features for emotion recognition. As demonstrated by the experimental results, after introducing center loss, both the unweighted accuracy and weighted accuracy are improved by over 3\% on Mel-spectrogram input, and more than 4\% on Short Time Fourier Transform spectrogram input. 

**Abstract (ZH)**: 从语音中识别情感状态对于机器与说话者进行自然交互至关重要。然而，提取有效的情感特征存在难度，因为情感本身往往是模糊的。我们提出了一种新的方法，通过结合使用softmax交叉熵损失和中心损失，从变长频谱图中学习有区分性的特征，以实现情感识别。softmax交叉熵损失使来自不同情感类别的特征变得可分离，中心损失则有效地将相同情感类别的特征拉近其中心点。通过将两种损失结合起来，区分性能力将得到有效增强，从而使网络学习到更有效的用于情感识别的特征。实验结果表明，在使用梅尔频谱图输入时，引入中心损失后，无权重准确率和加权准确率分别提高了超过3%；在使用短时傅里叶变换频谱图输入时，两者分别提高了超过4%。 

---
# Disambiguation of Chinese Polyphones in an End-to-End Framework with Semantic Features Extracted by Pre-trained BERT 

**Title (ZH)**: 使用预训练BERT提取语义特征的端到端框架中多音字消歧研究 

**Authors**: Dongyang Dai, Zhiyong Wu, Shiyin Kang, Xixin Wu, Jia Jia, Dan Su, Dong Yu, Helen Meng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01102)  

**Abstract**: Grapheme-to-phoneme (G2P) conversion serves as an essential component in Chinese Mandarin text-to-speech (TTS) system, where polyphone disambiguation is the core issue. In this paper, we propose an end-to-end framework to predict the pronunciation of a polyphonic character, which accepts sentence containing polyphonic character as input in the form of Chinese character sequence without the necessity of any preprocessing. The proposed method consists of a pre-trained bidirectional encoder representations from Transformers (BERT) model and a neural network (NN) based classifier. The pre-trained BERT model extracts semantic features from a raw Chinese character sequence and the NN based classifier predicts the polyphonic character's pronunciation according to BERT output. In out experiments, we implemented three classifiers, a fully-connected network based classifier, a long short-term memory (LSTM) network based classifier and a Transformer block based classifier. The experimental results compared with the baseline approach based on LSTM demonstrate that, the pre-trained model extracts effective semantic features, which greatly enhances the performance of polyphone disambiguation. In addition, we also explored the impact of contextual information on polyphone disambiguation. 

**Abstract (ZH)**: 汉字到音素（Grapheme-to-phoneme, G2P）转换是中文普通话文本到语音（Text-to-Speech, TTS）系统中的一个关键组件，其中多音字消歧是核心问题。本文提出了一种端到端框架，用于预测多音字的发音，该框架以中文字符序列的形式接受包含多音字的句子作为输入，无需任何预处理。该提出的方法包括一个预训练的双向Transformer编码器（Bidirectional Encoder Representations from Transformers, BERT）模型和一个基于神经网络（Neural Network, NN）的分类器。预训练的BERT模型从原始的中文字符序列中提取语义特征，而基于NN的分类器根据BERT的输出预测多音字的发音。在我们的实验中，我们实现了三个不同的分类器：基于全连接网络的分类器、基于长短期记忆（Long Short-Term Memory, LSTM）网络的分类器以及基于Transformer块的分类器。实验结果与基于LSTM的基准方法进行比较，表明预训练模型可以从原始字符序列中提取有效的语义特征，极大地提高了多音字消歧的性能。此外，我们还探索了上下文信息对多音字消歧的影响。 

---
# MMVA: Multimodal Matching Based on Valence and Arousal across Images, Music, and Musical Captions 

**Title (ZH)**: MMVA：基于 valence 和 arousal 的多模态匹配研究——跨图像、音乐和音乐描述 

**Authors**: Suhwan Choi, Kyu Won Kim, Myungjoo Kang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01094)  

**Abstract**: We introduce Multimodal Matching based on Valence and Arousal (MMVA), a tri-modal encoder framework designed to capture emotional content across images, music, and musical captions. To support this framework, we expand the Image-Music-Emotion-Matching-Net (IMEMNet) dataset, creating IMEMNet-C which includes 24,756 images and 25,944 music clips with corresponding musical captions. We employ multimodal matching scores based on the continuous valence (emotional positivity) and arousal (emotional intensity) values. This continuous matching score allows for random sampling of image-music pairs during training by computing similarity scores from the valence-arousal values across different modalities. Consequently, the proposed approach achieves state-of-the-art performance in valence-arousal prediction tasks. Furthermore, the framework demonstrates its efficacy in various zeroshot tasks, highlighting the potential of valence and arousal predictions in downstream applications. 

**Abstract (ZH)**: 我们介绍了一种基于情感唤起和唤醒的多模态匹配模型（MMVA），这是一个三模态编码框架，旨在跨图像、音乐和音乐字幕捕捉情感内容。为支持这一框架，我们扩展了Image-Music-Emotion-Matching-Net (IMEMNet) 数据集，创建了IMEMNet-C，其中包括24,756张图像和25,944个音乐片段以及对应的音乐字幕。我们采用基于连续情感正性（情感积极程度）和唤醒（情感强度）的多模态匹配分数。这种连续匹配分数允许在训练过程中通过计算不同模态间唤起-唤醒值的相似性分数来进行随机采样图像-音乐配对。因此，所提出的方法在情感唤起-唤醒预测任务中达到了最先进的性能。此外，该框架在各种零样本任务中展示了其有效性，突显了情感正性和唤醒预测在下游应用中的潜力。 

---
# Graph Generative Pre-trained Transformer 

**Title (ZH)**: 图生成预训练变换器 

**Authors**: Xiaohui Chen, Yinkai Wang, Jiaxing He, Yuanqi Du, Soha Hassoun, Xiaolin Xu, Li-Ping Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01073)  

**Abstract**: Graph generation is a critical task in numerous domains, including molecular design and social network analysis, due to its ability to model complex relationships and structured data. While most modern graph generative models utilize adjacency matrix representations, this work revisits an alternative approach that represents graphs as sequences of node set and edge set. We advocate for this approach due to its efficient encoding of graphs and propose a novel representation. Based on this representation, we introduce the Graph Generative Pre-trained Transformer (G2PT), an auto-regressive model that learns graph structures via next-token prediction. To further exploit G2PT's capabilities as a general-purpose foundation model, we explore fine-tuning strategies for two downstream applications: goal-oriented generation and graph property prediction. We conduct extensive experiments across multiple datasets. Results indicate that G2PT achieves superior generative performance on both generic graph and molecule datasets. Furthermore, G2PT exhibits strong adaptability and versatility in downstream tasks from molecular design to property prediction. 

**Abstract (ZH)**: 图生成是众多领域中一项关键任务，包括分子设计和社会网络分析，因其能够建模复杂的相互关系和结构化数据。虽然大多数现代图生成模型采用邻接矩阵表示法，本项工作重新审视了一种替代方法，即将图表示为节点集和边集的序列。我们提倡这种方法，因为它能够高效地编码图结构，并提出了一种新的表示方法。基于这种表示方法，我们引入了图生成预训练变换器（G2PT），这是一种自回归模型，通过下一个图元预测学习图结构。为了进一步发挥G2PT作为通用基础模型的能力，我们探索了针对两种下游应用的微调策略：目标导向生成和图属性预测。我们在多个数据集中进行了广泛实验。结果表明，G2PT在通用图和分子数据集上的生成性能均优于其他方法。此外，G2PT在从分子设计到属性预测的下游任务中显示出强大的适应性和灵活性。 

---
# Risks of Cultural Erasure in Large Language Models 

**Title (ZH)**: 大型语言模型中的文化抹除风险 

**Authors**: Rida Qadri, Aida M. Davani, Kevin Robinson, Vinodkumar Prabhakaran  

**Link**: [PDF](https://arxiv.org/pdf/2501.01056)  

**Abstract**: Large language models are increasingly being integrated into applications that shape the production and discovery of societal knowledge such as search, online education, and travel planning. As a result, language models will shape how people learn about, perceive and interact with global cultures making it important to consider whose knowledge systems and perspectives are represented in models. Recognizing this importance, increasingly work in Machine Learning and NLP has focused on evaluating gaps in global cultural representational distribution within outputs. However, more work is needed on developing benchmarks for cross-cultural impacts of language models that stem from a nuanced sociologically-aware conceptualization of cultural impact or harm. We join this line of work arguing for the need of metricizable evaluations of language technologies that interrogate and account for historical power inequities and differential impacts of representation on global cultures, particularly for cultures already under-represented in the digital corpora. We look at two concepts of erasure: omission: where cultures are not represented at all and simplification i.e. when cultural complexity is erased by presenting one-dimensional views of a rich culture. The former focuses on whether something is represented, and the latter on how it is represented. We focus our analysis on two task contexts with the potential to influence global cultural production. First, we probe representations that a language model produces about different places around the world when asked to describe these contexts. Second, we analyze the cultures represented in the travel recommendations produced by a set of language model applications. Our study shows ways in which the NLP community and application developers can begin to operationalize complex socio-cultural considerations into standard evaluations and benchmarks. 

**Abstract (ZH)**: 大型语言模型 increasingly 越来越多地被集成到搜索引擎、在线教育和旅行规划等影响社会知识生产与发现的应用中。因此，这些模型将塑造人们对于全球文化的认知、感知和互动方式，从而使得考虑模型中所代表的知识体系和视角的重要性日益突显。认识到了这一点的重要性，机器学习和自然语言处理（NLP）领域的研究越来越多地专注于评估模型输出中的全球文化代表性的分布差距。然而，还需更多的研究工作来开发一种基准，以衡量语言模型对不同文化的跨文化影响，该基准应基于一种深度的社会意识概念化框架。我们加入了这一领域的研究，强调了对语言技术进行可量化的评估的必要性，这种评估需要考察和解决历史上的权力不平等以及代表性对不同全球文化的不同影响，特别是那些已经在数字语料中被严重忽视的文化。我们考察了两种类型的抹除概念：遗漏，指某个文化完全没有被代表；简化，当丰富的文化被简化为单一维度的观点时，文化复杂度被抹除。前者关注的是是否被代表，后者关注的是如何被代表。我们将分析集中在两种可能影响全球文化生产的任务情境上。首先，我们探究当语言模型被要求描述世界各地的不同地点时，会如何产生这些地区的代表性描述。其次，我们分析了一个语言模型应用集中产生的旅行推荐中所代表的文化。我们的研究展示了自然语言处理社区和应用开发人员如何将复杂的社会文化考量纳入标准的评估和基准中的方法。 

---
# MSWA: Refining Local Attention with Multi-ScaleWindow Attention 

**Title (ZH)**: MSWA：多尺度窗口注意机制精炼局部注意力 

**Authors**: Yixing Xu, Shivank Nag, Dong Li, Lu Tian, Emad Barsoum  

**Link**: [PDF](https://arxiv.org/pdf/2501.01039)  

**Abstract**: Transformer-based LLMs have achieved exceptional performance across a wide range of NLP tasks. However, the standard self-attention mechanism suffers from quadratic time complexity and linearly increased cache size. Sliding window attention (SWA) solves this problem by restricting the attention range to a fixed-size local context window. Nevertheless, SWA employs a uniform window size for each head in each layer, making it inefficient in capturing context of varying scales. To mitigate this limitation, we propose Multi-Scale Window Attention (MSWA) which applies diverse window sizes across heads and layers in the Transformer. It not only allows for different window sizes among heads within the same layer but also progressively increases window size allocation from shallow to deep layers, thus enabling the model to capture contextual information with different lengths and distances. Experimental results on language modeling and common-sense reasoning tasks substantiate that MSWA outperforms traditional local attention in both effectiveness and efficiency. 

**Abstract (ZH)**: 基于Transformer的大型语言模型（LLM）在广泛的语言处理任务（NLP）中取得了卓越的性能。然而，标准的自注意力机制存在二次时间复杂度和缓存大小线性增加的问题。滑动窗口注意力（SWA）通过将注意力范围限制在一个固定大小的局部上下文窗口内解决了这一问题。尽管如此，SWA 对每个层中的每个头使用统一的窗口大小，使其在捕捉不同尺度的上下文方面不够高效。为了解决这一局限，我们提出了多尺度窗口注意力（MSWA），它在Transformer的各个头和层中应用不同的窗口大小。MSWA 不仅允许同一层内不同头之间有不同的窗口大小，而且还从浅层逐步增加到深层各层中的窗口大小分配，从而使得模型能够捕捉不同长度和距离的上下文信息。在语言建模和常识推理任务上的实验结果表明，MSWA 在有效性和效率方面均优于传统的局部注意力机制。 

---
# MSC-Bench: Benchmarking and Analyzing Multi-Sensor Corruption for Driving Perception 

**Title (ZH)**: MSC-Bench：多传感器故障对驾驶感知影响的基准测试与分析 

**Authors**: Xiaoshuai Hao, Guanqun Liu, Yuting Zhao, Yuheng Ji, Mengchuan Wei, Haimei Zhao, Lingdong Kong, Rong Yin, Yu Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01037)  

**Abstract**: Multi-sensor fusion models play a crucial role in autonomous driving perception, particularly in tasks like 3D object detection and HD map construction. These models provide essential and comprehensive static environmental information for autonomous driving systems. While camera-LiDAR fusion methods have shown promising results by integrating data from both modalities, they often depend on complete sensor inputs. This reliance can lead to low robustness and potential failures when sensors are corrupted or missing, raising significant safety concerns. To tackle this challenge, we introduce the Multi-Sensor Corruption Benchmark (MSC-Bench), the first comprehensive benchmark aimed at evaluating the robustness of multi-sensor autonomous driving perception models against various sensor corruptions. Our benchmark includes 16 combinations of corruption types that disrupt both camera and LiDAR inputs, either individually or concurrently. Extensive evaluations of six 3D object detection models and four HD map construction models reveal substantial performance degradation under adverse weather conditions and sensor failures, underscoring critical safety issues. The benchmark toolkit and affiliated code and model checkpoints have been made publicly accessible. 

**Abstract (ZH)**: 多传感器融合模型在自动驾驶感知中起着关键作用，特别是在三维物体检测和高清地图构建等任务中。这些模型为自动驾驶系统提供了所需的基本且全面的静态环境信息。尽管基于相机和LiDAR的数据融合方法通过整合两种模态的数据展示了良好的效果，但它们往往依赖于完整的传感器输入。这种依赖性可能导致在传感器损坏或缺失时出现低鲁棒性和潜在失败，从而引发重大的安全问题。为应对这一挑战，我们提出了多传感器损坏基准（MSC-Bench），这是第一个旨在评估多传感器自动驾驶感知模型在各种传感器损坏情况下的鲁棒性的综合性基准。该基准包含16种破坏类型组合，这些组合可以破坏相机和LiDAR输入，要么单独破坏，要么同时破坏。对六种三维物体检测模型和四种高清地图构建模型的广泛评估表明，在恶劣天气条件和传感器故障下，性能显著下降，突显了关键的安全问题。基准工具有关的代码和模型检查点已公开提供。 

---
# ValuesRAG: Enhancing Cultural Alignment Through Retrieval-Augmented Contextual Learning 

**Title (ZH)**: ValuesRAG：通过检索增强上下文学习提高文化一致性 

**Authors**: Wonduk Seo, Zonghao Yuan, Yi Bu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01031)  

**Abstract**: Cultural values alignment in Large Language Models (LLMs) is a critical challenge due to their tendency to embed Western-centric biases from training data, leading to misrepresentations and fairness issues in cross-cultural contexts. Recent approaches, such as role-assignment and few-shot learning, often struggle with reliable cultural alignment as they heavily rely on pre-trained knowledge, lack scalability, and fail to capture nuanced cultural values effectively. To address these issues, we propose ValuesRAG, a novel and effective framework that applies Retrieval-Augmented Generation (RAG) with in-context learning to integrate cultural and demographic knowledge dynamically during text generation. Leveraging the World Values Survey (WVS) dataset, ValuesRAG first generates summaries of values for each individual. Subsequently, we curated several representative regional datasets to serve as test datasets and retrieve relevant summaries of values based on demographic features, followed by a reranking step to select the top-k relevant summaries. ValuesRAG consistently outperforms baseline methods, both in the main experiment and in the ablation study where only the values summary was provided, highlighting ValuesRAG's potential to foster culturally aligned AI systems and enhance the inclusivity of AI-driven applications. 

**Abstract (ZH)**: 大语言模型（LLMs）中的文化价值观对齐是一个关键挑战，因为它们倾向于从训练数据中嵌入以西方为中心的偏见，导致跨文化语境中的误表征和公平性问题。近年来，例如角色分配和少量示例学习等方法，在可靠的文化对齐方面往往遇到困难，因为这些方法严重依赖预训练知识，缺乏可扩展性，并且无法有效捕捉细微的文化价值观。为了解决这些问题，我们提出了一种名为ValuesRAG的新型且有效的框架，该框架结合使用检索增强生成（RAG）和上下文学习，在文本生成过程中动态集成文化与人口统计学知识。利用世界价值观调查（WVS）数据集，ValuesRAG 首先为每个个体生成价值观总结。随后，我们编制了一些代表性的区域数据集作为测试数据集，并根据人口统计特征检索相关价值观总结，然后通过重新排名步骤选择前k个最相关的总结。在主要实验和仅提供价值观总结的消融研究中，ValuesRAG 一致优于基线方法，这突显了ValuesRAG 在推动文化对齐的AI系统和增强AI驱动应用包容性方面的潜力。 

---
# Reasoning based on symbolic and parametric knowledge bases: a survey 

**Title (ZH)**: 基于符号知识库和参数知识库的推理：一个综述 

**Authors**: Mayi Xu, Yunfeng Ning, Yongqi Li, Jianhao Chen, Jintao Wen, Yao Xiao, Shen Zhou, Birong Pan, Zepeng Bao, Xin Miao, Hankun Kang, Ke Sun, Tieyun Qian  

**Link**: [PDF](https://arxiv.org/pdf/2501.01030)  

**Abstract**: Reasoning is fundamental to human intelligence, and critical for problem-solving, decision-making, and critical thinking. Reasoning refers to drawing new conclusions based on existing knowledge, which can support various applications like clinical diagnosis, basic education, and financial analysis. Though a good number of surveys have been proposed for reviewing reasoning-related methods, none of them has systematically investigated these methods from the viewpoint of their dependent knowledge base. Both the scenarios to which the knowledge bases are applied and their storage formats are significantly different. Hence, investigating reasoning methods from the knowledge base perspective helps us better understand the challenges and future directions. To fill this gap, this paper first classifies the knowledge base into symbolic and parametric ones. The former explicitly stores information in human-readable symbols, and the latter implicitly encodes knowledge within parameters. Then, we provide a comprehensive overview of reasoning methods using symbolic knowledge bases, parametric knowledge bases, and both of them. Finally, we identify the future direction toward enhancing reasoning capabilities to bridge the gap between human and machine intelligence. 

**Abstract (ZH)**: 推理是人类智能的基础，对于问题解决、决策制定和批判性思维至关重要。推理是指基于现有知识得出新结论的过程，可以支持诸如临床诊断、基础教育和金融分析等各种应用。虽然已经提出了许多文献综述来回顾与推理相关的技术，但这些综述都没有从知识基依赖性的视角系统地分析这些方法。由于知识基应用的场景及其存储格式相差甚远，因此从知识基的视角研究推理方法有助于我们更好地理解面临的挑战和未来发展方向。为填补这一空白，本文首先将知识基分为符号性和参数化两类。前者明确地以人类可读的符号形式存储信息，而后者则隐式地通过参数编码知识。然后，本文对使用符号性知识基、参数化知识基以及两者结合的推理方法进行了全面概述。最后，本文指出了增强推理能力以弥合人类智能与机器智能差距的未来方向。 

---
# Towards Adversarially Robust Deep Metric Learning 

**Title (ZH)**: 面向对抗攻击的鲁棒深度度量学习 

**Authors**: Xiaopeng Ke  

**Link**: [PDF](https://arxiv.org/pdf/2501.01025)  

**Abstract**: Deep Metric Learning (DML) has shown remarkable successes in many domains by taking advantage of powerful deep neural networks. Deep neural networks are prone to adversarial attacks and could be easily fooled by adversarial examples. The current progress on this robustness issue is mainly about deep classification models but pays little attention to DML models. Existing works fail to thoroughly inspect the robustness of DML and neglect an important DML scenario, the clustering-based inference. In this work, we first point out the robustness issue of DML models in clustering-based inference scenarios. We find that, for the clustering-based inference, existing defenses designed DML are unable to be reused and the adaptions of defenses designed for deep classification models cannot achieve satisfactory robustness performance. To alleviate the hazard of adversarial examples, we propose a new defense, the Ensemble Adversarial Training (EAT), which exploits ensemble learning and adversarial training. EAT promotes the diversity of the ensemble, encouraging each model in the ensemble to have different robustness features, and employs a self-transferring mechanism to make full use of the robustness statistics of the whole ensemble in the update of every single model. We evaluate the EAT method on three widely-used datasets with two popular model architectures. The results show that the proposed EAT method greatly outperforms the adaptions of defenses designed for deep classification models. 

**Abstract (ZH)**: 深度度量学习（DML）通过利用强大的深度神经网络已在众多领域取得了显著的成功。然而，深度神经网络容易遭受 adversarial attacks（对抗攻击）并可能被对抗样本轻易欺骗。目前在这个鲁棒性问题上的进展主要集中在深度分类模型上，但对于 DML 模型的关注相对较少。现有的研究未能彻底检查 DML 的鲁棒性，忽视了一个重要的 DML 场景，即基于聚类的推理。在本项工作中，我们首先指出了 DML 模型在基于聚类的推理场景下存在的鲁棒性问题。我们发现，对于基于聚类的推理，现有的针对 DML 的防护措施无法重新使用，而针对深度分类模型设计的防护措施的调整也无法获得满意的鲁棒性表现。为了减轻对抗样本的危害，我们提出了一种新的防护方法——集成对抗性训练（EAT），它利用了集成学习和对抗性训练。EAT 促进了集成的多样性，促使每个多模型在集成中拥有不同的鲁棒性特征，并采用自转移机制充分利用整个集成的鲁棒性统计信息来更新每一个单独的模型。我们使用三种广泛使用的数据集和两种流行的模型架构评估了 EAT 方法。结果表明，所提出的 EAT 方法在鲁棒性表现上显著优于针对深度分类模型设计的防护措施的调整。 

---
# MDSF: Context-Aware Multi-Dimensional Data Storytelling Framework based on Large language Model 

**Title (ZH)**: MDSF：基于大型语言模型的上下文感知多维数据叙事框架

这个标题翻译符合学术规范，保留了原文的含义和结构。其中，“MDSF”被译为“MDSF”，保持了原文的简称形式。“基于大型语言模型”准确地翻译了“based on Large language Model”，确保术语的专业性和准确性。 

**Authors**: Chengze Zhang, Changshan Li, Shiyang Gao  

**Link**: [PDF](https://arxiv.org/pdf/2501.01014)  

**Abstract**: The exponential growth of data and advancements in big data technologies have created a demand for more efficient and automated approaches to data analysis and storytelling. However, automated data analysis systems still face challenges in leveraging large language models (LLMs) for data insight discovery, augmented analysis, and data storytelling. This paper introduces the Multidimensional Data Storytelling Framework (MDSF) based on large language models for automated insight generation and context-aware storytelling. The framework incorporates advanced preprocessing techniques, augmented analysis algorithms, and a unique scoring mechanism to identify and prioritize actionable insights. The use of fine-tuned LLMs enhances contextual understanding and generates narratives with minimal manual intervention. The architecture also includes an agent-based mechanism for real-time storytelling continuation control. Key findings reveal that MDSF outperforms existing methods across various datasets in terms of insight ranking accuracy, descriptive quality, and narrative coherence. The experimental evaluation demonstrates MDSF's ability to automate complex analytical tasks, reduce interpretive biases, and improve user satisfaction. User studies further underscore its practical utility in enhancing content structure, conclusion extraction, and richness of detail. 

**Abstract (ZH)**: 大数据的指数级增长和大数据技术的进步促使对更高效和自动化的数据分析与叙述方法的需求。然而，自动数据分析系统在利用大型语言模型（LLM）进行数据洞察发现、增强分析和数据叙述方面仍面临挑战。本文介绍了一种基于大型语言模型的多维数据叙述框架（MDSF），该框架用于自动化洞察生成和上下文感知叙述。该框架整合了先进的预处理技术、增强分析算法以及独特的评分机制来识别和优先处理可操作的洞察。微调的LLM增强了对上下文的理解，并生成了需要最少手动干预的故事叙述。该架构还包括一种基于代理的机制，用于实时叙述延续控制。关键发现表明，MDSF在各类数据集上的洞察排名准确性、描述质量和叙述连贯性方面优于现有方法。实验评估展示了MDSF自动化复杂分析任务、减少解释偏见和提高用户满意度的能力。用户研究进一步突显了其在增强内容结构、结论提取和细节 richness 方面的实用价值。 

---
# CryptoMamba: Leveraging State Space Models for Accurate Bitcoin Price Prediction 

**Title (ZH)**: CryptoMamba：利用状态空间模型进行准确的比特币价格预测 

**Authors**: Mohammad Shahab Sepehri, Asal Mehradfar, Mahdi Soltanolkotabi, Salman Avestimehr  

**Link**: [PDF](https://arxiv.org/pdf/2501.01010)  

**Abstract**: Predicting Bitcoin price remains a challenging problem due to the high volatility and complex non-linear dynamics of cryptocurrency markets. Traditional time-series models, such as ARIMA and GARCH, and recurrent neural networks, like LSTMs, have been widely applied to this task but struggle to capture the regime shifts and long-range dependencies inherent in the data. In this work, we propose CryptoMamba, a novel Mamba-based State Space Model (SSM) architecture designed to effectively capture long-range dependencies in financial time-series data. Our experiments show that CryptoMamba not only provides more accurate predictions but also offers enhanced generalizability across different market conditions, surpassing the limitations of previous models. Coupled with trading algorithms for real-world scenarios, CryptoMamba demonstrates its practical utility by translating accurate forecasts into financial outcomes. Our findings signal a huge advantage for SSMs in stock and cryptocurrency price forecasting tasks. 

**Abstract (ZH)**: 预测比特币价格仍然是一个具有挑战性的问题，原因在于加密货币市场的高波动性和复杂的非线性动力学特征。传统的时序模型，如ARIMA和GARCH，以及循环神经网络（如LSTM），已被广泛应用于这一任务，但在捕捉数据中的状态转换和长期依赖关系方面力有不逮。在本文中，我们提出了一种新的基于Mamba的状态空间模型（SSM）架构，CryptoMamba，旨在有效地捕捉金融时间序列数据中的长期依赖关系。我们的实验结果表明，CryptoMamba不仅提供了更准确的预测，而且在不同市场条件下具有更强的泛化能力，超越了先前模型的限制。结合适用于现实场景的交易算法，CryptoMamba通过将准确的预测转化为实际的金融结果，展现了其实用价值。我们的研究结果表明，状态空间模型在股票和加密货币价格预测任务中具有巨大优势。 

---
# Deep Reinforcement Learning for Job Scheduling and Resource Management in Cloud Computing: An Algorithm-Level Review 

**Title (ZH)**: 面向云 computing 中作业调度与资源配置的深度强化学习：算法层面的综述 

**Authors**: Yan Gu, Zhaoze Liu, Shuhong Dai, Cong Liu, Ying Wang, Shen Wang, Georgios Theodoropoulos, Long Cheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01007)  

**Abstract**: Cloud computing has revolutionized the provisioning of computing resources, offering scalable, flexible, and on-demand services to meet the diverse requirements of modern applications. At the heart of efficient cloud operations are job scheduling and resource management, which are critical for optimizing system performance and ensuring timely and cost-effective service delivery. However, the dynamic and heterogeneous nature of cloud environments presents significant challenges for these tasks, as workloads and resource availability can fluctuate unpredictably. Traditional approaches, including heuristic and meta-heuristic algorithms, often struggle to adapt to these real-time changes due to their reliance on static models or predefined rules. Deep Reinforcement Learning (DRL) has emerged as a promising solution to these challenges by enabling systems to learn and adapt policies based on continuous observations of the environment, facilitating intelligent and responsive decision-making. This survey provides a comprehensive review of DRL-based algorithms for job scheduling and resource management in cloud computing, analyzing their methodologies, performance metrics, and practical applications. We also highlight emerging trends and future research directions, offering valuable insights into leveraging DRL to advance both job scheduling and resource management in cloud computing. 

**Abstract (ZH)**: 云计算彻底改变了计算资源的供应方式，通过提供可扩展、灵活且按需的服务来满足现代应用的多样化需求。高效云操作的核心在于作业调度和资源管理，这对于优化系统性能和确保及时且成本效益的服务交付至关重要。然而，云环境的动态和异构特性为这些任务带来了重大挑战，因为工作负载和资源可用性可能会不可预测地波动。传统方法，包括启发式和元启发式算法，往往难以适应这些实时变化，因为它们依赖于静态模型或预定义规则。深度强化学习（DRL）作为一种前景光明的解决方案，通过使系统能够根据环境的连续观察来学习和适应策略，促进智能和响应性的决策制定。本综述提供了一种全面的深度强化学习（DRL）算法在云计算中的作业调度和资源管理方面的评审，分析了其方法论、性能指标和实际应用。我们还指出了新兴趋势和未来研究方向，提供了利用DRL推动云计算中作业调度和资源管理进步的宝贵见解。 

---
# FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving 

**Title (ZH)**: FlashInfer：高效可定制的大型语言模型推理加速引擎 

**Authors**: Zihao Ye, Lequn Chen, Ruihang Lai, Wuwei Lin, Yineng Zhang, Stephanie Wang, Tianqi Chen, Baris Kasikci, Vinod Grover, Arvind Krishnamurthy, Luis Ceze  

**Link**: [PDF](https://arxiv.org/pdf/2501.01005)  

**Abstract**: Transformers, driven by attention mechanisms, form the foundation of large language models (LLMs). As these models scale up, efficient GPU attention kernels become essential for high-throughput and low-latency inference. Diverse LLM applications demand flexible and high-performance attention solutions. We present FlashInfer: a customizable and efficient attention engine for LLM serving. FlashInfer tackles KV-cache storage heterogeneity using block-sparse format and composable formats to optimize memory access and reduce redundancy. It also offers a customizable attention template, enabling adaptation to various settings through Just-In-Time (JIT) compilation. Additionally, FlashInfer's load-balanced scheduling algorithm adjusts to dynamism of user requests while maintaining compatibility with CUDAGraph which requires static configuration. FlashInfer have been integrated into leading LLM serving frameworks like SGLang, vLLM and MLC-Engine. Comprehensive kernel-level and end-to-end evaluations demonstrate FlashInfer's ability to significantly boost kernel performance across diverse inference scenarios: compared to state-of-the-art LLM serving solutions, FlashInfer achieve 29-69% inter-token-latency reduction compared to compiler backends for LLM serving benchmark, 28-30% latency reduction for long-context inference, and 13-17% speedup for LLM serving with parallel generation. 

**Abstract (ZH)**: 基于注意力机制的变换器构成了大语言模型（LLMs）的基础。随着这些模型的规模扩大，高效的GPU注意力内核变得对于高吞吐量和低延迟的推理至关重要。多样的LLM应用需要灵活且高性能的注意力解决方案。我们提出了FlashInfer：一种可定制且高效的LLM推理引擎。FlashInfer通过使用块稀疏格式和可组合格式来解决KV缓存存储异构性，从而优化内存访问并减少冗余。此外，它提供了一种可定制的注意力模板，通过即时编译（JIT）技术使得适应各种环境成为可能。另外，FlashInfer的负载均衡调度算法可以适应用户请求的动态变化，并且与需要静态配置的CUDAGraph兼容。FlashInfer已集成到领先的LLM推理框架如SGLang、vLLM和MLC-Engine中。全面的内核级和端到端评估表明，FlashInfer能够显著提升各种推理场景下的内核性能：与最先进的LLM推理解决方案相比，FlashInfer在LLM推理基准测试中实现了29-69%的token间延迟降低；对于长上下文推理，延迟降低了28-30%；对于并行生成的LLM推理，性能提高了13-17%。 

---
# Exploring Information Processing in Large Language Models: Insights from Information Bottleneck Theory 

**Title (ZH)**: 探索大型语言模型中的信息处理：信息瓶颈理论的见解 

**Authors**: Zhou Yang, Zhengyu Qi, Zhaochun Ren, Zhikai Jia, Haizhou Sun, Xiaofei Zhu, Xiangwen Liao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00999)  

**Abstract**: Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of tasks by understanding input information and predicting corresponding outputs. However, the internal mechanisms by which LLMs comprehend input and make effective predictions remain poorly understood. In this paper, we explore the working mechanism of LLMs in information processing from the perspective of Information Bottleneck Theory. We propose a non-training construction strategy to define a task space and identify the following key findings: (1) LLMs compress input information into specific task spaces (e.g., sentiment space, topic space) to facilitate task understanding; (2) they then extract and utilize relevant information from the task space at critical moments to generate accurate predictions. Based on these insights, we introduce two novel approaches: an Information Compression-based Context Learning (IC-ICL) and a Task-Space-guided Fine-Tuning (TS-FT). IC-ICL enhances reasoning performance and inference efficiency by compressing retrieved example information into the task space. TS-FT employs a space-guided loss to fine-tune LLMs, encouraging the learning of more effective compression and selection mechanisms. Experiments across multiple datasets validate the effectiveness of task space construction. Additionally, IC-ICL not only improves performance but also accelerates inference speed by over 40\%, while TS-FT achieves superior results with a minimal strategy adjustment. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已经在广泛的任务中展现出卓越的表现，通过理解输入信息并预测相应输出。然而，LLMs 在理解输入信息和生成有效预测的具体机制仍然知之甚少。本文从信息瓶颈理论的角度探讨了LLMs 在信息处理中的工作机制。我们提出了一种非训练构建策略来定义任务空间，从而发现了以下关键发现：（1）LLMs 将输入信息压缩至特定任务空间（如情感空间、主题空间），以促进任务理解；（2）然后在关键时刻从任务空间中提取和利用相关信息，生成准确的预测。基于这些见解，我们提出了两种新的方法：基于信息压缩的上下文学习（IC-ICL）和任务空间引导的微调（TS-FT）。IC-ICL 通过将检索到的示例信息压缩至任务空间来增强推理性能和推理效率。TS-FT 利用空间引导的损失来微调LLMs，激励学习更有效的压缩和选择机制。多种数据集上的实验验证了任务空间构建的有效性。此外，IC-ICL 不仅提高了性能，还通过超过40%的速度提升了推理速度，而TS-FT 在最小的策略调整下取得了优异的结果。 

---
# Bootstrapped Reward Shaping 

**Title (ZH)**: 有 bootstrap 支持的奖励塑形 

**Authors**: Jacob Adamczyk, Volodymyr Makarenko, Stas Tiomkin, Rahul V. Kulkarni  

**Link**: [PDF](https://arxiv.org/pdf/2501.00989)  

**Abstract**: In reinforcement learning, especially in sparse-reward domains, many environment steps are required to observe reward information. In order to increase the frequency of such observations, "potential-based reward shaping" (PBRS) has been proposed as a method of providing a more dense reward signal while leaving the optimal policy invariant. However, the required "potential function" must be carefully designed with task-dependent knowledge to not deter training performance. In this work, we propose a "bootstrapped" method of reward shaping, termed BSRS, in which the agent's current estimate of the state-value function acts as the potential function for PBRS. We provide convergence proofs for the tabular setting, give insights into training dynamics for deep RL, and show that the proposed method improves training speed in the Atari suite. 

**Abstract (ZH)**: 在强化学习中，尤其是在稀疏奖励环境中，需要大量的环境步来观察奖励信息。为了提高这种观察的频率，“基于潜能的奖励塑形”（PBRS）方法被提出，作为一种在保持最优策略不变的情况下提供更密集奖励信号的方法。然而，所需的“潜能函数”必须根据具体的任务进行精心设计，以避免影响训练性能。在本文中，我们提出了一种“递归”（bootstrapped）类型的奖励塑形方法，称为BSRS（基于递归的奖励塑形），其中代理当前对状态价值函数的估计用作PBRS中的潜能函数。我们为表格设置提供了收敛性证明，提供了深度强化学习训练动态的见解，并展示了所提出的方法在Atari游戏集上提高了训练速度。 

---
# Are LLMs effective psychological assessors? Leveraging adaptive RAG for interpretable mental health screening through psychometric practice 

**Title (ZH)**: 大规模语言模型在心理健康评估中的有效性：利用自适应检索增强技术实现可解释的心理测验筛查 

**Authors**: Federico Ravenda, Seyed Ali Bahrainian, Andrea Raballo, Antonietta Mira, Noriko Kando  

**Link**: [PDF](https://arxiv.org/pdf/2501.00982)  

**Abstract**: In psychological practice, standardized questionnaires serve as essential tools for assessing mental constructs (e.g., attitudes, traits, and emotions) through structured questions (aka items). With the increasing prevalence of social media platforms where users share personal experiences and emotions, researchers are exploring computational methods to leverage this data for rapid mental health screening. In this study, we propose a novel adaptive Retrieval-Augmented Generation (RAG) approach that completes psychological questionnaires by analyzing social media posts. Our method retrieves the most relevant user posts for each question in a psychological survey and uses Large Language Models (LLMs) to predict questionnaire scores in a zero-shot setting. Our findings are twofold. First we demonstrate that this approach can effectively predict users' responses to psychological questionnaires, such as the Beck Depression Inventory II (BDI-II), achieving performance comparable to or surpassing state-of-the-art models on Reddit-based benchmark datasets without relying on training data. Second, we show how this methodology can be generalized as a scalable screening tool, as the final assessment is systematically derived by completing standardized questionnaires and tracking how individual item responses contribute to the diagnosis, aligning with established psychometric practices. 

**Abstract (ZH)**: 在心理学实践中，标准化问卷是通过结构化问题（即项目）来评估心理构念（如态度、特质和情绪）的重要工具。随着社交媒体平台的普及，用户在此平台上分享个人经历和情绪，研究人员正在探索利用这些数据进行快速心理健康筛查的计算方法。在本研究中，我们提出了一种新颖的自适应检索增强生成（RAG）方法，通过分析社交媒体帖子来完成心理学问卷。我们的方法会为心理调查问卷中的每个问题检索最相关的用户帖子，并利用大语言模型（LLMs）在零样本设置下预测问卷得分。我们的发现包括两个方面：首先，我们表明该方法能有效预测用户对心理问卷的反应，如贝克抑郁量表第二版（BDI-II），在基于Reddit的基准数据集上的性能达到了或超越了最先进的模型，且无需依赖训练数据。其次，我们展示了该方法作为可扩展筛查工具的普适性，通过完成标准化问卷并追踪各个项目反应对诊断的影响，系统地得出最终评估结果，这与传统的心理测量实践相一致。 

---
# The Silent Majority: Demystifying Memorization Effect in the Presence of Spurious Correlations 

**Title (ZH)**: 沉默的大多数：解析无效相关性背景下的记忆效应 

**Authors**: Chenyu You, Haocheng Dai, Yifei Min, Jasjeet S. Sekhon, Sarang Joshi, James S. Duncan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00961)  

**Abstract**: Machine learning models often rely on simple spurious features -- patterns in training data that correlate with targets but are not causally related to them, like image backgrounds in foreground classification. This reliance typically leads to imbalanced test performance across minority and majority groups. In this work, we take a closer look at the fundamental cause of such imbalanced performance through the lens of memorization, which refers to the ability to predict accurately on \textit{atypical} examples (minority groups) in the training set but failing in achieving the same accuracy in the testing set. This paper systematically shows the ubiquitous existence of spurious features in a small set of neurons within the network, providing the first-ever evidence that memorization may contribute to imbalanced group performance. Through three experimental sources of converging empirical evidence, we find the property of a small subset of neurons or channels in memorizing minority group information. Inspired by these findings, we articulate the hypothesis: the imbalanced group performance is a byproduct of ``noisy'' spurious memorization confined to a small set of neurons. To further substantiate this hypothesis, we show that eliminating these unnecessary spurious memorization patterns via a novel framework during training can significantly affect the model performance on minority groups. Our experimental results across various architectures and benchmarks offer new insights on how neural networks encode core and spurious knowledge, laying the groundwork for future research in demystifying robustness to spurious correlation. 

**Abstract (ZH)**: 机器学习模型通常依赖于简单的似是而非特征——训练数据中的模式与目标相关但并不因果相关，例如在前景分类中的图像背景。这种依赖通常会导致测试性能在少数群体和多数群体之间不平衡。在本项研究中，我们通过记忆这一概念的核心原因，对这种不平衡表现进行了更深入的剖析。记忆指的是模型能够在训练集中准确预测非典型样本（少数群体），但在测试集中未能达到同样的准确率的能力。本文系统地展示了这样一个现象：在神经网络中一小部分神经元或通道中普遍存在似是而非特征的记忆。这为首次证据显示记忆可能影响少数群体表现提供了证明。通过三个方面实验获得的汇聚实证证据，我们发现一小部分神经元或通道具有记忆少数群体信息的特性。受此发现的启发，我们提出了假设：少数群体表现的不平衡是受限于一小部分神经元的“噪声”似是而非记忆的副产品。为了进一步证实这一假设，我们展示了在训练过程中通过一个新颖的框架消除这些不必要的似是而非记忆模式可以显著影响少数群体的表现。我们在不同架构和基准上的实验结果为神经网络如何编码核心和似是而非知识提供了新的见解，为未来研究揭示对似是而非相关性的鲁棒性奠定了基础。 

---
# Enhancing Early Diabetic Retinopathy Detection through Synthetic DR1 Image Generation: A StyleGAN3 Approach 

**Title (ZH)**: 通过合成DR1图像生成提高早期糖尿病视网膜病变检测：一种StyleGAN3方法 

**Authors**: Sagarnil Das, Pradeep Walia  

**Link**: [PDF](https://arxiv.org/pdf/2501.00954)  

**Abstract**: Diabetic Retinopathy (DR) is a leading cause of preventable blindness. Early detection at the DR1 stage is critical but is hindered by a scarcity of high-quality fundus images. This study uses StyleGAN3 to generate synthetic DR1 images characterized by microaneurysms with high fidelity and diversity. The aim is to address data scarcity and enhance the performance of supervised classifiers. A dataset of 2,602 DR1 images was used to train the model, followed by a comprehensive evaluation using quantitative metrics, including Frechet Inception Distance (FID), Kernel Inception Distance (KID), and Equivariance with respect to translation (EQ-T) and rotation (EQ-R). Qualitative assessments included Human Turing tests, where trained ophthalmologists evaluated the realism of synthetic images. Spectral analysis further validated image quality. The model achieved a final FID score of 17.29, outperforming the mean FID of 21.18 (95 percent confidence interval - 20.83 to 21.56) derived from bootstrap resampling. Human Turing tests demonstrated the model's ability to produce highly realistic images, though minor artifacts near the borders were noted. These findings suggest that StyleGAN3-generated synthetic DR1 images hold significant promise for augmenting training datasets, enabling more accurate early detection of Diabetic Retinopathy. This methodology highlights the potential of synthetic data in advancing medical imaging and AI-driven diagnostics. 

**Abstract (ZH)**: 糖尿病视网膜病变（DR）是可预防失明的主要原因之一。在DR1阶段早期检测至关重要，但由于高质量视网膜 fundus 图像稀缺，该阶段的检测受到阻碍。本研究利用 StyleGAN3 生成具有高保真度和多样性的 DR1 阶段微动脉瘤特征的合成图像，旨在解决数据稀缺性问题，并增强监督分类器的性能。使用包含 2,602 张 DR1 图像的数据集对模型进行训练，随后通过定量评估，包括弗雷歇入神距离（FID）、核入神距离（KID）以及平移（EQ-T）和旋转（EQ-R）等变性评估。定性评估包括由训练有素的眼科医生进行的人类图灵测试，用于评估合成图像的逼真度。进一步的频谱分析验证了图像质量。模型最终获得了 17.29 的 FID 分数，显著优于通过启引导出的 21.18（95% 置信区间 -20.83 至 21.56）的均值 FID。人类图灵测试表明，该模型能够生成高度逼真的图像，尽管在图像边缘附近存在少量伪影。研究结果表明，StyleGAN3 生成的合成 DR1 图像具有显著增强训练数据集的可能性，能够更准确地检测糖尿病视网膜病变。该方法强调了合成数据在推进医学成像和基于 AI 的诊断方面的潜力。 

---
# Incremental Dialogue Management: Survey, Discussion, and Implications for HRI 

**Title (ZH)**: 增量对话管理：综述、讨论及其对人机交互的影响 

**Authors**: Casey Kennington, Pierre Lison, David Schlangen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00953)  

**Abstract**: Efforts towards endowing robots with the ability to speak have benefited from recent advancements in NLP, in particular large language models. However, as powerful as current models have become, they still operate on sentence or multi-sentence level input, not on the word-by-word input that humans operate on, affecting the degree of responsiveness that they offer, which is critical in situations where humans interact with robots using speech. In this paper, we review the literature on interactive systems that operate incrementally (i.e., at the word level or below it). We motivate the need for incremental systems, survey incremental modeling of important aspects of dialogue like speech recognition and language generation. Primary focus is on the part of the system that makes decisions, known as the dialogue manager. We find that there is very little research on incremental dialogue management, offer some requirements for practical incremental dialogue management, and the implications of incremental dialogue for embodied, robotic platforms. 

**Abstract (ZH)**: 赋予机器人说话能力的努力得益于近年来自然语言处理（NLP）的最新进展，尤其是大规模语言模型的进步。然而，尽管当前模型变得非常强大，它们仍主要在句级或段落级上操作，而不是在字级上操作，这影响了它们的响应性，而在人类使用语音与机器人互动的情况下，响应性是非常关键的。本文综述了渐进式工作的交互系统（即在字级或更低层次上工作的系统）。我们探讨了渐进式系统的需求，并对对话识别和语言生成等重要对话方面进行了渐进式建模。主要关注的是做出决策的部分，即对话管理器。我们发现关于渐进式对话管理的研究非常少，并提出了实用的渐进式对话管理的一些要求。此外，我们还讨论了渐进式对话对具备实体形态的机器人平台的影响。 

---
# $\beta$-DQN: Improving Deep Q-Learning By Evolving the Behavior 

**Title (ZH)**: $\beta$-DQN：通过演化行为改进深度Q学习 

**Authors**: Hongming Zhang, Fengshuo Bai, Chenjun Xiao, Chao Gao, Bo Xu, Martin Müller  

**Link**: [PDF](https://arxiv.org/pdf/2501.00913)  

**Abstract**: While many sophisticated exploration methods have been proposed, their lack of generality and high computational cost often lead researchers to favor simpler methods like $\epsilon$-greedy. Motivated by this, we introduce $\beta$-DQN, a simple and efficient exploration method that augments the standard DQN with a behavior function $\beta$. This function estimates the probability that each action has been taken at each state. By leveraging $\beta$, we generate a population of diverse policies that balance exploration between state-action coverage and overestimation bias correction. An adaptive meta-controller is designed to select an effective policy for each episode, enabling flexible and explainable exploration. $\beta$-DQN is straightforward to implement and adds minimal computational overhead to the standard DQN. Experiments on both simple and challenging exploration domains show that $\beta$-DQN outperforms existing baseline methods across a wide range of tasks, providing an effective solution for improving exploration in deep reinforcement learning. 

**Abstract (ZH)**: 尽管已经提出了许多复杂的探索方法，但它们的通用性较差且计算成本较高，这往往使研究者更倾向于使用简单的策略如$\epsilon$-贪心。为此，我们提出了$\beta$-DQN，这是一种简单而高效的探索方法，通过将行为函数$\beta$添加到标准的DQN中来实现。该函数估计在每个状态下每种动作被采取的概率。通过利用$\beta$，我们生成了一组多样化的策略，这些策略在状态-动作覆盖和过度估计偏差校正之间实现了探索的平衡。设计了一个适应性的元控制器来为每个 episode 选择一个有效的策略，从而实现灵活且可解释的探索。$\beta$-DQN 实现起来非常简便，并且对标准 DQN 的计算开销几乎没有影响。实验表明，$\beta$-DQN 在不同难度的探索任务中均能优于现有的基线方法，为改进深度强化学习中的探索提供了有效的解决方案。 

---
# Population Aware Diffusion for Time Series Generation 

**Title (ZH)**: 时间序列生成中的群体意识扩散方法 

**Authors**: Yang Li, Han Meng, Zhenyu Bi, Ingolv T. Urnes, Haipeng Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00910)  

**Abstract**: Diffusion models have shown promising ability in generating high-quality time series (TS) data. Despite the initial success, existing works mostly focus on the authenticity of data at the individual level, but pay less attention to preserving the population-level properties on the entire dataset. Such population-level properties include value distributions for each dimension and distributions of certain functional dependencies (e.g., cross-correlation, CC) between different dimensions. For instance, when generating house energy consumption TS data, the value distributions of the outside temperature and the kitchen temperature should be preserved, as well as the distribution of CC between them. Preserving such TS population-level properties is critical in maintaining the statistical insights of the datasets, mitigating model bias, and augmenting downstream tasks like TS prediction. Yet, it is often overlooked by existing models. Hence, data generated by existing models often bear distribution shifts from the original data. We propose Population-aware Diffusion for Time Series (PaD-TS), a new TS generation model that better preserves the population-level properties. The key novelties of PaD-TS include 1) a new training method explicitly incorporating TS population-level property preservation, and 2) a new dual-channel encoder model architecture that better captures the TS data structure. Empirical results in major benchmark datasets show that PaD-TS can improve the average CC distribution shift score between real and synthetic data by 5.9x while maintaining a performance comparable to state-of-the-art models on individual-level authenticity. 

**Abstract (ZH)**: 扩散模型在生成高质量时间序列（TS）数据方面表现出潜在的能力。尽管初始成果令人鼓舞，现有工作主要关注个体水平数据的真实性，但在整个数据集上保留群体水平属性的关注较少。这些群体水平的属性包括每个维度上的值分布以及不同维度之间某些功能依赖性（例如，交叉相关性CC）的分布。例如，在生成基于房屋能耗的时间序列数据时，室外温度和厨房温度的值分布应被保留，同时还要保留它们之间CC的分布。保留这些TS群体水平的属性对于保持数据集的统计洞察、减轻模型偏差以及增强下游任务（如时间序列预测）至关重要。然而，这一问题经常被现有的模型忽视。因此，现有模型生成的数据经常与原始数据存在分布差异。为此，我们提出了一种新的时间序列生成模型——群体意识扩散（PaD-TS），以更好地保留群体水平属性。PaD-TS的关键创新包括：1）一种新的训练方法，明确地将TS群体水平属性的保留纳入其中；2）一种新的双通道编码器模型架构，更好地捕捉TS数据结构。在主要基准数据集上的实验结果表明，PaD-TS可以将真实数据与合成数据之间的平均CC分布差异分数提高5.9倍，同时保持与当前最先进的模型相当的个体水平的真实性表现。 

---
# Large Language Model Based Multi-Agent System Augmented Complex Event Processing Pipeline for Internet of Multimedia Things 

**Title (ZH)**: 基于大型语言模型的多代理系统增强复杂事件处理管道在多媒体事物互联网中的应用 

**Authors**: Talha Zeeshan, Abhishek Kumar, Susanna Pirttikangas, Sasu Tarkoma  

**Link**: [PDF](https://arxiv.org/pdf/2501.00906)  

**Abstract**: This paper presents the development and evaluation of a Large Language Model (LLM), also known as foundation models, based multi-agent system framework for complex event processing (CEP) with a focus on video query processing use cases. The primary goal is to create a proof-of-concept (POC) that integrates state-of-the-art LLM orchestration frameworks with publish/subscribe (pub/sub) tools to address the integration of LLMs with current CEP systems. Utilizing the Autogen framework in conjunction with Kafka message brokers, the system demonstrates an autonomous CEP pipeline capable of handling complex workflows. Extensive experiments evaluate the system's performance across varying configurations, complexities, and video resolutions, revealing the trade-offs between functionality and latency. The results show that while higher agent count and video complexities increase latency, the system maintains high consistency in narrative coherence. This research builds upon and contributes to, existing novel approaches to distributed AI systems, offering detailed insights into integrating such systems into existing infrastructures. 

**Abstract (ZH)**: 本文介绍了一种基于大规模语言模型（LLM）或称为基础模型的多Agent系统框架，该框架旨在处理复杂事件处理（CEP）中的视频查询应用场景。主要目标是创建一个概念验证（Proof of Concept, POC），将最先进的LLM编排框架与发布/订阅（Pub/Sub）工具集成，以解决将LLM与当前CEP系统集成的问题。通过结合使用Autogen框架和Kafka消息代理，系统展示了能够处理复杂工作流程的自主CEP管道。进行了广泛实验，评估了系统在不同配置、复杂性和视频分辨率下的性能，揭示了功能性和延迟之间的权衡。结果表明，尽管更高的Agent数量和视频复杂性增加了延迟，但系统在叙事连贯性方面保持了高度一致性。该研究建立在并贡献于现有分布式AI系统的新型方法之上，提供了将此类系统集成到现有基础设施中的详细见解。 

---
# Demystifying Online Clustering of Bandits: Enhanced Exploration Under Stochastic and Smoothed Adversarial Contexts 

**Title (ZH)**: 揭开在线集群 bandits 的神秘面纱：在随机和光滑对抗环境下增强探索方法 

**Authors**: Zhuohua Li, Maoli Liu, Xiangxiang Dai, John C.S. Lui  

**Link**: [PDF](https://arxiv.org/pdf/2501.00891)  

**Abstract**: The contextual multi-armed bandit (MAB) problem is crucial in sequential decision-making. A line of research, known as online clustering of bandits, extends contextual MAB by grouping similar users into clusters, utilizing shared features to improve learning efficiency. However, existing algorithms, which rely on the upper confidence bound (UCB) strategy, struggle to gather adequate statistical information to accurately identify unknown user clusters. As a result, their theoretical analyses require several strong assumptions about the "diversity" of contexts generated by the environment, leading to impractical settings, complicated analyses, and poor practical performance. Removing these assumptions has been a long-standing open problem in the clustering of bandits literature. In this paper, we provide two solutions to this open problem. First, following the i.i.d. context generation setting in existing studies, we propose two novel algorithms, UniCLUB and PhaseUniCLUB, which incorporate enhanced exploration mechanisms to accelerate cluster identification. Remarkably, our algorithms require substantially weaker assumptions while achieving regret bounds comparable to prior work. Second, inspired by the smoothed analysis framework, we propose a more practical setting that eliminates the requirement for i.i.d. context generation used in previous studies, thus enhancing the performance of existing algorithms for online clustering of bandits. Our technique can be applied to both graph-based and set-based clustering of bandits frameworks. Extensive evaluations on both synthetic and real-world datasets demonstrate that our proposed algorithms consistently outperform existing approaches. 

**Abstract (ZH)**: 上下文多臂老虎机（Contextual Multi-Armed Bandit, Contextual MAB）问题在序列决策中至关重要。一条研究路线被称为在线群组化多臂老虎机，它通过将具有相似特征的用户分组来扩展上下文多臂老虎机，利用共享特征来提高学习效率。然而，现有的算法依赖于上置信边界（Upper Confidence Bound, UCB）策略，难以收集足够的统计信息以准确识别未知用户群组，这导致它们的理论分析需要关于环境生成的“多样性”假设，这些假设在实际应用中往往不切实际，并且使分析复杂化且实际性能较差。去除这些假设一直是多臂老虎机群组化文献中的一个长期公开问题。在这篇论文中，我们提供了两个解决这一公开问题的方法。首先，沿用现有研究中的独立同分布（i.i.d.）上下文生成设置，我们提出了一种新颖的算法UniCLUB和一类算法PhaseUniCLUB，其中加入了增强的探索机制以加速群组识别。惊人的是，我们的算法在假设上更为宽松，同时仍能实现与现有工作相当的后悔界。其次，受平滑分析框架的启发，我们提出了一种更实用的设置，从而消除了现有研究中对独立同分布上下文生成的假设要求，这有助于提升现有在线群组化多臂老虎机算法的性能。我们的技术适用于基于图和基于集合的群组化多臂老虎机框架。对合成数据集和真实世界数据集进行的广泛评估表明，我们提出的算法在各种场景下始终表现出色，超越了现有的方法。 

---
# Representation in large language models 

**Title (ZH)**: 大型语言模型中的表示学习 

**Authors**: Cameron C. Yetman  

**Link**: [PDF](https://arxiv.org/pdf/2501.00885)  

**Abstract**: The extraordinary success of recent Large Language Models (LLMs) on a diverse array of tasks has led to an explosion of scientific and philosophical theorizing aimed at explaining how they do what they do. Unfortunately, disagreement over fundamental theoretical issues has led to stalemate, with entrenched camps of LLM optimists and pessimists often committed to very different views of how these systems work. Overcoming stalemate requires agreement on fundamental questions, and the goal of this paper is to address one such question, namely: is LLM behavior driven partly by representation-based information processing of the sort implicated in biological cognition, or is it driven entirely by processes of memorization and stochastic table look-up? This is a question about what kind of algorithm LLMs implement, and the answer carries serious implications for higher level questions about whether these systems have beliefs, intentions, concepts, knowledge, and understanding. I argue that LLM behavior is partially driven by representation-based information processing, and then I describe and defend a series of practical techniques for investigating these representations and developing explanations on their basis. The resulting account provides a groundwork for future theorizing about language models and their successors. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在多样性的任务上取得的非凡成功，导致了在解释它们如何执行任务方面产生了大量的科学和哲学理论。不幸的是，对基本理论问题的分歧导致了僵局，LLM 悲观派和乐观派阵营各有其固有的观点，这使得双方之间的共识难以达成。克服僵局需要在基本问题上达成一致，本文的目标是解决这样一个问题：即 LLMS 的行为是否部分地由类似于生物认知的认知表示信息处理驱动，还是完全由记忆和随机查找表的过程驱动？这是一个关于这些系统执行何种算法的问题，而答案对其它高层次问题，例如这些系统是否有信念、意图、概念、知识和理解，具有重要的影响。我认为 LLMS 的行为部分地由认知表示信息处理驱动，并且我将描述并捍卫一系列用于研究这些表示及其基础解释的实用技术。由此得出的描述为未来对语言模型及其后续版本的理论研究奠定了基础。 

---
# Diversity Optimization for Travelling Salesman Problem via Deep Reinforcement Learning 

**Title (ZH)**: 通过深度强化学习优化旅行商问题的多样性 

**Authors**: Qi Li, Zhiguang Cao, Yining Ma, Yaoxin Wu, Yue-Jiao Gong  

**Link**: [PDF](https://arxiv.org/pdf/2501.00884)  

**Abstract**: Existing neural methods for the Travelling Salesman Problem (TSP) mostly aim at finding a single optimal solution. To discover diverse yet high-quality solutions for Multi-Solution TSP (MSTSP), we propose a novel deep reinforcement learning based neural solver, which is primarily featured by an encoder-decoder structured policy. Concretely, on the one hand, a Relativization Filter (RF) is designed to enhance the robustness of the encoder to affine transformations of the instances, so as to potentially improve the quality of the found solutions. On the other hand, a Multi-Attentive Adaptive Active Search (MA3S) is tailored to allow the decoders to strike a balance between the optimality and diversity. Experimental evaluations on benchmark instances demonstrate the superiority of our method over recent neural baselines across different metrics, and its competitive performance against state-of-the-art traditional heuristics with significantly reduced computational time, ranging from $1.3\times$ to $15\times$ faster. Furthermore, we demonstrate that our method can also be applied to the Capacitated Vehicle Routing Problem (CVRP). 

**Abstract (ZH)**: 现有针对旅行推销员问题（TSP）的神经方法主要致力于寻找单一最优解。为发现具有多样性和高质量的多解旅行推销员问题（MSTSP），我们提出了一种基于深层强化学习的新型神经求解器，其主要特点是采用编码器-解码器结构策略。具体而言，一方面，我们设计了一个相对化滤波器（Relativization Filter, RF），以增强编码器对实例仿射变换的鲁棒性，从而提高找到的解的质量。另一方面，我们定制了一种多注意自适应主动搜索（Multi-Attentive Adaptive Active Search, MA3S）策略，以使解码器能够在最优性和多样性之间取得平衡。在基准实例上的实验评估表明，我们的方法在不同指标上优于最近的神经基线，并且在计算时间显著减少的情况下，能够与最先进的传统启发式算法竞争，范围从1.3倍到15倍的加速。此外，我们还展示了我们的方法也可以应用于容量约束车辆路径问题（CVRP）。 

---
# DiffETM: Diffusion Process Enhanced Embedded Topic Model 

**Title (ZH)**: DiffETM：增强扩散过程嵌入主题模型 

**Authors**: Wei Shao, Mingyang Liu, Linqi Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.00862)  

**Abstract**: The embedded topic model (ETM) is a widely used approach that assumes the sampled document-topic distribution conforms to the logistic normal distribution for easier optimization. However, this assumption oversimplifies the real document-topic distribution, limiting the model's performance. In response, we propose a novel method that introduces the diffusion process into the sampling process of document-topic distribution to overcome this limitation and maintain an easy optimization process. We validate our method through extensive experiments on two mainstream datasets, proving its effectiveness in improving topic modeling performance. 

**Abstract (ZH)**: 嵌入主题模型（ETM）是一种广泛使用的方法，该方法假设抽样的文档-主题分布符合逻辑正态分布，以便于优化。然而，这一假设简化了真实的文档-主题分布，限制了模型的性能。为了解决这一问题，我们提出了一种新颖的方法，通过将扩散过程引入文档-主题分布的抽样过程来克服这一限制，并保持优化过程的简便性。我们通过在两个主流数据集上进行广泛的实验来验证该方法，证明其在提高主题建模性能方面具有有效性。 

---
# What is a Social Media Bot? A Global Comparison of Bot and Human Characteristics 

**Title (ZH)**: 什么是社交媒体机器人？全球范围内机器人与人类特征的比较 

**Authors**: Lynnette Hui Xian Ng, Kathleen M. Carley  

**Link**: [PDF](https://arxiv.org/pdf/2501.00855)  

**Abstract**: Chatter on social media is 20% bots and 80% humans. Chatter by bots and humans is consistently different: bots tend to use linguistic cues that can be easily automated while humans use cues that require dialogue understanding. Bots use words that match the identities they choose to present, while humans may send messages that are not related to the identities they present. Bots and humans differ in their communication structure: sampled bots have a star interaction structure, while sampled humans have a hierarchical structure. These conclusions are based on a large-scale analysis of social media tweets across ~200mil users across 7 events. Social media bots took the world by storm when social-cybersecurity researchers realized that social media users not only consisted of humans but also of artificial agents called bots. These bots wreck havoc online by spreading disinformation and manipulating narratives. Most research on bots are based on special-purposed definitions, mostly predicated on the event studied. This article first begins by asking, "What is a bot?", and we study the underlying principles of how bots are different from humans. We develop a first-principle definition of a social media bot. With this definition as a premise, we systematically compare characteristics between bots and humans across global events, and reflect on how the software-programmed bot is an Artificial Intelligent algorithm, and its potential for evolution as technology advances. Based on our results, we provide recommendations for the use and regulation of bots. Finally, we discuss open challenges and future directions: Detect, to systematically identify these automated and potentially evolving bots; Differentiate, to evaluate the goodness of the bot in terms of their content postings and relationship interactions; Disrupt, to moderate the impact of malicious bots. 

**Abstract (ZH)**: 社交媒体上的发言中，有20%是机器人的，而80%是人类的。机器人的发言和人类的发言一直存在显著差异：机器人倾向于使用可以轻易自动化的语言线索，而人类则使用需要对话理解的线索。机器人发送的信息往往与其所选择呈现的身份相符，而人类发送的信息则可能与其所呈现的身份无关。机器人和人类在交流结构上也有所不同：抽样的机器人具有星状交互结构，而抽样的人类则具有层次结构。这些结论基于对全球约2亿用户在7个事件中的社交媒体推文的大规模分析。当社会网络信息安全研究人员意识到社交媒体用户不仅包括人类，还包括称为机器人的计算机代理后，这些机器人在互联网上引起了轩然大波。这些机器人通过传播虚假信息和操控叙事造成了破坏。大多数关于机器人的研究基于特殊定义，这些定义大多取决于所研究的事件。本文首先提出问题：“什么是机器人？”并探讨了机器人与人类之间的根本差异。我们为此类机器人制定了基于原理的基本定义。基于这一定义，我们系统地比较了机器人和人类在世界各地事件中的特征，并反思编程的计算机代理作为人工智能算法的潜力及其随着技术进步的进化可能性。根据我们的研究结果，我们提出了关于机器人使用和监管的建议。最后，我们讨论了开放挑战和未来方向：检测，系统性地识别这些自动且可能进化的机器人；区分，评估机器人在内容发布和关系互动方面的优劣；遏制，减轻恶意机器人的影响。 

---
# Distilled Lifelong Self-Adaptation for Configurable Systems 

**Title (ZH)**: 可配置系统中的精练终身自适应 

**Authors**: Yulong Ye, Tao Chen, Miqing Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.00840)  

**Abstract**: Modern configurable systems provide tremendous opportunities for engineering future intelligent software systems. A key difficulty thereof is how to effectively self-adapt the configuration of a running system such that its performance (e.g., runtime and throughput) can be optimized under time-varying workloads. This unfortunately remains unaddressed in existing approaches as they either overlook the available past knowledge or rely on static exploitation of past knowledge without reasoning the usefulness of information when planning for self-adaptation. In this paper, we tackle this challenging problem by proposing DLiSA, a framework that self-adapts configurable systems. DLiSA comes with two properties: firstly, it supports lifelong planning, and thereby the planning process runs continuously throughout the lifetime of the system, allowing dynamic exploitation of the accumulated knowledge for rapid adaptation. Secondly, the planning for a newly emerged workload is boosted via distilled knowledge seeding, in which the knowledge is dynamically purified such that only useful past configurations are seeded when necessary, mitigating misleading information. Extensive experiments suggest that the proposed DLiSA significantly outperforms state-of-the-art approaches, demonstrating a performance improvement of up to 229% and a resource acceleration of up to 2.22x on generating promising adaptation configurations. All data and sources can be found at our repository: this https URL. 

**Abstract (ZH)**: 现代可配置系统为构建未来的智能软件系统提供了巨大的机会。其中的一个关键难点是如何有效地在运行时自适应调整系统配置，从而使系统性能（例如，运行时间和吞吐量）能够在不断变化的工作负载下得到优化。不幸的是，现有方法对此仍未解决，因为它们要么忽略了可用的过往知识，要么依赖于静态利用过往知识而不推理论证信息的有效性，这对于自适应规划而言是至关重要的。本文通过提出DLiSA框架解决了这一具有挑战性的问题，该框架能够自适应调整可配置系统。DLiSA具有两种特性：首先，它支持终身规划，因此在系统的整个生命周期中，规划过程会持续进行，允许动态利用累积的知识以实现快速适应。其次，当出现新的工作负载时，可以通过精炼知识的播种来提升规划效率，从而动态净化知识，在必要的时候仅播种有用的历史配置，从而减轻误导信息的影响。广泛的实验表明，提出的DLiSA显著优于现有最先进的方法，显示了高达229%的性能提升和高达2.22倍的资源加速。通过我们在存储库中提供的数据和源代码，可以获得这些结果：this https URL。 

---
# LLM+AL: Bridging Large Language Models and Action Languages for Complex Reasoning about Actions 

**Title (ZH)**: 基于LLM和AL的桥梁：大语言模型与操作语言在复杂动作推理中的融合 

**Authors**: Adam Ishay, Joohyung Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.00830)  

**Abstract**: Large Language Models (LLMs) have made significant strides in various intelligent tasks but still struggle with complex action reasoning tasks that require systematic search. To address this limitation, we propose a method that bridges the natural language understanding capabilities of LLMs with the symbolic reasoning strengths of action languages. Our approach, termed "LLM+AL," leverages the LLM's strengths in semantic parsing and commonsense knowledge generation alongside the action language's proficiency in automated reasoning based on encoded knowledge. We compare LLM+AL against state-of-the-art LLMs, including ChatGPT-4, Claude 3 Opus, Gemini Ultra 1.0, and o1-preview, using benchmarks for complex reasoning about actions. Our findings indicate that, although all methods exhibit errors, LLM+AL, with relatively minimal human corrections, consistently leads to correct answers, whereas standalone LLMs fail to improve even with human feedback. LLM+AL also contributes to automated generation of action languages. 

**Abstract (ZH)**: 大语言模型（LLMs）在各种智能任务中取得了显著进展，但在涉及系统搜索的复杂动作推理任务中仍然存在局限性。为了解决这一限制，我们提出了一种方法，将LLMs的自然语言理解能力与动作语言的符号推理优势相结合。我们的方法称为“LLM+AL”，它利用了LLMs在语义解析和常识知识生成方面的优势，同时利用了动作语言基于编码知识进行自动推理的能力。我们使用针对复杂动作推理的基准测试来比较LLM+AL与最新的LLMs，包括ChatGPT-4、Claude 3 Opus、Gemini Ultra 1.0和o1-preview。研究结果表明，尽管所有方法都存在错误，但在最小的人工修正下，LLM+AL始终能够得到正确的答案，而单独的LLMs即使在获得人类反馈后也无法改进。此外，LLM+AL也有助于自动生成动作语言。 

---
# An LLM-Empowered Adaptive Evolutionary Algorithm For Multi-Component Deep Learning Systems 

**Title (ZH)**: 一种基于大规模语言模型的自适应进化算法用于多组件深度学习系统 

**Authors**: Haoxiang Tian, Xingshuo Han, Guoquan Wu, An Guo, Yuan Zhou. Jie Zhang, Shuo Li, Jun Wei, Tianwei Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00829)  

**Abstract**: Multi-objective evolutionary algorithms (MOEAs) are widely used for searching optimal solutions in complex multi-component applications. Traditional MOEAs for multi-component deep learning (MCDL) systems face challenges in enhancing the search efficiency while maintaining the diversity. To combat these, this paper proposes $\mu$MOEA, the first LLM-empowered adaptive evolutionary search algorithm to detect safety violations in MCDL systems. Inspired by the context-understanding ability of Large Language Models (LLMs), $\mu$MOEA promotes the LLM to comprehend the optimization problem and generate an initial population tailed to evolutionary objectives. Subsequently, it employs adaptive selection and variation to iteratively produce offspring, balancing the evolutionary efficiency and diversity. During the evolutionary process, to navigate away from the local optima, $\mu$MOEA integrates the evolutionary experience back into the LLM. This utilization harnesses the LLM's quantitative reasoning prowess to generate differential seeds, breaking away from current optimal solutions. We evaluate $\mu$MOEA in finding safety violations of MCDL systems, and compare its performance with state-of-the-art MOEA methods. Experimental results show that $\mu$MOEA can significantly improve the efficiency and diversity of the evolutionary search. 

**Abstract (ZH)**: 多目标进化算法（MOEAs）被广泛应用于复杂多组件应用中搜索最优解决方案。传统的多组件深度学习（MCDL）系统的MOEAs在提高搜索效率的同时保持多样性方面面临挑战。为了应对这些挑战，本文提出了$\mu$MOEA，这是一种受大型语言模型（LLMs）赋能的自适应演化搜索算法，用于检测MCDL系统的安全性违规行为。受大型语言模型上下文理解能力的启发，$\mu$MOEA促使LLMs理解优化问题，并生成适应进化目标的初始种群。随后，该算法采用自适应选择和变异，逐步产生新的后代，平衡演化效率和多样性。在演化过程中，为了摆脱局部最优解，$\mu$MOEA将演化经验反馈给LLMs。这一过程利用了LLMs的定量推理能力来生成差异性种子，从而打破现有的最优解。我们评估了$\mu$MOEA在其在检测MCDL系统安全性违规行为中的表现，并将其性能与最先进的MOEA方法进行了比较。实验结果表明，$\mu$MOEA显著提高了进化搜索的效率和多样性。 

---
# Embedding Style Beyond Topics: Analyzing Dispersion Effects Across Different Language Models 

**Title (ZH)**: 超越主题的嵌入风格：跨不同语言模型分析分散效应 

**Authors**: Benjamin Icard, Evangelia Zve, Lila Sainero, Alice Breton, Jean-Gabriel Ganascia  

**Link**: [PDF](https://arxiv.org/pdf/2501.00828)  

**Abstract**: This paper analyzes how writing style affects the dispersion of embedding vectors across multiple, state-of-the-art language models. While early transformer models primarily aligned with topic modeling, this study examines the role of writing style in shaping embedding spaces. Using a literary corpus that alternates between topics and styles, we compare the sensitivity of language models across French and English. By analyzing the particular impact of style on embedding dispersion, we aim to better understand how language models process stylistic information, contributing to their overall interpretability. 

**Abstract (ZH)**: 本文分析了书写风格如何影响各种最先进的语言模型中嵌入向量的分布。早期的变压器模型主要与主题建模相关，而本研究则探讨书写风格在塑造嵌入空间中的作用。通过使用一个交替涉及不同主题和风格的文学语料库，我们将比较法语和英语语言模型的敏感性。通过对书写风格对嵌入分布特有影响的分析，本文旨在更好地理解语言模型如何处理风格信息，从而提高它们的整体可解释性。 

---
# LLM-Powered Multi-Agent System for Automated Crypto Portfolio Management 

**Title (ZH)**: 基于LLM的强大多代理系统自动加密货币投资组合管理 

**Authors**: Yichen Luo, Yebo Feng, Jiahua Xu, Paolo Tasca, Yang Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00826)  

**Abstract**: Cryptocurrency investment is inherently difficult due to its shorter history compared to traditional assets, the need to integrate vast amounts of data from various modalities, and the requirement for complex reasoning. While deep learning approaches have been applied to address these challenges, their black-box nature raises concerns about trust and explainability. Recently, large language models (LLMs) have shown promise in financial applications due to their ability to understand multi-modal data and generate explainable decisions. However, single LLM faces limitations in complex, comprehensive tasks such as asset investment. These limitations are even more pronounced in cryptocurrency investment, where LLMs have less domain-specific knowledge in their training corpora.
To overcome these challenges, we propose an explainable, multi-modal, multi-agent framework for cryptocurrency investment. Our framework uses specialized agents that collaborate within and across teams to handle subtasks such as data analysis, literature integration, and investment decision-making for the top 30 cryptocurrencies by market capitalization. The expert training module fine-tunes agents using multi-modal historical data and professional investment literature, while the multi-agent investment module employs real-time data to make informed cryptocurrency investment decisions. Unique intrateam and interteam collaboration mechanisms enhance prediction accuracy by adjusting final predictions based on confidence levels within agent teams and facilitating information sharing between teams. Empirical evaluation using data from November 2023 to September 2024 demonstrates that our framework outperforms single-agent models and market benchmarks in classification, asset pricing, portfolio, and explainability performance. 

**Abstract (ZH)**: 与传统资产相比，数字货币的投资因其较短的历史、需要整合多种数据模态以及复杂推理解释的要求而固有地具有挑战性。尽管深度学习方法已被应用于解决这些挑战，但其黑箱特性引发了关于信任与解释性的担忧。最近，大规模语言模型（LLMs）在金融应用中显示出潜力，这得益于它们能够理解多模态数据并生成可解释的决策。然而，单一的大规模语言模型在处理复杂且综合性的任务，如资产投资时存在局限性。在加密货币投资中，由于训练语料库中的领域特定知识较少，这种局限性更为明显。

为了克服这些挑战，我们提出了一种可用于加密货币投资的可解释、多模态、多智能体框架。该框架中使用专门的智能体，在团队内部及跨团队进行协作，以处理数据分析、文献整合和市值前30位的加密货币的投资决策等子任务。专家训练模块通过多模态历史数据和专业的投资文献对智能体进行微调，而多智能体投资模块则利用实时数据进行加密货币投资决策。团队内部和跨团队的协作机制通过调整智能体团队内的置信水平来提高预测准确性，并促进团队之间的信息共享。通过从2023年11月至2024年9月的数据进行实证评估，我们的框架在分类、资产定价、投资组合和解释性性能方面均优于单一智能体模型和市场基准。 

---
# Decoupling Knowledge and Reasoning in Transformers: A Modular Architecture with Generalized Cross-Attention 

**Title (ZH)**: 将变换器中的知识和推理解耦：一种具有泛化交叉注意力的模块化架构 

**Authors**: Zhenyu Guo, Wenguang Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00823)  

**Abstract**: Transformers have achieved remarkable success across diverse domains, but their monolithic architecture presents challenges in interpretability, adaptability, and scalability. This paper introduces a novel modular Transformer architecture that explicitly decouples knowledge and reasoning through a generalized cross-attention mechanism to a shared knowledge base, specifically designed for effective knowledge retrieval. Critically, we provide a rigorous mathematical derivation demonstrating that the Feed-Forward Network (FFN) in a standard Transformer is a specialized case (a closure) of this generalized cross-attention, revealing its role in implicit knowledge retrieval and validating our design. This theoretical framework provides a new lens for understanding FFNs and lays the foundation for future research exploring enhanced interpretability, adaptability, and scalability, enabling richer interplay with external knowledge bases and other systems. 

**Abstract (ZH)**: 变换器在多种领域取得了显著的成功，但其一体化架构在可解释性、适应性和扩展性方面提出了挑战。本文引入了一种新颖的模块化变换器架构，通过一种泛化的跨注意力机制显式地将知识和推理分离，并专门设计用于有效的知识检索。至关重要的是，我们提供了一种严格的数学推导，证明标准变换器中的前馈网络（FFN）是这种泛化跨注意力机制的一种特例（闭包），揭示了其在隐式知识检索中的作用，并验证了我们的设计。该理论框架为理解FFN提供了一种新的视角，并为未来探索增强的可解释性、适应性和扩展性奠定了基础，从而使得与其他外部知识库和其他系统的交互更加丰富。 

---
# Reasoning-Oriented and Analogy-Based Methods for Locating and Editing in Zero-Shot Event-Relational Reasoning 

**Title (ZH)**: 面向推理和类比的零样本事件关系推理中的定位与编辑方法 

**Authors**: Jingyao Tang, Lishuang Li, Liteng Mi, Haiming Wu, Hongbin Lu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00803)  

**Abstract**: Zero-shot event-relational reasoning is an important task in natural language processing, and existing methods jointly learn a variety of event-relational prefixes and inference-form prefixes to achieve such tasks. However, training prefixes consumes large computational resources and lacks interpretability. Additionally, learning various relational and inferential knowledge inefficiently exploits the connections between tasks. Therefore, we first propose a method for Reasoning-Oriented Locating and Editing (ROLE), which locates and edits the key modules of the language model for reasoning about event relations, enhancing interpretability and also resource-efficiently optimizing the reasoning ability. Subsequently, we propose a method for Analogy-Based Locating and Editing (ABLE), which efficiently exploits the similarities and differences between tasks to optimize the zero-shot reasoning capability. Experimental results show that ROLE improves interpretability and reasoning performance with reduced computational cost. ABLE achieves SOTA results in zero-shot reasoning. 

**Abstract (ZH)**: 零样本事件关系推理是自然语言处理中的一个重要任务，现有方法联合学习各种事件关系前缀和推理形式前缀以达成此类任务。然而，训练这些前缀消耗大量计算资源并且缺乏可解释性。此外，学习各种关系和推理知识未能有效地利用任务间的联系。因此，我们首先提出了一种面向推理的定位与编辑（ROLE）方法，该方法定位并编辑语言模型中用于讨论事件关系的关键模块，增强可解释性，并且以资源高效的方式优化推理能力。随后，我们提出了一种基于类比的定位与编辑（ABLE）方法，该方法有效地利用任务之间的相似性和差异性来优化零样本推理能力。实验结果表明，ROLE在减少计算成本的同时提高了可解释性和推理性能。ABLE在零样本推理方面取得了当前最先进技术的结果。 

---
# Make Shuffling Great Again: A Side-Channel Resistant Fisher-Yates Algorithm for Protecting Neural Networks 

**Title (ZH)**: 再次让洗牌大放异彩：一种抗侧信道的 Fisher-Yates 算法以保护神经网络 

**Authors**: Leonard Puškáč, Marek Benovič, Jakub Breier, Xiaolu Hou  

**Link**: [PDF](https://arxiv.org/pdf/2501.00798)  

**Abstract**: Neural network models implemented in embedded devices have been shown to be susceptible to side-channel attacks (SCAs), allowing recovery of proprietary model parameters, such as weights and biases. There are already available countermeasure methods currently used for protecting cryptographic implementations that can be tailored to protect embedded neural network models. Shuffling, a hiding-based countermeasure that randomly shuffles the order of computations, was shown to be vulnerable to SCA when the Fisher-Yates algorithm is used. In this paper, we propose a design of an SCA-secure version of the Fisher-Yates algorithm. By integrating the masking technique for modular reduction and Blakely's method for modular multiplication, we effectively remove the vulnerability in the division operation that led to side-channel leakage in the original version of the algorithm. We experimentally evaluate that the countermeasure is effective against SCA by implementing a correlation power analysis attack on an embedded neural network model implemented on ARM Cortex-M4. Compared to the original proposal, the memory overhead is $2\times$ the biggest layer of the network, while the time overhead varies from $4\%$ to $0.49\%$ for a layer with $100$ and $1000$ neurons, respectively. 

**Abstract (ZH)**: 嵌入式设备中实现的神经网络模型已被证明对侧通道攻击（SCA）较为敏感，这允许攻击者恢复专有模型参数，如权重和偏差。目前已有用于保护密码学实现的反measure方法，这些方法可以针对保护嵌入式神经网络模型进行调整。Shuffling 是一种基于隐藏的反measure方法，它随机打乱计算的顺序，但当使用 Fisher-Yates 算法时，该方法已被证实对 SCA 漏洞。在本文中，我们提出了 Fisher-Yates 算法的 SCA 安全版本的设计。通过集成模数缩减的掩码技术与 Blakely 方法的模数乘法技术，我们有效地消除了算法原版中因除法操作导致的侧通道泄漏漏洞。通过在 ARM Cortex-M4 上实现嵌入式神经网络模型，并实施相关性功率分析攻击，实验评估证明该反measure措施能够有效地抵御 SCA。与原版提案相比，内存开销是网络最大层的两倍，而对于具有 100 和 1000 个神经元的层，时间开销分别从 4% 变化到 0.49%。 

---
# LENS-XAI: Redefining Lightweight and Explainable Network Security through Knowledge Distillation and Variational Autoencoders for Scalable Intrusion Detection in Cybersecurity 

**Title (ZH)**: LENS-XAI：通过知识蒸馏和变分自编码器重新定义轻量级可解释网络安全性以实现可扩展的网络安全入侵检测 

**Authors**: Muhammet Anil Yagiz, Polat Goktas  

**Link**: [PDF](https://arxiv.org/pdf/2501.00790)  

**Abstract**: The rapid proliferation of Industrial Internet of Things (IIoT) systems necessitates advanced, interpretable, and scalable intrusion detection systems (IDS) to combat emerging cyber threats. Traditional IDS face challenges such as high computational demands, limited explainability, and inflexibility against evolving attack patterns. To address these limitations, this study introduces the Lightweight Explainable Network Security framework (LENS-XAI), which combines robust intrusion detection with enhanced interpretability and scalability. LENS-XAI integrates knowledge distillation, variational autoencoder models, and attribution-based explainability techniques to achieve high detection accuracy and transparency in decision-making. By leveraging a training set comprising 10% of the available data, the framework optimizes computational efficiency without sacrificing performance. Experimental evaluation on four benchmark datasets: Edge-IIoTset, UKM-IDS20, CTU-13, and NSL-KDD, demonstrates the framework's superior performance, achieving detection accuracies of 95.34%, 99.92%, 98.42%, and 99.34%, respectively. Additionally, the framework excels in reducing false positives and adapting to complex attack scenarios, outperforming existing state-of-the-art methods. Key strengths of LENS-XAI include its lightweight design, suitable for resource-constrained environments, and its scalability across diverse IIoT and cybersecurity contexts. Moreover, the explainability module enhances trust and transparency, critical for practical deployment in dynamic and sensitive applications. This research contributes significantly to advancing IDS by addressing computational efficiency, feature interpretability, and real-world applicability. Future work could focus on extending the framework to ensemble AI systems for distributed environments, further enhancing its robustness and adaptability. 

**Abstract (ZH)**: 工业互联网（IIoT）系统的迅速普及亟需高效、可解释和可扩展的入侵检测系统（IDS）以应对新兴的网络安全威胁。传统的IDS面临高计算需求、解释性有限和对不断 evolution 的攻击模式缺乏灵活性等挑战。为解决这些限制，本研究引入了轻量级可解释网络安保框架（LENS-XAI），该框架结合了稳健的入侵检测和增强的可解释性和可扩展性。LENS-XAI通过结合知识蒸馏、变分自编码器模型和基于归因的可解释性技术，实现了高检测准确性和决策过程的透明度。通过利用数据集中 10% 的数据作为训练集，该框架在优化计算效率的同时不牺牲性能。在四个基准数据集 Edge-IIoTset、UKM-IDS20、CTU-13 和 NSL-KDD 上进行的实验评估表明，框架具有优越的性能，分别实现了 95.34%、99.92%、98.42% 和 99.34% 的检测准确率。此外，该框架在降低误报率和适应复杂攻击场景方面表现出色，优于现有最先进的方法。LENS-XAI 的主要优点包括其轻量级设计，适用于资源受限的环境，以及在多样化 IIoT 和网络安全场景中的可扩展性。此外，解释性模块增强了信任和透明度，这对于在动态和敏感应用中的实际部署至关重要。本研究在提高 IDS 的计算效率、特征可解释性和实际应用场景方面做出了重要贡献。未来的工作可以着眼于将该框架扩展到分布式环境中的集成 AI 系统，进一步增强其稳健性和适应性。 

---
# REM: A Scalable Reinforced Multi-Expert Framework for Multiplex Influence Maximization 

**Title (ZH)**: REM：一种可扩展的强化多专家框架，用于多层影响力最大化 

**Authors**: Huyen Nguyen, Hieu Dam, Nguyen Do, Cong Tran, Cuong Pham  

**Link**: [PDF](https://arxiv.org/pdf/2501.00779)  

**Abstract**: In social online platforms, identifying influential seed users to maximize influence spread is a crucial as it can greatly diminish the cost and efforts required for information dissemination. While effective, traditional methods for Multiplex Influence Maximization (MIM) have reached their performance limits, prompting the emergence of learning-based approaches. These novel methods aim for better generalization and scalability for more sizable graphs but face significant challenges, such as (1) inability to handle unknown diffusion patterns and (2) reliance on high-quality training samples. To address these issues, we propose the Reinforced Expert Maximization framework (REM). REM leverages a Propagation Mixture of Experts technique to encode dynamic propagation of large multiplex networks effectively in order to generate enhanced influence propagation. Noticeably, REM treats a generative model as a policy to autonomously generate different seed sets and learn how to improve them from a Reinforcement Learning perspective. Extensive experiments on several real-world datasets demonstrate that REM surpasses state-of-the-art methods in terms of influence spread, scalability, and inference time in influence maximization tasks. 

**Abstract (ZH)**: 在社交在线平台上，识别潜在的种子用户以最大化信息传播的影响范围是至关重要的，因为这可以显著减少信息传播所需的成本和努力。尽管传统的方法在多层影响最大化（MIM）方面非常有效，但它们已经达到了性能极限，从而推动了基于学习的方法的出现。这些新颖的方法旨在更好地泛化和扩展以适用于更大的图结构，但它们面临着重大挑战，例如（1）无法处理未知的传播模式和（2）依赖高质量的训练样本。为了解决这些问题，我们提出了一种强化专家最大化框架（REM）。REM 利用传播混合专家技术有效编码大规模多层网络中的动态传播，从而生成增强的影响传播。值得注意的是，REM 将生成模型视为策略，用于自主生成不同的种子集，并从强化学习的角度学习如何改进它们。在多个实际数据集上的广泛实验表明，在影响最大化任务中，REM 在影响传播范围、可扩展性和推理时间方面均超过了现有最先进的方法。 

---
# Revisiting Graph Neural Networks on Graph-level Tasks: Comprehensive Experiments, Analysis, and Improvements 

**Title (ZH)**: 重新审视图神经网络在图级任务中的应用：全面的实验、分析与改进 

**Authors**: Haoyang Li, Yuming Xu, Chen Jason Zhang, Alexander Zhou, Lei Chen, Qing Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.00773)  

**Abstract**: Graphs are essential data structures for modeling complex interactions in domains such as social networks, molecular structures, and biological systems. Graph-level tasks, which predict properties or classes for the entire graph, are critical for applications, such as molecular property prediction and subgraph counting. Graph Neural Networks (GNNs) have shown promise in these tasks, but their evaluations are often limited to narrow datasets, tasks, and inconsistent experimental setups, restricting their generalizability. To address these limitations, we propose a unified evaluation framework for graph-level GNNs. This framework provides a standardized setting to evaluate GNNs across diverse datasets, various graph tasks (e.g., graph classification and regression), and challenging scenarios, including noisy, imbalanced, and few-shot graphs. Additionally, we propose a novel GNN model with enhanced expressivity and generalization capabilities. Specifically, we enhance the expressivity of GNNs through a $k$-path rooted subgraph approach, enabling the model to effectively count subgraphs (e.g., paths and cycles). Moreover, we introduce a unified graph contrastive learning algorithm for graphs across diverse domains, which adaptively removes unimportant edges to augment graphs, thereby significantly improving generalization performance. Extensive experiments demonstrate that our model achieves superior performance against fourteen effective baselines across twenty-seven graph datasets, establishing it as a robust and generalizable model for graph-level tasks. 

**Abstract (ZH)**: 图是用于建模社交网络、分子结构和生物系统中复杂交互的重要数据结构。图层面的任务涉及预测整个图的性质或类别，这对于分子性质预测和子图计数等应用至关重要。图神经网络（GNNs）在这些任务中展现出了潜力，但其评估通常局限于狭窄的数据集、任务以及不一致的实验设置，从而限制了它们的通用性。为了解决这些限制，我们提出了一种统一的图层面GNN评估框架。该框架提供了一个标准化的环境，用于在多种数据集、不同图任务（如图分类和回归）以及具有挑战性的场景（包括嘈杂的、不平衡的和少量样本的图）下评估GNNs。此外，我们还提出了一种具有增强表征能力和泛化能力的新型GNN模型。具体而言，我们通过$k$-路径根子图方法增强了GNNs的表征能力，使模型能够有效地计数子图（例如路径和环）。另外，我们引入了一种统一的图对比学习算法，适用于不同领域的图，该算法自适应地移除不重要的边以增强图，从而显著提高了泛化性能。广泛的实验表明，我们的模型在二十个图数据集上优于十四种有效的基线模型，确立了其作为图层面任务的稳健和通用模型的地位。 

---
# Enhancing Transformers for Generalizable First-Order Logical Entailment 

**Title (ZH)**: 增强变压器以提高泛化一阶逻辑蕴含能力 

**Authors**: Tianshi Zheng, Jiazheng Wang, Zihao Wang, Jiaxin Bai, Hang Yin, Zheye Deng, Yangqiu Song, Jianxin Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.00759)  

**Abstract**: Transformers, as a fundamental deep learning architecture, have demonstrated remarkable capabilities in reasoning. This paper investigates the generalizable first-order logical reasoning ability of transformers with their parameterized knowledge and explores ways to improve it. The first-order reasoning capability of transformers is assessed through their ability to perform first-order logical entailment, which is quantitatively measured by their performance in answering knowledge graph queries. We establish connections between (1) two types of distribution shifts studied in out-of-distribution generalization and (2) the unseen knowledge and query settings discussed in the task of knowledge graph query answering, enabling a characterization of fine-grained generalizability. Results on our comprehensive dataset show that transformers outperform previous methods specifically designed for this task and provide detailed empirical evidence on the impact of input query syntax, token embedding, and transformer architectures on the reasoning capability of transformers. Interestingly, our findings reveal a mismatch between positional encoding and other design choices in transformer architectures employed in prior practices. This discovery motivates us to propose a more sophisticated, logic-aware architecture, TEGA, to enhance the capability for generalizable first-order logical entailment in transformers. 

**Abstract (ZH)**: 作为基本的深度学习架构，Transformer 展示出了在推理方面显著的能力。本文研究了配备参数化知识的 Transformer 的一般化一阶逻辑推理能力，并探讨了提升该能力的方法。通过评估 Transformer 完成一阶逻辑蕴含的能力，进而定量地测量其在回答知识图谱查询方面的表现，来评估 Transformer 的一阶推理能力。我们建立了两种类型分布偏移在领域外泛化中研究的联系与知识图谱查询任务中未见知识和查询设置的联系，从而使细致的泛化能力得以刻画。我们的综合数据集上的结果显示，Transformer 在该任务上优于专门为此任务设计的其他方法，并提供了关于输入查询语法、标记嵌入以及 Transformer 架构对 Transformer 推理能力影响的详实实证证据。有趣的是，我们的研究发现早期实践中所使用的 Transformer 架构中的位置编码与其他设计选择之间存在不匹配。这一发现促使我们提出了更复杂的、意识逻辑的架构 TEGA，以增强 Transformer 在一般化一阶逻辑蕴含方面的能力。 

---
# An AI-powered Bayesian generative modeling approach for causal inference in observational studies 

**Title (ZH)**: 基于人工智能的贝叶斯生成建模方法在观察性研究中的因果推断 

**Authors**: Qiao Liu, Wing Hung Wong  

**Link**: [PDF](https://arxiv.org/pdf/2501.00755)  

**Abstract**: Causal inference in observational studies with high-dimensional covariates presents significant challenges. We introduce CausalBGM, an AI-powered Bayesian generative modeling approach that captures the causal relationship among covariates, treatment, and outcome variables. The core innovation of CausalBGM lies in its ability to estimate the individual treatment effect (ITE) by learning individual-specific distributions of a low-dimensional latent feature set (e.g., latent confounders) that drives changes in both treatment and outcome. This approach not only effectively mitigates confounding effects but also provides comprehensive uncertainty quantification, offering reliable and interpretable causal effect estimates at the individual level. CausalBGM adopts a Bayesian model and uses a novel iterative algorithm to update the model parameters and the posterior distribution of latent features until convergence. This framework leverages the power of AI to capture complex dependencies among variables while adhering to the Bayesian principles. Extensive experiments demonstrate that CausalBGM consistently outperforms state-of-the-art methods, particularly in scenarios with high-dimensional covariates and large-scale datasets. Its Bayesian foundation ensures statistical rigor, providing robust and well-calibrated posterior intervals. By addressing key limitations of existing methods, CausalBGM emerges as a robust and promising framework for advancing causal inference in modern applications in fields such as genomics, healthcare, and social sciences. CausalBGM is maintained at the website this https URL. 

**Abstract (ZH)**: 在观察性研究中，高维协变量下的因果推断面临着显著的挑战。我们引入了CausalBGM，这是一种基于AI的贝叶斯生成建模方法，能够捕捉协变量、处理和结果变量之间的因果关系。CausalBGM的核心创新在于其能够通过学习驱动处理和结果变化的低维潜在特征集（例如潜在混杂因素）的个体特异性分布来估计个体治疗效果（ITE）。这种方法不仅有效地缓解了混杂效应，还提供了全面的不确定性量化，提供了可靠且可解释的个体层面因果效应估计。CausalBGM采用贝叶斯模型，并使用一种新型迭代算法来更新模型参数和潜在特征的后验分布，直至收敛。该框架结合了AI的力量来捕捉变量间的复杂依赖关系，同时遵循贝叶斯原则。大量实验表明，CausalBGM在高维协变量和大规模数据集场景中始终优于最先进的方法。其贝叶斯基础确保了统计严谨性，提供了稳健且校准良好的后验区间。通过解决现有方法的关键限制，CausalBGM在基因组学、医疗保健和社会科学等现代应用中的因果推断中展现出一个稳健且有前景的框架。CausalBGM可以在以下网址进行维护: [https://www.example.com/CausalBGM]。 

---
# Dynamics of Adversarial Attacks on Large Language Model-Based Search Engines 

**Title (ZH)**: 基于大型语言模型的搜索引擎中的对抗攻击动态研究 

**Authors**: Xiyang Hu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00745)  

**Abstract**: The increasing integration of Large Language Model (LLM) based search engines has transformed the landscape of information retrieval. However, these systems are vulnerable to adversarial attacks, especially ranking manipulation attacks, where attackers craft webpage content to manipulate the LLM's ranking and promote specific content, gaining an unfair advantage over competitors. In this paper, we study the dynamics of ranking manipulation attacks. We frame this problem as an Infinitely Repeated Prisoners' Dilemma, where multiple players strategically decide whether to cooperate or attack. We analyze the conditions under which cooperation can be sustained, identifying key factors such as attack costs, discount rates, attack success rates, and trigger strategies that influence player behavior. We identify tipping points in the system dynamics, demonstrating that cooperation is more likely to be sustained when players are forward-looking. However, from a defense perspective, we find that simply reducing attack success probabilities can, paradoxically, incentivize attacks under certain conditions. Furthermore, defensive measures to cap the upper bound of attack success rates may prove futile in some scenarios. These insights highlight the complexity of securing LLM-based systems. Our work provides a theoretical foundation and practical insights for understanding and mitigating their vulnerabilities, while emphasizing the importance of adaptive security strategies and thoughtful ecosystem design. 

**Abstract (ZH)**: 基于大语言模型（LLM）的搜索引擎集成日益增加，已经极大地改变了信息检索的格局。然而，这些系统容易遭受恶意攻击，尤其是排名操控攻击，攻击者可以通过精心构建网页内容来操控LLM的排名并推广特定内容，从而在竞争中获得不公平的优势。本文研究了排名操控攻击的动力学。我们将这个问题框架化为无限重复的囚徒困境，多个参与者战略性地决定是合作还是攻击。我们分析了确保合作能够持续的条件，识别了包括攻击成本、贴现率、攻击成功率和触发策略在内的关键因素，这些因素会影响玩家的行为。我们确定了系统动力学中的临界点，表明当玩家具有前瞻性时，合作更有可能持续。然而，从防御角度来看，我们发现简单降低攻击成功率在某些条件下反而可能激励攻击。此外，在某些情况下，限制攻击成功率的上限的防御措施可能无效。这些洞察突显了确保基于LLM系统的复杂性。我们的研究为理解并减轻其脆弱性提供了理论基础和实践见解，并强调了适应性安全策略和精心设计生态系统的重要性。 

---
# AttriReBoost: A Gradient-Free Propagation Optimization Method for Cold Start Mitigation in Attribute Missing Graphs 

**Title (ZH)**: AttriReBoost：一种用于属性缺失图中冷启动缓解的无梯度传播优化方法 

**Authors**: Mengran Li, Chaojun Ding, Junzhou Chen, Wenbin Xing, Cong Ye, Ronghui Zhang, Songlin Zhuang, Jia Hu, Tony Z. Qiu, Huijun Gao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00743)  

**Abstract**: Missing attribute issues are prevalent in the graph learning, leading to biased outcomes in Graph Neural Networks (GNNs). Existing methods that rely on feature propagation are prone to cold start problem, particularly when dealing with attribute resetting and low-degree nodes, which hinder effective propagation and convergence. To address these challenges, we propose AttriReBoost (ARB), a novel method that incorporates propagation-based method to mitigate cold start problems in attribute-missing graphs. ARB enhances global feature propagation by redefining initial boundary conditions and strategically integrating virtual edges, thereby improving node connectivity and ensuring more stable and efficient convergence. This method facilitates gradient-free attribute reconstruction with lower computational overhead. The proposed method is theoretically grounded, with its convergence rigorously established. Extensive experiments on several real-world benchmark datasets demonstrate the effectiveness of ARB, achieving an average accuracy improvement of 5.11% over state-of-the-art methods. Additionally, ARB exhibits remarkable computational efficiency, processing a large-scale graph with 2.49 million nodes in just 16 seconds on a single GPU. Our code is available at this https URL. 

**Abstract (ZH)**: 图学习中属性缺失问题普遍存在，这导致图神经网络（GNNs）的结果存在偏差。现有的依赖特征传播的方法在处理属性复位和低度节点时容易遇到冷启动问题，这妨碍了有效的传播和收敛。为了解决这些问题，我们提出了AttriReBoost（ARB），一种新的方法，将基于传播的方法融入其中，以应对属性缺失图的冷启动问题。ARB通过重新定义初始边界条件并战略性地整合虚拟边，增强全局特征传播，从而提高节点连通性并确保更稳定和高效的收敛。该方法促进了无梯度属性重构，并且具有较低的计算开销。该方法具有坚实的理论基础，并且其收敛性得到了严格证明。通过对多个真实基准数据集进行广泛实验，展示了ARB的有效性，相较于最先进的方法，其准确率平均提高了5.11%。此外，ARB在计算效率方面表现出色，在单个GPU上处理包含249万节点的大规模图只需要16秒。我们的代码可以在以下链接中找到：[提供链接]。 

---
# Towards End-to-End Neuromorphic Voxel-based 3D Object Reconstruction Without Physical Priors 

**Title (ZH)**: 面向端到端类脑体素基三维物体重建：无需物理先验知识 

**Authors**: Chuanzhi Xu, Langyi Chen, Vincent Qu, Haodong Chen, Vera Chung  

**Link**: [PDF](https://arxiv.org/pdf/2501.00741)  

**Abstract**: Neuromorphic cameras, also known as event cameras, are asynchronous brightness-change sensors that can capture extremely fast motion without suffering from motion blur, making them particularly promising for 3D reconstruction in extreme environments. However, existing research on 3D reconstruction using monocular neuromorphic cameras is limited, and most of the methods rely on estimating physical priors and employ complex multi-step pipelines. In this work, we propose an end-to-end method for dense voxel 3D reconstruction using neuromorphic cameras that eliminates the need to estimate physical priors. Our method incorporates a novel event representation to enhance edge features, enabling the proposed feature-enhancement model to learn more effectively. Additionally, we introduced Optimal Binarization Threshold Selection Principle as a guideline for future related work, using the optimal reconstruction results achieved with threshold optimization as the benchmark. Our method achieves a 54.6% improvement in reconstruction accuracy compared to the baseline method. 

**Abstract (ZH)**: 神经形态相机，也称为事件相机，是一种异步亮度变化传感器，能够捕捉极快速的运动且不会产生运动模糊，这使它们在极端环境中进行三维重建方面具有特别的潜力。然而，目前使用单目神经形态相机进行三维重建的研究相对有限，大多数方法依赖于估计物理先验，并且采用了复杂的多步管道。在此项工作中，我们提出了一种端到端的方法，使用神经形态相机进行密集体素三维重建，从而消除了估计物理先验的需求。我们的方法引入了一种新颖的事件表示，以增强边缘特征，使所提出的特征增强模型能够更有效地学习。此外，我们引入了最优二值化阈值选择原则作为未来相关工作的指南，使用通过阈值优化获得的最优重建结果作为基准。与基准方法相比，我们的方法在重建准确性上实现了54.6%的提升。 

---
# eRevise+RF: A Writing Evaluation System for Assessing Student Essay Revisions and Providing Formative Feedback 

**Title (ZH)**: eRevise+RF: 一种评估学生作文修订并提供形成性反馈的写作评估系统 

**Authors**: Zhexiong Liu, Diane Litman, Elaine Wang, Tianwen Li, Mason Gobat, Lindsay Clare Matsumura, Richard Correnti  

**Link**: [PDF](https://arxiv.org/pdf/2501.00715)  

**Abstract**: The ability to revise essays in response to feedback is important for students' writing success. An automated writing evaluation (AWE) system that supports students in revising their essays is thus essential. We present eRevise+RF, an enhanced AWE system for assessing student essay revisions (e.g., changes made to an essay to improve its quality in response to essay feedback) and providing revision feedback. We deployed the system with 6 teachers and 406 students across 3 schools in Pennsylvania and Louisiana. The results confirmed its effectiveness in (1) assessing student essays in terms of evidence usage, (2) extracting evidence and reasoning revisions across essays, and (3) determining revision success in responding to feedback. The evaluation also suggested eRevise+RF is a helpful system for young students to improve their argumentative writing skills through revision and formative feedback. 

**Abstract (ZH)**: 根据反馈修订作文的能力是学生写作成功的关键。因此，支持学生修订作文的自动写作评估（AWE）系统是必不可少的。我们提出了一种增强的AWE系统eRevise+RF，用于评估学生对作文的修订（例如，根据反馈意见改进作文所作出的修改）并提供修订反馈。该系统在学校层面进行了部署，涉及宾夕法尼亚州和路易斯安那州的3所学校，6名教师和406名学生。研究结果证实了eRevise+RF在以下方面的有效性：（1）评估学生作文的证据使用情况；（2）提取各作文之间的证据和推理修订；以及（3）确定作文修订是否成功回应了反馈意见。评估还表明，eRevise+RF是一种有助于年轻学生通过修订和形成性反馈提高论说性写作技能的有用系统。 

---
# Everywhere Attack: Attacking Locally and Globally to Boost Targeted Transferability 

**Title (ZH)**: 全域攻击：通过局部和全局攻击提升目标迁移性 

**Authors**: Hui Zeng, Sanshuai Cui, Biwei Chen, Anjie Peng  

**Link**: [PDF](https://arxiv.org/pdf/2501.00707)  

**Abstract**: Adversarial examples' (AE) transferability refers to the phenomenon that AEs crafted with one surrogate model can also fool other models. Notwithstanding remarkable progress in untargeted transferability, its targeted counterpart remains challenging. This paper proposes an everywhere scheme to boost targeted transferability. Our idea is to attack a victim image both globally and locally. We aim to optimize 'an army of targets' in every local image region instead of the previous works that optimize a high-confidence target in the image. Specifically, we split a victim image into non-overlap blocks and jointly mount a targeted attack on each block. Such a strategy mitigates transfer failures caused by attention inconsistency between surrogate and victim models and thus results in stronger transferability. Our approach is method-agnostic, which means it can be easily combined with existing transferable attacks for even higher transferability. Extensive experiments on ImageNet demonstrate that the proposed approach universally improves the state-of-the-art targeted attacks by a clear margin, e.g., the transferability of the widely adopted Logit attack can be improved by 28.8%-300%.We also evaluate the crafted AEs on a real-world platform: Google Cloud Vision. Results further support the superiority of the proposed method. 

**Abstract (ZH)**: 对抗样本（Adversarial Examples, AE）的可转移性指的是，使用一种替代模型生成的AE可以欺骗其他模型的现象。尽管无目标可转移性取得了显著进展，其对应的目标可转移性仍然具有挑战性。本文提出了一种增强目标可转移性的普遍方案。我们的想法是同时对受害者图像进行全局和局部攻击。我们旨在优化每个局部图像区域中的“目标军队”而不是先前工作中的高置信度单一目标。具体而言，我们将受害者图像分割成不重叠的块，并联合对每个块进行目标攻击。这种策略减轻了替代模型和受害者模型注意力不一致导致的转移失败，从而实现了更强的可转移性。我们的方法是无偏的，这意味着它能够与现有的可转移攻击方法轻松结合，以进一步提高可转移性。在ImageNet上的广泛实验表明，所提出的方法在无目标可转移性的现有最佳方法上普遍提高了目标可转移性，例如，广泛采用的Logit攻击的可转移性可以提高28.8%-300%。此外，我们还在一个实际平台（Google Cloud Vision）上对生成的AE进行了评估，结果进一步证实了所提出方法的优越性。 

---
# Adjoint sharding for very long context training of state space models 

**Title (ZH)**: 状态空间模型中非常长上下文训练的伴随分片方法 

**Authors**: Xingzi Xu, Amir Tavanaei, Kavosh Asadi, Karim Bouyarmane  

**Link**: [PDF](https://arxiv.org/pdf/2501.00692)  

**Abstract**: Despite very fast progress, efficiently training large language models (LLMs) in very long contexts remains challenging. Existing methods fall back to training LLMs with short contexts (a maximum of a few thousands tokens in training) and use inference time techniques when evaluating on long contexts (above 1M tokens context window at inference). As opposed to long-context-inference, training on very long context input prompts is quickly limited by GPU memory availability and by the prohibitively long training times it requires on state-of-the-art hardware. Meanwhile, many real-life applications require not only inference but also training/fine-tuning with long context on specific tasks. Such applications include, for example, augmenting the context with various sources of raw reference information for fact extraction, fact summarization, or fact reconciliation tasks. We propose adjoint sharding, a novel technique that comprises sharding gradient calculation during training to reduce memory requirements by orders of magnitude, making training on very long context computationally tractable. Adjoint sharding is based on the adjoint method and computes equivalent gradients to backpropagation. We also propose truncated adjoint sharding to speed up the algorithm while maintaining performance. We provide a distributed version, and a paralleled version of adjoint sharding to further speed up training. Empirical results show the proposed adjoint sharding algorithm reduces memory usage by up to 3X with a 1.27B parameter large language model on 1M context length training. This allows to increase the maximum context length during training or fine-tuning of a 1.27B parameter model from 35K tokens to above 100K tokens on a training infrastructure composed of five AWS P4 instances. 

**Abstract (ZH)**: 尽管取得了非常快速的进展，但在非常长的上下文中高效训练大规模语言模型（LLMs）仍然具有挑战性。现有方法倾向于使用短上下文（最多几千个令牌）进行训练，并在评估长上下文时使用推理时间的技术（在推理时上下文窗口超过100万令牌）。与长上下文推理相比，当在非常长的输入提示上进行训练时，很快就会受到GPU内存可用性和所需超长训练时间的限制。同时，许多实际应用场景不仅需要推理，还需要在特定任务上进行长时间上下文的训练/微调。例如，这些应用包括将上下文与各种原始参考信息来源结合以进行事实提取、事实总结或事实校对等任务。我们提出了一种名为反向导数分割的新技术，该技术在训练过程中拆分梯度计算，以将内存需求大幅减少几个数量级，使在非常长的上下文上进行训练成为计算上可行的任务。反向导数分割基于反向方法，计算与反向传播等效的梯度。我们还提出了一种截断的反向导数分割算法，以加快算法运行速度并保持性能。此外，我们提供了一种分布式版本和并行版本的反向导数分割以进一步加快训练速度。实验证明，对于包含10^9个参数、在100万令牌长度训练的实验，提出的反向导数分割算法可以将内存使用量减少高达3倍。这使得可以在由五台AWS P4实例组成的训练基础设施中将10^9个参数模型的训练最大上下文长度从3.5万个令牌增加到超过10万个令牌。 

---
# Leaf diseases detection using deep learning methods 

**Title (ZH)**: 使用深度学习方法进行叶片病害检测 

**Authors**: El Houcine El Fatimi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00669)  

**Abstract**: This study, our main topic is to devlop a new deep-learning approachs for plant leaf disease identification and detection using leaf image datasets. We also discussed the challenges facing current methods of leaf disease detection and how deep learning may be used to overcome these challenges and enhance the accuracy of disease detection. Therefore, we have proposed a novel method for the detection of various leaf diseases in crops, along with the identification and description of an efficient network architecture that encompasses hyperparameters and optimization methods. The effectiveness of different architectures was compared and evaluated to see the best architecture configuration and to create an effective model that can quickly detect leaf disease. In addition to the work done on pre-trained models, we proposed a new model based on CNN, which provides an efficient method for identifying and detecting plant leaf disease. Furthermore, we evaluated the efficacy of our model and compared the results to those of some pre-trained state-of-the-art architectures. 

**Abstract (ZH)**: 本研究的主要主题是开发一种新的深度学习方法，用于利用叶图像数据集进行植物叶片疾病识别与检测。我们还讨论了当前叶片疾病检测方法所面临的主要挑战，并探讨了如何利用深度学习来克服这些挑战，从而提高疾病检测的准确性。因此，我们提出了一种新的方法，用于各种作物叶片疾病的检测，并提出了一个高效网络架构，该架构涵盖了超参数和优化方法，以实现疾病的识别和描述。不同架构的有效性进行了比较和评估，以确定最佳的架构配置，并创建一个能够快速检测叶片疾病的高效模型。此外，在预训练模型的研究基础上，我们提出了一种基于CNN的新模型，提供了一种有效的叶片疾病识别与检测方法。最后，我们评估了该模型的效果，并将其结果与一些现有的预训练先进架构进行了比较。 

---
# Titans: Learning to Memorize at Test Time 

**Title (ZH)**: 泰坦：在测试时学习记忆 

**Authors**: Ali Behrouz, Peilin Zhong, Vahab Mirrokni  

**Link**: [PDF](https://arxiv.org/pdf/2501.00663)  

**Abstract**: Over more than a decade there has been an extensive research effort on how to effectively utilize recurrent models and attention. While recurrent models aim to compress the data into a fixed-size memory (called hidden state), attention allows attending to the entire context window, capturing the direct dependencies of all tokens. This more accurate modeling of dependencies, however, comes with a quadratic cost, limiting the model to a fixed-length context. We present a new neural long-term memory module that learns to memorize historical context and helps attention to attend to the current context while utilizing long past information. We show that this neural memory has the advantage of fast parallelizable training while maintaining a fast inference. From a memory perspective, we argue that attention due to its limited context but accurate dependency modeling performs as a short-term memory, while neural memory due to its ability to memorize the data, acts as a long-term, more persistent, memory. Based on these two modules, we introduce a new family of architectures, called Titans, and present three variants to address how one can effectively incorporate memory into this architecture. Our experimental results on language modeling, common-sense reasoning, genomics, and time series tasks show that Titans are more effective than Transformers and recent modern linear recurrent models. They further can effectively scale to larger than 2M context window size with higher accuracy in needle-in-haystack tasks compared to baselines. 

**Abstract (ZH)**: 在过去的十多年间，研究人员广泛致力于探索如何有效地利用循环模型和注意力机制。循环模型旨在将数据压缩到固定大小的记忆（称为隐藏状态），而注意力机制则允许模型关注整个上下文窗口，捕捉所有标记之间的直接依赖关系。然而，这种更准确的依赖关系建模伴随着二次时间复杂度的增加，从而限制了模型所能处理的上下文字长。我们提出了一种新的神经长期记忆模块，该模块能够学习记忆历史上下文，并在利用以往信息的同时帮助注意力机制关注当前上下文。我们展示出，这种神经记忆具有快速并行化的训练优势，同时保持快速的推理速度。从记忆角度来看，我们认为注意力机制虽然仅限于处理有限的上下文但具有准确的依赖关系建模能力，因此表现为短期记忆；而神经记忆由于具备存储数据的能力，表现为一种更持久的长期记忆。基于这两种模块，我们引入了一种新的架构家族，称为Titans，并提出了三种变体，以解决如何有效地将记忆集成到该架构中的问题。我们在语言建模、常识推理、基因组学和时间序列任务上的实验结果表明，Titans在效果上优于Transformers和最近的现代线性循环模型。此外，它们还能有效扩展到超过200万的上下文窗口大小，并在需要从大量无关信息中提取关键信息的任务中实现更高的准确性。 

---
# Efficient Standardization of Clinical Notes using Large Language Models 

**Title (ZH)**: 使用大规模语言模型进行临床笔记的高效标准化 

**Authors**: Daniel B. Hier, Michael D. Carrithers, Thanh Son Do, Tayo Obafemi-Ajayi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00644)  

**Abstract**: Clinician notes are a rich source of patient information but often contain inconsistencies due to varied writing styles, colloquialisms, abbreviations, medical jargon, grammatical errors, and non-standard formatting. These inconsistencies hinder the extraction of meaningful data from electronic health records (EHRs), posing challenges for quality improvement, population health, precision medicine, decision support, and research.
We present a large language model approach to standardizing a corpus of 1,618 clinical notes. Standardization corrected an average of $4.9 +/- 1.8$ grammatical errors, $3.3 +/- 5.2$ spelling errors, converted $3.1 +/- 3.0$ non-standard terms to standard terminology, and expanded $15.8 +/- 9.1$ abbreviations and acronyms per note. Additionally, notes were re-organized into canonical sections with standardized headings. This process prepared notes for key concept extraction, mapping to medical ontologies, and conversion to interoperable data formats such as FHIR.
Expert review of randomly sampled notes found no significant data loss after standardization. This proof-of-concept study demonstrates that standardization of clinical notes can improve their readability, consistency, and usability, while also facilitating their conversion into interoperable data formats. 

**Abstract (ZH)**: 医生笔记是患者信息的重要来源，但由于书写风格多样、俚语、缩写、医学术语、语法错误和非标准化格式等因素，常常存在不一致的情况。这些不一致性妨碍了从电子健康记录（EHRs）中提取有意义的数据，给质量改进、人群健康、精准医疗、决策支持和研究带来了挑战。

我们提出了一种大规模语言模型方法，用于标准化1,618份临床笔记。标准化过程平均每份笔记纠正了4.9±1.8个语法错误，3.3±5.2个拼写错误，将3.1±3.0个非标术语转换为标准术语，并扩展了15.8±9.1个缩写和首字母缩略词。此外，将笔记重新整理为具有标准化标题的标准部分。这一过程为关键概念提取、医学本体映射以及转换为诸如FHIR等互操作数据格式做准备。

对随机抽样的笔记进行专家评审后发现，标准化过程中没有显著的数据丢失。这一概念验证研究证明，标准化临床笔记可以提高其可读性、一致性和可利用率，同时也有助于将其转换为互操作数据格式。 

---
# Enabling New HDLs with Agents 

**Title (ZH)**: 启用基于代理的新高级描述语言 

**Authors**: Mark Zakharov, Farzaneh Rabiei Kashanaki, Jose Renau  

**Link**: [PDF](https://arxiv.org/pdf/2501.00642)  

**Abstract**: Large Language Models (LLMs) based agents are transforming the programming language landscape by facilitating learning for beginners, enabling code generation, and optimizing documentation workflows. Hardware Description Languages (HDLs), with their smaller user community, stand to benefit significantly from the application of LLMs as tools for learning new HDLs. This paper investigates the challenges and solutions of enabling LLMs for HDLs, particularly for HDLs that LLMs have not been previously trained on. This work introduces HDLAgent, an AI agent optimized for LLMs with limited knowledge of various HDLs. It significantly enhances off-the-shelf LLMs. 

**Abstract (ZH)**: 基于大型语言模型（Large Language Models, LLMs）的代理正在通过促进初学者学习、实现代码生成以及优化文档工作流，重塑编程语言的格局。硬件描述语言（Hardware Description Languages, HDLs），因其较小的用户群体，特别可以从LLMs应用中受益，作为学习新的HDLs的工具。本文探讨了使LLMs适用于HDLs所面临的挑战及其解决方案，尤其是对于LLMs尚未被训练的HDLs。本文介绍了一种名为HDLAgent的AI代理，它针对各种HDLs具有有限知识进行了优化，显著提升了现成的LLMs。 

---
# A Study on Context Length and Efficient Transformers for Biomedical Image Analysis 

**Title (ZH)**: 对上下文长度和高效-transformer 在生物医学图像分析中的研究 

**Authors**: Sarah M. Hooper, Hui Xue  

**Link**: [PDF](https://arxiv.org/pdf/2501.00619)  

**Abstract**: Biomedical imaging modalities often produce high-resolution, multi-dimensional images that pose computational challenges for deep neural networks. These computational challenges are compounded when training transformers due to the self-attention operator, which scales quadratically with context length. Recent developments in long-context models have potential to alleviate these difficulties and enable more efficient application of transformers to large biomedical images, although a systematic evaluation on this topic is lacking. In this study, we investigate the impact of context length on biomedical image analysis and we evaluate the performance of recently proposed long-context models. We first curate a suite of biomedical imaging datasets, including 2D and 3D data for segmentation, denoising, and classification tasks. We then analyze the impact of context length on network performance using the Vision Transformer and Swin Transformer by varying patch size and attention window size. Our findings reveal a strong relationship between context length and performance, particularly for pixel-level prediction tasks. Finally, we show that recent long-context models demonstrate significant improvements in efficiency while maintaining comparable performance, though we highlight where gaps remain. This work underscores the potential and challenges of using long-context models in biomedical imaging. 

**Abstract (ZH)**: 生物医学成像模式通常会产生高分辨率、多维度的图像，这为深度神经网络带来了计算挑战。在训练transformer时，由于自注意力操作符导致的计算挑战加剧，其计算复杂度与上下文长度成二次关系。近年来，对于长上下文模型的发展有可能缓解这些困难，并使transformer在大规模生物医学图像中的应用更加高效，尽管在这方面的系统性评估还比较缺乏。在本研究中，我们探讨了上下文长度对生物医学图像分析的影响，并评估了最近提出的长上下文模型的性能。我们首先整理了一个包含用于分割、去噪和分类任务的2D和3D生物医学成像数据集。然后，我们通过变化聚束大小和注意力窗口大小，利用Vision Transformer和Swin Transformer分析上下文长度对网络性能的影响。我们的研究表明，上下文长度与性能之间存在着密切的关系，特别是在像素级预测任务中尤为明显。最后，我们展示了最近的长上下文模型虽然在效率上有所提升，但仍有一些差距需要填平。这项工作强调了长上下文模型在生物医学成像中的潜在价值和面临的挑战。 

---
# DreamDrive: Generative 4D Scene Modeling from Street View Images 

**Title (ZH)**: DreamDrive：从街景图像生成4D场景模型 

**Authors**: Jiageng Mao, Boyi Li, Boris Ivanovic, Yuxiao Chen, Yan Wang, Yurong You, Chaowei Xiao, Danfei Xu, Marco Pavone, Yue Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00601)  

**Abstract**: Synthesizing photo-realistic visual observations from an ego vehicle's driving trajectory is a critical step towards scalable training of self-driving models. Reconstruction-based methods create 3D scenes from driving logs and synthesize geometry-consistent driving videos through neural rendering, but their dependence on costly object annotations limits their ability to generalize to in-the-wild driving scenarios. On the other hand, generative models can synthesize action-conditioned driving videos in a more generalizable way but often struggle with maintaining 3D visual consistency. In this paper, we present DreamDrive, a 4D spatial-temporal scene generation approach that combines the merits of generation and reconstruction, to synthesize generalizable 4D driving scenes and dynamic driving videos with 3D consistency. Specifically, we leverage the generative power of video diffusion models to synthesize a sequence of visual references and further elevate them to 4D with a novel hybrid Gaussian representation. Given a driving trajectory, we then render 3D-consistent driving videos via Gaussian splatting. The use of generative priors allows our method to produce high-quality 4D scenes from in-the-wild driving data, while neural rendering ensures 3D-consistent video generation from the 4D scenes. Extensive experiments on nuScenes and street view images demonstrate that DreamDrive can generate controllable and generalizable 4D driving scenes, synthesize novel views of driving videos with high fidelity and 3D consistency, decompose static and dynamic elements in a self-supervised manner, and enhance perception and planning tasks for autonomous driving. 

**Abstract (ZH)**: 从ego车辆驾驶轨迹合成逼真的视觉观察是实现自驾车模型可扩展训练的关键步骤。基于重建的方法从驾驶日志中创建3D场景，并通过神经渲染合成几何一致的驾驶视频，但它们对昂贵的对象标注的依赖限制了其在野外驾驶场景中的泛化能力。另一方面，生成模型能够以更可泛化的方式合成条件驱动视频，但通常难以保持3D视觉一致性。在本文中，我们提出了DreamDrive，这是一种结合生成和重建优势的4D空间-时间场景生成方法，用于合成可泛化的4D驾驶场景和动态驾驶视频，并保持3D一致性。具体而言，我们利用视频扩散模型的生成能力来合成一系列视觉参考，并通过一种新型的混合高斯表示进一步提升为4D。然后，给定驾驶轨迹，我们通过高斯点渲染生成几何一致的驾驶视频。利用生成先验知识，我们的方法可以从野外驾驶数据中生成高质量的4D场景，而神经渲染则确保从4D场景生成3D一致的视频。在nuScenes和街景图像上的广泛实验表明，DreamDrive能够生成可控且可泛化的4D驾驶场景，合成高保真度且3D一致的新型驾驶视频视图，以无监督方式分解静止和动态元素，并增强自动驾驶的感知和规划任务。 

---
# VideoRefer Suite: Advancing Spatial-Temporal Object Understanding with Video LLM 

**Title (ZH)**: VideoRefer Suite：通过视频LLM提升空时对象理解 

**Authors**: Yuqian Yuan, Hang Zhang, Wentong Li, Zesen Cheng, Boqiang Zhang, Long Li, Xin Li, Deli Zhao, Wenqiao Zhang, Yueting Zhuang, Jianke Zhu, Lidong Bing  

**Link**: [PDF](https://arxiv.org/pdf/2501.00599)  

**Abstract**: Video Large Language Models (Video LLMs) have recently exhibited remarkable capabilities in general video understanding. However, they mainly focus on holistic comprehension and struggle with capturing fine-grained spatial and temporal details. Besides, the lack of high-quality object-level video instruction data and a comprehensive benchmark further hinders their advancements. To tackle these challenges, we introduce the VideoRefer Suite to empower Video LLM for finer-level spatial-temporal video understanding, i.e., enabling perception and reasoning on any objects throughout the video. Specially, we thoroughly develop VideoRefer Suite across three essential aspects: dataset, model, and benchmark. Firstly, we introduce a multi-agent data engine to meticulously curate a large-scale, high-quality object-level video instruction dataset, termed VideoRefer-700K. Next, we present the VideoRefer model, which equips a versatile spatial-temporal object encoder to capture precise regional and sequential representations. Finally, we meticulously create a VideoRefer-Bench to comprehensively assess the spatial-temporal understanding capability of a Video LLM, evaluating it across various aspects. Extensive experiments and analyses demonstrate that our VideoRefer model not only achieves promising performance on video referring benchmarks but also facilitates general video understanding capabilities. 

**Abstract (ZH)**: 视频大型语言模型（Video LLMs）最近在通用视频理解方面展示了显著的能力。然而，它们主要侧重于整体理解，对于捕捉精细的空间和时间细节存在困难。此外，高质量的对象级视频指令数据的缺乏以及缺乏全面的基准进一步阻碍了它们的发展。为应对这些挑战，我们提出VideoRefer套件以增强Video LLM在细粒度空间-时间视频理解方面的能力，即能够对视频中的任何对象进行感知和推理。特别地，我们从三个关键方面全面开发了VideoRefer套件：数据集、模型和基准。首先，我们引入一个多智能体数据引擎，以精心构建一个大规模且高质量的对象级视频指令数据集，命名为VideoRefer-700K。其次，我们提出了VideoRefer模型，该模型配备了多功能的空间-时间对象编码器来捕捉精确的区域和序列表示。最后，我们精心构建了VideoRefer-Bench，以全面评估Video LLM的空间-时间理解能力，并从多个方面对其进行评估。广泛的实验和分析表明，我们的VideoRefer模型不仅在视频引用基准测试中取得了令人鼓舞的性能，还促进了通用视频理解能力的发展。 

---
# Unbiased GNN Learning via Fairness-Aware Subgraph Diffusion 

**Title (ZH)**: 通过公平性意识子图扩散实现无偏图神经网络学习 

**Authors**: Abdullah Alchihabi, Yuhong Guo  

**Link**: [PDF](https://arxiv.org/pdf/2501.00595)  

**Abstract**: Graph Neural Networks (GNNs) have demonstrated remarkable efficacy in tackling a wide array of graph-related tasks across diverse domains. However, a significant challenge lies in their propensity to generate biased predictions, particularly with respect to sensitive node attributes such as age and gender. These biases, inherent in many machine learning models, are amplified in GNNs due to the message-passing mechanism, which allows nodes to influence each other, rendering the task of making fair predictions notably challenging. This issue is particularly pertinent in critical domains where model fairness holds paramount importance. In this paper, we propose a novel generative Fairness-Aware Subgraph Diffusion (FASD) method for unbiased GNN learning. The method initiates by strategically sampling small subgraphs from the original large input graph, and then proceeds to conduct subgraph debiasing via generative fairness-aware graph diffusion processes based on stochastic differential equations (SDEs). To effectively diffuse unfairness in the input data, we introduce additional adversary bias perturbations to the subgraphs during the forward diffusion process, and train score-based models to predict these applied perturbations, enabling them to learn the underlying dynamics of the biases present in the data. Subsequently, the trained score-based models are utilized to further debias the original subgraph samples through the reverse diffusion process. Finally, FASD induces fair node predictions on the input graph by performing standard GNN learning on the debiased subgraphs. Experimental results demonstrate the superior performance of the proposed method over state-of-the-art Fair GNN baselines across multiple benchmark datasets. 

**Abstract (ZH)**: 图神经网络（GNNs）在解决各种涉及图的任务方面表现出了显著的效果，涵盖了多个不同的领域。然而，一个重大挑战在于它们生成带偏见预测的倾向，特别是在处理诸如年龄和性别等敏感节点属性时更为明显。这些偏见存在于许多机器学习模型中，并在GNNs中被放大，因为消息传递机制使得节点能够互相影响，从而使得公平预测任务变得极其复杂。这个问题在模型公平性具有至高重要性的关键领域尤为突出。在这篇论文中，我们提出了一种新的生成公平感知子图扩散（FASD）方法，以实现无偏的GNN学习。该方法首先通过策略性地从原始大输入图中采样小子图，然后基于随机微分方程（SDEs）进行生成公平感知的子图去偏置处理。为了有效地在输入数据中扩散不公平性，在正向扩散过程中，我们引入了额外的对抗性偏见扰动到子图中，并训练基于得分的模型以预测这些施加的扰动，使模型能够学习数据中存在的偏见动态。随后，利用训练好的基于得分的模型通过反向扩散过程进一步对原始子图样本进行去偏置处理。最后，FASD 通过在去偏置子图上进行标准的GNN学习，在输入图上产生公平的节点预测。实验结果表明，该方法在多个基准数据集上的表现优于最先进的公平GNN基线方法。 

---
# Causal Graph Guided Steering of LLM Values via Prompts and Sparse Autoencoders 

**Title (ZH)**: 基于因果图引导的LLM价值观通过提示和稀疏自编码器的调控 

**Authors**: Yipeng Kang, Junqi Wang, Yexin Li, Fangwei Zhong, Xue Feng, Mengmeng Wang, Wenming Tu, Quansen Wang, Hengli Li, Zilong Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.00581)  

**Abstract**: As large language models (LLMs) become increasingly integrated into critical applications, aligning their behavior with human values presents significant challenges. Current methods, such as Reinforcement Learning from Human Feedback (RLHF), often focus on a limited set of values and can be resource-intensive. Furthermore, the correlation between values has been largely overlooked and remains underutilized. Our framework addresses this limitation by mining a causal graph that elucidates the implicit relationships among various values within the LLMs. Leveraging the causal graph, we implement two lightweight mechanisms for value steering: prompt template steering and Sparse Autoencoder feature steering, and analyze the effects of altering one value dimension on others. Extensive experiments conducted on Gemma-2B-IT and Llama3-8B-IT demonstrate the effectiveness and controllability of our steering methods. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在关键应用中的日益集成，使它们的行为与人类价值观保持一致面临着重大挑战。当前的方法，如基于人类反馈的强化学习（Reinforcement Learning from Human Feedback，RLHF），通常关注有限的价值集，并且往往资源密集型。此外，价值之间的相关性已被大量忽视，且尚未得到充分利用。我们的框架通过挖掘一个因果图来解决这一限制，该因果图阐明了LLMs内部各种价值之间的隐含关系。利用因果图，我们实现了两种轻量级的价值导向机制：提示模板导向和稀疏自动编码器特征导向，并分析了一种价值维度的变化对其他价值维度的影响。在Gemma-2B-IT和Llama3-8B-IT上的 extensive 实验表明，我们导向方法的有效性和可控性。 

---
# An Overview and Discussion on Using Large Language Models for Implementation Generation of Solutions to Open-Ended Problems 

**Title (ZH)**: 大型语言模型在解决开放式问题解决方案生成中的应用综述与讨论 

**Authors**: Hashmath Shaik, Alex Doboli  

**Link**: [PDF](https://arxiv.org/pdf/2501.00562)  

**Abstract**: Large Language Models offer new opportunities to devise automated implementation generation methods that can tackle problem solving activities beyond traditional methods, which require algorithmic specifications and can use only static domain knowledge, like performance metrics and libraries of basic building blocks. Large Language Models could support creating new methods to support problem solving activities for open-ended problems, like problem framing, exploring possible solving approaches, feature elaboration and combination, more advanced implementation assessment, and handling unexpected situations. This report summarized the current work on Large Language Models, including model prompting, Reinforcement Learning, and Retrieval-Augmented Generation. Future research requirements were also discussed. 

**Abstract (ZH)**: 大型语言模型为设计自动化实现生成方法提供了新的机遇，这些方法可以解决传统方法无法处理的问题，而传统方法需要算法规范且只能利用静态领域知识，例如性能指标和基本构建块的库。大型语言模型可以支持创建新的方法来解决开放型问题，例如问题框架、探索可能的解决方法、特征细化和组合、更高级的实现评估以及处理意外情况。本报告总结了当前大型语言模型的相关工作，包括模型提示、强化学习和检索增强生成技术，并讨论了未来的研究需求。 

---
# Re-evaluating Automatic LLM System Ranking for Alignment with Human Preference 

**Title (ZH)**: 重新评估自动大型语言模型系统排名与人类偏好的一致性 

**Authors**: Mingqi Gao, Yixin Liu, Xinyu Hu, Xiaojun Wan, Jonathan Bragg, Arman Cohan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00560)  

**Abstract**: Evaluating and ranking the capabilities of different LLMs is crucial for understanding their performance and alignment with human preferences. Due to the high cost and time-consuming nature of human evaluations, an automatic LLM bencher (i.e., an automatic evaluation framework that aims to rank LLMs based on their alignment with human preferences) is indispensable. An automatic LLM bencher consists of four components: the input set (e.g., a user instruction), the evaluation model (e.g., an LLM), the evaluation type (e.g., pairwise comparison), and the aggregation method (e.g., the ELO rating system). However, previous work has not thoroughly explored how to select these components or how their different combinations influence the results. In this work, through controlled experiments, we provide a series of recommendations on how to choose each component to better automate the evaluation of LLMs. Furthermore, we discovered that when evaluating LLMs with similar performance, the performance of the automatic LLM bencher declines sharply, underscoring the limitations of current benchers and calling for future work. Lastly, we found that the evaluation models' performance at the instance level (e.g., the accuracy of selecting the best output) does not always align with their effectiveness when used as a component of a bencher, highlighting the importance of dedicated system-level evaluation of benchers. 

**Abstract (ZH)**: 评估和排名不同大型语言模型（LLM）的能力对于理解它们的性能和与人类偏好的一致性至关重要。由于人工评估成本高且耗时，因此需要一种自动的LLM评判器（即基于人类偏好排名LLM的自动评估框架）。一个自动LLM评判器包括四个组成部分：输入集（例如，用户指令）、评估模型（例如，LLM）、评估类型（例如，成对比较）以及聚合方法（例如，ELO评价系统）。然而，以往的研究并未详细探讨如何选择这些组成部分，或不同组合如何影响结果。在本研究中，通过控制实验，我们提供了一系列如何选择每个组成部分以更好地自动化LLM评估的建议。此外，我们发现，在评估具有相似性能的LLM时，自动LLM评判器的表现急剧下降，突显了当前评判器的局限性，并呼吁未来的研究工作。最后，我们发现，在实例层次上（例如，选择最佳输出的准确性）评估模型的表现并不总与其用作评判器组件时的有效性一致，强调需要专门进行系统层面的评判器评估的重要性。 

---
# AraSTEM: A Native Arabic Multiple Choice Question Benchmark for Evaluating LLMs Knowledge In STEM Subjects 

**Title (ZH)**: AraSTEM：一个用于评估大模型在STEM领域知识的阿拉伯语多项选择题基准测试 

**Authors**: Ahmad Mustapha, Hadi Al-Khansa, Hadi Al-Mubasher, Aya Mourad, Ranam Hamoud, Hasan El-Husseini, Marwah Al-Sakkaf, Mariette Awad  

**Link**: [PDF](https://arxiv.org/pdf/2501.00559)  

**Abstract**: Large Language Models (LLMs) have shown remarkable capabilities, not only in generating human-like text, but also in acquiring knowledge. This highlights the need to go beyond the typical Natural Language Processing downstream benchmarks and asses the various aspects of LLMs including knowledge and reasoning. Numerous benchmarks have been developed to evaluate LLMs knowledge, but they predominantly focus on the English language. Given that many LLMs are multilingual, relying solely on benchmarking English knowledge is insufficient. To address this issue, we introduce AraSTEM, a new Arabic multiple-choice question dataset aimed at evaluating LLMs knowledge in STEM subjects. The dataset spans a range of topics at different levels which requires models to demonstrate a deep understanding of scientific Arabic in order to achieve high accuracy. Our findings show that publicly available models of varying sizes struggle with this dataset, and underscores the need for more localized language models. The dataset is freely accessible on Hugging Face. 

**Abstract (ZH)**: 大型语言模型（LLMs）在生成类人类文本方面表现出色，同时也能够获取知识。这突显了超越传统的自然语言处理下游基准，评估LLMs各方面能力（包括知识和推理）的需求。已经开发了多种基准来评估LLMs的知识，但这些基准主要集中在英语上。鉴于许多LLM是多语言的，仅仅依靠英语知识的基准是不够的。为了解决这一问题，我们引入了AraSTEM，这是一个新的阿拉伯语多选题数据集，旨在评估LLMs在STEM学科中的知识水平。该数据集涵盖了不同层次和范围的主题，要求模型展示深入的理解科学阿拉伯语，以实现高准确性。我们的研究发现，不同规模的公开可用模型在该数据集上表现出挑战，强调了开发更多本地化语言模型的需求。该数据集已免费发布在Hugging Face上。 

---
# Monty Hall and Optimized Conformal Prediction to Improve Decision-Making with LLMs 

**Title (ZH)**: 蒙提霍尔问题与优化一致预测在改善基于LLM的决策制定中的应用 

**Authors**: Harit Vishwakarma, Alan Mishler, Thomas Cook, Niccolò Dalmasso, Natraj Raman, Sumitra Ganesh  

**Link**: [PDF](https://arxiv.org/pdf/2501.00555)  

**Abstract**: Large language models (LLMs) are empowering decision-making in several applications, including tool or API usage and answering multiple-choice questions (MCQs). However, they often make overconfident, incorrect predictions, which can be risky in high-stakes settings like healthcare and finance. To mitigate these risks, recent works have used conformal prediction (CP), a model-agnostic framework for distribution-free uncertainty quantification. CP transforms a \emph{score function} into prediction sets that contain the true answer with high probability. While CP provides this coverage guarantee for arbitrary scores, the score quality significantly impacts prediction set sizes. Prior works have relied on LLM logits or other heuristic scores, lacking quality guarantees. We address this limitation by introducing CP-OPT, an optimization framework to learn scores that minimize set sizes while maintaining coverage. Furthermore, inspired by the Monty Hall problem, we extend CP's utility beyond uncertainty quantification to improve accuracy. We propose \emph{conformal revision of questions} (CROQ) to revise the problem by narrowing down the available choices to those in the prediction set. The coverage guarantee of CP ensures that the correct choice is in the revised question prompt with high probability, while the smaller number of choices increases the LLM's chances of answering it correctly. Experiments on MMLU, ToolAlpaca, and TruthfulQA datasets with Gemma-2, Llama-3 and Phi-3 models show that CP-OPT significantly reduces set sizes while maintaining coverage, and CROQ improves accuracy over the standard inference, especially when paired with CP-OPT scores. Together, CP-OPT and CROQ offer a robust framework for improving both the safety and accuracy of LLM-driven decision-making. 

**Abstract (ZH)**: 大规模语言模型（LLMs）正在赋能多种应用中的决策过程，包括工具或API的使用以及回答多项选择题（MCQs）。然而，这些模型在高风险场合（如医疗和金融）中往往会做出过于自信且错误的预测，这存在一定的风险。为减轻这些风险，最近的研究采用了区间预测（CP，Conformal Prediction）这一不依赖特定模型的框架，以实现无分布假设下的不确定性量化。CP 把一个 **评分函数** 转化为包含正确答案的概率较高的预测集。尽管 CP 能为任意评分提供这一覆盖保证，但评分的质量显著影响预测集的大小。先前的研究依赖于语言模型的输出 logits 或其他启发式评分，但缺乏质量保证。我们通过引入 CP-OPT（一种优化框架，用于学习能够最小化预测集大小同时保持覆盖范围的评分函数），来解决这一局限性。此外，受蒙提霍尔问题的启发，我们将 CP 的适用范围扩展到超越不确定性量化领域，以提高预测的准确性。我们提出了 **区间预测修订问题**（CROQ, Conformal Revision of Questions），通过将问题选项限定在预测集中以缩小选择范围。CP 的覆盖保证确保修订后的提示中正确答案的概率较高，而选择范围的缩小增加了语言模型正确回答问题的机会。我们在 MMLU、ToolAlpaca 和 TruthfulQA 数据集上的实验显示，CP-OPT 显著减小了预测集的大小并保持了覆盖范围，而 CROQ 能在标准推理之上提高准确性，尤其是在与 CP-OPT 评分结合使用时。共同使用 CP-OPT 和 CROQ 能为 LLM 驱动的决策提供一个提升其安全性和准确性的强大框架。 

---
# Superposition in Transformers: A Novel Way of Building Mixture of Experts 

**Title (ZH)**: Transformer中的超position效应：一种构建专家混合的新方法 

**Authors**: Ayoub Ben Chaliah, Hela Dellagi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00530)  

**Abstract**: Catastrophic forgetting remains a major challenge when adapting large language models (LLMs) to new tasks or domains. Conventional fine-tuning often overwrites existing knowledge, causing performance degradation on original tasks. We introduce Superposition in Transformers, a novel architecture that leverages autoencoders to superimpose the hidden representations of a base model and a fine-tuned model within a shared parameter space. By using B-spline-based blending coefficients and autoencoders that adaptively reconstruct hidden states based on the input data distribution, our method effectively mitigates catastrophic forgetting and enables a new paradigm of "in-model" superposition. This approach preserves original model capabilities while allowing compact domain-specific expertise to be added, and it supports dynamic switching between model states during inference. 

**Abstract (ZH)**: 当将大型语言模型（LLMs）适应新任务或领域时，灾难性遗忘仍然是一个主要挑战。传统的微调经常会覆盖原有知识，导致在原始任务上的性能下降。我们提出了一种新颖的变换器架构——超位置（Superposition in Transformers），该架构利用自编码器在共享参数空间内叠加基础模型和微调模型的隐藏表示。通过使用基于B样条的混合系数，并根据输入数据分布自适应地重构隐藏状态，我们的方法有效缓解了灾难性遗忘问题，并且实现了“模型内”超位置的新范式。该方法能够在保持原有模型能力的同时，允许添加紧凑的领域特定专长，并且在推理过程中支持模型状态的动态切换。 

---
# PyMilo: A Python Library for ML I/O 

**Title (ZH)**: PyMilo：一个用于机器学习输入输出的Python库 

**Authors**: AmirHosein Rostami, Sepand Haghighi, Sadra Sabouri, Alireza Zolanvari  

**Link**: [PDF](https://arxiv.org/pdf/2501.00528)  

**Abstract**: PyMilo is an open-source Python package that addresses the limitations of existing Machine Learning (ML) model storage formats by providing a transparent, reliable, and safe method for exporting and deploying trained models. Current formats, such as pickle and other binary formats, have significant problems, such as reliability, safety, and transparency issues. In contrast, PyMilo serializes ML models in a transparent non-executable format, enabling straightforward and safe model exchange, while also facilitating the deserialization and deployment of exported models in production environments. This package aims to provide a seamless, end-to-end solution for the exportation and importation of pre-trained ML models, which simplifies the model development and deployment pipeline. 

**Abstract (ZH)**: PyMilo 是一个开源的 Python 包，通过提供透明、可靠且安全的方法来导出和部署训练好的模型，解决了现有机器学习（ML）模型存储格式的局限性。当前的格式，如 pickle 及其他二进制格式，存在可靠性、安全性和透明性等方面的问题。相比之下，PyMilo 以一种透明且非执行的格式序列化 ML 模型，使得模型的简单且安全的交换成为可能，同时也便于在生产环境中反序列化和部署导出的模型。该包旨在提供从导出到导入预训练 ML 模型的无缝、端到端解决方案，简化了模型开发和部署流程。 

---
# TinyHelen's First Curriculum: Training and Evaluating Tiny Language Models in a Simpler Language Environment 

**Title (ZH)**: TinyHelen的第一个课程：在更简单的语言环境中训练和评估小型语言模型 

**Authors**: Ke Yang, Volodymyr Kindratenko, ChengXiang Zhai  

**Link**: [PDF](https://arxiv.org/pdf/2501.00522)  

**Abstract**: Training language models (LMs) and their application agents is increasingly costly due to large datasets and models, making test failures difficult to bear. Simplified language environments serve as primordial training and testing grounds, retaining essential commonsense and communication skills but in a more digestible form, potentially enhancing the learning efficiency of LMs, and thus reducing the required model size and data volume for effective training and evaluation. In these simplified language environments, workable strategies for small models, datasets, and agents may be adaptable to larger models, datasets, and agents in complex language environments.
To create such environments, we focus on two aspects: i) minimizing language dataset noise and complexity, and ii) preserving the essential text distribution characteristics. Unlike previous methods, we propose a pipeline to refine text data by eliminating noise, minimizing vocabulary, and maintaining genre-specific patterns (e.g., for books, conversation, code, etc.). Implementing this pipeline with large LMs, we have created a leaner suite of LM training and evaluation datasets: 71M Leaner-Pretrain, 7M Leaner-Instruct, Leaner-Glue for assessing linguistic proficiency, and Leaner-Eval for testing instruction-following ability.
Our experiments show that leaner pre-training boosts LM learning efficiency. Tiny LMs trained on these datasets outperform those trained on original datasets in instruction-following across different language granularity levels. Moreover, the Leaner-Pretrain dataset's alignment with conventional large LM training sets enables resource-optimized analysis of how learning objectives, model architectures, and training techniques impact performance on language modeling and downstream tasks. Our code and datasets are available at this https URL. 

**Abstract (ZH)**: 训练语言模型（LMs）及其应用代理的成本由于大型数据集和模型而逐渐增加，使得测试失败变得难以承受。简化语言环境作为最初的训练和测试场地，保留了核心常识和交流技能，并以更易于理解的形式呈现，这可能提高LM的学习效率，从而减少有效训练和评估所需的模型规模和数据量。在这些简化语言环境中，适用于小型模型、数据集和代理的工作策略可能在复杂语言环境中的大型模型、数据集和代理中具有可扩展性。
为了创建这样的环境，我们重点关注两个方面：i）减少语言数据集的噪声和复杂性，ii）保留基本的文本分布特征。与之前的方法不同，我们提出了一种管道方法，通过消除噪声、减少词汇量并保留特定类别的模式（例如，对于书籍、对话、代码等），来净化文本数据。使用大型LM实现这一管道后，我们创建了一套更精简的LM训练和评估数据集：71M Leaner-Pretrain、7M Leaner-Instruct、Learner-Glue 用于评估语言能力，Leaner-Eval 用于测试指令执行能力。
我们的实验显示，精简预训练可以提升LM的学习效率。使用这些数据集训练的小型LM在不同语言粒度级别的指令执行方面优于使用原始数据集训练的LM。此外，Leaner-Pretrain数据集与传统大型LM训练集的对齐使得资源优化分析学习目标、模型架构和训练技术对语言建模及下游任务性能的影响成为可能。我们的代码和数据集可在以下网址获取：this https URL。 

---
# A Method for Enhancing the Safety of Large Model Generation Based on Multi-dimensional Attack and Defense 

**Title (ZH)**: 基于多维度攻击与防御的方法以提升大型模型生成的安全性 

**Authors**: Keke Zhai  

**Link**: [PDF](https://arxiv.org/pdf/2501.00517)  

**Abstract**: Currently, large models are prone to generating harmful content when faced with complex attack instructions, significantly reducing their defensive capabilities. To address this issue, this paper proposes a method based on constructing data aligned with multi-dimensional attack defense to enhance the generative security of large models. The core of our method lies in improving the effectiveness of safe alignment learning for large models by innova-tively increasing the diversity of attack instruction dimensions and the accuracy of generat-ing safe responses. To validate the effectiveness of our method, beyond existing security evaluation benchmarks, we additionally designed new security evaluation benchmarks and conducted comparative experiments using Llama3.2 as the baseline model. The final ex-perimental results demonstrate that our method can significantly improve the generative security of large models under complex instructional attacks, while also maintaining and enhancing the models' general capabilities. 

**Abstract (ZH)**: 当前，大型模型在面对复杂的攻击指令时容易生成有害内容，显著降低了其防御能力。为解决这一问题，本文提出了一种基于构建多维度攻击防御对齐数据的方法，以增强大型模型的生成安全性。该方法的核心在于通过创新地增加攻击指令维度的多样性和生成安全响应的准确性，来提高大型模型的安全对齐学习效果。为验证该方法的有效性，除了使用现有的安全评估基准之外，我们还设计了新的安全评估基准，并以Llama3.2为基线模型进行了对比实验。最终的实验结果显示，该方法可以在复杂指令攻击下显著提高大型模型的生成安全性，同时保持和增强模型的一般能力。 

---
# H-Net: A Multitask Architecture for Simultaneous 3D Force Estimation and Stereo Semantic Segmentation in Intracardiac Catheters 

**Title (ZH)**: H-Net：一种用于同时实现心内导管中三维力估计和立体语义分割的多任务架构 

**Authors**: Pedram Fekri, Mehrdad Zadeh, Javad Dargahi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00514)  

**Abstract**: The success rate of catheterization procedures is closely linked to the sensory data provided to the surgeon. Vision-based deep learning models can deliver both tactile and visual information in a sensor-free manner, while also being cost-effective to produce. Given the complexity of these models for devices with limited computational resources, research has focused on force estimation and catheter segmentation separately. However, there is a lack of a comprehensive architecture capable of simultaneously segmenting the catheter from two different angles and estimating the applied forces in 3D. To bridge this gap, this work proposes a novel, lightweight, multi-input, multi-output encoder-decoder-based architecture. It is designed to segment the catheter from two points of view and concurrently measure the applied forces in the x, y, and z directions. This network processes two simultaneous X-Ray images, intended to be fed by a biplane fluoroscopy system, showing a catheter's deflection from different angles. It uses two parallel sub-networks with shared parameters to output two segmentation maps corresponding to the inputs. Additionally, it leverages stereo vision to estimate the applied forces at the catheter's tip in 3D. The architecture features two input channels, two classification heads for segmentation, and a regression head for force estimation through a single end-to-end architecture. The output of all heads was assessed and compared with the literature, demonstrating state-of-the-art performance in both segmentation and force estimation. To the best of the authors' knowledge, this is the first time such a model has been proposed 

**Abstract (ZH)**: 导管插入手术的成功率与提供的感觉数据密切相关。基于视觉的深度学习模型能够在无传感器的情况下提供触觉和视觉信息，同时成本效益高。由于这些模型对于计算资源有限的设备而言结构复杂，研究重点集中在力估计和导管分割上。然而，目前缺乏一种能够同时从两个角度分割导管并从三维角度估计所施加的力的综合架构。为填补这一空白，本研究提出了一种新型的轻量级多输入多输出编码-解码架构。该架构旨在从两个角度分割导管，并同时测量$x$、$y$和$z$方向的力。该网络处理由双平面 fluoroscopy 系统提供的两个同时的 X 射线图像，分别从不同角度展示导管的偏折情况。它利用两个具有共享参数的并行子网络输出与输入对应的两个分割图。此外，该网络利用立体视觉在三维方向上估计导管尖端处所施加的力。该架构包含两个输入通道、两个用于分割的分类头以及一个用于通过单一端到端架构估计力的回归头。所有头的输出被评估并与其他文献进行比较，显示出在分割和力估计方面的先进性能。据作者所知，这是首次提出此类模型。 

---
# Exploring Physics-Informed Neural Networks for Crop Yield Loss Forecasting 

**Title (ZH)**: 探索物理知情神经网络在作物产量损失预测中的应用 

**Authors**: Miro Miranda, Marcela Charfuelan, Andreas Dengel  

**Link**: [PDF](https://arxiv.org/pdf/2501.00502)  

**Abstract**: In response to climate change, assessing crop productivity under extreme weather conditions is essential to enhance food security. Crop simulation models, which align with physical processes, offer explainability but often perform poorly. Conversely, machine learning (ML) models for crop modeling are powerful and scalable yet operate as black boxes and lack adherence to crop growths physical principles. To bridge this gap, we propose a novel method that combines the strengths of both approaches by estimating the water use and the crop sensitivity to water scarcity at the pixel level. This approach enables yield loss estimation grounded in physical principles by sequentially solving the equation for crop yield response to water scarcity, using an enhanced loss function. Leveraging Sentinel-2 satellite imagery, climate data, simulated water use data, and pixel-level yield data, our model demonstrates high accuracy, achieving an R2 of up to 0.77, matching or surpassing state-of-the-art models like RNNs and Transformers. Additionally, it provides interpretable and physical consistent outputs, supporting industry, policymakers, and farmers in adapting to extreme weather conditions. 

**Abstract (ZH)**: 为了应对气候变化，评估在极端天气条件下的作物生产力对于增强食物安全至关重要。传统的作物模拟模型虽然遵循物理过程，但往往表现不佳。相比之下，机器学习（ML）模型在作物建模方面具有强大的能力和可扩展性，但也存在黑箱操作且不符合作物生长的物理原理。为了解决这一问题，我们提出了一种结合两种方法优点的新方法，通过在像素级别估计水利用和作物对水分稀缺的敏感性。这种方法通过逐次解决作物产量对水分稀缺响应的方程，并使用增强的损失函数，实现了基于物理原理的产量损失估计。利用Sentinel-2卫星图像、气候数据、模拟的水利用数据和像素级别的产量数据，我们的模型表现出高度的准确性，R2值最高可达0.77，与其它前沿模型（如RNN和Transformers）相当或超越。此外，该模型提供可解释且物理一致的输出，有助于行业、政策制定者和农民适应极端天气条件。 

---
# Differentiable Prompt Learning for Vision Language Models 

**Title (ZH)**: 视觉语言模型的可微提示学习 

**Authors**: Zhenhan Huang, Tejaswini Pedapati, Pin-Yu Chen, Jianxi Gao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00457)  

**Abstract**: Prompt learning is an effective way to exploit the potential of large-scale pre-trained foundational models. Continuous prompts parameterize context tokens in prompts by turning them into differentiable vectors. Deep continuous prompts insert prompts not only in the input but also in the intermediate hidden representations. Manually designed deep continuous prompts exhibit a remarkable improvement compared to the zero-shot pre-trained model on downstream tasks. How to automate the continuous prompt design is an underexplored area, and a fundamental question arises, is manually designed deep prompt strategy optimal? To answer this question, we propose a method dubbed differentiable prompt learning (DPL). The DPL method is formulated as an optimization problem to automatically determine the optimal context length of the prompt to be added to each layer, where the objective is to maximize the performance. We test the DPL method on the pre-trained CLIP. We empirically find that by using only limited data, our DPL method can find deep continuous prompt configuration with high confidence. The performance on the downstream tasks exhibits the superiority of the automatic design: our method boosts the average test accuracy by 2.60% on 11 datasets compared to baseline methods. Besides, our method focuses only on the prompt configuration (i.e. context length for each layer), which means that our method is compatible with the baseline methods that have sophisticated designs to boost the performance. The DPL method can be deployed to large language models or computer vision models at no cost. 

**Abstract (ZH)**: 预训练基础模型的潜力可以通过提示学习有效地加以利用。连续提示通过将提示中的上下文标记参数化为可微分向量，来实现对上下文信息的细粒度控制。深层连续提示不仅在输入中插入提示，还在中间隐藏表示中插入提示。与零样本预训练模型相比，手工设计的深层连续提示在下游任务中表现出显著的改进。如何自动设计连续提示是未充分探索的领域，一个基本的问题随之产生：手工设计的深层提示策略是否是最优的？为回答这一问题，我们提出了一种名为可微提示学习（Differentiable Prompt Learning, DPL）的方法。DPL方法被表述为一个优化问题，用于自动确定要在每一层中添加提示的最优上下文长度，目标是最大化模型性能。我们测试了DPL方法在预训练的CLIP模型上的应用。实验结果显示，通过使用有限的数据，我们的DPL方法可以找到具有高置信度的深层连续提示配置。在下游任务上的性能表明，自动设计具有显著优势：相比基线方法，我们的方法在11个数据集上将平均测试准确度提升了2.60%。此外，我们的方法仅关注提示配置（即每一层的上下文长度），这意味着我们的方法与那些为提高性能而采用复杂设计的基线方法兼容。DPL方法可以在大型语言模型或计算机视觉模型中无需成本地部署。 

---
# Do Students with Different Personality Traits Demonstrate Different Physiological Signals in Video-based Learning? 

**Title (ZH)**: 不同个性特质的学生在基于视频的学习中是否表现出不同的生理信号？ 

**Authors**: Chun-Hsiung Tseng, Hao-Chiang Koong Lin, Yung-Hui Chen, Jia-Rou Lin, Andrew Chih-Wei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00449)  

**Abstract**: Past researches show that personality trait is a strong predictor for ones academic performance. Today, mature and verified marker systems for assessing personality traits already exist. However, marker systems-based assessing methods have their own limitations. For example, dishonest responses cannot be avoided. In this research, the goal is to develop a method that can overcome the limitations. The proposed method will rely on physiological signals for the assessment. Thirty participants have participated in this experiment. Based on the statistical results, we found that there are correlations between students personality traits and their physiological signal change when learning via videos. Specifically, we found that participants degree of extraversion, agreeableness, conscientiousness, and openness to experiences are correlated with the variance of heart rates, the variance of GSR values, and the skewness of voice frequencies, etc. 

**Abstract (ZH)**: 过去的研究表明，个性特质是预测个体学术表现的一个强有力的因素。如今，已经存在成熟且经过验证的指标系统来评估个性特质。然而，基于指标系统的评估方法也存在一定的局限性，例如无法避免不诚实的回答。在这项研究中，目标是开发一种能够克服这些局限性的方法。本方法将依赖于生理信号来进行评估。共有三十名参与者参与了此次实验。根据统计结果，我们发现学生在通过视频学习时的个性特质与生理信号变化之间存在关联。具体而言，我们发现参与者外向性、宜人性、尽责性和开放性等个性特质与其心率变异性的变化、皮肤电导率值变异性的变化以及声音频率偏斜度等之间的相关性。 

---
# Generalizing Trust: Weak-to-Strong Trustworthiness in Language Models 

**Title (ZH)**: 泛化信任：语言模型中的弱可信性到强可信性 

**Authors**: Martin Pawelczyk, Lillian Sun, Zhenting Qi, Aounon Kumar, Himabindu Lakkaraju  

**Link**: [PDF](https://arxiv.org/pdf/2501.00418)  

**Abstract**: The rapid proliferation of generative AI, especially large language models, has led to their integration into a variety of applications. A key phenomenon known as weak-to-strong generalization - where a strong model trained on a weak model's outputs surpasses the weak model in task performance - has gained significant attention. Yet, whether critical trustworthiness properties such as robustness, fairness, and privacy can generalize similarly remains an open question. In this work, we study this question by examining if a stronger model can inherit trustworthiness properties when fine-tuned on a weaker model's outputs, a process we term weak-to-strong trustworthiness generalization. To address this, we introduce two foundational training strategies: 1) Weak Trustworthiness Finetuning (Weak TFT), which leverages trustworthiness regularization during the fine-tuning of the weak model, and 2) Weak and Weak-to-Strong Trustworthiness Finetuning (Weak+WTS TFT), which extends regularization to both weak and strong models. Our experimental evaluation on real-world datasets reveals that while some trustworthiness properties, such as fairness, adversarial, and OOD robustness, show significant improvement in transfer when both models were regularized, others like privacy do not exhibit signs of weak-to-strong trustworthiness. As the first study to explore trustworthiness generalization via weak-to-strong generalization, our work provides valuable insights into the potential and limitations of weak-to-strong generalization. 

**Abstract (ZH)**: 生成式AI的迅速发展，特别是大型语言模型的应用日益广泛。一个被称为“弱到强泛化”的关键现象逐渐受到关注，即一个基于较弱模型输出训练的强大模型在任务性能上超越了较弱模型。然而，诸如鲁棒性、公平性和隐私等关键信任属性是否也能类似地泛化，仍然是一个开放的问题。在本文中，我们通过研究是否一个较强模型在基于较弱模型输出进行微调时能够继承这些信任属性来探讨这一问题，这一过程我们称之为弱到强的信任属性泛化。为了应对这一挑战，我们引入了两种基本的训练策略：1) 轻量化信任属性微调（弱TFT），该策略利用信任属性正则化来微调较弱模型；2) 轻量化及弱到强信任属性微调（弱+WTS TFT），该策略将正则化扩展到较弱和较强模型。我们在真实数据集上的实验评价表明，尽管一些信任属性，如公平性、对抗性和OOD鲁棒性，在两个模型均进行正则化的情况下表现出显著的转移改进，但其他属性如隐私并未显示出明显的弱到强信任属性泛化的迹象。作为首次探讨通过弱到强泛化来实现信任属性泛化的研究，本文为我们提供了关于弱到强泛化的潜力和局限性的宝贵见解。 

---
# TSPE: Task-Specific Prompt Ensemble for Improved Zero-Shot Audio Classification 

**Title (ZH)**: TSPE：面向任务的提示集合方法以提高零样本音频分类性能 

**Authors**: Nishit Anand, Ashish Seth, Ramani Duraiswami, Dinesh Manocha  

**Link**: [PDF](https://arxiv.org/pdf/2501.00398)  

**Abstract**: Audio-language models (ALMs) excel in zero-shot audio classification, a task where models classify previously unseen audio clips at test time by leveraging descriptive natural language prompts. We introduce TSPE (Task-Specific Prompt Ensemble), a simple, training-free hard prompting method that boosts ALEs' zero-shot performance by customizing prompts for diverse audio classification tasks. Rather than using generic template-based prompts like "Sound of a car" we generate context-rich prompts, such as "Sound of a car coming from a tunnel". Specifically, we leverage label information to identify suitable sound attributes, such as "loud" and "feeble", and appropriate sound sources, such as "tunnel" and "street" and incorporate this information into the prompts used by Audio-Language Models (ALMs) for audio classification. Further, to enhance audio-text alignment, we perform prompt ensemble across TSPE-generated task-specific prompts. When evaluated on 12 diverse audio classification datasets, TSPE improves performance across ALMs by showing an absolute improvement of 1.23-16.36% over vanilla zero-shot evaluation. 

**Abstract (ZH)**: 音频语言模型（ALMs）在零样本音频分类任务中表现出色，该任务要求模型通过利用描述性的自然语言提示，在测试时对未见过的音频片段进行分类。我们引入了TSPE（任务特定提示集合），这是一种简单且无需训练的硬提示方法，通过为多样化的音频分类任务量身定制提示，提升了ALMs的零样本性能。与使用通用模板提示（如“汽车的声音”）不同，我们生成了包含丰富上下文的提示，例如“隧道中的汽车声音”。具体而言，我们利用标签信息来识别合适的音频属性，如“响亮”和“微弱”，以及适当的声源，如“隧道”和“街道”，并将这些信息整合到用于音频分类的音频语言模型（ALMs）的提示中。此外，为了增强音频文本的对齐，我们在TSPE生成的任务特定提示之间进行了提示集合。在对12个不同音频分类数据集进行评估时，TSPE在ALMs上取得了显著的性能提升，相对于传统的零样本评估，其绝对性能改进为1.23%-16.36%。 

---
# Efficient Relational Context Perception for Knowledge Graph Completion 

**Title (ZH)**: 高效的关系上下文感知方法在知识图谱完成中的应用 

**Authors**: Wenkai Tu, Guojia Wan, Zhengchun Shang, Bo Du  

**Link**: [PDF](https://arxiv.org/pdf/2501.00397)  

**Abstract**: Knowledge Graphs (KGs) provide a structured representation of knowledge but often suffer from challenges of incompleteness. To address this, link prediction or knowledge graph completion (KGC) aims to infer missing new facts based on existing facts in KGs. Previous knowledge graph embedding models are limited in their ability to capture expressive features, especially when compared to deeper, multi-layer models. These approaches also assign a single static embedding to each entity and relation, disregarding the fact that entities and relations can exhibit different behaviors in varying graph contexts. Due to complex context over a fact triple of a KG, existing methods have to leverage complex non-linear context encoder, like transformer, to project entity and relation into low dimensional representations, resulting in high computation cost. To overcome these limitations, we propose Triple Receptance Perception (TRP) architecture to model sequential information, enabling the learning of dynamic context of entities and relations. Then we use tensor decomposition to calculate triple scores, providing robust relational decoding capabilities. This integration allows for more expressive representations. Experiments on benchmark datasets such as YAGO3-10, UMLS, FB15k, and FB13 in link prediction and triple classification tasks demonstrate that our method performs better than several state-of-the-art models, proving the effectiveness of the integration. 

**Abstract (ZH)**: 知识图谱（KGs）提供了一种结构化的知识表示形式，但常常面临不完整性的挑战。为了应对这一问题，链接预测或知识图谱补全（KGC）旨在根据KG中已有的事实推断缺失的新事实。之前的知识图嵌入模型在捕捉表达性特征方面能力有限，尤其是在与更深更多层次的模型相比时。这些方法还为每个实体和关系分配一个单一的静态嵌入，忽视了实体和关系在不同图上下文中的行为差异。由于KG的三元组需要复杂的上下文信息，现有方法不得不借助如变换器这样的复杂非线性上下文编码器，将实体和关系投影到低维度表示中，从而导致了高计算成本。为克服这些限制，我们提出了三元组感知接收器架构（Triple Receptance Perception, TRP），用于建模序列信息，允许学习实体和关系的动态上下文。然后，我们使用张量分解来计算三元组得分，提供强大的关系解码能力。这种集成使得能够获得更具表达性的表示形式。在链路预测和三元组分类任务中的基准数据集（如YAGO3-10、UMLS、FB15k和FB13）上的实验表明，我们的方法优于几种最先进的模型，证明了该集成的有效性。 

---
# Proactive Conversational Agents with Inner Thoughts 

**Title (ZH)**: 具有内在思考能力的前瞻性对话代理 

**Authors**: Xingyu Bruce Liu, Shitao Fang, Weiyan Shi, Chien-Sheng Wu, Takeo Igarashi, Xiang `Anthony' Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00383)  

**Abstract**: One of the long-standing aspirations in conversational AI is to allow them to autonomously take initiatives in conversations, i.e., being proactive. This is especially challenging for multi-party conversations. Prior NLP research focused mainly on predicting the next speaker from contexts like preceding conversations. In this paper, we demonstrate the limitations of such methods and rethink what it means for AI to be proactive in multi-party, human-AI conversations. We propose that just like humans, rather than merely reacting to turn-taking cues, a proactive AI formulates its own inner thoughts during a conversation, and seeks the right moment to contribute. Through a formative study with 24 participants and inspiration from linguistics and cognitive psychology, we introduce the Inner Thoughts framework. Our framework equips AI with a continuous, covert train of thoughts in parallel to the overt communication process, which enables it to proactively engage by modeling its intrinsic motivation to express these thoughts. We instantiated this framework into two real-time systems: an AI playground web app and a chatbot. Through a technical evaluation and user studies with human participants, our framework significantly surpasses existing baselines on aspects like anthropomorphism, coherence, intelligence, and turn-taking appropriateness. 

**Abstract (ZH)**: 在对话式人工智能领域的一个长期追求目标是使它们能够在对话中主动采取行动，即表现出主动性。这在多对话语境中尤为具有挑战性。此前的自然语言处理（NLP）研究主要集中在从上下文（如之前的对话）预测下一个发言者。在本文中，我们探讨了这类方法的局限性，并重新思考在多对人机对话中“主动性”的含义。我们认为，如同人类一样，主动性的AI不仅应对轮换提示做出反应，还要在对话中形成自己的内在想法，并寻找合适的时刻参与对话。通过一项包含24名参与者的形成性研究，并结合语言学和认知心理学的启发，我们提出了“内心想法”框架。该框架让AI在显式的沟通过程之外，持续地保持着内在的思考，这使其能够通过模型其表达这些想法的内在动机来主动参与对话。我们将这一框架应用于两个实时系统：一个AI游乐场网页应用和一个聊天机器人。通过技术评估和涉及人类参与者的用户研究，我们的框架在拟人性、连贯性、智能性和轮换适宜性等方面显著超越了现有基准。 

---
# Adventures in Demand Analysis Using AI 

**Title (ZH)**: 使用AI进行需求分析的探险之旅 

**Authors**: Philipp Bach, Victor Chernozhukov, Sven Klaassen, Martin Spindler, Jan Teichert-Kluge, Suhas Vijaykumar  

**Link**: [PDF](https://arxiv.org/pdf/2501.00382)  

**Abstract**: This paper advances empirical demand analysis by integrating multimodal product representations derived from artificial intelligence (AI). Using a detailed dataset of toy cars on \textit{this http URL}, we combine text descriptions, images, and tabular covariates to represent each product using transformer-based embedding models. These embeddings capture nuanced attributes, such as quality, branding, and visual characteristics, that traditional methods often struggle to summarize. Moreover, we fine-tune these embeddings for causal inference tasks. We show that the resulting embeddings substantially improve the predictive accuracy of sales ranks and prices and that they lead to more credible causal estimates of price elasticity. Notably, we uncover strong heterogeneity in price elasticity driven by these product-specific features. Our findings illustrate that AI-driven representations can enrich and modernize empirical demand analysis. The insights generated may also prove valuable for applied causal inference more broadly. 

**Abstract (ZH)**: 本文通过将多种模态的产品表示整合到经验需求分析中，推动了该领域的进步。这些产品表示是从人工智能（AI）中提取的，我们使用一个详细的玩具车数据集（\textit{参见网址: ...}），结合文本描述、图像和表格式协变量来表示每个产品，采用基于转换器的嵌入模型。这些嵌入模型能够捕捉到传统方法难以总结的细微特性，如质量、品牌和视觉特征。此外，我们还将这些嵌入模型微调用于因果推断任务。研究显示，由此产生的嵌入模型在销售排名和价格预测准确性方面有了显著提升，并且能够产生更可信的价格弹性因果估计。值得注意的是，这些产品特定特征导致了显著的价格弹性异质性。我们的研究结果表明，AI驱动的表示可以丰富和现代化工症需求分析。生成的见解也可能对更广泛的实证因果推断有所帮助。 

---
# Design Optimizer for Soft Growing Robot Manipulators in Three-Dimensional Environments 

**Title (ZH)**: 三维环境中软生长机器人 manipulator 的设计优化器 

**Authors**: Ahmet Astar, Ozan Nurcan, Erk Demirel, Emir Ozen, Ozan Kutlar, Fabio Stroppa  

**Link**: [PDF](https://arxiv.org/pdf/2501.00368)  

**Abstract**: Soft growing robots are novel devices that mimic plant-like growth for navigation in cluttered or dangerous environments. Their ability to adapt to surroundings, combined with advancements in actuation and manufacturing technologies, allows them to perform specialized manipulation tasks. This work presents an approach for design optimization of soft growing robots; specifically, the three-dimensional extension of the optimizer designed for planar manipulators. This tool is intended to be used by engineers and robot enthusiasts before manufacturing their robot: it suggests the optimal size of the robot for solving a specific task. The design process models a multi-objective optimization problem to refine a soft manipulator's kinematic chain. Thanks to the novel Rank Partitioning algorithm integrated into Evolutionary Computation (EC) algorithms, this method achieves high precision in reaching targets and is efficient in resource usage. Results show significantly high performance in solving three-dimensional tasks, whereas comparative experiments indicate that the optimizer features robust output when tested with different EC algorithms, particularly genetic algorithms. 

**Abstract (ZH)**: 软生长机器人是新型装置，能够模仿植物生长方式，在乱序或危险环境中进行导航。它们适应环境的能力，结合了驱动技术和制造技术的进步，使其能够执行特定的操纵任务。本文提出了一种软生长机器人设计优化方法，尤其是针对平面操纵器设计优化器的三维扩展方法。该工具旨在供工程师和机器人爱好者在制造机器人之前使用：它建议了为解决特定任务所需的最优机器人尺寸。设计过程将多目标优化问题建模，以细化软操纵器的运动链。通过集成到进化计算（EC）算法中的新颖排秩分区算法，该方法在达到目标方面实现了高精度，并且在资源使用方面表现出高效性。结果表明，在解决三维任务方面具有很高的性能。而比较实验表明，使用不同进化的计算算法（尤其是遗传算法）进行测试时，优化器展现出稳健的输出结果。 

---
# Low-Rank Adaptation for Foundation Models: A Comprehensive Review 

**Title (ZH)**: 基础模型的低秩适应性：综述 

**Authors**: Menglin Yang, Jialin Chen, Yifei Zhang, Jiahong Liu, Jiasheng Zhang, Qiyao Ma, Harshit Verma, Qianru Zhang, Min Zhou, Irwin King, Rex Ying  

**Link**: [PDF](https://arxiv.org/pdf/2501.00365)  

**Abstract**: The rapid advancement of foundation modelslarge-scale neural networks trained on diverse, extensive datasetshas revolutionized artificial intelligence, enabling unprecedented advancements across domains such as natural language processing, computer vision, and scientific discovery. However, the substantial parameter count of these models, often reaching billions or trillions, poses significant challenges in adapting them to specific downstream tasks. Low-Rank Adaptation (LoRA) has emerged as a highly promising approach for mitigating these challenges, offering a parameter-efficient mechanism to fine-tune foundation models with minimal computational overhead. This survey provides the first comprehensive review of LoRA techniques beyond large Language Models to general foundation models, including recent techniques foundations, emerging frontiers and applications of low-rank adaptation across multiple domains. Finally, this survey discusses key challenges and future research directions in theoretical understanding, scalability, and robustness. This survey serves as a valuable resource for researchers and practitioners working with efficient foundation model adaptation. 

**Abstract (ZH)**: 基础模型的快速发展，这些模型是基于多样性和大规模数据集训练的大型神经网络，已经彻底改变了人工智能领域，推动了自然语言处理、计算机视觉和科学发现等多个领域的前所未有的进步。然而，这些模型的庞大参数量常常达到数十亿甚至数百亿，给将它们适应特定的下游任务带来了重大挑战。低秩适应（LoRA）作为一种高度有前途的方法，已经出现，它提供了一种高效的机制，可以在最小的计算开销下对基础模型进行微调。本文综述了LoRA技术，除了大型语言模型之外，还涵盖了通用基础模型，包括最新的基础模型、低秩适应在多个领域的新兴前沿和应用。最后，本文讨论了理论理解、可扩展性和鲁棒性方面的关键挑战和未来研究方向。本文为研究者和实践者提供了关于高效基础模型适应的宝贵资源。 

---
# RAG-Instruct: Boosting LLMs with Diverse Retrieval-Augmented Instructions 

**Title (ZH)**: RAG-Instruct：通过多样化检索增强指令提升大型语言模型 

**Authors**: Wanlong Liu, Junying Chen, Ke Ji, Li Zhou, Wenyu Chen, Benyou Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00353)  

**Abstract**: Retrieval-Augmented Generation (RAG) has emerged as a key paradigm for enhancing large language models (LLMs) by incorporating external knowledge. However, current RAG methods face two limitations: (1) they only cover limited RAG scenarios. (2) They suffer from limited task diversity due to the lack of a general RAG dataset. To address these limitations, we propose RAG-Instruct, a general method for synthesizing diverse and high-quality RAG instruction data based on any source corpus. Our approach leverages (1) five RAG paradigms, which encompass diverse query-document relationships, and (2) instruction simulation, which enhances instruction diversity and quality by utilizing the strengths of existing instruction datasets. Using this method, we construct a 40K instruction dataset from Wikipedia, comprehensively covering diverse RAG scenarios and tasks. Experiments demonstrate that RAG-Instruct effectively enhances LLMs' RAG capabilities, achieving strong zero-shot performance and significantly outperforming various RAG baselines across a diverse set of tasks. RAG-Instruct is publicly available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）已经成为通过引入外部知识来增强大语言模型（LLMs）的关键范式。然而，现有的RAG方法面临两个局限：（1）它们仅涵盖有限的RAG场景。（2）由于缺乏通用的RAG数据集，导致任务多样性有限。为了克服这些局限，我们提出了RAG-Instruct，这是一种基于任意来源语料库合成多样且高质量RAG指令数据的一般方法。我们的方法利用了以下两点：（1）五种RAG范式，涵盖了多样化的查询-文档关系；（2）指令模拟，通过利用现有指令数据集的长处来增强指令的多样性和质量。利用这种方法，我们从Wikipedia中构建了一个包含40,000条指令的数据集，全面覆盖了多样化的RAG场景和任务。实验表明，RAG-Instruct有效地增强了LLMs的RAG能力，实现了强大的零样本性能，并且在一系列任务上显著优于各种RAG基线方法。RAG-Instruct已在以下网址公开提供：[这里](this https URL)。 

---
# Temporal Information Reconstruction and Non-Aligned Residual in Spiking Neural Networks for Speech Classification 

**Title (ZH)**: 时空信息重构与非对齐残差在神经形态网络中的语音分类 

**Authors**: Qi Zhang, Huamin Wang, Hangchi Shen, Shukai Duan, Shiping Wen, Tingwen Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00348)  

**Abstract**: Recently, it can be noticed that most models based on spiking neural networks (SNNs) only use a same level temporal resolution to deal with speech classification problems, which makes these models cannot learn the information of input data at different temporal scales. Additionally, owing to the different time lengths of the data before and after the sub-modules of many models, the effective residual connections cannot be applied to optimize the training processes of these this http URL solve these problems, on the one hand, we reconstruct the temporal dimension of the audio spectrum to propose a novel method named as Temporal Reconstruction (TR) by referring the hierarchical processing process of the human brain for understanding speech. Then, the reconstructed SNN model with TR can learn the information of input data at different temporal scales and model more comprehensive semantic information from audio data because it enables the networks to learn the information of input data at different temporal resolutions. On the other hand, we propose the Non-Aligned Residual (NAR) method by analyzing the audio data, which allows the residual connection can be used in two audio data with different time lengths. We have conducted plentiful experiments on the Spiking Speech Commands (SSC), the Spiking Heidelberg Digits (SHD), and the Google Speech Commands v0.02 (GSC) datasets. According to the experiment results, we have achieved the state-of-the-art (SOTA) result 81.02\% on SSC for the test classification accuracy of all SNN models, and we have obtained the SOTA result 96.04\% on SHD for the classification accuracy of all models. 

**Abstract (ZH)**: 近年来，大多数基于脉冲神经网络（SNNs）的模型仅使用相同的时间分辨率来处理语音分类问题，这使得这些模型无法学习输入数据在不同时间尺度上的信息。此外，由于许多模型的子模块在时间和数据长度上的差异，有效的残差连接无法被应用于优化这些模型的训练过程。为了解决这些问题，一方面，我们借鉴人类大脑分层处理过程理解语音的方式，重构音频频谱的时间维度，提出了名为“时间重构”（TR）的方法。基于TR重构的SNN模型能够在不同时间尺度上学习输入数据的信息，并从音频数据中建模更全面的语义信息，因为这种方法使网络能够在不同时间分辨率下学习输入数据的信息。另一方面，我们通过分析音频数据提出了“非对齐残差”（NAR）方法，允许残差连接在具有不同时间长度的两种音频数据间使用。我们在Spiking Speech Commands（SSC）、Spiking Heidelberg Digits（SHD）和Google Speech Commands v0.02（GSC）数据集上进行了大量的实验。根据实验结果，我们在SSC数据集上的测试分类准确率达到了目前最先进的水平（SOTA），为81.02%，在SHD数据集上的分类准确率达到了目前最先进的水平（SOTA），为96.04%。 

---
# CNC: Cross-modal Normality Constraint for Unsupervised Multi-class Anomaly Detection 

**Title (ZH)**: CNC：跨模态正常性约束在无监督多类别异常检测中的应用 

**Authors**: Xiaolei Wang, Xiaoyang Wang, Huihui Bai, Eng Gee Lim, Jimin Xiao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00346)  

**Abstract**: Existing unsupervised distillation-based methods rely on the differences between encoded and decoded features to locate abnormal regions in test images. However, the decoder trained only on normal samples still reconstructs abnormal patch features well, degrading performance. This issue is particularly pronounced in unsupervised multi-class anomaly detection tasks. We attribute this behavior to over-generalization(OG) of decoder: the significantly increasing diversity of patch patterns in multi-class training enhances the model generalization on normal patches, but also inadvertently broadens its generalization to abnormal patches. To mitigate OG, we propose a novel approach that leverages class-agnostic learnable prompts to capture common textual normality across various visual patterns, and then apply them to guide the decoded features towards a normal textual representation, suppressing over-generalization of the decoder on abnormal patterns. To further improve performance, we also introduce a gated mixture-of-experts module to specialize in handling diverse patch patterns and reduce mutual interference between them in multi-class training. Our method achieves competitive performance on the MVTec AD and VisA datasets, demonstrating its effectiveness. 

**Abstract (ZH)**: 现有的无监督蒸馏方法依赖于编码和解码特征之间的差异来定位测试图像中的异常区域。然而，仅在正常样本上训练的解码器仍然能够很好地重建异常补丁特征，这会降低性能。在无监督多类异常检测任务中，这一问题尤为突出。我们归因于解码器的过度泛化（Over-Generalization, OG）现象：在多类训练中补丁模式的显著多样性增强了模型对正常补丁的泛化能力，但也随之增加了模型对异常补丁的泛化能力。为了缓解OG，我们提出了一种新的方法，该方法利用类无条件的学习提示来捕获各种视觉模式下的共同文本正常性，并将这些提示应用于引导解码特征向正常的文本表示靠拢，抑制解码器在异常模式上的过度泛化。为了进一步提高性能，我们还引入了一个门控专家混合模块来专门处理各种补丁模式，并在多类训练中减少它们之间的相互干扰。我们的方法在MVTec AD和VisA数据集上取得了竞争力的表现，展示了其有效性。 

---
# Chunk-Distilled Language Modeling 

**Title (ZH)**: 句块蒸馏语言建模 

**Authors**: Yanhong Li, Karen Livescu, Jiawei Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2501.00343)  

**Abstract**: We introduce Chunk-Distilled Language Modeling (CD-LM), an approach to text generation that addresses two challenges in current large language models (LLMs): the inefficiency of token-level generation, and the difficulty of adapting to new data and knowledge. Our method combines deep network-based LLMs with a straightforward retrieval module, which allows the generation of multi-token text chunks at a single decoding step. Our retrieval framework enables flexible construction of model- or domain-specific datastores, either leveraging the internal knowledge of existing models, or incorporating expert insights from human-annotated corpora. This adaptability allows for enhanced control over the language model's distribution without necessitating additional training. We present the CD-LM formulation along with performance metrics demonstrating its ability to improve language model performance and efficiency across a diverse set of downstream tasks. Code and data will be made publicly available. 

**Abstract (ZH)**: 我们将介绍片段提取语言模型（CD-LM），这是一种解决当前大型语言模型（LLMs）中的两个挑战的方法： TOKEN 级别生成的低效率，以及适应新数据和知识的难度。我们的方法结合了基于深层网络的大型语言模型和一个简单的检索模块，该模块允许在单个解码步骤中生成多TOKEN 的文本片段。我们的检索框架允许灵活构建模型特定或领域特定的数据存储，无论是利用现有模型的内部知识，还是整合来自标注语料库的人类专家意见。这种可适应性使得对语言模型的分布进行增强控制成为可能，而无需额外训练。我们将展示 CD-LM 的建模框架，并提供性能指标来证明其在多种下游任务中提高语言模型性能和效率的能力。代码和数据将公开提供。 

---
# Loss-Aware Curriculum Learning for Chinese Grammatical Error Correction 

**Title (ZH)**: 面向损失的学习层次训练方法及其在中文语法错误修正中的应用 

**Authors**: Ding Zhang, Yangning Li, Lichen Bai, Hao Zhang, Yinghui Li, Haiye Lin, Hai-Tao Zheng, Xin Su, Zifei Shan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00334)  

**Abstract**: Chinese grammatical error correction (CGEC) aims to detect and correct errors in the input Chinese sentences. Recently, Pre-trained Language Models (PLMS) have been employed to improve the performance. However, current approaches ignore that correction difficulty varies across different instances and treat these samples equally, enhancing the challenge of model learning. To address this problem, we propose a multi-granularity Curriculum Learning (CL) framework. Specifically, we first calculate the correction difficulty of these samples and feed them into the model from easy to hard batch by batch. Then Instance-Level CL is employed to help the model optimize in the appropriate direction automatically by regulating the loss function. Extensive experimental results and comprehensive analyses of various datasets prove the effectiveness of our method. 

**Abstract (ZH)**: 中文翻译如下，符合学术规范：

中文语法错误修正（CGEC）旨在检测并修正输入的中文句子中的错误。近年来，预训练语言模型（PLMs）被用于提高性能。然而，当前的方法忽略了错误修正的难度在不同实例之间存在差异，并且对待这些样本一视同仁，从而增加了模型学习的挑战。为了应对这一问题，我们提出了一种多粒度层次教学（Curriculum Learning, CL）框架。具体来说，我们首先计算这些样本的修正难度，并按照从简单到复杂的顺序逐批次输入模型。然后，我们采用实例级层次教学，通过调节损失函数自动引导模型优化到适当的方向。广泛的实验结果和对多种数据集的综合分析证明了我们方法的有效性。 

---
# Exploring the Implicit Semantic Ability of Multimodal Large Language Models: A Pilot Study on Entity Set Expansion 

**Title (ZH)**: 探索多模态大型语言模型的隐含语义能力：一个关于实体集扩展的初步研究 

**Authors**: Hebin Wang, Yangning Li, Yinghui Li, Hai-Tao Zheng, Wenhao Jiang, Hong-Gee Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.00330)  

**Abstract**: The rapid development of multimodal large language models (MLLMs) has brought significant improvements to a wide range of tasks in real-world applications. However, LLMs still exhibit certain limitations in extracting implicit semantic information. In this paper, we apply MLLMs to the Multi-modal Entity Set Expansion (MESE) task, which aims to expand a handful of seed entities with new entities belonging to the same semantic class, and multi-modal information is provided with each entity. We explore the capabilities of MLLMs to understand implicit semantic information at the entity-level granularity through the MESE task, introducing a listwise ranking method LUSAR that maps local scores to global rankings. Our LUSAR demonstrates significant improvements in MLLM's performance on the MESE task, marking the first use of generative MLLM for ESE tasks and extending the applicability of listwise ranking. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）的快速发展已在众多实际应用任务中带来了显著的进展。然而，大型语言模型在提取隐含语义信息方面仍存在一定的局限性。本文将MLLMs应用到多模态实体集扩展（MESE）任务中，MESE任务旨在通过提供每个实体的多模态信息，扩展少量的种子实体至相同语义类的新实体。我们通过MESE任务探索MLLMs在实体级粒度上理解隐含语义信息的能力，并引入了一种列表式排名方法LUSAR，该方法将局部得分映射到全局排名。我们的LUSAR在MESE任务中显著提升了MLLMs的表现，标志着首次将生成型MLLMs应用于ESE任务，并扩展了列表式排名的应用范围。 

---
# OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning 

**Title (ZH)**: OCRBench v2：用于评估大型多模态模型在视觉文本定位与推理方面性能的改进基准 

**Authors**: Ling Fu, Biao Yang, Zhebin Kuang, Jiajun Song, Yuzhe Li, Linghao Zhu, Qidi Luo, Xinyu Wang, Hao Lu, Mingxin Huang, Zhang Li, Guozhi Tang, Bin Shan, Chunhui Lin, Qi Liu, Binghong Wu, Hao Feng, Hao Liu, Can Huang, Jingqun Tang, Wei Chen, Lianwen Jin, Yuliang Liu, Xiang Bai  

**Link**: [PDF](https://arxiv.org/pdf/2501.00321)  

**Abstract**: Scoring the Optical Character Recognition (OCR) capabilities of Large Multimodal Models (LMMs) has witnessed growing interest recently. Existing benchmarks have highlighted the impressive performance of LMMs in text recognition; however, their abilities on certain challenging tasks, such as text localization, handwritten content extraction, and logical reasoning, remain underexplored. To bridge this gap, we introduce OCRBench v2, a large-scale bilingual text-centric benchmark with currently the most comprehensive set of tasks (4x more tasks than the previous multi-scene benchmark OCRBench), the widest coverage of scenarios (31 diverse scenarios including street scene, receipt, formula, diagram, and so on), and thorough evaluation metrics, with a total of 10,000 human-verified question-answering pairs and a high proportion of difficult samples. After carefully benchmarking state-of-the-art LMMs on OCRBench v2, we find that 20 out of 22 LMMs score below 50 (100 in total) and suffer from five-type limitations, including less frequently encountered text recognition, fine-grained perception, layout perception, complex element parsing, and logical reasoning. The benchmark and evaluation scripts are available at this https URL. 

**Abstract (ZH)**: 近年来，对大型多模态模型（LMMs）的光学字符识别（OCR）能力进行评分的兴趣逐渐增加。现有的基准测试突出显示了LMMs在文本识别方面令人印象深刻的性能，但它们在某些具有挑战性的任务，如文本定位、手写内容提取和逻辑推理方面的能力尚未得到充分探索。为解决这一问题，我们引入了OCRBench v2，这是一个大规模双语文本中心的基准测试，包含目前最全面的任务集（比之前的多场景基准测试OCRBench多4倍的任务），涵盖了最广泛的场景（包括街头场景、收据、公式、图表等31种不同的场景），并具有详细的评估指标，总共有10,000个经人工验证的问题-答案对，困难样本占比较大。经过精细的基准测试后，我们发现，在OCRBench v2上，22种最先进的LMM中有20种得分低于50分（满分100分），并且面临着五种类型的限制，包括不常见的文本识别、细粒度感知、布局感知、复杂元素解析和逻辑推理。该基准测试和评估脚本可在以下链接获取：[此链接](https://)。 

---
# M2I2: Learning Efficient Multi-Agent Communication via Masked State Modeling and Intention Inference 

**Title (ZH)**: M2I2：通过掩蔽状态建模和意图推理学习高效的多Agent通信 

**Authors**: Chuxiong Sun, Peng He, Qirui Ji, Zehua Zang, Jiangmeng Li, Rui Wang, Wei Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00312)  

**Abstract**: Communication is essential in coordinating the behaviors of multiple agents. However, existing methods primarily emphasize content, timing, and partners for information sharing, often neglecting the critical aspect of integrating shared information. This gap can significantly impact agents' ability to understand and respond to complex, uncertain interactions, thus affecting overall communication efficiency. To address this issue, we introduce M2I2, a novel framework designed to enhance the agents' capabilities to assimilate and utilize received information effectively. M2I2 equips agents with advanced capabilities for masked state modeling and joint-action prediction, enriching their perception of environmental uncertainties and facilitating the anticipation of teammates' intentions. This approach ensures that agents are furnished with both comprehensive and relevant information, bolstering more informed and synergistic behaviors. Moreover, we propose a Dimensional Rational Network, innovatively trained via a meta-learning paradigm, to identify the importance of dimensional pieces of information, evaluating their contributions to decision-making and auxiliary tasks. Then, we implement an importance-based heuristic for selective information masking and sharing. This strategy optimizes the efficiency of masked state modeling and the rationale behind information sharing. We evaluate M2I2 across diverse multi-agent tasks, the results demonstrate its superior performance, efficiency, and generalization capabilities, over existing state-of-the-art methods in various complex scenarios. 

**Abstract (ZH)**: 沟通在协调多个代理的行为中至关重要。然而，现有的方法主要强调信息共享的内容、时机和伙伴，往往忽视了整合共享信息这一关键方面。这一缺口可能严重影响代理对复杂和不确定互动的理解和响应能力，从而影响整体通信效率。为了解决这个问题，我们提出了M2I2这一新颖框架，旨在增强代理有效吸收和利用接收到信息的能力。M2I2赋予代理高级的掩蔽状态建模和联合行动预测能力，丰富了它们对环境不确定性感知的能力，并促进了对队友意图的预见。这种方法确保代理不仅获得全面且相关的信息，还能促进更具信息性和协同性的行为。此外，我们提出了一种维度理性网络，通过元学习范式进行创新训练，以识别各个维度信息的重要性，并评估其对决策和支持任务的贡献。然后，我们实现了一种基于重要性的启发式选择，进行信息的掩蔽和共享。该策略优化了掩蔽状态建模的效率以及信息共享的合理性。我们在多种多代理任务中评估了M2I2，结果显示该方法在各种复杂场景中具有优于现有最先进的方法的性能、效率和泛化能力。 

---
# Fast and Interpretable Mixed-Integer Linear Program Solving by Learning Model Reduction 

**Title (ZH)**: 快速且可解释的混合整数线性规划求解方法学习模型简化 

**Authors**: Yixuan Li, Can Chen, Jiajun Li, Jiahui Duan, Xiongwei Han, Tao Zhong, Vincent Chau, Weiwei Wu, Wanyuan Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00307)  

**Abstract**: By exploiting the correlation between the structure and the solution of Mixed-Integer Linear Programming (MILP), Machine Learning (ML) has become a promising method for solving large-scale MILP problems. Existing ML-based MILP solvers mainly focus on end-to-end solution learning, which suffers from the scalability issue due to the high dimensionality of the solution space. Instead of directly learning the optimal solution, this paper aims to learn a reduced and equivalent model of the original MILP as an intermediate step. The reduced model often corresponds to interpretable operations and is much simpler, enabling us to solve large-scale MILP problems much faster than existing commercial solvers. However, current approaches rely only on the optimal reduced model, overlooking the significant preference information of all reduced models. To address this issue, this paper proposes a preference-based model reduction learning method, which considers the relative performance (i.e., objective cost and constraint feasibility) of all reduced models on each MILP instance as preferences. We also introduce an attention mechanism to capture and represent preference information, which helps improve the performance of model reduction learning tasks. Moreover, we propose a SetCover based pruning method to control the number of reduced models (i.e., labels), thereby simplifying the learning process. Evaluation on real-world MILP problems shows that 1) compared to the state-of-the-art model reduction ML methods, our method obtains nearly 20% improvement on solution accuracy, and 2) compared to the commercial solver Gurobi, two to four orders of magnitude speedups are achieved. 

**Abstract (ZH)**: 通过利用混合整数线性规划（MILP）的问题结构与其解之间的相关性，机器学习（ML）已成为解决大规模MILP问题的有前景的方法。现有的基于ML的MILP求解器主要集中在端到端的解学习上，但由于解空间的高维性，这种方法存在可扩展性问题。本文的目标不是直接学习最优解，而是学习原始MILP的一个简化且等效的模型作为中间步骤。简化模型通常对应于可解释的操作，从而可以比现有的商用求解器更快地解决大规模MILP问题。然而，当前的方法仅依赖最优的简化模型，忽略了所有简化模型的显著偏好信息。为了应对这一问题，本文提出了一种基于偏好的模型简化学习方法，该方法将每个MILP实例中所有简化模型的相对性能（即目标成本和约束可行性）作为偏好进行考虑。同时，引入了注意力机制来捕捉和表示偏好信息，有助于提高模型简化学习任务的性能。此外，我们提出了一个基于集合覆盖的方法来控制简化模型的数量（即标签的数量），从而简化学习过程。对实际MILP问题的评估表明：1）与最先进的模型简化ML方法相比，本文的方法在解的准确性上获得了约20%的提升；2）与商用求解器Gurobi相比，实现了两个到四个数量级的速度提升。 

---
# Enhancing Deployment-Time Predictive Model Robustness for Code Analysis and Optimization 

**Title (ZH)**: 提升代码分析与优化中部署时预测模型的鲁棒性 

**Authors**: Huanting Wang, Patrick Lenihan, Zheng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00298)  

**Abstract**: Supervised machine learning techniques have shown promising results in code analysis and optimization problems. However, a learning-based solution can be brittle because minor changes in hardware or application workloads -- such as facing a new CPU architecture or code pattern -- may jeopardize decision accuracy, ultimately undermining model robustness. We introduce Prom, an open-source library to enhance the robustness and performance of predictive models against such changes during deployment. Prom achieves this by using statistical assessments to identify test samples prone to mispredictions and using feedback on these samples to improve a deployed model. We showcase Prom by applying it to 13 representative machine learning models across 5 code analysis and optimization tasks. Our extensive evaluation demonstrates that Prom can successfully identify an average of 96% (up to 100%) of mispredictions. By relabeling up to 5% of the Prom-identified samples through incremental learning, Prom can help a deployed model achieve a performance comparable to that attained during its model training phase. 

**Abstract (ZH)**: 监督机器学习技术已经在代码分析和优化问题上展示了令人鼓舞的结果。然而，基于学习的解决方案可能较为脆弱，因为硬件或应用程序负载中的微小变化——比如面对新的CPU架构或代码模式——可能会危害决策准确性，最终削弱模型的鲁棒性。我们引入了Prom这一开源库，旨在提高预测模型在部署过程中对这类变化的鲁棒性和性能。Prom通过使用统计评估来识别易出现误预测的测试样本，并利用这些样本的反馈来改进已部署的模型。我们通过将Prom应用于5种代表性代码分析和优化任务中的13个机器学习模型，展示了Prom的效果。广泛的评估表明，Prom能够成功识别出高达96%（最多100%）的误预测。通过对Prom识别的样本进行最多5%的增量重新标记，Prom能够帮助已部署的模型恢复到与其训练阶段相当的性能水平。 

---
# Predicate Invention from Pixels via Pretrained Vision-Language Models 

**Title (ZH)**: 通过预训练的跨模态模型从像素中发明谓词 

**Authors**: Ashay Athalye, Nishanth Kumar, Tom Silver, Yichao Liang, Tomás Lozano-Pérez, Leslie Pack Kaelbling  

**Link**: [PDF](https://arxiv.org/pdf/2501.00296)  

**Abstract**: Our aim is to learn to solve long-horizon decision-making problems in highly-variable, combinatorially-complex robotics domains given raw sensor input in the form of images. Previous work has shown that one way to achieve this aim is to learn a structured abstract transition model in the form of symbolic predicates and operators, and then plan within this model to solve novel tasks at test time. However, these learned models do not ground directly into pixels from just a handful of demonstrations. In this work, we propose to invent predicates that operate directly over input images by leveraging the capabilities of pretrained vision-language models (VLMs). Our key idea is that, given a set of demonstrations, a VLM can be used to propose a set of predicates that are potentially relevant for decision-making and then to determine the truth values of these predicates in both the given demonstrations and new image inputs. We build upon an existing framework for predicate invention, which generates feature-based predicates operating on object-centric states, to also generate visual predicates that operate on images. Experimentally, we show that our approach -- pix2pred -- is able to invent semantically meaningful predicates that enable generalization to novel, complex, and long-horizon tasks across two simulated robotic environments. 

**Abstract (ZH)**: 我们的目标是在高度变化和组合复杂性的机器人领域中，利用原始传感器输入（以图像形式），学习解决长期决策问题。之前的研究表明，实现这一目标的一种方法是学习一种结构化抽象转移模型，该模型以符号谓词和操作符的形式存在，然后在模型中进行计划，以在测试时解决新颖的任务。然而，这些学习到的模型不能直接从少数演示中推断到像素级。在本研究中，我们提出了一种方法，通过利用预训练的视觉语言模型（VLM）的能力，直接在输入图像上定义谓词。我们的核心思想是，在给定一组演示的情况下，可以使用VLM提出一组潜在相关的谓词，并在这些演示和新的图像输入上确定这些谓词的真实性值。我们在此前的谓词发明框架基础上进行了扩展，该框架可以生成基于特征的谓词以操作面向对象的状态，同时也能生成操作图像的视觉谓词。实验结果显示，我们的方法——pix2pred——能够发明具有语义意义的谓词，从而在两个模拟的机器人环境中实现对新颖、复杂和长期决策任务的泛化。 

---
# Dual Diffusion for Unified Image Generation and Understanding 

**Title (ZH)**: 统一图像生成与理解的双重扩散方法 

**Authors**: Zijie Li, Henry Li, Yichun Shi, Amir Barati Farimani, Yuval Kluger, Linjie Yang, Peng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00289)  

**Abstract**: Diffusion models have gained tremendous success in text-to-image generation, yet still lag behind with visual understanding tasks, an area dominated by autoregressive vision-language models. We propose a large-scale and fully end-to-end diffusion model for multi-modal understanding and generation that significantly improves on existing diffusion-based multimodal models, and is the first of its kind to support the full suite of vision-language modeling capabilities. Inspired by the multimodal diffusion transformer (MM-DiT) and recent advances in discrete diffusion language modeling, we leverage a cross-modal maximum likelihood estimation framework that simultaneously trains the conditional likelihoods of both images and text jointly under a single loss function, which is back-propagated through both branches of the diffusion transformer. The resulting model is highly flexible and capable of a wide range of tasks including image generation, captioning, and visual question answering. Our model attained competitive performance compared to recent unified image understanding and generation models, demonstrating the potential of multimodal diffusion modeling as a promising alternative to autoregressive next-token prediction models. 

**Abstract (ZH)**: 扩散模型在文本生成图片方面取得了巨大的成功，但在视觉理解任务上仍落后于以自回归视觉语言模型为主导的领域。我们提出了一种大规模的端到端多模态扩散模型，该模型在现有的基于扩散的多模态模型上显著改进，并且是首个支持全面视觉语言建模能力的模型。受多模态扩散变换器（MM-DiT）和离散扩散语言建模近期进展的启发，我们利用一种跨模态的最大似然估计框架，在单一损失函数下同时训练图像和文本的条件似然性，该损失函数通过扩散变换器的两个分支进行反向传播。最终，该模型具有高度的灵活性，能够处理包括图像生成、字幕生成和视觉问答等广泛的任务。与近期统一的图像理解和生成模型相比，我们的模型取得了竞争力的表现，证明了多模态扩散建模作为自回归下一个token预测模型替代方案的潜力。 

---
# Efficient Human-in-the-Loop Active Learning: A Novel Framework for Data Labeling in AI Systems 

**Title (ZH)**: 高效的人机交互主动学习：AI系统数据标注的新型框架 

**Authors**: Yiran Huang, Jian-Feng Yang, Haoda Fu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00277)  

**Abstract**: Modern AI algorithms require labeled data. In real world, majority of data are unlabeled. Labeling the data are costly. this is particularly true for some areas requiring special skills, such as reading radiology images by physicians. To most efficiently use expert's time for the data labeling, one promising approach is human-in-the-loop active learning algorithm. In this work, we propose a novel active learning framework with significant potential for application in modern AI systems. Unlike the traditional active learning methods, which only focus on determining which data point should be labeled, our framework also introduces an innovative perspective on incorporating different query scheme. We propose a model to integrate the information from different types of queries. Based on this model, our active learning frame can automatically determine how the next question is queried. We further developed a data driven exploration and exploitation framework into our active learning method. This method can be embedded in numerous active learning algorithms. Through simulations on five real-world datasets, including a highly complex real image task, our proposed active learning framework exhibits higher accuracy and lower loss compared to other methods. 

**Abstract (ZH)**: 现代AI算法需要标注数据。在现实世界中，大部分数据都是未标注的。对数据进行标注的成本很高。特别是在需要特殊技能的领域，如医生阅读放射影像，标注数据的成本更为突出。为了最有效地利用专家的时间进行数据标注，一种有前景的方法是人工参与的主动学习算法。在本项工作中，我们提出了一种具有广泛应用潜力的新型主动学习框架。与传统的主动学习方法仅关注应选择哪些数据点进行标注不同，我们的框架还引入了合并不同查询方案的新颖视角。我们提出了一种模型，用以整合不同类型查询的信息。基于此模型，我们的主动学习框架可以自动确定下一个问题应该如何提出。我们进一步将基于数据驱动的探索与利用框架融入到了我们的主动学习方法中。该方法可以嵌入到多种主动学习算法中。通过在包括一个高度复杂的实际图像任务在内的五个真实世界数据集上进行模拟，我们提出的主动学习框架在准确性和降低损失方面均优于其他方法。 

---
# Enhancing Wireless Sensor Network Security through Integration with the ServiceNow Cloud Platform 

**Title (ZH)**: 通过集成到ServiceNow云平台来增强无线传感器网络安全性 

**Authors**: Syed Atif Ali, Salwa Din  

**Link**: [PDF](https://arxiv.org/pdf/2501.00264)  

**Abstract**: Wireless Sensor Networks (WSNs) continue to experience rapid developments and integration into modern-day applications. Overall, WSNs collect and process relevant data through sensors or nodes and communicate with different networks for superior information management. Nevertheless, a primary concern relative to WSNs is security. Considering the high constraints on throughput, battery, processing power, and memory, typical security procedures present limitations for application in WSNs. This research focuses on the integration of WSNs with the cloud platform, specifically to address these security risks. The cloud platform also adopts a security-driven approach and has attracted many applications across various sectors globally. This research specifically explores how cloud computing could be exploited to impede Denial of Service attacks from endangering WSNs. WSNs are now deployed in various low-powered applications, including disaster management, homeland security, battlefield surveillance, agriculture, and the healthcare industry. WSNs are distinguished from traditional networks by the numerous wireless connected sensors being deployed to conduct an assigned task. In testing scenarios, the size of WSNs ranges from a few to several thousand. The overarching requirements of WSNs include rapid processing of collected data, low-cost installation and maintenance, and low latency in network operations. Given that a substantial amount of WSN applications are used in high-risk and volatile environments, they must effectively address security concerns. This includes the secure movement, storage, and communication of data through networks, an environment in which WSNs are notably vulnerable. The limitations of WSNs have meant that they are predominantly used in unsecured applications despite positive advancements. This study explores methods for integrating the WSN with the cloud. 

**Abstract (ZH)**: 无线传感器网络（WSNs）一直经历着快速的发展，并被广泛应用于现代应用中。总体而言，WSNs通过传感器或节点收集和处理相关数据，并与其他网络通信以实现更优秀的信息管理。然而，与WSNs相关的首要关注点是安全性。考虑到吞吐量、电池、处理能力和存储等方面的高限制，典型的安全程序在应用于WSNs时会遇到限制。本研究集中在将WSNs与云计算平台集成，以解决这些安全风险。云计算平台采用以安全为主导的方法，并在全球各个行业中吸引了许多应用。本研究特别探讨了云计算如何被利用以防止分布式拒绝服务（DoS）攻击威胁WSNs。WSNs现在被部署在各种低功耗应用中，包括灾害管理、国土安全、战场监控、农业和医疗保健行业。WSNs因其部署了大量无线连接的传感器以执行指定任务而与传统网络区分开来。在测试场景中，WSNs的规模可以从几个节点到几千个不等。WSNs的基本要求包括快速处理收集的数据、低成本的安装和维护、以及较低的网络延迟。鉴于WSNs中有相当一部分应用在高风险和多变的环境中使用，它们必须有效地解决安全问题。这包括保障数据在网络中的安全传输、存储和通信，而WSNs在这方面尤为脆弱。WSNs的局限性意味着，尽管取得了积极的发展，它们仍主要用于非安全应用中。本研究探讨了将WSNs与云计算集成的方法。 

---
# Collaborative Approaches to Enhancing Smart Vehicle Cybersecurity by AI-Driven Threat Detection 

**Title (ZH)**: 基于AI驱动威胁检测的协作增强智能车辆网络安全方法 

**Authors**: Syed Atif Ali, Salwa Din  

**Link**: [PDF](https://arxiv.org/pdf/2501.00261)  

**Abstract**: The introduction sets the stage for exploring collaborative approaches to bolstering smart vehicle cybersecurity through AI-driven threat detection. As the automotive industry increasingly adopts connected and automated vehicles (CAVs), the need for robust cybersecurity measures becomes paramount. With the emergence of new vulnerabilities and security requirements, the integration of advanced technologies such as 5G networks, blockchain, and quantum computing presents promising avenues for enhancing CAV cybersecurity . Additionally, the roadmap for cybersecurity in autonomous vehicles emphasizes the importance of efficient intrusion detection systems and AI-based techniques, along with the integration of secure hardware, software stacks, and advanced threat intelligence to address cybersecurity challenges in future autonomous vehicles. 

**Abstract (ZH)**: 引言部分为探讨通过人工智能驱动的威胁检测来增强智能车辆网络安全的合作方法奠定了基础。随着 automotive 行业越来越多地采用连接式和自动化车辆（CAVs），对 robust 网络安全措施的需求变得至关重要。随着新漏洞和安全要求的出现，5G 网络、区块链和量子计算等先进技术的集成为增强 CAV 网络安全提供了有希望的途径。此外，自主车辆的网络安全路线图强调了高效入侵检测系统和基于 AI 的技术的重要性，以及安全硬件、软件栈和先进威胁情报的集成，以应对未来自主车辆的网络安全挑战。 

---
# Exploring Variability in Fine-Tuned Models for Text Classification with DistilBERT 

**Title (ZH)**: 探索基于DistilBERT的细调模型在文本分类中的变异性 

**Authors**: Giuliano Lorenzoni, Ivens Portugal, Paulo Alencar, Donald Cowan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00241)  

**Abstract**: This study evaluates fine-tuning strategies for text classification using the DistilBERT model, specifically the distilbert-base-uncased-finetuned-sst-2-english variant. Through structured experiments, we examine the influence of hyperparameters such as learning rate, batch size, and epochs on accuracy, F1-score, and loss. Polynomial regression analyses capture foundational and incremental impacts of these hyperparameters, focusing on fine-tuning adjustments relative to a baseline model.
Results reveal variability in metrics due to hyperparameter configurations, showing trade-offs among performance metrics. For example, a higher learning rate reduces loss in relative analysis (p=0.027) but challenges accuracy improvements. Meanwhile, batch size significantly impacts accuracy and F1-score in absolute regression (p=0.028 and p=0.005) but has limited influence on loss optimization (p=0.170). The interaction between epochs and batch size maximizes F1-score (p=0.001), underscoring the importance of hyperparameter interplay.
These findings highlight the need for fine-tuning strategies addressing non-linear hyperparameter interactions to balance performance across metrics. Such variability and metric trade-offs are relevant for tasks beyond text classification, including NLP and computer vision. This analysis informs fine-tuning strategies for large language models and promotes adaptive designs for broader model applicability. 

**Abstract (ZH)**: 本研究评估了使用DistilBERT模型进行文本分类的微调策略，特别是针对distilbert-base-uncased-finetuned-sst-2-english变体的微调策略。通过有组织的实验，我们考察了学习率、批量大小和迭代次数等超参数对准确率、F1分数和损失的影响。多项式回归分析捕捉到这些超参数的基础性和累积性影响，重点关注相对于基础模型的微调调整。
结果表明，由于超参数配置的变化导致了指标的波动性，显示了性能指标之间的权衡。例如，在相对分析中，较高的学习率降低了损失（p=0.027），但挑战了准确率的改进。同时，批量大小显著影响绝对回归中的准确率和F1分数（p=0.028 和 p=0.005），但对损失优化的影响有限（p=0.170）。而迭代次数和批量大小之间的交互作用最大化了F1分数（p=0.001），强调了超参数交互作用的重要性。
这些发现强调了需要针对非线性超参数交互作用制定微调策略，以在指标间实现性能平衡。这种变化和指标权衡不仅适用于文本分类任务，还适用于NLP和计算机视觉等任务。此分析为大型语言模型的微调策略提供了指导，并促进了更广泛的模型应用的适应性设计。 

---
# Federated Deep Subspace Clustering 

**Title (ZH)**: 联邦深度子空间聚类 

**Authors**: Yupei Zhang, Ruojia Feng, Yifei Wang, Xuequn Shang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00230)  

**Abstract**: This paper introduces FDSC, a private-protected subspace clustering (SC) approach with federated learning (FC) schema. In each client, there is a deep subspace clustering network accounting for grouping the isolated data, composed of a encode network, a self-expressive layer, and a decode network. FDSC is achieved by uploading the encode network to communicate with other clients in the server. Besides, FDSC is also enhanced by preserving the local neighborhood relationship in each client. With the effects of federated learning and locality preservation, the learned data features from the encoder are boosted so as to enhance the self-expressiveness learning and result in better clustering performance. Experiments test FDSC on public datasets and compare with other clustering methods, demonstrating the effectiveness of FDSC. 

**Abstract (ZH)**: 本文介绍了一种基于联邦学习（Federated Learning, FL）方案的私保护子空间聚类（Private-Protected Subspace Clustering, FDSC）方法。在每个客户端中，存在一个深度子空间聚类网络，用于将孤立数据分组，该网络由编码网络、自我表达层和解码网络组成。FDSC 通过将编码网络上传到服务器，使其能够在客户端之间进行通信而实现。此外，FDSC 还通过在每个客户端中保留局部邻域关系来增强该方法。通过联邦学习和局部关系保留的效果，编码器学习到的数据特征得到了增强，从而提高了自我表达学习的效果，并提升了聚类性能。实验在公共数据集上测试了 FDSC，并与其他聚类方法进行了比较，证明了 FDSC 的有效性。 

---
# Extracting effective solutions hidden in large language models via generated comprehensive specialists: case studies in developing electronic devices 

**Title (ZH)**: 通过生成综合专家提取隐藏在大规模语言模型中的有效解决方案：电子产品开发中的案例研究 

**Authors**: Hikari Tomita, Nobuhiro Nakamura, Shoichi Ishida, Toshio Kamiya, Kei Terayama  

**Link**: [PDF](https://arxiv.org/pdf/2501.00224)  

**Abstract**: Recently, many studies have increasingly explored the use of large language models (LLMs) to generate research ideas and scientific hypotheses. However, real-world research and development often require solving complex, interdisciplinary challenges where solutions may not be readily found through existing knowledge related to the problem. Therefore, it is desirable to leverage the vast, comprehensive knowledge of LLMs to generate effective, breakthrough solutions by integrating various perspectives from other disciplines. Here, we propose SELLM (Solution Enumeration via comprehensive List and LLM), a framework leveraging LLMs and structured guidance using MECE (Mutually Exclusive, Collectively Exhaustive) principles, such as International Patent Classification (IPC) and the periodic table of elements. SELLM systematically constructs comprehensive expert agents from the list to generate cross-disciplinary and effective solutions. To evaluate SELLM's practicality, we applied it to two challenges: improving light extraction in organic light-emitting diode (OLED) lighting and developing electrodes for next-generation memory materials. The results demonstrate that SELLM significantly facilitates the generation of effective solutions compared to cases without specific customization or effort, showcasing the potential of SELLM to enable LLMs to generate effective solutions even for challenging problems. 

**Abstract (ZH)**: 近年来，许多研究越来越多地探讨了使用大型语言模型（LLMs）来生成研究想法和科学假设。然而，现实世界的研究与发展往往需要解决复杂的、跨学科的挑战，而这些问题的解决方案可能无法通过现有与问题相关的知识轻易找到。因此，有必要充分利用LLMs广泛而综合的知识，通过整合其他学科的各种视角来生成有效且突破性的解决方案。在此，我们提出了SELLM（基于MECE原则的综合列表和LLM解决方案列举框架），该框架利用LLMs和MECE（互斥且详尽）原则进行结构化的指导，如国际专利分类（IPC）和元素周期表。SELLM系统地从列表中构建综合专家代理，以生成跨学科且有效的解决方案。为了评估SELLM的实际应用性，我们将其应用于两个挑战：改善有机发光二极管（OLED）照明中的光提取和开发下一代存储材料的电极。结果表明，与没有特定定制或努力的情况相比，SELLM显著促进了有效解决方案的生成，展示了SELLM能够使LLMs为棘手问题生成有效解决方案的潜力。 

---
# The Potential of LLMs in Automating Software Testing: From Generation to Reporting 

**Title (ZH)**: 大型语言模型在自动化软件测试中的潜力：从生成到报告 

**Authors**: Betim Sherifi, Khaled Slhoub, Fitzroy Nembhard  

**Link**: [PDF](https://arxiv.org/pdf/2501.00217)  

**Abstract**: Having a high quality software is essential in software engineering, which requires robust validation and verification processes during testing activities. Manual testing, while effective, can be time consuming and costly, leading to an increased demand for automated methods. Recent advancements in Large Language Models (LLMs) have significantly influenced software engineering, particularly in areas like requirements analysis, test automation, and debugging. This paper explores an agent-oriented approach to automated software testing, using LLMs to reduce human intervention and enhance testing efficiency. The proposed framework integrates LLMs to generate unit tests, visualize call graphs, and automate test execution and reporting. Evaluations across multiple applications in Python and Java demonstrate the system's high test coverage and efficient operation. This research underscores the potential of LLM-powered agents to streamline software testing workflows while addressing challenges in scalability and accuracy. 

**Abstract (ZH)**: 高质量的软件在软件工程中至关重要，这需要在测试活动中采用强大的验证和验证流程。虽然人工测试效果显著，但其耗时和成本较高，因此对自动化方法的需求也在增加。近年来，大型语言模型（LLMs）的进步对软件工程领域产生了重大影响，特别是在需求分析、测试自动化和调试等方面。本文探索了一种面向代理的自动软件测试方法，利用LLMs减少人工干预并提高测试效率。所提出的框架结合使用LLMs生成单元测试、可视化调用图并自动化测试执行和报告。跨多个Python和Java应用程序的评估表明，该系统的测试覆盖率高且运行高效。这项研究强调了LLM驱动代理在简化软件测试工作流方面的作用，同时也应对扩展性和准确性方面的挑战。 

---
# Debunking the CUDA Myth Towards GPU-based AI Systems 

**Title (ZH)**: 面向基于GPU的AI系统的CUDA Myth破除研究 

**Authors**: Yunjae Lee, Juntaek Lim, Jehyeon Bang, Eunyeong Cho, Huijong Jeong, Taesu Kim, Hyungjun Kim, Joonhyung Lee, Jinseop Im, Ranggi Hwang, Se Jung Kwon, Dongsoo Lee, Minsoo Rhu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00210)  

**Abstract**: With the rise of AI, NVIDIA GPUs have become the de facto standard for AI system design. This paper presents a comprehensive evaluation of Intel Gaudi NPUs as an alternative to NVIDIA GPUs for AI model serving. First, we create a suite of microbenchmarks to compare Intel Gaudi-2 with NVIDIA A100, showing that Gaudi-2 achieves competitive performance not only in primitive AI compute, memory, and communication operations but also in executing several important AI workloads end-to-end. We then assess Gaudi NPU's programmability by discussing several software-level optimization strategies to employ for implementing critical FBGEMM operators and vLLM, evaluating their efficiency against GPU-optimized counterparts. Results indicate that Gaudi-2 achieves energy efficiency comparable to A100, though there are notable areas for improvement in terms of software maturity. Overall, we conclude that, with effective integration into high-level AI frameworks, Gaudi NPUs could challenge NVIDIA GPU's dominance in the AI server market, though further improvements are necessary to fully compete with NVIDIA's robust software ecosystem. 

**Abstract (ZH)**: 随着人工智能（AI）的兴起，英伟达（NVIDIA）GPU 已成为 AI 系统设计的事实标准。本文旨在全面评估英特尔（Intel）Gaudi 神经处理器（NPUs）作为 NVIDIA GPU 的替代方案用于 AI 模型服务。首先，我们构建了一套微型基准测试，将 Gaudi-2 与 NVIDIA A100 进行对比，结果显示 Gaudi-2 不仅在基本的 AI 计算、内存操作及通信操作中表现出竞争力，还在端到端执行多个重要的 AI 工作负载方面表现出色。随后，我们通过讨论几种软件层面的优化策略来评估 Gaudi NPU 的可编程性，这些策略包括用于实现关键 FBGEMM 操作和 vLLM 的优化方法，并将这些方法与 GPU 优化版本进行效率对比。结果表明，Gaudi-2 在能效方面与 A100 相当，但存在一些软件成熟度方面的明显提升空间。总体而言，我们得出结论，在有效集成到高级 AI 框架中后，Gaudi NPUs 颠覆 NVIDIA GPU 在 AI 服务器市场主导地位的能力是有可能的，尽管仍需要进一步改进，以完全与 NVIDIA 强大的软件生态系统竞争。 

---
# An Empirical Evaluation of Large Language Models on Consumer Health Questions 

**Title (ZH)**: 大型语言模型在消费者健康问题上的实证评估 

**Authors**: Moaiz Abrar, Yusuf Sermet, Ibrahim Demir  

**Link**: [PDF](https://arxiv.org/pdf/2501.00208)  

**Abstract**: This study evaluates the performance of several Large Language Models (LLMs) on MedRedQA, a dataset of consumer-based medical questions and answers by verified experts extracted from the AskDocs subreddit. While LLMs have shown proficiency in clinical question answering (QA) benchmarks, their effectiveness on real-world, consumer-based, medical questions remains less understood. MedRedQA presents unique challenges, such as informal language and the need for precise responses suited to non-specialist queries. To assess model performance, responses were generated using five LLMs: GPT-4o mini, Llama 3.1: 70B, Mistral-123B, Mistral-7B, and Gemini-Flash. A cross-evaluation method was used, where each model evaluated its responses as well as those of others to minimize bias. The results indicated that GPT-4o mini achieved the highest alignment with expert responses according to four out of the five models' judges, while Mistral-7B scored lowest according to three out of five models' judges. This study highlights the potential and limitations of current LLMs for consumer health medical question answering, indicating avenues for further development. 

**Abstract (ZH)**: 本研究评估了多种大型语言模型（LLM）在MedRedQA数据集上的表现，该数据集包含从AskDocs子版块提取的由经过验证的专家解答的消费导向型医学问题和答案。尽管LLM已经在临床问答基准测试中展示了其能力，但它们在真实世界、消费导向型医学问题上的效果尚不完全清楚。MedRedQA数据集提出了独特的挑战，包括非正式的语言和需要针对非专科查询给出精确的回答。为了评估模型性能，使用了五种LLM生成了响应：GPT-4o mini、Llama 3.1: 70B、Mistral-123B、Mistral-7B 和 Gemini-Flash。采用了一种交叉评估方法，即每种模型不仅评估自己的响应，还评估其他模型的响应，以减少偏差。结果显示，GPT-4o mini 根据四款模型的评判员得到了与专家响应最高的一致性评价，而Mistral-7B则根据三款模型的评判员得到了最低的评价。本研究突显了当前LLM在消费健康医学问答方面的潜力和局限性，并指出了进一步发展的途径。 

---
# GPT-4 on Clinic Depression Assessment: An LLM-Based Pilot Study 

**Title (ZH)**: 基于语言模型的初步研究：GPT-4在临床抑郁评估中的应用 

**Authors**: Giuliano Lorenzoni, Pedro Elkind Velmovitsky, Paulo Alencar, Donald Cowan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00199)  

**Abstract**: Depression has impacted millions of people worldwide and has become one of the most prevalent mental disorders. Early mental disorder detection can lead to cost savings for public health agencies and avoid the onset of other major comorbidities. Additionally, the shortage of specialized personnel is a critical issue because clinical depression diagnosis is highly dependent on expert professionals and is time consuming.
In this study, we explore the use of GPT-4 for clinical depression assessment based on transcript analysis. We examine the model's ability to classify patient interviews into binary categories: depressed and not depressed. A comparative analysis is conducted considering prompt complexity (e.g., using both simple and complex prompts) as well as varied temperature settings to assess the impact of prompt complexity and randomness on the model's performance.
Results indicate that GPT-4 exhibits considerable variability in accuracy and F1-Score across configurations, with optimal performance observed at lower temperature values (0.0-0.2) for complex prompts. However, beyond a certain threshold (temperature >= 0.3), the relationship between randomness and performance becomes unpredictable, diminishing the gains from prompt complexity.
These findings suggest that, while GPT-4 shows promise for clinical assessment, the configuration of the prompts and model parameters requires careful calibration to ensure consistent results. This preliminary study contributes to understanding the dynamics between prompt engineering and large language models, offering insights for future development of AI-powered tools in clinical settings. 

**Abstract (ZH)**: 抑郁症影响了全世界数百万人口，并已成为最常见的精神障碍之一。早期的精神障碍检测可以为公共卫生机构节省成本，并避免其他严重共病的出现。此外，专业人员的短缺也是一个关键问题，因为临床抑郁诊断高度依赖于专业人员，并且耗时较长。

在本研究中，我们探讨了使用GPT-4进行临床抑郁评估的方法，基于对话转录分析。我们考察了模型将患者访谈分类为两类（抑郁和非抑郁）的能力。我们进行了比较分析，考虑了提示复杂性（例如，使用简单和复杂的提示）以及不同的温度设置，以评估提示复杂性与随机性对模型性能的影响。

结果表明，在不同配置下，GPT-4在准确性与F1分数方面表现出较大的波动性，对于复杂提示，最优性能出现在较低的温度值（0.0-0.2）。然而，当温度超过一定阈值（温度>=0.3）时，随机性和性能之间的关系变得不可预测，提示复杂性带来的收益开始减弱。

这些发现表明，尽管GPT-4在临床评估方面显示出潜力，但提示和模型参数的配置需要仔细调整以确保结果的一致性。本初步研究为理解提提示工程与大规模语言模型之间的动态关系提供了见解，为未来临床环境下AI驱动工具的发展提供了参考。

（注：GPT-4作为最新的模型，原文可能使用GPT-4或其他相关模型名称，这里根据上下文翻译为GPT-4。） 

---
# Towards Unraveling and Improving Generalization in World Models 

**Title (ZH)**: 探索和完善世界模型中的泛化能力 

**Authors**: Qiaoyi Fang, Weiyu Du, Hang Wang, Junshan Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00195)  

**Abstract**: World models have recently emerged as a promising approach to reinforcement learning (RL), achieving state-of-the-art performance across a wide range of visual control tasks. This work aims to obtain a deep understanding of the robustness and generalization capabilities of world models. Thus motivated, we develop a stochastic differential equation formulation by treating the world model learning as a stochastic dynamical system, and characterize the impact of latent representation errors on robustness and generalization, for both cases with zero-drift representation errors and with non-zero-drift representation errors. Our somewhat surprising findings, based on both theoretic and experimental studies, reveal that for the case with zero drift, modest latent representation errors can in fact function as implicit regularization and hence result in improved robustness. We further propose a Jacobian regularization scheme to mitigate the compounding error propagation effects of non-zero drift, thereby enhancing training stability and robustness. Our experimental studies corroborate that this regularization approach not only stabilizes training but also accelerates convergence and improves accuracy of long-horizon prediction. 

**Abstract (ZH)**: 世界模型近年来被证明是强化学习（RL）的一种有前途的方法，已在各种视觉控制任务中取得了性能前沿的表现。本项工作旨在深入理解世界模型的鲁棒性和泛化能力。为此，我们通过将世界模型学习视为一个随机动力系统，构建了一个随机微分方程的形式，刻画了潜在表示错误对鲁棒性和泛化能力的影响，适用于零漂移表示错误和非零漂移表示错误两种情况。基于理论和实验研究，我们发现在零漂移情况下，适度的潜在表示错误实际上可以起到隐式正则化的作用，从而提高鲁棒性。进一步地，我们提出了一种雅克比正则化方案来减轻非零漂移引起的累积误差传播效应，从而增强训练稳定性并提高鲁棒性。实验研究表明，这种正则化方法不仅能够稳定训练，还能加速收敛，提高长时预测的准确性。 

---
# SepsisCalc: Integrating Clinical Calculators into Early Sepsis Prediction via Dynamic Temporal Graph Construction 

**Title (ZH)**: SepsisCalc：通过动态时态图构建将临床计算器集成到早期败血症预测中 

**Authors**: Changchang Yin, Shihan Fu, Bingsheng Yao, Thai-Hoang Pham, Weidan Cao, Dakuo Wang, Jeffrey Caterino, Ping Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00190)  

**Abstract**: Sepsis is an organ dysfunction caused by a deregulated immune response to an infection. Early sepsis prediction and identification allow for timely intervention, leading to improved clinical outcomes. Clinical calculators (e.g., the six-organ dysfunction assessment of SOFA) play a vital role in sepsis identification within clinicians' workflow, providing evidence-based risk assessments essential for sepsis diagnosis. However, artificial intelligence (AI) sepsis prediction models typically generate a single sepsis risk score without incorporating clinical calculators for assessing organ dysfunctions, making the models less convincing and transparent to clinicians. To bridge the gap, we propose to mimic clinicians' workflow with a novel framework SepsisCalc to integrate clinical calculators into the predictive model, yielding a clinically transparent and precise model for utilization in clinical settings. Practically, clinical calculators usually combine information from multiple component variables in Electronic Health Records (EHR), and might not be applicable when the variables are (partially) missing. We mitigate this issue by representing EHRs as temporal graphs and integrating a learning module to dynamically add the accurately estimated calculator to the graphs. Experimental results on real-world datasets show that the proposed model outperforms state-of-the-art methods on sepsis prediction tasks. Moreover, we developed a system to identify organ dysfunctions and potential sepsis risks, providing a human-AI interaction tool for deployment, which can help clinicians understand the prediction outputs and prepare timely interventions for the corresponding dysfunctions, paving the way for actionable clinical decision-making support for early intervention. 

**Abstract (ZH)**: 脓毒症是由感染引发的免疫反应失调导致的器官功能障碍。早期脓毒症的预测和识别可以及时介入，从而改善临床结果。临床计算器（如SOFA的六器官功能障碍评估）在 clinician 的工作流程中发挥着重要作用，提供了基于证据的风险评估，对于脓毒症的诊断至关重要。然而，人工智能（AI）脓毒症预测模型通常生成单一的脓毒症风险评分，而不结合临床计算器评估器官功能障碍，使得这些模型对clinician来说不够令人信服且不透明。为此，我们提出了一种名为SepsisCalc的新框架，旨在将临床计算器整合到预测模型中，从而构建一个临床透明且精准的模型，适用于临床使用。实际上，临床计算器通常会综合电子健康记录（EHR）中多个成分变量的信息，但在这些变量部分缺失的情况下可能不适用。我们通过将EHR表示为时间图并引入一个学习模块来动态补充准确估计的计算器，解决了这一问题。在实际数据集上的实验结果显示，所提出的方法比现有最佳方法在脓毒症预测任务上表现更优。此外，我们还开发了一个系统，用于识别器官功能障碍和潜在的脓毒症风险，并提供了一种人机交互工具以支持部署，有助于clinician理解预测结果并为相应的功能障碍准备及时的干预措施，为早期干预提供了可操作的临床决策支持。 

---
# The Text Classification Pipeline: Starting Shallow going Deeper 

**Title (ZH)**: 文本分类流水线：从浅层走向深层 

**Authors**: Marco Siino, Ilenia Tinnirello, Marco La Cascia  

**Link**: [PDF](https://arxiv.org/pdf/2501.00174)  

**Abstract**: Text Classification (TC) stands as a cornerstone within the realm of Natural Language Processing (NLP), particularly when viewed through the lens of computer science and engineering. The past decade has seen deep learning revolutionize TC, propelling advancements in text retrieval, categorization, information extraction, and summarization. The scholarly literature is rich with datasets, models, and evaluation criteria, with English being the predominant language of focus, despite studies involving Arabic, Chinese, Hindi, and others. The efficacy of TC models relies heavily on their ability to capture intricate textual relationships and nonlinear correlations, necessitating a comprehensive examination of the entire TC pipeline.
This monograph provides an in-depth exploration of the TC pipeline, with a particular emphasis on evaluating the impact of each component on the overall performance of TC models. The pipeline includes state-of-the-art datasets, text preprocessing techniques, text representation methods, classification models, evaluation metrics, current results and future trends. Each chapter meticulously examines these stages, presenting technical innovations and significant recent findings. The work critically assesses various classification strategies, offering comparative analyses, examples, case studies, and experimental evaluations. These contributions extend beyond a typical survey, providing a detailed and insightful exploration of TC. 

**Abstract (ZH)**: 文本分类（Text Classification, TC）作为自然语言处理（Natural Language Processing, NLP）领域的基石，在计算机科学和工程领域具有重要意义。过去的十年见证了深度学习对TC的革命性影响，推动了文本检索、分类、信息提取和摘要等领域的进步。学术文献中充斥着各种数据集、模型和评估标准，尽管主要关注英语，但也有涉及阿拉伯语、汉语、印地语等其他语言的研究。TC模型的有效性很大程度上依赖于它们捕获复杂文本关系和非线性相关性的能力，因此需要对整个TC流程进行全面评估。

本专著深入探讨了TC流程，重点关注每个组件对TC模型整体性能的影响。流程包括最先进的数据集、文本预处理技术、文本表示方法、分类模型、评估指标、当前结果和未来趋势。每一章都详细地分析了这些阶段，展示了技术创新和最近的重要发现。本书批判性地评估了各种分类策略，提供了比较分析、案例研究和实验评估。这些贡献超越了一般性的综述，提供了对TC的详细且深入的探索。 

---
# Federated Learning with Workload Reduction through Partial Training of Client Models and Entropy-Based Data Selection 

**Title (ZH)**: 通过客户端模型的部分训练和基于熵的数据选择实现工作量减少的联邦学习 

**Authors**: Hongrui Shi, Valentin Radu, Po Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00170)  

**Abstract**: With the rapid expansion of edge devices, such as IoT devices, where crucial data needed for machine learning applications is generated, it becomes essential to promote their participation in privacy-preserving Federated Learning (FL) systems. The best way to achieve this desiderate is by reducing their training workload to match their constrained computational resources. While prior FL research has address the workload constrains by introducing lightweight models on the edge, limited attention has been given to optimizing on-device training efficiency through reducing the amount of data need during training. In this work, we propose FedFT-EDS, a novel approach that combines Fine-Tuning of partial client models with Entropy-based Data Selection to reduce training workloads on edge devices. By actively selecting the most informative local instances for learning, FedFT-EDS reduces training data significantly in FL and demonstrates that not all user data is equally beneficial for FL on all rounds. Our experiments on CIFAR-10 and CIFAR-100 show that FedFT-EDS uses only 50% user data while improving the global model performance compared to baseline methods, FedAvg and FedProx. Importantly, FedFT-EDS improves client learning efficiency by up to 3 times, using one third of training time on clients to achieve an equivalent performance to the baselines. This work highlights the importance of data selection in FL and presents a promising pathway to scalable and efficient Federate Learning. 

**Abstract (ZH)**: 伴随着边缘设备的迅速扩展，诸如物联网设备等，在这些设备上生成了大量用于机器学习应用的关键数据，促进它们在保护隐私的联邦学习（FL）系统中的参与变得至关重要。实现这一目标的最佳途径是减少它们的训练工作量，以匹配其有限的计算资源。尽管先前的联邦学习研究通过引入轻量级模型来缓解计算约束，但在通过减少训练所需的数据量来优化边缘设备上的训练效率方面，研究的关注度相对较低。在本文中，我们提出了一种名为FedFT-EDS的新颖方法，该方法结合了对部分客户端模型进行微调和基于熵的数据选择，以减少边缘设备上的训练工作量。通过积极选择最具信息性的本地实例来进行学习，FedFT-EDS在联邦学习中显著减少了训练数据量，并展示了并非所有用户的训练数据在所有轮次中都对联邦学习具有同等的益处。我们在CIFAR-10和CIFAR-100上的实验表明，与基准方法FedAvg和FedProx相比，FedFT-EDS仅使用50%的用户数据，就能提高全局模型的性能。重要的是，FedFT-EDS通过使客户端的学习效率提高多达3倍，仅使用三分之一的训练时间即可达到基准方法的同等性能。本文突显了在联邦学习中数据选择的重要性，并提出了一个具有前景的可扩展和高效的联邦学习路径。 

---
# DeepLL: Considering Linear Logic for the Analysis of Deep Learning Experiments 

**Title (ZH)**: DeepLL：考虑线性逻辑对深度学习实验的分析 

**Authors**: Nick Papoulias  

**Link**: [PDF](https://arxiv.org/pdf/2501.00169)  

**Abstract**: Deep Learning experiments have critical requirements regarding the careful handling of their datasets as well as the efficient and correct usage of APIs that interact with hardware accelerators. On the one hand, software mistakes during data handling can contaminate experiments and lead to incorrect results. On the other hand, poorly coded APIs that interact with the hardware can lead to sub-optimal usage and untrustworthy conclusions. In this work we investigate the use of Linear Logic for the analysis of Deep Learning experiments. We show that primitives and operators of Linear Logic can be used to express: (i) an abstract representation of the control flow of an experiment, (ii) a set of available experimental resources, such as API calls to the underlying data-structures and hardware as well as (iii) reasoning rules about the correct consumption of resources during experiments. Our proposed model is not only lightweight but also easy to comprehend having both a symbolic and a visual component. Finally, its artifacts are themselves proofs in Linear Logic that can be readily verified by off-the-shelf reasoners. 

**Abstract (ZH)**: 深度学习实验在数据集处理和与硬件加速器交互的API使用方面有严格的要求。一方面，在数据处理中的软件错误可能会污染实验并导致错误的结果。另一方面，编码不良的API可能导致资源利用不充分且不可靠的结论。在本工作中，我们探讨了使用线性逻辑来分析深度学习实验。我们展示了线性逻辑的原始形式和运算符可以用于表达：（i）实验控制流的抽象表示，（ii）可用的实验资源集，如底层数据结构和硬件的API调用，以及（iii）关于实验中正确消耗资源的推理规则。我们提出的方法不仅轻量级且易于理解，具有符号和视觉两个方面的成分。最后，该方法的产物本身是线性逻辑中的证明，可以被现成的推理器直接验证。 

---
# Class-based Subset Selection for Transfer Learning under Extreme Label Shift 

**Title (ZH)**: 基于类别的子集选择在极端标签偏移下的迁移学习 

**Authors**: Akul Goyal, Carl Edwards  

**Link**: [PDF](https://arxiv.org/pdf/2501.00162)  

**Abstract**: Existing work within transfer learning often follows a two-step process -- pre-training over a large-scale source domain and then finetuning over limited samples from the target domain. Yet, despite its popularity, this methodology has been shown to suffer in the presence of distributional shift -- specifically when the output spaces diverge. Previous work has focused on increasing model performance within this setting by identifying and classifying only the shared output classes between distributions. However, these methods are inherently limited as they ignore classes outside the shared class set, disregarding potential information relevant to the model transfer. This paper proposes a new process for few-shot transfer learning that selects and weighs classes from the source domain to optimize the transfer between domains. More concretely, we use Wasserstein distance to choose a set of source classes and their weights that minimize the distance between the source and target domain. To justify our proposed algorithm, we provide a generalization analysis of the performance of the learned classifier over the target domain and show that our method corresponds to a bound minimization algorithm. We empirically demonstrate the effectiveness of our approach (WaSS) by experimenting on several different datasets and presenting superior performance within various label shift settings, including the extreme case where the label spaces are disjoint. 

**Abstract (ZH)**: 现有的迁移学习研究通常遵循两步过程——在大规模源领域进行预训练，然后在目标领域的有限样本上进行微调。尽管这种方法很受欢迎，但在分布变化存在的情况下，该方法已被证明会受到影响，尤其是在输出空间产生差异时。以往的研究主要集中在通过识别和分类各分布之间的共享输出类别来提升模型性能上。然而，这些方法本身存在局限性，因为它们忽略了共享类集中之外的类别，从而忽视了可能对模型迁移有帮助的相关信息。本文提出了一种新的少量样本迁移学习过程，从源领域中选择并加权其类，以优化不同领域之间的迁移。具体而言，我们使用Wasserstein距离来选择能够最小化源领域与目标领域之间距离的源类及其权重。为了证明我们提出的算法的有效性，我们对在目标领域中学习到的分类器的泛化性能进行了分析，并且证明了我们的方法对应于一个边界最小化算法。我们通过在多种不同数据集上进行实验并展示了在各种标签变化设置中（包括标签空间完全不重合的极端情况）的优越性能，来实证验证了我们方法的效果（WaSS）。 

---
# Temporal reasoning for timeline summarisation in social media 

**Title (ZH)**: 社交媒体中的时间线总结中的时间推理 

**Authors**: Jiayu Song, Mahmud Akhter, Dana Atzil Slonim, Maria Liakata  

**Link**: [PDF](https://arxiv.org/pdf/2501.00152)  

**Abstract**: This paper explores whether enhancing temporal reasoning capabilities in Large Language Models (LLMs) can improve the quality of timeline summarization, the task of summarising long texts containing sequences of events, particularly social media threads . We introduce \textit{NarrativeReason}, a novel dataset focused on temporal relationships among sequential events within narratives, distinguishing it from existing temporal reasoning datasets that primarily address pair-wise event relationships. Our approach then combines temporal reasoning with timeline summarization through a knowledge distillation framework, where we first fine-tune a teacher model on temporal reasoning tasks and then distill this knowledge into a student model while simultaneously training it for the task of timeline summarization. Experimental results demonstrate that our model achieves superior performance on mental health-related timeline summarization tasks, which involve long social media threads with repetitions of events and a mix of emotions, highlighting the importance of leveraging temporal reasoning to improve timeline summarisation. 

**Abstract (ZH)**: 本文探讨了在大型语言模型（LLMs）中增强时间推理能力是否能够提高事件序列（尤其是社交媒体帖文）长文本总结的质量。我们引入了《NarrativeReason》，这是一个专注于叙事中序列事件之间时间关系的新型数据集，与现有主要关注事件对之间关系的时间推理数据集不同。我们的方法通过知识蒸馏框架将时间推理与时间线总结结合起来，首先对教师模型进行针对时间推理任务的微调，然后将这些知识传送给学生模型，同时训练学生模型进行时间线总结任务。实验结果表明，我们的模型在涉及情感混合和事件重复的心理健康相关的长社交媒体帖文总结任务中表现更佳，强调了利用时间推理提高时间线总结质量的重要性。 

---
# NiaAutoARM: Automated generation and evaluation of Association Rule Mining pipelines 

**Title (ZH)**: NiaAutoARM：关联规则挖掘管道的自动化生成与评估 

**Authors**: Uroš Mlakar, Iztok Fister Jr., Iztok Fister  

**Link**: [PDF](https://arxiv.org/pdf/2501.00138)  

**Abstract**: The Numerical Association Rule Mining paradigm that includes concurrent dealing with numerical and categorical attributes is beneficial for discovering associations from datasets consisting of both features. The process is not considered as easy since it incorporates several processing steps running sequentially that form an entire pipeline, e.g., preprocessing, algorithm selection, hyper-parameter optimization, and the definition of metrics evaluating the quality of the association rule. In this paper, we proposed a novel Automated Machine Learning method, NiaAutoARM, for constructing the full association rule mining pipelines based on stochastic population-based meta-heuristics automatically. Along with the theoretical representation of the proposed method, we also present a comprehensive experimental evaluation of the proposed method. 

**Abstract (ZH)**: 基于随机种群启发式算法的自动生成方法NiaAutoARM，在同时处理数值型和分类型属性方面改进了数值关联规则挖掘的范式，有助于从包含多种特征的数据集中发现关联。由于该过程包括多个需要顺序执行的处理步骤，形成一个完整的管道，例如预处理、算法选择、超参数优化以及评估关联规则质量的度量，因此该过程并不简单。本文我们提出了一种新的自动化机器学习方法NiaAutoARM，用于基于随机种群启发式算法自动构建完整的关联规则挖掘管道。除理论描述外，我们还提供了对该方法的全面实验评估。 

---
# Detection-Fusion for Knowledge Graph Extraction from Videos 

**Title (ZH)**: 视频中知识图 extraction 的检测融合方法 

**Authors**: Taniya Das, Louis Mahon, Thomas Lukasiewicz  

**Link**: [PDF](https://arxiv.org/pdf/2501.00136)  

**Abstract**: One of the challenging tasks in the field of video understanding is extracting semantic content from video inputs. Most existing systems use language models to describe videos in natural language sentences, but this has several major shortcomings. Such systems can rely too heavily on the language model component and base their output on statistical regularities in natural language text rather than on the visual contents of the video. Additionally, natural language annotations cannot be readily processed by a computer, are difficult to evaluate with performance metrics and cannot be easily translated into a different natural language. In this paper, we propose a method to annotate videos with knowledge graphs, and so avoid these problems. Specifically, we propose a deep-learning-based model for this task that first predicts pairs of individuals and then the relations between them. Additionally, we propose an extension of our model for the inclusion of background knowledge in the construction of knowledge graphs. 

**Abstract (ZH)**: 在视频理解领域，从视频输入中提取语义内容是一项具有挑战性的任务。现有的大多数系统利用语言模型以自然语言句子的方式描述视频，但这种方法存在几个显著的缺点。这类系统可能会过度依赖语言模型组件，并且其输出主要基于自然语言文本中的统计规律，而不是视频中的视觉内容。此外，自然语言注释不适合计算机直接处理，难以用性能指标对其进行评估，并且不能轻易地翻译成其他自然语言。在本文中，我们提出了一种使用知识图谱对视频进行标注的方法，以避免上述问题。具体而言，我们提出了一种基于深度学习的模型，首先预测个体之间的配对关系，然后预测它们之间的关系。此外，我们还提出了一种扩展模型，以纳入背景知识来构建知识图谱。 

---
# GroverGPT: A Large Language Model with 8 Billion Parameters for Quantum Searching 

**Title (ZH)**: GroverGPT：一种用于量子搜索的80亿参数大型语言模型 

**Authors**: Haoran Wang, Pingzhi Li, Min Chen, Jinglei Cheng, Junyu Liu, Tianlong Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00135)  

**Abstract**: Quantum computing is an exciting non-Von Neumann paradigm, offering provable speedups over classical computing for specific problems. However, the practical limits of classical simulatability for quantum circuits remain unclear, especially with current noisy quantum devices. In this work, we explore the potential of leveraging Large Language Models (LLMs) to simulate the output of a quantum Turing machine using Grover's quantum circuits, known to provide quadratic speedups over classical counterparts. To this end, we developed GroverGPT, a specialized model based on LLaMA's 8-billion-parameter architecture, trained on over 15 trillion tokens. Unlike brute-force state-vector simulations, which demand substantial computational resources, GroverGPT employs pattern recognition to approximate quantum search algorithms without explicitly representing quantum states. Analyzing 97K quantum search instances, GroverGPT consistently outperformed OpenAI's GPT-4o (45\% accuracy), achieving nearly 100\% accuracy on 6- and 10-qubit datasets when trained on 4-qubit or larger datasets. It also demonstrated strong generalization, surpassing 95\% accuracy for systems with over 20 qubits when trained on 3- to 6-qubit data. Analysis indicates GroverGPT captures quantum features of Grover's search rather than classical patterns, supported by novel prompting strategies to enhance performance. Although accuracy declines with increasing system size, these findings offer insights into the practical boundaries of classical simulatability. This work suggests task-specific LLMs can surpass general-purpose models like GPT-4o in quantum algorithm learning and serve as powerful tools for advancing quantum research. 

**Abstract (ZH)**: 量子计算是一种激动人心的非冯·诺伊曼范式，在特定问题上可以提供可证明的经典加速。然而，当前嘈杂的量子设备使得经典模拟量子电路的实用界限仍然模糊不清。在这项工作中，我们探讨了利用大型语言模型（LLMs）模拟量子图灵机输出的潜力，特别是在Grover量子电路的帮助下，这些电路提供了经典对应物的二次加速。为此，我们开发了GroverGPT，这是一种基于LLaMA 80亿参数架构的专业模型，并使用超过15万亿个标记进行训练。与需求大量计算资源的糊化态矢量模拟不同，GroverGPT利用模式识别来近似量子搜索算法，而无需显式表示量子态。通过分析97,000个量子搜索实例，GroverGPT在准确性上始终优于OpenAI的GPT-4o（45%的准确性），在使用4量子比特或更大数据集训练时，6-比特和10-比特数据集的准确性接近100%。此外，GroverGPT还展示了很强的泛化能力，在使用3-至6量子比特数据集训练时，对于超过20量子比特的系统也取得了超过95%的准确性。分析表明，GroverGPT捕捉到了Grover搜索的量子特征而不是经典模式，这一结论得到了新的提示策略以提高性能的支持。尽管准确性随系统规模的增加而下降，但这些发现对于理解经典模拟的实用界限提供了见解。这项工作表明，针对特定任务的LLM可以在量子算法学习方面超越通用模型如GPT-4o，并作为推进量子研究的强大工具。 

---
# A Data-Centric Approach to Detecting and Mitigating Demographic Bias in Pediatric Mental Health Text: A Case Study in Anxiety Detection 

**Title (ZH)**: 以数据为中心的方法检测和缓解儿童心理健康文本中的人口统计偏见：焦虑检测案例研究 

**Authors**: Julia Ive, Paulina Bondaronek, Vishal Yadav, Daniel Santel, Tracy Glauser, Tina Cheng, Jeffrey R. Strawn, Greeshma Agasthya, Jordan Tschida, Sanghyun Choo, Mayanka Chandrashekar, Anuj J. Kapadia, John Pestian  

**Link**: [PDF](https://arxiv.org/pdf/2501.00129)  

**Abstract**: Introduction: Healthcare AI models often inherit biases from their training data. While efforts have primarily targeted bias in structured data, mental health heavily depends on unstructured data. This study aims to detect and mitigate linguistic differences related to non-biological differences in the training data of AI models designed to assist in pediatric mental health screening. Our objectives are: (1) to assess the presence of bias by evaluating outcome parity across sex subgroups, (2) to identify bias sources through textual distribution analysis, and (3) to develop a de-biasing method for mental health text data. Methods: We examined classification parity across demographic groups and assessed how gendered language influences model predictions. A data-centric de-biasing method was applied, focusing on neutralizing biased terms while retaining salient clinical information. This methodology was tested on a model for automatic anxiety detection in pediatric patients. Results: Our findings revealed a systematic under-diagnosis of female adolescent patients, with a 4% lower accuracy and a 9% higher False Negative Rate (FNR) compared to male patients, likely due to disparities in information density and linguistic differences in patient notes. Notes for male patients were on average 500 words longer, and linguistic similarity metrics indicated distinct word distributions between genders. Implementing our de-biasing approach reduced diagnostic bias by up to 27%, demonstrating its effectiveness in enhancing equity across demographic groups. Discussion: We developed a data-centric de-biasing framework to address gender-based content disparities within clinical text. By neutralizing biased language and enhancing focus on clinically essential information, our approach demonstrates an effective strategy for mitigating bias in AI healthcare models trained on text. 

**Abstract (ZH)**: 简介：医疗保健领域的AI模型往往会继承其训练数据中的偏见。尽管努力主要集中在结构化数据的偏见上，但心理健康状况却高度依赖于非结构化数据。本研究旨在检测并减轻辅助儿童精神健康筛查的AI模型训练数据中与非生物差异相关的语言差异。我们的目标是：（1）通过评估性别子组之间结果的公平性来评估偏见的存在；（2）通过文本分布分析识别偏见来源；（3）开发针对精神健康文本数据的去偏方法。方法：我们分析了不同人口统计学组之间分类的公平性，并评估了性别化语言对模型预测的影响。我们应用了一种以数据为中心的去偏方法，重点是在消除偏见术语的同时保留关键的临床信息。这种方法在自动检测儿科患者焦虑症的模型中进行了测试。结果：我们的研究发现，对于女性青少年患者存在系统性的诊断不足，其准确度低 4%，假阴性率（FNR）高 9%，这可能是由于信息密度差异和患者记录中语言差异造成的。男性患者的笔记平均长500词，语言相似度指标显示性别之间有明显的词汇分布差异。应用我们的去偏方法可减少高达27%的诊断偏见，这证明了其在增进不同人口统计学组之间公平性方面的有效性。讨论：我们开发了一种以数据为中心的去偏框架，以解决临床文本中基于性别的内容差异。通过消除偏见语言并增强对临床相关信息的关注，我们的方法展示了在文本训练的AI医疗保健模型中减轻偏见的有效策略。 

---
# Text-to-Image GAN with Pretrained Representations 

**Title (ZH)**: 预训练表示的文本到图像生成网络 

**Authors**: Xiaozhou You, Jian Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00116)  

**Abstract**: Generating desired images conditioned on given text descriptions has received lots of attention. Recently, diffusion models and autoregressive models have demonstrated their outstanding expressivity and gradually replaced GAN as the favored architectures for text-to-image synthesis. However, they still face some obstacles: slow inference speed and expensive training costs. To achieve more powerful and faster text-to-image synthesis under complex scenes, we propose TIGER, a text-to-image GAN with pretrained representations. To be specific, we propose a vision-empowered discriminator and a high-capacity generator. (i) The vision-empowered discriminator absorbs the complex scene understanding ability and the domain generalization ability from pretrained vision models to enhance model performance. Unlike previous works, we explore stacking multiple pretrained models in our discriminator to collect multiple different representations. (ii) The high-capacity generator aims to achieve effective text-image fusion while increasing the model capacity. The high-capacity generator consists of multiple novel high-capacity fusion blocks (HFBlock). And the HFBlock contains several deep fusion modules and a global fusion module, which play different roles to benefit our model. Extensive experiments demonstrate the outstanding performance of our proposed TIGER both on standard and zero-shot text-to-image synthesis tasks. On the standard text-to-image synthesis task, TIGER achieves state-of-the-art performance on two challenging datasets, which obtain a new FID 5.48 (COCO) and 9.38 (CUB). On the zero-shot text-to-image synthesis task, we achieve comparable performance with fewer model parameters, smaller training data size and faster inference speed. Additionally, more experiments and analyses are conducted in the Supplementary Material. 

**Abstract (ZH)**: 基于给定文字描述生成所需图像的研究受到了广泛关注。最近，扩散模型和自回归模型展示了其出色的表现力，并逐渐取代了生成对抗网络（GAN）在文字到图像合成方面的青睐地位。然而，它们仍然面临着一些障碍：推理速度较慢和训练成本较高。为了在复杂场景下实现更强大的、更快的文字到图像合成，我们提出了一种具有预训练表征的文本到图像生成对抗网络（TIGER）。具体而言，我们提出了一种视觉增强的判别器和一个高容量生成器。（i）视觉增强的判别器从预训练的视觉模型中吸收复杂的场景理解能力和领域泛化能力，以增强模型性能。与先前的工作不同，我们在判别器中探索堆叠多个预训练模型，以收集多种不同的表示。（ii）高容量生成器旨在在提高模型容量的同时实现有效的图文融合。高容量生成器由多个新颖的高容量融合块（HFBlock）组成，而HFBlock包含多个深度融合模块和一个全局融合模块，它们在我们的模型中发挥不同的作用。广泛的实验表明，在标准和零-shot文字到图像合成任务中，我们提出的TIGER均表现出色。在标准文字到图像合成任务中，TIGER在两个具有挑战性的数据集上达到了最先进的性能，分别获得新的FID值5.48（COCO）和9.38（CUB）。在零-shot文字到图像合成任务中，我们使用较少的模型参数、较小的训练数据量和更快的推理速度实现了可媲美的性能。此外，我们在补充材料中还进行了更多的实验和分析。 

---
# An Unsupervised Anomaly Detection in Electricity Consumption Using Reinforcement Learning and Time Series Forest Based Framework 

**Title (ZH)**: 使用强化学习和时间序列森林基于框架的无监督电能消耗异常检测 

**Authors**: Jihan Ghanim, Mariette Awad  

**Link**: [PDF](https://arxiv.org/pdf/2501.00107)  

**Abstract**: Anomaly detection (AD) plays a crucial role in time series applications, primarily because time series data is employed across real-world scenarios. Detecting anomalies poses significant challenges since anomalies take diverse forms making them hard to pinpoint accurately. Previous research has explored different AD models, making specific assumptions with varying sensitivity toward particular anomaly types. To address this issue, we propose a novel model selection for unsupervised AD using a combination of time series forest (TSF) and reinforcement learning (RL) approaches that dynamically chooses an AD technique. Our approach allows for effective AD without explicitly depending on ground truth labels that are often scarce and expensive to obtain. Results from the real-time series dataset demonstrate that the proposed model selection approach outperforms all other AD models in terms of the F1 score metric. For the synthetic dataset, our proposed model surpasses all other AD models except for KNN, with an impressive F1 score of 0.989. The proposed model selection framework also exceeded the performance of GPT-4 when prompted to act as an anomaly detector on the synthetic dataset. Exploring different reward functions revealed that the original reward function in our proposed AD model selection approach yielded the best overall scores. We evaluated the performance of the six AD models on an additional three datasets, having global, local, and clustered anomalies respectively, showing that each AD model exhibited distinct performance depending on the type of anomalies. This emphasizes the significance of our proposed AD model selection framework, maintaining high performance across all datasets, and showcasing superior performance across different anomaly types. 

**Abstract (ZH)**: 异常检测（AD）在时间序列应用中扮演着至关重要的角色，主要原因在于时间序列数据广泛应用于现实世界的各个场景。检测异常值面临重大挑战，因为异常值形式多样，难以准确识别。之前的研究所探讨了不同的AD模型，并在不同程度上对特定类型的异常值有不同的敏感性。为了应对这一问题，我们提出了一种新颖的时间序列森林（TSF）与强化学习（RL）结合的无监督AD模型选择方法，该方法能够动态选择合适的AD技术。我们的方法在不依赖于稀缺且获取成本较高的真实标签的情况下，能够有效地进行异常检测。结果显示，我们在实时序列数据集上的方法在F1分数指标上超过了其他所有AD模型。对于合成数据集，我们的模型除了与KNN的F1分数为0.989外，超过了其他所有AD模型。在要求GPT-4充当异常检测器时，我们提出的模型选择框架的性能也超过了GPT-4。通过对多种奖励函数的探索，发现我们提出的AD模型选择方法中原始的奖励函数在总体得分上表现最佳。

我们进一步评估了六个AD模型在另外三个数据集上的性能，这三个数据集分别具有全球性、局部性和成簇性异常，结果显示每个AD模型在不同类型的异常值检测上的表现有所不同。这强调了我们提出的AD模型选择框架的重要性，能够在所有数据集上保持高水平的性能，并在不同类型的异常检测中展现出优越的性能。 

---
# LicenseGPT: A Fine-tuned Foundation Model for Publicly Available Dataset License Compliance 

**Title (ZH)**: LicenseGPT：用于公共数据集许可合规性的细调基础模型 

**Authors**: Jingwen Tan, Gopi Krishnan Rajbahadur, Zi Li, Xiangfu Song, Jianshan Lin, Dan Li, Zibin Zheng, Ahmed E. Hassan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00106)  

**Abstract**: Dataset license compliance is a critical yet complex aspect of developing commercial AI products, particularly with the increasing use of publicly available datasets. Ambiguities in dataset licenses pose significant legal risks, making it challenging even for software IP lawyers to accurately interpret rights and obligations. In this paper, we introduce LicenseGPT, a fine-tuned foundation model (FM) specifically designed for dataset license compliance analysis. We first evaluate existing legal FMs (i.e., FMs specialized in understanding and processing legal texts) and find that the best-performing model achieves a Prediction Agreement (PA) of only 43.75%. LicenseGPT, fine-tuned on a curated dataset of 500 licenses annotated by legal experts, significantly improves PA to 64.30%, outperforming both legal and general-purpose FMs. Through an A/B test and user study with software IP lawyers, we demonstrate that LicenseGPT reduces analysis time by 94.44%, from 108 seconds to 6 seconds per license, without compromising accuracy. Software IP lawyers perceive LicenseGPT as a valuable supplementary tool that enhances efficiency while acknowledging the need for human oversight in complex cases. Our work underscores the potential of specialized AI tools in legal practice and offers a publicly available resource for practitioners and researchers. 

**Abstract (ZH)**: 数据集许可合规是开发商业AI产品的一个关键但复杂的方面，尤其是在公共数据集的使用日益增多的情况下。数据集许可中的模糊性带来了重大的法律风险，甚至令软件知识产权律师在准确解释权利和义务方面也面临挑战。本文介绍了LicenseGPT，这是一种专门为数据集许可合规分析而 fine-tuned 的基础模型（FM）。我们首先评估了现有的法律基础模型（即专门用于理解和处理法律文本的 FM），并发现最好性能的模型仅实现了 43.75% 的预测一致性（PA）。LicenseGPT 通过在其上 fine-tuned 一个由法律专家标注的 500 个许可数据集，显著地将 PA 提高到 64.30%，超过了法律基础模型和一般的 FM。通过对比测试和软件知识产权律师的用户研究，我们证明 LicenseGPT 可将每份许可的分析时间缩短 94.44%，从 108 秒减少到 6 秒，同时保持准确性。软件知识产权律师认为 LicenseGPT 是一个有价值的补充工具，能提高效率，同时承认在复杂情况下仍需人力监督。我们的工作突显了专业 AI 工具在法律实践中的潜力，并为从业者和研究者提供了一个公开可用的资源。 

---
# CaseSumm: A Large-Scale Dataset for Long-Context Summarization from U.S. Supreme Court Opinions 

**Title (ZH)**: CaseSumm：源自美国最高法院意见的大型长上下文摘要数据集 

**Authors**: Mourad Heddaya, Kyle MacMillan, Anup Malani, Hongyuan Mei, Chenhao Tan  

**Link**: [PDF](https://arxiv.org/pdf/2501.00097)  

**Abstract**: This paper introduces CaseSumm, a novel dataset for long-context summarization in the legal domain that addresses the need for longer and more complex datasets for summarization evaluation. We collect 25.6K U.S. Supreme Court (SCOTUS) opinions and their official summaries, known as "syllabuses." Our dataset is the largest open legal case summarization dataset, and is the first to include summaries of SCOTUS decisions dating back to 1815.
We also present a comprehensive evaluation of LLM-generated summaries using both automatic metrics and expert human evaluation, revealing discrepancies between these assessment methods. Our evaluation shows Mistral 7b, a smaller open-source model, outperforms larger models on most automatic metrics and successfully generates syllabus-like summaries. In contrast, human expert annotators indicate that Mistral summaries contain hallucinations. The annotators consistently rank GPT-4 summaries as clearer and exhibiting greater sensitivity and specificity. Further, we find that LLM-based evaluations are not more correlated with human evaluations than traditional automatic metrics. Furthermore, our analysis identifies specific hallucinations in generated summaries, including precedent citation errors and misrepresentations of case facts. These findings demonstrate the limitations of current automatic evaluation methods for legal summarization and highlight the critical role of human evaluation in assessing summary quality, particularly in complex, high-stakes domains.
CaseSumm is available at this https URL 

**Abstract (ZH)**: 本文介绍了CaseSumm，这是一个针对法律领域的新型数据集，用于长上下文摘要总结，旨在解决摘要评估中对更长、更复杂的数据集的需求。我们收集了25,600篇美国最高法院（SCOTUS）意见及其官方摘要，即“概要”。我们的数据集是最大的开放法律案例摘要数据集，并且是第一个包含可追溯至1815年的SCOTUS决策摘要的数据集。

此外，我们还使用自动评估指标和专业知识评估了LLM生成的摘要，揭示了这些评估方法之间的差异。我们的评估结果显示，一个较小的开源模型Mistral 7b在大多数自动评估指标上表现优于大型模型，并能够生成类似概要的摘要。相比之下，专家人工标注者指出，Mistral的摘要存在虚构信息。注释者一致认为GPT-4的摘要更加清晰，并显示出更高的准确性和针对性。进一步的研究发现，基于LLM的评估与传统自动评估指标同样不更相关。此外，我们的分析指出了生成摘要中的具体虚构信息，包括先例引用错误和案件事实的误述。这些发现表明当前自动评估方法在法律摘要总结方面存在局限性，并强调了在复杂、高风险领域评估摘要质量时人类评估的至关重要的作用。

数据集CaseSumm可通过以下链接访问：[请提供链接] 

---
# Machine Learning-Based Security Policy Analysis 

**Title (ZH)**: 基于机器学习的安防策略分析 

**Authors**: Krish Jain, Joann Sum, Pranav Kapoor, Amir Eaman  

**Link**: [PDF](https://arxiv.org/pdf/2501.00085)  

**Abstract**: Security-Enhanced Linux (SELinux) is a robust security mechanism that enforces mandatory access controls (MAC), but its policy language's complexity creates challenges for policy analysis and management. This research investigates the automation of SELinux policy analysis using graph-based techniques combined with machine learning approaches to detect policy anomalies. The study addresses two key questions: Can SELinux policy analysis be automated through graph analysis, and how do different anomaly detection models compare in analyzing SELinux policies? We will be comparing different machine learning models by evaluating their effectiveness in detecting policy violations and anomalies. Our approach utilizes Neo4j for graph representation of policies, with Node2vec transforming these graph structures into meaningful vector embeddings that can be processed by our machine learning models. In our results, the MLP Neural Network consistently demonstrated superior performance across different dataset sizes, achieving 95% accuracy with balanced precision and recall metrics, while both Random Forest and SVM models showed competitive but slightly lower performance in detecting policy violations. This combination of graph-based modeling and machine learning provides a more sophisticated and automated approach to understanding and analyzing complex SELinux policies compared to traditional manual analysis methods. 

**Abstract (ZH)**: 增强安全的Linux（SELinux）是一种强大的安全机制，它强制执行强制访问控制（MAC），但其策略语言的复杂性给策略分析和管理带来了挑战。本研究旨在通过结合图技术与机器学习方法，自动进行SELinux策略分析，并检测政策异常。研究主要解答了两个关键问题：SELinux策略分析是否可以通过图分析实现自动化，以及不同异常检测模型在分析SELinux策略方面的表现如何？我们将通过评估这些模型在检测策略违规和异常方面的有效性来比较不同的机器学习模型。我们的方法利用Neo4j表示策略的图结构，并通过Node2vec将这些图结构转换成有意义的向量嵌入，以便我们的机器学习模型进行处理。在我们的实验结果中，多层感知器（MLP）神经网络在不同数据集大小的情况下始终保持了最佳性能，达到了95%的准确率，同时保持了均衡的精确度和召回率指标，而随机森林和支持向量机（SVM）模型在检测策略违规方面显示出了竞争力但略低的性能。这种结合图建模和机器学习的方法为理解和分析复杂SELinux策略提供了一个更高级且自动化的途径，相比于传统的手动分析方法更为优越。 

---
# AI Agent for Education: von Neumann Multi-Agent System Framework 

**Title (ZH)**: 教育中的AI代理：冯·诺伊曼多代理系统框架 

**Authors**: Yuan-Hao Jiang, Ruijia Li, Yizhou Zhou, Changyong Qi, Hanglei Hu, Yuang Wei, Bo Jiang, Yonghe Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00083)  

**Abstract**: The development of large language models has ushered in new paradigms for education. This paper centers on the multi-Agent system in education and proposes the von Neumann multi-Agent system framework. It breaks down each AI Agent into four modules: control unit, logic unit, storage unit, and input-output devices, defining four types of operations: task deconstruction, self-reflection, memory processing, and tool invocation. Furthermore, it introduces related technologies such as Chain-of-Thought, Reson+Act, and Multi-Agent Debate associated with these four types of operations. The paper also discusses the ability enhancement cycle of a multi-Agent system for education, including the outer circulation for human learners to promote knowledge construction and the inner circulation for LLM-based-Agents to enhance swarm intelligence. Through collaboration and reflection, the multi-Agent system can better facilitate human learners' learning and enhance their teaching abilities in this process. 

**Abstract (ZH)**: 大规模语言模型的发展为教育带来了新的范式。本文关注教育中的多Agent系统，并提出了一种冯·诺伊曼多Agent系统框架。该框架将每个AI Agent分解为四个模块：控制单元、逻辑单元、存储单元和输入输出设备，并定义了四种类型的操作：任务分解、自我反思、记忆处理和工具调用。此外，本文还介绍了与这四种操作相关的相关技术，如Chain-of-Thought、Reson+Act和多Agent辩论。文章还讨论了教育中多Agent系统的能力建设计划，包括外循环以促进人类学习者的知识构建，以及内循环以增强基于LLM的Agent的群体智能。通过协作和反思，多Agent系统可以更好地促进人类学习者的学习过程，并在此过程中增强他们的教学能力。 

---
# Human-like Bots for Tactical Shooters Using Compute-Efficient Sensors 

**Title (ZH)**: 使用计算高效传感器的战术射击游戏仿人类机器人 

**Authors**: Niels Justesen, Maria Kaselimi, Sam Snodgrass, Miruna Vozaru, Matthew Schlegel, Jonas Wingren, Gabriella A. B. Barros, Tobias Mahlmann, Shyam Sudhakaran, Wesley Kerr, Albert Wang, Christoffer Holmgård, Georgios N. Yannakakis, Sebastian Risi, Julian Togelius  

**Link**: [PDF](https://arxiv.org/pdf/2501.00078)  

**Abstract**: Artificial intelligence (AI) has enabled agents to master complex video games, from first-person shooters like Counter-Strike to real-time strategy games such as StarCraft II and racing games like Gran Turismo. While these achievements are notable, applying these AI methods in commercial video game production remains challenging due to computational constraints. In commercial scenarios, the majority of computational resources are allocated to 3D rendering, leaving limited capacity for AI methods, which often demand high computational power, particularly those relying on pixel-based sensors. Moreover, the gaming industry prioritizes creating human-like behavior in AI agents to enhance player experience, unlike academic models that focus on maximizing game performance. This paper introduces a novel methodology for training neural networks via imitation learning to play a complex, commercial-standard, VALORANT-like 2v2 tactical shooter game, requiring only modest CPU hardware during inference. Our approach leverages an innovative, pixel-free perception architecture using a small set of ray-cast sensors, which capture essential spatial information efficiently. These sensors allow AI to perform competently without the computational overhead of traditional methods. Models are trained to mimic human behavior using supervised learning on human trajectory data, resulting in realistic and engaging AI agents. Human evaluation tests confirm that our AI agents provide human-like gameplay experiences while operating efficiently under computational constraints. This offers a significant advancement in AI model development for tactical shooter games and possibly other genres. 

**Abstract (ZH)**: 人工智能（AI）已经使代理能够掌握复杂的视频游戏，从第一人称射击游戏如《反恐精英》（Counter-Strike）到即时战略游戏如《星际争霸II》以及赛车游戏如《Gran Turismo》。尽管这些成就值得关注，但在商业视频游戏制作中应用这些AI方法仍然面临挑战，因为计算资源受限。在商业场景中，大部分计算资源用于3D渲染，留给AI方法的计算能力有限，而这些方法通常需要高性能的计算能力，尤其是依赖于像素传感器的方法。此外，游戏行业更注重创造符合人类行为的AI代理以提升玩家体验，而非学术模型关注的游戏性能最大化的任务。本文介绍了一种通过模仿学习训练神经网络的新方法，使其能够在复杂的、商业标准的VALORANT风格的2V2战术射击游戏中表现优异，仅需少量CPU硬件即可进行推理。我们的方法利用了一种创新的无像素感知架构，使用少量射线传感器来高效捕捉空间信息。这些传感器使AI能够在不承担传统方法计算开销的情况下进行有效操作。模型通过监督学习模仿人类行为训练而成，从而产生具有真实感和沉浸感的AI代理。人评价测试结果显示，我们的AI代理能够在计算资源受限的情况下提供类似人类的 gameplay 经验。这为战术射击游戏及其他类型游戏的AI模型开发提供了重要进展。 

---
# A Novel Framework for Learning Stochastic Representations for Sequence Generation and Recognition 

**Title (ZH)**: 一种用于序列生成与识别的学习随机表示的新框架 

**Authors**: Jungsik Hwang, Ahmadreza Ahmadi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00076)  

**Abstract**: The ability to generate and recognize sequential data is fundamental for autonomous systems operating in dynamic environments. Inspired by the key principles of the brain-predictive coding and the Bayesian brain-we propose a novel stochastic Recurrent Neural Network with Parametric Biases (RNNPB). The proposed model incorporates stochasticity into the latent space using the reparameterization trick used in variational autoencoders. This approach enables the model to learn probabilistic representations of multidimensional sequences, capturing uncertainty and enhancing robustness against overfitting. We tested the proposed model on a robotic motion dataset to assess its performance in generating and recognizing temporal patterns. The experimental results showed that the stochastic RNNPB model outperformed its deterministic counterpart in generating and recognizing motion sequences. The results highlighted the proposed model's capability to quantify and adjust uncertainty during both learning and inference. The stochasticity resulted in a continuous latent space representation, facilitating stable motion generation and enhanced generalization when recognizing novel sequences. Our approach provides a biologically inspired framework for modeling temporal patterns and advances the development of robust and adaptable systems in artificial intelligence and robotics. 

**Abstract (ZH)**: 在动态环境中自主系统生成和识别序贯数据的能力是其基本要求。受大脑预测编码和贝叶斯大脑原理的启发，我们提出了一种带参数偏置的随机循环神经网络（RNNPB）。该模型通过变分自编码器中使用的重参数化技巧将随机性引入潜空间，从而使模型能够学习多维序列的概率表示，捕捉不确定性并增强对抗过拟合的鲁棒性。我们使用一个机器人运动数据集测试了所提出模型，以评估其生成和识别时间模式的能力。实验结果表明，带随机性的RNNPB模型在生成和识别运动序列方面优于其确定性对照模型。结果突显了所提模型在学习和推断过程中量化和调整不确定性的能力。随机性产生了连续的潜空间表示，使运动生成更加稳定，并在识别新序列时增强了泛化能力。本研究提供了一种生物启发的框架来建模时间模式，并推进了人工智能和机器人领域中稳健且适应性强的系统的发展。 

---
# Open-Book Neural Algorithmic Reasoning 

**Title (ZH)**: 开放书籍神经算法推理 

**Authors**: Hefei Li, Chao Peng, Chenyang Xu, Zhengfeng Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00072)  

**Abstract**: Neural algorithmic reasoning is an emerging area of machine learning that focuses on building neural networks capable of solving complex algorithmic tasks. Recent advancements predominantly follow the standard supervised learning paradigm -- feeding an individual problem instance into the network each time and training it to approximate the execution steps of a classical algorithm. We challenge this mode and propose a novel open-book learning framework. In this framework, whether during training or testing, the network can access and utilize all instances in the training dataset when reasoning for a given instance.
Empirical evaluation is conducted on the challenging CLRS Algorithmic Reasoning Benchmark, which consists of 30 diverse algorithmic tasks. Our open-book learning framework exhibits a significant enhancement in neural reasoning capabilities. Further, we notice that there is recent literature suggesting that multi-task training on CLRS can improve the reasoning accuracy of certain tasks, implying intrinsic connections between different algorithmic tasks. We delve into this direction via the open-book framework. When the network reasons for a specific task, we enable it to aggregate information from training instances of other tasks in an attention-based manner. We show that this open-book attention mechanism offers insights into the inherent relationships among various tasks in the benchmark and provides a robust tool for interpretable multi-task training. 

**Abstract (ZH)**: 神经算法推理是机器学习的一个新兴领域，专注于构建能够解决复杂算法任务的神经网络。近期的进展主要遵循传统的监督学习范式——每次向网络输入单个问题实例，并训练其逼近经典算法的执行步骤。我们挑战这一模式，并提出了一种新的开放书籍学习框架。在此框架下，无论是训练还是测试，网络在推理某个实例时可以访问并利用训练数据集中的所有实例。

我们在具有挑战性的CLRS算法推理基准上进行了经验评估，该基准包含30个不同的算法任务。我们的开放书籍学习框架展示了神经推理能力的显著提升。此外，我们注意到最近有文献表明，在CLRS上进行多任务训练可以提高某些任务的推理准确性，暗示不同算法任务之间存在内在联系。我们通过开放书籍框架探索了这一方向。在网络推理特定任务时，我们允许它以基于注意力的方式聚合其他任务训练实例中的信息。我们展示了这种开放书籍注意力机制为理解基准中各种任务的内在关系提供了见解，并提供了一种用于可解释多任务训练的稳健工具。 

---
# ICLR: In-Context Learning of Representations 

**Title (ZH)**: ICLR：基于上下文的学习表示 

**Authors**: Core Francisco Park, Andrew Lee, Ekdeep Singh Lubana, Yongyi Yang, Maya Okawa, Kento Nishi, Martin Wattenberg, Hidenori Tanaka  

**Link**: [PDF](https://arxiv.org/pdf/2501.00070)  

**Abstract**: Recent work has demonstrated that semantics specified by pretraining data influence how representations of different concepts are organized in a large language model (LLM). However, given the open-ended nature of LLMs, e.g., their ability to in-context learn, we can ask whether models alter these pretraining semantics to adopt alternative, context-specified ones. Specifically, if we provide in-context exemplars wherein a concept plays a different role than what the pretraining data suggests, do models reorganize their representations in accordance with these novel semantics? To answer this question, we take inspiration from the theory of conceptual role semantics and define a toy "graph tracing" task wherein the nodes of the graph are referenced via concepts seen during training (e.g., apple, bird, etc.) and the connectivity of the graph is defined via some predefined structure (e.g., a square grid). Given exemplars that indicate traces of random walks on the graph, we analyze intermediate representations of the model and find that as the amount of context is scaled, there is a sudden re-organization from pretrained semantic representations to in-context representations aligned with the graph structure. Further, we find that when reference concepts have correlations in their semantics (e.g., Monday, Tuesday, etc.), the context-specified graph structure is still present in the representations, but is unable to dominate the pretrained structure. To explain these results, we analogize our task to energy minimization for a predefined graph topology, providing evidence towards an implicit optimization process to infer context-specified semantics. Overall, our findings indicate scaling context-size can flexibly re-organize model representations, possibly unlocking novel capabilities. 

**Abstract (ZH)**: 近期的研究已经表明，预训练数据指定的语义影响大型语言模型（LLM）中不同类型概念的表示组织方式。然而，鉴于LLM的开放性，例如它们的上下文学习能力，我们是否可以询问模型是否会改变这些预训练语义以适应上下文指定的语义？具体来说，如果我们提供一些范例，其中某个概念在这些范例中的作用不同于预训练数据所暗示的，模型是否会根据这些新颖的语义重新组织其表示？为了回答这个问题，我们借鉴概念角色语义理论，并定义了一个简单的“图跟踪”任务。在这个任务中，图的节点通过训练期间见过的概念（例如苹果、鸟等）进行引用，而图的连接性通过某些预定义的结构（例如正方形网格）来定义。我们提供了一些表明图形上随机漫步路径的范例，并分析模型的中间表示。结果显示，随着上下文量的增加，模型的表示会突然从预训练语义重新组织为与图形结构对齐的上下文指定表示。进一步地，我们发现当参考概念在语义上存在相关性（例如周一、周二等）时，上下文指定的图形结构仍然存在于表示中，但无法主导预训练结构。为了解释这些结果，我们将任务类比于预定义图拓扑的能源最小化过程，提供了一种隐式优化过程以推断上下文指定的语义的证据。总体而言，我们的研究结果表明，扩大上下文规模可以灵活地重新组织模型表示，这可能解锁新的能力。 

---
# Adversarial Negotiation Dynamics in Generative Language Models 

**Title (ZH)**: 生成语言模型中的对抗性谈判动态 

**Authors**: Arinbjörn Kolbeinsson, Benedikt Kolbeinsson  

**Link**: [PDF](https://arxiv.org/pdf/2501.00069)  

**Abstract**: Generative language models are increasingly used for contract drafting and enhancement, creating a scenario where competing parties deploy different language models against each other. This introduces not only a game-theory challenge but also significant concerns related to AI safety and security, as the language model employed by the opposing party can be unknown. These competitive interactions can be seen as adversarial testing grounds, where models are effectively red-teamed to expose vulnerabilities such as generating biased, harmful or legally problematic text. Despite the importance of these challenges, the competitive robustness and safety of these models in adversarial settings remain poorly understood. In this small study, we approach this problem by evaluating the performance and vulnerabilities of major open-source language models in head-to-head competitions, simulating real-world contract negotiations. We further explore how these adversarial interactions can reveal potential risks, informing the development of more secure and reliable models. Our findings contribute to the growing body of research on AI safety, offering insights into model selection and optimisation in competitive legal contexts and providing actionable strategies for mitigating risks. 

**Abstract (ZH)**: 生成式语言模型在合同起草和改进中越来越广泛地使用，这创造了一个场景，即竞争方可能采用不同的语言模型对彼此进行挑战。这不仅引入了博弈论方面的挑战，还对人工智能的安全性和安全性提出了重大关切，因为对方使用的语言模型是未知的。这些竞争性交互可以被视为对抗测试环境，模型在这种环境中有效扮演红队角色，以揭示如生成有偏见、有害或法律问题文本等漏洞。尽管这些挑战的重要性不言而喻，但这些模型在对抗环境中的竞争稳健性与安全性仍然知之甚少。在这项小型研究中，我们通过评估主要开源语言模型在头对头竞争中的表现和漏洞，模拟真实的合同谈判过程，来解决这一问题。我们进一步探讨了这些对抗性交互如何揭示潜在风险，从而指导开发更安全、更可靠的模型。我们的研究结果为不断增长的关于人工智能安全性的研究文献做出了贡献，提供了在竞争性法律环境中进行模型选择和优化的见解，并提供了规避风险的可行策略。 

---
# Ensemble of classifiers for speech evaluation 

**Title (ZH)**: 语音评估的分类器ensemble方法 

**Authors**: G. Belokrylov, A. Korenev, B. Lodonova, A. Novokhrestov  

**Link**: [PDF](https://arxiv.org/pdf/2501.00067)  

**Abstract**: The article describes an attempt to apply an ensemble of binary classifiers to solve the problem of speech assessment in medicine. A dataset was compiled based on quantitative and expert assessments of syllable pronunciation quality. Quantitative assessments of 7 selected metrics were used as features: dynamic time warp distance, Minkowski distance, correlation coefficient, longest common subsequence (LCSS), edit distance of real se-quence (EDR), edit distance with real penalty (ERP), and merge split (MSM). Expert as-sessment of pronunciation quality was used as a class label: class 1 means high-quality speech, class 0 means distorted. A comparison of training results was carried out for five classification methods: logistic regression (LR), support vector machine (SVM), naive Bayes (NB), decision trees (DT), and K-nearest neighbors (KNN). The results of using the mixture method to build an ensemble of classifiers are also presented. The use of an en-semble for the studied data sets allowed us to slightly increase the classification accuracy compared to the use of individual binary classifiers. 

**Abstract (ZH)**: 本文描述了一种尝试使用二元分类器的集成来解决医学语音评估问题的尝试。基于音节发音质量的定量评估和专家评估构建了一个数据集。使用了7个选定指标的定量评估作为特征：动态时间波动距离（Dynamic Time Warping Distance, DTW）、Minkowski距离、相关系数、最长公共子序列（Longest Common Subsequence, LCSS）、实际序列编辑距离（Edit Distance on Real Sequence, EDR）、带实际惩罚的编辑距离（Edit Distance with Real Penalty, ERP）和合并分裂（Merge Split, MS）。专家对发音质量的评估被用作分类标签：1表示高质量语音，0表示失真语音。对五种分类方法——逻辑回归（Logistic Regression, LR）、支持向量机（Support Vector Machine, SVM）、朴素贝叶斯（Naive Bayes, NB）、决策树（Decision Trees, DT）和K最近邻算法（K-Nearest Neighbors, KNN）进行了训练结果的比较。还展示了使用混合方法构建分类器集成的结果。对于研究的数据集，使用集成比单独使用二元分类器更能略微提高分类精度。 

---
# On Adversarial Robustness of Language Models in Transfer Learning 

**Title (ZH)**: 语言模型在迁移学习中的对抗robust性研究 

**Authors**: Bohdan Turbal, Anastasiia Mazur, Jiaxu Zhao, Mykola Pechenizkiy  

**Link**: [PDF](https://arxiv.org/pdf/2501.00066)  

**Abstract**: We investigate the adversarial robustness of LLMs in transfer learning scenarios. Through comprehensive experiments on multiple datasets (MBIB Hate Speech, MBIB Political Bias, MBIB Gender Bias) and various model architectures (BERT, RoBERTa, GPT-2, Gemma, Phi), we reveal that transfer learning, while improving standard performance metrics, often leads to increased vulnerability to adversarial attacks. Our findings demonstrate that larger models exhibit greater resilience to this phenomenon, suggesting a complex interplay between model size, architecture, and adaptation methods. Our work highlights the crucial need for considering adversarial robustness in transfer learning scenarios and provides insights into maintaining model security without compromising performance. These findings have significant implications for the development and deployment of LLMs in real-world applications where both performance and robustness are paramount. 

**Abstract (ZH)**: 我们研究了在迁移学习场景中大语言模型（LLMs）对对抗攻击的鲁棒性。通过在多个数据集（MBIB仇恨言论、MBIB政治偏见、MBIB性别偏见）和各种模型架构（BERT、RoBERTa、GPT-2、Gemma、Phi）上进行综合实验，我们发现，尽管迁移学习能够改进标准性能指标，但往往会增加模型对对抗攻击的易感性。研究结果表明，较大的模型在这一现象面前表现出了更高的鲁棒性，这暗示了模型大小、架构和适应方法之间的复杂交互作用。我们的研究强调了在迁移学习场景中考虑对抗鲁棒性的重要性，并提供了确保模型安全性和性能的平衡的见解。这些发现对在实际应用中同时考虑性能和鲁棒性强大的大语言模型的开发和部署具有重要意义。 

---
# Predicting Preschoolers' Externalizing Problems with Mother-Child Interaction Dynamics and Deep Learning 

**Title (ZH)**: 使用母子互动动力学和深度学习预测学龄前儿童的外部问题行为 

**Authors**: Xi Chen, Yu Ji, Cong Xia, Wen Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00065)  

**Abstract**: Objective: Predicting children's future levels of externalizing problems helps to identify children at risk and guide targeted prevention. Existing studies have shown that mothers providing support in response to children's dysregulation was associated with children's lower levels of externalizing problems. The current study aims to evaluate and improve the accuracy of predicting children's externalizing problems with mother-child interaction dynamics. Method: This study used mother-child interaction dynamics during a challenging puzzle task to predict children's externalizing problems six months later (N=101, 46 boys, Mage=57.41 months, SD=6.58). Performance of the Residual Dynamic Structural Equation Model (RDSEM) was compared with the Attention-based Sequential Behavior Interaction Modeling (ASBIM) model, developed using the deep learning techniques. Results: The RDSEM revealed that children whose mothers provided more autonomy support after increases of child defeat had lower levels of externalizing problems. Five-fold cross-validation showed that the RDSEM had good prediction accuracy. The ASBIM model further improved prediction accuracy, especially after including child inhibitory control as a personalized individual feature. Conclusions: The dynamic process of mother-child interaction provides important information for predicting children's externalizing problems, especially maternal autonomy supportive response to child defeat. The deep learning model is a useful tool to further improve prediction accuracy. 

**Abstract (ZH)**: 目标：预测儿童未来外显问题水平有助于识别高风险儿童并指导针对性的预防措施。现有研究表明，母亲在孩子出现调节障碍时提供支持与儿童较低的外显问题水平有关。本研究旨在评估和提高使用母子互动动态来预测儿童外显问题的准确性。

方法：本研究使用了一场挑战性拼图任务中的母子互动动态来预测六个月后的儿童外显问题（样本量：101名儿童，其中46名为男孩，平均年龄：57.41个月，标准差：6.58）。研究比较了残差动态结构方程模型（RDSEM）和基于深度学习技术开发的行为互动模型（ASBIM）的性能。

结果：RDSEM 表明，在孩子遭受失败增加后提供更高程度自主支持的母亲所对应的儿童外显问题水平较低。五折交叉验证显示，RDSEM 具有良好的预测准确性。ASBIM 模型进一步提高了预测准确性，特别是在纳入儿童抑制控制作为个性化个体特征后。

结论：母子互动的动态过程为预测儿童外显问题提供了重要信息，尤其是在母亲对儿童失败的自主支持反应方面。深度学习模型是一个有用的工具，可以进一步提高预测准确性。 

---
# "Generative Models for Financial Time Series Data: Enhancing Signal-to-Noise Ratio and Addressing Data Scarcity in A-Share Market 

**Title (ZH)**: 生成模型在金融时间序列数据中的应用：提升信噪比并解决A股市场数据稀缺问题 

**Authors**: Guangming Che  

**Link**: [PDF](https://arxiv.org/pdf/2501.00063)  

**Abstract**: The financial industry is increasingly seeking robust methods to address the challenges posed by data scarcity and low signal-to-noise ratios, which limit the application of deep learning techniques in stock market analysis. This paper presents two innovative generative model-based approaches to synthesize stock data, specifically tailored for different scenarios within the A-share market in China. The first method, a sector-based synthesis approach, enhances the signal-to-noise ratio of stock data by classifying the characteristics of stocks from various sectors in China's A-share market. This method employs an Approximate Non-Local Total Variation algorithm to smooth the generated data, a bandpass filtering method based on Fourier Transform to eliminate noise, and Denoising Diffusion Implicit Models to accelerate sampling speed. The second method, a recursive stock data synthesis approach based on pattern recognition, is designed to synthesize data for stocks with short listing periods and limited comparable companies. It leverages pattern recognition techniques and Markov models to learn and generate variable-length stock sequences, while introducing a sub-time-level data augmentation method to alleviate data scarcity this http URL validate the effectiveness of these methods through extensive experiments on various datasets, including those from the main board, STAR Market, Growth Enterprise Market Board, Beijing Stock Exchange, NASDAQ, NYSE, and AMEX. The results demonstrate that our synthesized data not only improve the performance of predictive models but also enhance the signal-to-noise ratio of individual stock signals in price trading strategies. Furthermore, the introduction of sub-time-level data significantly improves the quality of synthesized data. 

**Abstract (ZH)**: 金融行业愈加寻找强大的方法以应对数据稀缺和低信噪比带来的挑战，这些挑战限制了深度学习技术在股票市场分析中的应用。本文提出了两种创新的生成模型方法，专门用于中国A股市场中不同的场景，以合成股票数据。第一种方法基于行业领域的合成方法，通过分类中国A股市场不同行业股票的特征来提升数据的信噪比。该方法利用近似非局部分数量子总变分算法（Approximate Non-Local Total Variation algorithm）对生成的数据进行平滑处理，利用傅里叶变换基础上的带通滤波方法消除噪声，并采用降噪扩散隐式模型（Denoising Diffusion Implicit Models）加速采样速度。第二种方法基于模式识别的递归股票数据合成方法，专门针对上市时间短和可比公司有限的情况进行数据合成。该方法结合了模式识别技术和马尔科夫模型来学习并生成变长的股票序列，并引入了子时间级别数据增强方法以缓解数据稀缺问题。本文通过在包括主板、科创板、创业板、北京证券交易所、纳斯达克、纽交所和AMEX等不同数据集上进行广泛的实验，验证了这些方法的有效性。结果表明，我们合成的数据不仅提高了预测模型的性能，还提升了单个股票信号在价格交易策略中的信噪比。此外，引入子时间级别数据显著提升了合成数据的质量。 

---
# ELECTRA and GPT-4o: Cost-Effective Partners for Sentiment Analysis 

**Title (ZH)**: ELECTRA 和 GPT-4o：性价比高的情感分析合作伙伴 

**Authors**: James P. Beno  

**Link**: [PDF](https://arxiv.org/pdf/2501.00062)  

**Abstract**: Bidirectional transformers excel at sentiment analysis, and Large Language Models (LLM) are effective zero-shot learners. Might they perform better as a team? This paper explores collaborative approaches between ELECTRA and GPT-4o for three-way sentiment classification. We fine-tuned (FT) four models (ELECTRA Base/Large, GPT-4o/4o-mini) using a mix of reviews from Stanford Sentiment Treebank (SST) and DynaSent. We provided input from ELECTRA to GPT as: predicted label, probabilities, and retrieved examples. Sharing ELECTRA Base FT predictions with GPT-4o-mini significantly improved performance over either model alone (82.74 macro F1 vs. 79.29 ELECTRA Base FT, 79.52 GPT-4o-mini) and yielded the lowest cost/performance ratio (\$0.12/F1 point). However, when GPT models were fine-tuned, including predictions decreased performance. GPT-4o FT-M was the top performer (86.99), with GPT-4o-mini FT close behind (86.77) at much less cost (\$0.38 vs. \$1.59/F1 point). Our results show that augmenting prompts with predictions from fine-tuned encoders is an efficient way to boost performance, and a fine-tuned GPT-4o-mini is nearly as good as GPT-4o FT at 76% less cost. Both are affordable options for projects with limited resources. 

**Abstract (ZH)**: 双向变换器在情感分析方面表现出色，而大规模语言模型（LLM）在零样本学习方面效果显著。它们能否作为团队表现更好？本文探讨了ELECTRA和GPT-4o在三类情感分类中的协作方法。我们使用斯坦福情感树库（SST）和DynaSent的混合评论对四种模型（ELECTRA Base/Large，GPT-4o/4o-mini）进行了微调。我们将ELECTRA的输入提供给GPT：预测标签、概率和检索到的示例。将ELECTRA Base的微调预测与GPT-4o-mini共享显著提高了性能（宏F1得分为82.74，而单独的ELECTRA Base微调得分为79.29，GPT-4o-mini的得分为79.52），并实现了最低的成本/性能比（每F1得分0.12美元）。然而，当对GPT模型进行微调时，包含预测反而降低了性能。微调后的GPT-4o FT-M表现最佳（得分为86.99），GPT-4o-mini的微调紧随其后（得分为86.77），但成本更低（每F1得分0.38美元，相比之下，GPT-4o FT的成本为1.59美元）。我们的结果显示，通过向提示添加微调编码器的预测可以高效地提升性能，微调后的GPT-4o-mini在成本降低76%的情况下几乎与GPT-4o FT表现相当。两者都是资源有限项目中成本效益较高的选项。 

---
# Training-free Heterogeneous Model Merging 

**Title (ZH)**: 无训练的异构模型融合 

**Authors**: Zhengqi Xu, Han Zheng, Jie Song, Li Sun, Mingli Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.00061)  

**Abstract**: Model merging has attracted significant attention as a powerful paradigm for model reuse, facilitating the integration of task-specific models into a singular, versatile framework endowed with multifarious capabilities. Previous studies, predominantly utilizing methods such as Weight Average (WA), have shown that model merging can effectively leverage pretrained models without the need for laborious retraining. However, the inherent heterogeneity among models poses a substantial constraint on its applicability, particularly when confronted with discrepancies in model architectures. To overcome this challenge, we propose an innovative model merging framework designed for heterogeneous models, encompassing both depth and width heterogeneity. To address depth heterogeneity, we introduce a layer alignment strategy that harmonizes model layers by segmenting deeper models, treating consecutive layers with similar representations as a cohesive segment, thus enabling the seamless merging of models with differing layer depths. For width heterogeneity, we propose a novel elastic neuron zipping algorithm that projects the weights from models of varying widths onto a common dimensional space, eliminating the need for identical widths. Extensive experiments validate the efficacy of these proposed methods, demonstrating that the merging of structurally heterogeneous models can achieve performance levels comparable to those of homogeneous merging, across both vision and NLP tasks. Our code is publicly available at this https URL. 

**Abstract (ZH)**: 模型合并近年来引起了广泛关注，作为一种强大的模型复用范式，它能够将特定任务的模型整合到一个具备多种功能的多功能框架中。先前的研究主要利用加权平均（WA）等方法，表明模型合并可以通过无需繁重的重新训练，有效地利用预训练模型。然而，模型之间的固有异质性对其应用构成了重大限制，尤其是在面对模型架构差异时。为克服这一挑战，我们提出了一种专为异构模型设计的创新模型合并框架，涵盖深度和宽度的异质性。为解决深度异质性问题，我们引入了一种层对齐策略，通过对深层模型进行分段处理，将具有类似表示的连续层视为一个统一的段，从而实现具有不同层深度的模型的无缝合并。为解决宽度异质性问题，我们提出了一种新颖的弹性神经元打包算法，将不同宽度模型的权重投影到同一维度空间，从而无需拥有相同宽度。广泛的实验验证了这些提出方法的有效性，表明结构异构模型的合并可以在视觉和自然语言处理（NLP）任务中达到与同构合并相当的性能水平。我们的代码已在以下网址公开：[请插入网址]。 

---
# Large Language Models for Mathematical Analysis 

**Title (ZH)**: 大规模语言模型在数学分析中的应用 

**Authors**: Ziye Chen, Hao Qi  

**Link**: [PDF](https://arxiv.org/pdf/2501.00059)  

**Abstract**: Mathematical problem-solving is a key field in artificial intelligence (AI) and a critical benchmark for evaluating the capabilities of large language models (LLMs). While extensive research has focused on mathematical problem-solving, most existing work and datasets concentrate on computational tasks, leaving gaps in areas like mathematical analysis, which demands rigorous proofs and formal reasoning. We developed the DEMI-MathAnalysis dataset, comprising proof-based problems from mathematical analysis topics such as Sequences and Limits, Infinite Series, and Convex Functions. We also designed a guiding framework to rigorously enhance LLMs' ability to solve these problems. Through fine-tuning LLMs on this dataset and employing our framework, we observed significant improvements in their capability to generate logical, complete, and elegant proofs. This work addresses critical gaps in mathematical reasoning and contributes to advancing trustworthy AI capable of handling formalized mathematical language. The code is publicly accessible at LLMs for Mathematical Analysis. 

**Abstract (ZH)**: 数学问题求解是人工智能（AI）中的一个关键领域，也是评估大型语言模型（LLMs）能力的重要基准。尽管大量研究集中在数学问题求解上，但现有工作和数据集大多集中在计算任务上，而在需要严谨证明和形式推理的数学分析领域存在空白。为此，我们开发了DEMI-MathAnalysis数据集，该数据集包含源自数学分析主题的问题，如数列和极限、无穷级数以及凸函数的基于证明的问题。我们还设计了一套指导框架，以严谨地提升LLMs解决这些问题的能力。通过在该数据集上对LLMs进行微调并使用我们的框架，我们观察到它们生成逻辑严密、完整且精美的证明的能力有了显著提升。这项工作填补了数学推理中的关键空白，并有助于推进能够处理形式化数学语言的可信AI的发展。相关代码已在LLMs for Mathematical Analysis中公开。 

---
# VisTabNet: Adapting Vision Transformers for Tabular Data 

**Title (ZH)**: VisTabNet: 将视觉变压器应用于表格数据 

**Authors**: Witold Wydmański, Ulvi Movsum-zada, Jacek Tabor, Marek Śmieja  

**Link**: [PDF](https://arxiv.org/pdf/2501.00057)  

**Abstract**: Although deep learning models have had great success in natural language processing and computer vision, we do not observe comparable improvements in the case of tabular data, which is still the most common data type used in biological, industrial and financial applications. In particular, it is challenging to transfer large-scale pre-trained models to downstream tasks defined on small tabular datasets. To address this, we propose VisTabNet -- a cross-modal transfer learning method, which allows for adapting Vision Transformer (ViT) with pre-trained weights to process tabular data. By projecting tabular inputs to patch embeddings acceptable by ViT, we can directly apply a pre-trained Transformer Encoder to tabular inputs. This approach eliminates the conceptual cost of designing a suitable architecture for processing tabular data, while reducing the computational cost of training the model from scratch. Experimental results on multiple small tabular datasets (less than 1k samples) demonstrate VisTabNet's superiority, outperforming both traditional ensemble methods and recent deep learning models. The proposed method goes beyond conventional transfer learning practice and shows that pre-trained image models can be transferred to solve tabular problems, extending the boundaries of transfer learning. 

**Abstract (ZH)**: 尽管深度学习模型在自然语言处理和计算机视觉领域取得了巨大成功，但在表格数据领域并未观察到类似的改进，而表格数据依然是生物、工业和金融应用中最常见的数据类型。特别是，将大规模预训练模型迁移应用到基于小型表格数据集的下游任务中存在很大挑战。为了解决这一问题，我们提出了VisTabNet——一种跨模态迁移学习方法，该方法允许使用预训练权重的视觉变换器（ViT）对表格数据进行处理。通过将表格输入投影为可接受的ViT补丁嵌入，可以直接将预训练的Transformer编码器应用于表格输入。这种方法消除了为处理表格数据设计合适架构的概念性成本，同时减少了从头开始训练模型的计算成本。实验结果表明，VisTabNet在多个小型表格数据集（样本数小于1000）上优于传统集成方法和最近的深度学习模型。所提出的方法突破了传统的迁移学习实践，展示了预训练图像模型可以迁移解决表格问题的能力，拓展了迁移学习的边界。 

---
# Transforming CCTV cameras into NO$_2$ sensors at city scale for adaptive policymaking 

**Title (ZH)**: 将城市规模的监控摄像头转变为NO₂传感器以实现适应性政策制定 

**Authors**: Mohamed R. Ibrahim, Terry Lyons  

**Link**: [PDF](https://arxiv.org/pdf/2501.00056)  

**Abstract**: Air pollution in cities, especially NO\textsubscript{2}, is linked to numerous health problems, ranging from mortality to mental health challenges and attention deficits in children. While cities globally have initiated policies to curtail emissions, real-time monitoring remains challenging due to limited environmental sensors and their inconsistent distribution. This gap hinders the creation of adaptive urban policies that respond to the sequence of events and daily activities affecting pollution in cities. Here, we demonstrate how city CCTV cameras can act as a pseudo-NO\textsubscript{2} sensors. Using a predictive graph deep model, we utilised traffic flow from London's cameras in addition to environmental and spatial factors, generating NO\textsubscript{2} predictions from over 133 million frames. Our analysis of London's mobility patterns unveiled critical spatiotemporal connections, showing how specific traffic patterns affect NO\textsubscript{2} levels, sometimes with temporal lags of up to 6 hours. For instance, if trucks only drive at night, their effects on NO\textsubscript{2} levels are most likely to be seen in the morning when people commute. These findings cast doubt on the efficacy of some of the urban policies currently being implemented to reduce pollution. By leveraging existing camera infrastructure and our introduced methods, city planners and policymakers could cost-effectively monitor and mitigate the impact of NO\textsubscript{2} and other pollutants. 

**Abstract (ZH)**: 城市中的空气污染，尤其是二氧化氮（NO₂），与多种健康问题相关，从死亡率增加到心理健康问题和儿童的注意力缺陷。尽管全球城市已启动相关政策以减少排放，但由于环境传感器数量有限且分布不均，实时监测仍然具有挑战性。这一缺口阻碍了制定能够应对影响城市污染事件序列和日常活动的适应性城市政策。在此，我们展示了城市监控摄像头如何作为伪NO₂传感器的应用。利用预测图深学习模型，我们利用伦敦摄像头的交通流量数据以及环境和空间因素，从超过1.33亿帧中生成NO₂预测数据。通过分析伦敦的出行模式，我们发现关键的空间-时间联系，展示了特定交通模式如何影响NO₂水平，有时滞后时间长达6小时。例如，如果卡车只在夜间行驶，它们对NO₂水平的影响最可能在早晨人们通勤时显现出来。这些发现对当前用于减少污染的部分城市政策的有效性提出了质疑。通过利用现有的摄像头基础设施和我们提出的方法，城市规划者和政策制定者可以以成本效益的方式监测和减轻NO₂和其他污染物的影响。 

---
# LLM-Virus: Evolutionary Jailbreak Attack on Large Language Models 

**Title (ZH)**: LLM-Virus：大型语言模型的演化型突破攻击 

**Authors**: Miao Yu, Junfeng Fang, Yingjie Zhou, Xing Fan, Kun Wang, Shirui Pan, Qingsong Wen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00055)  

**Abstract**: While safety-aligned large language models (LLMs) are increasingly used as the cornerstone for powerful systems such as multi-agent frameworks to solve complex real-world problems, they still suffer from potential adversarial queries, such as jailbreak attacks, which attempt to induce harmful content. Researching attack methods allows us to better understand the limitations of LLM and make trade-offs between helpfulness and safety. However, existing jailbreak attacks are primarily based on opaque optimization techniques (e.g. token-level gradient descent) and heuristic search methods like LLM refinement, which fall short in terms of transparency, transferability, and computational cost. In light of these limitations, we draw inspiration from the evolution and infection processes of biological viruses and propose LLM-Virus, a jailbreak attack method based on evolutionary algorithm, termed evolutionary jailbreak. LLM-Virus treats jailbreak attacks as both an evolutionary and transfer learning problem, utilizing LLMs as heuristic evolutionary operators to ensure high attack efficiency, transferability, and low time cost. Our experimental results on multiple safety benchmarks show that LLM-Virus achieves competitive or even superior performance compared to existing attack methods. 

**Abstract (ZH)**: 尽管安全对齐的大语言模型（LLMs）在诸如多智能体框架等强大系统中被越来越广泛地用作基础支柱，以解决复杂的现实世界问题，但它们仍然面临潜在的对抗查询，例如脱逃攻击（jailbreak attacks），这些攻击试图诱导有害内容。研究攻击方法有助于我们更好地了解LLM的局限性，并在帮助性和安全性之间做出权衡。然而，现有的脱逃攻击主要基于不透明的优化技术（例如，标记级梯度下降）和启发式搜索方法（如LLM优化），这些方法在透明性、转移性和计算成本方面存在不足。鉴于这些局限性，我们从生物病毒的进化和感染过程中汲取灵感，提出了一种基于进化算法的脱逃攻击方法，称为进化脱逃（evolutionary jailbreak）。LLM-Virus将脱逃攻击视为一种进化和迁移学习问题，利用LLM作为启发式的进化操作符，以确保高攻击效率、良好的转移性和低时间成本。我们在多个安全基准上的实验结果表明，LLM-Virus在性能上具有竞争力，甚至优于现有的攻击方法。 

---
# AdvAnchor: Enhancing Diffusion Model Unlearning with Adversarial Anchors 

**Title (ZH)**: AdvAnchor：通过对抗锚点增强扩散模型的遗忘能力 

**Authors**: Mengnan Zhao, Lihe Zhang, Xingyi Yang, Tianhang Zheng, Baocai Yin  

**Link**: [PDF](https://arxiv.org/pdf/2501.00054)  

**Abstract**: Security concerns surrounding text-to-image diffusion models have driven researchers to unlearn inappropriate concepts through fine-tuning. Recent fine-tuning methods typically align the prediction distributions of unsafe prompts with those of predefined text anchors. However, these techniques exhibit a considerable performance trade-off between eliminating undesirable concepts and preserving other concepts. In this paper, we systematically analyze the impact of diverse text anchors on unlearning performance. Guided by this analysis, we propose AdvAnchor, a novel approach that generates adversarial anchors to alleviate the trade-off issue. These adversarial anchors are crafted to closely resemble the embeddings of undesirable concepts to maintain overall model performance, while selectively excluding defining attributes of these concepts for effective erasure. Extensive experiments demonstrate that AdvAnchor outperforms state-of-the-art methods. Our code is publicly available at this https URL. 

**Abstract (ZH)**: 文本到图像的扩散模型存在安全顾虑，促使研究人员通过微调重新学习，消除不恰当的概念。最近的微调方法通常通过与预定义的文本锚点对齐不安全提示的预测分布来实现这一目标。然而，这些技术在消除不希望出现的概念与保留其他概念之间表现出显著的性能折衷。在这篇论文中，我们系统地分析了不同文本锚点对重新学习性能的影响。基于这种分析，我们提出了一种名为AdvAnchor的新方法，该方法生成对抗性锚点以缓解这一折衷问题。这些对抗性锚点被设计为与不希望出现的概念的嵌入高度相似，以维持整体模型性能，同时选择性地排除这些概念的定义属性，从而实现有效的消除。广泛的实验表明，AdvAnchor 在性能上优于现有的最先进技术。我们的代码已在以下网址公开提供：[在这里插入网址]。 

---
# Implementing Trust in Non-Small Cell Lung Cancer Diagnosis with a Conformalized Uncertainty-Aware AI Framework in Whole-Slide Images 

**Title (ZH)**: 在整张切片图像中，基于一致化不确定性感知AI框架实现非小细胞肺癌诊断中的信任机制 

**Authors**: Xiaoge Zhang, Tao Wang, Chao Yan, Fedaa Najdawi, Kai Zhou, Yuan Ma, Yiu-ming Cheung, Bradley A. Malin  

**Link**: [PDF](https://arxiv.org/pdf/2501.00053)  

**Abstract**: Ensuring trustworthiness is fundamental to the development of artificial intelligence (AI) that is considered societally responsible, particularly in cancer diagnostics, where a misdiagnosis can have dire consequences. Current digital pathology AI models lack systematic solutions to address trustworthiness concerns arising from model limitations and data discrepancies between model deployment and development environments. To address this issue, we developed TRUECAM, a framework designed to ensure both data and model trustworthiness in non-small cell lung cancer subtyping with whole-slide images. TRUECAM integrates 1) a spectral-normalized neural Gaussian process for identifying out-of-scope inputs and 2) an ambiguity-guided elimination of tiles to filter out highly ambiguous regions, addressing data trustworthiness, as well as 3) conformal prediction to ensure controlled error rates. We systematically evaluated the framework across multiple large-scale cancer datasets, leveraging both task-specific and foundation models, illustrate that an AI model wrapped with TRUECAM significantly outperforms models that lack such guidance, in terms of classification accuracy, robustness, interpretability, and data efficiency, while also achieving improvements in fairness. These findings highlight TRUECAM as a versatile wrapper framework for digital pathology AI models with diverse architectural designs, promoting their responsible and effective applications in real-world settings. 

**Abstract (ZH)**: 确保可信度是实现社会负责的人工智能（AI）开发的基础，特别是在癌症诊断中尤为重要。一个误诊可能会带来严重的后果。当前的数字病理AI模型缺乏系统性方案来解决模型部署环境与开发环境间数据差异以及模型限制所引起的可信度问题。为解决这一问题，我们开发了TRUECAM框架，旨在使用整个切片图像进行非小细胞肺癌亚型分类时确保数据和模型的可信度。TRUECAM融合了以下三个关键技术：1）光谱归一化神经高斯过程，用于识别超出范围的输入；2）基于模糊性引导的瓷砖剔除方法，以过滤掉高度模糊的区域，从而解决数据可信度问题；以及3）符合性预测，以确保可控的错误率。我们系统地在多个大规模癌症数据集上评估了该框架，利用特定任务模型和基础模型，展现了TRUECAM包裹的AI模型在分类准确性、鲁棒性、可解释性和数据效率方面显著优于缺乏此类指导的模型，同时也在公平性方面有所改进。这些发现突显了TRUECAM作为不同架构设计的数字病理AI模型的多功能性包裹框架的重要性，促进了其在实际应用场景中的负责任和有效应用。 

---
# DDD-GenDT: Dynamic Data-driven Generative Digital Twin Framework 

**Title (ZH)**: DDD-GenDT：动态数据驱动的生成型数字孪生框架 

**Authors**: Yu-Zheng Lin, Qinxuan Shi, Zhanglong Yang, Banafsheh Saber Latibari, Sicong Shao, Soheil Salehi, Pratik Satam  

**Link**: [PDF](https://arxiv.org/pdf/2501.00051)  

**Abstract**: Digital twin (DT) technology has emerged as a transformative approach to simulate, predict, and optimize the behavior of physical systems, with applications that span manufacturing, healthcare, climate science, and more. However, the development of DT models often faces challenges such as high data requirements, integration complexity, and limited adaptability to dynamic changes in physical systems. This paper presents a new method inspired by dynamic data-driven applications systems (DDDAS), called the dynamic data-driven generative of digital twins framework (DDD-GenDT), which combines the physical system with LLM, allowing LLM to act as DT to interact with the physical system operating status and generate the corresponding physical behaviors. We apply DDD-GenDT to the computer numerical control (CNC) machining process, and we use the spindle current measurement data in the NASA milling wear data set as an example to enable LLMs to forecast the physical behavior from historical data and interact with current observations. Experimental results show that in the zero-shot prediction setting, the LLM-based DT can adapt to the change in the system, and the average RMSE of the GPT-4 prediction is 0.479A, which is 4.79% of the maximum spindle motor current measurement of 10A, with little training data and instructions required. Furthermore, we analyze the performance of DDD-GenDT in this specific application and their potential to construct digital twins. We also discuss the limitations and challenges that may arise in practical implementations. 

**Abstract (ZH)**: 数字孪生（Digital Twin, DT）技术作为一种变革性的方法，用于模拟、预测和优化物理系统的行为，其应用领域涵盖了制造、医疗、气候变化等众多方面。然而，DT 模型的开发常常面临高数据需求、集成复杂性和对物理系统动态变化的适应性有限等挑战。本文提出了一种受动态数据驱动应用系统（Dynamic Data-Driven Applications Systems, DDDAS）启发的新方法，称为动态数据驱动生成数字孪生框架（Dynamic Data-Driven Generative of Digital Twins, DDD-GenDT），该方法将物理系统与大型语言模型（LLM）结合，使得 LLM 能够充当数字孪生，与物理系统运行状态互动并生成相应的物理行为。我们将 DDD-GenDT 应用于计算机数控（CNC）加工过程，并使用NASA铣削磨损数据集中主轴电流测量数据作为示例，使 LLM 能够从历史数据中预测物理行为并与当前观测互动。实验结果表明，在零样本预测设置下，基于LLM的数字孪生能够适应系统的变化，GPT-4 的预测平均绝对均方根误差（RMSE）为0.479A，占最大主轴电机电流测量值10A的4.79%，且所需训练数据和指令较少。此外，我们分析了该特定应用中DDD-GenDT的效果及其构建数字孪生的潜力，并讨论了实际实施中可能出现的限制和挑战。 

---
# Stroke Prediction using Clinical and Social Features in Machine Learning 

**Title (ZH)**: 使用临床和社会特征进行中风预测的研究 

**Authors**: Aidan Chadha  

**Link**: [PDF](https://arxiv.org/pdf/2501.00048)  

**Abstract**: Every year in the United States, 800,000 individuals suffer a stroke - one person every 40 seconds, with a death occurring every four minutes. While individual factors vary, certain predictors are more prevalent in determining stroke risk. As strokes are the second leading cause of death and disability worldwide, predicting stroke likelihood based on lifestyle factors is crucial. Showing individuals their stroke risk could motivate lifestyle changes, and machine learning offers solutions to this prediction challenge. Neural networks excel at predicting outcomes based on training features like lifestyle factors, however, they're not the only option. Logistic regression models can also effectively compute the likelihood of binary outcomes based on independent variables, making them well-suited for stroke prediction. This analysis will compare both neural networks (dense and convolutional) and logistic regression models for stroke prediction, examining their pros, cons, and differences to develop the most effective predictor that minimizes false negatives. 

**Abstract (ZH)**: 每年在美国，有800,000人遭受中风的侵袭，平均每40秒就有1人发病，每4分钟就有1人因此死亡。虽然个体因素各不相同，但某些预测因素在确定中风风险方面更为普遍。由于中风是全球第二大致死和致残原因，基于生活方式因素预测中风的可能性至关重要。向个体展示其中风风险可能会激励他们进行生活方式的改变，而机器学习为这一预测挑战提供了解决方案。神经网络在基于训练特征（如生活方式因素）预测结果方面表现出色，但并非唯一的选择。逻辑回归模型也可以有效计算基于独立变量的二元结果的概率，使其非常适合用于中风预测。本分析将比较神经网络（包括密集型和卷积型）和逻辑回归模型在中风预测中的应用，探讨它们各自的优缺点和差异，以开发出最有效的预测模型，最大限度地减少假阴性结果。 

---
# Resource-Efficient Transformer Architecture: Optimizing Memory and Execution Time for Real-Time Applications 

**Title (ZH)**: 高效资源Transformer架构：针对实时应用优化内存和执行时间 

**Authors**: Krisvarish V, Priyadarshini T, K P Abhishek Sri Saai, Vaidehi Vijayakumar  

**Link**: [PDF](https://arxiv.org/pdf/2501.00042)  

**Abstract**: This paper describes a memory-efficient transformer model designed to drive a reduction in memory usage and execution time by substantial orders of magnitude without impairing the model's performance near that of the original model. Recently, new architectures of transformers were presented, focused on parameter efficiency and computational optimization; however, such models usually require considerable resources in terms of hardware when deployed in real-world applications on edge devices. This approach addresses this concern by halving embedding size and applying targeted techniques such as parameter pruning and quantization to optimize the memory footprint with minimum sacrifices in terms of accuracy. Experimental results include a 52% reduction in memory usage and a 33% decrease in execution time, resulting in better efficiency than state-of-the-art models. This work compared our model with existing compelling architectures, such as MobileBERT and DistilBERT, and proved its feasibility in the domain of resource-friendly deep learning architectures, mainly for applications in real-time and in resource-constrained applications. 

**Abstract (ZH)**: 本文描述了一种内存高效的Transformer模型，该模型旨在通过大幅减少内存使用和执行时间来实现这一点，同时不牺牲近似于原始模型的性能。最近，提出了一些基于Transformer的新架构，专注于参数效率和计算优化；然而，在将这些模型部署到边缘设备的实际应用场景中，通常需要大量硬件资源。本文通过减少嵌入尺寸并采用参数剪枝和量化等针对性技术，优化模型的内存占用，同时最大限度地减少准确性损失。实验结果表明，该模型的内存使用减少了52%，执行时间减少了33%，其效率优于现有的先进模型。本文还对比了我们的模型与现有具有竞争力的架构，如MobileBERT和DistilBERT，并证明了其在资源友好型深度学习架构中的可行性，特别是适用于实时和资源受限的应用场景。 

---
# Time Series Feature Redundancy Paradox: An Empirical Study Based on Mortgage Default Prediction 

**Title (ZH)**: 时间序列特征冗余悖论：基于房贷违约预测的经验研究 

**Authors**: Chengyue Huang, Yahe Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00034)  

**Abstract**: With the widespread application of machine learning in financial risk management, conventional wisdom suggests that longer training periods and more feature variables contribute to improved model performance. This paper, focusing on mortgage default prediction, empirically discovers a phenomenon that contradicts traditional knowledge: in time series prediction, increased training data timespan and additional non-critical features actually lead to significant deterioration in prediction effectiveness. Using Fannie Mae's mortgage data, the study compares predictive performance across different time window lengths (2012-2022) and feature combinations, revealing that shorter time windows (such as single-year periods) paired with carefully selected key features yield superior prediction results. The experimental results indicate that extended time spans may introduce noise from historical data and outdated market patterns, while excessive non-critical features interfere with the model's learning of core default factors. This research not only challenges the traditional "more is better" approach in data modeling but also provides new insights and practical guidance for feature selection and time window optimization in financial risk prediction. 

**Abstract (ZH)**: 随着机器学习在金融风险管理中的广泛应用，人们普遍认为更长的训练时间和更多的特征变量会提高模型性能。本文以住房抵押贷款违约预测为例，实证发现了一个与传统知识相悖的现象：在时间序列预测中，增加训练数据的时间跨度和添加不重要的特征实际上会导致预测效果显著下降。利用房地美（Fannie Mae）的抵押贷款数据，本研究比较了不同时间窗口长度（2012-2022）和特征组合下的预测性能，结果显示，较短的时间窗口（如单年度时期）与精心选择的关键特征相结合，可以获得更好的预测结果。实验结果表明，延长的时间跨度可能会引入历史数据中的噪音和过时的市场模式，而过多的不重要特征会干扰模型对核心违约因素的学习。这项研究不仅挑战了数据建模中传统的“多多益善”的观点，还为金融风险预测中的特征选择和时间窗口优化提供了新的见解和实战建议。 

---
# Highly Optimized Kernels and Fine-Grained Codebooks for LLM Inference on Arm CPUs 

**Title (ZH)**: 针对Arm CPU的高优化内核和细粒度代码簿用于大规模语言模型推理 

**Authors**: Dibakar Gope, David Mansell, Danny Loh, Ian Bratt  

**Link**: [PDF](https://arxiv.org/pdf/2501.00032)  

**Abstract**: Large language models (LLMs) have transformed the way we think about language understanding and generation, enthralling both researchers and developers. However, deploying LLMs for inference has been a significant challenge due to their unprecedented size and resource requirements. While quantizing model weights to sub-byte precision has emerged as a promising solution to ease memory pressure, the group quantization formats commonly used for LLM quantization have significant compute overheads and a resource-intensive dequantization process. As a result, a higher proportion of compute instructions do not perform multiplies, i.e., real work, rendering them unsuitable for meeting the required latency requirements for LLMs deployed on commodity CPUs. In this work, we propose a set of highly optimized kernels to accelerate LLM inference and unleash the full potential of CPUs, particularly Arm CPUs. These kernels amortize the cost of loading the operands and the cost of weight unpacking across multiple output rows. This, along with the introduction of an optimized interleaved group data layout for weights and decompression path optimizations to reduce unnecessary operations and dequantization overhead while maximizing the use of vector and matrix multiply operations, significantly improves the efficiency of MAC operations. Furthermore, we present a groupwise non-uniform codebook-based quantization method for ultra-low-precision quantization of LLMs to better match non-uniform patterns in their weight distributions, demonstrating better throughput during token generation while ensuring better quality than the state-of-the-art. Applying these improvements to 4-bit LLMs results in a 3-3.2x improvement in prompt processing and a 2x improvement in autoregressive decoding on Arm CPUs, compared to this http URL-based solution. The optimized kernels are available at this https URL. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已经彻底改变了我们对语言理解和生成的看法，引起了研究者和开发者的极大兴趣。然而，由于LLMs规模空前庞大，对资源的需求也极高，将它们部署用于推理已经成为一个重大挑战。尽管将模型权重量化到亚字节精度已成为缓解内存压力的一种有前景的解决方案，但常用的LLM量化分组格式具有显著的计算开销，并且去量化过程资源密集。因此，大量的计算指令并没有进行乘法操作，即未完成实际工作，这使得它们不适合满足在通用CPU上部署LLMs所需的延迟要求。在这项工作中，我们提出了一套高度优化的内核，以加速LLM推理并充分发挥CPU，尤其是Arm CPU的潜力。这些内核通过将操作数加载成本和权重展开成本在多行输出中摊销，提高了效率。此外，通过引入优化的交织分组权重数据布局和解压缩路径优化来减少不必要的操作和去量化开销，同时最大限度地利用向量和矩阵乘法操作，显著提高了MAC操作的效率。我们还提出了一种分组非均匀码本量化方法，用于LLM的超低精度量化，以更好地匹配权重分布中的非均匀模式，在提高生成词元吞吐量的同时，保持了更好的质量。将这些改进应用于4位LLM时，与该网址的解决方案相比，在Arm CPU上提供了3-3.2倍的提示处理改进以及2倍的自回归解码性能提升。优化后的内核可在该网址获取。 

---
# Predicting Crack Nucleation and Propagation in Brittle Materials Using Deep Operator Networks with Diverse Trunk Architectures 

**Title (ZH)**: 使用具有多样化主干架构的深度算子网络预测脆性材料中的裂纹 nucleation 和 propagation 

**Authors**: Elham Kiyani, Manav Manav, Nikhil Kadivar, Laura De Lorenzis, George Em Karniadakis  

**Link**: [PDF](https://arxiv.org/pdf/2501.00016)  

**Abstract**: Phase-field modeling reformulates fracture problems as energy minimization problems and enables a comprehensive characterization of the fracture process, including crack nucleation, propagation, merging, and branching, without relying on ad-hoc assumptions. However, the numerical solution of phase-field fracture problems is characterized by a high computational cost. To address this challenge, in this paper, we employ a deep neural operator (DeepONet) consisting of a branch network and a trunk network to solve brittle fracture problems. We explore three distinct approaches that vary in their trunk network configurations. In the first approach, we demonstrate the effectiveness of a two-step DeepONet, which results in a simplification of the learning task. In the second approach, we employ a physics-informed DeepONet, whereby the mathematical expression of the energy is integrated into the trunk network's loss to enforce physical consistency. The integration of physics also results in a substantially smaller data size needed for training. In the third approach, we replace the neural network in the trunk with a Kolmogorov-Arnold Network and train it without the physics loss. Using these methods, we model crack nucleation in a one-dimensional homogeneous bar under prescribed end displacements, as well as crack propagation and branching in single edge-notched specimens with varying notch lengths subjected to tensile and shear loading. We show that the networks predict the solution fields accurately, and the error in the predicted fields is localized near the crack. 

**Abstract (ZH)**: 相场模型将断裂问题重新表述为能量最小化问题，能够全面表征断裂过程，包括裂纹的产生、传播、合并和分支，无需依赖于任意假设。然而，相场断裂问题的数值求解具有计算成本高的特点。为应对这一挑战，本文采用一个由分枝网络和干管网络组成的深度神经算子（DeepONet）来解决脆性断裂问题。我们探讨了三种不同的方法，这些方法在干管网络配置上有所不同。在第一种方法中，我们展示了两步DeepONet的有效性，从而简化了学习任务。在第二种方法中，我们使用了一种物理信息下的DeepONet，其中能量的数学表达式被整合到干管网络的损失中，以保证物理一致性。物理信息的整合还大幅减小了训练所需的样本数据量。在第三种方法中，我们将干管网络中的神经网络替换为柯尔莫哥洛夫-阿诺尔德网络，并在无物理损失的情况下进行训练。通过这些方法，我们模拟了一维均匀杆在规定端部位移下的裂纹产生，以及不同缺口长度的单边缺口试样在拉伸和剪切载荷下的裂纹传播和分支过程。结果表明，这些网络能够准确预测解决方案场，预测的误差主要集中在裂纹附近。 

---
# Relation-Aware Equivariant Graph Networks for Epitope-Unknown Antibody Design and Specificity Optimization 

**Title (ZH)**: 基于关系的等变图网络在抗原未知抗体设计及特异性优化中的应用 

**Authors**: Lirong Wu, Haitao Lin, Yufei Huang, Zhangyang Gao, Cheng Tan, Yunfan Liu, Tailin Wu, Stan Z. Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.00013)  

**Abstract**: Antibodies are Y-shaped proteins that protect the host by binding to specific antigens, and their binding is mainly determined by the Complementary Determining Regions (CDRs) in the antibody. Despite the great progress made in CDR design, existing computational methods still encounter several challenges: 1) poor capability of modeling complex CDRs with long sequences due to insufficient contextual information; 2) conditioned on pre-given antigenic epitopes and their static interaction with the target antibody; 3) neglect of specificity during antibody optimization leads to non-specific antibodies. In this paper, we take into account a variety of node features, edge features, and edge relations to include more contextual and geometric information. We propose a novel Relation-Aware Antibody Design (RAAD) framework, which dynamically models antigen-antibody interactions for co-designing the sequences and structures of antigen-specific CDRs. Furthermore, we propose a new evaluation metric to better measure antibody specificity and develop a contrasting specificity-enhancing constraint to optimize the specificity of antibodies. Extensive experiments have demonstrated the superior capability of RAAD in terms of antibody modeling, generation, and optimization across different CDR types, sequence lengths, pre-training strategies, and input contexts. 

**Abstract (ZH)**: 抗体是Y形蛋白质，通过与特定抗原结合来保护宿主，其结合主要由抗体中的互补决定区（CDRs）决定。尽管在CDR设计方面取得了巨大进展，但现有的计算方法仍然面临几个挑战：1）因缺乏足够的上下文信息，难以建模较长序列的复杂CDRs；2）受限于预给定的抗原表位及其与靶抗体的静态相互作用；3）在抗体优化过程中忽视特异性，导致产生非特异性抗体。本文中，我们考虑了各种节点特征、边特征和边关系，以包含更多的上下文和几何信息。我们提出了一种新的aware抗体设计（RAAD）框架，该框架能够动态建模抗原-抗体相互作用，以联合设计抗表位特异性CDR的序列和结构。此外，我们提出了一种新的评估指标来更好地衡量抗体的特异性，并开发了一种对比增强特异性的约束条件，以优化抗体的特异性。广泛实验表明，RAAD在不同CDR类型、序列长度、预训练策略和输入上下文下的抗体建模、生成和优化方面表现出优越的能力。 

---
# Model-Driven Deep Neural Network for Enhanced AoA Estimation Using 5G gNB 

**Title (ZH)**: 基于模型的深度神经网络在增强5G gNB角度估计中的应用 

**Authors**: Shengheng Liu, Xingkang Li, Zihuan Mao, Peng Liu, Yongming Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00009)  

**Abstract**: High-accuracy positioning has become a fundamental enabler for intelligent connected devices. Nevertheless, the present wireless networks still rely on model-driven approaches to achieve positioning functionality, which are susceptible to performance degradation in practical scenarios, primarily due to hardware impairments. Integrating artificial intelligence into the positioning framework presents a promising solution to revolutionize the accuracy and robustness of location-based services. In this study, we address this challenge by reformulating the problem of angle-of-arrival (AoA) estimation into image reconstruction of spatial spectrum. To this end, we design a model-driven deep neural network (MoD-DNN), which can automatically calibrate the angular-dependent phase error. The proposed MoD-DNN approach employs an iterative optimization scheme between a convolutional neural network and a sparse conjugate gradient algorithm. Simulation and experimental results are presented to demonstrate the effectiveness of the proposed method in enhancing spectrum calibration and AoA estimation. 

**Abstract (ZH)**: 高精度定位已成为智能连接设备的基础支撑。然而，目前的无线网络仍依赖于模型驱动的方法来实现定位功能，这些方法在实际应用场景中容易因硬件影响而导致性能下降。将人工智能集成到定位框架中，为提高基于位置服务的准确性和鲁棒性提供了有前途的解决方案。在本研究中，我们通过将到达角（AoA）估计问题重新定义为空间频谱的图像重建问题来应对这一挑战。为此，我们设计了一个模型驱动的深度神经网络（MoD-DNN），该网络可以自动校准角度相关的相位误差。提出的MoD-DNN方法采用卷积神经网络和稀疏共轭梯度算法之间的迭代优化方案。仿真和实验结果表明，该方法在提高频谱校准和到达角估计方面具有有效性。 

---
# NewsHomepages: Homepage Layouts Capture Information Prioritization Decisions 

**Title (ZH)**: 新闻首页布局：首页布局反映信息优先级决策 

**Authors**: Ben Welsh, Naitian Zhou, Arda Kaz, Michael Vu, Alexander Spangher  

**Link**: [PDF](https://arxiv.org/pdf/2501.00004)  

**Abstract**: Information prioritization plays an important role in how humans perceive and understand the world. Homepage layouts serve as a tangible proxy for this prioritization. In this work, we present NewsHomepages, a large dataset of over 3,000 new website homepages (including local, national and topic-specific outlets) captured twice daily over a three-year period. We develop models to perform pairwise comparisons between news items to infer their relative significance. To illustrate that modeling organizational hierarchies has broader implications, we applied our models to rank-order a collection of local city council policies passed over a ten-year period in San Francisco, assessing their "newsworthiness". Our findings lay the groundwork for leveraging implicit organizational cues to deepen our understanding of information prioritization. 

**Abstract (ZH)**: 信息优先级在人类感知和理解世界的过程中起着重要作用。主页布局为此优先级提供了具体的代理。在本研究中，我们介绍了一个名为 NewsHomepages 的大型数据集，该数据集包含超过 3,000 个新闻网站的主页（包括地方、国家和特定主题的渠道），这些主页在三年间每天被采集两次。我们开发了模型来进行新闻项目的成对比较，以推断其相对重要性。为了说明建模组织层次关系具有更广泛的意义，我们将这些模型应用于按时间顺序排列旧金山十年间颁布的地方城市议会政策，评估它们的“新闻价值”。我们的研究结果为利用隐含的组织提示深化我们对信息优先级的理解奠定了基础。 

---