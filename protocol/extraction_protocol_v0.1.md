---
title: "SOCE Extraction Protocol v0.1"
subtitle: "Producing a structural signature · the two-tier rule"
author: "Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino"
date: "v0.1.0 · July 2026"
lang: en
---

# The two-tier use rule

- **Exploratory use is open to all.** Any analyst — human or machine — may
  load the codebook, read a case and produce a provisional reading.
- **Canonical diagnosis requires two trained coders under the δ-protocol.** A
  signature produced without that validation is not a canonical SOCE signature
  and must not be presented as one.

Reproducibility is defined as two independent analysts producing the same Φ —
not as a statistical coefficient. This protocol is what makes that definition
operable.

# 1 · The descriptive procedure (SOCE-D), five steps

The descriptive-synchronic module reads an already-consolidated case and
produces its signature:

1. **Read the intensity of each node** against the documented diagnosis and
   write σ.
2. **Annotate the three Todorov axes** (activation questions in ascending
   order, highest value sustained by ≥ 2 independent sources) and write V.
3. **Verify each of the eleven links** against the evidence — does it operate?
   in which state? — and mark E.
4. **Identify the link that carries the causal weight** of the case and mark
   it dominant (⇒).
5. **Derive the topological family** by structural comparison of E against the
   existing families. If it fits none, recognise a new type — the signal of a
   theoretically productive case.

# 2 · The hybrid protocol — two layers, one integrator

The choice is methodological, not cosmetic. A **structured-metadata layer**
(the signature Φ as a JSON-analogue package: compact, comparable,
machine-readable) distils a **semantic layer** in natural language (the
analysis record of each node, irreducible to a single scale).

> The signature is the artefact of integration; **the analyst is the agent of
> integration.** The ordinal state summarises; the textual record preserves
> the evidence and reasoning no state fully captures.

Symbol collisions are resolved by node prefixing (II.G, II.V, II.B) so that V
the node is never confused with II.V the values component.

# 3 · AI-assisted extraction

When an LLM proposes a signature, it does so **under the anchor rubrics and
through the Anchor Set** — the curated reference corpus that functions as
control space. Queries pass through its filter, forcing the model to
contextualise observational data under the predefined theoretical categories;
accumulation happens by interpretive jurisprudence (validated precedents,
CVA), never by weight retraining.

The AI handles scale, syntactic consistency and pattern alerting. It proposes
Φ **with justifications and uncertainty flags (?)** on every reading it cannot
sustain in evidence. It does not decide; it does not produce scores that
classify persons; the epistemological governor vetoes activation of any node
without a referent.

# 4 · Validation

1. **Directed validation.** The human audits the flagged readings. Acceptance
   is recorded as a validation act (CVA) with empty corrections — positive
   evidence. Correction is classified (error classes E1–E7) with justification
   and a pattern note.
2. **Second coder.** For a canonical signature, a second trained coder
   produces Φ independently.
3. **Comparison.** The two signatures are compared on the δ scale
   (`protocol/delta_protocol`). δ₀ closes the case; any higher grade follows
   the δ-protocol.

# 5 · Uncertainty flags

Ambiguity is made traceable, not eliminated. A flag (?) marks a reading the
rubrics cannot settle; flagged readings cannot silently enter a canonical
signature — they are resolved in validation or held open by explicit decision.
Open flags are versioned with the case (see the corpus registry, §4, for the
currently open flags of Case 9).
