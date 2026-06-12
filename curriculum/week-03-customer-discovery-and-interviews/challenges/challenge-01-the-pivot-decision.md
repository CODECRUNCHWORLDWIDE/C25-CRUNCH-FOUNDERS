# Challenge 1 — The Pivot Decision

**Time estimate:** ~90 minutes.
**Output:** `challenges/challenge-01-answer.md`, committed to your Week 3 repo.

## The setup

You are the founder of **ShiftFill**, and you've just finished a brutal week of discovery. Your original hypothesis, set in Week 2:

> *"Independent restaurants struggle to cover last-minute shift gaps when a server calls out sick, which costs them a stressful scramble and sometimes a short-staffed, badly-run night. I'll build an app that broadcasts open shifts to a pool of vetted local part-time staff who can claim them."*

Your Week 2 **kill criteria** (you wrote these before any interview — don't change them now):

1. **Kill** if fewer than half of restaurant managers describe last-minute coverage as a top-3 operational headache.
2. **Kill** if managers have not already spent money or meaningful effort trying to solve it (no workaround = not painful enough).
3. **Kill** if the gap happens less than roughly twice a month for a typical venue.

You ran **six** interviews. Here's the (deliberately messy) data.

---

## The interview data

**I-01 — GM, 40-seat neighborhood bistro.**
> "Honestly the call-out thing happens maybe once a month and we just absorb it — someone stays late. The thing that actually kills me is *scheduling* in the first place. I spend three hours every Sunday in a spreadsheet doing next week's rota, and then someone swaps and it all breaks."
Workaround: spreadsheet + group text. Pays for nothing. Offered to show me the spreadsheet. Frequency of *call-outs*: ~monthly. Severity: shrug. Frequency of *scheduling pain*: weekly, 3 hrs.

**I-02 — Owner, two taco spots.**
> "Covering a sick call is annoying but I've got a WhatsApp group and someone usually grabs it. What I'd pay real money for is something that stops people from *no-call-no-showing* — when they just don't turn up and don't tell me, that's the nightmare."
Workaround: WhatsApp group (free). For no-shows: nothing works; "I just eat it." Call-out coverage: ~twice/month, low severity. No-show: ~weekly across two venues, high severity, no workaround.

**I-03 — Manager, busy brunch cafe.**
> "Last-minute coverage? Constant. We're short literally every weekend. I've tried three staffing apps — they send me randoms who don't show or can't pour a coffee. I currently pay a temp agency $25/hr and hate it."
Workaround: pays temp agency ($25/hr). Tried 3 apps, churned. Frequency: weekly+. Severity: high. Asked, unprompted, "so how is yours different?"

**I-04 — GM, upscale 90-seat restaurant.**
> "We don't really have this problem — we're fully staffed and people don't call out much because the tips are good. Scheduling is handled by my AGM."
No pain. Frequency: rare. Severity: low. (Note: high-end venue, different labor dynamics.)

**I-05 — Owner-operator, food truck + small cafe.**
> "It's just me and two part-timers. If one's out, I cover it myself. Painful but there's no 'pool' to call — it's a me problem." Liked the idea ("sounds cool!") but couldn't point to spend or a workaround beyond "I work the shift."
Frequency: ~twice/month. Severity: medium (it's the owner's time). Signal: compliment only.

**I-06 — Assistant manager, 60-seat gastropub (referred by I-03).**
> "Weekend coverage is a real headache, yeah. We keep a list of 'always say yes' people and text them. Works about half the time. Haven't paid for anything but I've definitely thought about it." Pointed me to two more managers.
Workaround: personal text list, ~50% hit rate. Frequency: weekly (weekends). Severity: medium-high. Signal: two referrals.

---

## Your task

Work the data the way Lecture 2 and Exercise 3 taught you, then make the call. Your answer file must contain:

1. **The decision, in one bold line at the top:** PERSEVERE, PIVOT, or DROP — and if pivot, *to what exactly*.

2. **A signal table** — for each candidate problem (shift-coverage, scheduling, no-shows, …), count independent unprompted mentions, note who has a real workaround/spend, and rate frequency and severity separately.

3. **The kill-criteria check** — go through all three criteria *as written* and state whether each is tripped, with the specific evidence. Resist the urge to soften a criterion to save the idea.

4. **The honesty paragraph** — explicitly name the data that *argues against* your chosen decision. (Every honest decision here has inconvenient data; find yours and own it.)

5. **Next step** — the specific next interviews or cheap test that would *resolve* the biggest remaining ambiguity. Name the segment and the question.

---

## Things to wrestle with (don't skip these)

- **Your original problem (last-minute coverage) got mixed reviews.** Some say constant-and-painful (I-03, I-06), some say monthly-and-shrug (I-01, I-02, I-05), one says no problem (I-04). Does it pass kill criterion #1? Be precise about *how you count*.
- **Two louder, different problems surfaced unprompted:** Sunday *scheduling* (I-01, and it lurks behind others) and *no-call-no-shows* (I-02). Each was raised with real heat. Are they surprises worth pivoting to, or one-off noise? How would you tell?
- **I-03 is your strongest signal** — real spend ($25/hr agency), tried competitors, leaned in. But she's *one* venue. How much weight does one intense data point deserve?
- **The segment isn't uniform.** The upscale venue (I-04) has no pain; the tiny operators (I-05) have pain but no "pool" to fill from, which may break your solution's core assumption. Does your real customer turn out to be a *narrower* segment than "independent restaurants"?
- **Watch the compliment trap.** I-05 said "sounds cool!" — does that move the needle at all? (It shouldn't. Say why.)

---

## What a strong answer looks like

A strong answer doesn't just pick a verdict — it shows its work. For example, it might conclude that last-minute coverage *narrowly survives* kill criterion #1 only if you scope the segment to busy mid-market weekend-driven venues (I-03, I-06, arguably I-02), and *fails* it across "all independent restaurants"; that the strongest, most-served-by-real-spend pain is concentrated in exactly that narrower segment; and therefore the right move is a **segment-narrowing pivot** plus three more interviews with brunch/weekend venues to confirm, while explicitly setting aside the scheduling and no-show threads as separate ideas to log, not chase now. Or it might argue the data is too thin at n=6 with this much spread to do anything but **keep interviewing toward ten with a sharper screen for who actually has the pain.** Both can be excellent — if the reasoning is honest and evidence-cited.

A weak answer says "PERSEVERE — most people had the problem and one person already pays for a competitor, so there's clearly a market," ignoring the segment split, the kill criteria, and the two unprompted surprises.

---

## Stretch

- Re-derive the decision if you *delete I-03* (your single strongest data point). Does your conclusion survive the loss of your best interview? If it doesn't, what does that tell you about how much you were leaning on one person?
- Draft the three-interview screening question that would have *prevented* you wasting I-04's slot (the no-pain upscale venue). Good screening makes discovery cheaper.

---

*Commit your answer as `challenges/challenge-01-answer.md`. State the decision up top, then defend it in about a page.*
