<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Hi%2C%20I'm%20Ashane%20👋&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%20and%20Cloud&descAlignY=58&descSize=20" alt="header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Software+Engineering+Graduate+at+Curtin+;Building+RAG+systems%2C+GNNs+and+AI+agents;FastAPI+%7C+.NET+%7C+React+%7C+Azure;Turning+ideas+into+production-ready+systems" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ashane-ar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:alarangalla@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://medium.com/@alarangalla"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="https://www.upwork.com/freelancers/~0112945997605f472d"><img src="https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white" alt="Upwork"/></a>
  <img src="https://komarev.com/ghpvc/?username=ashanearangalla&style=for-the-badge&color=0e75b6&label=Profile+views" alt="profile views"/>
</p>

---

## 🧑‍💻 About me

I'm a software engineer based in **Perth, Australia** 🇦🇺. I build **AI-powered backends, cloud-deployed apps and full-stack systems**, and I care about taking them past "it works on my machine" to something that's deployed, documented and maintainable.

```yaml
name: Ashane Arangalla
location: Perth, WA
currently:
  - Freelance developer on Upwork
education:
  - Bachelor of Computing (Software Engineering), Curtin University · CWA 82.09
  - Higher Diploma in Computing & Software Engineering (Distinction), Cardiff Metropolitan University
experience:
  - Completed Software Engineering Internship at Deloitte
  - Associate Software Developer @ Frost Colombo (2024)
focus: [AI engineering, RAG & LLM apps, graph ML, cloud (Azure), APIs]
learning: [CI/CD, AZ-900, AI-901, AZ-104]
off_keyboard: competitive cricket 🏏 (teamwork, discipline and strategy)
```

---

## 🚀 What I bring

| | |
|---|---|
| 🤖 **AI & LLM engineering** | RAG pipelines (LangChain, Qdrant, OpenAI), tool-calling agents with human-in-the-loop approval, prompt grounding with source citations |
| 🧠 **Machine learning** | Graph neural networks in PyTorch Geometric (GINEConv, GraphSAGE, GATv2) and a hybrid quantum GNN with PennyLane, for fraud detection |
| ⚙️ **Backend & APIs** | FastAPI, ASP.NET Core, Node/Express and PHP REST APIs; JWT auth; async job queues (RQ/Valkey); SQLAlchemy/EF Core with migrations |
| ☁️ **Cloud & DevOps** | Azure Container Apps, ACR, Key Vault, managed identity, Blob Storage, Log Analytics; Docker and Docker Compose |
| 🖥️ **Frontend & mobile** | React + Vite + Tailwind, D3 visualisations, Streamlit, native Android (Java), JavaFX |
| 🏗️ **Software design** | Plugin architectures, repository pattern, modular builds (JPMS/Gradle), Gitflow team workflows |

---

## 🛠️ Tech stack

<p align="center"><b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=py,java,cs,js,php,html,css&perline=7" alt="languages"/>
</p>

<p align="center"><b>Frameworks & libraries</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,dotnet,react,nodejs,express,tailwind,bootstrap,vite&perline=8" alt="frameworks"/>
</p>

<p align="center"><b>AI / ML</b><br/><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch_Geometric-3C2179?style=flat-square&logo=pyg&logoColor=white"/>
  <img src="https://img.shields.io/badge/PennyLane-1C1C1C?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
</p>

<p align="center"><b>Databases, cloud & tools</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite,azure,docker,git,github,linux,androidstudio,gradle,postman,vscode&perline=14" alt="tools"/>
</p>

---

## 🌟 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### ⚛️ [Q-Detect](https://github.com/ThaiGiaNganNGUYEN/Q-Detect)
**Hybrid quantum-classical money-mule detection** · *Curtin capstone with Deloitte*

Treats bank transactions as a graph and scores each one with GNNs, including a 2-qubit **PennyLane quantum GNN**. A crash-safe poller streams 50k-transaction batches through a model-serving microservice, and flagged activity is grouped into mule networks that analysts review in a D3 dashboard.

`PyTorch Geometric` `PennyLane` `FastAPI` `PostgreSQL` `React` `D3` `MSAL`

</td>
<td width="50%" valign="top">

### 📚 [rag-async](https://github.com/ashanearangalla/rag-async)
**Asynchronous RAG chat assistant for PDFs**

Questions are queued with RQ/Valkey and answered by background workers. They retrieve chunks from Qdrant and call OpenAI with conversation memory, and every answer cites its source page. Includes JWT auth, per-user chat history and Alembic migrations.

`FastAPI` `LangChain` `Qdrant` `OpenAI` `RQ` `PostgreSQL` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📸 [social-media-app](https://github.com/ashanearangalla/social-media-app)
**Instagram-style app deployed to Azure**

Full auth lifecycle with fastapi-users, image and video posts stored in Azure Blob Storage, and non-blocking uploads. Containerised with Docker and deployed to **Azure Container Apps** with ACR, Key Vault and managed identity.

`FastAPI` `async SQLAlchemy` `Azure` `Docker` `Alembic` `pytest`

</td>
<td width="50%" valign="top">

### 🎟️ [eventMgtSys](https://github.com/ashanearangalla/eventMgtSys)
**Event ticketing platform**

An ASP.NET Core 8 Web API with EF Core, the repository pattern and AutoMapper, plus a PHP frontend for customers, event partners and admins. Handles ticket types, sales and commission tracking. The backend is containerised and deployed to Azure.

`ASP.NET Core 8` `EF Core` `SQL Server` `Docker` `Azure`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧩 [texteditor](https://github.com/ashanearangalla/texteditor)
**Extensible JavaFX text editor**

Loads plugin JARs at runtime using reflection and Groovy scripts through a shared API. Key bindings come from a custom DSL parsed with **ANTLR**, and the UI is localised into English and Sinhala.

`Java 21` `JavaFX` `ANTLR` `Groovy` `Gradle` `JPMS`

</td>
<td width="50%" valign="top">

### 🐾 [PawPal](https://github.com/ashanearangalla/pawpal)
**Native Android pet-care booking app**

Pet owners post care requests, and caregivers search for and accept them. Built with separate role-based flows, bottom navigation and on-device SQLite.

`Java` `Android SDK` `SQLite` `Material`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🚌 [ezBusLK](https://github.com/ashanearangalla/ezBusLK)
**Online bus seat booking for Sri Lanka**: trip search, a seat map with a 5-minute seat hold, e-tickets, email confirmations, and dashboards for admins and operators. `PHP` `MySQL` `JavaScript` `PHPMailer`

</td>
</tr>
</table>

### 💼 Also built

- **AI customer-support agent** for an e-commerce client (Aromatic Hug). It uses FastAPI and Gemini tool-calling, with an approval queue for sensitive actions and least-privilege database access with column allowlists to protect customer data.
- **AutoDevOps**: a MERN-stack infrastructure co-pilot, live at [cmcloud.online](https://cmcloud.online)
- E-commerce builds for freelance clients, with AI chatbots
- REST APIs in FastAPI and plain PHP with JWT auth, including a Sri Lanka public holidays API

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ashanearangalla&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashanearangalla&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ashanearangalla&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

<!-- Snake animation: works once the snake workflow has run (see the setup guide) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ashanearangalla/ashanearangalla/output/github-contribution-grid-snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/ashanearangalla/ashanearangalla/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## 🎯 Currently

- 🌱 Studying **AI engineering and cloud computing** every day: AZ-900 → AI-901 → AZ-104, plus CI/CD pipelines
- ✍️ Writing about cloud deployments in plain language on Medium
- 🤝 Open to **graduate and junior software, AI or cloud engineering roles** in Australia

---

<p align="center">
  <i>"Prefer working code over theory, and always ask why."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" alt="footer"/>
</p>
