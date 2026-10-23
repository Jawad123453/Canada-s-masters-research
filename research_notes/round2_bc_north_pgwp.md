# Round 2: VIU MEDL deep check, other VIU/BC/North, Yukon U, PGWP rules (23 Oct 2026)

Agent notes. Evidence rules per 00_agent_brief.md. Pages fetched with scratchpad/tools/fetch.sh (curl, or headless Chromium with --browser).

## Blocked hosts / fetch errors
(none yet)

## Plan
1. VIU MEDL: program page, programs.viu.ca courses/requirements, international admissions + English, general regulations (grade scale), Schedule #022 PDF, medical insurance, gov.bc.ca MSP fee.
2. VIU graduate program list (anything not already eliminated).
3. Yukon University master's.
4. PGWP rules on canada.ca (eligibility, language-results, field-of-study, PAL, private/PPP).
5. DLI rows from 01_dli_extract.md.
6. Western public institutions quick scan (KPU, Capilano, Okanagan, Coast Mountain, NVIT, Mount Royal, MacEwan).

## 1. VIU MEd in Educational Leadership (MEDL), Full-Time option, Nanaimo

Pages opened in full (curl, 23 Oct 2026):
- P1 program page: https://www.viu.ca/programs/education/master-education-educational-leadership
- P2 international admissions: https://www.viu.ca/admissions/international (same content as https://international.viu.ca/admissions/)
- P3 general regulations: https://www.viu.ca/registration/general-regulations (curl needs --compressed; fetch.sh without it returned gzip bytes)
- P4 Schedule #022 PDF: https://gov.viu.ca/sites/default/files/documents/Tuition%20and%20Fee%20Schedule%20022%20International%20APPROVED%20March%2031%202026.pdf
- P5 VIU PGWP list: https://international.viu.ca/international-student-support-iss-hub/pgwp-eligible-programs

### F1 bar
- P1 "Admission Requirements": "Completion of a Bachelor's degree, (preferably a Bachelor of Education degree, or equivalent)" ... "acceptable in content to the Faculty of Education with either:" / "a cumulative grade point average of "B" in the final two years and/or" / "demonstration of academic excellence". No % stated on P1.
- P2 "Admission to graduate programs": "Minimum "B" average in the final 2 years of a Bachelor's degree." No %.
- P3 "Grade scale: University, Academic, Adult Basic Education Programs": B+ 76-79 (3.33), B 72-75 (3.00), B- 68-71 (2.67); C+ 64-67. "Effective September 1, 2010 VIU converted to a 4.33 grade scale."
- Lebanon: P2 has only a HIGH-SCHOOL country table ("Lebanon / General Secondary Education Certificate"). No graduate Lebanon row, no WES mention anywhere on P1/P2 (grep "WES|evaluat|credential": none). Evaluation method UNCONFIRMED (VIU appears to evaluate in-house from official transcripts + certified translations, P2 "All documents must be translated by a certified translator or notarized" - paraphrase of process, not a stated rule).
- Repeated courses: P3 "Repeating a course or program": "if it is an upper-level course, the highest grade will be included in the graduation GPA calculation" - VIU's own students only; no admission rule for external transcripts. UNCONFIRMED.
- Applicant: VIU B = 3.00 = 72-75%. Last-two-years ~73% (retakes replaced) -> clears 72; ~66-67% (all attempts) -> B-/C+ -> fails; WES 2.90 < 3.00 -> fails. "and/or demonstration of academic excellence" + "Flexible Admission" (P1: "In exceptional circumstances ... significant professional experience") is a soft escape, not a path for this applicant.
- Verdict F1: UNCONFIRMED (stated as plain "B"; VIU's own scale puts B at 72%; outcome depends on how VIU converts the Lebanese % and treats failed attempts).

### F6 degree / experience
- P1: degree "preferably a Bachelor of Education degree, or equivalent" and "acceptable in content to the Faculty of Education". B.Ed is PREFERRED, not required.
- P1: "A résumé outlining teaching experience (two years preferred)." Preferred, not required. Also "letter of intent" and "Two current, confidential assessment reports (reference letters are not acceptable in lieu ...)".
- P1: "Enrolment in this program is limited. Students who meet or exceed the minimum admission requirements may not necessarily be admitted".
- Program described as "designed for practicing and aspiring professionals in the education field". Verdict F6: UNCONFIRMED (not blocked on paper; competitiveness of a BME with no teaching experience unknown).

### F2 English
- P1: must meet "VIU's English Language requirements for Graduate Programs" (link to international admissions #graduateadmissions).
- P2 "Admission to graduate programs" table: "IELTS (Academic) 6.5 (no band below 6.0)"; TOEFL iBT 88 (no section below 20); PTE Academic 60; Duolingo 115.
- Conflict resolved: the current official graduate requirement is 6.5 / no band below 6.0 (the older 7.0/6.5 figure came from a ~2025 application-form PDF, superseded). Only "IELTS (Academic)" listed; General Training not listed -> GT NOT accepted (by omission).
- Verdict F2: PASS (applicant 7.0 each band, if Academic).

### F3 cost (fee year 2026-27, Schedule #022 "Approved by the Board March 31, 2026", "Effective Date April 1, 2026")
Sources opened in full: P4 (PDF): "Master of Education in Educational Leadership $ 704.62 per credit"; P4 note "Student activity, student services, and mandatory lab and supply fees for international students are assessed at the same rate as those listed for domestic students."
- https://www.viu.ca/admissions/tuition-fee-schedule (P6): "Fees are effective April 1."; domestic graduate table "MEDL 600 $53.06 lab fee"; "Activity fees are assessed at a rate of $20.78 per month"; "Student services fees are assessed for all programs at a rate of $22.94 per month"; "VIUSU fees - Nanaimo (as of April 1, 2026)" Total "$50.08" monthly (incl. $20.00 SUB levy "per 2025 referendum"); "Fees are applicable throughout the entire year."
- P1 international fee table (verbatim rows): "Tuition* (30 credits x $704.62 per credit) 21,138.60"; "Lab Fee 53.06"; "Student Activity fee (16 months x $20.78 per month) 332.48"; "Student Services fee (16 months x $22.94 per month) 367.04"; "VIU Students' Union fee (16 months x $50.08 per month) 801.28"; "Health and Dental Plan fee (2 years x $285.00 per year) 570.00"; "Textbooks and supplies (approximate cost) 880.00"; "Total 24,142.46". Note: "expected to increase by 2% each year on April 1."
- Health, https://international.viu.ca/international-student-support-iss-hub/medical-insurance (P7): guard.me "All new students are automatically enrolled"; "Approximate cost $246 per semester"; "students will continue to be enrolled, and charged, for subsequent terms until proof of BC MSP is provided to guard.me". Greenshield Extended Health and Dental "$275 per year" (P7) vs $285/yr on P1 -> use 285 (conservative). P7: "The health-care coverage fee for International students is $75 per month per student."
- BC fee amount (gov.bc.ca, amount only): https://www2.gov.bc.ca/gov/content/health/accessing-health-care/health-fee-international-students : "a mandatory monthly fee of $75 charged to all international students studying in British Columbia on a valid study permit for at least six months"; wait period "the balance of the month in which residency is established, plus two months."
- Months: P1 bills 16 months of monthly fees. Full-time option: "Generally all required coursework is completed over two years but may be completed sooner." Year 1 = 21 cr, Year 2 = 9 cr. Scenario A = 16 months (Sep 2027-Dec 2028), Scenario B = 20 months (Sep 2027-Apr 2029). ISHF from Nov 2027 (arrive Aug 2027): A 14 months, B 18 months.

| Item | A: 16 mo (CAD) | B: 20 mo (CAD) |
|---|---|---|
| Tuition 30 x 704.62 | 21,138.60 | 21,138.60 |
| Lab fee (MEDL 600) | 53.06 | 53.06 |
| Monthly fees 93.80 x 16 / x 20 | 1,500.80 | 1,876.00 |
| VIUSU health & dental 2 x 285 | 570.00 | 570.00 |
| guard.me first semester | 246.00 | 246.00 |
| BC ISHF 75 x 14 / x 18 | 1,050.00 | 1,350.00 |
| **Mandatory total** | **24,558.46** | **25,233.66** |
| + textbooks (VIU estimate 880) | 25,438.46 | 26,113.66 |
- Fee-increase projection (Sept 2027 start falls under the Apr 1, 2027 schedule, not yet published): +2%/yr (VIU's own stated expectation) -> 21 cr x 718.71 + 9 cr x 733.08 = 21,690.63 tuition (+552.03); scenario B all-in ~25,836 mandatory, ~26,716 with textbooks. Still < 27,000 -> no fee-increase-risk flag on 2% assumption; at 5%/yr it would reach ~27k.
- Deposit: application fee $156.06 (P4). Deposit amount not on pages opened this round (prior notes: $10,000) - UNCONFIRMED.
- Verdict F3: PASS (~24.6-25.2k mandatory on 2026-27 rates).

### F4 supervisor / F5 delivery / full-time
- P1 Full-Time Option: "This cohort-based model is designed for students wishing to study full-time on the VIU campus."; Year 2 "Course Based Completion Option" = 3 graduate electives (9 cr) OR "Thesis Completion Option" (elective + MEDL 680 + MEDL 690). Footnote: MEDL 680/690 "may be completed on-campus or online." Full-time option text: "Students may complete these components online and up to one semester early."
- Courses page https://programs.viu.ca/courses/master-education-educational-leadership : MEDL 690 is "Under the guidance of faculty mentors/supervisors" -> assigned within the course; course-based route needs no supervisor. F4: PASS.
- F5: Year 1 21/30 credits face-to-face in Nanaimo = 70% in person minimum; even if all 9 Year-2 credits went online, in-class share is 70% (>50%). Department page https://education.viu.ca/master-education-programs : "full-time face-to-face option designed for those wishing to study full time at the Nanaimo campus". Part-time option "can be completed fully online" (P1) -> must NOT be chosen. F5: PASS (full-time option).
- Full-time status: P3 "A full course load for a graduate program is a minimum of nine credits per semester." "A full-time graduate student is one who is enrolled in at least 60 percent of the full course load" (= 5.4 cr, i.e. 2 courses). Year 2 9 cr over 2 semesters: if split 6+3, the 3-cr semester is below 60% unless it is the FINAL semester (IRCC exempts final semester; see PGWP section) or a project semester ("thesis preparation, final project ... considered to comprise a full course load"). UNCONFIRMED: ask VIU for the Year-2 schedule.
- PGWP on VIU's own site (P5): "All bachelor's and master's degree programs are PGWP eligible as long as at least 50% of the program is completed in person in Canada."
- Department text (edu page): "Both M.Ed. programs attract people from various professions ... are not limited to teachers working in the K-12 education sector." -> supports F6 not blocked.

### Intake / deadline / contacts
- P1 International: start "Sep 7, 2027"; accepting applications "Oct 1, 2026 to Mar 31, 2027"; "Accepting Late Applications: No"; "Document deadline is April 16, 2027." (So Mar 31 = application deadline, Apr 16 = document deadline - conflict resolved.) "This program has one intake each Fall (September)." Rolling; "typically fills up before the deadline". No Winter/Summer 2028 intake.
- Contacts: educ.gp@viu.ca (program questions); International Admissions Officer Ekaterina.Kurovskaia@viu.ca; transcripts to study@viu.ca. Info session Nov 12, 2026 4 pm (edu page).

## 2. Other VIU master's
- https://www.viu.ca/programs/graduate-programs "All graduate and post-degree programs at VIU" -> Master's degrees: MBA, MEd Educational Leadership, MEd Special Education only. Schedule #022 also prices MA Sustainable Leisure Mgmt, MGISA, Master's in Community Planning (all eliminated). Nothing new. Cheapest per-credit is MCP $587.17 (eliminated on total cost earlier).

## 3. Yukon University (DLI O19604209351, PGWP Yes, Grad Program Yes per 01_dli_extract)
- https://www.yukonu.ca/programs/public-administration (opened in full): the only "Master's degree" outcome listed. "This degree is delivered by the University of Alaska Southeast."; "learning from home ... e-Learning environment"; "Tuition fees are set by the University of Alaska Southeast."; "Course costs in Canadian dollars average CAN$1,400 to $2,800 per course."; contact uas.mpa@alaska.edu. -> Foreign (US) degree, online: FAIL F5 / PGWP (not a YukonU credential).
- https://www.yukonu.ca/programs/courses/renr-603 (opened): "Registration restricted to graduate students based at YukonU as part of the Environmental and Conservation Sciences program." RENR is a University of Alberta course code (inference): research-based graduate students hosted at YukonU, i.e. a supervisor-based (UAlberta) route -> FAIL F4 (and UAlberta already eliminated). This probably explains the "Grad Program Yes" flag.
- https://www.yukonu.ca/programs (browser render) and https://www.yukonu.ca/international/future-students/admission: no YukonU-granted master's listed ("Earn a bachelor's degree, diploma, certificate or apprenticeship without leaving Yukon."). WebSearch (site:yukonu.ca) found no YukonU master's launch.
- Verdict: N/A - no YukonU master's an international student can take in person.

## 4. PGWP rules (canada.ca, all opened in full via headless Chromium, 23 Oct 2026)
**A. Who can apply** - https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/after-graduation/eligibility.html (Date modified: 2026-06-24)
- General: "you completed a program of study at a PGWP-eligible designated learning institution ... that was at least 8 months long"; "you maintained full-time status as a student in Canada during each semester of your study program"; "You may study part-time during your final semester."; apply "within 180 days".
- Distance learning, lock-in on/after Sept 1, 2024: "You must complete at least 50% of your program in class within Canada."; "The time spent studying outside of Canada will be deducted from the length of your PGWP."
- Not eligible if you "completed over 50% of your study program through distance learning (online courses, e-learning or correspondence)".
- Partly online: no rule beyond the 50% in-class test; time studied online from outside Canada after Aug 31, 2024 does not count toward PGWP length. (Online courses taken while physically in Canada are not "in class" for the 50% test - paraphrase/inference.)
- Private / P3: curriculum licensing agreements (private college delivering a public college's program) "are not PGWP-eligible in most cases"; same-province exception only if started "on or before May 15, 2024". Also not eligible: "completed a study program at a non-Canadian institution located in Canada"; "completed a course or program of study at a DLI that is not PGWP-eligible".
- Language: bachelor's/master's/doctoral graduates "must prove your English or French language skills with a minimum level of Canadian Language Benchmarks (CLB) 7 ... in all 4 language areas".
- Field of study: "There are no field of study requirements for graduates with a bachelor's degree, master's degree or doctoral degree."
**B. Length** - https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/work/after-graduation/about.html (Date modified: 2026-03-09): "For master's degree programs as of February 15, 2024 You can apply for a 3-year PGWP, even if your master's program was less than 2 years, as long as your program was at least 8 months".
**C. Language results** - .../after-graduation/eligibility/language-results.html (Date modified: 2026-05-27): "If you apply on or after November 1, 2024, you must provide proof of English or French language skills." Tables listed: CELPIP (General), IELTS (General Training), PTE Core, TEF Canada, TCF Canada. IELTS GT CLB 7 = Reading 6.0, Writing 6.0, Listening 6.0, Speaking 6.0. IELTS Academic not listed.
- .../after-graduation/get-documents.html (Date modified: 2026-06-24): "Language tests should be taken in person."; results "less than 2 years old when you submit your application"; "You should take the IELTS General Training option."; "You should take the CELPIP-General test."; "You should take the PTE Core option". -> Applicant's IELTS Academic (if that is what it is) will NOT serve for PGWP; and a 2025/26 test will be >2 years old by PGWP time (~2029) anyway -> new GT/CELPIP/PTE Core test needed then.
**D. Field of study** - .../after-graduation/eligibility/field-of-study.html (Date modified: 2026-03-09): exempt if "You graduated with a bachelor's degree, master's degree or doctoral degree."
**E. PAL/TAL** - https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/get-documents/provincial-attestation-letter.html (Date modified: 2026-09-02): "You don't need a PAL or TAL when applying for a study permit if ... You're applying to study at a ... degree-granting graduate program at the master's or doctoral level at a public DLI starting January 1, 2026". Also exempt: schools in the "Francophone Minority Communities Student Pilot (FMCSP)" (relevant to Saint-Boniface / Sainte-Anne / Hearst if participating - not checked).
**F. DLI list page** - https://www.canada.ca/en/immigration-refugees-citizenship/services/study-canada/study-permit/prepare/designated-learning-institutions-list.html (Date modified: 2026-10-05): "this list includes all DLIs that currently offer programs of study that make you eligible for the PGWP."; "Not all programs offered by a DLI are eligible for a PGWP. Make sure to check the details". BC note: "Some listed programs, like associate degrees, must also meet the PGWP field of study requirement".

## 5. DLI rows (re-checked against dli-full-list.json via Chromium, 1,424 rows, 23 Oct 2026; all Public institution, Grad Program Yes, PGWP Yes)
| Institution | DLI # | Campus(es) |
|---|---|---|
| University of Regina (incl. Campion, FNUniv, Luther) | O19425660270 | Regina |
| UPEI | O19220071452 | Charlottetown |
| University of Guelph | O19305391192 | Main (Guelph), Guelph-Humber (Toronto), Alfred, Kemptville, Ridgetown |
| Algoma University | O19395422197 | Sault Ste. Marie (Main), Brampton, Timmins |
| Vancouver Island University | O19395299688 | Duncan, Nanaimo, Parksville, Powell River (city field; campus blank) |
| Concordia University of Edmonton | O19073475522 | Edmonton |
| Mount Allison University | O19273922302 | Sackville |
| St. Thomas University | O19391556376 | Fredericton |
| Université de Saint-Boniface | O19126670302 | Winnipeg |
| Université Sainte-Anne | O19391556726 | Church Point |
| Université de Hearst | O19395677925 | Hearst, Kapuskasing, Timmins |
| Yukon University | O19604209351 | Whitehorse (Ayamdigut) + 11 community campuses |
