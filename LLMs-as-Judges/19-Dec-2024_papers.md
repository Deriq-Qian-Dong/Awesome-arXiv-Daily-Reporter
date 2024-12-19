# GLIDER: Grading LLM Interactions and Decisions using Explainable Ranking 

**Title (ZH)**: GLIDER：使用可解释排名评估大规模语言模型交互和决策 

**Authors**: Darshan Deshpande, Selvan Sunitha Ravi, Sky CH-Wang, Bartosz Mielczarek, Anand Kannappan, Rebecca Qian  

**Link**: [PDF](https://arxiv.org/pdf/2412.14140)  

**Abstract**: The LLM-as-judge paradigm is increasingly being adopted for automated evaluation of model outputs. While LLM judges have shown promise on constrained evaluation tasks, closed source LLMs display critical shortcomings when deployed in real world applications due to challenges of fine grained metrics and explainability, while task specific evaluation models lack cross-domain generalization. We introduce GLIDER, a powerful 3B evaluator LLM that can score any text input and associated context on arbitrary user defined criteria. GLIDER shows higher Pearson's correlation than GPT-4o on FLASK and greatly outperforms prior evaluation models, achieving comparable performance to LLMs 17x its size. GLIDER supports fine-grained scoring, multilingual reasoning, span highlighting and was trained on 685 domains and 183 criteria. Extensive qualitative analysis shows that GLIDER scores are highly correlated with human judgments, with 91.3% human agreement. We have open-sourced GLIDER to facilitate future research. 

**Abstract (ZH)**: 以下是从英文翻译成中文的版本，确保符合学术规范：

大规模语言模型（LLM）作为评委的范式越来越被用于模型输出的自动化评估。尽管LLM评委在受限评估任务上显示出了一定的潜力，但由于细粒度评估指标和可解释性方面的挑战，闭源LLM在实际应用中暴露出了关键的不足，而针对特定任务的评估模型则缺乏跨领域的泛化能力。我们提出了GLIDER，这是一种强大的30亿参数的评价LLM，能够对任意文本输入及其相关背景进行任意用户定义标准的打分。GLIDER在FLASK上的皮尔逊相关系数优于GPT-4o，并且在评估性能上显著优于之前的所有评估模型，其性能相当于大小是自身17倍的LLM。GLIDER支持细粒度打分、多语言推理和片段高亮，并且在其训练中涵盖了685个领域和183项标准。详尽的定性分析显示，GLIDER的打分与人类判断高度相关，91.3%的人类一致性。我们已开源GLIDER，以便促进未来的研究。 

---
# JudgeBlender: Ensembling Judgments for Automatic Relevance Assessment 

**Title (ZH)**: JudgeBlender: 组合判决以实现自动相关性评估 

**Authors**: Hossein A. Rahmani, Emine Yilmaz, Nick Craswell, Bhaskar Mitra  

**Link**: [PDF](https://arxiv.org/pdf/2412.13268)  

**Abstract**: The effective training and evaluation of retrieval systems require a substantial amount of relevance judgments, which are traditionally collected from human assessors -- a process that is both costly and time-consuming. Large Language Models (LLMs) have shown promise in generating relevance labels for search tasks, offering a potential alternative to manual assessments. Current approaches often rely on a single LLM, such as GPT-4, which, despite being effective, are expensive and prone to intra-model biases that can favour systems leveraging similar models. In this work, we introduce JudgeBlender, a framework that employs smaller, open-source models to provide relevance judgments by combining evaluations across multiple LLMs (LLMBlender) or multiple prompts (PromptBlender). By leveraging the LLMJudge benchmark [18], we compare JudgeBlender with state-of-the-art methods and the top performers in the LLMJudge challenge. Our results show that JudgeBlender achieves competitive performance, demonstrating that very large models are often unnecessary for reliable relevance assessments. 

**Abstract (ZH)**: 有效的检索系统训练和评估需要大量的相关性判断，这些判断传统上是由人工评估者收集的——这是一个既昂贵又耗时的过程。大型语言模型（LLMs）在为搜索任务生成相关性标签方面显示出潜力，从而为替代人工评估提供了可能。当前的方法通常依赖单一的LLM，如GPT-4，尽管其有效，但成本较高且容易受到模型内部偏差的影响，这些偏差可能导致利用类似模型的系统获得优势。在本文中，我们引入了JudgeBlender框架，该框架通过结合多个LLM（LLMBlender）或多个提示（PromptBlender）的评估来使用较小的开源模型提供相关性判断。通过利用LLMJudge基准数据集[18]，我们将JudgeBlender与最先进的方法和LLMJudge挑战中的顶尖表现者进行了比较。我们的结果表明，JudgeBlender取得了竞争力的表现，这表明可靠的相关性评估通常并不需要非常大的模型。 

---