# Mini-Project — The Co-founder Agreement Draft

> Produce a plain-language **co-founder agreement draft** for your venture — parties and roles, decision rights, an equity split *with written reasoning*, a vesting schedule with a cliff, a departure clause that handles the unhappy path, a one-screen cap-table preview, and a list of questions for a real lawyer. Solo founders draft the equivalent: their own founder vesting plus the terms they'd offer a first key hire.

This is the Week 4 capstone deliverable and a **direct input to the C25 capstone** — the final demo-day rubric grades a "co-founder agreement draft covering roles, decision rights, equity, and vesting with a cliff." What you produce this week *is* that artifact. Do it well now and you carry it, lightly revised, to demo day.

**This is a template and a reasoning exercise, not legal advice.** When you actually form a company, have a lawyer paper it. The goal is to walk into Week 9 (and into a real lawyer's office) with a draft so clear they immediately know what to paper — and with the right vocabulary to discuss it.

**Estimated time:** ~8 hours across the week (the schedule front-loads the thinking into the exercises and homework, then Friday/Saturday assemble and polish).

---

## Where this fits in the course

You don't start this from nothing. It **compounds** on everything before it:

- **Week 1 (founder brief, control-vs-wealth lean)** → the lean is the consistency check for your split and decision rights.
- **Week 2 (chosen idea)** → the company you're splitting equity in.
- **Week 3 (discovery interviews)** → the evidence that this is a real company worth structuring, not a daydream.
- **This week's exercises and homework** → their outputs are literally the sections of this document. Exercise 1 → equity reasoning; Exercise 2 / Homework 1 → decision rights; Exercise 3 / Homework 4 → vesting + 83(b); Homework 3 → departure clause.

And it sets up what's ahead: **Week 8 (cap tables, SAFEs, dilution)** extends the cap-table preview you build here into a full dilution model; **Week 9 (incorporation, IP, legal)** turns this draft into something a lawyer papers.

So: most of the raw material already exists. This project is where you **assemble, reconcile, and pressure-test** it into one coherent agreement.

---

## What you will produce

A single file, `mini-project/COFOUNDER-AGREEMENT-DRAFT.md`, in your Week 4 repo, with **seven** sections.

### 1. Parties and roles
Who the founders are (roles/initials — no sensitive personal data in a repo), each person's primary responsibilities, and their title. One paragraph per founder. If solo: you, plus a clearly-labelled "first key hire (hypothetical)."

### 2. Decision rights
The matrix from Exercise 2 / Homework 1: each major decision, its single final-call owner, the spend threshold with a real dollar figure, each founder's domain, and explicit tiebreak rules for the company-defining shared decisions. **No blank cells.**

### 3. Equity split
The split **and** the input-by-input reasoning from Exercise 1 (idea/prior work, time, capital, skill/replaceability, opportunity cost). State the number for each founder and, in 2–4 sentences, why. Then explicitly tie it to your Week 1 control-vs-wealth lean.

### 4. Vesting
The schedule for **every** founder (4-year vest, 1-year cliff, monthly thereafter is the expected default — deviate only with a written reason). Include the cumulative-vested milestones (months 12/24/36/48) and one sentence on acceleration (single- vs. double-trigger — naming double-trigger as the default to confirm with counsel). Include the **83(b) reminder** with each founder's 30-day deadline and a named owner.

### 5. Departure terms
From Homework 3: treatment of **unvested** equity (returns to pool, at what price), **vested** equity (buyback right? price? good-leaver vs. bad-leaver?), and **IP / account handover** (reference the CIIA). Write the unhappy path while everyone's happy.

### 6. Cap-table preview
A simple one-screen table: each founder, their share count, their %, and the founder pool / option pool reserved. This is your first cap table — Week 8 turns it into a dilution model. Keep it to founders + a reserved option pool for now (no investors yet).

```
| Holder            | Shares     |   %    |
|-------------------|-----------:|-------:|
| Founder 1         |  5,500,000 |  49.5% |
| Founder 2         |  4,500,000 |  40.5% |
| Option pool (res.)|  1,111,111 |  10.0% |
| **Total**         | 11,111,111 | 100.0% |
```

(Numbers above are illustrative — a 55/45 founder split with a 10% reserved option pool. Use your own.)

### 7. Open questions for a lawyer
A short, honest list of everything you'd want a professional to review before signing — at minimum: the good-leaver/bad-leaver definition, the vested-share buyback mechanism and price, acceleration terms, the 83(b) filing, and entity/jurisdiction specifics (Week 9). This section is a *strength*, not a weakness — it shows you know the edge of your own competence.

**Include a visible note at the top of the file that this is a draft for education, not legal advice.**

---

## Acceptance criteria

You can mark the mini-project done when:

- [ ] File exists at `mini-project/COFOUNDER-AGREEMENT-DRAFT.md`.
- [ ] **All seven sections** are present and filled in for *your* venture (or solo equivalent).
- [ ] Section 2's decision-rights table has **no blank final-call cells** and a real spend threshold.
- [ ] Section 3's equity split includes **input-by-input reasoning** and an explicit **control-vs-wealth tie-in**.
- [ ] Section 4's vesting includes a **cliff** and covers **every** founder, plus an **83(b) reminder** with the 30-day deadline.
- [ ] Section 5's departure terms handle **unvested, vested, leaver provisions, and IP/handover**.
- [ ] Section 6's **cap-table preview** sums to 100% and matches the split in Section 3.
- [ ] Section 7 lists **at least five** genuine questions for a lawyer.
- [ ] A visible **"not legal advice"** note is present.
- [ ] Every clause passes the **"would you say it to their face?"** test.
- [ ] Committed and pushed; the URL posted in your cohort tracker.

---

## Suggested order of operations

You'll find it far easier to assemble than to write cold — most pieces already exist.

### Step 1 — Gather (15 min)
Open your four `notes/` homework files, your three exercise outputs, and your Week 1 founder brief. Everything you need is in them.

### Step 2 — Draft sections 1–4 (2 h)
Paste in and tighten: parties/roles, the decision-rights matrix (Exercise 2), the equity split + reasoning (Exercise 1), the vesting schedule + 83(b) (Exercise 3). Reconcile any contradictions you find between artifacts — they *will* show up, and finding them now is the point.

### Step 3 — Draft section 5, the departure clause (1.5 h)
From Homework 3. This is the hardest section. If you did the [challenge](../challenges/README.md), fold its lessons in — your day-one clause should now anticipate the month-14 vested-equity problem.

### Step 4 — Build the cap-table preview (1 h)
Put the founder shares and a reserved option pool in a table. Confirm the percentages match Section 3 and sum to 100%. A spreadsheet helps; paste the result in.

### Step 5 — The lawyer's list (30 min)
Write Section 7 honestly. What don't you know? What's jurisdiction-specific? What did you flag throughout?

### Step 6 — The face test and consistency pass (1 h)
Read the *entire* document aloud, slowly, as if your co-founder is across the table. Fix every clause that makes you wince. Then check the whole thing against your Week 1 lean one more time.

### Step 7 — Have the actual conversation (if you have a co-founder) (1 h+)
If you have a real prospective co-founder, *use this draft to have the real conversation.* That's the entire point of the week. Note where reality differed from your draft and revise. (If solo, walk an advisor or a peer through it instead.)

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|-------:|-------------------------|
| Decision rights leave no gaps | 20% | Every decision has one final-call owner; real spend threshold; tiebreaks on shared calls |
| Equity reasoning is sound and tied to the control/wealth lean | 25% | Input-by-input justification a co-founder would accept; explicit, consistent lean tie-in |
| Vesting includes a cliff and covers everyone, with 83(b) | 20% | Correct 4yr/1yr schedule for all founders; the 30-day 83(b) deadline noted with an owner |
| Departure terms handle the unhappy path | 15% | Unvested, vested, good/bad-leaver, and IP/handover all addressed and fair |
| Cap-table preview is correct and consistent | 10% | Sums to 100%; matches the split; option pool reserved |
| Lawyer-review questions identified | 10% | At least five genuine, specific questions; shows awareness of the limits of self-help |

**Passing bar:** 75%. The most common failure is a split with a number but no reasoning, or a vesting section that forgets the cliff or the 83(b) — both are graded hard because both are the whole point of the week.

---

## Stretch (optional)

- **Run the real conversation and write a one-page retro:** where did your draft survive contact with your co-founder, and where did it break? This is worth more than any other stretch.
- **Add a third-founder scenario:** model what your split and cap table become if a third co-founder joins in month 9 — who dilutes, by how much, and does the decision-rights table still work with three voices?
- **Pressure-test against the challenge:** if you did [Challenge 1](../challenges/challenge-01-the-departing-cofounder.md), rewrite your departure clause so that the month-14 vested-equity problem is *already answered* by your day-one terms.
- **Preview Week 8:** sketch what happens to each founder's % after a hypothetical $500k pre-seed on a $5M post-money SAFE. (You'll do this properly in Week 8 — this is just to feel the dilution.)

---

## Resources

- *Y Combinator — documents library (Series Seed, SAFE)*: <https://www.ycombinator.com/documents/>
- *Founder Institute — FAST Agreement* (a real vesting-based template to model on): <https://fi.co/fast>
- *Carta — "How startup equity works"* (cap tables, vesting, dilution): <https://carta.com/learn/>
- *Cooley GO — 83(b) and vesting explainers*: <https://www.cooleygo.com/documents/>
- *Holloway — Open Guide to Equity Compensation*: <https://www.holloway.com/g/equity-compensation>

---

## Submission

When done:

1. Push `COFOUNDER-AGREEMENT-DRAFT.md` to your Week 4 repo (public or shared per your cohort's norm).
2. Make sure all seven sections are present and the "not legal advice" note is visible.
3. Confirm the cap table sums to 100% and matches Section 3.
4. Post the link in your cohort tracker. If you had the real co-founder conversation, say so — that's the work that actually de-risks your company.

---

*This material is education, not legal or tax advice. An equity split decided by handshake is a lawsuit deferred; a draft you can read to your co-founder's face is a company that survives its first hard year. Next: [Week 5 — Lean MVP & Build-Measure-Learn](../../week-05-lean-mvp-and-build-measure-learn/).*
