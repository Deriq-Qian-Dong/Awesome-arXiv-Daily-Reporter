# Reasoning-Enhanced Self-Training for Long-Form Personalized Text Generation 

**Title (ZH)**: 增强推理的自训练方法在长文本个性化生成中的应用 

**Authors**: Alireza Salemi, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Weize Kong, Tao Chen, Zhuowan Li, Michael Bendersky, Hamed Zamani  

**Link**: [PDF](https://arxiv.org/pdf/2501.04167)  

**Abstract**: Personalized text generation requires a unique ability of large language models (LLMs) to learn from context that they often do not encounter during their standard training. One way to encourage LLMs to better use personalized context for generating outputs that better align with the user's expectations is to instruct them to reason over the user's past preferences, background knowledge, or writing style. To achieve this, we propose Reasoning-Enhanced Self-Training for Personalized Text Generation (REST-PG), a framework that trains LLMs to reason over personal data during response generation. REST-PG first generates reasoning paths to train the LLM's reasoning abilities and then employs Expectation-Maximization Reinforced Self-Training to iteratively train the LLM based on its own high-reward outputs. We evaluate REST-PG on the LongLaMP benchmark, consisting of four diverse personalized long-form text generation tasks. Our experiments demonstrate that REST-PG achieves significant improvements over state-of-the-art baselines, with an average relative performance gain of 14.5% on the benchmark. 

**Abstract (ZH)**: 个性化文本生成需要大型语言模型（LLMs）具备一种独特的从上下文中学习的能力，而这些上下文在它们的标准训练中可能不会遇到。为了鼓励LLMs更好地利用个性化上下文以生成更好地符合用户期望的输出，可以通过指导它们推理用户的过去偏好、背景知识或写作风格来实现这一目标。为此，我们提出了一种增强推理的自主训练框架（Reasoning-Enhanced Self-Training for Personalized Text Generation，REST-PG），该框架在响应生成过程中使LLMs能够推理个人数据。首先，REST-PG生成推理路径以增强LLMs的推理能力，然后利用期望最大化强化自主训练来基于其自身的高奖励输出迭代训练LLMs。我们在LongLaMP基准数据集上评估了REST-PG，该基准数据集包含四个多样化的个性化长文本生成任务。实验结果表明，与现有的最佳基线方法相比，REST-PG在基准数据集上取得了显著的性能提升，平均相对性能提升达到了14.5%。 

---
# URSA: Understanding and Verifying Chain-of-thought Reasoning in Multimodal Mathematics 

**Title (ZH)**: URSA：理解与验证多模态数学中的链式推理 

**Authors**: Ruilin Luo, Zhuofan Zheng, Yifan Wang, Yiyao Yu, Xinzhe Ni, Zicheng Lin, Jin Zeng, Yujiu Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04686)  

**Abstract**: Chain-of-thought (CoT) reasoning has been widely applied in the mathematical reasoning of Large Language Models (LLMs). Recently, the introduction of derivative process supervision on CoT trajectories has sparked discussions on enhancing scaling capabilities during test time, thereby boosting the potential of these models. However, in multimodal mathematical reasoning, the scarcity of high-quality CoT training data has hindered existing models from achieving high-precision CoT reasoning and has limited the realization of reasoning potential during test time. In this work, we propose a three-module synthesis strategy that integrates CoT distillation, trajectory-format rewriting, and format unification. It results in a high-quality CoT reasoning instruction fine-tuning dataset in multimodal mathematics, MMathCoT-1M. We comprehensively validate the state-of-the-art (SOTA) performance of the trained URSA-7B model on multiple multimodal mathematical benchmarks. For test-time scaling, we introduce a data synthesis strategy that automatically generates process annotation datasets, known as DualMath-1.1M, focusing on both interpretation and logic. By further training URSA-7B on DualMath-1.1M, we transition from CoT reasoning capabilities to robust supervision abilities. The trained URSA-RM-7B acts as a verifier, effectively enhancing the performance of URSA-7B at test time. URSA-RM-7B also demonstrates excellent out-of-distribution (OOD) verifying capabilities, showcasing its generalization. Model weights, training data and code will be open-sourced. 

**Abstract (ZH)**: 链式思维（CoT）推理已在大规模语言模型（LLMs）的数学推理中广泛应用。最近，在CoT轨迹中引入微分过程监督引发了关于测试时增强扩展能力的讨论，从而提升了这些模型的潜力。然而，在多模态数学推理中，高质量CoT训练数据的稀缺性阻碍了现有模型实现高精度CoT推理，并且限制了其在测试时推理潜力的发挥。在本项工作中，我们提出了一种三模块综合策略，该策略结合了CoT蒸馏、轨迹格式重写和格式统一。这生成了一个高质量的多模态数学CoT推理指令微调数据集——MMathCoT-1M。我们全面验证了训练后的URSA-7B模型在多个多模态数学基准测试中的最先进（SOTA）性能。为了实现测试时的扩展，我们引入了一种数据合成策略，该策略可以自动生成过程注释数据集，称之为DualMath-1.1M，关注解释和逻辑的双重结合。通过进一步在DualMath-1.1M上训练URSA-7B，我们从CoT推理能力转向了稳健的监督能力。训练后的URSA-RM-7B作为验证器，有效提升了URSA-7B在测试时的表现。URSA-RM-7B还展示了出色的分布外（OOD）验证能力，展示了其泛化能力。模型权重、训练数据和代码将开源。 

---
# Assessing Language Comprehension in Large Language Models Using Construction Grammar 

**Title (ZH)**: 使用构建语法评估大规模语言模型的语言理解能力 

**Authors**: Wesley Scivetti, Melissa Torgbi, Austin Blodgett, Mollie Shichman, Taylor Hudson, Claire Bonial, Harish Tayyar Madabushi  

**Link**: [PDF](https://arxiv.org/pdf/2501.04661)  

**Abstract**: Large Language Models, despite their significant capabilities, are known to fail in surprising and unpredictable ways. Evaluating their true `understanding' of language is particularly challenging due to the extensive web-scale data they are trained on. Therefore, we construct an evaluation to systematically assess natural language understanding (NLU) in LLMs by leveraging Construction Grammar (CxG), which provides insights into the meaning captured by linguistic elements known as constructions (Cxns). CxG is well-suited for this purpose because provides a theoretical basis to construct targeted evaluation sets. These datasets are carefully constructed to include examples which are unlikely to appear in pre-training data, yet intuitive and easy for humans to understand, enabling a more targeted and reliable assessment. Our experiments focus on downstream natural language inference and reasoning tasks by comparing LLMs' understanding of the underlying meanings communicated through 8 unique Cxns with that of humans. The results show that while LLMs demonstrate some knowledge of constructional information, even the latest models including GPT-o1 struggle with abstract meanings conveyed by these Cxns, as demonstrated in cases where test sentences are dissimilar to their pre-training data. We argue that such cases provide a more accurate test of true language understanding, highlighting key limitations in LLMs' semantic capabilities. We make our novel dataset and associated experimental data including prompts and model responses publicly available. 

**Abstract (ZH)**: 尽管大规模语言模型拥有显著的能力，但它们在意外和不可预测的方式中往往会失败。由于这些模型是基于大规模网络数据训练的，因此评估它们真正理解语言的能力尤为具有挑战性。因此，我们构建了一种评估方法，利用构式语法（CxG）系统性地评估大规模语言模型（LLMs）的自然语言理解（NLU），CxG为理解语言元素（构式）所捕捉到的意义提供了见解。CxG非常适合这一目的，因为它为构建针对性的评估集提供了理论基础。这些数据集精心构建，包含了在预训练数据中不太可能出现但令人直观且易于人类理解的例子，从而能进行更精准和可靠的评估。我们的实验集中在下游自然语言推理和推理性任务上，通过比较LLMs理解和人类对通过8种独特构式（Cxns）传达的底层意义的理解，来考察模型的理解能力。结果显示，虽然LLMs在一些构造信息方面展示了知识，但即使是最新的模型（如GPT-o1）仍难以理解这些Cxns传达的抽象意义，特别是在测试句子与预训练数据显著不同时更为明显。我们认为，这些案例为评估真正的语言理解提供了更为精准的测试，突显了LLMs在语义能力方面的关键限制。我们公开发布了我们的新颖数据集及相关实验数据，包括提示和模型响应等。 

---
# rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking 

**Title (ZH)**: rStar-Math：小型LLM可以通过自我进化深入思考来掌握数学推理 

**Authors**: Xinyu Guan, Li Lyna Zhang, Yifei Liu, Ning Shang, Youran Sun, Yi Zhu, Fan Yang, Mao Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04519)  

**Abstract**: We present rStar-Math to demonstrate that small language models (SLMs) can rival or even surpass the math reasoning capability of OpenAI o1, without distillation from superior models. rStar-Math achieves this by exercising "deep thinking" through Monte Carlo Tree Search (MCTS), where a math policy SLM performs test-time search guided by an SLM-based process reward model. rStar-Math introduces three innovations to tackle the challenges in training the two SLMs: (1) a novel code-augmented CoT data sythesis method, which performs extensive MCTS rollouts to generate step-by-step verified reasoning trajectories used to train the policy SLM; (2) a novel process reward model training method that avoids naïve step-level score annotation, yielding a more effective process preference model (PPM); (3) a self-evolution recipe in which the policy SLM and PPM are built from scratch and iteratively evolved to improve reasoning capabilities. Through 4 rounds of self-evolution with millions of synthesized solutions for 747k math problems, rStar-Math boosts SLMs' math reasoning to state-of-the-art levels. On the MATH benchmark, it improves Qwen2.5-Math-7B from 58.8% to 90.0% and Phi3-mini-3.8B from 41.4% to 86.4%, surpassing o1-preview by +4.5% and +0.9%. On the USA Math Olympiad (AIME), rStar-Math solves an average of 53.3% (8/15) of problems, ranking among the top 20% the brightest high school math students. Code and data will be available at this https URL. 

**Abstract (ZH)**: 我们提出rStar-Math，以证明小型语言模型（SLMs）可以与甚至超越OpenAI o1在数学推理能力上的表现，而无需从更优秀的模型中进行蒸馏。rStar-Math通过蒙特卡洛树搜索（MCTS）实现“深度思考”，其中数学策略SLM根据基于过程奖励模型的SLM过程引导进行测试时搜索。rStar-Math提出了三种创新方法来应对训练两个SLM所面临的挑战：（1）一种新颖的代码增强型CoT数据合成方法，通过执行广泛的MCTS展开来生成经过逐步验证的推理轨迹，用于训练策略SLM；（2）一种新型的过程奖励模型训练方法，避免了简单的步骤级评分注释，生成更有效的过程偏好模型（PPM）；（3）一种自我进化方法，在这种方法中，策略SLM和PPM从头构建并通过迭代进化提高推理能力。通过四轮自我进化并对74.7万个数学问题生成数百万种合成解决方案，rStar-Math将SLMs的数学推理能力提升至最新的技术水平。在MATH基准测试中，它将Qwen2.5-Math-7B的得分从58.8%提高到90.0%，将Phi3-mini-3.8B的得分从41.4%提高到86.4%，分别超越o1-preview 4.5%和0.9%。在美国数学奥林匹克（AIME）中，rStar-Math平均解决8/15（53.3%）个问题，其表现跻身最亮高中生数学能力的前20%。代码和数据将在此处提供：[此链接]。 

---
# When LLMs Struggle: Reference-less Translation Evaluation for Low-resource Languages 

**Title (ZH)**: 当大语言模型遇到挑战：无参考译文评估方法在低资源语言中的应用 

**Authors**: Archchana Sindhujan, Diptesh Kanojia, Constantin Orasan, Shenbin Qian  

**Link**: [PDF](https://arxiv.org/pdf/2501.04473)  

**Abstract**: This paper investigates the reference-less evaluation of machine translation for low-resource language pairs, known as quality estimation (QE). Segment-level QE is a challenging cross-lingual language understanding task that provides a quality score (0-100) to the translated output. We comprehensively evaluate large language models (LLMs) in zero/few-shot scenarios and perform instruction fine-tuning using a novel prompt based on annotation guidelines. Our results indicate that prompt-based approaches are outperformed by the encoder-based fine-tuned QE models. Our error analysis reveals tokenization issues, along with errors due to transliteration and named entities, and argues for refinement in LLM pre-training for cross-lingual tasks. We release the data, and models trained publicly for further research. 

**Abstract (ZH)**: 本文探讨了低资源语言对机器翻译的无参考评估问题，即质量估测（QE）。段落级的QE是一项具有挑战性的跨语言语言理解任务，它为翻译输出提供一个质量分（0-100分）。我们全面评估了大型语言模型（LLMs）在零样本/少样本场景下的性能，并利用基于注释指南的新颖提示进行指令微调。实验结果表明，基于提示的方法在性能上不如基于编码器的微调QE模型。我们的错误分析揭示了分词问题，以及由于音译和命名实体导致的错误，这表明需改进大型语言模型在跨语言任务中的预训练。我们公开发布了数据和训练模型，以便进一步研究。 

---
# Hidden Entity Detection from GitHub Leveraging Large Language Models 

**Title (ZH)**: 利用大规模语言模型从GitHub检测隐藏实体 

**Authors**: Lu Gan, Martin Blum, Danilo Dessi, Brigitte Mathiak, Ralf Schenkel, Stefan Dietze  

**Link**: [PDF](https://arxiv.org/pdf/2501.04455)  

**Abstract**: Named entity recognition is an important task when constructing knowledge bases from unstructured data sources. Whereas entity detection methods mostly rely on extensive training data, Large Language Models (LLMs) have paved the way towards approaches that rely on zero-shot learning (ZSL) or few-shot learning (FSL) by taking advantage of the capabilities LLMs acquired during pretraining. Specifically, in very specialized scenarios where large-scale training data is not available, ZSL / FSL opens new opportunities. This paper follows this recent trend and investigates the potential of leveraging Large Language Models (LLMs) in such scenarios to automatically detect datasets and software within textual content from GitHub repositories. While existing methods focused solely on named entities, this study aims to broaden the scope by incorporating resources such as repositories and online hubs where entities are also represented by URLs. The study explores different FSL prompt learning approaches to enhance the LLMs' ability to identify dataset and software mentions within repository texts. Through analyses of LLM effectiveness and learning strategies, this paper offers insights into the potential of advanced language models for automated entity detection. 

**Abstract (ZH)**: 从非结构化数据源构建知识库时，命名实体识别是一项重要任务。尽管实体检测方法大多依赖广泛的训练数据，但大规模语言模型（LLMs）为基于零样本学习（ZSL）或少样本学习（FSL）的方法开辟了道路，这得益于LLMs在预训练阶段获得的能力。具体而言，在大规模训练数据不可用的非常专业化场景中，ZSL / FSL方法为我们提供了新的机会。本文遵循这一最新趋势，探讨在这些场景中利用大规模语言模型（LLMs）以自动在GitHub仓库的文本内容中检测数据集和软件的潜力。现有的方法仅专注于命名实体，而本研究旨在通过纳入包含实体URL的仓库和在线中心等资源来扩大研究范围。研究探索了不同的FSL提示学习方法，以增强LLMs识别仓库文本中数据集和软件提及的能力。通过分析大规模语言模型的效果和学习策略，本文提供了关于高级语言模型在自动化实体检测方面潜力的见解。 

---
# End-to-End Bangla AI for Solving Math Olympiad Problem Benchmark: Leveraging Large Language Model Using Integrated Approach 

**Title (ZH)**: 面向数学奥林匹克问题基准的端到端孟加拉语AI解决方案：结合大型语言模型的集成方法 

**Authors**: H.M. Shadman Tabib, Jaber Ahmed Deedar  

**Link**: [PDF](https://arxiv.org/pdf/2501.04425)  

**Abstract**: This work introduces systematic approach for enhancing large language models (LLMs) to address Bangla AI mathematical challenges. Through the assessment of diverse LLM configurations, fine-tuning with specific datasets, and the implementation of Retrieval-Augmented Generation (RAG), we enhanced the model's reasoning precision in a multilingual setting. Crucial discoveries indicate that customized prompting, dataset augmentation, and iterative reasoning improve the model's efficiency regarding Olympiad-level mathematical challenges. 

**Abstract (ZH)**: 本研究引入了一种系统方法，旨在提升大型语言模型（LLMs）以应对孟加拉语人工智能数学挑战。通过评估多种LLM配置、使用特定数据集进行微调以及实施检索增强生成（RAG），我们提高了模型在多语言环境下的推理精确度。关键发现表明，定制化提示、数据集增强和迭代推理可以提高模型在奥林匹克级别数学挑战中的效率。 

---
# SEO: Stochastic Experience Optimization for Large Language Models 

**Title (ZH)**: SEO: 基于随机经验优化的大语言模型 

**Authors**: Jitao Xu, Hongyun Zhou, Lei Shen, Conghui Zhu, Jin Huang, Yitao Duan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04393)  

**Abstract**: Large Language Models (LLMs) can benefit from useful experiences to improve their performance on specific tasks. However, finding helpful experiences for different LLMs is not obvious, since it is unclear what experiences suit specific LLMs. Previous studies intended to automatically find useful experiences using LLMs, while it is difficult to ensure the effectiveness of the obtained experience. In this paper, we propose Stochastic Experience Optimization (SEO), an iterative approach that finds optimized model-specific experience without modifying model parameters through experience update in natural language. In SEO, we propose a stochastic validation method to ensure the update direction of experience, avoiding unavailing updates. Experimental results on three tasks for three LLMs demonstrate that experiences optimized by SEO can achieve consistently improved performance. Further analysis indicates that SEO-optimized experience can generalize to out-of-distribution data, boosting the performance of LLMs on similar tasks. 

**Abstract (ZH)**: Large语言模型（LLMs）可以从有用的经验中受益，以提高其在特定任务上的性能。然而，找到适合不同LLMs的有效经验并不明显，因为不清楚哪些经验适合特定的LLMs。以前的研究旨在使用LLMs自动找到有用的经验，但确保获取的经验有效是具有挑战性的。本文我们提出了一种称为随机经验优化（SEO）的方法，这是一种迭代方法，通过自然语言中的经验更新找到优化的模型特定经验，而无需修改模型参数。在SEO中，我们提出了一种随机验证方法，以确保经验更新的方向，避免无效的更新。我们在三个LLMs上的三个任务上的实验结果表明，通过SEO优化的经验可以实现一致的性能提升。进一步的分析表明，SEO优化的经验可以泛化到未见过的数据，从而在类似任务上提升LLMs的性能。 

---
# Understanding Before Reasoning: Enhancing Chain-of-Thought with Iterative Summarization Pre-Prompting 

**Title (ZH)**: 理解优先于推理：通过迭代总结前提示增强链式思考能力 

**Authors**: Dong-Hai Zhu, Yu-Jie Xiong, Jia-Chen Zhang, Xi-Jiong Xie, Chun-Ming Xia  

**Link**: [PDF](https://arxiv.org/pdf/2501.04341)  

**Abstract**: Chain-of-Thought (CoT) Prompting is a dominant paradigm in Large Language Models (LLMs) to enhance complex reasoning. It guides LLMs to present multi-step reasoning, rather than generating the final answer directly. However, CoT encounters difficulties when key information required for reasoning is implicit or missing. This occurs because CoT emphasizes the sequence of reasoning steps while overlooking the early extraction of essential information. We propose a pre-prompting method called Iterative Summarization Pre-Prompting (ISP^2) to refine LLM reasoning when key information is not explicitly provided. First, entities and their corresponding descriptions are extracted to form potential key information pairs. Next, we use a reliability rating to assess these pairs, then merge the two lowest-ranked pairs into a new entity description. This process is repeated until a unique key information pair is obtained. Finally, that pair, along with the original question, is fed into LLMs to produce the answer. Extensive experiments demonstrate a 7.1% improvement compared to existing methods. Unlike traditional prompting, ISP^2 adopts an inductive approach with pre-prompting, offering flexible integration into diverse reasoning frameworks. The code is available at this https URL. 

**Abstract (ZH)**: 链推理（CoT）提示是大型语言模型（LLMs）中提高复杂推理能力的主要范式。它引导LLMs进行多步推理，而不是直接生成最终答案。然而，当用于推理的关键信息是隐含的或缺失时，CoT会遇到困难。这是因为CoT侧重于推理步骤的顺序，而忽视了早期提取重要信息的重要性。我们提出了一种预提示方法，称为迭代总结预提示（ISP^2），以在关键信息未显式提供时改进LLMs的推理。首先，从实体及其对应描述中提取潜在的关键信息对。接着，利用可靠性评分评估这些对，然后合并评分最低的两个对以形成新的实体描述。这一过程重复进行，直到获得唯一的关键信息对。最后，将这一对以及原始问题输入到LLMs中以生成答案。大量的实验结果显示，ISP^2方法相较于现有方法提高了7.1%。与传统的提示方法不同，ISP^2采取归纳的方法进行预提示，提供了灵活的集成到各种推理框架中的可能性。相关代码可在如下链接获取：[插入链接]。 

---
# LLM4SR: A Survey on Large Language Models for Scientific Research 

**Title (ZH)**: LLM4SR：大型语言模型在科学研究中的综述 

**Authors**: Ziming Luo, Zonglin Yang, Zexin Xu, Wei Yang, Xinya Du  

**Link**: [PDF](https://arxiv.org/pdf/2501.04306)  

**Abstract**: In recent years, the rapid advancement of Large Language Models (LLMs) has transformed the landscape of scientific research, offering unprecedented support across various stages of the research cycle. This paper presents the first systematic survey dedicated to exploring how LLMs are revolutionizing the scientific research process. We analyze the unique roles LLMs play across four critical stages of research: hypothesis discovery, experiment planning and implementation, scientific writing, and peer reviewing. Our review comprehensively showcases the task-specific methodologies and evaluation benchmarks. By identifying current challenges and proposing future research directions, this survey not only highlights the transformative potential of LLMs, but also aims to inspire and guide researchers and practitioners in leveraging LLMs to advance scientific inquiry. Resources are available at the following repository: this https URL 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的快速发展已经彻底改变了科学研究的格局，为科研周期的各个阶段提供了前所未有的支持。本文进行了一篇系统性的文献综述，旨在探讨LLMs如何正在改变科研过程。我们分析了LLMs在科研四个关键阶段的独特作用：假设发现、实验规划与实施、科学写作以及同行评审。综述全面展示了任务特定的方法论和评估标准。通过对当前挑战的识别和对未来研究方向的建议，这篇综述不仅突显了LLMs的变革潜力，还旨在激发和指导研究人员和从业者利用LLMs推进科学研究。相关资源可访问以下仓库：this https URL 

---
# Multimodal Graph Constrastive Learning and Prompt for ChartQA 

**Title (ZH)**: 多模态图对比学习与提示在图表问答中的应用 

**Authors**: Yue Dai, Soyeon Caren Han, Wei Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04303)  

**Abstract**: ChartQA presents significant challenges due to the complex distribution of chart elements and the implicit patterns embedded within the underlying data. In this chapter, we have developed a joint multimodal scene graph for charts, explicitly representing the relationships between chart elements and their associated patterns.
Our proposed multimodal scene graph consists of two components: a visual graph and a textual graph, each designed to capture the structural and semantic information within the chart. To unify representations across these different modalities, we introduce a multimodal graph contrastive learning approach that learns unified representations by maximizing similarity between nodes representing the same object across multimodal graphs. The learned graph representations can be seamlessly incorporated into a transformer decoder as a soft prompt.
Additionally, given the growing need for Multimodal Large Language Models (MLLMs) in zero-shot scenarios, we have designed Chain-of-Thought (CoT) prompts for MLLMs to reduce hallucinations. We tested both methods on public benchmarks such as ChartQA, OpenCQA, and ChartX, demonstrating improved performance and validating the effectiveness of our proposed methods. 

**Abstract (ZH)**: 将以下论文内容或标题翻译成中文，并符合学术规范：

ChartQA 因其图表元素复杂分布和嵌入在底层数据中的隐含模式而提出了显著的挑战。在本章中，我们开发了一个联合多模态场景图，明确地表示了图表元素与其相关模式之间的关系。
我们提出的一体化多模态场景图由两个组成部分组成：一个视觉图和一个文本图，每个组成部分都旨在捕捉图表中的结构和语义信息。为了统一这些不同模态之间的表示，我们引入了一种多模态图对比学习方法，该方法通过在多模态图中最大化表示同一对象的节点之间的相似性来学习统一的表示。学习到的图表示可以无缝地集成到变压器解码器中作为软提示。
此外，鉴于在零样本场景中对多模态大规模语言模型（MLLM）的需求不断增加，我们为 MLLMs 设计了推理链（CoT）提示来减少幻觉。我们在这类图表问答测试集（如 ChartQA、OpenCQA 和 ChartX）上测试了这两种方法，结果显示性能有所提升，并验证了我们所提出方法的有效性。 

---
# IOLBENCH: Benchmarking LLMs on Linguistic Reasoning 

**Title (ZH)**: IOLBENCH：评估语言推理能力的LLM基准测试 

**Authors**: Satyam Goyal, Soham Dan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04249)  

**Abstract**: Despite the remarkable advancements and widespread applications of deep neural networks, their ability to perform reasoning tasks remains limited, particularly in domains requiring structured, abstract thought. In this paper, we investigate the linguistic reasoning capabilities of state-of-the-art large language models (LLMs) by introducing IOLBENCH, a novel benchmark derived from International Linguistics Olympiad (IOL) problems. This dataset encompasses diverse problems testing syntax, morphology, phonology, and semantics, all carefully designed to be self-contained and independent of external knowledge. These tasks challenge models to engage in metacognitive linguistic reasoning, requiring the deduction of linguistic rules and patterns from minimal examples. Through extensive benchmarking of leading LLMs, we find that even the most advanced models struggle to handle the intricacies of linguistic complexity, particularly in areas demanding compositional generalization and rule abstraction. Our analysis highlights both the strengths and persistent limitations of current models in linguistic problem-solving, offering valuable insights into their reasoning capabilities. By introducing IOLBENCH, we aim to foster further research into developing models capable of human-like reasoning, with broader implications for the fields of computational linguistics and artificial intelligence. 

**Abstract (ZH)**: 尽管深度神经网络在进展和广泛应用方面取得了显著成就，它们在进行推理任务方面的能力仍受到限制，尤其是在需要结构化和抽象思维的领域。在本文中，我们通过引入IOLBENCH，这一源自国际语言学奥林匹克（IOL）问题的新基准，来研究最先进的大规模语言模型（LLMs）的语法规则推理能力。该数据集涵盖了涉及句法、形态学、音系学和语义学的多种问题，所有问题都经过精心设计，确保它们具有相对独立性，不依赖于外部知识。这些任务挑战模型进行元认知语法规则推理，要求从最小的例子中推导出语法规则和模式。通过对领先的大规模语言模型进行广泛的基准测试，我们发现即使是最先进的模型在处理语法规则的复杂性方面也存在困难，特别是在需要组合泛化和规则抽象的领域。我们的分析强调了当前模型在语言问题解决中的优势和持续存在的局限性，为理解它们的推理能力提供了宝贵的见解。通过引入IOLBENCH，我们旨在促进进一步研究，以开发出能够在语法规则推理方面接近人类水平的模型，这将对计算语言学和人工智能领域产生更广泛的影响。 

---
# A Survey on Large Language Models with some Insights on their Capabilities and Limitations 

**Title (ZH)**: 大型语言模型综述：关于其能力与局限性的某些见解 

**Authors**: Andrea Matarazzo, Riccardo Torlone  

**Link**: [PDF](https://arxiv.org/pdf/2501.04040)  

**Abstract**: The rapid advancement of artificial intelligence, particularly with the development of Large Language Models (LLMs) built on the transformer architecture, has redefined the capabilities of natural language processing. These models now exhibit remarkable performance across various language-related tasks, such as text generation, question answering, translation, and summarization, often rivaling human-like comprehension. More intriguingly, LLMs have demonstrated emergent abilities extending beyond their core functions, showing proficiency in tasks like commonsense reasoning, code generation, and arithmetic. This survey paper explores the foundational components, scaling mechanisms, and architectural strategies that drive these capabilities. Emphasizing models like GPT and LLaMA, we analyze the impact of exponential data and computational growth on LLM performance, while also addressing the trade-offs associated with scaling. We also examine LLM applications across sectors, such as healthcare, finance, education, and law, highlighting their adaptability and potential to solve domain-specific challenges. Central to this work are the questions of how LLMs generalize across diverse tasks, exhibit planning, and reasoning abilities, and whether these emergent abilities can be systematically elicited or enhanced. In particular, we provide some insights into the CoT (Chain of Thought) and PoT (Plan of Thought) abilities within LLMs, focusing on how pre-training data influences their emergence. Additionally, we investigate LLM-modulo frameworks that integrate external systems, allowing LLMs to handle complex, dynamic tasks. By analyzing these factors, this paper aims to foster the ongoing discussion on the capabilities and limits of LLMs, promoting their responsible development and application in novel and increasingly complex environments. 

**Abstract (ZH)**: 人工智能的迅速发展，特别是在基于Transformers架构构建的大规模语言模型（LLMs）的发展下，重新定义了自然语言处理的能力。这些模型在文本生成、问答、翻译和总结等多种语言相关任务中表现出卓越的性能，往往能够媲美人类的理解能力。更令人着迷的是，LLMs展示了超出其核心功能的新兴能力，展示了在常识推理、代码生成和算术任务上的专长。本文综述了这些能力的基础组件、扩展示例机制和架构策略。以GPT和LLaMA为代表的模型为例，我们分析了指数级数据和计算增长对LLMs性能的影响，并讨论了与扩展现有的权衡。此外，我们还探讨了LLMs在医疗保健、金融、教育和法律领域的广泛应用，突显了它们的适应能力和解决特定领域挑战的潜力。本文的关键问题在于LLMs在不同任务中的泛化能力、计划能力和推理能力，以及这些新兴能力能否系统地引发或增强。特别地，我们探讨了LLMs中CoT（思维链）和PoT（思维计划）能力，关注预训练数据对它们出现的影响。我们还研究了将外部系统集成到LLMs中的LLM-modulo框架，使LLMs能够处理复杂、动态的任务。通过对这些因素的分析，本文旨在促进对LLMs能力和限制的持续讨论，促进其负责任的开发和在日益复杂的新环境中应用。 

---
# Towards System 2 Reasoning in LLMs: Learning How to Think With Meta Chain-of-Though 

**Title (ZH)**: 向LLM中引入系统二推理：学习如何通过元链式思考进行思考 

**Authors**: Violet Xiang, Charlie Snell, Kanishk Gandhi, Alon Albalak, Anikait Singh, Chase Blagden, Duy Phung, Rafael Rafailov, Nathan Lile, Dakota Mahan, Louis Castricato, Jan-Philipp Franken, Nick Haber, Chelsea Finn  

**Link**: [PDF](https://arxiv.org/pdf/2501.04682)  

**Abstract**: We propose a novel framework, Meta Chain-of-Thought (Meta-CoT), which extends traditional Chain-of-Thought (CoT) by explicitly modeling the underlying reasoning required to arrive at a particular CoT. We present empirical evidence from state-of-the-art models exhibiting behaviors consistent with in-context search, and explore methods for producing Meta-CoT via process supervision, synthetic data generation, and search algorithms. Finally, we outline a concrete pipeline for training a model to produce Meta-CoTs, incorporating instruction tuning with linearized search traces and reinforcement learning post-training. Finally, we discuss open research questions, including scaling laws, verifier roles, and the potential for discovering novel reasoning algorithms. This work provides a theoretical and practical roadmap to enable Meta-CoT in LLMs, paving the way for more powerful and human-like reasoning in artificial intelligence. 

**Abstract (ZH)**: 我们提出了一种新颖的框架，即元思维链（Meta-CoT），它通过明确建模达到特定思维链（CoT）所需的底层推理，扩展了传统的思维链方法。我们展示了最先进的模型表现出类似上下文搜索的行为，并探讨了通过过程监督、合成数据生成和搜索算法来生成元CoT的方法。最后，我们概述了一个具体的训练模型生成元CoT的管道，该管道结合了指令调优、线性化搜索轨迹以及训练后的强化学习。最后，我们讨论了开放的研究问题，包括扩展律、验证者角色以及发现新型推理算法的可能性。这项工作为在大语言模型（LLM）中实现元CoT提供了一个理论和实践的路线图，为人工智能中更强大和类人的推理铺平了道路。 

---
# FlairGPT: Repurposing LLMs for Interior Designs 

**Title (ZH)**: FlairGPT: 将大语言模型应用于室内设计 

**Authors**: Gabrielle Littlefair, Niladri Shekhar Dutt, Niloy J. Mitra  

**Link**: [PDF](https://arxiv.org/pdf/2501.04648)  

**Abstract**: Interior design involves the careful selection and arrangement of objects to create an aesthetically pleasing, functional, and harmonized space that aligns with the client's design brief. This task is particularly challenging, as a successful design must not only incorporate all the necessary objects in a cohesive style, but also ensure they are arranged in a way that maximizes accessibility, while adhering to a variety of affordability and usage considerations. Data-driven solutions have been proposed, but these are typically room- or domain-specific and lack explainability in their design design considerations used in producing the final layout. In this paper, we investigate if large language models (LLMs) can be directly utilized for interior design. While we find that LLMs are not yet capable of generating complete layouts, they can be effectively leveraged in a structured manner, inspired by the workflow of interior designers. By systematically probing LLMs, we can reliably generate a list of objects along with relevant constraints that guide their placement. We translate this information into a design layout graph, which is then solved using an off-the-shelf constrained optimization setup to generate the final layouts. We benchmark our algorithm in various design configurations against existing LLM-based methods and human designs, and evaluate the results using a variety of quantitative and qualitative metrics along with user studies. In summary, we demonstrate that LLMs, when used in a structured manner, can effectively generate diverse high-quality layouts, making them a viable solution for creating large-scale virtual scenes. Project webpage at this https URL 

**Abstract (ZH)**: 室内设计涉及精心选择和布置物体，以创建一个符合审美、功能性和和谐的环境，同时也需与客户的设计需求相符。这一任务特别具有挑战性，因为成功的方案不仅要以一种连贯的风格整合所有必要物体，还必须确保这些物体的摆放方式能够最大化地提高可达性，并且考虑到多种成本和使用方面的需求。尽管已经提出了数据驱动的解决方案，但这些方案通常局限于特定的房间或领域，并且在生成最终布局时缺乏解释性。在本文中，我们探讨了大型语言模型（LLMs）是否可以直接用于室内设计。尽管我们发现LLMs尚不具备生成完整布局的能力，但可以通过一种结构化的方式有效地利用它们，借鉴室内设计师的工作流程。通过系统地探究LLMs，我们可以可靠地生成物体列表及其相关约束条件，从而指导它们的布局。我们将这些信息转换为设计布局图，然后使用现成的约束优化方案生成最终布局。我们使用各种设计配置对我们的算法与现有的LLM基方法和人类设计进行了基准测试，并使用多种定量和定性指标以及用户研究来评估结果。总的来说，我们证明了，当以结构化方式使用时，LLMs能够有效地生成多样的高质量布局，使其成为创建大规模虚拟场景的有效解决方案。项目网站详见以下链接：[该项目网页链接] 

---
# InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection 

**Title (ZH)**: InfiGUIAgent：一种具有原生推理和反思能力的多模态通用GUI代理 

**Authors**: Yuhang Liu, Pengxiang Li, Zishu Wei, Congkai Xie, Xueyu Hu, Xinchen Xu, Shengyu Zhang, Xiaotian Han, Hongxia Yang, Fei Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04575)  

**Abstract**: Graphical User Interface (GUI) Agents, powered by multimodal large language models (MLLMs), have shown great potential for task automation on computing devices such as computers and mobile phones. However, existing agents face challenges in multi-step reasoning and reliance on textual annotations, limiting their effectiveness. We introduce \textit{InfiGUIAgent}, an MLLM-based GUI Agent trained with a two-stage supervised fine-tuning pipeline. Stage 1 enhances fundamental skills such as GUI understanding and grounding, while Stage 2 integrates hierarchical reasoning and expectation-reflection reasoning skills using synthesized data to enable native reasoning abilities of the agents. \textit{InfiGUIAgent} achieves competitive performance on several GUI benchmarks, highlighting the impact of native reasoning skills in enhancing GUI interaction for automation tasks. Resources are available at \url{this https URL}. 

**Abstract (ZH)**: 由多模态大规模语言模型（MLLMs）驱动的图形用户界面（GUI）代理已经在计算设备如计算机和手机上展示了在任务自动化方面的巨大潜力。然而，现有的代理在多步推理和依赖文本标注方面面临挑战，限制了它们的效果。我们提出了基于MLLM的\textit{InfiGUIAgent}，这是一种通过两阶段监督微调管道进行训练的GUI代理。第一阶段增强基础技能，如GUI理解与定位，第二阶段则通过合成数据整合层级推理和预期-反思推理技能，使代理具备本体推理能力。在多个GUI基准测试中，\textit{InfiGUIAgent}取得了竞争力的表现，突显了本体推理技能在提升GUI交互以适应自动化任务方面的效果。更多资源可参见\url{this https URL}。 

---
# More is not always better? Enhancing Many-Shot In-Context Learning with Differentiated and Reweighting Objectives 

**Title (ZH)**: 更多未必更好？差异化和加权目标增强多样本反例学习效果研究 

**Authors**: Xiaoqing Zhang, Ang Lv, Yuhan Liu, Flood Sung, Wei Liu, Shuo Shang, Xiuying Chen, Rui Yan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04070)  

**Abstract**: Large language models (LLMs) excel at few-shot in-context learning (ICL) without requiring parameter updates. However, as the number of ICL demonstrations increases from a few to many, performance tends to plateau and eventually decline. We identify two primary causes for this trend: the suboptimal negative log-likelihood (NLL) optimization objective and the incremental data noise. To address these issues, we introduce DR-ICL, a novel optimization method that enhances model performance through Differentiated Learning and advantage-based Reweighting objectives. Globally, DR-ICL utilizes differentiated learning to optimize the NLL objective, ensuring that many-shot performance surpasses zero-shot levels. Locally, it dynamically adjusts the weighting of many-shot demonstrations by leveraging cumulative advantages inspired by reinforcement learning, thereby improving generalization. This approach allows the model to handle varying numbers of shots effectively, mitigating the impact of noisy data. Recognizing the lack of multi-task datasets with diverse many-shot distributions, we develop the Many-Shot ICL Benchmark (MICLB)-a large-scale benchmark covering shot numbers from 1 to 350 within sequences of up to 8,000 tokens-for fine-tuning purposes. MICLB facilitates the evaluation of many-shot ICL strategies across seven prominent NLP tasks and 50 distinct datasets. Experimental results demonstrate that LLMs enhanced with DR-ICL achieve significant improvements in many-shot setups across various tasks, including both in-domain and out-of-domain scenarios. We release the code and benchmark dataset hoping to facilitate further research in many-shot ICL. 

**Abstract (ZH)**: 大型语言模型（LLMs）在少量示例下/background知识学习（ICL）中表现出色，无需更新参数。然而，随着ICL示例数量从少量增加到许多，性能往往会达到稳定状态并最终下降。我们确定了这种趋势的两个主要原因：次优的负对数似然（NLL）优化目标以及逐步增加的数据噪声。为了解决这些问题，我们引入了DR-ICL（区分学习和优势加权重定义），这是一种新颖的优化方法，能够通过区分学习和优势加权的目标增强模型性能。全球而言，DR-ICL 通过区分学习优化 NLL 目标，确保多示例的表现超过零示例水平。局部而言，它通过借鉴强化学习中的累积优势动态调整多示例示例的权重，从而提高泛化能力。这种方法使模型能够有效应对不同的示例数量，减轻噪声数据的影响。考虑到缺乏包含多种多示例分布的多任务数据集，我们开发了多示例ICL基准（MICLB），这是一个大规模的基准，涵盖了序列内至多8000个标记中从1到350的不同多示例数量，用于微调目的。MICLB 使得能够在七个主要自然语言处理（NLP）任务和50个不同数据集上评估多示例ICL策略。实验结果表明，使用DR-ICL增强的LLMs在各种任务中，在多示例设置中取得了显著改进，包括领域内和领域外场景。我们发布了代码和基准数据集，希望促进多示例ICL领域的进一步研究。 

---
# RoRA: Efficient Fine-Tuning of LLM with Reliability Optimization for Rank Adaptation 

**Title (ZH)**: RoRA：针对排名适应性的可靠性能优化高效细调大语言模型 

**Authors**: Jun Liu, Zhenglun Kong, Peiyan Dong, Xuan Shen, Pu Zhao, Hao Tang, Geng Yuan, Wei Niu, Wenbin Zhang, Xue Lin, Dong Huang, Yanzhi Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04315)  

**Abstract**: Fine-tuning helps large language models (LLM) recover degraded information and enhance task this http URL Low-Rank Adaptation (LoRA) is widely used and effective for fine-tuning, we have observed that its scaling factor can limit or even reduce performance as the rank size increases. To address this issue, we propose RoRA (Rank-adaptive Reliability Optimization), a simple yet effective method for optimizing LoRA's scaling factor. By replacing $\alpha/r$ with $\alpha/\sqrt{r}$, RoRA ensures improved performance as rank size increases. Moreover, RoRA enhances low-rank adaptation in fine-tuning uncompressed models and excels in the more challenging task of accuracy recovery when fine-tuning pruned models. Extensive experiments demonstrate the effectiveness of RoRA in fine-tuning both uncompressed and pruned models. RoRA surpasses the state-of-the-art (SOTA) in average accuracy and robustness on LLaMA-7B/13B, LLaMA2-7B, and LLaMA3-8B, specifically outperforming LoRA and DoRA by 6.5% and 2.9% on LLaMA-7B, respectively. In pruned model fine-tuning, RoRA shows significant advantages; for SHEARED-LLAMA-1.3, a LLaMA-7B with 81.4% pruning, RoRA achieves 5.7% higher average accuracy than LoRA and 3.9% higher than DoRA. 

**Abstract (ZH)**: 细调有助于大型语言模型（LLM）恢复降级信息并增强任务性能。我们观察到，随着秩大小增加，低秩适应（LoRA）的缩放因子可能会限制甚至降低性能。为了解决这一问题，我们提出了RoRA（Rank-adaptive Reliability Optimization），一种简单而有效的方法来优化LoRA的缩放因子。通过将$\alpha/r$替换为$\alpha/\sqrt{r}$，RoRA确保随秩大小增加时性能得到提升。此外，RoRA在细调未压缩模型时增强了低秩适应性，并在细调剪枝模型时取得了更高的准确度恢复效果。广泛的实验结果表明，RoRA在未压缩和剪枝模型的细调中都表现出有效性。在对LLaMA-7B/13B、LLaMA2-7B和LLaMA3-8B的平均准确度和鲁棒性测试中，RoRA分别比LoRA和DoRA高出6.5%和2.9%。在剪枝模型的细调中，RoRA表现出明显优势；对于SHEARED-LLAMA-1.3（去掉了81.4%的LLaMA-7B），RoRA的平均准确度比LoRA高出5.7%，比DoRA高出3.9%。 

---