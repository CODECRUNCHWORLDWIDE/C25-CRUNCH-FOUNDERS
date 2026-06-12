# Mini-Project — The Idea-Triage Log

> Generate a problem-first inventory, score 5–10 candidates against an honest five-axis filter, run free desk validation on your top two, and commit to **one** idea — stated as a problem, armed with falsifiable kill criteria and five reachable interview targets — to carry into Week 3 discovery.

This is the deliverable the whole week builds toward, and it is the first compounding artifact of the C25 capstone. The single idea you commit to here is the idea you interview ten people about in Week 3, model the unit economics of in Week 6, test with an MVP in Week 5, and pitch on demo day in Week 10. **Choose it like it matters, because it does.** This is not a worksheet you throw away; it is the foundation the next eight weeks stand on.

**Estimated time:** ~10 hours, spread across Friday, Saturday, and Sunday in the suggested schedule (the desk-validation passes are the time sink, and they are worth it).

---

## What you will produce

A single file, `IDEA-TRIAGE-LOG.md`, committed to your Week 2 repo, containing five sections:

1. A **triage table** scoring 5–10 candidate problems on the five-axis filter.
2. **Desk-validation notes** for the top two candidates.
3. **The commitment** — one idea, stated as a problem.
4. **Kill criteria** — 3–5 falsifiable, numeric conditions that would make you drop it.
5. **Five interview targets**, named by role, that you can reach in Week 3.

The exercises already produced most of the raw material. The mini-project is largely **assembly plus one hard decision** — but the decision is the whole point, so don't rush it.

---

## How this compounds (the through-line)

This is week two of a ten-week sequence, and almost nothing here is throwaway:

| Week | What it does with your committed idea |
|------|----------------------------------------|
| **2 (now)** | Commit to one problem, with kill criteria and interview targets. |
| **3** | Run ten discovery interviews against *this* problem; check results against *these* kill criteria. |
| **5** | Build the cheapest MVP that tests this problem's riskiest assumption. |
| **6** | Model unit economics (CAC, LTV, payback) for *this* customer. |
| **7** | Pick a go-to-market motion to reach *these* interview targets at scale. |
| **10** | Pitch *this* idea, with *this* evidence, in three minutes. |

If you pick a weak or unreachable idea here, you carry that weakness for eight weeks. The cheapest time to fix a bad idea is *now*, on paper, before you've spent a single interview. That is exactly what honest scoring and kill criteria are for.

---

## Prerequisites (do the exercises first)

You should arrive at the mini-project having completed:

- [Exercise 1 — Problem inventory](../exercises/exercise-01-problem-inventory.md): 15+ problems, first-cut to a shortlist of 5–10 painkillers with standing.
- [Exercise 2 — Triage filter worksheet](../exercises/exercise-02-triage-filter.md): your shortlist scored on all five axes, with the soft spot of your top idea named.
- [Exercise 3 — Desk-validation canvas](../exercises/exercise-03-desk-validation-canvas.md): the four desk passes run on your top two candidates.

If those are done honestly, the mini-project is 60% assembly. If you skipped them, do not fake the log — go back and do the work. The log is only as good as the inputs.

---

## Section-by-section spec

### 1. Triage table

Pull the scored table from Exercise 2. At least **five** rows, each a problem stated in one sentence with **no solution named**.

| Idea (problem, no solution) | Painkiller | Frequency | Standing | Reachability | Pay signal | **Total /25** |
|------------------------------|:---------:|:---------:|:--------:|:------------:|:----------:|:-------------:|
| _e.g._ Small clinics lose 10–15% of bookable revenue to no-shows they can't fill | 5 | 5 | 5 | 4 | 4 | **23** |
| _(your problem)_ | | | | | | |

Rules:
- Score each axis 1–5 against the Exercise 2 rubric.
- **No row may be a straight column of 5s** unless you append a one-line defense of why each 5 is genuinely real.
- Sort descending by total. The top two carry into Section 2.

### 2. Desk validation (top two)

For each of the two highest scorers, summarize the four passes from Exercise 3 in a few tight lines:

- **Search demand** — the slope and the most telling autocomplete / "people also ask" finding.
- **Existing alternatives** — **named, with links**, and typed (competitor / spreadsheet / intern-VA / duct-tape / nothing). "There are some competitors" is not acceptable; name them.
- **Willingness-to-pay signal** — the strongest costly signal you found (a paid tool + price, hours spent on a manual workaround), not a vanity signal.
- **One-line verdict** — stronger or weaker than the triage score suggested, and your revised estimate /25.

### 3. The commitment

- **The one idea I carry into Week 3:** state the **problem**, not the solution, in one sentence.
- **Why this one** (2–3 sentences): reference the scores and the desk-validation findings. If your top two were close, state your tie-break (reachability → standing → pay signal).
- **Why now** (one sentence): what recently changed — a technology shift, a regulation, a behavior change — that makes this the right moment. (You'll expand this for the Week 10 pitch.)

### 4. Kill criteria

Write **3–5** kill criteria. Each must be **specific** (names a number or a clear condition), **falsifiable** (an outcome could prove it true or false), and **decided in advance** (you're writing it before the Week 3 interviews). Cover at least:

- **Problem reality** — a threshold on how many of 10 interviewees confirm a recurring, costly pain.
- **Workaround existence** — whether people actually do something about it today.
- **Reachability** — whether you can assemble the discovery sample at all.
- **Dissatisfaction** — whether the current solution is genuinely painful or merely present.

> Good: *"If fewer than 6 of 10 interviewees describe this as a recurring, costly pain they've acted on in the last month, I drop it."*
> Bad: *"If it seems like a bad idea."*

### 5. Five interview targets (by role)

Name **five** people or roles you can plausibly reach for Week 3 discovery — by role and relationship, **never private contact info in a committed file**. ("Office manager at the clinic I worked at," "two freelancer friends from my old agency," "a practice-owner my aunt knows.") If you can't name five, that *is* a finding: your reachability score was inflated, and you should re-examine whether this is the right idea for *you*.

---

## Worked example (shape only — clinic no-shows)

```markdown
## 3. The commitment

**The one idea I carry into Week 3:**
Small clinics lose 10–15% of bookable revenue to no-shows and last-minute
cancellations they can't fill in time.

**Why this one:** Highest triage score (23/25) and desk validation made it
stronger, not weaker — incumbents send reminders but nobody auto-fills the
canceled slot from a waitlist, which is the actual revenue leak, and clinics
already pay $200–400/mo for the adjacent reminder tools. Reachability beat my
second idea (a tutor-scheduling tool, 18/25) on the tie-break: I know ~20
office managers personally and can message them this week.

**Why now:** Cheap SMS APIs plus clinics' post-2020 comfort with software in
their booking flow make automated waitlist-fill finally feasible; the pain is
old, the cheap fix is new.

## 4. Kill criteria
1. If fewer than 6 of 10 office managers call no-show revenue loss a recurring,
   costly pain they track, I drop it.
2. If nobody currently keeps a manual list/process to fill canceled slots, I drop it.
3. If I can't get 10 office managers to a 20-minute call within two weeks, I drop it.
4. If every interviewee is satisfied with their current reminder tool and can't
   name a complaint about empty chairs, I drop it.

## 5. Five interview targets (by role)
1. Office manager at the dental clinic I worked at (3 years; warm).
2. Practice owner — referral from #1.
3. Front-desk lead at a competing clinic (LinkedIn, 2nd-degree).
4. Billing coordinator — my dentist's office.
5. Multi-location operations manager — friend's spouse runs ops for a small chain.
```

---

## Acceptance criteria

You can mark this mini-project done when:

- [ ] File exists at `mini-project/IDEA-TRIAGE-LOG.md` in your Week 2 repo.
- [ ] Triage table with **at least five** scored ideas, each stated as a problem with no solution named, sorted by total.
- [ ] **No straight column of 5s** (or a written defense of each 5 if one genuinely warrants it).
- [ ] Desk validation for the **top two** candidates, with alternatives **named and linked** and at least one **costly** (paid-tool or hours-spent) signal cited per idea.
- [ ] **Exactly one** idea committed, stated as a problem, with a "why this one" and a one-line "why now."
- [ ] **3–5** kill criteria, every one specific, falsifiable, and numeric/threshold-based.
- [ ] **Five** interview targets named by role (no private contact info committed).
- [ ] Committed to Git with a sensible message.

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|------:|--------------------------|
| Ideas stated as problems, not solutions | 20% | Every row passes the one-sentence test; not a single "an app that…" |
| Honest scoring | 20% | No inflated columns; the top idea's soft spot is visible and acknowledged |
| Desk validation cites real, costly signals | 20% | Alternatives named and linked; a real price or hours figure, not "sounds cool" |
| Kill criteria are specific and falsifiable | 20% | Every criterion has a number/threshold you could actually test in Week 3 |
| A single, reachable idea is committed | 20% | One idea, five nameable targets, a defensible "why this one" and "why now" |

A log that hedges (carries two ideas), inflates (all 5s), or hand-waves validation ("there's clearly demand") fails even if the writing is polished. The discipline *is* the grade.

---

## Common ways this goes wrong (read before you submit)

- **Committing to two ideas "to be safe."** This is the most common failure and it's a trap — spreading ten interviews across two ideas gives you two inconclusive read-outs. Pick one.
- **Kill criteria you can't test.** "If the market is too small" is untestable in a Week 3 interview. "If fewer than 5 of 10 confirm a recurring pain" is. Every criterion must be answerable by the discovery work you're about to do.
- **Inflated reachability.** "I could probably find them" is not five named targets. If you can't list five people by role, your reachability score was a wish.
- **Solution language creeping into the problem.** "The problem is there's no AI tool for X" is a solution wearing a problem's clothes. The problem is the pain; the AI tool is one possible answer.
- **Treating desk validation as confirmation.** It isn't. It kills obvious losers and sharpens survivors. Confirmation is Week 3's job. Your verdict should end with the question only interviews can answer.

---

## What this prepares you for

- **Week 3 — Customer Discovery & Interviews.** You walk in with one idea, five targets, and kill criteria. Discovery either confirms the pain or trips a kill criterion — and because you wrote the criteria *before* falling in love, you'll honor the outcome.
- **Week 5 — Lean MVP.** The "riskiest assumption" you'll test with an MVP is usually the soft spot you named in triage and the question your desk validation couldn't answer.
- **Week 6 — Unit economics.** The "what would one customer pay" line from your desk validation becomes the starting anchor for LTV.
- **Week 10 — The pitch.** "Problem → evidence" is the first third of your demo-day pitch, and this log is where the evidence trail begins.

---

## Resources

- *How to Get Startup Ideas* — Paul Graham: <https://www.paulgraham.com/startupideas.html>
- *Customer Development Manifesto* — Steve Blank: <https://steveblank.com/2009/10/29/customer-development-manifesto-reasons-for-the-revolution-part-1/>
- *Y Combinator Startup Library* (idea & validation tracks): <https://www.ycombinator.com/library>
- *Google Trends*: <https://trends.google.com/trends/>

---

## Submission

1. Commit `IDEA-TRIAGE-LOG.md` to your Week 2 repo with a sensible message (e.g. `Idea-triage log: committed to clinic no-show problem`).
2. Make sure the committed file carries **no private contact information** — targets are named by role and relationship only.
3. Read your kill criteria aloud to a peer or your cohort and let them make them *sharper, not nicer*. Revise and re-commit if needed.
4. You now have one idea, stated as a problem, with evidence and a falsifiable contract. Continue to [Week 3 — Customer Discovery & Interviews](../../week-03-customer-discovery-and-interviews/) and test it against ten real people.

---

*The idea is not the asset. The validated problem is. Triage ruthlessly; commit only to one — then go find out if you were right.*
