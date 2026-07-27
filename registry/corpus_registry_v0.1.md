---
title: "SOCE Corpus Registry v0.1"
subtitle: "Eleven documented cases · structural signatures and provenance"
author: "Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino"
date: "v0.1.0 · July 2026"
lang: en
---

# Registry rule

Every case is read against its documented diagnosis, never from memory. Each
signature below is the validated output of that reading. Corpus items (new
documents attached to an existing case) do not alter the case count.

# 1 · The eleven structural signatures

| # | Case | σ [I·II·III·IV·V] | Dominant link | Shortcuts | τ |
|---|---|---|---|---|---|
| 1 | Spain 1492 | E·E·E·D·E | I→II | V→I | τ₁ |
| 2 | Jim Crow | E·E·D·E·P | IV→ᵐV | — | τ₂ |
| 3 | Apartheid | E·E·D·E·P | II→IV | — | τ₂ |
| 4 | Rohingya | E·D·E·D·E | I→V | I→V, III→V | puente |
| 5 | Colonial America | E·E·D·E·D | I→II | V→I double | τ₁ |
| 6 | EU 2015 | E·D⁻·E·D·P | I→IV | I→IV, V→III | puente |
| 7 | Nazi | E·E·E·E·E | canonical max. | V→⁺I | τ₁ |
| 8 | AfD/Lukreta | P·D·E·P·P | III→IV | III→IV, III→V | aislado |
| 9 | MAGA | D·D·E·D·D | II→I | II→I, III→IV | τ₃ |
| 10 | MORENA | D·E·E·D·P | II→I | II→I, III→V | τ₃ |
| 11 | Patriot Front | L·E·E·P·D | III→IV | III→V, V→III | aislado |

Documented Todorov vectors (read from diagnosis, never inferred): EU 2015
V=(3,4,3) · MORENA V=(4,2,4). Remaining cases: V is read from the case
diagnosis on file.

# 2 · Families over the corpus

| Family | Cases | Defining trait |
|---|---|---|
| τ₁ canonical-full | 1, 5, 7 | All links active, high intensity, I→II as motor |
| τ₂ braked at IV→V | 2, 3 | Economic limit modulates obedience→Other; px ≤ 3 |
| τ₃ inversion II→I | 9, 10 | Ideology rewrites the record; contemporary democracies |
| puente (skip of II) | 4, 6 | I⇒V or I⇒IV; dense ideological elaboration bypassed |
| aislado (III motor) | 8, 11 | III⇒IV via aesthetic camouflage; extra-registral actor |

**Multiple realisations on record.** τ₃ = {MAGA, MORENA}: same subgraph,
opposed ideological sign. aislado = {AfD/Lukreta, Patriot Front}: same
subgraph, opposed institutional position. Case 11's admission closed all three
of its intake flags and converted *aislado* from singleton to type.

# 3 · Retrodictive validation on record

The prospective module was validated by retrodiction on three cases of known
outcome: freeze the data at an early date, forbid everything later, project,
compare against the real signature (read from the diagnosis).

| Case (frozen at) | A_core | τ predicted | τ real | Chronology |
|---|---|---|---|---|
| MAGA (←2016) | Strong (personalist-restorative) | τ₃ (voiding) | τ₃ ✓ | failed (9 years) |
| MORENA (←2018) | Strong (moral-historical) | τ₃ (capture) | τ₃ ✓ | failed (6 years) |
| EU (←2014) | Weak (securitarian) | puente | puente ✓ | failed (exogenous trigger) |

Three topological-destination hits; chronology is declared outside the
instrument's reliable range. The preregistered replication of this battery is
the object of the OSF deposit that cites this registry's concept DOI.

# 4 · Corpus items and open flags

**Case 9 · MAGA — corpus item: presidential speech, 4 July 2026.** Registered
as an item of Case 9, not a new case. Three flags remain **open** and are
inherited by this registry:

1. Save America Act as candidate inscriptional escalation (Node I)
2. Internal "communist" Other with organic elimination metaphor (Node V
   reading)
3. Appropriation of the state commemorative apparatus as Node III extension

Open flags are closed only by explicit decision of the canonical authority;
their resolution enters a subsequent registry version.

# 5 · Provenance

| Case(s) | Source diagnosis |
|---|---|
| 1–9 | *Diagnóstico 9 casos — ciclo ontológico* (project document) |
| 10 | *Diagnóstico Caso 10 — MORENA* (project document) |
| 11 + Case 9 item | *SOCE Corpus Update — 11 casos* (project document) |

The underlying diagnosis documents are part of the project's internal corpus;
they are cited here as the provenance layer of every signature and enter open
deposit progressively as their clearance is confirmed.
