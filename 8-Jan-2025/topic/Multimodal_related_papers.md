# LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token 

**Title (ZH)**: LLaVA-Mini：高效的一视窗大规模多模态模型 

**Authors**: Shaolei Zhang, Qingkai Fang, Zhe Yang, Yang Feng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03895)  

**Abstract**: The advent of real-time large multimodal models (LMMs) like GPT-4o has sparked considerable interest in efficient LMMs. LMM frameworks typically encode visual inputs into vision tokens (continuous representations) and integrate them and textual instructions into the context of large language models (LLMs), where large-scale parameters and numerous context tokens (predominantly vision tokens) result in substantial computational overhead. Previous efforts towards efficient LMMs always focus on replacing the LLM backbone with smaller models, while neglecting the crucial issue of token quantity. In this paper, we introduce LLaVA-Mini, an efficient LMM with minimal vision tokens. To achieve a high compression ratio of vision tokens while preserving visual information, we first analyze how LMMs understand vision tokens and find that most vision tokens only play a crucial role in the early layers of LLM backbone, where they mainly fuse visual information into text tokens. Building on this finding, LLaVA-Mini introduces modality pre-fusion to fuse visual information into text tokens in advance, thereby facilitating the extreme compression of vision tokens fed to LLM backbone into one token. LLaVA-Mini is a unified large multimodal model that can support the understanding of images, high-resolution images, and videos in an efficient manner. Experiments across 11 image-based and 7 video-based benchmarks demonstrate that LLaVA-Mini outperforms LLaVA-v1.5 with just 1 vision token instead of 576. Efficiency analyses reveal that LLaVA-Mini can reduce FLOPs by 77%, deliver low-latency responses within 40 milliseconds, and process over 10,000 frames of video on the GPU hardware with 24GB of memory. 

**Abstract (ZH)**: 实时大规模多模态模型（LMMs）如GPT-4o的出现引起了人们对高效LMMs的兴趣。LMM框架通常将视觉输入编码为视觉标记（连续表示），并将它们与文本指令整合进大型语言模型（LLMs）的上下文中，其中大规模参数和大量上下文标记（主要是视觉标记）导致了显著的计算开销。以往针对高效LMMs的努力主要集中于用较小的模型替换LLM主干，而忽视了标记数量的关键问题。在本文中，我们提出了LLaVA-Mini，这是一种具有最小视觉标记的高效LMM。为了在保持视觉信息的同时实现视觉标记的高压缩比，我们首先分析了LMMs如何理解视觉标记，并发现大多数视觉标记主要在LLM主干的早期层中起关键作用，在此过程中，它们主要将视觉信息融合到文本标记中。基于这一发现，LLaVA-Mini 引入了模态前融合，提前将视觉信息融合到文本标记中，从而实现了向LLM主干提供的视觉标记极端压缩到一个标记。LLaVA-Mini 是一个统一的大规模多模态模型，可以高效地支持对图像、高分辨率图像和视频的理解。在11个基于图像和7个基于视频的基准测试中进行的实验表明，与使用576个视觉标记的LLaVA-v1.5相比，仅使用1个视觉标记的LLaVA-Mini表现出色。效率分析表明，LLaVA-Mini 可以将FLOPs减少77%，在40毫秒内提供低延迟响应，并在具有24GB内存的GPU硬件上处理超过10,000帧的视频。 

---
# RAG-Check: Evaluating Multimodal Retrieval Augmented Generation Performance 

**Title (ZH)**: RAG-Check：评估多模态检索增强生成性能 

**Authors**: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus  

**Link**: [PDF](https://arxiv.org/pdf/2501.03995)  

**Abstract**: Retrieval-augmented generation (RAG) improves large language models (LLMs) by using external knowledge to guide response generation, reducing hallucinations. However, RAG, particularly multi-modal RAG, can introduce new hallucination sources: (i) the retrieval process may select irrelevant pieces (e.g., documents, images) as raw context from the database, and (ii) retrieved images are processed into text-based context via vision-language models (VLMs) or directly used by multi-modal language models (MLLMs) like GPT-4o, which may hallucinate. To address this, we propose a novel framework to evaluate the reliability of multi-modal RAG using two performance measures: (i) the relevancy score (RS), assessing the relevance of retrieved entries to the query, and (ii) the correctness score (CS), evaluating the accuracy of the generated response. We train RS and CS models using a ChatGPT-derived database and human evaluator samples. Results show that both models achieve ~88% accuracy on test data. Additionally, we construct a 5000-sample human-annotated database evaluating the relevancy of retrieved pieces and the correctness of response statements. Our RS model aligns with human preferences 20% more often than CLIP in retrieval, and our CS model matches human preferences ~91% of the time. Finally, we assess various RAG systems' selection and generation performances using RS and CS. 

**Abstract (ZH)**: 检索增强生成（Retrieval-Augmented Generation，RAG）通过利用外部知识引导响应生成，从而改进了大规模语言模型（Large Language Models，LLMs），减少幻觉现象。然而，RAG，尤其是多模态RAG，可能会引入新的幻觉来源：（i）检索过程可能会从数据库中选择与查询无关的片段（如文档、图像）作为原始上下文；（ii）检索到的图像通过视觉语言模型（Vision-Language Models，VLMs）转换为基于文本的上下文，或者直接被多模态语言模型（Multimodal Language Models，MLLMs）如GPT-4o使用，可能导致幻觉。为应对这一问题，我们提出了一种新的框架来评估多模态RAG的可靠性，使用两种性能指标：（i）相关性评分（Relevance Score，RS），评估检索条目与查询的相关性；（ii）正确性评分（Correctness Score，CS），评估生成响应的准确性。我们使用从ChatGPT派生的数据库和人工评估样本训练RS和CS模型。结果显示，这两种模型在测试数据上的准确率均达到约88%。此外，我们构建了一个包含5000个样本的人工标注数据库，用于评估检索片段的相关性及响应陈述的准确性。我们的RS模型在检索中比CLIP更符合人类偏好20%，而我们的CS模型约91%的情况下与人类偏好一致。最后，我们使用RS和CS评估了各种RAG系统的选择和生成性能。 

---
# Video-of-Thought: Step-by-Step Video Reasoning from Perception to Cognition 

**Title (ZH)**: 思维视频：从感知到认知的逐步视频推理 

**Authors**: Hao Fei, Shengqiong Wu, Wei Ji, Hanwang Zhang, Meishan Zhang, Mong-Li Lee, Wynne Hsu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03230)  

**Abstract**: Existing research of video understanding still struggles to achieve in-depth comprehension and reasoning in complex videos, primarily due to the under-exploration of two key bottlenecks: fine-grained spatial-temporal perceptive understanding and cognitive-level video scene comprehension. This paper bridges the gap by presenting a novel solution. We first introduce a novel video Multimodal Large Language Model (MLLM), MotionEpic, which achieves fine-grained pixel-level spatial-temporal video grounding by integrating video spatial-temporal scene graph (STSG) representation. Building upon MotionEpic, we then develop a Video-of-Thought (VoT) reasoning framework. VoT inherits the Chain-of-Thought (CoT) core, breaking down a complex task into simpler and manageable sub-problems, and addressing them step-by-step from a low-level pixel perception to high-level cognitive interpretation. Extensive experiments across various complex video QA benchmarks demonstrate that our overall framework strikingly boosts existing state-of-the-art. To our knowledge, this is the first attempt at successfully implementing the CoT technique for achieving human-level video reasoning, where we show great potential in extending it to a wider range of video understanding scenarios. Project is open at this https URL 

**Abstract (ZH)**: 现有的视频理解研究在实现对复杂视频的深入理解和推理方面仍然面临挑战，主要原因是忽视了两个关键瓶颈：精细化的空间-时间感知理解和认知级别的视频场景理解。本文通过提出一种新颖的解决方案来弥补这一差距。我们首先介绍了一种新颖的视频多模态大型语言模型（MLLM），名为MotionEpic，该模型通过集成视频空间-时间场景图（STSG）表示，实现了精细化的像素级空间-时间视频接地。在此基础上，我们进一步开发了一种视频思维（VoT）推理框架。VoT继承了链式思维（CoT）的核心理念，将复杂任务细分为更简单且可管理的子问题，并从低层次的像素感知逐步过渡到高层次的认知解释。广泛实验结果表明，我们提出的整体框架显著提升了现有最先进的方法。据我们所知，这是首次尝试成功实施CoT技术以实现人类级别的视频推理，在各种复杂的视频问答基准测试中展示了巨大潜力，我们展示了将其扩展到更广泛的视频理解场景的巨大可能性。该项目的代码已开源，可以访问此链接：[请在此处添加链接] 

---
# VLM-driven Behavior Tree for Context-aware Task Planning 

**Title (ZH)**: 基于VLM的上下文感知任务规划行为树 

**Authors**: Naoki Wake, Atsushi Kanehira, Jun Takamatsu, Kazuhiro Sasabuchi, Katsushi Ikeuchi  

**Link**: [PDF](https://arxiv.org/pdf/2501.03968)  

**Abstract**: The use of Large Language Models (LLMs) for generating Behavior Trees (BTs) has recently gained attention in the robotics community, yet remains in its early stages of development. In this paper, we propose a novel framework that leverages Vision-Language Models (VLMs) to interactively generate and edit BTs that address visual conditions, enabling context-aware robot operations in visually complex environments. A key feature of our approach lies in the conditional control through self-prompted visual conditions. Specifically, the VLM generates BTs with visual condition nodes, where conditions are expressed as free-form text. Another VLM process integrates the text into its prompt and evaluates the conditions against real-world images during robot execution. We validated our framework in a real-world cafe scenario, demonstrating both its feasibility and limitations. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）用于生成行为树（BTs）在机器人领域引起了关注，但这一领域仍处于早期发展阶段。本文提出了一种新颖的框架，该框架利用视觉语言模型（VLMs）交互生成和编辑能够处理视觉条件的行为树，从而在视觉复杂环境中实现具有情境感知能力的机器人操作。我们方法的关键特点在于通过自我提示的视觉条件进行条件控制。具体来说，VLM 生成带有视觉条件节点的行为树，其中条件以自由形式的文本表达。另一个 VLM 过程将文本融入其提示中，并在机器人执行过程中针对真实世界的图像评估条件。我们已经在现实世界的咖啡店场景中验证了该框架，展示了其可行性及其局限性。 

---
# CL3DOR: Contrastive Learning for 3D Large Multimodal Models via Odds Ratio on High-Resolution Point Clouds 

**Title (ZH)**: CL3DOR：基于高分辨率点云上的优势比对比学习的大规模多模态3D模型 

**Authors**: Keonwoo Kim, Yeongjae Cho, Taebaek Hwang, Minsoo Jo, Sangdo Han  

**Link**: [PDF](https://arxiv.org/pdf/2501.03879)  

**Abstract**: Recent research has demonstrated that Large Language Models (LLMs) are not limited to text-only tasks but can also function as multimodal models across various modalities, including audio, images, and videos. In particular, research on 3D Large Multimodal Models (3D LMMs) is making notable strides, driven by the potential of processing higher-dimensional data like point clouds. However, upon closer examination, we find that the visual and textual content within each sample of existing training datasets lacks both high informational granularity and clarity, which serve as a bottleneck for precise cross-modal understanding. To address these issues, we propose CL3DOR, Contrastive Learning for 3D large multimodal models via Odds ratio on high-Resolution point clouds, designed to ensure greater specificity and clarity in both visual and textual content. Specifically, we increase the density of point clouds per object and construct informative hard negative responses in the training dataset to penalize unwanted responses. To leverage hard negative responses, we incorporate the odds ratio as an auxiliary term for contrastive learning into the conventional language modeling loss. CL3DOR achieves state-of-the-art performance in 3D scene understanding and reasoning benchmarks. Additionally, we demonstrate the effectiveness of CL3DOR's key components through extensive experiments. 

**Abstract (ZH)**: 近年来的研究表明，大型语言模型（LLMs）不仅局限于文本任务，还可以作为多种模态模型在音频、图像和视频等各种模态中发挥作用。特别是，关于3D大型多模态模型（3D LMMs）的研究已经取得了显著进展，这得益于处理高维度数据（如点云）的潜力。然而，进一步观察发现，现有训练数据集中每个样本中的视觉和文本内容缺乏高的信息粒度和清晰度，这成为实现精确跨模态理解的瓶颈。为了解决这些问题，我们提出了CL3DOR——一种基于点云高分辨率的似然比对比学习方法，旨在提高视觉和文本内容的特异性和清晰度。具体而言，我们增加了每个对象的点云密度，并在训练数据集中构建了信息性的“硬负样本”响应，以削弱不希望得到的响应。为了利用这些“硬负样本”响应，我们将似然比引入传统的语言建模损失中作为辅助项进行对比学习。CL3DOR在3D场景理解和推理基准测试中实现了最先进的性能。此外，我们通过广泛的实验展示了CL3DOR关键组件的有效性。 

---
# Self-adaptive vision-language model for 3D segmentation of pulmonary artery and vein 

**Title (ZH)**: 自适应视觉-语言模型在肺动脉和静脉的三维分割中的应用 

**Authors**: Xiaotong Guo, Deqian Yang, Dan Wang, Haochen Zhao, Yuan Li, Zhilin Sui, Tao Zhou, Lijun Zhang, Yanda Meng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03722)  

**Abstract**: Accurate segmentation of pulmonary structures iscrucial in clinical diagnosis, disease study, and treatment planning. Significant progress has been made in deep learning-based segmentation techniques, but most require much labeled data for training. Consequently, developing precise segmentation methods that demand fewer labeled datasets is paramount in medical image analysis. The emergence of pre-trained vision-language foundation models, such as CLIP, recently opened the door for universal computer vision tasks. Exploiting the generalization ability of these pre-trained foundation models on downstream tasks, such as segmentation, leads to unexpected performance with a relatively small amount of labeled data. However, exploring these models for pulmonary artery-vein segmentation is still limited. This paper proposes a novel framework called Language-guided self-adaptive Cross-Attention Fusion Framework. Our method adopts pre-trained CLIP as a strong feature extractor for generating the segmentation of 3D CT scans, while adaptively aggregating the cross-modality of text and image representations. We propose a s pecially designed adapter module to fine-tune pre-trained CLIP with a self-adaptive learning strategy to effectively fuse the two modalities of embeddings. We extensively validate our method on a local dataset, which is the largest pulmonary artery-vein CT dataset to date and consists of 718 labeled data in total. The experiments show that our method outperformed other state-of-the-art methods by a large margin. Our data and code will be made publicly available upon acceptance. 

**Abstract (ZH)**: 准确的肺部结构分割对于临床诊断、疾病研究和治疗计划至关重要。基于深度学习的分割技术取得了显著进展，但大多数方法需要大量的标注数据进行训练。因此，开发少标注数据需求的精确分割方法在医学图像分析中至关重要。近年来，预训练的跨模态基础模型，如CLIP，的出现为通用计算机视觉任务打开了大门。利用这些预训练基础模型在下游任务，如分割中的泛化能力，可以取得相对较小的标注数据量但令人惊讶的性能。然而，探索这些模型用于肺动脉-静脉分割仍然有限。本文提出了一种名为语言引导自适应交叉注意力融合框架的新框架。我们的方法采用预训练的CLIP作为强特征提取器，用于生成3D CT扫描的分割结果，并自适应地聚合文本和图像表示的跨模态信息。我们提出了一种特别设计的适配器模块，使用自适应学习策略微调预训练的CLIP，以有效融合两种嵌入表示。我们广泛验证了该方法，使用目前最大的肺动脉-静脉CT数据集进行验证，该数据集包含718个标注数据。实验结果显示，该方法在所有当前最先进的方法中表现出了显著的优势。论文的数据和代码将在接受后公开提供。 

---
# Action Quality Assessment via Hierarchical Pose-guided Multi-stage Contrastive Regression 

**Title (ZH)**: 基于层次姿势引导多阶段对比回归的动作质量评估 

**Authors**: Mengshi Qi, Hao Ye, Jiaxuan Peng, Huadong Ma  

**Link**: [PDF](https://arxiv.org/pdf/2501.03674)  

**Abstract**: Action Quality Assessment (AQA), which aims at automatic and fair evaluation of athletic performance, has gained increasing attention in recent years. However, athletes are often in rapid movement and the corresponding visual appearance variances are subtle, making it challenging to capture fine-grained pose differences and leading to poor estimation performance. Furthermore, most common AQA tasks, such as diving in sports, are usually divided into multiple sub-actions, each of which contains different durations. However, existing methods focus on segmenting the video into fixed frames, which disrupts the temporal continuity of sub-actions resulting in unavoidable prediction errors. To address these challenges, we propose a novel action quality assessment method through hierarchically pose-guided multi-stage contrastive regression. Firstly, we introduce a multi-scale dynamic visual-skeleton encoder to capture fine-grained spatio-temporal visual and skeletal features. Then, a procedure segmentation network is introduced to separate different sub-actions and obtain segmented features. Afterwards, the segmented visual and skeletal features are both fed into a multi-modal fusion module as physics structural priors, to guide the model in learning refined activity similarities and variances. Finally, a multi-stage contrastive learning regression approach is employed to learn discriminative representations and output prediction results. In addition, we introduce a newly-annotated FineDiving-Pose Dataset to improve the current low-quality human pose labels. In experiments, the results on FineDiving and MTL-AQA datasets demonstrate the effectiveness and superiority of our proposed approach. Our source code and dataset are available at this https URL. 

**Abstract (ZH)**: 动作质量评估（AQA），旨在实现对运动员表现的自动且公平评价，近年来引起了越来越多的关注。然而，运动员往往处于快速移动状态，相应的视觉外观变化微妙，这使得捕捉动作间的微小差异变得极具挑战性，从而导致估计性能不佳。此外，大多数常见的AQA任务，如体育中的跳水，通常被划分为多个子动作，每个子动作具有不同的持续时间。然而，现有方法专注于将视频分割成固定帧，这打断了子动作的时间连续性，导致不可避免的预测误差。为应对这些挑战，我们提出了一种通过分层动作导向多阶段对比回归的新颖动作质量评估方法。首先，我们引入多尺度动态视觉骨架编码器，以捕获精细的空间-时间视觉和骨架特征。然后，引入一个程序分割网络以分离不同的子动作并获取分割特征。接着，将分割的视觉和骨架特征同时输入多模态融合模块，作为物理结构先验，以引导模型学习精细的活动相似性和差异。最后，采用多阶段对比学习回归方法来学习判别性表示并输出预测结果。此外，我们引入了一个新标注的FineDiving-Pose数据集，以提高当前低质量的人体姿态标签。在实验中，对FineDiving和MTL-AQA数据集的结果表明了我们提出方法的有效性和优越性。我们的源代码和数据集可以在以下链接获取：[这里插入实际链接]。 

---
# Multi-Modal One-Shot Federated Ensemble Learning for Medical Data with Vision Large Language Model 

**Title (ZH)**: 基于视觉大型语言模型的多模态一-shot联邦集成学习在医疗数据中的应用 

**Authors**: Naibo Wang, Yuchen Deng, Shichen Fan, Jianwei Yin, See-Kiong Ng  

**Link**: [PDF](https://arxiv.org/pdf/2501.03292)  

**Abstract**: Federated learning (FL) has attracted considerable interest in the medical domain due to its capacity to facilitate collaborative model training while maintaining data privacy. However, conventional FL methods typically necessitate multiple communication rounds, leading to significant communication overhead and delays, especially in environments with limited bandwidth. One-shot federated learning addresses these issues by conducting model training and aggregation in a single communication round, thereby reducing communication costs while preserving privacy. Among these, one-shot federated ensemble learning combines independently trained client models using ensemble techniques such as voting, further boosting performance in non-IID data scenarios. On the other hand, existing machine learning methods in healthcare predominantly use unimodal data (e.g., medical images or textual reports), which restricts their diagnostic accuracy and comprehensiveness. Therefore, the integration of multi-modal data is proposed to address these shortcomings. In this paper, we introduce FedMME, an innovative one-shot multi-modal federated ensemble learning framework that utilizes multi-modal data for medical image analysis. Specifically, FedMME capitalizes on vision large language models to produce textual reports from medical images, employs a BERT model to extract textual features from these reports, and amalgamates these features with visual features to improve diagnostic accuracy. Experimental results show that our method demonstrated superior performance compared to existing one-shot federated learning methods in healthcare scenarios across four datasets with various data distributions. For instance, it surpasses existing one-shot federated learning approaches by more than 17.5% in accuracy on the RSNA dataset when applying a Dirichlet distribution with ($\alpha$ = 0.3). 

**Abstract (ZH)**: 联邦学习（FL）在医疗领域引起了广泛关注，因为它能够促进模型协作训练的同时保持数据隐私。然而，传统的FL方法通常需要多次通信轮次，导致显著的通信开销和延迟，尤其是在带宽有限的环境中。一次性联邦学习通过在单次通信轮次中进行模型训练和聚合，解决了这些问题，从而降低了通信成本并保持了隐私性。其中，一次性联邦集成学习结合了独立训练的客户端模型，并使用投票等集成技术进一步提高了在非IID数据场景中的性能。另一方面，现有医疗领域的机器学习方法主要使用单一模态数据（如医学图像或文本报告），这限制了它们的诊断准确性和全面性。因此，提出了集成多模态数据来弥补这些不足。在本文中，我们介绍了一种名为FedMME的创新一次性多模态联邦集成学习框架，该框架利用多模态数据进行医学图像分析。具体来说，FedMME利用愿景大型语言模型从医学图像生成文本报告，采用BERT模型从这些报告中提取文本特征，并将这些特征与视觉特征结合以提高诊断准确性。实验结果表明，与医疗场景中现有的一次性联邦学习方法相比，我们的方法在四个具有不同数据分布的数据库上表现更为优越。例如，当在RSNA数据集上采用狄利克雷分布（$\alpha$ = 0.3）时，其准确率优于现有的一次性联邦学习方法的17.5%以上。 

---