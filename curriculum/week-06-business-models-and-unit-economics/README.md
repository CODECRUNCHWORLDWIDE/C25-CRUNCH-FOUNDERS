# Week 6 — Business Models & Unit Economics

Welcome to the back half of **C25 · Crunch Founders**. Weeks 1–5 were about proving the problem is real and that someone will adopt a solution. You have ten-ish discovery interviews, a co-founder agreement draft, and an MVP wired to one metric. You have *demand evidence*. What you do **not** yet have is an answer to the question every investor, every co-founder, and every future you will eventually ask:

> **Can this thing ever make money — and does growth help or hurt?**

That question is this week. It is the hinge of the whole course. A startup with real demand and broken unit economics is not a startup; it is a machine that loses money faster the more it succeeds. We have all watched a beautifully-growing company torch a hundred million dollars selling dollars for ninety cents, then call it "scaling." This week you learn to see that trap before you fall into it, and to build the one-page model and the spreadsheet that prove you are not in it.

We move in two passes. First, the **lean canvas** — a one-page hypothesis of how the whole business is supposed to work, nine boxes you can fill (or admit you can't) in twenty minutes. Then the **unit economics** — the four or five numbers (contribution margin, CAC, LTV, the LTV:CAC ratio, payback period) that tell you whether the canvas is a business or a hobby with revenue. By Sunday you will have a lean canvas and a unit-economics sheet for *your* concept, every assumption written down and stress-tested, with an honest one-sentence verdict at the bottom.

This is a business week. **You will write zero code.** The deliverables are a canvas, a spreadsheet-shaped worksheet, and a defensible argument. The discipline is the same as engineering, though: state your assumptions, make them falsifiable, and don't lie to yourself about the numbers.

## Learning objectives

By the end of this week, you will be able to:

- **Fill in a lean business model canvas** for your concept — the nine-block, one-page hypothesis of how value is created, delivered, and captured — and name the blocks you *can't* yet fill as your riskiest business-model assumptions.
- **Distinguish a business model from a revenue model from a pricing model** — three things founders constantly collapse into one.
- **Choose a revenue model** (subscription, transactional/marketplace take rate, usage-based, one-time, ads, freemium, hybrid) that fits *your* customer and value, and defend the choice.
- **Set a first price using value-based reasoning**, not cost-plus, and explain why underpricing is the most common and most expensive early mistake.
- **Compute contribution margin** per unit/customer and separate it cleanly from gross margin and from fixed costs.
- **Compute CAC** honestly — including the founder-time and tooling costs everyone conveniently forgets.
- **Compute LTV** on *contribution* (not revenue), tie it to a churn/retention assumption, and avoid the most common ways an LTV figure lies.
- **Compute the LTV:CAC ratio and the CAC payback period**, and explain what "healthy" means directionally and why payback governs how fast you can grow on a given amount of cash.
- **State every assumption explicitly and run a sensitivity check** — what happens if CAC doubles or retention halves — so your model is honest rather than hopeful.
- **Deliver a one-sentence verdict**: *can this model make money at scale, and what would have to be true?*

## Prerequisites

This week assumes you have completed **C25 Weeks 1–5**, or have an equivalent live concept in flight. Specifically:

- You have a **specific customer and problem** from your discovery work (Weeks 2–3). Unit economics computed against "everyone" are meaningless; you need a segment.
- You have an **MVP or prototype** (Week 5) and at least a guess at how someone would pay for it.
- You are comfortable with **arithmetic and a spreadsheet** — addition, multiplication, division, and a single division to get a ratio. That is the entire mathematical demand of this week. If you can split a restaurant bill, you can do unit economics.
- You have a notebook or doc where your **assumptions** live. We will add a lot of them this week.

You do **not** need any finance or accounting background. We define every term from scratch and deliberately avoid GAAP, accruals, and the parts of finance that don't change an early founder's decisions. This is the founder's slice of finance: just enough to know whether to step on the gas or the brake.

## Topics covered

- **The business model canvas vs. the lean canvas** — Osterwalder's nine blocks vs. Maurya's startup-tuned variant, and why we use the lean version at this stage.
- The nine blocks as a **hypothesis, not a plan**: customer segments, problem, unique value proposition, solution, channels, revenue streams, cost structure, key metrics, unfair advantage.
- **Revenue models**: one-time/transactional, subscription (the 2026 default for software), marketplace take rate, usage/consumption-based (the AI-era resurgence), advertising, freemium, and hybrids — with the trade-off each one makes.
- **Pricing basics**: value-based vs. cost-plus vs. competitor-anchored; willingness-to-pay; the underpricing trap; why "what does it cost us" is the wrong starting question.
- **Contribution margin**: price minus variable cost per unit; the difference between contribution margin, gross margin, and operating margin; why fixed costs are deliberately excluded from unit economics.
- **CAC** (customer acquisition cost): the honest version that counts founder time, tools, and content — not just ad spend; blended vs. paid CAC.
- **LTV** (lifetime value): contribution-based LTV, the churn/retention assumption underneath it, the difference between revenue-LTV and contribution-LTV, and how an LTV number quietly lies.
- **LTV:CAC ratio** and **CAC payback period**: what the rules of thumb (≈3:1, <12 months) mean, where they come from, and when to ignore them.
- **Why a great top line can hide a broken model**, and the famous failure patterns (negative-margin growth, the subsidy treadmill).
- **Stating assumptions and running sensitivity**: best/base/worst cases; the single scariest variable; what would have to be true.

## Weekly schedule

The schedule below adds up to approximately **36 hours** across a full week of focused founder work. The syllabus quotes ~10 hours for a part-time learner; the table below is the full-intensity version (a residential/bootcamp week or a sprint), which is the standard altitude for these week packets. Treat it as a target, not a contract. Field work — pricing conversations with real prospects — spikes Wednesday and Thursday.

| Day       | Focus                                              | Lectures | Exercises | Challenges | Quiz/Read | Homework | Mini-Project | Self-Study | Daily Total |
|-----------|----------------------------------------------------|---------:|----------:|-----------:|----------:|---------:|-------------:|-----------:|------------:|
| Monday    | The lean canvas; business vs. revenue vs. pricing  |   2h     |   1.5h    |    0h      |   0.5h    |   1h     |    0h        |   0.5h     |   5.5h      |
| Tuesday   | Revenue models & value-based pricing               |   2h     |   1.5h    |    0h      |   0.5h    |   1h     |    0h        |   0.5h     |   5.5h      |
| Wednesday | Contribution margin & CAC (field: pricing convos)  |   1h     |   1.5h    |    1h      |   0.5h    |   1h     |    0.5h      |   0.5h     |   6h        |
| Thursday  | LTV, LTV:CAC, payback, sensitivity                 |   1h     |   1.5h    |    1h      |   0.5h    |   1h     |    1h        |   0h       |   6h        |
| Friday    | Canvas + unit-economics sheet build                |   0h     |   0.5h    |    0h      |   0.5h    |   1h     |    3h        |   0.5h     |   5.5h      |
| Saturday  | Mini-project deep work, sensitivity & verdict      |   0h     |   0h      |    0h      |   0h      |   0h     |    3.5h      |   0h       |   3.5h      |
| Sunday    | Quiz, peer model review, polish                    |   0h     |   0h      |    0h      |   1h     |   0h     |    2h        |   0h       |   3h        |
| **Total** |                                                    | **6h**   | **6.5h**  | **2h**     | **4h**    | **5h**   | **13.5h**    | **2.5h**   | **35h**     |

## In-class / studio activities

These are the live activities your cohort runs. Even if you're solo, do them out loud with a friend or a rubber duck; the value is in being challenged.

- **Canvas in 20.** Fill all nine lean-canvas blocks for your idea in twenty minutes, single-line answers only. The boxes you *can't* fill are your riskiest business-model assumptions — circle them. We do this fast on purpose; perfectionism is the enemy of a first canvas.
- **The pricing dare.** Each founder names their intended price out loud. The room's only response is: *"why not double it?"* You have to defend the number or admit you're guessing. Nine times out of ten the founder caves and the price goes up. Underpricing is the single most common early mistake and the easiest to fix.
- **The leaky model.** We hand you a one-pager of real-looking numbers where CAC quietly exceeds LTV. As a group you diagnose what's broken (retention? price? channel?) and name the one change that would fix it. This is the diagnostic muscle the whole week is building.
- **Assumption hunt.** Swap unit-economics sheets with another founder. Your only job is to find the one assumption that, if wrong, breaks their whole model — and circle it. You'll find it faster in their sheet than in your own.

## Worked example (carried through the week)

We carry one running example so the math has a home. **Maya runs a SaaS that helps small dental clinics fill same-day cancellation slots** (a real, dull, lucrative problem she found in Week 3 discovery).

- **Price:** $99/month per clinic (a value-based number — a single filled cancellation slot is worth ~$150 to a clinic, so $99/month is a fraction of the value she creates).
- **Variable cost to serve:** ~$9/month per clinic (SMS to patients, payment processing, a sliver of support). **Contribution margin = $99 − $9 = $90/month.**
- **CAC:** she expects ~$300 to land a clinic — counting her own founder-led-sales time at a notional rate plus tools and a little ad spend. (Counting her time is the part founders skip.)
- **Retention:** clinics that adopt tend to stay ~24 months before churn. **Contribution-LTV ≈ $90 × 24 = $2,160.**
- **LTV:CAC ≈ $2,160 / $300 ≈ 7:1** — healthy, directionally well above the 3:1 rule of thumb.
- **Payback ≈ $300 / $90 ≈ 3.3 months** — fast, which means cash recycles quickly and she can grow without raising much.

Then the scary question: **what if CAC triples to $900** (paid channels are more expensive than founder-led sales, and they will be as she scales)? Payback stretches to ~10 months and LTV:CAC drops to ~2.4:1 — thinner, below the rule of thumb, but still alive. *That sensitivity check is the entire point.* A model that only survives the best case is a wish, not a model.

## How to navigate this week

| File | What's inside |
|------|---------------|
| [README.md](./README.md) | This overview (you are here) |
| [resources.md](./resources.md) | Curated, free references: Strategyzer, Lean Canvas, YC, a16z, SaaS-metrics primers |
| [lecture-notes/01-the-business-model-canvas-and-revenue-models.md](./lecture-notes/01-the-business-model-canvas-and-revenue-models.md) | The lean canvas's nine blocks, revenue models, value-based pricing |
| [lecture-notes/02-unit-economics-that-tell-the-truth.md](./lecture-notes/02-unit-economics-that-tell-the-truth.md) | Contribution margin, CAC, LTV, LTV:CAC, payback, sensitivity |
| [exercises/README.md](./exercises/README.md) | How the exercises work + a checklist |
| [exercises/exercise-01-canvas-and-margins.md](./exercises/exercise-01-canvas-and-margins.md) | Guided: fill the canvas, then compute contribution margin |
| [exercises/exercise-02-lean-canvas-worksheet.md](./exercises/exercise-02-lean-canvas-worksheet.md) | Fill-in worksheet/template: your nine-block lean canvas |
| [exercises/exercise-03-unit-economics-sheet.md](./exercises/exercise-03-unit-economics-sheet.md) | Fill-in spreadsheet template: CAC, LTV, payback, sensitivity |
| [challenges/README.md](./challenges/README.md) | What the challenge is and how it's assessed |
| [challenges/challenge-01-the-leaky-model-turnaround.md](./challenges/challenge-01-the-leaky-model-turnaround.md) | Diagnose and fix a startup whose unit economics are upside-down |
| [quiz.md](./quiz.md) | 10 questions with an answer key |
| [homework.md](./homework.md) | Assignment with a grading rubric |
| [mini-project/README.md](./mini-project/README.md) | Full spec for your lean canvas + unit-economics sheet |

## The "honest verdict" promise

C25 uses one recurring marker for every business-model deliverable. At the bottom of your unit-economics sheet, you must be able to write one sentence in this exact shape:

> **This model makes money at scale if and only if `<the one thing>` holds; if it doesn't, the model breaks because `<consequence>`.**

If you can't fill that sentence in, you don't understand your model yet — you have a spreadsheet, not an argument. The point of this week is to make that sentence ordinary and true.

## Stretch goals

If you finish the core work early and want to push further:

- Read Bill Gurley's classic **"The Dangerous Seduction of the Lifetime Value (LTV) Formula"** and list every way the simple LTV formula can mislead: <https://abovethecrowd.com/2012/09/04/the-dangerous-seduction-of-the-lifetime-value-ltv-formula/>.
- Read David Skok's **"SaaS Metrics 2.0"** and map his diagrams onto your own model: <https://www.forentrepreneurs.com/saas-metrics-2/>.
- Watch the YC Startup School talk on **business models and pricing**, then rewrite your price using one idea you didn't have before: <https://www.startupschool.org/>.
- Build a second canvas for the *same idea* with a **different revenue model** (e.g., switch Maya from subscription to a per-filled-slot take rate). See which one survives the sensitivity check better. The exercise of modeling two revenue models for one product is itself the lesson.
- Read a public S-1 or shareholder letter (e.g., any recent SaaS IPO) and find where they disclose CAC payback or net revenue retention. Real companies report these. Yours should too.

## Up next

Continue to **Week 7 — Go-to-Market & Early Traction** once your canvas and unit-economics sheet are committed and peer-reviewed. A model that *can* make money is worthless without a repeatable way to reach customers — and Week 7's CAC will only be as honest as the channel you actually test. Your Week 6 CAC assumption becomes Week 7's number to validate.

---

*A great top line can hide a broken model for a surprisingly long time. Know your contribution margin, CAC, LTV, and payback before you pour fuel on the fire — and if you find yourself losing money on every customer, growth is not the cure. It's the accelerant.*
