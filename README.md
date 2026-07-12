# Hi, I'm Bakul

I'm a UVA Darden '27 student. I'm building AI tools with real-world use case based on my academic + professional experiences in ai x bio/longevity, ai x blockchain, VC and PE, etc. I'm also building interactive tools I use to drill dense technical material.

## Projects

**[Tranche AI](https://github.com/bakulbadwal/tranche-ai)** — condition-gated capital release for VC deals: an AI agent reviews milestone evidence and posts a signed, on-chain attestation (EAS). Solidity + Foundry, live on Base Sepolia. [Live](https://tranche-ai.vercel.app)

**[TraceHound](https://github.com/bakulbadwal/tracehound)** — an agentic on-chain crypto hack tracer: live hop-by-hop tracing from compromised wallet via the Etherscan API, cross-references a watchlist populated with real, current OFAC-sanctioned addresses pulled from Treasury's SDN list, LLM narration, and drafts a demand letter. [Live](https://tracehound.vercel.app)

**[The AI Stack](https://github.com/bakulbadwal/aistack)** — an interactive map of the AI industry from silicon to application layer, with ~20 company profiles, three money-flow traces, and a personal AI-cost calculator (subscription vs. pay-as-you-go, at your own usage). [Live](https://aistacked.netlify.app/)

**Live Forever** *(private)* — a personal longevity data engine: unifies Oura Ring, Apple Health, and clinical bloodwork (via MCP + REST APIs), computes a **PhenoAge** biological-age clock from a standard blood panel, benchmarks against Bryan Johnson's public Blueprint targets and population cohorts, and quantifies what each intervention actually moved — HRV, sleep, recovery, resilience, on a 28-day before/after basis.

**[PhaseSignal](https://github.com/bakulbadwal/phasesignal)** — pulls real, live trial data from the ClinicalTrials.gov API and scores each one against a cited published base rate, adjusted by four computed factors with a full live-reweighting breakdown — no black-box score, every number sourced or fetched. [Live](https://bakulbadwal.github.io/phasesignal/)

**[IB Technicals Fluency Trainer](https://github.com/bakulbadwal/ibtrainer)** — a merger-model cockpit, purchase-price allocator, and DCF sensitivity heatmap built as live playgrounds, backed by generative math drills and spaced repetition. 

**[Consulting Case Prep Trainer](https://github.com/bakulbadwal/consultingtrainer)** — a profit-diagnosis game that scores hypothesis-driven reasoning under a limited information budget, not memorized frameworks, plus a market-sizing builder and exhibit reader.

**[The Operator's P&L Room](https://github.com/bakulbadwal/p-lroom)** — an eight-quarter run-the-business simulator under real leverage and covenants, paired with a 13-week cash-crisis room for distress-operator decision-making.

## How these are built

Most are self-contained apps — vanilla HTML/CSS/JS, no framework, no build step, no dependencies — designed, built, and shipped solo end-to-end: data model, interaction design, and deployment. The AI Stack and PhaseSignal split data from rendering (`data.json` + `app.js`) so their content can update without touching the app itself; the three trainers are single-file by design since their content doesn't go stale the same way. PhaseSignal goes a step further with a real Python data pipeline (`data/build_dataset.py`) that pulls and scores live data rather than reading from hand-authored fixtures. TraceHound is the exception — it needs a real backend to keep API keys server-side, so it's a Next.js app with server-rendered API routes, deployed on Vercel.

## Connect

[LinkedIn](https://www.linkedin.com/in/bakulbadwal/) · [Site](https://bakulbadwal.com) · [Email](mailto:badwalb@gmail.com)
