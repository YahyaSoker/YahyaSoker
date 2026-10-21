# Hi there, I'm Yahya Söker 👋 

### AI Solutions Architect | Enterprise AI Agents · Edge & Local AI · Full Stack

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=435&lines=Building+Enterprise+AI+Agents;Running+LLMs+Locally;Shipping+Edge-AI+Systems;From+Cloud+to+Device" alt="Typing SVG" />
</div>

I build AI systems end to end, wherever they need to run: **agentic platforms on Azure** for enterprise teams, **air-gapped LLMs and RAG** on local hardware, and **real-time inference** on edge and mobile devices. Currently at **PEAKUP**, taking AI products from first prototype to production.

---

### 🚀 Key Architecture & Projects

#### 🏢 Enterprise AI

**Read-only Ops ChatOps Agent**
> An assistant for enterprise IT operations teams. Engineers ask about system health in plain language and get answers pulled from logs, clusters, databases and message queues in a single chat, scoped to their own permissions and fully audited. Read-only by design.
> ⚙️ **Flow:** `Question` ➔ `Role-Based Access Check` ➔ `MCP Tools (Logs · OpenShift · DB · Kafka)` ➔ `Audited Answer`
> 🛠️ **Tech:** `MCP` `OpenShift` `Kafka` `Azure OpenAI` `Python`

**Solution Design Agent**
> Collects sales requirements from chat, forms or customer documents. An LLM structures them, a rule engine produces deterministic sizing, and the output is a single reviewable Word report that ships only after human approval.
> ⚙️ **Flow:** `Requirements` ➔ `LLM Structuring` ➔ `Deterministic Rule Engine` ➔ `Human-Approved Report`
> 🛠️ **Tech:** `FastAPI (SSE)` `React` `PostgreSQL + pgvector` `Hybrid Search` `Docker`

**AI Adoption & Maturity Platform**
> A multilingual platform where employees complete a voice or text interview. The system scores AI maturity, builds an explainable capability profile and surfaces automation opportunities for the organization.
> ⚙️ **Flow:** `Voice Interview` ➔ `Speech-to-Text` ➔ `Agent Scoring` ➔ `Personal & Org Reports`
> 🛠️ **Tech:** `Next.js` `FastAPI` `Azure OpenAI` `Azure Speech` `PostgreSQL`

**Multi-Agent Orchestration Platform**
> An internal chat platform where a router sends each question to the right department agent and streams the answer token by token, both on the web and inside Microsoft Teams / M365 Copilot.
> ⚙️ **Flow:** `User Query` ➔ `Router` ➔ `Department Agents` ➔ `SSE Stream (Web · Teams)`
> 🛠️ **Tech:** `Azure OpenAI` `Cosmos DB` `Redis` `Entra ID` `Teams`

#### 🔬 Edge & Local AI

**Local NotebookLM & Mind-Mapper**
> Built a local research assistant using LLM-aided OCR to extract handwritten "stickers" and notes. Powered by a local LLM, it dynamically generates interactive, expandable flowcharts and a vectorized knowledge base for local RAG.
> ⚙️ **Flow:** `Image Ingest` ➔ `LLM OCR` ➔ `Entity Extraction` ➔ `Dynamic Expanding Flowchart`
> 🛠️ **Tech:** `Local LLM` `Dynamic UI` `OCR` `Local RAG`

**Nebulai Ecosystem**
> Architected a local LLM cluster and an agentic routing system. Cut token costs by 30% and operational costs by 60%.
> ⚙️ **Flow:** `User Query` ➔ `Router Agent` ➔ `vLLM Cluster` ➔ `Cost-Optimized Output`
> 🛠️ **Tech:** `vLLM` `Agentic Orchestration` `Cost Optimization`

**OpTomo (Medical Diagnostic Pipeline)**
> Designed an end-to-end inference pipeline for breast cancer detection, migrating heavy Python logic to hardware-accelerated bindings for a 40% latency reduction.
> ⚙️ **Flow:** `Medical Scan` ➔ `Python Preprocessing` ➔ `C++ Inference Bindings` ➔ `Real-Time Diagnosis`
> 🛠️ **Tech:** `C++` `Python` `Hardware Optimization` `Edge Inference`

**Secure Enterprise RAG**
> Built an air-gapped "Talk-to-your-Data" tool utilizing hybrid search and robust data engineering pipelines.
> ⚙️ **Flow:** `Enterprise Data` ➔ `Apache NiFi Ingest` ➔ `Hybrid Search (BM25 + Vector)` ➔ `Secure LLM`
> 🛠️ **Tech:** `Apache NiFi` `Milvus / Pinecone` `Hybrid Search` `Air-gapped LLM`

**Mobile Edge-AI Engine**
> Engineered a hot-swappable mobile inference engine capable of switching neural architectures at runtime without requiring app store updates.
> ⚙️ **Flow:** `Android App` ➔ `Kotlin Orchestrator` ➔ `ONNX Model Hot-Swap` ➔ `On-Device Inference`
> 🛠️ **Tech:** `Kotlin` `ONNX` `Android SDK` `Neural Architecture`

### 🐍 Contribution Snake
<div align="center">
  <img src="https://github.com/YahyaSoker/YahyaSoker/raw/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution snake animation" />
</div>

---

### 🛠️ Tech Stack

**Cloud & Enterprise AI**
<br>
<img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logoColor=white" alt="Microsoft Azure" />
<img src="https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logoColor=white" alt="Azure OpenAI" />
<img src="https://img.shields.io/badge/Azure%20AI%20Foundry-0078D4?style=for-the-badge&logoColor=white" alt="Azure AI Foundry" />
<img src="https://img.shields.io/badge/Azure%20Speech-0078D4?style=for-the-badge&logoColor=white" alt="Azure Speech" />
<img src="https://img.shields.io/badge/Bicep-0078D4?style=for-the-badge&logoColor=white" alt="Bicep" />
<img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" alt="OpenShift" />

**Edge AI & Hardware Optimization**
<br>
<img src="https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX" />
<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="TensorRT" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
<img src="https://img.shields.io/badge/GGUF%20%2F%20Llama.cpp-000000?style=for-the-badge&logo=github&logoColor=white" alt="GGUF / Llama.cpp" />

**Generative AI & Agents**
<br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude" />
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge&logoColor=white" alt="vLLM" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />

**Data Engineering, RAG & Databases**
<br>
<img src="https://img.shields.io/badge/Apache%20NiFi-729819?style=for-the-badge&logo=apache&logoColor=white" alt="Apache NiFi" />
<img src="https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white" alt="Milvus" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logoColor=white" alt="pgvector" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />

**Computer Vision**
<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLO" />

**Full Stack & DevOps**
<br>
<img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=YahyaSoker&theme=dark&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub Streak" />
</p>

### 📫 Connect
<p align="left">
  <a href="https://linkedin.com/in/yahyasoker">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:artificialyahya@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.kaggle.com/yahyasoker">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
  </a>
</p>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=YahyaSoker&style=flat-square&color=38BDF8&label=Profile+Views" alt="Profile Views" />
</div>
