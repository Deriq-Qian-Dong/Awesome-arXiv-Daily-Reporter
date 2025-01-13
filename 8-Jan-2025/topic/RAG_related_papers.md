# MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems 

**Title (ZH)**: MTRAG：一种多轮对话基准，用于评估检索增强生成系统 

**Authors**: Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-Suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.03468)  

**Abstract**: Retrieval-augmented generation (RAG) has recently become a very popular task for Large Language Models (LLMs). Evaluating them on multi-turn RAG conversations, where the system is asked to generate a response to a question in the context of a preceding conversation is an important and often overlooked task with several additional challenges. We present MTRAG: an end-to-end human-generated multi-turn RAG benchmark that reflects several real-world properties across diverse dimensions for evaluating the full RAG pipeline. MTRAG contains 110 conversations averaging 7.7 turns each across four domains for a total of 842 tasks. We also explore automation paths via synthetic data and LLM-as-a-Judge evaluation. Our human and automatic evaluations show that even state-of-the-art LLM RAG systems struggle on MTRAG. We demonstrate the need for strong retrieval and generation systems that can handle later turns, unanswerable questions, non-standalone questions, and multiple domains. MTRAG is available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）近年来已成为大型语言模型（LLMs）的一个非常流行的任务。在多轮RAG对话中评估它们——系统需要根据前一对话的背景生成对问题的回复——是一项重要但常被忽视的任务，还面临多个额外挑战。我们提出了MTRAG：一个端到端的人工生成多轮RAG基准，该基准在多个维度上反映了多种真实世界特性，用于全面评估RAG管道。MTRAG包含四个领域共110场对话，平均每场对话7.7轮，总共涵盖了842项任务。我们还探讨了通过合成数据和LLM作为裁判的评估方法来自动化的途径。我们的手动和自动评估表明，即使是当前最先进的LLM RAG系统在MTRAG上也存在困难。我们演示了需要强大的检索和生成系统来处理后续轮次、无法回答的问题、非独立的问题以及多个领域的需求。MTRAG可在以下链接获取：这个 https URL。 

---
# RAG-Check: Evaluating Multimodal Retrieval Augmented Generation Performance 

**Title (ZH)**: RAG-Check：评估多模态检索增强生成性能 

**Authors**: Matin Mortaheb, Mohammad A. Amir Khojastepour, Srimat T. Chakradhar, Sennur Ulukus  

**Link**: [PDF](https://arxiv.org/pdf/2501.03995)  

**Abstract**: Retrieval-augmented generation (RAG) improves large language models (LLMs) by using external knowledge to guide response generation, reducing hallucinations. However, RAG, particularly multi-modal RAG, can introduce new hallucination sources: (i) the retrieval process may select irrelevant pieces (e.g., documents, images) as raw context from the database, and (ii) retrieved images are processed into text-based context via vision-language models (VLMs) or directly used by multi-modal language models (MLLMs) like GPT-4o, which may hallucinate. To address this, we propose a novel framework to evaluate the reliability of multi-modal RAG using two performance measures: (i) the relevancy score (RS), assessing the relevance of retrieved entries to the query, and (ii) the correctness score (CS), evaluating the accuracy of the generated response. We train RS and CS models using a ChatGPT-derived database and human evaluator samples. Results show that both models achieve ~88% accuracy on test data. Additionally, we construct a 5000-sample human-annotated database evaluating the relevancy of retrieved pieces and the correctness of response statements. Our RS model aligns with human preferences 20% more often than CLIP in retrieval, and our CS model matches human preferences ~91% of the time. Finally, we assess various RAG systems' selection and generation performances using RS and CS. 

**Abstract (ZH)**: 检索增强生成（Retrieval-Augmented Generation，RAG）通过利用外部知识引导响应生成，从而改进了大规模语言模型（Large Language Models，LLMs），减少幻觉现象。然而，RAG，尤其是多模态RAG，可能会引入新的幻觉来源：（i）检索过程可能会从数据库中选择与查询无关的片段（如文档、图像）作为原始上下文；（ii）检索到的图像通过视觉语言模型（Vision-Language Models，VLMs）转换为基于文本的上下文，或者直接被多模态语言模型（Multimodal Language Models，MLLMs）如GPT-4o使用，可能导致幻觉。为应对这一问题，我们提出了一种新的框架来评估多模态RAG的可靠性，使用两种性能指标：（i）相关性评分（Relevance Score，RS），评估检索条目与查询的相关性；（ii）正确性评分（Correctness Score，CS），评估生成响应的准确性。我们使用从ChatGPT派生的数据库和人工评估样本训练RS和CS模型。结果显示，这两种模型在测试数据上的准确率均达到约88%。此外，我们构建了一个包含5000个样本的人工标注数据库，用于评估检索片段的相关性及响应陈述的准确性。我们的RS模型在检索中比CLIP更符合人类偏好20%，而我们的CS模型约91%的情况下与人类偏好一致。最后，我们使用RS和CS评估了各种RAG系统的选择和生成性能。 

---
# SenseRAG: Constructing Environmental Knowledge Bases with Proactive Querying for LLM-Based Autonomous Driving 

**Title (ZH)**: SenseRAG：通过主动查询构建环境知识库以支持基于大语言模型的自动驾驶 

**Authors**: Xuewen Luo, Fan Ding, Fengze Yang, Yang Zhou, Junnyong Loo, Hwa Hui Tew, Chenxi Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.03535)  

**Abstract**: This study addresses the critical need for enhanced situational awareness in autonomous driving (AD) by leveraging the contextual reasoning capabilities of large language models (LLMs). Unlike traditional perception systems that rely on rigid, label-based annotations, it integrates real-time, multimodal sensor data into a unified, LLMs-readable knowledge base, enabling LLMs to dynamically understand and respond to complex driving environments. To overcome the inherent latency and modality limitations of LLMs, a proactive Retrieval-Augmented Generation (RAG) is designed for AD, combined with a chain-of-thought prompting mechanism, ensuring rapid and context-rich understanding. Experimental results using real-world Vehicle-to-everything (V2X) datasets demonstrate significant improvements in perception and prediction performance, highlighting the potential of this framework to enhance safety, adaptability, and decision-making in next-generation AD systems. 

**Abstract (ZH)**: 本文通过利用大规模语言模型（LLMs）的上下文推理能力，解决了自动驾驶（AD）中增强态势感知的关键需求。不同于依赖于刚性标签注释的传统感知系统，本文将实时的多模态传感器数据整合进一个统一的、LLMs可读的知识库中，使LLMs能够动态地理解和应对复杂的驾驶环境。为了克服LLMs固有的延迟和模态限制，本文为AD设计了一种前瞻性的检索增强生成（RAG）方法，并结合了一种链式思考提示机制，确保快速且富有上下文的理解。使用实际的车辆到一切（V2X）数据集的实验结果表明，在感知和预测性能方面取得了显著的改进，突显了该框架在提升下一代AD系统的安全性、适应性和决策能力方面的潜力。 

---
# A Soft Sensor Method with Uncertainty-Awareness and Self-Explanation Based on Large Language Models Enhanced by Domain Knowledge Retrieval 

**Title (ZH)**: 基于领域知识检索增强的大语言模型的不确定性意识与自我解释软传感器方法 

**Authors**: Shuo Tong, Runyuan Guo, Wenqing Wang, Xueqiong Tian, Lingyun Wei, Lin Zhang, Huayong Wu, Ding Liu, Youmin Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2501.03295)  

**Abstract**: Data-driven soft sensors are crucial in predicting key performance indicators in industrial systems. However, current methods predominantly rely on the supervised learning paradigms of parameter updating, which inherently faces challenges such as high development costs, poor robustness, training instability, and lack of interpretability. Recently, large language models (LLMs) have demonstrated significant potential across various domains, notably through In-Context Learning (ICL), which enables high-performance task execution with minimal input-label demonstrations and no prior training. This paper aims to replace supervised learning with the emerging ICL paradigm for soft sensor modeling to address existing challenges and explore new avenues for advancement. To achieve this, we propose a novel framework called the Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS), which includes the Zero-shot Auxiliary Variable Selector (LLM-ZAVS) and the Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS). The LLM-ZAVS retrieves from the Industrial Knowledge Vector Storage to enhance LLMs' domain-specific knowledge, enabling zero-shot auxiliary variable selection. In the LLM-UFSS, we utilize text-based context demonstrations of structured data to prompt LLMs to execute ICL for predicting and propose a context sample retrieval augmentation strategy to improve performance. Additionally, we explored LLMs' AIGC and probabilistic characteristics to propose self-explanation and uncertainty quantification methods for constructing a trustworthy soft sensor. Extensive experiments demonstrate that our method achieved state-of-the-art predictive performance, strong robustness, and flexibility, effectively mitigates training instability found in traditional methods. To the best of our knowledge, this is the first work to establish soft sensor utilizing LLMs. 

**Abstract (ZH)**: 数据驱动的软传感器在预测工业系统中的关键性能指标方面至关重要。然而，当前的方法主要依赖监督学习中的参数更新框架，这本身就面临着高开发成本、鲁棒性差、训练不稳定性和缺乏可解释性等挑战。近年来，大型语言模型（LLMs）在各个领域展现出了巨大的潜力，特别是通过上下文学习（In-Context Learning, ICL），能够在最少的输入-标签示范和无需先验训练的情况下实现高性能的任务执行。本文旨在利用新兴的ICL范式替换监督学习，以解决现有的挑战并探索新的发展路径。为此，我们提出了一种名为Few-shot Uncertainty-aware and self-Explaining Soft Sensor (LLM-FUESS)的新框架，该框架包括Zero-shot Auxiliary Variable Selector (LLM-ZAVS)和Uncertainty-aware Few-shot Soft Sensor (LLM-UFSS)。LLM-ZAVS从工业知识向量存储中检索信息，以增强LLMs的领域特定知识，实现零样本辅助变量选择。在LLM-UFSS中，我们利用结构化数据的文本上下文示范来驱动LLMs执行ICL以进行预测，并提出了一种上下文样本检索增强策略以提高性能。此外，我们探索了LLMs的特性，包括生成式人工智能（AIGC）和概率特性，并提出了自我解释和不确定性量化方法，以构建可信的软传感器。广泛实验结果表明，我们的方法达到了最先进的预测性能、强大的鲁棒性和灵活性，有效缓解了传统方法中发现的训练稳定性问题。据我们所知，这是首次利用LLMs构建软传感器的工作。 

---