# Lecture 2 — Agreements, Operational Hygiene, and the Due-Diligence Self-Audit

> **Duration:** ~1 hour of reading + applying it to your own venture.
> **Outcome:** You can list the core agreements an early company needs and who signs each, set up genuinely minimal operational hygiene without over-engineering, and run a due-diligence self-audit that finds the problems while they are still cheap to fix.
>
> **Still education, not legal or tax advice. Anything binding goes to a licensed professional.**

Lecture 1 was about the *foundation* — the entity, founder stock, IP. This lecture is about the *connective tissue*: the handful of agreements that keep relationships clean, the small set of operational habits that keep the company auditable, and the self-audit that tells you whether the whole thing would survive an investor's lawyer. If Lecture 1 built the house, Lecture 2 makes sure the deed is signed, the utilities are in the company's name, and you can pass inspection.

The recurring test is the same one from the README:

> **Would this survive a pre-seed due-diligence pass?**

---

## 1. The core early agreements (few, but essential)

A young company needs surprisingly *few* documents. Founders who buy a 40-document "startup legal pack" and sign none of the right ones are worse off than founders who sign five and stop. Here are the few that matter, roughly in the order you need them.

### 1.1 The founders' agreement

This is your **Week 4 draft, papered properly.** It captures:

- **Roles and titles** — who's CEO, who owns what function.
- **Decision rights** — who decides what, and how ties break (especially in a 50/50).
- **Equity split** — the percentages, now backed by issued stock.
- **Vesting** — the four-year/one-year-cliff schedule, now a real restricted-stock/vesting agreement.
- **What happens if a founder leaves** — the repurchase mechanics, voluntarily or not.

The Week 4 document was the *thinking*. At incorporation, a lawyer turns it into binding stock-purchase and vesting agreements. The thinking is the hard part; you already did it. **Bring the draft to the lawyer — don't make them extract it from scratch on the clock.**

### 1.2 IP / invention assignment

Every founder and every contributor signs one (Lecture 1, §7). This is non-negotiable and it is the cheapest insurance you will ever buy. The agreement says: *anything I create that's relevant to the company belongs to the company.* Sign these:

- At incorporation, for all founders (covering pre-incorporation work explicitly).
- Before any contractor or employee starts work — *embedded* in their agreement, see below.
- Retroactively, for anyone who already contributed and never signed (chase these down now).

### 1.3 Advisor agreements

If you take on advisors — experienced people who help in exchange for a small slice of equity — paper it. Define **what they actually do** (it should be specific, not "be available"), **how much equity** (typically a fraction of a percent, vesting over a year or two), and **for how long**. The FAST (Founder/Advisor Standard Template) is a free, widely used framework (see `resources.md`). The trap here is giving away meaningful equity to "advisors" who do nothing; specificity protects you.

### 1.4 Contractor and employee agreements

Anyone you *pay* — a freelance designer, a part-time developer, your first hire — should have an agreement that includes, at minimum:

- **Scope and payment** terms.
- **IP assignment** — their work belongs to the company. (This is the same trap as Lecture 1's "friend who helped," prevented up front.)
- **Confidentiality** — they won't leak your internal information.

For employees there's more (at-will/notice terms, benefits, local labor law), and that's lawyer territory — but the IP + confidentiality core is universal. **The single most important clause in any contractor agreement is the IP assignment.** A contractor with no signed assignment owns what they built for you.

### 1.5 NDAs — used sparingly and deliberately

The Non-Disclosure Agreement is the most *over-requested* document by inexperienced founders. Reality:

- **Most early conversations do not need one.** Discovery interviews don't. Most investor conversations don't — in fact, **asking an investor to sign an NDA before you pitch signals inexperience**, and many will simply decline. Investors see hundreds of decks; they won't take on legal liability to hear yours.
- **NDAs are appropriate** for genuinely sensitive, specific situations: sharing detailed financials or proprietary technical specifics with a partner or potential acquirer, or before deep due diligence.

The skill is restraint. Reserve NDAs for the few situations that truly warrant them, and don't let an over-eager NDA request brand you as a first-timer.

### Agreements at a glance

| Agreement | Who signs | When | If you skip it |
|-----------|-----------|------|----------------|
| Founders' agreement (stock + vesting) | All founders | At incorporation | "Dead equity," disputes, un-fundable cap table |
| IP / invention assignment | All founders + every contributor | At incorporation; before any work | Company doesn't own its own product; diligence killer |
| Advisor agreement | Each advisor | When the advisor starts | Equity given for nothing; unclear expectations |
| Contractor / employee agreement (with IP + confidentiality) | Each contractor/hire | Before they start | Unassigned IP; leaked information |
| NDA | The few who truly need it | Only when genuinely sensitive | (Usually fine to skip) / over-using it signals inexperience |

---

## 2. Operational hygiene — the short, deliberate list

Ops at this stage is **not** about looking like a real company. It's about *not creating messes that cost you later.* Resist the urge to buy a dozen SaaS subscriptions; a two-person team running like a 200-person one is wasting time and money. Here is the genuinely minimal list.

### 2.1 A dedicated business bank account

The first and most important ops move. Open a separate account in the company's name and **never mix personal and company money.** Commingling is dangerous for two reasons:

1. **It pierces limited liability.** The protection you incorporated for evaporates if a court sees you treating the company's money as your own (Lecture 1, §1.1).
2. **It makes bookkeeping and taxes a nightmare.** Untangling "was that coffee a business expense?" across a personal account, months later, at tax time, is misery — and it makes your books untrustworthy in diligence.

The rule is absolute and easy: company money in the company account, personal money in your personal account, and if you need to put your own money in, do it as a documented loan or contribution, not by paying a vendor from your personal card.

### 2.2 Basic bookkeeping from day one

Track every dollar in and every dollar out, starting *now*. Early on, a clean spreadsheet is genuinely enough; soon a low-cost tool (Wave is free; QuickBooks/Xero are cheap) earns its keep. What matters is not the tool but the *habit*: a complete, categorized record of income and expenses. This is what lets you answer an investor's "show me your burn" without a panicked weekend of receipt archaeology — and it's what your accountant needs to do your taxes and your elections.

The minimum a spreadsheet needs is six columns and a habit of filling them in weekly:

| Date | Description | Category | In | Out | Running balance |
|------|-------------|----------|---:|----:|----------------:|
| 2026-06-01 | Pilot clinic A — first month | Revenue | 200 | | 200 |
| 2026-06-02 | Cloud hosting | Infrastructure | | 40 | 160 |
| 2026-06-03 | Domain renewal | Infrastructure | | 12 | 148 |
| 2026-06-05 | Pilot clinic B | Revenue | 200 | | 348 |

A handful of categories is plenty early — Revenue, Infrastructure, Software/Tools, Contractors, Legal/Accounting, Other. The point isn't accounting elegance; it's that when an investor asks "what's your monthly burn and runway?", the answer is a thirty-second lookup, not a two-day reconstruction. **Burn** is your average monthly net-out; **runway** is cash-in-bank divided by burn. Those two numbers come straight off a kept spreadsheet and are dead on arrival without one.

### 2.3 One organized document store

Every signed agreement, the cap table, the formation documents, the IP assignments, the founder agreements — in **one organized place** (a shared "Company Documents" drive folder is fine). When an investor's lawyer asks for "the IP assignments and the cap table," the answer should be a link, not a two-day scramble. Disorganization *reads as* risk in diligence even when nothing is actually wrong.

A folder structure that handles diligence with zero scrambling:

```
Company Documents/
├── 01-Formation/        (charter/articles, bylaws, formation certificate)
├── 02-Equity/           (cap table, founder stock agreements, vesting, option grants)
├── 03-IP/               (every signed IP assignment — founders + contributors)
├── 04-Agreements/       (advisor, contractor, employee, NDAs)
├── 05-Fundraising/      (SAFEs/notes, term sheets, investor agreements)
├── 06-Finance/          (bank statements, bookkeeping, tax filings)
└── 07-Compliance/       (the deadline calendar, annual filings, the 83(b) confirmation)
```

When the lead investor's lawyer emails "send your cap table, IP assignments, and formation docs," you send three folder links and look like a company that has its act together — because you do. The structure is the artifact; building it now means it's never a fire drill later.

### 2.4 A compliance / deadline calendar

A shared calendar (or a section of your checklist) listing every **filing and tax deadline**, especially:

- The **time-sensitive tax election** from Lecture 1 (the 83(b)-style election) — this one has the shortest, most unforgiving deadline and the worst consequence for missing it.
- Annual entity filings / franchise taxes (these exist even at zero revenue in many jurisdictions).
- Any local registrations.

Your accountant can enumerate these for your specific entity and location. You maintain the calendar. Missing a deadline because "nobody was tracking it" is the most embarrassing, most preventable failure mode.

A concrete compliance calendar for a freshly incorporated US C-corp might look like this (yours will differ by jurisdiction — get the exact list from your accountant):

| When | Item | Consequence of missing it |
|------|------|---------------------------|
| Within 30 days of stock grant | File the 83(b) tax election | Irreversible; potentially large future tax bill |
| Annually (state deadline) | Franchise tax / annual report | Penalties; entity can fall out of "good standing" |
| Annually (federal/state) | Corporate income tax return | Penalties and interest |
| Quarterly (if you have payroll) | Payroll tax deposits | Penalties; personal liability in some cases |
| As they occur | Update cap table for any SAFE / option grant | Cap table drifts from reality; diligence pain |

The point of writing it down isn't bureaucracy — it's that "good standing" with the registry is a literal status that investors check in diligence, and it lapses silently if a single annual filing is missed. A founder who can pull up this calendar and show every item current is signaling competence; one who says "uh, I think my accountant handles that?" is signaling risk.

### 2.5 The ops minimum, summarized

```
Form entity (with advisor)
  → Issue founder stock with vesting
  → Everyone signs IP assignment
  → File the time-sensitive tax election (with accountant, on deadline)
  → Open a dedicated business bank account
  → Start basic bookkeeping
  → Store signed docs + cap table in one place
  → Note every tax/filing deadline on a shared calendar
```

Everything beyond this is premature until the company is meaningfully bigger. If a tool or process isn't on this list and isn't solving a problem you actually have *today*, you don't need it yet.

---

## 3. The due-diligence self-audit

Here is the skill that ties the whole week together and previews Week 10: **read your own company the way an investor's lawyer will, before they do.**

When you raise even a small pre-seed, a competent investor (or their counsel) runs a diligence pass: a structured check that the company is what you say it is and owns what it claims. The findings either get ticked or flagged. A flagged item stalls or kills a deal. The brilliant move is to **run that checklist on yourself first**, find your own problems while they're cheap, and fix them — so that when the real diligence comes, it's clean.

Here is a representative early-stage diligence checklist. For each item, the honest answer is "yes, here's the document" or it's a finding.

### Corporate & ownership

- [ ] The entity is properly formed, in good standing, with current filings.
- [ ] The **cap table** is accurate and matches the issued stock (your Week 8 model, now real).
- [ ] Founder stock was **issued** and is **subject to vesting with a cliff** (Week 4 → real agreement).
- [ ] There is no "**dead equity**" — no large holder who left and kept un-vesting shares.
- [ ] Any SAFEs/notes are documented, and you understand their conversion (Week 8).

### Intellectual property

- [ ] **Every founder** has signed IP assignment, covering pre-incorporation work.
- [ ] **Every contractor/contributor** (paid or favor) has assigned their work.
- [ ] No founder built the core product under a **prior employer's** "we own your inventions" clause without a release.
- [ ] The company name/brand doesn't obviously infringe an existing trademark (you did a basic search).
- [ ] Domains, accounts, and repositories are owned by the **company**, not a personal account.

### Operations & finance

- [ ] A **dedicated** business bank account exists; no commingling.
- [ ] **Books** are clean enough to show income, expenses, and burn on request.
- [ ] **Tax elections** (the 83(b)-style one) were filed on deadline, or you can account for them.
- [ ] Compliance/filing deadlines are tracked and current.

### People & agreements

- [ ] A **founders' agreement** exists with roles, decision rights, equity, and vesting.
- [ ] Any **advisors** have agreements with defined scope and (vesting) equity.
- [ ] Contractors/employees have agreements with **IP + confidentiality**.

Run this on your concept. **Every box you can't honestly tick is a finding** — and finding it now, in week 9, with a one-page assignment or a calendar entry as the fix, is the entire point. Finding it during a real round, with a wire pending and a clock running, is how rounds die. This self-audit *is* the Week 9 challenge, and the triaged findings feed directly into your mini-project checklist.

---

## 4. A timeline: when each agreement and ops step actually happens

Founders often ask "do I need *all* of this on day one?" No. The agreements and ops steps have a natural order, keyed to events in the company's life, not to the calendar. Here's the realistic sequence for a typical two-founder, venture-track startup. Map your own events onto it.

| Trigger event | What you do | Why then |
|---------------|-------------|----------|
| **Deciding to do this together** | Founders' agreement *terms* (Week 4 draft) | Before resentment makes the equity conversation impossible |
| **Incorporating** | Form entity; issue restricted founder stock; all founders sign IP assignment | The promise becomes ownership; the company starts owning its IP |
| **Within 30 days of stock grant** | File the time-sensitive tax election (with accountant) | Hard, irreversible deadline (the 83(b) window) |
| **Before the first dollar moves** | Open the dedicated bank account; start bookkeeping | No commingling, ever; clean books from transaction #1 |
| **Before any contractor/hire starts** | Their agreement, with IP + confidentiality, *signed first* | Unassigned work is the trap; prevent it up front |
| **When you take on an advisor** | Advisor agreement, defined scope + vesting equity | Equity for nothing is the failure mode; specificity prevents it |
| **When you raise** | SAFE/round documents (with a lawyer) | The legal instrument the Week 8 math runs on |
| **Ongoing, monthly** | Update books, file on the compliance calendar | Diligence-ready at all times, not in a panic |

Notice that almost nothing here is "do it all at once." The discipline is doing each step *when its trigger fires* — and never *after*. The contractor agreement signed *before* they start is a non-event; the same agreement chased down *after* they've built something is a negotiation.

## 5. SAFEs in practice — what actually gets signed

Lecture 1 introduced the SAFE conceptually. Here's the operational reality, because it's the legal event Weeks 8 and 9 have been building toward.

When you raise on a SAFE:

1. **You and the investor agree the terms** — primarily the **valuation cap** (and possibly a **discount**) and the amount. This is often a short conversation, not a 40-page negotiation; that simplicity is the SAFE's whole appeal.
2. **You use a standard SAFE document** — YC's post-money SAFE is the de facto template; most investors recognize it and won't re-paper it. (Read it; see `resources.md`.) Using the standard doc signals you know what you're doing and keeps legal costs near zero.
3. **The investor wires the money; you both sign.** The SAFE is now a binding contract: the investor has paid for the *right to stock later*, at your next priced round, on the cap/discount terms.
4. **You record it on the cap table** — as an outstanding SAFE, not yet stock. Your Week 8 model showed how it will convert and dilute. The actual conversion happens at the priced round, often a year or two out.

What can go wrong, and why this week matters:

- **Stacking SAFEs without modeling them.** Raise three SAFEs at different caps and you can dilute yourself far more than you realized at the priced round. The Week 8 model is exactly what prevents this surprise — keep it current as each SAFE comes in.
- **Raising on a messy company.** A SAFE on a company with unissued founder stock, unassigned IP, or a commingled bank account is a SAFE on a liability. The cleaner investor *will* do light diligence even on a SAFE round. This is why the self-audit (§3) precedes the raise.
- **Promising the same equity twice.** Hand-shake "I'll give you 5%" to an advisor *and* a SAFE to an investor, both un-modeled, and the cap table no longer adds up. Everything routes through one cap table; the cap table is the source of truth.

The through-line: the SAFE is *simple as a document* precisely because the company underneath it is *clean*. The simplicity you want at fundraising time is bought by the boring hygiene you do this week.

## 6. The cost of skipping this — three short failure stories

Abstractions don't motivate; consequences do. Three composite stories from how this actually goes wrong:

- **The dead-equity round that died.** Two founders, 50/50, no vesting. One left at month four. Eighteen months later the remaining founder had real traction and a verbal term sheet — which evaporated the moment the investor saw 50% of the company owned by someone who'd been gone for over a year. There was no clean fix; the absent co-founder had no incentive to give equity back. *Cost of prevention: one vesting agreement at incorporation.*

- **The contractor who couldn't be found.** A startup's core onboarding flow was built by a freelancer paid via an invoice, no IP assignment. During acquisition diligence two years later, the acquirer's lawyer flagged it. The freelancer had moved, changed emails, and — once located — wanted a payment to sign the assignment they should have signed for free at the start. *Cost of prevention: one paragraph in the original contract.*

- **The commingled books.** A solo founder ran everything through a personal account "to keep it simple." When an angel offered to invest, the founder couldn't produce clean books showing burn and runway, and spent a frantic week reconstructing two years of mixed personal-and-business transactions. The angel, unimpressed by the chaos, passed. *Cost of prevention: a separate bank account on day one.*

Every one of these was cheap to prevent and expensive-to-unfixable to cure. That asymmetry is the entire argument for doing the boring work now.

---

## 7. The boundary, one more time

The rule from Lecture 1 governs everything here too:

> **Do the organizing yourself. Get the binding documents and the tax/entity decisions from a licensed professional.**

You draft the founders' terms, assemble the checklist, keep the books, maintain the document store and the deadline calendar, and run the self-audit. You get a **lawyer** for the binding agreements (founder stock/vesting, IP assignment, advisor, employee, the round paperwork) and an **accountant** for the entity/tax decisions and the deadline-bound elections. Showing up to those meetings with a tidy document store, a current cap table, and a triaged list of findings turns a vague, expensive engagement into a focused, cheap one.

That preparation — the checklist, the self-audit, the questions — is exactly what you build in this week's exercises, challenge, and mini-project.

One practical caution on the boundary: **don't let "I'll get a lawyer for that" become a reason to do nothing.** Founders sometimes use "that's a legal question" to defer every uncomfortable item indefinitely, and then a year passes with no entity, no IP assignments, and a commingled account. The boundary cuts both ways: the *binding* work waits for a professional, but the *organizing* work — opening the bank account, chasing the easy signatures, building the document store, writing the calendar — is yours to do today, and most of it is free. Do the DIY column now; book the professional for the rest. The failure mode isn't doing the lawyer's job; it's using the lawyer as an excuse to do none of yours.

---

## 7a. The contributor-onboarding reflex

Most IP traps are a *process* failure, not a one-time mistake: there was no step that said "before this person touches anything, they sign." Install that step now and you never create Trap 2 again. The reflex, for *anyone* who will contribute anything the company relies on — co-founder, hire, contractor, intern, or favor-doing friend:

1. **Before they start**, they sign an agreement that includes **IP assignment** and **confidentiality**. Before, not after. "Before" is a non-event; "after" is a negotiation.
2. **Give them company accounts**, not personal ones — company GitHub org, company email, company drive. Work created in the company's accounts is unambiguous; work on a personal account is a future cleanup.
3. **Record it** — add them and their signed agreement to the document store, and update the cap table if any equity is involved.
4. **Off-boarding mirrors on-boarding** — when someone leaves, revoke access, confirm the assignment covers everything they made, and (for equity holders) handle vesting/repurchase per the agreement.

This four-step reflex costs minutes per person and eliminates the single most common diligence finding. Founders who treat it as bureaucracy relearn its value the expensive way during a round. Make it muscle memory: *no contribution before a signature.*

## 7b. Choosing your minimal viable legal stack

There's a temptation, once you start reading about all this, to over-build — to buy the 40-document legal pack, the four SaaS subscriptions, the premium cap-table tool, on day one. Resist it. The right early stack is *minimal viable*: the fewest documents and tools that keep you clean and fundable, and nothing more. A useful decision rule:

> **Add a document or tool only when a real trigger fires — never "to be safe" or "to look legit."**

Concretely, for a typical pre-revenue, two-founder startup:

| You need now | You don't need yet |
|--------------|--------------------|
| Founder stock + vesting agreements | An employee handbook |
| IP assignment for both founders | A trademark filing (clear the name; file later) |
| A dedicated bank account | Multiple bank accounts / corporate cards per person |
| A bookkeeping spreadsheet (or free tool) | Premium accounting software |
| One document-store folder | A document-management SaaS |
| A simple cap table (your Week 8 sheet) | A paid cap-table platform |
| A compliance/deadline note | A dedicated compliance tool |

The right-hand column isn't *wrong* — it's *premature*. Each item earns its place when a real trigger arrives: the first employee (handbook), the first real brand investment (trademark), the first multi-holder cap table (cap-table tool). Buying ahead of the trigger wastes money and time you don't have, and — worse — creates the illusion of progress. A two-person team with clean books in a spreadsheet is in far better shape than one drowning in tools it bought to feel like a real company.

The honest test for any addition: *what problem that I have today does this solve?* If the answer is "none yet," it goes on a "later" list, not in your stack.

---

## 8. Recap

You should now be able to:

- List the core early agreements (founders', IP assignment, advisor, contractor/employee, NDA) and say who signs each and when.
- Explain why NDAs are over-requested and when they're actually appropriate.
- Set up the genuinely minimal ops stack: dedicated bank account, basic bookkeeping, one document store, a deadline calendar — and explain *why* commingling is dangerous.
- Run a due-diligence self-audit across corporate, IP, ops/finance, and people, and treat each un-tickable box as a finding to fix early and cheaply.
- Sequence the agreements and ops steps to their natural triggers, and install the "no contribution before a signature" onboarding reflex.
- Describe what actually gets signed in a SAFE round and why a clean company is what keeps that document simple.
- Choose a minimal viable legal stack — adding a document or tool only when a real trigger fires, never to "look legit."
- Draw the line between your organizing work and a professional's binding work — and avoid using "I'll get a lawyer" as an excuse to do none of your own.

These five skills, plus Lecture 1's incorporation and IP foundations, are everything you need to produce a clean, defensible, fundable company on paper. The remaining work this week — the exercises, the challenge, the mini-project — is applying them to *your* venture until the answer to "would this survive diligence?" is honestly *yes*.

---

*Back to the [week overview](../README.md). Now do the [exercises](../exercises/README.md) — draft your advisor questions, run your IP-trap audit, and fill in your incorporation decision canvas — then take the [challenge](../challenges/README.md) and build the [checklist](../mini-project/README.md).*

*This is education, not legal or tax advice. Confirm every binding or jurisdiction-specific item with a licensed professional.*
