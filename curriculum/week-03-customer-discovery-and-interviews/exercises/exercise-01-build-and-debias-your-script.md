# Exercise 1 — Build & De-bias Your Interview Script

**Type:** Guided worksheet.
**Estimated time:** ~50 minutes.
**Output:** `discovery-dossier/interview-script.md` — a ready-to-use discovery script with a bias audit showing zero pitches and zero unrewritten leading/hypothetical questions.

---

## Why this exercise

Your script is the safety net you bring into every interview. A good script keeps you on the past, off your solution, and listening more than talking. A bad script bakes your bias right into the conversation, and then your "data" just echoes your hopes back at you. You'll write a script, then run it through a **bias audit** that forces you to inspect every single question — because the dangerous questions are the ones that *feel* fine.

This is not a one-off. You'll refine this script as you learn what works, and you'll carry it (and its descendants) all the way to the capstone.

---

## Step 1 — Reframe your idea as a problem (5 min)

You cannot interview about a solution. At the top of your file, write your idea as a **problem statement**, in the form:

> *People in [segment] struggle with [problem], which costs them [time / money / stress] when [trigger].*

Example: *"Independent dental clinics struggle to fill appointment slots after a late cancellation, which costs them a specialist's hourly revenue every time it happens."*

If you can only phrase your idea as "an app that…", stop and reframe. The problem is the subject of the interview; the app is none of the interviewee's business.

## Step 2 — Write the frame (5 min)

One or two sentences you'll open with. It must (a) say you're researching, (b) explicitly disclaim a pitch, and (c) ask permission to take notes.

> *"I'm researching how [segment] handle [problem]. I'm not selling anything — I genuinely just want to learn from your experience. Mind if I ask about how this works for you, and is it okay if I jot a few notes?"*

## Step 3 — Write 6–8 questions (20 min)

All anchored in **past behavior, cost, and workarounds**. Build them from these proven stems:

- "Walk me through the last time [problem] happened."
- "What did you do about it? What did that cost you — time, money, stress?"
- "What do you use today to handle this? How well does it work?"
- "What's the most frustrating part of how this works now?"
- "What have you already tried? Why did you stop / keep going?"
- "What do you currently pay — in tools, time, or people — to deal with this?"
- "What's the most annoying part of all this that I haven't asked about?" *(the surprise prompt)*
- "Who else has this problem that I should talk to?" *(referral + commitment signal)*

Order them roughly along the interview arc from Lecture 2: context → last-time story → workarounds/spend → surprise → referral.

## Step 4 — Run the bias audit (15 min)

This is the heart of the exercise. For **every** question, fill in the table. Be ruthless — most first drafts hide at least one hypothetical or leading question.

```markdown
## Bias audit
| # | Question | Leading? | Hypothetical? | Pitches solution? | Rewrite (if any flag is "yes") |
|---|----------|----------|---------------|-------------------|-------------------------------|
| 1 | Walk me through the last time X happened. | No | No | No | — |
| 2 | Wouldn't it be easier if there were one tool for this? | YES | YES | YES | "What do you use today, and what's missing from it?" |
| ... |
```

A question fails if it is **leading** (hints at the answer you want), **hypothetical** (about the future or an imagined scenario), or **pitches** (mentions or implies your solution). Any "yes" requires a rewrite in the last column. Don't delete the bad question from the audit — keeping it visible is the point; it trains your eye.

---

## Expected outcome

A committed file `discovery-dossier/interview-script.md` containing:

1. Your idea reframed as a one-sentence **problem statement**.
2. A non-pitch **frame** with a notes-permission ask.
3. **6–8 questions** anchored in past behavior, cost, and workarounds, including a surprise prompt and a referral ask.
4. A **bias audit table** covering every question, with at least one question caught and rewritten.

You should finish able to say: *every question in my script asks about something that actually happened, none of them hint at the answer I want, and none of them mention my solution.*

---

## Acceptance criteria

- [ ] File at `discovery-dossier/interview-script.md`, committed.
- [ ] Idea is stated as a **problem**, not a solution.
- [ ] A frame that disclaims a pitch and asks to take notes.
- [ ] 6–8 questions, all past/behavior/cost/workaround oriented.
- [ ] A surprise prompt and a referral ask are present.
- [ ] A bias audit covering **every** question.
- [ ] At least one question flagged and rewritten.
- [ ] **Zero** questions that pitch your solution.

---

## Hints

- If a question can be honestly answered "yeah, sounds good" or "probably," it's a hypothetical. Rewrite it to ask what *actually* happened.
- "Don't you hate…", "Wouldn't it be nice…", "Isn't it frustrating that…" are all leading. The customer should be the one to call it frustrating, unprompted.
- The solution stays in your pocket. Discovery interviews never show a mockup; that's a *validation* interview, weeks from now.
- A good test: hand your script to a cohort-mate and ask them to find the pitch. If they find one, your audit missed it.

---

*Next: capture each conversation with the [Exercise 2 write-up template](exercise-02-interview-writeup-template.md).*
