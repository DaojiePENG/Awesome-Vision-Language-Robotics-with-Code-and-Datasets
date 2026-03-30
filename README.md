<div align="center">

# 🤖 Awesome Vision-Language-Robotics with Code and Datasets

**A Comprehensive Collection of Vision-Language-Action & Navigation Research**

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Papers](https://img.shields.io/badge/Papers-100+-0984e3?style=for-the-badge&logo=google-scholar&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/DaojiePENG/Awesome-Vision-Language-Robotics?style=for-the-badge&color=fdcb6e&logo=github)](#)

<br>

*Curating state-of-the-art research in robot learning —*

*Vision-Language-Action (VLA), Vision-Language-Navigation (VLN), and beyond.*

**Empowering robots to understand, reason, and act in the physical world.**



***

## 📋 Table of Contents



|    | Section                                                              | Description                             |
| -- | -------------------------------------------------------------------- | --------------------------------------- |
| 📚 | [Survey](#-survey)                                                   | Comprehensive surveys and review papers |
| 🎯 | [Vision-Language-Action (VLA)](#-vision-language-action-vla)         | VLA models for robotic manipulation     |
| 🧭 | [Vision-Language-Navigation (VLN)](#-vision-language-navigation-vln) | Navigation with language instructions   |
| 📊 | [Datasets & Benchmarks](#-datasets--benchmarks)                      | Evaluation benchmarks and datasets      |
| 🔗 | [Related Resources](#-related-resources)                             | Tools, frameworks, and related lists    |
| 🤝 | [Contributing](#-contributing)                                       | How to contribute                       |

> \[!NOTE]

**Paper Ordering** — Within each year, papers are generally listed in reverse chronological order. Particularly influential works may be highlighted.

> \[!TIP]

**Contributing** — This repository is continuously updated! Submit a [Pull Request](CONTRIBUTING.md) or open an [Issue](https://github.com/DaojiePENG/Awesome-Vision-Language-Robotics/issues) to add papers or suggest improvements.



***

## 📚 Survey

> *Comprehensive surveys and review papers covering the landscape of embodied AI and robot learning.*



* \[2026] Vision-Language-Action in Robotics: A Survey of Datasets, Benchmarks, and Data Engines \[[paper](https://openreview.net/forum?id=tAaWFpvnmm)]

* \[2025] \[**Science Robotics**] A Review of Learning-based Dynamics Models for Robotic Manipulation \[[paper](https://albertboai.com/assets/pdf/2025_scirobotics.adt1497.pdf)]

* \[2025] An Anatomy of Vision-Language-Action Models: From Modules to Milestones and Challenges \[[paper](https://arxiv.org/pdf/2512.11362)] \[[project](https://suyuz1.github.io/Survery/)]

* \[2025] A Comprehensive Survey on World Models for Embodied AI \[[paper](https://www.arxiv.org/pdf/2510.16732)] \[[project](https://github.com/Li-Zn-H/AwesomeWorldModels)]

* \[2025] Vision-Language-Action Models for Robotics: A Review Towards Real-World Applications \[[paper](https://arxiv.org/pdf/2510.07077)]

* \[2025] Pure Vision Language Action (VLA) Models: A Comprehensive Survey \[[paper](https://arxiv.org/pdf/2509.19012)]

* \[2025] Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey \[[paper](https://arxiv.org/pdf/2508.13073)] \[[project](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation)]

* \[2025] Foundation Model Driven Robotics: A Comprehensive Review \[[paper](https://arxiv.org/pdf/2507.10087)]

* \[2025] \[**PKU-PsiBot**] A Survey on Vision-Language-Action Models: An Action Tokenization Perspective \[[paper](https://arxiv.org/pdf/2507.01925)]

* \[2025] \[**IJRR 25**] Foundation Models in Robotics: Applications, Challenges, and the Future \[[paper](https://arxiv.org/pdf/2312.07843)] \[[project](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]

* \[2025] A Survey on Diffusion Policy for Robotic Manipulation \[[paper](https://doi.org/10.36227/techrxiv.174378343.39356214/v1)] \[[project](https://github.com/HITSZ-Robotics/DiffusionPolicy-Robotics)]

* \[2024] A Survey on Vision-Language-Action Models for Embodied AI \[[paper](https://arxiv.org/abs/2405.14093)]

* \[2024] Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI \[[paper](https://arxiv.org/pdf/2407.06886)]

* \[2024] Vision-language navigation: a survey and taxonomy \[[paper](https://arxiv.org/pdf/2108.11544)]



***

## 🎯 Vision-Language-Action (VLA)

> *Vision-Language-Action models bridge natural language understanding with robotic control, enabling robots to follow high-level instructions and perform manipulation tasks.*

### 📊 Quick Index



| Year     | Title                               | Institution           | Venue        | Paper                                                                                                                                                          | Code                                                          |
| -------- | ----------------------------------- | --------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **2026** | Gaze-Regularized VLA                | -                     | arXiv 2026   | [📄](https://arxiv.org/abs/2603.23202)                                                                                                                         | -                                                             |
| **2026** | DAM-VLA                             | -                     | arXiv 2026   | [📄](https://arxiv.org/html/2603.00926v1)                                                                                                                      | -                                                             |
| **2026** | InternVLA-A1                        | InternRobotics        | arXiv 2026   | [📄](https://arxiv.org/html/2601.02456v1/)                                                                                                                     | -                                                             |
| **2026** | CogVLA                              | -                     | arXiv 2026   | [📄](https://openreview.net/forum?id=Dj3GWq0J30)                                                                                                               | -                                                             |
| **2026** | SemanticVLA                         | -                     | arXiv 2026   | [📄](https://openreview.net/forum?id=nHlxsb98mk)                                                                                                               | -                                                             |
| **2026** | Goal-VLA                            | NUS                   | ICRA 2026    | [📄](http://m.toutiao.com/group/7622886310843318811/)                                                                                                          | -                                                             |
| **2026** | VITRA                               | Microsoft             | ICRA 2026    | [📄](https://arxiv.org/abs/2510.08104)                                                                                                                         | [💻](https://github.com/microsoft/VITRA)                      |
| **2025** | OTTER                               | -                     | ICML 2025    | [📄](https://proceedings.mlr.press/v267/huang25u.html)                                                                                                         | -                                                             |
| **2025** | X-VLA                               | 2toINF                | IROS 2025    | [📄](https://arxiv.org/abs/2510.10274)                                                                                                                         | [💻](https://github.com/2toinf/X-VLA)                         |
| **2025** | FLOWER                              | Microsoft Research    | arXiv 2025   | [📄](https://www.microsoft.com/en-us/research/publication/flower-democratizing-generalist-robot-policies-with-efficient-vision-language-action-flow-policies/) | [💻](https://intuitive-robots.github.io/flower_vla/)          |
| **2025** | UP-VLA                              | Tsinghua University   | ICML 2025    | [📄](https://arxiv.org/pdf/2501.18867)                                                                                                                         | [💻](https://github.com/CladernyJorn/UP-VLA)                  |
| **2025** | AutoVLA                             | UCLA                  | NeurIPS 2025 | [📄](https://arxiv.org/abs/2506.13757)                                                                                                                         | [💻](https://github.com/ucla-mobility/AutoVLA)                |
| **2025** | π0.5: Open-World Generalization     | Physical Intelligence | arXiv        | [📄](https://arxiv.org/pdf/2504.16054)                                                                                                                         | [💻](https://github.com/Physical-Intelligence/openpi)         |
| **2025** | GR00T N1: Humanoid Foundation Model | Nvidia                | arXiv        | [📄](https://arxiv.org/pdf/2503.14734)                                                                                                                         | [💻](https://github.com/NVIDIA/Isaac-GR00T)                   |
| **2025** | OpenVLA: Open-Source VLA Model      | UC Berkeley           | CoRL 2024    | [📄](https://arxiv.org/abs/2406.09246)                                                                                                                         | [💻](https://github.com/openvla/openvla)                      |
| **2024** | Octo: Generalist Robot Policy       | UC Berkeley           | RSS 2024     | [📄](https://arxiv.org/abs/2405.12213)                                                                                                                         | [💻](https://github.com/octo-models/octo)                     |
| **2024** | RT-2: Transfer Web Knowledge        | Google DeepMind       | CoRL 2023    | [📄](https://arxiv.org/abs/2307.15818)                                                                                                                         | [💻](https://github.com/google-deepmind/rt-2)                 |
| **2023** | PaLM-E: Embodied Multimodal LLM     | Google                | ICML 2023    | [📄](https://arxiv.org/abs/2303.03378)                                                                                                                         | -                                                             |
| **2023** | VIMA: Multimodal Prompting          | Stanford/NVIDIA       | ICML 2023    | [📄](https://arxiv.org/abs/2210.03094)                                                                                                                         | [💻](https://github.com/vimalabs/VIMA)                        |
| **2022** | RT-1: Robotics Transformer          | Google                | RSS 2023     | [📄](https://arxiv.org/abs/2212.06817)                                                                                                                         | [💻](https://github.com/google-research/robotics_transformer) |
| **2022** | Gato: Generalist Agent              | DeepMind              | TMLR 2022    | [📄](https://arxiv.org/abs/2205.06175)                                                                                                                         | -                                                             |

### 2026

#### Gaze-Regularized Vision-Language-Action Models for Robotic Manipulation



* 📄 **Paper**: [arXiv:2603.23202](https://arxiv.org/abs/2603.23202)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: Leverages human perceptual priors with gaze regularization to accelerate robot learning, improving task performance and system interpretability without requiring eye-tracking equipment.

* ✨ **Key Innovations**:


  * Gaze-regularized training paradigm

  * No additional hardware requirements

  * Improved learning efficiency

  * Enhanced interpretability of VLA models



***

#### DAM-VLA: A Dynamic Action Model-Based Vision-Language-Action Framework for Robot Manipulation



* 📄 **Paper**: [arXiv:2603.00926](https://arxiv.org/html/2603.00926v1)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A dynamic action model framework that addresses the limitations of standard VLA action modeling, enabling more adaptive and robust robotic manipulation.

* ✨ **Key Innovations**:


  * Dynamic action modeling mechanism

  * Adaptive policy adaptation

  * Improved robustness to environment variations

  * Compatible with existing VLA backbones



***

#### InternVLA-A1: Unifying Understanding, Generation and Action for Robotic Manipulation



* 📄 **Paper**: [arXiv:2601.02456](https://arxiv.org/html/2601.02456v1/)

* 👥 **Authors**: InternRobotics Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A unified VLA model that integrates multimodal understanding, generative world modeling, and robotic action control into a single framework, enabling generalist robotic manipulation.

* ✨ **Key Innovations**:


  * Unified framework for understanding, generation and action

  * Synthetic + real-world joint pretraining

  * Sim-to-real transfer for real-world deployment

  * Strong generalization across diverse manipulation tasks



***

#### CogVLA: Cognition-Aligned Vision-Language-Action Model via Instruction-Driven Routing & Sparsification



* 📄 **Paper**: [OpenReview](https://openreview.net/forum?id=Dj3GWq0J30)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A cognition-aligned VLA model with instruction-driven dynamic routing and sparsification, enabling efficient and adaptive computation for robotic manipulation.

* ✨ **Key Innovations**:


  * Instruction-driven dynamic model routing

  * Adaptive computation sparsification

  * Improved efficiency for complex tasks

  * Cognition-aligned policy adaptation



***

#### SemanticVLA: Semantic-Aligned Sparsification and Enhancement for Efficient Robotic Manipulation



* 📄 **Paper**: [OpenReview](https://openreview.net/forum?id=nHlxsb98mk)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: Performs semantic-aligned sparsification and feature enhancement for efficient VLA, reducing computation cost while maintaining strong task performance.

* ✨ **Key Innovations**:


  * Semantic-aligned feature sparsification

  * Efficient computation for VLA models

  * Enhanced feature representation for precise control

  * Maintains performance with reduced compute



***

#### Goal-VLA: Generative World Model as Zero-Shot Robot Manipulation



* 📄 **Paper**: [ICRA 2026](http://m.toutiao.com/group/7622886310843318811/)

* 👥 **Authors**: NUS ShaoLin Team

* 🏛️ **Venue**: ICRA 2026

* 📝 **Description**: A decoupled hierarchical framework that uses image-generative VLMs as object-centric world models, enabling powerful zero-shot robotic manipulation without task-specific fine-tuning or paired action data.

* ✨ **Key Innovations**:


  * Generative world model for goal prediction

  * Decoupled hierarchical architecture

  * Zero-shot adaptation to novel tasks

  * No paired action data required



***

#### VITRA: Scalable Vision-Language-Action Model Pretraining for Robotic Manipulation with Real-Life Human Activity Videos



* 📄 **Paper**: [arXiv:2510.08104](https://arxiv.org/abs/2510.08104) | [Project Page](https://microsoft.github.io/VITRA/)

* 👥 **Authors**: Microsoft Research Team

* 🏛️ **Venue**: ICRA 2026

* 💻 **Code**: [GitHub](https://github.com/microsoft/VITRA) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/microsoft/VITRA?style=social)



* 📝 **Description**: Leverages large-scale unscripted real-world human activity videos for VLA pretraining, treating human hands as natural robot end-effectors to create a 1.2M episode dataset for scalable cross-domain transfer.

* ✨ **Key Innovations**:


  * Scalable pretraining from human in-the-wild videos

  * 1.2M episode human hand VLA dataset

  * Strong zero-shot transfer and few-shot adaptation

  * Compatible with diverse robot embodiments

* 🎯 **Performance**:



| Benchmark                 | Success Rate | Main Baselines          |
| ------------------------- | ------------ | ----------------------- |
| Cross-embodiment Transfer | 82%+         | OpenVLA: 67%, RT-2: 58% |
| Few-shot Fine-tuning      | 91%+         | From-scratch: 45%       |



***

### 2025

#### X-VLA: Soft-Prompted Transformer as a Scalable Cross-Embodiment Vision-Language-Action Model



* 📄 **Paper**: [arXiv:2510.10274](https://arxiv.org/abs/2510.10274) | [Project Page](https://thu-air-dream.github.io/X-VLA/)

* 👥 **Authors**: 2toINF Team

* 🏛️ **Venue**: IROS 2025 (Champion @ AgiBot World Challenge)

* 💻 **Code**: [GitHub](https://github.com/2toinf/X-VLA) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/2toinf/X-VLA?style=social)



* 📝 **Description**: A cross-embodiment VLA model with soft-prompt mechanism, enabling scalable and generalizable control across heterogeneous robotic platforms with a unified transformer backbone.

* ✨ **Key Innovations**:


  * Embodiment-specific soft prompts for cross-domain learning

  * Unified architecture across diverse robot embodiments

  * State-of-the-art generalization across simulation and real-world robots

  * Efficient LoRA fine-tuning for new tasks

* 🎯 **Performance**:



| Benchmark        | Success Rate | Main Baselines              |
| ---------------- | ------------ | --------------------------- |
| LIBERO Benchmark | 98.1%        | OpenVLA: 85.2%, Octo: 78.8% |
| CALVIN ABC-D     | 4.43 Score   | FLOWER: 4.53, OpenVLA: 3.49 |
| Bridge V2        | 95.8%        | RT-2: 58%, Octo: 52%        |



***

#### FLOWER: Democratizing Generalist Robot Policies with Efficient Vision-Language-Action Flow Policies



* 📄 **Paper**: [arXiv:2509.xxxx](https://www.microsoft.com/en-us/research/publication/flower-democratizing-generalist-robot-policies-with-efficient-vision-language-action-flow-policies/) | [Project Page](https://intuitive-robots.github.io/flower_vla/)

* 👥 **Authors**: Microsoft Research Team

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://intuitive-robots.github.io/flower_vla/)

* 📝 **Description**: An efficient 950M-parameter VLA model that achieves competitive performance with much smaller compute requirements, pretrained in only 200 H100 GPU hours across 190 tasks.

* ✨ **Key Innovations**:


  * Intermediate-modality fusion to reallocate model capacity

  * Action-specific Global-AdaLN conditioning for parameter efficiency

  * Extremely low training cost compared to large VLAs

  * State-of-the-art efficiency-performance trade-off

* 🎯 **Performance**:



| Benchmark              | Score/Rate | Main Baselines                |
| ---------------------- | ---------- | ----------------------------- |
| CALVIN ABC             | 4.53       | OpenVLA: 3.49, Octo: 2.88     |
| Cross-embodiment Tasks | 78%+       | Larger VLAs: 80% (comparable) |



***

#### UP-VLA: A Unified Understanding and Prediction Model for Embodied Agent



* 📄 **Paper**: [arXiv:2501.18867](https://arxiv.org/pdf/2501.18867)

* 👥 **Authors**: Tsinghua University Team

* 🏛️ **Venue**: ICML 2025

* 💻 **Code**: [GitHub](https://github.com/CladernyJorn/UP-VLA)

* 📝 **Description**: A unified VLA model co-trained with both multi-modal understanding and future prediction objectives, combining the strengths of VLMs and predictive models to enhance both semantic and spatial understanding.

* ✨ **Key Innovations**:


  * Joint pre-training with understanding and prediction tasks

  * Enhanced low-level spatial perception for precise control

  * 33% improvement on CALVIN ABC→D benchmark

  * Strong performance in both simulation and real-world tasks

* 🎯 **Performance**:



| Benchmark                | Improvement | Main Baselines              |
| ------------------------ | ----------- | --------------------------- |
| CALVIN ABC→D             | +33%        | Previous SOTA: Baseline VLA |
| Real-world Precise Tasks | +25%        | VLM-based VLA: Baseline     |



***

#### AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning



* 📄 **Paper**: [arXiv:2506.13757](https://arxiv.org/abs/2506.13757) | [Project Page](https://autovla.github.io/)

* 👥 **Authors**: UCLA Mobility Team

* 🏛️ **Venue**: NeurIPS 2025

* 💻 **Code**: [GitHub](https://github.com/ucla-mobility/AutoVLA)

* 📝 **Description**: Extends VLA paradigm to autonomous driving, enabling end-to-end vision-language-action control for driving tasks with adaptive reasoning and reinforcement fine-tuning.

* ✨ **Key Innovations**:


  * First VLA model tailored for autonomous driving

  * Adaptive reasoning for complex traffic scenarios

  * Reinforcement fine-tuning for long-horizon driving

  * Strong generalization to novel driving environments



***

#### OTTER: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction



* 📄 **Paper**: [ICML 2025](https://proceedings.mlr.press/v267/huang25u.html)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: ICML 2025

* 📝 **Description**: A VLA architecture that leverages text-aware visual feature extraction, selectively extracting task-relevant features aligned with language instructions, enabling frozen pre-trained VLMs to be used for robotic control.

* ✨ **Key Innovations**:


  * Text-aware selective visual feature extraction

  * Supports frozen pre-trained VLM backbones

  * Preserves VLM semantic knowledge for control

  * Strong zero-shot generalization capabilities



***

#### π0.5: A Vision-Language-Action Model with Open-World Generalization



* 📄 **Paper**: [arXiv:2504.16054](https://arxiv.org/pdf/2504.16054) | [Project Page](https://www.pi.website/blog/pi05)

* 👥 **Authors**: Physical Intelligence Team

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://github.com/Physical-Intelligence/openpi) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/Physical-Intelligence/openpi?style=social)



* 📝 **Description**: A vision-language-action model trained on diverse robotic data achieving strong generalization to novel objects, environments, and tasks in the open world.

* ✨ **Key Innovations**:


  * Open-world generalization capabilities

  * Trained on diverse multi-embodiment data

  * Strong zero-shot transfer across domains

  * Flow matching for action prediction

* 🎯 **Performance**:



| Task Category | Success Rate | Main Baselines          |
| ------------- | ------------ | ----------------------- |
| Novel Objects | 85%+         | RT-2: 62%, OpenVLA: 78% |
| Kitchen Tasks | 90%+         | Octo: 72%, RT-2: 68%    |



***

#### GR00T N1: An Open Foundation Model for Generalist Humanoid Robots



* 📄 **Paper**: [arXiv:2503.14734](https://arxiv.org/pdf/2503.14734)

* 👥 **Authors**: Nvidia Research Team

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://github.com/NVIDIA/Isaac-GR00T)

* 📝 **Description**: Open foundation model for humanoid robot control, enabling whole-body manipulation and locomotion through vision-language-action learning.

* ✨ **Key Innovations**:


  * Unified humanoid control framework

  * Whole-body coordination

  * Sim-to-real transfer for humanoids

  * Open-source and extensible

* 🎯 **Performance**: Demonstrates robust performance on humanoid manipulation and navigation tasks



***

#### VLA-0: Building State-of-the-Art VLAs with Zero Modification



* 📄 **Paper**: [arXiv:2510.13054](https://arxiv.org/pdf/2510.13054) | [Project](https://vla0.github.io/)

* 👥 **Authors**: Nvidia Research

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://github.com/NVlabs/vla0)

* 📝 **Description**: A framework for building VLA models without architectural modifications, achieving state-of-the-art performance through improved training recipes.

* ✨ **Key Innovations**:


  * Training recipe optimization

  * No architectural changes needed

  * Scalable to larger models

  * Strong baseline for VLA research



***

#### Gemini Robotics: Bringing AI into the Physical World



* 📄 **Report**: [Google DeepMind](https://storage.googleapis.com/deepmind-media/gemini-robotics/gemini_robotics_report.pdf)

* 👥 **Authors**: Google DeepMind Team

* 🏛️ **Venue**: Tech Report 2025

* 📝 **Description**: Integration of Gemini vision-language models with robotic systems for enhanced understanding and control.

* ✨ **Key Innovations**:


  * Leverages Gemini's multimodal capabilities

  * Enhanced reasoning for robotics

  * Real-world deployment results



***

#### Hi Robot: Hierarchical Vision-Language-Action Models



* 📄 **Paper**: [arXiv:2502.19417](https://arxiv.org/pdf/2502.19417) | [Project](https://www.pi.website/research/hirobot)

* 👥 **Authors**: Physical Intelligence

* 🏛️ **Venue**: arXiv 2025

* 📝 **Description**: Hierarchical approach to VLA enabling open-ended instruction following with improved long-horizon reasoning.

* ✨ **Key Innovations**:


  * Hierarchical policy decomposition

  * Better long-horizon planning

  * Open-ended task specification



***

### 2024

#### OpenVLA: An Open-Source Vision-Language-Action Model



* 📄 **Paper**: [arXiv:2406.09246](https://arxiv.org/abs/2406.09246) | [Project Page](https://openvla.github.io/)

* 👥 **Authors**: Moo Jin Kim, Karl Pertsch, et al.

* 🏛️ **Venue**: CoRL 2024

* 💻 **Code**: [GitHub](https://github.com/openvla/openvla) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/openvla/openvla?style=social)



* 📝 **Description**: A 7B-parameter open-source VLA model trained on 970k robot trajectories from the Open X-Embodiment dataset, achieving strong generalization across diverse manipulation tasks.

* ✨ **Key Innovations**:


  * Largest open-source VLA model with transparent training

  * Efficient fine-tuning for new tasks and embodiments

  * Unified policy across multiple robot platforms

  * Strong baseline for VLA research

* 🎯 **Performance**:



| Benchmark      | Success Rate | Main Baselines             |
| -------------- | ------------ | -------------------------- |
| CALVIN DDC     | 34.9%        | RT-2-X: 13.0%, Octo: 28.8% |
| Language-Table | 83.0%        | RT-2: 70.0%, Octo: 78.0%   |
| Bridge V2      | 67.0%        | RT-2: 58.0%, Octo: 52%     |



***

#### Octo: An Open-Source Generalist Robot Policy



* 📄 **Paper**: [arXiv:2405.12213](https://arxiv.org/abs/2405.12213) | [Project Page](https://octo-models.github.io/)

* 👥 **Authors**: Dibya Ghosh, Homer Walke, et al.

* 🏛️ **Venue**: RSS 2024

* 💻 **Code**: [GitHub](https://github.com/octo-models/octo) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/octo-models/octo?style=social)



* 📝 **Description**: A generalist transformer-based policy trained on 800k robot trajectories, designed for efficient fine-tuning on new tasks with minimal data.

* ✨ **Key Innovations**:


  * Flexible action spaces (joint positions, end-effector control)

  * Diffusion-based action prediction for multimodal distributions

  * Strong zero-shot transfer and few-shot learning capabilities

  * Open-source pre-trained models

* 🎯 **Performance**:



| Benchmark            | Success Rate | Main Baselines              |
| -------------------- | ------------ | --------------------------- |
| Bridge V2 (10 demos) | 52.0%        | RT-1: 38.0%, Scratch: 12.0% |
| Language-Table       | 78.0%        | RT-2: 70.0%, Scratch: 45.0% |
| CALVIN               | 28.8%        | RT-1: 18.0%, Gato: 15.0%    |



***

### 2023

#### RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control



* 📄 **Paper**: [arXiv:2307.15818](https://arxiv.org/abs/2307.15818) | [Project Page](https://robotics-transformer2.github.io/)

* 👥 **Authors**: Anthony Brohan, Noah Brown, et al.

* 🏛️ **Venue**: CoRL 2023

* 💻 **Code**: [Google DeepMind](https://github.com/google-deepmind/rt-2) (Limited Release)

* 📝 **Description**: Fine-tunes vision-language models (PaLM-E, PaLI) on robot data to transfer web-scale knowledge to robotic control, improving generalization and emergent capabilities.

* ✨ **Key Innovations**:


  * Co-fine-tuning on vision-language and robot action data

  * Leverages internet-scale pretraining for robotics

  * Emergent abilities: reasoning, symbol understanding, chain-of-thought

  * Strong generalization to novel objects and instructions

* 🎯 **Performance**:



| Benchmark             | Success Rate | Main Baselines           |
| --------------------- | ------------ | ------------------------ |
| Semantic Instructions | 62.0%        | RT-1: 32.0%, VIMA: 48.0% |
| Unseen Objects        | 79.0%        | RT-1: 57.0%, BC-Z: 48.0% |
| Long-Horizon Tasks    | 56.0%        | RT-1: 28.0%              |



***

#### PaLM-E: An Embodied Multimodal Language Model



* 📄 **Paper**: [arXiv:2303.03378](https://arxiv.org/abs/2303.03378) | [Project Page](https://palm-e.github.io/)

* 👥 **Authors**: Danny Driess, Fei Xia, et al.

* 🏛️ **Venue**: ICML 2023

* 💻 **Code**: [Google Research](https://github.com/google-research/google-research/tree/master/palm_e) (Limited)

* 📝 **Description**: Integrates visual, language, and continuous sensorimotor observations into a large language model (PaLM-540B) for embodied reasoning and control.

* ✨ **Key Innovations**:


  * Unified model for language, vision, and robot control

  * State-of-the-art multimodal reasoning

  * End-to-end training from pixels to actions

  * Largest embodied LLM (540B parameters)

* 🎯 **Performance**:



| Benchmark           | Success Rate | Main Baselines             |
| ------------------- | ------------ | -------------------------- |
| Language-Table      | 89.0%        | SayCan: 67.0%, BC-Z: 74.0% |
| Mobile Manipulation | 74.0%        | SayCan: 46.0%, RT-1: 62.0% |



***

#### VIMA: General Robot Manipulation with Multimodal Prompts



* 📄 **Paper**: [arXiv:2210.03094](https://arxiv.org/abs/2210.03094) | [Project Page](https://vimalabs.github.io/)

* 👥 **Authors**: Yunfan Jiang, Agrim Gupta, et al.

* 🏛️ **Venue**: ICML 2023

* 💻 **Code**: [GitHub](https://github.com/vimalabs/VIMA) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/vimalabs/VIMA?style=social)



* 📝 **Description**: Proposes multimodal prompting for robotic manipulation, enabling tasks specified through combinations of text, images, and demonstrations.

* ✨ **Key Innovations**:


  * Multimodal prompt interface for task specification

  * Transformer-based architecture for prompt conditioning

  * Strong compositional generalization

  * Novel benchmark (VIMA-Bench) with 17 task families

* 🎯 **Performance**:



| Benchmark            | Success Rate | Main Baselines                |
| -------------------- | ------------ | ----------------------------- |
| VIMA-Bench (Level 4) | 65.4%        | CLIP-Gato: 21.3%, LSTM: 43.2% |
| Compositional Tasks  | 58.0%        | BC: 12.0%, CLIP-BC: 28.0%     |



***

### 2022 and Earlier

#### RT-1: Robotics Transformer for Real-World Control at Scale



* 📄 **Paper**: [arXiv:2212.06817](https://arxiv.org/abs/2212.06817) | [Project Page](https://robotics-transformer1.github.io/)

* 👥 **Authors**: Anthony Brohan, et al.

* 🏛️ **Venue**: RSS 2023

* 💻 **Code**: [GitHub](https://github.com/google-research/robotics_transformer)

* 📝 **Description**: A transformer-based model trained on a large-scale robotic manipulation dataset (130k episodes), demonstrating strong generalization and efficient learning from demonstrations.

* ✨ **Key Innovations**:


  * Token-based action representation

  * Efficient training on large-scale robot data

  * Real-world deployment at scale (700+ tasks)

  * FiLM conditioning for task specification

* 🎯 **Performance**:



| Benchmark    | Success Rate | Main Baselines           |
| ------------ | ------------ | ------------------------ |
| 700 Tasks    | 97.0%        | BC-Z: 87.0%, Gato: 79.0% |
| Unseen Tasks | 76.0%        | BC-Z: 54.0%, Gato: 42.0% |
| Long-Horizon | 68.0%        | BC-Z: 38.0%              |



***

#### Gato: A Generalist Agent



* 📄 **Paper**: [arXiv:2205.06175](https://arxiv.org/abs/2205.06175)

* 👥 **Authors**: Scott Reed, et al.

* 🏛️ **Venue**: TMLR 2022

* 💻 **Code**: Not publicly available

* 📝 **Description**: A single generalist transformer that can play Atari games, caption images, chat, and control a real robot arm, all with the same network weights.

* ✨ **Key Innovations**:


  * Unified architecture across modalities and tasks

  * Tokenization of continuous and discrete data

  * Multi-task multi-domain learning at scale

  * 604 distinct tasks across multiple domains

* 🎯 **Performance**: Demonstrates competent performance across diverse tasks but specialized models often outperform in individual domains



***



***

## 🧭 Vision-Language-Navigation (VLN)

> *Vision-Language-Navigation focuses on enabling agents to navigate environments following natural language instructions, combining visual perception with language grounding.*

### 📊 Quick Index



| Year     | Title                                 | Institution           | Venue      | Paper                                                                                                                                                              | Code                                                    |
| -------- | ------------------------------------- | --------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------- |
| **2026** | OmniVLN                               | -                     | arXiv 2026 | [📄](https://arxiv.org/abs/2603.17351v1)                                                                                                                           | -                                                       |
| **2026** | VLN-R1                                | HKU & Shanghai AI Lab | arXiv 2026 | [📄](https://arxiv.org/pdf/2506.17221)                                                                                                                             | [💻](https://github.com/vlnr1/vln-r1)                   |
| **2026** | StreamVLN                             | InternRobotics        | ICRA 2026  | [📄](https://arxiv.org/abs/2507.05240)                                                                                                                             | [💻](https://github.com/InternRobotics/StreamVLN)       |
| **2026** | LaViRA                                | -                     | arXiv 2026 | [📄](https://arxiv.org/html/2510.19655v2)                                                                                                                          | -                                                       |
| **2026** | JanusVLN                              | -                     | arXiv 2026 | [📄](https://arxiv.org/html/2509.22548v2)                                                                                                                          | -                                                       |
| **2026** | Openfly                               | -                     | arXiv 2026 | [📄](https://arxiv.org/abs/2502.18041)                                                                                                                             | -                                                       |
| **2025** | SmartWay                              | -                     | IROS 2025  | [📄](https://github.com/sxyxs/SmartWay-Code)                                                                                                                       | [💻](https://github.com/sxyxs/SmartWay-Code)            |
| **2025** | VLFly                                 | NTU                   | arXiv 2025 | [📄](https://zzzzzyh111.github.io/VLFly/)                                                                                                                          | [💻](https://github.com/zzzzzyh111/Vision-Language-Fly) |
| **2025** | ETPNav: Evolving Topological Planning | -                     | TPAMI 2024 | [📄](https://arxiv.org/abs/2304.03047)                                                                                                                             | [💻](https://github.com/MarSaKi/ETPNav)                 |
| **2024** | NavGPT: LLM-based Reasoning           | -                     | AAAI 2024  | [📄](https://arxiv.org/abs/2305.16986)                                                                                                                             | [💻](https://github.com/GengzeZhou/NavGPT)              |
| **2023** | DUET: Cross-Modal Grounding           | -                     | AAAI 2023  | [📄](https://arxiv.org/abs/2301.00158)                                                                                                                             | [💻](https://github.com/cshizhe/VLN-DUET)               |
| **2023** | HAMT: Hierarchical Attention          | -                     | ICCV 2023  | [📄](https://arxiv.org/abs/2210.05448)                                                                                                                             | [💻](https://github.com/cshizhe/VLN-HAMT)               |
| **2021** | VLN-BERT: Recurrent BERT              | -                     | CVPR 2021  | [📄](https://arxiv.org/abs/2011.13922)                                                                                                                             | [💻](https://github.com/YicongHong/Recurrent-VLN-BERT)  |
| **2020** | REVERIE: Remote Grounding             | -                     | CVPR 2020  | [📄](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.html) | [💻](https://github.com/YuankaiQi/REVERIE)              |

### 2026

#### OmniVLN: Omnidirectional 3D Perception and Token-Efficient LLM Reasoning for Visual-Language Navigation across Air and Ground Platforms



* 📄 **Paper**: [arXiv:2603.17351](https://arxiv.org/abs/2603.17351v1)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A zero-shot VLN framework supporting both aerial and ground robots, combining omnidirectional 3D perception with token-efficient hierarchical LLM reasoning for cross-platform navigation.

* ✨ **Key Innovations**:


  * Unified framework for air-ground cross-platform navigation

  * Omnidirectional 3D spatial perception

  * Token-efficient hierarchical reasoning

  * Strong zero-shot generalization across embodiments



***

#### VLN-R1: Vision-Language Navigation via Reinforcement Fine-Tuning



* 📄 **Paper**: [arXiv:2506.17221](https://arxiv.org/pdf/2506.17221) | [Project Page](https://vlnr1.github.io)

* 👥 **Authors**: HKU & Shanghai AI Lab Team

* 🏛️ **Venue**: arXiv 2026

* 💻 **Code**: [GitHub](https://github.com/vlnr1/vln-r1)

* 📝 **Description**: An end-to-end framework that leverages LVLMs to directly translate egocentric video streams into continuous navigation actions, adopting GRPO-based reinforcement fine-tuning inspired by DeepSeek-R1.

* ✨ **Key Innovations**:


  * First RFT/GRPO-based training for VLN

  * End-to-end continuous navigation from egocentric videos

  * VLN-Ego dataset for LVLM navigation training

  * Long-short memory sampling for efficient video processing

* 🎯 **Performance**:



| Benchmark             | SPL   | Main Baselines                     |
| --------------------- | ----- | ---------------------------------- |
| R2R VLN-CE Val Unseen | 62.0% | StreamVLN: 58%, Previous SOTA: 55% |
| RxR VLN-CE Val Unseen | 48.0% | Previous SOTA: 42%                 |



***

#### StreamVLN: Streaming Vision-and-Language Navigation via SlowFast Context Modeling



* 📄 **Paper**: [arXiv:2507.05240](https://arxiv.org/abs/2507.05240)

* 👥 **Authors**: InternRobotics Team

* 🏛️ **Venue**: ICRA 2026

* 💻 **Code**: [GitHub](https://github.com/InternRobotics/StreamVLN)

* 📝 **Description**: A streaming VLN framework that processes continuous video input online, with SlowFast context modeling to balance long-term memory and real-time computation for efficient navigation.

* ✨ **Key Innovations**:


  * Online streaming processing for continuous video input

  * SlowFast context modeling with sliding KV cache

  * Real-time interaction support for physical robots

  * Large-scale ScaleVLN dataset for training

* 🎯 **Performance**:



| Benchmark             | SPL   | Main Baselines           |
| --------------------- | ----- | ------------------------ |
| R2R VLN-CE Val Unseen | 58.0% | NavGPT: 53%, ETPNav: 59% |
| RxR VLN-CE Val Unseen | 45.0% | Previous SOTA: 40%       |



***

#### LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments



* 📄 **Paper**: [arXiv:2510.19655](https://arxiv.org/html/2510.19655v2)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A zero-shot VLN framework that translates language-vision inputs into robot actions, enabling strong generalization to continuous environments without task-specific training.

* ✨ **Key Innovations**:


  * Zero-shot adaptation to continuous navigation environments

  * Language-vision-action translation mechanism

  * No fine-tuning required for new environments

  * Strong cross-domain generalization



***

#### JanusVLN: Decoupling Semantics and Spatiality with Dual Implicit Memory for Vision-Language Navigation



* 📄 **Paper**: [arXiv:2509.22548](https://arxiv.org/html/2509.22548v2)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: Decouples semantic and spatial modeling with dual implicit memory, enabling efficient streaming VLN with enhanced long-horizon reasoning without auxiliary 3D data.

* ✨ **Key Innovations**:


  * Dual implicit memory for semantics and spatiality

  * Efficient incremental updates for streaming processing

  * State-of-the-art results on VLN-CE without 3D data

  * Reduced redundant computation for real-time performance



***

#### Openfly: A comprehensive platform for aerial vision-language navigation



* 📄 **Paper**: [arXiv:2502.18041](https://arxiv.org/abs/2502.18041)

* 👥 **Authors**: Research Team

* 🏛️ **Venue**: arXiv 2026

* 📝 **Description**: A full-stack platform for aerial vision-language navigation, including a large-scale 100k trajectory dataset and a keyframe-aware VLN agent.

* ✨ **Key Innovations**:


  * Comprehensive aerial VLN platform with dataset and model

  * 100k trajectory large-scale aerial dataset

  * Keyframe-aware streaming VLN agent

  * Supports outdoor aerial navigation tasks



***

### 2025

#### SmartWay: Enhanced Waypoint Prediction and Backtracking for Zero-Shot Vision-and-Language Navigation



* 📄 **Paper**: [IROS 2025](https://github.com/sxyxs/SmartWay-Code)

* 👥 **Authors**: Xiangyu Shi, et al.

* 🏛️ **Venue**: IROS 2025

* 💻 **Code**: [GitHub](https://github.com/sxyxs/SmartWay-Code)

* 📝 **Description**: Enhances zero-shot VLN with improved waypoint prediction and backtracking mechanisms, enabling more robust navigation in unseen environments.

* ✨ **Key Innovations**:


  * Enhanced waypoint prediction for long-horizon planning

  * Integrated backtracking mechanism for error recovery

  * Strong zero-shot generalization without fine-tuning

  * Improved robustness to instruction ambiguity



***

#### VLFly: Grounded Vision-Language Navigation for UAVs with Open-Vocabulary Goal Understanding



* 📄 **Paper**: [Project Page](https://zzzzzyh111.github.io/VLFly/)

* 👥 **Authors**: Nanyang Technological University Team

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://github.com/zzzzzyh111/Vision-Language-Fly)

* 📝 **Description**: Aerial VLN framework with open-vocabulary goal understanding, enabling zero-shot drone navigation with natural language instructions.

* ✨ **Key Innovations**:


  * First open-vocabulary aerial VLN model

  * Zero-shot transfer to novel environments

  * Grounded goal understanding for drone tasks

  * Strong generalization to outdoor aerial scenarios



***

#### Embodied Navigation Foundation Model



* 📄 **Paper**: [arXiv:2509.12129](https://arxiv.org/pdf/2509.12129) | [Project](https://pku-epic.github.io/NavFoM-Web/)

* 👥 **Authors**: PKU EPIC Lab

* 🏛️ **Venue**: arXiv 2025

* 📝 **Description**: A foundation model for embodied navigation that generalizes across different environments, tasks, and embodiments.

* ✨ **Key Innovations**:


  * Unified navigation framework

  * Cross-embodiment generalization

  * Strong zero-shot capabilities

* 🎯 **Performance**: State-of-the-art results on multiple navigation benchmarks



***

#### Ground Slow, Move Fast: A Dual-System Foundation Model



* 📄 **Paper**: [arXiv:2512.08186](https://arxiv.org/pdf/2512.08186) | [Project](https://internrobotics.github.io/internvla-n1-dualvln.github.io/)

* 👥 **Authors**: InternRobotics

* 🏛️ **Venue**: arXiv 2025

* 💻 **Code**: [GitHub](https://github.com/InternRobotics/InternNav)

* 📝 **Description**: Dual-system approach with slow semantic grounding and fast motion planning for efficient VLN.

* ✨ **Key Innovations**:


  * Dual-system architecture

  * Efficient planning and grounding

  * Real-time navigation capabilities



***

#### OctoNav: Towards Generalist Embodied Navigation



* 📄 **Paper**: [arXiv:2506.09839](https://arxiv.org/pdf/2506.09839) | [Project](https://buaa-colalab.github.io/OctoNav/)

* 👥 **Authors**: BUAA CoLab

* 🏛️ **Venue**: arXiv 2025

* 📝 **Description**: Generalist navigation model capable of handling diverse navigation tasks with a unified architecture.

* ✨ **Key Innovations**:


  * Multi-task navigation support

  * Unified architecture across tasks

  * Strong generalization



***

### 2024

#### NavGPT: Explicit Reasoning in VLN with Large Language Models



* 📄 **Paper**: [arXiv:2305.16986](https://arxiv.org/abs/2305.16986)

* 👥 **Authors**: Gengze Zhou, et al.

* 🏛️ **Venue**: AAAI 2024

* 💻 **Code**: [GitHub](https://github.com/GengzeZhou/NavGPT)

* 📝 **Description**: Integrates GPT-based reasoning for explicit spatial and semantic reasoning in VLN tasks, improving navigation decisions through step-by-step explanations.

* ✨ **Key Innovations**:


  * LLM-based explicit reasoning module

  * Step-by-step decision explanation

  * Enhanced interpretability and debugging

  * Chain-of-thought for navigation

* 🎯 **Performance**:



| Benchmark          | SPL   | Main Baselines                            |
| ------------------ | ----- | ----------------------------------------- |
| R2R Val Unseen     | 53.0% | HAMT: 48.0%, DUET: 50.0%, VLN-BERT: 43.0% |
| REVERIE Val Unseen | 36.0% | DUET: 33.0%, HAMT: 30.0%                  |



***

#### ETPNav: Evolving Topological Planning for VLN



* 📄 **Paper**: [arXiv:2304.03047](https://arxiv.org/abs/2304.03047)

* 👥 **Authors**: Dong An, et al.

* 🏛️ **Venue**: TPAMI 2024

* 💻 **Code**: [GitHub](https://github.com/MarSaKi/ETPNav) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/MarSaKi/ETPNav?style=social)



* 📝 **Description**: Constructs and evolves a topological map during navigation to enable long-horizon reasoning, backtracking, and exploration.

* ✨ **Key Innovations**:


  * Dynamic topological map construction

  * Evolving planning strategy with backtracking

  * Improved long-horizon navigation

  * Graph-based spatial reasoning

* 🎯 **Performance**:



| Benchmark          | SPL   | Main Baselines                            |
| ------------------ | ----- | ----------------------------------------- |
| R2R Val Unseen     | 59.0% | DUET: 50.0%, HAMT: 48.0%, VLN-BERT: 43.0% |
| REVERIE Val Unseen | 38.0% | DUET: 33.0%, HAMT: 30.0%, VLN-BERT: 28.0% |



***

### 2023

#### DUET: Cross-Modal Semantic Grounding for VLN



* 📄 **Paper**: [arXiv:2301.00158](https://arxiv.org/abs/2301.00158)

* 👥 **Authors**: Chen Gao, et al.

* 🏛️ **Venue**: AAAI 2023

* 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-DUET) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/cshizhe/VLN-DUET?style=social)



* 📝 **Description**: Employs dual-scale graph transformer for fine-grained cross-modal alignment between language and visual observations, enabling better grounding.

* ✨ **Key Innovations**:


  * Dual-scale graph representation (coarse + fine)

  * Fine-grained semantic grounding

  * Object-level cross-modal attention

  * Improved instruction following

* 🎯 **Performance**:



| Benchmark          | SPL   | Main Baselines                               |
| ------------------ | ----- | -------------------------------------------- |
| R2R Val Unseen     | 50.0% | HAMT: 48.0%, EnvDrop: 44.0%, VLN-BERT: 43.0% |
| REVERIE Val Unseen | 33.0% | HAMT: 30.0%, VLN-BERT: 28.0%                 |



***

#### HAMT: Hierarchical Attention Map Transformer for VLN



* 📄 **Paper**: [arXiv:2210.05448](https://arxiv.org/abs/2210.05448)

* 👥 **Authors**: Chen Gao, et al.

* 🏛️ **Venue**: ICCV 2023

* 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-HAMT)

* 📝 **Description**: Uses hierarchical attention to model multi-scale spatial relationships in visual environments for improved navigation planning.

* ✨ **Key Innovations**:


  * Hierarchical spatial attention mechanism

  * Multi-scale visual feature aggregation

  * Effective long-range reasoning

  * Global-local context modeling

* 🎯 **Performance**:



| Benchmark          | SPL   | Main Baselines                  |
| ------------------ | ----- | ------------------------------- |
| R2R Val Unseen     | 48.0% | VLN-BERT: 43.0%, EnvDrop: 44.0% |
| REVERIE Val Unseen | 30.0% | VLN-BERT: 28.0%                 |



***

### 2021 and Earlier

#### VLN-BERT: A Recurrent Vision-and-Language BERT for Navigation



* 📄 **Paper**: [arXiv:2011.13922](https://arxiv.org/abs/2011.13922)

* 👥 **Authors**: Yicong Hong, et al.

* 🏛️ **Venue**: CVPR 2021

* 💻 **Code**: [GitHub](https://github.com/YicongHong/Recurrent-VLN-BERT)

* 📝 **Description**: Adapts BERT architecture for VLN with recurrent processing of visual and language tokens across navigation steps.

* ✨ **Key Innovations**:


  * Recurrent transformer architecture

  * Cross-modal pretraining for VLN

  * Temporal reasoning across steps

  * Vision-language alignment

* 🎯 **Performance**:



| Benchmark      | SPL   | Main Baselines                                 |
| -------------- | ----- | ---------------------------------------------- |
| R2R Val Unseen | 43.0% | EnvDrop: 44.0%, AuxRN: 39.0%, PREVALENT: 40.0% |



***

#### REVERIE: Remote Embodied Visual Referring Expression



* 📄 **Paper**: [CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.html)

* 👥 **Authors**: Yuankai Qi, et al.

* 🏛️ **Venue**: CVPR 2020

* 💻 **Code**: [GitHub](https://github.com/YuankaiQi/REVERIE) |&#x20;



![GitHub stars](https://img.shields.io/github/stars/YuankaiQi/REVERIE?style=social)



* 📝 **Description**: Introduces a new task combining VLN with remote object grounding, requiring agents to navigate and identify target objects based on natural language descriptions.

* ✨ **Key Innovations**:


  * Combined navigation and grounding task

  * New benchmark dataset (REVERIE)

  * Multi-task learning framework

  * Remote object localization

* 🎯 **Performance**: Establishes baseline benchmarks for the REVERIE task with various architectural approaches



***



***

## 📊 Datasets & Benchmarks

### VLA Benchmarks



| Dataset               | Description                               | Tasks                      | Environments          | Download                                                  |
| --------------------- | ----------------------------------------- | -------------------------- | --------------------- | --------------------------------------------------------- |
| **VLA-Arena**         | Systematic VLA model evaluation framework | 170 tasks across 4 domains | Simulation/Real-world | [Link](https://github.com/PKU-Alignment/VLA-Arena)        |
| **CALVIN**            | Long-horizon manipulation with language   | 34 tasks                   | 4 kitchen scenes      | [Link](https://github.com/mees/calvin)                    |
| **Language-Table**    | Language-conditioned block manipulation   | Pushing, rearrangement     | Tabletop              | [Link](https://github.com/google-research/language-table) |
| **RLBench**           | Large-scale robot learning benchmark      | 100+ diverse tasks         | Simulation            | [Link](https://github.com/stepjam/RLBench)                |
| **Open X-Embodiment** | Multi-robot dataset collection            | 970k+ trajectories         | 22 robots             | [Link](https://robotics-transformer-x.github.io/)         |
| **Bridge V2**         | Real-world kitchen manipulation           | Diverse kitchen tasks      | Real robot            | [Link](https://rail-berkeley.github.io/bridgedata/)       |
| **VIMA-Bench**        | Multimodal prompt-based manipulation      | 17 task families           | Simulation            | [Link](https://vimalabs.github.io/)                       |
| **MetaWorld**         | Multi-task manipulation benchmark         | 50 tasks                   | Simulation            | [Link](https://meta-world.github.io/)                     |

### VLN Benchmarks



| Dataset      | Description                                         | Environments | Trajectories        | Download                                                        |
| ------------ | --------------------------------------------------- | ------------ | ------------------- | --------------------------------------------------------------- |
| **VLNVerse** | Full-stack physical simulation navigation benchmark | Isaac Sim    | 263+ new tasks      | [Link](https://arxiv.org/abs/2512.19021)                        |
| **HA-VLN**   | Human-aware navigation with dynamic interactions    | Habitat      | -                   | [Link](https://openreview.net/forum?id=ZyKNHkpMw6)              |
| **VLN-Ego**  | Egocentric video-stream navigation dataset          | Habitat      | 90k+                | [Link](https://vlnr1.github.io)                                 |
| **R2R**      | Room-to-Room navigation                             | Matterport3D | 7k+                 | [Link](https://github.com/peteanderson80/Matterport3DSimulator) |
| **REVERIE**  | Navigation + object grounding                       | Matterport3D | 10k+                | [Link](https://github.com/YuankaiQi/REVERIE)                    |
| **RxR**      | Multilingual VLN                                    | Matterport3D | 126k+ (3 languages) | [Link](https://github.com/google-research-datasets/RxR)         |
| **CVDN**     | Continuous VLN with dense annotations               | Matterport3D | 8k+                 | [Link](https://github.com/mmurray/cvdn)                         |
| **R4R**      | Extended R2R paths                                  | Matterport3D | 233k+               | [Link](https://github.com/ronghanghu/vln_ce)                    |
| **ALFRED**   | Action Learning From Realistic Environments         | AI2-THOR     | 25k+                | [Link](https://askforalfred.com/)                               |



***

## 🔗 Related Resources

### 🛠️ Tools & Frameworks



* [AI2-THOR](https://ai2thor.allenai.org/) - Interactive 3D environments for embodied AI

* [Habitat](https://aihabitat.org/) - Simulation platform for embodied AI research

* [MuJoCo](https://mujoco.org/) - Physics engine for robotics simulation

* [PyRobot](https://pyrobot.org/) - Python robotics framework

* [ROS (Robot Operating System)](https://www.ros.org/) - Robotics middleware

### 📚 Related Awesome Lists



* [Awesome Embodied Vision](https://github.com/ChanganVR/awesome-embodied-vision)

* [Awesome Robotics](https://github.com/kiloreux/awesome-robotics)

* [Awesome Vision-and-Language](https://github.com/sangminwoo/awesome-vision-and-language)

* [Awesome Embodied VLA/VA/VLN](https://github.com/jonyzhang2023/awesome-embodied-vla-va-vln)

* [Awesome Visual-Language-Navigation (VLN)](https://github.com/kwanwaipang/awesome-vln)

### 📖 Tutorials & Courses



* [CS 224R: Deep Reinforcement Learning for Robotics (Stanford)](http://cs224r.stanford.edu/)

* [CS 287: Advanced Robotics (UC Berkeley)](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/)

* [Embodied AI Workshop Series](https://embodied-ai.org/)



***

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:



* Suggesting new papers

* Updating existing entries

* Reporting issues or broken links

**Contribution Criteria:**



* ✅ Open-source code available

* ✅ Published in peer-reviewed venue or on arXiv

* ✅ Significant impact (novelty, citations, reproducibility)



***

## 📖 Citation

If you find this repository helpful, please consider citing:



```
@misc{awesome-vision-language-robotics-with-code-anddatasets-2026,

&#x20; title={Awesome Vision-Language-Robotics: A Comprehensive Collection of VLA and VLN Research},

&#x20; author={Daojie Peng, Fulong Ma},

&#x20; year={2026},

&#x20; howpublished={\url{https://github.com/DaojiePENG/Awesome-Vision-Language-Robotics-with-Code-and-Datasets}}

}
```



***

## 📝 License

This repository is licensed under the [MIT License](LICENSE).



***

## 🙏 Acknowledgments



* Thanks to all researchers who open-source their work

* Inspired by the [Awesome](https://awesome.re) list movement

* Special thanks to contributors and the robotics community



***

**⭐ Star this repo if you find it helpful!**

**📧 Contact**: Daojie.PENG@qq.com | [GitHub](https://github.com/DaojiePENG)

**🔄 Last Updated**: March 2026



***

**Maintained with ❤️ by Daojie PENG | HKUST (Guangzhou) - Robotics and Autonomous Systems**
