# Robust Change Captioning in Remote Sensing: SECOND-CC Dataset and MModalCC Framework 

**Title (ZH)**: 遥感中的稳健变化描述：SECOND-CC 数据集和 MModalCC 框架 

**Authors**: Ali Can Karaca, M. Enes Ozelbas, Saadettin Berber, Orkhan Karimli, Turabi Yildirim, M. Fatih Amasyali  

**Link**: [PDF](https://arxiv.org/pdf/2501.10075)  

**Abstract**: Remote sensing change captioning (RSICC) aims to describe changes between bitemporal images in natural language. Existing methods often fail under challenges like illumination differences, viewpoint changes, blur effects, leading to inaccuracies, especially in no-change regions. Moreover, the images acquired at different spatial resolutions and have registration errors tend to affect the captions. To address these issues, we introduce SECOND-CC, a novel RSICC dataset featuring high-resolution RGB image pairs, semantic segmentation maps, and diverse real-world scenarios. SECOND-CC which contains 6,041 pairs of bitemporal RS images and 30,205 sentences describing the differences between images. Additionally, we propose MModalCC, a multimodal framework that integrates semantic and visual data using advanced attention mechanisms, including Cross-Modal Cross Attention (CMCA) and Multimodal Gated Cross Attention (MGCA). Detailed ablation studies and attention visualizations further demonstrate its effectiveness and ability to address RSICC challenges. Comprehensive experiments show that MModalCC outperforms state-of-the-art RSICC methods, including RSICCformer, Chg2Cap, and PSNet with +4.6% improvement on BLEU4 score and +9.6% improvement on CIDEr score. We will make our dataset and codebase publicly available to facilitate future research at this https URL 

**Abstract (ZH)**: 遥感变化描述（Remote Sensing Change Captioning, RSICC）旨在利用自然语言描述不同时期图像之间的变化。现有方法在光照差异、视角变化、模糊效果等挑战下常常会出现准确性下降的问题，尤其是在无变化区域。此外，不同空间分辨率的图像及其注册误差也会影响描述的准确性。为解决这些问题，我们引入了SECOND-CC，这是一个全新的RSICC数据集，该数据集包含高分辨率的RGB图像对、语义分割图以及多样化的现实场景。SECOND-CC包含6041个不同时期的遥感图像对和30205个描述图像差异的句子。此外，我们提出了MModalCC，这是一种多模态框架，通过使用高级注意力机制（包括跨模态跨注意力CMCA和多模态门控跨注意力MGCA）来结合语义和视觉数据。详细的消融研究和注意力可视化进一步证明了其有效性和对RSICC挑战的解决能力。全面的实验表明，MModalCC在最先进的RSICC方法（包括RSICCformer, Chg2Cap和PSNet）中表现更佳，提高了BLEU4分数4.6%和CIDEr分数9.6%。我们将我们的数据集和代码库公开发布，以促进未来的研究，链接如下：[此链接此处替换为实际的公开链接] 

---
# Mitigating Hallucinations on Object Attributes using Multiview Images and Negative Instructions 

**Title (ZH)**: 使用多视角图像和负向指令减轻对象属性幻觉现象 

**Authors**: Zhijie Tan, Yuzhi Li, Shengwei Meng, Xiang Yuan, Weiping Li, Tong Mo, Bingce Wang, Xu Chu  

**Link**: [PDF](https://arxiv.org/pdf/2501.10011)  

**Abstract**: Current popular Large Vision-Language Models (LVLMs) are suffering from Hallucinations on Object Attributes (HoOA), leading to incorrect determination of fine-grained attributes in the input images. Leveraging significant advancements in 3D generation from a single image, this paper proposes a novel method to mitigate HoOA in LVLMs. This method utilizes multiview images sampled from generated 3D representations as visual prompts for LVLMs, thereby providing more visual information from other viewpoints. Furthermore, we observe the input order of multiple multiview images significantly affects the performance of LVLMs. Consequently, we have devised Multiview Image Augmented VLM (MIAVLM), incorporating a Multiview Attributes Perceiver (MAP) submodule capable of simultaneously eliminating the influence of input image order and aligning visual information from multiview images with Large Language Models (LLMs). Besides, we designed and employed negative instructions to mitigate LVLMs' bias towards ``Yes" responses. Comprehensive experiments demonstrate the effectiveness of our method. 

**Abstract (ZH)**: 当前流行的大型视觉-语言模型（LVLMs）在对象属性上存在幻觉问题（HoOA），导致输入图像中的细粒度属性判断不正确。基于单张图像生成3D图像的重要进展，本文提出了一种新颖的方法来减轻LVLMs中的HoOA问题。该方法利用从生成的3D表示中采样的多视角图像作为LVLMs的视觉提示，从而提供来自其他视角的更多视觉信息。此外，我们观察到多视角图像的输入顺序对LVLMs的性能有显著影响。因此，我们设计了多视角图像增强视觉语言模型（MIAVLM），该模型包含一个多视角属性感知器（MAP）模块，可以同时消除输入图像顺序的影响，并将多视角图像中的视觉信息与大规模语言模型（LLMs）对齐。此外，我们设计并使用了负指令以减轻LVLMs对“是”回答的偏见。全面的实验表明了我们方法的有效性。 

---
# Multi-Modal Attention Networks for Enhanced Segmentation and Depth Estimation of Subsurface Defects in Pulse Thermography 

**Title (ZH)**: 用于增强脉冲热成像下层缺陷分割和深度估计的多模态注意力网络 

**Authors**: Mohammed Salah, Naoufel Werghi, Davor Svetinovic, Yusra Abdulrahman  

**Link**: [PDF](https://arxiv.org/pdf/2501.09994)  

**Abstract**: AI-driven pulse thermography (PT) has become a crucial tool in non-destructive testing (NDT), enabling automatic detection of hidden anomalies in various industrial components. Current state-of-the-art techniques feed segmentation and depth estimation networks compressed PT sequences using either Principal Component Analysis (PCA) or Thermographic Signal Reconstruction (TSR). However, treating these two modalities independently constrains the performance of PT inspection models as these representations possess complementary semantic features. To address this limitation, this work proposes PT-Fusion, a multi-modal attention-based fusion network that fuses both PCA and TSR modalities for defect segmentation and depth estimation of subsurface defects in PT setups. PT-Fusion introduces novel feature fusion modules, Encoder Attention Fusion Gate (EAFG) and Attention Enhanced Decoding Block (AEDB), to fuse PCA and TSR features for enhanced segmentation and depth estimation of subsurface defects. In addition, a novel data augmentation technique is proposed based on random data sampling from thermographic sequences to alleviate the scarcity of PT datasets. The proposed method is benchmarked against state-of-the-art PT inspection models, including U-Net, attention U-Net, and 3D-CNN on the Université Laval IRT-PVC dataset. The results demonstrate that PT-Fusion outperforms the aforementioned models in defect segmentation and depth estimation accuracies with a margin of 10%. 

**Abstract (ZH)**: 基于AI的脉冲热成像（PT）已成为无损检测（NDT）中的关键工具，能够自动检测工业组件中隐藏的异常。当前最先进的技术使用主成分分析（PCA）或热成像信号重建（TSR）压缩PT序列，输入分割和深度估计网络。然而，独立处理这两种表示方式限制了PT检测模型的性能，因为这两种表示方式具有互补的语义特征。为了解决这一局限性，本研究提出了一种多模态注意融合网络PT-Fusion，该网络将PCA和TSR模态融合，用于PT设置中次表面缺陷的缺陷分割和深度估计。PT-Fusion引入了新颖的特征融合模块——编码器注意力融合门（EAFG）和注意力增强解码块（AEDB），以增强次表面缺陷的分割和深度估计。此外，还提出了一种基于热成像序列中随机数据采样的新颖数据增强技术，以缓解PT数据集稀缺的问题。该方法在Université Laval IRT-PVC数据集上与包括Unet、注意力Unet和3D-CNN在内的最新PT检测模型进行了基准测试。结果表明，PT-Fusion在缺陷分割和深度估计准确性方面分别比上述模型高出10%。 

---
# GVMGen: A General Video-to-Music Generation Model with Hierarchical Attentions 

**Title (ZH)**: GVMGen：一种基于层次注意力机制的通用视频到音乐生成模型 

**Authors**: Heda Zuo, Weitao You, Junxian Wu, Shihong Ren, Pei Chen, Mingxu Zhou, Yujia Lu, Lingyun Sun  

**Link**: [PDF](https://arxiv.org/pdf/2501.09972)  

**Abstract**: Composing music for video is essential yet challenging, leading to a growing interest in automating music generation for video applications. Existing approaches often struggle to achieve robust music-video correspondence and generative diversity, primarily due to inadequate feature alignment methods and insufficient datasets. In this study, we present General Video-to-Music Generation model (GVMGen), designed for generating high-related music to the video input. Our model employs hierarchical attentions to extract and align video features with music in both spatial and temporal dimensions, ensuring the preservation of pertinent features while minimizing redundancy. Remarkably, our method is versatile, capable of generating multi-style music from different video inputs, even in zero-shot scenarios. We also propose an evaluation model along with two novel objective metrics for assessing video-music alignment. Additionally, we have compiled a large-scale dataset comprising diverse types of video-music pairs. Experimental results demonstrate that GVMGen surpasses previous models in terms of music-video correspondence, generative diversity, and application universality. 

**Abstract (ZH)**: 为视频作曲是必不可少但极具挑战性的任务，这导致了在视频应用中自动化音乐生成的兴趣日益增长。现有的方法往往难以实现稳健的音乐-视频对应和生成多样性，主要原因是特征对齐方法不足以及数据集不充足。在此研究中，我们提出了通用视频到音乐生成模型（GVMGen），旨在生成与视频输入高度相关的音乐。我们的模型采用了层次注意力机制，在空间和时间维度上提取并对齐视频特征和音乐，确保保留关键特征的同时减少冗余。值得一提的是，我们的方法具有极大的通用性，能够在零样本的情况下从不同类型的视频输入生成多种风格的音乐。我们还提出了一种评估模型，并引入了两个新的客观评估指标，用于评估视频-音乐对齐情况。此外，我们还编译了一个包含多种类型的视频-音乐配对的大规模数据集。实验结果表明，GVMGen在音乐-视频对应、生成多样性和应用通用性方面超越了之前的模型。 

---
# CrossModalityDiffusion: Multi-Modal Novel View Synthesis with Unified Intermediate Representation 

**Title (ZH)**: CrossModalityDiffusion: 使用统一中间表示的多模态新型视角合成 

**Authors**: Alex Berian, Daniel Brignac, JhihYang Wu, Natnael Daba, Abhijit Mahalanobis  

**Link**: [PDF](https://arxiv.org/pdf/2501.09838)  

**Abstract**: Geospatial imaging leverages data from diverse sensing modalities-such as EO, SAR, and LiDAR, ranging from ground-level drones to satellite views. These heterogeneous inputs offer significant opportunities for scene understanding but present challenges in interpreting geometry accurately, particularly in the absence of precise ground truth data. To address this, we propose CrossModalityDiffusion, a modular framework designed to generate images across different modalities and viewpoints without prior knowledge of scene geometry. CrossModalityDiffusion employs modality-specific encoders that take multiple input images and produce geometry-aware feature volumes that encode scene structure relative to their input camera positions. The space where the feature volumes are placed acts as a common ground for unifying input modalities. These feature volumes are overlapped and rendered into feature images from novel perspectives using volumetric rendering techniques. The rendered feature images are used as conditioning inputs for a modality-specific diffusion model, enabling the synthesis of novel images for the desired output modality. In this paper, we show that jointly training different modules ensures consistent geometric understanding across all modalities within the framework. We validate CrossModalityDiffusion's capabilities on the synthetic ShapeNet cars dataset, demonstrating its effectiveness in generating accurate and consistent novel views across multiple imaging modalities and perspectives. 

**Abstract (ZH)**: 地理空间成像利用了多种传感器数据，如光学遥感（EO）、合成孔径雷达（SAR）和激光雷达（LiDAR），这些数据来源从低空无人机到卫星视图不等。这些异构输入为场景理解提供了重大机遇，但缺乏精确的地面真实数据时，它们在准确解释几何形状方面带来了挑战。为解决这一问题，我们提出了一种名为CrossModalityDiffusion的模块化框架，该框架能够在无需先验场景几何知识的情况下，生成不同模态和视角的图像。CrossModalityDiffusion采用了特定模态的编码器，这些编码器接受多个输入图像，并生成编码场景结构相对于输入相机位置的几何感知特征体。这些特征体所在的空间充当了一个统一输入模态的共同基础。特征体通过体绘制技术从新颖视角重叠并渲染成特征图像。渲染出的特征图像作为特定模态的扩散模型的条件输入，从而能够合成所需输出模态的新图像。在本文中，我们展示了联合训练不同模块确保框架内各模态之间几何理解的一致性。我们在合成ShapeNet汽车数据集上验证了CrossModalityDiffusion的能力，展示了其在多种成像模态和视角下生成准确且一致的新视角图像的有效性。 

---
# MSTS: A Multimodal Safety Test Suite for Vision-Language Models 

**Title (ZH)**: MSTS：面向视觉-语言模型的多模态安全测试套件 

**Authors**: Paul Röttger, Giuseppe Attanasio, Felix Friedrich, Janis Goldzycher, Alicia Parrish, Rishabh Bhardwaj, Chiara Di Bonaventura, Roman Eng, Gaia El Khoury Geagea, Sujata Goswami, Jieun Han, Dirk Hovy, Seogyeong Jeong, Paloma Jeretič, Flor Miriam Plaza-del-Arco, Donya Rooein, Patrick Schramowski, Anastassia Shaitarova, Xudong Shen, Richard Willats, Andrea Zugarini, Bertie Vidgen  

**Link**: [PDF](https://arxiv.org/pdf/2501.10057)  

**Abstract**: Vision-language models (VLMs), which process image and text inputs, are increasingly integrated into chat assistants and other consumer AI applications. Without proper safeguards, however, VLMs may give harmful advice (e.g. how to self-harm) or encourage unsafe behaviours (e.g. to consume drugs). Despite these clear hazards, little work so far has evaluated VLM safety and the novel risks created by multimodal inputs. To address this gap, we introduce MSTS, a Multimodal Safety Test Suite for VLMs. MSTS comprises 400 test prompts across 40 fine-grained hazard categories. Each test prompt consists of a text and an image that only in combination reveal their full unsafe meaning. With MSTS, we find clear safety issues in several open VLMs. We also find some VLMs to be safe by accident, meaning that they are safe because they fail to understand even simple test prompts. We translate MSTS into ten languages, showing non-English prompts to increase the rate of unsafe model responses. We also show models to be safer when tested with text only rather than multimodal prompts. Finally, we explore the automation of VLM safety assessments, finding even the best safety classifiers to be lacking. 

**Abstract (ZH)**: 视觉语言模型（VLMs），这些模型处理图像和文本输入，正越来越多地集成到聊天助手和其他消费者AI应用中。然而，如果没有适当的保障措施，VLMs可能会提供有害建议（例如如何自残）或鼓励不安全行为（例如摄入药物）。尽管存在这些明显的风险，迄今为止很少有研究评估VLM的安全性以及多模态输入带来的新型风险。为弥补这一空白，我们引入了MSTS，即多模态安全性测试套件（Multimodal Safety Test Suite for VLMs）。MSTS 包含了400个测试提示，涵盖了40个细微的风险类别。每个测试提示由一个文本和一个图像组成，只有结合起来才能揭示其全部潜在的不安全含义。通过MSTS，我们发现了一些开放性VLM中存在的明显安全问题。我们还发现有些VLM由于无法理解甚至简单的测试提示而意外地表现出安全性。我们将MSTS翻译成十种语言，显示非英语提示可以增加不可靠模型的响应率。我们还展示了仅使用文本而非多模态提示进行测试可以使模型更安全。最后，我们探讨了VLM安全性评估的自动化问题，发现即使是最好的安全性分类器也存在不足。 

---