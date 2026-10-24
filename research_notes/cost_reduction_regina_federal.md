# Cost reduction options — University of Regina (M.Eng. ESE / MKin) + Saskatchewan + federal

Check date: 24 Oct 2026. Method: official pages fetched with fetch.sh (curl; --browser for canada.ca / saskatchewan.ca / JS pages). Quotes verbatim unless marked (paraphrase). Contains only official rules, quotes, URLs and amounts; no applicant data.
Fee baseline: see deepcheck_regina.md §5 (2026-27 rates; International Surcharge 1,487.25/term; U-Pass 90.00/term; H&D 225.85 Fall only).

## Blocked hosts
- tools-student-aid.edu.service.canada.ca (ESDC designated-institutions list, International: https://tools-student-aid.edu.service.canada.ca/en/designated-institutions-list.html?province=INTER, redirected from tools.canlearn.ca): curl `curl: (60) SSL certificate problem: unable to get local issuer certificate`; Chromium `net::ERR_CERT_AUTHORITY_INVALID` (Issuer: Entrust OV TLS Issuing RSA CA 2). Not bypassed. → whether a Lebanese institution is on the international designated list is UNCONFIRMED.
- 404s (not blocks): FGSR costofstudy.pdf; FGSR calculator.html; /graduate-studies-research/current-students/funding-and-awards.html

## Plan
1. UR FGSR scholarships/awards; Engineering & KHS grad awards; UR International awards; tuition reimbursement initiative; payment plans; GTA/RA; on-campus jobs
2. Fee opt-outs: U-Pass; Health & Dental
3. Saskatchewan Graduate Retention Program
4. Federal: off-campus work hours; on-campus work; spouse OWP; CRA tuition credit
5. Other savers: fewer terms; Spring/Summer; housing; cost-of-living estimate

## 1. U of R FGSR scholarships, awards, GTA (all HTTP 200 via curl unless noted)

### 1a. Gatekeeping rules
- Calendar 2026-27 PDF https://www.uregina.ca/graduate-studies-research/assets/docs/fgsr-docs/2026-2027-graduate-calendar.pdf, "Classification of Students": Fully-Qualified = "a 4-year degree with a minimum grade point average of 70%" in "a field closely related to the baccalaureate"; "Applicants with an overall average below the minimum may be considered for this category if their average over the last two complete years is 75% or more." / "Only fully-qualified students are eligible to hold funding provided by FGSR." Probationary = "marginal for admission". → Applicant at the 70% line: fully-qualified status UNCONFIRMED (depends on how FGSR reads the record and whether BME counts as "closely related"); must be confirmed in the offer letter.
- Calendar "Scholarships and Teaching Assistantships/Fellowships": "Students should not assume that an offer of admission is associated with financial support." / FGSR funds "are available only to fully qualified students in master's and doctoral programs." / TAs "typically available only in the fall and winter terms."
- FAQ PDF (Apr 2025) https://www.uregina.ca/graduate-studies-research/assets/docs/scholarships-docs/faqs-apr-2025.pdf: "As an international student, you are eligible for all University of Regina graduate awards, except those that require Canadian citizenship or permanent residency." GAP competitions: "Winter (deadline is February 28), Spring (deadline is May 30) and Fall (deadline is September 29)." Entrants with no U of R grades "MUST also provide a copy of your last institution transcript along with the grading key".
- Scholarships index https://www.uregina.ca/graduate-studies-research/scholarships/index.html: GAP windows "Sept. 1–29 / Feb. 1–28 / May 1–30".

### 1b. FGSR entrance / special funding (pages under https://www.uregina.ca/graduate-studies-research/scholarships/external/<slug>.html)
| Award | Value | Key eligibility quote | Applicant |
|---|---|---|---|
| UR Excellence Entrance (fgsr-ur-excellence-entrance-scholarship) | $10,000 (10/yr) | "Students must have previously completed an undergraduate degree from the University of Regina." + "minimum of a first class average (equivalent to a minimum of 80%...)" ; deadline Feb 28 | NO (non-U of R degree; 80%) |
| UR Scholars Entrance (fgsr-ur-scholars-entrance-scholarship) | "Full tuition and associated fees ... up to 2 years for a Masters student" | "thesis based, fully-qualified"; 80%; "Nominations ... made by each faculty"; June 30; open to "International student" | NO (thesis only; 80%) |
| Opportunity Award (fgsr-opportunity-award) | up to ten × $2,000; automatic | "previously completed an undergraduate degree from the University of Regina within the last two years" | NO |
| Graduate Scholarship Base Fund / URGS (fgsr-graduate-scholarship-base-fund-gsbf) | "URGS: A minimum of $500 per semester"; faculty-set | "Master's students must have a minimum of 75% coming into their Master's and must maintain 80% throughout"; URGF/URGA "only ... thesis-based"; deadline "As determined by the Academic Unit" | NO at entry (75% bar); course-based eligibility for URGS not excluded in text — UNCLEAR, ask unit |
| Guaranteed Minimum Funding (fgsr-gmf-program) | $15,500/yr | "fully-qualified graduate in a PhD program" | NO (PhD only) |
| GTA (fgsr-graduate-teaching-assistantship-gta) | CUPE 2419 salary, "120 hours per semester" | see 1c | UNCLEAR-competitive |

### 1c. Graduate Teaching Assistantship (GTA) — the realistic earning route
- GTA Terms of Reference (Apr 2025) https://www.uregina.ca/graduate-studies-research/assets/docs/scholarships-docs/gta-tor.pdf: "current status as a fully-qualified student in a master's or doctoral degree program" (no thesis-only restriction stated → course-based M.Eng./MKin NOT excluded by text); "The maximum number of hours of work per semester is 120."; "Students are to submit the FGSR Funding Application Form for GTAs to their academic unit"; "There are always significantly more eligible applicants ... than there is available funding."; "Grad Thrive Plus 801 ... must be completed by the end of the first semester"; GTEC (GRST 800AB) within two semesters; on-campus part-time cap "75 hours every two weeks"; "There are no restrictions for holding jobs off campus." Application form lists "Temporary Resident (study permit)" as an option.
- Pay: CUPE 2419 Salary Scales PDF https://www.uregina.ca/human-resources/assets/collective-agreements/cupe-2419-2022-2025-collective-agreement-salary-scales.pdf, "2025 – 3%": "Grad Teaching Assistant (120 hrs/semester) ... Masters 2,700.00 [w/o vacation] 2,908.80 [with vacation pay]"; "Teaching Assistant 1 (90 hrs/semester) Masters 2,025.00 / 2,181.60"; "Teaching Assistant 2 (Hourly Rate) Masters 22.50 / 24.24". Agreement is "2022-2025" (latest posted on HR page; newer scale NOT posted).
- → One Masters GTA ≈ $2,908.80/term gross (Fall & Winter only) = up to ≈ $5,817.60/yr gross; 4 terms max ≈ $11,635 gross. Competitive; not guaranteed.
- HR Student Employment https://www.uregina.ca/human-resources/student-employment.html: "Students enrolled at the U of R with a valid study permit are eligible to work on campus, subject to guidelines set by Immigration, Refugees and Citizenship Canada"; "Non-students are not eligible to apply for positions covered under CUPE 2419."; jobs at https://urcareers.uregina.ca/.

### 1d. Award database scan (listing https://www.uregina.ca/graduate-studies-research/scholarships/listing.html, --browser; 207 entries; 67 internal Unrestricted/Engineering/Kinesiology award pages opened)
GPA thresholds on award pages ("Grade point average (GPA)" field): almost all merit awards 80%+. Examples (page under /graduate-studies-research/scholarships/internal/):
- Dr. E.C. Leslie Entrance $7,500 ×3, May 30: "Have completed a bachelor's (undergraduate) degree from a Canadian university" + TGPA 80% → NO.
- Anne Rigney $9,200, May 30: CGPA "88%" → NO.
- Chancellor's Fellowship $25,000, GPA 85 → NO.
- Dr. J.D. Mollard $4,150: "Master of Applied Science or a PhD" → NO (M.Eng. excluded).
- Dr. Esam Hussein $1,800: U of R Engineering undergrads; 80% → NO.
- PTRC $9,900: Petroleum Systems Eng; 80% → NO. Gaia Power $4,750: 80% → NO. Sampson J. Goodfellow $5,200 ×3, Feb 28: "minimum GPA of 85%" → NO. Edgar Wahn $7,150: 90% → NO.
- Miklos F. Barabas $10,900 (M.Eng. eligible): "Must be a resident of Saskatchewan, or citizen of Hungary" + 80% → NO.
- Saskatchewan Innovation and Excellence: "PhD Thesis Students or Master's Thesis Students"; 80% → NO.
- Joseph W. Schwann (KHS) $2,000: "Master of Science in Kinesiology and Health Studies" or PhD → NO for MKin. Canada Games Fellowship $12,300 (KHS): research + 80% → NO. NASSM $1,600: 80% → NO.
- Centennial 2011 Legacy $5,225: "Has successfully completed 6 credit hours of any graduate studies program; - Has attained a minimum grade point average of 80%" + leadership → POSSIBLE later IF graduate average ≥80% (uses graduate grades).
- UR Alumni Assoc. Scott Irving Spirit Award $2,075 ×2, Sept 29: "Registered full-time ... Minimum CGPA of 75%" + non-academic contributions → POSSIBLE in 2nd year if U of R grad CGPA ≥75%.
- Project Resilience $5,000 ×4 (May 30 / Sept 29 / Feb 28): "Student is fleeing from an area of global conflict, - have an incoming GPA of 75%, a lower GPA may be considered on a case by case basis"; "enrolled in any graduate degree"; essay on "how the war has inhibited their ability to pay for tuition" → UNCLEAR (whether Lebanon qualifies is not defined; ask grad.funding@uregina.ca).
- U of R Family Scholarship $1,000 (80%); Graduate Single Parent Bursary $1,820 (GPA 70; single parents only); John R. Kowalchuk $2,050 (GPA 70 but "studying Saskatchewan OR Prairie culture OR history") → NO.
- International category: only "International Doctoral Student Award(IDSA) $1450" (doctoral) and CSC (doctoral) → none for international master's.
- Conference travel awards (FGSR / URGSA) exist but are post-travel reimbursements, not cost reduction.

### 1e. Tuition "reimbursement initiative" — CONFIRMED undergraduate-only
- Student Fees page https://www.uregina.ca/financial-services/fees.html (newest schedules "2027 Winter Fee Schedules ... Information Last Updated: October 19, 2026"): "Are graduate students eligible? Currently, the reimbursement initiative applies only to eligible international undergraduate students." Also limited to students who "began their full-time studies in Spring/Summer 2026 or earlier"; final term "Spring/Summer 2029". → NO for applicant (graduate, and Fall 2027 start).

## 2. Mandatory fee opt-outs
Source: Student Services FAQ https://www.uregina.ca/students/services-faq.html (HTTP 200).

### 2a. Health & Dental plan ($225.85/yr, charged Fall)
- "The plan for full-year coverage (Sept 1 – August 31) is $225.85 ($101.15 for Health coverage and $124.70 for dental coverage)."
- "You may choose to opt-out, if you have comparable alternative coverage, such as a spouse, parents, or employer plan. (Note: Saskatchewan Health or International Emergency Insurance are not considered comparable alternative coverage)."
- "Proof of alternative coverage is required." / "Separate opt-out requests are required for health coverage and dental coverage." / "Only Fall term opt-outs allowed." / 2026 window "August 1, 2026 to September 14, 2026. No exceptions"; credit "by November 15, 2026". Contact uofregina@mystudentplan.ca.
- → Saskatchewan Health Card does NOT count. Applicant can opt out only with a genuine spouse/parent/employer extended-health plan. Saving if eligible: $225.85 per Fall (×2 = $451.70 over a 2-Fall program). Realistically NO.

### 2b. U-Pass ($90/term)
- "The cost is $90 per semester." Conditions: "Live in University of Regina residence" / "Live within Regina's designated opt-out zone (within 1 km from campus)" / "Live outside Regina city limits and commute to Regina for classes (within 75 km from Regina)" / "Registered in all online/remote/distance courses with NO on-campus component" / "Have a medical disability that precludes the ability to ride the bus/Paratransit" / "Experiential learning requirement (eg. practicum, internship, fieldwork, outgoing exchange) outside Regina city limits."
- Deadline: "the 100% add/drop deadline for registration each semester"; S/S uses "Part of Term (POT) 1 deadlines"; documentation required; form in UR Self Service.
- → Saving $90/term (5 terms = $450) only if living in residence or within 1 km of campus (or MKin practicum outside Regina). Note: in a term with no on-campus class/registration no code is assigned ("you have not been charged the UPASS fee").
- No other student-fee opt-outs found: SSHW 117.65 "mandatory even if the student does not access facilities" (deepcheck_regina.md §5).

### 1f. UR International awards — undergraduate only
- https://www.uregina.ca/ur-international/scholarships.html: "All international undergraduate students who apply for admission are automatically considered" (International Entrance Scholarship $5,000 at 83%; Student of Distinction; International Undergraduate Student Bursary). No graduate award listed → NO for applicant.

### 1g. Payment plan / payment method (not a reduction, avoids penalties)
- https://www.uregina.ca/financial-services/payment_methods.html: "A one-time 3.0% enrollment fee is required at the time of sign-up." / "Four Convenient Installments" (Fall: enrolment, Oct 1, Nov 2, Dec 1) / "A $50 late fee applies to overdue payments." / eligibility "previous term balance less than $2,000". → COSTS 3%; useful only for cash-flow. Flywire: "excellent foreign exchange rates ... save a significant amount of money, compared to traditional banks and credit card exchange rates" (no figure).
- https://www.uregina.ca/financial-services/student-resources.html: "Late payment charges accrue at a rate of 1.5% of the outstanding balance per month." → pay by the penalty-free deadline. T2202 "accessible for printing from UR Self-Service by the end of February".
- https://www.uregina.ca/financial-services/income-tax-for-students.html: T2202 "doesn't confirm eligibility for tax credits. Each student must assess their eligibility."

### 1h. Co-op (earning, not a fee saving)
- https://www.uregina.ca/graduate-studies-research/current-students/graduate-co-operative-education.html: "Students will pay tuition or a fee to participate in the co-op program ... equivalent to the undergraduate co-op fees, plus all mandatory student fees, as well as the international surcharge where applicable." / "Graduate work term courses will not replace courses or requirements" / "International students should apply for a work visa two terms before". Engineering lists "Co-op (MEng, MASc)" for ESE (https://www.uregina.ca/engineering/graduate-students/Index.html). Co-op fee 1,149.00/term (deepcheck_regina.md). → Adds ≈ $1,149 + surcharge 1,487.25 + mandatory fees per work term; net positive only if paid placement; extends program. UNCLEAR value.
- Engineering grad page also states: "Fall intake - apply by January 31" / "Electronics MENG students do not need to contact professors". No Engineering-specific graduate award list found beyond FGSR database (fees-finances page links only SAMS [undergrad], loans, REEF).
- KHS: no separate graduate awards page found on https://www.uregina.ca/kinesiology-health-studies/ (index has no award link); KHS awards are in the FGSR database (see 1d). KHS deadline clause "used when determining scholarship distribution/eligibility" (deepcheck_regina.md).

## 5. Other cost savers at Regina

### 5a. Fewer terms (largest controllable saving)
- Calendar 2026-27 "Registration": "the maximum course load one can self-register for is 6 credit hours per term; Approval to register for additional credit hours will be reviewed by the academic unit to a maximum of 12 credit hours". "International students must register every term. Full-time in fall and winter terms, and minimally part-time in the spring/summer term." BUT "Scheduled Breaks: Spring/Summer may be a scheduled break for graduate students in Masters and Post-Graduate Diploma programs only (all registration regulations still apply)." and "New international graduate students are required to register for a minimum of 6 credit hours in their first term." → whether S/S can be an unregistered break for an international master's student is AMBIGUOUS (same as deepcheck item 10); ask FGSR.
- Per-term fixed costs (2026-27): International Surcharge 1,487.25 + Students' fees base 44.60 + SSHW 117.65 + ATF 26.80 + U-Pass 90.00 ≈ $1,766.30/term (deepcheck_regina.md §5). Arithmetic from deepcheck totals: M.Eng. 4 terms 25,620.40 vs 5 terms 27,386.70 → saves 1,766.30; vs 6 terms 29,153.00 → saves 3,532.60 (2026-27 rates).
- Thesis-maintenance trap: calendar "Students must be registered in the term in which their thesis, project, practicum, or exhibition is examined" and maintenance GRST 995AA thereafter → finish the project inside the last course term to avoid an extra billed term.

### 5b. Housing (published by U of R)
- Residence rates 2026-27 https://www.uregina.ca/housing-services/payment-fees.html ("Rates listed are for the 2026-2027 Academic Year", "per person, per bedroom, each term"): College West 6/7-Bedroom Apartment "$3,202.00"/term; Paskwāw/Wakpá Dorm Shared Washroom "$2,395.00" (requires meal plan, min "$1,500" per Fall/Winter term); 4-Bedroom Apartment "$3,482.00". Fees: application "$50", "Confirmation Fee $400", "Activity Fee $20"; tenant insurance auto (opt-out with proof).
- Living in residence also qualifies for U-Pass opt-out ($90/term).
- Institutional Research summary 2026-27 (reported to StatCan June 2026) https://www.uregina.ca/institutional-research/assets/statistics/tuition-and-related-fees/2026-27-summary-tuition-living-costs.pdf: on-campus "Room Only $6,404 [lower] $9,160 [upper]" per 8-month year; "Meal Plan Only $3,000 $7,100".
- No published off-campus rent figure from U of R found (newly-admitted page lists Kijiji / Facebook Marketplace / UsedRegina / URSU Classified only).

### 5c. Cost-of-living estimate
- FGSR tuition page: "This amount does not include living expenses" — no living estimate on it. Calendar says "annual estimates of costs of living are regularly updated and are available on the FGSR website", but FGSR cost-of-study PDF https://www.uregina.ca/graduate-studies-research/assets/docs/admissions-docs/costofstudy.pdf → HTTP 404 (search snippet showed Fall 2023 data; not used). Graduate calculator https://uregina.ca/graduate-studies-research/future-students/calculator.html → 404.
- UR International (undergraduate example) https://www.uregina.ca/ur-international/tuition-and-fees.html: "Books and Supplies $1,500 / On-Campus Housing** $7,000 / Food and Fun $6,000" per 8 months (undergraduate; not a graduate figure).

## 3. Saskatchewan Graduate Retention Program (GRP)
Source: https://www.saskatchewan.ca/residents/education-and-learning/graduate-retention-program (Chromium; canonical URL) + GRP FAQs PDF https://publications.saskatchewan.ca/api/v1/products/125797/formats/147120/download (HTTP 200).
- "The Graduate Retention Program (GRP) provides a tax rebate to eligible post-secondary graduates who live and file income tax in Saskatchewan."
- Eligibility: graduated from an approved program at an "eligible post-secondary institution" (link → ESDC master list of designated educational institutions) that is "equivalent to at least six months of full-time study" and "results in a certificate, diploma, undergraduate degree or journeyperson certification"; "live in or be moving to Saskatchewan; file Saskatchewan income tax; and have graduated within the last seven years."
- MASTER'S EXCLUDED: "*Master's and PhD degrees are not eligible for the GRP. Your undergraduate program may qualify if it meets the above requirements." → the U of R M.Eng./MKin earns NOTHING under GRP.
- Amounts (graduated on/after Oct 1, 2024): "1-year Certificate, Diploma or Journeyperson $3,600"; "2- or 3-year Certificate or Diploma $7,680"; "3-year Undergraduate Degree $18,000"; "4-year Undergraduate Degree $24,000". "based on your program and the amount of tuition paid over the course of your studies" (T2202).
- Payout: "Your maximum rebate is paid out over seven years ... 10 per cent of your tax credit in each of the first four years; and 20 per cent in each of the final three years." (4-yr degree: $2,400/yr ×4 then $4,800/yr ×3.) FAQ: "the GRP is applied as a reduction to income tax owed. Where your eligible GRP rebate is greater than the amount of income tax owed, the excess amount can be carried forward".
- International: FAQ "International students may be eligible if they stay and file income tax in Saskatchewan after graduating. If you graduated from an eligible international post-secondary institution, you will also need to complete a Canadian education credential assessment to determine GRP eligibility." Page: "If you studied internationally, save a copy of your Canadian educational credential assessment"; institutions outside SK "must apply ... through the Saskatchewan Ministry of Advanced Education".
- Lifetime: "You may be eligible to receive GRP for multiple credentials if you have not exceeded your eligible lifetime limit."
- → For this applicant: the master's itself = NO. The foreign BME bachelor's could in principle count ONLY IF the Lebanese institution is on the ESDC international designated list (UNCONFIRMED — list host blocked, see top) AND within 7 years of graduation AND tuition paid supports the amount (amount is tied to tuition paid per T2202 — how foreign tuition is measured is UNCLEAR). Ask studentservices@gov.sk.ca / 1-800-597-8278. Treat as UNCLEAR, possibly NO.

## 4. Federal rules (canada.ca, Chromium)

### 4a. Off-campus work — https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/work-off-campus.html (Page details date 2026-04-15)
- "During regular school terms or semesters You can work up to 24 hours per week."
- "If your current study permit says that you may only work 20 hours per week off campus ... you're allowed to work up to 24 hours per week as long as you continue to meet the eligibility requirements".
- "During scheduled breaks in the school year ... such as summer and winter holidays, or a reading week, you can work unlimited hours off campus" / "take courses on a part-time or full-time basis This does not affect your ability to work unlimited hours during your break."
- "If your program doesn't have scheduled breaks You can work up to 24 hours per week."
- Conditions: "full-time student at a designated learning institution"; "You've started your study program."; "Your study program is at least 6 months long"; work conditions printed on permit; SIN. "You can't work before your studies begin." On authorized leave: "can't work off campus".
- → Regina: whether Spring/Summer is a "scheduled break" for the applicant depends on U of R (calendar: "Spring/Summer may be a scheduled break for graduate students in Masters ... (all registration regulations still apply)"). Rough gross: 24 h × $15.35?? — DO NOT use; SK minimum wage not checked in this run. Use hours only.

### 4b. On-campus work — https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/work-on-campus.html (Page details date 2026-05-01)
- "There is no limit to on-campus work hours during regular school terms or semesters scheduled breaks in the school year You can work as many hours as you want as long as you're eligible."
- Off-campus location allowed if "You're working as a teaching or research assistant." and "Your work is strictly related to a research grant." etc.
- Must stop if "you stop studying full-time, unless you're in your final semester".
- U of R's own cap for GTAs who also hold part-time on-campus jobs: "75 hours every two weeks" (GTA ToR) — institutional, not IRCC.

### 4c. Spouse/common-law partner open work permit — https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/help-your-spouse-common-law-partner-work-canada.html (Page details date 2026-02-03)
- "Starting January 21, 2025, your spouse or common-law partner may be eligible for an open work permit if you have a valid study permit and you're either studying in a master's degree program of 16 months or longer ..."
- Documents: "a valid letter of acceptance from your designated learning institution (DLI)" or proof of enrolment or transcripts; "Most of the time, your spouse or common-law partner's work permit will be valid for the same period of time as your study permit."
- U of R lengths (deepcheck_regina.md): ESE "Master of Engineering – Project: 2 years"; MKin "Length: 2 years" → likely ≥16 months, BUT IRCC reads the length on the letter of acceptance; a planned 4-term (≈20-month Sept–Apr) schedule is still ≥16 months. → YES if the applicant has a spouse/partner (applicant-specific; not assumed).

### 4d. CRA tuition credit
- International students page https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/individuals-leaving-entering-canada-non-residents/international-students-studying-canada.html (Page details date 2022-01-18): "You must determine your residency status to know how you will be taxed in Canada." / "many international students who study or carry on research in Canada do establish significant residential ties with Canada." / "You are a resident of Canada for income tax purposes if you establish significant residential ties with Canada."
- Line 32300 https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses/line-32300-your-tuition-education-textbook-amounts.html (2025-11-26): "To claim your tuition fees, you must have received one of the following forms ... Form T2202, Tuition and Enrolment Certificate"; "The federal education and textbook tax credits were eliminated in 2017."
- Eligible tuition fees subpage (2026-05-15): "the fees you paid to attend each educational institution must be more than $100"; eligible include "admission fees", "charges for use of library or laboratory facilities", "application fees (but only if the student subsequently enrols in the institution)", "mandatory computer service fees", "academic fees".
- Carry forward subpage https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses/line-32300-your-tuition-education-textbook-amounts/transferring-carrying-forward-amounts.html (2025-11-26): "You can carry forward your current year's unused federal tuition fees (that you did not transfer) to claim in a future year"; "You have to claim your carry forward amount in the first year that you have to pay income tax."; "You have to file an income tax and benefit return every year if you have tuition that you are carrying forward ... If you miss filing a year ... the amount will not be carried forward"; "You may transfer a maximum of $5,000 of the current year's federal tuition amount" (to spouse/parent/grandparent).
- P105 Students and Income Tax 2025 https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/p105/p105-students-income-tax.html (2026-05-06): "The federal non-refundable tax credits are calculated by multiplying the total dollar amount by the lowest personal tax rate percentage, which is currently 15%." Scholarship exemption: awards for a program where you are a full-time qualifying student are exempt (GTA pay = employment income, not exempt).
- Saskatchewan provincial tuition credit: CRA archived 2018 SK info https://www.canada.ca/en/revenue-agency/services/forms-publications/tax-packages-years/archived-general-income-tax-benefit-package-2018/saskatchewan/5008-pc/information-residents-saskatchewan.html: "For 2018 and later tax years, tuition and education amounts have been eliminated" (only pre-2018 unused amounts carry). → only the FEDERAL credit applies.
- → Value: a CRA-resident student's eligible T2202 tuition (M.Eng. tuition 17,932.50 + International Surcharge 5,949–7,436 at 2026-27 rates; whether the surcharge and which fees appear on T2202 is UNCONFIRMED) × 15% ≈ $3,600–$3,800 (M.Eng.) / ≈ $2,800–$2,900 (MKin), non-refundable: only reduces federal tax actually owed (e.g. on GTA/part-time/PGWP earnings), carried forward if filed every year. Not cash in hand during study unless income is taxable.
