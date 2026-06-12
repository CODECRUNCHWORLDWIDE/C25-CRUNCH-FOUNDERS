# Exercise 1 — Canvas and Margins

**Goal:** Fill the lean canvas for *your* concept and compute its contribution margin — the foundation of everything in this week's unit-economics work. This is the guided, walk-through version; Exercises 2 and 3 are the fuller templates.

**Estimated time:** ~50 minutes.

**Prerequisite:** You've read [Lecture 1](../lecture-notes/01-the-business-model-canvas-and-revenue-models.md). You have a concept from your discovery work (Weeks 2–5).

---

## Why you're doing this

By the end of this exercise you'll have, on one page: the nine-block story of your business, a chosen revenue model and a first price with reasoning, and a contribution margin computed from itemized variable costs. That contribution margin is the *first input* to the unit-economics sheet (Exercise 3) and the mini-project. Get it right here and the rest of the week flows; fudge it and everything downstream inherits the fudge.

---

## Steps

### Step 1 — Fill the canvas fast (20 min)

Open a new file in your Week 6 repo and fill all nine lean-canvas blocks for your concept. **Single-line answers only.** Don't polish — capture. Use the order from Lecture 1: Problem and Customer Segments first, Unfair Advantage last.

If a block is genuinely empty, **write "(empty — riskiest assumption)" rather than inventing something.** The empty boxes are information: they're what you don't yet know about your own business.

### Step 2 — Flag the weakest block (5 min)

Look across your nine blocks. Which one are you *least* confident about? Mark it explicitly as your **riskiest business-model assumption**. For most founders this week it's either Channels (how do I actually reach them?) or Revenue Streams (will they really pay this?). Naming it now tells you what to test next.

### Step 3 — Choose revenue model + first price (10 min)

Decide *how* you'll charge (subscription, transactional, take rate, usage, freemium-into-one-of-those, hybrid) and *how much* — your starting price. Then write **one sentence of value-based reasoning**: what is the outcome worth to the customer, and what fraction of that are you capturing? If you find yourself reasoning from *your costs*, stop and start over from the customer's value.

Apply the pricing dare to yourself: look at your number and ask "why not double it?" Write down your honest answer.

### Step 4 — Compute contribution margin (15 min)

List **every variable cost** to serve one customer for one period — the costs that exist *because* the customer exists (payment fees, hosting per user, SMS, support time, per-request AI inference, etc.). Itemize each with its assumption. Then:

```
Contribution margin = Price − (sum of variable costs per customer per period)
```

Compute both the **dollar** figure and the **percentage** (margin ÷ price). If your contribution margin is *negative*, that's a five-alarm finding — note it loudly; you're losing money on each customer before you've even tried to acquire them.

---

## Template to fill

Save this as your exercise-01 deliverable and fill every line.

```markdown
# Canvas & margins — <your concept>

## Lean canvas
- Problem (top 1–3):
- Existing alternatives (what they do today):
- Customer segments (specific!):
- Early adopters:
- Unique value proposition (one sentence):
- Solution (top 1–3 features):
- Channels:
- Revenue streams:
- Cost structure (variable vs. fixed):
- Key metrics:
- Unfair advantage (honest):

Weakest block (riskiest assumption): ______

## Revenue model & price
- Model: ______
- Starting price: ______
- Value-based reasoning: the outcome is worth ~$____ to the customer; I'm
  capturing ~__% of that, which is an easy yes because ______
- "Why not double it?": ______

## Contribution margin
Price: $______ per ______
Variable costs to serve one customer per period:
- ______ : $____  (assumption: ______)
- ______ : $____  (assumption: ______)
- ______ : $____  (assumption: ______)
Total variable cost: $______
Contribution margin = $______  (____% of price)
```

---

## Worked example (Maya's clinic SaaS) — for reference only

```markdown
## Contribution margin
Price: $99 per clinic per month
Variable costs:
- SMS to patients : $4  (assumption: ~80 texts/mo at ~$0.05)
- Payment processing : $3  (assumption: ~3% of $99)
- Support : $2  (assumption: ~5 min/mo at a loaded rate)
Total variable cost: $9
Contribution margin = $90  (91% of price)
```

---

## Acceptance criteria

- [ ] File present in your Week 6 repo; all nine canvas blocks filled (or honestly marked empty).
- [ ] Weakest block flagged as the riskiest business-model assumption.
- [ ] Revenue model and starting price chosen, with **value-based** reasoning (not cost-plus).
- [ ] The "why not double it?" question answered honestly.
- [ ] Contribution margin computed as a dollar *and* a percentage, with every variable cost itemized and assumed.
- [ ] If contribution margin is negative or thin, it's flagged explicitly.
- [ ] Committed.

---

## Expected outcome

You walk away with a one-page business story and a single number — contribution margin — that you trust because you can see every assumption under it. When you start Exercise 3, that number is the first cell you fill, and you won't have to re-derive it. You'll also have discovered (probably) that your first price was a flinch and should go up.

---

## Hints

- If a block is empty, that emptiness is *information* — it's your next test, not a failure.
- When unsure on price, write the higher number and note that you'll test it. You can always discount; it's painful to raise.
- The variable cost everyone forgets is **payment processing** (~3%). The second is **support time**. Get both in.
- "Customer segments: everyone who…" is always wrong. Narrow it until it's almost uncomfortably specific.

---

*Next: the fuller [lean canvas worksheet](exercise-02-lean-canvas-worksheet.md), then the [unit-economics sheet](exercise-03-unit-economics-sheet.md).*
