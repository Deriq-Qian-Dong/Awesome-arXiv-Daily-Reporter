# Metadata Conditioning Accelerates Language Model Pre-training 

**Title (ZH)**: 元数据条件化加速语言模型的预训练 

**Authors**: Tianyu Gao, Alexander Wettig, Luxi He, Yihe Dong, Sadhika Malladi, Danqi Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01956)  

**Abstract**: The vast diversity of styles, domains, and quality levels present in language model pre-training corpora is essential in developing general model capabilities, but efficiently learning and deploying the correct behaviors exemplified in each of these heterogeneous data sources is challenging. To address this, we propose a new method, termed Metadata Conditioning then Cooldown (MeCo), to incorporate additional learning cues during pre-training. MeCo first provides metadata (e.g., URLs like this http URL) alongside the text during training and later uses a cooldown phase with only the standard text, thereby enabling the model to function normally even without metadata. MeCo significantly accelerates pre-training across different model scales (600M to 8B parameters) and training sources (C4, RefinedWeb, and DCLM). For instance, a 1.6B language model trained with MeCo matches the downstream task performance of standard pre-training while using 33% less data. Additionally, MeCo enables us to steer language models by conditioning the inference prompt on either real or fabricated metadata that encodes the desired properties of the output: for example, prepending this http URL to reduce harmful generations or this http URL (fabricated) to improve common knowledge task performance. We also demonstrate that MeCo is compatible with different types of metadata, such as model-generated topics. MeCo is remarkably simple, adds no computational overhead, and demonstrates promise in producing more capable and steerable language models. 

**Abstract (ZH)**: 语言模型预训练语料库中存在的广泛风格、领域和质量水平的多样性对于开发通用模型能力至关重要，但在高效学习和部署每种异构数据源中的正确行为方面具有挑战性。为了解决这一问题，我们提出了一种新的方法，称为元数据条件处理然后冷却（MeCo），在预训练过程中引入额外的学习线索。MeCo 首先在训练过程中提供元数据（例如，如“http://”这样的URL），然后在冷却期使用标准文本，从而使模型在没有元数据的情况下也能正常工作。MeCo 在不同模型规模（6亿到80亿参数）以及不同训练来源（C4、RefinedWeb 和 DCLM）下的预训练过程中显著加速。例如，使用 MeCo 训练的16亿参数语言模型在使用33%较少数据的情况下，其下游任务性能可以与标准预训练相当。此外，MeCo 还使我们能够通过将推理提示条件化于真实的或虚构的元数据上来引导语言模型，这些元数据编码了所需输出的属性：例如，预置“http://”可以减少有害生成，或预置“http://”（虚构的）以提高常识任务性能。我们还展示了 MeCo 可以兼容不同类型元数据，例如模型生成的主题。MeCo 极其简单，不会增加计算开销，并且具有生产更强大和可控制的语言模型的潜力。 

---
# Abstractive Text Summarization for Contemporary Sanskrit Prose: Issues and Challenges 

**Title (ZH)**: 当代梵文散文的摘要性文本总结：问题与挑战 

**Authors**: Shagun Sinha  

**Link**: [PDF](https://arxiv.org/pdf/2501.01933)  

**Abstract**: This thesis presents Abstractive Text Summarization models for contemporary Sanskrit prose. The first chapter, titled Introduction, presents the motivation behind this work, the research questions, and the conceptual framework. Sanskrit is a low-resource inflectional language. The key research question that this thesis investigates is what the challenges in developing an abstractive TS for Sanskrit. To answer the key research questions, sub-questions based on four different themes have been posed in this work. The second chapter, Literature Review, surveys the previous works done. The third chapter, data preparation, answers the remaining three questions from the third theme. It reports the data collection and preprocessing challenges for both language model and summarization model trainings. The fourth chapter reports the training and inference of models and the results obtained therein. This research has initiated a pipeline for Sanskrit abstractive text summarization and has reported the challenges faced at every stage of the development. The research questions based on every theme have been answered to answer the key research question. 

**Abstract (ZH)**: 本论文提出了用于现代表形式梵文的extractive文本摘要模型。第一章，即引言部分，阐述了本工作的动机、研究问题和概念框架。梵文是一种低资源屈折语言。本论文的研究主要集中在开发现代表形式梵文的抽 sourced摘要模型所面临的挑战。为了回答核心研究问题，本研究提出了基于四个不同主题的子问题。第二章，文献综述部分，回顾了相关的工作。第三章，数据准备部分，回答了第三主题中的其余三个问题，报告了语言模型和摘要模型训练过程中数据收集和预处理的挑战。第四章报告了模型的训练与推理过程及所得结果。本研究启动了一条针对梵文的extractive文本摘要处理管线，并在每个开发阶段报告了面临的挑战。基于每个主题的研究问题都被回答，用以回答核心研究问题。 

---
# Long Context vs. RAG for LLMs: An Evaluation and Revisits 

**Title (ZH)**: 长上下文对比基于检索的生成：对大语言模型的评估与回顾 

**Authors**: Xinze Li, Yixin Cao, Yubo Ma, Aixin Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.01880)  

**Abstract**: Extending context windows (i.e., Long Context, LC) and using retrievers to selectively access relevant information (i.e., Retrieval-Augmented Generation, RAG) are the two main strategies to enable LLMs to incorporate extremely long external contexts. This paper revisits recent studies on this topic, highlighting their key insights and discrepancies. We then provide a more comprehensive evaluation by filtering out questions answerable without external context, identifying the most effective retrieval methods, and expanding the datasets. We show that LC generally outperforms RAG in question-answering benchmarks, especially for Wikipedia-based questions. Summarization-based retrieval performs comparably to LC, while chunk-based retrieval lags behind. However, RAG has advantages in dialogue-based and general question queries. These insights underscore the trade-offs between RAG and LC strategies, offering guidance for future optimization of LLMs with external knowledge sources. We also provide an in-depth discussion on this topic, highlighting the overlooked importance of context relevance in existing studies. 

**Abstract (ZH)**: 扩展上下文窗口（即Long Context，LC）和利用检索器选择性地访问相关信息（即检索增强生成，RAG）是使大语言模型（LLM）能够纳入极其长的外部上下文的两种主要策略。本论文重新审视了这一领域近期的研究，强调了它们的关键见解和差异。我们通过筛选出不需要外部上下文即可回答的问题，识别出最有效的检索方法，并扩展数据集，提供了一种更为全面的评估。结果显示，LC在问题回答基准测试中通常优于RAG，特别是在基于Wikipedia的问题上。基于摘要的检索方法与LC表现相当，而基于片段的检索方法则落后于后者。然而，RAG在基于对话的问题查询和一般的查询中具有优势。这些见解突显了RAG和LC策略之间的权衡，为未来利用外部知识源优化LLM提供了指导。我们还对这一主题进行了深入讨论，强调了现有研究中被忽视的上下文相关性的重要性。 

---
# Turning Logic Against Itself : Probing Model Defenses Through Contrastive Questions 

**Title (ZH)**: 反其道而行之：通过对比性问题探究模型防护策略 

**Authors**: Rachneet Sachdeva, Rima Hazra, Iryna Gurevych  

**Link**: [PDF](https://arxiv.org/pdf/2501.01872)  

**Abstract**: Despite significant efforts to align large language models with human values and ethical guidelines, these models remain susceptible to sophisticated jailbreak attacks that exploit their reasoning capabilities. Traditional safety mechanisms often focus on detecting explicit malicious intent, leaving deeper vulnerabilities unaddressed. In this work, we introduce a jailbreak technique, POATE (Polar Opposite query generation, Adversarial Template construction, and Elaboration), which leverages contrastive reasoning to elicit unethical responses. POATE generates prompts with semantically opposite intents and combines them with adversarial templates to subtly direct models toward producing harmful responses. We conduct extensive evaluations across six diverse language model families of varying parameter sizes, including LLaMA3, Gemma2, Phi3, and GPT-4, to demonstrate the robustness of the attack, achieving significantly higher attack success rates (~44%) compared to existing methods. We evaluate our proposed attack against seven safety defenses, revealing their limitations in addressing reasoning-based vulnerabilities. To counteract this, we propose a defense strategy that improves reasoning robustness through chain-of-thought prompting and reverse thinking, mitigating reasoning-driven adversarial exploits. 

**Abstract (ZH)**: 尽管在使大型语言模型与人类价值观和伦理规范保持一致方面付出了大量努力，这些模型仍然容易受到利用其推理能力的复杂“逃逸攻击”的影响。传统的安全机制往往侧重于检测明确的恶意意图，从而忽略了更深层次的脆弱性。在本研究中，我们引入了一种名为POATE（对比推理生成极性相反的提示、对抗性模板构建和详细解释）的逃逸攻击技术，利用对比推理引出不道德的回应。POATE生成具有语义上相反意图的提示，并结合对抗性模板，微妙地引导模型产生有害的回应。我们对六个不同参数规模的多种语言模型家族进行了广泛评估，包括LLaMA3、Gemma2、Phi3和GPT-4，以证明该攻击的鲁棒性，并取得了显著更高的攻击成功率（约44%），相比现有方法。我们对七种安全防护措施进行了评估，揭示了它们在应对基于推理的脆弱性方面的局限性。为了应对这一挑战，我们提出了一种防御策略，通过链式思考提示和逆向思考来提高推理的鲁棒性，从而减轻基于推理的对抗性攻击。 

---
# Time Series Language Model for Descriptive Caption Generation 

**Title (ZH)**: 时间序列语言模型在描述性图 caption 生成中的应用 

**Authors**: Mohamed Trabelsi, Aidan Boyd, Jin Cao, Huseyin Uzunalioglu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01832)  

**Abstract**: The automatic generation of representative natural language descriptions for observable patterns in time series data enhances interpretability, simplifies analysis and increases cross-domain utility of temporal data. While pre-trained foundation models have made considerable progress in natural language processing (NLP) and computer vision (CV), their application to time series analysis has been hindered by data scarcity. Although several large language model (LLM)-based methods have been proposed for time series forecasting, time series captioning is under-explored in the context of LLMs. In this paper, we introduce TSLM, a novel time series language model designed specifically for time series captioning. TSLM operates as an encoder-decoder model, leveraging both text prompts and time series data representations to capture subtle temporal patterns across multiple phases and generate precise textual descriptions of time series inputs. TSLM addresses the data scarcity problem in time series captioning by first leveraging an in-context prompting synthetic data generation, and second denoising the generated data via a novel cross-modal dense retrieval scoring applied to time series-caption pairs. Experimental findings on various time series captioning datasets demonstrate that TSLM outperforms existing state-of-the-art approaches from multiple data modalities by a significant margin. 

**Abstract (ZH)**: 时间序列数据中可观察模式的自动自然语言描述生成可以增强解释性、简化分析，并提高时间数据在不同领域的实用性。尽管预训练的基础模型在自然语言处理（NLP）和计算机视觉（CV）上取得了显著进展，但它们在时间序列分析中的应用受到了数据稀缺性的影响。虽然已经提出了几种基于大型语言模型（LLM）的时间序列预测方法，但时间序列图注在LLM的上下文中仍然未被充分探索。在本文中，我们引入了TSLM，这是一种专门设计用于时间序列图注的新型时间序列语言模型。TSLM 作为一种编码器-解码器模型，利用文本提示和时间序列数据表示来捕捉多个阶段中的细腻时间模式，并生成时间序列输入的精确文本描述。TSLM 通过首先利用上下文提示下的合成数据生成，以及其次通过应用于时间序列-图注对的新颖跨模态稠密检索评分进行去噪，解决了时间序列图注中的数据稀缺性问题。在多种时间序列图注数据集上的实验结果表明，TSLM 在多种数据模态下显著超越了现有的最先进的方法。 

---
# The Proof is in the Almond Cookies 

**Title (ZH)**: 实验结果尽在其中（以杏仁饼干为例） 

**Authors**: Remi van Trijp, Katrien Beuls, Paul Van Eecke  

**Link**: [PDF](https://arxiv.org/pdf/2501.01827)  

**Abstract**: This paper presents a case study on how to process cooking recipes (and more generally, how-to instructions) in a way that makes it possible for a robot or artificial cooking assistant to support human chefs in the kitchen. Such AI assistants would be of great benefit to society, as they can help to sustain the autonomy of aging adults or people with a physical impairment, or they may reduce the stress in a professional kitchen. We propose a novel approach to computational recipe understanding that mimics the human sense-making process, which is narrative-based. Using an English recipe for almond crescent cookies as illustration, we show how recipes can be modelled as rich narrative structures by integrating various knowledge sources such as language processing, ontologies, and mental simulation. We show how such narrative structures can be used for (a) dealing with the challenges of recipe language, such as zero anaphora, (b) optimizing a robot's planning process, (c) measuring how well an AI system understands its current tasks, and (d) allowing recipe annotations to become language-independent. 

**Abstract (ZH)**: 本文介绍了一种案例研究，探讨了如何处理烹饪食谱（更广泛地说，是如何做的指令），以使机器人或人工智能烹饪助手能够辅助厨房中的人类厨师。这样的AI助手对社会有很大的益处，因为它们可以帮助维持老年人或有身体障碍的人的自主性，或者可能减轻专业厨房中的工作压力。我们提出了一种新的计算食谱理解方法，该方法模拟了人类的意义建构过程，这是一种基于叙述的方法。以一种英语食谱——杏仁半月酥为例，展示了如何通过整合语言处理、本体和心理模拟等多种知识源来构建丰富的叙述结构来表示食谱。我们展示了这些叙述结构如何用于（a）应对食谱语言的挑战，如零代词现象，（b）优化机器人计划过程，（c）衡量AI系统对其当前任务的理解程度，以及（d）使食谱注释变得与语言无关。 

---
# End-to-End Long Document Summarization using Gradient Caching 

**Title (ZH)**: 使用梯度缓存的端到端长文档摘要生成 

**Authors**: Rohit Saxena, Hao Tang, Frank Keller  

**Link**: [PDF](https://arxiv.org/pdf/2501.01805)  

**Abstract**: Training transformer-based encoder-decoder models for long document summarization poses a significant challenge due to the quadratic memory consumption during training. Several approaches have been proposed to extend the input length at test time, but training with these approaches is still difficult, requiring truncation of input documents and causing a mismatch between training and test conditions. In this work, we propose CachED (Gradient $\textbf{Cach}$ing for $\textbf{E}$ncoder-$\textbf{D}$ecoder models), an approach that enables end-to-end training of existing transformer-based encoder-decoder models, using the entire document without truncation. Specifically, we apply non-overlapping sliding windows to input documents, followed by fusion in decoder. During backpropagation, the gradients are cached at the decoder and are passed through the encoder in chunks by re-computing the hidden vectors, similar to gradient checkpointing. In the experiments on long document summarization, we extend BART to CachED BART, processing more than 500K tokens during training and achieving superior performance without using any additional parameters. 

**Abstract (ZH)**: 基于Transformer的编码器-解码器模型在训练长文档摘要时会面临显著的挑战，主要原因是训练过程中内存消耗呈平方级增长。尽管已经提出了一些方法来在测试时扩展输入长度，但在这些方法下训练仍然困难，需要裁剪输入文档，从而导致训练和测试条件不匹配。在本工作中，我们提出了一种名为CachED（基于编码器-解码器模型的梯度缓存）的方法，该方法可以在不裁剪文档的情况下，端到端地训练现有的基于Transformer的编码器-解码器模型。具体而言，我们对输入文档应用非重叠滑动窗口，并在解码器中进行融合。在反向传播过程中，梯度在解码器中缓存，并通过重新计算隐藏向量分块通过编码器，类似于梯度检查点技术。在长文档摘要实验中，我们将BART扩展为CachED BART，在训练过程中处理超过50万个标记，且无需使用额外参数即可达到优越的性能。 

---
# Reading Between the Lines: A dataset and a study on why some texts are tougher than others 

**Title (ZH)**: 在字里行间探寻差异：一个文本难度差异的数据集及研究 

**Authors**: Nouran Khallaf, Carlo Eugeni, Serge Sharoff  

**Link**: [PDF](https://arxiv.org/pdf/2501.01796)  

**Abstract**: Our research aims at better understanding what makes a text difficult to read for specific audiences with intellectual disabilities, more specifically, people who have limitations in cognitive functioning, such as reading and understanding skills, an IQ below 70, and challenges in conceptual domains. We introduce a scheme for the annotation of difficulties which is based on empirical research in psychology as well as on research in translation studies. The paper describes the annotated dataset, primarily derived from the parallel texts (standard English and Easy to Read English translations) made available online. we fine-tuned four different pre-trained transformer models to perform the task of multiclass classification to predict the strategies required for simplification. We also investigate the possibility to interpret the decisions of this language model when it is aimed at predicting the difficulty of sentences. The resources are available from this https URL 

**Abstract (ZH)**: 我们的研究旨在更深入地理解哪些因素使得特定智障群体难以阅读文本，特别是那些存在认知功能障碍的人，如阅读和理解能力有限、智商低于70以及概念领域的挑战等。我们提出了一种基于心理学实证研究和翻译研究的研究方案，用于标注文本阅读难度。本文描述了标注数据集，主要来源于在线提供的平行文本（标准英语和易读英语的翻译）。我们对四种不同的预训练变换器模型进行了微调，使其能够执行多类分类任务，预测简化策略的需求。我们还探讨了当该语言模型旨在预测句子难度时，对其决策进行解释的可能性。相关资源可从以下链接获取：[请提供具体的URL链接] 

---
# Automating Legal Concept Interpretation with LLMs: Retrieval, Generation, and Evaluation 

**Title (ZH)**: 使用大语言模型自动化法律概念解释：检索、生成与评估 

**Authors**: Kangcheng Luo, Quzhe Huang, Cong Jiang, Yansong Feng  

**Link**: [PDF](https://arxiv.org/pdf/2501.01743)  

**Abstract**: Legal articles often include vague concepts to adapt to the ever-changing society. Providing detailed interpretations of these concepts is a critical task for legal practitioners, which requires meticulous and professional annotations by legal experts, admittedly time-consuming and expensive to collect at scale. In this paper, we introduce a novel retrieval-augmented generation framework, ATRI, for AuTomatically Retrieving relevant information from past judicial precedents and Interpreting vague legal concepts. We further propose a new benchmark, Legal Concept Entailment, to automate the evaluation of generated concept interpretations without expert involvement. Automatic evaluations indicate that our generated interpretations can effectively assist large language models (LLMs) in understanding vague legal concepts. Multi-faceted evaluations by legal experts indicate that the quality of our concept interpretations is comparable to those written by human experts. Our work has strong implications for leveraging LLMs to support legal practitioners in interpreting vague legal concepts and beyond. 

**Abstract (ZH)**: 法律文章常包含模糊概念以适应不断变化的社会环境。为这些概念提供详细的解释是一项关键任务，这要求法律专家进行细致且专业的注释，无疑是一个耗时且成本高昂的过程。本文介绍了一种新颖的检索增强生成框架ATRI（Automatically Retrieving and Interpreting Legal Concepts from Past Judicial Precedents），它可以从过往司法先例中自动检索相关信息并解释模糊的法律概念。我们还提出了一种新的基准任务——法律概念蕴含（Legal Concept Entailment），以实现生成的概念解释的自动化评估，无需法律专家的参与。自动评估结果表明，我们生成的概念解释能够有效地辅助大型语言模型（LLMs）理解模糊的法律概念。法律专家进行的多维度评估表明，我们的概念解释质量与人类专家撰写的解释相当。我们的工作对利用LLMs支持法律从业者解释模糊法律概念以及其他方面具有重要的启示意义。 

---
# The Essence of Contextual Understanding in Theory of Mind: A Study on Question Answering with Story Characters 

**Title (ZH)**: 注意力理解的本质在理论思维中的体现：基于故事情节中角色的问题回答研究 

**Authors**: Chulun Zhou, Qiujing Wang, Mo Yu, Xiaoqian Yue, Rui Lu, Jiangnan Li, Yifan Zhou, Shunchi Zhang, Jie Zhou, Wai Lam  

**Link**: [PDF](https://arxiv.org/pdf/2501.01705)  

**Abstract**: Theory-of-Mind (ToM) is a fundamental psychological capability that allows humans to understand and interpret the mental states of others. Humans infer others' thoughts by integrating causal cues and indirect clues from broad contextual information, often derived from past interactions. In other words, human ToM heavily relies on the understanding about the backgrounds and life stories of others. Unfortunately, this aspect is largely overlooked in existing benchmarks for evaluating machines' ToM capabilities, due to their usage of short narratives without global backgrounds. In this paper, we verify the importance of understanding long personal backgrounds in ToM and assess the performance of LLMs in such realistic evaluation scenarios. To achieve this, we introduce a novel benchmark, CharToM-QA, comprising 1,035 ToM questions based on characters from classic novels. Our human study reveals a significant disparity in performance: the same group of educated participants performs dramatically better when they have read the novels compared to when they have not. In parallel, our experiments on state-of-the-art LLMs, including the very recent o1 model, show that LLMs still perform notably worse than humans, despite that they have seen these stories during pre-training. This highlights the limitations of current LLMs in capturing the nuanced contextual information required for ToM reasoning. 

**Abstract (ZH)**: 理论共情（Theory-of-Mind, ToM）是人类的一种基本心理能力，使得人们能够理解并解释他人的心智状态。人类通过整合因果线索和广泛背景信息中的间接提示，推断他人的思想，这些信息通常来源于过去的互动经历。换句话说，人类的ToM高度依赖于对他人的背景和个人故事的理解。不幸的是，这种方面在现有评估机器ToM能力的基准中被严重忽视，因为这些基准使用的是缺乏全局背景的短篇叙述。在本文中，我们验证了理解长期个人背景在ToM中的重要性，并评估LLM在这种现实评估场景中的表现。为实现这一目标，我们引入了一个新的基准CharToM-QA，基于经典小说中的人物构建了1,035个ToM问题。我们的人类研究揭示了显著的性能差异：受过教育的参与者在阅读小说时的表现与未阅读时相比有显著的提升。同时，我们在最先进的LLM上进行的实验，包括最新的o1模型，表明尽管这些模型在预训练中见过这些故事，它们的表现仍然远不如人类。这突显了当前LLM在捕捉ToM推理所需的细微背景信息方面的局限性。 

---
# Adaptive Few-shot Prompting for Machine Translation with Pre-trained Language Models 

**Title (ZH)**: 基于预训练语言模型的自适应少样本提示方法在机器翻译中的应用 

**Authors**: Lei Tang, Jinghui Qin, Wenxuan Ye, Hao Tan, Zhijing Yang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01679)  

**Abstract**: Recently, Large language models (LLMs) with in-context learning have demonstrated remarkable potential in handling neural machine translation. However, existing evidence shows that LLMs are prompt-sensitive and it is sub-optimal to apply the fixed prompt to any input for downstream machine translation tasks. To address this issue, we propose an adaptive few-shot prompting (AFSP) framework to automatically select suitable translation demonstrations for various source input sentences to further elicit the translation capability of an LLM for better machine translation. First, we build a translation demonstration retrieval module based on LLM's embedding to retrieve top-k semantic-similar translation demonstrations from aligned parallel translation corpus. Rather than using other embedding models for semantic demonstration retrieval, we build a hybrid demonstration retrieval module based on the embedding layer of the deployed LLM to build better input representation for retrieving more semantic-related translation demonstrations. Then, to ensure better semantic consistency between source inputs and target outputs, we force the deployed LLM itself to generate multiple output candidates in the target language with the help of translation demonstrations and rerank these candidates. Besides, to better evaluate the effectiveness of our AFSP framework on the latest language and extend the research boundary of neural machine translation, we construct a high-quality diplomatic Chinese-English parallel dataset that consists of 5,528 parallel Chinese-English sentences. Finally, extensive experiments on the proposed diplomatic Chinese-English parallel dataset and the United Nations Parallel Corpus (Chinese-English part) show the effectiveness and superiority of our proposed AFSP. 

**Abstract (ZH)**: 近年来，具有上下文学习能力的大规模语言模型（LLMs）在神经机器翻译中展示了显著的潜力。然而，现有证据表明，LLMs 对提示（prompt）敏感，使用固定提示来处理下游机器翻译任务的输入并不可行。为解决这一问题，本文提出了一种自适应少量提示（AFSP）框架，该框架能够自动选择适合各种源输入句子的翻译示范，进一步激发LLM的翻译能力，以获得更好的机器翻译效果。首先，我们基于LLM的嵌入构建了一个翻译示范检索模块，从对齐的平行翻译语料库中检索最相关的top-k语义相似翻译示范。不同于使用其他嵌入模型进行语义示范检索，我们基于部署的LLM的嵌入层构建了一个混合示范检索模块，从而构建更好的输入表示，以便检索更多语义相关的翻译示范。其次，为了确保源输入与目标输出之间的更好语义一致性，我们借助翻译示范强制部署的LLM生成多个目标语言输出候选，并重新排序这些候选。此外，为了更好地评估我们提出的AFSP框架的有效性并扩展神经机器翻译的研究边界，我们构建了一个高质量的外交场合中英文平行语料库，其中包括5,528对中英文平行句子。最后，我们在提出的外交场合中英文平行语料库以及联合国平行语料库（中英文部分）上的广泛实验表明了我们提出AFSP框架的有效性和优越性。 

---
# CoT-based Synthesizer: Enhancing LLM Performance through Answer Synthesis 

**Title (ZH)**: 基于CoT的合成器：通过答案合成提升大语言模型性能 

**Authors**: Bohan Zhang, Xiaokang Zhang, Jing Zhang, Jifan Yu, Sijia Luo, Jie Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01668)  

**Abstract**: Current inference scaling methods, such as Self-consistency and Best-of-N, have proven effective in improving the accuracy of LLMs on complex reasoning tasks. However, these methods rely heavily on the quality of candidate responses and are unable to produce correct answers when all candidates are incorrect. In this paper, we propose a novel inference scaling strategy, CoT-based Synthesizer, which leverages CoT reasoning to synthesize superior answers by analyzing complementary information from multiple candidate responses, even when all candidate responses are flawed. To enable a lightweight and cost-effective implementation, we introduce an automated data generation pipeline that creates diverse training data. This allows smaller LLMs trained on this data to improve the inference accuracy of larger models, including API-based LLMs. Experimental results across four benchmark datasets with seven policy models demonstrate that our method significantly enhances performance, with gains of 11.8% for Llama3-8B and 10.3% for GPT-4o on the MATH dataset. The corresponding training data and code are publicly available on this https URL. 

**Abstract (ZH)**: 当前的推理扩展方法，如自我一致性（Self-consistency）和Best-of-N，已被证明能在复杂推理任务中提高大规模语言模型（LLM）的准确性。然而，这些方法高度依赖候选响应的质量，在所有候选响应都错误的情况下无法生成正确的答案。在本文中，我们提出了一种新的推理扩展策略——基于CoT的合成器（CoT-based Synthesizer），该策略利用CoT推理通过分析多个候选响应中的互补信息来综合出更优的答案，即使所有候选响应都是错误的。为了实现轻量级且成本效益高的实施，我们引入了一个自动数据生成管道，以生成多样化的训练数据。这使得在该数据上训练的小型LLM可以提升更大模型（包括基于API的LLM）的推理准确性。在四个基准数据集上进行的实验结果表明，我们的方法显著提高了性能，Llama3-8B在MATH数据集上的性能提高了11.8%，GPT-4o的性能提高了10.3%。相关训练数据和代码已在此网址公开：[提供网址]。 

---
# MIRAGE: Exploring How Large Language Models Perform in Complex Social Interactive Environments 

**Title (ZH)**: MIRAGE：探索大型语言模型在复杂社会互动环境中的表现 

**Authors**: Cai Yin, Gu Zhouhong, Du Zhaohan, Ye Zheyu, Cao Shaosheng, Xu Yiqian, Feng Hongwei, Chen Ping  

**Link**: [PDF](https://arxiv.org/pdf/2501.01652)  

**Abstract**: Large Language Models (LLMs) have shown remarkable capabilities in environmental perception, reasoning-based decision-making, and simulating complex human behaviors, particularly in interactive role-playing contexts. This paper introduces the Multiverse Interactive Role-play Ability General Evaluation (MIRAGE), a comprehensive framework designed to assess LLMs' proficiency in portraying advanced human behaviors through murder mystery games. MIRAGE features eight intricately crafted scripts encompassing diverse themes and styles, providing a rich simulation. To evaluate LLMs' performance, MIRAGE employs four distinct methods: the Trust Inclination Index (TII) to measure dynamics of trust and suspicion, the Clue Investigation Capability (CIC) to measure LLMs' capability of conducting information, the Interactivity Capability Index (ICI) to assess role-playing capabilities and the Script Compliance Index (SCI) to assess LLMs' capability of understanding and following instructions. Our experiments indicate that even popular models like GPT-4 face significant challenges in navigating the complexities presented by the MIRAGE. The datasets and simulation codes are available in \href{this https URL}{github}. 

**Abstract (ZH)**: 大型语言模型（LLMs）在环境感知、基于推理的决策制定以及模拟复杂的人类行为方面展示了显著的能力，尤其是在互动角色扮演的语境中。本文介绍了多维互动角色扮演能力通用评估框架（MIRAGE），这是一个全面的框架，旨在通过谋杀谜题游戏评估LLMs在呈现高级人类行为方面的 proficiency。

MIRAGE 包含八个精密编撰的脚本，涵盖不同的主题和风格，提供了丰富的模拟环境。为了评估LLMs的表现，MIRAGE 使用了四种不同的方法：信任倾向指数（TII）用于衡量信任和疑虑的动力学过程，线索调查能力（CIC）用于衡量LLMs的线索调查能力，互动能力指数（ICI）用于评估角色扮演能力，脚本遵从指数（SCI）用于评估LLMs理解并遵循指令的能力。我们的实验表明，即使是流行模型如GPT-4，在应对MIRAGE 提出的复杂性时也面临重大挑战。

实验数据和模拟代码可在 \href{https://github.com/...}{GitHub} 获取。 

---
# Multimodal Contrastive Representation Learning in Augmented Biomedical Knowledge Graphs 

**Title (ZH)**: augmented 生物医学知识图谱中的多模态对比表示学习 

**Authors**: Tien Dang, Viet Thanh Duy Nguyen, Minh Tuan Le, Truong-Son Hy  

**Link**: [PDF](https://arxiv.org/pdf/2501.01644)  

**Abstract**: Biomedical Knowledge Graphs (BKGs) integrate diverse datasets to elucidate complex relationships within the biomedical field. Effective link prediction on these graphs can uncover valuable connections, such as potential novel drug-disease relations. We introduce a novel multimodal approach that unifies embeddings from specialized Language Models (LMs) with Graph Contrastive Learning (GCL) to enhance intra-entity relationships while employing a Knowledge Graph Embedding (KGE) model to capture inter-entity relationships for effective link prediction. To address limitations in existing BKGs, we present PrimeKG++, an enriched knowledge graph incorporating multimodal data, including biological sequences and textual descriptions for each entity type. By combining semantic and relational information in a unified representation, our approach demonstrates strong generalizability, enabling accurate link predictions even for unseen nodes. Experimental results on PrimeKG++ and the DrugBank drug-target interaction dataset demonstrate the effectiveness and robustness of our method across diverse biomedical datasets. Our source code, pre-trained models, and data are publicly available at this https URL 

**Abstract (ZH)**: 生物医学知识图谱（BKGs）综合多种数据集，以阐明生物医学领域的复杂关系。在这类图上进行有效的链接预测可以揭示有价值的联系，例如潜在的新药物-疾病关系。我们提出了一个新型的多模态方法，该方法将专用语言模型（LMs）的嵌入与图对比学习（GCL）相结合，同时使用知识图嵌入（KGE）模型捕捉实体间的关系，以实现有效的链接预测。为了克服现有BKGs的局限性，我们提出了PrimeKG++，这是一种增强的知识图谱，包含了多模态数据，包括每个实体类型的生物序列和文本描述。通过在一个统一表示中结合语义和关系信息，我们的方法展示了强大的泛化能力，即使对于未见过的节点也能进行准确的链接预测。我们在PrimeKG++和DrugBank药物-靶标相互作用数据集上的实验结果表明，我们的方法在多种生物医学数据集上具有有效性与稳健性。我们的源代码、预训练模型和数据可在以下网址公开获取：this https URL 

---
# A non-ergodic framework for understanding emergent capabilities in Large Language Models 

**Title (ZH)**: 一个非遍历框架，用于理解大型语言模型中涌现能力的机制 

**Authors**: Javier Marin  

**Link**: [PDF](https://arxiv.org/pdf/2501.01638)  

**Abstract**: Large language models have emergent capabilities that come unexpectedly at scale, but we need a theoretical framework to explain why and how they emerge. We prove that language models are actually non-ergodic systems while providing a mathematical framework based on Stuart Kauffman's theory of the adjacent possible (TAP) to explain capability emergence. Our resource-constrained TAP equation demonstrates how architectural, training, and contextual constraints interact to shape model capabilities through phase transitions in semantic space. We prove through experiments with three different language models that capacities emerge through discrete transitions guided by constraint interactions and path-dependent exploration. This framework provides a theoretical basis for understanding emergence in language models and guides the development of architectures that can guide capability emergence. 

**Abstract (ZH)**: 大规模语言模型在一定规模下展现出意想不到的新兴能力，但我们需要一个理论框架来解释它们为什么以及如何出现。我们证明语言模型实际上是非遍历系统，并基于斯图尔特·考夫曼的邻近可能理论（TAP）提供了数学框架来解释这些能力的出现。我们的资源受限TAP方程展示了针对语义空间相变，架构、训练和上下文约束如何相互作用以塑造模型的能力。通过使用三个不同语言模型的实验，我们证明能力是通过由约束交互和路径依赖探索引导的离散过渡逐步出现的。该框架为理解语言模型中的新兴现象提供了理论基础，并指导了能够引导能力出现的架构的开发。 

---
# ICPC: In-context Prompt Compression with Faster Inference 

**Title (ZH)**: ICPC：基于上下文的提示压缩与更快的推理 

**Authors**: Ziyang Yu, Yuyu Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01625)  

**Abstract**: Despite the recent success of Large Language Models (LLMs), it remains challenging to feed LLMs with long prompts due to the fixed size of LLM inputs. As a remedy, prompt compression becomes a promising solution by removing redundant tokens in the prompt. However, using LLM in the existing works requires additional computation resources and leads to memory overheads. To address it, we propose ICPC (In-context Prompt Compression), a novel and scalable prompt compression method that adaptively reduces the prompt length. The key idea of ICPC is to calculate the probability of each word appearing in the prompt using encoders and calculate information carried by each word through the information function, which effectively reduces the information loss during prompt compression and increases the speed of compression. Empirically, we demonstrate that ICPC can effectively compress long texts of different categories and thus achieve better performance and speed on different types of NLP tasks. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）取得了近期的成功，但由于LLM输入长度固定的问题，向LLM提供长提示仍然具有挑战性。为此，提示压缩成为一种有前途的解决方案，通过去除提示中的冗余词汇来解决问题。然而，在现有工作中使用LLM需要额外的计算资源，并导致内存开销。为了解决这一问题，我们提出了ICPC（In-context Prompt Compression）方法，这是一种新颖且可扩展的提示压缩方法，能够自适应地减少提示长度。ICPC的核心思想是使用编码器计算提示中每个词出现的概率，并通过信息函数计算每个词携带的信息量，从而有效地减少压缩过程中信息丢失，并提高压缩速度。实验证明，ICPC能够有效地压缩不同类别的长文本，从而在不同类型的语言处理任务上实现更好的性能和速度。 

---
# PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents 

**Title (ZH)**: PSYCHE：一种多维度患者模拟框架，用于心理健康评估对话代理的评估 

**Authors**: Jingoo Lee, Kyungho Lim, Young-Chul Jung, Byung-Hoon Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.01594)  

**Abstract**: Recent advances in large language models (LLMs) have accelerated the development of conversational agents capable of generating human-like responses. Since psychiatric assessments typically involve complex conversational interactions between psychiatrists and patients, there is growing interest in developing LLM-based psychiatric assessment conversational agents (PACAs) that aim to simulate the role of psychiatrists in clinical evaluations. However, standardized methods for benchmarking the clinical appropriateness of PACAs' interaction with patients still remain underexplored. Here, we propose PSYCHE, a novel framework designed to enable the 1) clinically relevant, 2) ethically safe, 3) cost-efficient, and 4) quantitative evaluation of PACAs. This is achieved by simulating psychiatric patients based on a multi-faceted psychiatric construct that defines the simulated patients' profiles, histories, and behaviors, which PACAs are expected to assess. We validate the effectiveness of PSYCHE through a study with 10 board-certified psychiatrists, supported by an in-depth analysis of the simulated patient utterances. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）的发展加速了能生成类人类响应的对话代理的开发。由于精神病评估通常涉及精神科医师与患者之间的复杂对话互动，因此在基于LLM的精神病评估对话代理（PACAs）中模拟精神科医师的角色引起了越来越大的兴趣。然而，用于基准测试PACAs与患者互动临床适宜性的标准化方法仍处于未探索状态。在此，我们提出了一种名为PSYCHE的新颖框架，旨在实现如下四个方面的评估：1）临床相关性，2）伦理安全性，3）成本效益，4）定量评估。该框架通过基于多维精神病构想来模拟患者的个人特征、历史和行为，并评估PACAs对这些患者的评估能力。我们通过一项包含10名认证精神科医师的研究，结合对模拟患者话语的深入分析，验证了PSYCHE的有效性。 

---
# (WhyPHI) Fine-Tuning PHI-3 for Multiple-Choice Question Answering: Methodology, Results, and Challenges 

**Title (ZH)**: (WhyPHI) 将 PHI-3 调整应用于多项选择题回答：方法、结果与挑战 

**Authors**: Mohamed Hisham Abdellatif  

**Link**: [PDF](https://arxiv.org/pdf/2501.01588)  

**Abstract**: Large Language Models (LLMs) have become essential tools across various domains due to their impressive capabilities in understanding and generating human-like text. The ability to accurately answer multiple-choice questions (MCQs) holds significant value in education, particularly in automated tutoring systems and assessment platforms. However, adapting LLMs to handle MCQ tasks effectively remains challenging due to the hallucinations and unclear prompts. This work explores the potential of Microsoft's PHI-3\cite{Abdin2024}, a compact yet efficient LLM, for MCQ answering. Our contributions include fine-tuning the model on the TruthfulQA dataset, designing optimized prompts to enhance model performance, and evaluating using perplexity and traditional metrics like accuracy and F1 score. Results show a remarkable improvement in PHI-3.5's MCQ handling post-fine-tuning, with perplexity decreasing from 4.68 to 2.27, and accuracy rising from 62\% to 90.8\%. This research underlines the importance of efficient models in adaptive learning systems and educational assessments, paving the way for broader integration into the classroom, particularly in fields like test preparation, student feedback, and personalized learning. 

**Abstract (ZH)**: 大型语言模型（LLMs）因其在理解和生成人类样式的文本方面表现出色，已成为各个领域的关键工具。准确回答多项选择题（MCQs）的能力在教育领域尤为重要，特别是在自动化辅导系统和评估平台中。然而，有效地适应LLMs以处理MCQ任务仍面临挑战，这主要是由于它们在生成与现实不一致的回答和模糊提示方面的问题。本研究探讨了微软PHI-3 [1] 在处理MCQ任务方面的潜在价值，PHI-3是一个紧凑而高效的LLM。我们的贡献包括在TruthfulQA数据集上对该模型进行微调，设计优化提示以提高模型性能，并使用困惑度和传统的准确率和F1分数等指标进行评估。结果显示，经过微调后，PHI-3.5在处理MCQ任务方面的表现有了显著提升，困惑度从4.68降至2.27，准确率从62%升至90.8%。本研究强调了在自适应学习系统和教育评估中使用高效模型的重要性，为将其更广泛地应用于课堂教学铺平了道路，特别是在测试准备、学生反馈和个人化学习等领域中。 

---
# Auto-RT: Automatic Jailbreak Strategy Exploration for Red-Teaming Large Language Models 

**Title (ZH)**: Auto-RT：用于红队测试大规模语言模型的自动越狱策略探索 

**Authors**: Yanjiang Liu, Shuhen Zhou, Yaojie Lu, Huijia Zhu, Weiqiang Wang, Hongyu Lin, Ben He, Xianpei Han, Le Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.01830)  

**Abstract**: Automated red-teaming has become a crucial approach for uncovering vulnerabilities in large language models (LLMs). However, most existing methods focus on isolated safety flaws, limiting their ability to adapt to dynamic defenses and uncover complex vulnerabilities efficiently. To address this challenge, we propose Auto-RT, a reinforcement learning framework that automatically explores and optimizes complex attack strategies to effectively uncover security vulnerabilities through malicious queries. Specifically, we introduce two key mechanisms to reduce exploration complexity and improve strategy optimization: 1) Early-terminated Exploration, which accelerate exploration by focusing on high-potential attack strategies; and 2) Progressive Reward Tracking algorithm with intermediate downgrade models, which dynamically refine the search trajectory toward successful vulnerability exploitation. Extensive experiments across diverse LLMs demonstrate that, by significantly improving exploration efficiency and automatically optimizing attack strategies, Auto-RT detects a boarder range of vulnerabilities, achieving a faster detection speed and 16.63\% higher success rates compared to existing methods. 

**Abstract (ZH)**: 自动化红队编程已成为发现大型语言模型（LLMs）漏洞的关键方法。然而，现有大多数方法主要集中在孤立的安全缺陷上，限制了它们适应动态防御并高效发现复杂漏洞的能力。为解决这一挑战，我们提出了Auto-RT，这是一种基于强化学习的框架，能够自动探索和优化复杂攻击策略，以高效地通过恶意查询发现安全漏洞。具体而言，我们引入了两种关键机制以降低探索复杂性并改进策略优化：1）早期终止探索，通过集中于具有高潜力的攻击策略加速探索；2）逐步奖励追踪算法结合中间降级模型，动态优化寻找成功利用漏洞的搜索路径。广泛的跨不同类型的LLM实验表明，通过大幅提高探索效率并自动优化攻击策略，Auto-RT检测到更广泛的漏洞，实现更快的检测速度以及比现有方法高出16.63%的成功率。 

---
# SDPO: Segment-Level Direct Preference Optimization for Social Agents 

**Title (ZH)**: SDPO：社会智能体的段级直接偏好优化 

**Authors**: Aobo Kong, Wentao Ma, Shiwan Zhao, Yongbin Li, Yuchuan Wu, Ke Wang, Xiaoqian Liu, Qicheng Li, Yong Qin, Fei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01821)  

**Abstract**: Social agents powered by large language models (LLMs) can simulate human social behaviors but fall short in handling complex goal-oriented social dialogues. Direct Preference Optimization (DPO) has proven effective in aligning LLM behavior with human preferences across a variety of agent tasks. Existing DPO-based approaches for multi-turn interactions are divided into turn-level and session-level methods. The turn-level method is overly fine-grained, focusing exclusively on individual turns, while session-level methods are too coarse-grained, often introducing training noise. To address these limitations, we propose Segment-Level Direct Preference Optimization (SDPO), which focuses on specific key segments within interactions to optimize multi-turn agent behavior while minimizing training noise. Evaluations on the SOTOPIA benchmark demonstrate that SDPO-tuned agents consistently outperform both existing DPO-based methods and proprietary LLMs like GPT-4o, underscoring SDPO's potential to advance the social intelligence of LLM-based agents. We release our code and data at this https URL. 

**Abstract (ZH)**: 由大型语言模型（LLMs）驱动的社会代理能够模拟人类的社会行为，但在处理复杂的以目标为导向的社会对话时表现不佳。直接偏好优化（DPO）已在多种代理任务中证明了其有效性，能够将语言模型的行为与人类偏好对齐。现有的基于DPO的多轮交互方法被分为回合级和会话级两种方法。回合级方法过于精细，仅专注于单个回合，而会话级方法则过于粗糙，经常引入训练噪声。为了解决这些问题，我们提出了一种段落级直接偏好优化（SDPO）方法，该方法专注于交互中的特定关键段落，以优化多轮代理行为并最小化训练噪声。在SOTOPIA基准上的评估表明，SDPO调优的代理始终优于现有的基于DPO的方法和专有的LLM模型，如GPT-4o，这表明SDPO有可能提升基于LLM的社会智能。我们已在以下链接发布了我们的代码和数据：[请输入代码和数据发布链接]。 

---
# How Toxic Can You Get? Search-based Toxicity Testing for Large Language Models 

**Title (ZH)**: 《你能有多毒？基于搜索的大型语言模型毒性测试》

这个翻译保持了原文的学术风格，并且清晰地传达了研究的主题。在这里，“Toxicity”特指言论或内容的有害性或攻击性。如果在特定背景下有更精确的术语，可以进一步调整。 

**Authors**: Simone Corbo, Luca Bancale, Valeria De Gennaro, Livia Lestingi, Vincenzo Scotti, Matteo Camilli  

**Link**: [PDF](https://arxiv.org/pdf/2501.01741)  

**Abstract**: Language is a deep-rooted means of perpetration of stereotypes and discrimination. Large Language Models (LLMs), now a pervasive technology in our everyday lives, can cause extensive harm when prone to generating toxic responses. The standard way to address this issue is to align the LLM, which, however, dampens the issue without constituting a definitive solution. Therefore, testing LLM even after alignment efforts remains crucial for detecting any residual deviations with respect to ethical standards. We present EvoTox, an automated testing framework for LLMs' inclination to toxicity, providing a way to quantitatively assess how much LLMs can be pushed towards toxic responses even in the presence of alignment. The framework adopts an iterative evolution strategy that exploits the interplay between two LLMs, the System Under Test (SUT) and the Prompt Generator steering SUT responses toward higher toxicity. The toxicity level is assessed by an automated oracle based on an existing toxicity classifier. We conduct a quantitative and qualitative empirical evaluation using four state-of-the-art LLMs as evaluation subjects having increasing complexity (7-13 billion parameters). Our quantitative evaluation assesses the cost-effectiveness of four alternative versions of EvoTox against existing baseline methods, based on random search, curated datasets of toxic prompts, and adversarial attacks. Our qualitative assessment engages human evaluators to rate the fluency of the generated prompts and the perceived toxicity of the responses collected during the testing sessions. Results indicate that the effectiveness, in terms of detected toxicity level, is significantly higher than the selected baseline methods (effect size up to 1.0 against random search and up to 0.99 against adversarial attacks). Furthermore, EvoTox yields a limited cost overhead (from 22% to 35% on average). 

**Abstract (ZH)**: 语言是一种根深蒂固的刻板印象和歧视传递手段。大型语言模型（LLM）如今已成为我们日常生活中不可或缺的技术，但在生成有毒回应时，可能会造成广泛的损害。解决这一问题的standard方法是使LLM对齐，然而这种方法只能缓解问题而不能提供一个最终的解决方案。因此，在对齐努力之后继续测试LLM对于检测任何残留的违背伦理标准的偏差仍然是至关重要的。我们提出了EvoTox，这是一个自动化的测试框架，用于评估LLM倾向生成有毒回应的程度，提供了一种定量评估方法，即使在对齐之后也能量化地评估LLM接近有毒回应的程度。该框架采用迭代进化策略，利用系统待测（SUT）和提示生成器（Prompt Generator）之间的相互作用，促使SUT生成更具毒性的回应。毒性水平通过基于现有毒提示分类器的自动仲裁进行评估。我们使用四种具有不同复杂度（7-13亿个参数）的先进LLM作为评估对象，进行了定量和定性的实验评估。定量评估评估了四种EvoTox版本相对于现有基线方法（随机搜索、精心策划的有毒提示数据集和对抗攻击）的成本效益。定性评估则邀请人类评估者根据生成提示的流畅性和收集到的测试会话中回应的感知毒性进行评分。结果显示，从检测毒性水平的有效性来看，EvoTox显著高于所选基线方法（与随机搜索的效果大小高达1.0，与对抗攻击的效果大小高达0.99）。此外，EvoTox的成本开销相对有限（平均从22%到35%）。 

---
# AgentRefine: Enhancing Agent Generalization through Refinement Tuning 

**Title (ZH)**: AgentRefine：通过精调提升代理的一般化能力 

**Authors**: Dayuan Fu, Keqing He, Yejie Wang, Wentao Hong, Zhuoma Gongque, Weihao Zeng, Wei Wang, Jingang Wang, Xunliang Cai, Weiran Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01702)  

**Abstract**: Large Language Model (LLM) based agents have proved their ability to perform complex tasks like humans. However, there is still a large gap between open-sourced LLMs and commercial models like the GPT series. In this paper, we focus on improving the agent generalization capabilities of LLMs via instruction tuning. We first observe that the existing agent training corpus exhibits satisfactory results on held-in evaluation sets but fails to generalize to held-out sets. These agent-tuning works face severe formatting errors and are frequently stuck in the same mistake for a long while. We analyze that the poor generalization ability comes from overfitting to several manual agent environments and a lack of adaptation to new situations. They struggle with the wrong action steps and can not learn from the experience but just memorize existing observation-action relations. Inspired by the insight, we propose a novel AgentRefine framework for agent-tuning. The core idea is to enable the model to learn to correct its mistakes via observation in the trajectory. Specifically, we propose an agent synthesis framework to encompass a diverse array of environments and tasks and prompt a strong LLM to refine its error action according to the environment feedback. AgentRefine significantly outperforms state-of-the-art agent-tuning work in terms of generalization ability on diverse agent tasks. It also has better robustness facing perturbation and can generate diversified thought in inference. Our findings establish the correlation between agent generalization and self-refinement and provide a new paradigm for future research. 

**Abstract (ZH)**: 基于大型语言模型（LLM）的代理已经证明了其能够执行复杂任务的能力，如同人类一样。然而，开源的LLM与商用模型如GPT系列之间仍然存在较大的差距。在本文中，我们专注于通过指令调优来提高LLM代理的泛化能力。我们首先观察到，现有的代理训练数据集在内部分割的评估集中取得了令人满意的结果，但在外部分割的评估集上却无法很好地泛化。这些代理调优工作面临严重的格式错误，且经常长时间陷入同样的错误。我们分析认为，这种差的泛化能力来自于对几个手动代理环境的过度拟合，以及对新情况适应不足。它们难以纠正错误的行动步骤，不能从经验中学习，只是记忆现有的观察-行动关系。受到这一洞察的启发，我们提出了一种新的AgentRefine框架来改善代理调优。核心思想是让模型通过轨迹中的观察来学习自我纠正错误。具体而言，我们提出了一个代理合成框架，以涵盖广泛多样化的环境和任务，并提示一个强大的LLM根据环境反馈修正其错误动作。与最先进的代理调优工作相比，AgentRefine在多种代理任务上的泛化能力显著更优。此外，它在面对干扰时具有更好的鲁棒性，并且在推理过程中能生成多样化的思考。我们的发现确立了代理泛化能力与自我修正之间的关联，并为未来的研究提供了一个新的框架。 

---
# Crossing Language Borders: A Pipeline for Indonesian Manhwa Translation 

**Title (ZH)**: 跨越语言边界：印尼 manhwa 翻译管道 

**Authors**: Nithyasri Narasimhan, Sagarika Singh  

**Link**: [PDF](https://arxiv.org/pdf/2501.01629)  

**Abstract**: In this project, we develop a practical and efficient solution for automating the Manhwa translation from Indonesian to English. Our approach combines computer vision, text recognition, and natural language processing techniques to streamline the traditionally manual process of Manhwa(Korean comics) translation. The pipeline includes fine-tuned YOLOv5xu for speech bubble detection, Tesseract for OCR and fine-tuned MarianMT for machine translation. By automating these steps, we aim to make Manhwa more accessible to a global audience while saving time and effort compared to manual translation methods. While most Manhwa translation efforts focus on Japanese-to-English, we focus on Indonesian-to-English translation to address the challenges of working with low-resource languages. Our model shows good results at each step and was able to translate from Indonesian to English efficiently. 

**Abstract (ZH)**: 在本项目中，我们开发了一种实用且高效的自动化方案，用于将印尼语漫画（Manhwa）翻译成英语。我们的方法结合了计算机视觉、文本识别和自然语言处理技术，从而简化了传统的手动翻译过程。整个工作流包括针对对话泡泡检测进行了微调的YOLov5xu、用于光学字符识别（OCR）的Tesseract以及针对机器翻译进行了微调的MarianMT。通过自动化这些步骤，我们旨在使印尼语漫画在全球范围内更加易于访问，同时相比手动翻译方法节省时间和精力。尽管大多数漫画翻译工作侧重于从日语到英语的翻译，但我们更专注于从印尼语到英语的翻译，以应对使用低资源语言所面临的挑战。我们的模型在每一步都取得了良好的结果，并能够高效地完成从印尼语到英语的翻译任务。 

---
# Predicting the Performance of Black-box LLMs through Self-Queries 

**Title (ZH)**: 通过自我查询预测黑盒大语言模型的性能 

**Authors**: Dylan Sam, Marc Finzi, J. Zico Kolter  

**Link**: [PDF](https://arxiv.org/pdf/2501.01558)  

**Abstract**: As large language models (LLMs) are increasingly relied on in AI systems, predicting when they make mistakes is crucial. While a great deal of work in the field uses internal representations to interpret model behavior, these representations are inaccessible when given solely black-box access through an API. In this paper, we extract features of LLMs in a black-box manner by using follow-up prompts and taking the probabilities of different responses as representations to train reliable predictors of model behavior. We demonstrate that training a linear model on these low-dimensional representations produces reliable and generalizable predictors of model performance at the instance level (e.g., if a particular generation correctly answers a question). Remarkably, these can often outperform white-box linear predictors that operate over a model's hidden state or the full distribution over its vocabulary. In addition, we demonstrate that these extracted features can be used to evaluate more nuanced aspects of a language model's state. For instance, they can be used to distinguish between a clean version of GPT-4o-mini and a version that has been influenced via an adversarial system prompt that answers question-answering tasks incorrectly or introduces bugs into generated code. Furthermore, they can reliably distinguish between different model architectures and sizes, enabling the detection of misrepresented models provided through an API (e.g., identifying if GPT-3.5 is supplied instead of GPT-4o-mini). 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在AI系统中的应用越来越广泛，预测其何时出错变得至关重要。尽管该领域中大量的工作使用内部表示来解释模型行为，但在仅通过API获取黑箱访问的情况下，这些表示是不可用的。在本文中，我们通过使用后续提示并以不同响应的概率作为表示来以黑箱方式提取LLMs的特征，以此训练可靠的行为预测模型。我们证明，在这些低维度表示上训练线性模型能够生成可靠的、具有普适性的实例级模型性能预测器（例如，如果某一生成正确回答了一个问题）。令人惊讶的是，这些预测器常常能够超越那些在模型隐藏状态或其词汇分布的完整概率分布上运行的白箱线性预测器。此外，我们还证明，这些提取的特征可用于评估语言模型状态的更精细方面。举例来说，它们可用于区分GPT-4o-mini的干净版本和被恶意系统提示影响过的版本，该提示错误回答了问题或引入了生成代码中的错误。此外，这些提取的特征还能可靠地区分不同的模型架构和规模，从而能够在API提供的模型中检测到误导性的模型（例如，识别是否存在使用GPT-3.5代替GPT-4o-mini的情况）。 

---
# Many of Your DPOs are Secretly One: Attempting Unification Through Mutual Information 

**Title (ZH)**: 你的许多DPO都秘密地归为一类：尝试通过互信息实现统一

注释：DPO是Distributed Processing Operator（分布式处理操作符）的缩写，在某些特定领域或研究中可能有特定的含义。在没有具体上下文的情况下，我将其翻译为“分布式处理操作符”。如果“DPO”在特定领域内有具体的含义，建议提供更具体的信息以便进行更准确的翻译。 

**Authors**: Rasul Tutnov, Antoine Grosnit, Haitham Bou-Ammar  

**Link**: [PDF](https://arxiv.org/pdf/2501.01544)  

**Abstract**: Post-alignment of large language models (LLMs) is critical in improving their utility, safety, and alignment with human intentions. Direct preference optimisation (DPO) has become one of the most widely used algorithms for achieving this alignment, given its ability to optimise models based on human feedback directly. However, the vast number of DPO variants in the literature has made it increasingly difficult for researchers to navigate and fully grasp the connections between these approaches. This paper introduces a unifying framework inspired by mutual information, which proposes a new loss function with flexible priors. By carefully specifying these priors, we demonstrate that many existing algorithms, such as SimPO, TDPO, SparsePO, and others, can be derived from our framework. This unification offers a clearer and more structured approach, allowing researchers to understand the relationships between different DPO variants better. We aim to simplify the landscape of DPO algorithms, making it easier for the research community to gain insights and foster further advancements in LLM alignment. Ultimately, we hope our framework can be a foundation for developing more robust and interpretable alignment techniques. 

**Abstract (ZH)**: 大规模语言模型（LLMs）的后对齐对于提高其实用性和与人类意图的一致性至关重要。直接偏好优化（DPO）因其能够基于人类反馈直接优化模型的能力，已成为实现这一对齐最广泛使用的方法之一。然而，文献中众多的DPO变体使得研究人员越来越难以导航和全面理解这些方法之间的联系。本文引入了一个以互信息为基础的统一框架，提出了一个新的具有灵活先验的损失函数。通过仔细制定这些先验条件，我们演示了SimPO、TDPO、SparsePO以及其他许多现有算法可以从我们的框架中导出。这一统一方法提供了一个更清晰且结构化的视角，使研究人员能够更好地理解不同DPO变体之间的关系。我们旨在简化DPO算法的景观，使研究社区更容易获得洞察力，并进一步推动LLM对齐的进展。最终，我们希望这个框架能成为开发更稳健且可解释对齐技术的基础。 

---
# A Metasemantic-Metapragmatic Framework for Taxonomizing Multimodal Communicative Alignment 

**Title (ZH)**: 一种元语义-元语用框架，用于分类化多模态交际对齐 

**Authors**: Eugene Yu Ji  

**Link**: [PDF](https://arxiv.org/pdf/2501.01535)  

**Abstract**: Drawing on contemporary pragmatist philosophy and linguistic theories on cognition, meaning, and communication, this paper presents a dynamic, metasemantic-metapragmatic taxonomy for grounding and conceptualizing human-like multimodal communicative alignment. The framework is rooted in contemporary developments of the three basic communicative capacities initially identified by American logician and pragmatist philosopher Charles Sanders Peirce: iconic (sensory and perceptual qualities), indexical (contextual and sociocultural associations), and rule-like (symbolic and intuitive reasoning). Expanding on these developments, I introduce the concept of indexical contextualization and propose the principle of "contextualization directionality" for characterizing the crucial metapragmatic capacity for maintaining, navigating, or transitioning between semantic and pragmatic modes of multimodal communication. I contend that current cognitive-social computational and engineering methodologies disproportionately emphasize the semantic/metasemantic domain, overlooking the pivotal role of metapragmatic indexicality in traversing the semantic-pragmatic spectrum of communication. The framework's broader implications for intentionality, identity, affect, and ethics in within-modal and cross-modal human-machine alignment are also discussed. 

**Abstract (ZH)**: 本文借鉴了当代实用主义哲学和认知、意义及交流语言理论，提出了一种动态的、元语义-元修辞分类框架，用于建立和概念化类似人类的多模态交流对齐。该框架扎根于美国逻辑学家和实用主义哲学家查尔斯·桑德斯·皮尔士最初识别出的三种基本交流能力的当代发展：符号性的（感官和知觉特性）、指示性的（语境和社会文化关联），以及规则性的（象征性和直觉推理）。在此基础上，本文引入了“指示性语境化”的概念，并提出了“语境化方向性”原则，用于描述维持、导航或多模态沟通在语义和语用模式之间转换的关键元修辞能力。我主张当前的认知社会计算方法和工程方法过度强调语义/元语义领域，忽视了元修辞指示性在跨越沟通语义-语用光谱中的关键作用。此外，本文还讨论了该框架在同模态和跨模态的人机对齐中对意向性、身份、情感和伦理学的更广泛影响。 

---
# Improving Robustness Estimates in Natural Language Explainable AI though Synonymity Weighted Similarity Measures 

**Title (ZH)**: 通过同义词权重相似度度量提高自然语言可解释人工智能的稳健性估计 

**Authors**: Christopher Burger  

**Link**: [PDF](https://arxiv.org/pdf/2501.01516)  

**Abstract**: Explainable AI (XAI) has seen a surge in recent interest with the proliferation of powerful but intractable black-box models. Moreover, XAI has come under fire for techniques that may not offer reliable explanations. As many of the methods in XAI are themselves models, adversarial examples have been prominent in the literature surrounding the effectiveness of XAI, with the objective of these examples being to alter the explanation while maintaining the output of the original model. For explanations in natural language, it is natural to use measures found in the domain of information retrieval for use with ranked lists to guide the adversarial XAI process. We show that the standard implementation of these measures are poorly suited for the comparison of explanations in adversarial XAI and amend them by using information that is discarded, the synonymity of perturbed words. This synonymity weighting produces more accurate estimates of the actual weakness of XAI methods to adversarial examples. 

**Abstract (ZH)**: 可解释人工智能（XAI）在近期由于强大但难以捉摸的黑盒模型的广泛应用而引起了广泛关注。此外，XAI因可能不提供可靠解释的技术而受到了批评。由于许多XAI方法本身也是模型，对抗性示例在关于XAI有效性的文献中占据了重要位置，这些示例的目的是在保持原始模型输出不变的情况下改变解释。对于自然语言解释，自然可以使用信息检索领域用于加权排名列表的度量来引导对抗性XAI过程。

我们发现标准实现的这些度量方法在对抗性XAI中比较解释效果时并不合适，并通过利用被丢弃的信息（即扰动单词的同义性）对它们进行了改进。这种同义性加权可以更准确地估计XAI方法对抗性示例的实际脆弱性。 

---
# Enhancing Reasoning through Process Supervision with Monte Carlo Tree Search 

**Title (ZH)**: 通过蒙特卡洛树搜索进行过程监督以增强推理能力 

**Authors**: Shuangtao Li, Shuaihao Dong, Kexin Luan, Xinhan Di, Chaofan Ding  

**Link**: [PDF](https://arxiv.org/pdf/2501.01478)  

**Abstract**: Large language models (LLMs) have demonstrated their remarkable capacity across a variety of tasks. However, reasoning remains a challenge for LLMs. To improve LLMs' reasoning ability, process supervision has proven to be better than outcome supervision. In this work, we study using Monte Carlo Tree Search (MCTS) to generate process supervision data with LLMs themselves for training them. We sample reasoning steps with an LLM and assign each step a score that captures its "relative correctness," and the LLM is then trained by minimizing weighted log-likelihood of generating the reasoning steps. This generate-then-train process is repeated iteratively until this http URL experimental results demonstrate that the proposed methods considerably improve the performance of LLMs on two mathematical reasoning datasets. Furthermore, models trained on one dataset also exhibit improved performance on the other, showing the transferability of the enhanced reasoning ability. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已经在多种任务中展现出了其显著的能力。然而，推理仍然是LLMs的一个挑战。为了提高LLMs的推理能力，过程监督已经被证明比结果监督更为有效。在本工作中，我们研究了利用蒙特卡洛树搜索（MCTS）结合LLMs本身来生成过程监督数据进行训练的方法。我们使用LLMs抽样推理步骤，并为每个步骤分配一个“相对正确性”的评分，然后通过最小化生成推理步骤的加权对数似然来进行LLMs的训练。此生成-训练过程是迭代进行的，直到满足特定条件为止。实验结果表明，提出的这些方法显著提高了LLMs在两个数学推理数据集上的性能。此外，通过一个数据集训练的模型在另一个数据集上也表现出改进的性能，展示了增强的推理能力的转移性。 

---
# Reinforcing Thinking through Reasoning-Enhanced Reward Models 

**Title (ZH)**: 通过推理增强奖励模型来强化思维 

**Authors**: Diji Yang, Linda Zeng, Kezhen Chen, Yi Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01457)  

**Abstract**: Large Language Models (LLMs) exhibit great potential in complex multi-step reasoning through inference-time thinking but still struggle with deciding when to stop thinking due to limited self-awareness about their knowledge boundaries. While human preference alignment has shown extraordinary opportunities, expensive labeling challenges adherence to scaling law. Language model self-critique, as an alternative to using human-labeled reasoning data, is questioned with its inherited biases. This work addresses these challenges by distilling the LLM's own reasoning processes into synthetic behavioral data, eliminating the need for manual labeling of intermediate steps. Building on this concept, we propose Distillation-Reinforcement-Reasoning (DRR), a three-step framework that leverages the LLM's inherent behaviors as external feedback by first generating behavioral data using the Reasoner (LLM) to reflect its reasoning capabilities, then training a lightweight discriminative reward model (DM) on behavioral data, and finally deploying the DM at inference time to assist the Reasoner's decision-making. Experiments on multiple benchmarks show that the DRR framework outperforms self-critique approaches without relying on additional complex data annotation. Benefiting from lightweight design, ease of replication, and adaptability, DRR is applicable to a wide range of LLM-centric tasks. 

**Abstract (ZH)**: 大语言模型（LLMs）在通过推理时展现出了在复杂多步骤推理方面的巨大潜力，但由于自我意识有限，它们在决定何时停止推理方面仍然存在困难。虽然人类偏好对齐展示了巨大的机会，但昂贵的标签成本违背了缩放定律。作为替代于使用人工标注的推理数据的语言模型自我批判，其本身固有的偏见引起了质疑。本研究通过对LLM自身的推理过程进行提炼，生成合成行为数据，从而消除人工标注中间步骤的需求。基于这一概念，我们提出了Distillation-Reinforcement-Reasoning (DRR) 三维框架，该框架利用LLM固有的行为作为外部反馈，首先使用Reasoner（LLM）生成行为数据以反映其推理能力，然后在一个轻量级判别奖励模型（DM）上训练行为数据，最后在推理时部署DM以协助Reasoner的决策。在多个基准测试中的实验表明，DRR框架在不依赖额外复杂数据标注的情况下优于自我批判方法。DRR由于其轻量级的设计、易于复制和适配性，适用于一系列以LLM为中心的任务。 

---