<h1>Hi, I’m Juan Martinez — <a href="https://github.com/josejuanmartinez">@josejuanmartinez</a></h1>

**AI engineer and game developer.** ex-FRVR, ex-Fortis Games, now building casual viral
games at a small studio — art, code and gameplay AI. Before games I spent most of my career
in NLP and data science.

### 🏛️ [Portfolio → josejuanmartinez.github.io](https://josejuanmartinez.github.io/)

Gameplay reels, the projects below with diagrams, and every public repository in one place.

---

## 🦝 Possum Archaeologists — what I work on day to day

[![Possum Archaeologists](https://josejuanmartinez.github.io/assets/possumarch-banner.jpg)](https://josejuanmartinez.github.io/#studio)

Two possum archaeologists have excavated a junkyard and are entirely convinced they have
found priceless ancient relics. It is a rubber duck. It is a broken flip phone. They do not
care — every piece of rubbish is solemnly catalogued under its museum name, and a bottle cap
becomes the Crown of the Fizz King.

Underneath the joke it is a tile-pile matcher: only uncovered relics can be tapped, three of
a kind clear, and the seven-slot tray never gets any bigger. Dig sites are generated, so every
run is a different shape and depth, and **Today's Trench** is one date-seeded dig shared by
every player in the world that day.

- **77KB of gzipped JavaScript** for the entire game — engine, interface and all. No Unity,
  no three.js, no Phaser: raw WebGL and TypeScript on Bun.
- **One draw call for most frames.** Sprites, particles and the whole UI share a single
  texture atlas and a single batch.
- **A skinned-mesh renderer written from scratch**, so the mascot is a real rigged 3D
  character standing over a 2D board — 334KB for eleven animations, where baked sprite sheets
  cost 574KB for one.
- **A cheap Android phone is the floor**: 60fps target, zero allocations in the frame loop,
  and a second shading path for GPUs that refuse the fast one.
- **Live from day one:** weekly tournaments, a daily leaderboard, cloud saves, remote
  difficulty tuning and churn funnels.
- **Built by an agentic pipeline** — a concept artist sets the direction, a technical artist
  generates sprites and drives image-to-3D character generation and rigging, an audio agent
  writes the SFX and voice lines, a marketing agent captures gameplay and builds the store
  set. Each on a least-privilege tool allowlist, each cost-gated before it may spend a cent,
  and none of them allowed to call the work done — a read-only verifier does that.

> It is a closed-source studio project, so there is no repository to link.
> [Screenshots and a real gameplay reel are on the portfolio ↗](https://josejuanmartinez.github.io/#studio)

---

## 🎮 Games & gameplay AI

| | |
|---|---|
| [**Runeboard**](https://josejuanmartinez.github.io/Runeboard/) | Strategy + card game handcrafted to showcase art, gameplay and AI. There is a full dev diary. |
| [**videogamesAI**](https://github.com/josejuanmartinez/videogamesAI) | C++ and C# projects on video-game AI — pathfinding, decision making, NPC behaviour. |
| [**NazgulsUnleashed**](https://github.com/josejuanmartinez/NazgulsUnleashed) | *The Realm of the Long Rider*, a submod for Realms in Exile (Crusader Kings III). |

## 🧠 AI & creative tools

| | |
|---|---|
| [**mindcraft**](https://github.com/josejuanmartinez/mindcraft) | Open-source NLP engine for crafting the minds of video-game NPCs. |
| [**concept-art-generator**](https://github.com/josejuanmartinez/concept-art-generator) | Agentic concept-art generation for creative workflows. |
| [**qwen-image-lora-studio**](https://github.com/josejuanmartinez/qwen-image-lora-studio) | LoRA training and inference studio for Qwen Image. |
| [**FLUX-1-dev**](https://github.com/josejuanmartinez/FLUX-1-dev) | Hugging Face Space for training QLoRA on FLUX.1-dev. |

## 📊 NLP, data & open source

| | |
|---|---|
| [**Finance NLP**](https://www.johnsnowlabs.com/finance-nlp/) · [**Legal NLP**](https://www.johnsnowlabs.com/legal-nlp/) | Built from scratch at [John Snow Labs](https://www.johnsnowlabs.com/), creators of [Spark NLP](https://www.johnsnowlabs.com/spark-nlp/). |
| [**TeaNLP**](https://github.com/josejuanmartinez/TeaNLP) | Transform, Extract, Analyze — NLP graphs. ([front](https://github.com/josejuanmartinez/TeaNLP-front)) |
| [**documentqa**](https://github.com/josejuanmartinez/documentqa_back) | Document question answering with vector stores, LangChain and LLMs. ([front](https://github.com/josejuanmartinez/documentqa_front)) |
| [**libreCatastro**](https://github.com/josejuanmartinez/libreCatastro) | Open platform for querying the Spanish official cadastral registry. |
| [**toxicity_es_transformers_shap**](https://github.com/josejuanmartinez/toxicity_es_transformers_shap) | XLM-RoBERTa toxicity classifier with SHAP interpretability and Optuna search. |

---

### 📚 Background

Five years of software engineering, four of linguistics, an MBA in educational-institution
management, and a master's in video-game development (C#, C++, Unity, Unreal).
I speak Spanish, Russian, English and some Portuguese.

### 📫 Find me

[Portfolio](https://josejuanmartinez.github.io/) ·
[LinkedIn](https://www.linkedin.com/in/jjmcarrascosa) ·
[GitHub](https://github.com/josejuanmartinez)

<!---
josejuanmartinez/josejuanmartinez is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
