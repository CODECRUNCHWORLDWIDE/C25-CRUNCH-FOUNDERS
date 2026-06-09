# Lecture 2 — Unit Economics

> **Duration:** ~1 hour. **Outcome:** You can compute contribution margin, CAC, LTV, LTV:CAC, and payback, and run a sensitivity check.

> **A business with great revenue and bad unit economics is a machine for losing money faster as it grows.**

## 1. Contribution margin

The profit on one unit/customer after the *variable* costs of serving them:

```
Contribution margin = Price − Variable cost per unit
```

If you charge $99/month and it costs $9/month to serve (payments, messaging, support), contribution margin is $90/month. Fixed costs (rent, salaries) are separate; unit economics focus on the per-customer math.

## 2. CAC — Customer Acquisition Cost

What it costs, on average, to acquire one paying customer:

```
CAC = Total sales & marketing spend ÷ Customers acquired
```

Early on, include the real cost of founder-led sales effort and tools, not just ad spend. Underestimating CAC is the most common self-deception in this lecture.

## 3. LTV — Lifetime Value

The total contribution a customer generates before they churn:

```
LTV ≈ Contribution margin per period × Expected lifetime (periods)
```

For $90/month and a 24-month average lifetime, LTV ≈ $2,160. Use *contribution*, not revenue — paying for delivery out of "LTV" you never had is how models lie.

## 4. LTV:CAC ratio

```
LTV : CAC
```

Directionally, a ratio comfortably above 1 means each customer is worth more than they cost to acquire; a healthy software target people often cite is around 3:1 or higher. Well below 1 means you lose money on every customer — do not scale. (These are rules of thumb, not laws.)

## 5. Payback period

How long until a customer's contribution repays their CAC:

```
Payback (periods) = CAC ÷ Contribution margin per period
```

$300 CAC ÷ $90/month ≈ 3.3 months. Short payback is precious early because it frees cash to acquire the next customer. Long payback can be fine for big-LTV businesses but is dangerous when cash is tight.

## 6. State assumptions; then stress them

Every number above rests on assumptions (price, churn/lifetime, variable cost, CAC). Write them down. Then run a **sensitivity check**: what happens if CAC doubles, or lifetime halves? A model that only works under best-case assumptions is not a model — it is a wish.

## 7. The honest verdict

After the math, answer plainly: *can this model make money at scale, and what would have to be true?* That sentence is the deliverable's spine.

---

*Back to the [week overview](../README.md). Do [Exercise 1](../exercises/exercise-01-canvas-and-margins.md), then build the [canvas + sheet](../mini-project/README.md).*
