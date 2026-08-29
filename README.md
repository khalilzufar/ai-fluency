# AI Fluency

A public portfolio project about building AI workflows that are useful, explainable, bounded, and reviewable.

## What this project demonstrates

- Turning a practical question into a measurable, evidence-based case.
- Using AI for research, drafting, evaluation, and decision support.
- Building a read-only personal agent with structured outputs and explicit safety boundaries.
- Designing an automation workflow with triggers, failure handling, and human review.
- Publishing a responsive project website with documented QA and limitations.

## Project structure

~~~text
ai-fluency/
|-- index.html                 # Public project page and case explorer
|-- demo.mp4                   # Caption-led project walkthrough
|-- favicon.svg                # Site icon
|-- blank/                     # Near-blank page milestone
|-- ai_fluency/
|   |-- agent/                 # Agent design, implementation, and run capture
|   |-- mcp/                   # Agent, workflow, and tool-boundary notes
|   |-- website/               # Build, QA, documentation, and reflection notes
|   |-- workflows/             # Automation workflow specification
|   |-- submissions/           # Evidence map and deliverable index
|-- README.md
~~~

## Live site

[Open the AI Fluency project](https://khalilzufar.github.io/ai-fluency/)

The measured ML case and source notebooks are documented in the [FlyRank-ML repository](https://github.com/khalilzufar/FlyRank-ML).

## Run locally

~~~bash
python -m http.server 8766
~~~

Open http://localhost:8766/ in a browser. To run the personal agent:

~~~bash
python ai_fluency/agent/personal_agent.py --query "Check the public paper"
~~~

The agent uses public evidence only and does not edit, submit, publish, or send messages.

## Safety boundary

The project is designed to keep evidence, limitations, and human review visible. It does not include private client exports, credentials, tokens, or third-party tracking identifiers. Metrics are presented as observed or measured decision support, not as causal claims.

## CV-ready summary

Built a public project demonstrating evidence-based AI workflows through an interactive case explorer, a bounded read-only personal agent, an automation workflow, responsive website QA, and caption-led documentation.
