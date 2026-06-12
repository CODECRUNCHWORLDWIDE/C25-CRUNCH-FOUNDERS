# Mini-Project — Your Lean Canvas + Unit-Economics Sheet

> Produce a one-page **lean business model canvas** and a **unit-economics sheet** for *your own* startup concept, every assumption stated, with a base/worst/best sensitivity analysis and an honest one-sentence verdict. This is not a throwaway exercise — both artifacts are **capstone deliverables** (the syllabus capstone rubric weights "lean canvas + unit economics, internally consistent and assumption-stated" at 15%), and you will defend the numbers in your Week 10 pitch. Build it to last. No code.

**Estimated time:** ~13 hours across Friday, Saturday, and Sunday in the suggested schedule. It compounds directly on Weeks 1–5: it uses the *customer and problem* you validated in discovery (Weeks 2–3), the *solution* you tested in your MVP (Week 5), and it produces the *model* that Week 7's go-to-market and Week 10's pitch both stand on.

---

## Where this sits in the course

```
Week 2–3  Discovery: a real problem + a specific customer  ──┐
Week 5    MVP: a tested solution + persevere/pivot decision  ─┤
                                                              ▼
Week 6  ►  CANVAS (the business story) + UNIT ECONOMICS (does it make money?)
                                                              │
Week 7     Go-to-market: validate the CAC assumption for real ◄┘ (your Week 6 CAC becomes Week 7's number to test)
Week 8     Fundraising: your unit economics decide if/when to raise
Week 10    Pitch: you defend this model live, in 3 minutes
```

This is the week your idea stops being "a thing people want" and becomes "a thing that could be a company." If your discovery and MVP work was honest, this week will either confirm a business is there or reveal — early and cheaply — that it isn't. Both outcomes are wins.

---

## What you will produce

A folder in your Week 6 repo with three artifacts:

### 1. `canvas/CANVAS.md` — the lean canvas

All nine lean-canvas blocks (Problem, Customer Segments, Unique Value Proposition, Solution, Channels, Revenue Streams, Cost Structure, Key Metrics, Unfair Advantage), single-line answers, with:

- The **weakest block flagged** as your riskiest business-model assumption, plus how you'll test it.
- A **revenue model chosen** and defended (subscription / transactional / take-rate / usage / freemium-into-one / hybrid).
- A **starting price** with one sentence of value-based reasoning.

(This is your Exercise 2 worksheet, brought up to final quality.)

### 2. `unit-economics/` — the sheet

A **real spreadsheet** (Google Sheets / Excel / Numbers / LibreOffice) — export it as CSV *and* drop a screenshot or PDF into the folder so it's readable in the repo without opening a spreadsheet app. It must compute, with every input assumption-labeled:

- **Contribution margin** ($ and %), variable costs itemized.
- **CAC**, fully loaded (founder/team time included and shown).
- **LTV**, on *contribution*, tied to an explicit churn/retention figure.
- **LTV:CAC** ratio.
- **CAC payback period** (in months).
- A **base / worst / best sensitivity table** — at minimum a worst case where your scariest variable moves the wrong way (e.g., CAC doubles, or churn doubles), recomputed.

(This is your Exercise 3 sheet, finalized.)

### 3. `unit-economics/VERDICT.md` — the honest verdict

A short write-up (½–1 page) containing:

- The **one-sentence verdict** in the required shape: *"This model makes money at scale if and only if `<X>` holds; if it doesn't, it breaks because `<Y>`."*
- The **single most fragile assumption** named, and *why* it's the one that matters most (from your sensitivity table).
- A plain-English answer to: **can this make money at scale, and what would have to be true?**
- One sentence on **what you'll do about it** (which assumption you'll go validate first — this becomes a Week 7 input).

---

## Rules

- **Use your real concept**, the one you've carried since discovery. Don't invent a clean fictional company to make the math easy — the point is to test *your* idea.
- **Every number gets an assumption.** A naked number is an automatic deduction. "Churn is 5%" → "Churn is 5%/month because that's what comparable early SaaS tools report and matches the two power users I interviewed."
- **LTV on contribution, never revenue.** This is the line most likely to fail review.
- **CAC includes founder time.** If you'd sell by hand, price your hours into CAC.
- **The sheet must be a real spreadsheet** (so the grader — and future you — can change an input and watch the ratio move), not numbers typed into prose. Markdown tables are fine for the *canvas* and *verdict*; the *economics* must live in a sheet.
- **Internal consistency matters.** The price in your canvas must equal the price in your sheet. The variable costs in your Cost Structure block must equal the ones in your contribution-margin calc. Graders check this.

---

## Suggested order of operations

You'll find it easier to build incrementally than to stare at a blank sheet.

### Phase 1 — Finalize the canvas (~2h)

Take your Exercise 2 worksheet and tighten every block. Kill the "everyone" customer segment. Make the value prop an outcome, not a mechanism. Make sure every Solution feature traces to a Problem line. Commit `canvas/CANVAS.md`.

### Phase 2 — Pull the inputs (~1.5h)

From the canvas, extract into your spreadsheet's Inputs section: price, each variable cost, churn, and each CAC component. For each, write the assumption — and where the assumption *comes from* (an interview? a comparable company? a guess you'll test?). The honesty of this phase determines the honesty of everything downstream.

### Phase 3 — Compute the core five (~2h)

In the spreadsheet, build the formulas (not hard-coded numbers, so sensitivity works):

- `Contribution margin = Price − SUM(variable costs)`
- `Lifetime = 1 / monthly churn`
- `LTV = Contribution margin × Lifetime`
- `LTV:CAC = LTV / CAC`
- `Payback = CAC / Contribution margin`

Sanity-check each against the rules of thumb. If LTV:CAC is wildly high (>10:1), suspect underpricing or honeymoon-churn and dig in.

### Phase 4 — Sensitivity (~2h)

Build the base/worst/best columns. Move your scariest variable to a pessimistic-but-plausible value and recompute. Identify the single variable that breaks the model fastest. This is where the real learning happens — most founders discover their fragility is *retention*, not what they assumed.

### Phase 5 — Verdict + peer review (~3h)

Write `VERDICT.md`. Then — Sunday's peer review — swap sheets with another founder and run the "assumption hunt": find the one assumption in *their* model that, if wrong, breaks everything, and let them do the same to yours. Fix what the review exposes. Commit.

### Phase 6 — Polish (~2.5h, incl. weekend deep work)

- Make the spreadsheet legible: labels, units, a notes column for assumptions.
- Export CSV + screenshot/PDF into the repo.
- Re-check internal consistency (canvas price == sheet price, etc.).
- Write a short `README.md` in your project folder pointing to the three artifacts.

---

## Acceptance criteria

- [ ] `canvas/CANVAS.md` — all nine lean-canvas blocks filled; weakest block flagged with a test; revenue model + price defended.
- [ ] A **real spreadsheet** in `unit-economics/` (CSV + screenshot/PDF committed) computing contribution margin ($ and %), CAC (fully loaded), LTV (on contribution), LTV:CAC, and payback.
- [ ] **Every input has a labeled assumption**, and the key ones cite where they came from.
- [ ] A **base/worst/best sensitivity** analysis with at least one full worst-case recompute; scariest variable identified.
- [ ] `unit-economics/VERDICT.md` — the one-sentence verdict (required shape), the most fragile assumption named, and a plain-English "can this make money at scale" answer.
- [ ] **Internal consistency**: numbers match across canvas and sheet.
- [ ] LTV uses **contribution**, not revenue. (Auto-fail if it doesn't.)
- [ ] CAC includes **founder time**.
- [ ] All artifacts committed to your Week 6 repo.

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|-------:|-------------------------|
| Canvas complete & internally consistent | 20% | Nine sharp single-line blocks; no "everyone"; value prop is an outcome; weakest block flagged with a test. |
| Five unit-economics metrics correct | 30% | Contribution margin, CAC, LTV, LTV:CAC, payback all computed right, in a live spreadsheet. |
| Assumptions explicit & sourced | 20% | Every number has a stated, reasonable assumption; key ones trace to an interview or comparable. |
| Sensitivity analysis | 15% | Base/worst/best done; scariest variable correctly identified; worst case recomputed, not hand-waved. |
| Honest verdict | 15% | The one-sentence verdict is filled correctly and the most fragile assumption is named and defended. |

---

## Stretch (optional)

- Model the **same concept under a second revenue model** (e.g., switch from subscription to a per-transaction take rate). Compare which survives the sensitivity check better — the comparison *is* the insight.
- Add an **overall break-even** calc: total fixed costs ÷ contribution margin = customers needed to break even. Turn "be profitable" into a customer-count target.
- Pull a **comparable public company's** disclosed CAC payback or net revenue retention from an S-1 and benchmark your numbers against a real one.
- Add a tiny **cohort retention curve** (months 1–12, % retained) instead of a single flat churn number, and recompute LTV off the curve. More honest, slightly harder.

---

## What this prepares you for

- **Week 7 (Go-to-Market):** your CAC here is a *hypothesis*. Week 7 is where you run a real channel and find out if the number holds. Your Week 6 CAC assumption is literally Week 7's target to validate.
- **Week 8 (Fundraising):** whether you *should* raise — and how much — falls out of your payback period and the cash gap it implies. A short-payback business may not need to raise; a long-payback one must.
- **Week 10 (Pitch):** the "model" slide of your deck is this sheet, compressed. The hard investor question — "what are your unit economics?" — is one you'll answer from memory because you built this.

---

## Submission

1. Push your repo with `canvas/`, `unit-economics/` (sheet CSV + screenshot/PDF), and `VERDICT.md`.
2. Make sure the spreadsheet is *legible in the repo* (the screenshot/PDF), not just a link to a Google Sheet that might be private.
3. Make sure your one-sentence verdict is the last thing a reader sees in `VERDICT.md`.
4. Post the repo URL in your cohort tracker and bring it to Sunday's peer review. You did real founder work — show it, and let it get pressure-tested.

---

*Next: [Week 7 — Go-to-Market & Early Traction](../../week-07-go-to-market-and-early-traction/). A model that can make money is worthless without a repeatable way to reach customers — and Week 7 will test the CAC you just assumed.*
