<h1 align="center">Devansh Gaur</h1>
<p align="center">Building AI systems — from trading agents to robotics to AI harness </p>

<p align="center">
  <a href="https://www.linkedin.com/in/devansh-gaur-248127259/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:Devanshshailendragaur@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://instagram.com/devansh.mhk"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" /></a>
</p>

---

### About

CS student at VIT Bhopal, active in the Robotics Club. I build backend and ML systems end-to-end — from architecture to deployment — with a focus on AI agents, trading systems, and robotics. Currently spending most of my time on AI systems engineering.

---

### What I'm building

**🔊 EchoFlow** — Backend for an audio-only short-form content platform (audio "reels"). Multi-stage recommendation pipeline: content-based retrieval → LightGCN graph embeddings → sequential ranking, with Whisper transcription and hybrid semantic + acoustic vector search.
`Django` `Celery` `PostgreSQL + pgvector` `Redis` `Whisper`
[→ repo](https://github.com/devansh1012007/EchoFlow)

**📈 BTC Scalping Trading Agent** — A hierarchical trading system for 30s–1m timeframes: market data → feature engine → dynamic support/resistance detection → regime detection (HMM + LightGBM) → an expert layer (trend / mean-reversion / breakout) → router → risk & execution, with full monitoring and a model registry. Runs end-to-end on a 12GB-RAM laptop, no GPU.
`Python` `CCXT` `LightGBM` `hmmlearn` `pandas`
[→ repo](https://github.com/devansh1012007/Btc_trading_agents)

**🦾 IRobots — Language-Controlled Robotic Arm** — Hackathon project: a robotic arm driven by natural language instead of fixed motion scripts. A vision model reads the scene, an LLM makes tool calls to select objects and target positions, coordinates go through inverse kinematics, and a simulator validates the path before any real movement — built to generalize better and need less data than a fine-tuned vision-action-language model.
`LLM tool-calling` `YOLO` `Inverse Kinematics`
[→ repo](https://github.com/devansh1012007/IRobots-Devansh_Gaur)

---

### Tech stack

- **Languages:** Python · C++ · JavaScript
- **Backend:** Django · Django REST Framework · FastAPI · Celery
- **Data / ML:** PyTorch · TensorFlow · LightGBM · pandas
- **AI Orchestration:** LangChain · LangGraph · LlamaIndex   
- **Infra / DB:** PostgreSQL · MongoDB · Redis · Docker
- **Robotics:** ROS · Arduino
- **Tools:** Git · GitHub · Postman

---

<p align="center"><i>Looking to collaborate on open source, hackathons, and early-stage startups.</i></p>
