# Exercise 1 — Cap-Table Basics

**Goal:** Build a starting cap table and add a single priced round, so the dilution math is concrete before the mini-project.

**Estimated time:** 45 minutes.

---

## What to produce

Create `exercises/exercise-01-cap-table-basics.md` (with the numbers worked in a spreadsheet, exported or screenshotted):

1. **Starting table** — founders and any early holders, with shares and ownership %.
2. **The round** — state the investment, pre-money, post-money, and the investor's resulting %.
3. **The new table** — post-round ownership for every holder, summing to 100%.
4. **Founder dilution** — each founder's ownership before and after, and the % they gave up.

```markdown
# Cap table — <your venture>

## Starting (100%)
| Holder | Shares | % |
|--------|-------:|--:|

## Round
Investment: $___  ·  Pre-money: $___  ·  Post-money: $___  ·  Investor %: ___

## After round
| Holder | Shares | % |
|--------|-------:|--:|

## Founder dilution
Founder A: __% → __%  ·  Founder B: __% → __%
```

---

## Acceptance criteria

- [ ] File present; starting table sums to 100%.
- [ ] Round states investment, pre/post-money, and investor %.
- [ ] Post-round table sums to 100%.
- [ ] Founder dilution shown before/after.
- [ ] Committed (sheet exported/screenshotted).

---

## Hints

- Investor % ≈ investment ÷ post-money. Post-money = pre-money + investment.
- For now you can leave the option pool out; you add it in the mini-project.

---

*Next: build the full [cap-table + dilution model](../mini-project/README.md).*
