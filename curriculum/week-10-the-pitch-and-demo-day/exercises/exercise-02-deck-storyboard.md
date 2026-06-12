# Exercise 2 — The Deck Storyboard

> **Estimated time:** ~60 minutes (35 min storyboarding all slides in text, 15 min the headline-sequence test, 10 min the red-pen pass). **Output:** a committed `exercise-02-deck-storyboard.md` that is the blueprint you build slides from — *not* the slides themselves.

This is a **worksheet**, not a slide-building task. You will not open Google Slides, Marp, or reveal.js in this exercise. The single most common way founders waste an evening is opening a slide tool and agonizing over fonts and layout *before* they know what each slide is supposed to say. The storyboard is where the deck gets honest, in cheap text, where it's a thirty-second fix instead of a thirty-minute one. Once every slide has an idea, a headline, and an evidence source, building the actual deck (Homework Problem 1) is a half-hour of formatting, not an evening of deciding what to say. The deciding happens here.

## Goal

Storyboard your 8–10 slide pitch deck in text. For each slide, write exactly three things — the one idea it carries, the headline (written as a *claim*, read in two seconds), and the evidence source that backs it — and nothing else. Then run two tests: the **headline-sequence test** (do your headlines, read alone, tell the whole story?) and the **red-pen pass** (does any headline ride on an adjective a number can't back?).

## The rule that governs every slide

**The slide is read in two seconds so you can be listened to for the other sixteen.** In a three-minute pitch over ten slides, each slide is on screen ~18 seconds. There is no time for the audience to parse a busy slide. So the slide is a billboard, not a document: one headline stated as a claim, one piece of supporting evidence visualized, nothing else. The storyboard enforces this by giving each slide exactly three fields — if you can't fill them in one line each, the slide has more than one idea and must be split or cut.

## Step 1 — Copy the template into your repo

Create `exercises/exercise-02-deck-storyboard.md` and paste this. The canonical 8–10 slide order (Lecture 1, §1.5) is pre-filled; adapt to your concept.

```markdown
# Deck storyboard — <company / concept>

> Rule: one idea per slide. Headline is a CLAIM, not a label. Every slide names its evidence.

| # | Slide | The ONE idea | Headline (a claim, ≤12 words) | Evidence source (file in repo) |
|---|-------|--------------|-------------------------------|--------------------------------|
| 1 | Title | What this is, in one line | <company> — <one-line what-it-is> | founder brief framing |
| 2 | Problem | Who hurts, how badly | <e.g. "Small clinics lose 8–12 paid slots a week to no-shows"> | discovery dossier |
| 3 | Evidence | The discovery proof (CREDIBILITY SLIDE) | <e.g. "12 of 12 clinics already pay for two tools and still lose slots"> | ≥10 synthesized interviews |
| 4 | Solution | What I built, the mechanism | <e.g. "When a patient cancels, we fill the slot from the waitlist"> | MVP + result |
| 5 | How it works | The mechanism, one visual | <one-line of how, + a screenshot/diagram> | MVP |
| 6 | Business model | Who pays, how much, the motion | <e.g. "$99/clinic/month, sold founder-led"> | lean canvas |
| 7 | Unit economics | The ratio that says scaling helps | <e.g. "~6:1 LTV:CAC, ~3-month payback"> | unit-economics sheet |
| 8 | Traction | The real number + the honest leak | <e.g. "2 clinics paying; onboarding is the leak I'm fixing"> | GTM one-pager + metric |
| 9 | Team | Why ME for THIS problem (founder-market fit) | <e.g. "2 years on a clinic front desk; I know 40 managers"> | founder brief + co-founder agreement |
| 10 | The ask | The single specific request | <e.g. "3 intros to multi-location clinic groups"> | cap-table model (if raising) / ops checklist |

## Slides I'm cutting (and why)
- <slide idea> → cut because <no evidence / second idea on another slide / decoration>

## Visual per slide (one each — chart, screenshot, big number, or one quote)
- S2: <the one visual> · S3: <the one visual> · ... · S10: <the one visual>
```

## Step 2 — Write each headline as a claim, not a label

This is the heart of the exercise. The top of every slide is a single sentence that *is the point of the slide*, not a topic word.

- "Problem" is a label. **"Small clinics lose 8–12 paid slots a week to no-shows"** is a claim.
- "Traction" is a label. **"Two clinics are paying today; the leak is onboarding"** is a claim.
- "Market" is a label. **"~30,000 reachable US clinics × $99/mo ≈ $36M serviceable"** is a claim.

The headline-as-claim does the work even if the audience reads nothing else — which is exactly what you must assume in a three-minute pitch where they're listening to you, not reading. Keep each headline under ~12 words so it's readable in two seconds.

## Step 3 — Assign exactly one visual per slide

Below each headline goes *one* thing that proves it: a single chart, a single screenshot, one big number, or one verbatim customer quote. Not three. A slide with one striking chart beats a slide with four small ones, because the room absorbs one thing in two seconds and absorbs nothing from six. Fill the "Visual per slide" section. The evidence slide (slide 3) is the clearest case: one line — "12 of 12 clinics already pay for two tools and still lose slots" — in big type with one customer quote underneath beats a wall of interview excerpts.

## Step 4 — The headline-sequence test

Read **only your headlines**, top to bottom, out loud, with nothing else. Do they form a coherent argument — problem, evidence, solution, model, traction, ask? If yes, your deck is structurally sound. If they stall or jump, you have a buried idea or a gap, and you fix it here in text. The clinic founder's headline sequence reads as a complete story on its own:

> "Small clinics lose 8–12 paid slots a week to no-shows" → "12 of 12 clinics already pay for two tools and still lose slots" → "When a patient cancels, we fill the slot from the waitlist" → "$99/clinic/month, ~6:1 LTV:CAC" → "Two clinics paying; onboarding is the leak" → "Three intros to multi-location clinic groups."

That sequence, read alone, tells a stranger the whole concept. That is the bar.

## Step 5 — The red-pen pass

Go through every headline and delete every adjective a number cannot back. "Revolutionary," "massive," "best-in-class," "game-changing" — each makes the slide look professional to a beginner and unserious to an investor. Also cut: logo clouds, "powered by AI/blockchain/cloud" banners, dense methodology footnotes. They are noise that competes with your voice. The clean slide with one claim and one proof reads as confidence; the busy slide reads as someone hiding a thin argument behind decoration.

## The "one-slide" standard

A production habit worth adopting: design every slide so it would still make sense as the *only* slide a distracted investor glances at. If they look up for exactly one slide, any slide, during your pitch, it should land a complete idea on its own. That standard enforces the one-idea discipline harder than any rule about bullet counts. Apply it to each row of your storyboard before you call it done.

## Expected output

A completed storyboard where every slide has one idea, a claim-headline, and a named evidence source; the headlines read as a coherent story; and no adjective survives that a number can't back. The clinic founder's slide 3 (the credibility slide), fully storyboarded:

```markdown
| 3 | Evidence | We did the discovery; the pattern is unanimous | "12 of 12 clinics already pay for two tools and STILL lose slots" | discovery-dossier/ (12 write-ups) |

Visual: the single line in 60pt type, plus one verbatim quote underneath:
  "The reminders aren't the problem — it's the empty slot I can't fill fast enough." — Clinic manager, interview #7
```

## Acceptance criteria

- [ ] `exercise-02-deck-storyboard.md` present with 8–10 slides, each with exactly one idea, a claim-headline (≤~12 words), and a named evidence source (a file in the repo).
- [ ] Every slide names one visual (chart, screenshot, big number, or one quote) — not a list of bullets.
- [ ] The headline-sequence test passes: headlines read alone tell the whole story (problem → evidence → solution → model → traction → ask).
- [ ] The red-pen pass is done — no decoration, no unbacked adjectives, no logo clouds.
- [ ] A "slides I'm cutting" note exists (cutting is a feature; if you cut nothing, you probably kept a weak slide).
- [ ] Committed.

## Common mistakes (and the fix)

- **Headlines are labels.** "Problem," "Solution," "Traction." Fix: rewrite each as the claim the slide makes.
- **Two ideas on one slide.** A slide carrying both the model *and* the unit economics. Fix: split into two, or cut the weaker one.
- **No evidence source.** A slide whose evidence column is blank. Fix: go get the artifact, or cut the slide — a slide your repo can't back fails the capstone's "survives a stranger" gate.
- **Building slides during this exercise.** If you opened a slide tool, stop. This is text. Build the slides in Homework Problem 1, from *this* storyboard.

---

*Next: rehearse the Q&A in [Exercise 3](./exercise-03-hard-questions-canvas.md). Build the actual deck from this storyboard in Homework Problem 1. Everything feeds the [capstone](../mini-project/README.md).*
