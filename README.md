# Hack <CX> Hackathon 2025 - Banking Customer Support Multi-Agent System

[![Hack <CX> Hackathon](https://img.shields.io/badge/Hack%3CCX%3EHackathon-2025-blue)](https://www.hacktogether.org/)

> This repository hosts the official implementation of Banking Customer Support Multi-Agent System.

## ✨ Features
- **User-Centered Banking Assistant**: Combines user behavior, banking info, and past interactions for personalized support.

- **Multi-Agent Architecture**:
   - Behaviour Analysis Agent for extracting and analyzing customer's behaviours, automatically supporting visualization for customer's behaviour analysis. 

   - Recommendation Agent for personalized banking offers based on customer's analysis results and bank promotional policies.

   - Conversation Agent for automating transactions and answering user's questions with memory (RAG-based).

- **Cooperative Multi-Agent System**:  Agents cooperate with each other for customer experience's enhancement. The Behavior Analysis Agent supplies insights that improve the Recommendation and Conversation Agents, which in turn update the user’s preferences and interests—forming a continuous, supportive feedback loop.

## 🚀 Pipeline Overview

<img width="1515" alt="Untitled (18)" src="https://github.com/user-attachments/assets/a3452e74-32ba-45dc-8a4a-166592f47423" />

## ⚙️ Installation

1. **Clone the repo**:
   ```bash
   git clone https://github.com/meanthai/HACK-CX-Hackathon-banking-agent.git
   ```

2. **Setup environment**:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. **Qdrant Installation**:
   - Follow [Qdrant installation guide](https://qdrant.tech/documentation/quickstart/)

## 🎯 Usage
Run the following command to start my Banking Agent system:
```bash
python app.py
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.


