# Challenge 1 — The Channel Pivot

**Time estimate:** ~90 minutes.

**Format:** A founder decision scenario. You read a realistic, messy situation, reason from the funnel data, and write a **decision memo** committing to a course of action you can defend. No code; this is judgment under uncertainty — the actual job of a founder.

---

## The scenario

You are **Devin**, solo founder of **StackPilot**, a $40/month tool that helps indie SaaS developers monitor their cloud costs and get alerted before a surprise bill. Your ICP is solo and 2–3 person dev teams running on AWS/GCP. You've been heads-down for eight weeks. You have **about 14 weeks of runway** left in your personal savings before you have to take contract work to survive — and contract work means StackPilot stalls.

Six weeks ago you committed to **one motion and one channel**: content/inbound via **founder-led technical writing** — deep, genuinely useful blog posts about cloud-cost surprises ("How I cut my AWS bill 60% in a weekend"), shared on Hacker News, r/devops, and your own X account. Your pre-registered success bar, written on week 1, was:

> "Win = **≥ 15 paid signups** AND **≥ 40% week-4 retention** on those signups, within 6 weeks."

It's now the end of week 6. Here's what actually happened. The numbers are real; the interpretation is your job.

### The funnel (6 weeks)

```
Blog readers (unique):            28,400
Clicked through to the site:       3,120   → 11.0% of readers
Started a free trial:                412   → 13.2% of clicks
Activated (connected a cloud acct):  158   → 38.3% of trials   ← biggest drop
Converted to paid:                    22   → 13.9% of activated
Still paying at week 4 (cohort):      17   → 77% of paid (of the ones old enough to measure)
```

### Extra context you have

- **Two posts carried everything.** One Hacker News front-page hit (week 2) and one that got picked up by a popular dev newsletter (week 4) drove ~80% of the 28,400 readers. Your other four posts barely moved. Founder-led content is *spiky*, not steady.
- **The 22 paying customers love it.** Five emailed you unprompted to say it saved them real money. Week-4 retention of the measurable cohort is **77%** — well above your 40% bar. The people who stick, *really* stick.
- **Activation is the leak.** Of 412 trials, only 158 connected a cloud account (38%). The other 254 signed up and never connected — your "aha" requires an AWS/GCP credential step that people stall on (security nerves, IAM permissions confusion).
- **You hit the retention bar but missed the paid-signups bar.** 22 paid vs. a bar of 15? You actually *cleared* the paid-signups number. Re-read the bar: it was **≥ 15 paid AND ≥ 40% week-4 retention.** You got 22 paid and 77% retention. By the letter of your pre-registered bar, **you hit it.**
- **But it doesn't feel like a win.** The traffic was two lucky viral spikes you're not sure you can repeat. Your *steady-state* content (the four normal posts) converted almost nobody. You're worried you mistook two lottery tickets for a channel.
- **An alternative is tugging at you.** A developer-tool marketplace (a popular CI/CD platform's integrations directory) has invited you to list StackPilot. It's a partnership/channel motion — potentially steady, gatekept, and unproven for you. Setting it up well would cost ~2 weeks and pull you off content.

### The tension

You did the honest thing and pre-registered a bar. **By the letter, you passed.** But your gut says the channel's success was luck, not a repeatable system, and your runway clock is loud. Meanwhile a new channel beckons — which could be the smart pivot or could be classic shiny-object channel-hopping. And there's a clear, fixable leak (activation) sitting right in front of you that has nothing to do with the channel at all.

---

## Your task

Write a **decision memo** (roughly 600–900 words) that makes and defends a call. Your memo must work through, in order:

1. **Did you hit your bar — really?** Address the letter-vs-spirit problem head-on. You technically passed; argue whether that pass is *real* given the viral spikes, or whether honoring the pre-registered bar means you should treat it as a win regardless of how it felt. (There's a genuine integrity question here: moving the goalposts after passing is as dishonest as moving them after failing.)
2. **Read the funnel by rate.** Name the true leakiest step and what it implies. Is your problem the *channel* (top of funnel) or the *product/onboarding* (activation)? These call for completely different responses.
3. **Separate signal from luck.** Decide what the 28,400 readers actually tell you. Is content a repeatable channel for StackPilot, or did two viral hits flatter a channel that doesn't steadily convert? What evidence would settle it?
4. **Make the decision.** Commit to ONE of:
   - **Double down** on content as-is (and explain how you'll de-risk the "was it luck" problem).
   - **Fix the leak first** (attack the 38% activation step) before judging the channel at all.
   - **Pivot/add** the marketplace channel (and explain how this isn't just shiny-object hopping).
   - **Kill content and run a different inner-ring channel** (name it).
5. **State the new success bar and time box.** Whatever you choose, pre-register the next bar and a runway-aware deadline. You have ~14 weeks; spend them like they're finite, because they are.
6. **Name your risk.** What are you betting wrong about? What single piece of evidence would flip your decision?

---

## What a strong memo does

- **Catches the activation leak.** The sharpest readers notice that the biggest drop (412 → 158 trials → activated, 38%) is a *product/onboarding* problem, not a *channel* problem — and that no amount of channel-switching fixes it. Fixing activation might more than double paid conversions from the *same* traffic. A memo that pivots channels while ignoring a 62% activation leak is fighting the wrong war.
- **Holds the line on the pre-registered bar honestly.** It's intellectually honest to say "I passed my bar, and I refuse to retroactively decide it doesn't count just because it felt lucky — but I'll set a *harder* bar next round to test repeatability." That's different from rationalizing.
- **Treats runway as a hard constraint.** 14 weeks isn't infinite. The memo should weight "fastest path to repeatable revenue" heavily and time-box accordingly.
- **Resists shiny-object syndrome with eyes open.** Adding the marketplace might be right — but only with a clear-eyed reason it beats fixing the funnel you already have. "It's new and exciting" is not a reason.
- **Ends with a specific, dated next action and a new falsifiable bar.**

## What a weak memo does

- Picks a channel pivot on vibes, ignoring the activation leak.
- Declares the channel a failure despite literally passing the pre-registered bar (moving goalposts after the fact).
- Says "do all of the above" — no focus, no decision.
- Sets no new bar, or a vague one ("get more traction").
- Ignores the runway clock entirely.

---

## Deliverable

Commit `challenges/challenge-01-channel-pivot/decision-memo.md` to your Week 7 repo. Structure:

```markdown
# StackPilot — channel decision memo (end of week 6)

## Decision (one sentence, up front)
____________________________________________

## 1. Did we hit the bar — really?
...

## 2. The funnel, by rate — where's the real leak?
...

## 3. Signal vs. luck — what do the 28,400 readers tell us?
...

## 4. The decision and why (vs. the alternatives I rejected)
...

## 5. New pre-registered success bar + time box (runway-aware)
Win = ____________________   Deadline: ____ (of ~14 weeks runway)

## 6. The risk I'm accepting / what would flip this
...
```

---

## Acceptance criteria

- [ ] A decision memo, ~600–900 words, with the decision stated in one sentence up front.
- [ ] Directly addresses the letter-vs-spirit problem of having passed the pre-registered bar.
- [ ] Identifies the true leakiest step **by rate** and distinguishes channel problems from product/onboarding problems.
- [ ] Separates the viral-spike luck from repeatable channel signal, and names what evidence would settle it.
- [ ] Commits to ONE course of action and explains why over the alternatives.
- [ ] Sets a new, numeric, falsifiable success bar with a runway-aware deadline.
- [ ] Names the risk being accepted and the single piece of evidence that would flip the decision.
- [ ] Committed to your Week 7 repo.

---

## Stretch

- **Model both paths on a runway timeline.** Sketch, week by week, where revenue likely is in 8 weeks if you (a) fix activation vs. (b) pivot to the marketplace. Which gets you to ramen-profitable faster?
- **Write the activation fix.** Draft the specific onboarding change that would attack the 38% activation step (e.g., a read-only "demo mode" that shows value *before* asking for cloud credentials). Estimate its impact on paid conversions from the same traffic.
- **Re-run the decision with half the runway.** Re-write the memo's decision assuming you have only **6** weeks of runway, not 14. Does the urgency change the call? It should — and noticing *how* is the lesson.

## Why this matters

This is the exact decision that separates founders who survive from founders who don't. The data is never clean. There's always a fixable leak you're tempted to ignore, a shiny new channel you're tempted to chase, a pre-registered bar you're tempted to reinterpret, and a runway clock making you want to do *something* — anything. The skill is reasoning from the funnel and your own pre-set rules instead of from panic. You'll make a version of this exact call before demo day in Week 10, and again every quarter for the life of the company.
