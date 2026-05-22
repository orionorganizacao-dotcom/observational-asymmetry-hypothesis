# The Observational Asymmetry Hypothesis (OAH)

A formal framework describing the structural distinction between generating and reconstructing decisional states.

---

## Core proposition

Formal statement:

Execution of a decisional state does not guarantee reconstructability of that state from externally accessible information.

Simplified proposition:

> "Execution does not imply observability."

---

## Motivation

Modern AI systems increasingly generate consequential actions while exposing only outputs and retrospective explanations.

Current assumptions often implicitly treat:

- execution as equivalent to accessibility
- outputs as equivalent to evidence
- explanations as equivalent to reconstruction

These assumptions may fail in systems where informational accessibility differs fundamentally from informational generation.

OAH proposes that such failures are not necessarily implementation problems, but may emerge from structural properties of decisional systems.

---

## Core definitions

### Decisional State

Internal informational configuration responsible for generating an action or output.

Examples:

- latent representations
- internal model states
- hidden policy configurations
- intermediate computational structures

---

### Execution

Transformation of a decisional state into observable output.

Formally:

```text
Decisional State → Output
```

---

### Observability

Ability to reconstruct properties of a decisional state from externally accessible information.

Formally:

```text
Observable Information → Reconstruction
```

---

### Observational Asymmetry

Condition where generation and reconstruction require fundamentally different informational resources.

Formally:

```text
Generation ≠ Reconstruction
```

---

## Central hypothesis

OAH proposes:

> Two systems may generate identical observable outputs while requiring fundamentally different informational accessibility for reconstruction.

Consequently:

- identical outputs do not imply identical internal structures
- explanations may be incomplete proxies
- outputs alone may be insufficient evidence
- auditability may require independent mechanisms

---

## Conceptual model

```text
Internal State
        ↓
Decision Formation
        ↓
Execution
        ↓
Observable Output
        ↓
Reconstruction Attempt
```

OAH suggests that information loss or informational asymmetry may occur between execution and reconstruction.

---

## Expected implications

If observational asymmetry exists, potential consequences include:

### AI governance

- limitations of post-hoc explanations
- need for independent evidence preservation
- limitations of transparency-only approaches

### Autonomous systems

- incomplete reconstructability
- hidden decision pathways
- latent internal dynamics

### Human-AI interaction

- perception mismatch
- trust calibration problems
- explainability limitations

### High-risk systems

Examples:

- healthcare
- financial systems
- legal systems
- autonomous agents
- safety-critical environments

---

## Repository structure

### /paper

Formal components of OAH.

Contents:

- `paper_v0.2.md` → Main manuscript
- `abstract.md` → Abstract
- `hypotheses.md` → Formal hypotheses
- `methods.md` → Experimental methodology
- `falsifiers.md` → Falsification criteria
- `limitations.md` → Known assumptions and limitations
- `references.md` → Bibliography
- `threat_model.md` → Threat model and attack surfaces

---

### /experiments

Experimental protocols and validation procedures.

Examples:

- Human-AI perception experiments
- blind evaluation experiments
- reconstruction tests
- drift simulations

---

### /diagrams

Conceptual and architectural visual models.

Examples:

- execution vs reconstruction
- informational flow
- asymmetry models
- attack surfaces

---

## Falsifiability principle

OAH is intended as a falsifiable framework.

The hypothesis fails if:

### F1

Reconstruction can always be derived from outputs alone.

---

### F2

Decisional states and observable outputs demonstrate complete informational equivalence.

---

### F3

No measurable asymmetry exists between generation and reconstruction processes.

---

## Known limitations

Current limitations include:

- conceptual stage
- incomplete empirical validation
- dependence on operational definitions
- reconstruction metrics under development
- possible domain dependence

OAH does not claim:

- universal applicability
- proof of correctness
- proof of consciousness
- proof of accountability

---

## Current status

Version:

```text
v0.2
```

Development status:

```text
Conceptual formulation      ✓
Formal structure            ✓
Definitions                 ✓
Falsification criteria      ✓
Experimental design         in progress
Empirical validation        pending
```

---

## Author

Ezio v.s. Santos

Independent Researcher

AI Governance & Verifiability

---

## Suggested citation

```bibtex
@misc{santos2026oah,
author={Ezio v.s. Santos},
title={The Observational Asymmetry Hypothesis (OAH)},
year={2026},
note={Work in progress},
url={https://github.com/orionorganizacao-dotcom/observational-asymmetry-hypothesis}
}
```

---

## License

Released for academic discussion, review, criticism, and collaborative development.
