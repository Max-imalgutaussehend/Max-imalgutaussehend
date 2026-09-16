# Max Rommel

21 year old Software Engineering student, B.Sc. Business Information Systems @ DHBW Mannheim & SAP SE.<br>

STAR (Student Training and Rotation) @ SAP, rotations through six departments, most recently Global Private Markets in New York.<br>

Passionate about mathematics, quantitative finance, and data science.

<hr>

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

<hr>

# Projects

## Earnings Call Alpha
Falsifiable reproduction of arXiv:2505.16090 — does segment-level earnings-call sentiment predict abnormal returns better than whole-transcript sentiment?

FinBERT sentiment scoring per Q&A segment · event-study abnormal returns vs. Fama-French 3/5-factor + momentum · nested regression for incremental R² · Probabilistic Sharpe Ratio (Bailey & López de Prado) · reports an honest **null result at n=16** instead of a p-hacked positive

Python · PyTorch/transformers · statsmodels · Docker

🔗 [Repository](https://github.com/Max-imalgutaussehend/earnings-call-alpha)

---

## Regime Lens
Can a time-series foundation model's internal representations detect market regimes without being trained to?

Extracts hidden-state embeddings from Google's TimesFM (and Chronos, for validation) · UMAP + k-Means clustering vs. classical baselines — Gaussian HMM, Markov-switching, PELT changepoint detection · evaluated on crisis-window overlap (2008, 2020, 2022, 2023), cluster quality, and walk-forward backtest with transaction costs

Python · PyTorch · hmmlearn · statsmodels · ruptures · Docker

🔗 [Repository](https://github.com/Max-imalgutaussehend/regime-lens)

---

## life-server
Personal AI infrastructure on a single VPS, built to be extended for years rather than rebuilt — n8n, autonomous agents, MCP servers, Postgres, Redis, all in Docker, all reproducible from the repo.

Zero inbound ports besides rate-limited SSH — web traffic via an outbound Cloudflare Tunnel · agents that execute model-chosen code run on an isolated network with no route to the data layer, verified by 20/20 sandbox-escape assertions · secrets encrypted at rest in Git (sops/AES-256-GCM) · config-as-code: every service declared once, Caddy routes/tunnel ingress/docs generated from it

Docker Compose · network-segmented services · Ansible · autonomous LLM agents · Cloudflare Tunnel

🔗 [Repository](https://github.com/Max-imalgutaussehend/life-server)

<hr>

## Beyond the terminal

10+ years of competitive wrestling, training across several martial arts, and running — Pfälzerwald Marathon 2025.

<hr>

## Contribution Graph

![Snake animation](https://raw.githubusercontent.com/Max-imalgutaussehend/Max-imalgutaussehend/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)
![Snake animation](https://raw.githubusercontent.com/Max-imalgutaussehend/Max-imalgutaussehend/output/github-contribution-grid-snake.svg#gh-light-mode-only)

<hr>

📍 Mannheim, Germany · 🌐 [maxrommel.de](https://maxrommel.de) · 💼 [LinkedIn](https://linkedin.com/in/maxrommel)
