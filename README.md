<!--
  GitHub Profile README — put this file in a repo named exactly after your username
  (e.g.  github.com/L-Sangmin/L-Sangmin )  so it renders on your profile page.
  Remaining TODOs: your email, and the Scholar/LinkedIn links (remove any you don't use).
-->

<h1 align="center">Hi, I'm Sangmin Lee 👋</h1>

<p align="center">
  <b>Computational biology · protein structure prediction · protein language models</b><br>
  Undergraduate @ <a href="https://www.kaist.ac.kr/en/">KAIST</a> — Bio &amp; Brain Engineering + School of Computing (double major)<br>
  Individual study @ <b>BCBL</b> (Bioinformatics &amp; Computational Biology Lab) · Daejeon, South Korea 🇰🇷
</p>

---

### 🧬 About me

I work at the boundary between **structural biology** and **machine learning**. My day-to-day sits in four connected threads:

- **Structure prediction & evaluation** — rigorously testing modern folding/docking models (AlphaFold-family systems, open reproductions) on hard, leakage-controlled cases, with a focus on *when and why they fail* rather than just headline accuracy.
- **Bio-tooling on Apple Silicon** - porting structure prediction and design tools to MLX so they run natively on ordinary Macs, with verification harnesses that hold ported outputs to reference implementations rather than trusting them.
- **LLMs & agents for computational biology** — using language models and agentic workflows to generalize traditionally narrow bio/chem tasks (molecule optimization, drug discovery, protein reasoning), and building benchmarks/tooling that make these systems measurable.
- **General-purpose but practical AI/LLM applications** — using frontier models to build software that solves real problems, and to automate the repetitive parts of everyday work. It's how I build a working sense of where AI actually gives leverage.

Most of my current work sits in that fourth thread — shipping is the fastest way to learn where these models actually hold up, and that instinct is exactly what the first two need. Longer term I'm most excited about **developing capable protein language models (pLMs)** and the evaluation methodology that keeps them honest.

```python
sangmin = {
    "affiliation":  "KAIST — Bio & Brain Engineering × School of Computing",
    "lab":          "BCBL (Bioinformatics & Computational Biology Lab)",
    "focus":        ["structure prediction", "protein language models", "LLM/agents for bio"],
    "toolbelt":     ["Python", "MATLAB", "F#", "Git", "data viz"],
    "paths_open":   ["academia", "industry / startup"],
    "currently":    "building research tooling + reading a lot of preprints critically",
}
```

---

### 🚀 Shipped

#### 📝 MakeItMarkdown &nbsp;—&nbsp; [🌐 live](https://makeitmarkdown.pages.dev) · [source](https://github.com/L-Sangmin/makeitmarkdown)
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PWA-offline--first-5A0FC8?style=flat&logo=pwa&logoColor=white" alt="PWA"/>
  <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat" alt="MIT"/>
</p>

> **Feed your LLM better.** A free, browser-only *context workbench* that converts **15 technical document formats** (`.ipynb`, `.docx`, `.pptx`, `.xlsx`, `.pdf`, `.tex`, `.eml`, `.srt`, …) into **LLM-ready Markdown** — and hands back a fidelity report of exactly what the parser detected, recovered, and lost.

Not a file converter but a **trust view**: original preview · converted Markdown · a weighted QC score (8 structural checks). Five output presets — Standard / Chat / **RAG** (chunk anchors) / **Obsidian** (callouts, wikilinks, frontmatter) / Archive — with real `o200k` token counting. **100% client-side**: files never leave the browser, the tool runs fully offline via service worker, and nothing persists on refresh.

<sub>Stack: vanilla JS (no build step, vendored libs) · Node <code>--test</code> (101 tests) · Cloudflare Pages · PWA · MIT</sub>

#### 🐠 FPD Manual Generator &nbsp;—&nbsp; [🌐 live](https://fpdmanualgenerator.pages.dev) · source `🔒 private`
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Paged.js-print--CSS-F5A830?style=flat" alt="Paged.js"/>
  <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages"/>
  <img src="https://img.shields.io/badge/client--side-only-5A0FC8?style=flat" alt="client-side only"/>
</p>

> **A print shop in a browser tab.** Fill in the values that change each year and get **four finished manuals** — freshman and advisory-group editions, in Korean and English — typeset to a 180×220mm trim and saved as a real vector PDF.

Built for the **KAIST School of Freshman**, where I was head of the 16th Freshman Program Designers. Rosters (`.xlsx`) and face photos (`.zip`) are parsed in the browser and composed on a 300dpi stage; page count flows with the roster. Nothing is uploaded — which is the whole point, since the input is real students' names, contacts, and faces. The site is public; the repository stays private for the same reason.

<sub>Stack: vanilla JS (no build step) · Paged.js · Playwright render harness · Cloudflare Pages</sub>

---

### 🔬 Research — in progress

Work from my individual study at **BCBL@KAIST**. The code below lives in private or local-only repos for now — I open-source pieces as they mature and as the work reaches publication.

- **AF3 evaluation for antibody / nanobody complexes** — assessing structure- and interaction-prediction quality on hard, leakage-controlled cases, with **multi-seed inference** and confidence-vs-accuracy analysis, on a self-hosted AlphaFold3 server + Protenix.
  <br><sub>Python · Docker · structural-bio data</sub>
- **Research knowledge-graph pipeline** &nbsp;`🚧 in development` — automated paper ingestion into a linked, queryable graph of my reading; runs a local LLM + the Gemini API. Goes public once it's mature. <br><sub>Python · Markdown / Obsidian · agent tooling</sub>
- **Vaccine MCP** &nbsp;`🔒 private` — Model-Context-Protocol tooling for vaccine-related workflows; a collaborative project. <br><sub>Python · MCP</sub>

<!-- Add public repos here as you open-source them. -->

---

### 🛠️ Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/F%23-378BBA?style=flat&logo=fsharp&logoColor=white" alt="F#"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
</p>
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <!-- TODO: trim any of the above you don't actually use; add e.g. Rosetta, RDKit, Linux, LaTeX -->
</p>

---

<p align="center"><sub>
  "All models are wrong, but some are useful." — and knowing <i>which</i> is the whole job.
</sub></p>
