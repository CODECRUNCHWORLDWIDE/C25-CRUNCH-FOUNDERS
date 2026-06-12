# Lecture 2 — Triage and Desk Validation

> **Duration:** ~2 hours of reading + hands-on with the free tools.
> **Outcome:** You can score a shortlist of ideas against a five-axis filter without inflating the numbers, run free desk validation on the top candidates in under an hour each, read a search-demand or competitor signal honestly, and write falsifiable kill criteria before you talk to a single customer.

Lecture 1 gave you a shortlist: 5–10 painkiller problems where you have standing. This lecture is the machinery that turns that shortlist into **one** committed idea with evidence behind it.

If you remember one sentence:

> **You cannot validate an idea from your desk — only interviews do that — but you can cheaply *kill* the obvious losers and rank the survivors, and you should, before you spend a single interview on a dud.**

---

## 1. The triage filter

Score each candidate on five axes, 1–5, and sum to a total out of 25. The axes are not arbitrary — each one maps to a way ideas commonly die.

| Axis | Question it answers | A "1" looks like | A "5" looks like |
|------|---------------------|------------------|------------------|
| **Painkiller-ness** | Is the pain urgent and costly? | Mild "nice to have," no urgency | People hack workarounds *today* under pressure |
| **Frequency** | How often does it bite? | Once a year | Daily or weekly |
| **Standing** | Why you, why now? | No access, no experience | You lived it; warm contacts in hand |
| **Reachability** | Can you find these people cheaply? | No idea where they are | A list you can message *this week* |
| **Pay signal** | Is anyone already paying to fix it? | No evidence anyone acts on it | Existing paid workarounds, even bad ones |

Read the axes as a set of independent failure modes:

- A **low painkiller-ness** score means you've found a vitamin. Vitamins don't get bought under pressure; they get ignored when budgets tighten.
- A **low frequency** score means even if the pain is real, you'll struggle to build a habit or a recurring-revenue business around something that happens once a year.
- A **low standing** score means *someone* should build this, but probably not you — you can't speak the customer's language or open the doors.
- A **low reachability** score is the silent killer. A 5-painkiller problem you can't reach scores like a dud *for you*, because you literally cannot run discovery.
- A **low pay signal** means the market hasn't priced this pain. Could mean "too mild" or "genuinely unserved" — only interviews resolve which, so a low pay signal raises your interview burden.

### Scoring rubric (so a "4" means the same thing every time)

| Score | Painkiller | Frequency | Standing | Reachability | Pay signal |
|------:|-----------|-----------|----------|--------------|------------|
| **5** | Workarounds today, under pressure | Daily | Lived it + warm list | Can message 10+ this week | Paid tools exist, people switch for better |
| **4** | Clear cost, acted on | Weekly | Worked adjacent + some contacts | Know exactly where they gather | Paid tools exist, sticky |
| **3** | Real but tolerated | Monthly | Understand the domain | Findable with effort | People spend *hours* (not $) on it |
| **2** | Mild annoyance | Quarterly | Outsider with interest | Vague idea where they are | Occasional ad-hoc spend |
| **1** | Nice-to-have | Yearly or less | No access | No idea | No evidence anyone acts |

A candidate that scores **20+ and is reachable** is worth interviewing. One in the low teens is usually a vitamin, a space you lack standing in, or both.

### A column of all-5s is a bug, not a win

The single most common way founders cheat this filter is by inflating every score. If your top idea scores 25/25, you are not being honest — you are scoring the idea you wish you had. Real painkiller problems have a soft spot somewhere: the pay signal is unproven, or reachability is harder than you'd like, or frequency is monthly not daily. **Find the soft spot and score it honestly.** The filter only protects you if the numbers mean something.

> **Maya's scoring.** Clinic no-shows: painkiller 5 (revenue, urgent), frequency 5 (daily gaps), standing 5 (front desk for 3 years), reachability 4 (knows ~20 office managers, not 100), pay signal 4 (clinics pay for clumsy SMS tools but rarely switch). Total **23/25** — and she could name *why* reachability and pay signal weren't 5s. That honesty is what makes 23 believable.

---

## 2. Desk validation — what you can learn for free, before any interview

Desk validation is everything you can find out from a browser without talking to anyone. It's cheap, it's fast (target under an hour per idea), and it does one job well: **killing obvious losers and sharpening the survivors before you spend scarce interviews.** It will never *confirm* an idea — that's Week 3's job — but it routinely saves you from interviewing a dud.

Run these four passes on each of your top two candidates.

### Pass 1 — Search demand

Are people actively searching for this problem, or for workarounds?

- **Google Trends** (<https://trends.google.com/trends/>) — relative demand over time. Don't read the absolute number; read the **slope** (rising, flat, declining) and **seasonality**. Compare two related terms to calibrate.
- **Search autocomplete** — type your problem into Google and read what it suggests. Those suggestions are real, high-frequency queries. The pain, in the customer's own words.
- **"People also ask" and "People also search for"** — the question cluster around your topic is a free map of what's actually on people's minds.
- **Answer the Public** (<https://answerthepublic.com/>) — visualizes the question-phrases around a keyword.

> **2026 caveat.** Search engines now answer many informational queries with an AI summary box, which deflects clicks and can flatten Trends for purely informational terms. Read Trends as *directional*, and weight forum/Reddit evidence (where people describe pain in their own words) more heavily than you would have a few years ago.

### Pass 2 — Existing alternatives (the real benchmark)

The question is never "is there a competitor?" It's **"what does someone with this problem do *today*?"** The honest answer is one of:

- **A direct competitor** — another product solving it. Good: validates the market exists. Now you need a wedge (Pass 4 of the reviews tells you where they're weak).
- **A spreadsheet** — the most common and most encouraging "competitor." If people maintain a hand-built spreadsheet to cope, the pain is real and unserved by a real product. Maya's color-coded cancellation sheet is exactly this.
- **An intern / a VA / a manual process** — people are throwing *labor* at it. Expensive workaround = strong signal.
- **Duct tape** — a chain of three tools and a Slack reminder. Fragile workarounds reveal exactly where a product should sit.
- **Nothing** — the dangerous one. "Nothing" means either the pain is too mild to act on (kill) or the market is genuinely unserved (rare, valuable — but confirm with interviews, never assume).

Name the alternatives specifically, with links. "There are some competitors" is not validation; "Curogram and NexHealth both do reminders but neither auto-fills a canceled slot from a waitlist" is.

### Pass 3 — Willingness-to-pay signal

Rank what you find, weakest to strongest:

1. Someone said the idea "sounds cool." *(Weakest. Worthless, actually.)*
2. People discuss the problem online but do nothing about it.
3. People spend **hours** on a manual workaround.
4. People pay for an **adjacent** tool that half-solves it.
5. People pay for a **clumsy, directly-aimed** tool and complain about it. *(Strongest. The market has priced the pain and is unhappy with the price-to-value.)*

The strongest desk signal is an existing paid tool with bad reviews — proof of both demand and dissatisfaction. Pricing pages are free; read them. App-store and G2/Capterra reviews are free; the 1- and 2-star ones are a gift-wrapped list of unmet needs.

### Pass 4 — Read the incumbents' reviews

Go to the App Store, Google Play, G2, Capterra, or Trustpilot for whatever tool is the current alternative. **Sort by lowest rating.** Read 20 critical reviews. You are looking for:

- Recurring complaints (your wedge).
- Features people beg for and don't get (unmet demand).
- "I switched away because…" (churn drivers = your opening).
- "I pay $X and it still doesn't…" (willingness-to-pay confirmed + dissatisfaction).

Twenty critical reviews of an incumbent will teach you more about a market in 20 minutes than a week of brainstorming.

---

## 3. Reading signals honestly (the traps)

Desk validation is only useful if you read it without flinching. Three traps catch nearly everyone.

### The "no competitors" trap

New founders see an empty field and think *goldmine*. Far more often, an empty field means **no money grows there.** Markets are efficient enough that a genuinely valuable, reachable problem usually has *someone* taking a swing at it. So when you find no competitors, your default hypothesis should be "there's no market here," and you have to actively disprove it — usually by finding the expensive manual workaround that proves the pain exists but hasn't been productized yet. "No competitors" is a question, not an answer.

### The flat-Trends trap

A flat or declining Google Trends line feels like a death sentence. It isn't always. The term might be niche (low absolute volume, but the people who search it are desperate), or the pain might be one people don't *search* for because they don't know a solution could exist (you can't search for what you can't imagine). Cross-check Trends against forum chatter and paid-tool existence before you let a flat line kill an idea.

### The vanity-signal trap

Likes, "this is awesome" comments, newsletter sign-ups, and survey "yes I'd use that" answers are **vanity signals.** They cost the respondent nothing and predict behavior badly. People are generous with encouragement and stingy with money and time. Weight the costly signals (paid tools, manual labor, hours spent) and discount the free ones. This is the desk-validation version of the Week 3 rule: ask about the *past* (what they actually did), not the *future* (what they say they'd do).

> **Rule of thumb.** If a signal cost the person nothing to produce, it's worth nothing. If it cost them money, time, or labor, it's worth a lot.

---

## 4. Kill criteria — decide what would end it, now

Here is the discipline that separates founders who learn from founders who fool themselves. **Before** you get attached, before a single interview, write down the specific, falsifiable, numeric evidence that would make you *drop* the idea.

Why before? Because once you're attached and have sunk a week into interviews, you will hear "yes" in every "maybe." Confirmation bias is not a character flaw you can will away — it's how human cognition works. The only reliable defense is to pre-commit to a threshold while you're still neutral.

### What a good kill criterion looks like

A kill criterion is **specific** (names a number or a clear condition), **falsifiable** (an outcome could prove it true or false), and **decided in advance** (written before the data arrives).

| Bad (vague) | Good (falsifiable, numeric) |
|-------------|------------------------------|
| "If it seems like a bad idea." | "If fewer than 5 of 10 interviewees describe this as a recurring, costly pain, I drop it." |
| "If people aren't interested." | "If nobody can point to a current workaround they actively use, I drop it." |
| "If the market's too small." | "If I can't find 10 reachable target customers in 2 weeks, I drop it." |
| "If competitors are too strong." | "If every interviewee is satisfied with their current tool and can't name a complaint, I drop it." |

### Write three to five

For your committed idea, write three to five kill criteria. Cover at least:

- **Problem reality** — a threshold on how many interviewees confirm it's a real, recurring, costly pain.
- **Workaround existence** — whether people actually do something about it today.
- **Reachability** — whether you can assemble the discovery sample at all.
- **Dissatisfaction** — whether the current solution is actually painful or merely present.

These become the contract you carry into Week 3. When you've done your ten interviews, you check the results against these pre-written thresholds and you *honor the outcome* — including dropping an idea you've grown to love. That's the whole point.

---

## 4b. A worked desk-validation pass (so you know what "good" looks like)

Reading the four passes in the abstract is one thing; here is what an hour of honest desk work actually produces. This is Maya's clinic-no-show idea, run end to end. Use it as a template for *depth*, not for content — your idea will look nothing like this.

**Pass 1 — Search demand.** Google Trends for "patient no-show" is low-volume but flat-to-rising over five years, with a clear seasonal dip in summer. The more telling signal isn't Trends at all — it's autocomplete: typing "reduce patient no" suggests "reduce patient no-shows," "...no-show rate," "...no-show policy," "...no-show fee." Those are practice managers searching for *operational fixes*, in their own words. "People also ask" surfaces "What is a good no-show rate?" and "How much do no-shows cost a practice?" — the second is a willingness-to-pay tell hiding in a search query. **Read:** demand is real but informational; people are looking for *how to fix it*, which is exactly the buyer mindset, not idle curiosity.

**Pass 2 — Existing alternatives.** Named, with links, typed:

| Alternative | Type | Note |
|-------------|------|------|
| Curogram, Weave, NexHealth | direct competitors | Send SMS/email reminders; reduce *some* no-shows but don't auto-fill a slot that's already empty |
| Front-desk spreadsheet | spreadsheet | The office manager hand-tracks no-shows and keeps a manual call list — Maya rebuilt this weekly for three years |
| "Call the waitlist" | intern/VA labor | Staff phone patients one by one when a slot opens; slow, often too late to fill |
| Overbooking | duct-tape process | Some clinics double-book to absorb no-shows, creating wait-room anger |

The pattern is unmistakable: reminders are productized, but **filling the gap a no-show creates is still done by hand or not at all.** That's the wedge.

**Pass 3 — Willingness-to-pay.** Clinics already pay roughly $200–400/month for reminder tools (Curogram's and Weave's pricing pages are public). That's a strong pay signal *for reminders*. The open question is whether they'd pay more for auto-fill — desk validation can't answer that, but the existing spend proves the budget line exists.

**Pass 4 — Incumbent reviews.** Sorting Curogram and Weave reviews on G2/Capterra lowest-first surfaces recurring complaints: "reminders cut some no-shows but we still have empty chairs we can't fill fast enough," "wish it would automatically offer the open slot to someone on the waitlist," "still calling patients manually when something opens up." That last cluster is gift-wrapped: the incumbents' own unhappy customers are describing Maya's product.

**Verdict.** Stronger than the triage score suggested. Reminders are solved; *recovery of the lost slot* is not, and the market already pays for the adjacent thing and complains in reviews about the exact gap. New estimate: 24/25. What desk work *can't* tell her, and so goes straight to Week 3 interviews: **would an office manager trust an automated waitlist-fill, or insist on calling patients themselves?** That trust question is the make-or-break, and only a human conversation answers it.

Notice what made this good: every alternative is *named and linked*, the pay signal is a *real dollar figure from a real pricing page*, the wedge comes from *actual review language*, and the verdict ends by naming the one thing desk work couldn't resolve. That last move — handing a sharp question to Week 3 — is the whole point of desk validation.

---

## 4c. Sizing, lightly (you'll do it for real in Week 6)

You are not building a TAM/SAM/SOM model this week — that's Week 6 — but desk validation should leave you with a *rough* sense of whether the market is big enough to matter, because an idea that passes every other test but serves 400 people worldwide is a lifestyle business, not a venture (which is fine, if that's what you want — just decide it on purpose).

A back-of-envelope sanity check, in three lines:

- **How many of these customers exist?** (Census data, industry-association member counts, "number of X businesses in the country" searches are all free.)
- **What might one pay per year?** (Anchored to what they already pay for the adjacent tool from Pass 3.)
- **Multiply.** If the honest product is "10,000 reachable customers × $3,000/year," that's a $30M ceiling — a real business, possibly a venture-scale one. If it's "400 customers × $200/year," that's $80K — know that now, not after you quit your job.

Don't over-engineer this. One paragraph. The point is to catch the idea that's wonderful and tiny *before* you commit, and to write down the assumption so Week 6 can pressure-test it. A flat "I'll figure out the market later" is how founders end up two years into a beautiful product with no possible path to a real outcome.

> **2026 note on AI-era markets.** When the solution is "AI does X," the market-size story is often borrowed from a McKinsey "AI will add $4T to GDP" headline. That number is not your market. Your market is the specific set of customers with the specific painful workflow you can reach and bill. Size *that*, not the macro headline.

---

## 5. Choose one

The lecture ends where the mini-project begins: you pick the single highest-scoring, reachable, kill-criteria-armed idea and carry **one** into Week 3.

Not three. Not "I'll keep two warm as a hedge." **One.**

Carrying three ideas into discovery means doing none of them justice. You have a finite number of interviews in you (energy, contacts, time). Spreading them across three ideas gives you three under-powered, inconclusive read-outs instead of one decisive one. The hedge feels safe but it's the opposite — it guarantees you learn nothing clearly.

How to choose when two are close:

1. **Reachability breaks ties.** If two ideas score similarly, pick the one you can interview *this week*. Momentum compounds; access is the constraint.
2. **Standing breaks the next tie.** The one where your founder-market fit is stronger will produce sharper interviews and a more defensible capstone.
3. **The pay signal breaks the last tie.** All else equal, take the one where the market has already shown it'll spend.

Then park the others honestly. The parking lot isn't a graveyard — a parked idea can come back when your standing or the market changes. But it doesn't come to Week 3 with you.

> **Maya commits.** Clinic no-shows (23/25) over her second-place idea (a scheduling tool for tutors, 18/25). Tie-break wasn't needed — but even if it had been, the clinic idea wins on standing (3 years front-desk) and reachability (20 warm office managers). She writes four kill criteria, names five interview targets by role (office manager, practice owner, front-desk lead, billing coordinator, a multi-location operations manager), and carries exactly one idea into Week 3.

---

## 5b. Why this is so hard: the psychology you're fighting

Everything in this lecture is technically simple — score five things, do some Googling, write down some thresholds. So why do experienced, intelligent founders get it wrong constantly? Because the difficulty isn't analytical, it's *emotional*, and naming the specific cognitive traps is the only way to beat them.

**The endowment effect.** The moment an idea is *yours*, you value it more than an identical idea that isn't. This is measurable and universal — people demand more to give up a mug they were handed five minutes ago than they'd pay to buy it. Your idea is the mug. You'll defend it past the point the evidence warrants simply because it's yours. The triage filter and kill criteria exist to put a number between you and the mug.

**Confirmation bias in discovery.** Once you have a hypothesis you like, you unconsciously ask questions that confirm it and discount answers that don't. "You'd use this, right?" gets a polite yes, and you log it as validation. This is why Week 3 bans pitching and why this week makes you write kill criteria *before* you're attached — the only reliable defense against confirmation bias is a pre-committed threshold you set while still neutral.

**Sunk-cost escalation.** The more time you've invested, the harder it is to quit, even as the evidence worsens. A founder three months into building will reinterpret a string of "no"s as "they just don't get it yet." The defense is to keep the sunk cost *small* until the problem is validated — which is exactly why this week is desk research and Week 3 is conversations, not building. You can walk away from an idea you've spent six hours on. You cannot easily walk away from one you've spent six months on.

**Social-desirability bias in your sources.** People are nice. They give encouragement freely because it's cheap and pleasant, and they withhold criticism because it's awkward. Every "that sounds cool," every "I'd totally use that," every supportive comment is contaminated by the respondent's desire to be kind. This is the root of the vanity-signal trap (§3): free, kind signals predict nothing. Costly signals — money, hours, an angry review someone bothered to write — are the ones that survived the niceness filter.

The whole machinery of this week — honest scoring, costly-signal weighting, pre-committed kill criteria, one idea not three — is engineered against these four biases. You can't will them away; they're how cognition works. You can only build process that doesn't trust your in-the-moment judgment. That's what a kill criterion *is*: a promise your neutral self makes to bind your future, attached self.

---

## 5c. Reading a competitive landscape like a founder, not a fan

When you find competitors (the common case), the amateur move is to either panic ("it's taken, kill it") or dismiss them ("ours will just be better"). Both are lazy. The founder move is to map the landscape and find the *wedge* — the specific, defensible slice where the incumbents are weak.

Build a quick competitor table during desk validation. For each real alternative, capture:

| Column | What you're looking for |
|--------|--------------------------|
| **Who they serve** | Their actual customer — often broader or narrower than they claim |
| **What they charge** | From the public pricing page; anchors your own pricing later |
| **Their wedge** | The one thing they're great at (so you don't fight them there) |
| **Their weak spot** | The recurring complaint in their reviews (your opening) |
| **Why they won't fix it** | Structural reasons — wrong customer, wrong incentive, too big to care about your slice |

That last column is the most important and the most overlooked. An incumbent leaves a gap unfixed for *reasons*, and understanding the reason tells you whether your wedge is durable or whether they'll close it the moment you prove it matters. Common durable reasons:

- **Wrong customer.** The incumbent serves enterprise; your slice is too small for their sales motion to bother with.
- **Cannibalization.** Fixing it would undercut a more profitable part of their business.
- **Architecture lock-in.** It's a deep rebuild they can't justify.
- **They literally can't see it.** Their customer base doesn't include your slice, so they never hear the complaint.

If the answer is "no structural reason — they'd just bolt it on next quarter," you may be looking at a **feature, not a company**, and you should know that now. If the answer is "they structurally can't or won't serve my slice," you have a real wedge.

> Maya's wedge holds up: the reminder incumbents serve a broad market and reminders are their whole product; auto-filling a canceled slot from a waitlist is a different motion (it touches the patient *and* the scheduling logic), and the small-clinic slice that feels the no-show pain most acutely is below the radar of the enterprise-priced players. The gap isn't an oversight they'll patch on Tuesday — it's structurally adjacent to what they do.

This competitive map is also the seed of your Week 10 pitch's "why us / why this wins" slide. Build it once now, honestly, and you'll reuse it for eight weeks.

---

## 6. Putting it together — the week's flow

```
15+ problems (L1, Ex1)
        │  first cut: painkiller vs vitamin
        ▼
5–10 shortlist with standing
        │  five-axis triage scoring, honest (L2 §1, Ex2)
        ▼
Top 2 candidates
        │  desk validation: demand, alternatives, pay signal, reviews (L2 §2–3, Ex3)
        ▼
1 committed idea
        │  kill criteria written before interviews (L2 §4)
        │  5 interview targets named by role
        ▼
Carry ONE into Week 3 discovery
```

That pipeline is the mini-project. Everything in this lecture feeds it.

---

## 6b. The one-hour desk-validation runbook

When you sit down to validate an idea, you don't want to improvise — you want a checklist you can run in under an hour. Print this, or keep it open in a tab.

| Min | Step | What you're capturing |
|----:|------|------------------------|
| 0–5 | Write the problem as **who + pain**, no solution | The thing you're validating |
| 5–15 | Google Trends (slope, seasonality) + autocomplete + "people also ask" | Demand shape, the pain in customers' words |
| 15–30 | `site:reddit.com` and forum search for the pain | Unprompted complaints; are people venting about this? |
| 30–45 | Name every existing alternative, typed and linked | The real benchmark: competitor / spreadsheet / labor / duct-tape / nothing |
| 45–55 | Pull competitor pricing pages + sort reviews lowest-first | Pay signal (real $) + the wedge (recurring complaints) |
| 55–60 | Write the verdict + the one question only interviews answer | Stronger/weaker, revised score, the Week 3 handoff |

If at minute 30 you've found no demand, no complaints, no alternatives, and no spend — that's not "keep digging," that's a kill or a strong "this is too mild / too unserved to bet on without a hard reachability check." The runbook is also a *time-box*: an hour, then a decision. Founders who let desk validation sprawl into days are usually procrastinating on the scary part — talking to humans in Week 3.

> **What desk validation can never do.** It cannot confirm an idea, it cannot tell you whether someone will *actually* switch and pay, and it cannot surface the problem you didn't know to search for. Only interviews do those. Desk validation's entire job is to make sure the interviews you run in Week 3 are pointed at a survivor, not a dud. Treat it as a filter, never as a verdict.

---

## 7. Recap

You should now be able to:

- Score a shortlist on the five-axis filter (painkiller, frequency, standing, reachability, pay signal) with a rubric so a "4" means the same thing each time.
- Recognize that a column of all-5s is dishonest, and find each idea's real soft spot.
- Run four desk-validation passes — demand, alternatives, pay signal, reviews — in under an hour per idea, using only free tools.
- Read signals honestly, dodging the no-competitors trap, the flat-Trends trap, and the vanity-signal trap.
- Write three to five specific, falsifiable, numeric kill criteria *before* interviewing.
- Commit to exactly one idea and explain the tie-breaks if it was close.

Next, the [exercises](../exercises/README.md) walk you through generating the inventory, scoring it, and running the desk-validation canvas. Then the [mini-project](../mini-project/README.md) assembles all of it into the idea-triage log you carry into Week 3.

---

## References

- *How to Get Startup Ideas* — Paul Graham: <https://www.paulgraham.com/startupideas.html>
- *Lean startup* — Wikipedia: <https://en.wikipedia.org/wiki/Lean_startup>
- *Market research* — Wikipedia: <https://en.wikipedia.org/wiki/Market_research>
- *Google Trends*: <https://trends.google.com/trends/>
- *Y Combinator Startup Library* (validation track): <https://www.ycombinator.com/library>
