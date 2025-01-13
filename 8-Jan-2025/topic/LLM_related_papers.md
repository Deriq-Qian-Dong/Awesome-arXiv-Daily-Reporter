# Influences on LLM Calibration: A Study of Response Agreement, Loss Functions, and Prompt Styles 

**Title (ZH)**: LLM校准的影响因素：关于响应一致性、损失函数和提示风格的研究 

**Authors**: Yuxi Xia, Pedro Henrique Luz de Araujo, Klim Zaporojets, Benjamin Roth  

**Link**: [PDF](https://arxiv.org/pdf/2501.03991)  

**Abstract**: Calibration, the alignment between model confidence and prediction accuracy, is critical for the reliable deployment of large language models (LLMs). Existing works neglect to measure the generalization of their methods to other prompt styles and different sizes of LLMs. To address this, we define a controlled experimental setting covering 12 LLMs and four prompt styles. We additionally investigate if incorporating the response agreement of multiple LLMs and an appropriate loss function can improve calibration performance. Concretely, we build Calib-n, a novel framework that trains an auxiliary model for confidence estimation that aggregates responses from multiple LLMs to capture inter-model agreement. To optimize calibration, we integrate focal and AUC surrogate losses alongside binary cross-entropy. Experiments across four datasets demonstrate that both response agreement and focal loss improve calibration from baselines. We find that few-shot prompts are the most effective for auxiliary model-based methods, and auxiliary models demonstrate robust calibration performance across accuracy variations, outperforming LLMs' internal probabilities and verbalized confidences. These insights deepen the understanding of influence factors in LLM calibration, supporting their reliable deployment in diverse applications. 

**Abstract (ZH)**: 校准，即模型的信心与预测准确性之间的对齐，对于大型语言模型（LLMs）的可靠部署至关重要。现有研究在衡量其方法对其他提示风格和其他大小的LLMs的一般化能力方面存在不足。为解决这一问题，我们定义了一个受控实验设置，涵盖了12种LLM和四种提示风格。我们还进一步探讨了是否可以结合多个LLM的回答一致性以及适当的损失函数来提升校准性能。具体而言，我们构建了一个名为Calib-n的新框架，该框架训练一个辅助模型以估计多种LLM的回答汇总后的共识。为了优化校准，我们结合了聚焦损失和AUC代用品损失与二元交叉熵损失。在四个数据集上的实验表明，回答一致性与聚焦损失都能改进校准性能。我们发现，少量示例的提示对基于辅助模型的方法最为有效，而辅助模型在不同准确度变化下的校准性能表现稳定，优于LLM内部概率和口头表述的信心度。这些见解加深了对LLM校准影响因素的理解，支持其在各种应用中的可靠部署。 

---
# AlphaPO -- Reward shape matters for LLM alignment 

**Title (ZH)**: AlphaPO —— 奖励形状对于LLM对齐至关重要 

**Authors**: Aman Gupta, Shao Tang, Qingquan Song, Sirou Zhu, Jiwoo Hong, Ankan Saha, Viral Gupta, Noah Lee, Eunki Kim, Jason Zhu, Natesh Pillai, S. Sathiya Keerthi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03884)  

**Abstract**: Reinforcement Learning with Human Feedback (RLHF) and its variants have made huge strides toward the effective alignment of large language models (LLMs) to follow instructions and reflect human values. More recently, Direct Alignment Algorithms (DAAs) have emerged in which the reward modeling stage of RLHF is skipped by characterizing the reward directly as a function of the policy being learned. Examples include Direct Preference Optimization (DPO) and Simple Preference Optimization (SimPO). These methods often suffer from likelihood displacement, a phenomenon by which the probabilities of preferred responses are often reduced undesirably.
In this paper, we argue that, for DAAs the reward (function) shape matters. We introduce AlphaPO, a new DAA method that leverages an $\alpha$-parameter to help change the shape of the reward function beyond the standard log reward. AlphaPO helps maintain fine-grained control over likelihood displacement and over-optimization. Compared to SimPO, one of the best performing DAAs, AlphaPO leads to about 7\% to 10\% relative improvement in alignment performance for the instruct versions of Mistral-7B and Llama3-8B. The analysis and results presented highlight the importance of the reward shape, and how one can systematically change it to affect training dynamics, as well as improve alignment performance. 

**Abstract (ZH)**: 强化学习与人类反馈（RLHF）及其变体在使大型语言模型（LLMs）有效遵循指令和反映人类价值观方面取得了巨大的进步。最近，直接对齐算法（DAAs）的出现通过直接将奖励建模为所学习策略的函数，省略了RLHF中的奖励建模阶段。这些方法包括直接偏好优化（DPO）和简单偏好优化（SimPO）。这些方法通常会遭受似然性置换的现象，即优选响应的概率往往会不必要地减少。

在本文中，我们认为，对于DAAs而言，奖励（函数）的形状很重要。我们提出了AlphaPO，这是一种新的DAAs方法，利用一个$\alpha$参数来帮助改变奖励函数的形状，超越了标准的对数奖励。AlphaPO有助于保持对似然性置换和过度优化的精细控制。与SimPO（目前已知表现最好的DAAs之一）相比，AlphaPO在Mistral-7B和Llama3-8B的指令版本中的对齐性能相对提高了约7%到10%。分析和结果表明了奖励形状的重要性，以及如何系统地改变它以影响训练动态，并提高对齐性能。 

---
# Progressive Document-level Text Simplification via Large Language Models 

**Title (ZH)**: 通过大型语言模型实现逐步文档级文本简化 

**Authors**: Dengzhao Fang, Jipeng Qiang, Yi Zhu, Yunhao Yuan, Wei Li, Yan Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03857)  

**Abstract**: Research on text simplification has primarily focused on lexical and sentence-level changes. Long document-level simplification (DS) is still relatively unexplored. Large Language Models (LLMs), like ChatGPT, have excelled in many natural language processing tasks. However, their performance on DS tasks is unsatisfactory, as they often treat DS as merely document summarization. For the DS task, the generated long sequences not only must maintain consistency with the original document throughout, but complete moderate simplification operations encompassing discourses, sentences, and word-level simplifications. Human editors employ a hierarchical complexity simplification strategy to simplify documents. This study delves into simulating this strategy through the utilization of a multi-stage collaboration using LLMs. We propose a progressive simplification method (ProgDS) by hierarchically decomposing the task, including the discourse-level, topic-level, and lexical-level simplification. Experimental results demonstrate that ProgDS significantly outperforms existing smaller models or direct prompting with LLMs, advancing the state-of-the-art in the document simplification task. 

**Abstract (ZH)**: 文本简化研究主要集中在词汇和句级变化上。长文档级简化（DS）仍然相对未被充分探索。大型语言模型（LLMs），如ChatGPT，在许多自然语言处理任务中表现出色。然而，在DS任务上的表现不尽如人意，因为它们通常将DS视为文档摘要。对于DS任务而言，生成的长序列不仅需要在整个文档中保持一致性，还需执行涵盖话语、句子和词汇级简化在内的适度简化操作。人类编辑者通过层级复杂性简化策略来简化文档。本研究通过利用多阶段LLMs协作，尝试模拟这一策略。我们通过层级分解任务（包括话语级、主题级和词汇级简化）提出了一种逐步简化方法（ProgDS）。实验结果表明，ProgDS 在文档简化任务中的表现显著优于现有较小的模型或直接使用LLMs进行提示，推动了该领域的技术前沿。 

---
# Can LLMs Design Good Questions Based on Context? 

**Title (ZH)**: 基于上下文，LLM能够设计出好的问题吗？ 

**Authors**: Yueheng Zhang, Xiaoyuan Liu, Yiyou Sun, Atheer Alharbi, Hend Alzahrani, Basel Alomair, Dawn Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.03491)  

**Abstract**: This paper evaluates questions generated by LLMs from context, comparing them to human-generated questions across six dimensions. We introduce an automated LLM-based evaluation method, focusing on aspects like question length, type, context coverage, and answerability. Our findings highlight unique characteristics of LLM-generated questions, contributing insights that can support further research in question quality and downstream applications. 

**Abstract (ZH)**: 本文从六个维度评估由大规模语言模型（LLM）生成的问题，将这些问题与人工生成的问题进行比较。我们引入了一种基于自动LLM的评估方法，重点关注诸如问题长度、类型、上下文覆盖和可回答性等方面。我们的研究结果揭示了LLM生成问题的独特特征，为后续关于问题质量的研究以及下游应用提供了宝贵的见解。 

---
# Reading with Intent -- Neutralizing Intent 

**Title (ZH)**: 《带着目的阅读——消除意图的阅读》

这个翻译旨在忠实于原文含义，并符合学术论文的规范。如果有特定的上下文或需要更详细的解释，请告知我。 

**Authors**: Benjamin Reichman, Adar Avsian, Larry Heck  

**Link**: [PDF](https://arxiv.org/pdf/2501.03475)  

**Abstract**: Queries to large language models (LLMs) can be divided into two parts: the instruction/question and the accompanying context. The context for retrieval-augmented generation (RAG) systems in most benchmarks comes from Wikipedia or Wikipedia-like texts which are written in a neutral and factual tone. However, when RAG systems retrieve internet-based content, they encounter text with diverse tones and linguistic styles, introducing challenges for downstream tasks. The Reading with Intent task addresses this issue by evaluating how varying tones in context passages affect model performance. Building on prior work that focused on sarcasm, we extend this paradigm by constructing a dataset where context passages are transformed to $11$ distinct emotions using a better synthetic data generation approach. Using this dataset, we train an emotion translation model to systematically adapt passages to specified emotional tones. The human evaluation shows that the LLM fine-tuned to become the emotion-translator benefited from the synthetically generated data. Finally, the emotion-translator is used in the Reading with Intent task to transform the passages to a neutral tone. By neutralizing the passages, it mitigates the challenges posed by sarcastic passages and improves overall results on this task by about $3\%$. 

**Abstract (ZH)**: 大规模语言模型（LLMs）的查询可以分为两部分：指令/问题和伴随的上下文。大多数基准测试中的检索增强生成（RAG）系统的上下文来源于维基百科或类似维基百科的文本，这些文本通常以中性和事实性的方式撰写。然而，当RAG系统检索网络内容时，会遇到具有多种语调和语言风格的文本，这为下游任务带来了挑战。《意图阅读》任务通过评估上下文段落中不同语调对模型性能的影响来应对这一问题。在此基础上，我们扩展了先前专注于讽刺的研究，通过更有效的合成数据生成方法构建了一个数据集，该数据集将上下文段落转换为11种不同的情绪。利用此数据集，我们训练了一个情绪翻译模型，使其系统地将段落转换为指定的情绪语调。人类评估表明，通过合成生成的数据微调的LLM从中有益。最后，将情绪翻译器应用于《意图阅读》任务，将段落转换成中性语调。通过中性化段落，它减轻了讽刺段落带来的挑战，并在该任务上整体提高了大约3%的性能。 

---
# ISSR: Iterative Selection with Self-Review for Vocabulary Test Distractor Generation 

**Title (ZH)**: ISSR：迭代选择与自我审查词汇测试干扰项生成方法 

**Authors**: Yu-Cheng Liu, An-Zi Yen  

**Link**: [PDF](https://arxiv.org/pdf/2501.03462)  

**Abstract**: Vocabulary acquisition is essential to second language learning, as it underpins all core language skills. Accurate vocabulary assessment is particularly important in standardized exams, where test items evaluate learners' comprehension and contextual use of words. Previous research has explored methods for generating distractors to aid in the design of English vocabulary tests. However, current approaches often rely on lexical databases or predefined rules, and frequently produce distractors that risk invalidating the question by introducing multiple correct options. In this study, we focus on English vocabulary questions from Taiwan's university entrance exams. We analyze student response distributions to gain insights into the characteristics of these test items and provide a reference for future research. Additionally, we identify key limitations in how large language models (LLMs) support teachers in generating distractors for vocabulary test design. To address these challenges, we propose the iterative selection with self-review (ISSR) framework, which makes use of a novel LLM-based self-review mechanism to ensure that the distractors remain valid while offering diverse options. Experimental results show that ISSR achieves promising performance in generating plausible distractors, and the self-review mechanism effectively filters out distractors that could invalidate the question. 

**Abstract (ZH)**: 词汇获取是第二语言学习的基石，因为它是所有核心语言技能的基础。准确的词汇评估在标准化考试中尤为重要，其中测试项目评估的是考生对词汇的理解和在语境中的使用能力。以往的研究探讨了生成干扰项的方法，以辅助设计英语词汇测试题。然而，当前的方法常常依赖于词汇数据库或预定义的规则，往往会产生一些干扰项，这些干扰项有可能导致问题无效化，引入多个正确选项。在本研究中，我们专注于台湾大学入学考试的英语词汇题目。我们分析了学生对题目答案的分布情况，以深入了解这些测试项目的特征，并为未来的研究提供参考。此外，我们还指出了大型语言模型（LLMs）在支持教师生成词汇测试题干扰项方面存在的关键局限性。为应对这些挑战，我们提出了迭代选择与自我审核（ISSR）框架。该框架利用了一种新颖的基于LLM的自我审核机制，以确保干扰项的有效性的同时提供多样化的选项。实验结果表明，ISSR 在生成合理干扰项方面取得了令人鼓舞的性能，而自我审核机制有效地筛选出了可能使问题无效化的干扰项。 

---
# Finding A Voice: Evaluating African American Dialect Generation for Chatbot Technology 

**Title (ZH)**: 寻找声音：评估非裔美国人口音生成技术在聊天机器人中的应用 

**Authors**: Sarah E. Finch, Ellie S. Paek, Sejung Kwon, Ikseon Choi, Jessica Wells, Rasheeta Chandler, Jinho D. Choi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03441)  

**Abstract**: As chatbots become increasingly integrated into everyday tasks, designing systems that accommodate diverse user populations is crucial for fostering trust, engagement, and inclusivity. This study investigates the ability of contemporary Large Language Models (LLMs) to generate African American Vernacular English (AAVE) and evaluates the impact of AAVE usage on user experiences in chatbot applications. We analyze the performance of three LLM families (Llama, GPT, and Claude) in producing AAVE-like utterances at varying dialect intensities and assess user preferences across multiple domains, including healthcare and education. Despite LLMs' proficiency in generating AAVE-like language, findings indicate that AAVE-speaking users prefer Standard American English (SAE) chatbots, with higher levels of AAVE correlating with lower ratings for a variety of characteristics, including chatbot trustworthiness and role appropriateness. These results highlight the complexities of creating inclusive AI systems and underscore the need for further exploration of diversity to enhance human-computer interactions. 

**Abstract (ZH)**: 随着聊天机器人的日常任务集成程度不断提高，设计能够适应多样用户群体的系统对于培养信任、增强参与度和促进包容性至关重要。本研究探讨了当前大型语言模型（LLMs）生成非标准英语（如非洲裔美国人方言英语AAVE）的能力，并评估AAVE在聊天机器人应用中的使用对其用户体验的影响。我们分析了三种LLM家族（Llama、GPT和Claude）在不同方言强度下生成AAVE样态表达的表现，并评估了用户在医疗保健和教育等多个领域的偏好。尽管LLMs在生成AAVE样态语言方面表现出了较高的能力，但研究结果表明，AAVE使用者更偏好标准美国英语(SAE)聊天机器人，且方言的使用程度越高，聊天机器人的可信度和角色适宜性等各方面评价越低。这些结果突显了创建包容性AI系统的复杂性，并强调了进一步探究多样性以增强人机互动的重要性。 

---
# Context-Alignment: Activating and Enhancing LLM Capabilities in Time Series 

**Title (ZH)**: 上下文对齐：激活并增强大型语言模型在时间序列中的能力 

**Authors**: Yuxiao Hu, Qian Li, Dongxiao Zhang, Jinyue Yan, Yuntian Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.03747)  

**Abstract**: Recently, leveraging pre-trained Large Language Models (LLMs) for time series (TS) tasks has gained increasing attention, which involves activating and enhancing LLMs' capabilities. Many methods aim to activate LLMs' capabilities based on token-level alignment but overlook LLMs' inherent strength on natural language processing -- their deep understanding of linguistic logic and structure rather than superficial embedding processing. We propose Context-Alignment, a new paradigm that aligns TS with a linguistic component in the language environments familiar to LLMs to enable LLMs to contextualize and comprehend TS data, thereby activating their capabilities. Specifically, such context-level alignment comprises structural alignment and logical alignment, which is achieved by a Dual-Scale Context-Alignment GNNs (DSCA-GNNs) applied to TS-language multimodal inputs. Structural alignment utilizes dual-scale nodes to describe hierarchical structure in TS-language, enabling LLMs treat long TS data as a whole linguistic component while preserving intrinsic token features. Logical alignment uses directed edges to guide logical relationships, ensuring coherence in the contextual semantics. Demonstration examples prompt are employed to construct Demonstration Examples based Context-Alignment (DECA) following DSCA-GNNs framework. DECA can be flexibly and repeatedly integrated into various layers of pre-trained LLMs to improve awareness of logic and structure, thereby enhancing performance. Extensive experiments show the effectiveness of DECA and the importance of Context-Alignment across tasks, particularly in few-shot and zero-shot forecasting, confirming that Context-Alignment provide powerful prior knowledge on context. 

**Abstract (ZH)**: 近年来，利用预训练的大语言模型（LLMs）处理时间序列（TS）任务引起了越来越多的关注，这涉及激活和增强LLMs的能力。许多方法旨在通过字元级别对齐来激活LLMs的能力，但忽略了LLMs在自然语言处理中固有的优势——对语言逻辑和结构的深刻理解，而不是浅层的嵌入处理。我们提出了一种名为Context-Alignment的新范式，通过将时间序列与自然语言环境中的语言组件对齐，使LLMs能够理解和上下文化时间序列数据，从而激活其能力。具体而言，这种上下文对齐包括结构对齐和逻辑对齐，通过应用双尺度上下文对齐图神经网络（DSCA-GNNs）来处理时间序列-语言多模态输入。结构对齐利用双尺度节点描述时间序列-语言的层次结构，使LLMs能够将长时间序列数据视为一个整体的语言组件，同时保留固有的字元特征。逻辑对齐使用有向边来引导逻辑关系，确保上下文语义的一致性。以示范示例为基础，我们构建了遵循DSCA-GNNs框架的基于示范示例上下文对齐（DECA）。DECA可以灵活地集成到预训练LLMs的不同层中，以提高逻辑和结构的意识，从而增强性能。广泛的实验表明DECA的有效性以及上下文对齐的重要性，特别是在少数样本和零样本预测任务中，证实了上下文对齐为上下文提供了强大的先验知识。 

---
# LlaMADRS: Prompting Large Language Models for Interview-Based Depression Assessment 

**Title (ZH)**: LlaMADRS：基于访谈的大语言模型抑郁症评估Prompting方法 

**Authors**: Gaoussou Youssouf Kebe, Jeffrey M. Girard, Einat Liebenthal, Justin Baker, Fernando De la Torre, Louis-Philippe Morency  

**Link**: [PDF](https://arxiv.org/pdf/2501.03624)  

**Abstract**: This study introduces LlaMADRS, a novel framework leveraging open-source Large Language Models (LLMs) to automate depression severity assessment using the Montgomery-Asberg Depression Rating Scale (MADRS). We employ a zero-shot prompting strategy with carefully designed cues to guide the model in interpreting and scoring transcribed clinical interviews. Our approach, tested on 236 real-world interviews from the Context-Adaptive Multimodal Informatics (CAMI) dataset, demonstrates strong correlations with clinician assessments. The Qwen 2.5--72b model achieves near-human level agreement across most MADRS items, with Intraclass Correlation Coefficients (ICC) closely approaching those between human raters. We provide a comprehensive analysis of model performance across different MADRS items, highlighting strengths and current limitations. Our findings suggest that LLMs, with appropriate prompting, can serve as efficient tools for mental health assessment, potentially increasing accessibility in resource-limited settings. However, challenges remain, particularly in assessing symptoms that rely on non-verbal cues, underscoring the need for multimodal approaches in future work. 

**Abstract (ZH)**: 本研究介绍了一种名为LlaMADRS的新框架，该框架利用开源的大规模语言模型（LLMs）自动化使用蒙特戈梅里-阿斯伯格抑郁量表（MADRS）评估抑郁严重程度。我们采用了零样本提示策略，并设计了精巧的触发器来引导模型在解释和评分转录的临床访谈时的思考过程。该方法在Context-Adaptive Multimodal Informatics (CAMI) 数据集中实际进行的236次临床访谈上进行了测试，显示出与临床评估人员的评分具有较强的关联性。Qwen 2.5--72b模型在大多数MADRS项目上达到接近人类水平的一致性，内在一致性相关系数（ICC）与人类评估者之间的一致性高度接近。我们对模型在不同MADRS项目上的性能进行了全面分析，突显了其优势和当前的局限性。研究结果表明，通过适当提示的大规模语言模型可以作为精神健康评估的高效工具，在资源受限的地区具有潜在的应用价值。然而，仍存在一些挑战，特别是在评估依赖非言语线索的症状方面，这强调了未来工作中需要采用多模态方法的重要性。 

---
# A Semantically-Aware, Kernel-Enhanced, and Divergence-Rich Paradigm for Direct Preference Optimization 

**Title (ZH)**: 一种语义意识强、核增强且富有差异性的直接偏好优化范式 

**Authors**: Amitava Das, Suranjana Trivedy, Danush Khanna, Rajarshi Roy, Gurpreet Singh, Basab Ghosh, Yaswanth Narsupalli, Vinija Jain, Vasu Sharma, Aishwarya Naresh Reganti, Aman Chadha  

**Link**: [PDF](https://arxiv.org/pdf/2501.03271)  

**Abstract**: The rapid rise of large language models (LLMs) has unlocked many applications but also underscores the challenge of aligning them with diverse values and preferences. Direct Preference Optimization (DPO) is central to alignment but constrained by fixed divergences and limited feature transformations. We propose DPO-Kernels, which integrates kernel methods to address these issues through four key contributions: (i) Kernelized Representations with polynomial, RBF, Mahalanobis, and spectral kernels for richer transformations, plus a hybrid loss combining embedding-based and probability-based objectives; (ii) Divergence Alternatives (Jensen-Shannon, Hellinger, Renyi, Bhattacharyya, Wasserstein, and f-divergences) for greater stability; (iii) Data-Driven Selection metrics that automatically choose the best kernel-divergence pair; and (iv) a Hierarchical Mixture of Kernels for both local precision and global modeling. Evaluations on 12 datasets demonstrate state-of-the-art performance in factuality, safety, reasoning, and instruction following. Grounded in Heavy-Tailed Self-Regularization, DPO-Kernels maintains robust generalization for LLMs, offering a comprehensive resource for further alignment research. 

**Abstract (ZH)**: 大型语言模型（LLMs）的迅速崛起解锁了众多应用，同时也突显了将其与多样价值观和偏好对齐的挑战。直接偏好优化（DPO）是实现对齐的核心方法，但受限于固定的差异度量和有限的特征变换。我们提出了DPO-Kernels，通过四种关键贡献结合核方法来解决这些问题：（i）核化表示，包括多项式核、高斯核、马氏距离核和谱核，以及结合嵌入和概率目标的混合损失，以实现更丰富的变换；（ii）差异度量替代方法（如詹森-沙恩差异度、Hellinger差异度、Rényi差异度、巴特赤低差异度、Wasserstein距离和f-差异度），以提高稳定性；（iii）数据驱动选择度量，能够自动选择最佳核-差异度配对；（iv）分层核混合，同时提供局部精度和全局建模。在12个数据集上的评估结果显示，DPO-Kernels在事实性、安全性、推理和指令跟随方面都达到了最先进的性能。基于重尾自我正则化，DPO-Kernels为LLMs提供了稳健的泛化能力，并为进一步的对齐研究提供了全面的资源。 

---
# RAG-Check: Evaluating Multimodal Retrieval Augmented Generation Performance 

**Title (ZH)**: RAG-Check：评估多模态检索增强生成性能 

**Authors**: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus  

**Link**: [PDF](https://arxiv.org/pdf/2501.03995)  

**Abstract**: Retrieval-augmented generation (RAG) improves large language models (LLMs) by using external knowledge to guide response generation, reducing hallucinations. However, RAG, particularly multi-modal RAG, can introduce new hallucination sources: (i) the retrieval process may select irrelevant pieces (e.g., documents, images) as raw context from the database, and (ii) retrieved images are processed into text-based context via vision-language models (VLMs) or directly used by multi-modal language models (MLLMs) like GPT-4o, which may hallucinate. To address this, we propose a novel framework to evaluate the reliability of multi-modal RAG using two performance measures: (i) the relevancy score (RS), assessing the relevance of retrieved entries to the query, and (ii) the correctness score (CS), evaluating the accuracy of the generated response. We train RS and CS models using a ChatGPT-derived database and human evaluator samples. Results show that both models achieve ~88% accuracy on test data. Additionally, we construct a 5000-sample human-annotated database evaluating the relevancy of retrieved pieces and the correctness of response statements. Our RS model aligns with human preferences 20% more often than CLIP in retrieval, and our CS model matches human preferences ~91% of the time. Finally, we assess various RAG systems' selection and generation performances using RS and CS. 

**Abstract (ZH)**: 检索增强生成（Retrieval-Augmented Generation，RAG）通过利用外部知识引导响应生成，从而改进了大规模语言模型（Large Language Models，LLMs），减少幻觉现象。然而，RAG，尤其是多模态RAG，可能会引入新的幻觉来源：（i）检索过程可能会从数据库中选择与查询无关的片段（如文档、图像）作为原始上下文；（ii）检索到的图像通过视觉语言模型（Vision-Language Models，VLMs）转换为基于文本的上下文，或者直接被多模态语言模型（Multimodal Language Models，MLLMs）如GPT-4o使用，可能导致幻觉。为应对这一问题，我们提出了一种新的框架来评估多模态RAG的可靠性，使用两种性能指标：（i）相关性评分（Relevance Score，RS），评估检索条目与查询的相关性；（ii）正确性评分（Correctness Score，CS），评估生成响应的准确性。我们使用从ChatGPT派生的数据库和人工评估样本训练RS和CS模型。结果显示，这两种模型在测试数据上的准确率均达到约88%。此外，我们构建了一个包含5000个样本的人工标注数据库，用于评估检索片段的相关性及响应陈述的准确性。我们的RS模型在检索中比CLIP更符合人类偏好20%，而我们的CS模型约91%的情况下与人类偏好一致。最后，我们使用RS和CS评估了各种RAG系统的选择和生成性能。 

---
# Exploring the Potential of Large Language Models in Public Transportation: San Antonio Case Study 

**Title (ZH)**: 探索大规模语言模型在公共交通领域的潜力：桑托卢斯案例研究

注：此处将“San Antonio”翻译为了“桑托卢斯”，因为在中文语境中，直接使用地名的英文名可能不如其汉化名称更为人所熟知。如果需要更准确的翻译，可以保留“San Antonio”，并在括号中注释英文原名，如“探索大规模语言模型在公共交通领域的潜力：桑托卢斯（San Antonio）案例研究”。 

**Authors**: Ramya Jonnala, Gongbo Liang, Jeong Yang, Izzat Alsmadi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03904)  

**Abstract**: The integration of large language models (LLMs) into public transit systems presents a transformative opportunity to enhance urban mobility. This study explores the potential of LLMs to revolutionize public transportation management within the context of San Antonio's transit system. Leveraging the capabilities of LLMs in natural language processing and data analysis, we investigate their capabilities to optimize route planning, reduce wait times, and provide personalized travel assistance. By utilizing the General Transit Feed Specification (GTFS) and other relevant data, this research aims to demonstrate how LLMs can potentially improve resource allocation, elevate passenger satisfaction, and inform data-driven decision-making in transit operations. A comparative analysis of different ChatGPT models was conducted to assess their ability to understand transportation information, retrieve relevant data, and provide comprehensive responses. Findings from this study suggest that while LLMs hold immense promise for public transit, careful engineering and fine-tuning are essential to realizing their full potential. San Antonio serves as a case study to inform the development of LLM-powered transit systems in other urban environments. 

**Abstract (ZH)**: 将大型语言模型（LLMs）集成到公共交通系统中，为城市交通的变革性提升提供了机会。本研究探讨了LLMs在圣安东尼奥公交系统中重塑公共交通管理的潜在可能性。借助LLMs在自然语言处理和数据分析方面的优势，我们研究了其提高路线规划效率、减少等待时间并提供个性化出行协助的能力。通过利用通用公共交通喂给规范（GTFS）及其他相关数据，本研究旨在展示LLMs如何潜在地优化资源配置、提升乘客满意度，并支持基于数据的决策制定。我们还对不同的ChatGPT模型进行了比较分析，评估了它们理解交通信息、检索相关数据和提供综合回答的能力。本研究的发现表明，虽然LLMs在公共交通领域具有巨大的潜力，但精细的设计和调整对于充分发挥其潜力至关重要。圣安东尼奥作为案例研究，为其他城市环境中LLM驱动的公交系统的发展提供了参考。 

---
# SenseRAG: Constructing Environmental Knowledge Bases with Proactive Querying for LLM-Based Autonomous Driving 

**Title (ZH)**: SenseRAG：通过主动查询构建环境知识库以支持基于大语言模型的自动驾驶 

**Authors**: Xuewen Luo, Fan Ding, Fengze Yang, Yang Zhou, Junnyong Loo, Hwa Hui Tew, Chenxi Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03535)  

**Abstract**: This study addresses the critical need for enhanced situational awareness in autonomous driving (AD) by leveraging the contextual reasoning capabilities of large language models (LLMs). Unlike traditional perception systems that rely on rigid, label-based annotations, it integrates real-time, multimodal sensor data into a unified, LLMs-readable knowledge base, enabling LLMs to dynamically understand and respond to complex driving environments. To overcome the inherent latency and modality limitations of LLMs, a proactive Retrieval-Augmented Generation (RAG) is designed for AD, combined with a chain-of-thought prompting mechanism, ensuring rapid and context-rich understanding. Experimental results using real-world Vehicle-to-everything (V2X) datasets demonstrate significant improvements in perception and prediction performance, highlighting the potential of this framework to enhance safety, adaptability, and decision-making in next-generation AD systems. 

**Abstract (ZH)**: 本文通过利用大规模语言模型（LLMs）的上下文推理能力，解决了自动驾驶（AD）中增强态势感知的关键需求。不同于依赖于刚性标签注释的传统感知系统，本文将实时的多模态传感器数据整合进一个统一的、LLMs可读的知识库中，使LLMs能够动态地理解和应对复杂的驾驶环境。为了克服LLMs固有的延迟和模态限制，本文为AD设计了一种前瞻性的检索增强生成（RAG）方法，并结合了一种链式思考提示机制，确保快速且富有上下文的理解。使用实际的车辆到一切（V2X）数据集的实验结果表明，在感知和预测性能方面取得了显著的改进，突显了该框架在提升下一代AD系统的安全性、适应性和决策能力方面的潜力。 

---
# Video-of-Thought: Step-by-Step Video Reasoning from Perception to Cognition 

**Title (ZH)**: 思维视频：从感知到认知的逐步视频推理 

**Authors**: Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Meishan Zhang, Mong-Li Lee, Wynne Hsu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03230)  

**Abstract**: Existing research of video understanding still struggles to achieve in-depth comprehension and reasoning in complex videos, primarily due to the under-exploration of two key bottlenecks: fine-grained spatial-temporal perceptive understanding and cognitive-level video scene comprehension. This paper bridges the gap by presenting a novel solution. We first introduce a novel video Multimodal Large Language Model (MLLM), MotionEpic, which achieves fine-grained pixel-level spatial-temporal video grounding by integrating video spatial-temporal scene graph (STSG) representation. Building upon MotionEpic, we then develop a Video-of-Thought (VoT) reasoning framework. VoT inherits the Chain-of-Thought (CoT) core, breaking down a complex task into simpler and manageable sub-problems, and addressing them step-by-step from a low-level pixel perception to high-level cognitive interpretation. Extensive experiments across various complex video QA benchmarks demonstrate that our overall framework strikingly boosts existing state-of-the-art. To our knowledge, this is the first attempt at successfully implementing the CoT technique for achieving human-level video reasoning, where we show great potential in extending it to a wider range of video understanding scenarios. Project is open at this https URL 

**Abstract (ZH)**: 现有的视频理解研究在实现对复杂视频的深入理解和推理方面仍然面临挑战，主要原因是忽视了两个关键瓶颈：精细化的空间-时间感知理解和认知级别的视频场景理解。本文通过提出一种新颖的解决方案来弥补这一差距。我们首先介绍了一种新颖的视频多模态大型语言模型（MLLM），名为MotionEpic，该模型通过集成视频空间-时间场景图（STSG）表示，实现了精细化的像素级空间-时间视频接地。在此基础上，我们进一步开发了一种视频思维（VoT）推理框架。VoT继承了链式思维（CoT）的核心理念，将复杂任务细分为更简单且可管理的子问题，并从低层次的像素感知逐步过渡到高层次的认知解释。广泛实验结果表明，我们提出的整体框架显著提升了现有最先进的方法。据我们所知，这是首次尝试成功实施CoT技术以实现人类级别的视频推理，在各种复杂的视频问答基准测试中展示了巨大潜力，我们展示了将其扩展到更广泛的视频理解场景的巨大可能性。该项目的代码已开源，可以访问此链接：[请在此处添加链接] 

---
# Align-Pro: A Principled Approach to Prompt Optimization for LLM Alignment 

**Title (ZH)**: Align-Pro：一种原理性的方法，用于大规模语言模型对齐的提示优化 

**Authors**: Prashant Trivedi, Souradip Chakraborty, Avinash Reddy, Vaneet Aggarwal, Amrit Singh Bedi, George K. Atia  

**Link**: [PDF](https://arxiv.org/pdf/2501.03486)  

**Abstract**: The alignment of large language models (LLMs) with human values is critical as these models become increasingly integrated into various societal and decision-making processes. Traditional methods, such as reinforcement learning from human feedback (RLHF), achieve alignment by fine-tuning model parameters, but these approaches are often computationally expensive and impractical when models are frozen or inaccessible for parameter modification. In contrast, prompt optimization is a viable alternative to RLHF for LLM alignment. While the existing literature has shown empirical promise of prompt optimization, its theoretical underpinning remains under-explored. We address this gap by formulating prompt optimization as an optimization problem and try to provide theoretical insights into the optimality of such a framework. To analyze the performance of the prompt optimization, we study theoretical suboptimality bounds and provide insights in terms of how prompt optimization depends upon the given prompter and target model. We also provide empirical validation through experiments on various datasets, demonstrating that prompt optimization can effectively align LLMs, even when parameter fine-tuning is not feasible. 

**Abstract (ZH)**: 大型语言模型（LLMs）与人类价值观的对齐至关重要，因为这些模型越来越被整合到各种社会和决策过程中。传统的对齐方法，如基于人类反馈的强化学习（RLHF），通过调整模型参数实现对齐，但在模型冻结或无法修改参数的情况下，这些方法往往计算成本高且不切实际。相比之下，提示优化是RLHF之外的一种可行的LLMs对齐方法。尽管现有文献显示提示优化具有实际应用前景，但其理论基础仍然有待深入探索。我们通过将提示优化形式化为优化问题来填补这一空白，并尝试提供该框架最优性的理论洞察。为了分析提示优化的性能，我们研究了理论次优性边界，并从提示优化依赖于给定的提示提供者和目标模型的角度提供了见解。我们还通过在各种数据集上进行的实验提供了经验验证，证明了即使参数微调不可行，提示优化也能够有效对齐LLMs。 

---
# A Soft Sensor Method with Uncertainty-Awareness and Self-Explanation Based on Large Language Models Enhanced by Domain Knowledge Retrieval 

**Title (ZH)**: 基于领域知识检索增强的大语言模型的不确定性意识与自我解释软传感器方法 

**Authors**: Shuo Tong, Runyuan Guo, Wenqing Wang, Xueqiong Tian, Lingyun Wei, Lin Zhang, Huayong Wu, Ding Liu, Youmin Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03295)  

**Abstract**: Data-driven soft sensors are crucial in predicting key performance indicators in industrial systems. However, current methods predominantly rely on the supervised learning paradigms of parameter updating, which inherently faces challenges such as high development costs, poor robustness, training instability, and lack of interpretability. Recently, large language models (LLMs) have demonstrated significant potential across various domains, notably through In-Context Learning (ICL), which enables high-performance task execution with minimal input-label demonstrations and no prior training. This paper aims to replace supervised learning with the emerging ICL paradigm for soft sensor modeling to address existing challenges and explore new avenues for advancement. To achieve this, we propose a novel framework called the Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS), which includes the Zero-shot Auxiliary Variable Selector (LLM-ZAVS) and the Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS). The LLM-ZAVS retrieves from the Industrial Knowledge Vector Storage to enhance LLMs' domain-specific knowledge, enabling zero-shot auxiliary variable selection. In the LLM-UFSS, we utilize text-based context demonstrations of structured data to prompt LLMs to execute ICL for predicting and propose a context sample retrieval augmentation strategy to improve performance. Additionally, we explored LLMs' AIGC and probabilistic characteristics to propose self-explanation and uncertainty quantification methods for constructing a trustworthy soft sensor. Extensive experiments demonstrate that our method achieved state-of-the-art predictive performance, strong robustness, and flexibility, effectively mitigates training instability found in traditional methods. To the best of our knowledge, this is the first work to establish soft sensor utilizing LLMs. 

**Abstract (ZH)**: 数据驱动的软传感器在预测工业系统中的关键性能指标方面至关重要。然而，当前的方法主要依赖监督学习中的参数更新框架，这本身就面临着高开发成本、鲁棒性差、训练不稳定性和缺乏可解释性等挑战。近年来，大型语言模型（LLMs）在各个领域展现出了巨大的潜力，特别是通过上下文学习（In-Context Learning, ICL），能够在最少的输入-标签示范和无需先验训练的情况下实现高性能的任务执行。本文旨在利用新兴的ICL范式替换监督学习，以解决现有的挑战并探索新的发展路径。为此，我们提出了一种名为Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS)的新框架，该框架包括Zero-shot Auxiliary Variable Selector (LLM-ZAVS)和Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS)。LLM-ZAVS从工业知识向量存储中检索信息，以增强LLMs的领域特定知识，实现零样本辅助变量选择。在LLM-UFSS中，我们利用结构化数据的文本上下文示范来驱动LLMs执行ICL以进行预测，并提出了一种上下文样本检索增强策略以提高性能。此外，我们探索了LLMs的特性，包括生成式人工智能（AIGC）和概率特性，并提出了自我解释和不确定性量化方法，以构建可信的软传感器。广泛实验结果表明，我们的方法达到了最先进的预测性能、强大的鲁棒性和灵活性，有效缓解了传统方法中发现的训练稳定性问题。据我们所知，这是首次利用LLMs构建软传感器的工作。 

---
# CodeVision: Detecting LLM-Generated Code Using 2D Token Probability Maps and Vision Models 

**Title (ZH)**: CodeVision：使用2D令牌概率图和视觉模型检测LLM生成的代码 

**Authors**: Zhenyu Xu, Victor S. Sheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03288)  

**Abstract**: The rise of large language models (LLMs) like ChatGPT has significantly improved automated code generation, enhancing software development efficiency. However, this introduces challenges in academia, particularly in distinguishing between human-written and LLM-generated code, which complicates issues of academic integrity. Existing detection methods, such as pre-trained models and watermarking, face limitations in adaptability and computational efficiency. In this paper, we propose a novel detection method using 2D token probability maps combined with vision models, preserving spatial code structures such as indentation and brackets. By transforming code into log probability matrices and applying vision models like Vision Transformers (ViT) and ResNet, we capture both content and structure for more accurate detection. Our method shows robustness across multiple programming languages and improves upon traditional detectors, offering a scalable and computationally efficient solution for identifying LLM-generated code. 

**Abstract (ZH)**: 大型语言模型（LLMs）如ChatGPT的兴起显著提升了自动代码生成的能力，提高了软件开发的效率。然而，这在学术界引入了新的挑战，尤其是在区分人类编写的代码和LLM生成的代码方面，这使得学术诚信问题复杂化。现有的检测方法，如预训练模型和水印技术，在适应性和计算效率方面存在局限性。在本文中，我们提出了一种新的检测方法，结合使用2D标记概率图和视觉模型，保留了代码的空间结构，如缩进和括号。通过将代码转换为对数概率矩阵，并应用Vision Transformers (ViT)和ResNet等视觉模型，我们能够同时捕捉内容和结构，从而提高检测的准确性。我们的方法在多种编程语言中表现出强大的鲁棒性，并且相比传统检测器有所改进，提供了一种可扩展且计算高效的解决方案，用于识别LLM生成的代码。 

---