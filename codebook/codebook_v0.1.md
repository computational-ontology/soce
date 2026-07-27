---
title: "SOCE Codebook v0.1"
subtitle: "Measurement canon · Social-Ontological Cycle of Exclusion"
author: "Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino"
date: "v0.1.0 · July 2026"
lang: en
---

# Scope and governing sources

This codebook is the operative extraction of the SOCE measurement canon. It is
derived from the canonical Spanish-language project documents — chiefly *SOCE ·
Sistema completo de métricas* (v1.0, June 2026), the *Documento matriz del
exoesqueleto*, and the two-module specification — and distils them into the
coding scheme an analyst needs to produce a structural signature. The ordinal
notation itself is language-independent. Where wording here and in the source
documents could be read differently, the source documents govern.

**Governing principle.** *La IA propone, el humano decide* — the AI proposes,
the human decides. The AI handles scale, syntactic consistency and pattern
alerting; the human retains interpretive sovereignty, the ethics of diagnosis
and control of the fundamental ontology.

# 0 · The measurement canon

SOCE does not measure exclusion with indices, coefficients or continuous
values. It measures through a layered ordinal-nominal notation governed by one
invariant rule:

> **The notation describes what is already observed in a diagnosis; it
> introduces no magnitudes that are not measured. If something cannot be read
> from an existing diagnosis, it does not enter the notation.**

This rule has an absolute operative consequence: **no ordinal state may ever be
averaged, summed or weighted.** The order L < P < D < E is qualitative, not
arithmetic — the step from L to P is not necessarily equal to the step from D
to E. Assigning numeric weights to qualitative states, or fabricating
parameters the referent does not exhibit, is cosmetic formalisation and is
explicitly rejected.

**Reproducibility** is defined as two independent analysts producing the same
structural signature Φ on the same case — never as a statistical coefficient.
Divergence between analysts is not suppressed by a threshold; it is versioned
and graded on the ordinal δ scale (see `protocol/delta_protocol`).

**What the metrics deliberately do not do.** No SOCE metric produces an
exclusion score. Distances between qualitative states are not uniform; a score
would aggregate dimensions the system treats as irreducible; and a score would
rank persons on a continuum, creating direct algorithmic risk under the EU AI
Act. The system produces a topology of processes, not rankings of people.

**Where statistics lives.** The canon forbids quantification *inside* the
signature Φ. It does not forbid statistics in the calibration membrane of the
Anchor Set: quantitative corpora may calibrate the boundary between ordinal
categories, but the output that enters Φ is always the ordinal descriptor.
*Statistics calibrates the rubric; it never contaminates the signature.*

# 1 · The structural signature Φ = ⟨σ, V, E⟩

Each case is represented by one structural signature: a tuple of three layers,
measured separately and never collapsed into a single number.

| Layer | Notation | What it measures |
|---|---|---|
| **σ** — node intensity | ⟨I, II, III, IV, V⟩ ∈ {L, P, D, E} | The role of each of the five nodes in the case |
| **V** — Todorov axes | (ax, px, ep) ∈ {1..5} | Intensity of the treatment of the Other on three independent axes |
| **E** — link states | 11 links ∈ {·, →, ⇒, →ᵐ, →⁺} | How the cycle flows between the active nodes |

Diacritics: **⁻** marks weakened intensity within its category (e.g. D⁻); an
arrow over a state marks a transition in progress (e.g. D→E).

# 2 · Layer σ — node intensity

Each node receives one state on a four-value ordinal scale:

| Symbol | State | Meaning |
|---|---|---|
| **L** | Latent | The node exists but is not a motor of the cycle |
| **P** | Present | The node operates and contributes |
| **D** | Dominant | The node is one of the motors of the case |
| **E** | Structural | The node is the backbone of the case |

Qualitative order: **L < P < D < E**. Never averaged, never summed.

## 2.1 The five nodes and their anchor sources

| Node | Question it answers | Anchor source |
|---|---|---|
| **I · Documentality** | Who counts, in the record? Inscription decides: censuses, acts, statutes, databases | Ferraris |
| **II · Ideological anatomy** | What belief system naturalises the exclusion as "what is"? Tuple ⟨C,S,D,G,B,A,P,V,I,O,M⟩; the decisive element is the **A_core**, the non-negotiable nucleus the rest protects | Romero |
| **III · Imagined community** | How is the We — and the image of the excluded — fabricated and diffused? Critical variable: **velocity** of reproduction | Anderson |
| **IV · Normative obedience** | Why does the norm bind, and how is it obeyed? Act-sources and fact-sources; ten modes of obedience, each with its characteristic fracture | Pegoraro & Rinella |
| **V · Production of the Other** | How is the excluded defined, treated and known? Three irreducible axes | Todorov |

Symbol collisions (G, V, B appear in more than one node) are resolved by node
prefixing — II.G, II.V, II.B — never by tensors.

# 3 · Layer V — the Todorov axes

The only node with a subvector metric: three simultaneous, independent axes,
each ordinal 1–5. **The three axes are never summed or averaged; their
dissociation is diagnostic.** Between the planes there are affinities but, in
Todorov's terms, no rigorous implication: one cannot be reduced to or predicted
from another.

| Axis | What it measures | Range |
|---|---|---|
| **ax** — axiological | How the Other is valued | 1 = equal · 5 = existential threat |
| **px** — praxeological (*the thermometer*) | How the Other is treated | 1 = assimilation · 5 = physical elimination |
| **ep** — epistemological | How the Other is known | 1 = own voice · 5★ = erasure of the Other's own knowledge |

The **px** axis carries the full boundary-descriptor rubric (see
`anchors/anchor_rubrics`). The marker **ep:5★** flags the erasure of the
Other's own knowledge — the level at which resistance takes generations to
rebuild. Low px with high ax is the *elite-Other* reading (corpus: MORENA,
ax=4, px=2): the Other is valued as a grave threat but not physically
eliminated. Averaging the axes would destroy exactly the information that
distinguishes τ₃ from τ₁.

# 4 · Layer E — the links

While σ measures which nodes are active, E measures how they relate: what each
node transmits to which, with what intensity, in which direction.

## 4.1 The five link states

| State | Symbol | Meaning |
|---|---|---|
| Inactive | **·** | The link does not operate in this case |
| Active | **→** | The link operates |
| Dominant | **⇒** | The link carries the causal weight of the case |
| Modulated | **→ᵐ** | Operates with a brake (economic limit, institutional fracture, asymmetry) |
| Accelerant | **→⁺** | Reinforces itself with each iteration |

## 4.2 The catalogue of eleven links

Five canonical links (the spine) and six shortcuts confirmed against the
corpus, two of which emerged from extraction itself. The catalogue is
**saturated**: no proposed shortcut remained without a documenting case.

| Link | What it transfers | Type |
|---|---|---|
| I→II | Inscription fixes which categories are available for belief | Canonical |
| II→III | The A_core supplies the content to diffuse | Canonical |
| III→IV | The imagined community generates obedience | Canonical |
| IV→V | Obedience institutionalises the treatment of the Other | Canonical |
| V→I | The consolidated Other re-inscribes into the record | Canonical (closure) |
| I→IV | The record coerces obedience without dense ideology | Shortcut (EU 2015) |
| I→V | De-inscription is already production of the Other | Shortcut (Rohingya) |
| III→V | Technology produces Others in real time | Shortcut (MORENA, Rohingya) |
| III→IV | Aesthetic camouflage produces identitarian obedience | Shortcut (AfD/Lukreta) |
| V→III | The consolidated Other feeds back into imagination | Shortcut |
| II→I | Ideology rewrites the record (inversion) | Shortcut (MAGA, MORENA) |

Each link has a verifiable activation condition; that verifiability is what
sustains reproducibility.

## 4.3 The recursive closure V→I

V→I is not one more step: it is the macro-link that filters, in each
iteration, which inscriptions can be updated — only those coherent with the
already-consolidated Other. In Onnis's terms this is downward causation: the
macro level conditions the micro.

**Intervention asymmetry.** Before the loop closes, interrupting one link
suffices to stop the cycle. After closure, simultaneous multi-node
intervention is required: a single-node intervention is absorbed by the
others. Apartheid (1994) is the only corpus case successfully interrupted from
within, through simultaneous intervention in nodes I, II, III and IV.

# 5 · Derived metrics

## 5.1 The topological family τ

The family is read from the configuration of E — which links are active, which
is dominant, which are modulated — never from σ. Derivation is **structural
comparison against the existing families, not numerical distance**. A case
that fits no family is a new type: the signal of a theoretically productive
case.

| Family | Corpus cases | Defining trait |
|---|---|---|
| **τ₁** canonical-full | 1, 5, 7 | All links active, high intensity, I→II as motor |
| **τ₂** braked at IV→V | 2, 3 | Economic limit modulates obedience→Other; px ≤ 3 |
| **τ₃** inversion II→I | 9, 10 | Ideology rewrites the record; contemporary democracies |
| **puente** (skip of II) | 4, 6 | I⇒V or I⇒IV; dense ideological elaboration is bypassed |
| **aislado** (III motor) | 8, 11 | III⇒IV via aesthetic camouflage; extra-registral actor |

Two multiple realisations validate the architecture: **τ₃ = {MAGA, MORENA}**
joins a right-wing and a left-wing movement in the same subgraph despite
opposed A_cores — structural invariance across ideological sign; **aislado =
{AfD/Lukreta, Patriot Front}** joins an electoral party with partial
institutional access and an extra-institutional group with none — structural
invariance across institutional position. The equivalence is topological, not
axiological: identical structure does not imply equivalent gravity, which is
read from px and from the presence or absence of internal limits.

## 5.2 The topological genocide-risk correlate

A second-order metric legible directly from the signature. The two genocidal
corpus cases (Nazi, Rohingya) are the only ones in which **no link entering or
leaving node V is modulated and the closure V→I is accelerant**. In every
other case some link to or from V is braked — by an economic limit, an
institutional fracture, or an axiological-praxeological asymmetry.

The full substantive predictor requires co-presence of four conditions: (1) an
A_core of inverted causality — the Other is the cause of the ill, not merely
its consequence; (2) absence of legal subjecthood of the Other; (3) absence of
an economic limit; (4) the V→I acceleration condition. Its precise topological
correlate is the absence of any modulation on node-V links combined with
accelerant V→I. This is a **correlate read from the signature of a
consolidated case, not a predictive instrument**; the prospective module
detects tendency and does not forecast outcomes.

## 5.3 The δ scale — graded divergence

Measures how far apart two signatures produced by different analysts on the
same case are. Each grade contains the previous ones (δ₀ < δ₁ < δ₂ < δ₃ < δ₄):
a legitimate ordinal order by inclusion, not a distance metric. Full
specification and the operating procedure live in
`protocol/delta_protocol`.

# 6 · Modulated links are the map of fractures

A modulated link (→ᵐ) is not a failure of the cycle: it is the signal of where
resistance can intervene. Reading what brakes what is reading the structure of
opportunities for interruption. Together with the characteristic fracture of
the dominant obedience mode (Node IV), this is the system's principal
practical output.

# Version note

v0.1.0 freezes the current canon only. Open analytical flags of the project
(recorded in the project flag register) are **not** resolved in this document;
any change they produce enters as a versioned release, never as a silent edit.
