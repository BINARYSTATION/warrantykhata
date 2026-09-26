# WarrantyKhata — proving it works in reality

Right now WarrantyKhata is a **hypothesis**, not a fact. This plan tests it cheaply, before any
code is written, in the order that costs the least time first. It is also exactly the work the
Ignite program asks for: Module 2 "Validate Customer-Problem fit" and Module 5 "Prototypes for
Early Validation" (both lesson names verified on Wadhwani's faculty resources page).

## The hypothesis, written so it can fail
> Small mobile/electronics shop owners in Pune lose time, money or customers because warranty,
> serial/IMEI and follow-up records live on paper and WhatsApp — and at least some would change
> how they work to fix it.

## Pass / fail — decided BEFORE talking to anyone
These thresholds are a judgement call, not research. They are set in advance so the results can't
be read generously afterwards.

| Test | Pass | Fail → pivot |
|---|---|---|
| 10 problem interviews | ≥5 describe a **specific recent incident** (last 30 days) without being led | <3 care |
| Offer a free 2-week manual trial | ≥3 of 10 say yes | 0-1 say yes |
| After the 2-week trial | ≥1 shop keeps using it, asks to continue, or offers to pay | nobody uses it past week 1 |

A fail is not a failure of the venture journey. Ignite has a whole lesson on pivoting; a
well-evidenced "this wasn't the problem, THIS was" is a strong Milestone 1.

## Step 1 — Problem interviews (weeks 1-2)
- **10-15 shop owners.** Start where the door is already open: Mr Surya Electronics (where he
  worked) and the shops, distributors and service centres he knows through it. Then walk-ins
  around Wakad, Hinjewadi, Pimple Saudagar.
- Ask about **past behaviour**, never "would you use an app". People say yes politely. What they
  did last Tuesday doesn't lie. (Method: "The Mom Test", Rob Fitzpatrick.)
- Show the website / idea only at the END, after listening.
- Log every interview in `interview-log.csv` the same day.
- Script: `interview-script.md`.

## Step 2 — Count what's real (during interviews)
Collect numbers from the shop, not from the internet. These become the Milestone 1 evidence in
place of made-up market statistics:
- warranty claims per week
- minutes to find an old sale's record
- how records are kept today (photo of the register, **with permission**)
- incidents in the last month where a record couldn't be found

## Step 3 — Concierge trial (week 3-4)
Do the job **by hand** for 2-3 shops for two weeks. No app.
- One private Google Sheet per shop (or a Google Form on the owner's phone): date, customer name,
  phone, product, serial/IMEI, warranty end date.
- Manish sends the warranty-expiry reminders on WhatsApp himself, or hands the owner a daily list.
- Measure: entries per day, times the owner looked something up, whether they kept filling it in
  after week 1.
- **Privacy:** it's the shop's customers' data. Owner's consent, sheet shared only with that
  shop, deleted when the trial ends. Never reuse it.

## Step 4 — Commitment test
Ask for something that costs them: 30 more minutes, an introduction to another shop owner, or a
small advance to continue after the trial. A shop that pays even a little is proof. A shop that
says "achha idea hai" is not.

## Step 5 — Only then, build
If Steps 1-4 pass, the Android MVP is a small CRUD + reminders app — which is the Stage 2-3 Kotlin
project anyway. If they fail, the interviews will have shown which problem to switch to.

## What goes into Milestone 1
- Number of interviews, and who (shop type, area)
- 3-5 direct quotes from shop owners
- The real numbers from Step 2
- Concierge trial results
- Decision: continue / refine / pivot — with the reason

## Time budget (fits alongside work, B.Com (CA) and Kotlin)
~3-4 hours a week for 4 weeks: two or three shop visits per outing, logging the same day.
