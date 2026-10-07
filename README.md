# Kerry Shi

I build AI agents and the harnesses that keep them honest.

CS + Statistics at UNC Chapel Hill, graduating May 2027. Looking for new-grad AI engineering,
software engineering, and forward-deployed roles, NYC preferred.

## Projects

| Project | What it is | Evidence |
|---|---|---|
| [agentic-workflow](https://github.com/kerryshi/agentic-workflow) | TypeScript harness that drives Claude Code and Codex through gated plan, build, review, and verify stages, each in a fresh context | [Case study](https://github.com/kerryshi/agentic-workflow/blob/main/CASE-STUDY.md): from 4.3× the cost of no harness to 60% cheaper than its own baseline; 24 failure cases, 23 regression tests, 1 escaped bug written up |
| [china-garden-call-agent](https://github.com/kerryshi/china-garden-call-agent) | Bilingual (English/中文) phone-order agent for my family's restaurant: rules plus Claude Haiku for parsing, a state machine for the order read-back | 175 tests, including failing-first safety regressions from adversarial testing |
| [cad-agent](https://github.com/kerryshi/cad-agent) | English request to verified CadQuery part to OrcaSlicer to a print on a Bambu P2S | 13-task benchmark: a local 8B model extracts 13/13 specs; Sonnet writes 13/13 parts first try, a 30B local code model 0/13 |
| [ai-news-spider](https://github.com/kerryshi/ai-news-spider) | Local Ollama pipeline that ranks emerging AI news by velocity and novelty: Jetson collector, GPU enrichment, VS Code extension | [Live sample digest](https://kerryshi.github.io/ai-news-spider/); 132 tests, SSRF-hardened fetches |

## How I work

- A test I haven't watched fail isn't a test yet.
- The model that writes the code doesn't review it.
- "Done" comes with evidence: test output, logs, a before and after.

The longer version: [what a green test suite missed](https://github.com/kerryshi/agentic-workflow/blob/main/docs/write-up-2026-07.md).

## Contact

kshi@unc.edu · [LinkedIn](https://www.linkedin.com/in/kerryshi) · [Portfolio](https://a01-personal-portfolio-kerryshi.vercel.app)
