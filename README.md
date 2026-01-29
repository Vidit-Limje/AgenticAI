# 🧠 Agentic AI Financial Advisor (LangGraph + Open-Source LLM)

An **agentic AI–based financial advisory system** built using **LangGraph** and **LangChain**, powered by an **open-source large language model (Mistral-7B-Instruct)**.  
The system demonstrates how multiple specialized AI agents can collaborate through a shared state to generate structured investment advice.

> 📌 **Implementation Note**  
> This project is implemented entirely in **a single Jupyter Notebook (`.ipynb`)** and is designed to run seamlessly on **Google Colab**.

---

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Agent Architecture](#-agent-architecture)
- [Technology Stack](#-technology-stack)
- [Notebook Structure](#-notebook-structure)
- [How to Run (Google Colab)](#️-how-to-run-google-colab)
- [Example Input & Output](#-example-input--output)
- [Design Decisions](#-design-decisions)
- [Limitations](#️-limitations)
- [Future Enhancements](#-future-enhancements)
- [Disclaimer](#-disclaimer)

---

## 🔍 Project Overview

Traditional financial advisory systems are often rule-based and static.  
This project showcases an **agentic AI approach**, where multiple intelligent agents reason independently and collaboratively to produce a comprehensive investment advisory report.

Each agent focuses on a distinct responsibility such as market analysis, investment planning, and risk assessment, while sharing information through a centralized state.

---

## ✨ Key Features

- 🧩 Multi-agent architecture using **LangGraph**
- 🔓 Fully **open-source LLM** (no paid APIs required)
- ⚡ **4-bit quantized model** for execution on free Colab GPUs
- 🧠 Shared state for agent collaboration
- 📊 Professionally structured final advisory report
- 📓 Single-notebook implementation for easy evaluation
- 🛡️ Basic error handling and defensive prompting

---

## 🧠 Agent Architecture

The system consists of the following cooperative agents:

1. **Market Analysis Agent**  
   Analyzes current market conditions based on the investor’s risk profile.

2. **Short-Term Investment Agent**  
   Generates short-term strategies focusing on liquidity and capital preservation.

3. **Long-Term Investment Agent**  
   Recommends growth-oriented investment options for long-term wealth creation.

4. **Risk Analysis Agent**  
   Evaluates portfolio risk and diversification alignment.

5. **Final Report Agent**  
   Synthesizes all agent outputs into a structured professional report.
   


---

## 🛠️ Technology Stack

- **Language**: Python  
- **Agent Framework**: LangGraph  
- **LLM Orchestration**: LangChain  
- **Model**: Mistral-7B-Instruct-v0.2  
- **Inference**: Hugging Face Transformers  
- **Optimization**: BitsAndBytes (4-bit quantization)  
- **Environment**: Google Colab  

---

## 📓 Notebook Structure

The Jupyter Notebook is organized into clearly defined sections:

1. Dependency installation  
2. Library imports  
3. LLM loading and optimization  
4. Text generation pipeline setup  
5. Shared agent state definition  
6. Individual agent implementations  
7. LangGraph workflow construction  
8. Execution and final report generation  

Each section is thoroughly commented and documented for clarity and maintainability.

---

## ▶️ How to Run (Google Colab)

1. Open **Google Colab**
2. Upload the `.ipynb` notebook from this repository
3. Set runtime type to **GPU**
4. Run all cells sequentially
5. View the final advisory report in the output cell

> ⚠️ First execution may take a few minutes to download the model.

---

## 📥 Example Input

```python
{
    "risk_profile": "Moderate",
    "investment_horizon": "Short and Long Term"
}


Executive Summary
The investor demonstrates a moderate risk appetite...

Key Market Insights
Market conditions indicate moderate volatility...

Short-Term Recommendations
Focus on liquid and low-risk instruments...

Long-Term Recommendations
Allocate to diversified equity-oriented assets...

Risk & Diversification Notes
Balanced diversification helps mitigate downside risk...

