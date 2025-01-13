# Knowledge Retrieval Based on Generative AI 

**Title (ZH)**: 基于生成式AI的知识检索 

**Authors**: Te-Lun Yang, Jyi-Shane Liu, Yuen-Hsien Tseng, Jyh-Shing Roger Jang  

**Link**: [PDF](https://arxiv.org/pdf/2501.04635)  

**Abstract**: This study develops a question-answering system based on Retrieval-Augmented Generation (RAG) using Chinese Wikipedia and Lawbank as retrieval sources. Using TTQA and TMMLU+ as evaluation datasets, the system employs BGE-M3 for dense vector retrieval to obtain highly relevant search results and BGE-reranker to reorder these results based on query relevance. The most pertinent retrieval outcomes serve as reference knowledge for a Large Language Model (LLM), enhancing its ability to answer questions and establishing a knowledge retrieval system grounded in generative AI.
The system's effectiveness is assessed through a two-stage evaluation: automatic and assisted performance evaluations. The automatic evaluation calculates accuracy by comparing the model's auto-generated labels with ground truth answers, measuring performance under standardized conditions without human intervention. The assisted performance evaluation involves 20 finance-related multiple-choice questions answered by 20 participants without financial backgrounds. Initially, participants answer independently. Later, they receive system-generated reference information to assist in answering, examining whether the system improves accuracy when assistance is provided.
The main contributions of this research are: (1) Enhanced LLM Capability: By integrating BGE-M3 and BGE-reranker, the system retrieves and reorders highly relevant results, reduces hallucinations, and dynamically accesses authorized or public knowledge sources. (2) Improved Data Privacy: A customized RAG architecture enables local operation of the LLM, eliminating the need to send private data to external servers. This approach enhances data security, reduces reliance on commercial services, lowers operational costs, and mitigates privacy risks. 

**Abstract (ZH)**: 本研究基于检索增强生成（RAG）技术，开发了一个以中文维基百科和Lawbank为检索源的问题解答系统。该系统使用TTQA和TMMLU+作为评估数据集，并采用BGE-M3进行密集向量检索，获取高相关的搜索结果，使用BGE-reranker根据查询相关性对这些结果进行重新排序。最相关检索结果作为大型语言模型（LLM）的参考知识，增强其回答问题的能力，并建立基于生成型AI的知识检索系统。

该系统的有效性通过两个阶段的评估进行测试：自动和辅助性能评估。自动评估通过比较模型自动生成的标签与真实答案之间的准确性，评估系统的性能，并在没有人为干预的情况下标准化条件。辅助性能评估涉及20个金融相关的多项选择问题，由20名无金融背景的参与者独立作答。随后，参与者接收系统生成的参考信息来辅助作答，检查在提供帮助的情况下系统的准确性是否有所提升。

本研究的主要贡献包括：（1）增强的LLM能力：通过整合BGE-M3和BGE-reranker，系统能够检索和重新排序高相关的结果，减少虚构信息的产生，并动态访问授权或公共知识源。（2）改进的数据隐私保护：定制化的RAG架构允许本地运行LLM，无需将私人数据发送到外部服务器。这种做法增强了数据安全性，减少了对商业服务的依赖，降低了运营成本，并减少了隐私风险。 

---
# Advancing Similarity Search with GenAI: A Retrieval Augmented Generation Approach 

**Title (ZH)**: 利用生成式人工智能推进相似性搜索：一种检索增强生成方法 

**Authors**: Jean Bertin  

**Link**: [PDF](https://arxiv.org/pdf/2501.04006)  

**Abstract**: This article introduces an innovative Retrieval Augmented Generation approach to similarity search. The proposed method uses a generative model to capture nuanced semantic information and retrieve similarity scores based on advanced context understanding. The study focuses on the BIOSSES dataset containing 100 pairs of sentences extracted from the biomedical domain, and introduces similarity search correlation results that outperform those previously attained on this dataset. Through an in-depth analysis of the model sensitivity, the research identifies optimal conditions leading to the highest similarity search accuracy: the results reveals high Pearson correlation scores, reaching specifically 0.905 at a temperature of 0.5 and a sample size of 20 examples provided in the prompt. The findings underscore the potential of generative models for semantic information retrieval and emphasize a promising research direction to similarity search. 

**Abstract (ZH)**: 本文介绍了用于相似性搜索的一种创新性检索增强生成（Retrieval Augmented Generation, RAG）方法。所提出的方案利用生成模型捕获微妙的语义信息，并基于先进的上下文理解来检索相似性得分。研究重点在于BIOSSES数据集，该数据集包含100个医学领域句子配对，展示了优于该数据集此前成果的相似性搜索相关性结果。通过深入分析模型的敏感性，研究确定了导致最高相似性搜索准确率的最优条件：结果揭示出高皮尔逊相关系数，特别是在温度为0.5、提示中提供20个示例的情况下，具体相关系数达到了0.905。研究结果突显了生成模型在语义信息检索方面的潜力，并强调了为相似性搜索探索有前景的研究方向的重要性。 

---
# Re-ranking the Context for Multimodal Retrieval Augmented Generation 

**Title (ZH)**: 多模态检索增强生成中重构上下文的重新排名 

**Authors**: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus  

**Link**: [PDF](https://arxiv.org/pdf/2501.04695)  

**Abstract**: Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external knowledge to generate a response within a context with improved accuracy and reduced hallucinations. However, multi-modal RAG systems face unique challenges: (i) the retrieval process may select irrelevant entries to user query (e.g., images, documents), and (ii) vision-language models or multi-modal language models like GPT-4o may hallucinate when processing these entries to generate RAG output. In this paper, we aim to address the first challenge, i.e, improving the selection of relevant context from the knowledge-base in retrieval phase of the multi-modal RAG. Specifically, we leverage the relevancy score (RS) measure designed in our previous work for evaluating the RAG performance to select more relevant entries in retrieval process. The retrieval based on embeddings, say CLIP-based embedding, and cosine similarity usually perform poorly particularly for multi-modal data. We show that by using a more advanced relevancy measure, one can enhance the retrieval process by selecting more relevant pieces from the knowledge-base and eliminate the irrelevant pieces from the context by adaptively selecting up-to-$k$ entries instead of fixed number of entries. Our evaluation using COCO dataset demonstrates significant enhancement in selecting relevant context and accuracy of the generated response. 

**Abstract (ZH)**: 检索增强生成（RAG）通过融入外部知识，增强了大型语言模型（LLMs）在上下文中生成响应的准确性和降低了虚构现象。然而，多模态RAG系统面临独特的挑战：（i）检索过程可能会选择与用户查询无关的条目（例如，图像、文档），以及（ii）当使用如GPT-4o等视觉语言模型或多模态语言模型处理这些条目生成RAG输出时，可能会产生虚构现象。本文旨在解决第一个挑战，即在多模态RAG的检索阶段，改进从知识库中选择相关上下文的方式。具体来说，我们利用我们在先前工作中设计的相关性分数（RS）衡量方法来评估RAG性能，从而在检索过程中选择更多相关内容。基于嵌入（如CLIP嵌入）和余弦相似性的检索通常在多模态数据上表现不佳。我们表明，通过使用更高级的相关性衡量方法，可以在检索过程中选择更多相关内容，并通过适配性地选择最多$k$个条目而不是固定数量的条目，来消除上下文中的无关条目。使用COCO数据集的评估结果表明，这种改进方法显著提高了选择相关上下文和生成响应准确性。 

---
# Multi-task retriever fine-tuning for domain-specific and efficient RAG 

**Title (ZH)**: 面向特定领域且高效的RAG的多任务检索器微调 

**Authors**: Patrice Béchard, Orlando Marquez Ayala  

**Link**: [PDF](https://arxiv.org/pdf/2501.04652)  

**Abstract**: Retrieval-Augmented Generation (RAG) has become ubiquitous when deploying Large Language Models (LLMs), as it can address typical limitations such as generating hallucinated or outdated information. However, when building real-world RAG applications, practical issues arise. First, the retrieved information is generally domain-specific. Since it is computationally expensive to fine-tune LLMs, it is more feasible to fine-tune the retriever to improve the quality of the data included in the LLM input. Second, as more applications are deployed in the same real-world system, one cannot afford to deploy separate retrievers. Moreover, these RAG applications normally retrieve different kinds of data. Our solution is to instruction fine-tune a small retriever encoder on a variety of domain-specific tasks to allow us to deploy one encoder that can serve many use cases, thereby achieving low-cost, scalability, and speed. We show how this encoder generalizes to out-of-domain settings as well as to an unseen retrieval task on real-world enterprise use cases. 

**Abstract (ZH)**: 检索增强生成（RAG）已经在部署大语言模型（LLMs）时变得无处不在，因为它可以解决诸如生成幻觉或过时信息等典型限制。然而，在构建实际的RAG应用时，实际问题也会出现。首先，检索到的信息通常具有领域特定性。由于对LLMs进行微调计算成本较高，更可行的方式是对检索器进行微调以提高LLMs输入中包含的数据质量。其次，随着越来越多的应用部署在同一实际系统中，无法为每个应用单独部署检索器。此外，这些RAG应用通常需要检索不同种类的数据。我们的解决方案是，在多种领域特定任务上对小型检索编码器进行指令微调，从而允许我们部署一个能服务于多种应用场景的编码器，从而实现低成本、可扩展性和快速响应。我们展示了该编码器在领域外环境以及在真实企业应用的未见检索任务中的泛化能力。 

---
# TimelineKGQA: A Comprehensive Question-Answer Pair Generator for Temporal Knowledge Graphs 

**Title (ZH)**: 时间线KGQA：时空知识图谱的综合问答对生成器 

**Authors**: Qiang Sun, Sirui Li, Du Huynh, Mark Reynolds, Wei Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.04343)  

**Abstract**: Question answering over temporal knowledge graphs (TKGs) is crucial for understanding evolving facts and relationships, yet its development is hindered by limited datasets and difficulties in generating custom QA pairs. We propose a novel categorization framework based on timeline-context relationships, along with \textbf{TimelineKGQA}, a universal temporal QA generator applicable to any TKGs. The code is available at: \url{this https URL} as an open source Python package. 

**Abstract (ZH)**: 时间知识图谱（TKGs）上的问答对于理解演变的事实和关系至关重要，但其发展受限于可用数据集有限以及生成自定义QA对的困难。我们提出了一种基于时间轴-上下文关系的新分类框架，并开发了适用于任何TKGs的通用时间问答生成器\textbf{TimelineKGQA}。此代码库可在以下链接处获取：\url{此网址链接}，并以开源Python包的形式提供。 

---