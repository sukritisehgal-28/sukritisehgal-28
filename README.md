# Hey, I'm Sukriti Sehgal 👋

### Founder & CEO @ Oriva Health · AI Engineer

**I build clinical AI, from the decision engine and LLM pipeline to the clinic workflow it runs in.**

🟢 **Looking for opportunities:** AI engineering, applied AI, ML engineering and AI product roles, in any location. [Let's talk →](mailto:sukritisehgal2800@gmail.com)

🏆 **Healthcare AI Hackathon: 2nd Place + People's Choice** · **CalHacks 12.0 Winner (Fetch.ai Track)** · **NSF I-Corps Fellow**  
🎓 **MS Data Science, University of Colorado Boulder (2026)**  
📍 **San Francisco Bay Area** · 🌐 **[sukritisehgal.me](https://sukritisehgal.me)**

---

## 🦷 Building Oriva Health

**Founder & CEO** (Oct 2026 – now). Before that, **Founder & AI Engineer** (Apr – Sep 2026), while Oriva was a CU Boulder venture backed by Catalyze CU and NSF I-Corps.

Oriva is a clinical AI platform for dental practices, working with **2 design-partner clinics**. Veronica, the voice agent built by our CTO, has taken real patient calls since September 2026 and books visits through the scheduler I built.

- Built the **clinical engine** (Python, FastAPI, Cloud Run) from AAE guidelines and the research literature, refined with CU Anschutz faculty. It returns a confidence level and an urgency band for every case.
- **Kept the LLM out of clinical decisions:** Claude Haiku 4.5 only turns what patients say into structured answers, and a safety layer checks for red flags on every turn.
- Built a **voicemail triage service** (Twilio, Deepgram Nova-3, Claude Haiku 4.5 with schema-constrained JSON) that sorts messages by intent and flags emergencies.
- Created the **Smart Questionnaire** (Next.js, React) and a **booking service** (FastAPI, PostgreSQL, Cloud Tasks).
- Wrote an **evaluation harness** over a **459-case labelled set**, tracking top-1 and top-3 accuracy, urgency accuracy and calibration.
- Ran **60+ NSF I-Corps interviews** and signed **7 letters of intent**.
- **$25K equity-free** from Catalyze CU · Boulder Startup Week finalist · TiE Women Silicon Valley semifinalist · Chicago Venture Summit 2026 Future of Health portfolio

`Clinical AI` `Claude` `FastAPI` `Next.js` `Twilio` `Deepgram` `PostgreSQL` `Cloud Run`

---

## 🚀 Featured Projects

### 🏥 Project Uzima: Emergency Bed-Finding Voice Agents
A multi-agent system that calls every capable hospital at once to find a bed for a critically ill patient. Each hospital gets its own voice agent (Twilio, GPT OSS on AWS Bedrock), and every answer is read back and confirmed before it counts. Six FastAPI microservices handle call coordination, voice, live event streaming and an encrypted **HL7 FHIR** patient handoff through a SMART Health Link, behind a React map dashboard, covered by 76 automated tests.

🏆 **2nd Place + People's Choice, Healthcare AI Hackathon (AWS × OpenAI), San Francisco**

[Code](https://github.com/sukritisehgal-28/project-uzima) · [Live site](https://project-uzima.vercel.app) · [Demo video](https://youtu.be/xUHAnPiojRM)

`Python` `FastAPI` `React` `Twilio` `AWS Bedrock` `HL7 FHIR` `GCP Cloud Run`

---

### 🧬 ATLAS-MD: Agentic Clinical Research Workspace
Turns a clinical question into an interactive **knowledge graph** of the research behind it. It scores the evidence, flags studies that disagree, and runs a research agent that reads alongside you and opens new search threads as patterns emerge.

[Live site](https://atlasmd.live) · [Code](https://github.com/sukritisehgal-28/ATLAS-MD) · [Demo video](https://youtu.be/IdHC7GCf-JA)

`React` `Express` `SQLite` `D3.js` `Gemini` `Semantic Scholar` `AI Agents`

---

### 🎤 InterViewAR: Real-Time VR Interview Coach
A Meta Quest 3 interview coach. Seven Fetch.ai agents turn live mic audio into pace, filler-word and tension scores, push coaching cues to a WebXR HUD every 1.5 seconds, and batch speech by silence before Groq Whisper.

🏆 **Winner, Fetch.ai Track, CalHacks 12.0**

[Code](https://github.com/sukritisehgal-28/InterVIew-AR-Calhacks2025) · [Devpost](https://devpost.com/software/interviewar) · [Article on Fetch.ai's Medium](https://medium.com/fetch-ai/agentviewar-building-empathy-into-interviews-with-fetch-ai-agents-e2c6ebb0d8ad)

`WebXR` `FastAPI` `Groq Whisper` `Fetch.ai` `AI Agents`

---

### 🛒 OmniShelf AI: Retail Computer Vision
An end-to-end system for **retail shelf monitoring, SKU localization, planogram comparison and out-of-stock detection**. A multi-stage pipeline combines SKU-110K localization, a fine-tuned YOLOv11 model and automated vision verification.

**95.51% mAP@50 · 84.89% Precision · 88.52% Recall**

[Code](https://github.com/sukritisehgal-28/OmniShelf-AI-CV) · [Demo video](https://youtu.be/DcdsqbaZNQo)

`YOLOv11` `Computer Vision` `FastAPI` `React/TypeScript` `Python`

---

### 🏥 Secure Medical AI: Clinical Documentation Platform
A full-stack healthcare platform with retrieval-augmented clinical summaries, semantic search across medical notes, role-based access and PostgreSQL-backed patient data, deployed on GCP. Built with [Sakshi Asati](https://github.com/sakshiasati17).

[Live demo](https://sukritisehgal-28.github.io/Secure-med-ai/) · [Code](https://github.com/sukritisehgal-28/Secure-med-ai) · [Demo video](https://youtu.be/iyclbDlEuXg)

`React` `TypeScript` `FastAPI` `LangChain` `FAISS` `GCP` `PostgreSQL`

---

## 💼 Experience

### 🤖 Data Science & AI Intern, GoodieBag Food Co. (Techstars-backed) · Jun 2025 – Apr 2026
- Shipped the company's **first AI support chatbot** for 180K+ customers (RAG on PostgreSQL/pgvector, FastAPI, HubSpot). It resolves routine tickets on its own and flags likely fraud, **cutting manual triage by 70%**.
- Developed a **multimodal agent** that turns product photos into ready-to-post marketing content, **raising content output by 55%**.
- Set up the company-wide **Tableau analytics platform** (SQL pipelines, 20+ KPIs) for sales, partner onboarding and orders.

### 📊 Data Analytics Intern, C5 Consultare / University of Denver · Sep 2025 – Mar 2026
- Worked with a PhD researcher on **whether college pays off**: merged national debt and earnings data (100K+ records), modeled which programs leave graduates in financial distress, shipped a searchable dashboard and presented the findings to client executives in Power BI.

### 🎓 Course Assistant, University of Colorado Boulder · 2026
- Taught **12 labs in Python, R and Excel to 120+ students**.

### 🧠 Machine Learning Engineer Intern, Omdena · 2023 – 2024
- Improved a **tuberculosis risk-prediction** pipeline in TensorFlow and shipped an end-to-end prototype (model and Streamlit app) with a global team.

### 🔬 Machine Learning Intern, DRDO · 2022 – 2023
- Built transformer summarization pipelines with Hugging Face and spaCy, reaching **0.85+ BERTScore**, and privacy-preserving NLP workflows. [Code](https://github.com/sukritisehgal-28/Summerizer-using-GPT)

### 🌊 Research Intern, NITI Aayog
- Built a logistic regression model that predicts **floods in Assam** from monthly rainfall, with about **95% accuracy**. [Code](https://github.com/sukritisehgal-28/Flood-Prediction-Model_)

---

## 🧠 Technical Toolkit

**AI & LLMs**

`Claude` · `Gemini` · `AWS Bedrock` · `Deepgram` · `RAG (pgvector, FAISS)` · `Tool calling` · `Structured outputs` · `Multi-agent systems` · `LLM evals`

**Engineering & Data**

`Python` · `SQL` · `FastAPI` · `PostgreSQL` · `Next.js` · `React` · `Docker` · `Google Cloud` · `pandas` · `R` · `scikit-learn` · `PyTorch` · `Tableau` · `Power BI`

**Product & Healthcare**

`Customer discovery` · `Workflow mapping` · `User testing` · `Clinical workflows` · `HL7 FHIR` · `HIPAA` · `Audit logging`

---

## 🏆 Highlights

- 🏆 **2nd Place + People's Choice, Healthcare AI Hackathon (AWS × OpenAI)**
- 🏆 **Winner, Fetch.ai Track, CalHacks 12.0**
- 🚀 **Founder & CEO, Oriva Health**
- 💰 **$25K equity-free, Catalyze CU accelerator**
- 🔬 **NSF I-Corps Fellow** (Starting Blocks and R2M)
- 🌟 **Finalist, Boulder Startup Week** · **Semifinalist, TiE Women Silicon Valley** · **Chicago Venture Summit 2026, Future of Health portfolio**
- 📄 **IEEE Access (2024):** co-author of a usability study of payment apps with 15 visually impaired participants
- 🎓 **MS Data Science, University of Colorado Boulder** · Former Chair, Data Science Student Association
- ⚡ Hackathon **builder, winner and judge**

---

## 🌱 A Little More About Me

My path has taken me from **ML research and data science → production AI systems → winning hackathons → working with clinicians → building a startup from zero**.

That changed how I approach technology. I care about the model, but just as much about **what problem it solves, how the system is engineered, and whether someone actually wants to use it.**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sukritisehgal-28&show_icons=true&theme=tokyonight&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sukritisehgal-28&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

---

## 📬 Let's Connect

[![Portfolio](https://img.shields.io/badge/-sukritisehgal.me-1C1D22?style=flat-square&logo=googlechrome&logoColor=white)](https://sukritisehgal.me)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sukriti-sehgal28/)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sukritisehgal2800@gmail.com)
[![Book a call](https://img.shields.io/badge/-Book_a_call-4285F4?style=flat-square&logo=googlecalendar&logoColor=white)](https://calendar.app.google/jkD169VRaqfqENtb9)

---

**🟢 Looking for opportunities in AI engineering, applied AI, ML engineering and AI product, in any location. If you're building something real, I'd love to talk.**
