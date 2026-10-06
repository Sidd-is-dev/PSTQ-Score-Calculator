# What the PSTQ Score Calculator does

**PSTQ Score Calculator** is a free website that estimates a Québec skilled-worker selection score out of **1,400 points**, shows which stream the profile falls into, flags hard minimums, and compares the estimate with published Arrima invitation ranges.

Live: [pstq.getnorthpath.com](https://pstq.getnorthpath.com)

It is a focused public product: a calculator, stream landing pages, guides, tools, occupation notes, region notes, a draw history, an FAQ, and a methodology page. It is **not** Arrima, and it does not file a CSQ or a permanent-residence application. Broader GetNorthPath context is in [ABOUT.md](../ABOUT.md).

---

## Problem it solves

Québec’s skilled-worker grid is easy to misread:

- The total is **1,400 points**, not the federal CRS total
- **Only French** is scored
- **Four streams** share one point formula and differ by eligibility gates and invitation pools
- A missed **hard gate** makes the point total irrelevant until it is fixed
- There is **no fixed pass mark**. Invitation ranges are published after each round and move by stream
- The **PEQ closed** to new applications in November 2025. Québec experience and diplomas still score points. They no longer bypass Arrima

Generic “Québec points” pages often mix eligibility, ranking, and a promised cutoff. This product separates those questions and cites the grid it uses.

---

## Who it is for

- Skilled workers estimating a PSTQ score for Arrima
- Applicants who need to know whether they are in Stream 1, 2, 3, or 4
- People converting a TEF Canada or TCF Canada comprehension score into Québec’s 1–12 French scale
- People who had been planning a PEQ application and now need the PSTQ path
- Readers comparing Montréal metro settlement with regions outside the Communauté métropolitaine de Montréal (CMM)

---

## Product surfaces

```
pstq.getnorthpath.com
├── Home / calculator     profile form, score, gates, factor breakdown
├── Stream landings       /calculator/… for streams 1 to 4
├── Guides                program, streams, scoring, PEQ, documents
├── Tools                 French level, CLB reference, NOC/TEER, PEQ, CSQ timeline
├── Occupations           six occupation profiles
├── Regions               six region profiles
├── Draws                 2026 Arrima rounds
├── FAQ                   scoring vs eligibility and related questions
├── Methodology           sources and verified vs partial factors
└── French                same public routes under /fr/…
```

Details: [FEATURES.md](FEATURES.md) · [WORKFLOW.md](WORKFLOW.md) · [SCORING-MODEL.md](SCORING-MODEL.md)

---

## User journey

1. Open the [calculator](https://pstq.getnorthpath.com/). No account is required.
2. Enter age and whether an accompanying spouse or common-law partner is included. Those choices change several maximums.
3. Enter TEER (NOC 2021) and whether the occupation is regulated in Québec. That assigns the stream.
4. Enter labour-market diagnosis, Québec experience, education, and French levels on the Échelle québécoise (1 to 12).
5. Read the estimate, the hard-gate message, the factor breakdown, and the comparison with the latest published round.
6. Optionally open a guide, a tool, an occupation or region page, or the draw history.
7. Optionally request a consultation. The form attaches the current score and stream. See [PRIVACY.md](PRIVACY.md).

---

## Estimate, eligibility, threshold, decision

| | Estimate | Eligibility | Invitation threshold | Official decision |
| --- | --- | --- | --- | --- |
| **Question** | How many points does this profile score on the published grid? | Does the person meet stream conditions and hard minimums? | What range did a past round actually invite? | Will Québec invite, issue a CSQ, or will IRCC grant PR? |
| **Who answers** | This calculator, as an independent estimate | Stream rules. The calculator flags gates it knows. It does not issue eligibility | MIFI, after each round, on quebec.ca | MIFI, then IRCC |
| **What a high number means** | Higher rank potential in Arrima | Nothing by itself. A high score can still be ineligible | Nothing about a future round | Nothing binding |

The live disclaimer on the calculator: **independent estimate; not an official Arrima score, not eligibility, not legal advice.**

---

## What it is

- A **sourced points estimate** against the PSTQ grid of 20 June 2025 (erratum 9 July 2025)
- A **content site** for streams, factors, tools, occupations, regions, draws, and FAQ
- A **gateway** to an optional GetNorthPath walkthrough
- Available in **English and French** (French at `/fr/…`)
- Free. No account is required to calculate

## What it is not

- Not an official Québec, MIFI, Arrima, or IRCC tool
- Not a guarantee of an invitation, a CSQ, or permanent residence
- Not legal advice
- Not a substitute for the current requirements page for your stream
- Not Express Entry, and a CSQ is not a provincial nomination that adds CRS points
- Not a remaining PEQ application route

---

## Accuracy stance

| Source | Role |
| --- | --- |
| Points document, ministerial order of 20 June 2025 | Every point value the calculator treats as verified |
| Guide des procédures d'immigration, ch. 3 §1 | Stream definitions, TEER mapping, hard gates |
| Québec requirements pages | Per-stream requirement wording |
| Arrima invitations for 2026 | Dates, streams, invitation counts, score ranges |
| Gazette officielle text of the order | Underlying legal instrument. The methodology page says this is **not yet paginated or cited exactly** |

Factors the site cannot confirm cell by cell are labeled **partial** in the calculator and in [SCORING-MODEL.md](SCORING-MODEL.md). They are not presented as exact official rows.

If this site and quebec.ca or canada.ca disagree, **the government page wins**.

---

## Limitations

- Education level, Québec diploma, occupational-experience × diagnosis, and several spouse factors are **partial**. See [SCORING-MODEL.md](SCORING-MODEL.md).
- The Stream 4 French gate is **not stated** in the source excerpt the site used. Verify it directly.
- The NOC/TEER finder covers **common occupations**, not the full NOC 2021 structure.
- The CLB table is marked **unverified** on the site and does not affect the PSTQ score.
- Occupation pages do not publish a NOC code. Confirm the code on the official NOC.
- Draw history is only what Québec has published and the site has transcribed, through **24 September 2026** at the time of this writing. Later rounds will not appear here until the live page is updated.
- The document checklist is a **general preparation list**, not the official MIFI checklist.
- The CSQ timeline tool **does not state a number of months** for IRCC processing.

---

## Privacy

The consultation form collects a name, an email, an optional phone number, and the score and stream already on screen. The site says it uses that information to contact you about PSTQ options and will follow up by email. Policy text lives on GetNorthPath’s privacy page. See [PRIVACY.md](PRIVACY.md).

---

## Related GetNorthPath pages

| Page | Job |
| --- | --- |
| **PSTQ Score Calculator** (this) | Free Québec skilled-worker estimate and explainers |
| **GetNorthPath** | Parent site |
| **Walkthrough** | Optional call booked from the parent contact page |

© 2026 GetNorthPath. Not affiliated with MIFI, the Gouvernement du Québec, or IRCC.
