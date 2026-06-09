# Lecture 2 — Cap Tables, SAFEs, and Dilution

> **Duration:** ~45 min. **Outcome:** You can read and build a basic cap table, explain SAFEs in plain terms, and compute dilution across a round.

## 1. The cap table

A capitalization table lists who owns what. At its simplest:

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 4,000,000 | 50% |
| Founder B | 4,000,000 | 50% |
| **Total** | **8,000,000** | **100%** |

Ownership % = a holder's shares ÷ total shares. When new shares are issued (a round, an option pool), the total grows and everyone's *percentage* drops even though their *share count* stays the same — that is dilution.

## 2. Pre-money vs. post-money

- **Pre-money valuation** — what the company is said to be worth *before* new money.
- **Post-money valuation** — pre-money + the amount invested.

Investor ownership in a priced round ≈ **investment ÷ post-money**. Raise $500k at $4.5M pre → $5.0M post → investor owns 10%.

## 3. SAFEs and convertibles (plain terms)

Early rounds often use a **SAFE** (Simple Agreement for Future Equity) or a **convertible note** instead of pricing the company immediately. In plain terms: the investor gives money now and gets shares *later*, when a priced round happens. Two common knobs:

- **Valuation cap** — the maximum valuation at which their money converts (protects the early investor if you raise the next round at a high price).
- **Discount** — a percentage discount on the next round's price.

You do not need to master conversion math now. Know that SAFEs defer the valuation, that the cap and discount decide how much the early money is worth later, and that they *will* dilute you when they convert.

## 4. The option pool

Investors usually want an **option pool** (e.g., 10–15%) reserved for future employees. If the pool is created *pre-money*, it comes out of the founders' slice before the investor's money lands — so founders dilute more than the headline round implies. This "pool shuffle" surprises first-timers; model it explicitly.

## 5. Dilution worked example

Start: founders own 100% (8M shares). Create a 10% post-round option pool and raise so the investor ends at 10%:

```
After round (illustrative):
  Investor:      10%
  Option pool:   10%
  Founders:      80%  (down from 100%)
```

The exact share counts depend on whether the pool is pre- or post-money; the lesson is that *two 10% slices removed roughly 20% of founder ownership in one round*. Multiply across several rounds and you see why founders track the cap table closely.

## 6. Tie back to control vs. wealth

A control-leaning founder minimizes rounds and dilution; a wealth-leaning founder accepts dilution for growth and a bigger pie. Your cap-table model this week should reflect *your* lean — and show you, in numbers, what the raise would cost.

> **Not investment or legal advice.** SAFEs and rounds are paper you sign with a lawyer. This is enough to be an informed founder, not to skip counsel.

---

*Back to the [week overview](../README.md). Do [Exercise 1](../exercises/exercise-01-cap-table-basics.md), then build the [cap-table model](../mini-project/README.md).*
