### Hi, I'm Fernando Canseco

**M.S. in Artificial Intelligence · B.S. in Computer Science**

I build applied AI systems across **machine learning, deep learning, NLP, computer vision, and LLM-powered agents** — and I'm at my best on hard, open-ended problems where the answer isn't in a textbook yet. I like to dig into the research, find what others have tried, and build my own technique when nothing off-the-shelf fits.

I've taken part in research and development programs sponsored by or partnered with **John Deere**, the **U.S. Space Force**, and **UT Health San Antonio**.

Open to **Data Science / AI / ML Engineering** roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernando-canseco-4817a6216/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:FernCanCode@gmail.com)

---

## Featured Projects

### [Restaurant Voice Ordering Agent](https://github.com/FernCanCode/Restaurant-Voice-Agent)
`Python` · `FastAPI` · `Claude` · `RAG` · `MCP` · `Twilio` · `Docker`

A phone-capable AI agent that takes restaurant orders over a real phone line. It greets callers, answers menu questions from retrieved menu evidence, handles dietary/allergen questions cautiously, builds and modifies the order, tracks a running total, reads the order back, and returns a confirmation code. RAG-grounded on the menu with `sentence-transformers`, an MCP tool layer driving the order logic, and Twilio Programmable Voice for live calls — all reproducible via Docker Compose.

### [Lifting Pose Estimation](https://github.com/FernCanCode/lifting-pose-estimation)
`Python` · `MoveNet` · `MediaPipe` · `TensorFlow` · `Computer Vision`

Analyzes weightlifting form (squat, deadlift) from a single phone video and decides whether a rep was done correctly. The hard part was **monocular 3D pose estimation** — recovering accurate joint angles from one camera at an arbitrary angle. It pairs MoveNet Thunder with Kalman filtering for stable tracking, auto-detects front/side/oblique views, and uses a geometry engine to "un-rotate" oblique footage and measure true squat depth, knee valgus, and hip flexion — then segments the eccentric/concentric phases to score the lift.

### [Reversi AI Agent](https://github.com/FernCanCode/reversi-ai-project) — 1st place (x2)
`Python` · `Monte-Carlo Tree Search` · `Alpha-Beta Pruning` · `Deep Learning` · `Bitboards`

A Reversi-playing agent combining Monte-Carlo Tree Search, alpha-beta pruning, and an AlphaZero-style deep-learning player. It took **first place in both competitions** in my graduate AI course. The key performance unlock was a **bitboard** board representation (my contribution) — the board encoded as 64-bit integers with bitwise move generation, JIT-compiled with Numba — which made search fast enough to reach far greater depth within the per-move time limit. *(Team project.)*

### [Post2Place](https://github.com/FernCanCode/Post2Place)
`Python` · `NLP` · `Transformer Embeddings` · `PyTorch` · `Geospatial ML`

A research project (UTSA) that predicts the geographic coordinates of a tweet **from its text alone** — no profile metadata. Transformer embeddings feed a regression head that maps language directly to latitude/longitude. We assembled an **11-million-tweet** dataset (real geotagged tweets plus LLM-synthesized, news-grounded tweets) and reached a **754 km mean Haversine error — beating published baselines (PSOP, UnicodeCNN) by 2–4×**, with a downstream application flagging PFAS-contamination zones. *(Team research with B. Hinkley & J. De La Rosa.)*

<details>
<summary><b>More projects</b></summary>

- **[Library Management System](https://github.com/FernCanCode/DBMS_Project_Library)** — `Python` · `Streamlit` · `PostgreSQL`. A library management web app with dashboards, catalog/member lookup, checkout/return flows, and an analytics page driven by SQL JOIN/GROUP BY/HAVING queries.
- **SudoCode** — `Flutter` · `Dart`. A mobile app for learning data structures & algorithms through three interactive modes — a friendlier alternative to grinding LeetCode. *(Private repo — available on request.)*
- **[NLP Coursework](https://github.com/FernCanCode/NLP_Class)** — `Python`. Assignments and experiments from my graduate Natural Language Processing course.

</details>

---

## Skills

**Languages:** Python · C++ · Java · SQL · JavaScript · Dart · Bash

**ML / AI:** Deep Learning · Natural Language Processing · Computer Vision · Reinforcement Learning · Retrieval-Augmented Generation (RAG) · LLM Agents

**Libraries & Tools:** PyTorch · TensorFlow · scikit-learn · MediaPipe · sentence-transformers · NumPy · pandas

**Backend & Data:** FastAPI · Streamlit · PostgreSQL · Docker · MCP

---

## Get in touch
- **LinkedIn:** [fernando-canseco](https://www.linkedin.com/in/fernando-canseco-4817a6216/)
- **Email:** FernCanCode@gmail.com
