> English | [中文](README.md)

# Hi, I'm Dennie 👋

Content & Localization Product Manager, formerly a simultaneous interpreter and delivery PM. I'm currently exploring new opportunities in AI product management, using side projects to work through one question seriously:

> **Where should AI step in—and where do deterministic rules and human judgment need to stay in charge?**

Most of my projects start from real operational friction. I built a translation quality evaluation experiment because I wanted a straight answer: can a business actually ship AI-translated place names as-is? A wrong name, a corrupted airport code, and a guess made without enough context each fail differently—and require different safeguards.

## Currently Building

- **Wenwen · Chat Agent** `v6.1` · `FastAPI` `GPT-5`
  A local chat app where the model decides when to search the web and read pages (up to 3 rounds, with parallel tool calls per round). What I care about most is **observability**: you can expand every step in the UI to inspect which tools ran, which pages were read, and whether a page's date actually backs up a "latest" claim.

- **Voyage · Travel Content Pre-Translation Workbench** · `DeepSeek` `GPT-5`
  A local full-stack prototype that turns "AI drafts → rules validate → humans decide" directly into a product workflow: DeepSeek produces initial translations, GPT-5 runs an independent 6-dimension evaluation, and human reviewers check items in a queue before batch-applying what passes.

- **Translation Quality Eval & Feedback Loop** `v0.2`
  A personal synthetic-data experiment (30 airport and region name samples) running an end-to-end loop: generation → rule checks + independent AI QA → feedback revision → independent re-test. All 8 intentionally injected errors were caught and fixed; human calibration is still underway. One key lesson recorded along the way: **a translation matching the reference text can still mask code corruption**.

- **Doudou Grid · Fuse Bead Pattern Generator** `v1.9`
  Turns images into build-ready bead patterns: choose dimensions and palette → generate → fine-tune → download or print, complete with coordinate color codes, material lists, and near-color grouping. Runs fully locally; optional AI illustration for chibi styles keeps your API key strictly in your own browser.

- **AI Translation Solution Decision Retrospective**
  A sanitized write-up of a solution evaluation from my previous role, comparing an in-house build, a lightweight workflow, and existing platforms across trade-offs and open questions. I always keep this boundary clear: **this documents the decision-making process, not a shipped product**.

## Other Experiments

| Project | Description |
| :--- | :--- |
| **Email Triage Prototype** | Rule-based logic + LLM classification + audit logging |
| **English Reading Tool** | Import articles and tap words for pronunciation |
| **Image Analysis Bookmarklet** | Select any web image for structured analysis via DeepSeek |
| **Girls, Workout Now!** | Full PRD taken through to a local H5 prototype |
| **Personal Website** | Personal homepage site |

## How I Work

- Start by getting clear on **who is struggling with what**, then scope the smallest useful step: what belongs to deterministic rules, what AI should draft, and where a human must sign off.
- Every project documents its **verification date, sample size, actual results, and unfinished parts**.
- Unfinished means unfinished. I'd rather show real progress than package half-done work as "completed."

> Public repositories and case studies are being organized and published gradually—links will be added as they go live.
