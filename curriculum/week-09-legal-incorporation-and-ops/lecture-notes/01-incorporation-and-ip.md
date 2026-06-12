# Lecture 1 — Incorporation, Founder Stock, and IP

> **Duration:** ~1.5 hours of reading + working through your own situation.
> **Outcome:** You can explain why and when to incorporate, name the common entity choices and the trade-offs at a high level, understand how founder stock and vesting actually get issued, recognize the existence of time-sensitive tax elections, and identify the three classic IP traps before they show up in due diligence.
>
> **This is education, not legal or tax advice. Entity rules, securities law, and tax elections are jurisdiction-specific and change. Every binding decision below routes to a licensed professional in your jurisdiction.**

If you only remember one sentence from this lecture, remember this:

> **Incorporation is the moment your company becomes a thing that can own assets, owe money, and be owned — separately from you.** Everything that follows — founder stock, vesting, IP, the bank account, the tax filings — is about making sure that "thing" is *clean*: that it clearly owns what it depends on, that its owners clearly own it, and that nothing is hiding on a personal laptop or a former employer's payroll waiting to detonate during diligence.

---

## 1. Why incorporate at all

People starting out usually picture incorporation as "filing some paperwork to look official." That undersells it. Incorporating creates a separate legal *person* — the entity — and that separateness buys you four concrete things:

### 1.1 Limited liability

This is the headline reason and the one most misunderstood. When you incorporate, the company's debts and legal risks are, by default, the *company's* — not yours personally. If the company signs a contract it can't honor, or gets sued, the claimant generally goes after the company's assets, not your house.

The crucial caveat: **limited liability is not a force field.** It can be "pierced." The fastest way to pierce it is to treat the company's money as your own — paying personal expenses from the company account, or company expenses from your personal card. (That's why Lecture 2's first ops rule is a dedicated bank account.) Fraud and personal guarantees also pierce it. So limited liability is real, but it is *conditional on you respecting the separation you just created.*

### 1.2 Ownership clarity

In Week 4 you reasoned out an equity split — say 55/45, or 50/50 with a tie-breaker — and a vesting schedule with a cliff. Right now that lives in a Google Doc. It is a *promise*, not a fact. Incorporation is where the promise becomes ownership: the company issues **stock**, and the cap table you modeled in Week 8 becomes the actual register of who owns what. Until you incorporate and issue stock, nobody literally owns anything. "We're 50/50" is a sentence, not a legal reality.

### 1.3 Fundraising readiness

Investors invest in *entities*. You cannot sell equity in a handshake. A SAFE (Week 8, and §8 below) is a contract between an investor and a *company* — it has to be a company. The moment you decide you will raise even a small pre-seed, you have decided you will incorporate first. There is no "raise now, incorporate later" path that a competent investor accepts.

### 1.4 Cleanliness

Contracts, payroll, taxes, intellectual property, the bank account — all of these need a clear *home*. Before incorporation, a contract you sign is signed by *you, personally*. The brand you build is owned by *whoever made it*. After incorporation, there is one obvious owner of all of it: the company. This is less dramatic than limited liability but it is what makes the company *auditable* — and auditability is exactly what diligence tests.

> **The honest counterweight.** Incorporating has real costs: formation fees, ongoing compliance filings, a registered agent in some jurisdictions, annual taxes that exist even at zero revenue, and the cognitive overhead of keeping the separation clean. For a founder still poking at an idea with no money and no co-founder, incorporating on day one is premature. The skill is timing, which is §2.

---

## 2. When to incorporate — and the asymmetric cost of getting it wrong

The honest answer is: **incorporate around the time money or partners enter.** More precisely, incorporate when any of these becomes true:

- You are about to **take money** — from a customer, and especially from an investor.
- You are about to **sign a real contract** in the company's name.
- You are **bringing on a co-founder** and want the equity split and vesting to be real, not a promise.
- You are about to **hire** anyone, contractor or employee.
- You are about to **build the core asset** with more than one person involved (so IP can be assigned to a real entity).

Now the asymmetry, because this is where founders get it wrong in both directions:

**Incorporating too early** mostly costs *money and overhead*: fees and filings before there is anything to protect. It is annoying but rarely fatal. You can always dissolve an entity you formed too soon.

**Incorporating too late** can create *unfixable messes*:

- Who owned the IP during the "informal" period? If two people built the product for six months before incorporating, and then one walks, the ownership of that pre-incorporation work is genuinely murky — and you'll be untangling it during a fundraise, under time pressure, with a lawyer on the clock.
- Did founder stock get issued and a vesting clock started? If you incorporate two years in and *then* issue stock, you may face a tax bill on stock that's now "worth something," and you've missed the short window to make the election that would have avoided it (§6).
- Did you take money or sign contracts personally that now need to be assigned to the company?

So the cost is asymmetric: too-early wastes money; too-late can cost you the round. **When in doubt, lean earlier — but the precise timing, and the precise structure, is an advisor question.** This week's job is to know the heuristic and bring it to a professional, not to guess.

---

## 3. Entity choices, at a high level

There are several common entity types, and the right one depends heavily on your **country, your state/region, your tax situation, and your fundraising plans.** Because this is genuinely jurisdiction-specific, the course deliberately does **not** prescribe one. Instead it teaches you the shape of the decision and the questions to bring.

Here are the broad shapes you'll hear named (conceptually — names and rules vary by country):

| Shape | What it is | Typical fit | Watch out for |
|-------|------------|-------------|---------------|
| **Sole proprietorship / nothing** | You, operating under your own name. No separate entity. | A side experiment with no money, no partners, no risk. | No liability protection; can't sell equity; messy if it grows. |
| **LLC (or local equivalent)** | A flexible limited-liability company. | Solo founders, lifestyle/bootstrapped businesses, consultancies. | Awkward for traditional venture equity (issuing stock, SAFEs, options). |
| **Corporation (e.g., US C-corp)** | A company taxed as its own entity, issuing shares. | Startups planning to raise venture money. Investors expect it. | More formality, double-taxation concerns at profit (rarely relevant early), ongoing compliance. |
| **Local startup-friendly forms** | Many countries have their own (e.g., a private limited company). | Founders raising locally. | The "US C-corp" advice in most blogs may not apply to you at all. |

The single most common piece of startup-legal folklore is "**just do a Delaware C-corp.**" For a US founder planning to raise from US venture investors, that's often the conventional default — investors and their lawyers are used to it, the SAFE and option-pool machinery is built for it. **But:**

- If you are **not** raising venture money, a C-corp's overhead may be pure cost — an LLC or local equivalent may fit better.
- If you are **not in the US**, "Delaware C-corp" may be actively wrong, or it may mean a "flip" structure that's complex and expensive — a real, situation-specific decision for a cross-border lawyer.
- If you are **solo and bootstrapping**, the venture-default machinery is overkill.

So the questions you bring to an advisor are:

1. **Given my location, my tax situation, and my fundraising plans, what entity fits?**
2. **What are the tax implications, and are there elections with deadlines I must not miss?**
3. **What does formation cost, and what does ongoing compliance cost each year?**
4. **If I'm cross-border, do I need a structure that lets future investors invest the way they expect?**

Take those to a lawyer and an accountant. **Do not** copy what a blog said worked for a company in a different country with a different plan. This is the part of the week where the right move is explicitly *"ask a professional"* — and being able to ask precisely is the skill.

A note on **cost and speed**, because founders always ask: in the simplest cases (a single-jurisdiction US C-corp through a service like Stripe Atlas or Clerky), formation can be a few hundred dollars and a few days. But that headline number hides recurring costs — annual franchise taxes or registry fees that exist even at zero revenue, a registered agent in some jurisdictions, and the accountant time for the tax election and annual filings. And the *simplest case* is exactly the one a service handles well; a cross-border or non-standard situation is neither cheap nor fast, and trying to force it through a one-size service is how founders create the expensive messes. Budget for the recurring cost, not just the formation fee, and don't let a low advertised price lure you into the wrong structure.

---

## 4. What actually happens at incorporation (the mechanics)

When you incorporate, a sequence of things happens — usually within days, often through a service like Stripe Atlas or Clerky for US C-corps, or through a local lawyer/registry elsewhere:

1. **The entity is formed** with the registry: a name, a registered address/agent, formation documents (a charter / articles).
2. **Initial governance is set:** who the directors are, who the officers are (CEO, etc.), and the basic bylaws.
3. **Shares are authorized** (the company is allowed to issue, say, 10,000,000 shares) and a portion is **issued** to the founders — this is founder stock (§5).
4. **A founder may pay for that stock** (often a nominal amount, since the company is worth almost nothing on day one).
5. **An option pool** may be carved out for future hires (you modeled its dilutive effect in Week 8).
6. **Founders sign their stock-purchase and vesting agreements** (§5–6).
7. **Everyone signs IP assignment** (§7).

You do not need to memorize the order of operations of a specific jurisdiction. You need to understand that incorporation *is* this bundle — entity + governance + stock + vesting + IP — and that doing only the first part ("I formed an LLC!") while skipping the rest leaves you with a company that owns nothing and whose founders own nothing in a defensible way.

---

## 5. Founder stock and vesting at incorporation

This is where your **Week 4 equity split and vesting schedule become real.**

At incorporation, founders are **issued stock** representing the split you agreed: if it was 55/45, the founder gets 55% of the founder shares, the co-founder 45%. (The exact share *count* is arbitrary — what matters is the percentages and that they match your cap table.)

Crucially, that stock should be **subject to vesting** — typically the four-year schedule with a one-year cliff you reasoned through in Week 4. Mechanically, this usually means the stock is **restricted**: the company keeps a **repurchase right** over the unvested portion. If a founder leaves before the cliff, the company can buy back *all* their (zero vested) shares; if they leave after two years, the company can repurchase the ~50% still unvested. This is the entire protective point of vesting, made legally enforceable.

> **Why this matters concretely.** Imagine you and a co-founder incorporate 50/50 with *no* vesting. Six weeks in, your co-founder gets a job offer and walks — keeping 50% of your company forever, contributing nothing further. You now have a "dead" 50% shareholder on your cap table, which is close to un-fundable: no investor wants half the equity sitting with someone who left. Vesting with a cliff prevents exactly this. It protects the people who *stay* — including you. An equal split is a *decision*, and vesting is the safety belt on that decision.

A subtlety worth flagging: vesting also reassures *investors*. During diligence, "do the founders' shares vest, with a cliff?" is a standard question. "No" is a red flag. So vesting isn't only co-founder hygiene; it's fundraising readiness.

To make the mechanics concrete, here's how a standard 4-year/1-year-cliff schedule actually plays out for a founder granted 4,000,000 shares (the count is arbitrary; the percentages are what matter):

| When the founder leaves | Vested shares | What the company can repurchase | Outcome |
|-------------------------|--------------:|--------------------------------:|---------|
| Month 6 (before cliff) | 0 | All 4,000,000 | Leaves with nothing — exactly the protection |
| Month 12 (cliff hits) | 1,000,000 (25%) | 3,000,000 | Keeps a year's worth; the rest returns to the pool |
| Month 30 | 2,500,000 (~62.5%) | 1,500,000 | Keeps what they earned; the unvested 37.5% returns |
| Month 48 (fully vested) | 4,000,000 | 0 | Owns it all; vesting is complete |

After the cliff, vesting typically accrues **monthly** (1/48 of the grant per month). The cliff is the "all or nothing" gate at the front; the monthly accrual is the smooth slope after it. This is the structure investors expect to see on every founder's stock, and it's the structure your Week 4 reasoning becomes at incorporation.

One more nuance founders ask about: **acceleration.** Some agreements include "single-trigger" (vesting accelerates if the company is acquired) or "double-trigger" (accelerates only if acquired *and* the founder is let go) clauses. These are real and negotiable, but they're a refinement, not a Week-9 essential — flag them as a question for your lawyer rather than something to design yourself.

---

## 6. The time-sensitive tax election (know it exists; file it with a pro)

Here is the single most common, most expensive, *irreversible* founder mistake, and it lives in this lecture because it happens *at incorporation*:

When founder stock is **restricted** (subject to that repurchase/vesting), some tax systems treat it as if you receive the stock *as it vests* — and tax you on its value *at that time*. If the company succeeds, the stock is worth far more in year three than at incorporation, so vesting-as-you-go can create a growing tax bill on paper gains you can't sell.

To avoid this, many jurisdictions offer an election to be taxed **now**, while the stock is worth almost nothing, instead of later. In the US this is the famous **83(b) election**. The catch:

- It is **time-limited** — in the US, you have **30 days** from the stock grant. Miss it and it's gone.
- It is **irreversible**.
- It is **easy to get wrong** if you self-file.

**Your job this week is not to file it.** Your job is to *know it exists*, know that it has a hard deadline tied to your stock grant, and **route it to your accountant the moment you incorporate.** Put it on your compliance calendar (Lecture 2). If you are outside the US, ask your accountant for the local analogue — many countries have a "tax it now at near-zero value" mechanism with its own short window.

This is the cleanest example of the week's whole philosophy: a binding, irreversible, deadline-bound decision that you should *recognize and escalate*, not *attempt*.

---

## 7. IP assignment — the quiet killer

Now the trap that kills more fundable companies in diligence than any other.

**Default rule:** the person who *creates* something — writes the code, designs the logo, drafts the copy — owns it, unless they have assigned it to someone else (or it was made within the scope of certain employment relationships). Read that again. By default, **the company does not own the work the company depends on.** The *makers* do.

So the company needs **IP assignment** agreements: a signed document in which each founder and each contributor transfers ownership of their work to the company. Without it, the company is a shell that *uses* IP it doesn't own — and an investor's lawyer will find that in about ten minutes.

### The three classic traps

**Trap 1 — The personal-account / pre-incorporation code.**
A co-founder built the core product on their personal GitHub account, before the company existed, before any agreement was signed. Who owns that code? Not the company — the company didn't exist. The co-founder does, personally. If they later leave on bad terms, they may have a real claim over the thing your company is built on. *Fix:* sign IP assignment that explicitly covers pre-incorporation work, and ideally re-confirm ownership of the repository under the company.

**Trap 2 — The "friend who helped."**
Someone — a friend, a freelancer paid in pizza, a designer who did the logo "as a favor" — contributed something the company now relies on, and never signed anything. They own their contribution. Years later, when it matters (an acquirer's diligence, a dispute), that unassigned logo or that weekend script is a cloud on the company's title. *Fix:* get a one-page IP assignment signed by *everyone* who contributed anything you still use — even the favors. It's cheap now and unfixable-feeling later.

**Trap 3 — The prior-employer claim.**
A founder built the prototype — or even just the idea — while still employed somewhere else, especially at a big tech company with broad "inventions made during employment belong to us" clauses. The prior employer may have a legitimate claim on what you built. This one is the scariest because it can be *true* and *unfixable*. *Fix:* honestly examine your own (and your co-founders') prior-employment agreements *before* you build on anything questionable, and if there's doubt, get a lawyer to look — and sometimes to get a release from the former employer.

### Why it always surfaces at the worst time

All three traps are dormant until **due diligence.** An investor about to wire money — or an acquirer about to buy you — hires a lawyer to verify that the company *actually owns what it claims to own.* That lawyer pulls the IP assignments, the contributor list, and the founders' prior-employment situations. Every gap is a finding. Findings stall rounds; some kill them. The deal is six weeks from closing and suddenly there's an unsigned contractor from 18 months ago who can't be located.

**The fix is almost always cheap if done early and almost always painful if done late.** A one-page assignment signed today costs nothing. The same assignment chased down two years later, from someone who now realizes they have leverage, can cost real money or kill a deal. This is why Week 9's whole posture is *do the boring paperwork now.*

### 7.1 The brand dimension people forget

IP isn't only code. Your **company name and brand** are assets too, and they have their own cheap-now / expensive-later trap:

- **Clear the name before you commit to it.** Do a basic search of your jurisdiction's trademark registry and a plain web search before printing business cards and buying the domain. Discovering that another company in your space already owns your name *after* you've built brand equity around it is a painful, sometimes expensive rebrand.
- **Own the domain in the company's name**, not a personal registrar account that nobody else can access if you're hit by a bus.
- **Filing a trademark is usually a "later" task**, not a day-one one — but *clearing* the name is a day-one task. Don't conflate the two: clearing is cheap and urgent; filing is a deliberate, later spend once the brand is worth protecting.

The brand trap is gentler than the prior-employer one, but it's the most common thing founders forget to even check. Add "is our name actually available?" to your audit.

---

## 8. A first look at SAFEs as legal instruments (bridge from Week 8)

In Week 8 you modeled how a pre-seed round dilutes founders, including post-money SAFE math. Here's the legal-surface view, which matters this week because incorporation is what *enables* it.

A **SAFE (Simple Agreement for Future Equity)** is a short contract: an investor gives the company money *now*, in exchange for the right to receive stock *later*, when the company does a priced round. It is **not a loan** — there's no interest and no maturity date (that's a convertible note, the debt-flavored cousin). The two knobs that matter:

- The **valuation cap** — the maximum company valuation at which the investor's money converts to stock. A lower cap means the early investor gets *more* stock for their money (rewarding early risk).
- The **discount** — sometimes a percentage discount to the next round's price, instead of or alongside the cap.

What actually gets signed is a SAFE document (YC publishes the standard post-money SAFE openly — read it; see `resources.md`). The legal prerequisites: there must be a **company** to invest in (incorporation), the founders must **clearly own their stock** (issuance + vesting), and the company must **own its IP** (assignment). A SAFE on a company with murky IP and unissued founder stock is a SAFE on a mess.

The cap-table consequence is the post-money math you already did in Week 8: a post-money SAFE fixes the investor's *ownership percentage* at conversion, so the dilution lands cleanly on the founders and the option pool. The reason this lecture revisits it: **the legal cleanliness this week is what makes the financial model from Week 8 actually executable.** You can't wire money into a handshake.

---

## 9. Three founders, three different right answers

The single biggest mistake in startup-legal thinking is assuming there's one correct setup. There isn't — the right answer is a function of *your* situation. Here are three realistic founders from a typical C25 cohort, each with a *different* correct path. Read these and notice that copying any one of them onto the wrong situation produces a mess.

### Founder A — the venture-track US software team

Two co-founders in the US, building a B2B SaaS, planning to raise a pre-seed on a SAFE within nine months, then a seed within two years.

- **Entity:** the conventional venture default (a US C-corp) is genuinely a good fit — investors expect it, the SAFE and option-pool machinery is built for it, and the team's whole plan is the venture path.
- **Founder stock:** issued at incorporation, restricted, 4-year/1-year-cliff vesting, matching their Week 4 split.
- **The election:** they file the 83(b) within 30 days — *with their accountant* — because their stock is worth almost nothing now and they fully intend it to be worth a lot later.
- **The trap they hit:** one co-founder wrote the first prototype on a personal account before incorporating. Fix: explicit pre-incorporation IP assignment at formation. Cheap, done day one.

### Founder B — the solo bootstrapper

One founder, a profitable-from-month-one productivity tool, *no* intention of raising venture money — wants to own 100% and live off the cash flow.

- **Entity:** a C-corp would be pure overhead here. An LLC (or local equivalent) fits — simpler, cheaper, taxed in a way that suits a cash-flow business. The "always do a C-corp" advice would actively *cost* this founder money for benefits they'll never use.
- **Founder stock / vesting:** largely moot — solo, no co-founder to protect against, no investors to reassure. (If they later add a partner, *that's* when vesting enters.)
- **The election:** may not apply the same way; an accountant confirms.
- **The trap they hit:** they've been running the business through a personal bank account "to keep it simple." Fix: a dedicated business account *now*, before commingling corrupts the books and pierces the very liability protection they incorporated for.

### Founder C — the cross-border team

Two co-founders in two different countries, building a marketplace, wanting to raise from investors who are in a *third* country.

- **Entity:** this is genuinely hard and genuinely `[NEEDS ADVISOR]`. A "flip" structure (operating company in one country, a holding company where investors expect to invest) may be required — and it is expensive and easy to get wrong. The single worst move is to read a US blog and "just do a Delaware C-corp" without understanding the tax consequences in two other countries.
- **Founder stock / vesting:** still applies, but the *mechanics* differ by jurisdiction.
- **The election:** there may be an analogue in each founder's country, each with its own deadline. Two accountants, possibly.
- **The trap they hit:** the cross-border structure itself is the risk. Fix: a cross-border startup lawyer, early, before they've built a structure that's expensive to unwind.

**The lesson:** the entity, the election, and the agreements are not a checklist you copy — they're a *decision tree* keyed to your fundraising intent, your geography, and your team. This week teaches you to *locate yourself* on that tree and bring the right questions, not to memorize one path.

---

## 10. A founder FAQ for the things people always get wrong

**"Can't I just incorporate later when I actually need it?"**
Sometimes, but the costs are asymmetric (§2). Too-late risks unfixable IP and tax messes. If money or a co-founder is near, lean earlier.

**"Do I really need vesting if I trust my co-founder?"**
Yes — *especially* then. Vesting isn't a sign of distrust; it's the safety belt everyone wears so that an early, unforeseeable departure doesn't leave dead equity on the cap table. Trust is exactly why it's easy to agree to now and impossible to add after a falling-out.

**"My friend helped a little — surely that's not a real IP issue?"**
It's *the* classic real issue (Trap 2). The fix is a one-page signature today and an unfixable cloud on your title later. Do it now.

**"Should I patent my idea before I tell anyone?"**
Almost certainly not at this stage. Most early software startups never patent; speed and execution matter more than a patent. (Trademark on your name is a more common early concern.) If you genuinely have patentable, defensible technology, that's a specific lawyer conversation — not a default move.

**"Can I file the tax election myself to save money?"**
You *can*, and people do — but it's irreversible, deadline-bound, and easy to botch. The cost of an accountant double-checking it is trivial against the cost of getting it wrong. Route it to a pro.

**"An investor wants to invest — do I need to incorporate first?"**
Yes. There is no path where an investor wires money into a person instead of a company. Incorporation is a prerequisite to the SAFE, not a follow-up.

---

## 11. The boundary — what you do vs. what a professional does

A useful rule that runs through the whole week:

> **Do the organizing yourself. Get the binding documents and the tax/entity decisions from a licensed professional.**

You can and should, yourself:

- Reason through your entity *options* and write down your situation and plans.
- Draft your founders' agreement terms (Week 4) and assemble your checklist (mini-project).
- Maintain your cap table, your document store, and your compliance calendar.
- Identify your IP traps honestly and chase down the easy assignment signatures.

You should get a **lawyer** for:

- The actual entity formation in a non-trivial situation, and anything cross-border.
- The binding founder stock, vesting, and IP-assignment documents.
- The SAFE/round paperwork.
- Anything that binds people or money.

You should get an **accountant** for:

- The entity/tax structure decision and its implications.
- The time-sensitive elections and their deadlines (the 83(b)-style election above).
- Ongoing filings and what the entity will owe.

The founders who waste money on professionals are the ones who show up vague: "uh, what should I do?" The founders who *save* money show up with a checklist and specific questions: "Given that I plan to raise a pre-seed within a year and I'm based in X, what entity, and is there a tax-election deadline I need on my calendar from day one?" Same lawyer, a fraction of the billable hours, far better advice. **Being prepared is the whole game**, and producing that preparation is this week's deliverable.

---

## 12. Recap

You should now be able to:

- State the four reasons to incorporate (liability, ownership clarity, fundraising readiness, cleanliness) and the honest limits of each.
- Apply the "incorporate when money or partners enter" heuristic and explain why too-late is more dangerous than too-early.
- Name the common entity shapes at a high level and articulate why the course refuses to prescribe one — and what to ask an advisor instead.
- Describe how founder stock gets issued and why it should be restricted/vesting, tying back to your Week 4 schedule.
- Recognize that a time-sensitive, irreversible tax election (the 83(b) and its analogues) exists, and that your job is to *route it to a pro on time*, not file it yourself.
- Identify the three classic IP traps — personal-account code, the unassigned helper, and prior-employer claims — and explain when they detonate and how to fix them cheaply now.
- Explain what a SAFE is as a legal instrument and why incorporation, stock issuance, and IP assignment are its prerequisites.
- Draw the boundary between DIY organizing and professional binding work.

Next: the agreements every early company needs, the operational hygiene that keeps the company clean, and the due-diligence self-audit. Continue to [Lecture 2 — Agreements and Ops](./02-agreements-and-ops.md).

---

## References

- *YC — A Guide to Seed Fundraising*: <https://www.ycombinator.com/library/4A-a-guide-to-seed-fundraising>
- *YC — SAFE documents and user guide*: <https://www.ycombinator.com/documents>
- *SBA — Choose a business structure*: <https://www.sba.gov/business-guide/launch-your-business/choose-business-structure>
- *Carta — founder stock, vesting, cliff explainers*: <https://carta.com/learn/>
- *Copyright.gov — What is copyright?*: <https://www.copyright.gov/what-is-copyright/>
- *USPTO — Trademark basics*: <https://www.uspto.gov/trademarks/basics>

*This is education, not legal or tax advice. Confirm every jurisdiction-specific item with a licensed professional.*
