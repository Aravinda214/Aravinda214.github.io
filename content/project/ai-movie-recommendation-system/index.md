---
title: AI Movie Recommendation System
date: 2026-03-22
summary: Production-grade recommender system with hybrid feedback, temporal evaluation, Flask serving, CI/CD, Docker, and monitoring.
featured: true
show_date: false
reading_time: false
links:
  - name: GitHub
    icon: brands/github
    url: https://github.com/Aravinda214/AI-Movie-Recommendation-System
tags:
  - AI / ML
  - Recommender Systems
  - Software Engineering
  - MLOps
---

Production-grade recommender system for a streaming-style use case, designed around sparse feedback, cold start behavior, leakage-aware evaluation, and serving reliability.

<!--more-->

## Highlights

- Built a hybrid recommendation pipeline using explicit and implicit feedback signals.
- Used a temporal train/validation/test split to evaluate the model without leakage.
- Served recommendations through a Flask API with CI/CD, Docker, testing, and telemetry.
- Added graceful degradation with an ALS fallback model for reliability.

## Tech Stack

Python, scikit-learn, Flask, Kafka, pytest, Docker, and GitHub Actions.

## Why It Matters

This project demonstrates end-to-end ML system design, not just modeling, with attention to evaluation rigor, service reliability, and production-readiness.
