
# 🚀 CySecBench: Generative AI-based CyberSecurity-focused Prompt Dataset for Benchmarking Large Language Models 🛡️

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  

**The Cybersecurity domain-specific dataset for benchmarking Large Language Models.**

---

## 🌟 Overview

The **CySecBench** paper offers:
- 🎯 **A cutting-edge dataset** of 12662 prompts tailored to cybersecurity challenges.
- 🧠 **Novel jailbreaking methods** leveraging prompt obfuscation and refinement.
- 📊 **Comprehensive performance evaluation** of LLMs like ChatGPT, Claude, and Gemini.  

**Why CySecBench?**

Existing datasets are too broad and often lack focus on cybersecurity. CySecBench fills this gap by providing **domain-specific prompts** organized into 10 categories, enabling a precise evaluation of LLM security mechanisms.

---

## ✨ Features
### 🗂️ Dataset
- 📁 **10 Categories of Prompts**:
  - 🌩️ Cloud Attacks
  - ⚙️ Control System Attacks
  - 🔒 Cryptographic Attacks
  - 🕵️ Evasion Techniques
  - 💻 Hardware Attacks
  - 🔐 Intrusion Techniques
  - 📡 IoT Attacks
  - 🦠 Malware Attacks
  - 🌐 Network Attacks
  - 🌍 Web Application Attacks
 
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
│       ├── cysecbench-2000.csv
│       ├── cysecbench-500.csv
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
- 📈 **Average Rating (AR)**: Degree of harmfulness in LLM responses.
  
### ⚡ Jailbreaking Performance
| **LLM**       | **Success Rate (SR)** | **Average Rating (AR)** |
| ------------- | --------------------- | ----------------------- |
| 🤖 Claude     | 17.4%                 | 2.00                   |
| 🤖 ChatGPT    | 65.4%                 | 4.06                   |
| 🤖 Gemini     | 88.4%                 | 4.77                   |

---

## 🔒 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---
