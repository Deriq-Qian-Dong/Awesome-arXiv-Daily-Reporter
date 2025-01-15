# A Roadmap to Guide the Integration of LLMs in Hierarchical Planning 

**Title (ZH)**: 指导大型语言模型融入分层规划的路线图 

**Authors**: Israel Puerta-Merino, Carlos Núñez-Molina, Pablo Mesejo, Juan Fernández-Olivares  

**Link**: [PDF](https://arxiv.org/pdf/2501.08068)  

**Abstract**: Recent advances in Large Language Models (LLMs) are fostering their integration into several reasoning-related fields, including Automated Planning (AP). However, their integration into Hierarchical Planning (HP), a subfield of AP that leverages hierarchical knowledge to enhance planning performance, remains largely unexplored. In this preliminary work, we propose a roadmap to address this gap and harness the potential of LLMs for HP. To this end, we present a taxonomy of integration methods, exploring how LLMs can be utilized within the HP life cycle. Additionally, we provide a benchmark with a standardized dataset for evaluating the performance of future LLM-based HP approaches, and present initial results for a state-of-the-art HP planner and LLM planner. As expected, the latter exhibits limited performance (3\% correct plans, and none with a correct hierarchical decomposition) but serves as a valuable baseline for future approaches. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的发展促进了它们在多种推理相关领域的应用，包括自动规划（AP）。然而，将其集成到层次化规划（HP）中，这是AP的一个子领域，主要依赖层次化知识来提高规划性能，这一领域仍基本未被探索。在本初步研究中，我们提出了一条 roadmap，以填补这一空白，并利用LLMs在HP中的潜力。为此，我们提供了一种集成方法的税收分类，探讨了LLMs如何在HP 生命周期中被利用。此外，我们还提供了一个基准测试和标准化数据集，用于评估未来基于LLM的HP方法的性能，并展示了最先进的HP规划器和LLM规划器的初步结果。正如预期的那样，后者在性能方面表现出有限的结果（只有3%的正确计划，且没有一个具有正确层次化分解的），但作为未来方法的基准，这一结果具有重要的参考价值。 

---
# LLM-Ehnanced Holonic Architecture for Ad-Hoc Scalable SoS 

**Title (ZH)**: 增强语言模型的自组织架构以实现即需即用的可扩展系统系（SoS） 

**Authors**: Muhammad Ashfaq, Ahmed R. Sadik, Tommi Mikkonen, Muhammad Waseem, Niko Mäkitalo  

**Link**: [PDF](https://arxiv.org/pdf/2501.07992)  

**Abstract**: As modern system of systems (SoS) become increasingly adaptive and human centred, traditional architectures often struggle to support interoperability, reconfigurability, and effective human system interaction. This paper addresses these challenges by advancing the state of the art holonic architecture for SoS, offering two main contributions to support these adaptive needs. First, we propose a layered architecture for holons, which includes reasoning, communication, and capabilities layers. This design facilitates seamless interoperability among heterogeneous constituent systems by improving data exchange and integration. Second, inspired by principles of intelligent manufacturing, we introduce specialised holons namely, supervisor, planner, task, and resource holons aimed at enhancing the adaptability and reconfigurability of SoS. These specialised holons utilise large language models within their reasoning layers to support decision making and ensure real time adaptability. We demonstrate our approach through a 3D mobility case study focused on smart city transportation, showcasing its potential for managing complex, multimodal SoS environments. Additionally, we propose evaluation methods to assess the architecture efficiency and scalability,laying the groundwork for future empirical validations through simulations and real world implementations. 

**Abstract (ZH)**: 随着现代系统体系（SoS）变得越来越适应人类需求并更加动态化，传统架构往往难以支持互操作性、可重构性和有效的人-系统交互。本文通过推进面向SoS的holonic架构的前沿状态，针对这些挑战提供了两个主要贡献来支持这些适应性需求。首先，我们提出了一种分层的holon架构，包括推理、通信和能力层。这种设计通过改进数据交换和集成来促进异构组成部分系统的无缝互操作性。其次，受智能制造原则的启发，我们引入了特定类型的holon，包括监督者、规划者、任务和资源holon，旨在增强SoS的适应性和可重构性。这些特定的holon在其推理层中利用大规模语言模型来支持决策制定并确保实时适应。我们通过一个3D移动性案例研究，专注于智能城市交通，展示了其在管理复杂多模态SoS环境方面的潜力。此外，我们还提出了评估架构效率和可扩展性的方法，为未来的实证验证奠定了基础，这些验证将通过仿真实验和实际应用来实现。 

---
# Large Language Model Interface for Home Energy Management Systems 

**Title (ZH)**: 面向家庭能源管理系统的大语言模型接口 

**Authors**: François Michelon, Yihong Zhou, Thomas Morstyn  

**Link**: [PDF](https://arxiv.org/pdf/2501.07919)  

**Abstract**: Home Energy Management Systems (HEMSs) help households tailor their electricity usage based on power system signals such as energy prices. This technology helps to reduce energy bills and offers greater demand-side flexibility that supports the power system stability. However, residents who lack a technical background may find it difficult to use HEMSs effectively, because HEMSs require well-formatted parameterization that reflects the characteristics of the energy resources, houses, and users' needs. Recently, Large-Language Models (LLMs) have demonstrated an outstanding ability in language understanding. Motivated by this, we propose an LLM-based interface that interacts with users to understand and parameterize their ``badly-formatted answers'', and then outputs well-formatted parameters to implement an HEMS. We further use Reason and Act method (ReAct) and few-shot prompting to enhance the LLM performance. Evaluating the interface performance requires multiple user--LLM interactions. To avoid the efforts in finding volunteer users and reduce the evaluation time, we additionally propose a method that uses another LLM to simulate users with varying expertise, ranging from knowledgeable to non-technical. By comprehensive evaluation, the proposed LLM-based HEMS interface achieves an average parameter retrieval accuracy of 88\%, outperforming benchmark models without ReAct and/or few-shot prompting. 

**Abstract (ZH)**: 家庭能源管理系统（HEMSs）帮助家庭根据电力系统信号（如电价）来调整其用电行为。这项技术有助于降低能源账单，并提供更高的需求侧灵活性，从而支持电力系统的稳定性。然而，缺乏技术背景的居民可能难以有效使用HEMSs，因为HEMSs需要格式良好的参数化设置，反映出能源资源、房屋和用户需求的特点。最近，大语言模型（LLMs）在语言理解方面展现了卓越的能力。受此启发，我们提出了一种基于LLM的界面，该界面能够与用户互动，理解并参数化用户的“格式不良的答案”，然后输出格式良好的参数以实现HEMS。为进一步增强LLM的性能，我们采用了Reason and Act方法（ReAct）和少量示例提示。评估界面性能需要多次用户-LLM交互。为了避免寻找志愿者用户和减少评估时间，我们还提出了一种方法，使用另一种LLM来模拟具有不同专业知识水平的用户，从熟练的到非技术背景的用户。通过综合评估，所提出的基于LLM的HEMS界面实现了参数检索平均准确率88%，优于没有使用ReAct和/或少量示例提示的标准模型。 

---
# A Driver Advisory System Based on Large Language Model for High-speed Train 

**Title (ZH)**: 基于大型语言模型的高速列车驾驶辅助系统 

**Authors**: Y.C. Luo, J. Xun, W. Wang, R.Z. Zhang, Z.C. Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2501.07837)  

**Abstract**: With the rapid development of China high-speed railway, drivers face increasingly significant technical challenges during operations, such as fault handling. Currently, drivers depend on the onboard mechanic when facing technical issues, for instance, traction loss or sensor faults. This dependency can hinder effective operation, even lead to accidents, while waiting for faults to be addressed. To enhance the accuracy and explainability of actions during fault handling, an Intelligent Driver Advisory System (IDAS) framework based on a large language model (LLM) named IDAS-LLM, is introduced. Initially, domain-fine-tuning of the LLM is performed using a constructed railway knowledge question-and-answer dataset to improve answer accuracy in railway-related questions. Subsequently, integration of the Retrieval-augmented Generation (RAG) architecture is pursued for system design to enhance the explainability of generated responses. Comparative experiments are conducted using the constructed railway driving knowledge assessment dataset. Results indicate that domain-fine-tuned LLMs show an improvement in answer accuracy by an average of 10%, outperforming some current mainstream LLMs. Additionally, the inclusion of the RAG framework increases the average recall rate of question-and-answer sessions by about 4%. Finally, the fault handling capability of IDAS-LLM is demonstrated through simulations of real operational scenarios, proving that the proposed framework has practical application prospects. 

**Abstract (ZH)**: 随着中国高速铁路的快速发展，列车司机在运营过程中面临的技術挑战越来越显著，如故障处理等。目前，面对技术问题时，司机依赖车辆机械师，例如牵引力损失或传感器故障。这种依赖在故障处理过程中可能导致操作效率低下，甚至可能引发事故。为了提高故障处理过程中操作的准确性和可解释性，本文提出了一个基于大型语言模型（LLM）的智能司机辅助系统（IDAS）框架，该框架命名为IDAS-LLM。首先，通过使用构建的铁路知识问答数据集对LLM进行领域微调，以提高铁路相关问题回答的准确性。随后，通过结合检索增强生成（RAG）架构来优化系统设计，以增强生成响应的可解释性。通过使用构建的铁路驾驶知识评估数据集进行对比实验。结果表明，领域微调后的LLM在回答准确性方面平均提高了10%，超过了当前一些主流LLM。此外，引入RAG框架使得问答会话的平均召回率提高了约4%。最后，通过模拟实际运营场景展示了IDAS-LLM的故障处理能力，证明该提出的框架具有实际应用的前景。 

---
# Agent-Centric Projection of Prompting Techniques and Implications for Synthetic Training Data for Large Language Models 

**Title (ZH)**: 基于代理的提示技术投影及对大规模语言模型合成训练数据的影响 

**Authors**: Dhruv Dhamani, Mary Lou Maher  

**Link**: [PDF](https://arxiv.org/pdf/2501.07815)  

**Abstract**: Recent advances in prompting techniques and multi-agent systems for Large Language Models (LLMs) have produced increasingly complex approaches. However, we lack a framework for characterizing and comparing prompting techniques or understanding their relationship to multi-agent LLM systems. This position paper introduces and explains the concepts of linear contexts (a single, continuous sequence of interactions) and non-linear contexts (branching or multi-path) in LLM systems. These concepts enable the development of an agent-centric projection of prompting techniques, a framework that can reveal deep connections between prompting strategies and multi-agent systems. We propose three conjectures based on this framework: (1) results from non-linear prompting techniques can predict outcomes in equivalent multi-agent systems, (2) multi-agent system architectures can be replicated through single-LLM prompting techniques that simulate equivalent interaction patterns, and (3) these equivalences suggest novel approaches for generating synthetic training data. We argue that this perspective enables systematic cross-pollination of research findings between prompting and multi-agent domains, while providing new directions for improving both the design and training of future LLM systems. 

**Abstract (ZH)**: 近年来，针对大型语言模型（LLM）的提示技术与多agent系统方面取得了显著进展，产生了日益复杂的方法。然而，我们缺乏一种框架来表征和比较提示技术，或理解它们与多agent LLM系统之间的关系。本文观点引入并解释了线性上下文（单一、连续的互动序列）和非线性上下文（分支或多路径）的概念在LLM系统中的意义。这些概念使得能够从agent为中心的角度构建提示技术的投影框架，该框架可以揭示提示策略与多agent系统之间的深层次联系。基于这一框架，我们提出了三条假设：（1）非线性提示技术的结果可以预测等效多agent系统的成果；（2）多agent系统架构可以通过模拟等效互动模式的单一LLM提示技术进行复制；（3）这些等效性提出了生成合成训练数据的新型方法。我们认为，这一视角促进了提示技术与多agent领域研究发现的系统性交叉影响，同时还为改进未来LLM系统的设计和训练提供了新的方向。 

---
# Large Language Models for Interpretable Mental Health Diagnosis 

**Title (ZH)**: 可解释的心理健康诊断中的大规模语言模型 

**Authors**: Brian Hyeongseok Kim, Chao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.07653)  

**Abstract**: We propose a clinical decision support system (CDSS) for mental health diagnosis that combines the strengths of large language models (LLMs) and constraint logic programming (CLP). Having a CDSS is important because of the high complexity of diagnostic manuals used by mental health professionals and the danger of diagnostic errors. Our CDSS is a software tool that uses an LLM to translate diagnostic manuals to a logic program and solves the program using an off-the-shelf CLP engine to query a patient's diagnosis based on the encoded rules and provided data. By giving domain experts the opportunity to inspect the LLM-generated logic program, and making modifications when needed, our CDSS ensures that the diagnosis is not only accurate but also interpretable. We experimentally compare it with two baseline approaches of using LLMs: diagnosing patients using the LLM-only approach, and using the LLM-generated logic program but without expert inspection. The results show that, while LLMs are extremely useful in generating candidate logic programs, these programs still require expert inspection and modification to guarantee faithfulness to the official diagnostic manuals. Additionally, ethical concerns arise from the direct use of patient data in LLMs, underscoring the need for a safer hybrid approach like our proposed method. 

**Abstract (ZH)**: 我们提出了一种结合大型语言模型（LLMs）和约束逻辑编程（CLP）优势的心理健康诊断临床决策支持系统（CDSS）。开发CDSS的重要性在于，心理健康专业人员使用的诊断手册具有极高的复杂性，诊断错误存在潜在风险。我们的CDSS是一种软件工具，它使用LLM将诊断手册翻译成逻辑程序，并使用现成的CLP引擎查询患者的诊断结果，基于编码规则和提供的数据。通过让领域专家检查LLM生成的逻辑程序，并在必要时进行修改，我们的CDSS确保诊断既准确又可解释。我们实验性地将CDSS与两种基于LLM的基本方法进行了比较：仅使用LLM进行患者诊断的方法，以及使用LLM生成的逻辑程序但未经专家检查的方法。实验结果表明，尽管LLM在生成候选逻辑程序方面非常有用，但这些程序仍然需要专家的检查和修改，才能确保与官方诊断手册的一致性。此外，直接在LLM中使用患者数据引发了一些伦理问题，突显了需要一种更安全的混合方法，如我们提出的方法。 

---
# SafePowerGraph-LLM: Novel Power Grid Graph Embedding and Optimization with Large Language Models 

**Title (ZH)**: SafePowerGraph-LLM：基于大规模语言模型的新颖电力网络图嵌入与优化方法 

**Authors**: Fabien Bernier, Jun Cao, Maxime Cordy, Salah Ghamizi  

**Link**: [PDF](https://arxiv.org/pdf/2501.07639)  

**Abstract**: Efficiently solving Optimal Power Flow (OPF) problems in power systems is crucial for operational planning and grid management. There is a growing need for scalable algorithms capable of handling the increasing variability, constraints, and uncertainties in modern power networks while providing accurate and fast solutions. To address this, machine learning techniques, particularly Graph Neural Networks (GNNs) have emerged as promising approaches. This letter introduces SafePowerGraph-LLM, the first framework explicitly designed for solving OPF problems using Large Language Models (LLM)s. The proposed approach combines graph and tabular representations of power grids to effectively query LLMs, capturing the complex relationships and constraints in power systems. A new implementation of in-context learning and fine-tuning protocols for LLMs is introduced, tailored specifically for the OPF problem. SafePowerGraph-LLM demonstrates reliable performances using off-the-shelf LLM. Our study reveals the impact of LLM architecture, size, and fine-tuning and demonstrates our framework's ability to handle realistic grid components and constraints. 

**Abstract (ZH)**: 在电力系统中高效解决问题最优功率流（OPF）对于运行计划和电网管理至关重要。随着现代电力网络中可变性、约束和不确定性不断增加，对能够处理这些增强的可扩展算法的需求也在增长。为此，机器学习技术，特别是图神经网络（GNNs），已经被证明是颇具前景的方法。本文介绍了SafePowerGraph-LLM，这是第一个专门为利用大型语言模型（LLMs）解决OPF问题设计的框架。提出的这种方法将电力网络的图表示和表格表示结合起来，以便有效地查询LLMs，捕捉电力系统中的复杂关系和约束条件。我们提出了针对OPF问题的新颖的上下文学习和微调协议实现。SafePowerGraph-LLM 在使用即用型大型语言模型的情况下展示了可靠的性能。我们的研究揭示了LLM架构、大小和微调的影响，并展示了我们框架处理现实电网组件和约束的能力。 

---
# PokerBench: Training Large Language Models to become Professional Poker Players 

**Title (ZH)**: PokerBench: 训练大型语言模型成为职业筹码争夺者

注释：在学术翻译中，为了使术语更加准确和符合专业惯例，将“Professional Poker Players”翻译为“职业筹码争夺者”。这是因为，在扑克职业领域，“Professional Poker Player”通常指的是专业扑克玩家，而“Professional”在特定的扑克语境中更强调其获得收益的能力。而“筹码争夺者”在中文语境下，更加形象地表达了“Poker Player”在扑克比赛中追求胜利和筹码积累的含义。 

**Authors**: Richard Zhuang, Akshat Gupta, Richard Yang, Aniket Rahane, Zhengyu Li, Gopala Anumanchipalli  

**Link**: [PDF](https://arxiv.org/pdf/2501.08328)  

**Abstract**: We introduce PokerBench - a benchmark for evaluating the poker-playing abilities of large language models (LLMs). As LLMs excel in traditional NLP tasks, their application to complex, strategic games like poker poses a new challenge. Poker, an incomplete information game, demands a multitude of skills such as mathematics, reasoning, planning, strategy, and a deep understanding of game theory and human psychology. This makes Poker the ideal next frontier for large language models. PokerBench consists of a comprehensive compilation of 11,000 most important scenarios, split between pre-flop and post-flop play, developed in collaboration with trained poker players. We evaluate prominent models including GPT-4, ChatGPT 3.5, and various Llama and Gemma series models, finding that all state-of-the-art LLMs underperform in playing optimal poker. However, after fine-tuning, these models show marked improvements. We validate PokerBench by having models with different scores compete with each other, demonstrating that higher scores on PokerBench lead to higher win rates in actual poker games. Through gameplay between our fine-tuned model and GPT-4, we also identify limitations of simple supervised fine-tuning for learning optimal playing strategy, suggesting the need for more advanced methodologies for effectively training language models to excel in games. PokerBench thus presents a unique benchmark for a quick and reliable evaluation of the poker-playing ability of LLMs as well as a comprehensive benchmark to study the progress of LLMs in complex game-playing scenarios. The dataset and code will be made available at: \url{this https URL}. 

**Abstract (ZH)**: 我们介绍了PokerBench——一个用于评估大型语言模型（LLMs）在扑克游戏中的能力的标准工具。作为传统NLP任务中的强者，LLMs在复杂的战略性游戏中，如扑克，的运用提出了新的挑战。扑克是一种不完整信息的游戏，需要多种技能，包括数学、推理、规划、策略和对博弈论及人类心理学的深刻理解。这使得扑克成为大型语言模型的下一个理想挑战领域。PokerBench包括11,000个最重要的场景综合，这些场景被分为摊前和摊后策略开发，并与训练有素的扑克玩家进行了合作。

我们评估了包括GPT-4、ChatGPT 3.5以及各种Llama和Gemma系列模型在内的知名模型，发现所有最先进的LLMs在玩最优扑克时都表现不佳。然而，在进行微调后，这些模型显示出明显的改进。我们通过让不同评分的模型相互竞争，验证了PokerBench，表明PokerBench上的较高分数会在实际扑克游戏中带来更高的胜率。通过我们的微调模型与GPT-4的对局，我们也发现简单的监督微调方法在学习最优策略方面存在局限性，强调了需要更高级的方法来有效训练语言模型以在游戏场景中表现出色。因此，PokerBench为快速可靠地评估LLMs在扑克中的能力提供了一个独特的基准，并为研究LLMs在复杂游戏场景中的进步提供了一个全面的基准。该数据集和代码将在此处获得：\url{this https URL}。 

---
# HALoGEN: Fantastic LLM Hallucinations and Where to Find Them 

**Title (ZH)**: HALoGEN：卓越的大语言模型幻觉及其来源探索 

**Authors**: Abhilasha Ravichander, Shrusti Ghela, David Wadden, Yejin Choi  

**Link**: [PDF](https://arxiv.org/pdf/2501.08292)  

**Abstract**: Despite their impressive ability to generate high-quality and fluent text, generative large language models (LLMs) also produce hallucinations: statements that are misaligned with established world knowledge or provided input context. However, measuring hallucination can be challenging, as having humans verify model generations on-the-fly is both expensive and time-consuming. In this work, we release HALoGEN, a comprehensive hallucination benchmark consisting of: (1) 10,923 prompts for generative models spanning nine domains including programming, scientific attribution, and summarization, and (2) automatic high-precision verifiers for each use case that decompose LLM generations into atomic units, and verify each unit against a high-quality knowledge source. We use this framework to evaluate ~150,000 generations from 14 language models, finding that even the best-performing models are riddled with hallucinations (sometimes up to 86% of generated atomic facts depending on the domain). We further define a novel error classification for LLM hallucinations based on whether they likely stem from incorrect recollection of training data (Type A errors), or incorrect knowledge in training data (Type B errors), or are fabrication (Type C errors). We hope our framework provides a foundation to enable the principled study of why generative models hallucinate, and advances the development of trustworthy large language models. 

**Abstract (ZH)**: 尽管生成型大型语言模型（LLMs）具有生成高质量流畅文本的强大能力，但它们也会产生幻觉：即模型生成的陈述与现有的世界知识或提供的上下文不一致。然而，衡量这些幻觉是具有挑战性的，因为让人类实时验证模型生成的内容既昂贵又耗时。在本研究中，我们发布了HALoGEN，这是一个综合性的幻觉基准，包括：（1）涵盖编程、科学引证和总结等九个领域的10,923个用于生成模型的提示；（2）针对每种应用场景提供自动的高精度验证器，将LLM生成的内容分解为原子单元，并使用高质量的知识来源验证每个单元。我们使用该框架评估了来自14个语言模型的约150,000个生成内容，发现即使表现最好的模型也充满了幻觉（有时在某些领域中，幻觉比例高达86%）。此外，我们还定义了一种新的错误分类方法，即根据幻觉是否源自训练数据的错误记忆（类型A错误）、训练数据中的错误知识（类型B错误）或虚构（类型C错误）来分类。我们希望这项框架能够为科学地研究生成模型为什么会产生幻觉提供基础，并促进可信的大规模语言模型的发展。 

---
# Eliciting In-context Retrieval and Reasoning for Long-context Large Language Models 

**Title (ZH)**: 在长上下文环境中引导基于情境检索与推理的大语言模型 

**Authors**: Yifu Qiu, Varun Embar, Yizhe Zhang, Navdeep Jaitly, Shay B. Cohen, Benjamin Han  

**Link**: [PDF](https://arxiv.org/pdf/2501.08248)  

**Abstract**: Recent advancements in long-context language models (LCLMs) promise to transform Retrieval-Augmented Generation (RAG) by simplifying pipelines. With their expanded context windows, LCLMs can process entire knowledge bases and perform retrieval and reasoning directly -- a capability we define as In-Context Retrieval and Reasoning (ICR^2). However, existing benchmarks like LOFT often overestimate LCLM performance by providing overly simplified contexts. To address this, we introduce ICR^2, a benchmark that evaluates LCLMs in more realistic scenarios by including confounding passages retrieved with strong retrievers. We then propose three methods to enhance LCLM performance: (1) retrieve-then-generate fine-tuning, (2) retrieval-attention-probing, which uses attention heads to filter and de-noise long contexts during decoding, and (3) joint retrieval head training alongside the generation head. Our evaluation of five well-known LCLMs on LOFT and ICR^2 demonstrates significant gains with our best approach applied to Mistral-7B: +17 and +15 points by Exact Match on LOFT, and +13 and +2 points on ICR^2, compared to vanilla RAG and supervised fine-tuning, respectively. It even outperforms GPT-4-Turbo on most tasks despite being a much smaller model. 

**Abstract (ZH)**: 近年来，长上下文语言模型（LCLMs）的进步有望通过简化管道来改造检索增强生成（RAG）系统。借助扩展的上下文窗口，LCLMs能够处理整个知识库，并直接进行检索和推理——我们将其定义为上下文检索与推理（ICR^2）的能力。然而，现有的基准测试，例如LOFT，往往由于提供了过于简化的上下文而高估了LCLM的表现。为了解决这一问题，我们引入了ICR^2，这是一个基准测试，它通过包含使用强大检索器检索的干扰段落，在更现实的场景中评估LCLMs的表现。接着，我们提出了三种方法来提升LCLM的表现：(1) 检索-生成微调方法；(2) 检索-注意-探查，这种方法利用注意头在解码过程中筛选和去噪长上下文；(3) 结合生成头部和检索头部的联合训练。我们对LOFT和ICR^2的五个知名LCLMs进行的评估表明，在我们的最佳方法应用于Mistral-7B模型时，与传统的RAG和监督微调相比，在LOFT上的精确匹配分数分别提高了17和15个点，在ICR^2上的分数分别提高了13和2个点。即使与较小的模型GPT-4-Turbo相比，Mistral-7B也表现出色，不过在许多任务中仍然取得了更好的表现。 

---
# ASTRID -- An Automated and Scalable TRIaD for the Evaluation of RAG-based Clinical Question Answering Systems 

**Title (ZH)**: ASTRID —— 一种自动化且可扩展的 TRIaD，用于评估基于RAG的临床问答系统 

**Authors**: Mohita Chowdhury, Yajie Vera He, Aisling Higham, Ernest Lim  

**Link**: [PDF](https://arxiv.org/pdf/2501.08208)  

**Abstract**: Large Language Models (LLMs) have shown impressive potential in clinical question answering (QA), with Retrieval Augmented Generation (RAG) emerging as a leading approach for ensuring the factual accuracy of model responses. However, current automated RAG metrics perform poorly in clinical and conversational use cases. Using clinical human evaluations of responses is expensive, unscalable, and not conducive to the continuous iterative development of RAG systems. To address these challenges, we introduce ASTRID - an Automated and Scalable TRIaD for evaluating clinical QA systems leveraging RAG - consisting of three metrics: Context Relevance (CR), Refusal Accuracy (RA), and Conversational Faithfulness (CF). Our novel evaluation metric, CF, is designed to better capture the faithfulness of a model's response to the knowledge base without penalising conversational elements. To validate our triad, we curate a dataset of over 200 real-world patient questions posed to an LLM-based QA agent during surgical follow-up for cataract surgery - the highest volume operation in the world - augmented with clinician-selected questions for emergency, clinical, and non-clinical out-of-domain scenarios. We demonstrate that CF can predict human ratings of faithfulness better than existing definitions for conversational use cases. Furthermore, we show that evaluation using our triad consisting of CF, RA, and CR exhibits alignment with clinician assessment for inappropriate, harmful, or unhelpful responses. Finally, using nine different LLMs, we demonstrate that the three metrics can closely agree with human evaluations, highlighting the potential of these metrics for use in LLM-driven automated evaluation pipelines. We also publish the prompts and datasets for these experiments, providing valuable resources for further research and development. 

**Abstract (ZH)**: 大型语言模型（LLMs）在临床问答（QA）方面展现了令人印象深刻的潜力，检索增强生成（RAG）方法因其确保模型响应事实准确性的能力而成为领先的方法。然而，现有的自动化RAG评估指标在临床和对话场景中表现不佳。目前，使用临床人工评估响应成本高、无法扩展，也不利于RAG系统的持续迭代开发。为解决这些挑战，我们提出了一种名为ASTRID的自动化和可扩展的RAG评估框架，以评估利用RAG的临床QA系统，该框架包含三个指标：上下文相关性（CR）、拒绝准确性（RA）和对话一致性（CF）。我们提出的新型评估指标CF旨在更好地捕捉模型响应与知识库的一致性，而不惩罚对话元素。为了验证这一指标框架，我们编译了一个包含200多个真实世界患者问题的数据集，这些问题是在进行白内障手术术后随访时提出给基于LLM的QA代理的，其中还包括临床专家精选的问题，以涵盖急诊、临床和非临床领域。我们证明，CF能够比现有定义更好地预测对话场景中的人类一致性评级。此外，我们展示了使用包含CF、RA和CR的三重评估框架与临床评估的一致性，尤其是在不适当、有害或无用的响应方面。最后，我们使用九种不同的LLM进行测试，证明这三个指标与人类评估结果高度一致，突显了这些指标在基于LLM的自动评估管道中的应用潜力。我们还发布了这些实验的提示和数据集，为进一步的研究和开发提供了宝贵的资源。 

---
# Potential and Perils of Large Language Models as Judges of Unstructured Textual Data 

**Title (ZH)**: 大型语言模型作为无结构文本数据裁判的潜力与风险 

**Authors**: Rewina Bedemariam, Natalie Perez, Sreyoshi Bhaduri, Satya Kapoor, Alex Gil, Elizabeth Conjar, Ikkei Itoku, David Theil, Aman Chadha, Naumaan Nayyar  

**Link**: [PDF](https://arxiv.org/pdf/2501.08167)  

**Abstract**: Rapid advancements in large language models have unlocked remarkable capabilities when it comes to processing and summarizing unstructured text data. This has implications for the analysis of rich, open-ended datasets, such as survey responses, where LLMs hold the promise of efficiently distilling key themes and sentiments. However, as organizations increasingly turn to these powerful AI systems to make sense of textual feedback, a critical question arises, can we trust LLMs to accurately represent the perspectives contained within these text based datasets? While LLMs excel at generating human-like summaries, there is a risk that their outputs may inadvertently diverge from the true substance of the original responses. Discrepancies between the LLM-generated outputs and the actual themes present in the data could lead to flawed decision-making, with far-reaching consequences for organizations. This research investigates the effectiveness of LLMs as judge models to evaluate the thematic alignment of summaries generated by other LLMs. We utilized an Anthropic Claude model to generate thematic summaries from open-ended survey responses, with Amazon's Titan Express, Nova Pro, and Meta's Llama serving as LLM judges. The LLM-as-judge approach was compared to human evaluations using Cohen's kappa, Spearman's rho, and Krippendorff's alpha, validating a scalable alternative to traditional human centric evaluation methods. Our findings reveal that while LLMs as judges offer a scalable solution comparable to human raters, humans may still excel at detecting subtle, context-specific nuances. This research contributes to the growing body of knowledge on AI assisted text analysis. We discuss limitations and provide recommendations for future research, emphasizing the need for careful consideration when generalizing LLM judge models across various contexts and use cases. 

**Abstract (ZH)**: 大规模语言模型的迅速发展解锁了处理和总结非结构化文本数据的惊人能力。这为分析丰富且开放式数据集（如调查回复）带来了重要影响，L大型语言模型（LLMs）有望高效地提炼关键主题和情绪。然而，随着组织越来越多地利用这些强大的人工智能系统来理解文本反馈，一个关键问题应运而生：我们能否信任LLMs准确地代表这些文本数据集中的视角？尽管LLMs在生成人类般自然的摘要方面表现出色，但它们的输出可能存在无意中的偏差，偏离原始回应的真实内容。LLMs生成的输出与实际数据主题之间的差异可能导致决策失误，对组织产生深远影响。本研究调查了LLMs作为评判模型评估由其他LLMs生成的摘要主题一致性的有效性。我们使用Anthropic的Claude模型从开放式调查回复中生成主题摘要，并使用Amazon的Titan Express、Nova Pro和Meta的Llama作为LLMs评判者。LLM评判者的方法与使用科恩κ、斯皮尔曼ρ和克里彭多夫α进行的人类评估进行了比较，验证了一种可扩展的人性化评估方法的替代方案。我们的研究发现，尽管作为评判者的LLMs提供了与人类评分者相比可扩展的解决方案，但人类评分者仍可能在检测细微的、情境特定的差异方面更为出色。本研究为AI辅助文本分析领域提供了更多信息。我们讨论了限制并提供了未来研究的建议，强调在不同背景和应用场景下一般化LLM评判模型时需要谨慎考虑。 

---
# I Can Find You in Seconds! Leveraging Large Language Models for Code Authorship Attribution 

**Title (ZH)**: 我可以在秒内找到你！利用大规模语言模型进行代码作者ship归属分析 

**Authors**: Soohyeon Choi, Yong Kiam Tan, Mark Huasong Meng, Mohamed Ragab, Soumik Mondal, David Mohaisen, Khin Mi Mi Aung  

**Link**: [PDF](https://arxiv.org/pdf/2501.08165)  

**Abstract**: Source code authorship attribution is important in software forensics, plagiarism detection, and protecting software patch integrity. Existing techniques often rely on supervised machine learning, which struggles with generalization across different programming languages and coding styles due to the need for large labeled datasets. Inspired by recent advances in natural language authorship analysis using large language models (LLMs), which have shown exceptional performance without task-specific tuning, this paper explores the use of LLMs for source code authorship attribution.
We present a comprehensive study demonstrating that state-of-the-art LLMs can successfully attribute source code authorship across different languages. LLMs can determine whether two code snippets are written by the same author with zero-shot prompting, achieving a Matthews Correlation Coefficient (MCC) of 0.78, and can attribute code authorship from a small set of reference code snippets via few-shot learning, achieving MCC of 0.77. Additionally, LLMs show some adversarial robustness against misattribution attacks.
Despite these capabilities, we found that naive prompting of LLMs does not scale well with a large number of authors due to input token limitations. To address this, we propose a tournament-style approach for large-scale attribution. Evaluating this approach on datasets of C++ (500 authors, 26,355 samples) and Java (686 authors, 55,267 samples) code from GitHub, we achieve classification accuracy of up to 65% for C++ and 68.7% for Java using only one reference per author. These results open new possibilities for applying LLMs to code authorship attribution in cybersecurity and software engineering. 

**Abstract (ZH)**: 源代码作者归属在软件取证、剽窃检测和保护软件补丁完整性方面具有重要意义。现有的技术方法通常依赖监督机器学习，但在不同编程语言和编程风格之间泛化时往往会遇到困难，因为需要大量标记的数据集。受近期大型语言模型（LLMs）在自然语言作者归属分析中表现出色且无需特定任务微调的进展启发，本文探索了使用LLMs进行源代码作者归属的方法。

我们进行了全面的研究，证明了最先进的LLMs能够成功地在不同编程语言之间进行源代码作者归属。LLMs可以通过零样本提示判断两个代码片段是否由同一个作者编写，达到了0.78的Matthews相关系数（MCC），并通过少量样本学习将代码作者归属从一小部分参考代码片段中进行分类，达到了0.77的MCC。此外，LLMs还表现出一定程度的对抗鲁棒性，能够抵御误归属攻击。

尽管具有这些能力，我们发现简单的LLMs提示方法在大量作者的情况下无法很好地扩展，这主要是由于输入标记的限制。为了解决这个问题，我们提出了一种锦标赛式的方法来实现大范围的归属。在来自GitHub的C++（500位作者，26,355个样本）和Java（686位作者，55,267个样本）代码的数据集上进行评估，通过每个作者仅使用一个参考代码片段，实现了高达65%的C++分类准确率和68.7%的Java分类准确率。这些结果为在网络安全和软件工程中应用LLMs进行代码作者归属提供了新的可能性。 

---
# Consistency of Responses and Continuations Generated by Large Language Models on Social Media 

**Title (ZH)**: 大型语言模型在社交媒体上生成的回答和续写的一致性 

**Authors**: Wenlu Fan, Yuqi Zhu, Chenyang Wang, Bin Wang, Wentao Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.08102)  

**Abstract**: Large Language Models (LLMs) demonstrate remarkable capabilities in text generation, yet their emotional consistency and semantic coherence in social media contexts remain insufficiently understood. This study investigates how LLMs handle emotional content and maintain semantic relationships through continuation and response tasks using two open-source models: Gemma and Llama. By analyzing climate change discussions from Twitter and Reddit, we examine emotional transitions, intensity patterns, and semantic similarity between human-authored and LLM-generated content. Our findings reveal that while both models maintain high semantic coherence, they exhibit distinct emotional patterns: Gemma shows a tendency toward negative emotion amplification, particularly anger, while maintaining certain positive emotions like optimism. Llama demonstrates superior emotional preservation across a broader spectrum of affects. Both models systematically generate responses with attenuated emotional intensity compared to human-authored content and show a bias toward positive emotions in response tasks. Additionally, both models maintain strong semantic similarity with original texts, though performance varies between continuation and response tasks. These findings provide insights into LLMs' emotional and semantic processing capabilities, with implications for their deployment in social media contexts and human-AI interaction design. 

**Abstract (ZH)**: 大型语言模型（LLMs）在文本生成方面表现出显著的能力，但在社交媒体情境下情感一致性和语义连贯性方面仍然缺乏足够理解。本研究通过使用两个开源模型Gemma和Llama，利用Twitter和Reddit上的气候变化讨论数据，探讨LLMs如何处理情感内容并维持语义关系。我们通过续写和回应任务来分析人类和模型生成的内容间的情感转换、情感强度模式及语义相似性。研究发现，尽管两种模型都保持了较高的语义连贯性，但它们在情感模式上表现出不同的特点：Gemma倾向于放大负面情感，尤其是愤怒，同时保持一定比例的正面情感，如乐观；而Llama则在更广泛的范围内表现出优越的情感保留能力。两种模型系统性地生成的情感强度较低的回应内容，并且在回应任务中倾向于积极情感。此外，两种模型在续写和回应任务中都保持了与原始文本较强的语义相似性，但任务表现存在差异。这些发现揭示了LLMs的情感和语义处理能力，对于其在社交媒体情境中的应用和人机交互设计具有重要启示。 

---
# Leveraging Metamemory Mechanisms for Enhanced Data-Free Code Generation in LLMs 

**Title (ZH)**: 利用元记忆机制增强LLM中的无数据代码生成 

**Authors**: Shuai Wang, Liang Ding, Yibing Zhan, Yong Luo, Zheng He, Dapeng Tao  

**Link**: [PDF](https://arxiv.org/pdf/2501.07892)  

**Abstract**: Automated code generation using large language models (LLMs) has gained attention due to its efficiency and adaptability. However, real-world coding tasks or benchmarks like HumanEval and StudentEval often lack dedicated training datasets, challenging existing few-shot prompting approaches that rely on reference examples. Inspired by human metamemory-a cognitive process involving recall and evaluation-we present a novel framework (namely M^2WF) for improving LLMs' one-time code generation. This approach enables LLMs to autonomously generate, evaluate, and utilize synthetic examples to enhance reliability and performance. Unlike prior methods, it minimizes dependency on curated data and adapts flexibly to various coding scenarios. Our experiments demonstrate significant improvements in coding benchmarks, offering a scalable and robust solution for data-free environments. The code and framework will be publicly available on GitHub and HuggingFace. 

**Abstract (ZH)**: 使用大型语言模型（LLMs）自动进行代码生成由于其高效性和适应性而引起了关注。然而，现实世界的编码任务或基准，如HumanEval和StudentEval，往往缺乏专门训练的数据集，这挑战了依赖参考示例的现有少量示例提示方法。受到人类元记忆——一种涉及回忆和评估的认知过程——的启发，我们提出了一种新的框架（称为M^2WF），以提高LLMs的一次性代码生成能力。该方法使LLMs能够自主生成、评估和利用合成示例，以增强可靠性和性能。与先前的方法不同，它最大限度地减少了对精心策划数据的依赖，并能够灵活适应各种编码场景。我们的实验结果显示在编码基准上取得了显著的改进，提供了一种适用于数据匮乏环境的可扩展和稳健的解决方案。该代码和框架将在GitHub和HuggingFace上公开提供。 

---
# Hierarchical Repository-Level Code Summarization for Business Applications Using Local LLMs 

**Title (ZH)**: 使用本地LLM进行商业应用的分层仓库级别代码摘要 

**Authors**: Nilesh Dhulshette, Sapan Shah, Vinay Kulkarni  

**Link**: [PDF](https://arxiv.org/pdf/2501.07857)  

**Abstract**: In large-scale software development, understanding the functionality and intent behind complex codebases is critical for effective development and maintenance. While code summarization has been widely studied, existing methods primarily focus on smaller code units, such as functions, and struggle with larger code artifacts like files and packages. Additionally, current summarization models tend to emphasize low-level implementation details, often overlooking the domain and business context that are crucial for real-world applications. This paper proposes a two-step hierarchical approach for repository-level code summarization, tailored to business applications. First, smaller code units such as functions and variables are identified using syntax analysis and summarized with local LLMs. These summaries are then aggregated to generate higher-level file and package summaries. To ensure the summaries are grounded in business context, we design custom prompts that capture the intended purpose of code artifacts based on the domain and problem context of the business application. We evaluate our approach on a business support system (BSS) for the telecommunications domain, showing that syntax analysis-based hierarchical summarization improves coverage, while business-context grounding enhances the relevance of the generated summaries. 

**Abstract (ZH)**: 在大规模软件开发中，理解复杂代码库的功能和意图对于有效的开发和维护至关重要。虽然代码总结已经得到了广泛的研究，但现有方法主要关注较小的代码单元，如函数，并在处理文件和包这样的较大代码构件时遇到困难。此外，当前的总结模型往往强调低级别的实现细节，而忽视了真实世界应用中至关重要的领域和业务上下文。本文提出了一种针对商业应用的两阶段层次化代码库总结方法。首先，通过语法分析识别较小的代码单元（如函数和变量），并使用局部语言模型（LLM）对其进行总结。这些摘要随后被聚合，以生成较高层次的文件和包摘要。为了确保摘要是基于业务上下文的，我们设计了定制的提示，根据业务应用的领域和问题上下文来捕获代码构件的预期目的。我们在电信领域的业务支持系统（BSS）上评估了我们的方法，结果表明，基于语法分析的层次化总结可以提高覆盖范围，而基于业务上下文的上下文约束则增强了生成摘要的相关性。 

---
# Real-time Verification and Refinement of Language Model Text Generation 

**Title (ZH)**: 实时验证和细化语言模型文本生成 

**Authors**: Joonho Ko, Jinheon Baek, Sung Ju Hwang  

**Link**: [PDF](https://arxiv.org/pdf/2501.07824)  

**Abstract**: Large language models (LLMs) have shown remarkable performance across a wide range of natural language tasks. However, a critical challenge remains in that they sometimes generate factually incorrect answers. To address this, while many previous work has focused on identifying errors in their generation and further refining them, they are slow in deployment since they are designed to verify the response from LLMs only after their entire generation (from the first to last tokens) is done. Further, we observe that once LLMs generate incorrect tokens early on, there is a higher likelihood that subsequent tokens will also be factually incorrect. To this end, in this work, we propose Streaming-VR (Streaming Verification and Refinement), a novel approach designed to enhance the efficiency of verification and refinement of LLM outputs. Specifically, the proposed Streaming-VR enables on-the-fly verification and correction of tokens as they are being generated, similar to a streaming process, ensuring that each subset of tokens is checked and refined in real-time by another LLM as the LLM constructs its response. Through comprehensive evaluations on multiple datasets, we demonstrate that our approach not only enhances the factual accuracy of LLMs, but also offers a more efficient solution compared to prior refinement methods. 

**Abstract (ZH)**: 大型语言模型（LLMs）在各类自然语言任务中表现出色。然而，一个关键挑战在于它们有时会产生事实错误的答案。为了解决这一问题，尽管许多先前的工作集中在识别LLMs生成中的错误并进一步对其进行修正，但这些方法在部署上通常较慢，因为它们设计成只在LLMs完成其整个生成过程（从第一个到最后一个词元）后才对其进行验证。此外，我们观察到，一旦LLMs在早期生成错误词元，后续词元更有可能也是事实错误的。基于此，本文提出了一种名为Streaming-VR（流式验证与修正）的新颖方法，旨在提高LLMs输出验证与修正的效率。具体而言，Streaming-VR方法能够实现实时验证和修正生成中的词元，类似于流式处理过程，确保每个词元子集在LLMs构建其响应的同时被另一个LLMs实时检查和修正。通过在多个数据集上的全面评估，我们证明了该方法不仅提高了LLMs的事实准确性，而且提供了比先前修正方法更高效的解决方案。 

---
# Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering 

**Title (ZH)**: 与合适的专家对话：多 Agent 系统中的路由与规划在问答中的应用 

**Authors**: Feijie Wu, Zitao Li, Fei Wei, Yaliang Li, Bolin Ding, Jing Gao  

**Link**: [PDF](https://arxiv.org/pdf/2501.07813)  

**Abstract**: Leveraging large language models (LLMs), an agent can utilize retrieval-augmented generation (RAG) techniques to integrate external knowledge and increase the reliability of its responses. Current RAG-based agents integrate single, domain-specific knowledge sources, limiting their ability and leading to hallucinated or inaccurate responses when addressing cross-domain queries. Integrating multiple knowledge bases into a unified RAG-based agent raises significant challenges, including increased retrieval overhead and data sovereignty when sensitive data is involved. In this work, we propose RopMura, a novel multi-agent system that addresses these limitations by incorporating highly efficient routing and planning mechanisms. RopMura features two key components: a router that intelligently selects the most relevant agents based on knowledge boundaries and a planner that decomposes complex multi-hop queries into manageable steps, allowing for coordinating cross-domain responses. Experimental results demonstrate that RopMura effectively handles both single-hop and multi-hop queries, with the routing mechanism enabling precise answers for single-hop queries and the combined routing and planning mechanisms achieving accurate, multi-step resolutions for complex queries. 

**Abstract (ZH)**: 利用大规模语言模型（LLMs），代理可以通过检索增强生成（RAG）技术整合外部知识，从而提高其响应的可靠性。当前基于RAG的代理通常集成单一的领域特异性知识源，这限制了它们的能力，并且在处理跨域查询时可能导致产生不实或不准确的响应。将多个知识库整合到统一的基于RAG的代理中带来了显著的挑战，包括检索开销的增加以及涉及敏感数据时的数据主权问题。在这项工作中，我们提出了RopMura，这是一种新颖的多Agent系统，通过引入高效的路由和规划机制来解决这些限制。RopMura 包含两个关键组件：一个路由器，可以智能地根据知识边界选择最相关的代理，以及一个规划器，可以将复杂的多跳查询分解为可管理的步骤，从而协调跨域响应。实验结果表明，RopMura 有效地处理了一跳和多跳查询，其中路由机制能够为一跳查询提供精确的回答，而结合的路由和规划机制则能够为复杂的查询实现准确的多步骤解决方案。 

---
# Exploring Robustness of Multilingual LLMs on Real-World Noisy Data 

**Title (ZH)**: 探索多语言大语言模型在真实世界噪声数据中的鲁棒性 

**Authors**: Amirhossein Aliakbarzadeh, Lucie Flek, Akbar Karimi  

**Link**: [PDF](https://arxiv.org/pdf/2501.08322)  

**Abstract**: Large Language Models (LLMs) are trained on Web data that might contain spelling errors made by humans. But do they become robust to similar real-world noise? In this paper, we investigate the effect of real-world spelling mistakes on the performance of 9 language models, with parameters ranging from 0.2B to 13B, in 3 different NLP tasks, namely Natural Language Inference (NLI), Name Entity Recognition (NER), and Intent Classification (IC). We perform our experiments on 6 different languages and build a dictionary of real-world noise for them using the Wikipedia edit history. We show that the performance gap of the studied models on the clean and noisy test data averaged across all the datasets and languages ranges from 2.3 to 4.3 absolute percentage points. In addition, mT5 models, in general, show more robustness compared to BLOOM, Falcon, and BERT-like models. In particular, mT5 (13B), was the most robust on average overall, across the 3 tasks, and in 4 of the 6 languages. 

**Abstract (ZH)**: 大规模语言模型（LLMs）是基于可能包含人类拼写错误的网络数据进行训练的。但它们是否对类似的现实世界噪音具有鲁棒性呢？在本文中，我们探讨了现实世界中的拼写错误对9种不同参数量（从0.2B到13B）的语言模型在3种不同自然语言处理（NLP）任务中的性能影响，具体任务为自然语言推理（NLI）、命名实体识别（NER）和意图分类（IC）。我们在6种不同语言上进行了实验，并使用维基百科的编辑历史构建了针对这些语言的现实世界噪音词典。结果显示，所研究模型在清洁数据和含有噪声数据上的性能差距（在所有数据集和语言上的平均值）范围为2.3到4.3个绝对百分点。此外，mT5模型通常比BLOOM、Falcon和BERT样式的模型更为鲁棒。特别是在3种任务和6种语言中的4种上，mT5（13B）模型表现出了最好的鲁棒性。 

---
# Exploring Robustness of LLMs to Sociodemographically-Conditioned Paraphrasing 

**Title (ZH)**: 探索大语言模型对社会人口统计学条件化同义词的鲁棒性 

**Authors**: Pulkit Arora, Akbar Karimi, Lucie Flek  

**Link**: [PDF](https://arxiv.org/pdf/2501.08276)  

**Abstract**: Large Language Models (LLMs) have shown impressive performance in various NLP tasks. However, there are concerns about their reliability in different domains of linguistic variations. Many works have proposed robustness evaluation measures for local adversarial attacks, but we need globally robust models unbiased to different language styles. We take a broader approach to explore a wider range of variations across sociodemographic dimensions to perform structured reliability tests on the reasoning capacity of language models. We extend the SocialIQA dataset to create diverse paraphrased sets conditioned on sociodemographic styles. The assessment aims to provide a deeper understanding of LLMs in (a) their capability of generating demographic paraphrases with engineered prompts and (b) their reasoning capabilities in real-world, complex language scenarios. We also explore measures such as perplexity, explainability, and ATOMIC performance of paraphrases for fine-grained reliability analysis of LLMs on these sets. We find that demographic-specific paraphrasing significantly impacts the performance of language models, indicating that the subtleties of language variations remain a significant challenge. The code and dataset will be made available for reproducibility and future research. 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种自然语言处理（NLP）任务中展现了令人印象深刻的性能。然而，它们在不同的语言变体领域中的可靠性引起了关注。许多工作提出了针对局部对抗攻击的鲁棒性评估指标，但我们需要的是对不同语言风格具有全局鲁棒性的模型。我们采取了更为广泛的方法，以探索跨社会人口学维度的更广泛变化，并对其进行结构化的可靠性测试，以评估语言模型的推理能力。我们扩展了SocialIQA数据集，创建了基于社会人口学风格的多样化的同义替换集合。这些评估旨在深入了解LLMs在（a）使用精心设计的提示生成针对社会人口学的同义替换方面的能力；以及（b）在现实世界的复杂语言场景中进行推理的能力。我们还探讨了困惑度、可解释性和原子性能等指标，以进行这些集合上的LLMs细粒度可靠性的分析。我们的研究发现，针对不同社会人口学特征的同义替换显著影响了语言模型的性能，这表明语言变体的细微差别仍然是一个重大挑战。我们将代码和数据集公开，以实现可重复性和未来的研究。 

---
# ArithmAttack: Evaluating Robustness of LLMs to Noisy Context in Math Problem Solving 

**Title (ZH)**: 阿斯姆攻击：评估大型语言模型在数学问题求解中对噪声上下文鲁棒性的表现 

**Authors**: Zain Ul Abedin, Shahzeb Qamar, Lucie Flek, Akbar Karimi  

**Link**: [PDF](https://arxiv.org/pdf/2501.08203)  

**Abstract**: While Large Language Models (LLMs) have shown impressive capabilities in math problem-solving tasks, their robustness to noisy inputs is not well-studied. In this work, we propose ArithmAttack to examine how robust the LLMs are when they encounter noisy prompts that contain extra noise in the form of punctuation marks. While being easy to implement, ArithmAttack does not cause any information loss since words are not added or deleted from the context. We evaluate the robustness of seven LLMs, including LLama3, Mistral, and Mathstral, on noisy GSM8K and MultiArith datasets. Our experiments suggest that all the studied models show vulnerability to such noise, with more noise leading to poorer performances. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）在数学问题解决任务中展示了令人印象深刻的性能，但它们对噪声输入的鲁棒性研究尚不充分。在本研究中，我们提出ArithmAttack，以考察LLMs在遇到包含标点符号形式噪声的噪声提示时的鲁棒性。ArithmAttack 既易于实现，又不会造成信息损失，因为上下文中的单词没有被添加或删除。我们在Noisy GSM8K 和 MultiArith 数据集上对七种LLMs（包括LLama3、Mistral 和 Mathstral）的鲁棒性进行了评估。实验结果表明，所有研究的模型对这种噪声都表现出脆弱性，噪声越大，性能越差。 

---
# ReARTeR: Retrieval-Augmented Reasoning with Trustworthy Process Rewarding 

**Title (ZH)**: ReARTeR：具有可信过程奖励的检索增强推理 

**Authors**: Zhongxiang Sun, Qipeng Wang, Weijie Yu, Xiaoxue Zang, Kai Zheng, Jun Xu, Xiao Zhang, Song Yang, Han Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.07861)  

**Abstract**: Retrieval-Augmented Generation (RAG) systems for Large Language Models (LLMs) hold promise in knowledge-intensive tasks but face limitations in complex multi-step reasoning. While recent methods have integrated RAG with chain-of-thought reasoning or test-time search using Process Reward Models (PRMs), these approaches encounter challenges such as a lack of explanations, bias in PRM training data, early-step bias in PRM scores, and insufficient post-training optimization of reasoning potential. To address these issues, we propose Retrieval-Augmented Reasoning through Trustworthy Process Rewarding (ReARTeR), a framework that enhances RAG systems' reasoning capabilities through post-training and test-time scaling. At test time, ReARTeR introduces Trustworthy Process Rewarding via a Process Reward Model for accurate scalar scoring and a Process Explanation Model (PEM) for generating natural language explanations, enabling step refinement. During post-training, it utilizes Monte Carlo Tree Search guided by Trustworthy Process Rewarding to collect high-quality step-level preference data, optimized through Iterative Preference Optimization. ReARTeR addresses three core challenges: (1) misalignment between PRM and PEM, tackled through off-policy preference learning; (2) bias in PRM training data, mitigated by balanced annotation methods and stronger annotations for challenging examples; and (3) early-step bias in PRM, resolved through a temporal-difference-based look-ahead search strategy. Experimental results on multi-step reasoning benchmarks demonstrate significant improvements, underscoring ReARTeR's potential to advance the reasoning capabilities of RAG systems. 

**Abstract (ZH)**: 增强检索的生成（RAG）系统在大型语言模型（LLMs）中的知识密集型任务中展现出潜力，但在复杂多步推理方面面临局限。尽管最近的方法已经将RAG与链式推理或测试时的搜索（使用过程奖励模型PRM）相结合，但这些方法仍然存在诸如缺乏解释、PRM训练数据中的偏差、PRM评分的早期步骤偏差以及推理潜力的测试后训练优化不足等问题。为了解决这些问题，我们提出了一种名为“信赖过程奖励增强推理”（ReARTeR）的框架，该框架通过测试时和测试后训练的放大来增强RAG系统的推理能力。在测试时，ReARTeR通过引入一种过程奖励模型进行准确的标量评分，并通过过程解释模型（PEM）生成自然语言解释，以实现步骤细化。在测试后训练阶段，它利用通过信赖过程奖励指导的蒙特卡罗树搜索收集高质量的步骤偏好数据，并通过迭代偏好优化进行优化。ReARTeR解决的三个核心挑战包括：（1）PRM和PEM之间的不一致，通过离策偏好学习解决；（2）PRM训练数据中的偏差，通过平衡注释方法和对具有挑战性的例子进行更严格的注释来缓解；（3）PRM中的早期步骤偏差，通过基于时差的前瞻搜索策略解决。在多步骤推理基准测试中的实验结果表明，ReARTeR在显著提高RAG系统的推理能力方面具有巨大潜力。 

---
# Reasoning with Graphs: Structuring Implicit Knowledge to Enhance LLMs Reasoning 

**Title (ZH)**: 利用图形进行推理：构架隐含知识以增强LLMs的推理能力 

**Authors**: Haoyu Han, Yaochen Xie, Hui Liu, Xianfeng Tang, Sreyashi Nag, William Headden, Hui Liu, Yang Li, Chen Luo, Shuiwang Ji, Qi He, Jiliang Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.07845)  

**Abstract**: Large language models (LLMs) have demonstrated remarkable success across a wide range of tasks; however, they still encounter challenges in reasoning tasks that require understanding and inferring relationships between distinct pieces of information within text sequences. This challenge is particularly pronounced in tasks involving multi-step processes, such as logical reasoning and multi-hop question answering, where understanding implicit relationships between entities and leveraging multi-hop connections in the given context are crucial. Graphs, as fundamental data structures, explicitly represent pairwise relationships between entities, thereby offering the potential to enhance LLMs' reasoning capabilities. External graphs have proven effective in supporting LLMs across multiple tasks. However, in many reasoning tasks, no pre-existing graph structure is provided. Can we structure implicit knowledge derived from context into graphs to assist LLMs in reasoning? In this paper, we propose Reasoning with Graphs (RwG) by first constructing explicit graphs from the context and then leveraging these graphs to enhance LLM reasoning performance on reasoning tasks. Extensive experiments demonstrate the effectiveness of the proposed method in improving both logical reasoning and multi-hop question answering tasks. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在各种任务中取得了显著的成功；然而，它们在需要理解并推断文本序列中不同信息之间的关系的推理任务中仍然面临挑战。这种挑战在涉及多步骤过程的任务中尤为明显，例如逻辑推理和多跳问答，因为在这些任务中理解实体之间的隐含关系并利用给定上下文中的多跳连接至关重要。图作为一种基本的数据结构，明确地表示实体对之间的关系，从而有可能增强LLMs的推理能力。外部图已经在多个任务中有效地支持了LLMs。然而，在许多推理任务中，并不提供现成的图结构。我们能否将从上下文中推导出的隐含知识结构化为图，以辅助LLMs进行推理？在本文中，我们提出了一种名为“Graph-based Reasoning”（RwG）的方法，即首先从上下文中构建显式的图结构，然后利用这些图来提升LLMs在推理任务中的性能。广泛的实验结果表明，所提出的方法在提高逻辑推理和多跳问答任务的效果方面具有显著的效果。 

---
# Advancing Student Writing Through Automated Syntax Feedback 

**Title (ZH)**: 通过自动句法反馈促进学生写作能力提升 

**Authors**: Kamyar Zeinalipour, Mehak Mehak, Fatemeh Parsamotamed, Marco Maggini, Marco Gori  

**Link**: [PDF](https://arxiv.org/pdf/2501.07740)  

**Abstract**: This study underscores the pivotal role of syntax feedback in augmenting the syntactic proficiency of students. Recognizing the challenges faced by learners in mastering syntactic nuances, we introduce a specialized dataset named Essay-Syntax-Instruct designed to enhance the understanding and application of English syntax among these students. Leveraging the capabilities of Large Language Models (LLMs) such as GPT3.5-Turbo, Llama-2-7b-chat-hf, Llama-2-13b-chat-hf, and Mistral-7B-Instruct-v0.2, this work embarks on a comprehensive fine-tuning process tailored to the syntax improvement task. Through meticulous evaluation, we demonstrate that the fine-tuned LLMs exhibit a marked improvement in addressing syntax-related challenges, thereby serving as a potent tool for students to identify and rectify their syntactic errors. The findings not only highlight the effectiveness of the proposed dataset in elevating the performance of LLMs for syntax enhancement but also illuminate a promising path for utilizing advanced language models to support language acquisition efforts. This research contributes to the broader field of language learning technology by showcasing the potential of LLMs in facilitating the linguistic development of Students. 

**Abstract (ZH)**: 本研究强调了语法反馈在提升学生语法能力方面所发挥的关键作用。面对学习者在掌握语法细微差别方面的挑战，我们引入了一个名为Essay-Syntax-Instruct的专门数据集，旨在增强学生对英语语法的理解和应用能力。利用诸如GPT3.5-Turbo、Llama-2-7b-chat-hf、Llama-2-13b-chat-hf和Mistral-7B-Instruct-v0.2等大型语言模型（LLMs）的能力，本研究启动了一项全面的微调过程，专门针对语法改进任务。通过细致的评估，我们证明了微调后的LLMs在处理语法相关挑战方面表现出明显的改善，从而为学生识别和纠正语法错误提供了一种有力的工具。研究结果不仅突显了所提数据集在提升LLMs语法增强性能方面的有效性，还揭示了利用先进语言模型支持语言习得的努力可能带来的前景。本研究通过展示LLMs在促进学生语言发展方面的潜力，为语言学习技术领域做出了贡献。 

---
# LLMic: Romanian Foundation Language Model 

**Title (ZH)**: LLMic：罗马尼亚基础语言模型 

**Authors**: Vlad-Andrei Bădoiu, Mihai-Valentin Dumitru, Alexandru M. Gherghescu, Alexandru Agache, Costin Raiciu  

**Link**: [PDF](https://arxiv.org/pdf/2501.07721)  

**Abstract**: Recent advances in Large Language Models (LLMs) have demonstrated remarkable capabilities across various tasks with commercial models leading the way. While open models usually operate at a smaller scale, they maintain competitiveness through specialization and fine-tuning. However, a significant challenge persists: open models often underperform in low-resource languages due to limited representation in the training corpus. In this paper, we present LLMic, a bilingual foundation language model designed specifically for the Romanian Language. We document the complete process of pretraining a foundation model for a low-resource language, including corpus construction, architecture selection, and hyper-parameter optimization. Our evaluation demonstrates that LLMic can be specialized for tasks in the target language, achieving results comparable to other much larger open models. We show that fine-tuning LLMic for language translation after the initial pretraining phase outperforms existing solutions in English-to-Romanian translation tasks. This opens the path for efficient large-scale processing for the Romanian language community, using the much smaller LLMic model 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在各种任务中的表现展现了卓越的能力，商业模型在这方面处于领先地位。虽然开放模型通常规模较小，但通过专门化和微调仍能保持竞争力。然而，一个显著的挑战仍然存在：开放模型在低资源语言中往往表现不佳，因为训练语料中的代表性不足。在本文中，我们介绍了一种专门为罗曼语设计的双语基础语言模型——LLMic。我们详细记录了构建低资源语言基础模型的完整过程，包括语料库构建、架构选择和超参数优化。我们的评估表明，LLMic 可以针对目标语言进行专门化，其性能可与更大规模的开放模型相媲美。我们展示了在初始预训练阶段后，对LLMic进行语言翻译微调，可显著优于现有的英-罗翻译解决方案。这为罗曼语社区的高效大规模处理铺平了道路，使用的是更小规模的LLMic模型。 

---
# GPT as a Monte Carlo Language Tree: A Probabilistic Perspective 

**Title (ZH)**: 将下面的论文内容或标题翻译成中文，可以翻译为：

GPT作为一种蒙特卡洛语言树：一种概率视角

这样翻译既保留了原文的学术性，又符合中文的表达习惯。 

**Authors**: Kun-Peng Ning, Jia-Yu Yao, Yu-Yang Liu, Mu-Nan Ning, Li Yuan  

**Link**: [PDF](https://arxiv.org/pdf/2501.07641)  

**Abstract**: Large Language Models (LLMs), such as GPT, are considered to learn the latent distributions within large-scale web-crawl datasets and accomplish natural language processing (NLP) tasks by predicting the next token. However, this mechanism of latent distribution modeling lacks quantitative understanding and analysis. In this paper, we propose a novel perspective that any language dataset can be represented by a Monte Carlo Language Tree (abbreviated as ``Data-Tree''), where each node denotes a token, each edge denotes a token transition probability, and each sequence has a unique path. Any GPT-like language model can also be flattened into another Monte Carlo Language Tree (abbreviated as ``GPT-Tree''). Our experiments show that different GPT models trained on the same dataset exhibit significant structural similarity in GPT-Tree visualization, and larger models converge more closely to the Data-Tree. More than 87\% GPT output tokens can be recalled by Data-Tree. These findings may confirm that the reasoning process of LLMs is more likely to be probabilistic pattern-matching rather than formal reasoning, as each model inference seems to find a context pattern with maximum probability from the Data-Tree. Furthermore, we provide deeper insights into issues such as hallucination, Chain-of-Thought (CoT) reasoning, and token bias in LLMs. 

**Abstract (ZH)**: 大规模语言模型（LLMs），如GPT，被认为是通过预测下一个词来学习大规模网络爬取数据集中的潜在分布，从而完成自然语言处理（NLP）任务。然而，这种潜在分布建模机制缺乏定量的理解和分析。在本文中，我们提出了一个新颖的观点，即任何语言数据集都可以表示为一个蒙特卡洛语言树（简称“Data-Tree”），其中每个节点表示一个词，每条边表示一个词转接概率，每个序列有一个唯一的路径。任何类似于GPT的语言模型也可以展平为另一个蒙特卡洛语言树（简称“GPT-Tree”）。我们的实验表明，相同数据集训练的不同GPT模型在GPT-Tree可视化方面显示出显著的结构相似性，较大的模型更接近于Data-Tree。超过87%的GPT生成的词可以被Data-Tree召回。这些发现可能表明，LLMs的推理过程更可能是概率模式匹配而不是形式推理，因为每个模型的推理似乎是从Data-Tree中找到具有最大概率的上下文模式。此外，我们还深入探讨了LLMs中存在的幻觉、思维链（CoT）推理和词偏见等问题。 

---