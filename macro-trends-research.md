# 4.2 Macro trends - WarrantyKhata
Researched 2026-09-20. India. "NOT ON PAGE" = page did not say it.

## Submitted / planned answers (100 chars max each; Area is a dropdown)
Favorable
1. Area = Economy: "More phones are bought in shops: IDC puts offline share at 57% in 2025 and 62% in Q1 2026."
2. Area = Legal: "Govt Right to Repair portal lists warranty and service terms for phone and electronics brands."
Unfavorable (planned answers for the next page)
3. Area = Economy: "Phone shipments fell 4.1% in Q1 2026 as memory costs rose, so fewer new sales to record (IDC)."
4. Area = Legal: "New data rules (DPDP 2025) need consent notices and breach reporting for customer phone numbers."

## Why each trend matters to WarrantyKhata
1. Shops are the majority phone channel and their share is rising, so the counter is where the warranty record is created.
2. The government is making warranty and service information a public, searchable topic; shops that can show a customer's record fit that direction. The portal's own About page says the framework should "boost business for small repair shops".
3. Fewer new phones sold = fewer new warranty records to capture per shop. IDC: entry-level segment fell 59% YoY, and brands are "revising annual shipment targets downward".
4. WarrantyKhata would store customers' names and phone numbers. Likely role: the shop is the Data Fiduciary and WarrantyKhata a Data Processor - NOT verified, needs legal advice before launch. Cost: consent notice, security safeguards, breach handling.

## Evidence ledger
| # | Claim | Grade | Source | Read? | Data date | Geography |
|---|---|---|---|---|---|---|
| 1 | Q1 2026 India smartphone shipments -4.1% YoY to 31.0M; entry-level -59% YoY (memory cost inflation); brands revising annual targets down; offline share 62% (up from 58%), online 38% | A (IDC's own blog) | https://www.idc.com/resource-center/blog/india-smartphone-market-q1-2026/ | read | Q1 2026 | India |
| 2 | 2025: 152M units, +0.5%; offline share 57% (2025) vs 51% (2024), offline +12%; IDC expects volumes to contract in 2026 amid a global memory shortage | C (EE Times India relaying IDC; 51% and the 2026 outlook only via this relay). IDC's full-year press release was not found | https://www.eetindia.co.in/idc-india-smartphone-market-flat-in-2025/ | read | 2025 | India |
| 3 | Right to Repair portal (Dept of Consumer Affairs, built by NIC): sectors include Mobiles/Electronics; brands registered include Samsung India, OPPO, LG, HP, Havells; lets users find warranty, service terms and post-sales support; lists authorised and third-party service providers | A (official portal) | https://righttorepairindia.gov.in/ , /about , /faq | read (fetch tool hit a certificate error; read with curl -k, public pages, nothing sent) | 2026-09-20 | India |
| 4 | DPDP Rules 2025 notified 14 Nov 2025; 18-month phased compliance; every Data Fiduciary must give a separate clear consent notice stating the purpose; breach must be told to affected people; penalties up to Rs 250 crore for failing reasonable security safeguards | A (PIB note "DPDP Rules, 2025 Notified", 17 Nov 2025) | https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf | read (text extracted from the PDF; the fetch tool's summary missed it) | Nov 2025 | India |
| 5 | Exact end date of the 18 months ("13 May 2027") | D - search snippets only; the PIB note says "eighteen-month" but not the date | - | snippet | - | India |
| 6 | WhatsApp Business API utility message price about Rs 0.115-0.145 | D - snippets disagree; NOT used | - | snippet | - | India |

**Load-bearing (A):** rows 1, 3, 4. **Do not act on:** rows 5, 6. Row 2 only for the 2025 numbers (152M units, 57% offline share).
**Could not verify:** whether the Right to Repair rules are already binding on brands (the About page says "would be mandatory" - framework language); whether a tiny shop tool counts as Data Fiduciary or Processor; IDC's own full-year 2025 press release.
**Confidence:** high that these four trends exist and are correctly described; moderate on how much they matter to a single-store shop. Trend 2 breaks if the portal turns out to be little used by customers.
