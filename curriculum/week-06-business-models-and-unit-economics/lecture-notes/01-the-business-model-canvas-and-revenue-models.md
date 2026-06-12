# Lecture 1 — The Business Model Canvas and Revenue Models

> **Duration:** ~2 hours of reading + a live "Canvas in 20" exercise.
> **Outcome:** You can fill a lean canvas for your concept, name the difference between a business model, a revenue model, and a pricing model, choose a revenue model that fits your customer, and set a first price using value-based reasoning instead of cost-plus guessing.

If you remember one thing from this lecture, remember this:

> **A business model is a hypothesis about how value gets created, delivered, and captured — and like any hypothesis, most of it is wrong on the first draft. The canvas exists to make the wrong parts visible and cheap to test, not to look impressive in a deck.**

You have spent five weeks earning the right to ask the money question. You have discovery interviews that say the problem is real. You have an MVP that says someone will use a solution. None of that tells you whether there is a *business* here. Plenty of products people love have no business underneath them — the math of serving the customer never closes. This lecture builds the one-page map. Lecture 2 does the arithmetic that decides whether the map leads anywhere.

---

## 1. Three things founders collapse into one word

Founders say "business model" to mean three different things. Untangling them is half the battle, because each is a different decision with different stakes.

| Layer | Question it answers | Example (Maya's clinic SaaS) |
|-------|--------------------|------------------------------|
| **Business model** | How does the *whole thing* create, deliver, and capture value? | "Software that fills dental cancellation slots, sold to clinic owners, delivered as a web app, paid for monthly." |
| **Revenue model** | *How* do we charge? | Subscription (vs. take-rate per filled slot, vs. usage). |
| **Pricing model** | What are the actual numbers and structure? | $99/month flat per clinic (vs. $49 + $2/filled slot). |

The business model is the nine-box canvas — the territory. The revenue model is one box inside it (Revenue Streams), but it's the box that most determines whether the unit economics in Lecture 2 work. The pricing model is the specific dial setting. You can keep the same business model and completely change its viability by switching revenue models — Maya's clinic product is a different *business* if she charges per filled slot than if she charges a flat subscription, even though the software is identical.

**Why this matters now:** in your discovery work you validated a *problem*. This week you're choosing among several possible *businesses* you could build on that one validated problem. The canvas is how you lay the candidates side by side.

---

## 2. Two canvases: Osterwalder's and Maurya's

There are two famous one-page canvases, and you will hear both names.

**The Business Model Canvas (Alexander Osterwalder, 2010)** has nine blocks: Customer Segments, Value Propositions, Channels, Customer Relationships, Revenue Streams, Key Resources, Key Activities, Key Partnerships, Cost Structure. It was designed to describe *any* business — a corner bakery, an airline, a SaaS — so it leans toward operations and partnerships.

**The Lean Canvas (Ash Maurya, 2012)** adapts Osterwalder's for *early-stage startups*. It keeps the one-page format but swaps four blocks that don't matter yet (Key Resources, Key Activities, Key Partnerships, Customer Relationships) for four that matter enormously when you're pre-product-market-fit: **Problem, Solution, Key Metrics, and Unfair Advantage.**

We use the **Lean Canvas** in C25. Here's why, concretely: at your stage, "key partnerships" is a fantasy box (you have no leverage to partner with anyone yet), but "what is the top problem, and what's my unfair advantage in solving it" is the entire game. Maurya designed his canvas for exactly the person you are this week — someone with an unvalidated business resting on a validated problem.

The nine Lean Canvas blocks, in the order you fill them:

```
┌─────────────────┬─────────────────┬─────────────────┬─────────────────┬─────────────────┐
│  1. PROBLEM     │  4. SOLUTION    │  3. UNIQUE       │  9. UNFAIR       │  2. CUSTOMER    │
│                 │                 │     VALUE        │     ADVANTAGE    │     SEGMENTS    │
│  Top 1-3        │  Top 1-3        │     PROP.        │                  │                 │
│  problems       │  features       │                 │  Can't be        │  Target users   │
│                 ├─────────────────┤  Single, clear, │  copied/bought   │  & customers    │
│  Existing       │  8. KEY         │  compelling      ├─────────────────┤                 │
│  alternatives   │     METRICS     │  message        │  5. CHANNELS     │  Early adopters │
│                 │                 │                 │                  │                 │
├─────────────────┴─────────────────┴─────────────────┴─────────────────┴─────────────────┤
│  7. COST STRUCTURE                          │  6. REVENUE STREAMS                         │
│  Customer acquisition, hosting, people…     │  Revenue model, pricing, LTV…               │
└─────────────────────────────────────────────┴─────────────────────────────────────────────┘
```

Fill order matters: **Problem and Customer Segments first** (1, 2), because everything else is downstream of *who* and *what hurts*. Then Unique Value Proposition (3) — the bridge between problem and solution. Then Solution (4). Then the delivery and money blocks. We do Unfair Advantage (9) last because it's the hardest and most honest box, and you'll write better nonsense early and better truth late.

---

## 3. The nine blocks, one at a time

We'll fill each block for Maya's clinic SaaS as we go. Single-line answers. The discipline is brutal compression — if you can't say it in one line, you don't understand it yet.

### Block 1 — Problem (and existing alternatives)

The top one to three problems your customer has, *in their words from your interviews*, plus what they do today instead (the "existing alternatives" — almost never "nothing").

- **Maya's:** "Last-minute cancellations leave chairs empty and revenue lost; the front desk can't fill the slot fast enough by calling down a paper waitlist."
- **Existing alternatives:** front desk calls patients manually; the slot goes unfilled; a generic scheduling tool with no waitlist automation.

The existing-alternatives line is the one founders skip and investors pounce on. *Nobody has zero current solution.* Even "they live with the pain" is an alternative. If you can't name what they do today, you haven't done discovery.

### Block 2 — Customer Segments (and early adopters)

Who specifically. Not "dentists" — *which* dentists, and who among them will buy *first*.

- **Maya's:** Independent dental clinics, 1–3 chairs, owner-operated, in the US.
- **Early adopters:** Owner-dentists who already feel the cancellation pain acutely and are comfortable with web tools (often the newer practices).

Early adopters are a separate line because the people who buy first are weirder and more desperate than your eventual mainstream. You design the MVP and the first GTM for them, not the mass market.

### Block 3 — Unique Value Proposition

A single, clear, compelling sentence: what you do, for whom, and the result — different from the alternatives.

- **Maya's:** "Fill same-day cancellation slots automatically, so independent clinics stop losing revenue to empty chairs."

The test: could a competitor put the *exact same sentence* on their site? If yes, it's not unique. "Easy scheduling software" fails. "Automatically fills cancellations" is specific to the pain.

### Block 4 — Solution

The top one to three features that deliver the value prop. *Features, not the whole roadmap.*

- **Maya's:** Auto-text the waitlist when a cancellation hits; one-tap claim; auto-confirm and update the calendar.

Notice it maps one-to-one to the problem. Every feature here should trace back to a problem line. Features that don't trace back are scope creep wearing a lab coat.

### Block 5 — Channels

How you reach customers — to *acquire* them, not just to deliver. This is where Week 7 lives, but you seed it here.

- **Maya's:** Founder-led outbound to local clinics; dental practice-management Facebook groups; later, partnerships with practice-management software.

### Block 6 — Revenue Streams

How you charge and roughly how much. This is the block that decides whether Lecture 2's math works, so it gets its own section below (§4–§6).

- **Maya's:** $99/month subscription per clinic.

### Block 7 — Cost Structure

What it costs to run — split into the *variable* costs (per customer) and *fixed* costs (regardless of customers). The variable ones feed contribution margin in Lecture 2.

- **Maya's variable:** SMS per text, payment processing, a sliver of support (~$9/clinic/month).
- **Maya's fixed:** her own time, hosting baseline, tools.

### Block 8 — Key Metrics

The one or two numbers that tell you if the model is working *right now*. (Week 7 obsesses over picking the *one* that matters; here, name candidates.)

- **Maya's:** Slots filled per clinic per month (the activation/value metric); monthly churn.

### Block 9 — Unfair Advantage

The thing that can't easily be copied or bought. Most founders can't fill this honestly on day one — and admitting that is more useful than inventing a fake moat.

- **Maya's (early, honest):** "None durable yet; the bet is that proprietary waitlist-behavior data and clinic switching costs accumulate over time." Better than pretending she has a moat she doesn't.

> **The point of "Canvas in 20":** the boxes you *can't* fill are your riskiest assumptions. An empty Channels box means you have no idea how you'll reach customers — that's a Week 7 emergency. An empty Unfair Advantage box is normal and fine at this stage. A confident-but-vague Revenue Streams box is a trap, because Lecture 2 will expose it.

---

## 4. Revenue models: how you charge

The Revenue Streams block deserves real attention because the *same product* becomes a different business under a different revenue model. Here are the models you'll actually choose among in 2026, with the trade-off each makes.

### Subscription (the SaaS default)

Customer pays a recurring fee — monthly or annual — for ongoing access. The dominant model for software in 2026 for good reason: predictable revenue, compounding retention, clean LTV math.

- **Good when:** you deliver continuous value (the customer needs you every month), and switching is mildly sticky.
- **Watch out for:** you must *keep earning it* — churn is the silent killer of subscription businesses (Lecture 2).
- **Examples:** Maya's $99/mo; most B2B tools.

### Transactional / one-time

Customer pays once per purchase. No recurring obligation either way.

- **Good when:** the value is episodic — a customer buys when they need it, not continuously.
- **Watch out for:** every month starts at zero; you re-acquire constantly. CAC has to be tiny relative to order value.
- **Examples:** e-commerce, a one-off course, a paid download.

### Marketplace take rate

You connect two sides (buyers and sellers) and keep a percentage of each transaction — the "take rate," typically 5–30%.

- **Good when:** you facilitate a transaction that would happen anyway and can defend disintermediation (people transacting around you).
- **Watch out for:** chicken-and-egg (need both sides at once); leakage (once introduced, they cut you out).
- **Examples:** Airbnb (~14% blended historically), Uber, Etsy. A 15% take rate is a common anchor.

### Usage / consumption-based (the AI-era resurgence)

Customer pays per unit consumed — per API call, per GB, per token, per seat-hour. Surged back into fashion with AI products in 2023–2026 because the underlying cost (model inference) is itself usage-based, so the pricing matches the cost.

- **Good when:** value scales with usage, costs scale with usage, and customers want to pay only for what they use.
- **Watch out for:** revenue is less predictable; customers fear surprise bills (so many products add caps/commitments — a "hybrid").
- **Examples:** cloud infrastructure (AWS), AI APIs ($/million tokens), Twilio ($/message).

### Advertising

The user is free; advertisers pay for attention. Revenue per user is small, so it needs *massive* scale.

- **Good when:** you can reach enormous audiences cheaply and the product is engagement-heavy.
- **Watch out for:** a founder bootstrapping at small scale almost never makes ads work. It is a late-game, big-numbers model.
- **Examples:** social platforms, free media. **Rarely the right first model for a startup** — name it only if you genuinely have a scale path.

### Freemium

A free tier acquires users; a paid tier monetizes a slice of them. **Freemium is a *funnel*, not a revenue model** — the actual revenue comes from a subscription or usage tier underneath. We list it because founders constantly say "we'll do freemium" as if that answers the revenue question. It doesn't.

- **Good when:** the free tier has low marginal cost and naturally demonstrates value, and a clear slice will convert.
- **Watch out for:** free users cost you money (support, hosting) and most never convert. Conversion rates of 2–5% free-to-paid are common. Do the math before you commit.

### Hybrids (the 2026 norm)

Real companies mix: a base subscription **plus** usage overage (the most common B2B SaaS shape in 2026), or a platform fee plus a take rate, or freemium funneling into a per-seat subscription. Hybrids exist to align price with value *and* keep revenue predictable. Maya could do **$49 base + $1 per filled slot** — a hybrid that ties more of her revenue to the value she demonstrably creates.

> **How to choose:** start from value and cost. Charge in the unit your customer already *thinks* in (clinics think in months and filled slots, not API calls). Match the revenue model's rhythm to how the value arrives (continuous → subscription; episodic → transactional; metered → usage). Then sanity-check against Lecture 2: does the chosen model produce a contribution margin that survives a realistic CAC?

---

## 5. Pricing: the part everyone underdoes

Choosing a revenue model tells you *how* you charge. Pricing tells you *how much*. Founders get this wrong in one predictable direction: **they underprice.** Almost always. Let's fix the reasoning.

### The three ways to set a price

1. **Cost-plus.** Add up your costs, tack on a margin. *This is the wrong starting question for a startup.* Your costs have nothing to do with the value you create. Software's marginal cost is near zero — cost-plus would price you at near zero, which is insane.
2. **Competitor-anchored.** Look at what others charge and price near them. Useful as a *sanity check* and a reference point for what the market expects, but it cedes your pricing power to incumbents and assumes you offer the same value.
3. **Value-based.** Start from *what the outcome is worth to the customer*, and price as a fraction of that value. **This is the founder's default.**

### Value-based pricing, concretely

Maya's product fills cancellation slots. **A single filled slot is worth ~$150 to a clinic** (the revenue from one appointment). If her software fills even *four* slots a month that would otherwise have gone empty, she has created ~$600/month of value. Pricing at $99/month means she captures about 16% of the value she creates and leaves the clinic with the rest — an easy yes for the customer, and still a great margin for her (her cost to serve is ~$9).

Notice what *didn't* enter that reasoning: her costs. Value-based pricing starts from the customer's gain, not the provider's expense. Cost only sets the *floor* (don't price below your variable cost) and feeds the *margin* math later.

### The underpricing trap (and the "pricing dare")

Why do founders underprice? Fear. A low price feels safer — "they'll definitely say yes." But a price that gets a 100% yes rate is too low; you're leaving money on the table and, worse, **signaling the product is cheap/unserious**, which can repel exactly the customers who'd pay more. In the studio's *pricing dare*, every founder names their price and the room asks "why not double it?" The founder almost always discovers their number was a flinch, not an analysis.

Heuristics worth internalizing:

- **If nobody ever pushes back on your price, it's too low.** A healthy price gets *some* "that's expensive."
- **Raising prices is the highest-leverage growth lever** you have, and the cheapest to test — a price change is a one-line experiment, no engineering.
- **Anchor high, discount deliberately.** It's far easier to come down than to go up.
- **Price the value, not the feature.** Customers pay for filled slots (outcomes), not for "automated SMS" (mechanism).

### Willingness to pay — find it, don't guess it

You don't have to divine the perfect price. *Ask.* In your remaining discovery conversations, probe willingness to pay: "What are empty slots costing you per month?" "If a tool reliably filled half of them, what would that be worth?" "What do you pay today for [the alternative]?" The Van Westendorp-style questions (at what price is this too expensive / a bargain / too cheap to trust) are a lightweight way to triangulate. You'll set the first price as a *hypothesis* and test it — pricing is iterative, not a one-time decree.

---

## 6. From canvas to the money question

By now you have a filled lean canvas and a chosen revenue model with a first price. The canvas tells you the *story* of the business. But a story can be internally coherent and still lose money on every customer. Two businesses with identical canvases can have opposite fates depending on four numbers: what it costs to serve a customer, what it costs to acquire one, how long they stay, and how much you charge.

That's Lecture 2. Here's the bridge, made concrete with Maya's canvas:

- Her **Revenue Streams** block says $99/month. Her **Cost Structure** block says ~$9/month variable to serve. → **Contribution margin = $90/month.** (Lecture 2, §1)
- Her **Channels** block says founder-led sales. That has a cost — her time. → **CAC ≈ $300.** (Lecture 2, §2)
- Her **Key Metrics** block tracks churn. Clinics stay ~24 months. → **LTV ≈ $90 × 24 = $2,160.** (Lecture 2, §3)
- Divide: **LTV:CAC ≈ 7:1**, **payback ≈ 3.3 months.** (Lecture 2, §4–5)

The canvas *produced* the inputs to the unit-economics math. That's not a coincidence — a good canvas is exactly the set of assumptions the unit-economics sheet needs. If your canvas is vague, your math will be fiction. If it's specific and honest, the math will tell you something true and possibly uncomfortable.

---

## 7. Zooming in: the Value Proposition Canvas

The single hardest block on the lean canvas is the **Unique Value Proposition** — the bridge between the customer's problem and your solution. When founders struggle with it (and most do), there's a sharper tool: Strategyzer's **Value Proposition Canvas**, a zoom-in on just two of the nine blocks (Customer Segments and Value Proposition). It's worth ten minutes because it forces a fit you can otherwise hand-wave.

It has two halves that must *match*:

**The customer profile (right side) — what's true about the customer regardless of you:**
- **Jobs** — what the customer is trying to get done (functional: "fill an empty chair"; emotional: "feel in control of the schedule"; social: "look competent to the dentist I work for").
- **Pains** — what annoys, blocks, or scares them about getting the job done ("the slot stays empty," "calling the waitlist is slow and awkward").
- **Gains** — the outcomes they *want*, including the unexpected delights ("the slot fills itself," "I never think about it again").

**The value map (left side) — what you offer:**
- **Products & services** — what you actually provide.
- **Pain relievers** — how you kill specific pains (each should point at a named pain).
- **Gain creators** — how you produce specific gains.

**Fit** happens when your pain relievers and gain creators line up against the customer's *most important, most intense* pains and gains — not all of them, the ones that matter. Maya's "auto-text the waitlist the instant a cancellation hits" is a pain reliever that maps precisely onto the pain "calling the waitlist is slow." That one-to-one mapping is what makes a value proposition feel *inevitable* to the customer instead of merely nice.

The discipline this enforces: if you have a pain reliever that addresses no real pain, it's a feature nobody asked for (cut it). If you have an intense customer pain with no pain reliever pointing at it, that's a gap a competitor will exploit. The Value Proposition Canvas is just a magnifying glass on the two lean-canvas blocks that decide whether you have product-market fit at all — use it when your UVP block feels mushy.

---

## 8. Channels and customer relationships have economics too

Two blocks founders treat as soft, fuzzy strategy actually drive hard numbers downstream: **Channels** (how you reach and acquire customers) and, in Osterwalder's fuller canvas, **Customer Relationships** (how you get, keep, and grow them). They're soft on the canvas and *expensive* in the unit economics.

- **Channels feed CAC.** "Founder-led outbound" is a channel with a cost: your hours. "Paid social ads" is a channel with a different cost: dollars that rise as you saturate the audience. "Content/SEO" is a channel with a long lead time and near-zero marginal cost once it's working. The channel you pick in your Channels block *is* the CAC you'll compute in Lecture 2 — they're the same decision viewed from two angles. A founder who writes "social media!" in the Channels box and then assumes a $40 CAC hasn't connected the two.
- **Customer Relationships feed churn, and churn drives LTV.** "Self-serve with great onboarding" vs. "high-touch account management" vs. "community" aren't just vibes — they're different retention curves and different costs to serve. High-touch relationships lift retention (good for LTV) but raise variable cost (bad for contribution margin). The relationship model is a *trade* between margin and retention, and you should make it on purpose.

The lesson that ties §7–§8 together: **every "soft" block on the canvas cashes out as a number in the unit-economics sheet.** Value proposition fit → willingness to pay → price. Channels → CAC. Relationships → churn → LTV. A canvas isn't a creative-writing exercise; it's the qualitative front-end of a quantitative model. Fill it like the numbers depend on it, because they do.

---

## 9. The same product, two revenue models — a worked comparison

The claim that "the revenue model can change whether you have a business" is easy to assert and hard to feel until you run the same product two ways. Let's do it with Maya. The *software is identical* in both — same code, same value, same customer. Only the Revenue Streams block changes.

**Model A — flat subscription ($99/month per clinic).** This is what we've used. Revenue is predictable: 100 clinics = $9,900/month, every month, whether they fill 2 slots or 20. The clinic likes the predictability too — a fixed line item they can budget. The risk lives entirely in *churn*: Maya earns the $99 again every month and has to keep earning it.

**Model B — per-filled-slot take ($49 base + $1 per filled slot).** Now Maya's revenue rises with the value she demonstrably creates. A clinic that fills 30 slots/month pays $49 + $30 = $79; a clinic that fills 4 pays $53. On average, a clinic filling ~10 slots pays ~$59 — *less* than Model A's $99 — but the heavy users pay more, and the pricing *feels* fairer to the clinic because it tracks outcomes.

Lay them side by side for an average clinic filling ~10 slots/month:

| | Model A (flat $99) | Model B ($49 + $1/slot, ~10 slots) |
|--|------------------:|----------------------------------:|
| Revenue / clinic / month | $99 | ~$59 |
| Variable cost (incl. per-slot SMS) | ~$9 | ~$11 |
| Contribution margin | $90 | ~$48 |
| Revenue predictability | High (fixed) | Lower (usage-driven) |
| Perceived fairness to clinic | Medium | High (pay for value) |
| Churn risk | Concentrated in cancellation | Lower (price scales down in slow months → less reason to cancel) |

The trade-off is real and goes both ways. Model A has fatter contribution margin and clean, predictable revenue — but a clinic having a slow month still pays full freight and may churn out of resentment. Model B has thinner margin and lumpier revenue — but it's "fair," self-discounts in slow months (reducing churn), and *captures more from the high-value clinics* who'd be a bargain at $99 flat.

There's no universally right answer — and that's the lesson. The *same software* is a different business under each model, with different fragilities (Model A: churn; Model B: average-usage-too-low). A founder who's only ever modeled one revenue path doesn't actually know their business yet. This is exactly why the mini-project's stretch goal asks you to model your concept under two revenue models: the comparison surfaces which fragility you're actually signing up for.

---

## 10. From canvas to test: mapping assumptions to experiments

A canvas is worthless if it just sits in a slide. Its job is to *generate your test list*. Every block is an assumption, and every assumption has a cheapest possible test. Walk your canvas and, for the riskiest two or three boxes, write the experiment that would prove or kill it. Maya's:

| Canvas block | The assumption hiding in it | Cheapest test (this week / Week 7) |
|--------------|----------------------------|-------------------------------------|
| Customer Segments | "1–3 chair owner-operated clinics are the right first segment" | Compare interview enthusiasm of small vs. large clinics; see who replies to outreach. |
| Revenue Streams | "Clinics will pay $99/month" | Ask 10 clinics the willingness-to-pay questions; offer a paid pilot to 3. |
| Channels | "Founder-led outbound can land clinics affordably" | Cold-outreach 20 clinics; measure reply rate and hours-per-close (→ a real CAC). |
| Key Metrics | "Slots filled is the metric that predicts retention" | Watch whether clinics that fill more slots in month 1 churn less. |

Notice the discipline: each test is *cheap* and *fast* and produces a number that updates a canvas block — which updates the unit-economics sheet. This is the build-measure-learn loop from Week 5, now applied to the *business model* instead of the product. The canvas isn't a document you finish; it's a board of bets you keep settling. When you commit your canvas this week, annotate the two riskiest boxes with their test — that annotation is what makes it a living artifact instead of a pretty rectangle.

---

## 11. Common ways the canvas lies

Before you go fill yours, here are the failure modes graders and investors spot instantly:

- **The "everyone" customer segment.** "Our customer is anyone who…" means you have no customer. Narrow it until it's almost uncomfortably specific.
- **The mechanism-as-value-prop.** "We use AI to…" is not a value proposition; it's a how. The value prop is the customer's outcome.
- **The empty existing-alternatives line.** Pretending the customer does nothing today. They always do *something*; name it.
- **The fantasy unfair advantage.** "First mover," "our team's passion," "great UX" — none of these are moats. Honest "no durable moat yet" beats a fake one.
- **The hand-wave revenue block.** "We'll figure out monetization later" / "freemium." Pick a model and a number, even as a hypothesis. Lecture 2 needs it.
- **Costs that forget the founder's time.** A cost structure with no founder labor in it makes CAC look free. It isn't.

---

## 12. Recap

- A **business model** is a one-page hypothesis (the lean canvas's nine blocks) about how value is created, delivered, and captured. Most of it is wrong on draft one — the canvas makes the wrong parts visible.
- We use the **Lean Canvas** (Maurya) over the Business Model Canvas (Osterwalder) because its Problem / Solution / Key Metrics / Unfair Advantage blocks fit a pre-PMF startup.
- **Revenue model ≠ pricing model ≠ business model.** The revenue model (subscription, transactional, take-rate, usage, ads, freemium, hybrid) is one block but it largely decides whether the unit economics close.
- **Price on value, not cost.** Underpricing is the most common and most expensive early mistake; raising price is the highest-leverage, cheapest-to-test lever you have.
- The canvas isn't the deliverable on its own — it *produces the inputs* to the unit-economics sheet, which is the real test of whether there's a business here.

---

*Back to the [week overview](../README.md). Next: [Lecture 2 — Unit Economics That Tell the Truth](./02-unit-economics-that-tell-the-truth.md). Then do [Exercise 1](../exercises/exercise-01-canvas-and-margins.md) and fill your [lean canvas worksheet](../exercises/exercise-02-lean-canvas-worksheet.md).*
