# EpiCoder: Encompassing Diversity and Complexity in Code Generation 

**Title (ZH)**: EpiCoder：包容多样性和复杂性的代码生成 

**Authors**: Yaoxiang Wang, Haoling Li, Xin Zhang, Jie Wu, Xiao Liu, Wenxiang Hu, Zhongxin Guo, Yangyu Huang, Ying Xin, Yujiu Yang, Jinsong Su, Qi Chen, Scarlett Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.04694)  

**Abstract**: Effective instruction tuning is indispensable for optimizing code LLMs, aligning model behavior with user expectations and enhancing model performance in real-world applications. However, most existing methods focus on code snippets, which are limited to specific functionalities and rigid structures, restricting the complexity and diversity of the synthesized data. To address these limitations, we introduce a novel feature tree-based synthesis framework inspired by Abstract Syntax Trees (AST). Unlike AST, which captures syntactic structure of code, our framework models semantic relationships between code elements, enabling the generation of more nuanced and diverse data. The feature tree is constructed from raw data and refined iteratively to increase the quantity and diversity of the extracted features. This process enables the identification of more complex patterns and relationships within the code. By sampling subtrees with controlled depth and breadth, our framework allows precise adjustments to the complexity of the generated code, supporting a wide range of tasks from simple function-level operations to intricate multi-file scenarios. We fine-tuned widely-used base models to create the EpiCoder series, achieving state-of-the-art performance at both the function and file levels across multiple benchmarks. Notably, empirical evidence indicates that our approach shows significant potential in synthesizing highly complex repository-level code data. Further analysis elucidates the merits of this approach by rigorously assessing data complexity and diversity through software engineering principles and LLM-as-a-judge method. 

**Abstract (ZH)**: 有效的指令调整对于优化代码LLM至关重要，能够使模型行为与用户期望一致，并提高模型在实际应用中的性能。然而，现有的大多数方法仅关注代码片段，这些片段局限于特定的功能和固定的结构，限制了合成数据的复杂性和多样性。为了解决这些局限性，我们引入了一种基于特征树的新合成框架，该框架借鉴了抽象语法树（AST）的思想。与仅捕获代码语法结构的AST不同，我们的框架建模了代码元素之间的语义关系，从而能够生成更为细致和多样化的数据。特征树从原始数据中构建，并通过迭代精炼以增加提取特征的数量和多样性。这一过程能够识别代码中的更为复杂的模式和关系。通过受控深度和广度地抽样子树，我们的框架允许精确调整生成代码的复杂度，支持从简单的函数级操作到复杂的多文件场景的各种任务。我们对广泛使用的基模型进行了微调，以创建EpiCoder系列模型，在多个基准测试中实现了在函数和文件级别上的顶级性能。值得注意的是，实验证据表明，我们的方法在合成高级别的代码数据方面表现出显著潜力。进一步的分析通过软件工程原则和LLM作为裁判的方法，严格评估了数据复杂性和多样性的优势，阐明了该方法的优点。 

---
# URSA: Understanding and Verifying Chain-of-thought Reasoning in Multimodal Mathematics 

**Title (ZH)**: URSA：理解与验证多模态数学中的链式推理 

**Authors**: Ruilin Luo, Zhuofan Zheng, Yifan Wang, Yiyao Yu, Xinzhe Ni, Zicheng Lin, Jin Zeng, Yujiu Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04686)  

**Abstract**: Chain-of-thought (CoT) reasoning has been widely applied in the mathematical reasoning of Large Language Models (LLMs). Recently, the introduction of derivative process supervision on CoT trajectories has sparked discussions on enhancing scaling capabilities during test time, thereby boosting the potential of these models. However, in multimodal mathematical reasoning, the scarcity of high-quality CoT training data has hindered existing models from achieving high-precision CoT reasoning and has limited the realization of reasoning potential during test time. In this work, we propose a three-module synthesis strategy that integrates CoT distillation, trajectory-format rewriting, and format unification. It results in a high-quality CoT reasoning instruction fine-tuning dataset in multimodal mathematics, MMathCoT-1M. We comprehensively validate the state-of-the-art (SOTA) performance of the trained URSA-7B model on multiple multimodal mathematical benchmarks. For test-time scaling, we introduce a data synthesis strategy that automatically generates process annotation datasets, known as DualMath-1.1M, focusing on both interpretation and logic. By further training URSA-7B on DualMath-1.1M, we transition from CoT reasoning capabilities to robust supervision abilities. The trained URSA-RM-7B acts as a verifier, effectively enhancing the performance of URSA-7B at test time. URSA-RM-7B also demonstrates excellent out-of-distribution (OOD) verifying capabilities, showcasing its generalization. Model weights, training data and code will be open-sourced. 

**Abstract (ZH)**: 链式推理（CoT）方法在大型语言模型（LLMs）的数学推理中得到了广泛应用。最近，在CoT轨迹引入衍生过程监督机制引起了关于提升测试时扩展能力的讨论，从而提高了这些模型的潜力。然而，在多模态数学推理中，高质量CoT训练数据的稀缺限制了现有模型实现高精度的CoT推理，并且在测试时限制了推理潜力的发挥。在本项工作中，我们提出了一种三模块合成策略，该策略结合了CoT蒸馏、轨迹格式重写和格式统一。它生成了一个高质量的多模态数学CoT推理指令微调数据集，即MMathCoT-1M。我们全面验证了在多个多模态数学基准上训练的URSA-7B模型的最先进的（SOTA）性能。为了扩展测试时的性能，在测试时我们引入了一种数据合成策略，自动生成过程注解数据集，名为DualMath-1.1M，这重点关注解释和逻辑。通过在DualMath-1.1M上进一步训练URSA-7B，我们从CoT推理能力过渡到稳健的监督能力。经过训练的URSA-RM-7B充当验证器，在测试时有效提高了URSA-7B的性能。URSA-RM-7B还展示了出色的离分布验证能力，展示了其泛化能力。模型权重、训练数据和代码将开源。 

---
# Enhancing Financial VQA in Vision Language Models using Intermediate Structured Representations 

**Title (ZH)**: 使用中间结构表示增强视觉语言模型中的财务视觉问答 

**Authors**: Archita Srivastava, Abhas Kumar, Rajesh Kumar, Prabhakar Srinivasan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04675)  

**Abstract**: Chart interpretation is crucial for visual data analysis, but accurately extracting information from charts poses significant challenges for automated models. This study investigates the fine-tuning of DEPLOT, a modality conversion module that translates the image of a plot or chart to a linearized table, on a custom dataset of 50,000 bar charts. The dataset comprises simple, stacked, and grouped bar charts, targeting the unique structural features of these visualizations. The finetuned DEPLOT model is evaluated against its base version using a test set of 1,000 images and two metrics: Relative Mapping Similarity (RMS), which measures categorical mapping accuracy, and Relative Number Set Similarity (RNSS), which evaluates numerical interpretation accuracy. To further explore the reasoning capabilities of large language models (LLMs), we curate an additional set of 100 bar chart images paired with question answer sets. Our findings demonstrate that providing a structured intermediate table alongside the image significantly enhances LLM reasoning performance compared to direct image queries. 

**Abstract (ZH)**: 图表解析对于可视化数据分析至关重要，但从图表中准确提取信息对自动化模型提出了重大挑战。本研究探讨了在包含50,000个条形图的自定义数据集上微调DEPLOT模块的情况，该模块是一种模态转换模块，能够将图表或图形图像转换为线性表。该数据集包括简单的、叠置的和分组的条形图，旨在捕捉这些可视化图表的独特结构特征。经过微调的DEPLOT模型使用包含1,000张图像的测试集以及两类度量标准进行评估：相对映射相似度（RMS），用于衡量分类映射准确性；相对数集相似度（RNSS），用于评估数值解释准确性。为进一步探究大语言模型（LLMs）的推理能力，我们还精心挑选了100张条形图，并为每张图配对了一个问题和答案集。我们的研究结果表明，在图像旁边提供一个结构化的中间表格，可以显著提高LLMs的推理性能，相比于直接进行图像查询。 

---
# On The Origin of Cultural Biases in Language Models: From Pre-training Data to Linguistic Phenomena 

**Title (ZH)**: 语言模型中文化偏见的起源：从预训练数据到语言现象 

**Authors**: Tarek Naous, Wei Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04662)  

**Abstract**: Language Models (LMs) have been shown to exhibit a strong preference towards entities associated with Western culture when operating in non-Western languages. In this paper, we aim to uncover the origins of entity-related cultural biases in LMs by analyzing several contributing factors, including the representation of entities in pre-training data and the impact of variations in linguistic phenomena across languages. We introduce CAMeL-2, a parallel Arabic-English benchmark of 58,086 entities associated with Arab and Western cultures and 367 masked natural contexts for entities. Our evaluations using CAMeL-2 reveal reduced performance gaps between cultures by LMs when tested in English compared to Arabic. We find that LMs struggle in Arabic with entities that appear at high frequencies in pre-training, where entities can hold multiple word senses. This also extends to entities that exhibit high lexical overlap with languages that are not Arabic but use the Arabic script. Further, we show how frequency-based tokenization leads to this issue in LMs, which gets worse with larger Arabic vocabularies. We will make CAMeL-2 available at: this https URL 

**Abstract (ZH)**: 语言模型（LMs）在非西方语言中已被证明倾向于偏好与西方文化相关联的实体。本文旨在通过分析多个促成因素，揭示LMs中实体相关文化偏见的起源，包括预训练数据中实体的表示及其在不同语言中语言现象变化的影响。我们引入了CAMeL-2，这是一个包含58,086个与阿拉伯文化和西方文化相关的实体及其367个掩码自然语境的平行阿拉伯语-英语基准数据集。使用CAMeL-2进行的评估表明，当在英语中测试时，LMs在文化性能差距上比在阿拉伯语中表现得更好。我们发现，在阿拉伯语中，LMs难以处理在预训练数据中出现频率较高的实体，特别是那些具有多个词义的实体。这种情况也扩展到了那些在阿拉伯字母书写系统中使用但不是阿拉伯语的其他语言的实体中。此外，我们展示了基于频率的分词方法导致这一问题在LMs中出现，并且随着阿拉伯语词汇量的增加而变得更加严重。我们将公开发布CAMeL-2数据集，链接为：this https URL 

---
# Assessing Language Comprehension in Large Language Models Using Construction Grammar 

**Title (ZH)**: 使用构造语法评估大规模语言模型的语言理解能力 

**Authors**: Wesley Scivetti, Melissa Torgbi, Austin Blodgett, Mollie Shichman, Taylor Hudson, Claire Bonial, Harish Tayyar Madabushi  

**Link**: [PDF](https://arxiv.org/pdf/2501.04661)  

**Abstract**: Large Language Models, despite their significant capabilities, are known to fail in surprising and unpredictable ways. Evaluating their true `understanding' of language is particularly challenging due to the extensive web-scale data they are trained on. Therefore, we construct an evaluation to systematically assess natural language understanding (NLU) in LLMs by leveraging Construction Grammar (CxG), which provides insights into the meaning captured by linguistic elements known as constructions (Cxns). CxG is well-suited for this purpose because provides a theoretical basis to construct targeted evaluation sets. These datasets are carefully constructed to include examples which are unlikely to appear in pre-training data, yet intuitive and easy for humans to understand, enabling a more targeted and reliable assessment. Our experiments focus on downstream natural language inference and reasoning tasks by comparing LLMs' understanding of the underlying meanings communicated through 8 unique Cxns with that of humans. The results show that while LLMs demonstrate some knowledge of constructional information, even the latest models including GPT-o1 struggle with abstract meanings conveyed by these Cxns, as demonstrated in cases where test sentences are dissimilar to their pre-training data. We argue that such cases provide a more accurate test of true language understanding, highlighting key limitations in LLMs' semantic capabilities. We make our novel dataset and associated experimental data including prompts and model responses publicly available. 

**Abstract (ZH)**: 尽管大型语言模型具有显著的能力，但在令人惊讶且不可预测的方式上会出错。由于这些模型是在大量网络数据上进行训练的，因此评估它们对语言的真正理解是具有挑战性的。因此，我们构建了一种评估方法，以便系统地通过构式语法（CxG）评估大型语言模型（LLMs）的自然语言理解（NLU），CxG 为语言学元素（即构式 Cxns）所捕捉的意义提供了理论洞察。CxG 正适合这一目的，因为它提供了构建针对性评估集的理论基础。这些数据集经过精心设计，包含了在预训练数据中很少出现但对人类而言直观且易于理解的示例，从而能够实现更加针对性和可靠的有效评估。我们的实验侧重于下游自然语言推理和语义推理任务，通过比较在 8 种独特构式 Cxns 中传达的潜在意义的理解，将 LLMs 的理解与人类的理解进行比较。结果表明，尽管 LLMs 在某些构式信息方面表现出一些知识，但即使是最新模型（包括 GPT-1）也难以处理这些 Cxns 所传达的抽象意义，特别是在测试句与预训练数据不相似的情况下。我们认为，这种情况下提供了对真正语言理解的更准确测试，突显了 LLMs 在语义能力方面的关键限制。我们公开发布了我们的新颖数据集以及相关的实验数据，包括提示和模型响应。 

---
# Multi-task retriever fine-tuning for domain-specific and efficient RAG 

**Title (ZH)**: 面向特定领域且高效的RAG的多任务检索器微调 

**Authors**: Patrice Béchard, Orlando Marquez Ayala  

**Link**: [PDF](https://arxiv.org/pdf/2501.04652)  

**Abstract**: Retrieval-Augmented Generation (RAG) has become ubiquitous when deploying Large Language Models (LLMs), as it can address typical limitations such as generating hallucinated or outdated information. However, when building real-world RAG applications, practical issues arise. First, the retrieved information is generally domain-specific. Since it is computationally expensive to fine-tune LLMs, it is more feasible to fine-tune the retriever to improve the quality of the data included in the LLM input. Second, as more applications are deployed in the same real-world system, one cannot afford to deploy separate retrievers. Moreover, these RAG applications normally retrieve different kinds of data. Our solution is to instruction fine-tune a small retriever encoder on a variety of domain-specific tasks to allow us to deploy one encoder that can serve many use cases, thereby achieving low-cost, scalability, and speed. We show how this encoder generalizes to out-of-domain settings as well as to an unseen retrieval task on real-world enterprise use cases. 

**Abstract (ZH)**: 检索增强生成（RAG）已经在部署大语言模型（LLMs）时变得无处不在，因为它可以解决诸如生成幻觉或过时信息等典型限制。然而，在构建实际的RAG应用时，实际问题也会出现。首先，检索到的信息通常具有领域特定性。由于对LLMs进行微调计算成本较高，更可行的方式是对检索器进行微调以提高LLMs输入中包含的数据质量。其次，随着越来越多的应用部署在同一实际系统中，无法为每个应用单独部署检索器。此外，这些RAG应用通常需要检索不同种类的数据。我们的解决方案是，在多种领域特定任务上对小型检索编码器进行指令微调，从而允许我们部署一个能服务于多种应用场景的编码器，从而实现低成本、可扩展性和快速响应。我们展示了该编码器在领域外环境以及在真实企业应用的未见检索任务中的泛化能力。 

---
# Quantum-inspired Embeddings Projection and Similarity Metrics for Representation Learning 

**Title (ZH)**: 量子启发的嵌入投影及相似性度量在表示学习中的应用 

**Authors**: Ivan Kankeu, Stefan Gerd Fritsch, Gunnar Schönhoff, Elie Mounzer, Paul Lukowicz, Maximilian Kiefer-Emmanouilidis  

**Link**: [PDF](https://arxiv.org/pdf/2501.04591)  

**Abstract**: Over the last decade, representation learning, which embeds complex information extracted from large amounts of data into dense vector spaces, has emerged as a key technique in machine learning. Among other applications, it has been a key building block for large language models and advanced computer vision systems based on contrastive learning. A core component of representation learning systems is the projection head, which maps the original embeddings into different, often compressed spaces, while preserving the similarity relationship between vectors.
In this paper, we propose a quantum-inspired projection head that includes a corresponding quantum-inspired similarity metric. Specifically, we map classical embeddings onto quantum states in Hilbert space and introduce a quantum circuit-based projection head to reduce embedding dimensionality. To evaluate the effectiveness of this approach, we extended the BERT language model by integrating our projection head for embedding compression. We compared the performance of embeddings, which were compressed using our quantum-inspired projection head, with those compressed using a classical projection head on information retrieval tasks using the TREC 2019 and TREC 2020 Deep Learning benchmarks. The results demonstrate that our quantum-inspired method achieves competitive performance relative to the classical method while utilizing 32 times fewer parameters. Furthermore, when trained from scratch, it notably excels, particularly on smaller datasets. This work not only highlights the effectiveness of the quantum-inspired approach but also emphasizes the utility of efficient, ad hoc low-entanglement circuit simulations within neural networks as a powerful quantum-inspired technique. 

**Abstract (ZH)**: 在过去十年中，表示学习作为一种将大量数据中提取的复杂信息嵌入到密集向量空间中的关键技术，在机器学习领域得到了快速发展。它在大型语言模型和其他应用中发挥了关键作用，并且在基于对比学习的高级计算机视觉系统中也起到了关键作用。表示学习系统的核心组件是投影头，它将原始嵌入映射到不同的，往往是压缩的空间中，同时保留向量之间的相似性关系。

在本文中，我们提出了一种受量子启发的投影头，其中包括相应的量子启发相似度度量。具体来说，我们通过将经典嵌入映射到希尔伯特空间中的量子态来降低嵌入维度，并引入基于量子电路的投影头。为了评估该方法的有效性，我们通过将我们的投影头整合到BERT语言模型中来扩展BERT模型，来进行嵌入压缩，并在TREC 2019和TREC 2020深度学习基准测试的信息检索任务中将使用我们受量子启发的投影头压缩的嵌入与使用经典投影头压缩的嵌入进行了对比。结果表明，与经典方法相比，我们的量子启发方法在参数数量减少了32倍的情况下，实现了相当的竞争性能。此外，在从头训练时，它在小数据集上的表现尤为突出。这项工作不仅突显了量子启发方法的有效性，还强调了在神经网络中利用高效且适配的低纠缠量子电路模拟作为一种强大的量子启发技术的重要性。 

---
# OpenOmni: Large Language Models Pivot Zero-shot Omnimodal Alignment across Language with Real-time Self-Aware Emotional Speech Synthesis 

**Title (ZH)**: OpenOmni：大规模语言模型实现跨语言的零样本全模态对齐，并结合实时自我意识情感语音合成 

**Authors**: Run Luo, Ting-En Lin, Haonan Zhang, Yuchuan Wu, Xiong Liu, Min Yang, Yongbin Li, Longze Chen, Jiaming Li, Lei Zhang, Yangyi Chen, Hamid Alinejad-Rokny, Fei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04561)  

**Abstract**: Recent advancements in omnimodal learning have been achieved in understanding and generation across images, text, and speech, though mainly within proprietary models. Limited omnimodal datasets and the inherent challenges associated with real-time emotional speech generation have hindered open-source progress. To address these issues, we propose openomni, a two-stage training method combining omnimodal alignment and speech generation to develop a state-of-the-art omnimodal large language model. In the alignment phase, a pre-trained speech model is further trained on text-image tasks to generalize from vision to speech in a (near) zero-shot manner, outperforming models trained on tri-modal datasets. In the speech generation phase, a lightweight decoder facilitates real-time emotional speech through training on speech tasks and preference learning. Experiments demonstrate that openomni consistently improves across omnimodal, vision-language, and speech-language evaluations, enabling natural, emotion-rich dialogues and real-time emotional speech generation. 

**Abstract (ZH)**: 近年来，多模态学习在图像、文本和语音的理解与生成方面取得了显著进展，尽管这些进步主要局限于私有模型中。受限于有限的多模态数据集以及实时情感语音生成固有的挑战，开源进展受到阻碍。为解决这些问题，我们提出了一种双重训练方法Openomni，该方法结合了多模态对齐和语音生成，旨在开发出领先水平的多模态大规模语言模型。在对齐阶段，通过进一步训练预训练的语音模型来执行文本-图像任务，使其能够以（近）零样本方式从视觉领域向语音领域泛化，性能优于基于三模态数据集训练的模型。在语音生成阶段，通过语音任务训练和偏好学习，轻量级解码器能够促进实时情感语音的生成。实验结果表明，Openomni在多模态、视觉语言和语音语言评估中均表现出持续改进，能够实现自然、富有情感的对话以及实时情感语音生成。 

---
# rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking 

**Title (ZH)**: rStar-Math：小型LLM可以通过自我进化深入思考来掌握数学推理 

**Authors**: Xinyu Guan, Li Lyna Zhang, Yifei Liu, Ning Shang, Youran Sun, Yi Zhu, Fan Yang, Mao Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04519)  

**Abstract**: We present rStar-Math to demonstrate that small language models (SLMs) can rival or even surpass the math reasoning capability of OpenAI o1, without distillation from superior models. rStar-Math achieves this by exercising "deep thinking" through Monte Carlo Tree Search (MCTS), where a math policy SLM performs test-time search guided by an SLM-based process reward model. rStar-Math introduces three innovations to tackle the challenges in training the two SLMs: (1) a novel code-augmented CoT data sythesis method, which performs extensive MCTS rollouts to generate step-by-step verified reasoning trajectories used to train the policy SLM; (2) a novel process reward model training method that avoids naïve step-level score annotation, yielding a more effective process preference model (PPM); (3) a self-evolution recipe in which the policy SLM and PPM are built from scratch and iteratively evolved to improve reasoning capabilities. Through 4 rounds of self-evolution with millions of synthesized solutions for 747k math problems, rStar-Math boosts SLMs' math reasoning to state-of-the-art levels. On the MATH benchmark, it improves Qwen2.5-Math-7B from 58.8% to 90.0% and Phi3-mini-3.8B from 41.4% to 86.4%, surpassing o1-preview by +4.5% and +0.9%. On the USA Math Olympiad (AIME), rStar-Math solves an average of 53.3% (8/15) of problems, ranking among the top 20% the brightest high school math students. Code and data will be available at this https URL. 

**Abstract (ZH)**: 我们提出rStar-Math，以证明小型语言模型（SLMs）可以与甚至超越OpenAI o1在数学推理能力上的表现，而无需从更优秀的模型中进行蒸馏。rStar-Math通过蒙特卡洛树搜索（MCTS）实现“深度思考”，其中数学策略SLM根据基于过程奖励模型的SLM过程引导进行测试时搜索。rStar-Math提出了三种创新方法来应对训练两个SLM所面临的挑战：（1）一种新颖的代码增强型CoT数据合成方法，通过执行广泛的MCTS展开来生成经过逐步验证的推理轨迹，用于训练策略SLM；（2）一种新型的过程奖励模型训练方法，避免了简单的步骤级评分注释，生成更有效的过程偏好模型（PPM）；（3）一种自我进化方法，在这种方法中，策略SLM和PPM从头构建并通过迭代进化提高推理能力。通过四轮自我进化并对74.7万个数学问题生成数百万种合成解决方案，rStar-Math将SLMs的数学推理能力提升至最新的技术水平。在MATH基准测试中，它将Qwen2.5-Math-7B的得分从58.8%提高到90.0%，将Phi3-mini-3.8B的得分从41.4%提高到86.4%，分别超越o1-preview 4.5%和0.9%。在美国数学奥林匹克（AIME）中，rStar-Math平均解决8/15（53.3%）个问题，其表现跻身最亮高中生数学能力的前20%。代码和数据将在此处提供：[此链接]。 

---
# PolInterviews -- A Dataset of German Politician Public Broadcast Interviews 

**Title (ZH)**: PolInterviews -- 德国政治家公共广播访谈数据集 

**Authors**: Lukas Birkenmaier, Laureen Sieber, Felix Bergstein  

**Link**: [PDF](https://arxiv.org/pdf/2501.04484)  

**Abstract**: This paper presents a novel dataset of public broadcast interviews featuring high-ranking German politicians. The interviews were sourced from YouTube, transcribed, processed for speaker identification, and stored in a tidy and open format. The dataset comprises 99 interviews with 33 different German politicians across five major interview formats, containing a total of 28,146 sentences. As the first of its kind, this dataset offers valuable opportunities for research on various aspects of political communication in the (German) political contexts, such as agenda-setting, interviewer dynamics, or politicians' self-presentation. 

**Abstract (ZH)**: 本文介绍了首个包含较高层级德国政要访谈的公开广播数据集。该数据集来源于YouTube，已完成转录、处理以实现说话人识别，并以整洁且开放的形式存储。数据集包括99场访谈，涉及33位不同德国政要，并涵盖五种主要访谈格式，共计包含28,146个句子。作为其领域的首创之作，该数据集为研究德国政治背景下（诸如议程设置、访谈者动态或政界人士的自我呈现等）的各种政治传播方面提供了宝贵的机会。 

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
# Who Does the Giant Number Pile Like Best: Analyzing Fairness in Hiring Contexts 

**Title (ZH)**: 《大數據背景下的公平 Hiring 分析：谁是最受偏爱的求职者》

注：这里的"Hiring"在上下文中主要是指招聘、入职等含义，根据具体语境，也可以翻译为“招聘过程中的公平性分析：谁最受青睐”。为了更符合中文的表达习惯和学术规范，翻译时可以适当调整，以确保学术严谨性和流畅度。 

**Authors**: Preethi Seshadri, Seraphina Goldfarb-Tarrant  

**Link**: [PDF](https://arxiv.org/pdf/2501.04316)  

**Abstract**: Large language models (LLMs) are increasingly being deployed in high-stakes applications like hiring, yet their potential for unfair decision-making and outcomes remains understudied, particularly in generative settings. In this work, we examine the fairness of LLM-based hiring systems through two real-world tasks: resume summarization and retrieval. By constructing a synthetic resume dataset and curating job postings, we investigate whether model behavior differs across demographic groups and is sensitive to demographic perturbations. Our findings reveal that race-based differences appear in approximately 10% of generated summaries, while gender-based differences occur in only 1%. In the retrieval setting, all evaluated models display non-uniform selection patterns across demographic groups and exhibit high sensitivity to both gender and race-based perturbations. Surprisingly, retrieval models demonstrate comparable sensitivity to non-demographic changes, suggesting that fairness issues may stem, in part, from general brittleness issues. Overall, our results indicate that LLM-based hiring systems, especially at the retrieval stage, can exhibit notable biases that lead to discriminatory outcomes in real-world contexts. 

**Abstract (ZH)**: 大规模语言模型（LLMs）越来越多地被部署在高风险的应用场景中，如招聘，然而它们在生成环境下潜在的不公平决策及其结果仍未得到充分研究。在这项工作中，我们通过两个实际任务——简历摘要和检索——来探讨LLM驱动的招聘系统的公平性。通过构建一个合成简历数据集并收集招聘信息，我们研究了模型行为在不同人口统计群体之间的差异及其如何受到人口统计学扰动的影响。研究发现，在生成的摘要中约10%存在基于种族的差异，而基于性别的差异则仅占1%。在检索场景中，所有评估的模型在不同人口统计群体中的选择模式均表现出非均匀性，并且对基于性别的和基于种族的变化极其敏感。令人惊讶的是，检索模型对非人口统计学变化同样表现出相当的敏感性，这表明公平性问题可能部分源自一般性脆弱性问题。总体而言，我们的结果表明，尤其是检索阶段，基于LLM的招聘系统在实际场景中可能会显示出显著的偏见，导致歧视性结果。 

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
# Multimodal Multihop Source Retrieval for Web Question Answering 

**Title (ZH)**: 多模态多跳源检索在网页问答中的应用 

**Authors**: Navya Yarrabelly, Saloni Mittal  

**Link**: [PDF](https://arxiv.org/pdf/2501.04173)  

**Abstract**: This work deals with the challenge of learning and reasoning over multi-modal multi-hop question answering (QA). We propose a graph reasoning network based on the semantic structure of the sentences to learn multi-source reasoning paths and find the supporting facts across both image and text modalities for answering the question. In this paper, we investigate the importance of graph structure for multi-modal multi-hop question answering. Our analysis is centered on WebQA. We construct a strong baseline model, that finds relevant sources using a pairwise classification task. We establish that, with the proper use of feature representations from pre-trained models, graph structure helps in improving multi-modal multi-hop question answering. We point out that both graph structure and adjacency matrix are task-related prior knowledge, and graph structure can be leveraged to improve the retrieval performance for the task. Experiments and visualized analysis demonstrate that message propagation over graph networks or the entire graph structure can replace massive multimodal transformers with token-wise cross-attention. We demonstrated the applicability of our method and show a performance gain of \textbf{4.6$\%$} retrieval F1score over the transformer baselines, despite being a very light model. We further demonstrated the applicability of our model to a large scale retrieval setting. 

**Abstract (ZH)**: 本文探讨了多模态多跳问答（QA）中的学习与推理挑战。我们提出了一种基于句子语义结构的图推理网络，用于学习多源推理路径，并在图像和文本模态之间寻找支持事实以回答问题。在本文中，我们研究了图结构在多模态多跳问答中的重要性。我们分析集中在WebQA上。我们构建了一个强大的基线模型，该模型通过一对多分类任务找到相关来源。我们证明，在适当使用预训练模型的特征表示时，图结构有助于提高多模态多跳问答的效果。我们指出，图结构和邻接矩阵都是与任务相关的先验知识，并且图结构可以利用以改进任务的检索性能。实验和可视化分析表明，图网络中的消息传递或整个图结构可以替代大规模多模态变压器，使用基于令牌的交叉注意机制。我们展示了该方法的应用范围，并在一个非常轻量级的模型上取得了4.6%的检索F1分数改进，尽管这是一个非常轻量级的模型。此外，我们还展示了该模型在大规模检索场景中的应用范围。 

---
# Reasoning-Enhanced Self-Training for Long-Form Personalized Text Generation 

**Title (ZH)**: 增强推理的自我训练方法用于长格式个性化文本生成 

**Authors**: Alireza Salemi, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Weize Kong, Tao Chen, Zhuowan Li, Michael Bendersky, Hamed Zamani  

**Link**: [PDF](https://arxiv.org/pdf/2501.04167)  

**Abstract**: Personalized text generation requires a unique ability of large language models (LLMs) to learn from context that they often do not encounter during their standard training. One way to encourage LLMs to better use personalized context for generating outputs that better align with the user's expectations is to instruct them to reason over the user's past preferences, background knowledge, or writing style. To achieve this, we propose Reasoning-Enhanced Self-Training for Personalized Text Generation (REST-PG), a framework that trains LLMs to reason over personal data during response generation. REST-PG first generates reasoning paths to train the LLM's reasoning abilities and then employs Expectation-Maximization Reinforced Self-Training to iteratively train the LLM based on its own high-reward outputs. We evaluate REST-PG on the LongLaMP benchmark, consisting of four diverse personalized long-form text generation tasks. Our experiments demonstrate that REST-PG achieves significant improvements over state-of-the-art baselines, with an average relative performance gain of 14.5% on the benchmark. 

**Abstract (ZH)**: 个性化文本生成需要大型语言模型（LLMs）具备一种独特的能力——从训练中很少遇到的实际上下文中学习。为了鼓励LLMs更好地利用个性化的上下文来生成更符合用户期望的输出，一种方法是指导它们推理用户的过去偏好、背景知识或写作风格。为了实现这一点，我们提出了增强推理的自我训练以进行个性化文本生成（REST-PG）框架，该框架在响应生成过程中训练LLMs推理个人数据的能力。REST-PG首先生成推理路径以训练LLMs的推理能力，然后通过期望最大化强化自我训练迭代训练LLMs，基于其高奖励输出。我们在包含四个多样化的个性化长文本生成任务的LongLaMP基准上评估了REST-PG。实验结果表明，REST-PG在基准测试上的性能显著提升，相对性能平均提高了14.5%。 

---
# Multilingual Open QA on the MIA Shared Task 

**Title (ZH)**: 多语言开源问答挑战任务中的MIA共享任务 

**Authors**: Navya Yarrabelly, Saloni Mittal, Ketan Todi, Kimihiro Hasegawa  

**Link**: [PDF](https://arxiv.org/pdf/2501.04153)  

**Abstract**: Cross-lingual information retrieval (CLIR) ~\cite{shi2021cross, asai2021one, jiang2020cross} for example, can find relevant text in any language such as English(high resource) or Telugu (low resource) even when the query is posed in a different, possibly low-resource, language. In this work, we aim to develop useful CLIR models for this constrained, yet important, setting where we do not require any kind of additional supervision or labelled data for retrieval task and hence can work effectively for low-resource languages.
\par We propose a simple and effective re-ranking method for improving passage retrieval in open question answering. The re-ranker re-scores retrieved passages with a zero-shot multilingual question generation model, which is a pre-trained language model, to compute the probability of the input question in the target language conditioned on a retrieved passage, which can be possibly in a different language. We evaluate our method in a completely zero shot setting and doesn't require any training. Thus the main advantage of our method is that our approach can be used to re-rank results obtained by any sparse retrieval methods like BM-25. This eliminates the need for obtaining expensive labelled corpus required for the retrieval tasks and hence can be used for low resource languages. 

**Abstract (ZH)**: 跨语言信息检索（CLIR）例如，可以找到任何语言中的相关文本，如英语（高资源）或特伦甘纳语（低资源），即使查询语句是用不同且可能是低资源的语言提出。在本工作中，我们旨在开发适用于这种受限但重要的场景的CLIR模型，我们不要求提供任何额外的监督或标注数据来进行检索任务，因此可以有效地应用于低资源语言。

我们提出了一种简单且有效的再排序方法，以改善开放问题回答中的段落检索。再排序器使用零样本多语言问题生成模型（这是一种预训练的语言模型）重新评分检索到的段落，计算输入问题在目标语言（可能是不同语言）条件下在一个检索到的段落上的概率。我们完全在零样本设置下评估了该方法，不需要任何训练。因此，我们方法的主要优势在于，我们的方法可以用于重新排序任何稀疏检索方法（如BM-25）得到的结果。这消除了获取用于检索任务的昂贵标注语料库的需要，因此可以应用于低资源语言。 

---
# "Yeah Right!" -- Do LLMs Exhibit Multimodal Feature Transfer? 

**Title (ZH)**: “yeah right！”——大型语言模型是否表现出跨模态特征迁移？ 

**Authors**: Benjamin Reichman, Kartik Talamadupula  

**Link**: [PDF](https://arxiv.org/pdf/2501.04138)  

**Abstract**: Human communication is a multifaceted and multimodal skill. Communication requires an understanding of both the surface-level textual content and the connotative intent of a piece of communication. In humans, learning to go beyond the surface level starts by learning communicative intent in speech. Once humans acquire these skills in spoken communication, they transfer those skills to written communication. In this paper, we assess the ability of speech+text models and text models trained with special emphasis on human-to-human conversations to make this multimodal transfer of skill. We specifically test these models on their ability to detect covert deceptive communication. We find that with no special prompting speech+text LLMs have an advantage over unimodal LLMs in performing this task. Likewise, we find that human-to-human conversation-trained LLMs are also advantaged in this skill. 

**Abstract (ZH)**: 人类沟通是一项多维度和多模态的技能。沟通不仅要求理解文本内容的表面意义，还需理解其隐含意图。在人类中，学会超越表面层次的沟通始于对言语沟通意图的理解。一旦人类在口头沟通中掌握这些技能，便会将这些技能转移到书面沟通中。在本文中，我们评估了多模态言语+文本模型和具备特别强调人际沟通训练的文本模型在实现这种跨模式技能迁移方面的能力。我们特别测试了这些模型在检测隐蔽欺骗性沟通方面的能力。我们发现，在没有特别提示的情况下，多模态言语+文本的大规模语言模型（LLM）在这项任务上的表现优于单一模态的大规模语言模型。同样，我们发现具备人际沟通训练的大规模语言模型在这一技能上也具有优势。 

---
# A Survey on Large Language Models with some Insights on their Capabilities and Limitations 

**Title (ZH)**: 大型语言模型综述：一些关于其能力与局限性的见解 

**Authors**: Andrea Matarazzo, Riccardo Torlone  

**Link**: [PDF](https://arxiv.org/pdf/2501.04040)  

**Abstract**: The rapid advancement of artificial intelligence, particularly with the development of Large Language Models (LLMs) built on the transformer architecture, has redefined the capabilities of natural language processing. These models now exhibit remarkable performance across various language-related tasks, such as text generation, question answering, translation, and summarization, often rivaling human-like comprehension. More intriguingly, LLMs have demonstrated emergent abilities extending beyond their core functions, showing proficiency in tasks like commonsense reasoning, code generation, and arithmetic. This survey paper explores the foundational components, scaling mechanisms, and architectural strategies that drive these capabilities. Emphasizing models like GPT and LLaMA, we analyze the impact of exponential data and computational growth on LLM performance, while also addressing the trade-offs associated with scaling. We also examine LLM applications across sectors, such as healthcare, finance, education, and law, highlighting their adaptability and potential to solve domain-specific challenges. Central to this work are the questions of how LLMs generalize across diverse tasks, exhibit planning, and reasoning abilities, and whether these emergent abilities can be systematically elicited or enhanced. In particular, we provide some insights into the CoT (Chain of Thought) and PoT (Plan of Thought) abilities within LLMs, focusing on how pre-training data influences their emergence. Additionally, we investigate LLM-modulo frameworks that integrate external systems, allowing LLMs to handle complex, dynamic tasks. By analyzing these factors, this paper aims to foster the ongoing discussion on the capabilities and limits of LLMs, promoting their responsible development and application in novel and increasingly complex environments. 

**Abstract (ZH)**: 人工智能的迅猛发展，尤其是基于变换器架构的大型语言模型（LLMs）的发展，重新定义了自然语言处理的能力。这些模型现在在诸如文本生成、问答、翻译和摘要等各类语言相关任务中表现出色，其性能常常与人类的理解能力相媲美。更令人 intrigue 的是，LLMs 展示出超越其核心功能的新兴能力，显示出在常识推理、代码生成和算术等任务上的熟练度。本文综述了驱动这些能力的基础组件、扩增机制和架构策略。着重分析了 GPT 和 LLaMA 等模型，并探讨了指数级数据和计算增长对 LLM 性能的影响，同时讨论了扩增过程中所涉及的权衡。此外，我们还探讨了 LLM 在医疗保健、金融、教育和法律等领域的应用，突显其适应性和解决领域特定挑战的潜力。本文的核心问题在于 LLMs 在多样化任务上的泛化能力、计划和推理能力的展示，以及这些新兴能力能否得到系统性的激发或增强。特别地，我们对 LLM 中的 CoT（思维链）和 PoT（思维计划）能力进行了探讨，重点关注预训练数据如何影响它们的出现。此外，我们还研究了 LLM 融合外部系统的方法框架，以使 LLM 能够处理复杂的动态任务。通过对这些因素的分析，本文旨在促进对 LLMs 的能力及其限制的持续讨论，推动其负责任地开发和在不断复杂的新环境中应用。 

---
# Towards System 2 Reasoning in LLMs: Learning How to Think With Meta Chain-of-Though 

**Title (ZH)**: 向LLMs学习系统二层次推理：通过元链式思考进行思考学习 

**Authors**: Violet Xiang, Charlie Snell, Kanishk Gandhi, Alon Albalak, Anikait Singh, Chase Blagden, Duy Phung, Rafael Rafailov, Nathan Lile, Dakota Mahan, Louis Castricato, Jan-Philipp Franken, Nick Haber, Chelsea Finn  

**Link**: [PDF](https://arxiv.org/pdf/2501.04682)  

**Abstract**: We propose a novel framework, Meta Chain-of-Thought (Meta-CoT), which extends traditional Chain-of-Thought (CoT) by explicitly modeling the underlying reasoning required to arrive at a particular CoT. We present empirical evidence from state-of-the-art models exhibiting behaviors consistent with in-context search, and explore methods for producing Meta-CoT via process supervision, synthetic data generation, and search algorithms. Finally, we outline a concrete pipeline for training a model to produce Meta-CoTs, incorporating instruction tuning with linearized search traces and reinforcement learning post-training. Finally, we discuss open research questions, including scaling laws, verifier roles, and the potential for discovering novel reasoning algorithms. This work provides a theoretical and practical roadmap to enable Meta-CoT in LLMs, paving the way for more powerful and human-like reasoning in artificial intelligence. 

**Abstract (ZH)**: 我们提出了一种新的框架，即元思维链（Meta-CoT），它在传统思维链（CoT）的基础上扩展，通过明确建模达到特定CoT所需的潜在推理过程。我们展示了最先进的模型的行为与上下文搜索相符的实证证据，并探讨了通过流程监督、合成数据生成和搜索算法生成Meta-CoT的方法。最后，我们详细阐述了一个具体的训练模型生成Meta-CoT的流程，该流程结合了带有线性化搜索轨迹的指令微调和后训练的强化学习。最后，我们讨论了开放的研究问题，包括规模法则、验证者角色以及发现新推理算法的潜力。本文为在大规模语言模型（LLM）中实现Meta-CoT提供了理论和实践的路线图，为人工智能中的更强大和接近人类的推理铺平了道路。 

---
# FlairGPT: Repurposing LLMs for Interior Designs 

**Title (ZH)**: FlairGPT: 将大语言模型应用于室内设计 

**Authors**: Gabrielle Littlefair, Niladri Shekhar Dutt, Niloy J. Mitra  

**Link**: [PDF](https://arxiv.org/pdf/2501.04648)  

**Abstract**: Interior design involves the careful selection and arrangement of objects to create an aesthetically pleasing, functional, and harmonized space that aligns with the client's design brief. This task is particularly challenging, as a successful design must not only incorporate all the necessary objects in a cohesive style, but also ensure they are arranged in a way that maximizes accessibility, while adhering to a variety of affordability and usage considerations. Data-driven solutions have been proposed, but these are typically room- or domain-specific and lack explainability in their design design considerations used in producing the final layout. In this paper, we investigate if large language models (LLMs) can be directly utilized for interior design. While we find that LLMs are not yet capable of generating complete layouts, they can be effectively leveraged in a structured manner, inspired by the workflow of interior designers. By systematically probing LLMs, we can reliably generate a list of objects along with relevant constraints that guide their placement. We translate this information into a design layout graph, which is then solved using an off-the-shelf constrained optimization setup to generate the final layouts. We benchmark our algorithm in various design configurations against existing LLM-based methods and human designs, and evaluate the results using a variety of quantitative and qualitative metrics along with user studies. In summary, we demonstrate that LLMs, when used in a structured manner, can effectively generate diverse high-quality layouts, making them a viable solution for creating large-scale virtual scenes. Project webpage at this https URL 

**Abstract (ZH)**: 室内设计涉及精心选择和布置物体，以创建一个符合审美、功能性和和谐的环境，同时也需与客户的设计需求相符。这一任务特别具有挑战性，因为成功的方案不仅要以一种连贯的风格整合所有必要物体，还必须确保这些物体的摆放方式能够最大化地提高可达性，并且考虑到多种成本和使用方面的需求。尽管已经提出了数据驱动的解决方案，但这些方案通常局限于特定的房间或领域，并且在生成最终布局时缺乏解释性。在本文中，我们探讨了大型语言模型（LLMs）是否可以直接用于室内设计。尽管我们发现LLMs尚不具备生成完整布局的能力，但可以通过一种结构化的方式有效地利用它们，借鉴室内设计师的工作流程。通过系统地探究LLMs，我们可以可靠地生成物体列表及其相关约束条件，从而指导它们的布局。我们将这些信息转换为设计布局图，然后使用现成的约束优化方案生成最终布局。我们使用各种设计配置对我们的算法与现有的LLM基方法和人类设计进行了基准测试，并使用多种定量和定性指标以及用户研究来评估结果。总的来说，我们证明了，当以结构化方式使用时，LLMs能够有效地生成多样的高质量布局，使其成为创建大规模虚拟场景的有效解决方案。项目网站详见以下链接：[该项目网页链接] 

---
# InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection 

**Title (ZH)**: InfiGUIAgent：一种内生推理与反思能力的多模态通用GUI代理 

**Authors**: Yuhang Liu, Pengxiang Li, Zishu Wei, Congkai Xie, Xueyu Hu, Xinchen Xu, Shengyu Zhang, Xiaotian Han, Hongxia Yang, Fei Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04575)  

**Abstract**: Graphical User Interface (GUI) Agents, powered by multimodal large language models (MLLMs), have shown great potential for task automation on computing devices such as computers and mobile phones. However, existing agents face challenges in multi-step reasoning and reliance on textual annotations, limiting their effectiveness. We introduce \textit{InfiGUIAgent}, an MLLM-based GUI Agent trained with a two-stage supervised fine-tuning pipeline. Stage 1 enhances fundamental skills such as GUI understanding and grounding, while Stage 2 integrates hierarchical reasoning and expectation-reflection reasoning skills using synthesized data to enable native reasoning abilities of the agents. \textit{InfiGUIAgent} achieves competitive performance on several GUI benchmarks, highlighting the impact of native reasoning skills in enhancing GUI interaction for automation tasks. Resources are available at \url{this https URL}. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）驱动的图形用户界面（GUI）代理在计算设备（如计算机和移动电话）上的任务自动化方面展现了巨大的潜力。然而，现有的代理在多步推理和对文本注释的依赖上存在挑战，这限制了它们的效用。我们介绍了一种基于MLLM的两阶段监督微调管道训练的GUI代理——InfiGUIAgent。第一阶段增强基础技能，如GUI理解与定位，第二阶段通过合成数据集成层次推理和期望-反思推理技能，使代理具备原生推理能力。InfiGUIAgent在多个GUI基准测试中实现了竞争力的表现，突显了原生推理技能对提升GUI交互自动化的影响。有关资源请参阅 \url{此链接}。 

---
# Supervision-free Vision-Language Alignment 

**Title (ZH)**: 无监督视觉-语言对齐 

**Authors**: Giorgio Giannone, Ruoteng Li, Qianli Feng, Evgeny Perevodchikov, Rui Chen, Aleix Martinez  

**Link**: [PDF](https://arxiv.org/pdf/2501.04568)  

**Abstract**: Vision-language models (VLMs) have demonstrated remarkable potential in integrating visual and linguistic information, but their performance is often constrained by the need for extensive, high-quality image-text training data. Curation of these image-text pairs is both time-consuming and computationally expensive. To address this challenge, we introduce SVP (Supervision-free Visual Projection), a novel framework that enhances vision-language alignment without relying on curated data or preference annotation. SVP leverages self-captioning and a pre-trained grounding model as a feedback mechanism to elicit latent information in VLMs. We evaluate our approach across six key areas: captioning, referring, visual question answering, multitasking, hallucination control, and object recall. Results demonstrate significant improvements, including a 14% average improvement in captioning tasks, up to 12% increase in object recall, and substantial reduction in hallucination rates. Notably, a small VLM using SVP achieves hallucination reductions comparable to a model five times larger, while a VLM with initially poor referring capabilities more than doubles its performance, approaching parity with a model twice its size. 

**Abstract (ZH)**: 视觉语言模型（VLMs）在整合视觉和语言信息方面展现了显著的潜力，但其性能往往受限于需要广泛的高质量图像-文本训练数据。这些图像-文本配对的编目既耗时又计算成本高昂。为解决这一挑战，我们提出了一种新的框架——无监督视觉投影（SVP），该框架能够在不依赖于编目数据或偏好注解的情况下增强视觉语言对齐。SVP 利用自我标注和预训练的 grounding 模型作为反馈机制，以激发 VLMs 中的潜在信息。我们从六个关键方面评估了该方法：描述、引用、视觉问答、多任务处理、幻觉控制和对象回忆。结果显示，该方法在各个方面都取得了显著改进，包括描述任务平均改进14%，对象回忆率提高12%，幻觉率显著降低。值得注意的是，使用 SVP 的小型 VLM 在幻觉修正方面达到了比其大五倍模型相当的效果，而最初在引用方面表现不佳的 VLM 将其性能提高了两倍以上，接近其两倍大小模型的水平。 

---
# Improving Image Captioning by Mimicking Human Reformulation Feedback at Inference-time 

**Title (ZH)**: 通过在推断时模仿人类改写反馈来改进图像字幕生成 

**Authors**: Uri Berger, Omri Abend, Lea Frermann, Gabriel Stanovsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.04513)  

**Abstract**: Incorporating automatically predicted human feedback into the process of training generative models has attracted substantial recent interest, while feedback at inference time has received less attention. The typical feedback at training time, i.e., preferences of choice given two samples, does not naturally transfer to the inference phase. We introduce a novel type of feedback -- caption reformulations -- and train models to mimic reformulation feedback based on human annotations. Our method does not require training the image captioning model itself, thereby demanding substantially less computational effort. We experiment with two types of reformulation feedback: first, we collect a dataset of human reformulations that correct errors in the generated captions. We find that incorporating reformulation models trained on this data into the inference phase of existing image captioning models results in improved captions, especially when the original captions are of low quality. We apply our method to non-English image captioning, a domain where robust models are less prevalent, and gain substantial improvement. Second, we apply reformulations to style transfer. Quantitative evaluations reveal state-of-the-art performance on German image captioning and English style transfer, while human validation with a detailed comparative framework exposes the specific axes of improvement. 

**Abstract (ZH)**: 将生成模型训练过程纳入自动预测的人类反馈已引起广泛关注，而推理时的反馈则较少受到关注。训练时典型的反馈，即对两个样本的选择偏好，无法自然地应用于推理阶段。我们引入了一种新型反馈——字幕重述，并基于人类注释训练模型以模拟重述反馈。我们的方法无需重新训练图像字幕模型本身，从而减少了大量的计算需求。我们尝试了两种类型的重述反馈：首先，我们收集了一个包含人类重述的数据集，这些重述用于修正生成字幕中的错误。我们发现，将基于该数据集训练的重述模型纳入现有图像字幕模型的推理阶段，可以显著改善生成的字幕，尤其是在原字幕质量较低的情况下。我们将该方法应用于非英语图像字幕领域，该领域中稳健的模型较少，取得了显著的改进。其次，我们将重述应用于风格迁移。定量评估结果显示，在德语图像字幕和英语风格迁移方面达到了最先进的性能。详细的验证框架下的人类评估揭示了具体改进的轴线。 

---
# Developing a Modular Compiler for a Subset of a C-like Language 

**Title (ZH)**: 开发一种面向C-like语言子集的模块化编译器 

**Authors**: Debasish Dutta, Neeharika Sonowal, Irani Hazarika  

**Link**: [PDF](https://arxiv.org/pdf/2501.04503)  

**Abstract**: The paper introduces the development of a modular compiler for a subset of a C-like language, which addresses the challenges in constructing a compiler for high-level languages. This modular approach will allow developers to modify a language by adding or removing subsets as required, resulting in a minimal and memory-efficient compiler. The development process is divided into small, incremental steps, where each step yields a fully functioning compiler for an expanding subset of the language. The paper outlines the iterative developmental phase of the compiler, emphasizing progressive enhancements in capabilities and functionality. Adherence to industry best practices of modular design, code reusability, and documentation has enabled the resulting compiler's functional efficiency, maintainability, and extensibility. The compiler proved to be effective not only in managing the language structure but also in developing optimized code, which demonstrates its practical usability. This was also further assessed using the compiler on a tiny memory-deficient single-board computer, again showing the compiler's efficiency and suitability for resource-constrained devices. 

**Abstract (ZH)**: 本文介绍了一种针对某一C语言子集的模块化编译器的开发，旨在应对构建高级语言编译器所面临的挑战。这种模块化方法允许开发人员根据需要添加或删除子集，从而实现一个简洁且内存高效的编译器。开发过程被细分为多个小的增量步骤，每个步骤都会产出适用于语言扩展子集的完整功能编译器。本文详细描述了编译器的迭代开发阶段，强调了逐步增强功能和功能。遵循模块化设计、代码重用和详尽文档编制的最佳实践，使得最终编译器在功能效率、可维护性和可扩展性方面表现出色。编译器不仅在管理和处理语言结构方面表现出有效性，还在生成优化代码方面也显示出其实用性。该编译器还在一个小内存单板计算机上进行了进一步评估，再次证明了其在资源受限设备上的高效性和适用性。 

---
# NSA: Neuro-symbolic ARC Challenge 

**Title (ZH)**: NSA: 神经符号ARC挑战任务 

**Authors**: Paweł Batorski, Jannik Brinkmann, Paul Swoboda  

**Link**: [PDF](https://arxiv.org/pdf/2501.04424)  

**Abstract**: The Abstraction and Reasoning Corpus (ARC) evaluates general reasoning capabilities that are difficult for both machine learning models and combinatorial search methods. We propose a neuro-symbolic approach that combines a transformer for proposal generation with combinatorial search using a domain-specific language. The transformer narrows the search space by proposing promising search directions, which allows the combinatorial search to find the actual solution in short time. We pre-train the trainsformer with synthetically generated data. During test-time we generate additional task-specific training tasks and fine-tune our model. Our results surpass comparable state of the art on the ARC evaluation set by 27% and compare favourably on the ARC train set. We make our code and dataset publicly available at this https URL. 

**Abstract (ZH)**: 抽象与推理语料库（ARC）评估了一种既难以用机器学习模型又难以用组合搜索方法处理的一般推理能力。我们提出了一种神经符号方法，该方法结合了变压器进行提议生成和使用领域特定语言进行组合搜索。变压器通过提出有希望的搜索方向来缩减搜索空间，从而使组合搜索能够在短时间内找到实际解决方案。我们使用合成生成的数据对变压器进行预训练。在测试阶段，我们生成额外的任务特定训练任务并对模型进行微调。我们的结果在ARC评估集上的表现超过了可比的最先进的方法27%，并在ARC训练集上表现良好。我们已将我们的代码和数据集开源，可访问此[链接]。 

---
# Decoding EEG Speech Perception with Transformers and VAE-based Data Augmentation 

**Title (ZH)**: 使用变压器和基于VAE的数据增强解码脑电（EEG）语音感知 

**Authors**: Terrance Yu-Hao Chen, Yulin Chen, Pontus Soederhaell, Sadrishya Agrawal, Kateryna Shapovalenko  

**Link**: [PDF](https://arxiv.org/pdf/2501.04359)  

**Abstract**: Decoding speech from non-invasive brain signals, such as electroencephalography (EEG), has the potential to advance brain-computer interfaces (BCIs), with applications in silent communication and assistive technologies for individuals with speech impairments. However, EEG-based speech decoding faces major challenges, such as noisy data, limited datasets, and poor performance on complex tasks like speech perception. This study attempts to address these challenges by employing variational autoencoders (VAEs) for EEG data augmentation to improve data quality and applying a state-of-the-art (SOTA) sequence-to-sequence deep learning architecture, originally successful in electromyography (EMG) tasks, to EEG-based speech decoding. Additionally, we adapt this architecture for word classification tasks. Using the Brennan dataset, which contains EEG recordings of subjects listening to narrated speech, we preprocess the data and evaluate both classification and sequence-to-sequence models for EEG-to-words/sentences tasks. Our experiments show that VAEs have the potential to reconstruct artificial EEG data for augmentation. Meanwhile, our sequence-to-sequence model achieves more promising performance in generating sentences compared to our classification model, though both remain challenging tasks. These findings lay the groundwork for future research on EEG speech perception decoding, with possible extensions to speech production tasks such as silent or imagined speech. 

**Abstract (ZH)**: 从无创脑信号（如脑电图（EEG））解码语音具有潜力促进脑机接口（BCIs）的发展，特别是在无声交流和言语障碍个体的辅助技术方面。然而，基于EEG的语音解码面临诸多挑战，包括数据噪声大、数据集有限以及在复杂任务如语音感知方面表现不佳。本研究旨在通过使用变分自编码器（VAEs）对EEG数据进行扩充以提高数据质量，并采用一种在肌电图（EMG）任务中取得成功的最先进的序列到序列（SOTA）深度学习架构，应用于EEG基的语音解码。此外，我们将该架构调整以适应单词分类任务。使用包含受试者听叙述性言语的EEG记录的Brennan数据集，我们预处理这些数据，并评估分类模型和序列到序列模型在EEG到单词/句子任务中的表现。实验结果表明，VAEs有可能重建用于扩充的伪EEG数据。同时，我们的序列到序列模型在生成句子方面表现出更优越的性能，尽管两者都仍然是具有挑战性的任务。这些发现为进一步研究EEG语音感知解码奠定了基础，未来可能扩展到无声或想象的speech生产任务。 

---
# TimelineKGQA: A Comprehensive Question-Answer Pair Generator for Temporal Knowledge Graphs 

**Title (ZH)**: 时间线KGQA：时空知识图谱的综合问答对生成器 

**Authors**: Qiang Sun, Sirui Li, Du Huynh, Mark Reynolds, Wei Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04343)  

**Abstract**: Question answering over temporal knowledge graphs (TKGs) is crucial for understanding evolving facts and relationships, yet its development is hindered by limited datasets and difficulties in generating custom QA pairs. We propose a novel categorization framework based on timeline-context relationships, along with \textbf{TimelineKGQA}, a universal temporal QA generator applicable to any TKGs. The code is available at: \url{this https URL} as an open source Python package. 

**Abstract (ZH)**: 时间知识图谱（TKGs）上的问答对于理解演变的事实和关系至关重要，但其发展受限于可用数据集有限以及生成自定义QA对的困难。我们提出了一种基于时间轴-上下文关系的新分类框架，并开发了适用于任何TKGs的通用时间问答生成器\textbf{TimelineKGQA}。此代码库可在以下链接处获取：\url{此网址链接}，并以开源Python包的形式提供。 

---
# Circuit Complexity Bounds for Visual Autoregressive Model 

**Title (ZH)**: 视觉自回归模型的电路复杂性界 

**Authors**: Yekun Ke, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.04299)  

**Abstract**: Understanding the expressive ability of a specific model is essential for grasping its capacity limitations. Recently, several studies have established circuit complexity bounds for Transformer architecture. Besides, the Visual AutoRegressive (VAR) model has risen to be a prominent method in the field of image generation, outperforming previous techniques, such as Diffusion Transformers, in generating high-quality images. We investigate the circuit complexity of the VAR model and establish a bound in this study. Our primary result demonstrates that the VAR model is equivalent to a simulation by a uniform $\mathsf{TC}^0$ threshold circuit with hidden dimension $d \leq O(n)$ and $\mathrm{poly}(n)$ precision. This is the first study to rigorously highlight the limitations in the expressive power of VAR models despite their impressive performance. We believe our findings will offer valuable insights into the inherent constraints of these models and guide the development of more efficient and expressive architectures in the future. 

**Abstract (ZH)**: 理解特定模型的表达能力对于掌握其能力限制至关重要。近期，有数项研究为Transformer架构设定了电路复杂性界限。此外，Visual AutoRegressive（VAR）模型已成为图像生成领域的突出方法，其生成高质量图像的能力优于先前的技术，如Diffusion Transformers。在本研究中，我们探讨了VAR模型的电路复杂性并建立了相应的界限。我们的主要结果表明，VAR模型等价于一个隐藏维度 $d \leq O(n)$ 且精度为 $\mathrm{poly}(n)$ 的均匀 $\mathsf{TC}^0$ 门限电路的模拟。这是首个严格揭示尽管VAR模型表现出色但仍存在表达能力限制的研究。我们相信，我们的发现将为这些模型固有的约束提供有价值的见解，并指导未来更高效和更具表达能力架构的发展。 

---
# Agent Laboratory: Using LLM Agents as Research Assistants 

**Title (ZH)**: 智能体实验室：将大语言模型智能体作为研究助手 

**Authors**: Samuel Schmidgall, Yusheng Su, Ze Wang, Ximeng Sun, Jialian Wu, Xiaodong Yu, Jiang Liu, Zicheng Liu, Emad Barsoum  

**Link**: [PDF](https://arxiv.org/pdf/2501.04227)  

**Abstract**: Historically, scientific discovery has been a lengthy and costly process, demanding substantial time and resources from initial conception to final results. To accelerate scientific discovery, reduce research costs, and improve research quality, we introduce Agent Laboratory, an autonomous LLM-based framework capable of completing the entire research process. This framework accepts a human-provided research idea and progresses through three stages--literature review, experimentation, and report writing to produce comprehensive research outputs, including a code repository and a research report, while enabling users to provide feedback and guidance at each stage. We deploy Agent Laboratory with various state-of-the-art LLMs and invite multiple researchers to assess its quality by participating in a survey, providing human feedback to guide the research process, and then evaluate the final paper. We found that: (1) Agent Laboratory driven by o1-preview generates the best research outcomes; (2) The generated machine learning code is able to achieve state-of-the-art performance compared to existing methods; (3) Human involvement, providing feedback at each stage, significantly improves the overall quality of research; (4) Agent Laboratory significantly reduces research expenses, achieving an 84% decrease compared to previous autonomous research methods. We hope Agent Laboratory enables researchers to allocate more effort toward creative ideation rather than low-level coding and writing, ultimately accelerating scientific discovery. 

**Abstract (ZH)**: 历史上，科学研究是一个漫长且昂贵的过程，从最初的构想到最终结果，都需要大量的时间和资源。为了加快科学研究进程、降低研究成本并提高研究质量，我们介绍了一种自主的基于大语言模型（LLM）的框架——Agent Laboratory，该框架能够完成整个研究过程。该框架接受人类提供的研究构想，并通过三个阶段——文献综述、实验和报告撰写，产生全面的研究输出，包括代码仓库和研究报告，同时允许用户在每个阶段提供反馈和指导。我们采用各种最先进的LLM部署Agent Laboratory，并邀请多名研究人员参与质量评估，通过提供人力反馈来指导研究过程，然后对最终论文进行评估。我们发现：（1）由o1-preview驱动的Agent Laboratory产生最优的研究成果；（2）生成的机器学习代码在性能上达到了现有方法的先进水平；（3）人类参与，在每个阶段提供反馈，显著提高了研究的整体质量；（4）Agent Laboratory显著降低了研究费用，相对于以前的自主研究方法，成本减少了84%。我们希望Agent Laboratory能够使研究人员更多地投入到富有创造力的构想中，而非低级别的编码和写作，从而最终加快科学研究的进程。 

---
# MM-GEN: Enhancing Task Performance Through Targeted Multimodal Data Curation 

**Title (ZH)**: MM-GEN：通过目标导向的多模态数据整理增强任务性能 

**Authors**: Siddharth Joshi, Besmira Nushi, Vidhisha Balachandran, Varun Chandrasekaran, Vibhav Vineet, Neel Joshi, Baharan Mirzasoleiman  

**Link**: [PDF](https://arxiv.org/pdf/2501.04155)  

**Abstract**: Vision-language models (VLMs) are highly effective but often underperform on specialized tasks; for example, Llava-1.5 struggles with chart and diagram understanding due to scarce task-specific training data. Existing training data, sourced from general-purpose datasets, fails to capture the nuanced details needed for these tasks. We introduce MM-Gen, a scalable method that generates task-specific, high-quality synthetic text for candidate images by leveraging stronger models. MM-Gen employs a three-stage targeted process: partitioning data into subgroups, generating targeted text based on task descriptions, and filtering out redundant and outlier data. Fine-tuning VLMs with data generated by MM-Gen leads to significant performance gains, including 29% on spatial reasoning and 15% on diagram understanding for Llava-1.5 (7B). Compared to human-curated caption data, MM-Gen achieves up to 1.6x better improvements for the original models, proving its effectiveness in enhancing task-specific VLM performance and bridging the gap between general-purpose datasets and specialized requirements. Code available at this https URL. 

**Abstract (ZH)**: 视觉-语言模型（VLMs）高度有效，但在特定任务上往往表现不佳；例如，Llava-1.5 在图表和图理解方面表现不佳，这主要是因为缺乏特定任务的训练数据。现有的训练数据来源于通用数据集，无法捕捉到完成这些任务所需的细微差别。我们提出了MM-Gen，这是一种可扩展的方法，通过利用更强的模型生成任务特定的高质量合成文本，用于候选图像。MM-Gen采用三层目标导向的过程：将数据划分为子组、根据任务描述生成目标文本，并过滤冗余和异常数据。使用MM-Gen生成的数据微调VLMs可以显著提高性能，包括Llava-1.5（7B）在空间推理方面的29%提升和图理解方面的15%提升。与人工标注的标题数据相比，MM-Gen能够将原始模型的性能提高多达1.6倍，证明了其在提升特定任务的VLM性能方面的作用，并弥补了通用数据集与特定需求之间的差距。代码详见此链接：https://your-code-link-here.com 

---
# More is not always better? Enhancing Many-Shot In-Context Learning with Differentiated and Reweighting Objectives 

**Title (ZH)**: 更多未必更好？差异化和加权目标增强多样本反例学习效果研究 

**Authors**: Xiaoqing Zhang, Ang Lv, Yuhan Liu, Flood Sung, Wei Liu, Shuo Shang, Xiuying Chen, Rui Yan  

**Link**: [PDF](https://arxiv.org/pdf/2501.04070)  

**Abstract**: Large language models (LLMs) excel at few-shot in-context learning (ICL) without requiring parameter updates. However, as the number of ICL demonstrations increases from a few to many, performance tends to plateau and eventually decline. We identify two primary causes for this trend: the suboptimal negative log-likelihood (NLL) optimization objective and the incremental data noise. To address these issues, we introduce DR-ICL, a novel optimization method that enhances model performance through Differentiated Learning and advantage-based Reweighting objectives. Globally, DR-ICL utilizes differentiated learning to optimize the NLL objective, ensuring that many-shot performance surpasses zero-shot levels. Locally, it dynamically adjusts the weighting of many-shot demonstrations by leveraging cumulative advantages inspired by reinforcement learning, thereby improving generalization. This approach allows the model to handle varying numbers of shots effectively, mitigating the impact of noisy data. Recognizing the lack of multi-task datasets with diverse many-shot distributions, we develop the Many-Shot ICL Benchmark (MICLB)-a large-scale benchmark covering shot numbers from 1 to 350 within sequences of up to 8,000 tokens-for fine-tuning purposes. MICLB facilitates the evaluation of many-shot ICL strategies across seven prominent NLP tasks and 50 distinct datasets. Experimental results demonstrate that LLMs enhanced with DR-ICL achieve significant improvements in many-shot setups across various tasks, including both in-domain and out-of-domain scenarios. We release the code and benchmark dataset hoping to facilitate further research in many-shot ICL. 

**Abstract (ZH)**: 大型语言模型（LLMs）在少量示例下/background知识学习（ICL）中表现出色，无需更新参数。然而，随着ICL示例数量从少量增加到许多，性能往往会达到稳定状态并最终下降。我们确定了这种趋势的两个主要原因：次优的负对数似然（NLL）优化目标以及逐步增加的数据噪声。为了解决这些问题，我们引入了DR-ICL（区分学习和优势加权重定义），这是一种新颖的优化方法，能够通过区分学习和优势加权的目标增强模型性能。全球而言，DR-ICL 通过区分学习优化 NLL 目标，确保多示例的表现超过零示例水平。局部而言，它通过借鉴强化学习中的累积优势动态调整多示例示例的权重，从而提高泛化能力。这种方法使模型能够有效应对不同的示例数量，减轻噪声数据的影响。考虑到缺乏包含多种多示例分布的多任务数据集，我们开发了多示例ICL基准（MICLB），这是一个大规模的基准，涵盖了序列内至多8000个标记中从1到350的不同多示例数量，用于微调目的。MICLB 使得能够在七个主要自然语言处理（NLP）任务和50个不同数据集上评估多示例ICL策略。实验结果表明，使用DR-ICL增强的LLMs在各种任务中，在多示例设置中取得了显著改进，包括领域内和领域外场景。我们发布了代码和基准数据集，希望促进多示例ICL领域的进一步研究。 

---
# The Power of Negative Zero: Datatype Customization for Quantized Large Language Models 

**Title (ZH)**: 负零的力量：量化大型语言模型的数据类型自定义 

**Authors**: Yuzong Chen, Xilai Dai, Chi-chih Chang, Yash Akhauri, Mohamed S. Abdelfattah  

**Link**: [PDF](https://arxiv.org/pdf/2501.04052)  

**Abstract**: Large language models (LLMs) have demonstrated remarkable performance across various machine learning tasks, quickly becoming one of the most prevalent AI workloads. Yet the substantial memory requirement of LLMs significantly hinders their deployment for end users. Post-training quantization (PTQ) serves as one of the most hardware-efficient methods to mitigate the memory and computational demands of LLMs. Although the traditional integer (INT) datatype has received widespread adoption in PTQ methods, floating-point (FP) quantization has emerged as a viable alternative thanks to its effectiveness in fitting LLM numerical distributions. However, the FP datatype in sign-magnitude binary representation contains both positive and negative zero, which constrains its representation capability, particularly under low precision (3 and 4 bits). In this paper, we extend the basic FP datatype to perform Redundant Zero Remapping (RaZeR), which remaps the negative zero FP encoding to a set of pre-defined special values to maximally utilize FP quantization encodings and to better fit LLM numerical distributions. Through careful selection of special values, RaZeR outperforms conventional asymmetric INT quantization while achieving high computational efficiency. We demonstrate that RaZeR can be seamlessly integrated with quantization algorithms for both weights and KV-cache, including advanced methods with clipping and transformations, and consistently achieve better model accuracy. Additionally, we implement a fast GEMV kernel with fused dequantization that efficiently converts the 4-bit RaZeR value to FP16 through novel bit-level manipulation. On modern GPUs, our evaluation shows that RaZeR improves the GEMV speed by up to 7.56$\times$ compared to the FP16 implementation, while achieving up to 2.72$\times$ speedup in the LLM decoding throughput. 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种机器学习任务中表现出色，迅速成为最普遍的AI工作负载之一。然而，LLMs显著的内存需求极大地阻碍了它们在终端用户的部署。后训练量化（PTQ）作为减轻LLMs的内存和计算需求的最高效硬件方法之一而受到重视。虽然传统的整数（INT）数据类型在PTQ方法中已经得到了广泛应用，但凭借在适应LLMs数值分布方面的能力，浮点（FP）量化也逐渐成为一种可行的选择。然而，表示为符号幅度二进制表示的FP数据类型包含正零和负零，这限制了其表示能力，尤其是在低精度（3和4位）情况下。在本文中，我们扩展了基本的FP数据类型，提出了冗余零重构（RaZeR）方法，该方法将负零FP编码重新映射到预定义的特殊值集合上，以最大化利用FP量化编码，并更好地适应LLMs的数值分布。通过仔细选择特殊值，RaZeR在计算效率高时优于传统的非对称INT量化。我们证明了RaZeR可以无缝嵌入到权重和KV缓存的量化算法中，包括带有剪枝和变换的高级方法，且能够实现更好的模型精度。此外，我们实现了快速的GEMV内核，并结合混合去量化操作，高效地将4位RaZeR值转换为FP16，通过新颖的位级操作完成这一过程。在现代GPU上，我们的评估结果表明，与FP16实现相比，RaZeR可以将GEMV速度提高至多7.56倍，同时在LLM解码吞吐量上实现最高至2.72倍的加速。 

---