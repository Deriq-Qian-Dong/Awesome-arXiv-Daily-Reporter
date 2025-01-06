# Training Medical Large Vision-Language Models with Abnormal-Aware Feedback 

**Title (ZH)**: 带有异常意识反馈的医学大规模视觉-语言模型训练 

**Authors**: Yucheng Zhou, Lingran Song, Jianbing Shen  

**Link**: [PDF](https://arxiv.org/pdf/2501.01377)  

**Abstract**: Existing Medical Large Vision-Language Models (Med-LVLMs), which encapsulate extensive medical knowledge, demonstrate excellent capabilities in understanding medical images and responding to human queries based on these images. However, there remain challenges in visual localization in medical images, which is crucial for abnormality detection and interpretation. To address these issues, we propose a novel UMed-LVLM designed with Unveiling Medical abnormalities. Specifically, we collect a Medical Abnormalities Unveiling (MAU) dataset and propose a two-stage training method for UMed-LVLM training. To collect MAU dataset, we propose a prompt method utilizing the GPT-4V to generate diagnoses based on identified abnormal areas in medical images. Moreover, the two-stage training method includes Abnormal-Aware Instruction Tuning and Abnormal-Aware Rewarding, comprising Abnormal Localization Rewarding and Vision Relevance Rewarding. Experimental results demonstrate that our UMed-LVLM surpasses existing Med-LVLMs in identifying and understanding medical abnormality. In addition, this work shows that enhancing the abnormality detection capabilities of Med-LVLMs significantly improves their understanding of medical images and generalization capability. 

**Abstract (ZH)**: 现有的医学大型视觉语言模型（Med-LVLMs），它们整合了大量的医学知识，表现出在理解医学图像和基于这些图像回答人类查询方面出色的性能。然而，在医学图像中的视觉定位仍然是一个挑战，这对于异常检测和解释至关重要。为了解决这些问题，我们提出了一种名为UMed-LVLM的新颖模型，该模型旨在揭示医学异常。具体而言，我们收集了一个医学异常揭示（MAU）数据集，并提出了一种两阶段训练方法来训练UMed-LVLM。为了收集MAU数据集，我们提出了一种利用GPT-4V的提示方法，基于医学图像中识别出的异常区域生成诊断。此外，两阶段训练方法包括异常意识指令调优和异常意识奖励，具体包括异常定位奖励和视觉相关性奖励。实验结果表明，我们的UMed-LVLM在识别和理解医学异常方面优于现有的Med-LVLMs。此外，本研究还表明，增强Med-LVLMs的异常检测能力显著提高了它们对医学图像的理解能力和泛化能力。 

---
# Advancing Singlish Understanding: Bridging the Gap with Datasets and Multimodal Models 

**Title (ZH)**: 提升新加坡英语理解：借助数据集和多模态模型缩小差距 

**Authors**: Bin Wang, Xunlong Zou, Shuo Sun, Wenyu Zhang, Yingxu He, Zhuohan Liu, Chengwei Wei, Nancy F. Chen, AiTi Aw  

**Link**: [PDF](https://arxiv.org/pdf/2501.01034)  

**Abstract**: Singlish, a Creole language rooted in English, is a key focus in linguistic research within multilingual and multicultural contexts. However, its spoken form remains underexplored, limiting insights into its linguistic structure and applications. To address this gap, we standardize and annotate the largest spoken Singlish corpus, introducing the Multitask National Speech Corpus (MNSC). These datasets support diverse tasks, including Automatic Speech Recognition (ASR), Spoken Question Answering (SQA), Spoken Dialogue Summarization (SDS), and Paralinguistic Question Answering (PQA). We release standardized splits and a human-verified test set to facilitate further research. Additionally, we propose SingAudioLLM, a multi-task multimodal model leveraging multimodal large language models to handle these tasks concurrently. Experiments reveal our models adaptability to Singlish context, achieving state-of-the-art performance and outperforming prior models by 10-30% in comparison with other AudioLLMs and cascaded solutions. 

**Abstract (ZH)**: 新加坡话，这一源于英语的克里奥耳语言，在多语言和多文化背景下是语言研究的一个重要焦点。然而，其口语形式仍然没有得到充分探索，限制了对其语言结构和应用的理解。为弥补这一空白，我们标准化并标注了最大的新加坡话语料库，引入了多任务国家语音语料库（MNSC）。这些数据集支持多种任务，包括自动语音识别（ASR）、口语问答（SQA）、口语对话摘要（SDS）和副语言问答（PQA）。我们发布标准化的划分和经人工验证的测试集，以促进进一步的研究。此外，我们提出了SingAudioLLM，这是一种利用多模态大型语言模型的多任务多模态模型，能够同时处理这些任务。实验结果显示，我们的模型在新加坡话语境中的适应性更佳，实现了最先进的性能，并在与其他音频LLM和级联解决方案的对比中提升了10%到30%。 

---
# Negative to Positive Co-learning with Aggressive Modality Dropout 

**Title (ZH)**: 负向到正向的模态共学习方法结合激进模态丢弃 

**Authors**: Nicholas Magal, Minh Tran, Riku Arakawa, Suzanne Nie  

**Link**: [PDF](https://arxiv.org/pdf/2501.00865)  

**Abstract**: This paper aims to document an effective way to improve multimodal co-learning by using aggressive modality dropout. We find that by using aggressive modality dropout we are able to reverse negative co-learning (NCL) to positive co-learning (PCL). Aggressive modality dropout can be used to "prep" a multimodal model for unimodal deployment, and dramatically increases model performance during negative co-learning, where during some experiments we saw a 20% gain in accuracy. We also benchmark our modality dropout technique against PCL to show that our modality drop out technique improves co-learning during PCL, although it does not have as much as an substantial effect as it does during NCL. Github: this https URL 

**Abstract (ZH)**: 本文旨在通过使用激进模态 Dropout 方法记录一种提高多模态协同学习有效性的方式。我们发现，通过使用激进模态 Dropout，可以将负协同学习（NCL）转变为正协同学习（PCL）。激进模态 Dropout 可以用来“预热”多模态模型以备单模态部署，并在负协同学习期间显著提高模型性能，在某些实验中我们看到了高达 20% 准确率的提升。此外，我们将模态 Dropout 技术与 PCL 进行基准测试，以展示我们的模态 Dropout 技术在 PCL 中能够改善协同学习效果，尽管其效果不如在 NCL 中显著。GitHub 地址：[这里](this https URL) 

---
# Decoding the Flow: CauseMotion for Emotional Causality Analysis in Long-form Conversations 

**Title (ZH)**: 解码流变：CauseMotion在长篇对话中情感因果关系分析中的应用 

**Authors**: Yuxuan Zhang, Yulong Li, Zichen Yu, Feilong Tang, Zhixiang Lu, Chong Li, Kang Dang, Jionglong Su  

**Link**: [PDF](https://arxiv.org/pdf/2501.00778)  

**Abstract**: Long-sequence causal reasoning seeks to uncover causal relationships within extended time series data but is hindered by complex dependencies and the challenges of validating causal links. To address the limitations of large-scale language models (e.g., GPT-4) in capturing intricate emotional causality within extended dialogues, we propose CauseMotion, a long-sequence emotional causal reasoning framework grounded in Retrieval-Augmented Generation (RAG) and multimodal fusion. Unlike conventional methods relying only on textual information, CauseMotion enriches semantic representations by incorporating audio-derived features-vocal emotion, emotional intensity, and speech rate-into textual modalities. By integrating RAG with a sliding window mechanism, it effectively retrieves and leverages contextually relevant dialogue segments, thus enabling the inference of complex emotional causal chains spanning multiple conversational turns. To evaluate its effectiveness, we constructed the first benchmark dataset dedicated to long-sequence emotional causal reasoning, featuring dialogues with over 70 turns. Experimental results demonstrate that the proposed RAG-based multimodal integrated approach, the efficacy of substantially enhances both the depth of emotional understanding and the causal inference capabilities of large-scale language models. A GLM-4 integrated with CauseMotion achieves an 8.7% improvement in causal accuracy over the original model and surpasses GPT-4o by 1.2%. Additionally, on the publicly available DiaASQ dataset, CauseMotion-GLM-4 achieves state-of-the-art results in accuracy, F1 score, and causal reasoning accuracy. 

**Abstract (ZH)**: 长序列因果推理旨在揭示扩展时间序列数据中的因果关系，但由于复杂的依赖关系和验证因果链接的挑战而受到限制。为了克服大型语言模型（如GPT-4）在捕捉扩展对话中复杂情感因果关系方面的局限性，我们提出了CauseMotion，这是一种基于检索增强生成（RAG）和多模态融合的长序列情感因果推理框架。与仅依赖文本信息的传统方法不同，CauseMotion通过将音频提取的特征（即声情、情感强度和语速）融入文本模态中，丰富了语义表示。通过将RAG与滑动窗口机制结合，它有效地检索和利用上下文相关的话语片段，从而能够推断跨越多个对话回合的复杂情感因果链。为了评估其有效性，我们构建了首个专注于长序列情感因果推理的基准数据集，其中包含超过70个回合的对话。实验结果表明，基于RAG的多模态集成方法显著增强了大型语言模型的情感理解深度和因果推理能力。集成CauseMotion的GLM-4在因果准确性上比原模型提升了8.7%，并且超越了GPT-4o 1.2%。此外，在公开可用的DiaASQ数据集上，CauseMotion-GLM-4在准确率、F1分数和因果推理准确性方面达到了最先进的性能。 

---
# Exploring the Implicit Semantic Ability of Multimodal Large Language Models: A Pilot Study on Entity Set Expansion 

**Title (ZH)**: 探索多模态大型语言模型的隐含语义能力：一个关于实体集扩展的初步研究 

**Authors**: Hebin Wang, Yangning Li, Yinghui Li, Hai-Tao Zheng, Wenhao Jiang, Hong-Gee Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.00330)  

**Abstract**: The rapid development of multimodal large language models (MLLMs) has brought significant improvements to a wide range of tasks in real-world applications. However, LLMs still exhibit certain limitations in extracting implicit semantic information. In this paper, we apply MLLMs to the Multi-modal Entity Set Expansion (MESE) task, which aims to expand a handful of seed entities with new entities belonging to the same semantic class, and multi-modal information is provided with each entity. We explore the capabilities of MLLMs to understand implicit semantic information at the entity-level granularity through the MESE task, introducing a listwise ranking method LUSAR that maps local scores to global rankings. Our LUSAR demonstrates significant improvements in MLLM's performance on the MESE task, marking the first use of generative MLLM for ESE tasks and extending the applicability of listwise ranking. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）的快速发展已在众多实际应用任务中带来了显著的进展。然而，大型语言模型在提取隐含语义信息方面仍存在一定的局限性。本文将MLLMs应用到多模态实体集扩展（MESE）任务中，MESE任务旨在通过提供每个实体的多模态信息，扩展少量的种子实体至相同语义类的新实体。我们通过MESE任务探索MLLMs在实体级粒度上理解隐含语义信息的能力，并引入了一种列表式排名方法LUSAR，该方法将局部得分映射到全局排名。我们的LUSAR在MESE任务中显著提升了MLLMs的表现，标志着首次将生成型MLLMs应用于ESE任务，并扩展了列表式排名的应用范围。 

---
# A Breadth-First Catalog of Text Processing, Speech Processing and Multimodal Research in South Asian Languages 

**Title (ZH)**: 南亚语言文本处理、语音处理和多模态研究的广度优先目录 

**Authors**: Pranav Gupta  

**Link**: [PDF](https://arxiv.org/pdf/2501.00029)  

**Abstract**: We review the recent literature (January 2022- October 2024) in South Asian languages on text-based language processing, multimodal models, and speech processing, and provide a spotlight analysis focused on 21 low-resource South Asian languages, namely Saraiki, Assamese, Balochi, Bhojpuri, Bodo, Burmese, Chhattisgarhi, Dhivehi, Gujarati, Kannada, Kashmiri, Konkani, Khasi, Malayalam, Meitei, Nepali, Odia, Pashto, Rajasthani, Sindhi, and Telugu. We identify trends, challenges, and future research directions, using a step-wise approach that incorporates relevance classification and clustering based on large language models (LLMs). Our goal is to provide a breadth-first overview of the recent developments in South Asian language technologies to NLP researchers interested in working with South Asian languages. 

**Abstract (ZH)**: 我们回顾了2022年1月至2024年10月期间南亚语言中关于文本语言处理、多模态模型和语音处理的最新文献，并对包括21种低资源南亚语言（具体为：萨里基语、阿萨姆语、俾路支语、邦迪语、博多语、密支那语、恰蒂斯加尔语、 Divehi语、古吉拉特语、卡纳达语、克什米尔语、康枝尼语、卡西语、马拉雅拉姆语、密铁埃语、尼泊尔语、奥里亚语、普什图语、拉贾斯坦语、信德语和泰卢固语）的研究进行了重点分析。我们通过逐步方法识别趋势、挑战及未来研究方向，该方法结合了大规模语言模型（LLMs）的 relevance 分类和聚类。我们的目标是为对南亚语言感兴趣进行自然语言处理（NLP）研究的学者提供一个全面的近期南亚语言技术发展概述。 

---
# Unifying Specialized Visual Encoders for Video Language Models 

**Title (ZH)**: 统一专门视觉编码器以构建视频语言模型 

**Authors**: Jihoon Chung, Tyler Zhu, Max Gonzalez Saez-Diez, Juan Carlos Niebles, Honglu Zhou, Olga Russakovsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.01426)  

**Abstract**: The recent advent of Large Language Models (LLMs) has ushered sophisticated reasoning capabilities into the realm of video through Video Large Language Models (VideoLLMs). However, VideoLLMs currently rely on a single vision encoder for all of their visual processing, which limits the amount and type of visual information that can be conveyed to the LLM. Our method, MERV, Multi-Encoder Representation of Videos, instead leverages multiple frozen visual encoders to create a unified representation of a video, providing the VideoLLM with a comprehensive set of specialized visual knowledge. Spatio-temporally aligning the features from each encoder allows us to tackle a wider range of open-ended and multiple-choice video understanding questions and outperform prior state-of-the-art works. MERV is up to 3.7% better in accuracy than Video-LLaVA across the standard suite video understanding benchmarks, while also having a better Video-ChatGPT score. We also improve upon SeViLA, the previous best on zero-shot Perception Test accuracy, by 2.2%. MERV introduces minimal extra parameters and trains faster than equivalent single-encoder methods while parallelizing the visual processing. Finally, we provide qualitative evidence that MERV successfully captures domain knowledge from each of its encoders. Our results offer promising directions in utilizing multiple vision encoders for comprehensive video understanding. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）的兴起为视频领域带来了复杂的推理能力，通过Video Large Language Models（VideoLLMs）实现了这一目标。然而，目前VideoLLMs在视觉处理方面仍然依赖单一的视觉编码器，这限制了传递给LLM的视觉信息的数量和类型。我们提出的方法，即MERV（Multi-Encoder Representation of Videos），采用多个冻结的视觉编码器来创建视频的统一表示，为VideoLLM提供了一套全面的专业视觉知识。通过时空对齐每个编码器的特征，MERV能够应对更加开放和多元的视频理解问题，并在先前的先进工作基础上取得了更好的性能。与Video-LLaVA相比，MERV在标准视频理解基准上的准确率提高了3.7%，同时具有更好的Video-ChatGPT评分。我们在零样本感知测试中的准确率上也超越了此前最佳的SeViLA，提高了2.2%。MERV引入了极少的额外参数，训练速度也快于同等单编码器方法，同时实现了视觉处理的并行化。最后，我们提供了定性的证据，证明MERV成功地从每个编码器中捕获了领域知识。我们的研究结果为利用多个视觉编码器进行全面视频理解提供了令人鼓舞的方向。 

---
# Large Vision-Language Model Alignment and Misalignment: A Survey Through the Lens of Explainability 

**Title (ZH)**: 大规模多模态模型的一致性与分歧：基于可解释性视角的综述 

**Authors**: Dong Shu, Haiyan Zhao, Jingyu Hu, Weiru Liu, Lu Cheng, Mengnan Du  

**Link**: [PDF](https://arxiv.org/pdf/2501.01346)  

**Abstract**: Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities in processing both visual and textual information. However, the critical challenge of alignment between visual and linguistic representations is not fully understood. This survey presents a comprehensive examination of alignment and misalignment in LVLMs through an explainability lens. We first examine the fundamentals of alignment, exploring its representational and behavioral aspects, training methodologies, and theoretical foundations. We then analyze misalignment phenomena across three semantic levels: object, attribute, and relational misalignment. Our investigation reveals that misalignment emerges from challenges at multiple levels: the data level, the model level, and the inference level. We provide a comprehensive review of existing mitigation strategies, categorizing them into parameter-frozen and parameter-tuning approaches. Finally, we outline promising future research directions, emphasizing the need for standardized evaluation protocols and in-depth explainability studies. 

**Abstract (ZH)**: 大型多模态语言视觉模型（LVLMs）在处理视觉和文本信息方面展现了卓越的能力。然而，视觉和语言表示之间的对齐问题尚未完全理解。本文综述通过解释性视角全面探讨了LVLMs中的对齐与不对齐问题。我们首先探讨了对齐的基本原理，包括其表示和行为方面的特点、训练方法以及理论基础。随后，我们将分析从物体、属性到关系三个语义层次的不对齐现象。我们的研究揭示出，不对齐现象源自多个层面的挑战：数据层面、模型层面和推理层面。我们提供了一个对现有缓解策略的全面回顾，并将这些策略分为参数冻结和参数调优两类。最后，我们指出了未来研究有希望的方向，强调需要标准化的评估协议和深入的解释性研究。 

---
# CultureVLM: Characterizing and Improving Cultural Understanding of Vision-Language Models for over 100 Countries 

**Title (ZH)**: CultureVLM: 表征和提升视觉语言模型在100多个国家的文化理解能力 

**Authors**: Shudong Liu, Yiqiao Jin, Cheng Li, Derek F. Wong, Qingsong Wen, Lichao Sun, Haipeng Chen, Xing Xie, Jindong Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01282)  

**Abstract**: Vision-language models (VLMs) have advanced human-AI interaction but struggle with cultural understanding, often misinterpreting symbols, gestures, and artifacts due to biases in predominantly Western-centric training data. In this paper, we construct CultureVerse, a large-scale multimodal benchmark covering 19, 682 cultural concepts, 188 countries/regions, 15 cultural concepts, and 3 question types, with the aim of characterizing and improving VLMs' multicultural understanding capabilities. Then, we propose CultureVLM, a series of VLMs fine-tuned on our dataset to achieve significant performance improvement in cultural understanding. Our evaluation of 16 models reveals significant disparities, with a stronger performance in Western concepts and weaker results in African and Asian contexts. Fine-tuning on our CultureVerse enhances cultural perception, demonstrating cross-cultural, cross-continent, and cross-dataset generalization without sacrificing performance on models' general VLM benchmarks. We further present insights on cultural generalization and forgetting. We hope that this work could lay the foundation for more equitable and culturally aware multimodal AI systems. 

**Abstract (ZH)**: 视觉语言模型（VLMs）在促进人机交互方面取得了进展，但在文化理解方面存在困难，常因训练数据偏向于西方文化而误解符号、手势和文物。本论文旨在构建CultureVerse，一个大规模多模态基准，涵盖19,682个文化概念、188个国家/地区、15个文化概念和3种问题类型，旨在表征并提升VLMs的多文化理解能力。随后，我们提出CultureVLM，一系列在我们的数据集上进行微调的VLMs，以显著提高其文化理解能力。对16种模型的评价结果表明，这些模型在西方概念理解上表现出色，但在非洲和亚洲背景下的表现较弱。在我们的CultureVerse上进行微调可以提升文化感知能力，展示了跨文化、跨洲际和跨数据集的一般化能力，而不会牺牲模型在通用VLM基准测试中的表现。我们进一步提出了关于文化一般化和遗忘的洞见。我们希望这项工作能够为更加公正和文化意识强烈的多模态AI系统的构建奠定基础。 

---
# Face-Human-Bench: A Comprehensive Benchmark of Face and Human Understanding for Multi-modal Assistants 

**Title (ZH)**: Face-Human-Bench：多模态助手中人脸和人类理解的综合基准 

**Authors**: Lixiong Qin, Shilong Ou, Miaoxuan Zhang, Jiangning Wei, Yuhang Zhang, Xiaoshuai Song, Yuchen Liu, Mei Wang, Weiran Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01243)  

**Abstract**: Faces and humans are crucial elements in social interaction and are widely included in everyday photos and videos. Therefore, a deep understanding of faces and humans will enable multi-modal assistants to achieve improved response quality and broadened application scope. Currently, the multi-modal assistant community lacks a comprehensive and scientific evaluation of face and human understanding abilities. In this paper, we first propose a hierarchical ability taxonomy that includes three levels of abilities. Then, based on this taxonomy, we collect images and annotations from publicly available datasets in the face and human community and build a semi-automatic data pipeline to produce problems for the new benchmark. Finally, the obtained Face-Human-Bench comprises a development set with 900 problems and a test set with 1800 problems, supporting both English and Chinese. We conduct evaluations over 25 mainstream multi-modal large language models (MLLMs) with our Face-Human-Bench, focusing on the correlation between abilities, the impact of the relative position of targets on performance, and the impact of Chain of Thought (CoT) prompting on performance. Moreover, inspired by multi-modal agents, we also explore which abilities of MLLMs need to be supplemented by specialist models. 

**Abstract (ZH)**: 人类和面部在社交互动中至关重要，并广泛出现在日常生活中的照片和视频中。因此，对人类和面部的深刻理解将使多模态助手在响应质量和应用范围上得到增强。目前，多模态助手社区缺乏对面部和人类理解能力的全面和科学评估。本文中，我们首先提出了一种分层能力分类体系，包括三个能力层级。然后，基于此分类体系，我们从面部和人体社区的公开数据集中收集图像和标注，并构建了一种半自动数据处理管道以生成新基准的问题。最后，所获得的Face-Human-Bench包括一个包含900个问题的开发集和一个包含1800个问题的测试集，支持英文和中文。我们使用我们的Face-Human-Bench对25个主流多模态大型语言模型（MLLM）进行了评估，重点关注能力之间的相关性、目标相对位置对性能的影响以及思维链（Chain of Thought，CoT）提示对性能的影响。此外，借鉴多模态代理的研究，我们还探讨了哪些MLLM的能力需要由专门模型补充。 

---
# 2.5 Years in Class: A Multimodal Textbook for Vision-Language Pretraining 

**Title (ZH)**: 2.5年在校时间：一种用于视觉-语言预训练的多模态教材 

**Authors**: Wenqi Zhang, Hang Zhang, Xin Li, Jiashuo Sun, Yongliang Shen, Weiming Lu, Deli Zhao, Yueting Zhuang, Lidong Bing  

**Link**: [PDF](https://arxiv.org/pdf/2501.00958)  

**Abstract**: Compared to image-text pair data, interleaved corpora enable Vision-Language Models (VLMs) to understand the world more naturally like humans. However, such existing datasets are crawled from webpage, facing challenges like low knowledge density, loose image-text relations, and poor logical coherence between images. On the other hand, the internet hosts vast instructional videos (e.g., online geometry courses) that are widely used by humans to learn foundational subjects, yet these valuable resources remain underexplored in VLM training. In this paper, we introduce a high-quality \textbf{multimodal textbook} corpus with richer foundational knowledge for VLM pretraining. It collects over 2.5 years of instructional videos, totaling 22,000 class hours. We first use an LLM-proposed taxonomy to systematically gather instructional videos. Then we progressively extract and refine visual (keyframes), audio (ASR), and textual knowledge (OCR) from the videos, and organize as an image-text interleaved corpus based on temporal order. Compared to its counterparts, our video-centric textbook offers more coherent context, richer knowledge, and better image-text alignment. Experiments demonstrate its superb pretraining performance, particularly in knowledge- and reasoning-intensive tasks like ScienceQA and MathVista. Moreover, VLMs pre-trained on our textbook exhibit outstanding interleaved context awareness, leveraging visual and textual cues in their few-shot context for task solving~\footnote{Our code are available at \url{this https URL}}. 

**Abstract (ZH)**: 与图像-文本对数据相比，交错语料库使视觉-语言模型（VLMs）能够更自然地理解世界，类似于人类的理解方式。然而，现有的这类数据集是从网页上爬取的，面临着知识密度低、图像-文本关系松散和图像间的逻辑连贯性差等挑战。另一方面，互联网上存在大量的教学视频（例如，网上几何课程），这些视频在人类学习基础科目时被广泛使用，但这些宝贵资源在VLM训练中尚未得到充分挖掘。在本文中，我们介绍了一个高质量的多模态教材语料库，它为VLM预训练提供了更加丰富的基础知识。该语料库收集了超过两年半的教学视频，总计22,000课时。我们首先使用一个语言模型（LLM）提出的分类体系，系统地收集教学视频。然后，我们逐步从视频中提取和精炼视觉（关键帧）、音频（语音识别）和文本知识（光学字符识别），并根据时间顺序组织成交错的图像-文本语料库。与同类数据集相比，我们以视频为中心的教材提供了更为连贯的上下文、更丰富的内容以及更好的图像-文本对齐。实验结果表明，该语料库在科学问答（ScienceQA）和数学视野（MathVista）等知识密集和推理密集的任务上的预训练性能尤为出色。此外，基于我们教材预训练的VLM在处理任务时能够更好地利用视觉和文本提示来理解交错的上下文（注释\footnote{我们的代码可在\url{这个链接}下载}）。 

---
# Unleashing Text-to-Image Diffusion Prior for Zero-Shot Image Captioning 

**Title (ZH)**: 释放文本到图像扩散先验以实现零样本图像配描述 

**Authors**: Jianjie Luo, Jingwen Chen, Yehao Li, Yingwei Pan, Jianlin Feng, Hongyang Chao, Ting Yao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00437)  

**Abstract**: Recently, zero-shot image captioning has gained increasing attention, where only text data is available for training. The remarkable progress in text-to-image diffusion model presents the potential to resolve this task by employing synthetic image-caption pairs generated by this pre-trained prior. Nonetheless, the defective details in the salient regions of the synthetic images introduce semantic misalignment between the synthetic image and text, leading to compromised results. To address this challenge, we propose a novel Patch-wise Cross-modal feature Mix-up (PCM) mechanism to adaptively mitigate the unfaithful contents in a fine-grained manner during training, which can be integrated into most of encoder-decoder frameworks, introducing our PCM-Net. Specifically, for each input image, salient visual concepts in the image are first detected considering the image-text similarity in CLIP space. Next, the patch-wise visual features of the input image are selectively fused with the textual features of the salient visual concepts, leading to a mixed-up feature map with less defective content. Finally, a visual-semantic encoder is exploited to refine the derived feature map, which is further incorporated into the sentence decoder for caption generation. Additionally, to facilitate the model training with synthetic data, a novel CLIP-weighted cross-entropy loss is devised to prioritize the high-quality image-text pairs over the low-quality counterparts. Extensive experiments on MSCOCO and Flickr30k datasets demonstrate the superiority of our PCM-Net compared with state-of-the-art VLMs-based approaches. It is noteworthy that our PCM-Net ranks first in both in-domain and cross-domain zero-shot image captioning. The synthetic dataset SynthImgCap and code are available at this https URL. 

**Abstract (ZH)**: 近年来，零样本图像标注得到了越来越多的关注，其中仅使用文本数据进行训练。文本到图像的扩散模型的显著进展为通过使用由预训练模型生成的合成图像-描述对来解决这一问题提供了可能。然而，合成图像中的缺陷细节在显著区域引入了合成图像与文本之间的语义错配，导致生成的结果不佳。为了解决这一挑战，我们提出了一种新颖的Patch-wise跨模态特征Mix-up (PCM)机制，在训练过程中以细粒度的方式自适应地减轻不忠实的内容，该机制可以整合到多数编码-解码框架中，形成我们的PCM-Net。具体来说，对于每个输入图像，首先在CLIP空间中考虑图像-文本相似性来检测图像中的显著视觉概念。接着，输入图像的局部视觉特征与显著视觉概念的文本特征选择性地融合，形成一个内容较少有缺陷的混合特征图。最后，利用视觉-语义编码器对生成的特征图进行细化，并进一步将其整合到句子解码器中进行描述生成。此外，为了便于使用合成数据进行模型训练，我们设计了一种新颖的CLIP加权交叉熵损失函数，优先选择高质量的图像-文本对。在MSCOCO和Flickr30k数据集上的 extensive 实验表明，我们提出的PCM-Net 在与最先进的基于语义-视觉模型的方法相比时表现出更好的性能。值得注意的是，我们的PCM-Net在领域内和跨领域零样本图像标注中均排名第一。合成数据集 SynthImgCap 和代码可通过以下链接获得：[提供的链接]。 

---
# MLLM-as-a-Judge for Image Safety without Human Labeling 

**Title (ZH)**: 将以下论文的内容或标题翻译成中文，同时确保符合学术规范：

“MLLM-as-a-Judge 无须人工标注的图像安全性评估”

说明：
- “MLLM”可能是指多模态大型语言模型（Multimodal Large Language Model），因此这里将其翻译为“MLLM”以保持原文缩写的完整性。
- “as a Judge”在这里指的是“作为评估者”。
- “无须人工标注”是对“without Human Labeling”的翻译，符合学术写作中的表达习惯。
- “图像安全性评估”是对“Image Safety”的翻译。 

**Authors**: Zhenting Wang, Shuming Hu, Shiyu Zhao, Xiaowen Lin, Felix Juefei-Xu, Zhuowei Li, Ligong Han, Harihar Subramanyam, Li Chen, Jianfa Chen, Nan Jiang, Lingjuan Lyu, Shiqing Ma, Dimitris N. Metaxas, Ankit Jain  

**Link**: [PDF](https://arxiv.org/pdf/2501.00192)  

**Abstract**: Image content safety has become a significant challenge with the rise of visual media on online platforms. Meanwhile, in the age of AI-generated content (AIGC), many image generation models are capable of producing harmful content, such as images containing sexual or violent material. Thus, it becomes crucial to identify such unsafe images based on established safety rules. Pre-trained Multimodal Large Language Models (MLLMs) offer potential in this regard, given their strong pattern recognition abilities. Existing approaches typically fine-tune MLLMs with human-labeled datasets, which however brings a series of drawbacks. First, relying on human annotators to label data following intricate and detailed guidelines is both expensive and labor-intensive. Furthermore, users of safety judgment systems may need to frequently update safety rules, making fine-tuning on human-based annotation more challenging. This raises the research question: Can we detect unsafe images by querying MLLMs in a zero-shot setting using a predefined safety constitution (a set of safety rules)? Our research showed that simply querying pre-trained MLLMs does not yield satisfactory results. This lack of effectiveness stems from factors such as the subjectivity of safety rules, the complexity of lengthy constitutions, and the inherent biases in the models. To address these challenges, we propose a MLLM-based method includes objectifying safety rules, assessing the relevance between rules and images, making quick judgments based on debiased token probabilities with logically complete yet simplified precondition chains for safety rules, and conducting more in-depth reasoning with cascaded chain-of-thought processes if necessary. Experiment results demonstrate that our method is highly effective for zero-shot image safety judgment tasks. 

**Abstract (ZH)**: 随着在线平台上视觉媒体的兴起，图像内容安全已成为一项重大挑战。同时，在人工智能生成内容（AIGC）的时代，许多图像生成模型能够生成有害内容，如包含色情或暴力的图像。因此，基于现有的安全规则识别此类不安全图像变得至关重要。预训练的多模态大型语言模型（MLLMs）在这方面具有潜力，因其具有强大的模式识别能力。现有的方法通常会使用人工标注的数据集对MLLMs进行微调，但这种方法带来了许多缺点。首先，依靠人工注释员按照复杂的详细指南标注数据既昂贵又耗时。此外，使用安全评估系统的用户可能需要频繁更新安全规则，使得基于人工标注的微调更加困难。这提出了一个问题：我们是否可以在零样本设置中通过查询预训练的MLLMs并使用预定义的安全宪法（一组安全规则）来检测不安全图像？我们的研究结果显示，仅仅通过查询预训练的MLLMs并不能取得满意的效果。这种无效性主要源于安全规则的主观性、宪法的复杂性以及模型本身的固有偏差。为解决这些挑战，我们提出了一种基于MLLMs的方法，该方法包括客观化安全规则、评估规则与图像的相关性、基于去偏置的令牌概率进行快速判断，并使用逻辑完整但简化的情境链来确定安全规则，必要时进行更深入的递进式推理。实验结果表明，我们的方法在零样本图像安全判断任务中非常有效。 

---
# On the Robustness of Cover Version Identification Models: A Study Using Cover Versions from YouTube 

**Title (ZH)**: 关于Cover Version Identification模型的鲁棒性研究：基于YouTube的Cover版本数据 

**Authors**: Simon Hachmeier, Robert Jäschke  

**Link**: [PDF](https://arxiv.org/pdf/2501.01333)  

**Abstract**: Recent advances in cover song identification have shown great success. However, models are usually tested on a fixed set of datasets which are relying on the online cover song database SecondHandSongs. It is unclear how well models perform on cover songs on online video platforms, which might exhibit alterations that are not expected. In this paper, we annotate a subset of songs from YouTube sampled by a multi-modal uncertainty sampling approach and evaluate state-of-the-art models. We find that existing models achieve significantly lower ranking performance on our dataset compared to a community dataset. We additionally measure the performance of different types of versions (e.g., instrumental versions) and find several types that are particularly hard to rank. Lastly, we provide a taxonomy of alterations in cover versions on the web. 

**Abstract (ZH)**: 近年来，音乐覆盖识别领域的研究取得了显著成果。然而，这些模型通常仅在依赖于SecondHandSongs在线曲目数据库的一组固定数据集上进行测试。对于在线视频平台上出现的覆盖歌曲，模型的表现情况尚不清楚，这些歌曲可能存在不可预期的修改。本文采用多模态不确定性抽样方法从YouTube中选定一部分歌曲进行标注，并评估当前最先进的模型。我们发现，现有模型在我们数据集上的排名性能显著低于社区数据集中的性能。此外，我们还测量了不同版本（如纯乐器版本）的性能，并发现一些特定类型的版本尤其难以进行排名。最后，我们提供了一份网络中覆盖版本修改类型的分类体系。 

---
# Fine-grained Video-Text Retrieval: A New Benchmark and Method 

**Title (ZH)**: 细粒度视频-文本检索：一个新的基准和方法 

**Authors**: Yifan Xu, Xinhao Li, Yichun Yang, Rui Huang, Limin Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00513)  

**Abstract**: The ability of perceiving fine-grained spatial and temporal information is crucial for video-language retrieval. However, the existing video retrieval benchmarks, such as MSRVTT and MSVD, fail to efficiently evaluate the fine-grained retrieval ability of video-language models (VLMs) due to a lack of detailed annotations. To address this problem, we present FIBER, a FIne-grained BEnchmark for text to video Retrieval, containing 1,000 videos sourced from the FineAction dataset. Uniquely, our FIBER benchmark provides detailed human-annotated spatial annotations and temporal annotations for each video, making it possible to independently evaluate the spatial and temporal bias of VLMs on video retrieval task. Besides, we employ a text embedding method to unlock the capability of fine-grained video-language understanding of Multimodal Large Language Models (MLLMs). Surprisingly, the experiment results show that our Video Large Language Encoder (VLLE) performs comparably to CLIP-based models on traditional benchmarks and has a stronger capability of fine-grained representation with lower spatial-temporal bias. Project page: this https URL. 

**Abstract (ZH)**: 对细粒度空间和时间信息的感知能力对于视频-语言检索至关重要。然而，现有的视频检索基准，如MSRVTT和MSVD，未能有效评估视频-语言模型（VLMs）的细粒度检索能力，原因在于缺乏详细的标注。为解决这一问题，我们提出了FIBER（细粒度文本到视频检索基准），该基准包含来自FineAction数据集的1000个视频。独特之处在于，我们的FIBER基准提供了每个视频的详细的人工标注空间注释和时间注释，使得可以独立评估VLMs在视频检索任务中对空间和时间偏见的处理能力。此外，我们采用了文本嵌入方法，解锁了多模态大语言模型（MLLMs）对细粒度视频-语言理解的能力。令人惊讶的是，实验结果表明，我们的视频大语言编码器（VLLE）在传统基准上的表现与基于CLIP的模型相当，并且具有更低的空间-时间偏见和更强的细粒度表征能力。项目页面：[请将提供的URL补充完整]。 

---
# Beyond Text: Implementing Multimodal Large Language Model-Powered Multi-Agent Systems Using a No-Code Platform 

**Title (ZH)**: 超越文本：使用无代码平台实现基于大型语言模型的多模态多代理系统 

**Authors**: Cheonsu Jeong  

**Link**: [PDF](https://arxiv.org/pdf/2501.00750)  

**Abstract**: This study proposes the design and implementation of a multimodal LLM-based Multi-Agent System (MAS) leveraging a No-Code platform to address the practical constraints and significant entry barriers associated with AI adoption in enterprises. Advanced AI technologies, such as Large Language Models (LLMs), often pose challenges due to their technical complexity and high implementation costs, making them difficult for many organizations to adopt. To overcome these limitations, this research develops a No-Code-based Multi-Agent System designed to enable users without programming knowledge to easily build and manage AI systems. The study examines various use cases to validate the applicability of AI in business processes, including code generation from image-based notes, Advanced RAG-based question-answering systems, text-based image generation, and video generation using images and prompts. These systems lower the barriers to AI adoption, empowering not only professional developers but also general users to harness AI for significantly improved productivity and efficiency. By demonstrating the scalability and accessibility of No-Code platforms, this study advances the democratization of AI technologies within enterprises and validates the practical applicability of Multi-Agent Systems, ultimately contributing to the widespread adoption of AI across various industries. 

**Abstract (ZH)**: 本研究提出了一种利用无代码平台设计和实现基于多模态大型语言模型（LLM）的多代理系统（MAS），以解决企业在采用人工智能时所面临的实际限制和显著进入壁垒。先进的AI技术，如大型语言模型（LLMs），往往由于其技术复杂性和高昂的实施成本而带来挑战，使得许多组织难以采用。为克服这些限制，本研究开发了一种基于无代码的多代理系统，旨在使不具备编程知识的用户能够轻松构建和管理AI系统。研究探讨了多种应用场景来验证AI在业务流程中的适用性，包括基于图像笔记的代码生成、基于高级检索与生成（RAG）的问题回答系统、基于文本的图像生成，以及使用图像和提示生成视频系统。这些系统降低了AI的采用门槛，不仅赋能专业的开发人员，还赋能普通用户利用AI来显著提高生产力和效率。通过展示无代码平台的扩展性和可访问性，本研究推动了企业内部AI技术的民主化，并验证了多代理系统的实际适用性，最终促进了AI在各行业的广泛采用。 

---
# Multi-Modal Video Feature Extraction for Popularity Prediction 

**Title (ZH)**: 多模态视频特征提取及其对流行度预测的应用 

**Authors**: Haixu Liu, Wenning Wang, Haoxiang Zheng, Penghao Jiang, Qirui Wang, Ruiqing Yan, Qiuzhuang Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.01422)  

**Abstract**: This work aims to predict the popularity of short videos using the videos themselves and their related features. Popularity is measured by four key engagement metrics: view count, like count, comment count, and share count. This study employs video classification models with different architectures and training methods as backbone networks to extract video modality features. Meanwhile, the cleaned video captions are incorporated into a carefully designed prompt framework, along with the video, as input for video-to-text generation models, which generate detailed text-based video content understanding. These texts are then encoded into vectors using a pre-trained BERT model. Based on the six sets of vectors mentioned above, a neural network is trained for each of the four prediction metrics. Moreover, the study conducts data mining and feature engineering based on the video and tabular data, constructing practical features such as the total frequency of hashtag appearances, the total frequency of mention appearances, video duration, frame count, frame rate, and total time online. Multiple machine learning models are trained, and the most stable model, XGBoost, is selected. Finally, the predictions from the neural network and XGBoost models are averaged to obtain the final result. 

**Abstract (ZH)**: 本文旨在利用短视频及其相关特征预测其受欢迎程度。受欢迎程度通过四个关键的参与度指标进行衡量：播放量、点赞量、评论量和分享量。本研究采用具有不同架构和训练方法的视频分类模型作为骨干网络，以提取视频模态特征。同时，经过清洗的视频字幕被整合进一个精心设计的提示框架中，与视频一起作为输入，用于生成视频到文本的模型，生成详细的基于文本的视频内容理解。这些文本随后通过预训练的BERT模型编码成向量。基于上述六组向量，分别训练了四个预测指标的神经网络。此外，本研究基于视频和表格数据进行了数据挖掘和特征工程，构建了诸如标签出现的总频率、提及出现的总频率、视频时长、帧数、帧率和上线总时长等实用特征。多种机器学习模型被训练，最终选定了稳定性最佳的XGBoost模型。最后，神经网络和XGBoost模型的预测结果被平均，获得最终预测结果。 

---
# Retrieval-Augmented Dynamic Prompt Tuning for Incomplete Multimodal Learning 

**Title (ZH)**: 基于检索增强的动态提示调优方法用于不完整多模态学习 

**Authors**: Jian Lang, Zhangtao Cheng, Ting Zhong, Fan Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2501.01120)  

**Abstract**: Multimodal learning with incomplete modality is practical and challenging. Recently, researchers have focused on enhancing the robustness of pre-trained MultiModal Transformers (MMTs) under missing modality conditions by applying learnable prompts. However, these prompt-based methods face several limitations: (1) incomplete modalities provide restricted modal cues for task-specific inference, (2) dummy imputation for missing content causes information loss and introduces noise, and (3) static prompts are instance-agnostic, offering limited knowledge for instances with various missing conditions. To address these issues, we propose RAGPT, a novel Retrieval-AuGmented dynamic Prompt Tuning framework. RAGPT comprises three modules: (I) the multi-channel retriever, which identifies similar instances through a within-modality retrieval strategy, (II) the missing modality generator, which recovers missing information using retrieved contexts, and (III) the context-aware prompter, which captures contextual knowledge from relevant instances and generates dynamic prompts to largely enhance the MMT's robustness. Extensive experiments conducted on three real-world datasets show that RAGPT consistently outperforms all competitive baselines in handling incomplete modality problems. The code of our work and prompt-based baselines is available at this https URL. 

**Abstract (ZH)**: 不完整模态下的多模态学习既具实践性又具挑战性。最近，研究人员专注于通过应用可学习的提示来增强预训练多模态变换器（MMTs）在缺失模态条件下的鲁棒性。然而，这些基于提示的方法存在一些限制：（1）不完整的模态提供了有限的模态线索进行任务特定推理，（2）对缺失内容的虚假填充会导致信息丢失并引入噪声，（3）静态提示缺乏实例意识，对于各种缺失条件的实例提供的知识有限。为了解决这些问题，我们提出了RAGPT，一种新颖的检索增强动态提示调优框架。RAGPT 包含三个模块：（I）多通道检索器，通过在模态内检索策略来识别相似实例，（II）缺失模态生成器，使用检索到的上下文恢复缺失信息，（III）上下文感知提示器，从相关实例中捕捉上下文知识并生成动态提示，以大大增强 MMT 的鲁棒性。在三个实际数据集上进行的大量实验表明，RAGPT 一致地优于所有竞争基线，处理不完整模态问题。我们工作的代码和基于提示的基线可以从以下链接获取：this https URL。 

---
# MMVA: Multimodal Matching Based on Valence and Arousal across Images, Music, and Musical Captions 

**Title (ZH)**: MMVA：基于 valence 和 arousal 的多模态匹配研究——跨图像、音乐和音乐描述 

**Authors**: Suhwan Choi, Kyu Won Kim, Myungjoo Kang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01094)  

**Abstract**: We introduce Multimodal Matching based on Valence and Arousal (MMVA), a tri-modal encoder framework designed to capture emotional content across images, music, and musical captions. To support this framework, we expand the Image-Music-Emotion-Matching-Net (IMEMNet) dataset, creating IMEMNet-C which includes 24,756 images and 25,944 music clips with corresponding musical captions. We employ multimodal matching scores based on the continuous valence (emotional positivity) and arousal (emotional intensity) values. This continuous matching score allows for random sampling of image-music pairs during training by computing similarity scores from the valence-arousal values across different modalities. Consequently, the proposed approach achieves state-of-the-art performance in valence-arousal prediction tasks. Furthermore, the framework demonstrates its efficacy in various zeroshot tasks, highlighting the potential of valence and arousal predictions in downstream applications. 

**Abstract (ZH)**: 我们介绍了一种基于情感唤起和唤醒的多模态匹配模型（MMVA），这是一个三模态编码框架，旨在跨图像、音乐和音乐字幕捕捉情感内容。为支持这一框架，我们扩展了Image-Music-Emotion-Matching-Net (IMEMNet) 数据集，创建了IMEMNet-C，其中包括24,756张图像和25,944个音乐片段以及对应的音乐字幕。我们采用基于连续情感正性（情感积极程度）和唤醒（情感强度）的多模态匹配分数。这种连续匹配分数允许在训练过程中通过计算不同模态间唤起-唤醒值的相似性分数来进行随机采样图像-音乐配对。因此，所提出的方法在情感唤起-唤醒预测任务中达到了最先进的性能。此外，该框架在各种零样本任务中展示了其有效性，突显了情感正性和唤醒预测在下游应用中的潜力。 

---
# Adventures in Demand Analysis Using AI 

**Title (ZH)**: 使用AI进行需求分析的探险之旅 

**Authors**: Philipp Bach, Victor Chernozhukov, Sven Klaassen, Martin Spindler, Jan Teichert-Kluge, Suhas Vijaykumar  

**Link**: [PDF](https://arxiv.org/pdf/2501.00382)  

**Abstract**: This paper advances empirical demand analysis by integrating multimodal product representations derived from artificial intelligence (AI). Using a detailed dataset of toy cars on \textit{this http URL}, we combine text descriptions, images, and tabular covariates to represent each product using transformer-based embedding models. These embeddings capture nuanced attributes, such as quality, branding, and visual characteristics, that traditional methods often struggle to summarize. Moreover, we fine-tune these embeddings for causal inference tasks. We show that the resulting embeddings substantially improve the predictive accuracy of sales ranks and prices and that they lead to more credible causal estimates of price elasticity. Notably, we uncover strong heterogeneity in price elasticity driven by these product-specific features. Our findings illustrate that AI-driven representations can enrich and modernize empirical demand analysis. The insights generated may also prove valuable for applied causal inference more broadly. 

**Abstract (ZH)**: 本文通过将多种模态的产品表示整合到经验需求分析中，推动了该领域的进步。这些产品表示是从人工智能（AI）中提取的，我们使用一个详细的玩具车数据集（\textit{参见网址: ...}），结合文本描述、图像和表格式协变量来表示每个产品，采用基于转换器的嵌入模型。这些嵌入模型能够捕捉到传统方法难以总结的细微特性，如质量、品牌和视觉特征。此外，我们还将这些嵌入模型微调用于因果推断任务。研究显示，由此产生的嵌入模型在销售排名和价格预测准确性方面有了显著提升，并且能够产生更可信的价格弹性因果估计。值得注意的是，这些产品特定特征导致了显著的价格弹性异质性。我们的研究结果表明，AI驱动的表示可以丰富和现代化工症需求分析。生成的见解也可能对更广泛的实证因果推断有所帮助。 

---
# OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning 

**Title (ZH)**: OCRBench v2：用于评估大型多模态模型在视觉文本定位与推理方面性能的改进基准 

**Authors**: Ling Fu, Biao Yang, Zhebin Kuang, Jiajun Song, Yuzhe Li, Linghao Zhu, Qidi Luo, Xinyu Wang, Hao Lu, Mingxin Huang, Zhang Li, Guozhi Tang, Bin Shan, Chunhui Lin, Qi Liu, Binghong Wu, Hao Feng, Hao Liu, Can Huang, Jingqun Tang, Wei Chen, Lianwen Jin, Yuliang Liu, Xiang Bai  

**Link**: [PDF](https://arxiv.org/pdf/2501.00321)  

**Abstract**: Scoring the Optical Character Recognition (OCR) capabilities of Large Multimodal Models (LMMs) has witnessed growing interest recently. Existing benchmarks have highlighted the impressive performance of LMMs in text recognition; however, their abilities on certain challenging tasks, such as text localization, handwritten content extraction, and logical reasoning, remain underexplored. To bridge this gap, we introduce OCRBench v2, a large-scale bilingual text-centric benchmark with currently the most comprehensive set of tasks (4x more tasks than the previous multi-scene benchmark OCRBench), the widest coverage of scenarios (31 diverse scenarios including street scene, receipt, formula, diagram, and so on), and thorough evaluation metrics, with a total of 10,000 human-verified question-answering pairs and a high proportion of difficult samples. After carefully benchmarking state-of-the-art LMMs on OCRBench v2, we find that 20 out of 22 LMMs score below 50 (100 in total) and suffer from five-type limitations, including less frequently encountered text recognition, fine-grained perception, layout perception, complex element parsing, and logical reasoning. The benchmark and evaluation scripts are available at this https URL. 

**Abstract (ZH)**: 近年来，对大型多模态模型（LMMs）的光学字符识别（OCR）能力进行评分的兴趣逐渐增加。现有的基准测试突出显示了LMMs在文本识别方面令人印象深刻的性能，但它们在某些具有挑战性的任务，如文本定位、手写内容提取和逻辑推理方面的能力尚未得到充分探索。为解决这一问题，我们引入了OCRBench v2，这是一个大规模双语文本中心的基准测试，包含目前最全面的任务集（比之前的多场景基准测试OCRBench多4倍的任务），涵盖了最广泛的场景（包括街头场景、收据、公式、图表等31种不同的场景），并具有详细的评估指标，总共有10,000个经人工验证的问题-答案对，困难样本占比较大。经过精细的基准测试后，我们发现，在OCRBench v2上，22种最先进的LMM中有20种得分低于50分（满分100分），并且面临着五种类型的限制，包括不常见的文本识别、细粒度感知、布局感知、复杂元素解析和逻辑推理。该基准测试和评估脚本可在以下链接获取：[此链接](https://)。 

---
# Predicate Invention from Pixels via Pretrained Vision-Language Models 

**Title (ZH)**: 通过预训练的跨模态模型从像素中发明谓词 

**Authors**: Ashay Athalye, Nishanth Kumar, Tom Silver, Yichao Liang, Tomás Lozano-Pérez, Leslie Pack Kaelbling  

**Link**: [PDF](https://arxiv.org/pdf/2501.00296)  

**Abstract**: Our aim is to learn to solve long-horizon decision-making problems in highly-variable, combinatorially-complex robotics domains given raw sensor input in the form of images. Previous work has shown that one way to achieve this aim is to learn a structured abstract transition model in the form of symbolic predicates and operators, and then plan within this model to solve novel tasks at test time. However, these learned models do not ground directly into pixels from just a handful of demonstrations. In this work, we propose to invent predicates that operate directly over input images by leveraging the capabilities of pretrained vision-language models (VLMs). Our key idea is that, given a set of demonstrations, a VLM can be used to propose a set of predicates that are potentially relevant for decision-making and then to determine the truth values of these predicates in both the given demonstrations and new image inputs. We build upon an existing framework for predicate invention, which generates feature-based predicates operating on object-centric states, to also generate visual predicates that operate on images. Experimentally, we show that our approach -- pix2pred -- is able to invent semantically meaningful predicates that enable generalization to novel, complex, and long-horizon tasks across two simulated robotic environments. 

**Abstract (ZH)**: 我们的目标是在高度变化和组合复杂性的机器人领域中，利用原始传感器输入（以图像形式），学习解决长期决策问题。之前的研究表明，实现这一目标的一种方法是学习一种结构化抽象转移模型，该模型以符号谓词和操作符的形式存在，然后在模型中进行计划，以在测试时解决新颖的任务。然而，这些学习到的模型不能直接从少数演示中推断到像素级。在本研究中，我们提出了一种方法，通过利用预训练的视觉语言模型（VLM）的能力，直接在输入图像上定义谓词。我们的核心思想是，在给定一组演示的情况下，可以使用VLM提出一组潜在相关的谓词，并在这些演示和新的图像输入上确定这些谓词的真实性值。我们在此前的谓词发明框架基础上进行了扩展，该框架可以生成基于特征的谓词以操作面向对象的状态，同时也能生成操作图像的视觉谓词。实验结果显示，我们的方法——pix2pred——能够发明具有语义意义的谓词，从而在两个模拟的机器人环境中实现对新颖、复杂和长期决策任务的泛化。 

---
# Dual Diffusion for Unified Image Generation and Understanding 

**Title (ZH)**: 统一图像生成与理解的双重扩散方法 

**Authors**: Zijie Li, Henry Li, Yichun Shi, Amir Barati Farimani, Yuval Kluger, Linjie Yang, Peng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00289)  

**Abstract**: Diffusion models have gained tremendous success in text-to-image generation, yet still lag behind with visual understanding tasks, an area dominated by autoregressive vision-language models. We propose a large-scale and fully end-to-end diffusion model for multi-modal understanding and generation that significantly improves on existing diffusion-based multimodal models, and is the first of its kind to support the full suite of vision-language modeling capabilities. Inspired by the multimodal diffusion transformer (MM-DiT) and recent advances in discrete diffusion language modeling, we leverage a cross-modal maximum likelihood estimation framework that simultaneously trains the conditional likelihoods of both images and text jointly under a single loss function, which is back-propagated through both branches of the diffusion transformer. The resulting model is highly flexible and capable of a wide range of tasks including image generation, captioning, and visual question answering. Our model attained competitive performance compared to recent unified image understanding and generation models, demonstrating the potential of multimodal diffusion modeling as a promising alternative to autoregressive next-token prediction models. 

**Abstract (ZH)**: 扩散模型在文本生成图片方面取得了巨大的成功，但在视觉理解任务上仍落后于以自回归视觉语言模型为主导的领域。我们提出了一种大规模的端到端多模态扩散模型，该模型在现有的基于扩散的多模态模型上显著改进，并且是首个支持全面视觉语言建模能力的模型。受多模态扩散变换器（MM-DiT）和离散扩散语言建模近期进展的启发，我们利用一种跨模态的最大似然估计框架，在单一损失函数下同时训练图像和文本的条件似然性，该损失函数通过扩散变换器的两个分支进行反向传播。最终，该模型具有高度的灵活性，能够处理包括图像生成、字幕生成和视觉问答等广泛的任务。与近期统一的图像理解和生成模型相比，我们的模型取得了竞争力的表现，证明了多模态扩散建模作为自回归下一个token预测模型替代方案的潜力。 

---
# Text-to-Image GAN with Pretrained Representations 

**Title (ZH)**: 预训练表示的文本到图像生成网络 

**Authors**: Xiaozhou You, Jian Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00116)  

**Abstract**: Generating desired images conditioned on given text descriptions has received lots of attention. Recently, diffusion models and autoregressive models have demonstrated their outstanding expressivity and gradually replaced GAN as the favored architectures for text-to-image synthesis. However, they still face some obstacles: slow inference speed and expensive training costs. To achieve more powerful and faster text-to-image synthesis under complex scenes, we propose TIGER, a text-to-image GAN with pretrained representations. To be specific, we propose a vision-empowered discriminator and a high-capacity generator. (i) The vision-empowered discriminator absorbs the complex scene understanding ability and the domain generalization ability from pretrained vision models to enhance model performance. Unlike previous works, we explore stacking multiple pretrained models in our discriminator to collect multiple different representations. (ii) The high-capacity generator aims to achieve effective text-image fusion while increasing the model capacity. The high-capacity generator consists of multiple novel high-capacity fusion blocks (HFBlock). And the HFBlock contains several deep fusion modules and a global fusion module, which play different roles to benefit our model. Extensive experiments demonstrate the outstanding performance of our proposed TIGER both on standard and zero-shot text-to-image synthesis tasks. On the standard text-to-image synthesis task, TIGER achieves state-of-the-art performance on two challenging datasets, which obtain a new FID 5.48 (COCO) and 9.38 (CUB). On the zero-shot text-to-image synthesis task, we achieve comparable performance with fewer model parameters, smaller training data size and faster inference speed. Additionally, more experiments and analyses are conducted in the Supplementary Material. 

**Abstract (ZH)**: 基于给定文字描述生成所需图像的研究受到了广泛关注。最近，扩散模型和自回归模型展示了其出色的表现力，并逐渐取代了生成对抗网络（GAN）在文字到图像合成方面的青睐地位。然而，它们仍然面临着一些障碍：推理速度较慢和训练成本较高。为了在复杂场景下实现更强大的、更快的文字到图像合成，我们提出了一种具有预训练表征的文本到图像生成对抗网络（TIGER）。具体而言，我们提出了一种视觉增强的判别器和一个高容量生成器。（i）视觉增强的判别器从预训练的视觉模型中吸收复杂的场景理解能力和领域泛化能力，以增强模型性能。与先前的工作不同，我们在判别器中探索堆叠多个预训练模型，以收集多种不同的表示。（ii）高容量生成器旨在在提高模型容量的同时实现有效的图文融合。高容量生成器由多个新颖的高容量融合块（HFBlock）组成，而HFBlock包含多个深度融合模块和一个全局融合模块，它们在我们的模型中发挥不同的作用。广泛的实验表明，在标准和零-shot文字到图像合成任务中，我们提出的TIGER均表现出色。在标准文字到图像合成任务中，TIGER在两个具有挑战性的数据集上达到了最先进的性能，分别获得新的FID值5.48（COCO）和9.38（CUB）。在零-shot文字到图像合成任务中，我们使用较少的模型参数、较小的训练数据量和更快的推理速度实现了可媲美的性能。此外，我们在补充材料中还进行了更多的实验和分析。 

---