# InsightForge: AI-Powered Business Intelligence Assistant

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-green.svg)](https://openai.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

> Transforming business data into intelligent decisions with AI-powered analytics, RAG, and natural language processing.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Components](#key-components)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

InsightForge is an AI-powered Business Intelligence Assistant developed as part of the Simplilearn AI Capstone Project. It leverages cutting-edge technologies including Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and FAISS vector databases to transform raw business data into actionable insights.

### Problem Statement

Small and medium-sized enterprises often struggle to extract valuable insights from their data due to:
- Limited resources for expensive BI tools
- Lack of data science expertise
- Time-consuming manual analysis processes
- Difficulty in making data-driven decisions

### Solution

InsightForge addresses these challenges by providing:
- Automated data analysis using AI
- Natural language query interface for non-technical users
- Document-based knowledge retrieval via RAG
- Professional visualization dashboards
- Exportable business intelligence reports

---

## Features

### RAG-Based Document Processing
- Loads and processes business documents (PDFs, research papers)
- Creates semantic embeddings using OpenAI's `text-embedding-ada-002`
- Builds FAISS vector index for fast similarity search
- Enables context-aware question answering

### LLM Integration
- Direct integration with OpenAI GPT-4 Turbo
- Natural language understanding and generation
- Context-aware responses with source citations

### Data Analysis Engine
- Automated data quality assessment
- Statistical analysis and trend identification
- Missing value detection and reporting
- Duplicate record identification

### Visualization Dashboard
- Age distribution analysis (histogram + box plot)
- Gender distribution charts (bar + pie)
- Data completeness visualization
- Demographic comparison charts

### Interactive Query System
- Ask questions in plain English
- Get instant AI-powered answers
- Context-aware responses with data citations

### Report Generation
- Cleaned dataset exports (Excel)
- Data quality reports
- Statistical summaries (multi-sheet workbooks)
- Executive summary documents

---

## Demo

### Example Queries You Can Try

```python
# Query the RAG system about business documents
query_rag_system("What are best practices for AI in business intelligence?")

# Ask questions about your dataset
ask_insightforge("What is the average age of patients?")
ask_insightforge("Which columns have missing data?")


======================================================================
SAMPLE INSIGHTFORGE ANSWERS
======================================================================
Key benefits of implementing AI in business intelligence include:

1. Automated Data Analysis: AI processes vast amounts of data faster 
   than traditional methods, identifying patterns humans might miss.

2. Predictive Insights: Machine learning enables forecasting and 
   predictive analytics for better strategic planning.

3. Real-time Decision Making: AI-powered BI systems provide instant 
   insights for quick market response.

======================================================================
📎 Sources:
   • AI business model innovation.pdf
   • BI approaches.pdf
======================================================================


My Project Technology Core Stack:

Python 3.10+ — Primary programming language
OpenAI GPT-4 Turbo — Large language model for natural language processing
FAISS — Vector database for semantic search
Pandas & NumPy — Data manipulation and analysis
Matplotlib & Seaborn — Data visualization

AI/ML Components:

Retrieval-Augmented Generation (RAG) — Context-aware AI responses
Text Embeddings — text-embedding-ada-002 for semantic search
Vector Similarity Search — FAISS for efficient retrieval
Document Processing
PyPDF — PDF text extraction
OpenAI Embeddings — Document vectorization
