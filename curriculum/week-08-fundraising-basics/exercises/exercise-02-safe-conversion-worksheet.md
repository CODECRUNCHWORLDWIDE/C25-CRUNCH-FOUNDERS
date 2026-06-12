# Exercise 2 — SAFE Conversion Worksheet

**Goal:** Stack a realistic set of post-money SAFEs and compute, *before you sign anything*, how much of your company you've already promised away — then convert the stack at a priced round and see the founders absorb every point of it. This is the worksheet that prevents the most common pre-seed disaster: waking up at the priced round having given away 30% you never tracked.

**Estimated time:** 50 minutes.

**Format:** This is a **worksheet template**, not code. Fill it in for your own venture (or the example scenario) in a spreadsheet, and record the results in the tables below. Copy this file into your Week 8 repo and complete the blanks.

> **Education, not investment or legal advice.** SAFEs are documents you sign with a lawyer.

---

## How a post-money SAFE converts (the one rule you need)

For a **post-money SAFE**, the investor's ownership is fixed the day they sign:

> **SAFE investor % ≈ investment ÷ post-money cap**

A $200,000 SAFE on a $5,000,000 post-money cap is worth **4.0%** of the company (`200,000 ÷ 5,000,000`) when it converts — regardless of what valuation your priced round lands at, as long as the round prices below the cap. (If the round prices *above* the cap, the cap protects them and they may get *more* than that nominal %; if it prices below, the discount or the round price governs. For this worksheet we assume the priced round is at or above each cap, so each SAFE converts at roughly its cap-implied %.)

The critical consequence, from Lecture 2: with post-money SAFEs, **the founders absorb the dilution of every additional SAFE.** The SAFE holders don't dilute each other; you dilute to make room for all of them. So you must **add up every SAFE's implied %** before signing the next one.

---

## Part A — Build the SAFE stack

Fill in your actual (or planned) SAFEs. The example rows show the scenario from Lecture 2; replace them with yours.

| # | Investor | Amount | Post-money cap | Discount | Implied % (= amount ÷ cap) |
|--:|----------|-------:|---------------:|---------:|---------------------------:|
| 1 | Lead angel | $300,000 | $6,000,000 | 0% | 5.0% |
| 2 | Angel 2 | $200,000 | $6,000,000 | 0% | 3.3% |
| 3 | Friend & family | $100,000 | $5,000,000 | 20% | 2.0% |
| 4 | _______ | $_______ | $_______ | __% | ___% |
| | **TOTAL RAISED** | **$_______** | — | — | **Σ implied % = ____%** |

**The number that matters:** the sum of the "Implied %" column. That is how much of your company you've promised to SAFE holders *before the priced round even starts.* In the example it's **~10.3%**. Write yours here:

> **Total promised to SAFEs before the priced round: ______%**

If that number made you wince, good — that's the exercise working. Most first-timers sign SAFEs one at a time, feeling each as small, and never sum the column until conversion forces them to.

---

## Part B — The priced round

Now a lead investor prices a round. State its terms:

```
Priced investment:   $__________
Pre-money:           $__________
Post-money:          = pre + priced investment = $__________
Priced investor %:   = priced investment ÷ post-money = ______%
Option pool (new):   ______%  (created pre-money — comes out of founders + SAFE holders)
```

At this round, **all the SAFEs convert into shares at once**, alongside the new pool and the new investor.

---

## Part C — The post-conversion cap table

Lay out who owns what *after* the SAFEs convert, the pool is created, and the priced investor is in. Fill in the percentages (let your spreadsheet do the share counts; the percentages are what you reason about):

| Holder | Ownership % after conversion |
|--------|-----------------------------:|
| Founder A | ______% |
| Founder B | ______% |
| SAFE holders (all converted) | ______% |
| Option pool | ______% |
| Priced investor | ______% |
| **Total** | **100.0%** |

**Check:** sums to 100.0%. The SAFE-holders row should be close to your Part A total (it gets nudged a little by the pool and priced round, but the cap-implied share is the anchor).

---

## Part D — Founder dilution, the whole story

State each founder's journey from the very start to after the priced round:

```
Founder A: 50.0% (start)  →  ____% (after SAFEs + pool + priced round)  ·  gave up ____ points
Founder B: 50.0% (start)  →  ____% (after SAFEs + pool + priced round)  ·  gave up ____ points

Of the points given up:
  - ____ points went to SAFE holders
  - ____ points went to the option pool
  - ____ points went to the priced investor
```

That decomposition is the payoff. You can now say *exactly* where every point of your ownership went — and notice how much of it went to instruments (SAFEs) that felt "free and easy" when you signed them.

---

## Acceptance criteria

- [ ] At least **two** SAFEs in the stack (the example has three), each with amount, cap, and implied %.
- [ ] Each SAFE's implied % is computed as `amount ÷ post-money cap`.
- [ ] The **total promised to SAFEs** is summed and stated as a single number.
- [ ] A priced round is defined (investment, pre, post, investor %) with post and % computed by formula.
- [ ] A post-conversion cap table that sums to **100.0%**.
- [ ] Founder dilution shown start → end, decomposed into SAFEs / pool / priced investor.
- [ ] Committed to your Week 8 repo.

---

## Stretch

- **The stacking trap, dramatized.** Add two *more* small SAFEs ($50k each at a $5M cap). Watch the SAFE total climb and founder ownership drop *before any priced money arrives.* Note how each felt small alone.
- **Cap vs. round price.** Re-run with the priced round *below* one SAFE's cap. That SAFE now converts at the round price (or discount), not the cap — it gets *less* than its nominal %. Explain in one line who benefits.
- **Pre-money vs. post-money SAFE.** Re-do Part A as if these were *pre-money* SAFEs (the pre-2018 default). Note that with pre-money SAFEs the holders dilute *each other*, not just you — and why that made founders prefer them and investors prefer the post-money version.

---

## Hints

<details>
<summary>I don't know what cap to use for the example</summary>

Use the Lecture 2 numbers: a $6,000,000 post-money cap for the two angels and $5,000,000 for the friend. The point isn't the specific cap; it's seeing the implied-% column add up. For *your* venture, pick a cap consistent with your Week 6 economics and 2026 pre-seed norms (roughly $4M–$10M post-money caps are common for an early pre-seed with traction; AI-native outliers aside).

</details>

<details>
<summary>Why might the SAFE-holders row not exactly equal my Part A total?</summary>

Part A computes each SAFE's % against its own cap, in isolation. When everything converts together with a new pool and a priced investor, the denominators interact slightly, so the realized % can shift a point or two. The cap-implied total is the right *anchor* and the number to reason with; the exact post-conversion figure is what a cap-table tool (Carta, Pulley) computes precisely. For this worksheet, being within a point or two is correct.

</details>

---

*Next: read a term sheet like a founder, not a lawyer — [Exercise 3 — Term-Sheet Read-Through](exercise-03-term-sheet-readthrough.md).*
