# Week 8 — Fundraising Basics

Welcome to **Phase 4 — Money, Law & Pitch**. Week 8 is the money week. By Sunday you should be able to look a hypothetical pre-seed round in the eye and tell, in your own words and in your own spreadsheet, exactly what it costs you: how much ownership you give up, how much control you trade, and whether the cash actually buys growth you couldn't buy any cheaper.

The single most important sentence in this week is this:

> **Raising money is a tool, not a milestone.** "We raised" is not an achievement. It is a *liability with a press release.* You took on a partner who now expects a 10x-plus return, and you sold a slice of your company to get cash you may or may not have needed. The achievement is the *evidence* — the interviews, the working MVP, the traction metric — that made the money worth taking in the first place.

Most of this course is allergic to vanity. This week is where that allergy gets tested hardest, because fundraising is the most vanity-soaked corner of the startup world. The tech press writes about raises, not about profits. Founders post announcement graphics. We are going to ignore all of it and ask the only two questions that matter: *do you need this money, and what does it cost?*

This is a business week. There is **zero code**. The artifacts are spreadsheets, memos, term-sheet read-throughs, and decision scenarios. The mini-project is a cap-table model — the single most valuable spreadsheet a first-time founder can learn to build, because it is the one document that tells you, in numbers you can't argue with, who will own your company after you've done all the things people will tell you to do.

We are current to 2026 practice: post-money SAFEs are the default pre-seed instrument, the 2022–2023 valuation correction has left a more disciplined early market in its wake, AI-adjacent pre-seed rounds are an outlier market of their own, and the "raise a giant round at any cost" era is over. We teach what a sober operator does, not what a 2021 deck promised.

## Learning objectives

By the end of this week, you will be able to:

- **Decide when *not* to raise.** Name the four conditions under which raising is the wrong move, and apply them honestly to your own venture.
- **Distinguish the funding ladder** — bootstrapping, friends & family, angels, pre-seed, seed — and say what kind of evidence each stage expects before it will write a check.
- **Read and build a cap table** from a blank spreadsheet: shares, fully-diluted ownership, and how issuing new shares changes everyone's percentage.
- **Explain a SAFE in plain English** — post-money vs. pre-money SAFE, valuation cap, discount, MFN — and explain *why* a SAFE that feels "free" today dilutes you tomorrow.
- **Compute dilution** across a priced round and an option pool, including the "pool shuffle" that surprises every first-timer.
- **Model a full pre-seed round** end to end: starting table, option pool created pre-money, SAFE conversion or a priced round, and founder ownership before vs. after.
- **Read a pre-seed term sheet** well enough to know which three or four terms actually matter and which are boilerplate.
- **Connect the raise decision to your control-vs-wealth lean** from Week 1 and your unit economics from Week 6, so the choice is reasoned, not reflexive.

## Prerequisites

This week assumes you have completed **Weeks 1–7** of C25, or have the equivalent. Specifically:

- **Week 1** — you have a stated control-vs-wealth lean. This week makes that lean cost something concrete, in percentage points.
- **Week 4** — you have a co-founder equity split (or a deliberate solo decision) and understand vesting with a cliff. The cap table you build this week starts from that split.
- **Week 6** — you have a unit-economics sheet (CAC, LTV, contribution margin, payback). You cannot answer "would the money buy growth?" without it. Raising to scale broken unit economics just scales the loss faster.
- **Week 7** — you have one traction metric you hold yourself to. Traction is the leverage that makes a raise possible on good terms.

You do **not** need any finance background, any accounting, or any prior exposure to term sheets. We start from "what is a share." If you have raised before, you may know more than this week teaches — use it to pressure-test the numbers, and watch for habits formed in a different market cycle.

## Topics covered

- **When not to raise:** reaching sustainability without it, an unvalidated model, a control-leaning founder, and broken unit economics. The cost of capital in founder terms.
- **The funding ladder:** bootstrapping → friends & family → angels → pre-seed → seed, and the evidence each stage expects.
- **What "venture-scale" means** and why most good businesses are not venture-scale — and shouldn't pretend to be.
- **The cap table:** shares, fully-diluted ownership %, authorized vs. issued, and how new issuance dilutes everyone proportionally.
- **Pre-money vs. post-money valuation,** and the identity `investor % ≈ investment ÷ post-money`.
- **SAFEs and convertible notes:** the post-money SAFE (the 2026 default), valuation cap, discount, MFN, and how stacked SAFEs convert at the priced round.
- **The option pool** and the pre-money "pool shuffle" that dilutes founders more than the headline round suggests.
- **Dilution across a round,** worked end to end with real share counts.
- **The pre-seed term sheet:** the handful of terms that matter (valuation/cap, board, pro-rata, option pool) vs. boilerplate.
- **Investor expectations and the power-law math** that drives why venture funds need outsized returns — and what that implies for you.

## Weekly schedule

The schedule below adds up to approximately **36 hours** across the week if you treat this as a full-time block; the syllabus targets ~10 hours for a part-time learner. Scale the deep-work rows to your situation. Treat it as a target, not a contract.

| Day       | Focus                                              | Lectures | Exercises | Challenges | Quiz/Read | Homework | Mini-Project | Self-Study | Daily Total |
|-----------|----------------------------------------------------|---------:|----------:|-----------:|----------:|---------:|-------------:|-----------:|------------:|
| Monday    | When (not) to raise; the funding ladder            |   2h     |   1h      |    0h      |   0.5h    |   1h     |    0h        |   0.5h     |    5h       |
| Tuesday   | Cap tables; pre-money vs post-money                |   2h     |   1.5h    |    0h      |   0.5h    |   1h     |    0h        |   0.5h     |    5.5h     |
| Wednesday | SAFEs, caps, discounts, MFN                        |   1.5h   |   1.5h    |    1h      |   0.5h    |   1h     |    0.5h      |   0.5h     |    6.5h     |
| Thursday  | Dilution, the option pool, the pool shuffle        |   0.5h   |   1h      |    1h      |   0.5h    |   1h     |    1.5h      |   0.5h     |    6h       |
| Friday    | Term sheets; investor expectations; model work     |   0h     |   0.5h    |    0h      |   0.5h    |   1h     |    2.5h      |   0.5h     |    5h       |
| Saturday  | Mini-project deep work (cap-table model)           |   0h     |   0h      |    0h      |   0h      |   0.5h   |    3h        |   0h       |    3.5h     |
| Sunday    | Quiz, raise memo, review, polish                   |   0h     |   0h      |    0h      |   1h      |   0h     |    1h        |   0.5h     |    2.5h     |
| **Total** |                                                    | **6h**   | **5.5h**  | **2h**     | **3.5h**  | **5.5h** |  **9h**      | **3.5h**   | **35h**     |

## In-class activities

- **Raise or not?** Each founder gets three minutes to argue whether their venture should raise *now*, given its traction and the founder's control-vs-wealth lean. The room scores the *reasoning*, not the conclusion — "not yet, because X" beats "yes, because everyone does."
- **Cap-table build-along.** Everyone builds the same starting cap table in a sheet, adds an option pool, then adds a round, and watches the percentages move in real time. The goal is muscle memory: open a blank sheet, model a round, in under fifteen minutes.
- **Dilution shock.** Create a 15% option pool *pre-money*, then add the round, and watch founder ownership drop further than the headline suggests. This is the moment the "pool shuffle" stops being abstract.
- **Term-sheet red-team.** In pairs, read a sample pre-seed term sheet (linked in resources) and each person flags the one term they'd push back on and why. Then swap and defend.

## The "show me the number" promise

C25 uses a recurring marker for this week's work: every claim about a raise must terminate in a number you can point to in a spreadsheet.

```
Founder A: 50.0% → 40.5%  ·  gave up 9.5 points  ·  to buy $500k at $5.0M post
```

If your memo says "this round dilutes us a bit," you are not done. *How much,* exactly, and *to buy what?* The point of Week 8 is to make that sentence ordinary — to turn "fundraising" from a vibe into arithmetic you control.

## How to navigate this week

| File | What's inside |
|------|---------------|
| [README.md](./README.md) | This overview (you are here) |
| [resources.md](./resources.md) | Curated, free, current fundraising references — instruments, cap-table tools, term-sheet templates |
| [lecture-notes/01-when-to-raise-and-the-funding-ladder.md](./lecture-notes/01-when-to-raise-and-the-funding-ladder.md) | When (not) to raise; bootstrapping vs. angels vs. pre-seed; what "venture-scale" means; investor expectations |
| [lecture-notes/02-cap-tables-safes-and-dilution.md](./lecture-notes/02-cap-tables-safes-and-dilution.md) | Cap tables, pre/post-money, post-money SAFEs, the option pool, dilution math worked end to end |
| [exercises/README.md](./exercises/README.md) | Index of the week's worksheets and how they fit together |
| [exercises/exercise-01-cap-table-basics.md](./exercises/exercise-01-cap-table-basics.md) | Guided build of a starting cap table plus one priced round |
| [exercises/exercise-02-safe-conversion-worksheet.md](./exercises/exercise-02-safe-conversion-worksheet.md) | A worksheet template for converting a stack of SAFEs at a priced round |
| [exercises/exercise-03-term-sheet-readthrough.md](./exercises/exercise-03-term-sheet-readthrough.md) | A term-sheet annotation template — mark what matters, flag what's boilerplate |
| [challenges/README.md](./challenges/README.md) | What the challenge is and how it's assessed |
| [challenges/challenge-01-the-down-round-decision.md](./challenges/challenge-01-the-down-round-decision.md) | A realistic, multi-path founder decision: a bridge, a down round, or a hard cut |
| [quiz.md](./quiz.md) | 10 questions with an answer key |
| [homework.md](./homework.md) | Four problems with a grading rubric |
| [mini-project/README.md](./mini-project/README.md) | Full spec for the "Cap-Table + Dilution Model" |

## Stretch goals

If you finish the regular work early and want to push further:

- Model a **two-round future**: your pre-seed plus a hypothetical seed eighteen months later. Watch how founder ownership compounds downward across two rounds and one option-pool top-up.
- Read the **actual Y Combinator post-money SAFE** documents (linked in resources). Find the valuation-cap line, the MFN clause, and the pro-rata side letter. Read the user guide alongside.
- Build a tiny **"would I be better off bootstrapping?"** comparison: project the same revenue path with and without the round, and show where the lines cross on founder take-home.
- Write a one-paragraph note to your future self answering: *if a respected investor offered me a check tomorrow on standard terms, would I take it — and what would have to be true for the answer to be no?*

## Up next

Continue to **Week 9 — Legal, Incorporation & Ops** once you've pushed your cap-table model and raise memo. Money decisions and legal scaffolding go hand in hand — the entity you incorporate and the founder stock you issue are what the cap table actually sits on top of.

---

*Raise to win, not to feel validated. Every dollar of outside money buys growth with a slice of ownership and control. This is education — not investment, tax, or legal advice. Anything you sign, you sign with a lawyer.*
