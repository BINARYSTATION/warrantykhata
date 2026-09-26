# 4.4 Back-of-the-envelope Year 1 - WarrantyKhata
Prepared 2026-09-20. Decisions: use Wadhwani's own Financial Planning tool for the
numbers, and do NOT count the founder's salary as an expense (solo founder, not drawing one).
These are the assumptions to type into the tool; the tool's own output is what goes in the form.

## Form answers already decided
- Currency: Indian Rupee (INR)
- Business model: Subscriptions (a monthly per-shop fee - matches the Module 6 plan)

## Revenue assumption (Year 1)
Price Rs 199/month per shop - the SAME price used for the 4.3 TAM. If this changes, 4.3 must change too.
- Months 1-5: building the app + free pilot with a handful of shops in Wakad/Hinjewadi. Revenue Rs 0.
- Months 6-12: paid. Paying shops ramp 15, 25, 35, 45, 55, 68, 80 (80 shops by month 12).
- 323 shop-months x Rs 199 = **Rs 64,277**
Why it is small and why that is right: one person selling door to door in Pune, no sales team, no ads.
The validation plan's own target is 10-15 shop interviews, so 80 paying shops in year one is already
optimistic rather than conservative.

## Expense assumptions (Year 1, no founder salary)
| Item | Rs |
|---|---|
| Test Android phone (one-time) | 12,000 |
| Google Play Console developer fee (one-time; approx rupee equivalent of USD 25 - NOT price-checked) | 2,500 |
| Internet + mobile (Rs 1,000 x 12) | 12,000 |
| Travel to shops in Pune (Rs 1,500 x 12) | 18,000 |
| Backend / Firebase (Rs 500 x 12; mostly free tier) | 6,000 |
| SMS fallback for reminders | 3,000 |
| Domain + landing page | 1,500 |
| Pamphlets and visiting cards | 5,000 |
| **Total** | **60,000** |

## Year 1 result
- Revenue Rs 64,277
- Expenses Rs 60,000
- Profit Rs 4,277 (barely break-even)

The story to tell: year one roughly washes its face because the founder's time is free and there is no
marketing spend. The moment a salary or paid acquisition is added, year one goes negative - which the
course explicitly says is acceptable as long as the reason is known.

## What was actually submitted in 4.4 (2026-09-20)
Currency: Indian Rupee (INR) | Business model: Subscriptions
Year 1 Revenues 64277 | Year 1 Total Expenses 60000 | Year 1 Profit 4277

**Wadhwani's own Financial Planning tool was NOT opened.** So these are our own figures, not the tool's output. If a reviewer asks where they came from, the
answer is the assumption table above, not the tool. Opening the tool later and re-checking is still possible.

## Trajectory beyond Year 1
With a 3% monthly churn and Rs 199/month: Year 2 about 243 shops -> Rs 4.1 lakh; Year 3 about 642 shops ->
Rs 11.2 lakh (roughly Rs 94,000/month). Rs 3 lakh/month needs about 1,500 paying shops at Rs 199 - about 1%
of AIMRA's 1.5 lakh mobile retailers, and not reachable by one person alone.
Pricing ceiling worth remembering: Vyapar's paid plan starts near Rs 283/month and is a full billing app,
so Rs 199 for a warranty-only tool is already at the top of what is defensible. Price is not the lever.

## Year 2 and Year 3 as submitted (2026-09-20)
Same engine as Year 1: Rs 199/month per shop, 3% monthly churn, linear ramp of paying shops.

| | Year 1 | Year 2 | Year 3 |
|---|---|---|---|
| Paying shops at year end | 80 | 243 | 642 |
| Revenue | 64,277 | 4,13,087 | 11,25,232 |
| Expenses | 60,000 | 1,67,500 | 6,11,500 |
| Profit | 4,277 | 2,45,587 | 5,13,732 |

Year 2 expense lines: internet 12,000; travel 36,000; Firebase 18,000; WhatsApp API + SMS 15,000; domain 1,500;
marketing 15,000; part-time onboarding/support help 48,000; second device 10,000; accounting/GST 12,000.
Year 3 expense lines: internet 12,000; travel 60,000; Firebase 48,000; WhatsApp API + SMS 40,000; domain 1,500;
marketing 50,000; full-time support person 2,16,000; part-time field sales 1,20,000; devices 15,000;
accounting/GST 24,000; DPDP compliance + legal 25,000 (ties back to the 4.2 unfavorable legal trend).

**The caveat that matters:** the founder draws no salary in any of the three years. At even Rs 25,000/month for
himself, Year 2 turns into a loss of about Rs 54,000. Say this plainly if a reviewer asks why margins look good.
**Also unpriced:** WhatsApp Business API rates could not be verified (sources disagreed), so those lines are
estimates covering a BSP platform fee plus messages, not a quoted price.

## Upload image for 4.4
`images/warrantykhata-3year-projections.png` (1500x935, ~161 KB) - built with headless Chrome from an HTML page,
NOT a screenshot of Wadhwani's simulator (that tool could not be driven).
It shows the assumptions strip, the 3-year table, all three expense breakdowns and the no-salary caveat.

## Things that are assumptions, not evidence
Every number above except the price link to 4.3 is an estimate by us. Nothing here is a researched
market figure and none of it should ever be presented as one. The Play Console fee is the only item
with a real external price and it was NOT re-checked - do that before quoting it anywhere.

## Consistency debts to watch
- Rs 199/month must stay identical in 4.3 TAM, Module 6 pricing and Module 7 financial assumptions.
- 80 shops at end of Year 1 is the base that Year 2 and Year 3 projections must grow from.
- WhatsApp reminders are sent by hand from the free WhatsApp Business app during the pilot, so there
  is no API cost in Year 1. If the tool asks for one, the honest answer is zero with SMS as fallback.
