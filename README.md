# Build with Evidence

Portfolio project tentang membangun workflow AI yang berguna, dapat dijelaskan, dan memiliki batas yang jelas. Website ini menggabungkan satu case machine learning berbasis evidence, personal agent read-only, automation workflow, serta catatan QA yang dapat direproduksi.

## Why this project is relevant

Project ini menunjukkan kemampuan untuk:

- mengubah pertanyaan kerja menjadi case yang terukur dan dapat ditinjau;
- menggunakan AI untuk research, drafting, evaluasi, dan pengambilan keputusan secara bertahap;
- membangun personal agent dengan tools kecil, output terstruktur, dan batasan tanpa aksi irreversible;
- membuat workflow automation yang memiliki trigger, langkah, failure handling, dan review manusia;
- menerjemahkan hasil teknis menjadi website publik yang responsif dan mudah dipahami;
- memeriksa responsive behavior, empty state, metadata, dan failure cases sebelum publikasi.

## Project structure

```text
build-with-evidence/
|-- index.html                 # Public portfolio and interactive case explorer
|-- demo.mp4                   # Caption-led project walkthrough
|-- favicon.svg                # Site icon
|-- blank/                     # Near-blank page milestone
|-- ai_fluency/
|   |-- agent/                 # Agent design, implementation, and run capture
|   |-- mcp/                   # Agent, workflow, and MCP boundary notes
|   |-- website/               # Build, QA, documentation, and reflection notes
|   |-- workflows/             # Automation workflow specification
|   `-- submissions/           # Evidence map and deliverable index
`-- README.md
```

## Live site

<https://khalilzufar.github.io/build-with-evidence/>

The measured ML case and source notebooks remain in the [FlyRank-ML repository](https://github.com/khalilzufar/FlyRank-ML).

## Run locally

```bash
python -m http.server 8766
```

Open <http://localhost:8766/> in a browser. To run the personal agent:

```bash
python ai_fluency/agent/personal_agent.py --query "Check the public paper"
```

The agent uses public evidence only, returns a bounded recommendation, and does not edit, submit, publish, or send messages.

## Public-safety boundary

The site contains no private warehouse export, client identity, credential, token, or third-party tracking identifier. Metrics are presented as observed or measured decision support, not as causal claims. Human review remains part of the workflow before any real-world action.

## CV-ready project description

**Build with Evidence - AI Fluency Portfolio**
Built a public portfolio demonstrating evidence-based AI workflows through an interactive case explorer, a bounded read-only personal agent, an automation workflow, responsive website QA, and caption-led documentation. Designed the system to keep evidence, limitations, and human review visible throughout the build.
