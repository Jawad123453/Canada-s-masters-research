# Education loans for international students (Lebanese citizen) — Regina M.Eng ESE / UNB M.Eng GGE, Fall 2027

Research date: 2026-11-13. Official sources only (lender sites, canada.ca, university pages). UNCONFIRMED = not stated on an official page.

## Log

## 1. MPOWER Financing (checked 2026-11-13)

Access notes: www.mpowerfinancing.com static pages fetch fine with curl; the interactive school list / eligibility checker (app.mpowerfinancing.com/eligibility) is behind a bot check ("Let's confirm you are human" page; AWS WAF "Human Verification" on JS assets) -> school-by-school and country-by-country lookup NOT possible from here. Help-centre articles read via support.mpowerfinancing.com Zendesk API (official MPOWER help centre).

- **Lending paused for 2026 (key!)** — https://www.mpowerfinancing.com/get-a-loan (banner): "temporarily unable to offer new loans for 2026." "Join our waitlist!" Status for Fall 2027 intake: UNCONFIRMED.
- **Citizenship / Lebanon** — https://support.mpowerfinancing.com/hc/en-us/articles/360021129333 (General Eligibility Information, updated 2026-10-29): "An international student from over 190 countries". No public country list; Lebanon specifically = UNCONFIRMED (checker blocked). Same article: "Canadians ... looking to study within Canada are not eligible".
- **Schools** — https://support.mpowerfinancing.com/hc/en-us/articles/360021129653 (updated 2026-11-07): "If your school isn't on our list of 50+ eligible schools, you won't be able to apply". The schools-we-support page heading now reads "MPOWER's network of schools in the U.S." and the list itself did not render (JS).
  - UNB: MPOWER blog https://www.mpowerfinancing.com/blog/graduate-studies-canada (updated 2 Apr 2026), section "Five affordable, MPOWER-eligible Canadian universities": item "4. University of New Brunswick". Blog evidence only (MPOWER's own site); program-level (M.Eng GGE) eligibility UNCONFIRMED.
  - University of Regina: not named on any MPOWER page found -> UNCONFIRMED (likely not eligible; the Saskatchewan school named is U of Saskatchewan).
- **Canada: tuition only** — https://support.mpowerfinancing.com/hc/en-us/articles/360021131013 (How can I use my MPOWER loan?, updated 2026-06-15): "For most MPOWER-eligible schools in Canada, we support only tuition expenses". get-a-loan page: "including living expenses (U.S. schools only)".
- **Amounts** — get-a-loan FAQ: "maximum of US$100,000 per application, with no more than US$50,000 allocated per term"; "Borrow US$2,001-US$100,000".
- **Rates (fixed)** — https://www.mpowerfinancing.com/repayment-examples: "lowest available interest rate without any discount or promotion is 10.24% (11.15% APR)"; "median interest rate for loans is 14.24% (15.57% APR)"; example top "16.99%, which equates to an APR of 18.88%" (origination fee 8.5%). 0.25% autopay discount (headline "Rates from 9.99% (10.89% APR)").
- **Fees** — https://support.mpowerfinancing.com/hc/en-us/articles/360021131153: "one-time origination fee starting at just 5%" (added to loan). No prepayment penalty (get-a-loan: "Prepayment penalty None").
- **Repayment** — https://support.mpowerfinancing.com/hc/en-us/articles/360046044354 (updated 2026-10-20): "interest-only payments begin 45 days after your school receives the funds"; interest-only period max 30 months, then "repay the loan in 10 years".
- **Co-signer/collateral** — get-a-loan terms table: "Collateral or cosigner Never required".
- **Visa / study-permit letter** — get-a-loan FAQ: "MPOWER can issue visa support letters at no cost ... upon final credit approval." Article 360020938334: letter includes "approved loan amount, the name of your university". Article 360039830053 (Canada section): "Obtain proof of funds from MPOWER or other sources to cover the first year". Whether IRCC accepts it = IRCC rule (see section 4); MPOWER letter is from a US lender (not a Canadian institution) — IRCC does not restrict lender nationality on the page (see below).
- **Timing** — get-a-loan FAQ: "apply for a loan a maximum of 12 months prior to when you need the money". Decision: article 360021130113: "Six to eight business days after complete document submission."

## 2. Prodigy Finance (checked 2026-11-13)

Access: prodigyfinance.com static pages + its school-search dataset (Gatsby static-query JSON https://prodigyfinance.com/assets/page-data/sq/d/799831111.json, which feeds https://prodigyfinance.com/where-can-i-study/) fetched OK; help centre read via support.prodigyfinance.com Zendesk API (HTML help pages return 403 to curl). help.prodigyfinance.com = proxy "connect_unreachable" (CONNECT 502), not needed.

- **New applications closed** — https://support.prodigyfinance.com/hc/en-us/articles/43746209305745 (Everything you need to know about 2027 applications, updated 2026-11-02): "New applications are closed for now, including for Spring 2027 and Fall 2026." "we don't have a reopening date yet." Fall 2027: "join the Fall 2027 waitlist"; "Joining doesn't give you priority". Loans page https://prodigyfinance.com/student-loans/: "Join the waitlist for our Fall 2027 intake."
- **Schools — Regina / UNB NOT supported** — https://prodigyfinance.com/where-can-i-study/ : "Explore 1137 schools across 342 universities in 12 countries." Dataset has 45 Canadian school entries (Carleton, Laval, McGill, McMaster, Queen's, SFU, TMU, UBC, Calgary, Guelph, Montreal, Toronto, Victoria, Waterloo, Western, York). No "Regina" or "New Brunswick" entry. Help article 360000145589: "If your university does not appear in our search tool, it means we don't currently fund that institution."
- **Country (Lebanon)** — article 360000145849 (Am I eligible?, updated 2026-10-24): "We are not able to fund residents of certain countries". Eligibility is by residence. Unsupported-country list article 360000134385 (updated 2026-11-11) no longer lists countries — shows only the pause text. Lebanon = UNCONFIRMED.
- **Canada residency rule** — 360000145849: "lived or worked in your study country for less than 90 days prior".
- **Rates/fees** — /student-loans/: "Master's loans starting from 11.01%* interest rate"; representative "12.69% APR representative variable" (7.70% fixed margin + 3.91% variable base), "Administration fee: USD 1,680 (4.2% of the amount borrowed)", "Processing fee: USD 500", repayable over 180 months, 30 months of initial reduced payments in the example. Variable rate.
- **Co-signer** — "No collateral, no co-signer*" (a co-signer loan product also exists: article 52145474718481 "co-signer loan agreements").
- **Visa letter** — article 360000705877 (updated 2026-08-06): "can be used as proof of funding for visa or immigration purposes"; final letter requires accepting the match and "paying the processing fee of up to USD 500". Canada page https://prodigyfinance.com/study-country/canada/: "Your loan letter sets out the amount and terms" (Prodigy's claim; IRCC acceptance is per IRCC).

## 4. IRCC proof of financial support (checked 2026-11-13)

URL: https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/get-documents/financial-support.html — Date modified: 2026-08-28.
- Section "Common documents ... / Tuition and study costs": "proof of a student or education loan from a bank".
- Same section: "This is not a complete list." / "There may be other types of documents you can provide as proof instead." -> a non-bank lender letter (MPOWER = US lender; Prodigy = UK FCA-regulated lender) is not named; acceptance is at officer discretion -> UNCONFIRMED whether a non-bank loan letter counts as "from a bank".
- Requirement: "you have enough financial resources for the first year" and, for programs >1 year, "tell us how you plan to pay" for the full duration; "We'll assess the amount of funds you have and their source".
- Living-cost amount, single applicant, applications "on or after September 1, 2026", outside Quebec: "$23,448" (excluding tuition and transportation).
- "If your country uses foreign exchange controls, you must prove that you'll be allowed to export funds" (relevant to Lebanese banks).
- Note: MPOWER funds tuition only at most Canadian schools (see section 1), so an MPOWER letter could not cover the $23,448 living component by itself.

## 5. University pages on loans for international students (checked 2026-11-13)

### University of Regina
- https://www.uregina.ca/cost-aid/funding/student-loans.html (Government Student Financial Assistance, "International Students" section): "International students on a study permit are encouraged to explore financial aid options available from their home country or to contact local banks for lending options." No lender named/partnered.
- https://www.uregina.ca/cost-aid/funding/additional-funding.html ("Bank Loans"): "Financial institutions provide student lines of credit to qualified students". "Loans for Newcomers to Canada" (Achēv Career Loans) are for "permanent residents, Canadian citizens or Convention Refugees" -> not study-permit holders.
- No MPOWER/Prodigy mention found on uregina.ca.

### University of New Brunswick
- https://www.unb.ca/international/financial/index.html: covers fees, scholarships, needs-based aid ("Financial aid is meant to supplement a student's resources"); no loan programme for international students.
- https://unb.ca/sas/finance/loans.html ("Lines of credit"): "Some financial institutions lend money for school." Otherwise only Canada Student Loans (residents) and US Direct Loans ("citizens, permanent residents, and eligible non-citizens of the United States").
- No MPOWER/Prodigy mention found on unb.ca.

## 3. Other lenders (checked 2026-11-13)

### Scotiabank — ScotiaLine Personal Line of Credit for Students
URL: https://www.scotiabank.com/ca/en/personal/loans-lines/line-of-credit/scotialine-personal-line-of-credit-students.html
- "International students" tab: "International students enrolled in a Canadian Graduate program can apply with a co-borrower who is a Canadian citizen/permanent Canadian resident."
- Footnote 5: "Only international students enrolled in a Canadian Graduate program can apply with a co-borrower" ... "and must provide valid proof of enrollment."
- Limits (international, graduate, program < 18 months): "$100,000" max total; > 18 months: annual limit = approved total / years.
- Rate: "Scotiabank prime plus 0.50%" (variable); interest-only while studying + "12-month grace period" on principal.
- Liability: "jointly and severally liable" (borrower and co-borrower).
- No nationality restriction stated for the student; Regina/UNB = Canadian graduate programs -> in scope. Whether it can be opened from abroad before arrival (needed for IRCC timing) = UNCONFIRMED. It is a bank -> fits IRCC "proof of a student or education loan from a bank".

### TD — Student Line of Credit
URL: https://www.td.com/ca/en/personal-banking/products/loans-and-lines-of-credit/student-borrowing
- "International students attending an accredited university or college in Canada or elsewhere must have a co-borrower who is a Canadian resident and a TD customer in good standing."
- "Co-signer requirements are dependent on your credit history and will be assessed on a case-by-case basis."

### RBC — Royal Credit Line for Students
URL: https://www.rbcroyalbank.com/personal-loans/student-loans/overview.html
- Requires "confirmation of enrollment in an eligible Canadian post-secondary educational institution"; rate example "RBC Prime minus 0.25%" (preferred rate offer).
- "If your credit history is limited ... a co-signor may be required." International-student-specific co-applicant rule: the RBC Money Academy article that (per search snippet) states it now returns 404 -> UNCONFIRMED.
- https://www.rbcroyalbank.com/new-to-canada/international-students/ : "An RBC GIC meets the proof of financial support requirement for a study permit." (GIC, not a loan).

### CIBC
- https://www.cibc.com/en/student/student-hub/international-students.html — no international-student line-of-credit eligibility found; membership T&Cs say "legal resident of Canada" for student LOC-based membership. International student LOC terms = UNCONFIRMED.

### Leap Finance
- https://leapfinance.com/faq (Eligibility): "master's or postgraduate programs in STEM courses at US universities". https://leapfinance.com/loan-features/usa: "for ambitious Indians students". -> Not applicable (US schools, Indian students). FAQ: "Yes, we require a co-signer".

## 6. Lebanese banks (quick check, 2026-11-13)
- IBL Bank KFS PDF https://ibl.com.lb/Library/Assets//Gallery/IBL/KnowYourRights/KFS/EDUCATIONAL%20LOAN%20KFS%20(NEW).pdf: "Finance the education of students accepted in universities (Lebanon and Abroad)"; "Maximum loan Amount LBP 150,000,000"; "Loan Currency LBP"; requires guarantor; references "4% (for year 2018)" -> document is dated (pre-crisis LBP terms); LBP cap is now a trivial amount in USD terms; current availability UNCONFIRMED.
- Byblos Bank University Educational Loan page now 404 (https://www.byblosbank.com/personal/loans/university-educational-loan). BCN "BDL educational loan" page loads but no terms extracted. No current USD-denominated study-abroad loan found on an official Lebanese bank page -> treat as not available / UNCONFIRMED.
- IRCC caution (section 4): "If your country uses foreign exchange controls, you must prove that you'll be allowed to export funds".

## Blocked / failed hosts
- app.mpowerfinancing.com/eligibility and www.mpowerfinancing.com in headless browser: bot-check page "Let's confirm you are human"; app JS assets return AWS WAF "Human Verification" HTML.
- help.prodigyfinance.com: proxy "connect_unreachable" (curl: (56) CONNECT tunnel failed, response 502). support.prodigyfinance.com HTML: HTTP 403 (API worked).
- RBC Money Academy student-LOC article: HTTP 404.
- leapfinance.com/faq via curl: FAQ text not rendered ("Error fetching FAQs at the momemt"); browser render worked.

## Bottom line (2026-11-13)
- MPOWER and Prodigy (the two no-co-signer lenders) both have NEW lending paused (MPOWER: "unable to offer new loans for 2026"; Prodigy: "New applications are closed for now") with Fall 2027 waitlists only.
- Prodigy: Regina and UNB are not in its supported-school dataset -> not an option even if it reopens.
- MPOWER: UNB named "MPOWER-eligible" (blog, Apr 2026); Regina not found; Canada = tuition-only funding at most schools; Lebanon not individually confirmable.
- Realistic route with a Canadian co-signer: Scotiabank student line of credit (international graduate students, Canadian citizen/PR co-borrower, up to $100,000, prime + 0.50%) or TD (co-borrower Canadian resident & TD customer). Bank-issued -> matches IRCC wording "student or education loan from a bank"; pre-arrival availability UNCONFIRMED (proof of enrolment required).
