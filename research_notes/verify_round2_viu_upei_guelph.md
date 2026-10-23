# Verification: VIU MEDL, UPEI MAIS, Guelph CDE (23 Oct 2026)

Verification agent. Each decisive source re-fetched with scratchpad/tools/fetch.sh (curl; --browser / curl --compressed where needed) and the quote grepped in the fetched text. Status: CONFIRMED / CORRECTED / NOT FOUND.

## Blocked hosts / fetch errors
(filled as encountered)

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
