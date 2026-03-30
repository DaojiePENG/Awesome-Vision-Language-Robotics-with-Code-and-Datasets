# Awesome Vision-Language-Action & Navigation 🤖🔍

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A comprehensive collection of Vision-Language-Action (VLA) models and Vision-Language-Navigation (VLN) research works. This repository provides curated access to papers, open-source implementations, benchmark results, and baseline comparisons to accelerate research in embodied AI.

**Maintained by**: [HKUST (Guangzhou) - Robotics and Autonomous Systems Thrust]

## 🌟 What's Inside

- 📚 **Curated Papers**: High-impact VLA and VLN research with complete details
- 💻 **Open-Source Code**: Direct links to official implementations
- 🎯 **Benchmark Results**: Performance metrics and baseline comparisons
- 🔬 **Key Innovations**: Highlights of novel contributions
- 📊 **Datasets**: Overview of common benchmarks and evaluation protocols

## 📋 Table of Contents

- [Vision-Language-Action (VLA)](#-vision-language-action-vla)
  - [2025](#2025)
  - [2024](#2024)
  - [2023](#2023)
  - [2022 and Earlier](#2022-and-earlier)
- [Vision-Language-Navigation (VLN)](#-vision-language-navigation-vln)
  - [2025](#2025-1)
  - [2024](#2024-1)
  - [2023](#2023-1)
  - [2022 and Earlier](#2022-and-earlier-1)
- [Datasets & Benchmarks](#-datasets--benchmarks)
- [Related Resources](#-related-resources)
- [Contributing](#-contributing)
- [Citation](#-citation)

---

## 🎯 Vision-Language-Action (VLA)

Vision-Language-Action models bridge natural language understanding with robotic control, enabling robots to follow high-level instructions and perform manipulation tasks.

### 2025

---

### 2024

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
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | CALVIN DDC | 34.9% | RT-2-X: 13.0%, Octo: 28.8% |
  | Language-Table | 83.0% | RT-2: 70.0%, Octo: 78.0% |

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
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Bridge V2 (10 demos) | 52.0% | RT-1: 38.0%, Scratch: 12.0% |
  | Language-Table | 78.0% | RT-2: 70.0%, Scratch: 45.0% |

  </details>

---

#### GRID: Goal-Conditioned Reinforcement Learning with Imagined Data

- 📄 **Paper**: [arXiv:2404.12453](https://arxiv.org/abs/2404.12453)
- 👥 **Authors**: Ziyuan Liu, et al.
- 🏛️ **Venue**: ICML 2024
- 💻 **Code**: [GitHub](https://github.com/LZY-HKUST/GRID)
- 📝 **Description**: Combines vision-language models with goal-conditioned RL using synthetic imagined demonstrations for data-efficient policy learning.
- ✨ **Key Innovations**:
  - Leverages VLMs to generate synthetic goal images
  - Reduces real robot data requirements
  - Effective for long-horizon manipulation tasks

---

### 2023

#### RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control

- 📄 **Paper**: [arXiv:2307.15818](https://arxiv.org/abs/2307.15818) | [Project Page](https://robotics-transformer2.github.io/)
- 👥 **Authors**: Anthony Brohan, Noah Brown, et al.
- 🏛️ **Venue**: CoRL 2023
- 💻 **Code**: [Google DeepMind](https://github.com/google-deepmind/rt-2) (Limited Release)
- 📝 **Description**: Fine-tunes vision-language models (PaLM-E, PaLI) on robot data to transfer web-scale knowledge to robotic control, improving generalization and emergent capabilities.
- ✨ **Key Innovations**:
  - Co-fine-tuning on vision-language and robot action data
  - Leverages internet-scale pretraining for robotics
  - Emergent abilities: reasoning, symbol understanding
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Semantic Instructions | 62.0% | RT-1: 32.0%, VIMA: 48.0% |
  | Unseen Objects | 79.0% | RT-1: 57.0% |

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
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | Language-Table | 89.0% | SayCan: 67.0%, BC-Z: 74.0% |
  | Mobile Manipulation | 74.0% | SayCan: 46.0% |

  </details>

---

#### RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation

- 📄 **Paper**: [arXiv:2306.11706](https://arxiv.org/abs/2306.11706)
- 👥 **Authors**: Konstantinos Bousmalis, et al.
- 🏛️ **Venue**: arXiv 2023
- 💻 **Code**: Not publicly available
- 📝 **Description**: A self-improving generalist agent that learns from diverse robot datasets and autonomously generates new training data through self-supervised learning.
- ✨ **Key Innovations**:
  - Self-improvement via autonomous data collection
  - Cross-embodiment generalization
  - Efficient adaptation to new tasks and robots

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
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | VIMA-Bench (Level 4) | 65.4% | CLIP-Gato: 21.3%, LSTM: 43.2% |

  </details>

---

### 2022 and Earlier

#### RT-1: Robotics Transformer for Real-World Control at Scale

- 📄 **Paper**: [arXiv:2212.06817](https://arxiv.org/abs/2212.06817) | [Project Page](https://robotics-transformer1.github.io/)
- 👥 **Authors**: Anthony Brohan, et al.
- 🏛️ **Venue**: RSS 2023
- 💻 **Code**: [GitHub](https://github.com/google-research/robotics_transformer)
- 📝 **Description**: A transformer-based model trained on a large-scale robotic manipulation dataset, demonstrating strong generalization and efficient learning from demonstrations.
- ✨ **Key Innovations**:
  - Token-based action representation
  - Efficient training on large-scale robot data
  - Real-world deployment at scale
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Success Rate | Main Baselines |
  |-----------|-------------|----------------|
  | 700 Tasks | 97.0% | BC-Z: 87.0%, Gato: 79.0% |
  | Unseen Tasks | 76.0% | BC-Z: 54.0% |

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
  - Multi-task multi-domain learning

---

## 🧭 Vision-Language-Navigation (VLN)

Vision-Language-Navigation focuses on enabling agents to navigate environments following natural language instructions, combining visual perception with language grounding.

### 2025

---

### 2024

#### NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models

- 📄 **Paper**: [arXiv:2305.16986](https://arxiv.org/abs/2305.16986)
- 👥 **Authors**: Gengze Zhou, et al.
- 🏛️ **Venue**: AAAI 2024
- 💻 **Code**: [GitHub](https://github.com/GengzeZhou/NavGPT)
- 📝 **Description**: Integrates GPT-based reasoning for explicit spatial and semantic reasoning in VLN tasks, improving navigation decisions.
- ✨ **Key Innovations**:
  - LLM-based explicit reasoning module
  - Step-by-step decision explanation
  - Enhanced interpretability
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 53.0% | HAMT: 48.0%, DUET: 50.0% |

  </details>

---

#### ETPNav: Evolving Topological Planning for Vision-Language Navigation

- 📄 **Paper**: [arXiv:2304.03047](https://arxiv.org/abs/2304.03047)
- 👥 **Authors**: Dong An, et al.
- 🏛️ **Venue**: TPAMI 2024
- 💻 **Code**: [GitHub](https://github.com/MarSaKi/ETPNav) | ![GitHub stars](https://img.shields.io/github/stars/MarSaKi/ETPNav?style=social)
- 📝 **Description**: Constructs and evolves a topological map during navigation to enable long-horizon reasoning and backtracking.
- ✨ **Key Innovations**:
  - Dynamic topological map construction
  - Evolving planning strategy
  - Improved long-horizon navigation
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 59.0% | DUET: 50.0%, HAMT: 48.0% |
  | REVERIE Val Unseen | 38.0% | DUET: 33.0%, HAMT: 30.0% |

  </details>

---

### 2023

#### DUET: Cross-Modal Semantic Grounding for Vision-and-Language Navigation

- 📄 **Paper**: [arXiv:2301.00158](https://arxiv.org/abs/2301.00158)
- 👥 **Authors**: Chen Gao, et al.
- 🏛️ **Venue**: AAAI 2023
- 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-DUET) | ![GitHub stars](https://img.shields.io/github/stars/cshizhe/VLN-DUET?style=social)
- 📝 **Description**: Employs dual-scale graph transformer for fine-grained cross-modal alignment between language and visual observations.
- ✨ **Key Innovations**:
  - Dual-scale graph representation
  - Fine-grained semantic grounding
  - Object-level cross-modal attention
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 50.0% | HAMT: 48.0%, EnvDrop: 44.0% |
  | REVERIE Val Unseen | 33.0% | HAMT: 30.0%, VLN-BERT: 28.0% |

  </details>

---

#### HAMT: Hierarchical Attention Map Transformer for Vision-Language Navigation

- 📄 **Paper**: [arXiv:2210.05448](https://arxiv.org/abs/2210.05448)
- 👥 **Authors**: Chen Gao, et al.
- 🏛️ **Venue**: ICCV 2023
- 💻 **Code**: [GitHub](https://github.com/cshizhe/VLN-HAMT)
- 📝 **Description**: Uses hierarchical attention to model multi-scale spatial relationships in visual environments for improved navigation.
- ✨ **Key Innovations**:
  - Hierarchical spatial attention mechanism
  - Multi-scale visual feature aggregation
  - Effective long-range reasoning
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 48.0% | VLN-BERT: 43.0%, EnvDrop: 44.0% |

  </details>

---

### 2022 and Earlier

#### REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments

- 📄 **Paper**: [CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.html)
- 👥 **Authors**: Yuankai Qi, et al.
- 🏛️ **Venue**: CVPR 2020
- 💻 **Code**: [GitHub](https://github.com/YuankaiQi/REVERIE) | ![GitHub stars](https://img.shields.io/github/stars/YuankaiQi/REVERIE?style=social)
- 📝 **Description**: Introduces a new task combining VLN with remote object grounding, requiring agents to navigate and identify target objects.
- ✨ **Key Innovations**:
  - Combined navigation and grounding task
  - New benchmark dataset
  - Multi-task learning framework
- 🎯 **Performance**: Establishes baseline benchmarks for the REVERIE task

---

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
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | SPL | Main Baselines |
  |-----------|-----|----------------|
  | R2R Val Unseen | 43.0% | EnvDrop: 44.0%, AuxRN: 39.0% |

  </details>

---

## 📊 Datasets & Benchmarks

### VLA Benchmarks

| Dataset | Description | Tasks | Download |
|---------|-------------|-------|----------|
| **CALVIN** | Long-horizon manipulation with language annotations | 34 tasks in 4 environments | [Link](https://github.com/mees/calvin) |
| **Language-Table** | Language-conditioned pushing and rearrangement | Block manipulation | [Link](https://github.com/google-research/language-table) |
| **RLBench** | Large-scale robot learning benchmark | 100+ diverse tasks | [Link](https://github.com/stepjam/RLBench) |
| **Open X-Embodiment** | Multi-robot dataset collection | 970k+ trajectories, 22 robots | [Link](https://robotics-transformer-x.github.io/) |
| **Bridge V2** | Real-world manipulation dataset | Kitchen tasks | [Link](https://rail-berkeley.github.io/bridgedata/) |
| **VIMA-Bench** | Multimodal prompt-based manipulation | Simulation benchmark | [Link](https://vimalabs.github.io/) |

### VLN Benchmarks

| Dataset | Description | Tasks | Download |
|---------|-------------|-------|----------|
| **R2R** | Room-to-Room navigation | Navigation from language | [Link](https://github.com/peteanderson80/Matterport3DSimulator) |
| **REVERIE** | Remote object grounding | Navigation + object grounding | [Link](https://github.com/YuankaiQi/REVERIE) |
| **RxR** | Multilingual VLN | 3 languages, diverse instructions | [Link](https://github.com/google-research-datasets/RxR) |
| **CVDN** | Continuous VLN | Dense annotations | [Link](https://github.com/mmurray/cvdn) |
| **R4R** | Extended R2R paths | Longer navigation episodes | [Link](https://github.com/ronghanghu/vln_ce) |
| **SOON** | Object-based navigation | Object-centric instructions | [Link](https://github.com/ZhuFengdaaa/SOON) |

---

## 🔗 Related Resources

### Surveys & Tutorials

- [A Survey on Embodied AI](https://arxiv.org/abs/2210.06849) - Comprehensive overview of embodied AI research
- [Vision-Language Navigation: A Survey](https://arxiv.org/abs/2203.12667) - VLN methods and benchmarks

### Related Awesome Lists

- [Awesome Embodied Vision](https://github.com/ChanganVR/awesome-embodied-vision)
- [Awesome Robotics](https://github.com/kiloreux/awesome-robotics)
- [Awesome Vision-and-Language](https://github.com/sangminwoo/awesome-vision-and-language)

### Tools & Frameworks

- [AI2-THOR](https://ai2thor.allenai.org/) - Interactive 3D environments
- [Habitat](https://aihabitat.org/) - Simulation platform for embodied AI
- [MuJoCo](https://mujoco.org/) - Physics engine for robotics
- [PyRobot](https://pyrobot.org/) - Python robotics framework

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Suggesting new papers
- Updating existing entries
- Reporting issues

**Contribution Criteria:**
- Open-source code available
- Published or on arXiv
- Significant impact (citations, reproducibility, novelty)

---

## 📖 Citation

If you find this repository helpful, please consider citing:

```bibtex
@misc{awesome-vla-vln-2025,
  title={Awesome Vision-Language-Action \& Navigation},
  author={HKUST(GZ) Robotics and Autonomous Systems},
  year={2025},
  howpublished={\url{https://github.com/[your-username]/[repo-name]}}
}
```

---

## 📝 License

This repository is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Thanks to all researchers who open-source their work
- Inspired by the [Awesome](https://awesome.re) list movement
- Maintained with ❤️ by the robotics research community

---

**Last Updated**: March 2025
**Maintainer**: HKUST (Guangzhou) - Robotics and Autonomous Systems Thrust

