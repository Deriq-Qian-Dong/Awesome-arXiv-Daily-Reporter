# LLM Content Moderation and User Satisfaction: Evidence from Response Refusals in Chatbot Arena 

**Title (ZH)**: 大型语言模型内容审核与用户满意度：来自聊天机器人领域的证据 

**Authors**: Stefan Pasch  

**Link**: [PDF](https://arxiv.org/pdf/2501.03266)  

**Abstract**: LLM safety and ethical alignment are widely discussed, but the impact of content moderation on user satisfaction remains underexplored. To address this, we analyze nearly 50,000 Chatbot Arena response-pairs using a novel fine-tuned RoBERTa model, that we trained on hand-labeled data to disentangle refusals due to ethical concerns from other refusals due to technical disabilities or lack of information. Our findings reveal a significant refusal penalty on content moderation, with users choosing ethical-based refusals roughly one-fourth as often as their preferred LLM response compared to standard responses. However, the context and phrasing play critical roles: refusals on highly sensitive prompts, such as illegal content, achieve higher win rates than less sensitive ethical concerns, and longer responses closely aligned with the prompt perform better. These results emphasize the need for nuanced moderation strategies that balance ethical safeguards with user satisfaction. Moreover, we find that the refusal penalty is notably lower in evaluations using the LLM-as-a-Judge method, highlighting discrepancies between user and automated assessments. 

**Abstract (ZH)**: LLM的安全性和伦理对齐受到广泛讨论，但内容审核对用户满意度的影响尚未充分探讨。为了解决这一问题，我们使用一种新型微调RoBERTa模型分析了近50,000个Chatbot Arena的响应对，该模型是基于手工标注的数据训练而成，以区分由于伦理关切而拒绝的情况与其他由于技术问题或信息不足而拒绝的情况。我们的研究发现，内容审核显著降低了用户满意度，用户选择基于伦理关切的拒绝的比例大约仅为他们首选的LLM响应的一半。然而，上下文和措辞起着关键作用：对于高度敏感的提示（如非法内容），基于伦理关切的拒绝获得了更高的成功率；而对于较不敏感的伦理关切，则表现较差。此外，更长且与提示高度一致的回应表现更好。这些结果强调了需要一种平衡伦理保护与用户满意度的细腻管理策略。另外，我们发现，在使用LLM作为法官的评估方法中，拒绝惩罚明显较低，这揭示了用户评估与自动化评估之间的差异。 

---
# MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems 

**Title (ZH)**: MTRAG：一种多轮对话基准，用于评估检索增强生成系统 

**Authors**: Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-Suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.03468)  

**Abstract**: Retrieval-augmented generation (RAG) has recently become a very popular task for Large Language Models (LLMs). Evaluating them on multi-turn RAG conversations, where the system is asked to generate a response to a question in the context of a preceding conversation is an important and often overlooked task with several additional challenges. We present MTRAG: an end-to-end human-generated multi-turn RAG benchmark that reflects several real-world properties across diverse dimensions for evaluating the full RAG pipeline. MTRAG contains 110 conversations averaging 7.7 turns each across four domains for a total of 842 tasks. We also explore automation paths via synthetic data and LLM-as-a-Judge evaluation. Our human and automatic evaluations show that even state-of-the-art LLM RAG systems struggle on MTRAG. We demonstrate the need for strong retrieval and generation systems that can handle later turns, unanswerable questions, non-standalone questions, and multiple domains. MTRAG is available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）近年来已成为大型语言模型（LLMs）的一个非常流行的任务。在多轮RAG对话中评估它们——系统需要根据前一对话的背景生成对问题的回复——是一项重要但常被忽视的任务，还面临多个额外挑战。我们提出了MTRAG：一个端到端的人工生成多轮RAG基准，该基准在多个维度上反映了多种真实世界特性，用于全面评估RAG管道。MTRAG包含四个领域共110场对话，平均每场对话7.7轮，总共涵盖了842项任务。我们还探讨了通过合成数据和LLM作为裁判的评估方法来自动化的途径。我们的手动和自动评估表明，即使是当前最先进的LLM RAG系统在MTRAG上也存在困难。我们演示了需要强大的检索和生成系统来处理后续轮次、无法回答的问题、非独立的问题以及多个领域的需求。MTRAG可在以下链接获取：这个 https URL。 

---