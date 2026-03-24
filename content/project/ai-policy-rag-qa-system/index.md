---
title: AI Policy RAG QA System
date: 2026-03-19
summary: Retrieval-augmented question answering system for policy documents with semantic retrieval, chunking strategy, and model-comparison experiments.
featured: true
show_date: false
reading_time: false
links:
  - name: GitHub
    icon: brands/github
    url: https://github.com/Aravinda214/ai-policy-rag-qa-system
tags:
  - AI / ML
  - RAG
  - NLP
  - Information Retrieval
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---

RAG system for semantic question answering over handbook-style policy documents, designed to make long documents easier to search, retrieve, and answer against.

<!--more-->

## Highlights

- Built document chunking, embedding, retrieval, and grounded QA end to end.
- Compared chunking strategies, similarity thresholds, and top-k retrieval settings.
- Evaluated multiple models to understand quality and cost tradeoffs.
- Focused on grounded answers rather than open-ended generation.

## Tech Stack

Python, FAISS, sentence-transformers, PyMuPDF, LlamaIndex, and OpenAI API.

## Why It Matters

This project shows the core design tradeoffs behind production RAG systems, especially around retrieval quality, chunking, and answer grounding.
