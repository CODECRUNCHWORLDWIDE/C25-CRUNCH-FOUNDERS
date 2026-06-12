# Lecture 2 — Traction and Metrics

> **Duration:** ~2 hours of reading + putting numbers on your own funnel.
> **Outcome:** You can pick the one metric that matters for your stage, separate vanity metrics from actionable ones using a concrete test, build an AARRR funnel and diagnose its leakiest step, tell leading indicators from lagging ones, and design a cheap channel experiment with a success bar you set *before* you see the data.

If you only remember one thing from this lecture, remember this:

> **Traction is evidence that people use and pay — not evidence that people noticed.** A million people noticing you is worth less than ten people paying you. The entire skill this week is learning to feel that in your gut, so "two paying clinics" lands as a bigger win than "ten thousand impressions" — because to anyone who matters, it is.

---

## 1. What traction actually is

"Traction" is one of the most abused words in startups. Investors use it as a gate ("come back when you have traction"); founders use it as a hope ("we're getting traction"). Both usually mean something vague.

Here's a working definition you can defend: **traction is evidence of real, repeated customer behavior that moves toward money.** The key words:

- **Evidence** — a number, not a feeling. "People love it" is not traction. "12 of 15 trial users converted to paid" is.
- **Real behavior** — something the customer *did*, not something they said they'd do. A waitlist signup is a promise; a payment is behavior.
- **Repeated** — once is luck; repeated is a pattern. Retention is the heart of traction.
- **Toward money** — even pre-revenue, the behavior has to be on the path to revenue. An activated user who does the core action weekly is traction; a follower who'll never pay is not.

The skeptic's test we use all week: **"Would a skeptical investor count this?"** A thousand waitlist emails: no. Ten people who paid: yes. Five who renewed: absolutely. If the number goes up when you do nothing, it's not traction — it's weather.

### A ladder of evidence, weakest to strongest

Not all evidence is equal. Here's roughly how a skeptic ranks the things founders call "traction," from least to most convincing:

1. **Impressions / followers / page views.** Almost worthless alone — attention without intent.
2. **Email signups / waitlist.** A weak promise; cheap to give, easy to ignore later.
3. **Waitlist with a refundable deposit.** Much stronger — they put money down, even if reversible.
4. **Activated users (did the core action once).** Real behavior; they experienced the value.
5. **Repeat usage / retention.** Strong — they came back, which means it actually helped.
6. **A paying customer.** Strong — they valued it more than the money.
7. **A *renewing* paying customer.** Strongest early signal there is — they paid, used it, and chose to pay again.

The practical move: **always try to climb this ladder.** If all you have is signups, can you convert a few to a paid pilot? If you have one-time users, do any come back? Every rung up is worth more than ten times the volume at the rung below. A founder with five renewing customers is in a stronger position than one with fifty thousand newsletter subscribers — and any experienced investor knows it.

Notice this also tells you what to *build your test around.* Don't design a channel test whose only output is signups (rung 2) if you could design one that produces a paid pilot (rung 6) from the same effort. Aim your experiment as high up the ladder as your stage allows.

---

## 2. The One Metric That Matters (OMTM)

From Croll & Yoskovitz's *Lean Analytics*: at any given stage, there is **one metric that matters more than all the others combined.** Pick it, put it on the wall, and let it drive your focus. This is not because the other metrics don't exist — it's because focus is the scarcest resource a founder has, and tracking forty metrics is a sophisticated way of avoiding the one that would tell you the truth.

How the OMTM changes by stage:

| Stage | The question you're answering | A good OMTM |
|-------|-------------------------------|-------------|
| **Pre-product / discovery** | Do they want it badly enough to act? | Letters of intent, pre-orders, or waitlist *with a deposit* |
| **MVP / pre-revenue** | Does the core action deliver value repeatedly? | Weekly activated users who do the core action |
| **Early revenue** | Will they pay, and keep paying? | Paying customers, or monthly recurring revenue (MRR) |
| **Marketplace** | Do both sides transact? | Completed transactions per week |
| **Scaling (later)** | Does growth compound profitably? | LTV:CAC, or net revenue retention |

The OMTM is a *spotlight*, not blinders. You still glance at the funnel around it. But when you have to decide what to work on this week, you ask: "what moves the OMTM?" and you ignore the rest.

> **Maria's OMTM:** she's at early-revenue stage, so her OMTM is **clinics that complete a paid onboarding** — money in the bank and the product actually in use. Not website visits (vanity), not demos booked (a leading indicator she watches, but not the one she optimizes), not "interested" replies. Paid onboarding is the number on her wall.

A note on the "North Star Metric": same idea, slightly different flavor. A North Star is usually a single *value-delivered* metric a whole company aligns on long-term (e.g., "nights booked" for Airbnb). For a pre-traction solo founder, OMTM and North Star collapse into the same thing: the one number that tells you if you're really making progress now.

---

## 3. Vanity vs. actionable metrics

This is the distinction that separates founders who fool themselves from founders who learn. From Eric Ries's *The Lean Startup*:

- **Vanity metrics** are big, flattering, and useless for decisions: total page views, total signups *ever*, social followers, "registered users," cumulative app downloads, press impressions. They share a tell: **they only go up.** A cumulative total can never deliver bad news, which is exactly why it's worthless for steering.
- **Actionable metrics** tie to real behavior and drive a decision: activation rate, week-over-week retention, conversion to paid, MRR, repeat purchase rate, churn. They can go *down*, which is what makes them honest.

### The three-question test

For any metric, ask:

1. **Does it change behavior?** If the number moved, would you know what to do differently? (Vanity metrics don't tell you what to do.)
2. **Is it comparable over time / across cohorts?** A *rate* ("8% of trials convert") is comparable; a cumulative total ("4,300 signups") buries this week's reality under all of history.
3. **Is it a ratio or a rate, not a running total?** Ratios and rates expose change; totals hide it. "Conversion rate" beats "total conversions"; "weekly active / signed up" beats "total users."

If a metric fails these, it's vanity. The fix is almost always to **turn the total into a rate.** Don't track "10,000 visitors" — track "5% of visitors start a trial." Don't track "2,000 signups" — track "this cohort's week-4 retention." Same data, decision-grade framing.

### A field guide

| Vanity (don't optimize) | Actionable rewrite (do optimize) |
|-------------------------|----------------------------------|
| Total page views | Visitor → signup conversion rate |
| Total signups ever | This week's signups → activation rate |
| Social followers | Follower → website-click rate, or content → demo rate |
| App downloads | Download → day-7 retention |
| Emails collected | Email → paid conversion rate |
| "Interested!" replies | Reply → demo-booked rate |
| Hours of usage (raw) | % of users hitting the core action ≥ N times/week |

> **Maria's hunt:** her landing page got 1,400 views last month (vanity — it went up because she posted once, tells her nothing). The actionable version: of the 40 clinics she *contacted*, what fraction replied, demoed, trialed, paid? That's a funnel she can act on.

---

## 4. The funnel: AARRR / pirate metrics

Dave McClure's "pirate metrics" give you a funnel skeleton that fits almost any business. Say it out loud — **AARRR** — and you'll remember it.

| Stage | Question | Example metric |
|-------|----------|----------------|
| **Acquisition** | How do people find you? | Visitors, replies, leads |
| **Activation** | Do they have a great first experience (the "aha")? | % who complete the core action once |
| **Retention** | Do they come back? | % active in week 2, 4, 8 |
| **Referral** | Do they tell others? | Invites sent, referral conversion |
| **Revenue** | Do they pay? | Conversion to paid, MRR |

A simpler version for the very early stage, which is what you'll actually use this week:

```
Reach   →   Interest   →   Activation   →   Retention / Revenue
(saw it)    (clicked/      (did the core    (came back /
             replied)       action once)     paid)
```

The two stages founders most often conflate are **Acquisition** and **Activation**. Acquisition is "they showed up." Activation is "they got value." A funnel that's great at acquisition and terrible at activation is a leaky bucket — you pour people in the top and they fall out before they ever experience the product. This is the most common early-startup pathology, and the most fixable once you *see* it.

### The leakiest step

Put **real numbers** on every step, then compute the conversion *rate* between each pair of steps. The **leakiest step** — the biggest percentage drop — is where you focus, because fixing the worst leak moves the whole funnel the most.

Worked example, Maria's funnel:

```
40 clinics contacted
12 replied          → 30% of contacts          (reach → interest)
 6 took a demo      → 50% of replies           (interest → activation-ish)
 3 started a trial  → 50% of demos   ← LEAK     (demo → trial)
 2 paid             → 67% of trials             (trial → revenue)
```

Where's the leak? It's tempting to panic about "only 2 paid from 40 contacted" — but look at the *rates*. The biggest controllable drop is demo → trial (half the people who *saw a demo* walked away). That's the leak. Fixing the contact → reply rate (a top-of-funnel volume problem) helps, but fixing demo → trial fixes a *conviction* problem — people see it and aren't convinced. That's the more dangerous, more informative leak, and it's where next week's work goes.

The discipline: **don't optimize the step that's easiest to move; optimize the step that's leaking the most.** And read rates, not raw counts — "2 out of 40" hides where the problem actually is.

---

### Rough benchmarks (use as sanity checks, not laws)

Founders constantly ask "is my conversion rate good?" The honest answer is "compared to what?" — but here are loose 2026 reference ranges so you can tell a catastrophe from a normal number. Treat these as conversation-starters; your specific market, price, and channel move them a lot.

| Step | Rough early-stage range | Notes |
|------|-------------------------|-------|
| Cold email → reply | 1–10% | Personalized to a tight, named list lands at the high end; templated blasts at the very low end (or zero, in spam). |
| Reply → meeting/demo | 20–50% | If they replied, they're warm; a low rate here usually means a weak ask or wrong-fit list. |
| Demo → trial/next step | 30–60% | Below ~30% signals a conviction or fit problem — the demo isn't landing. |
| Trial → paid (B2B) | 10–25% | Free-trial-to-paid; varies wildly by product and how qualified the trial is. |
| Landing page visitor → signup | 1–5% | Cold traffic. Warm/referred traffic converts much higher. |
| Free signup → paid (PLG) | 1–5% | Freemium conversion is famously low; the model assumes huge top-of-funnel. |

The point of benchmarks is **triage, not targets.** If your demo→trial is 5%, you don't have a "slightly below average" problem — you have a five-alarm fire telling you the product or the pitch is wrong. If it's 45%, stop optimizing it and go fix whatever's actually leaking. Don't obsess over hitting a number from a table; obsess over the *shape* of your own funnel.

A warning specific to early stage: **with tiny numbers, these rates are noisy.** "1 reply from 40" is 2.5%, but it's also basically a coin flip — you can't distinguish it from 0% or 5% with that sample. Use benchmarks to spot disasters, not to fine-tune. Real optimization needs more volume than you have in week one.

---

## 5. Leading vs. lagging indicators

- A **lagging indicator** reports the past: revenue, churn, total customers. It tells you what happened. It's true but it's *late* — by the time revenue moves, the cause is weeks old.
- A **leading indicator** predicts the future: demos booked, trials started, activation rate. It moves *first* and lets you steer.

Early founders should watch **leading indicators** to make decisions and **lagging indicators** to keep score. Maria's revenue (lagging) was $0 for weeks before her first sale — useless for steering. Her demos-booked-per-week (leading) was telling her something every single day. If demos booked dries up, she knows revenue will dry up in a month, and she can act *now.*

The trap: optimizing a leading indicator that doesn't actually lead to anything. "Demos booked" only matters if demos convert to revenue. Always tie your leading indicator back to the OMTM and sanity-check that the link is real.

---

## 6. Cohorts and retention, briefly

The truest early signal of all is **retention**: of the people who tried it, do they come back? Retention is the metric that's hardest to fake and the one investors trust most, because it directly answers "does this actually solve the problem?"

A **cohort** is a group defined by when they started — "everyone who signed up in May." You track each cohort's retention over time (week 1, 2, 4, 8). The shape of the curve tells the story:

- A curve that **flattens** above zero = you have a core of people for whom this is genuinely valuable. Even a small flat tail is a real signal. This is what product/market fit looks like in a chart.
- A curve that **decays to zero** = a leaky bucket. No matter how good acquisition looks, you're filling a bucket with a hole in it. More acquisition just wastes more people.

You can't run a full cohort analysis this week (you don't have enough users yet), but internalize the principle: **acquisition without retention is a treadmill.** If your channel test produces signups that don't stick, the answer isn't "more signups" — it's "fix the product or the targeting first." A thousand signups that all churn is worth less than ten that stay.

---

## 6b. How to actually count (without overbuilding)

A surprising number of founders stall here: "I'd measure my funnel, but I don't have analytics set up." You don't need analytics. At this stage, **the right tool is a spreadsheet, and the right method is by hand.**

For an outbound/founder-led motion, one row per prospect:

```
Clinic            | Contacted | Replied | Demo booked | Demo done | Trial | Paid | Notes
Maple Dental      | 06-12     | yes     | 06-14       | 06-15     | yes   | yes  | loved no-show stat
Riverside Family  | 06-12     | yes     | 06-14       |           |       |      | wants to "think"
Oak Street Clinic | 06-12     |         |             |           |       |      | no reply
...
```

Your funnel is just column sums. Replied = count of "yes" in that column. The conversion rates fall out of dividing adjacent sums. That's it. No event tracking, no dashboards, no SQL. The sheet *is* your analytics, and for fewer than a few hundred prospects it's actually *better* than a tool — because you see every row and remember every conversation.

For an inbound/content/PLG motion you do need to count anonymous visitors, so a lightweight tool helps: your form builder's built-in stats, a privacy-friendly analytics free tier, or just the signup count in your database. The principle is the same — **count the smallest number of steps that lets you find the leak**, and no more.

The anti-pattern to avoid: spending two days wiring up a full product-analytics stack before you have ten users. That's procrastination dressed as rigor. Instrument when you have enough volume that hand-counting breaks — not before.

A note on **attribution**: when you eventually run more than one channel, you'll want to know which one a customer came from. The cheap version is a single question on signup ("how did you hear about us?") or a distinct link per channel. Don't build a multi-touch attribution model at this stage; just know, roughly, where each customer originated.

---

## 7. Computing the numbers that matter

You don't need a finance degree. You need four numbers, and you already have most of them from Week 6.

**Conversion rate per step.** Of the people who reached step N, the fraction who reached N+1. `replies ÷ contacts`, `demos ÷ replies`, and so on. This is how you find the leak.

**Blended CAC from a real test.** Total spent (money + the value of your time) ÷ customers won.

> Maria's two-week test: she spent ~$0 in cash but ~20 hours of her time. Value her time at $50/hr → $1,000 of "spend." She won 2 customers. **Blended CAC ≈ $500/customer.** That sounds high until you compare it to LTV.

**Payback against LTV (from Week 6).** Maria's LTV was ~$1,400/clinic. CAC of ~$500 gives **LTV:CAC ≈ 2.8:1** — just under the ~3:1 health target, and it'll improve as she gets faster at selling. Payback: at $99/month with, say, ~$70 contribution margin/month, $500 CAC pays back in ~7 months. Comfortable.

**The honest caveat:** with only 2 customers, these numbers are *directional, not statistical.* You can't conclude "my CAC is exactly $500" from a sample of 2 — you can conclude "this motion is plausibly affordable, keep going." Don't over-fit tiny samples; do use them to decide whether to continue.

The point of the math: it turns "I did some outreach" into "this motion can or can't work at my price." That's the difference between activity and evidence.

---

## 8. Designing a cheap channel test

Everything above comes together in one deliverable: a **time-boxed channel experiment with a pre-registered success bar.** The structure:

1. **One channel.** Pick the single inner-ring channel from Lecture 1. Not three. One.
2. **A specific action.** "Contact 40 named clinics by personal email." Concrete enough that anyone could check whether you did it.
3. **A time box.** One to two weeks. Long enough to get a signal, short enough to force a decision.
4. **A pre-registered success bar.** Decide *now*, before any data, what counts as a win. "Win = ≥ 2 paid onboardings (or ≥ 4 trials started)." Write it on an index card and hand it in.
5. **A funnel to record.** Log every step: contacted → replied → demoed → trialed → paid, with dates.
6. **A decision rule.** Decide in advance what each outcome means: hit the bar → double down; missed but the funnel shows a fixable leak → fix and re-run once; missed with no signal → kill the channel and try the next inner-ring option.

**Why pre-register the bar?** Because the most natural thing in the world is to run a test, get a weak result, and then *invent a reason it's actually fine* ("well, it's only been a week," "the holidays hurt us," "one more push"). Setting the bar in advance is how you keep yourself honest. The "one more week" trap — extending a failing test indefinitely because quitting feels like losing — has killed more runways than any single bad decision. The bar protects you from yourself.

> **Maria's test plan:** Channel = personal cold email. Action = 40 named clinics in two weeks. Success bar (pre-registered) = ≥ 2 paid onboardings OR ≥ 4 trials started. Funnel logged in a sheet. Decision rule = hit → scale to 200 clinics next; miss-with-leak → fix the demo and re-run on 40 fresh clinics; miss-no-signal → switch to the practice-management-forum channel.

That's the field work for Wednesday–Thursday, and it's the spine of your mini-project.

---

## 8b. A worked vanity-metric autopsy

Let's slow down on one real-feeling mistake, because it's the one you're most likely to make.

Imagine you launch and your numbers look *amazing*: a Product Hunt post drives 6,000 visitors in a day, your signup count rockets to 1,200, your X following triples. You feel like a rocket ship. You tell your friends, you update your investors, you start thinking about hiring.

Now apply the skeptic's test and the three questions.

- **6,000 visitors** — would a skeptical investor count this? No. It's a one-day spike from a launch, not a repeatable channel. It only goes up. *Vanity.*
- **1,200 signups** — these are emails, not customers. How many activated? You check: 90 connected an account and actually used the core feature. So your *real* number is 90, and your activation rate is a brutal 7.5%. The 1,200 was hiding the truth. *Vanity, until turned into the activation rate — which is actionable, and alarming.*
- **3x followers** — do followers buy anything? You check: zero of your paying users came from your X following. *Pure vanity.*

The honest read: you don't have 1,200 of anything useful. You have **90 activated users and a 7.5% activation leak** screaming that your onboarding is broken. The vanity numbers didn't just flatter you — they actively hid the one problem you most needed to see. A founder who celebrates the 1,200 and scales acquisition pours more people into a bucket that loses 92% of them. A founder who sees the 7.5% fixes onboarding first and *then* turns on acquisition.

This is why the discipline matters. Vanity metrics aren't just useless; they're *dangerous*, because they feel like success while pointing you away from the real work. Every time a number makes you feel great, that's exactly when to run the three questions on it.

---

## 9. Common failure modes (so you can name yours)

- **Optimizing a vanity metric.** Pouring effort into followers or page views because they go up and feel good.
- **Confusing acquisition with activation.** Celebrating signups while ignoring that none of them ever used the product.
- **Reading raw counts, not rates.** Panicking about "2 of 40" instead of finding which *rate* is the real leak.
- **No pre-registered bar.** Running a test with no definition of success, so any result can be spun as "promising."
- **The "one more week" trap.** Extending a failing test forever because killing it feels like admitting defeat.
- **Over-fitting tiny samples.** Treating 2 customers as a precise CAC measurement and building a spreadsheet empire on it.
- **Acquisition without retention.** Scaling a channel that brings in people who immediately churn — filling a leaky bucket.

---

## 9b. How to present traction honestly (looking ahead to Week 10)

The metrics you build this week become your **traction slide** at demo day. A few rules for presenting them so they land as credible rather than inflated — because experienced listeners can smell a vanity metric from across the room, and one inflated number poisons trust in all your others.

- **Lead with the strongest *real* number, not the biggest number.** "Two clinics are paying and one renewed" beats "1,200 signups" with any audience that matters. The big number invites the question "okay, but how many *pay*?" — and now you're on the back foot. Lead with the answer to the skeptic's question.
- **Show the funnel, not just the endpoint.** "40 contacted → 12 replied → 6 demoed → 2 paid" tells a story and proves you understand your own business. A single number tells nothing and looks like you're hiding the rest.
- **Name the leak and your plan for it.** Saying "our demo→trial rate is our weak point and here's the fix we're testing" reads as *more* fundable, not less. It signals you reason from data. Founders who pretend everything is perfect look naive; founders who know exactly where their funnel leaks look like operators.
- **Use rates and time frames.** "8% trial-to-paid over the last 30 days" is credible. "Lots of interest" is noise.
- **Never present a vanity metric as if it were traction.** If you show followers or impressions, an experienced listener mentally discounts *everything else* you said. Guard your credibility; it's the only currency you have pre-revenue.
- **Be honest about the sample size.** "From a small sample of 2 paying customers, our early CAC looks like ~$500" is honest and disarming. Stating a tiny-sample number as gospel invites a question you can't answer.

The throughline: **the same honesty that makes your metrics useful to you makes them credible to others.** You're not building two sets of numbers — a real one for yourself and a flattering one for the pitch. You build one honest funnel, and you present it plainly. That's the whole discipline, and it pays off twice.

---

## 10. Recap

You should now be able to:

- Define **traction** as evidence of real, repeated behavior toward money, and apply the skeptic's test.
- Pick the **OMTM** for your stage and use it as a spotlight without going blind to the rest of the funnel.
- Separate **vanity from actionable** metrics with the three-question test, and rewrite any vanity metric into a rate.
- Build an **AARRR funnel**, compute per-step conversion, and find the **leakiest step** by reading rates, not counts.
- Tell **leading from lagging** indicators and use leading ones to steer.
- Explain why **retention** is the truest early signal and what a leaky bucket is.
- Compute **conversion rate, blended CAC, and payback** against last week's LTV — and not over-trust a tiny sample.
- Design a **time-boxed channel test** with a pre-registered success bar and a decision rule.
- Place any number on the **ladder of evidence** and aim your test as high up it as your stage allows.
- Use **rough benchmarks** to triage your funnel — spotting disasters, not chasing arbitrary targets.
- **Count by hand in a spreadsheet** without overbuilding analytics, and instrument only when volume demands it.
- **Present traction honestly** so it reads as credible at demo day rather than inflated.

One last reframe to carry into the field work: the goal this week is not to *get* good numbers — it's to *learn the truth* about whether you can reach customers. A test that honestly fails its bar and teaches you the channel is dead is a *success* of process, and it saves you months. A test you fudge into looking good is a failure dressed up, and it costs you those same months later, with interest. Optimize for truth, and the good numbers (or the honest pivot) follow.

Now go do it. Start with [Exercise 1 — Funnel and metric](../exercises/exercise-01-funnel-and-metric.md), design your test with [Exercise 2](../exercises/exercise-02-channel-test-plan.md), and pull it together in the [GTM one-pager mini-project](../mini-project/README.md).

---

## References

- *Startup Metrics for Pirates (AARRR)* — Dave McClure: <https://www.slideshare.net/dmc500hats/startup-metrics-for-pirates-long-version>
- *Lean Analytics* (One Metric That Matters) — Croll & Yoskovitz: <https://leananalyticsbook.com/>
- *The Lean Startup* (vanity vs. actionable) — Eric Ries: <https://theleanstartup.com/principles>
- *North Star Metric playbook* — Amplitude: <https://amplitude.com/blog/product-north-star-metric>
- *SaaS Metrics 2.0* (CAC, LTV, payback) — David Skok: <https://www.forentrepreneurs.com/saas-metrics-2/>
- *The Law of Shitty Clickthroughs* (channel decay) — Andrew Chen: <https://andrewchen.com/the-law-of-shitty-clickthroughs/>
- *Customer retention* — Wikipedia: <https://en.wikipedia.org/wiki/Customer_retention>
