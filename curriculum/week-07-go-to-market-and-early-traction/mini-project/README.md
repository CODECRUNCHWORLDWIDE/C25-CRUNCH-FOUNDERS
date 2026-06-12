# Mini-Project — The Go-to-Market One-Pager + Traction Test

> Run one real, time-boxed channel test against actual prospects, then write the single page that names your go-to-market motion, the channel you tested, the funnel you measured, and the one traction metric you'll hold yourself to. This page becomes the **traction slide** of your Week 10 capstone pitch — and the first hard *evidence*, beyond interviews, that you can reach customers.

**Estimated time:** ~9 hours, split across the week — ~6.5 hours of field work (running the test) plus ~2.5 hours writing and polishing. The test runs Wednesday–Thursday; the writing happens Friday–Saturday.

This is the third compounding deliverable of Phase 3 and it builds directly on the rest of the course:

- **Week 2–3** gave you a chosen problem and a customer you've interviewed. The test contacts *those* customers.
- **Week 5** gave you an MVP or prototype. The test points real prospects at *it* — you can't measure activation with nothing to activate.
- **Week 6** gave you a lean canvas and unit economics. You hold this week's CAC against *that* LTV, live.
- **Week 8** (next) decides whether you even need to raise. You can't answer that without knowing whether you can acquire customers — which is what this proves.

The whole capstone rubric weights "MVP actually tests the riskiest assumption, with a recorded result" and "the pitch lands problem → evidence → solution → model → **traction** → ask." This mini-project is where the **traction** comes from. It is not a thought experiment — you contact real humans and count what happens.

---

## What you will produce

Two things, both in your Week 7 repo:

### 1. A run traction test (the field work)

You execute the channel test you designed in Exercise 2 against **real prospects** — not a simulation. Minimum bar for "real":

- **≥ 30 genuine contacts** (or, for an inbound/content motion, a smoke-test page shown to ≥ 30 real people / driven by ≥ 1 real post or ad with a tiny budget).
- A **tracking sheet** with one row per prospect and the full funnel logged with dates.
- A **pre-registered success bar** set *before* you ran anything (carried from Exercise 2).

If running a real test is genuinely impossible this week (e.g., a regulated B2B sale with months-long cycles), you may run the **smallest legitimate proxy** — a fake-door/smoke test, a "fake demo" booking page, a waitlist *with a refundable deposit* — but it must involve **real strangers taking a real action**, and you must say plainly in the write-up what's a proxy and what's measured. A fully hypothetical funnel does not satisfy this project.

### 2. The GTM one-pager (the deliverable)

A file `gtm/GTM-ONE-PAGER.md` — **one page** when rendered — with these sections:

1. **Customer & motion.** Who you sell to (specific ICP), the single motion you chose, and the fit reasoning (price/ACV + reachability). One unscalable thing you did first.
2. **The One Metric That Matters.** The single metric for your stage, why it (not a flashier one), and the three vanity metrics you're explicitly ignoring.
3. **Channel test result.** The channel, the specific action, the time box, the **pre-registered bar**, the **funnel numbers** (every step, with conversion rates), and a one-line verdict: did it clear the bar?
4. **Leakiest step & next experiment.** The biggest drop *by rate*, what it implies (channel problem vs. product/onboarding problem), and the next time-boxed experiment with a new bar.
5. **Early economics.** Blended CAC (cash + valued time) from the test, LTV from Week 6, the LTV:CAC ratio, and rough payback — with the honest caveat about small samples.
6. **The traction commitment.** The single metric and the specific target you'll hold yourself accountable to over the next month, with a date.

Keep it to one page. A GTM plan that needs five pages this early is mostly guessing. The discipline of one page is the point — if you can't fit it, you don't yet know it.

---

## Suggested order of operations

### Phase 1 — Design (Wed morning, ~1h)

Finalize Exercise 2. Lock the channel, the action, the list, the message, the time box, and the **pre-registered bar** (write it down, dated, *before* sending anything). Set up the tracking sheet.

### Phase 2 — Build the list (Wed, ~1.5h)

Assemble your real target list (≥ 30). For outbound: named prospects from directories, communities, or your own network, filtered to your ICP. For inbound: stand up the smoke-test page / write the post. Quality of list beats quantity — 30 well-chosen prospects beat 300 random ones, especially in 2026's flooded inboxes.

### Phase 3 — Run it (Wed–Thu, ~3.5h of active work over 1–2 days)

Send the personalized outreach / publish the content / launch the smoke test. Take the demos yourself. Log every step in the sheet *as it happens* — contacted, replied, demoed, trialed, paid — with dates. Do the unscalable thing you committed to (concierge onboarding, personal demo). Resist the urge to change the test mid-flight.

### Phase 4 — Read the funnel (Fri, ~1h)

Compute the conversion rate between each step. Find the leakiest step *by rate*. Compute blended CAC (value your time) and check LTV:CAC and payback against Week 6. Decide, using your pre-registered decision rule: double down, fix the leak and re-run, or pivot the channel.

### Phase 5 — Write the one-pager (Fri–Sat, ~2h)

Fill the six sections above, starting from your Exercise 3 canvas. Be specific and honest. State whether you cleared the bar plainly — a missed bar honestly reported is worth more than a vague "promising results."

### Phase 6 — Polish + commit (Sat, ~0.5h)

Trim to one page. Make sure the funnel numbers, CAC math, and commitment are all there and internally consistent. Commit `gtm/GTM-ONE-PAGER.md` and the tracking sheet (export to CSV or Markdown so a reviewer can see the raw data).

---

## Acceptance criteria

- [ ] A **real channel test was run** against ≥ 30 real prospects (or a clearly-labeled legitimate proxy), with a tracking sheet committed to the repo.
- [ ] A **pre-registered success bar** existed *before* the test (visible in the commit history or dated in the file).
- [ ] `gtm/GTM-ONE-PAGER.md` exists and fits on **one page** when rendered.
- [ ] **Motion** named with fit reasoning tied to price/ACV and customer reach; one unscalable first move named.
- [ ] **One metric** chosen for the stage and justified; **three vanity metrics** explicitly set aside.
- [ ] **Channel test result** with the action, time box, pre-set bar, and **funnel numbers with conversion rates** on every step; a clear "cleared the bar / didn't" verdict.
- [ ] **Leakiest step** identified by rate, with channel-vs-product diagnosis and a next experiment + new bar.
- [ ] **Early economics**: blended CAC, LTV (from Week 6), LTV:CAC, payback — with the small-sample caveat stated.
- [ ] A **specific, dated traction commitment** for the next month.
- [ ] Everything committed to your Week 7 repo.

---

## Rubric

| Criterion | Weight | What "great" looks like |
|-----------|------:|-------------------------|
| **A real test was run** | 20% | ≥30 real contacts, real funnel logged with dates; not hypothetical. Proxy clearly labeled if used. |
| **Motion fits the model** | 20% | Motion matches price/ACV and customer reachability; the price-point ladder and channel/model fit hold up. |
| **Metric is actionable, not vanity** | 15% | OMTM is a rate/behavior tied to money; the three vanity metrics are correctly identified and set aside. |
| **Funnel read honestly for its leak** | 20% | Conversion rates computed; leakiest step found *by rate*; channel-vs-product diagnosis is correct. |
| **Pre-registered bar + honest verdict** | 10% | Bar existed before the test; the "cleared it / didn't" call is honest, no goalpost-moving. |
| **Economics carried from Week 6** | 10% | CAC computed from real spend; LTV:CAC and payback checked against last week's numbers; small-sample caveat. |
| **Specific traction commitment** | 5% | A single metric and a dated target, not a vague intention. |

---

## How this compounds toward the capstone

- **Week 8 (Fundraising):** "do you need to raise?" is unanswerable without knowing if you can acquire customers. This page is the input.
- **Week 9 (Legal/ops):** the motion shapes what you'll actually need — a sales-led motion needs contracts and invoicing; a self-serve motion needs terms of service and a payment processor.
- **Week 10 (Pitch/demo day):** your **traction slide** is this one-pager, distilled. "We contacted 40 clinics, 2 are paying, here's the funnel and what we fixed" is exactly the evidence the capstone rubric rewards — and exactly the kind of concrete, honest traction story that survives investor questions. A founder who can show a measured funnel and a leak they're fixing reads as far more fundable than one waving at a hockey-stick projection.

---

## Stretch (optional)

- **Run a second, contrasting channel test.** Test a different motion in parallel and put the two funnels side by side. The comparison is where channel conviction actually comes from — most founders never do it.
- **Cohort the early users.** If your test produced ≥ 10 trial users, track week-1 and week-2 retention. Even a tiny retention curve tells you whether you've got a leaky bucket before you scale acquisition.
- **Build the activation fix.** If your leak is at activation (very common), design and ship the specific onboarding change, then re-run on a fresh list to measure the lift from the *same* traffic.
- **Write the traction slide now.** Draft the actual Week 10 slide from this page — one chart (the funnel), one number (the OMTM), one sentence on the next move. Future-you will thank present-you.

---

## Resources

- *Do Things That Don't Scale* — Paul Graham: <https://paulgraham.com/ds.html>
- *Startup Metrics for Pirates (AARRR)* — Dave McClure: <https://www.slideshare.net/dmc500hats/startup-metrics-for-pirates-long-version>
- *SaaS Metrics 2.0* (CAC, LTV, payback) — David Skok: <https://www.forentrepreneurs.com/saas-metrics-2/>
- *How the fastest-growing startups find their first customers* — Lenny Rachitsky: <https://www.lennysnewsletter.com/p/how-the-fastest-growing-companies>

---

## Submission

When done:

1. Commit `gtm/GTM-ONE-PAGER.md` and your tracking sheet (CSV or Markdown) to your Week 7 repo.
2. Make sure the funnel numbers, CAC math, and traction commitment are all present and internally consistent.
3. Confirm the pre-registered bar is visible (in the file, dated, or in commit history) so the "cleared it / didn't" verdict is verifiable.
4. Post the repo link in your cohort tracker. You contacted real people and counted what happened — that's real traction work. Show it.

*Next: [Week 8 — Fundraising Basics](../../week-08-fundraising-basics/). With a model and proof you can reach customers, you can finally decide whether you even need outside money.*
