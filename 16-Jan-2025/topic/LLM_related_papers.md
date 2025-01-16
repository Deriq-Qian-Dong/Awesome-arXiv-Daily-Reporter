# Learning to Extract Cross-Domain Aspects and Understanding Sentiments Using Large Language Models 

**Title (ZH)**: 使用大型语言模型学习提取跨域方面并理解情感 

**Authors**: Karukriti Kaushik Ghosh, Chiranjib Sur  

**Link**: [PDF](https://arxiv.org/pdf/2501.08974)  

**Abstract**: Aspect-based sentiment analysis (ASBA) is a refined approach to sentiment analysis that aims to extract and classify sentiments based on specific aspects or features of a product, service, or entity. Unlike traditional sentiment analysis, which assigns a general sentiment score to entire reviews or texts, ABSA focuses on breaking down the text into individual components or aspects (e.g., quality, price, service) and evaluating the sentiment towards each. This allows for a more granular level of understanding of customer opinions, enabling businesses to pinpoint specific areas of strength and improvement. The process involves several key steps, including aspect extraction, sentiment classification, and aspect-level sentiment aggregation for a review paragraph or any other form that the users have provided. ABSA has significant applications in areas such as product reviews, social media monitoring, customer feedback analysis, and market research. By leveraging techniques from natural language processing (NLP) and machine learning, ABSA facilitates the extraction of valuable insights, enabling companies to make data-driven decisions that enhance customer satisfaction and optimize offerings. As ABSA evolves, it holds the potential to greatly improve personalized customer experiences by providing a deeper understanding of sentiment across various product aspects. In this work, we have analyzed the strength of LLMs for a complete cross-domain aspect-based sentiment analysis with the aim of defining the framework for certain products and using it for other similar situations. We argue that it is possible to that at an effectiveness of 92\% accuracy for the Aspect Based Sentiment Analysis dataset of SemEval-2015 Task 12. 

**Abstract (ZH)**: 基于方面的情感分析（Aspect-Based Sentiment Analysis，ABSA）是一种细化的情感分析方法，旨在根据产品、服务或实体的具体方面或特征提取和分类情感。与传统的情感分析不同，后者通常会为整个评论或文本分配一个总体情感评分，ABSA则致力于将文本分解为单独的组成部分或方面（例如，质量、价格、服务），并针对每个方面评估情感。这种做法可以让企业更具体地了解客户意见，使他们能够识别出产品优势和需要改进的具体领域。该过程包括几个关键步骤，如方面提取、情感分类和基于方面的情感聚合，以分析整段评论或用户提供的任何其他形式的文本。ABSA在产品评论、社交媒体监控、客户反馈分析和市场研究等领域具有广泛的应用前景。通过利用自然语言处理（NLP）和机器学习技术，ABSA有助于提取有价值的洞察，从而帮助企业做出数据驱动的决策，提高客户满意度并优化产品。随着ABSA的发展，它有可能通过提供对各种产品方面情感的更深入理解，极大地提升个性化客户体验。在本研究中，我们分析了大语言模型（LLMs）在跨领域方面情感分析中的能力，以期定义某种产品的框架并应用于其他类似情况。我们认为，在SemEval-2015 Task 12 的方面情感分析数据集上，LLMs可以达到92%的准确率。 

---
# Enhanced Large Language Models for Effective Screening of Depression and Anxiety 

**Title (ZH)**: 增强的大语言模型在有效筛查抑郁和焦虑中的应用 

**Authors**: June M. Liu, Mengxia Gao, Sahand Sabour, Zhuang Chen, Minlie Huang, Tatia M.C. Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.08769)  

**Abstract**: Depressive and anxiety disorders are widespread, necessitating timely identification and management. Recent advances in Large Language Models (LLMs) offer potential solutions, yet high costs and ethical concerns about training data remain challenges. This paper introduces a pipeline for synthesizing clinical interviews, resulting in 1,157 interactive dialogues (PsyInterview), and presents EmoScan, an LLM-based emotional disorder screening system. EmoScan distinguishes between coarse (e.g., anxiety or depressive disorders) and fine disorders (e.g., major depressive disorders) and conducts high-quality interviews. Evaluations showed that EmoScan exceeded the performance of base models and other LLMs like GPT-4 in screening emotional disorders (F1-score=0.7467). It also delivers superior explanations (BERTScore=0.9408) and demonstrates robust generalizability (F1-score of 0.67 on an external dataset). Furthermore, EmoScan outperforms baselines in interviewing skills, as validated by automated ratings and human evaluations. This work highlights the importance of scalable data-generative pipelines for developing effective mental health LLM tools. 

**Abstract (ZH)**: 抑郁和焦虑障碍十分普遍，亟需及时的识别和管理。近期大型语言模型（LLMs）的进步提供了潜在的解决方案，但其高昂的成本和训练数据的伦理问题仍然是挑战。本文介绍了一种合成临床访谈的基础管道，生成了1,157份交互对话（PsyInterview），并提出了一种基于LLM的情绪障碍筛查系统——EmoScan。EmoScan能够区分粗略的情绪障碍（如焦虑或抑郁障碍）和精细的情绪障碍（如重度抑郁障碍），并进行高质量的访谈。评估结果显示，EmoScan在筛查情绪障碍方面的性能超过了基础模型和其他LLM（如GPT-4）（F1分数=0.7467）。此外，EmoScan还提供优质的解释（BERTScore=0.9408），并展示了强大的泛化能力（在外数据集上的F1分数为0.67）。此外，EmoScan在访谈能力方面也优于基准模型，这一点通过自动评分和人工评价得到了验证。本研究强调了开发有效心理健康LLM工具时构建可扩展的数据生成管道的重要性。 

---
# The Inherent Limits of Pretrained LLMs: The Unexpected Convergence of Instruction Tuning and In-Context Learning Capabilities 

**Title (ZH)**: 预训练大语言模型的固有限制：指令 tuning 和上下文学习能力的意外交汇 

**Authors**: Irina Bigoulaeva, Harish Tayyar Madabushi, Iryna Gurevych  

**Link**: [PDF](https://arxiv.org/pdf/2501.08716)  

**Abstract**: Large Language Models (LLMs), trained on extensive web-scale corpora, have demonstrated remarkable abilities across diverse tasks, especially as they are scaled up. Nevertheless, even state-of-the-art models struggle in certain cases, sometimes failing at problems solvable by young children, indicating that traditional notions of task complexity are insufficient for explaining LLM capabilities. However, exploring LLM capabilities is complicated by the fact that most widely-used models are also "instruction-tuned" to respond appropriately to prompts. With the goal of disentangling the factors influencing LLM performance, we investigate whether instruction-tuned models possess fundamentally different capabilities from base models that are prompted using in-context examples. Through extensive experiments across various model families, scales and task types, which included instruction tuning 90 different LLMs, we demonstrate that the performance of instruction-tuned models is significantly correlated with the in-context performance of their base counterparts. By clarifying what instruction-tuning contributes, we extend prior research into in-context learning, which suggests that base models use priors from pretraining data to solve tasks. Specifically, we extend this understanding to instruction-tuned models, suggesting that their pretraining data similarly sets a limiting boundary on the tasks they can solve, with the added influence of the instruction-tuning dataset. 

**Abstract (ZH)**: 大规模语言模型（LLMs），基于广泛网络规模的数据集进行训练，在多种任务上展现了显著的能力，尤其是在模型扩展时更为突出。然而，即使是最先进的模型在某些情况下也会遇到困难，有时甚至在年轻人能够解决的问题上表现失败，这表明传统的任务复杂度概念不足以解释LLM的能力。然而，探索LLM能力受到广泛使用的模型多为“指令微调”以适当地响应提示这一事实的困扰。为了剖析影响LLM性能的因素，我们研究了指令微调模型是否与仅通过上下文示例进行提示的基模型在根本上具有不同的能力。通过在各种模型家族、规模和任务类型下进行广泛的实验，包括对90种不同的LLM进行指令微调，我们证明指令微调模型的性能与其基模型的上下文性能之间存在显著的相关性。通过阐明指令微调的贡献，我们将前人关于上下文学习的研究进一步扩展，表明基模型利用预训练数据中的先验知识来解决任务。特别是，我们将这一理解扩展到指令微调模型，表明其预训练数据同样设置了任务解决的限制边界，而附加影响来自于指令微调数据集。 

---
# Knowledge prompt chaining for semantic modeling 

**Title (ZH)**: 知识提示链式方法for语义建模

为了符合学术规范，更准确的翻译应该是：

知识提示链式方法在语义建模中的应用

或者

基于知识提示链的方法进行语义建模 

**Authors**: Ning Pei Ding, Jingge Du, Zaiwen Feng  

**Link**: [PDF](https://arxiv.org/pdf/2501.08540)  

**Abstract**: The task of building semantics for structured data such as CSV, JSON, and XML files is highly relevant in the knowledge representation field. Even though we have a vast of structured data on the internet, mapping them to domain ontologies to build semantics for them is still very challenging as it requires the construction model to understand and learn graph-structured knowledge. Otherwise, the task will require human beings' effort and cost. In this paper, we proposed a novel automatic semantic modeling framework: Knowledge Prompt Chaining. It can serialize the graph-structured knowledge and inject it into the LLMs properly in a Prompt Chaining architecture. Through this knowledge injection and prompting chaining, the model in our framework can learn the structure information and latent space of the graph and generate the semantic labels and semantic graphs following the chains' insturction naturally. Based on experimental results, our method achieves better performance than existing leading techniques, despite using reduced structured input data. 

**Abstract (ZH)**: 构建CSV、JSON和XML等结构化数据语义的任务在知识表示领域具有高度的相关性。尽管互联网上有大量的结构化数据，将这些数据映射到领域本体以构建其语义依然是一个非常具有挑战性的任务，因为它需要构建模型能够理解和学习图结构的知识。否则，该任务将需要人类的努力和成本。在本文中，我们提出了一种新颖的自动语义建模框架：知识提示链。该框架采用提示链架构，能够序列化图结构的知识并适当地注入到LLMs中。通过这种知识的注入和提示链的构建，我们框架中的模型可以学习图的结构信息和潜在空间，并能够自然地根据链的指令生成语义标签和语义图。根据实验结果，尽管我们的方法使用了减少的结构化输入数据，但在现有的领先技术中仍实现了更好的性能。 

---
# Large Language Models For Text Classification: Case Study And Comprehensive Review 

**Title (ZH)**: 大型语言模型在文本分类中的应用：案例研究与综述 

**Authors**: Arina Kostina, Marios D. Dikaiakos, Dimosthenis Stefanidis, George Pallis  

**Link**: [PDF](https://arxiv.org/pdf/2501.08457)  

**Abstract**: Unlocking the potential of Large Language Models (LLMs) in data classification represents a promising frontier in natural language processing. In this work, we evaluate the performance of different LLMs in comparison with state-of-the-art deep-learning and machine-learning models, in two different classification scenarios: i) the classification of employees' working locations based on job reviews posted online (multiclass classification), and 2) the classification of news articles as fake or not (binary classification). Our analysis encompasses a diverse range of language models differentiating in size, quantization, and architecture. We explore the impact of alternative prompting techniques and evaluate the models based on the weighted F1-score. Also, we examine the trade-off between performance (F1-score) and time (inference response time) for each language model to provide a more nuanced understanding of each model's practical applicability. Our work reveals significant variations in model responses based on the prompting strategies. We find that LLMs, particularly Llama3 and GPT-4, can outperform traditional methods in complex classification tasks, such as multiclass classification, though at the cost of longer inference times. In contrast, simpler ML models offer better performance-to-time trade-offs in simpler binary classification tasks. 

**Abstract (ZH)**: 利用大型语言模型（LLMs）在数据分类中的潜力代表了自然语言处理领域的一个有前景的前沿方向。在本文中，我们评估了不同LLMs与最新深度学习和机器学习模型在两种不同的分类场景中的性能表现：i) 根据在线发布的职位评论分类员工的工作地点（多类别分类）；ii) 将新闻文章分类为假新闻或真新闻（二元分类）。我们的分析涵盖了多种在大小、量化和架构方面有所区别的语言模型。我们探讨了替代提示技术的影响，并根据加权F1分数来评估这些模型。我们还分析了每种语言模型的性能（F1分数）与时间（推理响应时间）之间的权衡，以提供对每种模型实际应用性的更细致理解。我们的研究揭示了基于提示策略的模型响应在模型性能上的显著差异。我们发现，尤其是在复杂分类任务（如多类别分类）中，LLM，特别是Llama3和GPT-4，可以超越传统的分类方法，尽管这意味着需要更长的推理时间。相比之下，在简单的二元分类任务中，更简单的机器学习模型提供了更好的性能与时间之间的权衡。 

---
# Ensemble of Large Language Models for Curated Labeling and Rating of Free-text Data 

**Title (ZH)**: 大型语言模型的集成用于精选标注和评估自由文本数据 

**Authors**: Jiaxing Qiu, Dongliang Guo, Papini Natalie, Peace Noelle, Levinson Cheri, Teague R. Henry  

**Link**: [PDF](https://arxiv.org/pdf/2501.08413)  

**Abstract**: Free-text responses are commonly collected in psychological studies, providing rich qualitative insights that quantitative measures may not capture. Labeling curated topics of research interest in free-text data by multiple trained human coders is typically labor-intensive and time-consuming. Though large language models (LLMs) excel in language processing, LLM-assisted labeling techniques relying on closed-source LLMs cannot be directly applied to free-text data, without explicit consent for external use.
In this study, we propose a framework of assembling locally-deployable LLMs to enhance the labeling of predetermined topics in free-text data under privacy constraints. Analogous to annotation by multiple human raters, this framework leverages the heterogeneity of diverse open-source LLMs. The ensemble approach seeks a balance between the agreement and disagreement across LLMs, guided by a relevancy scoring methodology that utilizes embedding distances between topic descriptions and LLMs' reasoning. We evaluated the ensemble approach using both publicly accessible Reddit data from eating disorder related forums, and free-text responses from eating disorder patients, both complemented by human annotations.
We found that: (1) there is heterogeneity in the performance of labeling among same-sized LLMs, with some showing low sensitivity but high precision, while others exhibit high sensitivity but low precision. (2) Compared to individual LLMs, the ensemble of LLMs achieved the highest accuracy and optimal precision-sensitivity trade-off in predicting human annotations. (3) The relevancy scores across LLMs showed greater agreement than dichotomous labels, indicating that the relevancy scoring method effectively mitigates the heterogeneity in LLMs' labeling. 

**Abstract (ZH)**: 在心理学研究中，通常会收集开放文本回应，这些回应提供了丰富的定性见解，而这些见解可能无法通过定量测量捕捉到。为了在开放文本数据中标注研究感兴趣的主题，通常需要多个经过训练的人工编码员进行标注，这通常是耗费大量时间和人力的。尽管大型语言模型（LLMs）在语言处理方面表现出色，但依赖闭源LLMs的LLM辅助标注技术在没有明确外部使用同意的情况下无法直接应用于开放文本数据。

本研究提出了一种在隐私约束下增强对预定主题的开放文本数据标注的框架。类比于多个人类评估者的手动标注，该框架利用了多种开源LLMs的多样性。集成方法旨在在不同LLM之间找到一种平衡，即通过主题描述与LLM推理之间的嵌入距离来评估相关性得分方法，来平衡一致性和分歧。我们使用来自饮食障碍相关论坛的公开可访问的Reddit数据和饮食障碍患者的开放文本回应进行了评估，这些数据都与人类注释相补充。

研究结果表明：（1）相同规模的LLM在标注性能上存在异质性，一些LLM表现出低灵敏度但高精确度，而另一些则表现出高灵敏度但低精确度。（2）与单个LLM相比，LLM的集成在预测人类注释方面实现了最高的准确性以及最佳的精确度-灵敏度权衡。（3）LLM之间的相关性得分比二元标签显示了更高的共识，表明相关性得分方法有效地减轻了LLM标注中的异质性。 

---
# SEAL: Speaker Error Correction using Acoustic-conditioned Large Language Models 

**Title (ZH)**: SEAL：基于声学条件的大语言模型 speaker 错误校正 

**Authors**: Anurag Kumar, Rohit Paturi, Amber Afshan, Sundararajan Srinivasan  

**Link**: [PDF](https://arxiv.org/pdf/2501.08421)  

**Abstract**: Speaker Diarization (SD) is a crucial component of modern end-to-end ASR pipelines. Traditional SD systems, which are typically audio-based and operate independently of ASR, often introduce speaker errors, particularly during speaker transitions and overlapping speech. Recently, language models including fine-tuned large language models (LLMs) have shown to be effective as a second-pass speaker error corrector by leveraging lexical context in the transcribed output. In this work, we introduce a novel acoustic conditioning approach to provide more fine-grained information from the acoustic diarizer to the LLM. We also show that a simpler constrained decoding strategy reduces LLM hallucinations, while avoiding complicated post-processing. Our approach significantly reduces the speaker error rates by 24-43% across Fisher, Callhome, and RT03-CTS datasets, compared to the first-pass Acoustic SD. 

**Abstract (ZH)**: 说话人分离（SD）是现代端到端ASR流水线中的一个关键组件。传统的SD系统通常是基于音频的，并且独立于ASR系统工作，这在说话人转换和重叠语音时容易引入说话人错误。最近，包括微调的大语言模型（LLMs）已被证明能够通过利用转录输出中的词汇上下文，作为第二阶段的说话人错误校正工具，达到有效的作用。在本工作中，我们提出了一种新的声学条件编码方法，以向LLM提供更细致的信息。我们还展示了简单的约束解码策略减少了LLM的幻觉，同时避免了复杂的后处理步骤。与第一次的声学SD相比，我们的方法在Fisher、Callhome和RT03-CTS数据集上将说话人错误率显著降低了24-43%。 

---
# OptiChat: Bridging Optimization Models and Practitioners with Large Language Models 

**Title (ZH)**: OptiChat：连接优化模型与 Practitioners 的大型语言模型桥梁 

**Authors**: Hao Chen, Gonzalo Esteban Constante-Flores, Krishna Sri Ipsit Mantri, Sai Madhukiran Kompalli, Akshdeep Singh Ahluwalia, Can Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.08406)  

**Abstract**: Optimization models have been applied to solve a wide variety of decision-making problems. These models are usually developed by optimization experts but are used by practitioners without optimization expertise in various application domains. As a result, practitioners often struggle to interact with and draw useful conclusions from optimization models independently. To fill this gap, we introduce OptiChat, a natural language dialogue system designed to help practitioners interpret model formulation, diagnose infeasibility, analyze sensitivity, retrieve information, evaluate modifications, and provide counterfactual explanations. By augmenting large language models (LLMs) with functional calls and code generation tailored for optimization models, we enable seamless interaction and minimize the risk of hallucinations in OptiChat. We develop a new dataset to evaluate OptiChat's performance in explaining optimization models. Experiments demonstrate that OptiChat effectively bridges the gap between optimization models and practitioners, delivering autonomous, accurate, and instant responses. 

**Abstract (ZH)**: 优化模型已被应用于解决众多决策问题。这些模型通常由优化专家开发，但在各种应用领域中，实际操作者（缺乏优化专业知识）会使用这些模型。因此，实际操作者往往难以独立地与优化模型交互并从中得出有用的结论。为填补这一空白，我们介绍了一个名为OptiChat的自然语言对话系统，旨在帮助实际操作者解释模型公式、诊断不可行性、分析敏感性、检索信息、评估修改并提供反事实解释。通过将大型语言模型（LLMs）与针对优化模型的功能调用和代码生成相结合，我们使OptiChat的交互更加顺畅，并减少了其产生幻觉的风险。我们开发了一个新的数据集来评估OptiChat在解释优化模型方面的性能。实验结果表明，OptiChat有效地弥合了优化模型与实际操作者之间的差距，提供了自主、准确且即时的响应。 

---
# Development and Validation of the Provider Documentation Summarization Quality Instrument for Large Language Models 

**Title (ZH)**: 面向大型语言模型的提供者文档总结质量评价工具的开发与验证 

**Authors**: Emma Croxford, Yanjun Gao, Nicholas Pellegrino, Karen K. Wong, Graham Wills, Elliot First, Miranda Schnier, Kyle Burton, Cris G. Ebby, Jillian Gorskic, Matthew Kalscheur, Samy Khalil, Marie Pisani, Tyler Rubeor, Peter Stetson, Frank Liao, Cherodeep Goswami, Brian Patterson, Majid Afshar  

**Link**: [PDF](https://arxiv.org/pdf/2501.08977)  

**Abstract**: As Large Language Models (LLMs) are integrated into electronic health record (EHR) workflows, validated instruments are essential to evaluate their performance before implementation. Existing instruments for provider documentation quality are often unsuitable for the complexities of LLM-generated text and lack validation on real-world data. The Provider Documentation Summarization Quality Instrument (PDSQI-9) was developed to evaluate LLM-generated clinical summaries. Multi-document summaries were generated from real-world EHR data across multiple specialties using several LLMs (GPT-4o, Mixtral 8x7b, and Llama 3-8b). Validation included Pearson correlation for substantive validity, factor analysis and Cronbach's alpha for structural validity, inter-rater reliability (ICC and Krippendorff's alpha) for generalizability, a semi-Delphi process for content validity, and comparisons of high- versus low-quality summaries for discriminant validity. Seven physician raters evaluated 779 summaries and answered 8,329 questions, achieving over 80% power for inter-rater reliability. The PDSQI-9 demonstrated strong internal consistency (Cronbach's alpha = 0.879; 95% CI: 0.867-0.891) and high inter-rater reliability (ICC = 0.867; 95% CI: 0.867-0.868), supporting structural validity and generalizability. Factor analysis identified a 4-factor model explaining 58% of the variance, representing organization, clarity, accuracy, and utility. Substantive validity was supported by correlations between note length and scores for Succinct (rho = -0.200, p = 0.029) and Organized (rho = -0.190, p = 0.037). Discriminant validity distinguished high- from low-quality summaries (p < 0.001). The PDSQI-9 demonstrates robust construct validity, supporting its use in clinical practice to evaluate LLM-generated summaries and facilitate safer integration of LLMs into healthcare workflows. 

**Abstract (ZH)**: 将大型语言模型（LLMs）集成到电子健康记录（EHR）工作流程中，实施前需要使用经过验证的工具评估其性能变得至关重要。现有的提供者文档质量评估工具往往不适合LLM生成的复杂文本，并且缺乏实际数据的验证。为了评估LLM生成的临床摘要质量，开发了提供者文档摘要质量评估工具（PDSQI-9）。使用几种LLM（GPT-4o、Mixtral 8x7b 和 Llama 3-8b）从多个专科的真实EHR数据中生成多文档摘要。验证工作包括皮尔逊相关性分析以确保实质性效度、因素分析和Cronbach's α以确保结构效度、可靠性检验（ICC和克朗巴哈α）以确保通用性、半德尔菲过程以确保内容效度，以及高质量与低质量摘要的对比以确保区分效度。七位临床医生评价者共评估了779份摘要并回答了8,329个问题，达到了80%以上的评价者间可靠性。PDSQI-9具有良好的内部一致性（Cronbach's α = 0.879；95% CI: 0.867-0.891）和高度的评价者间可靠性（ICC = 0.867；95% CI: 0.867-0.868），这支持了其结构效度和通用性。因素分析识别出一个解释58%变异的4因子模型，分别代表了组织性、清晰度、准确性和实用性。实质性效度由注释长度和精练（Succinct）和组织（Organized）评分的相关性（rho = -0.200，p = 0.029；rho = -0.190，p = 0.037）支持。区分效度能够区分高质量和低质量的摘要（p < 0.001）。PDSQI-9展示了强大的构建效度，支持其在临床实践中评估LLM生成的摘要，并促进LLM在医疗保健工作流程中的安全集成。 

---
# Leveraging Large Language Models as Knowledge-Driven Agents for Reliable Retrosynthesis Planning 

**Title (ZH)**: 利用大型语言模型作为知识驱动代理进行可靠的逆合成规划 

**Authors**: Qinyu Ma, Yuhao Zhou, Jianfeng Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.08897)  

**Abstract**: Identifying reliable synthesis pathways in materials chemistry is a complex task, particularly in polymer science, due to the intricate and often non-unique nomenclature of macromolecules. To address this challenge, we propose an agent system that integrates large language models (LLMs) and knowledge graphs (KGs). By leveraging LLMs' powerful capabilities for extracting and recognizing chemical substance names, and storing the extracted data in a structured knowledge graph, our system fully automates the retrieval of relevant literatures, extraction of reaction data, database querying, construction of retrosynthetic pathway trees, further expansion through the retrieval of additional literature and recommendation of optimal reaction pathways. A novel Multi-branched Reaction Pathway Search (MBRPS) algorithm enables the exploration of all pathways, with a particular focus on multi-branched ones, helping LLMs overcome weak reasoning in multi-branched paths. This work represents the first attempt to develop a fully automated retrosynthesis planning agent tailored specially for macromolecules powered by LLMs. Applied to polyimide synthesis, our new approach constructs a retrosynthetic pathway tree with hundreds of pathways and recommends optimized routes, including both known and novel pathways, demonstrating its effectiveness and potential for broader applications. 

**Abstract (ZH)**: 在材料化学中识别可靠的合成途径是一个复杂任务，特别是在聚合物科学领域，由于高分子物质的名称复杂且往往不唯一。为了应对这一挑战，我们提出了一种结合大型语言模型（LLMs）和知识图谱（KGs）的代理系统。通过利用LLMs强大的提取和识别化学物质名称的能力，并将提取的数据存储在结构化知识图谱中，我们的系统实现了有关文献的全自动检索、反应数据的提取、数据库查询、逆向合成路径树的构建，并进一步通过检索额外文献来扩大路径范围，推荐最佳反应途径。一种新型的多分支反应路径搜索（MBRPS）算法能够探索所有可能路径，特别是对于多分支路径的探索尤为突出，帮助LLMs克服多分支路径推理的局限性。本研究代表了利用LLMs构建专门针对高分子的全自动逆向合成规划代理系统的首次尝试。应用到聚酰亚胺的合成中，我们提出的新方法构建了一个包含数百条路径的逆向合成路径树，并推荐了优化路径，包括已知和新颖路径，展示了其有效性和更广泛的应用潜力。 

---
# Multimodal LLMs Can Reason about Aesthetics in Zero-Shot 

**Title (ZH)**: 多模态大语言模型可以在零样本情况下进行审美推理 

**Authors**: Ruixiang Jiang, Changwen Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.09012)  

**Abstract**: We present the first study on how Multimodal LLMs' (MLLMs) reasoning ability shall be elicited to evaluate the aesthetics of artworks. To facilitate this investigation, we construct MM-StyleBench, a novel high-quality dataset for benchmarking artistic stylization. We then develop a principled method for human preference modeling and perform a systematic correlation analysis between MLLMs' responses and human preference. Our experiments reveal an inherent hallucination issue of MLLMs in art evaluation, associated with response subjectivity. ArtCoT is proposed, demonstrating that art-specific task decomposition and the use of concrete language boost MLLMs' reasoning ability for aesthetics. Our findings offer valuable insights into MLLMs for art and can benefit a wide range of downstream applications, such as style transfer and artistic image generation. Code available at this https URL. 

**Abstract (ZH)**: 我们首次探讨了如何通过Multimodal LLMs（多模态大语言模型）的推理能力评估艺术品的美学问题。为了便于这项研究，我们构建了MM-StyleBench，这是一个新颖的高质量基准数据集，用于评估艺术风格化。随后，我们开发了一种原则性的方法来建模人类偏好，并进行了MLLMs回答与人类偏好之间的系统相关性分析。我们的实验揭示了MLLMs在艺术评估中的固有幻觉问题，与响应的主观性有关。我们提出了ArtCoT，表明特定于艺术的任务分解和使用具体语言能够提升MLLMs在美学方面的推理能力。本研究为我们理解多模态大语言模型在艺术领域提供了宝贵的见解，并可以应用于多种下游应用，如风格迁移和艺术图像生成。代码见此处：[提供的链接]。 

---
# Leveraging LLM Agents for Translating Network Configurations 

**Title (ZH)**: 利用大语言模型代理进行网络配置翻译 

**Authors**: Yunze Wei, Xiaohui Xie, Yiwei Zuo, Tianshuo Hu, Xinyi Chen, Kaiwen Chi, Yong Cui  

**Link**: [PDF](https://arxiv.org/pdf/2501.08760)  

**Abstract**: Configuration translation is a critical and frequent task in network operations. When a network device is damaged or outdated, administrators need to replace it to maintain service continuity. The replacement devices may originate from different vendors, necessitating configuration translation to ensure seamless network operation. However, translating configurations manually is a labor-intensive and error-prone process. In this paper, we propose an intent-based framework for translating network configuration with Large Language Model (LLM) Agents. The core of our approach is an Intent-based Retrieval Augmented Generation (IRAG) module that systematically splits a configuration file into fragments, extracts intents, and generates accurate translations. We also design a two-stage verification method to validate the syntax and semantics correctness of the translated configurations. We implement and evaluate the proposed method on real-world network configurations. Experimental results show that our method achieves 97.74% syntax correctness, outperforming state-of-the-art methods in translation accuracy. 

**Abstract (ZH)**: 网络配置的翻译是网络运维中一个关键且频繁的任务。当网络设备出现故障或过时，管理员需要更换设备以保持服务连续性。替换设备可能来自不同的供应商，这需要进行配置翻译以确保网络无缝运行。然而，手动翻译配置是一个劳动密集且易出错的过程。在本文中，我们提出了一种基于意图的框架，利用大型语言模型（LLM）代理进行网络配置翻译。我们方法的核心是一个基于意图的检索增强生成（IRAG）模块，该模块系统地将配置文件拆分为片段、提取意图并生成准确的翻译。我们还设计了一种两阶段验证方法，以验证翻译配置的语法和语义正确性。我们已在实际网络配置上实现了并评估了该方法。实验结果表明，我们的方法在语法正确性方面达到了97.74%，在翻译准确性方面超过了现有最先进的方法。 

---
# LlamaRestTest: Effective REST API Testing with Small Language Models 

**Title (ZH)**: LlamaRestTest：使用小型语言模型进行有效的REST API测试 

**Authors**: Myeongsoo Kim, Saurabh Sinha, Alessandro Orso  

**Link**: [PDF](https://arxiv.org/pdf/2501.08598)  

**Abstract**: Modern web services rely heavily on REST APIs, typically documented using the OpenAPI specification. The widespread adoption of this standard has resulted in the development of many black-box testing tools that generate tests based on these specifications. Recent advancements in Natural Language Processing (NLP), particularly with Large Language Models (LLMs), have enhanced REST API testing by extracting actionable rules and generating input values from the human-readable portions of the specification. However, these advancements overlook the potential of continuously refining the identified rules and test inputs based on server responses. To address this limitation, we present LlamaRestTest, a novel approach that employs two custom LLMs to generate realistic test inputs and uncover parameter dependencies during the testing process by incorporating server responses. These LLMs are created by fine-tuning the Llama3-8b model, using mined datasets of REST API example values and inter-parameter dependencies. We evaluated LlamaRestTest on 12 real-world services (including popular services such as Spotify), comparing it against RESTGPT, a GPT-powered specification-enhancement tool, as well as several state-of-the-art REST API testing tools, including RESTler, MoRest, EvoMaster, and ARAT-RL. Our results show that fine-tuning enables smaller LLMs to outperform larger models in detecting actionable rules and generating inputs for REST API testing. We evaluated configurations from the base Llama3-8B to fine-tuned versions and explored 2-bit, 4-bit, and 8-bit quantization for efficiency. LlamaRestTest surpasses state-of-the-art tools in code coverage and error detection, even with RESTGPT-enhanced specifications, and an ablation study highlights the impact of its novel components. 

**Abstract (ZH)**: 现代Web服务高度依赖于REST API，这些API通常使用OpenAPI规范进行文档描述。这个标准的广泛采用导致开发了许多黑盒测试工具，这些工具根据规范生成测试用例。近年来，自然语言处理（NLP）的最新进展，尤其是大型语言模型（LLMs），通过从规范的人类可读部分中提取可操作规则并生成输入值，增强了REST API的测试。然而，这些进展忽视了根据服务器响应连续改进所识别规则和测试输入的潜力。为了解决这一局限，我们提出了LlamaRestTest，这是一种新颖的方法，通过结合服务器响应来生成现实的测试输入并揭示参数依赖关系。这种方法通过使用REST API示例值和参数间依赖关系的挖掘数据集对Llama3-8b模型进行微调来创建两个自定义的LLMs。我们在12个真实服务（包括流行的Spotify服务）上评估了LlamaRestTest，将其与RESTGPT（一个基于GPT的规格增强工具）以及RESTler、MoRest、EvoMaster和ARAT-RL等最先进的REST API测试工具进行了对比。结果显示，微调使小型LLMs能够超越大型模型，在检测可操作规则和生成REST API测试输入方面表现更优。我们从基础的Llama3-8B配置到微调版本进行了配置评估，并探索了2比特、4比特和8比特的量化方法以提高效率。LlamaRestTest在代码覆盖率和错误检测方面超越了最先进的工具，即使在RESTGPT增强的规格下也是如此。消融研究强调了其新型组件的影响。 

---
# LAMS: LLM-Driven Automatic Mode Switching for Assistive Teleoperation 

**Title (ZH)**: LAMS：由大语言模型驱动的辅助远程操作自动模式切换 

**Authors**: Yiran Tao, Jehan Yang, Dan Ding, Zackory Erickson  

**Link**: [PDF](https://arxiv.org/pdf/2501.08558)  

**Abstract**: Teleoperating high degrees-of-freedom (DoF) robotic manipulators via low-DoF controllers like joysticks often requires frequent switching between control modes, where each mode maps controller movements to specific robot actions. Manually performing this frequent switching can make teleoperation cumbersome and inefficient. On the other hand, existing automatic mode-switching solutions, such as heuristic-based or learning-based methods, are often task-specific and lack generalizability. In this paper, we introduce LLM-Driven Automatic Mode Switching (LAMS), a novel approach that leverages Large Language Models (LLMs) to automatically switch control modes based on task context. Unlike existing methods, LAMS requires no prior task demonstrations and incrementally improves by integrating user-generated mode-switching examples. We validate LAMS through an ablation study and a user study with 10 participants on complex, long-horizon tasks, demonstrating that LAMS effectively reduces manual mode switches, is preferred over alternative methods, and improves performance over time. The project website with supplementary materials is at this https URL. 

**Abstract (ZH)**: 通过低自由度（DoF）控制器（如游戏杆）遥控高自由度（DoF）机器人操作器时，经常需要频繁地在不同的控制模式之间切换，每个模式都将控制器的动作映射到特定的机器人动作。手动进行这种频繁的切换会让遥操作变得繁琐且低效。另一方面，现有的自动模式切换解决方案，如基于启发式或基于学习的方法，通常是任务特定的，缺乏普适性。在本文中，我们介绍了一种新颖的方法——大型语言模型驱动的自动模式切换（LAMS），该方法利用大型语言模型（LLMs）根据任务上下文自动切换控制模式。与现有的方法不同，LAMS不需要任何先验的任务演示，并通过整合用户生成的模式切换示例进行增量改进。我们通过消融研究和包含10名参与者的用户研究对LAMS进行了验证，表明LAMS有效减少了手动模式切换，优于其他方法，并随着时间的推移提高了性能。项目的官方网站和补充材料可在如下链接访问：[这个链接]。 

---