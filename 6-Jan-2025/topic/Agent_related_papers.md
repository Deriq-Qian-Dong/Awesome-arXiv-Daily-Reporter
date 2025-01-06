# MIRAGE: Exploring How Large Language Models Perform in Complex Social Interactive Environments 

**Title (ZH)**: MIRAGE：探索大型语言模型在复杂社会互动环境中的表现 

**Authors**: Cai Yin, Gu Zhouhong, Du Zhaohan, Ye Zheyu, Cao Shaosheng, Xu Yiqian, Feng Hongwei, Chen Ping  

**Link**: [PDF](https://arxiv.org/pdf/2501.01652)  

**Abstract**: Large Language Models (LLMs) have shown remarkable capabilities in environmental perception, reasoning-based decision-making, and simulating complex human behaviors, particularly in interactive role-playing contexts. This paper introduces the Multiverse Interactive Role-play Ability General Evaluation (MIRAGE), a comprehensive framework designed to assess LLMs' proficiency in portraying advanced human behaviors through murder mystery games. MIRAGE features eight intricately crafted scripts encompassing diverse themes and styles, providing a rich simulation. To evaluate LLMs' performance, MIRAGE employs four distinct methods: the Trust Inclination Index (TII) to measure dynamics of trust and suspicion, the Clue Investigation Capability (CIC) to measure LLMs' capability of conducting information, the Interactivity Capability Index (ICI) to assess role-playing capabilities and the Script Compliance Index (SCI) to assess LLMs' capability of understanding and following instructions. Our experiments indicate that even popular models like GPT-4 face significant challenges in navigating the complexities presented by the MIRAGE. The datasets and simulation codes are available in \href{this https URL}{github}. 

**Abstract (ZH)**: 大型语言模型（LLMs）在环境感知、基于推理的决策制定以及模拟复杂的人类行为方面展示了显著的能力，尤其是在互动角色扮演的语境中。本文介绍了多维互动角色扮演能力通用评估框架（MIRAGE），这是一个全面的框架，旨在通过谋杀谜题游戏评估LLMs在呈现高级人类行为方面的 proficiency。

MIRAGE 包含八个精密编撰的脚本，涵盖不同的主题和风格，提供了丰富的模拟环境。为了评估LLMs的表现，MIRAGE 使用了四种不同的方法：信任倾向指数（TII）用于衡量信任和疑虑的动力学过程，线索调查能力（CIC）用于衡量LLMs的线索调查能力，互动能力指数（ICI）用于评估角色扮演能力，脚本遵从指数（SCI）用于评估LLMs理解并遵循指令的能力。我们的实验表明，即使是流行模型如GPT-4，在应对MIRAGE 提出的复杂性时也面临重大挑战。

实验数据和模拟代码可在 \href{https://github.com/...}{GitHub} 获取。 

---
# PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents 

**Title (ZH)**: PSYCHE：一种多维度患者模拟框架，用于评估心理健康评估对话代理系统 

**Authors**: Jingoo Lee, Kyungho Lim, Young-Chul Jung, Byung-Hoon Kim  

**Link**: [PDF](https://arxiv.org/pdf/2501.01594)  

**Abstract**: Recent advances in large language models (LLMs) have accelerated the development of conversational agents capable of generating human-like responses. Since psychiatric assessments typically involve complex conversational interactions between psychiatrists and patients, there is growing interest in developing LLM-based psychiatric assessment conversational agents (PACAs) that aim to simulate the role of psychiatrists in clinical evaluations. However, standardized methods for benchmarking the clinical appropriateness of PACAs' interaction with patients still remain underexplored. Here, we propose PSYCHE, a novel framework designed to enable the 1) clinically relevant, 2) ethically safe, 3) cost-efficient, and 4) quantitative evaluation of PACAs. This is achieved by simulating psychiatric patients based on a multi-faceted psychiatric construct that defines the simulated patients' profiles, histories, and behaviors, which PACAs are expected to assess. We validate the effectiveness of PSYCHE through a study with 10 board-certified psychiatrists, supported by an in-depth analysis of the simulated patient utterances. 

**Abstract (ZH)**: 近年来，大规模语言模型（LLMs）的发展加速了能够生成人类般响应的对话代理的开发。由于精神疾病的评估通常涉及精神科医生与患者之间的复杂对话互动，因此业界对基于LLM的精神疾病评估对话代理（PACAs）产生了日益浓厚的兴趣。这些代理旨在模拟精神科医生在临床评估中的角色。然而，对于评估PACAs与患者交互的临床适当性的标准化方法仍较少探索。在此，我们提出PSYCHE，这是一个创新框架，旨在实现1）临床相关，2）伦理安全，3）成本效益高，以及4）定量的PACAs评估。这通过基于多维度的心理疾病构建体来模拟患者的画像、历史和行为来实现，PACAs被期望对其进行评估。我们通过一项涉及10名认证精神科医生的研究，并结合对模拟患者话语的深入分析，验证了PSYCHE的有效性。 

---
# SDPO: Segment-Level Direct Preference Optimization for Social Agents 

**Title (ZH)**: SDPO：社会智能体的段级直接偏好优化 

**Authors**: Aobo Kong, Wentao Ma, Shiwan Zhao, Yongbin Li, Yuchuan Wu, Ke Wang, Xiaoqian Liu, Qicheng Li, Yong Qin, Fei Huang  

**Link**: [PDF](https://arxiv.org/pdf/2501.01821)  

**Abstract**: Social agents powered by large language models (LLMs) can simulate human social behaviors but fall short in handling complex goal-oriented social dialogues. Direct Preference Optimization (DPO) has proven effective in aligning LLM behavior with human preferences across a variety of agent tasks. Existing DPO-based approaches for multi-turn interactions are divided into turn-level and session-level methods. The turn-level method is overly fine-grained, focusing exclusively on individual turns, while session-level methods are too coarse-grained, often introducing training noise. To address these limitations, we propose Segment-Level Direct Preference Optimization (SDPO), which focuses on specific key segments within interactions to optimize multi-turn agent behavior while minimizing training noise. Evaluations on the SOTOPIA benchmark demonstrate that SDPO-tuned agents consistently outperform both existing DPO-based methods and proprietary LLMs like GPT-4o, underscoring SDPO's potential to advance the social intelligence of LLM-based agents. We release our code and data at this https URL. 

**Abstract (ZH)**: 由大规模语言模型（LLMs）驱动的社会代理能够模拟人类社会行为，但在处理复杂的目的导向的社会对话方面存在不足。直接偏好优化（DPO）已证明在各种代理任务中能够有效使LLM的行为与人类偏好保持一致。现有的基于DPO的方法可以分为回合级和会话级方法。回合级方法过于细粒度，仅专注于个体回合，而会话级方法则过于粗粒度，常常引入训练噪声。为解决这些局限性，我们提出了段级直接偏好优化（SDPO），该方法专注于交互中的特定关键段落，以优化多回合代理行为，并尽量减少训练噪声。在SOTOPIA基准测试中的评估表明，SDPO优化后的代理在整个过程中持续优于现有基于DPO的方法以及专用LLM（如GPT-4o），突显出了SDPO在提升基于LLM的代理社会智能方面的潜力。我们已在以下网址发布了我们的代码和数据：[请补充具体网址]。 

---
# AgentRefine: Enhancing Agent Generalization through Refinement Tuning 

**Title (ZH)**: AgentRefine：通过细化调整提高智能体通用性 

**Authors**: Dayuan Fu, Keqing He, Yejie Wang, Wentao Hong, Zhuoma Gongque, Weihao Zeng, Wei Wang, Jingang Wang, Xunliang Cai, Weiran Xu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01702)  

**Abstract**: Large Language Model (LLM) based agents have proved their ability to perform complex tasks like humans. However, there is still a large gap between open-sourced LLMs and commercial models like the GPT series. In this paper, we focus on improving the agent generalization capabilities of LLMs via instruction tuning. We first observe that the existing agent training corpus exhibits satisfactory results on held-in evaluation sets but fails to generalize to held-out sets. These agent-tuning works face severe formatting errors and are frequently stuck in the same mistake for a long while. We analyze that the poor generalization ability comes from overfitting to several manual agent environments and a lack of adaptation to new situations. They struggle with the wrong action steps and can not learn from the experience but just memorize existing observation-action relations. Inspired by the insight, we propose a novel AgentRefine framework for agent-tuning. The core idea is to enable the model to learn to correct its mistakes via observation in the trajectory. Specifically, we propose an agent synthesis framework to encompass a diverse array of environments and tasks and prompt a strong LLM to refine its error action according to the environment feedback. AgentRefine significantly outperforms state-of-the-art agent-tuning work in terms of generalization ability on diverse agent tasks. It also has better robustness facing perturbation and can generate diversified thought in inference. Our findings establish the correlation between agent generalization and self-refinement and provide a new paradigm for future research. 

**Abstract (ZH)**: 基于大型语言模型（LLM）的智能体已经证明了其执行复杂任务的能力，类似于人类的行为。然而，开源的LLM与像GPT系列这样的商用模型之间仍然存在较大差距。本文旨在通过指令调优来提高LLM智能体的通用能力。我们首先观察到现有的智能体训练数据集在保留集上取得了令人满意的结果，但在排除集上却无法泛化。现有的智能体调优工作面临严重的格式错误，并且经常长期陷入相同的错误。我们分析认为，这种较差的通用能力来自于对几个手动智能体环境的过度拟合以及对新情况适应能力的缺乏。这些智能体难以纠正错误的操作步骤，不能从经验中学习，只是记忆现有的观察-动作关系。受到这一认识的启发，我们提出了一种名为AgentRefine的新框架来解决智能体调优问题。核心思想是使模型能够通过轨迹中的观察来学习纠正自己的错误。具体而言，我们提出了一种智能体合成框架，涵盖了多种多样的环境和任务，并促使强大的LLM根据环境反馈来修正其错误动作。AgentRefine在多种智能体任务上的泛化能力上显著优于最新的智能体调优工作，并且在面对扰动时具有更好的鲁棒性，能够生成多样化的推理思路。我们的研究结果建立了智能体泛化能力和自我修正之间的关联，并为未来的研究提供了一个新的范式。 

---
# Proposing Hierarchical Goal-Conditioned Policy Planning in Multi-Goal Reinforcement Learning 

**Title (ZH)**: 在多目标强化学习中提出分层次的目标条件策略规划 

**Authors**: Gavin B. Rens  

**Link**: [PDF](https://arxiv.org/pdf/2501.01727)  

**Abstract**: Humanoid robots must master numerous tasks with sparse rewards, posing a challenge for reinforcement learning (RL). We propose a method combining RL and automated planning to address this. Our approach uses short goal-conditioned policies (GCPs) organized hierarchically, with Monte Carlo Tree Search (MCTS) planning using high-level actions (HLAs). Instead of primitive actions, the planning process generates HLAs. A single plan-tree, maintained during the agent's lifetime, holds knowledge about goal achievement. This hierarchy enhances sample efficiency and speeds up reasoning by reusing HLAs and anticipating future actions. Our Hierarchical Goal-Conditioned Policy Planning (HGCPP) framework uniquely integrates GCPs, MCTS, and hierarchical RL, potentially improving exploration and planning in complex tasks. 

**Abstract (ZH)**: 类人机器人必须掌握大量具有稀疏奖励的任务，这对强化学习（RL）提出了挑战。我们提出了一种结合强化学习和自动规划的方法来解决这一问题。我们的方法采用分层组织的短目标条件策略（GCPs），并在高层次动作（HLAs）的指导下使用蒙特卡罗树搜索（MCTS）进行规划。与基本动作不同，规划过程生成HLAs。在整个代理生命周期中维护的一颗计划树保存了关于目标实现的知识。这种分层结构通过重用HLAs并预见未来的行为，提高了样本效率并加快了推理速度。我们的层次目标条件策略规划框架（Hierarchical Goal-Conditioned Policy Planning, HGCPP）独特地结合了GCPs、MCTS和层次化RL，有可能在复杂任务中改进探索和规划。 

---
# BLAST: A Stealthy Backdoor Leverage Attack against Cooperative Multi-Agent Deep Reinforcement Learning based Systems 

**Title (ZH)**: BLAST：针对合作多智能体深度强化学习系统的一种隐蔽后门利用攻击 

**Authors**: Yinbo Yu, Saihao Yan, Xueyu Yin, Jing Fang, Jiajia Liu  

**Link**: [PDF](https://arxiv.org/pdf/2501.01593)  

**Abstract**: Recent studies have shown that cooperative multi-agent deep reinforcement learning (c-MADRL) is under the threat of backdoor attacks. Once a backdoor trigger is observed, it will perform malicious actions leading to failures or malicious goals. However, existing backdoor attacks suffer from several issues, e.g., instant trigger patterns lack stealthiness, the backdoor is trained or activated by an additional network, or all agents are backdoored. To this end, in this paper, we propose a novel backdoor leverage attack against c-MADRL, BLAST, which attacks the entire multi-agent team by embedding the backdoor only in a single agent. Firstly, we introduce adversary spatiotemporal behavior patterns as the backdoor trigger rather than manual-injected fixed visual patterns or instant status and control the period to perform malicious actions. This method can guarantee the stealthiness and practicality of BLAST. Secondly, we hack the original reward function of the backdoor agent via unilateral guidance to inject BLAST, so as to achieve the \textit{leverage attack effect} that can pry open the entire multi-agent system via a single backdoor agent. We evaluate our BLAST against 3 classic c-MADRL algorithms (VDN, QMIX, and MAPPO) in 2 popular c-MADRL environments (SMAC and Pursuit), and 2 existing defense mechanisms. The experimental results demonstrate that BLAST can achieve a high attack success rate while maintaining a low clean performance variance rate. 

**Abstract (ZH)**: 近年来的研究表明，合作多智能体深度强化学习（c-MADRL）正受到后门攻击的威胁。一旦检测到后门触发因子，它将执行恶意操作，导致系统失败或实现恶意目标。然而，现有的后门攻击存在一些问题，例如即时触发模式缺乏隐蔽性，后门由额外的网络训练或激活，或者所有智能体都受到后门影响。为了解决这些问题，本文提出了一种针对c-MADRL的新型后门利用攻击，称为BLAST，它通过仅在一个智能体中嵌入后门来攻击整个多智能体团队。首先，我们引入对手时空行为模式作为后门触发因子，而不是手动注入的固定视觉图案或即时状态，并控制执行恶意操作的时间周期。这种方法可以确保BLAST的隐蔽性和实用性。其次，我们通过单向指导方式破解原始奖励函数，使后门智能体注入BLAST，从而实现通过单个后门智能体就可以打开整个多智能体系统的“杠杆攻击效果”。我们使用BLAST对3种经典c-MADRL算法（VDN、QMIX和MAPPO）以及2个流行c-MADRL环境（SMAC和Pursuit）中的2种现有防御机制进行了评估。实验结果表明，BLAST能够在维持较低清洁性能变异率的同时实现高攻击成功率。 

---
# Multi-Agent Conversational Online Learning for Adaptive LLM Response Identification 

**Title (ZH)**: 多代理对话式在线学习在自适应大语言模型响应识别中的应用 

**Authors**: Xiangxiang Dai, Yuejin Xie, Maoli Liu, Xuchuang Wang, Zhuohua Li, Huanyu Wang, John C.S. Lui  

**Link**: [PDF](https://arxiv.org/pdf/2501.01849)  

**Abstract**: The remarkable generative capability of large language models (LLMs) has sparked a growing interest in automatically generating responses for different applications. Given the dynamic nature of user preferences and the uncertainty of LLM response performance, it is crucial to design efficient online learning algorithms to identify optimal LLM responses (i.e., high-quality responses that also meet user preferences). Most existing online algorithms adopt a centralized approach and fail to leverage explicit user preferences for more efficient and personalized LLM response identification. In contrast, this paper introduces \textit{MACO} (\underline{M}ulti-\underline{A}gent \underline{C}onversational \underline{O}nline Learning for Adaptive LLM Response Identification): 1) The online LLM response identification process is accelerated by multiple local agents (such as smartphones), while enhancing data privacy; 2) A novel conversational mechanism is proposed to adaptively conduct conversations for soliciting user preferences (e.g., a preference for a humorous tone over a serious one in generated responses), so to minimize uncertainty in preference estimation. Our theoretical analysis demonstrates that \cadi\ is near-optimal regarding cumulative regret. Additionally, \cadi\ offers reduced communication costs and computational complexity by eliminating the traditional, computing-intensive ``G-optimal design" found in previous works. Extensive experiments with the open LLM \textit{Llama}, coupled with two different embedding models from Google and OpenAI for text vector representation, demonstrate that \cadi\ significantly outperforms the current state-of-the-art in online LLM response identification. 

**Abstract (ZH)**: 大型语言模型（LLMs）强大的生成能力激发了自动为不同应用生成响应的兴趣。鉴于用户偏好和LLM响应性能的动态性，设计高效的在线学习算法以识别最优LLM响应（即高质量且符合用户偏好的响应）至关重要。现有的大多数在线算法采用中心化的做法，未能充分利用显式的用户偏好来实现更高效的个性化LLM响应识别。与此不同，本文引入了一种名为 \textit{MACO}（多代理对话在线学习以适应性识别LLM响应）的方法：1）通过多台本地代理（如智能手机）加速在线LLM响应识别过程，同时增强数据隐私；2）提出了一种新的对话机制，以适应性地进行对话以征求用户偏好（例如，在生成的响应中偏好轻松幽默而非严肃），从而最小化偏好估计的不确定性。我们的理论分析表明，MACO 在累积后悔方面接近最优。此外，MACO 通过消除以往工作中常见的计算密集型的传统“G-最优设计”减少通信成本和计算复杂度。结合使用开源LLM \textit{Llama} 以及来自Google和OpenAI的两种不同嵌入模型进行文本向量表示的大量实验表明，MACO 显著优于当前在线LLM响应识别的最先进的方法。 

---
# MoColl: Agent-Based Specific and General Model Collaboration for Image Captioning 

**Title (ZH)**: MoColl：基于代理的特定模型与通用模型协作的图像_captioning方法 

**Authors**: Pu Yang, Bin Dong  

**Link**: [PDF](https://arxiv.org/pdf/2501.01834)  

**Abstract**: Image captioning is a critical task at the intersection of computer vision and natural language processing, with wide-ranging applications across various domains. For complex tasks such as diagnostic report generation, deep learning models require not only domain-specific image-caption datasets but also the incorporation of relevant general knowledge to provide contextual accuracy. Existing approaches exhibit inherent limitations: specialized models excel in capturing domain-specific details but lack generalization, while vision-language models (VLMs) built on large language models (LLMs) leverage general knowledge but struggle with domain-specific adaptation. To address these limitations, this paper proposes a novel agent-enhanced model collaboration framework, which we called \textbf{MoColl}, designed to effectively integrate domain-specific and general knowledge. Specifically, our approach is to decompose complex image captioning tasks into a series of interconnected question-answer subtasks. A trainable visual question answering (VQA) model is employed as a specialized tool to focus on domain-specific visual analysis, answering task-specific questions based on image content. Concurrently, an LLM-based agent with general knowledge formulates these questions and synthesizes the resulting question-answer pairs into coherent captions. Beyond its role in leveraging the VQA model, the agent further guides its training to enhance its domain-specific capabilities. Experimental results on radiology report generation validate the effectiveness of the proposed framework, demonstrating significant improvements in the quality of generated reports. 

**Abstract (ZH)**: 图像描述是计算机视觉与自然语言处理交叉领域的关键任务，具有广泛的应用前景。在诸如诊断报告生成等复杂任务中，深度学习模型不仅需要领域特定的图像-描述数据集，还需要融入相关的一般知识以提供上下文准确性。现有的方法存在固有的局限性：领域特定模型在捕捉领域细节方面表现优异，但在泛化能力上存在不足；基于大规模语言模型（LLM）的视觉-语言模型（VLM）虽能利用一般知识，但在领域特定适应性上却显得力不从心。为解决这些局限性，本文提出了一种新的代理增强模型协作框架，我们称之为**MoColl**，旨在有效整合领域特定和一般知识。具体而言，我们的方法将复杂的图像描述任务分解为一系列相互连接的问答子任务。一个可训练的视觉问答（VQA）模型被用作专门工具，专注于领域特定的视觉分析，基于图像内容回答特定任务的问题。同时，一个具有通用知识的LLM代理生成这些问题，并将生成的问答对整合成连贯的描述。除了利用VQA模型外，该代理进一步引导其训练以增强其领域特定的能力。在医学影像报告生成的实验中，所提出框架的有效性得到了验证，显著提升了生成报告的质量。 

---
# Goal Recognition using Actor-Critic Optimization 

**Title (ZH)**: 使用演员-评论员优化的目标识别 

**Authors**: Ben Nageris, Felipe Meneguzzi, Reuth Mirsky  

**Link**: [PDF](https://arxiv.org/pdf/2501.01463)  

**Abstract**: Goal Recognition aims to infer an agent's goal from a sequence of observations. Existing approaches often rely on manually engineered domains and discrete representations. Deep Recognition using Actor-Critic Optimization (DRACO) is a novel approach based on deep reinforcement learning that overcomes these limitations by providing two key contributions. First, it is the first goal recognition algorithm that learns a set of policy networks from unstructured data and uses them for inference. Second, DRACO introduces new metrics for assessing goal hypotheses through continuous policy representations. DRACO achieves state-of-the-art performance for goal recognition in discrete settings while not using the structured inputs used by existing approaches. Moreover, it outperforms these approaches in more challenging, continuous settings at substantially reduced costs in both computing and memory. Together, these results showcase the robustness of the new algorithm, bridging traditional goal recognition and deep reinforcement learning. 

**Abstract (ZH)**: 目标识别旨在从一系列观察中推断出代理的目标。现有的方法通常依赖于手工设计的领域和离散表示。基于深度强化学习的Deep Recognition using Actor-Critic Optimization (DRACO) 是一种新颖的方法，通过学习从非结构化数据中获得的一系列策略网络，并利用这些网络进行推理，从而克服了这些限制。DRACO 提出了两项关键贡献。首先，它是第一个从非结构化数据中学习一组策略网络并用于推理的目标识别算法。其次，DRACO 引入了新的度量标准，以通过连续策略表示评估目标假设。在不使用现有方法所使用的结构化输入的情况下，DRACO 在离散设置中达到了最先进的性能，同时在更具挑战性的连续设置中，以明显降低的计算和内存成本取得了更好的性能。综上所述，这些结果展示了该新算法的鲁棒性，将传统的目标识别和深度强化学习结合了起来。 

---