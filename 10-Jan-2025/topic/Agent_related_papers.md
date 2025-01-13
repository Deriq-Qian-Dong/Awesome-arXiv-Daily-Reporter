# Search-o1: Agentic Search-Enhanced Large Reasoning Models 

**Title (ZH)**: Search-o1: 代理增强的大推理模型搜索 

**Authors**: Xiaoxi Li, Guanting Dong, Jiajie Jin, Yuyao Zhang, Yujia Zhou, Yutao Zhu, Peitian Zhang, Zhicheng Dou  

**Link**: [PDF](https://arxiv.org/pdf/2501.05366)  

**Abstract**: Large reasoning models (LRMs) like OpenAI-o1 have demonstrated impressive long stepwise reasoning capabilities through large-scale reinforcement learning. However, their extended reasoning processes often suffer from knowledge insufficiency, leading to frequent uncertainties and potential errors. To address this limitation, we introduce \textbf{Search-o1}, a framework that enhances LRMs with an agentic retrieval-augmented generation (RAG) mechanism and a Reason-in-Documents module for refining retrieved documents. Search-o1 integrates an agentic search workflow into the reasoning process, enabling dynamic retrieval of external knowledge when LRMs encounter uncertain knowledge points. Additionally, due to the verbose nature of retrieved documents, we design a separate Reason-in-Documents module to deeply analyze the retrieved information before injecting it into the reasoning chain, minimizing noise and preserving coherent reasoning flow. Extensive experiments on complex reasoning tasks in science, mathematics, and coding, as well as six open-domain QA benchmarks, demonstrate the strong performance of Search-o1. This approach enhances the trustworthiness and applicability of LRMs in complex reasoning tasks, paving the way for more reliable and versatile intelligent systems. The code is available at \url{this https URL}. 

**Abstract (ZH)**: 大型推理模型（LRMs）如OpenAI-o1通过大规模强化学习展示了令人印象深刻的长步骤推理能力。然而，它们的延长推理过程往往受到知识不足的影响，导致频繁的不确定性甚至潜在错误。为了解决这一限制，我们引入了**Search-o1**，一个通过添加自主检索增强生成（RAG）机制和文档内推理模块来增强LRMs的框架。Search-o1将自主搜索工作流程整合到推理过程中，使LRMs在遇到不确定的知识点时能够动态检索外部知识。此外，由于检索到的文档通常内容丰富，我们设计了一个单独的文档内推理模块，在将这些信息注入推理链之前对其进行深入分析，从而减少噪声并保持连贯的推理流程。通过在科学、数学和编程等复杂推理任务以及六个开放领域问答基准测试中的广泛实验，证明了Search-o1的出色性能。该方法增强了LRMs在复杂推理任务中的可信度和适用性，为更可靠和多功能的智能系统铺平了道路。代码可在[此处](this https URL)获得。 

---
# On Corrigibility and Alignment in Multi Agent Games 

**Title (ZH)**: 多智能体游戏中可纠正性和对齐性的研究 

**Authors**: Edmund Dable-Heath, Boyko Vodenicharski, James Bishop  

**Link**: [PDF](https://arxiv.org/pdf/2501.05360)  

**Abstract**: Corrigibility of autonomous agents is an under explored part of system design, with previous work focusing on single agent systems. It has been suggested that uncertainty over the human preferences acts to keep the agents corrigible, even in the face of human irrationality. We present a general framework for modelling corrigibility in a multi-agent setting as a 2 player game in which the agents always have a move in which they can ask the human for supervision. This is formulated as a Bayesian game for the purpose of introducing uncertainty over the human beliefs. We further analyse two specific cases. First, a two player corrigibility game, in which we want corrigibility displayed in both agents for both common payoff (monotone) games and harmonic games. Then we investigate an adversary setting, in which one agent is considered to be a `defending' agent and the other an `adversary'. A general result is provided for what belief over the games and human rationality the defending agent is required to have to induce corrigibility. 

**Abstract (ZH)**: 自主智能体的可纠正性是系统设计中的一个尚未充分探索的领域，先前的工作主要集中在单智能体系统上。有人建议，对人类偏好不确定性的存在可以使智能体保持可纠正性，即使在面对人类的非理性行为时也是如此。本文提供了一个通用框架，将多智能体环境中的可纠正性模型化为一个两人博弈，其中智能体始终可以采取行动请求人类监督。该框架被表述为贝叶斯博弈，以引入对人类信念的不确定性。我们进一步分析了两种特定情况。首先，一种两人可纠正性博弈，我们希望两个智能体在共付（单调）博弈和和声博弈中都能表现出可纠正性。然后，我们探讨了一种对抗设置，其中一个智能体被视为“防守型”智能体，另一个为“攻击型”智能体。本文提供了防守型智能体所需的关于博弈及其对人类理性行为的信念的一般结果，以诱导可纠正性。 

---
# Constrained Optimization of Charged Particle Tracking with Multi-Agent Reinforcement Learning 

**Title (ZH)**: 多代理强化学习约束优化带电粒子跟踪 

**Authors**: Tobias Kortus, Ralf Keidel, Nicolas R. Gauger, Jan Kieseler  

**Link**: [PDF](https://arxiv.org/pdf/2501.05113)  

**Abstract**: Reinforcement learning demonstrated immense success in modelling complex physics-driven systems, providing end-to-end trainable solutions by interacting with a simulated or real environment, maximizing a scalar reward signal. In this work, we propose, building upon previous work, a multi-agent reinforcement learning approach with assignment constraints for reconstructing particle tracks in pixelated particle detectors. Our approach optimizes collaboratively a parametrized policy, functioning as a heuristic to a multidimensional assignment problem, by jointly minimizing the total amount of particle scattering over the reconstructed tracks in a readout frame. To satisfy constraints, guaranteeing a unique assignment of particle hits, we propose a safety layer solving a linear assignment problem for every joint action. Further, to enforce cost margins, increasing the distance of the local policies predictions to the decision boundaries of the optimizer mappings, we recommend the use of an additional component in the blackbox gradient estimation, forcing the policy to solutions with lower total assignment costs. We empirically show on simulated data, generated for a particle detector developed for proton imaging, the effectiveness of our approach, compared to multiple single- and multi-agent baselines. We further demonstrate the effectiveness of constraints with cost margins for both optimization and generalization, introduced by wider regions with high reconstruction performance as well as reduced predictive instabilities. Our results form the basis for further developments in RL-based tracking, offering both enhanced performance with constrained policies and greater flexibility in optimizing tracking algorithms through the option for individual and team rewards. 

**Abstract (ZH)**: 强化学习在建模复杂物理驱动系统方面展现了巨大的成功，通过与模拟或真实环境互动，提供端到端可训练的解决方案，最大化标量奖励信号。在这项工作中，我们在此前工作的基础上，提出了一种带分配约束的多智能体强化学习方法，用于在像素化粒子探测器中重构粒子轨迹。该方法通过联合最小化重建轨迹在读出帧中的总散射粒子量，协作优化一个参数化策略，该策略作为多维分配问题的启发式算法。为了满足约束要求，确保粒子击中点的唯一分配，我们提出了一种安全层，用于为每个联合动作解决线性分配问题。此外，为了增加局部策略预测与优化映射决策边界之间的成本差距，我们建议在黑盒梯度估计中增加一个额外组件，迫使策略向总分配成本较低的解决方案倾斜。我们通过模拟数据（模拟用于质子成像的粒子探测器生成的数据）的实验证明了我们方法的有效性，相比多个单智能体和多智能体基线，我们方法显示出更高的效果。我们还展示了带成本差距约束的有效性，这些约束在优化和泛化方面引入了更宽的重建性能高区域，以及减少了预测不稳定性的效果。我们的结果为基于RL的跟踪技术的进一步发展奠定了基础，提供了受限策略增强性能和通过个体和团队奖励优化跟踪算法更大灵活性的可能。 

---
# CuRLA: Curriculum Learning Based Deep Reinforcement Learning for Autonomous Driving 

**Title (ZH)**: CuRLA：基于课程学习的深度强化学习在自动驾驶中的应用 

**Authors**: Bhargava Uppuluri, Anjel Patel, Neil Mehta, Sridhar Kamath, Pratyush Chakraborty  

**Link**: [PDF](https://arxiv.org/pdf/2501.04982)  

**Abstract**: In autonomous driving, traditional Computer Vision (CV) agents often struggle in unfamiliar situations due to biases in the training data. Deep Reinforcement Learning (DRL) agents address this by learning from experience and maximizing rewards, which helps them adapt to dynamic environments. However, ensuring their generalization remains challenging, especially with static training environments. Additionally, DRL models lack transparency, making it difficult to guarantee safety in all scenarios, particularly those not seen during training. To tackle these issues, we propose a method that combines DRL with Curriculum Learning for autonomous driving. Our approach uses a Proximal Policy Optimization (PPO) agent and a Variational Autoencoder (VAE) to learn safe driving in the CARLA simulator. The agent is trained using two-fold curriculum learning, progressively increasing environment difficulty and incorporating a collision penalty in the reward function to promote safety. This method improves the agent's adaptability and reliability in complex environments, and understand the nuances of balancing multiple reward components from different feedback signals in a single scalar reward function. Keywords: Computer Vision, Deep Reinforcement Learning, Variational Autoencoder, Proximal Policy Optimization, Curriculum Learning, Autonomous Driving. 

**Abstract (ZH)**: 在自动驾驶领域，传统的计算机视觉（CV）代理往往在不熟悉的情况下因训练数据中的偏差而表现不佳。深度强化学习（DRL）代理通过从经验中学习并最大化奖励来解决这一问题，这有助于它们适应动态环境。然而，确保其泛化仍然具有挑战性，尤其是在静态的训练环境中。此外，DRL模型缺乏透明度，这使得在所有场景中保证其安全性变得困难，尤其是那些在训练期间未见过的场景。为了应对这些问题，我们提出了一种结合DRL与课程学习的方法，用于自动驾驶。我们的方法使用Proximal Policy Optimization（PPO）代理和Variational Autoencoder（VAE）在CARLA模拟器中学习安全驾驶。代理通过两阶段的课程学习进行训练，逐步增加环境难度，并在奖励函数中引入碰撞惩罚以促进安全。该方法提高了代理在复杂环境中的适应性和可靠性，并能够理解将来自多种反馈信号的多个奖励组件平衡到单个标量奖励函数中的细微差别。关键词：计算机视觉、深度强化学习、变分自编码器、 proximal 政策优化、课程学习、自动驾驶。 

---