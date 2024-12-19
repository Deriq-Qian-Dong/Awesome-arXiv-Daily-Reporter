# TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks 

**Title (ZH)**: 《Agent公司：评估大规模语言模型代理在重要现实任务中的表现》

这个标题翻译成中文后，更加符合学术论文的规范和表达习惯。原英文标题中的“LLM Agents”通常指的是“大规模语言模型代理”，在翻译时可以进一步明确为“大规模语言模型代理”。 

**Authors**: Frank F. Xu, Yufan Song, Boxuan Li, Yuxuan Tang, Kritanjali Jain, Mengxue Bao, Zora Z. Wang, Xuhui Zhou, Zhitong Guo, Murong Cao, Mingyang Yang, Hao Yang Lu, Amaad Martin, Zhe Su, Leander Maben, Raj Mehta, Wayne Chi, Lawrence Jang, Yiqing Xie, Shuyan Zhou, Graham Neubig  

**Link**: [PDF](https://arxiv.org/pdf/2412.14161)  

**Abstract**: We interact with computers on an everyday basis, be it in everyday life or work, and many aspects of work can be done entirely with access to a computer and the Internet. At the same time, thanks to improvements in large language models (LLMs), there has also been a rapid development in AI agents that interact with and affect change in their surrounding environments. But how performant are AI agents at helping to accelerate or even autonomously perform work-related tasks? The answer to this question has important implications for both industry looking to adopt AI into their workflows, and for economic policy to understand the effects that adoption of AI may have on the labor market. To measure the progress of these LLM agents' performance on performing real-world professional tasks, in this paper, we introduce TheAgentCompany, an extensible benchmark for evaluating AI agents that interact with the world in similar ways to those of a digital worker: by browsing the Web, writing code, running programs, and communicating with other coworkers. We build a self-contained environment with internal web sites and data that mimics a small software company environment, and create a variety of tasks that may be performed by workers in such a company. We test baseline agents powered by both closed API-based and open-weights language models (LMs), and find that with the most competitive agent, 24% of the tasks can be completed autonomously. This paints a nuanced picture on task automation with LM agents -- in a setting simulating a real workplace, a good portion of simpler tasks could be solved autonomously, but more difficult long-horizon tasks are still beyond the reach of current systems. 

**Abstract (ZH)**: 我们日常生活和工作中每天都会与计算机进行交互，许多工作可以通过计算机和互联网来完成。同时，得益于大型语言模型（LLMs）的改进，与环境交互并产生影响的AI代理也迅速发展起来。那么，这些AI代理在帮助加速或自主执行工作任务方面表现如何？这个问题的答案对于希望将AI纳入工作流程的行业以及理解AI采纳对劳动力市场影响的经济政策具有重要意义。

为了衡量这些LLM代理在执行真实世界专业任务方面的表现，本文介绍了一个可扩展的基准测试——TheAgentCompany。这个基准测试评估的是以类似于数字工人的方式与世界进行交互的AI代理：浏览网络、编写代码、运行程序、与同事沟通。我们构建了一个独立的环境，其中包括模拟小型软件公司环境的内部网站和数据，并创建了一系列可能由公司员工执行的任务。我们测试了使用封闭API和开放参数语言模型（LMs）为基础的基线代理，并发现使用最先进的代理时，有24%的任务可以自主完成。这展示了一个复杂的自动化任务图景——在一个模拟真实工作场所的环境中，许多简单的任务可以自主解决，但更复杂的长期任务仍然超出现有系统的能力范围。 

---
# GLIDER: Grading LLM Interactions and Decisions using Explainable Ranking 

**Title (ZH)**: GLIDER：使用可解释排名来评估LLM交互与决策 

**Authors**: Darshan Deshpande, Selvan Sunitha Ravi, Sky CH-Wang, Bartosz Mielczarek, Anand Kannappan, Rebecca Qian  

**Link**: [PDF](https://arxiv.org/pdf/2412.14140)  

**Abstract**: The LLM-as-judge paradigm is increasingly being adopted for automated evaluation of model outputs. While LLM judges have shown promise on constrained evaluation tasks, closed source LLMs display critical shortcomings when deployed in real world applications due to challenges of fine grained metrics and explainability, while task specific evaluation models lack cross-domain generalization. We introduce GLIDER, a powerful 3B evaluator LLM that can score any text input and associated context on arbitrary user defined criteria. GLIDER shows higher Pearson's correlation than GPT-4o on FLASK and greatly outperforms prior evaluation models, achieving comparable performance to LLMs 17x its size. GLIDER supports fine-grained scoring, multilingual reasoning, span highlighting and was trained on 685 domains and 183 criteria. Extensive qualitative analysis shows that GLIDER scores are highly correlated with human judgments, with 91.3% human agreement. We have open-sourced GLIDER to facilitate future research. 

**Abstract (ZH)**: LLM作为裁判的范式正越来越多地被应用于模型输出的自动化评估。虽然LLM裁判在受限评估任务中显示出了潜力，但封闭源代码的LLM在实际应用中由于细粒度指标和可解释性方面的挑战而表现出关键的不足，而特定任务的评估模型缺乏跨域泛化能力。我们引入了GLIDER，这是一种强大的3亿参数评估LLM，能够根据任意用户定义的评价标准对任意文本输入及其关联背景进行评分。GLIDER在FLASK上的皮尔逊相关系数高于GPT-4o，并且在其他方面显著超越了先前的评估模型，其性能与比自身规模大17倍的LLM相当。GLIDER支持细粒度评分、多语言推理、片段高亮，并基于685个领域和183个评价标准进行了训练。广泛的定性分析表明，GLIDER的评分与人工判断高度相关，91.3%的一致性。我们已开源了GLIDER，以便促进未来的研究。 

---
# Performance Gap in Entity Knowledge Extraction Across Modalities in Vision Language Models 

**Title (ZH)**: 视觉语言模型中跨模态实体知识提取的性能差距 

**Authors**: Ido Cohen, Daniela Gottesman, Mor Geva, Raja Giryes  

**Link**: [PDF](https://arxiv.org/pdf/2412.14133)  

**Abstract**: Vision-language models (VLMs) excel at extracting and reasoning about information from images. Yet, their capacity to leverage internal knowledge about specific entities remains underexplored. This work investigates the disparity in model performance when answering factual questions about an entity described in text versus depicted in an image. Our results reveal a significant accuracy drop --averaging 19%-- when the entity is presented visually instead of textually. We hypothesize that this decline arises from limitations in how information flows from image tokens to query tokens. We use mechanistic interpretability tools to reveal that, although image tokens are preprocessed by the vision encoder, meaningful information flow from these tokens occurs only in the much deeper layers. Furthermore, critical image processing happens in the language model's middle layers, allowing few layers for consecutive reasoning, highlighting a potential inefficiency in how the model utilizes its layers for reasoning. These insights shed light on the internal mechanics of VLMs and offer pathways for enhancing their reasoning capabilities. 

**Abstract (ZH)**: 视觉-语言模型（VLMs）在从图像中提取和推理信息方面表现出色。然而，它们利用内部知识处理特定实体的能力仍未得到充分探索。本研究探讨了当关于文本中描述的实体提出事实性问题和在图像中描述的问题相比时，模型性能之间的差异。我们的结果表明，在视觉呈现实体时相比于文本呈现，准确性平均降低了19%。我们假设这一下降源于图像标记到查询标记间信息流动的限制。我们利用机制可解释性工具发现，虽然图像标记由视觉编解码器预处理，但这些标记之间有意义的信息流动仅发生在更深的层次中。此外，关键的图像处理发生在语言模型的中间层，使得连续推理仅有少量层可利用，突显了模型在利用层次进行推理方面的潜在效率问题。这些洞察揭示了VLMs的内部工作机制，并为提升其推理能力提供了途径。 

---
# SEKE: Specialised Experts for Keyword Extraction 

**Title (ZH)**: SEKE: 专业专家关键词提取 

**Authors**: Matej Martinc, Hanh Thi Hong Tran, Senja Pollak, Boshko Koloski  

**Link**: [PDF](https://arxiv.org/pdf/2412.14087)  

**Abstract**: Keyword extraction involves identifying the most descriptive words in a document, allowing automatic categorisation and summarisation of large quantities of diverse textual data. Relying on the insight that real-world keyword detection often requires handling of diverse content, we propose a novel supervised keyword extraction approach based on the mixture of experts (MoE) technique. MoE uses a learnable routing sub-network to direct information to specialised experts, allowing them to specialize in distinct regions of the input space. SEKE, a mixture of Specialised Experts for supervised Keyword Extraction, uses DeBERTa as the backbone model and builds on the MoE framework, where experts attend to each token, by integrating it with a recurrent neural network (RNN), to allow successful extraction even on smaller corpora, where specialisation is harder due to lack of training data. The MoE framework also provides an insight into inner workings of individual experts, enhancing the explainability of the approach. We benchmark SEKE on multiple English datasets, achieving state-of-the-art performance compared to strong supervised and unsupervised baselines. Our analysis reveals that depending on data size and type, experts specialize in distinct syntactic and semantic components, such as punctuation, stopwords, parts-of-speech, or named entities. Code is available at: this https URL 

**Abstract (ZH)**: 关键词提取涉及识别文档中最具描述性的词语，从而实现大量异质文本数据的自动分类和总结。基于现实世界关键词检测往往需要处理多样内容的洞察，我们提出了一种基于混合专家（MoE）技术的新颖监督关键词提取方法。MoE 使用一个可学习的路由子网络来引导信息到专门的专家，使它们能够专注于输入空间的特定区域。SEKE，即基于混合专门专家的监督关键词提取方法，使用 DeBERTa 作为骨干模型，并在 MoE 框架下，通过将其与递归神经网络（RNN）集成，使专家能够关注每个词元，从而在规模较小的数据集上实现成功提取，尽管在这种情况下由于缺乏训练数据，专业化更加困难。MoE 框架还为个体专家的内部工作机制提供了洞察，增强了方法的可解释性。我们在多个英文数据集上对 SEKE 进行基准测试，相比强大的监督和非监督基线，取得了最先进的性能。我们的分析表明，根据数据的规模和类型，专家专注于不同的语法和语义成分，例如标点符号、停用词、词性或命名实体。代码可在以下网址获取：this https URL 

---
# Digestion Algorithm in Hierarchical Symbolic Forests: A Fast Text Normalization Algorithm and Semantic Parsing Framework for Specific Scenarios and Lightweight Deployment 

**Title (ZH)**: 层次符号森林中的消化算法：一种适用于特定场景且轻量部署的快速文本规范化算法及语义解析框架 

**Authors**: Kevin You  

**Link**: [PDF](https://arxiv.org/pdf/2412.14054)  

**Abstract**: Text Normalization and Semantic Parsing have numerous applications in natural language processing, such as natural language programming, paraphrasing, data augmentation, constructing expert systems, text matching, and more. Despite the prominent achievements of deep learning in Large Language Models (LLMs), the interpretability of neural network architectures is still poor, which affects their credibility and hence limits the deployments of risk-sensitive scenarios. In certain scenario-specific domains with scarce data, rapidly obtaining a large number of supervised learning labels is challenging, and the workload of manually labeling data would be enormous. Catastrophic forgetting in neural networks further leads to low data utilization rates. In situations where swift responses are vital, the density of the model makes local deployment difficult and the response time long, which is not conducive to local applications of these fields. Inspired by the multiplication rule, a principle of combinatorial mathematics, and human thinking patterns, a multilayer framework along with its algorithm, the Digestion Algorithm in Hierarchical Symbolic Forests (DAHSF), is proposed to address these above issues, combining text normalization and semantic parsing workflows. The Chinese Scripting Language "Fire Bunny Intelligent Development Platform V2.0" is an important test and application of the technology discussed in this paper. DAHSF can run locally in scenario-specific domains on little datasets, with model size and memory usage optimized by at least two orders of magnitude, thus improving the execution speed, and possessing a promising optimization outlook. 

**Abstract (ZH)**: 文本规范化和语义解析在自然语言处理中有众多应用，例如自然语言编程、同义词转换、数据增强、构建专家系统、文本匹配等。尽管大型语言模型（LLMs）中的深度学习取得了显著成就，但神经网络架构的可解释性仍然较差，这影响了它们的可信度，从而限制了在风险敏感场景中的部署。在某些特定数据稀缺的领域场景中，快速获取大量监督学习标签具有挑战性，而手动标注数据的工作量巨大。神经网络中的灾难性遗忘进一步导致了数据利用效率低下。在对迅速响应要求高的情况下，模型的稠密性使得局部部署困难，并增加了响应时间，从而不利于这些领域的本地应用。受乘法法则、组合数学原理和人类思维模式的启发，本文提出了一种多层次框架及其算法——分层符号森林中的消化算法（DAHSF），以解决上述问题，将文本规范化和语义解析的工作流程结合起来。中文scripting语言“Fire Bunny智能开发平台V2.0”是本文所讨论技术的重要测试和应用。DAHSF能够在特定场景的小数据集上进行本地运行，并通过至少两个数量级的模型大小和内存使用优化，从而提高执行速度，并展现出良好的优化前景。 

---
# Cross-Lingual Transfer of Debiasing and Detoxification in Multilingual LLMs: An Extensive Investigation 

**Title (ZH)**: 多语言大语言模型中去偏见和去毒化跨语言迁移的广泛研究 

**Authors**: Vera Neplenbroek, Arianna Bisazza, Raquel Fernández  

**Link**: [PDF](https://arxiv.org/pdf/2412.14050)  

**Abstract**: Recent generative large language models (LLMs) show remarkable performance in non-English languages, but when prompted in those languages they tend to express higher harmful social biases and toxicity levels. Prior work has shown that finetuning on specialized datasets can mitigate this behavior, and doing so in English can transfer to other languages. In this work, we investigate the impact of different finetuning methods on the model's bias and toxicity, but also on its ability to produce fluent and diverse text. Our results show that finetuning on curated non-harmful text is more effective for mitigating bias, and finetuning on direct preference optimization (DPO) datasets is more effective for mitigating toxicity. The mitigation caused by applying these methods in English also transfers to non-English languages. We find evidence that the extent to which transfer takes place can be predicted by the amount of data in a given language present in the model's pretraining data. However, this transfer of bias and toxicity mitigation often comes at the expense of decreased language generation ability in non-English languages, highlighting the importance of developing language-specific bias and toxicity mitigation methods. 

**Abstract (ZH)**: 近年来，生成型大型语言模型（LLMs）在非英语语言中表现出色，但在用这些语言进行提示时，往往会表现出更高的有害社会偏见和毒性水平。先前的研究已经表明，通过专门数据集进行微调可以减轻这种行为，并且在英语上进行的微调可以转移到其他语言。本研究探讨了不同微调方法对模型偏见和毒性的影响，同时也探讨了其产生流畅和多样化文本的能力。我们的结果显示，使用非有害文本编目的数据集进行微调更有效于减轻偏见，而使用直接偏好优化（DPO）数据集进行微调更有效于减轻毒性。这些方法在英语上的应用造成的减轻效果也会转移到非英语语言中。我们发现，转移的程度可以通过模型预训练数据中特定语言的数据量来预测。然而，这种偏见和毒性减轻的转移往往以非英语语言的语义生成能力降低为代价，突显了开发特定语言偏见和毒性减轻方法的重要性。 

---
# Hansel: Output Length Controlling Framework for Large Language Models 

**Title (ZH)**: Hansel: 大型语言模型的输出长度控制框架 

**Authors**: Seoha Song, Junhyun Lee, Hyeonmok Ko  

**Link**: [PDF](https://arxiv.org/pdf/2412.14033)  

**Abstract**: Despite the great success of large language models (LLMs), efficiently controlling the length of the output sequence still remains a challenge. In this paper, we propose Hansel, an efficient framework for length control in LLMs without affecting its generation ability. Hansel utilizes periodically outputted hidden special tokens to keep track of the remaining target length of the output sequence. Together with techniques to avoid abrupt termination of the output, this seemingly simple method proved to be efficient and versatile, while not harming the coherency and fluency of the generated text. The framework can be applied to any pre-trained LLMs during the finetuning stage of the model, regardless of its original positional encoding method. We demonstrate this by finetuning four different LLMs with Hansel and show that the mean absolute error of the output sequence decreases significantly in every model and dataset compared to the prompt-based length control finetuning. Moreover, the framework showed a substantially improved ability to extrapolate to target lengths unseen during finetuning, such as long dialog responses or extremely short summaries. This indicates that the model learns the general means of length control, rather than learning to match output lengths to those seen during training. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）取得了巨大的成功，但如何有效地控制输出序列的长度仍然是一项挑战。本文提出了一种名为Hansel的有效框架，能够在不牺牲LLMs生成能力的情况下控制输出序列的长度。Hansel利用定期输出的隐藏特殊标记来跟踪输出序列剩余的目标长度。结合避免输出突然终止的技术，这种方法虽然简单，但却证明是高效且灵活的，同时不会损害生成文本的连贯性和流畅度。该框架可以在模型的微调阶段应用于任何预训练的LLMs，而不限于其原始的位置编码方法。我们通过使用Hansel对四种不同的LLMs进行微调，并显示在每个模型和数据集中，使用Hansel的输出序列的绝对误差显著降低。此外，该框架在微调期间无法预见的目标长度（如长对话响应或极短的摘要）上表现出明显改进的外推能力。这一结果表明，模型学习了长度控制的一般方法，而不仅仅是学习匹配训练期间看到的输出长度。 

---