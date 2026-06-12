# Exercise 1 — The Pitch Outline

> **Estimated time:** ~50 minutes (20 min drafting, 15 min cutting and tying claims to evidence, 15 min reading aloud and timing). **Output:** a committed `exercise-01-pitch-outline.md` in your capstone repo that is the spine of your deck and your recording.

This is the exercise everyone underestimates, because it looks like a fill-in-the-blanks table. It is not. Outlining the pitch *first*, in text, before you open a slide tool or hit record, is what separates a tight three minutes from a rambling four-and-a-half that gets cut off at the model slide. You are not writing slides yet. You are deciding, beat by beat, exactly what you will say, how many seconds it gets, and — the part that matters most — which deliverable in your repo backs the claim. If a beat has no deliverable behind it, you have found a hole in your evidence here, at the cheapest possible moment to fix it.

## Goal

Produce a beat-by-beat outline of your 3-minute pitch on the reliable six-beat structure (Lecture 1, §1.2), with a timing budget that sums to ≤180 seconds, a one-line script for each beat, and the deliverable that backs every evidence-bearing claim. Then read it aloud, timed, and confirm it lands under 3:00.

## Why outline before you build

Three reasons, each a lesson the lecture made:

1. **The clock is the forcing function.** Three minutes is short on purpose. You cannot hide a weak problem behind a long product tour when the problem gets 20 seconds. Budgeting the seconds *before* you write the slides forces you to lead with what matters and cut everything else.
2. **The evidence column is a comprehension test.** When you try to name the deliverable behind each claim and cannot, that is not a formatting gap — it is a hole in your evidence. Better to find it now, in a text table, than on stage when someone asks "how do you know that?"
3. **Text is cheap to change; slides are not.** You will rewrite this outline five times in twenty minutes. Rewriting five slides takes an evening. Do the agonizing here, where it costs nothing.

## Step 1 — Copy the template into your repo

Create `exercises/exercise-01-pitch-outline.md` and paste this skeleton. Fill the bracketed parts with *your* concept.

```markdown
# Pitch outline — <company / concept name>

> One-line "what it is" (the sentence a stranger could repeat): <____>

## The six beats

| Beat | Seconds | What I say (one line, in my own words) | Backed by (deliverable in repo) |
|------|--------:|----------------------------------------|---------------------------------|
| Problem  | 20 | <who hurts, how badly, one real person> | founder brief / discovery dossier |
| Evidence | 40 | <count of interviews + the pattern + what they pay today> | discovery dossier (≥10 synthesized) |
| Solution | 30 | <what I built, the mechanism, one visual> | MVP / clickable prototype + result |
| Model    | 30 | <price + one unit-econ headline ratio + payback> | lean canvas + unit-economics sheet |
| Traction | 30 | <the strongest REAL number + the honest leak> | GTM one-pager + traction metric |
| Ask      | 20 | <the single specific request, matched to this room> | cap-table model (if raising) / ops checklist |

Total budget: 170s — leaves a ~10s buffer under the 3:00 cap.

## My three hard-question answers (one line each, evidence-based)
1. "How do you know this is a real problem?" → <____>  (backed by: ____)
2. "Why will customers choose you — and why now?" → <____>  (backed by: ____)
3. "Can this make money — and how big can it get?" → <____>  (backed by: ____)

## My riskiest assumption (stated calmly, in one sentence)
> The thing that, if wrong, sinks this is: <____>. I'm testing it right now by <____>, and the early signal is <____>.

## Pitch shape (circle one)
- [ ] Fundraising pitch — ends with a money ask, leans on the model (Lecture 1, §1.9d)
- [ ] Evidence pitch — ends with a next-experiment ask, leans on what I've validated (most of you)
```

## Step 2 — Draft each beat, in your own voice

Write the one-line script for each beat. The discipline per beat (from Lecture 1, §1.3):

- **Problem (20s).** One sentence, one real person's pain. *Weak:* "Scheduling is broken." *Strong:* "A two-doctor clinic loses 8–12 paid slots a week to no-shows, and every empty slot is revenue that never comes back." Make the room picture someone.
- **Evidence (40s) — the most seconds, for a reason.** Lead with the count and the pattern: "I interviewed 12 clinic managers; every one already pays for two tools and still loses slots." This is your credibility beat. If you have fewer than 10 synthesized interviews, say the honest number and the pattern so far — do not inflate it.
- **Solution (30s).** *Now* reveal what you built, and only the mechanism, not a feature tour. One sentence of how it works, one visual or 10-second prototype clip.
- **Model (30s).** One price, one ratio, one payback number. "$99/month, ~6:1 LTV:CAC, ~3-month payback." Not a P&L.
- **Traction (30s).** The strongest *real* evidence, and name the leak. Paying customers > trials > signups > followers. "Two clinics paying, and the honest leak: only a third of demos start a trial — that's what I'm fixing next."
- **Ask (20s).** One specific thing, matched to *this* room, the last thing they hear. "Three warm intros to multi-location clinic groups." Not "we're looking for support."

## Step 3 — Run the red-pen pass

Go through every line and delete every adjective a number cannot back. "Revolutionary," "massive," "game-changing," "incredible," "huge market" — each is a claim with no evidence, and a skeptical room reads each as a small lie. If the adjective has a number behind it, replace the word with the number ("a $2,400/year problem for each of ~90,000 small clinics"). If it does not, cut it. The outline that survives the red-pen pass is the one that survives the room.

## Step 4 — Tie every claim to a deliverable

For each evidence-bearing beat, fill the right-hand column with the *specific* artifact in your repo that backs it. Not "my research" — the file. `discovery-dossier/`, `unit-economics/`, `gtm/`. If you cannot name the file, you have two choices: go get the evidence, or cut the claim and rewrite the beat around what you *can* back. There is no third option that survives Q&A.

## Step 5 — Read it aloud, timed

Out loud, with a timer — not in your head. People read silently ~40% faster than they speak, so a pitch that "feels" like three minutes on the page is often four spoken. Cut until you land at **2:50 spoken**, not 3:05. If you run long, the beat to compress is almost always the solution or the model — never the evidence (that is your credibility) and never the ask (that is your close).

## Expected output

A completed outline that reads cleanly top to bottom and, read aloud, lands under 3:00. Here is the clinic founder's filled-in version as a reference for the *altitude* (yours uses your own numbers):

```markdown
# Pitch outline — WaitFill (waitlist auto-fill for small clinics)

> One-line: "When a patient cancels, we instantly fill the slot from the clinic's waitlist."

| Beat | Seconds | What I say | Backed by |
|------|--------:|------------|-----------|
| Problem  | 20 | "A two-doctor clinic loses 8–12 paid slots a week to no-shows; nobody fills them." | discovery dossier |
| Evidence | 40 | "12 clinic managers interviewed; all 12 already run two tools and still lose slots; the pain is the empty slot, not the missed appt." | discovery dossier (12 write-ups) |
| Solution | 30 | "WaitFill offers the open slot to the next person on the waitlist and books whoever says yes first." [10s clip] | mvp/ + result |
| Model    | 30 | "$99/clinic/month; ~6:1 LTV:CAC; ~3-month payback." | unit-economics/ |
| Traction | 30 | "Two clinics paying via founder-led sales; honest leak: only ~⅓ of demos start a trial — onboarding is next." | gtm/ |
| Ask      | 20 | "Three warm intros to multi-location clinic groups — the channel I want to test next." | — |

Total: 170s.

## Hard-question answers
1. Real problem? → "11 of 12 described the same pain in the same words; all pay for tools that don't solve it." (discovery dossier)
2. Why you / why now? → "Two years running a clinic front desk; small clinics now run cloud scheduling I can integrate with." (founder brief)
3. Make money / how big? → "~6:1 LTV:CAC; ~30,000 reachable US clinics at $99/mo ≈ $36M serviceable." (unit economics, bottom-up)

## Riskiest assumption
> Clinics will trust an automated system to message patients without a human approving each one. Testing it now with an "approve-before-send" mode; early adopters are comfortable, mainstream unknown.

## Pitch shape: [x] Evidence pitch
```

## Acceptance criteria

- [ ] `exercise-01-pitch-outline.md` present in the repo with all six beats, a one-line script each, and a timing budget summing to ≤180 seconds.
- [ ] Every evidence-bearing beat (evidence, solution, model, traction) names the *specific* deliverable that backs it.
- [ ] The red-pen pass is done — no adjective survives that a number cannot back.
- [ ] Three hard-question answers drafted, each citing a deliverable.
- [ ] The riskiest assumption is stated in one calm sentence with the test you're running.
- [ ] You read it aloud with a timer and it lands under 3:00 spoken.
- [ ] Committed.

## Common mistakes (and the fix)

- **Opening with the solution.** "We built an app that…" before the room knows whose pain it solves. Fix: problem and evidence first, solution third.
- **The evidence beat is thinnest.** It should be your *longest* beat. If yours is one vague line, your credibility beat is your weakest — go add the count and the pattern.
- **A grab-bag ask.** Five requests, none specific. Fix: one ask, matched to the room, the last thing they hear.
- **Budget sums to 190+.** You will run over live. Cut the solution or model beat until the total is ≤170s with a buffer.

---

*Next: storyboard the deck in [Exercise 2](./exercise-02-deck-storyboard.md), then rehearse the Q&A in [Exercise 3](./exercise-03-hard-questions-canvas.md). Everything feeds the [capstone](../mini-project/README.md).*
