# Mini-Project — Build, Launch, and Decide on a Real MVP

> Build the smallest experiment that tests your single riskiest assumption, put it in front of real people, measure one metric against a threshold you set in advance, and make a named persevere-or-pivot decision. This is the **Week 5 capstone deliverable** — the line in the syllabus that reads: *"a built MVP (any fidelity) wired to one clear metric, plus the result and your persevere/pivot decision."*

This is not a thought experiment. By Sunday you must have *run* something real — a fake door cold strangers visited, a concierge service you delivered by hand, a prototype real users tapped through, a Wizard-of-Oz product people used. Words from interviews don't count here; this week is about manufacturing the cheapest *behavior* you can measure.

**Estimated time:** ~10 hours (≈2h design Tue, ≈3h build Wed, ≈3h launch+measure Thu–Fri, ≈2h decide+write Sat).

---

## Where this fits in the course

C25 compounds. Each week's deliverable becomes raw material for the next, and all of them feed the Week 10 pitch:

- **Week 2** gave you a triaged problem worth solving.
- **Week 3** gave you discovery interviews and a pattern — the *source* of your riskiest assumption.
- **Week 4** gave you a co-founder agreement, so the "who runs the MVP" question is settled.
- **Week 5 (this week)** turns the validated *problem* into a tested *solution signal*. The experiment record you produce here is **one of the six capstone artifacts** and supplies the "MVP / prototype that tests the riskiest assumption" line of the capstone rubric (20% of the final grade).
- **Week 6** takes your validated (or pivoted) concept into a lean canvas and unit economics.
- **Week 10** puts the result on a slide: *"We tested X, here's what real people did, here's our decision."*

Keep everything in your founder repo so the paper trail survives to demo day.

---

## What you will produce

A folder `mvp/` in your Week 5 repo containing:

1. **The artifact** — the actual thing you built or ran:
   - a fake door: a link to the live page + screenshots, and a note on the traffic source;
   - a concierge: a description of the by-hand process + the tracking sheet (anonymized);
   - a Wizard of Oz: a link/screenshots of the front end + a note on what was faked;
   - a clickable prototype: a Figma/share link + the moderated-session notes.
2. **`mvp/SPEC.md`** — your completed [MVP Spec Canvas](../exercises/exercise-02-mvp-spec-canvas.md) (hypothesis, type, metric, threshold, build plan, ethics check), committed *before* launch.
3. **`mvp/EXPERIMENT.md`** — your completed [Experiment Record](../exercises/exercise-03-experiment-record-template.md): the result vs. threshold with the real number, sample size, honesty checks, validated learning, and the **named persevere/pivot decision**.
4. **`mvp/measurement/`** — the raw evidence: the tracking sheet, analytics screenshot, form responses (anonymized), or session notes. The number in `EXPERIMENT.md` must be traceable to something here.

---

## Rules

- **You may** use any free or near-free no-code tool (Carrd, Tally, Google Forms, Figma, Framer, GitHub Pages, Notion, Airtable, a Stripe payment link) — or do it entirely by hand.
- **You may NOT** spend more than a few days building. If your MVP takes more than ~3 days, you scoped a product, not an experiment — shrink it. A build that swallows the week is an automatic fail of the "genuinely minimal" criterion.
- **You must** test the riskiest assumption you chose in Exercise 1 — not a safer side-feature you'd rather test.
- **You must** put it in front of the **real segment**. Friends, family, and cohort-mates are excluded from the metric (they bias it).
- **You must** set the threshold *before* launch (your git history proves it) and **not move it** afterward.
- **You must** stay honest and legal: don't charge for what you can't deliver, don't lie about what happens after a click, and protect any personal data you collect. (See the ethics check in the spec canvas.)
- **Zero code.** This is a founders course. If your riskiest assumption is genuinely technical, fake the feature or use the single-feature build only as a last resort — and even then, prefer no-code.

---

## Acceptance criteria

- [ ] An `mvp/` folder committed to your Week 5 repo with the four items above.
- [ ] `mvp/SPEC.md` was committed **before** the launch (the git timestamp predates the result), with a falsifiable hypothesis, one metric, and a pre-committed threshold.
- [ ] The MVP **actually ran** with real people from the target segment — not a plan, a *result*.
- [ ] `mvp/EXPERIMENT.md` reports the **real metric value vs. the threshold**, the **sample size**, and answers the three honesty checks (sample big enough? signal or noise? measured the deed?).
- [ ] The experiment tests the **stated riskiest assumption** (not a side feature).
- [ ] The build was **genuinely minimal** — days not weeks, near-zero cost. Note the actual time and cost.
- [ ] A clear, **named** persevere-or-pivot decision appears, written as a decision sentence (number → threshold → decision → direction).
- [ ] Raw evidence lives under `mvp/measurement/` and the headline number traces to it.
- [ ] The threshold was **not moved** after the result.

---

## Suggested order of operations

### Phase 1 — Design the experiment (Tue, ~2h)

1. Finish **Exercise 1** (riskiest assumption) and **Exercise 2** (MVP spec canvas).
2. Copy the completed canvas into `mvp/SPEC.md`. Commit it. **This commit, before you launch, is your proof the threshold wasn't moved.**
3. Set up `mvp/EXPERIMENT.md` from the [template](../exercises/exercise-03-experiment-record-template.md), filling sections 1–4 (hypothesis + locked threshold). Leave 5–8 blank.

### Phase 2 — Build the MVP (Wed, ~3h)

4. Build only what the canvas says — nothing more. Hardcode, fake, and hand-do everything you can.
5. Put the artifact (or a description + screenshots) under `mvp/`. Commit: `MVP artifact built`.
6. Set up your measurement: a tracking sheet, an analytics event, form responses, or session notes. Test that it actually records the deed.

### Phase 3 — Launch and measure (Thu–Fri, ~3h)

7. Put it in front of the real segment through the channel you named. Exclude friends/family/cohort.
8. Let it run for the window you committed to. Watch the number, but don't touch the threshold.
9. Capture the raw evidence into `mvp/measurement/`. Commit: `Measurement data`.

### Phase 4 — Decide and write it up (Sat, ~2h)

10. Complete `mvp/EXPERIMENT.md` sections 5–8 with the real number, sample size, and honesty checks.
11. Write the validated-learning paragraph and the **named decision sentence**.
12. Commit: `Experiment record + persevere/pivot decision`.

### Phase 5 — Polish (Sun, ~1h)

13. Make sure a stranger could open `mvp/` and understand, in two minutes, what you tested, what happened, and what you decided.
14. Confirm the SPEC commit predates the result; confirm the threshold is unchanged.

---

## Example shape of a finished `EXPERIMENT.md` (Maya)

```
Riskiest assumption: front desks will hand off same-day refills.
MVP type: concierge — texted waitlisted patients by hand for 2 clinics. ~6h, ~$8.
Hypothesis (locked): right if refill rate >= 30% across 2 clinics in 1 week.
Result: refill rate 45% (9 of 20 cancellations), n=2 clinics, 1 week. PASS.
  Honesty: sample modest but behaviorally deep; friends excluded; measured the deed.
Validated learning: moderate confidence front desks adopt and manual refill works.
Decision: PERSEVERE. "We refilled 45% against a 30% threshold, so we persevere
  to a willingness-to-pay test."
Next experiment: will a clinic pay $99/mo? Wizard of Oz + Stripe link, threshold 1 of 2.
```

A **pivot** example is equally good work:

```
Result: fake-door CTA 1.2% vs. 10% threshold, n=210 cold visitors. MISS.
Decision: PIVOT (customer-segment). "We converted 1.2% against a 10% threshold,
  so we pivot from solo therapists to group practices — who reported the pain far
  more acutely in interviews — and re-run the fake door."
```

A miss, honestly reported and pivoted, scores **higher** than a vague "it went well."

---

## Rubric

| Criterion | Weight | What "great" looks like |
|---|---:|---|
| MVP tests the stated riskiest assumption | 25% | The experiment targets the load-bearing belief, not a comfortable side-feature |
| Threshold set before launch (and not moved) | 15% | Git history shows `SPEC.md` committed before the result; the number is unchanged |
| Ran with the real segment | 15% | Real people from the actual market touched it; friends/family excluded |
| Result reported honestly against the threshold | 20% | Real number, sample size, and the three honesty checks — a miss reported as a miss |
| Genuinely minimal build | 10% | Days not weeks, near-zero cost; faked/hand-did everything possible |
| Named persevere/pivot decision | 15% | A decision sentence with metric → threshold → decision → named direction |

---

## Stretch (optional)

- Run a **second** experiment on your next-riskiest assumption in the same week, with its own `EXPERIMENT.md`. Two clean loops in a week is elite pace.
- Add a **willingness-to-pay** signal: a Stripe payment link or fake pricing test layered on the fake door. Intent-to-pay is the strongest signal you can collect pre-product.
- Convert your concierge into a **Wizard of Oz**: build a thin front end so the experience looks automated, and note exactly what you faked and what it would cost to make real.
- Draft the **one pitch slide** this experiment will become at demo day: "We believed X. We tested it by Y. N real people did Z. We decided W." Week 10 will thank you.

---

## What this prepares you for

- **Week 6 (Business Models & Unit Economics):** the validated (or pivoted) concept you leave this week with becomes the subject of your lean canvas and unit-economics sheet. A pivoted concept is fine — it's a *better-aimed* canvas.
- **Week 7 (Go-to-Market):** the channel you used to reach the segment this week is your first data point on which acquisition motion fits.
- **Week 10 (Pitch + Demo Day):** "the MVP tested the riskiest assumption, with a recorded result" is worth 20% of your capstone grade and is the slide investors lean in for. You are building that slide's evidence right now.

---

## Submission

When done:

1. Push your Week 5 repo with the `mvp/` folder (SPEC, EXPERIMENT, artifact, measurement).
2. Confirm `mvp/SPEC.md`'s commit timestamp predates your result, and the threshold is unchanged.
3. Make sure a stranger can read `mvp/EXPERIMENT.md` and know what you tested, what happened, and what you decided — in under two minutes.
4. Post the repo link in your cohort tracker. You ran a real experiment on a real idea. Show it.

*Next: [Week 6 — Business Models & Unit Economics](../../week-06-business-models-and-unit-economics/).*
