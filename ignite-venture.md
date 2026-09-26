# Ignite venture — WarrantyKhata (draft)

**Status:** being created on the Wadhwani Ignite platform, 2026-09-19. Solo (standalone) venture.
This is Manish's personal learning venture for the Ignite course.

## Create Venture form — Step 1 (Team Details)

| Field | Value |
|---|---|
| Logo | skip for now (optional) |
| Company Name * | WarrantyKhata |
| Industry Type * | Retail (or closest: Retail & E-commerce / Consumer Services; fallback: Technology / Software) |
| Description * | see below |
| Website | https://warrantykhata.netlify.app (once deployed — see below). Leave blank until it is live |
| Country * | India |
| City * | Pune |

### Description (long)
Small mobile and electronics retailers still manage warranty records, serial/IMEI numbers and
after-sales follow-ups on paper registers, Excel sheets and WhatsApp chats. Records go missing,
warranty claims get delayed, and repeat customers are rarely followed up. Built on 12 years of
first-hand experience in electronics retail and accounts in Pune, WarrantyKhata is exploring a
simple mobile-first tool that keeps every sale's warranty and service details in one place and
reminds shop owners and customers at the right time.

### Description (short, if there is a character limit)
Helping small mobile and electronics shops stop losing warranty, serial/IMEI and customer
follow-up records kept on paper and WhatsApp — built on 12 years of electronics retail experience.

## Step 2 (Add Members)
Solo.

## Why this problem
- Founder-problem fit: 12 years at an electronics retailer (sales -> senior sales -> accounts &
  back office). He has lived this problem; he does not need to imagine it.
- Solo-friendly: one person can interview shop owners in Wakad/Pune himself.
- Doubles as Android practice: the eventual MVP is a simple CRUD + reminders app — exactly the
  Stage 2-3 skills in his study plan.
- Honest weakness: small-shop billing/khata apps already exist. Competitors get mapped properly in
  Module 4; nothing here claims the gap is proven.

## Venture options (2026-09-19) — Manish decides; nothing is locked in yet

| # | Venture | Customer | Personal connect | Solo validation | Helps Android portfolio | Can it earn |
|---|---|---|---|---|---|---|
| 1 | **WarrantyKhata** — shop warranty/IMEI/follow-up records | Mobile & electronics shop owners | Very high (12 yrs retail + accounts) | Medium — walk into Wakad shops | Yes, simple CRUD + reminders | Yes — shops pay (B2B) |
| 2 | **Student organiser** — assignments, practicals, exam dates for SPPU students | College students | High (he is one) | Very easy — classmates | Yes, simple | Weak — students rarely pay |
| 3 | **Coding-practice drills for career changers** — short daily drills, Hinglish | Adults moving from non-tech to tech | Very high (his exact situation right now) | Easy — online | Yes, medium | Some — crowded market |
| 4 | **Used-phone buyer check** — IMEI/condition checklist/fair price | People buying second-hand phones | High (electronics retail) | Medium | Yes, medium | Unclear — big players exist |
| 5 | **Small-shop accounts & GST back-office** — a service, not an app | Small shop owners | High (5.5 yrs accounts) | Easy | **No** | Fastest to earn — but competes with CAs/accountants |

Recommendation: #1 (strongest connect + someone who pays + builds the portfolio). Easiest
backup: #2. No competitor or market claim in this table has been verified yet — that is Module 4.
Pivoting is built into the program (Module 2 includes "Pivot / Refine Customer-Problem fit" —
faculty resources page, read), so the first choice is not permanent; avoid switching after
Milestone 1.
Best source of the venture: the real-world problems he already entered in L2 on the platform.

## Next Ignite steps (from Wadhwani's own lesson plans)
- Venture Journey Activity 1.1 — Discover Real Life Problems
- Venture Journey Activity 1.2 — Identify Industry/Domain of the Problem
- Venture Activity 1.3 — Analyze the Problem: 5 Whys, RCA fishbone, impact, personal connect
- Tool: Problem Statement Canvas

## Evidence ledger
| # | Claim | Grade | Source | Read? |
|---|---|---|---|---|
| 1 | Form fields: logo, company name*, industry*, description*, website, country*, city*; Step 2 add members | A | Manish's screenshot of the form | seen |
| 2 | Venture activities 1.1/1.2/1.3, Problem Statement Canvas, 5 Why/RCA | A | fdp.wadhwanifoundation.org lesson plans 1.3, 1.4 (PDF) | read |
| 3 | Classroom version is run as team activities ("5 mins per team", "Team Activity") | A | same lesson plans | read |
| 4 | Bootcamp teams are 3 members | F (unverified) | Scribd onboarding doc — only a search snippet; the document itself could not be read | snippet |
| 5 | Industry Type dropdown options | unknown | not visible in the screenshot | — |

Could not verify: whether a one-person venture is allowed; whether name/description can be edited
later; the industry dropdown list.

## Name change (2026-09-19)
First draft name "WarrantyMitra" was dropped: **Warranty Mitra is a live company in the same space**
("Warranty Distribution Platform for Retailers & Partners", warrantymitra.com, domain registered
2026-03-29). Using it would cause confusion and possible trademark trouble.
"WarrantyKhata": no app or company found under that exact name; warrantykhata.com and .in had no
registration at the time of checking; warrantykhata.netlify.app returned 404 (free).
Not a trademark search — do one before any real launch.

## Competitors to map in Module 4 (seen in search results only, not yet read)
- Retailer side: Warranty Mitra (warranty/protection-plan distribution through retailers) — read.
- Consumer side: Warranty Book (warrantybook.in), Warrify, Warranty Keeper, CheckMyWarranty,
  Warranty Tracker — these store warranties for the *buyer*. WarrantyKhata's angle is the *shop*.
- Device protection: Servify.
- Shop ledger/billing apps (khata-style) — adjacent, check whether they already track warranties.

## Website
Single-file landing page: `site/index.html` — no dependencies. Honest by design: labelled
"early stage", features marked "not built yet", no testimonials, no user numbers.
Contact button: the public copy of `site/index.html` in this repository uses a placeholder address
(hello@example.com); the real address is not published here.

Deploy: Netlify Drop (app.netlify.com/drop) — log in (free, Google sign-in), drag the `site`
folder, then rename the project to `warrantykhata` -> https://warrantykhata.netlify.app
Anonymous deploys must be claimed within one hour (Netlify docs), so log in first.

| # | Claim | Grade | Source | Read? |
|---|---|---|---|---|
| 6 | Warranty Mitra is a live retailer-warranty company | A | warrantymitra.com homepage | read |
| 7 | warrantymitra.com registered 2026-03-29, GoDaddy | A | whois | read |
| 8 | No app/company named WarrantyKhata found | B | two web searches + whois .com/.in | searched — absence of evidence, not a trademark search |
| 9 | Netlify drag-and-drop needs login; anonymous deploys claimable within 1 hour | A | docs.netlify.com | read |
