# A Cognitive Ideation Support Framework using IBM Watson Services 

**Title (ZH)**: 使用IBM Watson服务的认知构想支持框架 

**Authors**: Samaa Elnagar, Kweku-Muata Osei-Bryson  

**Link**: [PDF](https://arxiv.org/pdf/2412.14025)  

**Abstract**: Ideas generation is a core activity for innovation in organizations. The creativity of the generated ideas depends not only on the knowledge retrieved from the organizations' knowledge bases, but also on the external knowledge retrieved from other resources. Unfortunately, organizations often cannot efficiently utilize the knowledge in the knowledge bases due to the limited abilities of the search and retrieval mechanisms especially when dealing with unstructured data. In this paper, we present a new cognitive support framework for ideation that uses the IBM Watson DeepQA services. IBM Watson is a Question Answering system which mimics human cognitive abilities to retrieve and rank information. The proposed framework is based on the Search for Ideas in the Associative Memory (SIAM) model to help organizations develop creative ideas through discovering new relationships between retrieved data. To evaluate the effectiveness of the proposed system, the generated ideas generated are selected and assessed using a set of established creativity criteria. 

**Abstract (ZH)**: 创新是组织的核心活动之一。生成的创意质量不仅取决于从组织知识库中检索到的知识，还取决于从其他资源中检索到的外部知识。不幸的是，组织往往难以有效地利用知识库中的知识，尤其是在处理非结构化数据时，受限于搜索引擎和检索机制的能力有限。本文提出了一种新的创意支持框架，该框架利用了IBM Watson DeepQA服务。IBM Watson 是一个问答系统，模仿人类的认知能力，用于检索和排序信息。所提出的框架基于关联记忆中创意检索模型（SIAM模型），通过发现检索数据之间的新关系，来帮助组织发展创意。为了评估所提出系统的有效性，生成的创意根据一系列已建立的创意标准进行了选择和评估。 

---
# CRM: Retrieval Model with Controllable Condition 

**Title (ZH)**: CRM：可控条件检索模型 

**Authors**: Chi Liu, Jiangxia Cao, Rui Huang, Kuo Cai, Weifeng Ding, Qiang Luo, Kun Gai, Guorui Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2412.13844)  

**Abstract**: Recommendation systems (RecSys) are designed to connect users with relevant items from a vast pool of candidates while aligning with the business goals of the platform. A typical industrial RecSys is composed of two main stages, retrieval and ranking: (1) the retrieval stage aims at searching hundreds of item candidates satisfied user interests; (2) based on the retrieved items, the ranking stage aims at selecting the best dozen items by multiple targets estimation for each item candidate, including classification and regression targets. Compared with ranking model, the retrieval model absence of item candidate information during inference, therefore retrieval models are often trained by classification target only (e.g., click-through rate), but failed to incorporate regression target (e.g., the expected watch-time), which limit the effectiveness of retrieval. In this paper, we propose the Controllable Retrieval Model (CRM), which integrates regression information as conditional features into the two-tower retrieval paradigm. This modification enables the retrieval stage could fulfill the target gap with ranking model, enhancing the retrieval model ability to search item candidates satisfied the user interests and condition effectively. We validate the effectiveness of CRM through real-world A/B testing and demonstrate its successful deployment in Kuaishou short-video recommendation system, which serves over 400 million users. 

**Abstract (ZH)**: 推荐系统（RecSys）旨在将用户与大量候选项目中的相关项目进行匹配，同时与平台的业务目标保持一致。一个典型的工业推荐系统通常由两个主要阶段组成：检索和排序：（1）检索阶段的目标是在用户兴趣范围内搜索满足要求的数百个项目候选；（2）基于检索到的项目，排序阶段的目标是通过多个目标估计每个项目候选的最佳前十项，包括分类和回归目标。与排序模型相比，检索模型在推理过程中不包含项目候选信息，因此检索模型通常仅通过分类目标（例如点击率）进行训练，而未能结合回归目标（例如预期观看时间），这限制了检索模型的有效性。本文提出了一种可控检索模型（Controllable Retrieval Model, CRM），该模型将回归信息作为条件特征整合进两塔检索框架中。这一修改使检索阶段能够弥补与排序模型之间的目标差距，增强检索模型在搜索满足用户兴趣和条件的项目候选方面的能力。我们通过实际部署的A/B测试验证了CRM的有效性，并展示了其在快手短视频推荐系统中的成功应用，该系统的服务用户超过4亿。 

---
# Maybe you are looking for CroQS: Cross-modal Query Suggestion for Text-to-Image Retrieval 

**Title (ZH)**: 也许您正在寻找CroQS：跨模态查询建议在文本到图像检索中的应用 

**Authors**: Giacomo Pacini, Fabio Carrara, Nicola Messina, Nicola Tonellotto, Giuseppe Amato, Fabrizio Falchi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13834)  

**Abstract**: Query suggestion, a technique widely adopted in information retrieval, enhances system interactivity and the browsing experience of document collections. In cross-modal retrieval, many works have focused on retrieving relevant items from natural language queries, while few have explored query suggestion solutions. In this work, we address query suggestion in cross-modal retrieval, introducing a novel task that focuses on suggesting minimal textual modifications needed to explore visually consistent subsets of the collection, following the premise of ''Maybe you are looking for''. To facilitate the evaluation and development of methods, we present a tailored benchmark named CroQS. This dataset comprises initial queries, grouped result sets, and human-defined suggested queries for each group. We establish dedicated metrics to rigorously evaluate the performance of various methods on this task, measuring representativeness, cluster specificity, and similarity of the suggested queries to the original ones. Baseline methods from related fields, such as image captioning and content summarization, are adapted for this task to provide reference performance scores. Although relatively far from human performance, our experiments reveal that both LLM-based and captioning-based methods achieve competitive results on CroQS, improving the recall on cluster specificity by more than 115% and representativeness mAP by more than 52% with respect to the initial query. The dataset, the implementation of the baseline methods and the notebooks containing our experiments are available here: this https URL 

**Abstract (ZH)**: 查询建议是一种广泛应用于信息检索的技术，它增强了系统互动性和文档集合的浏览体验。在跨模态检索中，许多研究主要关注从自然语言查询中检索相关项目，而鲜有研究探索查询建议解决方案。在本项工作中，我们针对跨模态检索中的查询建议问题进行了研究，引入了一个新的任务，该任务关注建议最小的文字修改，以探索集合中视觉上一致的子集，前提是“或许您想要的是”。为了便于方法的评估和发展，我们提供了一个专门设计的基准数据集 CroQS。该数据集包括初始查询、分组结果集以及为每个组定义的人工建议查询。我们建立了专门的评估指标，以严格评估各种方法在该任务上的性能，衡量建议查询的代表性、聚类特异性以及与原始查询的相似度。来自相关领域的基准方法，如图像描述和内容摘要方法，进行了相应调整，以提供参考性能值。尽管远低于人类性能，但我们的实验表明，基于大语言模型（LLM）的方法和基于描述的方法在 CroQS 数据集上都取得了竞争力的结果。与初始查询相比，建议查询在聚类特异性召回率上提高了超过 115%，在代表性的 mAP 上提高了超过 52%。该数据集、基准方法的实现以及包含我们实验的笔记本电脑都可以在这里访问：[这个链接](this https URL)。 

---
# Heterogeneous Graph Collaborative Filtering 

**Title (ZH)**: 异质图协作过滤 

**Authors**: Lianghao Xia, Meiyan Xie, Yong Xu, Chao Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13825)  

**Abstract**: For modern recommender systems, the use of low-dimensional latent representations to embed users and items based on their observed interactions has become commonplace. However, many existing recommendation models are primarily designed for coarse-grained and homogeneous interactions, which limits their effectiveness in two critical dimensions. Firstly, these models fail to leverage the relational dependencies that exist across different types of user behaviors, such as page views, collects, comments, and purchases. Secondly, they struggle to capture the fine-grained latent factors that drive user interaction patterns. To address these limitations, we present a heterogeneous graph collaborative filtering model MixRec that excels at disentangling users' multi-behavior interaction patterns and uncovering the latent intent factors behind each behavior. Our model achieves this by incorporating intent disentanglement and multi-behavior modeling, facilitated by a parameterized heterogeneous hypergraph architecture. Furthermore, we introduce a novel contrastive learning paradigm that adaptively explores the advantages of self-supervised data augmentation, thereby enhancing the model's resilience against data sparsity and expressiveness with relation heterogeneity. To validate the efficacy of MixRec, we conducted extensive experiments on three public datasets. The results clearly demonstrate its superior performance, significantly outperforming various state-of-the-art baselines. Our model is open-sourced and available at: this https URL. 

**Abstract (ZH)**: 对于现代推荐系统而言，使用低维度的隐表示来根据用户和项目的观察交互来嵌入它们已成为常见做法。然而，许多现有的推荐模型主要设计用于粗粒度的和同质化的交互，这在两个关键维度上限制了其效果。首先，这些模型无法利用不同类型的用户行为（如页面浏览、收藏、评论和购买）之间存在的关系依赖性。其次，它们难以捕捉驱动用户交互模式的细粒度隐含因素。为了解决这些局限性，我们提出了一种异质图协作过滤模型MixRec，该模型擅长分离用户的多行为交互模式，并揭示每种行为背后的隐含意图因素。我们的模型通过结合意图分离和多行为建模，利用参数化的异质超图架构实现这一目标。此外，我们引入了一种新颖的对比学习范式，该范式能够适应性地探索自我监督数据增强的优势，从而增强模型对数据稀疏性和关系异质性下的鲁棒性和表达能力。

为了验证MixRec的有效性，我们在三个公开数据集上进行了广泛的实验。实验结果清楚地表明，MixRec在性能上显著优于各种最新的基线模型。我们的模型已开源，并可在此访问：[此链接](此 https URL)。 

---
# Semantic Convergence: Harmonizing Recommender Systems via Two-Stage Alignment and Behavioral Semantic Tokenization 

**Title (ZH)**: 语义趋同：通过两阶段对齐和行为语义词元化 harmonize 推荐系统 

**Authors**: Guanghan Li, Xun Zhang, Yufei Zhang, Yifan Yin, Guojun Yin, Wei Lin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13771)  

**Abstract**: Large language models (LLMs), endowed with exceptional reasoning capabilities, are adept at discerning profound user interests from historical behaviors, thereby presenting a promising avenue for the advancement of recommendation systems. However, a notable discrepancy persists between the sparse collaborative semantics typically found in recommendation systems and the dense token representations within LLMs. In our study, we propose a novel framework that harmoniously merges traditional recommendation models with the prowess of LLMs. We initiate this integration by transforming ItemIDs into sequences that align semantically with the LLMs space, through the proposed Alignment Tokenization module. Additionally, we design a series of specialized supervised learning tasks aimed at aligning collaborative signals with the subtleties of natural language semantics. To ensure practical applicability, we optimize online inference by pre-caching the top-K results for each user, reducing latency and improving effciency. Extensive experimental evidence indicates that our model markedly improves recall metrics and displays remarkable scalability of recommendation systems. 

**Abstract (ZH)**: 大型语言模型（LLMs）因其卓越的推理能力，能够从用户的历史行为中洞察深刻的用户兴趣，从而为推荐系统的发展提供了良好的前景。然而，推荐系统中通常存在的稀疏协作语义与LLMs中密集的令牌表示之间存在着显著差异。在我们的研究中，我们提出了一种新颖的框架，该框架能够和谐地将传统推荐模型与LLMs的优势结合起来。我们通过提出的对齐分词模块（Alignment Tokenization module）将项目ID转换为与LLMs空间语义相匹配的序列，从而开始了这种整合。此外，我们还设计了一系列专为对齐协作信号与自然语言语义细微差别的特殊监督学习任务。为确保其实用性，我们通过为每个用户预缓存前K个结果来优化在线推理，从而降低延迟和提高效率。大量的实验证据表明，我们的模型在召回率指标上显著提高，并且展示了推荐系统出色的可扩展性。 

---
# Bridging the User-side Knowledge Gap in Knowledge-aware Recommendations with Large Language Models 

**Title (ZH)**: 使用大型语言模型弥合知识aware推荐中的用户侧知识差距 

**Authors**: Zheng Hu, Zhe Li, Ziyun Jiao, Satoshi Nakagawa, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren  

**Link**: [PDF](https://arxiv.org/pdf/2412.13544)  

**Abstract**: In recent years, knowledge graphs have been integrated into recommender systems as item-side auxiliary information, enhancing recommendation accuracy. However, constructing and integrating structural user-side knowledge remains a significant challenge due to the improper granularity and inherent scarcity of user-side features. Recent advancements in Large Language Models (LLMs) offer the potential to bridge this gap by leveraging their human behavior understanding and extensive real-world knowledge. Nevertheless, integrating LLM-generated information into recommender systems presents challenges, including the risk of noisy information and the need for additional knowledge transfer. In this paper, we propose an LLM-based user-side knowledge inference method alongside a carefully designed recommendation framework to address these challenges. Our approach employs LLMs to infer user interests based on historical behaviors, integrating this user-side information with item-side and collaborative data to construct a hybrid structure: the Collaborative Interest Knowledge Graph (CIKG). Furthermore, we propose a CIKG-based recommendation framework that includes a user interest reconstruction module and a cross-domain contrastive learning module to mitigate potential noise and facilitate knowledge transfer. We conduct extensive experiments on three real-world datasets to validate the effectiveness of our method. Our approach achieves state-of-the-art performance compared to competitive baselines, particularly for users with sparse interactions. 

**Abstract (ZH)**: 近年来，知识图谱已作为商品侧辅助信息集成到推荐系统中，以提升推荐精度。然而，由于用户侧特征的不适当粒度和固有的稀疏性，构建和集成结构化的用户侧知识仍然是一个重大挑战。近年来，大规模语言模型（LLMs）的进步为解决这一问题提供了潜在的途径，通过利用其对人类行为的理解和广泛的现实世界知识。然而，将LLM生成的信息集成到推荐系统中仍面临挑战，包括嘈杂信息的风险以及额外的知识迁移需求。在本文中，我们提出了一种基于LLM的用户侧知识推理方法以及一个精心设计的推荐框架来应对这些挑战。我们的方法利用LLM根据历史行为推断用户兴趣，并将这种用户侧信息与商品侧和协作数据相结合，构建一种混合结构：协作兴趣知识图谱（CIKG）。此外，我们提出了一种基于CIKG的推荐框架，包括一个用户兴趣重建模块和一个跨域对比学习模块，以减轻潜在的噪声并促进知识迁移。我们通过在三个真实世界数据集上进行广泛实验来验证该方法的有效性。我们的方法在与具有稀疏交互用户的竞争基线相比时，达到了最先进的性能。 

---
# Large Language Model Enhanced Recommender Systems: Taxonomy, Trend, Application and Future 

**Title (ZH)**: 大型语言模型增强的推荐系统：分类、趋势、应用与未来 

**Authors**: Qidong Liu, Xiangyu Zhao, Yuhao Wang, Yejing Wang, Zijian Zhang, Yuqi Sun, Xiang Li, Maolin Wang, Pengyue Jia, Chong Chen, Wei Huang, Feng Tian  

**Link**: [PDF](https://arxiv.org/pdf/2412.13432)  

**Abstract**: Large Language Model (LLM) has transformative potential in various domains, including recommender systems (RS). There have been a handful of research that focuses on empowering the RS by LLM. However, previous efforts mainly focus on LLM as RS, which may face the challenge of intolerant inference costs by LLM. Recently, the integration of LLM into RS, known as LLM-Enhanced Recommender Systems (LLMERS), has garnered significant interest due to its potential to address latency and memory constraints in real-world applications. This paper presents a comprehensive survey of the latest research efforts aimed at leveraging LLM to enhance RS capabilities. We identify a critical shift in the field with the move towards incorporating LLM into the online system, notably by avoiding their use during inference. Our survey categorizes the existing LLMERS approaches into three primary types based on the component of the RS model being augmented: Knowledge Enhancement, Interaction Enhancement, and Model Enhancement. We provide an in-depth analysis of each category, discussing the methodologies, challenges, and contributions of recent studies. Furthermore, we highlight several promising research directions that could further advance the field of LLMERS. 

**Abstract (ZH)**: 大型语言模型（LLM）在多个领域具有变革性的潜力，包括推荐系统（RS）。已经有少数研究致力于通过LLM提升RS。然而，现有的努力主要集中在将LLM作为RS，这可能会面临LLM推理成本难以容忍的挑战。最近，将LLM集成到RS中的做法，也就是被称为LLM增强推荐系统（LLMERS），由于其在解决实际应用中的延迟和内存限制方面的潜力，已经引起了广泛关注。本文综述了最近的研究努力，旨在利用LLM提升RS功能。我们发现了一个领域的关键转变，即转向在在线系统中引入LLM，特别是避免在推理过程中使用它们。我们的综述将现有的LLMERS方法根据增强RS模型的组件分为三大类：知识增强、交互增强和模型增强。我们对每种类别进行了深入分析，讨论了近期研究的方法论、挑战和贡献。此外，我们还指出了几个有望进一步推进LLMERS领域研究的发展方向。 

---
# Lightweight yet Fine-grained: A Graph Capsule Convolutional Network with Subspace Alignment for Shared-account Sequential Recommendation 

**Title (ZH)**: 轻量且细粒度：一种用于共享账号序列推荐的子空间对齐图胶囊卷积网络 

**Authors**: Jinyu Zhang, Zhongying Zhao, Chao Li, Yanwei Yu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13408)  

**Abstract**: Shared-account Sequential Recommendation (SSR) aims to provide personalized recommendations for accounts shared by multiple users with varying sequential preferences. Previous studies on SSR struggle to capture the fine-grained associations between interactions and different latent users within the shared account's hybrid sequences. Moreover, most existing SSR methods (e.g., RNN-based or GCN-based methods) have quadratic computational complexities, hindering the deployment of SSRs on resource-constrained devices. To this end, we propose a Lightweight Graph Capsule Convolutional Network with subspace alignment for shared-account sequential recommendation, named LightGC$^2$N. Specifically, we devise a lightweight graph capsule convolutional network. It facilitates the fine-grained matching between interactions and latent users by attentively propagating messages on the capsule graphs. Besides, we present an efficient subspace alignment method. This method refines the sequence representations and then aligns them with the finely clustered preferences of latent users. The experimental results on four real-world datasets indicate that LightGC$^2$N outperforms nine state-of-the-art methods in accuracy and efficiency. 

**Abstract (ZH)**: 共享账号顺序推荐（Shared-account Sequential Recommendation, SSR）旨在为多个用户共享且具有不同顺序偏好的账号提供个性化推荐。以往关于SSR的研究难以捕捉共享账号混合序列中互动与不同潜在用户之间微妙的关系。此外，大多数现有的SSR方法（如基于RNN的方法或基于GCN的方法）具有二次计算复杂度，这在资源受限的设备上阻碍了SSR的应用。为了解决这些问题，我们提出了一种轻量级图胶囊卷积网络，该网络通过子空间对齐来应对共享账号顺序推荐问题，该方法称为LightGC$^2$N。具体而言，我们设计了一种轻量级图胶囊卷积网络，通过注意传播消息在胶囊图上来促进互动与潜在用户之间细微匹配。此外，我们还提出了一个高效的子空间对齐方法。该方法首先细化序列表示，然后将这些表示与潜在用户的精细聚类偏好对齐。在四个真实数据集上的实验结果表明，LightGC$^2$N在准确性和效率方面均优于九种最先进的方法。 

---
# JudgeBlender: Ensembling Judgments for Automatic Relevance Assessment 

**Title (ZH)**: JudgeBlender: 组合判决以实现自动相关性评估 

**Authors**: Hossein A. Rahmani, Emine Yilmaz, Nick Craswell, Bhaskar Mitra  

**Link**: [PDF](https://arxiv.org/pdf/2412.13268)  

**Abstract**: The effective training and evaluation of retrieval systems require a substantial amount of relevance judgments, which are traditionally collected from human assessors -- a process that is both costly and time-consuming. Large Language Models (LLMs) have shown promise in generating relevance labels for search tasks, offering a potential alternative to manual assessments. Current approaches often rely on a single LLM, such as GPT-4, which, despite being effective, are expensive and prone to intra-model biases that can favour systems leveraging similar models. In this work, we introduce JudgeBlender, a framework that employs smaller, open-source models to provide relevance judgments by combining evaluations across multiple LLMs (LLMBlender) or multiple prompts (PromptBlender). By leveraging the LLMJudge benchmark [18], we compare JudgeBlender with state-of-the-art methods and the top performers in the LLMJudge challenge. Our results show that JudgeBlender achieves competitive performance, demonstrating that very large models are often unnecessary for reliable relevance assessments. 

**Abstract (ZH)**: 有效的检索系统训练和评估需要大量的相关性判断，这些判断传统上是由人工评估者收集的——这是一个既昂贵又耗时的过程。大型语言模型（LLMs）在为搜索任务生成相关性标签方面显示出潜力，从而为替代人工评估提供了可能。当前的方法通常依赖单一的LLM，如GPT-4，尽管其有效，但成本较高且容易受到模型内部偏差的影响，这些偏差可能导致利用类似模型的系统获得优势。在本文中，我们引入了JudgeBlender框架，该框架通过结合多个LLM（LLMBlender）或多个提示（PromptBlender）的评估来使用较小的开源模型提供相关性判断。通过利用LLMJudge基准数据集[18]，我们将JudgeBlender与最先进的方法和LLMJudge挑战中的顶尖表现者进行了比较。我们的结果表明，JudgeBlender取得了竞争力的表现，这表明可靠的相关性评估通常并不需要非常大的模型。 

---
# Adaptive Two-Phase Finetuning LLMs for Japanese Legal Text Retrieval 

**Title (ZH)**: 自适应两阶段 fine-tuning 聚焦于日语法律文本检索的大型语言模型 

**Authors**: Quang Hoang Trung, Nguyen Van Hoang Phuc, Le Trung Hoang, Quang Huu Hieu, Vo Nguyen Le Duy  

**Link**: [PDF](https://arxiv.org/pdf/2412.13205)  

**Abstract**: Text Retrieval (TR) involves finding and retrieving text-based content relevant to a user's query from a large repository, with applications in real-world scenarios such as legal document retrieval. While most existing studies focus on English, limited work addresses Japanese contexts. In this paper, we introduce a new dataset specifically designed for Japanese legal contexts and propose a novel two-phase pipeline tailored to this domain.
In the first phase, the model learns a broad understanding of global contexts, enhancing its generalization and adaptability to diverse queries. In the second phase, the model is fine-tuned to address complex queries specific to legal scenarios. Extensive experiments are conducted to demonstrate the superior performance of our method, which outperforms existing baselines.
Furthermore, our pipeline proves effective in English contexts, surpassing comparable baselines on the MS MARCO dataset. We have made our code publicly available on GitHub, and the model checkpoints are accessible via HuggingFace. 

**Abstract (ZH)**: 文本检索（Text Retrieval, TR）涉及从大型数据库中找到并检索与用户查询相关的文本内容，具有在实际场景中的应用，例如法律文件检索。虽然现有的大多数研究主要集中在英语上，但对于日语环境的研究却相对较少。在本文中，我们介绍了一个专门为日语法律环境设计的新数据集，并提出了一种针对该领域定制的新型两阶段管道。

在第一阶段，模型学习更广泛的任务理解，提高了其对多样化查询的泛化能力和适应性。在第二阶段，模型进一步优化以解决特定于法律场景的复杂查询。我们进行了大量的实验，以展示我们方法的优越性能，该方法优于现有基线。

此外，我们的管道在英语环境中也表现出有效性，超越了MS MARCO数据集上的可比基线。我们已将代码公开发布在GitHub上，并通过HuggingFace提供模型检查点的访问权限。 

---
# Adversarial Hubness in Multi-Modal Retrieval 

**Title (ZH)**: 多模态检索中的对抗性团集现象 

**Authors**: Tingwei Zhang, Fnu Suya, Rishi Jha, Collin Zhang, Vitaly Shmatikov  

**Link**: [PDF](https://arxiv.org/pdf/2412.14113)  

**Abstract**: Hubness is a phenomenon in high-dimensional vector spaces where a single point from the natural distribution is unusually close to many other points. This is a well-known problem in information retrieval that causes some items to accidentally (and incorrectly) appear relevant to many queries. In this paper, we investigate how attackers can exploit hubness to turn any image or audio input in a multi-modal retrieval system into an adversarial hub. Adversarial hubs can be used to inject universal adversarial content (e.g., spam) that will be retrieved in response to thousands of different queries, as well as for targeted attacks on queries related to specific, attacker-chosen concepts. We present a method for creating adversarial hubs and evaluate the resulting hubs on benchmark multi-modal retrieval datasets and an image-to-image retrieval system based on a tutorial from Pinecone, a popular vector database. For example, in text-caption-to-image retrieval, a single adversarial hub is retrieved as the top-1 most relevant image for more than 21,000 out of 25,000 test queries (by contrast, the most common natural hub is the top-1 response to only 102 queries). We also investigate whether techniques for mitigating natural hubness are an effective defense against adversarial hubs, and show that they are not effective against hubs that target queries related to specific concepts. 

**Abstract (ZH)**: 高维向量空间中的“中心性”现象是指自然分布中的单个点与许多其他点异常接近。这是一个在信息检索领域中众所周知的问题，会导致一些项错误地在许多查询中被错误地视为相关。在本文中，我们探讨了攻击者如何利用中心性现象将任何图像或音频输入转换为多模态检索系统中的对抗中心。对抗中心可以用于注入通用的对抗内容（例如垃圾信息），这些内容会对成千上万的不同查询进行检索，同时也可以针对特定攻击者选定概念相关的问题进行有针对性的攻击。我们提出了一种创建对抗中心的方法，并在基准多模态检索数据集和基于 Pinecone（一个流行的向量数据库）教程的图像到图像检索系统上评估了生成的中心。例如，在文本-描述-图像检索中，一个单一的对抗中心被检索为超过 21,000 个测试查询（共计 25,000 个）中最相关的图像（相比之下，最常见的自然中心只在 102 个查询中作为最相关响应）。我们还研究了减轻自然中心性技术是否能有效防御对抗中心性，并证明它们对针对特定概念相关查询的中心无效。 

---
# RAG-RewardBench: Benchmarking Reward Models in Retrieval Augmented Generation for Preference Alignment 

**Title (ZH)**: RAG-RewardBench：检索增强生成中的奖励模型基准测试，用于偏好对齐 

**Authors**: Zhuoran Jin, Hongbang Yuan, Tianyi Men, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13746)  

**Abstract**: Despite the significant progress made by existing retrieval augmented language models (RALMs) in providing trustworthy responses and grounding in reliable sources, they often overlook effective alignment with human preferences. In the alignment process, reward models (RMs) act as a crucial proxy for human values to guide optimization. However, it remains unclear how to evaluate and select a reliable RM for preference alignment in RALMs. To this end, we propose RAG-RewardBench, the first benchmark for evaluating RMs in RAG settings. First, we design four crucial and challenging RAG-specific scenarios to assess RMs, including multi-hop reasoning, fine-grained citation, appropriate abstain, and conflict robustness. Then, we incorporate 18 RAG subsets, six retrievers, and 24 RALMs to increase the diversity of data sources. Finally, we adopt an LLM-as-a-judge approach to improve preference annotation efficiency and effectiveness, exhibiting a strong correlation with human annotations. Based on the RAG-RewardBench, we conduct a comprehensive evaluation of 45 RMs and uncover their limitations in RAG scenarios. Additionally, we also reveal that existing trained RALMs show almost no improvement in preference alignment, highlighting the need for a shift towards preference-aligned this http URL release our benchmark and code publicly at this https URL for future work. 

**Abstract (ZH)**: 尽管现有的检索增强语言模型（RALMs）在提供可靠响应和基于可靠来源的基础上取得了显著进展，但在有效与人类偏好对齐方面，它们常常有所忽视。在对齐过程中，奖励模型（RMs）作为一种关键代理，用于指引优化过程，反映人类价值观。然而，如何评价和选择适用于RALMs的可靠RM以实现偏好对齐仍然是一个未解之谜。为此，我们提出RAG-RewardBench，这是首个在检索增强（RAG）环境中评估RM基准。首先，我们设计了四个关键且具有挑战性的RAG特定场景，以评估RM，包括多跳推理、精细引文、适当地保持中立以及冲突稳健性。其次，我们整合了18个RAG子集、六种检索器和24种RALMs，以增加数据源的多样性。最后，我们采用LLM作为裁判的方法，以提高偏好注解的效率和有效性，表现出与人类注解的强烈相关性。基于RAG-RewardBench，我们对45种RM进行了全面评估，并发现了它们在RAG场景下的局限性。此外，我们还揭示了现有的训练过的RALMs在偏好对齐方面几乎没有改进，突显了向偏好对齐转变的必要性。我们将在https://your-public-url发布这个基准和代码，以便未来的研究工作使用。 

---
# Reverse Region-to-Entity Annotation for Pixel-Level Visual Entity Linking 

**Title (ZH)**: 像素级别视觉实体链接中的反向区域到实体标注 

**Authors**: Zhengfei Xu, Sijia Zhao, Yanchao Hao, Xiaolong Liu, Lili Li, Yuyang Yin, Bo Li, Xi Chen, Xin Xin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13614)  

**Abstract**: Visual Entity Linking (VEL) is a crucial task for achieving fine-grained visual understanding, matching objects within images (visual mentions) to entities in a knowledge base. Previous VEL tasks rely on textual inputs, but writing queries for complex scenes can be challenging. Visual inputs like clicks or bounding boxes offer a more convenient alternative. Therefore, we propose a new task, Pixel-Level Visual Entity Linking (PL-VEL), which uses pixel masks from visual inputs to refer to objects, supplementing reference methods for VEL. To facilitate research on this task, we have constructed the MaskOVEN-Wiki dataset through an entirely automatic reverse region-entity annotation framework. This dataset contains over 5 million annotations aligning pixel-level regions with entity-level labels, which will advance visual understanding towards fine-grained. Moreover, as pixel masks correspond to semantic regions in an image, we enhance previous patch-interacted attention with region-interacted attention by a visual semantic tokenization approach. Manual evaluation results indicate that the reverse annotation framework achieved a 94.8% annotation success rate. Experimental results show that models trained on this dataset improved accuracy by 18 points compared to zero-shot models. Additionally, the semantic tokenization method achieved a 5-point accuracy improvement over the trained baseline. 

**Abstract (ZH)**: 视觉实体链接（VEL）是实现精细视觉理解的关键任务，它涉及将图像中的对象（视觉提及）与知识库中的实体进行匹配。之前的VEL任务依赖于文本输入，但为复杂的场景编写查询可能会有挑战性。视觉输入，如点击或边界框，提供了更为便捷的替代方案。因此，我们提出了一个新的任务，像素级视觉实体链接（PL-VEL），它通过使用来自视觉输入的像素掩码来引用对象，补充了VEL的参考方法。为了促进对该任务的研究，我们通过全新的自动化逆向区域-实体注释框架构建了MaskOVEN-Wiki数据集。该数据集包含了超过500万个像素级区域与实体级标签对齐的注释，这将推动视觉理解向精细化发展。此外，由于像素掩码对应图像中的语义区域，我们通过视觉语义分词方法增强了先前的块交互注意力机制，引入了区域交互注意力机制。手动评估结果显示，逆向注释框架的注释成功率为94.8%。实验结果表明，基于该数据集训练的模型比零样本模型的准确性提高了18个百分点。此外，语义分词方法在训练基线下提高了5个百分点的准确性。 

---
# Information-Theoretic Generative Clustering of Documents 

**Title (ZH)**: 信息论生成聚类文档 

**Authors**: Xin Du, Kumiko Tanaka-Ishii  

**Link**: [PDF](https://arxiv.org/pdf/2412.13534)  

**Abstract**: We present {\em generative clustering} (GC) for clustering a set of documents, $\mathrm{X}$, by using texts $\mathrm{Y}$ generated by large language models (LLMs) instead of by clustering the original documents $\mathrm{X}$. Because LLMs provide probability distributions, the similarity between two documents can be rigorously defined in an information-theoretic manner by the KL divergence. We also propose a natural, novel clustering algorithm by using importance sampling. We show that GC achieves the state-of-the-art performance, outperforming any previous clustering method often by a large margin. Furthermore, we show an application to generative document retrieval in which documents are indexed via hierarchical clustering and our method improves the retrieval accuracy. 

**Abstract (ZH)**: 我们提出了一种生成聚类（Generative Clustering, GC）方法，通过使用大规模语言模型（Large Language Models, LLMs）生成的文本 $\mathrm{Y}$ 来对文档集 $\mathrm{X}$ 进行聚类，而不是直接对原始文档 $\mathrm{X}$ 进行聚类。由于LLMs提供了概率分布，可以通过KL散度在信息论意义上严格定义两份文档之间的相似性。我们还提出了一种基于重要性采样的新颖聚类算法。实验结果表明，GC方法在聚类性能上达到了最佳水平，通常大幅优于以往的任何聚类方法。此外，我们还展示了生成性文档检索的应用场景，在这种应用中，文档通过层次聚类进行索引，我们的方法提高了检索准确性。 

---
# AIR-Bench: Automated Heterogeneous Information Retrieval Benchmark 

**Title (ZH)**: AIR-Bench：自动异构信息检索基准测试 

**Authors**: Jianlyu Chen, Nan Wang, Chaofan Li, Bo Wang, Shitao Xiao, Han Xiao, Hao Liao, Defu Lian, Zheng Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13102)  

**Abstract**: Evaluation plays a crucial role in the advancement of information retrieval (IR) models. However, current benchmarks, which are based on predefined domains and human-labeled data, face limitations in addressing evaluation needs for emerging domains both cost-effectively and efficiently. To address this challenge, we propose the Automated Heterogeneous Information Retrieval Benchmark (AIR-Bench). AIR-Bench is distinguished by three key features: 1) Automated. The testing data in AIR-Bench is automatically generated by large language models (LLMs) without human intervention. 2) Heterogeneous. The testing data in AIR-Bench is generated with respect to diverse tasks, domains and languages. 3) Dynamic. The domains and languages covered by AIR-Bench are constantly augmented to provide an increasingly comprehensive evaluation benchmark for community developers. We develop a reliable and robust data generation pipeline to automatically create diverse and high-quality evaluation datasets based on real-world corpora. Our findings demonstrate that the generated testing data in AIR-Bench aligns well with human-labeled testing data, making AIR-Bench a dependable benchmark for evaluating IR models. The resources in AIR-Bench are publicly available at this https URL. 

**Abstract (ZH)**: 评价在信息检索（IR）模型的发展中发挥着至关重要的作用。然而，当前基于预定义领域和人工标注数据的基准测试面临在成本和效率方面有效应对新兴领域评价需求的限制。为解决这一挑战，我们提出了自动异构信息检索基准（AIR-Bench）。AIR-Bench具有三个关键特征：1）自动化。AIR-Bench的测试数据由大型语言模型（LLMs）自动生成，无需人工干预。2）异构性。AIR-Bench的测试数据针对多种任务、领域和语言生成。3）动态性。AIR-Bench所涵盖的领域和语言不断扩展，为社区开发者提供越来越全面的评价基准。我们开发了一个可靠且稳健的数据生成流水线，基于实际语料库自动创建多样且高质量的评价数据集。我们的研究成果表明，AIR-Bench生成的测试数据与人工标注的测试数据高度一致，使AIR-Bench成为一个可靠的IR模型评价基准。AIR-Bench的资源可以在此处访问：[该网址]。 

---
# A Survey on Recommendation Unlearning: Fundamentals, Taxonomy, Evaluation, and Open Questions 

**Title (ZH)**: 推荐遗忘的研究综述：基础、分类、评估及开放问题 

**Authors**: Yuyuan Li, Xiaohua Feng, Chaochao Chen, Qiang Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.12836)  

**Abstract**: Recommender systems have become increasingly influential in shaping user behavior and decision-making, highlighting their growing impact in various domains. Meanwhile, the widespread adoption of machine learning models in recommender systems has raised significant concerns regarding user privacy and security. As compliance with privacy regulations becomes more critical, there is a pressing need to address the issue of recommendation unlearning, i.e., eliminating the memory of specific training data from the learned recommendation models. Despite its importance, traditional machine unlearning methods are ill-suited for recommendation unlearning due to the unique challenges posed by collaborative interactions and model parameters. This survey offers a comprehensive review of the latest advancements in recommendation unlearning, exploring the design principles, challenges, and methodologies associated with this emerging field. We provide a unified taxonomy that categorizes different recommendation unlearning approaches, followed by a summary of widely used benchmarks and metrics for evaluation. By reviewing the current state of research, this survey aims to guide the development of more efficient, scalable, and robust recommendation unlearning techniques. Furthermore, we identify open research questions in this field, which could pave the way for future innovations not only in recommendation unlearning but also in a broader range of unlearning tasks across different machine learning applications. 

**Abstract (ZH)**: 推荐系统如今在塑造用户行为和决策方面的影响越来越大，突显了其在各个领域中的日益重要性。与此同时，推荐系统中广泛采用机器学习模型引发了对用户隐私和安全的重大关切。随着遵守隐私法规变得更为关键，亟需解决推荐遗忘的问题，即从已学习的推荐模型中删除特定训练数据的痕迹。尽管这个问题至关重要，但传统的机器遗忘方法由于协作交互和模型参数的独特挑战并不适用于推荐遗忘。本文综述了推荐遗忘的最新进展，探讨了这一新兴领域的设计原则、挑战和方法论。我们提供了一种统一的分类法，将不同的推荐遗忘方法进行分类，并总结了常用的基准和评估指标。通过回顾当前的研究状态，本文旨在指导开发更高效、更具扩展性和更稳健的推荐遗忘技术。此外，我们还确定了该领域的若干开放研究问题，这些问题有可能为未来不仅在推荐遗忘领域，还在不同机器学习应用范围内的遗忘任务创新铺平道路。 

---
# RemoteRAG: A Privacy-Preserving LLM Cloud RAG Service 

**Title (ZH)**: RemoteRAG：一种隐私 preservation 的云大语言模型检索即服务（RAG）服务 

**Authors**: Yihang Cheng, Lan Zhang, Junyang Wang, Mu Yuan, Yunhao Yao  

**Link**: [PDF](https://arxiv.org/pdf/2412.12775)  

**Abstract**: Retrieval-augmented generation (RAG) improves the service quality of large language models by retrieving relevant documents from credible literature and integrating them into the context of the user query. Recently, the rise of the cloud RAG service has made it possible for users to query relevant documents conveniently. However, directly sending queries to the cloud brings potential privacy leakage. In this paper, we are the first to formally define the privacy-preserving cloud RAG service to protect the user query and propose RemoteRAG as a solution regarding privacy, efficiency, and accuracy. For privacy, we introduce $(n,\epsilon)$-DistanceDP to characterize privacy leakage of the user query and the leakage inferred from relevant documents. For efficiency, we limit the search range from the total documents to a small number of selected documents related to a perturbed embedding generated from $(n,\epsilon)$-DistanceDP, so that computation and communication costs required for privacy protection significantly decrease. For accuracy, we ensure that the small range includes target documents related to the user query with detailed theoretical analysis. Experimental results also demonstrate that RemoteRAG can resist existing embedding inversion attack methods while achieving no loss in retrieval under various settings. Moreover, RemoteRAG is efficient, incurring only $0.67$ seconds and $46.66$KB of data transmission ($2.72$ hours and $1.43$ GB with the non-optimized privacy-preserving scheme) when retrieving from a total of $10^6$ documents. 

**Abstract (ZH)**: 检索增强生成（RAG）通过从可信文献中检索相关文档并将其集成到用户的查询上下文中，从而提高大型语言模型的服务质量。最近，云RAG服务的兴起使得用户能够方便地查询相关文档。然而，直接将查询发送到云中会带来潜在的隐私泄露风险。本文首次正式定义了保护用户查询隐私的云RAG服务，并提出RemoteRAG作为在隐私、效率和准确性方面的一揽子解决方案。为了保护隐私，我们引入了$(n, \epsilon)$-DistanceDP来表征用户查询及其从相关文档推理出的隐私泄露。为了提高效率，我们将搜索范围限定在从$(n, \epsilon)$-DistanceDP生成的扰动嵌入中相关的少量文档上，从而显著降低用于隐私保护的计算和通信成本。为了保证准确性，我们通过详细的理论分析确保该小范围包括与用户查询相关的目标文档。实验结果还表明，RemoteRAG能够在各种设置下抵御现有的嵌入反向攻击方法，并且在检索损失方面的表现与现有方法相当。此外，当从总共$10^6$份文档中检索时，RemoteRAG表现出高效性，仅需0.67秒和46.66KB的数据传输量（在未优化的隐私保护方案下分别为2.72小时和1.43GB）。 

---
# A Survey on Sequential Recommendation 

**Title (ZH)**: 序列推荐综述 

**Authors**: Liwei Pan, Weike Pan, Meiyan Wei, Hongzhi Yin, Zhong Ming  

**Link**: [PDF](https://arxiv.org/pdf/2412.12770)  

**Abstract**: Different from most conventional recommendation problems, sequential recommendation focuses on learning users' preferences by exploiting the internal order and dependency among the interacted items, which has received significant attention from both researchers and practitioners. In recent years, we have witnessed great progress and achievements in this field, necessitating a new survey. In this survey, we study the SR problem from a new perspective (i.e., the construction of an item's properties), and summarize the most recent techniques used in sequential recommendation such as pure ID-based SR, SR with side information, multi-modal SR, generative SR, LLM-powered SR, ultra-long SR and data-augmented SR. Moreover, we introduce some frontier research topics in sequential recommendation, e.g., open-domain SR, data-centric SR, could-edge collaborative SR, continuous SR, SR for good, and explainable SR. We believe that our survey could be served as a valuable roadmap for readers in this field. 

**Abstract (ZH)**: 与大多数传统的推荐问题不同，序列推荐专注于通过利用交互项目之间的内部顺序和依赖关系来学习用户的偏好，这受到了研究人员和从业人员的广泛关注。近年来，该领域取得了显著的进步和成果，亟需进行新的综述。在本次综述中，我们从一个新的视角（即项目的属性构建）研究序列推荐问题，并总结了最近在序列推荐中使用的技术，如基于ID的序列推荐、带有侧信息的序列推荐、多模态序列推荐、生成式序列推荐、基于大语言模型的序列推荐、超长期序列推荐以及数据增强的序列推荐。此外，我们还介绍了序列推荐领域的前沿研究课题，例如开放域序列推荐、以数据为中心的序列推荐、边缘-云端协作序列推荐、持续序列推荐、有益的序列推荐以及可解释的序列推荐。我们相信，本综述能够为该领域的读者提供一份宝贵的技术路线图。 

---
# Token-Level Graphs for Short Text Classification 

**Title (ZH)**: 短文本分类中的令牌级图方法 

**Authors**: Gregor Donabauer, Udo Kruschwitz  

**Link**: [PDF](https://arxiv.org/pdf/2412.12754)  

**Abstract**: The classification of short texts is a common subtask in Information Retrieval (IR). Recent advances in graph machine learning have led to interest in graph-based approaches for low resource scenarios, showing promise in such settings. However, existing methods face limitations such as not accounting for different meanings of the same words or constraints from transductive approaches. We propose an approach which constructs text graphs entirely based on tokens obtained through pre-trained language models (PLMs). By applying a PLM to tokenize and embed the texts when creating the graph(-nodes), our method captures contextual and semantic information, overcomes vocabulary constraints, and allows for context-dependent word meanings. Our approach also makes classification more efficient with reduced parameters compared to classical PLM fine-tuning, resulting in more robust training with few samples. Experimental results demonstrate how our method consistently achieves higher scores or on-par performance with existing methods, presenting an advancement in graph-based text classification techniques. To support reproducibility of our work we make all implementations publicly available to the community\footnote{\url{this https URL}}. 

**Abstract (ZH)**: 短文本分类是信息检索（IR）中的一个常见子任务。近年来，图机器学习的进步激发了对基于图的方法的研究兴趣，这些方法在低资源场景下显示出潜力。然而，现有方法面临一些限制，例如没有考虑到同义词在不同语境中的不同含义，或者来自归纳学习方法的约束。我们提出了一种基于预训练语言模型（PLMs）获取的标记构建文本图的方法。在创建图（节点）时，通过应用PLM对文本进行分词和嵌入，我们的方法能够捕获上下文和语义信息，克服词汇量的限制，并允许单词含义依赖于上下文。此外，与传统的PLM微调相比，我们的方法减少了参数数量，使得分类更高效，并能以少量样本进行更稳健的训练。实验结果表明，我们的方法在某些指标上持续优于或与现有方法持平，代表了图基文本分类技术的进步。为支持研究的可重复性，我们已将所有实现公开给社区（\url{此链接}）。 

---
# Boosting LLM-based Relevance Modeling with Distribution-Aware Robust Learning 

**Title (ZH)**: 基于分布感知的稳健学习提升基于LLM的相关性建模 

**Authors**: Hong Liu, Saisai Gong, Yixin Ji, Kaixin Wu, Jia Xu, Jinjie Gu  

**Link**: [PDF](https://arxiv.org/pdf/2412.12504)  

**Abstract**: With the rapid advancement of pre-trained large language models (LLMs), recent endeavors have leveraged the capabilities of LLMs in relevance modeling, resulting in enhanced performance. This is usually done through the process of fine-tuning LLMs on specifically annotated datasets to determine the relevance between queries and items. However, there are two limitations when LLMs are naively employed for relevance modeling through fine-tuning and inference. First, it is not inherently efficient for performing nuanced tasks beyond simple yes or no answers, such as assessing search relevance. It may therefore tend to be overconfident and struggle to distinguish fine-grained degrees of relevance (e.g., strong relevance, weak relevance, irrelevance) used in search engines. Second, it exhibits significant performance degradation when confronted with data distribution shift in real-world scenarios. In this paper, we propose a novel Distribution-Aware Robust Learning framework (DaRL) for relevance modeling in Alipay Search. Specifically, we design an effective loss function to enhance the discriminability of LLM-based relevance modeling across various fine-grained degrees of query-item relevance. To improve the generalizability of LLM-based relevance modeling, we first propose the Distribution-Aware Sample Augmentation (DASA) module. This module utilizes out-of-distribution (OOD) detection techniques to actively select appropriate samples that are not well covered by the original training set for model fine-tuning. Furthermore, we adopt a multi-stage fine-tuning strategy to simultaneously improve in-distribution (ID) and OOD performance, bridging the performance gap between them. DaRL has been deployed online to serve the Alipay's insurance product search... 

**Abstract (ZH)**: 随着预训练大型语言模型（LLMs）的迅速发展，近期的研究已经在利用LLMs在相关性建模方面的的能力，从而提升了模型性能。这通常是通过在特注注释的数据集上对LLMs进行微调来实现的，以确定查询与项目之间的相关性。然而，当LLMs简单地通过微调和推理来进行相关性建模时，存在两个局限性。首先，对于超越简单“是”或“否”的细致任务（例如，评估搜索相关性）来说，它未必是高效的。因此，模型可能会变得过于自信，并在区分细粒度的相关性程度（例如，高度相关、弱相关、不相关）方面遇到困难。其次，当面对现实世界中的数据分布偏移时，其性能会显著下降。在本文中，我们提出了一个新颖的面向分布的鲁棒学习框架（DaRL）来解决支付宝搜索中相关性建模的问题。具体而言，我们设计了一个有效的损失函数，以增强基于LLMs的相关性建模在不同细粒度查询-项目相关性方面的辨别能力。为了提高基于LLMs的相关性建模的泛化能力，我们首先提出了面向分布的样本增强（DASA）模块。该模块利用了离群值检测技术来主动选择那些原始训练集未能充分覆盖的适当样本，用于模型微调。进一步地，我们采用了多阶段微调策略以同时提升数据分布内（ID）和离群值（OOD）环境下的性能，从而弥合它们之间的性能差距。DaRL已被部署上线，服务于支付宝的保险产品搜索... 

---
# LLM is Knowledge Graph Reasoner: LLM's Intuition-aware Knowledge Graph Reasoning for Cold-start Sequential Recommendation 

**Title (ZH)**: 大语言模型是知识图谱推理器：大语言模型的基于直觉的知识图谱推理在冷启动序列推荐中的应用 

**Authors**: Keigo Sakurai, Ren Togo, Takahiro Ogawa, Miki Haseyama  

**Link**: [PDF](https://arxiv.org/pdf/2412.12464)  

**Abstract**: Knowledge Graphs (KGs) represent relationships between entities in a graph structure and have been widely studied as promising tools for realizing recommendations that consider the accurate content information of items. However, traditional KG-based recommendation methods face fundamental challenges: insufficient consideration of temporal information and poor performance in cold-start scenarios. On the other hand, Large Language Models (LLMs) can be considered databases with a wealth of knowledge learned from the web data, and they have recently gained attention due to their potential application as recommendation systems. Although approaches that treat LLMs as recommendation systems can leverage LLMs' high recommendation literacy, their input token limitations make it impractical to consider the entire recommendation domain dataset and result in scalability issues. To address these challenges, we propose a LLM's Intuition-aware Knowledge graph Reasoning model (LIKR). Our main idea is to treat LLMs as reasoners that output intuitive exploration strategies for KGs. To integrate the knowledge of LLMs and KGs, we trained a recommendation agent through reinforcement learning using a reward function that integrates different recommendation strategies, including LLM's intuition and KG embeddings. By incorporating temporal awareness through prompt engineering and generating textual representations of user preferences from limited interactions, LIKR can improve recommendation performance in cold-start scenarios. Furthermore, LIKR can avoid scalability issues by using KGs to represent recommendation domain datasets and limiting the LLM's output to KG exploration strategies. Experiments on real-world datasets demonstrate that our model outperforms state-of-the-art recommendation methods in cold-start sequential recommendation scenarios. 

**Abstract (ZH)**: 知识图谱（KGs）将实体之间的关系表示为图结构，并且被广泛研究作为一种能够考虑项目准确内容信息的推荐工具。然而，传统的基于KG的推荐方法面临根本性的挑战：缺乏对时间信息的充分考虑以及在冷启动场景中的表现不佳。另一方面，大型语言模型（LLMs）可以被视为从网络数据中学习了大量的知识的数据库，并且由于其在推荐系统中潜在的应用而近期引起了人们的关注。尽管将LLMs视为推荐系统的做法可以利用LLMs的高推荐素养，但由于输入令牌的限制，使得完全考虑推荐领域数据集变得不切实际，从而导致可扩展性问题。为了解决这些挑战，我们提出了一种LLM启发的知识图谱推理模型（LIKR）。我们的主要想法是将LLMs视为能够输出KGs直观探索策略的推理器。为了整合LLMs和KGs的知识，我们通过强化学习训练了一个推荐代理，使用的奖励函数综合了不同的推荐策略，包括LLMs的直觉和KG嵌入。通过工程化提示引入时间感知性，并从有限的交互中生成用户偏好的文本表示，LIKR能够在冷启动场景中提高推荐性能。此外，通过使用KGs来表示推荐领域数据集并且限制LLMs的输出为KG探索策略，LIKR解决了可扩展性问题。实验表明，在实际数据集上，我们的模型在冷启动序列推荐场景中优于最先进的推荐方法。 

---
# Searching Personal Collections 

**Title (ZH)**: 搜索个人收藏 

**Authors**: Michael Bendersky, Donald Metzler, Marc Najork, Xuanhui Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.12330)  

**Abstract**: This article describes the history of information retrieval on personal document collections. 

**Abstract (ZH)**: 本文描述了个人文档集合信息检索的历史。 

---
# Enhancing the conformal predictability of context-aware recommendation systems by using Deep Autoencoders 

**Title (ZH)**: 通过使用深度自编码器增强基于上下文的推荐系统中的预测一致性 

**Authors**: Saloua Zammali, Siddhant Dutta, Sadok Ben Yahia  

**Link**: [PDF](https://arxiv.org/pdf/2412.12110)  

**Abstract**: In the field of Recommender Systems (RS), neural collaborative filtering represents a significant milestone by combining matrix factorization and deep neural networks to achieve promising results. Traditional methods like matrix factorization often rely on linear models, limiting their capability to capture complex interactions between users, items, and contexts. This limitation becomes particularly evident with high-dimensional datasets due to their inability to capture relationships among users, items, and contextual factors. Unsupervised learning and dimension reduction tasks utilize autoencoders, neural network-based models renowned for their capacity to encode and decode data. Autoencoders learn latent representations of inputs, reducing dataset size while capturing complex patterns and features. In this paper, we introduce a framework that combines neural contextual matrix factorization with autoencoders to predict user ratings for items. We provide a comprehensive overview of the framework's design and implementation. To evaluate its performance, we conduct experiments on various real-world datasets and compare the results against state-of-the-art approaches. We also extend the concept of conformal prediction to prediction rating and introduce a Conformal Prediction Rating (CPR). For RS, we define the nonconformity score, a key concept of conformal prediction, and demonstrate that it satisfies the exchangeability property. 

**Abstract (ZH)**: 在推荐系统（RS）领域的研究中，神经协同过滤（Neural Collaborative Filtering, NCF）代表了一项重要里程碑，通过结合矩阵分解和深度神经网络，实现了令人瞩目的成果。传统的矩阵分解等方法往往依赖于线性模型，限制了其捕捉用户、商品和情境之间复杂交互的能力。在高维数据集中，这一限制尤为明显，因为这些方法无法捕捉用户、商品和情境因素之间的关系。无监督学习和降维任务使用自编码器（Autoencoders），这是一种基于神经网络的模型，以能够编码和解码数据而闻名。自编码器学习输入的潜在表示，从而减少数据集的大小同时捕捉复杂的模式和特征。在本文中，我们提出了一种框架，将神经上下文矩阵分解与自编码器相结合，用于预测用户对项目的评分。我们提供了该框架的设计和实现的全面概述。为了评估其性能，我们在多种实际数据集上进行了实验，并将结果与最先进的方法进行了对比。我们还扩展了可信推理的概念到评分预测，并引入了一种可信预测评分（CPR）。对于推荐系统，我们定义了非同效力分数，这是可信推理中的一个重要概念，并证明其满足交换性属性。 

---
# Re-calibrating methodologies in social media research: Challenge the visual, work with Speech 

**Title (ZH)**: 在社交媒体研究中重新校准方法论：质疑视觉呈现，侧重语音数据 

**Authors**: Hongrui Jin  

**Link**: [PDF](https://arxiv.org/pdf/2412.13170)  

**Abstract**: This article methodologically reflects on how social media scholars can effectively engage with speech-based data in their analyses. While contemporary media studies have embraced textual, visual, and relational data, the aural dimension remained comparatively under-explored. Building on the notion of secondary orality and rejection towards purely visual culture, the paper argues that considering voice and speech at scale enriches our understanding of multimodal digital content. The paper presents the TikTok Subtitles Toolkit that offers accessible speech processing readily compatible with existing workflows. In doing so, it opens new avenues for large-scale inquiries that blend quantitative insights with qualitative precision. Two illustrative cases highlight both opportunities and limitations of speech research: while genres like #storytime on TikTok benefit from the exploration of spoken narratives, nonverbal or music-driven content may not yield significant insights using speech data. The article encourages researchers to integrate aural exploration thoughtfully to complement existing methods, rather than replacing them. I conclude that the expansion of our methodological repertoire enables richer interpretations of platformised content, and our capacity to unpack digital cultures as they become increasingly multimodal. 

**Abstract (ZH)**: 本文从方法论的角度探讨了社会媒体研究者如何有效地分析基于言语的数据。尽管当前的媒体研究已经接受了文本、视觉和关系数据，但听觉维度相对较少被探索。基于次级口语音概念以及对纯粹视觉文化的拒绝，本文认为大规模考虑语音和言语能够丰富我们对多媒体数字内容的理解。本文介绍了TikTok字幕工具包，该工具包提供了易于访问的语音处理功能，与现有工作流程兼容。通过这种方式，它可以为结合定量洞察与定性精确性的大规模研究开辟新的途径。两个示例案例突出展示了言语研究的机遇和限制：例如，TikTok上的#storytime等体裁受益于对口语叙事的探索，而非言语或音乐驱动的内容可能不会从语音数据中获得显著的见解。本文鼓励研究人员有条不紊地整合听觉探索，以补充现有方法，而非取代它们。最终，本文认为扩大我们的方法论范式能够为我们提供更丰富的平台内容解读，帮助我们更深入地剖析日益多媒体化的数字文化。 

---
# C-FedRAG: A Confidential Federated Retrieval-Augmented Generation System 

**Title (ZH)**: C-FedRAG：一种保密联邦检索增强生成系统 

**Authors**: Parker Addison, Minh-Tuan H. Nguyen, Tomislav Medan, Mohammad T. Manzari, Brendan McElrone, Laksh Lalwani, Aboli More, Smita Sharma, Holger R. Roth, Isaac Yang, Chester Chen, Daguang Xu, Yan Cheng, Andrew Feng, Ziyue Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13163)  

**Abstract**: Organizations seeking to utilize Large Language Models (LLMs) for knowledge querying and analysis often encounter challenges in maintaining an LLM fine-tuned on targeted, up-to-date information that keeps answers relevant and grounded. Retrieval Augmented Generation (RAG) has quickly become a feasible solution for organizations looking to overcome the challenges of maintaining proprietary models and to help reduce LLM hallucinations in their query responses. However, RAG comes with its own issues regarding scaling data pipelines across tiered-access and disparate data sources. In many scenarios, it is necessary to query beyond a single data silo to provide richer and more relevant context for an LLM. Analyzing data sources within and across organizational trust boundaries is often limited by complex data-sharing policies that prohibit centralized data storage, therefore, inhibit the fast and effective setup and scaling of RAG solutions. In this paper, we introduce Confidential Computing (CC) techniques as a solution for secure Federated Retrieval Augmented Generation (FedRAG). Our proposed Confidential FedRAG system (C-FedRAG) enables secure connection and scaling of a RAG workflows across a decentralized network of data providers by ensuring context confidentiality. We also demonstrate how to implement a C-FedRAG system using the NVIDIA FLARE SDK and assess its performance using the MedRAG toolkit and MIRAGE benchmarking dataset. 

**Abstract (ZH)**: 组织希望利用大规模语言模型（LLMs）进行知识查询和分析时，常常面临维护一个针对特定且最新信息进行微调的LLM的挑战，这会导致答案的相关性和现实性受损。检索增强生成（RAG）迅速成为克服维护专有模型挑战和降低LLM在查询响应中产生幻觉可能性的可行解决方案。然而，RAG在大规模数据管道跨分层访问和不同数据源扩展时存在自身的问题。在许多情况下，为了提供更丰富和相关的情境，需要跨多个数据孤岛进行查询。分析组织信任边界内的数据源和跨边界的数据源常常受限于复杂的数据共享政策，这些政策禁止集中存储数据，从而阻碍了RAG解决方案的快速有效设置与扩展。在本文中，我们介绍保密计算（CC）技术作为一种安全联邦检索增强生成（FedRAG）的解决方案。我们提出的保密联邦RAG系统（C-FedRAG）通过确保上下文保密性，在分散的数据提供者网络中安全连接并扩展RAG工作流程。我们还展示了如何使用NVIDIA FLARE SDK实现C-FedRAG系统，并使用MedRAG工具包和MIRAGE基准测试数据集评估其性能。 

---