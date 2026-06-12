# Lecture 1 — The MVP Is an Experiment, Not a Tiny Product

> **Duration:** ~2 hours of reading + worksheet.
> **Outcome:** You can name your single riskiest assumption, pick the cheapest MVP type that could falsify it, and write the test as a hypothesis with a pre-committed threshold — all before you build anything.

If you remember one sentence from this entire week, make it this one:

> **A minimum viable product is the smallest thing that produces validated learning about your riskiest assumption — it is an experiment, not a tiny version of the final product.**

Most first-time founders hear "MVP" and build a stripped-down app. Three weeks later they have a worse product and zero new knowledge. We are going to do the opposite: spend almost no money, almost no time, and walk out with a *decision*.

---

## 1. The reframe, and why it's the whole ballgame

There are two definitions of MVP fighting for space in your head, and only one of them is useful.

**The bad definition:** "An MVP is the smallest product I can ship." Under this definition, an MVP is a product with fewer features. You scope down, cut corners, and launch something embarrassing. The trouble is that "smaller product" still takes weeks, still requires you to guess at what's worth building, and still tests *nothing in particular*. If it flops, you don't know which of the ten things you guessed wrong about killed it.

**The good definition:** "An MVP is the smallest *experiment* that tells me whether my riskiest assumption is true." Under this definition, an MVP has a hypothesis, a method, a metric, and a result. It might involve no product at all. It is judged not by how polished it is but by how much *risk it retires per dollar and per day*.

The reframe matters because the two definitions point at completely different work. The bad definition sends you to build. The good definition sends you to *think*: what must be true for this to work, which of those things am I least sure of, and what's the cheapest way to find out?

Here's the test that separates them. Ask of anything you're about to make: **"If this goes well, what will I have learned? If it goes badly, what will I have learned? And would a bad result actually change what I do next?"** If you can't answer all three crisply, you're building a tiny product, not running an experiment.

A worked contrast. Maya (our clinic-no-show founder from the week overview) could:

- **Bad MVP:** spend three weeks building a stripped-down waitlist app, launch it to one clinic, and watch it sit unused. She learns "this one clinic didn't use it" — but not *why*, and not whether the idea is dead.
- **Good MVP:** spend two days texting waitlisted patients *by hand* for two clinics and count how many cancellations she refills. She learns the exact thing that decides the company: *will front desks hand off the scramble, and does manual refill even work?* — for the cost of her own time.

Same week. One produces a decision; the other produces a worse app.

---

## 2. Riskiest-assumption thinking

Every startup idea is a tower of assumptions stacked on each other. Pull out the wrong block and the tower stands. Pull out the load-bearing one and it collapses. Your job this week is to find the load-bearing block and test *it first*.

### 2.1 Surface the assumptions

Write down everything that must be true for your idea to work. Don't filter yet. For Maya:

1. Clinics experience enough same-day cancellations for refill to matter.
2. Front-desk staff will adopt a new tool / hand off the task.
3. Waitlisted patients will respond fast enough to fill a same-day slot.
4. We can reach and sign up clinics affordably.
5. Clinics will pay for this.
6. We can technically integrate with their scheduling software.
7. Refilling slots actually improves the clinic's revenue noticeably.

That's seven. A real list is usually 8–15.

### 2.2 Score on two axes

Now score each assumption on two axes from 1 to 5:

- **Uncertainty** — how unsure are you that it's true? (5 = "honestly no idea." 1 = "near-certain.")
- **Fatality** — if it's false, how badly does it hurt? (5 = "the company is dead." 1 = "annoying, survivable.")

Multiply them. The highest product is your **riskiest assumption.**

| Assumption | Uncertainty | Fatality | Risk score |
|------------|:-----------:|:--------:|:----------:|
| Front desks will adopt / hand off the task | 5 | 5 | **25** |
| Patients respond fast enough to fill slots | 4 | 5 | 20 |
| Clinics will pay | 4 | 4 | 16 |
| We can reach clinics affordably | 3 | 4 | 12 |
| We can integrate with their scheduler | 2 | 3 | 6 |
| Clinics have enough cancellations | 2 | 5 | 10 |

Maya's top two (adoption, and patient response speed) can both be tested by the *same* concierge experiment, which is lucky and common: the riskiest assumptions often cluster.

### 2.3 The trap: testing the easy one

The single most common failure here is choosing the assumption that's *easiest to test* instead of the one that's *riskiest*. "Can we technically build it?" is comfortable to a builder, so builders test feasibility first and adoption never. But for most non-deep-tech ideas, **feasibility is rarely the riskiest assumption** — adoption and willingness-to-pay are. If you find yourself reaching for the technical assumption, stop and ask whether you're picking it because it's scary or because it's familiar.

> **Heuristic:** For consumer and SMB software in 2026, the order of risk is usually: *will they adopt it* > *will they pay* > *can we reach them* > *can we build it*. Deep-tech (biotech, hard hardware, novel ML) inverts the top and bottom — feasibility leads. Know which kind of company you are.

---

## 3. The five MVP archetypes (cheapest first)

Once you know your riskiest assumption, you match it to the cheapest MVP type that could falsify it. Here are the five, ordered roughly by cost and effort.

### 3.1 Smoke test / fake door

A landing page that describes the offer and has a **call-to-action button** — "Get started," "Buy now," "Join the beta." Behind the button is *nothing yet*: an email capture, a "we're launching soon" message, or a short survey.

- **Tests:** *interest and intent.* Will people click the thing that means "I want this"?
- **Metric:** click-through rate on the CTA; sometimes email-capture rate.
- **Cost:** an afternoon on Carrd or Framer, plus a little traffic.
- **When to use:** the riskiest assumption is "is there demand at all?" — you have a problem but no proof anyone will act on a solution.
- **Maya's version:** a one-page site for "AutoFill for Clinics — never lose a cancelled slot again. Book a demo," sent to 40 clinic managers. Measures whether the *pitch* lands before she builds.

### 3.2 Concierge

You deliver the service **manually, by hand**, to a few real customers, openly. No automation, no pretense — the customer knows you're doing it personally.

- **Tests:** *does the solution actually solve the problem,* and will people let you do it for them?
- **Metric:** completion / outcome (Maya: % of cancellations refilled), repeat usage, satisfaction tied to behavior.
- **Cost:** your time. That's the whole point — you're trading time for certainty.
- **When to use:** the riskiest assumption is "does our solution mechanism even work, and will people adopt it?" Concierge is the workhorse of this week.
- **Maya's version:** texting waitlisted patients herself for two clinics. This is the experiment she runs.

### 3.3 Wizard of Oz

The customer sees what *looks like* an automated product. Behind the curtain, **humans do the work**. Unlike concierge, the customer doesn't know it's manual.

- **Tests:** *demand for the experience* without building the expensive engine.
- **Metric:** usage of the "automated" product, retention, willingness to pay for it.
- **Cost:** a thin front end (a form, a chat, a simple page) plus your labor behind it.
- **When to use:** you believe the manual solution works (concierge passed) and now want to test whether people will use a productized version — before you spend months automating it.
- **Maya's version:** a simple dashboard clinics log into that *looks* like it auto-texts patients; in reality Maya gets a notification and sends the texts herself. Tests whether the product framing drives more adoption than the concierge framing.

### 3.4 Clickable prototype

A **Figma or slide click-through** — no real backend, just screens you can tap through.

- **Tests:** *comprehension and desirability of the flow.* Do people understand it? Do they want it? Where do they get lost?
- **Metric:** task completion in a moderated test, plus observed reactions ("would you use this every week?" tied to what they actually did, not just said).
- **Cost:** a day in Figma.
- **When to use:** the riskiest assumption is about the *interface or flow*, not demand — e.g., "will users understand a fundamentally new interaction?" Common for complex or novel UX.
- **Caution:** a prototype tests understanding, not real behavior. People are polite in usability tests. Don't read "they tapped through it fine" as "they'll pay."

### 3.5 Single-feature build (last resort)

You actually build *one* real feature — the core, nothing else.

- **Tests:** a genuinely **technical** riskiest assumption that cannot be faked: "can this ML model hit acceptable accuracy?", "can we sync these two systems in real time?"
- **Metric:** the technical result, plus early real usage.
- **Cost:** real engineering — the most expensive option, so it's the *last* resort.
- **When to use:** only when the riskiest assumption is feasibility and *no* fake, manual, or prototype version can answer it. If you can fake it, fake it.

### The decision rule

> **Match the type to the assumption, and always reach for the cheapest type that could actually falsify it.** If the risk is "will they adopt / will they pay," a fake door or concierge beats a build every time. Reserve building for risks that are truly technical.

| If your riskiest assumption is… | Cheapest MVP type |
|---|---|
| "Is there any demand?" | Fake door / smoke test |
| "Does our solution actually solve it?" | Concierge |
| "Will people use a productized version?" | Wizard of Oz |
| "Do people understand / want this flow?" | Clickable prototype |
| "Can we technically build the core at all?" | Single-feature build |

### 3.6 These aren't toy types — real companies started here

It's tempting to dismiss fake doors and concierge MVPs as exercises for a course. They're not. Several companies you know launched as exactly these archetypes, and the pattern is worth internalizing because it gives you permission to start small:

- **Dropbox** famously couldn't easily demo its file-sync magic before it was built, and the demand for "would anyone even want this" was the riskiest assumption. The early test was essentially a **fake door + explainer video**: a short walkthrough of the intended experience posted to a tech community, with a signup list. The waitlist jumped overnight — demand validated before the hard engineering was finished. The lesson: the riskiest assumption was *demand*, and a video tested it for the cost of a screen recording.
- **Zappos** (selling shoes online) began as a **Wizard of Oz / concierge**: the founder photographed shoes at local stores, posted them online, and — when someone ordered — went back, bought the pair at retail, and shipped it himself. He lost a little money per order on purpose. The riskiest assumption was "will people buy shoes online, sight-unfit?" He tested it without inventory, a warehouse, or logistics software.
- **Airbnb**'s earliest version was a **concierge** of one apartment: the founders rented out air mattresses in their own living room during a conference and hosted guests personally. They learned whether strangers would pay to sleep in a stranger's home before building any platform.
- Countless B2B SaaS tools ran a **concierge** first: the founder did the "software's" job in a spreadsheet for ten customers, by hand, every day, until they were certain the workflow was wanted — *then* they automated it.

The throughline: each company faced an *adoption or demand* risk, not a *feasibility* risk, and tested it with the cheapest possible experiment. None of them started by building the product. Your idea is not too special for this. If anything, the more novel your idea, the *more* you need a cheap test, because there's no benchmark telling you whether anyone wants it.

> **A caution about survivorship.** These are famous because they worked. For every Dropbox video there are thousands of fake doors that flopped — and that's the point. The flops were *cheap*. The founders learned "no" for the price of an afternoon and moved on. You're not trying to copy the winners' product; you're copying their *method*: test the scary thing cheaply, before you commit.

---

## 4. Write the experiment as a falsifiable hypothesis

An experiment you can't fail is theater. Before you build, write the test in a fixed shape so it *can* fail:

> **We believe** \[segment] **will** \[specific behavior] **because** \[reason].
> **We'll know we're right if** \[metric] **is at least** \[threshold] **by** \[date].
> **We'll know we're wrong if** \[metric] **is below** \[threshold].

Maya's:

> **We believe** small-clinic front desks **will hand off same-day cancellation refills to us** **because** the manual scramble is the worst part of their day.
> **We'll know we're right if** we refill **at least 30%** of same-day cancellations across **two clinics over one week.**
> **We'll know we're wrong if** we refill **under 30%.**

Notice four things this forces:

1. **A specific segment.** Not "people" — *small-clinic front desks.* Vague segments produce vague results.
2. **A behavior, not an opinion.** "Hand off refills," not "like the idea." Behavior is evidence; opinion is noise.
3. **A single metric.** Refill rate. Not three metrics you'll cherry-pick from on Friday.
4. **A threshold set in advance.** 30%, committed now. We'll spend all of Lecture 2 on why pre-committing the number is the difference between learning and lying to yourself.

If you can't fill in every bracket, you don't have an experiment yet. Go back to section 2 or 3 until you can.

---

## 5. The discipline of building *less*

The hardest skill this week is restraint. Everything that does not test your riskiest assumption is a distraction *this week*. You will build more later — once you know the core holds. Some rules that keep founders honest:

- **No feature that isn't load-bearing for the test.** Maya doesn't build logins, billing, or a settings page to test refill rate. She texts people.
- **Hardcode, fake, and hand-do everything you can.** "We'll automate it if it works" is the right instinct. A human behind a curtain is cheaper than code in front of one.
- **If your MVP takes more than a few days, you probably scoped a product.** Shrink it. Ask: "what's the version of this I could run by Thursday?"
- **Ugly is fine. Manual is fine. Embarrassing is fine.** Slow is the only failure — every extra week is a week you didn't learn.

> Reid Hoffman's line — "if you're not embarrassed by the first version of your product, you launched too late" — is about restraint, not sloppiness. The embarrassment comes from how *little* you built, not from bugs.

---

## 5.1 How to scope the MVP down to the bone

"Build less" is a slogan; here's the mechanical procedure. Take the full product in your head and run it through four cuts:

1. **Cut everything that isn't the riskiest assumption.** Write the one assumption at the top of a page. For every feature you're imagining, ask: "does this feature change whether I can answer that one question?" If no, it's out — this week. Maya's billing, logins, onboarding, settings, integrations: all out, because none of them tell her whether front desks will adopt.
2. **Replace the engine with a human.** Anywhere the product would "automatically" do something, ask whether *you* could do it by hand for the handful of customers in the test. Auto-texting patients → Maya texts them. Auto-matching → you match in a spreadsheet. Recommendation algorithm → you pick by hand. The human-behind-the-curtain version is almost always days, not weeks.
3. **Replace building with assembling.** Anything left that you *do* need, build from no-code blocks, not code: a Carrd page instead of a website, a Tally form instead of a signup flow, a Notion doc instead of a dashboard, a Stripe link instead of a billing system. The 2026 no-code stack can fake almost any front end in an afternoon.
4. **Set a hard time box.** "What's the version I could run by Thursday?" If the honest answer is "I can't," the experiment is still too big — cut more, or pick a cheaper MVP type (concierge instead of Wizard of Oz, fake door instead of concierge).

Run those four cuts and a "product" that felt like a two-month build collapses into a two-day experiment. That collapse is the skill. A founder who can't scope down will spend their whole runway building things they never needed to build.

> **The fidelity ladder.** When in doubt, start one rung lower than feels right: *fake door → concierge → Wizard of Oz → prototype → single-feature build.* You can always climb up next week once a risk is retired. You can never get back the weeks you spent building a rung too high.

---

## 6. Ethics and honesty (read this before you fake a door)

Fake doors and Wizard-of-Oz MVPs work because they let people act on something that doesn't fully exist yet. That power comes with three rules:

1. **Don't take money you can't honor.** Measuring willingness-to-pay with a real checkout (a Stripe payment link) is the gold-standard signal — but if you collect a payment, you must either deliver or refund immediately. "Charge and ghost" is fraud, not a lean experiment.
2. **Be honest after the click.** A fake door's CTA can advertise a thing that doesn't exist yet. What it *can't* do is lie about what happens next. "Coming soon — join the waitlist" after the click is honest. A fake "success! your order is confirmed" for an order that will never ship is not.
3. **Protect any data you collect.** If you capture emails, you owe people basic transparency (why you have it) and a way to be forgotten. Don't collect personal data you can't store responsibly — and for a one-week test, you usually need far less than you think.

The bar: *would you be comfortable if the customer learned exactly what you did?* If yes, run it. If no, redesign the experiment.

---

## 7. Sequencing: de-risk in the right order

You have more than one risky assumption. You test them **in order of risk**, cheapest test first, because each result changes what's worth testing next. If Maya's adoption test fails, there's no point testing whether clinics will pay — the company's dead in its current form, and she should pivot. If it passes, *then* willingness-to-pay becomes the next experiment.

This is why founders who move fast aren't building faster — they're **running the loop faster**, retiring the scariest risk first so they fail (or commit) early. A common pattern:

1. **Fake door** → is there demand? (days)
2. **Concierge** → does the solution work and will they adopt? (one week)
3. **Wizard of Oz** → will they use a product version, and pay? (two weeks)
4. **Single-feature build** → only now, with three risks retired, do you write real code.

You will run step 2 (or step 1) this week. Steps 3–4 are future weeks and future cycles.

---

## 7.1 A pre-launch checklist

Before you let a single real person touch your MVP, walk this list. Each item is a place founders routinely waste a week.

- [ ] **One riskiest assumption named.** Not two, not "the whole idea." One, scored highest on uncertainty × fatality.
- [ ] **The cheapest MVP type chosen** that could actually *falsify* it — and you can say in one sentence why nothing cheaper would work.
- [ ] **A falsifiable hypothesis written**, every bracket filled, with a "we'll know we're wrong if" clause.
- [ ] **Exactly one metric**, and it's a *deed* not a *word*, a *rate or cohort* not a cumulative total.
- [ ] **A threshold committed in writing** (and ideally in your git history) *before* launch.
- [ ] **The build is days, not weeks**, and near-zero cost — you ran the four scoping cuts.
- [ ] **Measurement is set up and tested** — you clicked your own CTA / added a test row / ran a test charge and saw it land.
- [ ] **The real segment is lined up**, through a named channel — friends, family, and cohort-mates are *excluded* from the metric.
- [ ] **The three ethics checks pass** — you can deliver or refund any money, nothing lies about what happens next, and you can protect any data you collect.

If every box is ticked, launch. If not, the unticked box is exactly where your week would otherwise have gone sideways.

---

## 8. Common mistakes to avoid

- **Building when you could fake.** The default failure. If you can test it by hand, test it by hand.
- **Testing the easy assumption.** Feasibility is comfortable; adoption is scary. Test the scary one.
- **No threshold, or a movable one.** Without a number set in advance, every result becomes a "win." (Lecture 2.)
- **Measuring words, not deeds.** "People said they loved it" is not a result. "12 of 40 clicked Buy" is.
- **One MVP, ten metrics.** Pick the one metric that maps to the assumption. The rest are noise you'll cherry-pick.
- **Polishing.** Time spent making the MVP pretty is time not spent learning. Ugly and live beats beautiful and unlaunched.
- **Running it on friends.** Friends are kind and unrepresentative. Run it on the actual segment.

---

## 9. A second worked example — a fake door, not a concierge

Maya's case is a concierge because her risk is "will they adopt and does it work." A different shape of risk wants a different MVP, so here's a contrasting example to keep you from defaulting to one type.

**Devon** is building a tool that turns a freelancer's messy project notes into a clean client-ready status update. His Week 3 interviews found freelancers *complaining* about status-update busywork — but complaining about a chore is not the same as being willing to adopt a new tool, or pay for it. Devon's assumption stack:

| Assumption | Uncertainty | Fatality | Risk |
|---|:-:|:-:|:-:|
| Freelancers will pay for an automated status-update tool | 5 | 5 | **25** |
| The tool can produce updates good enough to send a client | 3 | 5 | 15 |
| We can reach freelancers cheaply | 3 | 4 | 12 |

His riskiest assumption is **willingness to pay**, and the demand is unproven — no one has acted, they've only griped. The cheapest falsifying test is **not** a concierge (that tests efficacy, which he's less worried about) and **not** a build. It's a **fake door with a price**:

- A one-page site: "Stop writing status updates. We turn your notes into client-ready updates. $19/mo — start free trial."
- The "start" button leads to "We're onboarding in batches — leave your email and we'll set you up this week."
- He drives ~250 freelancers to it via two niche communities and a small ad.

His hypothesis: *We believe freelancers will sign up for a paid status-update tool because the busywork is hated; we'll know we're right if ≥6% of visitors click "start free trial" and leave an email; wrong if below 6%.*

If it converts at 9%, Devon perseveres — *then* he runs a concierge to test whether he can actually produce good-enough updates by hand before automating. If it converts at 1%, the "they hate the chore" complaints didn't translate into intent, and he pivots (maybe the segment is agencies, not solo freelancers; maybe the need is different). Notice: **same week, same budget, different MVP type — because the risk was different.** Always start from the risk, not from the MVP type you find most fun.

---

## 10. Recap

You should now be able to:

- State the difference between an MVP-as-experiment and an MVP-as-tiny-product, and why it decides the week.
- Surface your idea's assumptions and score them on uncertainty × fatality to find the riskiest one.
- Pick the cheapest MVP archetype (fake door, concierge, Wizard of Oz, prototype, single-feature) that could falsify it.
- Write the test as a falsifiable hypothesis with a single metric and a pre-committed threshold.
- Keep the build deliberately small and honest, and sequence your experiments by risk.

Here is the whole lecture in one table — the spine of everything you'll do this week:

| Step | Question it answers | Output |
|---|---|---|
| Surface assumptions | "What must be true for this to work?" | A list of 8+ beliefs |
| Score (uncertainty × fatality) | "Which belief is load-bearing?" | The riskiest assumption |
| Match MVP type | "What's the cheapest falsifying test?" | Fake door / concierge / WoZ / prototype / build |
| Write the hypothesis | "How would I know if I'm wrong?" | A falsifiable statement + one metric |
| Set the threshold | "What number changes my mind?" | A pre-committed success bar |
| Scope to the bone | "What could I run by Thursday?" | A 2–3 day, near-zero-cost build |

If any cell is blank, that's the work that's left before you launch.

Next up: how to run the loop, pick one honest metric, and turn the result into a persevere-or-pivot decision. Continue to [Lecture 2 — Build-Measure-Learn](./02-build-measure-learn.md).

---

## References

- *An MVP is not a Cheaper Product, It's about Smart Learning* — Steve Blank: <https://steveblank.com/2013/07/22/an-mvp-is-not-a-cheaper-product-its-about-smart-learning/>
- *Do Things That Don't Scale* — Paul Graham: <https://paulgraham.com/ds.html>
- *Minimum viable product* — Wikipedia: <https://en.wikipedia.org/wiki/Minimum_viable_product>
- *Lean startup* — Wikipedia: <https://en.wikipedia.org/wiki/Lean_startup>
- *How to Talk to Users* — Y Combinator: <https://www.ycombinator.com/library/6g-how-to-talk-to-users>
- *Test Cards & Learning Cards* — Strategyzer library: <https://www.strategyzer.com/library>
