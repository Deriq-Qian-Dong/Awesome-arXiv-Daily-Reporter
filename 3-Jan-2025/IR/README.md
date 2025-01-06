# An Efficient Attention Mechanism for Sequential Recommendation Tasks: HydraRec 

**Title (ZH)**: 一种用于序列推荐任务的高效注意力机制：HydraRec 

**Authors**: Uzma Mushtaque  

**Link**: [PDF](https://arxiv.org/pdf/2501.01242)  

**Abstract**: Transformer based models are increasingly being used in various domains including recommender systems (RS). Pretrained transformer models such as BERT have shown good performance at language modelling. With the greater ability to model sequential tasks, variants of Encoder-only models (like BERT4Rec, SASRec etc.) have found success in sequential RS problems. Computing dot-product attention in traditional transformer models has quadratic complexity in sequence length. This is a bigger problem with RS because unlike language models, new items are added to the catalogue every day. User buying history is a dynamic sequence which depends on multiple factors. Recently, various linear attention models have tried to solve this problem by making the model linear in sequence length (token dimensions). Hydra attention is one such linear complexity model proposed for vision transformers which reduces the complexity of attention for both the number of tokens as well as model embedding dimensions. Building on the idea of Hydra attention, we introduce an efficient Transformer based Sequential RS (HydraRec) which significantly improves theoretical complexity of computing attention for longer sequences and bigger datasets while preserving the temporal context. Extensive experiments are conducted to evaluate other linear transformer-based RS models and compared with HydraRec across various evaluation metrics. HydraRec outperforms other linear attention-based models as well as dot-product based attention models when used with causal masking for sequential recommendation next item prediction tasks. For bi-directional models its performance is comparable to the BERT4Rec model with an improvement in running time. 

**Abstract (ZH)**: 基于Transformer的模型在推荐系统（RS）等多个领域得到了越来越广泛的应用。预训练的Transformer模型如BERT在语言建模方面表现出色。由于具有更强的序贯任务建模能力，类似于BERT4Rec和SASRec的编码器仅模型也在序贯推荐系统问题中取得了成功。传统Transformer模型中的点积注意力机制在序列长度上具有二次复杂度，这对推荐系统来说是一个更大的问题。与语言模型不同，新的项目每天都会被加入到目录中。用户的购买历史是一个依赖于多种因素的动态序列。最近，各种线性注意力模型尝试通过使模型在序列长度（token维度）上呈现线性复杂度来解决这一问题。Hydra注意力是一种为视觉Transformer设计的线性复杂度模型，可以降低注意力的复杂度，不仅对token数量，而且对模型嵌入维度都有益。在此基础上，我们引入了高效的基于Transformer的序贯推荐系统(HydraRec)，它在保留时间上下文的同时，显著提高了在更长序列和更大数据集上计算注意力的理论复杂度。进行了广泛的实验来评估其他线性Transformer推荐系统模型，并在各种评估指标下与HydraRec进行了比较。当用于因果掩码的序列推荐下一个项目预测任务时，HydraRec优于其他基于线性注意力的模型以及基于点积注意力的模型。对于双向模型来说，其性能与BERT4Rec模型相当，并且在运行时间上有所改进。 

---
# Search Plurality 

**Title (ZH)**: “Search Plurality” 在学术论文中可以翻译为“搜索多样性”或“搜索多元性”。具体选择哪种翻译可以根据上下文进行调整，如下所示：

- **Search Plurality**: 搜索多样性
- **Search Plurality in Optimization Algorithms**: 优化算法中的搜索多样性

如果有更具体的背景信息或上下文，请提供，以便给出更准确的翻译。 

**Authors**: Shiran Dudy  

**Link**: [PDF](https://arxiv.org/pdf/2501.00987)  

**Abstract**: In light of Phillips' contention regarding the impracticality of Search Neutrality, asserting that non-epistemic factors presently dictate result prioritization, our objective in this study is to confront this constraint by questioning prevailing design practices in search engines. We posit that the concept of prioritization warrants scrutiny, along with the consistent hierarchical ordering that underlies this lack of neutrality. We introduce the term Search Plurality to encapsulate the idea of emphasizing the various means a query can be approached. This is demonstrated in a design that prioritizes the display of categories over specific search items, helping users grasp the breadth of their search. Whether a query allows for multiple interpretations or invites diverse opinions, the presentation of categories highlights the significance of organizing data based on relevance, importance, and relative significance, akin to traditional methods. However, unlike previous approaches, this method enriches our comprehension of the overall information landscape, countering the potential bias introduced by ranked lists. 

**Abstract (ZH)**: 鉴于Phillips关于搜索引擎中搜索中立性难以实现的主张，认为当前结果优先级主要由非知识性因素决定，本研究旨在通过质疑搜索引擎现有的设计实践来应对这一限制。我们提出，优先级的概念本身需要受到审视，同时其背后的持续层级排序也体现了一种缺乏中立性的状态。我们提出了“搜索多元性”（Search Plurality）的概念，以强调查询可以采用的各种途径。这一概念通过在设计中优先展示类别而非具体搜索项来体现，帮助用户理解搜索的广泛性。无论是查询内容可能有多重解释，还是激发多样意见，类别展示都突出了根据相关性、重要性和相对重要性组织数据的重要性，类似于传统方法。然而，与以往的方法不同，这种方法增强了我们对整体信息景观的理解，从而抵消了排名列表可能引入的潜在偏见。 

---
# S-Diff: An Anisotropic Diffusion Model for Collaborative Filtering in Spectral Domain 

**Title (ZH)**: S-Diff：谱域中具有各向异性扩散的协同过滤模型 

**Authors**: Rui Xia, Yanhua Cheng, Yongxiang Tang, Xiaocheng Liu, Xialong Liu, Lisong Wang, Peng Jiang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00384)  

**Abstract**: Recovering user preferences from user-item interaction matrices is a key challenge in recommender systems. While diffusion models can sample and reconstruct preferences from latent distributions, they often fail to capture similar users' collective preferences effectively. Additionally, latent variables degrade into pure Gaussian noise during the forward process, lowering the signal-to-noise ratio, which in turn degrades performance. To address this, we propose S-Diff, inspired by graph-based collaborative filtering, better to utilize low-frequency components in the graph spectral domain. S-Diff maps user interaction vectors into the spectral domain and parameterizes diffusion noise to align with graph frequency. This anisotropic diffusion retains significant low-frequency components, preserving a high signal-to-noise ratio. S-Diff further employs a conditional denoising network to encode user interactions, recovering true preferences from noisy data. This method achieves strong results across multiple datasets. 

**Abstract (ZH)**: 从用户-项交互矩阵中恢复用户偏好是推荐系统中的一个关键挑战。虽然扩散模型可以从潜在分布中采样和重构偏好，但它们往往难以有效地捕捉相似用户集体偏好的特性。此外，在前向过程中，潜在变量退化为纯高斯噪声，降低了信噪比，从而影响性能。为了解决这个问题，我们提出了S-Diff，该方法借鉴了基于图的合作过滤，更好地利用图频域中的低频分量。S-Diff将用户交互向量映射到频域，并对扩散噪声进行参数化，使其与图频率对齐。这种各向异性扩散保留了大量低频分量，从而保持了较高的信噪比。S-Diff进一步采用条件去噪网络来编码用户交互，从噪声数据中恢复真实的偏好。该方法在多个数据集中都取得了良好的效果。 

---
# Who Gets Recommended? Investigating Gender, Race, and Country Disparities in Paper Recommendations from Large Language Models 

**Title (ZH)**: 谁会被推荐？大型语言模型在论文推荐中的性别、种族和国家差异研究 

**Authors**: Yifan Tian, Yixin Liu, Yi Bu, Jiqun Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00367)  

**Abstract**: This paper investigates the performance of several representative large models in the tasks of literature recommendation and explores potential biases in research exposure. The results indicate that not only LLMs' overall recommendation accuracy remains limited but also the models tend to recommend literature with greater citation counts, later publication date, and larger author teams. Yet, in scholar recommendation tasks, there is no evidence that LLMs disproportionately recommend male, white, or developed-country authors, contrasting with patterns of known human biases. 

**Abstract (ZH)**: 本文研究了几种代表性的大规模模型在文献推荐任务中的性能，并探讨了研究曝光中的潜在偏差。结果表明，不仅LLMs的整体推荐准确性有限，而且模型更倾向于推荐引用次数更多、发表日期较晚以及作者团队更大的文献。然而，在学者推荐任务中，并没有证据表明LLMs会不当地推荐男性、白人或发达国家的作者，与已知的人类偏差模式相反。 

---
# Retrieval-Augmented Generation with Graphs (GraphRAG) 

**Title (ZH)**: 基于图的检索增强生成（GraphRAG） 

**Authors**: Haoyu Han, Yu Wang, Harry Shomer, Kai Guo, Jiayuan Ding, Yongjia Lei, Mahantesh Halappanavar, Ryan A. Rossi, Subhabrata Mukherjee, Xianfeng Tang, Qi He, Zhigang Hua, Bo Long, Tong Zhao, Neil Shah, Amin Javari, Yinglong Xia, Jiliang Tang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00309)  

**Abstract**: Retrieval-augmented generation (RAG) is a powerful technique that enhances downstream task execution by retrieving additional information, such as knowledge, skills, and tools from external sources. Graph, by its intrinsic "nodes connected by edges" nature, encodes massive heterogeneous and relational information, making it a golden resource for RAG in tremendous real-world applications. As a result, we have recently witnessed increasing attention on equipping RAG with Graph, i.e., GraphRAG. However, unlike conventional RAG, where the retriever, generator, and external data sources can be uniformly designed in the neural-embedding space, the uniqueness of graph-structured data, such as diverse-formatted and domain-specific relational knowledge, poses unique and significant challenges when designing GraphRAG for different domains. Given the broad applicability, the associated design challenges, and the recent surge in GraphRAG, a systematic and up-to-date survey of its key concepts and techniques is urgently desired. Following this motivation, we present a comprehensive and up-to-date survey on GraphRAG. Our survey first proposes a holistic GraphRAG framework by defining its key components, including query processor, retriever, organizer, generator, and data source. Furthermore, recognizing that graphs in different domains exhibit distinct relational patterns and require dedicated designs, we review GraphRAG techniques uniquely tailored to each domain. Finally, we discuss research challenges and brainstorm directions to inspire cross-disciplinary opportunities. Our survey repository is publicly maintained at this https URL. 

**Abstract (ZH)**: 基于检索增强生成（RAG）是一种强大的技术，它通过从外部来源检索额外的信息（如知识、技能和工具）来增强下游任务的执行。由于其基本的“节点通过边连接”的特性，图能够编码大量的异构和关系信息，使其成为RAG在大量实际应用中的宝贵资源。因此，我们最近见证了越来越多的注意力被集中在将图与RAG结合使用上，即GraphRAG。然而，与传统RAG不同，在传统RAG中检索器、生成器和外部数据源可以均匀地设计在神经嵌入空间中，图结构数据的独特性，如多种格式和特定领域的关系知识，为设计适用于不同领域的GraphRAG带来了独特而重要的挑战。考虑到其广泛的应用领域、相关的设计挑战以及GraphRAG的最近增长，系统地且最新的GraphRAG的关键概念和技术的综述是迫切需要的。出于这一动机，我们提供了一篇全面且最新的GraphRAG综述。我们的综述首先提出了一种完整的GraphRAG框架，通过定义其关键组件，包括查询处理器、检索器、组织器、生成器和数据源。此外，考虑到不同领域的图表现出不同的关系模式并需要专门的设计，我们回顾了针对每个领域的GraphRAG技术。最后，我们讨论了研究挑战并提出了跨学科机遇的方向。我们的综述库在此网址公开维护：[https://github.com/your-repo-name]。 

---
# NewsHomepages: Homepage Layouts Capture Information Prioritization Decisions 

**Title (ZH)**: 新闻主页布局：主页布局捕捉信息优先级决策 

**Authors**: Ben Welsh, Naitian Zhou, Arda Kaz, Michael Vu, Alexander Spangher  

**Link**: [PDF](https://arxiv.org/pdf/2501.00004)  

**Abstract**: Information prioritization plays an important role in how humans perceive and understand the world. Homepage layouts serve as a tangible proxy for this prioritization. In this work, we present NewsHomepages, a large dataset of over 3,000 new website homepages (including local, national and topic-specific outlets) captured twice daily over a three-year period. We develop models to perform pairwise comparisons between news items to infer their relative significance. To illustrate that modeling organizational hierarchies has broader implications, we applied our models to rank-order a collection of local city council policies passed over a ten-year period in San Francisco, assessing their "newsworthiness". Our findings lay the groundwork for leveraging implicit organizational cues to deepen our understanding of information prioritization. 

**Abstract (ZH)**: 信息优先级在人类如何感知和理解世界中起着重要作用。主页布局为这种优先级提供了一个具体的代理。在这项工作中，我们介绍了NewsHomepages，这是一个包含超过3000个新闻网站主页的大数据集（包括地方、国家级和特定主题的出版物），这些主页在过去三年中每天被捕捉两次。我们开发了模型来进行新闻项目的两两比较，以推断它们的相对重要性。为了说明模型组织层次结构的含义更为广泛，我们将这些模型应用于对旧金山过去十年通过的地方城市议会政策进行排名，并评估它们的“新闻价值”。我们的发现为进一步利用隐含的组织线索深入理解信息优先级奠定了基础。 

---
# On the Robustness of Cover Version Identification Models: A Study Using Cover Versions from YouTube 

**Title (ZH)**: 关于Cover Version Identification模型的鲁棒性研究：基于YouTube的Cover版本数据 

**Authors**: Simon Hachmeier, Robert Jäschke  

**Link**: [PDF](https://arxiv.org/pdf/2501.01333)  

**Abstract**: Recent advances in cover song identification have shown great success. However, models are usually tested on a fixed set of datasets which are relying on the online cover song database SecondHandSongs. It is unclear how well models perform on cover songs on online video platforms, which might exhibit alterations that are not expected. In this paper, we annotate a subset of songs from YouTube sampled by a multi-modal uncertainty sampling approach and evaluate state-of-the-art models. We find that existing models achieve significantly lower ranking performance on our dataset compared to a community dataset. We additionally measure the performance of different types of versions (e.g., instrumental versions) and find several types that are particularly hard to rank. Lastly, we provide a taxonomy of alterations in cover versions on the web. 

**Abstract (ZH)**: 近年来，音乐覆盖识别领域的研究取得了显著成果。然而，这些模型通常仅在依赖于SecondHandSongs在线曲目数据库的一组固定数据集上进行测试。对于在线视频平台上出现的覆盖歌曲，模型的表现情况尚不清楚，这些歌曲可能存在不可预期的修改。本文采用多模态不确定性抽样方法从YouTube中选定一部分歌曲进行标注，并评估当前最先进的模型。我们发现，现有模型在我们数据集上的排名性能显著低于社区数据集中的性能。此外，我们还测量了不同版本（如纯乐器版本）的性能，并发现一些特定类型的版本尤其难以进行排名。最后，我们提供了一份网络中覆盖版本修改类型的分类体系。 

---
# Domain-invariant feature learning in brain MR imaging for content-based image retrieval 

**Title (ZH)**: 基于内容的图像检索中脑部MRI成像的领域不变特征学习 

**Authors**: Shuya Tobari, Shuhei Tomoshige, Hayato Muraki, Kenichi Oishi, Hitoshi Iyatomi  

**Link**: [PDF](https://arxiv.org/pdf/2501.01326)  

**Abstract**: When conducting large-scale studies that collect brain MR images from multiple facilities, the impact of differences in imaging equipment and protocols at each site cannot be ignored, and this domain gap has become a significant issue in recent years. In this study, we propose a new low-dimensional representation (LDR) acquisition method called style encoder adversarial domain adaptation (SE-ADA) to realize content-based image retrieval (CBIR) of brain MR images. SE-ADA reduces domain differences while preserving pathological features by separating domain-specific information from LDR and minimizing domain differences using adversarial learning.
In evaluation experiments comparing SE-ADA with recent domain harmonization methods on eight public brain MR datasets (ADNI1/2/3, OASIS1/2/3/4, PPMI), SE-ADA effectively removed domain information while preserving key aspects of the original brain structure and demonstrated the highest disease search accuracy. 

**Abstract (ZH)**: 在从多个医疗机构收集脑磁共振成像（MR图像）的大规模研究中，每个场地的成像设备和协议的差异不容忽视，这一领域差距已成为近年来的重要问题。为解决这一问题，本研究提出了一种新的低维表示（LDR）获取方法——风格编码对抗领域适应（SE-ADA），用于实现基于内容的图像检索（CBIR）脑磁共振图像。SE-ADA通过分离LDR中的领域特定信息，并利用对抗学习最小化领域差异，从而减少领域差异同时保留病理特征。

在与八个公开的脑MR数据集（ADNI1/2/3、OASIS1/2/3/4、PPMI）中的近期领域谐调方法进行评估实验中，SE-ADA成功地去除了领域信息，同时保留了原始脑结构的关键方面，并展示了最高的疾病搜索准确性。 

---
# LUSIFER: Language Universal Space Integration for Enhanced Multilingual Embeddings with Large Language Models 

**Title (ZH)**: LUSIFER：语言通用空间集成以增强大型语言模型的多语言嵌入 

**Authors**: Hieu Man, Nghia Trung Ngo, Viet Dac Lai, Ryan A. Rossi, Franck Dernoncourt, Thien Huu Nguyen  

**Link**: [PDF](https://arxiv.org/pdf/2501.00874)  

**Abstract**: Recent advancements in large language models (LLMs) based embedding models have established new state-of-the-art benchmarks for text embedding tasks, particularly in dense vector-based retrieval. However, these models predominantly focus on English, leaving multilingual embedding capabilities largely unexplored. To address this limitation, we present LUSIFER, a novel zero-shot approach that adapts LLM-based embedding models for multilingual tasks without requiring multilingual supervision. LUSIFER's architecture combines a multilingual encoder, serving as a language-universal learner, with an LLM-based embedding model optimized for embedding-specific tasks. These components are seamlessly integrated through a minimal set of trainable parameters that act as a connector, effectively transferring the multilingual encoder's language understanding capabilities to the specialized embedding model. Additionally, to comprehensively evaluate multilingual embedding performance, we introduce a new benchmark encompassing 5 primary embedding tasks, 123 diverse datasets, and coverage across 14 languages. Extensive experimental results demonstrate that LUSIFER significantly enhances the multilingual performance across various embedding tasks, particularly for medium and low-resource languages, without requiring explicit multilingual training data. 

**Abstract (ZH)**: 基于大型语言模型（LLMs）的嵌入模型的最新进展已经为文本嵌入任务，特别是在密集向量检索中，设定了新的最先进基准。然而，这些模型主要集中在英语上，使得多语言嵌入能力的探索相对有限。为了解决这一局限性，我们提出LUSIFER，这是一种新颖的零样本方法，可以在无需多语言监督的情况下，将基于LLM的嵌入模型适应多语言任务。LUSIFER的架构结合了一个多语言编码器，作为一种语言通用的学习器，以及一个针对嵌入特定任务优化的基于LLM的嵌入模型。这些组件通过少量可训练参数无缝集成，这些参数充当连接器，有效地将多语言编码器的语言理解能力转移到专门的嵌入模型上。此外，为了全面评估多语言嵌入性能，我们引入了一个新的基准，该基准包括5项主要嵌入任务，123个多样化的数据集，并涵盖14种语言。广泛的实验结果表明，LUSIFER在各种嵌入任务中显著提高了多语言性能，特别是在中低资源语言方面，无需使用显式多语言训练数据。 

---
# DiffETM: Diffusion Process Enhanced Embedded Topic Model 

**Title (ZH)**: DiffETM：增强扩散过程的嵌入式主题模型 

**Authors**: Wei Shao, Mingyang Liu, Linqi Song  

**Link**: [PDF](https://arxiv.org/pdf/2501.00862)  

**Abstract**: The embedded topic model (ETM) is a widely used approach that assumes the sampled document-topic distribution conforms to the logistic normal distribution for easier optimization. However, this assumption oversimplifies the real document-topic distribution, limiting the model's performance. In response, we propose a novel method that introduces the diffusion process into the sampling process of document-topic distribution to overcome this limitation and maintain an easy optimization process. We validate our method through extensive experiments on two mainstream datasets, proving its effectiveness in improving topic modeling performance. 

**Abstract (ZH)**: 嵌入主题模型（ETM）是一种广泛应用的方法，假设抽样得到的文档-主题分布符合对数正态分布，以简化优化过程。然而，这一假设过于简化了真实的文档-主题分布，限制了模型的性能。为此，我们提出了一种新颖的方法，在文档-主题分布的抽样过程中引入扩散过程，以克服这一限制并保持优化过程的简便性。我们通过在两个主流数据集上进行广泛的实验来验证该方法的有效性，证明了其在提高主题建模性能方面的有效性。 

---
# Navigating Nuance: In Quest for Political Truth 

**Title (ZH)**: 探索微妙之处：追求政治真相 

**Authors**: Soumyadeep Sar, Dwaipayan Roy  

**Link**: [PDF](https://arxiv.org/pdf/2501.00782)  

**Abstract**: This study investigates the several nuanced rationales for countering the rise of political bias. We evaluate the performance of the Llama-3 (70B) language model on the Media Bias Identification Benchmark (MBIB), based on a novel prompting technique that incorporates subtle reasons for identifying political leaning. Our findings underscore the challenges of detecting political bias and highlight the potential of transfer learning methods to enhance future models. Through our framework, we achieve a comparable performance with the supervised and fully fine-tuned ConvBERT model, which is the state-of-the-art model, performing best among other baseline models for the political bias task on MBIB. By demonstrating the effectiveness of our approach, we contribute to the development of more robust tools for mitigating the spread of misinformation and polarization. Our codes and dataset are made publicly available in github. 

**Abstract (ZH)**: 本研究探讨了多种复杂的原因以应对政治偏见的上升。我们基于一种新颖的提示技术，该技术结合了识别政治倾向的微妙原因，评估了Llama-3（70B）语言模型在媒体偏见识别基准（MBIB）上的性能。我们的研究结果强调了检测政治偏见的挑战，并突显了迁移学习方法在未来模型中的潜在价值。通过我们的框架，我们在MBIB的政治理性任务中实现了与监督学习和完全微调的ConvBERT模型相当的表现，后者是当前最佳的基线模型。通过证明我们方法的有效性，我们为开发更 robust 的工具以减轻虚假信息和极化的蔓延做出了贡献。我们的代码和数据集已在GitHub上公开发布。 

---
# Dynamics of Adversarial Attacks on Large Language Model-Based Search Engines 

**Title (ZH)**: 大型语言模型为基础的搜索引擎中的对抗攻击动态解析 

**Authors**: Xiyang Hu  

**Link**: [PDF](https://arxiv.org/pdf/2501.00745)  

**Abstract**: The increasing integration of Large Language Model (LLM) based search engines has transformed the landscape of information retrieval. However, these systems are vulnerable to adversarial attacks, especially ranking manipulation attacks, where attackers craft webpage content to manipulate the LLM's ranking and promote specific content, gaining an unfair advantage over competitors. In this paper, we study the dynamics of ranking manipulation attacks. We frame this problem as an Infinitely Repeated Prisoners' Dilemma, where multiple players strategically decide whether to cooperate or attack. We analyze the conditions under which cooperation can be sustained, identifying key factors such as attack costs, discount rates, attack success rates, and trigger strategies that influence player behavior. We identify tipping points in the system dynamics, demonstrating that cooperation is more likely to be sustained when players are forward-looking. However, from a defense perspective, we find that simply reducing attack success probabilities can, paradoxically, incentivize attacks under certain conditions. Furthermore, defensive measures to cap the upper bound of attack success rates may prove futile in some scenarios. These insights highlight the complexity of securing LLM-based systems. Our work provides a theoretical foundation and practical insights for understanding and mitigating their vulnerabilities, while emphasizing the importance of adaptive security strategies and thoughtful ecosystem design. 

**Abstract (ZH)**: 基于大型语言模型（LLM）的搜索引擎日益集成，已经彻底改变了信息检索的格局。然而，这些系统容易受到对抗性攻击，尤其是排名操纵攻击，攻击者可以通过精心设计网页内容来操控LLM的排名，并推广特定内容，从而在竞争中获得不公平优势。在本文中，我们研究了排名操纵攻击的动态。我们将此问题框架化为无限重复的囚徒困境，多个参与者战略性地决定是合作还是攻击。我们分析了何种条件下合作可以持续存在，确定了影响参与者行为的关键因素，如攻击成本、折扣率、攻击成功率和触发策略。我们发现系统动态中的临界点，表明当参与者具有前瞻性思维时，合作更有可能持续存在。然而，从防御角度来看，我们发现简单地降低攻击成功率在某些情况下可能会意外地激励攻击。此外，限制攻击成功率上限的防御措施在某些情况下可能无效。这些见解突显了保护基于LLM的系统所面临的复杂性。我们的研究提供了理论基础和实用见解，有助于理解和减轻其脆弱性，同时强调了适应性安全策略和明智生态系统设计的重要性。 

---
# Fine-grained Video-Text Retrieval: A New Benchmark and Method 

**Title (ZH)**: 细粒度视频-文本检索：一个新的基准和方法 

**Authors**: Yifan Xu, Xinhao Li, Yichun Yang, Rui Huang, Limin Wang  

**Link**: [PDF](https://arxiv.org/pdf/2501.00513)  

**Abstract**: The ability of perceiving fine-grained spatial and temporal information is crucial for video-language retrieval. However, the existing video retrieval benchmarks, such as MSRVTT and MSVD, fail to efficiently evaluate the fine-grained retrieval ability of video-language models (VLMs) due to a lack of detailed annotations. To address this problem, we present FIBER, a FIne-grained BEnchmark for text to video Retrieval, containing 1,000 videos sourced from the FineAction dataset. Uniquely, our FIBER benchmark provides detailed human-annotated spatial annotations and temporal annotations for each video, making it possible to independently evaluate the spatial and temporal bias of VLMs on video retrieval task. Besides, we employ a text embedding method to unlock the capability of fine-grained video-language understanding of Multimodal Large Language Models (MLLMs). Surprisingly, the experiment results show that our Video Large Language Encoder (VLLE) performs comparably to CLIP-based models on traditional benchmarks and has a stronger capability of fine-grained representation with lower spatial-temporal bias. Project page: this https URL. 

**Abstract (ZH)**: 对细粒度空间和时间信息的感知能力对于视频-语言检索至关重要。然而，现有的视频检索基准，如MSRVTT和MSVD，未能有效评估视频-语言模型（VLMs）的细粒度检索能力，原因在于缺乏详细的标注。为解决这一问题，我们提出了FIBER（细粒度文本到视频检索基准），该基准包含来自FineAction数据集的1000个视频。独特之处在于，我们的FIBER基准提供了每个视频的详细的人工标注空间注释和时间注释，使得可以独立评估VLMs在视频检索任务中对空间和时间偏见的处理能力。此外，我们采用了文本嵌入方法，解锁了多模态大语言模型（MLLMs）对细粒度视频-语言理解的能力。令人惊讶的是，实验结果表明，我们的视频大语言编码器（VLLE）在传统基准上的表现与基于CLIP的模型相当，并且具有更低的空间-时间偏见和更强的细粒度表征能力。项目页面：[请将提供的URL补充完整]。 

---
# MAIN-RAG: Multi-Agent Filtering Retrieval-Augmented Generation 

**Title (ZH)**: MAIN-RAG：多代理过滤检索增强生成 

**Authors**: Chia-Yuan Chang, Zhimeng Jiang, Vineeth Rakesh, Menghai Pan, Chin-Chia Michael Yeh, Guanchu Wang, Mingzhi Hu, Zhichao Xu, Yan Zheng, Mahashweta Das, Na Zou  

**Link**: [PDF](https://arxiv.org/pdf/2501.00332)  

**Abstract**: Large Language Models (LLMs) are becoming essential tools for various natural language processing tasks but often suffer from generating outdated or incorrect information. Retrieval-Augmented Generation (RAG) addresses this issue by incorporating external, real-time information retrieval to ground LLM responses. However, the existing RAG systems frequently struggle with the quality of retrieval documents, as irrelevant or noisy documents degrade performance, increase computational overhead, and undermine response reliability. To tackle this problem, we propose Multi-Agent Filtering Retrieval-Augmented Generation (MAIN-RAG), a training-free RAG framework that leverages multiple LLM agents to collaboratively filter and score retrieved documents. Specifically, MAIN-RAG introduces an adaptive filtering mechanism that dynamically adjusts the relevance filtering threshold based on score distributions, effectively minimizing noise while maintaining high recall of relevant documents. The proposed approach leverages inter-agent consensus to ensure robust document selection without requiring additional training data or fine-tuning. Experimental results across four QA benchmarks demonstrate that MAIN-RAG consistently outperforms traditional RAG approaches, achieving a 2-11% improvement in answer accuracy while reducing the number of irrelevant retrieved documents. Quantitative analysis further reveals that our approach achieves superior response consistency and answer accuracy over baseline methods, offering a competitive and practical alternative to training-based solutions. 

**Abstract (ZH)**: 大规模语言模型（LLMs）已成为各种自然语言处理任务的重要工具，但常常会生成过时或不准确的信息。检索增强生成（RAG）通过结合外部的实时信息检索来确保LLM回答的准确性和相关性，解决了这一问题。然而，现有的RAG系统在检索文档的质量方面常常面临挑战，无关或噪声文档会降低性能、增加计算开销并削弱回答的可靠性。为了解决这一问题，我们提出了一种名为Multi-Agent Filtering Retrieval-Augmented Generation（MAIN-RAG）的无需训练的RAG框架，该框架利用多个LLM代理协作筛选和评估检索到的文档。具体来说，MAIN-RAG引入了一种自适应筛选机制，该机制会根据评分分布动态调整相关性筛选阈值，有效减少了噪声并保持了相关文档的高召回率。该方法利用代理间的共识来确保稳健的文档选择，而无需额外的训练数据或微调。在四个问答基准测试中的实验结果表明，MAIN-RAG 在回答准确性和减少无关检索文档数量方面始终优于传统的RAG方法。定量分析进一步表明，我们的方法在响应一致性和回答准确性方面优于基准方法，提供了基于训练的解决方案的有竞争力且实用的替代方案。 

---
# Exploring the Implicit Semantic Ability of Multimodal Large Language Models: A Pilot Study on Entity Set Expansion 

**Title (ZH)**: 探索多模态大型语言模型的隐含语义能力：实体集扩展的试点研究 

**Authors**: Hebin Wang, Yangning Li, Yinghui Li, Hai-Tao Zheng, Wenhao Jiang, Hong-Gee Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.00330)  

**Abstract**: The rapid development of multimodal large language models (MLLMs) has brought significant improvements to a wide range of tasks in real-world applications. However, LLMs still exhibit certain limitations in extracting implicit semantic information. In this paper, we apply MLLMs to the Multi-modal Entity Set Expansion (MESE) task, which aims to expand a handful of seed entities with new entities belonging to the same semantic class, and multi-modal information is provided with each entity. We explore the capabilities of MLLMs to understand implicit semantic information at the entity-level granularity through the MESE task, introducing a listwise ranking method LUSAR that maps local scores to global rankings. Our LUSAR demonstrates significant improvements in MLLM's performance on the MESE task, marking the first use of generative MLLM for ESE tasks and extending the applicability of listwise ranking. 

**Abstract (ZH)**: 多模态大型语言模型（MLLMs）的快速发展在广泛的实际应用场景中带来了显著的进步。然而，这些模型在提取隐含语义信息方面仍存在一定的局限性。在本文中，我们应用MLLMs到多模态实体集扩展（MESE）任务，该任务的目标是通过补充同一语义类别的新实体来扩展少量种子实体，并且每个实体还提供了多模态信息。我们通过MESE任务研究MLLMs在实体级别理解隐含语义信息的能力，并引入了一种名为LUSAR的列表级排名方法，将局部分数映射到全局排名。我们的LUSAR在MESE任务中显著提升了MLLMs的性能，标志着首次将生成性MLLM应用于ESE任务，并扩展了列表级排名的应用范围。 

---
# Towards Pattern-aware Data Augmentation for Temporal Knowledge Graph Completion 

**Title (ZH)**: 面向模式感知的数据增强方法研究：用于时间型知识图谱补全 

**Authors**: Jiasheng Zhang, Deqiang Ouyang, Shuang Liang, Jie Shao  

**Link**: [PDF](https://arxiv.org/pdf/2501.00252)  

**Abstract**: Predicting missing facts for temporal knowledge graphs (TKGs) is a fundamental task, called temporal knowledge graph completion (TKGC). One key challenge in this task is the imbalance in data distribution, where facts are unevenly spread across entities and timestamps. This imbalance can lead to poor completion performance or long-tail entities and timestamps, and unstable training due to the introduction of false negative samples. Unfortunately, few previous studies have investigated how to mitigate these effects. Moreover, for the first time, we found that existing methods suffer from model preferences, revealing that entities with specific properties (e.g., recently active) are favored by different models. Such preferences will lead to error accumulation and further exacerbate the effects of imbalanced data distribution, but are overlooked by previous studies. To alleviate the impacts of imbalanced data and model preferences, we introduce Booster, the first data augmentation strategy for TKGs. The unique requirements here lie in generating new samples that fit the complex semantic and temporal patterns within TKGs, and identifying hard-learning samples specific to models. Therefore, we propose a hierarchical scoring algorithm based on triadic closures within TKGs. By incorporating both global semantic patterns and local time-aware structures, the algorithm enables pattern-aware validation for new samples. Meanwhile, we propose a two-stage training approach to identify samples that deviate from the model's preferred patterns. With a well-designed frequency-based filtering strategy, this approach also helps to avoid the misleading of false negatives. Experiments justify that Booster can seamlessly adapt to existing TKGC models and achieve up to an 8.7% performance improvement. 

**Abstract (ZH)**: 时间知识图谱（TKGs）中缺失事实的预测是一项基础任务，被称为时间知识图谱完成（TKGC）。在这个任务中，一个主要的挑战是由数据分布的不平衡引起的，即事实在实体和时间戳之间分布不均。这种不平衡可能导致完成性能不佳，特别是对于长尾实体和时间戳，以及由于引入虚假负样本而导致的不稳定的训练过程。遗憾的是，很少有先前的研究探讨如何减轻这些影响。此外，本研究首次发现现有方法存在模型偏好问题，揭示出具有特定属性的实体（例如，最近活跃的实体）会被不同的模型优先处理。这样的偏好会导致误差累积，并进一步加剧数据分布不平衡的影响，但这些影响被先前的研究所忽视。为了缓解数据不平衡和模型偏好带来的影响，我们引入了Booster，这是首个专为TKGs设计的数据增强策略。这里的独特要求在于生成能够适应TKGs复杂语义和时间模式的新样本，并识别特定于模型的难以学习的样本。因此，我们提出了一种基于TKGs三元闭包的分层评分算法。通过结合全局语义模式和局部时间敏感结构，该算法能够为新样本提供模式感知的验证。同时，我们提出了两阶段训练方法来识别与模型偏好模式相偏离的样本。借助精心设计的基于频率的过滤策略，该方法也有助于避免虚假负样本造成的误导。实验结果表明，Booster能够无缝适应现有的TKGC模型，并实现最高8.7%的性能提升。 

---
# CancerKG.ORG A Web-scale, Interactive, Verifiable Knowledge Graph-LLM Hybrid for Assisting with Optimal Cancer Treatment and Care 

**Title (ZH)**: CancerKG.ORG：一个面向Web的大规模、交互式、可验证的知识图谱-LLM混合系统，用于辅助最佳癌症治疗与护理 

**Authors**: Michael Gubanov, Anna Pyayt, Aleksandra Karolak  

**Link**: [PDF](https://arxiv.org/pdf/2501.00223)  

**Abstract**: Here, we describe one of the first Web-scale hybrid Knowledge Graph (KG)-Large Language Model (LLM), populated with the latest peer-reviewed medical knowledge on colorectal Cancer. It is currently being evaluated to assist with both medical research and clinical information retrieval tasks at Moffitt Cancer Center, which is one of the top Cancer centers in the U.S. and in the world. Our hybrid is remarkable as it serves the user needs better than just an LLM, KG or a search-engine in isolation. LLMs as is are known to exhibit hallucinations and catastrophic forgetting as well as are trained on outdated corpora. The state of the art KGs, such as PrimeKG, cBioPortal, ChEMBL, NCBI, and other require manual curation, hence are quickly getting stale. CancerKG is unsupervised and is capable of automatically ingesting and organizing the latest medical findings. To alleviate the LLMs shortcomings, the verified KG serves as a Retrieval Augmented Generation (RAG) guardrail. CancerKG exhibits 5 different advanced user interfaces, each tailored to serve different data modalities better and more convenient for the user. 

**Abstract (ZH)**: 以下是符合学术规范的中文翻译：

这里，我们描述了一个早期的网络规模混合知识图谱（KG）-大型语言模型（LLM），该图谱包含了最新的同行评审医学知识，关于结直肠癌的信息。目前，该混合体正在莫菲特癌症中心进行评估，以协助医学研究和临床信息检索任务。莫菲特癌症中心是美国乃至世界顶尖的癌症中心之一。我们的混合体之所以令人瞩目，是因为它能够比单独使用LLM、KG或搜索引擎更好地满足用户需求。现有的大型语言模型已知存在幻觉和灾难性遗忘问题，并且是基于过时的语料库进行训练的。目前的先进知识图谱，如PrimeKG、cBioPortal、ChEMBL和NCBI等，需要人工维护，因此它们正在迅速变得过时。CancerKG是未监督的，并且能够自动摄取和组织最新的医学发现。为了弥补大型语言模型的不足，经过验证的知识图谱充当了检索增强生成（RAG）的护栏。CancerKG展示了5种不同的高级用户界面，每种界面都针对不同的数据模态进行了优化，使用户使用起来更加方便。 

---
# The Text Classification Pipeline: Starting Shallow going Deeper 

**Title (ZH)**: 文本分类流水线：从浅层迈向深层 

**Authors**: Marco Siino, Ilenia Tinnirello, Marco La Cascia  

**Link**: [PDF](https://arxiv.org/pdf/2501.00174)  

**Abstract**: Text Classification (TC) stands as a cornerstone within the realm of Natural Language Processing (NLP), particularly when viewed through the lens of computer science and engineering. The past decade has seen deep learning revolutionize TC, propelling advancements in text retrieval, categorization, information extraction, and summarization. The scholarly literature is rich with datasets, models, and evaluation criteria, with English being the predominant language of focus, despite studies involving Arabic, Chinese, Hindi, and others. The efficacy of TC models relies heavily on their ability to capture intricate textual relationships and nonlinear correlations, necessitating a comprehensive examination of the entire TC pipeline.
This monograph provides an in-depth exploration of the TC pipeline, with a particular emphasis on evaluating the impact of each component on the overall performance of TC models. The pipeline includes state-of-the-art datasets, text preprocessing techniques, text representation methods, classification models, evaluation metrics, current results and future trends. Each chapter meticulously examines these stages, presenting technical innovations and significant recent findings. The work critically assesses various classification strategies, offering comparative analyses, examples, case studies, and experimental evaluations. These contributions extend beyond a typical survey, providing a detailed and insightful exploration of TC. 

**Abstract (ZH)**: 文本分类（TC）是自然语言处理（NLP）领域的重要基石，特别是在计算科学和工程学的视角下。过去十年间，深度学习彻底改变了文本分类，推动了文本检索、分类、信息提取和摘要等领域的进步。学术文献中充满了各类数据集、模型和评估标准，尽管研究主要集中在英语上，但也涵盖了阿拉伯语、汉语、印地语等多种语言的研究。

TC模型的有效性很大程度上取决于其捕获复杂文本关系和非线性相关性的能力，这要求对整个TC管道进行全面的审视。

本专著深入探讨了文本分类管道的各个方面，特别强调了每个组成部分对整体性能的影响。管道涵盖了最先进的数据集、文本预处理技术、文本表示方法、分类模型、评估指标、当前成果和未来趋势。每一章都详细考察了这些阶段，介绍了技术革新和近期的重要发现。本书批判性地评估了各种分类策略，提供了对比分析、案例研究和实验评估。这些贡献超越了一般的综述性工作，为读者提供了对文本分类的详细和深入的探索。 

---
# Crime Hotspot Analysis and Mapping Using Geospatial Technology in Dessie City, Ethiopia 

**Title (ZH)**: 使用地理空间技术在埃塞俄比亚迪西市进行犯罪热点分析与mapping 

**Authors**: H.A.Kebede, M.M.Assen, M.A.Sharew  

**Link**: [PDF](https://arxiv.org/pdf/2501.00036)  

**Abstract**: Over the past few decades, crime and delinquency rates have increased drastically in many countries; nevertheless, it is important to note that crime trends can differ significantly by geographic region. This study's primary goal was to use geographic technology to map and analyze Dessie City's crime patterns. To investigate the geographic clustering of crime, the researchers used semivariogram modeling and spatial autocorrelation analysis with Moran'sI. The neighborhoods of Hote, Arada, and Segno in Dessie's central city were found to be crime-prone "hot spot" locations, as evidenced by statistically significant high Z-scores ranging from 0.037 to 4.608. On the other hand, low negative Z-scores ranging from -3.231 to -0.116 indicated "cold spot" concentrations of crime in the city's north-central sub-cities of Menafesha and Bounbouwha. With an index of 0.027492 and a Z-score of 3.297616 (p<0.01), the analysis overall showed a substantial positive spatial autocorrelation, suggesting a clustered pattern of crime in Dessie. The majority of crimes showed a north-south directionality, except for murder, which trended from northeast to southwest. The mean center of all crime types was found in the central Hote area. To address the complicated problem of rising crime rates in Dessie and other developing metropolitan areas, more focused and efficient enforcement techniques, and resource deployment can be informed through the knowledge acquired from the geospatial analysis. 

**Abstract (ZH)**: 在过去几十年中，许多国家的犯罪和青少年犯罪率急剧上升；然而，值得注意的是，犯罪趋势在不同的地理区域之间可能存在显著差异。本研究的主要目标是利用地理技术对德西市（Dessie City）的犯罪模式进行绘制和分析。为探讨犯罪的地理聚集现象，研究人员使用了半变异函数建模和基于莫兰指数（Moran's I）的空间自相关分析。研究发现，德西市中心的霍特（Hote）、阿达（Arada）和塞诺（Segno）等 neighborhoods 是犯罪“热点”区域，其统计显着的高Z分数（范围从0.037到4.608）为这些区域提供了证据。另一方面，北部和中部郊区的梅纳夫夏（Menafesha）和布恩布武夏（Bounbouwha）显示出低负Z分数（范围从-3.231到-0.116），表明这些区域内存在犯罪的“冷点”集中现象。总体而言，分析结果显示了0.027492的指数和3.297616的Z分数（p<0.01）的空间自相关性，表明德西市内的犯罪呈现出显著的空间聚集模式。大多数犯罪显示出由北向南的趋势，但谋杀案则呈现出从东北向西南的趋势。所有类型犯罪的重心位于市中心的霍特区域。为了应对德西及其他发展中的大城市的犯罪率上升这一复杂问题，可以通过空间地理分析获得的知识来指导更集中和高效的执法手段及资源配置。 

---
# A Breadth-First Catalog of Text Processing, Speech Processing and Multimodal Research in South Asian Languages 

**Title (ZH)**: 南亚语言文本处理、语音处理和多模态研究的广度优先目录 

**Authors**: Pranav Gupta  

**Link**: [PDF](https://arxiv.org/pdf/2501.00029)  

**Abstract**: We review the recent literature (January 2022- October 2024) in South Asian languages on text-based language processing, multimodal models, and speech processing, and provide a spotlight analysis focused on 21 low-resource South Asian languages, namely Saraiki, Assamese, Balochi, Bhojpuri, Bodo, Burmese, Chhattisgarhi, Dhivehi, Gujarati, Kannada, Kashmiri, Konkani, Khasi, Malayalam, Meitei, Nepali, Odia, Pashto, Rajasthani, Sindhi, and Telugu. We identify trends, challenges, and future research directions, using a step-wise approach that incorporates relevance classification and clustering based on large language models (LLMs). Our goal is to provide a breadth-first overview of the recent developments in South Asian language technologies to NLP researchers interested in working with South Asian languages. 

**Abstract (ZH)**: 我们回顾了2022年1月至2024年10月期间南亚语言中关于文本语言处理、多模态模型和语音处理的最新文献，并对包括21种低资源南亚语言（具体为：萨里基语、阿萨姆语、俾路支语、邦迪语、博多语、密支那语、恰蒂斯加尔语、 Divehi语、古吉拉特语、卡纳达语、克什米尔语、康枝尼语、卡西语、马拉雅拉姆语、密铁埃语、尼泊尔语、奥里亚语、普什图语、拉贾斯坦语、信德语和泰卢固语）的研究进行了重点分析。我们通过逐步方法识别趋势、挑战及未来研究方向，该方法结合了大规模语言模型（LLMs）的 relevance 分类和聚类。我们的目标是为对南亚语言感兴趣进行自然语言处理（NLP）研究的学者提供一个全面的近期南亚语言技术发展概述。 

---