# A RAG-Based Institutional Assistant 

**Title (ZH)**: 基于RAG的机构助手 

**Authors**: Gustavo Kuratomi, Paulo Pirozelli, Fabio G. Cozman, Sarajane M. Peres  

**Link**: [PDF](https://arxiv.org/pdf/2501.13880)  

**Abstract**: Although large language models (LLMs) demonstrate strong text generation capabilities, they struggle in scenarios requiring access to structured knowledge bases or specific documents, limiting their effectiveness in knowledge-intensive tasks. To address this limitation, retrieval-augmented generation (RAG) models have been developed, enabling generative models to incorporate relevant document fragments into their inputs. In this paper, we design and evaluate a RAG-based virtual assistant specifically tailored for the University of São Paulo. Our system architecture comprises two key modules: a retriever and a generative model. We experiment with different types of models for both components, adjusting hyperparameters such as chunk size and the number of retrieved documents. Our optimal retriever model achieves a Top-5 accuracy of 30%, while our most effective generative model scores 22.04\% against ground truth answers. Notably, when the correct document chunks are supplied to the LLMs, accuracy significantly improves to 54.02%, an increase of over 30 percentage points. Conversely, without contextual input, performance declines to 13.68%. These findings highlight the critical role of database access in enhancing LLM performance. They also reveal the limitations of current semantic search methods in accurately identifying relevant documents and underscore the ongoing challenges LLMs face in generating precise responses. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）表现出强大的文本生成能力，但在需要访问结构化知识库或特定文档的场景中，它们的表现却大打折扣，从而限制了它们在知识密集型任务中的效果。为了解决这一局限，已经开发出了检索增强生成（RAG）模型，使生成模型能够将相关的文档片段纳入输入中。在本文中，我们为圣保罗大学设计并评估了一个专门的RAG虚拟助手系统。该系统架构包括两个关键模块：检索器和生成模型。对这两个组件中的不同类型的模型进行了实验，调整了诸如片段大小和检索文档数量等超参数。我们的最佳检索模型在前五名准确率达到30%，而我们最有效的生成模型的得分则为22.04%。值得注意的是，当正确的文档片段提供给LLMs时，准确率显著提高到54.02%，提高了超过30个百分点。相反，如果没有上下文输入，性能则下降到13.68%。这些发现凸显了数据库访问对于提升LLM性能的至关重要性。它们还揭示了当前语义搜索方法在准确识别相关文档方面的局限，并强调了LLMs在生成精确响应方面所面临的持续挑战。 

---
# RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation 

**Title (ZH)**: RPO：鲁棒检索增强生成中的检索偏好优化 

**Authors**: Shi-Qi Yan, Zhen-Hua Ling  

**Link**: [PDF](https://arxiv.org/pdf/2501.13726)  

**Abstract**: While Retrieval-Augmented Generation (RAG) has exhibited promise in utilizing external knowledge, its generation process heavily depends on the quality and accuracy of the retrieved context. Large language models (LLMs) struggle to evaluate the correctness of non-parametric knowledge retrieved externally when it differs from internal memorization, leading to knowledge conflicts during response generation. To this end, we introduce the Retrieval Preference Optimization (RPO), a lightweight and effective alignment method to adaptively leverage multi-source knowledge based on retrieval relevance. An implicit representation of retrieval relevance is derived and incorporated into the reward model to integrate retrieval evaluation and response generation into a single model, solving the problem that previous methods necessitate the additional procedure to assess the retrieval quality. Notably, RPO is the only RAG-dedicated alignment approach that quantifies the awareness of retrieval relevance in training, overcoming mathematical obstacles. Experiments on four datasets demonstrate that RPO outperforms RAG by 4-10% in accuracy without any extra component, exhibiting its robust generalization. 

**Abstract (ZH)**: 尽管检索增强生成（RAG）展示了利用外部知识的潜力，其生成过程高度依赖于检索上下文的质量和准确性。大型语言模型（LLMs）在评估与内部记忆不同的外部非参数化知识的正确性时存在困难，这导致在响应生成过程中出现知识冲突。为此，我们提出了检索偏好优化（RPO），这是一种轻量级且有效的对齐方法，可以根据检索相关性适当地利用多源知识。通过推导检索相关性的隐式表示并将其融入奖励模型中，将检索评估与响应生成整合到单一模型中，解决了先前方法需要额外步骤评估检索质量的问题。值得注意的是，RPO 是唯一一种在训练中量化检索相关性意识的 RAG 专用对齐方法，克服了数学障碍。在四个数据集上的实验表明，RPO 在无需任何额外组件的情况下比 RAG 在准确性上提高了 4%-10%，展示了其稳健的泛化能力。 

---
# Improving Contextual Faithfulness of Large Language Models via Retrieval Heads-Induced Optimization 

**Title (ZH)**: 通过检索头部引导优化提高大型语言模型的语境忠实度 

**Authors**: Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yangfan Ye, Weihong Zhong, Yuxuan Gu, Baoxin Wang, Dayong Wu, Guoping Hu, Bing Qin  

**Link**: [PDF](https://arxiv.org/pdf/2501.13573)  

**Abstract**: Ensuring contextual faithfulness in retrieval-augmented large language models (LLMs) is crucial for building trustworthy information-seeking systems, particularly in long-form question-answering (LFQA) scenarios. In this work, we identify a salient correlation between LFQA faithfulness and retrieval heads, a set of attention heads responsible for retrieving contextual information. Leveraging this insight, we propose RHIO, a framework designed to teach LLMs to explicitly discriminate between faithful and unfaithful generations. RHIO first augments unfaithful samples that simulate realistic model-intrinsic errors by selectively masking retrieval heads. Then, these samples are incorporated into joint training, enabling the model to distinguish unfaithful outputs from faithful ones conditioned on control tokens. Furthermore, these control tokens are leveraged to self-induce contrastive outputs, amplifying their difference through contrastive decoding. Additionally, to facilitate the evaluation of contextual faithfulness, we also introduce GroundBench, a comprehensive benchmark compiled from five existing LFQA datasets. Extensive experimental results on GroundBench demonstrate that RHIO significantly improves faithfulness, even outperforming GPT-4o. 

**Abstract (ZH)**: 在检索增强的大语言模型（LLMs）中确保上下文一致性忠实性对于构建可信赖的信息检索系统至关重要，特别是在长文本问答（LFQA）场景中。在本研究中，我们发现了LFQA忠实性与检索头部之间的显著关联，检索头部是一系列负责检索上下文信息的注意力头部。基于这一洞察，我们提出了RHIO框架，旨在教导LLMs明确区分忠实生成和不忠实生成。RHIO首先通过选择性屏蔽检索头部来增强不忠实样例，模拟模型固有的错误，然后将这些样例纳入联合训练，从而让模型在控制令牌条件下区分不忠实输出和忠实输出。此外，这些控制令牌还被利用来自我引导对比性输出，通过对比解码放大其差异。此外，为了方便评估上下文忠实性，我们还引入了GroundBench基准，该基准从五个现有的LFQA数据集中综合而成。在GroundBench上的广泛实验结果表明，RHIO显著提高了忠实性，甚至优于GPT-4o。 

---
# K-COMP: Retrieval-Augmented Medical Domain Question Answering With Knowledge-Injected Compressor 

**Title (ZH)**: K-COMP：知识注入压缩器增强的医学领域检索增援问答 

**Authors**: Jeonghun Cho, Gary Geunbae Lee  

**Link**: [PDF](https://arxiv.org/pdf/2501.13567)  

**Abstract**: Retrieval-augmented question answering (QA) integrates external information, and thereby increases the QA accuracy of reader models that lack domain knowledge. However, documents retrieved for closed domains require high expertise, so the reader model may have difficulty fully comprehending the text. Moreover, the retrieved documents contain thousands of tokens, some unrelated to the question. As a result, the documents include some inaccurate information, which could lead the reader model to mistrust the passages and could result in hallucinations. To solve these problems, we propose K-COMP (Knowledge-injected compressor) which provides the knowledge required to answer correctly. The compressor automatically generates the requisite prior knowledge to facilitate the answering process prior to the compression of retrieved passages. Subsequently, the passages are compressed autoregressively, with the generated knowledge being integrated into the compression process. This process ensures alignment between the question intent and the compressed context. By augmenting this prior knowledge and concise context, the reader models are guided toward relevant answers and trust the context. 

**Abstract (ZH)**: 检索增强问答（QA）通过整合外部信息，提高了缺少领域知识的读者模型的问答准确性。然而，对于封闭领域的文档检索需要高度专业化的知识，因此读者模型可能难以完全理解文本。此外，检索到的文档包含数千个标记，其中一些与问题无关。因此，这些文档可能包含一些不准确的信息，这可能导致读者模型对段落产生怀疑，从而引发幻觉。为了解决这些问题，我们提出了K-COMP（知识注入压缩器），它提供了回答正确问题所需的必要的知识。压缩器自动生成必要的先验知识，以在压缩检索到的段落之前促进回答过程。随后，段落通过自回归方式压缩，生成的知识被整合到压缩过程中。这一过程确保了问题意图与压缩上下文之间的对齐。通过增强这种先验知识和简洁的上下文，读者模型能够更容易地找到相关答案，并信任该上下文。 

---
# RAG-Reward: Optimizing RAG with Reward Modeling and RLHF 

**Title (ZH)**: RAG-Reword：通过奖励建模和RLHF优化RAG

注释：RAG通常指的是Retrieval-Augmented Generation，是一种结合检索和生成的技术，可以在生成文本时利用检索到的相关信息。在翻译时，保持了RAG的缩写形式，但在中文环境中，可以根据上下文将其展开为“检索增强生成”。此外，“RLHF”指的是Reinforcement Learning from Human Feedback，即从人类反馈中学习的强化学习。 

**Authors**: Hanning Zhang, Juntong Song, Juno Zhu, Yuanhao Wu, Tong Zhang, Cheng Niu  

**Link**: [PDF](https://arxiv.org/pdf/2501.13264)  

**Abstract**: Retrieval-augmented generation (RAG) enhances Large Language Models (LLMs) with relevant and up-to-date knowledge, improving their ability to answer knowledge-intensive questions. It has been shown to enhance both generation quality and trustworthiness. While numerous works have focused on improving retrieval, generation, and evaluation, the role of reward models in reinforcement learning for optimizing RAG and establishing automated benchmarking pipelines remains underexplored. In this paper, we introduce \textbf{RAG-Reward}, a dataset designed to enable \textit{hallucination-free, comprehensive, reliable, and efficient RAG}. We define four key metrics for assessing generation quality and develop an automated annotation pipeline that leverages multiple LLMs to generate outputs across diverse RAG scenarios. GPT-4o is used to evaluate and construct preference data. Using \textbf{RAG-Reward}, we train reward models and apply reinforcement learning with human feedback (RLHF) to improve LLMs' effectiveness in RAG. Experimental results show that our reward model achieves state-of-the-art performance on a held-out test set, demonstrating both the effectiveness of our approach and the quality of our dataset. Furthermore, the improved generation quality of the trained policy model highlights the feasibility of using RLHF to enhance RAG pipelines. 

**Abstract (ZH)**: 检索增强生成（RAG）通过引入相关和最新的知识来增强大型语言模型（LLMs），从而提高其回答知识密集型问题的能力。已有研究表明，RAG能够提升生成质量和可信度。尽管许多研究集中在提高检索、生成和评估方面，但在强化学习中利用奖励模型优化RAG以及建立自动基准测试管道的作用仍较少被探索。在本文中，我们介绍了\textbf{RAG-Reward}数据集，旨在实现\textit{无幻觉、全面、可靠且高效的RAG}。我们定义了四个关键指标来评估生成质量，并开发了一个自动化注释管道，该管道利用多个LLM生成适用于多种RAG场景的输出。采用GPT-4o进行评估并构建偏好数据。使用\textbf{RAG-Reward}，我们训练了奖励模型，并应用基于人类反馈的强化学习（RLHF）来提升LLMs在RAG中的有效性。实验结果表明，我们的奖励模型在独立测试集上达到了最先进的性能，证明了我们方法的有效性和数据集的质量。此外，训练策略模型生成质量的提高进一步证实了使用RLHF增强RAG管道的可行性。 

---