# Re-ranking the Context for Multimodal Retrieval Augmented Generation 

**Title (ZH)**: 多模态检索增强生成中重构上下文的重新排名 

**Authors**: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus  

**Link**: [PDF](https://arxiv.org/pdf/2501.04695)  

**Abstract**: Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external knowledge to generate a response within a context with improved accuracy and reduced hallucinations. However, multi-modal RAG systems face unique challenges: (i) the retrieval process may select irrelevant entries to user query (e.g., images, documents), and (ii) vision-language models or multi-modal language models like GPT-4o may hallucinate when processing these entries to generate RAG output. In this paper, we aim to address the first challenge, i.e, improving the selection of relevant context from the knowledge-base in retrieval phase of the multi-modal RAG. Specifically, we leverage the relevancy score (RS) measure designed in our previous work for evaluating the RAG performance to select more relevant entries in retrieval process. The retrieval based on embeddings, say CLIP-based embedding, and cosine similarity usually perform poorly particularly for multi-modal data. We show that by using a more advanced relevancy measure, one can enhance the retrieval process by selecting more relevant pieces from the knowledge-base and eliminate the irrelevant pieces from the context by adaptively selecting up-to-$k$ entries instead of fixed number of entries. Our evaluation using COCO dataset demonstrates significant enhancement in selecting relevant context and accuracy of the generated response. 

**Abstract (ZH)**: 检索增强生成（RAG）通过融入外部知识，增强了大型语言模型（LLMs）在上下文中生成响应的准确性和降低了虚构现象。然而，多模态RAG系统面临独特的挑战：（i）检索过程可能会选择与用户查询无关的条目（例如，图像、文档），以及（ii）当使用如GPT-4o等视觉语言模型或多模态语言模型处理这些条目生成RAG输出时，可能会产生虚构现象。本文旨在解决第一个挑战，即在多模态RAG的检索阶段，改进从知识库中选择相关上下文的方式。具体来说，我们利用我们在先前工作中设计的相关性分数（RS）衡量方法来评估RAG性能，从而在检索过程中选择更多相关内容。基于嵌入（如CLIP嵌入）和余弦相似性的检索通常在多模态数据上表现不佳。我们表明，通过使用更高级的相关性衡量方法，可以在检索过程中选择更多相关内容，并通过适配性地选择最多$k$个条目而不是固定数量的条目，来消除上下文中的无关条目。使用COCO数据集的评估结果表明，这种改进方法显著提高了选择相关上下文和生成响应准确性。 

---
# OpenOmni: Large Language Models Pivot Zero-shot Omnimodal Alignment across Language with Real-time Self-Aware Emotional Speech Synthesis 

**Title (ZH)**: OpenOmni：大规模语言模型实现跨语言的零样本全模态对齐，并结合实时自我意识情感语音合成 

**Authors**: Run Luo, Ting-En Lin, Haonan Zhang, Yuchuan Wu, Xiong Liu, Min Yang, Yongbin Li, Longze Chen, Jiaming Li, Lei Zhang, Yangyi Chen, Hamid Alinejad-Rokny, Fei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04561)  

**Abstract**: Recent advancements in omnimodal learning have been achieved in understanding and generation across images, text, and speech, though mainly within proprietary models. Limited omnimodal datasets and the inherent challenges associated with real-time emotional speech generation have hindered open-source progress. To address these issues, we propose openomni, a two-stage training method combining omnimodal alignment and speech generation to develop a state-of-the-art omnimodal large language model. In the alignment phase, a pre-trained speech model is further trained on text-image tasks to generalize from vision to speech in a (near) zero-shot manner, outperforming models trained on tri-modal datasets. In the speech generation phase, a lightweight decoder facilitates real-time emotional speech through training on speech tasks and preference learning. Experiments demonstrate that openomni consistently improves across omnimodal, vision-language, and speech-language evaluations, enabling natural, emotion-rich dialogues and real-time emotional speech generation. 

**Abstract (ZH)**: 近年来，多模态学习在图像、文本和语音的理解与生成方面取得了显著进展，尽管这些进步主要局限于私有模型中。受限于有限的多模态数据集以及实时情感语音生成固有的挑战，开源进展受到阻碍。为解决这些问题，我们提出了一种双重训练方法Openomni，该方法结合了多模态对齐和语音生成，旨在开发出领先水平的多模态大规模语言模型。在对齐阶段，通过进一步训练预训练的语音模型来执行文本-图像任务，使其能够以（近）零样本方式从视觉领域向语音领域泛化，性能优于基于三模态数据集训练的模型。在语音生成阶段，通过语音任务训练和偏好学习，轻量级解码器能够促进实时情感语音的生成。实验结果表明，Openomni在多模态、视觉语言和语音语言评估中均表现出持续改进，能够实现自然、富有情感的对话以及实时情感语音生成。 

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
# Multimodal Multihop Source Retrieval for Web Question Answering 

**Title (ZH)**: 多模态多跳源检索以实现网页问答 

**Authors**: Navya Yarrabelly, Saloni Mittal  

**Link**: [PDF](https://arxiv.org/pdf/2501.04173)  

**Abstract**: This work deals with the challenge of learning and reasoning over multi-modal multi-hop question answering (QA). We propose a graph reasoning network based on the semantic structure of the sentences to learn multi-source reasoning paths and find the supporting facts across both image and text modalities for answering the question. In this paper, we investigate the importance of graph structure for multi-modal multi-hop question answering. Our analysis is centered on WebQA. We construct a strong baseline model, that finds relevant sources using a pairwise classification task. We establish that, with the proper use of feature representations from pre-trained models, graph structure helps in improving multi-modal multi-hop question answering. We point out that both graph structure and adjacency matrix are task-related prior knowledge, and graph structure can be leveraged to improve the retrieval performance for the task. Experiments and visualized analysis demonstrate that message propagation over graph networks or the entire graph structure can replace massive multimodal transformers with token-wise cross-attention. We demonstrated the applicability of our method and show a performance gain of \textbf{4.6$\%$} retrieval F1score over the transformer baselines, despite being a very light model. We further demonstrated the applicability of our model to a large scale retrieval setting. 

**Abstract (ZH)**: 本研究聚焦于多模态多跳问答（QA）中的学习与推理挑战。我们提出了一种基于句子语义结构的图推理网络，用于学习多源推理路径，并在图像和文本模态之间寻找支持事实以回答问题。在本文中，我们探讨了图结构在多模态多跳问答中的重要性。我们的分析集中在WebQA数据集上。我们构建了一个强基线模型，该模型通过一对分类任务来查找相关源。我们证明，通过恰当利用预训练模型的特征表示，图结构有助于提升多模态多跳问答的效果。我们指出，图结构和邻接矩阵都是与任务相关的先验知识，图结构可以被利用来改进任务的检索性能。实验和可视化分析表明，图网络中的消息传播或整个图结构可以替代大量多模态变换器，使用的是基于令牌的双向注意机制。我们展示了本方法的应用性，并在保持轻量模型的情况下，与变换器基线相比，取得了**4.6%**的检索F1分数提升。此外，我们进一步展示了该模型在大规模检索环境中的应用性。 

---
# "Yeah Right!" -- Do LLMs Exhibit Multimodal Feature Transfer? 

**Title (ZH)**: “yeah right！”——大型语言模型是否表现出跨模态特征迁移？ 

**Authors**: Benjamin Reichman, Kartik Talamadupula  

**Link**: [PDF](https://arxiv.org/pdf/2501.04138)  

**Abstract**: Human communication is a multifaceted and multimodal skill. Communication requires an understanding of both the surface-level textual content and the connotative intent of a piece of communication. In humans, learning to go beyond the surface level starts by learning communicative intent in speech. Once humans acquire these skills in spoken communication, they transfer those skills to written communication. In this paper, we assess the ability of speech+text models and text models trained with special emphasis on human-to-human conversations to make this multimodal transfer of skill. We specifically test these models on their ability to detect covert deceptive communication. We find that with no special prompting speech+text LLMs have an advantage over unimodal LLMs in performing this task. Likewise, we find that human-to-human conversation-trained LLMs are also advantaged in this skill. 

**Abstract (ZH)**: 人类沟通是一项多维度和多模态的技能。沟通不仅要求理解文本内容的表面意义，还需理解其隐含意图。在人类中，学会超越表面层次的沟通始于对言语沟通意图的理解。一旦人类在口头沟通中掌握这些技能，便会将这些技能转移到书面沟通中。在本文中，我们评估了多模态言语+文本模型和具备特别强调人际沟通训练的文本模型在实现这种跨模式技能迁移方面的能力。我们特别测试了这些模型在检测隐蔽欺骗性沟通方面的能力。我们发现，在没有特别提示的情况下，多模态言语+文本的大规模语言模型（LLM）在这项任务上的表现优于单一模态的大规模语言模型。同样，我们发现具备人际沟通训练的大规模语言模型在这一技能上也具有优势。 

---
# InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection 

**Title (ZH)**: InfiGUIAgent：一种具有原生推理和反思能力的多模态通用GUI代理 

**Authors**: Yuhang Liu, Pengxiang Li, Zishu Wei, Congkai Xie, Xueyu Hu, Xinchen Xu, Shengyu Zhang, Xiaotian Han, Hongxia Yang, Fei Wu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04575)  

**Abstract**: Graphical User Interface (GUI) Agents, powered by multimodal large language models (MLLMs), have shown great potential for task automation on computing devices such as computers and mobile phones. However, existing agents face challenges in multi-step reasoning and reliance on textual annotations, limiting their effectiveness. We introduce \textit{InfiGUIAgent}, an MLLM-based GUI Agent trained with a two-stage supervised fine-tuning pipeline. Stage 1 enhances fundamental skills such as GUI understanding and grounding, while Stage 2 integrates hierarchical reasoning and expectation-reflection reasoning skills using synthesized data to enable native reasoning abilities of the agents. \textit{InfiGUIAgent} achieves competitive performance on several GUI benchmarks, highlighting the impact of native reasoning skills in enhancing GUI interaction for automation tasks. Resources are available at \url{this https URL}. 

**Abstract (ZH)**: 由多模态大规模语言模型（MLLMs）驱动的图形用户界面（GUI）代理已经在计算设备如计算机和手机上展示了在任务自动化方面的巨大潜力。然而，现有的代理在多步推理和依赖文本标注方面面临挑战，限制了它们的效果。我们提出了基于MLLM的\textit{InfiGUIAgent}，这是一种通过两阶段监督微调管道进行训练的GUI代理。第一阶段增强基础技能，如GUI理解与定位，第二阶段则通过合成数据整合层级推理和预期-反思推理技能，使代理具备本体推理能力。在多个GUI基准测试中，\textit{InfiGUIAgent}取得了竞争力的表现，突显了本体推理技能在提升GUI交互以适应自动化任务方面的效果。更多资源可参见\url{this https URL}。 

---
# Supervision-free Vision-Language Alignment 

**Title (ZH)**: 无监督视觉-语言对齐 

**Authors**: Giorgio Giannone, Ruoteng Li, Qianli Feng, Evgeny Perevodchikov, Rui Chen, Aleix Martinez  

**Link**: [PDF](https://arxiv.org/pdf/2501.04568)  

**Abstract**: Vision-language models (VLMs) have demonstrated remarkable potential in integrating visual and linguistic information, but their performance is often constrained by the need for extensive, high-quality image-text training data. Curation of these image-text pairs is both time-consuming and computationally expensive. To address this challenge, we introduce SVP (Supervision-free Visual Projection), a novel framework that enhances vision-language alignment without relying on curated data or preference annotation. SVP leverages self-captioning and a pre-trained grounding model as a feedback mechanism to elicit latent information in VLMs. We evaluate our approach across six key areas: captioning, referring, visual question answering, multitasking, hallucination control, and object recall. Results demonstrate significant improvements, including a 14% average improvement in captioning tasks, up to 12% increase in object recall, and substantial reduction in hallucination rates. Notably, a small VLM using SVP achieves hallucination reductions comparable to a model five times larger, while a VLM with initially poor referring capabilities more than doubles its performance, approaching parity with a model twice its size. 

**Abstract (ZH)**: 视觉-语言模型（VLMs）在整合视觉和语言信息方面展现了 remarkable 的潜力，但其性能往往受限于需要大量高质量的图像-文本训练数据。收集这些图像-文本对既耗时又需要高性能计算资源。为了解决这一挑战，我们提出了 SVP（无需监督的视觉投影），这是一种新颖的框架，能够在不依赖于标注数据或偏好标注的情况下增强视觉-语言对齐。SVP 利用自我 caption 生成和预训练的 grounding 模型作为反馈机制，以提取 VLMs 中潜藏的信息。我们从六个关键方面评估了我们的方法：captioning、referencing、视觉问答、多任务、幻觉控制和对象召回。结果表明，该方法在多个方面取得了显著的改进，包括 captioning 任务平均改进了 14%，对象召回增加了 12%，以及在幻觉率方面实现了大幅降低。值得注意的是，使用 SVP 的小型 VLM 在幻觉减少方面的效果与五倍大小的模型相当，而一个初始 referencing 能力较弱的 VLM 则将自己的性能提高了两倍以上，接近与两倍大小模型的性能相当。 

---
# MM-GEN: Enhancing Task Performance Through Targeted Multimodal Data Curation 

**Title (ZH)**: MM-GEN：通过目标导向的多模态数据整理增强任务性能 

**Authors**: Siddharth Joshi, Besmira Nushi, Vidhisha Balachandran, Varun Chandrasekaran, Vibhav Vineet, Neel Joshi, Baharan Mirzasoleiman  

**Link**: [PDF](https://arxiv.org/pdf/2501.04155)  

**Abstract**: Vision-language models (VLMs) are highly effective but often underperform on specialized tasks; for example, Llava-1.5 struggles with chart and diagram understanding due to scarce task-specific training data. Existing training data, sourced from general-purpose datasets, fails to capture the nuanced details needed for these tasks. We introduce MM-Gen, a scalable method that generates task-specific, high-quality synthetic text for candidate images by leveraging stronger models. MM-Gen employs a three-stage targeted process: partitioning data into subgroups, generating targeted text based on task descriptions, and filtering out redundant and outlier data. Fine-tuning VLMs with data generated by MM-Gen leads to significant performance gains, including 29% on spatial reasoning and 15% on diagram understanding for Llava-1.5 (7B). Compared to human-curated caption data, MM-Gen achieves up to 1.6x better improvements for the original models, proving its effectiveness in enhancing task-specific VLM performance and bridging the gap between general-purpose datasets and specialized requirements. Code available at this https URL. 

**Abstract (ZH)**: 视觉-语言模型（VLMs）高度有效，但在特定任务上往往表现不佳；例如，Llava-1.5 在图表和图理解方面表现不佳，这主要是因为缺乏特定任务的训练数据。现有的训练数据来源于通用数据集，无法捕捉到完成这些任务所需的细微差别。我们提出了MM-Gen，这是一种可扩展的方法，通过利用更强的模型生成任务特定的高质量合成文本，用于候选图像。MM-Gen采用三层目标导向的过程：将数据划分为子组、根据任务描述生成目标文本，并过滤冗余和异常数据。使用MM-Gen生成的数据微调VLMs可以显著提高性能，包括Llava-1.5（7B）在空间推理方面的29%提升和图理解方面的15%提升。与人工标注的标题数据相比，MM-Gen能够将原始模型的性能提高多达1.6倍，证明了其在提升特定任务的VLM性能方面的作用，并弥补了通用数据集与特定需求之间的差距。代码详见此链接：https://your-code-link-here.com 

---
# MedCoDi-M: A Multi-Prompt Foundation Model for Multimodal Medical Data Generation 

**Title (ZH)**: MedCoDi-M：一种用于多模态医疗数据生成的多提示基础模型 

**Authors**: Daniele Molino, Francesco Di Feola, Eliodoro Faiella, Deborah Fazzini, Domiziana Santucci, Linlin Shen, Valerio Guarrasi, Paolo Soda  

**Link**: [PDF](https://arxiv.org/pdf/2501.04614)  

**Abstract**: Artificial Intelligence is revolutionizing medical practice, enhancing diagnostic accuracy and healthcare delivery. However, its adaptation in medical settings still faces significant challenges, related to data availability and privacy constraints. Synthetic data has emerged as a promising solution to mitigate these issues, addressing data scarcity while preserving privacy. Recently, Latent Diffusion Models have emerged as a powerful tool for generating high-quality synthetic data. Meanwhile, the integration of different modalities has gained interest, emphasizing the need of models capable of handle multimodal medical this http URL approaches struggle to integrate complementary information and lack the ability to generate modalities simultaneously. To address this challenge, we present MedCoDi-M, a 6.77-billion-parameter model, designed for multimodal medical data generation, that, following Foundation Model paradigm, exploits contrastive learning and large quantity of data to build a shared latent space which capture the relationships between different data modalities. Further, we introduce the Multi-Prompt training technique, which significantly boosts MedCoDi-M's generation under different settings. We extensively validate MedCoDi-M: first we benchmark it against five competitors on the MIMIC-CXR dataset, a state-of-the-art dataset for Chest X-ray and radiological report generation. Secondly, we perform a Visual Turing Test with expert radiologists to assess the realism and clinical relevance of the generated data, ensuring alignment with real-world scenarios. Finally, we assess the utility of MedCoDi-M in addressing key challenges in the medical field, such as anonymization, data scarcity and imbalance learning. The results are promising, demonstrating the applicability of MedCoDi-M in medical contexts. Project page is at this https URL. 

**Abstract (ZH)**: 人工智能正在革命性地改变医疗实践，提高了诊断准确性和医疗服务。然而，其在医疗环境中的应用仍然面临着数据可用性和隐私限制的重大挑战。合成数据已成为缓解这些问题的潜在解决方案，既解决了数据稀缺性问题，又保护了隐私。最近，潜在扩散模型（Latent Diffusion Models）已成为生成高质量合成数据的强大工具。同时，对不同模态的集成引起了广泛关注，强调了能够处理多模态医疗数据的模型的需求。现有的方法在整合互补信息方面存在困难，并且缺乏同时生成不同模态的能力。为了解决这一挑战，我们提出了MedCoDi-M，这是一个67.7亿参数的模型，旨在生成多模态医疗数据。该模型遵循基础模型范式，利用对比学习和大量数据构建共享的潜在空间，捕捉不同数据模态之间的关系。此外，我们还引入了多提示训练技术，这显著提升了MedCoDi-M在不同设置下的生成效果。我们广泛验证了MedCoDi-M：首先，我们在MIMIC-CXR数据集上（该数据集是用于胸部X光片和放射报告生成的前沿数据集）将其与五个竞争对手进行基准测试。其次，我们通过专家放射科医生进行视觉图灵测试，以评估生成数据的现实性和临床相关性，确保与实际场景保持一致。最后，我们评估了MedCoDi-M在应对医疗领域中的关键挑战（如匿名化、数据稀缺性和不均衡学习）方面的实用性。结果非常令人鼓舞，展示了MedCoDi-M在医疗环境中的应用潜力。项目页面链接为：这个 <https://>。 

---
# Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding 

**Title (ZH)**: 超越视觉：通过语言锚定细调具备异构传感器的通用机器人策略 

**Authors**: Joshua Jones, Oier Mees, Carmelo Sferrazza, Kyle Stachowicz, Pieter Abbeel, Sergey Levine  

**Link**: [PDF](https://arxiv.org/pdf/2501.04693)  

**Abstract**: Interacting with the world is a multi-sensory experience: achieving effective general-purpose interaction requires making use of all available modalities -- including vision, touch, and audio -- to fill in gaps from partial observation. For example, when vision is occluded reaching into a bag, a robot should rely on its senses of touch and sound. However, state-of-the-art generalist robot policies are typically trained on large datasets to predict robot actions solely from visual and proprioceptive observations. In this work, we propose FuSe, a novel approach that enables finetuning visuomotor generalist policies on heterogeneous sensor modalities for which large datasets are not readily available by leveraging natural language as a common cross-modal grounding. We combine a multimodal contrastive loss with a sensory-grounded language generation loss to encode high-level semantics. In the context of robot manipulation, we show that FuSe enables performing challenging tasks that require reasoning jointly over modalities such as vision, touch, and sound in a zero-shot setting, such as multimodal prompting, compositional cross-modal prompting, and descriptions of objects it interacts with. We show that the same recipe is applicable to widely different generalist policies, including both diffusion-based generalist policies and large vision-language-action (VLA) models. Extensive experiments in the real world show that FuSeis able to increase success rates by over 20% compared to all considered baselines. 

**Abstract (ZH)**: 与世界交互是一种多感官体验：为了实现有效的通用交互，需要充分利用所有可用的模态，包括视觉、触觉和音频，以填补部分观察带来的空白。例如，在视线受阻的情况下从袋子里取东西时，机器人应当依赖触觉和听觉。然而，最先进的通用机器人策略通常只在大型数据集上进行训练，从视觉和本体感觉观察中预测机器人的行为。在本研究中，我们提出了FuSe，一种新颖的方法，通过利用自然语言作为跨模态的共同基础，使视觉运动的通用策略能够针对无法获得大量数据的异构传感器模态进行微调。我们结合了多模态对比损失和基于感官的语义生成损失，以编码高层次的语义。在机器人操作的背景下，我们展示了FuSe能够在零样本设置中执行需要联合推理多种模态（如视觉、触觉和音频）的挑战性任务，包括多模态提示、组成跨模态提示以及描述其交互对象的描述。我们表明，相同的配方适用于广泛不同的通用策略，包括基于扩散的通用策略和大型视觉-语言-动作（VLA）模型。在实际世界中的大量实验中，我们发现FuSe相较于所有考虑的基线方法，能够将成功率达到20%以上的提高。 

---
# DRIVINGVQA: Analyzing Visual Chain-of-Thought Reasoning of Vision Language Models in Real-World Scenarios with Driving Theory Tests 

**Title (ZH)**: 车载视觉问答：在驾驶理论测试中分析视觉语言模型在现实场景中的视觉链式思维推理能力 

**Authors**: Charles Corbière, Simon Roburin, Syrielle Montariol, Antoine Bosselut, Alexandre Alahi  

**Link**: [PDF](https://arxiv.org/pdf/2501.04671)  

**Abstract**: Large vision-language models (LVLMs) augment language models with visual understanding, enabling multimodal reasoning. However, due to the modality gap between textual and visual data, they often face significant challenges, such as over-reliance on text priors, hallucinations, and limited capacity for complex visual reasoning. Existing benchmarks to evaluate visual reasoning in LVLMs often rely on schematic or synthetic images and on imprecise machine-generated explanations. To bridge the modality gap, we present DrivingVQA, a new benchmark derived from driving theory tests to evaluate visual chain-of-thought reasoning in complex real-world scenarios. It offers 3,931 expert-crafted multiple-choice problems and interleaved explanations grounded with entities relevant to the reasoning process. We leverage this dataset to perform an extensive study of LVLMs' ability to reason about complex visual scenarios. Our experiments reveal that open-source and proprietary LVLMs struggle with visual chain-of-thought reasoning under zero-shot settings. We investigate training strategies that leverage relevant entities to improve visual reasoning. Notably, we observe a performance boost of up to 7\% when reasoning over image tokens of cropped regions tied to these entities. 

**Abstract (ZH)**: 大型跨模态语言模型（LVLMs）通过引入视觉理解来扩展语言模型的功能，从而实现多模态推理。然而，由于文本数据和视觉数据之间的模态差距，它们往往面临诸多挑战，例如过度依赖文本先验、幻觉以及复杂视觉推理能力有限。现有用于评估LVLMs视觉推理能力的基准测试往往依赖于简化的或合成的图像以及不精确的人工生成的解释。为了解决这一模态差距，我们提出了DrivingVQA，这是一种新的基准测试，源自驾驶理论测试，旨在评估复杂现实场景中的视觉链式推理能力。它提供了3,931个专家手工制作的多项选择题和嵌入了相关实体的解释。我们利用这个数据集来探讨LVLMs在复杂视觉场景推理方面的能力。我们的实验表明，在零样本设置下，开源和专有LVLMs在视觉链式推理方面存在困难。我们研究了利用相关实体进行训练的方法以提高视觉推理能力。值得注意的是，当我们对与这些实体相关的裁剪区域图像进行推理时，观察到最大7%的性能提升。 

---
# H-MBA: Hierarchical MamBa Adaptation for Multi-Modal Video Understanding in Autonomous Driving 

**Title (ZH)**: H-MBA：自主驾驶中多模态视频理解的分层MamBa自适应方法 

**Authors**: Siran Chen, Yuxiao Luo, Yue Ma, Yu Qiao, Yali Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04302)  

**Abstract**: With the prevalence of Multimodal Large Language Models(MLLMs), autonomous driving has encountered new opportunities and challenges. In particular, multi-modal video understanding is critical to interactively analyze what will happen in the procedure of autonomous driving. However, videos in such a dynamical scene that often contains complex spatial-temporal movements, which restricts the generalization capacity of the existing MLLMs in this field. To bridge the gap, we propose a novel Hierarchical Mamba Adaptation (H-MBA) framework to fit the complicated motion changes in autonomous driving videos. Specifically, our H-MBA consists of two distinct modules, including Context Mamba (C-Mamba) and Query Mamba (Q-Mamba). First, C-Mamba contains various types of structure state space models, which can effectively capture multi-granularity video context for different temporal resolutions. Second, Q-Mamba flexibly transforms the current frame as the learnable query, and attentively selects multi-granularity video context into query. Consequently, it can adaptively integrate all the video contexts of multi-scale temporal resolutions to enhance video understanding. Via a plug-and-play paradigm in MLLMs, our H-MBA shows the remarkable performance on multi-modal video tasks in autonomous driving, e.g., for risk object detection, it outperforms the previous SOTA method with 5.5% mIoU improvement. 

**Abstract (ZH)**: 随着多模态大语言模型（MLLMs）的普及，自动驾驶面临着新的机遇与挑战。尤其在自动驾驶过程中，多模态视频理解对于实时分析即将发生的情况至关重要。然而，这些动态场景中的视频通常包含复杂的时空运动，这限制了现有MLLMs在这方面的泛化能力。为了解决这一问题，我们提出了一种新颖的层次Mamba自适应（H-MBA）框架，以适应自动驾驶视频中的复杂运动变化。具体而言，我们的H-MBA框架包含两个不同的模块，即上下文Mamba（C-Mamba）和查询Mamba（Q-Mamba）。首先，C-Mamba包含多种结构状态空间模型，能够有效捕捉不同时间分辨率下的多尺度视频上下文。其次，Q-Mamba灵活地将当前帧转换为可学习的查询，并注意力选择多尺度视频上下文作为查询。由此，它可以通过自适应地整合不同时间尺度下的所有视频上下文来增强视频理解。通过在MLLMs中的插拔式 Paradigm，我们的 H-MBA 在自动驾驶中的多模态视频任务中展现出显著性能，例如，在风险对象检测中，与之前的最先进的方法相比，取得了5.5%的mIoU改进。 

---
# Enhancing Scene Classification in Cloudy Image Scenarios: A Collaborative Transfer Method with Information Regulation Mechanism using Optical Cloud-Covered and SAR Remote Sensing Images 

**Title (ZH)**: 基于光学云覆盖图像和SAR遥感图像的协作迁移方法及其信息调节机制在云雾场景下场景分类能力的提升 

**Authors**: Yuze Wang, Rong Xiao, Haifeng Li, Mariana Belgiu, Chao Tao  

**Link**: [PDF](https://arxiv.org/pdf/2501.04283)  

**Abstract**: In remote sensing scene classification, leveraging the transfer methods with well-trained optical models is an efficient way to overcome label scarcity. However, cloud contamination leads to optical information loss and significant impacts on feature distribution, challenging the reliability and stability of transferred target models. Common solutions include cloud removal for optical data or directly using Synthetic aperture radar (SAR) data in the target domain. However, cloud removal requires substantial auxiliary data for support and pre-training, while directly using SAR disregards the unobstructed portions of optical data. This study presents a scene classification transfer method that synergistically combines multi-modality data, which aims to transfer the source domain model trained on cloudfree optical data to the target domain that includes both cloudy optical and SAR data at low cost. Specifically, the framework incorporates two parts: (1) the collaborative transfer strategy, based on knowledge distillation, enables the efficient prior knowledge transfer across heterogeneous data; (2) the information regulation mechanism (IRM) is proposed to address the modality imbalance issue during transfer. It employs auxiliary models to measure the contribution discrepancy of each modality, and automatically balances the information utilization of modalities during the target model learning process at the sample-level. The transfer experiments were conducted on simulated and real cloud datasets, demonstrating the superior performance of the proposed method compared to other solutions in cloud-covered scenarios. We also verified the importance and limitations of IRM, and further discussed and visualized the modality imbalance problem during the model transfer. Codes are available at this https URL 

**Abstract (ZH)**: 在遥感场景分类中，利用预训练光学模型的迁移方法是一种有效克服标签稀缺的方法。然而，云污染导致了光学信息的丢失，并对特征分布产生了显著影响，这挑战了目标模型的可靠性和稳定性。常见的解决方案包括对光学数据进行云去除或直接在目标域中使用合成孔径雷达（SAR）数据。但是，云去除需要大量的辅助数据支持和预训练，而直接使用SAR数据则忽视了光学数据中的清晰部分。本研究提出了一种结合多模态数据的场景分类迁移方法，旨在以低成本将训练于无云光学数据源域模型迁移到包括有云光学和SAR数据的目标域。具体而言，该框架包括两个部分：（1）基于知识蒸馏的协同迁移策略能够高效地在异构数据间转移先验知识；（2）提出了一种信息调节机制（IRM），以解决迁移过程中模态不平衡的问题。该机制利用辅助模型测量每种模态的贡献差异，并在目标模型学习过程中按样本级自动平衡不同模态的信息利用。我们在模拟和实际的云覆盖数据集上进行了迁移实验，结果显示与现有解决方案相比，所提出的方法在云覆盖场景中的性能更优。我们还验证了IRM的重要性及其限制，并进一步讨论和可视化了模型迁移过程中模态不平衡的问题。代码可在以下链接获取：[此处提供链接] 

---
# Listening and Seeing Again: Generative Error Correction for Audio-Visual Speech Recognition 

**Title (ZH)**: 重新倾听与观看：生成式错误修正的视听语音识别 

**Authors**: Rui Liu, Hongyu Yuan, Haizhou Li  

**Link**: [PDF](https://arxiv.org/pdf/2501.04038)  

**Abstract**: Unlike traditional Automatic Speech Recognition (ASR), Audio-Visual Speech Recognition (AVSR) takes audio and visual signals simultaneously to infer the transcription. Recent studies have shown that Large Language Models (LLMs) can be effectively used for Generative Error Correction (GER) in ASR by predicting the best transcription from ASR-generated N-best hypotheses. However, these LLMs lack the ability to simultaneously understand audio and visual, making the GER approach challenging to apply in AVSR. In this work, we propose a novel GER paradigm for AVSR, termed AVGER, that follows the concept of ``listening and seeing again''. Specifically, we first use the powerful AVSR system to read the audio and visual signals to get the N-Best hypotheses, and then use the Q-former-based Multimodal Synchronous Encoder to read the audio and visual information again and convert them into an audio and video compression representation respectively that can be understood by LLM. Afterward, the audio-visual compression representation and the N-Best hypothesis together constitute a Cross-modal Prompt to guide the LLM in producing the best transcription. In addition, we also proposed a Multi-Level Consistency Constraint training criterion, including logits-level, utterance-level and representations-level, to improve the correction accuracy while enhancing the interpretability of audio and visual compression representations. The experimental results on the LRS3 dataset show that our method outperforms current mainstream AVSR systems. The proposed AVGER can reduce the Word Error Rate (WER) by 24% compared to them. Code and models can be found at: this https URL. 

**Abstract (ZH)**: 与传统的自动语音识别（ASR）不同，音频-视觉语音识别（AVSR）同时利用音频和视觉信号来推断转写。 recent 研究表明，大语言模型（LLMs）能够有效用于ASR中的生成性错误纠正（GER），通过预测ASR生成的N-best假设中最优的转写结果。然而，这些LLMs缺乏同时理解音频和视觉信号的能力，使得GER方法在AVSR中的应用具有挑战性。在这项工作中，我们提出了一种新的AVSR的GER范式，称为AVGER，遵循“再次倾听并观察”的概念。具体而言，我们首先使用强大的AVSR系统阅读音频和视觉信号以获得N-best假设，然后使用基于Q-former的多模态同步编码器再次阅读音频和视觉信息，并分别将其转换为LLM能够理解的音频和视频压缩表示。随后，音频-视觉压缩表示和N-best假设共同构成交叉模态提示，以指导LLM生成最优的转写结果。此外，我们还提出了多级一致性约束训练准则，包括logits级、语句级和表示级，以提高纠错准确性并增强音频和视觉压缩表示的可解释性。在LRS3数据集上的实验证明了我们的方法优于当前主流的AVSR系统。所提出的方法在Word Error Rate（WER）上相比它们降低了24%。有关代码和模型可访问：this https URL。 

---