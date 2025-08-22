📊 Finance Conversational AI Chatbot

An agent-based conversational AI built using LangGraph concepts and the Perplexity LLM API, designed to provide personalized financial insights with long-term memory.
The chatbot integrates real-time market data from Yahoo Finance (yfinance) and forex/technical indicators from Alpha Vantage.

🚀 Features

✅ Phase 1 – Simple Chatbot

Basic conversational finance assistant.

Context-aware responses powered by Perplexity API.

Long-term memory across sessions.

✅ Phase 2 – Finance Agent

Adds financial tools for real-time queries.

Fetches stock prices using yfinance.

Retrieves forex exchange rates via Alpha Vantage API.

Context-aware, with history of user queries.

✅ Phase 3 – Advanced Conversational Agent (optional)

Long-term personalized insights (e.g., stock tracking, proactive suggestions).

Technical indicators and ETF/crypto support.

Designed to be extended with LangGraph memory nodes and event-driven follow-ups.

🛠️ Tech Stack

LLM: Perplexity API
 via langchain_perplexity

Agent Framework: LangGraph concepts for memory & tool orchestration

Finance APIs:

Yahoo Finance
 (yfinance) – stock/ETF/crypto data

Alpha Vantage
 – forex & technical indicators

Programming: Python 3.x, Jupyter Notebook
