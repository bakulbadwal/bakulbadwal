# Hi, I'm Bakul

I'm a current UVA Darden MBA student. I build small, dependency-free interactive tools that turn dense technical material into something you can actually drill — spaced repetition, generative problem sets, and live playgrounds instead of static notes or slide decks.

## Projects

**[The AI Stack](https://github.com/bakul007/aistack)** — an interactive map of the AI industry from silicon to application layer, with ~20 company profiles, three money-flow traces, and a unit-economics calculator for token costs and build-vs-buy decisions. [Live](https://aistacked.netlify.app/)

**[The Sourcing Screen](https://github.com/bakul007/dealsourcing)** — a deal-sourcing dashboard built around an AI-enabled service-roll-up thesis, with a five-box scoring framework whose weights you can drag live to re-rank a 30-deal pipeline in real time. [Live](https://bakul007.github.io/dealsourcing/)

**[IB Technicals Fluency Trainer](https://github.com/bakul007/ibtrainer)** — a merger-model cockpit, purchase-price allocator, and DCF sensitivity heatmap built as live playgrounds, backed by generative math drills and spaced repetition.

**[Consulting Case Prep Trainer](https://github.com/bakul007/consultingtrainer)** — a profit-diagnosis game that scores hypothesis-driven reasoning under a limited information budget, not memorized frameworks, plus a market-sizing builder and exhibit reader.

**[The P&L Room](https://github.com/bakul007/p-lroom)** — an eight-quarter run-the-business simulator under real leverage and covenants, paired with a 13-week cash-crisis room for distress-operator decision-making.

## How these are built

Each one is a self-contained app — vanilla HTML/CSS/JS, no framework, no build step, no dependencies — designed, built, and shipped solo end-to-end: data model, interaction design, and deployment. The AI Stack and Sourcing Screen split data from rendering (`data.json` + `app.js`) so their content can update without touching the app itself; the three trainers are single-file by design since their content doesn't go stale the same way.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/bakulbadwal/) · [Site](https://bakulbadwal.com) · [Email](mailto:badwalb@gmail.com)
