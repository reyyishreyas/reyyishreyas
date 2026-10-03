<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/hero-light.svg">
  <img src="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/hero-dark.svg" alt="Reyyi Shreyas. AI/ML engineer, researcher, open source. Portrait rendered as ASCII characters generated from a photo." width="100%">
</picture>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=900&color=71717A&vCenter=true&width=860&height=55&lines=Open-source+contributor+to+nilearn%2C+PCNtoolkit+and+movement.;ML+path%3A+data+%E2%86%92+modeling+%E2%86%92+evaluation+%E2%86%92+systems.;Deep+learning%2C+ensembles%2C+agentic+LLM+systems." alt="Open-source contributor to nilearn, PCNtoolkit and movement. ML path: data to modeling to evaluation to systems. Deep learning, ensembles, agentic LLM systems." width="860">

<br/>

<a href="https://github.com/reyyishreyas"><img src="https://img.shields.io/badge/GitHub-262626?style=flat-square&logo=github&logoColor=e4e4e7" alt="GitHub"></a>&nbsp;&nbsp;<a href="https://www.linkedin.com/in/reyyi-shreyas/"><img src="https://img.shields.io/badge/LinkedIn-262626?style=flat-square&logo=linkedin&logoColor=e4e4e7" alt="LinkedIn"></a>&nbsp;&nbsp;<a href="mailto:reyyishreyas@gmail.com"><img src="https://img.shields.io/badge/Email-262626?style=flat-square&logo=gmail&logoColor=e4e4e7" alt="Email"></a>

---

**ML engineer working the full path: raw data → modeling → evaluation → systems.**

Most of what I learn happens in public: recent documentation and contributor work for **nilearn**, **PCNtoolkit** and **movement**, plus applied projects in deep learning, ensemble methods and agentic LLM systems.

I'd rather read the source than trust the demo.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/status-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/status-light.svg">
  <img src="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/main/assets/status-dark.svg" alt="Status panel: 244 commits, 17 pull requests, 11 repositories contributed to, 305 contribution days. Snapshot October 2026." width="100%">
</picture>

---

## Currently

- Researching lightweight hallucination detection for quantized small LMs
- Building and evaluating agentic LLM systems
- Contributing to open-source scientific Python projects
- Exploring efficient ML systems and evaluation

---

## Open source contributions

| Repository | Contribution | Status |
|:--|:--|:--:|
| [**nilearn** #6614](https://github.com/nilearn/nilearn/pull/6614) | Fixed the decoder training message being logged multiple times per `fit` | ![](https://img.shields.io/badge/MERGED-16a34a?style=flat-square) |
| [**nilearn** #6597](https://github.com/nilearn/nilearn/pull/6597) | Fixed stale `standardize` docs across the user guide and docstrings; added a gallery example | ![](https://img.shields.io/badge/MERGED-16a34a?style=flat-square) |
| [**PCNtoolkit** #551](https://github.com/predictive-clinical-neuroscience/PCNtoolkit/pull/551) | Documented `basis_column`, `nknots` and `degree` in the HBR normative-modelling tutorial | ![](https://img.shields.io/badge/MERGED-16a34a?style=flat-square) |
| [**movement** #1115](https://github.com/neuroinformatics-unit/movement/pull/1115) | Added the IO-guide update step to the *"Implementing new loaders & writers"* guide | ![](https://img.shields.io/badge/MERGED-16a34a?style=flat-square) |

<sub>Selected open pull requests under review: PCNtoolkit #563, movement #1125 and #1127, artem-is #164 and #165, mcp-mifosx #522, mcp-mifosx-self-service #43 and #44, sentiment module #14.</sub>

---

## Research

### Lightweight Retrieval-Grounded Hallucination Detection

Researching a lightweight hallucination detection pipeline for quantized small language models using retrieval grounding, embedding-overlap signals and generation confidence.

The system performs sentence-level detection using a lightweight classifier and evaluates the trade-offs between **FP16, 8-bit and 4-bit quantization** across detection quality, hallucination rate, latency and GPU memory.

`LLMs` `RAG` `Quantization` `Hallucination Detection` `Evaluation`

**Status:** Preparing submissions to research conferences

---

## Selected work

<table>
<tr>

<td width="50%" valign="top">

**ChessMind AI**

Adaptive chess trainer using a two-model shared-memory architecture: a suggester LLM reasons over the position while a feedback LLM coaches from verified engine facts.

Reduced first-feedback latency from **7.6s → 1.7s** while keeping generation grounded in verified engine analysis. Includes a per-move Elo ensemble and reproducible evaluation harness.

`LLM Agents` `Ensembles` `Evaluation`

<a href="https://github.com/reyyishreyas/ChessMind_AI">VIEW REPOSITORY →</a>

</td>
<td width="50%" valign="top">

**Research Paper Analyst** <a href="https://research-agent-rag.streamlit.app/"><img src="https://img.shields.io/badge/LIVE-0d9488?style=flat-square" alt="Live demo"></a>

Agentic RAG that autonomously chooses between retrieval, summarization and comparison tools over a paper corpus, with grounded, source-cited answers.

`LangChain` `Gemini` `FAISS`

<a href="https://github.com/reyyishreyas/research-agent-rag">VIEW REPOSITORY →</a>

</td>

</tr>
<tr>

<td width="50%" valign="top">

**Lunar image registration**

Sub-pixel registration of Chandrayaan-2 imagery to LRO NAC using SIFT correspondence and RANSAC, with a 7-module super-resolution pipeline ([isro_1m](https://github.com/reyyishreyas/isro_1m)) for hazard mapping.

`OpenCV` `RANSAC` `Super-resolution`

<a href="https://github.com/reyyishreyas/lunar-image-registration">VIEW REPOSITORY →</a>

</td>
<td width="50%" valign="top">

**Astra Chronos AI**

A 2-layer GRU predicts UAV trajectories from flight history; predictions drive threat scoring and autonomous interceptor guidance in a real-time 3D simulator.

`PyTorch` `GRU` `3D Simulation`

<a href="https://github.com/reyyishreyas/Astra-chronus-ai-">VIEW REPOSITORY →</a>

</td>

</tr>
<tr>

<td width="50%" valign="top">

**TRICP** <a href="https://churn-predictor-kappa.vercel.app"><img src="https://img.shields.io/badge/LIVE-0d9488?style=flat-square" alt="Live demo"></a>

Stacking-ensemble churn prediction that surfaces the factors behind each prediction, then triggers personalized retention workflows automatically.

`XGBoost` `LightGBM` `Explainability`

<a href="https://github.com/reyyishreyas/TRICP">VIEW REPOSITORY →</a>

</td>
<td width="50%" valign="top"></td>

</tr>
</table>

---

## Experience & leadership

**ASTRA — President**
BMSIT&M's defence-technology student organization. Leading technical, research, recruitment and cross-team initiatives.

**ML Intern — Launched Global**
Worked on machine-learning applications and applied AI workflows.

**Open-source contributor**
Contributed documentation, bug fixes and tooling improvements across scientific Python and open-source ML projects.

---

## Tech stack

<table>
<tr>
<td width="24%" valign="top"><b>LANGUAGES</b></td>
<td><code>Python</code></td>
</tr>

<tr>
<td valign="top"><b>ML / DEEP LEARNING</b></td>
<td><code>PyTorch</code> | <code>scikit-learn</code> | <code>XGBoost</code> | <code>LightGBM</code> | <code>OpenCV</code></td>
</tr>

<tr>
<td valign="top"><b>LLM / RETRIEVAL</b></td>
<td><code>Transformers</code> | <code>LangGraph</code> | <code>LangChain</code> | <code>FAISS</code></td>
</tr>

<tr>
<td valign="top"><b>ENGINEERING</b></td>
<td><code>FastAPI</code> | <code>Flask</code> | <code>Streamlit</code> | <code>Docker</code> | <code>Git</code></td>
</tr>

<tr>
<td valign="top"><b>DATA</b></td>
<td><code>NumPy</code> | <code>pandas</code></td>
</tr>
</table>

---

## How I work

**Understand → Experiment → Break → Ship.** Read the implementation, understand the assumptions, build alternatives, measure what changes, test where systems fail, then turn what survives into something usable.

> **A model that works in a notebook is an experiment.**
>
> **A model that survives evaluation, integration and real usage is a system.**

---

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/output/github-snake-light.svg">
  <img src="https://raw.githubusercontent.com/reyyishreyas/reyyishreyas/output/github-snake-dark.svg" alt="Contribution snake animation" width="100%">
</picture>

---

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=15&duration=3500&pause=1200&color=71717A&vCenter=true&width=700&height=40&lines=Build+the+model.;Understand+the+system.;Test+the+assumptions.;Ship+what+survives." alt="Build the model. Understand the system. Test the assumptions. Ship what survives." width="700">

<br/>

<sub>AI/ML | Research | Open Source</sub>
