<!--
  ░░ surajmeruva0786 ░░ "The Glass Box" profile
  Bespoke animated SVGs live in /assets and render after the first push to main.
  Light/dark adaptive via <picture>. Stat cards use community mirrors (canonical URLs kept in comments).
-->

<div align="center">

<!-- ══════════════ ANIMATED HEADER (hand-coded · light + dark) ══════════════ -->
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/header-light.svg">
  <img src="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/header-dark.svg" width="100%" alt="Suraj Meruva — Explainable AI · Applied ML · Full-Stack Systems">
</picture>

<!-- ══════════════ STATUS TICKER ══════════════ -->
<a href="https://github.com/surajmeruva0786">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&pause=1000&color=22D3EE&center=true&vCenter=true&width=720&height=34&lines=%24+suraj+--now+%E2%86%92+patent-pending+OCR+confidence+engine;%24+suraj+--exploring+%E2%86%92+multi-agent+systems+%26+LLM+red-teaming;%24+suraj+--ask-me+%E2%86%92+explainable+AI+%26+applied+ML;%24+suraj+--mission+%E2%86%92+turn+black-box+models+into+glass+boxes" alt="status" />
</a>

<!-- ══════════════ CONTROL PANEL (links + honest stats) ══════════════ -->
<p>
  <a href="https://github.com/surajmeruva0786"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=22D3EE" /></a>
  <a href="https://www.linkedin.com/in/suraj-meruva/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=38BDF8" /></a>
  <a href="https://www.kaggle.com/meruvakodandasuraj"><img src="https://img.shields.io/badge/Kaggle-0D1117?style=for-the-badge&logo=kaggle&logoColor=20BEFF" /></a>
  <a href="https://x.com/SurajMeruva786"><img src="https://img.shields.io/badge/X-0D1117?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="mailto:meruva24102@iiitnr.edu.in"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" /></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=surajmeruva0786&style=flat-square&color=22D3EE&label=ORBIT+VISITS" />
  <img src="https://img.shields.io/badge/DSAI-IIIT_Naya_Raipur_'28-818CF8?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/focus-Explainable_AI-22D3EE?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/mission_domains-7-38BDF8?style=flat-square&labelColor=0D1117" />
</p>

</div>

---

## `// 00 · MANIFEST`

```yaml
# ~/.config/suraj.yaml
identity:
  name:   Suraj Meruva
  alias:  meruvakodandasuraj                       # kaggle
  role:   AI/ML Engineer · Researcher · Full-Stack Developer
  base:   IIIT Naya Raipur — B.Tech, Data Science & AI (2024 → 2028)

thesis: >
  I don't ship black boxes. Every model I build explains itself —
  SHAP, Grad-CAM, confidence maps — because high-stakes domains
  can't trust what they can't audit.

building:
  applied_ml:  [ biomedical-signals(ECG·PPG·EEG), predictive-maintenance(RUL), sonar/vibration ]
  llm_agents:  [ multi-agent-systems, PEFT/LoRA, RAG, document-intelligence(OCR) ]
  full_stack:  [ react, next.js, fastapi, "kafka · timescaledb · redis" ]

domains:  [ defence(DRDO), energy(NTPC), naval(NSTL), law-enforcement, govtech, fintech, healthtech ]
now:      "patent-pending OCR confidence engine (FileTract) + multi-agent quant finance (UMQ-Agent)"
open_to:  "AI/ML research & SWE internships · open-source · collaborations"
```

---

## `// 01 · THE METHOD`

Most ML ships a number and asks you to trust it. I build the opposite: pipelines where **every prediction arrives with its receipts** — *which* feature, *which* frequency band, *which* pixel drove the call. That feedback loop doesn't just explain the model, it **audits and patches** it.

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'JetBrains Mono, monospace','lineColor':'#6D5DF6','primaryColor':'#0D1117','primaryTextColor':'#E5ECF4','primaryBorderColor':'#22D3EE'}}}%%
flowchart LR
    A([📡 Raw Signals + Docs]):::in --> B[🧠 Applied ML / DL]:::ml
    B --> C{{🔍 Explainability Layer<br/>SHAP · Grad-CAM · Confidence}}:::xai
    C --> D[🪟 Glass-Box Decision]:::out
    D --> E([🎯 High-Stakes Domains]):::dom
    C -. audit + patch .-> B
    classDef in  fill:#0B1620,stroke:#22D3EE,color:#CDE9F2;
    classDef ml  fill:#0E1A12,stroke:#34D399,color:#D6F2E4;
    classDef xai fill:#15111F,stroke:#818CF8,color:#E2DEF8,font-weight:bold;
    classDef out fill:#101A26,stroke:#38BDF8,color:#D8EEFB;
    classDef dom fill:#1A1320,stroke:#F472B6,color:#F6DCEC;
```

---

## `// 02 · FIELD NOTES`

*Selected builds — most ship with explainability wired in.*

#### 🪟 &nbsp;FileTract · *self-auditing OCR engine*
> Turns degraded scans into structured data, then **scores its own certainty** field-by-field — and re-reads only the regions it doubts.
>
> `Python` · `OCR` · `Computer Vision` · `Patent-pending`
> &nbsp;🔍 **Explains →** per-field confidence maps · adaptive re-OCR · confidence-weighted fusion

#### 🧠 &nbsp;AeroMind · *EEG cognitive-fatigue radar*
> Reads an operator's brainwaves in real time to flag fatigue **before** it gets dangerous — built for pilots, drone operators & submariners *(DRDO / DIPAS domain)*.
>
> `PyTorch` · `MNE-Python` · `CapsuleNet + LSTM` · `XAI`
> &nbsp;🔍 **Explains →** SHAP attributions painted onto a 2D scalp topography

#### 📈 &nbsp;UMQ-Agent · *multi-agent quant-finance platform*
> Autonomous agents stream live markets and surface **risk & fraud** in real time, on a clean microservice backbone.
>
> `Python` · `Multi-Agent` · `Kafka` · `TimescaleDB` · `Redis` · `React`
> &nbsp;🔍 **Explains →** traceable agent decisions + live monitoring dashboard

#### 🪪 &nbsp;CSC Sahayak · *AI co-pilot for India's service centres* &nbsp;`⭐ most-forked`
> A Chrome extension + desktop app that auto-fills government portals and cuts citizen application rejections — **bilingually**.
>
> `TypeScript` · `Python` · `LLM` · `Document-AI`
> &nbsp;🔍 **Explains →** extraction backed by FileTract's confidence scoring

<details>
<summary><b>&nbsp;▸ &nbsp;more builds in the hangar</b></summary>

<br/>

| Project | Domain | What it does |
|---|---|---|
| **TurboGuard** | ⚡ Energy *(NTPC)* | Vibration-based predictive maintenance + Remaining-Useful-Life, SHAP-explained |
| **HydroSense** | 🌊 Naval *(NSTL)* | Explainable passive-sonar vessel classification (Grad-CAM + SHAP) |
| **CG Police** | 👮 Law Enforcement | Deepfake detection + malicious-URL + cyber-intel platform |
| **XAI-DBMS** | 🗄️ Data | LLM-powered ML workbench with transparent, auditable predictions |
| **PEFT Research** | 🧪 LLM | Cross-domain transfer (medical ↔ legal) at 95%+ fewer trained params |
| **ECG/PPG** | 🫀 HealthTech | Heart-attack prediction from physiological signals |
| **Jungle Safari** | 🐯 Orbis Systems | Official website + mobile app for Jungle Safari, Naya Raipur |
| **nanoGPT** | 🧠 Foundations | A GPT built from scratch, the Karpathy way |

</details>

---

## `// 03 · MISSION DOMAINS`

<div align="center">

| Domain | Build | Real-world stake |
|:--|:--|:--|
| 🛡️ **Defence — Aircrew** | `AeroMind` | Catch cognitive fatigue before a fatal mistake |
| ⚡ **Energy — Power Plants** | `TurboGuard` | Predict machine failure before it happens |
| 🌊 **Naval — Acoustics** | `HydroSense` | Identify vessels from underwater sound |
| 👮 **Law Enforcement** | `CG Police` | Fight deepfakes & cybercrime at scale |
| 🏛️ **GovTech — Citizens** | `CSC Sahayak` | Fewer rejected applications, faster service |
| 💸 **FinTech — Markets** | `UMQ-Agent` | Real-time risk & fraud intelligence |
| 🫀 **HealthTech — Signals** | `ECG/PPG` | Earlier warning from heart signals |

</div>

---

## `// 04 · INSTRUMENTS`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,fastapi,react,nextjs,ts,nodejs,tailwind,docker,kafka,redis,postgres,mongodb,git,vscode,figma,vercel&theme=dark&perline=10">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,fastapi,react,nextjs,ts,nodejs,tailwind,docker,kafka,redis,postgres,mongodb,git,vscode,figma,vercel&theme=light&perline=10">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv,fastapi,react,nextjs,ts,nodejs,tailwind,docker,kafka,redis,postgres,mongodb,git,vscode,figma,vercel&theme=dark&perline=10" alt="tech stack" />
</picture>

<sub>**+ explainability:** SHAP · Grad-CAM · LIME &nbsp;|&nbsp; **+ LLM/agents:** Hugging Face · LangChain · PEFT/LoRA &nbsp;|&nbsp; **+ data:** Pandas · NumPy · SciPy</sub>

</div>

---

## `// 05 · TELEMETRY`

<div align="center">

<!-- canonical (use when up): https://github-readme-stats.vercel.app/api?username=surajmeruva0786 -->
<img height="170" src="https://github-readme-stats-sigma-five.vercel.app/api?username=surajmeruva0786&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=22D3EE&icon_color=818CF8&text_color=9FB1C4&bg_color=0D1117" />
<img height="170" src="https://streak-stats.demolab.com/?user=surajmeruva0786&theme=tokyonight&hide_border=true&background=0D1117&ring=22D3EE&fire=818CF8&currStreakLabel=22D3EE&sideLabels=9FB1C4&dates=64748B" />

<br/>

<!-- canonical (use when up): https://github-readme-stats.vercel.app/api/top-langs/?username=surajmeruva0786 -->
<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=surajmeruva0786&layout=compact&langs_count=8&hide_border=true&title_color=22D3EE&text_color=9FB1C4&bg_color=0D1117&hide=jupyter%20notebook" width="46%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=surajmeruva0786&theme=react-dark&bg_color=0D1117&hide_border=true&area=true&color=22D3EE&line=818CF8&point=FFFFFF&custom_title=Contribution%20Orbit" width="100%" />

</div>

---

## `// 06 · TRAJECTORY`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/output/github-contribution-grid-snake.svg">
  <img src="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/output/github-contribution-grid-snake-dark.svg" width="100%" alt="contribution snake" />
</picture>

<img src="https://ghchart.rshah.org/22D3EE/surajmeruva0786" alt="contribution heatmap" width="100%" />

</div>

---

## `// 07 · UPLINK`

<div align="center">

I publish datasets, research notebooks & ML-competition work on **Kaggle**, and I'm always up for a good problem in explainable / applied AI.

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="quote" />

<p>
  <a href="https://www.linkedin.com/in/suraj-meruva/"><img src="https://img.shields.io/badge/Let's_connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.kaggle.com/meruvakodandasuraj"><img src="https://img.shields.io/badge/Notebooks-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" /></a>
  <a href="mailto:meruva24102@iiitnr.edu.in"><img src="https://img.shields.io/badge/Reach_out-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>

<!-- ══════════════ ANIMATED FOOTER (hand-coded · light + dark) ══════════════ -->
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/footer-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/footer-light.svg">
  <img src="https://raw.githubusercontent.com/surajmeruva0786/surajmeruva0786/main/assets/footer-dark.svg" width="100%" alt="Let's build AI that explains itself">
</picture>
</div>
