# Week 8 Homework

Four problems that revisit the week's topics and feed straight into the mini-project and your Week 10 capstone. The full set should take about **5.5 hours**. Work in your Week 8 Git repository so each problem produces at least one commit you can point to later.

Each problem includes a **problem statement**, **acceptance criteria** so you know when you're done, a **hint** if you get stuck, and an **estimated time**. A **grading rubric** is at the bottom.

> **This is education, not investment, tax, or legal advice.**

---

## Problem 1 — Raise-or-not memo

**Problem statement.** At `notes/raise-or-not.md`, decide — for *your* venture — whether you should raise right now. Reason explicitly through the two questions from Lecture 1 and the four "don't raise" conditions:

1. Is **capital actually the bottleneck**, or is it customers / product / clarity?
2. Do you have **evidence the money compounds** (cite your Week 6 unit economics and Week 7 traction metric)?
3. Are you in any of the **four "don't raise" conditions** (default-alive without it, unvalidated model, control lean, broken unit economics)?
4. State an **explicit decision** and tie it to your Week 1 control-vs-wealth lean.

**Acceptance criteria.**

- File `notes/raise-or-not.md` exists.
- All four points addressed, each citing a specific prior-week artifact (economics, traction, lean).
- An explicit raise / don't-raise decision is stated.
- Committed.

**Hint.** "Not yet, because [specific reason]" is the most common *correct* answer in a zero-to-validation course. A decisive "not yet" beats a wishy-washy "maybe."

**Estimated time.** 45 minutes.

---

## Problem 2 — Round + option-pool model

**Problem statement.** At `notes/round-model.md` (backed by a spreadsheet you export/screenshot), model a hypothetical pre-seed for your venture:

- Your starting cap table (Week 4 split), summing to 100%.
- A **10% option pool created pre-money.**
- An investor ending at a target % (e.g., 10%), with pre-money and post-money stated.
- Founder ownership **before and after**, in points.

The model must show the **pool shuffle**: founders dilute by the round *plus the whole pool*.

**Acceptance criteria.**

- File present, backed by a spreadsheet (CSV export or screenshot committed).
- Option pool modeled **pre-money** (not post-money by mistake).
- Pre-money and post-money both stated; investor % = `investment ÷ post-money`.
- Founder dilution shown before → after, in points; tables sum to 100%.
- Committed.

**Hint.** With a 10% round and a 10% pre-money pool, founders typically give up ~20 points, not 10 — the two 10% slices both come (mostly) out of you. If your founders only dropped 10, you applied the pool post-money.

**Estimated time.** 1 hour 15 minutes.

---

## Problem 3 — SAFE stack in plain English + numbers

**Problem statement.** At `notes/safe-explainer.md`, do two things:

1. **In 150–250 words of your own prose,** explain what a post-money SAFE is, what a valuation cap and a discount each do, and *why* a SAFE that's painless to sign today dilutes you tomorrow.
2. **Then show the numbers:** invent (or use your real) stack of at least **three SAFEs** with amounts and post-money caps. Compute each one's implied % (`amount ÷ cap`) and the **total promised before the priced round.**

**Acceptance criteria.**

- File present; prose section is 150–250 words, original (not copied from YC's site).
- Cap and discount both explained; the later-dilution point made clearly.
- At least three SAFEs with amount, cap, and implied %; a stated stack total.
- Committed.

**Hint.** Read the YC SAFE user guide (resources.md), then write the prose as if explaining it to your co-founder over coffee. For the math, just sum the `amount ÷ cap` column — that's the number that matters.

**Estimated time.** 1 hour.

---

## Problem 4 — The "ask" slide draft

**Problem statement.** Draft the one-line **ask** you'll use on your Week 10 capstone pitch, plus the three-sentence backing. At `notes/the-ask.md`:

- One line: *"We're raising $X at $Y to reach milestone Z. It costs us W points of ownership."* (Fill in from your Problem 2 model.)
- Three sentences backing it: what the money buys, why that milestone matters, and why the dilution is worth it given your unit economics.
- Then anticipate and answer, in 2–3 sentences, the single hardest question an investor would ask about this ask.

**Acceptance criteria.**

- File present with the one-line ask, fully filled in with real numbers from your model.
- Three backing sentences tying the raise to a milestone and your economics.
- One anticipated hard question, answered honestly.
- Committed.

**Hint.** The hardest question is usually "why this much?" or "why now, given [weak spot in your traction]?" Answer the real one, not a softball you invented.

**Estimated time.** 45 minutes.

---

## Time budget recap

| Problem | Estimated time |
|--------:|--------------:|
| 1 | 45 min |
| 2 | 1 h 15 min |
| 3 | 1 h 0 min |
| 4 | 45 min |
| **Total** | **~3 h 45 min** |

*(The remaining homework hours in the weekly schedule go to reading the YC SAFE materials and reviewing your model.)*

---

## Grading rubric

Each problem is graded out of its weight; the homework is worth the homework portion of your weekly grade.

| Problem | Weight | What "great" looks like |
|--------:|------:|-------------------------|
| **1 — Raise-or-not memo** | 25% | Decision is explicit and reasoned from the two questions, the four conditions, and your Week 1 lean — citing specific Week 6/7 artifacts, not generalities |
| **2 — Round + pool model** | 30% | Tables sum to 100%; pool is pre-money and the shuffle is visible; founder dilution shown in points; investor % matches post-money |
| **3 — SAFE explainer + math** | 25% | Original prose correctly explains cap, discount, and later dilution; ≥3 SAFEs with implied % and a correct stack total |
| **4 — Ask slide** | 20% | One-line ask filled with real numbers from the model; backing ties to a milestone and economics; the hard question answered is the *real* one |

**Automatic point losses:**

- Any cap table that doesn't sum to 100% — model is wrong, not "close." (−10%)
- Option pool applied post-money when the problem says pre-money. (−10%)
- A raise decision with no stated reasoning, or reasoning untethered from your own numbers. (−10%)
- Prose in Problem 3 copied from a source instead of written in your own words. (−15%)

When you've finished all four, build the [Cap-Table + Dilution Model](./mini-project/README.md) — most of the inputs are now sitting in your `notes/` folder.
