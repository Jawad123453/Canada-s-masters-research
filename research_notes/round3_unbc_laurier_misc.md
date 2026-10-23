# Round 3 – UNBC deep check, Laurier "last year / last two years" re-check, misc quick re-checks
Started 23 Oct 2026. Evidence from full official pages fetched with fetch.sh unless labelled otherwise. No applicant grades recorded here.

## Blocked hosts / fetch errors
- www.uwindsor.ca/professional/421/tuition-and-fees: HTTP 503 "Site under maintenance | Professional Programs" (curl, then headless Chromium).
- www.uwindsor.ca/finance/fee-estimator: Drupal POST form; curl POST returned the page without a fee table (no figures retrievable).
- www.brandonu.ca/registration/files/Graduate-International-Tuition-Table-2026-27.pdf: HTTP 404 (only the 2025-26 table is posted).
- Previously blocked, now OPEN: www.unbc.ca (HTTP 200); academic-calendar.wlu.ca (HTTP 200, 2026/27 Graduate Calendar live).

## Plan
1. UNBC: grad admission rule (last 60 credit hours, 3.00 B), UNBC grade scale (% for B / B-), foreign-credential conversion (Lebanon/WES), "may be considered" / special-circumstances / mature routes, repeated courses. Course-based master's (MEng IWD, MBA, others): cost 2026-27, supervisor, prerequisites, English incl. Duolingo, delivery, intakes, contact.
2. Laurier: SJCE MA (Brantford) "last year" B; Geography MA/MES EDA years averaged; other "last year"/"last two years" B programs; Duolingo minimum; retry academic-calendar.wlu.ca.
3. Quick re-checks: Brandon (foreign % conversion, course-based master's), Lethbridge ("last 20 graded" courses), Lakehead Lebanon rows (only if <30k course-based exists), Windsor (any 70% bar <30k).
4. Full verification of survivors incl. PGWP DLI (DLI rows already extracted in 01_dli_extract.md: UNBC O19283889692; Laurier O19395164307; Brandon O19201298932; Lethbridge O18776949622; Lakehead O19396019447; Windsor O19358946722).

## 1. UNBC (Prince George) – FAIL at institution level (Lebanon row 80%; Duolingo 125)
www.unbc.ca reachable this round (HTTP 200 via curl, 23 Oct 2026) – the prior-round "403 connect_rejected" no longer applies. All pages below fetched in full.

### 1a. General rule – the old "last 60 credit hours" wording is gone
- Graduate Calendar, https://www.unbc.ca/calendar/graduate/admissions ("Updated: January 30, 2026"), section "1.3 Admission to Master's Degrees", 1.3.1: "must hold a four-year baccalaureate degree (or equivalent)"; "Domestic applicants are normally required to have a minimum overall average of 3.00 (B) for third- and fourth-year courses." / "Specific minimum admission requirements for graduates with credentials completed at an institution outside of Canada are determined by country".
- So for a Lebanese degree the country table governs, not the 3.00 / last-60-credit rule (the "last 60 credit hours" phrase quoted in the prior round does not appear in the current calendar).

### 1b. Country table – LEBANON row (QUOTED)
- https://www.unbc.ca/apply/graduate/international-admission-requirements , "International Graduate Admission Requirements by Country":
  - **"Lebanon / 4 year Bachelor's (see France for French Patterned Universities) / 80%"**
  - France row: "Licence; Maitrise ( until 2009) / 14 on a 20 point scale".
- Method (same page): "Starting with the May (Spring) and September (Fall) 2026 admission intakes, the admission GPA for applicant's with international credentials is calculated based on the final two years (or equivalent)". "We do not convert to a UNBC grade scale (4.33). Rather, applicants are assessed based on the grading system of their institution." UNBC evaluates itself; no WES requirement seen.
- Hard cut-off: "Your minimum credential and admission GPA must meet or exceed the minimum or your application will not be considered for admission and will be closed".
- Inconsistency: https://www.unbc.ca/programs-and-admissions/graduate/academic-requirements says in one paragraph "international credential method as outlined below (cumulative total degree)" and in the next "calculated based on the final two years (or equivalent)". Either window is far below 80% for a ~70-74% record.
- Repeated courses: no rule found for external transcripts (calendar 2.x only says "Graduate students may not repeat graduate courses except under exceptional circumstances" – UNBC grad courses). Moot.
- UNBC grade-scale % bands: not needed (UNBC explicitly does not convert international grades). Moot.
- French-patterned route: the France row (14/20) applies only to "French Patterned Universities" with Licence/Maitrise; a /100-graded Lebanese Bachelor of Engineering would fall under the Lebanon 80% row. UNCONFIRMED whether UNBC would treat a given Lebanese university as French-patterned (ask graduate-admissions@unbc.ca).

### 1c. Escape routes (QUOTED; none usable)
- 1.3.2: "In exceptional situations and at the discretion of the program, an applicant's admissibility may be adjudicated on the basis of performance in at least 12 credit hours of upper-level coursework directly related to the intended field of study." (discretionary)
- 1.3.3: "may recommend admission ... who does not meet the minimum GPA ... if the applicant demonstrates sufficient relevant experience and expertise to offset GPA deficiencies." (needs work experience)
- 1.4 Mature student: "Five years after completion of a baccalaureate degree ... may be admitted conditionally as mature students"; "The minimum GPA for admission to a Master's program as a conditionally admitted mature student is 2.67 (B-) or equivalent." → only open 5 years after graduation (not Fall 2027/2028 for a 2026 graduate). Applies to all applicants (no domestic restriction stated). 
- Pre-entry program: "pre-entry program of undergraduate coursework totalling at least 12 credit hours ... average of not less than 3.33 (B+)". Not a direct route.

### 1d. English
- https://www.unbc.ca/admissions/graduate/english-language-proficiency : "IELTS ... Academic score of at least 6.5 overall, with not less than 6.0 in any of the four modules"; "IELTS Indicator is not accepted"; **"Duolingo: overall score of 125, with no individual subscore below 115."** ("*Requirements shown are subject to final approval by the university governance.")

### 1e. Course-based master's (for the record; all blocked by 1b)
- MEng in Wood Engineering (formerly Integrated Wood Design), https://www.unbc.ca/engineering/meng-integrated-wood-design : "8 courses plus a final project with a total of 30 credits over 12 to 24 months"; "Year Starts: September"; Prince George; regular option Fall 4 courses / Winter 4 courses / Summer capstone.
- NEW Master of Engineering (civil & environmental), https://www.unbc.ca/engineering/master-engineering : "Course-Based Master's Program | 30 credit hours"; "offered in person at UNBC's Prince George campus"; non-Canadian-degree holders must include "ENGR 410-3 Professional Practice and Law". Civil/environmental focus (BME fit UNCONFIRMED).
- MBA: prior round found 3 years' work experience required (not re-checked).
- Cost not re-verified this round (moot). Prior-round figure (2026/27): MEng IWD "$745.76" per credit hour x 30 = 22,372.80 + fees.
- **Verdict UNBC: DROP.** Single reason: Lebanon row "80%" on the final two years (plus Duolingo 125/115 minimum). Contact if ever needed: graduate-admissions@unbc.ca.

## 2. Wilfrid Laurier – "last year" / "last two years" B programs (calendar now readable)
- academic-calendar.wlu.ca is BACK (HTTP 200, 23 Oct 2026): 2026/2027 Graduate Calendar at https://academic-calendar.wlu.ca/index_old.php?cal=3&y=94 .
- Laurier grade scale (from round 2): "B 73-76", "B- 70-72" (students.wlu.ca GPA calculator).

### 2a. Institution-level rules (2026/27 Graduate Calendar, "University Graduate Regulations > Admission Requirements", https://academic-calendar.wlu.ca/section.php?cal=3&s=1188&ss=4735&y=94)
- Master's: "graduated with a minimum of second-class honours or B standing in the fourth year of an honours program or equivalent at an approved university". → the general rule looks at the FOURTH (final) year.
- Probationary student: "A student who does not meet fully all of the admission requirements ... may be admitted as a probationary student" (must meet a set performance level in first 1-2 terms).
- Qualifying student: "minimum of B or equivalent standing in the final year of a general program" (qualifying year, not degree admission).
- No Lebanon / international equivalency table and no rule on repeated/failed external courses in this section (UNCONFIRMED how Laurier treats failed-then-passed attempts).
- **English: Duolingo NOT accepted.** https://www.wlu.ca/academics/faculties/graduate-and-postdoctoral-studies/admissions/assets/resources/english-proficiency.html : "the Duolingo English Test (DET) is not accepted for admission to graduate programs at Wilfrid Laurier University." IELTS / IELTS Online "academic – minimum score of 6.5 with no band score below 6.0". → an IELTS Academic (or TOEFL/PTE/CAEL) is mandatory for every Laurier program.

### 2b. MA Social Justice & Community Engagement (Brantford)
- Program page https://www.wlu.ca/programs/liberal-arts/graduate/social-justice-and-community-engagement-ma/index.html (fetched in full): "Brantford / In Person"; "12-month full-time program (part-time available)"; "All students start in the fall semester"; coursework is default route ("All students admitted to the program are automatically admitted to this route"); MRP optional – "not required to have confirmed a supervisor prior to applying".
- Admission (program page): "A four-year (honours) undergraduate degree (or equivalent) in humanities, social science, natural science, education, social work or related interdisciplinary program." / "A background in the concepts of social and environmental justice." / **"A minimum B average in your last year of undergraduate study, or equivalent."** Also: "We accept applications from people with a wide variety of academic backgrounds, lived experiences, and participation in volunteer/grassroots activities."
- Calendar entry (https://academic-calendar.wlu.ca/program.php?cal=3&d=3350&p=7823&s=1200&y=94): "a 12-month, 3-term program"; "four year honours BA from a humanities, social science, natural science or interdisciplinary program, and a background in the concepts of social and environmental justice. Applicants should have a minimum B standing or equivalent. An applicant who does not meet these requirements may still apply for admission as a qualifying student." Fall: SOJE601/603/621/690; Winter: SOJE602/621/631/690; Spring: SOJE605+606 (coursework) or SOJE695 MRP. 120-hour unpaid community placement.
- Filter 1: Laurier B = 73-76% in the last year. Engineering is NOT in the listed degree fields (humanities / social science / natural science / education / social work / interdisciplinary) – degree fit doubtful (filter 6 UNCONFIRMED, lean FAIL without social-justice background).
- Deadline: "Applications open: Oct. 25"; "First round consideration ... by Jan. 31 (domestic and international)"; rolling after if spots remain. For Fall 2027: apply by 31 Jan 2027. Fall start only.
- Cost (2026-27 rates, Brantford, 3 terms): tuition "MA/MEd/MES/MAP/MKin/MMus $7,861.00" per term (https://students.wlu.ca/finances/tuition-and-fees/fees-breakdown/tuition-fees.html, "Full-Time Graduate Visa Students ... Entering All Years") x 3 = 23,583.00. Graduate incidental fees (https://students.wlu.ca/finances/tuition-and-fees/fees-breakdown/incidental-fees.html, "All Graduate Student Incidental Fees"; no Brantford-specific graduate fees listed, U-Pass/Athletics are "Waterloo Campus" only): per term 3.31+57.92+10.72+9.01+8.00+461.40+3.63+7.36 = 561.35 x 3 = 1,684.05; one-off CFS 21.08 + OneCard 31.00 + 15.24 = 67.32; GSA Health 486.74 + Dental 252.43 = 739.17; UHIP September 2026 single $948 (uhip.ca "Rates for September 1, 2026 to August 31, 2027"). **Total 27,021.54** (fee-increase risk: >=27k; 2027-28 rates not published).
- Contacts: ctravers@wlu.ca (program administrator), rgodderis@wlu.ca (graduate coordinator), gradadmissions@wlu.ca.

### 2c. Geography MA / MES – Environmental Data Analytics (Waterloo)
- Calendar MA (p=7779) and MES (p=7780): "should hold an undergraduate honours degree or equivalent with at least a B standing. Normally, the undergraduate degree will be in geography, but applications are welcomed from superior students regardless of background." No year window in the program entry → falls back to general rule "B standing in the fourth year". Program page: "A four-year honours undergraduate degree (or equivalent) in geography or related program." / "A minimum B average."
- EDA: "two terms of course work (six courses) and one term of research placement"; calendar "8 courses (4.0 credits), including an applied research placement course in the spring semester" (GG500, GG501, GG502 placement, GG569 ...). Fall start; "March 30 (international applicants)".
- Degree fit: "superior students regardless of background" + must "demonstrate ... the necessary background" – BME not geography → filter 6 UNCONFIRMED (lean FAIL). Cost (from round 2, Waterloo, 3 terms): 27,712.05.

### 2d. MEd (Interdisciplinary, full-time option, Waterloo) – NEW borderline candidate
- Program page https://www.wlu.ca/programs/education/graduate/education-med/index.html (fetched in full): "The MEd is a course-based program with no thesis option" (8 half-credit courses, capstone EU598). Admission: **"A minimum "B" standing in your final two years of study."**; "A Bachelor of Education degree is not required"; "Successful experience as an educator in a professional setting may be considered" (not required). Calendar (https://academic-calendar.wlu.ca/program.php?cal=3&d=3348&p=7821&s=1199&y=94): "honours degree or equivalent ... Normally a minimum "B" standing in the final two years of study is required."
- Full-time: "one or two spaces in the Interdisciplinary program for Waterloo campus students wishing to complete the program on a full-time basis. Students would take three courses in the first term, three courses in the second term and two courses in the final term." "Full-time students complete the program in three consecutive terms (one year)"; May start.
- Delivery: calendar "in-person hybrid program ... A minimum of 50% of required courses are offered in-person, hyflex, or in-person hybrid mode"; page: "includes some Online courses, and some blended courses". PGWP RISK: up to 50% may be online; IRCC disqualifies >50% online. UNCONFIRMED exact split for the full-time sequence – must ask.
- Deadline (Spring/May start): "Applications open: Aug. 15"; "First consideration: Dec. 15 (or until full)"; "Nov. 1 (international applicants)". → for May 2028 start apply by 1 Nov 2027 (Fall 2027 entry not possible for the in-person program; fall start is the online part-time option only = FAIL delivery).
- Cost (2026-27 rates, May start, 3 terms May-Apr): tuition 3 x 7,861 = 23,583.00; Waterloo per-term incidentals 791.52 x 3 = 2,374.56 (round-2 sum incl. U-Pass 131.14 and Athletics 99.03, re-checked same table); one-off 67.32; GSA health/dental spring 4-month 165.25+87.14 then fall 12-month 486.74+252.43 = 991.56 (conservative); UHIP May 2027 "$316" + September renewal $948 = 1,264. **Total ≈ 28,280.44** (fee-increase risk; real intake May 2028 at unknown 2027-28/2028-29 rates).
- Contact: gradadmissions@wlu.ca (Faculty of Education graduate office email not captured).

### 2e. Other Laurier programs checked in the 2026/27 calendar (all FAIL)
- Sociology MA (p=7792): "An average of B+ in the final year". Philosophy MA (p=7788): "A final year average of B+". Master of Computer Science (p=7777): "final year average of at least B+" + CS degree. Kinesiology MSc (p=7772): "minimum average of B is required in the last two years" but thesis with "prospective supervisor" and kinesiology/health degree → FAIL supervisor/degree.

## 3. Brandon University (Brandon, MB) – MA Rural Development, course-based option: BORDERLINE CANDIDATE
Source: Graduate Calendar 2026-27 PDF https://www.brandonu.ca/calendar/files/2026/02/Graduate-Calendar-2026-27.pdf (read via pdftotext, sections 2, 3.8, 8), plus pages below, 23 Oct 2026.
- Admission bar (8.1.2 "ADMISSION, MASTER OF ARTS (RURAL DEVELOPMENT)"): "Students will normally have a four-year Bachelor's degree (BA, BSc, or equivalent)"; **"Students will normally have a minimum cumulative grade point average (CGPA) of 3.00 in the last 30 credit hours of study completed prior to application for entry. Student with less than a 3.00 CGPA may be required by the Rural Development Graduate Admissions Committee to undertake compensatory study."** → window = last 30 credit hours only; sub-3.00 is not an automatic reject (compensatory study). The prior round's "3.00 (B) in the last 60 credit hours" is the MPN rule (7.1, line "A minimum GPA of 3.00 (B) in the last 60 credit hours"), not RD.
- Also 8.3.1(7): "All prospective students must have an advanced undergraduate research methods course or the equivalent." (BME transcript fit UNCONFIRMED.)
- Conditional admission (2.2.3): "Conditional status may be assigned to a student who ... does not meet graduate admission requirements" – must meet conditions within two terms, max 12 graduate credits.
- Brandon scale (3.8): "B 3.00", "B- 2.70", "C+ 2.30" – no percentage bands published. Foreign-grade conversion: no country table found; Brandon accepts WES: https://www.brandonu.ca/graduate-studies/international-applicants/admission-requirements/ "We also accept World Education Services (WES) credential evaluation reports, directly from WES." (UNCONFIRMED whether WES is used to compute the last-30-credit CGPA or Brandon evaluates itself.)
- Repeated courses (3.8.3, Brandon's own courses): "only the grade and any associated credits earned on the most recent attempt will be used for calculating grade point averages" – external-transcript rule UNCONFIRMED.
- Structure (8.3.1/8.3.5): "30 credit hours either by taking 10 courses or six courses and a thesis"; "Course-based Option": 88:560, 88:562, 88:591, 88:592 + "six electives from any of the 500 level Rural Development courses" = 30. Advisor assigned: "The student will be assigned an academic advisor upon entry to the program." → filter 4 PASS (course-based).
- Full-time = "nine or more credit hours per academic year" (3.4.2). Length for 30 credits not stated (2 regular sessions at 15 cr/yr). Graduation needs "minimum degree GPA of 3.00".
- English (2.1, grad calendar): "Duolingo English Test 120; minimum 105 on all component scores"; "IELTS ... (Academic) 6.5 overall; Minimum 6.0 on each section"; "Individual graduate programs may require minimum scores higher" (RD section only refers back to 2.1).
- Delivery: fee table lists RD "ON CAMPUS" and "NET" (online) course rows; program page does not state the mix. Online share UNCONFIRMED (ask; must be <=50% online for PGWP).
- Deadlines: https://www.brandonu.ca/graduate-studies/applications/ "Graduate Diploma/Master of Arts (Rural Development)" – "International Application Deadline: For September – December 15" (application and documents same date; "begin processing applications ... October 1st"). Calendar 8.1.2 says "September entry for Domestic and International ... by January 31st" – CONFLICT; use 15 Dec 2026 for Sept 2027. January entry is domestic only ("Applications for January entry for Domestic students").
- Cost: 2026-27 table not posted (Graduate-International-Tuition-Table-2026-27.pdf → HTTP 404). 2025-26 table https://www.brandonu.ca/registration/files/Graduate-International-Tuition-Table-2025-26.pdf "INTERNATIONAL STUDENT - REGULAR SESSION 2025/2026", Rural Development ON CAMPUS, 15 credit hours: tuition 6,823.50 (= 454.90/credit hour) + fees incl. "Health Insurance Fee" 1,200.00 and BUSU fees → "Total Fees" **9,124.68** per regular session (15 cr). Footnote: "International Student Health Insurance approximately $1,104/year." 30 credits = 2 x 9,124.68 = **18,249.36** (2025-26 rates; add ~5-10% for 2026-27/2027-28 → still ~20k). PASS cost by a wide margin.
- Contact: Dr. Doug Ramsey, Chair, ramsey@brandonu.ca (https://www.brandonu.ca/rural-development/graduate-students/); admissions@brandonu.ca.
- PGWP/DLI: Brandon University O19201298932, PGWP "Yes" (01_dli_extract.md).
- Verdict: plausible but UNCONFIRMED on filter 1 (B=3.00 on last 30 credits, "normally", compensatory-study escape; conversion method of a /100 Lebanese transcript unknown) and filter 5 (online share). Best-value lead found this round.

## 4. University of Lethbridge – DROP (no fitting course-based program)
- MEd page https://www.ulethbridge.ca/future-student/graduate-studies/master-education (fetched in full): "Minimum grade point average (GPA) of 3.00 in the terms containing the last 20 graded university courses (60.0 credit hours)." plus "Approximately two years of teaching experience or other relevant educational experience." → FAIL filter 6 (experience) and filter 1 (3.00).
- MSc Management (Business Analytics project pathway), https://www.ulethbridge.ca/future-student/graduate-studies/master-science-management : "designed for students with an undergraduate degree, or significant professional experience, in Management, Commerce, Business or a related discipline" → FAIL filter 6 for BME.
- No foreign-grade conversion table found on ulethbridge.ca (WebSearch discovery only; not evidence). Not pursued further.

## 5. Lakehead University – DROP (Lebanon row)
- https://www.lakeheadu.ca/programs/graduate/academic-information/international-credential-equivalency (fetched in full), Lebanon ("Effective 2020-02-20"): "Bachelor`s, Licence requiring 4 years of study"; "90-100% / 18-20 / A-, A, A+"; "80-89% / 15-17 / B-, B, B+"; **"70-79% / 12-14 / C-, C, C+"**; "60-69% / 10-11 / D-, D, D+". → any 70-79% Lebanese average = Lakehead C-range; a B-range needs 80%+. FAIL filter 1 for every Lakehead master's (incl. Master of Environmental Management).

## 6. University of Windsor – M.Ed.: bar passes, cost UNCONFIRMED (likely FAIL)
- https://www.uwindsor.ca/education/masters/apply (fetched in full): "academic standing equivalent to 70% or better in the final two years of study (full time equivalent)"; "4 year (Honours) undergraduate degree or equivalent"; "in the discipline to which s/he is seeking admission" (generic M2 wording); IELTS "7.0 (or above) in three of the four areas ... with the other being no lower than 6.5"; TOEFL 100. Duolingo not listed (UNCONFIRMED; assume not accepted). Intakes September and January.
- Cost: fee estimator https://www.uwindsor.ca/finance/fee-estimator ("approved fees for 2026-2027 academic year ... per term") is a Drupal POST form; results not retrievable with curl/headless dump (POST returned page without fee table). https://www.uwindsor.ca/professional/421/tuition-and-fees → HTTP 503 "Site under maintenance | Professional Programs". 2026/27 Operating Budget (Senate package May 21 2026, https://www.uwindsor.ca/secretariat/sites/uwindsor.ca.secretariat/files/s260521p_-_combined_may_21_2026_senate_package.pdf): "International tuition for course-based master's programs is adjusted on a program-by-program basis" – no M.Ed. dollar figure. Prior round: $33,000 over 4 terms (2020-21). → UNCONFIRMED, likely > 30k.

## 7. PGWP / DLI for leads (from 01_dli_extract.md, DLI JSON read 23 Oct 2026)
- Brandon University O19201298932 (Brandon campus) PGWP "Yes". Wilfrid Laurier University O19395164307 (Brantford Campus; Waterloo Main Campus) PGWP "Yes". University of Windsor O19358946722 "Yes". UNBC O19283889692 "Yes".

## Summary (round 3)
- UNBC: DROP – Lebanon row "80%" (final two years) + Duolingo min 125/115.
- Laurier: Duolingo NOT accepted (IELTS Academic 6.5/6.0 needed). Bars: SJCE "minimum B average in your last year" (B = 73-76%), MEd "minimum B standing in your final two years", Geography EDA "B standing" (general rule = fourth year). SJCE degree list excludes engineering; Geography wants geography/"superior students"; MEd full-time has "one or two spaces", May start, up to 50% online. Costs 2026-27: SJCE 27,021.54; MEd ~28,280.44; Geography EDA 27,712.05 – all fee-increase risk.
- Brandon MA Rural Development (course-based): last-30-credit 3.00 "normally" with compensatory-study escape, Duolingo 120/105 minimum, ~18.2k for 30 credits at 2025-26 rates, intl deadline 15 Dec (Sept). Best lead; conversion method and online share UNCONFIRMED.
- Lethbridge, Lakehead: DROP. Windsor M.Ed.: cost unretrievable.

## Blocked hosts (round 3)
- www.uwindsor.ca/professional/421/tuition-and-fees: HTTP 503 "Site under maintenance".
- www.uwindsor.ca/finance/fee-estimator: form POST results not returned to curl (no fee table in response).
- www.brandonu.ca/registration/files/Graduate-International-Tuition-Table-2026-27.pdf: HTTP 404 (only 2025-26 posted).
