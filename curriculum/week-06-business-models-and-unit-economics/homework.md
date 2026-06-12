# Week 6 — Homework

Four problems that revisit the week's topics and feed straight into the mini-project. The full set should take about **5 hours**. Work in your **Week 6 Git repo** so each problem produces at least one commit you can point to. And — because this is a founder course, not a finance course — **keep interviewing toward your ten capstone discovery conversations**; pricing and willingness-to-pay questions slot naturally into the ones you have left.

Each problem includes a **statement**, **acceptance criteria**, a **hint**, and an **estimated time**. The combined grading rubric is at the bottom.

---

## Problem 1 — Revenue-model comparison

**Problem statement.** At `notes/revenue-models.md`, evaluate **two** plausible revenue models for *your* concept (e.g., subscription vs. usage-based, or subscription vs. marketplace take rate). For each model, address:

1. How the customer *experiences* paying (what's the rhythm, what do they think they're buying?).
2. What it does to your **revenue predictability** and your **CAC payback**.
3. One risk the model carries (churn for subscription, re-acquisition for transactional, chicken-and-egg for marketplace, bill-shock for usage, etc.).

Then **choose one** and write two sentences on why it fits your customer and value better than the other.

**Acceptance criteria.**
- File present; two distinct revenue models compared across all three dimensions.
- A clear choice with reasoning grounded in *your* customer's behavior, not generic pros/cons.
- Committed.

**Hint.** Match the model's rhythm to how the customer actually *gets* value over time — continuous value wants subscription, episodic value wants transactional, metered value wants usage. Re-read Lecture 1 §4.

**Estimated time.** 45 minutes.

---

## Problem 2 — Full unit-economics math (with a worked check)

**Problem statement.** At `notes/unit-economics.md`, compute, for your concept, with **every assumption labeled**:

1. Contribution margin ($ and %), variable costs itemized.
2. CAC, fully loaded — **founder time included and shown** as `hours × rate`.
3. LTV, on **contribution**, tied to an explicit monthly churn figure (and show `lifetime = 1 / churn`).
4. LTV:CAC ratio.
5. CAC payback period in months.

Then **run one sensitivity case** — pick your scariest variable, move it to a pessimistic-but-plausible value, and recompute all five. State whether the model survives.

**Acceptance criteria.**
- All five metrics computed and shown (not just stated).
- Every input has a labeled assumption.
- CAC includes founder time; LTV uses contribution (auto-fail if it uses revenue).
- One full sensitivity recompute, with a survive/fail call.
- Committed.

**Hint.** Lifetime = 1 ÷ monthly churn. If LTV:CAC comes out above ~8:1 in your base case, be suspicious — you've likely underpriced, underestimated CAC, or used honeymoon-phase churn. Re-read Lecture 2 §1–6.

**Estimated time.** 1 hour 15 minutes.

---

## Problem 3 — The pricing experiment

**Problem statement.** At `notes/pricing.md`, do the value-based pricing work for your concept:

1. State what the *outcome* is worth to your customer (in dollars per period or per transaction), with the reasoning.
2. Propose a price that captures a defensible fraction of that value.
3. Apply the **pricing dare** to yourself: write down the price, then honestly answer "why not double it?" — and decide whether you should raise your number.
4. Draft **three willingness-to-pay questions** you'll ask in your remaining discovery interviews to test the price (e.g., "what does this problem cost you per month today?").

**Acceptance criteria.**
- File present; value-to-customer quantified with reasoning.
- A proposed price defended as a fraction of value (not cost-plus).
- The "why not double it?" question genuinely engaged (you may keep or raise the price, but show the thinking).
- Three concrete willingness-to-pay interview questions drafted.
- Committed.

**Hint.** "Our software fills ~4 cancellation slots/month worth ~$150 each = ~$600 of value; pricing at $99 captures ~16%, an easy yes" is the shape. Don't reason from your costs. Re-read Lecture 1 §5.

**Estimated time.** 1 hour.

---

## Problem 4 — The honest verdict

**Problem statement.** At `notes/model-verdict.md`, write **150–250 words** answering: *can this model make money at scale, and what would have to be true?* You must:

1. End with the one-sentence verdict in the required shape: *"This model makes money at scale if and only if `<X>` holds; if it doesn't, it breaks because `<Y>`."*
2. Name the **single most fragile assumption** (from your Problem 2 sensitivity work) and why it's the one that matters most.
3. State, in one sentence, **what you'll do about it** — which assumption you'll go validate first (this becomes a Week 7 input).

**Acceptance criteria.**
- File present; 150–250 words.
- The one-sentence verdict is present and correctly shaped.
- The most fragile assumption is named and justified.
- A concrete "what I'll validate first" next step is stated.
- Committed.

**Hint.** "It works if churn stays under 5%/month and CAC stays under $400; it breaks if retention slips, because LTV halves and the 3:1 cushion disappears — so I'll validate retention first by checking how long my MVP's first users stick" is a strong shape.

**Estimated time.** 30 minutes.

---

## Time budget recap

| Problem | Estimated time |
|--------:|---------------:|
| 1 — Revenue-model comparison | 45 min |
| 2 — Full unit-economics math | 1 h 15 min |
| 3 — The pricing experiment | 1 h 0 min |
| 4 — The honest verdict | 30 min |
| **Total** | **~3 h 30 min** |

(The remaining ~1.5h of the week's homework budget is the interviewing and reflection you carry across every week of C25.)

---

## Grading rubric

Each problem is graded against the criteria below; the homework is worth 100 points total.

| Problem | Points | Full marks requires |
|---------|-------:|---------------------|
| **P1 — Revenue-model comparison** | 20 | Two models compared across all three dimensions; choice justified from *your customer's* behavior, not generic lists. |
| **P2 — Unit-economics math** | 35 | All five metrics correct and shown; every assumption labeled; CAC includes founder time; **LTV on contribution** (revenue-based LTV = automatic 0 for this problem); one full sensitivity recompute with a survive/fail call. |
| **P3 — Pricing experiment** | 25 | Value-to-customer quantified; price defended as a fraction of value (not cost-plus); "why not double it?" genuinely engaged; three concrete WTP interview questions. |
| **P4 — Honest verdict** | 20 | 150–250 words; correctly-shaped one-sentence verdict; most-fragile assumption named and justified; a concrete next validation step. |

**Cross-cutting deductions** (applied to any problem):
- Any naked number with no stated assumption: −2 each.
- LTV computed on revenue instead of contribution anywhere: −5.
- CAC with no founder time when the concept implies founder-led sales: −3.
- Not committed to the repo: −5 per problem.

**What "A-grade" homework looks like:** every number traces to an assumption that traces (where possible) to a real interview or a comparable company; the pricing reasoning starts from customer value and visibly resists underpricing; and the verdict is *uncomfortably honest* — it names a real fragility rather than declaring premature victory.

---

When you've finished all four, you'll have most of the raw material for the mini-project already written. Push your repo and open the [mini-project](./mini-project/README.md) — you're assembling, not starting from scratch.
