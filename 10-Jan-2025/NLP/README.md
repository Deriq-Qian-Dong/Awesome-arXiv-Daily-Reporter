# A survey of textual cyber abuse detection using cutting-edge language models and large language models 

**Title (ZH)**: 使用尖端语言模型和大型语言模型的文本网络欺凌检测综述 

**Authors**: Jose A. Diaz-Garcia, Joao Paulo Carvalho  

**Link**: [PDF](https://arxiv.org/pdf/2501.05443)  

**Abstract**: The success of social media platforms has facilitated the emergence of various forms of online abuse within digital communities. This abuse manifests in multiple ways, including hate speech, cyberbullying, emotional abuse, grooming, and sexting. In this paper, we present a comprehensive analysis of the different forms of abuse prevalent in social media, with a particular focus on how emerging technologies, such as Language Models (LMs) and Large Language Models (LLMs), are reshaping both the detection and generation of abusive content within these networks. We delve into the mechanisms through which social media abuse is perpetuated, exploring the psychological and social impact. Additionally, we examine the dual role of advanced language models-highlighting their potential to enhance automated detection systems for abusive behavior while also acknowledging their capacity to generate harmful content. This paper aims to contribute to the ongoing discourse on online safety and ethics, offering insights into the evolving landscape of cyberabuse and the technological innovations that both mitigate and exacerbate it. 

**Abstract (ZH)**: 社交媒体平台的成功促进了数字社区中各种形式在线虐待的出现。这种虐待以多种形式表现出来，包括 hateful 话语、网络暴力、情感虐待、诱骗和裸聊。在本文中，我们对社交媒体中存在的不同形式的虐待进行了全面分析，并特别关注新兴技术如语言模型（LMs）和大规模语言模型（LLMs）如何重塑这些网络中虐待内容的检测与生成。我们探讨了社交媒体虐待行为传播的机制，分析了其心理和社会影响。此外，我们还考察了高级语言模型的双重角色——既强调它们可以增强自动化检测系统以识别有害行为，同时也承认它们有生成有害内容的能力。本文旨在为有关在线安全和伦理的持续讨论做出贡献，提供有关网络虐待演变景观及技术进步对这种演变影响的见解。 

---
# LongProc: Benchmarking Long-Context Language Models on Long Procedural Generation 

**Title (ZH)**: 长文摘: 长上下文语言模型在长程序生成任务上的基准测试 

**Authors**: Xi Ye, Fangcong Yin, Yinghui He, Joie Zhang, Howard Yen, Tianyu Gao, Greg Durrett, Danqi Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.05414)  

**Abstract**: Existing benchmarks for evaluating long-context language models (LCLMs) primarily focus on long-context recall, requiring models to produce short responses based on a few critical snippets while processing thousands of irrelevant tokens. We introduce LongProc (Long Procedural Generation), a new benchmark that requires both the integration of highly dispersed information and long-form generation. LongProc consists of six diverse procedural generation tasks, such as extracting structured information from HTML pages into a TSV format and executing complex search procedures to create travel plans. These tasks challenge LCLMs by testing their ability to follow detailed procedural instructions, synthesize and reason over dispersed information, and generate structured, long-form outputs (up to 8K tokens). Furthermore, as these tasks adhere to deterministic procedures and yield structured outputs, they enable reliable rule-based evaluation. We evaluate 17 LCLMs on LongProc across three difficulty levels, with maximum numbers of output tokens set at 500, 2K, and 8K. Notably, while all tested models claim a context window size above 32K tokens, open-weight models typically falter on 2K-token tasks, and closed-source models like GPT-4o show significant degradation on 8K-token tasks. Further analysis reveals that LCLMs struggle to maintain long-range coherence in long-form generations. These findings highlight critical limitations in current LCLMs and suggest substantial room for improvement. Data and code available at: this https URL 

**Abstract (ZH)**: 现有用于评估长上下文语言模型（LCLMs）的标准基准主要侧重于长上下文召回率，要求模型在处理数千个无关的标记时，基于几个关键片段生成简短的响应。我们引入了LongProc（长过程生成）这一新的基准，要求模型不仅能够整合高度分散的信息，还能生成长篇形式的内容。LongProc 包括六个多样化的过程生成任务，例如从 HTML 页面中提取结构化信息并转换为 TSV 格式，以及执行复杂的搜索程序以创建旅行计划。这些任务通过测试LCLMs随细节过程指令进行操作的能力、综合和推理分散信息的能力，并生成结构化且长格式的输出（最多 8K 个标记），挑战了LCLMs。此外，由于这些任务遵循确定性过程并产生结构化输出，因此它们能够进行可靠的经验法则评估。我们按照三个难度级别对17种LCLMs进行了LongProc评估，输出标记的最大数量分别为500、2K和8K。值得注意的是，尽管所有测试模型声称上下文窗口大小超过32K标记，但开源模型通常在2K标记任务上表现不佳，而像GPT-4o这样的封闭源代码模型在8K标记任务上的表现显著下降。进一步分析显示，LCLMs在长篇生成中难以保持长程连贯性。这些发现突显了当前LCLMs存在的关键限制，并建议有很大的改进空间。数据和代码可在以下链接获取：this https URL 

---
# FairCode: Evaluating Social Bias of LLMs in Code Generation 

**Title (ZH)**: FairCode: 评估代码生成中大型语言模型的社会偏见 

**Authors**: Yongkang Du, Jen-tse Huang, Jieyu Zhao, Lu Lin  

**Link**: [PDF](https://arxiv.org/pdf/2501.05396)  

**Abstract**: Large language models (LLMs) have demonstrated significant capability in code generation, drawing increasing attention to the evaluation of the quality and safety of their outputs. However, research on bias in code generation remains limited. Existing studies typically assess bias by applying malicious prompts or reapply tasks and dataset for discriminative models. Given that LLMs are often aligned with human values and that prior datasets are not fully optimized for code-related tasks, there is a pressing need for benchmarks specifically designed for evaluating code models. In this study, we introduce FairCode, a novel benchmark for evaluating bias in code generation. FairCode comprises two tasks: function implementation and test case generation, each evaluating social bias through diverse scenarios. Additionally, we propose a new metric, FairScore, to assess model performance on this benchmark. We conduct experiments on widely used LLMs and provide a comprehensive analysis of the results. The findings reveal that all tested LLMs exhibit bias. The code is available at this https URL. 

**Abstract (ZH)**: 大型语言模型（LLMs）在代码生成方面展现了显著的能力，这引起了对其输出质量和安全性的评估越来越多的关注。然而，关于代码生成中的偏见研究仍然有限。现有研究通常通过应用恶意提示或将任务和数据集重新用于辨别模型来评估偏见。鉴于LLMs往往与人类价值观对齐，且先前的数据集在代码相关任务上尚未完全优化，迫切需要专门设计的基准来评估代码模型。在本研究中，我们介绍了FairCode，这是一种用于评估代码生成中偏见的新基准。FairCode 包含两个任务：函数实现和测试用例生成，每个任务通过不同的场景来评估社会偏见。此外，我们提出了一种新的评估指标FairScore，用于评估模型在该基准上的表现。我们在广泛使用的LLMs上进行了实验，并对结果进行了全面分析。研究发现所有测试的LLMs都表现出偏见。代码可在以下链接获取：this https URL。 

---
# Stream Aligner: Efficient Sentence-Level Alignment via Distribution Induction 

**Title (ZH)**: 流动对齐器：通过分布诱导实现高效的句级对齐 

**Authors**: Hantao Lou, Jiaming Ji, Kaile Wang, Yaodong Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05336)  

**Abstract**: The rapid advancement of large language models (LLMs) has led to significant improvements in their capabilities, but also to increased concerns about their alignment with human values and intentions. Current alignment strategies, including adaptive training and inference-time methods, have demonstrated potential in this area. However, these approaches still struggle to balance deployment complexity and capability across various tasks and difficulties. In this work, we introduce the Streaming Distribution Induce Aligner (Stream Aligner), a novel alignment paradigm that combines efficiency with enhanced performance in various tasks throughout the generation process. Stream Aligner achieves dynamic sentence-level correction by using a small model to learn the preferences of the suffix sentence, iteratively correcting the suffix sentence output by the upstream model, and then using the corrected sentence to replace the suffix sentence in subsequent generations. Compared to Aligner, our experiments demonstrate that Stream Aligner reduces reliance on the capabilities of additional models, enhances the reasoning abilities of LLMs, and decreases latency during user interaction. Specifically, Stream Aligner-2B model has achieved an improvement of 76.1% in helpfulness, 36.0% in harmlessness on the tested Llama2-70B-chat model, and Stream Aligner-8B has achieved an improvement of 3.5% on the math ability of the tested Llama3-70B-Instruct model. 

**Abstract (ZH)**: 大型语言模型（LLMs）的迅速发展在其能力上带来了显著提升，但也引发了对其与人类价值观和意图一致性方面的担忧。当前的对齐策略，包括适应性训练和推理时的方法，已经在这一领域显示出潜力。然而，这些方法仍然难以在各种任务和难度下平衡部署复杂性和模型能力。在此项工作中，我们提出了流式分布诱导对齐器（Stream Aligner），这是一种新颖的对齐范式，能够通过生成过程中的效率与性能提升相结合的方式实现动态的句子级别修正。Stream Aligner 通过使用一个小模型学习后缀句子的偏好，并迭代地对上游模型生成的后缀句子输出进行修正，然后使用修正后的句子替换后续生成中的后缀句子，从而实现动态的句子级别修正。与原来的 Aligner 相比，我们的实验结果显示，Stream Aligner 在减少对额外模型能力的依赖、增强 LLM 的推理能力以及降低用户交互延迟方面表现出色。具体而言，Stream Aligner-2B 模型在测试的 Llama2-70B-chat 模型上，帮助性方面提升了 76.1%，有害性方面降低了 36.0%；而 Stream Aligner-8B 模型在测试的 Llama3-70B-Instruct 模型的数学能力上提升了 3.5%。 

---
# Enhancing Plagiarism Detection in Marathi with a Weighted Ensemble of TF-IDF and BERT Embeddings for Low-Resource Language Processing 

**Title (ZH)**: 使用加权集成的TF-IDF和BERT嵌入提高马拉地语的抄袭检测能力：面向低资源语言处理 

**Authors**: Atharva Mutsaddi, Aditya Choudhary  

**Link**: [PDF](https://arxiv.org/pdf/2501.05260)  

**Abstract**: Plagiarism involves using another person's work or concepts without proper attribution, presenting them as original creations. With the growing amount of data communicated in regional languages such as Marathi -- one of India's regional languages -- it is crucial to design robust plagiarism detection systems tailored for low-resource languages. Language models like Bidirectional Encoder Representations from Transformers (BERT) have demonstrated exceptional capability in text representation and feature extraction, making them essential tools for semantic analysis and plagiarism detection. However, the application of BERT for low-resource languages remains under-explored, particularly in the context of plagiarism detection. This paper presents a method to enhance the accuracy of plagiarism detection for Marathi texts using BERT sentence embeddings in conjunction with Term Frequency-Inverse Document Frequency (TF-IDF) feature representation. This approach effectively captures statistical, semantic, and syntactic aspects of text features through a weighted voting ensemble of machine learning models. 

**Abstract (ZH)**: 抄袭涉及未经授权使用他人作品或概念，并将其呈现为原创创作。随着越来越多的数据用区域语言（如印度的一种区域语言马哈拉施特拉语）进行通信，设计针对低资源语言的 robust 抄袭检测系统变得至关重要。类似于 Bidirectional Encoder Representations from Transformers（BERT）的语言模型在文本表示和特征提取方面展示了出色的能力，使其成为语义分析和抄袭检测的重要工具。然而，BERT在低资源语言中的应用仍处于探索阶段，尤其是在抄袭检测方面的应用尤为不足。本文提出了一种方法，通过结合 BERT 句子嵌入与词频-逆文档频（TF-IDF）特征表示，以提高马哈拉施特拉语文本抄袭检测的准确性。该方法通过加权投票集成机器学习模型，有效捕捉了文本特征的统计、语义和句法方面。 

---
# Optimizing Estonian TV Subtitles with Semi-supervised Learning and LLMs 

**Title (ZH)**: 使用半监督学习和大规模语言模型优化爱沙尼亚电视字幕 

**Authors**: Artem Fedorchenko, Tanel Alumäe  

**Link**: [PDF](https://arxiv.org/pdf/2501.05234)  

**Abstract**: This paper presents an approach for generating high-quality, same-language subtitles for Estonian TV content. We fine-tune the Whisper model on human-generated Estonian subtitles and enhance it with iterative pseudo-labeling and large language model (LLM) based post-editing. Our experiments demonstrate notable subtitle quality improvement through pseudo-labeling with an unlabeled dataset. We find that applying LLM-based editing at test time enhances subtitle accuracy, while its use during training does not yield further gains. This approach holds promise for creating subtitle quality close to human standard and could be extended to real-time applications. 

**Abstract (ZH)**: 本文提出了一个生成高质量同语言 Estonia 电视内容字幕的方法。我们通过微调 Whisper 模型，并结合迭代伪标签和基于大语言模型（LLM）的后编辑，提升了字幕质量。实验结果显示，在未标注数据集上应用伪标签可显著提高字幕质量。我们发现，在测试时应用基于大语言模型的编辑可以提升字幕的准确性，而在训练期间使用则不会带来额外的改进。此方法有可能生成接近人类标准的高质量字幕，并有望扩展至实时应用。 

---
# Leveraging Large Language Models for Zero-shot Lay Summarisation in Biomedicine and Beyond 

**Title (ZH)**: 利用大型语言模型实现生物医药及更领域中的零样本概要提取 

**Authors**: Tomas Goldsack, Carolina Scarton, Chenghua Lin  

**Link**: [PDF](https://arxiv.org/pdf/2501.05224)  

**Abstract**: In this work, we explore the application of Large Language Models to zero-shot Lay Summarisation. We propose a novel two-stage framework for Lay Summarisation based on real-life processes, and find that summaries generated with this method are increasingly preferred by human judges for larger models. To help establish best practices for employing LLMs in zero-shot settings, we also assess the ability of LLMs as judges, finding that they are able to replicate the preferences of human judges. Finally, we take the initial steps towards Lay Summarisation for Natural Language Processing (NLP) articles, finding that LLMs are able to generalise to this new domain, and further highlighting the greater utility of summaries generated by our proposed approach via an in-depth human evaluation. 

**Abstract (ZH)**: 在本研究中，我们探讨了大型语言模型在零样本摘要（零样本Lay摘要）中的应用。我们提出了一个基于现实生活过程的两阶段框架，并发现使用这种方法生成的摘要随着模型规模的增大越来越受到人类评委的青睐。为了帮助建立在零样本设置中利用LLM的最佳实践，我们还评估了LLM作为评委的能力，发现它们能够复制人类评委的偏好。最后，我们向NLP文章的零样本摘要迈出了初步的步骤，发现LLM能够泛化到这一新领域，并通过深入的人类评价进一步突显了我们提出的方法生成的摘要具有更大的实用价值。 

---
# ParaRev: Building a dataset for Scientific Paragraph Revision annotated with revision instruction 

**Title (ZH)**: ParaRev：一个基于修订指令标注的科学段落修订数据集构建方法 

**Authors**: Léane Jourdan, Nicolas Hernandez, Richard Dufour, Florian Boudin, Akiko Aizawa  

**Link**: [PDF](https://arxiv.org/pdf/2501.05222)  

**Abstract**: Revision is a crucial step in scientific writing, where authors refine their work to improve clarity, structure, and academic quality. Existing approaches to automated writing assistance often focus on sentence-level revisions, which fail to capture the broader context needed for effective modification. In this paper, we explore the impact of shifting from sentence-level to paragraph-level scope for the task of scientific text revision. The paragraph level definition of the task allows for more meaningful changes, and is guided by detailed revision instructions rather than general ones. To support this task, we introduce ParaRev, the first dataset of revised scientific paragraphs with an evaluation subset manually annotated with revision instructions. Our experiments demonstrate that using detailed instructions significantly improves the quality of automated revisions compared to general approaches, no matter the model or the metric considered. 

**Abstract (ZH)**: 修订是科学写作中的一个关键步骤，作者通过这一过程精炼和完善其作品，以提高清晰度、结构和学术水平。现有的自动写作辅助方法大多集中在句子级别的修订上，这往往无法捕捉到有效修改所需的广泛语境。在本文中，我们探讨了将任务从句子级别转向段落级别的影响，对于科学文本的修订任务而言，段落级别的定义能够带来更有意义的变化，并且这些变化是根据详细的修订指南而非一般的指南来进行的。为了支持这一任务，我们引入了ParaRev数据集，这是首个包含修订说明的手动标注修订的科学段落数据集。我们的实验表明，使用详细的修订指南相比一般方法显著提高了自动修订的质量，无论采用哪种模型或评估指标。 

---
# GLaM-Sign: Greek Language Multimodal Lip Reading with Integrated Sign Language Accessibility 

**Title (ZH)**: GLaM-Sign: 带有整合的手语 Accessibility 的希腊语多模态唇读 

**Authors**: Dimitris Kouremenos, Klimis Ntalianis  

**Link**: [PDF](https://arxiv.org/pdf/2501.05213)  

**Abstract**: The Greek Language Multimodal Lip Reading with Integrated Sign Language Accessibility (GLaM-Sign) [1] is a groundbreaking resource in accessibility and multimodal AI, designed to support Deaf and Hard-of-Hearing (DHH) individuals. Developed from the FEELIT project [2], it integrates high-resolution audio, video, textual transcriptions, and Greek Sign Language translations for applications like real-time sign language translation and enhanced subtitle synchronization. While its primary focus is on promoting inclusivity in the Greek tourism sector, its adaptability extends to education, healthcare, and public services. Future advancements will enhance word-level precision and scalability to additional languages, supported by advanced AI methodologies and collaborations with diverse stakeholders. This dataset underscores the transformative potential of multimodal resources in bridging communication gaps, fostering innovation, and setting a benchmark for ethical AI and inclusive technologies. 

**Abstract (ZH)**: 《希腊语言多模态唇读与集成手语访问性(GLaM-Sign)》[1] 是无障碍技术和多模态人工智能领域的开创性资源，旨在支持聋人和听力障碍者（DHH）群体。该项目源自于FEELIT项目[2]，整合了高分辨率音频、视频、文本转录以及希腊手语翻译，适用于实时手语翻译和增强字幕同步等多种应用。尽管其主要集中在促进希腊旅游行业的包容性，但其灵活性还可扩展到教育、医疗保健和公共服务领域。未来的发展将进一步提高单词级别的精确度，并扩展至其他语言，通过先进的AI方法和与多元利益相关方的合作来实现。该数据集展示了多模态资源在弥合沟通障碍、促进创新和为伦理AI与包容性技术设定标杆方面的潜在影响。 

---
# Biomedical Relation Extraction via Adaptive Document-Relation Cross-Mapping and Concept Unique Identifier 

**Title (ZH)**: 通过自适应文档-关系交叉映射和概念唯一标识符进行生物医学关系提取 

**Authors**: Yufei Shang, Yanrong Guo, Shijie Hao, Richang Hong  

**Link**: [PDF](https://arxiv.org/pdf/2501.05155)  

**Abstract**: Document-Level Biomedical Relation Extraction (Bio-RE) aims to identify relations between biomedical entities within extensive texts, serving as a crucial subfield of biomedical text mining. Existing Bio-RE methods struggle with cross-sentence inference, which is essential for capturing relations spanning multiple sentences. Moreover, previous methods often overlook the incompleteness of documents and lack the integration of external knowledge, limiting contextual richness. Besides, the scarcity of annotated data further hampers model training. Recent advancements in large language models (LLMs) have inspired us to explore all the above issues for document-level Bio-RE. Specifically, we propose a document-level Bio-RE framework via LLM Adaptive Document-Relation Cross-Mapping (ADRCM) Fine-Tuning and Concept Unique Identifier (CUI) Retrieval-Augmented Generation (RAG). First, we introduce the Iteration-of-REsummary (IoRs) prompt for solving the data scarcity issue. In this way, Bio-RE task-specific synthetic data can be generated by guiding ChatGPT to focus on entity relations and iteratively refining synthetic data. Next, we propose ADRCM fine-tuning, a novel fine-tuning recipe that establishes mappings across different documents and relations, enhancing the model's contextual understanding and cross-sentence inference capabilities. Finally, during the inference, a biomedical-specific RAG approach, named CUI RAG, is designed to leverage CUIs as indexes for entities, narrowing the retrieval scope and enriching the relevant document contexts. Experiments conducted on three Bio-RE datasets (GDA, CDR, and BioRED) demonstrate the state-of-the-art performance of our proposed method by comparing it with other related works. 

**Abstract (ZH)**: 生物医学文档级关系提取（Bio-RE）旨在识别文本中生物医学实体之间的关系，是生物医学文本挖掘中的关键子领域。现有Bio-RE方法在句间推理方面存在困难，句间关系的捕获至关重要。此外，先前的方法往往忽略了文档的不完整性，缺乏外部知识的整合，限制了上下文的丰富性。此外，标注数据稀缺进一步阻碍了模型的训练。近期在大规模语言模型（LLMs）方面的进展启发我们探索这些问题以改进文档级Bio-RE方法。具体而言，我们提出了一种通过LLMs自适应文档-关系跨映射（ADRCM）微调和概念唯一标识符（CUI）检索增强生成（RAG）的文档级Bio-RE框架。首先，我们介绍了Iterative Relation Extraction Summary（IoRs）提示，以解决数据稀缺问题。通过这种方式，可以引导ChatGPT关注实体关系并迭代优化合成数据，生成任务特定的合成数据。接着，我们提出了ADRCM微调，这是一种新颖的微调方法，能够建立不同文档和关系之间的映射，增强模型的上下文理解和句间推理能力。最后，在推理过程中，我们设计了一种特定于生物医学的RAG方法——CUI RAG，利用CUI作为实体的索引，缩小检索范围并丰富相关文档上下文。在GDA、CDR和BioRED三个Bio-RE数据集上的实验表明，我们的方法在与其他相关工作的比较中表现出最先进的性能。 

---
# Centurio: On Drivers of Multilingual Ability of Large Vision-Language Model 

**Title (ZH)**: Centurio：大型视觉-语言模型的多语言能力驱动因素探究 

**Authors**: Gregor Geigle, Florian Schneider, Carolin Holtermann, Chris Biemann, Radu Timofte, Anne Lauscher, Goran Glavaš  

**Link**: [PDF](https://arxiv.org/pdf/2501.05122)  

**Abstract**: Most Large Vision-Language Models (LVLMs) to date are trained predominantly on English data, which makes them struggle to understand non-English input and fail to generate output in the desired target language. Existing efforts mitigate these issues by adding multilingual training data, but do so in a largely ad-hoc manner, lacking insight into how different training mixes tip the scale for different groups of languages. In this work, we present a comprehensive investigation into the training strategies for massively multilingual LVLMs. First, we conduct a series of multi-stage experiments spanning 13 downstream vision-language tasks and 43 languages, systematically examining: (1) the number of training languages that can be included without degrading English performance and (2) optimal language distributions of pre-training as well as (3) instruction-tuning data. Further, we (4) investigate how to improve multilingual text-in-image understanding, and introduce a new benchmark for the task. Surprisingly, our analysis reveals that one can (i) include as many as 100 training languages simultaneously (ii) with as little as 25-50\% of non-English data, to greatly improve multilingual performance while retaining strong English performance. We further find that (iii) including non-English OCR data in pre-training and instruction-tuning is paramount for improving multilingual text-in-image understanding. Finally, we put all our findings together and train Centurio, a 100-language LVLM, offering state-of-the-art performance in an evaluation covering 14 tasks and 56 languages. 

**Abstract (ZH)**: 迄今为止，大多数大型视觉-语言模型（Large Vision-Language Models, LVLMs）主要在英语数据上进行训练，这使得它们在理解非英语输入和生成目标语言输出方面存在问题。现有的努力通过增加多语言训练数据来缓解这些问题，但在很大程度上是随意进行的，缺乏对不同训练混合如何影响不同语言群体的表现的深入理解。在本工作中，我们对大规模多语言LVLM的训练策略进行了全面调查。首先，我们进行了跨越13个下游视觉-语言任务和43种语言的多阶段实验，系统地探讨了：（1）不损害英语性能的情况下可以包含的训练语言数量；（2）预训练和（3）指令调优数据的最佳语言分布。此外，我们（4）探讨如何提高多语言文本-图像理解能力，并引入了该任务的新基准。令人惊讶的是，我们的分析显示，可以同时（i）包含多达100种训练语言（ii）仅使用25-50%的非英语数据，从而大幅提高多语言性能，同时保留良好的英语性能。我们还发现，（iii）在预训练和指令调优中包含非英语OCR数据对于提高多语言文本-图像理解至关重要。最后，我们将所有这些发现结合起来，训练了一个包含100种语言的Centurio模型，在涵盖14个任务和56种语言的评估中表现出最先进的性能。 

---
# SWE-Fixer: Training Open-Source LLMs for Effective and Efficient GitHub Issue Resolution 

**Title (ZH)**: SWE-Fixer: 训练开源大语言模型以实现高效有效的 GitHub 问题解决 

**Authors**: Chengxing Xie, Bowen Li, Chang Gao, He Du, Wai Lam, Difan Zou, Kai Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.05040)  

**Abstract**: Large Language Models (LLMs) have demonstrated remarkable proficiency across a variety of complex tasks. One significant application of LLMs is in tackling software engineering challenges, particularly in resolving real-world tasks on GitHub by fixing code based on the issues reported by the users. However, many current approaches rely on proprietary LLMs, which limits reproducibility, accessibility, and transparency. The critical components of LLMs for addressing software engineering issues and how their capabilities can be effectively enhanced remain unclear. To address these challenges, we introduce SWE-Fixer, a novel open-source LLM designed to effectively and efficiently resolve GitHub issues. SWE-Fixer comprises two essential modules: a code file retrieval module and a code editing module. The retrieval module employs BM25 along with a lightweight LLM model to achieve coarse-to-fine file retrieval. Subsequently, the code editing module utilizes the other LLM model to generate patches for the identified files. Then, to mitigate the lack of publicly available datasets, we compile an extensive dataset that includes 110K GitHub issues along with their corresponding patches, and train the two modules of SWE-Fixer separately. We assess our approach on the SWE-Bench Lite and Verified benchmarks, achieving state-of-the-art performance among open-source models with scores of 23.3% and 30.2%, respectively. These outcomes highlight the efficacy of our approach. We will make our model, dataset, and code publicly available at this https URL. 

**Abstract (ZH)**: 大型语言模型（LLMs）在多种复杂任务中展示了卓越的表现。LLMs的一个重要应用领域是解决软件工程挑战，特别是在通过修复代码来解决GitHub上用户报告的问题时。然而，目前许多方法依赖于专有LLMs，这限制了可再现性、可访问性和透明度。LLMs解决软件工程问题的关键组件及其能力如何有效提升尚不明确。为了解决这些挑战，我们提出了一种新型开源LLM——SWE-Fixer，它旨在有效且高效地解决GitHub问题。SWE-Fixer包含两个核心模块：代码文件检索模块和代码编辑模块。检索模块利用BM25与轻量级LLM模型结合，实现粗到细的文件检索。随后，代码编辑模块利用另一LLM模型生成识别文件的补丁代码。此外，为了解决缺乏公开数据集的问题，我们编制了一个包含110,000个GitHub问题及其对应补丁的大型数据集，并分别训练了SWE-Fixer的两个模块。我们在SWE-Bench Lite和Verified基准上评估了我们的方法，分别取得了开源模型中的最佳性能，得分为23.3%和30.2%。这些结果凸显了我们方法的有效性。我们将模型、数据集和代码公开发布在[这里](http://this.url/)。 

---
# Enhancing Human-Like Responses in Large Language Models 

**Title (ZH)**: 增强大型语言模型的人类响应能力 

**Authors**: Ethem Yağız Çalık, Talha Rüzgar Akkuş  

**Link**: [PDF](https://arxiv.org/pdf/2501.05032)  

**Abstract**: This paper explores the advancements in making large language models (LLMs) more human-like. We focus on techniques that enhance natural language understanding, conversational coherence, and emotional intelligence in AI systems. The study evaluates various approaches, including fine-tuning with diverse datasets, incorporating psychological principles, and designing models that better mimic human reasoning patterns. Our findings demonstrate that these enhancements not only improve user interactions but also open new possibilities for AI applications across different domains. Future work will address the ethical implications and potential biases introduced by these human-like attributes. 

**Abstract (ZH)**: 本文探讨了使大型语言模型（LLMs）更加人化的进步。我们重点关注能够增强人工智能系统自然语言理解、对话连贯性和情绪智能的技术。研究评估了各种方法，包括使用多样化的数据集进行微调、纳入心理学原理以及设计更符合人类推理模式的模型。研究发现，这些增强不仅改善了用户体验，还为不同领域的AI应用开辟了新的可能性。未来的研究将关注这些接近人类特性的伦理问题及其潜在的偏差。 

---
# TreeKV: Smooth Key-Value Cache Compression with Tree Structures 

**Title (ZH)**: TreeKV：基于树结构的平滑键值缓存压缩 

**Authors**: Ziwei He, Jian Yuan, Haoli Bai, Jingwen Leng, Bo Jiang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04987)  

**Abstract**: Efficient key-value (KV) cache compression is critical for scaling transformer-based Large Language Models (LLMs) in long sequences and resource-limited settings. Existing methods evict tokens based on their positions or importance scores, but position-based strategies can miss crucial information outside predefined regions, while those relying on global importance scores resulting in strong regional biases, limiting the KV cache's overall context retention and potentially impairing the performance of LLMs on complex tasks. Our wavelet analysis reveals that as tokens approach the end of sequence, their contributions to generation gradually increase and tends to diverge more from neighboring tokens, indicating a smooth transition with increasing complexity and variability from distant to nearby context. Motivated by this observation, we propose TreeKV, an intuitive, training-free method that employs a tree structure for smooth cache compression. TreeKV maintains a fixed cache size, allowing LLMs to deliver high-quality output even in long text scenarios. Unlike most compression methods, TreeKV is applicable to both the generation and prefilling stages. It consistently surpasses all baseline models in language modeling tasks on PG19 and OpenWebText2, allowing LLMs trained with short context window to generalize to longer window with a 16x cache reduction. On the Longbench benchmark, TreeKV achieves the best performance with only 6\% of the budget at optimal efficiency. 

**Abstract (ZH)**: 高效的键值（KV）缓存压缩对于扩展基于变压器的大型语言模型（LLMs）在长序列和资源受限环境下的性能至关重要。现有方法根据位置或重要性评分来移除令牌，但基于位置的策略可能会错过预定义区域之外的关键信息，而依赖全局重要性评分的方法则会导致强烈的区域偏差，限制了KV缓存的整体上下文保留能力，并可能损害LLMs在复杂任务上的性能。我们通过小波分析发现，随着令牌接近序列末尾，它们对生成的贡献逐渐增加，并且与邻近令牌的偏差越来越大，表明从远处到近处的上下文具有逐步增加的复杂性和变异性。受到这一观察的启发，我们提出了一种名为TreeKV的直观、无需训练的方法，利用树结构进行平滑缓存压缩。TreeKV保持固定大小的缓存，使得LLMs即使在长文本场景下也能提供高质量的输出。与大多数压缩方法不同，TreeKV既适用于生成阶段也适用于预填充阶段。在PG19和OpenWebText2上的语言建模任务中，TreeKV始终超越所有基线模型，并通过减少16倍的缓存大小使得使用短上下文窗口训练的LLMs能够泛化到长上下文窗口。在Longbench基准测试中，TreeKV在最优效率下仅使用6%的预算实现了最佳性能。 

---
# SensorQA: A Question Answering Benchmark for Daily-Life Monitoring 

**Title (ZH)**: SensorQA：日常生活监控领域的问答基准ẑ
user
一种用于非接触式心率监测的新型机器学习方法 

**Authors**: Benjamin Reichman, Xiaofan Yu, Lanxiang Hu, Jack Truxal, Atishay Jain, Rushil Chandrupatla, Tajana Šimunić Rosing, Larry Heck  

**Link**: [PDF](https://arxiv.org/pdf/2501.04974)  

**Abstract**: With the rapid growth in sensor data, effectively interpreting and interfacing with these data in a human-understandable way has become crucial. While existing research primarily focuses on learning classification models, fewer studies have explored how end users can actively extract useful insights from sensor data, often hindered by the lack of a proper dataset. To address this gap, we introduce \Dataset, the first human-created question-answering (QA) dataset for long-term time-series sensor data for daily life monitoring. \Dataset is created by human workers and includes 5.6K diverse and practical queries that reflect genuine human interests, paired with accurate answers derived from sensor data. We further establish benchmarks for state-of-the-art AI models on this dataset and evaluate their performance on typical edge devices. Our results reveal a gap between current models and optimal QA performance and efficiency, highlighting the need for new contributions. The dataset and code are available at: \url{this https URL}. 

**Abstract (ZH)**: 随着传感器数据的迅速增长，有效地以人类可理解的方式解释和接口处理这些数据变得至关重要。尽管现有的研究主要集中在学习分类模型上，但很少有研究探讨终端用户如何积极地从传感器数据中提取有用洞察，这往往受到缺乏适当数据集的限制。为了解决这一问题，我们介绍了\Dataset，这是首个专为日常生活中长期时间序列传感器数据设计的人工创建的问答（QA）数据集。\Dataset由人类工作者创建，包含了5600多个多样且实用的查询，这些查询反映了真实的人类兴趣，并配以从传感器数据中得出的准确答案。我们进一步为最先进的AI模型在该数据集上建立了基准，并评估了它们在典型边缘设备上的性能。我们的结果显示了现有模型与最佳问答性能和效率之间的差距，突显了需要新的贡献。数据集和代码可在: \url{此处请填写实际的URL} 获得。 

---
# VoxEval: Benchmarking the Knowledge Understanding Capabilities of End-to-End Spoken Language Models 

**Title (ZH)**: VoxEval: 评估端到端口语语言模型的知识理解能力 

**Authors**: Wenqian Cui, Xiaoqi Jiao, Ziqiao Meng, Irwin King  

**Link**: [PDF](https://arxiv.org/pdf/2501.04962)  

**Abstract**: With the growing demand for developing speech-based interaction models, end-to-end Spoken Language Models (SLMs) have emerged as a promising solution. When engaging in conversations with humans, it is essential for these models to comprehend a wide range of world knowledge. In this paper, we introduce VoxEval, a novel speech question-answering benchmark specifically designed to assess SLMs' knowledge understanding through purely speech-based interactions. Unlike existing AudioQA benchmarks, VoxEval maintains speech format for both questions and answers, evaluates model robustness across diverse audio conditions (varying timbres, audio qualities, and speaking styles), and pioneers the assessment of challenging domains like mathematical problem-solving in spoken format. Our comprehensive evaluation of recent SLMs using VoxEval reveals significant performance limitations in current models, highlighting crucial areas for future improvements. 

**Abstract (ZH)**: 随着对基于语音的交互模型需求的增长，端到端语音语言模型（SLMs）已经成为了极具前景的解决方案。当这些模型与人类进行对话时，理解广泛的世界知识至关重要。本文介绍了一种名为VoxEval的新颖语音问答基准，专门设计用于通过纯语音交互评估SLMs的知识理解能力。与现有的音频问答基准不同，VoxEval保持了语音格式的问题和答案，并评估模型在各种音频条件（包括不同音色、音频质量和口音）下的鲁棒性，并首次通过语音形式评估了数学问题解决等具有挑战性的领域。通过使用VoxEval对近期的SLMs进行综合评估，我们揭示了当前模型中存在显著的性能限制，突显了未来需要改进的关键领域。 

---
# Demystifying Domain-adaptive Post-training for Financial LLMs 

**Title (ZH)**: 揭开面向金融大语言模型的后训练 domain-adaptive 后训练之谜 

**Authors**: Zixuan Ke, Yifei Ming, Xuan-Phi Nguyen, Caiming Xiong, Shafiq Joty  

**Link**: [PDF](https://arxiv.org/pdf/2501.04961)  

**Abstract**: Domain-adaptive post-training of large language models (LLMs) has emerged as a promising approach for specialized domains such as medicine and finance. However, significant challenges remain in identifying optimal adaptation criteria and training strategies across varying data and model configurations. To address these challenges, we introduce FINDAP, a systematic and fine-grained investigation into domain-adaptive post-training of LLMs for the finance domain. Our approach begins by identifying the core capabilities required for the target domain and designing a comprehensive evaluation suite aligned with these needs. We then analyze the effectiveness of key post-training stages, including continual pretraining, instruction tuning, and preference alignment. Building on these insights, we propose an effective training recipe centered on a novel preference data distillation method, which leverages process signals from a generative reward model. The resulting model, Llama-Fin, achieves state-of-the-art performance across a wide range of financial tasks. Our analysis also highlights how each post-training stage contributes to distinct capabilities, uncovering specific challenges and effective solutions, providing valuable insights for domain adaptation of LLMs. Project page: this https URL 

**Abstract (ZH)**: 面向特定领域的大型语言模型（LLMs）的域适应后训练已经成为了医学和金融等专业领域的有前途的方法。然而，在不同数据和模型配置下确定最优适应标准和训练策略仍然面临重大挑战。为应对这些挑战，我们提出了 FINDAP 方法，这是一种系统而细致的针对金融领域的大型语言模型域适应后训练的调查研究。我们的方法首先确定目标领域所需的核心能力，并设计一个与这些需求相一致的全面评估套件。然后，我们分析关键后训练阶段的有效性，包括持续预训练、指令调优和偏好对齐。基于这些洞察，我们提出了一种以新颖的偏好数据蒸馏方法为中心的有效训练配方，该方法利用生成奖励模型的进程信号。由此得出的模型 Llama-Fin 在多种金融任务上实现了最先进的性能。我们的分析还强调了每个后训练阶段如何贡献不同能力，揭示了特定挑战及有效解决方案，为大型语言模型的领域适应提供了宝贵见解。项目页面：[这里](this https URL) 

---
# Step-by-Step Mastery: Enhancing Soft Constraint Following Ability of Large Language Models 

**Title (ZH)**: 逐步掌握：提高大型语言模型遵守软约束的能力 

**Authors**: Qingyu Ren, Jie Zeng, Qianyu He, Jiaqing Liang, Yanghua Xiao, Weikang Zhou, Zeye Sun, Fei Yu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04945)  

**Abstract**: It is crucial for large language models (LLMs) to follow instructions that involve multiple constraints. However, soft constraints are semantically related and difficult to verify through automated methods. These constraints remain a significant challenge for LLMs. To enhance the ability of LLMs to follow soft constraints, we initially design a pipeline to obtain high-quality outputs automatically. Additionally, to fully utilize the acquired data, we introduce a training paradigm based on curriculum learning. We experimentally evaluate the effectiveness of our methods in improving LLMs' soft constraint following ability and analyze the factors driving the improvements. The datasets and code are publicly available at this https URL. 

**Abstract (ZH)**: 对于大型语言模型（LLMs）而言，遵循涉及多重约束的指令至关重要。然而，软约束是语义相关的，难以通过自动化方法验证，这些约束仍然是LLMs面临的一个重大挑战。为了增强LLMs遵循软约束的能力，我们首先设计了一个管道以自动获取高质量的输出。此外，为了充分利用获取的数据，我们引入了一种基于渐进学习的训练范式。我们实证评估了我们的方法在提高LLMs遵循软约束能力方面的有效性，并分析了推动这些改进的因素。相关数据集和代码已在以下网址公开：this https URL。 

---
# Investigating Numerical Translation with Large Language Models 

**Title (ZH)**: 使用大型语言模型探究数值翻译 

**Authors**: Wei Tang, Jiawei Yu, Yuang Li, Yanqing Zhao, Weidong Zhang, Wei Feng, Min Zhang, Hao Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04927)  

**Abstract**: The inaccurate translation of numbers can lead to significant security issues, ranging from financial setbacks to medical inaccuracies. While large language models (LLMs) have made significant advancements in machine translation, their capacity for translating numbers has not been thoroughly explored. This study focuses on evaluating the reliability of LLM-based machine translation systems when handling numerical data. In order to systematically test the numerical translation capabilities of currently open source LLMs, we have constructed a numerical translation dataset between Chinese and English based on real business data, encompassing ten types of numerical translation. Experiments on the dataset indicate that errors in numerical translation are a common issue, with most open-source LLMs faltering when faced with our test scenarios. Especially when it comes to numerical types involving large units like ``million", ``billion", and "yi", even the latest llama3.1 8b model can have error rates as high as 20%. Finally, we introduce three potential strategies to mitigate the numerical mistranslations for large units. 

**Abstract (ZH)**: 不准确的数字翻译可能导致严重的安全问题，从财务损失到医疗错误不一而足。虽然大型语言模型（LLMs）在机器翻译方面取得了显著进展，但它们处理数字的能力尚未得到充分研究。本研究重点评估基于LLM的机器翻译系统在处理数值数据时的可靠性。为了系统地测试当前开源LLM的数字翻译能力，我们基于实际业务数据构建了一个中英文数字翻译数据集，涵盖了十种类型的数字翻译。实验表明，数字翻译中的错误是一个常见问题，大多数开源LLM在面对我们的测试场景时表现不佳。特别是在处理“百万”、“亿”等大单位类型的数字时，即使是最新的llama3.1 8b模型，错误率也可能高达20%。最后，我们介绍了三种潜在策略，以减轻大单位数字翻译中的误解问题。 

---
# JELLY: Joint Emotion Recognition and Context Reasoning with LLMs for Conversational Speech Synthesis 

**Title (ZH)**: JELLY：结合LLM的情感识别与情境推理在对话语音合成中的应用 

**Authors**: Jun-Hyeok Cha, Seung-Bin Kim, Hyung-Seok Oh, Seong-Whan Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.04904)  

**Abstract**: Recently, there has been a growing demand for conversational speech synthesis (CSS) that generates more natural speech by considering the conversational context. To address this, we introduce JELLY, a novel CSS framework that integrates emotion recognition and context reasoning for generating appropriate speech in conversation by fine-tuning a large language model (LLM) with multiple partial LoRA modules. We propose an Emotion-aware Q-former encoder, which enables the LLM to perceive emotions in speech. The encoder is trained to align speech emotions with text, utilizing datasets of emotional speech. The entire model is then fine-tuned with conversational speech data to infer emotional context for generating emotionally appropriate speech in conversation. Our experimental results demonstrate that JELLY excels in emotional context modeling, synthesizing speech that naturally aligns with conversation, while mitigating the scarcity of emotional conversational speech datasets. 

**Abstract (ZH)**: 近年来，随着对对话式语音合成（CSS）需求的增长，这种合成技术越来越注重在考虑对话上下文的情况下生成更为自然的语音。为解决这一问题，我们引入了JELLY——一种新型CSS框架，该框架通过结合情感识别和上下文推理来引导模型生成适当的对话语音，同时对大型语言模型（LLM）进行了微调，使用了多个部分LoRA模块。我们提出了一种情感感知的QFormer编码器，该编码器使LLM能够感知语音中的情感。该编码器经过训练，能够使语音情感与文本情感对齐，并利用了情感语音数据集。整个模型随后通过对话语音数据进行了微调，以推断情感上下文并生成情感恰当的对话语音。实验结果表明，JELLY在情感上下文建模方面表现出色，能合成与对话自然对齐的语音，并缓解了情感对话语音数据集稀缺的问题。 

---
# SUGAR: Leveraging Contextual Confidence for Smarter Retrieval 

**Title (ZH)**: SUGAR：利用上下文置信度进行更智能的检索 

**Authors**: Hanna Zubkova, Ji-Hoon Park, Seong-Whan Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.04899)  

**Abstract**: Bearing in mind the limited parametric knowledge of Large Language Models (LLMs), retrieval-augmented generation (RAG) which supplies them with the relevant external knowledge has served as an approach to mitigate the issue of hallucinations to a certain extent. However, uniformly retrieving supporting context makes response generation source-inefficient, as triggering the retriever is not always necessary, or even inaccurate, when a model gets distracted by noisy retrieved content and produces an unhelpful answer. Motivated by these issues, we introduce Semantic Uncertainty Guided Adaptive Retrieval (SUGAR), where we leverage context-based entropy to actively decide whether to retrieve and to further determine between single-step and multi-step retrieval. Our empirical results show that selective retrieval guided by semantic uncertainty estimation improves the performance across diverse question answering tasks, as well as achieves a more efficient inference. 

**Abstract (ZH)**: 考虑到大型语言模型（LLMs）的参数知识有限，通过检索增强生成（RAG）方法，为它们提供相关外部知识，已经在一定程度上缓解了幻觉问题。然而，均匀检索支持上下文使得响应生成缺乏效率，因为当模型受到噪声检索内容的干扰并产生无用的答案时，触发检索器并不总是必要的，甚至可能是不准确的。为了解决这些问题，我们提出了语义不确定性引导自适应检索（SUGAR），在此方法中，我们利用上下文熵来主动决定是否进行检索，并进一步确定是进行单步检索还是多步检索。我们的实验证明，基于语义不确定性估计的选择性检索提高了各种问答任务的性能，并实现了更加高效的推理。 

---
# Leveraging Log Probabilities in Language Models to Forecast Future Events 

**Title (ZH)**: 利用语言模型中的对数概率预测未来事件 

**Authors**: Tommaso Soru, Jim Marshall  

**Link**: [PDF](https://arxiv.org/pdf/2501.04880)  

**Abstract**: In the constantly changing field of data-driven decision making, accurately predicting future events is crucial for strategic planning in various sectors. The emergence of Large Language Models (LLMs) marks a significant advancement in this area, offering advanced tools that utilise extensive text data for prediction. In this industry paper, we introduce a novel method for AI-driven foresight using LLMs. Building on top of previous research, we employ data on current trends and their trajectories for generating forecasts on 15 different topics. Subsequently, we estimate their probabilities via a multi-step approach based on log probabilities. We show we achieve a Brier score of 0.186, meaning a +26% improvement over random chance and a +19% improvement over widely-available AI systems. 

**Abstract (ZH)**: 在不断变化的数据驱动决策领域，准确预测未来事件对于各行业的战略规划至关重要。大型语言模型（LLMs）的出现标志着这一领域的显著进步，为利用大量文本数据进行预测提供了先进的工具。在本文中，我们介绍了一种基于LLMs的新型人工智能驱动 foresight 方法。在前人研究的基础上，我们利用当前趋势及其轨迹数据，对15个不同主题进行预测。随后，我们通过基于对数概率的多步方法估计这些预测的概率。结果显示，我们的方法实现了0.186的Brier分数，这意味着相比随机猜测，改善了26%，相比广泛可用的AI系统，改善了19%。 

---
# Real-Time Textless Dialogue Generation 

**Title (ZH)**: 实时无文本对话生成 

**Authors**: Long Mai, Julie Carson-Berndsen  

**Link**: [PDF](https://arxiv.org/pdf/2501.04877)  

**Abstract**: Recent advancements in large language models (LLMs) have led to significant progress in text-based dialogue systems. These systems can now generate high-quality responses that are accurate and coherent across a wide range of topics and tasks. However, spoken dialogue systems still lag behind in terms of naturalness. They tend to produce robotic interactions, with issues such as slow response times, overly generic or cautious replies, and a lack of natural rhythm and fluid turn-taking. This shortcoming is largely due to the over-reliance on the traditional cascaded design, which involve separate, sequential components, as well as the use of text as an intermediate representation. This paper propose a real-time, textless spoken dialogue generation model (RTTL-DG) that aims to overcome these challenges. Our system enables fluid turn-taking and generates responses with minimal delay by processing streaming spoken conversation directly. Additionally, our model incorporates backchannels, filters, laughter, and other paralinguistic signals, which are often absent in cascaded dialogue systems, to create more natural and human-like interactions. The implementations and generated samples are available in our repository: this https URL 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的发展极大地推动了基于文本的对话系统的进步。这些系统现在能够生成高质量、准确且连贯的响应，适用于广泛的主题和任务。然而，对于口头对话系统而言，自然度方面仍存在不足。它们往往生成较为机械化、刻板的交互，表现为响应延迟时间长、回复过于泛泛或谨慎、以及缺乏自然的节奏和流畅的对话轮换。这些不足主要是由于过度依赖传统的级联设计所导致，这种设计包括一个个相互独立且顺序执行的组件，以及文本作为中间表示形式的使用。本文提出了一种实时、无文本的口头对话生成模型（RTTL-DG），旨在克服这些挑战。我们的系统通过直接处理实时口头对话流来实现流畅的对话轮换，并且能够以极小的延迟生成回应。此外，我们的模型整合了回话、过滤器、笑声以及其他非言语信号，这些元素在传统的级联对话系统中通常缺失，从而创造出更加自然和类人的交互体验。我们的实施代码和生成样例可以在我们的仓库中获取：[这里](this https URL) 

---
# Advancing Retrieval-Augmented Generation for Persian: Development of Language Models, Comprehensive Benchmarks, and Best Practices for Optimization 

**Title (ZH)**: 提高波斯语检索增强生成的能力：语言模型的发展、全面基准测试及优化最佳实践 

**Authors**: Sara Bourbour Hosseinbeigi, Sina Asghari, Mohammad Ali Seif Kashani, Mohammad Hossein Shalchian, Mohammad Amin Abbasi  

**Link**: [PDF](https://arxiv.org/pdf/2501.04858)  

**Abstract**: This paper examines the specific obstacles of constructing Retrieval-Augmented Generation(RAG) systems in low-resource languages, with a focus on Persian's complicated morphology and versatile syntax. The research aims to improve retrieval and generation accuracy by introducing Persian-specific models, namely MatinaRoberta(a masked language model) and MatinaSRoberta(a fine-tuned Sentence-BERT), along with a comprehensive benchmarking framework. Three datasets-general knowledge(PQuad), scientifically specialized texts, and organizational reports, were used to assess these models after they were trained on a varied corpus of 73.11 billion Persian tokens. The methodology involved extensive pretraining, fine-tuning with tailored loss functions, and systematic evaluations using both traditional metrics and the Retrieval-Augmented Generation Assessment framework. The results show that MatinaSRoberta outperformed previous embeddings, achieving superior contextual relevance and retrieval accuracy across datasets. Temperature tweaking, chunk size modifications, and document summary indexing were explored to enhance RAG setups. Larger models like Llama-3.1 (70B) consistently demonstrated the highest generation accuracy, while smaller models faced challenges with domain-specific and formal contexts. The findings underscore the potential for developing RAG systems in Persian through customized embeddings and retrieval-generation settings and highlight the enhancement of NLP applications such as search engines and legal document analysis in low-resource languages. 

**Abstract (ZH)**: 本文探讨了在低资源语言中构建检索增强生成（RAG）系统的特定障碍，着重于波斯语复杂形态和多变的句法结构。研究旨在通过引入波斯语特定模型——MatinaRoberta（一种掩码语言模型）和MatinaSRoberta（微调后的Sentence-BERT）以及一个全面的基准测试框架来提高检索和生成的准确性。经过731.1亿个波斯语令牌组成的多样化语料库训练后，使用了三个数据集：通用知识数据集（PQuad）、科学专著和组织报告，以评估这些模型。研究方法包括广泛的预训练、针对特定损失函数的微调以及使用传统度量和RAG评估框架进行系统的评估。结果显示，MatinaSRoberta超过了先前的嵌入，实现了跨数据集的更高语境相关性和检索准确率。通过调整温度、分块大小和文档摘要索引来增强RAG设置进行了探索。较大的模型如Llama-3.1（70B）在生成准确性方面表现最佳，而较小的模型在领域特定和正式语言环境中面临挑战。研究结果强调了通过定制嵌入和检索生成设置开发波斯语RAG系统的潜力，并突显了在低资源语言中增强自然语言处理（NLP）应用，如搜索引擎和法律文件分析的可能性。 

---
# Building Foundations for Natural Language Processing of Historical Turkish: Resources and Models 

**Title (ZH)**: 古代土耳其语自然语言处理的基础构建：资源与模型 

**Authors**: Şaziye Betül Özateş, Tarık Emre Tıraş, Ece Elif Adak, Berat Doğan, Fatih Burak Karagöz, Efe Eren Genç, Esma F. Bilgin Taşdemir  

**Link**: [PDF](https://arxiv.org/pdf/2501.04828)  

**Abstract**: This paper introduces foundational resources and models for natural language processing (NLP) of historical Turkish, a domain that has remained underexplored in computational linguistics. We present the first named entity recognition (NER) dataset, HisTR and the first Universal Dependencies treebank, OTA-BOUN for a historical form of the Turkish language along with transformer-based models trained using these datasets for named entity recognition, dependency parsing, and part-of-speech tagging tasks. Additionally, we introduce Ottoman Text Corpus (OTC), a clean corpus of transliterated historical Turkish texts that spans a wide range of historical periods. Our experimental results show significant improvements in the computational analysis of historical Turkish, achieving promising results in tasks that require understanding of historical linguistic structures. They also highlight existing challenges, such as domain adaptation and language variations across time periods. All of the presented resources and models are made available at this https URL to serve as a benchmark for future progress in historical Turkish NLP. 

**Abstract (ZH)**: 本文介绍了用于历史土耳其语自然语言处理（NLP）的基础资源和模型。尽管在计算语言学领域对历史土耳其语的研究尚不足，但这是一个亟待探索的领域。我们首次提出了一个人名实体识别（NER）数据集HisTR，并首次为历史土耳其语形式构建了一个通用依存树库OTA-BOUN。此外，我们使用这些数据集训练了基于转换器的模型，用于人名实体识别、依存句法解析和词性标注任务。本文还介绍了《奥斯曼文本语料库》（OTC），这是一个洁净的历史土耳其语转写文本语料库，覆盖了多个历史时期。实验结果表明，在历史土耳其语的计算分析中取得了显著进步，特别是在需要理解历史语言结构的任务中取得了令人鼓舞的结果。同时，本文也指出了现有的一些挑战，如领域适应和跨时期语言变化问题。所有展示的资源和模型均在以下链接发布：https://example.com，以作为未来历史土耳其语NLP进展的参考基准。 

---
# Unifying the Extremes: Developing a Unified Model for Detecting and Predicting Extremist Traits and Radicalization 

**Title (ZH)**: 统一两端：开发一个统一模型以检测和预测极端主义特征与激进化 

**Authors**: Allison Lahnala, Vasudha Varadarajan, Lucie Flek, H. Andrew Schwartz, Ryan L. Boyd  

**Link**: [PDF](https://arxiv.org/pdf/2501.04820)  

**Abstract**: The proliferation of ideological movements into extremist factions via social media has become a global concern. While radicalization has been studied extensively within the context of specific ideologies, our ability to accurately characterize extremism in more generalizable terms remains underdeveloped. In this paper, we propose a novel method for extracting and analyzing extremist discourse across a range of online community forums. By focusing on verbal behavioral signatures of extremist traits, we develop a framework for quantifying extremism at both user and community levels. Our research identifies 11 distinct factors, which we term ``The Extremist Eleven,'' as a generalized psychosocial model of extremism. Applying our method to various online communities, we demonstrate an ability to characterize ideologically diverse communities across the 11 extremist traits. We demonstrate the power of this method by analyzing user histories from members of the incel community. We find that our framework accurately predicts which users join the incel community up to 10 months before their actual entry with an AUC of $>0.6$, steadily increasing to AUC ~0.9 three to four months before the event. Further, we find that upon entry into an extremist forum, the users tend to maintain their level of extremism within the community, while still remaining distinguishable from the general online discourse. Our findings contribute to the study of extremism by introducing a more holistic, cross-ideological approach that transcends traditional, trait-specific models. 

**Abstract (ZH)**: 社交媒体上意识形态运动向极端派别蔓延已成为全球关注的问题。尽管极端主义在特定意识形态的背景下得到了广泛研究，但对其在更通用术语中的准确描述方法仍然不够成熟。本文提出了一种新颖的方法，用于提取和分析跨多种在线社区论坛的极端主义言论。通过专注于极端主义特质的言语行为特征，我们开发了一个框架，用于在用户和社区层面量化极端主义程度。我们的研究识别出了11个不同的因素，我们将其称为“极端主义十一因素”，并将其作为极端主义的一般心理社会模型。将该方法应用于各种在线社区，我们展示了能够利用这11个极端主义特质来标识具有不同意识形态的社区。通过对“ Obtainer”（incel）社区成员历史记录的分析，我们展示了此方法的强大功能；结果表明，在用户实际加入incel社区前10个月，我们的框架能够预测出70%以上（AUC >0.6）的用户，且在事件前三到四个月时AUC值接近0.9。此外，我们发现，在进入极端主义论坛后，用户在社区中的极端程度通常保持稳定，但仍可与一般网络言论区分开来。我们的研究结果通过引入一种更具包容性和跨意识形态的研究方法，为极端主义研究做出了贡献，这种方法超越了传统的单一特征模型。 

---
# Cued Speech Generation Leveraging a Pre-trained Audiovisual Text-to-Speech Model 

**Title (ZH)**: 利用预训练的音视频文本转语音模型生成指式手语 

**Authors**: Sanjana Sankar, Martin Lenglet, Gerard Bailly, Denis Beautemps, Thomas Hueber  

**Link**: [PDF](https://arxiv.org/pdf/2501.04799)  

**Abstract**: This paper presents a novel approach for the automatic generation of Cued Speech (ACSG), a visual communication system used by people with hearing impairment to better elicit the spoken language. We explore transfer learning strategies by leveraging a pre-trained audiovisual autoregressive text-to-speech model (AVTacotron2). This model is reprogrammed to infer Cued Speech (CS) hand and lip movements from text input. Experiments are conducted on two publicly available datasets, including one recorded specifically for this study. Performance is assessed using an automatic CS recognition system. With a decoding accuracy at the phonetic level reaching approximately 77%, the results demonstrate the effectiveness of our approach. 

**Abstract (ZH)**: 本文提出了一种新颖的方法，用于自动生成视觉手势编码语言（Cued Speech，CS），这是一种专为听力受损人士设计的视觉交流系统，旨在更好地诱发口语表达。我们通过利用预训练的音频-视觉自回归文本转语音模型（AVTacotron2）探索迁移学习策略。该模型被重新编程，以从文本输入中推断出Cued Speech的手部和唇部动作。我们在两个公开可用的数据集上进行了实验，其中包括一个为本研究专门录制的数据集。性能评估使用了自动Cued Speech识别系统。结果显示，在音素层面的解码准确率达到约77%，证明了该方法的有效性。 

---
# ReFocus: Visual Editing as a Chain of Thought for Structured Image Understanding 

**Title (ZH)**: ReFocus: 视觉编辑作为结构化图像理解的思维链 

**Authors**: Xingyu Fu, Minqian Liu, Zhengyuan Yang, John Corring, Yijuan Lu, Jianwei Yang, Dan Roth, Dinei Florencio, Cha Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05452)  

**Abstract**: Structured image understanding, such as interpreting tables and charts, requires strategically refocusing across various structures and texts within an image, forming a reasoning sequence to arrive at the final answer. However, current multimodal large language models (LLMs) lack this multihop selective attention capability. In this work, we introduce ReFocus, a simple yet effective framework that equips multimodal LLMs with the ability to generate "visual thoughts" by performing visual editing on the input image through code, shifting and refining their visual focuses. Specifically, ReFocus enables multimodal LLMs to generate Python codes to call tools and modify the input image, sequentially drawing boxes, highlighting sections, and masking out areas, thereby enhancing the visual reasoning process. We experiment upon a wide range of structured image understanding tasks involving tables and charts. ReFocus largely improves performance on all tasks over GPT-4o without visual editing, yielding an average gain of 11.0% on table tasks and 6.8% on chart tasks. We present an in-depth analysis of the effects of different visual edits, and reasons why ReFocus can improve the performance without introducing additional information. Further, we collect a 14k training set using ReFocus, and prove that such visual chain-of-thought with intermediate information offers a better supervision than standard VQA data, reaching a 8.0% average gain over the same model trained with QA pairs and 2.6% over CoT. 

**Abstract (ZH)**: 结构化图像理解，例如解释表格和图表，需要在一个图像中战略性地重新聚焦于各种结构和文本，形成推理序列以得出最终答案。然而，当前的多模态大型语言模型（LLMs）缺乏这种多跳选择性注意力的能力。在本研究中，我们提出了ReFocus，这是一种简单而有效的框架，通过代码对输入图像进行视觉编辑，使多模态LLMs能够生成“视觉思考”，并逐步调整和细化其视觉关注点。具体来说，ReFocus使多模态LLMs能够生成Python代码来调用工具并修改输入图像，依次绘制框、突出显示部分并遮盖区域，从而增强视觉推理过程。我们在涉及表格和图表的广泛结构化图像理解任务中进行了实验。ReFocus在无需视觉编辑的情况下显著提高了GPT-4o的表现，在表格任务中平均提高了11.0%，在图表任务中提高了6.8%。我们深入分析了不同视觉编辑的效果及其为何能够在不引入额外信息的情况下提高表现。此外，我们使用ReFocus收集了一个包含14,000个训练样本的数据集，并证明了这种包含中间信息的视觉链式思考比标准的VQA数据提供了更好的监督，模型在使用QA对和CoT训练时分别获得了8.0%和2.6%的平均性能提升。 

---
# Search-o1: Agentic Search-Enhanced Large Reasoning Models 

**Title (ZH)**: Search-o1: 代理增强的大推理模型搜索 

**Authors**: Xiaoxi Li, Guanting Dong, Jiajie Jin, Yuyao Zhang, Yujia Zhou, Yutao Zhu, Peitian Zhang, Zhicheng Dou  

**Link**: [PDF](https://arxiv.org/pdf/2501.05366)  

**Abstract**: Large reasoning models (LRMs) like OpenAI-o1 have demonstrated impressive long stepwise reasoning capabilities through large-scale reinforcement learning. However, their extended reasoning processes often suffer from knowledge insufficiency, leading to frequent uncertainties and potential errors. To address this limitation, we introduce \textbf{Search-o1}, a framework that enhances LRMs with an agentic retrieval-augmented generation (RAG) mechanism and a Reason-in-Documents module for refining retrieved documents. Search-o1 integrates an agentic search workflow into the reasoning process, enabling dynamic retrieval of external knowledge when LRMs encounter uncertain knowledge points. Additionally, due to the verbose nature of retrieved documents, we design a separate Reason-in-Documents module to deeply analyze the retrieved information before injecting it into the reasoning chain, minimizing noise and preserving coherent reasoning flow. Extensive experiments on complex reasoning tasks in science, mathematics, and coding, as well as six open-domain QA benchmarks, demonstrate the strong performance of Search-o1. This approach enhances the trustworthiness and applicability of LRMs in complex reasoning tasks, paving the way for more reliable and versatile intelligent systems. The code is available at \url{this https URL}. 

**Abstract (ZH)**: 大型推理模型（LRMs）如OpenAI-o1通过大规模强化学习展示了令人印象深刻的长步骤推理能力。然而，它们的延长推理过程往往受到知识不足的影响，导致频繁的不确定性甚至潜在错误。为了解决这一限制，我们引入了**Search-o1**，一个通过添加自主检索增强生成（RAG）机制和文档内推理模块来增强LRMs的框架。Search-o1将自主搜索工作流程整合到推理过程中，使LRMs在遇到不确定的知识点时能够动态检索外部知识。此外，由于检索到的文档通常内容丰富，我们设计了一个单独的文档内推理模块，在将这些信息注入推理链之前对其进行深入分析，从而减少噪声并保持连贯的推理流程。通过在科学、数学和编程等复杂推理任务以及六个开放领域问答基准测试中的广泛实验，证明了Search-o1的出色性能。该方法增强了LRMs在复杂推理任务中的可信度和适用性，为更可靠和多功能的智能系统铺平了道路。代码可在[此处](this https URL)获得。 

---
# CallNavi: A Study and Challenge on Function Calling Routing and Invocation in Large Language Models 

**Title (ZH)**: CallNavi：大型语言模型中函数调用路由与调用研究与挑战 

**Authors**: Yewei Song, Cedric Lothritz, Xunzhu Tang, Saad Ezzini, Jacques Klein, Tegawendé F. Bissyandé, Andrey Boytsov, Ulrick Ble, Anne Goujon  

**Link**: [PDF](https://arxiv.org/pdf/2501.05255)  

**Abstract**: Interacting with a software system via a chatbot can be challenging, especially when the chatbot needs to generate API calls, in the right order and with the right parameters, to communicate with the system. API calling in chatbot systems poses significant challenges, particularly in complex, multi-step tasks requiring accurate API selection and execution. We contribute to this domain in three ways: first, by introducing a novel dataset designed to assess models on API function selection, parameter generation, and nested API calls; second, by benchmarking state-of-the-art language models across varying levels of complexity to evaluate their performance in API function generation and parameter accuracy; and third, by proposing an enhanced API routing method that combines general-purpose large language models for API selection with fine-tuned models for parameter generation and some prompt engineering approach. These approaches lead to substantial improvements in handling complex API tasks, offering practical advancements for real-world API-driven chatbot systems. 

**Abstract (ZH)**: 通过聊天机器人与软件系统交互可能会颇具挑战，尤其是在聊天机器人需要按正确顺序生成带有正确参数的API调用来与系统通信时尤为如此。在聊天机器人系统中进行API调用提出了重大挑战，特别是在执行复杂、多步骤任务并准确选择和执行API时。我们在这三个方面为该领域做出了贡献：首先，通过引入一个新颖的数据集来评估模型在API功能选择、参数生成及嵌套API调用方面的性能；其次，对最先进的语言模型进行基准测试，以评估它们在API功能生成和参数准确性方面的表现；最后，提出了一种增强的API路由方法，该方法结合了一般用途的大规模语言模型进行API选择，并结合了精细调整的模型进行参数生成及一些提示工程技术。这些方法在处理复杂API任务方面取得了显著进步，并为实际的API驱动聊天机器人系统提供了实用的改进。 

---
# A Novel Approach to Scalable and Automatic Topic-Controlled Question Generation in Education 

**Title (ZH)**: 一种面向教育领域的新型可扩展和自动话题控制问题生成方法 

**Authors**: Ziqing Li, Mutlu Cukurova, Sahan Bulathwela  

**Link**: [PDF](https://arxiv.org/pdf/2501.05220)  

**Abstract**: The development of Automatic Question Generation (QG) models has the potential to significantly improve educational practices by reducing the teacher workload associated with creating educational content. This paper introduces a novel approach to educational question generation that controls the topical focus of questions. The proposed Topic-Controlled Question Generation (T-CQG) method enhances the relevance and effectiveness of the generated content for educational purposes. Our approach uses fine-tuning on a pre-trained T5-small model, employing specially created datasets tailored to educational needs. The research further explores the impacts of pre-training strategies, quantisation, and data augmentation on the model's performance. We specifically address the challenge of generating semantically aligned questions with paragraph-level contexts, thereby improving the topic specificity of the generated questions. In addition, we introduce and explore novel evaluation methods to assess the topical relatedness of the generated questions. Our results, validated through rigorous offline and human-backed evaluations, demonstrate that the proposed models effectively generate high-quality, topic-focused questions. These models have the potential to reduce teacher workload and support personalised tutoring systems by serving as bespoke question generators. With its relatively small number of parameters, the proposals not only advance the capabilities of question generation models for handling specific educational topics but also offer a scalable solution that reduces infrastructure costs. This scalability makes them feasible for widespread use in education without reliance on proprietary large language models like ChatGPT. 

**Abstract (ZH)**: 自动问答（QG）模型的发展有望显著提高教育实践的效果，通过减少教师创建教育内容所花费的工作量。本文介绍了一种新的教育问题生成方法，该方法控制问题的主题焦点。所提出的主题控制问题生成（T-CQG）方法增强了生成内容的相关性和有效性，以适应教育目的。我们的方法通过对预训练的T5-small模型进行微调，并使用专门为教育需求定制的数据集。研究还进一步探讨了预训练策略、量化和数据增强对模型性能的影响。我们特别解决了生成与段落级上下文语义对齐的问题，从而提高了生成问题的主题针对性。此外，我们引入并探讨了新的评估方法，以评估生成问题的主题相关性。通过严格的离线和人工验证，我们的结果表明，所提出的模型能够有效地生成高质量、主题相关的问答内容。这些模型具有减轻教师工作负荷和支持个性化辅导系统的能力，能够作为定制问题生成器使用。由于参数较少，这些提议不仅推进了特定教育主题的问答模型的能力，而且还提供了一种可扩展的解决方案，能够降低基础设施成本。这种可扩展性使得它们能够在教育中广泛应用，无需依赖像ChatGPT这样的专有大型语言模型。 

---
# Bringing Order Amidst Chaos: On the Role of Artificial Intelligence in Secure Software Engineering 

**Title (ZH)**: 在混乱中带来秩序：人工智能在软件安全工程中的作用 

**Authors**: Matteo Esposito  

**Link**: [PDF](https://arxiv.org/pdf/2501.05165)  

**Abstract**: Context. Developing secure and reliable software remains a key challenge in software engineering (SE). The ever-evolving technological landscape offers both opportunities and threats, creating a dynamic space where chaos and order compete. Secure software engineering (SSE) must continuously address vulnerabilities that endanger software systems and carry broader socio-economic risks, such as compromising critical national infrastructure and causing significant financial losses. Researchers and practitioners have explored methodologies like Static Application Security Testing Tools (SASTTs) and artificial intelligence (AI) approaches, including machine learning (ML) and large language models (LLMs), to detect and mitigate these vulnerabilities. Each method has unique strengths and limitations.
Aim. This thesis seeks to bring order to the chaos in SSE by addressing domain-specific differences that impact AI accuracy.
Methodology. The research employs a mix of empirical strategies, such as evaluating effort-aware metrics, analyzing SASTTs, conducting method-level analysis, and leveraging evidence-based techniques like systematic dataset reviews. These approaches help characterize vulnerability prediction datasets.
Results. Key findings include limitations in static analysis tools for identifying vulnerabilities, gaps in SASTT coverage of vulnerability types, weak relationships among vulnerability severity scores, improved defect prediction accuracy using just-in-time modeling, and threats posed by untouched methods.
Conclusions. This thesis highlights the complexity of SSE and the importance of contextual knowledge in improving AI-driven vulnerability and defect prediction. The comprehensive analysis advances effective prediction models, benefiting both researchers and practitioners. 

**Abstract (ZH)**: 背景. 在软件工程（SE）领域，开发安全可靠软件仍然是一个关键挑战。不断变化的技术景观既带来了机遇也带来了威胁，形成了一个动态空间，在这个空间中，混乱与秩序相互竞争。安全软件工程（SSE）必须不断应对威胁软件系统并带来更广泛的社会经济风险（如破坏关键的国家基础设施和造成重大经济损失）的漏洞。研究人员和实践者已经探索了诸如静态应用程序安全测试工具（SASTTs）和人工智能（AI）方法，包括机器学习（ML）和大型语言模型（LLMs），以检测和缓解这些漏洞。每种方法都有其独特的优缺点。

目标. 本论文旨在通过解决影响AI准确性的领域特定差异，为SSE中的混乱带来秩序。

方法. 研究采用了一种混合实验策略，包括评估意识工作量的指标、分析SASTTs、进行方法层面的分析以及利用证据基技术（如系统数据集审查）等手段。这些方法有助于表征漏洞预测数据集的特征。

结果. 关键发现包括静态分析工具在识别漏洞方面的局限性、SASTT对漏洞类型的覆盖率不足、漏洞严重性评分之间的弱相关性、无实时建模也能提高缺陷预测准确性、以及未触及的方法所带来的威胁。

结论. 本论文突显了SSE的复杂性以及提升基于AI的漏洞和缺陷预测的上下文知识的重要性。全面的分析推进了有效的预测模型，对研究人员和实践者都有益。 

---
# Comparison of Feature Learning Methods for Metadata Extraction from PDF Scholarly Documents 

**Title (ZH)**: PDF学术文档中元数据提取的特征学习方法比较 

**Authors**: Zeyd Boukhers, Cong Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05082)  

**Abstract**: The availability of metadata for scientific documents is pivotal in propelling scientific knowledge forward and for adhering to the FAIR principles (i.e. Findability, Accessibility, Interoperability, and Reusability) of research findings. However, the lack of sufficient metadata in published documents, particularly those from smaller and mid-sized publishers, hinders their accessibility. This issue is widespread in some disciplines, such as the German Social Sciences, where publications often employ diverse templates. To address this challenge, our study evaluates various feature learning and prediction methods, including natural language processing (NLP), computer vision (CV), and multimodal approaches, for extracting metadata from documents with high template variance. We aim to improve the accessibility of scientific documents and facilitate their wider use. To support our comparison of these methods, we provide comprehensive experimental results, analyzing their accuracy and efficiency in extracting metadata. Additionally, we provide valuable insights into the strengths and weaknesses of various feature learning and prediction methods, which can guide future research in this field. 

**Abstract (ZH)**: 科学文档中的元数据可用性对于推动科学知识的发展和遵守研究成果的FAIR原则（即可查找性、可访问性、互操作性和可重用性）至关重要。然而，特别是对于小型和中型出版商而言，已发表文档中元数据的不足限制了它们的可访问性。这一问题在一些学科中尤为普遍，如德国社会科学领域，其中的出版物常使用多种不同的模板。为应对这一挑战，我们的研究评估了各种特征学习和预测方法，包括自然语言处理（NLP）、计算机视觉（CV）和多模态方法，以从具有高模板变异性的文档中提取元数据。我们旨在提高科学文档的可访问性，并促进其更广泛的使用。为了支持这些方法的比较，我们提供了全面的实验结果，分析了它们在提取元数据方面的准确性和效率。此外，我们还提供了关于各种特征学习和预测方法的优势和劣势的宝贵见解，这些见解可以指导未来该领域的研究。 

---
# Jailbreaking Multimodal Large Language Models via Shuffle Inconsistency 

**Title (ZH)**: 通过混合不一致性破解多模态大型语言模型 

**Authors**: Shiji Zhao, Ranjie Duan, Fengxiang Wang, Chi Chen, Caixin Kang, Jialing Tao, YueFeng Chen, Hui Xue, Xingxing Wei  

**Link**: [PDF](https://arxiv.org/pdf/2501.04931)  

**Abstract**: Multimodal Large Language Models (MLLMs) have achieved impressive performance and have been put into practical use in commercial applications, but they still have potential safety mechanism vulnerabilities. Jailbreak attacks are red teaming methods that aim to bypass safety mechanisms and discover MLLMs' potential risks. Existing MLLMs' jailbreak methods often bypass the model's safety mechanism through complex optimization methods or carefully designed image and text prompts. Despite achieving some progress, they have a low attack success rate on commercial closed-source MLLMs. Unlike previous research, we empirically find that there exists a Shuffle Inconsistency between MLLMs' comprehension ability and safety ability for the shuffled harmful instruction. That is, from the perspective of comprehension ability, MLLMs can understand the shuffled harmful text-image instructions well. However, they can be easily bypassed by the shuffled harmful instructions from the perspective of safety ability, leading to harmful responses. Then we innovatively propose a text-image jailbreak attack named SI-Attack. Specifically, to fully utilize the Shuffle Inconsistency and overcome the shuffle randomness, we apply a query-based black-box optimization method to select the most harmful shuffled inputs based on the feedback of the toxic judge model. A series of experiments show that SI-Attack can improve the attack's performance on three benchmarks. In particular, SI-Attack can obviously improve the attack success rate for commercial MLLMs such as GPT-4o or Claude-3.5-Sonnet. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）已在商业应用中取得了显著的性能，并被实际应用，但它们仍然存在潜在的安全机制漏洞。押解攻击是红队测试方法，旨在绕过安全机制并发现MLLMs的潜在风险。现有的MLLMs押解方法通常通过复杂的优化方法或精心设计的图像和文本提示来绕过模型的安全机制。尽管取得了一些进展，但它们在商业闭源MLLMs上的攻击成功率较低。与以往研究不同，我们通过实证研究发现，MLLMs在处理乱序有害指令时存在理解和安全性之间的不一致性（Shuffle Inconsistency）。也就是说，从理解能力的角度来看，MLLMs能够很好地理解乱序有害文本-图像指令。然而，从安全性角度来看，它们却容易被乱序有害指令绕过，从而产生有害的响应。然后，我们创新地提出了一种名为SI-Attack的图文押解攻击方法。具体而言，为了充分利用这种不一致性并克服乱序的随机性，我们应用了一种基于查询的黑盒优化方法，根据有毒法官模型的反馈选择最具有害的乱序输入。一系列实验表明，SI-Attack可以提高在三个基准上的攻击性能。特别是，SI-Attack能够明显提高对如GPT-4o或Claude-3.5-Sonnet等商业MLLMs的攻击成功率。 

---
# FLowHigh: Towards Efficient and High-Quality Audio Super-Resolution with Single-Step Flow Matching 

**Title (ZH)**: FlowHigh：单步流匹配 toward 高效的高质量音频超分辨率 

**Authors**: Jun-Hak Yun, Seung-Bin Kim, Seong-Whan Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.04926)  

**Abstract**: Audio super-resolution is challenging owing to its ill-posed nature. Recently, the application of diffusion models in audio super-resolution has shown promising results in alleviating this challenge. However, diffusion-based models have limitations, primarily the necessity for numerous sampling steps, which causes significantly increased latency when synthesizing high-quality audio samples. In this paper, we propose FLowHigh, a novel approach that integrates flow matching, a highly efficient generative model, into audio super-resolution. We also explore probability paths specially tailored for audio super-resolution, which effectively capture high-resolution audio distributions, thereby enhancing reconstruction quality. The proposed method generates high-fidelity, high-resolution audio through a single-step sampling process across various input sampling rates. The experimental results on the VCTK benchmark dataset demonstrate that FLowHigh achieves state-of-the-art performance in audio super-resolution, as evaluated by log-spectral distance and ViSQOL while maintaining computational efficiency with only a single-step sampling process. 

**Abstract (ZH)**: 音频超分辨率由于其病态性质而具有挑战性。最近，扩散模型在音频超分辨率中的应用展示了缓解这一挑战的有前景的结果。然而，基于扩散的模型存在局限性，主要是需要大量的采样步骤，这在合成高质量音频样本时会导致显著增加的延迟。本文提出了一种名为FLowHigh的新方法，该方法将高效生成模型中的流匹配技术整合到音频超分辨率中。我们还探索了专门针对音频超分辨率的概率路径，这些路径有效地捕捉了高分辨率音频分布，从而提高了重建质量。该方法通过不同输入采样率下的单步采样过程生成高保真、高分辨率的音频。在VCTK基准数据集上的实验结果表明，FLowHigh在音频超分辨率方面达到了最先进的性能，依据对数谱距离和ViSQOL评估，同时仅通过单步采样过程保持了计算效率。 

---
# Enhancing Listened Speech Decoding from EEG via Parallel Phoneme Sequence Prediction 

**Title (ZH)**: 通过并行音素序列预测增强基于EEG的聆听语音解码 

**Authors**: Jihwan Lee, Tiantian Feng, Aditya Kommineni, Sudarsana Reddy Kadiri, Shrikanth Narayanan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04844)  

**Abstract**: Brain-computer interfaces (BCI) offer numerous human-centered application possibilities, particularly affecting people with neurological disorders. Text or speech decoding from brain activities is a relevant domain that could augment the quality of life for people with impaired speech perception. We propose a novel approach to enhance listened speech decoding from electroencephalography (EEG) signals by utilizing an auxiliary phoneme predictor that simultaneously decodes textual phoneme sequences. The proposed model architecture consists of three main parts: EEG module, speech module, and phoneme predictor. The EEG module learns to properly represent EEG signals into EEG embeddings. The speech module generates speech waveforms from the EEG embeddings. The phoneme predictor outputs the decoded phoneme sequences in text modality. Our proposed approach allows users to obtain decoded listened speech from EEG signals in both modalities (speech waveforms and textual phoneme sequences) simultaneously, eliminating the need for a concatenated sequential pipeline for each modality. The proposed approach also outperforms previous methods in both modalities. The source code and speech samples are publicly available. 

**Abstract (ZH)**: 脑-计算机接口（BCI）为人类中心的应用提供了多种可能性，特别是在影响神经疾病患者方面。从脑活动解码文本或言语是相关领域之一，这可以提高言语感知受损患者的日常生活质量。我们提出了一种新的方法，通过利用一个辅助音素预测器来同时解码文本音素序列，从而增强基于脑电图（EEG）信号的听说言语解码。我们提出的方法架构包括三个主要部分：EEG模块、言语模块和音素预测器。EEG模块负责将EEG信号适当地转换为EEG嵌入。言语模块从EEG嵌入生成言语波形。音素预测器输出解码的音素序列（以文本模态表示）。我们提出的方法使用户能够同时从两种模态（言语波形和文本音素序列）获得从EEG信号解码的听说言语，消除了为每个模态构建串联顺序流水线的需要。此外，我们提出的方法在两种模态上均优于之前的方法。源代码和言语样本已公开发布。 

---
# Reproducing HotFlip for Corpus Poisoning Attacks in Dense Retrieval 

**Title (ZH)**: 在密集检索中复制 HotFlip 对 corpus 毒化攻击的研究 

**Authors**: Yongkang Li, Panagiotis Eustratiadis, Evangelos Kanoulas  

**Link**: [PDF](https://arxiv.org/pdf/2501.04802)  

**Abstract**: HotFlip is a topical gradient-based word substitution method for attacking language models. Recently, this method has been further applied to attack retrieval systems by generating malicious passages that are injected into a corpus, i.e., corpus poisoning. However, HotFlip is known to be computationally inefficient, with the majority of time being spent on gradient accumulation for each query-passage pair during the adversarial token generation phase, making it impossible to generate an adequate number of adversarial passages in a reasonable amount of time. Moreover, the attack method itself assumes access to a set of user queries, a strong assumption that does not correspond to how real-world adversarial attacks are usually performed. In this paper, we first significantly boost the efficiency of HotFlip, reducing the adversarial generation process from 4 hours per document to only 15 minutes, using the same hardware. We further contribute experiments and analysis on two additional tasks: (1) transfer-based black-box attacks, and (2) query-agnostic attacks. Whenever possible, we provide comparisons between the original method and our improved version. Our experiments demonstrate that HotFlip can effectively attack a variety of dense retrievers, with an observed trend that its attack performance diminishes against more advanced and recent methods. Interestingly, we observe that while HotFlip performs poorly in a black-box setting, indicating limited capacity for generalization, in query-agnostic scenarios its performance is correlated to the volume of injected adversarial passages. 

**Abstract (ZH)**: HotFlip 是一种基于主题梯度的词替换方法，用于攻击语言模型。最近，这种方法已被进一步应用于攻击检索系统，通过生成恶意段落并将其插入到语料库中，即语料库污染。然而，HotFlip 以其计算效率低下著称，在生成对抗性标记阶段，需要对每个查询-段落对进行梯度累积，这使得在合理的时间内生成足够的对抗性段落变得不可能。此外，该攻击方法假设可以访问用户查询集，这是一个强假设，与实际的对抗攻击通常如何执行的方式不符。在本文中，我们首先大幅提高了 HotFlip 的效率，将每个文档的对抗生成过程从4小时缩短到仅15分钟，使用相同的硬件。我们还进一步在两个附加任务上进行实验和分析：(1) 基于转移的黑盒攻击，(2) 无查询的攻击。在可能的情况下，我们提供了原始方法与改进版本之间的比较。我们的实验表明，HotFlip 可以有效攻击各种密集检索器，并观察到其攻击性能随更先进和更新的方法而减弱的趋势。有趣的是，我们发现虽然在黑盒环境中 HotFlip 表现不佳，显示出有限的泛化能力，但在无查询场景中，其性能与注入的对抗性段落数量相关。 

---