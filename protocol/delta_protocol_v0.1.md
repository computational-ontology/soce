---
title: "SOCE δ-Protocol v0.1"
subtitle: "Graded divergence between independent coders"
author: "Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino"
date: "v0.1.0 · July 2026 · §3 operating procedure: DRAFT pending canonical validation"
lang: en
---

# 1 · The δ scale (canonical)

The δ scale measures how far apart two signatures produced by independent
analysts on the same case are. It is read from the components of Φ = ⟨σ, V, E⟩
from the most superficial to the most structural. **Each grade contains the
previous ones** (a δ₃ divergence is also δ₂ and δ₁): a legitimate ordinal
order by inclusion, not a distance metric. There is no distance between
grades; there is inclusion.

| Grade | Name | What differs between the two signatures | Interpretation |
|---|---|---|---|
| **δ₀** | Convergent | Complete identical signature | No real dissent; spurious bifurcation |
| **δ₁** | Divergent in axis | A single value of V, or one σ state; links and family coincide | Interpretive noise — nuance, not phenomenon |
| **δ₂** | Divergent in link | The state of one or more links (e.g. → vs →ᵐ); dominant link and family coincide | Substantive but contained dissent |
| **δ₃** | Divergent in subgraph | Which link is dominant (⇒) — the causal skeleton reconfigures, within the same family | Two causal readings of the same type |
| **δ₄** | Divergent in family | Different topological families τ for the same case | Maximal structural separation |

**Why this and not a coefficient.** A high inter-rater kappa over an ordinal
object is illusory precision; convergence-of-signature plus versioned dissent
by δ grades is *more* epistemically robust, because it makes auditable where
judgment is genuinely ambiguous instead of hiding it behind a decimal.

# 2 · Arbitration mapping (canonical)

What governs the arbitration recommendation is the δ grade **sustained over
new cases** — never its value on a single case. Stability is read
qualitatively: does the grade get reabsorbed, or does it settle?

| Sustained grade | Reading | Arbitration outcome |
|---|---|---|
| δ₀ – δ₁ | Convergence or reabsorbable nuance | **Collapse to one rule** — one reading wins, the other is re-signed |
| δ₂ – δ₃ | Substantive dissent within the same family; still ambiguous | **Keep in bifurcation**; watch whether it rises to δ₄ or reabsorbs to δ₁ |
| δ₄ + divergent V→I cascade | Different families, divergent recursive closure, no reconciliation | **Promote to permanent theoretical distinction** — or recognise a new mechanism (E7) if the catalogue itself is insufficient |

The decision is human and is itself stored as a meta-level validation act. The
platform does not resolve epistemological dissent — it administers it,
versions it, and preserves the trace of how the expert resolved it. Dissent
opens two rule-branches without stopping the flow (git-branching of dissent);
while arbitration waits, all accumulated signatures remain valid and
consultable.

# 3 · Operating procedure for two coders — **DRAFT, pending validation**

> **Status.** §§1–2 above are canonical (extracted verbatim in substance from
> the project's canonical documents). This section assembles them into a
> step-by-step procedure two coders can execute. It is a **draft
> reconstruction**: it becomes canonical only on explicit approval by the
> project's canonical authority, and until then carries this banner.

1. **Independence.** Both coders produce Φ on the same case, each against the
   documented diagnosis, without communication during coding. Uncertainty
   flags (?) are recorded, not discussed.
2. **Disclosure.** Signatures are exchanged simultaneously, with their
   evidence citations and flags.
3. **Grading.** The pair reads the δ grade of the divergence directly from
   Φ, using the table in §1, at the *highest* applicable grade.
4. **Resolution by grade.**
   - **δ₀** — the case closes; one CVA records convergence.
   - **δ₁** — coders review the single diverging value against the anchor
     rubric and the Anchor Set precedent. If one reading lacks the required
     two independent sources, it yields. If both are sustained, the case
     carries the diverging value with a flag, and the divergence is logged.
   - **δ₂–δ₃** — no forced resolution. Both readings are recorded as branches;
     the case enters the bifurcation register. Subsequent cases are watched
     for reabsorption or escalation.
   - **δ₄** — the case escalates to the senior panel with both full
     signatures, evidence and flags. Outcomes: collapse / promote / recognise
     new mechanism (E7), each stored as a meta-level CVA; E7 triggers
     retrospective re-indexing.
5. **Record.** Every step leaves a trace: the two original signatures are
   never overwritten; resolution produces a *new* validated signature that
   cites both.

**Open design item (inherited, not resolved here).** The operationalisation of
*"sustained"* — how many new cases, and what absence of reconciliation, counts
as stabilisation of a δ grade — is deliberately left qualitative (a
non-reconciliation window), pending definition. It must not be closed by a
count threshold, which would reintroduce through the back door the τ_crit-type
parameter the canon rejected.

# 4 · Machine coders

Two distinct AIs loading the same pack under the same canon are treated as two
coders for exploratory purposes: their divergence is classified on the same δ
scale and under the same jurisprudence as inter-human divergence. This does
**not** alter the two-tier rule: a canonical signature still requires two
trained *human* coders; machine–machine convergence is evidence about the
interface, not a canonical diagnosis.
