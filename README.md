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

<p align="center">
  <a href="mailto:lsm030406@kaist.ac.kr"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <!-- TODO: add / remove links below as they apply -->
  <a href="https://www.linkedin.com/in/sangmin-lee-351b9a348"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### 🧬 About me

I work at the boundary between **structural biology** and **machine learning**. My day-to-day sits
in two connected threads:

- **Structure prediction & evaluation** — rigorously testing modern folding/docking models
  (AlphaFold-family systems, open reproductions) on hard, leakage-controlled cases, with a focus
  on *when and why they fail* rather than just headline accuracy.
- **LLMs & agents for computational biology** — using language models and agentic workflows to
  generalize traditionally narrow bio/chem tasks (molecule optimization, drug discovery, protein
  reasoning), and building benchmarks/tooling that make these systems measurable.

Longer term I'm most excited about **developing capable protein language models (pLMs)** and the
evaluation methodology that keeps them honest.

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

### 🚀 Featured projects

#### 📝 MakeItMarkdown &nbsp;—&nbsp; [🌐 live](https://makeitmarkdown.pages.dev) · [source](https://github.com/L-Sangmin/makeitmarkdown)
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PWA-offline--first-5A0FC8?style=flat&logo=pwa&logoColor=white" alt="PWA"/>
  <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat&logo=cloudflarepages&logoColor=white" alt="Cloudflare Pages"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat" alt="MIT"/>
</p>

> **Feed your LLM better.** A free, browser-only *context workbench* that converts **15 technical
> document formats** (`.ipynb`, `.docx`, `.pptx`, `.xlsx`, `.pdf`, `.tex`, `.eml`, `.srt`, …) into
> **LLM-ready Markdown** — and hands back a fidelity report of exactly what the parser detected,
> recovered, and lost.

Not a file converter but a **trust view**: original preview · converted Markdown · a weighted QC
score (8 structural checks). Five output presets — Standard / Chat / **RAG** (chunk anchors) /
**Obsidian** (callouts, wikilinks, frontmatter) / Archive — with real `o200k` token counting.
**100% client-side**: files never leave the browser, the tool runs fully offline via service
worker, and nothing persists on refresh.

<sub>Stack: vanilla JS (no build step, vendored libs) · Node <code>--test</code> (101 tests) · Cloudflare Pages · PWA · MIT</sub>

#### 🔬 Structure-prediction evaluation toolkit
Experimental pipeline for evaluating folding/docking models on antibody–antigen and
nanobody–antigen complexes, including **multi-seed inference** and confidence-vs-accuracy analysis.
Runs against both a hosted prediction server and an open-source reproduction.
<sub>Stack: Python · Docker · structural-bio data wrangling</sub>

#### 🕸️ Research knowledge-graph pipeline ("research wiki")
An automated pipeline that ingests papers and builds a linked, queryable knowledge graph of my
reading — designed for clean handoff to coding agents and idempotent re-runs.
<sub>Stack: Python · Markdown/Obsidian · agent tooling</sub>

#### 💉 Vaccine MCP
An ongoing project exploring Model-Context-Protocol tooling applied to vaccine-related workflows.
<sub>Stack: Python · MCP</sub>

<!-- Add more repos here as you open-source them. -->

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

### 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=L-Sangmin&show_icons=true&hide_border=true&count_private=true" alt="stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=L-Sangmin&layout=compact&hide_border=true&langs_count=8" alt="top langs" height="165"/>
</p>

---

<p align="center"><sub>
  "All models are wrong, but some are useful." — and knowing <i>which</i> is the whole job.
</sub></p>
