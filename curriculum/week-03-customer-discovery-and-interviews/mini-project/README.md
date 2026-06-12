# Mini-Project — The Discovery Dossier

> Assemble your interviews and synthesis into a single, version-controlled **Discovery Dossier**. This is the evidence base for your entire startup concept and the part investors and demo-day judges trust most — because real quotes and real numbers from real customers cannot be faked. You start it this week with **five interviews and a synthesis**, and you grow it to **ten or more** by the Week 10 capstone, where it is worth **25% of the final rubric** — the single largest line item.

**Estimated time:** ~8 hours this week (the interviews themselves, plus recruiting, write-ups, and synthesis). Field work spikes in Week 3 exactly as the syllabus promises.

---

## Where this sits in the course

The dossier is the spine of C25. Almost everything downstream feeds on it:

- **Week 1** gave you a problem space you have standing in.
- **Week 2** gave you one triaged idea and your kill criteria.
- **Week 3 (now)** turns that idea into *evidence* — or honestly kills it.
- **Week 5** picks your riskiest assumption (straight out of this dossier) and builds the smallest test of it.
- **Week 6** seeds pricing and CAC from your "what do you pay today" answers.
- **Week 10** synthesizes ≥10 interviews into the pitch's evidence slide.

If you pivot or drop this week, you re-run discovery on the next idea — the dossier *process* is permanent even if a given idea isn't. This is the founder habit you keep for the life of the company.

---

## What you will produce

A folder `discovery-dossier/` in your Week 3 repository, containing:

```
discovery-dossier/
├── interview-script.md            (from Exercise 1)
├── recruiting-tracker.md          (your funnel: who, segment, status, date)
├── interviews/
│   ├── interview-01.md            (Exercise 2 template, filled)
│   ├── interview-02.md
│   ├── interview-03.md
│   ├── interview-04.md
│   └── interview-05.md            (five this week; grows to ten+ by capstone)
└── dossier/
    └── SYNTHESIS.md               (from Exercise 3, ending in a decision)
```

Each piece is a real artifact you'll reuse and extend, not a one-time deliverable.

### 1. The recruiting tracker

A simple table that proves you ran a funnel, not a scramble. One row per prospect:

| # | Segment / role (no name) | Source | Status | Date | One-line takeaway |
|---|--------------------------|--------|--------|------|-------------------|
| 1 | office mgr, indie clinic | warm | done | 2026-06-15 | empty-slot pain > no-shows |
| 2 | clinic mgr | referral I-1 | scheduled | 2026-06-18 | — |
| 3 | front-desk | community | no-show | — | — |

This is also where your "contact 15–20 to land 5" reality lives. Showing the no-shows and the no-replies is *good* — it proves the funnel is real.

### 2. Five interview write-ups

One file per interview, using the [Exercise 2 template](../exercises/exercise-02-interview-writeup-template.md). Each must:

- Use a **role/segment**, never a private identifier.
- Contain at least one **verbatim quote** of the problem in the customer's words.
- Tell a **specific last-time story**, not a generic average.
- Capture the **current workaround and spend**.
- Note **signal** honestly (commitment, or "just politeness").
- Be written the **same day** as the interview.

### 3. The synthesis

`dossier/SYNTHESIS.md`, completed with the [Exercise 3 canvas](../exercises/exercise-03-synthesis-and-pattern-canvas.md):

- The **segment(s)** you talked to and **how many** of each.
- The **problem in customers' words**, with quotes.
- **Frequency and cost evidence**, with counts and numbers where you have them.
- The **dominant workaround** (your de facto competitor and spec).
- **Surprises**, and whether any suggests a pivot.
- A **kill-criteria check** (each Week 2 criterion, tripped or not, with evidence).
- An explicit **persevere / pivot / drop** decision with reasoning.

---

## Acceptance criteria

- [ ] `discovery-dossier/` exists in your Week 3 repo and is committed.
- [ ] `interview-script.md` present (the de-biased script from Exercise 1).
- [ ] `recruiting-tracker.md` shows a real funnel — including the people who didn't reply or didn't show.
- [ ] `interviews/` contains **at least five** write-ups this week.
- [ ] **Every** write-up follows the Exercise 2 structure and contains **no private identifiers**.
- [ ] At least **three** of the five interviews used a genuine **past-behavior** question that produced a specific story (the quotes prove it).
- [ ] `dossier/SYNTHESIS.md` exists with **counted** themes (independent mentions), the workaround, and surprises.
- [ ] **Every** Week 2 kill criterion is explicitly checked against the evidence.
- [ ] A clear **persevere / pivot / drop** decision with reasoning.
- [ ] No interview is a pitch in disguise — there is **no mockup, demo, or solution** shown in any write-up.

---

## Suggested order of operations

You'll finish this far more calmly if you front-load recruiting.

### Monday — script + recruiting (start the funnel)
- Finish [Exercise 1](../exercises/exercise-01-build-and-debias-your-script.md): your de-biased script.
- Build `recruiting-tracker.md`. List 15–20 prospects across warm network, communities, and cold-but-relevant.
- Send outreach to all of them today. Attach a self-booking link if you can.

### Tuesday — confirm + drill
- Chase replies; aim to have ≥5 interviews booked across the week.
- Do a role-play run of your script with a cohort-mate; tighten any question that drifts toward a pitch.

### Wednesday–Friday — run interviews + same-day write-ups
- Run interviews 1–5 across these days. After **each one**, immediately fill an Exercise 2 write-up.
- End every interview with the referral ask — it refills your funnel toward ten.
- Update the tracker as you go.

### Saturday — synthesis deep work
- Lay out every finding (sticky notes / Miro / FigJam). Cluster into themes.
- Complete Parts A–F of the [Exercise 3 canvas](../exercises/exercise-03-synthesis-and-pattern-canvas.md): findings → themes → signal table → frequency×severity → workaround → surprise.

### Sunday — the decision
- Complete Parts G–H: check **every** kill criterion, then make the explicit persevere/pivot/drop call with reasoning.
- Commit the whole `discovery-dossier/`. Take the [quiz](../quiz.md).

---

## What "great" looks like vs. "passing"

| Dimension | Passing | Great |
|-----------|---------|-------|
| Interviews | 5 done, written up | 5+ with vivid verbatim quotes and specific costs ($/hours) |
| Bias | Mostly past-behavior questions | Zero pitches; you can show where an interview *threatened* the idea |
| Workaround | Named | Named precisely enough to be a product spec |
| Synthesis | Themes listed | Themes *counted* (independent mentions), frequency≠severity, surprise named |
| Kill criteria | Mentioned | Each checked as-written; goalposts not moved |
| Decision | Stated | Falls cleanly out of the cited evidence; next test named |

---

## Rubric

| Criterion | Weight | What earns full marks |
|-----------|------:|-----------------------|
| Interviews use **past behavior, not pitches** | 30% | Quotes show real last-time stories; no solution shown anywhere |
| Synthesis is **honest** — patterns counted, not cherry-picked | 25% | Independent-mention counts; threatening data acknowledged |
| **Kill criteria** are actually checked | 20% | Each Week 2 criterion evaluated as written, with evidence |
| The **workaround and surprises** are identified | 15% | Dominant workaround named precisely; surprise stated honestly |
| The **decision** (persevere/pivot/drop) is justified | 10% | Explicit, specific, and follows from the evidence cited |

A **drop** decision earns full marks when the reasoning is rigorous. The grade rewards honest method, not whether your idea survived.

---

## How this grows toward the capstone

You will add interviews in Weeks 4–9, toward **ten or more**, refining your script and re-running synthesis as the picture sharpens. At the capstone the dossier is graded again — expanded, with ≥10 interviews synthesized into a defensible (not cherry-picked) pattern, worth **25%** of the final rubric. The real numbers you collect now (what a no-show costs, what they pay a temp agency, how long the manual workaround takes) become the evidence slide judges trust most. Start strong; future-you is grateful.

---

*Next: [Week 4 — Co-founders, Roles, Equity & Vesting](../../week-04-cofounders-roles-equity-and-vesting/). Bring your five write-ups and your decision; discovery continues toward ten while the course turns to team and money.*
