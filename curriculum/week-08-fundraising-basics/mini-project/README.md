# Mini-Project — Cap-Table + Dilution Model

> Build the single most valuable spreadsheet a first-time founder can own: a cap-table model that shows founder ownership before and after a hypothetical pre-seed round — SAFEs, an option pool created pre-money, dilution computed to the point — paired with a raise memo that says whether you'd actually do it. The dilution number you produce here becomes the backbone of the "ask" slide in your Week 10 capstone pitch.

**This is education — not investment, tax, or legal advice.** Anything you'd actually sign, you sign with a lawyer.

**Estimated time:** ~9 hours across Thursday, Friday, and Saturday in the suggested schedule.

---

## Why this is the week's capstone artifact

Every other artifact this week feeds this one. The cap-table model is where your control-vs-wealth lean (Week 1), your co-founder split (Week 4), and your unit economics (Week 6) all collide with arithmetic. When you finish, you will be able to say — in numbers no one can argue with — exactly what a pre-seed round costs you and whether it's worth it. That sentence is the heart of a fundable pitch.

This compounds directly onto prior weeks:

- It **starts from your Week 4 founder split** — the same cap table, now facing its first outside money.
- It **uses your Week 6 economics** to answer "would the money buy growth?" — the question that separates a multiplier from a bonfire.
- It **feeds your Week 10 pitch** — the "ask" slide ("we're raising $X to reach milestone Y, here's what it costs us") is this model, summarized.

---

## What you will build

### 1. The cap-table model (a spreadsheet)

A single spreadsheet (Google Sheets or LibreOffice Calc) with these stacked, clearly labeled sections. Ownership % must be **formulas**, never typed numbers, so the whole thing recomputes when you change an input.

1. **Starting table** — your founders and any existing early holders, summing to 100%. Use your *real* Week 4 split.
2. **The SAFE stack** (if you use SAFEs) — each SAFE's amount, post-money cap, and implied % (`amount ÷ cap`), totaled. Or skip to a priced round if you prefer to model that path.
3. **The option pool** — created **pre-money**, sized realistically (10–15%), so you see the pool shuffle take a slice out of *your* ownership before the investor's money lands.
4. **The round** — investment, pre-money, post-money (`pre + investment`), and investor % (`investment ÷ post-money`), all by formula.
5. **The post-round table** — every holder's shares and ownership %, summing to 100%, including converted SAFEs, the pool, and the new investor.
6. **The dilution summary** — each founder's ownership before vs. after, in points, with a one-line decomposition of where the points went (SAFEs / pool / investor).

### 2. The raise memo (`cap-table/RAISE-MEMO.md`)

About half a page to a page. Would you actually raise this round? Decide, and defend the decision by reasoning from:

- your **control-vs-wealth lean** (Week 1),
- your **unit economics** (Week 6) — is capital the bottleneck, and would it buy growth that compounds?,
- the **dilution number** your own model just produced.

"Not yet" is a completely valid, often correct conclusion. What's *not* valid is a memo that doesn't reason from the numbers you built.

---

## Acceptance criteria

- [ ] A spreadsheet with **all six sections** above, clearly labeled.
- [ ] **Starting and post-round tables each sum to exactly 100.0%.**
- [ ] Ownership % is a **formula** (`shares ÷ total` or `investment ÷ post-money`) throughout — not a typed number.
- [ ] **The option pool is created pre-money** and visibly dilutes the founders (the pool shuffle is shown, not hidden).
- [ ] **Pre-money and post-money are both stated;** the investor % is consistent with `investment ÷ post-money`.
- [ ] **Founder dilution is shown before → after, in points,** for each founder, with the where-did-the-points-go decomposition.
- [ ] If SAFEs are used, **each SAFE's implied % is computed against its cap** and the stack total is stated.
- [ ] A **`RAISE-MEMO.md`** with an explicit raise/don't-raise decision, reasoned from lean + economics + the dilution number.
- [ ] A visible **"this is education, not investment/legal advice"** note in the repo.
- [ ] Committed to your Week 8 repo (sheet exported to CSV *and* screenshotted; memo in markdown).

---

## Suggested order of operations

Build it incrementally. Trying to model the whole round at once is how you get a table that doesn't sum to 100.

### Phase 1 — The starting table (~45 min)

Open a blank sheet. Put in your Week 4 founder split with a round share count (10,000,000 is fine). Make Ownership % a formula dividing by the live total. Confirm it sums to 100.0%. Commit: `Starting cap table`.

### Phase 2 — The option pool, pre-money (~1h)

Add a 10–15% option pool *created pre-money*. The trick: the pool comes out of existing holders before the round. Model the founders dropping to `(100% − pool%)` of the pre-round company. Watch your ownership fall before any investor money appears. This is the pool shuffle from Lecture 2; make it visible. Commit: `Pre-money option pool`.

### Phase 3 — The round (~1.5h)

Add the round block: investment, pre-money, post-money (`= pre + investment`), investor % (`= investment ÷ post-money`). Issue the shares that make the investor's target % true (`new total = existing shares ÷ (1 − investor%)`). Build the post-round table. Confirm it sums to 100.0% and the investor row reads the right %. Commit: `Priced round + post-round table`.

### Phase 4 — SAFEs, if you use them (~1.5h)

If your pre-seed is on SAFEs (the 2026 default), model the stack: each SAFE's amount, post-money cap, and implied % (`amount ÷ cap`). Total the column — that's what you've promised before the priced round. Then show the SAFEs converting in the post-round table. Reconcile: the SAFE-holders row should anchor near your stack total. Commit: `SAFE stack + conversion`. *(If you're modeling a pure priced round with no SAFEs, skip this phase and note why in the memo.)*

### Phase 5 — The dilution summary (~1h)

Add the payoff section. For each founder: ownership before → after, in points. Then one line decomposing where the points went (to SAFEs, to the pool, to the investor). This is the number that goes on your capstone ask slide. Commit: `Dilution summary`.

### Phase 6 — The raise memo (~1.5h)

Write `RAISE-MEMO.md`. Decide: would you raise this? Reason from your lean, your economics, and the dilution number your model produced. Be honest — "not yet" is fine if that's where the numbers point. Commit: `Raise memo`.

### Phase 7 — Polish (~1h)

Label every section. Add the not-advice note. Export the sheet to CSV and screenshot it. Confirm a stranger could open your repo and understand, in five minutes, what the round costs and whether you'd take it. Push. Commit: `Polish + export`.

---

## Worked reference (check your math against this)

Using the Lecture 2 end-to-end example as a sanity check. Two founders at 10,000,000 shares, $500k at $4.5M pre-money, with a 10% pre-money option pool:

```
Starting:         Founder A 50.0% · Founder B 50.0%                       (= 100%)
After the round:  Founder A 40.0% · Founder B 40.0% · Pool 10.0% · Investor 10.0%  (= 100%)

Founder A: 50.0% → 40.0%  ·  gave up 10.0 points
Founder B: 50.0% → 40.0%  ·  gave up 10.0 points

Where the points went (each founder):  5.0 to the investor  +  5.0 to the pool
```

Note the founders gave up **10 points each on a "10% round"** — because the pre-money pool came out of their slice. If your model shows founders dropping by only the round size and not the pool, you've forgotten the pool shuffle. Your own numbers will differ (different split, valuation, SAFEs); the *structure* should match.

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|------:|-------------------------|
| **Cap-table math** | 30% | Starting and post-round tables sum to exactly 100%; investor % matches `investment ÷ post-money`; everything is a formula |
| **Option pool / pool shuffle** | 20% | Pool created pre-money and visibly dilutes founders; not hidden or applied post-money by mistake |
| **SAFE handling** | 15% | Each SAFE's implied % computed against its cap; stack totaled; conversion reconciles (or a clean reasoned priced-round alternative) |
| **Founder dilution clarity** | 15% | Before → after in points, per founder, with where-the-points-went decomposition |
| **Raise memo** | 20% | Explicit decision reasoned from control/wealth lean + unit economics + the model's own dilution number; honest, not vanity |

---

## Stretch (optional)

- **Two rounds.** Add a hypothetical seed 18 months after the pre-seed, with its own pool top-up. Watch founder ownership compound downward across two rounds. This is the single best way to feel why founders end up minority owners.
- **The bootstrapping counterfactual.** Build a second tab projecting the same revenue path *without* the round. Show where founder take-home crosses over — at what growth rate does keeping 100% of a smaller company beat owning 40% of a bigger one?
- **Sensitivity.** Add a small input panel (investment, pre-money, pool %) and confirm the whole model recomputes live. Then find: what pre-money valuation would hold your dilution to single digits?
- **Anti-dilution.** Read what broad-based weighted-average anti-dilution does, and model how it protects your *existing* pre-seed investors in a future down round (it shifts more dilution onto you).

---

## What this prepares you for

- **Week 9 — Legal, incorporation & ops.** The shares in this cap table sit on top of an actual entity, actual founder stock, and actual vesting. Week 9 makes the table legally real.
- **Week 10 — The pitch + demo day.** Your "ask" slide is this model in one line: *"Raising $X at $Y to reach milestone Z; it costs us W points."* You'll defend that number under questioning — and because you built it yourself, you can.
- **The capstone.** A founder who can model their own dilution is a founder investors take seriously. This spreadsheet is portable proof you understand the deal you're asking for.

---

## Submission

1. Push your Week 8 repo with the spreadsheet (CSV export + screenshot), `RAISE-MEMO.md`, and the not-advice note.
2. Make sure a stranger could open it and, in under five minutes, see what the round costs the founders and whether you'd take it.
3. Carry the founder-dilution line forward — you will reuse it, verbatim, on your capstone ask slide.

*Next: [Week 9 — Legal, Incorporation & Ops](../../week-09-legal-incorporation-and-ops/).*
