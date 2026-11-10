# University of Regina master's table A (Engineering, Science, KHS, Nursing, Social Work) — check date 10 Nov 2026

Method: fetch.sh --browser (headless Chromium) of official uregina.ca pages; 2026-27 graduate calendar program pages; Fall 2026 + Winter 2027 grad fee schedules. Only official rules, quotes, URLs and costs.

## Blocked hosts
(none yet)

## Plan
1. Master's list page -> enumerate programs/routes in the five faculties
2. Calendar pages per program (credits, routes, supervision, admission, length)
3. How to Apply (deadlines, PGWP-ineligible list)
4. Fee schedules (columns), cost arithmetic
5. Table

## 1. Inventory (Master's Programs list page, fetched 10 Nov 2026)
URL: https://www.uregina.ca/graduate-studies-research/programs/masters-programs.html
- Engineering & Applied Science: ESE (MASc/MEng), ERSE, EVSE (MASc/MEng), ISE (MASc/MEng; embedded MCerts Adv. Manufacturing, Eng. Management), PSE (MASc/MEng; MCert Geothermal), PSEng (MASc/MEng; MCert CCUS), SSE (MASc/MEng; MCert AI in Engineering). The list shows "Suspended for one year, effective 202630 ..." directly under the SSE link; the SSE calendar page places this under "Embedded Certificate Options" and "Suspended Programs: Master's Certificate (MCert) in Artificial Intelligence in Engineering — Admission to this program has been suspended for one year, effective 202630." -> the suspension on the calendar page is the AI MCert, NOT the SSE MASc/MEng (correction to regina_all_masters_2026-11.md, which read it as SSE suspended). SSE MASc/MEng still listed with no suspension note.
- KHS: "Kinesiology and Health Studies (MSc)", "Kinesology (MKin)" [sic].
- Nursing: "Master of Nursing", "Collaborative Nurse Practitioner Program (CNPP)".
- Science: Biology, Chemistry/Biochemistry, Computer Science, Earth Sciences, Mathematics/Statistics, Physics (all MSc).
- Social Work: "Social Work", "Indigenous Social Work".

## 2. Calendar pages (2026-27 graduate calendar web pages, all fetched 10 Nov 2026 with --browser)
Base: https://www.uregina.ca/graduate-studies-research/graduate-calendar/all-programs/<page>.html

### Engineering (contact engg.grad@uregina.ca)
| Program/route | Credits (calendar TOTAL) | Structure / quote |
|---|---|---|
| ESE MASc (thesis) engg-ese | 30 | 5 courses + ENGG 401 (3) + ENEL 901 12 ch; "research-oriented program with a thesis requirement"; "All MASc and PhD students must have an identified supervisor from Electronic Systems Engineering." |
| ESE MEng (project) | 30 | 8 x 3-ch courses + ENGG 701/702/703 (1 each) + "ENEL 917 (taken over two semesters)" 3 ch; "oriented towards students desiring professional rather than academic careers"; "MEng students will normally be assigned a project supervisor just prior to starting their project" |
| ESE MEng (co-op) | 30 | as project + ENGG 601/602 (0 ch) |
| ESE admission | — | "MEng applicants from non-engineering backgrounds ... are welcome." ; lacking design/law/ethics/economics "may be admitted as “qualifying students.”" |
| ERSE MASc (thesis) engg-erse | 30 | 5 courses + ENER 901 15 ch |
| ERSE MEng (project) | 30 | 8 courses + ENGG 701-703 + ENER 902 (3); "with a project report attracts practicing engineers" |
| ERSE MEng (co-op) | 30 | + ENGG 601/602. ERSE page has no admission/supervision section. |
| EVSE MASc (thesis) engg-evse | 30 | 5 courses + ENEV 901 15 ch |
| EVSE MEng (project) | 30 | 7 courses + ENGG 701-703 + ENEV 902 6 ch |
| EVSE MEng (co-op) | 30 | 8 courses + ENGG 600 + 601/602 + 701-703 (no project listed) |
| ISE MASc (thesis) engg-ise | 30 | 5 courses + ENIN 901 15 ch |
| ISE MEng (course) | 39 | 12 courses + ENGG 701-703 |
| ISE MEng (project) | 30 | 7 courses + 701-703 + "ENIN 902 (over 2 semesters at 3 cr hrs each)" 6 ch |
| ISE MEng (co-op) | 30 | as project + 601/602 |
| PSE MASc (thesis) engg-pse | 30 | 5 courses + ENPE 901 15 |
| PSE MEng (project/co-op) | 30 / 30 | 8 courses + 701-703 + ENPE 902 (3) |
| PSEng MASc (thesis) engg-pseng | 30 | 5 courses + ENPC 901 15 |
| PSEng MEng (project/co-op) | 30 / 30 | 8 courses + 701-703 + ENPC 902 |
| SSE MASc (thesis) engg-sse | 30 | 5 courses + ENSE 901 15; "All MASc and PhD students must have an identified supervisor from Software Systems Engineering." |
| SSE MEng (project/co-op) | 30 / 30 | 7 courses + 701-703 + "ENSE 902 (over 2 semesters at 3 credit hours each)" 6; "The MEng is effectively a course-based program ... MEng students will normally be assigned a project supervisor" ; qualifying admission possible |

### Science
| Program/route | Credits | Quote |
|---|---|---|
| Biology MSc (thesis) | 30 | "thesis-based degree programs"; "We strongly recommend arranging for a supervisor prior to applying for admission" |
| Chemistry MSc (thesis), Biochemistry MSc (thesis) | 30 each | CHEM/BIOC 800 + 2 courses + 901 21 ch; "Complete and defend a research thesis" |
| Computer Science MSc (thesis) | 30 | 15 coursework + CS 901 15 |
| CS MSc (project) | 30 | "Admission to this program is suspended, effective 202810." (Winter 2028) — 21 coursework + CS 902 9 ch |
| CS MSc (course) | 30 | "Admission to this program has been suspended effective 202130" |
| CS MSc (Data Science) (course) | 30 | "Admission to this program has been temporarily suspended." |
| CS MSc (Human-Centred Computing) (course) | 30 | "Admission to this program has been temporarily suspended." |
| Earth Sciences MSc (thesis) | 30 | "must complete a thesis project under the supervision of a faculty member" |
| Math MSc thesis / course; Statistics MSc thesis / course / co-op; Actuarial Science MSc (course) | 30 each | "The entrance requirement for the MSc program is a BSc degree in mathematics or statistics, with a grade average of at least 75%."; "The MSc degrees normally requires two years of study" |
| Physics MSc (thesis) | 30 | "A BSc Honours degree (or equivalent) in physics or engineering physics is required"; "minimum average of 75% in all physics and mathematics courses"; international deadlines "May 15 for ... Fall" / "August 15 for Winter" |

### KHS, Nursing, Social Work
| Program/route | Credits | Quote |
|---|---|---|
| KHS MSc (thesis) | 30 | "Admission is contingent on students securing a supervisor for their program."; research-methods course required; Bio-Sciences area needs "human anatomy, human physiology, biomechanics and movement science" |
| MKin | 30 | "KHS 8** ... 24", KHS 902, KHS 903 |
| Master of Nursing (course) | 30 | "This program is offered through distance learning"; "may not qualify for a Post Graduate Work Permit"; "Registered Nurses, Registered Psychiatric Nurses or Licensed Practical Nurses with any baccalaureate degree" |
| CNPP (MN, NP specialization) | 33 | "delivered entirely in an online asynchronous format"; "be licensed to practice as an RN in a Canadian Province(s) or Territory"; Effective 202730 "overall grade point average of 75% in the most recent 60 credit hours" |
| MSW (thesis) / MSW (Field Education) | 30 / 30 | "must hold a Bachelor of Social Work (BSW) degree with a minimum GPA of 70% and have the equivalent of at least two years employment in a social work position"; research-practicum and field-practicum routes "Effective 202710, admissions to this program are suspended." |
| MISW (internship) (FNUniv) | 30 | "Admission to this program will resume for Fall 2022 and in alternating years thereafter, i.e. 2024, 2026."; deadline "March 15 of each alternating year"; "Candidates will enroll on a full-time basis."; MISW (thesis) "This route is not offered at this time." |

## 3. Program pages (www.uregina.ca/academics/programs/..., fetched 10 Nov 2026; parallel Chromium runs first returned "This site can’t be reached" for 14 pages — refetched sequentially, all OK)
- ESE engineering/masters-phd-electronic-systems-engineering.html Quick Facts "Length:" "Master of Applied Science – Thesis: 2 years" / "Master of Engineering – Project: 2 years" / "Master of Engineering – Co-op: 2 years, 8 months". Program-list wording: "Master of Engineering – Co-op (38 credit hours)" — CONFLICT with calendar co-op TOTAL 30 (ENGG 601/602 listed at 0 ch). Same 38-ch co-op wording on EVSE, ISE, PSE, PSEng, SSE pages, which also list "Master of Applied Science – Co-op (38 credit hours)" (no MASc co-op table in the calendar).
- ERSE, EVSE, ISE, PSE, PSEng, SSE pages: Length identical pattern — MASc thesis 2 years; MASc co-op 2 years 8 months; MEng project 2 years; MEng co-op 2 years 8 months.
- No program page states a suspension for any engineering master's. ISE page lists only MASc thesis/co-op and MEng project/co-op — the calendar's MEng (course) 39 ch is not on the program page.
- Engineering Graduate Students page https://www.uregina.ca/engineering/graduate-students/Index.html: "It is recommended that you make contact with the professors to find a supervisor before you complete your application." / "You may still apply if you have not made contact." / "Electronics MENG students do not need to contact professors, all applications are reviewed automatically by the Program". "Programs Currently Offered": ESE, EVSE, ISE, PSE, PSEng, SSE each "Thesis (MASc, PhD) / Project (MEng) / Co-op (MEng, MASc)". ERSE NOT listed under "Programs Currently Offered" (UNCONFIRMED whether ERSE admits). "a fulltime student takes 6 credit hours per semester and there are three semesters in a year."

## 4. How to Apply (https://www.uregina.ca/graduate-studies-research/future-students/how-to-apply.html, fetched 10 Nov 2026; deadline table parsed from HTML)
- PGWP list: "IRCC requires at least 50% of a program of study to be in-person to apply for a study permit and subsequently a post-graduation work permit. The following programs are not eligible for either: Master of Nursing / Master of Social Work / Master of Health Administration / Graduate/Master Certificates"
- WES ICAP required for: Computer Science, Education, "Engineering and Applied Science (Master of Science in Electronic Systems Engineering - Thesis is exempted from this requirement)", Levene, KHS, MAP, Social Work.
- No-deadline programs: "Spring/Summer - March 1 / Fall - July 1 / Winter - November 1" (applies to Biology, Earth Sciences — not in the table).
- Engineering: "For Winter admission: July 31 / For Fall admission: January 31 / Late applications will not be accepted"
- KHS: "For Fall admission: April 15 / For Winter admission: August 15"
- Nursing: MN "For Fall admission: July 1 / For Winter admission: November 1 / For Spring/Summer admission: March 1"; "Applications for the Master's of Nursing and Graduate Certificates will open in November."; CNPP "For Fall or Winter admission: January 31"
- Chemistry and Biochemistry: Fall April 15 / Winter August 15 / S/S December 15
- Computer Science: Fall February 15 / Winter June 15 / S/S October 15; "Master of Science – Human-Centred Computing" "For Winter admission only: June 15 (admission to this program has been postponed until further notice)"; "Master of Science – Data Science" "For Fall admission only: February 15 (admission to this program has been postponed until further notice)"
- Math/Stats: thesis MSc/PhD "For Fall admission: January 31 / For Winter admission: June 30"; course MSc Math, Actuarial Science, Statistics course and co-op: "For Fall Admission only: October 31"
- Physics: "For Fall admission: May 15 (recommended for international applicants) / For Winter admission: August 15"
- Social Work: MSW "For Spring/Summer/Fall admission: November 1"; Indigenous Social Work "March 15 (admission will be in alternating years i.e. 2020, 2022, 2024 etc.)"

## 5. Program pages — Science / KHS / Nursing / SW (fetched 10 Nov 2026)
- Biology science/master-phd-biology.html: "Master’s Degree: 2-3 years"; "four-year bachelor's degree in biology with an overall average of at least 70 per cent"; "arranging for a supervisor prior to applying for admission" (calendar: "strongly recommend").
- Chem/Biochem science/master-phd-chemistry-biochemistry.html: "Master’s Degree: 2-3 years"; "four-year bachelor's degree in chemistry or biochemistry with an overall average of at least 70 per cent"; "coursework and research under the supervision of a faculty member".
- Computer Science science/master-phd-computer-science.html: "Master’s Degree: 2 years"; "four-year bachelor's degree in computer science with an overall average of at least 70 per cent, and a computer science average of at least 75 per cent." CS grad index https://www.uregina.ca/science/computer-science/graduate-programs/index.html: "the professionally-focused programs are currently under review and not accepting new students at this time. The earlier course-based MSc option is no longer available."; "The normal duration is 2 years (6 terms) full-time". CS application process page: "if you wish to pursue a Ph.D., M.Sc. Thesis, or M.Sc. Project degree, you must find a potential supervisor within our department who is accepting new graduate students."; Data Science / HCC "do not need to contact a supervisor in advance" (but not accepting). Non-CS degree: "we still require an equivalent B.Sc degree in Computer Science, with the equivalent of 10 CS 300- or 400-level courses".
- Earth Sciences science/master-phd-earth-sciences.html: "Master’s Degree: 2 years".
- Math/Stats science/master-phd-mathematics-statistics.html: "Master’s Degree: 2 years"; "minimum requirement of a 75 percent average in their Bachelor of Science within the same subject area"; "four-year undergraduate degree in science in Mathematics or Statistics". Program page lists Math thesis/course, Stats thesis/course/co-op (Actuarial Science MSc on calendar only; science/actuarial-science.html is the BSc page).
- Physics science/master-phd-physics.html: "Master’s Degree: 2 years"; "four-year Bachelor of Science honours degree in physics or engineering physics".
- KHS MSc khs/master-phd-kinesiology-health-studies.html: "Master’s Degree: 2-3 years"; "You must also secure a supervisor before applying to your program."
- MKin khs/masters-kinesiology.html: "Length: 2 years"; "four-year health sciences bachelor’s degree"; "human anatomy, human physiology, and two other human health sciences classes"; second practicum "students must identify and secure a supervised setting in the community".
- MN nursing/master-nursing-course-based.html: "Length: 2-6 years"; "Courses are offered online, through web-based learning".
- CNPP nursing/master-nurse-practitioner.html (renders Sask Nursing Degree site): "an online graduate level program offered through a joint partnership between the Saskatchewan Polytechnic and the University of Regina".
- MSW social-work/master-social-work.html: "Full-time, degree requirements can be completed in 2 years."
- MISW social-work/master-indigenous-social-work.html: "Length: 1 year"; "This program takes place on our Saskatoon campus."; offered with First Nations University of Canada.

## 6. Calendar PDF cross-check (https://www.uregina.ca/graduate-studies-research/assets/docs/fgsr-docs/2026-2027-graduate-calendar.pdf, revision "September 9, 2026 Updated deferral section and suspended programs")
- PDF has NO suspension note for SSE or its AI MCert, and no "suspended, effective 202810" note on CS (project) — the web calendar pages (fetched 10 Nov 2026) are newer and carry these notes. Treat web as current.
- PDF Nursing: "Clinical Nurse Specialist (CNS) (Admission to this program has been suspended until further notice)"; "The entire program can be taken online". (Not on web Master's list.)
- PDF MSW research practicum / field practicum "suspended effective 202710".

## 7. Fees — columns and arithmetic (2026-27 rates)
Sources: F26 https://www.uregina.ca/financial-services/assets/pdf/fee-schedules/202630-grad-studies-tuition-schedule-may-15.pdf ("Fall 2026 (202630) SEMESTER as of May 15, 2026 (subject to change)"); W27 https://www.uregina.ca/financial-services/assets/202710-grad-studies-tuition-schedule-oct-16.pdf ("Winter 2027 (202710) SEMESTER as of October 16, 2026"). Both HTTP 200, read in full.
- Columns (international tuition per ch, identical F26/W27): "Masters Programs (Including MCERT)" 365.50; "Master of Engineering (Including MCERT) (All Students)" 597.75; "Master of Nursing (NP & CNS) (Including MCERT)" 597.75; "Master of Journalism" 597.75; "Master of Science in Computer Science (Data Science and Human Centered Computing)^^^" 597.75. Note ^^^: "All other Computer Science graduate programs tuition is calculated using the regular MSc and PhD rates."
- Column assignment: MEng (all streams) -> MEng column. MASc -> "Masters Programs" (INFERENCE: MEng column header names only Master of Engineering; no MASc column). MSc (Science, KHS), MKin, MSW, MISW, course-based MN -> "Masters Programs" (MN course-based INFERENCE: the Nursing column is labelled "NP & CNS" only). CNPP (MN-NP) -> Nursing (NP & CNS) column. CS Data Science/HCC -> 597.75 column.
- Per-term add-ons (int'l): "International Surcharge" 1,487.25; "*Students' fees will be assessed as $44.60/student plus $5.70/credit hour"; SSHW 117.65; "Academic Technologies Fee of $26.80 per semester"; U-Pass 90.00 ("enrolled in at least one on-campus course"); H&D 225.85 Fall only at >=6 ch ("The Plan and the $225.85 fee are mandatory"). "Co-op Fee 1,149.00 per term". GRST 995AA (finished credit hours, thesis/project not yet defended) int'l "3,903.50" per term (On Campus, Full time). Application fee 125.00 (excluded).
- Schedule row checks: Masters F6 4,219.35 / W6 3,993.50 / W3 2,879.90 / F12 6,446.55 / W12 6,220.70; MEng F6 5,612.85 / W6 5,387.00 / W3 3,576.65 / F9 7,423.20 / W9 7,197.35. S/S priced at the Winter 2027 schedule (S/S takes preceding Winter's rate — see deepcheck_regina.md fee-year finding). All totals below at 2026-27 rates, no escalation (Fall 2027 start would be ~+3%/yr).

| Scenario | Pattern | Total CAD |
|---|---|---|
| MEng project (any stream) 30 ch, 2 yrs | F6 W6 S3 F6 W6 S3 | 29,153.00 (5,612.85+5,387.00+3,576.65+5,612.85+5,387.00+3,576.65) |
| MEng project 30 ch, 5 terms | F6 W6 S6 F6 W6 | 27,386.70 |
| MEng co-op 30 ch (coursework as 6-term) + 2 x co-op fee | + 2,298.00 | 31,451.00 (work-term surcharge/fees UNCONFIRMED; program page length 2 yrs 8 months) |
| ISE MEng course 39 ch | F9 W6 S6 F6 W6 S6 | 34,584.05 ; 5-term F9 W9 S3 F9 W9 = 32,817.75 |
| MASc / MSc thesis 30 ch at Masters rate | F6 W6 S3 F6 W6 S3 | 22,185.50 ; each extra term on GRST 995AA +3,903.50 (3-yr thesis ≈ 33,896.00 + any H&D) |
| MASc if billed at MEng rate (worst case) | same | 29,153.00 |
| MSc course (Math/Stats/Actuarial) 30 ch | F6 W6 S6 F6 W6 | 20,419.20 |
| MSc Statistics co-op 30 ch | F6 W6 [S co-op] F6 W6 [S co-op] F6 + 2 x 1,149 | 22,943.05 |
| MKin / MSW / MN 30 ch | F6 W6 S6 F6 W6 | 20,419.20 ; 6-term F6 W6 S3 F6 W6 S3 = 22,185.50 |
| MN online, no U-Pass, 5 terms | | 19,969.20 |
| MISW 30 ch, 1 yr | F12 W12 S6 | 16,660.75 |
| CNPP 33 ch (NP column) | F6 W6 S6 F6 W6 S3 | 30,963.35 (no U-Pass: 30,423.35) |
| CS Data Science / HCC 30 ch | F6 W6 S6 F6 W6 | 27,386.70 (suspended) |

## 8. Summary judgements (BME graduate; deadlines for Fall 2027 unless noted)
- Best fits: ESE MEng project (signal/image processing, ML, embedded; no supervisor contact; 27,386.70–29,153.00 → fee-increase risk flag >=27k); ISE MEng project (control, robotics, "human powered" modelling, manufacturing; supervisor contact "recommended", not required; same cost). SSE MEng project moderate (software/AI). EVSE/PSE/PSEng/ERSE MEng project: weak topical fit. All Engineering: Fall deadline 31 Jan 2027, Winter 31 Jul 2027, "Late applications will not be accepted"; WES ICAP mandatory.
- MASc (all streams): thesis; ESE/SSE "must have an identified supervisor"; others "recommended" — fails no-supervisor filter.
- ISE MEng (course) 39 ch: cost > 30k (32,817.75–34,584.05) and not on program page / Engineering "Programs Currently Offered".
- ERSE: on Master's list and calendar but missing from Engineering "Programs Currently Offered" — status UNCONFIRMED.
- Science MSc: Biology/Chem/Biochem need a degree in that subject; CS needs CS degree + 75% CS average + supervisor (thesis/project); CS project suspended from 202810; DS/HCC/course routes suspended; Physics honours physics/eng-physics; Math/Stats BSc in subject + 75%; Earth Sciences thesis under a supervisor. None fit.
- KHS MSc: "Admission is contingent on students securing a supervisor" — fails. MKin: "four-year health sciences bachelor’s degree" + anatomy/physiology + 2 health courses; BME acceptance UNCONFIRMED; 20,419.20–22,185.50; KHS deadline 15 Apr 2027.
- MN, CNPP, CNS: online/RN licence; MN & MSW on FGSR PGWP-ineligible list. MSW needs BSW + 2 yrs SW employment. MISW: alternating even years (next intake 2028, deadline 15 Mar 2028), Saskatoon campus, FNUniv.
