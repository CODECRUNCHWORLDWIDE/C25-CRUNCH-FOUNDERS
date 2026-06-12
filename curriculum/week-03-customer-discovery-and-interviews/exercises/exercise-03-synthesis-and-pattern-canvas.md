# Exercise 3 — Synthesis & Pattern Canvas

**Type:** Canvas (complete once, after ≥5 interviews).
**Estimated time:** ~90 minutes.
**Output:** `discovery-dossier/dossier/SYNTHESIS.md` — a completed canvas ending in an explicit persevere/pivot/drop decision.

---

## Why this exercise

Five interviews in a folder are not evidence — they're raw material. Synthesis is the step where you turn conversations into a *pattern* you can defend, or honestly conclude there isn't one. This is where most founders either find the truth or rationalize past it, so we use a method instead of vibes. Fill this canvas in order; don't skip to the decision.

Bring two things to this exercise: all your Exercise 2 write-ups, and your **Week 2 kill criteria**.

---

## Part A — Extract the findings (15 min)

Go through every write-up and pull each distinct finding onto its own line (or sticky note, if you're working on a wall/Miro/FigJam — recommended). **One finding per line, in the customer's words.** Don't editorialize yet; just harvest.

```markdown
## Raw findings
- I-01: "the slot just sits dead when someone cancels morning-of"
- I-01: keeps a paper waitlist in a drawer
- I-02: pays for two reminder tools, neither does waitlists
- I-03: "the empty chair is the part that actually costs us"
- ...
```

## Part B — Affinity-cluster into themes (20 min)

Group findings that say the same thing. Each cluster is a **theme**. Name each theme and list which interviews contributed.

```markdown
## Themes
### Theme 1: Late-cancellation empty slots are the real pain
- Sources: I-01, I-03, I-04, I-05  (4 of 5)
- Representative quote: "the empty chair is the part that actually costs us"

### Theme 2: Existing reminder tools don't touch waitlists
- Sources: I-02, I-04  (2 of 5)
- ...
```

## Part C — Count the signal (10 min)

For each theme, fill the table. **Independent mentions** = how many distinct people raised it *unprompted*. This is the rigor that separates a pattern from a cherry-pick.

```markdown
## Signal table
| Theme | Independent mentions | Anyone committed (time/referral/money)? | Strength of workaround |
|-------|---------------------:|------------------------------------------|------------------------|
| Empty slots | 4 of 5 | 2 offered referrals; 1 asked to buy | Strong: paper list + manual texting |
| Reminder gap | 2 of 5 | none | Medium |
```

## Part D — Plot frequency vs. severity (10 min)

Place each theme on the 2×2. Frequent + severe is your target; frequent + mild is a vitamin; rare + severe is a different (often slower) business; rare + mild is dead.

```markdown
## Frequency × Severity
|              | Mild severity      | High severity        |
|--------------|--------------------|----------------------|
| **Frequent** | (vitamin)          | <-- TARGET themes    |
| **Rare**     | (drop)             | (niche / slow GTM)   |

- Empty slots:  Frequent + High  → TARGET
- Reminder gap: Frequent + Mild  → vitamin
```

## Part E — Name the dominant workaround (5 min)

What do people *do today*? A shared workaround is a product-shaped hole and your de facto spec.

```markdown
## Dominant workaround
Most clinics keep a manual waitlist (paper or a personal phone list) and
text people one at a time after a cancellation. ~20 min per incident, low hit rate.
That manual process is my competitor and my spec.
```

## Part F — Name the surprise (5 min)

The unprompted finding that wasn't your hypothesis. Be honest even (especially) when it's inconvenient.

```markdown
## The surprise
I came in about NO-SHOWS. 4 of 5 kept steering to LATE CANCELLATIONS / empty slots.
That's a different, sharper, less-served problem than I set out to test.
```

## Part G — Check the kill criteria (10 min)

Pull your Week 2 kill criteria. For each, ask the data: tripped or not? Be ruthless — moving goalposts here is how founders waste years.

```markdown
## Kill-criteria check
| Kill criterion (from Week 2) | Tripped? | Evidence |
|------------------------------|----------|----------|
| Kill if <half call it a top-3 problem | No | 4 of 5 ranked it top-3 |
| Kill if no one spends money/effort on it | No | manual workaround + paid tools |
| Kill if it happens less than monthly | No | weekly+ for most |
```

## Part H — The decision (10 min)

One explicit call, with reasoning. "I'll just build it and see" is not an option.

```markdown
## Decision: PERSEVERE / PIVOT / DROP
**Decision:** PIVOT — from "no-show reminders" to "automatic waitlist fill for late cancellations."

**Reasoning:** 4 of 5 independently described the empty-slot problem as the real, frequent,
costly pain; the existing reminder tools don't address it; no kill criterion tripped; the
surprise points clearly at the pivot. I'll keep interviewing the same segment toward 10,
with a script re-aimed at the cancellation-and-fill workflow.

**Next interviews target:** more clinic managers + front-desk staff; ask to see the actual waitlist.
```

---

## Acceptance criteria

- [ ] File at `discovery-dossier/dossier/SYNTHESIS.md`, committed.
- [ ] Raw findings extracted from **all** write-ups.
- [ ] Findings clustered into named themes with sources listed.
- [ ] A signal table with **independent-mention counts**.
- [ ] A frequency × severity placement for each theme.
- [ ] The dominant workaround named precisely.
- [ ] The surprise named honestly (or "no surprise — and here's why").
- [ ] **Every** kill criterion checked against the evidence.
- [ ] An **explicit** persevere/pivot/drop decision with reasoning.

---

## Hints

- If every theme has only 1 mention, you don't have a pattern yet — that usually means "keep interviewing toward ten," not "force a decision."
- Counting unprompted mentions is the whole game. A finding you had to fish for with a leading question doesn't count as independent signal — flag those honestly.
- A "drop" decision earns full marks here. The grade is for rigor and honesty, not for your idea surviving. Killing a weak idea cheaply *is* the win.

---

*This canvas becomes the spine of your [Discovery Dossier mini-project](../mini-project/README.md) and is graded again, expanded to ≥10 interviews, at the capstone.*
