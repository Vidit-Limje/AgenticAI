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
   

