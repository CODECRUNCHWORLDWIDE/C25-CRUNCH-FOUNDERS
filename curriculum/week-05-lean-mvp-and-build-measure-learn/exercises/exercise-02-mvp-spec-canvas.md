<!--
Exercise 2 — MVP Spec Canvas (WORKSHEET / TEMPLATE — not code)

HOW TO USE THIS FILE
  1. Copy this file to your Week 5 repo as exercises/exercise-02-mvp-spec-canvas.md
     (or fill it in place in your fork).
  2. Replace every <ANGLE-BRACKET PROMPT> with your own answer. Delete the
     guidance comments once you've answered.
  3. Fill it in BEFORE you build or launch anything. The threshold in section 4
     MUST be committed to git before your launch — your git history is the proof
     you didn't move the goalposts.
  4. This canvas drives the mini-project. When it's done, you build exactly what
     section 5 says — nothing more.

ACCEPTANCE (see the bottom of this file for the full checklist):
  [ ] A falsifiable hypothesis (section 3) in the "we'll know we're wrong if" form.
  [ ] Exactly ONE metric (section 4) and a threshold set before launch.
  [ ] A build plan you could finish in 2–3 days (section 5).
  [ ] Committed before launch.
-->

# MVP Spec Canvas — <YOUR IDEA NAME>

> One page that turns your riskiest assumption into a runnable experiment. Fill every section. If you can't, you're not ready to build.

**Founder(s):** <name(s)>
**Date filled (before launch):** <YYYY-MM-DD>
**Idea in one line:** <what it is, for whom, replacing what they do today>

---

## 1. The riskiest assumption (from Exercise 1)

> Carry over the single highest-risk assumption you chose. State it as a plain belief.

**Riskiest assumption:** <e.g., small-clinic front desks will hand off same-day cancellation refills to us>

**Why this one (uncertainty × fatality):** <one sentence on why it's both most uncertain and most fatal>

---

## 2. What "validated" vs. "invalidated" would mean

> Before you design the test, say in plain words what each outcome implies for the company.

- **If validated, we will:** <next step — usually test the NEXT riskiest assumption>
- **If invalidated, we will:** <the kind of pivot we'd most likely make — name it>

---

## 3. The falsifiable hypothesis

> Fill every bracket. If you can't, go back to Exercise 1.

**We believe** <segment — be specific, not "people">
**will** <observable behavior — a deed, not an opinion>
**because** <the reason rooted in your Week 3 interviews>.

**We'll know we're RIGHT if** <metric> **is at least** <threshold> **by** <date>.
**We'll know we're WRONG if** <metric> **is below** <threshold>.

---

## 4. The one metric + pre-committed threshold

> Exactly one metric. A deed, not a word. A rate or cohort, never a cumulative total.

| Field | Your answer |
|---|---|
| **The one metric (OMTM)** | <e.g., refill rate = % of same-day cancellations refilled> |
| **How it's measured** | <e.g., a Google Sheet: one row per cancellation, marked refilled/not> |
| **Threshold for "validated"** | at least <number> |
| **Where the threshold came from** | <unit-economics floor / benchmark / "would change my mind" gut check> |
| **Sample size I need to trust it** | <e.g., 2 clinics over 1 week; ~20+ cancellation events> |
| **Date I decide** | <YYYY-MM-DD> |

**Vanity-metric red-team:** *Could I hit this number and still have learned nothing?*
> <answer honestly. If "yes," fix the metric before continuing.>

---

## 5. The MVP itself (build plan)

> The cheapest type that could falsify the assumption. The build must be doable in 2–3 days. If it isn't, you scoped a product — shrink it.

| Field | Your answer |
|---|---|
| **MVP type** | <fake door / concierge / Wizard of Oz / clickable prototype / single-feature build> |
| **Why this is the cheapest test of THIS assumption** | <one sentence> |
| **What I will actually build/do** | <concrete: "a Carrd page + Tally form" or "text patients by hand for 2 clinics"> |
| **What I am deliberately NOT building** | <logins, billing, automation — list what you're faking or skipping> |
| **Tools (free/low-cost)** | <Carrd / Tally / Figma / GitHub Pages / Stripe payment link / a spreadsheet> |
| **Estimated build time** | <hours/days — should be ≤ 3 days> |
| **Estimated cost** | <should be near $0> |

---

## 6. How real people will touch it (the launch)

> The MVP only counts once the actual segment touches it. Friends don't count.

| Field | Your answer |
|---|---|
| **Who I'll put it in front of** | <the real segment — where they are> |
| **How I'll reach them** | <channel: cold DM, existing contacts, community, small ad, in-person> |
| **How many I expect to reach** | <number — sanity-check against your sample-size need> |
| **What I'll explicitly exclude** | <friends, family, cohort-mates — they bias the result> |

---

## 7. Ethics & honesty check

> Answer all three "yes" before launching.

- [ ] If I collect money, I can deliver or instantly refund. (No charging for something I can't honor.)
- [ ] Nothing the user sees *lies* about what happens next. ("Coming soon" after a click is fine; a fake confirmed order is not.)
- [ ] Any personal data I collect, I can store responsibly and delete on request.

**Would I be comfortable if the customer learned exactly what I did?** <yes / no — if no, redesign>

---

## 8. Timeline

| Day | Plan |
|---|---|
| Tue | Finish this canvas; commit (threshold locked). |
| Wed | Build the MVP. |
| Thu | Launch; start measuring. |
| Fri | Read results; complete Exercise 3. |
| Sat | Persevere/pivot decision; write the experiment up. |

---

## Worked example (Maya — clinic no-shows), abridged

- **Riskiest assumption:** front desks will hand off same-day refills.
- **Hypothesis:** *We believe small-clinic front desks will let us run their same-day cancellation refills because the manual scramble is their worst task. We'll know we're right if refill rate is at least 30% across 2 clinics in 1 week; wrong if below 30%.*
- **One metric / threshold:** refill rate · ≥30% · from a Google Sheet, one row per cancellation.
- **MVP type:** concierge — cheapest because it tests adoption + efficacy by hand, no code.
- **Build:** a shared Sheet + a texting app; Maya watches the feed and texts patients herself.
- **Not building:** software, logins, automation.
- **Launch:** 2 clinics she met in Week 3 interviews; excludes her own contacts.

---

## Acceptance criteria

- [ ] Sections 1–7 fully filled for your own idea (no leftover `<brackets>`).
- [ ] Section 3 is a falsifiable hypothesis with a "we'll know we're wrong if" clause.
- [ ] Section 4 has exactly ONE metric and a threshold, with where the number came from.
- [ ] The vanity-metric red-team is answered honestly.
- [ ] Section 5's build plan is doable in ≤ 3 days at near-zero cost.
- [ ] Committed to your Week 5 repo *before* you launch.

*Next: set up [Exercise 3 — Experiment Record Template](./exercise-03-experiment-record-template.md) now, and complete it after you run the MVP.*
