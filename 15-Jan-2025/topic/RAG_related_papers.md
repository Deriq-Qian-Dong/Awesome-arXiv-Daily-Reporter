# ASTRID -- An Automated and Scalable TRIaD for the Evaluation of RAG-based Clinical Question Answering Systems 

**Title (ZH)**: ASTRID —— 一种自动化且可扩展的 TRIaD，用于评估基于RAG的临床问答系统 

**Authors**: Mohita Chowdhury, Yajie Vera He, Aisling Higham, Ernest Lim  

**Link**: [PDF](https://arxiv.org/pdf/2501.08208)  

**Abstract**: Large Language Models (LLMs) have shown impressive potential in clinical question answering (QA), with Retrieval Augmented Generation (RAG) emerging as a leading approach for ensuring the factual accuracy of model responses. However, current automated RAG metrics perform poorly in clinical and conversational use cases. Using clinical human evaluations of responses is expensive, unscalable, and not conducive to the continuous iterative development of RAG systems. To address these challenges, we introduce ASTRID - an Automated and Scalable TRIaD for evaluating clinical QA systems leveraging RAG - consisting of three metrics: Context Relevance (CR), Refusal Accuracy (RA), and Conversational Faithfulness (CF). Our novel evaluation metric, CF, is designed to better capture the faithfulness of a model's response to the knowledge base without penalising conversational elements. To validate our triad, we curate a dataset of over 200 real-world patient questions posed to an LLM-based QA agent during surgical follow-up for cataract surgery - the highest volume operation in the world - augmented with clinician-selected questions for emergency, clinical, and non-clinical out-of-domain scenarios. We demonstrate that CF can predict human ratings of faithfulness better than existing definitions for conversational use cases. Furthermore, we show that evaluation using our triad consisting of CF, RA, and CR exhibits alignment with clinician assessment for inappropriate, harmful, or unhelpful responses. Finally, using nine different LLMs, we demonstrate that the three metrics can closely agree with human evaluations, highlighting the potential of these metrics for use in LLM-driven automated evaluation pipelines. We also publish the prompts and datasets for these experiments, providing valuable resources for further research and development. 

**Abstract (ZH)**: 大型语言模型（LLMs）在临床问答（QA）方面展现了令人印象深刻的潜力，检索增强生成（RAG）方法因其确保模型响应事实准确性的能力而成为领先的方法。然而，现有的自动化RAG评估指标在临床和对话场景中表现不佳。目前，使用临床人工评估响应成本高、无法扩展，也不利于RAG系统的持续迭代开发。为解决这些挑战，我们提出了一种名为ASTRID的自动化和可扩展的RAG评估框架，以评估利用RAG的临床QA系统，该框架包含三个指标：上下文相关性（CR）、拒绝准确性（RA）和对话一致性（CF）。我们提出的新型评估指标CF旨在更好地捕捉模型响应与知识库的一致性，而不惩罚对话元素。为了验证这一指标框架，我们编译了一个包含200多个真实世界患者问题的数据集，这些问题是在进行白内障手术术后随访时提出给基于LLM的QA代理的，其中还包括临床专家精选的问题，以涵盖急诊、临床和非临床领域。我们证明，CF能够比现有定义更好地预测对话场景中的人类一致性评级。此外，我们展示了使用包含CF、RA和CR的三重评估框架与临床评估的一致性，尤其是在不适当、有害或无用的响应方面。最后，我们使用九种不同的LLM进行测试，证明这三个指标与人类评估结果高度一致，突显了这些指标在基于LLM的自动评估管道中的应用潜力。我们还发布了这些实验的提示和数据集，为进一步的研究和开发提供了宝贵的资源。 

---
# Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering 

**Title (ZH)**: 恰当地与专家沟通：面向多代理系统的问答路由与规划 

**Authors**: Feijie Wu, Zitao Li, Fei Wei, Yaliang Li, Bolin Ding, Jing Gao  

**Link**: [PDF](https://arxiv.org/pdf/2501.07813)  

**Abstract**: Leveraging large language models (LLMs), an agent can utilize retrieval-augmented generation (RAG) techniques to integrate external knowledge and increase the reliability of its responses. Current RAG-based agents integrate single, domain-specific knowledge sources, limiting their ability and leading to hallucinated or inaccurate responses when addressing cross-domain queries. Integrating multiple knowledge bases into a unified RAG-based agent raises significant challenges, including increased retrieval overhead and data sovereignty when sensitive data is involved. In this work, we propose RopMura, a novel multi-agent system that addresses these limitations by incorporating highly efficient routing and planning mechanisms. RopMura features two key components: a router that intelligently selects the most relevant agents based on knowledge boundaries and a planner that decomposes complex multi-hop queries into manageable steps, allowing for coordinating cross-domain responses. Experimental results demonstrate that RopMura effectively handles both single-hop and multi-hop queries, with the routing mechanism enabling precise answers for single-hop queries and the combined routing and planning mechanisms achieving accurate, multi-step resolutions for complex queries. 

**Abstract (ZH)**: 利用大规模语言模型（LLMs），代理可以通过检索增强生成（RAG）技术整合外部知识，从而提高其回复的可靠性。当前基于RAG的代理整合的是单个、专业化的知识来源，这限制了它们的能力，并在处理跨领域查询时导致产生了虚假或不准确的回复。将多个知识库整合到统一的基于RAG的代理中会面临显著的挑战，包括增加的检索开销以及涉及敏感数据时的数据主权问题。在这项工作中，我们提出了一种名为RopMura的新型多代理系统，通过引入高效的路由和规划机制来解决这些局限性。RopMura有两个关键组件：一个路由器，可以根据知识边界智能地选择最相关的代理；以及一个规划器，将复杂的多跳查询分解成可管理的步骤，从而协调跨领域的回复。实验结果表明，RopMura能够有效处理单跳和多跳查询。路由机制能够为单跳查询提供精确的答案，而结合的路由和规划机制则可以实现复杂查询的精确、多步解决方案。 

---
# Unsupervised Query Routing for Retrieval Augmented Generation 

**Title (ZH)**: 无监督查询路由以增强检索生成 

**Authors**: Feiteng Mu, Liwen Zhang, Yong Jiang, Wenjie Li, Zhen Zhang, Pengjun Xie, Fei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.07793)  

**Abstract**: Query routing for retrieval-augmented generation aims to assign an input query to the most suitable search engine. Existing works rely heavily on supervised datasets that require extensive manual annotation, resulting in high costs and limited scalability, as well as poor generalization to out-of-distribution scenarios. To address these challenges, we introduce a novel unsupervised method that constructs the "upper-bound" response to evaluate the quality of retrieval-augmented responses. This evaluation enables the decision of the most suitable search engine for a given query. By eliminating manual annotations, our approach can automatically process large-scale real user queries and create training data. We conduct extensive experiments across five datasets, demonstrating that our method significantly enhances scalability and generalization capabilities. 

**Abstract (ZH)**: 检索增强生成中的查询路由旨在将输入查询分配给最适合的搜索引擎。现有工作主要依赖于需要大量人工标注的监督数据集，导致成本高且扩展有限，并且在处理分布外场景时表现不佳。为了应对这些挑战，我们提出了一种新的无监督方法，该方法构建了“上限”响应以评估检索增强响应的质量。通过这种评估，可以为给定查询决定最适合的搜索引擎。通过消除人工标注，我们的方法可以自动处理大规模的实际用户查询并生成训练数据。我们通过五个数据集进行了广泛的实验，表明我们的方法在可扩展性和泛化能力方面显著增强。 

---
# ReARTeR: Retrieval-Augmented Reasoning with Trustworthy Process Rewarding 

**Title (ZH)**: ReARTeR：具有可信过程奖励的检索增强推理 

**Authors**: Zhongxiang Sun, Qipeng Wang, Weijie Yu, Xiaoxue Zang, Kai Zheng, Jun Xu, Xiao Zhang, Song Yang, Han Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.07861)  

**Abstract**: Retrieval-Augmented Generation (RAG) systems for Large Language Models (LLMs) hold promise in knowledge-intensive tasks but face limitations in complex multi-step reasoning. While recent methods have integrated RAG with chain-of-thought reasoning or test-time search using Process Reward Models (PRMs), these approaches encounter challenges such as a lack of explanations, bias in PRM training data, early-step bias in PRM scores, and insufficient post-training optimization of reasoning potential. To address these issues, we propose Retrieval-Augmented Reasoning through Trustworthy Process Rewarding (ReARTeR), a framework that enhances RAG systems' reasoning capabilities through post-training and test-time scaling. At test time, ReARTeR introduces Trustworthy Process Rewarding via a Process Reward Model for accurate scalar scoring and a Process Explanation Model (PEM) for generating natural language explanations, enabling step refinement. During post-training, it utilizes Monte Carlo Tree Search guided by Trustworthy Process Rewarding to collect high-quality step-level preference data, optimized through Iterative Preference Optimization. ReARTeR addresses three core challenges: (1) misalignment between PRM and PEM, tackled through off-policy preference learning; (2) bias in PRM training data, mitigated by balanced annotation methods and stronger annotations for challenging examples; and (3) early-step bias in PRM, resolved through a temporal-difference-based look-ahead search strategy. Experimental results on multi-step reasoning benchmarks demonstrate significant improvements, underscoring ReARTeR's potential to advance the reasoning capabilities of RAG systems. 

**Abstract (ZH)**: 增强检索的生成（RAG）系统在大型语言模型（LLMs）中的知识密集型任务中展现出潜力，但在复杂多步推理方面面临局限。尽管最近的方法已经将RAG与链式推理或测试时的搜索（使用过程奖励模型PRM）相结合，但这些方法仍然存在诸如缺乏解释、PRM训练数据中的偏差、PRM评分的早期步骤偏差以及推理潜力的测试后训练优化不足等问题。为了解决这些问题，我们提出了一种名为“信赖过程奖励增强推理”（ReARTeR）的框架，该框架通过测试时和测试后训练的放大来增强RAG系统的推理能力。在测试时，ReARTeR通过引入一种过程奖励模型进行准确的标量评分，并通过过程解释模型（PEM）生成自然语言解释，以实现步骤细化。在测试后训练阶段，它利用通过信赖过程奖励指导的蒙特卡罗树搜索收集高质量的步骤偏好数据，并通过迭代偏好优化进行优化。ReARTeR解决的三个核心挑战包括：（1）PRM和PEM之间的不一致，通过离策偏好学习解决；（2）PRM训练数据中的偏差，通过平衡注释方法和对具有挑战性的例子进行更严格的注释来缓解；（3）PRM中的早期步骤偏差，通过基于时差的前瞻搜索策略解决。在多步骤推理基准测试中的实验结果表明，ReARTeR在显著提高RAG系统的推理能力方面具有巨大潜力。 

---