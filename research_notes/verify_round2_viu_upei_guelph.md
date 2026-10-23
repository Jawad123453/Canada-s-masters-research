# Verification: VIU MEDL, UPEI MAIS, Guelph CDE (23 Oct 2026)

Verification agent. Each decisive source re-fetched with scratchpad/tools/fetch.sh (curl; --browser / curl --compressed where needed) and the quote grepped in the fetched text. Status: CONFIRMED / CORRECTED / NOT FOUND.

## Blocked hosts / fetch errors
None. www.viu.ca and programs.viu.ca returned gzip bytes to plain curl (fixed with curl --compressed); not a block.

## Plan
A. VIU MEDL (program page, international admissions, general regulations, Schedule #022, tuition-fee-schedule, medical insurance, gov.bc.ca ISHF).
B. UPEI MAIS (program page, calendar GA/GR/PR/T, fees page, ELP page, handbook).
C. Guelph CDE (cost page, Registrar grad fees, calendar, program page, credential guide, requirements page, English page).

## A. VIU MEd Educational Leadership, Full-Time option, Nanaimo

Fetched 23 Oct 2026 (all HTTP 200). www.viu.ca/admissions/tuition-fee-schedule and www.viu.ca/registration/general-regulations and programs.viu.ca returned gzip bytes through fetch.sh (curl without --compressed); re-fetched with `curl --compressed` - not a block.
- P1 https://www.viu.ca/programs/education/master-education-educational-leadership
- P2 https://www.viu.ca/admissions/international
- P3 https://www.viu.ca/registration/general-regulations
- P4 https://gov.viu.ca/sites/default/files/documents/Tuition%20and%20Fee%20Schedule%20022%20International%20APPROVED%20March%2031%202026.pdf
- P6 https://www.viu.ca/admissions/tuition-fee-schedule
- P7 https://international.viu.ca/international-student-support-iss-hub/medical-insurance
- BC https://www2.gov.bc.ca/gov/content/health/accessing-health-care/health-fee-international-students
- EDU https://education.viu.ca/master-education-programs ; CRS https://programs.viu.ca/courses/master-education-educational-leadership ; PGWP https://international.viu.ca/international-student-support-iss-hub/pgwp-eligible-programs

| Item | Status | Source | Verbatim (grep-matched) |
|---|---|---|---|
| Bar wording | CONFIRMED | P1 Admission Requirements | "a cumulative grade point average of “B” in the final two years and/or" / "demonstration of academic excellence" |
| Bar (intl page) | CONFIRMED | P2 "Admission to graduate programs" | "Minimum “B” average in the final 2 years of a Bachelor’s degree." |
| Grade scale | CONFIRMED | P3 "Grade scale: University, Academic, Adult Basic Education Programs" | B+ "76-79" 3.33; B "72-75" 3.00; B- "68-71" 2.67; "Effective September 1, 2010 VIU converted to a 4.33 grade scale." |
| % / Lebanon graduate row | CONFIRMED absent | P1, P2 | No % on P1/P2; P2 Lebanon row is only "General Secondary Education Certificate" (high-school table) |
| WES | CONFIRMED absent | P1, P2, P3 | grep "WES / World Education": zero hits. P2: "All documents must be translated by a certified translator or notarized" |
| Repeat rule | CONFIRMED (VIU's own courses only) | P3 | "if it is an upper-level course, the highest grade will be included in the graduation GPA calculation" - no admission rule for external transcripts |
| B.Ed | CONFIRMED preferred | P1 | "(preferably a Bachelor of Education degree, or equivalent)" ... "acceptable in content to the Faculty of Education" |
| Teaching experience | CONFIRMED preferred | P1 | "A résumé outlining teaching experience (two years preferred)." |
| Non-teachers | CONFIRMED | EDU | "are not limited to teachers working in the K-12 education" (sector) |
| IELTS | CONFIRMED | P2 graduate table | "IELTS (Academic)" "6.5" "(no band below 6.0)"; test "no older than 2 years". Only Academic listed. |
| Full-time on campus | CONFIRMED | P1 Full-Time Option | "designed for students wishing to study full-time on the VIU campus." EDU: "full-time face-to-face option designed for those wishing to study full time at the Nanaimo campus" |
| Year 2 course-based | CONFIRMED | P1 Program Outline | "Course Based Completion Option" = 3 x "Elective Course**" (9 cr); "Electives must be at the graduate level" |
| Year 1 share | CONFIRMED (arithmetic; per-course mode not stated) | P1 | Year 1 "Total Credits 21" of "Total Program Credits 30" = 70%; thesis-route MEDL 680/690 "may be completed on-campus or online" |
| Supervisor | CONFIRMED | CRS | MEDL 690 "Under the guidance of faculty mentors/supervisors" (thesis route only) |
| Deadlines (Intl) | CONFIRMED | P1 International table | "Sep 7, 2027" / "Oct 1, 2026 to Mar 31, 2027" / "Accepting Late Applications: No" / "Document deadline is April 16, 2027." / "one intake each Fall (September)" |
| Tuition | CONFIRMED | P4 | "Master of Education in Educational Leadership $ 704.62 per credit"; "March 31, 2026 Approved by the Board"; "April 1, 2026 Effective Date" |
| Intl table | CONFIRMED | P1 International Fees | "Tuition* (30 credits x $704.62 per credit) 21,138.60"; "Lab Fee 53.06"; "Total 24,142.46" |
| Monthly fees | CONFIRMED | P6 | "$20.78 per month"; "$22.94 per month"; "VIUSU fees – Nanaimo (as of April 1, 2026)" Total "$50.08"; "Fees are applicable throughout the entire year." Sum 93.80/month |
| Lab fee | CONFIRMED | P6 | "MEDL 600" "$53.06 lab fee" |
| Health & dental | CONFIRMED (discrepancy) | P1 vs P7 | P1 "Health and Dental Plan fee (2 years x $285.00 per year) 570.00"; P7 Greenshield "$275 per year" "charged annually" |
| guard.me | CONFIRMED | P7 | "Approximate cost $246 per semester"; "continue to be enrolled, and charged, for subsequent terms until proof of BC MSP is provided" |
| BC ISHF | CONFIRMED (minor wording fix) | BC | "a mandatory monthly fee of $75 charged to all international students studying in British Columbia on a valid study permit for at least six months of the year" (round 2 omitted "of the year"); wait = "the balance of the month in which residency is established, plus two months." P7: "$75 per month per student" |
| 2% increase | CONFIRMED | P1 | "are expected to increase by 2% each year on April 1." |
| Contacts | CONFIRMED | P1 | "educ.gp@viu.ca"; "Ekaterina.Kurovskaia@viu.ca"; transcripts "study@viu.ca" (Intl); application fee "$156.06" |
| PGWP | CONFIRMED | PGWP page | "PGWP eligible as long as at least 50% of the program is completed in person in Canada." |

New item not in round-2 notes (in-program risk): P1 "Program Progression Requirements": "Students must maintain a minimum average of ‘B’ (3.0) in each semester of the program"; "they may retake up to 2 individual courses".

### Recomputed cost (2026-27 rates, Schedule #022)
Monthly fees 20.78 + 22.94 + 50.08 = 93.80. ISHF: arrive Aug 2027 -> wait Aug (balance) + Sep + Oct -> charged from Nov 2027.
| Item | 16 mo (Sep27-Dec28) | 20 mo (Sep27-Apr29) |
|---|---|---|
| Tuition 30 x 704.62 | 21,138.60 | 21,138.60 |
| Lab fee | 53.06 | 53.06 |
| Monthly fees 93.80 x 16 / 20 | 1,500.80 | 1,876.00 |
| VIUSU health & dental 2 x 285 | 570.00 | 570.00 |
| guard.me 1 semester | 246.00 | 246.00 |
| ISHF 75 x 14 / 18 | 1,050.00 | 1,350.00 |
| Mandatory total | 24,558.46 | 25,233.66 |
| + textbooks 880 (VIU estimate) | 25,438.46 | 26,113.66 |
Matches round 2 exactly. With VIU's stated +2%/yr applied to all VIU items (Apr 2027 x1.02, Apr 2028 x1.0404): tuition 21,690.74; mandatory 25,181 (16 mo) / 25,873 (20 mo). < 27,000 -> no fee-increase flag at 2%.
Verdict unchanged: F2-F6 PASS (full-time option), F3 PASS; F1 UNCONFIRMED (plain "B" = VIU 72-75%; no Lebanon/WES rule).

## B. UPEI MA Island Studies (course-based)

Fetched 23 Oct 2026 with curl --compressed (all HTTP 200); handbook PDF via fetch.sh.
- P https://www.upei.ca/programs/island-studies
- GA https://calendar.upei.ca/current/chapter/graduate-program-admissions/
- GR https://calendar.upei.ca/current/chapter/graduate-academic-regulations/
- PR https://calendar.upei.ca/current/chapter/program-regulations-graduate-studies/
- C https://calendar.upei.ca/current/chapter/master-of-arts-ma-island-studies/
- T https://calendar.upei.ca/current/chapter/tuition-and-fees-2/
- FP https://www.upei.ca/fees?field_faculty_department_tid=All&field_level_value=graduate&field_time_value=fulltime&field_type_value=international
- E https://www.upei.ca/admission-requirements/english-language-proficiency-requirements/graduate-programs
- AD https://www.upei.ca/admission-requirements/graduate-admissions ; CS https://www.upei.ca/admission-requirements/country-specific-requirements
- H https://files.upei.ca/arts/mais/mais_student_handbook.pdf ; ISO https://files.upei.ca/iso/welcome_to_upei.pdf ; SU https://www.upeisu.ca/health-dental ; BN https://www.upei.ca/communications/news/2026/04/upei-board-governors-approves-balanced-2026-2027-operating-budget

| Item | Status | Source | Verbatim (grep-matched) |
|---|---|---|---|
| Bar | CONFIRMED | P "Admissions Criteria" | "The applicant will ordinarily be expected to have achieved an average of at least second class (“B”, i.e. 70% to 79.9%) standing in the work of the last four semesters or the last two undergraduate years." GA "Master of Arts (MA)" has the same text with "second-class (“B,” i.e., 70% to 79.9%)" |
| Reference standard | CONFIRMED | GA/P | "the standard of reference is the typical Canadian university curriculum and university system." |
| Registrar evaluates | CONFIRMED | GR | "The evaluation of transcripts shall be the responsibility of the Registrar’s Office in consultation with the appropriate Department and Dean." |
| No WES | CONFIRMED absent | P, GA, GR, AD, CS, C | grep "WES / World Education": zero hits. AD: "we will not pre-evaluate your transcripts or other scores for admissibility." |
| Lebanon | CONFIRMED (undergrad only) | CS | "LEBANON" / "Baccalaureat II with a score of at least 12/20 (Good)." (high-school row; no graduate row) |
| Provisional | CONFIRMED | PR §2 (MSc/MVSc/MA/PhD section) | "An applicant whose qualifications are not completely clear may be admitted as a full-time provisional student." Review "at the end of one semester" |
| Repeated-course admission rule | CONFIRMED absent | GA, GR, P, C, AD | grep "repeat/retake": zero hits in GA, GR, P, C, AD. (PR "repeat that course one time" is the MEd/PhD Education in-program rule only) |
| In-program bar | CONFIRMED | PR §5 (MA section) | "must maintain a cumulative average grade of at least 75% in the substantive courses" |
| IELTS | CONFIRMED | E graduate table, column "REGULAR OFFER (ALL PROGRAMS EXCEPT THOSE NOTED IN NEXT COLUMN)" | "IELTS (Academic)" "7 in writing and no band lower than 6.5"; conditional "6". Only Academic listed. |
| Supervisor | CONFIRMED | P | "You do not have to secure a supervisor prior to applying to this program." C: "Coordinator (for the course-based option)" |
| Delivery | CONFIRMED | P | "Course-based stream students will participate in in-person and/or hybrid model delivery courses, combining face-to-face, online, and video-based instruction."; Year 2 courses "each delivered mostly face-to-face"; IST 6210 "might be at your home location, on PEI or at other sites around the world." |
| Full-time | CONFIRMED | PR, ISO | "Students are enrolled in the MAIS on a program basis and are considered to be full time graduate students."; ISO "Graduate Students are always full time, and must be enrolled every semester." |
| Degree fit | CONFIRMED | P | "We welcome students from around the world with diverse disciplinary backgrounds and diverse degrees" |
| Tuition | CONFIRMED | T "Tuition by Program" | "Master of Arts in Island Studies" / "Per three semester hour credit course – $1,536" / "International Fee per course – $972" / "Maintenance of Status Fee per term – $500" |
| Fee year | CONFIRMED | T, FP | T "approved by the University of Prince Edward Island Board of Governors for the 2026/2027 Academic Year"; FP "approved ... for the 2026–2027 academic year." |
| $9,718 line | CONFIRMED (two places) | T, FP | T: "International students fee per annum– $9,718" is under "Undergraduate Programs". FP lists both "Full-Time International Fee (Graduate programs) - $9,718 per year" and "International Fee (Master of Arts in Island Studies) - $972 per course / This amount is paid in addition to course tuition". P: "International students pay $972 per course in addition to full-time course tuition." |
| UPEI fees | CONFIRMED amounts; PERIOD NOT STATED | FP, T | "Library Resource Fee - $96", "Fitness and Recreation Fee - $294" (T: "Fitness and Administration Fee – $294"), "Technology Fee - $107". No "per year"/"per term" on FP, T, H, /fees/deadlines, /fees/money-matters, /fees/other-fees. ISO: "Tuition and fees are payable each term" (payment timing, not period). UNCONFIRMED. |
| UPEISU fees | CONFIRMED amounts; period not stated | FP | CFS $12, Student Centre $46, Transit $72, WUSC $10, CASA $6, Student Union Fee $198, Wellness $6 = $350 |
| Health + dental | CONFIRMED annual | FP, T, SU | FP "International Student Health Insurance - $1,000" ("may partially opt out"), "International Student Dental Insurance - $186"; T = "Single Extended Health Insurance – $328" + "International Single Medical Insurance – $672"; T "The term of coverage is from September 1st to August 31st of each registered year"; SU "Insurance coverage terminates each year on August 31st" -> per YEAR |
| Deadlines | CONFIRMED | P | Fall "July 1 (international students)", materials "July 8 (international students)"; Winter "November 1", materials "November 8"; "Students applying by March 31 will receive first consideration for scholarships." |
| Deposit | CONFIRMED | P, T | "international applicants $3,000"; T: "First year international students for all course based Graduate programs are required to pay a $3,000 deposit." |
| Contacts | CONFIRMED | P | "Dr. Laurie Brinklow, Co-ordinator, MAIS - brinklow@upei.ca"; "mais@upei.ca" |
| Length | CONFIRMED | H "MAIS Timeline (Course – Based)" | Term 1 Fall ... Term 6 Summer (IST 6200 June, IST 6220 July-August); 5 courses/year |
| Increases | CONFIRMED | BN | "UPEI will increase tuition by 6.5% and international fees by 7.5%." ; "the second of at least four years of continued recalibration" |

### Recomputed cost (2026-27 rates)
- Tuition 10 x 1,536 = 15,360; international fee 10 x 972 = 9,720 -> 25,080
- Annual fees: UPEI 96+294+107 = 497; UPEISU 350; health 1,000 + dental 186 = 1,186 -> 2,033/yr; x 2 years = 4,066
- TOTAL 29,146 -> CONFIRMED (< 30,000; >= 27,000 fee-increase risk).
- Sensitivity (new): if the 847 UPEI+UPEISU fees are per Fall/Winter term rather than per year, add 847 x 2 per year = +1,694 -> 30,840 (FAIL even at 2026-27 rates); if charged in all 3 terms, 32,534. Period must be asked.
- Fall 2027 projection at 6.5%/7.5% repeated: 13,403.70 (2027-28, 5 courses) + 14,327.20 (2028-29) + 4,066 = 31,796.90 -> CONFIRMED arithmetic; FAIL on projection.
Verdict unchanged: F2/F4/F5/F6 PASS; F1 UNCONFIRMED; F3 PASS only at 2026-27 rates and only if fees are annual; projected FAIL for Fall 2027.

## C. University of Guelph, Master of Capacity Development & Extension (MSc CDE, coursework option)

Fetched 23 Oct 2026 with curl --compressed (all HTTP 200; graduatestudies.uoguelph.ca reachable).
- COST https://graduatestudies.uoguelph.ca/future/cost
- REG https://www.uoguelph.ca/registrar/finances-fees/tuition-fees/guelph-grad
- CAL https://calendar.uoguelph.ca/graduate-calendar/graduate-programs/capacity-development-extension/
- PROG https://www.uoguelph.ca/programs/master-capacity-development-extension/
- ICG https://graduatestudies.uoguelph.ca/future/international/credential
- REQ https://graduatestudies.uoguelph.ca/future/apply/requirements
- ENG https://graduatestudies.uoguelph.ca/future/international/english

| Item | Status | Source | Verbatim (grep-matched) |
|---|---|---|---|
| Annual = 3 semesters | CONFIRMED | COST "Graduate Tuition" | "Annual tuition includes tuition for three consecutive semesters: Fall, Winter, and Summer." |
| CDE row | CONFIRMED, NO asterisk | COST | "Master of Capacity Development and Extension" "$7,133" "$21,946" "$24,141" (domestic 2026-27 / intl 2026-27 / intl 2027-28). "**Program is billed per credit. The listed fee reflects cost of total required credits for program" applies only to ** rows (MBA, MA Leadership, MA Mental Health, MCJ, cyber x2, MEM, MPAcc, MRE, MSCM). -> 24,141 is ANNUAL |
| Registrar tuition | CONFIRMED (CDE not listed) | REG "Fall 2026, Winter 2027 & Summer 2027" | "Regular Masters (MA, MSC, MASC, GDIP - unless listed separately below)" "$2,377.53" "$6,837.54" per semester. PROG: "Degree MSc (Master of Science)" -> REG would give 3 x 6,837.54 = 20,512.62 vs COST 21,946 (discrepancy stands; COST "Other Master of Science programs" = "$20,512") |
| Compulsory fees | CONFIRMED | REG, full-time | "Total Compulsory Fees" "$937.21" "$642.80" "$635.55" (Fall/Winter/Summer) = 2,215.56/yr |
| UHIP | CONFIRMED | REG | "(UHIP, international students only, charged annually in the fall semester)" "$948.00" |
| Length | CONFIRMED (conflict) | CAL vs PROG | CAL: "a full-time course-based, professional development option, which requires three to four semesters of study." PROG: "Duration Full Time: 24 months" |
| Coursework | CONFIRMED | CAL | "Students must complete 4.50 credits according to the following: five (5) core courses, a minimum of four (4) electives". New: required CDE*6030 is "Summer Only" and is completed via "an internship or a group field tour project" -> a F-W-S 3-semester path is structurally possible (inference) |
| Lebanon row | CONFIRMED, NO grade threshold | ICG "Lebanon" | "Master's Minimum Admission Requirement" / "Bachelor`s, Licence requiring 4 years of study" / "Typical Degree Credits: Not available" / link "Lebanon's most common grading system" (Scholaro) / "Effective 2025-10-01". No country row on ICG has a % or /20 figure (grep "%" and "/20": zero hits). |
| General bar | CONFIRMED | REQ "Master's Admission" | "70% (B-) average is required in the last two years of full-time equivalent study." |
| US scale | CONFIRMED | REQ "Grade Conversion" | "Guelph's minimum grade requirement equivalent of 70% (B -) which is 3.0 on the US 4.0 scale." Also: "Scholaro may be used for country specific grading scales." |
| International years | CONFIRMED | REQ | "Typically, the last 4 full-time semesters (or 6 full-time semesters for full-year education systems) equivalent credits." ; "moving backward per credit until the equivalent of the last two years of full-time study is achieved." |
| WES | CONFIRMED | REQ | "Transcript evaluation services are not accepted for credentials assessments. However, World Education Services (WES) evaluation reports are accepted as certified copies of official transcripts." |
| Repeat rule | CONFIRMED absent | REQ, PROG, CAL CDE section | no "repeat/failed" wording |
| Program bar | CONFIRMED | PROG | "Admission Average B- (70% - 72%)"; "at least second class honours (B-) in the last four semesters of full-time study or two years of professional work in a related field." CAL: "A four-year honours undergraduate degree with a least B- in the last two years of undergraduate study" |
| Degree fit | CONFIRMED | CAL | "open to qualified graduates from a wide variety of disciplines including ... health" |
| Supervisor | CONFIRMED | PROG "How to Apply" | "you are not required to secure a faculty advisor to supervise your program." |
| Delivery | CONFIRMED | PROG | "Delivery On-campus"; CDE*6030 "Not offered through Distance Education" |
| Deadline | CONFIRMED (conflict remains) | PROG | header "International : Fall (September): April 15", "Winter (January): October 25, 2026", "Summer (May): January 31"; lower: "Applications are ongoing for international students" and "Note: Only Fall semester entry is available for this program." |
| IELTS | CONFIRMED | ENG | "International English Language Testing System (Academic) (IELTS)" / "Computer-delivered IELTS" "6.5" (column "Minimum Overall Score"; no IELTS sub-band) |
| Contacts | CONFIRMED | PROG | Lorena Barker "cde@uoguelph.ca"; Leigh West "lewest@uoguelph.ca" |

### Scholaro (third-party tool that Guelph's own REQ and ICG point to; NOT Guelph's own conversion)
https://www.scholaro.com/db/Countries/Lebanon/Grading-System (HTTP 200): "Most Common 100-Point": "70.000 - 79.000" "good (bien)" US "B+"; "University Level": "70.000 - 79.990" "Good" US "B"; "60.000 - 69.990" "Acceptable" US "C". If Guelph applies this, 70.51% overall and ~73% last-two-years both map to US B (3.0) = meets "3.0 on the US 4.0 scale"; the ~66-67% all-attempts figure maps to US C (University Level) and fails. This shifts Guelph F1 from "FAIL-leaning" to "UNCONFIRMED, leaning PASS if retakes replace failures" - still needs the program's confirmation.

### Recomputed cost (Fall 2027 entry; 2027-28 intl tuition; fees/UHIP at 2026-27 rates)
- Per semester tuition 24,141 / 3 = 8,047.00; compulsory 937.21 + 642.80 + 635.55 = 2,215.56; UHIP 948
- 3 semesters (F27/W28/S28): 24,141 + 2,215.56 + 948 = 27,304.56 -> CONFIRMED (< 30k, fee-increase risk)
- 4 semesters (+F28): 27,304.56 + 8,047 + 937.21 + 948 = 37,236.77 -> CONFIRMED (FAIL; floor, uses 2027-28 rate)
- 24 months / 6 semesters: 2 x 27,304.56 = 54,609.12 (FAIL)
- Cross-check 2026-27 (cost page) 21,946 + 2,215.56 + 948 = 25,109.56; Registrar regular-MSc rate 23,676.18. 2027-28 increase on cost page +10.0%.
Verdict: F2/F4/F5/F6 PASS; F3 PASS only if finished in 3 semesters (else FAIL); F1 UNCONFIRMED (no Lebanon threshold; Scholaro mapping favourable for 70-73%).

## Blocked hosts (final)
None. Only fetch issue: www.viu.ca (tuition-fee-schedule, general-regulations) and programs.viu.ca return gzip-compressed bodies to plain curl; fixed with `curl --compressed`.
