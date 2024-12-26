# PromptOptMe: Error-Aware Prompt Compression for LLM-based MT Evaluation Metrics 

**Title (ZH)**: PromptOptMe：面向错误的prompt压缩方法以优化基于LLM的 machine translation 评估指标 

**Authors**: Daniil Larionov, Steffen Eger  

**Link**: [PDF](https://arxiv.org/pdf/2412.16120)  

**Abstract**: Evaluating the quality of machine-generated natural language content is a challenging task in Natural Language Processing (NLP). Recently, large language models (LLMs) like GPT-4 have been employed for this purpose, but they are computationally expensive due to the extensive token usage required by complex evaluation prompts. In this paper, we propose a prompt optimization approach that uses a smaller, fine-tuned language model to compress input data for evaluation prompt, thus reducing token usage and computational cost when using larger LLMs for downstream evaluation. Our method involves a two-stage fine-tuning process: supervised fine-tuning followed by preference optimization to refine the model's outputs based on human preferences. We focus on Machine Translation (MT) evaluation and utilize the GEMBA-MQM metric as a starting point. Our results show a $2.37\times$ reduction in token usage without any loss in evaluation quality. This work makes state-of-the-art LLM-based metrics like GEMBA-MQM more cost-effective and efficient, enhancing their accessibility for broader use. 

**Abstract (ZH)**: 评估机器生成的自然语言内容质量是自然语言处理（NLP）领域的一项具有挑战性的任务。近年来，大型语言模型（LLMs）如GPT-4已经被用于这一任务，但由于复杂的评估提示所需的大量标记使用，使得计算成本高昂。在本文中，我们提出了一种提示优化方法，该方法使用一个较小的微调语言模型来压缩用于评估的输入数据，从而在使用大型LLMs进行下游评估时减少标记使用和计算成本。我们的方法包括两个阶段的微调过程：监督微调，随后是偏好优化，以根据人类偏好细化模型输出。我们专注于机器翻译（MT）评估，并利用GEMBA-MQM度量作为起点。实验结果表明，在没有损失评估质量的情况下，标记使用量减少了2.37倍。这项工作使最先进的基于LLM的度量标准，如GEMBA-MQM更具有成本效益和高效性，从而增强其在更广泛范围中的可访问性。 

---
# Logical Consistency of Large Language Models in Fact-checking 

**Title (ZH)**: 大型语言模型在事实核查中的逻辑一致性研究 

**Authors**: Bishwamittra Ghosh, Sarah Hasan, Naheed Anjum Arafat, Arijit Khan  

**Link**: [PDF](https://arxiv.org/pdf/2412.16100)  

**Abstract**: In recent years, large language models (LLMs) have demonstrated significant success in performing varied natural language tasks such as language translation, question-answering, summarizing, fact-checking, etc. Despite LLMs' impressive ability to generate human-like texts, LLMs are infamous for their inconsistent responses -- a meaning-preserving change in the input query results in an inconsistent response and attributes to vulnerabilities of LLMs such as hallucination, jailbreaking, etc. Consequently, existing research focuses on simple paraphrasing-based consistency assessment of LLMs, and ignores complex queries that necessitates an even better understanding of logical reasoning by an LLM. Our work therefore addresses the logical inconsistency of LLMs under complex logical queries with primitive logical operators, e.g., negation, conjunction, and disjunction. As a test bed, we consider retrieval-augmented LLMs on a fact-checking task involving propositional logic queries from real-world knowledge graphs (KGs). Our contributions are three-fold. Benchmark: We introduce three logical fact-checking datasets over KGs for community development towards logically consistent LLMs. Assessment: We propose consistency measures of LLMs on propositional logic queries as input and demonstrate that existing LLMs lack logical consistency, specially on complex queries. Improvement: We employ supervised fine-tuning to improve the logical consistency of LLMs on the complex fact-checking task with KG contexts. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLM）在诸如语言翻译、问答、摘要、事实核查等多种自然语言任务中展现出显著的成功。尽管LLM在生成类人文本方面表现出色，但它们以不可预测的方式响应，即输入查询的含义保持不变，却导致响应不一致。这种不一致归因于LLM的一些漏洞，如幻觉和破解等。因此，现有研究主要集中在基于简单 paraphrasing 的一致性评估上，而忽视了需要更深入理解逻辑推理的复杂查询。我们的研究工作旨在解决在复杂逻辑查询中使用基本逻辑运算符（如否定、合取和析取）时LLM的逻辑不一致性问题。作为实验平台，我们考虑了在涉及来自现实知识图谱（KGs）的命题逻辑查询的事实核查任务中增强检索的LLM。我们的贡献包括三个方面：

1. **基准数据集**：我们引入了三个基于KG的逻辑事实核查数据集，以促进对逻辑一致的LLM的社区开发。
2. **评估**：我们提出了针对命题逻辑查询的LLM一致性度量，展示现有的LLM在逻辑一致性方面存在不足，尤其是对于复杂的查询。
3. **改进**：我们采用监督微调方法，在包含KG上下文的复杂事实核查任务中提高LLM的逻辑一致性。 

---
# The Only Way is Ethics: A Guide to Ethical Research with Large Language Models 

**Title (ZH)**: 唯一的路是伦理：大型语言模型伦理研究指南 

**Authors**: Eddie L. Ungless, Nikolas Vitsakis, Zeerak Talat, James Garforth, Björn Ross, Arno Onken, Atoosa Kasirzadeh, Alexandra Birch  

**Link**: [PDF](https://arxiv.org/pdf/2412.16022)  

**Abstract**: There is a significant body of work looking at the ethical considerations of large language models (LLMs): critiquing tools to measure performance and harms; proposing toolkits to aid in ideation; discussing the risks to workers; considering legislation around privacy and security etc. As yet there is no work that integrates these resources into a single practical guide that focuses on LLMs; we attempt this ambitious goal. We introduce 'LLM Ethics Whitepaper', which we provide as an open and living resource for NLP practitioners, and those tasked with evaluating the ethical implications of others' work. Our goal is to translate ethics literature into concrete recommendations and provocations for thinking with clear first steps, aimed at computer scientists. 'LLM Ethics Whitepaper' distils a thorough literature review into clear Do's and Don'ts, which we present also in this paper. We likewise identify useful toolkits to support ethical work. We refer the interested reader to the full LLM Ethics Whitepaper, which provides a succinct discussion of ethical considerations at each stage in a project lifecycle, as well as citations for the hundreds of papers from which we drew our recommendations. The present paper can be thought of as a pocket guide to conducting ethical research with LLMs. 

**Abstract (ZH)**: 关于大型语言模型（LLMs）的伦理考虑，已经积累了大量研究工作：批评用于衡量性能和风险的工具；提出辅助创意设计的工具包；讨论对工作者的影响；考虑隐私和安全相关的立法等。迄今为止，还没有将这些资源整合成一个针对LLMs的综合性实用指南的工作；我们试图实现这一艰巨的目标。我们推出了一份名为“LLM伦理白皮书”的资源，为自然语言处理研究者及评估他人工作伦理影响的人员提供了一个开放且不断更新的资源。我们的目标是将伦理文献转化为具体的建议和启发性思考，面向计算机科学家，明确了清晰的第一步。我们在此白皮书中提炼了一份彻底的文献综述，归纳出明确的“可做”和“不可做”原则。我们同样识别了一些有用的工具包以支持伦理工作。有兴趣的读者可以参阅完整的“LLM伦理白皮书”，其中详细讨论了项目生命周期每个阶段的伦理考虑，并提供了我们提出建议所参考的数百篇论文的引用。本文可以视为进行LLM伦理研究的手册。 

---
# Data-Centric Improvements for Enhancing Multi-Modal Understanding in Spoken Conversation Modeling 

**Title (ZH)**: 以数据为中心的改进方法以增强多模态理解在口语对话建模中的效果 

**Authors**: Maximillian Chen, Ruoxi Sun, Sercan Ö. Arık  

**Link**: [PDF](https://arxiv.org/pdf/2412.15995)  

**Abstract**: Conversational assistants are increasingly popular across diverse real-world applications, highlighting the need for advanced multimodal speech modeling. Speech, as a natural mode of communication, encodes rich user-specific characteristics such as speaking rate and pitch, making it critical for effective interaction. Our work introduces a data-centric customization approach for efficiently enhancing multimodal understanding in conversational speech modeling. Central to our contributions is a novel multi-task learning paradigm that involves designing auxiliary tasks to utilize a small amount of speech data. Our approach achieves state-of-the-art performance on the Spoken-SQuAD benchmark, using only 10% of the training data with open-weight models, establishing a robust and efficient framework for audio-centric conversational modeling. We also introduce ASK-QA, the first dataset for multi-turn spoken dialogue with ambiguous user requests and dynamic evaluation inputs. Code and data forthcoming. 

**Abstract (ZH)**: 对话助手在各种现实应用中越来越受欢迎，突显了先进多模态语音建模的必要性。语音作为自然的交流方式，承载着丰富的用户特定特征，如语速和音调，这些特征对于有效的交互至关重要。我们引入了一种以数据为中心的定制方法，以提高对话语音建模中的多模态理解效率。我们贡献的核心在于提出了一种新颖的多任务学习框架，通过设计辅助任务来利用少量的语音数据。我们的方法在Spoken-SQuAD基准测试中达到了最先进的性能，仅使用了10%的训练数据和开放权重模型，建立了以音频为中心的对话建模的稳健且高效的框架。我们还引入了ASK-QA，这是一个首个包含模糊用户请求和动态评估输入的多轮对话数据集。代码和数据即将发布。 

---
# Fearful Falcons and Angry Llamas: Emotion Category Annotations of Arguments by Humans and LLMs 

**Title (ZH)**: 《恐惧的猎鹰与愤怒的羊驼：人类和语言模型对论点情绪类别的标注》 

**Authors**: Lynn Greschner, Roman Klinger  

**Link**: [PDF](https://arxiv.org/pdf/2412.15993)  

**Abstract**: Arguments evoke emotions, influencing the effect of the argument itself. Not only the emotional intensity but also the category influence the argument's effects, for instance, the willingness to adapt stances. While binary emotionality has been studied in arguments, there is no work on discrete emotion categories (e.g., "Anger") in such data. To fill this gap, we crowdsource subjective annotations of emotion categories in a German argument corpus and evaluate automatic LLM-based labeling methods. Specifically, we compare three prompting strategies (zero-shot, one-shot, chain-of-thought) on three large instruction-tuned language models (Falcon-7b-instruct, Llama-3.1-8B-instruct, GPT-4o-mini). We further vary the definition of the output space to be binary (is there emotionality in the argument?), closed-domain (which emotion from a given label set is in the argument?), or open-domain (which emotion is in the argument?). We find that emotion categories enhance the prediction of emotionality in arguments, emphasizing the need for discrete emotion annotations in arguments. Across all prompt settings and models, automatic predictions show a high recall but low precision for predicting anger and fear, indicating a strong bias toward negative emotions. 

**Abstract (ZH)**: 论证可以唤起情感，从而影响论证本身的效果。不仅情感强度，情感类别也会对论证的效果产生影响，例如改变立场的意愿。虽然已经研究了二元情感在论证中的作用，但关于特定离散情感类别（例如“愤怒”）在数据中的研究却鲜有报道。为填补这一空白，我们众包了对一个德语论证语料库中情感类别的主观注释，并评估了自动大型语言模型（LLM）基标注方法。具体来说，我们比较了三种提示策略（零样本、单样本、思考链）在三种大规模指令调优语言模型（Falcon-7b-instruct、Llama-3.1-8B-instruct、GPT-4o-mini）上的表现。此外，我们还改变了输出空间的定义，使其分别为二元（论证中是否有情感？）、闭合领域（从给定标签集中，论证中包含哪个情感？）或开放领域（论证中包含哪种情感？）。我们发现，情感类别能够增强对论证中情感性的预测，突显了在论证中进行离散情感注释的必要性。在所有提示设置和模型中，自动预测对愤怒和恐惧的召回率较高，但精确率较低，表明存在对负面情感的强烈偏见。 

---
# BabyHGRN: Exploring RNNs for Sample-Efficient Training of Language Models 

**Title (ZH)**: BabyHGRN：探索RNN在网络模型样本高效训练中的应用 

**Authors**: Patrick Haller, Jonas Golde, Alan Akbik  

**Link**: [PDF](https://arxiv.org/pdf/2412.15978)  

**Abstract**: This paper explores the potential of recurrent neural networks (RNNs) and other subquadratic architectures as competitive alternatives to transformer-based models in low-resource language modeling scenarios. We utilize HGRN2 (Qin et al., 2024), a recently proposed RNN-based architecture, and comparatively evaluate its effectiveness against transformer-based baselines and other subquadratic architectures (LSTM, xLSTM, Mamba). Our experimental results show that BABYHGRN, our HGRN2 language model, outperforms transformer-based models in both the 10M and 100M word tracks of the challenge, as measured by their performance on the BLiMP, EWoK, GLUE and BEAR benchmarks. Further, we show the positive impact of knowledge distillation. Our findings challenge the prevailing focus on transformer architectures and indicate the viability of RNN-based models, particularly in resource-constrained environments. 

**Abstract (ZH)**: 本文探讨了循环神经网络（RNN）以及其他次平方复杂度架构在低资源语言建模场景中作为基于变压器模型的竞争力替代方案的潜在价值。我们利用了Qin等人（2024）提出的一种基于RNN的HGRN2架构，并将其与基于变压器的标准基准模型以及其他次平方复杂度架构（如LSTM、xLSTM、Mamba）进行了比较评估。实验结果显示，我们的HGRN2语言模型BABYHGRN在挑战中的10M和100M单词赛道上，均优于基于变压器的模型，这是根据其在BLiMP、EWoK、GLUE和BEAR基准上的表现得出的结论。此外，我们还展示了知识蒸馏的积极影响。我们的发现挑战了当前对变压器架构的重视，并表明基于RNN的模型在资源受限环境中具有可行性，尤其是当资源有限时。 

---
# From General to Specific: Tailoring Large Language Models for Personalized Healthcare 

**Title (ZH)**: 从通用到专用：根据个人需求调整大型语言模型以应用于个性化医疗 

**Authors**: Ruize Shi, Hong Huang, Wei Zhou, Kehan Yin, Kai Zhao, Yun Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2412.15957)  

**Abstract**: The rapid development of large language models (LLMs) has transformed many industries, including healthcare. However, previous medical LLMs have largely focused on leveraging general medical knowledge to provide responses, without accounting for patient variability and lacking true personalization at the individual level. To address this, we propose a novel method called personalized medical language model (PMLM), which explores and optimizes personalized LLMs through recommendation systems and reinforcement learning (RL). Specifically, by utilizing self-informed and peer-informed personalization, PMLM captures changes in behaviors and preferences to design initial personalized prompts tailored to individual needs. We further refine these initial personalized prompts through RL, ultimately enhancing the precision of LLM guidance. Notably, the personalized prompt are hard prompt, which grants PMLM high adaptability and reusability, allowing it to directly leverage high-quality proprietary LLMs. We evaluate PMLM using real-world obstetrics and gynecology data, and the experimental results demonstrate that PMLM achieves personalized responses, and it provides more refined and individualized services, offering a potential way for personalized medical LLMs. 

**Abstract (ZH)**: 大型语言模型（LLM）的迅猛发展已经改变了许多行业，包括医疗保健行业。然而，以往的医疗LLM大多侧重于利用通用医学知识来提供响应，而未考虑患者之间的差异性，缺乏真正的个性化服务。为解决这一问题，我们提出了一种新的方法，称为个性化医疗语言模型（PMLM），该方法通过推荐系统和强化学习（RL）探索和优化个性化LLM。具体而言，通过运用自我启发和同伴启发的个性化策略，PMLM捕捉行为和偏好变化，设计出适应个人需求的初始个性化提示。在此基础上，我们进一步通过RL精炼这些初始个性化提示，最终提高LLM指导的精确度。值得注意的是，个性化提示作为硬提示，使得PMLM具有高度的适应性和重复使用性，可以直接利用高质量的专用LLM。我们使用真实的妇产科数据评估了PMLM，并且实验结果表明PMLM能够实现个性化响应，并提供更加细分和个性化的服务，为个性化医疗LLM提供了一种潜在的方式。 

---
# Development of a Large-scale Dataset of Chest Computed Tomography Reports in Japanese and a High-performance Finding Classification Model 

**Title (ZH)**: 日语大型胸部计算机断层扫描报告数据集的开发及高性能发现分类模型的研究 

**Authors**: Yosuke Yamagishi, Yuta Nakamura, Tomohiro Kikuchi, Yuki Sonoda, Hiroshi Hirakawa, Shintaro Kano, Satoshi Nakamura, Shouhei Hanaoka, Takeharu Yoshikawa, Osamu Abe  

**Link**: [PDF](https://arxiv.org/pdf/2412.15907)  

**Abstract**: Background: Recent advances in large language models highlight the need for high-quality multilingual medical datasets. While Japan leads globally in CT scanner deployment and utilization, the lack of large-scale Japanese radiology datasets has hindered the development of specialized language models for medical imaging analysis. Objective: To develop a comprehensive Japanese CT report dataset through machine translation and establish a specialized language model for structured finding classification. Additionally, to create a rigorously validated evaluation dataset through expert radiologist review. Methods: We translated the CT-RATE dataset (24,283 CT reports from 21,304 patients) into Japanese using GPT-4o mini. The training dataset consisted of 22,778 machine-translated reports, while the validation dataset included 150 radiologist-revised reports. We developed CT-BERT-JPN based on "tohoku-nlp/bert-base-japanese-v3" architecture for extracting 18 structured findings from Japanese radiology reports. Results: Translation metrics showed strong performance with BLEU scores of 0.731 and 0.690, and ROUGE scores ranging from 0.770 to 0.876 for Findings and from 0.748 to 0.857 for Impression sections. CT-BERT-JPN demonstrated superior performance compared to GPT-4o in 11 out of 18 conditions, including lymphadenopathy (+14.2%), interlobular septal thickening (+10.9%), and atelectasis (+7.4%). The model maintained F1 scores exceeding 0.95 in 14 out of 18 conditions and achieved perfect scores in four conditions. Conclusions: Our study establishes a robust Japanese CT report dataset and demonstrates the effectiveness of a specialized language model for structured finding classification. The hybrid approach of machine translation and expert validation enables the creation of large-scale medical datasets while maintaining high quality. 

**Abstract (ZH)**: 背景：近年来，大规模语言模型的最新进展突显了高質量多语种医学数据集的重要性。尽管日本在全球CT扫描部署和使用方面处于领先地位，但缺乏大规模的日语放射学数据集阻碍了专门针对医学影像分析的语言模型的发展。目的：通过机器翻译开发一个全面的日语CT报告数据集，并建立一个专门的语言模型用于结构化发现分类。此外，通过专家放射科医师的审查，建立一个严格的验证评估数据集。方法：我们使用GPT-4o mini 将CT-RATE数据集（24,283份来自21,304名患者的CT报告）翻译成日语。训练数据集由22,778份机器翻译报告组成，验证数据集包括150份放射科医师修订的报告。基于"tohoku-nlp/bert-base-japanese-v3"架构开发了CT-BERT-JPN，用于从日语放射学报告中提取18种结构化发现。结果：翻译指标显示了较强的表现，发现部分的BLEU得分为0.731，0.690，摘要部分的得分为0.770到0.876；印象部分的得分为0.748到0.857。在18个条件中有11个，CT-BERT-JPN在18种结构化发现的提取中表现优于GPT-4o，包括淋巴结肿大（+14.2%）、肝叶间隔增厚（+10.9%）和萎陷（+7.4%）。模型在14种条件下的F1分数超过了0.95，在四种条件下取得了完美的成绩。结论：本研究建立了一个坚实的日语CT报告数据集，并展示了专门用于结构化发现分类的语言模型的有效性。通过机器翻译和专家验证的混合方法，可以创建大规模高质量的医学数据集。 

---
# On the Suitability of pre-trained foundational LLMs for Analysis in German Legal Education 

**Title (ZH)**: 预训练基础大语言模型在德国法律教育分析中的适用性研究 

**Authors**: Lorenz Wendlinger, Christian Braun, Abdullah Al Zubaer, Simon Alexander Nonn, Sarah Großkopf, Christofer Fellicious, Michael Granitzer  

**Link**: [PDF](https://arxiv.org/pdf/2412.15902)  

**Abstract**: We show that current open-source foundational LLMs possess instruction capability and German legal background knowledge that is sufficient for some legal analysis in an educational context. However, model capability breaks down in very specific tasks, such as the classification of "Gutachtenstil" appraisal style components, or with complex contexts, such as complete legal opinions. Even with extended context and effective prompting strategies, they cannot match the Bag-of-Words baseline. To combat this, we introduce a Retrieval Augmented Generation based prompt example selection method that substantially improves predictions in high data availability scenarios. We further evaluate the performance of pre-trained LLMs on two standard tasks for argument mining and automated essay scoring and find it to be more adequate. Throughout, pre-trained LLMs improve upon the baseline in scenarios with little or no labeled data with Chain-of-Thought prompting further helping in the zero-shot case. 

**Abstract (ZH)**: 我们表明，当前开源的基础型大语言模型具有一定的指令能力和德法律制背景知识，足以在教育情境下进行部分法律分析。然而，模型的能力在某些特定任务中会失效，例如“Gutachtenstil”评估风格成分的分类，或者在复杂的语境中，如完整的法律意见。即使提供扩展的语境和有效的提示策略，它们也无法匹配基于词汇的基线模型。为解决这一问题，我们提出了一种检索增强生成（RAG）基于提示示例选择的方法，该方法在数据充足的情况下显著提高了预测效果。此外，我们进一步评估了预训练大语言模型在两个标准任务中的表现，即论据挖掘和自动作文评分，并发现它们更为合适。在整个过程中，预训练的大语言模型在标注数据较少或没有的情况下表现更好，链式思考（Chain-of-Thought）提示在零样本情况下也有助于提高性能。 

---
# A Thorough Investigation into the Application of Deep CNN for Enhancing Natural Language Processing Capabilities 

**Title (ZH)**: 对深度CNN在增强自然语言处理能力方面应用的彻底探究 

**Authors**: Chang Weng, Scott Rood, Mehdi Ali Ramezani, Amir Aslani, Reza Zarrab, Wang Zwuo, Sanjeev Salimans, Tim Satheesh  

**Link**: [PDF](https://arxiv.org/pdf/2412.15900)  

**Abstract**: Natural Language Processing (NLP) is widely used in fields like machine translation and sentiment analysis. However, traditional NLP models struggle with accuracy and efficiency. This paper introduces Deep Convolutional Neural Networks (DCNN) into NLP to address these issues. By integrating DCNN, machine learning (ML) algorithms, and generative adversarial networks (GAN), the study improves language understanding, reduces ambiguity, and enhances task performance. The high-performance NLP model shows a 10% improvement in segmentation accuracy and a 4% increase in recall rate compared to traditional models. This integrated approach excels in tasks such as word segmentation, part-of-speech tagging, machine translation, and text classification, offering better recognition accuracy and processing efficiency. 

**Abstract (ZH)**: 自然语言处理（NLP）广泛应用于机器翻译和情感分析等领域。然而，传统的NLP模型在准确性和效率方面存在不足。本文通过引入深度卷积神经网络（DCNN）来解决这些问题。通过将DCNN与机器学习（ML）算法和生成对抗网络（GAN）相结合，本研究提高了语言理解能力，减少了歧义，提升了任务性能。高性能的NLP模型在分词准确率上提高了10%，召回率提高了4%，相对于传统模型表现出显著的提升。这种集成方法在词分割、词性标注、机器翻译和文本分类等任务中表现出色，提供了更好的识别准确率和处理效率。 

---
# TelcoLM: collecting data, adapting, and benchmarking language models for the telecommunication domain 

**Title (ZH)**: TelcoLM：收集数据、适应模型并将其与电信领域中的语言模型进行基准测试 

**Authors**: Camille Barboule, Viet-Phi Huynh, Adrien Bufort, Yoan Chabot, Géraldine Damnati, Gwénolé Lecorvé  

**Link**: [PDF](https://arxiv.org/pdf/2412.15891)  

**Abstract**: Despite outstanding processes in many tasks, Large Language Models (LLMs) still lack accuracy when dealing with highly technical domains. Especially, telecommunications (telco) is a particularly challenging domain due the large amount of lexical, semantic and conceptual peculiarities. Yet, this domain holds many valuable use cases, directly linked to industrial needs. Hence, this paper studies how LLMs can be adapted to the telco domain. It reports our effort to (i) collect a massive corpus of domain-specific data (800M tokens, 80K instructions), (ii) perform adaptation using various methodologies, and (iii) benchmark them against larger generalist models in downstream tasks that require extensive knowledge of telecommunications. Our experiments on Llama-2-7b show that domain-adapted models can challenge the large generalist models. They also suggest that adaptation can be restricted to a unique instruction-tuning step, dicarding the need for any fine-tuning on raw texts beforehand. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）在许多任务中表现出色，但在处理高度技术性的领域时仍然缺乏准确性。特别是在电信（telco）这一特别具有挑战性的领域，由于存在大量的词汇、语义和概念上的特殊性。然而，这一领域包含了众多直接关联工业需求的重要应用场景。因此，本文探讨了如何使LLMs适应电信领域。本文报告了我们为了实现这一目标所做的努力，具体包括：（i）收集大量领域的特定数据集（8亿个标记，8万个指令），（ii）采用多种方法进行适应，以及（iii）在需要广泛电信知识的下游任务中将这些适应后的模型与更大范围的一般模型进行对比基准测试。我们的实验结果显示，领域适应模型可以挑战大型的一般性模型。这些结果还表明，适应可以仅限于一次指令调优步骤，从而取消了在原始文本上进行任何微调的必要性。 

---
# $\pi$-yalli: un nouveau corpus pour le nahuatl 

**Title (ZH)**: π-yalli： Nahua 语言新的语料库 

**Authors**: Juan-Manuel Torres-Moreno, Juan-José Guzmán-Landa, Graham Ranger, Martha Lorena Avendaño Garrido, Miguel Figueroa-Saavedra, Ligia Quintana-Torres, Carlos-Emiliano González-Gallardo, Elvys Linhares Pontes, Patricia Velázquez Morales, Luis-Gil Moreno Jiménez  

**Link**: [PDF](https://arxiv.org/pdf/2412.15821)  

**Abstract**: The NAHU$^2$ project is a Franco-Mexican collaboration aimed at building the $\pi$-YALLI corpus adapted to machine learning, which will subsequently be used to develop computer resources for the Nahuatl language. Nahuatl is a language with few computational resources, even though it is a living language spoken by around 2 million people. We have decided to build $\pi$-YALLI, a corpus that will enable to carry out research on Nahuatl in order to develop Language Models (LM), whether dynamic or not, which will make it possible to in turn enable the development of Natural Language Processing (NLP) tools such as: a) a grapheme unifier, b) a word segmenter, c) a POS grammatical analyser, d) a content-based Automatic Text Summarization; and possibly, e) a translator translator (probabilistic or learning-based). 

**Abstract (ZH)**: NAHU$^2$项目是一个法墨合作项目，旨在构建适应机器学习的$\pi$-YALLI语料库，并随后利用该语料库开发纳瓦特尔语的计算机资源。纳瓦特尔语尽管是一种活的语言，使用者约为200万人，但其可计算资源却十分有限。我们决定构建$\pi$-YALLI语料库，以开展纳瓦特尔语的相关研究，进而开发语言模型（包括动态和非动态模型），这些模型将能够反过来支持自然语言处理（NLP）工具的开发。这些工具包括但不限于：（a）字母统一器，（b）单词分段器，（c）词性标注分析器，（d）基于内容的自动文本摘要；并有可能开发（e）翻译器翻译器（基于概率或学习的方法）。 

---
# Ensembling Large Language Models with Process Reward-Guided Tree Search for Better Complex Reasoning 

**Title (ZH)**: 使用过程奖励引导的树搜索技术集成大型语言模型以实现更复杂的推理 

**Authors**: Sungjin Park, Xiao Liu, Yeyun Gong, Edward Choi  

**Link**: [PDF](https://arxiv.org/pdf/2412.15797)  

**Abstract**: Despite recent advances in large language models, open-source models often struggle to consistently perform well on complex reasoning tasks. Existing ensemble methods, whether applied at the token or output levels, fail to address these challenges. In response, we present Language model Ensemble with Monte Carlo Tree Search (LE-MCTS), a novel framework for process-level ensembling of language models. LE-MCTS formulates step-by-step reasoning with an ensemble of language models as a Markov decision process. In this framework, states represent intermediate reasoning paths, while actions consist of generating the next reasoning step using one of the language models selected from a predefined pool. Guided by a process-based reward model, LE-MCTS performs a tree search over the reasoning steps generated by different language models, identifying the most accurate reasoning chain. Experimental results on five mathematical reasoning benchmarks demonstrate that our approach outperforms both single language model decoding algorithms and language model ensemble methods. Notably, LE-MCTS improves performance by 3.6% and 4.3% on the MATH and MQA datasets, respectively, highlighting its effectiveness in solving complex reasoning problems. 

**Abstract (ZH)**: 尽管近年来大型语言模型取得了重大进展，但开源模型在复杂推理任务上往往难以持续表现出色。现有的集成方法，无论是在标记级还是输出级应用，都无法解决这些问题。为应对这一挑战，我们提出了一种新的语言模型集成框架——基于蒙特卡洛树搜索的语言模型集成（LE-MCTS）。LE-MCTS 将语言模型的逐步推理过程视为马尔可夫决策过程。在这个框架中，状态代表中间推理路径，而动作则是从预定义的池中选择一个语言模型生成下一步推理。通过基于过程导向的奖励模型的引导，LE-MCTS 对不同语言模型生成的推理步骤进行树搜索，识别出最准确的推理链。在五个数学推理基准测试上的实验结果显示，我们的方法优于单个语言模型解码算法以及所有的语言模型集成方法。值得注意的是，LE-MCTS 在 MATH 和 MQA 数据集上的性能分别提高了 3.6% 和 4.3%，突显了其在解决复杂推理问题方面的有效性。 

---
# Learning from Impairment: Leveraging Insights from Clinical Linguistics in Language Modelling Research 

**Title (ZH)**: 从缺陷中学习：借鉴临床语言学见解推进语言模型研究 

**Authors**: Dominique Brunato  

**Link**: [PDF](https://arxiv.org/pdf/2412.15785)  

**Abstract**: This position paper investigates the potential of integrating insights from language impairment research and its clinical treatment to develop human-inspired learning strategies and evaluation frameworks for language models (LMs). We inspect the theoretical underpinnings underlying some influential linguistically motivated training approaches derived from neurolinguistics and, particularly, aphasiology, aimed at enhancing the recovery and generalization of linguistic skills in aphasia treatment, with a primary focus on those targeting the syntactic domain. We highlight how these insights can inform the design of rigorous assessments for LMs, specifically in their handling of complex syntactic phenomena, as well as their implications for developing human-like learning strategies, aligning with efforts to create more sustainable and cognitively plausible natural language processing (NLP) models. 

**Abstract (ZH)**: 本文的研究立场探讨了将语言障碍研究及其临床治疗方法中的见解整合到语言模型（LMs）中，以开发受人类启发的学习策略和评估框架的潜力。我们审视了神经语言学和尤其是失语症学中一些有影响力的、以语言为导向的训练方法的理论基础，特别是那些旨在增强失语症治疗中语言技能恢复和一般化的做法，重点关注那些针对句法领域的研究。我们强调，这些见解如何可以启发对LMs进行严格评估的设计，特别是在它们处理复杂句法现象方面，以及它们如何影响人类学习策略的开发，从而与创建更可持续且认知上合理的自然语言处理（NLP）模型的努力相一致。 

---
# Linguistic Features Extracted by GPT-4 Improve Alzheimer's Disease Detection based on Spontaneous Speech 

**Title (ZH)**: GPT-4 提取的 Linguistic 特征基于自发言语提高 Alzheimer's 病检测 

**Authors**: Jonathan Heitz, Gerold Schneider, Nicolas Langer  

**Link**: [PDF](https://arxiv.org/pdf/2412.15772)  

**Abstract**: Alzheimer's Disease (AD) is a significant and growing public health concern. Investigating alterations in speech and language patterns offers a promising path towards cost-effective and non-invasive early detection of AD on a large scale. Large language models (LLMs), such as GPT, have enabled powerful new possibilities for semantic text analysis. In this study, we leverage GPT-4 to extract five semantic features from transcripts of spontaneous patient speech. The features capture known symptoms of AD, but they are difficult to quantify effectively using traditional methods of computational linguistics. We demonstrate the clinical significance of these features and further validate one of them ("Word-Finding Difficulties") against a proxy measure and human raters. When combined with established linguistic features and a Random Forest classifier, the GPT-derived features significantly improve the detection of AD. Our approach proves effective for both manually transcribed and automatically generated transcripts, representing a novel and impactful use of recent advancements in LLMs for AD speech analysis. 

**Abstract (ZH)**: 阿尔茨海默病（AD）是当前一个重要的公共卫生问题，探索言语和语言模式的变化为成本低且无创的大规模早期检测AD提供了一条有希望的道路。大型语言模型（LLMs），如GPT，为语义文本分析带来了强大的新可能性。在本研究中，我们利用GPT-4从自发患者言语的转录中提取五个语义特征。这些特征捕捉到了AD已知的症状，但传统计算语言学方法难以有效量化。我们展示了这些特征的临床意义，并进一步通过替代指标和人工评分验证了其中一个特征（“找词困难”）。当这些特征与现有的语言特征以及随机森林分类器结合使用时，能够显著提高AD的检测效果。我们的方法证明了在手动转录和自动生成的转录中均有效，代表了近期LLMs在AD言语分析中的一种新颖且具有影响力的使用方式。 

---
# Critique of Impure Reason: Unveiling the reasoning behaviour of medical Large Language Models 

**Title (ZH)**: 《不纯洁的理由：揭开医疗大型语言模型的推理行为》

这个标题翻译成中文后，既保留了原文的意思，也符合学术论文标题的规范。 

**Authors**: Shamus Sim, Tyrone Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15748)  

**Abstract**: Background: Despite the current ubiquity of Large Language Models (LLMs) across the medical domain, there is a surprising lack of studies which address their reasoning behaviour. We emphasise the importance of understanding reasoning behaviour as opposed to high-level prediction accuracies, since it is equivalent to explainable AI (XAI) in this context. In particular, achieving XAI in medical LLMs used in the clinical domain will have a significant impact across the healthcare sector. Results: Therefore, we define the concept of reasoning behaviour in the specific context of medical LLMs. We then categorise and discuss the current state of the art of methods which evaluate reasoning behaviour in medical LLMs. Finally, we propose theoretical frameworks which can empower medical professionals or machine learning engineers to gain insight into the low-level reasoning operations of these previously obscure models. Conclusion: The subsequent increased transparency and trust in medical machine learning models by clinicians as well as patients will accelerate the integration, application as well as further development of medical AI for the healthcare system as a whole 

**Abstract (ZH)**: 背景：尽管大型语言模型（LLMs）在医学领域已经无处不在，但却缺乏专注于它们推理行为的研究。我们强调理解推理行为的重要性，而非仅仅关注高层预测精度，因为这一点在医学领域等同于可解释的人工智能（XAI）。特别是，实现医学LLMs中的XAI将在整个医疗健康领域产生重大影响。结果：因此，我们定义了医学LLMs中推理行为的特定概念。我们随后对当前用于评估医学LLMs推理行为的方法进行了分类和讨论。最后，我们提出了理论框架，以帮助医疗专业人士或机器学习工程师深入了解这些过去较为隐晦模型的底层推理操作。结论：由此将增加临床医生和患者对医学机器学习模型的透明度和信任度，进而推动整个医疗健康系统的医学AI的集成、应用及其进一步发展。 

---
# Fine-tuning Whisper on Low-Resource Languages for Real-World Applications 

**Title (ZH)**: 将Whisper在低资源语言上的微调应用于实际场景 

**Authors**: Vincenzo Timmel, Claudio Paonessa, Reza Kakooee, Manfred Vogel, Daniel Perruchoud  

**Link**: [PDF](https://arxiv.org/pdf/2412.15726)  

**Abstract**: This paper presents a new approach to fine-tuning OpenAI's Whisper model for low-resource languages by introducing a novel data generation method that converts sentence-level data into a long-form corpus, using Swiss German as a case study. Non-sentence-level data, which could improve the performance of long-form audio, is difficult to obtain and often restricted by copyright laws. Our method bridges this gap by transforming more accessible sentence-level data into a format that preserves the model's ability to handle long-form audio and perform segmentation without requiring non-sentence-level data. Our data generation process improves performance in several real-world applications and leads to the development of a new state-of-the-art speech-to-text (STT) model for Swiss German. We compare our model with a non-fine-tuned Whisper and our previous state-of-the-art Swiss German STT models, where our new model achieves higher BLEU scores. Our results also indicate that the proposed method is adaptable to other low-resource languages, supported by written guidance and code that allows the creation of fine-tuned Whisper models, which keep segmentation capabilities and allow the transcription of longer audio files using only sentence-level data with high quality. 

**Abstract (ZH)**: 本文提出了一种新的方法，用于通过引入一种新颖的数据生成方法来细化 OpenAI 的 Whisper 模型，该方法将句子级数据转换成长篇语料库，并以瑞士德语为例进行了研究。非句子级数据虽然可以提升长篇音频的表现，但获取难度较大且常受到版权法的限制。我们通过将更易获取的句子级数据转换为能够保持模型处理长篇音频和进行分段能力的格式，填补了这一空白，无需使用非句子级数据。我们的数据生成过程在多个现实应用中提高了性能，并开发了首个用于瑞士德语的最先进的语音转文本（STT）模型。我们将我们的模型与未经过微调的 Whisper 以及我们之前最先进的瑞士德语 STT 模型进行了比较，结果显示我们新模型的 BLEU 分数较高。我们的研究结果还表明，所提出的方法可以适应其他低资源语言，提供了书面指导和代码，可以在仅使用高质量的句子级数据的情况下创建具有分段能力的微调 Whisper 模型，并实现较长音频文件的转录。 

---
# Contrastive Learning for Task-Independent SpeechLLM-Pretraining 

**Title (ZH)**: 用于任务无关语音大语言模型的对比学习预训练 

**Authors**: Maike Züfle, Jan Niehues  

**Link**: [PDF](https://arxiv.org/pdf/2412.15712)  

**Abstract**: Large language models (LLMs) excel in natural language processing but adapting these LLMs to speech processing tasks efficiently is not straightforward. Direct task-specific fine-tuning is limited by overfitting risks, data requirements, and computational costs. To address these challenges, we propose a scalable, two-stage training approach: (1) A task-independent speech pretraining stage using contrastive learning to align text and speech representations over all layers, followed by (2) a task-specific fine-tuning stage requiring minimal data. This approach outperforms traditional ASR pretraining and enables the model to surpass models specialized on speech translation and question answering while being trained on only 10% of the task-specific data. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在自然语言处理方面表现出色，但将这些LLMs高效地适应语音处理任务并不 straightforward。直接的任务特定微调受限于过拟合风险、数据需求和计算成本。为了解决这些挑战，我们提出了一种可扩展的两阶段训练方法：（1）使用对比学习进行任务无关的语音预训练阶段，该阶段通过所有层将文本表示和语音表示对齐，随后是（2）要求最少数据的任务特定微调阶段。该方法优于传统ASR预训练，并使模型能够在仅使用10%的任务特定数据的情况下超越专注于语音翻译和问答的专用模型。 

---
# Variability Need Not Imply Error: The Case of Adequate but Semantically Distinct Responses 

**Title (ZH)**: 变异性未必意味着错误：充分但语义上不同的反应案例 

**Authors**: Evgenia Ilia, Wilker Aziz  

**Link**: [PDF](https://arxiv.org/pdf/2412.15683)  

**Abstract**: With the broader use of language models (LMs) comes the need to estimate their ability to respond reliably to prompts (e.g., are generated responses likely to be correct?). Uncertainty quantification tools (notions of confidence and entropy, i.a.) can be used to that end (e.g., to reject a response when the model is `uncertain'). For example, Kuhn et al. (semantic entropy; 2022b) regard semantic variation amongst sampled responses as evidence that the model `struggles' with the prompt and that the LM is likely to err. We argue that semantic variability need not imply error--this being especially intuitive in open-ended settings, where prompts elicit multiple adequate but semantically distinct responses. Hence, we propose to annotate sampled responses for their adequacy to the prompt (e.g., using a classifier) and estimate the Probability the model assigns to Adequate Responses (PROBAR), which we then regard as an indicator of the model's reliability at the instance level. We evaluate PROBAR as a measure of confidence in selective prediction with OPT models (in two QA datasets and in next-word prediction, for English) and find PROBAR to outperform semantic entropy across prompts with varying degrees of ambiguity/open-endedness. 

**Abstract (ZH)**: 随着语言模型（LMs）的应用范围不断扩大，评估其对提示作出可靠响应的能力变得愈加重要（例如，生成的响应是否很可能正确？）。为了实现这一目标，可以使用不确定性量化工具（如置信度和熵的概念等），以便在模型“不确定”时拒绝响应。例如，Kuhn等人（语义熵；2022b）认为，样本响应之间语义上的多样性是模型“难以应对”提示和模型可能会出错的证据。我们提出，语义多样性未必意味着错误，特别是在开放性设置中尤为直观，因为提示可能引发多个语义上不相同但都足够恰当的响应。因此，我们建议为样本响应标注它们对提示的适当性（例如，使用分类器），并估计模型为适当响应分配的概率（PROBAR），将其视为模型在实例级别的可靠性指标。我们评估在OPT模型中PROBAR作为选择性预测置信度度量的表现（在两个问答数据集和英语的下一个词预测中），发现与语义熵相比，PROBAR在不同模糊度/开放性程度的提示下表现更佳。 

---
# MathSpeech: Leveraging Small LMs for Accurate Conversion in Mathematical Speech-to-Formula 

**Title (ZH)**: 数学语音转换：利用小型语言模型实现准确的数学语音到公式转换 

**Authors**: Sieun Hyeon, Kyudan Jung, Jaehee Won, Nam-Joon Kim, Hyun Gon Ryu, Hyuk-Jae Lee, Jaeyoung Do  

**Link**: [PDF](https://arxiv.org/pdf/2412.15655)  

**Abstract**: In various academic and professional settings, such as mathematics lectures or research presentations, it is often necessary to convey mathematical expressions orally. However, reading mathematical expressions aloud without accompanying visuals can significantly hinder comprehension, especially for those who are hearing-impaired or rely on subtitles due to language barriers. For instance, when a presenter reads Euler's Formula, current Automatic Speech Recognition (ASR) models often produce a verbose and error-prone textual description (e.g., e to the power of i x equals cosine of x plus i $\textit{side}$ of x), instead of the concise $\LaTeX{}$ format (i.e., $ e^{ix} = \cos(x) + i\sin(x) $), which hampers clear understanding and communication. To address this issue, we introduce MathSpeech, a novel pipeline that integrates ASR models with small Language Models (sLMs) to correct errors in mathematical expressions and accurately convert spoken expressions into structured $\LaTeX{}$ representations. Evaluated on a new dataset derived from lecture recordings, MathSpeech demonstrates $\LaTeX{}$ generation capabilities comparable to leading commercial Large Language Models (LLMs), while leveraging fine-tuned small language models of only 120M parameters. Specifically, in terms of CER, BLEU, and ROUGE scores for $\LaTeX{}$ translation, MathSpeech demonstrated significantly superior capabilities compared to GPT-4o. We observed a decrease in CER from 0.390 to 0.298, and higher ROUGE/BLEU scores compared to GPT-4o. 

**Abstract (ZH)**: 在各种学术和专业环境中，如数学讲座或研究展示中，口头传达数学表达式通常是必要的。然而，没有辅助视觉的情况下朗读数学表达式会严重影响理解，尤其是在听力受限的人或者因语言障碍依赖字幕的情况下。例如，当演讲者读到欧拉公式时，当前的自动语音识别（ASR）模型往往会生成冗长且容易出错的文字描述（如“e的i倍x次方等于x的余弦加上i乘以x的正弦”），而不是简洁的LaTeX格式（即 $e^{ix} = \cos(x) + i\sin(x)$），这会妨碍清晰的理解和交流。为了应对这一问题，我们提出了MathSpeech这一新的处理管道，将ASR模型与小型语言模型（sLMs）结合，以纠正数学表达式中的错误，并准确地将口头表达转换为结构化的LaTeX表示形式。该模型在基于讲座录音构建的新数据集上进行了评估，结果显示MathSpeech在LaTeX生成能力上与主要的商用大型语言模型（LLMs）相当，同时仅利用了1.2亿参数的微调小型语言模型。具体而言，根据LaTeX翻译的编辑距离（CER）、BLEU和ROUGE分数，MathSpeech在这些指标上表现出显著优于GPT-4o的能力。我们观察到CER从0.390降低到0.298，ROUGE和BLEU分数也高于GPT-4o。 

---
# Error-driven Data-efficient Large Multimodal Model Tuning 

**Title (ZH)**: 错误驱动的数据高效大型多模态模型调优 

**Authors**: Barry Menglong Yao, Qifan Wang, Lifu Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15652)  

**Abstract**: Large Multimodal Models (LMMs) have demonstrated impressive performance across numerous academic benchmarks. However, fine-tuning still remains essential to achieve satisfactory performance on downstream tasks, while the task-specific tuning samples are usually not readily available or expensive and time-consuming to obtain. To address this, we propose an error-driven data-efficient tuning framework that aims to efficiently adapt generic LMMs to newly emerging tasks without requiring any task-specific training samples. In our approach, a generic LMM, acting as a student model, is first evaluated on a small validation set of the target task, and then a more powerful model, acting as a teacher model, identifies the erroneous steps within the student model's reasoning steps and analyzes its capability gaps from fully addressing the target task. Based on these gaps, targeted training samples are further retrieved from existing task-agnostic datasets to tune the student model and tailor it to the target task. We perform extensive experiments across three different training data scales and seven tasks, demonstrating that our training paradigm significantly and efficiently improves LMM's performance on downstream tasks, achieving an average performance boost of 7.01%. 

**Abstract (ZH)**: 大规模多模态模型（Large Multimodal Models, LMMs）已经在众多学术基准测试中展示了杰出的性能。然而，为了在下游任务中实现满意的性能，模型仍需进行微调，而特定任务的数据样本通常难以获得或获取成本高昂且耗时。为解决这一问题，我们提出了一种基于错误驱动的数据高效微调框架，旨在无需任何特定任务的训练样本的情况下，使通用LMMs能够快速适应新出现的任务。在我们的方法中，一个通用LMM作为学生模型，首先在目标任务的小型验证集上进行评估；随后，一个更强大的模型作为教师模型，识别学生模型推理过程中的错误步骤，并分析其在完全完成目标任务中的能力差距。根据这些差距，我们进一步从现有的任务无关数据集中检索目标特定的训练样本，以调整学生模型并使其适应目标任务。我们进行了广泛的实验，涵盖了三个不同的训练数据规模和七个任务，结果显示我们的训练范式显著且高效地提高了LMM在下游任务上的性能，平均提升了7.01%。 

---
# Can Input Attributions Interpret the Inductive Reasoning Process Elicited in In-Context Learning? 

**Title (ZH)**: 输入归因能否解释基于上下文学习中引发的归纳推理过程？ 

**Authors**: Mengyu Ye, Tatsuki Kuribayashi, Goro Kobayashi, Jun Suzuki  

**Link**: [PDF](https://arxiv.org/pdf/2412.15628)  

**Abstract**: Elucidating the rationale behind neural models' outputs has been challenging in the machine learning field, which is indeed applicable in this age of large language models (LLMs) and in-context learning (ICL). When it comes to estimating input attributions (IA), ICL poses a new issue of interpreting which example in the prompt, consisting of a set of examples, contributed to identifying the task/rule to be solved. To this end, in this paper, we introduce synthetic diagnostic tasks inspired by the poverty of the stimulus design in inductive reasoning; here, most in-context examples are ambiguous w.r.t. their underlying rule, and one critical example disambiguates the task demonstrated. The question is whether conventional IA methods can identify such an example in interpreting the inductive reasoning process in ICL. Our experiments provide several practical findings; for example, a certain simple IA method works the best, and the larger the model, the generally harder it is to interpret the ICL with gradient-based IA methods. 

**Abstract (ZH)**: 阐明神经模型输出背后的理据在机器学习领域一直具有挑战性，这一问题在当前的大语言模型（LLMs）和在上下文学习（ICL）时代尤其适用。当涉及到输入归因（IA）的估计时，ICL 引入了一个新的问题：即如何解释在提示中包含的一组示例中，哪个示例对识别要解决的任务/规则起到了关键作用。为了解决这个问题，本文介绍了一种由归纳推理设计中的贫乏刺激设计启发的合成诊断任务；在这里，大多数示例在基本规则方面是模棱两可的，而一个关键的示例则澄清了所展示的任务。问题是，传统的IA方法是否能在解释ICL中的归纳推理过程时识别出这样的示例。我们的实验提供了多个实际发现，例如，某些简单的IA方法表现最好，而随着模型规模的增大，基于梯度的IA方法通常更难以解释ICL。 

---
# A Fusion Approach of Dependency Syntax and Sentiment Polarity for Feature Label Extraction in Commodity Reviews 

**Title (ZH)**: 依赖语法与情感极性融合的方法在商品评论中特征标签提取中的应用 

**Authors**: Jianfei Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15610)  

**Abstract**: This study analyzes 13,218 product reviews from this http URL, covering four categories: mobile phones, computers, cosmetics, and food. A novel method for feature label extraction is proposed by integrating dependency parsing and sentiment polarity analysis. The proposed method addresses the challenges of low robustness in existing extraction algorithms and significantly enhances extraction accuracy. Experimental results show that the method achieves an accuracy of 0.7, with recall and F-score both stabilizing at 0.8, demonstrating its effectiveness. However, challenges such as dependence on matching dictionaries and the limited scope of extracted feature tags require further investigation in future research. 

**Abstract (ZH)**: 本研究分析了从该网址（此网址）获取的13,218条产品评价数据，涵盖了四类商品：手机、电脑、化妆品和食品。本文提出了一种新颖的功能标签提取方法，该方法结合了依赖性解析和情感极性分析。所提出的方法解决了现有提取算法低稳健性的问题，显著提升了提取准确性。实验结果显示，该方法的准确率为0.7，召回率和F分数均稳定在0.8，表明其有效性。然而，该方法对匹配字典的依赖性以及提取功能标签范围有限等问题仍需在未来研究中进一步探讨。 

---
# Don't Do RAG: When Cache-Augmented Generation is All You Need for Knowledge Tasks 

**Title (ZH)**: 不要进行检索增强生成：当知识任务仅需缓存增强生成时 

**Authors**: Brian J Chan, Chao-Ting Chen, Jui-Hung Cheng, Hen-Hsen Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15605)  

**Abstract**: Retrieval-augmented generation (RAG) has gained traction as a powerful approach for enhancing language models by integrating external knowledge sources. However, RAG introduces challenges such as retrieval latency, potential errors in document selection, and increased system complexity. With the advent of large language models (LLMs) featuring significantly extended context windows, this paper proposes an alternative paradigm, cache-augmented generation (CAG) that bypasses real-time retrieval. Our method involves preloading all relevant resources, especially when the documents or knowledge for retrieval are of a limited and manageable size, into the LLM's extended context and caching its runtime parameters. During inference, the model utilizes these preloaded parameters to answer queries without additional retrieval steps. Comparative analyses reveal that CAG eliminates retrieval latency and minimizes retrieval errors while maintaining context relevance. Performance evaluations across multiple benchmarks highlight scenarios where long-context LLMs either outperform or complement traditional RAG pipelines. These findings suggest that, for certain applications, particularly those with a constrained knowledge base, CAG provide a streamlined and efficient alternative to RAG, achieving comparable or superior results with reduced complexity. 

**Abstract (ZH)**: 检索增强生成（RAG）作为一种通过集成外部知识源增强语言模型的强大方法，已经引起了广泛关注。然而，RAG引入了诸如检索延迟、文档选择潜在错误以及系统复杂性增加等挑战。随着大型语言模型（LLMs）出现，特征是具有显著扩展的上下文窗口，本文提出了一种替代范式——缓存增强生成（CAG），它绕过了实时检索。我们的方法包括预先加载所有相关资源，尤其是在检索所需的文档或知识有限且可管理时，将其加载到LLM的扩展上下文中，并缓存其运行时参数。在推理过程中，模型利用这些预先加载的参数来回答查询，而无需额外的检索步骤。比较分析表明，CAG消除了检索延迟并最小化了检索错误，同时保持了上下文的相关性。性能评估跨多个基准表明，长上下文LLM在某些情况下要么优于或补充传统RAG流水线。这些发现表明，对于某些特定应用，特别是那些知识库受限制的应用，CAG提供了一种更简洁高效的选择，通过降低复杂度就能实现相当甚至更优的结果。 

---
# Dynamic Label Name Refinement for Few-Shot Dialogue Intent Classification 

**Title (ZH)**: 面向少样本对话意图分类的动态标签名称精炼 

**Authors**: Gyutae Park, Ingeol Baek, ByeongJeong Kim, Joongbo Shin, Hwanhee Lee  

**Link**: [PDF](https://arxiv.org/pdf/2412.15603)  

**Abstract**: Dialogue intent classification aims to identify the underlying purpose or intent of a user's input in a conversation. Current intent classification systems encounter considerable challenges, primarily due to the vast number of possible intents and the significant semantic overlap among similar intent classes. In this paper, we propose a novel approach to few-shot dialogue intent classification through in-context learning, incorporating dynamic label refinement to address these challenges. Our method retrieves relevant examples for a test input from the training set and leverages a large language model to dynamically refine intent labels based on semantic understanding, ensuring that intents are clearly distinguishable from one another. Experimental results demonstrate that our approach effectively resolves confusion between semantically similar intents, resulting in significantly enhanced performance across multiple datasets compared to baselines. We also show that our method generates more interpretable intent labels, and has a better semantic coherence in capturing underlying user intents compared to baselines. 

**Abstract (ZH)**: 对话意图分类的目标是识别用户输入在对话中存在的潜在目的或意图。当前的意图分类系统面临诸多挑战，主要原因是可能的意图种类繁多以及相似意图类别之间的重大语义重叠。在本文中，我们提出了一种通过上下文学习实现少样本对话意图分类的新型方法，并结合动态标签优化以应对这些挑战。该方法从训练集中检索与测试输入相关的示例，并利用大型语言模型基于语义理解动态优化意图标签，确保各个意图之间能够明显区分。实验结果表明，我们的方法有效解决了语义相似意图之间的混淆，相较于基线方法，在多个数据集上均展现出显著提高的性能。此外，我们也证明了我们的方法生成了更具可解释性的意图标签，并在捕捉用户潜在意图方面具有更好的语义连贯性。 

---
# Template-Driven LLM-Paraphrased Framework for Tabular Math Word Problem Generation 

**Title (ZH)**: 基于模板驱动的大语言模型改写框架：表格数值问题生成 

**Authors**: Xiaoqiang Kang, Zimu Wang, Xiaobo Jin, Wei Wang, Kaizhu Huang, Qiufeng Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15594)  

**Abstract**: Solving tabular math word problems (TMWPs) has become a critical role in evaluating the mathematical reasoning ability of large language models (LLMs), where large-scale TMWP samples are commonly required for LLM fine-tuning. Since the collection of high-quality TMWP datasets is costly and time-consuming, recent research has concentrated on automatic TMWP generation. However, current generated samples usually suffer from issues of either correctness or diversity. In this paper, we propose a Template-driven LLM-paraphrased (TeLL) framework for generating high-quality TMWP samples with diverse backgrounds and accurate tables, questions, answers, and solutions. To this end, we first extract templates from existing real samples to generate initial problems, ensuring correctness. Then, we adopt an LLM to extend templates and paraphrase problems, obtaining diverse TMWP samples. Furthermore, we find the reasoning annotation is important for solving TMWPs. Therefore, we propose to enrich each solution with illustrative reasoning steps. Through the proposed framework, we construct a high-quality dataset TabMWP-TeLL by adhering to the question types in the TabMWP dataset, and we conduct extensive experiments on a variety of LLMs to demonstrate the effectiveness of TabMWP-TeLL in improving TMWP solving performance. The code and data of this paper are available at: this https URL. 

**Abstract (ZH)**: 将以下论文内容或标题翻译成中文，符合学术规范：

表格数学文字问题（TMWPs）的求解已成为评估大规模语言模型（LLMs）数学推理能力的关键领域，通常需要大量的TMWP样本来对LLMs进行微调。由于高质量TMWP数据集的收集成本高昂且耗时，近年来的研究主要集中在自动TMWP生成方面。然而，现有的生成样本通常在正确性和多样性方面存在问题。本文提出了一个基于模板的大规模语言模型重述（TeLL）框架，用于生成具备多样化背景且包含准确表格、问题、答案和解决步骤的高质量TMWP样本。为此，我们首先从现有样本中提取模板以生成初始问题，确保其正确性；然后，我们利用大规模语言模型扩展模板并重述问题，以获得多样化的TMWP样本。此外，我们发现推理标注对于解决TMWPs至关重要。因此，我们提出为每个解决方案添加说明性的推理步骤。通过所提出的方法，我们基于TabMWP数据集中的问题类型构建了一个高质量数据集TabMWP-TeLL，并在多种LLMs上进行了广泛的实验，以证明TabMWP-TeLL在提高TMWP解决性能方面的有效性。本文的代码和数据可在以下链接获得：this https URL。 

---
# NeSyCoCo: A Neuro-Symbolic Concept Composer for Compositional Generalization 

**Title (ZH)**: NeSyCoCo：一种神经符号概念合成器，实现组合泛化 

**Authors**: Danial Kamali, Elham J. Barezi, Parisa Kordjamshidi  

**Link**: [PDF](https://arxiv.org/pdf/2412.15588)  

**Abstract**: Compositional generalization is crucial for artificial intelligence agents to solve complex vision-language reasoning tasks. Neuro-symbolic approaches have demonstrated promise in capturing compositional structures, but they face critical challenges: (a) reliance on predefined predicates for symbolic representations that limit adaptability, (b) difficulty in extracting predicates from raw data, and (c) using non-differentiable operations for combining primitive concepts. To address these issues, we propose NeSyCoCo, a neuro-symbolic framework that leverages large language models (LLMs) to generate symbolic representations and map them to differentiable neural computations. NeSyCoCo introduces three innovations: (a) augmenting natural language inputs with dependency structures to enhance the alignment with symbolic representations, (b) employing distributed word representations to link diverse, linguistically motivated logical predicates to neural modules, and (c) using the soft composition of normalized predicate scores to align symbolic and differentiable reasoning. Our framework achieves state-of-the-art results on the ReaSCAN and CLEVR-CoGenT compositional generalization benchmarks and demonstrates robust performance with novel concepts in the CLEVR-SYN benchmark. 

**Abstract (ZH)**: 组合泛化对于人工智能代理解决复杂的视知觉推理任务至关重要。神经符号方法在捕捉组合结构方面显示出前景，但它们面临关键挑战：（a）依赖预定义谓词进行符号表示，这限制了适应性；（b）从原始数据中抽取出谓词的难度；（c）使用非可微操作结合基本概念。为了解决这些问题，我们提出了NeSyCoCo这一神经符号框架，利用大规模语言模型（LLMs）生成符号表示并将其映射到可微神经计算中。NeSyCoCo引入了三项创新：（a）在自然语言输入中增加依存结构，以增强与符号表示的对齐；（b）采用分布式词向量表示，将多种语言动机逻辑谓词链接到神经模块；（c）利用标准化谓词得分的软组合，使符号和可微推理对齐。我们的框架在ReaSCAN和CLEVR-CoGenT组合泛化基准测试中达到了最先进的效果，并在CLEVR-SYN基准测试中的新技术概念上表现出稳健的性能。 

---
# In-context Continual Learning Assisted by an External Continual Learner 

**Title (ZH)**: 基于外部连续学习者的上下文连续学习 

**Authors**: Saleh Momeni, Sahisnu Mazumder, Zixuan Ke, Bing Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15563)  

**Abstract**: Existing continual learning (CL) methods mainly rely on fine-tuning or adapting large language models (LLMs). They still suffer from catastrophic forgetting (CF). Little work has been done to exploit in-context learning (ICL) to leverage the extensive knowledge within LLMs for CL without updating any parameters. However, incrementally learning each new task in ICL necessitates adding training examples from each class of the task to the prompt, which hampers scalability as the prompt length increases. This issue not only leads to excessively long prompts that exceed the input token limit of the underlying LLM but also degrades the model's performance due to the overextended context. To address this, we introduce InCA, a novel approach that integrates an external continual learner (ECL) with ICL to enable scalable CL without CF. The ECL is built incrementally to pre-select a small subset of likely classes for each test instance. By restricting the ICL prompt to only these selected classes, InCA prevents prompt lengths from becoming excessively long, while maintaining high performance. Experimental results demonstrate that InCA significantly outperforms existing CL baselines, achieving substantial performance gains. 

**Abstract (ZH)**: 现有的连续学习（CL）方法主要依赖于微调或适应大型语言模型（LLMs）。这些方法仍然受到灾难性遗忘（CF）的困扰。较少的工作致力于利用上下文学习（ICL）来利用LLMs中的丰富知识进行CL，而不更新任何参数。然而，ICL中逐增量地学习每个新任务需要为每个任务的类别添加训练示例到提示中，这随着提示长度的增加会降低可扩展性。这一问题不仅导致提示过长，超出了底层LLM的输入token限制，还因上下文过度扩展而降低了模型的性能。为解决这一问题，我们提出了一种名为InCA的新方法，该方法将外部连续学习器（ECL）与ICL相结合，以实现无CF的可扩展CL。ECL逐增量地构建，以预选每个测试实例的少量可能类别。通过将ICL提示限制为仅这些选定的类别，InCA防止了提示长度的急剧增长，同时保持了高性能。实验结果表明，InCA显著优于现有CL基线，实现了显著的性能提升。 

---
# NGQA: A Nutritional Graph Question Answering Benchmark for Personalized Health-aware Nutritional Reasoning 

**Title (ZH)**: NGQA：个性化健康意识营养推理的营养图问答基准 

**Authors**: Zheyuan Zhang, Yiyang Li, Nhi Ha Lan Le, Zehong Wang, Tianyi Ma, Vincent Galassi, Keerthiram Murugesan, Nuno Moniz, Werner Geyer, Nitesh V Chawla, Chuxu Zhang, Yanfang Ye  

**Link**: [PDF](https://arxiv.org/pdf/2412.15547)  

**Abstract**: Diet plays a critical role in human health, yet tailoring dietary reasoning to individual health conditions remains a major challenge. Nutrition Question Answering (QA) has emerged as a popular method for addressing this problem. However, current research faces two critical limitations. On one hand, the absence of datasets involving user-specific medical information severely limits \textit{personalization}. This challenge is further compounded by the wide variability in individual health needs. On the other hand, while large language models (LLMs), a popular solution for this task, demonstrate strong reasoning abilities, they struggle with the domain-specific complexities of personalized healthy dietary reasoning, and existing benchmarks fail to capture these challenges. To address these gaps, we introduce the Nutritional Graph Question Answering (NGQA) benchmark, the first graph question answering dataset designed for personalized nutritional health reasoning. NGQA leverages data from the National Health and Nutrition Examination Survey (NHANES) and the Food and Nutrient Database for Dietary Studies (FNDDS) to evaluate whether a food is healthy for a specific user, supported by explanations of the key contributing nutrients. The benchmark incorporates three question complexity settings and evaluates reasoning across three downstream tasks. Extensive experiments with LLM backbones and baseline models demonstrate that the NGQA benchmark effectively challenges existing models. In sum, NGQA addresses a critical real-world problem while advancing GraphQA research with a novel domain-specific benchmark. 

**Abstract (ZH)**: 饮食在人类健康中扮演着至关重要的角色，但根据个人健康状况定制饮食建议仍然面临巨大挑战。营养问答（Nutrition QA）已经成为解决这一问题的一种流行方法。然而，当前的研究存在两个关键限制。一方面，缺乏包含用户特定医疗信息的数据库极大限制了个性化。这一挑战进一步受到个体健康需求广泛变化的影响。另一方面，尽管大规模语言模型（LLMs）在这一任务中表现出强大的推理能力，但在处理个性化健康饮食推理的领域特定复杂性方面仍存在困难，现有的基准测试也未能捕捉到这些挑战。为解决这些缺口，我们引入了营养图问题回答（NGQA）基准，这是第一个用于个性化营养健康推理的图问题回答数据集。NGQA 利用国家健康与营养检查调查（NHANES）和膳食研究中的食品和营养数据库（FNDDS）的数据，评估特定用户是否适合某种食物，并提供了关键营养成分的解释。基准测试包括三个问题复杂性设置，并在三个下游任务上评估推理能力。广泛的实验使用大规模语言模型和基线模型表明，NGQA 基准有效地挑战了现有的模型。总而言之，NGQA 不仅解决了一个关键的现实世界问题，还通过一个新颖的领域特定基准推动了图问题回答（GraphQA）研究的发展。 

---
# MRAG: A Modular Retrieval Framework for Time-Sensitive Question Answering 

**Title (ZH)**: MRAG：一种用于时间敏感问题回答的模块化检索框架 

**Authors**: Zhang Siyue, Xue Yuxiang, Zhang Yiming, Wu Xiaobao, Luu Anh Tuan, Zhao Chen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15540)  

**Abstract**: Understanding temporal relations and answering time-sensitive questions is crucial yet a challenging task for question-answering systems powered by large language models (LLMs). Existing approaches either update the parametric knowledge of LLMs with new facts, which is resource-intensive and often impractical, or integrate LLMs with external knowledge retrieval (i.e., retrieval-augmented generation). However, off-the-shelf retrievers often struggle to identify relevant documents that require intensive temporal reasoning. To systematically study time-sensitive question answering, we introduce the TempRAGEval benchmark, which repurposes existing datasets by incorporating temporal perturbations and gold evidence labels. As anticipated, all existing retrieval methods struggle with these temporal reasoning-intensive questions. We further propose Modular Retrieval (MRAG), a trainless framework that includes three modules: (1) Question Processing that decomposes question into a main content and a temporal constraint; (2) Retrieval and Summarization that retrieves evidence and uses LLMs to summarize according to the main content; (3) Semantic-Temporal Hybrid Ranking that scores each evidence summarization based on both semantic and temporal relevance. On TempRAGEval, MRAG significantly outperforms baseline retrievers in retrieval performance, leading to further improvements in final answer accuracy. 

**Abstract (ZH)**: 理解时间关系并回答时间敏感的问题是大型语言模型（LLMs）驱动的问题回答系统面临的一个关键但具有挑战性的任务。现有的方法要么通过更新LLMs的参数知识来加入新事实，这需要大量资源且通常不现实，要么将LLMs与外部知识检索结合起来（即检索增强生成）。然而，现成的检索器在识别需要密集时间推理的相关文档方面常常表现不佳。为了系统地研究时间敏感的问题回答，我们引入了TempRAGEval基准，该基准通过引入时间扰动和黄金证据标签重新利用现有的数据集。正如预期的那样，所有现有的检索方法在这些需要密集时间推理的问题上都表现不佳。我们进一步提出了模块化检索（MRAG），这是一种无需训练的框架，包括三个模块：（1）问题处理，将问题分解为主内容和时间约束；（2）检索和摘要，检索证据并使用LLMs根据主内容进行总结；（3）语义-时间混合排序，基于语义和时间相关性为每项证据摘要打分。在TempRAGEval上，MRAG在检索性能上显著优于基线检索器，从而进一步提高了最终答案的准确性。 

---
# XRAG: eXamining the Core -- Benchmarking Foundational Components in Advanced Retrieval-Augmented Generation 

**Title (ZH)**: XRAG: 探索核心——高级检索增强生成的基础组件评估 

**Authors**: Qianren Mao, Yangyifei Luo, Jinlong Zhang, Hanwen Hao, Zhilong Cao, Xiaolong Wang, Xiao Guan, Zhenting Huang, Weifeng Jiang, Shuyu Guo, Zhentao Han, Qili Zhang, Siyuan Tao, Yujie Liu, Junnan Liu, Zhixing Tan, Jie Sun, Bo Li, Xudong Liu, Richong Zhang, Jianxin Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.15529)  

**Abstract**: Retrieval-augmented generation (RAG) synergizes the retrieval of pertinent data with the generative capabilities of Large Language Models (LLMs), ensuring that the generated output is not only contextually relevant but also accurate and this http URL introduce XRAG, an open-source, modular codebase that facilitates exhaustive evaluation of the performance of foundational components of advanced RAG modules. These components are systematically categorized into four core phases: pre-retrieval, retrieval, post-retrieval, and generation. We systematically analyse them across reconfigured datasets, providing a comprehensive benchmark for their effectiveness. Given the escalating complexity of RAG systems, we underscore the necessity of identifying potential failure points of RAG modules. We formulate a suite of experimental methodologies and diagnostic testing protocols to dissect the failure points inherent in the engineering of RAG modules. Subsequently, we proffer bespoke solutions that are designed to augment the validation processes and bolster the overall performance of these modules. Our work thoroughly evaluates the performance of core advanced components in RAG systems, providing insights into optimizations for prevalent failure points. 

**Abstract (ZH)**: 检索增强生成（RAG）将相关数据的检索能力与大型语言模型（LLMs）的生成能力相结合，确保生成的输出不仅具有上下文相关性，还能保持准确性和可靠性。本文介绍了XRAG，一个开源、模块化的代码库，旨在进行全面评估先进RAG模块基础组件的性能。这些组件被系统地归类为四个核心阶段：预检索、检索、后检索和生成。我们通过对重新配置的数据集进行全面分析，提供了这些组件有效性的综合基准。随着RAG系统的复杂性日益增加，我们强调识别RAG模块潜在故障点的重要性。我们制定了实验方法和诊断测试协议，旨在剖析工程RAG模块时固有的故障点。随后，我们提出了一些定制化的解决方案，旨在增强这些模块的验证过程，从而提高它们的整体性能。我们的工作全面评估了RAG系统中核心先进组件的性能，提供了针对常见故障点优化的见解。 

---
# HREF: Human Response-Guided Evaluation of Instruction Following in Language Models 

**Title (ZH)**: 基于人类反馈的语言模型指令跟随评估方法 

**Authors**: Xinxi Lyu, Yizhong Wang, Hannaneh Hajishirzi, Pradeep Dasigi  

**Link**: [PDF](https://arxiv.org/pdf/2412.15524)  

**Abstract**: Evaluating the capability of Large Language Models (LLMs) in following instructions has heavily relied on a powerful LLM as the judge, introducing unresolved biases that deviate the judgments from human judges. In this work, we reevaluate various choices for automatic evaluation on a wide range of instruction-following tasks. We experiment with methods that leverage human-written responses and observe that they enhance the reliability of automatic evaluations across a wide range of tasks, resulting in up to a 3.2% improvement in agreement with human judges. We also discovered that human-written responses offer an orthogonal perspective to model-generated responses in following instructions and should be used as an additional context when comparing model responses. Based on these observations, we develop a new evaluation benchmark, Human Response-Guided Evaluation of Instruction Following (HREF), comprising 4,258 samples across 11 task categories with a composite evaluation setup, employing a composite evaluation setup that selects the most reliable method for each category. In addition to providing reliable evaluation, HREF emphasizes individual task performance and is free from contamination. Finally, we study the impact of key design choices in HREF, including the size of the evaluation set, the judge model, the baseline model, and the prompt template. We host a live leaderboard that evaluates LLMs on the private evaluation set of HREF. 

**Abstract (ZH)**: 对大型语言模型（LLMs）遵循指令能力的评估长期以来主要依赖于一个强大的LLM作为评判者，这引入了未解决的偏见，导致其判断与人类评判者产生偏差。在本研究中，我们重新评估了在广泛范围的指令遵循任务中自动评估的各种方法。我们尝试了利用人工撰写响应的方法，并观察到这些方法在各种任务中增强了自动评估的可靠性，结果在与人类评判者的共识方面提高了高达3.2%。我们还发现，人工撰写的响应为指令遵循提供了另一种独立视角，应该在比较模型响应时作为额外上下文使用。基于这些发现，我们开发了一个新的评估基准——人工响应引导的指令遵循评估（HREF），包含包含4258个样本的多个任务类别，通过综合评估设置选择每类任务最可靠的方法。此外，HREF不仅提供了可靠的评估，还强调了个体任务的性能，并且不受污染。最后，我们研究了HREF中关键设计选择的影响，包括评估集的规模、评判模型、基线模型和提示模板。我们还提供了一个实时排行榜，该排行榜在HREF的私有评估集上对LLMs进行评估。 

---
# ADEQA: A Question Answer based approach for joint ADE-Suspect Extraction using Sequence-To-Sequence Transformers 

**Title (ZH)**: ADEQA：一种基于问题回答的方法，使用序列到序列变换器联合提取ADE和怀疑药物edata 

**Authors**: Vinayak Arannil, Tomal Deb, Atanu Roy  

**Link**: [PDF](https://arxiv.org/pdf/2412.15510)  

**Abstract**: Early identification of Adverse Drug Events (ADE) is critical for taking prompt actions while introducing new drugs into the market. These ADEs information are available through various unstructured data sources like clinical study reports, patient health records, social media posts, etc. Extracting ADEs and the related suspect drugs using machine learning is a challenging task due to the complex linguistic relations between drug ADE pairs in textual data and unavailability of large corpus of labelled datasets. This paper introduces ADEQA, a question-answer(QA) based approach using quasi supervised labelled data and sequence-to-sequence transformers to extract ADEs, drug suspects and the relationships between them. Unlike traditional QA models, natural language generation (NLG) based models don't require extensive token level labelling and thereby reduces the adoption barrier significantly. On a public ADE corpus, we were able to achieve state-of-the-art results with an F1 score of 94% on establishing the relationships between ADEs and the respective suspects. 

**Abstract (ZH)**: 早期识别不良药物事件（ADE）对于在市场推出新药物时采取及时行动至关重要。这些ADE信息可通过临床研究报告、患者健康记录、社交媒体帖子等各种非结构化数据源获得。使用机器学习从文本数据中提取ADE及其相关可疑药物是一个具有挑战性的问题，因为药物-ADE对之间的语言关系复杂，且缺乏大量标注数据集。本文介绍了一种基于问题-答案（QA）的方法——ADEQA，该方法利用准监督标注数据和序列到序列的变换器来提取ADE、可疑药物及其之间的关系。与传统的QA模型不同，基于自然语言生成（NLG）的模型不需要进行详尽的标记，从而显著降低了采用障碍。在公共ADE数据集上，我们能够以94%的F1分数实现关系建立的最先进结果。 

---
# Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework 

**Title (ZH)**: 在多代理框架内的多目标方法减轻大型语言模型中的社会偏见 

**Authors**: Zhenjie Xu, Wenqing Chen, Yi Tang, Xuanying Li, Cheng Hu, Zhixuan Chu, Kui Ren, Zibin Zheng, Zhichao Lu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15504)  

**Abstract**: Natural language processing (NLP) has seen remarkable advancements with the development of large language models (LLMs). Despite these advancements, LLMs often produce socially biased outputs. Recent studies have mainly addressed this problem by prompting LLMs to behave ethically, but this approach results in unacceptable performance degradation. In this paper, we propose a multi-objective approach within a multi-agent framework (MOMA) to mitigate social bias in LLMs without significantly compromising their performance. The key idea of MOMA involves deploying multiple agents to perform causal interventions on bias-related contents of the input questions, breaking the shortcut connection between these contents and the corresponding answers. Unlike traditional debiasing techniques leading to performance degradation, MOMA substantially reduces bias while maintaining accuracy in downstream tasks. Our experiments conducted on two datasets and two models demonstrate that MOMA reduces bias scores by up to 87.7%, with only a marginal performance degradation of up to 6.8% in the BBQ dataset. Additionally, it significantly enhances the multi-objective metric icat in the StereoSet dataset by up to 58.1%. Code will be made available at this https URL. 

**Abstract (ZH)**: 自然语言处理（NLP）随着大型语言模型（LLMs）的发展取得了显著进展。尽管取得了这些进展，但LLMs常常产生社会偏见的输出。近期的研究主要通过促使LLMs表现得更加伦理来解决这一问题，但这种做法会导致性能显著下降。本文提出了一种多目标方法（MOMA），在多智能体框架内减轻LLMs中的社会偏见，而不显著牺牲其性能。MOMA的核心思想是部署多个智能体对输入问题中的偏见相关内容进行因果干预，从而打破这些内容与相应答案之间的捷径连接。与传统去偏方法导致的性能下降不同，MOMA在大幅减少偏见的同时，能够维持下游任务的准确性。我们在两个数据集和两个模型上进行的实验表明，MOMA在BBQ数据集上仅导致至多6.8%的轻微性能下降，同时将偏见分数降低至高达87.7%。此外，MOMA还在StereoSet数据集上显著提高了多目标指标icat，提高幅度高达58.1%。代码将在以下链接处开源：this https URL。 

---
# Humanlike Cognitive Patterns as Emergent Phenomena in Large Language Models 

**Title (ZH)**: 大型语言模型中的人类认知模式作为 emergent 现象 

**Authors**: Zhisheng Tang, Mayank Kejriwal  

**Link**: [PDF](https://arxiv.org/pdf/2412.15501)  

**Abstract**: Research on emergent patterns in Large Language Models (LLMs) has gained significant traction in both psychology and artificial intelligence, motivating the need for a comprehensive review that offers a synthesis of this complex landscape. In this article, we systematically review LLMs' capabilities across three important cognitive domains: decision-making biases, reasoning, and creativity. We use empirical studies drawing on established psychological tests and compare LLMs' performance to human benchmarks. On decision-making, our synthesis reveals that while LLMs demonstrate several human-like biases, some biases observed in humans are absent, indicating cognitive patterns that only partially align with human decision-making. On reasoning, advanced LLMs like GPT-4 exhibit deliberative reasoning akin to human System-2 thinking, while smaller models fall short of human-level performance. A distinct dichotomy emerges in creativity: while LLMs excel in language-based creative tasks, such as storytelling, they struggle with divergent thinking tasks that require real-world context. Nonetheless, studies suggest that LLMs hold considerable potential as collaborators, augmenting creativity in human-machine problem-solving settings. Discussing key limitations, we also offer guidance for future research in areas such as memory, attention, and open-source model development. 

**Abstract (ZH)**: 对大型语言模型（LLMs）中涌现模式的研究已在心理学和人工智能领域引起了广泛关注，这激发了对其复杂景观进行全面综述的需求，旨在提供这一领域的综合性的合成。本文系统地回顾了LLMs在三个重要的认知领域的能力：决策偏差、推理和创造力。我们采用了基于已建立的心理学测试的实证研究，将LLMs的表现与人类基准进行比较。在决策方面，我们的综述表明，尽管LLMs表现出几种类似人类的偏差，但一些在人类中观察到的偏差是不存在的，这表明认知模式与人类决策部分对齐。在推理方面，先进的LLMs如GPT-4表现出类似于人类系统2思维的审慎推理，而较小的模型未能达到人类水平的表现。在创造力方面，LLMs在基于语言的创造性任务方面表现出色，例如讲故事，但在需要现实世界背景的发散思维任务中表现不佳。然而，研究表明，LLMs在人类与机器问题解决设置中的协作中具有巨大的潜力，可以增强创造力。我们还讨论了关键限制，并为未来的研究提供指导，特别是关于记忆、注意力以及开源模型开发的领域。 

---
# The First Multilingual Model For The Detection of Suicide Texts 

**Title (ZH)**: 第一个多语言模型用于自杀文本检测 

**Authors**: Rodolfo Zevallos, Annika Schoene, John E. Ortega  

**Link**: [PDF](https://arxiv.org/pdf/2412.15498)  

**Abstract**: Suicidal ideation is a serious health problem affecting millions of people worldwide. Social networks provide information about these mental health problems through users' emotional expressions. We propose a multilingual model leveraging transformer architectures like mBERT, XML-R, and mT5 to detect suicidal text across posts in six languages - Spanish, English, German, Catalan, Portuguese and Italian. A Spanish suicide ideation tweet dataset was translated into five other languages using SeamlessM4T. Each model was fine-tuned on this multilingual data and evaluated across classification metrics. Results showed mT5 achieving the best performance overall with F1 scores above 85%, highlighting capabilities for cross-lingual transfer learning. The English and Spanish translations also displayed high quality based on perplexity. Our exploration underscores the importance of considering linguistic diversity in developing automated multilingual tools to identify suicidal risk. Limitations exist around semantic fidelity in translations and ethical implications which provide guidance for future human-in-the-loop evaluations. 

**Abstract (ZH)**: 自杀意念是一个影响全球数百万人的重大健康问题。社交媒体通过用户的感情表达提供了关于这些心理健康问题的信息。我们提出了一种利用mBERT、XML-R和mT5等变压器架构的多语言模型，以在六种语言——西班牙语、英语、德语、加泰罗尼亚语、葡萄牙语和意大利语——的帖子中检测自杀性文本。使用SeamlessM4T将西班牙语的自杀意念推文数据集翻译成五种其他语言。每种模型均在这个多语言数据集上进行微调，并通过分类指标进行评估。结果显示，mT5整体表现最佳，F1分数超过85%，突显了跨语言迁移学习的能力。英语和西班牙语翻译的质量也非常高，根据 perplexity 测量。我们的探索强调了在开发自动多语言工具以识别自杀风险时考虑语言多样性的重要性。翻译中的语义保真度限制和伦理问题为未来的人机结合评估提供了指导。 

---
# Lexicography Saves Lives (LSL): Automatically Translating Suicide-Related Language 

**Title (ZH)**: 词典编纂拯救生命 (LSL): 自动翻译与自杀相关语言 

**Authors**: Annika Marie Schoene, John E. Ortega, Rodolfo Joel Zevallos, Laura Haaber Ihle  

**Link**: [PDF](https://arxiv.org/pdf/2412.15497)  

**Abstract**: Recent years have seen a marked increase in research that aims to identify or predict risk, intention or ideation of suicide. The majority of new tasks, datasets, language models and other resources focus on English and on suicide in the context of Western culture. However, suicide is global issue and reducing suicide rate by 2030 is one of the key goals of the UN's Sustainable Development Goals. Previous work has used English dictionaries related to suicide to translate into different target languages due to lack of other available resources. Naturally, this leads to a variety of ethical tensions (e.g.: linguistic misrepresentation), where discourse around suicide is not present in a particular culture or country. In this work, we introduce the 'Lexicography Saves Lives Project' to address this issue and make three distinct contributions. First, we outline ethical consideration and provide overview guidelines to mitigate harm in developing suicide-related resources. Next, we translate an existing dictionary related to suicidal ideation into 200 different languages and conduct human evaluations on a subset of translated dictionaries. Finally, we introduce a public website to make our resources available and enable community participation. 

**Abstract (ZH)**: 近年来，旨在识别或预测自杀风险、意图或观念的研究呈现出显著的增长。大多数新的任务、数据集、语言模型以及其他资源主要集中在英语以及西方文化背景下的自杀问题上。然而，自杀是一个全球性问题，到2030年减少自杀率是联合国可持续发展目标中的关键目标之一。先前的工作由于缺乏其他可用资源，往往会使用与自杀相关的英语词典来翻译成目标语言。自然地，这导致了一系列伦理困境（例如：语言误导），其中关于自杀的讨论在特定的文化或国家中并未出现。在此项工作中，我们介绍了“Lexicography Saves Lives Project”项目以解决这一问题，并做出三项贡献。首先，我们概述了伦理考量，并提供了减小发展自杀相关资源时潜在危害的总体指导方针。其次，我们将一个与自杀观念相关的词典翻译成200种不同的语言，并对翻译后的词典进行了部分人工评估。最后，我们引入了一个公共网站，以使我们的资源可供使用并促进社区参与。 

---
# TL-Training: A Task-Feature-Based Framework for Training Large Language Models in Tool Use 

**Title (ZH)**: TL-训练：一种基于任务特征的大型语言模型训练框架，用于工具使用 

**Authors**: Junjie Ye, Yilong Wu, Sixian Li, Yuming Yang, Tao Gui, Qi Zhang, Xuanjing Huang, Peng Wang, Zhongchao Shi, Jianping Fan, Zhengyin Du  

**Link**: [PDF](https://arxiv.org/pdf/2412.15495)  

**Abstract**: Large language models (LLMs) achieve remarkable advancements by leveraging tools to interact with external environments, a critical step toward generalized AI. However, the standard supervised fine-tuning (SFT) approach, which relies on large-scale datasets, often overlooks task-specific characteristics in tool use, leading to performance bottlenecks. To address this issue, we analyze three existing LLMs and uncover key insights: training data can inadvertently impede tool-use behavior, token importance is distributed unevenly, and errors in tool calls fall into a small set of distinct categories. Building on these findings, we propose TL-Training, a task-feature-based framework that mitigates the effects of suboptimal training data, dynamically adjusts token weights to prioritize key tokens during SFT, and incorporates a robust reward mechanism tailored to error categories, optimized through proximal policy optimization. We validate TL-Training by training CodeLLaMA-2-7B and evaluating it on four diverse open-source test sets. Our results demonstrate that the LLM trained by our method matches or surpasses both open- and closed-source LLMs in tool-use performance using only 1,217 training data points. Additionally, our method enhances robustness in noisy environments and improves general task performance, offering a scalable and efficient paradigm for tool-use training in LLMs. The code and data are available at this https URL. 

**Abstract (ZH)**: 大型语言模型（LLMs）通过利用工具与外部环境交互，实现了显著的进步，这是通向通用人工智能的关键步骤。然而，依赖大规模数据集的标准监督微调（SFT）方法往往忽略了工具使用中的任务特定特征，导致性能瓶颈。为了解决这一问题，我们分析了三种现有的LLMs，并发现了一些关键见解：训练数据可能无意中阻碍了工具使用行为，各标记的重要性分布不均，工具调用错误主要集中在几个不同的类别中。基于这些发现，我们提出了一种基于任务特征的TL-Training框架，该框架可以缓解不理想的训练数据的影响，在微调过程中动态调整标记权重以优先处理关键标记，并引入了一种针对错误类别优化的 robust 奖励机制。我们通过训练 CodeLLaMA-2-7B 并使用四个不同的开源测试集对其进行评估，验证了TL-Training的有效性。我们的结果显示，通过我们的方法训练的LLM仅使用1,217个训练数据点，就能在工具使用性能上匹配或超越开源和封闭源的LLM。此外，我们的方法还提高了在噪声环境中的稳健性，并提高了通用任务性能，为LLMs中的工具使用训练提供了一种可扩展且高效的范式。完整的代码和数据可在以下链接获取：[请插入链接]。 

---
# Multi-LLM Text Summarization 

**Title (ZH)**: 多语言大型语言模型文本摘要 

**Authors**: Jiangnan Fang, Cheng-Tse Liu, Jieun Kim, Yash Bhedaru, Ethan Liu, Nikhil Singh, Nedim Lipka, Puneet Mathur, Nesreen K. Ahmed, Franck Dernoncourt, Ryan A. Rossi, Hanieh Deilamsalehy  

**Link**: [PDF](https://arxiv.org/pdf/2412.15487)  

**Abstract**: In this work, we propose a Multi-LLM summarization framework, and investigate two different multi-LLM strategies including centralized and decentralized. Our multi-LLM summarization framework has two fundamentally important steps at each round of conversation: generation and evaluation. These steps are different depending on whether our multi-LLM decentralized summarization is used or centralized. In both our multi-LLM decentralized and centralized strategies, we have k different LLMs that generate diverse summaries of the text. However, during evaluation, our multi-LLM centralized summarization approach leverages a single LLM to evaluate the summaries and select the best one whereas k LLMs are used for decentralized multi-LLM summarization. Overall, we find that our multi-LLM summarization approaches significantly outperform the baselines that leverage only a single LLM by up to 3x. These results indicate the effectiveness of multi-LLM approaches for summarization. 

**Abstract (ZH)**: 在本文中，我们提出了一种多大型语言模型（Multi-LLM）总结框架，并探讨了两种不同的多大型语言模型策略，包括集中式和去中心化策略。我们的多大型语言模型总结框架在每次对话回合中包含两个基本步骤：生成和评估。这两个步骤会根据是使用去中心化的多大型语言模型总结还是集中式的总结而有所不同。在我们的去中心化和集中式多大型语言模型策略中，都会使用k个不同的大型语言模型来生成文本的多样化总结。然而，在评估阶段，我们的集中式多大型语言模型总结方法使用单一的大型语言模型来评估总结并选择最佳结果，而在去中心化的多大型语言模型总结方法中，会使用k个大型语言模型。总体而言，我们发现我们的多大型语言模型总结方法相对于只使用单一大型语言模型的基线方法取得显著改进，最高提升可达3倍。这些结果表明，多大型语言模型方法在总结任务中的有效性。 

---
# Continual Learning Using Only Large Language Model Prompting 

**Title (ZH)**: 仅使用大型语言模型提示的持续学习 

**Authors**: Jiabao Qiu, Zixuan Ke, Bing Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15479)  

**Abstract**: We introduce CLOB, a novel continual learning (CL) paradigm wherein a large language model (LLM) is regarded as a black box. Learning is done incrementally via only verbal prompting. CLOB does not fine-tune any part of the LLM or add any trainable parameters to it. It is particularly suitable for LLMs that are accessible via APIs. We also propose a new CL technique, called CIS, based on incremental summarization that also overcomes the LLM's input length limit. Experiments show CIS outperforms baselines by a very large margin. 

**Abstract (ZH)**: 我们引入了CLOB（Continual Learning Box），这是一种新颖的连续学习（Continual Learning, CL）范式，其中大型语言模型（Large Language Model, LLM）被视为一个黑盒。学习是通过仅使用口头提示进行增量学习完成的。CLOB 不对 LLM 的任何部分进行微调，也不为其添加任何可训练参数。它特别适用于通过 API 访问的 LLM。我们还提出了一种新的 CL 技术，称为CIS（Continual Incremental Summarization），该技术基于增量总结，并克服了LLM的输入长度限制。实验结果表明，CIS 在性能上显著优于基线方法。 

---
# A Review of the Marathi Natural Language Processing 

**Title (ZH)**: 马拉地语自然语言处理的综述 

**Authors**: Asang Dani, Shailesh R Sathe  

**Link**: [PDF](https://arxiv.org/pdf/2412.15471)  

**Abstract**: Marathi is one of the most widely used languages in the world. One might expect that the latest advances in NLP research in languages like Enlighs reach such a large community. However, NLP advancements in English didn't immediately reach Indian languages like Marathi. There were several reasons for this. They included diversity of scripts used, lack of (publicly available) resources like tokenization strategies, high quality datasets \& benchmarks, and evaluation metrics. In addition to this, the morphologically rich nature of Marathi, made NLP tasks challenging. Advances in Neural Network (NN) based models and tools since the early 2000s helped improve this situation and make NLP research more accessible. In the past 10 years, significant efforts were made to improve language resources for all 22 scheduled languages of India. This paper presents a broad overview of evolution of NLP research in Indic languages with a focus on Marathi and state-of-the-art resources and tools available to the research community. It also provides an overview of tools \& techniques associated with Marathi NLP tasks. 

**Abstract (ZH)**: 马哈拉SH特语是世界上使用最广泛的语言之一。人们可能会预料到，英语等语言的最新自然语言处理（NLP）研究进展会迅速影响如此庞大的社区。然而，英语的NLP进展并没有立即惠及如马哈拉SH特语这样的印度语言。这种延迟的原因有多种，包括使用的书写系统多样性、缺乏（公开可用的）如分词策略、高质量的数据集和基准测试以及评估指标等资源。此外，马哈拉SH特语丰富的形态特征使NLP任务变得更加复杂。自2000年代初以来，基于神经网络（NN）的模型和工具的发展有助于改善这一情况，使其更加易于进行NLP研究。在过去十年中，为了所有印度22种官方语言的语言资源都取得了显著的进步。本文概述了印地语族语言的NLP研究演化，重点关注马哈拉SH特语，并介绍了研究社区可用的最新资源和工具。此外，本文还概述了与马哈拉SH特语NLP任务相关的工具和技术。 

---
# Northeastern Uni at Multilingual Counterspeech Generation: Enhancing Counter Speech Generation with LLM Alignment through Direct Preference Optimization 

**Title (ZH)**: 东北师范大学在多语言反制言论生成中的研究：通过直接偏好优化实现语言模型对齐以增强反制言论生成 

**Authors**: Sahil Wadhwa, Chengtian Xu, Haoming Chen, Aakash Mahalingam, Akankshya Kar, Divya Chaudhary  

**Link**: [PDF](https://arxiv.org/pdf/2412.15453)  

**Abstract**: The automatic generation of counter-speech (CS) is a critical strategy for addressing hate speech by providing constructive and informed responses. However, existing methods often fail to generate high-quality, impactful, and scalable CS, particularly across diverse linguistic contexts. In this paper, we propose a novel methodology to enhance CS generation by aligning Large Language Models (LLMs) using Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO). Our approach leverages DPO to align LLM outputs with human preferences, ensuring contextually appropriate and linguistically adaptable responses. Additionally, we incorporate knowledge grounding to enhance the factual accuracy and relevance of generated CS. Experimental results demonstrate that DPO-aligned models significantly outperform SFT baselines on CS benchmarks while scaling effectively to multiple languages. These findings highlight the potential of preference-based alignment techniques to advance CS generation across varied linguistic settings. The model supervision and alignment is done in English and the same model is used for reporting metrics across other languages like Basque, Italian, and Spanish. 

**Abstract (ZH)**: 自动生成反驳言论（CS）是应对仇恨言论的一个关键策略，通过提供具有建设性和信息性的回应。然而，现有方法在生成高质量、有影响力且可扩展的反驳言论方面往往效果不佳，尤其是在多种语言背景下。本文提出了一种新的方法来增强反驳言论的生成，该方法通过监督微调（SFT）和直接偏好优化（DPO）对大型语言模型（LLMs）进行对齐。我们的方法利用DPO确保生成的反驳言论适合具体情境，并且在语言上具有适应性。此外，我们还引入了知识接地策略，以提高生成反驳言论的准确性和相关性。实验结果表明，通过对齐的DPO模型在多种语言的反驳言论基准测试中显著优于SFT基线，并且能够有效扩展到其他语言，如巴斯克语、意大利语和西班牙语。这些发现表明，基于偏好的对齐技术具有推动反驳言论生成跨多种语言环境发展的潜力。模型的监督和对齐在英语中完成，而性能指标在其他语言（例如巴斯克语、意大利语和西班牙语）中使用同一模型进行报告。 

---
# Fietje: An open, efficient LLM for Dutch 

**Title (ZH)**: 费特捷：一种开源高效的荷兰语大型语言模型 

**Authors**: Bram Vanroy  

**Link**: [PDF](https://arxiv.org/pdf/2412.15450)  

**Abstract**: This paper introduces Fietje, a family of small language models (SLMs) specifically designed for the Dutch language. The model is based on Phi 2, an English-centric model of 2.7 billion parameters. Fietje demonstrated competitive results with larger language models upon its release. A core emphasis of this work is transparency and reproducibility: Fietje is fully open-source, with model weights, datasets, training, and evaluation code all publicly accessible.
The paper discusses the performance of Fietje and many other models on an extensive evaluation suite of benchmarks on reasoning, sentiment analysis, world knowledge, linguistic acceptability and word sense disambiguation. Evaluation results illustrate the rapid progress in the field of LLMs, where recent small models outperform older, larger models that were fine-tuned for Dutch. This trend signals an exciting future for Dutch language processing, suggesting that even compact LLMs are becoming increasingly capable. Furthermore, ongoing and future efforts to adapt LLMs to Dutch are poised to enhance these models even further, broadening their applicability and accessibility. Fietje is only an intermediate step in improving accessibility to language technology for users of the Dutch language. 

**Abstract (ZH)**: 本文介绍了Fietje，一种专门针对荷兰语的小型语言模型（SLMs）家族。该模型基于具有27亿参数的Phi 2模型，这是一位以英语为中心的模型。Fietje在发布时展现出与大型语言模型竞争的成果。本项工作的核心重点是透明性和可再现性：Fietje 完全开源，其模型权重、数据集、训练代码和评估代码均可公开访问。

本文讨论了Fietje 和其他许多模型在广泛的基准测试集上的表现，这些基准测试涵盖了逻辑推理、情感分析、世界知识、语言接受性和词义消歧等不同领域。评估结果展示了大型语言模型（LLMs）领域快速进步的现状，其中近期的小型模型在荷兰语处理方面超越了之前通过微调改进的大型模型。这一趋势预示着荷兰语处理的未来充满活力，表明即使是紧凑型的LLMs也在变得越来越强大。此外，未来努力将LLMs适配至荷兰语将进一步增强这些模型，拓宽其应用范围和可访问性。Fietje 只是提高荷兰语用户对语言技术访问性的中间步骤。 

---
# SKETCH: Structured Knowledge Enhanced Text Comprehension for Holistic Retrieval 

**Title (ZH)**: SKETCH: 结构化知识增强的文本理解方法用于全面检索 

**Authors**: Aakash Mahalingam, Vinesh Kumar Gande, Aman Chadha, Vinija Jain, Divya Chaudhary  

**Link**: [PDF](https://arxiv.org/pdf/2412.15443)  

**Abstract**: Retrieval-Augmented Generation (RAG) systems have become pivotal in leveraging vast corpora to generate informed and contextually relevant responses, notably reducing hallucinations in Large Language Models. Despite significant advancements, these systems struggle to efficiently process and retrieve information from large datasets while maintaining a comprehensive understanding of the context. This paper introduces SKETCH, a novel methodology that enhances the RAG retrieval process by integrating semantic text retrieval with knowledge graphs, thereby merging structured and unstructured data for a more holistic comprehension. SKETCH, demonstrates substantial improvements in retrieval performance and maintains superior context integrity compared to traditional methods. Evaluated across four diverse datasets: QuALITY, QASPER, NarrativeQA, and Italian Cuisine-SKETCH consistently outperforms baseline approaches on key RAGAS metrics such as answer_relevancy, faithfulness, context_precision and context_recall. Notably, on the Italian Cuisine dataset, SKETCH achieved an answer relevancy of 0.94 and a context precision of 0.99, representing the highest performance across all evaluated metrics. These results highlight SKETCH's capability in delivering more accurate and contextually relevant responses, setting new benchmarks for future retrieval systems. 

**Abstract (ZH)**: 检索增强生成（RAG）系统已经被证明是利用大量语料库生成有信息量且上下文相关回答的关键工具，显著减少了大型语言模型中的幻觉现象。尽管取得了显著的进展，这些系统在高效处理和从大型数据集中检索信息的同时保持全面的上下文理解方面仍存在挑战。本文提出了一种名为SKETCH的新方法，通过将语义文本检索与知识图谱结合，增强了RAG的检索过程，从而将结构化数据和非结构化数据结合起来，提供了更全面的理解。SKETCH在检索性能上表现出显著提升，并在保持上下文完整性方面优于传统方法。SKETCH在QuALITY、QASPER、NarrativeQA和意大利菜谱这四个不同数据集上的表现均超过了基准方法，在关键的RAGAS指标（如答案相关性、忠实性、上下文精确度和上下文召回率）上均表现出色。特别是在意大利菜谱数据集上，SKETCH达到了0.94的答案相关性和0.99的上下文精确度，这些指标在整个评估中均达到了最高性能。这些结果突显了SKETCH在提供更准确且上下文相关的回答方面的能力，为未来的检索系统设定了新的基准。 

---
# Systematic Evaluation of Long-Context LLMs on Financial Concepts 

**Title (ZH)**: 对金融概念进行系统评估的长期上下文语言模型 

**Authors**: Lavanya Gupta, Saket Sharma, Yiyun Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2412.15386)  

**Abstract**: Long-context large language models (LC LLMs) promise to increase reliability of LLMs in real-world tasks requiring processing and understanding of long input documents. However, this ability of LC LLMs to reliably utilize their growing context windows remains under investigation. In this work, we evaluate the performance of state-of-the-art GPT-4 suite of LC LLMs in solving a series of progressively challenging tasks, as a function of factors such as context length, task difficulty, and position of key information by creating a real world financial news dataset. Our findings indicate that LC LLMs exhibit brittleness at longer context lengths even for simple tasks, with performance deteriorating sharply as task complexity increases. At longer context lengths, these state-of-the-art models experience catastrophic failures in instruction following resulting in degenerate outputs. Our prompt ablations also reveal unfortunate continued sensitivity to both the placement of the task instruction in the context window as well as minor markdown formatting. Finally, we advocate for more rigorous evaluation of LC LLMs by employing holistic metrics such as F1 (rather than recall) and reporting confidence intervals, thereby ensuring robust and conclusive findings. 

**Abstract (ZH)**: 长上下文大规模语言模型（LC LLMs）有望在需要处理和理解长输入文档的实际任务中提高大语言模型的可靠性。然而，LC LLMs在利用其不断增长的上下文窗口方面能否可靠地维持这一能力尚未得到充分研究。在这项工作中，我们通过创建一个实际世界金融新闻数据集，评估了最先进的GPT-4系列长上下文语言模型在解决一系列逐步复杂的任务方面的性能，这些任务与上下文长度、任务难度和关键信息的位置等因素相关。我们的研究结果表明，即使在简单任务中，LC LLMs在较长的上下文长度下也表现出脆弱性，随着任务复杂性的增加，性能急剧下降。在较长的上下文长度下，这些最先进的模型在指令遵循方面经历了灾难性失败，导致输出退化。我们还通过对提示的消融实验发现，模型对上下文窗口中任务指令的位置以及轻微的Markdown格式化变化仍存在不幸的敏感性。最后，我们主张通过使用综合指标如F1（而不是召回率）并报告置信区间来更严格地评估LC LLMs，从而确保稳健且明确的研究结果。 

---
# Automatic Extraction of Metaphoric Analogies from Literary Texts: Task Formulation, Dataset Construction, and Evaluation 

**Title (ZH)**: 自动提取文学文本中的隐喻类比：任务表述、数据集构建与评估 

**Authors**: Joanne Boisson, Zara Siddique, Hsuvas Borkakoty, Dimosthenis Antypas, Luis Espinosa Anke, Jose Camacho-Collados  

**Link**: [PDF](https://arxiv.org/pdf/2412.15375)  

**Abstract**: Extracting metaphors and analogies from free text requires high-level reasoning abilities such as abstraction and language understanding. Our study focuses on the extraction of the concepts that form metaphoric analogies in literary texts. To this end, we construct a novel dataset in this domain with the help of domain experts. We compare the out-of-the-box ability of recent large language models (LLMs) to structure metaphoric mappings from fragments of texts containing proportional analogies. The models are further evaluated on the generation of implicit elements of the analogy, which are indirectly suggested in the texts and inferred by human readers. The competitive results obtained by LLMs in our experiments are encouraging and open up new avenues such as automatically extracting analogies and metaphors from text instead of investing resources in domain experts to manually label data. 

**Abstract (ZH)**: 从自由文本中提取隐喻和类比需要高级推理能力，如抽象和语言理解。本研究重点关注文学文本中构成隐喻类比的概念提取。为此，我们在专家的帮助下构建了一个新的数据集。我们对比了近期大语言模型（LLMs）直接从包含比例类比的文本片段中结构化隐喻映射的能力。进一步地，我们评估了这些模型生成类比中隐含元素的能力，这些隐含元素在文本中间接暗示并需要人类读者进行推断。我们在实验中获得的具有竞争力的结果令人鼓舞，这为自动从文本中提取隐喻和类比开辟了新的途径，而不是投入资源请领域专家手动标注数据。 

---
# Decade of Natural Language Processing in Chronic Pain: A Systematic Review 

**Title (ZH)**: 近十年自然语言处理在慢性疼痛领域中的研究：一项系统评价 

**Authors**: Swati Rajwal  

**Link**: [PDF](https://arxiv.org/pdf/2412.15360)  

**Abstract**: In recent years, the intersection of Natural Language Processing (NLP) and public health has opened innovative pathways for investigating various domains, including chronic pain in textual datasets. Despite the promise of NLP in chronic pain, the literature is dispersed across various disciplines, and there is a need to consolidate existing knowledge, identify knowledge gaps in the literature, and inform future research directions in this emerging field. This review aims to investigate the state of the research on NLP-based interventions designed for chronic pain research. A search strategy was formulated and executed across PubMed, Web of Science, IEEE Xplore, Scopus, and ACL Anthology to find studies published in English between 2014 and 2024. After screening 132 papers, 26 studies were included in the final review. Key findings from this review underscore the significant potential of NLP techniques to address pressing challenges in chronic pain research. The past 10 years in this field have showcased the utilization of advanced methods (transformers like RoBERTa and BERT) achieving high-performance metrics (e.g., F1>0.8) in classification tasks, while unsupervised approaches like Latent Dirichlet Allocation (LDA) and k-means clustering have proven effective for exploratory analyses. Results also reveal persistent challenges such as limited dataset diversity, inadequate sample sizes, and insufficient representation of underrepresented populations. Future research studies should explore multimodal data validation systems, context-aware mechanistic modeling, and the development of standardized evaluation metrics to enhance reproducibility and equity in chronic pain research. 

**Abstract (ZH)**: 近年来，自然语言处理（NLP）与公共卫生的交叉研究为慢性疼痛等众多领域提供了创新的研究途径。尽管NLP在慢性疼痛研究中展现出巨大潜力，但相关文献分散在多个学科之中，仍需整合现有知识、识别文献中的知识空白，并为这一新兴领域的未来研究方向提供建议。本综述旨在探讨基于NLP的干预措施在慢性疼痛研究中的现状。通过在PubMed、Web of Science、IEEE Xplore、Scopus和ACL Anthology等数据库中制定并执行检索策略，我们找到了2014年至2024年间发表的132篇相关研究论文。最终共纳入26篇研究进行分析。本综述的关键发现强调了NLP技术在解决慢性疼痛研究中紧迫问题方面的巨大潜力。过去十年间，该领域的研究表明，使用先进的方法（如RoBERTa和BERT）在分类任务中取得了高精度（例如F1>0.8），而无监督方法（如潜在狄利克雷分配模型LDA和K均值聚类）在探索性分析中也表现出有效性。研究结果还揭示了持续存在的挑战，例如数据集多样性不足、样本大小不足以及代表性不足群体的不足。未来的研究应探索多模态数据验证系统、上下文感知的机制模型以及标准化评估指标的开发，以提高慢性疼痛研究的可重复性和公平性。 

---
# Eliciting Causal Abilities in Large Language Models for Reasoning Tasks 

**Title (ZH)**: 在推理任务中激发大型语言模型的因果能力 

**Authors**: Yajing Wang, Zongwei Luo, Jingzhe Wang, Zhanke Zhou, Yongqiang Chen, Bo Han  

**Link**: [PDF](https://arxiv.org/pdf/2412.15314)  

**Abstract**: Prompt optimization automatically refines prompting expressions, unlocking the full potential of LLMs in downstream tasks. However, current prompt optimization methods are costly to train and lack sufficient interpretability. This paper proposes enhancing LLMs' reasoning performance by eliciting their causal inference ability from prompting instructions to correct answers. Specifically, we introduce the Self-Causal Instruction Enhancement (SCIE) method, which enables LLMs to generate high-quality, low-quantity observational data, then estimates the causal effect based on these data, and ultimately generates instructions with the optimized causal effect. In SCIE, the instructions are treated as the treatment, and textual features are used to process natural language, establishing causal relationships through treatments between instructions and downstream tasks. Additionally, we propose applying Object-Relational (OR) principles, where the uncovered causal relationships are treated as the inheritable class across task objects, ensuring low-cost reusability. Extensive experiments demonstrate that our method effectively generates instructions that enhance reasoning performance with reduced training cost of prompts, leveraging interpretable textual features to provide actionable insights. 

**Abstract (ZH)**: 本文的内容或标题翻译成中文如下，符合学术规范：

自适应提示优化能够自动精炼提示表达，从而全面释放大型语言模型（LLM）在下游任务中的潜力。然而，当前的提示优化方法训练成本高昂且缺乏足够的解释性。本文提出了一种增强LLM推理性能的方法，即通过从提示指令到正确答案中激发它们的因果推理能力。具体而言，我们引入了自因指令增强（Self-Causal Instruction Enhancement, SCIE）方法，该方法使LLM能够生成高质量的、低数量的观察性数据，然后基于这些数据估计因果效应，并最终生成具有优化因果效应的提示指令。在SCIE中，指令被视为治疗手段，文本特征被用于处理自然语言，建立指令与下游任务之间的因果关系。此外，我们提出了对象关系（Object-Relational, OR）原则的应用，其中发现的因果关系被视为任务对象之间的可继承类，从而确保低成本的可重用性。广泛的实验证明，我们的方法能够有效地生成增强推理性能的提示指令，且降低了提示训练的成本，并利用可解释的文本特征提供了可操作的见解。 

---
# Conceptual In-Context Learning and Chain of Concepts: Solving Complex Conceptual Problems Using Large Language Models 

**Title (ZH)**: 基于上下文的概念学习与概念链：使用大型语言模型解决复杂的概念问题 

**Authors**: Nishtha N. Vaidya, Thomas Runkler, Thomas Hubauer, Veronika Haderlein-Hoegberg, Maja Mlicic Brandt  

**Link**: [PDF](https://arxiv.org/pdf/2412.15309)  

**Abstract**: Science and engineering problems fall in the category of complex conceptual problems that require specific conceptual information (CI) like math/logic -related know-how, process information, or engineering guidelines to solve them. Large Language Models (LLMs) are promising agents to solve such complex conceptual problems due to their implications in advancing engineering and science tasks like assisted problem-solving. But vanilla LLMs, trained on open-world data, lack the necessary CI. In this work, we specifically explore shallow customization methods (SCMs) of LLMs for solving complex conceptual problems. We propose two novel SCM algorithms for LLM, to augment LLMs with CI and enable LLMs to solve complex conceptual problems: Conceptual In-Context Learning (C-ICL) and Chain of Concepts (CoC). The problem tackled in this paper is generation of proprietary data models in the engineering/industry domain based on conceptual information in data modelling guidelines. We evaluate our algorithms on varied sizes of the OpenAI LLMs against four evaluation metrics related to syntactic and semantic correctness, time and cost incurred. The proposed algorithms perform better than currently popular LLM SCMs like In-context Learning (ICL) and Chain of Thoughts (CoT). It was observed that as compared to CoT, response correctness increased by 30.6% and 29.88% for the new SCMs C-ICL and CoC respectively. Qualitative analysis suggests that the proposed new SCMs activate emergent capabilities in LLMs, previously unobserved in the existing SCMs. They make problem-solving processes more transparent and reduce hallucinations and the tendency of model responses to copy examples from prompts (parroting). 

**Abstract (ZH)**: 科学和工程问题属于需要特定概念信息（CI）的复杂概念问题，这些CI包括数学/逻辑知识、过程信息或工程指导方针等才能解决。大型语言模型（LLMs）由于在辅助问题解决等工程和科学任务上的潜力而有望解决这类复杂概念问题。然而，仅基于开放世界的训练的通用LLMs缺乏必要的CI。在本研究中，我们特别探索了LLMs的浅层定制方法（SCMs）以解决复杂概念问题。我们为LLMs提出了两种新的SCM算法，以增强其所需概念信息并使LLMs能够解决复杂概念问题：概念上下文学习（C-ICL）和概念链（CoC）。

本文所解决的问题是基于数据建模指南中的概念信息生成工程/工业领域的专有数据模型。我们使用四个人工评估指标，包括语法和语义的正确性以及消耗的时间和成本，对各种规模的OpenAI LLMs算法进行了评估。提出的算法在目前流行的LLM SCMs，如上下文学习（ICL）和逐步思考（CoT）方面表现出更优异的结果。相比之下，与CoT相比，新的SCMs C-ICL和CoC的响应正确性分别提高了30.6%和29.88%。定性分析表明，提出的新SCMs激活了LLMs中未观察到的涌现能力。这些新方法使问题解决过程更加透明，并减少了模型响应中的幻觉现象和模仿提示中示例的倾向（鹦鹉学舌）。 

---
# ViFactCheck: A New Benchmark Dataset and Methods for Multi-domain News Fact-Checking in Vietnamese 

**Title (ZH)**: ViFactCheck：一个多领域越南新闻事实核查的新基准数据集和方法 

**Authors**: Tran Thai Hoa, Tran Quang Duy, Khanh Quoc Tran, Kiet Van Nguyen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15308)  

**Abstract**: The rapid spread of information in the digital age highlights the critical need for effective fact-checking tools, particularly for languages with limited resources, such as Vietnamese. In response to this challenge, we introduce ViFactCheck, the first publicly available benchmark dataset designed specifically for Vietnamese fact-checking across multiple online news domains. This dataset contains 7,232 human-annotated pairs of claim-evidence combinations sourced from reputable Vietnamese online news, covering 12 diverse topics. It has been subjected to a meticulous annotation process to ensure high quality and reliability, achieving a Fleiss Kappa inter-annotator agreement score of 0.83. Our evaluation leverages state-of-the-art pre-trained and large language models, employing fine-tuning and prompting techniques to assess performance. Notably, the Gemma model demonstrated superior effectiveness, with an impressive macro F1 score of 89.90%, thereby establishing a new standard for fact-checking benchmarks. This result highlights the robust capabilities of Gemma in accurately identifying and verifying facts in Vietnamese. To further promote advances in fact-checking technology and improve the reliability of digital media, we have made the ViFactCheck dataset, model checkpoints, fact-checking pipelines, and source code freely available on GitHub. This initiative aims to inspire further research and enhance the accuracy of information in low-resource languages. 

**Abstract (ZH)**: 数字时代信息的迅速传播凸显了有效事实核查工具的迫切需求，特别是在资源有限的语言中尤为重要，如越南语。为应对这一挑战，我们介绍了ViFactCheck，这是首个专为越南语事实核查设计的公开基准数据集，涵盖多个在线新闻领域。该数据集包含7,232个由人类标注的主张-证据配对，来源于信誉良好的越南语在线新闻，覆盖了12个不同的话题。它经过了严格标注过程，确保了高质量和可靠性，Fleiss Kappa内聚系数达到了0.83。我们的评估利用了最先进的预训练和大型语言模型，通过微调和提示技术评估性能。值得注意的是，Gemma模型表现尤为出色，取得了令人印象深刻的宏F1分数89.90%，从而确立了事实核查基准的新标准。这一结果突显了Gemma在准确识别和验证越南语事实方面的强大能力。为了进一步推动事实核查技术的进步，并提高数字媒体的可靠性，我们已将ViFactCheck数据集、模型检查点、事实核查流水线和源代码全部免费发布在GitHub上。这一举措旨在激发进一步的研究，提升低资源语言信息的准确性。 

---
# Self-Evolution Knowledge Distillation for LLM-based Machine Translation 

**Title (ZH)**: 基于自进化知识精炼的大型语言模型机器翻译方法 

**Authors**: Yuncheng Song, Liang Ding, Changtong Zan, Shujian Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15303)  

**Abstract**: Knowledge distillation (KD) has shown great promise in transferring knowledge from larger teacher models to smaller student models. However, existing KD strategies for large language models often minimize output distributions between student and teacher models indiscriminately for each token. This overlooks the imbalanced nature of tokens and their varying transfer difficulties. In response, we propose a distillation strategy called Self-Evolution KD. The core of this approach involves dynamically integrating teacher distribution and one-hot distribution of ground truth into the student distribution as prior knowledge, which promotes the distillation process. It adjusts the ratio of prior knowledge based on token learning difficulty, fully leveraging the teacher model's potential. Experimental results show our method brings an average improvement of approximately 1.4 SacreBLEU points across four translation directions in the WMT22 test sets. Further analysis indicates that the improvement comes from better knowledge transfer from teachers, confirming our hypothesis. 

**Abstract (ZH)**: 知识蒸馏（Knowledge Distillation, KD）在将大型教师模型的知识传递给较小的学生模型方面展现了巨大的潜力。然而，现有的大型语言模型的KD策略通常会对每个tokens的输出分布不加区分地进行最小化处理，这忽视了tokens之间存在的不平衡性质及其不同的传递难度。为应对这一问题，我们提出了一种名为自我演化KD（Self-Evolution KD）的蒸馏策略。该方法的核心在于动态地将教师模型的分布和ground truth的一핫分布作为先验知识整合进学生模型中，从而促进蒸馏过程。该方法根据tokens的学习难度调整先验知识的比例，充分发挥了教师模型的潜力。实验结果表明，该方法在WMT22测试集中四个翻译方向上平均提升了约1.4个SacreBLEU点。进一步的分析表明，这种改进来自于更好的知识传递，从而验证了我们的假设。 

---
# LAMA-UT: Language Agnostic Multilingual ASR through Orthography Unification and Language-Specific Transliteration 

**Title (ZH)**: LAMA-UT：通过拼写统一和语言特定的转写实现语言无关的多语言ASR 

**Authors**: Sangmin Lee, Woo-Jin Chung Hong-Goo Kang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15299)  

**Abstract**: Building a universal multilingual automatic speech recognition (ASR) model that performs equitably across languages has long been a challenge due to its inherent difficulties. To address this task we introduce a Language-Agnostic Multilingual ASR pipeline through orthography Unification and language-specific Transliteration (LAMA-UT). LAMA-UT operates without any language-specific modules while matching the performance of state-of-the-art models trained on a minimal amount of data. Our pipeline consists of two key steps. First, we utilize a universal transcription generator to unify orthographic features into Romanized form and capture common phonetic characteristics across diverse languages. Second, we utilize a universal converter to transform these universal transcriptions into language-specific ones. In experiments, we demonstrate the effectiveness of our proposed method leveraging universal transcriptions for massively multilingual ASR. Our pipeline achieves a relative error reduction rate of 45% when compared to Whisper and performs comparably to MMS, despite being trained on only 0.1% of Whisper's training data. Furthermore, our pipeline does not rely on any language-specific modules. However, it performs on par with zero-shot ASR approaches which utilize additional language-specific lexicons and language models. We expect this framework to serve as a cornerstone for flexible multilingual ASR systems that are generalizable even to unseen languages. 

**Abstract (ZH)**: 构建一种在多种语言上表现公平的通用多语言自动语音识别（ASR）模型一直是一个挑战，这主要是由于其内在的困难。为了解决这一任务，我们引入了一种基于拼写统一和语言特定转写（LAMA-UT）的无语言依赖多语言ASR管道。LAMA-UT 在没有使用任何语言特定模块的情况下，能够匹配最先进的模型在极少量数据上的表现。我们的管道包含两个关键步骤。首先，我们使用一种通用的转录生成器将拼写特征统一为罗马化形式，并捕捉不同语言中的共同音素特征。其次，我们使用一种通用转换器将这些通用转录转换为特定语言的转录。在实验中，我们展示了一种利用通用转录的方法对大规模多语言ASR的有效性。我们的管道在与Whisper相比，相对错误率减少了45%，且训练数据仅为Whisper的0.1%的情况下，表现与MMS相当。此外，我们的管道不需要任何语言特定模块。尽管如此，其表现与利用额外语言词典和语言模型的零样本ASR方法相当。我们期望这一框架能够成为灵活多语言ASR系统的基础，即使对未见过的语言也具有推广性。 

---
# A Comparative Study of DSPy Teleprompter Algorithms for Aligning Large Language Models Evaluation Metrics to Human Evaluation 

**Title (ZH)**: 针对大型语言模型评估指标与人工评估对齐的 DSPy 电子提词器算法比较研究 

**Authors**: Bhaskarjit Sarmah, Kriti Dutta, Anna Grigoryan, Sachin Tiwari, Stefano Pasquali, Dhagash Mehta  

**Link**: [PDF](https://arxiv.org/pdf/2412.15298)  

**Abstract**: We argue that the Declarative Self-improving Python (DSPy) optimizers are a way to align the large language model (LLM) prompts and their evaluations to the human annotations. We present a comparative analysis of five teleprompter algorithms, namely, Cooperative Prompt Optimization (COPRO), Multi-Stage Instruction Prompt Optimization (MIPRO), BootstrapFewShot, BootstrapFewShot with Optuna, and K-Nearest Neighbor Few Shot, within the DSPy framework with respect to their ability to align with human evaluations. As a concrete example, we focus on optimizing the prompt to align hallucination detection (using LLM as a judge) to human annotated ground truth labels for a publicly available benchmark dataset. Our experiments demonstrate that optimized prompts can outperform various benchmark methods to detect hallucination, and certain telemprompters outperform the others in at least these experiments. 

**Abstract (ZH)**: 我们认为，声明式自我优化Python（DSPy）优化器是一种使大型语言模型（LLM）提示及其评估与人类注释相一致的方法。我们在这一体系结构（DSPy框架）下，对五种对话提示算法进行了比较分析，包括合作性提示优化（COPRO）、多阶段指令提示优化（MIPRO）、BootstrapFewShot、基于Optuna的BootstrapFewShot以及K近邻Few Shot，以评估它们在与人类评价相一致的能力。以具体实例为例，我们专注于优化提示，使其在使用LLM作为评估者的情况下，对幻觉检测（幻觉检测结果由人类标注的 Ground Truth 标签提供参考）与公共基准数据集进行对齐。我们的实验表明，优化后的提示可以超越多种基准方法，用于检测幻觉，并且某些对话提示器在这次实验中表现优于其他方法。 

---
# Confidence in the Reasoning of Large Language Models 

**Title (ZH)**: 大型语言模型推理的置信度 

**Authors**: Yudi Pawitan, Chris Holmes  

**Link**: [PDF](https://arxiv.org/pdf/2412.15296)  

**Abstract**: There is a growing literature on reasoning by large language models (LLMs), but the discussion on the uncertainty in their responses is still lacking. Our aim is to assess the extent of confidence that LLMs have in their answers and how it correlates with accuracy. Confidence is measured (i) qualitatively in terms of persistence in keeping their answer when prompted to reconsider, and (ii) quantitatively in terms of self-reported confidence score. We investigate the performance of three LLMs -- GPT4o, GPT4-turbo and Mistral -- on two benchmark sets of questions on causal judgement and formal fallacies and a set of probability and statistical puzzles and paradoxes. Although the LLMs show significantly better performance than random guessing, there is a wide variability in their tendency to change their initial answers. There is a positive correlation between qualitative confidence and accuracy, but the overall accuracy for the second answer is often worse than for the first answer. There is a strong tendency to overstate the self-reported confidence score. Confidence is only partially explained by the underlying token-level probability. The material effects of prompting on qualitative confidence and the strong tendency for overconfidence indicate that current LLMs do not have any internally coherent sense of confidence. 

**Abstract (ZH)**: 关于大型语言模型（LLMs）的推理研究正在逐步增多，但对于其回答时的不确定性讨论仍然不足。本研究旨在评估LLMs对其答案的信心程度及其与准确性的关联。信心的度量方法包括：（i）定性方面，即在被要求重新考虑时坚持其答案的坚持程度；（ii）定量方面，即自我报告的信心分数。我们对三种LLM——GPT4o、GPT4-turbo和Mistral——在因果判断和逻辑谬误、概率与统计悖论两套基准问题集上的表现进行了研究。尽管LLMs的表现明显优于随机猜测，但在更改初始答案的倾向上存在显著差异。定性信心与准确性之间存在正相关，但一般情况下，第二次答案的总体准确性往往低于第一次答案。自我报告的信心评分存在显著的夸大倾向。信心仅部分由底层标记级概率解释。在定性信心方面的提示效应以及过度自信的倾向表明，当前的LLMs并没有任何内在一致的信心感。 

---
# A Large-scale Empirical Study on Large Language Models for Election Prediction 

**Title (ZH)**: 大规模实证研究：大型语言模型在选举预测中的应用 

**Authors**: Chenxiao Yu, Zhaotian Weng, Yuangang Li, Zheng Li, Xiyang Hu, Yue Zhao  

**Link**: [PDF](https://arxiv.org/pdf/2412.15291)  

**Abstract**: Can Large Language Models (LLMs) accurately predict election outcomes? While LLMs have demonstrated impressive performance in healthcare, legal analysis, and creative applications, their capabilities in election forecasting remain uncertain. Notably, election prediction poses unique challenges: limited voter-level data, evolving political contexts, and the complexity of modeling human behavior. In the first part of this paper, we explore and introduce a multi-step reasoning framework for election prediction, which systematically integrates demographic, ideological, and time-sensitive factors. Validated on 2016 and 2020 real-world data and extensive synthetic personas, our approach adapts to changing political landscapes, reducing bias and significantly improving predictive accuracy. We further apply our pipeline to the 2024 U.S. presidential election, illustrating its ability to generalize beyond observed historical data. Beyond enhancing accuracy, the second part of the paper provides insights into the broader implications of LLM-based election forecasting. We identify potential political biases embedded in pretrained corpora, examine how demographic patterns can become exaggerated, and suggest strategies for mitigating these issues. Together, this project, a large-scale LLM empirical study, advances the accuracy of election predictions and establishes directions for more balanced, transparent, and context-aware modeling in political science research and practice. 

**Abstract (ZH)**: 大语言模型（LLMs）能否准确预测选举结果？尽管LLMs在医疗保健、法律分析和创意应用方面表现出色，但在选举预测领域的表现仍有待验证。值得注意的是，选举预测面临独特的挑战：选民层面数据有限，政治环境不断变化以及建模人类行为的复杂性。在本文的第一部分中，我们探讨并引入了一种多步推理框架，系统地整合了人口统计学、意识形态和时间敏感因素。我们通过2016年和2020年的实际数据以及广泛的合成人物验证了该方法，使其能够适应不断变化的政治格局，减少偏差并显著提高预测准确性。我们进一步将该框架应用于2024年美国总统选举，展示了其超越既往历史数据的能力。除了提高预测准确性，本文第二部分还探讨了基于LLM的选举预测在更广泛层面的意义。我们识别了预训练语料库中潜在的政治偏见，分析了人口模式如何被放大，并提出了缓解这些问题的策略。该项目是一个大规模的LLM实证研究，推动了选举预测的准确性，并为政治科学研究与实践中更均衡、透明、情境感知的建模方向指明了方向。 

---
# Inference-Aware Fine-Tuning for Best-of-N Sampling in Large Language Models 

**Title (ZH)**: 基于推理的精调以实现大型语言模型中“最佳-n”采样 

**Authors**: Yinlam Chow, Guy Tennenholtz, Izzeddin Gur, Vincent Zhuang, Bo Dai, Sridhar Thiagarajan, Craig Boutilier, Rishabh Agarwal, Aviral Kumar, Aleksandra Faust  

**Link**: [PDF](https://arxiv.org/pdf/2412.15287)  

**Abstract**: Recent studies have indicated that effectively utilizing inference-time compute is crucial for attaining better performance from large language models (LLMs). In this work, we propose a novel inference-aware fine-tuning paradigm, in which the model is fine-tuned in a manner that directly optimizes the performance of the inference-time strategy. We study this paradigm using the simple yet effective Best-of-N (BoN) inference strategy, in which a verifier selects the best out of a set of LLM-generated responses. We devise the first imitation learning and reinforcement learning~(RL) methods for BoN-aware fine-tuning, overcoming the challenging, non-differentiable argmax operator within BoN. We empirically demonstrate that our BoN-aware models implicitly learn a meta-strategy that interleaves best responses with more diverse responses that might be better suited to a test-time input -- a process reminiscent of the exploration-exploitation trade-off in RL. Our experiments demonstrate the effectiveness of BoN-aware fine-tuning in terms of improved performance and inference-time compute. In particular, we show that our methods improve the Bo32 performance of Gemma 2B on Hendrycks MATH from 26.8% to 30.8%, and pass@32 from 60.0% to 67.0%, as well as the pass@16 on HumanEval from 61.6% to 67.1%. 

**Abstract (ZH)**: 近年来的研究表明，在推理时有效利用计算资源对于提高大型语言模型（LLMs）的性能至关重要。在此项工作中，我们提出了一种新颖的推理感知微调范式，在该范式中，模型以直接优化推理时策略性能的方式进行微调。我们使用一种简单而有效的“最佳中的N个”（BoN）推理策略进行研究，在该策略中，验证器从一组LLM生成的响应中选择最佳者。我们首次为BoN意识微调设计了模仿学习和强化学习（RL）方法，克服了BoN内部难以处理的非可微分的argmax操作。我们的实证研究表明，我们的BoN意识模型隐式学习了一种元策略，该策略将最佳响应与可能更适合测试输入的更具有多样性的响应交错使用——这一过程类似于RL中的探索-利用权衡。我们的实验表明，BoN意识微调在提高性能和推理计算资源利用方面是有效的。特别是，我们的方法将Gemma 2B在Hendrycks MATH上的Bo32性能从26.8%提高到30.8%，pass@32从60.0%提高到67.0%，并且在HumanEval上的pass@16从61.6%提高到67.1%。 

---
# Maximize Your Data's Potential: Enhancing LLM Accuracy with Two-Phase Pretraining 

**Title (ZH)**: 最大化数据的潜力：通过两阶段预训练提升大语言模型的准确性 

**Authors**: Steven Feng, Shrimai Prabhumoye, Kezhi Kong, Dan Su, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro  

**Link**: [PDF](https://arxiv.org/pdf/2412.15285)  

**Abstract**: Pretraining large language models effectively requires strategic data selection, blending and ordering. However, key details about data mixtures especially their scalability to longer token horizons and larger model sizes remain underexplored due to limited disclosure by model developers. To address this, we formalize the concept of two-phase pretraining and conduct an extensive systematic study on how to select and mix data to maximize model accuracies for the two phases. Our findings illustrate that a two-phase approach for pretraining outperforms random data ordering and natural distribution of tokens by 3.4% and 17% on average accuracies. We provide in-depth guidance on crafting optimal blends based on quality of the data source and the number of epochs to be seen. We propose to design blends using downsampled data at a smaller scale of 1T tokens and then demonstrate effective scaling of our approach to larger token horizon of 15T tokens and larger model size of 25B model size. These insights provide a series of steps practitioners can follow to design and scale their data blends. 

**Abstract (ZH)**: 大规模语言模型的有效预训练需要战略性的数据选择、融合和排序。然而，尤其是关于数据混合在更长的令牌窗口和更大模型尺寸中的可扩展性，相关细节仍然缺乏探索，这主要是由于模型开发者披露有限。为了解决这个问题，我们形式化了两阶段预训练的概念，并进行了广泛系统的研究，探讨如何选择和混合数据以最大化两个阶段的模型准确性。我们的研究结果表明，两阶段预训练方法在平均准确率上分别比随机数据排序和自然的令牌分布高出3.4%和17%。我们提供了关于如何根据数据源的质量和所见的迭代次数来精心设计最优混合方式的详细指导。我们建议使用1万亿令牌的小规模下采样数据来设计混合，并展示了如何有效地将我们的方法扩展到15万亿令牌的更长令牌窗口和250亿参数的更大模型尺寸。这些见解为实践者提供了一系列步骤，以便设计和扩展其数据混合。 

---
# Channel Merging: Preserving Specialization for Merged Experts 

**Title (ZH)**: 通道合并：保留合并专家专业化程度 

**Authors**: Mingyang Zhang, Jing Liu, Ganggui Ding, Xinyi Yu, Linlin Ou, Bohan Zhuang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15283)  

**Abstract**: Lately, the practice of utilizing task-specific fine-tuning has been implemented to improve the performance of large language models (LLM) in subsequent tasks. Through the integration of diverse LLMs, the overall competency of LLMs is significantly boosted. Nevertheless, traditional ensemble methods are notably memory-intensive, necessitating the simultaneous loading of all specialized models into GPU memory. To address the inefficiency, model merging strategies have emerged, merging all LLMs into one model to reduce the memory footprint during inference. Despite these advances, model merging often leads to parameter conflicts and performance decline as the number of experts increases. Previous methods to mitigate these conflicts include post-pruning and partial merging. However, both approaches have limitations, particularly in terms of performance and storage efficiency when merged experts increase. To address these challenges, we introduce Channel Merging, a novel strategy designed to minimize parameter conflicts while enhancing storage efficiency. This method clusters and merges channel parameters based on their similarity to form several groups offline. By ensuring that only highly similar parameters are merged within each group, it significantly reduces parameter conflicts. During inference, we can instantly look up the expert parameters from the merged groups, preserving specialized knowledge. Our experiments demonstrate that Channel Merging consistently delivers high performance, matching unmerged models in tasks like English and Chinese reasoning, mathematical reasoning, and code generation. Moreover, it obtains results comparable to model ensemble with just 53% parameters when used with a task-specific router. 

**Abstract (ZH)**: 近年来，利用任务特定微调的方法已被应用于提高大规模语言模型（LLM）在后续任务中的性能。通过整合多种不同的LLM，整体语言模型的竞争力得到了显著提升。然而，传统的集成方法在内存使用上非常密集，需要同时将所有专业模型加载到GPU内存中。为了解决这种方法的效率问题，已经出现了模型合并策略，即将所有LLM合并为一个模型以减少推理过程中的内存占用。尽管取得了进展，但随着专家数量的增加，模型合并往往会导致参数冲突和性能下降。前人的方法包括后剪枝和部分合并来缓解这些冲突，但两者在合并专家数量增加时，在性能和存储效率方面都存在局限性。为了解决这些问题，我们提出了通道合并（Channel Merging）这一新型策略，旨在同时最小化参数冲突和提高存储效率。这种方法根据参数间的相似性在离线阶段对通道参数进行分组和合并。通过确保在每个组内只合并高度相似的参数，它可以显著减少参数冲突。在推理过程中，我们可以从合并后的组中即时查找专家参数，保留特定的知识。我们的实验表明，通道合并能够在英语和中文推理、数学推理及代码生成等任务中持续提供高性能，与未合并模型相当。而且，当与任务特定路由器结合使用时，该方法仅需合并模型参数的53%，即可获得与模型集成相当的结果。 

---
# A Systematic Examination of Preference Learning through the Lens of Instruction-Following 

**Title (ZH)**: 通过遵循指令的角度对偏好学习进行系统性考察 

**Authors**: Joongwon Kim, Anirudh Goyal, Aston Zhang, Bo Xiong, Rui Hou, Melanie Kambadur, Dhruv Mahajan, Hannaneh Hajishirzi, Liang Tan  

**Link**: [PDF](https://arxiv.org/pdf/2412.15282)  

**Abstract**: Preference learning is a widely adopted post-training technique that aligns large language models (LLMs) to human preferences and improves specific downstream task capabilities. In this work we systematically investigate how specific attributes of preference datasets affect the alignment and downstream performance of LLMs in instruction-following tasks. We use a novel synthetic data generation pipeline to generate 48,000 unique instruction-following prompts with combinations of 23 verifiable constraints that enable fine-grained and automated quality assessments of model responses. With our synthetic prompts, we use two preference dataset curation methods - rejection sampling (RS) and Monte Carlo Tree Search (MCTS) - to obtain pairs of (chosen, rejected) responses. Then, we perform experiments investigating the effects of (1) the presence of shared prefixes between the chosen and rejected responses, (2) the contrast and quality of the chosen, rejected responses and (3) the complexity of the training prompts. Our experiments reveal that shared prefixes in preference pairs, as generated by MCTS, provide marginal but consistent improvements and greater stability across challenging training configurations. High-contrast preference pairs generally outperform low-contrast pairs; however, combining both often yields the best performance by balancing diversity and learning efficiency. Additionally, training on prompts of moderate difficulty leads to better generalization across tasks, even for more complex evaluation scenarios, compared to overly challenging prompts. Our findings provide actionable insights into optimizing preference data curation for instruction-following tasks, offering a scalable and effective framework for enhancing LLM training and alignment. 

**Abstract (ZH)**: 偏好学习是一种广泛采用的后训练技术，用于将大型语言模型（LLMs）与人类偏好对齐，并提高特定下游任务的能力。在本文中，我们系统性地研究了偏好数据集的具体属性如何影响LLMs在指令遵循任务中的对齐和下游性能。我们使用一种新颖的合成数据生成管道生成了48,000个独特的指令遵循提示，这些提示结合了23种可验证约束，从而能够对模型响应进行精细和自动的质量评估。使用我们的合成提示，我们采用了两种偏好数据集编纂方法——拒绝抽样（RS）和蒙特卡洛树搜索（MCTS）——来获得（选择，拒绝）响应对。然后，我们进行了一系列实验，以探讨以下因素的影响：（1）选择和拒绝响应之间的共享前缀；（2）选择和拒绝响应的对比度和质量；（3）训练提示的复杂性。我们的实验结果显示，由MCTS生成的偏好对中的共享前缀提供了微小但一致的改进，并且在具有挑战性的训练配置中提供了更大的稳定性。高对比度的偏好对通常优于低对比度的偏好对；然而，将两者结合使用往往能够通过平衡多样性和学习效率来获得最佳性能。此外，使用中等难度的提示进行训练能够在任务中获得更好的泛化能力，即使在更复杂的评估场景中也是如此，而使用过于具有挑战性的提示效果较差。我们的发现为优化指令遵循任务中的偏好数据编纂提供了可操作的见解，并提供了一种可扩展且有效的框架，用于增强LLM训练和对齐。 

---
# Context-DPO: Aligning Language Models for Context-Faithfulness 

**Title (ZH)**: Context-DPO：调整语言模型以确保上下文一致性 

**Authors**: Baolong Bi, Shaohan Huang, Yiwei Wang, Tianchi Yang, Zihan Zhang, Haizhen Huang, Lingrui Mei, Junfeng Fang, Zehao Li, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Shenghua Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15280)  

**Abstract**: Reliable responses from large language models (LLMs) require adherence to user instructions and retrieved information. While alignment techniques help LLMs align with human intentions and values, improving context-faithfulness through alignment remains underexplored. To address this, we propose $\textbf{Context-DPO}$, the first alignment method specifically designed to enhance LLMs' context-faithfulness. We introduce $\textbf{ConFiQA}$, a benchmark that simulates Retrieval-Augmented Generation (RAG) scenarios with knowledge conflicts to evaluate context-faithfulness. By leveraging faithful and stubborn responses to questions with provided context from ConFiQA, our Context-DPO aligns LLMs through direct preference optimization. Extensive experiments demonstrate that our Context-DPO significantly improves context-faithfulness, achieving 35% to 280% improvements on popular open-source models. Further analysis demonstrates that Context-DPO preserves LLMs' generative capabilities while providing interpretable insights into context utilization. Our code and data are released at this https URL 

**Abstract (ZH)**: 大型语言模型（LLMs）可靠的响应需要遵循用户指令和检索到的信息。尽管对齐技术有助于使LLMs与人类意图和价值观保持一致，通过对齐提高上下文忠实度仍然未被充分探索。为解决这一问题，我们提出了**Context-DPO**，这是第一个专门设计用于提高LLMs上下文忠实度的对齐方法。我们引入了**ConFiQA**，这是一个基准测试，模拟了包含知识冲突的检索增强生成（RAG）场景，用于评估上下文忠实度。通过利用ConFiQA提供的上下文环境中忠实且固执的回答，我们的Context-DPO通过对直接偏好优化进行对齐。广泛实验表明，我们的Context-DPO显著提高了上下文忠实度，在流行开源模型上取得了35%至280%的提升。进一步的分析表明，Context-DPO保留了LLMs的生成能力，并提供了关于上下文利用的可解释性洞察。我们的代码和数据可在以下链接中获取：this https URL 

---
# PLPP: Prompt Learning with Perplexity Is Self-Distillation for Vision-Language Models 

**Title (ZH)**: PLPP：基于 perplexity 的自蒸馏(prompt 学习)方法用于视觉-语言模型 

**Authors**: Biao Liu, Wenyi Fang, Xiaoyu Wu, Yang Zheng, Zheng Hu, Bo Yuan  

**Link**: [PDF](https://arxiv.org/pdf/2412.15277)  

**Abstract**: Pre-trained Vision-Language (VL) models such as CLIP have demonstrated their excellent performance across numerous downstream tasks. A recent method, Context Optimization (CoOp), further improves the performance of VL models on downstream tasks by introducing prompt learning. CoOp optimizes a set of learnable vectors, aka prompt, and freezes the whole CLIP model. However, relying solely on CLIP loss to fine-tune prompts can lead to models that are prone to overfitting on downstream task. To address this issue, we propose a plug-in prompt-regularization method called PLPP (Prompt Learning with PerPlexity), which use perplexity loss to regularize prompt learning. PLPP designs a two-step operation to compute the perplexity for prompts: (a) calculating cosine similarity between the weight of the embedding layer and prompts to get labels, (b) introducing a language model (LM) head that requires no training behind text encoder to output word probability distribution. Meanwhile, we unveil that the essence of PLPP is inherently a form of self-distillation. To further prevent overfitting as well as to reduce the additional computation introduced by PLPP, we turn the hard label to soft label and choose top-$k$ values for calculating the perplexity loss. For accelerating model convergence, we introduce mutual self-distillation learning, that is perplexity and inverted perplexity loss. The experiments conducted on four classification tasks indicate that PLPP exhibits superior performance compared to existing methods. 

**Abstract (ZH)**: 预训练的视觉-语言（VL）模型，如CLIP，在众多下游任务中展现了卓越的性能。最近提出的一种方法，Context Optimization (CoOp)，通过引入提示学习进一步提高了VL模型在下游任务中的性能。CoOp 优化了一组可学习向量，即提示，并冻结整个CLIP模型。然而，仅依赖CLIP损失来微调提示可能会导致模型在下游任务上容易过拟合。为解决这一问题，我们提出了一种名为PLPP（提示学习中使用困惑度正则化）的插件提示正则化方法，该方法使用困惑度损失来正则化提示学习。PLPP 设计了两步操作来计算提示的困惑度：(a) 计算嵌入层权重与提示之间的余弦相似性以获取标签，(b) 引入一个无需对文本编码器进行训练即可输出词的概率分布的语言模型（LM）头。同时，我们揭示了PLPP 的本质其实是自我蒸馏的一种形式。为了进一步防止过拟合并减少PLPP 引入的额外计算，我们将硬标签转换为软标签，并选择前K值来计算困惑度损失。为了加速模型的收敛，我们引入了相互自我蒸馏学习，即困惑度损失和逆困惑度损失。在四个分类任务上的实验表明，PLPP 在性能上优于现有方法。 

---
# Memory-Augmented Agent Training for Business Document Understanding 

**Title (ZH)**: 基于记忆增强代理训练的商业文档理解 

**Authors**: Jiale Liu, Yifan Zeng, Malte Højmark-Bertelsen, Marie Normann Gadeberg, Huazheng Wang, Qingyun Wu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15274)  

**Abstract**: Traditional enterprises face significant challenges in processing business documents, where tasks like extracting transport references from invoices remain largely manual despite their crucial role in logistics operations. While Large Language Models offer potential automation, their direct application to specialized business domains often yields unsatisfactory results. We introduce Matrix (Memory-Augmented agent Training through Reasoning and Iterative eXploration), a novel paradigm that enables LLM agents to progressively build domain expertise through experience-driven memory refinement and iterative learning. To validate this approach, we collaborate with one of the world's largest logistics companies to create a dataset of Universal Business Language format invoice documents, focusing on the task of transport reference extraction. Experiments demonstrate that Matrix outperforms prompting a single LLM by 30.3%, vanilla LLM agent by 35.2%. We further analyze the metrics of the optimized systems and observe that the agent system requires less API calls, fewer costs and can analyze longer documents on average. Our methods establish a new approach to transform general-purpose LLMs into specialized business tools through systematic memory enhancement in document processing tasks. 

**Abstract (ZH)**: 传统企业在处理商务文档时面临着显著的挑战，尽管发票中提取运输参考编号等任务在物流运营中至关重要，但这些任务仍然主要依赖人工完成。尽管大型语言模型具备潜在的自动化能力，但直接应用于专门的商业领域时，往往效果不尽如人意。我们提出了一种名为Matrix（记忆增强代理训练通过推理与迭代探索）的新型范式，该范式通过基于经验的记忆精炼和迭代学习，使大型语言模型代理能够逐步构建特定领域的专业知识。为了验证这一方法，我们与世界上最大的物流公司之一合作，创建了一个通用商务语言格式的发票文档数据集，专注于运输参考编号的提取任务。实验结果显示，Matrix在性能上比仅通过提示单个大型语言模型高出30.3%，比原始的大型语言模型代理高出35.2%。我们进一步分析了优化系统的指标，并发现代理系统所需的API调用次数较少、成本更低，并且能够平均分析更长的文档。我们的方法为通过系统性的文档处理任务中增强记忆，将通用型大型语言模型转变为专门的商业工具建立了新的途径。 

---
# SimGRAG: Leveraging Similar Subgraphs for Knowledge Graphs Driven Retrieval-Augmented Generation 

**Title (ZH)**: SimGRAG：利用相似子图的知识图驱动检索增强生成 

**Authors**: Yuzheng Cai, Zhenyue Guo, Yiwen Pei, Wanrui Bian, Weiguo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15272)  

**Abstract**: Recent advancements in large language models (LLMs) have shown impressive versatility across various tasks. To eliminate its hallucinations, retrieval-augmented generation (RAG) has emerged as a powerful approach, leveraging external knowledge sources like knowledge graphs (KGs). In this paper, we study the task of KG-driven RAG and propose a novel Similar Graph Enhanced Retrieval-Augmented Generation (SimGRAG) method. It effectively addresses the challenge of aligning query texts and KG structures through a two-stage process: (1) query-to-pattern, which uses an LLM to transform queries into a desired graph pattern, and (2) pattern-to-subgraph, which quantifies the alignment between the pattern and candidate subgraphs using a graph semantic distance (GSD) metric. We also develop an optimized retrieval algorithm that efficiently identifies the top-$k$ subgraphs within 1-second latency on a 10-million-scale KG. Extensive experiments show that SimGRAG outperforms state-of-the-art KG-driven RAG methods in both question answering and fact verification, offering superior plug-and-play usability and scalability. 

**Abstract (ZH)**: 近年来，大型语言模型（LLMs）在各种任务中展示了令人印象深刻的多功能性。为了解决其自动生成的虚构问题，检索增强生成（RAG）作为一种强大的方法逐渐兴起，利用外部知识源如知识图谱（KGs）。在本文中，我们研究了基于KG的RAG任务，并提出了一种名为SimGRAG（Similar Graph Enhanced Retrieval-Augmented Generation）的新方法。该方法通过两阶段过程有效地解决了查询文本与KG结构对齐的挑战：（1）查询到模式阶段，该阶段使用LLM将查询转换为期望的图模式；（2）模式到子图阶段，该阶段使用图语义距离（GSD）度量来量化模式与候选子图之间的对齐程度。我们还开发了一种优化的检索算法，能够在1秒延迟的条件下从大规模（1000万规模）KG中高效地识别出前k个子图。大规模实验表明，与最先进的基于KG的RAG方法相比，SimGRAG在问答和事实验证方面表现出更优秀的表现，并提供更好的即插即用易用性和可扩展性。 

---
# A MapReduce Approach to Effectively Utilize Long Context Information in Retrieval Augmented Language Models 

**Title (ZH)**: 一种利用检索增强语言模型中长上下文信息的有效MapReduce方法 

**Authors**: Gongbo Zhang, Zihan Xu, Qiao Jin, Fangyi Chen, Yilu Fang, Yi Liu, Justin F. Rousseau, Ziyang Xu, Zhiyong Lu, Chunhua Weng, Yifan Peng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15271)  

**Abstract**: While holding great promise for improving and facilitating healthcare, large language models (LLMs) struggle to produce up-to-date responses on evolving topics due to outdated knowledge or hallucination. Retrieval-augmented generation (RAG) is a pivotal innovation that improves the accuracy and relevance of LLM responses by integrating LLMs with a search engine and external sources of knowledge. However, the quality of RAG responses can be largely impacted by the rank and density of key information in the retrieval results, such as the "lost-in-the-middle" problem. In this work, we aim to improve the robustness and reliability of the RAG workflow in the medical domain. Specifically, we propose a map-reduce strategy, BriefContext, to combat the "lost-in-the-middle" issue without modifying the model weights. We demonstrated the advantage of the workflow with various LLM backbones and on multiple QA datasets. This method promises to improve the safety and reliability of LLMs deployed in healthcare domains. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）在提高和促进医疗服务方面展现出巨大的潜力，它们在处理快速演化的主题时，由于知识陈旧或幻觉（hallucination）而难以提供及时准确的回答。检索增强生成（RAG，Retrieval-Augmented Generation）作为一种关键的创新技术，通过将LLMs与搜索引擎和外部知识源相结合，提高了其回答的准确性和相关性。然而，RAG的回答质量很大程度上受到检索结果中关键信息排名和密度的影响，例如“中间信息丢失”问题。在这项工作中，我们旨在提高医疗领域的RAG工作流的稳健性和可靠性。具体而言，我们提出了一种映射-减少策略（BriefContext），通过这种策略可以在不修改模型权重的情况下应对“中间信息丢失”问题。我们通过多种LLM基础模型和多个QA数据集展示了该方法的优势。该方法有望提高部署在医疗领域的LLMs的安全性和可靠性。 

---
# Baichuan4-Finance Technical Report 

**Title (ZH)**: 《巴 cham4-金融技术报告》

注：这里的“Baichuan4”疑似指的是“巴 cham4”，“巴”可能是对于名称的误输入或特定称谓，若“巴 cham4”并非预设的特定名称，请提供准确名称以便进行更准确的翻译。此外，在实际的学术报告标题中，通常会保持原文名称的准确性，除非该名称在中文中有常用且被广泛接受的翻译或音译版本。 

**Authors**: Hanyu Zhang, Boyu Qiu, Yuhao Feng, Shuqi Li, Qian Ma, Xiyuan Zhang, Qiang Ju, Dong Yan, Jian Xie  

**Link**: [PDF](https://arxiv.org/pdf/2412.15270)  

**Abstract**: Large language models (LLMs) have demonstrated strong capabilities in language understanding, generation, and reasoning, yet their potential in finance remains underexplored due to the complexity and specialization of financial knowledge. In this work, we report the development of the Baichuan4-Finance series, including a comprehensive suite of foundational Baichuan4-Finance-Base and an aligned language model Baichuan4-Finance, which are built upon Baichuan4-Turbo base model and tailored for finance domain. Firstly, we have dedicated significant effort to building a detailed pipeline for improving data quality. Moreover, in the continual pre-training phase, we propose a novel domain self-constraint training strategy, which enables Baichuan4-Finance-Base to acquire financial knowledge without losing general capabilities. After Supervised Fine-tuning and Reinforcement Learning from Human Feedback and AI Feedback, the chat model Baichuan4-Finance is able to tackle various financial certification questions and real-world scenario applications. We evaluate Baichuan4-Finance on many widely used general datasets and two holistic financial benchmarks. The evaluation results show that Baichuan4-Finance-Base surpasses almost all competitive baselines on financial tasks by significant margins without sacrificing performance on general LLM benchmarks. At the same time, Baichuan4-Finance demonstrates even more impressive performance on financial application scenarios, showcasing its potential to foster community innovation in the financial LLM field. 

**Abstract (ZH)**: 大型语言模型（LLMs）在语言理解和生成、推理方面展现了强大的能力，但由于金融知识的复杂性和专业性，其在金融领域的潜力尚未得到充分发掘。在此项工作中，我们报道了Baichuan4-Finance系列的研发，包括全面的基础模型Baichuan4-Finance-Base和对齐的语言模型Baichuan4-Finance，这些模型基于Baichuan4-Turbo基础模型并针对金融领域进行了定制开发。首先，我们投入了大量精力构建了一个详细的数据质量改进管道。此外，在持续预训练阶段，我们提出了一种新颖的领域自我约束训练策略，使Baichuan4-Finance-Base能够在不丢失通用能力的情况下获得金融知识。经过监督微调和基于人类反馈和AI反馈的强化学习后，对话模型Baichuan4-Finance能够应对各种金融认证问题和现实世界应用场景。我们在多个广泛使用的通用数据集和两个全面的金融基准上评估了Baichuan4-Finance。评估结果表明，Baichuan4-Finance-Base在金融任务上显著超过了几乎所有竞争性 baselines，且在通用LLM基准上没有牺牲性能。同时，Baichuan4-Finance 在金融应用场景中表现出更加出色的能力，展示了其在金融LLM领域促进社区创新的潜力。 

---
# The Reliability Paradox: Exploring How Shortcut Learning Undermines Language Model Calibration 

**Title (ZH)**: 可靠性悖论：探索捷径学习如何损害语言模型的校准 

**Authors**: Geetanjali Bihani, Julia Rayz  

**Link**: [PDF](https://arxiv.org/pdf/2412.15269)  

**Abstract**: The advent of pre-trained language models (PLMs) has enabled significant performance gains in the field of natural language processing. However, recent studies have found PLMs to suffer from miscalibration, indicating a lack of accuracy in the confidence estimates provided by these models. Current evaluation methods for PLM calibration often assume that lower calibration error estimates indicate more reliable predictions. However, fine-tuned PLMs often resort to shortcuts, leading to overconfident predictions that create the illusion of enhanced performance but lack generalizability in their decision rules. The relationship between PLM reliability, as measured by calibration error, and shortcut learning, has not been thoroughly explored thus far. This paper aims to investigate this relationship, studying whether lower calibration error implies reliable decision rules for a language model. Our findings reveal that models with seemingly superior calibration portray higher levels of non-generalizable decision rules. This challenges the prevailing notion that well-calibrated models are inherently reliable. Our study highlights the need to bridge the current gap between language model calibration and generalization objectives, urging the development of comprehensive frameworks to achieve truly robust and reliable language models. 

**Abstract (ZH)**: 预训练语言模型（PLMs）的出现已经在自然语言处理领域实现了显著的性能提升。然而，近期的研究发现PLMs存在校准失准的问题，表明这些模型提供的置信度估计不够准确。当前对PLM校准的评估方法往往假设校准误差越低表示预测越可靠。但是，经过微调的PLMs往往依赖捷径，导致过度自信的预测，虽然这制造了性能提升的幻象，但却缺乏普遍适用的决策规则。目前，关于PLM可靠性（通过校准误差衡量）与捷径学习之间的关系尚未得到充分探讨。本文旨在探讨这一关系，研究低校准误差是否意味着语言模型具有可靠的决策规则。我们的研究发现，看似更优校准的模型实际上在普遍适用的决策规则方面表现得更好。这一发现挑战了校准良好的模型自然可靠的观念。我们的研究强调了在语言模型校准与泛化目标之间建立联系的必要性，呼吁开发全面的框架以实现真正稳健和可靠的语言模型。 

---
# Enhancing LLM-based Hatred and Toxicity Detection with Meta-Toxic Knowledge Graph 

**Title (ZH)**: 基于元毒刺激知识图谱增强基于大规模语言模型的仇恨和毒性检测 

**Authors**: Yibo Zhao, Jiapeng Zhu, Can Xu, Xiang Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.15268)  

**Abstract**: The rapid growth of social media platforms has raised significant concerns regarding online content toxicity. When Large Language Models (LLMs) are used for toxicity detection, two key challenges emerge: 1) the absence of domain-specific toxic knowledge leads to false negatives; 2) the excessive sensitivity of LLMs to toxic speech results in false positives, limiting freedom of speech. To address these issues, we propose a novel method called MetaTox, leveraging graph search on a meta-toxic knowledge graph to enhance hatred and toxicity detection. First, we construct a comprehensive meta-toxic knowledge graph by utilizing LLMs to extract toxic information through a three-step pipeline, with toxic benchmark datasets serving as corpora. Second, we query the graph via retrieval and ranking processes to supplement accurate, relevant toxic knowledge. Extensive experiments and in-depth case studies across multiple datasets demonstrate that our MetaTox significantly decreases the false positive rate while boosting overall toxicity detection performance. Our code will be available soon. 

**Abstract (ZH)**: 社交媒体平台的迅速增长引发了对在线内容毒性的重大关注。当大型语言模型（LLMs）用于检测毒性时，两个关键挑战随之浮现：1）缺乏特定领域的毒信息知识导致假阴性；2）大型语言模型对有毒言论的过度敏感性导致假阳性结果，限制了言论自由。为了解决这些问题，我们提出了一种名为MetaTox的新方法，该方法通过图搜索在元毒信息图上增强仇恨和毒性检测。首先，我们通过利用LLMs以三步流水线来提取毒信息的方式构建了一个全面的元毒信息图，毒信息基准数据集作为语料库。其次，我们通过检索和排序过程查询图，以补充准确且相关的毒信息知识。在多个数据集上进行的广泛实验和深入案例研究表明，我们的MetaTox显著降低了假阳性率，并提升了整体毒性检测性能。我们的代码很快将对外开放。 

---
# On the Structural Memory of LLM Agents 

**Title (ZH)**: 大型语言模型代理的结构性记忆研究 

**Authors**: Ruihong Zeng, Jinyuan Fang, Siwei Liu, Zaiqiao Meng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15266)  

**Abstract**: Memory plays a pivotal role in enabling large language model~(LLM)-based agents to engage in complex and long-term interactions, such as question answering (QA) and dialogue systems. While various memory modules have been proposed for these tasks, the impact of different memory structures across tasks remains insufficiently explored. This paper investigates how memory structures and memory retrieval methods affect the performance of LLM-based agents. Specifically, we evaluate four types of memory structures, including chunks, knowledge triples, atomic facts, and summaries, along with mixed memory that combines these components. In addition, we evaluate three widely used memory retrieval methods: single-step retrieval, reranking, and iterative retrieval. Extensive experiments conducted across four tasks and six datasets yield the following key insights: (1) Different memory structures offer distinct advantages, enabling them to be tailored to specific tasks; (2) Mixed memory structures demonstrate remarkable resilience in noisy environments; (3) Iterative retrieval consistently outperforms other methods across various scenarios. Our investigation aims to inspire further research into the design of memory systems for LLM-based agents. 

**Abstract (ZH)**: 记忆在使基于大型语言模型（LLM）的代理能够进行复杂和长期的交互（如问题回答和对话系统）中发挥着关键作用。虽然为这些任务提出的各种记忆模块已经取得了显著进展，但不同记忆结构在不同任务中的影响仍然没有得到充分探索。本文探讨了记忆结构和记忆检索方法如何影响LLM代理的性能。具体来说，我们评估了四种类型的记忆结构，包括片段、知识三元组、原子事实和摘要，以及它们的混合记忆结构。此外，我们还评估了三种广泛使用的记忆检索方法：单步检索、再排序和迭代检索。通过对四个任务和六个数据集进行广泛实验，我们得出了以下关键见解：（1）不同的记忆结构提供了各自的优势，使其能够适应特定任务；（2）混合记忆结构在嘈杂环境中表现出色；（3）迭代检索方法在各种场景中始终优于其他方法。我们的研究旨在激发进一步探索用于LLM代理的记忆系统设计的研究。 

---
# Chinese SafetyQA: A Safety Short-form Factuality Benchmark for Large Language Models 

**Title (ZH)**: 中国安全QA：大规模语言模型的安全简短事实性基准 

**Authors**: Yingshui Tan, Boren Zheng, Baihui Zheng, Kerui Cao, Huiyun Jing, Jincheng Wei, Jiaheng Liu, Yancheng He, Wenbo Su, Xiangyong Zhu, Bo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15265)  

**Abstract**: With the rapid advancement of Large Language Models (LLMs), significant safety concerns have emerged. Fundamentally, the safety of large language models is closely linked to the accuracy, comprehensiveness, and clarity of their understanding of safety knowledge, particularly in domains such as law, policy and ethics. This factuality ability is crucial in determining whether these models can be deployed and applied safely and compliantly within specific regions. To address these challenges and better evaluate the factuality ability of LLMs to answer short questions, we introduce the Chinese SafetyQA benchmark. Chinese SafetyQA has several properties (i.e., Chinese, Diverse, High-quality, Static, Easy-to-evaluate, Safety-related, Harmless). Based on Chinese SafetyQA, we perform a comprehensive evaluation on the factuality abilities of existing LLMs and analyze how these capabilities relate to LLM abilities, e.g., RAG ability and robustness against attacks. 

**Abstract (ZH)**: 随着大型语言模型（LLMs）的快速进步，安全问题日益突出。从根本上说，大型语言模型的安全性与其对安全知识的理解准确性、全面性和清晰度密切相关，特别是在法律、政策和伦理等领域。这种事实判断能力决定了这些模型是否能够在特定区域安全合规地部署和应用。为了应对这些挑战，并更好地评估LLMs回答简短问题的事实判断能力，我们提出了中文安全QA基准（Chinese SafetyQA）。中文安全QA具有以下特性：（1）中文性；（2）多样性；（3）高质量；（4）静态性；（5）易于评估；（6）与安全相关；（7）无害性。基于中文安全QA，我们对现有的LLMs的事实判断能力进行了全面评估，并分析了这些能力与LLMs的其他能力（例如RAG能力及对抗攻击的鲁棒性）之间的关系。 

---
# ReXTrust: A Model for Fine-Grained Hallucination Detection in AI-Generated Radiology Reports 

**Title (ZH)**: ReXTrust：一种用于AI生成放射学报告细粒度幻觉检测的模型 

**Authors**: Romain Hardy, Sung Eun Kim, Pranav Rajpurkar  

**Link**: [PDF](https://arxiv.org/pdf/2412.15264)  

**Abstract**: The increasing adoption of AI-generated radiology reports necessitates robust methods for detecting hallucinations--false or unfounded statements that could impact patient care. We present ReXTrust, a novel framework for fine-grained hallucination detection in AI-generated radiology reports. Our approach leverages sequences of hidden states from large vision-language models to produce finding-level hallucination risk scores. We evaluate ReXTrust on a subset of the MIMIC-CXR dataset and demonstrate superior performance compared to existing approaches, achieving an AUROC of 0.8751 across all findings and 0.8963 on clinically significant findings. Our results show that white-box approaches leveraging model hidden states can provide reliable hallucination detection for medical AI systems, potentially improving the safety and reliability of automated radiology reporting. 

**Abstract (ZH)**: 随着AI生成的放射学报告越来越多地被采用，迫切需要发展出一套稳健的方法来检测幻觉——这种虚假或无根据的陈述可能会影响患者的护理。我们提出了一种新的框架ReXTrust，用于检测AI生成的放射学报告中的幻觉。我们的方法利用大型视觉-语言模型中的隐藏状态序列来生成基于发现的幻觉风险评分。我们对MIMIC-CXR数据集的一部分进行评估，并展示了ReXTrust相比于现有方法的优越性能，其总体AUROC为0.8751，对临床意义重大的发现来说为0.8963。我们的研究结果表明，利用模型隐藏状态的白盒方法可以为医疗AI系统提供可靠的幻觉检测，从而有可能提高自动化放射学报告的安全性和可靠性。 

---
# PROPOE 2: Avan\c{c}os na S\'intese Computacional de Poemas Baseados em Prosa Liter\'aria Brasileira 

**Title (ZH)**: PROPOE 2: 在巴西文学散文基础上的计算合成诗歌进展 

**Authors**: Felipe José D. Sousa, Sarah P. Cerqueira, João Queiroz, Angelo Loula  

**Link**: [PDF](https://arxiv.org/pdf/2412.15263)  

**Abstract**: The computational generation of poems is a complex task, which involves several sound, prosodic and rhythmic resources. In this work we present PROPOE 2, with the extension of structural and rhythmic possibilities compared to the original system, generating poems from metered sentences extracted from the prose of Brazilian literature, with multiple rhythmic assembly criteria. These advances allow for a more coherent exploration of rhythms and sound effects for the poem. Results of poems generated by the system are demonstrated, with variations in parameters to exemplify generation and evaluation using various criteria.
A geração computacional de poemas é uma tarefa complexa, que envolve diversos recursos sonoros, prosódicos e rítmicos. Neste trabalho apresentamos PROPOE 2, com a ampliação de possibilidades estruturais e rítmicas em relação ao sistema original, gerando poemas a partir de sentenças metrificadas extraídas da prosa da literatura brasileira, com múltiplos critérios rítmicos de montagem. Esses avanços permitem uma exploração mais coerente de ritmos e efeitos sonoros para o poema. Resultados de poemas gerados pelo sistema são demonstrados, com variações de parâmetros para exemplificar a geração e a avaliação pelos variados critérios. 

**Abstract (ZH)**: 计算生成诗歌是一项复杂任务，涉及多种声音、韵律和节奏资源。在本研究中，我们介绍了PROPOE 2，相较于原始系统，其扩展了结构和节奏的可能性，从巴西文学的散文中提取有韵的句子来生成诗歌，并采用多种节奏组合标准。这些进步使得对诗歌中的节奏和声音效果进行更连贯的探索成为可能。系统生成的诗歌结果得到了展示，并通过变化的参数进行示例，以说明各种标准下的生成和评估过程。 

---
# Advanced ingestion process powered by LLM parsing for RAG system 

**Title (ZH)**: 由大规模语言模型解析驱动的高级摄取过程用于检索增强系统 

**Authors**: Arnau Perez, Xavier Vizcaino  

**Link**: [PDF](https://arxiv.org/pdf/2412.15262)  

**Abstract**: Retrieval Augmented Generation (RAG) systems struggle with processing multimodal documents of varying structural complexity. This paper introduces a novel multi-strategy parsing approach using LLM-powered OCR to extract content from diverse document types, including presentations and high text density files both scanned or not. The methodology employs a node-based extraction technique that creates relationships between different information types and generates context-aware metadata. By implementing a Multimodal Assembler Agent and a flexible embedding strategy, the system enhances document comprehension and retrieval capabilities. Experimental evaluations across multiple knowledge bases demonstrate the approach's effectiveness, showing improvements in answer relevancy and information faithfulness. 

**Abstract (ZH)**: 检索增强生成（RAG）系统在处理结构复杂性变化的多模态文档时面临挑战。本文介绍了一种新的多策略解析方法，利用LLM驱动的OCR技术从各类文档中提取内容，包括演示文稿和高文本密度的文件（无论是扫描版还是非扫描版）。该方法采用基于节点的提取技术，创建不同类型信息之间的关系，并生成上下文相关的元数据。通过实施多模态组装代理和灵活的嵌入策略，系统增强了文档的可理解性和检索能力。在多个知识库上的实验评估表明，该方法的有效性，特别是在答案的相关性和信息的真实度方面有所提升。 

---
# Analyzing Images of Legal Documents: Toward Multi-Modal LLMs for Access to Justice 

**Title (ZH)**: 分析法律文件图像：通往公正法律获取的多模态LLM之路 

**Authors**: Hannes Westermann, Jaromir Savelka  

**Link**: [PDF](https://arxiv.org/pdf/2412.15260)  

**Abstract**: Interacting with the legal system and the government requires the assembly and analysis of various pieces of information that can be spread across different (paper) documents, such as forms, certificates and contracts (e.g. leases). This information is required in order to understand one's legal rights, as well as to fill out forms to file claims in court or obtain government benefits. However, finding the right information, locating the correct forms and filling them out can be challenging for laypeople. Large language models (LLMs) have emerged as a powerful technology that has the potential to address this gap, but still rely on the user to provide the correct information, which may be challenging and error-prone if the information is only available in complex paper documents. We present an investigation into utilizing multi-modal LLMs to analyze images of handwritten paper forms, in order to automatically extract relevant information in a structured format. Our initial results are promising, but reveal some limitations (e.g., when the image quality is low). Our work demonstrates the potential of integrating multi-modal LLMs to support laypeople and self-represented litigants in finding and assembling relevant information. 

**Abstract (ZH)**: 与法律系统和政府交互需要整理和分析散布在不同（纸质）文件中的各种信息，例如表单、证书和合同（例如租赁合同）。这些信息对于了解自己的法律权利，以及填写法庭诉讼或申请政府福利所需的表格至关重要。然而，找到正确的信息、定位正确的表单并填写这些表格对普通老百姓来说可能会面临挑战。大规模语言模型（LLMs）作为一种强大的技术，有潜力解决这一问题，但仍需用户提供正确的信息，而当这些信息仅以复杂的纸质文档形式存在时，这一过程可能具有挑战性和易出错性。我们研究了利用多模态LLMs分析手写纸质表单图像，以自动提取结构化格式的相关信息。初步结果显示了积极的趋势，但也揭示了一些局限性（例如，当图像质量较低时）。我们的工作展示了多模态LLMs整合以支持普通老百姓和代表自己出庭的诉讼当事人的潜力，帮助他们查找和整理相关的信息。 

---
# GLARE: Google Apps Arabic Reviews Dataset 

**Title (ZH)**: GLARE：Google 应用阿拉伯语评论数据集 

**Authors**: Fatima AlGhamdi, Reem Mohammed, Hend Al-Khalifa, Areeb Alowisheq  

**Link**: [PDF](https://arxiv.org/pdf/2412.15259)  

**Abstract**: This paper introduces GLARE an Arabic Apps Reviews dataset collected from Saudi Google PlayStore. It consists of 76M reviews, 69M of which are Arabic reviews of 9,980 Android Applications. We present the data collection methodology, along with a detailed Exploratory Data Analysis (EDA) and Feature Engineering on the gathered reviews. We also highlight possible use cases and benefits of the dataset. 

**Abstract (ZH)**: 本文介绍了一项从沙特阿拉伯Google Play Store收集的阿拉伯应用程序评论数据集GLARE。该数据集包含7600万条评论，其中6900万条评论是9980个Android应用程序的阿拉伯文评论。我们介绍了数据收集方法，并对其收集的评论进行了详细的数据探索性分析（EDA）和特征工程。此外，我们还强调了该数据集的潜在应用场景及其带来的好处。 

---
# DisEmbed: Transforming Disease Understanding through Embeddings 

**Title (ZH)**: DisEmbed：通过嵌入变换疾病理解 

**Authors**: Salman Faroz  

**Link**: [PDF](https://arxiv.org/pdf/2412.15258)  

**Abstract**: The medical domain is vast and diverse, with many existing embedding models focused on general healthcare applications. However, these models often struggle to capture a deep understanding of diseases due to their broad generalization across the entire medical field. To address this gap, I present DisEmbed, a disease-focused embedding model. DisEmbed is trained on a synthetic dataset specifically curated to include disease descriptions, symptoms, and disease-related Q\&A pairs, making it uniquely suited for disease-related tasks. For evaluation, I benchmarked DisEmbed against existing medical models using disease-specific datasets and the triplet evaluation method. My results demonstrate that DisEmbed outperforms other models, particularly in identifying disease-related contexts and distinguishing between similar diseases. This makes DisEmbed highly valuable for disease-specific use cases, including retrieval-augmented generation (RAG) tasks, where its performance is particularly robust. 

**Abstract (ZH)**: 医学领域庞大而多样，尽管已有许多嵌入模型专注于一般医疗应用，但这些模型在捕捉疾病深层次的理解方面往往存在困难，原因在于它们在整個医学领域中的广泛泛化。为了解决这一问题，我提出了DisEmbed，一种疾病导向的嵌入模型。DisEmbed基于一个专门设计的合成数据集进行训练，该数据集包含了疾病描述、症状以及疾病相关的问答对，使其特别适用于疾病相关的任务。为了评估DisEmbed的表现，我使用了疾病专门化的数据集和三元组评估方法，将DisEmbed与现有的医疗模型进行了基准测试。结果显示，DisEmbed在识别疾病相关上下文和区分相似疾病方面表现尤为出色，使其在疾病专门的应用场景中具有极高的价值，特别是在增强检索生成（RAG）任务中，其性能尤为稳健。 

---
# An Incremental Clustering Baseline for Event Detection on Twitter 

**Title (ZH)**: 基于Twitter上的事件检测的增量聚类baseline方法 

**Authors**: Marjolaine Ray, Qi Wang, Frédérique Mélanie-Becquet, Thierry Poibeau, Béatrice Mazoyer  

**Link**: [PDF](https://arxiv.org/pdf/2412.15257)  

**Abstract**: Event detection in text streams is a crucial task for the analysis of online media and social networks. One of the current challenges in this field is establishing a performance standard while maintaining an acceptable level of computational complexity. In our study, we use an incremental clustering algorithm combined with recent advancements in sentence embeddings. Our objective is to compare our findings with previous studies, specifically those by Cao et al. (2024) and Mazoyer et al. (2020). Our results demonstrate significant improvements and could serve as a relevant baseline for future research in this area. 

**Abstract (ZH)**: 文本流中的事件检测是在线媒体和社会网络分析中的关键任务。当前该领域的挑战之一是在保持合理计算复杂度的同时建立性能标准。在本研究中，我们采用增量聚类算法，并结合了最新的句子嵌入技术。我们的目标是将研究结果与Cao等（2024）和Mazoyer等（2020）的相关研究进行比较。研究结果表明，我们的方法在多个方面显著改进，并可作为未来研究的合适基线。 

---
# Structured Extraction of Real World Medical Knowledge using LLMs for Summarization and Search 

**Title (ZH)**: 使用大语言模型进行总结和搜索的现实世界医学知识结构化提取 

**Authors**: Edward Kim, Manil Shrestha, Richard Foty, Tom DeLay, Vicki Seyfert-Margolis  

**Link**: [PDF](https://arxiv.org/pdf/2412.15256)  

**Abstract**: Creation and curation of knowledge graphs can accelerate disease discovery and analysis in real-world data. While disease ontologies aid in biological data annotation, codified categories (SNOMED-CT, ICD10, CPT) may not capture patient condition nuances or rare diseases. Multiple disease definitions across data sources complicate ontology mapping and disease clustering. We propose creating patient knowledge graphs using large language model extraction techniques, allowing data extraction via natural language rather than rigid ontological hierarchies. Our method maps to existing ontologies (MeSH, SNOMED-CT, RxNORM, HPO) to ground extracted entities.
Using a large ambulatory care EHR database with 33.6M patients, we demonstrate our method through the patient search for Dravet syndrome, which received ICD10 recognition in October 2020. We describe our construction of patient-specific knowledge graphs and symptom-based patient searches. Using confirmed Dravet syndrome ICD10 codes as ground truth, we employ LLM-based entity extraction to characterize patients in grounded ontologies. We then apply this method to identify Beta-propeller protein-associated neurodegeneration (BPAN) patients, demonstrating real-world discovery where no ground truth exists. 

**Abstract (ZH)**: 知识图谱的创建与管理可以加速在真实世界数据中疾病的发现与分析。尽管疾病本体有助于生物数据注释，但编码类别（如SNOMED-CT、ICD10、CPT）可能无法捕捉患者状况细微之处或罕见疾病。由于不同数据源中存在多个疾病定义，这增加了本体映射和疾病聚类的复杂性。我们提出使用大规模语言模型提取技术创建患者知识图谱，通过自然语言而非严格的本体层次结构进行数据提取。我们的方法将提取的实体映射到现有的本体（如MeSH、SNOMED-CT、RxNORM、HPO），以奠定实体的基础。

我们使用包含3360万患者的大型门诊电子健康记录（EHR）数据库，通过搜索Dravet综合征患者来演示我们的方法，其中ICD10对Dravet综合征的识别发生在2020年10月。我们描述了患者特定的知识图谱构建及基于症状的患者搜索。利用已确认的Dravet综合征ICD10编码作为真实数据标准，我们使用基于大规模语言模型的实体提取技术来描述患者在本体中的特征。然后，我们应用这种方法来识别β螺旋桨蛋白相关神经退行性疾病（BPAN）患者，展示了在没有真实数据标准的情况下进行真实世界疾病发现的情况。 

---
# Data Laundering: Artificially Boosting Benchmark Results through Knowledge Distillation 

**Title (ZH)**: 数据漂白：通过知识蒸馏人工提升基准结果 

**Authors**: Jonibek Mansurov, Akhmed Sakip, Alham Fikri Aji  

**Link**: [PDF](https://arxiv.org/pdf/2412.15255)  

**Abstract**: In this paper, we show that knowledge distillation can be subverted to manipulate language model benchmark scores, revealing a critical vulnerability in current evaluation practices. We introduce "Data Laundering," a three-phase process analogous to financial money laundering, that enables the covert transfer of benchmark-specific knowledge through seemingly legitimate intermediate training steps. Through extensive experiments with a 2-layer BERT student model, we show how this approach can achieve substantial improvements in benchmark accuracy (up to 75\% on GPQA) without developing genuine reasoning capabilities. Notably, this method can be exploited intentionally or even unintentionally, as researchers may inadvertently adopt this method that inflates scores using knowledge distillation without realizing the implications. While our findings demonstrate the effectiveness of this technique, we present them as a cautionary tale highlighting the urgent need for more robust evaluation methods in AI. This work aims to contribute to the ongoing discussion about evaluation integrity in AI development and the need for benchmarks that more accurately reflect true model capabilities. The code is available at \url{this https URL}. 

**Abstract (ZH)**: 在本文中，我们展示了知识蒸馏可以被操纵以操控语言模型基准测试得分，揭示了当前评价实践中的一个关键漏洞。我们介绍了“数据漂白”(Data Laundering)这一三个阶段的过程，这一过程类似于金融上的洗钱，能够通过表面上合法的中间训练步骤，秘密地转移基准特定的知识。通过使用两层BERT学生模型进行大量实验，我们展示了这种做法如何能够在不发展真正推理能力的情况下，实现显著的基准准确率提升（在GPQA上最高可达75%）。值得注意的是，这种方法既可以故意使用，也可能无意中使用，研究人员可能在不知情的情况下采用这种方法，使其评分虚增，而未意识到其影响。虽然我们的发现证明了该技术的有效性，但我们将其呈现为一个警示故事，突显了在人工智能开发中需要更稳健的评价方法的迫切性。本文旨在促进对人工智能开发中评价完整性的持续讨论，以及对更准确反映真实模型能力的基准的需求。相关代码可在以下链接获取：\url{this https URL}。 

---
# RIRO: Reshaping Inputs, Refining Outputs Unlocking the Potential of Large Language Models in Data-Scarce Contexts 

**Title (ZH)**: RIRO：重塑输入，精炼输出——在数据稀缺环境中释放大规模语言模型的潜力 

**Authors**: Ali Hamdi, Hozaifa Kassab, Mohamed Bahaa, Marwa Mohamed  

**Link**: [PDF](https://arxiv.org/pdf/2412.15254)  

**Abstract**: Large language models (LLMs) have significantly advanced natural language processing, excelling in areas like text generation, summarization, and question-answering. Despite their capabilities, these models face challenges when fine-tuned on small, domain-specific datasets, often struggling to generalize and deliver accurate results with unfamiliar inputs. To tackle this issue, we introduce RIRO, a novel two-layer architecture designed to improve performance in data-scarce environments. The first layer leverages advanced prompt engineering to reformulate inputs, ensuring better alignment with training data, while the second layer focuses on refining outputs to minimize inconsistencies. Through fine-tuning models like Phi-2, Falcon 7B, and Falcon 1B, with Phi-2 outperforming the others. Additionally, we introduce a benchmark using evaluation metrics such as cosine similarity, Levenshtein distance, BLEU score, ROUGE-1, ROUGE-2, and ROUGE-L. While these advancements improve performance, challenges like computational demands and overfitting persist, limiting the potential of LLMs in data-scarce, high-stakes environments such as healthcare, legal documentation, and software testing. 

**Abstract (ZH)**: 大型语言模型（LLMs）在自然语言处理方面取得了显著进展，特别是在文本生成、摘要和问答等领域表现出色。尽管如此，这些模型在使用小规模、领域特定的数据集微调时，往往会面临泛化能力不足的问题，往往难以对不熟悉的数据输入提供准确的结果。为解决这一问题，我们提出了一种名为RIRO的新颖两层结构，旨在提高在数据稀缺环境中性能。第一层通过先进的提示工程来重新格式化输入，确保更好地与训练数据对齐，而第二层则专注于优化输出，减少不一致性。通过使用Phi-2、Falcon 7B和Falcon 1B等模型进行微调，结果显示Phi-2的表现优于其他模型。此外，我们还引入了一个使用余弦相似度、Levenshtein距离、BLEU分数、ROUGE-1、ROUGE-2和ROUGE-L等评价指标的基准测试。虽然这些进步提高了性能，但计算需求高和过拟合等问题仍然存在，限制了LLMs在医疗保健、法律文件和软件测试等数据稀缺、高风险环境中的应用潜力。 

---
# Using Machine Learning to Distinguish Human-written from Machine-generated Creative Fiction 

**Title (ZH)**: 使用机器学习区分人类创作与机器生成的创意小说 

**Authors**: Andrea Cristina McGlinchey, Peter J Barclay  

**Link**: [PDF](https://arxiv.org/pdf/2412.15253)  

**Abstract**: Following the universal availability of generative AI systems with the release of ChatGPT, automatic detection of deceptive text created by Large Language Models has focused on domains such as academic plagiarism and "fake news". However, generative AI also poses a threat to the livelihood of creative writers, and perhaps to literary culture in general, through reduction in quality of published material. Training a Large Language Model on writers' output to generate "sham books" in a particular style seems to constitute a new form of plagiarism. This problem has been little researched. In this study, we trained Machine Learning classifier models to distinguish short samples of human-written from machine-generated creative fiction, focusing on classic detective novels. Our results show that a Naive Bayes and a Multi-Layer Perceptron classifier achieved a high degree of success (accuracy > 95%), significantly outperforming human judges (accuracy < 55%). This approach worked well with short text samples (around 100 words), which previous research has shown to be difficult to classify. We have deployed an online proof-of-concept classifier tool, AI Detective, as a first step towards developing lightweight and reliable applications for use by editors and publishers, with the aim of protecting the economic and cultural contribution of human authors. 

**Abstract (ZH)**: 随着ChatGPT等生成式AI系统的广泛可用性，自动检测由大型语言模型生成的虚假文本已经重点关注了学术剽窃和“假新闻”等领域。然而，生成式AI也通过降低出版物质量对作家的生计构成了威胁，并可能对整体文学文化构成威胁。使用作家的写作输出训练大型语言模型以生成特定风格的“假书”似乎构成了一种新的剽窃形式。这个问题尚未受到广泛研究。在本研究中，我们训练了机器学习分类器模型，以区分人类创作的短篇小说片段与机器生成的创意小说片段，重点研究了经典侦探小说。我们的结果显示，朴素贝叶斯分类器和多层感知机分类器达到了极高的准确率（准确率>95%），显著优于人类评委（准确率<55%）。该方法在处理较短的文本样本（约100词）时表现良好，而先前的研究表明，这类样本很难进行分类。我们部署了一个名为“AI侦探”的在线概念验证分类器工具，作为开发轻量级且可靠的应用程序以供编辑和出版商使用的第一步，旨在保护人类作者的经济和文化贡献。 

---
# NER- RoBERTa: Fine-Tuning RoBERTa for Named Entity Recognition (NER) within low-resource languages 

**Title (ZH)**: NER-RoBERTa：在低资源语言中 fine-tune RoBERTa 进行命名实体识别（NER） 

**Authors**: Abdulhady Abas Abdullah, Srwa Hasan Abdulla, Dalia Mohammad Toufiq, Halgurd S. Maghdid, Tarik A. Rashid, Pakshan F. Farho, Shadan Sh. Sabr, Akar H. Taher, Darya S. Hamad, Hadi Veisi, Aras T. Asaad  

**Link**: [PDF](https://arxiv.org/pdf/2412.15252)  

**Abstract**: Nowadays, Natural Language Processing (NLP) is an important tool for most people's daily life routines, ranging from understanding speech, translation, named entity recognition (NER), and text categorization, to generative text models such as ChatGPT. Due to the existence of big data and consequently large corpora for widely used languages like English, Spanish, Turkish, Persian, and many more, these applications have been developed accurately. However, the Kurdish language still requires more corpora and large datasets to be included in NLP applications. This is because Kurdish has a rich linguistic structure, varied dialects, and a limited dataset, which poses unique challenges for Kurdish NLP (KNLP) application development. While several studies have been conducted in KNLP for various applications, Kurdish NER (KNER) remains a challenge for many KNLP tasks, including text analysis and classification. In this work, we address this limitation by proposing a methodology for fine-tuning the pre-trained RoBERTa model for KNER. To this end, we first create a Kurdish corpus, followed by designing a modified model architecture and implementing the training procedures. To evaluate the trained model, a set of experiments is conducted to demonstrate the performance of the KNER model using different tokenization methods and trained models. The experimental results show that fine-tuned RoBERTa with the SentencePiece tokenization method substantially improves KNER performance, achieving a 12.8% improvement in F1-score compared to traditional models, and consequently establishes a new benchmark for KNLP. 

**Abstract (ZH)**: 如今，自然语言处理（NLP）已成为人们日常生活中的一个重要工具，涵盖了语音理解、翻译、命名实体识别（NER）、文本分类，以及生成文本模型（如ChatGPT）等广泛的应用领域。由于大量数据的存在，尤其是广泛使用的英语、西班牙语、土耳其语、波斯语等语言的大规模语料库，这些应用已经得到了较为准确的发展。然而，库尔德语仍然需要更多的语料库和大规模数据集以纳入NLP应用中。这是因为库尔德语具有丰富的语言结构、多样的方言和有限的数据集，这使得库尔德语NLP（KNLP）应用开发面临独特的挑战。尽管在各种KNLP应用的研究中取得了一定进展，但库尔德语命名实体识别（KNER）仍然是很多KNLP任务中的一个挑战，包括文本分析和分类任务。在这项工作中，我们通过提出一种方法来微调预训练的RoBERTa模型解决这一局限性，该方法专门用于KNER。为此，我们首先创建了一个库尔德语语料库，随后设计了一种改良的模型架构并实现了训练程序。为了评估训练后的模型，我们进行了一系列实验，通过不同的分词方法和训练模型展示了KNER模型的性能。实验结果显示，使用SentencePiece分词方法微调后的RoBERTa模型显著提高了KNER性能，与传统模型相比，F1分数提高了12.8%，从而为KNLP建立了新的基准。 

---
# AgentPS: Agentic Process Supervision for Multi-modal Content Quality Assurance through Multi-round QA 

**Title (ZH)**: AgentPS：代理过程监督在多模态内容质量保障中的多轮问答方法 

**Authors**: Gorden Liu, Yu Sun, Ruixiao Sun, Xin Dong, Hongyu Xiong  

**Link**: [PDF](https://arxiv.org/pdf/2412.15251)  

**Abstract**: The advanced processing and reasoning capabilities of multimodal large language models (MLLMs) have driven substantial progress in vision-language (VL) understanding tasks. However, while effective for tasks governed by straightforward logic, MLLMs often encounter challenges when reasoning over complex, interdependent logic structures. To address this limitation, we introduce \textit{AgentPS}, a novel framework that integrates Agentic Process Supervision into MLLMs via multi-round question answering during fine-tuning. \textit{AgentPS} demonstrates significant performance improvements over baseline MLLMs on proprietary TikTok datasets, due to its integration of process supervision and structured sequential reasoning. Furthermore, we show that replacing human-annotated labels with LLM-generated labels retains much of the performance gain, highlighting the framework's practical scalability in industrial applications. These results position \textit{AgentPS} as a highly effective and efficient architecture for multimodal classification tasks. Its adaptability and scalability, especially when enhanced by automated annotation generation, make it a powerful tool for handling large-scale, real-world challenges. 

**Abstract (ZH)**: 多模态大语言模型（MLLMs）的高级处理和推理能力推动了视觉语言（VL）理解任务的显著进展。然而，这类模型在处理复杂互动的逻辑结构时往往遇到挑战。为此，我们提出了一种名为AgentPS的新框架，通过微调期间多轮问答集成代理过程监督。AgentPS在专用的TikTok数据集上展示了显著的性能提升，这得益于其结合了过程监督和结构化顺序推理。进一步的研究表明，用大语言模型生成的标签替代人工标注的标签仍能保持大部分的性能提升，突显了该框架在工业应用层面的实用可扩展性。这些结果将AgentPS定位为一种在多模态分类任务中高效且有效的架构。其适应性与可扩展性，特别是在增强自动化标注生成时，使其成为应对大规模真实世界挑战的强大工具。 

---
# An Enhanced Text Compression Approach Using Transformer-based Language Models 

**Title (ZH)**: 基于Transformer语言模型的增强文本压缩方法 

**Authors**: Chowdhury Mofizur Rahman, Mahbub E Sobhani, Anika Tasnim Rodela, Swakkhar Shatabda  

**Link**: [PDF](https://arxiv.org/pdf/2412.15250)  

**Abstract**: Text compression shrinks textual data while keeping crucial information, eradicating constraints on storage, bandwidth, and computational efficacy. The integration of lossless compression techniques with transformer-based text decompression has received negligible attention, despite the increasing volume of English text data in communication. The primary barrier in advancing text compression and restoration involves optimizing transformer-based approaches with efficient pre-processing and integrating lossless compression algorithms, that remained unresolved in the prior attempts. Here, we propose a transformer-based method named RejuvenateForme for text decompression, addressing prior issues by harnessing a new pre-processing technique and a lossless compression method. Our meticulous pre-processing technique incorporating the Lempel-Ziv-Welch algorithm achieves compression ratios of 12.57, 13.38, and 11.42 on the BookCorpus, EN-DE, and EN-FR corpora, thus showing state-of-the-art compression ratios compared to other deep learning and traditional approaches. Furthermore, the RejuvenateForme achieves a BLEU score of 27.31, 25.78, and 50.45 on the EN-DE, EN-FR, and BookCorpus corpora, showcasing its comprehensive efficacy. In contrast, the pre-trained T5-Small exhibits better performance over prior state-of-the-art models. 

**Abstract (ZH)**: 文本压缩在保持关键信息的前提下缩小了文本数据的大小，消除了存储、带宽和计算效率的限制。尽管英语文本数据在通信中的volume不断增加，将无损压缩技术与基于变换器的文本解压缩技术结合使用的做法仍未受到广泛关注。这一领域的主要障碍在于优化基于变换器的方法，以实现高效的预处理，并结合无损压缩算法，而这些在之前的尝试中尚未得到解决。在此，我们提出了一种基于变换器的方法——RejuvenateForme，通过利用一种新的预处理技术及一种无损压缩方法来解决这些问题。我们的精细预处理技术结合了Lempel-Ziv-Welch算法，在BookCorpus、EN-DE和EN-FR语料库中分别实现了12.57、13.38和11.42的压缩比，显示出了与其他深度学习和传统方法相比的最新压缩比。此外，RejuvenateForme在EN-DE、EN-FR和BookCorpus语料库中的BLEU评分分别为27.31、25.78和50.45，表明其具有全面的效用。相比之下，预训练的T5-Small模型在性能上优于之前的最新模型。 

---
# LLMs for Literature Review: Are we there yet? 

**Title (ZH)**: 用于文献综述的大型语言模型：我们到了吗？ 

**Authors**: Shubham Agarwal, Gaurav Sahu, Abhay Puri, Issam H. Laradji, Krishnamurthy DJ Dvijotham, Jason Stanley, Laurent Charlin, Christopher Pal  

**Link**: [PDF](https://arxiv.org/pdf/2412.15249)  

**Abstract**: Literature reviews are an essential component of scientific research, but they remain time-intensive and challenging to write, especially due to the recent influx of research papers. This paper explores the zero-shot abilities of recent Large Language Models (LLMs) in assisting with the writing of literature reviews based on an abstract. We decompose the task into two components: 1. Retrieving related works given a query abstract, and 2. Writing a literature review based on the retrieved results. We analyze how effective LLMs are for both components. For retrieval, we introduce a novel two-step search strategy that first uses an LLM to extract meaningful keywords from the abstract of a paper and then retrieves potentially relevant papers by querying an external knowledge base. Additionally, we study a prompting-based re-ranking mechanism with attribution and show that re-ranking doubles the normalized recall compared to naive search methods, while providing insights into the LLM's decision-making process. In the generation phase, we propose a two-step approach that first outlines a plan for the review and then executes steps in the plan to generate the actual review. To evaluate different LLM-based literature review methods, we create test sets from arXiv papers using a protocol designed for rolling use with newly released LLMs to avoid test set contamination in zero-shot evaluations. We release this evaluation protocol to promote additional research and development in this regard. Our empirical results suggest that LLMs show promising potential for writing literature reviews when the task is decomposed into smaller components of retrieval and planning. Further, we demonstrate that our planning-based approach achieves higher-quality reviews by minimizing hallucinated references in the generated review by 18-26% compared to existing simpler LLM-based generation methods. 

**Abstract (ZH)**: 文献综述是科学研究不可或缺的组成部分，但撰写文献综述仍然是一项耗时且具有挑战性的工作，尤其是由于近年来研究论文的急剧增加。本文探讨了近期大规模语言模型（LLMs）在基于摘要辅助撰写文献综述方面的零样本能力。我们将任务分解为两个部分：1. 在给定查询摘要的情况下检索相关工作，2. 根据检索结果撰写文献综述。我们分析了LLMs在这两个方面的效果。对于检索部分，我们提出了一种新颖的两步搜索策略：首先使用LLM从论文摘要中提取有意义的关键词，然后再通过查询外部知识库检索潜在相关论文。此外，我们研究了一种基于提示的重新排名机制，并展示了重新排名相比朴素搜索方法可以将归一化召回率提高一倍，同时提供对LLM决策过程的洞察。在生成阶段，我们提出了一种两步方法：首先概述综述计划，然后根据计划执行步骤以生成实际的综述。为了评估不同的LLM基文献综述方法，我们从arXiv论文中创建了测试集，并设计了一个在使用新发布的LLM时可以滚动更新的协议，以避免零样本评估中的测试集污染。我们发布了这一评估协议，以促进对该领域的进一步研究与开发。我们的实证结果显示，当任务分解为检索和规划的小部件时，LLM在撰写文献综述方面表现出令人鼓舞的潜力。此外，我们展示了基于规划的方法通过减少生成综述中虚构参考文献的比例（18%至26%）而实现了更高的综述质量，相比之下，现有的简单LLM生成方法效果较差。 

---
# RoundTripOCR: A Data Generation Technique for Enhancing Post-OCR Error Correction in Low-Resource Devanagari Languages 

**Title (ZH)**: 往返OCR：一种用于增强低资源.DEVANAGARI语言后期OCR错误校正的数据生成技术 

**Authors**: Harshvivek Kashid, Pushpak Bhattacharyya  

**Link**: [PDF](https://arxiv.org/pdf/2412.15248)  

**Abstract**: Optical Character Recognition (OCR) technology has revolutionized the digitization of printed text, enabling efficient data extraction and analysis across various domains. Just like Machine Translation systems, OCR systems are prone to errors. In this work, we address the challenge of data generation and post-OCR error correction, specifically for low-resource languages. We propose an approach for synthetic data generation for Devanagari languages, RoundTripOCR, that tackles the scarcity of the post-OCR Error Correction datasets for low-resource languages. We release post-OCR text correction datasets for Hindi, Marathi, Bodo, Nepali, Konkani and Sanskrit. We also present a novel approach for OCR error correction by leveraging techniques from machine translation. Our method involves translating erroneous OCR output into a corrected form by treating the OCR errors as mistranslations in a parallel text corpus, employing pre-trained transformer models to learn the mapping from erroneous to correct text pairs, effectively correcting OCR errors. 

**Abstract (ZH)**: 光学字符识别（OCR）技术彻底改变了印刷文本的数字化过程，使其能够在各个领域实现高效的数据提取与分析。就像机器翻译系统一样，OCR系统也容易出错。在本研究中，我们专注于数据生成与OCR后错误修正的挑战，特别是针对低资源语言。我们提出了一种针对梵文系语言的合成数据生成方法——RoundTripOCR，旨在解决低资源语言后OCR错误修正数据集稀缺的问题。我们发布了针对印地语、马哈拉施特拉语、博迪语、尼泊尔语、康坎语和梵语的后OCR文本修正数据集。此外，我们提出了一种利用机器翻译技术的新颖方法来进行OCR错误修正。该方法通过将OCR错误视为平行文本语料中的误译，利用预训练的变压器模型学习错误文本与正确文本的映射关系，从而有效地修正OCR错误。 

---
# Streamlining Systematic Reviews: A Novel Application of Large Language Models 

**Title (ZH)**: 简化系统评价：大型语言模型的一项新型应用 

**Authors**: Fouad Trad, Ryan Yammine, Jana Charafeddine, Marlene Chakhtoura, Maya Rahme, Ghada El-Hajj Fuleihan, Ali Chehab  

**Link**: [PDF](https://arxiv.org/pdf/2412.15247)  

**Abstract**: Systematic reviews (SRs) are essential for evidence-based guidelines but are often limited by the time-consuming nature of literature screening. We propose and evaluate an in-house system based on Large Language Models (LLMs) for automating both title/abstract and full-text screening, addressing a critical gap in the literature. Using a completed SR on Vitamin D and falls (14,439 articles), the LLM-based system employed prompt engineering for title/abstract screening and Retrieval-Augmented Generation (RAG) for full-text screening. The system achieved an article exclusion rate (AER) of 99.5%, specificity of 99.6%, a false negative rate (FNR) of 0%, and a negative predictive value (NPV) of 100%. After screening, only 78 articles required manual review, including all 20 identified by traditional methods, reducing manual screening time by 95.5%. For comparison, Rayyan, a commercial tool for title/abstract screening, achieved an AER of 72.1% and FNR of 5% when including articles Rayyan considered as undecided or likely to include. Lowering Rayyan's inclusion thresholds improved FNR to 0% but increased screening time. By addressing both screening phases, the LLM-based system significantly outperformed Rayyan and traditional methods, reducing total screening time to 25.5 hours while maintaining high accuracy. These findings highlight the transformative potential of LLMs in SR workflows by offering a scalable, efficient, and accurate solution, particularly for the full-text screening phase, which has lacked automation tools. 

**Abstract (ZH)**: 系统评价（SRs）对于基于证据的指南至关重要，但文献筛查往往耗时较长，限制了其应用。我们提出并评估了一种基于大规模语言模型（LLMs）的内部系统，用于自动化标题/摘要筛查和全文筛查，填补了文献中的一个关键空白。利用完成的一项关于维生素D与跌倒的SR（14,439篇文章），基于LLMs的系统采用了提示工程技术进行标题/摘要筛查，并使用检索增强生成（RAG）进行全文筛查。该系统实现了文章排除率（AER）99.5%、特异度99.6%、假阴性率（FNR）0%和阴性预测值（NPV）100%。经过筛查后，仅需手动审查78篇文章，这包括所有20篇传统方法筛选出的文章，从而将手动筛查时间减少了95.5%。相比之下，Rayyan是一种用于标题/摘要筛查的商业工具，当包括Rayyan视为未决定或可能包含的文章时，其AER为72.1%，FNR为5%。通过降低Rayyan的纳入阈值可以将FNR降低到0%，但会增加筛查时间。通过同时解决两个筛查阶段，基于LLMs的系统显著优于Rayyan和传统的筛查方法，将总筛查时间降至25.5小时，同时保持高准确性。这些发现突显了LLMs在SR工作流程中的变革潜力，提供了可扩展、高效且准确的解决方案，尤其是在全文筛查阶段，该阶段缺乏自动化工具。 

---
# Accelerating Retrieval-Augmented Generation 

**Title (ZH)**: 加速检索增强生成 

**Authors**: Derrick Quinn, Mohammad Nouri, Neel Patel, John Salihu, Alireza Salemi, Sukhan Lee, Hamed Zamani, Mohammad Alian  

**Link**: [PDF](https://arxiv.org/pdf/2412.15246)  

**Abstract**: An evolving solution to address hallucination and enhance accuracy in large language models (LLMs) is Retrieval-Augmented Generation (RAG), which involves augmenting LLMs with information retrieved from an external knowledge source, such as the web. This paper profiles several RAG execution pipelines and demystifies the complex interplay between their retrieval and generation phases. We demonstrate that while exact retrieval schemes are expensive, they can reduce inference time compared to approximate retrieval variants because an exact retrieval model can send a smaller but more accurate list of documents to the generative model while maintaining the same end-to-end accuracy. This observation motivates the acceleration of the exact nearest neighbor search for RAG.
In this work, we design Intelligent Knowledge Store (IKS), a type-2 CXL device that implements a scale-out near-memory acceleration architecture with a novel cache-coherent interface between the host CPU and near-memory accelerators. IKS offers 13.4-27.9x faster exact nearest neighbor search over a 512GB vector database compared with executing the search on Intel Sapphire Rapids CPUs. This higher search performance translates to 1.7-26.3x lower end-to-end inference time for representative RAG applications. IKS is inherently a memory expander; its internal DRAM can be disaggregated and used for other applications running on the server to prevent DRAM, which is the most expensive component in today's servers, from being stranded. 

**Abstract (ZH)**: 解决大型语言模型（LLMs）中幻觉问题并提高准确性的逐步演进解决方案是检索增强生成（RAG），即通过将LLMs与外部知识源（如网络）检索的信息结合起来进行增强。本文概述了几种RAG执行管道，并揭示了它们检索和生成阶段复杂交互的作用。我们表明，尽管精确检索方案成本高昂，但与近似检索变体相比，它们可以缩短推理时间，因为精确检索模型可以发送更小但更准确的文档列表给生成模型，同时保持相同的端到端准确率。这一观察结果促使我们加速RAG中的精确最近邻搜索。

在本文中，我们设计了一种名为智能知识存储（IKS）的CXL类型2设备，该设备实现了基于主机CPU和近内存加速器之间新型缓存一致接口的扩展近内存加速架构。IKS 在一个512GB向量数据库中进行精确最近邻搜索的速度比在Intel Sapphirerapids CPU上执行搜索快13.4至27.9倍。这种更高的搜索性能转化为代表性的RAG应用程序中1.7至26.3倍的较低端到端推理时间。IKS 内置地扩展了内存，其内部的DRAM可以被分割并用于服务器上的其他应用程序，防止了成本最高的组件（即当前服务器中的DRAM）被闲置。 

---
# MPPO: Multi Pair-wise Preference Optimization for LLMs with Arbitrary Negative Samples 

**Title (ZH)**: MPPO：具有任意负样本的LLMs的多对数偏好优化 

**Authors**: Shuo Xie, Fangzhi Zhu, Jiahui Wang, Lulu Wen, Wei Dai, Xiaowei Chen, Junxiong Zhu, Kai Zhou, Bo Zheng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15244)  

**Abstract**: Aligning Large Language Models (LLMs) with human feedback is crucial for their development. Existing preference optimization methods such as DPO and KTO, while improved based on Reinforcement Learning from Human Feedback (RLHF), are inherently derived from PPO, requiring a reference model that adds GPU memory resources and relies heavily on abundant preference data. Meanwhile, current preference optimization research mainly targets single-question scenarios with two replies, neglecting optimization with multiple replies, which leads to a waste of data in the application. This study introduces the MPPO algorithm, which leverages the average likelihood of model responses to fit the reward function and maximizes the utilization of preference data. Through a comparison of Point-wise, Pair-wise, and List-wise implementations, we found that the Pair-wise approach achieves the best performance, significantly enhancing the quality of model responses. Experimental results demonstrate MPPO's outstanding performance across various benchmarks. On MT-Bench, MPPO outperforms DPO, ORPO, and SimPO. Notably, on Arena-Hard, MPPO surpasses DPO and ORPO by substantial margins. These achievements underscore the remarkable advantages of MPPO in preference optimization tasks. 

**Abstract (ZH)**: 将以下论文内容或标题翻译成中文，符合学术规范：

使大语言模型（LLMs）与人类反馈对齐对其发展至关重要。现有的偏好优化方法，如DPO和KTO，基于人类反馈强化学习（RLHF）进行了改进，但这些方法本质上源自PPO，需要一个参考模型，这增加了GPU内存资源的消耗，并且高度依赖丰富的偏好数据。同时，当前的偏好优化研究主要集中在单个问题场景中两个回复的优化上，忽视了多回复的优化，导致了在应用中的数据浪费。本研究引入了MPPO算法，该算法利用模型响应的平均可能性来拟合奖励函数，并最大限度地利用偏好数据。通过对比点对点（Point-wise）、成对（Pair-wise）和列表（List-wise）实现方式，我们发现成对方法的性能最佳，显著提升了模型响应的质量。实验结果表明，MPPO在各种基准测试中表现出色。在MT-Bench上，MPPO的表现优于DPO、ORPO和SimPO。值得注意的是，在Arena-Hard上，MPPO相对于DPO和ORPO在性能上有显著提升。这些成就突显了MPPO在偏好优化任务中的显著优势。 

---
# Script-Based Dialog Policy Planning for LLM-Powered Conversational Agents: A Basic Architecture for an "AI Therapist" 

**Title (ZH)**: 基于脚本的对话策略规划：为大规模语言模型驱动的对话代理设计“AI治疗师”基本架构 

**Authors**: Robert Wasenmüller, Kevin Hilbert, Christoph Benzmüller  

**Link**: [PDF](https://arxiv.org/pdf/2412.15242)  

**Abstract**: Large Language Model (LLM)-Powered Conversational Agents have the potential to provide users with scaled behavioral healthcare support, and potentially even deliver full-scale "AI therapy'" in the future. While such agents can already conduct fluent and proactive emotional support conversations, they inherently lack the ability to (a) consistently and reliably act by predefined rules to align their conversation with an overarching therapeutic concept and (b) make their decision paths inspectable for risk management and clinical evaluation -- both essential requirements for an "AI Therapist".
In this work, we introduce a novel paradigm for dialog policy planning in conversational agents enabling them to (a) act according to an expert-written "script" that outlines the therapeutic approach and (b) explicitly transition through a finite set of states over the course of the conversation. The script acts as a deterministic component, constraining the LLM's behavior in desirable ways and establishing a basic architecture for an AI Therapist.
We implement two variants of Script-Based Dialog Policy Planning using different prompting techniques and synthesize a total of 100 conversations with LLM-simulated patients. The results demonstrate the feasibility of this new technology and provide insights into the efficiency and effectiveness of different implementation variants. 

**Abstract (ZH)**: 大语言模型（LLM）驱动的对话代理有可能为用户提供扩展的行为健康支持，并且未来甚至可以提供全面的“AI疗法”。虽然这些代理已经能够进行流畅、积极的情感支持对话，但它们仍然存在无法（a）始终一致地按照预定义规则行动，以使对话与整体治疗概念保持一致，以及（b）使决策路径可检查，以便风险管理与临床评估的问题——这两者是“AI疗法”所必需的要求。

在本研究中，我们提出了一个用于对话策略规划的新范式，使对话代理能够（a）根据专家编写的“剧本”进行行动，该剧本概述了治疗方法，以及（b）在对话过程中明确地通过一组有限状态。该剧本作为确定性的组成部分，限制了LLM的行为，并奠定了“AI疗法”基本架构的基础。

我们使用不同的提示技术实现了两种基于剧本的对话策略规划变体，并使用LLM模拟的患者合成了共计100次对话。实验结果证明了该新方法的可行性，并提供了不同实施变体的效率与有效性见解。 

---
# Quantifying Positional Biases in Text Embedding Models 

**Title (ZH)**: 量化文本嵌入模型中的位置偏见 

**Authors**: Samarth Goel, Reagan J. Lee, Kannan Ramchandran  

**Link**: [PDF](https://arxiv.org/pdf/2412.15241)  

**Abstract**: Embedding models are crucial for tasks in Information Retrieval (IR) and semantic similarity measurement, yet their handling of longer texts and associated positional biases remains underexplored. In this study, we investigate the impact of content position and input size on text embeddings. Our experiments reveal that embedding models, irrespective of their positional encoding mechanisms, disproportionately prioritize the beginning of an input. Ablation studies demonstrate that insertion of irrelevant text or removal at the start of a document reduces cosine similarity between altered and original embeddings by up to 12.3\% more than ablations at the end. Regression analysis further confirms this bias, with sentence importance declining as position moves further from the start, even with with content-agnosticity. We hypothesize that this effect arises from pre-processing strategies and chosen positional encoding techniques. These findings quantify the sensitivity of retrieval systems and suggest a new lens towards embedding model robustness. 

**Abstract (ZH)**: 嵌入模型对于信息检索（IR）任务和语义相似性测量至关重要，但它们在处理较长文本及其相关的位置偏差方面仍存在不足。在本研究中，我们探讨了内容位置和输入大小对文本嵌入的影响。实验结果表明，无论嵌入模型采用何种位置编码机制，它们都会不均衡地倾向于输入的开头部分。消融实验表明，在文档开头插入无关文本或删除开头内容会比在文档末尾进行消融导致更改后的嵌入与原始嵌入的余弦相似度降低12.3%以上。回归分析进一步证实了这种偏差，句重要性随位置远离开头而下降，即使在内容无关的情况下也是如此。我们假设这一效应源于预处理策略和选择的位置编码技术。这些发现量化了检索系统的敏感性，并提出了一种新的嵌入模型鲁棒性视角。 

---
# ChainStream: An LLM-based Framework for Unified Synthetic Sensing 

**Title (ZH)**: ChainStream：一种基于大语言模型的统一合成感知框架 

**Authors**: Jiacheng Liu, Yuanchun Li, Liangyan Li, Yi Sun, Hao Wen, Xiangyu Li, Yao Guo, Yunxin Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15240)  

**Abstract**: Many applications demand context sensing to offer personalized and timely services. Yet, developing sensing programs can be challenging for developers and using them is privacy-concerning for end-users. In this paper, we propose to use natural language as the unified interface to process personal data and sense user context, which can effectively ease app development and make the data pipeline more transparent. Our work is inspired by large language models (LLMs) and other generative models, while directly applying them does not solve the problem - letting the model directly process the data cannot handle complex sensing requests and letting the model write the data processing program suffers error-prone code generation. We address the problem with 1) a unified data processing framework that makes context-sensing programs simpler and 2) a feedback-guided query optimizer that makes data query more informative. To evaluate the performance of natural language-based context sensing, we create a benchmark that contains 133 context sensing tasks. Extensive evaluation has shown that our approach is able to automatically solve the context-sensing tasks efficiently and precisely. The code is opensourced at this https URL. 

**Abstract (ZH)**: 许多应用程序需要情境感知以提供个性化和及时的服务。然而，开发感知程序对于开发者来说具有挑战性，而用户在使用这些程序时则关心个人隐私。本文中，我们提出使用自然语言作为统一界面来处理个人数据并感知用户情境，这将有效简化应用程序开发并使数据处理流程更具透明性。我们的工作灵感来源于大型语言模型（LLMs）和其他生成模型，但直接应用于这些模型并不能解决问题——让模型直接处理数据无法处理复杂的感知请求，而让模型编写数据处理程序则会导致错误的代码生成。我们通过以下方式解决了这一问题：1) 提出了一种统一的数据处理框架，使情境感知程序更简单；2) 提出了一个反馈指导的查询优化器，使数据查询更具信息性。为了评估基于自然语言的情境感知性能，我们创建了一个基准测试，其中包含133个情境感知任务。广泛的评估表明，我们的方法能够高效且精确地自动完成情境感知任务。源代码已开源，可访问 <请提供具体的URL或直接提供链接>。 

---
# Modeling Story Expectations to Understand Engagement: A Generative Framework Using LLMs 

**Title (ZH)**: 利用大语言模型构建生成框架，以建模故事情节预期并理解参与度 

**Authors**: Hortense Fong, George Gui  

**Link**: [PDF](https://arxiv.org/pdf/2412.15239)  

**Abstract**: Understanding when and why consumers engage with stories is crucial for content creators and platforms. While existing theories suggest that audience beliefs of what is going to happen should play an important role in engagement decisions, empirical work has mostly focused on developing techniques to directly extract features from actual content, rather than capturing forward-looking beliefs, due to the lack of a principled way to model such beliefs in unstructured narrative data. To complement existing feature extraction techniques, this paper introduces a novel framework that leverages large language models to model audience forward-looking beliefs about how stories might unfold. Our method generates multiple potential continuations for each story and extracts features related to expectations, uncertainty, and surprise using established content analysis techniques. Applying our method to over 30,000 book chapters from Wattpad, we demonstrate that our framework complements existing feature engineering techniques by amplifying their marginal explanatory power on average by 31%. The results reveal that different types of engagement-continuing to read, commenting, and voting-are driven by distinct combinations of current and anticipated content features. Our framework provides a novel way to study and explore how audience forward-looking beliefs shape their engagement with narrative media, with implications for marketing strategy in content-focused industries. 

**Abstract (ZH)**: 了解消费者何时以及为何参与故事对于内容创作者和平台至关重要。虽然现有理论表明观众对未来可能发生的事件的信念应该在参与决策中扮演重要角色，但实证研究大多集中于开发从实际内容中直接提取特征的技术，而不是捕捉前瞻性信念，这是因为缺乏一种在非结构化叙事数据中建模此类信念的系统化方法。为了补充现有的特征提取技术，本文引入了一种新的框架，利用大规模语言模型来建模观众对故事可能如何发展的前瞻性信念。我们的方法为每个故事生成多个潜在续篇，并通过现有的内容分析技术提取与期望、不确定性以及惊喜相关的特征。将我们的方法应用于 Wattpad 上超过 30,000 个章节，结果显示，我们的框架通过平均放大现有特征工程技术边际解释力 31%，从而进一步补充了它们。研究结果表明，不同类型的参与行为（继续阅读、评论和投票）由当前和预期内容特征的不同组合驱动。我们的框架为研究和探索前瞻性信念如何影响观众对叙事媒体的参与提供了一种新的途径，对于内容导向行业的营销策略具有重要意义。 

---
# Dipper: Diversity in Prompts for Producing Large Language Model Ensembles in Reasoning tasks 

**Title (ZH)**: 提斗：推理任务中大型语言模型集成的提示多样性 

**Authors**: Gregory Kang Ruey Lau, Wenyang Hu, Diwen Liu, Jizhuo Chen, See-Kiong Ng, Bryan Kian Hsiang Low  

**Link**: [PDF](https://arxiv.org/pdf/2412.15238)  

**Abstract**: Large Language Models still encounter substantial challenges in reasoning tasks, especially for smaller models, which many users may be restricted to due to resource constraints (e.g. GPU memory restrictions). Inference-time methods to boost LLM performance, such as prompting methods to invoke certain reasoning pathways in responses, have been shown effective in past works, though they largely rely on sequential queries. The ensemble method, which consists of multiple constituent models running in parallel, is a promising approach to achieving better inference-time performance, especially given recent developments that enabled significant speed-ups in LLM batch inference. In this work, we propose a novel, training-free LLM ensemble framework where a single LLM model is fed an optimized, diverse set of prompts in parallel, effectively producing an ensemble at inference time to achieve performance improvement in reasoning tasks. We empirically demonstrate that our method leads to significant gains on math reasoning tasks, e.g., on MATH, where our ensemble consisting of a few small models (e.g., three Qwen2-MATH-1.5B-it models) can outperform a larger model (e.g., Qwen2-MATH-7B-it). 

**Abstract (ZH)**: 大型语言模型在推理任务中仍然面临诸多挑战，尤其是对于较小的模型，很多用户可能由于资源限制（如GPU内存限制）而无法使用。在推理时间提升大型语言模型（LLM）性能的方法，如通过提示方法触发特定的推理路径，在以往的研究中已被证明有效，尽管这些方法主要依赖于顺序查询。由多个并行运行的组成部分模型组成的集成方法是一种有望在提升推理时间性能方面取得更好结果的方法，尤其是在最近的技术发展使得LLM批量推理速度显著提高的情况下。在本研究中，我们提出了一种全新的无需训练的LLM集成框架，其中单个LLM模型同时接受优化且多样的提示输入，从而在推理时间生成集成体，以在推理任务中实现性能提升。我们通过实验证明，我们的方法在数学推理任务上表现出了显著的改进，例如，在MATH数据集上，由几个小型模型（例如，三个Qwen2-MATH-1.5B-it模型）组成的集成体可以优于一个较大的模型（例如，Qwen2-MATH-7B-it）。 

---
# CareBot: A Pioneering Full-Process Open-Source Medical Language Model 

**Title (ZH)**: CareBot： pioneernike的全流程开源医疗语言模型

为了更符合学术规范和中文表达习惯，可以进一步优化为：

CareBot：全流程开源医疗语言模型探研

这样既保留了原文的核心信息，又体现了学术论文的规范和风格。 

**Authors**: Lulu Zhao, Weihao Zeng, Xiaofeng Shi, Hua Zhou  

**Link**: [PDF](https://arxiv.org/pdf/2412.15236)  

**Abstract**: Recently, both closed-source LLMs and open-source communities have made significant strides, outperforming humans in various general domains. However, their performance in specific professional domains such as medicine, especially within the open-source community, remains suboptimal due to the complexity of medical knowledge. In this paper, we propose CareBot, a bilingual medical LLM, which leverages a comprehensive approach integrating continuous pre-training (CPT), supervised fine-tuning (SFT), and reinforcement learning with human feedback (RLHF). Our novel two-stage CPT method, comprising Stable CPT and Boost CPT, effectively bridges the gap between general and domain-specific data, facilitating a smooth transition from pre-training to fine-tuning and enhancing domain knowledge progressively. We also introduce DataRater, a model designed to assess data quality during CPT, ensuring that the training data is both accurate and relevant. For SFT, we develope a large and diverse bilingual dataset, along with ConFilter, a metric to enhance multi-turn dialogue quality, which is crucial to improving the model's ability to handle more complex dialogues. The combination of high-quality data sources and innovative techniques significantly improves CareBot's performance across a range of medical applications. Our rigorous evaluations on Chinese and English benchmarks confirm CareBot's effectiveness in medical consultation and education. These advancements not only address current limitations in medical LLMs but also set a new standard for developing effective and reliable open-source models in the medical domain. We will open-source the datasets and models later, contributing valuable resources to the research community. 

**Abstract (ZH)**: 近年来，无论是闭源的大型语言模型（LLM）还是开源社区，都取得了显著进展，在多个通用领域已经超过了人类的表现。然而，这些模型在特定的专业领域，尤其是医疗领域，由于医学知识的复杂性，其表现仍然不尽如人意。本文中，我们提出了CareBot，一种双语医疗LLM，它采用了综合的方法，结合了连续预训练（CPT）、监督微调（SFT）和基于人类反馈的强化学习（RLHF）。我们提出了一种创新的两阶段CPT方法，包括稳定的CPT和增强的CPT，有效地缩小了通用数据与领域特定数据之间的差距，促进了从预训练到微调的平稳过渡，并逐步增强领域知识。我们还介绍了一个名为DataRater的模型，用于评估CPT过程中的数据质量，确保训练数据既准确又相关。对于SFT，我们开发了一个大规模且多样性的双语数据集，并引入了一个度量标准ConFilter，用于提高多轮对话质量，这对于提高模型处理更复杂对话的能力至关重要。高质量的数据来源和创新技术的结合，显著提升了CareBot在医疗应用领域的性能。我们对中文和英文基准的严格的评估结果显示，CareBot在医疗咨询和教育方面具有很强的有效性。这些进步不仅解决了当前医疗LLM的局限性，也为在医疗领域开发有效且可靠的开源模型设定了新的标准。我们将后续开源这些数据集和模型，为研究社区提供宝贵的资源。 

---
# OG-RAG: Ontology-Grounded Retrieval-Augmented Generation For Large Language Models 

**Title (ZH)**: OG-RAG：面向本体检索增强生成方法用于大型语言模型 

**Authors**: Kartik Sharma, Peeyush Kumar, Yunqing Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.15235)  

**Abstract**: This paper presents OG-RAG, an Ontology-Grounded Retrieval Augmented Generation method designed to enhance LLM-generated responses by anchoring retrieval processes in domain-specific ontologies. While LLMs are widely used for tasks like question answering and search, they struggle to adapt to specialized knowledge, such as industrial workflows or knowledge work, without expensive fine-tuning or sub-optimal retrieval methods. Existing retrieval-augmented models, such as RAG, offer improvements but fail to account for structured domain knowledge, leading to suboptimal context generation. Ontologies, which conceptually organize domain knowledge by defining entities and their interrelationships, offer a structured representation to address this gap. OG-RAG constructs a hypergraph representation of domain documents, where each hyperedge encapsulates clusters of factual knowledge grounded using domain-specific ontology. An optimization algorithm then retrieves the minimal set of hyperedges that constructs a precise, conceptually grounded context for the LLM. This method enables efficient retrieval while preserving the complex relationships between entities. OG-RAG applies to domains where fact-based reasoning is essential, particularly in tasks that require workflows or decision-making steps to follow predefined rules and procedures. These include industrial workflows in healthcare, legal, and agricultural sectors, as well as knowledge-driven tasks such as news journalism, investigative research, consulting and more. Our evaluations demonstrate that OG-RAG increases the recall of accurate facts by 55% and improves response correctness by 40% across four different LLMs. Additionally, OG-RAG enables 30% faster attribution of responses to context and boosts fact-based reasoning accuracy by 27% compared to baseline methods. 

**Abstract (ZH)**: 本文提出了一种基于本体的检索增强生成方法（OG-RAG），旨在通过将检索过程锚定在领域特定本体上，从而增强LLM生成的响应。虽然LLM广泛应用于问答和搜索等任务，但在处理如工业流程或知识工作等专业领域知识时，它们往往无法通过昂贵的微调或不理想的检索方法进行有效适应。现有的检索增强模型，如RAG，虽然提供了改进，但未能考虑到结构化的领域知识，导致上下文生成效果欠佳。本体从概念上组织领域知识，通过定义实体及其相互关系来提供一种结构化的表示方法，以此填补这一空白。OG-RAG 构建了一个领域文档的超图表示，其中每个超边封装了通过领域特定本体进行事实性知识归因的实体集群。随后优化算法检索出能够构成精确、概念性上下文的最小超边集，以供LLM使用。这种方法能够在保留实体间复杂关系的同时实现高效的检索。OG-RAG 适用于基于事实的推理至关重要的领域，特别是在需要遵循预定义规则和程序的工作流或决策任务中尤为重要。这些领域包括医疗、法律和农业行业的工业工作流程，以及诸如新闻采编、调查研究、咨询等知识驱动的任务。我们的评估结果显示，OG-RAG 将准确事实的召回率提高了55%，并将响应的正确性提高了40%。此外，OG-RAG 使得对上下文的响应归属速度提高了30%，并且相比基准方法提高了27%的事实性推理准确性。 

---
# Offline Reinforcement Learning for LLM Multi-Step Reasoning 

**Title (ZH)**: 离线强化学习在大规模语言模型多步骤推理中的应用 

**Authors**: Huaijie Wang, Shibo Hao, Hanze Dong, Shenao Zhang, Yilin Bao, Ziran Yang, Yi Wu  

**Link**: [PDF](https://arxiv.org/pdf/2412.16145)  

**Abstract**: Improving the multi-step reasoning ability of large language models (LLMs) with offline reinforcement learning (RL) is essential for quickly adapting them to complex tasks. While Direct Preference Optimization (DPO) has shown promise in aligning LLMs with human preferences, it is less suitable for multi-step reasoning tasks because (1) DPO relies on paired preference data, which is not readily available for multi-step reasoning tasks, and (2) it treats all tokens uniformly, making it ineffective for credit assignment in multi-step reasoning tasks, which often come with sparse reward. In this work, we propose OREO (Offline Reasoning Optimization), an offline RL method for enhancing LLM multi-step reasoning. Building on insights from previous works of maximum entropy reinforcement learning, it jointly learns a policy model and value function by optimizing the soft Bellman Equation. We show in principle that it reduces the need to collect pairwise data and enables better credit assignment. Empirically, OREO surpasses existing offline learning methods on multi-step reasoning benchmarks, including mathematical reasoning tasks (GSM8K, MATH) and embodied agent control (ALFWorld). The approach can be extended to a multi-iteration framework when additional resources are available. Furthermore, the learned value function can be leveraged to guide the tree search for free, which can further boost performance during test time. 

**Abstract (ZH)**: 利用离线强化学习（RL）提高大型语言模型（LLMs）的多步推理能力对于快速适应复杂任务至关重要。尽管直接偏好优化（DPO）在使LLMs与人类偏好相一致方面显示出潜力，但它对于多步推理任务并不适用，原因在于（1）DPO依赖配对偏好数据，而这种数据对于多步推理任务来说并不容易获得，以及（2）它对待所有标记的处理方式是统一的，使其在多步推理任务中进行奖励归因方面效果较差，而这种任务通常具有稀疏奖励。在本文中，我们提出了一种名为OREO（Offline Reasoning Optimization）的方法，这是一种用于增强LLM多步推理能力的离线RL方法。该方法基于最大熵强化学习领域先前工作的见解，通过优化软贝尔曼方程同时学习策略模型和价值函数。我们从原则上证明了，这种方法减少了收集配对数据的需要并有助于更好地进行奖励归因。实验结果表明，OREO在多步推理基准测试中超过了现有的离线学习方法，包括数学推理任务（如GSM8K、MATH）和具身处代理控制任务（如ALFWorld）。当可用额外资源时，该方法可以扩展到多迭代框架。此外，学习到的价值函数可以免费指导树搜索，从而在测试时间进一步提升性能。 

---
# Can LLMs Obfuscate Code? A Systematic Analysis of Large Language Models into Assembly Code Obfuscation 

**Title (ZH)**: 大型语言模型能否混淆代码？对大型语言模型生成汇编代码混淆的系统分析 

**Authors**: Seyedreza Mohseni, Seyedali Mohammadi, Deepa Tilwani, Yash Saxena, Gerald Ndwula, Sriram Vema, Edward Raff, Manas Gaur  

**Link**: [PDF](https://arxiv.org/pdf/2412.16135)  

**Abstract**: Malware authors often employ code obfuscations to make their malware harder to detect. Existing tools for generating obfuscated code often require access to the original source code (e.g., C++ or Java), and adding new obfuscations is a non-trivial, labor-intensive process. In this study, we ask the following question: Can Large Language Models (LLMs) potentially generate a new obfuscated assembly code? If so, this poses a risk to anti-virus engines and potentially increases the flexibility of attackers to create new obfuscation patterns. We answer this in the affirmative by developing the MetamorphASM benchmark comprising MetamorphASM Dataset (MAD) along with three code obfuscation techniques: dead code, register substitution, and control flow change. The MetamorphASM systematically evaluates the ability of LLMs to generate and analyze obfuscated code using MAD, which contains 328,200 obfuscated assembly code samples. We release this dataset and analyze the success rate of various LLMs (e.g., GPT-3.5/4, GPT-4o-mini, Starcoder, CodeGemma, CodeLlama, CodeT5, and LLaMA 3.1) in generating obfuscated assembly code. The evaluation was performed using established information-theoretic metrics and manual human review to ensure correctness and provide the foundation for researchers to study and develop remediations to this risk. The source code can be found at the following GitHub link: this https URL. 

**Abstract (ZH)**: 恶意软件作者经常使用代码混淆技术来使其恶意软件更难被检测。现有的生成混淆代码的工具通常需要访问原始源代码（例如C++或Java），而添加新的混淆技术则是一个非平凡且劳动密集型的过程。在本研究中，我们提出以下问题：大型语言模型（LLMs）是否有可能生成新的混淆汇编代码？如果可以，这将给反病毒引擎带来风险，并可能增加攻击者创建新混淆模式的灵活性。我们通过开发包含MetamorphASM数据集（MAD）以及三种代码混淆技术（死代码、寄存器替换和控制流变化）的MetamorphASM基准来回答这个问题。MetamorphASM系统地评估了LLMs生成和分析混淆代码的能力，MAD包含328,200个不同的混淆汇编代码样本。我们发布了该数据集，并分析了各种LLMs（例如GPT-3.5/4、GPT-4o-mini、Starcoder、CodeGemma、CodeLlama、CodeT5和LLaMA 3.1）生成混淆汇编代码的成功率。评估使用了现有的信息论度量和人工手动审查来确保正确性，并为研究人员研究和开发相应的缓解措施提供了基础。源代码可以在以下GitHub链接中找到：this https URL。 

---
# Towards Interpretable Radiology Report Generation via Concept Bottlenecks using a Multi-Agentic RAG 

**Title (ZH)**: 通过多智能体RAG中的概念瓶颈实现可解释的放射学报告生成 

**Authors**: Hasan Md Tusfiqur Alam, Devansh Srivastav, Md Abdul Kadir, Daniel Sonntag  

**Link**: [PDF](https://arxiv.org/pdf/2412.16086)  

**Abstract**: Deep learning has advanced medical image classification, but interpretability challenges hinder its clinical adoption. This study enhances interpretability in Chest X-ray (CXR) classification by using concept bottleneck models (CBMs) and a multi-agent Retrieval-Augmented Generation (RAG) system for report generation. By modeling relationships between visual features and clinical concepts, we create interpretable concept vectors that guide a multi-agent RAG system to generate radiology reports, enhancing clinical relevance, explainability, and transparency. Evaluation of the generated reports using an LLM-as-a-judge confirmed the interpretability and clinical utility of our model's outputs. On the COVID-QU dataset, our model achieved 81% classification accuracy and demonstrated robust report generation performance, with five key metrics ranging between 84% and 90%. This interpretable multi-agent framework bridges the gap between high-performance AI and the explainability required for reliable AI-driven CXR analysis in clinical settings. 

**Abstract (ZH)**: 深度学习在医学图像分类方面取得了进展，但由于可解释性挑战，其在临床中的应用受到限制。本研究通过使用概念瓶颈模型（CBMs）和多代理检索增强生成（RAG）系统来增强胸部X射线（CXR）分类的可解释性。通过建模视觉特征与临床概念之间的关系，我们创建了可解释的概念向量，以指导多代理RAG系统生成放射学报告，从而增强临床相关性、可解释性和透明度。使用LLM作为评判者对生成的报告进行评估，证实了我们模型输出的可解释性和临床实用性。在COVID-QU数据集上，我们的模型实现了81%的分类准确性，并展示了稳健的报告生成性能，五个关键指标的范围在84%至90%之间。这种可解释的多代理框架在临床环境中弥合了高性能AI与所需可解释性之间的差距，促进了基于AI的CXR分析的可靠应用。 

---
# Align Anything: Training All-Modality Models to Follow Instructions with Language Feedback 

**Title (ZH)**: anything对齐：通过语言反馈训练多模态模型遵循指令 

**Authors**: Jiaming Ji, Jiayi Zhou, Hantao Lou, Boyuan Chen, Donghai Hong, Xuyao Wang, Wenqi Chen, Kaile Wang, Rui Pan, Jiahao Li, Mohan Wang, Josef Dai, Tianyi Qiu, Hua Xu, Dong Li, Weipeng Chen, Jun Song, Bo Zheng, Yaodong Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15838)  

**Abstract**: Reinforcement learning from human feedback (RLHF) has proven effective in enhancing the instruction-following capabilities of large language models; however, it remains underexplored in the cross-modality domain. As the number of modalities increases, aligning all-modality models with human intentions -- such as instruction following -- becomes a pressing challenge. In this work, we make the first attempt to fine-tune all-modality models (i.e. input and output with any modality, also named any-to-any models) using human preference data across all modalities (including text, image, audio, and video), ensuring its behavior aligns with human intentions. This endeavor presents several challenges. First, there is no large-scale all-modality human preference data in existing open-source resources, as most datasets are limited to specific modalities, predominantly text and image. Secondly, the effectiveness of binary preferences in RLHF for post-training alignment in complex all-modality scenarios remains an unexplored area. Finally, there is a lack of a systematic framework to evaluate the capabilities of all-modality models, particularly regarding modality selection and synergy. To address these challenges, we propose the align-anything framework, which includes meticulously annotated 200k all-modality human preference data. Then, we introduce an alignment method that learns from unified language feedback, effectively capturing complex modality-specific human preferences and enhancing the model's instruction-following capabilities. Furthermore, to assess performance improvements in all-modality models after post-training alignment, we construct a challenging all-modality capability evaluation framework -- eval-anything. All data, models, and code frameworks have been open-sourced for the community. For more details, please refer to this https URL. 

**Abstract (ZH)**: 强化学习领域的人类反馈（Reinforcement Learning from Human Feedback, RLHF）在提升大规模语言模型的指令遵循能力方面已证明是有效的；然而，在跨模态领域这一方法仍处于探索的早期阶段。随着模态数量的增加，将所有模态模型与人类意图（例如指令遵循）对齐成为一个紧迫的挑战。本研究首次尝试利用跨模态的大量人类偏好数据对任何模态输入和输出的模型（即输入和输出可以是任意模态，也称为任意到任意模型）进行微调，以确保其行为符合人类意图。这一努力带来了若干挑战。首先，在现有开源资源中缺乏大规模的跨模态人类偏好数据，因为大多数数据集仅限于特定模态，主要是文本和图像。其次，二元偏好在复杂跨模态场景下RLHF后训练对齐的有效性仍是一个未被探索的领域。最后，缺少一个系统性的框架来评估所有模态模型的能力，特别是模态选择和协同效应方面的能力。为了解决这些问题，我们提出了一种对齐任何事物（align-anything）框架，其中包括详细标注的200,000个跨模态人类偏好数据集。然后，我们引入了一种通过统一语言反馈进行对齐的方法，可以有效捕捉复杂的模态特定人类偏好，并增强模型的指令遵循能力。此外，为了评估跨模态模型在后训练对齐后的性能改进，我们构建了一个具有挑战性的跨模态能力评估框架（eval-anything）。所有数据、模型和代码框架均已开源给社区。更多详情请参阅此链接：https://

（注：翻译时保留了原文中的链接格式和引用格式，未提供具体的链接地址，实际使用时请替换为正确的链接。） 

---
# Enriching Social Science Research via Survey Item Linking 

**Title (ZH)**: 通过调查项目链接丰富社会科学研究 

**Authors**: Tornike Tsereteli, Daniel Ruffinelli, Simone Paolo Ponzetto  

**Link**: [PDF](https://arxiv.org/pdf/2412.15831)  

**Abstract**: Questions within surveys, called survey items, are used in the social sciences to study latent concepts, such as the factors influencing life satisfaction. Instead of using explicit citations, researchers paraphrase the content of the survey items they use in-text. However, this makes it challenging to find survey items of interest when comparing related work. Automatically parsing and linking these implicit mentions to survey items in a knowledge base can provide more fine-grained references. We model this task, called Survey Item Linking (SIL), in two stages: mention detection and entity disambiguation. Due to an imprecise definition of the task, existing datasets used for evaluating the performance for SIL are too small and of low-quality. We argue that latent concepts and survey item mentions should be differentiated. To this end, we create a high-quality and richly annotated dataset consisting of 20,454 English and German sentences. By benchmarking deep learning systems for each of the two stages independently and sequentially, we demonstrate that the task is feasible, but observe that errors propagate from the first stage, leading to a lower overall task performance. Moreover, mentions that require the context of multiple sentences are more challenging to identify for models in the first stage. Modeling the entire context of a document and combining the two stages into an end-to-end system could mitigate these problems in future work, and errors could additionally be reduced by collecting more diverse data and by improving the quality of the knowledge base. The data and code are available at this https URL . 

**Abstract (ZH)**: 在问卷调查中，称为问卷项目的问卷问题被社会科学家用来研究潜在概念，如影响生活满意度的因素。研究人员会在正文中对其进行改写而不是使用明确的引用。这使得在比较相关研究时难以找到感兴趣的问卷项目。通过自动解析和链接隐含提及到知识库中的问卷项目，可以提供更多具体的参考。我们将这项任务，称为问卷项目链接（SIL），分为两个阶段：提及检测和实体消歧。

由于任务定义不够精确，用于评估SIL性能的现有数据集较小且质量较低。我们认为潜在概念和问卷项目提及应区别开来。因此，我们创建了一个高质量且注释丰富的数据集，包含20,454个英文和德文句子。通过对每个阶段独立基准测试深度学习系统，我们证明了该任务是可行的，但也观察到错误在第一阶段传播，导致整体任务性能较低。另外，第一阶段的模型识别跨多个句子的提及更为困难。建模整个文档的上下文并结合两个阶段形成端到端系统可以在未来的工作中缓解这些问题，同时通过收集更多样化的数据并提高知识库的质量，还可以进一步减少错误。

数据和代码可在以下网址获取：[https://your-url-here.com](https://your-url-here.com) 

---
# S$^2$DN: Learning to Denoise Unconvincing Knowledge for Inductive Knowledge Graph Completion 

**Title (ZH)**: S$^2$DN：学习去噪不足的知識以完成归纳知识图谱 

**Authors**: Tengfei Ma, Yujie Chen, Liang Wang, Xuan Lin, Bosheng Song, Xiangxiang Zeng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15822)  

**Abstract**: Inductive Knowledge Graph Completion (KGC) aims to infer missing facts between newly emerged entities within knowledge graphs (KGs), posing a significant challenge. While recent studies have shown promising results in inferring such entities through knowledge subgraph reasoning, they suffer from (i) the semantic inconsistencies of similar relations, and (ii) noisy interactions inherent in KGs due to the presence of unconvincing knowledge for emerging entities. To address these challenges, we propose a Semantic Structure-aware Denoising Network (S$^2$DN) for inductive KGC. Our goal is to learn adaptable general semantics and reliable structures to distill consistent semantic knowledge while preserving reliable interactions within KGs. Specifically, we introduce a semantic smoothing module over the enclosing subgraphs to retain the universal semantic knowledge of relations. We incorporate a structure refining module to filter out unreliable interactions and offer additional knowledge, retaining robust structure surrounding target links. Extensive experiments conducted on three benchmark KGs demonstrate that S$^2$DN surpasses the performance of state-of-the-art models. These results demonstrate the effectiveness of S$^2$DN in preserving semantic consistency and enhancing the robustness of filtering out unreliable interactions in contaminated KGs. 

**Abstract (ZH)**: 归纳知识图谱完成（Inductive Knowledge Graph Completion, KGC）旨在推断知识图谱（KGs）中新出现实体之间的缺失事实，这是一项具有挑战性的任务。尽管最近的研究在通过知识子图推理来推断这些实体方面取得了有希望的结果，但它们仍然面临以下问题：（i）类似关系的语义不一致，以及（ii）由于KG中存在不可信的知识，使得相互作用变得嘈杂。为了解决这些问题，我们提出了一种语义结构感知的去噪网络（S$^2$DN）用于归纳KGC。我们的目标是在提取一致的语义知识的同时保留可靠结构，以学习适应性强的一般语义和可靠结构。具体而言，我们通过在包含的子图上引入语义平滑模块来保留关系的通用语义知识。我们还引入了一种结构精炼模块来过滤掉不可靠的相互作用并提供额外的知识，从而保留与目标链接周围的稳健结构。在三个基准KG上的广泛实验表明，S$^2$DN的性能超越了现有的最先进的模型。这些结果展示了S$^2$DN在保留语义一致性并增强筛选不可靠相互作用的稳健性方面的有效性。 

---
# AutoLife: Automatic Life Journaling with Smartphones and LLMs 

**Title (ZH)**: AutoLife：利用智能手机和大规模语言模型的自动生活记事 

**Authors**: Huatao Xu, Panron Tong, Mo Li, Mani Srivastava  

**Link**: [PDF](https://arxiv.org/pdf/2412.15714)  

**Abstract**: This paper introduces a novel mobile sensing application - life journaling - designed to generate semantic descriptions of users' daily lives. We present AutoLife, an automatic life journaling system based on commercial smartphones. AutoLife only inputs low-cost sensor data (without photos or audio) from smartphones and can automatically generate comprehensive life journals for users. To achieve this, we first derive time, motion, and location contexts from multimodal sensor data, and harness the zero-shot capabilities of Large Language Models (LLMs), enriched with commonsense knowledge about human lives, to interpret diverse contexts and generate life journals. To manage the task complexity and long sensing duration, a multilayer framework is proposed, which decomposes tasks and seamlessly integrates LLMs with other techniques for life journaling. This study establishes a real-life dataset as a benchmark and extensive experiment results demonstrate that AutoLife produces accurate and reliable life journals. 

**Abstract (ZH)**: 本文介绍了一种新颖的移动感知应用——生活记录，旨在生成用户日常生活的语义描述。我们提出了AutoLife，一个基于商业智能手机的自动生活记录系统。AutoLife仅需要输入手机的低成本传感器数据（不包括照片或音频），即可自动为用户生成全面的生活记录。为了实现这一点，我们首先从多模态传感器数据中提取时间、运动和位置上下文，并利用大型语言模型（LLMs）的零样本能力，结合关于人类生活的常识知识，来解释多样化的上下文并生成生活记录。为了管理和降低任务复杂性及长时间的感知需求，我们提出了一种多层框架，该框架将任务分解并与其他技术无缝集成，以实现生活记录功能。本研究建立了一个实际数据集作为基准，并通过广泛的实验结果证明了AutoLife能够生成准确可靠的生活记录。 

---
# Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration 

**Title (ZH)**: 协作 Gym：一个促进和评估人-代理协作的框架 

**Authors**: Yijia Shao, Vinay Samuel, Yucheng Jiang, John Yang, Diyi Yang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15701)  

**Abstract**: Recent advancements in language models (LMs) have sparked growing interest in developing LM agents. While fully autonomous agents could excel in many scenarios, numerous use cases inherently require them to collaborate with humans due to humans' latent preferences, domain expertise, or need for control. To facilitate the study of human-agent collaboration, we present Collaborative Gym (Co-Gym), a general framework enabling asynchronous, tripartite interaction among agents, humans, and task environments. We instantiate Co-Gym with three representative tasks in both simulated and real-world conditions, and propose an evaluation framework that assesses both the collaboration outcomes and processes. Our findings reveal that collaborative agents consistently outperform their fully autonomous counterparts in task performance within those delivered cases, achieving win rates of 86% in Travel Planning, 74% in Tabular Analysis, and 66% in Related Work when evaluated by real users. However, our study also highlights significant challenges in developing collaborative agents, requiring advancements in core aspects of intelligence -- communication capabilities, situational awareness, and balancing autonomy and human control. 

**Abstract (ZH)**: 近年来语言模型（LMs）的发展激发了对LM代理的研究兴趣。虽然完全自主的代理在许多场景中表现出色，但许多应用案例由于人类潜在的偏好、专业知识或控制需求，自然需要它们与人类协作。为了促进人机协作的研究，我们提出了协作健身房（Co-Gym），这是一种使代理、人类和任务环境能够在异步三元交互中协同工作的通用框架。我们通过模拟和真实世界条件下的三种代表性任务实例化了Co-Gym，并提出了一种评估框架，以评估合作结果和过程。我们的研究成果表明，在这些案例中，合作代理在任务性能上始终优于完全自主的代理，其中在旅行规划任务中达到了86%的胜率，在表格分析任务中达到了74%的胜率，在相关工作任务中达到了66%的胜率，这些评估结果来自于真实用户。然而，我们的研究也指出了开发协作代理面临的重大挑战，要求在核心智能方面取得进步——包括沟通能力、情境感知以及自主性和人类控制之间的平衡。 

---
# Adaptable and Precise: Enterprise-Scenario LLM Function-Calling Capability Training Pipeline 

**Title (ZH)**: 适配性强且精确度高：针对企业场景的LLM函数调用能力训练pipeline 

**Authors**: Guancheng Zeng, Wentao Ding, Beining Xu, Chi Zhang, Wenqiang Han, Gang Li, Jingjing Mo, Pengxu Qiu, Xinran Tao, Wang Tao, Haowen Hu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15660)  

**Abstract**: Enterprises possess a vast array of API assets scattered across various functions, forming the backbone of existing business processes. By leveraging these APIs as functional tools, enterprises can design diverse, scenario-specific agent applications, driven by on-premise function-calling models as the core engine. However, generic models often fail to meet enterprise requirements in terms of computational efficiency, output accuracy, and stability, necessitating scenario-specific adaptation. In this paper, we propose a training pipeline for function-calling capabilities tailored to real-world business scenarios. This pipeline includes the synthesis and augmentation of scenario-specific function-calling data, model fine-tuning, and performance evaluation and analysis. Using this pipeline, we generated 1,260 fully AI-generated samples and 1,035 augmented manually-labeled samples in digital HR agent scenario. The Qwen2.5-Coder-7B-Instruct model was employed as the base model and fine-tuned using the LoRA method on four GPUs with 24GB VRAM. Our fine-tuned model demonstrated outstanding performance in evaluations and practical applications, surpassing GPT-4 and GPT-4o in accuracy on the test set. These results validate the reliability of the proposed pipeline for training scenario-specific function-calling models. 

**Abstract (ZH)**: 企业内部存在分散在各项功能中的大量API资产，这些API构成了现有业务流程的核心。通过将这些API作为功能工具进行利用，企业可以设计出多种多样、针对特定场景的代理应用，这些应用的核心引擎基于本地调用函数的模型。然而，通用模型往往在计算效率、输出准确性和稳定性方面无法满足企业的需求，因此需要进行针对特定场景的适应。在本文中，我们提出了一种针对实际业务场景定制的函数调用能力训练管道。该管道包括生成和增强特定场景的函数调用数据、模型微调以及性能评估与分析。利用该管道，我们在数字人力资源代理场景中生成了1,260个完全由AI生成的样本和1,035个手动标注后增强的样本。我们使用Qwen2.5-Coder-7B-Instruct模型作为基础模型，并通过四块配备24GB VRAM的GPU采用LoRA方法进行了微调。我们微调后的模型在评估和实际应用中表现出色，在测试集上的准确率超过了GPT-4和GPT-4o。这些结果验证了所提出的针对特定场景的函数调用模型训练管道的可靠性。 

---
# TouchASP: Elastic Automatic Speech Perception that Everyone Can Touch 

**Title (ZH)**: TouchASP：弹性自动语音感知技术，让人们轻松触及 

**Authors**: Xingchen Song, Chengdong Liang, Binbin Zhang, Pengshen Zhang, ZiYu Wang, Youcheng Ma, Menglong Xu, Lin Wang, Di Wu, Fuping Pan, Dinghao Zhou, Zhendong Peng  

**Link**: [PDF](https://arxiv.org/pdf/2412.15622)  

**Abstract**: Large Automatic Speech Recognition (ASR) models demand a vast number of parameters, copious amounts of data, and significant computational resources during the training process. However, such models can merely be deployed on high-compute cloud platforms and are only capable of performing speech recognition tasks. This leads to high costs and restricted capabilities. In this report, we initially propose the elastic mixture of the expert (eMoE) model. This model can be trained just once and then be elastically scaled in accordance with deployment requirements. Secondly, we devise an unsupervised data creation and validation procedure and gather millions of hours of audio data from diverse domains for training. Using these two techniques, our system achieves elastic deployment capabilities while reducing the Character Error Rate (CER) on the SpeechIO testsets from 4.98\% to 2.45\%. Thirdly, our model is not only competent in Mandarin speech recognition but also proficient in multilingual, multi-dialect, emotion, gender, and sound event perception. We refer to this as Automatic Speech Perception (ASP), and the perception results are presented in the experimental section. 

**Abstract (ZH)**: 大型自动语音识别（ASR）模型在训练过程中需要大量的参数、数据和计算资源。然而，这些模型只能部署在高性能的云平台上，仅能执行语音识别任务。这会导致高昂的成本和有限的能力。在本报告中，我们首先提出了弹性专家混合模型（eMoE）。该模型只需一次性训练，然后可以根据部署需求弹性扩展。其次，我们设计了一种无监督的数据生成和验证流程，并从多个领域收集了数百万小时的音频数据用于训练。通过这两种技术，我们的系统实现了弹性部署能力，同时将SpeechIO测试集上的字符错误率（CER）从4.98%降低到了2.45%。此外，我们的模型不仅适用于 Mandarin 语音识别，还适用于多语言、多方言、情感、性别和声学事件感知。我们将这一技术称为自动语音感知（ASP），并将在实验部分展示感知结果。 

---
# Continual Learning Using a Kernel-Based Method Over Foundation Models 

**Title (ZH)**: 使用内核方法的基础模型连续学习 

**Authors**: Saleh Momeni, Sahisnu Mazumder, Bing Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15571)  

**Abstract**: Continual learning (CL) learns a sequence of tasks incrementally. This paper studies the challenging CL setting of class-incremental learning (CIL). CIL has two key challenges: catastrophic forgetting (CF) and inter-task class separation (ICS). Despite numerous proposed methods, these issues remain persistent obstacles. This paper proposes a novel CIL method, called Kernel Linear Discriminant Analysis (KLDA), that can effectively avoid CF and ICS problems. It leverages only the powerful features learned in a foundation model (FM). However, directly using these features proves suboptimal. To address this, KLDA incorporates the Radial Basis Function (RBF) kernel and its Random Fourier Features (RFF) to enhance the feature representations from the FM, leading to improved performance. When a new task arrives, KLDA computes only the mean for each class in the task and updates a shared covariance matrix for all learned classes based on the kernelized features. Classification is performed using Linear Discriminant Analysis. Our empirical evaluation using text and image classification datasets demonstrates that KLDA significantly outperforms baselines. Remarkably, without relying on replay data, KLDA achieves accuracy comparable to joint training of all classes, which is considered the upper bound for CIL performance. The KLDA code is available at this https URL. 

**Abstract (ZH)**: 连续学习（CL）能够增量地学习一系列任务。本文研究了类增量学习（CIL）这一具有挑战性的连续学习设置。CIL面临两个主要挑战：灾难性遗忘（CF）和任务间类别分离（ICS）。尽管已经提出了许多方法，但这些问题仍然是一大障碍。本文提出了一种新的CIL方法，称为核线性判别分析（KLDA），该方法能够有效避免CF和ICS问题。KLDA仅利用基础模型（FM）中学习的强大特征，但直接使用这些特征效果并不理想。为了解决这一问题，KLDA引入了径向基函数（RBF）核及其随机傅里叶特征（RFF），以增强FM提供的特征表示，从而提高性能。当新任务到来时，KLDA仅计算每个类别的均值，并基于核特征更新所有已学习类别的共享协方差矩阵。分类过程使用线性判别分析进行。我们使用文本和图像分类数据集的实验评估表明，KLDA显著优于 baselines。更令人印象深刻的是，KLDA不依赖于重放数据，其准确率与所有类别的联合训练相当，这被认为是CIL性能的上限。KLDA的代码可在以下链接获取：[这里提供链接]。

请注意，您提供的文本末尾有一个“this https URL”，而实际的链接内容未给出，因此在中文翻译中需要用“[这里提供链接]”来代替。您可以根据实际情况插入具体的链接地址。 

---
# MORTAR: Metamorphic Multi-turn Testing for LLM-based Dialogue Systems 

**Title (ZH)**: MORTAR：变倍式多轮测试方法用于基于LLM的对话系统 

**Authors**: Guoxiang Guo, Aldeida Aleti, Neelofar Neelofar, Chakkrit Tantithamthavorn  

**Link**: [PDF](https://arxiv.org/pdf/2412.15557)  

**Abstract**: With the widespread application of LLM-based dialogue systems in daily life, quality assurance has become more important than ever. Recent research has successfully introduced methods to identify unexpected behaviour in single-turn scenarios. However, multi-turn dialogue testing remains underexplored, with the Oracle problem in multi-turn testing posing a persistent challenge for dialogue system developers and researchers. In this paper, we propose MORTAR, a MetamORphic multi-TuRn diAlogue testing appRoach, which mitigates the test oracle problem in the assessment of LLM-based dialogue systems. MORTAR automates the generation of follow-up question-answer (QA) dialogue test cases with multiple dialogue-level perturbations and metamorphic relations. MORTAR employs a novel knowledge graph-based dialogue information model which effectively generates perturbed dialogue test datasets and detects bugs of multi-turn dialogue systems in a low-cost manner. The proposed approach does not require an LLM as a judge, eliminating potential of any biases in the evaluation step. According to the experiment results on multiple LLM-based dialogue systems and comparisons with single-turn metamorphic testing approaches, MORTAR explores more unique bugs in LLM-based dialogue systems, especially for severe bugs that MORTAR detects up to four times more unique bugs than the most effective existing metamorphic testing approach. 

**Abstract (ZH)**: 随着基于大语言模型（LLM）的对话系统在日常生活中的广泛应用，质量保证变得比以往任何时候都更加重要。最近的研究成功引入了识别单轮场景中意外行为的方法。然而，多轮对话测试仍处于探索阶段，并且在多轮测试中存在一个持续性的挑战——Oracle问题，这给对话系统开发人员和研究者带来了困难。本文提出了一种名为MORTAR的元Q反演变式多轮对话测试方法，该方法在评估基于LLM的对话系统时减轻了测试Oracle问题。MORTAR自动生成具有多轮对话级扰动和元变换关系的后续问题-答案（QA）对话测试案例。MORTAR采用一种基于知识图谱的对话信息模型，可以有效地生成扰动对话测试数据集，并以低成本的方式检测多轮对话系统的故障。该方法不需要使用LLM作为评判标准，消除了评估步骤中的任何偏差可能性。根据在多个基于LLM的对话系统上的实验结果和与单轮元变换测试方法的比较，MORTAR在基于LLM的对话系统中发现更多独特的bug，尤其是MORTAR检测到的更为严重的bug，相比目前最有效的现有元变换测试方法，MORTAR能检测到的唯一bug多四倍。 

---
# TalkWithMachines: Enhancing Human-Robot Interaction for Interpretable Industrial Robotics Through Large/Vision Language Models 

**Title (ZH)**: TalkWithMachines：通过大型/视觉语言模型增强具有可解释性的工业机器人交互 

**Authors**: Ammar N. Abbas, Csaba Beleznai  

**Link**: [PDF](https://arxiv.org/pdf/2412.15462)  

**Abstract**: TalkWithMachines aims to enhance human-robot interaction by contributing to interpretable industrial robotic systems, especially for safety-critical applications. The presented paper investigates recent advancements in Large Language Models (LLMs) and Vision Language Models (VLMs), in combination with robotic perception and control. This integration allows robots to understand and execute commands given in natural language and to perceive their environment through visual and/or descriptive inputs. Moreover, translating the LLM's internal states and reasoning into text that humans can easily understand ensures that operators gain a clearer insight into the robot's current state and intentions, which is essential for effective and safe operation. Our paper outlines four LLM-assisted simulated robotic control workflows, which explore (i) low-level control, (ii) the generation of language-based feedback that describes the robot's internal states, (iii) the use of visual information as additional input, and (iv) the use of robot structure information for generating task plans and feedback, taking the robot's physical capabilities and limitations into account. The proposed concepts are presented in a set of experiments, along with a brief discussion. Project description, videos, and supplementary materials will be available on the project website: this https URL. 

**Abstract (ZH)**: TalkWithMachines旨在通过贡献可解释的工业机器人系统来提升人机交互，特别是在安全关键应用领域。本论文探讨了大型语言模型（LLMs）和视觉语言模型（VLMs）的最新进展，并将其与机器人的感知和控制相结合。这种集成使得机器人能够理解并执行自然语言指令，并通过视觉和/或描述性输入感知其环境。此外，将LLM的内部状态和推理转换为人类易于理解的文本，使操作员更好地了解机器人当前的状态和意图，这对于有效的安全操作至关重要。本文概述了四种基于LLM的模拟机器人控制工作流，这些工作流涵盖了（i）低级控制、（ii）基于语言的反馈生成，描述机器人的内部状态，（iii）使用视觉信息作为额外输入，以及（iv）结合机器人的结构信息生成任务计划和反馈，考虑到机器人的物理能力和限制。所提出的概念在一系列实验中进行了展示，并附有简要讨论。项目描述、视频和补充材料可在项目网站上获取：this https URL。 

---
# Time Will Tell: Timing Side Channels via Output Token Count in Large Language Models 

**Title (ZH)**: 时间会证明一切：通过大型语言模型的输出token数量进行定时侧信道攻击 

**Authors**: Tianchen Zhang, Gururaj Saileshwar, David Lie  

**Link**: [PDF](https://arxiv.org/pdf/2412.15431)  

**Abstract**: This paper demonstrates a new side-channel that enables an adversary to extract sensitive information about inference inputs in large language models (LLMs) based on the number of output tokens in the LLM response. We construct attacks using this side-channel in two common LLM tasks: recovering the target language in machine translation tasks and recovering the output class in classification tasks. In addition, due to the auto-regressive generation mechanism in LLMs, an adversary can recover the output token count reliably using a timing channel, even over the network against a popular closed-source commercial LLM. Our experiments show that an adversary can learn the output language in translation tasks with more than 75% precision across three different models (Tower, M2M100, MBart50). Using this side-channel, we also show the input class in text classification tasks can be leaked out with more than 70% precision from open-source LLMs like Llama-3.1, Llama-3.2, Gemma2, and production models like GPT-4o. Finally, we propose tokenizer-, system-, and prompt-based mitigations against the output token count side-channel. 

**Abstract (ZH)**: 本文展示了一种新的侧信道，它使攻击者能够在大型语言模型（LLMs）的响应中根据生成的输出令牌数量提取关于推理输入的敏感信息。我们使用这种侧信道构造了两种常见LLM任务的攻击：在机器翻译任务中恢复目标语言，在分类任务中恢复输出类别。此外，由于LLMs中的自回归生成机制，即使是在网络上对流行的封闭源商业LLM进行攻击时，攻击者也可以通过时间信道可靠地恢复输出令牌数量。我们的实验表明，攻击者可以通过三个不同模型（Tower、M2M100、MBart50）在超过75%的精度下学习翻译任务的输出语言。通过这种方法，我们还展示了可以从开源LLM（如Llama-3.1、Llama-3.2、Gemma2以及生产模型如GPT-4o）的文本分类任务中以超过70%的精度泄露输入类别。最后，我们提出了针对输出令牌数量侧信道的基于分词器、系统和提示的缓解措施。 

---
# Transcribing and Translating, Fast and Slow: Joint Speech Translation and Recognition 

**Title (ZH)**: 快速与缓慢并行：联合语音翻译与识别 

**Authors**: Niko Moritz, Ruiming Xie, Yashesh Gaur, Ke Li, Simone Merello, Zeeshan Ahmed, Frank Seide, Christian Fuegen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15415)  

**Abstract**: We propose the joint speech translation and recognition (JSTAR) model that leverages the fast-slow cascaded encoder architecture for simultaneous end-to-end automatic speech recognition (ASR) and speech translation (ST). The model is transducer-based and uses a multi-objective training strategy that optimizes both ASR and ST objectives simultaneously. This allows JSTAR to produce high-quality streaming ASR and ST results. We apply JSTAR in a bilingual conversational speech setting with smart-glasses, where the model is also trained to distinguish speech from different directions corresponding to the wearer and a conversational partner. Different model pre-training strategies are studied to further improve results, including training of a transducer-based streaming machine translation (MT) model for the first time and applying it for parameter initialization of JSTAR. We demonstrate superior performances of JSTAR compared to a strong cascaded ST model in both BLEU scores and latency. 

**Abstract (ZH)**: 我们提出了一种联合语音翻译与识别（JSTAR）模型，该模型利用快慢级联编码器架构实现了端到端的同步自动语音识别（ASR）和语音翻译（ST）。该模型基于翻译模型，并采用多目标训练策略，同时优化ASR和ST的目标。这使得JSTAR能够产生高质量的流式ASR和ST结果。我们在使用智能眼镜的双语对话场景中应用了JSTAR，模型还被训练用于区分来自佩戴者和对话伙伴的不同方向的语音。我们研究了不同的模型预训练策略以进一步提高性能，包括首次训练基于翻译模型的流式机器翻译（MT）模型，并将其应用于JSTAR的参数初始化。我们证明了在BLEU分数和延迟方面，JSTAR在评测比强级联ST模型时表现更优。 

---
# Learning Visual Composition through Improved Semantic Guidance 

**Title (ZH)**: 通过增强语义指导学习视觉 composition 

**Authors**: Austin Stone, Hagen Soltau, Robert Geirhos, Xi Yi, Ye Xia, Bingyi Cao, Kaifeng Chen, Abhijit Ogale, Jonathon Shlens  

**Link**: [PDF](https://arxiv.org/pdf/2412.15396)  

**Abstract**: Visual imagery does not consist of solitary objects, but instead reflects the composition of a multitude of fluid concepts. While there have been great advances in visual representation learning, such advances have focused on building better representations for a small number of discrete objects bereft of an understanding of how these objects are interacting. One can observe this limitation in representations learned through captions or contrastive learning -- where the learned model treats an image essentially as a bag of words. Several works have attempted to address this limitation through the development of bespoke learned architectures to directly address the shortcomings in compositional learning. In this work, we focus on simple, and scalable approaches. In particular, we demonstrate that by substantially improving weakly labeled data, i.e. captions, we can vastly improve the performance of standard contrastive learning approaches. Previous CLIP models achieved near chance rate on challenging tasks probing compositional learning. However, our simple approach boosts performance of CLIP substantially and surpasses all bespoke architectures. Furthermore, we showcase our results on a relatively new captioning benchmark derived from DOCCI. We demonstrate through a series of ablations that a standard CLIP model trained with enhanced data may demonstrate impressive performance on image retrieval tasks. 

**Abstract (ZH)**: 视觉表象并非由孤立的对象组成，而是反映了多种流动概念的组成。虽然在视觉表示学习方面取得了巨大的进展，但这些进展主要集中在构建更好的表示，这些表示针对的是少量孤立的对象，而不理解这些对象是如何相互作用的。这种局限性在通过字幕或对比学习获得的表示中可以观察到——这些学到的模型基本上将图像视为词语集合。一些研究工作试图通过开发特制的学习架构来解决这种局限性，直接针对组成学习的短coming。在这项工作中，我们专注于简单且可扩展的方法。特别是，我们证明通过大幅改进未严格标注的数据（即字幕），可以显著提高标准对比学习方法的性能。先前的CLIP模型在挑战性的组成学习任务中仅达到了接近随机猜测的水平。然而，我们简单的方法显著提升了CLIP的性能，并超越了所有特制的架构。此外，我们在来自DOCCI的一个相对较新的字幕基准测试中展示了我们的结果。通过一系列消融实验，我们证明了一个使用增强数据训练的标准CLIP模型在图像检索任务中可能表现出令人印象深刻的表现。 

---
# SATA: A Paradigm for LLM Jailbreak via Simple Assistive Task Linkage 

**Title (ZH)**: SATA：通过简单辅助任务链接的大型语言模型脱管范式 

**Authors**: Xiaoning Dong, Wenbo Hu, Wei Xu, Tianxing He  

**Link**: [PDF](https://arxiv.org/pdf/2412.15289)  

**Abstract**: Large language models (LLMs) have made significant advancements across various tasks, but their safety alignment remain a major concern. Exploring jailbreak prompts can expose LLMs' vulnerabilities and guide efforts to secure them. Existing methods primarily design sophisticated instructions for the LLM to follow, or rely on multiple iterations, which could hinder the performance and efficiency of jailbreaks. In this work, we propose a novel jailbreak paradigm, Simple Assistive Task Linkage (SATA), which can effectively circumvent LLM safeguards and elicit harmful responses. Specifically, SATA first masks harmful keywords within a malicious query to generate a relatively benign query containing one or multiple [MASK] special tokens. It then employs a simple assistive task such as a masked language model task or an element lookup by position task to encode the semantics of the masked keywords. Finally, SATA links the assistive task with the masked query to jointly perform the jailbreak. Extensive experiments show that SATA achieves state-of-the-art performance and outperforms baselines by a large margin. Specifically, on AdvBench dataset, with mask language model (MLM) assistive task, SATA achieves an overall attack success rate (ASR) of 85% and harmful score (HS) of 4.57, and with element lookup by position (ELP) assistive task, SATA attains an overall ASR of 76% and HS of 4.43. 

**Abstract (ZH)**: 大型语言模型（LLMs）在各种任务方面取得了显著进展，但其安全性对齐仍然是一个主要问题。探索恶意提示可以揭示LLMs的安全漏洞，并为保护它们的努力提供指导。现有方法主要设计复杂的指令供LLM遵循，或者依赖于多次迭代，这可能会妨碍恶意提示的有效性和效率。在本项工作中，我们提出了一个新颖的恶意提示范式，即简单辅助任务链接（SATA），它可以有效地规避LLMs的安全机制并引发有害响应。具体而言，SATA 首先在恶意查询中掩蔽有害关键词，生成一个相对无害但包含一个或多个[MASK]特殊标记的查询。它然后采用简单的辅助任务（例如掩蔽语言模型任务或按位置查找元素任务）来编码掩蔽关键词的语义。最后，SATA 将辅助任务与掩蔽查询链接起来，共同执行恶意提示。广泛的实验表明，SATA 达到了最先进的性能，并在多个基准上显著优于基线。具体而言，在AdvBench数据集上，使用掩蔽语言模型（MLM）辅助任务时，SATA的整体攻击成功率（ASR）为85%，有害得分为4.57；使用按位置查找元素（ELP）辅助任务时，SATA的整体ASR为76%，有害得分为4.43。 

---
# Fooling LLM graders into giving better grades through neural activity guided adversarial prompting 

**Title (ZH)**: 通过神经活动引导的对抗提示欺骗LLM评分器给出更高的评分 

**Authors**: Atsushi Yamamura, Surya Ganguli  

**Link**: [PDF](https://arxiv.org/pdf/2412.15275)  

**Abstract**: The deployment of artificial intelligence (AI) in critical decision-making and evaluation processes raises concerns about inherent biases that malicious actors could exploit to distort decision outcomes. We propose a systematic method to reveal such biases in AI evaluation systems and apply it to automated essay grading as an example. Our approach first identifies hidden neural activity patterns that predict distorted decision outcomes and then optimizes an adversarial input suffix to amplify such patterns. We demonstrate that this combination can effectively fool large language model (LLM) graders into assigning much higher grades than humans would. We further show that this white-box attack transfers to black-box attacks on other models, including commercial closed-source models like Gemini. They further reveal the existence of a "magic word" that plays a pivotal role in the efficacy of the attack. We trace the origin of this magic word bias to the structure of commonly-used chat templates for supervised fine-tuning of LLMs and show that a minor change in the template can drastically reduce the bias. This work not only uncovers vulnerabilities in current LLMs but also proposes a systematic method to identify and remove hidden biases, contributing to the goal of ensuring AI safety and security. 

**Abstract (ZH)**: 将人工智能（AI）应用于关键决策和评估过程中，引发了关于恶意行为者可能利用内在偏见来扭曲决策结果的担忧。我们提出了一种系统性方法，用于揭示AI评估系统中的这些偏见，并通过自动作文评分作为示例进行应用。该方法首先识别出能预测扭曲决策结果的隐藏神经活动模式，然后优化一个对抗性输入后缀以放大这些模式。我们证明了这种结合可以有效地欺骗大型语言模型（LLM）评分者，使其给出远高于人工评分的分数。此外，我们还展示了这种白盒攻击可以转移到其他模型的黑盒攻击上，包括像Gemini这样的商业封闭源代码模型。这一过程进一步揭示了一个“魔术单词”的存在，该单词在攻击的有效性中起着关键作用。我们追踪了这一魔术单词偏见的起源，发现其与监督微调大型语言模型时常用对话模板的结构密切相关，并表明模板中微小的更改可以大幅减少这种偏见。本研究不仅揭示了当前大型语言模型中存在的漏洞，还提出了一种系统方法来识别并移除隐藏偏见，从而有助于确保人工智能的安全性和安全性。 

---
# Do Voters Get the Information They Want? Understanding Authentic Voter FAQs in the US and How to Improve for Informed Electoral Participation 

**Title (ZH)**: 选民是否获得了他们想要的信息？理解美国的 authentic 投票常见问题及其改进方法以促进知情选举参与 

**Authors**: Vipula Rawte, Deja N Scott, Gaurav Kumar, Aishneet Juneja, Bharat Sowrya Yaddanapalli, Biplav Srivastava  

**Link**: [PDF](https://arxiv.org/pdf/2412.15273)  

**Abstract**: Accurate information is crucial for democracy as it empowers voters to make informed decisions about their representatives and keeping them accountable. In the US, state election commissions (SECs), often required by law, are the primary providers of Frequently Asked Questions (FAQs) to voters, and secondary sources like non-profits such as League of Women Voters (LWV) try to complement their information shortfall. However, surprisingly, to the best of our knowledge, there is neither a single source with comprehensive FAQs nor a study analyzing the data at national level to identify current practices and ways to improve the status quo. This paper addresses it by providing the {\bf first dataset on Voter FAQs covering all the US states}. Second, we introduce metrics for FAQ information quality (FIQ) with respect to questions, answers, and answers to corresponding questions. Third, we use FIQs to analyze US FAQs to identify leading, mainstream and lagging content practices and corresponding states. Finally, we identify what states across the spectrum can do to improve FAQ quality and thus, the overall information ecosystem. Across all 50 U.S. states, 12% were identified as leaders and 8% as laggards for FIQS\textsubscript{voter}, while 14% were leaders and 12% laggards for FIQS\textsubscript{developer}. 

**Abstract (ZH)**: 准确的信息对于民主至关重要，因为它赋予选民权力建立关于代表的信息，并使其能够对其代表进行问责。在美国，根据法律要求，州选举委员会（SECs）通常是为选民提供常见问题解答（FAQs）的主要来源，而诸如妇女选民联盟（LWV）这样的非盈利组织则试图补充信息空白。然而，据我们所知，目前既没有涵盖所有州的全面FAQ来源，也没有任何全国性的研究来分析数据，以确定当前的做法并找出改进现状的方法。本文通过提供**首个涵盖所有美国州份的选民FAQ数据集**来解决这一问题。其次，我们引入了针对问题、答案以及对应问题的解答的FAQ信息质量（FIQ）的度量标准。第三，我们使用FIQ来分析美国的FAQs，以确定领先、主流和落后的内容实践及其对应的州份。最后，我们确定了不同州份可以采取的措施，以提高FAQ质量，从而改善整体信息生态系统。在所有50个美国州中，12%的州被评为FIQS\textsubscript{voter}的领先者，8%被评为落后者，而14%的州被评为FIQS\textsubscript{developer}的领先者，12%的州被评为落后者。 

---
# Toxicity Detection towards Adaptability to Changing Perturbations 

**Title (ZH)**: 适应变化扰动的毒性检测 

**Authors**: Hankun Kang, Jianhao Chen, Yongqi Li, Xin Miao, Mayi Xu, Ming Zhong, Yuanyuan Zhu, Tieyun Qian  

**Link**: [PDF](https://arxiv.org/pdf/2412.15267)  

**Abstract**: Toxicity detection is crucial for maintaining the peace of the society. While existing methods perform well on normal toxic contents or those generated by specific perturbation methods, they are vulnerable to evolving perturbation patterns. However, in real-world scenarios, malicious users tend to create new perturbation patterns for fooling the detectors. For example, some users may circumvent the detector of large language models (LLMs) by adding `I am a scientist' at the beginning of the prompt. In this paper, we introduce a novel problem, i.e., continual learning jailbreak perturbation patterns, into the toxicity detection field. To tackle this problem, we first construct a new dataset generated by 9 types of perturbation patterns, 7 of them are summarized from prior work and 2 of them are developed by us. We then systematically validate the vulnerability of current methods on this new perturbation pattern-aware dataset via both the zero-shot and fine tuned cross-pattern detection. Upon this, we present the domain incremental learning paradigm and the corresponding benchmark to ensure the detector's robustness to dynamically emerging types of perturbed toxic text. Our code and dataset are provided in the appendix and will be publicly available at GitHub, by which we wish to offer new research opportunities for the security-relevant communities. 

**Abstract (ZH)**: 毒性检测对于维护社会和平至关重要。虽然现有的方法在正常毒性内容或特定扰动方法生成的内容上表现良好，但它们对不断演变的扰动模式较为脆弱。然而，在现实场景中，恶意用户往往会创造新的扰动模式来欺骗检测器。例如，一些用户可能会通过在其提示的开头加上“我是科学家”来绕过大型语言模型（LLMs）的检测器。在本文中，我们引入了一个新的问题，即持续学习逃逸扰动模式，将其纳入毒性检测领域。为了解决这一问题，我们首先构建了一个由9种不同类型扰动模式生成的新数据集，其中7种源自先前的工作，2种是我们自行开发的。然后，我们通过零样本检测和微调跨模式检测系统地验证了当前方法在这一新扰动模式数据集上的脆弱性。在此基础上，我们提出了领域增量学习范式及其相应的基准，以确保检测器在动态出现的各种形式的扰动有毒文本方面的鲁棒性。我们已在附录中提供了代码和数据集，并将在GitHub上公开，希望能为相关安全社区提供新的研究机会。 

---
# Early Dementia Detection Using Multiple Spontaneous Speech Prompts: The PROCESS Challenge 

**Title (ZH)**: 使用多种自发语音提示进行早期痴呆症检测：PROCESS 挑战 

**Authors**: Fuxiang Tao, Bahman Mirheidari, Madhurananda Pahar, Sophie Young, Yao Xiao, Hend Elghazaly, Fritz Peters, Caitlin Illingworth, Dorota Braun, Ronan O'Malley, Simon Bell, Daniel Blackburn, Fasih Haider, Saturnino Luz, Heidi Christensen  

**Link**: [PDF](https://arxiv.org/pdf/2412.15230)  

**Abstract**: Dementia is associated with various cognitive impairments and typically manifests only after significant progression, making intervention at this stage often ineffective. To address this issue, the Prediction and Recognition of Cognitive Decline through Spontaneous Speech (PROCESS) Signal Processing Grand Challenge invites participants to focus on early-stage dementia detection. We provide a new spontaneous speech corpus for this challenge. This corpus includes answers from three prompts designed by neurologists to better capture the cognition of speakers. Our baseline models achieved an F1-score of 55.0% on the classification task and an RMSE of 2.98 on the regression task. 

**Abstract (ZH)**: 痴呆与多种认知障碍相关，且通常在显著进展后才表现出症状，这使得在这一阶段进行干预往往无效。为解决这一问题，自发言语预测与识别认知下降的PROCESS信号处理挑战赛邀请参赛者聚焦于早期痴呆症检测。我们为此挑战提供了一个新的自发言语语料库。该语料库包含神经学家设计的三个提示的回答，以更好地捕捉发言者的能力情况。我们的基线模型在分类任务上的F1值达到55.0%，在回归任务上的均方根误差为2.98。 

---