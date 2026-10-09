# Holly and AI

**Holly** is the name HollyEarth uses for its assistance layer: deterministic helpers, a case-scoped investigation assistant, optional model reasoning and voices. In v0.1.0 Holly is **not** one autonomous agent and not a global assistant.

## HollyEarth works without a language model

Navigation, maps, graphs, cases, claims and quotations, typed money, deterministic analysis, Story, Monitoring, HollySport, Social Intelligence and the Riga Twin all work with every model switched off. A model adds optional wording, reasoning and research help around this core.

## What Holly is today

| Holly as… | Status | What it is |
|---|---|---|
| **Deterministic helpers** | `WORKING` | "Holly sees" register counters in Social, case analysis patterns, story assembly, quotation checks — no model |
| **Investigation assistant** | `BETA` | A chat inside a case. It answers analytic questions from the case's saved analysis first and uses a model only for other questions; suggested actions must refer to records the case holds |
| **Optional model reasoning** | `BETA` | "Suggest new analytic ideas" — hypotheses and directions, labelled as hypotheses, never stored as facts |
| **Model-assisted research** | `BETA` | Research runs may use a model to find and read sources; a proposed claim is kept only if its quotation is found word for word in the document. A research session states its budget |
| **Story wording** | `BETA` | A model may reword sentences inside the deterministic story plan; the result is checked against the plan's figures and claim counts |
| **Decision analysis on the Twin** | `BETA` | Hypotheses about a council decision from its canonical record; being changed to run only on an explicit request, with caching and limits |
| **Voice** | `BETA` | Browser voice, a local voice model, or a paid hosted voice used only after confirmation |
| **Global Holly assistant** | `FUTURE` | Not connected in v0.1.0 |
| **Autonomous agents** | `FUTURE` | Not part of v0.1.0 |

## The boundary between models and knowledge

- Models **cannot** write into the canonical graph, and cannot set a corroborated or verified status.
- Model output is labelled by kind — interpretation, hypothesis, rival hypothesis, prediction. Facts, legal conclusions and personal ratings are refused.
- In cases, a model can propose claims, entities and amounts only through the verbatim-quotation gate. In v0.1.0 that produced 8 of 111 case claims, 12 of 104 case entities and 7 of 84 money records. These are not yet marked as model-extracted in the interface — being added.
- Stored model outputs (analyses, hypotheses, one story wording, two assistant answers) are labelled and can be older than the case; the product says so.

## What comes next

One gateway for every model and voice provider with budgets, logging and a kill switch; a consistent "AI / paid" marker on every control that calls a model; explicit-only decision analysis; marked and filterable model-extracted records; and a human review workflow. Production hardening (authentication, rate limits, cost controls) comes before any public deployment.

Model providers used optionally in v0.1.0 are listed in [DATA_SOURCES.md](../DATA_SOURCES.md). Details: [FEATURE_STATUS.md](FEATURE_STATUS.md#holly-ai).
