# Large Language Model driven Policy Exploration for Recommender Systems 

**Title (ZH)**: Large语言模型驱动的策略探索在推荐系统中的应用 

**Authors**: Jie Wang, Alexandros Karatzoglou, Ioannis Arapakis, Joemon M. Jose  

**Link**: [PDF](https://arxiv.org/pdf/2501.13816)  

**Abstract**: Recent advancements in Recommender Systems (RS) have incorporated Reinforcement Learning (RL), framing the recommendation as a Markov Decision Process (MDP). However, offline RL policies trained on static user data are vulnerable to distribution shift when deployed in dynamic online environments. Additionally, excessive focus on exploiting short-term relevant items can hinder exploration, leading to suboptimal recommendations and negatively impacting long-term user gains. Online RL-based RS also face challenges in production deployment, due to the risks of exposing users to untrained or unstable policies. Large Language Models (LLMs) offer a promising solution to mimic user objectives and preferences for pre-training policies offline to enhance the initial recommendations in online settings. Effectively managing distribution shift and balancing exploration are crucial for improving RL-based RS, especially when leveraging LLM-based pre-training. To address these challenges, we propose an Interaction-Augmented Learned Policy (iALP) that utilizes user preferences distilled from an LLM. Our approach involves prompting the LLM with user states to extract item preferences, learning rewards based on feedback, and updating the RL policy using an actor-critic framework. Furthermore, to deploy iALP in an online scenario, we introduce an adaptive variant, A-iALP, that implements a simple fine-tuning strategy (A-iALP$_{ft}$), and an adaptive approach (A-iALP$_{ap}$) designed to mitigate issues with compromised policies and limited exploration. Experiments across three simulated environments demonstrate that A-iALP introduces substantial performance improvements 

**Abstract (ZH)**: 近年来，推荐系统（RS）的进步已经将强化学习（RL）纳入其中，将推荐问题框架化为马尔可夫决策过程（MDP）。然而，基于静止用户数据离线训练的RL策略在动态在线环境中部署时容易受到分布转移的影响。此外，过分注重利用短期内的相关项目可能会妨碍探索，导致推荐不理想，并对长期用户收益产生负面影响。基于在线RL的推荐系统在实际部署中也面临着挑战，因为这可能使用户接触到未训练或不稳定策略的风险。大型语言模型（LLMs）提供了一种有前景的解决方案，通过从LLM中提取用户偏好进行离线策略训练，以增强在线环境初期的推荐效果。有效地管理分布转移并平衡探索对于提高基于RL的推荐系统至关重要，特别是在利用基于LLM的预训练时。为了解决这些挑战，我们提出了一种增强交互的学习策略（iALP），它利用从LLM中提炼出的用户偏好。我们的方法包括使用LLM提示用户状态以提取项目偏好，基于反馈学习奖励，并使用演员-评论家框架更新RL策略。此外，为了在线环境中部署iALP，我们引入了一个适应性变体A-iALP，其中包括一种简单的微调策略（A-iALP$_{ft}$）和一种适应性方法（A-iALP$_{ap}$），该方法旨在缓解策略缺陷和有限探索所带来的问题。在三个模拟环境中进行的实验表明，A-iALP带来了显著的性能改进。 

---
# EICopilot: Search and Explore Enterprise Information over Large-scale Knowledge Graphs with LLM-driven Agents 

**Title (ZH)**: EICopilot：使用LLM驱动代理在大规模知识图中搜索和探索企业信息 

**Authors**: Yuhui Yun, Huilong Ye, Xinru Li, Ruojia Li, Jingfeng Deng, Li Li, Haoyi Xiong  

**Link**: [PDF](https://arxiv.org/pdf/2501.13746)  

**Abstract**: The paper introduces EICopilot, an novel agent-based solution enhancing search and exploration of enterprise registration data within extensive online knowledge graphs like those detailing legal entities, registered capital, and major shareholders. Traditional methods necessitate text-based queries and manual subgraph explorations, often resulting in time-consuming processes. EICopilot, deployed as a chatbot via Baidu Enterprise Search, improves this landscape by utilizing Large Language Models (LLMs) to interpret natural language queries. This solution automatically generates and executes Gremlin scripts, providing efficient summaries of complex enterprise relationships. Distinct feature a data pre-processing pipeline that compiles and annotates representative queries into a vector database of examples for In-context learning (ICL), a comprehensive reasoning pipeline combining Chain-of-Thought with ICL to enhance Gremlin script generation for knowledge graph search and exploration, and a novel query masking strategy that improves intent recognition for heightened script accuracy. Empirical evaluations demonstrate the superior performance of EICopilot, including speed and accuracy, over baseline methods, with the \emph{Full Mask} variant achieving a syntax error rate reduction to as low as 10.00% and an execution correctness of up to 82.14%. These components collectively contribute to superior querying capabilities and summarization of intricate datasets, positioning EICopilot as a groundbreaking tool in the exploration and exploitation of large-scale knowledge graphs for enterprise information search. 

**Abstract (ZH)**: 本文介绍了EICopilot，一种基于代理的新颖解决方案，该方案增强了在广泛的在线知识图谱（如法律实体、注册资本和主要股东详情）中搜索和探索企业注册数据的能力。传统方法需要基于文本的查询和手动的子图探索，这往往会导致耗时的过程。通过在百度企业搜索中部署聊天机器人的方式，EICopilot 利用大型语言模型（LLMs）解释自然语言查询，从而自动生成和执行Gremlin脚本，提供高效的复杂企业关系总结。该解决方案具有以下特点：一个数据预处理管道，用于编译和注释代表性查询以构成语境学习（ICL）的向量数据库示例；一个综合推理管道，结合了有问答推理（Chain-of-Thought）和ICL，以增强Gremlin脚本生成，用于知识图搜索和探索；以及一种新颖的查询掩码策略，以提高意图识别并增强脚本准确性。实验证明，EICopilot 在速度和准确性方面优于基线方法，其中“全掩码”变体将语法错误率降低到最低10.00%，执行正确性高达82.14%。这些组件共同提高了查询能力和复杂数据集的总结能力，将EICopilot 作为探索和利用大规模知识图谱进行企业信息搜索的开创性工具。 

---
# Full-Stack Optimized Large Language Models for Lifelong Sequential Behavior Comprehension in Recommendation 

**Title (ZH)**: 针对推荐系统中全 生命周期 序列行为理解的全栈优化大型语言模型 

**Authors**: Rong Shan, Jiachen Zhu, Jianghao Lin, Chenxu Zhu, Bo Chen, Ruiming Tang, Yong Yu, Weinan Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13344)  

**Abstract**: In this paper, we address the lifelong sequential behavior incomprehension problem in large language models (LLMs) for recommendation, where LLMs struggle to extract useful information from long user behavior sequences, even within their context limits. To tackle this, we propose ReLLaX (Retrieval-enhanced Large Language models Plus), a framework offering optimization across data, prompt, and parameter levels. At the data level, we introduce Semantic User Behavior Retrieval (SUBR) to reduce sequence heterogeneity, making it easier for LLMs to extract key information. For prompt-level enhancement, we employ Soft Prompt Augmentation (SPA) to inject collaborative knowledge, aligning item representations with recommendation tasks and improving LLMs's exploration of item relationships. Finally, at the parameter level, we propose Component Fully-interactive LoRA (CFLoRA), which enhances LoRA's expressiveness by enabling interactions between its components, allowing better capture of sequential information. Moreover, we present new perspectives to compare current LoRA-based LLM4Rec methods, i.e. from both a composite and a decomposed view. We theoretically demonstrate that the ways they employ LoRA for recommendation are degraded versions of our CFLoRA, with different constraints on atom component interactions. Extensive experiments on three public datasets demonstrate ReLLaX's superiority over existing baselines and its ability to mitigate lifelong sequential behavior incomprehension effectively. 

**Abstract (ZH)**: 在这篇文章中，我们研究了大型语言模型（LLMs）在推荐中的终身序列行为理解问题，LLMs 在提取来自长用户行为序列的有用信息方面存在困难，即使在它们的上下文限制内也是如此。为了解决这个问题，我们提出了一种名为 ReLLaX（检索增强的大规模语言模型增强）的框架，该框架在数据、提示和参数层面提供优化。在数据层面，我们引入了语义用户行为检索（SUBR）来减少序列异质性，使大型语言模型更容易提取关键信息。在提示层面，我们使用软提示增强（SPA）注入协作知识，使项目表示与推荐任务对齐，并提高大型语言模型在探索项目关系方面的探索能力。最后，在参数层面，我们提出了组件完全交互的低秩自适应（CFLoRA），它通过使低秩自适应（LoRA）的组件之间能够相互作用来增强它的表达能力，从而更好地捕捉序列信息。此外，我们从整体和分解的角度提出了新的视角来对比当前基于LoRA的LLM4Rec方法。我们理论证明了它们使用LoRA的方式是我们的CFLoRA的退化版本，具有不同的原子组件交互约束。大规模实验在三个公开数据集上表明，ReLLaX在性能上优于现有基线，并且能够有效缓解终身序列行为理解问题。 

---
# Hallucinations Can Improve Large Language Models in Drug Discovery 

**Title (ZH)**: hallucinations 可以提高药物发现中大型语言模型的能力 

**Authors**: Shuzhou Yuan, Michael Färber  

**Link**: [PDF](https://arxiv.org/pdf/2501.13824)  

**Abstract**: Concerns about hallucinations in Large Language Models (LLMs) have been raised by researchers, yet their potential in areas where creativity is vital, such as drug discovery, merits exploration. In this paper, we come up with the hypothesis that hallucinations can improve LLMs in drug discovery. To verify this hypothesis, we use LLMs to describe the SMILES string of molecules in natural language and then incorporate these descriptions as part of the prompt to address specific tasks in drug discovery. Evaluated on seven LLMs and five classification tasks, our findings confirm the hypothesis: LLMs can achieve better performance with text containing hallucinations. Notably, Llama-3.1-8B achieves an 18.35% gain in ROC-AUC compared to the baseline without hallucination. Furthermore, hallucinations generated by GPT-4o provide the most consistent improvements across models. Additionally, we conduct empirical analyses and a case study to investigate key factors affecting performance and the underlying reasons. Our research sheds light on the potential use of hallucinations for LLMs and offers new perspectives for future research leveraging LLMs in drug discovery. 

**Abstract (ZH)**: 研究人员对大型语言模型（LLMs）的幻觉 concerns提出了一定担忧，然而在涉及创造力的关键领域，如药物发现，它们的潜力仍值得探索。本文中，我们提出了这样一个假设：幻觉能够提升药物发现中的LLMs性能。为了验证这一假设，我们利用LLMs将分子的SMILES字符串描述为自然语言，并将这些描述纳入特定药物发现任务的提示中。我们在七种LLMs和五项分类任务上进行了评估，研究结果证实了这一假设：包含幻觉的文本能够提高LLMs的性能。值得注意的是，Llama-3.1-8B在没有幻觉的情况下基线性能上实现了18.35%的ROC-AUC增幅。此外，GPT-4o生成的幻觉在不同模型中提供了最一致的改进。我们还通过实证分析和案例研究探讨了影响性能的关键因素及背后的机制。本研究为利用幻觉提升LLMs的药物发现潜能提供了新的视角，并对未来利用LLMs进行药物发现的研究提供了新的思路。 

---
# Do Large Language Models Truly Understand Geometric Structures? 

**Title (ZH)**: 大型语言模型真正在理解几何结构吗？ 

**Authors**: Xiaofeng Wang, Yiming Wang, Wenhong Zhu, Rui Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13773)  

**Abstract**: Geometric ability is a significant challenge for large language models (LLMs) due to the need for advanced spatial comprehension and abstract thinking. Existing datasets primarily evaluate LLMs on their final answers, but they cannot truly measure their true understanding of geometric structures, as LLMs can arrive at correct answers by coincidence. To fill this gap, we introduce the GeomRel dataset, designed to evaluate LLMs' understanding of geometric structures by isolating the core step of geometric relationship identification in problem-solving. Using this benchmark, we conduct thorough evaluations of diverse LLMs and identify key limitations in understanding geometric structures. We further propose the Geometry Chain-of-Thought (GeoCoT) method, which enhances LLMs' ability to identify geometric relationships, resulting in significant performance improvements. 

**Abstract (ZH)**: 几何能力是大型语言模型（LLMs）的一个重要挑战，因为这需要高级的空间理解和抽象思维。现有的数据集主要评估LLMs的最终答案，但它们无法真正衡量LLMs对几何结构的理解，因为LLMs可能会通过巧合得出正确答案。为填补这一空白，我们引入了GeomRel数据集，旨在通过隔离问题解决中的几何关系识别核心步骤来评估LLMs对几何结构的理解。利用这一基准，我们对各种LLMs进行了全面评估，并识别出理解几何结构的关键限制。我们进一步提出了几何推理链（GeoCoT）方法，该方法增强了LLMs识别几何关系的能力，从而取得了显著的性能提升。 

---
# UGMathBench: A Diverse and Dynamic Benchmark for Undergraduate-Level Mathematical Reasoning with Large Language Models 

**Title (ZH)**: UGMathBench：用于本科生级数学推理的大语言模型多样性动态基准测试 

**Authors**: Xin Xu, Jiaxin Zhang, Tianhao Chen, Zitong Chao, Jishan Hu, Can Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13766)  

**Abstract**: Large Language Models (LLMs) have made significant strides in mathematical reasoning, underscoring the need for a comprehensive and fair evaluation of their capabilities. However, existing benchmarks often fall short, either lacking extensive coverage of undergraduate-level mathematical problems or probably suffering from test-set contamination. To address these issues, we introduce UGMathBench, a diverse and dynamic benchmark specifically designed for evaluating undergraduate-level mathematical reasoning with LLMs. UGMathBench comprises 5,062 problems across 16 subjects and 111 topics, featuring 10 distinct answer types. Each problem includes three randomized versions, with additional versions planned for release as leading open-source LLMs become saturated in UGMathBench. Furthermore, we propose two key metrics: effective accuracy (EAcc), which measures the percentage of correctly solved problems across all three versions, and reasoning gap ($\Delta$), which assesses reasoning robustness by calculating the difference between the average accuracy across all versions and EAcc. Our extensive evaluation of 23 leading LLMs reveals that the highest EAcc achieved is 56.3\% by OpenAI-o1-mini, with large $\Delta$ values observed across different models. This highlights the need for future research aimed at developing "large reasoning models" with high EAcc and $\Delta = 0$. We anticipate that the release of UGMathBench, along with its detailed evaluation codes, will serve as a valuable resource to advance the development of LLMs in solving mathematical problems. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在数学推理方面取得了显著进步，凸显了全面公平评估其能力的迫切需要。然而，现有的基准测试往往存在不足，要么涵盖的本科水平数学问题不够广泛，要么存在测试集污染的问题。为解决这些问题，我们引入了UGMathBench，一种专为评估LLMs在本科水平数学推理能力的多样性和动态基准测试。UGMathBench 包含16个学科和111个主题的5062道题目，涵盖10种不同的答案类型。每个问题包括三种随机版本，随着领先的开源LLMs在UGMathBench 中饱和，计划发布更多版本。此外，我们提出了两个关键指标：有效的准确率（EAcc），衡量所有三个版本中正确解决问题的比例；推理差距（$\Delta$），通过计算所有版本平均准确率与EAcc之间的差异来评估推理的稳健性。我们对23个领先的大规模语言模型进行的广泛评估表明，最高EAcc为OpenAI-o1-mini 达到了56.3%，不同模型在$\Delta$方面有很高的差异值。这强调了未来研究的需要，以开发具有高EAcc和$\Delta = 0$的“大推理模型”。我们预计UGMathBench 的发布及其详细的评估代码将成为推进解决数学问题的大规模语言模型开发的一个宝贵资源。 

---
# Pseudocode-Injection Magic: Enabling LLMs to Tackle Graph Computational Tasks 

**Title (ZH)**: 伪代码注入魔力：使大模型能够应对图计算任务 

**Authors**: Chang Gong, Wanrui Bian, Zhijie Zhang, Weiguo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.13731)  

**Abstract**: Graph computational tasks are inherently challenging and often demand the development of advanced algorithms for effective solutions. With the emergence of large language models (LLMs), researchers have begun investigating their potential to address these tasks. However, existing approaches are constrained by LLMs' limited capability to comprehend complex graph structures and their high inference costs, rendering them impractical for handling large-scale graphs. Inspired by human approaches to graph problems, we introduce a novel framework, PIE (Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks), which consists of three key steps: problem understanding, prompt design, and code generation. In this framework, LLMs are tasked with understanding the problem and extracting relevant information to generate correct code. The responsibility for analyzing the graph structure and executing the code is delegated to the interpreter. We inject task-related pseudocodes into the prompts to further assist the LLMs in generating efficient code. We also employ cost-effective trial-and-error techniques to ensure that the LLM-generated code executes correctly. Unlike other methods that require invoking LLMs for each individual test case, PIE only calls the LLM during the code generation phase, allowing the generated code to be reused and significantly reducing inference costs. Extensive experiments demonstrate that PIE outperforms existing baselines in terms of both accuracy and computational efficiency. 

**Abstract (ZH)**: 图计算任务本质上具有挑战性，通常需要开发高级算法以实现有效解决。随着大型语言模型（LLMs）的出现，研究人员开始探讨其在解决这些问题方面的潜力。然而，现有的方法受限于LLMs理解复杂图结构的能力有限以及高昂的推理成本，这使得它们在处理大规模图时 impractical。受人类解决图问题方法的启发，我们提出了一种名为PIE（Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks）的新框架，该框架包含三个关键步骤：问题理解、提示设计和代码生成。在该框架中，LLMs的任务是理解问题并提取相关信息以生成正确的代码。分析图结构和执行代码的责任被委托给解释器。为了进一步帮助LLMs生成高效的代码，我们在提示中注入了相关任务的伪代码。我们还采用经济有效的试错技术，以确保LLM生成的代码能够正确执行。与需要为每个单独的测试案例调用LLM的方法不同，PIE在代码生成阶段仅调用LLM，从而使生成的代码可以重用，并显著降低了推理成本。广泛的经验表明，PIE在准确性和计算效率方面都优于现有基线方法。 

---
# RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation 

**Title (ZH)**: RPO：鲁棒检索增强生成中的检索偏好优化 

**Authors**: Shi-Qi Yan, Zhen-Hua Ling  

**Link**: [PDF](https://arxiv.org/pdf/2501.13726)  

**Abstract**: While Retrieval-Augmented Generation (RAG) has exhibited promise in utilizing external knowledge, its generation process heavily depends on the quality and accuracy of the retrieved context. Large language models (LLMs) struggle to evaluate the correctness of non-parametric knowledge retrieved externally when it differs from internal memorization, leading to knowledge conflicts during response generation. To this end, we introduce the Retrieval Preference Optimization (RPO), a lightweight and effective alignment method to adaptively leverage multi-source knowledge based on retrieval relevance. An implicit representation of retrieval relevance is derived and incorporated into the reward model to integrate retrieval evaluation and response generation into a single model, solving the problem that previous methods necessitate the additional procedure to assess the retrieval quality. Notably, RPO is the only RAG-dedicated alignment approach that quantifies the awareness of retrieval relevance in training, overcoming mathematical obstacles. Experiments on four datasets demonstrate that RPO outperforms RAG by 4-10% in accuracy without any extra component, exhibiting its robust generalization. 

**Abstract (ZH)**: 尽管检索增强生成（RAG）展示了利用外部知识的潜力，其生成过程高度依赖于检索上下文的质量和准确性。大型语言模型（LLMs）在评估与内部记忆不同的外部非参数化知识的正确性时存在困难，这导致在响应生成过程中出现知识冲突。为此，我们提出了检索偏好优化（RPO），这是一种轻量级且有效的对齐方法，可以根据检索相关性适当地利用多源知识。通过推导检索相关性的隐式表示并将其融入奖励模型中，将检索评估与响应生成整合到单一模型中，解决了先前方法需要额外步骤评估检索质量的问题。值得注意的是，RPO 是唯一一种在训练中量化检索相关性意识的 RAG 专用对齐方法，克服了数学障碍。在四个数据集上的实验表明，RPO 在无需任何额外组件的情况下比 RAG 在准确性上提高了 4%-10%，展示了其稳健的泛化能力。 

---
# How to Complete Domain Tuning while Keeping General Ability in LLM: Adaptive Layer-wise and Element-wise Regularization 

**Title (ZH)**: 如何在保持泛化能力的同时完成领域微调：自适应分层和元素化正则化 

**Authors**: Shezheng Song, Hao Xu, Jun Ma, Shasha Li, Long Peng, Qian Wan, Xiaodong Liu, Jie Yu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13669)  

**Abstract**: Large Language Models (LLMs) exhibit strong general-purpose language capabilities. However, fine-tuning these models on domain-specific tasks often leads to catastrophic forgetting, where the model overwrites or loses essential knowledge acquired during pretraining. This phenomenon significantly limits the broader applicability of LLMs. To address this challenge, we propose a novel approach to compute the element-wise importance of model parameters crucial for preserving general knowledge during fine-tuning. Our method utilizes a dual-objective optimization strategy: (1) regularization loss to retain the parameter crucial for general knowledge; (2) cross-entropy loss to adapt to domain-specific tasks. Additionally, we introduce layer-wise coefficients to account for the varying contributions of different layers, dynamically balancing the dual-objective optimization. Extensive experiments on scientific, medical, and physical tasks using GPT-J and LLaMA-3 demonstrate that our approach mitigates catastrophic forgetting while enhancing model adaptability. Compared to previous methods, our solution is approximately 20 times faster and requires only 10%-15% of the storage, highlighting the practical efficiency. The code will be released. 

**Abstract (ZH)**: 大型语言模型（LLMs）展现出强大的通用语言能力。然而，在特定任务上的微调往往会导致灾难性的遗忘现象，即模型在微调过程中会覆盖或丢失预训练阶段获得的重要知识。这一现象极大地限制了LLMs的广泛应用。为了解决这一挑战，我们提出了一种新的方法，用于计算在微调过程中对保持通用知识至关重要的模型参数的元素级重要性。我们的方法采用双目标优化策略：（1）正则化损失，以保留对于通用知识至关重要的参数；（2）交叉熵损失，以适应特定任务。此外，我们引入了分层系数来 account for 不同层的差异性贡献，并动态平衡双目标优化。在使用GPT-J和LLaMA-3进行的涉及科学、医学和物理任务的广泛实验中，我们证明了我们的方法可以减轻灾难性的遗忘现象，同时增强模型的适应性。与之前的解决方案相比，我们的方法大约快20倍，并且只需要10%-15%的存储空间，这突显出其实用效率。我们将发布相应的代码。 

---
# Improving Contextual Faithfulness of Large Language Models via Retrieval Heads-Induced Optimization 

**Title (ZH)**: 通过检索头部引导优化提高大型语言模型的语境忠实度 

**Authors**: Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yangfan Ye, Weihong Zhong, Yuxuan Gu, Baoxin Wang, Dayong Wu, Guoping Hu, Bing Qin  

**Link**: [PDF](https://arxiv.org/pdf/2501.13573)  

**Abstract**: Ensuring contextual faithfulness in retrieval-augmented large language models (LLMs) is crucial for building trustworthy information-seeking systems, particularly in long-form question-answering (LFQA) scenarios. In this work, we identify a salient correlation between LFQA faithfulness and retrieval heads, a set of attention heads responsible for retrieving contextual information. Leveraging this insight, we propose RHIO, a framework designed to teach LLMs to explicitly discriminate between faithful and unfaithful generations. RHIO first augments unfaithful samples that simulate realistic model-intrinsic errors by selectively masking retrieval heads. Then, these samples are incorporated into joint training, enabling the model to distinguish unfaithful outputs from faithful ones conditioned on control tokens. Furthermore, these control tokens are leveraged to self-induce contrastive outputs, amplifying their difference through contrastive decoding. Additionally, to facilitate the evaluation of contextual faithfulness, we also introduce GroundBench, a comprehensive benchmark compiled from five existing LFQA datasets. Extensive experimental results on GroundBench demonstrate that RHIO significantly improves faithfulness, even outperforming GPT-4o. 

**Abstract (ZH)**: 在检索增强的大语言模型（LLMs）中确保上下文一致性忠实性对于构建可信赖的信息检索系统至关重要，特别是在长文本问答（LFQA）场景中。在本研究中，我们发现了LFQA忠实性与检索头部之间的显著关联，检索头部是一系列负责检索上下文信息的注意力头部。基于这一洞察，我们提出了RHIO框架，旨在教导LLMs明确区分忠实生成和不忠实生成。RHIO首先通过选择性屏蔽检索头部来增强不忠实样例，模拟模型固有的错误，然后将这些样例纳入联合训练，从而让模型在控制令牌条件下区分不忠实输出和忠实输出。此外，这些控制令牌还被利用来自我引导对比性输出，通过对比解码放大其差异。此外，为了方便评估上下文忠实性，我们还引入了GroundBench基准，该基准从五个现有的LFQA数据集中综合而成。在GroundBench上的广泛实验结果表明，RHIO显著提高了忠实性，甚至优于GPT-4o。 

---
# LLMs Can Plan Only If We Tell Them 

**Title (ZH)**: LLMs 只能在我们明确指示的情况下才能进行规划 

**Authors**: Bilgehan Sel, Ruoxi Jia, Ming Jin  

**Link**: [PDF](https://arxiv.org/pdf/2501.13545)  

**Abstract**: Large language models (LLMs) have demonstrated significant capabilities in natural language processing and reasoning, yet their effectiveness in autonomous planning has been under debate. While existing studies have utilized LLMs with external feedback mechanisms or in controlled environments for planning, these approaches often involve substantial computational and development resources due to the requirement for careful design and iterative backprompting. Moreover, even the most advanced LLMs like GPT-4 struggle to match human performance on standard planning benchmarks, such as the Blocksworld, without additional support. This paper investigates whether LLMs can independently generate long-horizon plans that rival human baselines. Our novel enhancements to Algorithm-of-Thoughts (AoT), which we dub AoT+, help achieve state-of-the-art results in planning benchmarks out-competing prior methods and human baselines all autonomously. 

**Abstract (ZH)**: 大型语言模型（LLMs）在自然语言处理和推理方面展现出了显著的能力，但在自主规划方面的有效性一直存在争议。尽管现有研究已经利用具有外部反馈机制或在受控环境中应用LLMs进行规划，这些方法往往需要大量的计算和开发资源，因为它们要求精心设计和反复的反向提示。此外，即使是最先进的LLM，如GPT-4，在标准规划基准测试（如Blocksworld）上也难以达到与人类相当的性能，除非得到额外的支持。本文探讨了LLMs是否能够独立生成与人类基线相匹敌的长期规划。我们对Algorithm-of-Thoughts（AoT）算法进行了一些新的改进，称为AoT+，这些改进使得在规划基准测试中取得了领先于先前方法和人类基线的最新成果，并实现了全部自主规划。 

---
# RECALL: Library-Like Behavior In Language Models is Enhanced by Self-Referencing Causal Cycles 

**Title (ZH)**: RECALL：通过自我参照因果循环增强的语言模型库-like 行为 

**Authors**: Munachiso Nwadike, Zangir Iklassov, Toluwani Aremu, Tatsuya Hiraoka, Velibor Bojkovic, Benjamin Heinzerling, Hilal Alqaubeh, Martin Takáč, Kentaro Inui  

**Link**: [PDF](https://arxiv.org/pdf/2501.13491)  

**Abstract**: We introduce the concept of the self-referencing causal cycle (abbreviated RECALL) - a mechanism that enables large language models (LLMs) to bypass the limitations of unidirectional causality, which underlies a phenomenon known as the reversal curse. When an LLM is prompted with sequential data, it often fails to recall preceding context. For example, when we ask an LLM to recall the line preceding "O say does that star-spangled banner yet wave" in the U.S. National Anthem, it often fails to correctly return "Gave proof through the night that our flag was still there" - this is due to the reversal curse. It occurs because language models such as ChatGPT and Llama generate text based on preceding tokens, requiring facts to be learned and reproduced in a consistent token order. While the reversal curse is often viewed as a limitation, we offer evidence of an alternative view: it is not always an obstacle in practice. We find that RECALL is driven by what we designate as cycle tokens - sequences that connect different parts of the training data, enabling recall of preceding tokens from succeeding ones. Through rigorous probabilistic formalization and controlled experiments, we demonstrate how the cycles they induce influence a model's ability to reproduce information. To facilitate reproducibility, we provide our code and experimental details at this https URL. 

**Abstract (ZH)**: 我们引入了自我参照因果循环（简称RECALL）的概念——这是一种机制，使得大规模语言模型（LLMs）能够克服单一方向因果性的限制，这些限制导致了一种被称为反转诅咒的现象。当LLM被馈送序贯数据时，它常常无法回溯先前的上下文。例如，在要求LLM回溯爱国歌曲《星条旗》中的“O say does that star-spangled banner yet wave”这句前面的那一行文字时（正确答案是“Gave proof through the night that our flag was still there”），它经常无法正确地返回这个信息 —— 这就是反转诅咒的原因。这种现象是因为像ChatGPT和Llama这样的语言模型是基于先前的词元生成文本的，要求事实以一致的词元顺序被学习和再现。虽然反转诅咒通常被视为一种限制，但我们提供了证据，表明这是一种替代的看法：在实践中，它并不总是障碍。我们发现，RECALL是由于我们称之为循环词元的序列驱动的 —— 这些序列连接训练数据的不同部分，从而使模型能够从后续词元回溯到先前的词元并进行回溯。通过严谨的概率形式化和受控实验，我们展示了循环如何影响模型再现信息的能力。为了促进可重复性，我们在这里提供了我们的代码和实验细节：https://example.com（请注意，这里的URL是示例，您需要替换为实际的URL）。 

---
# Can Large Language Models Understand Preferences in Personalized Recommendation? 

**Title (ZH)**: 大型语言模型能否理解个性化推荐中的偏好？ 

**Authors**: Zhaoxuan Tan, Zinan Zeng, Qingkai Zeng, Zhenyu Wu, Zheyuan Liu, Fengran Mo, Meng Jiang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13391)  

**Abstract**: Large Language Models (LLMs) excel in various tasks, including personalized recommendations. Existing evaluation methods often focus on rating prediction, relying on regression errors between actual and predicted ratings. However, user rating bias and item quality, two influential factors behind rating scores, can obscure personal preferences in user-item pair data. To address this, we introduce PerRecBench, disassociating the evaluation from these two factors and assessing recommendation techniques on capturing the personal preferences in a grouped ranking manner. We find that the LLM-based recommendation techniques that are generally good at rating prediction fail to identify users' favored and disfavored items when the user rating bias and item quality are eliminated by grouping users. With PerRecBench and 19 LLMs, we find that while larger models generally outperform smaller ones, they still struggle with personalized recommendation. Our findings reveal the superiority of pairwise and listwise ranking approaches over pointwise ranking, PerRecBench's low correlation with traditional regression metrics, the importance of user profiles, and the role of pretraining data distributions. We further explore three supervised fine-tuning strategies, finding that merging weights from single-format training is promising but improving LLMs' understanding of user preferences remains an open research problem. Code and data are available at this https URL 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种任务中表现出色，包括个性化推荐。现有的评估方法往往侧重于评分预测，依赖于实际评分和预测评分之间的回归误差。然而，用户评分偏差和物品质量这两个影响评分分数的重要因素，可能会掩盖用户-物品对数据中的个人偏好。为了解决这个问题，我们引入了PerRecBench，使评估与这两个因素脱钩，并通过分组排名的方式评估推荐技术捕捉个人偏好的能力。我们发现，一般擅长评分预测的基于LLM的推荐技术，在消除用户评分偏差和物品质量后的分组用户数据中，难以识别用户的喜爱和不喜欢的物品。利用PerRecBench和19种LLM，我们发现虽然较大的模型通常优于较小的模型，但在个性化推荐方面仍存在问题。我们的研究结果揭示了成对排名和列表排名方法优于点预测方法的优势，PerRecBench和传统回归指标的相关性较低，用户资料的重要性，以及预训练数据分布的作用。我们进一步探讨了三种监督微调策略，发现从单一格式训练中合并权重是颇具前景的，但提升LLM对用户偏好的理解仍然是一个有待解决的研究问题。代码和数据可在以下链接获取：[此 https URL] 

---
# Hypothesis Generation for Materials Discovery and Design Using Goal-Driven and Constraint-Guided LLM Agents 

**Title (ZH)**: 使用目标驱动和约束引导的大规模语言模型代理进行材料发现与设计的假设生成 

**Authors**: Shrinidhi Kumbhar, Venkatesh Mishra, Kevin Coutinho, Divij Handa, Ashif Iquebal, Chitta Baral  

**Link**: [PDF](https://arxiv.org/pdf/2501.13299)  

**Abstract**: Materials discovery and design are essential for advancing technology across various industries by enabling the development of application-specific materials. Recent research has leveraged Large Language Models (LLMs) to accelerate this process. We explore the potential of LLMs to generate viable hypotheses that, once validated, can expedite materials discovery. Collaborating with materials science experts, we curated a novel dataset from recent journal publications, featuring real-world goals, constraints, and methods for designing real-world applications. Using this dataset, we test LLM-based agents that generate hypotheses for achieving given goals under specific constraints. To assess the relevance and quality of these hypotheses, we propose a novel scalable evaluation metric that emulates the process a materials scientist would use to evaluate a hypothesis critically. Our curated dataset, proposed method, and evaluation framework aim to advance future research in accelerating materials discovery and design with LLMs. 

**Abstract (ZH)**: 材料的发现与设计对于跨多个行业的技术进步至关重要，它们能够促进定制化材料的发展。最近的研究利用大型语言模型（LLMs）来加速这一过程。我们探索了LLMs生成可行假设的可能性，这些假设一旦得到验证，可以加速材料的发现过程。通过与材料科学家的合作，我们从最近的期刊出版物中筛选出一个新颖的数据集，其中包括实际目标、约束条件和用于设计实际应用的方法。利用这个数据集，我们测试基于LLM的代理，用于在特定约束条件下生成实现给定目标的假设。为了评估这些假设的相关性和质量，我们提出了一种新的可扩展评估指标，模拟材料科学家在批判性评估假设时所使用的过程。我们筛选出来的工作数据集、提议的方法以及评价框架旨在推动未来使用LLMs加速材料发现与设计的研究。 

---
# RAMQA: A Unified Framework for Retrieval-Augmented Multi-Modal Question Answering 

**Title (ZH)**: RAMQA：一种统一的检索增强多模态问答框架 

**Authors**: Yang Bai, Christan Earl Grant, Daisy Zhe Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13297)  

**Abstract**: Multi-modal retrieval-augmented Question Answering (MRAQA), integrating text and images, has gained significant attention in information retrieval (IR) and natural language processing (NLP). Traditional ranking methods rely on small encoder-based language models, which are incompatible with modern decoder-based generative large language models (LLMs) that have advanced various NLP tasks. To bridge this gap, we propose RAMQA, a unified framework combining learning-to-rank methods with generative permutation-enhanced ranking techniques. We first train a pointwise multi-modal ranker using LLaVA as the backbone. Then, we apply instruction tuning to train a LLaMA model for re-ranking the top-k documents using an innovative autoregressive multi-task learning approach. Our generative ranking model generates re-ranked document IDs and specific answers from document candidates in various permutations. Experiments on two MRAQA benchmarks, WebQA and MultiModalQA, show significant improvements over strong baselines, highlighting the effectiveness of our approach. Code and data are available at: this https URL 

**Abstract (ZH)**: 多模态检索增强的问答（MRAQA），结合文本和图像，已在信息检索（IR）和自然语言处理（NLP）领域引起了广泛关注。传统的排名方法依赖于小型的基于编码器的语言模型，这些模型与现代基于解码器的生成型大型语言模型（LLMs）不兼容，后者已在多种NLP任务中取得进展。为了弥补这一差距，我们提出了一种结合了学习到排名方法和生成型排列增强排名技术的统一框架RAMQA。我们首先使用LLaVA作为骨干训练一个点wise多模态排名器。然后，我们通过创新的自回归多任务学习方法对LLaMA模型进行指令微调，以对前k个文档进行重新排名。我们的生成型排名模型从文档候选集中生成重新排排名的文档ID和特定答案的各种排列。在两个MRAQA基准数据集WebQA和MultiModalQA上的实验表明，我们的方法在强基线方法上取得了显著的改进，突显了我们方法的有效性。相关代码和数据可在以下链接获取：this https URL 

---
# Preference Curriculum: LLMs Should Always Be Pretrained on Their Preferred Data 

**Title (ZH)**: 偏好 Curriculum：大规模语言模型应在首选数据上始终进行预训练 

**Authors**: Xuemiao Zhang, Liangyu Xu, Feiyu Duan, Yongwei Zhou, Sirui Wang, Jingang Wang, Xunliang Cai  

**Link**: [PDF](https://arxiv.org/pdf/2501.13126)  

**Abstract**: Current large language models (LLMs) generally utilize a consistent data distribution throughout the entire pretraining process. However, as the model's ability improves, it intuitively should be pretrained with differentiated data. To achieve it, we propose the Perplexity Difference based Preference Curriculum learning (PDPC) framework, which always perceives and uses the data preferred by LLMs to train and boost them. Firstly, we introduce the PD metric to measure the difference in how well strong and weak models fit the samples. Samples with high PD are more challenging for weak models to learn and are more suitable to be arranged in the later stage of pretraining. Secondly, we propose the PD preference function to approximate the model and predict the data preference of the LLM at any time, so as to complete the arrangement of the entire data offline and ensure continuous training without interruption. Experimental results on 1.3B and 3B models demonstrate that our PDPC significantly surpasses baselines. Notably, the 3B model achieved more substantial gains, with an increased average accuracy of over 4.1% across various benchmarks. 

**Abstract (ZH)**: 当前的大规模语言模型（LLMs）通常在整个预训练过程中采用一致的数据分布。然而，随着模型能力的提高，直观上应该使用差异化的数据来进行预训练。为实现这一点，我们提出了基于困惑度差异的偏好 Curriculum 学习框架（PDPC），该框架始终感知并利用 LLM 更偏好使用的数据来训练和提升模型。首先，我们引入了 PD 指标来衡量强模型和弱模型在拟合样本方面差异的程度。高 PD 的样本对于弱模型来说更具挑战性，更适合安排在预训练的后期阶段。其次，我们提出了 PD 偏好函数来近似模型，并预测 LLM 在任意时间的数据偏好，从而在线下完成整个数据的排列，确保连续训练不间断。我们在1.3B和3B模型上的实验结果显示，我们的 PDPC 显著优于基线模型。值得注意的是，3B模型取得了更大的进步，各基准测试的平均准确率提高了超过4.1%。 

---
# Zero-Shot Verification-guided Chain of Thoughts 

**Title (ZH)**: 零样本验证引导的推理链 

**Authors**: Jishnu Ray Chowdhury, Cornelia Caragea  

**Link**: [PDF](https://arxiv.org/pdf/2501.13122)  

**Abstract**: Previous works have demonstrated the effectiveness of Chain-of-Thought (COT) prompts and verifiers in guiding Large Language Models (LLMs) through the space of reasoning. However, most such studies either use a fine-tuned verifier or rely on manually handcrafted few-shot examples. In contrast, in this paper, we focus on LLM-based self-verification of self-generated reasoning steps via COT prompts in a completely zero-shot regime. To explore this setting, we design a new zero-shot prompt, which we call COT STEP, to aid zero-shot decomposition of reasoning steps and design two new zero-shot prompts for LLM-based verifiers. We evaluate the verifiers' ability to classify the correctness of reasoning chains and explore different ways to use verifier scores in guiding reasoning for various mathematical and commonsense reasoning tasks with different LLMs. 

**Abstract (ZH)**: 先前的研究证明了Chain-of-Thought (COT) 提示和验证器在引导大语言模型（LLMs）进行推理方面的有效性。然而，大多数此类研究要么使用微调的验证器，要么依赖于手工构建的少量示例。相比之下，在本论文中，我们关注LLM本身的自验证机制，通过COT提示在完全零样本的情况下对自我生成的推理步骤进行自验证。为了探索这一环境，我们设计了一种新的零样本提示，我们称之为COT STEP，以帮助零样本分解推理步骤，并设计了两种新的零样本提示用于基于LLM的验证器。我们评估了验证器区分推理链正确性的能力，并探索了使用验证器分数指导不同LLM的各种数学和常识推理任务的各种方法。 

---
# Episodic Memories Generation and Evaluation Benchmark for Large Language Models 

**Title (ZH)**: 大型语言模型的 episodic 记忆生成与评估基准 

**Authors**: Alexis Huet, Zied Ben Houidi, Dario Rossi  

**Link**: [PDF](https://arxiv.org/pdf/2501.13121)  

**Abstract**: Episodic memory -- the ability to recall specific events grounded in time and space -- is a cornerstone of human cognition, enabling not only coherent storytelling, but also planning and decision-making. Despite their remarkable capabilities, Large Language Models (LLMs) lack a robust mechanism for episodic memory: we argue that integrating episodic memory capabilities into LLM is essential for advancing AI towards human-like cognition, increasing their potential to reason consistently and ground their output in real-world episodic events, hence avoiding confabulations. To address this challenge, we introduce a comprehensive framework to model and evaluate LLM episodic memory capabilities. Drawing inspiration from cognitive science, we develop a structured approach to represent episodic events, encapsulating temporal and spatial contexts, involved entities, and detailed descriptions. We synthesize a unique episodic memory benchmark, free from contamination, and release open source code and datasets to assess LLM performance across various recall and episodic reasoning tasks. Our evaluation of state-of-the-art models, including GPT-4 and Claude variants, Llama 3.1, and o1-mini, reveals that even the most advanced LLMs struggle with episodic memory tasks, particularly when dealing with multiple related events or complex spatio-temporal relationships -- even in contexts as short as 10k-100k tokens. 

**Abstract (ZH)**: episodic 记忆，即回忆特定的时间和空间背景下的事件的能力，是人类认知的基础，不仅使连贯的故事叙述成为可能，还使规划和决策成为可能。尽管大型语言模型（LLMs）具备令人印象深刻的能力，但它们缺乏稳定的 episodic 记忆机制：我们认为，将 episodic 记忆能力整合到 LLM 中对于推动人工智能向人类认知方向发展至关重要，可以提高它们合理推理和将其输出与现实世界的具体事件联系起来的能力，从而避免虚构行为。为解决这一挑战，我们提出了一个全面的框架来建模和评估 LLM 的 episodic 记忆能力。借鉴认知科学的思路，我们开发了一个有组织的方法来表示 episodic 事件，涵盖了时间与空间背景、涉及的实体以及详细的描述。我们合成了一个独特且不受污染的 episodic 记忆基准，并公开了代码和数据集，以便在各种回忆和 episodic 推理任务中评估 LLM 的性能。对包括 GPT-4 和 Claude 变体、Llama 3.1 以及 o1-mini 在内的最新模型的评估表明，即使是目前最先进的 LLM 也难以完成 episodic 记忆任务，尤其是在涉及多个相关事件或复杂时空关系的情况下——即使文本长度仅为 10K-100K 个标记也是如此。 

---
# Multilinguality in LLM-Designed Reward Functions for Restless Bandits: Effects on Task Performance and Fairness 

**Title (ZH)**: LLM设计的奖励函数中的多语言性对活跃臂问题任务性能和公平性的影响 

**Authors**: Ambreesh Parthasarathy, Chandrasekar Subramanian, Ganesh Senrayan, Shreyash Adappanavar, Aparna Taneja, Balaraman Ravindran, Milind Tambe  

**Link**: [PDF](https://arxiv.org/pdf/2501.13120)  

**Abstract**: Restless Multi-Armed Bandits (RMABs) have been successfully applied to resource allocation problems in a variety of settings, including public health. With the rapid development of powerful large language models (LLMs), they are increasingly used to design reward functions to better match human preferences. Recent work has shown that LLMs can be used to tailor automated allocation decisions to community needs using language prompts. However, this has been studied primarily for English prompts and with a focus on task performance only. This can be an issue since grassroots workers, especially in developing countries like India, prefer to work in local languages, some of which are low-resource. Further, given the nature of the problem, biases along population groups unintended by the user are also undesirable. In this work, we study the effects on both task performance and fairness when the DLM algorithm, a recent work on using LLMs to design reward functions for RMABs, is prompted with non-English language commands. Specifically, we run the model on a synthetic environment for various prompts translated into multiple languages. The prompts themselves vary in complexity. Our results show that the LLM-proposed reward functions are significantly better when prompted in English compared to other languages. We also find that the exact phrasing of the prompt impacts task performance. Further, as prompt complexity increases, performance worsens for all languages; however, it is more robust with English prompts than with lower-resource languages. On the fairness side, we find that low-resource languages and more complex prompts are both highly likely to create unfairness along unintended dimensions. 

**Abstract (ZH)**: restless 多臂老虎机（RMABs）已经在多种场景下的资源分配问题中得到了成功的应用，包括公共卫生领域。随着强大语言模型（LLMs）的快速发展，它们正越来越多地被用于设计奖励函数，以更好地匹配人类偏好。最近的研究表明，LLMs可以使用语言提示来定制自动化的资源分配决策以满足社区需求。然而，这一研究主要集中在英语提示上，并且仅关注任务性能。这可能是一个问题，因为草根工作者，尤其是像印度这样的发展中地区的工作者，更倾向于使用地方语言工作，其中一些语言是资源匮乏的语言。此外，鉴于问题的性质，由用户无意引入的人群组偏见也是不希望的。在本项工作中，我们研究了当使用 LLMs 设计奖励函数的 DLM 算法被提示非英语语言命令时，其对任务性能和公平性的影响。具体来说，我们在多种语言翻译成的多个提示中运行了该模型，并在合成环境中进行了各种提示试验。提示本身在复杂度上有所不同。我们的研究表明，与用其他语言提示相比，用英语提示时提供的 LLM 设计的奖励函数显著更好。我们还发现，提示的具体措辞对任务性能有影响。进一步地，随着提示复杂度的增加，所有语言的性能都会下降；然而，使用英语提示比使用资源匮乏的语言提示时表现更为稳定。在公平性方面，我们发现低资源语言和更复杂的提示都很可能在未预期的方面造成不公正。 

---
# MyGO Multiplex CoT: A Method for Self-Reflection in Large Language Models via Double Chain of Thought Thinking 

**Title (ZH)**: MyGO 多重共思：一种通过双重链式思考在大规模语言模型中实现自我反思的方法 

**Authors**: Shihao Ji, Zihui Song, Fucheng Zhong, Jisen Jia, Zhaobo Wu, Zheyi Cao, Tianhao Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13117)  

**Abstract**: Recent advancements in large language models (LLMs) have demonstrated their impressive abilities in various reasoning and decision-making tasks. However, the quality and coherence of the reasoning process can still benefit from enhanced introspection and self-reflection. In this paper, we introduce Multiplex CoT (Chain of Thought), a method that enables LLMs to simulate a form of self-review while reasoning, by initiating double Chain of Thought (CoT) thinking. Multiplex CoT leverages the power of iterative reasoning, where the model generates an initial chain of thought and subsequently critiques and refines this reasoning with a second round of thought generation. This recursive approach allows for more coherent, logical, and robust answers, improving the overall decision-making process. We demonstrate how this method can be effectively implemented using simple prompt engineering in existing LLM architectures, achieving an effect similar to that of the Learning-Refinement Model (LRM) without the need for additional training. Additionally, we present a practical guide for implementing the method in Google Colab, enabling easy integration into real-world applications. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在各种推理和决策任务中展现出令人印象深刻的性能。然而，推理过程的质量和连贯性仍可从增强的内省和自我反思中受益。本文介绍了一种名为Multiplex CoT（链式思维）的方法，该方法允许LLMs在推理过程中模拟一种自我审查的形式，通过启动双重链式思维（CoT）思考实现这一点。Multiplex CoT利用迭代推理的力量，模型首先生成初始的链式思维，然后通过第二轮思维生成对其进行批判和修订。这种递归方法可以提高答案的连贯性、逻辑性和鲁棒性，从而改进整体的决策过程。我们展示了如何通过简单的提示工程技术在现有的LLM架构中有效地实施该方法，从而实现类似于学习精炼模型（LRM）的效果，无需额外的训练。此外，我们提供了一种实用指南，说明如何在Google Colab中实施该方法，便于将其无缝集成到实际应用中。 

---
# Dagger Behind Smile: Fool LLMs with a Happy Ending Story 

**Title (ZH)**: 微笑背后的伪装：用一个圆满结局的故事愚弄LLMs 

**Authors**: Xurui Song, Zhixin Xie, Shuo Huai, Jiayi Kong, Jun Luo  

**Link**: [PDF](https://arxiv.org/pdf/2501.13115)  

**Abstract**: The wide adoption of Large Language Models (LLMs) has attracted significant attention from \textit{jailbreak} attacks, where adversarial prompts crafted through optimization or manual design exploit LLMs to generate malicious content. However, optimization-based attacks have limited efficiency and transferability, while manual designs are either easily detectable or demand intricate interactions with LLMs. In this paper, we first point out a novel perspective for jailbreak attacks: LLMs are more responsive to \textit{positive} prompts. Based on this, we deploy Happy Ending Attack (HEA) to wrap up a malicious request in a scenario template involving a positive prompt formed mainly via a \textit{happy ending}, it thus fools LLMs into jailbreaking either immediately or at a follow-up malicious request. This has made HEA both efficient and effective, as it requires only up to two steps to fully jailbreak LLMs. Extensive experiments show that our HEA can successfully jailbreak on state-of-the-art LLMs, including GPT-4o, Llama3-70b, Gemini-pro, and achieves 88.79\% Attack Success Rate on average. We also provide potential quantitative explanations for the success of HEA. 

**Abstract (ZH)**: 大规模语言模型（LLMs）的广泛应用引发了对“逃逸攻击”(jailbreak attacks)的广泛关注，这种攻击通过优化或手动设计的对抗提示利用LLMs生成恶意内容。然而，基于优化的攻击效率有限且缺乏可移植性，而手动设计要么容易被检测到，要么需要复杂的与LLMs的交互。在本文中，我们首先指出“逃逸攻击”的一个新颖视角：LLMs对积极正面的提示更为敏感。基于这一观点，我们部署了Happy Ending Attack（喜 ending 攻击）来将恶意请求嵌入到包含主要通过“完美结局”形成的积极正面提示的场景模板中。这样一来，在第一次请求或随后的恶意请求中，该攻击可以欺骗LLMs进行逃逸。这使HEA既高效又有效，因为它只需要两步即可实现LLMs的完全逃逸。大量的实验表明，我们的HEA能够成功地逃逸最先进的LLMs，包括GPT-4o、Llama3-70b、Gemini-pro，并且平均成功率为88.79%。我们还提供了HEA成功潜在的定量解释。 

---
# On the Reasoning Capacity of AI Models and How to Quantify It 

**Title (ZH)**: AI模型的推理能力及其度量方法研究 

**Authors**: Santosh Kumar Radha, Oktay Goktas  

**Link**: [PDF](https://arxiv.org/pdf/2501.13833)  

**Abstract**: Recent advances in Large Language Models (LLMs) have intensified the debate surrounding the fundamental nature of their reasoning capabilities. While achieving high performance on benchmarks such as GPQA and MMLU, these models exhibit limitations in more complex reasoning tasks, highlighting the need for more rigorous evaluation methodologies. We propose a novel phenomenological approach that goes beyond traditional accuracy metrics to probe the underlying mechanisms of model behavior, establishing a framework that could broadly impact how we analyze and understand AI systems. Using positional bias in multiple-choice reasoning tasks as a case study, we demonstrate how systematic perturbations can reveal fundamental aspects of model decision-making. To analyze these behaviors, we develop two complementary phenomenological models: a Probabilistic Mixture Model (PMM) that decomposes model responses into reasoning, memorization, and guessing components and an Information-Theoretic Consistency (ITC) analysis that quantifies the relationship between model confidence and strategy selection. Through controlled experiments on reasoning benchmarks, we show that true reasoning remains challenging for current models, with apparent success often relying on sophisticated combinations of memorization and pattern matching rather than genuine logical deduction. More fundamentally, we demonstrate that accuracy alone often overstates a model's reasoning abilities, as model behavior can be characterized through underlying mechanisms in the phase space of cognitive strategies, revealing how models dynamically balance different approaches when responding to queries. This framework enables quantitative criteria for real-world deployments, allowing applications to specify reliability thresholds based on strategy distributions rather than aggregate performance metrics. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的最新进展加剧了对其推理能力本质的辩论。尽管在GPQA和MMLU等基准测试中表现出色，这些模型在更复杂的推理任务中仍存在局限性，这突显了需要采用更严格的评估方法的必要性。我们提出了一种新颖的现象学方法，超越了传统准确度指标，以探查模型行为背后的机制，建立了一个可能广泛影响我们分析和理解人工智能系统的方法论框架。

我们以多项选择推理任务中的位置偏差为案例研究，展示了系统性扰动如何揭示模型决策的基本方面。为了分析这些行为，我们开发了两种互补的现象学模型：一种是概率混合模型（PMM），该模型将模型响应分解为推理、记忆和猜测三个部分，以及一种信息论一致性（ITC）分析，量化了模型置信度与其策略选择之间的关系。通过推理基准的受控实验，我们表明，当前模型在真正推理方面仍然面临挑战，看似成功往往依赖于复杂的记忆和模式匹配的组合，而不是真正的逻辑推导。

更根本的是，我们证明了仅依赖准确率往往高估了模型的推理能力，因为模型行为可以通过认知策略相空间中的底层机制来刻画，揭示了模型在回复查询时如何动态平衡不同方法。该框架提供了定量标准，使实际部署的软件可以基于策略分布而非综合性能指标来确定可靠性阈值，从而允许应用程序根据各自的需求制定具体的可靠性标准。 

---
# Explainable XR: Understanding User Behaviors of XR Environments using LLM-assisted Analytics Framework 

**Title (ZH)**: 可解释的XR：使用LLM辅助分析框架理解XR环境中的用户行为 

**Authors**: Yoonsang Kim, Zainab Aamir, Mithilesh Singh, Saeed Boorboor, Klaus Mueller, Arie E. Kaufman  

**Link**: [PDF](https://arxiv.org/pdf/2501.13778)  

**Abstract**: We present Explainable XR, an end-to-end framework for analyzing user behavior in diverse eXtended Reality (XR) environments by leveraging Large Language Models (LLMs) for data interpretation assistance. Existing XR user analytics frameworks face challenges in handling cross-virtuality - AR, VR, MR - transitions, multi-user collaborative application scenarios, and the complexity of multimodal data. Explainable XR addresses these challenges by providing a virtuality-agnostic solution for the collection, analysis, and visualization of immersive sessions. We propose three main components in our framework: (1) A novel user data recording schema, called User Action Descriptor (UAD), that can capture the users' multimodal actions, along with their intents and the contexts; (2) a platform-agnostic XR session recorder, and (3) a visual analytics interface that offers LLM-assisted insights tailored to the analysts' perspectives, facilitating the exploration and analysis of the recorded XR session data. We demonstrate the versatility of Explainable XR by demonstrating five use-case scenarios, in both individual and collaborative XR applications across virtualities. Our technical evaluation and user studies show that Explainable XR provides a highly usable analytics solution for understanding user actions and delivering multifaceted, actionable insights into user behaviors in immersive environments. 

**Abstract (ZH)**: 我们提出了可解释的扩展现实（Explainable XR），这是一个端到端框架，利用大语言模型（LLMs）进行数据解释辅助，以分析在多种扩展现实（XR）环境中的用户行为。现有的XR用户分析框架在处理AR、VR、MR之间的转换、多用户协作应用场景以及多模态数据的复杂性时存在挑战。Explainable XR通过提供一种与虚拟现实无关的解决方案来解决这些挑战，该解决方案用于收集、分析和可视化沉浸式会话。我们提出了框架中的三个主要组件：（1）一种新的用户数据记录模式，称为用户动作描述符（UAD），能够捕捉用户的多模态行为及其意图和上下文；（2）一个平台无关的XR会话记录器；以及（3）一种基于大语言模型的视觉分析界面，提供定制化的分析洞见，以便分析师探索和分析记录的XR会话数据。我们通过在不同虚拟现实环境中的个体和协作XR应用中展示五个用例场景，展示了Explainable XR的灵活性。我们的技术评估和用户研究显示，Explainable XR提供了一个高度可用的分析解决方案，用于理解和提供关于沉浸式环境中用户行为多方面的、可操作的洞察。 

---
# ReasVQA: Advancing VideoQA with Imperfect Reasoning Process 

**Title (ZH)**: ReasVQA：改进推理过程的视频问答研究 

**Authors**: Jianxin Liang, Xiaojun Meng, Huishuai Zhang, Yueqian Wang, Jiansheng Wei, Dongyan Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2501.13536)  

**Abstract**: Video Question Answering (VideoQA) is a challenging task that requires understanding complex visual and temporal relationships within videos to answer questions accurately. In this work, we introduce \textbf{ReasVQA} (Reasoning-enhanced Video Question Answering), a novel approach that leverages reasoning processes generated by Multimodal Large Language Models (MLLMs) to improve the performance of VideoQA models. Our approach consists of three phases: reasoning generation, reasoning refinement, and learning from reasoning. First, we generate detailed reasoning processes using additional MLLMs, and second refine them via a filtering step to ensure data quality. Finally, we use the reasoning data, which might be in an imperfect form, to guide the VideoQA model via multi-task learning, on how to interpret and answer questions based on a given video. We evaluate ReasVQA on three popular benchmarks, and our results establish new state-of-the-art performance with significant improvements of +2.9 on NExT-QA, +7.3 on STAR, and +5.9 on IntentQA. Our findings demonstrate the supervising benefits of integrating reasoning processes into VideoQA. Further studies validate each component of our method, also with different backbones and MLLMs, and again highlight the advantages of this simple but effective method. We offer a new perspective on enhancing VideoQA performance by utilizing advanced reasoning techniques, setting a new benchmark in this research field. 

**Abstract (ZH)**: 视频问答（Video Question Answering, VideoQA）是一项具有挑战性的任务，要求理解视频中的复杂视觉和时间关系以准确回答问题。在本工作中，我们提出了一种新的方法 \textbf{ReasVQA}（增强推理的视频问答），该方法利用多模态大型语言模型（MLLMs）生成的推理过程来提高VideoQA模型的性能。我们的方法分为三个阶段：推理生成、推理优化以及从推理中学习。首先，我们使用额外的MLLM生成详细的推理过程，然后通过筛选步骤进一步优化推理以确保数据质量。最后，我们利用这些可能不完美的推理数据通过多任务学习来指导VideoQA模型，使其如何根据给定的视频理解和回答问题。我们使用ReasVQA在三个流行的基准测试上进行评估，实验结果表明，其在NExT-QA、STAR和IntentQA三个基准上的表现均显著优于现有方法，分别提高了2.9%、7.3%和5.9%。我们的研究结果证实了在VideoQA中整合推理过程的监督优势。进一步的研究验证了我们方法中每个组件的优势，并在不同的骨干网络和MLLM下再次突显了此方法的简单而有效的优点。我们提出了一种新的视角，即通过利用先进的推理技术来增强VideoQA性能，并为该研究领域设立了新的基准。 

---
# CRPO: Confidence-Reward Driven Preference Optimization for Machine Translation 

**Title (ZH)**: CRPO：基于置信度-奖励驱动的偏好优化在机器翻译中的应用 

**Authors**: Guofeng Cui, Pichao Wang, Yang Liu, Zemian Ke, Zhu Liu, Vimal Bhat  

**Link**: [PDF](https://arxiv.org/pdf/2501.13927)  

**Abstract**: Large language models (LLMs) have shown great potential in natural language processing tasks, but their application to machine translation (MT) remains challenging due to pretraining on English-centric data and the complexity of reinforcement learning from human feedback (RLHF). Direct Preference Optimization (DPO) has emerged as a simpler and more efficient alternative, but its performance depends heavily on the quality of preference data. To address this, we propose Confidence-Reward driven Preference Optimization (CRPO), a novel method that combines reward scores with model confidence to improve data selection for fine-tuning. CRPO selects challenging sentence pairs where the model is uncertain or underperforms, leading to more effective learning. While primarily designed for LLMs, CRPO also generalizes to encoder-decoder models like NLLB, demonstrating its versatility. Empirical results show that CRPO outperforms existing methods such as RS-DPO, RSO and MBR score in both translation accuracy and data efficiency. 

**Abstract (ZH)**: 大语言模型（LLMs）在自然语言处理任务中展现出了巨大的潜力，但在机器翻译（MT）中的应用仍然具有挑战性，这主要是由于其在以英语为中心的数据上进行预训练，以及从人类反馈中进行强化学习（RLHF）的复杂性。直接偏好优化（DPO）作为一种更简单、更高效的替代方案已经出现，但其性能高度依赖于偏好数据的质量。为了解决这个问题，我们提出了一种新的方法——信心-奖励驱动的偏好优化（CRPO），该方法结合了奖励分数与模型信心来改进微调所需数据的选择。CRPO选择那些模型不确定或表现不佳的挑战性句子对，从而提高学习效果。尽管主要设计用于LLMs，CRPO也适用于如NLLB这类编码器-解码器模型，显示了其广泛的适用性。实验结果表明，CRPO在翻译准确性和数据效率方面均优于现有方法，如RS-DPO、RSO和MBR评分。 

---
# EventVL: Understand Event Streams via Multimodal Large Language Model 

**Title (ZH)**: 事件VL：通过多模态大型语言模型理解事件流 

**Authors**: Pengteng Li, Yunfan Lu, Pinghao Song, Wuyang Li, Huizai Yao, Hui Xiong  

**Link**: [PDF](https://arxiv.org/pdf/2501.13707)  

**Abstract**: The event-based Vision-Language Model (VLM) recently has made good progress for practical vision tasks. However, most of these works just utilize CLIP for focusing on traditional perception tasks, which obstruct model understanding explicitly the sufficient semantics and context from event streams. To address the deficiency, we propose EventVL, the first generative event-based MLLM (Multimodal Large Language Model) framework for explicit semantic understanding. Specifically, to bridge the data gap for connecting different modalities semantics, we first annotate a large event-image/video-text dataset, containing almost 1.4 million high-quality pairs of data, which enables effective learning across various scenes, e.g., drive scene or human motion. After that, we design Event Spatiotemporal Representation to fully explore the comprehensive information by diversely aggregating and segmenting the event stream. To further promote a compact semantic space, Dynamic Semantic Alignment is introduced to improve and complete sparse semantic spaces of events. Extensive experiments show that our EventVL can significantly surpass existing MLLM baselines in event captioning and scene description generation tasks. We hope our research could contribute to the development of the event vision community. 

**Abstract (ZH)**: 基于事件的视觉-语言模型（VLM）近期在实际视觉任务中取得了良好进展。然而，大多数这些工作仅仅利用CLIP来专注于传统的感知任务，这阻碍了模型从事件流中明确理解足够的语义和上下文。为了解决这一缺陷，我们提出了一种名为EventVL的生成型事件基多模大型语言模型（Multimodal Large Language Model, MLLM）框架，旨在实现显式的语义理解。具体而言，为了弥合跨不同模态语义的数据缺口，我们首先标注了一个包含近140万高质量数据对的大规模事件-图像/视频-文本数据集，这些数据使模型能够有效地在各种场景中学习，例如驾驶场景或人体动作。在此基础上，我们设计了一种事件时空表示方法，通过多样化的事件流聚合与分割，充分探索全面的信息。为进一步促进紧凑的语义空间，我们引入了动态语义对齐，以改善和补充事件的稀疏语义空间。通过广泛的实验，我们发现我们的EventVL在事件描述和场景描述生成任务中显著超越了现有的MLLM基线模型。我们希望我们的研究能够为事件视觉社区的发展做出贡献。 

---
# Adaptive Testing for LLM-Based Applications: A Diversity-based Approach 

**Title (ZH)**: 基于多样性的自适应测试方法：面向LLM的應用 

**Authors**: Juyeon Yoon, Robert Feldt, Shin Yoo  

**Link**: [PDF](https://arxiv.org/pdf/2501.13480)  

**Abstract**: The recent surge of building software systems powered by Large Language Models (LLMs) has led to the development of various testing frameworks, primarily focused on treating prompt templates as the unit of testing. Despite the significant costs associated with test input execution and output assessment, the curation of optimized test suites is yet overlooked in these tools, which calls for tailored test selection or prioritization strategies. In this paper, we show that diversity-based testing techniques, such as Adaptive Random Testing (ART) with appropriate string distance metrics, can be effectively applied to the testing of prompt templates. Our proposed adaptive testing approach adjusts the conventional ART process to this context by selecting new test inputs based on scores derived from existing test suite and their labelling results. Our results, obtained using various implementations that explore several string-based distances, confirm that our approach enables the discovery of failures with reduced testing budgets and promotes the generation of more varied outputs. 

**Abstract (ZH)**: 近年来，受大规模语言模型（LLMs）驱动的软件系统建设热潮，催生了各种测试框架，主要侧重于将提示模板视为测试单元。尽管测试输入执行和输出评估的成本较高，但这些工具在优化测试套件的维护方面仍被忽视，这需要定制化的测试选择或优先级策略。在本文中，我们展示了一种基于多样性的测试技术，如适当使用的字符串距离度量的自适应随机测试（ART），可以有效地应用于提示模板的测试。我们提出的一种自适应测试方法，通过利用现有测试套件及其标签结果的评分来选择新的测试输入，调整了传统的ART流程。通过多种实施的研究探索了几种字符串距离方法，我们的结果证实了这种方法能够在降低测试预算的情况下发现更多失败，并促进生成更多样化的输出。 

---