<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Abhishek%20Singh%20Kushwaha&fontSize=44&fontColor=ffffff&fontAlignY=32&desc=AI%20Software%20Engineer%20%C2%B7%20Agentic%20Systems%20%C2%B7%20RAG%20Pipelines&descAlignY=54&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&multiline=false&width=940&lines=AI+Software+Engineer+%C2%B7+6+Years+Shipping+Software;Building+Production+Agentic+AI+Systems;RAG+Pipelines+%C2%B7+LLM+Apps+%C2%B7+Full+Stack;Open+Weights+or+Frontier+API+%C2%B7+Whatever+Fits;Python+%7C+LangChain+%7C+LangGraph+%7C+FastAPI+%7C+AWS" alt="Typing SVG" />

<p>
  <a href="https://www.linkedin.com/in/abhishek-singh-kushwaha"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:abhisheksinghs.1031@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/AbhishekSinghKushwaha"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=AbhishekSinghKushwaha&color=A78BFA&style=flat-square&label=Profile+Views"/>
  <img src="https://img.shields.io/github/followers/AbhishekSinghKushwaha?style=flat-square&color=6366F1&label=Followers"/>
  <img src="https://img.shields.io/badge/Open_to-AI_Engineering_Roles-A78BFA?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Building_Agents-10B981?style=flat-square"/>
</p>

</div>

---

## 👋 About Me

I'm an **AI Software Engineer** with **6 years of experience** building full-stack applications and production-grade AI systems. I design **agentic workflows**, **RAG pipelines**, and **LLM-powered products** using Python, LangChain, LangGraph, and FastAPI, running on frontier APIs and open-weight models alike, deployed across AWS and Google Cloud.

My path runs from **data science** → **three years of full-stack engineering** shipping production apps for users across the US and Africa → **graduate AI research** on deep learning for Alzheimer's detection and biometric authentication. That arc means I think about AI systems from both the research bench and the production floor. I know what it costs when systems fail at scale.

```console
$ whoami --verbose

  role      →  AI Software Engineer @ Srasks
  focus     →  Agentic Workflows · RAG · LLM Systems · Cloud AI
  models    →  GPT · Claude · Gemini · Llama · Mistral · Qwen · DeepSeek
  runtime   →  Ollama · Groq · Docker · Kubernetes · AWS · GCP
  daily     →  Claude Code · Codex · OpenCode · Antigravity
  open_to   →  Senior AI Engineer · Applied AI Engineer · AI/ML Engineer
  motto     →  "Make it correct, then make it cheap, then make it fast."

$ _
```

---

## 🧬 How I Build Agentic Systems

> The shape almost every system I ship converges on: routed, grounded, evaluated, and cheap by default.

```mermaid
flowchart LR
    U([User]) --> R{Router<br/>LangGraph}

    R -->|simple| S[Small Open Model<br/>Llama · Qwen · Mistral]
    R -->|hard| F[Frontier API<br/>GPT · Claude · Gemini]
    R -->|retrieval| RAG[[RAG Pipeline]]

    RAG --> E[Embed + Chunk]
    E --> V[(Vector Store<br/>Weaviate · FAISS)]
    V --> RR[Rerank + Ground]
    RR --> F

    S --> T{{Tool Layer<br/>APIs · SQL · Code}}
    F --> T
    T --> G[Guardrails<br/>+ Validation]
    G -->|pass| O([Response])
    G -->|fail| R

    O --> OBS[/Traces · Evals · Cost<br/>LangSmith/]
    OBS -.->|feedback loop| R

    classDef acc fill:#302b63,stroke:#A78BFA,stroke-width:2px,color:#fff
    classDef store fill:#1C3C3C,stroke:#10B981,stroke-width:2px,color:#fff
    classDef edge fill:#0f0c29,stroke:#6366F1,stroke-width:2px,color:#fff
    class R,S,F,G acc
    class V,E,RR,RAG store
    class U,O,T,OBS edge
```

---

## 🛠️ Tech Stack

<details open>
<summary><b>🧠 Models & Inference</b></summary>
<br>
<p>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic_Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Llama_3.x-0866FF?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/Mistral_%2F_Mixtral-FA520F?style=for-the-badge&logo=mistralai&logoColor=white"/>
<img src="https://img.shields.io/badge/Qwen-6236FF?style=for-the-badge&logo=alibabacloud&logoColor=white"/>
<img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemma-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge"/>
</p>
</details>

<details open>
<summary><b>🤖 AI Coding Agents</b></summary>
<br>
<p>
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCode-1C1C1C?style=for-the-badge&logo=opensourceinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
</p>
</details>

<details open>
<summary><b>🔗 AI / ML Frameworks</b></summary>
<br>
<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LlamaIndex-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/LoRA_%2F_PEFT-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>
</details>

<details open>
<summary><b>💻 Languages, Backend & Web</b></summary>
<br>
<img src="https://skillicons.dev/icons?i=python,js,ts,c&theme=dark"/>
<br><br>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,react,nextjs,angular&theme=dark"/>
</details>

<details open>
<summary><b>🗄️ Data, Vector & Cloud</b></summary>
<br>
<p>
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Weaviate-3B82F6?style=for-the-badge&logo=weaviate&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white"/>
</p>
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>
</details>

---

## 🔭 Currently

```text
▸ Building     multi-agent workflows with LangGraph + MCP tool servers
▸ Exploring    open-weight model routing with Ollama and Groq
▸ Learning     eval-driven development & LLM observability at scale
▸ Ask me about RAG that survives contact with real documents
```

<div align="center">

*Building at the intersection of agentic AI, retrieval systems, and production infrastructure.*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
