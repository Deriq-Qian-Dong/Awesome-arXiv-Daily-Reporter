# Fooling LLM graders into giving better grades through neural activity guided adversarial prompting 

**Title (ZH)**: 通过神经活动引导的对抗提示欺骗LLM评分器给出更高的评分 

**Authors**: Atsushi Yamamura, Surya Ganguli  

**Link**: [PDF](https://arxiv.org/pdf/2412.15275)  

**Abstract**: The deployment of artificial intelligence (AI) in critical decision-making and evaluation processes raises concerns about inherent biases that malicious actors could exploit to distort decision outcomes. We propose a systematic method to reveal such biases in AI evaluation systems and apply it to automated essay grading as an example. Our approach first identifies hidden neural activity patterns that predict distorted decision outcomes and then optimizes an adversarial input suffix to amplify such patterns. We demonstrate that this combination can effectively fool large language model (LLM) graders into assigning much higher grades than humans would. We further show that this white-box attack transfers to black-box attacks on other models, including commercial closed-source models like Gemini. They further reveal the existence of a "magic word" that plays a pivotal role in the efficacy of the attack. We trace the origin of this magic word bias to the structure of commonly-used chat templates for supervised fine-tuning of LLMs and show that a minor change in the template can drastically reduce the bias. This work not only uncovers vulnerabilities in current LLMs but also proposes a systematic method to identify and remove hidden biases, contributing to the goal of ensuring AI safety and security. 

**Abstract (ZH)**: 将人工智能（AI）应用于关键决策和评估过程中，引发了关于恶意行为者可能利用内在偏见来扭曲决策结果的担忧。我们提出了一种系统性方法，用于揭示AI评估系统中的这些偏见，并通过自动作文评分作为示例进行应用。该方法首先识别出能预测扭曲决策结果的隐藏神经活动模式，然后优化一个对抗性输入后缀以放大这些模式。我们证明了这种结合可以有效地欺骗大型语言模型（LLM）评分者，使其给出远高于人工评分的分数。此外，我们还展示了这种白盒攻击可以转移到其他模型的黑盒攻击上，包括像Gemini这样的商业封闭源代码模型。这一过程进一步揭示了一个“魔术单词”的存在，该单词在攻击的有效性中起着关键作用。我们追踪了这一魔术单词偏见的起源，发现其与监督微调大型语言模型时常用对话模板的结构密切相关，并表明模板中微小的更改可以大幅减少这种偏见。本研究不仅揭示了当前大型语言模型中存在的漏洞，还提出了一种系统方法来识别并移除隐藏偏见，从而有助于确保人工智能的安全性和安全性。 

---