<div align="center">

# Longjie Li

AI Algorithm & Application Developer  
Agentic RAG / Graph RAG / Knowledge Graph / NLP / Time Series Forecasting

[![Email](https://img.shields.io/badge/Email-longjieli0922%40gmail.com-0A66C2?style=flat-square)](mailto:longjieli0922@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-li--longjie-181717?style=flat-square&logo=github)](https://github.com/li-longjie)
[![Demo](https://img.shields.io/badge/Demo-AI_Watch_Dog-FF6699?style=flat-square&logo=bilibili)](https://www.bilibili.com/video/BV187EE6JEy5/)

</div>

## About

I focus on building AI systems that connect models, retrieval, tools and real-world workflows. My recent work is centered on Agent applications, RAG / Graph RAG, knowledge graph construction, NLP information extraction, model service integration and AI infrastructure.

Currently, I am working on intelligent analysis and large-model application systems, including NLP extraction, knowledge graph construction, RAG question answering, Agent tool calling and model/retrieval service deployment.

## Current Focus

- Agent systems: task planning, intent routing, tool calling, multi-step reasoning, fallback handling, streaming responses, short-term and long-term memory.
- RAG and Graph RAG: hybrid retrieval, metadata filtering, reranking, evidence-chain generation, entity-event graph reasoning.
- Knowledge graph and NLP: entity extraction, relation extraction, event extraction, triple extraction, event-chain construction and structured generation.
- AI application infrastructure: model serving, API orchestration, vector databases, experiment tracking and deployment workflows.
- Time series forecasting: hydrological forecasting models, covariate modeling, multi-step prediction and analysis-agent integration.

## Featured Projects

### AI Watch Dog: Multimodal Activity Log Agentic RAG System

[Repository](https://github.com/li-longjie/AI_Watch_Dog) | [Bilibili Demo](https://www.bilibili.com/video/BV187EE6JEy5/)

Built a multimodal Agent assistant for personal activity logs. The system collects video scenes, desktop activity, screen OCR, window titles, browser URLs, application usage and voice input, then supports natural-language search, activity summarization, tool calling and voice Q&A.

Key points:

- Built a Hybrid RAG retrieval pipeline over multimodal activity logs, combining sparse keyword matching, dense embeddings, time/application/URL/event metadata filters and reranking.
- Designed a multi-source indexing pipeline for video analysis results, OCR text, window titles, URLs, mouse events and application usage records.
- Implemented lightweight Agent orchestration with intent recognition, retrieval routing, tool selection, tool execution, answer generation and fallback handling.
- Integrated MCP-style tools for web search, browser automation, file-system access and time queries; connected Faster-Whisper and TTS for voice interaction.
- Awarded Northeast First Prize and National Third Prize in the China Collegiate Computing Contest Network Technology Challenge.

### Multi-source Event Knowledge Graph and Behavior Reasoning System

Built a Graph RAG-style reasoning service for complex event analysis. The system connects text retrieval, graph query and spatiotemporal computation to support evidence-driven behavior reasoning.

Key points:

- Constructed a knowledge graph from structured data, news text, historical events and object relationships.
- Built an NLP extraction pipeline that converts entities, relations and events into triples and writes them into Neo4j.
- Combined Elasticsearch retrieval, Neo4j path query and spatiotemporal feature calculation for hybrid evidence recall.
- Extracted trajectory distance, activity range, speed/direction change and continuous time-window features to support rule-based reasoning and explainable outputs.

### Event Chain Construction and Target Movement Analysis System

Built an intelligent analysis service for news and event data, covering event extraction, incremental event-chain merging, target movement tracking, event prediction and report generation.

Key points:

- Designed an incremental event-chain merging pipeline with Qdrant, Qwen Embedding, TopK retrieval, threshold filtering and time-window constraints.
- Built a pending-event pool for unmatched events and used vector clustering plus time-span splitting to form new event chains.
- Extracted event names, time, location, entities, risk levels and target movement timelines from text.
- Generated structured analysis reports with streaming output for long-running analysis tasks.

### Hydrological Time Series Forecasting and Agent Analysis System

Designed a forecasting model and an Agent-oriented analysis workflow for river and lake water-level forecasting, risk warning and report generation.

Key points:

- Implemented a water-level forecasting model that combines historical targets, historical covariates and known future covariates for multi-step prediction.
- Modeled exogenous variables as controlled residual calibration over a target-centered baseline to reduce overfitting from noisy or redundant covariates.
- Designed a natural-language hydrological analysis Agent that routes user questions to forecasting, history query, covariate retrieval, risk-threshold judgment, chart generation and report tools.
- Built the training and evaluation framework with multiple losses, early stopping, gradient clipping, ablation studies and baseline comparison; completed model implementation, dataset construction and manuscript preparation within about two months.

## Tech Stack

**Languages and Engineering**

Python, SQL, C, Linux, Git, Docker, Docker Compose, FastAPI, Flask, RESTful API, OpenAPI

**LLM Applications**

LangChain, LangGraph, RAG, Graph RAG, MCP, Skills, Agent orchestration, tool calling, long-term memory, short-term memory

**Retrieval and Knowledge Graph**

Qdrant, ChromaDB, Elasticsearch, Neo4j, PostGIS, BM25, embedding retrieval, metadata filtering, rerank, evidence-chain construction

**NLP and Model Training**

PyTorch, Hugging Face, BERT, Qwen, LLaMA-Factory, LoRA / PEFT, entity extraction, relation extraction, event extraction, triple extraction

**AI Infrastructure**

vLLM, SGLang, New API, WandB, MLflow, DeepSpeed basics, Kubernetes basics

## Education and Experience

- M.Eng. in Information and Communication Engineering, Liaoning Technical University, 2024 - 2027.
- B.Eng. in Software Engineering, Jilin Normal University, 2019 - 2023.
- Algorithm Engineer / Research Intern, Institute of Automation, Chinese Academy of Sciences, 2025 - present.

## Awards and Publications

- China Collegiate Computing Contest Network Technology Challenge: Northeast First Prize, National Third Prize.
- Two Agent-related software copyrights.
- One Agent-related EI conference paper and one SCI Q1 manuscript under review.

## What I Like Building

I enjoy turning model capabilities into usable systems: retrieval pipelines that can be inspected, Agent workflows that can recover from failure, knowledge graphs that make reasoning traceable, and model services that can actually be called by users through natural language.

