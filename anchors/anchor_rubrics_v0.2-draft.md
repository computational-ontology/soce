---
title: "SOCE Anchor Rubrics v0.2 — DRAFT"
subtitle: "Todorov axes procedure: proposed revisions for canonical validation"
author: "Luis Bourguet · LabOnt — Centre for Ontology, Università degli Studi di Torino"
date: "DRAFT · 2026-10-19 · pending canonical validation against the Anchor Set"
lang: en
---

> **Status.** This file is a **draft** revision of §1 of `anchor_rubrics_v0.1.md`
> ("Todorov axes — procedure"). Nothing in it is canonical. It was prepared under
> the governing principle — *la IA propone, el humano decide* — from an
> AI-assisted review of the v0.1 deposit, the external expert Pilot 01 and the
> constitutional application of the axes in the *Otherness in Constitutions*
> study. Each proposal states its evidence and its compatibility with the canon
> (qualitative-ordinal notation; no averaging, summing or weighting; two-tier use
> rule). Proposals marked **patch** do not touch the notation and could enter as
> v0.1.1; proposals marked **v0.2** change the rubric and require validation
> against the eleven corpus cases before release. The v0.1 text remains the
> operative canon until then.

# 0 · Source passage (added)

The v0.1 rubric names Todorov but does not quote him. The passage on which the
three axes rest, in the Spanish edition used by the project:

> «…la relación con el otro no se constituye en una sola dimensión. Para dar
> cuenta de las diferencias existentes en la realidad, hay que distinguir por lo
> menos tres ejes, en los que se puede situar la problemática de la alteridad.
> Primero hay un juicio de valor (un plano axiológico): el otro es bueno o malo,
> lo quiero o no lo quiero, o bien, como se prefiere decir en esa época, es mi
> igual o es inferior a mí […]. En segundo lugar, está la acción de acercamiento
> o de alejamiento en relación con el otro (un plano praxeológico): adopto los
> valores del otro, me identifico con él; o asimilo al otro a mí, le impongo mi
> propia imagen; entre la sumisión al otro y la sumisión del otro hay un tercer
> punto, que es la neutralidad, o indiferencia. En tercer lugar, conozco o ignoro
> la identidad del otro (éste sería un plano epistémico); evidentemente no hay
> aquí ningún absoluto, sino una gradación infinita entre los estados de
> conocimiento menos o más elevados. Claro que existen relaciones y afinidades
> entre estos tres planos, pero no hay ninguna implicación rigurosa; por lo
> tanto, no se puede reducir uno a otro, ni se puede prever uno a partir del
> otro.»
>
> — Tzvetan Todorov, *La conquista de América. El problema del otro*, trad.
> Flora Botton Burlá, México: Siglo XXI, 1987, p. 195 (ch. 4 «Conocer», §
> «Tipología de las relaciones con el otro»). Original: *La conquête de
> l'Amérique. La question de l'autre*, Paris: Seuil, 1982.

Two canonical rules are Todorov's own: the **dissociation rule** («ninguna
implicación rigurosa») and the **gradation** of the epistemic axis («gradación
infinita»), which licenses an ordinal scale with anchored endpoints.

# 1 · Procedure (revised)

## 1.0 Step 0 — identify the We and the Other(s)  [patch]

Before any axis is read, the analyst records (a) the **We** as inscribed in the
case (the "people", the nation, the citizen body) and (b) each **Other** the
case produces, with the inscription that names it. An Other that the sources
never name is recorded as *unnamed* and read by exclusion from the We; an
unnamed Other defaults to a high ep value **with an uncertainty flag**, because
absence of naming is evidence about ep, not absence of evidence.

*Evidence.* Pilot 01, Case B recorded two Others (Rohingya; Muslims more
broadly); Case 9 (MAGA) carries an open flag on an internal "communist" Other;
constitutional texts routinely institute several Others (foreigner, minority,
indigenous people, religious or linguistic group, ideological enemy).

## 1.1 One vector per Other  [patch]

V is written **per Other**: V_O = (ax, px, ep) for each Other identified in
Step 0. The **case vector** is the vector of the Other that activates the
highest px; the identifier of that Other is annotated beside it. Vectors of
different Others are never averaged, summed or merged.

## 1.2 Reading window and transitions  [v0.2]

Each V_O is read for a stated **window** (date range; territory). Where the
case spans several phases, the analyst writes one vector per window and marks
transitions with the arrow diacritic already used for σ (e.g. `px 3→4`). The
"highest affirmative value" rule applies **within a window**, not across the
whole history of the case.

*Evidence.* Pilot 01 (Case B): "underrepresenting phase dynamics of
displacement and the changing political-military context".

## 1.3 Two independent sources — definition of independence  [patch]

Sources are classed:

| Class | Content |
|---|---|
| **S1** | Primary inscription: constitution, statute, decree, treaty, official programme |
| **S2** | Institutional record: judgment, census, administrative file, parliamentary record |
| **S3** | The Other's own voice: testimony, the Other's own documents, its language in the record |
| **S4** | Third-party documentation: international bodies, NGOs, scholarship, press |

Two sources are **independent** when they belong to **two different classes**.
Two citations of the same documentary chain (a statute and the gazette that
publishes it; a report and the press that summarises it) count as one source.

For **ep**, at least one S3 source is required — **or the documented absence of
any S3 source**, which is itself evidence for ep 4–5★ and must be recorded as
such.

## 1.4 Ascending questions; the thermometer is a maximum, not a ladder  [patch]

px is the **highest level activated**. Levels are not assumed cumulative: a
case may activate px 4 without px 3 (Jim Crow: segregation and impunity
without expulsion). A **skipped step** is recorded as a diagnostic flag
(`px 4 · step 3 = no`); it is information about the case, not an error.

## 1.5 Inscribed and enacted readings  [v0.2]

Where the sources allow, each axis receives two readings:

- **V_inscribed** — read from S1/S2: what the record institutes;
- **V_enacted** — read from S3/S4: what is done.

Their dissociation is diagnostic in the same sense as the dissociation between
axes: a px_inscribed of 3 with a px_enacted of 4 is the signature of structural
impunity; a px_inscribed of 1 with a px_enacted of 2 is the signature of a
record that promises what practice withholds. The codebook's requirement to
distinguish text from practice and validity from efficacy applies to V.

## 1.6 Registry field for documental activations  [v0.2]

px 3 ("active de-inscription") and ep 5★ ("erasure of the Other's own
knowledge") are Node I phenomena. When either is activated by documental means
the analyst records a nominal **registry** field: *which* registry (nationality,
civil status, census, residence/padrón, electoral roll, land, archive, language
register), *who controls it*, and *what condition* it imposes on inscription.
This operationalises the shortcut I→V ("de-inscription is already production of
the Other") inside the V layer, without tensors.

## 1.7 Brake field  [v0.2]

The corpus finding that the economic limit brakes px below 5 (τ₂) enters V as
a nominal field **brake** ∈ {economic, institutional, international, none},
parallel to the modulated link →ᵐ in E. It records *why* px stopped where it
did; it adds no magnitude.

## 1.8 Bounded uncertainty flag  [patch]

The uncertainty flag (?) may be **bounded** between two adjacent values
(`px 2?3`). A bounded flag is still ordinal; it lets the δ-scale distinguish
adjacent-value doubt (δ₁ noise) from wide divergence. Unbounded (?) remains
available for readings the rubric cannot locate at all.

*Evidence.* Pilot 01, §4-b: hesitations concentrated on adjacent distinctions.

## 1.9 V-screen  [patch]

A **V-screen** — the three axes alone, per Other, with sources and flags — is an
admissible *exploratory* output (first tier) and the recommended first pass
before a full signature Φ. It does not alter the two-tier rule.

*Evidence.* Pilot 01, §4-c: ~3 h against a ~90-minute target.

# 2 · Praxeological axis px — the thermometer (unchanged from v0.1)

| px | Boundary descriptor | Activation question |
|---|---|---|
| **1** | Assimilation: the Other can become Us | Is there an institutional path to full rights through integration? |
| **2** | Soft segregation: separated but tolerated | Is there systematic separation without expulsion or elimination? |
| **3** | Expulsion or physical/legal confinement | Is there deportation, internment, or active de-inscription? |
| **4** | Systematic violence with structural impunity | Is physical violence institutionalised, not episodic? |
| **5** | Physical elimination of the group as such | Is there an elimination policy with planning or mass outcome? |

**Duration criterion for px 4 (proposed, v0.2).** "Institutionalised, not
episodic" is satisfied when violence against the Other recurs across at least
two cycles of the relevant record (two reporting years, two electoral cycles,
two census rounds) without sanction of the perpetrators recorded in S2.

# 3 · Axiological axis ax — full rubric (proposed, v0.2)

v0.1 fixes the endpoints and declares the intermediate descriptors "a declared
expansion for a later codebook version". The following descriptors are proposed
for validation against the Anchor Set; until validated, intermediate values
continue to cite the precedent on which they lean.

| ax | Boundary descriptor | Activation question |
|---|---|---|
| **1** | The Other valued as equal | Is equal worth, with equal rights, affirmed without a condition of identity? |
| **2** | Inferior but redeemable: tutelage, "protection", civil minority | Is the Other valued as an object of care or correction rather than a full subject? |
| **3** | Inferior by nature or culture: a non-redeemable hierarchy | Is a difference of worth affirmed that integration does not erase? |
| **4** | Threat to goods or order: competitor, burden, danger | Is the Other named as the cause of concrete ills (jobs, housing, security, cohesion)? |
| **5** | Existential threat | Is it affirmed that the We cannot exist while the Other exists among it? |

Precedents on record: EU 2015 ax = 3; MORENA ax = 4 (registry); Apartheid ax = 3;
Rohingya ax = 5 (Pilot 01, exploratory).

# 4 · Epistemic axis ep — full rubric (proposed, v0.2)

| ep | Boundary descriptor | Activation question |
|---|---|---|
| **1** | Own voice: the Other's categories and language enter the record | Does the Other appear in its own words in the inscription? |
| **2** | Translated voice: heard through interpreters or representatives, in our categories | Is there consultation or representation, but in the We's vocabulary? |
| **3** | Known only through our categories: counted, classified, voiceless | Does the Other exist in the record only as an administrative category? |
| **4** | Stereotype replaces knowledge: available evidence about the Other is ignored | Is a fixed image of the Other maintained against evidence on record? |
| **5★** | Erasure of the Other's own supports: language, archives, institutions destroyed | Have the means by which the Other could re-inscribe itself been destroyed? |

Precedents on record: EU 2015 ep = 3; MORENA ep = 4 (registry); Apartheid ep = 2;
Rohingya ep = 4 (Pilot 01, exploratory). The 5★ marker keeps its v0.1 meaning:
the level at which resistance takes generations to rebuild.

# 5 · V-profiles — a catalogue with precedents (proposed, v0.2)

As the families τ are read from E, **V-profiles** are read from V. Each profile
must cite at least one Anchor case; a vector that fits no profile is a signal of
a theoretically productive case, exactly as for τ.

| Profile | Pattern | Precedent |
|---|---|---|
| **elite-Other** | ax ≥ 4 with px ≤ 2 | MORENA (4·2·4) |
| **protected-but-unknown** | ax 1 with ep ≥ 3 | *to be validated* (equality clauses that never name the Other) |
| **assimilationist** | px 1 with ep 3–4 | *to be validated* (integration mandates) |
| **exterminatory** | ax 5 · px 5 · ep 5★ | Nazi; Rohingya (5·4·4 exploratory) |
| **benevolent erasure** | ax 1–2 with ep 5★ | *to be validated* (missionary and colonial tutelage) |

# 6 · What is not changed

The notation remains qualitative-ordinal; no field introduced here is a
magnitude (registry, brake and profile are nominal; windows and bounded flags
are ordinal). The two-tier use rule, the governing rule (*if it cannot be read
from an existing diagnosis, it does not enter the notation*) and the δ-protocol
are untouched.

# 7 · Validation plan for this draft

1. Publish the eleven V vectors of the corpus registry with their evidence
   citations (currently only EU 2015 and MORENA are on record) — prerequisite
   for any external coder to "read against Anchor Set precedents".
2. Re-read the eleven cases with §§3–4; record every value that the new
   descriptors change, and why.
3. Run a two-coder V-screen on two cases outside the corpus (one constitutional
   text, one movement) and grade divergence on the δ-scale.
4. Promote to v0.2 only the proposals that survive 1–3; the rest remain draft.
