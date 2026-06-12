# Exercise 2 — Decision-Rights Matrix

**Goal:** Turn "we'll figure it out as we go" into a written table where every decision that can cause a founder fight has a named **final-call owner** and, where the call is shared or contested, an agreed **tiebreak rule**. A blank cell here is a future fight; the entire exercise is to leave no blank cells.

**Estimated time:** 40 minutes.

**You produce:** a completed worksheet, `exercise-02-decision-rights-matrix.md`, in your Week 4 repo. This is a **business worksheet** — fill in the template below. No code.

---

## Why this exists

Titles ("I'm CEO, you're CTO") are for the outside world. **Decision rights** are for the inside: when you two genuinely disagree and the clock is running, who decides? A 50/50 team with two equal voices and no tiebreaker deadlocks on exactly the decisions that matter most. This worksheet forces the conversation now, while it's cheap. (Lecture 1 §2.)

We use a lightweight **RACI** vocabulary — but the only column you cannot leave blank is **Final call (A — Accountable)**.

| Letter | Meaning | In founder terms |
|---|---|---|
| **A — Accountable** | The single person who owns the decision and breaks the tie | **Required for every row** |
| **R — Responsible** | Who does the work to inform/execute it | Often the same person, sometimes not |
| **C — Consulted** | Whose input is sought before deciding | "We talk first, then A decides" |
| **I — Informed** | Who's told after | |

For each decision, exactly **one** person holds **A**. If you're tempted to write "both," that's the signal you need a tiebreak rule, not a shared A.

---

## The worksheet

Copy this into your file and fill every cell. Replace `F1`, `F2` (and `F3` if you have three founders) with initials/roles.

```markdown
# Decision-rights matrix — <company / your name>

Founders: F1 = ____ (role)   F2 = ____ (role)   [F3 = ____]

| # | Decision | A (final call) | R | C | I | Tiebreak rule (if A is contested) |
|---|----------|----------------|---|---|---|------------------------------------|
| 1 | Product direction / whether to pivot        | ? | ? | ? | ? | ? |
| 2 | Hiring (who, when)                           | ? | ? | ? | ? | ? |
| 3 | Firing / letting someone go                  | ? | ? | ? | ? | ? |
| 4 | Pricing and packaging                        | ? | ? | ? | ? | ? |
| 5 | Whether to raise, and on what terms          | ? | ? | ? | ? | ? |
| 6 | Any single spend above $______ (set X)       | ? | ? | ? | ? | ? |
| 7 | Equity / option grants to new hires          | ? | ? | ? | ? | ? |
| 8 | Brand, public messaging, who speaks for us   | ? | ? | ? | ? | ? |
| 9 | Tech architecture / build roadmap            | ? | ? | ? | ? | ? |
| 10| Taking the company in a materially new direction | ? | ? | ? | ? | ? |

## The spend threshold
We agree that any single spend above **$______** requires: (sign-off rule)

## Domains
F1 owns the final call inside this domain: ...
F2 owns the final call inside this domain: ...

## Genuinely shared decisions (the dangerous ones)
For #1 and #10 (pivot / new direction), our tiebreak is: ...
(e.g., "CEO breaks ties" OR "requires both — a deliberate mutual veto")

## What happens when we still can't agree
If the tiebreak rule itself fails or feels unfair in the moment, our escalation is: ...
(e.g., "sleep on it 48h, then the A-owner decides"; "bring in our shared advisor X")
```

---

## How to fill it well

**Divide by competence, then give each owner the final call in their lane.** The pattern that works for most two-founder teams: the CEO owns fundraising, hiring/firing, pricing, and public messaging; the CTO owns architecture and the build roadmap. Inside your lane, you decide. (Lecture 1 §2.)

**The shared rows are where it gets real.** "Whether to pivot" (#1) and "materially new direction" (#10) can't usually be put in one person's lane. For these you must pick a tiebreak and write it down. Two honest options:
- *"CEO breaks ties"* — someone can always move the company forward.
- *"Requires both"* — a deliberate mutual veto; nothing this big happens unless you both agree. Slower, but no one gets steamrolled.
Either is defensible. *Undecided* is not.

**Set the spend number.** "Any spend above $X needs both signatures" only works if X is a real number. Pick one ($500? $2,500? $10,000?) appropriate to your stage. A blank X means the first budget overrun is a surprise fight.

**Check it against your control-vs-wealth lean.** A control-leaning founder will hold more A's; a wealth-leaning founder will share more decision rights to keep a strong co-founder motivated. If your table contradicts your Week 1 lean, resolve it.

---

## The test

Before you call it done: **read the whole table out loud, slowly, imagining your co-founder across the table.** Any row that makes you wince — "I quietly gave myself the final call on firing and I'm hoping they won't notice" — is the exact conversation you must have *now*, not later. The wince is the feature.

---

## Worked example (Ana / Ben — don't copy, derive)

| # | Decision | A | Tiebreak |
|---|---|---|---|
| 2 | Hiring | Ana (CEO) | — (her lane) |
| 5 | Whether/how to raise | Ana (CEO) | — (her lane), Ben consulted |
| 9 | Tech architecture | Ben (CTO) | — (his lane) |
| 1 | Whether to pivot | shared | Requires both; if stuck 1 week, CEO decides |
| 6 | Spend > $2,000 | shared | Both must sign |

Ana holds more A's, consistent with her larger 55% stake and her stated control lean — but Ben has an unambiguous lane (architecture) and a real voice on the company-defining calls. Both can say the table out loud to each other.

---

## Acceptance criteria

- [ ] File `exercise-02-decision-rights-matrix.md` exists in your Week 4 repo.
- [ ] All ten decision rows have a single named **A (final call)** — **no blank A cells**.
- [ ] The spend threshold **$X is a real number**, with a sign-off rule.
- [ ] Each founder's **domain** (where they own the final call) is stated.
- [ ] The genuinely shared rows (#1, #10) have an **explicit tiebreak rule**.
- [ ] An **escalation path** for when the tiebreak itself fails is written down.
- [ ] The table is consistent with your control-vs-wealth lean (or the contradiction is explained).
- [ ] Committed.

---

## Hints

<details>
<summary>"We're 50/50 and we trust each other, do we really need this?"</summary>

50/50 trust is exactly *why* you need it. Trust doesn't resolve a real disagreement about whether to take a low-ball acquisition offer; a tiebreak rule does. The agreement isn't a sign you distrust each other — it's the thing that lets you stay friends *through* a hard disagreement.

</details>

<details>
<summary>Solo founder?</summary>

Fill it as "who will own this once I hire for it, and where do I keep the final call." It clarifies which decisions you'll delegate and which define your control lean before you ever bring someone on.

</details>

---

*Next: [Exercise 3 — Vesting-schedule template](./exercise-03-vesting-schedule-template.md).*
