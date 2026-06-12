# Week 5 — Homework

Five problems that carry you from "I have a riskiest assumption" to "I have a result and a decision." The full set should take about **5 hours** beyond the lectures and exercises, with Problem 3 (the build + run) doubling as your mini-project work. Do everything in your Week 5 Git repo so each problem produces a timestamped commit you can point to later — the timestamps matter this week, because they prove your threshold preceded your result.

And keep interviewing toward ten. Every week of C25 you should be adding discovery interviews; the capstone needs at least ten, and a few of this week's MVP conversations can count if you genuinely dug into the past, not the pitch.

Each problem includes a **problem statement**, **acceptance criteria**, a **hint**, and an **estimated time**.

---

## Problem 1 — Assumption map

**Problem statement.** At `notes/assumption-map.md`, list every assumption your idea depends on (aim for **8+**), score each on uncertainty (1–5) and fatality (1–5), multiply for a risk score, and circle the riskiest. Then write one paragraph: *why is this the riskiest one, and which assumption did you most want to avoid testing?* (That second answer is usually a clue you're scoring optimistically.)

**Acceptance criteria.** File present; 8+ assumptions each scored on both axes; one circled as riskiest; the reflection paragraph included. Committed.

**Hint.** Adoption and willingness-to-pay are usually riskier than feasibility for non-deep-tech ideas. If your top row is "can we build it," double-check you're not just picking the comfortable one.

**Estimated time.** 30 min.

---

## Problem 2 — MVP spec + locked threshold

**Problem statement.** Fill in the [MVP Spec Canvas](./exercises/exercise-02-mvp-spec-canvas.md) for your idea at `notes/mvp-spec.md`: the falsifiable hypothesis, the chosen MVP type with a justification that it's the *cheapest* test, the single metric, and the threshold. Run the **vanity-metric red-team** on your own metric in writing ("could I hit this and learn nothing?"). Commit this **before** you build anything.

**Acceptance criteria.** File present; falsifiable hypothesis in the "we'll know we're wrong if…" form; exactly one metric; a threshold with a stated source (unit-economics floor / benchmark / gut check); the red-team answered honestly; MVP type justified as cheapest. Committed *before* the build commit.

**Hint.** If your build plan runs longer than ~3 days, you picked a product. Find the fake-door or concierge version. The threshold should be a number where, below it, you'd genuinely doubt the idea.

**Estimated time.** 50 min.

---

## Problem 3 — Build and run the MVP (build log)

**Problem statement.** Build your chosen MVP and run it with real people from the target segment. Keep a log at `notes/mvp-build-log.md`: what you built, the free/low-cost tools used, how long it took, the actual cost, who you put it in front of and through what channel, and a link or screenshot of the artifact. This is also your mini-project artifact.

**Acceptance criteria.** File present; artifact linked or screenshotted; build time and cost recorded (days not weeks, near-zero cost); the real segment named (friends/family/cohort excluded); it actually *ran* (a result exists, not just a plan). Committed.

**Hint.** Carrd, Tally, Google Forms, Figma, a Stripe payment link, or doing it by hand all count. Build less than feels comfortable. Test that your measurement actually records the *deed* before you launch.

**Estimated time.** ~2.5 hours (this is the week's build, shared with the mini-project).

---

## Problem 4 — Result, learning, and decision

**Problem statement.** At `notes/mvp-result.md`, complete the [Experiment Record](./exercises/exercise-03-experiment-record-template.md): the real metric value vs. your pre-set threshold, the sample size, the three honesty checks (sample big enough? signal or noise? measured the deed?), a validated-learning paragraph, and a **named** persevere-or-pivot decision written as a decision sentence (number → threshold → decision → direction).

**Acceptance criteria.** File present; real number vs. threshold stated; sample size noted; honesty checks answered; validated-learning paragraph with a confidence level; an explicit, named persevere/pivot decision tied to the number. Threshold unchanged from Problem 2. Committed.

**Hint.** A miss is not the week failing — it's the week *working*. A clean, honestly-reported, well-named pivot scores higher than a mushy "it went okay." Don't move the threshold.

**Estimated time.** 45 min.

---

## Problem 5 — Reflection: what would you tell an investor?

**Problem statement.** Write a 250–350 word reflection at `notes/week-05-reflection.md` answering, each in its own paragraph:

1. What was your riskiest assumption, and did the experiment validate or invalidate it? What surprised you?
2. Where were you tempted to cheat — pick the easy assumption, move the threshold, count a vanity metric, or run it on friends? Did you catch yourself?
3. Draft the **one sentence** you'd say to an investor at demo day about this experiment: *"We believed X; we tested it by Y; N real people did Z; we decided W."*
4. What's the next experiment, and why is *that* now the riskiest thing?

**Acceptance criteria.** File present, 250–350 words; each of the four prompts addressed in its own paragraph; the demo-day sentence is concrete and number-bearing. Committed.

**Hint.** This is for *you* and for Week 10. Be honest about the temptations — naming them is how you resist them next time. Future-you, building the pitch deck, will be grateful for the one-sentence draft.

**Estimated time.** 25 min.

---

## Time budget recap

| Problem | Estimated time |
|--------:|--------------:|
| 1 — Assumption map | 30 min |
| 2 — MVP spec + threshold | 50 min |
| 3 — Build and run | 2 h 30 min |
| 4 — Result + decision | 45 min |
| 5 — Reflection | 25 min |
| **Total** | **~5 h 0 min** |

---

## Grading rubric

Each problem is scored 0–4. **Total: 20 points.** 16+ is a pass; below 12, redo the weakest problems before Week 6 — the unit-economics work assumes a real, honestly-evaluated result to build on.

| Problem | 4 — Excellent | 3 — Solid | 2 — Thin | 0–1 — Missing/wrong |
|---|---|---|---|---|
| **1 — Assumption map** | 8+ assumptions, both axes scored, riskiest defensibly chosen, honest reflection on the avoided one | 8+ scored, riskiest chosen | <8 or only one axis scored | Missing, or riskiest is obviously the easy one with no reasoning |
| **2 — MVP spec + threshold** | Falsifiable hypothesis, one metric, sourced threshold committed before build, red-team honest, cheapest type justified | Hypothesis + metric + threshold, mostly sound | Vague hypothesis or no clear threshold source | No falsifiable hypothesis, or threshold set after building |
| **3 — Build and run** | Minimal build, ran with the real segment, time/cost/channel logged, artifact shown | Built and ran, log mostly complete | Built but barely ran, or weeks-long build | Not built, or never put in front of real people |
| **4 — Result + decision** | Real number vs. threshold, sample size, honesty checks, validated learning, named decision sentence | Result + a decision, lightly justified | Result with no honest checks or unnamed decision | No result, or threshold moved to manufacture a "win" |
| **5 — Reflection** | All four prompts, candid on temptations, concrete number-bearing demo-day sentence | Four prompts addressed | 1–2 prompts skipped or generic | Missing or off-topic |

**Automatic deductions** (the integrity rules of the week):

- **−4** if the threshold was moved after the result, or `mvp-spec.md`'s commit does not predate the result.
- **−2** if the metric is a vanity metric (a cumulative total, an opinion, "they said they liked it") with no behavioral basis.
- **−2** if the experiment was run only on friends, family, or cohort-mates.

---

When you've finished all five, your mini-project's `mvp/` folder should be essentially complete. Push the repo and confirm a stranger can read your experiment record and understand what you tested, what happened, and what you decided. Then continue to [Week 6 — Business Models & Unit Economics](../week-06-business-models-and-unit-economics/).
