# Scoring model

The PSTQ grid used by [pstq.getnorthpath.com](https://pstq.getnorthpath.com) totals **1,400 points**. The same formula is used in all four streams. Streams change **gates and invitation pools**, not the point table.

Primary source named by the site: the explanatory document for the ministerial order of **20 June 2025** (erratum **9 July 2025**). The methodology page says the explanatory document text was last updated **26 June 2026**.

This page repeats the maxima and the verified/partial labels the site publishes. It does **not** reconstruct intermediate rows the site has not published (for example every age or every month of experience). Where only a maximum is shown, treat the maximum as verified and the path between zero and that maximum as whatever the methodology label says.

Live explanation: [scoring factors](https://pstq.getnorthpath.com/guide/scoring-factors) · [methodology](https://pstq.getnorthpath.com/methodology)

---

## Three sections

| Section | Maximum | What it covers |
| --- | --- | --- |
| Capital humain | 520 | French, age, general work experience, education level |
| Réponse aux besoins du marché du travail | 700 | Occupation and diagnosis, Québec diploma, Québec experience, region, job offer, professional authorization |
| Facteurs d'adaptation | 180 | Study in Québec without a diploma, family in Québec, spouse factors |
| **Total** | **1,400** | |

English language proficiency is **not scored**. The site calls this the main structural difference from the federal CRS and from Ontario’s OINP grid.

When scores are equal, the scoring-factors page says ranking uses the **date and time the expression of interest was submitted**. Earlier wins.

---

## Status labels

The methodology page defines two labels, and the calculator shows them in the interface.

| Label | Meaning on the site |
| --- | --- |
| **Verified** | The exact point table came from the primary points document. Nothing is approximated. |
| **Partial / estimate** | The source gave a range, an endpoint, or a level band rather than a complete table. The calculator uses a stated approximation and flags it. |

A third label appears only on the CLB tool: **unverified**. That table is not part of the PSTQ score. See [TOOLS.md](TOOLS.md).

---

## Capital humain (max 520)

| Factor | Max, principal alone | Max, with spouse | Status |
| --- | --- | --- | --- |
| Knowledge of French, 4 competencies | 200 | 160 | Verified |
| Age | 120 | 100 | Verified |
| Work experience, any occupation, last 5 years | 70 | 50 | Verified |
| Education level | 130 | 110 | **Partial** |

French is read on the **Échelle québécoise des niveaux de compétence en français**, levels **1 to 12**, from an accepted test taken within the **last 2 years**, or an accepted diploma. The calculator scores four competencies: oral comprehension, oral production, written comprehension, and written production. The homepage states a maximum of **50 points per competency** alone, or **40 with a spouse** (4 × 50 = 200, 4 × 40 = 160).

The FAQ states that age points peak between **20 and 30** and decline to **zero at 45**. The site does not publish the full age table in the public guide, so this hub does not invent the points for each year.

Education is partial because points depend on a **separate field-of-study list**. The calculator uses the **midpoint of the published level range**. The form tells you to see the methodology.

---

## Réponse aux besoins du marché du travail (max 700)

| Factor | Max shown | Status | What the site says is approximated |
| --- | --- | --- | --- |
| Occupational experience × labour-market diagnosis | 120 | **Partial** | Only the ≥48-month and <12-month endpoints are confirmed. Months in between are **linearly interpolated**, not taken from a published row |
| Diploma obtained in Québec | 200 | **Partial** | 6 of about 15 published level rows were retrieved. The graduate row uses a midpoint of a range |
| Work experience in Québec | 160 | Verified | None |
| Residence outside the Montréal metro area | 40 | Verified | None |
| Work experience outside the Montréal metro area | 60 | Verified | None |
| Study duration outside the Montréal metro area | 20 | Verified | None |
| Validated job offer | 50 | Verified | None at the factor level. The form states **50 outside Montréal** and **30 inside** |
| Professional authorization or recognition | 50 | Verified | None |

Regional points are for residence, work, and study **outside** the Montréal metropolitan area. At the maximum month bands those three rows sum to **120** (40 + 60 + 20). They are not an automatic 120 for naming a region. See [REGIONS.md](REGIONS.md).

A validated job offer is **optional in all four streams**.

The diagnosis control on first load shows **Léger déficit (slight shortage)** and the note “Interpolated under 48 months.” The site tells you to confirm the NOC 2021 code against the official diagnosis list. This hub does not list diagnosis categories that are not visible without opening the control.

---

## Facteurs d'adaptation (max 180)

| Factor | Max | Status |
| --- | --- | --- |
| Studied in Québec without completing a diploma | 30 | Verified |
| Family member already in Québec | 10 | Verified |
| Spouse’s knowledge of French | 40 | **Partial** |
| Spouse’s age | 20 | **Partial** |
| Spouse’s work experience in Québec | 30 | Verified |
| Spouse’s level of education | 20 | **Partial** |
| Spouse’s diploma obtained in Québec | 30 | **Partial** |

Spouse French, age, education, and Québec diploma are partial because per-competency or per-year tables were **not fully retrieved**. The calculator uses simplified proportional estimates.

Spouse factors apply when you indicate an accompanying spouse or common-law partner. That choice also lowers several principal-applicant maximums in Capital humain, as in the table above.

---

## What the program does not score

- English test results (IELTS, CELPIP, or otherwise)
- A promised cutoff such as “600 points means invited”
- Express Entry CRS points. A CSQ is not a provincial nomination

---

## How to read a result

1. If a **hard gate** is missed, the site says the point total does not change the outcome until the gate is fixed. See [WORKFLOW.md](WORKFLOW.md).
2. Treat rows marked **est.** or **partial** as approximations, not as Arrima’s official cell.
3. Compare the total with a **published round** for the same stream, not with a pass mark that was never published. See [DRAWS.md](DRAWS.md).
4. Re-check [quebec.ca](https://www.quebec.ca/en/immigration/permanent-workers/skilled-worker-selection-program) before you rely on a number for an application.

The Gazette officielle text of the ministerial order is listed on the methodology page as the underlying legal instrument, with status **not yet paginated / cited exactly**. This hub does not invent a gazette citation.
