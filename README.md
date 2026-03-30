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

<br>

---

</div>

## 📋 Table of Contents

| | Section | Description |
|:---:|:---|:---|
| 📚 | [Survey](#-survey) | Comprehensive surveys and review papers |
| 🎯 | [Vision-Language-Action (VLA)](#-vision-language-action-vla) | VLA models for robotic manipulation |
| 🧭 | [Vision-Language-Navigation (VLN)](#-vision-language-navigation-vln) | Navigation with language instructions |
| 📊 | [Datasets & Benchmarks](#-datasets--benchmarks) | Evaluation benchmarks and datasets |
| 🔗 | [Related Resources](#-related-resources) | Tools, frameworks, and related lists |
| 🤝 | [Contributing](#-contributing) | How to contribute |

<br>

> [!NOTE]
> **Paper Ordering** — Within each year, papers are generally listed in reverse chronological order. Particularly influential works may be highlighted.

> [!TIP]
> **Contributing** — This repository is continuously updated! Submit a [Pull Request](CONTRIBUTING.md) or open an [Issue](https://github.com/DaojiePENG/Awesome-Vision-Language-Robotics/issues) to add papers or suggest improvements.

<br>

---

## 📚 Survey

> *Comprehensive surveys and review papers covering the landscape of embodied AI and robot learning.*

<details open>
<summary><b>Recent Surveys (2025-2026)</b></summary>

- [2025] [**Science Robotics**] A Review of Learning-based Dynamics Models for Robotic Manipulation [[paper](https://albertboai.com/assets/pdf/2025_scirobotics.adt1497.pdf)]
- [2025] An Anatomy of Vision-Language-Action Models: From Modules to Milestones and Challenges [[paper](https://arxiv.org/pdf/2512.11362)] [[project](https://suyuz1.github.io/Survery/)]
- [2025] A Comprehensive Survey on World Models for Embodied AI [[paper](https://www.arxiv.org/pdf/2510.16732)] [[project](https://github.com/Li-Zn-H/AwesomeWorldModels)]
- [2025] Vision-Language-Action Models for Robotics: A Review Towards Real-World Applications [[paper](https://arxiv.org/pdf/2510.07077)]
- [2025] Pure Vision Language Action (VLA) Models: A Comprehensive Survey [[paper](https://arxiv.org/pdf/2509.19012)]
- [2025] Large VLM-based Vision-Language-Action Models for Robotic Manipulation: A Survey [[paper](https://arxiv.org/pdf/2508.13073)] [[project](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation)]
- [2025] Foundation Model Driven Robotics: A Comprehensive Review [[paper](https://arxiv.org/pdf/2507.10087)]
- [2025] [**PKU-PsiBot**] A Survey on Vision-Language-Action Models: An Action Tokenization Perspective [[paper](https://arxiv.org/pdf/2507.01925)]
- [2025] [**IJRR 25**] Foundation Models in Robotics: Applications, Challenges, and the Future [[paper](https://arxiv.org/pdf/2312.07843)] [[project](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]
- [2025] A Survey on Diffusion Policy for Robotic Manipulation [[paper](https://doi.org/10.36227/techrxiv.174378343.39356214/v1)] [[project](https://github.com/HITSZ-Robotics/DiffusionPolicy-Robotics)]
- [2024] A Survey on Vision-Language-Action Models for Embodied AI [[paper](https://arxiv.org/abs/2405.14093)]
- [2024] Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI [[paper](https://arxiv.org/pdf/2407.06886)]
- [2024] Vision-language navigation: a survey and taxonomy [[paper](https://arxiv.org/pdf/2108.11544)]

</details>

<br>

---

## 🎯 Vision-Language-Action (VLA)

> *Vision-Language-Action models bridge natural language understanding with robotic control, enabling robots to follow high-level instructions and perform manipulation tasks.*

### 📊 Quick Index

<details>
<summary><b>VLA Papers by Year (Click to expand table)</b></summary>

| Year | Title | Institution | Venue | Paper | Code |
|:----:|:------|:------------|:------|:-----:|:----:|
| **2025** | π0.5: Open-World Generalization | Physical Intelligence | arXiv | [📄](https://arxiv.org/pdf/2504.16054) | [💻](https://github.com/Physical-Intelligence/openpi) |
| **2025** | GR00T N1: Humanoid Foundation Model | Nvidia | arXiv | [📄](https://arxiv.org/pdf/2503.14734) | [💻](https://github.com/NVIDIA/Isaac-GR00T) |
| **2025** | OpenVLA: Open-Source VLA Model | UC Berkeley | CoRL 2024 | [📄](https://arxiv.org/abs/2406.09246) | [💻](https://github.com/openvla/openvla) |
| **2024** | Octo: Generalist Robot Policy | UC Berkeley | RSS 2024 | [📄](https://arxiv.org/abs/2405.12213) | [💻](https://github.com/octo-models/octo) |
| **2024** | RT-2: Transfer Web Knowledge | Google DeepMind | CoRL 2023 | [📄](https://arxiv.org/abs/2307.15818) | [💻](https://github.com/google-deepmind/rt-2) |
| **2023** | PaLM-E: Embodied Multimodal LLM | Google | ICML 2023 | [📄](https://arxiv.org/abs/2303.03378) | - |
| **2023** | VIMA: Multimodal Prompting | Stanford/NVIDIA | ICML 2023 | [📄](https://arxiv.org/abs/2210.03094) | [💻](https://github.com/vimalabs/VIMA) |
| **2022** | RT-1: Robotics Transformer | Google | RSS 2023 | [📄](https://arxiv.org/abs/2212.06817) | [💻](https://github.com/google-research/robotics_transformer) |
| **2022** | Gato: Generalist Agent | DeepMind | TMLR 2022 | [📄](https://arxiv.org/abs/2205.06175) | - |

</details>

<br>

### 2025

<details open>
<summary><b>Show 2025 Papers</b></summary>

#### π0.5: A Vision-Language-Action Model with Open-World Generalization

- 📄 **Paper**: [arXiv:2504.16054](https://arxiv.org/pdf/2504.16054) | [Project Page](https://www.pi.website/blog/pi05)
- 👥 **Authors**: Physical Intelligence Team
- 🏛️ **Venue**: arXiv 2025
- 💻 **Code**: [GitHub](https://github.com/Physical-Intelligence/openpi) | ![GitHub stars](https://img.shields.io/github/stars/Physical-Intelligence/openpi?style=social)
- 📝 **Description**: A vision-language-action model trained on diverse robotic data achieving strong generalization to novel objects, environments, and tasks in the open world.
- ✨ **Key Innovations**:
  - Open-world generalization capabilities
  - Trained on diverse multi-embodiment data
  - Strong zero-shot transfer across domains
  - Flow matching for action prediction
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Task Category | Success Rate | Main Baselines |
  |---------------|-------------|----------------|
  | Novel Objects | 85%+ | RT-2: 62%, OpenVLA: 78% |
  | Kitchen Tasks | 90%+ | Octo: 72%, RT-2: 68% |

  </details>

---

#### GR00T N1: An Open Foundation Model for Generalist Humanoid Robots

- 📄 **Paper**: [arXiv:2503.14734](https://arxiv.org/pdf/2503.14734)
- 👥 **Authors**: Nvidia Research Team
- 🏛️ **Venue**: arXiv 2025
- 💻 **Code**: [GitHub](https://github.com/NVIDIA/Isaac-GR00T)
- 📝 **Description**: Open foundation model for humanoid robot control, enabling whole-body manipulation and locomotion through vision-language-action learning.
- ✨ **Key Innovations**:
  - Unified humanoid control framework
  - Whole-body coordination
  - Sim-to-real transfer for humanoids
  - Open-source and extensible
- 🎯 **Performance**: Demonstrates robust performance on humanoid manipulation and navigation tasks

---

#### VLA-0: Building State-of-the-Art VLAs with Zero Modification

- 📄 **Paper**: [arXiv:2510.13054](https://arxiv.org/pdf/2510.13054) | [Project](https://vla0.github.io/)
- 👥 **Authors**: Nvidia Research
- 🏛️ **Venue**: arXiv 2025
- 💻 **Code**: [GitHub](https://github.com/NVlabs/vla0)
- 📝 **Description**: A framework for building VLA models without architectural modifications, achieving state-of-the-art performance through improved training recipes.
- ✨ **Key Innovations**:
  - Training recipe optimization
  - No architectural changes needed
  - Scalable to larger models
  - Strong baseline for VLA research

---

#### Gemini Robotics: Bringing AI into the Physical World

- 📄 **Report**: [Google DeepMind](https://storage.googleapis.com/deepmind-media/gemini-robotics/gemini_robotics_report.pdf)
- 👥 **Authors**: Google DeepMind Team
- 🏛️ **Venue**: Tech Report 2025
- 📝 **Description**: Integration of Gemini vision-language models with robotic systems for enhanced understanding and control.
- ✨ **Key Innovations**:
  - Leverages Gemini's multimodal capabilities
  - Enhanced reasoning for robotics
  - Real-world deployment results

---

#### Hi Robot: Hierarchical Vision-Language-Action Models

- 📄 **Paper**: [arXiv:2502.19417](https://arxiv.org/pdf/2502.19417) | [Project](https://www.pi.website/research/hirobot)
- 👥 **Authors**: Physical Intelligence
- 🏛️ **Venue**: arXiv 2025
- 📝 **Description**: Hierarchical approach to VLA enabling open-ended instruction following with improved long-horizon reasoning.
- ✨ **Key Innovations**:
  - Hierarchical policy decomposition
  - Better long-horizon planning
  - Open-ended task specification

---

</details>

### 2024

<details>
<summary><b>Show 2024 Papers</b></summary>

#### OpenVLA: An Open-Source Vision-Language-Action Model

- 📄 **Paper**: [arXiv:2406.09246](https://arxiv.org/abs/2406.09246) | [Project Page](https://openvla.github.io/)
- 👥 **Authors**: Moo Jin Kim, Karl Pertsch, et al.
- 🏛️ **Venue**: CoRL 2024
- 💻 **Code**: [GitHub](https://github.com/openvla/openvla) | ![GitHub stars](https://img.shields.io/github/stars/openvla/openvla?style=social)
- 📝 **Description**: A 7B-parameter open-source VLA model trained on 970k robot trajectories from the Open X-Embodiment dataset, achieving strong generalization across diverse manipulation tasks.
- ✨ **Key Innovations**:
  - Largest open-source VLA model with transparent training
  - Efficient fine-tuning for new tasks and embodiments
  - Unified policy across multiple robot platforms
  - Strong baseline for VLA research
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | CALVIN DDC | 34.9% | RT-2-X: 13.0%, Octo: 28.8% |
  | Language-Table | 83.0% | RT-2: 70.0%, Octo: 78.0% |
  | Bridge V2 | 67.0% | RT-2: 58.0%, Octo: 52.0% |

  </details>

---

#### Octo: An Open-Source Generalist Robot Policy

- 📄 **Paper**: [arXiv:2405.12213](https://arxiv.org/abs/2405.12213) | [Project Page](https://octo-models.github.io/)
- 👥 **Authors**: Dibya Ghosh, Homer Walke, et al.
- 🏛️ **Venue**: RSS 2024
- 💻 **Code**: [GitHub](https://github.com/octo-models/octo) | ![GitHub stars](https://img.shields.io/github/stars/octo-models/octo?style=social)
- 📝 **Description**: A generalist transformer-based policy trained on 800k robot trajectories, designed for efficient fine-tuning on new tasks with minimal data.
- ✨ **Key Innovations**:
  - Flexible action spaces (joint positions, end-effector control)
  - Diffusion-based action prediction for multimodal distributions
  - Strong zero-shot transfer and few-shot learning capabilities
  - Open-source pre-trained models
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Bridge V2 (10 demos) | 52.0% | RT-1: 38.0%, Scratch: 12.0% |
  | Language-Table | 78.0% | RT-2: 70.0%, Scratch: 45.0% |
  | CALVIN | 28.8% | RT-1: 18.0%, Gato: 15.0% |

  </details>

---

</details>

### 2023

<details>
<summary><b>Show 2023 Papers</b></summary>

#### RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control

- 📄 **Paper**: [arXiv:2307.15818](https://arxiv.org/abs/2307.15818) | [Project Page](https://robotics-transformer2.github.io/)
- 👥 **Authors**: Anthony Brohan, Noah Brown, et al.
- 🏛️ **Venue**: CoRL 2023
- 💻 **Code**: [Google DeepMind](https://github.com/google-deepmind/rt-2) (Limited Release)
- 📝 **Description**: Fine-tunes vision-language models (PaLM-E, PaLI) on robot data to transfer web-scale knowledge to robotic control, improving generalization and emergent capabilities.
- ✨ **Key Innovations**:
  - Co-fine-tuning on vision-language and robot action data
  - Leverages internet-scale pretraining for robotics
  - Emergent abilities: reasoning, symbol understanding, chain-of-thought
  - Strong generalization to novel objects and instructions
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Semantic Instructions | 62.0% | RT-1: 32.0%, VIMA: 48.0% |
  | Unseen Objects | 79.0% | RT-1: 57.0%, BC-Z: 48.0% |
  | Long-Horizon Tasks | 56.0% | RT-1: 28.0% |

  </details>

---

#### PaLM-E: An Embodied Multimodal Language Model

- 📄 **Paper**: [arXiv:2303.03378](https://arxiv.org/abs/2303.03378) | [Project Page](https://palm-e.github.io/)
- 👥 **Authors**: Danny Driess, Fei Xia, et al.
- 🏛️ **Venue**: ICML 2023
- 💻 **Code**: [Google Research](https://github.com/google-research/google-research/tree/master/palm_e) (Limited)
- 📝 **Description**: Integrates visual, language, and continuous sensorimotor observations into a large language model (PaLM-540B) for embodied reasoning and control.
- ✨ **Key Innovations**:
  - Unified model for language, vision, and robot control
  - State-of-the-art multimodal reasoning
  - End-to-end training from pixels to actions
  - Largest embodied LLM (540B parameters)
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Language-Table | 89.0% | SayCan: 67.0%, BC-Z: 74.0% |
  | Mobile Manipulation | 74.0% | SayCan: 46.0%, RT-1: 62.0% |

  </details>

---

#### VIMA: General Robot Manipulation with Multimodal Prompts

- 📄 **Paper**: [arXiv:2210.03094](https://arxiv.org/abs/2210.03094) | [Project Page](https://vimalabs.github.io/)
- 👥 **Authors**: Yunfan Jiang, Agrim Gupta, et al.
- 🏛️ **Venue**: ICML 2023
- 💻 **Code**: [GitHub](https://github.com/vimalabs/VIMA) | ![GitHub stars](https://img.shields.io/github/stars/vimalabs/VIMA?style=social)
- 📝 **Description**: Proposes multimodal prompting for robotic manipulation, enabling tasks specified through combinations of text, images, and demonstrations.
- ✨ **Key Innovations**:
  - Multimodal prompt interface for task specification
  - Transformer-based architecture for prompt conditioning
  - Strong compositional generalization
  - Novel benchmark (VIMA-Bench) with 17 task families
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | VIMA-Bench (Level 4) | 65.4% | CLIP-Gato: 21.3%, LSTM: 43.2% |
  | Compositional Tasks | 58.0% | BC: 12.0%, CLIP-BC: 28.0% |

  </details>

---

</details>

### 2022 and Earlier

<details>
<summary><b>Show 2022 and Earlier Papers</b></summary>

#### RT-1: Robotics Transformer for Real-World Control at Scale

- 📄 **Paper**: [arXiv:2212.06817](https://arxiv.org/abs/2212.06817) | [Project Page](https://robotics-transformer1.github.io/)
- 👥 **Authors**: Anthony Brohan, et al.
- 🏛️ **Venue**: RSS 2023
- 💻 **Code**: [GitHub](https://github.com/google-research/robotics_transformer)
- 📝 **Description**: A transformer-based model trained on a large-scale robotic manipulation dataset (130k episodes), demonstrating strong generalization and efficient learning from demonstrations.
- ✨ **Key Innovations**:
  - Token-based action representation
  - Efficient training on large-scale robot data
  - Real-world deployment at scale (700+ tasks)
  - FiLM conditioning for task specification
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | 700 Tasks | 97.0% | BC-Z: 87.0%, Gato: 79.0% |
  | Unseen Tasks | 76.0% | BC-Z: 54.0%, Gato: 42.0% |
  | Long-Horizon | 68.0% | BC-Z: 38.0% |

  </details>

---

#### Gato: A Generalist Agent

- 📄 **Paper**: [arXiv:2205.06175](https://arxiv.org/abs/2205.06175)
- 👥 **Authors**: Scott Reed, et al.
- 🏛️ **Venue**: TMLR 2022
- 💻 **Code**: Not publicly available
- 📝 **Description**: A single generalist transformer that can play Atari games, caption images, chat, and control a real robot arm, all with the same network weights.
- ✨ **Key Innovations**:
  - Unified architecture across modalities and tasks
  - Tokenization of continuous and discrete data
  - Multi-task multi-domain learning at scale
  - 604 distinct tasks across multiple domains
- 🎯 **Performance**: Demonstrates competent performance across diverse tasks but specialized models often outperform in individual domains

---

</details>

<br>

---

## 🧭 Vision-Language-Navigation (VLN)

> *Vision-Language-Navigation focuses on enabling agents to navigate environments following natural language instructions, combining visual perception with language grounding.*

### 📊 Quick Index

<details>
<summary><b>VLN Papers by Year (Click to expand table)</b></summary>

| Year | Title | Institution | Venue | Paper | Code |
|:----:|:------|:------------|:------|:-----:|:----:|
| **2025** | ETPNav: Evolving Topological Planning | - | TPAMI 2024 | [📄](https://arxiv.org/abs/2304.03047) | [💻](https://github.com/MarSaKi/ETPNav) |
| **2024** | NavGPT: LLM-based Reasoning | - | AAAI 2024 | [📄](https://arxiv.org/abs/2305.16986) | [💻](https://github.com/GengzeZhou/NavGPT) |
| **2023** | DUET: Cross-Modal Grounding | - | AAAI 2023 | [📄](https://arxiv.org/abs/2301.00158) | [💻](https://github.com/cshizhe/VLN-DUET) |
| **2023** | HAMT: Hierarchical Attention | - | ICCV 2023 | [📄](https://arxiv.org/abs/2210.05448) | [💻](https://github.com/cshizhe/VLN-HAMT) |
| **2021** | VLN-BERT: Recurrent BERT | - | CVPR 2021 | [📄](https://arxiv.org/abs/2011.13922) | [💻](https://github.com/YicongHong/Recurrent-VLN-BERT) |
| **2020** | REVERIE: Remote Grounding | - | CVPR 2020 | [📄](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.html) | [💻](https://github.com/YuankaiQi/REVERIE) |

</details>

<br>

### 2025

<details open>
<summary><b>Show 2025 Papers</b></summary>

#### Embodied Navigation Foundation Model

- 📄 **Paper**: [arXiv:2509.12129](https://arxiv.org/pdf/2509.12129) | [Project](https://pku-epic.github.io/NavFoM-Web/)
- 👥 **Authors**: PKU EPIC Lab
- 🏛️ **Venue**: arXiv 2025
- 📝 **Description**: A foundation model for embodied navigation that generalizes across different environments, tasks, and embodiments.
- ✨ **Key Innovations**:
  - Unified navigation framework
  - Cross-embodiment generalization
  - Strong zero-shot capabilities
- 🎯 **Performance**: State-of-the-art results on multiple navigation benchmarks

---

#### Ground Slow, Move Fast: A Dual-System Foundation Model

- 📄 **Paper**: [arXiv:2512.08186](https://arxiv.org/pdf/2512.08186) | [Project](https://internrobotics.github.io/internvla-n1-dualvln.github.io/)
- 👥 **Authors**: InternRobotics
- 🏛️ **Venue**: arXiv 2025
- 💻 **Code**: [GitHub](https://github.com/InternRobotics/InternNav)
- 📝 **Description**: Dual-system approach with slow semantic grounding and fast motion planning for efficient VLN.
- ✨ **Key Innovations**:
  - Dual-system architecture
  - Efficient planning and grounding
  - Real-time navigation capabilities

---

#### OctoNav: Towards Generalist Embodied Navigation

- 📄 **Paper**: [arXiv:2506.09839](https://arxiv.org/pdf/2506.09839) | [Project](https://buaa-colalab.github.io/OctoNav/)
- 👥 **Authors**: BUAA CoLab
- 🏛️ **Venue**: arXiv 2025
- 📝 **Description**: Generalist navigation model capable of handling diverse navigation tasks with a unified architecture.
- ✨ **Key Innovations**:
  - Multi-task navigation support
  - Unified architecture across tasks
  - Strong generalization

---

</details>

### 2024

<details>
<summary><b>Show 2024 Papers</b></summary>

#### NavGPT: Explicit Reasoning in VLN with Large Language Models

- 📄 **Paper**: [arXiv:2305.16986](https://arxiv.org/abs/2305.16986)
- 👥 **Authors**: Gengze Zhou, et al.
- 🏛️ **Venue**: AAAI 2024
- 💻 **Code**: [GitHub](https://github.com/GengzeZhou/NavGPT)
- 📝 **Description**: Integrates GPT-based reasoning for explicit spatial and semantic reasoning in VLN tasks, improving navigation decisions through step-by-step explanations.
- ✨ **Key Innovations**:
  - LLM-based explicit reasoning module
  - Step-by-step decision explanation
  - Enhanced interpretability and debugging
  - Chain-of-thought for navigation
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 53.0% | HAMT: 48.0%, DUET: 50.0%, VLN-BERT: 43.0% |
  | REVERIE Val Unseen | 36.0% | DUET: 33.0%, HAMT: 30.0% |

  </details>

---

#### ETPNav: Evolving Topological Planning for VLN

- 📄 **Paper**: [arXiv:2304.03047](https://arxiv.org/abs/2304.03047)
- 👥 **Authors**: Dong An, et al.
- 🏛️ **Venue**: TPAMI 2024
- 💻 **Code**: [GitHub](https://github.com/MarSaKi/ETPNav) | ![GitHub stars](https://img.shields.io/github/stars/MarSaKi/ETPNav?style=social)
- 📝 **Description**: Constructs and evolves a topological map during navigation to enable long-horizon reasoning, backtracking, and exploration.
- ✨ **Key Innovations**:
  - Dynamic topological map construction
  - Evolving planning strategy with backtracking
  - Improved long-horizon navigation
  - Graph-based spatial reasoning
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 59.0% | DUET: 50.0%, HAMT: 48.0%, VLN-BERT: 43.0% |
  | REVERIE Val Unseen | 38.0% | DUET: 33.0%, HAMT: 30.0%, VLN-BERT: 28.0% |

  </details>

---

</details>

### 2023

<details>
<summary><b>Show 2023 Papers</b></summary>

#### DUET: Cross-Modal Semantic Grounding for VLN

- 📄 **Paper**: [arXiv:2301.00158](https://arxiv.org/abs/2301.00158)
- 👥 **Authors**: Chen Gao, et al.
- 🏛️ **Venue**: AAAI 2023
- 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-DUET) | ![GitHub stars](https://img.shields.io/github/stars/cshizhe/VLN-DUET?style=social)
- 📝 **Description**: Employs dual-scale graph transformer for fine-grained cross-modal alignment between language and visual observations, enabling better grounding.
- ✨ **Key Innovations**:
  - Dual-scale graph representation (coarse + fine)
  - Fine-grained semantic grounding
  - Object-level cross-modal attention
  - Improved instruction following
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 50.0% | HAMT: 48.0%, EnvDrop: 44.0%, VLN-BERT: 43.0% |
  | REVERIE Val Unseen | 33.0% | HAMT: 30.0%, VLN-BERT: 28.0% |

  </details>

---

#### HAMT: Hierarchical Attention Map Transformer for VLN

- 📄 **Paper**: [arXiv:2210.05448](https://arxiv.org/abs/2210.05448)
- 👥 **Authors**: Chen Gao, et al.
- 🏛️ **Venue**: ICCV 2023
- 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-HAMT)
- 📝 **Description**: Uses hierarchical attention to model multi-scale spatial relationships in visual environments for improved navigation planning.
- ✨ **Key Innovations**:
  - Hierarchical spatial attention mechanism
  - Multi-scale visual feature aggregation
  - Effective long-range reasoning
  - Global-local context modeling
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 48.0% | VLN-BERT: 43.0%, EnvDrop: 44.0% |
  | REVERIE Val Unseen | 30.0% | VLN-BERT: 28.0% |

  </details>

---

</details>

### 2021 and Earlier

<details>
<summary><b>Show 2021 and Earlier Papers</b></summary>

#### VLN-BERT: A Recurrent Vision-and-Language BERT for Navigation

- 📄 **Paper**: [arXiv:2011.13922](https://arxiv.org/abs/2011.13922)
- 👥 **Authors**: Yicong Hong, et al.
- 🏛️ **Venue**: CVPR 2021
- 💻 **Code**: [GitHub](https://github.com/YicongHong/Recurrent-VLN-BERT)
- 📝 **Description**: Adapts BERT architecture for VLN with recurrent processing of visual and language tokens across navigation steps.
- ✨ **Key Innovations**:
  - Recurrent transformer architecture
  - Cross-modal pretraining for VLN
  - Temporal reasoning across steps
  - Vision-language alignment
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 43.0% | EnvDrop: 44.0%, AuxRN: 39.0%, PREVALENT: 40.0% |

  </details>

---

#### REVERIE: Remote Embodied Visual Referring Expression

- 📄 **Paper**: [CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.html)
- 👥 **Authors**: Yuankai Qi, et al.
- 🏛️ **Venue**: CVPR 2020
- 💻 **Code**: [GitHub](https://github.com/YuankaiQi/REVERIE) | ![GitHub stars](https://img.shields.io/github/stars/YuankaiQi/REVERIE?style=social)
- 📝 **Description**: Introduces a new task combining VLN with remote object grounding, requiring agents to navigate and identify target objects based on natural language descriptions.
- ✨ **Key Innovations**:
  - Combined navigation and grounding task
  - New benchmark dataset (REVERIE)
  - Multi-task learning framework
  - Remote object localization
- 🎯 **Performance**: Establishes baseline benchmarks for the REVERIE task with various architectural approaches

---

</details>

<br>

---

## 📊 Datasets & Benchmarks

### VLA Benchmarks

| Dataset | Description | Tasks | Environments | Download |
|---------|-------------|-------|--------------|----------|
| **CALVIN** | Long-horizon manipulation with language | 34 tasks | 4 kitchen scenes | [Link](https://github.com/mees/calvin) |
| **Language-Table** | Language-conditioned block manipulation | Pushing, rearrangement | Tabletop | [Link](https://github.com/google-research/language-table) |
| **RLBench** | Large-scale robot learning benchmark | 100+ diverse tasks | Simulation | [Link](https://github.com/stepjam/RLBench) |
| **Open X-Embodiment** | Multi-robot dataset collection | 970k+ trajectories | 22 robots | [Link](https://robotics-transformer-x.github.io/) |
| **Bridge V2** | Real-world kitchen manipulation | Diverse kitchen tasks | Real robot | [Link](https://rail-berkeley.github.io/bridgedata/) |
| **VIMA-Bench** | Multimodal prompt-based manipulation | 17 task families | Simulation | [Link](https://vimalabs.github.io/) |
| **MetaWorld** | Multi-task manipulation benchmark | 50 tasks | Simulation | [Link](https://meta-world.github.io/) |

### VLN Benchmarks

| Dataset | Description | Environments | Trajectories | Download |
|---------|-------------|--------------|--------------|----------|
| **R2R** | Room-to-Room navigation | Matterport3D | 7k+ | [Link](https://github.com/peteanderson80/Matterport3DSimulator) |
| **REVERIE** | Navigation + object grounding | Matterport3D | 10k+ | [Link](https://github.com/YuankaiQi/REVERIE) |
| **RxR** | Multilingual VLN | Matterport3D | 126k+ (3 languages) | [Link](https://github.com/google-research-datasets/RxR) |
| **CVDN** | Continuous VLN with dense annotations | Matterport3D | 8k+ | [Link](https://github.com/mmurray/cvdn) |
| **R4R** | Extended R2R paths | Matterport3D | 233k+ | [Link](https://github.com/ronghanghu/vln_ce) |
| **ALFRED** | Action Learning From Realistic Environments | AI2-THOR | 25k+ | [Link](https://askforalfred.com/) |

<br>

---

## 🔗 Related Resources

### 🛠️ Tools & Frameworks

- [**AI2-THOR**](https://ai2thor.allenai.org/) - Interactive 3D environments for embodied AI
- [**Habitat**](https://aihabitat.org/) - Simulation platform for embodied AI research
- [**MuJoCo**](https://mujoco.org/) - Physics engine for robotics simulation
- [**PyRobot**](https://pyrobot.org/) - Python robotics framework
- [**ROS (Robot Operating System)**](https://www.ros.org/) - Robotics middleware

### 📚 Related Awesome Lists

- [Awesome Embodied Vision](https://github.com/ChanganVR/awesome-embodied-vision)
- [Awesome Robotics](https://github.com/kiloreux/awesome-robotics)
- [Awesome Vision-and-Language](https://github.com/sangminwoo/awesome-vision-and-language)
- [Awesome Embodied VLA/VA/VLN](https://github.com/jonyzhang2023/awesome-embodied-vla-va-vln)

### 📖 Tutorials & Courses

- [CS 224R: Deep Reinforcement Learning for Robotics (Stanford)](http://cs224r.stanford.edu/)
- [CS 287: Advanced Robotics (UC Berkeley)](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/)
- [Embodied AI Workshop Series](https://embodied-ai.org/)

<br>

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Suggesting new papers
- Updating existing entries
- Reporting issues or broken links

**Contribution Criteria:**
- ✅ Open-source code available
- ✅ Published in peer-reviewed venue or on arXiv
- ✅ Significant impact (novelty, citations, reproducibility)

<br>

---

## 📖 Citation

If you find this repository helpful, please consider citing:

```bibtex
@misc{awesome-vision-language-robotics-2026,
  title={Awesome Vision-Language-Robotics: A Comprehensive Collection of VLA and VLN Research},
  author={Daojie Peng},
  year={2026},
  howpublished={\url{https://github.com/DaojiePENG/Awesome-Vision-Language-Robotics}}
}
```

<br>

---

## 📝 License

This repository is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Thanks to all researchers who open-source their work
- Inspired by the [Awesome](https://awesome.re) list movement
- Special thanks to contributors and the robotics community

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

**📧 Contact**: Daojie.PENG@qq.com | [GitHub](https://github.com/DaojiePENG)

**🔄 Last Updated**: March 2026

---

**Maintained with ❤️ by Daojie PENG | HKUST (Guangzhou) - Robotics and Autonomous Systems**

</div>
