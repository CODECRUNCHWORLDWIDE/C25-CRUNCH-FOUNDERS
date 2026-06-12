# Week 5 — Lean MVP & Build-Measure-Learn

Welcome to **C25 · Crunch Founders**, Week 5. This is the week you finally *build* — and the first instinct you have to kill is the instinct to build the product. You are not building a product this week. You are building the smallest possible **experiment** that tests the single riskiest thing your idea depends on.

The most common first-time mistake is treating the MVP as "version one of the real thing, just smaller." It isn't. A minimum viable product is the cheapest way to learn whether your validated *problem* (Weeks 2–3) can be solved in a way real people will actually adopt and, eventually, pay for. Sometimes the cheapest test is a landing page that nothing sits behind. Sometimes it's you doing the work by hand for five customers while they think it's automated. The lean **build → measure → learn** loop turns each of those into one thing: a decision. **Persevere or pivot**, with a number behind it.

This week compounds directly on what you've already done. By now you have a triaged idea (Week 2), at least five real discovery interviews and a first pattern (Week 3), and a co-founder agreement draft (Week 4). Week 5 takes that pattern and forces it to survive contact with reality: you pick the one belief that, if wrong, kills the company, and you spend roughly two days and almost no money finding out whether it's true.

We move fast and we are allergic to vanity. A signup that never logs in is not evidence. A "that's a great idea" in an interview is not evidence. Behavior is evidence. This week is about manufacturing the cheapest behavior you can measure.

## Learning objectives

By the end of this week, you will be able to:

- **Distinguish** an MVP-as-experiment from an MVP-as-tiny-product — and explain why the difference decides whether the week was worth anything.
- **Surface and rank** every assumption your idea rests on, and isolate your single **riskiest assumption** using an uncertainty × fatality scoring grid.
- **Choose an MVP type** that matches the assumption: smoke test / fake door, concierge, Wizard of Oz, clickable prototype, or (last resort) a single-feature build.
- **Write a falsifiable hypothesis** in the form "We believe \[segment] will \[behavior] because \[reason]; we'll know we're wrong if \[metric] is below \[threshold]."
- **Define one success metric** the MVP will move (or fail to move), and **pre-commit a threshold** before launch so you can't move the goalposts.
- **Build a real MVP** in days using free or near-free no-code tools (Carrd, Tally/Google Forms, Figma, GitHub Pages, a Stripe payment link) — or by hand.
- **Run the build-measure-learn loop**, instrument the one metric, and read the result honestly against the pre-set threshold.
- **Decide persevere or pivot**, name *which kind* of pivot (zoom-in, customer-segment, problem, channel, business-model), and write the decision down with the number that drove it.
- **Recognize vanity metrics** and replace them with behavioral, actionable, comparable metrics.

## Prerequisites

This week assumes you have completed **C25 Weeks 1–4**, or arrive with equivalent founder work in hand. Specifically:

- A chosen idea that survived **Week 2** problem-first triage (you can state the problem, who has it, and why it's a painkiller not a vitamin).
- At least five **Week 3** discovery interviews written up, plus a first pattern summary. You will lean on these to name the riskiest assumption.
- A **Week 4** co-founder agreement draft (or a deliberate solo-founder decision) so the "who builds the MVP" question is already answered.
- Comfort with basic spreadsheet math (percentages, conversion rates). No coding required — this course writes zero code, and so does this week.
- A GitHub repo (or equivalent) where you've been committing your founder artifacts. We keep everything versioned so the capstone has a paper trail.

You do **not** need any product, any design skill, or any budget beyond pocket change. If you can make a Google Form and send ten text messages, you can run every MVP type in this week.

## Topics covered

- The MVP reframe: experiment with a hypothesis, a method, and a measurable result — not a small product.
- **Riskiest-assumption thinking:** what must be true for this to work, and which belief is both most uncertain and most fatal.
- The five MVP archetypes, cheapest-first, and the decision rule for matching type to assumption.
- The **build → measure → learn** loop and the idea of *validated learning* — minimizing total time through the loop, not time spent building.
- Writing a falsifiable hypothesis and pre-committing a single threshold.
- **Vanity vs. actionable metrics**; the "one metric that matters" at the experiment stage.
- Reading results honestly: signal vs. noise, sample-size sanity, the difference between "said" and "did."
- **Persevere vs. pivot**, and the named pivot types (zoom-in/zoom-out, customer segment, customer need, platform, channel, business architecture, value capture, engine of growth).
- Sequencing experiments: testing the scariest assumption first, then the next, so you de-risk in the right order.
- Keeping it ethical and legal: fake-door honesty, charging before delivering, and not collecting data you can't protect.

## Weekly schedule

The schedule below adds up to approximately **36 hours** across the week, front-loaded toward field work because the MVP only counts once real people touch it. Treat it as a target, not a contract — field work spikes mid-week.

| Day       | Focus                                            | Lectures | Exercises | Challenges | Quiz/Read | Homework | Mini-Project | Self-Study | Daily Total |
|-----------|--------------------------------------------------|---------:|----------:|-----------:|----------:|---------:|-------------:|-----------:|------------:|
| Monday    | MVP as experiment; riskiest assumption           |    2h    |    1.5h   |     0h     |    0.5h   |   1h     |     0h       |    0.5h    |     5.5h    |
| Tuesday   | MVP types; pick type, write hypothesis + threshold|   2h    |    2h     |     1h     |    0.5h   |   0.5h   |     0.5h     |    0h      |     6.5h    |
| Wednesday | Build the MVP (no-code / by hand)                |    0h    |    1h     |     1h     |    0.5h   |   1h     |     2h       |    0.5h    |     6h      |
| Thursday  | Launch + measure; field-work spike               |    1h    |    0.5h   |     0h     |    0.5h   |   1h     |     2.5h     |    0.5h    |     6h      |
| Friday    | Read results; vanity-metric audit; learn         |    1h    |    0.5h   |     0h     |    0.5h   |   1h     |     2h       |    0.5h    |     5.5h    |
| Saturday  | Persevere/pivot decision; write the experiment up |   0h    |    0h     |     1h     |    0h     |   0.5h   |     2.5h     |    0h      |     4h      |
| Sunday    | Quiz, review, polish the experiment record       |    0h    |    0h     |     0h     |    1h     |   0h     |     1h       |    0.5h    |     2.5h    |
| **Total** |                                                  | **6h**   | **5.5h**  | **3h**     | **3.5h**  | **5h**   | **10.5h**    | **2.5h**   | **36h**     |

## In-class activities

- **Riskiest-assumption surfacing.** Each founder lists every assumption their idea depends on, then ranks by "if this is false, the whole thing dies." The top one becomes the MVP target. Peers challenge any ranking that conveniently picks the easiest assumption to test.
- **MVP-type matching.** Given an assumption, the group races to name the *cheapest* MVP type that could falsify it. The win condition is "tested without building software." If someone proposes a four-week build, the room finds the fake-door or concierge version.
- **Threshold pre-commit.** Every founder writes, out loud and on the board, the number that would count as success *before* launching — so no one can move the goalposts on Friday.
- **Vanity-metric red-team.** Pairs swap experiment plans and try to break each other's metric: "Could you hit that number and still have learned nothing?" If yes, the metric is vanity; fix it.

## Worked example (carried through the week)

Maya is building a no-show fix for small medical clinics. Her **Week 3** interviews surfaced a pattern: front desks hate the manual scramble to refill a slot when a patient cancels. Her idea is a waitlist auto-fill tool that texts the next patient the moment a cancellation lands.

Her **riskiest assumption** is *not* "can we send a text" (trivially true) and *not* "do clinics dislike no-shows" (already validated). It's **"front-desk staff will actually adopt a new tool in the chaos of their day, and it will refill enough slots to matter."** Most uncertain, most fatal.

The cheapest test is *not* building the software. It's a **concierge MVP**: for two clinics, Maya personally watches their cancellation feed and texts waitlisted patients by hand, tracking how many slots she refills. Her pre-committed **threshold**, set Tuesday before she starts: *refill at least 30% of same-day cancellations across one week.*

She refills 45%. The assumption holds — front desks are happy to hand off the scramble, and patients say yes often enough. She **perseveres** to a thin software version (a Wizard-of-Oz next, then real automation). Had she refilled 5%, she'd **pivot** — maybe the bottleneck is patient response time, not the front desk, which would point her at a different solution entirely. Either way she learned in one week for the cost of her own time and a texting app. You'll see Maya again in the lectures, the exercises, and the quiz.

## How to navigate this week

| File | What's inside |
|------|---------------|
| [README.md](./README.md) | This overview (you are here) |
| [resources.md](./resources.md) | Curated, free references: lean-method primers, no-code tools, instrumentation, and ethics |
| [lecture-notes/01-mvp-as-experiment.md](./lecture-notes/01-mvp-as-experiment.md) | The MVP reframe, riskiest-assumption thinking, the five MVP archetypes, writing a falsifiable hypothesis |
| [lecture-notes/02-build-measure-learn.md](./lecture-notes/02-build-measure-learn.md) | The loop, one-metric discipline, vanity vs. actionable metrics, reading results, persevere vs. the named pivots |
| [exercises/README.md](./exercises/README.md) | Index of the week's worksheets + a checklist |
| [exercises/exercise-01-riskiest-assumption.md](./exercises/exercise-01-riskiest-assumption.md) | Guided: surface, score, and pick the assumption your MVP will test |
| [exercises/exercise-02-mvp-spec-canvas.md](./exercises/exercise-02-mvp-spec-canvas.md) | A fill-in MVP spec canvas: hypothesis, type, metric, threshold, build plan |
| [exercises/exercise-03-experiment-record-template.md](./exercises/exercise-03-experiment-record-template.md) | The reusable experiment-record template you'll fill after launch |
| [challenges/README.md](./challenges/README.md) | What the challenge is and how it's assessed |
| [challenges/challenge-01-pivot-or-persevere-board.md](./challenges/challenge-01-pivot-or-persevere-board.md) | Run a real persevere/pivot decision against three founder scenarios + your own |
| [quiz.md](./quiz.md) | 10 questions with an answer key |
| [homework.md](./homework.md) | The assignment with a grading rubric |
| [mini-project/README.md](./mini-project/README.md) | Build, launch, and report a real MVP — a capstone deliverable |

## The "would a bad result change your mind?" promise

C25 uses one recurring test in every experiment this week:

> **If your MVP cannot fail, it is not a test.**

Before you launch anything, ask: *what result would prove me wrong, and would I actually believe it?* If you can't name a number that would make you change direction — or if you secretly know you'd rationalize any result into a "win" — you haven't designed an experiment. You've designed a way to feel busy. The whole point of Week 5 is to make "I ran an experiment that could have killed my idea, and here's what happened" an ordinary sentence in your founder vocabulary.

## Stretch goals

If you finish the regular work early and want to push further:

- Run a **second** experiment on your next-riskiest assumption in the same week. De-risking is sequential; the founders who go fastest are testing assumption #2 while #1's results land.
- Add a **fake pricing test** to your fake door — show two or three price points and measure which "buy" button gets the clicks. (You don't charge yet; you measure intent. Don't take money you can't honor.)
- Replace your manual concierge step with a **Wizard of Oz** front end so the customer experience looks automated. Note which parts you faked and what it would cost to make them real.
- Write a one-page "experiment backlog": the five cheapest experiments you'd run next, ranked by how much risk each retires per dollar.
- Read one real teardown of a failed startup and identify the riskiest assumption they *never tested* before building.

## Up next

Continue to **Week 6 — Business Models & Unit Economics** once your experiment record is committed. With evidence that people will *adopt*, Week 6 asks the next question: can this thing ever make money? You'll bring your validated (or pivoted) concept into a lean canvas and a unit-economics sheet.

---

*The MVP is an experiment, not a product. If it cannot fail, it is not a test. Want to build the prototype fast and under pressure? Pair this week with [C4 · Crunch Labs Hackathons](../../../C4-Crunch-Labs-Hackathons/). If you find errors in this material, open an issue or send a PR — future founders will thank you.*
