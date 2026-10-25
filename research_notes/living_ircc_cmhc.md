# Living costs: IRCC proof of funds + CMHC rents (round 2, 25 Oct 2026)

Blocked hosts: (none yet)

Plan: 1) IRCC proof of financial support page (canada.ca, --browser); PAL exemption; processing times URL.
2) CMHC rents/vacancy for Regina CMA, Fredericton CMA, Guelph CMA, Brandon CA (HMIP / RMR / StatCan 34-10-0133-01).

## 1. IRCC proof of financial support (opened in full via headless Chromium)
URL: https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/get-documents/financial-support.html
Date modified: 2026-08-28
- Covers: "tuition fees for the course or program of studies"; "living expenses for yourself and the family members"; "transportation to and from Canada". Must be "without working in Canada".
- First year: "show you have enough financial resources for the first year of your studies"; for programs > 1 year, "tell us how you plan to pay for the full duration of your studies".
- Annual update: "These amounts are updated each year." (Amounts "do not include tuition and transportation costs.")
- Table heading "If you apply on or after September 1, 2026", "All provinces and territories except Quebec":
  1 person $23,448; 2 $29,192; 3 $35,888; 4 $43,572; 5 $49,419; 6 $55,736; 7 $62,054; "If more than 7 people, each additional family member $6,318".
  (Increment from 1 to 2 persons = $5,744 (arithmetic).)
- Previous table "If you apply between January 1, 2025, and August 31, 2026 (inclusively)": 1 person $22,895; >7 each additional $6,170.
- No figure for 2027 is published yet (paraphrase); since "updated each year", a Fall 2027 applicant applying after the next update (likely around Sept 2027 based on the 2026 pattern, paraphrase/inference) may face a higher figure. UNCONFIRMED what the next figure / date will be.
- Proof examples ("This is not a complete list"): receipt for first-year tuition and housing paid to DLI (must be accompanied by proof of living + transport funds); student/education loan from a bank; scholarship / Government of Canada-funded program; pay stubs; letter from person/institution giving money (with their employment, relationship, dependants, amount, ID photo or business registration); Canadian bank account in your name; GIC from a Canadian financial institution; "bank statements ... for the past 6 months" with source of income; pension documents; rental income proof. Foreign exchange controls: must prove you can export funds.
- Quebec: separate MIFI amounts for CAQ.

## PAL exemption
URL: https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/get-documents/provincial-attestation-letter.html (Date modified 2026-09-02)
- Exempt list includes "master’s degree-granting program at a public DLI" -> result "you don’t need a PAL/TAL", but "you need to provide proof that you meet one of the exceptions" (e.g. letter of acceptance). CONFIRMED exempt for master's at public DLI.
- Apply page (https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/apply.html, Date modified 2026-09-02): "If you meet an exception, you must provide any evidence in the Client information field."

## Processing times
Tool page: https://www.canada.ca/en/immigration-refugees-citizenship/services/application/check-processing-times.html (Date modified 2026-10-20; "Updated weekly"; times shown only after selections).
Data file behind the tool: https://www.canada.ca/content/dam/ircc/documents/json/data-ptime-en.json -> "study": "LB": "7 weeks", "lastupdated": "October 21, 2026" (study permit from outside Canada, Lebanon). Times change weekly; recheck at application.
Note: plain curl to canada.ca fails: "curl: (92) HTTP/2 stream 1 was not closed cleanly: INTERNAL_ERROR (err 2)"; headless Chromium works.

## 2. CMHC Rental Market Survey, October 2025 (latest; next survey release expected ~Dec 2026)
Source page: https://www.cmhc-schl.gc.ca/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market/rental-market-report-data-tables
- Quote: "Find the results from CMHC’s 2025 Rental Market Survey (presented in Microsoft Excel tables)"; page date "December 11, 2025".
Excel files (opened & parsed; Table 1.1.1 = private apartment vacancy %, Table 1.1.2 = private apartment average rent $, column Oct-25):
- Saskatchewan: https://assets.cmhc-schl.gc.ca/sites/cmhc/professional/housing-markets-data-and-research/housing-data-tables/rental-market/rental-market-report-data-tables/2025/rmr-saskatchewan-2025-en.xlsx
- New Brunswick: .../2025/rmr-new-brunswick-2025-en.xlsx ; Ontario: .../2025/rmr-ontario-2025-en.xlsx ; Manitoba: .../2025/rmr-manitoba-2025-en.xlsx (same base path)
Quality indicators (table footnote): "a — Excellent b — Very Good c — Good d — Poor (use with caution)"; "** — Data suppressed".

| Centre | Studio rent | 1-bed rent | 2-bed rent | All-units rent | Vac studio | Vac 1-bed | Vac 2-bed | Vac total |
|---|---|---|---|---|---|---|---|---|
| Regina CMA | $901 (a) | $1,238 (a) | $1,473 (a) | $1,386 (a) | 3.3% (d) | 3.4% (b) | 2.2% (a) | 2.7% (a) |
| Fredericton CMA | $1,046 (a) | $1,203 (a) | $1,413 (a) | $1,389 (a) | 1.9% (c) | 1.7% (b) | 2.9% (a) | 2.5% (a) |
| Guelph CMA | $1,332 (c) | $1,627 (a) | $1,802 (a) | $1,733 (a) | ** suppressed | 3.4% (c) | 2.7% (b) | 3.1% (b) |
| Brandon CA | $652 (b) | $810 (a) | $1,086 (a) | $1,057 (a) | ** suppressed | 3.0% (b) | 1.6% (b) | 1.9% (b) |
Oct-24 comparison (same tables): Regina 879/1,185/1,415, vac total 2.6; Fredericton 1,011/1,137/1,341, vac total 0.9; Guelph 1,271/1,598/1,740, vac total 1.9; Brandon 622/813/1,068, vac total 1.6.
Notes: averages are for ALL existing private apartments (incl. long-term sitting tenants), so asking rents for new leases are typically higher (paraphrase/caveat, not a CMHC quote). Rent excludes utilities in some cases - UNCONFIRMED what is included.
HMIP portal (https://www03.cmhc-schl.gc.ca/hmip-pimh/en) returned HTTP 200 via curl; not needed since official Excel tables were used. StatCan 34-10-0133-01 not needed.

## 3. Other living costs: skipped (not quick); IRCC $23,448/yr is the official benchmark.
