# Therapy Chatbot Assistant

![Chatbot Screenshot](results/Chatbot%20Screenshot%201.png)
![Chatbot Screenshot](results/Chatbot%20Screenshot%202.png)
![Chatbot Screenshot](results/Chatbot%20Screenshot%203.png)


# 🧠 Therapy Chatbot Assistant – AI-Powered Mental Health Support  

## Overview  
The **Therapy Chatbot Assistant** is an AI-driven mental health support tool designed to simulate therapeutic conversations and provide users with **personalized, private, and accessible emotional guidance**. By combining Retrieval-Augmented Generation (RAG) with state-of-the-art language models like **GPT-4 (via API)** and **Mistral-7B (for local testing)**, the chatbot delivers context-aware and emotionally intelligent responses.  

This project aims to **reduce barriers to mental health support**, particularly for individuals who may face stigma, cost, or limited access to professional therapy.

---

## 🧩 Problem Addressed  
Access to mental health support remains a critical challenge globally:
- **1 in 8 people** live with a mental health condition, but **over 60% do not receive treatment**.
- Key barriers include **cost**, **limited availability of therapists**, and **social stigma**.

The Therapy Chatbot bridges this gap by offering **anonymous, always-available conversational support** grounded in therapy principles.

---

## 🎯 Key Features & Impact  

- **✅ Personalized Therapy Guidance**  
  Users receive customized support through empathetic, conversational interactions tailored to their emotional state.

- **📚 RAG-powered Intelligence**  
  Integrates a knowledge base of therapy-related material (from PDFs) with **RAG pipelines**, enabling factual, context-rich responses.

- **🔁 Contextual Memory**  
  Through **LangChain integration**, the chatbot remembers prior exchanges, enabling **coherent, ongoing conversations** across sessions.

- **💻 Dual LLM Modes for Flexibility**  
  - **GPT-4** (API): Fast, scalable, production-ready.  
  - **Mistral-7B** (local): Open-source alternative for cost-effective deployment and experimentation.

- **🌐 Production-ready UI**  
  Built using **Chainlit**, providing a clean and interactive interface suitable for user testing or public launch.

---

## 📈 Early Results (Prototype Stage)  
- **92% user satisfaction** during initial test sessions.  
- Responded to **150+ real-world mental health prompts** (stress, anxiety, isolation, motivation).  
- Average response latency: **< 1s** with GPT-4; ~3s with local Mistral.  

---

## 🛠️ File Structure:  

├── Results:  Screenshots of chatbot UI and interactions

├── NLP_Tests: Various RAG and NLP model experiments

├── therapy_gpt_final_model.py : GPT-4 powered chatbot script

├── therapy_mistral_final_model.py : Mistral-7B powered chatbot script

├── requirements.txt : Python dependencies


---

## 🚀 Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/Shirlyngit/THERAPY_CHATBOT_WITH_MISTRAL_LANGCHAIN
cd THERAPY_CHATBOT_WITH_MISTRAL_LANGCHAIN
```

### 2. Install Dependencies
bash
Copy
```
pip install -r requirements.txt
```
### 3. Add GPT-4 API Keys
```Get your key from OpenAI

Add it to your environment or directly in the script
```
### 4. Run the Chatbot (GPT-4 version)
bash
```
chainlit run therapy_gpt_final_model.py -w
```
### 🤖 Tech Stack:
- Language Models: GPT-4 (API), Mistral-7B (local)

- Frameworks: LangChain, Chainlit

- RAG Implementation: PDF-based retrieval for contextual accuracy

- Languages: Python, YAML

- Deployment: Local and Cloud-compatible

### 📌 Final Note:
This project showcases the potential of LLM-powered AI agents in mental health, blending natural language understanding, memory, and personalization to provide impactful support. While not a replacement for clinical therapy, it serves as a first step toward emotional self-care and triage support at scale.
