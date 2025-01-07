
# 🚀 CySecBench: Generative AI-based CyberSecurity-focused Prompt Dataset for Benchmarking Large Language Models 🛡️

<a href="https://arxiv.org/abs/2501.01335">
	<img src="https://img.shields.io/static/v1?label=Paper&message=Arxiv:CySecBench&color=red&logo=arxiv" alt="Arxiv:CySecBench">
</a>

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  

**The largest and most comprehensive Generative AI-based CyberSecurity-focused Dataset for Benchmarking Large Language Models**
---

## 🌟 Overview

The **CySecBench** paper offers:
- 🎯 **A cutting-edge dataset** of 12662 prompts tailored to cybersecurity challenges.
- 🧠 **Novel jailbreaking methods** leveraging prompt obfuscation and refinement.
- 📊 **Comprehensive performance evaluation** of LLMs like ChatGPT, Claude, and Gemini.

**Why CySecBench?**

Existing datasets are too broad and often lack focus on cybersecurity. CySecBench fills this gap by providing **domain-specific prompts** organized into 10 categories, enabling a precise evaluation of LLM security mechanisms.

### 📄 Access the Paper

You can download the full research paper here: [CySecBench (PDF)](CySecBench_paper.pdf)

---

## ✨ Features
### 🗂️ Dataset
- 📁 **10 Categories of Prompts**:
  - 🌩️ [Cloud Attacks](Dataset/Category%20sets/cysecbench-cloud-attacks.csv)
  - ⚙️ [Control System Attacks](Dataset/Category%20sets/cysecbench-control-system-attacks.csv)
  - 🔒 [Cryptographic Attacks](Dataset/Category%20sets/cysecbench-cryptographic-attacks.csv)
  - 🕵️ [Evasion Techniques](Dataset/Category%20sets/cysecbench-evasion-techniques.csv)
  - 💻 [Hardware Attacks](Dataset/Category%20sets/cysecbench-hardware-attacks.csv)
  - 🔐 [Intrusion Techniques](Dataset/Category%20sets/cysecbench-intrusion-techniques.csv)
  - 📡 [IoT Attacks](Dataset/Category%20sets/cysecbench-iot-attacks.csv)
  - 🦠 [Malware Attacks](Dataset/Category%20sets/cysecbench-malware-attacks.csv)
  - 🌐 [Network Attacks](Dataset/Category%20sets/cysecbench-network-attacks.csv)
  - 🌍 [Web Application Attacks](Dataset/Category%20sets/cysecbench-web-application-attacks.csv)
 
---

## 🗂️ Repository Structure

```
/
├── Code/
│   ├── dataset_generation.py
│   ├── keywords.txt
├── Dataset/
│   ├── Category sets/
│   │   ├── cysecbench-cloud-attacks.csv
│   │   ├── cysecbench-control-system-attacks.csv
│   │   ├── cysecbench-cryptographic-attacks.csv
│   │   ├── cysecbench-evasion-techniques.csv
│   │   ├── cysecbench-hardware-attacks.csv
│   │   ├── cysecbench-intrusion-techniques.csv
│   │   ├── cysecbench-iot-attacks.csv
│   │   ├── cysecbench-malware-attacks.csv
│   │   ├── cysecbench-network-attacks.csv
│   │   ├── cysecbench-web-application-attacks.csv
│   ├── Full dataset/
│   │   ├── cysecbench.csv
│   ├── Sample sets/
│       ├── cysecbench-500.csv
│       ├── cysecbench-2000.csv
│       ├── cysecbench-6000.csv
```

---

## 🚀 Getting Started
### ⚙️ Prerequisites

- 🐍 **Python 3.8+**
- 📦 Required libraries: `openai` (**only for dataset generation**)

---

## 📊 Results using CySecBench

### 🎯 Evaluation Metrics
- ✅ **Success Rate (SR)**: Percentage of prompts bypassing ethical guidelines.
- 📈 **Average Rating (AR)**: Degree of harmfulness in LLM responses (on a scale of 1-5, where 5 is the most harmful).
  
### ⚡ Jailbreaking Performance
| **LLM**       | **Success Rate (SR)** | **Average Rating (AR)** |
| ------------- | --------------------- | ----------------------- |
| 🤖 Claude     | 17.4%                 | 2.00                   |
| 🤖 ChatGPT    | 65.4%                 | 4.06                   |
| 🤖 Gemini     | 88.4%                 | 4.77                   |

---

## 📜 Citation

If you use CySecBench, please cite:

```bibtex
@article{CySecBench2024,
	title        = {{CySecBench: Generative AI-based CyberSecurity-focused Prompt Dataset for Benchmarking Large Language Models}},
	author       = {Johan Wahréus and Ahmed Mohamed Hussain and Panos Papadimitratos},
	year         = {2025},
	journal      = {arXiv preprint arXiv:2501.01335},
	url          = {https://arxiv.org/abs/2501.01335}
}
```

## ⭐ Star This Repository!

If you found **CySecBench** helpful or interesting, please give this repository a **star** ⭐ to show your support!  

---

## 🔒 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
