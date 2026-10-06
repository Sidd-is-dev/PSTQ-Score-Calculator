# From profile to next step

How a visit to [pstq.getnorthpath.com](https://pstq.getnorthpath.com) moves from inputs to a score, a gate, and a draw comparison.

The result is an **estimate**. It is not an Arrima score, not an eligibility decision, and not an invitation. Official Québec pages win if they disagree. Scoring detail: [SCORING-MODEL.md](SCORING-MODEL.md). Stream gates: [STREAMS.md](STREAMS.md).

---

## 1. Enter the profile

On the [homepage calculator](https://pstq.getnorthpath.com/), the form is grouped in five blocks.

| Step | What you enter | Why it matters |
| --- | --- | --- |
| Who’s applying | Age. Accompanying spouse or common-law partner, yes or no | Age is worth up to 120 points alone, or 100 with a spouse. Several other maximums also change |
| Occupation | TEER category (NOC 2021). Whether the occupation is regulated in Québec. Labour-market diagnosis. Months in that occupation. Professional authorization, if any | Assigns the stream and feeds the diagnosis factor (max 120, **partial** under 48 months) |
| Québec experience and status | Months of work in any occupation in the last 5 years. Months of Québec work. Months resident, working, or studying outside the Montréal metro. Validated job offer. Family member in Québec. Study in Québec without a diploma | Québec-specific factors are worth more than the general work factor. A validated offer is **optional** in all four streams |
| Education | Highest level completed. Diploma obtained in Québec | Both education rows are **partial**. The form says points depend on field of study |
| Language | Oral comprehension, oral production, written comprehension, written production, each level 1 to 12 | French is the only language scored. Levels come from an accepted test within the last 2 years, or an accepted diploma |

The empty form opens on **TEER 3**, not regulated, which the page labels **Stream 2**. That is the initial control state, not a recommendation.

If you do not know your French level, use the [TEF/TCF converter](https://pstq.getnorthpath.com/tools/tef-tcf-to-nclc) for comprehension scores, then type the level into the calculator. The [CLB converter](https://pstq.getnorthpath.com/tools/clb-converter) does not change the PSTQ score.

---

## 2. Stream is assigned, not chosen

The site states that stream is decided mainly by occupation:

- **TEER 0, 1, or 2**, and not regulated → Stream 1
- **TEER 3, 4, or 5**, and not regulated → Stream 2
- **Regulated profession** → usually Stream 3, including when TEER would otherwise suggest Stream 1 or 2
- **Exceptional talent** → separate, self-declared pathway with its own rules

You cannot pick a more favourable stream from a dropdown and have that choice override the occupation rules. The homepage does offer an “All streams” filter and links to each stream landing. Those pages explain gates. They do not replace the occupation rules. See [STREAMS.md](STREAMS.md).

---

## 3. The score is calculated

The running total is shown **out of 1,400**, with subtotals for:

- Who’s applying (age)
- Occupation and diagnosis
- Québec experience and status
- Education
- Language (French)
- Spouse factors

A factor table lists each row with its maximum. Rows the methodology marks partial show an **est.** label. Examples on the live breakdown: education level, and occupational experience × labour diagnosis.

“Highest-impact next steps” lists factors that still have unused points, in the order the page computes for the current answers. On an empty profile the page highlights French (up to 200), a Québec diploma (up to 200), and Québec work experience (up to 160).

---

## 4. Hard gates are checked before the total matters

The calculator prints a gate message when a minimum for the assigned stream is missed. On the default Stream 2 profile with French still at 0, the page says oral French is below the **level 5** minimum and that the point total would not matter until that is fixed.

Gates stated on the stream pages:

| Stream | French gate on the site | Status |
| --- | --- | --- |
| 1 Highly qualified | Oral 7+ and written 5+ | Stated on the stream page. Confirm against the current grid |
| 2 Intermediate and manual | Oral 5+. No written minimum stated | Stated on the stream page |
| 3 Regulated professions | Follows TEER: oral 7+ / written 5+ for TEER 0–2; oral 5+ for TEER 3–5 | Stated on the stream page |
| 4 Exceptional talent | Not stated in the source excerpt the site used | **Partial.** Verify directly |

Other stream conditions (years of experience, diploma type, a permit for Stream 3) are eligibility gates too. The FAQ states you can score well and still be ineligible. Fix a missed gate before treating the estimate as competitive.

---

## 5. Compare with published draws

Under the score, the homepage cites the latest round it has for that stream. With the default Stream 2 profile it cites the **24 September 2026** Stream 2 range **611–706**, and the same round’s other streams (Stream 1 **634–706**, Stream 3 **380–697**, Stream 4 **no score published**).

That comparison is historical. It is not a pass mark for a future round. The full table is on [/draws](https://pstq.getnorthpath.com/draws) and in [DRAWS.md](DRAWS.md).

---

## 6. Next steps the site offers

1. Open the matching [stream landing](https://pstq.getnorthpath.com/calculator/highly-qualified-skills) or [streams guide](https://pstq.getnorthpath.com/guide/pstq-streams) if the gate or TEER is unclear.
2. Open [methodology](https://pstq.getnorthpath.com/methodology) before relying on any row marked partial.
3. Open [draws](https://pstq.getnorthpath.com/draws) instead of assuming a cutoff.
4. Use a [tool](https://pstq.getnorthpath.com/tools) for French levels, NOC/TEER, the PEQ closure, or the CSQ-to-PR sequence.
5. Optionally [request a consultation](https://pstq.getnorthpath.com/#consult) or [book a walkthrough](https://www.getnorthpath.com/contact?intent=walkthrough&tool=pstq-calculator#book).

None of these steps files an Arrima declaration, a CSQ application, or an IRCC application.

---

## Related

- [FEATURES.md](FEATURES.md): full inventory
- [pages/HOME.md](pages/HOME.md): homepage README
- [pages/CALCULATOR.md](pages/CALCULATOR.md): stream landings
