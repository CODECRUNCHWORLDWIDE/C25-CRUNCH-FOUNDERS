# Exercise 1 — Riskiest Assumption

**Goal:** Surface every assumption your idea depends on, score them on uncertainty × fatality, and choose the single one your MVP will test — plus the cheapest MVP type to test it. By the end you'll have a one-sentence riskiest-assumption hypothesis that drives the rest of the week.

**Estimated time:** 45 minutes.

**You'll need:** your Week 2 idea statement and your Week 3 interview pattern summary open beside you. The riskiest assumption usually hides in the gap between "what I believe" and "what my interviews actually proved."

---

## Why this exercise exists

You can only run one good experiment this week. Pick the wrong assumption to test and you'll spend two days proving something that didn't matter. This exercise is the filter: it forces you to enumerate what *must be true*, score it for danger, and aim the MVP at the load-bearing belief — not the comfortable one.

---

## Step 1 — Dump every assumption (no filtering)

List everything that must be true for your idea to work. Don't judge yet — get them all out. Aim for **at least 8**. Prompt yourself across these categories:

- **Demand** — that the problem is painful enough that people will act.
- **Adoption / behavior change** — that people will actually change what they do to use this.
- **Willingness to pay** — that someone will pay, and pay enough.
- **Reachability** — that you can find and acquire customers affordably.
- **Solution efficacy** — that your solution actually solves the problem.
- **Feasibility** — that you can technically build/deliver it.
- **Retention** — that they'll keep using it, not try it once.

Write each as a plain declarative sentence: *"Front-desk staff will adopt a new tool in the chaos of their day."*

## Step 2 — Score on two axes (1–5)

For each assumption, score:

- **Uncertainty** — how unsure are you it's true? (5 = no idea; 1 = near-certain)
- **Fatality** — if false, how badly does it hurt? (5 = company is dead; 1 = survivable)

Multiply for the **risk score**. The highest is your riskiest assumption.

> **Honesty check:** if your scariest assumption isn't near the top, you're probably scoring optimistically. The belief you *least want to test* is usually the one you most need to.

## Step 3 — State the riskiest assumption as a hypothesis

Take the top-scoring row and rewrite it as a falsifiable hypothesis (you'll formalize the threshold in Exercise 2):

> *"We believe \[segment] will \[behavior] because \[reason]."*

## Step 4 — Pick the cheapest MVP type that could falsify it

From the five archetypes (fake door, concierge, Wizard of Oz, clickable prototype, single-feature build), pick the **cheapest** one that could actually prove this assumption *false*. Write one sentence justifying *why it's the cheapest test of THIS assumption* — not just an MVP type you like.

## Step 5 — Name the metric and a draft threshold

State the one behavioral metric the MVP will move, and a draft success threshold. You'll lock this in Exercise 2; here, just get a first number on paper.

---

## What to produce

Create `exercises/exercise-01-riskiest-assumption.md` in your Week 5 repo:

```markdown
# Riskiest assumption — <your idea>

## Assumption list (scored)
| Assumption | Uncertainty (1–5) | Fatal if false? (1–5) | Risk score |
|------------|:-----------------:|:---------------------:|:----------:|
| People will adopt this in their daily workflow | 5 | 5 | 25 |
| They'll pay at least $X/mo | 4 | 4 | 16 |
| ...(at least 8 rows)... | | | |

## My riskiest assumption (as a hypothesis)
We believe <segment> will <behavior> because <reason>.

## Chosen MVP type + why it's the cheapest test of THIS assumption
<fake door / concierge / Wizard of Oz / clickable prototype / single-feature build>
Why cheapest: <one sentence>

## Draft metric and threshold (locked in Exercise 2)
Metric: ___   ·   Draft success = at least ___
```

---

## Worked example (Maya — clinic no-shows)

| Assumption | Uncertainty | Fatality | Risk score |
|---|:-:|:-:|:-:|
| Front desks will adopt / hand off refills | 5 | 5 | **25** |
| Patients respond fast enough to fill slots | 4 | 5 | 20 |
| Clinics will pay $99/mo | 4 | 4 | 16 |
| We can reach clinics affordably | 3 | 4 | 12 |
| Clinics have enough cancellations to matter | 2 | 5 | 10 |
| We can integrate with their scheduler | 2 | 3 | 6 |

- **Riskiest assumption (hypothesis):** *We believe small-clinic front desks will hand off same-day cancellation refills to us because the manual scramble is the worst part of their day.*
- **Chosen MVP type:** Concierge. *Why cheapest:* it tests both adoption and solution efficacy by hand for two clinics in one week, with zero engineering — a build would take weeks and test nothing more.
- **Draft metric / threshold:** refill rate · success = at least 30%.

---

## Acceptance criteria

You can mark this exercise done when:

- [ ] File `exercises/exercise-01-riskiest-assumption.md` exists with at least **8 assumptions**, each scored on both axes.
- [ ] One riskiest assumption is chosen (highest risk score) and stated as a falsifiable hypothesis.
- [ ] An MVP type is chosen with a one-sentence justification that it's the *cheapest test of this specific assumption*.
- [ ] A single behavioral metric and a draft threshold are named.
- [ ] The file is committed to your Week 5 repo.

---

## Hints

- If your chosen MVP requires weeks of coding, you almost certainly picked a *build* when a fake door or concierge would do. Reach for the cheaper type.
- "We can build it" is rarely the riskiest assumption for non-deep-tech ideas. Adoption and willingness-to-pay usually are.
- A good behavioral metric is a *deed*, not a *word*: "clicked Buy," "let us run it," "came back day three" — never "said they liked it."
- The threshold must be a number where, below it, you'd genuinely doubt the idea. If no number would make you doubt, you haven't found the real risk yet.

---

*Next: turn this into a runnable experiment in [Exercise 2 — MVP Spec Canvas](./exercise-02-mvp-spec-canvas.md).*
