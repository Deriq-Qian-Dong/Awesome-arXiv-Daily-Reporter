# Multi-stage Large Language Model Pipelines Can Outperform GPT-4o in Relevance Assessment 

**Title (ZH)**: 多阶段大型语言模型管道可以在相关性评估中超越GPT-4o 

**Authors**: Julian A. Schnabel, Johanne R. Trippas, Falk Scholer, Danula Hettiachchi  

**Link**: [PDF](https://arxiv.org/pdf/2501.14296)  

**Abstract**: The effectiveness of search systems is evaluated using relevance labels that indicate the usefulness of documents for specific queries and users. While obtaining these relevance labels from real users is ideal, scaling such data collection is challenging. Consequently, third-party annotators are employed, but their inconsistent accuracy demands costly auditing, training, and monitoring. We propose an LLM-based modular classification pipeline that divides the relevance assessment task into multiple stages, each utilising different prompts and models of varying sizes and capabilities. Applied to TREC Deep Learning (TREC-DL), one of our approaches showed an 18.4% Krippendorff's $\alpha$ accuracy increase over OpenAI's GPT-4o mini while maintaining a cost of about 0.2 USD per million input tokens, offering a more efficient and scalable solution for relevance assessment. This approach beats the baseline performance of GPT-4o (5 USD). With a pipeline approach, even the accuracy of the GPT-4o flagship model, measured in $\alpha$, could be improved by 9.7%. 

**Abstract (ZH)**: 基于搜索系统的有效性通过相关性标签进行评估，这些标签表明特定查询和用户对于文档的有用性。尽管从真实用户处获取这些相关性标签是理想的，但大规模收集此类数据具有挑战性。因此，通常会雇佣第三方标注者，但他们的不一致准确性需要耗费大量成本进行审核、培训和监控。我们提出了一种基于大语言模型（LLM）的模块化分类流水线，将相关性评估任务划分为多个阶段，每个阶段使用不同类型的提示和具有不同大小与能力的模型。应用于TREC深度学习（TREC-DL）任务中，我们的一种方法在保持每百万输入标记成本约为0.2美元的情况下，Krippendorff’s $\alpha$精度提高了18.4%，提供了一种更为高效和可扩展的相关性评估解决方案。这种方法优于GPT-4o基线模型（5美元）。使用流水线方法，即使是GPT-4o旗舰模型的$\alpha$精度也得以提高9.7%。 

---
# Do LLMs Provide Consistent Answers to Health-Related Questions across Languages? 

**Title (ZH)**: 大型语言模型在不同语言中对健康相关问题的回答是否一致？ 

**Authors**: Ipek Baris Schlicht, Zhixue Zhao, Burcu Sayin, Lucie Flek, Paolo Rosso  

**Link**: [PDF](https://arxiv.org/pdf/2501.14719)  

**Abstract**: Equitable access to reliable health information is vital for public health, but the quality of online health resources varies by language, raising concerns about inconsistencies in Large Language Models (LLMs) for healthcare. In this study, we examine the consistency of responses provided by LLMs to health-related questions across English, German, Turkish, and Chinese. We largely expand the HealthFC dataset by categorizing health-related questions by disease type and broadening its multilingual scope with Turkish and Chinese translations. We reveal significant inconsistencies in responses that could spread healthcare misinformation. Our main contributions are 1) a multilingual health-related inquiry dataset with meta-information on disease categories, and 2) a novel prompt-based evaluation workflow that enables sub-dimensional comparisons between two languages through parsing. Our findings highlight key challenges in deploying LLM-based tools in multilingual contexts and emphasize the need for improved cross-lingual alignment to ensure accurate and equitable healthcare information. 

**Abstract (ZH)**: 公共健康领域内公平获取可靠健康信息至关重要，但在线健康资源的质量因语言而异，这引发了对大型语言模型（LLMs）在医疗健康领域中一致性问题的关注。本研究旨在探讨LLMs对健康相关问题在英语、德语、土耳其语和中文中的回答一致性。我们通过按疾病类型对健康相关问题进行分类，并扩展至包括土耳其语和中文的多语言范围，对HealthFC数据集进行了大幅扩展。我们揭示了回答中的显著不一致性，这些不一致性可能导致健康误导信息的传播。我们的主要贡献包括：1) 一个包含疾病类别元信息的多语言健康相关问询数据集；2) 一种新颖的基于提示的评估工作流，能够通过解析实现两种语言在子维度上的比较。研究结果突显了在多语言环境中部署基于LLM的工具所面临的关键挑战，并强调了改进跨语言对齐的重要性，以确保医药健康信息的准确性和公平性。 

---
# MedSlice: Fine-Tuned Large Language Models for Secure Clinical Note Sectioning 

**Title (ZH)**: MedSlice: 细化调优的大语言模型在安全临床笔记分区中的应用 

**Authors**: Joshua Davis, Thomas Sounack, Kate Sciacca, Jessie M Brain, Brigitte N Durieux, Nicole D Agaronnik, Charlotta Lindvall  

**Link**: [PDF](https://arxiv.org/pdf/2501.14105)  

**Abstract**: Extracting sections from clinical notes is crucial for downstream analysis but is challenging due to variability in formatting and labor-intensive nature of manual sectioning. While proprietary large language models (LLMs) have shown promise, privacy concerns limit their accessibility. This study develops a pipeline for automated note sectioning using open-source LLMs, focusing on three sections: History of Present Illness, Interval History, and Assessment and Plan. We fine-tuned three open-source LLMs to extract sections using a curated dataset of 487 progress notes, comparing results relative to proprietary models (GPT-4o, GPT-4o mini). Internal and external validity were assessed via precision, recall and F1 score. Fine-tuned Llama 3.1 8B outperformed GPT-4o (F1=0.92). On the external validity test set, performance remained high (F1= 0.85). Fine-tuned open-source LLMs can surpass proprietary models in clinical note sectioning, offering advantages in cost, performance, and accessibility. 

**Abstract (ZH)**: 从临床笔记中提取段落对于下游分析至关重要，但由于格式差异性和手工分段的劳动密集型性质，这颇具挑战性。虽然专有的大型语言模型（LLMs）显示出一定的潜力，但隐私问题限制了它们的可访问性。本研究开发了一种使用开源LLMs的自动化笔记分段管道，重点关注三个段落：当前病情病史、间歇病史和评估与计划。我们对三个开源LLMs进行了微调，使用一个包含487篇病情进展记录的数据集来提取段落，并将结果与专有模型（GPT-4o、GPT-4o mini）进行比较。内部和外部有效性的评估基于精确度、召回率和F1分数。微调后的Llama 3.1 8B在准确性方面优于GPT-4o（F1=0.92）。在外部有效性测试集中，性能仍然很高（F1=0.85）。微调后的开源LLMs在临床笔记分段方面可以超越专有模型，提供成本、性能和可访问性方面的优势。 

---
# CAPRAG: A Large Language Model Solution for Customer Service and Automatic Reporting using Vector and Graph Retrieval-Augmented Generation 

**Title (ZH)**: CAPRAG：一种基于向量和图检索增强生成的大型语言模型解决方案，用于客户服务和自动报告 

**Authors**: Hamza Landolsi, Kais Letaief, Nizar Taghouti, Ines Abdeljaoued-Tej  

**Link**: [PDF](https://arxiv.org/pdf/2501.13993)  

**Abstract**: The introduction of new features and services in the banking sector often overwhelms customers, creating an opportunity for banks to enhance user experience through financial chatbots powered by large language models (LLMs). We initiated an AI agent designed to provide customers with relevant information about banking services and insights from annual reports. We proposed a hybrid Customer Analysis Pipeline Retrieval-Augmented Generation (CAPRAG) that effectively addresses both relationship-based and contextual queries, thereby improving customer engagement in the digital banking landscape. To implement this, we developed a processing pipeline to refine text data, which we utilized in two main frameworks: Vector RAG and Graph RAG. This dual approach enables us to populate both vector and graph databases with processed data for efficient retrieval. The Cypher query component is employed to effectively query the graph database. When a user submits a query, it is first expanded by a query expansion module before being routed to construct a final query from the hybrid Knowledge Base (KB). This final query is then sent to an open-source LLM for response generation. Overall, our innovative, designed to international banks, serves bank's customers in an increasingly complex digital environment, enhancing clarity and accessibility of information. 

**Abstract (ZH)**: 银行部门引入新功能和服务往往会让客户感到不知所措，为银行通过大型语言模型（LLMs）驱动的金融聊天机器人提升用户体验提供了机会。我们启动了一个AI代理，旨在为客户提供与银行服务相关的信息以及年度报告的见解。我们提出了一种混合客户分析管道检索-增强生成（CAPRAG）方法，该方法有效地处理了基于关系和上下文的查询，从而在数字银行领域中提高了客户服务的参与度。为了实现这一目标，我们开发了一个处理管道来精炼文本数据，并将其应用于两个主要框架：向量RAG和图RAG。这种双重方法使我们能够将处理后的数据填充到向量和图数据库中，以实现高效的检索。我们使用Cypher查询组件来有效地查询图数据库。当用户提交查询时，该查询首先由查询扩展模块扩展，然后路由到构建最终查询的混合知识库（KB）。该最终查询随后发送给开源LLM以生成回应。总体而言，我们创新的解决方案旨在为国际银行的客户提供一个日益复杂的数字环境中的帮助，从而提高信息的清晰度和可访问性。 

---
# FlexiGPT: Pruning and Extending Large Language Models with Low-Rank Weight Sharing 

**Title (ZH)**: FlexiGPT：通过低秩权重共享进行大规模语言模型的剪枝与扩展 

**Authors**: James Seale Smith, Chi-Heng Lin, Shikhar Tuli, Haris Jeelani, Shangqian Gao, Yilin Shen, Hongxia Jin, Yen-Chang Hsu  

**Link**: [PDF](https://arxiv.org/pdf/2501.14713)  

**Abstract**: The rapid proliferation of large language models (LLMs) in natural language processing (NLP) has created a critical need for techniques that enable efficient deployment on memory-constrained devices without compromising performance. We present a method to prune LLMs that selectively prunes model blocks based on an importance score and replaces them with a low-parameter replacement strategy. Specifically, we propose a principled metric to replace each pruned block using a weight-sharing mechanism that leverages unpruned counterparts from the model and block-specific low-rank adapters. Furthermore, we facilitate the learning of these replacement blocks with output feature normalization and an adapter initialization scheme built on low-rank SVD reconstructions. Empirical evaluations demonstrate substantial performance gains over existing methods, achieving state-of-the-art performance on 5/6 benchmarks for a compression rate of 30% and 6/6 benchmarks for a compression rate of 40%. We also demonstrate that our approach can extend smaller models, boosting performance on 6/6 benchmarks using only ~0.3% tokens of extended training with minimal additional parameter costs. 

**Abstract (ZH)**: 自然语言处理（NLP）领域中大型语言模型（LLMs）的迅速发展，对能够在内存受限设备上高效部署的技术提出了迫切需求，同时不牺牲性能。本文提出了一种方法，通过基于重要性评分选择性地剪枝模型模块，并用低参数替换策略来替换这些模块。具体来说，我们提出了一种原则性的度量方法，通过利用模型中未剪枝的对应模块和特定模块的低秩适配器，使用权重共享机制为每个剪枝模块寻找替换模块。此外，我们通过输出特征归一化和基于低秩SVD重构的适配器初始化方案，促进了这些替换模块的学习。实证评估表明，相较于现有方法，本方法取得了显著的性能提升，在压缩率为30%时，取得了5/6基准测试的最优表现；在压缩率为40%时，则在6/6基准测试中取得了最优表现。我们还展示了这种方法可以扩展较小的模型，在仅进行约0.3%额外训练序列的扩展训练下，在所有6/6基准测试中提升了性能，且几乎不增加额外的参数成本。 

---
# Investigating the (De)Composition Capabilities of Large Language Models in Natural-to-Formal Language Conversion 

**Title (ZH)**: 探究大型语言模型在自然语言到形式语言转换中的（分解与）组合能力 

**Authors**: Ziyao Xu, Houfeng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.14649)  

**Abstract**: To achieve generalized and robust natural-to-formal language conversion (N2F), large language models (LLMs) need to have strong capabilities of decomposition and composition in N2F when faced with an unfamiliar formal language and be able to cope with compositional gaps and counter-intuitive symbolic names. To investigate whether LLMs have this set of basic capabilities in N2F, we propose the DEDC framework. This framework semi-automatically performs sample and task construction, allowing decoupled evaluation of the set of decomposition and composition capabilities of LLMs in N2F. Based on this framework, we evaluate and analyze the most advanced LLMs, and the main findings include that: (1) the LLMs are deficient in both decomposition and composition; (2) the LLMs show a wide coverage of error types that can be attributed to deficiencies in natural language understanding and the learning and use of symbolic systems; (3) compositional gaps and counter-intuitive symbolic names both affect the decomposition and composition of the LLMs. Our work provides a new perspective for investigating the basic capabilities of decomposition and composition of LLMs in N2F. The detailed analysis of deficiencies and attributions can help subsequent improvements of LLMs. 

**Abstract (ZH)**: 为了实现通用且鲁棒的自然语言到形式语言转换（N2F），大型语言模型（LLMs）在面对不熟悉的正式语言时，需要具备强大的分解和组合能力，并能够应对组合空白和反直觉的符号名称。为了探究LLMs是否具备这种基本的N2F能力，我们提出了DEDC框架。该框架半自动地执行样本和任务的构造，使得能够从解构和组合两个方面独立评估LLMs在N2F中的能力。基于此框架，我们评估和分析了最先进的LLMs，主要发现包括：（1）LLMs在解构和组合方面都存在缺陷；（2）LLMs显示出广泛覆盖的错误类型，这些错误可以归因于自然语言理解和符号系统学习与使用能力的不足；（3）组合空白和反直觉的符号名称都影响着LLMs的解构和组合能力。我们的工作为探究LLMs在N2F中的基本解构和组合能力提供了新的视角。详细的缺陷分析和归因可以帮助后续改进LLMs。 

---
# Evaluating and Improving Graph to Text Generation with Large Language Models 

**Title (ZH)**: 评估并改进基于大型语言模型的图到文本生成 

**Authors**: Jie He, Yijun Yang, Wanqiu Long, Deyi Xiong, Victor Gutierrez Basulto, Jeff Z. Pan  

**Link**: [PDF](https://arxiv.org/pdf/2501.14497)  

**Abstract**: Large language models (LLMs) have demonstrated immense potential across various tasks. However, research for exploring and improving the capabilities of LLMs in interpreting graph structures remains limited. To address this gap, we conduct a comprehensive evaluation of prompting current open-source LLMs on graph-to-text generation tasks. Although we explored the optimal prompting strategies and proposed a novel and effective diversity-difficulty-based few-shot sample selection method, we found that the improvements from tuning-free approaches were incremental, as LLMs struggle with planning on complex graphs, particularly those with a larger number of triplets. To further improve LLMs in planning with graph sequences and grounding in truth, we introduce a new graph-to-text dataset, PlanGTG, annotated with two sub-tasks: reordering and attribution. Through extensive automatic and human evaluations, we demonstrate significant improvements in the quality of generated text from both few-shot learning and fine-tuning perspectives using the PlanGTG dataset. Our study paves the way for new research directions in graph-to-text generation. PlanGTG datasets can be found in this https URL. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在各种任务中展现出了巨大的潜力。然而，对于探索和提升LLMs在解释图形结构方面的能力的研究仍然有限。为了弥补这一空白，我们对当前开源的LLMs在图形到文本生成任务上的提示进行了全面评估。尽管我们探索了最优的提示策略，并提出了一种基于多样性和难度的少样本示例选择的新颖且有效的方法，但我们发现，无微调的方法带来的改进是增量的，主要是因为LLMs在处理复杂图形时存在困难，特别是当图形包含大量三元组时。为了进一步提高LLMs在图形序列上的规划能力和与事实的对接能力，我们引入了一个新的图形到文本数据集PlanGTG，并为此数据集标注了两个子任务：重排序和归因。通过广泛的自动和人工评估，我们证明了在使用PlanGTG数据集从少样本学习和微调的角度来看，生成文本的质量得到了显著提升。本研究为图形到文本生成领域的未来研究方向铺平了道路。PlanGTG数据集可以在以下链接找到：[请在这里插入链接]。 

---
# Domaino1s: Guiding LLM Reasoning for Explainable Answers in High-Stakes Domains 

**Title (ZH)**: Domaino1s：引导LLM推理以在高 stakes 领域生成可解释的答案 

**Authors**: Xu Chu, Zhijie Tan, Hanlin Xue, Guanyu Wang, Tong Mo, Weiping Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.14431)  

**Abstract**: Large Language Models (LLMs) are widely applied to downstream domains. However, current LLMs for high-stakes domain tasks, such as financial investment and legal QA, typically generate brief answers without reasoning processes and explanations. This limits users' confidence in making decisions based on their responses. While original CoT shows promise, it lacks self-correction mechanisms during reasoning. This work introduces Domain$o1$s, which enhances LLMs' reasoning capabilities on domain tasks through supervised fine-tuning and tree search. We construct CoT-stock-2k and CoT-legal-2k datasets for fine-tuning models that activate domain-specific reasoning steps based on their judgment. Additionally, we propose Selective Tree Exploration to spontaneously explore solution spaces and sample optimal reasoning paths to improve performance. We also introduce PROOF-Score, a new metric for evaluating domain models' explainability, complementing traditional accuracy metrics with richer assessment dimensions. Extensive experiments on stock investment recommendation and legal reasoning QA tasks demonstrate Domaino1s's leading performance and explainability. Our code is available at this https URL. 

**Abstract (ZH)**: 大规模语言模型（LLMs）广泛应用于下游领域。然而，当前应用于高风险任务领域的LLMs，如金融投资和法律问答，通常仅生成简短的答案而缺乏推理过程和解释。这限制了用户根据这些答案做出决策的信心。虽然原始CoT显示出潜力，但其推理过程中缺乏自我修正机制。本研究引入了Domain\$o1\$, 通过监督微调和树搜索增强LLMs在领域任务上的推理能力。我们构建了CoT-stock-2k和CoT-legal-2k数据集，用于微调能够基于自身判断激活领域特异性推理步骤的模型。此外，我们提出了选择性树探索方法，自动探索解决方案空间，并采样最优推理路径以改进表现。我们还引入了PROOF-Score这一新的评估指标，通过丰富的评估维度补充了传统的准确性指标，以评估领域模型的解释性。大量实验在股票投资推荐和法律推理问答任务上证明了Domain\$o1\$的优越性能和解释性。我们的代码可在以下链接获取：https://your-link-url.com 

---
# DRESSing Up LLM: Efficient Stylized Question-Answering via Style Subspace Editing 

**Title (ZH)**: 穿着风格：通过风格子空间编辑实现高效个性化问答 

**Authors**: Xinyu Ma, Yifeng Xu, Yang Lin, Tianlong Wang, Xu Chu, Xin Gao, Junfeng Zhao, Yasha Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.14371)  

**Abstract**: We introduce DRESS, a novel approach for generating stylized large language model (LLM) responses through representation editing. Existing methods like prompting and fine-tuning are either insufficient for complex style adaptation or computationally expensive, particularly in tasks like NPC creation or character role-playing. Our approach leverages the over-parameterized nature of LLMs to disentangle a style-relevant subspace within the model's representation space to conduct representation editing, ensuring a minimal impact on the original semantics. By applying adaptive editing strengths, we dynamically adjust the steering vectors in the style subspace to maintain both stylistic fidelity and semantic integrity. We develop two stylized QA benchmark datasets to validate the effectiveness of DRESS, and the results demonstrate significant improvements compared to baseline methods such as prompting and ITI. In short, DRESS is a lightweight, train-free solution for enhancing LLMs with flexible and effective style control, making it particularly useful for developing stylized conversational agents. Codes and benchmark datasets are available at this https URL. 

**Abstract (ZH)**: 我们引入了DRESS，这是一种通过表示编辑生成风格化大型语言模型（LLM）响应的新颖方法。现有的方法，如提示和微调，在复杂风格适应方面要么不够充分，要么在计算成本上非常昂贵，特别是在创建NPC或角色扮演等任务中。我们的方法利用了LLM的过度参数化特性，在模型的表示空间中分离出一个与风格相关的子空间，以进行表示编辑，从而确保对原始语义的最小影响。通过应用自适应编辑强度，我们可以动态调整风格子空间中的导向向量，以保持风格的真实性和语义的一致性。我们构建了两个风格化的问答基准数据集来验证DRESS的有效性，结果表明其与提示和交互式文本智能（ITI）等基线方法相比取得了显著改进。简而言之，DRESS是一种轻量级、无需训练的解决方案，用于通过灵活有效的样式控制增强LLM，使它特别适用于开发风格化的对话代理。相关代码和基准数据集可在以下链接获取：this https URL。 

---
# Leveraging Online Olympiad-Level Math Problems for LLMs Training and Contamination-Resistant Evaluation 

**Title (ZH)**: 利用在线奥林匹克水平数学问题进行大规模语言模型训练和抗污染评估 

**Authors**: Sadegh Mahdavi, Muchen Li, Kaiwen Liu, Christos Thrampoulidis, Leonid Sigal, Renjie Liao  

**Link**: [PDF](https://arxiv.org/pdf/2501.14275)  

**Abstract**: Advances in Large Language Models (LLMs) have sparked interest in their ability to solve Olympiad-level math problems. However, the training and evaluation of these models are constrained by the limited size and quality of available datasets, as creating large-scale data for such advanced problems requires extensive effort from human experts. In addition, current benchmarks are prone to contamination, leading to unreliable evaluations. In this paper, we present an automated pipeline that leverages the rich resources of the Art of Problem Solving (AoPS) forum, which predominantly features Olympiad-level problems and community-driven solutions. Using open-source LLMs, we develop a method to extract question-answer pairs from the forum, resulting in AoPS-Instruct, a dataset of more than 600,000 high-quality QA pairs. Our experiments demonstrate that fine-tuning LLMs on AoPS-Instruct improves their reasoning abilities across various benchmarks. Moreover, we build an automatic pipeline that introduces LiveAoPSBench, an evolving evaluation set with timestamps, derived from the latest forum data, providing a contamination-resistant benchmark for assessing LLM performance. Notably, we observe a significant decline in LLM performance over time, suggesting their success on older examples may stem from pre-training exposure rather than true reasoning ability. Our work presents a scalable approach to creating and maintaining large-scale, high-quality datasets for advanced math reasoning, offering valuable insights into the capabilities and limitations of LLMs in this domain. Our benchmark and code is available at this https URL 

**Abstract (ZH)**: 大型语言模型（LLMs）的进步激发了对其解决奥林匹克级别数学问题能力的兴趣。然而，这些模型的训练和评估受到可用数据集规模有限和质量欠佳的限制，因为为这类高级问题创建大规模数据需要大量的人工专家努力。此外，当前的基准容易受到污染，导致评估结果不可靠。在本文中，我们提出了一个自动化的管道，该管道利用Art of Problem Solving（AoPS）论坛丰富的资源，该论坛主要包含奥林匹克级别的问题和社区驱动的解决方案。通过使用开源LLMs，我们开发了一种从论坛中提取问题-答案对的方法，从而形成了包含超过600,000个高质量问题-答案对的数据集AoPS-Instruct。我们的实验表明，在AoPS-Instruct上微调LLMs可以在不同的基准上提高它们的推理能力。此外，我们构建了一个自动化的管道来引入LiveAoPSBench，这是一个具有时间戳的不断演化的评估集，由最新的论坛数据提取而来，提供了一个抵御污染的基准，用于评估LLMs的表现。值得注意的是，我们观察到LLMs的表现随时间显著下降，这表明它们在处理较早示例时的成功可能来自于预训练的暴露，而不是真实的推理能力。我们的工作提供了一种可扩展的方法来创建和维护大规模高质量的高级数学推理数据集，并提供了有关LLMs在此领域的能力和局限性的有价值见解。我们的基准和代码可以通过以下链接访问：[此 https URL](https://www.example.com)。 

---
# Communicating Activations Between Language Model Agents 

**Title (ZH)**: 语言模型代理之间的激活传播 

**Authors**: Vignav Ramesh, Kenneth Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.14082)  

**Abstract**: Communication between multiple language model (LM) agents has been shown to scale up the reasoning ability of LMs. While natural language has been the dominant medium for inter-LM communication, it is not obvious this should be the standard: not only does natural language communication incur high inference costs that scale quickly with the number of both agents and messages, but also the decoding process abstracts away too much rich information that could be otherwise accessed from the internal activations. In this work, we propose a simple technique whereby LMs communicate via activations; concretely, we pause an LM $\textit{B}$'s computation at an intermediate layer, combine its current activation with another LM $\textit{A}$'s intermediate activation via some function $\textit{f}$, then pass $\textit{f}$'s output into the next layer of $\textit{B}$ and continue the forward pass till decoding is complete. This approach scales up LMs on new tasks with zero additional parameters and data, and saves a substantial amount of compute over natural language communication. We test our method with various functional forms $\textit{f}$ on two experimental setups--multi-player coordination games and reasoning benchmarks--and find that it achieves up to $27.0\%$ improvement over natural language communication across datasets with $<$$1/4$ the compute, illustrating the superiority and robustness of activations as an alternative "language" for communication between LMs. 

**Abstract (ZH)**: 多语言模型（LM）代理之间的通信已被证明能够提高语言模型的推理能力。虽然自然语言一直是跨语言模型通信的主要媒介，但这种标准未必是必须的：自然语言通信不仅伴随着高推理成本，这种成本随着代理和消息的数量迅速增加，而且解码过程会丢失过多原本可以从内部激活中获取的丰富信息。本文中，我们提出了一种简单的方法，通过激活进行通信。具体而言，我们在语言模型 B 的一个中间层暂停其计算，将当前激活与另一个语言模型 A 的中间激活通过某种函数 f 结合，然后将 f 的输出传递给语言模型 B 的下一层，并继续前向传播直到完成解码。这种方法可以在不增加任何额外参数和数据的情况下，提高语言模型在新任务上的表现，并且通过减少计算量，相较于自然语言通信具有显著优势。我们通过不同的函数形式 f 在两种实验设置——多方协调游戏和推理基准测试中测试了该方法，并在较低计算量（少于四分之一）的情况下实现了高达 27.0% 的性能提升，这表明激活作为语言模型之间通信的另一种“语言”的优越性和鲁棒性。 

---
# LLMs are Vulnerable to Malicious Prompts Disguised as Scientific Language 

**Title (ZH)**: 大型语言模型容易受到伪装成科学语言的恶意提示攻击 

**Authors**: Yubin Ge, Neeraja Kirtane, Hao Peng, Dilek Hakkani-Tür  

**Link**: [PDF](https://arxiv.org/pdf/2501.14073)  

**Abstract**: As large language models (LLMs) have been deployed in various real-world settings, concerns about the harm they may propagate have grown. Various jailbreaking techniques have been developed to expose the vulnerabilities of these models and improve their safety. This work reveals that many state-of-the-art proprietary and open-source LLMs are vulnerable to malicious requests hidden behind scientific language. Specifically, our experiments with GPT4o, GPT4o-mini, GPT-4, LLama3-405B-Instruct, Llama3-70B-Instruct, Cohere, Gemini models on the StereoSet data demonstrate that, the models' biases and toxicity substantially increase when prompted with requests that deliberately misinterpret social science and psychological studies as evidence supporting the benefits of stereotypical biases. Alarmingly, these models can also be manipulated to generate fabricated scientific arguments claiming that biases are beneficial, which can be used by ill-intended actors to systematically jailbreak even the strongest models like GPT. Our analysis studies various factors that contribute to the models' vulnerabilities to malicious requests in academic language. Mentioning author names and venues enhances the persuasiveness of some models, and the bias scores can increase as dialogues progress. Our findings call for a more careful investigation on the use of scientific data in the training of LLMs. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在各种实际应用场景中的部署，人们对它们可能传播的危害的担忧日益增加。各种“监狱突破”技术已被开发出来，以揭示这些模型的漏洞并提高其安全性。本研究发现，许多最先进的专有和开源LLMs在遇到故意误用社会科学研究和心理学研究作为支持刻板偏见益处证据的恶意请求时，其偏见和毒性显著增加。令人警觉的是，这些模型还可以被操纵生成虚假的科学论点，声称偏见是有益的，这可能被恶意行为者用来系统地突破即使是最强的模型如GPT。我们的分析研究了在学术语言中导致模型对恶意请求脆弱的各种因素。提及作者姓名和会议信息可以增强某些模型的说服力，而偏见得分可能会随着对话的进展而增加。我们的研究结果呼吁对LLMs在训练中使用科学数据的方式进行更仔细的研究。 

---
# Leveraging Large Language Models to Analyze Emotional and Contextual Drivers of Teen Substance Use in Online Discussions 

**Title (ZH)**: 利用大型语言模型分析青少年在线讨论中物质使用的情感和情境驱动因素 

**Authors**: Jianfeng Zhu, Ruoming Jin, Hailong Jiang, Yulan Wang, Xinyu Zhang, Karin G. Coifman  

**Link**: [PDF](https://arxiv.org/pdf/2501.14037)  

**Abstract**: Adolescence is a critical stage often linked to risky behaviors, including substance use, with significant developmental and public health implications. Social media provides a lens into adolescent self-expression, but interpreting emotional and contextual signals remains complex. This study applies Large Language Models (LLMs) to analyze adolescents' social media posts, uncovering emotional patterns (e.g., sadness, guilt, fear, joy) and contextual factors (e.g., family, peers, school) related to substance use. Heatmap and machine learning analyses identified key predictors of substance use-related posts. Negative emotions like sadness and guilt were significantly more frequent in substance use contexts, with guilt acting as a protective factor, while shame and peer influence heightened substance use risk. Joy was more common in non-substance use discussions. Peer influence correlated strongly with sadness, fear, and disgust, while family and school environments aligned with non-substance use. Findings underscore the importance of addressing emotional vulnerabilities and contextual influences, suggesting that collaborative interventions involving families, schools, and communities can reduce risk factors and foster healthier adolescent development. 

**Abstract (ZH)**: 青春期是一个关键的发展阶段，常常与风险行为相关，包括物质滥用，这对其个体发展和公共卫生具有重大影响。社交媒体为了解青少年的自我表达提供了窗口，但解读情感和情境信号仍然复杂。本研究应用大规模语言模型（LLMs）分析青少年的社交媒体帖子，揭示与物质滥用相关的情感模式（例如，悲伤、内疚、恐惧、快乐）和情境因素（例如，家庭、同伴、学校）。通过热图和机器学习分析，确定了与物质滥用相关的帖子的关键预测因素。负向情感如悲伤和内疚在物质滥用情境中更为常见，其中内疚起到了保护性作用，而羞愧和同伴影响则提高了物质滥用的风险。快乐在非物质滥用讨论中更为常见。同伴影响与悲伤、恐惧和厌恶相关，而家庭和学校环境则与非物质滥用相符。研究结果强调了关注情感脆弱性和情境因素的重要性，表明家庭、学校和社区之间的合作干预措施可以降低风险因素，促进更健康的青少年发展。 

---
# Advancing Math Reasoning in Language Models: The Impact of Problem-Solving Data, Data Synthesis Methods, and Training Stages 

**Title (ZH)**: 提升语言模型的数学推理能力：解决问题数据、数据合成方法和训练阶段的影响研究 

**Authors**: Zui Chen, Tianqiao Liu, Mi Tian, Qing Tong, Weiqi Luo, Zitao Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.14002)  

**Abstract**: Advancements in LLMs have significantly expanded their capabilities across various domains. However, mathematical reasoning remains a challenging area, prompting the development of math-specific LLMs. These models typically follow a two-stage training paradigm: pre-training with math-related corpora and post-training with problem datasets for SFT. Despite these efforts, the improvements in mathematical reasoning achieved through continued pre-training (CPT) are often less significant compared to those obtained via SFT. This study addresses this discrepancy by exploring alternative strategies during the pre-training phase, focusing on the use of problem-solving data over general mathematical corpora. We investigate three primary research questions: (1) Can problem-solving data enhance the model's mathematical reasoning capabilities more effectively than general mathematical corpora during CPT? (2) Are synthetic data from the same source equally effective, and which synthesis methods are most efficient? (3) How do the capabilities developed from the same problem-solving data differ between the CPT and SFT stages, and what factors contribute to these differences? Our findings indicate that problem-solving data significantly enhances the model's mathematical capabilities compared to general mathematical corpora. We also identify effective data synthesis methods, demonstrating that the tutorship amplification synthesis method achieves the best performance. Furthermore, while SFT facilitates instruction-following abilities, it underperforms compared to CPT with the same data, which can be partially attributed to its poor learning capacity for hard multi-step problem-solving data. These insights provide valuable guidance for optimizing the mathematical reasoning capabilities of LLMs, culminating in our development of a powerful mathematical base model called JiuZhang-8B. 

**Abstract (ZH)**: 大型语言模型（LLM）的最新进展显著扩展了它们在各个领域的功能。然而，数学推理仍然是一个挑战性领域，促使开发专门的数学LLM。这些模型通常遵循两阶段训练范式：使用与数学相关的语料进行预训练，然后使用问题数据集进行指令-following（SFT）训练。尽管如此，通过持续预训练（CPT）所取得的数学推理改进往往不如通过SFT所取得的显著。本研究旨在通过探索预训练阶段的替代策略来解决这一问题，重点关注使用解决问题的数据而非一般数学语料。我们探讨了三个主要的研究问题：（1）解决问题的数据能否在CPT期间更有效地增强模型的数学推理能力，而不是使用一般数学语料？（2）来自于同一源的合成数据是否同样有效，哪些合成方法是最高效的？（3）同一解决问题数据在CPT和SFT阶段所开发的能力有何不同，这些差异是由哪些因素引起的？我们的发现表明，解决问题的数据与一般数学语料相比，可以显著增强模型的数学能力。此外，我们还确定了有效的数据合成方法，证明了导师增强合成方法取得了最佳性能。同时，虽然SFT有助于增强指令跟随能力，但与使用相同数据进行CPT相比，SFT的表现较差，这可能部分归因于其对复杂多步解决问题数据的学习能力不佳。这些见解为优化LLM的数学推理能力提供了宝贵指导，促成了我们开发的一款强大的数学基础模型——JiuZhang-8B。 

---
# Comprehensive Modeling and Question Answering of Cancer Clinical Practice Guidelines using LLMs 

**Title (ZH)**: 使用大规模语言模型对癌症临床实践指南进行全面建模与问答 

**Authors**: Bhumika Gupta, Pralaypati Ta, Keerthi Ram, Mohanasankar Sivaprakasam  

**Link**: [PDF](https://arxiv.org/pdf/2501.13984)  

**Abstract**: The updated recommendations on diagnostic procedures and treatment pathways for a medical condition are documented as graphical flows in Clinical Practice Guidelines (CPGs). For effective use of the CPGs in helping medical professionals in the treatment decision process, it is necessary to fully capture the guideline knowledge, particularly the contexts and their relationships in the graph. While several existing works have utilized these guidelines to create rule bases for Clinical Decision Support Systems, limited work has been done toward directly capturing the full medical knowledge contained in CPGs. This work proposes an approach to create a contextually enriched, faithful digital representation of National Comprehensive Cancer Network (NCCN) Cancer CPGs in the form of graphs using automated extraction and node & relationship classification. We also implement semantic enrichment of the model by using Large Language Models (LLMs) for node classification, achieving an accuracy of 80.86% and 88.47% with zero-shot learning and few-shot learning, respectively. Additionally, we introduce a methodology for answering natural language questions with constraints to guideline text by leveraging LLMs to extract the relevant subgraph from the guideline knowledge base. By generating natural language answers based on subgraph paths and semantic information, we mitigate the risk of incorrect answers and hallucination associated with LLMs, ensuring factual accuracy in medical domain Question Answering. 

**Abstract (ZH)**: 将以下关于临床实践指南（CPGs）中诊断流程和治疗路径更新建议的内容或标题翻译成中文，符合学术规范：

临床实践指南（CPGs）中记录了某一医疗条件的更新后的诊断流程和治疗路径推荐，通常以图形流程的形式呈现。为了在诊断决策过程中有效利用CPGs辅助医疗专业人员，需要全面捕捉指导原则知识，特别是图中的上下文及其关系。虽然已有几项研究利用这些指南创建临床决策支持系统的规则库，但直接从CPGs中提取完整医疗知识的工作相对较少。本研究提出了一种使用自动化提取和节点与关系分类方法来创建富含上下文、忠实表示国家综合癌症网络（NCCN）癌症指南的图的方法。我们还通过使用大规模语言模型（LLMs）对模型进行语义增强，分别在零样本学习和少量样本学习下，节点分类的准确率分别为80.86%和88.47%。此外，我们提出了一种利用LLMs从指南知识库中提取相关子图的方法，以应对自然语言问题，并提出了约束条件下的自然语言答案生成方法。通过基于子图路径和语义信息生成自然语言回答，我们减轻了LLMs在生成答案时可能出现的错误和虚构风险，确保医疗领域问答系统的事实准确性。 

---
# AdEval: Alignment-based Dynamic Evaluation to Mitigate Data Contamination in Large Language Models 

**Title (ZH)**: AdEval: 基于对齐的动态评估方法以减轻大型语言模型中的数据污染问题 

**Authors**: Yang Fan  

**Link**: [PDF](https://arxiv.org/pdf/2501.13983)  

**Abstract**: As Large Language Models (LLMs) are pretrained on massive-scale corpora, the issue of data contamination has become increasingly severe, leading to potential overestimation of model performance during evaluation. To address this, we propose AdEval (Alignment-based Dynamic Evaluation), a dynamic data evaluation method aimed at mitigating the impact of data contamination on evaluation reliability. AdEval extracts key knowledge points and main ideas to align dynamically generated questions with static data's core concepts. It also leverages online search to provide detailed explanations of related knowledge points, thereby creating high-quality evaluation samples with robust knowledge support. Furthermore, AdEval incorporates mechanisms to control the number and complexity of questions, enabling dynamic alignment and flexible adjustment. This ensures that the generated questions align with the complexity of static data while supporting varied complexity levels. Based on Bloom's taxonomy, AdEval conducts a multi-dimensional evaluation of LLMs across six cognitive levels: remembering, understanding, applying, analyzing, evaluating, and creating. Experimental results on multiple datasets demonstrate that AdEval effectively reduces the impact of data contamination on evaluation outcomes, enhancing both the fairness and reliability of the evaluation process. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在大规模语料库上进行预训练，数据污染问题日益严重，这可能导致在评估期间对模型性能的潜在高估。为应对这一挑战，我们提出了AdEval（基于对齐的动态评估），这是一种动态数据评估方法，旨在减轻数据污染对评估可靠性的负面影响。AdEval通过动态提取关键知识点和主要思想，将生成的问题与静态数据的核心概念相-align，同时利用在线搜索提供相关知识点的详细解释，从而生成高质量的评估样本，具有稳固的知识支持。此外，AdEval还整合了控制问题数量和复杂性的机制，实现了动态对齐和灵活调整。这确保了生成的问题与静态数据的复杂性相匹配，同时支持不同的复杂度水平。根据布卢姆 taxonomy，AdEval在六个认知层面：记忆、理解、应用、分析、评价和创造上对LLMs进行多维度评估。在多个数据集上的实验结果表明，AdEval有效地减少了数据污染对评估结果的影响，提高了评估过程的公平性和可靠性。 

---
# Re-ranking Using Large Language Models for Mitigating Exposure to Harmful Content on Social Media Platforms 

**Title (ZH)**: 使用大型语言模型重新排序以减轻社交媒体平台上有害内容的暴露风险 

**Authors**: Rajvardhan Oak, Muhammad Haroon, Claire Jo, Magdalena Wojcieszak, Anshuman Chhabra  

**Link**: [PDF](https://arxiv.org/pdf/2501.13977)  

**Abstract**: Social media platforms utilize Machine Learning (ML) and Artificial Intelligence (AI) powered recommendation algorithms to maximize user engagement, which can result in inadvertent exposure to harmful content. Current moderation efforts, reliant on classifiers trained with extensive human-annotated data, struggle with scalability and adapting to new forms of harm. To address these challenges, we propose a novel re-ranking approach using Large Language Models (LLMs) in zero-shot and few-shot settings. Our method dynamically assesses and re-ranks content sequences, effectively mitigating harmful content exposure without requiring extensive labeled data. Alongside traditional ranking metrics, we also introduce two new metrics to evaluate the effectiveness of re-ranking in reducing exposure to harmful content. Through experiments on three datasets, three models and across three configurations, we demonstrate that our LLM-based approach significantly outperforms existing proprietary moderation approaches, offering a scalable and adaptable solution for harm mitigation. 

**Abstract (ZH)**: 社交媒体平台利用基于机器学习（ML）和人工智能（AI）的推荐算法来最大化用户参与度，这可能导致用户无意间接触到有害内容。目前依赖于大量人工标注数据训练的分类器进行的管控努力，在规模性和适应新型危害方面存在困难。为了解决这些问题，我们提出了一种新的重排方法，利用大语言模型（LLMs）在零样本和少样本设置中进行处理。我们的方法能够动态评估和重新排列内容序列，有效地减少有害内容的暴露，而无需大量标注数据。除了传统的排名指标，我们还引入了两种新的指标来评估重新排列在减少有害内容暴露方面的有效性。通过在三个数据集、三种模型和三种配置上的实验，我们证明了基于LLM的方法显著优于现有的专有管控方法，提供了一种可扩展且可适应的有害内容缓解解决方案。 

---
# Towards Safer Social Media Platforms: Scalable and Performant Few-Shot Harmful Content Moderation Using Large Language Models 

**Title (ZH)**: 向着更安全的社交媒体平台迈进：基于大规模语言模型的可扩展高效少量样本有害内容审核方法 

**Authors**: Akash Bonagiri, Lucen Li, Rajvardhan Oak, Zeerak Babar, Magdalena Wojcieszak, Anshuman Chhabra  

**Link**: [PDF](https://arxiv.org/pdf/2501.13976)  

**Abstract**: The prevalence of harmful content on social media platforms poses significant risks to users and society, necessitating more effective and scalable content moderation strategies. Current approaches rely on human moderators, supervised classifiers, and large volumes of training data, and often struggle with scalability, subjectivity, and the dynamic nature of harmful content (e.g., violent content, dangerous challenge trends, etc.). To bridge these gaps, we utilize Large Language Models (LLMs) to undertake few-shot dynamic content moderation via in-context learning. Through extensive experiments on multiple LLMs, we demonstrate that our few-shot approaches can outperform existing proprietary baselines (Perspective and OpenAI Moderation) as well as prior state-of-the-art few-shot learning methods, in identifying harm. We also incorporate visual information (video thumbnails) and assess if different multimodal techniques improve model performance. Our results underscore the significant benefits of employing LLM based methods for scalable and dynamic harmful content moderation online. 

**Abstract (ZH)**: 社交媒体平台上有害内容的普遍存在对用户和社会构成了重大风险，因此迫切需要更有效且可扩展的内容审核策略。当前的方法依赖于人类审核员、监督分类器和大量训练数据，常常难以应对可扩展性、主观性和有害内容的动态性（如暴力内容、危险挑战趋势等）带来的挑战。为填补这些空白，我们利用大型语言模型（LLMs）通过上下文学习进行少量样本动态内容审核。通过在多种LLM上进行大量实验，我们展示了我们的少量样本方法在识别危害方面可以超越现有的专有基准方法（如Perspective和OpenAI审核）以及此前的最佳少量样本学习方法。此外，我们还结合了视觉信息（视频缩略图），并评估了不同多模态技术是否能提升模型性能。我们的研究结果强调了使用基于LLM的方法进行在线有害内容的可扩展和动态审核的巨大优势。 

---
# Benchmarking Generative AI for Scoring Medical Student Interviews in Objective Structured Clinical Examinations (OSCEs) 

**Title (ZH)**: Benchmarking 生成式人工智能在客观结构化临床考试（OSCEs）中评分医学学生面试中的应用 

**Authors**: Jadon Geathers, Yann Hicke, Colleen Chan, Niroop Rajashekar, Justin Sewell, Susannah Cornes, Rene Kizilcec, Dennis Shung  

**Link**: [PDF](https://arxiv.org/pdf/2501.13957)  

**Abstract**: Introduction. Objective Structured Clinical Examinations (OSCEs) are widely used to assess medical students' communication skills, but scoring interview-based assessments is time-consuming and potentially subject to human bias. This study explored the potential of large language models (LLMs) to automate OSCE evaluations using the Master Interview Rating Scale (MIRS).
Methods. We compared the performance of four state-of-the-art LLMs (GPT-4o, Claude 3.5, Llama 3.1, and Gemini 1.5 Pro) in evaluating OSCE transcripts across all 28 items of the MIRS under the conditions of zero-shot, chain-of-thought (CoT), few-shot, and multi-step prompting. The models were benchmarked against a dataset of 10 OSCE cases with 174 expert consensus scores available. Model performance was measured using three accuracy metrics (exact, off-by-one, thresholded).
Results. Averaging across all MIRS items and OSCE cases, LLMs performed with low exact accuracy (0.27 to 0.44), and moderate to high off-by-one accuracy (0.67 to 0.87) and thresholded accuracy (0.75 to 0.88). A zero temperature parameter ensured high intra-rater reliability ($\alpha = 0.98$ for GPT-4o). CoT, few-shot, and multi-step techniques proved valuable when tailored to specific assessment items. The performance was consistent across MIRS items independent of encounter phases and communication domains.
Conclusion. We demonstrated the feasibility of AI-assisted OSCE evaluation and provided benchmarking of multiple LLMs across multiple prompt techniques. Our work provides a baseline performance assessment for LLMs that lays a foundation for future research in automated assessment of clinical communication skills. 

**Abstract (ZH)**: 介绍。结构化临床考试（OSCEs）广泛用于评估医学生沟通技能，但评分面试评估耗时且可能受到人类偏见的影响。本研究探讨了大型语言模型（LLMs）在使用《主面试评分量表》（MIRS）自动化OSCE评估方面的潜力。

方法。我们比较了四款最先进的LLMs（GPT-4o、Claude 3.5、Llama 3.1和Gemini 1.5 Pro）在零样本、链式思考（CoT）、少样本和多步骤提示条件下评估OSCE转录材料的性能。这些模型在包含10个OSCE案例和174个专家一致评分的数据集上进行了基准测试。模型性能通过三种准确性指标（精确匹配、相差一、阈值）进行了测量。

结果。总体而言，LLMs在所有MIRS项目和OSCE案例中的精确匹配准确性较低（0.27到0.44），但在相差一和阈值准确性方面中等到高（0.67到0.87 和0.75到0.88）。GPT-4o使用零温度参数确保了高评分者内一致度（$\alpha = 0.98$）。链式思考、少样本和多步骤技术在针对特定评估项进行调整时显得尤为重要。性能在MIRS项目上保持一致，不受遇诊阶段和沟通领域的影响。

结论。我们展示了人工智能辅助OSCE评估的可行性，并对多种LLMs在多种提示技术下的表现进行了基准测试。我们的研究为未来在临床沟通技能自动化评估领域的研究奠定了基础，并提供了LLMs基线性能评估，为其在该领域的进一步应用提供了依据。 

---
# Guided Persona-based AI Surveys: Can we replicate personal mobility preferences at scale using LLMs? 

**Title (ZH)**: 基于引导人物的AI调查：我们能否使用大语言模型（LLMs）大规模复制个人的出行偏好？ 

**Authors**: Ioannis Tzachristas, Santhanakrishnan Narayanan, Constantinos Antoniou  

**Link**: [PDF](https://arxiv.org/pdf/2501.13955)  

**Abstract**: This study explores the potential of Large Language Models (LLMs) to generate artificial surveys, with a focus on personal mobility preferences in Germany. By leveraging LLMs for synthetic data creation, we aim to address the limitations of traditional survey methods, such as high costs, inefficiency and scalability challenges. A novel approach incorporating "Personas" - combinations of demographic and behavioural attributes - is introduced and compared to five other synthetic survey methods, which vary in their use of real-world data and methodological complexity. The MiD 2017 dataset, a comprehensive mobility survey in Germany, serves as a benchmark to assess the alignment of synthetic data with real-world patterns. The results demonstrate that LLMs can effectively capture complex dependencies between demographic attributes and preferences while offering flexibility to explore hypothetical scenarios. This approach presents valuable opportunities for transportation planning and social science research, enabling scalable, cost-efficient and privacy-preserving data generation. 

**Abstract (ZH)**: 本研究探讨了大型语言模型（LLMs）在生成虚拟调查方面的潜力，重点关注德国的个人移动偏好。通过利用LLMs创建合成数据，我们旨在解决传统调查方法的局限性，如成本高昂、效率低下和可扩展性挑战。提出了结合“角色”（Personas）的新方法，角色由人口统计学和行为特征的组合构成，并将其与五种其他合成调查方法进行比较，这些方法在使用真实数据和方法复杂性方面有所不同。以德国的MiD 2017移动调查集为基准，评估合成数据与真实模式的一致性。研究结果表明，LLMs能够有效地捕捉人口统计学特征与偏好之间的复杂关系，并提供探索假设场景的灵活性。这种方法为交通规划和社会科学研究提供了有价值的机遇，能够实现大规模、成本效益高且隐私保护的数据生成。 

---
# A Layered Multi-Expert Framework for Long-Context Mental Health Assessments 

**Title (ZH)**: 一种分层多专家框架，用于长上下文心理健康评估 

**Authors**: Jinwen Tang, Qiming Guo, Wenbo Sun, Yi Shang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13951)  

**Abstract**: Long-form mental health assessments pose unique challenges for large language models (LLMs), which often exhibit hallucinations or inconsistent reasoning when handling extended, domain-specific contexts. We introduce Stacked Multi-Model Reasoning (SMMR), a layered framework that leverages multiple LLMs and specialized smaller models as coequal 'experts'. Early layers isolate short, discrete subtasks, while later layers integrate and refine these partial outputs through more advanced long-context models. We evaluate SMMR on the DAIC-WOZ depression-screening dataset and 48 curated case studies with psychiatric diagnoses, demonstrating consistent improvements over single-model baselines in terms of accuracy, F1-score, and PHQ-8 error reduction. By harnessing diverse 'second opinions', SMMR mitigates hallucinations, captures subtle clinical nuances, and enhances reliability in high-stakes mental health assessments. Our findings underscore the value of multi-expert frameworks for more trustworthy AI-driven screening. 

**Abstract (ZH)**: 长篇心理健康评估对大型语言模型（LLMs）提出了独特的挑战，这些模型在处理扩展的、领域特定的背景时经常表现出幻觉或不一致的推理现象。我们提出了堆叠多模型推理（Stacked Multi-Model Reasoning, SMMR），这是一种分层框架，利用多个LLMs和专门的小型模型作为同等的“专家”。早期层隔离短暂的、离散的子任务，而后期层则通过更为高级的长上下文模型整合并精炼这些部分输出。我们在DAIC-WOZ抑郁症筛查数据集和48例经过精心筛选的精神疾病病例中对SMMR进行了评估，展示了在准确率、F1分数和PHQ-8误差减少方面相对于单模型基线的一致性改进。通过利用多样化的“第二意见”，SMMR减轻了幻觉现象，捕捉到了细微的临床差异，并增强了高度敏感的心理健康评估的可靠性。我们的研究结果强调了多专家框架对于更可靠的人工智能驱动筛查的价值。 

---
# A Comprehensive Survey on Integrating Large Language Models with Knowledge-Based Methods 

**Title (ZH)**: 大型语言模型与知识基础方法集成的综合调研 

**Authors**: Lilian Some, Wenli Yang, Michael Bain, Byeong Kang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13947)  

**Abstract**: The rapid development of artificial intelligence has brought about substantial advancements in the field. One promising direction is the integration of Large Language Models (LLMs) with structured knowledge-based systems. This approach aims to enhance AI capabilities by combining the generative language understanding of LLMs with the precise knowledge representation of structured systems. This survey explores the synergy between LLMs and knowledge bases, focusing on real-world applications and addressing associated technical, operational, and ethical challenges. Through a comprehensive literature review, the study identifies critical issues and evaluates existing solutions. The paper highlights the benefits of integrating generative AI with knowledge bases, including improved data contextualization, enhanced model accuracy, and better utilization of knowledge resources. The findings provide a detailed overview of the current state of research, identify key gaps, and offer actionable recommendations. These insights contribute to advancing AI technologies and support their practical deployment across various sectors. 

**Abstract (ZH)**: 随着人工智能的迅速发展，该领域取得了显著的进步。一个有前途的方向是将大型语言模型（LLMs）与结构化知识系统集成。这种方法旨在通过结合LLMs的生成语言理解和结构化系统精确的知识表示来增强人工智能的能力。本文综述了LLMs与知识库之间的协同作用，重点关注实际应用，并解决相关的技术和操作性挑战以及伦理问题。通过全面的文献综述，研究识别出关键问题并评估现有解决方案。文章强调了将生成式AI与知识库集成的好处，包括改善数据上下文、提高模型准确性以及更好地利用知识资源。研究结果提供了当前研究状态的详细概述，指出现有研究的关键缺口，并提出可操作建议。这些见解有助于推动人工智能技术的进步，并支持其在各种领域的实际部署。 

---
# Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks 

**Title (ZH)**: 使用代理AI基座语言框架减轻幻觉现象 

**Authors**: Diego Gosmar, Deborah A. Dahl  

**Link**: [PDF](https://arxiv.org/pdf/2501.13946)  

**Abstract**: Hallucinations remain a significant challenge in current Generative AI models, undermining trust in AI systems and their reliability. This study investigates how orchestrating multiple specialized Artificial Intelligent Agents can help mitigate such hallucinations, with a focus on systems leveraging Natural Language Processing (NLP) to facilitate seamless agent interactions. To achieve this, we design a pipeline that introduces over three hundred prompts, purposefully crafted to induce hallucinations, into a front-end agent. The outputs are then systematically reviewed and refined by second- and third-level agents, each employing distinct large language models and tailored strategies to detect unverified claims, incorporate explicit disclaimers, and clarify speculative content. Additionally, we introduce a set of novel Key Performance Indicators (KPIs) specifically designed to evaluate hallucination score levels. A dedicated fourth-level AI agent is employed to evaluate these KPIs, providing detailed assessments and ensuring accurate quantification of shifts in hallucination-related behaviors. A core component of this investigation is the use of the OVON (Open Voice Network) framework, which relies on universal NLP-based interfaces to transfer contextual information among agents. Through structured JSON messages, each agent communicates its assessment of the hallucination likelihood and the reasons underlying questionable content, thereby enabling the subsequent stage to refine the text without losing context. The results demonstrate that employing multiple specialized agents capable of interoperating with each other through NLP-based agentic frameworks can yield promising outcomes in hallucination mitigation, ultimately bolstering trust within the AI community. 

**Abstract (ZH)**: 幻觉仍然是当前生成型人工智能模型中的重大挑战，削弱了人们对人工智能系统及其可靠性的信任。本研究探讨了如何通过协调多个专门的人工智能代理来减轻这样的幻觉，重点关注利用自然语言处理（NLP）促进代理间无缝交互的系统。为了实现这一目标，我们设计了一条管线，将超过三百个旨在诱发幻觉的提示引入前端代理。然后，这些输出由第二级和第三级代理系统地审查和修订，每级代理使用不同的大型语言模型和定制策略来检测未验证的声明、纳入明确的免责声明，并澄清推测性内容。此外，我们引入了一组新的关键绩效指标（KPI），专门设计用于评估幻觉评分水平。一个专门的第四级AI代理用于评估这些KPI，提供详细的评估并确保幻觉相关行为变化的准确量化。本研究的核心成分为采用OVON（开放语音网络）框架，该框架依赖于基于通用NLP的接口在代理之间传递上下文信息。通过结构化的JSON消息，每个代理传达其对幻觉可能性的评估以及可疑内容的原因，从而使得后一阶段能够不丢失上下文地调整文本。研究结果表明，通过利用能够通过基于NLP的代理框架相互协作的多个专门代理，可以在幻觉减轻方面取得令人鼓舞的结果，最终增强人工智能社区的信任度。 

---
# Fast Think-on-Graph: Wider, Deeper and Faster Reasoning of Large Language Model on Knowledge Graph 

**Title (ZH)**: 快速图思考：大型语言模型在知识图谱中的更宽、更深、更快推理 

**Authors**: Xujian Liang, Zhaoquan Gu  

**Link**: [PDF](https://arxiv.org/pdf/2501.14300)  

**Abstract**: Graph Retrieval Augmented Generation (GRAG) is a novel paradigm that takes the naive RAG system a step further by integrating graph information, such as knowledge graph (KGs), into large-scale language models (LLMs) to mitigate hallucination. However, existing GRAG still encounter limitations: 1) simple paradigms usually fail with the complex problems due to the narrow and shallow correlations capture from KGs 2) methods of strong coupling with KGs tend to be high computation cost and time consuming if the graph is dense. In this paper, we propose the Fast Think-on-Graph (FastToG), an innovative paradigm for enabling LLMs to think ``community by community" within KGs. To do this, FastToG employs community detection for deeper correlation capture and two stages community pruning - coarse and fine pruning for faster retrieval. Furthermore, we also develop two Community-to-Text methods to convert the graph structure of communities into textual form for better understanding by LLMs. Experimental results demonstrate the effectiveness of FastToG, showcasing higher accuracy, faster reasoning, and better explainability compared to the previous works. 

**Abstract (ZH)**: Graph Retrieval Augmented Generation (GRAG) 是一种新颖的框架，它在基础的 RAG 系统基础上进一步整合了图信息（如知识图谱 KGs），以减轻幻觉现象。然而，现有的 GRAG 仍然存在一些局限性：1) 简单的框架在处理复杂问题时往往因 KG 中浅显和狭窄的相关性捕捉而失效；2) 与 KG 强耦合的方法如果图密集，则可能产生高计算成本和耗时的问题。本文中，我们提出了 Fast Think-on-Graph (FastToG)，这是一种创新的框架，旨在使大规模语言模型 (LLMs) 在知识图谱中以“社区为单位”进行思考。为了实现这一点，FastToG 应用了社区检测以捕捉更深层次的相关性，并通过粗略和精细的社区裁剪实现了更快的检索。此外，我们还开发了两种社区到文本的方法，将社区的图结构转换为文本形式，以更好地被语言模型理解。实验结果表明，FastToG 的有效性，其展示了比以往工作更高的准确性、更快的推理速度和更好的解释性。 

---
# Evaluating Computational Accuracy of Large Language Models in Numerical Reasoning Tasks for Healthcare Applications 

**Title (ZH)**: 评估大型语言模型在健康-care领域数值推理任务中计算准确性的研究 

**Authors**: Arjun R. Malghan  

**Link**: [PDF](https://arxiv.org/pdf/2501.13936)  

**Abstract**: Large Language Models (LLMs) have emerged as transformative tools in the healthcare sector, demonstrating remarkable capabilities in natural language understanding and generation. However, their proficiency in numerical reasoning, particularly in high-stakes domains like in clinical applications, remains underexplored. Numerical reasoning is critical in healthcare applications, influencing patient outcomes, treatment planning, and resource allocation. This study investigates the computational accuracy of LLMs in numerical reasoning tasks within healthcare contexts. Using a curated dataset of 1,000 numerical problems, encompassing real-world scenarios such as dosage calculations and lab result interpretations, the performance of a refined LLM based on the GPT-3 architecture was evaluated. The methodology includes prompt engineering, integration of fact-checking pipelines, and application of regularization techniques to enhance model accuracy and generalization. Key metrics such as precision, recall, and F1-score were utilized to assess the model's efficacy. The results indicate an overall accuracy of 84.10%, with improved performance in straightforward numerical tasks and challenges in multi-step reasoning. The integration of a fact-checking pipeline improved accuracy by 11%, underscoring the importance of validation mechanisms. This research highlights the potential of LLMs in healthcare numerical reasoning and identifies avenues for further refinement to support critical decision-making in clinical environments. The findings aim to contribute to the development of reliable, interpretable, and contextually relevant AI tools for healthcare. 

**Abstract (ZH)**: 大型语言模型（LLMs）已在医疗保健领域展现出革命性的工具作用，展示了在自然语言理解与生成方面非凡的能力。然而，在如临床应用等高风险领域中，它们在数值推理方面的能力尚未得到充分探索。数值推理在医疗保健应用中至关重要，它影响患者结果、治疗计划和资源分配。本研究探讨了LLMs在医疗保健背景下数值推理任务中的计算准确性。通过使用包含1,000个数值问题的定制数据集，涵盖如剂量计算和化验结果解释等真实场景，评估了一个基于GPT-3架构精炼后的LLM的性能。该研究方法包括prompt工程、整合事实核查管道以及应用正则化技术，以提高模型的准确性和泛化能力。精确度、召回率和F1分数等关键指标被用来评估模型的效果。结果表明，整体准确率为84.10%，在简单的数值任务上的表现较好，但在多步推理方面存在挑战。事实核查管道的整合提高了11%的准确性，突显了验证机制的重要性。研究揭示了LLMs在医疗保健数值推理中的潜力，并指出了进一步细化以支持临床环境中关键决策的方向。研究旨在促进可靠、可解释和上下文相关的人工智能工具在医疗保健领域的开发。 

---
# Extracting Problem Structure with LLMs for Optimized SAT Local Search 

**Title (ZH)**: 使用大型语言模型提取问题结构以优化SAT局部搜索 

**Authors**: André Schilder, Stefan Szeider  

**Link**: [PDF](https://arxiv.org/pdf/2501.14630)  

**Abstract**: Local search preprocessing makes Conflict-Driven Clause Learning (CDCL) solvers faster by providing high-quality starting points and modern SAT solvers have incorporated this technique into their preprocessing steps. However, these tools rely on basic strategies that miss the structural patterns in problems. We present a method that applies Large Language Models (LLMs) to analyze Python-based encoding code. This reveals hidden structural patterns in how problems convert into SAT. Our method automatically generates specialized local search algorithms that find these patterns and use them to create strong initial assignments. This works for any problem instance from the same encoding type. Our tests show encouraging results, achieving faster solving times compared to baseline preprocessing systems. 

**Abstract (ZH)**: 局部搜索预处理通过提供高质量的起始点使冲突驱动子句学习（CDCL）求解器更加快速。现代SAT求解器已经将这种技术纳入其预处理步骤中。然而，这些工具依靠基本策略，无法捕捉问题中的结构模式。我们提出了一种方法，利用大型语言模型（LLMs）分析基于Python的编码代码，从而揭示问题转换为SAT中的隐藏结构模式。该方法自动生成专门化的局部搜索算法，用于发现这些模式并利用它们创建强初始赋值。这种方法适用于同一编码类型下的任何问题实例。我们的测试显示了令人鼓舞的结果，相较于基线预处理系统，能够实现更快的求解时间。 

---
# VERUS-LM: a Versatile Framework for Combining LLMs with Symbolic Reasoning 

**Title (ZH)**: VERUS-LM：一种将大规模语言模型与符号推理相结合的通用框架 

**Authors**: Benjamin Callewaert, Simon Vandevelde, Joost Vennekens  

**Link**: [PDF](https://arxiv.org/pdf/2501.14540)  

**Abstract**: A recent approach to neurosymbolic reasoning is to explicitly combine the strengths of large language models (LLMs) and symbolic solvers to tackle complex reasoning tasks. However, current approaches face significant limitations, including poor generalizability due to task-specific prompts, inefficiencies caused by the lack of separation between knowledge and queries, and restricted inferential capabilities. These shortcomings hinder their scalability and applicability across diverse domains. In this paper, we introduce VERUS-LM, a novel framework designed to address these challenges. VERUS-LM employs a generic prompting mechanism, clearly separates domain knowledge from queries, and supports a wide range of different logical reasoning tasks. This framework enhances adaptability, reduces computational cost, and allows for richer forms of reasoning, such as optimization and constraint satisfaction. We show that our approach succeeds in diverse reasoning on a novel dataset, markedly outperforming LLMs. Additionally, our system achieves competitive results on common reasoning benchmarks when compared to other state-of-the-art approaches, and significantly surpasses them on the difficult AR-LSAT dataset. By pushing the boundaries of hybrid reasoning, VERUS-LM represents a significant step towards more versatile neurosymbolic AI systems 

**Abstract (ZH)**: 近年来，神经符号推理的一种方法是明确结合大规模语言模型（LLMs）和符号求解器的优势，以应对复杂的推理任务。然而，当前的方法面临着显著的局限性，包括由于任务特定的提示导致的泛化能力差、由于知识与查询之间缺乏分离导致的效率低下，以及推理能力的限制。这些不足限制了它们在不同领域的可扩展性和适用性。在本文中，我们介绍了一种名为VERUS-LM的新型框架，旨在解决这些挑战。VERUS-LM采用了通用的提示机制，明确地将领域知识与查询分离，并支持多种不同的逻辑推理任务。该框架增强了适应性，降低了计算成本，并允许进行更加丰富的推理形式，如优化和约束满足。我们的方法在新型数据集上的多样性推理中取得了成功，显著优于LLMs。此外，当与其他最先进的方法进行比较时，我们的系统在常用推理基准测试中取得了竞争力的结果，并在困难的AR-LSAT数据集中明显超越了它们。通过推动混合推理的界限，VERUS-LM代表了更通用的神经符号AI系统的重大进步。 

---
# MASTER: A Multi-Agent System with LLM Specialized MCTS 

**Title (ZH)**: MASTER：一种专门化的LLM多代理系统与MCTS结合的架构 

**Authors**: Bingzheng Gan, Yufan Zhao, Tianyi Zhang, Jing Huang, Yusu Li, Shu Xian Teo, Changwang Zhang, Wei Shi  

**Link**: [PDF](https://arxiv.org/pdf/2501.14304)  

**Abstract**: Large Language Models (LLM) are increasingly being explored for problem-solving tasks. However, their strategic planning capability is often viewed with skepticism. Recent studies have incorporated the Monte Carlo Tree Search (MCTS) algorithm to augment the planning capacity of LLM. Despite its potential, MCTS relies on extensive sampling simulations to approximate the true reward distribution, leading to two primary issues. Firstly, MCTS is effective for tasks like the Game of Go, where simulation results can yield objective rewards (e.g., 1 for a win and 0 for a loss). However, for tasks such as question answering, the result of a simulation is the answer to the question, which cannot obtain an objective reward without the ground truth. Secondly, obtaining statistically significant reward estimations typically requires a sample size exceeding 30 simulations, resulting in excessive token usage and time consumption. To address these challenges, we present Multi-Agent System with Tactical Execution and Reasoning using LLM Specialized MCTS (MASTER), a novel framework that coordinates agent recruitment and communication using LLM specialized MCTS. This system autonomously adjusts the number of agents based on task complexity and ensures focused communication among them. Comprehensive experiments across various tasks demonstrate the effectiveness of our proposed framework. It achieves 76% accuracy on HotpotQA and 80% on WebShop, setting new state-of-the-art performance on these datasets. 

**Abstract (ZH)**: 大型语言模型（LLM）越来越多地被应用于问题解决任务中。然而，人们对其战略规划能力持怀疑态度。近期的研究将蒙特卡洛树搜索（MCTS）算法引入LLM，以增强其规划能力。尽管MCTS具有潜力，但它依赖于广泛的采样模拟来近似真实的奖励分布，导致了两个主要问题。首先，MCTS在围棋等任务中表现良好，因为这些任务的模拟结果可以产生客观奖励（例如胜利计1分，失败计0分）。然而，对于诸如问答等任务，模拟的结果只是问题的答案，没有 ground truth 时很难获得客观奖励。其次，通常需要超过30次模拟来获得统计上显著的奖励估计，这会导致大量的 token 使用和时间消耗。为了解决这些问题，我们提出了一个名为 Multi-Agent System with Tactical Execution and Reasoning using LLM Specialized MCTS（MASTER）的新型框架，该框架利用LLM专项MCTS协调代理的招募和沟通。此系统根据任务复杂性自主调整代理数量，并确保它们之间的集中沟通。跨多种任务的综合实验表明，我们提出的框架具有有效性。它在HotpotQA上的准确率达到76%，在WebShop上的准确率达到80%，在这些数据集上设置了新的最先进的性能标准。 

---
# A Zero-Shot LLM Framework for Automatic Assignment Grading in Higher Education 

**Title (ZH)**: 面向高等教育中自动评分任务的零样本大型语言模型框架 

**Authors**: Calvin Yeung, Jeff Yu, King Chau Cheung, Tat Wing Wong, Chun Man Chan, Kin Chi Wong, Keisuke Fujii  

**Link**: [PDF](https://arxiv.org/pdf/2501.14305)  

**Abstract**: Automated grading has become an essential tool in education technology due to its ability to efficiently assess large volumes of student work, provide consistent and unbiased evaluations, and deliver immediate feedback to enhance learning. However, current systems face significant limitations, including the need for large datasets in few-shot learning methods, a lack of personalized and actionable feedback, and an overemphasis on benchmark performance rather than student experience. To address these challenges, we propose a Zero-Shot Large Language Model (LLM)-Based Automated Assignment Grading (AAG) system. This framework leverages prompt engineering to evaluate both computational and explanatory student responses without requiring additional training or fine-tuning. The AAG system delivers tailored feedback that highlights individual strengths and areas for improvement, thereby enhancing student learning outcomes. Our study demonstrates the system's effectiveness through comprehensive evaluations, including survey responses from higher education students that indicate significant improvements in motivation, understanding, and preparedness compared to traditional grading methods. The results validate the AAG system's potential to transform educational assessment by prioritizing learning experiences and providing scalable, high-quality feedback. 

**Abstract (ZH)**: 自动评分已成为教育技术中的一个关键技术工具，因为它能够高效地评估大量学生作业，提供一致且无偏见的评价，并立即提供反馈以提高学习效果。然而，当前的系统面临着显著的限制，包括在少数样本学习方法中需要大量数据集、缺乏个性化和可操作的反馈，以及过分强调基准性能而非学生体验。为了应对这些挑战，我们提出了一种基于零样本大规模语言模型（LLM）的自动作业评分（AAG）系统。该框架利用提示工程来评估学生的计算性和解释性回答，无需额外的训练或微调。AAG系统提供定制化的反馈，强调学生的强项和需要改进的地方，从而提高学生的学习成果。我们的研究通过全面评估来证明系统的有效性，包括来自高等教育学生的调查反馈表明，与传统评分方法相比，AAG系统能够显著提高动机、理解能力和应对准备。研究结果验证了AAG系统在优先考虑学习体验并通过提供可扩展和高质量的反馈来变革教育评估方面的重要潜力。 

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