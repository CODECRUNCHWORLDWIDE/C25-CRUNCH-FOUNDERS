# Exercise 2 — IP & Contribution Trap Audit (Worksheet)

> This is a **fill-in worksheet**, not code. Copy this whole file into your Week 9 repo as
> `exercises/exercise-02-ip-trap-audit.md`, replace every `<…>` and every `TODO`, and commit it.
> The audit you produce feeds directly into the mini-project checklist and the due-diligence challenge.

**Goal:** Map every asset your company depends on to *who made it*, *on whose account*, and *whether it's been assigned to the company* — and surface the three classic IP traps before an investor's lawyer does.

**Estimated time:** 50 minutes.

> **This is education, not legal advice.** Where the audit finds something binding (a prior-employer claim, an unassigned core asset), the action is "flag for the lawyer," not "decide it yourself."

---

## How to use this worksheet

1. **List every asset the company depends on.** Not just code — the brand/name, the logo, the domain, the content, the data, any designs. If the company would be hurt by losing it or by someone else claiming it, list it.
2. **For each, fill the row honestly.** Maker, the account/location it lives on, and whether there's a signed IP assignment covering it.
3. **Run the three trap checks.** Each is a yes/no with a fix.
4. **Write the triage.** What to fix this week (cheap, do it now), what to flag for the lawyer.

Be honest. A pretty audit that hides the messy parts is worse than useless — it gives you false confidence right up until diligence finds the thing you papered over.

---

## Part A — Asset inventory

> Replace the example rows with your own. Status legend: `ASSIGNED` (signed assignment in place) · `UNASSIGNED` (no assignment yet) · `UNSURE`.

| # | Asset | Who made it | Account / where it lives | Assignment status | Notes / risk |
|---|-------|-------------|--------------------------|-------------------|--------------|
| 1 | _e.g._ Core booking code | _e.g._ Co-founder B | _e.g._ B's personal GitHub | `UNASSIGNED` | Built before incorporation — Trap 1 |
| 2 | _e.g._ Logo & brand | _e.g._ Freelance designer | _e.g._ Designer's files | `UNSURE` | Paid in cash, no contract — Trap 2 |
| 3 | _e.g._ Reminder script | _e.g._ A friend, as a favor | _e.g._ Shared Drive | `UNASSIGNED` | No agreement — Trap 2 |
| 4 | _e.g._ Domain name | _e.g._ Me | _e.g._ My personal registrar account | `UNASSIGNED` | Should be in company's name |
| 5 | _e.g._ Landing-page copy | _e.g._ Me (ex-employer's hours?) | _e.g._ Company site | `UNSURE` | Wrote some at old job — Trap 3 |
| 6 | TODO | TODO | TODO | TODO | TODO |
| 7 | TODO | TODO | TODO | TODO | TODO |
| 8 | TODO | TODO | TODO | TODO | TODO |

*(Add rows until every company-critical asset is listed. Most early companies have 6–12.)*

---

## Part B — The three classic traps

For each trap, answer honestly and note the fix if it applies.

### Trap 1 — Personal-account / pre-incorporation work

> Code or assets built on a personal account, before the company existed or before any agreement was signed. By default the *maker* owns it, not the company.

- **Does this apply to you?** `YES / NO` → TODO
- **Which assets?** (reference the row numbers above) → TODO
- **Fix:** Signed IP assignment explicitly covering pre-incorporation work; move repos/accounts under the company.
  - **Cheap to fix now?** `YES / NO` → TODO
  - **Action + owner + date:** TODO

### Trap 2 — The "friend who helped" / unassigned contributor

> Anyone — friend, freelancer, favor — who contributed something you still use and never signed an assignment. They own their contribution.

- **Does this apply to you?** `YES / NO` → TODO
- **Who, and what did they make?** → TODO
- **Fix:** One-page IP assignment signed by each contributor (even favors), retroactively covering their work.
  - **Can you reach them?** `YES / NO / UNSURE` → TODO _(unreachable contributors are a real diligence problem — flag it)_
  - **Action + owner + date:** TODO

### Trap 3 — Prior-employer claim

> Work (or even the idea) created while employed elsewhere, especially under an "inventions made during employment belong to us" clause. The former employer may have a legitimate claim.

- **Did any founder build any company asset while employed elsewhere?** `YES / NO / UNSURE` → TODO
- **Who, what, and what did the prior employment agreement say?** → TODO
- **Fix:** Read the prior-employment agreement; if there's any doubt, this is **lawyer territory** — possibly a release from the former employer.
  - **`[NEEDS ADVISOR]`?** `YES / NO` → TODO
  - **Action + owner + date:** TODO

---

## Part C — Triage

### Fix this week (cheap, do it now)

> Things solvable with a one-page assignment, an account transfer, or a signature. List concrete actions.

- TODO
- TODO

### Flag for the lawyer (binding / uncertain)

> Things you should not decide yourself: prior-employer claims, anything where ownership is genuinely contested, anything jurisdiction-specific.

- TODO
- TODO

### Honest risk rating

> One line: how clean is your IP today, on a scale, and what's the single biggest exposure?

- **Overall:** `CLEAN / MINOR GAPS / SERIOUS GAP` → TODO
- **Biggest single exposure:** TODO

---

## Acceptance criteria

- [ ] Part A lists every company-critical asset with maker, account/location, and assignment status.
- [ ] All three traps in Part B are explicitly checked (YES/NO), with a fix noted for each that applies.
- [ ] Part C separates "fix this week" from "`[NEEDS ADVISOR]`" and gives an honest overall risk rating.
- [ ] At least one concrete action has an owner and a date.
- [ ] Committed to your Week 9 repo.

---

## Hints

- **The brand and the domain count.** Founders obsess over code and forget the company name might infringe a trademark, or the domain sits in a personal account. List them.
- **"It's just a favor" is exactly the trap.** The friend-who-helped case feels too small to bother with — until it isn't. The fix costs nothing today. Do it.
- **If Trap 3 is even slightly "unsure," flag it.** Prior-employer IP is the one trap that can be genuinely unfixable, so it's the one most worth surfacing early.

---

*Next: capture your incorporation situation and options in the [incorporation decision canvas](exercise-03-incorporation-decision-canvas.md).*
