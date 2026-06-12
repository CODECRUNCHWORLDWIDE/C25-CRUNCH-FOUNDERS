# Lecture 2 — Cap Tables, SAFEs, and Dilution

> **Duration:** ~2 hours of reading + working the numbers in a spreadsheet alongside.
> **Outcome:** You can build a cap table from a blank sheet, explain a post-money SAFE in plain English, model an option pool created pre-money, and compute — to the share and the percentage point — what a round costs founders.

This is the mechanical half of the week. Lecture 1 was the *should you*; this is the *what it does to you*. Open a blank spreadsheet now and build every table as you read. You will not internalize dilution by reading about it. You internalize it by watching your own percentage drop in a cell you typed yourself.

> **The one identity that unlocks everything:** `ownership % = your shares ÷ total shares`. That's it. Every dilution surprise in this lecture is just that fraction, with the denominator getting bigger. New shares get issued, the denominator grows, your numerator stays put, your percentage falls. Hold that and the rest is arithmetic.

---

## 1. What a cap table is

A **capitalization table** — "cap table" — is the record of who owns what. At its simplest it's a three-column table: holder, shares, ownership %.

Two founders split a company evenly and authorize 10,000,000 shares (a common round number; the absolute count is arbitrary — what matters is the *ratios*):

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | 50.0% |
| Founder B | 5,000,000 | 50.0% |
| **Total** | **10,000,000** | **100.0%** |

That's a cap table. The ownership column is just each holder's shares divided by the total. Note three things first-timers miss:

- **The total share count is a choice, and it doesn't matter on its own.** 10,000,000 shares split 50/50 is identical, in ownership terms, to 8 shares split 4/4. People pick large round numbers so that future grants (you'll issue options in small share counts) divide cleanly. Don't fixate on the absolute number; watch the ratios.
- **"Issued" vs. "authorized."** You *authorize* a ceiling of shares in your incorporation docs and *issue* some of them. Unissued authorized shares aren't owned by anyone and don't count toward ownership %. We'll keep it simple and treat issued shares as the denominator.
- **"Fully diluted" is the number that matters.** The honest ownership picture counts *everything that could become a share* — issued shares, the option pool (even unallocated), and convertibles like SAFEs once they convert. When an investor asks "what's your fully diluted cap table," they mean: show me everything, including the slices that don't exist yet but will.

---

## 2. Dilution is just a growing denominator

Issue new shares to anyone and the total grows. Everyone who *didn't* get new shares sees their percentage fall, even though their share count is unchanged. That's dilution. It is not theft and it is not always bad — if the new shares brought in money or talent that grows the whole pie, your smaller slice can be worth more than your old bigger one. But the *percentage* falls, mechanically, every time.

Suppose Founders A and B issue 1,000,000 new shares to a key early hire:

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | 45.5% |
| Founder B | 5,000,000 | 45.5% |
| Early hire | 1,000,000 |  9.1% |
| **Total** | **11,000,000** | **100.0%** |

Neither founder lost a single share. Both dropped from 50.0% to 45.5%. The denominator went from 10M to 11M; `5,000,000 ÷ 11,000,000 = 45.5%`. That is the entire mechanic. Everything below is this same move, dressed up.

---

## 3. Pre-money and post-money valuation

When you raise a **priced round**, you and the investor agree on a valuation. There are two flavors, and confusing them is the most common founder error in the whole process.

- **Pre-money valuation** — what the company is agreed to be worth *before* the new money goes in.
- **Post-money valuation** — pre-money **plus** the amount invested. `post = pre + investment`.

The investor's resulting ownership is:

> **investor % = investment ÷ post-money valuation**

This is the second identity to memorize. Work an example. You raise **$500,000** at a **$4,500,000 pre-money** valuation:

```
post-money = pre-money + investment
           = $4,500,000 + $500,000
           = $5,000,000

investor % = investment ÷ post-money
           = $500,000 ÷ $5,000,000
           = 10.0%
```

The investor ends up owning **10%** of the company. The founders, who owned 100%, now own 90% *combined*. Watch the asymmetry that trips people up: the investor's percentage is computed against **post**-money, but founders' dollar value sits on **pre**-money. If a founder hears "$4.5M pre" and thinks they sold 10% of $4.5M, they've mis-modeled it. The investor bought 10% of the *$5.0M* post-money company.

### 3.1 Issuing the shares to make it true

In a real cap table you don't just write "10%"; you issue shares so the math holds. Start from 10,000,000 founder shares = 90% post-round. Solve for the new total:

```
founder shares ÷ new total = 90%
10,000,000 ÷ new total = 0.90
new total = 10,000,000 ÷ 0.90 = 11,111,111
investor shares = new total − founder shares
               = 11,111,111 − 10,000,000 = 1,111,111
```

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | 45.0% |
| Founder B | 5,000,000 | 45.0% |
| Pre-seed investor | 1,111,111 | 10.0% |
| **Total** | **11,111,111** | **100.0%** |

Each founder went **50.0% → 45.0%**, giving up 5.0 points each, to bring in $500k. That's the round, cleanly modeled. Now we add the two complications that make real rounds cost more than the headline: the **option pool** and the **SAFE**.

---

## 4. The option pool and the "pool shuffle"

Investors almost always require you to set aside an **option pool** — shares reserved for future employees (engineers, early hires) who'll be paid partly in equity. A typical pre-seed/seed pool is **10–15%** of the post-round company.

Here's the part that surprises everyone. Investors want the pool created **pre-money** — *before* their money goes in. Why does that matter? Because a pre-money pool comes out of the **existing shareholders' slice** (that's you, the founders), *not* out of the investor's. The investor still gets their clean 10% on top of a company that already has the pool baked in. The pool dilutes you; it does not dilute them.

This is the **pool shuffle**, and it's the single most common way founders end up owning less than they expected. Let's make it concrete. Same $500k at $4.5M pre, but now the investor also requires a **10% post-money option pool, created pre-money.**

After the round we need: investor 10%, option pool 10%, founders 80%. Founders' 10,000,000 shares must equal 80% of the new total:

```
10,000,000 ÷ new total = 80%
new total = 10,000,000 ÷ 0.80 = 12,500,000

option pool shares = 10% × 12,500,000 = 1,250,000
investor shares    = 10% × 12,500,000 = 1,250,000
```

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder A | 5,000,000 | 40.0% |
| Founder B | 5,000,000 | 40.0% |
| Option pool (unallocated) | 1,250,000 | 10.0% |
| Pre-seed investor | 1,250,000 | 10.0% |
| **Total** | **12,500,000** | **100.0%** |

Each founder went **50.0% → 40.0%** — they gave up **10 points each**, not the 5 they'd have guessed from a "10% round." The extra 5 points is the pool, and *the founders paid for all of it* because it was created pre-money. The investor still cleanly owns 10%.

> **The pool-shuffle lesson:** "we're raising a 10% round" almost never means "founders dilute 10%." With a pre-money pool, founders dilute by the round *plus the whole pool*. Always model the pool explicitly and always ask whether it's pre- or post-money. You can negotiate the pool size (do you really need 15%, or will 10% cover your next 18 months of hires?) — and every point you shave comes straight back to you.

---

## 5. SAFEs — money now, shares later

Pricing a company is hard and slow: you and the investor have to agree on a valuation when there's barely a company to value. The **SAFE** (Simple Agreement for Future Equity), created by Y Combinator, sidesteps this. In plain English:

> **A SAFE is a promise.** The investor gives you money *now*, and in exchange gets the right to receive shares *later* — automatically — when you do a priced round. No valuation is set today; the SAFE just defines *how* the money converts into shares when the time comes.

A SAFE is **not** a loan. There's no interest, no maturity date, no repayment (a convertible *note*, the older instrument, does have those — interest and a maturity date — which is one reason SAFEs largely replaced notes for early rounds). A SAFE is also **not equity yet** — the investor isn't a shareholder until it converts. It sits in between, which is exactly why it's fast and founder-friendly to sign — and exactly why it's easy to over-sign.

Two knobs determine how good the SAFE is for the investor (and therefore how much it dilutes you):

### 5.1 The valuation cap

The **valuation cap** is the maximum valuation at which the SAFE converts. It protects the early investor: if you go on to raise your priced round at a high valuation, the SAFE holder still converts as if the company were worth (at most) the cap. They took early risk; the cap rewards them with a better effective price than the later, lower-risk investors.

Example: an angel puts in $100k on a SAFE with a **$5,000,000 cap**. You later raise a priced round at a $20,000,000 valuation. The SAFE converts as if the company were worth $5M, not $20M — so the angel's $100k buys four times the shares it would have at the full price. The cap is the early investor's reward for being early.

### 5.2 The discount

The **discount** gives the SAFE holder a percentage off the priced round's per-share price — commonly **10–20%**. If the round prices at $1.00/share and the SAFE has a 20% discount, the SAFE converts at $0.80/share. A SAFE can have a cap, a discount, or both (when it has both, the holder takes whichever gives them more shares).

### 5.3 MFN

**MFN** ("most favored nation") lets an early SAFE holder upgrade to better terms if you later grant a *more generous* SAFE to someone else. It stops you from quietly giving a friend a sweeter deal at the early investor's expense. Common on uncapped early SAFEs.

### 5.4 Post-money vs. pre-money SAFE — why 2026 cares

The original (2013) YC SAFE was **pre-money**. In 2018 YC replaced it with the **post-money SAFE**, and that's the 2026 default. The difference is subtle but matters enormously to you:

- With a **post-money SAFE**, the cap is measured *including* the SAFE money itself. The crucial consequence: **the investor's percentage of the company is fixed and knowable the day you sign.** If they put in $500k on a $5M post-money cap, they own 10% — full stop — regardless of what other SAFEs you sign afterward.
- The catch: with post-money SAFEs, **the founders absorb the dilution from every *additional* SAFE.** Sign one post-money SAFE, then another, then another, and each one's percentage is locked in *against you*. The investors don't dilute each other; you dilute to make room for all of them.

> **The post-money SAFE trap:** because each SAFE's ownership is fixed and easy to sign, founders stack them — $250k here, $200k there, $100k from an angel — and only when they all convert at the priced round do they discover they've promised away 25–30% before the priced investor even shows up. *Add up every SAFE's implied percentage before you sign the next one.* The whole point of Exercise 2 is to make you do that arithmetic before reality does it for you.

---

## 6. A full pre-seed, end to end

Let's put it all together the way your mini-project will. A founder raises **$600,000 on post-money SAFEs**, then does a priced **seed** where those SAFEs convert and a new investor leads with a fresh option pool. We'll keep it to the shape; your spreadsheet does the exact shares.

**Step 0 — starting table.** Two founders, 10,000,000 shares, 50/50.

**Step 1 — the SAFEs.** Three SAFEs totaling $600k:

| SAFE | Amount | Post-money cap | Implied % at conversion |
|------|-------:|---------------:|------------------------:|
| Lead angel | $300,000 | $6,000,000 | 5.0% |
| Angel 2 | $200,000 | $6,000,000 | 3.3% |
| Friend | $100,000 | $5,000,000 | 2.0% |
| **Total** | **$600,000** | — | **~10.3%** |

Before the priced round even begins, the founders have already promised away **~10.3%** (each SAFE's amount ÷ its cap). With post-money SAFEs, that 10.3% is locked; the founders eat all of it.

**Step 2 — the priced seed.** A seed investor puts in **$1,500,000 at a $6,000,000 pre-money**, and requires a **10% post-money option pool created pre-money**. The SAFEs convert into shares at this round. After everything settles, a plausible fully-diluted table:

| Holder | Ownership % |
|--------|------------:|
| Founder A | ~31% |
| Founder B | ~31% |
| SAFE holders (converted) | ~10% |
| Option pool | ~10% |
| Seed investor | ~18% |
| **Total** | **100%** |

The founders started at 100% combined and, after one SAFE round and one priced seed with a pool, sit around **62% combined** — each roughly **50% → 31%**. No single step felt huge. The SAFEs were "easy to sign." The pool was "standard." The seed was "a great valuation." Stacked together, they cost the founders nearly 40 points. **That stacking is the entire reason this week exists.** None of it is a scandal; all of it is arithmetic you must see coming.

---

## 7. Reading a term sheet — what actually matters

A pre-seed/seed term sheet is short. Most of it is boilerplate that's the same across every deal. A handful of terms decide your outcome:

- **Valuation / cap.** The headline. Sets the price and, with it, dilution. Important — but the part founders over-index on.
- **Option pool size and timing.** As Section 4 showed, a pre-money pool comes out of *you*. Negotiate the size; confirm the timing. This is often where the real, unglamorous money is.
- **Pro-rata rights.** The investor's right to invest again in future rounds to maintain their percentage. Standard and usually fine; just know you're granting it.
- **Board composition.** At the priced stage, who sits on the board and who controls it. This is your *control* lever from Week 1, made literal. At pre-seed on SAFEs there's usually no board change yet.
- **Liquidation preference.** In a sale, who gets paid back first and at what multiple (1x non-participating is the founder-friendly standard). Mostly a priced-round term.

The boilerplate — confidentiality, governing law, the no-shop clause, standard reps and warranties — matters less and is the same everywhere. Your job as a founder isn't to lawyer the document; it's to *know which four or five lines change your life* and to brief a real lawyer on those. Exercise 3 walks you through annotating one.

---

## 8. A SAFE conversion, worked to the share

Section 6 gave the shape; here's the arithmetic so you can do it yourself. This is exactly the calculation Exercise 2 asks you to build, and the one cap-table tools automate.

A founder has **8,000,000 shares** (single founder, for clarity). She raises one **post-money SAFE: $500,000 at a $5,000,000 post-money cap.** Later she does a priced round: **$1,000,000 at a $4,000,000 pre-money.** Watch the conversion.

**Step 1 — what the SAFE is owed.** On a post-money SAFE, the investor's ownership is `investment ÷ post-money cap = $500,000 ÷ $5,000,000 = 10%` of the company *after the SAFE converts but before the new priced money*. Hold that 10% target.

**Step 2 — the priced round's headline.** `post-money = pre + investment = $4,000,000 + $1,000,000 = $5,000,000`, so the new investor targets `$1,000,000 ÷ $5,000,000 = 20%`.

**Step 3 — solve the cap table so all three targets hold.** After everything: SAFE holder 10%, new investor 20%, founder gets the remaining **70%**. Her 8,000,000 shares must equal 70% of the new total:

```
new total = 8,000,000 ÷ 0.70 = 11,428,571 shares

SAFE holder shares     = 10% × 11,428,571 = 1,142,857
new investor shares     = 20% × 11,428,571 = 2,285,714
founder shares (unchanged) = 8,000,000
```

| Holder | Shares | Ownership % |
|--------|-------:|------------:|
| Founder | 8,000,000 | 70.0% |
| SAFE holder (converted) | 1,142,857 | 10.0% |
| Priced investor | 2,285,714 | 20.0% |
| **Total** | **11,428,571** | **100.0%** |

The founder went **100% → 70%** in one pre-seed-plus-seed sequence: 10 points to the SAFE, 20 to the priced investor. Notice the SAFE — the "easy, founder-friendly, no-valuation" instrument — cost her a clean 10 points, fixed the day she signed it. That's not a trick; it's the deal. The lesson is simply to *see it coming*, which means doing this arithmetic before you sign, not after the round closes.

> **Why the post-money cap makes this predictable.** Because the SAFE's % is pinned to its own cap, you can compute it in isolation the day you sign — no need to know the future priced valuation. That predictability is the post-money SAFE's whole selling point, and the reason founders can (and must) sum their SAFE stack in advance.

---

## 9. Frequently confused points

A short clinic on the things that trip up first-timers, because the mini-project rubric docks you for each one.

- **"More shares means I own more."** No. Ownership is a *ratio*. Issuing yourself more shares while everyone gets the same multiple changes nothing. Only the *split* matters.
- **"A higher valuation is always better for me."** Mostly true for dilution — a higher pre-money means less dilution for the same money. But an inflated valuation you can't grow into sets a brutal bar for the next round and invites a down round later. Price for the *next* round, not your ego.
- **"The option pool dilutes the investor too."** Only if it's created *post*-money. The standard pre-money pool comes out of *you*. Always confirm the timing.
- **"SAFEs don't dilute me until later, so they're cheaper."** They dilute you *exactly as much* as the equity they'll convert into; you just don't *see* it until conversion. Deferred pain is still pain.
- **"My friends-and-family money doesn't need real paperwork."** It needs it *more*, because the relationship raises the stakes of a misunderstanding. Use a real SAFE with a real cap.
- **"I'll figure out the cap table when I raise."** By then it's set in signed documents. The whole point of modeling it now is that the cheap time to understand your dilution is *before* anyone wires money.

---

## 10. The formulas, in one place

Pin this. Every number you'll compute this week comes from one of these. Keep it next to your spreadsheet.

| You want | Formula |
|----------|---------|
| A holder's ownership | `shares ÷ total shares` |
| Post-money valuation | `pre-money + investment` |
| Investor % (priced round) | `investment ÷ post-money` |
| New total shares for a target investor % | `existing shares ÷ (1 − investor %)` |
| New investor's shares | `new total − existing shares` |
| Post-money SAFE investor % | `investment ÷ post-money cap` |
| SAFE discount conversion price | `round price × (1 − discount)` |
| Founder % after a pre-money pool + round | `founder shares ÷ new total`, where the pool and investor both take their slices of `new total` |
| Dilution suffered | `ownership before − ownership after` (in points) |

If you can drive a model from this table without looking anything else up, you have the week's mechanics. The hard part was never the arithmetic — it's *remembering to include the pool and the SAFE stack* before you reassure yourself the dilution is small.

---

## 11. Allocating the option pool (a glance ahead)

The pool isn't just a number that dilutes you; it's real equity you'll hand to real early employees, and how you allocate it is its own small skill. You won't grant options in this course, but know the shape so the pool isn't a black box on your cap table:

- **Options vs. shares.** Employees usually get *stock options* — the right to *buy* shares at a fixed "strike" price later — not shares outright. If the company grows, the shares are worth more than the strike, and that gap is the employee's reward.
- **They vest.** Just like founder equity (Week 4), employee options vest over time — commonly four years with a one-year cliff. Someone who leaves in month six gets nothing; the unvested portion returns to the pool.
- **Earlier = more.** The first engineer might get 1–2%; the tenth, a fraction of that. The pool is sized to cover a *plan* of hires, which is exactly why you should size it to your real 18-month hiring plan and not to whatever round number the investor first suggests.
- **Unallocated pool still dilutes you.** Here's the sting that ties back to the shuffle: even the *unallocated* part of a pre-money pool sits on the fully-diluted cap table diluting founders from day one. An oversized pool is pure, unforced founder dilution. Right-size it.

This is why "negotiate the pool down to what you actually need" (Section 4) is one of the highest-leverage, least-glamorous moves in a round. Every unused point of an oversized pre-money pool is ownership you gave away for nothing.

---

## 12. Tie it back to control vs. wealth

Everything in this lecture is a number, but every number is a values choice you made in Week 1:

- A **control-leaning** founder minimizes rounds, keeps the pool tight, avoids a board seat for as long as possible, and may stop raising entirely once the business is default alive. They accept slower growth to keep the wheel.
- A **wealth-leaning** founder accepts more dilution and more investors because they're optimizing the *size of the pie*, betting that 31% of a huge outcome beats 100% of a modest one.

Neither is right in the abstract; the cap table just makes the trade *visible*. When you build your model this week, the founder-ownership-before-vs-after line is not a finance exercise. It's the price tag on the decision you leaned toward in Week 1. Read it as such.

> **Not investment or legal advice.** SAFEs, pools, and priced rounds are documents you sign with a lawyer. This lecture makes you an informed founder who can brief counsel and model your own dilution — not a substitute for counsel.

---

## 9. Recap

You should now be able to:

- Build a cap table and explain the identity `ownership % = your shares ÷ total shares`.
- Explain dilution as a growing denominator and compute it for a new issuance.
- Distinguish pre-money from post-money and apply `investor % = investment ÷ post-money`.
- Issue the actual shares that make a target ownership true.
- Model an option pool created pre-money and explain the pool shuffle in your own words.
- Explain a post-money SAFE — cap, discount, MFN — and why stacked SAFEs dilute founders, not each other.
- Walk a full pre-seed end to end and name which term-sheet lines actually matter.

Now make it real: do [Exercise 1 — Cap-Table Basics](../exercises/exercise-01-cap-table-basics.md), then [Exercise 2 — SAFE Conversion](../exercises/exercise-02-safe-conversion-worksheet.md) and [Exercise 3 — Term-Sheet Read-Through](../exercises/exercise-03-term-sheet-readthrough.md), and build the [Cap-Table + Dilution Model](../mini-project/README.md).

---

## References

- *Y Combinator — post-money SAFE documents and user guide:* <https://www.ycombinator.com/documents/>
- *Carta — Startup cap table basics:* <https://carta.com/learn/startups/cap-table/>
- *Investopedia — Pre-Money vs. Post-Money Valuation:* <https://www.investopedia.com/ask/answers/114.asp>
- *NVCA — model legal documents:* <https://nvca.org/model-legal-documents/>

*Back to the [week overview](../README.md).*
