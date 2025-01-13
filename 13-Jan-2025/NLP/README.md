# Contextual ASR Error Handling with LLMs Augmentation for Goal-Oriented Conversational AI 

**Title (ZH)**: 基于上下文的ASR错误处理：通过LLM增强的目标导向会话AI中的应用 

**Authors**: Yuya Asano, Sabit Hassan, Paras Sharma, Anthony Sicilia, Katherine Atwell, Diane Litman, Malihe Alikhani  

**Link**: [PDF](https://arxiv.org/pdf/2501.06129)  

**Abstract**: General-purpose automatic speech recognition (ASR) systems do not always perform well in goal-oriented dialogue. Existing ASR correction methods rely on prior user data or named entities. We extend correction to tasks that have no prior user data and exhibit linguistic flexibility such as lexical and syntactic variations. We propose a novel context augmentation with a large language model and a ranking strategy that incorporates contextual information from the dialogue states of a goal-oriented conversational AI and its tasks. Our method ranks (1) n-best ASR hypotheses by their lexical and semantic similarity with context and (2) context by phonetic correspondence with ASR hypotheses. Evaluated in home improvement and cooking domains with real-world users, our method improves recall and F1 of correction by 34% and 16%, respectively, while maintaining precision and false positive rate. Users rated .8-1 point (out of 5) higher when our correction method worked properly, with no decrease due to false positives. 

**Abstract (ZH)**: 通用的自动语音识别（ASR）系统在目标导向对话中并不总是表现出色。现有的ASR纠错方法依赖于用户的先验数据或命名实体。我们扩展了纠错到那些没有用户先验数据且表现出语文灵活性的任务，如词汇和句法变化。我们提出了一种新的上下文增强方法，该方法结合了大规模语言模型和一种排名策略，该策略综合了目标导向对话AI及其任务在对话状态中的上下文信息。我们的方法通过（1）按与上下文的词汇和语义相似度对n-best ASR假设进行排名，以及（2）通过音素对应关系对上下文进行排名。在家庭装修和烹饪领域通过真实用户进行了评估，我们的方法在召回率和F1值上分别提高了34%和16%，同时保持了精确度和假阳性率。当我们的纠错方法正常工作时，用户评分提高了0.8至1分（满分5分），并且没有因假阳性而降低评分。 

---
# Merging Feed-Forward Sublayers for Compressed Transformers 

**Title (ZH)**: 压缩Transformer中前馈子层的融合 

**Authors**: Neha Verma, Kenton Murray, Kevin Duh  

**Link**: [PDF](https://arxiv.org/pdf/2501.06126)  

**Abstract**: With the rise and ubiquity of larger deep learning models, the need for high-quality compression techniques is growing in order to deploy these models widely. The sheer parameter count of these models makes it difficult to fit them into the memory constraints of different hardware. In this work, we present a novel approach to model compression by merging similar parameter groups within a model, rather than pruning away less important parameters. Specifically, we select, align, and merge separate feed-forward sublayers in Transformer models, and test our method on language modeling, image classification, and machine translation. With our method, we demonstrate performance comparable to the original models while combining more than a third of model feed-forward sublayers, and demonstrate improved performance over a strong layer-pruning baseline. For instance, we can remove over 21% of total parameters from a Vision Transformer, while maintaining 99% of its original performance. Additionally, we observe that some groups of feed-forward sublayers exhibit high activation similarity, which may help explain their surprising mergeability. 

**Abstract (ZH)**: 随着更大规模深度学习模型的兴起及其无处不在的应用，对高效压缩技术的需求也在增长，以广泛部署这些模型。这些模型的参数数量庞大，使得它们难以适应不同硬件的内存限制。本研究提出了一种新的模型压缩方法，通过在模型内部合并相似的参数组，而不是剪枝掉不重要的参数。具体而言，我们选择了、对齐并合并了Transformer模型中的独立前馈子层，并在语言建模、图像分类和机器翻译任务上测试了我们的方法。通过我们的方法，我们在保持性能的同时合并了超过模型前馈子层的三分之一，同时超过了强大的层剪枝基准模型的性能。例如，我们可以在不牺牲其99%原始性能的情况下从Vision Transformer中移除超过21%的总参数。此外，我们观察到某些前馈子层组表现出高度激活相似性，这可能有助于解释它们的合并能力。 

---
# Fleurs-SLU: A Massively Multilingual Benchmark for Spoken Language Understanding 

**Title (ZH)**: Fleurs-SLU：大规模多语种语音语言理解基准测试 

**Authors**: Fabian David Schmidt, Ivan Vulić, Goran Glavaš, David Ifeoluwa Adelani  

**Link**: [PDF](https://arxiv.org/pdf/2501.06117)  

**Abstract**: While recent multilingual automatic speech recognition models claim to support thousands of languages, ASR for low-resource languages remains highly unreliable due to limited bimodal speech and text training data. Better multilingual spoken language understanding (SLU) can strengthen massively the robustness of multilingual ASR by levering language semantics to compensate for scarce training data, such as disambiguating utterances via context or exploiting semantic similarities across languages. Even more so, SLU is indispensable for inclusive speech technology in roughly half of all living languages that lack a formal writing system. However, the evaluation of multilingual SLU remains limited to shallower tasks such as intent classification or language identification. To address this, we present Fleurs-SLU, a multilingual SLU benchmark that encompasses topical speech classification in 102 languages and multiple-choice question answering through listening comprehension in 92 languages. We extensively evaluate both end-to-end speech classification models and cascaded systems that combine speech-to-text transcription with subsequent classification by large language models on Fleurs-SLU. Our results show that cascaded systems exhibit greater robustness in multilingual SLU tasks, though speech encoders can achieve competitive performance in topical speech classification when appropriately pre-trained. We further find a strong correlation between robust multilingual ASR, effective speech-to-text translation, and strong multilingual SLU, highlighting the mutual benefits between acoustic and semantic speech representations. 

**Abstract (ZH)**: 尽管近年来的多语种自动语音识别（ASR）模型声称支持数千种语言，但低资源语言的ASR仍旧因为有限的双模态（即语音和文本）训练数据而可靠性较差。更好的多语种口语语言理解（SLU）可以通过利用语言语义来补偿稀缺的训练数据，从而大大增强多语种ASR的鲁棒性，例如通过上下文来消歧义语音片段或利用语言之间的语义相似性。更为重要的是，SLU对于缺乏正式书写系统的大约一半现存语言来说是必不可少的。然而，多语种SLU的评估仍然局限于较浅层次的任务，如意图分类或语言识别。为了解决这一问题，我们提出了Fleurs-SLU基准，该基准包括102种语言的主题语音分类和92种语言的听力理解型多项选择题回答。我们全面评估了端到端语音分类模型和结合语音转文本转录与后续大型语言模型分类的级联系统在Fleurs-SLU上的性能。我们的结果显示，在多语种SLU任务中，级联系统表现出更好的鲁棒性，尽管适当的预训练可以让语音编码器在主题语音分类任务中取得竞争力的表现。此外，我们发现鲁棒的多语种ASR、有效的语音转文本翻译和强大的多语种SLU之间存在很强的相关性，突显了声学和语义语音表示之间的相互益处。 

---
# From Conversation to Automation: Leveraging Large Language Models to Analyze Strategies in Problem Solving Therapy 

**Title (ZH)**: 从对话到自动化：利用大规模语言模型分析问题解决疗法中的策略 

**Authors**: Elham Aghakhani, Lu Wang, Karla T. Washington, George Demiris, Jina Huh-Yoo, Rezvaneh Rezapour  

**Link**: [PDF](https://arxiv.org/pdf/2501.06101)  

**Abstract**: Problem-solving therapy (PST) is a structured psychological approach that helps individuals manage stress and resolve personal issues by guiding them through problem identification, solution brainstorming, decision-making, and outcome evaluation. As mental health care increasingly integrates technologies like chatbots and large language models (LLMs), understanding how PST can be effectively automated is important. This study leverages anonymized therapy transcripts to analyze and classify therapeutic interventions using various LLMs and transformer-based models. Our results show that GPT-4o achieved the highest accuracy (0.76) in identifying PST strategies, outperforming other models. Additionally, we introduced a new dimension of communication strategies that enhances the current PST framework, offering deeper insights into therapist-client interactions. This research demonstrates the potential of LLMs to automate complex therapeutic dialogue analysis, providing a scalable, efficient tool for mental health interventions. Our annotation framework can enhance the accessibility, effectiveness, and personalization of PST, supporting therapists in real-time with more precise, targeted interventions. 

**Abstract (ZH)**: 问题解决疗法（PST）是一种结构化的心理治疗方法，通过引导个体识别问题、 brainstorm 解决方案、做出决策和评估结果，帮助他们管理压力和解决个人问题。随着心理健康护理越来越多地结合聊天机器人和大型语言模型（LLMs）等技术，了解如何有效自动化 PST 是至关重要的。本研究利用匿名的心理治疗转录材料，使用各种 LLM 和基于变换器的模型进行分析和分类。研究结果表明，GPT-4o 在识别 PST 策略方面取得了最高准确率（0.76），超越了其他模型。此外，我们还引入了一种新的沟通策略维度，以增强现有的 PST 框架，提供对咨询师与求助者互动更深层次的洞察。本研究证明了 LLMs 在自动化复杂治疗对话分析方面的潜力，提供了一种可扩展且高效的工具，用于支持心理健康干预。我们的注解框架可以增强 PST 的可访问性、有效性及个性化，支持咨询师实时提供更加精准和针对性的干预措施。 

---
# Benchmarking Rotary Position Embeddings for Automatic Speech Recognition 

**Title (ZH)**: Rotary Position Embeddings for Automatic Speech Recognition 的基准测试 

**Authors**: Shucong Zhang, Titouan Parcollet, Rogier van Dalen, Sourav Bhattacharya  

**Link**: [PDF](https://arxiv.org/pdf/2501.06051)  

**Abstract**: Rotary Position Embedding (RoPE) encodes relative and absolute positional information in Transformer-based models through rotation matrices applied to input vectors within sequences. While RoPE has demonstrated superior performance compared to other positional embedding technologies in natural language processing tasks, its effectiveness in speech processing applications remains understudied. In this work, we conduct a comprehensive evaluation of RoPE across diverse automatic speech recognition (ASR) tasks. Our experimental results demonstrate that for ASR tasks, RoPE consistently achieves lower error rates compared to the currently widely used relative positional embedding. To facilitate further research, we release the implementation and all experimental recipes through the SpeechBrain toolkit. 

**Abstract (ZH)**: 以下是经过学术规范翻译后的版本：

在基于Transformer的模型中，旋转位置嵌入（Rotary Position Embedding，简称RoPE）通过将旋转矩阵应用于序列中的输入向量来编码相对和绝对位置信息。虽然RoPE在自然语言处理任务中已经展示出优于其他位置嵌入技术的性能，但在语音处理应用中的效果尚未得到充分研究。本研究针对自动语音识别（Automatic Speech Recognition，简称ASR）任务进行了全面评估。实验结果表明，对于ASR任务，RoPE始终能够实现更低的错误率，相比当前广泛使用的相对位置嵌入方法更具优势。为了进一步促进相关研究，我们将RoPE的实现和所有实验配置通过SpeechBrain工具包公开发布。 

---
# How to Tune a Multilingual Encoder Model for Germanic Languages: A Study of PEFT, Full Fine-Tuning, and Language Adapters 

**Title (ZH)**: 如何调整多语言编码器模型以适用于日耳曼语言：基于PEFT、全程微调和语言适配器的研究 

**Authors**: Romina Oji, Jenny Kunz  

**Link**: [PDF](https://arxiv.org/pdf/2501.06025)  

**Abstract**: This paper investigates the optimal use of the multilingual encoder model mDeBERTa for tasks in three Germanic languages -- German, Swedish, and Icelandic -- representing varying levels of presence and likely data quality in mDeBERTas pre-training data. We compare full fine-tuning with the parameter-efficient fine-tuning (PEFT) methods LoRA and Pfeiffer bottleneck adapters, finding that PEFT is more effective for the higher-resource language, German. However, results for Swedish and Icelandic are less consistent. We also observe differences between tasks: While PEFT tends to work better for question answering, full fine-tuning is preferable for named entity recognition. Inspired by previous research on modular approaches that combine task and language adapters, we evaluate the impact of adding PEFT modules trained on unstructured text, finding that this approach is not beneficial. 

**Abstract (ZH)**: 本文探讨了多语言编码器模型mDeBERTa在三种日耳曼语系语言——德语、瑞典语和冰岛语——中的最优应用。这三种语言在mDeBERTa预训练数据中的存在程度和可能的数据质量各异。我们对比了全面微调与参数高效微调（PEFT）方法（LoRA和Pfeiffer瓶颈适配器）的效果，发现对于资源较为丰富的德语，PEFT方法更为有效。然而，对于瑞典语和冰岛语，结果不够一致。我们还发现了任务之间的差异：尽管对于问答任务，PEFT方法的效果更佳，但对于命名实体识别任务，全面微调更为适合。受先前研究关于结合任务适配器和语言适配器的模块化方法的启发，我们评估了在未结构化文本上训练PEFT模块的影响，发现这种方法并无益处。 

---
# Constraining constructions with WordNet: pros and cons for the semantic annotation of fillers in the Italian Constructicon 

**Title (ZH)**: 使用WordNet约束构建：对意大利Constructicon中填充词的语义注解的利弊分析 

**Authors**: Flavio Pisciotta, Ludovica Pannitto, Lucia Busso, Beatrice Bernasconi, Francesca Masini  

**Link**: [PDF](https://arxiv.org/pdf/2501.05990)  

**Abstract**: The paper discusses the role of WordNet-based semantic classification in the formalization of constructions, and more specifically in the semantic annotation of schematic fillers, in the Italian Constructicon. We outline how the Italian Constructicon project uses Open Multilingual WordNet topics to represent semantic features and constraints of constructions. 

**Abstract (ZH)**: 本文探讨了基于WordNet的语义分类在构造形式化中的作用，特别是在意大利Constructicon中方案填充语义标注中的作用。我们概述了意大利Constructicon项目如何使用开放多语言WordNet主题来表示构造的语义特征和约束。 

---
# Addressing speaker gender bias in large scale speech translation systems 

**Title (ZH)**: 大规模语音翻译系统中讲话者性别偏见的应对方法 

**Authors**: Shubham Bansal, Vikas Joshi, Harveen Chadha, Rupeshkumar Mehta, Jinyu Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.05989)  

**Abstract**: This study addresses the issue of speaker gender bias in Speech Translation (ST) systems, which can lead to offensive and inaccurate translations. The masculine bias often found in large-scale ST systems is typically perpetuated through training data derived from Machine Translation (MT) systems. Our approach involves two key steps. First, we employ Large Language Models (LLMs) to rectify translations based on the speaker's gender in a cost-effective manner. Second, we fine-tune the ST model with the corrected data, enabling the model to generate gender-specific translations directly from audio cues, without the need for explicit gender input. Additionally, we propose a three-mode fine-tuned model for scenarios where the speaker's gender is either predefined or should not be inferred from speech cues. We demonstrate a 70% improvement in translations for female speakers compared to our baseline and other large-scale ST systems, such as Seamless M4T and Canary, on the MuST-SHE test set. 

**Abstract (ZH)**: 本研究针对语音翻译（ST）系统中的说话人口音偏差问题进行了研究，这一问题可能导致冒犯性和不准确的翻译。大规模ST系统中常见的男性偏见通常通过源于机器翻译（MT）系统的训练数据得以延续。我们的方法包括两个关键步骤。首先，我们利用大型语言模型（LLMs）以经济高效的方式纠正翻译中的性别偏差。其次，我们使用修正后的数据微调ST模型，使模型能够直接从音频提示中生成性别特定的翻译，而无需明确输入性别信息。此外，我们还提出了一种三模式微调模型，适用于说话人口音已预定义或不应从语音提示中推断的情况。我们使用MuST-SHE测试集展示了与基线及其他大规模ST系统（如Seamless M4T和Canary）相比，对于女性说话人的翻译改进率达到70%。 

---
# Hermit Kingdom Through the Lens of Multiple Perspectives: A Case Study of LLM Hallucination on North Korea 

**Title (ZH)**: 多重视角下的隐秘王国：一项关于LLM幻觉的朝鲜案例研究 

**Authors**: Eunjung Cho, Won Ik Cho, Soomin Seo  

**Link**: [PDF](https://arxiv.org/pdf/2501.05981)  

**Abstract**: Hallucination in large language models (LLMs) remains a significant challenge for their safe deployment, particularly due to its potential to spread misinformation. Most existing solutions address this challenge by focusing on aligning the models with credible sources or by improving how models communicate their confidence (or lack thereof) in their outputs. While these measures may be effective in most contexts, they may fall short in scenarios requiring more nuanced approaches, especially in situations where access to accurate data is limited or determining credible sources is challenging. In this study, we take North Korea - a country characterised by an extreme lack of reliable sources and the prevalence of sensationalist falsehoods - as a case study. We explore and evaluate how some of the best-performing multilingual LLMs and specific language-based models generate information about North Korea in three languages spoken in countries with significant geo-political interests: English (United States, United Kingdom), Korean (South Korea), and Mandarin Chinese (China). Our findings reveal significant differences, suggesting that the choice of model and language can lead to vastly different understandings of North Korea, which has important implications given the global security challenges the country poses. 

**Abstract (ZH)**: 大型语言模型（LLMs）中的幻觉仍然是其安全部署中的一个重大挑战，尤其是在其有可能传播虚假信息的情况下。目前大多数现有的解决方案主要集中在使模型与可信赖的来源保持一致或通过提高模型对其输出的信心（或缺乏信心）的表达来解决这一挑战。虽然这些措施在大多数情况下可能有效，但在需要更细致方法的场景中，特别是在获取准确数据受限或识别可信来源困难的情况下，这些措施可能收效甚微。本研究以朝鲜为例——这是一个极度缺乏可靠信息来源且存在大量耸人听闻的谬误的国家——作为案例研究。我们探讨并评估了部分表现最佳的多语言LLMs和特定语言模型如何用英语（美国、英国）、韩语（韩国）和普通话（中国）三种语言生成关于朝鲜的信息。我们的研究发现表明，所选择的模型和语言可以导致对朝鲜截然不同的理解，这对于考虑到该国在全球安全挑战中的作用尤为重要。 

---
# Finnish SQuAD: A Simple Approach to Machine Translation of Span Annotations 

**Title (ZH)**: 芬兰SQuAD：一种简单的机器翻译断言注解方法

注释：这里的“SQuAD”可能是指Stanford Question Answering Dataset的缩写，在机器学习和自然语言处理领域，SQuAD是一种广泛使用的机器阅读理解数据集。因此，如果这是指一个为SQuAD创建的特定于芬兰语的版本或相关工作，翻译时也可以保持SQuAD的缩写形式，具体如下：

芬兰SQuAD：SQuAD语料在断言注解机器翻译中的简单方法 

**Authors**: Emil Nuutinen, Iiro Rastas, Filip Ginter  

**Link**: [PDF](https://arxiv.org/pdf/2501.05963)  

**Abstract**: We apply a simple method to machine translate datasets with span-level annotation using the DeepL MT service and its ability to translate formatted documents. Using this method, we produce a Finnish version of the SQuAD2.0 question answering dataset and train QA retriever models on this new dataset. We evaluate the quality of the dataset and more generally the MT method through direct evaluation, indirect comparison to other similar datasets, a backtranslation experiment, as well as through the performance of downstream trained QA models. In all these evaluations, we find that the method of transfer is not only simple to use but produces consistently better translated data. Given its good performance on the SQuAD dataset, it is likely the method can be used to translate other similar span-annotated datasets for other tasks and languages as well. All code and data is available under an open license: data at HuggingFace TurkuNLP/squad_v2_fi, code on GitHub TurkuNLP/squad2-fi, and model at HuggingFace TurkuNLP/bert-base-finnish-cased-squad2. 

**Abstract (ZH)**: 我们使用DeepL MT服务及其处理格式化文档的能力，应用了一个简单的机器翻译方法，将带有 span 级标注的数据集翻译成另一种语言。通过这种方法，我们生成了SQuAD2.0问答数据集的芬兰语版本，并在该新数据集上训练了 QA 检索模型。我们通过直接评估、间接与类似数据集的比较、回译实验以及下游训练的问答模型的表现等多方面，评估了该数据集和更广泛的机器翻译方法的质量。在所有这些评估中，我们发现这种方法不仅使用简单，而且能够稳定地生成质量更高的翻译数据。鉴于其在SQuAD数据集上的良好表现，该方法很可能可以用于翻译其他类似 span 标注的数据集，应用于其他任务和语言。所有代码和数据均在开放许可下提供：数据可在 HuggingFace TurkuNLP/squad_v2_fi 获取，代码在 GitHub TurkuNLP/squad2-fi，模型在 HuggingFace TurkuNLP/bert-base-finnish-cased-squad2。 

---
# Effective faking of verbal deception detection with target-aligned adversarial attacks 

**Title (ZH)**: 面向目标的对抗攻击在语音欺骗检测中的有效伪造 

**Authors**: Bennett Kleinberg, Riccardo Loconte, Bruno Verschuere  

**Link**: [PDF](https://arxiv.org/pdf/2501.05962)  

**Abstract**: Background: Deception detection through analysing language is a promising avenue using both human judgments and automated machine learning judgments. For both forms of credibility assessment, automated adversarial attacks that rewrite deceptive statements to appear truthful pose a serious threat. Methods: We used a dataset of 243 truthful and 262 fabricated autobiographical stories in a deception detection task for humans and machine learning models. A large language model was tasked to rewrite deceptive statements so that they appear truthful. In Study 1, humans who made a deception judgment or used the detailedness heuristic and two machine learning models (a fine-tuned language model and a simple n-gram model) judged original or adversarial modifications of deceptive statements. In Study 2, we manipulated the target alignment of the modifications, i.e. tailoring the attack to whether the statements would be assessed by humans or computer models. Results: When adversarial modifications were aligned with their target, human (d=-0.07 and d=-0.04) and machine judgments (51% accuracy) dropped to the chance level. When the attack was not aligned with the target, both human heuristics judgments (d=0.30 and d=0.36) and machine learning predictions (63-78%) were significantly better than chance. Conclusions: Easily accessible language models can effectively help anyone fake deception detection efforts both by humans and machine learning models. Robustness against adversarial modifications for humans and machines depends on that target alignment. We close with suggestions on advancing deception research with adversarial attack designs. 

**Abstract (ZH)**: 背景：通过分析语言进行欺骗检测是一种既有前途的方法，可以利用人类判断和自动机器学习判断。无论是哪种形式的可信度评估，自动化的对抗性攻击都可以通过改写欺骗性陈述使其看似真实，从而构成严重威胁。

方法：我们使用了一个包含243篇真实陈述和262篇编造的自传体故事的数据集，用于人类和机器学习模型的欺骗检测任务。一个大型语言模型被指派改写欺骗性陈述，使其看起来真实。在研究1中，人类被要求对原始或对抗性修改的欺骗性陈述进行欺骗判断或使用详细性启发法，并且使用了两个机器学习模型（一个微调的语言模型和一个简单的n-克隆模型）进行判断。在研究2中，我们操控了修改的目标对齐度，即针对是否由人类或计算机模型评估进行攻击调整。

结果：当对抗性修改与目标对齐时，人类（d=-0.07和d=-0.04）和机器判断（51%的准确性）均下降至随机水平。当攻击未对齐目标时，人类启发式判断（d=0.30和d=0.36）和机器学习预测（63-78%的准确率）均显著高于随机水平。

结论：易于获取的语言模型可以有效地帮助任何人通过人类和机器学习模型来进行欺骗检测的欺诈行为。人类和机器对抗性修改的鲁棒性取决于目标对齐度。我们提出了有关利用对抗性攻击设计推进欺骗研究的建议。 

---
# Universal-2-TF: Robust All-Neural Text Formatting for ASR 

**Title (ZH)**: 通用2-TF：鲁棒的全神经文本格式化在ASR中的应用 

**Authors**: Yash Khare, Taufiquzzaman Peyash, Andrea Vanzo, Takuya Yoshioka  

**Link**: [PDF](https://arxiv.org/pdf/2501.05948)  

**Abstract**: This paper introduces an all-neural text formatting (TF) model designed for commercial automatic speech recognition (ASR) systems, encompassing punctuation restoration (PR), truecasing, and inverse text normalization (ITN). Unlike traditional rule-based or hybrid approaches, this method leverages a two-stage neural architecture comprising a multi-objective token classifier and a sequence-to-sequence (seq2seq) model. This design minimizes computational costs and reduces hallucinations while ensuring flexibility and robustness across diverse linguistic entities and text domains. Developed as part of the Universal-2 ASR system, the proposed method demonstrates superior performance in TF accuracy, computational efficiency, and perceptual quality, as validated through comprehensive evaluations using both objective and subjective methods. This work underscores the importance of holistic TF models in enhancing ASR usability in practical settings. 

**Abstract (ZH)**: 本文介绍了一种专为商用自动语音识别（ASR）系统设计的全部基于神经网络的文本格式化（TF）模型，该模型涵盖了标点符号恢复（PR）、真实大小写转换（Truecasing）和逆文本规范化（ITN）。不同于传统的基于规则或混合方法，该方法采用了一种基于两阶段神经架构的设计，包括一个多目标标记分类器和一个序列到序列（seq2seq）模型。这种设计在减少计算成本和降低幻觉现象的同时，确保了在不同语言实体和文本领域中的灵活性和鲁棒性。作为Universal-2 ASR系统的部分开发内容，所提出的方法在文本格式化准确度、计算效率和感知质量方面表现优异，这通过全面的客观和主观评估得到了验证。本文强调了全面的文本格式化模型在提高ASR实用性和适用性方面的的重要性。 

---
# LLMs Reproduce Stereotypes of Sexual and Gender Minorities 

**Title (ZH)**: LLMs再生产性少数性和性别少数群体的刻板印象 

**Authors**: Ruby Ostrow, Adam Lopez  

**Link**: [PDF](https://arxiv.org/pdf/2501.05926)  

**Abstract**: A large body of research has found substantial gender bias in NLP systems. Most of this research takes a binary, essentialist view of gender: limiting its variation to the categories _men_ and _women_, conflating gender with sex, and ignoring different sexual identities. But gender and sexuality exist on a spectrum, so in this paper we study the biases of large language models (LLMs) towards sexual and gender minorities beyond binary categories. Grounding our study in a widely used psychological framework -- the Stereotype Content Model -- we demonstrate that English-language survey questions about social perceptions elicit more negative stereotypes of sexual and gender minorities from LLMs, just as they do from humans. We then extend this framework to a more realistic use case: text generation. Our analysis shows that LLMs generate stereotyped representations of sexual and gender minorities in this setting, raising concerns about their capacity to amplify representational harms in creative writing, a widely promoted use case. 

**Abstract (ZH)**: 大量的研究已经发现了自然语言处理（NLP）系统中存在显著的性别偏见。大多数此类研究采取的是二元（二分）和本质主义（essentialist）的观点，将性别限制在男性和女性两个类别中，将性别与生物学性别混为一谈，并忽略了不同的性取向和性别认同。然而，性别和性取向是一条连续谱，因此在这篇论文中，我们研究了大型语言模型（LLMs）对超越二元分类的性取向和性别少数群体的偏见。基于广泛采用的心理学框架——刻板印象内容模型（Stereotype Content Model），我们表明，使用英语进行的社会认知调查问卷更倾向于从LLMs中唤起对性取向和性别少数群体的负面刻板印象，就像人类一样。随后，我们将这一框架扩展到更为实际的应用场景：文本生成。我们的分析表明，在这种情况下，LLMs生成了对性取向和性别少数群体的刻板印象表示，这引起了对其在创造性写作中放大代表性伤害能力的担忧，而创造性写作是广泛倡导的应用场景之一。 

---
# Navigating Tomorrow: Reliably Assessing Large Language Models Performance on Future Event Prediction 

**Title (ZH)**: 导航未来：可靠评估大规模语言模型在预测未来事件方面的性能 

**Authors**: Petraq Nako, Adam Jatowt  

**Link**: [PDF](https://arxiv.org/pdf/2501.05925)  

**Abstract**: Predicting future events is an important activity with applications across multiple fields and domains. For example, the capacity to foresee stock market trends, natural disasters, business developments, or political events can facilitate early preventive measures and uncover new opportunities. Multiple diverse computational methods for attempting future predictions, including predictive analysis, time series forecasting, and simulations have been proposed. This study evaluates the performance of several large language models (LLMs) in supporting future prediction tasks, an under-explored domain. We assess the models across three scenarios: Affirmative vs. Likelihood questioning, Reasoning, and Counterfactual analysis. For this, we create a dataset1 by finding and categorizing news articles based on entity type and its popularity. We gather news articles before and after the LLMs training cutoff date in order to thoroughly test and compare model performance. Our research highlights LLMs potential and limitations in predictive modeling, providing a foundation for future improvements. 

**Abstract (ZH)**: 预测未来事件是一项重要的活动，具有跨多个领域和行业的广泛应用。例如，预见股市走势、自然灾害、企业发展或政治事件的能力可以促进早期预防措施并发现新的机遇。多种不同的计算方法被提出以尝试进行未来预测，包括预测分析、时间序列预测和模拟等。本研究评估了几种大规模语言模型（LLMs）在支持未来预测任务中的表现，这是一个尚未广泛探索的领域。我们通过基于实体类型及其流行度来查找并分类新闻文章来构建数据集，并收集了LLMs训练截止日期前后发布的新闻文章，以全面测试和比较模型性能。我们的研究突出了LLMs在预测建模中的潜力和局限性，为未来改进奠定了基础。 

---
# Affordably Fine-tuned LLMs Provide Better Answers to Course-specific MCQs 

**Title (ZH)**: 经济实惠地微调的大型语言模型提供了更好的课程特定选择题答案 

**Authors**: Bianca Raimondi, Saverio Giallorenzo, Maurizio Gabbrielli  

**Link**: [PDF](https://arxiv.org/pdf/2501.05891)  

**Abstract**: In education, the capability of generating human-like text of Large Language Models (LLMs) inspired work on how they can increase the efficiency of learning and teaching. We study the affordability of these models for educators and students by investigating how LLMs answer multiple-choice questions (MCQs) with respect to hardware constraints and refinement techniques. We explore this space by using generic pre-trained LLMs (the 7B, 13B, and 70B variants of LLaMA-2) to answer 162 undergraduate-level MCQs from a course on Programming Languages (PL) -- the MCQ dataset is a contribution of this work, which we make publicly available. Specifically, we dissect how different factors, such as using readily-available material -- (parts of) the course's textbook -- for fine-tuning and quantisation (to decrease resource usage) can change the accuracy of the responses. The main takeaway is that smaller textbook-based fine-tuned models outperform generic larger ones (whose pre-training requires conspicuous resources), making the usage of LLMs for answering MCQs resource- and material-wise affordable. 

**Abstract (ZH)**: 在教育领域，大型语言模型（LLMs）生成类人类文本的能力激发了它们如何能提高学习和教学效率的研究。我们通过探讨硬件限制和改进技术，研究这些模型对教育工作者和学生来说的经济性。我们使用通用预训练的LLM（LLaMA-2 7B、13B和70B变体）来回答一门编程语言（PL）课程中的162道本科水平的多项选择题（MCQs），并因此构建了一个MCQ数据集，该数据集已公开提供。具体来说，我们分析了使用现成的课程教材的部分内容进行微调和量化（以减少资源使用）等因素如何影响模型的响应准确性。主要结论是，基于教材的较小模型的性能优于通用的大型模型（其预训练需要大量资源），这使得使用LLMs回答MCQs从资源和材料的角度来看是可行且经济的。 

---
# ConSim: Measuring Concept-Based Explanations' Effectiveness with Automated Simulatability 

**Title (ZH)**: ConSim：基于概念的解释的自动可模拟性评估方法 

**Authors**: Antonin Poché, Alon Jacovi, Agustin Martin Picard, Victor Boutin, Fanny Jourdan  

**Link**: [PDF](https://arxiv.org/pdf/2501.05855)  

**Abstract**: Concept-based explanations work by mapping complex model computations to human-understandable concepts. Evaluating such explanations is very difficult, as it includes not only the quality of the induced space of possible concepts but also how effectively the chosen concepts are communicated to users. Existing evaluation metrics often focus solely on the former, neglecting the latter. We introduce an evaluation framework for measuring concept explanations via automated simulatability: a simulator's ability to predict the explained model's outputs based on the provided explanations. This approach accounts for both the concept space and its interpretation in an end-to-end evaluation. Human studies for simulatability are notoriously difficult to enact, particularly at the scale of a wide, comprehensive empirical evaluation (which is the subject of this work). We propose using large language models (LLMs) as simulators to approximate the evaluation and report various analyses to make such approximations reliable. Our method allows for scalable and consistent evaluation across various models and datasets. We report a comprehensive empirical evaluation using this framework and show that LLMs provide consistent rankings of explanation methods. Code available at this https URL 

**Abstract (ZH)**: 基于概念的解释通过将复杂的模型计算映射到人类可理解的概念来工作。评估这种解释非常困难，因为它不仅涉及生成的概念空间的质量，还包括所选概念向用户传达的效果。现有的评估指标往往只关注前者，忽视了后者。我们引入了一种基于自动仿真性测量概念解释的评估框架：仿真器根据提供的解释预测解释模型输出的能力。这种方法在端到端的评估中考虑了概念空间及其解释。在大规模、全面的实证评估中（这是本工作的内容），使人类实现仿真性研究尤为困难。我们提出使用大规模语言模型（LLMs）作为仿真器来近似评估，并报告各种分析以确保这种近似可靠。我们的方法可以在各种模型和数据集上实现可扩展且一致的评估。我们使用该框架进行了一项全面的实证评估，并证明LLMs可以一致地评估解释方法的效果。代码可在此处访问：https://github.com/... 

---
# IndoNLP 2025: Shared Task on Real-Time Reverse Transliteration for Romanized Indo-Aryan languages 

**Title (ZH)**: IndoNLP 2025：罗马化印欧语系语言实时逆转写共享任务 

**Authors**: Deshan Sumanathilaka, Isuri Anuradha, Ruvan Weerasinghe, Nicholas Micallef, Julian Hough  

**Link**: [PDF](https://arxiv.org/pdf/2501.05816)  

**Abstract**: The paper overviews the shared task on Real-Time Reverse Transliteration for Romanized Indo-Aryan languages. It focuses on the reverse transliteration of low-resourced languages in the Indo-Aryan family to their native scripts. Typing Romanized Indo-Aryan languages using ad-hoc transliterals and achieving accurate native scripts are complex and often inaccurate processes with the current keyboard systems. This task aims to introduce and evaluate a real-time reverse transliterator that converts Romanized Indo-Aryan languages to their native scripts, improving the typing experience for users. Out of 11 registered teams, four teams participated in the final evaluation phase with transliteration models for Sinhala, Hindi and Malayalam. These proposed solutions not only solve the issue of ad-hoc transliteration but also empower low-resource language usability in the digital arena. 

**Abstract (ZH)**: 本文概述了关于实时逆向转写（Real-Time Reverse Transliteration）罗马化印欧语到其本土脚本的共享任务。该任务集中于将罗马化的印欧语系低资源语言转换为其本土脚本。目前的键盘系统使用临时转写工具输入罗马化的印欧语语言，并将其转换为准确的本土脚本是一个复杂且通常不准确的过程。此任务旨在引入并评估一种实时逆向转写器，能够将罗马化的印欧语转换为其本土脚本，从而改善用户的打字体验。在11支注册队伍中，有四支队伍在最终评估阶段参与，其中包括斯里兰卡语（Sinhala）、印地语（Hindi）和马拉雅拉姆语（Malayalam）的转写模型。提出的解决方案不仅解决了临时转写的问题，也提升了低资源语言在数字领域的可用性。 

---
# Migician: Revealing the Magic of Free-Form Multi-Image Grounding in Multimodal Large Language Models 

**Title (ZH)**: 《Migician：揭示多模态大型语言模型中自由形式多图像 grounding 的魔力》 

**Authors**: You Li, Heyu Huang, Chi Chen, Kaiyu Huang, Chao Huang, Zonghao Guo, Zhiyuan Liu, Jinan Xu, Yuhua Li, Ruixuan Li, Maosong Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.05767)  

**Abstract**: The recent advancement of Multimodal Large Language Models (MLLMs) has significantly improved their fine-grained perception of single images and general comprehension across multiple images. However, existing MLLMs still face challenges in achieving precise grounding in complex multi-image scenarios. To address this, we first explore a Chain-of-Thought (CoT) framework that integrates single-image grounding with multi-image comprehension. While partially effective, it remains unstable and struggles to capture abstract visual information due to its non-end-to-end nature. Therefore, we introduce Migician, the first multi-image grounding model capable of performing free-form and accurate grounding across multiple images. To support this, we present the MGrounding-630k dataset, which comprises data for several multi-image grounding tasks derived from existing datasets, along with newly generated free-form grounding instruction-following data. Furthermore, we propose MIG-Bench, a comprehensive benchmark specifically designed for evaluating multi-image grounding capabilities. Experimental results demonstrate that our model achieves significantly superior multi-image grounding capabilities, outperforming the best existing MLLMs by 21.61% and even surpassing much larger 70B models. Our code, model, dataset, and benchmark are fully open-sourced. 

**Abstract (ZH)**: 近年来，多模态大规模语言模型（MLLMs）在单图像的细粒度感知和多图像的一般理解方面取得了显著进步。然而，现有的MLLMs在复杂多图像场景下的精准定位方面仍面临挑战。为解决这一问题，我们首先探索将单图像定位与多图像理解结合的链式思考（CoT）框架。虽然部分有效，但由于其非端到端的特性，该框架仍不稳定，并且难以捕捉抽象的视觉信息。因此，我们提出了Migician，这是首个能够跨多个图像进行自由形式和准确定位的多图像定位模型。为此，我们发布了MGrounding-630k数据集，该数据集包含来自现有数据集的多种多图像定位任务的数据，以及新生成的自由形式的定位指令遵循数据。此外，我们还提出了MIG-Bench，这是一个全面的基准，专门用于评估多图像定位能力。实验结果表明，我们的模型在多图像定位能力方面取得了显著优越的表现，相较于现有的最佳MLLMs提高了21.61%，甚至超越了更庞大的70B模型。我们的代码、模型、数据集和基准均已开源。 

---
# Controlling Large Language Models Through Concept Activation Vectors 

**Title (ZH)**: 通过概念激活向量控制大型语言模型 

**Authors**: Hanyu Zhang, Xiting Wang, Chengao Li, Xiang Ao, Qing He  

**Link**: [PDF](https://arxiv.org/pdf/2501.05764)  

**Abstract**: As large language models (LLMs) are widely deployed across various domains, the ability to control their generated outputs has become more critical. This control involves aligning LLMs outputs with human values and ethical principles or customizing LLMs on specific topics or styles for individual users. Existing controlled generation methods either require significant computational resources and extensive trial-and-error or provide coarse-grained control. In this paper, we propose Generation with Concept Activation Vector (GCAV), a lightweight model control framework that ensures accurate control without requiring resource-extensive fine-tuning. Specifically, GCAV first trains a concept activation vector for specified concepts to be controlled, such as toxicity. During inference, GCAV steers the concept vector in LLMs, for example, by removing the toxicity concept vector from the activation layers. Control experiments from different perspectives, including toxicity reduction, sentiment control, linguistic style, and topic control, demonstrate that our framework achieves state-of-the-art performance with granular control, allowing for fine-grained adjustments of both the steering layers and the steering magnitudes for individual samples. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在各个领域中的广泛应用，对其生成输出的控制能力变得越来越重要。这种控制涉及将LLMs的输出与人类价值观和伦理原则对齐，或者针对特定主题或风格对LLMs进行个性化定制。现有的控制生成方法要么需要大量的计算资源和广泛的试错，要么提供的控制粒度较粗。本文提出了一种名为Concept Activation Vector生成（GCAV）的轻量级模型控制框架，该框架确保了精确控制，而无需进行资源密集型的微调。具体来说，GCAV首先为需要控制的概念（如毒性）训练一个概念激活向量，在推理过程中，GCAV通过从激活层中移除相应概念的向量等方式来引导这些概念。从减少毒性、控制情感、语言风格和主题控制等多个角度进行的控制实验表明，我们的框架实现了最先进的性能，并且具有细粒度控制能力，允许对操作层和控制幅度进行个体样本级别的精细调整。 

---
# Bridging Dialects: Translating Standard Bangla to Regional Variants Using Neural Models 

**Title (ZH)**: 方言桥梁：使用神经模型将标准孟加拉语翻译为区域变体 

**Authors**: Md. Arafat Alam Khandaker, Ziyan Shirin Raha, Bidyarthi Paul, Tashreef Muhammad  

**Link**: [PDF](https://arxiv.org/pdf/2501.05749)  

**Abstract**: The Bangla language includes many regional dialects, adding to its cultural richness. The translation of Bangla Language into regional dialects presents a challenge due to significant variations in vocabulary, pronunciation, and sentence structure across regions like Chittagong, Sylhet, Barishal, Noakhali, and Mymensingh. These dialects, though vital to local identities, lack of representation in technological applications. This study addresses this gap by translating standard Bangla into these dialects using neural machine translation (NMT) models, including BanglaT5, mT5, and mBART50. The work is motivated by the need to preserve linguistic diversity and improve communication among dialect speakers. The models were fine-tuned using the "Vashantor" dataset, containing 32,500 sentences across various dialects, and evaluated through Character Error Rate (CER) and Word Error Rate (WER) metrics. BanglaT5 demonstrated superior performance with a CER of 12.3% and WER of 15.7%, highlighting its effectiveness in capturing dialectal nuances. The outcomes of this research contribute to the development of inclusive language technologies that support regional dialects and promote linguistic diversity. 

**Abstract (ZH)**: 孟加拉语包含许多地区方言，增加了它的文化多样性。将孟加拉语翻译为地区方言面临着挑战，因为不同地区如恰詼江、锡乐、巴里谢尔、诺阿克查利和摩木林吉的词汇、发音和句法结构存在显著差异。这些方言尽管对于地方身份至关重要，但在技术应用中却缺乏代表性。本研究旨在通过使用神经机器翻译（NMT）模型（包括BanglaT5、mT5和mBART50）将标准孟加拉语翻译为这些方言，填补这一空白。本研究的动机是保存语言多样性，并提高方言使用者之间的沟通。研究中使用了包含各种方言共32,500句话的“瓦什托尼尔”数据集，并通过字符错误率（CER）和词错误率（WER）指标进行了评估。BanglaT5表现出更优的性能，CER为12.3%，WER为15.7%，突显了其在捕捉方言细微差别方面的有效性。本研究的结果有助于开发支持地区方言的包容性语言技术，并促进语言多样性的发展。 

---
# Enabling Scalable Oversight via Self-Evolving Critic 

**Title (ZH)**: 通过自我进化的评论者实现 scalable 监督 

**Authors**: Zhengyang Tang, Ziniu Li, Zhenyang Xiao, Tian Ding, Ruoyu Sun, Benyou Wang, Dayiheng Liu, Fei Huang, Tianyu Liu, Bowen Yu, Junyang Lin  

**Link**: [PDF](https://arxiv.org/pdf/2501.05727)  

**Abstract**: Despite their remarkable performance, the development of Large Language Models (LLMs) faces a critical challenge in scalable oversight: providing effective feedback for tasks where human evaluation is difficult or where LLMs outperform humans. While there is growing interest in using LLMs for critique, current approaches still rely on human annotations or more powerful models, leaving the issue of enhancing critique capabilities without external supervision unresolved. We introduce SCRIT (Self-evolving CRITic), a framework that enables genuine self-evolution of critique abilities. Technically, SCRIT self-improves by training on synthetic data, generated by a contrastive-based self-critic that uses reference solutions for step-by-step critique, and a self-validation mechanism that ensures critique quality through correction outcomes. Implemented with Qwen2.5-72B-Instruct, one of the most powerful LLMs, SCRIT achieves up to a 10.3\% improvement on critique-correction and error identification benchmarks. Our analysis reveals that SCRIT's performance scales positively with data and model size, outperforms alternative approaches, and benefits critically from its self-validation component. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）表现出色，但其发展面临着可扩展监督的关键挑战：为那些难以进行人类评估或LLMs超越人类的任务提供有效反馈。虽然越来越多的研究正在利用LLMs进行批评，但当前的方法仍然依赖于人工注释或更强大的模型，这使得在缺乏外部监督的情况下增强批评能力的问题仍未解决。我们提出了SCRIT（Self-evolving CRITic）框架，该框架能够真正实现批评能力的自我进化。从技术上讲，SCRIT通过利用基于对比的方法生成的合成数据进行自我改进，这些数据源自一个使用参考解决方案进行逐步批评的自我批评机制，以及一个自我验证机制，该机制通过纠正结果确保批评质量。采用目前最强大的LLM之一Qwen2.5-72B-Instruct实现后，SCRIT在批评-纠正和错误识别基准上的性能提升了10.3%。我们的分析表明，SCRIT的性能随着数据和模型规模的增加而正向扩展，超越了其他替代方法，并且严重受益于其自我验证组件。 

---
# How to Enable Effective Cooperation Between Humans and NLP Models: A Survey of Principles, Formalizations, and Beyond 

**Title (ZH)**: 如何实现人类与自然语言处理模型之间有效的协作：原则、形式化方法及更多方面的综述 

**Authors**: Chen Huang, Yang Deng, Wenqiang Lei, Jiancheng Lv, Tat-Seng Chua, Jimmy Xiangji Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05714)  

**Abstract**: With the advancement of large language models (LLMs), intelligent models have evolved from mere tools to autonomous agents with their own goals and strategies for cooperating with humans. This evolution has birthed a novel paradigm in NLP, i.e., human-model cooperation, that has yielded remarkable progress in numerous NLP tasks in recent years. In this paper, we take the first step to present a thorough review of human-model cooperation, exploring its principles, formalizations, and open challenges. In particular, we introduce a new taxonomy that provides a unified perspective to summarize existing approaches. Also, we discuss potential frontier areas and their corresponding challenges. We regard our work as an entry point, paving the way for more breakthrough research in this regard. 

**Abstract (ZH)**: 随着大规模语言模型（LLMs）的发展，智能模型已从单纯的工具演变为具有自身目标和与人类合作策略的自主代理。这一演变催生了一种新的自然语言处理（NLP）范式，即人类-模型合作，近年来在众多NLP任务中取得了显著进展。在本文中，我们首次对该领域进行了全面回顾，探讨了其原则、形式化方法以及面临的关键挑战。特别地，我们引入了一个新的分类体系，为总结现有方法提供统一视角。此外，我们讨论了潜在的研究前沿领域及其相应的挑战。我们认为，我们的工作是这一领域的入门点，为后续更突破性的研究铺平了道路。 

---
# Multi-Step Reasoning in Korean and the Emergent Mirage 

**Title (ZH)**: 韩语中的多步推理与 emergent mirage 的涌现 

**Authors**: Guijin Son, Hyunwoo Ko, Dasol Choi  

**Link**: [PDF](https://arxiv.org/pdf/2501.05712)  

**Abstract**: We introduce HRMCR (HAE-RAE Multi-Step Commonsense Reasoning), a benchmark designed to evaluate large language models' ability to perform multi-step reasoning in culturally specific contexts, focusing on Korean. The questions are automatically generated via templates and algorithms, requiring LLMs to integrate Korean cultural knowledge into sequential reasoning steps. Consistent with prior observations on emergent abilities, our experiments reveal that models trained on fewer than \(2 \cdot 10^{25}\) training FLOPs struggle to solve any questions, showing near-zero performance. Beyond this threshold, performance improves sharply. State-of-the-art models (e.g., O1) still score under 50\%, underscoring the difficulty of our tasks. Notably, stepwise analysis suggests the observed emergent behavior may stem from compounding errors across multiple steps rather than reflecting a genuinely new capability. We publicly release the benchmark and commit to regularly updating the dataset to prevent contamination. 

**Abstract (ZH)**: 我们将介绍HRMCR（HAE-RAE多步常识推理基准），这是一个用于评估大型语言模型在特定文化背景下进行多步推理能力的基准，重点关注韩国文化。问题通过模板和算法自动生成，要求模型将韩国文化知识整合到连续的推理步骤中。与先前关于涌现能力的观察一致，我们的实验表明，训练参数量少于 \(2 \cdot 10^{25}\) 浮点运算（FLOPs）的模型几乎无法解决任何问题，表现出近零性能。超过这一阈值后，性能急剧提高。最先进的模型（如O1）的得分仍低于50%，突显了我们任务的难度。值得注意的是，逐步分析表明观察到的涌现行为可能是多个步骤中的累积错误导致的，而不是真正的新能力的体现。我们已公开发布该基准，并承诺定期更新数据集以防止数据污染。 

---
# Multiagent Finetuning: Self Improvement with Diverse Reasoning Chains 

**Title (ZH)**: 多智能体微调：通过多样化推理链实现自我提升 

**Authors**: Vighnesh Subramaniam, Yilun Du, Joshua B. Tenenbaum, Antonio Torralba, Shuang Li, Igor Mordatch  

**Link**: [PDF](https://arxiv.org/pdf/2501.05707)  

**Abstract**: Large language models (LLMs) have achieved remarkable performance in recent years but are fundamentally limited by the underlying training data. To improve models beyond the training data, recent works have explored how LLMs can be used to generate synthetic data for autonomous self-improvement. However, successive steps of self-improvement can reach a point of diminishing returns. In this work, we propose a complementary approach towards self-improvement where finetuning is applied to a multiagent society of language models. A group of language models, all starting from the same base model, are independently specialized by updating each one using data generated through multiagent interactions among the models. By training each model on independent sets of data, we illustrate how this approach enables specialization across models and diversification over the set of models. As a result, our overall system is able to preserve diverse reasoning chains and autonomously improve over many more rounds of fine-tuning than single-agent self-improvement methods. We quantitatively illustrate the efficacy of the approach across a wide suite of reasoning tasks. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）在多个任务中取得了显著的性能，但其根本上仍受限于训练数据。为了超越训练数据的限制，近期的研究探索了如何利用LLMs生成合成数据以促进自主自适应。然而，连续的自适应步骤可能会达到边际收益递减的阶段。在本文中，我们提出了一种互补的自适应方法，在该方法中，对多智能体社会中的语言模型进行微调。一群从同一基础模型出发的语言模型通过模型间的多智能体交互生成数据，各自独立地进行专业化训练。通过让每个模型在独立的数据集上进行训练，本文展示了这种方法如何在模型之间实现专业化，并在模型集合中实现多样化。因此，我们的整体系统能够在多轮次的微调中实现更自主的进步，并且比单智能体自适应方法能够进行更多轮次的优化。我们通过广泛的心理任务验证了该方法的有效性。 

---
# Linguistic Entity Masking to Improve Cross-Lingual Representation of Multilingual Language Models for Low-Resource Languages 

**Title (ZH)**: 改进低资源语言多语言语言模型跨语言表示的 Linguistic 实体遮罩 

**Authors**: Aloka Fernando, Surangika Ranathunga  

**Link**: [PDF](https://arxiv.org/pdf/2501.05700)  

**Abstract**: Multilingual Pre-trained Language models (multiPLMs), trained on the Masked Language Modelling (MLM) objective are commonly being used for cross-lingual tasks such as bitext mining. However, the performance of these models is still suboptimal for low-resource languages (LRLs). To improve the language representation of a given multiPLM, it is possible to further pre-train it. This is known as continual pre-training. Previous research has shown that continual pre-training with MLM and subsequently with Translation Language Modelling (TLM) improves the cross-lingual representation of multiPLMs. However, during masking, both MLM and TLM give equal weight to all tokens in the input sequence, irrespective of the linguistic properties of the tokens. In this paper, we introduce a novel masking strategy, Linguistic Entity Masking (LEM) to be used in the continual pre-training step to further improve the cross-lingual representations of existing multiPLMs. In contrast to MLM and TLM, LEM limits masking to the linguistic entity types nouns, verbs and named entities, which hold a higher prominence in a sentence. Secondly, we limit masking to a single token within the linguistic entity span thus keeping more context, whereas, in MLM and TLM, tokens are masked randomly. We evaluate the effectiveness of LEM using three downstream tasks, namely bitext mining, parallel data curation and code-mixed sentiment analysis using three low-resource language pairs English-Sinhala, English-Tamil, and Sinhala-Tamil. Experiment results show that continually pre-training a multiPLM with LEM outperforms a multiPLM continually pre-trained with MLM+TLM for all three tasks. 

**Abstract (ZH)**: 多语言预训练语言模型（multiPLMs）通常是在掩码语言建模（MLM）目标上进行训练的，它们被广泛用于跨语言任务，如双语文本挖掘。然而，这些模型在低资源语言（LRLs）上的表现仍然不佳。为了进一步提高给定multiPLM的语言表示，可以对其进行连续预训练。这种做法被称为连续预训练。先前的研究表明，连续预训练结合MLM和随后的翻译语言建模（TLM）能够改进multiPLMs的跨语言表示。然而，在掩码过程中，无论是MLM还是TLM都会对输入序列中的所有标记赋予相同的权重，不论这些标记的语言特性如何。在这篇论文中，我们提出了一种新颖的掩码策略——语言实体掩码（LEM），用于连续预训练步骤，以进一步改进现有multiPLMs的跨语言表示。与MLM和TLM不同，LEM仅对较高的句子中占主导地位的语言实体类型，如名词、动词和专有名词进行掩码。其次，LEM在语言实体范围内仅对单一标记进行掩码，从而保留更多的上下文信息，而MLM和TLM则随机掩码标记。我们使用英语-僧伽罗语、英语-泰米尔语和僧伽罗语-泰米尔语三种低资源语言对，通过三个下游任务——双语文本挖掘、平行数据整理和代码混合情感分析，评估LEM的有效性。实验结果表明，使用LEM进行连续预训练的multiPLM在所有三个任务中都优于使用MLM+TLM进行连续预训练的multiPLM。 

---
# Cascaded Self-Evaluation Augmented Training for Efficient Multimodal Large Language Models 

**Title (ZH)**: 级联自评估增强训练以提高高效多模态大型语言模型的效果 

**Authors**: Zheqi Lv, Wenkai Wang, Jiawei Wang, Shengyu Zhang, Fei Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.05662)  

**Abstract**: Efficient Multimodal Large Language Models (EMLLMs) have rapidly advanced recently. Incorporating Chain-of-Thought (CoT) reasoning and step-by-step self-evaluation has improved their performance. However, limited parameters often hinder EMLLMs from effectively using self-evaluation during inference. Key challenges include synthesizing evaluation data, determining its quantity, optimizing training and inference strategies, and selecting appropriate prompts.
To address these issues, we introduce Self-Evaluation Augmented Training (SEAT). SEAT uses more powerful EMLLMs for CoT reasoning, data selection, and evaluation generation, then trains EMLLMs with the synthesized data. However, handling long prompts and maintaining CoT reasoning quality are problematic. Therefore, we propose Cascaded Self-Evaluation Augmented Training (Cas-SEAT), which breaks down lengthy prompts into shorter, task-specific cascaded prompts and reduces costs for resource-limited settings. During data synthesis, we employ open-source 7B-parameter EMLLMs and annotate a small dataset with short prompts.
Experiments demonstrate that Cas-SEAT significantly boosts EMLLMs' self-evaluation abilities, improving performance by 19.68%, 55.57%, and 46.79% on the MathVista, Math-V, and We-Math datasets, respectively. Additionally, our Cas-SEAT Dataset serves as a valuable resource for future research in enhancing EMLLM self-evaluation. 

**Abstract (ZH)**: 高效多模态大型语言模型（EMLLMs）最近取得了迅速的进步。引入链式思维（CoT）推理和逐步自我评估提高了其性能。然而，有限的参数往往妨碍EMLLMs在推理过程中有效地利用自我评估。关键挑战包括合成评估数据、确定其数量、优化训练和推理策略，以及选择合适的提示。

为了解决这些问题，我们提出了自我评估增强训练（SEAT）。SEAT 使用更强大的EMLLMs进行CoT推理、数据选择和评估生成，然后使用合成的数据训练EMLLMs。然而，处理长提示并保持CoT推理质量存在困难。因此，我们提出了分步自我评估增强训练（Cas-SEAT），该方法将长提示分解为更短、任务特定的分步提示，以降低资源有限环境下成本。在数据合成过程中，我们使用开源的7B参数EMLLMs，并对短提示进行了标注。

实验表明，Cas-SEAT 显著提高了EMLLMs的自我评估能力，在MathVista、Math-V和We-Math数据集上的表现分别提高了19.68%、55.57%和46.79%。此外，我们提出的Cas-SEAT数据集为未来增强EMLLM自我评估的研究提供了宝贵的资源。 

---
# Iconicity in Large Language Models 

**Title (ZH)**: 大型语言模型中的意象性 

**Authors**: Anna Marklová, Jiří Milička, Leonid Ryvkin, Ľudmila Lacková Bennet, Libuše Kormaníková  

**Link**: [PDF](https://arxiv.org/pdf/2501.05643)  

**Abstract**: Lexical iconicity, a direct relation between a word's meaning and its form, is an important aspect of every natural language, most commonly manifesting through sound-meaning associations. Since Large language models' (LLMs') access to both meaning and sound of text is only mediated (meaning through textual context, sound through written representation, further complicated by tokenization), we might expect that the encoding of iconicity in LLMs would be either insufficient or significantly different from human processing. This study addresses this hypothesis by having GPT-4 generate highly iconic pseudowords in artificial languages. To verify that these words actually carry iconicity, we had their meanings guessed by Czech and German participants (n=672) and subsequently by LLM-based participants (generated by GPT-4 and Claude 3.5 Sonnet). The results revealed that humans can guess the meanings of pseudowords in the generated iconic language more accurately than words in distant natural languages and that LLM-based participants are even more successful than humans in this task. This core finding is accompanied by several additional analyses concerning the universality of the generated language and the cues that both human and LLM-based participants utilize. 

**Abstract (ZH)**: 词义iconicity，即单词的意义与其形式之间的直接关系，是每种自然语言的重要特征，通常表现为声音与意义之间的关联。由于大型语言模型（LLMs）对文本的意义和声音的获取是通过文本上下文（意义）和书面表示（声音）进行的间接获取，并且进一步复杂化了通过分词过程，我们可能预期LLMs中iconicity的编码要么不足，要么与人类处理方式显著不同。本研究通过让GPT-4生成高度iconic的人造语言中的拟造词来验证这一假设。为了验证这些拟造词确实携带iconicity，我们让捷克和德国的参与者（共672人）猜测这些拟造词的意思，并随后让基于LLM的参与者（由GPT-4和Claude 3.5 Sonnet生成）进行猜测。研究结果表明，人类能够比猜测远处自然语言中词的意思更准确地猜测生成的iconic语言中的拟造词的意思，并且基于LLM的参与者在这项任务中更为成功。这一核心发现伴随着关于生成语言的通用性以及人类和基于LLM的参与者所利用的线索的多项附加分析。 

---
# Automating Date Format Detection for Data Visualization 

**Title (ZH)**: 自动化日期格式检测以应用于数据可视化 

**Authors**: Zixuan Liang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05640)  

**Abstract**: Data preparation, specifically date parsing, is a significant bottleneck in analytic workflows. To address this, we present two algorithms, one based on minimum entropy and the other on natural language modeling that automatically derive date formats from string data. These algorithms achieve over 90% accuracy on a large corpus of data columns, streamlining the data preparation process within visualization environments. The minimal entropy approach is particularly fast, providing interactive feedback. Our methods simplify date format extraction, making them suitable for integration into data visualization tools and databases. 

**Abstract (ZH)**: 数据分析准备，特别是日期解析，是分析工作流中的一个显著瓶颈。为了解决这个问题，我们提出了两种算法：一种基于最小熵的方法，另一种基于自然语言建模的方法，用于从字符串数据中自动推导日期格式。这两种算法在大量数据列的数据集上达到了90%以上的准确率，简化了可视化环境中的数据准备过程。最小熵方法特别快速，可以提供交互式的反馈。我们的方法简化了日期格式的提取过程，使其适合集成到数据可视化工具和数据库中。 

---
# The Impact of Model Scaling on Seen and Unseen Language Performance 

**Title (ZH)**: 模型规模对已见和未见语言性能的影响 

**Authors**: Rhitabrat Pokharel, Sina Bagheri Nezhad, Ameeta Agrawal, Suresh Singh  

**Link**: [PDF](https://arxiv.org/pdf/2501.05629)  

**Abstract**: The rapid advancement of Large Language Models (LLMs), particularly those trained on multilingual corpora, has intensified the need for a deeper understanding of their performance across a diverse range of languages and model sizes. Our research addresses this critical need by studying the performance and scaling behavior of multilingual LLMs in text classification and machine translation tasks across 204 languages. We systematically examine both seen and unseen languages across three model families of varying sizes in zero-shot and few-shot settings. Our findings show significant differences in scaling behavior between zero-shot and two-shot scenarios, with striking disparities in performance between seen and unseen languages. Model scale has little effect on zero-shot performance, which remains mostly flat. However, in two-shot settings, larger models show clear linear improvements in multilingual text classification. For translation tasks, however, only the instruction-tuned model showed clear benefits from scaling. Our analysis also suggests that overall resource levels, not just the proportions of pretraining languages, are better predictors of model performance, shedding light on what drives multilingual LLM effectiveness. 

**Abstract (ZH)**: 大型语言模型（LLMs）的 rapid advancement，特别是基于多语种语料库训练的LLMs的进展，加剧了对它们在不同语言和模型规模下的性能理解的需要。我们的研究旨在通过在204种语言下研究多语种LLMs在文本分类和机器翻译任务中的性能和扩展行为，来满足这一关键需求。我们系统地考察了不同规模的三种语言模型家族在零样本和少量样本设置下的表现和扩展行为。研究发现，零样本和两样本设置下的扩展行为存在显著差异，且在已见语言和未见语言之间的性能表现存在明显差异。模型规模对零样本性能的影响较小，该性能保持相对平稳。然而，在两样本设置下，较大的模型在多语种文本分类上表现出明显的线性改进。对于翻译任务，只有指令调整后的模型从扩展中获得了明显的好处。我们的分析还表明，整体资源水平比仅仅是预训练语言的比例更有效地预测模型性能，揭示了多语种LLMs有效性背后的驱动因素。 

---
# Harmonizing Metadata of Language Resources for Enhanced Querying and Accessibility 

**Title (ZH)**: harmonizing 语言资源的元数据以提高查询能力和可访问性 

**Authors**: Zixuan Liang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05606)  

**Abstract**: This paper addresses the harmonization of metadata from diverse repositories of language resources (LRs). Leveraging linked data and RDF techniques, we integrate data from multiple sources into a unified model based on DCAT and META-SHARE OWL ontology. Our methodology supports text-based search, faceted browsing, and advanced SPARQL queries through Linghub, a newly developed portal. Real user queries from the Corpora Mailing List (CML) were evaluated to assess Linghub capability to satisfy actual user needs. Results indicate that while some limitations persist, many user requests can be successfully addressed. The study highlights significant metadata issues and advocates for adherence to open vocabularies and standards to enhance metadata harmonization. This initial research underscores the importance of API-based access to LRs, promoting machine usability and data subset extraction for specific purposes, paving the way for more efficient and standardized LR utilization. 

**Abstract (ZH)**: 本文探讨了语言资源（LRs）多样性存储库中的元数据同步问题。借助链接数据和RDF技术，我们将来自多个数据源的数据整合到一个基于DCAT和META-SHARE OWL本体的统一模型中。我们的方法通过Linghub门户支持基于文本的搜索、分类浏览以及高级SPARQL查询。通过对语料库邮件列表（CML）的真实用户查询进行评估，评估了Linghub的能力以满足实际用户需求。结果表明，虽然存在一些限制，但仍有许多用户请求可以通过Linghub得到满意解决。研究突出了显著的元数据问题，并提倡遵循开源词汇表和标准以提高元数据同步。初步研究强调了基于API的LR访问的重要性，促进了机器使用友好性和特定目的下的数据子集提取，为更高效和标准化的LR利用奠定了基础。 

---
# Exploring Large Language Models for Translating Romanian Computational Problems into English 

**Title (ZH)**: 探索大型语言模型在将罗马尼亚计算问题翻译成英语中的应用 

**Authors**: Adrian Marius Dumitran, Adrian-Catalin Badea, Stefan-Gabriel Muscalu, Angela-Liliana Dumitran, Stefan-Cosmin Dascalescu, Radu-Sebastian Amarie  

**Link**: [PDF](https://arxiv.org/pdf/2501.05601)  

**Abstract**: Recent studies have suggested that large language models (LLMs) underperform on mathematical and computer science tasks when these problems are translated from Romanian into English, compared to their original Romanian format. Accurate translation is critical for applications ranging from automatic translations in programming competitions to the creation of high-quality educational materials, as well as minimizing errors or fraud in human translations. This study shows that robust large language models (LLMs) can maintain or even enhance their performance in translating less common languages when given well-structured prompts. Our findings suggest that LLMs, with appropriate supervision, can be reliably used for the automatic translation of IOI (International Olympiad in Informatics)-style tasks. We evaluate several translation methods across multiple LLMs, including OpenRoLLM, Llama 3.1 8B, Llama 3.2 3B and GPT-4o, assessing their translation accuracy and performance stability through repeated runs. Additionally, we augment the OJI (Romanian County-Level Informatics Olympiad) Romanian dataset with accurate English translations, enhancing its utility for future LLM training and evaluation. Through detailed syntactic and semantic analyses, we confirm that with human oversight, LLMs can serve as a viable solution for multilingual problem-solving. We also compare the translation quality of LLMs against human translators, as evaluated by a certified expert, underscoring the potential of LLMs in realworld scenarios. 

**Abstract (ZH)**: 近年来的研究表明，当数学和计算机科学问题从罗马尼亚语翻译成英语时，大型语言模型（LLMs）的表现逊于其原始的罗马尼亚语格式。准确的翻译对于编程竞赛中的自动翻译、高质量教育资源的创建以及减少人工翻译中的错误或欺诈至关重要。本研究展示了，在给定良好结构的提示时，强大的LLMs可以在翻译较不常见的语言时维持甚至增强其性能。我们的研究结果表明，在适当的监督下，LLMs可以可靠地用于IOI（国际信息学奥林匹克）风格任务的自动翻译。我们评估了几种翻译方法在多个LLMs（包括OpenRoLLM、Llama 3.1 8B、Llama 3.2 3B和GPT-4o）上的表现，通过多次运行评估其翻译准确性和性能稳定性。此外，我们还扩展了OJI（罗马尼亚县级信息学奥林匹克）的罗马尼亚语数据集，增加了准确的英语翻译，增强了其在未来LLM训练和评估中的实用性。通过详细的句法和语义分析，我们确认，在人类监督下，LLMs可以作为一种可行的多语言问题解决解决方案。我们也对比了LLMs与专业人工译者的翻译质量，强调了LLMs在实际应用场景中的潜力。 

---
# LLMQuoter: Enhancing RAG Capabilities Through Efficient Quote Extraction From Large Contexts 

**Title (ZH)**: LLMQuoter：通过高效提取大规模语境中的引用来增强RAG能力 

**Authors**: Yuri Facanha Bezerra, Li Weigang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05554)  

**Abstract**: We introduce LLMQuoter, a lightweight, distillation-based model designed to enhance Retrieval Augmented Generation (RAG) by extracting the most relevant textual evidence for downstream reasoning tasks. Built on the LLaMA-3B architecture and fine-tuned with Low-Rank Adaptation (LoRA) on a 15,000-sample subset of HotpotQA, LLMQuoter adopts a "quote-first-then-answer" strategy, efficiently identifying key quotes before passing curated snippets to reasoning models. This workflow reduces cognitive overhead and outperforms full-context approaches like Retrieval-Augmented Fine-Tuning (RAFT), achieving over 20-point accuracy gains across both small and large language models. By leveraging knowledge distillation from a high-performing teacher model, LLMQuoter achieves competitive results in a resource-efficient fine-tuning setup. It democratizes advanced RAG capabilities, delivering significant performance improvements without requiring extensive model retraining. Our results highlight the potential of distilled quote-based reasoning to streamline complex workflows, offering a scalable and practical solution for researchers and practitioners alike. 

**Abstract (ZH)**: 我们介绍了LLMQuoter，这是一个轻量级的蒸馏模型，旨在通过提取与下游推理由证任务最相关的文本证据来增强检索增强生成（RAG）。该模型基于LLaMA-3B架构，并在HotpotQA的一个包含15,000个样本的子集中使用低秩适应（LoRA）进行了微调。LLMQuoter采用“先引述再回答”的策略，在确定关键引述后，将精炼片段传递给推理模型。这种工作流程降低了认知负担，并在各个方面（无论是小型还是大型语言模型）都超越了全文上下文方法，如检索增强微调（RAFT），实现了超过20个百分点的准确性提升。通过利用高性能教师模型的知识蒸馏，LLMQuoter在资源高效微调设置中取得了竞争力的结果。它使高级RAG能力更加普及，能够在不进行大量模型重新训练的情况下实现显著的性能提升。我们的研究结果突显了知识蒸馏引述推理的潜力，可以通过简化复杂的工作流程来提供一种可扩展且实用的解决方案，对于研究者和实践者都具有重要意义。 

---
# The dynamics of meaning through time: Assessment of Large Language Models 

**Title (ZH)**: 意义随时间的动态演变：大型语言模型的评估 

**Authors**: Mohamed Taher Alrefaie, Fatty Salem, Nour Eldin Morsy, Nada Samir, Mohamed Medhat Gaber  

**Link**: [PDF](https://arxiv.org/pdf/2501.05552)  

**Abstract**: Understanding how large language models (LLMs) grasp the historical context of concepts and their semantic evolution is essential in advancing artificial intelligence and linguistic studies. This study aims to evaluate the capabilities of various LLMs in capturing temporal dynamics of meaning, specifically how they interpret terms across different time periods. We analyze a diverse set of terms from multiple domains, using tailored prompts and measuring responses through both objective metrics (e.g., perplexity and word count) and subjective human expert evaluations. Our comparative analysis includes prominent models like ChatGPT, GPT-4, Claude, Bard, Gemini, and Llama. Findings reveal marked differences in each model's handling of historical context and semantic shifts, highlighting both strengths and limitations in temporal semantic understanding. These insights offer a foundation for refining LLMs to better address the evolving nature of language, with implications for historical text analysis, AI design, and applications in digital humanities. 

**Abstract (ZH)**: 理解大型语言模型（LLMs）如何掌握概念的历史背景及其语义演变，对于推动人工智能和语言学研究至关重要。本研究旨在评估不同LLMs在捕捉意义的 temporal 动态方面的能力，特别是它们如何在不同时间时期解释术语。我们分析了来自多个领域的多种术语，并采用定制的提示和通过客观指标（如困惑度和词数）以及主观的人类专家评估来衡量响应。本研究的比较分析包括著名的模型，如ChatGPT、GPT-4、Claude、Bard、Gemini和Llama。研究发现，每个模型在处理历史背景和语义转变方面存在显著差异，突显了在时间语义理解方面的优势和局限性。这些见解为改进LLMs以更好地应对语言演变奠定了基础，并对历史文本分析、AI设计以及数字人文的应用具有重要意义。 

---
# The more polypersonal the better -- a short look on space geometry of fine-tuned layers 

**Title (ZH)**: 越个性化越好——关于微调层的空间几何结构的简要探讨 

**Authors**: Sergei Kudriashov, Veronika Zykova, Angelina Stepanova, Yakov Raskind, Eduard Klyshinsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.05503)  

**Abstract**: The interpretation of deep learning models is a rapidly growing field, with particular interest in language models. There are various approaches to this task, including training simpler models to replicate neural network predictions and analyzing the latent space of the model. The latter method allows us to not only identify patterns in the model's decision-making process, but also understand the features of its internal structure. In this paper, we analyze the changes in the internal representation of the BERT model when it is trained with additional grammatical modules and data containing new grammatical structures (polypersonality). We find that adding a single grammatical layer causes the model to separate the new and old grammatical systems within itself, improving the overall performance on perplexity metrics. 

**Abstract (ZH)**: 深度学习模型的解释是一个迅速发展的领域，尤其是在语言模型方面引起了广泛关注。为了实现这一目标，有多种方法，包括训练更简单的模型来复制神经网络的预测以及分析模型的潜在空间。后者的方法不仅让我们能够识别模型决策过程中的模式，还能理解其内部结构的特征。在本文中，我们分析了在训练BERT模型时添加额外的语法规则模块和包含新的语法规则数据（如多重人格）时，模型内部表示的变化。我们发现，增加单一的语法规则层使得模型能够在内部分离新的和旧的语法规则系统，从而在困惑度指标方面提高了整体性能。 

---
# Spatial Information Integration in Small Language Models for Document Layout Generation and Classification 

**Title (ZH)**: -small语言模型中空间信息集成在文档布局生成与分类中的应用 

**Authors**: Pablo Melendez, Clemens Havas  

**Link**: [PDF](https://arxiv.org/pdf/2501.05497)  

**Abstract**: Document layout understanding is a field of study that analyzes the spatial arrangement of information in a document hoping to understand its structure and layout. Models such as LayoutLM (and its subsequent iterations) can understand semi-structured documents with SotA results; however, the lack of open semi-structured data is a limitation in itself. While semi-structured data is common in everyday life (balance sheets, purchase orders, receipts), there is a lack of public datasets for training machine learning models for this type of document. In this investigation we propose a method to generate new, synthetic, layout information that can help overcoming this data shortage. According to our results, the proposed method performs better than LayoutTransformer, another popular layout generation method. We also show that, in some scenarios, text classification can improve when supported by bounding box information. 

**Abstract (ZH)**: 文档布局理解是研究领域之一，该领域分析文档中信息的空间排列，旨在理解其结构和布局。如LayoutLM（及其后续迭代版本）这样的模型能够理解半结构化文档，并已达到目前最先进的技术水平；然而，缺乏公开的半结构化数据本身就是一个限制。虽然半结构化数据在日常生活中很常见（如资产负债表、采购订单、收据等），但针对这种类型的文档，缺乏可用于训练机器学习模型的公开数据集。在这项研究中，我们提出了一种生成新的合成布局信息的方法，以克服数据短缺的问题。根据我们的结果，提出的方法在生成布局信息方面优于另一种流行的生成方法LayoutTransformer。此外，我们还表明，在某些情况下，通过使用边界框信息来支持文本分类，可以提高分类性能。 

---
# The Future of AI: Exploring the Potential of Large Concept Models 

**Title (ZH)**: 人工智能的未来：探究大型概念模型的潜力 

**Authors**: Hussain Ahmad, Diksha Goel  

**Link**: [PDF](https://arxiv.org/pdf/2501.05487)  

**Abstract**: The field of Artificial Intelligence (AI) continues to drive transformative innovations, with significant progress in conversational interfaces, autonomous vehicles, and intelligent content creation. Since the launch of ChatGPT in late 2022, the rise of Generative AI has marked a pivotal era, with the term Large Language Models (LLMs) becoming a ubiquitous part of daily life. LLMs have demonstrated exceptional capabilities in tasks such as text summarization, code generation, and creative writing. However, these models are inherently limited by their token-level processing, which restricts their ability to perform abstract reasoning, conceptual understanding, and efficient generation of long-form content. To address these limitations, Meta has introduced Large Concept Models (LCMs), representing a significant shift from traditional token-based frameworks. LCMs use concepts as foundational units of understanding, enabling more sophisticated semantic reasoning and context-aware decision-making. Given the limited academic research on this emerging technology, our study aims to bridge the knowledge gap by collecting, analyzing, and synthesizing existing grey literature to provide a comprehensive understanding of LCMs. Specifically, we (i) identify and describe the features that distinguish LCMs from LLMs, (ii) explore potential applications of LCMs across multiple domains, and (iii) propose future research directions and practical strategies to advance LCM development and adoption. 

**Abstract (ZH)**: 人工智能（AI）领域继续推动着变革性创新，尤其是在对话界面、自动驾驶车辆和智能内容生成方面取得了显著进展。自2022年底ChatGPT发布以来，生成型AI的兴起标志着一个关键时期的到来，大型语言模型（LLMs）这一术语已成为日常生活的一部分。LLMs在文本总结、代码生成和创意写作等任务中展示了卓越的能力。然而，这些模型受到其基于令牌级别的处理的内在限制，这限制了它们进行抽象推理、概念理解以及高效生成长篇内容的能力。为了克服这些限制，Meta引入了大型概念模型（LCMs），代表了从传统基于令牌框架到基于概念框架的重大转变。LCMs以概念作为理解的基本单位，能够实现更高级的语义推理和上下文感知决策。由于对该新兴技术的研究有限，我们的研究旨在通过收集、分析和综合现有灰色文献来弥合知识差距，以全面理解LCMs。具体来说，我们将（i）识别并描述区分LCMs和LLMs的特征，（ii）探索LCMs在多个领域的潜在应用，以及（iii）提出未来的研究方向和实用策略，以促进LCMs的发展和应用。 

---
# S2 Chunking: A Hybrid Framework for Document Segmentation Through Integrated Spatial and Semantic Analysis 

**Title (ZH)**: S2分段：一种结合空间和语义综合分析的文档分段混合框架 

**Authors**: Prashant Verma  

**Link**: [PDF](https://arxiv.org/pdf/2501.05485)  

**Abstract**: Document chunking is a critical task in natural language processing (NLP) that involves dividing a document into meaningful segments. Traditional methods often rely solely on semantic analysis, ignoring the spatial layout of elements, which is crucial for understanding relationships in complex documents. This paper introduces a novel hybrid approach that combines layout structure, semantic analysis, and spatial relationships to enhance the cohesion and accuracy of document chunks. By leveraging bounding box information (bbox) and text embeddings, our method constructs a weighted graph representation of document elements, which is then clustered using spectral clustering. Experimental results demonstrate that this approach outperforms traditional methods, particularly in documents with diverse layouts such as reports, articles, and multi-column designs. The proposed method also ensures that no chunk exceeds a specified token length, making it suitable for use cases where token limits are critical (e.g., language models with input size limitations) 

**Abstract (ZH)**: 文档切块是自然语言处理（NLP）中的一个关键任务，涉及将文档划分为有意义的部分。传统方法通常仅依靠语义分析，而忽略了元素的空间布局，这一点对于理解复杂文档中的关系至关重要。本文提出了一种新颖的混合方法，该方法结合了布局结构、语义分析和空间关系，以提高文档切块的连贯性和准确性。通过利用边界框信息（bbox）和文本嵌入，我们的方法构建了一个表示文档元素的加权图表示，然后使用谱聚类对其进行聚类。实验结果表明，该方法优于传统方法，特别是在报告、文章和多列设计等具有多样化布局的文档中表现出色。所提出的方法还确保每个切块不超过指定的token长度，使其适用于令牌限制至关重要的应用场景（例如，具有输入尺寸限制的语言模型）。 

---
# HP-BERT: A framework for longitudinal study of Hinduphobia on social media via LLMs 

**Title (ZH)**: HP-BERT：通过大语言模型 longitudinally 研究社交媒体上 Hinduphobia 的框架 

**Authors**: Ashutosh Singh, Rohitash Chandra  

**Link**: [PDF](https://arxiv.org/pdf/2501.05482)  

**Abstract**: During the COVID-19 pandemic, community tensions intensified, fuelling Hinduphobic sentiments and discrimination against individuals of Hindu descent within India and worldwide. Large language models (LLMs) have become prominent in natural language processing (NLP) tasks and social media analysis, enabling longitudinal studies of platforms like X (formerly Twitter) for specific issues during COVID-19. We present an abuse detection and sentiment analysis framework that offers a longitudinal analysis of Hinduphobia on X (Twitter) during and after the COVID-19 pandemic. This framework assesses the prevalence and intensity of Hinduphobic discourse, capturing elements such as derogatory jokes and racist remarks through sentiment analysis and abuse detection from pre-trained and fine-tuned LLMs. Additionally, we curate and publish a "Hinduphobic COVID-19 X (Twitter) Dataset" of 8,000 tweets annotated for Hinduphobic abuse detection, which is used to fine-tune a BERT model, resulting in the development of the Hinduphobic BERT (HP-BERT) model. We then further fine-tune HP-BERT using the SenWave dataset for multi-label sentiment analysis. Our study encompasses approximately 27.4 million tweets from six countries, including Australia, Brazil, India, Indonesia, Japan, and the United Kingdom. Our findings reveal a strong correlation between spikes in COVID-19 cases and surges in Hinduphobic rhetoric, highlighting how political narratives, misinformation, and targeted jokes contributed to communal polarisation. These insights provide valuable guidance for developing strategies to mitigate communal tensions in future crises, both locally and globally. We advocate implementing automated monitoring and removal of such content on social media to curb divisive discourse. 

**Abstract (ZH)**: 在COVID-19疫情期间，社区紧张局势加剧，促进了对印度教徒的恐惧情绪和针对印度教背景个体的歧视。大规模语言模型（LLMs）在自然语言处理（NLP）任务和社会媒体分析中发挥了重要作用，使我们能够对诸如X（原名Twitter）等平台在COVID-19疫情期间的特定问题进行纵向研究。我们提出了一种虐待检测和情感分析框架，该框架对X（Twitter）上的印度教恐惧主义进行了纵向分析，涵盖疫情之前和之后的时期。该框架评估了印度教恐惧主义言论的普遍性和强度，通过情感分析和虐待检测利用预训练和微调的LLMs捕捉贬低的笑话和种族主义评论等元素。此外，我们整理并发布了包含8,000条标注了印度教恐惧主义虐待的“印度教恐惧主义COVID-19 X（Twitter）数据集”，用以微调BERT模型，从而开发出印度教恐惧主义BERT（HP-BERT）模型。随后，我们使用SenWave数据集进一步微调HP-BERT，进行多标签情感分析。本研究涵盖了来自六个不同国家（澳大利亚、巴西、印度、印度尼西亚、日本和英国）共计约2740万条推特。研究发现表明，在COVID-19病例激增期间印度教恐惧主义言论的激增之间存在强烈关联，突显了政治叙事、虚假信息和针对印度教徒的针对性笑话在引发社区分裂方面的角色。这些见解提供了宝贵的信息，为企业和组织在未来的危机中制定缓解社区紧张局势的战略提供了指导，无论是在本地还是全球范围内。我们建议实施自动化监控和移除此类内容，以遏制分化性言论。 

---
# The \textit{Questio de aqua et terra}: A Computational Authorship Verification Study 

**Title (ZH)**: 《论水与土的问题》：一篇计算作者身份验证研究 

**Authors**: Martina Leocata, Alejandro Moreo, Fabrizio Sebastiani  

**Link**: [PDF](https://arxiv.org/pdf/2501.05480)  

**Abstract**: The Questio de aqua et terra is a cosmological treatise traditionally attributed to Dante Alighieri. However, the authenticity of this text is controversial, due to discrepancies with Dante's established works and to the absence of contemporary references. This study investigates the authenticity of the Questio via computational authorship verification (AV), a class of techniques which combine supervised machine learning and stylometry. We build a family of AV systems and assemble a corpus of 330 13th- and 14th-century Latin texts, which we use to comparatively evaluate the AV systems through leave-one-out cross-validation. Our best-performing system achieves high verification accuracy (F1=0.970) despite the heterogeneity of the corpus in terms of textual genre. The key contribution to the accuracy of this system is shown to come from Distributional Random Oversampling (DRO), a technique specially tailored to text classification which is here used for the first time in AV.
The application of the AV system to the Questio returns a highly confident prediction concerning its authenticity. These findings contribute to the debate on the authorship of the Questio, and highlight DRO's potential in the application of AV to cultural heritage. 

**Abstract (ZH)**: 《水与土的问题》是传统上归功于但丁·阿利吉耶里的天文学著作。然而，由于该文本与但丁已知的作品存在分歧，并且缺乏同时代的文献引用，其真实性存在争议。本研究通过计算作者身份验证（AV）技术，即结合监督机器学习和语料统计的技术，对《水与土的问题》的真实性进行了调查。我们建立了一系列表征分析系统，并收集了一个由330篇13世纪和14世纪拉丁文文本构成的语料库，以此来比较评估这些AV系统，通过逐一排除交叉验证法进行评估。我们性能最佳的系统在多样性语料库中实现了高验证准确性（F1=0.970）。系统准确性的主要贡献因素被证明是分布随机过采样（DRO）技术，这是一种特别为文本分类设计的技术，在本文中首次将其应用于作者身份验证。

将AV系统应用于《水与土的问题》得出其真实性具有极高的可信度预测。这些发现有助于《水与土的问题》作者身份的辩论，并突显了DRO技术在作者身份验证应用于文化遗产中的潜力。 

---
# Practical Design and Benchmarking of Generative AI Applications for Surgical Billing and Coding 

**Title (ZH)**: 面向外科账单和编码的应用生成型人工智能实用设计与基准测试 

**Authors**: John C. Rollman, Bruce Rogers, Hamed Zaribafzadeh, Daniel Buckland, Ursula Rogers, Jennifer Gagnon, Ozanan Meireles, Lindsay Jennings, Jim Bennett, Jennifer Nicholson, Nandan Lad, Linda Cendales, Andreas Seas, Alessandro Martinino, E. Shelley Hwang, Allan D. Kirk  

**Link**: [PDF](https://arxiv.org/pdf/2501.05479)  

**Abstract**: Background: Healthcare has many manual processes that can benefit from automation and augmentation with Generative Artificial Intelligence (AI), the medical billing and coding process. However, current foundational Large Language Models (LLMs) perform poorly when tasked with generating accurate International Classification of Diseases, 10th edition, Clinical Modification (ICD-10-CM) and Current Procedural Terminology (CPT) codes. Additionally, there are many security and financial challenges in the application of generative AI to healthcare. We present a strategy for developing generative AI tools in healthcare, specifically for medical billing and coding, that balances accuracy, accessibility, and patient privacy.
Methods: We fine tune the PHI-3 Mini and PHI-3 Medium LLMs using institutional data and compare the results against the PHI-3 base model, a PHI-3 RAG application, and GPT-4o. We use the post operative surgical report as input and the patients billing claim the associated ICD-10, CPT, and Modifier codes as the target result. Performance is measured by accuracy of code generation, proportion of invalid codes, and the fidelity of the billing claim format.
Results: Both fine-tuned models performed better or as well as GPT-4o. The Phi-3 Medium fine-tuned model showed the best performance (ICD-10 Recall and Precision: 72%, 72%; CPT Recall and Precision: 77%, 79%; Modifier Recall and Precision: 63%, 64%). The Phi-3 Medium fine-tuned model only fabricated 1% of ICD-10 codes and 0.6% of CPT codes generated.
Conclusions: Our study shows that a small model that is fine-tuned on domain-specific data for specific tasks using a simple set of open-source tools and minimal technological and monetary requirements performs as well as the larger contemporary consumer models. 

**Abstract (ZH)**: 背景：医疗健康领域有许多手动流程，可以通过与生成型人工智能（Generative Artificial Intelligence, AI）相结合实现自动化和增强。医疗账单和编码过程便是其中之一。然而，当前的基础大型语言模型（Large Language Models, LLMs）在生成准确的国际疾病分类第10版临床修改版（International Classification of Diseases, 10th edition, Clinical Modification, ICD-10-CM）和当前程序术语（Current Procedural Terminology, CPT）代码方面表现不佳。此外，在医疗应用中使用生成型AI还存在许多安全和财务挑战。我们提出了一种医疗健康领域（尤其是医疗账单和编码）开发生成型AI工具的策略，该策略平衡了准确性、可访问性和患者隐私。
方法：我们使用机构数据对PHI-3 Mini和PHI-3 Medium LLM进行微调，并将其结果与PHI-3基础模型、PHI-3检索型应用和GPT-4o进行比较。我们使用术后手术报告作为输入，患者的账单索赔相关ICD-10、CPT和修改代码作为目标结果。性能通过代码生成的准确性、无效代码的比例以及账单索赔格式的保真度进行衡量。
结果：两个微调模型的表现均优于或与GPT-4o相当。PHI-3 Medium微调模型表现最佳（ICD-10召回率和精确率：72%，72%；CPT召回率和精确率：77%，79%；修改召回率和精确率：63%，64%）。PHI-3 Medium微调模型仅生成了1%的ICD-10代码和0.6%的CPT代码。
结论：我们的研究表明，一个小规模模型通过使用特定任务的领域特定数据进行微调，并结合简单的一组开源工具和最少的技术及财务要求，可以达到与现代大规模消费型模型相当的表现。 

---
# Language and Planning in Robotic Navigation: A Multilingual Evaluation of State-of-the-Art Models 

**Title (ZH)**: 机器人导航中的语言与规划：对最先进的模型进行多语言评估 

**Authors**: Malak Mansour, Ahmed Aly, Bahey Tharwat, Sarim Hashmi, Dong An, Ian Reid  

**Link**: [PDF](https://arxiv.org/pdf/2501.05478)  

**Abstract**: Large Language Models (LLMs) such as GPT-4, trained on huge amount of datasets spanning multiple domains, exhibit significant reasoning, understanding, and planning capabilities across various tasks. This study presents the first-ever work in Arabic language integration within the Vision-and-Language Navigation (VLN) domain in robotics, an area that has been notably underexplored in existing research. We perform a comprehensive evaluation of state-of-the-art multi-lingual Small Language Models (SLMs), including GPT-4o mini, Llama 3 8B, and Phi-3 medium 14B, alongside the Arabic-centric LLM, Jais. Our approach utilizes the NavGPT framework, a pure LLM-based instruction-following navigation agent, to assess the impact of language on navigation reasoning through zero-shot sequential action prediction using the R2R dataset. Through comprehensive experiments, we demonstrate that our framework is capable of high-level planning for navigation tasks when provided with instructions in both English and Arabic. However, certain models struggled with reasoning and planning in the Arabic language due to inherent limitations in their capabilities, sub-optimal performance, and parsing issues. These findings highlight the importance of enhancing planning and reasoning capabilities in language models for effective navigation, emphasizing this as a key area for further development while also unlocking the potential of Arabic-language models for impactful real-world applications. 

**Abstract (ZH)**: 大型语言模型（LLMs）如GPT-4，在跨多个领域的大量数据集上进行训练，展现出了在各种任务中显著的推理、理解和计划能力。本研究首次将阿拉伯语融入机器人学中的视觉-语言导航（VLN）领域，这一领域在现有研究中鲜有探讨。我们对最先进的多语言小语言模型（SLMs），包括GPT-4o mini、Llama 3 8B和Phi-3中型14B，以及阿拉伯语中心的LLM Jais进行了全面评估。我们的方法利用了NavGPT框架，这是一种完全基于LLM的指令跟随导航代理，通过零样本连续动作预测实验来评估语言对导航推理的影响，测试使用了R2R数据集。通过全面的实验，我们证明了当提供英文和阿拉伯文指令时，我们的框架能够完成高层次的导航任务计划。然而，某些模型在阿拉伯语推理和计划方面遇到了困难，这主要是由于这些模型固有的局限性、性能不佳和解析问题所导致。这些发现强调了增强语言模型的计划和推理能力对于实现有效导航的重要性，指出这是一个需要进一步发展的关键领域，同时也展现了阿拉伯语模型在现实世界应用中的潜在影响力。 

---
# IntegrityAI at GenAI Detection Task 2: Detecting Machine-Generated Academic Essays in English and Arabic Using ELECTRA and Stylometry 

**Title (ZH)**: IntegrityAI在GenAI检测任务2中的应用：利用ELECTRA和文体学识别英文和阿拉伯语文本生成的学术论文 

**Authors**: Mohammad AL-Smadi  

**Link**: [PDF](https://arxiv.org/pdf/2501.05476)  

**Abstract**: Recent research has investigated the problem of detecting machine-generated essays for academic purposes. To address this challenge, this research utilizes pre-trained, transformer-based models fine-tuned on Arabic and English academic essays with stylometric features. Custom models based on ELECTRA for English and AraELECTRA for Arabic were trained and evaluated using a benchmark dataset. Proposed models achieved excellent results with an F1-score of 99.7%, ranking 2nd among of 26 teams in the English subtask, and 98.4%, finishing 1st out of 23 teams in the Arabic one. 

**Abstract (ZH)**: 最近的研究探讨了识别学术用途的机器生成作文的问题。为应对这一挑战，本研究利用预训练的变压器模型，针对阿拉伯语和英语的学术作文进行了微调，并结合了 stylistic 特征。基于 ELECTRA 的定制模型用于英语任务，基于 AraELECTRA 的定制模型用于阿拉伯语任务。这些模型使用基准数据集进行了训练和评估。提出的模型取得了出色的结果，F1 分数达到了 99.7%，在英语子任务中排名第二（26 支队伍中），阿拉伯语子任务中 F1 分数为 98.4%，在 23 支队伍中排名第一。 

---
# Retrieval-Augmented Generation by Evidence Retroactivity in LLMs 

**Title (ZH)**: 基于证据回溯的LLM中检索增强生成 

**Authors**: Liang Xiao, Wen Dai, Shuai Chen, Bin Qin, Chongyang Shi, Haopeng Jing, Tianyu Guo  

**Link**: [PDF](https://arxiv.org/pdf/2501.05475)  

**Abstract**: Retrieval-augmented generation has gained significant attention due to its ability to integrate relevant external knowledge, enhancing the accuracy and reliability of the LLMs' responses. Most of the existing methods apply a dynamic multiple retrieval-generating process, to address multi-hop complex questions by decomposing them into sub-problems. However, these methods rely on an unidirectional forward reasoning paradigm, where errors from insufficient reasoning steps or inherent flaws in current retrieval systems are irreversible, potentially derailing the entire reasoning chain. For the first time, this work introduces Retroactive Retrieval-Augmented Generation (RetroRAG), a novel framework to build a retroactive reasoning paradigm. RetroRAG revises and updates the evidence, redirecting the reasoning chain to the correct direction. RetroRAG constructs an evidence-collation-discovery framework to search, generate, and refine credible evidence. It synthesizes inferential evidence related to the key entities in the question from the existing source knowledge and formulates search queries to uncover additional information. As new evidence is found, RetroRAG continually updates and organizes this information, enhancing its ability to locate further necessary evidence. Paired with an Answerer to generate and evaluate outputs, RetroRAG is capable of refining its reasoning process iteratively until a reliable answer is obtained. Empirical evaluations show that RetroRAG significantly outperforms existing methods. 

**Abstract (ZH)**: 检索增强生成由于其整合相关外部知识的能力，在提高大语言模型（LLM）响应的准确性和可靠性方面获得了广泛关注。目前大多数现有方法采用动态多轮检索-生成过程，通过将多跳复杂问题分解为子问题来解决问题。然而，这些方法依赖于单向前向推理模式，其中由于推理步骤不足或当前检索系统中的内在缺陷导致的错误是不可逆的，可能会导致整个推理链的偏离。首次提出，本工作引入了回溯检索增强生成（RetroRAG），一种新颖的框架以构建回溯推理范式。RetroRAG 能够修正和更新证据，重新引导推理链的方向。RetroRAG 构建了一个证据收集发现框架，用于搜索、生成和完善可信证据。它从现有来源知识中合成与问题关键实体相关的推断性证据，并制定搜索查询以发现额外信息。随着新证据的发现，RetroRAG 不断更新和组织这些信息，增强其定位进一步所需的证据的能力。结合一个回答器生成和评估输出，RetroRAG 能够迭代地改进其推理过程，直到获得可靠的答案。实证评估表明，RetroRAG 显著优于现有方法。 

---
# Modality-Invariant Bidirectional Temporal Representation Distillation Network for Missing Multimodal Sentiment Analysis 

**Title (ZH)**: 针对缺失多模态情感分析的模态不变双向时序表示蒸馏网络 

**Authors**: Xincheng Wang, Liejun Wang, Yinfeng Yu, Xinxin Jiao  

**Link**: [PDF](https://arxiv.org/pdf/2501.05474)  

**Abstract**: Multimodal Sentiment Analysis (MSA) integrates diverse modalities(text, audio, and video) to comprehensively analyze and understand individuals' emotional states. However, the real-world prevalence of incomplete data poses significant challenges to MSA, mainly due to the randomness of modality missing. Moreover, the heterogeneity issue in multimodal data has yet to be effectively addressed. To tackle these challenges, we introduce the Modality-Invariant Bidirectional Temporal Representation Distillation Network (MITR-DNet) for Missing Multimodal Sentiment Analysis. MITR-DNet employs a distillation approach, wherein a complete modality teacher model guides a missing modality student model, ensuring robustness in the presence of modality missing. Simultaneously, we developed the Modality-Invariant Bidirectional Temporal Representation Learning Module (MIB-TRL) to mitigate heterogeneity. 

**Abstract (ZH)**: 多模态情感分析（Multimodal Sentiment Analysis, MSA）结合了多种模态（文本、音频和视频），以全面分析和理解个体的情感状态。然而，现实世界中数据不完整的问题对MSA构成了重大挑战，主要原因是模态缺失的随机性。此外，多模态数据的异质性问题尚未得到有效解决。为应对这些挑战，我们提出了用于缺失多模态情感分析的模态不变双向时间表示蒸馏网络（Modality-Invariant Bidirectional Temporal Representation Distillation Network, MITR-DNet）。MITR-DNet 采用蒸馏方法，由完整的模态教师模型引导缺失模态的学生模型，确保在模态缺失情况下的鲁棒性。同时，我们开发了模态不变双向时间表示学习模块（Modality-Invariant Bidirectional Temporal Representation Learning Module, MIB-TRL），以减轻异质性问题。 

---
# LatteReview: A Multi-Agent Framework for Systematic Review Automation Using Large Language Models 

**Title (ZH)**: LatteReview：使用大规模语言模型进行系统评价自动化的一种多代理框架 

**Authors**: Pouria Rouzrokh, Moein Shariatnia  

**Link**: [PDF](https://arxiv.org/pdf/2501.05468)  

**Abstract**: Systematic literature reviews and meta-analyses are essential for synthesizing research insights, but they remain time-intensive and labor-intensive due to the iterative processes of screening, evaluation, and data extraction. This paper introduces and evaluates LatteReview, a Python-based framework that leverages large language models (LLMs) and multi-agent systems to automate key elements of the systematic review process. Designed to streamline workflows while maintaining rigor, LatteReview utilizes modular agents for tasks such as title and abstract screening, relevance scoring, and structured data extraction. These agents operate within orchestrated workflows, supporting sequential and parallel review rounds, dynamic decision-making, and iterative refinement based on user feedback. LatteReview's architecture integrates LLM providers, enabling compatibility with both cloud-based and locally hosted models. The framework supports features such as Retrieval-Augmented Generation (RAG) for incorporating external context, multimodal reviews, Pydantic-based validation for structured inputs and outputs, and asynchronous programming for handling large-scale datasets. The framework is available on the GitHub repository, with detailed documentation and an installable package. 

**Abstract (ZH)**: 系统文献综述和元分析是综合研究洞察力的重要工具，但由于筛选、评估和数据提取的迭代过程，它们仍耗时且劳动密集。本文介绍了并评估了LatteReview，这是一个基于Python的框架，利用大型语言模型（LLMs）和多智能体系统自动化系统综述过程中的关键要素。设计时旨在简化工作流程同时保持严格性，LatteReview使用模块化的代理程序来执行诸如标题和摘要筛选、相关性评分和结构化数据提取等任务。这些代理程序在协调的流程中运作，支持顺序和并行的审查轮次、动态决策和基于用户反馈的迭代改进。LatteReview的架构整合了LLM提供者，使得既兼容基于云的模型也兼容本地托管的模型。该框架支持诸如检索增强生成（RAG）、多模态审查、基于Pydantic的验证以确保输入和输出的结构化，以及异步编程以处理大规模数据集等功能。该框架在GitHub存储库中可用，配备了详细的文档和可安装的包。 

---
# Small Language Models (SLMs) Can Still Pack a Punch: A survey 

**Title (ZH)**: 小型语言模型（SLMs）依然实力强劲：一个综述 

**Authors**: Shreyas Subramanian, Vikram Elango, Mecit Gungor  

**Link**: [PDF](https://arxiv.org/pdf/2501.05465)  

**Abstract**: As foundation AI models continue to increase in size, an important question arises - is massive scale the only path forward? This survey of about 160 papers presents a family of Small Language Models (SLMs) in the 1 to 8 billion parameter range that demonstrate smaller models can perform as well, or even outperform large models. We explore task agnostic, general purpose SLMs, task-specific SLMs and techniques to create SLMs that can guide the community to build models while balancing performance, efficiency, scalability and cost. Furthermore we define and characterize SLMs' effective sizes, representing increased capability with respect to LLMs. 

**Abstract (ZH)**: 随着基础AI模型的规模不断增大，一个重要的问题随之浮现：大规模是否是唯一的发展路径？本综述研究了大约160篇论文，展示了在1亿到8亿参数范围内的Small Language Models（SLM），证明了较小的模型可以在某些情况下与大型模型表现相当，甚至超越大型模型。我们探讨了适用于各种任务的一般性SLM、针对特定任务的SLM以及创建具有指导意义的SLM的技术，以帮助社区在性能、效率、可扩展性和成本之间进行平衡。此外，我们定义并描述了SLM的有效规模，这代表了与大型语言模型（LLM）相比，SLM增强了的能力。 

---
# LLM-MedQA: Enhancing Medical Question Answering through Case Studies in Large Language Models 

**Title (ZH)**: LLM-MedQA：通过大型语言模型案例研究增强医学问答能力 

**Authors**: Hang Yang, Hao Chen, Hui Guo, Yineng Chen, Ching-Sheng Lin, Shu Hu, Jinrong Hu, Xi Wu, Xin Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05464)  

**Abstract**: Accurate and efficient question-answering systems are essential for delivering high-quality patient care in the medical field. While Large Language Models (LLMs) have made remarkable strides across various domains, they continue to face significant challenges in medical question answering, particularly in understanding domain-specific terminologies and performing complex reasoning. These limitations undermine their effectiveness in critical medical applications. To address these issues, we propose a novel approach incorporating similar case generation within a multi-agent medical question-answering (MedQA) system. Specifically, we leverage the Llama3.1:70B model, a state-of-the-art LLM, in a multi-agent architecture to enhance performance on the MedQA dataset using zero-shot learning. Our method capitalizes on the model's inherent medical knowledge and reasoning capabilities, eliminating the need for additional training data. Experimental results show substantial performance gains over existing benchmark models, with improvements of 7% in both accuracy and F1-score across various medical QA tasks. Furthermore, we examine the model's interpretability and reliability in addressing complex medical queries. This research not only offers a robust solution for medical question answering but also establishes a foundation for broader applications of LLMs in the medical domain. 

**Abstract (ZH)**: 准确且高效的问答系统对于提供高质量的医疗服务至关重要。尽管大型语言模型（LLMs）已经在各个领域取得了显著进展，但在医疗领域的问答任务中，它们仍然面临重大挑战，特别是在理解和处理领域特定术语以及进行复杂推理方面。这些限制削弱了它们在关键医疗应用中的效果。为了解决这些问题，我们提出了一种新颖的方法，即在多智能体医疗问答（MedQA）系统中引入相似病例生成技术。具体而言，我们利用最先进的大型语言模型Llama3.1:70B，在多智能体架构中进行零样本学习，以增强MedQA数据集上的性能。我们的方法充分利用了模型内置的医学知识和推理能力，无需额外的训练数据。实验结果显示，与现有基准模型相比，我们的方法在各种医学问答任务中实现了显著的性能提升，准确率和F1分数分别提高了7%。此外，我们还考察了该模型在处理复杂医学查询时的可解释性和可靠性。这项研究不仅提供了一种稳健的解决方案以应对医学问答任务，还为我们探索大型语言模型在医疗领域的更广泛应用奠定了基础。 

---
# Towards Early Prediction of Self-Supervised Speech Model Performance 

**Title (ZH)**: 面向自监督语音模型性能的早期预测研究 

**Authors**: Ryan Whetten, Lucas Maison, Titouan Parcollet, Marco Dinarelli, Yannick Estève  

**Link**: [PDF](https://arxiv.org/pdf/2501.05966)  

**Abstract**: In Self-Supervised Learning (SSL), pre-training and evaluation are resource intensive. In the speech domain, current indicators of the quality of SSL models during pre-training, such as the loss, do not correlate well with downstream performance. Consequently, it is often difficult to gauge the final downstream performance in a cost efficient manner during pre-training. In this work, we propose unsupervised efficient methods that give insights into the quality of the pre-training of SSL speech models, namely, measuring the cluster quality and rank of the embeddings of the SSL model. Results show that measures of cluster quality and rank correlate better with downstream performance than the pre-training loss with only one hour of unlabeled audio, reducing the need for GPU hours and labeled data in SSL model evaluation. 

**Abstract (ZH)**: 在自监督学习（SSL）中，预训练和评估都需要大量资源。在语音领域，当前用于评估SSL模型预训练质量的指标，如损失值，并不能很好地与下游性能相关联。因此，在预训练过程中以经济高效的方式评估最终的下游性能往往颇具挑战性。在这项工作中，我们提出了一种无监督的有效方法，用于揭示SSL语音模型预训练质量，具体包括测量SSL模型的嵌入向量的聚类质量和排名。结果表明，使用仅一小时的未标记音频就可以使聚类质量和排名的度量与下游性能之间的相关性优于预训练损失，从而减少了在SSL模型评估中对GPU时间和标记数据的需求。 

---
# Scalable Vision Language Model Training via High Quality Data Curation 

**Title (ZH)**: 通过高质量数据整理实现可扩展的视觉语言模型训练 

**Authors**: Hongyuan Dong, Zijian Kang, Weijie Yin, Xiao Liang, Chao Feng, Jiao Ran  

**Link**: [PDF](https://arxiv.org/pdf/2501.05952)  

**Abstract**: In this paper, we introduce SAIL-VL (ScAlable Vision Language Model TraIning via High QuaLity Data Curation), an open-source vision language model (VLM) of state-of-the-art (SOTA) performance with 2B parameters. We introduce three key improvements that contribute to SAIL-VL's leading performance: (1) Scalable high-quality visual understanding data construction: We implement a visual understanding data construction pipeline, which enables hundred-million-scale high-quality recaption data annotation. Equipped with this pipeline, we curate SAIL-Caption, a large-scale caption dataset with large quantity and the highest data quality compared with opensource caption datasets. (2) Scalable Pretraining with High-Quality Visual Understanding Data: We scale SAIL-VL's pretraining budget up to 131B tokens and show that even a 2B VLM benefits from scaled up training data sizes, exhibiting expected data size scaling laws in visual understanding and instruction following performance. (3) Scalable SFT via quantity and quality scaling: We introduce general guidance for instruction data curation to scale up instruction data continuously, allowing us to construct a large SFT dataset with the highest quality. To further improve SAIL-VL's performance, we propose quality scaling, a multi-stage training recipe with curriculum learning, to improve model performance scaling curves w.r.t. data sizes from logarithmic to be near-linear. SAIL-VL obtains the highest average score in 19 commonly used benchmarks in our evaluation and achieves top1 performance among VLMs of comparable sizes on OpenCompass (this https URL). We release our SAIL-VL-2B model at HuggingFace (this https URL). 

**Abstract (ZH)**: 在本文中，我们介绍了SAIL-VL（ScAlable Vision Language Model TraIning via High QuaLity Data Curation），这是一种开源的高性能视觉语言模型（VLM），参数量达到20亿。我们介绍了三项关键改进，这些改进共同推动了SAIL-VL的领先性能：（1）可扩展的高质量视觉理解数据构建：我们实现了一个视觉理解数据构建管道，能够生成超过亿级规模的高质量重描述数据标注。利用该管道，我们整理了SAIL-Caption这一大型数据集，其数据量大且数据质量超过开源重描述数据集。（2）基于高质量视觉理解数据的大规模预训练：我们将SAIL-VL的预训练预算扩展至1310亿个令牌，并证明即使参数量为20亿的模型也能从中受益，表现出随着数据规模增加，视觉理解和指令跟随性能的预期数据规模扩展规律。（3）通过数量和质量扩展的大规模精炼训练：我们提出了一种通用的指令数据整理指导原则，允许我们持续扩大指令数据集规模，从而构建高质量的大规模精炼训练数据集。为了进一步提升SAIL-VL的性能，我们提出了一种多层次的训练策略，结合了课程学习方法，使模型性能随数据规模增加的曲线从对数关系变为近似线性。SAIL-VL在我们的评估中获得了19个常用基准中最高的平均得分，并在与之参数量相近的其他VLM模型中表现最佳（这些信息可在以下链接查询：[请提供链接]）。我们已将SAIL-VL-2B模型发布在Hugging Face（请提供链接）。 

---
# VideoRAG: Retrieval-Augmented Generation over Video Corpus 

**Title (ZH)**: VideoRAG：基于视频语料的检索增强生成 

**Authors**: Soyeong Jeong, Kangsan Kim, Jinheon Baek, Sung Ju Hwang  

**Link**: [PDF](https://arxiv.org/pdf/2501.05874)  

**Abstract**: Retrieval-Augmented Generation (RAG) is a powerful strategy to address the issue of generating factually incorrect outputs in foundation models by retrieving external knowledge relevant to queries and incorporating it into their generation process. However, existing RAG approaches have primarily focused on textual information, with some recent advancements beginning to consider images, and they largely overlook videos, a rich source of multimodal knowledge capable of representing events, processes, and contextual details more effectively than any other modality. While a few recent studies explore the integration of videos in the response generation process, they either predefine query-associated videos without retrieving them according to queries, or convert videos into the textual descriptions without harnessing their multimodal richness. To tackle these, we introduce VideoRAG, a novel framework that not only dynamically retrieves relevant videos based on their relevance with queries but also utilizes both visual and textual information of videos in the output generation. Further, to operationalize this, our method revolves around the recent advance of Large Video Language Models (LVLMs), which enable the direct processing of video content to represent it for retrieval and seamless integration of the retrieved videos jointly with queries. We experimentally validate the effectiveness of VideoRAG, showcasing that it is superior to relevant baselines. 

**Abstract (ZH)**: 检索增强生成（RAG）是一种强大的策略，用于解决基础模型生成事实性错误输出的问题。通过检索与查询相关的外部知识并将其纳入生成过程，RAG能够克服这一问题。然而，现有的RAG方法主要集中在文本信息上，近年来的一些进展开始考虑图像，但它们很大程度上忽略了视频这一丰富的多模态知识来源，视频能够比任何其他模态更有效地表示事件、过程和上下文细节。虽然有一些最近的研究探讨了在响应生成过程中整合视频的方法，但它们要么预先定义与查询相关的视频而不根据查询检索它们，要么将视频转换为文本描述而不充分利用其多模态丰富性。为了解决这些问题，我们引入了VideoRAG，这是一种新型框架，不仅能够根据查询的相关性动态检索相关视频，还能够在生成输出时利用视频的视觉和文本信息。此外，为了实现这一目标，我们的方法围绕最近的大型视频语言模型（LVLMs）的进展展开，这使得可以直接处理视频内容以用于检索，并无缝地将检索到的视频与查询联合集成。通过实验验证了VideoRAG的有效性，展示了它在与基线方法相比的优越性。 

---
# MARS6: A Small and Robust Hierarchical-Codec Text-to-Speech Model 

**Title (ZH)**: MARS6：一种小型且稳健的分层编解码器文本到语音模型 

**Authors**: Matthew Baas, Pieter Scholtz, Arnav Mehta, Elliott Dyson, Akshat Prakash, Herman Kamper  

**Link**: [PDF](https://arxiv.org/pdf/2501.05787)  

**Abstract**: Codec-based text-to-speech (TTS) models have shown impressive quality with zero-shot voice cloning abilities. However, they often struggle with more expressive references or complex text inputs. We present MARS6, a robust encoder-decoder transformer for rapid, expressive TTS. MARS6 is built on recent improvements in spoken language modelling. Utilizing a hierarchical setup for its decoder, new speech tokens are processed at a rate of only 12 Hz, enabling efficient modelling of long-form text while retaining reconstruction quality. We combine several recent training and inference techniques to reduce repetitive generation and improve output stability and quality. This enables the 70M-parameter MARS6 to achieve similar performance to models many times larger. We show this in objective and subjective evaluations, comparing TTS output quality and reference speaker cloning ability. Project page: this https URL 

**Abstract (ZH)**: 基于编解码器的文本转语音（TTS）模型在零样本语音克隆能力方面展现出了令人印象深刻的质量。然而，它们在处理更具有表现力的参考文本或复杂文本输入时往往会遇到困难。我们提出了MARS6，一种稳健的编码器-解码器变换器，用于快速生成具有表现力的TTS。MARS6 建立在最近语音语言建模的改进之上。通过其解码器的分层设置，新的语音标记以每秒12赫兹的速度处理，既能够高效地建模长文本，又能够保持重建质量。我们结合了几种最近的训练和推理技术，以减少重复生成并提高输出的稳定性和质量。这使得参数量为700万的MARS6在性能上可与大得多的模型相媲美。我们在客观和主观评估中展示了这一点，对比了TTS输出质量以及参考说话人克隆能力。项目页面：[这里](this https URL) 

---
# Semantic Exploration with Adaptive Gating for Efficient Problem Solving with Language Models 

**Title (ZH)**: 适应性门控机制驱动的语义探索以实现高效的语言模型问题求解 

**Authors**: Sungjae Lee, Hyejin Park, Jaechang Kim, Jungseul Ok  

**Link**: [PDF](https://arxiv.org/pdf/2501.05752)  

**Abstract**: Recent advancements in large language models (LLMs) have shown remarkable potential in various complex tasks requiring multi-step reasoning methods like tree search to explore diverse reasoning paths. However, existing methods often suffer from computational inefficiency and redundancy. First, they overlook the diversity of task difficulties, leading to unnecessarily extensive searches even for easy tasks. Second, they neglect the semantics of reasoning paths, resulting in redundant exploration of semantically identical paths. To address these limitations, we propose Semantic Exploration with Adaptive Gating (SEAG), a computationally efficient method. SEAG employs an adaptive gating mechanism that dynamically decides whether to conduct a tree search, based on the confidence level of answers from a preceding simple reasoning method. Furthermore, its tree-based exploration consolidates semantically identical reasoning steps, reducing redundant explorations while maintaining or even improving accuracy. Our extensive experiments demonstrate that SEAG significantly improves accuracy by 4.3% on average while requiring only 31% of computational costs compared to existing tree search-based methods on complex reasoning benchmarks including GSM8K and ARC with diverse language models such as Llama2, Llama3, and Mistral. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在需要多步推理方法的各种复杂任务中展现出了显著的潜力，这些任务类似于树搜索，用于探索多样的推理路径。然而，现有的方法往往存在计算效率低下和冗余的问题。首先，它们忽视了任务难度的多样性，导致即使对于简单的任务也会进行不必要的广泛搜索。其次，它们忽略了推理路径的语义信息，导致对语义相同的路径进行了冗余探索。为了解决这些问题，我们提出了一种计算高效的语义探索方法——自适应门控（SEAG）。

SEAG 使用一个自适应门控机制，该机制根据前一简单推理方法答案的信心水平，动态决定是否进行树搜索。此外，其基于树的探索能够整合语义相同的推理步骤，减少冗余探索，同时保持或甚至提高准确性。我们在广泛实验中证明，与现有的基于树搜索的方法相比，SEAG 在涉及不同语言模型（如 Llama2、Llama3 和 Mistral）的复杂推理基准（如 GSM8K 和 ARC）上，平均提高了 4.3% 的准确性，但仅需 31% 的计算成本。 

---
# Overcoming Language Priors for Visual Question Answering Based on Knowledge Distillation 

**Title (ZH)**: 基于知识蒸馏克服语言偏见的视觉问答方法 

**Authors**: Daowan Peng, Wei Wei  

**Link**: [PDF](https://arxiv.org/pdf/2501.05690)  

**Abstract**: Previous studies have pointed out that visual question answering (VQA) models are prone to relying on language priors for answer predictions. In this context, predictions often depend on linguistic shortcuts rather than a comprehensive grasp of multimodal knowledge, which diminishes their generalization ability. In this paper, we propose a novel method, namely, KDAR, leveraging knowledge distillation to address the prior-dependency dilemmas within the VQA task. Specifically, the regularization effect facilitated by soft labels from a well-trained teacher is employed to penalize overfitting to the most common answers. The soft labels, which serve a regularization role, also provide semantic guidance that narrows the range of candidate answers. Additionally, we design an adaptive sample-wise reweighting learning strategy to further mitigate bias by dynamically adjusting the importance of each sample. Experimental results demonstrate that our method enhances performance in both OOD and IID settings. Our method achieves state-of-the-art performance on the VQA-CPv2 out-of-distribution (OOD) benchmark, significantly outperforming previous state-of-the-art approaches. 

**Abstract (ZH)**: 之前的研究所指出，视觉问答（VQA）模型倾向于依赖语言先验来进行答案预测。在此背景下，预测往往依赖于语言上的捷径而不是对多模态知识的全面理解，这削弱了模型的泛化能力。本文提出了一种新的方法，即KDAR（Knowledge Distillation and Adaptive Reweighting），通过知识蒸馏来解决VQA任务中的先验依赖问题。具体而言，利用良好训练的教师模型提供的柔和标签所产生的正则化效应，来惩罚对最常见的答案的过拟合。这些柔和标签作为一种正则化手段，也为预测提供了语义指导，从而缩小了候选答案的范围。此外，我们设计了一种自适应的样本级重加权学习策略，通过动态调整每个样本的重要性来进一步减少偏差。实验结果表明，本方法在既有的条件独立（IID）和条件非独立（OOD）设置中均提升了性能。在VQA-CPv2的条件非独立（OOD）基准测试中，我们的方法达到了最先进的性能，显著优于以往的最先进方法。 

---
# Collaboration of Large Language Models and Small Recommendation Models for Device-Cloud Recommendation 

**Title (ZH)**: 将大型语言模型与小型推荐模型相结合的设备-云推荐协作方法 

**Authors**: Zheqi Lv, Tianyu Zhan, Wenjie Wang, Xinyu Lin, Shengyu Zhang, Wenqiao Zhang, Jiwei Li, Kun Kuang, Fei Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.05647)  

**Abstract**: Large Language Models (LLMs) for Recommendation (LLM4Rec) is a promising research direction that has demonstrated exceptional performance in this field. However, its inability to capture real-time user preferences greatly limits the practical application of LLM4Rec because (i) LLMs are costly to train and infer frequently, and (ii) LLMs struggle to access real-time data (its large number of parameters poses an obstacle to deployment on devices). Fortunately, small recommendation models (SRMs) can effectively supplement these shortcomings of LLM4Rec diagrams by consuming minimal resources for frequent training and inference, and by conveniently accessing real-time data on devices.
In light of this, we designed the Device-Cloud LLM-SRM Collaborative Recommendation Framework (LSC4Rec) under a device-cloud collaboration setting. LSC4Rec aims to integrate the advantages of both LLMs and SRMs, as well as the benefits of cloud and edge computing, achieving a complementary synergy. We enhance the practicability of LSC4Rec by designing three strategies: collaborative training, collaborative inference, and intelligent request. During training, LLM generates candidate lists to enhance the ranking ability of SRM in collaborative scenarios and enables SRM to update adaptively to capture real-time user interests. During inference, LLM and SRM are deployed on the cloud and on the device, respectively. LLM generates candidate lists and initial ranking results based on user behavior, and SRM get reranking results based on the candidate list, with final results integrating both LLM's and SRM's scores. The device determines whether a new candidate list is needed by comparing the consistency of the LLM's and SRM's sorted lists. Our comprehensive and extensive experimental analysis validates the effectiveness of each strategy in LSC4Rec. 

**Abstract (ZH)**: 大语言模型（LLMs）在推荐任务中的应用（LLM4Rec）是极具前景的研究方向，已经在推荐领域展示了出色的效果。然而，LLM4Rec 无法捕捉实时用户偏好，极大地限制了其实际应用，主要原因包括（i）LLM 训练和推理成本高昂，且（ii）LLM 难以访问实时数据（其参数量庞大是部署在设备上的障碍）。幸运的是，小型推荐模型（SRMs）能够有效补充 LLM4Rec 的这些不足，通过消耗最少资源频繁训练和推理，并方便地在设备上访问实时数据。

为了解决这些问题，我们设计了在设备-云协作框架下的设备-云LLM-SRM协作推荐框架（LSC4Rec）。LSC4Rec 的目标是融合 LLM 和 SRM 的优势，以及云计算和边缘计算的优势，实现互补协同。我们通过设计三种策略来增强 LSC4Rec 的实用性：协同训练、协同推理和智能请求。在训练过程中，LLM 生成候选列表，以增强 SRM 在协作场景下的排名能力，并使 SRM 能够根据用户偏好进行自适应更新以捕捉实时用户兴趣。在推理过程中，LLM 和 SRM 分别部署在云和设备上。LLM 根据用户行为生成候选列表和初步排名结果，SRM 基于候选列表生成二次排序结果，最终结果结合了 LLM 和 SRM 的分数。设备通过比较 LLM 和 SRM 排序列表的一致性来决定是否需要生成新的候选列表。我们进行了全面而广泛的实验分析，验证了 LSC4Rec 中每种策略的有效性。 

---
# LSEBMCL: A Latent Space Energy-Based Model for Continual Learning 

**Title (ZH)**: LSEBMCL：基于潜在空间的能量模型在连续学习中的应用 

**Authors**: Xiaodi Li, Dingcheng Li, Rujun Gao, Mahmoud Zamani, Latifur Khan  

**Link**: [PDF](https://arxiv.org/pdf/2501.05495)  

**Abstract**: Continual learning has become essential in many practical applications such as online news summaries and product classification. The primary challenge is known as catastrophic forgetting, a phenomenon where a model inadvertently discards previously learned knowledge when it is trained on new tasks. Existing solutions involve storing exemplars from previous classes, regularizing parameters during the fine-tuning process, or assigning different model parameters to each task. The proposed solution LSEBMCL (Latent Space Energy-Based Model for Continual Learning) in this work is to use energy-based models (EBMs) to prevent catastrophic forgetting by sampling data points from previous tasks when training on new ones. The EBM is a machine learning model that associates an energy value with each input data point. The proposed method uses an EBM layer as an outer-generator in the continual learning framework for NLP tasks. The study demonstrates the efficacy of EBM in NLP tasks, achieving state-of-the-art results in all experiments. 

**Abstract (ZH)**: 持续学习在许多实际应用中变得至关重要，如在线新闻摘要和产品分类。主要挑战被称为灾难性遗忘，这是一种现象，在对新任务进行训练时，模型会无意中丢弃之前学到的知识。现有解决方案包括存储先前类别的示例、在微调过程中正则化参数，或将不同的模型参数分配给每个任务。本文提出的方法是LSEBMCL（潜空间能量为基础模型的持续学习），其目的是通过在对新任务进行训练时从先前任务中采样数据点来使用能量为基础的模型（EBM）防止灾难性遗忘。EBM是一种机器学习模型，与每个输入数据点关联一个能量值。本文提出的方法使用EBM层作为NLP任务持续学习框架中的外部生成器。研究结果表明，EBM在NLP任务中具有很高的有效性，并在所有实验中实现了最先进的结果。 

---