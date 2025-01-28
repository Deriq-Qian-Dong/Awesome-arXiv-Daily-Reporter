# LLM Reasoner and Automated Planner: A new NPC approach 

**Title (ZH)**: 大规模语言模型推理器和自动规划器：一种新的NPC方法 

**Authors**: Israel Puerta-Merino, Jordi Sabater-Mir  

**Link**: [PDF](https://arxiv.org/pdf/2501.10106)  

**Abstract**: In domains requiring intelligent agents to emulate plausible human-like behaviour, such as formative simulations, traditional techniques like behaviour trees encounter significant challenges. Large Language Models (LLMs), despite not always yielding optimal solutions, usually offer plausible and human-like responses to a given problem. In this paper, we exploit this capability and propose a novel architecture that integrates an LLM for decision-making with a classical automated planner that can generate sound plans for that decision. The combination aims to equip an agent with the ability to make decisions in various situations, even if they were not anticipated during the design phase. 

**Abstract (ZH)**: 在需要智能代理模仿人类行为的领域，如形成性模拟中，传统方法如行为树面临重大挑战。尽管大型语言模型（LLMs）通常不能总是提供最优解，但通常能提供合理且类似人类的响应。本文利用这一能力，提出了一种新的架构，该架构将LLM用于决策制定与经典的自动规划器相结合，后者能够生成支持该决策的可信计划。此组合旨在使代理能够在各种情况下做出决策，即使这些情况在设计阶段并未预见。 

---
# A Survey on LLM Test-Time Compute via Search: Tasks, LLM Profiling, Search Algorithms, and Relevant Frameworks 

**Title (ZH)**: 关于通过搜索进行大模型测试时计算的研究综述：任务、大模型分析、搜索算法及相关框架 

**Authors**: Xinzhe Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.10069)  

**Abstract**: LLM test-time compute (or LLM inference) via search has emerged as a promising research area with rapid developments. However, current frameworks often adopt distinct perspectives on three key aspects (task definition, LLM profiling, and search procedures), making direct comparisons challenging. Moreover, the search algorithms employed often diverge from standard implementations, and their specific characteristics are not thoroughly specified. In this survey, we provide a comprehensive technical review that unifies task definitions and provides modular definitions of LLM profiling and search procedures. The definitions enable precise comparisons of various LLM inference frameworks while highlighting their departures from conventional search algorithms. We also discuss the applicability, performance, and efficiency of these methods. For further details and ongoing updates, please refer to our GitHub repository: this https URL 

**Abstract (ZH)**: 基于搜索的大型语言模型（LLM）测试时计算（或推断）近年来已成为一个充满前景的研究领域，伴随着快速的发展。然而，当前的框架在任务定义、LLM分析和搜索过程三个方面通常采用不同的视角，这使得直接比较变得困难。此外，所使用的搜索算法往往不同于标准实现，其具体特征也没有得到充分规定。在本文综述中，我们提供了一个全面的技术回顾，统一了任务定义，并提供了模块化的LLM分析和搜索过程定义。这些定义使各种LLM推断框架之间的精确比较成为可能，同时突显了它们与传统搜索算法的不同之处。我们还讨论了这些方法的适用性、性能和效率。如需更多详细信息或最新更新，请参阅我们的GitHub仓库：[这个链接](this https URL)。 

---
# AirRAG: Activating Intrinsic Reasoning for Retrieval Augmented Generation via Tree-based Search 

**Title (ZH)**: AirRAG：通过树状搜索激活内在推理以增强检索生成

这个翻译符合学术规范，保留了原文的核心概念和结构。希望这对你有帮助！如果有更具体的内容需要翻译或进一步的帮助，请告诉我。 

**Authors**: Wenfeng Feng, Chuzhan Hao, Yuewei Zhang, Jingyi Song, Hao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.10053)  

**Abstract**: Leveraging the autonomous decision-making capabilities of large language models (LLMs) demonstrates superior performance in reasoning tasks. Despite the successes of iterative or recursive retrieval-augmented generation (RAG), they often are trapped in a single solution space when confronted with complex tasks. In this paper, we propose a novel thinking pattern in RAG which integrates system analysis with efficient reasoning actions, significantly activating intrinsic reasoning capabilities and expanding the solution space of specific tasks via Monte Carlo Tree Search (MCTS), dubbed AirRAG. Specifically, our approach designs five fundamental reasoning actions that are expanded to a wide tree-based reasoning spaces using MCTS. The extension also uses self-consistency verification to explore potential reasoning paths and implement inference scaling. In addition, computationally optimal strategies are used to apply more inference computation to key actions to achieve further performance improvements. Experimental results demonstrate the effectiveness of AirRAG through considerable performance gains over complex QA datasets. Furthermore, AirRAG is flexible and lightweight, making it easy to integrate with other advanced technologies. 

**Abstract (ZH)**: 利用大型语言模型（LLMs）的自主决策能力在推理任务中展现了优异的表现。尽管迭代或递归检索增强生成（RAG）方法取得了成功，但在面对复杂任务时，它们往往受限于单一的解决方案空间。本文提出了一种名为AirRAG的新颖的RAG推理模式，该方法将系统分析与高效的推理动作相结合，通过蒙特卡洛树搜索（MCTS）显著激活内在的推理能力，并通过这种方法扩展特定任务的解决方案空间。具体而言，我们的方法设计了五个基本的推理动作，并通过MCTS扩展到广泛的树结构推理空间。扩展还采用了自我一致性验证来探索潜在的推理路径并实现推理扩展。此外，使用计算上优化的策略将更多的推理计算应用到关键动作上，以实现进一步的性能提升。实验结果显示，与复杂的QA数据集相比，AirRAG在性能提升方面具有明显的效果。此外，AirRAG具有高度的灵活性和轻量级特性，使其易于与其他先进技术集成。 

---
# Evolving Deeper LLM Thinking 

**Title (ZH)**: 演化更深的大型语言模型思维 

**Authors**: Kuang-Huei Lee, Ian Fischer, Yueh-Hua Wu, Dave Marwood, Shumeet Baluja, Dale Schuurmans, Xinyun Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.09891)  

**Abstract**: We explore an evolutionary search strategy for scaling inference time compute in Large Language Models. The proposed approach, Mind Evolution, uses a language model to generate, recombine and refine candidate responses. The proposed approach avoids the need to formalize the underlying inference problem whenever a solution evaluator is available. Controlling for inference cost, we find that Mind Evolution significantly outperforms other inference strategies such as Best-of-N and Sequential Revision in natural language planning tasks. In the TravelPlanner and Natural Plan benchmarks, Mind Evolution solves more than 98% of the problem instances using Gemini 1.5 Pro without the use of a formal solver. 

**Abstract (ZH)**: 我们探索了一种进化搜索策略，以扩展大型语言模型的推理时间计算能力。所提出的方法名为Mind Evolution，利用语言模型生成、重组并优化候选答案。该方法避免了在有解决方案评估器可用时需要形式化底层推理问题的需要。在控制推理成本的情况下，我们发现Mind Evolution在自然语言规划任务中显著优于其他推理策略，如Best-of-N和序列修订。在TravelPlanner和Natural Plan基准测试中，没有使用正式解算器的情况下，Mind Evolution解决了超过98%的问题实例，使用的模型为Gemini 1.5 Pro。 

---
# Agent4Edu: Generating Learner Response Data by Generative Agents for Intelligent Education Systems 

**Title (ZH)**: Agent4Edu: 生成学习者响应数据的生成型智能代理以支持智能教育系统 

**Authors**: Weibo Gao, Qi Liu, Linan Yue, Fangzhou Yao, Rui Lv, Zheng Zhang, Hao Wang, Zhenya Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.10332)  

**Abstract**: Personalized learning represents a promising educational strategy within intelligent educational systems, aiming to enhance learners' practice efficiency. However, the discrepancy between offline metrics and online performance significantly impedes their progress. To address this challenge, we introduce Agent4Edu, a novel personalized learning simulator leveraging recent advancements in human intelligence through large language models (LLMs). Agent4Edu features LLM-powered generative agents equipped with learner profile, memory, and action modules tailored to personalized learning algorithms. The learner profiles are initialized using real-world response data, capturing practice styles and cognitive factors. Inspired by human psychology theory, the memory module records practice facts and high-level summaries, integrating reflection mechanisms. The action module supports various behaviors, including exercise understanding, analysis, and response generation. Each agent can interact with personalized learning algorithms, such as computerized adaptive testing, enabling a multifaceted evaluation and enhancement of customized services. Through a comprehensive assessment, we explore the strengths and weaknesses of Agent4Edu, emphasizing the consistency and discrepancies in responses between agents and human learners. The code, data, and appendix are publicly available at this https URL. 

**Abstract (ZH)**: 个性化学习在智能教育资源系统中代表了一种有前景的教学策略，旨在提高学习者的学习效率。然而，离线指标与在线表现之间的差异严重阻碍了其进步。为解决这一挑战，我们介绍了Agent4Edu，这是一种利用大型语言模型（LLMs）近期在人类智能方面的进展的新型个性化学习模拟器。Agent4Edu 配备了由学习者概况、记忆和行为模块支持的LLM驱动生成代理，这些模块专门针对个性化学习算法进行了定制。学习者概况使用实际反应数据进行初始化，捕捉了学习者的实践风格和认知因素。该记忆模块记录了实践事实和高阶总结，并整合了反思机制。行为模块支持各种行为，包括理解练习、分析和生成响应。每个代理都可以与个性化学习算法（如计算机化自适应测试）进行交互，从而实现对定制服务的多维评估和增强。通过全面评估，我们探讨了Agent4Edu的优势和不足，强调了代理和人类学习者之间反应的一致性和差异性。相关代码、数据和附录可在以下网址公开访问：[此链接](此链接)。 

---
# Accelerating Large Language Models through Partially Linear Feed-Forward Network 

**Title (ZH)**: 通过部分线性前馈网络加速大型语言模型 

**Authors**: Gansen Hu, Zhaoguo Wang, Jinglin Wei, Wei Huang, Haibo Chen  

**Link**: [PDF](https://arxiv.org/pdf/2501.10054)  

**Abstract**: Large language models (LLMs) demonstrate remarkable capabilities but face deployment challenges due to their massive parameter counts. While existing compression techniques like pruning can reduce model size, it leads to significant accuracy degradation under high compression ratios. We present a novel perspective inspired by constant folding in compiler optimization. Our approach enables parameter reduction by treating activation functions in LLMs as linear functions.
However, recent LLMs use complex non-linear activations like GELU that prevent direct application of this technique. We propose TARDIS, which enables optimization of LLMs with non-linear activations by partially approximating them with linear functions in frequently occurring input ranges. For outlier inputs, TARDIS employs an online predictor to dynamically fall back to original computations.
Our experiments demonstrate that TARDIS achieves 80% parameter reduction in feed-forward networks, while significantly outperforming state-of-the-art pruning methods Wanda and RIA with up to 65% higher accuracy. In practical deployments for a 7B model, TARDIS achieves 1.6x end-to-end inference speedup when integrated with the vLLM serving system, and 1.4x speedup with the widely adopted HuggingFace implementation, while incurring only a 10.9% accuracy trade-off. 

**Abstract (ZH)**: larg的语言模型（LLMs）表现出卓越的能力，但由于其庞大的参数数量，部署时面临挑战。虽然现有的压缩技术如剪枝可以在一定程度上减少模型大小，但在高压缩比下，这会导致显著的准确率下降。我们提出了一种新的视角，借鉴编译器优化中的常量折叠策略。我们的方法通过将LLMs中的激活函数视为线性函数来实现参数减少。

然而，最近的LLMs使用复杂的非线性激活函数（如GELU），这使得这种方法的直接应用变得不可能。为此，我们提出了TARDIS，它通过在经常出现的输入范围内部分地用线性函数近似非线性激活函数来优化使用非线性激活函数的LLMs。对于异常输入，TARDIS 使用一个在线预测器，根据需要动态切换回原始计算。

实验结果表明，TARDIS 在前向网络中实现了80%的参数减少，同时显著优于最先进的剪枝方法Wanda和RIA，在准确率上提高了高达65%。在结合vLLM服务系统和广泛采用的HuggingFace实现的实际部署中，TARDIS 为7B模型实现了1.6倍的端到端推理速度提升，同时仅有10.9%的准确率损失。 

---
# Attention-guided Self-reflection for Zero-shot Hallucination Detection in Large Language Models 

**Title (ZH)**: 面向注意力引导的自省方法在大型语言模型零样本幻觉检测中的应用 

**Authors**: Qiang Liu, Xinlong Chen, Yue Ding, Shizhen Xu, Shu Wu, Liang Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.09997)  

**Abstract**: Hallucination has emerged as a significant barrier to the effective application of Large Language Models (LLMs). In this work, we introduce a novel Attention-Guided SElf-Reflection (AGSER) approach for zero-shot hallucination detection in LLMs. The AGSER method utilizes attention contributions to categorize the input query into attentive and non-attentive queries. Each query is then processed separately through the LLMs, allowing us to compute consistency scores between the generated responses and the original answer. The difference between the two consistency scores serves as a hallucination estimator. In addition to its efficacy in detecting hallucinations, AGSER notably reduces computational complexity, requiring only three passes through the LLM and utilizing two sets of tokens. We have conducted extensive experiments with four widely-used LLMs across three different hallucination benchmarks, demonstrating that our approach significantly outperforms existing methods in zero-shot hallucination detection. 

**Abstract (ZH)**: 幻觉已成为大型语言模型（LLMs）有效应用的重要障碍。本文引入了一种新颖的注意力引导自我反思（AGSER）方法，用于零样本幻觉检测。AGSER 方法利用注意力贡献将输入查询分为注意查询和非注意查询。随后，每个查询分别通过 LLM 处理，使得我们可以计算生成响应与原始答案之间的一致性得分。两个一致性得分之间的差异作为幻觉估计器。除了在检测幻觉方面的有效性之外，AGSER 显著减少了计算复杂度，只需三次 LLM 通过，并使用两组标记。我们使用四种广泛使用的 LLM 在三个不同的幻觉基准上进行了大量的实验，结果显示我们的方法在零样本幻觉检测方面的性能显著优于现有方法。 

---
# Explainable artificial intelligence (XAI): from inherent explainability to large language models 

**Title (ZH)**: 可解释的人工智能（XAI）：从固有可解释性到大型语言模型 

**Authors**: Fuseini Mumuni, Alhassan Mumuni  

**Link**: [PDF](https://arxiv.org/pdf/2501.09967)  

**Abstract**: Artificial Intelligence (AI) has continued to achieve tremendous success in recent times. However, the decision logic of these frameworks is often not transparent, making it difficult for stakeholders to understand, interpret or explain their behavior. This limitation hinders trust in machine learning systems and causes a general reluctance towards their adoption in practical applications, particularly in mission-critical domains like healthcare and autonomous driving. Explainable AI (XAI) techniques facilitate the explainability or interpretability of machine learning models, enabling users to discern the basis of the decision and possibly avert undesirable behavior. This comprehensive survey details the advancements of explainable AI methods, from inherently interpretable models to modern approaches for achieving interpretability of various black box models, including large language models (LLMs). Additionally, we review explainable AI techniques that leverage LLM and vision-language model (VLM) frameworks to automate or improve the explainability of other machine learning models. The use of LLM and VLM as interpretability methods particularly enables high-level, semantically meaningful explanations of model decisions and behavior. Throughout the paper, we highlight the scientific principles, strengths and weaknesses of state-of-the-art methods and outline different areas of improvement. Where appropriate, we also present qualitative and quantitative comparison results of various methods to show how they compare. Finally, we discuss the key challenges of XAI and directions for future research. 

**Abstract (ZH)**: 近年来，人工智能（AI）取得了 tremendous 的成功。然而，这些框架的决策逻辑往往不够透明，这使得利益相关者难以理解、解释或解释其行为。这一局限性阻碍了对机器学习系统的信任，并导致在关键任务领域，如医疗保健和自动驾驶等广泛应用中，存在普遍的采用犹豫情绪。可解释的人工智能（XAI）技术能够增强机器学习模型的可解释性或可理解性，允许用户了解决策的基础，并可能防止不良行为。本文综述了可解释人工智能方法的最新进展，从固有的可解释性模型到现代实现各种黑盒模型可解释性的方法，包括大型语言模型（LLMs）。此外，本文还回顾了利用LLM和视觉-语言模型（VLM）框架提高其他机器学习模型可解释性的技术。使用LLM和VLM作为可解释性方法特别能够提供关于模型决策和行为的高层次、语义上具有意义的解释。在论文中，我们强调了最先进的方法的科学原理、优势和局限性，并概述了不同的改进领域。在适当时，我们还提供了各种方法的定性和定量比较结果，展示了它们之间的差异。最后，本文讨论了可解释人工智能的关键挑战和未来研究的方向。 

---
# Steering Large Language Models with Feature Guided Activation Additions 

**Title (ZH)**: 使用特征导向激活添加来引导大型语言模型 

**Authors**: Samuel Soo, Wesley Teng, Chandrasekaran Balaganesh  

**Link**: [PDF](https://arxiv.org/pdf/2501.09929)  

**Abstract**: Effective and reliable control over large language model (LLM) behavior is a significant challenge. While activation steering methods, which add steering vectors to a model's hidden states, are a promising approach, existing techniques often lack precision and interpretability in how they influence model outputs. We introduce Feature Guided Activation Additions (FGAA), a novel activation steering method that leverages insights from Contrastive Activation Addition (CAA) and Sparse Autoencoder-Targeted Steering (SAE-TS). By operating in the latent space of a Sparse Autoencoder (SAE) and employing optimization techniques to select desired SAE features, FGAA constructs precise steering vectors that provide better steering effects while maintaining coherence of steered model outputs. In this regard, evaluations on Gemma-2-2B and Gemma-2-9B models across various steering tasks demonstrate that FGAA outperforms existing steering methods of CAA, SAE decoder steering, and SAE-TS. Our results also highlight important trade-offs between steering scale and general model capabilities that are consistent across all tested steering methods. 

**Abstract (ZH)**: 对大型语言模型（LLM）行为的有效且可靠的控制是一个重大挑战。虽然激活引导方法——通过向模型的隐状态添加引导向量——是一种有希望的解决方案，但现有技术往往在如何影响模型输出方面缺乏精确性和可解释性。我们提出了一种名为特征引导激活添加（FGAA）的新颖激活引导方法，该方法结合了对比激活添加（CAA）和稀疏自动编码器目标导向引导（SAE-TS）的见解。FGAA在稀疏自动编码器（SAE）的潜在空间中操作，并使用优化技术选择所需的SAE特征，从而构建出能够提供更精确引导效果的同时保持引导后模型输出一致性的引导向量。在这点上，对Gemma-2-2B和Gemma-2-9B模型在多种引导任务上的评估表明，FGAA在各种引导方法中表现更优。此外，我们的研究结果还凸显了所有测试方法中引导规模与通用模型能力之间的重要权衡关系。 

---
# Multiple Choice Questions: Reasoning Makes Large Language Models (LLMs) More Self-Confident Even When They Are Wrong 

**Title (ZH)**: 多项选择题：推理使大规模语言模型（LLMs）即使在答错时也能更加自信 

**Authors**: Tairan Fu, Javier Conde, Gonzalo Martínez, María Grandury, Pedro Reviriego  

**Link**: [PDF](https://arxiv.org/pdf/2501.09775)  

**Abstract**: One of the most widely used methods to evaluate LLMs are Multiple Choice Question (MCQ) tests. MCQ benchmarks enable the testing of LLM knowledge on almost any topic at scale as the results can be processed automatically. To help the LLM answer, a few examples called few shots can be included in the prompt. Moreover, the LLM can be asked to answer the question directly with the selected option or to first provide the reasoning and then the selected answer, which is known as chain of thought. In addition to checking whether the selected answer is correct, the evaluation can look at the LLM-estimated probability of its response as an indication of the confidence of the LLM in the response. In this paper, we study how the LLM confidence in its answer depends on whether the model has been asked to answer directly or to provide the reasoning before answering. The results of the evaluation of questions on a wide range of topics in seven different models show that LLMs are more confident in their answers when they provide reasoning before the answer. This occurs regardless of whether the selected answer is correct. Our hypothesis is that this behavior is due to the reasoning that modifies the probability of the selected answer, as the LLM predicts the answer based on the input question and the reasoning that supports the selection made. Therefore, LLM estimated probabilities seem to have intrinsic limitations that should be understood in order to use them in evaluation procedures. Interestingly, the same behavior has been observed in humans, for whom explaining an answer increases confidence in its correctness. 

**Abstract (ZH)**: 评价大规模语言模型（LLM）的最常用方法之一是多项选择题（MCQ）测试。MCQ基准测试使得可以在大规模测试LLM知识方面发挥作用，因为结果可以自动处理。为了帮助LLM作答，可以在提示中包含一些示例，称为“零样本”或“少量样本”。此外，LLM可以被要求直接选择答案或首先提供推理再选择答案，这被称为推理链。除了检查选定的答案是否正确外，评估还可以通过检查LLM为其反应估算的概率来衡量其对答案的信心。在这种论文中，我们研究了LLM在直接作答与先提供推理再作答这两种情况下，其作答信心的变化。对七个不同模型在多种主题下的问题进行评估结果显示，LLM在先提供推理再作答的情况下对答案的信心更强。无论选定的答案是否正确，这种行为都会发生。我们的假设是，这种行为可能是由于推理改变了选定答案的概率，因为LLM是根据输入问题和支撑选择的推理来预测答案的。因此，LLM估算的概率似乎具有内在的局限性，有必要理解这些局限性以便在评估程序中加以利用。有趣的是，同样的行为也在人类中被观察到，即解释答案会增加对其正确性的信心。 

---
# Can Large Language Models Predict the Outcome of Judicial Decisions? 

**Title (ZH)**: 大型语言模型能否预测司法判决的结果？ 

**Authors**: Mohamed Bayan Kmainasi, Ali Ezzat Shahroor, Amani Al-Ghraibah  

**Link**: [PDF](https://arxiv.org/pdf/2501.09768)  

**Abstract**: Large Language Models (LLMs) have shown exceptional capabilities in Natural Language Processing (NLP) across diverse domains. However, their application in specialized tasks such as Legal Judgment Prediction (LJP) for low-resource languages like Arabic remains underexplored. In this work, we address this gap by developing an Arabic LJP dataset, collected and preprocessed from Saudi commercial court judgments. We benchmark state-of-the-art open-source LLMs, including LLaMA-3.2-3B and LLaMA-3.1-8B, under varying configurations such as zero-shot, one-shot, and fine-tuning using QLoRA. Additionally, we used a comprehensive evaluation framework combining quantitative metrics (BLEU and ROUGE) and qualitative assessments (Coherence, legal language, clarity). Our results demonstrate that fine-tuned smaller models achieve comparable performance to larger models in task-specific contexts while offering significant resource efficiency. Furthermore, we investigate the effects of prompt engineering and fine-tuning on model outputs, providing insights into performance variability and instruction sensitivity. By making the dataset, implementation code, and models publicly available, we establish a robust foundation for future research in Arabic legal NLP. 

**Abstract (ZH)**: 大型语言模型（LLMs）在跨多个领域进行自然语言处理（NLP）方面展现出了非凡的能力。然而，它们在阿拉伯语等低资源语言的法律判决预测（LJP）等专业化任务中的应用仍未得到充分探索。本文通过建立并预处理了来自沙特商业法院判决的阿拉伯语LJP数据集，来弥补这一空白。我们使用了包括LLaMA-3.2-3B和LLaMA-3.1-8B在内的最新开源LLMs，并在零样本、单样本和使用QLoRA微调等不同配置下进行了基准测试。此外，我们采用了一套综合的评估框架，结合定量指标（BLEU和ROUGE）和定性评估（连贯性、法律语言、清晰度）来进行评估。我们的结果显示，在特定任务中，微调后的较小模型可以达到与大型模型相当的性能，同时在资源效率上具有明显优势。此外，我们还研究了提示工程和微调对模型输出的影响，提供了关于性能变异性及指令敏感性的见解。通过公开数据集、实现代码和模型，我们为未来阿拉伯语法律NLP的研究奠定了坚实的基础。 

---
# Boosting Tool Use of Large Language Models via Iterative Reinforced Fine-Tuning 

**Title (ZH)**: 通过迭代强化微调提升大型语言模型的工具使用能力 

**Authors**: Yirong Zeng, Xiao Ding, Yuxian Wang, Weiwen Liu, Wu Ning, Yutai Hou, Xu Huang, Bing Qin, Ting Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.09766)  

**Abstract**: Augmenting large language models (LLMs) with external tools is a promising approach to enhance their capabilities. Effectively leveraging this potential for complex tasks hinges crucially on improving their ability to use tools. Synthesizing tool use data by simulating the real world is an effective approach. Nevertheless, our investigation reveals that training gains significantly decay as the scale of these data increases. The primary factor is the model's poor performance (a.k.a deficiency) in complex scenarios, which hinders learning from data using SFT. Driven by this objective, we propose an iterative reinforced fine-tuning strategy to continually guide the model to alleviate it. Specifically, we first identify deficiency-related data based on feedback from the policy model, then perform a Monte Carlo Tree Search to collect fine-grained preference pairs to pinpoint deficiencies. Subsequently, we update the policy model using preference optimization to align with ground truth and misalign with deficiencies. This process can be iterated. Moreover, before the iteration, we propose an easy-to-hard warm-up SFT strategy to facilitate learning from challenging data. The experiments demonstrate our models go beyond the same parametric models, outperforming many larger open-source and closed-source models. Additionally, it has achieved notable training gains in complex tool use scenarios. 

**Abstract (ZH)**: 将大型语言模型（LLMs）与外部工具结合是一种提升其能力的有前途的方法。有效地利用这一潜力对于复杂任务至关重要，关键在于提高模型使用工具的能力。通过模拟现实世界来合成工具使用数据是一种有效的方法。然而，我们的研究表明，随着这些数据规模的增加，训练收益显著下降。主要因素是模型在复杂场景下的表现不佳（亦称缺陷），这阻碍了通过强化 fine-tuning（SFT）从数据中学习。为实现这一目标，我们提出了一种迭代强化 fine-tuning 策略，持续引导模型来克服这些缺陷。具体而言，我们首先基于策略模型的反馈识别与缺陷相关的数据，然后进行蒙特卡洛树搜索以收集细粒度的偏好对，以定位缺陷。随后，我们使用偏好优化更新策略模型，使其与真实值对齐并远离缺陷。这一过程可以迭代进行。此外，在迭代之前，我们提出了一种从易到难的 warm-up SFT 策略，以利于从具有挑战性的数据中学习。实验表明，我们的模型超越了具有相同参数量的模型，优于许多较大的开源和封闭源模型。此外，它还在复杂工具使用场景中实现了显著的训练收益。 

---
# PaSa: An LLM Agent for Comprehensive Academic Paper Search 

**Title (ZH)**: PaSa：一种全面学术论文搜索的大型语言模型代理 

**Authors**: Yichen He, Guanhua Huang, Peiyuan Feng, Yuan Lin, Yuchen Zhang, Hang Li, Weinan E  

**Link**: [PDF](https://arxiv.org/pdf/2501.10120)  

**Abstract**: We introduce PaSa, an advanced Paper Search agent powered by large language models. PaSa can autonomously make a series of decisions, including invoking search tools, reading papers, and selecting relevant references, to ultimately obtain comprehensive and accurate results for complex scholarly queries. We optimize PaSa using reinforcement learning with a synthetic dataset, AutoScholarQuery, which includes 35k fine-grained academic queries and corresponding papers sourced from top-tier AI conference publications. Additionally, we develop RealScholarQuery, a benchmark collecting real-world academic queries to assess PaSa performance in more realistic scenarios. Despite being trained on synthetic data, PaSa significantly outperforms existing baselines on RealScholarQuery, including Google, Google Scholar, Google with GPT-4 for paraphrased queries, chatGPT (search-enabled GPT-4o), GPT-o1, and PaSa-GPT-4o (PaSa implemented by prompting GPT-4o). Notably, PaSa-7B surpasses the best Google-based baseline, Google with GPT-4o, by 37.78% in recall@20 and 39.90% in recall@50. It also exceeds PaSa-GPT-4o by 30.36% in recall and 4.25% in precision. Model, datasets, and code are available at this https URL. 

**Abstract (ZH)**: 我们介绍了PaSa，这是一种由大规模语言模型驱动的高级论文搜索代理。PaSa可以自主作出一系列决策，包括调用搜索工具、阅读论文和选择相关参考文献，最终为复杂的学术查询提供全面而准确的结果。我们使用强化学习并利用一个合成数据集AutoScholarQuery来优化PaSa，该数据集包含了35,000个精细的学术查询及其相应的论文，这些论文来源于顶级人工智能会议的出版物。此外，我们还开发了RealScholarQuery基准数据集，收集了真实世界的学术查询，以更现实的场景评估PaSa的表现。尽管PaSa是基于合成数据进行训练的，但它在RealScholarQuery上的表现显著优于现有基线，包括Google、Google Scholar、使用GPT-4进行改写的Google、chatGPT（搜索功能增强的GPT-4o）、GPT-o1和PaSa-GPT-4o（基于GPT-4o实现的PaSa）。值得注意的是，PaSa-7B在召回率@20上比基于Google的最佳基线（Google与GPT-4结合）高出37.78%，在召回率@50上高出39.90%。此外，它的召回率超过了PaSa-GPT-4o 30.36%，而精确率高出4.25%。相关模型、数据集和代码可在以下网址获取。 

---
# Conversational Text Extraction with Large Language Models Using Retrieval-Augmented Systems 

**Title (ZH)**: 使用检索增强系统的大语言模型对话文本提取 

**Authors**: Soham Roy, Mitul Goswami, Nisharg Nargund, Suneeta Mohanty, Prasant Kumar Pattnaik  

**Link**: [PDF](https://arxiv.org/pdf/2501.09801)  

**Abstract**: This study introduces a system leveraging Large Language Models (LLMs) to extract text and enhance user interaction with PDF documents via a conversational interface. Utilizing Retrieval-Augmented Generation (RAG), the system provides informative responses to user inquiries while highlighting relevant passages within the PDF. Upon user upload, the system processes the PDF, employing sentence embeddings to create a document-specific vector store. This vector store enables efficient retrieval of pertinent sections in response to user queries. The LLM then engages in a conversational exchange, using the retrieved information to extract text and generate comprehensive, contextually aware answers. While our approach demonstrates competitive ROUGE values compared to existing state-of-the-art techniques for text extraction and summarization, we acknowledge that further qualitative evaluation is necessary to fully assess its effectiveness in real-world applications. The proposed system gives competitive ROUGE values as compared to existing state-of-the-art techniques for text extraction and summarization, thus offering a valuable tool for researchers, students, and anyone seeking to efficiently extract knowledge and gain insights from documents through an intuitive question-answering interface. 

**Abstract (ZH)**: 本研究介绍了一种利用大型语言模型（LLMs）的系统，通过对话界面提取文本并增强用户与PDF文档的交互。该系统利用检索增强生成（RAG）技术，能够对用户的查询提供信息性的回应，并突出显示PDF中的相关段落。用户上传PDF文档后，系统对其进行处理，使用句子嵌入创建特定文档的向量库。该向量库能够在接收到用户查询时高效地检索相关部分。随后，大型语言模型参与对话交流，利用检索到的信息提取文本并生成全面且上下文相关的答案。尽管我们的方法在文本抽取与总结方面与现有的先进技术相比展现了竞争力的ROUGE值，但我们认识到还需要进一步的定性评估来全面评估其在实际应用中的有效性。所提出的系统在文本抽取与总结方面与现有的先进技术相比展示了竞争性的ROUGE值，从而为研究人员、学生以及希望通过直观的问答接口高效地从文档中提取知识和获得洞察的人提供了一个有 value 的工具。 

---
# Towards Preventing Overreliance on Task-Oriented Conversational AI Through Accountability Modeling 

**Title (ZH)**: 通过责任建模预防过度依赖面向任务的对话AI 

**Authors**: Suvodip Dey, Yi-Jyun Sun, Gokhan Tur, Dilek Hakkani-Tur  

**Link**: [PDF](https://arxiv.org/pdf/2501.10316)  

**Abstract**: Recent LLMs have enabled significant advancements for conversational agents. However, they are also well-known to hallucinate, i.e., they often produce responses that seem plausible but are not factually correct. On the other hand, users tend to over-rely on LLM-based AI agents; they accept the AI's suggestion even when it is wrong. Adding good friction, such as explanations or getting user confirmations, has been proposed as a mitigation in AI-supported decision-making systems. In this paper, we propose an accountability model for LLM-based task-oriented dialogue agents to address user overreliance via friction turns in cases of model uncertainty and errors associated with dialogue state tracking (DST). The accountability model is an augmented LLM with an additional accountability head, which functions as a binary classifier to predict the slots of the dialogue states. We perform our experiments with three backbone LLMs (Llama, Mistral, Gemma) on two established task-oriented datasets (MultiWOZ and Snips). Our empirical findings demonstrate that this approach not only enables reliable estimation of AI agent errors but also guides the LLM decoder in generating more accurate actions. We observe around 3% absolute improvement in joint goal accuracy by incorporating accountability heads in modern LLMs for the MultiWOZ dataset. We also show that this method enables the agent to self-correct its actions, further boosting its performance by 3%. Finally, we discuss the application of accountability modeling to prevent user overreliance by introducing friction. 

**Abstract (ZH)**: 近年来，大型语言模型（LLM）为对话代理带来了显著的进步。然而，它们也广为人知地具有自幻象特性，即经常生成看似合理但实际上并不符合事实的响应。另一方面，用户倾向于过度依赖基于LLM的AI代理；即使AI的建议是错误的，他们也往往会接受。加入“摩擦”措施，如解释或获取用户的确认，已被提议用于AI支持的决策系统中以减轻这种依赖。在这篇论文中，我们提出了一个负责制模型，用于解决基于LLM的任务导向对话代理在模型不确定性及对话状态跟踪（DST）相关错误情况下的用户过度依赖问题，通过引入摩擦环节。该负责制模型是一个增强的LLM，额外增加了一个负责制头，其功能作为二元分类器来预测对话状态的槽位。我们在三个骨干LLM（Llama、Mistral、Gemma）上使用了两个现有的任务导向数据集（MultiWOZ和Snips）进行了实验。我们的实证发现表明，这种方法不仅能够有效估计AI代理的错误，还能够引导LLM解码器生成更准确的操作。我们在MultiWOZ数据集上引入负责制头的现代LLM中观察到约3%的绝对改进，使联合目标准确度得以提升。此外，我们还展示了这种方法使代理能够自我纠正其操作，进一步提高了其性能约3%。最后，我们讨论了通过引入摩擦来应用负责制建模以防止用户过度依赖的方法。 

---
# A Survey on Multi-Turn Interaction Capabilities of Large Language Models 

**Title (ZH)**: 大型语言模型多轮交互能力综述 

**Authors**: Chen Zhang, Xinyi Dai, Yaxiong Wu, Qu Yang, Yasheng Wang, Ruiming Tang, Yong Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.09959)  

**Abstract**: Multi-turn interaction in the dialogue system research refers to a system's ability to maintain context across multiple dialogue turns, enabling it to generate coherent and contextually relevant responses. Recent advancements in large language models (LLMs) have significantly expanded the scope of multi-turn interaction, moving beyond chatbots to enable more dynamic agentic interactions with users or environments. In this paper, we provide a focused review of the multi-turn capabilities of LLMs, which are critical for a wide range of downstream applications, including conversational search and recommendation, consultation services, and interactive tutoring. This survey explores four key aspects: (1) the core model capabilities that contribute to effective multi-turn interaction, (2) how multi-turn interaction is evaluated in current practice, (3) the general algorithms used to enhance multi-turn interaction, and (4) potential future directions for research in this field. 

**Abstract (ZH)**: 对话系统中的多轮交互指的是系统能够在多轮对话中维持上下文的能力，使其能够生成连贯且上下文相关的响应。大型语言模型（LLMs）的最新进展极大地扩展了多轮交互的范围，使其超越了聊天机器人，能够与用户或环境进行更加动态的自主交互。在本文中，我们对LLMs的多轮交互能力进行了集中审查，这些能力对于各种下游应用至关重要，包括对话式搜索和推荐、咨询服务以及互动式教学。本文回顾了四个关键方面：（1）构成有效多轮交互的核心模型能力，（2）当前实践中多轮交互的评估方法，（3）用于增强多轮交互的一般算法，以及（4）该领域未来研究方向的潜在可能性。 

---
# Large language models for automated scholarly paper review: A survey 

**Title (ZH)**: 大型语言模型在自动化学术论文评审中的应用：一项综述 

**Authors**: Zhenzhen Zhuang, Jiandong Chen, Hongfeng Xu, Yuwen Jiang, Jialiang Lin  

**Link**: [PDF](https://arxiv.org/pdf/2501.10326)  

**Abstract**: Large language models (LLMs) have significantly impacted human society, influencing various domains. Among them, academia is not simply a domain affected by LLMs, but it is also the pivotal force in the development of LLMs. In academic publications, this phenomenon is represented during the incorporation of LLMs into the peer review mechanism for reviewing manuscripts. We proposed the concept of automated scholarly paper review (ASPR) in our previous paper. As the incorporation grows, it now enters the coexistence phase of ASPR and peer review, which is described in that paper. LLMs hold transformative potential for the full-scale implementation of ASPR, but they also pose new issues and challenges that need to be addressed. In this survey paper, we aim to provide a holistic view of ASPR in the era of LLMs. We begin with a survey to find out which LLMs are used to conduct ASPR. Then, we review what ASPR-related technological bottlenecks have been solved with the incorporation of LLM technology. After that, we move on to explore new methods, new datasets, new source code, and new online systems that come with LLMs for ASPR. Furthermore, we summarize the performance and issues of LLMs in ASPR, and investigate the attitudes and reactions of publishers and academia to ASPR. Lastly, we discuss the challenges associated with the development of LLMs for ASPR. We hope this survey can serve as an inspirational reference for the researchers and promote the progress of ASPR for its actual implementation. 

**Abstract (ZH)**: 大型语言模型（LLMs）对人类社会产生了显著影响，并已渗透到多个领域。在这个过程中，学术界不仅是LLMs影响的对象，而且也是推动LLMs发展的关键力量。在学术出版物中，这种现象体现在LLMs被纳入同行评审机制以审稿 manuscript 的过程中。我们之前提出过自动学术论文评审（ASPR）的概念。随着这一过程的发展，ASPR和传统同行评审机制现已进入了共存阶段，并在我们的论文中进行了详细描述。LLMs为ASPR的大规模实施提供了变革性的潜力，但也带来了一些新问题和挑战，需要加以解决。在这篇综述论文中，我们旨在为LLMs时代下的ASPR提供一个全面的视角。首先，我们进行了一项调研以确定使用哪些LLMs来进行ASPR。然后，我们回顾了通过引入LLM技术已经解决的与ASPR相关的技术瓶颈。接下来，我们将探讨LLMs带给ASPR的新方法、新数据集、新软件代码以及新在线系统。此外，我们总结了LLMs在ASPR中的性能和问题，并调查了出版商和学术界对ASPR的态度和反应。最后，我们讨论了用于ASPR的LLMs发展中所面临的挑战。我们希望这篇综述能够为研究人员提供灵感，并促进ASPR的实际实施进程。 

---
# Computational Protein Science in the Era of Large Language Models (LLMs) 

**Title (ZH)**: 大型语言模型时代下的计算蛋白质科学 

**Authors**: Wenqi Fan, Yi Zhou, Shijie Wang, Yuyao Yan, Hui Liu, Qian Zhao, Le Song, Qing Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.10282)  

**Abstract**: Considering the significance of proteins, computational protein science has always been a critical scientific field, dedicated to revealing knowledge and developing applications within the protein sequence-structure-function paradigm. In the last few decades, Artificial Intelligence (AI) has made significant impacts in computational protein science, leading to notable successes in specific protein modeling tasks. However, those previous AI models still meet limitations, such as the difficulty in comprehending the semantics of protein sequences, and the inability to generalize across a wide range of protein modeling tasks. Recently, LLMs have emerged as a milestone in AI due to their unprecedented language processing & generalization capability. They can promote comprehensive progress in fields rather than solving individual tasks. As a result, researchers have actively introduced LLM techniques in computational protein science, developing protein Language Models (pLMs) that skillfully grasp the foundational knowledge of proteins and can be effectively generalized to solve a diversity of sequence-structure-function reasoning problems. While witnessing prosperous developments, it's necessary to present a systematic overview of computational protein science empowered by LLM techniques. First, we summarize existing pLMs into categories based on their mastered protein knowledge, i.e., underlying sequence patterns, explicit structural and functional information, and external scientific languages. Second, we introduce the utilization and adaptation of pLMs, highlighting their remarkable achievements in promoting protein structure prediction, protein function prediction, and protein design studies. Then, we describe the practical application of pLMs in antibody design, enzyme design, and drug discovery. Finally, we specifically discuss the promising future directions in this fast-growing field. 

**Abstract (ZH)**: 考虑到蛋白质的重要性，计算蛋白质科学一直是一个关键的科学领域，致力于在蛋白质序列-结构-功能范式中揭示知识和开发应用。在过去的几十年中，人工智能（AI）在计算蛋白质科学中产生了重大影响，使得特定蛋白质建模任务取得了显著的成功。然而，之前的AI模型仍然存在一些局限性，如难以理解蛋白质序列的语义，以及无法在广泛的蛋白质建模任务中进行泛化。最近，由于其前所未有的语言处理与泛化能力，大规模语言模型（LLMs）在人工智能领域成为了一个里程碑。它们可以促进各个领域的全面进展，而不仅仅是解决个别任务。因此，研究人员已经积极将LLM技术引入计算蛋白质科学领域，开发出能够熟练掌握蛋白质基础知识的蛋白质语言模型（pLMs），并且能够有效泛化以解决多样的序列-结构-功能推理问题。尽管取得了一系列进展，但是有必要系统地概括LLM技术赋能的计算蛋白质科学的发展。首先，我们根据pLMs掌握的蛋白质知识将其分为类别，包括潜在的序列模式、明确的结构和功能信息以及外部科学语言。其次，我们介绍了pLMs的应用和适应性，突显了它们在促进蛋白质结构预测、蛋白质功能预测和蛋白质设计研究中的显著成就。然后，我们描述了pLMs在抗体设计、酶设计和药物发现中的实际应用。最后，我们特别讨论了这一快速发展的领域中富有前景的未来方向。 

---