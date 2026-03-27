<h1 align="center">Hi, I'm Siddhant Jain 👋</h1>
<p align="center">
Building production-grade <b>Generative AI systems</b> with <b>multi-agent orchestration</b>
</p>

---

## 💫 About Me

I'm an **AI/ML Engineer** specializing in **Generative AI and multi-agent systems**, with hands-on experience designing and deploying **production-grade LLM workflows**.

I specialize in:
- **Multi-agent orchestration** using LangGraph, LangChain, MCP, and Autogen  
- **Tool-based agents** with memory, state, and human-in-the-loop control  
- **Scalable GenAI backends** built on Azure (Functions, Cosmos DB, Blob Storage, App Service)

I build systems where LLMs don't just respond — they **reason, delegate tasks, invoke tools, coordinate with other agents, and operate under real-world constraints** like latency, reliability, and safety.

Currently at **Accenture**, I work on improving GenAI system performance, architecture, and developer usability, while evaluating emerging multi-agent frameworks for enterprise adoption.

---

## 🔗 Connect With Me

<p align="left">
<a href="mailto:jainsiddhant603@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/siddhant-jain-ai">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/siddhant603">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white"/>
</a>
</p>

---

## 💻 Core Tech Stack

### 🧠 Generative AI & Agents
<p>
<img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-4285F4?logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-0B3C5D"/>
<img src="https://img.shields.io/badge/LangGraph-1F2937"/>
<img src="https://img.shields.io/badge/Autogen-000000"/>
</p>

### ☁️ Cloud & Backend
<p>
<img src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-FF9900?logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-005571?logo=fastapi"/>
<img src="https://img.shields.io/badge/Flask-000000?logo=flask"/>
<img src="https://img.shields.io/badge/JWT-black?logo=jsonwebtokens"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black"/>
</p>

### 📊 Data & Vector Search
<p>
<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-blue"/>
<img src="https://img.shields.io/badge/FAISS-0467DF"/>
<img src="https://img.shields.io/badge/Chroma-000000"/>
</p>

### 🤖 ML & Data Science
<p>
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv"/>
</p>

---

## 🚀 Featured Projects

### 🛡️ Brand Guardian AI — Video Compliance Audit System  
**Tech:** LangChain, LangGraph, Azure OpenAI (GPT-4), Azure Video Indexer, Azure AI Search, FastAPI  

- Built an **AI-powered compliance auditing system** that automatically analyzes video content against brand guidelines, FTC regulations, and advertising standards  
- Designed a **LangGraph workflow** with two nodes — Indexer (video processing) and Auditor (RAG-based compliance checking) — orchestrated end-to-end  
- Used **Azure Video Indexer** to extract speech transcripts and on-screen text (OCR) from YouTube videos  
- Applied **RAG pattern** with Azure AI Search (vector DB) to match video content against indexed compliance rules  
- Exposed results via a **FastAPI REST API** with structured JSON reports, severity classification (CRITICAL / WARNING), and session tracking  

> **Pipeline:** YouTube Video → Azure Video Indexer → Transcript + OCR → RAG (Azure AI Search + GPT-4) → Compliance Report

---

### 🏥 Medical RAG Chatbot — AWS Bedrock  
**Tech:** LangChain, Pinecone, AWS Bedrock (Llama 3), HuggingFace, Streamlit  

- Built an end-to-end **RAG pipeline** for medical question-answering over PDF knowledge bases  
- Used **HuggingFace `all-MiniLM-L6-v2`** embeddings with **Pinecone** for persistent vector storage and semantic retrieval  
- Integrated **Meta Llama 3 8B via AWS Bedrock** for serverless LLM inference — no GPU required  
- Delivered answers with **source attribution**, showing which document chunks backed each response  
- Built a **Streamlit chat UI** with session history, sample questions, and a clean conversational interface  

> **Pipeline:** PDF Documents → Chunked & Embedded → Pinecone → RAG Chain → Llama 3 → Streamlit UI

---

## 🧠 System Design Focus

- Multi-agent coordination & control flow  
- LLM state and memory management  
- Tool isolation and failure handling  
- Latency and cost optimization  
- Human-in-the-loop safety mechanisms  

---

## 🧩 Currently Exploring

I'm currently learning **n8n** to design **automation workflows** that connect APIs, tools, and AI systems.

My focus is on building **event-driven, reusable automation pipelines** that integrate LLM-based decision-making with real-world services.  
Projects will be published as these workflows mature into production-style use cases.

---
