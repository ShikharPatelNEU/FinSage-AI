# FinSage-AI 🏦
The Multi-Agent Financial Analyst simplifies investing by turning a stock symbol into a clear executive summary, performance report, and actionable insights. Multiple AI agents work together to deliver fast, accurate, and easy-to-understand financial analysis for smarter decisions.

## Overview
FinSage AI is a Multi-Agent Financial Analyst that simplifies investing by turning a stock symbol into a clear executive summary, performance analysis, and actionable insights. Multiple AI agents work together to deliver fast, accurate, and easy-to-understand financial analysis for smarter investment decisions. By leveraging conversational AI and real-time market data, FinSage can provide personalized stock recommendations and comprehensive reports tailored to individual investors' needs. This significantly improves investment decision-making and streamlines the financial analysis process.

## Problem Statement
● Information Overload: Investors face overwhelming amounts of financial data, making it difficult to extract actionable insights without specialized knowledge.
● Analysis Complexity: Comprehensive stock analysis requires evaluating multiple metrics, technical indicators, and market trends, which is time-consuming and technically challenging for most individuals.
● Real-time Decision Making: Market conditions change rapidly, requiring frequent reassessment of investment positions, which is impractical for casual investors without automated tools.
● Limited Personalization: Traditional financial reports lack personalization, often presenting generic information rather than insights tailored to specific investment goals or risk profiles.

## Technology Stack

1.Streamlit (User Interface)
2.SambaNova LLM (Llama-4-Maverick)
3.CrewAI Framework (Agent Orchestration)
4.YFinance (Stock Data API)
5.Pandas (Data Analysis)
6.Plotly (Data Visualization)
7.Pydantic (Data Validation)
8.Python-dotenv (Environment Management)

## Architecture Workflow
![Workflow](https://github.com/ShikharPatelNEU/FinSage-AI/blob/main/finsage_architecture.png)


Project Structure
📦 FinSage-AI
├─ README.md
├─ Documentation
├─ Images
│  ├─ architecture.jpg
│  └─ ui_screenshots.png
├─ src
│  ├─ financial_analyst.py
│  ├─ requirements.txt
│  └─ tools
│     └─ financial_tools.py
├─ tests
│  └─ test_financial_tools.py
├─ Dockerfile
└─ docker-compose.yml
