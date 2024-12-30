# Agents on the Bench: Large Language Model Based Multi Agent Framework for Trustworthy Digital Justice 

**Title (ZH)**: 《审判席上的代理人：基于大型语言模型的多代理系统框架，以实现可信赖的数字正义》

此标题翻译遵循了学术规范，保持了原文的核心意思，并用中文学术界常用的表达方式进行了适当调整。 

**Authors**: Cong Jiang, Xiaolei Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.18697)  

**Abstract**: The justice system has increasingly employed AI techniques to enhance efficiency, yet limitations remain in improving the quality of decision-making, particularly regarding transparency and explainability needed to uphold public trust in legal AI. To address these challenges, we propose a large language model based multi-agent framework named AgentsBench, which aims to simultaneously improve both efficiency and quality in judicial decision-making. Our approach leverages multiple LLM-driven agents that simulate the collaborative deliberation and decision making process of a judicial bench. We conducted experiments on legal judgment prediction task, and the results show that our framework outperforms existing LLM based methods in terms of performance and decision quality. By incorporating these elements, our framework reflects real-world judicial processes more closely, enhancing accuracy, fairness, and society consideration. AgentsBench provides a more nuanced and realistic methods of trustworthy AI decision-making, with strong potential for application across various case types and legal scenarios. 

**Abstract (ZH)**: 司法系统正越来越多地采用人工智能技术以提高效率，然而在提高决策质量方面仍存在局限，尤其是在透明性和可解释性方面，这是维护公众对法律人工智能的信任所需的重要方面。为应对这些挑战，我们提出了一种基于大型语言模型的多代理框架，名为AgentsBench，旨在同时提高司法决策的效率和质量。我们的方法利用多个由大型语言模型驱动的代理，模拟司法庭的协作讨论和决策过程。我们进行了法律判决预测任务的实验，结果表明，与现有的基于大型语言模型的方法相比，我们的框架在性能和决策质量上表现更优。通过这些元素，我们的框架更接近于真实的司法流程，提高了准确性、公平性和社会考量。AgentsBench 提供了一种更为细致和现实的可信赖人工智能决策方法，适用于各种案件类型和法律情境，具有较大的应用潜力。 

---
# CypherBench: Towards Precise Retrieval over Full-scale Modern Knowledge Graphs in the LLM Era 

**Title (ZH)**: CypherBench：面向大规模现代知识图谱在大语言模型时代精确检索的研究 

**Authors**: Yanlin Feng, Simone Papicchio, Sajjadur Rahman  

**Link**: [PDF](https://arxiv.org/pdf/2412.18702)  

**Abstract**: Retrieval from graph data is crucial for augmenting large language models (LLM) with both open-domain knowledge and private enterprise data, and it is also a key component in the recent GraphRAG system (edge et al., 2024). Despite decades of research on knowledge graphs and knowledge base question answering, leading LLM frameworks (e.g. Langchain and LlamaIndex) have only minimal support for retrieval from modern encyclopedic knowledge graphs like Wikidata. In this paper, we analyze the root cause and suggest that modern RDF knowledge graphs (e.g. Wikidata, Freebase) are less efficient for LLMs due to overly large schemas that far exceed the typical LLM context window, use of resource identifiers, overlapping relation types and lack of normalization. As a solution, we propose property graph views on top of the underlying RDF graph that can be efficiently queried by LLMs using Cypher. We instantiated this idea on Wikidata and introduced CypherBench, the first benchmark with 11 large-scale, multi-domain property graphs with 7.8 million entities and over 10,000 questions. To achieve this, we tackled several key challenges, including developing an RDF-to-property graph conversion engine, creating a systematic pipeline for text-to-Cypher task generation, and designing new evaluation metrics. 

**Abstract (ZH)**: 从图形数据中检索对于增强大型语言模型（LLM）的通用领域知识和企业私有数据至关重要，并且也是最近的GraphRAG系统（edge等，2024）中的关键组成部分。尽管在知识图谱和知识库问答方面进行了几十年的研究，主流的LLM框架（例如Langchain和LlamaIndex）对现代百科全书式知识图谱（如Wikidata）的检索支持仍然相对有限。在本论文中，我们分析了根本原因，并建议现代RDF知识图谱（如Wikidata、Freebase）因为其过大且远超标准LLM上下文窗口的模式定义、使用资源标识符、关系类型重叠以及缺乏规范化而导致效率低下。为此，我们提出了一种基于底层RDF图的属性图视图，使其可以使用Cypher高效地被LLM查询。我们在Wikidata上实现了这一想法，并引入了CypherBench，这是第一个包含11个大规模、多领域属性图的基准，拥有超过780万个实体和10000多个问题。为实现这一点，我们攻克了多个关键挑战，包括开发RDF到属性图的转换引擎、创建系统性的从文本到Cypher任务生成管道以及设计新的评估指标。 

---