# OAH Adversarial Tests

## Purpose

Stress-testing assumptions is different from falsifying a theory.

This document records hostile scenarios intended to probe the limits of OAH.

---

## OA-001 — Selective Commitment Attack

Scenario:

The system preserves a commitment before output but intentionally omits relevant variables.

Question:

Can temporal integrity exist without informational completeness?

Expected:

Temporal integrity survives.
Completeness does not.

Mitigation:

External schemas.

---

## OA-002 — Institutional Collusion

Scenario:

Decision producer and auditor share incentives.

Question:

Does independent evidence remain meaningful if authority is compromised?

Expected:

OAH preserves evidence.

Institutional legitimacy remains external.

---

## OA-003 — Retroactive Reconstruction Attack

Scenario:

Model inversion attempts to reconstruct decisional states after execution.

Question:

Can reconstruction become equivalent to preserved evidence?

Expected:

Reconstruction ≠ verification.

---

## Status

Open stress scenarios.
