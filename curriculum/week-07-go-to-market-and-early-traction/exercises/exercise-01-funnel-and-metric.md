# Exercise 1 — Funnel and Metric

**Goal:** Build your acquisition funnel, choose the single One Metric That Matters for your stage, and identify the leakiest step — the thing that, if fixed, moves your whole funnel the most.

**Estimated time:** 45 minutes.

**Format:** Guided. We walk every step with Maria's ClinicFlow as the worked example, then you do the same for your own startup. This is a Markdown worksheet — no code.

---

## Why this exercise

Before you run a channel test (Exercise 2) or write your one-pager (Exercise 3), you need a clear-eyed picture of how customers currently move from "never heard of you" to "paying you." Even if your numbers are rough estimates, the *shape* of the funnel tells you where to aim. Founders who skip this step optimize whatever's easiest instead of whatever's leaking, and waste weeks doing it.

---

## Step 1 — Name your motion (5 min)

From Lecture 1, pick the **single** motion that best fits your model and price point. Write one sentence stating the motion *and the reason it fits* — referencing your price/ACV and how reachable your customers are.

> **Maria:** "Founder-led sales, because clinics are a small, nameable list and at $1,188 ACV a personal demo is affordable and trust-building."

If your instinct is "a bit of everything," stop — that's the mistake Lecture 1 warns about. Force a single choice. You can revisit it after the test.

---

## Step 2 — Pick your One Metric That Matters (5 min)

From Lecture 2, name the single metric that best captures progress *at your current stage*. State the stage, the metric, and why this metric (not a flashier one) is the right one now.

> **Maria:** "Stage: early revenue. OMTM: clinics that complete a paid onboarding. Why: money in the bank with the product actually in use — it proves the whole funnel end to end, unlike demos booked or signups."

Stage cheat sheet (from Lecture 2): pre-product → letters of intent / paid waitlist; MVP → weekly activated users; early revenue → paying customers or MRR; marketplace → completed transactions.

---

## Step 3 — Name three vanity metrics you'll ignore (5 min)

List three flattering numbers you will *deliberately not optimize*, and for each, the actionable rewrite. Naming them keeps them from sneaking back in.

> **Maria:**
> - Landing-page views → rewrite: visitor → demo-request rate.
> - LinkedIn post likes → rewrite: post → clinic-reply rate.
> - "Interested!" replies → rewrite: reply → demo-booked rate.

Apply the three-question test (does it change behavior? comparable over time? a rate not a total?) to confirm each one you're setting aside really is vanity.

---

## Step 4 — Build the funnel with numbers (15 min)

Put a number on every step. Use **real data** where you have it and clearly-labeled **estimates** `(est.)` where you don't. Use the early-stage funnel skeleton:

```
Reach        →   Interest      →   Activation       →   Retention / Revenue
(saw it)         (clicked/         (did the core        (came back /
                  replied)          action once)         paid)
```

For each step, also compute the **conversion rate** from the step before.

> **Maria's funnel (real, from a 2-week test):**
> ```
> Reach (clinics contacted):        40
> Interest (replied):               12      → 30% of contacts
> Activation (took a demo):          6      → 50% of replies
> Trial started:                     3      → 50% of demos
> Revenue (paid onboarding):         2      → 67% of trials
> ```

If you have no real data yet (you haven't run anything), make honest estimates and label them — but plan to replace them with real numbers after Exercise 2's test. An estimated funnel is a hypothesis; a measured one is evidence.

---

## Step 5 — Find the leakiest step (10 min)

Look at the **rates**, not the raw counts. The leakiest step is the biggest *controllable* percentage drop — and it's often not the one that scares you at first glance. State which step it is, why it's the one to fix (not just the easiest to move), and one concrete thing you'd try.

> **Maria:** "Raw counts tempt me to panic about '2 paid from 40.' But the rates show the real leak is **demo → trial (50%)**: half the people who *see* the product walk away. That's a conviction problem, more dangerous and more informative than a volume problem. Fix idea: rebuild the demo around their actual no-show numbers instead of a generic feature tour, and end with a same-day trial setup so they don't cool off."

---

## What to produce

Create `exercises/exercise-01-funnel-and-metric.md` in your Week 7 repo:

```markdown
# Funnel & metric — <your idea>

## Chosen motion
(One sentence: the motion + why it fits your price/ACV and customer reach.)

## My One Metric That Matters
(Stage + the single metric + why this one, not a flashier one.)

## Three vanity metrics I will ignore
- <vanity> → <actionable rewrite>
- <vanity> → <actionable rewrite>
- <vanity> → <actionable rewrite>

## Funnel (numbers on every step; label estimates "(est.)")
Reach:               ___        
Interest:            ___   → __% of reach
Activation:          ___   → __% of interest
Trial (if any):      ___   → __% of activation
Retention/Revenue:   ___   → __% of prior step

## Leakiest step
(Which step, by RATE; why it's the one to fix — not just the easiest to move; one concrete fix to try.)
```

---

## Acceptance criteria

- [ ] File present; motion chosen with a one-sentence reason tied to price/ACV and reach.
- [ ] One metric named for your current stage, with justification.
- [ ] Three vanity metrics explicitly set aside, each with an actionable rewrite.
- [ ] Funnel with a number on **every** step, estimates labeled, conversion rates computed.
- [ ] Leakiest step identified **by rate** with a reason and a concrete fix.
- [ ] Survives the skeptic's test: a reviewer would call this a real funnel, not a wish.
- [ ] Committed to your Week 7 repo.

---

## Hints

- If your chosen motion is **paid ads** but your audience is tiny and nameable, or your price is low, reconsider — the motion probably doesn't fit (Lecture 1's price-point ladder).
- **Retention is the truest signal.** If you can estimate even a rough "do they come back," include it — a leaky bucket changes everything.
- Don't optimize the step that's *easiest* to move. Optimize the step that's *leaking the most.* They're often different.
- If two steps have similar drops, prefer fixing the one closer to revenue first — it converts work into money faster.

---

*Next: design the experiment that will replace your estimates with real numbers — [Exercise 2 — Channel test plan](exercise-02-channel-test-plan.md).*
