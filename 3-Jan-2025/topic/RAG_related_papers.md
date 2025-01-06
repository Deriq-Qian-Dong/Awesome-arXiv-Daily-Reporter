# ValuesRAG: Enhancing Cultural Alignment Through Retrieval-Augmented Contextual Learning 

**Title (ZH)**: ValuesRAG：通过检索增强上下文学习提高文化一致性 

**Authors**: Wonduk Seo, Zonghao Yuan, Yi Bu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01031)  

**Abstract**: Cultural values alignment in Large Language Models (LLMs) is a critical challenge due to their tendency to embed Western-centric biases from training data, leading to misrepresentations and fairness issues in cross-cultural contexts. Recent approaches, such as role-assignment and few-shot learning, often struggle with reliable cultural alignment as they heavily rely on pre-trained knowledge, lack scalability, and fail to capture nuanced cultural values effectively. To address these issues, we propose ValuesRAG, a novel and effective framework that applies Retrieval-Augmented Generation (RAG) with in-context learning to integrate cultural and demographic knowledge dynamically during text generation. Leveraging the World Values Survey (WVS) dataset, ValuesRAG first generates summaries of values for each individual. Subsequently, we curated several representative regional datasets to serve as test datasets and retrieve relevant summaries of values based on demographic features, followed by a reranking step to select the top-k relevant summaries. ValuesRAG consistently outperforms baseline methods, both in the main experiment and in the ablation study where only the values summary was provided, highlighting ValuesRAG's potential to foster culturally aligned AI systems and enhance the inclusivity of AI-driven applications. 

**Abstract (ZH)**: 大语言模型（LLMs）中的文化价值观对齐是一个关键挑战，因为它们倾向于从训练数据中嵌入以西方为中心的偏见，导致跨文化语境中的误表征和公平性问题。近年来，例如角色分配和少量示例学习等方法，在可靠的文化对齐方面往往遇到困难，因为这些方法严重依赖预训练知识，缺乏可扩展性，并且无法有效捕捉细微的文化价值观。为了解决这些问题，我们提出了一种名为ValuesRAG的新型且有效的框架，该框架结合使用检索增强生成（RAG）和上下文学习，在文本生成过程中动态集成文化与人口统计学知识。利用世界价值观调查（WVS）数据集，ValuesRAG 首先为每个个体生成价值观总结。随后，我们编制了一些代表性的区域数据集作为测试数据集，并根据人口统计特征检索相关价值观总结，然后通过重新排名步骤选择前k个最相关的总结。在主要实验和仅提供价值观总结的消融研究中，ValuesRAG 一致优于基线方法，这突显了ValuesRAG 在推动文化对齐的AI系统和增强AI驱动应用包容性方面的潜力。 

---
# Are LLMs effective psychological assessors? Leveraging adaptive RAG for interpretable mental health screening through psychometric practice 

**Title (ZH)**: 大规模语言模型在心理健康评估中的有效性：利用自适应检索增强技术实现可解释的心理测验筛查 

**Authors**: Federico Ravenda, Seyed Ali Bahrainian, Andrea Raballo, Antonietta Mira, Noriko Kando  

**Link**: [PDF](https://arxiv.org/pdf/2501.00982)  

**Abstract**: In psychological practice, standardized questionnaires serve as essential tools for assessing mental constructs (e.g., attitudes, traits, and emotions) through structured questions (aka items). With the increasing prevalence of social media platforms where users share personal experiences and emotions, researchers are exploring computational methods to leverage this data for rapid mental health screening. In this study, we propose a novel adaptive Retrieval-Augmented Generation (RAG) approach that completes psychological questionnaires by analyzing social media posts. Our method retrieves the most relevant user posts for each question in a psychological survey and uses Large Language Models (LLMs) to predict questionnaire scores in a zero-shot setting. Our findings are twofold. First we demonstrate that this approach can effectively predict users' responses to psychological questionnaires, such as the Beck Depression Inventory II (BDI-II), achieving performance comparable to or surpassing state-of-the-art models on Reddit-based benchmark datasets without relying on training data. Second, we show how this methodology can be generalized as a scalable screening tool, as the final assessment is systematically derived by completing standardized questionnaires and tracking how individual item responses contribute to the diagnosis, aligning with established psychometric practices. 

**Abstract (ZH)**: 在心理学实践中，标准化问卷是通过结构化问题（即项目）来评估心理构念（如态度、特质和情绪）的重要工具。随着社交媒体平台的普及，用户在此平台上分享个人经历和情绪，研究人员正在探索利用这些数据进行快速心理健康筛查的计算方法。在本研究中，我们提出了一种新颖的自适应检索增强生成（RAG）方法，通过分析社交媒体帖子来完成心理学问卷。我们的方法会为心理调查问卷中的每个问题检索最相关的用户帖子，并利用大语言模型（LLMs）在零样本设置下预测问卷得分。我们的发现包括两个方面：首先，我们表明该方法能有效预测用户对心理问卷的反应，如贝克抑郁量表第二版（BDI-II），在基于Reddit的基准数据集上的性能达到了或超越了最先进的模型，且无需依赖训练数据。其次，我们展示了该方法作为可扩展筛查工具的普适性，通过完成标准化问卷并追踪各个项目反应对诊断的影响，系统地得出最终评估结果，这与传统的心理测量实践相一致。 

---
# TrustRAG: Enhancing Robustness and Trustworthiness in RAG 

**Title (ZH)**: TrustRAG：提高RAG模型鲁棒性和可信度 

**Authors**: Huichi Zhou, Kin-Hei Lee, Zhonghao Zhan, Yue Chen, Zhenhao Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.00879)  

**Abstract**: Retrieval-Augmented Generation (RAG) systems enhance large language models (LLMs) by integrating external knowledge sources, enabling more accurate and contextually relevant responses tailored to user queries. However, these systems remain vulnerable to corpus poisoning attacks that can significantly degrade LLM performance through the injection of malicious content. To address these challenges, we propose TrustRAG, a robust framework that systematically filters compromised and irrelevant content before it reaches the language model. Our approach implements a two-stage defense mechanism: first, it employs K-means clustering to identify potential attack patterns in retrieved documents based on their semantic embeddings, effectively isolating suspicious content. Second, it leverages cosine similarity and ROUGE metrics to detect malicious documents while resolving discrepancies between the model's internal knowledge and external information through a self-assessment process. TrustRAG functions as a plug-and-play, training-free module that integrates seamlessly with any language model, whether open or closed-source, maintaining high contextual relevance while strengthening defenses against attacks. Through extensive experimental validation, we demonstrate that TrustRAG delivers substantial improvements in retrieval accuracy, efficiency, and attack resistance compared to existing approaches across multiple model architectures and datasets. We have made TrustRAG available as open-source software at \url{this https URL}. 

**Abstract (ZH)**: 检索增强生成（RAG）系统通过整合外部知识源来强化大型语言模型（LLMs），从而使模型能够提供更准确和上下文相关的响应，更好地满足用户查询的需求。然而，这些系统仍然容易受到语料库投毒攻击的影响，这种攻击可以通过注入恶意内容显著降低LLM的性能。为了解决这些问题，我们提出了TrustRAG，这是一个稳健的框架，能够系统性地过滤掉被篡改和无关的内容，从而防止其被传递给语言模型。该方法采用两阶段的防御机制：首先，使用K-means聚类根据文档的语义嵌入识别潜在的攻击模式，从而有效隔离可疑内容；其次，利用余弦相似度和ROUGE指标来检测恶意文档，并通过模型内知识与外部信息之间的自我评估过程解决两者之间的不一致。TrustRAG作为插件式、无需训练的模块，能够无缝集成到任何语言模型中，无论其是开源还是闭源版本，同时保持高度的相关性并增强对抗攻击的能力。通过广泛的实验验证，我们证明了TrustRAG在多个模型架构和数据集中，在检索准确性、效率和攻击抵抗力方面都带来了显著改进，相比于现有方法具有明显优势。我们已将TrustRAG以开源软件的形式提供，并可以在 \url{this https URL} 下载。 

---
# Decoding the Flow: CauseMotion for Emotional Causality Analysis in Long-form Conversations 

**Title (ZH)**: 解码流变：CauseMotion在长篇对话中情感因果关系分析中的应用 

**Authors**: Yuxuan Zhang, Yulong Li, Zichen Yu, Feilong Tang, Zhixiang Lu, Chong Li, Kang Dang, Jionglong Su  

**Link**: [PDF](https://arxiv.org/pdf/2501.00778)  

**Abstract**: Long-sequence causal reasoning seeks to uncover causal relationships within extended time series data but is hindered by complex dependencies and the challenges of validating causal links. To address the limitations of large-scale language models (e.g., GPT-4) in capturing intricate emotional causality within extended dialogues, we propose CauseMotion, a long-sequence emotional causal reasoning framework grounded in Retrieval-Augmented Generation (RAG) and multimodal fusion. Unlike conventional methods relying only on textual information, CauseMotion enriches semantic representations by incorporating audio-derived features-vocal emotion, emotional intensity, and speech rate-into textual modalities. By integrating RAG with a sliding window mechanism, it effectively retrieves and leverages contextually relevant dialogue segments, thus enabling the inference of complex emotional causal chains spanning multiple conversational turns. To evaluate its effectiveness, we constructed the first benchmark dataset dedicated to long-sequence emotional causal reasoning, featuring dialogues with over 70 turns. Experimental results demonstrate that the proposed RAG-based multimodal integrated approach, the efficacy of substantially enhances both the depth of emotional understanding and the causal inference capabilities of large-scale language models. A GLM-4 integrated with CauseMotion achieves an 8.7% improvement in causal accuracy over the original model and surpasses GPT-4o by 1.2%. Additionally, on the publicly available DiaASQ dataset, CauseMotion-GLM-4 achieves state-of-the-art results in accuracy, F1 score, and causal reasoning accuracy. 

**Abstract (ZH)**: 长序列因果推理旨在揭示扩展时间序列数据中的因果关系，但由于复杂的依赖关系和验证因果链接的挑战而受到限制。为了克服大型语言模型（如GPT-4）在捕捉扩展对话中复杂情感因果关系方面的局限性，我们提出了CauseMotion，这是一种基于检索增强生成（RAG）和多模态融合的长序列情感因果推理框架。与仅依赖文本信息的传统方法不同，CauseMotion通过将音频提取的特征（即声情、情感强度和语速）融入文本模态中，丰富了语义表示。通过将RAG与滑动窗口机制结合，它有效地检索和利用上下文相关的话语片段，从而能够推断跨越多个对话回合的复杂情感因果链。为了评估其有效性，我们构建了首个专注于长序列情感因果推理的基准数据集，其中包含超过70个回合的对话。实验结果表明，基于RAG的多模态集成方法显著增强了大型语言模型的情感理解深度和因果推理能力。集成CauseMotion的GLM-4在因果准确性上比原模型提升了8.7%，并且超越了GPT-4o 1.2%。此外，在公开可用的DiaASQ数据集上，CauseMotion-GLM-4在准确率、F1分数和因果推理准确性方面达到了最先进的性能。 

---
# RAG-Instruct: Boosting LLMs with Diverse Retrieval-Augmented Instructions 

**Title (ZH)**: RAG-Instruct：通过多样化检索增强指令提升大型语言模型 

**Authors**: Wanlong Liu, Junying Chen, Ke Ji, Li Zhou, Wenyu Chen, Benyou Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00353)  

**Abstract**: Retrieval-Augmented Generation (RAG) has emerged as a key paradigm for enhancing large language models (LLMs) by incorporating external knowledge. However, current RAG methods face two limitations: (1) they only cover limited RAG scenarios. (2) They suffer from limited task diversity due to the lack of a general RAG dataset. To address these limitations, we propose RAG-Instruct, a general method for synthesizing diverse and high-quality RAG instruction data based on any source corpus. Our approach leverages (1) five RAG paradigms, which encompass diverse query-document relationships, and (2) instruction simulation, which enhances instruction diversity and quality by utilizing the strengths of existing instruction datasets. Using this method, we construct a 40K instruction dataset from Wikipedia, comprehensively covering diverse RAG scenarios and tasks. Experiments demonstrate that RAG-Instruct effectively enhances LLMs' RAG capabilities, achieving strong zero-shot performance and significantly outperforming various RAG baselines across a diverse set of tasks. RAG-Instruct is publicly available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）已经成为通过引入外部知识来增强大语言模型（LLMs）的关键范式。然而，现有的RAG方法面临两个局限：（1）它们仅涵盖有限的RAG场景。（2）由于缺乏通用的RAG数据集，导致任务多样性有限。为了克服这些局限，我们提出了RAG-Instruct，这是一种基于任意来源语料库合成多样且高质量RAG指令数据的一般方法。我们的方法利用了以下两点：（1）五种RAG范式，涵盖了多样化的查询-文档关系；（2）指令模拟，通过利用现有指令数据集的长处来增强指令的多样性和质量。利用这种方法，我们从Wikipedia中构建了一个包含40,000条指令的数据集，全面覆盖了多样化的RAG场景和任务。实验表明，RAG-Instruct有效地增强了LLMs的RAG能力，实现了强大的零样本性能，并且在一系列任务上显著优于各种RAG基线方法。RAG-Instruct已在以下网址公开提供：[这里](this https URL)。 

---
# MAIN-RAG: Multi-Agent Filtering Retrieval-Augmented Generation 

**Title (ZH)**: MAIN-RAG：多代理过滤检索增强生成 

**Authors**: Chia-Yuan Chang, Zhimeng Jiang, Vineeth Rakesh, Menghai Pan, Chin-Chia Michael Yeh, Guanchu Wang, Mingzhi Hu, Zhichao Xu, Yan Zheng, Mahashweta Das, Na Zou  

**Link**: [PDF](https://arxiv.org/pdf/2501.00332)  

**Abstract**: Large Language Models (LLMs) are becoming essential tools for various natural language processing tasks but often suffer from generating outdated or incorrect information. Retrieval-Augmented Generation (RAG) addresses this issue by incorporating external, real-time information retrieval to ground LLM responses. However, the existing RAG systems frequently struggle with the quality of retrieval documents, as irrelevant or noisy documents degrade performance, increase computational overhead, and undermine response reliability. To tackle this problem, we propose Multi-Agent Filtering Retrieval-Augmented Generation (MAIN-RAG), a training-free RAG framework that leverages multiple LLM agents to collaboratively filter and score retrieved documents. Specifically, MAIN-RAG introduces an adaptive filtering mechanism that dynamically adjusts the relevance filtering threshold based on score distributions, effectively minimizing noise while maintaining high recall of relevant documents. The proposed approach leverages inter-agent consensus to ensure robust document selection without requiring additional training data or fine-tuning. Experimental results across four QA benchmarks demonstrate that MAIN-RAG consistently outperforms traditional RAG approaches, achieving a 2-11% improvement in answer accuracy while reducing the number of irrelevant retrieved documents. Quantitative analysis further reveals that our approach achieves superior response consistency and answer accuracy over baseline methods, offering a competitive and practical alternative to training-based solutions. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已成为各种自然语言处理任务的重要工具，但常常会生成过时或不准确的信息。检索增强生成（RAG）通过结合外部的实时信息检索来确保LLM回答的准确性和相关性，解决了这一问题。然而，现有的RAG系统在检索文档的质量方面常常面临挑战，无关或噪声文档会降低性能、增加计算开销并削弱回答的可靠性。为了解决这一问题，我们提出了一种名为Multi-Agent Filtering Retrieval-Augmented Generation（MAIN-RAG）的无需训练的RAG框架，该框架利用多个LLM代理协作筛选和评估检索到的文档。具体来说，MAIN-RAG引入了一种自适应筛选机制，该机制会根据评分分布动态调整相关性筛选阈值，有效减少了噪声并保持了相关文档的高召回率。该方法利用代理间的共识来确保稳健的文档选择，而无需额外的训练数据或微调。在四个问答基准测试中的实验结果表明，MAIN-RAG 在回答准确性和减少无关检索文档数量方面始终优于传统的RAG方法。定量分析进一步表明，我们的方法在响应一致性和回答准确性方面优于基准方法，提供了基于训练的解决方案的有竞争力且实用的替代方案。 

---
# Retrieval-Augmented Generation with Graphs (GraphRAG) 

**Title (ZH)**: 基于图的检索增强生成（GraphRAG） 

**Authors**: Haoyu Han, Yu Wang, Harry Shomer, Kai Guo, Jiayuan Ding, Yongjia Lei, Mahantesh Halappanavar, Ryan A. Rossi, Subhabrata Mukherjee, Xianfeng Tang, Qi He, Zhigang Hua, Bo Long, Tong Zhao, Neil Shah, Amin Javari, Yinglong Xia, Jiliang Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00309)  

**Abstract**: Retrieval-augmented generation (RAG) is a powerful technique that enhances downstream task execution by retrieving additional information, such as knowledge, skills, and tools from external sources. Graph, by its intrinsic "nodes connected by edges" nature, encodes massive heterogeneous and relational information, making it a golden resource for RAG in tremendous real-world applications. As a result, we have recently witnessed increasing attention on equipping RAG with Graph, i.e., GraphRAG. However, unlike conventional RAG, where the retriever, generator, and external data sources can be uniformly designed in the neural-embedding space, the uniqueness of graph-structured data, such as diverse-formatted and domain-specific relational knowledge, poses unique and significant challenges when designing GraphRAG for different domains. Given the broad applicability, the associated design challenges, and the recent surge in GraphRAG, a systematic and up-to-date survey of its key concepts and techniques is urgently desired. Following this motivation, we present a comprehensive and up-to-date survey on GraphRAG. Our survey first proposes a holistic GraphRAG framework by defining its key components, including query processor, retriever, organizer, generator, and data source. Furthermore, recognizing that graphs in different domains exhibit distinct relational patterns and require dedicated designs, we review GraphRAG techniques uniquely tailored to each domain. Finally, we discuss research challenges and brainstorm directions to inspire cross-disciplinary opportunities. Our survey repository is publicly maintained at this https URL. 

**Abstract (ZH)**: 基于检索增强生成（RAG）是一种强大的技术，它通过从外部来源检索额外的信息（如知识、技能和工具）来增强下游任务的执行。由于其基本的“节点通过边连接”的特性，图能够编码大量的异构和关系信息，使其成为RAG在大量实际应用中的宝贵资源。因此，我们最近见证了越来越多的注意力被集中在将图与RAG结合使用上，即GraphRAG。然而，与传统RAG不同，在传统RAG中检索器、生成器和外部数据源可以均匀地设计在神经嵌入空间中，图结构数据的独特性，如多种格式和特定领域的关系知识，为设计适用于不同领域的GraphRAG带来了独特而重要的挑战。考虑到其广泛的应用领域、相关的设计挑战以及GraphRAG的最近增长，系统地且最新的GraphRAG的关键概念和技术的综述是迫切需要的。出于这一动机，我们提供了一篇全面且最新的GraphRAG综述。我们的综述首先提出了一种完整的GraphRAG框架，通过定义其关键组件，包括查询处理器、检索器、组织器、生成器和数据源。此外，考虑到不同领域的图表现出不同的关系模式并需要专门的设计，我们回顾了针对每个领域的GraphRAG技术。最后，我们讨论了研究挑战并提出了跨学科机遇的方向。我们的综述库在此网址公开维护：[https://github.com/your-repo-name]。 

---