# Contributing to Awesome VLA & VLN 🤝

Thank you for your interest in contributing to this repository! We appreciate your help in making this a comprehensive resource for the Vision-Language-Action and Vision-Language-Navigation research community.

## 📋 Table of Contents

- [How to Contribute](#how-to-contribute)
- [Contribution Guidelines](#contribution-guidelines)
- [Paper Entry Format](#paper-entry-format)
- [Quality Standards](#quality-standards)
- [Review Process](#review-process)

---

## 🚀 How to Contribute

### 1. **Suggesting New Papers**

To suggest a new paper, please:

1. **Check for duplicates**: Ensure the paper isn't already listed
2. **Open an issue**: Use the "Suggest Paper" template
3. **Or submit a Pull Request**: Follow the format below

### 2. **Updating Existing Entries**

If you notice errors or missing information:

1. Open an issue describing the problem
2. Or submit a PR with the corrections

### 3. **Other Improvements**

- Fixing typos or broken links
- Improving organization or formatting
- Adding new sections (datasets, tools, etc.)

---

## ✅ Contribution Guidelines

### **Eligibility Criteria**

Papers must meet the following requirements:

- ✅ **Open-source code**: GitHub repository or equivalent publicly available
- ✅ **Published or preprint**: Peer-reviewed venue or arXiv
- ✅ **Relevance**: Directly related to VLA or VLN
- ✅ **Impact**: Demonstrates novelty, strong results, or significant citations
- ✅ **Reproducibility**: Clear documentation and working code

### **What We Accept**

- ✅ Conference papers (CVPR, ICCV, ECCV, NeurIPS, ICML, CoRL, RSS, IROS, ICRA, etc.)
- ✅ Journal papers (TPAMI, IJRR, T-RO, etc.)
- ✅ High-quality arXiv preprints with significant impact

### **What We Generally Don't Accept**

- ❌ Papers without open-source code
- ❌ Duplicate entries
- ❌ Low-quality or poorly documented work
- ❌ Papers tangentially related to VLA/VLN

---

## 📝 Paper Entry Format

When adding a new paper, please follow this exact format:

```markdown
#### [Paper Title]

- 📄 **Paper**: [arXiv:XXXX.XXXXX](arxiv-link) | [Project Page](project-link) | [PDF](pdf-link)
- 👥 **Authors**: First Author, Second Author, et al.
- 🏛️ **Venue**: Conference/Journal Year
- 💻 **Code**: [GitHub](github-link) | ![GitHub stars](https://img.shields.io/github/stars/username/repo?style=social)
- 📝 **Description**: A concise 1-2 sentence summary of the approach and contributions.
- ✨ **Key Innovations**:
  - Innovation point 1
  - Innovation point 2
  - Innovation point 3
- 🎯 **Performance**:
  <details>
  <summary>Main Results</summary>

  | Benchmark | Metric | Score | Main Baselines |
  |-----------|--------|-------|----------------|
  | Dataset 1 | Metric | XX.X% | Baseline1: XX%, Baseline2: XX% |
  | Dataset 2 | Metric | XX.X% | Baseline1: XX%, Baseline2: XX% |

  </details>
```

### **Field Descriptions**

- **Paper**: Include arXiv link (preferred) and/or official publication link. Add project page if available.
- **Authors**: List first 2-3 authors followed by "et al." for papers with many authors.
- **Venue**: Conference/Journal name and year (e.g., "CVPR 2024", "arXiv 2025")
- **Code**: GitHub repository with stars badge. Use format: `![GitHub stars](https://img.shields.io/github/stars/username/repo?style=social)`
- **Description**: Brief summary highlighting the main approach
- **Key Innovations**: 2-4 bullet points of novel contributions
- **Performance**: Table with main benchmark results and baseline comparisons (use collapsible section)

### **Example Entry**

```markdown
#### OpenVLA: An Open-Source Vision-Language-Action Model

- 📄 **Paper**: [arXiv:2406.09246](https://arxiv.org/abs/2406.09246) | [Project Page](https://openvla.github.io/)
- 👥 **Authors**: Moo Jin Kim, Karl Pertsch, et al.
- 🏛️ **Venue**: CoRL 2024
- 💻 **Code**: [GitHub](https://github.com/openvla/openvla) | ![GitHub stars](https://img.shields.io/github/stars/openvla/openvla?style=social)
- 📝 **Description**: A 7B-parameter open-source VLA model trained on 970k robot trajectories from the Open X-Embodiment dataset.
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
```

---

## 🎯 Quality Standards

### **Code Requirements**

- Repository must be accessible and functional
- Include README with setup instructions
- Preferably includes pretrained models or clear training instructions

### **Paper Requirements**

- Clear methodology and contributions
- Experimental validation on established benchmarks
- Comparison with relevant baselines

### **Documentation**

- All links must be valid and accessible
- Information must be accurate and up-to-date
- Follow the exact formatting guidelines

---

## 🔍 Review Process

1. **Submission**: Open an issue or submit a PR
2. **Review**: Maintainers check eligibility and quality
3. **Feedback**: You may be asked to provide additional information
4. **Approval**: If criteria are met, contribution is merged
5. **Acknowledgment**: Your contribution will be acknowledged

**Review Timeline**: We aim to review contributions within 1 week.

---

## 📮 Contact

For questions or discussions:

- Open an issue in this repository
- Contact maintainers: [Your email or contact info]

---

## 🌟 Recognition

All contributors will be acknowledged! Significant contributions may be highlighted in the README.

---

## 📄 Code of Conduct

Please be respectful and constructive in all interactions. We're building a community resource for researchers worldwide.

---

Thank you for helping make this resource better for everyone! 🎉
