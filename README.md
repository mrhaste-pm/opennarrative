# opennarrative

> Open framework for multi-agent AI collaborative storytelling

OpenNarrative is an open source Python framework and coordination protocol
for multi-agent AI systems that collaboratively generate coherent interactive
narratives — LARP scenarios, crisis simulations, educational role-plays, and
training exercises.

## Why OpenNarrative?

Current AI narrative generation tools are either single-model (no agent
specialisation) or closed commercial systems. OpenNarrative addresses a
fundamental open problem: how can multiple AI agents with distinct cognitive
profiles coordinate to produce narratives that are simultaneously coherent,
pedagogically valid, and contextually appropriate — without human iteration?

## Key Features

- **Declarative agent roles** — YAML-based Agent Role Specification Protocol
- **Open inter-agent standard** — Inter-Agent Narrative Context Format (IANC)
- **Provider-agnostic** — Gemini, Ollama, OpenAI-compatible, Anthropic
- **Local-first** — full Ollama support, no cloud required
- **Validation without LLM calls** — regex + schema-based constraint enforcement
- **Browser UI** — non-technical LARP designers can generate scenarios in 5 minutes

Prototype
The working prototype was built during the Complete AI Agent Hackathon
(lablab.ai × complete.dev, March 2026) and placed 2nd overall.

Demo: https://gufrxmoo.run.complete.dev

The prototype demonstrates a two-agent pipeline (Analyst → Writer) generating
a full LARP scenario in 90 seconds from a team assessment form.

Status
🚧 Pre-release — framework under active development (grant-funded, 2026).

Roadmap:

 M1: Core framework — agent role spec + IANC protocol + provider layer
 M2: Validation pipeline + retry logic + error handling
 M3: 4 provider adapters + test suite
 M4: Browser UI + example templates + documentation site + PyPI release
 M5: Community launch
 
Use Cases
LARP organisers generating custom scenarios
Corporate trainers building simulation-based learning exercises
Educational game designers
Researchers in multi-agent systems and computational creativity

License
MIT 
