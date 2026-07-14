# Hi, I'm Bakul

- 🎓 UVA Darden '27
- 🛠️ Building for fun + real-world use cases in ai x bio/longevity, ai x blockchain, VC and PE, AI-native services, e-learning, etc.

## Projects

### AI × Blockchain

**[Tranche AI](https://github.com/bakulbadwal/tranche-ai)** — condition-gated capital release for VC deals: an AI agent reviews milestone evidence and posts a signed, on-chain attestation (EAS). Solidity, live on Base Sepolia network.<br>
> [Live →](https://tranche-ai.vercel.app)

**[TraceHound](https://github.com/bakulbadwal/tracehound)** — agentic on-chain crypto hack tracer: live hop-by-hop tracing from compromised wallet via the Etherscan API, cross-references an OFAC watchlist populated with real, current sanctioned addresses pulled from Treasury's SDN list, LLM narration, and a drafted demand letter. Built from direct experience with FBI & U.S. Secret Service on a personal hack + tracking/referring $6M of crypto crime.<br>
> [Live →](https://tracehound.vercel.app)

### AI × Bio/Longevity

**LiveForever** *(live, private health control tower)* — personal longevity engine that unifies Oura Ring, Apple Health, Nori, 10+ years of clinical bloodwork and daily self-logged inputs into one owned data layer.

Then, computes a **PhenoAge** biological-age clock tracked from blood panels since 2015, benchmarks against Bryan Johnson's public Blueprint targets and age/sex population cohorts, runs an N-of-1 correlation engine quantifying what each input (nootropics, biohacking, fitness, sleep, medication, etc.) actually does to next-day HRV, recovery, resilience scores, plus a 28-day before/after analysis on any intervention.

Cross-referenced against my own DNA from 23andMe (caffeine/dopamine pharmacogenomics, APOE and metabolic-risk variants) so the guidance is genetically personalized. Daily auto-refresh via MCP + REST APIs.

**[PhaseSignal](https://github.com/bakulbadwal/phasesignal)** — pulls real, live trial data from the ClinicalTrials.gov API and scores each one against a cited published base rate, adjusted by four computed factors with a full live-reweighting breakdown.<br>
> [Live →](https://bakulbadwal.github.io/phasesignal/)

### AI × VC & PE

**[Deal Docket](https://github.com/bakulbadwal/dealdocket)** — deal-screening dashboard built around an AI-enabled service-roll-up thesis, with a five-box scoring framework whose weights you can drag live to re-rank a pipeline in real time.<br>
> [Live →](https://bakulbadwal.github.io/dealdocket/)

**[The AI Stack](https://github.com/bakulbadwal/aistack)** — interactive map of the AI industry from silicon to application layer, with ~20 company profiles, three money-flow traces, and a personal AI-cost calculator (subscription vs. pay-as-you-go, at your own usage).<br>
> [Live →](https://aistacked.netlify.app/)

### E-Learning

**[IB Technicals Fluency Trainer](https://github.com/bakulbadwal/ibtrainer)** — merger-model cockpit, purchase-price allocator, and DCF sensitivity heatmap built as live playgrounds, backed by generative math drills and spaced repetition. 

**[Consulting Case Prep Trainer](https://github.com/bakulbadwal/consultingtrainer)** — profit-diagnosis game that scores hypothesis-driven reasoning under a limited information budget, not memorized frameworks, plus a market-sizing builder and exhibit reader.

**[The Operator's P&L Room](https://github.com/bakulbadwal/p-lroom)** — eight-quarter run-the-business simulator under real leverage and covenants, paired with a 13-week cash-crisis room for distress-operator decision-making.

## How these are built

Most are self-contained apps — vanilla HTML/CSS/JS, no framework, no build step, no dependencies — designed, built, and shipped solo end-to-end. AI Stack and PhaseSignal split data from rendering (`data.json` + `app.js`) for content updates. PhaseSignal uses a real Python data pipeline (`data/build_dataset.py`) that pulls and scores live data rather than reading from hand-authored fixtures. TraceHound needs a real backend to keep API keys server-side, so it's a Next.js app with server-rendered API routes, deployed on Vercel.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-black?logo=vercel&logoColor=white)

## Connect

[LinkedIn](https://www.linkedin.com/in/bakulbadwal/) · [Site](https://bakulbadwal.com) · [Email](mailto:badwalb@gmail.com)
