# Anshul Dani

Founding Engineer at [Levee](https://levee.biz) · New York

I build AI systems that run in production: vision pipelines, agents, and the harnesses that make them reliable.

[anshuldani.com](https://anshuldani.com) · [LinkedIn](https://linkedin.com/in/anshul-dani) · [anshuldani@gmail.com](mailto:anshuldani@gmail.com)

## Now

At Levee I build the AI behind room inspections for hotels: a phone scan that checks every item in a room against the property's own standards.

- **Inspection pipeline.** On-device image embeddings close the easy items instantly on iOS and Android. A vision-language model verifies only the hard frames in the cloud, and confidence-based routing decides which path each item takes.
- **Agents after the scan.** An event-driven agent pipeline turns each scan into findings, a score and follow-up tasks for managers.
- **Standards as knowledge.** Hotel SOP documents become structured, searchable standards and training content.
- **Mobile.** Shipped the native Android app solo, from zero to Google Play, at parity with iOS.
- **How the work gets built.** I run engineering through a multi-agent harness: a planner, engineers in isolated worktrees, a fresh-context QA gate, evals, and a human approval gate before anything ships.

## How I build

- The model is swappable. The harness around it (context, tools, guardrails, evals) is the product.
- Fail closed. A model outage is "unknown", never a pass.
- Every change gets a reviewer that didn't write it.

## Selected work

| Project | What it is |
|:--|:--|
| [**Salient-Quant**](https://github.com/anshuldani/Simplified-Quantization-for-Edge-Ready-Language-Models) | Salience-guided mixed-precision post-training quantization for edge LLMs, at 1.61 bits per weight without the collapse uniform sub-2-bit methods suffer. |
| [**TAVI**](https://github.com/anshuldani/TAVI-Talk-and-Vision-) | Wearable multimodal assistant for visually impaired users. **Winner, Google Hack for Accessibility 2025.** |
| [**Shareholder Catalyst**](https://github.com/anshuldani/finance_ai_hackathon) | Multi-agent analysis of SEC filings into an investment thesis. **Top 20, LandingAI Financial AI Hackathon**, judged by Andrew Ng. |
| [**Authflow**](https://github.com/anshuldani/authflow-backend) | Prior-authorization automation built in 54 hours. **3rd, Techstars Chicago Startup Weekend.** |
| [**ClearCare**](https://github.com/anshuldani/clearcare) | Multimodal agent that decodes discharge papers and disputes medical bills. Google DeepMind Vibecoding Hackathon. |
| [**Agent Graveyard**](https://github.com/anshuldani/agent-graveyard) | Prompt-injection attack simulator for agent systems. |

## Stack

- **Languages:** Python, TypeScript, Swift, Kotlin, Rust
- **AI:** PyTorch, Core ML, ONNX, Gemini, Claude, MCP, embeddings and vector search
- **Platform:** Django, FastAPI, Next.js, PostgreSQL, Redis, Celery, GCP, Kubernetes, Docker

---

MS in Artificial Intelligence, Illinois Institute of Technology, 2026
