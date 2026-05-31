# Hi, I'm Deepali 👋
📍 New York, NY &nbsp;·&nbsp; 📧 db5144@nyu.edu &nbsp;·&nbsp; 💼 [linkedin.com/in/deepali-bk](https://linkedin.com/in/deepali-bk) &nbsp;·&nbsp; 🌐 [Portfolio](https://www.datascienceportfol.io/deepalibalakrishnate)

---

## About Me

I'm a Data Science grad student at NYU who builds AI systems that actually work — not just on benchmarks, but in the real world. From placing at hackathons with multimodal Gemini agents to shipping production NLP pipelines that process millions of documents, I care about the full journey from idea to deployed system. My work spans NLP, LLMs, healthcare AI, and multi-agent architectures across research, enterprise, and hackathon stages.

- 🔬 Graduate Research Assistant @ NYU Rory Meyers College of Nursing
- 🏆 3rd Place — GDG NYC × NYU Tandon "Build With AI" Hackathon 2026 (TenantShield)
- 🏆 Violet Internship & Research Award 2025 & 2026
- 🌐 Women in Data Science Ambassador 2026
- 📄 Published Researcher — International Journal of Engineering Research & Technology (IJERT)

---

## 🛠 Tech Stack

**Languages & Tools**
`Python` `R` `SQL` `C++` `Kotlin` `TypeScript` `Git`

**Machine Learning & Deep Learning**
`Scikit-learn` `PyTorch` `TensorFlow` `XGBoost` `Flair` `FastText` `LoRA` `Reinforcement Learning` `Computer Vision`

**NLP & Generative AI**
`HuggingFace Transformers` `LangChain` `LangGraph` `SpaCy` `BERT` `RoBERTa` `GPT-4` `RAG Systems`
`Gemini API` `Gemini Live API` `Google ADK` `Multi-agent AI (A2A)` `Vertex AI`
`RLHF` `PPO-Lagrangian` `Sentiment Analysis` `Topic Modeling` `Named Entity Recognition` `Few-shot Prompting`

**Cloud & Backend**
`Google Cloud` `Firebase (Auth, Firestore, Storage)` `Vertex AI` `FastAPI` `Temporal` `Render` `Vercel`

**Frontend & Mobile**
`Next.js` `React` `Tailwind CSS` `Framer Motion` `Jetpack Compose` `CameraX` `Android (Kotlin)`

**Data & Visualization**
`Pandas` `NumPy` `Matplotlib` `Seaborn` `Tableau` `ClickHouse` `Spark` `Hadoop (HDFS)`

**Statistics**
`Statistical Modeling` `Bayesian Methods` `A/B Testing` `Hypothesis Testing`

---
## 🚀 Featured Projects

### 🏆 [TenantShield — AI Building Inspection & Complaint Platform](https://github.com/Deepali-BK/TenantShield.git) *(GDG NYC × NYU Tandon "Build With AI" Hackathon — 3rd Place 🥉)*
Multi-agent AI platform helping tenants document housing violations and auto-generate formal NYC housing complaints — built in one day at NYC Open Data Week.
- Designed a **3-agent A2A pipeline** (Interacting → Inspection → Filing) coordinated by a central state machine
- **Interacting Agent** uses **Gemini Live API** (real-time voice over WebSocket) for conversational tenant intake
- **Inspection Agent** performs **multimodal image analysis** to classify violations per NYC Housing Maintenance Code (Class A / B / C)
- **Filing Agent** generates structured, legally-formatted complaint documents from inspection results
- Full-stack: Android mobile app (**Kotlin, Jetpack Compose, CameraX**) + web application, backed by **Firebase** (Auth, Firestore, Storage)
- 🤝 Team project with 3 NYU collaborators — judged by engineers from Meta, Bloomberg, Instagram & Google

`Gemini Live API` `Vertex AI` `Firebase` `Google Cloud` `Kotlin` `Jetpack Compose` `CameraX` `Multi-agent AI` `A2A`

### 🤔 [To Ask or Not to Ask — Strategic Clarification in LLM Agents](https://github.com/Deepali-BK/rl_llm_multiturn_cmdp)
RL agent trained to decide *when* to ask clarifying questions vs. answer directly — balancing answer quality against over-questioning via a Constrained MDP.
- Fine-tuned **Qwen2.5-Coder-7B** via **LoRA + PPO-Lagrangian (RLHF)** on the HumanEvalComm benchmark
- Used a **GPT-4o-mini simulator** to evaluate across clarification budgets; best policy achieves **+6.2pp MT pass@1** over untrained baseline (*p* < 0.0001)

`Reinforcement Learning` `PPO-Lagrangian` `LoRA` `RLHF` `Qwen2.5-Coder-7B` `LangChain` `HumanEvalComm`



### ☕ [CoffeeAgntcy — Multi-Agent System Optimization](https://github.com/Deepali-BK/Coffee-Agentcy-Optimization)
Profiled and optimized a distributed multi-agent AI system running across 10 Docker containers with LangGraph A2A architecture.
- Used **cProfile** to pinpoint OpenAI API I/O as the bottleneck
- Applied **asyncio + aiohttp** concurrency, **MD5-keyed caching**, and TCP pooling — achieving **17% latency reduction** and **12,000× throughput gain**

`asyncio` `aiohttp` `LangChain` `LangGraph` `GPT-4o` `Docker` `cProfile`

### 🔍 [Muck Rack — HTML Quality Detection Pipeline](https://github.com/Deepali-BK/Article-Ingestion-Pipeline-for-Muck-Rack) *(Capstone)*
Production-grade ML pipeline combining **BeautifulSoup + XGBoost** with rule-based heuristics for HTML quality detection for PR firm Muck Rack.
- Achieved **0.98 precision / 0.920 F1** score
- Built a **GPT-4.1-mini few-shot labeling pipeline** to expand an imbalanced seed dataset
- Eliminated manual QA bottlenecks entirely

`Python` `XGBoost` `BeautifulSoup` `GPT-4` `Few-shot Learning` `ML Pipelines`

### 🧠 [Emotion Learning Evaluation for LLMs](https://github.com/Deepali-BK/NLU-project)
Benchmarked emotional intelligence capabilities of **Gemma, Qwen, and Llama** using zero-shot and few-shot prompt engineering.
- Demonstrated above-chance performance across all three models
- Leveraged **LangChain** and **HuggingFace** for evaluation orchestration

`LangChain` `HuggingFace` `Prompt Engineering` `Zero-shot` `Few-shot` `LLM Evaluation`

### 🛒 [Auto E-Commerce — Autonomous Trend-to-Storefront Pipeline](https://github.com/Deepali-BK/Auto-Ecommerce) *(Agentic Engineering Hack)*
Autonomous multi-agent system that detects niche microtrends and launches a full e-commerce store end-to-end — no human required.
- Built a **CEO Orchestrator Agent** coordinating 5 specialized sub-agents: Research, Buyer, Legal/Risk, Advertising, and Store Creator
- **Research Agent** scores trend strength via **Nimble API**; **Store Creator** spins up a live storefront at a unique subdomain in minutes
- Every agent decision stored in **ClickHouse** as long-term memory, feeding back into future agent prompts for improved scoring
- Full observability via **Datadog** traces; durable agent orchestration via **Temporal** (retry-safe, LLM-flakiness-proof)
- 🤝 Team project with 3 collaborators

`Google ADK` `Gemini 2.5 Flash` `Temporal` `ClickHouse` `Nimble API` `Datadog` `FastAPI` `Next.js` `Multi-agent AI`


### 🎮 [heart-maxxxxing — Cardiac Rehab Gamification](https://devpost.com/software/heart-maxxxxing) *(Pulse Foundry AI Healthcare Hackathon 2026)*
Mario-style browser game that turns the standard 36-session cardiac rehabilitation program into an interactive world-map adventure — making recovery feel like play, not a clinical chore.
- Reframed 36 rehab sessions as "Levels" on a platformer world map with Power-Ups, milestones, and safety pause prompts for over-exertion
- Integrated **Gemini API** as an in-game AI guide providing personalized, encouraging tips at each stage of recovery
- Built accessible, high-contrast pixel-art UI with **Framer Motion** animations targeting patients of all ages
- Deployed on **Vercel** with a **Next.js + React** frontend
- 🤝 Team project with 3 collaborators

`Gemini API` `Next.js` `React` `Tailwind CSS` `Framer Motion` `Vercel` `Healthcare AI`


### 🏥 [Interactive Health Bot](https://github.com/Deepali-BK/Voice-Based-Disease-Prediction-using-NLP-Random-Forest-on-Raspberry-Pi)
Voice-based disease prediction system using NLP & Random Forest deployed on Raspberry Pi — achieving **95.02% accuracy**.
- Designed an end-to-end pipeline: Speech-to-Text → NLP symptom extraction → Random Forest classification → TTS feedback
- Received **₹37,000 funding** by Innovative and Entrepreneurship Development Centres (IEDC), Indian Govt.
- 📄 [Published in IJERT](https://www.ijert.org/research/symptoms-extraction-from-a-voice-input-using-natural-language-processing-IJERTV9IS040645.pdf)

`Python` `NLTK` `Scikit-learn` `Speech Recognition` `Raspberry Pi`

---

## 💼 Experience

### Graduate Research Assistant — NYU Rory Meyers College of Nursing *(Sep 2025 – Present)*
- Statistical modeling on survey data from **90+ countries** for COVID-19 healthcare pattern recognition
- Built interactive **Tableau dashboard** for the organization's public-facing website
- **BERT-based multi-class classifier** achieving **87% accuracy** on 5,000+ survey responses on violence against medical professionals

### Data Science Intern — Global Consortium of Nursing & Midwifery Studies *(Jun – Sep 2025)*
- Analyzed **21,000+ survey responses** across **40+ languages** using multilingual **RoBERTa**
- Applied sentiment analysis and topic modeling on PPE usage data during COVID-19

### Software Engineer (ML) — CGI Inc. *(Feb 2022 – Jun 2023)*
- Led **NER implementation** as SME for a Fortune 500 telecom client — extracted entities from **2M+ unstructured documents** using SpaCy
- Reduced manual review time by **71%** through automated document processing
- Built classification system with **Flair + FastText** to categorize 10,000+ reviews for C-suite strategic planning

---

## 🎓 Education

| Degree | Institution | Year |
|--------|------------|------|
| M.S. Data Science | New York University | 2024 – 2026 |
| B.E. Electronics & Communication | B.N.M Institute of Technology | 2016 – 2020 |

**Relevant coursework:** Deep Learning · Machine Learning · Natural Language Understanding · Reinforcement Learning · Big Data · AI Applications in Business (NYU Stern)

---

*Always open to research collaborations and data science opportunities. Feel free to reach out!*
