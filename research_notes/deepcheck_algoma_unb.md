# Deep check — Algoma MCS (12-month) vs UNB M.Eng. Geodesy & Geomatics (course-based)

Date: 23 Oct 2026. Method: official algomau.ca / unb.ca pages and canada.ca DLI JSON fetched in full with fetch.sh (curl or headless Chromium). Quotes are verbatim unless marked (paraphrase).
Privacy: this file records only university/IRCC rules, quotes, URLs and costs.

## Blocked hosts / fetch errors
- docs.google.com (Algoma Graduate Student Handbook): "Sorry, the owner hasn't given you permission to download this file." / export HTTP 401 / empty DOM in headless Chromium. All algomau.ca, unb.ca and canada.ca pages loaded (HTTP 200).

## Plan
A. Algoma MCS: admission rule, Lebanon row, backlogs, foundation courses, WES, pre-screening; English (Duolingo/IELTS, exemption proof); intakes (Fall 2027 / Winter 2028), fee, checklist; campus; tuition rows 2026-27/2027-28, ancillary, UHIP, VIP; DLI rows.
B. UNB GGE MEng: program + SGS bar, degree list, background courses, WES; SGS English; application mechanics, checklist, deposit; program structure/course schedule; 2026-27 fee sheet recompute; DLI row.

## A. Algoma University — Master of Computer Science, 12-month (course-based)
All pages fetched in full 23 Oct 2026, HTTP 200 (curl). Program page: https://algomau.ca/academics/graduate-programs/master-of-computer-science/ (the .../master-of-computer-science-12mth/ URL serves identical content).

### A1. Admission
- Program page, "2. Check out our Admission Requirements" -> "Admission Requirements (Beginning with the Fall 2026 intake)": CONFIRMED verbatim: "four-year computer science or closely related undergraduate degree from an accredited university, with a minimum 70% (B) average over four years, OR a minimum 75% (B+) average over the last two years of full-time undergraduate study."
- Same section: "having two or more backlogs in computer science core courses will significantly decrease an applicant's chances for admission". "Backlog" is not defined on the page (paraphrase: commonly used to mean a failed course, whether or not later cleared — UNCONFIRMED how Algoma counts failed-then-passed attempts).
- Foundation list, CONFIRMED: "Applicants should have completed any three of the following foundational (prerequisite) courses": Introductory Programming (Java, Python, C, C++, C#); Data Structures; Theory of Computing; Analysis of Algorithms; Database Programming; Web Programming; Software Engineering; Techniques of Systems Analysis; Object Oriented Analysis and Design; Microprocessor and Assembly Language Programming; Computer Organization; Operating Systems; Computer Networks; Introductory Computer Graphics; Introductory Statistics.
- CONFLICT on the same page, "6. Apply" checklist: "You completed the following course prerequisites: Introductory Programming, Introductory Statistics, Computer Organization, Data Structures II, Computer Networks, Theory of Computing" and "Attained a minimum 75% (B+) average over the last two years". Checklist also says "Applicants need to meet all the above-listed conditions". So the page contradicts itself (any three / 70%-over-four-years vs six named / 75%-last-two-years).
- "closely related" is not defined anywhere on the page. Intro sentence: "designed for Bachelor degree graduates in computer science, information technology (IT) and related areas."
- WES: OPTIONAL. "Supplementary material (Optional): ... WES (World Education Services) evaluation for institutions attended outside of North America." (with optional personal statement up to 500 words and CV).
- Pre-screening: CONFIRMED "Note: Email pre-screening is not available, submitting an application is required for assessment." Also "graduate admission decisions ... are final and not subject to appeal."
- Graduate credential page https://algomau.ca/students/international-students/international-credential-equivalencies-grad/ — intro: "requires a minimum Ontario equivalent grade of B or B+, as required by the specific program ... with the required academic standing achieved in the final two years of full-time study." "provided as a general guideline only".
- LEBANON row, CONFIRMED verbatim (unchanged since earlier rounds): "Lebanon / Minimum GPA Required: 75% or 12/20 / B Plus GPA: 80% or 14/20 / Bachelor's Degree Equivalent: Bachelor's or Licence / English Language Test Requirement: Required".
- Inconsistency: 12/20 (=60% linear) is not equivalent to 75%; other rows pair "Burundi: 70% or 14/20", "Iran: 14/20 (B) ... 16/20 (B+)". Read with the MCS rule, a Lebanese "B" = 75% (four-year route) and "B+" = 80% (last-two-years route) on the /100 basis; on the /20 basis B = 12/20, B+ = 14/20. Which basis applies to a /100 transcript: UNCONFIRMED.
- Pre-application FAQ PDF https://algomau.ca/wp-content/uploads/2024/03/Pre-application-FAQ-MCS-.pdf : "Those who do not meet the minimum requirements will not be selected"; extra documents (references etc.) "we will not request or consider"; "Conditional offers are not issued in the Master's program"; "no part-time option at admission"; "completed in one year (12 months) ... three consecutive semesters"; "planned around admission cycles (Fall and Winter)"; no scheduled break between semesters.
- Graduate Student Handbook (linked from program page) is a Google Drive file: https://docs.google.com/document/d/1qYZNd9UkA-mcD5m3UE0Q4cX8v9Pde9w5/ — NOT READABLE: download returns "Sorry, the owner hasn't given you permission to download this file."; headless Chromium dump empty.

### A2. English
- Program page "English Language Requirements", CONFIRMED: "IELTS Academic: 6.5 overall, no band lower than 6.0"; "Duolingo English Test (DET): 115 overall, no band lower than 95"; TOEFL iBT "93 overall, minimum 20 in each band" (new scale 4.0); PTE "65 overall, minimum 60 in each band"; CAEL "70, no band below 60"; CAE "176".
- Validity: "English proficiency test scores must have been taken within 24 months of the application submission date."
- Exemption: "Completed four or more years of full-time studies in an approved post-secondary institution outside Canada where English was the primary language of instruction." No proof (MOI letter etc.) is specified on the MCS page — NOT FOUND.
- But: Lebanon row "English Language Test Requirement: Required"; Step 5 requires "Language test result (for international applicants that completed their undergraduate degree in a country where English is not an official language)"; general English page https://algomau.ca/admissions/admissions-requirements/english-language-requirements/ country-exemption list does not include Lebanon (and "Exemption is not automatic"; some countries "require an MOI"). That page says "Graduate programs have separate English language proficiency requirements." => Treat a test as required for Lebanon.

### A3. Intakes, fee, documents, deposit, timeline
- Program page (23 Oct 2026): "Applications are currently open for: WINTER 2027 intake: Application opens on June 29, 2026." International: "Applications accepted until December 1, 2026"; "Document submission deadline: December 15, 2026". Domestic: Jan 6 / Jan 8, 2027. Fall 2027 / Winter 2028: NOT POSTED anywhere found (program page, graduate index, international how-to-apply page, web search). Intakes are Fall and Winter per FAQ.
- Decision timeline: "between two and six weeks"; "we do not issue application status updates prior to the completion of the review process".
- Application fee: "$125 for International applicants" (program page Step 5; Service Fees on https://algomau.ca/students/student-accounts/tuition-residence-fees/ "Application Fee International $125.00").
- Documents (Step 5): application form; fee; "Undergraduate degree transcript ready to be uploaded"; language test; "Official transcripts will be requested at a later time, following the pre-screening of the application". Optional: personal statement (<=500 words), CV, WES. No references required (FAQ: references not considered).
- Deposit: amount not on graduate pages. Payment page https://algomau.ca/?p=155 (Payment Information & Important Dates): "New Students: Deposit amount and due date are outlined in your Letter of Offer (LOA)." International how-to-apply page https://algomau.ca/admissions/how-to-apply/international-students/ : "Payment of the non-refundable deposit ... secures your seat in the program at the campus listed on your LOA"; deferral "once to the next available intake with no formal reason required".

### A4. Campus / delivery
- 12-month MCS page: no campus stated. Faculty committee: Dean Xu "Sault Ste. Marie Campus"; Graduate Officer Sultana, Khandaker, Asad "Brampton Campus".
- NEW: Brampton campus page https://algomau.ca/about/our-campuses-overview/brampton/ : "Explore all programs available at our Brampton campus." lists "Master of Computer Science — Designed for Bachelor's degree graduates in computer science, IT, and related areas" (links to the 12-month page) and the 16-month specialization. Sault Ste. Marie campus page lists no programs (links to general list). 16-month page by contrast says "Available in Brampton and Sault Ste. Marie Campus". => 12-month MCS: Brampton CONFIRMED as a delivery campus; Sault Ste. Marie NOT FOUND for the 12-month MCS. Campus is fixed on the LOA.
- Delivery: no online option stated; course schedules only via student portal (https://algomau.ca/course-schedules/). In-person assumed (paraphrase), UNCONFIRMED in words.

### A5. Cost (2026-27 rates; "The fees listed below are for the 2026/27 academic year and are subject to change.")
- Tuition page https://algomau.ca/students/tuition-scholarships-financial-aid/graduate-programs-tuition-awards-and-funding/ , table "Master of Computer Science (Course-Based)| MCS", row "International Full-Time / 2026 Fall & 2027 Winter per semester / $8,500.00* / $485.51** / $8,985.51". (Prior row "2026 Spring per semester $8,049.30* $485.51** $8,534.81".) Spring 2027 / 2027-28 rates: NOT POSTED.
- "** The SSM bus pass is an additional $82.80 per semester" (SSM only).
- UHIP: "$316 per semester beginning in 26F"; UHIP page https://algomau.ca/students/international-students/mandatory-health-insurance-plan-for-international-students/ "UHIP Rates for 2026/27": September 2026 "$948", January 2027 "$632", May 2027 "$316" (single).
- VIP: "All full-time students require VIP Insurance coverage at the rate of $320 per year." (opt-out only with comparable coverage).
- Other possible fees (ancillary page): "LABORATORY/STUDIO FEE: Selected courses in ... Computer Science ... additional $22 per 3-credit course"; "OFF-SITE ANCILLARY FEE: ... applies to courses not offered on the Sault Ste. Marie, Ontario campus" (amount NOT STATED — relevant if Brampton); "Convocation Fee ... $100.00".
- Arithmetic, 3 semesters at 2026-27 rates: tuition+ancillary 3 x 8,985.51 = 26,956.53; UHIP 3 x 316 = 948; VIP 320 -> 28,224.53. + application 125 + convocation 100 = 28,449.53. If all 10 courses carry the $22 lab fee: +220 -> 28,669.53. (SSM bus pass would add 248.40, not applicable in Brampton.)
- Fall 2027 entry (2027-28 rates unknown): at the last observed +5.6% step (8,049.30 -> 8,500): tuition 8,976 x 3 = 26,928 + ancillary 1,456.53 + UHIP 948 + VIP 320 = 29,652.53 (before app/convocation/lab/off-site fees) -> fee-increase risk; could reach ~30k.

### A6. PGWP / DLI
- https://www.canada.ca/content/dam/ircc/documents/json/dli/dli-full-list.json (curl --compressed, HTTP 200, 1,425 rows, 23 Oct 2026):
  - "Algoma University","DLI #":"O19395422197","City":"Brampton","Campus":"Algoma at Brampton","Grad Program":"Yes","PGWP":"Yes","Public institution"
  - same DLI, "City":"Sault Ste. Marie","Campus":"Main Campus","Grad Program":"Yes","PGWP":"Yes"
  - same DLI, "City":"Timmins","Campus":"Algoma at Timmins","Grad Program":"Yes","PGWP":"Yes"
  - Campus does not change PGWP eligibility (all rows Yes).
- IRCC PGWP rules (https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/after-graduation/about.html , .../eligibility.html , .../eligibility/language-results.html, headless Chromium):
  - "You can apply for a 3-year PGWP, even if your master's program was less than 2 years, as long as your program was at least 8 months".
  - Master's graduates: "minimum level of Canadian Language Benchmarks (CLB) 7 ... in all 4 language areas"; "There are no field of study requirements for graduates with a bachelor's degree, master's degree or doctoral degree."
  - Accepted PGWP tests: CELPIP (General), IELTS (General Training), PTE Core, TEF Canada, TCF Canada (Duolingo is not listed).
  - "You must complete at least 50% of your program within Canada".

## B. UNB Fredericton — M.Eng. Geodesy & Geomatics Engineering (course-based)
All pages fetched in full 23 Oct 2026, HTTP 200 (curl).

### B1. Admission
- Dept MEng page https://www.unb.ca/fredericton/engineering/depts/gge/graduate/master-of-engineering.html , "MEng admission requirements": CONFIRMED "Minimum GPA: 3.0/4.3, or B Average (the equivalent of 70%)"; degree "in Geodesy, Geomatics, or a related field (such as Geology, Geography, Physics, Math, Engineering, Science, Computer Science) from an accredited university" (Engineering listed; biomedical not named specifically); "Supervisor: None required. The Director of Graduate Studies will advise on course selections."
- SGS program page https://www.unb.ca/gradstudies/programs/gge.html : "All applicants should have a minimum 3.0 CGPA equivalent to a ( B Average)." (no 70% here); related field "such as geology, physics, math, engineering, or science"; "complete application including three reference letters"; deadline "MEng (Feb. 1, for international applicants and June 1, for domestic applicants)"; "Duration: 12-24 Months (MEng)"; "Entry Terms: Fall (MEng Fall intake only)". Contact Lisa Valenta (l.valenta@unb.ca) / Dr. Richard Langley, DGS; 1-506-458-7085.
- SGS regulations https://www.unb.ca/gradstudies/current/resources/regulations-and-guidelines/regulations/admissions.html : CONFIRMED "cumulative grade point average of at least 3.0. For foreign applicants, these requirements translate to at least a B average (North American System) or upper second class standing (British System)". Probation route example needs "exceptional (A range) performance in the last two years".
- Foreign-credential conversion table / Lebanon row: NOT FOUND on any UNB page read. No rule on repeated/failed undergraduate attempts found.
- WES: SGS FAQ https://www.unb.ca/gradstudies/admissions/faq.html "a course by course (CxC) WES evaluation is acceptable" (alternative to transcripts, not required).
- Background courses: none required for admission (not stated). Suggested sequences include 3000-5000-level GGE courses that count as "alternate level courses that carry graduate level credit" (MEng checklist PDF).

### B2. English
- SGS International page https://www.unb.ca/gradstudies/admissions/international.html : CONFIRMED "Duolingo English Test / Minimum overall score of 125. / Minimum subscore of 105."; "IELTS ... Academic Module / Minimum overall band score of 7. / One Skill Retake accepted. / Online version not accepted."; TOEFL iBT pre-2026 "Minimum score of 94"; post-Jan-2026 "Minimum of 5 overall with no less than 4.5 each in speaking and writing"; PTE Academic "65"; CAEL "80".
- Dept MEng page: "IELTS band 7 and/or ... TOEFL score of 92" (SGS GGE page says TOEFL 94 — inconsistency; Duolingo not mentioned by dept).
- "The School of Graduate Studies will not issue waivers based on language tests. Applications will not go for review until the language requirement has been met".
- NEW exemption: "An international applicant is not required to submit proof of English Language proficiency if: The applicant has studied in an English-speaking institution for more than two years within the last five years." (plus a country list; Lebanon not on it). Required proof for the institution-based exemption: NOT STATED on the page (ask SGS; likely a medium-of-instruction letter — UNCONFIRMED).

### B3. Application mechanics
- Common questions https://www.unb.ca/fredericton/engineering/depts/gge/graduate/common-questions.html : CONFIRMED "Start date is fall term only, apply from November to February to be considered for fall start."; MEng "course based / self-funded / ... no thesis, no supervisor required".
- CONFLICT: GGE How-to-apply page https://www.unb.ca/fredericton/engineering/depts/gge/graduate/prospective-students.html says "There is no deadline to apply. Applications are reviewed all year round." vs MEng page "Entry term: September. Apply by Feb. 1." and SGS "Feb. 1, for international applicants". Use 1 Feb 2027 for Fall 2027.
- Documents (GGE how-to-apply): "Resume/CV"; "Statement of Purpose – 1-2 pages"; "Transcripts – unofficial copies are acceptable for the initial application"; "Proof of English Language Proficiency"; "Three References – at least two references should be from academic sources." Advice: "apply 6-12 months in advance".
- Fee: SGS admissions https://www.unb.ca/gradstudies/admissions/index.html "International - $125.00"; FAQ "Application fees are mandatory and non-refundable."
- Timing: admissions index "Applications usually take four to six weeks to process"; FAQ "it can take up to six months".
- Deposit: Steps after admission https://www.unb.ca/gradstudies/admissions/nextsteps.html — deposit only "If you are a domestic student accepted into the MQIM, MN, MEM, or MBA programs". => No deposit for MEng (NEW).
- Deferral: "Students may request a deferral one time".

### B4. Program structure
- Dept page: "30 credit hours of coursework, at least 15 of which must be 6000 level courses"; "designed to be completed in 3 or 4 academic terms, depending on the student's background"; "Normal duration: 16-24 months"; "Residency: First term"; "Time limit: 24 months (full-time)"; maintain "3.0/B average"; optional co-op ("up to 12 months of paid co-op work terms").
- NEW — Suggested sequences PDF https://www.unb.ca/fredericton/engineering/_assets/documents/gge/graduate/graduate-course-sequence.pdf : all four streams (GIS/RS & Computer Vision; Spatial Data Science; Geodesy, Positioning & Navigation; Hydrospatial) are laid out Fall / Winter / "Summer 0" / Fall, 9 courses, "total credits 31-33" / 31 / 32 / 32. Summer has no courses; Directed Research GGE6921 suggested in Summer "at the discretion of the supervisor". Co-op section: "return to academic studies in September or January, when the majority of our graduate courses are offered".
  => Realistic completion: 4 terms / 16 months (Sept 2027 - Dec 2028). 3-term (12-month) completion would need a heavy Fall+Winter load plus summer Directed Research with a willing faculty member — possible on paper, not the department's model.
- MEng checklist PDF https://www.unb.ca/fredericton/engineering/_assets/documents/gge/graduate/meng-course-checklist.pdf : "At least 15 credit hours should be from the GGE department"; optional "3ch of Directed Research (GGE 6921) with a faculty supervisor".
- Campus: Fredericton (Head Hall). Delivery in person (no online delivery stated; online fee $150/course "may apply").

### B5. Cost — 2026-27 fee sheet (re-opened)
- https://www.unb.ca/finance/_assets/documents/financial-services/fredericton-tuition/grad/course-based/fred_gr_cb_eng_ft.pdf "UNB Fredericton 2026-2027 Tuition & Fees (effective September 1, 2026) Master of Engineering - Course Based - Full Time". International lines CONFIRMED: Tuition (per course) 1,909.00; Mandatory Fees1 (per term) 107.25 "*Applies to only two terms per academic year"; Mandatory Fees2 (per course) 41.00; GSA (per term) 74.00; GSA Health and Dental 730.00 (Fall; 590.00 January start); GSA Universal Bus Pass 176.00; International Emergency Health Ins. 200.00 per term ("Requires valid NB MEDICARE Card to opt out"); International Health Travel Insurance 64.50 (once per 12 months). "A minimum of 3 courses is required per term for full time status." 2027-28 sheet: NOT POSTED (index https://www.unb.ca/finance/financial-services/graduate/fredericton.html lists only the 2026-27 PDFs).
- Health page https://www.unb.ca/finance/financial-services/health-insurance.html : guard.me "$200 per person for a four-month term"; "These plans are mandatory"; Annual Excursion "$64.50/year" mandatory; opt-out only with NB Medicare card or SNB letter.
- Tuition is charged "per course" (not per credit hour). Suggested sequences have 9 courses (some 4-5 ch). Whether a 4-5 ch course is billed as one course: UNCONFIRMED. Base case below = 10 courses (conservative); 9-course variant shown.
- Per course: 1,909 + 41 = 1,950.
  - 3 terms (F/W/S), 10 courses: 19,500 + 2 x 107.25 (214.50) + 3 x 74 (222) + 730 + 176 + 3 x 200 (600) + 64.50 = **21,507.00** (9 courses: 19,557.00).
  - 4 terms (F/W/S/F, department model), 10 courses: 21,507.00 + 107.25 + 74 + 730 + 176 + 200 + 64.50 = **22,858.75** (9 courses: 20,908.75). If no summer charges while unregistered: about 274 less (UNCONFIRMED). If NB Medicare obtained, emergency 200/term can be opted out (saves up to 600-800).
  - + application fee 125.
  - Fall 2027 entry is billed at 2027-28/2028-29 rates (not posted). +5%/yr on tuition: about 22,859 + 975 (yr1) + ~200 (yr2 extra) ≈ 24,000-24,100.

### B6. PGWP / DLI
- DLI JSON (same file, 23 Oct 2026): "University of New Brunswick","DLI #":"O19348802512","City":"Fredericton","Campus":"UNB – Fredericton","Grad Program":"Yes","PGWP":"Yes","Public institution". CONFIRMED.
- PAL: SGS International "Effective Jan. 1, 2026, international graduate students enrolling at UNB will be exempt from requiring a Provincial Attestation Letter (PAL)".
- IRCC: master's >= 8 months -> "3-year PGWP"; CLB 7 in all four skills with CELPIP-G / IELTS General / PTE Core / TEF / TCF at PGWP application (see A6).

## Blocked / unreadable
- docs.google.com (Algoma Graduate Student Handbook, file 1qYZNd9UkA-mcD5m3UE0Q4cX8v9Pde9w5): export HTTP 401; drive download "Sorry, the owner hasn't given you permission to download this file."; headless Chromium returned empty DOM.
- No other host blocked. canada.ca DLI JSON loaded with curl --compressed (HTTP 200); canada.ca PGWP pages via headless Chromium.
