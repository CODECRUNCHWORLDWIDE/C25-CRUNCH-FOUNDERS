# Exercise 3 — Unit-Economics Sheet

**This is a spreadsheet template expressed in Markdown, not a reading.** Rebuild it in Google Sheets / Excel / Numbers (recommended, so the formulas auto-update) **or** fill the Markdown tables below directly. Either way you produce one artifact: a unit-economics sheet for *your* concept where every number has a stated assumption and a sensitivity table sits underneath. **You write zero code.** The math is addition, multiplication, and one division.

**Estimated time:** ~50 minutes.

**Prerequisite:** Exercise 2 done — you'll pull your price, variable costs, and churn from the canvas.

---

## What "done" looks like

A sheet with five sections: (1) **Inputs & assumptions**, (2) **Contribution margin**, (3) **CAC**, (4) **LTV, LTV:CAC, payback**, (5) **Sensitivity + verdict**. The grader can read it top to bottom and see *exactly* where every number came from. No naked numbers.

---

## Section 1 — Inputs & assumptions

Every downstream number traces to one of these. Fill the assumption column or the whole sheet is a guess.

| Input | Your value | Assumption (the "because…") |
|-------|-----------:|-----------------------------|
| Price per customer per period | $______ | |
| Billing period (month / year / transaction) | ______ | |
| Variable cost 1 | $______ | |
| Variable cost 2 | $______ | |
| Variable cost 3 | $______ | |
| Monthly churn rate (%) | ____% | |
| CAC — channel/ad spend per customer | $______ | |
| CAC — founder/team time per customer | $______ | (hours × hourly rate) |
| CAC — tools/content allocated | $______ | |

---

## Section 2 — Contribution margin

```
Contribution margin ($) = Price − (sum of variable costs)
Contribution margin (%) = Contribution margin ($) ÷ Price
```

| Line | Value |
|------|------:|
| Price | $______ |
| Total variable cost | $______ |
| **Contribution margin ($)** | **$______** |
| **Contribution margin (%)** | **____%** |

> If this is **negative**, STOP and flag it in red. You lose money on every customer before acquisition even starts. No CAC or LTV math will save a negative contribution margin — fix price or variable cost first.

---

## Section 3 — CAC (fully loaded)

```
CAC = channel spend + founder/team time + tools/content   (per acquired customer)
```

| Component | Value |
|-----------|------:|
| Channel / ad spend per customer | $______ |
| Founder/team time per customer (hours × rate) | $______ |
| Tools / content allocated per customer | $______ |
| **CAC (fully loaded)** | **$______** |

> The most common error here is leaving out **founder time**. If you sell by hand, your time *is* the CAC. Price it (e.g., 6 hours × $50 = $300) even though no cash leaves your account.

---

## Section 4 — LTV, LTV:CAC, payback

```
Expected lifetime (periods) = 1 ÷ monthly churn rate
LTV = Contribution margin ($) × Expected lifetime          ← CONTRIBUTION, not price
LTV:CAC = LTV ÷ CAC
Payback (periods) = CAC ÷ Contribution margin ($)
```

| Line | Value |
|------|------:|
| Monthly churn rate | ____% |
| Expected lifetime (months) = 1 ÷ churn | ______ |
| Contribution margin per month | $______ |
| **LTV (on contribution)** | **$______** |
| CAC | $______ |
| **LTV : CAC** | **____ : 1** |
| **CAC payback (months)** | **______** |

> Read your numbers against the rules of thumb: LTV:CAC ≈ 3:1 healthy (below 1 = stop; above 5 = maybe underinvesting in growth); payback under ~12 months healthy. State which zone you're in.

---

## Section 5 — Sensitivity + verdict

Move the scary variables in the *wrong* direction. Fill base, then worst (pessimistic-but-plausible) and best (optimistic-but-plausible).

| Metric | Worst | **Base** | Best |
|--------|------:|---------:|-----:|
| Price | $____ | $____ | $____ |
| Contribution margin/mo | $____ | $____ | $____ |
| CAC | $____ | $____ | $____ |
| Monthly churn | ____% | ____% | ____% |
| Lifetime (mo) | ____ | ____ | ____ |
| **LTV** | $____ | $____ | $____ |
| **LTV:CAC** | ____:1 | ____:1 | ____:1 |
| **Payback (mo)** | ____ | ____ | ____ |

**Scariest single variable** (the one that breaks the model fastest if it goes wrong): ______

**The one-sentence verdict** (required):

> This model makes money at scale if and only if ____________ holds; if it doesn't, the model breaks because ____________.

---

## Worked example (Maya / FillChair) — for calibration

| | Worst | **Base** | Best |
|--|------:|---------:|-----:|
| Price | $79 | $99 | $129 |
| Contribution margin/mo | $72 | $90 | $118 |
| CAC | $900 | $300 | $200 |
| Monthly churn | 8% | 4% | 3% |
| Lifetime (mo) | 12 | 24 | 33 |
| LTV | $864 | $2,160 | $3,894 |
| **LTV:CAC** | 0.96:1 | 7.2:1 | 19.5:1 |
| **Payback (mo)** | 12.5 | 3.3 | 1.7 |

**Scariest variable:** churn — it's the only one that, at its worst (8%), combined with worst-case CAC, pushes LTV:CAC below 1.

**Verdict:** *This model makes money at scale if and only if clinic churn stays near 4%/month; if churn doubles to 8% while CAC also rises, LTV:CAC falls below 1 and we lose money on each clinic — so retention, not acquisition, is the thing to defend.*

---

## Acceptance criteria

- [ ] All five sections filled for your concept (sheet or Markdown).
- [ ] Every input has a stated assumption.
- [ ] Contribution margin computed in $ and %; flagged if negative.
- [ ] CAC is fully loaded (founder time included and shown).
- [ ] LTV computed on **contribution**, tied to an explicit churn figure.
- [ ] LTV:CAC and payback computed; the rule-of-thumb zone stated.
- [ ] Base/worst/best sensitivity table filled; scariest variable named.
- [ ] One-sentence verdict written in the required shape.
- [ ] Committed to your Week 6 repo.

---

## Hints

- Build it in a real spreadsheet if you can — then changing one input recomputes the ratio and you can *play* with sensitivity instead of redoing arithmetic.
- Lifetime = 1 ÷ monthly churn. 5% churn → 20 months. 10% churn → 10 months. Churn is brutal; small changes swing LTV hard.
- If your LTV:CAC is enormous (>10:1) in the base case, don't celebrate — suspect you've underpriced, underestimated CAC, or used honeymoon-phase churn. Pressure-test before you brag.

---

*This sheet is the heart of the [mini-project](../mini-project/README.md). Carry it straight in.*
