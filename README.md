
### **Andres Teheran** · `@4ndr3s-00`

_Software Developer in training @ **RIWI**_

<p align="center">
  <a href="https://4ndr3s-00.github.io/Portfolio/"><img src="https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/andres-teheran/"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/4ndr3s-00"><img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

</div>

---

### 👨💻 About Me

I'm a **Software Developer in training** at **RIWI**, focused on building production-ready architectures, optimizing performance, and engineering practical software.

- 📄 Built **[PDF-Engine](https://github.com/4ndr3s-00/PDF-Engine)** — high-performance hybrid document & OCR engine (< 3.5s per doc, $0 cloud cost)
- 🔥 Created **[freecode-zero](https://github.com/4ndr3s-00/freecode-zero)** — run OpenCode 100% free with smart multi-provider rotation
- 🧠 Engineered **[Mentia](https://github.com/4ndr3s-00/mentia-learning-lab)** — adaptive learning platform with a rule-based ranking engine
- 🐧 Daily driver: **Arch Linux + Hyprland**, fully customized
- 🧠 Focus areas: **backend systems**, **applied AI / local models**, and **resource efficiency**
- ⚡ Fun fact: I like learning new things and _estar parchao_

---

### 📌 Featured Projects

#### 📄 PDF-Engine — High-Performance Hybrid Document & OCR Engine

<p>
  <a href="https://github.com/4ndr3s-00/PDF-Engine"><img src="https://img.shields.io/badge/PDF--Engine-github-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/%240%2Fmo-100%25_Local_AI-22c55e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyMuPDF-C--Level-FF5722?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tesseract_OCR-Parallel-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Local_AI-Qwen_2.5-8B5CF6?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
</p>

> ⚡ **Performance:** ~3.4s for 8 complex mixed pages (receipts, orders & IDs)  
> 🔍 **Spatial Search:** < 4ms lookups with exact `[x0, y0, x1, y1]` bounding boxes  
> 🔒 **Privacy & Cost:** 100% on-premise execution, zero data leakage, $0 API bills

Industrial-grade document processing and search engine built for speed and complete cloud independence. Unifies digital text, parallel OCR, sub-millisecond spatial search, and local LLM extraction:

- **Smart Dual-Stream OCR:** Direct C-level text extraction with PyMuPDF; only scanned pages/images trigger parallel Tesseract workers. Digital pages are never rendered.
- **Faint Watermark & Logo Recovery:** High-pass local background subtraction filter (`NumPy` + `--psm 11`) to extract low-contrast headers, watermarks, and dot-matrix fonts that standard layout analyzers drop.
- **Spatial Word Index & Predictive Search (< 4 ms):** Maps exact bounding boxes for visual in-browser highlighting. Resolves matches across a 4-tier hierarchy: exact, prefix/autocomplete (`doc` ➔ `doctor`), internal substrings, and Levenshtein fuzzy fallback.
- **Compound Code & National ID Decomposition:** Breaks compound codes (`CO9CA0101-LOSARTAN` ➔ `losartan`) and indexes clean unpunctuated IDs (`1.043.589.150` ➔ `1043589150`) as well as MRZ barcode sequences with pixel coordinates.
- **Local AI Extraction with Guardrails:** Structured JSON schema extraction with Qwen 2.5 local via Ollama, featuring context pruning and an **anti-hallucination guard** (`null` with confidence 0 when no evidence exists).

**Why it exists:** Cloud vision APIs (AWS Textract, Azure Document AI) are expensive and leak sensitive customer documents, while heavy VLMs like LLaVA take minutes per page. PDF-Engine achieves enterprise accuracy and instant search on standard CPUs with zero running cost.

---

#### 🔥 freecode-zero — OpenCode 100% free

<p>
  <a href="https://github.com/4ndr3s-00/freecode-zero"><img src="https://img.shields.io/badge/freecode__zero-github-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/%240%2Fmo-%24100%25_FREE-22c55e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenCode-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

Ready-to-use **OpenCode setup at $0/month** — free AI models on the OpenCode Zen free tier, per-account backups (Google AI Studio + OpenRouter) that never run out at the same time, and a plugin that kills the *"retry zombie"* when a free provider saturates. No credit card needed.

`opencode.json` · `zen-guard.ts` (anti-429 plugin) · `setup.sh` · full free-tier guide

**Why it exists:** The Zen free tier runs out daily (per-IP quota). Instead of paying, it switches intelligently between complementary free tiers that never collide, keeping developer productivity unbroken.

---

#### 🧠 Mentia — Adaptive Learning Platform

<p>
  <a href="https://github.com/4ndr3s-00/mentia-learning-lab"><img src="https://img.shields.io/badge/Mentia-Adaptive_Learning_Platform-6D28D9?style=for-the-badge" /></a>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

Diagnoses learner profiles, recommends personalized learning methodologies, and measures pedagogical effectiveness through a **dynamic ranking and scoring system**. Features a rule-based classification engine, clean FastAPI backend, lightweight Vanilla JS SPA frontend, and PostgreSQL persistence.

**Why it exists:** Many projects introduce heavy, black-box Machine Learning models where simple, transparent logic is better. Mentia demonstrates that a deterministic, rule-based scoring engine is 10x faster, fully explainable, and vastly easier to audit.

---

#### 🗺️ What I'm Engineering Next

- **Distributed Queues & Background Processing:** Asynchronous document ingestion with Redis worker pools.
- **Hybrid Retrieval (Lexical + Vector):** Combining spatial word indexes with `pgvector` semantic embeddings.
- **Local Agentic Tool-Use:** Tool-calling pipelines orchestrating lightweight open-weight models locally.
- **Zero-Cost Developer Tooling:** Expanding the `freecode-zero` ecosystem for autonomous agents.

---

### 🛠️ Tech Stack & Tools

**Applied AI & Vision / Document Processing**

<p>
  <img src="https://img.shields.io/badge/Ollama-Local_Inference-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Qwen_2.5-SLM-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tesseract_OCR-5.x-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PyMuPDF-High_Performance-FF5722?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NumPy-Vectorized_Math-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pillow-Image_Ops-1f2937?style=for-the-badge" />
</p>

**Languages**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Backend & Data**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**DevOps, Environment & Automation**

<p>
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Hyprland-Wayland-00B0FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-Workflows-orange?style=for-the-badge&logo=n8n" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" alt="GitHub Stats" src="https://github-readme-stats-fast.vercel.app/api?username=4ndr3s-00&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=ffffff&text_color=cccccc&icon_color=ffffff" />
  &nbsp;
  <img height="165" alt="Top Languages" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=4ndr3s-00&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=ffffff&text_color=cccccc" />
</p>

---

<p align="center"><i>"Estar parchao, seguir aprendiendo, y construir cosas que funcionen."</i></p>
<p align="center"><code>&gt; EOF — thanks for visiting</code></p>
