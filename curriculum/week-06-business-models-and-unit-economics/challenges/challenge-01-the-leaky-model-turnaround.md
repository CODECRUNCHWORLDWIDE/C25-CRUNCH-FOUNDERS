# Challenge 1 — The Leaky-Model Turnaround

**Time estimate:** ~90 minutes.
**Deliverable:** A Markdown write-up in your Week 6 repo (`challenges/challenge-01-leaky-model.md`) with a diagnosis, a recommended fix, a rebuilt unit-economics table, a sensitivity check, and an honest verdict. No code.

---

## The scenario

You've just joined **GreenCrate** as the first "business person" on a three-engineer founding team. GreenCrate is a subscription meal-kit-style box — but for *office snack restocking*: small companies (10–40 people) pay a monthly subscription, and GreenCrate ships a curated box of snacks and drinks to the office each week.

The team is thrilled because **revenue is up and to the right** — they've gone from 20 to 180 paying offices in eight months and are about to raise a pre-seed on that growth. But the bank balance is falling faster than revenue is rising, and nobody on the team can explain why. The CEO hands you the numbers and says: *"We're growing 9x. Why are we running out of money? Tell me what to do — we pitch investors in three weeks."*

Here are the real numbers, monthly, per office (their current "blended" view):

| Line item | Value | Notes |
|-----------|------:|-------|
| Subscription price | $400 / office / month | One flat plan. |
| Cost of snacks in the box | $210 / office / month | Wholesale cost of goods. |
| Packing & fulfillment labor | $35 / office / month | Hourly staff packing boxes. |
| Shipping (4 boxes/month) | $80 / office / month | Regional courier. |
| Payment processing | $12 / office / month | ~3% of $400. |
| Customer support | $18 / office / month | A lot of "my box was wrong" tickets. |
| **CAC** | **$520 / office** | Mostly paid social ads + a part-time SDR's loaded cost. |
| **Monthly churn** | **9%** | Offices cancel often — "snacks were boring," "switched to a competitor," "budget cut." |

The team also mentions, almost in passing: *"Bigger offices (30–40 people) almost never churn and barely cost more to serve — but they're only about 15% of our customers because our ads mostly bring in tiny 10-person offices."*

---

## Your task

Work the numbers, then write up the following.

### Part A — Diagnose (the math)

1. Compute the **contribution margin** per office per month. Itemize.
2. Compute the **expected lifetime** (from churn) and the **LTV on contribution**.
3. Compute **LTV:CAC** and **CAC payback**.
4. State plainly: **is GreenCrate making or losing money per office, and where exactly is the leak?** "Growing 9x" is a clue to *what kind* of trouble they're in — name it.

### Part B — Find the highest-leverage fix (the judgment)

GreenCrate could, in theory, attack any of: price, cost of goods, fulfillment cost, support cost, CAC, or churn. You don't have time or focus to fix all of them, and a pre-seed-stage team can realistically change **one or two things** before the raise. Your job is to name the **single highest-leverage fix** (or a tight pair) and *prove with the math* that it beats the alternatives. Consider — but don't just list — options like:

- Raise the price (and to what, with what value justification?).
- Cut cost of goods (renegotiate suppliers / shrink the box).
- Change *who they acquire* (the bigger-office hint is doing a lot of work — what does it imply about CAC, churn, and contribution margin if they target 30–40-person offices?).
- Reduce churn directly (why are offices leaving, and is that fixable in three weeks?).
- Cut CAC (different channel).

You must explicitly reason about the **segment hint** — it's the most important sentence in the scenario, and a sharp founder catches it.

### Part C — Rebuild the model (prove it)

Present a **post-fix unit-economics table** showing contribution margin, LTV, LTV:CAC, and payback *after* your recommended change(s). Every new number gets a stated assumption (e.g., "if we target 30–40-person offices, churn drops from 9% to 4% because [reason]").

### Part D — Sensitivity + verdict (the honesty)

Run a worst-case on your fix (what if your churn improvement is only half what you hoped? what if the price raise loses you 20% of prospects?). Then write the **one-sentence verdict** in the standard shape:

> GreenCrate makes money at scale if and only if ____________; if not, it breaks because ____________.

If, after all this, you conclude the model **cannot** be saved into a fundable shape in three weeks, say so and defend it — "tell the CEO to delay the raise and fix the model first" is a legitimate, gradeable answer if the math supports it.

---

## Acceptance criteria

- [ ] Part A: contribution margin, lifetime, LTV (on contribution), LTV:CAC, and payback all computed correctly and shown.
- [ ] Part A: the leak is correctly named (this is a negative-contribution-or-thin-margin-plus-high-churn-plus-high-CAC situation — you must identify *which*).
- [ ] Part B: a single highest-leverage fix (or tight pair) is named and justified *with math*, not vibes; the segment hint is explicitly addressed.
- [ ] Part C: a rebuilt unit-economics table with every new assumption stated.
- [ ] Part D: a worst-case sensitivity check on the fix, plus the one-sentence verdict.
- [ ] The write-up is readable by a non-finance person in ~2 minutes.
- [ ] Committed to your Week 6 repo.

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|-------:|-------------------------|
| Diagnosis correctness | 25% | Every number right; the leak named precisely (not just "CAC is high"). |
| Prioritization & judgment | 30% | The *one* fix chosen is genuinely the highest-leverage one, proven against alternatives; the segment hint is exploited. |
| Rebuilt model | 20% | Post-fix table is correct, internally consistent, every assumption stated. |
| Sensitivity & honesty | 15% | Worst-case run; verdict in the required shape; willing to say "delay the raise" if warranted. |
| Communication | 10% | A non-finance reader gets it in two minutes. |

---

## A nudge (not the answer)

Do the arithmetic before you read this. Then: notice that GreenCrate's contribution margin per office is **$400 − ($210 + $35 + $80 + $12 + $18) = $45/month** — only ~11% margin, brutal for a box business. At 9% churn, lifetime ≈ 11 months, so LTV ≈ $45 × 11 ≈ **$495**, against a **$520 CAC** → **LTV:CAC ≈ 0.95:1** and payback ≈ **11.5 months**. They lose money on every office and they're *spending more to acquire them faster* — that's why 9x growth is draining the bank. This is the "scale the loss" trap from Lecture 2, live.

Now the segment hint: bigger offices have *lower churn* (longer lifetime → higher LTV) and *barely higher serving cost* (similar contribution margin) and may have *lower CAC per dollar of revenue* (a 35-person office paying a bigger plan amortizes acquisition better). The highest-leverage move probably isn't "shave $5 off shipping" — it's **changing who they acquire and likely raising/segmenting the price**, which can flip several variables at once. Prove it. And pressure-test it: what if the churn improvement is only partial? Show the worst case before you'd let the CEO pitch this.

---

*This diagnostic reasoning is exactly what you'll apply to your *own* funnel in Week 7. Don't skip it.*
