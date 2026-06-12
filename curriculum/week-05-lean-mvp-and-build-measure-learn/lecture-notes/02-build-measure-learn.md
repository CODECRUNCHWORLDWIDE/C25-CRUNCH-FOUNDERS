# Lecture 2 — Build → Measure → Learn, and the Persevere/Pivot Decision

> **Duration:** ~2 hours of reading + worksheet.
> **Outcome:** You can run the lean loop end to end, instrument one honest metric against a pre-committed threshold, tell vanity metrics from actionable ones, read a noisy result without lying to yourself, and make a named persevere-or-pivot decision.

Lecture 1 got you to a designed experiment: a riskiest assumption, a matched MVP type, and a falsifiable hypothesis with a threshold. This lecture is about *running* it and *deciding* on the result. The build is the easy part. The honesty is the hard part.

Here's the uncomfortable truth this lecture is built around: **the experiment will tempt you to lie to yourself at every step.** When the result comes in low, you'll want to find a kinder metric. When the sample is biased, you'll want to ignore it. When you're attached to the idea, you'll want to call a miss "early signal." None of these are character flaws — they're the default wiring of a motivated human looking at their own work. The frameworks below (pre-committed thresholds, the vanity-metric audit, the honesty checks) exist precisely because we *can't* be trusted to be objective about our own startup bare-handed. Treat them as guardrails, not bureaucracy.

---

## 1. The loop

The lean methodology describes a cycle. It looks like this:

```
            ┌───────────┐
            │   IDEAS   │
            └─────┬─────┘
        LEARN     │     BUILD
       ┌──────────┴──────────┐
       │                     ▼
 ┌───────────┐         ┌───────────┐
 │   DATA    │ ◄────── │ PRODUCT   │
 └─────┬─────┘ MEASURE │  (MVP)    │
       │               └───────────┘
       └──► validated learning ──► (back to IDEAS)
```

You turn an idea into the smallest MVP (**build**), put it in front of real people and collect data (**measure**), and extract *validated learning* that updates the idea (**learn**). Then you go around again.

The crucial, counterintuitive point: **the goal is to minimize the total time through the loop, not to build the best MVP.** A founder who completes the loop in five days, even with an ugly experiment, beats a founder who spends five weeks on a beautiful one. Speed of *learning* is the metric of the meta-game. Every week you spend not-learning is a week of runway you can't get back.

This reframes "build" as the *least* important phase. Build only as much as you need to get to measure. The temptation is always to keep building — to add the feature, fix the styling, handle the edge case. Resist. The loop rewards getting to data, then around again, then again.

---

## 2. One metric, decided in advance

Pick the **single** metric that tells you whether the riskiest assumption held. Not three. One. The discipline of choosing one metric forces you to be clear about what the experiment is actually testing.

Examples, by MVP type:

- **Fake door:** click-through rate on the CTA — what fraction of people who saw the offer acted on it. (Sometimes: email-capture rate.)
- **Concierge:** the outcome metric — Maya's *refill rate* (% of cancellations refilled). Did the manual solution produce the result customers care about?
- **Wizard of Oz:** activation or repeat usage of the "automated" product; or paid conversion.
- **Clickable prototype:** task completion in a moderated test, plus a behavioral follow-up (did they ask when it ships?).

Then — and this is the part founders skip — **write the threshold before you launch.** "Success = at least X." Maya committed to 30% refill *on Tuesday,* before she sent a single text.

### 2.1 Why pre-committing the number matters more than the number itself

Human beings are exceptional at rationalizing. Run an experiment with no threshold and *any* result becomes a win: a 5% conversion is "early signal," a 2% is "we just need better copy," a 0.5% is "wrong channel." There is no number low enough to disprove an idea you're emotionally attached to — *unless you committed to the number before you saw the result.*

The threshold is a contract with your past self, written when you were more objective than you are now. It's not magic — you can argue with it afterward — but you have to argue *against your own prior judgment*, out loud, which is exactly the friction that keeps you honest. A team that says "we set 30%, we hit 8%, and here's our genuine case for why we should persevere anyway" is doing real thinking. A team that never set a number is just feeling good.

### 2.2 How to pick the threshold

You won't always know the "right" number. Set it from:

- **A unit-economics floor.** What conversion/outcome would the business *need* to work? (You'll formalize this in Week 6, but a back-of-envelope version works now. Maya: below ~20% refill, the time saved doesn't justify a clinic paying.)
- **A benchmark.** Industry rough numbers — e.g., cold landing-page CTAs often convert 1–5%; a strong "join the waitlist" might hit 10–20% with warm traffic. Use these to sanity-check, not as gospel.
- **A "would this change my mind" gut check.** Pick a number where, below it, you'd genuinely doubt the idea. If no number would make you doubt, you're not ready to run the test.

A threshold that's *too low* is the common cheat — set it where you can't lose. Red-team it: "Could I hit this number and still have a dead idea?" If yes, raise it.

---

## 3. Vanity metrics vs. actionable metrics

This is the most expensive distinction in the whole course. A **vanity metric** goes up, feels good, and changes no decision. An **actionable metric** is behavioral, tied to your assumption, and would change what you do next if it came in low.

| Vanity (avoid) | Actionable (use) |
|---|---|
| Total signups (cumulative, only goes up) | Activation rate (signups who did the key action) |
| Page views | Click-through to the CTA |
| Total registered users | Weekly active / repeat usage |
| "Likes," followers, impressions | Paid conversion; willingness-to-pay |
| Email list size | Email → behavior conversion |
| App downloads | Downloads that completed onboarding |

Three tests for whether a metric is actionable (the classic "AAA"):

1. **Actionable** — would a bad number change a decision? If not, it's vanity.
2. **Accessible** — can you actually measure it simply and honestly with your MVP? (For a one-week concierge test, a spreadsheet beats analytics tooling.)
3. **Auditable** — is it a real count of real behavior you could show someone, not a number you massaged?

The deadliest vanity metric is the **cumulative total** — total signups, total downloads — because it *only ever goes up*, so it always feels like progress even when the thing is dying. Replace every cumulative total with a *rate* or a *cohort*: not "5,000 signups" but "of the 200 people who signed up this week, 11% came back."

> **The "said vs. did" rule.** What people *say* in an interview is weak evidence; what they *do* in front of your MVP is strong evidence. "I would totally use this" is worth almost nothing. "They clicked Buy" or "they came back on day three" is worth a lot. Design your one metric around a *deed*, never a *word*. (This is also why Week 3's discovery interviews never pitched — talk is cheap; this week we manufacture cheap behavior instead.)

---

## 4. Measuring honestly: signal, noise, and sample size

A result is only useful if you can trust it. Three honesty checks before you act on a number.

### 4.1 Is the sample big enough to mean anything?

If two people saw your fake door and one clicked, your "50% conversion" is noise. There's no magic number, but rough founder-stage sanity:

- **Fake door:** you want at least ~100 visitors before a conversion rate means much; ~30 is a rumor, not a result.
- **Concierge:** even 5–10 customers tells you a lot, *because* you're observing deep behavior, not a shallow click. Depth substitutes for breadth.
- **Prototype:** ~5 moderated sessions surfaces most usability problems (the classic Nielsen finding), but tells you little about demand.

If your sample is tiny, your honest conclusion is often "inconclusive — need more data," and the right move is to *keep the loop running another few days*, not to declare victory or defeat.

### 4.2 Is it signal or noise?

Ask: would this result hold if I ran it again next week with different people? A spike on the day you posted in a friendly community isn't demand — it's your network being nice. Strip out friends, family, and your own cohort. Run it on the *actual segment* from your hypothesis.

### 4.3 Did I measure the deed I committed to?

It's easy, post-hoc, to drift from "refill rate" to "clinics said they liked it." Hold yourself to the *exact* metric and threshold from your hypothesis. If you find yourself reporting a *different* metric than you committed to, that's a tell that the committed one came in badly.

---

## 4.4 Instrumentation: how to actually capture the number

"Measure" sounds simple until you realize you forgot to set up the counting *before* you launched and now your number is a guess. Don't be that founder. Match the instrument to the MVP type, and keep it as light as the experiment:

- **Fake door:** you need two counts — *how many saw the offer* (visitors) and *how many acted* (clicks on the CTA). A privacy-friendly analytics tool (Plausible) or a simple event in PostHog/GA4 captures both, and the ratio is your conversion. Set up the event and test it with your own click *before* you send traffic. If you can't instrument the click, you can't run the experiment.
- **Concierge:** a spreadsheet beats any tool. One row per attempt, columns for the deed (refilled? yes/no) and any notes. Maya's entire measurement system was a Google Sheet with 20 rows. For a one-week, low-volume test, this is *better* instrumentation than analytics — it's auditable and you can see every case.
- **Wizard of Oz:** instrument the front end like a fake door (activation, repeat usage) and log your behind-the-curtain work so you know what it would cost to automate.
- **Clickable prototype:** record the session (with consent) or take notes against a fixed task script, marking completion/failure per participant. Five sessions, five rows.
- **Willingness to pay:** the strongest instrument is a real **Stripe payment link** — a completed checkout is the least-fakeable signal a human can give. (Refund immediately if you can't yet deliver; see the ethics rules in Lecture 1.) A "fake" buy button that leads to "join the waitlist" measures *intent*, which is weaker but still behavioral.

Two rules that save experiments:

1. **Test your measurement before you launch.** Click your own CTA, add a test row, run a $0.50 test charge. Confirm the number lands where you'll read it.
2. **Decide what you'll record before the result exists.** If you find yourself inventing a new thing to count *after* seeing the data, that's a tell — you're fishing for a flattering number. Count the deed in your hypothesis, full stop.

---

## 5. Validated learning

The output of the loop isn't a product — it's **validated learning**: a statement about the world you now believe more (or less) because of evidence. A good validated-learning statement has three parts:

1. **What you tested** (the hypothesis).
2. **What happened** (the metric vs. the threshold, with the number).
3. **What you now believe** (and how confident you are).

Maya's: *"We tested whether front desks would hand off same-day refills (target: 30% refill across two clinics, one week). We refilled 45%. We now believe — with moderate confidence, n=2 clinics — that front desks will adopt this and that manual refill works. Next risk to test: willingness to pay."*

Note the honesty markers: the actual number, the sample size, the confidence level, and the *next* thing to test. That paragraph is the single most valuable artifact you'll produce this week. It's worth more than any code.

---

## 6. Persevere or pivot

Now the decision. Your metric came in. Compare it to the threshold:

### 6.1 Persevere

The metric **cleared the threshold.** You keep the core hypothesis and build the next-cheapest layer — usually testing your *next* riskiest assumption. Persevere does **not** mean "build the whole product now." It means "this assumption held; advance to the next experiment." Maya persevered from concierge to Wizard of Oz, not to a finished app.

### 6.2 Pivot

The metric **missed.** A pivot is a *structured change of direction grounded in what you learned* — not quitting, and not stubbornly re-running the same test hoping for a kinder result. Crucially, a pivot keeps **one foot planted**: you change one major variable and keep the validated parts. The mistake is the "full reset," throwing away everything you learned and starting a brand-new idea from scratch.

**Name the pivot.** "We're pivoting" is vague. Pick which variable you're changing:

| Pivot type | What changes | Example |
|---|---|---|
| **Zoom-in** | A single feature becomes the whole product | Maya drops "refill" and builds *just* the waitlist-management piece people loved |
| **Zoom-out** | The whole product becomes one feature of something bigger | The refill tool becomes part of a full front-desk suite |
| **Customer-segment** | Same problem, different buyer | Pivot from small clinics to dental practices, who cancel more |
| **Customer-need / problem** | Same buyer, different problem | Front desks didn't care about refills but desperately need insurance pre-checks |
| **Platform** | App ↔ platform, or channel of delivery | From standalone tool to a plugin inside their existing scheduler |
| **Channel** | How you reach customers | From cold outreach to partnering with scheduling-software vendors |
| **Business-architecture** | High-margin/low-volume ↔ low-margin/high-volume | From bespoke enterprise to self-serve SMB |
| **Value-capture** | How you make money | From per-seat to per-refilled-slot pricing |
| **Engine-of-growth** | How you scale | From paid acquisition to referral |

A miss is not the week failing — **a miss is the week working.** You spent two days and pocket change instead of two months and your savings to discover the idea-as-stated doesn't hold. That's the entire point. Pivot honestly, name the move, and re-run the loop.

### 6.3 The decision sentence

Whatever you decide, write it as one sentence with the number in it:

> *"We refilled 45% against a 30% threshold, so we **persevere** to a willingness-to-pay test."*
>
> *"We converted 1.2% against a 10% threshold, so we **pivot** (customer-segment) from solo therapists to group practices, who reported the pain far more acutely, and re-run the fake-door test."*

That sentence — number, threshold, decision, named direction — is what the mini-project asks you to commit, and what a Week 10 investor will want to hear.

---

## 6.4 Three fully worked decisions

Decisions are a skill, and skills need reps. Here are three end-to-end calls so you can see the reasoning, not just the rule.

**Decision 1 — a clean pass (persevere).** Maya's concierge refilled 45% against a 30% threshold, n=2 clinics over a week. The number cleared the bar with room to spare, the metric was the exact deed she committed to (slots refilled, not "clinics liked it"), and friends weren't in the sample. The honest read: a pass, with confidence capped at *moderate* by the small sample. **Call:** persevere — advance to willingness-to-pay, the next-riskiest assumption. *"We refilled 45% against a 30% threshold, so we persevere to a willingness-to-pay test."* What she does **not** do: declare victory and start building a full product. One assumption held; the next is still untested.

**Decision 2 — a clean miss (pivot).** Devon's fake door converted 1.2% against a 6% threshold, n=250 cold visitors. Big enough sample, right segment, real deed (clicked "start free trial"). The complaints in interviews didn't translate into intent. The honest read: a clear miss — the *idea as stated* doesn't hold. But Devon noticed in his analytics that a small cluster of *agency owners* (not solo freelancers) converted at 8%. **Call:** pivot, customer-segment. *"We converted 1.2% against a 6% threshold, so we pivot from solo freelancers to agencies — who converted at 8% in the same test — and re-run the fake door aimed at them."* What he does **not** do: keep the same audience and "improve the copy" to chase a number the data already answered.

**Decision 3 — a genuine inconclusive (gather more).** A founder ran a fake door, set a 10% threshold, and got 11% — but on only 28 visitors, most from her own community. The number *technically* passed, but the sample is tiny and biased. The honest read: not enough signal to trust either way. **Call:** gather more. *"11% beat the threshold but on 28 warm-biased visitors, so the result is inconclusive — re-run with cold traffic to ~150 visitors before deciding."* The discipline here is resisting the urge to bank a flattering number. A pass you can't trust is not a pass.

Notice the pattern across all three: read the number, check it against the *committed* threshold, sanity-check the sample and the segment, confirm it's a deed not a word, *then* decide — and always write the one-sentence decision with the number in it.

---

## 7. Speed and cost: keep the loop cheap

A few closing rules that separate fast founders from busy ones:

- **Each loop should cost days, not months, and dollars, not thousands.** If your MVP took three weeks to build, it was a small product, not an experiment. Shrink the next one.
- **Run experiments in parallel where you safely can.** While one result lands, design the next.
- **Write down every loop**, even the inconclusive ones. The experiment record (your mini-project deliverable) is a compounding asset: by Week 10 it's the evidence backbone of your pitch.
- **Beware the loop that never closes.** Some founders measure forever, afraid to decide. Set the date in the hypothesis ("by Friday"), and on that date, decide with the data you have — even if it's "inconclusive, run again."

---

## 7.1 Why loop speed *is* runway

Founders treat "runway" (months of money left) and "learning speed" as separate concerns. They're the same concern. Every trip through the build-measure-learn loop spends some runway and buys some certainty. Your survival depends on the *exchange rate*: how much risk you retire per dollar and per week.

Two founders start with the same idea and the same twelve months of savings:

- **Founder A** spends three months building a polished v1, launches, and learns the riskiest assumption was false. Cost of that one lesson: a quarter of their runway. They have time for maybe two more big swings.
- **Founder B** runs a two-day fake door, learns the same "no," pivots, runs another two-day test, learns "warmer," runs a third, finds a "yes." Cost of three lessons: under two weeks. They have time for *dozens* of swings.

Same money, same idea — wildly different number of shots on goal. That's the entire strategic argument for the lean loop: **it converts your fixed runway into the maximum number of validated lessons.** When you catch yourself adding a feature "while you're in there," remember you're not spending an afternoon — you're spending a shot on goal. Most startups don't fail because their one idea was wrong; they fail because they spent all their runway proving *one* wrong idea slowly instead of testing five quickly.

This is also why "the build is the least important phase" isn't a paradox. Building is the part that *spends* runway; measuring and learning are the parts that *buy* something with it. Spend as little as possible on the part that only costs, to maximize the part that pays.

---

## 8. Common mistakes to avoid

- **Optimizing the build instead of closing the loop.** More features, more polish — none of it is learning. Get to measure.
- **Cumulative vanity metrics.** "Total signups" only goes up. Use rates and cohorts.
- **Moving the threshold after the result.** The cardinal sin. The number was a contract.
- **Calling a pivot "quitting" — or calling stubbornness "perseverance."** Both are failures to read the data. Persevere on a clear pass; pivot on a clear miss; gather more on a genuine inconclusive.
- **The full reset.** Throwing away validated learning to chase a shiny new idea. Pivot keeps a foot planted.
- **Never deciding.** Measuring forever to avoid the verdict. Set a date and honor it.

---

## 8.1 A worked vanity-trap case study

A team building a study-group-matching app for university students ran a Wizard-of-Oz MVP and came to "office hours" glowing: **1,200 signups in two weeks.** That number feels like a company. It is not.

Walk it through the three vanity tests:

- **Actionable?** Would a *lower* signup count have changed their plan? No — they'd have said "early days, keep pushing" at 600 too. A number that doesn't change a decision is vanity.
- **A rate or a cumulative total?** Cumulative. It only goes up. It will read "1,200" forever, even if not one of those students ever forms a study group.
- **A deed or a word?** Signing up is barely a deed — it's a click and an email. The deed that *matters* is "actually got matched into a group and met." 

The honest metric was hiding underneath: of the 1,200 signups, how many completed the core action — got matched and attended one session? The answer was **41**. A 3.4% activation rate. *That's* the actionable number, and it was telling a very different story than "1,200." The team had been celebrating the vanity metric and ignoring the one that decided whether the product worked.

The fix isn't "signups are bad." It's: behind every flattering cumulative total, find the *cohort* and the *deed* — "of the people who signed up this week, what fraction did the thing that proves the assumption?" When the team re-ran with **activation rate** as their OMTM and a 15% threshold, they got an honest read, missed it, and made a productive customer-need pivot. The 1,200 number had been actively hiding the truth for two weeks.

> The danger of a vanity metric isn't that it's useless — it's that it's *comforting*. It feels like progress, so it postpones the hard question. Every week you spend admiring a cumulative total is a week you didn't spend learning whether the thing works.

## 8.2 Quick FAQ

**"My sample is tiny — is the experiment worthless?"** No. A small concierge sample (5–10 customers) with deep behavioral signal is often more decisive than a big shallow one. State the sample size and cap your confidence accordingly: "moderate confidence, n=2." A tentative conclusion honestly labeled beats a confident one that's lying about its sample.

**"What if the result is right at the threshold?"** Treat a near-miss/near-hit as *inconclusive* and gather a bit more, rather than forcing a verdict on noise. The threshold is a decision aid, not an oracle.

**"Can I change my metric mid-experiment?"** No. Changing the metric or threshold after launch is the cardinal sin — it's how every result becomes a "win." If you realize the metric was wrong, finish the run, record that learning honestly, and fix the metric for the *next* loop.

**"How many loops should I run before deciding the whole idea is dead?"** There's no fixed number, but a useful rule: if you've pivoted on the *same* riskiest assumption two or three times and still can't clear a sane threshold, the problem may not be your solution — it may be that the problem isn't painful enough. That's a Week 2/3 finding arriving late, and it's worth taking seriously rather than pivoting a fourth time.

**"Is a pivot a failure I should hide from investors?"** The opposite. A well-evidenced pivot is one of the strongest things you can tell an investor: it proves you run experiments, read results honestly, and change course on data rather than ego. "We believed X, tested it, it didn't hold, here's the pivot and why" is a *credibility* story.

**"My co-founder and I disagree on whether we passed — now what?"** This is exactly why the threshold is set *together and in advance.* When you disagree after the result, go back to the written threshold: did the number clear it or not? That's a fact, not an opinion. The disagreement that remains — "should we persevere despite a miss?" — is a legitimate judgment call, but at least you're arguing about the *decision*, not relitigating what counts as success. If you didn't set a threshold together, fix that before the next loop; ambiguity here poisons co-founder trust (which you formalized back in Week 4).

**"What counts as 'real people' — can my newsletter subscribers count?"** It depends on how warm they are. Anyone with a personal relationship to you (friends, family, classmates) is out — they'll be kind. A newsletter audience that subscribed because of the *problem space* is borderline-acceptable but warm; flag it. The gold standard is people who have no relationship to you and arrived because the offer spoke to them. Mixed sample? Segment it and report cold vs. warm separately, the way Scenario A in the challenge does.

**"The result was a clean pass — am I done with experiments?"** Never. A pass retires *one* assumption; the next-riskiest is still live. Maya's 45% refill rate validated adoption, but willingness-to-pay, reachability, and feasibility are all still untested. "Done" in a startup means you've run out of riskiest assumptions worth testing cheaply — which, in practice, is roughly never. Each pass just promotes the next assumption to the top of the queue.

**"What if I genuinely can't reach the real segment this week?"** Then say so honestly and run the best proxy you can, clearly labeled. A test on an adjacent-but-reachable group, flagged as a proxy, beats both a fake test on friends and no test at all. Just don't quietly pretend the proxy was the real segment — that's the same self-deception in a different costume.

## 8.3 The meta-skill: changing your mind on evidence

Strip away the frameworks and this week teaches one human skill that most people are bad at: *changing your mind because of a number, even when you don't want to.* Every founder says they're data-driven. Far fewer actually let a result overrule a belief they're attached to. The threshold, the vanity-metric audit, the pre-committed hypothesis — these are all scaffolding for that single act of intellectual honesty, because we don't trust ourselves to do it bare-handed.

The founders who last aren't the ones who guess right; they're the ones who notice they guessed wrong *fast* and cheaply, and turn. Practice it on small experiments now, when the stakes are an afternoon and a few dollars, so that when the stakes are your company's last six months of runway, the reflex — *look at the number, honor the threshold, decide, turn if you must* — is already wired in.

One concrete habit makes this real: **say the result out loud to someone before you interpret it.** "We set 30%, we got 8%" is hard to spin when another human just heard you say both numbers. Founders who report results only to themselves, in their own heads, drift toward the kind interpretation every time. Founders who report to a co-founder, a mentor, or even a cohort channel stay honest because the threshold and the result are now witnessed. The challenge this week is built on exactly that mechanic — you're going to read other founders' numbers coldly, then read your own under the same gaze. Build the witnessing into your real company too; it's the cheapest integrity insurance you'll ever buy.

---

## 9. Recap

You should now be able to:

- Run the build → measure → learn loop and explain why minimizing loop time beats maximizing build quality.
- Instrument one actionable metric and pre-commit a threshold, and defend why pre-committing matters.
- Tell a vanity metric from an actionable one, and replace cumulative totals with rates and cohorts.
- Read a noisy result honestly — sample size, signal vs. noise, said vs. did.
- Write a validated-learning statement and make a *named* persevere-or-pivot decision with the number that drove it.

---

## 10. How this connects to the rest of the course

This week's loop isn't a one-off; it's the operating system you'll run for the rest of C25 and beyond.

- **Week 6 (Business Models & Unit Economics)** takes whatever concept survives this week — validated or pivoted — and asks whether it can make money. Your threshold this week often *came from* a rough unit-economics floor; Week 6 makes that floor precise. A concept you pivoted into is a *better* input to the canvas, not a worse one, because it's aimed at real signal.
- **Week 7 (Go-to-Market)** builds on the channel you used to reach your segment this week. The "one metric that matters" discipline you practiced here is exactly the discipline Week 7 applies to a real funnel — and the vanity-vs-actionable distinction is the whole point of spotting vanity traffic metrics.
- **Week 8 (Fundraising)** is where the evidence pays off. Investors fund *de-risked* ideas; every experiment record you produce is a retired risk you can point to. "We tested our riskiest assumption and here's what real people did" is the sentence that separates a fundable founder from a hopeful one.
- **Week 10 (Pitch + Demo Day)** turns your experiment records into the "evidence" and "traction" slides. The decision sentence you wrote this week — number → threshold → decision → direction — is, almost verbatim, the line you'll deliver in the pitch.

Keep every experiment record. By demo day, your stack of honest loops *is* your credibility. A founder who can show three clean experiments — even with two misses and a pivot — is more fundable than one with a polished deck and no evidence, because the first one has proven they can learn, and the second has only proven they can present.

---

*Back to the [week overview](../README.md). Now do [Exercise 1 — Riskiest Assumption](../exercises/exercise-01-riskiest-assumption.md) and [Exercise 2 — MVP Spec Canvas](../exercises/exercise-02-mvp-spec-canvas.md), then run the [MVP mini-project](../mini-project/README.md).*

## References

- *Lean startup* (build-measure-learn, validated learning, pivot) — Wikipedia: <https://en.wikipedia.org/wiki/Lean_startup>
- *Pivot types* — Wikipedia (Lean startup § Pivot): <https://en.wikipedia.org/wiki/Lean_startup#Pivot>
- *Do Things That Don't Scale* — Paul Graham: <https://paulgraham.com/ds.html>
- *The Lean Startup — principles* (official): <https://theleanstartup.com/principles>
- *How to Talk to Users* — Y Combinator: <https://www.ycombinator.com/library/6g-how-to-talk-to-users>
- *Test Cards & Learning Cards* — Strategyzer library: <https://www.strategyzer.com/library>
