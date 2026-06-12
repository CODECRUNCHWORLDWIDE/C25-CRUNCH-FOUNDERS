# Lecture 2 — Vesting, Cliffs, and Departures

> **Duration:** ~1.5 hours of reading + working the schedule arithmetic yourself.
> **Outcome:** You can explain vesting and the cliff in plain terms, build a four-year/one-year-cliff schedule, say what should happen to a departing founder's equity, recognize single- vs. double-trigger acceleration, and explain the 83(b) election and its unforgivable 30-day deadline — enough to brief a lawyer well, not to replace one.

The single sentence to carry out of this lecture:

> **Vesting with a cliff is not distrust — it is mutual protection, and it protects the founders who *stay and carry the load* most of all.**

Lecture 1 got you to a defensible equity split. This lecture gives you the instrument that makes a split *safe to commit to* on day zero, before you've worked together a single day: you don't actually *own* your founder equity outright on day one — you *earn* it over time. That single mechanism quietly solves the scariest problem in co-founding: what if my partner takes their huge slice and walks in month three?

---

## 1. What vesting actually is

**Vesting** means a founder earns their equity over time rather than owning all of it on day one. The shares are granted up front (so you're a real owner from the start, with voting rights and the tax clock running — more on that in §6), but they are **subject to repurchase** by the company until you've "vested" them by sticking around.

The 2026 standard for founders — and it really is a standard, the way "four-year/one-year-cliff" rolls off every startup lawyer's tongue:

- **Four-year vesting.** Your equity is earned in equal monthly increments over 48 months.
- **One-year cliff.** *Nothing* vests for the first 12 months. At the one-year mark, the first **25%** (12 months' worth) vests all at once — that's the "cliff." After the cliff, the remaining equity vests **monthly** (1/48th per month) for the next 36 months.

So:

- Leave at **month 11** → you vested **0%**. Nothing. The cliff was not reached.
- Leave at **month 12** (just past the cliff) → you vested **25%** (it vested in a lump the moment you crossed the cliff).
- Leave at **month 24** → you vested **50%**.
- Stay the full **48 months** → you vested **100%**; the equity is fully yours, repurchase right gone.

```
Founder equity earned over time (4-year vest, 1-year cliff)

100% │                                              ┌──────
     │                                       ┌──────┘
     │                                ┌──────┘   (monthly vesting,
 50% │                         ┌──────┘           1/48 per month)
     │                  ┌──────┘
 25% │           ╔══════╝  ← cliff: 25% vests all at once at month 12
     │           ║
   0%└───────────╨──────────────────────────────────────────
     0          12          24          36          48  (months)
       (nothing vests
        before the cliff)
```

### The arithmetic, concretely

Say a founder is granted **4,000,000 shares** on a 4-year / 1-year-cliff schedule.

- Per-month vesting after the cliff: 4,000,000 ÷ 48 = **83,333 shares/month**.
- At the cliff (month 12): 12 × 83,333 ≈ **1,000,000 shares** vest at once (25%).
- Month 30: 30 × 83,333 ≈ **2,500,000 shares** vested (62.5%).
- Month 48: all **4,000,000** vested.

You will build exactly this table in Exercise 3. Doing the arithmetic by hand once is the point — it makes the cliff stop being a vocabulary word and start being a thing you can feel.

### Why these specific numbers — four years and one year?

Founders often ask whether the 4-year/1-year shape is law. It isn't — it's a **convention** that won, and knowing *why* it won helps you decide when to deviate.

- **Four years** roughly matches how long it takes a startup to reach a meaningful outcome or clearly fail, and it's long enough that a founder has to genuinely commit, not just dabble. It's also the standard for *employee* option grants, so the whole cap table vests on one rhythm.
- **The one-year cliff** is a commitment filter. The first year is where you find out whether a co-founder actually shows up — whether the coffee-chat enthusiasm survives contact with the grind. Granting *zero* until month 12 means a co-founder who bails in month 4 (the single most common bad outcome) leaves with nothing, cleanly. It protects against the worst case precisely when the worst case is most likely.

You *can* deviate — some teams use a shorter vest for a co-founder joining late, or add extra cliff for a part-timer "until you go full-time." But deviate *on purpose, in writing*, with a reason. Defaulting to 4/1 and explaining any change is the fundable posture.

### A common point of confusion: granted vs. vested

A frequent misunderstanding: "if I'm vesting, do I even own my shares?" Yes. With restricted stock (the founder instrument — §7), the shares are **granted to you on day one** — you're a real shareholder, you vote them, and critically the tax clock and 83(b) window start now. What vesting controls is the company's **repurchase right**: until shares vest, the company can buy them back (at your original nominal price) if you leave. "Unvested" doesn't mean "not yet yours" — it means "yours, but the company can claw them back if you walk early." That distinction is exactly why the 83(b) timing in §6 matters: you're taxed as an owner from grant, not from vest.

---

## 2. Why vesting protects *everyone* (especially the people who stay)

Founders who skip vesting "to show we trust each other" almost always regret it the first time someone leaves. Vesting sounds like distrust; it is the opposite. Walk through who it protects.

**It protects the company and the remaining founders** from a co-founder who leaves early with a large, dead-weight stake. Imagine Ben (from Lecture 1) had 45% with *no* vesting, decided in month three that startups aren't for him, and walked. He'd keep 45% of the company forever, contributing nothing, while Ana builds it. Worse: that 45% is now *unrecruitable equity* — Ana can't offer a real engineering co-founder a competitive slice because 45% is sitting dead on the cap table. And every future investor will see it and balk. A 45%-owned absentee founder can sink a company before it starts.

**It protects the founder who stays and carries the load.** This is the part people miss. Vesting isn't the strong founder protecting themselves *from* the weak one — it's a mutual promise that ownership tracks contribution. The founder who grinds for four years *earns* their full stake; they're protected from watching a departed partner keep equal ownership for a quarter of the work.

**It makes the equity returnable.** When unvested shares are repurchased, they go *back to the pool* — available to recruit a replacement co-founder or to grant to the team. The company stays financeable and recruitable.

And here's the kicker: **investors will require it anyway.** Standard institutional term sheets impose (or re-impose) founder vesting as a condition of investment. So doing it yourself, early, is not a concession — it's a signal of seriousness, and it lets *you* set the terms rather than having a VC dictate them later.

> **The "would you say it to their face?" test, applied.** "I want us both on a four-year vest with a one-year cliff, including me, so that whichever of us ends up carrying this thing is fairly rewarded and neither of us can walk with equity we didn't earn." That's a sentence you can say to a co-founder's face with a straight back. If your proposed terms *can't* be said that way — say, you vest but they don't — that asymmetry is the tell.

---

## 3. The departure clause — write the unhappy path while everyone is happy

The cliff and the vesting schedule answer *how much* a leaver keeps. The **departure clause** answers everything else. Decide all of this in advance, because the day someone leaves is the worst possible day to negotiate it.

**Unvested equity.** Returns to the company (repurchased, typically at the founder's original purchase price — often cents). This is the entire point of vesting; make it explicit.

**Vested equity.** This is the genuinely hard part. The departing founder *earned* their vested shares — but do you want a person who is no longer building the company holding a meaningful stake and a vote? Common answers:
- *Let them keep it.* Cleanest, most generous, and fine if the slice is small or the departure is amicable. They keep what they earned.
- *Company repurchase right on vested shares.* The company has the option (not obligation) to buy back vested shares at **fair market value** (for a "good leaver") — this keeps the cap table clean but is a real cost and can feel punitive. Be careful: a *cheap* forced buyback of vested shares is the kind of clause that doesn't survive the say-it-to-their-face test.

**Good leaver / bad leaver.** Many agreements distinguish *how* someone leaves. A **good leaver** (illness, relocation, mutual decision) keeps vested equity on fair terms. A **bad leaver** (fired for cause, walks out, breaches) may face a less favorable buyback. This is legitimate but it's also where agreements get adversarial fast — flag it for a lawyer and don't over-engineer it yourself.

**IP and accounts.** Anything the departing founder built — code, designs, customer relationships, the domain name registered under their personal account, the Stripe login — belongs to or transfers to the **company**, not the individual. This is why the IP-assignment agreement (the CIIA, §7) exists. The handover of accounts and credentials should be spelled out so a messy exit doesn't lock the remaining team out of their own infrastructure.

> Write the unhappy path while everyone is happy. It is the *only* time you can write it fairly, because today neither of you knows which one of you will be the leaver.

---

## 4. Acceleration: single-trigger vs. double-trigger

You'll hear "acceleration" the moment a real lawyer or a real acquisition enters the picture. It means **unvested equity vesting faster than scheduled, on a defined trigger** — usually an acquisition.

- **Single-trigger acceleration.** Some or all unvested equity vests immediately when the company is **acquired**. Founder-friendly, but acquirers dislike it: they're often buying the *team*, and if everyone's equity fully vests at close, the team can walk away rich on day one. It can actually make the company *harder* to sell.
- **Double-trigger acceleration.** Unvested equity accelerates only if **two** things happen: the company is acquired **and** the founder is terminated (or constructively pushed out) within some window after. This is the market standard for a reason — it protects the founder from being acquired and then fired to dodge their unvested equity, *without* spooking acquirers who want to retain the team.

You do not need to master the mechanics now. You need to (a) know the two terms exist, (b) understand that double-trigger is the usual default, and (c) flag acceleration as something for your lawyer when you actually paper the company. Putting "double-trigger acceleration — confirm with counsel" in your draft is exactly the right level of fluency for Week 4.

---

## 5. Good leaver, bad leaver, and the buyback price — a worked scenario

Return to Ana and Ben, 55/45, both on a 4-year / 1-year cliff.

**Scenario A — Ben leaves at month 9 (before the cliff).** Ben vested **nothing**. All of his 45% is unvested and is repurchased by the company at his original price. It returns to the pool. Ana can now offer a real engineering co-founder a competitive slice. The cliff did its job: it protected the company *and* Ana, cleanly, with no negotiation, because they wrote it down on day one.

**Scenario B — Ben leaves at month 30 (62.5% vested).** Ben earned ~28 of his 45 points (62.5% × 45). The remaining ~17 points are unvested and return to the pool. Now the hard question: what happens to Ben's *vested* ~28 points? If the agreement says "good leavers keep vested equity," Ben walks with ~28% — a real, earned stake — and the cap table carries a non-builder owner unless the company exercises a fair-value buyback right it was smart enough to negotiate up front. *This* is why §3's vested-equity decision matters: month-9 Ben is easy; month-30 Ben is the scenario your departure clause actually exists for.

You'll navigate exactly this in the week's challenge.

### What the cap table actually looks like, before and after

Numbers make this concrete. Ana and Ben at 55/45 on a 10,000,000-share founder pool: Ana holds 5,500,000 shares, Ben 4,500,000.

**Day one cap table:**

| Holder | Shares | % |
|---|---:|---:|
| Ana | 5,500,000 | 55% |
| Ben | 4,500,000 | 45% |
| **Total** | 10,000,000 | 100% |

**Ben leaves at month 9 (Scenario A — pre-cliff).** All 4,500,000 of Ben's shares are unvested and get repurchased into the pool. The post-departure table:

| Holder | Shares | % |
|---|---:|---:|
| Ana | 5,500,000 | 100% (of issued) |
| Returned to pool | 4,500,000 | available to re-grant |

Ana now controls the company outright and has a full 45% slice to recruit a real engineering co-founder or to spread across an early team. *This is the cliff doing its entire job in one move* — cleanly, with no negotiation, because they wrote it down on day one.

**Ben leaves at month 30 (Scenario B — 62.5% vested).** Ben vested ~2,812,500 shares (62.5% × 4.5M); ~1,687,500 are unvested and return to the pool. Now the cap table carries a complication:

| Holder | Shares | % of remaining |
|---|---:|---:|
| Ana | 5,500,000 | ~66% |
| Ben (departed, vested) | ~2,812,500 | ~34% |
| Returned to pool | ~1,687,500 | re-grantable |

That ~34% held by someone *no longer building the company* is the live problem your departure clause exists to address — keep it, buy it back at fair value, or treat it per good-leaver/bad-leaver terms. The arithmetic is easy; the *decision* is the hard part, and it's why §3 told you to write the vested-equity rule in advance.

> **The lesson the two tables teach:** the cliff makes the *early* departure trivially clean, which is exactly when departures are most likely and most dangerous. By the time someone has vested a meaningful chunk, they've usually earned it — so the later case is rarer *and* fairer to negotiate. Vesting front-loads your protection to where you need it most.

---

## 6. The 83(b) election — the most expensive 30 days in a founder's life

This is the one piece of tax mechanics every founder must know, because missing it is common, avoidable, and *expensive*, and the deadline is brutal.

When you receive **restricted stock** (founder shares subject to vesting), the IRS's default treatment is ugly: you're taxed on the shares' value *as they vest*, year after year, at whatever the company is worth *then*. If the company's value climbs, you owe ordinary income tax on the growing value of shares you haven't even sold — a phantom tax bill on illiquid stock. That's a nightmare.

An **83(b) election** is a one-page filing you send to the IRS that says: "tax me **now**, on the full grant, at **today's** value." On day one, your founder shares are worth almost nothing, so the tax is almost nothing (often zero). You lock in the low early value, the clock for long-term capital gains starts immediately, and all future appreciation is taxed later as capital gains when you actually sell — not as income as it vests.

**The catch, and it is unforgiving:** the 83(b) election must be filed with the IRS **within 30 days of the stock grant.** There is **no extension, no exception, no "I didn't know."** Miss the window and you cannot fix it — you're stuck with the default treatment for the life of the grant. This is why startup lawyers and accountants treat the 83(b) deadline with near-religious seriousness, and why "did everyone file their 83(b)?" is one of the first questions a diligence process asks.

For Week 4, you need to be able to say, in two sentences, to a peer: *"An 83(b) election makes me pay tax now on my near-worthless founder shares instead of later as they appreciate, which is almost always the right move. It has to be filed within 30 days of the grant, with no extensions, so don't miss it."* That's the fluency target. (Specific to the US tax code; other jurisdictions have their own equivalents and quirks — another reason for a local professional.)

> **Education, not tax advice.** The 83(b) is jurisdiction-specific and fact-specific. Know it exists, know the 30-day clock, and put it on the list for your accountant.

---

## 6a. A practical good-leaver / bad-leaver framework

§3 said the vested-equity question depends on *how* someone leaves, and that this is where agreements get adversarial. You don't need to draft airtight legal language this week, but you should be able to reason about it cleanly. Here's a working frame you can write in plain English and then hand to a lawyer.

A **good leaver** is someone whose departure is, broadly, not their fault or is genuinely mutual:
- Serious illness or a family emergency.
- A relocation neither party could prevent.
- A mutual, amicable decision that it isn't working.
- Being let go *without* cause (the company's call, not their misconduct).

A **bad leaver** is someone whose departure is, broadly, their breach:
- Fired *for cause* — gross misconduct, theft, serious breach of duties.
- Walking out with no notice and no handover, leaving the team stranded.
- Breaching the CIIA, competing, or taking IP/customers.

**Why the distinction earns its keep:** a good leaver should be treated *generously* — they keep what they vested, on fair terms — because how you treat good leavers is watched by everyone who's still there. Treat an exhausted, honest co-founder punitively and you teach the whole team to hide problems and grind until they break. A bad leaver can face a less favorable buyback (sometimes at cost rather than fair value) because they breached the deal — but be careful: punitive bad-leaver clauses are heavily scrutinized by courts in many jurisdictions, and a clause that looks like a penalty can be unenforceable. This is precisely the kind of thing to *flag for a lawyer* rather than over-engineer yourself.

**The trap to avoid:** leaving the definition blank (the exact gap in this week's challenge). If your agreement says "the company may repurchase vested shares, good-leaver/bad-leaver TBD," then the day someone leaves you're negotiating the definition *and* the money simultaneously, under maximum pressure. Write at least a plain-language version now.

> **Say-it-to-their-face check:** read your bad-leaver clause imagining the *good* leaver — the burned-out, honest co-founder — accidentally caught by it. If your wording would punish them, it's too broad. Tighten it until only genuine breach triggers the harsh treatment.

---

## 6b. Restricted stock vs. options, one level deeper

You'll meet both instruments; using the wrong word in front of an investor or lawyer signals inexperience. Here's the founder-relevant difference.

| | **Restricted stock (RSA)** — founders | **Stock options (ISO/NSO)** — employees |
|---|---|---|
| What you get | Actual shares, *now*, at a nominal price | The *right to buy* shares later at a fixed "strike" price |
| Ownership | You're a shareholder from day one (vote, etc.) | Not a shareholder until you exercise |
| Vesting | Company can repurchase *unvested* shares if you leave | Unvested options are simply forfeited |
| Tax timing | Pay tax at grant (file the **83(b)**!) | Tax at exercise / sale, generally |
| Who uses it | Founders, very early team | Most employees |

The reason **founders get restricted stock**: at the very beginning the shares are worth almost nothing, so you can own real equity for a trivial price and, with the 83(b), lock in that near-zero tax basis. Options exist mostly to grant equity to people *after* the company has some value, when handing them cheap stock would create an immediate tax bill they can't pay. For your agreement this week, founders hold **restricted stock subject to vesting**, full stop — and each files an 83(b). Get this vocabulary right and the rest of the room assumes you've done this before.

---

## 7. The instrument behind it all: RSAs and the CIIA

Two more terms so the draft you write this week uses the right words.

**Restricted Stock (an RSA — restricted stock *agreement*/award).** The usual founder instrument. You *buy* (or are granted) actual shares up front at a nominal price, and they're "restricted" — subject to the company's repurchase right until they vest. This is different from **stock options** (the usual *employee* instrument), which give the right to buy shares later at a fixed price. Founders almost always hold restricted stock with an 83(b) election; employees almost always hold options. You don't need to master the difference, but use the right word: founders get **restricted stock**, not options.

**The CIIA — Confidential Information and Invention Assignment agreement.** Every founder signs one. It does two jobs: it keeps company confidential information confidential, and — critically — it **assigns to the company any IP the founder creates** related to the business. Without it, a founder could later claim the code, the brand, or the core invention is personally theirs. The CIIA closes that door. We go deep on IP assignment in Week 9; for this week, your departure clause should reference "IP assigned to the company per the CIIA each founder signs," and that's the right altitude.

---

## 7a. Time-based vs. milestone-based vesting

The standard 4-year schedule is **time-based**: you earn equity simply by remaining engaged over time. There's an alternative you'll occasionally meet — **milestone-based vesting**, where equity vests when specific goals are hit (ship the MVP, reach $X revenue, close the first ten customers).

Milestone vesting is intuitively appealing — "pay for results, not for showing up." But it's a trap for most early teams, and you should understand *why* so you don't reach for it:

- **Milestones change.** Startups pivot. A milestone you set today ("hit 1,000 users on the marketplace") can be irrelevant in six months after you pivot, leaving the schedule meaningless or unfair.
- **It invites gaming and disputes.** "Did we *really* hit the milestone?" becomes a fight. Time, by contrast, is unambiguous — month 14 is month 14.
- **It under-rewards the unglamorous grind.** A founder who spends three months on hiring, fundraising prep, and putting out fires hit no "milestone" but did essential work. Time-based vesting credits it; milestone vesting doesn't.

A reasonable *hybrid*: time-based as the spine, with a small additional grant tied to a single, hard-to-game milestone (e.g., "an extra slug vests on closing the seed round"). But for your Week 4 draft, use straight time-based 4/1 unless you have a specific, defensible reason. It's the default for good reasons.

> This is the vesting analogue of the Lecture 1 "dynamic vs. fixed split" debate: the cleverer-looking, contribution-tracking option usually loses to the boring, certain one, because certainty is itself valuable and disputes are expensive.

---

## 7b. A note on refresh grants and the four-year wall

One thing the four-year schedule creates that surprises first-time founders: the **"vesting wall"** or "cliff at the end." Around year four, a founder (or key employee) becomes **fully vested** — they now own all their equity outright, and there's nothing left to *retain* them with. For founders this is usually fine (you own your company; that's the point). For *employees* it's a real retention problem, which is why mature startups give **refresh grants** — new option grants, on a fresh vesting schedule, before someone fully vests, to keep them holding unvested upside.

You don't need to act on this in Week 4 — your company is at month zero. But knowing the term means that when an investor or an experienced hire asks "what's your refresh policy?" you won't be caught flat. File it under "things that matter in year three, named now."

---

## 8. Tie it back to control vs. wealth

Vesting interacts with control. A founder who insists on a controlling stake but *won't* vest it creates a risk: if they leave, that controlling block is frozen on the cap table, the company becomes un-financeable, and everyone loses. A founder who vests cleanly keeps the company recruitable and financeable *and* keeps their earned ownership.

Whichever lean you chose in Week 1 — control or wealth — **vesting with a one-year cliff is the standard, founder-friendly default for all of the founders.** It is not a wealth-vs-control trade-off; it's the structural floor underneath whichever trade-off you chose. A control-leaning founder still vests. A wealth-leaning founder still vests. The lean shows up in the *split* and the *decision rights* (Lecture 1); the vesting is just the discipline that makes either lean survivable.

---

## 8a. A checklist for your vesting terms

When you write the vesting section of your agreement this week, every one of these should have an explicit answer. A blank is a future problem.

- [ ] **Schedule length and cadence** — four years, monthly after the cliff (the default; deviate only with a reason).
- [ ] **Cliff** — one year, 25% vesting at the cliff (the default).
- [ ] **Applies to whom** — *every* founder, including you, including any solo-founder self-vest.
- [ ] **Instrument** — restricted stock for founders, with the repurchase right on unvested shares named.
- [ ] **Repurchase price for unvested shares** — original purchase price (cost).
- [ ] **83(b) plan** — each founder files within 30 days of grant; one named owner makes sure it happens.
- [ ] **Acceleration** — single- or double-trigger (default: double); flagged for counsel.
- [ ] **Good-leaver / bad-leaver** — at least a plain-language definition; flagged for counsel.
- [ ] **Vested-equity-on-departure** — keep, or company buyback right at what price.
- [ ] **IP / handover** — assigned to the company per the CIIA; account/credential handover spelled out.

If you can check every box in plain language, you have a draft a lawyer can paper and a co-founder can sign without later surprise. That is the entire deliverable of the week's mini-project.

---

## 9. Recap

You should now be able to:

- Explain vesting and the one-year cliff, and compute what a founder keeps at any month of a 4-year/1-year schedule.
- Explain why vesting protects everyone — especially the founders who stay.
- Draft a departure clause covering unvested equity, vested equity, leaver provisions, and IP/account handover.
- Distinguish single- from double-trigger acceleration and name the usual default.
- Explain the 83(b) election and its 30-day deadline in two sentences.
- Use the right words: restricted stock for founders, CIIA for IP assignment.

You now have everything you need to draft the agreement. Do [Exercise 2](../exercises/exercise-02-decision-rights-matrix.md) and [Exercise 3](../exercises/exercise-03-vesting-schedule-template.md), then assemble the [mini-project](../mini-project/README.md).

---

## Frequently asked (every cohort asks these)

**"I'm the sole founder and I own 100%. Why would I put myself on a vesting schedule?"**
Three reasons. First, a future co-founder or key hire will find it far more credible that *they* should vest if you're on the same terms — "I vest, you vest" is a fair sentence; "you vest, I don't" isn't. Second, investors will likely impose founder vesting at the first priced round, and setting it yourself early lets you choose the terms. Third, it costs you nothing if you stay — you vest fully. It's pure downside protection for the company with no real cost to a committed founder.

**"We started 8 months ago with a handshake and no vesting. Are we stuck?"**
No — but fix it now, deliberately. You can adopt a vesting agreement today and, fairly, credit the time already served (e.g., give each founder vesting *as if* it started 8 months ago, so you've each already vested ~8 months toward your cliff). The mistake is continuing to operate with no vesting because "we already started." Retro-fitting vesting is a normal, healthy thing to do before you raise.

**"Does the 83(b) apply if my shares aren't subject to vesting?"**
If shares are fully vested at grant (no repurchase risk), there's nothing for an 83(b) to accelerate — the income event already happened at grant. The 83(b) specifically matters when your stock is *subject to a substantial risk of forfeiture* (i.e., vesting). Since founders almost always vest, founders almost always file. When in doubt, the answer is "ask your accountant within the 30-day window," not "wait and see."

**"What's a fair price for the company to repurchase unvested shares?"**
Almost always the founder's **original purchase price** (often a tiny fraction of a cent per share). Unvested shares were never earned, so they return at cost. Vested shares are the genuinely contested case — that's fair market value or a negotiated number, and it's where you want the good-leaver/bad-leaver framework and, ultimately, a lawyer.

**"Can a co-founder refuse to vest?"**
They can refuse, and that refusal is *itself* information. A co-founder who won't accept the same standard, founder-friendly, mutual-protection terms you're accepting is telling you something about how they'll behave when things get hard. It's a conversation worth having before, not after, you've built something together.

---

## References

- *Cooley GO — "What is a Section 83(b) election?"*: <https://www.cooleygo.com/what-is-a-section-83b-election/>
- *Cooley GO — vesting and acceleration explainers*: <https://www.cooleygo.com/documents/>
- *Holloway — Open Guide to Equity Compensation* (vesting, RSAs vs. options, 83(b)): <https://www.holloway.com/g/equity-compensation>
- *Carta — "How startup equity works"*: <https://carta.com/learn/>
- *Founder Institute — FAST Agreement* (a real vesting-based template): <https://fi.co/fast>
- *Wikipedia — Vesting*: <https://en.wikipedia.org/wiki/Vesting>

*Education, not legal or tax advice. The 83(b) clock is real and unforgiving — when you actually grant founder stock, get a professional to confirm the filing.*
