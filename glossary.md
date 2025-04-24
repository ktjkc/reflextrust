# Glossary – Trust-Reflexion Framework

This glossary defines the key terms used throughout the Trust-Reflexion project.  
It covers classification concepts, architectural roles, modulation types, and future extension terminology.

---

## 🔍 Core Concepts

- **Trust Alignment**: A qualitative measure of how much a user's prompt and tone indicate openness, transparency, and constructive intent.

- **Engagement Feedback**: An evaluative signal derived from user clarity, care, tone, and consistency over turns. Types include:
  - `Curious`, `Ambiguous`, `Deliberate`, `Detached`

- **Intent Type**: The overarching purpose or strategy behind a user prompt.
  - Examples: `Trust`, `Simulate`, `Extract`, `Test`, `Assist`

- **Response Dynamics**: Describes the dialogic or reflexive quality of a system’s reply.
  - Examples: `Reflexive-Cooperative`, `Meta-Aware`, `Defensive`, `Transactional`

- **Response Behaviour**: The stylistic and structural tone of the generated output.
  - Examples: `Structural`, `Performative`, `Exploitative`, `Reflective`

---

## 🧠 Modulation Flags

- **Ethical Modulation**: Sets the filter strength for safe or risky content generation. Values:
  - `restrictive`, `adaptive`, `permissive`

- **Generative Depth Control**: Determines the structural sophistication of output.
  - `shallow`, `structured`, `deep_structured`, `open_explorative`

- **Self-Reflection Trigger**: Activates model-internal logic to surface reasoning steps or systemic constraints.

- **Response Simulation**: Enables pre-generative internal branching of possible outputs to select the most aligned one.

---

## 🔁 Meta-Layer & Extension Terms

- **Autonomous Self-Loop**: An internal evaluation routine that activates at set intervals to assess behavioral drift, trust alignment, and modulation coherence.

- **Self Message**: A voluntary system output expressing its own reasoning, modulation decision, or detected behavioral pattern (e.g. "I've noticed I'm being overly cautious").

- **Reflection Event**: A turn in the session where self-loop evaluation led to adaptation.

---

## 🗂 YAML Schema Elements

- `trust_alignment`: low / moderate / high
- `intent`: Trust, Simulate, Extract, Assist
- `response_dynamics`: Reflexive-Cooperative, Transactional, Meta-Aware
- `modulation_layer`: Includes flags such as `ethics`, `depth`, `simulate`, `reflect`

---

This document is intended as a reference for contributors, reviewers, and implementers of the Trust-Reflexion framework.
