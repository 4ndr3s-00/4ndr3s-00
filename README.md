
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

I'm a **Software Developer in training** at **RIWI**, focused on building real projects while sharpening my backend and frontend skills.

- 🔭 Built **PDF-Engine** — high-performance hybrid document processing & local AI extraction (< 3.5s per doc)
- 🚀 Created **freecode-zero** — run OpenCode 100% free, forever
- 👨🏫 And **Mentia** — adaptive learning platform with a rule-based ranking engine
- 🌱 Deepening my knowledge of **TypeScript, React and Node.js**
- 🐧 Daily driver: **Arch Linux + Hyprland**, fully customized
- 🧠 Focus areas: **backend development** and **applied AI**
- ⚡ Fun fact: I like learning new things and _estar parchao_

---

### 📌 Featured Projects

#### 📄 PDF-Engine — High-Performance Hybrid Document & OCR Engine

<p>
  <a href="https://github.com/estebanp26/PDF-Engine.git"><img src="https://img.shields.io/badge/PDF--Engine-github-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyMuPDF-C--Level-FF5722?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tesseract_OCR-Parallel-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Local_AI-Qwen_2.5-8B5CF6?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
</p>

Industrial-grade document processing and search engine built for **high speed and zero cloud costs ($0/mo, 100% on-premise privacy)**. Unifies digital text, parallel OCR, sub-millisecond spatial search, and local LLM extraction. Processes 8 mixed complex pages (thermal receipts, medical prescriptions, Colombian ID cards front & back) in **~3.4 seconds**.

- **Intelligent Dual-Stream OCR:** C-level digital parsing (PyMuPDF) + selective parallel OCR (Tesseract) with deduplication so digital pages are never rendered.
- **Watermark & Header Recovery:** High-pass local background subtraction filter (`NumPy` + `--psm 11`) to detect faint watermarks, logos, and dot-matrix fonts that standard layout analyzers drop.
- **Spatial Word Index & Predictive Search (< 4 ms):** Maps exact `[x0, y0, x1, y1]` coordinates for in-browser visual highlighting. Features 4-tier match hierarchy: exact, prefix/autocomplete (`doc` ➔ `doctor`), internal substrings, and Levenshtein fuzzy fallback.
- **Compound & ID Normalization:** Decomposes delimited medication codes (`CO9CA0101-LOSARTAN` ➔ `losartan`) and indexes clean unpunctuated national IDs (`1.043.589.150` ➔ `1043589150`) including MRZ barcode lines.
- **Pruned Context AI Extraction:** Qwen 2.5 via local Ollama for structured JSON and Q&A with an **anti-hallucination guard** (`null` with confidence 0 when no evidence is found).

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

**Why it exists:** the Zen free tier runs out daily (per-IP quota). Instead of paying, it switches intelligently between free tiers that never collide.

---

#### 🧠 Mentia — Adaptive Learning Platform

<p>
  <a href="https://github.com/4ndr3s-00/mentia-learning-lab"><img src="https://img.shields.io/badge/Mentia-Adaptive_Learning_Platform-6D28D9?style=for-the-badge" /></a>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

Diagnoses learner profiles, recommends personalized methodologies, and measures effectiveness through a **dynamic ranking system** — rule-based classification engine (no ML dependency), FastAPI backend, Vanilla JS SPA frontend, and PostgreSQL.

---

#### 🗺️ What I'm working on next

- Strengthening **TypeScript + React** on the frontend
- Pushing **FastAPI + PostgreSQL** backend patterns
- Automating workflows with **n8n** and **OpenCode**
- More free-tier tools in the style of freecode-zero

---

### 🛠️ Tech Stack & Tools

**Languages**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**Backend & Data**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

**DevOps & Tools**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCode-000000?style=for-the-badge&logo=terminal&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-Workflows-orange?style=for-the-badge&logo=n8n" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-Local_LLMs-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Tesseract_OCR-5.x-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/PyMuPDF-High_Performance-FF5722?style=for-the-badge" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" alt="Estadísticas de GitHub" src="https://github-readme-stats-fast.vercel.app/api?username=4ndr3s-00&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=ffffff&text_color=cccccc&icon_color=ffffff" />
  &nbsp;
  <img height="165" alt="Lenguajes más usados" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=4ndr3s-00&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=ffffff&text_color=cccccc" />
</p>

---

<p align="center"><i>"Estar parchao, seguir aprendiendo, y construir cosas que funcionen."</i></p>
<p align="center"><code>&gt; EOF — thanks for visiting</code></p>
