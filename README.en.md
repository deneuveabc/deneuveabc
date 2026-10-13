> 中文 | [English](README.md)

# Hi, I'm Dennie 👋

I'm a product manager for content and localization, and before that I worked as a translator and a delivery PM. I'm currently looking for new opportunities in AI product management, while using personal projects to practice answering one question:

**Where should AI step in — and where must rules and human judgment stay?**

My projects usually start from a real scenario. The translation evaluation, for example, came from a practical question: can a business actually use the place names AI translates? A wrong name, a corrupted airport code, and a guessed answer under missing context each need different handling.

## In progress

- **Wenjian, a chat agent (v6.1)** — a local chat app built with FastAPI + GPT-5: the model decides when to search the web or read a page, up to three rounds with parallel tool calls per round. What I care most about is visibility — every step shows which tool was chosen, which page was read, and whether that page's date can actually support the word "latest."
- **Voyage, an AI pre-translation workbench for travel content** — a local full-stack prototype: DeepSeek drafts, GPT-5 judges independently against a six-dimension rubric, a human review queue checks every line, and only approved items get applied, manually. The division of labor — AI drafts, rules validate, humans decide — is built into the product flow.
- **Translation evaluation & feedback-driven revision (v0.2)** — a personal synthetic-data experiment: 30 airport/region-name samples through a loop of generation → rule checks + independent AI review → feedback revision → independent retest. All 8 intentionally injected errors were caught and revised; human calibration is still in progress. Honest lesson learned: a translation can match the reference and still hide a corrupted code.
- **Bead Pattern Maker / 豆豆图纸 (v1.9)** — turns a favorite image into a bead pattern you can actually follow: pick size and palette → generate → fine-tune → export or print, with coordinates, color codes, a supply list, and near-color cleanup. Works fully offline; the optional AI "chibi" illustration keeps your API key in your own browser.
- **AI translation product decisions** — an anonymized version of research done during employment, comparing an internal system, a lightweight workflow, and an existing platform, with trade-offs and open questions. It shows a thinking process, not a shipped product — I keep that boundary visible on purpose.

## Also in flight

An email triage prototype (rules + LLM judgment + audit trail) · an English reading tool (article import, tap-to-pronounce) · an image-insight bookmarklet (send a selected web image to DeepSeek for structured analysis) · Girls, Workout Now! (full PRD → local H5 trial build) · a personal website

## How I work

First clarify who is struggling with what, then find the smallest useful step: where to use deterministic rules, where to let AI draft, where a human must decide. Every project states its validation date, sample size, results, and unfinished parts.

Unfinished means unfinished. I'd rather show real progress than a polished "done."

> Public repos and case articles are being published progressively; links will be added as each goes live.

---

中文 | [English](README.md)
