# From Interets to Insights: An LLM Approach to Course Recommendations Using Natural Language Queries 

**Title (ZH)**: 从兴趣到洞见：基于自然语言查询的LLM课程推荐方法 

**Authors**: Hugh Van Deventer, Mark Mills, August Evrard  

**Link**: [PDF](https://arxiv.org/pdf/2412.19312)  

**Abstract**: Most universities in the United States encourage their students to explore academic areas before declaring a major and to acquire academic breadth by satisfying a variety of requirements. Each term, students must choose among many thousands of offerings, spanning dozens of subject areas, a handful of courses to take. The curricular environment is also dynamic, and poor communication and search functions on campus can limit a student's ability to discover new courses of interest. To support both students and their advisers in such a setting, we explore a novel Large Language Model (LLM) course recommendation system that applies a Retrieval Augmented Generation (RAG) method to the corpus of course descriptions. The system first generates an 'ideal' course description based on the user's query. This description is converted into a search vector using embeddings, which is then used to find actual courses with similar content by comparing embedding similarities. We describe the method and assess the quality and fairness of some example prompts. Steps to deploy a pilot system on campus are discussed. 

**Abstract (ZH)**: 美国大多数大学鼓励学生在正式选定专业之前探索学术领域，并通过满足各种要求来获得学科广度。每一学期，学生都需要从数千门课程中选择若干门课程，这些课程涵盖几十个学科领域。课程结构环境是动态变化的，而校园内的不良沟通和搜索功能可能限制学生发现新课程的能力。为了在这样一个环境中支持学生及其导师，我们探讨了一种新颖的大型语言模型（LLM）课程推荐系统，该系统采用检索增强生成（RAG）方法对课程描述语料库进行处理。该系统首先根据用户的查询生成一个“理想”的课程描述。然后，将该描述转换为嵌入向量，通过比较嵌入相似度来查找具有类似内容的实际课程。我们描述了这种方法，并评估了一些示例提示的质量和公平性。还讨论了在校园中部署试点系统的步骤。 

---
# RAG with Differential Privacy 

**Title (ZH)**: 差分隐私下的RAG方法 

**Authors**: Nicolas Grislain  

**Link**: [PDF](https://arxiv.org/pdf/2412.19291)  

**Abstract**: Retrieval-Augmented Generation (RAG) has emerged as the dominant technique to provide *Large Language Models* (LLM) with fresh and relevant context, mitigating the risk of hallucinations and improving the overall quality of responses in environments with large and fast moving knowledge bases. However, the integration of external documents into the generation process raises significant privacy concerns. Indeed, when added to a prompt, it is not possible to guarantee a response will not inadvertently expose confidential data, leading to potential breaches of privacy and ethical dilemmas. This paper explores a practical solution to this problem suitable to general knowledge extraction from personal data. It shows *differentially private token generation* is a viable approach to private RAG. 

**Abstract (ZH)**: 检索增强生成（RAG）已成为提供大型语言模型（LLM）最新和相关上下文的主要技术，减轻了在大规模和快速变化的知识库环境中出现幻觉的风险，并提高了响应的整体质量。然而，将外部文档集成到生成过程中引发了重大的隐私问题。实际上，当将其添加到提示中时，无法保证不会无意间暴露敏感数据，从而可能导致隐私泄露和伦理困境。本文探讨了一种适用于个人数据通用知识提取的实用解决方案。它表明差异隐私的标记生成是一种可行的方法，用于保护隐私的RAG。 

---
# DynaGRAG: Improving Language Understanding and Generation through Dynamic Subgraph Representation in Graph Retrieval-Augmented Generation 

**Title (ZH)**: DynaGRAG：通过图检索增强生成中的动态子图表示提高语言理解和生成 

**Authors**: Karishma Thakrar  

**Link**: [PDF](https://arxiv.org/pdf/2412.18644)  

**Abstract**: Graph Retrieval-Augmented Generation (GRAG or Graph RAG) architectures aim to enhance language understanding and generation by leveraging external knowledge. However, effectively capturing and integrating the rich semantic information present in textual and structured data remains a challenge. To address this, a novel GRAG framework is proposed to focus on enhancing subgraph representation and diversity within the knowledge graph. By improving graph density, capturing entity and relation information more effectively, and dynamically prioritizing relevant and diverse subgraphs, the proposed approach enables a more comprehensive understanding of the underlying semantic structure. This is achieved through a combination of de-duplication processes, two-step mean pooling of embeddings, query-aware retrieval considering unique nodes, and a Dynamic Similarity-Aware BFS (DSA-BFS) traversal algorithm. Integrating Graph Convolutional Networks (GCNs) and Large Language Models (LLMs) through hard prompting further enhances the learning of rich node and edge representations while preserving the hierarchical subgraph structure. Experimental results on multiple benchmark datasets demonstrate the effectiveness of the proposed GRAG framework, showcasing the significance of enhanced subgraph representation and diversity for improved language understanding and generation. 

**Abstract (ZH)**: Graph检索增强生成（GRAG或Graph RAG）架构旨在通过利用外部知识来增强语言理解与生成。然而，有效地捕捉和整合文本和结构化数据中的丰富语义信息仍然是一个挑战。为了解决这一问题，提出了一个新颖的GRAG框架，以增强知识图中的子图表示和多样性。通过提高图的密度、更有效地捕捉实体和关系信息，并动态优先考虑相关和多样化的子图，所提出的方法能够更全面地理解潜在的语义结构。这通过去重过程的组合、两步嵌入聚类平均、考虑唯一节点的查询感知检索以及动态相似性感知BFS（DSA-BFS）遍历算法实现。通过将图卷积网络（GCNs）和大型语言模型（LLMs）结合使用硬提示，进一步增强了丰富的节点和边表示的学习能力，同时保留了层次化的子图结构。在多个基准数据集上的实验结果表明，提出的GRAG框架的有效性，展示了增强子图表示和多样性的显著意义，以提高语言理解和生成。 

---
# KRAIL: A Knowledge-Driven Framework for Base Human Reliability Analysis Integrating IDHEAS and Large Language Models 

**Title (ZH)**: KRAIL：一种基于知识的框架，结合IDHEAS和大规模语言模型进行基础人类可靠性分析 

**Authors**: Xingyu Xiao, Peng Chen, Ben Qi, Hongru Zhao, Jingang Liang, Jiejuan Tong, Haitao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.18627)  

**Abstract**: Human reliability analysis (HRA) is crucial for evaluating and improving the safety of complex systems. Recent efforts have focused on estimating human error probability (HEP), but existing methods often rely heavily on expert knowledge,which can be subjective and time-consuming. Inspired by the success of large language models (LLMs) in natural language processing, this paper introduces a novel two-stage framework for knowledge-driven reliability analysis, integrating IDHEAS and LLMs (KRAIL). This innovative framework enables the semi-automated computation of base HEP values. Additionally, knowledge graphs are utilized as a form of retrieval-augmented generation (RAG) for enhancing the framework' s capability to retrieve and process relevant data efficiently. Experiments are systematically conducted and evaluated on authoritative datasets of human reliability. The experimental results of the proposed methodology demonstrate its superior performance on base HEP estimation under partial information for reliability assessment. 

**Abstract (ZH)**: 人类可靠性分析（HRA）对于评估和改善复杂系统的安全性至关重要。近期的研究主要集中在估计人类错误概率（HEP），但现有方法往往依赖于专家知识，这可能会导致主观性和耗时性。受到大型语言模型（LLMs）在自然语言处理领域取得成功的影响，本文提出了一种新的基于知识驱动的可靠性分析框架——KRAIL（Knowledge-driven Reliability Analysis using Integrated IDHEAS and Large Language Models），并采用两阶段流程实现这一框架。这个创新性框架能够半自动化地计算基础HEP值。此外，本文还利用知识图谱作为一种检索增强生成（RAG）方法，以提高框架在高效检索和处理相关数据方面的能力。我们系统地在权威的人类可靠性数据集上进行了实验并进行了评估。所提出方法的实验结果表明，在可靠性评估中基于部分信息对基础HEP进行估计时，该方法表现出卓越的性能。 

---