# Exercise 1 — Cap-Table Basics

**Goal:** Build a starting cap table from a blank spreadsheet, then add a single priced round and compute founder dilution to the share and the percentage point. By the end you can open an empty sheet and model a round without referring to this file.

**Estimated time:** 45 minutes.

**Format:** A spreadsheet (Google Sheets or LibreOffice Calc) plus a short markdown write-up. **This is not code.** Type the formulas yourself; do not hard-code percentages.

> **Education, not investment or legal advice.**

---

## Setup

Open a blank spreadsheet. You'll build three tables stacked vertically: **Starting**, **The Round**, and **After the Round**. Use *your own* venture's founder split from Week 4 if you have one; if you're working solo or don't have co-founders, use the two-founder 50/50 example below and adapt.

You will need only four columns: **Holder**, **Shares**, **Ownership %**, and a notes column. Make the Ownership % column a *formula* — `=Shares ÷ Total` — never a typed number. This is the entire discipline of the exercise: when you change an input, the percentages must move on their own.

---

## Step 1 — The starting table

Authorize a round number of shares and split them by your founder agreement. The example uses 10,000,000 shares, two founders, 50/50:

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | `=5000000/10000000` → 50.0% |
| Founder B | 5,000,000 | `=5000000/10000000` → 50.0% |
| **Total** | **=SUM(shares)** = 10,000,000 | **100.0%** |

**Check:** the Ownership column sums to exactly 100.0%. If it doesn't, your formula references are off. A starting table that doesn't sum to 100 is wrong — fix it before going on.

> If your real split is, say, 60/40 or three founders at 40/35/25, use *those* numbers. The mechanic is identical; only the inputs change.

---

## Step 2 — Define the round

State the three numbers that define a priced round, and derive the fourth:

```
Investment:   $500,000        (what the investor puts in)
Pre-money:    $4,500,000      (agreed value before the money)
Post-money:   = pre + investment = $5,000,000      ← formula, not typed
Investor %:   = investment / post-money = 10.0%    ← formula, not typed
```

Write these in a small block above the "after" table. The two formulas — `post = pre + investment` and `investor % = investment ÷ post` — are the heart of the whole week. If you typed 10% instead of computing it, redo it as a formula.

---

## Step 3 — Issue the shares that make it true

The investor must end up owning 10%, which means the founders own 90% *combined* after the round. Solve for the new total share count, then for the investor's shares:

```
new total      = founder shares / founder % after
               = 10,000,000 / 0.90
               = 11,111,111

investor shares = new total − founder shares
                = 11,111,111 − 10,000,000
                = 1,111,111
```

Put those into the "after" table:

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | 45.0% |
| Founder B | 5,000,000 | 45.0% |
| Pre-seed investor | 1,111,111 | 10.0% |
| **Total** | **11,111,111** | **100.0%** |

**Check:** Ownership sums to 100.0%, and the investor row reads 10.0% (`1,111,111 ÷ 11,111,111`). If the investor isn't at exactly 10%, your new-total formula is off.

---

## Step 4 — Compute founder dilution

State, explicitly, what each founder gave up:

```
Founder A: 50.0% → 45.0%   ·   gave up 5.0 points
Founder B: 50.0% → 45.0%   ·   gave up 5.0 points
```

Notice the founders did **not** lose any shares — both still hold 5,000,000. They lost *percentage*, because the denominator grew from 10M to 11.11M. That's dilution: a growing denominator, not a shrinking numerator.

---

## Step 5 — Write it up

In a markdown file (`exercises/exercise-01-writeup.md` in your Week 8 repo), capture the result for *your* venture:

```markdown
# Cap table — <your venture>

## Starting (100%)
| Holder | Shares | % |
|--------|-------:|--:|
| ...    | ...    | ..|

## The round
Investment: $___  ·  Pre-money: $___  ·  Post-money: $___  ·  Investor %: ___%

## After the round (100%)
| Holder | Shares | % |
|--------|-------:|--:|
| ...    | ...    | ..|

## Founder dilution
Founder A: __% → __%  ·  gave up __ points
Founder B: __% → __%  ·  gave up __ points

## One sentence
"To bring in $___, we each gave up __ points of ownership, to buy ___."
```

That final sentence — *what you gave up, to buy what* — is the "show me the number" promise from the README. Make it true and specific.

---

## Acceptance criteria

- [ ] A spreadsheet with starting and after-round tables, each summing to exactly **100.0%**.
- [ ] Ownership % is a **formula** (`shares ÷ total`), not a typed number, everywhere.
- [ ] The round states investment, pre-money, post-money, and investor %, with post-money and investor % computed by formula.
- [ ] The investor row reads exactly the target % (10.0% in the example).
- [ ] Founder dilution is shown before → after, in points, for each founder.
- [ ] A one-sentence "what we gave up, to buy what" statement.
- [ ] Committed to your Week 8 repo (sheet exported to CSV or screenshotted; write-up in markdown).

---

## Stretch

- Change the **pre-money** from $4.5M to $9M, keeping the $500k investment, and watch founder dilution *halve*. Higher valuation = less dilution for the same money. This is why valuation matters — and why founders fixate on it.
- Add a **third founder** at the start (40/35/25) and re-run the round. Confirm all three dilute proportionally.
- Leave the option pool out *for now* — you add it in Exercise 2 and the mini-project, where the "pool shuffle" makes founders dilute more than this clean example shows.

---

## Hints

<details>
<summary>My percentages don't sum to 100%</summary>

Your Ownership formula is probably dividing by a fixed cell instead of the live `SUM` of the shares column. Make the denominator reference the total cell (use an absolute reference like `$B$5`) so every row divides by the same total. Re-check that the total cell is `=SUM()` over exactly the holder rows — not including the header or the total itself.

</details>

<details>
<summary>The investor isn't landing on exactly 10%</summary>

Work backwards from the target. If the investor must be 10%, the *existing* holders must be 90% *after* the round. So `new total = existing shares ÷ 0.90`, and `investor shares = new total − existing shares`. If you instead added "10% of the old total" as new shares, you'll be slightly off, because that 10% should be of the *new* total, not the old one.

</details>

<details>
<summary>Why does the founder dollar value use pre-money but the investor % use post-money?</summary>

The investor buys their slice of the company that exists *after* their money lands — so their % is measured against post-money. The founders' pre-existing value is what the company was worth *before* the money — pre-money. Same round, two reference points. Mixing them up is the most common modeling error; keep the two valuations in clearly labeled cells.

</details>

---

*Next: stack some SAFEs and see what you've promised away before the priced round — [Exercise 2 — SAFE Conversion Worksheet](exercise-02-safe-conversion-worksheet.md).*
