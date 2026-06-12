# Exercise 2 — Lean Canvas Worksheet

**This is a worksheet/template, not a reading.** Copy the template block below into a file in your Week 6 repo (or print it), and fill every field for *your* concept. It's the full version of the canvas you sketched in Exercise 1 — same nine blocks, more room and more prompts. A completed worked example (Maya's clinic SaaS) follows the template so you can see the altitude expected. **You write zero code.** Single-line answers; compression is the discipline.

**Estimated time:** ~40 minutes.

---

## How to use this worksheet

1. Fill the blocks **in number order** (1 → 9). The numbers are the fill order, not the visual layout — Problem and Customer first, Unfair Advantage last.
2. **One line per prompt.** If it takes a paragraph, you don't understand it yet.
3. **Don't invent for empty boxes.** Write `(EMPTY — riskiest assumption)`. Empty boxes are your test list.
4. Pull the numbers in blocks 6 and 7 forward into Exercise 3 (the unit-economics sheet). This canvas *is* the assumption set that sheet needs.
5. Re-read the "common ways the canvas lies" section of Lecture 1 before you call it done, and self-check against it.

---

## The template — copy and fill

```markdown
# Lean Canvas — <your concept> — <date>

## 1. PROBLEM
- Top problem:
- Second problem (optional):
- Third problem (optional):
- Existing alternatives (what the customer does TODAY):

## 2. CUSTOMER SEGMENTS
- Target customer (specific — NOT "everyone"):
- Who is the economic buyer (who pays)?:
- Who is the user (who uses it)?:
- Early adopters (the desperate few who buy first):

## 3. UNIQUE VALUE PROPOSITION
- One clear sentence (what / for whom / result):
- High-concept pitch (the "X for Y" line, optional):
- Could a competitor put this EXACT sentence on their site? (y/n — if yes, sharpen it):

## 4. SOLUTION
- Feature that solves problem 1:
- Feature that solves problem 2:
- Feature that solves problem 3:
- (Each must trace back to a Problem line. If it doesn't, it's scope creep.)

## 5. CHANNELS
- How you'll REACH customers to acquire them:
- Channel you'll test FIRST:
- (This seeds Week 7. An empty box here is a real problem.)

## 6. REVENUE STREAMS
- Revenue model (subscription / transactional / take-rate / usage / freemium / hybrid):
- Starting price:
- Value-based reasoning (outcome is worth $___, capturing ___%):

## 7. COST STRUCTURE
- Variable costs (per customer — feed contribution margin):
- Fixed costs (regardless of customer count):

## 8. KEY METRICS
- The one or two numbers that tell you the model is working NOW:
- Your activation / "aha" metric:

## 9. UNFAIR ADVANTAGE
- The thing that can't be easily copied or bought:
- (Honest "no durable moat yet, but the bet is ___" beats a fake moat.)

---
WEAKEST BLOCK (riskiest assumption): ______
WHAT I'LL DO TO TEST IT: ______
```

---

## Worked example — Maya's dental-clinic SaaS (reference)

Use this to calibrate altitude, *not* to copy. Your concept is different.

```markdown
# Lean Canvas — FillChair (same-day cancellation filler for dental clinics) — 2026-06-12

## 1. PROBLEM
- Top problem: Same-day cancellations leave chairs empty; that revenue is gone forever.
- Second problem: Front desk can't fill the slot fast enough by phoning a paper waitlist.
- Existing alternatives: Front desk calls patients manually; slot goes unfilled; generic scheduler with no waitlist automation.

## 2. CUSTOMER SEGMENTS
- Target customer: Independent US dental clinics, 1–3 chairs, owner-operated.
- Economic buyer: The owner-dentist (signs the check).
- User: The front-desk/office manager (uses it daily).
- Early adopters: Owner-dentists who feel cancellation pain acutely and already use web tools.

## 3. UNIQUE VALUE PROPOSITION
- One sentence: Automatically fill same-day cancellation slots so independent clinics stop losing revenue to empty chairs.
- High-concept: "Self-driving waitlist for dental cancellations."
- Could a competitor copy the sentence? No — it's specific to the cancellation pain, not "easy scheduling."

## 4. SOLUTION
- Auto-text the waitlist the instant a cancellation hits. (→ problem 2)
- One-tap claim for the patient. (→ problem 2)
- Auto-confirm and update the calendar. (→ problem 1)

## 5. CHANNELS
- Reach: founder-led outbound to local clinics; dental practice-management Facebook groups.
- First test: founder-led outbound to 20 local clinics.

## 6. REVENUE STREAMS
- Model: subscription.
- Price: $99/month per clinic.
- Value reasoning: one filled slot ≈ $150; filling ~4/mo ≈ $600 value; $99 captures ~16% — easy yes.

## 7. COST STRUCTURE
- Variable: SMS (~$4), payment processing (~$3), support (~$2) = ~$9/clinic/mo.
- Fixed: founder time, base hosting, tools (~$9k/mo all-in early).

## 8. KEY METRICS
- Slots filled per clinic per month (value metric); monthly churn.
- Activation: clinic fills its first cancellation slot via FillChair.

## 9. UNFAIR ADVANTAGE
- Honest: no durable moat yet. The bet is proprietary waitlist-behavior data + switching costs accumulate.

---
WEAKEST BLOCK (riskiest assumption): Channels — can founder-led outbound actually land clinics at a CAC that works?
WHAT I'LL DO TO TEST IT: Cold-outreach 20 clinics in Week 7, measure conversion and cost-per-clinic.
```

---

## Self-check before you commit

- [ ] No "everyone" in Customer Segments — it's specific enough to picture one real person.
- [ ] Existing-alternatives line is filled (they always do *something* today).
- [ ] Value prop is an *outcome*, not a mechanism ("fills cancellations," not "uses AI").
- [ ] Every Solution feature traces back to a Problem line.
- [ ] Revenue model and price are concrete (a number, even if a hypothesis).
- [ ] Variable costs are separated from fixed costs in Cost Structure.
- [ ] Unfair Advantage is honest — no "first mover" / "great UX" / "our passion."
- [ ] Weakest block is named and has a test attached.
- [ ] Committed to your Week 6 repo.

---

*Next: the [unit-economics sheet](exercise-03-unit-economics-sheet.md) — where blocks 6 and 7 above become real numbers.*
