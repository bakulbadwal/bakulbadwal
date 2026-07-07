# Hi, I'm Bakul

I'm a current UVA Darden MBA student. Among other projects, I'm building interactive tools that turn dense technical material into something you can actually drill — spaced repetition, generative problem sets, and live playgrounds instead of static notes or slide decks. 

## Projects

**[The AI Stack](https://github.com/bakulbadwal/aistack)** — an interactive map of the AI industry from silicon to application layer, with ~20 company profiles, three money-flow traces, and a unit-economics calculator for token costs and build-vs-buy decisions. [Live](https://aistacked.netlify.app/)

**[TraceHound](https://github.com/bakulbadwal/tracehound)** — an agentic on-chain crypto hack tracer: live hop-by-hop tracing from compromised wallet via the Etherscan API, cross-references a watchlist populated with real, current OFAC-sanctioned addresses pulled from Treasury's SDN list, LLM narration, and drafts a demand letter from the trace facts. Victims should file with the FBI's IC3. [Live](https://tracehound.vercel.app)

**[The Sourcing Screen](https://github.com/bakulbadwal/dealsourcing)** — a deal-sourcing dashboard built around an AI-enabled service-roll-up thesis, with a five-box scoring framework whose weights you can drag live to re-rank a 30-deal pipeline in real time. [Live](https://bakulbadwal.github.io/dealsourcing/)

**[Clinical Trial Screener](https://github.com/bakulbadwal/clinicaltrial-screener)** — pulls real, live trial data from the ClinicalTrials.gov API and scores each one against a cited published base rate, adjusted by four computed factors with a full live-reweighting breakdown — no black-box score, every number sourced or fetched. [Live](https://bakulbadwal.github.io/clinicaltrial-screener/)

**[IB Technicals Fluency Trainer](https://github.com/bakulbadwal/ibtrainer)** — a merger-model cockpit, purchase-price allocator, and DCF sensitivity heatmap built as live playgrounds, backed by generative math drills and spaced repetition.

**[Consulting Case Prep Trainer](https://github.com/bakulbadwal/consultingtrainer)** — a profit-diagnosis game that scores hypothesis-driven reasoning under a limited information budget, not memorized frameworks, plus a market-sizing builder and exhibit reader.

**[The Operator's P&L Room](https://github.com/bakulbadwal/p-lroom)** — an eight-quarter run-the-business simulator under real leverage and covenants, paired with a 13-week cash-crisis room for distress-operator decision-making.

## How these are built

Most are self-contained apps — vanilla HTML/CSS/JS, no framework, no build step, no dependencies — designed, built, and shipped solo end-to-end: data model, interaction design, and deployment. The AI Stack, Sourcing Screen, and Clinical Trial Screener split data from rendering (`data.json` + `app.js`) so their content can update without touching the app itself; the three trainers are single-file by design since their content doesn't go stale the same way. Clinical Trial Screener goes a step further with a real Python data pipeline (`data/build_dataset.py`) that pulls and scores live data rather than reading from hand-authored fixtures. TraceHound is the exception — it needs a real backend to keep API keys server-side, so it's a Next.js app with server-rendered API routes, deployed on Vercel.

## Connect

[LinkedIn](https://www.linkedin.com/in/bakulbadwal/) · [Site](https://bakulbadwal.com) · [Email](mailto:badwalb@gmail.com)
