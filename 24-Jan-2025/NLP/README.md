# CRPO: Confidence-Reward Driven Preference Optimization for Machine Translation 

**Title (ZH)**: CRPO：基于置信度-奖励驱动的偏�.GetFileNameTooLongException 

**Authors**: Guofeng Cui, Pichao Wang, Yang Liu, Zemian Ke, Zhu Liu, Vimal Bhat  

**Link**: [PDF](https://arxiv.org/pdf/2501.13927)  

**Abstract**: Large language models (LLMs) have shown great potential in natural language processing tasks, but their application to machine translation (MT) remains challenging due to pretraining on English-centric data and the complexity of reinforcement learning from human feedback (RLHF). Direct Preference Optimization (DPO) has emerged as a simpler and more efficient alternative, but its performance depends heavily on the quality of preference data. To address this, we propose Confidence-Reward driven Preference Optimization (CRPO), a novel method that combines reward scores with model confidence to improve data selection for fine-tuning. CRPO selects challenging sentence pairs where the model is uncertain or underperforms, leading to more effective learning. While primarily designed for LLMs, CRPO also generalizes to encoder-decoder models like NLLB, demonstrating its versatility. Empirical results show that CRPO outperforms existing methods such as RS-DPO, RSO and MBR score in both translation accuracy and data efficiency. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在自然语言处理任务中显示出了巨大的潜力，但在将其应用于机器翻译（MT）时仍面临挑战，主要原因是这些模型在预训练过程中使用了大量的以英语为中心的数据，以及从人类反馈中进行强化学习（RLHF）的复杂性。直接偏好优化（DPO）作为一种更简单和高效的替代方法已经出现，但其性能高度依赖于偏好数据的质量。为了解决这一问题，我们提出了一种新的方法——基于置信度和奖励驱动的偏好优化（CRPO，Confidence-Reward Driven Preference Optimization），该方法结合了奖励分数和模型置信度来改善用于微调的数据选择。CRPO 选择模型不确定或表现不佳的充满挑战的句对，从而提高学习效果。虽然 CRPO 主要针对 LLMs 设计，但其也适用于像 NLLB 这样的编码解码模型，展示了其广泛的适用性。实验证明，与现有的方法如 RS-DPO、RSO 和 MBR 分数相比，CRPO 在翻译准确性和数据效率方面均表现更优。 

---
# The Breeze 2 Herd of Models: Traditional Chinese LLMs Based on Llama with Vision-Aware and Function-Calling Capabilities 

**Title (ZH)**: 《轻风2模型 herd：基于LLama的傳統中文大型语言模型，具有视觉意识和函数调用能力》

注释：
1. "The Breeze 2 Herd of Models" 被翻译为 "轻风2模型 herd"，这里的 "herd" 是指一组模型或多个模型的集合。
2. "Traditional Chinese LLMs" 被翻译为 "基于LLama的傳統中文大型语言模型"，其中“LLM”通常指的是“大型语言模型”。
3. "Vision-Aware" 被翻译为 "视觉意识"，这指的是模型具有处理视觉信息的能力。
4. "Function-Calling Capabilities" 被翻译为 "函数调用能力"，这指的是模型能够调用外部函数或执行特定任务的能力。 

**Authors**: Chan-Jan Hsu, Chia-Sheng Liu, Meng-Hsi Chen, Muxi Chen, Po-Chun Hsu, Yi-Chang Chen, Da-Shan Shiu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13921)  

**Abstract**: Breeze 2 is a suite of advanced multi-modal language models, available in 3B and 8B parameter configurations, specifically designed to enhance Traditional Chinese language representation. Building upon the Llama 3, Breeze 2 continues pretraining on an extensive corpus to enhance the linguistic and cultural heritage of Traditional Chinese. It incorporates vision-aware capabilities through a visual encoder and a bridge module, and supports function-calling via prompt templates and post-training on function-calling data. The effectiveness of Breeze 2 is benchmarked across various tasks, including Taiwan general knowledge, instruction-following, long context, function calling, and vision understanding. Furthermore, we showcase the capabilities of the its 3B model in a mobile application. We are publicly releasing all Breeze 2 models under the Llama 3 Community License. 

**Abstract (ZH)**: Breeze 2 是一套高级多模态语言模型，提供 3B 和 8B 参数配置，专门设计用于增强传统中文语言表示。基于 Llama 3，Breeze 2 继续在广泛的语料库上进行预训练，以增强传统中文的语言和文化内涵。它通过视觉编码器和桥接模块集成了视觉感知能力，并通过提示模板和函数调用数据的后续训练支持函数调用。Breeze 2 的效果在各类任务中进行了基准测试，包括台湾常识、指令遵循、长文本上下文、函数调用和视觉理解。此外，我们展示了其 3B 模型在移动应用程序中的能力。我们将根据 Llama 3 社区许可协议公开发布所有 Breeze 2 模型。 

---
# Analysis of Indic Language Capabilities in LLMs 

**Title (ZH)**: LLM中印度语能力分析 

**Authors**: Aatman Vaidya, Tarunima Prabhakar, Denny George, Swair Shah  

**Link**: [PDF](https://arxiv.org/pdf/2501.13912)  

**Abstract**: This report evaluates the performance of text-in text-out Large Language Models (LLMs) to understand and generate Indic languages. This evaluation is used to identify and prioritize Indic languages suited for inclusion in safety benchmarks. We conduct this study by reviewing existing evaluation studies and datasets; and a set of twenty-eight LLMs that support Indic languages. We analyze the LLMs on the basis of the training data, license for model and data, type of access and model developers. We also compare Indic language performance across evaluation datasets and find that significant performance disparities in performance across Indic languages. Hindi is the most widely represented language in models. While model performance roughly correlates with number of speakers for the top five languages, the assessment after that varies. 

**Abstract (ZH)**: 本报告评估了文本输入-文本输出大型语言模型（LLMs）在理解和生成印地语系语言方面的能力。通过现有评估研究和数据集以及支持印地语系语言的28个大型语言模型，我们对该研究进行了评估，以识别和优先考虑适合纳入安全性基准的印地语系语言。我们从训练数据、模型和数据的许可、访问类型以及模型开发者的角度分析了这些大型语言模型。此外，我们比较了不同评估数据集中印地语系语言的表现，并发现这些语言之间存在显著的表现差异。印地语是模型中最广泛代表的语言。虽然头部五种语言的模型表现大致与使用者数量成正比，但随后的语言评估结果则有所不同。 

---
# GUI-Bee: Align GUI Action Grounding to Novel Environments via Autonomous Exploration 

**Title (ZH)**: GUI-Bee: 通过自主探索将GUI操作定位映射到新型环境中 

**Authors**: Yue Fan, Handong Zhao, Ruiyi Zhang, Yu Shen, Xin Eric Wang, Gang Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13896)  

**Abstract**: Graphical User Interface (GUI) action grounding is a critical step in GUI automation that maps language instructions to actionable elements on GUI screens. Most recent works of GUI action grounding leverage large GUI datasets to fine-tune MLLMs. However, the fine-tuning data always covers limited GUI environments, and we find the performance of the resulting model deteriorates in novel environments. We argue that the GUI grounding models should be further aligned to the novel environments to reveal their full potential, when the inference is known to involve novel environments, i.e., environments not used during the previous fine-tuning. To realize this, we first propose GUI-Bee, an MLLM-based autonomous agent, to collect high-quality, environment-specific data through exploration and then continuously fine-tune GUI grounding models with the collected data. Our agent leverages a novel Q-value-Incentive In-Context Reinforcement Learning (Q-ICRL) method to optimize exploration efficiency and data quality. Additionally, we introduce NovelScreenSpot, a benchmark for testing how well the data can help align GUI action grounding models to novel environments and demonstrate the effectiveness of data collected by GUI-Bee in the experiments. Furthermore, we conduct an ablation study to validate the Q-ICRL method in enhancing the efficiency of GUI-Bee. Project page: this https URL 

**Abstract (ZH)**: 图形用户界面（GUI）动作定位是GUI自动化中的一个关键步骤，它将语言指令映射到GUI屏幕上的可操作元素。最近的许多GUI动作定位工作利用大规模的GUI数据集对深度学习模型进行微调。然而，这些微调数据通常仅覆盖有限的GUI环境，我们发现模型在新型环境中表现不佳。我们认为，在推理涉及新型环境（即，在先前微调过程中未使用的环境）时，GUI定位模型应进一步与这些新型环境对齐，以发挥其全部潜力。为此，我们首先提出了一种基于MLLM的自主代理GUI-Bee，通过探索收集高质量的环境特定数据，然后持续使用收集的数据对GUI定位模型进行微调。我们的代理利用一种新颖的Q值激励内部强化学习（Q-ICRL）方法来优化探索效率和数据质量。此外，我们引入了NovelScreenSpot基准，以测试数据如何帮助将GUI动作定位模型与新型环境对齐，并通过实验展示了GUI-Bee收集的数据的有效性。我们还进行了消融研究，验证Q-ICRL方法如何提高GUI-Bee的效率。项目页面：[此处链接](this https URL) 

---
# A RAG-Based Institutional Assistant 

**Title (ZH)**: 基于RAG的机构助手 

**Authors**: Gustavo Kuratomi, Paulo Pirozelli, Fabio G. Cozman, Sarajane M. Peres  

**Link**: [PDF](https://arxiv.org/pdf/2501.13880)  

**Abstract**: Although large language models (LLMs) demonstrate strong text generation capabilities, they struggle in scenarios requiring access to structured knowledge bases or specific documents, limiting their effectiveness in knowledge-intensive tasks. To address this limitation, retrieval-augmented generation (RAG) models have been developed, enabling generative models to incorporate relevant document fragments into their inputs. In this paper, we design and evaluate a RAG-based virtual assistant specifically tailored for the University of São Paulo. Our system architecture comprises two key modules: a retriever and a generative model. We experiment with different types of models for both components, adjusting hyperparameters such as chunk size and the number of retrieved documents. Our optimal retriever model achieves a Top-5 accuracy of 30%, while our most effective generative model scores 22.04\% against ground truth answers. Notably, when the correct document chunks are supplied to the LLMs, accuracy significantly improves to 54.02%, an increase of over 30 percentage points. Conversely, without contextual input, performance declines to 13.68%. These findings highlight the critical role of database access in enhancing LLM performance. They also reveal the limitations of current semantic search methods in accurately identifying relevant documents and underscore the ongoing challenges LLMs face in generating precise responses. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）表现出强大的文本生成能力，但在需要访问结构化知识库或特定文档的场景中，它们的表现却大打折扣，从而限制了它们在知识密集型任务中的效果。为了解决这一局限，已经开发出了检索增强生成（RAG）模型，使生成模型能够将相关的文档片段纳入输入中。在本文中，我们为圣保罗大学设计并评估了一个专门的RAG虚拟助手系统。该系统架构包括两个关键模块：检索器和生成模型。对这两个组件中的不同类型的模型进行了实验，调整了诸如片段大小和检索文档数量等超参数。我们的最佳检索模型在前五名准确率达到30%，而我们最有效的生成模型的得分则为22.04%。值得注意的是，当正确的文档片段提供给LLMs时，准确率显著提高到54.02%，提高了超过30个百分点。相反，如果没有上下文输入，性能则下降到13.68%。这些发现凸显了数据库访问对于提升LLM性能的至关重要性。它们还揭示了当前语义搜索方法在准确识别相关文档方面的局限，并强调了LLMs在生成精确响应方面所面临的持续挑战。 

---
# Think Outside the Data: Colonial Biases and Systemic Issues in Automated Moderation Pipelines for Low-Resource Languages 

**Title (ZH)**: 跳出数据的框架：低资源语言自动审核管道中的殖民主义偏见与系统性问题 

**Authors**: Farhana Shahid, Mona Elswah, Aditya Vashistha  

**Link**: [PDF](https://arxiv.org/pdf/2501.13836)  

**Abstract**: Most social media users come from non-English speaking countries in the Global South. Despite the widespread prevalence of harmful content in these regions, current moderation systems repeatedly struggle in low-resource languages spoken there. In this work, we examine the challenges AI researchers and practitioners face when building moderation tools for low-resource languages. We conducted semi-structured interviews with 22 AI researchers and practitioners specializing in automatic detection of harmful content in four diverse low-resource languages from the Global South. These are: Tamil from South Asia, Swahili from East Africa, Maghrebi Arabic from North Africa, and Quechua from South America. Our findings reveal that social media companies' restrictions on researchers' access to data exacerbate the historical marginalization of these languages, which have long lacked datasets for studying online harms. Moreover, common preprocessing techniques and language models, predominantly designed for data-rich English, fail to account for the linguistic complexity of low-resource languages. This leads to critical errors when moderating content in Tamil, Swahili, Arabic, and Quechua, which are morphologically richer than English. Based on our findings, we establish that the precarities in current moderation pipelines are rooted in deep systemic inequities and continue to reinforce historical power imbalances. We conclude by discussing multi-stakeholder approaches to improve moderation for low-resource languages. 

**Abstract (ZH)**: 大多数社交媒体用户来自全球南方的非英语国家。尽管这些地区普遍存在有害内容，但当前的监管系统在处理这些低资源语言时屡次陷入困境。在本工作中，我们探讨了AI研究人员和从业者在为低资源语言构建监管工具时所面临的挑战。我们对22名专注于自动检测有害内容的AI研究人员和从业者进行了半结构化访谈，这些专家专门研究了来自全球南方四种不同的低资源语言，分别是南亚的泰米尔语、东非的斯瓦希里语、北非的北非阿拉伯语和南美洲的昆卡亚语。我们的研究发现表明，社交媒体公司在研究人员访问数据方面的限制加剧了这些语言的历史边缘化，由于长期以来缺乏研究网络危害的数据集，这些语言一直难以进行研究。此外，常用的预处理技术和语言模型，主要针对数据丰富的英语设计，未能考虑到低资源语言的复杂性。当在泰米尔语、斯瓦希里语、阿拉伯语和昆卡亚语中监管内容时，这会导致关键错误，因为这些语言的形态学丰富程度超过英语。基于我们的发现，我们指出当前监管管道中的脆弱性根植于深层次的系统不平等，并继续强化历史上的权力不平等。最后，我们讨论了多利益相关者的策略以改进低资源语言的监管。 

---
# Predicting Compact Phrasal Rewrites with Large Language Models for ASR Post Editing 

**Title (ZH)**: 使用大规模语言模型预测紧凑的短语重写以进行ASR后编辑 

**Authors**: Hao Zhang, Felix Stahlberg, Shankar Kumar  

**Link**: [PDF](https://arxiv.org/pdf/2501.13831)  

**Abstract**: Large Language Models (LLMs) excel at rewriting tasks such as text style transfer and grammatical error correction. While there is considerable overlap between the inputs and outputs in these tasks, the decoding cost still increases with output length, regardless of the amount of overlap. By leveraging the overlap between the input and the output, Kaneko and Okazaki (2023) proposed model-agnostic edit span representations to compress the rewrites to save computation. They reported an output length reduction rate of nearly 80% with minimal accuracy impact in four rewriting tasks. In this paper, we propose alternative edit phrase representations inspired by phrase-based statistical machine translation. We systematically compare our phrasal representations with their span representations. We apply the LLM rewriting model to the task of Automatic Speech Recognition (ASR) post editing and show that our target-phrase-only edit representation has the best efficiency-accuracy trade-off. On the LibriSpeech test set, our method closes 50-60% of the WER gap between the edit span model and the full rewrite model while losing only 10-20% of the length reduction rate of the edit span model. 

**Abstract (ZH)**: 大型语言模型（LLMs）在文本风格转换和语法错误修正等任务中表现优异。尽管这些任务的输入和输出之间存在很大的重叠，但解码成本仍然随着输出长度的增加而增加，不受重叠程度的影响。通过利用输入和输出之间的重叠，Kaneko和Okazaki（2023）提出了一种模型无关的编辑短语表示方法，以压缩重写内容并节省计算资源。他们在四个重写任务中报告了在几乎不影响准确性的前提下减少了近80%的输出长度。在本文中，我们提出了一种受基于短语的统计机器翻译启发的编辑短语表示方法。我们系统地比较了我们的短语表示方法与区间表示方法。我们将LLM重写模型应用于自动语音识别（ASR）后编辑任务，并展示了我们仅目标短语的编辑表示方法在效率-准确性的权衡上表现最优。在LibriSpeech测试集上，我们的方法在减少了50-60%的编辑区间模型与完整重写模型之间的单词错误率差距的同时，仅损失了编辑区间模型长度减少率的10-20%。 

---
# Hallucinations Can Improve Large Language Models in Drug Discovery 

**Title (ZH)**: 幻觉可以提高药物发现中的大型语言模型性能 

**Authors**: Shuzhou Yuan, Michael Färber  

**Link**: [PDF](https://arxiv.org/pdf/2501.13824)  

**Abstract**: Concerns about hallucinations in Large Language Models (LLMs) have been raised by researchers, yet their potential in areas where creativity is vital, such as drug discovery, merits exploration. In this paper, we come up with the hypothesis that hallucinations can improve LLMs in drug discovery. To verify this hypothesis, we use LLMs to describe the SMILES string of molecules in natural language and then incorporate these descriptions as part of the prompt to address specific tasks in drug discovery. Evaluated on seven LLMs and five classification tasks, our findings confirm the hypothesis: LLMs can achieve better performance with text containing hallucinations. Notably, Llama-3.1-8B achieves an 18.35% gain in ROC-AUC compared to the baseline without hallucination. Furthermore, hallucinations generated by GPT-4o provide the most consistent improvements across models. Additionally, we conduct empirical analyses and a case study to investigate key factors affecting performance and the underlying reasons. Our research sheds light on the potential use of hallucinations for LLMs and offers new perspectives for future research leveraging LLMs in drug discovery. 

**Abstract (ZH)**: 研究人员对大型语言模型（LLMs）中的幻觉问题表示出了担忧，但这些模型在创造力至关重要的领域，如药物发现，仍具有潜在价值，值得进一步探索。本文中，我们提出了一个假设：幻觉能够提高LLMs在药物发现中的表现。为了验证这一假设，我们使用LLMs将分子的SMILES字符串用自然语言描述，并将这些描述作为指令的一部分应用于药物发现中的特定任务。我们的研究在七个LLMs和五个分类任务上进行评估，结果显示这一假设得到了验证：相比不含幻觉的基线模型，包含幻觉的文本可以使LLMs实现更好的性能。具体而言，Llama-3.1-8B在ROC-AUC上取得了18.35%的增益。此外，GPT-4o生成的幻觉提供了对多个模型最一致的改进。我们还进行了实证分析和案例研究，以探讨影响性能的关键因素及其背后的原理。本研究为LLMs利用幻觉的潜在用途提供了新的视角，并为进一步利用LLMs进行药物发现的研究提供了新的思路。 

---
# Generation of reusable learning objects from digital medical collections: An analysis based on the MASMDOA framework 

**Title (ZH)**: 基于MASMDOA框架的数字化医学资源中可重用学习对象的生成分析 

**Authors**: Félix Buendía, Joaquín Gayoso-Cabada, José-Luis Sierra  

**Link**: [PDF](https://arxiv.org/pdf/2501.13806)  

**Abstract**: Learning Objects represent a widespread approach to structuring instructional materials in a large variety of educational contexts. The main aim of this work consists of analyzing from a qualitative point of view the process of generating reusable learning objects (RLOs) followed by Clavy, a tool that can be used to retrieve data from multiple medical knowledge sources and reconfigure such sources in diverse multimedia-based structures and organizations. From these organizations, Clavy is able to generate learning objects which can be adapted to various instructional healthcare scenarios with several types of user profiles and distinct learning requirements. Moreover, Clavy provides the capability of exporting these learning objects through educational standard specifications, which improves their reusability features. The analysis insights highlight the importance of having a tool able to transfer knowledge from the available digital medical collections to learning objects that can be easily accessed by medical students and healthcare practitioners through the most popular e-learning platforms. 

**Abstract (ZH)**: 学习对象是一种广泛应用于各种教育情境下结构化教学材料的方法。本文的主要目的是从定性的角度分析Clavy工具生成可重用学习对象（RLOs）的过程。Clavy是一种可以从多种医学知识源中检索数据并重新配置这些源至多种多媒体结构和组织的工具。从这些组织中，Clavy能够生成可以适应各类医学教育场景的学习对象，并针对不同用户类型和学习需求进行调整。此外，Clavy还提供将这些学习对象导出至教育标准规范的能力，从而提高其可重用性。分析结果强调了开发一种能够将现有数字医学资源中的知识转换为易于医学学生和医疗保健从业者通过主流在线学习平台访问的学习对象工具的重要性。 

---
# Parameter-Efficient Fine-Tuning for Foundation Models 

**Title (ZH)**: 基础模型的参数高效微调 

**Authors**: Dan Zhang, Tao Feng, Lilong Xue, Yuandong Wang, Yuxiao Dong, Jie Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13787)  

**Abstract**: This survey delves into the realm of Parameter-Efficient Fine-Tuning (PEFT) within the context of Foundation Models (FMs). PEFT, a cost-effective fine-tuning technique, minimizes parameters and computational complexity while striving for optimal downstream task performance. FMs, like ChatGPT, DALL-E, and LLaVA specialize in language understanding, generative tasks, and multimodal tasks, trained on diverse datasets spanning text, images, and videos. The diversity of FMs guides various adaptation strategies for PEFT. Therefore, this survey aims to provide a comprehensive overview of PEFT techniques applied to diverse FMs and address critical gaps in understanding the techniques, trends, and applications. We start by providing a detailed development of FMs and PEFT. Subsequently, we systematically review the key categories and core mechanisms of PEFT across diverse FMs to offer a comprehensive understanding of trends. We also explore the most recent applications across various FMs to demonstrate the versatility of PEFT, shedding light on the integration of systematic PEFT methods with a range of FMs. Furthermore, we identify potential research and development directions for improving PEFTs in the future. This survey provides a valuable resource for both newcomers and experts seeking to understand and use the power of PEFT across FMs. All reviewed papers are listed at \url{this https URL}. 

**Abstract (ZH)**: 本文综述了基础模型（Foundation Models, FMs）背景下参数高效微调（Parameter-Efficient Fine-Tuning, PEFT）的研究领域。PEFT 是一种成本效益高的微调技术，在减少参数量和计算复杂度的同时，力求获得最佳下游任务性能。FMs，例如 ChatGPT、DALL-E 和 LLaVA，专注于语言理解、生成任务和多模态任务，并在各种数据集上进行训练，涵盖文本、图像和视频等多种数据类型。FMs 的多样性为 PEFT 提供了不同的适应策略。因此，本文综述旨在提供 PEFT 技术在多种 FMs 上应用的全面概述，并解决理解技术、趋势和应用方面的关键空白。首先，我们详细介绍了 FMs 和 PEFT 的发展。随后，我们系统地回顾了 PEFT 在不同 FMs 中的关键类别和核心机制，以提供对其趋势的全面理解。此外，我们探讨了 PEFT 在各种 FMs 中的最新应用，展示了 PEFT 的多功能性，并探讨了如何将系统化的 PEFT 方法与多种 FMs 整合。最后，我们指出了提高 PEFT 的未来研究和开发方向。本文综述为希望理解和应用 PEFT 在 FMs 中的新手和专家提供了一项有价值的资源。所有审查的论文均可在 \url{this https URL} 中找到。 

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
# 2-Tier SimCSE: Elevating BERT for Robust Sentence Embeddings 

**Title (ZH)**: 两层级 SimCSE：提高 BERT 以获得稳健的句子嵌入 

**Authors**: Yumeng Wang, Ziran Zhou, Junjin Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13758)  

**Abstract**: Effective sentence embeddings that capture semantic nuances and generalize well across diverse contexts are crucial for natural language processing tasks. We address this challenge by applying SimCSE (Simple Contrastive Learning of Sentence Embeddings) using contrastive learning to fine-tune the minBERT model for sentiment analysis, semantic textual similarity (STS), and paraphrase detection. Our contributions include experimenting with three different dropout techniques, namely standard dropout, curriculum dropout, and adaptive dropout, to tackle overfitting, proposing a novel 2-Tier SimCSE Fine-tuning Model that combines both unsupervised and supervised SimCSE on STS task, and exploring transfer learning potential for Paraphrase and SST tasks. Our findings demonstrate the effectiveness of SimCSE, with the 2-Tier model achieving superior performance on the STS task, with an average test score of 0.742 across all three downstream tasks. The results of error analysis reveals challenges in handling complex sentiments and reliance on lexical overlap for paraphrase detection, highlighting areas for future research. The ablation study revealed that removing Adaptive Dropout in the Single-Task Unsupervised SimCSE Model led to improved performance on the STS task, indicating overfitting due to added parameters. Transfer learning from SimCSE models on Paraphrase and SST tasks did not enhance performance, suggesting limited transferability of knowledge from the STS task. 

**Abstract (ZH)**: 有效的句子嵌入能够捕捉语义细微差别并在多种场景下泛化，对于自然语言处理任务至关重要。针对这一挑战，我们采用对比学习的方法，通过SimCSE（简单句嵌入对比学习）对minBERT模型进行微调，应用于情感分析、语义文本相似度（STS）和同义句检测任务。我们的贡献包括：尝试了三种不同的dropout技术，即标准dropout、逐级dropout和自适应dropout，以解决过拟合问题；提出了一种新的双层SimCSE微调模型，该模型结合了STS任务上的无监督和监督SimCSE，探索了SimCSE模型在同义句和SST任务上的迁移学习潜力。实验结果表明，双层模型在STS任务上的性能最为出色，三项下游任务的平均测试得分为0.742。错误分析揭示了处理复杂情感的挑战以及同义句检测中对词汇重叠的依赖，这指出了未来研究的方向。削除单任务无监督SimCSE模型中的自适应dropout后，模型在STS任务上的性能有所提升，表明多余参数导致了过拟合。从SimCSE模型中进行的迁移学习在同义句和SST任务上并未提高性能，暗示STS任务的知识转移有限。 

---
# A Study of the Plausibility of Attention between RNN Encoders in Natural Language Inference 

**Title (ZH)**: 自然语言推理中RNN编码器之间注意力机制可行性研究 

**Authors**: Duc Hau Nguyen, Duc Hau Nguyen, Pascale Sébillot  

**Link**: [PDF](https://arxiv.org/pdf/2501.13735)  

**Abstract**: Attention maps in neural models for NLP are appealing to explain the decision made by a model, hopefully emphasizing words that justify the decision. While many empirical studies hint that attention maps can provide such justification from the analysis of sound examples, only a few assess the plausibility of explanations based on attention maps, i.e., the usefulness of attention maps for humans to understand the decision. These studies furthermore focus on text classification. In this paper, we report on a preliminary assessment of attention maps in a sentence comparison task, namely natural language inference. We compare the cross-attention weights between two RNN encoders with human-based and heuristic-based annotations on the eSNLI corpus. We show that the heuristic reasonably correlates with human annotations and can thus facilitate evaluation of plausible explanations in sentence comparison tasks. Raw attention weights however remain only loosely related to a plausible explanation. 

**Abstract (ZH)**: 神经模型中用于自然语言处理的注意力图在解释模型决策方面具有吸引力，希望能够突出那些支持决策的词语。尽管许多实证研究表明，从良好示例的分析中，注意力图可以提供这样的解释，但仅少有研究评估基于注意力图的解释的合理性，即注意力图对于人类理解决策的实际用处。此外，大多数研究集中在文本分类任务上。在本文中，我们对注意力图在句子对比任务，即自然语言推理（Natural Language Inference, NLI）中的作用进行了初步评估。我们比较了两个递归神经网络（RNN）编码器之间的交叉注意力权重，并使用eSNLI语料库中的人类标注和启发式标注作为对照。我们发现，启发式标注与人类标注有合理的相关性，从而可以促进在句子对比任务中评估合理的解释。然而，原始注意力权重与合理的解释之间仅有松散的相关性。 

---
# Pseudocode-Injection Magic: Enabling LLMs to Tackle Graph Computational Tasks 

**Title (ZH)**: 伪代码注入魔法：使大语言模型能够应对图计算任务 

**Authors**: Chang Gong, Wanrui Bian, Zhijie Zhang, Weiguo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2501.13731)  

**Abstract**: Graph computational tasks are inherently challenging and often demand the development of advanced algorithms for effective solutions. With the emergence of large language models (LLMs), researchers have begun investigating their potential to address these tasks. However, existing approaches are constrained by LLMs' limited capability to comprehend complex graph structures and their high inference costs, rendering them impractical for handling large-scale graphs. Inspired by human approaches to graph problems, we introduce a novel framework, PIE (Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks), which consists of three key steps: problem understanding, prompt design, and code generation. In this framework, LLMs are tasked with understanding the problem and extracting relevant information to generate correct code. The responsibility for analyzing the graph structure and executing the code is delegated to the interpreter. We inject task-related pseudocodes into the prompts to further assist the LLMs in generating efficient code. We also employ cost-effective trial-and-error techniques to ensure that the LLM-generated code executes correctly. Unlike other methods that require invoking LLMs for each individual test case, PIE only calls the LLM during the code generation phase, allowing the generated code to be reused and significantly reducing inference costs. Extensive experiments demonstrate that PIE outperforms existing baselines in terms of both accuracy and computational efficiency. 

**Abstract (ZH)**: 图计算任务本质上是具有挑战性的，通常需要开发高级算法以实现有效的解决方案。随着大型语言模型（LLMs）的出现，研究人员已经开始探索其在解决这些任务方面的潜力。然而，现有的方法受限于LLMs对复杂图结构理解能力的局限性和高昂的推理成本，这使得它们在处理大规模图时变得不切实际。受人类解决图问题方法的启发，我们提出了一种新颖的框架，即PIE（Pseudocode-Injection-Enhanced LLM Reasoning for Graph Computational Tasks），该框架包含三个关键步骤：问题理解、提示设计和代码生成。在该框架中，LLMs的任务是理解问题并提取相关信息以生成正确的代码。图结构的分析和代码执行的责任被委托给解释器。我们向提示中注入与任务相关的伪代码，以进一步帮助LLMs生成高效代码。我们还采用低成本的试错技术来确保生成的代码能够正确执行。与需要为每个独立测试用例调用LLM的方法不同，PIE仅在其代码生成阶段调用LLM，从而使生成的代码可以复用，并显著降低了推理成本。大量的实验表明，PIE在准确性和计算效率方面都优于现有基线方法。 

---
# RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation 

**Title (ZH)**: RPO：鲁棒检索增强生成中的检索偏好优化 

**Authors**: Shi-Qi Yan, Zhen-Hua Ling  

**Link**: [PDF](https://arxiv.org/pdf/2501.13726)  

**Abstract**: While Retrieval-Augmented Generation (RAG) has exhibited promise in utilizing external knowledge, its generation process heavily depends on the quality and accuracy of the retrieved context. Large language models (LLMs) struggle to evaluate the correctness of non-parametric knowledge retrieved externally when it differs from internal memorization, leading to knowledge conflicts during response generation. To this end, we introduce the Retrieval Preference Optimization (RPO), a lightweight and effective alignment method to adaptively leverage multi-source knowledge based on retrieval relevance. An implicit representation of retrieval relevance is derived and incorporated into the reward model to integrate retrieval evaluation and response generation into a single model, solving the problem that previous methods necessitate the additional procedure to assess the retrieval quality. Notably, RPO is the only RAG-dedicated alignment approach that quantifies the awareness of retrieval relevance in training, overcoming mathematical obstacles. Experiments on four datasets demonstrate that RPO outperforms RAG by 4-10% in accuracy without any extra component, exhibiting its robust generalization. 

**Abstract (ZH)**: 尽管检索增强生成（RAG）展示了利用外部知识的潜力，其生成过程高度依赖于检索上下文的质量和准确性。大型语言模型（LLMs）在评估与内部记忆不同的外部非参数化知识的正确性时存在困难，这导致在响应生成过程中出现知识冲突。为此，我们提出了检索偏好优化（RPO），这是一种轻量级且有效的对齐方法，可以根据检索相关性适当地利用多源知识。通过推导检索相关性的隐式表示并将其融入奖励模型中，将检索评估与响应生成整合到单一模型中，解决了先前方法需要额外步骤评估检索质量的问题。值得注意的是，RPO 是唯一一种在训练中量化检索相关性意识的 RAG 专用对齐方法，克服了数学障碍。在四个数据集上的实验表明，RPO 在无需任何额外组件的情况下比 RAG 在准确性上提高了 4%-10%，展示了其稳健的泛化能力。 

---
# Musical ethnocentrism in Large Language Models 

**Title (ZH)**: 大型语言模型中的音乐民族中心主义 

**Authors**: Anna Kruspe  

**Link**: [PDF](https://arxiv.org/pdf/2501.13720)  

**Abstract**: Large Language Models (LLMs) reflect the biases in their training data and, by extension, those of the people who created this training data. Detecting, analyzing, and mitigating such biases is becoming a focus of research. One type of bias that has been understudied so far are geocultural biases. Those can be caused by an imbalance in the representation of different geographic regions and cultures in the training data, but also by value judgments contained therein. In this paper, we make a first step towards analyzing musical biases in LLMs, particularly ChatGPT and Mixtral. We conduct two experiments. In the first, we prompt LLMs to provide lists of the "Top 100" musical contributors of various categories and analyze their countries of origin. In the second experiment, we ask the LLMs to numerically rate various aspects of the musical cultures of different countries. Our results indicate a strong preference of the LLMs for Western music cultures in both experiments. 

**Abstract (ZH)**: 大型语言模型（LLMs）在其训练数据中反映了偏差，并且这些偏差延伸到创建这些训练数据的人们。检测、分析和减轻这种偏差已成为研究的重点。到目前为止，一种类型的偏差（即地缘文化偏差）研究还相对较少。这些偏差可能是由于不同地理区域和文化在训练数据中的代表性不平衡造成的，也可能是由于其中包含的价值判断。在本文中，我们朝着分析LLMs中的音乐偏差迈出第一步，特别是针对ChatGPT和Mistral。我们进行了两项实验。在第一项实验中，我们促使LLMs提供各种类别的“前100名”音乐贡献者的名单，并分析他们的国籍。在第二项实验中，我们要求LLMs对不同国家的音乐文化的各种方面进行数值评分。我们的结果显示，在两项实验中，LLMs对西方音乐文化有强烈的偏好。 

---
# DI-BENCH: Benchmarking Large Language Models on Dependency Inference with Testable Repositories at Scale 

**Title (ZH)**: DI-BENCH：基于可测试存储库的大规模依赖推理大型语言模型基准测试 

**Authors**: Linghao Zhang, Junhao Wang, Shilin He, Chaoyun Zhang, Yu Kang, Bowen Li, Jiaheng Wen, Chengxing Xie, Maoquan Wang, Yufan Huang, Elsie Nallipogu, Qingwei Lin, Yingnong Dang, Saravan Rajmohan, Dongmei Zhang, Qi Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13699)  

**Abstract**: Large Language Models have advanced automated software development, however, it remains a challenge to correctly infer dependencies, namely, identifying the internal components and external packages required for a repository to successfully run. Existing studies highlight that dependency-related issues cause over 40\% of observed runtime errors on the generated repository. To address this, we introduce DI-BENCH, a large-scale benchmark and evaluation framework specifically designed to assess LLMs' capability on dependency inference. The benchmark features 581 repositories with testing environments across Python, C#, Rust, and JavaScript. Extensive experiments with textual and execution-based metrics reveal that the current best-performing model achieves only a 42.9% execution pass rate, indicating significant room for improvement. DI-BENCH establishes a new viewpoint for evaluating LLM performance on repositories, paving the way for more robust end-to-end software synthesis. 

**Abstract (ZH)**: 大型语言模型在自动化软件开发中取得了显著进展，然而正确推断依赖关系仍是一个挑战，具体来说，是识别一个仓库中所需运行的所有内部组件和外部包。现有研究指出，依赖相关问题导致生成的仓库中超过40%的运行时错误。为解决这一问题，我们引入了DI-BENCH，这是一个大规模的基准测试和评估框架，专门用于评估LLM在依赖推断方面的能力。该基准测试包括581个跨Python、C#、Rust和JavaScript的测试环境的仓库。通过广泛使用文本和执行指标的实验表明，当前性能最佳的模型仅实现了42.9%的执行通过率，这表明有巨大的改进空间。DI-BENCH 为评估LLM在仓库上的性能提供了一个新的视角，为更稳健的端到端软件合成铺平了道路。 

---
# Question Answering on Patient Medical Records with Private Fine-Tuned LLMs 

**Title (ZH)**: 使用私有微调大型语言模型进行患者医疗记录的问答 

**Authors**: Sara Kothari, Ayush Gupta  

**Link**: [PDF](https://arxiv.org/pdf/2501.13687)  

**Abstract**: Healthcare systems continuously generate vast amounts of electronic health records (EHRs), commonly stored in the Fast Healthcare Interoperability Resources (FHIR) standard. Despite the wealth of information in these records, their complexity and volume make it difficult for users to retrieve and interpret crucial health insights. Recent advances in Large Language Models (LLMs) offer a solution, enabling semantic question answering (QA) over medical data, allowing users to interact with their health records more effectively. However, ensuring privacy and compliance requires edge and private deployments of LLMs.
This paper proposes a novel approach to semantic QA over EHRs by first identifying the most relevant FHIR resources for a user query (Task1) and subsequently answering the query based on these resources (Task2). We explore the performance of privately hosted, fine-tuned LLMs, evaluating them against benchmark models such as GPT-4 and GPT-4o. Our results demonstrate that fine-tuned LLMs, while 250x smaller in size, outperform GPT-4 family models by 0.55% in F1 score on Task1 and 42% on Meteor Task in Task2. Additionally, we examine advanced aspects of LLM usage, including sequential fine-tuning, model self-evaluation (narcissistic evaluation), and the impact of training data size on performance. The models and datasets are available here: this https URL 

**Abstract (ZH)**: 医疗系统持续生成大量电子健康记录（EHRs），这些记录通常存储在Fast Healthcare Interoperability Resources（FHIR）标准中。尽管这些记录中包含丰富信息，但由于其复杂性和大量的数据，用户很难检索和解释关键的健康洞察。近年来，大规模语言模型（LLMs）的发展提供了解决方案，使用户能够通过这些模型进行语义问题回答（QA），从而更有效地与健康记录互动。然而，确保隐私和合规性需要在边缘和私有环境中部署LLMs。

本文提出了一种新的方法，通过对用户查询相关性最高的FHIR资源进行识别（任务1），随后基于这些资源回答查询（任务2），以实现对EHRs的语义QA。我们研究了私有托管、微调后的LLMs的性能，并将其与基准模型如GPT-4和GPT-4o进行对比评估。结果显示，虽然微调后的LLMs比GPT-4模型小250倍，但在任务1（F1分数）上仍能比GPT-4系列模型高出0.55%，在任务2（Meteor任务）上高出42%。此外，我们还研究了LLM使用的高级方面，包括顺序微调、模型自我评估（自恋式评估）以及训练数据量对性能的影响。相关模型和数据集可在此处获取：this https URL 

---
# Collective Memory and Narrative Cohesion: A Computational Study of Palestinian Refugee Oral Histories in Lebanon 

**Title (ZH)**: 集体记忆与叙事凝聚力：黎巴嫩巴勒斯坦难民口述历史的计算研究 

**Authors**: Ghadeer Awwad, Lavinia Dunagan, David Gamba, Tamara N. Rayan  

**Link**: [PDF](https://arxiv.org/pdf/2501.13682)  

**Abstract**: This study uses the Palestinian Oral History Archive (POHA) to investigate how Palestinian refugee groups in Lebanon sustain a cohesive collective memory of the Nakba through shared narratives. Grounded in Halbwachs' theory of group memory, we employ statistical analysis of pairwise similarity of narratives, focusing on the influence of shared gender and location. We use textual representation and semantic embeddings of narratives to represent the interviews themselves. Our analysis demonstrates that shared origin is a powerful determinant of narrative similarity across thematic keywords, landmarks, and significant figures, as well as in semantic embeddings of the narratives. Meanwhile, shared residence fosters cohesion, with its impact significantly amplified when paired with shared origin. Additionally, women's narratives exhibit heightened thematic cohesion, particularly in recounting experiences of the British occupation, underscoring the gendered dimensions of memory formation. This research deepens the understanding of collective memory in diasporic settings, emphasizing the critical role of oral histories in safeguarding Palestinian identity and resisting erasure. 

**Abstract (ZH)**: 本研究利用巴勒斯坦口述历史档案（POHA）探究黎巴嫩巴勒斯坦难民群体如何通过共有的叙事维持挪巴卡（Nakba）的集体记忆。基于Halbwachs的群体记忆理论，我们通过对叙事相似性的统计分析，重点关注性别和地理位置的共同性对叙事的影响。我们使用文本表示和语义嵌入方法来表示访谈内容。分析结果显示，共同的原籍是叙事在主题关键词、地标和重要人物方面相似性的强大力量，同时在叙事的语义嵌入中也是如此。此外，共同居住增强了群体记忆的凝聚力，当与共同原籍相匹配时，这种影响尤为显著。同时，女性的叙事在回顾英国占领时期的经历时表现出高度的主题一致性，突显了记忆形成中的性别维度。这项研究深化了对流散社区中集体记忆的理解，强调了口头历史在保护巴勒斯坦身份和抵制遗忘方面的重要作用。 

---
# How to Complete Domain Tuning while Keeping General Ability in LLM: Adaptive Layer-wise and Element-wise Regularization 

**Title (ZH)**: 如何在保持泛化能力的同时完成领域微调：自适应分层和元素化正则化 

**Authors**: Shezheng Song, Hao Xu, Jun Ma, Shasha Li, Long Peng, Qian Wan, Xiaodong Liu, Jie Yu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13669)  

**Abstract**: Large Language Models (LLMs) exhibit strong general-purpose language capabilities. However, fine-tuning these models on domain-specific tasks often leads to catastrophic forgetting, where the model overwrites or loses essential knowledge acquired during pretraining. This phenomenon significantly limits the broader applicability of LLMs. To address this challenge, we propose a novel approach to compute the element-wise importance of model parameters crucial for preserving general knowledge during fine-tuning. Our method utilizes a dual-objective optimization strategy: (1) regularization loss to retain the parameter crucial for general knowledge; (2) cross-entropy loss to adapt to domain-specific tasks. Additionally, we introduce layer-wise coefficients to account for the varying contributions of different layers, dynamically balancing the dual-objective optimization. Extensive experiments on scientific, medical, and physical tasks using GPT-J and LLaMA-3 demonstrate that our approach mitigates catastrophic forgetting while enhancing model adaptability. Compared to previous methods, our solution is approximately 20 times faster and requires only 10%-15% of the storage, highlighting the practical efficiency. The code will be released. 

**Abstract (ZH)**: 大型语言模型（LLMs）展现出强大的通用语言能力。然而，在特定任务上的微调往往会导致灾难性的遗忘现象，即模型在微调过程中会覆盖或丢失预训练阶段获得的重要知识。这一现象极大地限制了LLMs的广泛应用。为了解决这一挑战，我们提出了一种新的方法，用于计算在微调过程中对保持通用知识至关重要的模型参数的元素级重要性。我们的方法采用双目标优化策略：（1）正则化损失，以保留对于通用知识至关重要的参数；（2）交叉熵损失，以适应特定任务。此外，我们引入了分层系数来 account for 不同层的差异性贡献，并动态平衡双目标优化。在使用GPT-J和LLaMA-3进行的涉及科学、医学和物理任务的广泛实验中，我们证明了我们的方法可以减轻灾难性的遗忘现象，同时增强模型的适应性。与之前的解决方案相比，我们的方法大约快20倍，并且只需要10%-15%的存储空间，这突显出其实用效率。我们将发布相应的代码。 

---
# LVPruning: An Effective yet Simple Language-Guided Vision Token Pruning Approach for Multi-modal Large Language Models 

**Title (ZH)**: LVPruning：一种有效且简单的基于语言指导的视觉Token剪枝方法，用于多模态大规模语言模型 

**Authors**: Yizheng Sun, Yanze Xin, Hao Li, Jingyuan Sun, Chenghua Lin, Riza Batista-Navarro  

**Link**: [PDF](https://arxiv.org/pdf/2501.13652)  

**Abstract**: Multi-modal Large Language Models (MLLMs) have achieved remarkable success by integrating visual and textual modalities. However, they incur significant computational overhead due to the large number of vision tokens processed, limiting their practicality in resource-constrained environments. We introduce Language-Guided Vision Token Pruning (LVPruning) for MLLMs, an effective yet simple method that significantly reduces the computational burden while preserving model performance. LVPruning employs cross-attention modules to compute the importance of vision tokens based on their interaction with language tokens, determining which to prune. Importantly, LVPruning can be integrated without modifying the original MLLM parameters, which makes LVPruning simple to apply or remove. Our experiments show that LVPruning can effectively reduce up to 90% of vision tokens by the middle layer of LLaVA-1.5, resulting in a 62.1% decrease in inference Tera Floating-Point Operations Per Second (TFLOPs), with an average performance loss of just 0.45% across nine multi-modal benchmarks. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）通过整合视觉和文本模态取得了显著的成功。然而，由于需要处理大量的视觉标记，它们产生了显著的计算开销，限制了在资源受限环境中的实用性。我们提出了一种名为语言引导的视觉标记剪枝（LVPruning）的方法，这是一种有效且简单的策略，能够在大幅减少计算负担的同时保持模型性能。LVPruning 利用交叉注意力模块根据视觉标记与语言标记之间的交互计算视觉标记的重要性，从而决定要剪枝哪些标记。重要的是，LVPruning 可以在不修改原始 MLLM 参数的情况下进行集成，这使得 LVPruning 简单易行。我们的实验表明，LVPruning 可以有效减少 LLaVA-1.5 中间层最多 90% 的视觉标记，导致推理吞吐量（TFLOPs）降低 62.1%，同时在九个多模态基准测试中的平均性能损失仅为 0.45%。 

---
# Sigma: Differential Rescaling of Query, Key and Value for Efficient Language Models 

**Title (ZH)**: Sigma：查询、键和值的差异性缩放以提高高效语言模型性能 

**Authors**: Zhenghao Lin, Zihao Tang, Xiao Liu, Yeyun Gong, Yi Cheng, Qi Chen, Hang Li, Ying Xin, Ziyue Yang, Kailai Yang, Yu Yan, Xiao Liang, Shuai Lu, Yiming Huang, Zheheng Luo, Lei Qu, Xuan Feng, Yaoxiang Wang, Yuqing Xia, Feiyang Chen, Yuting Jiang, Yasen Hu, Hao Ni, Binyang Li, Guoshuai Zhao, Jui-Hao Chiang, Zhongxin Guo, Chen Lin, Kun Kuang, Wenjie Li, Yelong Shen, Jian Jiao, Peng Cheng, Mao Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13629)  

**Abstract**: We introduce Sigma, an efficient large language model specialized for the system domain, empowered by a novel architecture including DiffQKV attention, and pre-trained on our meticulously collected system domain data. DiffQKV attention significantly enhances the inference efficiency of Sigma by optimizing the Query (Q), Key (K), and Value (V) components in the attention mechanism differentially, based on their varying impacts on the model performance and efficiency indicators. Specifically, we (1) conduct extensive experiments that demonstrate the model's varying sensitivity to the compression of K and V components, leading to the development of differentially compressed KV, and (2) propose augmented Q to expand the Q head dimension, which enhances the model's representation capacity with minimal impacts on the inference speed. Rigorous theoretical and empirical analyses reveal that DiffQKV attention significantly enhances efficiency, achieving up to a 33.36% improvement in inference speed over the conventional grouped-query attention (GQA) in long-context scenarios. We pre-train Sigma on 6T tokens from various sources, including 19.5B system domain data that we carefully collect and 1T tokens of synthesized and rewritten data. In general domains, Sigma achieves comparable performance to other state-of-arts models. In the system domain, we introduce the first comprehensive benchmark AIMicius, where Sigma demonstrates remarkable performance across all tasks, significantly outperforming GPT-4 with an absolute improvement up to 52.5%. 

**Abstract (ZH)**: 我们介绍了Sigma，这是专为系统领域设计的一种高效的大语言模型，它基于一种新颖的架构——DiffQKV注意力机制，并且是在我们精心收集的系统领域数据上进行预训练的。DiffQKV注意力机制通过根据不同组件（查询Q、键K和值V）对模型性能和效率指标的不同影响，分别优化这些组件来显著提高推理效率。具体来说，我们（1）进行了广泛的实验，证明了模型对键K和值V组件压缩的敏感性不同，从而开发出了不同压缩级别的KV；（2）提出了增强后的查询Q，通过扩大Q头的维度来增强模型的表示能力，同时不影响推理速度。严谨的理论和实证分析表明，DiffQKV注意力机制显著提高了效率，在长上下文场景下，相比传统的分组查询注意力机制（GQA），推理速度提升了高达33.36%。我们在Sigma上进行了6T字节的预训练，来自多个来源的数据包括1950亿个系统领域数据点和1000亿个合成和重写的数据点。在一般领域中，Sigma的表现可与当前最先进的模型相媲美。在系统领域中，我们引入了首个全面基准测试AIMicius，在所有任务中，Sigma表现出色，显著优于GPT-4，绝对性能提升高达52.5%。 

---
# Domain-Specific Machine Translation to Translate Medicine Brochures in English to Sorani Kurdish 

**Title (ZH)**: 将医学宣传册从英语翻译成索里语库尔德语的专业领域机器翻译 

**Authors**: Mariam Shamal, Hossein Hassani  

**Link**: [PDF](https://arxiv.org/pdf/2501.13609)  

**Abstract**: Access to Kurdish medicine brochures is limited, depriving Kurdish-speaking communities of critical health information. To address this problem, we developed a specialized Machine Translation (MT) model to translate English medicine brochures into Sorani Kurdish using a parallel corpus of 22,940 aligned sentence pairs from 319 brochures, sourced from two pharmaceutical companies in the Kurdistan Region of Iraq (KRI). We trained a Statistical Machine Translation (SMT) model using the Moses toolkit, conducting seven experiments that resulted in BLEU scores ranging from 22.65 to 48.93. We translated three new brochures to improve the evaluation process and encountered unknown words. We addressed unknown words through post-processing with a medical dictionary, resulting in BLEU scores of 56.87, 31.05, and 40.01. Human evaluation by native Kurdish-speaking pharmacists, physicians, and medicine users showed that 50% of professionals found the translations consistent, while 83.3% rated them accurate. Among users, 66.7% considered the translations clear and felt confident using the medications. 

**Abstract (ZH)**: 库尔德语地区获得医学手册的渠道有限，剥夺了库尔德语社区重要的健康信息。为解决这一问题，我们开发了一个专门的机器翻译（MT）模型，将英语医学手册翻译成索莫鲁库尔德语（Sorani Kurdish），利用来自伊拉克库尔德地区（KRI）两家制药公司的22,940个对齐句子对的平行语料库，共计319份手册。我们使用Moses工具集训练了一个统计机器翻译（SMT）模型，并进行了七次实验，BLEU分数范围从22.65到48.93不等。为了改进评估过程，我们翻译了三份新手册，遇到了一些未知词。通过使用医学词典进行后处理，最终BLEU分数分别为56.87、31.05和40.01。由库尔德语母语药剂师、医师和患者进行的人类评估显示，50%的专业人士认为翻译连贯，83.3%的受访者认为翻译准确。在用户中，66.7%的人认为翻译清晰，并且有信心使用这些药物。 

---
# Improving Contextual Faithfulness of Large Language Models via Retrieval Heads-Induced Optimization 

**Title (ZH)**: 通过检索头部引导优化提高大型语言模型的语境忠实度 

**Authors**: Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yangfan Ye, Weihong Zhong, Yuxuan Gu, Baoxin Wang, Dayong Wu, Guoping Hu, Bing Qin  

**Link**: [PDF](https://arxiv.org/pdf/2501.13573)  

**Abstract**: Ensuring contextual faithfulness in retrieval-augmented large language models (LLMs) is crucial for building trustworthy information-seeking systems, particularly in long-form question-answering (LFQA) scenarios. In this work, we identify a salient correlation between LFQA faithfulness and retrieval heads, a set of attention heads responsible for retrieving contextual information. Leveraging this insight, we propose RHIO, a framework designed to teach LLMs to explicitly discriminate between faithful and unfaithful generations. RHIO first augments unfaithful samples that simulate realistic model-intrinsic errors by selectively masking retrieval heads. Then, these samples are incorporated into joint training, enabling the model to distinguish unfaithful outputs from faithful ones conditioned on control tokens. Furthermore, these control tokens are leveraged to self-induce contrastive outputs, amplifying their difference through contrastive decoding. Additionally, to facilitate the evaluation of contextual faithfulness, we also introduce GroundBench, a comprehensive benchmark compiled from five existing LFQA datasets. Extensive experimental results on GroundBench demonstrate that RHIO significantly improves faithfulness, even outperforming GPT-4o. 

**Abstract (ZH)**: 在检索增强的大语言模型（LLMs）中确保上下文一致性忠实性对于构建可信赖的信息检索系统至关重要，特别是在长文本问答（LFQA）场景中。在本研究中，我们发现了LFQA忠实性与检索头部之间的显著关联，检索头部是一系列负责检索上下文信息的注意力头部。基于这一洞察，我们提出了RHIO框架，旨在教导LLMs明确区分忠实生成和不忠实生成。RHIO首先通过选择性屏蔽检索头部来增强不忠实样例，模拟模型固有的错误，然后将这些样例纳入联合训练，从而让模型在控制令牌条件下区分不忠实输出和忠实输出。此外，这些控制令牌还被利用来自我引导对比性输出，通过对比解码放大其差异。此外，为了方便评估上下文忠实性，我们还引入了GroundBench基准，该基准从五个现有的LFQA数据集中综合而成。在GroundBench上的广泛实验结果表明，RHIO显著提高了忠实性，甚至优于GPT-4o。 

---
# K-COMP: Retrieval-Augmented Medical Domain Question Answering With Knowledge-Injected Compressor 

**Title (ZH)**: K-COMP: 嵌入知识的压缩器增强医疗领域检索辅助问答 

**Authors**: Jeonghun Cho, Gary Geunbae Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.13567)  

**Abstract**: Retrieval-augmented question answering (QA) integrates external information, and thereby increases the QA accuracy of reader models that lack domain knowledge. However, documents retrieved for closed domains require high expertise, so the reader model may have difficulty fully comprehending the text. Moreover, the retrieved documents contain thousands of tokens, some unrelated to the question. As a result, the documents include some inaccurate information, which could lead the reader model to mistrust the passages and could result in hallucinations. To solve these problems, we propose K-COMP (Knowledge-injected compressor) which provides the knowledge required to answer correctly. The compressor automatically generates the requisite prior knowledge to facilitate the answering process prior to the compression of retrieved passages. Subsequently, the passages are compressed autoregressively, with the generated knowledge being integrated into the compression process. This process ensures alignment between the question intent and the compressed context. By augmenting this prior knowledge and concise context, the reader models are guided toward relevant answers and trust the context. 

**Abstract (ZH)**: 检索增强的问答（QA）将外部信息整合进来，从而增加缺乏领域知识的阅读器模型的问答准确性。然而，对于闭合领域检索到的文档要求较高的专业知识，因此阅读器模型可能难以完全理解文本。此外，检索到的文档包含数千个词元，其中一些与问题无关。结果，文档中包含一些不准确的信息，这可能导致阅读器模型对段落产生不信任，并可能引发幻觉。为了解决这些问题，我们提出了K-COMP（知识注入压缩器），它提供了正确回答所需的知识。压缩器会自动生成必要的先验知识，以在压缩检索到的段落之前促进回答过程。随后，段落通过自回归的方式被压缩，生成的知识被整合到压缩过程中。这一过程确保了问题意图与压缩上下文之间的对齐。通过增强这种先验知识和简洁的上下文，阅读器模型被引导向相关答案，并对上下文产生信任。 

---
# LLMs Can Plan Only If We Tell Them 

**Title (ZH)**: LLMs 只有在我们告诉它们的情况下才能进行规划 

**Authors**: Bilgehan Sel, Ruoxi Jia, Ming Jin  

**Link**: [PDF](https://arxiv.org/pdf/2501.13545)  

**Abstract**: Large language models (LLMs) have demonstrated significant capabilities in natural language processing and reasoning, yet their effectiveness in autonomous planning has been under debate. While existing studies have utilized LLMs with external feedback mechanisms or in controlled environments for planning, these approaches often involve substantial computational and development resources due to the requirement for careful design and iterative backprompting. Moreover, even the most advanced LLMs like GPT-4 struggle to match human performance on standard planning benchmarks, such as the Blocksworld, without additional support. This paper investigates whether LLMs can independently generate long-horizon plans that rival human baselines. Our novel enhancements to Algorithm-of-Thoughts (AoT), which we dub AoT+, help achieve state-of-the-art results in planning benchmarks out-competing prior methods and human baselines all autonomously. 

**Abstract (ZH)**: 大型语言模型（LLMs）已经在自然语言处理和推理方面展现出了显著的能力，但在自主规划方面的有效性一直存在争议。虽然现有的研究利用了具备外部反馈机制或在受控环境中运行的LLMs进行规划，但这些方法通常需要大量的计算和开发资源，因为这要求仔细的设计和迭代的反向提示。此外，即使是最先进的LLMs，如GPT-4，在标准规划基准测试（如Blocksworld）上也难以达到人类的性能水平，除非得到额外的支持。本文探讨了LLMs是否能够独立生成能够与人类基准相媲美的长期规划。我们对思维算法（AoT）的创新改进，称之为AoT+，帮助我们在规划基准测试中取得了领先的结果，优于先前的方法和人类基准，完全实现了自主规划。 

---
# RECALL: Library-Like Behavior In Language Models is Enhanced by Self-Referencing Causal Cycles 

**Title (ZH)**: RECALL：通过自参照因果循环增强的语言模型中的图书馆式行为 

**Authors**: Munachiso Nwadike, Zangir Iklassov, Toluwani Aremu, Tatsuya Hiraoka, Velibor Bojkovic, Benjamin Heinzerling, Hilal Alqaubeh, Martin Takáč, Kentaro Inui  

**Link**: [PDF](https://arxiv.org/pdf/2501.13491)  

**Abstract**: We introduce the concept of the self-referencing causal cycle (abbreviated RECALL) - a mechanism that enables large language models (LLMs) to bypass the limitations of unidirectional causality, which underlies a phenomenon known as the reversal curse. When an LLM is prompted with sequential data, it often fails to recall preceding context. For example, when we ask an LLM to recall the line preceding "O say does that star-spangled banner yet wave" in the U.S. National Anthem, it often fails to correctly return "Gave proof through the night that our flag was still there" - this is due to the reversal curse. It occurs because language models such as ChatGPT and Llama generate text based on preceding tokens, requiring facts to be learned and reproduced in a consistent token order. While the reversal curse is often viewed as a limitation, we offer evidence of an alternative view: it is not always an obstacle in practice. We find that RECALL is driven by what we designate as cycle tokens - sequences that connect different parts of the training data, enabling recall of preceding tokens from succeeding ones. Through rigorous probabilistic formalization and controlled experiments, we demonstrate how the cycles they induce influence a model's ability to reproduce information. To facilitate reproducibility, we provide our code and experimental details at this https URL. 

**Abstract (ZH)**: 我们引入了自参照因果循环（简称RECALL）的概念——一种机制，使得大型语言模型（LLMs）能够超越单一方向因果性的限制，这种限制会导致所谓的反转诅咒。当LLM接收到序列化数据时，常常无法回溯之前的背景信息。例如，当我们要求LLM回忆美国国歌中“O say does that star-spangled banner yet wave”这一行的前一行时，它通常无法准确返回“Gave proof through the night that our flag was still there”——这正是反转诅咒的结果。这种情况发生在语言模型如ChatGPT和Llama根据前一个标记生成文本时，需要事实按照一致的标记顺序被学习和重现。虽然反转诅咒通常被视为一种限制，但我们提供证据表明，它可以从另一种角度看作并非总是实践中的障碍。我们发现，RECALL是由我们称之为循环标记所驱动的——这些序列将训练数据的不同部分连接起来，从而使得从后续标记回溯到前面的标记成为可能。通过严格的概率形式化和控制实验，我们展示了这些循环如何影响模型再现信息的能力。为了方便复现，我们在以下链接提供我们的代码和实验细节：\[请根据实际情况填写链接\]。 

---
# Multi-Level Attention and Contrastive Learning for Enhanced Text Classification with an Optimized Transformer 

**Title (ZH)**: 优化 Transformer 的多层注意力和对比学习增强文本分类 

**Authors**: Jia Gao, Guiran Liu, Binrong Zhu, Shicheng Zhou, Hongye Zheng, Xiaoxuan Liao  

**Link**: [PDF](https://arxiv.org/pdf/2501.13467)  

**Abstract**: This paper studies a text classification algorithm based on an improved Transformer to improve the performance and efficiency of the model in text classification tasks. Aiming at the shortcomings of the traditional Transformer model in capturing deep semantic relationships and optimizing computational complexity, this paper introduces a multi-level attention mechanism and a contrastive learning strategy. The multi-level attention mechanism effectively models the global semantics and local features in the text by combining global attention with local attention; the contrastive learning strategy enhances the model's ability to distinguish between different categories by constructing positive and negative sample pairs while improving the classification effect. In addition, in order to improve the training and inference efficiency of the model on large-scale text data, this paper designs a lightweight module to optimize the feature transformation process and reduce the computational cost. Experimental results on the dataset show that the improved Transformer model outperforms the comparative models such as BiLSTM, CNN, standard Transformer, and BERT in terms of classification accuracy, F1 score, and recall rate, showing stronger semantic representation ability and generalization performance. The method proposed in this paper provides a new idea for algorithm optimization in the field of text classification and has good application potential and practical value. Future work will focus on studying the performance of this model in multi-category imbalanced datasets and cross-domain tasks and explore the integration wi 

**Abstract (ZH)**: 本文研究了一种基于改进Transformer的文本分类算法，以提高模型在文本分类任务中的性能和效率。针对传统Transformer模型在捕捉深层次语义关系和优化计算复杂度方面的不足，本文引入了多层注意力机制和对比学习策略。多层注意力机制通过结合全局注意力和局部注意力，有效地建模了文本中的全局语义和局部特征；对比学习策略通过构建正样本和负样本对，增强了模型在区分不同类别方面的能力，同时提高了分类效果。此外，为了提高模型在大规模文本数据上的训练和推理效率，本文设计了一个轻量级模块来优化特征转换过程并降低计算成本。实验结果表明，改进后的Transformer模型在分类准确率、F1分数和召回率方面优于BiLSTM、CNN、标准Transformer和BERT等基准模型，展示了更强的语义表示能力和泛化性能。本文提出的方法为文本分类领域的算法优化提供了新的思路，并具有良好的应用前景和实用价值。未来的工作将集中在研究该模型在多类别不平衡数据集和跨域任务中的性能，并探索其与其他方法的整合。 

---
# Softplus Attention with Re-weighting Boosts Length Extrapolation in Large Language Models 

**Title (ZH)**: 软\Response关键词*函数注意力与权重新加权增强大型语言模型中的长度外推能力 

**Authors**: Bo Gao, Michael W. Spratling  

**Link**: [PDF](https://arxiv.org/pdf/2501.13428)  

**Abstract**: Large language models have achieved remarkable success in recent years, primarily due to the implementation of self-attention mechanisms. However, traditional Softmax attention suffers from numerical instability and reduced performance as the length of inference tokens increases. This paper addresses these issues by decomposing the Softmax operation into a non-linear transformation and the $l_1$-norm. We identify the latter as essential for maintaining model performance. By replacing the non-linear transformation with the Softplus activation function and introducing a dynamic length scale factor for different token lengths based on invariance entropy, we create a novel attention mechanism with performance better than conventional Softmax attention across various inference lengths. To further improve the length extrapolation ability of the proposed attention mechanism, we introduce a re-weighting mechanism that amplifies significant attention weights while diminishing weaker ones, enabling the model to concentrate more effectively on relevant tokens. When combined with our proposed attention mechanism, this approach demonstrates significant promise in managing longer sequences, maintaining nearly constant validation loss even at 16$\times$ the training token length while ensuring numerical stability. Our code is available at: this https URL. 

**Abstract (ZH)**: 近年来，大规模语言模型取得了显著的成功，主要得益于自注意力机制的应用。然而，传统的Softmax注意力机制在推理序列长度增加时表现出数值不稳定性，并导致性能下降。本文通过将Softmax操作分解为非线性变换和$l_1$范数来解决这些问题，我们发现后者对于保持模型性能至关重要。通过用Softplus激活函数替换非线性变换，并根据不变熵引入不同序列长度的动态长度比例因子，我们提出了一种新的注意力机制，其在各种推理长度下的性能优于传统的Softmax注意力机制。为了进一步提高所提注意力机制的长度外推能力，我们引入了一种重新加权机制，以增强重要注意力权重并减弱较弱的权重，从而使模型能够更有效地集中于相关词元。当结合我们提出的新注意力机制时，该方法在处理较长序列时显示出巨大的潜力，即使在训练词元长度的16倍情况下，仍然能够保持近似不变的验证损失，并确保数值稳定性。我们的代码可在以下链接获取：this https URL。 

---
# A Survey of Code-switched Arabic NLP: Progress, Challenges, and Future Directions 

**Title (ZH)**: 代码-switching 阿拉伯语自然语言处理的研究综述：进展、挑战及未来方向 

**Authors**: Injy Hamed, Caroline Sabty, Slim Abdennadher, Ngoc Thang Vu, Thamar Solorio, Nizar Habash  

**Link**: [PDF](https://arxiv.org/pdf/2501.13419)  

**Abstract**: Language in the Arab world presents a complex diglossic and multilingual setting, involving the use of Modern Standard Arabic, various dialects and sub-dialects, as well as multiple European languages. This diverse linguistic landscape has given rise to code-switching, both within Arabic varieties and between Arabic and foreign languages. The widespread occurrence of code-switching across the region makes it vital to address these linguistic needs when developing language technologies. In this paper, we provide a review of the current literature in the field of code-switched Arabic NLP, offering a broad perspective on ongoing efforts, challenges, research gaps, and recommendations for future research directions. 

**Abstract (ZH)**: 阿拉伯世界的语言呈现一种复杂的二元多语现状，涉及现代标准阿拉伯语、各种方言及其亚方言，以及多种欧洲语言的使用。这种多样的语言景观导致了代码转换现象，既在阿拉伯语内部发生，又在阿拉伯语与外国语言之间发生。该地区代码转换的普遍现象使得在开发语言技术时必须解决这些语言需求至关重要。本文提供了一个关于代码转换阿拉伯自然语言处理的当前文献综述，从广泛的角度探讨了正在进行的努力、面临的挑战、研究缺口以及未来研究方向的建议。 

---
# ExLM: Rethinking the Impact of $\texttt{[MASK]}$ Tokens in Masked Language Models 

**Title (ZH)**: ExLM：重新思考掩码语言模型中$\texttt{[MASK]}$令牌的影响 

**Authors**: Kangjie Zheng, Junwei Yang, Siyue Liang, Bin Feng, Zequn Liu, Wei Ju, Zhiping Xiao, Ming Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13397)  

**Abstract**: Masked Language Models (MLMs) have achieved remarkable success in many self-supervised representation learning tasks. MLMs are trained by randomly replacing some tokens in the input sentences with $\texttt{[MASK]}$ tokens and predicting the original tokens based on the remaining context. This paper explores the impact of $\texttt{[MASK]}$ tokens on MLMs. Analytical studies show that masking tokens can introduce the corrupted semantics problem, wherein the corrupted context may convey multiple, ambiguous meanings. This problem is also a key factor affecting the performance of MLMs on downstream tasks. Based on these findings, we propose a novel enhanced-context MLM, ExLM. Our approach expands $\texttt{[MASK]}$ tokens in the input context and models the dependencies between these expanded states. This expansion increases context capacity and enables the model to capture richer semantic information, effectively mitigating the corrupted semantics problem during pre-training. Experimental results demonstrate that ExLM achieves significant performance improvements in both text modeling and SMILES modeling tasks. Further analysis confirms that ExLM enhances semantic representations through context enhancement, and effectively reduces the multimodality problem commonly observed in MLMs. 

**Abstract (ZH)**: 掩码语言模型（MLMs）在许多自监督表示学习任务中取得了显著的成功。MLMs的训练是通过随机替换输入句子中的某些标记为$\texttt{[MASK]}$标记，并基于剩余的上下文预测原始标记。本文探讨了$\texttt{[MASK]}$标记对MLMs的影响。分析研究表明，掩码标记可能引入损坏语义问题，即受损的上下文可能传达多重、模糊的意义。这个问题也是影响MLMs在下游任务性能的关键因素之一。基于上述发现，我们提出了一种新颖的增强上下文MLMs，即ExLM。我们的方法扩展了输入上下文中的$\texttt{[MASK]}$标记，并建模这些扩展状态之间的依赖关系。这种扩展增加了上下文容量，使模型能够捕捉到更丰富的语义信息，在预训练期间有效缓解了损坏的语义问题。实验结果表明，ExLM在文本建模和SMILES建模任务中均实现了显著的性能提升。进一步的分析证实，ExLM通过上下文增强提高了语义表示能力，并有效地减少了MLMs中常见的模态性问题。 

---
# Can Large Language Models Understand Preferences in Personalized Recommendation? 

**Title (ZH)**: 大型语言模型能否理解个性化推荐中的偏好？ 

**Authors**: Zhaoxuan Tan, Zinan Zeng, Qingkai Zeng, Zhenyu Wu, Zheyuan Liu, Fengran Mo, Meng Jiang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13391)  

**Abstract**: Large Language Models (LLMs) excel in various tasks, including personalized recommendations. Existing evaluation methods often focus on rating prediction, relying on regression errors between actual and predicted ratings. However, user rating bias and item quality, two influential factors behind rating scores, can obscure personal preferences in user-item pair data. To address this, we introduce PerRecBench, disassociating the evaluation from these two factors and assessing recommendation techniques on capturing the personal preferences in a grouped ranking manner. We find that the LLM-based recommendation techniques that are generally good at rating prediction fail to identify users' favored and disfavored items when the user rating bias and item quality are eliminated by grouping users. With PerRecBench and 19 LLMs, we find that while larger models generally outperform smaller ones, they still struggle with personalized recommendation. Our findings reveal the superiority of pairwise and listwise ranking approaches over pointwise ranking, PerRecBench's low correlation with traditional regression metrics, the importance of user profiles, and the role of pretraining data distributions. We further explore three supervised fine-tuning strategies, finding that merging weights from single-format training is promising but improving LLMs' understanding of user preferences remains an open research problem. Code and data are available at this https URL 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种任务中表现出色，包括个性化推荐。现有的评估方法往往侧重于评分预测，依赖于实际评分和预测评分之间的回归误差。然而，用户评分偏差和物品质量这两个影响评分分数的重要因素，可能会掩盖用户-物品对数据中的个人偏好。为了解决这个问题，我们引入了PerRecBench，使评估与这两个因素脱钩，并通过分组排名的方式评估推荐技术捕捉个人偏好的能力。我们发现，一般擅长评分预测的基于LLM的推荐技术，在消除用户评分偏差和物品质量后的分组用户数据中，难以识别用户的喜爱和不喜欢的物品。利用PerRecBench和19种LLM，我们发现虽然较大的模型通常优于较小的模型，但在个性化推荐方面仍存在问题。我们的研究结果揭示了成对排名和列表排名方法优于点预测方法的优势，PerRecBench和传统回归指标的相关性较低，用户资料的重要性，以及预训练数据分布的作用。我们进一步探讨了三种监督微调策略，发现从单一格式训练中合并权重是颇具前景的，但提升LLM对用户偏好的理解仍然是一个有待解决的研究问题。代码和数据可在以下链接获取：[此 https URL] 

---
# Do as We Do, Not as You Think: the Conformity of Large Language Models 

**Title (ZH)**: 《依葫芦画瓢，不必_guess 徒劳：大型语言模型的从众行为》

注释：这里的“徒劳”是对“Think”的一种幽默且学术规范的翻译，原句中的“Think”是作为对比出现的，意在指出与“Do as We Do”的对比，即模型的行为和人类的行为选择结果上的从众，而不是仅仅遵从错误的观念或假设。在中文翻译中，力求精准传达原意并符合中文的表达习惯。 

**Authors**: Zhiyuan Weng, Guikun Chen, Wenguan Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13381)  

**Abstract**: Recent advancements in large language models (LLMs) revolutionize the field of intelligent agents, enabling collaborative multi-agent systems capable of tackling complex problems across various domains. However, the potential of conformity within these systems, analogous to phenomena like conformity bias and groupthink in human group dynamics, remains largely unexplored, raising concerns about their collective problem-solving capabilities and possible ethical implications. This paper presents a comprehensive study on conformity in LLM-driven multi-agent systems, focusing on three aspects: the existence of conformity, the factors influencing conformity, and potential mitigation strategies. In particular, we introduce BenchForm, a new conformity-oriented benchmark, featuring reasoning-intensive tasks and five distinct interaction protocols designed to probe LLMs' behavior in collaborative scenarios. Several representative LLMs are evaluated on BenchForm, using metrics such as conformity rate and independence rate to quantify conformity's impact. Our analysis delves into factors influencing conformity, including interaction time and majority size, and examines how the subject agent rationalizes its conforming behavior. Furthermore, we explore two strategies to mitigate conformity effects, i.e., developing enhanced personas and implementing a reflection mechanism. Several interesting findings regarding LLMs' conformity are derived from empirical results and case studies. We hope that these insights can pave the way for more robust and ethically-aligned collaborative AI systems. Our benchmark and code are available at BenchForm. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）的最新进展正在重新定义智能代理领域，使得能够解决跨多个领域的复杂问题的协作多代理系统成为可能。然而，这些系统内部的从众现象——类似于人类群体动态中的从众偏见和团体思维等现象——的潜力仍未得到充分探索，这引起了对其集体解决问题能力及潜在伦理影响的担忧。本文对LLM驱动的多代理系统中的从众现象进行了全面研究，主要从三个方面进行了探讨：从众现象的存在、影响从众现象的因素以及潜在的缓解策略。特别是，我们引入了BenchForm，这是一种新的以从众为导向的基准测试，包含推理密集型任务和五种不同的交互协议，旨在探讨代理在协作场景中的行为。多种代表性LLM在BenchForm上进行评估，使用从众率和独立率等指标来量化从众现象的影响。我们的分析深入探讨了影响从众现象的因素，包括交互时间和多数人的规模，并考察了代理如何合理化其从众行为。此外，我们探讨了两种缓解从众现象影响的策略，即开发增强的人格和实施反思机制。从实验结果和案例研究中得出了关于LLMs从众现象的一些有趣发现。我们希望这些见解能够为更稳健且伦理导向的协作人工智能系统的开发铺平道路。我们的基准测试和代码可以在BenchForm上获得。 

---
# Watching the AI Watchdogs: A Fairness and Robustness Analysis of AI Safety Moderation Classifiers 

**Title (ZH)**: 观看AI守卫者的工作：关于AI安全调节分类器的公平性与鲁棒性分析 

**Authors**: Akshit Achara, Anshuman Chhabra  

**Link**: [PDF](https://arxiv.org/pdf/2501.13302)  

**Abstract**: AI Safety Moderation (ASM) classifiers are designed to moderate content on social media platforms and to serve as guardrails that prevent Large Language Models (LLMs) from being fine-tuned on unsafe inputs. Owing to their potential for disparate impact, it is crucial to ensure that these classifiers: (1) do not unfairly classify content belonging to users from minority groups as unsafe compared to those from majority groups and (2) that their behavior remains robust and consistent across similar inputs. In this work, we thus examine the fairness and robustness of four widely-used, closed-source ASM classifiers: OpenAI Moderation API, Perspective API, Google Cloud Natural Language (GCNL) API, and Clarifai API. We assess fairness using metrics such as demographic parity and conditional statistical parity, comparing their performance against ASM models and a fair-only baseline. Additionally, we analyze robustness by testing the classifiers' sensitivity to small and natural input perturbations. Our findings reveal potential fairness and robustness gaps, highlighting the need to mitigate these issues in future versions of these models. 

**Abstract (ZH)**: AI安全审核（ASM）分类器旨在规范社交媒体平台上的内容，并防止大型语言模型（LLMs）在不安全的输入上进行微调。由于它们可能产生不同的影响，确保这些分类器具备以下特性至关重要：（1）不得不公平地将少数群体用户的内容误分类为不安全内容，而多数群体用户的内容则不被误分类；（2）其行为在相似的输入上保持稳健且一致。因此，在本研究中，我们对四种广泛使用的、封闭源代码的ASM分类器进行了评估，包括OpenAI审核API、Perspective API、Google Cloud自然语言API（GCNL API）以及Clarifai API。我们使用人口统计平等和条件统计平等等公平性指标来评估这些分类器的性能，并将其与ASM模型和仅公平性基准进行比较。此外，我们还通过测试分类器对小规模和自然输入扰动的敏感性来分析其鲁棒性。我们的研究结果揭示了潜在的公平性和鲁棒性差距，强调在未来版本的这些模型中缓解这些问题的必要性。 

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

**Abstract (ZH)**: 多模态检索增强问答（MRAQA），结合文本和图像的信息检索（IR）和自然语言处理（NLP），已引起广泛关注。传统的排名方法依赖小型基于编码器的语言模型，这些模型与现代基于解码器的生成型大型语言模型（LLMs）不兼容，LLMs在多种NLP任务中取得了进步。为了解决这一问题，我们提出了一种名为RAMQA的统一框架，该框架结合了学习排序方法与生成型排列增强排名技术。首先，我们使用LLaVA作为基础模型训练一个点wise多模态排名器。然后，我们通过一种创新的自回归多任务学习方法对LLaMA模型进行指令微调，以对最有可能的文档列表进行再排名。我们的生成型排名模型能够从文档候选中生成再排名后的文档ID和特定答案，采用多种排列方式。在两个MRAQA基准数据集WebQA和MultiModalQA上的实验结果显示，相较于强基线方法，我们的方法取得了显著的改进，突显了该方法的有效性。相关代码和数据可在以下链接获取：this https URL 

---
# Automatic Fact-Checking with Frame-Semantics 

**Title (ZH)**: 基于框架语义学的自动事实核查 

**Authors**: Jacob Devasier, Rishabh Mediratta, Akshith Putta, Chengkai Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.13288)  

**Abstract**: We propose a novel paradigm for automatic fact-checking that leverages frame semantics to enhance the structured understanding of claims, addressing the challenges posed by misinformation in today's information ecosystem. To support this approach, we introduce a pilot dataset of real-world claims extracted from PolitiFact, specifically annotated for large-scale structured data. This dataset underpins two case studies: the first investigates voting-related claims using the Vote semantic frame, while the second explores various semantic frames and data sources from the Organisation for Economic Co-operation and Development (OECD). Our findings demonstrate the effectiveness of frame semantics in improving evidence retrieval, indicating a meaningful advancement in automatic fact-checking capabilities. Finally, we conducted a survey of frames evoked in fact-checked claims, identifying high-impact frames to guide future research. 

**Abstract (ZH)**: 我们提出了一种新颖的自动事实核查 paradigm，利用框架语义学来增强论断的结构化理解，以应对当今信息生态系统中假信息所带来的挑战。为支持这一方法，我们引入了一个基于 PolitiFact 的原型数据集，专门对大规模结构化数据进行了标注。该数据集支撑了两个案例研究：第一个案例研究使用投票框架 (Vote semantic frame) 探讨与投票相关的论断，第二个案例研究则探索来自经济合作与发展组织 (OECD) 的各种框架和数据源。我们的研究结果表明，框架语义学在提高证据检索效果方面非常有效，这标志着自动事实核查能力的一个实质性进展。最后，我们对经过事实核查的论断中唤起的框架进行了调查，以识别高影响框架，为未来的研究提供指导。 

---
# RAG-Reward: Optimizing RAG with Reward Modeling and RLHF 

**Title (ZH)**: RAG-Reword：通过奖励建模和RLHF优化RAG

注释：RAG通常指的是Retrieval-Augmented Generation，是一种结合检索和生成的技术，可以在生成文本时利用检索到的相关信息。在翻译时，保持了RAG的缩写形式，但在中文环境中，可以根据上下文将其展开为“检索增强生成”。此外，“RLHF”指的是Reinforcement Learning from Human Feedback，即从人类反馈中学习的强化学习。 

**Authors**: Hanning Zhang, Juntong Song, Juno Zhu, Yuanhao Wu, Tong Zhang, Cheng Niu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13264)  

**Abstract**: Retrieval-augmented generation (RAG) enhances Large Language Models (LLMs) with relevant and up-to-date knowledge, improving their ability to answer knowledge-intensive questions. It has been shown to enhance both generation quality and trustworthiness. While numerous works have focused on improving retrieval, generation, and evaluation, the role of reward models in reinforcement learning for optimizing RAG and establishing automated benchmarking pipelines remains underexplored. In this paper, we introduce \textbf{RAG-Reward}, a dataset designed to enable \textit{hallucination-free, comprehensive, reliable, and efficient RAG}. We define four key metrics for assessing generation quality and develop an automated annotation pipeline that leverages multiple LLMs to generate outputs across diverse RAG scenarios. GPT-4o is used to evaluate and construct preference data. Using \textbf{RAG-Reward}, we train reward models and apply reinforcement learning with human feedback (RLHF) to improve LLMs' effectiveness in RAG. Experimental results show that our reward model achieves state-of-the-art performance on a held-out test set, demonstrating both the effectiveness of our approach and the quality of our dataset. Furthermore, the improved generation quality of the trained policy model highlights the feasibility of using RLHF to enhance RAG pipelines. 

**Abstract (ZH)**: 检索增强生成（RAG）通过引入相关和最新的知识来增强大型语言模型（LLMs），从而提高其回答知识密集型问题的能力。已有研究表明，RAG能够提升生成质量和可信度。尽管许多研究集中在提高检索、生成和评估方面，但在强化学习中利用奖励模型优化RAG以及建立自动基准测试管道的作用仍较少被探索。在本文中，我们介绍了\textbf{RAG-Reward}数据集，旨在实现\textit{无幻觉、全面、可靠且高效的RAG}。我们定义了四个关键指标来评估生成质量，并开发了一个自动化注释管道，该管道利用多个LLM生成适用于多种RAG场景的输出。采用GPT-4o进行评估并构建偏好数据。使用\textbf{RAG-Reward}，我们训练了奖励模型，并应用基于人类反馈的强化学习（RLHF）来提升LLMs在RAG中的有效性。实验结果表明，我们的奖励模型在独立测试集上达到了最先进的性能，证明了我们方法的有效性和数据集的质量。此外，训练策略模型生成质量的提高进一步证实了使用RLHF增强RAG管道的可行性。 

---
# Preference Curriculum: LLMs Should Always Be Pretrained on Their Preferred Data 

**Title (ZH)**: 偏好课程学习：大规模语言模型应该始终在首选数据上进行预训练 

**Authors**: Xuemiao Zhang, Liangyu Xu, Feiyu Duan, Yongwei Zhou, Sirui Wang, Jingang Wang, Xunliang Cai  

**Link**: [PDF](https://arxiv.org/pdf/2501.13126)  

**Abstract**: Current large language models (LLMs) generally utilize a consistent data distribution throughout the entire pretraining process. However, as the model's ability improves, it intuitively should be pretrained with differentiated data. To achieve it, we propose the Perplexity Difference based Preference Curriculum learning (PDPC) framework, which always perceives and uses the data preferred by LLMs to train and boost them. Firstly, we introduce the PD metric to measure the difference in how well strong and weak models fit the samples. Samples with high PD are more challenging for weak models to learn and are more suitable to be arranged in the later stage of pretraining. Secondly, we propose the PD preference function to approximate the model and predict the data preference of the LLM at any time, so as to complete the arrangement of the entire data offline and ensure continuous training without interruption. Experimental results on 1.3B and 3B models demonstrate that our PDPC significantly surpasses baselines. Notably, the 3B model achieved more substantial gains, with an increased average accuracy of over 4.1% across various benchmarks. 

**Abstract (ZH)**: 当前的大规模语言模型（LLMs）通常在整个预训练过程中使用一致的数据分布。然而，随着模型能力的提升，直观上应使用差异化数据进行预训练。为了实现这一点，我们提出了基于困惑度差异的偏好课程学习（PDPC）框架，该框架始终感知并利用LLMs偏好的数据进行训练和提升。首先，我们引入了困惑度差异（PD）度量来衡量强模型和弱模型对样本拟合能力之间的差异。具有高PD的样本对于弱模型来说更具挑战性，并更适合安排在预训练的后期阶段。其次，我们提出了PD偏好函数来近似模型，并预测任意时刻LLMs的数据偏好，从而在线下完成整个数据的排列，确保连续无间断的训练。在1.3B和3B规模的模型上的实验结果表明，我们的PDPC显著超越了基线方法。值得注意的是，3B规模的模型取得了更大的提升，在不同基准测试中平均准确性提高了超过4.1%。 

---
# Generating Plausible Distractors for Multiple-Choice Questions via Student Choice Prediction 

**Title (ZH)**: 通过学生选择预测生成合理的多项选择题干扰项 

**Authors**: Yooseop Lee, Suin Kim, Yohan Jo  

**Link**: [PDF](https://arxiv.org/pdf/2501.13125)  

**Abstract**: In designing multiple-choice questions (MCQs) in education, creating plausible distractors is crucial for identifying students' misconceptions and gaps in knowledge and accurately assessing their understanding. However, prior studies on distractor generation have not paid sufficient attention to enhancing the difficulty of distractors, resulting in reduced effectiveness of MCQs. This study presents a pipeline for training a model to generate distractors that are more likely to be selected by students. First, we train a pairwise ranker to reason about students' misconceptions and assess the relative plausibility of two distractors. Using this model, we create a dataset of pairwise distractor ranks and then train a distractor generator via Direct Preference Optimization (DPO) to generate more plausible distractors. Experiments on computer science subjects (Python, DB, MLDL) demonstrate that our pairwise ranker effectively identifies students' potential misunderstandings and achieves ranking accuracy comparable to human experts. Furthermore, our distractor generator outperforms several baselines in generating plausible distractors and produces questions with a higher item discrimination index (DI). 

**Abstract (ZH)**: 在教育中设计多项选择题（MCQs）时，生成合理的干扰项对于识别学生的思想误区和知识缺口以及准确评估其理解能力至关重要。然而，之前关于干扰项生成的研究并未充分关注增强干扰项的难度，从而减少了MCQs的有效性。本研究提出了一种生成更可能被学生选中的干扰项的模型训练管道。首先，我们训练了一个成对排序器来推理学生的思想误区，并评估两个干扰项的相对合理性。利用该模型，我们构建了一个成对干扰项排序的数据集，并通过直接偏好优化（DPO）训练了一个干扰项生成器，以生成更多合理的干扰项。实验表明，在计算机科学领域（Python、DB、MLDL）中，我们的成对排序器有效地识别了学生的潜在误解，并且排名准确性与人类专家相当。此外，我们的干扰项生成器在生成合理干扰项方面优于几种基线模型，并生成了具有更高项目鉴别指数（DI）的问题。 

---
# Debate Helps Weak-to-Strong Generalization 

**Title (ZH)**: 辩论有助于从弱到强的泛化能力提升 

**Authors**: Hao Lang, Fei Huang, Yongbin Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.13124)  

**Abstract**: Common methods for aligning already-capable models with desired behavior rely on the ability of humans to provide supervision. However, future superhuman models will surpass the capability of humans. Therefore, humans will only be able to weakly supervise superhuman models. This expected deficiency of human evaluation would weaken the safety of future AI systems. Scalable oversight and weak-to-strong generalization are two complementary approaches to tackle this issue. In this paper, we attempt to combine the strengths of these two approaches to further improve alignment. Specifically, we investigate ways of improving human supervision with a strong pretrained model and then supervise the strong model with enhanced weak human supervision. To make iterative empirical progress, we consider an analogy: can we use a strong model to improve weak model supervision and then use it to supervise the strong model? We empirically test it by finetuning a small weak model on ground truth labels with the additional help from a large strong model, and then finetuning the strong model on labels generated by the weak model. We find that debate can assist a weak model in extracting trustworthy information from an untrustworthy strong model, which provides leverage as context on samples when training a weak model. We also show that an ensemble of weak models helps exploit long arguments generated by strong model debaters and obtain a more robust supervision estimate. Extensive experiments on the OpenAI weak-to-strong NLP benchmarks show that the combination approach leads to better alignment, which indicates that debate has the potential to help weak-to-strong generalization. 

**Abstract (ZH)**: 目前用于调整已具备能力的模型以符合期望行为的方法大多依赖于人类的监督能力。然而，未来的超级智能模型将会超越人类的能力，因此人类只能进行有限监督。这种预期的人类评估不足将削弱未来AI系统的安全性。可扩展的监管和从有限监督到完全监督的泛化是应对这一问题的两种互补方法。本文尝试将这两种方法的优势结合起来，进一步提高模型的对齐程度。具体而言，我们研究了利用强大的预训练模型改进人类监督的方式，然后使用增强的人类监督来监督强大的模型。为了实现迭代的实证进展，我们借鉴了一个类比：是否可以使用强大模型来改善弱模型的监督，然后使用这种方法监督强大的模型？我们通过在真实标签的帮助下微调一个小型弱模型，并利用强大模型生成的标签进一步微调强大模型进行了实证测试。我们发现，辩论可以帮助弱模型从不可信赖的强大模型中提取可信信息，并在训练弱模型时提供上下文支持。我们还展示了弱模型的集合如何帮助利用强大模型辩论者生成的长论证，从而获得更稳健的监督估计。广泛的实验表明，这种结合方法能够更好地实现模型对齐，这表明辩论具有帮助实现从弱到强泛化的潜力。 

---
# Zero-Shot Verification-guided Chain of Thoughts 

**Title (ZH)**: 零样本验证引导的思维链 

**Authors**: Jishnu Ray Chowdhury, Cornelia Caragea  

**Link**: [PDF](https://arxiv.org/pdf/2501.13122)  

**Abstract**: Previous works have demonstrated the effectiveness of Chain-of-Thought (COT) prompts and verifiers in guiding Large Language Models (LLMs) through the space of reasoning. However, most such studies either use a fine-tuned verifier or rely on manually handcrafted few-shot examples. In contrast, in this paper, we focus on LLM-based self-verification of self-generated reasoning steps via COT prompts in a completely zero-shot regime. To explore this setting, we design a new zero-shot prompt, which we call COT STEP, to aid zero-shot decomposition of reasoning steps and design two new zero-shot prompts for LLM-based verifiers. We evaluate the verifiers' ability to classify the correctness of reasoning chains and explore different ways to use verifier scores in guiding reasoning for various mathematical and commonsense reasoning tasks with different LLMs. 

**Abstract (ZH)**: 以往的研究已经证明，通过Chain-of-Thought (COT) 提示和验证器可以指导大型语言模型（LLMs）在推理空间中的有效导航。然而，大多数此类研究要么使用微调的验证器，要么依赖于手动手工编写的少量示例。相比之下，本文关注的是通过COT 提示实现基于LLM 的自我验证，无需任何微调和预训练示例。为了探索这种设置，我们设计了一个新的零样本提示——称为COT STEP，以帮助零样本分解推理步骤，并设计了两种新的零样本提示，用于基于LLM 的验证器。我们评估了验证器在分类推理链的正确性方面的能力，并探索了使用验证器分数的不同方法，以引导各种数学和常识推理任务中的推理，其中使用了不同类型的LLM。 

---
# Episodic Memories Generation and Evaluation Benchmark for Large Language Models 

**Title (ZH)**: 大型语言模型的 episodic 记忆生成与评估基准 

**Authors**: Alexis Huet, Zied Ben Houidi, Dario Rossi  

**Link**: [PDF](https://arxiv.org/pdf/2501.13121)  

**Abstract**: Episodic memory -- the ability to recall specific events grounded in time and space -- is a cornerstone of human cognition, enabling not only coherent storytelling, but also planning and decision-making. Despite their remarkable capabilities, Large Language Models (LLMs) lack a robust mechanism for episodic memory: we argue that integrating episodic memory capabilities into LLM is essential for advancing AI towards human-like cognition, increasing their potential to reason consistently and ground their output in real-world episodic events, hence avoiding confabulations. To address this challenge, we introduce a comprehensive framework to model and evaluate LLM episodic memory capabilities. Drawing inspiration from cognitive science, we develop a structured approach to represent episodic events, encapsulating temporal and spatial contexts, involved entities, and detailed descriptions. We synthesize a unique episodic memory benchmark, free from contamination, and release open source code and datasets to assess LLM performance across various recall and episodic reasoning tasks. Our evaluation of state-of-the-art models, including GPT-4 and Claude variants, Llama 3.1, and o1-mini, reveals that even the most advanced LLMs struggle with episodic memory tasks, particularly when dealing with multiple related events or complex spatio-temporal relationships -- even in contexts as short as 10k-100k tokens. 

**Abstract (ZH)**: episodic 记忆，即回忆特定的时间和空间背景下的事件的能力，是人类认知的基础，不仅使连贯的故事叙述成为可能，还使规划和决策成为可能。尽管大型语言模型（LLMs）具备令人印象深刻的能力，但它们缺乏稳定的 episodic 记忆机制：我们认为，将 episodic 记忆能力整合到 LLM 中对于推动人工智能向人类认知方向发展至关重要，可以提高它们合理推理和将其输出与现实世界的具体事件联系起来的能力，从而避免虚构行为。为解决这一挑战，我们提出了一个全面的框架来建模和评估 LLM 的 episodic 记忆能力。借鉴认知科学的思路，我们开发了一个有组织的方法来表示 episodic 事件，涵盖了时间与空间背景、涉及的实体以及详细的描述。我们合成了一个独特且不受污染的 episodic 记忆基准，并公开了代码和数据集，以便在各种回忆和 episodic 推理任务中评估 LLM 的性能。对包括 GPT-4 和 Claude 变体、Llama 3.1 以及 o1-mini 在内的最新模型的评估表明，即使是目前最先进的 LLM 也难以完成 episodic 记忆任务，尤其是在涉及多个相关事件或复杂时空关系的情况下——即使文本长度仅为 10K-100K 个标记也是如此。 

---
# Multilinguality in LLM-Designed Reward Functions for Restless Bandits: Effects on Task Performance and Fairness 

**Title (ZH)**: LLM设计的奖励函数中的多语言性对奖励问题任务性能和公平性的影响 

**Authors**: Ambreesh Parthasarathy, Chandrasekar Subramanian, Ganesh Senrayan, Shreyash Adappanavar, Aparna Taneja, Balaraman Ravindran, Milind Tambe  

**Link**: [PDF](https://arxiv.org/pdf/2501.13120)  

**Abstract**: Restless Multi-Armed Bandits (RMABs) have been successfully applied to resource allocation problems in a variety of settings, including public health. With the rapid development of powerful large language models (LLMs), they are increasingly used to design reward functions to better match human preferences. Recent work has shown that LLMs can be used to tailor automated allocation decisions to community needs using language prompts. However, this has been studied primarily for English prompts and with a focus on task performance only. This can be an issue since grassroots workers, especially in developing countries like India, prefer to work in local languages, some of which are low-resource. Further, given the nature of the problem, biases along population groups unintended by the user are also undesirable. In this work, we study the effects on both task performance and fairness when the DLM algorithm, a recent work on using LLMs to design reward functions for RMABs, is prompted with non-English language commands. Specifically, we run the model on a synthetic environment for various prompts translated into multiple languages. The prompts themselves vary in complexity. Our results show that the LLM-proposed reward functions are significantly better when prompted in English compared to other languages. We also find that the exact phrasing of the prompt impacts task performance. Further, as prompt complexity increases, performance worsens for all languages; however, it is more robust with English prompts than with lower-resource languages. On the fairness side, we find that low-resource languages and more complex prompts are both highly likely to create unfairness along unintended dimensions. 

**Abstract (ZH)**: 羁旅多臂 bandit (RMABs) 已经成功应用于各种环境下的资源分配问题，包括公共卫生领域。随着强大大型语言模型 (LLMs) 的迅速发展，它们被越来越多地用于设计奖励函数，以更好地匹配人类偏好。近期研究表明，LLMs 可以通过语言提示来定制自动化分配决策，以满足社区需求。然而，这主要是在英文提示下进行的研究，并且重点关注任务性能。这可能是个问题，因为基层工作人员，尤其是在印度等发展中地区，更倾向于使用当地语言工作，而这些语言资源相对有限。此外，考虑到问题的性质，用户未意想的群体偏向也是不希望出现的。在本文中，我们研究了当使用 DLM 算法（一种利用 LLMs 为 RMABs 设计奖励函数的近期工作）时，用非英文语言指令进行提示对任务性能和公平性的影响。具体地，我们在多个语言版本的提示下运行模型，以模拟不同的合成环境。这些提示在复杂性上有所不同。我们的结果显示，与用其他语言提示相比，用英文提示提出的人工智能建议奖励函数效果显著更好。我们还发现，提示的具体措辞也会影响任务性能。进一步地，随着提示复杂性的增加，所有语言的任务性能均下降；然而，使用英文提示比使用资源较少的语言提示更具鲁棒性。在公平性方面，我们发现资源较少的语言和更复杂的提示都很容易在未意想的维度上产生不公平现象。 

---
# MyGO Multiplex CoT: A Method for Self-Reflection in Large Language Models via Double Chain of Thought Thinking 

**Title (ZH)**: MyGO多层共思：大型语言模型中双重链式思考的自我反思方法 

**Authors**: Shihao Ji, Zihui Song, Fucheng Zhong, Jisen Jia, Zhaobo Wu, Zheyi Cao, Tianhao Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13117)  

**Abstract**: Recent advancements in large language models (LLMs) have demonstrated their impressive abilities in various reasoning and decision-making tasks. However, the quality and coherence of the reasoning process can still benefit from enhanced introspection and self-reflection. In this paper, we introduce Multiplex CoT (Chain of Thought), a method that enables LLMs to simulate a form of self-review while reasoning, by initiating double Chain of Thought (CoT) thinking. Multiplex CoT leverages the power of iterative reasoning, where the model generates an initial chain of thought and subsequently critiques and refines this reasoning with a second round of thought generation. This recursive approach allows for more coherent, logical, and robust answers, improving the overall decision-making process. We demonstrate how this method can be effectively implemented using simple prompt engineering in existing LLM architectures, achieving an effect similar to that of the Learning-Refinement Model (LRM) without the need for additional training. Additionally, we present a practical guide for implementing the method in Google Colab, enabling easy integration into real-world applications. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）在各种推理和决策任务中展示了令人印象深刻的性能。然而，推理过程的质量和连贯性仍有待通过增强的内省和自我反思来提升。本文提出了Multiplex CoT（思维链），这是一种方法，能够在推理过程中模拟一种自我审查的形式，通过启动双重思维链（CoT）思考来实现这一目的。Multiplex CoT 利用了迭代推理的力量，模型首先生成初始思维链，然后通过第二次思维生成对其进行批判和改进。这种递归方法能够提供更加连贯、逻辑严密且稳健的答案，改善整体决策过程。我们展示了如何通过简单的提示工程在现有的LLM架构中有效实现该方法，从而在无需额外训练的情况下达到类似学习-精炼模型（LRM）的效果。此外，我们还提供了一种实用指南，说明如何在Google Colab中实现该方法，以便轻松将其集成到实际应用中。 

---
# Dagger Behind Smile: Fool LLMs with a Happy Ending Story 

**Title (ZH)**: 微笑背后有暗钩：用happy ending的故事欺骗LLMs 

**Authors**: Xurui Song, Zhixin Xie, Shuo Huai, Jiayi Kong, Jun Luo  

**Link**: [PDF](https://arxiv.org/pdf/2501.13115)  

**Abstract**: The wide adoption of Large Language Models (LLMs) has attracted significant attention from \textit{jailbreak} attacks, where adversarial prompts crafted through optimization or manual design exploit LLMs to generate malicious content. However, optimization-based attacks have limited efficiency and transferability, while manual designs are either easily detectable or demand intricate interactions with LLMs. In this paper, we first point out a novel perspective for jailbreak attacks: LLMs are more responsive to \textit{positive} prompts. Based on this, we deploy Happy Ending Attack (HEA) to wrap up a malicious request in a scenario template involving a positive prompt formed mainly via a \textit{happy ending}, it thus fools LLMs into jailbreaking either immediately or at a follow-up malicious request. This has made HEA both efficient and effective, as it requires only up to two steps to fully jailbreak LLMs. Extensive experiments show that our HEA can successfully jailbreak on state-of-the-art LLMs, including GPT-4o, Llama3-70b, Gemini-pro, and achieves 88.79\% Attack Success Rate on average. We also provide potential quantitative explanations for the success of HEA. 

**Abstract (ZH)**: 大型语言模型（LLMs）的广泛应用吸引了对“脱逃”攻击（\textit{jailbreak} 攻击）的广泛关注，这类攻击通过优化或手动设计的对抗提示，利用LLMs生成恶意内容。然而，基于优化的攻击效率较低且不具备良好的可移植性，而手动设计的攻击要么容易被检测，要么需要复杂的与LLMs的交互。本文首先提出了一种新的“脱逃”攻击视角：LLMs 对积极的提示更为敏感。基于此，我们部署了Happy Ending Attack（HEA）攻击，通过情景模板将恶意请求包装在一个主要由“happy ending”形成的积极提示中，从而使LLMs 在接收到深层恶意请求时被诱骗进行“脱逃”。这使得HEA 既高效又有效，只需两步即可完全“脱逃”LLMs。广泛的实验证明，我们的HEA 可以成功地对最先进的LLMs（包括GPT-4o、Llama3-70b、Gemini-pro）实施“脱逃”攻击，并平均实现了88.79%的攻击成功率。我们还提供了HEA 成功的潜在定量解释。 

---
# Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step 

**Title (ZH)**: 我们可以生成带有解释过程的图像吗？让我们逐步验证和强化图像生成过程 

**Authors**: Ziyu Guo, Renrui Zhang, Chengzhuo Tong, Zhizheng Zhao, Peng Gao, Hongsheng Li, Pheng-Ann Heng  

**Link**: [PDF](https://arxiv.org/pdf/2501.13926)  

**Abstract**: Chain-of-Thought (CoT) reasoning has been extensively explored in large models to tackle complex understanding tasks. However, it still remains an open question whether such strategies can be applied to verifying and reinforcing image generation scenarios. In this paper, we provide the first comprehensive investigation of the potential of CoT reasoning to enhance autoregressive image generation. We focus on three techniques: scaling test-time computation for verification, aligning model preferences with Direct Preference Optimization (DPO), and integrating these techniques for complementary effects. Our results demonstrate that these approaches can be effectively adapted and combined to significantly improve image generation performance. Furthermore, given the pivotal role of reward models in our findings, we propose the Potential Assessment Reward Model (PARM) and PARM++, specialized for autoregressive image generation. PARM adaptively assesses each generation step through a potential assessment approach, merging the strengths of existing reward models, and PARM++ further introduces a reflection mechanism to self-correct the generated unsatisfactory image. Using our investigated reasoning strategies, we enhance a baseline model, Show-o, to achieve superior results, with a significant +24% improvement on the GenEval benchmark, surpassing Stable Diffusion 3 by +15%. We hope our study provides unique insights and paves a new path for integrating CoT reasoning with autoregressive image generation. Code and models are released at this https URL 

**Abstract (ZH)**: 将以下论文内容或标题翻译成中文，以符合学术规范：

链式推理 (Chain-of-Thought, CoT) 战略已在大型模型中广泛研究，以解决复杂的理解任务。然而，仍不清楚这些策略是否可以应用于验证和强化图像生成场景。本文首次全面探讨了CoT推理在增强自回归图像生成方面的潜力。我们重点关注三种技术：扩展测试时的计算量以进行验证、将模型偏好与直接偏好优化（DPO）对齐，以及结合这些技术以产生互补效果。我们的研究结果表明，这些方法可以通过有效的适应和结合显著提高图像生成性能。此外，鉴于我们在研究中发现的奖励模型的关键作用，我们提出了专门针对自回归图像生成的潜在评估奖励模型（PARM）和 PARM++。PARM 通过潜在评估方法动态评估每个生成步骤，整合现有奖励模型的优点；而 PARM++ 进一步引入了反思机制，以自我纠正生成的不满意图像。利用我们探索的推理策略，我们增强了 Show-o 基线模型，并在 GenEval 基准测试中取得了显著的 +24% 改进，超过了 Stable Diffusion 3 的 +15%。我们希望我们的研究能提供独特的见解，并开辟将 CoT 推理与自回归图像生成集成的新路径。相关代码和模型已在此处发布：[提供链接] 

---
# IMAGINE-E: Image Generation Intelligence Evaluation of State-of-the-art Text-to-Image Models 

**Title (ZH)**: IMAGINE-E：先进文本到图像模型的图像生成智能评估 

**Authors**: Jiayi Lei, Renrui Zhang, Xiangfei Hu, Weifeng Lin, Zhen Li, Wenjian Sun, Ruoyi Du, Le Zhuo, Zhongyu Li, Xinyue Li, Shitian Zhao, Ziyu Guo, Yiting Lu, Peng Gao, Hongsheng Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.13920)  

**Abstract**: With the rapid development of diffusion models, text-to-image(T2I) models have made significant progress, showcasing impressive abilities in prompt following and image generation. Recently launched models such as FLUX.1 and Ideogram2.0, along with others like Dall-E3 and Stable Diffusion 3, have demonstrated exceptional performance across various complex tasks, raising questions about whether T2I models are moving towards general-purpose applicability. Beyond traditional image generation, these models exhibit capabilities across a range of fields, including controllable generation, image editing, video, audio, 3D, and motion generation, as well as computer vision tasks like semantic segmentation and depth estimation. However, current evaluation frameworks are insufficient to comprehensively assess these models' performance across expanding domains. To thoroughly evaluate these models, we developed the IMAGINE-E and tested six prominent models: FLUX.1, Ideogram2.0, Midjourney, Dall-E3, Stable Diffusion 3, and Jimeng. Our evaluation is divided into five key domains: structured output generation, realism, and physical consistency, specific domain generation, challenging scenario generation, and multi-style creation tasks. This comprehensive assessment highlights each model's strengths and limitations, particularly the outstanding performance of FLUX.1 and Ideogram2.0 in structured and specific domain tasks, underscoring the expanding applications and potential of T2I models as foundational AI tools. This study provides valuable insights into the current state and future trajectory of T2I models as they evolve towards general-purpose usability. Evaluation scripts will be released at this https URL. 

**Abstract (ZH)**: 随着扩散模型的飞速发展，文本到图像（T2I）模型取得了显著进步，展示了其在指令跟随和图像生成方面的出色能力。最近推出的模型，如FLUX.1和Ideogram2.0，以及其他模型如Dall-E3和Stable Diffusion 3，已经在各种复杂任务中展现了卓越性能，引发了关于T2I模型是否正朝着通用适用性发展的讨论。除了传统的图像生成外，这些模型还在可控生成、图像编辑、视频、音频、3D和运动生成，以及语义分割和深度估计等计算机视觉任务中表现出广泛的适用能力。然而，当前的评估框架尚不足以全面评估这些模型在不断扩展领域的性能。为了全面评估这些模型，我们开发了IMAGINE-E框架，并测试了六种突出的模型：FLUX.1、Ideogram2.0、Midjourney、Dall-E3、Stable Diffusion 3和Jimeng。我们的评估分为五个关键领域：结构化输出生成、真实性、物理一致性、特定领域生成、具有挑战性的场景生成以及多风格生成任务。这项全面的评估突显了每个模型的优势和局限性，特别是在FLUX.1和Ideogram2.0在结构化和特定领域任务中的卓越表现，强调了T2I模型作为基础AI工具的广泛应用前景和潜力。本研究为T2I模型当前状态及其向通用适用性发展的未来路径提供了宝贵的见解。评估脚本将在此链接中公布：[此 https URL]。 

---
# Temporal Preference Optimization for Long-Form Video Understanding 

**Title (ZH)**: 长时视频理解中的时间偏好优化 

**Authors**: Rui Li, Xiaohan Wang, Yuhui Zhang, Zeyu Wang, Serena Yeung-Levy  

**Link**: [PDF](https://arxiv.org/pdf/2501.13919)  

**Abstract**: Despite significant advancements in video large multimodal models (video-LMMs), achieving effective temporal grounding in long-form videos remains a challenge for existing models. To address this limitation, we propose Temporal Preference Optimization (TPO), a novel post-training framework designed to enhance the temporal grounding capabilities of video-LMMs through preference learning. TPO adopts a self-training approach that enables models to differentiate between well-grounded and less accurate temporal responses by leveraging curated preference datasets at two granularities: localized temporal grounding, which focuses on specific video segments, and comprehensive temporal grounding, which captures extended temporal dependencies across entire video sequences. By optimizing on these preference datasets, TPO significantly enhances temporal understanding while reducing reliance on manually annotated data. Extensive experiments on three long-form video understanding benchmarks--LongVideoBench, MLVU, and Video-MME--demonstrate the effectiveness of TPO across two state-of-the-art video-LMMs. Notably, LLaVA-Video-TPO establishes itself as the leading 7B model on the Video-MME benchmark, underscoring the potential of TPO as a scalable and efficient solution for advancing temporal reasoning in long-form video understanding. Project page: this https URL. 

**Abstract (ZH)**: 尽管在视频大规模多模态模型（Video-LMMs）方面已取得显著进展，但现有模型在长视频中实现有效的时空定位仍是一项挑战。为应对这一局限性，我们提出了时空偏好优化（TPO，Temporal Preference Optimization），这是一种新颖的后训练框架，旨在通过偏好学习增强Video-LMMs的时空定位能力。TPO 采用自训练方法，使模型能够通过融合两个粒度的偏好数据集区分精确的和不准确的时空响应：局部时空定位关注特定视频片段，而全时段时空定位则捕捉整个视频序列中的长期时空依赖关系。通过优化这些偏好数据集，TPO 显著提高了时空理解能力，同时减少了对手动标注数据的依赖。在三个长视频理解基准测试集（LongVideoBench、MLVU 和 Video-MME）上进行的广泛实验表明，TPO 能够在两种最先进的视频-LMMs 上取得显著效果。值得注意的是，LLaVA-Video-TPO 成为了 Video-MME 基准测试集上 7B 模型的领先模型，这突显了 TPO 作为提升长视频理解中时空推理能力的一种可扩展且高效解决方案的潜力。项目页面：请访问此链接。 

---
# On the Reasoning Capacity of AI Models and How to Quantify It 

**Title (ZH)**: AI模型的推理能力及其量化方法探究 

**Authors**: Santosh Kumar Radha, Oktay Goktas  

**Link**: [PDF](https://arxiv.org/pdf/2501.13833)  

**Abstract**: Recent advances in Large Language Models (LLMs) have intensified the debate surrounding the fundamental nature of their reasoning capabilities. While achieving high performance on benchmarks such as GPQA and MMLU, these models exhibit limitations in more complex reasoning tasks, highlighting the need for more rigorous evaluation methodologies. We propose a novel phenomenological approach that goes beyond traditional accuracy metrics to probe the underlying mechanisms of model behavior, establishing a framework that could broadly impact how we analyze and understand AI systems. Using positional bias in multiple-choice reasoning tasks as a case study, we demonstrate how systematic perturbations can reveal fundamental aspects of model decision-making. To analyze these behaviors, we develop two complementary phenomenological models: a Probabilistic Mixture Model (PMM) that decomposes model responses into reasoning, memorization, and guessing components and an Information-Theoretic Consistency (ITC) analysis that quantifies the relationship between model confidence and strategy selection. Through controlled experiments on reasoning benchmarks, we show that true reasoning remains challenging for current models, with apparent success often relying on sophisticated combinations of memorization and pattern matching rather than genuine logical deduction. More fundamentally, we demonstrate that accuracy alone often overstates a model's reasoning abilities, as model behavior can be characterized through underlying mechanisms in the phase space of cognitive strategies, revealing how models dynamically balance different approaches when responding to queries. This framework enables quantitative criteria for real-world deployments, allowing applications to specify reliability thresholds based on strategy distributions rather than aggregate performance metrics. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的发展加剧了对其推理能力基本性质的争论。尽管在GPQA和MMLU等基准测试中表现出色，这些模型在更复杂的推理任务中显示出局限性，这表明需要更严格的评估方法。我们提出了一种新的现象学方法，这种方法超越了传统的准确率指标，以探究模型行为背后的机制，建立了一个可能广泛影响我们分析和理解AI系统的框架。通过将位置偏见作为多项选择推理任务的案例研究，我们展示了系统性扰动如何揭示模型决策的基本方面。为了分析这些行为，我们开发了两种互补的现象学模型：概率混合模型（PMM），它将模型响应分解为推理、记忆和猜测成分，以及基于信息论一致性（ITC）的分析，量化模型信心与策略选择之间的关系。通过在推理基准测试上的受控实验，我们证明了当前模型在真正推理方面仍然具有挑战性，表面上的成功往往依赖于记忆和模式匹配的复杂组合，而不是真实的逻辑推理。更本质的是，我们证明了仅仅依靠准确率往往高估了模型的推理能力，因为模型行为可以通过认知策略相空间中的基机制进行特征描述，揭示了模型在回应查询时如何动态平衡不同的方法。这一框架为实际部署提供了量化标准，使应用程序可以根据策略分布而非综合性能指标来指定可靠性阈值。 

---
# Video-MMMU: Evaluating Knowledge Acquisition from Multi-Discipline Professional Videos 

**Title (ZH)**: 视频-MMMU模型：评估多学科专业视频中的知识获取 

**Authors**: Kairui Hu, Penghao Wu, Fanyi Pu, Wang Xiao, Yuanhan Zhang, Xiang Yue, Bo Li, Ziwei Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13826)  

**Abstract**: Humans acquire knowledge through three cognitive stages: perceiving information, comprehending knowledge, and adapting knowledge to solve novel problems. Videos serve as an effective medium for this learning process, facilitating a progression through these cognitive stages. However, existing video benchmarks fail to systematically evaluate the knowledge acquisition capabilities in Large Multimodal Models (LMMs). To address this gap, we introduce Video-MMMU, a multi-modal, multi-disciplinary benchmark designed to assess LMMs' ability to acquire and utilize knowledge from videos. Video-MMMU features a curated collection of 300 expert-level videos and 900 human-annotated questions across six disciplines, evaluating knowledge acquisition through stage-aligned question-answer pairs: Perception, Comprehension, and Adaptation. A proposed knowledge gain metric, {\Delta}knowledge, quantifies improvement in performance after video viewing. Evaluation of LMMs reveals a steep decline in performance as cognitive demands increase and highlights a significant gap between human and model knowledge acquisition, underscoring the need for methods to enhance LMMs' capability to learn and adapt from videos. 

**Abstract (ZH)**: 人类通过三个认知阶段获取知识：感知信息、理解知识以及将知识应用于解决新问题。视频作为一种有效的媒介，促进了这一学习过程，帮助依次完成这些认知阶段。然而，现有的视频基准未能系统地评估大型多模态模型（LMMs）的知识获取能力。为解决这一问题，我们引入了Video-MMMU，这是一个多模态、跨学科的基准，用于评估LMMs从视频中获取和利用知识的能力。Video-MMMU 包含了涵盖六个学科领域的300个专家级视频和900个人标注问题的精选集合，并通过阶段对齐的问题-答案对评估知识获取：感知、理解以及应用。我们还提出了一种知识增益度量{\(\Delta\)knowledge}，用于量化视频观看后性能的提升。对LMMs的评估揭示了随着认知需求的增加，其性能显著下降，并指出了人类与模型之间在知识获取能力上的显著差距，强调了需要开发增强LMMs从视频中学习和适应能力的方法。 

---
# Explainable XR: Understanding User Behaviors of XR Environments using LLM-assisted Analytics Framework 

**Title (ZH)**: 可解释的XR：使用LLM辅助分析框架理解XR环境中的用户行为 

**Authors**: Yoonsang Kim, Zainab Aamir, Mithilesh Singh, Saeed Boorboor, Klaus Mueller, Arie E. Kaufman  

**Link**: [PDF](https://arxiv.org/pdf/2501.13778)  

**Abstract**: We present Explainable XR, an end-to-end framework for analyzing user behavior in diverse eXtended Reality (XR) environments by leveraging Large Language Models (LLMs) for data interpretation assistance. Existing XR user analytics frameworks face challenges in handling cross-virtuality - AR, VR, MR - transitions, multi-user collaborative application scenarios, and the complexity of multimodal data. Explainable XR addresses these challenges by providing a virtuality-agnostic solution for the collection, analysis, and visualization of immersive sessions. We propose three main components in our framework: (1) A novel user data recording schema, called User Action Descriptor (UAD), that can capture the users' multimodal actions, along with their intents and the contexts; (2) a platform-agnostic XR session recorder, and (3) a visual analytics interface that offers LLM-assisted insights tailored to the analysts' perspectives, facilitating the exploration and analysis of the recorded XR session data. We demonstrate the versatility of Explainable XR by demonstrating five use-case scenarios, in both individual and collaborative XR applications across virtualities. Our technical evaluation and user studies show that Explainable XR provides a highly usable analytics solution for understanding user actions and delivering multifaceted, actionable insights into user behaviors in immersive environments. 

**Abstract (ZH)**: 我们提出了可解释的扩展现实（Explainable XR），这是一个端到端框架，利用大语言模型（LLMs）进行数据解释辅助，以分析在多种扩展现实（XR）环境中的用户行为。现有的XR用户分析框架在处理AR、VR、MR之间的转换、多用户协作应用场景以及多模态数据的复杂性时存在挑战。Explainable XR通过提供一种与虚拟现实无关的解决方案来解决这些挑战，该解决方案用于收集、分析和可视化沉浸式会话。我们提出了框架中的三个主要组件：（1）一种新的用户数据记录模式，称为用户动作描述符（UAD），能够捕捉用户的多模态行为及其意图和上下文；（2）一个平台无关的XR会话记录器；以及（3）一种基于大语言模型的视觉分析界面，提供定制化的分析洞见，以便分析师探索和分析记录的XR会话数据。我们通过在不同虚拟现实环境中的个体和协作XR应用中展示五个用例场景，展示了Explainable XR的灵活性。我们的技术评估和用户研究显示，Explainable XR提供了一个高度可用的分析解决方案，用于理解和提供关于沉浸式环境中用户行为多方面的、可操作的洞察。 

---
# Certified Robustness Under Bounded Levenshtein Distance 

**Title (ZH)**: 具有有界莱文斯坦距离的认证鲁棒性 

**Authors**: Elias Abad Rocamora, Grigorios G. Chrysos, Volkan Cevher  

**Link**: [PDF](https://arxiv.org/pdf/2501.13676)  

**Abstract**: Text classifiers suffer from small perturbations, that if chosen adversarially, can dramatically change the output of the model. Verification methods can provide robustness certificates against such adversarial perturbations, by computing a sound lower bound on the robust accuracy. Nevertheless, existing verification methods incur in prohibitive costs and cannot practically handle Levenshtein distance constraints. We propose the first method for computing the Lipschitz constant of convolutional classifiers with respect to the Levenshtein distance. We use these Lipschitz constant estimates for training 1-Lipschitz classifiers. This enables computing the certified radius of a classifier in a single forward pass. Our method, LipsLev, is able to obtain $38.80$% and $13.93$% verified accuracy at distance $1$ and $2$ respectively in the AG-News dataset, while being $4$ orders of magnitude faster than existing approaches. We believe our work can open the door to more efficient verification in the text domain. 

**Abstract (ZH)**: 文本分类器对小型扰动非常敏感，如果这些扰动是恶意选择的，可以显著改变模型的输出。验证方法可以通过计算鲁棒准确度的严格下界来提供对抗扰动的鲁棒性证书。然而，现有的验证方法成本极高，无法实际处理Levenshtein距离约束。我们提出了第一个计算卷积分类器在Levenshtein距离下的Lipschitz常数的方法。我们利用这些Lipschitz常数估计值来训练1-Lipschitz分类器。这使得可以在单次前向传播中计算分类器的验证半径。我们的方法LipsLev在AG-News数据集中分别在距离为1和2时获得了38.80%和13.93%的验证准确率，比现有方法快4个数量级。我们相信我们的工作可以为文本领域的更高效验证打开新的大门。 

---
# ReasVQA: Advancing VideoQA with Imperfect Reasoning Process 

**Title (ZH)**: ReasVQA：改进推理过程的视频问答研究 

**Authors**: Jianxin Liang, Xiaojun Meng, Huishuai Zhang, Yueqian Wang, Jiansheng Wei, Dongyan Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2501.13536)  

**Abstract**: Video Question Answering (VideoQA) is a challenging task that requires understanding complex visual and temporal relationships within videos to answer questions accurately. In this work, we introduce \textbf{ReasVQA} (Reasoning-enhanced Video Question Answering), a novel approach that leverages reasoning processes generated by Multimodal Large Language Models (MLLMs) to improve the performance of VideoQA models. Our approach consists of three phases: reasoning generation, reasoning refinement, and learning from reasoning. First, we generate detailed reasoning processes using additional MLLMs, and second refine them via a filtering step to ensure data quality. Finally, we use the reasoning data, which might be in an imperfect form, to guide the VideoQA model via multi-task learning, on how to interpret and answer questions based on a given video. We evaluate ReasVQA on three popular benchmarks, and our results establish new state-of-the-art performance with significant improvements of +2.9 on NExT-QA, +7.3 on STAR, and +5.9 on IntentQA. Our findings demonstrate the supervising benefits of integrating reasoning processes into VideoQA. Further studies validate each component of our method, also with different backbones and MLLMs, and again highlight the advantages of this simple but effective method. We offer a new perspective on enhancing VideoQA performance by utilizing advanced reasoning techniques, setting a new benchmark in this research field. 

**Abstract (ZH)**: 视频问答（Video Question Answering, VideoQA）是一项具有挑战性的任务，要求理解视频中的复杂视觉和时间关系以准确回答问题。在本工作中，我们提出了一种新的方法 \textbf{ReasVQA}（增强推理的视频问答），该方法利用多模态大型语言模型（MLLMs）生成的推理过程来提高VideoQA模型的性能。我们的方法分为三个阶段：推理生成、推理优化以及从推理中学习。首先，我们使用额外的MLLM生成详细的推理过程，然后通过筛选步骤进一步优化推理以确保数据质量。最后，我们利用这些可能不完美的推理数据通过多任务学习来指导VideoQA模型，使其如何根据给定的视频理解和回答问题。我们使用ReasVQA在三个流行的基准测试上进行评估，实验结果表明，其在NExT-QA、STAR和IntentQA三个基准上的表现均显著优于现有方法，分别提高了2.9%、7.3%和5.9%。我们的研究结果证实了在VideoQA中整合推理过程的监督优势。进一步的研究验证了我们方法中每个组件的优势，并在不同的骨干网络和MLLM下再次突显了此方法的简单而有效的优点。我们提出了一种新的视角，即通过利用先进的推理技术来增强VideoQA性能，并为该研究领域设立了新的基准。 

---
# DQ-Data2vec: Decoupling Quantization for Multilingual Speech Recognition 

**Title (ZH)**: DQ-Data2vec：多语种语音识别中的去耦量化 

**Authors**: Qijie Shao, Linhao Dong, Kun Wei, Sining Sun, Lei Xie  

**Link**: [PDF](https://arxiv.org/pdf/2501.13497)  

**Abstract**: Data2vec is a self-supervised learning (SSL) approach that employs a teacher-student architecture for contextual representation learning via masked prediction, demonstrating remarkable performance in monolingual ASR. Previous studies have revealed that data2vec's shallow layers capture speaker and language information, middle layers encode phoneme and word features, while deep layers are responsible for reconstruction. Language and phoneme features are crucial for multilingual ASR. However, data2vec's masked representation generation relies on multi-layer averaging, inevitably coupling these features. To address this limitation, we propose a decoupling quantization based data2vec (DQ-Data2vec) for multilingual ASR, which includes a data2vec backbone and two improved online K-means quantizers. Our core idea is using the K-means quantizer with specified cluster numbers to decouple language and phoneme information for masked prediction. Specifically, in the language quantization, considering that the number of languages is significantly different from other irrelevant features (e.g., speakers), we assign the cluster number to match the number of languages, explicitly decoupling shallow layers' language-related information from irrelevant features. This strategy is also applied to decoupling middle layers' phoneme and word features. In a self-supervised scenario, experiments on the CommonVoice dataset demonstrate that DQ-Data2vec achieves a relative reduction of 9.51% in phoneme error rate (PER) and 11.58% in word error rate (WER) compared to data2vec and UniData2vec. Moreover, in a weakly-supervised scenario incorporating language labels and high-resource language text labels, the relative reduction is 18.09% and 1.55%, respectively. 

**Abstract (ZH)**: Data2vec 是一种自监督学习（SSL）方法，采用教师-学生架构通过遮蔽预测进行上下文表示学习，在单语声学隐写分析（Automatic Speech Recognition, ASR）中表现出色。先前的研究表明，Data2vec 的浅层捕捉说话人和语言信息，中层编码音素和词特征，而深层负责重建。语言和音素特征对于多语言 ASR 至关重要。然而，Data2vec 的遮蔽表示生成依赖于多层平均，不可避免地将这些特征相互耦合。为了解决这一局限性，我们提出了基于解耦量化的数据2vec（DQ-Data2vec），其包含一个数据2vec 主干和两个改进的在线 K-means 量化器。我们的核心思想是使用具有指定聚类数的 K-means 量化器，以解耦语言信息和遮蔽预测中的音素信息。具体而言，在语言量化中，由于语言的数量与其他无关特征（例如说话人）有显著差异，我们为语言分配聚类数以匹配语言数量，从而明确地从无关特征中解耦浅层的相关语言信息。这一策略同样应用于解耦中层的音素和词特征。在自监督场景中，使用 CommonVoice 数据集的实验表明，相比于数据2vec 和 UniData2vec，DQ-Data2vec 在音素错误率（PER）和词错误率（WER）上分别实现了 9.51% 和 11.58% 的相对降低。在结合语言标签和高资源语言文本标签的弱监督场景中，相对降低分别达到了 18.09% 和 1.55%。 

---
# MambaQuant: Quantizing the Mamba Family with Variance Aligned Rotation Methods 

**Title (ZH)**: MambaQuant：基于方差对齐旋转方法的Mamba家族量化方法 

**Authors**: Zukang Xu, Yuxuan Yue, Xing Hu, Zhihang Yuan, Zixu Jiang, Zhixuan Chen, Jiangyong Yu, Chen Xu, Sifan Zhou, Dawei Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13484)  

**Abstract**: Mamba is an efficient sequence model that rivals Transformers and demonstrates significant potential as a foundational architecture for various tasks. Quantization is commonly used in neural networks to reduce model size and computational latency. However, applying quantization to Mamba remains underexplored, and existing quantization methods, which have been effective for CNN and Transformer models, appear inadequate for Mamba models (e.g., Quarot suffers a 21% accuracy drop on Vim-T$^\dagger$ even under W8A8). We have pioneered the exploration of this issue and identified several key challenges. First, significant outliers are present in gate projections, output projections, and matrix multiplications. Second, Mamba's unique parallel scan further amplifies these outliers, leading to uneven and heavy-tailed data distributions. Third, even with the application of the Hadamard transform, the variance across channels in weights and activations still remains inconsistent. To these ends, we propose MambaQuant, a post-training quantization (PTQ) framework consisting of: 1) Karhunen-Loeve Transformation (KLT) enhanced rotation, rendering the rotation matrix adaptable to diverse channel distributions. 2) Smooth-Fused rotation, which equalizes channel variances and can merge additional parameters into model weights. Experiments show that MambaQuant can quantize both weights and activations into 8-bit with less than 1% accuracy loss for Mamba-based vision and language tasks. To the best of our knowledge, MambaQuant is the first comprehensive PTQ design for the Mamba family, paving the way for further advancements in its application. 

**Abstract (ZH)**: 马amba 是一种高效序列模型，能够在性能上与 Transformer 相抗衡，并且展现出了作为各种任务基础架构的显著潜力。量化通常被用于神经网络中，以减小模型大小和降低计算延迟。然而，对于 Mamba 模型进行量化的研究仍然相对较少，且现有的量化方法（比如 Quarot 在 Vim-T$\dagger$ 上的表现甚至出现了 21% 的准确率下降）对于 Mamba 模型似乎并不足够有效。我们率先探索了这一问题，并发现了几个关键挑战。首先，马amba 模型的门控投影、输出投影和矩阵乘法中存在显著的异常值。其次，马amba 模型独有的并行扫描进一步放大了这些异常值，导致了数据分布的不均匀和重尾分布。第三，即使应用了 Hadamard 变换，权重和激活值在通道上的方差仍然不一致。为了解决这些问题，我们提出了马amba量化（MambaQuant）框架，该框架包括以下两部分：1）Karhunen-Loeve 变换（KLT）增强的旋转，使旋转矩阵能够适应多种通道分布；2）平滑融合旋转，可均衡通道方差，并能将额外参数合并到模型权重中。实验结果表明，MambaQuant 可以在 Mamba 基础的视觉和语言任务中将权重和激活量化为 8 位，且准确率损失不超过 1%。据我们所知，MambaQuant 是第一个全面的马amba量化设计，为马amba模型的应用进一步发展铺平了道路。 

---
# AgentRec: Agent Recommendation Using Sentence Embeddings Aligned to Human Feedback 

**Title (ZH)**: AgentRec: 基于与人类反馈对齐的句子嵌入的智能体推荐 

**Authors**: Joshua Park, Yongfeng Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.13333)  

**Abstract**: Multi-agent systems must decide which agent is the most appropriate for a given task. We propose a novel architecture for recommending which LLM agent out of many should perform a task given a natural language prompt by extending the Sentence-BERT (SBERT) encoder model. On test data, we are able to achieve a top-1 accuracy of 92.2% with each classification taking less than 300 milliseconds. In contrast to traditional classification methods, our architecture is computationally cheap, adaptive to new classes, interpretable, and controllable with arbitrary metrics through reinforcement learning. By encoding natural language prompts into sentence embeddings, our model captures the semantic content relevant to recommending an agent. The distance between sentence embeddings that belong to the same agent is then minimized through fine-tuning and aligned to human values through reinforcement learning from human feedback. This allows the classification of natural language prompts based on their nearest neighbors by measuring the cosine similarity between embeddings. This work is made possible through the generation of a synthetic dataset for agent recommendation, which we have open-sourced to the public along with the code for AgentRec recommendation system at this https URL. 

**Abstract (ZH)**: 多智能体系统需要决定哪个智能体最适合执行给定任务。我们提出了一个新颖的架构，通过扩展Sentence-BERT（SBERT）编码器模型，来推荐在多个语言模型智能体中应当由哪个智能体执行给定自然语言提示的任务。在测试数据上，我们能够达到92.2%的一级准确率，同时每次分类的时间小于300毫秒。与传统的分类方法相比，我们的架构计算成本低，能够适应新的类别，具有解释性和通过强化学习任意度量控制的能力。通过将自然语言提示编码为句子嵌入，我们的模型捕获了与推荐智能体相关的语义内容。然后，通过微调使相同智能体的句子嵌入之间的距离最小化，并通过从人类反馈进行的强化学习将这些嵌入与人类价值观对齐。这种方法使得可以通过计算嵌入之间余弦相似度来基于最近邻对自然语言提示进行分类。本工作得益于我们生成的用于智能体推荐的合成数据集，我们已经将此数据集公开，并在以下网址开源了AgentRec推荐系统的代码：[请插入网址]。 

---
# Toyteller: AI-powered Visual Storytelling Through Toy-Playing with Character Symbols 

**Title (ZH)**: Toyteller：通过角色符号玩偶讲述的AI驱动视觉叙事 

**Authors**: John Joon Young Chung, Melissa Roemmele, Max Kreminski  

**Link**: [PDF](https://arxiv.org/pdf/2501.13284)  

**Abstract**: We introduce Toyteller, an AI-powered storytelling system where users generate a mix of story text and visuals by directly manipulating character symbols like they are toy-playing. Anthropomorphized symbol motions can convey rich and nuanced social interactions; Toyteller leverages these motions (1) to let users steer story text generation and (2) as a visual output format that accompanies story text. We enabled motion-steered text generation and text-steered motion generation by mapping motions and text onto a shared semantic space so that large language models and motion generation models can use it as a translational layer. Technical evaluations showed that Toyteller outperforms a competitive baseline, GPT-4o. Our user study identified that toy-playing helps express intentions difficult to verbalize. However, only motions could not express all user intentions, suggesting combining it with other modalities like language. We discuss the design space of toy-playing interactions and implications for technical HCI research on human-AI interaction. 

**Abstract (ZH)**: 我们介绍了Toyteller，这是一个基于AI的故事讲述系统，用户可以通过直接操作像玩具一样的人性化符号来生成混合故事文本和视觉内容。这些人性化的符号运动可以传达丰富而细腻的社会互动；Toyteller 利用了这些运动（1）让用户能够引导故事文本的生成，以及（2）作为伴随故事文本的视觉输出格式。我们通过将运动和文本映射到共享语义空间中，使得大规模语言模型和运动生成模型可以将其用作翻译层，从而实现了运动驱动的文本生成和文本驱动的运动生成。技术评估结果显示，Toyteller 的表现优于竞品基线GPT-4o。我们的用户研究指出，玩具玩耍有助于表达难以用言语表达的意图。然而，仅通过运动无法完全表达用户的全部意图，这表明运动需要与其他模态，如语言相结合。我们讨论了玩具玩耍交互的设计空间以及其对人类-AI互动的技术人机交互（HCI）研究的含义。 

---