# Lecture 2 — Unit Economics That Tell the Truth

> **Duration:** ~1.5 hours of reading + hands-on with a spreadsheet.
> **Outcome:** You can compute contribution margin, CAC, LTV, the LTV:CAC ratio, and the CAC payback period from your own numbers; you can run a sensitivity check; and you can write the one honest sentence that says whether your model makes money at scale and what would have to be true.

If you remember one thing from this lecture, remember this:

> **A business with great revenue and bad unit economics is a machine for losing money *faster* as it grows. Growth is not a strategy for fixing broken unit economics — it's an accelerant for them.**

Lecture 1 gave you the map: a lean canvas with a revenue model and a first price. This lecture does the arithmetic that decides whether the map leads to a business or a hole. The good news: the math is genuinely simple — addition, multiplication, and one division. The hard part isn't the math. It's being honest about the inputs.

We carry Maya's dental-clinic SaaS from Lecture 1 all the way through.

---

## 1. Contribution margin — the profit on one more customer

**Contribution margin** is the money left from one unit (or one customer, one period) after the *variable* costs of serving them — the costs that exist *because* that customer exists.

```
Contribution margin = Price − Variable cost per unit
```

For Maya: she charges **$99/month** and it costs her about **$9/month** to serve one clinic — SMS to patients, payment processing, a sliver of support. So:

```
Contribution margin = $99 − $9 = $90/month per clinic
```

Three distinctions you must keep straight, because conflating them is how models lie:

- **Variable vs. fixed costs.** Variable costs scale with each customer (the $9). Fixed costs — Maya's salary, her base hosting bill, her laptop — exist whether she has 1 clinic or 100. **Unit economics deliberately exclude fixed costs.** Why? Because the question unit economics answers is: *does serving one more customer make or lose money?* If contribution margin is positive, each customer helps pay down the fixed costs. If it's negative, each customer *deepens* the hole, and no amount of scale saves you. Fixed costs matter for "when do we break even overall," which is a different (also important) question we touch in §7.
- **Contribution margin vs. gross margin.** Gross margin is revenue minus cost of goods sold, expressed as a percentage, and it's a whole-company accounting figure. Contribution margin is a per-unit figure focused on *variable* cost. For a software business they're close; for a hardware or services business they can diverge a lot. Use **contribution** for unit economics — it's the number that drives LTV.
- **Margin as a dollar vs. a percent.** Maya's contribution margin is **$90 (a dollar)** or **~91% (a percent: $90/$99)**. Both are useful. The dollar figure drives payback; the percent tells you the business's structural quality. Software's high contribution-margin percentage is exactly why software is a beloved business model — once built, each new customer is almost pure margin.

> **The single most common self-deception** in this whole lecture is forgetting a variable cost. Payment fees (~3%), support time, free-trial infrastructure, the AI inference cost per request for an AI product — these hide. List every cost that grows when you add a customer, or your contribution margin (and everything downstream) is fiction.

---

## 2. CAC — what it really costs to land a customer

**Customer Acquisition Cost (CAC)** is the average fully-loaded cost to acquire one *paying* customer.

```
CAC = Total sales & marketing spend ÷ New paying customers acquired
       (over the same period)
```

The word that does all the work is **fully-loaded**. Early founders compute CAC as "ad spend ÷ signups" and feel great because their ad spend is near zero. That number is a lie of omission. Real CAC includes:

- **Ad / channel spend** (the obvious part).
- **Founder and team time** spent selling, at a notional hourly rate. If Maya spends 6 hours landing a clinic and her time is worth $50/hour, that's $300 of cost *even though no cash left her bank account.* Founder-led sales feels free. It is not — it's the most expensive thing you do, because it doesn't scale and your time is finite.
- **Tools** (CRM, email, demo software) allocated per customer.
- **Content and collateral** amortized across the customers it brought in.

Maya's honest estimate: ~**$300 to land a clinic**, dominated by her own selling time. Note that's a *founder-led-sales* CAC. The trap waiting for her: when she scales beyond what she can personally sell and moves to paid channels, **CAC almost always rises** — paid acquisition is more expensive than a passionate founder closing deals by hand. (Andrew Chen's "Law of Shitty Clickthroughs": channels saturate and get more expensive over time.) That's why §6's sensitivity check on CAC is non-negotiable.

Two CAC flavors worth naming:

- **Blended CAC** = total S&M spend ÷ *all* new customers, including the ones who showed up organically (referrals, word of mouth). Flattering, because the free customers drag the average down.
- **Paid CAC** = spend ÷ customers from *paid* channels only. Less flattering, more honest about whether you can *buy* growth. As you scale, paid CAC is the number that governs you. Report blended if you want, but model paid.

---

## 3. LTV — what a customer is worth before they leave

**Lifetime Value (LTV, sometimes CLV)** is the total *contribution* a customer generates over their entire relationship with you, before they churn.

```
LTV ≈ Contribution margin per period × Expected customer lifetime (in periods)
```

And the lifetime comes from churn:

```
Expected lifetime (periods) ≈ 1 ÷ churn rate per period
```

For Maya: her clinics churn at roughly **4% per month**, so expected lifetime ≈ 1 / 0.04 = **25 months** (she rounds to ~24 for conservatism). With a contribution margin of $90/month:

```
LTV ≈ $90 × 24 = $2,160 per clinic
```

The single most important word here, again: **contribution.** Not revenue. If you compute LTV on *revenue* ($99 × 24 = $2,376) you're counting money you'll spend serving the customer as if it were profit. You'd then "afford" a CAC you can't actually afford, and pay for delivery out of an LTV you never had. **Always LTV on contribution margin.**

### The ways LTV lies (Bill Gurley's warning)

LTV is the most abused number in startup finance. Read Bill Gurley's "The Dangerous Seduction of the LTV Formula" in this week's resources; here's the short version of how the formula misleads:

- **Optimistic churn.** Your *current* churn is measured on early adopters who love you. Mainstream customers churn more. A 4% monthly churn assumption that's really 8% halves your LTV.
- **No discounting.** Money two years from now is worth less than money today. Simple LTV ignores the time value; for early-stage decisions that's usually fine, but know you're rounding up.
- **CAC creep ignored.** LTV is often held constant while CAC quietly rises with scale, so an LTV:CAC that looked great at 100 customers craters at 10,000.
- **Survivorship and cohort blending.** Averaging across cohorts hides that retention is getting *worse* over time.
- **Channel-specific economics.** A customer acquired via referral and one via paid ads can have wildly different LTVs; the blended average hides it.

The fix isn't to abandon LTV — it's to (a) use *contribution*, (b) use a *conservative* churn number, and (c) never let LTV stand alone. Which is why we always pair it with CAC.

---

## 4. LTV:CAC — is a customer worth more than they cost?

Divide the two:

```
LTV : CAC
```

For Maya: **$2,160 : $300 ≈ 7.2 : 1.**

What the ratio means, directionally:

- **Below 1:1** — you lose money on every customer. *Do not scale.* Growth here is the money-shredder. Fix the model first.
- **Around 1:1 to 3:1** — the customer is worth more than they cost, but the margin is thin. Often a sign you're underpricing, your CAC is too high, or your retention is too low. Survivable, not comfortable.
- **Around 3:1 or higher** — the commonly-cited "healthy SaaS" zone. Each customer pays back their acquisition cost several times over, leaving room for the fixed costs and a profit.
- **Way above 5:1** — counterintuitively, this can mean you're *underinvesting in growth* (or underpricing) — you could profitably spend more to acquire customers faster. Maya's 7:1 suggests she has room to spend more on acquisition, which is good news, not just a gold star.

**These are rules of thumb, not laws.** The famous "3:1" comes from observed SaaS distributions, not a theorem. A business with very long retention can thrive at a lower ratio; a business with fragile retention needs a higher one. Use the ratio to *ask questions*, not to declare victory. And never quote a ratio without stating the churn and CAC assumptions under it — the same way you'd never quote a benchmark with no methodology.

---

## 5. Payback period — how fast does the cash come back?

LTV:CAC tells you if a customer is *worth it eventually*. **Payback period** tells you *how long you wait* — how many periods of contribution it takes to repay the CAC you spent up front.

```
CAC payback (periods) = CAC ÷ Contribution margin per period
```

For Maya: **$300 ÷ $90/month ≈ 3.3 months.**

Why payback can matter *more* than LTV:CAC when you're a cash-strapped founder: you pay CAC **today**, in cash, up front, but you collect contribution **slowly**, month by month. The faster a customer repays their CAC, the faster that cash is free to acquire the *next* customer. Short payback is a money-recycling machine; it lets you grow on a small amount of capital. Long payback means your cash is tied up for months in each customer — fine if you have a big balance sheet, dangerous if you're bootstrapping or between rounds.

- **Maya at 3.3 months:** excellent. Each clinic repays its acquisition cost in a quarter, then it's pure contribution for ~21 more months. She can grow largely self-funded.
- **A business at 18-month payback:** every customer ties up cash for a year and a half. The LTV:CAC might still be great, but you need deep pockets (or a raise) to fund the gap. This is exactly why some high-LTV businesses *must* raise — not because the model is bad, but because the payback is long.

Rule of thumb for SaaS: **payback under ~12 months** is generally considered healthy; under 6 is great; over 18 means you'd better have a funding plan. Again — directional, not a law.

---

## 6. State your assumptions, then stress them

Every number above rests on assumptions: price, variable cost, churn/lifetime, CAC. **Write each one down explicitly.** A model whose assumptions are hidden isn't honest, and you can't pressure-test what you can't see. Your unit-economics sheet (Exercise 3, and the mini-project) has an Assumptions section for exactly this reason.

Then run a **sensitivity check**: move the scariest assumptions in the *wrong* direction and recompute. The discipline is to find the one variable that, if it goes bad, breaks the model — and to know in advance how bad it can get before you're underwater.

Maya's base case vs. a stress case where **CAC triples to $900** (realistic as she shifts from founder-led to paid channels):

| Metric | Base case | Stress: CAC → $900 | Stress: churn doubles (8%/mo) |
|--------|----------:|-------------------:|------------------------------:|
| Contribution margin | $90/mo | $90/mo | $90/mo |
| CAC | $300 | $900 | $300 |
| Lifetime | 24 mo | 24 mo | 12 mo |
| LTV (contribution) | $2,160 | $2,160 | $1,080 |
| **LTV:CAC** | **7.2:1** | **2.4:1** | **3.6:1** |
| **Payback** | **3.3 mo** | **10 mo** | **3.3 mo** |

Read the table like a founder:

- **Tripled CAC** drops her to 2.4:1 and a 10-month payback — *thinner, below the 3:1 rule, but still alive.* The model survives a tripling of acquisition cost. That's a robust model.
- **Doubled churn** is the more dangerous one: it halves LTV. Retention, not CAC, is her real fragility. *This is the kind of insight sensitivity analysis exists to produce* — it tells Maya to spend her energy on keeping clinics, not just landing them.

The general lesson: **a model that only works under best-case assumptions is not a model — it's a wish.** A robust model is one where you can move the scary variable substantially in the wrong direction and still not go underwater on every customer.

### Best / base / worst

The clean way to present this: three columns. **Base** (your honest central estimate), **Worst** (pessimistic-but-plausible — not apocalyptic), **Best** (optimistic-but-plausible). If even your *base* case is upside-down, stop and fix the model before building anything else. If your *worst* case is still above water, you have a genuinely robust business — rare and valuable.

### Rank your variables by how much they hurt

Beyond best/base/worst, there's a sharper move borrowed from financial modeling: move *each* assumption, one at a time, by the same proportion (say ±30%) and see which one swings the output most. Rank them. The variable that swings LTV:CAC hardest is the one to validate first and defend hardest — everything else is a rounding error by comparison. For Maya, a ±30% move plays out roughly like this:

| Move this ±30% | Effect on LTV:CAC | Rank |
|----------------|-------------------|-----:|
| Retention / churn | Huge — directly scales lifetime, hence LTV | **1 (most dangerous)** |
| Price | Large — flows through contribution margin *and* LTV | 2 |
| CAC | Moderate — divides the ratio, doesn't touch LTV | 3 |
| Variable cost | Small — Maya's margin is already 91%, so a 30% cost swing barely moves it | 4 |

Read that ranking like a to-do list: it tells Maya to spend her scarce founder energy on **retention first, pricing second**, and to worry far less about shaving variable costs (she's already efficient there). That's the entire payoff of sensitivity analysis — it converts a wall of numbers into a *prioritized list of what to worry about*. Most founders intuitively obsess over CAC because acquisition is visible and stressful; the math often says retention and price matter more. Let the math redirect your attention.

---

## 7. A note on fixed costs and overall break-even

Unit economics deliberately ignore fixed costs — but you the founder can't ignore them forever. Positive contribution margin means each customer *helps* pay the fixed costs; it doesn't mean you're profitable. **Overall break-even** is when total contribution covers total fixed costs:

```
Break-even customers = Total fixed costs per period ÷ Contribution margin per period
```

If Maya's fixed costs (her modest salary, hosting, tools) run $9,000/month, she needs **$9,000 ÷ $90 = 100 clinics** to break even overall. That's a useful, motivating number — it turns "be profitable" into "land 100 clinics" — but keep it *separate* from the per-customer unit economics. A model can have beautiful unit economics and still need a lot of customers to cover its overhead; that's normal, and it's a scale-and-funding question, not a "is the model broken" question. Don't blend the two analyses, or you'll confuse "we lose money on each customer" (fatal) with "we haven't reached break-even volume yet" (just early).

**Why this connects to runway.** The gap between today and break-even volume is the cash you have to fund out of savings or a raise. If Maya is at 30 clinics ($2,700/month contribution) against $9,000/month fixed costs, she's burning ~$6,300/month. With $30,000 in the bank, that's roughly **5 months of runway** — and her unit economics tell her exactly how to close the gap: each new clinic adds $90/month of contribution and costs ~3 months to pay back. This is the bridge to **Week 8 (fundraising)**: the *amount* you need to raise is essentially "the cash to survive from here to break-even volume, plus a buffer." A founder with strong unit economics and a clear path to break-even raises from a position of strength; one with broken unit economics is asking investors to fund a leak. The math you're doing this week is, quite literally, the math that decides how much money you'll need and how convincingly you can ask for it.

---

## 8. The honest verdict — the deliverable's spine

After all the arithmetic, you owe yourself (and your future investors, and your co-founder) one plain sentence. It's the marker from the week overview:

> **This model makes money at scale if and only if `<the one thing>` holds; if it doesn't, the model breaks because `<consequence>`.**

For Maya: *"This model makes money at scale if and only if clinic retention stays near 24 months; if churn doubles, LTV halves and the 3:1 cushion disappears — so retention, not acquisition, is the thing to defend."*

Notice what that sentence does: it names the **single most load-bearing assumption** (retention), states the **consequence** of it failing (LTV halves, ratio collapses), and implicitly tells her **what to work on** (keeping clinics). That's a founder who understands her business, versus one who has a pretty spreadsheet. If you can't write that sentence, go back — you have numbers, not understanding.

---

## 9. The whole chain, worked once, end to end

Let's run a *different* company start to finish so you've seen the full computation on numbers you haven't already memorized. Meet **Tomás**, building **a usage-based AI tool** that drafts contractor bid proposals for small construction firms. He charges **$0.40 per proposal generated**, sells via a freemium funnel (first 5 proposals free), and firms generate ~**50 proposals/month** once they're paying.

**Step 1 — Revenue per customer per month.** 50 proposals × $0.40 = **$20/month** per paying firm.

**Step 2 — Variable cost per customer per month.** This is an AI product, so inference cost is real and per-unit:
- AI inference: 50 proposals × $0.06 = $3.00 (his model API cost per generation)
- Payment processing: ~3% of $20 = $0.60
- Support: ~$1.40
- **Total variable cost = $5.00/month.**

**Step 3 — Contribution margin.** $20 − $5 = **$15/month (75%)**. Healthy percentage; small dollar figure. That small *dollar* figure will matter for payback.

**Step 4 — CAC.** Freemium means his "spend" is partly the cost of serving free users who never convert. Say he spends $200/month on ads bringing 400 signups, ~3% convert to paid = 12 paying firms, and his founder time adds ~$600/month of selling/onboarding. CAC = ($200 + $600) ÷ 12 = **$66.67 per paying firm.** Note how the *free users* and *founder time* both land in CAC — leave either out and the number lies.

**Step 5 — Lifetime and LTV.** His firms churn ~6%/month (construction is seasonal and budget-sensitive). Lifetime = 1 ÷ 0.06 ≈ **16.7 months.** LTV = $15 × 16.7 ≈ **$250** (on contribution).

**Step 6 — The two ratios.**
- LTV:CAC = $250 ÷ $66.67 ≈ **3.75:1** — just above the healthy line.
- Payback = $66.67 ÷ $15 ≈ **4.4 months** — fine.

**Step 7 — The honest read.** Tomás's model works, *barely*, and its fragility is obvious once you see the chain: his contribution margin is only $15 because **AI inference eats 15% of revenue**. If model costs *fall* (they have been, year over year), his margin widens and the model gets stronger; if his firms generate fewer proposals than assumed (say 30, not 50), revenue drops to $12, contribution to ~$9, and payback stretches past 7 months. His scariest variable isn't churn or CAC — it's **proposals-per-firm**, the usage assumption his whole revenue rests on. A founder who ran this chain knows to go validate *usage* first.

The point of working a second, structurally different example (usage-based, freemium, AI-cost-heavy) is to show the *same five formulas* apply everywhere — only the inputs and the fragility change. Subscription, usage, marketplace: same machine, different scary variable.

---

## 10. Simple LTV vs. cohort LTV — when the flat-churn shortcut breaks

We've used `LTV = contribution × (1/churn)`, which assumes a *constant* churn rate forever. Reality is messier and usually kinder in one specific way: churn is rarely flat. Most products lose customers fastest in the first few periods (people who never really activated), then the survivors stick much longer. A flat 5% churn assumption applied to a product whose real curve is "20% in month 1, then 2%/month" will *understate* the LTV of the customers who survive the first month.

The honest tool is a **cohort retention curve** — track what fraction of a cohort (everyone who joined in, say, January) is still paying in month 1, 2, 3, … and sum the contribution across the curve:

```
Cohort LTV = contribution per period × Σ (retention in each period)
```

You don't need this in Week 6 — a single conservative flat-churn number is a fine first model, and the mini-project accepts it. But know the shortcut's failure mode: it's least accurate exactly when retention is *front-loaded-bad-then-good*, which describes most software. If your sensitivity analysis shows LTV is your fragile variable (it often is), graduating from flat churn to a cohort curve is the highest-value refinement you can make — and it's the mini-project's optional stretch for that reason. The discipline either way is the same: **be conservative, and never quote an LTV without the retention assumption stapled to it.**

---

## 11. Reading benchmarks without fooling yourself

You'll be tempted to compare your numbers to "industry benchmarks" — the famous 3:1 LTV:CAC, the sub-12-month payback, "good SaaS gross margin is 70-80%," "best-in-class net revenue retention is 120%+." Benchmarks are genuinely useful as *smell tests*, but they're also where founders get fooled, so a few rules:

- **Know where the number came from.** A benchmark from a survey of *Series-B-and-later* SaaS companies tells you almost nothing about a pre-seed founder doing founder-led sales. The famous numbers usually come from companies far past your stage. Use them to set a *direction*, not a target.
- **A benchmark is a distribution, not a line.** "Healthy LTV:CAC is 3:1" really means "across a sample, the healthy ones clustered around 3:1." Your business might be a perfectly good outlier. Long-retention businesses thrive at 2:1; fragile-retention ones need 5:1.
- **Beware composite benchmarks computed differently than yours.** If a report's "CAC" is paid-channel-only and excludes founder time, and yours is fully-loaded, you're comparing different things. Always check the *definition* behind a benchmark before you panic or celebrate.
- **The benchmark you most need is your own, over time.** Is your CAC rising or falling month over month? Is retention improving as you fix onboarding? *Trend in your own numbers* beats comparison to a stranger's average. A worsening trend at "good" absolute levels is a warning; an improving trend at "bad" levels is a green shoot.

For Week 6, use benchmarks exactly once: as a final sanity check. After you compute your ratios, ask "is this in a plausible zone, or did I make an arithmetic or assumption error?" An LTV:CAC of 40:1 isn't a triumph — it's a signal you underpriced, under-counted CAC, or used fantasy churn. An LTV:CAC of 0.5:1 isn't necessarily a death sentence — but it means "do not scale yet." That's all the benchmark is for at this stage: catching errors and setting direction.

---

## 12. Scenario planning: three futures, not one number

A single sensitivity case (CAC doubles) is the minimum. A more mature version, worth doing once for your real model, is **scenario planning** — sketching two or three coherent *futures* and tracing what each does to the whole model at once. Not one variable moving, but a *story* moving several together.

For Maya, three plausible 18-month futures:

- **"Founder-led forever" (slow, safe).** She stays small, keeps selling by hand. CAC stays ~$300, retention stays high (~4% churn) because she onboards each clinic personally. LTV:CAC ~7:1, payback ~3 months. *Great unit economics, but capped growth* — she can only personally sell so many clinics. This is a lifestyle-business path, and it's a legitimate choice (recall the control-vs-wealth tension from Week 1).
- **"Pour fuel" (fast, risky).** She raises a round and shifts to paid channels to grow 5x. CAC rises to ~$900 (paid is dearer), and if she onboards less personally, churn creeps to 6%. LTV:CAC ~2:1, payback ~10 months. *Viable but thin* — she's now dependent on the round and on fixing retention before the money runs out.
- **"Move upmarket" (different customer).** She targets multi-location dental groups instead of single clinics. Price jumps to $400/month (more value, more chairs), churn drops (bigger customers are stickier), but CAC rises a lot (longer sales cycle) and the sales motion changes entirely. *A different business* — possibly better, possibly a distraction from what's working.

The value of scenarios isn't precision — every number is a guess. It's that laying three coherent futures side by side forces the *strategic* question the single-number model hides: **which future are you actually building toward, and do its unit economics work?** "Pour fuel" only makes sense if she's confident she can hold retention at scale. "Move upmarket" is a bet that the bigger-customer economics beat the simpler small-clinic ones. A founder who's modeled all three walks into a fundraising conversation (Week 8) able to say "here's the path I'm taking and here's why its economics hold" — which is a categorically stronger position than "here's my one spreadsheet."

You don't have to build three full models in Week 6. But name, in a sentence each, the two or three futures your concept could take, and note which one your unit-economics base case actually represents. It's the bridge from "does this make money" (this week) to "how do we grow it" (Week 7) and "should we raise" (Week 8).

---

## 13. Common ways unit economics lie

The failure modes graders and investors catch instantly:

- **Revenue-based LTV.** Counting the whole price as profit. Always use contribution.
- **Ad-spend-only CAC.** Forgetting founder time. Founder-led sales is the most expensive channel, not the free one.
- **Optimistic churn.** Using your honeymoon-phase retention as if it'll hold for the mainstream.
- **Forgotten variable costs.** Payment fees, support, free-trial infra, AI inference per request. Each one quietly shrinks contribution margin.
- **No sensitivity.** A single best-case column with no stress test. The first thing a sharp investor does is double your CAC and halve your retention in their head — beat them to it.
- **Blending unit economics with fixed-cost break-even.** Confusing "negative contribution margin" (fatal) with "haven't hit break-even volume" (just early).
- **A ratio with no assumptions attached.** "We're at 5:1!" — under what churn? what CAC? An unsourced ratio is a vanity metric.

---

## 14. The founder's dashboard: which number to watch when

You can't watch all five metrics with equal intensity at every stage — and you shouldn't try. The number that deserves your obsession changes as you grow, and knowing *which one* is itself a sign of a maturing founder.

- **Pre-revenue / first customers (you, now):** watch **contribution margin** and **willingness to pay**. You don't have enough customers for CAC or churn to mean anything statistically. The question is just: *is there positive margin, and will they pay the price?* If contribution margin is negative, nothing else matters — fix it first.
- **First repeatable sales (Week 7 territory):** watch **CAC** and **payback**. Now you're spending to acquire and you need to know if the channel is affordable and how fast cash recycles. A channel with a 3-month payback funds your next experiment; an 18-month one drains you.
- **Early scale:** watch **retention / churn** above all. This is where most models actually live or die, and where Maya's sensitivity analysis pointed. Acquisition gets the glory; retention pays the bills. A leaky bucket can't be filled faster than it drains.
- **Fundraising and growth (Weeks 8+):** watch **LTV:CAC trend** and, eventually, **net revenue retention**. Investors care less about a snapshot than about the *direction* — is each cohort better than the last?

The discipline: at any moment, you should be able to name the *one* number that, if it moved against you, would most threaten the business — and that's the one on your dashboard. For most pre-PMF founders this week, it's **contribution margin** (is there a business at all?) closely followed by the **willingness-to-pay** question behind the price. Everything else is a future week's obsession. Don't drown in metrics you're not ready to act on; pick the one that matches your stage and watch it like a hawk.

---

## 15. Recap

- **Contribution margin** = price − variable cost per unit. It's the profit on one *more* customer, before fixed costs. Get every variable cost in, or everything downstream is fiction.
- **CAC** = fully-loaded acquisition spend ÷ new paying customers — *including founder time*. It rises as you scale from founder-led to paid channels.
- **LTV** = contribution margin per period × lifetime (≈ 1/churn). On **contribution**, never revenue. Use a conservative churn number.
- **LTV:CAC** ≈ 3:1 is the healthy rule of thumb; below 1 means stop; way above 5 may mean you can spend more on growth.
- **Payback** = CAC ÷ contribution margin per period. Short payback recycles cash and lets you grow self-funded; long payback needs a balance sheet.
- **State assumptions, then stress them.** Find the variable that breaks the model. Present base/worst/best. A model that only works best-case is a wish.
- Finish with the **one honest sentence**: makes money at scale iff `<X>` holds, else it breaks because `<Y>`.

---

*Back to the [week overview](../README.md). Now do [Exercise 1](../exercises/exercise-01-canvas-and-margins.md), fill your [unit-economics sheet](../exercises/exercise-03-unit-economics-sheet.md), and bring it all together in the [mini-project](../mini-project/README.md).*
