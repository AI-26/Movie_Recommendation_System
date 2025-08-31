# 🎬 Movie Recommendation System

A production-ready, modular movie recommendation system. It supports **content-based**, **collaborative filtering**, and **hybrid** recommenders with offline training, evaluation, and a simple REST API for online serving.

> ✅ The movie dataset is already included in this repo.

---

## ✨ Features

- Content-based recommendations using plots, genres, cast/crew.
- User-based & item-based collaborative filtering (kNN) and matrix factorization (ALS/SVD).
- Hybrid ranker with learn-to-rank option.
- Fast REST API (`/recommend`, `/similar`, `/search`).
- Offline evaluation (RMSE/MAE for ratings; MAP@K/NDCG@K for ranking).
- Reproducible training via config files and deterministic seeds.
- Dockerized deployment + CLI utilities + notebooks.

---

## 🗂️ Repository Structure
