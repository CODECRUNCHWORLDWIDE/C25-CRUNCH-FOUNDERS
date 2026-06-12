# Challenge 1 — The Down-Round Decision

**Time estimate:** 90–120 minutes.

**Format:** A decision scenario. You'll build a small cap-table/runway model for each realistic path, choose one, and defend it. **This is not code, and it is not investment or legal advice** — it's the judgment muscle that pays off in your capstone.

---

## The situation

You are eighteen months into **Loop**, a B2B workflow tool. Here's where you stand.

**The cap table today** (post your earlier pre-seed):

| Holder | Ownership % |
|--------|------------:|
| Founder A (you, CEO) | 38% |
| Founder B (CTO) | 38% |
| Pre-seed investors (converted SAFEs) | 12% |
| Option pool (mostly allocated to 3 employees) | 12% |
| **Total** | **100%** |

**The numbers:**

- **Cash in bank:** $180,000.
- **Net burn:** $45,000/month. So **runway ≈ 4 months.**
- **Revenue:** $22,000/month MRR, growing ~6%/month. Real, paying customers — 30 of them.
- **Unit economics (your Week 6 work, updated):** CAC ≈ $1,400, recovered in about 5 months; contribution margin healthy and positive. The machine *works*; it's just not yet large.
- **The team:** you, your co-founder, and three employees, two of whom you'd struggle to replace.

**What changed:** the market turned. The frothy valuations of two years ago are gone. The seed round you'd assumed you'd raise at a $20M+ valuation is not available at that price. Your two strongest leads have gone quiet. One investor you trust has been honest with you:

> "I'd back you, but not at your old number. The market reset. I can do a **down round** at a $6M post-money, or I can do a **bridge** on a SAFE to extend your runway, but I'll want a low cap on it. Either way, this won't be the round you were planning a year ago."

You have **four months** to decide and execute. Choose.

---

## The four paths

### Path A — Take the down round

Raise **$1,200,000 at a $6,000,000 post-money** priced round, with a **new 10% option pool created pre-money** (the new investor requires it for future hires). This funds ~18 more months at current burn and lets you hire to accelerate. But it's a *down round* — a lower valuation than your last — and it's heavily dilutive at this size relative to the company's value today.

**Model it:** build the post-round cap table. Where do the founders land? Where do the *existing* pre-seed investors land (do they have anti-dilution protection — assume standard broad-based weighted-average, which softens but doesn't eliminate their dilution)? How many points do you and your co-founder give up?

### Path B — Take the bridge SAFE

Raise **$400,000 on a post-money SAFE at a $5,000,000 cap** from your honest investor. This extends runway by ~9 months without setting a new priced valuation today — you're betting that in 9 months you'll have enough traction to raise the real round on better terms. But it's another instrument stacked on your cap table, it converts later (diluting you then), and if the round in 9 months *still* isn't there, you've spent the bridge and you're back here with less.

**Model it:** compute the SAFE's implied % (`amount ÷ cap`), the new runway, and what conversion looks like *if* you later raise a $2M priced round at, say, an $8M pre-money. Founders land where?

### Path C — Cut to default-alive

Raise **nothing.** Cut burn hard: let go of one employee, take founder pay to near zero, and trim spend until **burn ≤ revenue.** At $22k MRR growing 6%/month, model how many months until you cross into default-alive (burn fully covered by revenue). You keep your cap table exactly as it is — **zero dilution** — and you keep full control. The cost is brutal: a painful layoff, founder hardship, slower growth, and the risk that a competitor with fresh capital outruns you.

**Model it:** the runway under the cut, the month you reach burn ≤ revenue, and a one-line statement of what you sacrifice (a teammate's job, your own pay, growth speed).

### Path D — Wind down / walk away

Acknowledge the honest case: maybe Loop is a fine business that isn't a *venture* business, and the right move is to stop raising, return remaining cash where obligated, and either shut down cleanly or convert it into a small, founder-owned, profitable operation that never raises again. Not every good company should keep pushing for the venture outcome.

**Model it:** what does an orderly wind-down or a "shrink to a profitable two-person business" path actually look like for the cap table and the team? (This path is sometimes the *right* one, and a founder who can name that is more mature than one who can't.)

---

## Your deliverable

Produce, in your Week 8 repo under `challenges/challenge-01/`:

1. **Four models** — a cap-table and/or runway model for each path (A, B, C, D), with the math shown. Percentages sum to 100%; runway numbers are derived, not guessed.
2. **A decision memo** (~400–600 words) that:
   - States your **chosen path**, unambiguously.
   - Defends it from your **control-vs-wealth lean** and the **unit economics** (the machine works — does that change the calculus?).
   - Names what you're **giving up** on the rejected paths, honestly.
   - Anticipates and answers the **single most obvious objection** to your choice.

---

## Acceptance criteria

- [ ] All four paths modeled with shown math; cap tables sum to 100%, runway figures derived.
- [ ] Path A shows founder *and* existing-investor post-round ownership, with the pre-money pool modeled.
- [ ] Path B shows the SAFE's implied %, new runway, and a later-conversion outcome.
- [ ] Path C shows the month burn ≤ revenue is reached and names the human cost of the cut.
- [ ] Path D sketches the wind-down / shrink-to-profitable cap-table and team outcome.
- [ ] A decision memo (~400–600 words) with an explicit choice, lean-based defense, honest trade-offs, and a rebutted objection.
- [ ] Committed to your Week 8 repo.

---

## How it's assessed

| Criterion | Weight |
|-----------|------:|
| All four paths modeled correctly, math shown, tables sum to 100% | 35% |
| Decision is explicit and defended from lean + unit economics | 30% |
| Trade-offs of rejected paths acknowledged honestly | 15% |
| The most obvious objection is anticipated and answered | 20% |

---

## Notes and nudges

- **There is no single right answer.** A control-leaning founder may pick **C** (keep the company, eat the pain, stay in charge). A wealth-leaning founder who believes in the upside may pick **A** (take the dilution, buy the growth). A patient optimist may pick **B** (bridge to a better round). A clear-eyed realist may pick **D**. All four are defensible *with the right reasoning*. We grade the reasoning.
- **The trap is avoiding the decision.** "I'd talk to more investors first" is not a path — it's a stall, and your runway doesn't care. Decide.
- **The unit economics are the twist.** The machine *works* — positive contribution margin, recovering CAC. That fact pushes against Path D and softens the case for a desperate down round. A founder who ignores that the underlying business is healthy is leaving the most important fact on the table.
- **Down rounds aren't shameful.** They were everywhere after the 2022–2023 reset. The stigma is largely vanity; the question is purely whether the money buys enough growth to justify the dilution at *this* price.

## Why this matters

This is the decision that separates founders who *understand* their cap table from founders who merely *have* one. In Week 10 your capstone "ask" slide will face exactly these questions from the room: *what does this round cost you, and why is it worth it?* A founder who has already war-gamed a down round answers calmly. A founder who hasn't, stammers. Do the hard one now, on paper, where it's free.
