<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:6C8EBF,100:412991&height=6&section=header" />

# Ashwin Ugale

AI / LLM Engineer — I build production agents, RAG pipelines, and the tooling that keeps them reliable.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://ashwin-portfolio-delta.vercel.app/)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=flat&logo=devdotto&logoColor=white)](https://dev.to/ashwin_ugale_102f2abc9cec)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashwin-ugale/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ugaleashwin@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-FF9900?style=flat&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/37dccc3c-462b-48a3-9f36-21e1195b0cf2/public_url)

## About

Software Engineer at Enidus USA, where I build enterprise AI for T-Mobile for Business — multi-tenant LLM tool-calling backends, hybrid retrieval, and LangGraph agents. M.S. in Computer Science from Indiana University Bloomington.

## Featured Projects

Most of what I build is **agent-reliability tooling** — ways to know an agent actually did the right thing, and to catch it when it didn't.

| Project | What it does |
| :--- | :--- |
| **[tracelint](https://github.com/AshwinUgale/tracelint)** | A deterministic linter for agent runs — reads the execution trace and fails CI on structural bugs (ignored tool errors, schema violations, loops, duplicate side effects). No LLM judge. |
| **[muteval](https://github.com/AshwinUgale/muteval)** | Mutation testing for LLM eval suites — degrades a system on purpose to check your evals actually catch regressions. Refuses to score on a red baseline. |
| **[Retrieval-Lab](https://github.com/AshwinUgale/Retrieval-Lab)** | Benchmark RAG retrieval configs on your own corpus, with deterministic, stage-level attribution for every failed query. |
| **[goldset](https://github.com/AshwinUgale/goldset)** | Turns production traffic into a versioned, deduplicated, coverage-tracked LLM regression suite — with a mandatory human-confirmed golden gate. |
| **[smolAmem](https://github.com/AshwinUgale/smolAmem)** | Multi-tier long-term memory for agents: working, episodic, and semantic. Published on PyPI. |
| **[ToolPicker](https://github.com/AshwinUgale/toolpicker)** | Hybrid BM25 + semantic router for agents with too many tools for the context window. Published on PyPI. |
| **[DocChat](https://github.com/AshwinUgale/docchat)** | Answers library questions from the exact version your lockfile pins. VS Code extension + MCP server. |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:412991,100:6C8EBF&height=6&section=footer" />
