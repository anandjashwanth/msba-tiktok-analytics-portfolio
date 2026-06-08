# AI Investment Evaluation RAG Agent

## Files

- Notebook: `ai_investment_rag_agent.ipynb`
- HTML view: `ai_investment_rag_agent.html`
- This README: `ai_investment_rag_agent_README.md`

## Overview

AI-augmented investment evaluation pipeline that ingests investment case documents, chunks text, builds hybrid retrieval, prompts an LLM, verifies outputs, scores confidence, and packages board-level reports and audit material.

## What the notebook contains

This notebook contains **33 cells**: 17 markdown cells, 16 code cells, and 17 saved outputs. The HTML view was generated from the existing notebook content so reviewers can inspect the work without relying on GitHub's notebook preview.

## Methods and tools shown

- Retrieval-augmented generation
- Hybrid retrieval using dense embeddings and BM25
- Sentence-transformer embeddings and FAISS-style retrieval
- LLM prompting and section generation
- Verification checks and confidence scoring
- Word/PDF-style report packaging and audit logs

## Portfolio relevance

Strongest project for the BytePlus AI Agent role because it directly shows RAG, AI search, prompt engineering, tool-style workflow design, evaluation, and presentable AI outputs.

## Notes from review

The notebook references API-key handling through environment variables/Colab secrets but does not include an exposed key.

## How to view

For GitHub review, open this README first. If the `.ipynb` preview appears blank or slow, download/open `ai_investment_rag_agent.html` locally or serve it through GitHub Pages. The notebook file is retained for technical review and reproducibility.
