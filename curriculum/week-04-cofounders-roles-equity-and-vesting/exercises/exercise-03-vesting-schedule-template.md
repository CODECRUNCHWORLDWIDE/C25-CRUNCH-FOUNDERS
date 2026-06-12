# Exercise 3 — Vesting-Schedule Template

**Goal:** Build a real four-year / one-year-cliff vesting schedule for each founder, by hand, then run three departure scenarios against it so the cliff stops being a vocabulary word and becomes something you can compute. Finish with an 83(b) reminder so nobody on your team misses the 30-day clock.

**Estimated time:** 45 minutes.

**You produce:** a completed worksheet, `exercise-03-vesting-schedule-template.md`, plus (recommended) a small spreadsheet for the month-by-month table. This is a **business worksheet** — fill in the template. No code.

---

## Why do this by hand

You will never have to *compute* a vesting schedule from scratch in real life — a lawyer or Carta does it. But doing it once by hand makes the cliff, the monthly vest, and the departure math *real*, so that when you negotiate terms you actually understand what you're agreeing to. (Lecture 2 §1.)

The 2026 standard founder shape: **4-year vest, 1-year cliff, monthly thereafter.**
- Nothing vests for 12 months.
- At month 12, **25%** vests at once (the cliff).
- After that, **1/48th** of the total vests each month for 36 more months.
- At month 48, 100% is vested.

---

## Part 1 — Build the schedule

Pick a total share count per founder. A common founder pool is round numbers; use **4,000,000 shares** per founder so the arithmetic is clean (or scale to your real split).

Fill this in for **each** founder:

```markdown
## Founder F1 — vesting schedule

Total founder shares granted: __________
Schedule: 4-year vest, 1-year cliff, monthly thereafter
Grant date: __________   →  83(b) filing deadline (grant + 30 days): __________

Per-month vest after cliff = total ÷ 48 = __________ shares/month

| Milestone | Month | Shares vested (cumulative) | % vested |
|-----------|------:|---------------------------:|---------:|
| Day one          |  0  | 0          | 0%    |
| Just before cliff | 11 | 0          | 0%    |
| Cliff             | 12 | __________ | 25%   |
| Halfway           | 24 | __________ | 50%   |
| Three-quarters    | 36 | __________ | 75%   |
| Fully vested      | 48 | __________ | 100%  |
```

**Check your numbers** against the worked example below before moving on.

### Worked example (4,000,000 shares)

- Per-month = 4,000,000 ÷ 48 = **83,333 shares/month**.
- Month 12 (cliff): 12 × 83,333 ≈ **1,000,000** (25%).
- Month 24: 24 × 83,333 ≈ **2,000,000** (50%).
- Month 36: 36 × 83,333 ≈ **3,000,000** (75%).
- Month 48: **4,000,000** (100%).

(**Recommended:** build the full 0–48 month table in a spreadsheet — one row per month — and graph cumulative vested shares. Mark the cliff as the vertical jump at month 12. Paste a screenshot or the table into your file. This is the "feel the cliff" payoff.)

---

## Part 2 — Three departure scenarios

For your founder F1 (the 4,000,000-share schedule), compute what they keep and what returns to the pool in each case.

```markdown
## Departure scenarios — F1

### Scenario 1 — leaves at month 9 (before the cliff)
- Vested: __________ shares (____%)
- Returns to the pool: __________ shares
- Who is protected, and how:

### Scenario 2 — leaves at month 18 (cliff passed, mid-vest)
- Vested: __________ shares (____%)   [hint: 18 × per-month]
- Returns to the pool: __________ shares
- The hard question — what happens to the VESTED shares? (keep / buyback / depends on leaver):

### Scenario 3 — leaves at month 50 (fully vested)
- Vested: __________ shares (____%)
- Returns to the pool: __________ shares
- Note: vesting is done; the leaver keeps everything. Any clean-up the company can still do?
```

Expected answers (check yourself): Scenario 1 → **0 vested**, all 4,000,000 return; the cliff protected the company and the staying founder. Scenario 2 → 18 × 83,333 ≈ **1,500,000 vested (37.5%)**, ~2,500,000 return; the *vested* 1.5M is the genuinely hard case your departure clause exists for. Scenario 3 → **fully vested**, nothing returns.

---

## Part 3 — Acceleration and 83(b) (one line each)

```markdown
## Acceleration
On a change of control, our default is: single-trigger / double-trigger (circle one) — reasoning:
(Lecture 2 §4 — double-trigger is the usual market default; flag for a lawyer either way.)

## 83(b) reminder
Each founder must file an 83(b) election within **30 days** of their stock grant.
- F1 grant date: ______  →  83(b) deadline: ______
- F2 grant date: ______  →  83(b) deadline: ______
- Owner who will make sure it happens: ______
(No extensions. No exceptions. Missing it is an avoidable tax disaster — Lecture 2 §6.)
```

---

## Acceptance criteria

- [ ] File `exercise-03-vesting-schedule-template.md` exists in your Week 4 repo.
- [ ] A vesting schedule table is completed for **every** founder (including you), with the cliff at month 12 marked and correct numbers.
- [ ] All **three departure scenarios** are computed, with the right vested amounts.
- [ ] Scenario 2 addresses the **vested-equity question** (keep / buyback / leaver-dependent) — not just the unvested return.
- [ ] **Acceleration** choice (single- vs. double-trigger) is stated with reasoning.
- [ ] An **83(b) reminder** with each founder's 30-day deadline and a named owner is present.
- [ ] (Recommended) A spreadsheet month-by-month table and/or vesting graph is attached or linked.
- [ ] Committed.

---

## Hints

<details>
<summary>Why does 25% vest all at once at the cliff?</summary>

The cliff is "no equity for the first year, then a year's worth lands at once." Twelve months of a 48-month schedule is 12/48 = 25%. It's a deliberate test of commitment: stay a year and you've earned a real stake; leave inside the year and you've earned nothing — which is exactly the protection that lets you commit to a co-founder you've worked with for zero days.

</details>

<details>
<summary>What price does the company pay to repurchase unvested shares?</summary>

Usually the founder's **original purchase price** (often a fraction of a cent per share), because those shares were never "earned." That's why a pre-cliff departure is clean: the equity returns at almost no cost. Vested shares are different and harder — that's the §3 / Scenario-2 problem.

</details>

<details>
<summary>I'm solo — do I really vest my own shares?</summary>

Yes. Founder vesting on yourself (a) is what investors will expect, (b) makes a future co-founder relationship credible ("I'm on the same terms I'm offering you"), and (c) is harmless if you stay — you vest fully. And your 83(b) is just as real and just as deadline-bound whether you're one founder or three.

</details>

---

*Next: assemble everything into the [co-founder agreement draft](../mini-project/README.md).*
