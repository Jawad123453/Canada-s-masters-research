# Round 2 — University of Regina follow-up (MKin + full graduate-calendar scan for non-thesis routes)

Research date: 23 Oct 2026. Method: fetch.sh (curl / headless Chromium) on official uregina.ca pages + 2026-2027 Graduate Calendar PDF; quotes verbatim unless marked (paraphrase). Fee components reused from round2_prairies.md (2026-27 FGS schedules: Masters Programs $365.50/ch; International Surcharge $1,487.25/term; Students' fees $44.60 + $5.70/ch; SSHW $117.65; ATF $26.80; U-Pass $90; H&D $225.85 per Fall).

## Blocked hosts
(none yet)

## Plan
1. MKin full verification (program page, calendar, KHS pages, deadlines, contact).
2. Calendar scan: every remaining master's (Arts, Science, Education, MAP/Fine Arts, FNUniv, Campion/Luther, Interdisciplinary) for non-thesis routes.
3. Survivors: per-filter verdicts, cost, intakes, contacts.

## Sources opened in full this round (HTTP 200 unless noted)
- 2026-2027 Graduate Calendar PDF (rev. "September 9, 2026 Updated deferral section and suspended programs"): https://www.uregina.ca/graduate-studies-research/assets/docs/fgsr-docs/2026-2027-graduate-calendar.pdf (whole TOC + Arts, Education, KHS, La Cité, MAP, Science sections read)
- Web calendar program list: https://www.uregina.ca/graduate-studies-research/graduate-calendar/all-programs/index.html
- Web calendar KHS: https://www.uregina.ca/graduate-studies-research/graduate-calendar/all-programs/khs.html
- MKin program page: https://www.uregina.ca/academics/programs/khs/masters-kinesiology.html
- KHS graduate students page: https://www.uregina.ca/kinesiology-health-studies/academic-programs/graduate-students/index.html (links only; no MKin detail)
- KHS Unit Review 2021-22, Appendix 9 "Proposed Course Based Masters Programs" (official uregina.ca PDF, HISTORICAL proposal, not the current calendar): https://uregina.ca/university-leadership/assets/docs/provost-docs/academic-unit-review-docs/2021-22/khs/appendix-9-proposed-course-master-prog.pdf
- FGSR How to Apply (deadlines): https://www.uregina.ca/graduate-studies-research/future-students/how-to-apply.html
- FGSR Eligibility: https://www.uregina.ca/graduate-studies-research/future-students/eligibility-requirements.html
- Calendar Application Procedures (ELP table): https://www.uregina.ca/graduate-studies-research/graduate-calendar/application-procedures.html
- Fee schedules 202630 (Fall 2026) and 202710 (Winter 2027) PDFs (URLs as in round2_prairies.md) — re-opened and re-read this round.

## Blocked hosts (update)
- banner.uregina.ca:17043 (Banner course catalogue / class search, needed for KHS 902/903 course descriptions): `curl: (35) Recv failure: Connection reset by peer` on every request (port 17043 not passed by proxy). KHS 902 description taken from the MKin program page FAQ instead; KHS 903 description NOT found.

## Fee components re-verified (2026-27, FGS schedules, international, "Masters Programs (Including MCERT)" column)
- Fall 2026 (202630) intl totals: 3 ch = $2,879.90; 6 ch = $4,219.35. Winter 2027 (202710): 3 ch = $2,879.90; 6 ch = $3,993.50.
- Components: tuition "365.50" per ch; "International Surcharge" 1,487.25/term; Students' fees "$44.60/student plus $5.70/credit hour"; SSHW 117.65; ATF 26.80; U-Pass 90.00; H&D $225.85 only in Fall and only for "graduate students enrolled in 6 or more credit hours" ("only assessed in the fall semester for health and dental coverage for 12 months").
- Fee-year convention: calendar cover "2026-27 academic year, including the spring/summer term 2026, the fall term 2026 and the winter term 2027" → Spring/Summer belongs to the NEXT fee year after the preceding Winter. No 202720 (S/S 2027) schedule yet → Winter rate used as proxy for S/S terms (no H&D).
- Maintenance if practicum unfinished: GRST 995AB part-time intl $2,789.90/term; 995AA full-time $3,903.50 (Fall 2026).

## 1. Master of Kinesiology (MKin) — course + 2 practicums, 30 ch — FULL VERIFICATION
Structure: calendar p.115 "24.0 KHS 8** (excluding KHS 800 and any KHS directed readings course) / 3.0 KHS 902 / 3.0 KHS 903 / 30.0 Total". Program page: "a course-based, practicum-based graduate program"; "eight core classes and two professional practicum (internship) placements"; Quick Facts "Length: 2 years". KHS 902 (program page FAQ): "Each 3 credit hours is equal to 240 hours within the clinical/applied setting. Students must complete 6 credit hours". Appendix 9 (2021-22 proposal, historical): "Course delivery will include intensive/block and evening offerings in the fall and winter semester, and an intensive offering in spring. Practicum placements may occur in any semester, but most likely spring/summer semesters." Required courses (2021 list): KHS 860, 866, 880, 882, 885, 886, 892, 902.
- NOTE: the 2026-27 calendar (PDF p.115 and web KHS page) prints ONLY the credit table for MKin — no admission paragraph. Admission wording exists only on the program page FAQ (current) and Appendix 9 (2021).

### F1 bar — PASS (thin)
- Program page FAQ "What are the admission requirements?": "A graduating average of at least 70 per cent from a four-year health sciences bachelor's degree is required". 70% = WES 2.67 (eligibility page: "The equivalent score to 70% at the U of R is 2.67 out of 4.00 as per the WES calculator"). Applicant WES 2.68 → PASS by 0.01.
- WES mandatory: eligibility page, KHS "All Programs": "International students are required to submit a WES ICAP Course-by-Course evaluation report as part of their graduate application to the MSc, MKin, and PhD programs." → WES CGPA (F* retakes excluded) is the number used; cuts in applicant's favour.
- Not a 75% program (75% list = "English, History, Mathematics and Statistics and the Master of Public Administration").

### F2 IELTS — PASS (Academic)
- Calendar Application Procedures table, row "FGSR Minimum": "Academic IELTS" "6.5 overall, 6.0 each" (no KHS row). 7.0/7.0 passes. General Training not listed → UNCONFIRMED (assume not accepted).

### F3 cost — PASS (2026-27 schedules; well below $27k)
- Scenario A (5 terms, 6 ch each: F27, W28, S/S28, F28, W29): 2 × 4,219.35 + 3 × 3,993.50 = **$20,419.20**. Component check: 30×365.50 = 10,965.00; surcharge 5×1,487.25 = 7,436.25; Students' fees 5×44.60+30×5.70 = 394.00; SSHW+ATF+U-Pass 5×234.45 = 1,172.25; H&D 2×225.85 = 451.70 → 20,419.20.
- Scenario B (6 terms = the stated "2 years": F6, W6, S/S6, F6, W3, S/S3 with KHS 903 in final summer): 4,219.35+3,993.50+3,993.50+4,219.35+2,879.90+2,879.90 = **$22,185.50**.
- +3%/yr projection respecting fee years (F27+W28 in 2027-28 ×1.03; S/S28+F28+W29 in 2028-29 ×1.0609; S/S29 in 2029-30 ×1.0927): A ≈ **$21,409**; B ≈ **$23,374**. Worst case B + one maintenance term (995AB ≈ $2,790 ×1.09 ≈ $3,050) ≈ $26.4k — still < $27k.
- No separate compulsory international insurance (Sask Health Card; U of R plan counted). Application fee $125 not included.

### F4 supervisor — PASS (no faculty supervisor), with PLACEMENT-SITE caveat
- Appendix 9 (2021, historical): "The standard application requirements are applicable, with the exception of identifying a supervisor. It is a course-based option, and there is no formal supervisor for this program."
- FGSR eligibility "Find a Supervisor": "Students who are pursuing a course-based program do not need to secure a supervisor as part of the application process." (but "non-thesis route (with the exception of course-based) will require a supervisor at some point").
- Practicum arrangement (program page, "Practicum placements"): "The first practicum is completed within the Faculty of Kinesiology & Health Studies" (KHS programs: Enrich Neurorehab, URGold, AHPi, Rock Steady Boxing) → arranged in-house. "For the second practicum, students must identify and secure a supervised setting in the community where they can apply their movement science knowledge." → the STUDENT must find the second placement site and its on-site supervisor (not a faculty research supervisor). Calendar names no practicum coordinator; KHS 903 description not obtainable (Banner blocked).
- Work-authorisation question (not researched on canada.ca here): a mandatory off-campus practicum may require a co-op work permit — ask KHS/UR International.

### F5 delivery — PASS
- In person: lab-based courses ("access to specialized labs and equipment"), practicums in KHS programmes and community; 2021 proposal "intensive/block and evening offerings". No online delivery stated. PGWP: in-class, ≥ 8 months.

### F6 BME background — UNCONFIRMED (main risk)
- Program page: "four-year health sciences bachelor's degree"; "Additionally, students much [sic] have completed classes in human anatomy, human physiology, and two other human health sciences classes." No "or equivalent" on the current page for the degree.
- Appendix 9 (2021): "A four-year health sciences undergraduate degree with a minimum average of 70%"; "Prerequisite classes (or equivalent): human anatomy, human physiology, and two from the following list: motor control, biomechanics, physics, exercise psychology, sport psychology, health psychology, nutrition, biochemistry, microbiology, aging, philosophy, pathology, physical rehabilitation" → "or equivalent" applies to the prerequisite classes; the list includes physics, biomechanics, biochemistry, which a BME transcript typically has (CHECK the IUL transcript for anatomy + physiology).
- FGSR general: "four-year baccalaureate degree (or equivalent)". Whether BME counts as "health sciences" is not defined anywhere → ask KHS. No honours, no work experience required.

### Intake / deadlines / length / contact
- KHS deadlines (how-to-apply): "For Fall admission: April 15"; "For Winter admission: August 15"; "The faculty will consider applications outside of these deadlines at the unit's discretion". Fall 2027 → 15 Apr 2027 (portal opens first week of Aug 2026); Winter 2028 → 15 Aug 2027 (UNCONFIRMED whether MKin admits in Winter: Appendix 9 gives only "April 15, 2022 for Fall intake" and a Fall-start cohort sequence). For study-permit timing apply well before 15 Apr.
- Length "2 years" (program page); 5-6 terms.
- Contacts: KHS Interim Associate Dean (Graduate Studies, Research & Special Projects) Cory Kulczycki, mailto "KHS.GSR-AssocDean@uregina.ca" (web calendar KHS page); FGSR grad.studies@uregina.ca (how-to-apply).
- Application: Appendix 9 (2021) said select "Kinesiology and Health Studies – MKin Practicum Special Case" — check current portal label.

### Open questions (KHS.GSR-AssocDean@uregina.ca)
1. Is a 4-year(5-yr) Biomedical Engineering degree accepted as a "health sciences" degree? Which IUL courses would count as anatomy, physiology and the two other health-science classes?
2. Is the WES ICAP CGPA 2.68 accepted against 70% / 2.67?
3. Intakes: Fall only, or also Winter? Cohort size?
4. Second practicum: what help does KHS give to find a community site? Can international students do it in Regina without a co-op work permit?
5. Typical term pattern (5 vs 6 terms; is Spring/Summer registration required?) and description of KHS 903.

## 2. Calendar scan — every remaining U of R master's (2026-27 calendar TOC + web program list + program pages)
Additional pages opened in full this round: web calendar La Cité https://www.uregina.ca/graduate-studies-research/graduate-calendar/all-programs/la-cite.html; La Cité MA page https://www.uregina.ca/academics/programs/la-cite-universitaire-francophone/en/ma-phd-french-francophone-intercultural-studies.html; Religious Studies https://www.uregina.ca/academics/programs/arts/masters-religious-studies.html; Ed Psych https://www.uregina.ca/academics/programs/education/masters-educational-psychology.html; AEHRD https://www.uregina.ca/academics/programs/education/masters-adult-education-human-resource-development.html; MIEd https://www.uregina.ca/academics/programs/education/masters-indigenous-education.html; MILEd https://www.uregina.ca/academics/programs/education/masters-indigenous-language-education.html; U of R programs index https://www.uregina.ca/academics/programs/index.html.
Blocked: lacite.uregina.ca — curl "(60) SSL certificate problem: unable to get local issuer certificate"; Chromium "net::ERR_CERT_AUTHORITY_INVALID" (issuer "YR2"). Used the uregina.ca La Cité pages instead.

Federated colleges: Campion and Luther award no master's of their own (none in the web program list); FNUniv contributes only MIEd/MILEd (Education) and MISW (Social Work).

| Program | Route(s) | Verdict | Quoted reason (source) |
|---|---|---|---|
| Economics MA | special case only | DROP F4 | Web program list: under "Special Case Programs*" ; Appendix D (calendar p.47-48): Special Case master's needs "A description of the thesis topic" and "A list of supervisor(s) and committee members" |
| Anthropology MA | special case | DROP F4 | calendar p.49 "The Master's program is available on a special case basis." + Appendix D supervisor list |
| Philosophy MA | special case, thesis | DROP F4 | p.57-58 "An approved program of study must be in place (including ... thesis topic and supervision) at the time of admission." |
| Political Science MA | thesis (special case) | DROP F4 | p.58 "There is no regular program in Political Science"; "18.0 PSCI 901" |
| Women's & Gender Studies | special case | DROP F4 | p.64 "There is no regular program in Women and Gender Studies." |
| Linguistics MA | special case thesis | DROP F4/F6 | p.57 "for students who have completed a B.A. Honours degree in linguistics, or equivalent"; "15 hours of thesis research" |
| Religious Studies MA | thesis only | DROP (no course/project route) | p.61 "15.0 Thesis research". (Note for coordinator: "Students will be assigned to a specific faculty member who will act as their supervisor" — assigned, but thesis route.) |
| Sociology MA | thesis only | DROP F6 | p.62 "if they have a BA Honours degree or equivalent in Sociology"; "18.0 SOC 901" |
| Psychology MSc Clinical / EAP | thesis only | DROP | TOC: only "(thesis)" routes; Clinical deadline "December 1 (Fall admission only)" |
| Geography & Environmental Studies | — | DROP | How-to-apply: "Geography (admission to this program has been postponed until further notice)"; not in web program list |
| Social and Political Thought MA | — | DROP | How-to-apply: "(admission to this program has been postponed until further notice)"; web list "Suspended Programs" |
| Indigenous Studies (FNUniv) | — | none exists | no Indigenous Studies master's in calendar or web program list |
| Interdisciplinary / Special Case master's (FGSR) | thesis | DROP F4 | Appendix D: "The thesis forms the critical component"; must list "supervisor(s) and committee members" |
| M.Ed. AEHRD (project/course), Ed Psych (course, practicum 1 & 2), MIEd, MILEd (project/course), MÉd EAL | course/project/practicum | DROP F6 (faculty rule; previous agent settled course routes — re-confirmed) | Calendar p.64: "a four-year degree applicable to the program (normally a B.Ed., B.H.R.D., or B.A.Ed., or equivalent)". Ed Psych page: "normally a B.Ed., B.A.Ed., or equivalent", "Length: 4 years", "blended (hybrid) and fully online course options". MIEd/MILEd pages: "At least two years of teaching or other relevant professional experience is preferred". Ed Psych practicum also needs a "Professional Associate approved by the Dean of FGSR" (p.66). Education project route needs "a Faculty Project supervisor" (p.66). Ed Psych "Project option is no longer available". |
| MA French & Francophone Intercultural Studies (La Cité, course: 8 courses + FRN 803 internship) | course + unpaid internship | DROP F6 (unless applicant has advanced French AND a degree La Cité accepts as equivalent) | Web calendar: "open to students who have an Honours B.A. degree in French ... or equivalent qualifications"; "may be accepted on the basis of having completed a university degree in French or an equivalent degree and may also be required to obtain level B2 at the ... DELF". (PDF p.115 wording differs: "a university degree in French or having obtained level B2 at the ... DELF".) Otherwise attractive: "offered on site", Masters rate, no English test ("with the exception of applications to French language programs in La Cité"), full-time route F/W/S-S(FRN 803 6 ch)/F/W ≈ $20.4k (2026-27). Contact michael.akinpelu@uregina.ca. |
| MMus Performance/Composition/Conducting (project) | project (recitals/portfolio) | DROP F6 | p.123 "will ordinarily hold a music degree comparable to the degree Bachelor of Music"; audition / four compositions required |
| MA Musicology / Music Theory | thesis | DROP F6 | p.124 "must hold a music degree comparable to the degree Bachelor of Music or Bachelor of Arts (Theory)" |
| MFA Film Production, MFA Visual Arts, MFA Media & Artistic Research | research and exhibition | DROP F6 | Eligibility page: Film Production "Applicants must upload a portfolio"; Visual Arts "A portfolio is required to apply for the MFA" |
| MA Film Studies; MA Media & Artistic Research | thesis | DROP F4 | TOC "(thesis)"; Film Studies "describing the intended focus of the thesis"; IDS "indicates the availability of supervision" |
| MSc Biology / Chemistry / Biochemistry / Earth Sciences / Physics | thesis only | DROP | TOC lists only "(thesis)"; Biology p.135 "We strongly recommend arranging for a supervisor prior to applying" |
| MSc KHS | thesis | DROP F4 | p.114 "Admission is contingent on students securing a supervisor for their program." |
| Theatre | special case | DROP F4 | web list "Special Case Programs*: MAP - Theatre" |

## 3. Survivors / summary (University of Regina follow-up, 23 Oct 2026)
| Program | F1 | F2 | F3 (2026-27; +3% proj.) | F4 | F5 | F6 | Overall |
|---|---|---|---|---|---|---|---|
| Master of Kinesiology (MKin), 30 ch, course + 2 practicums | PASS thin (70% = WES 2.67; WES ICAP mandatory; applicant 2.68) | PASS (Academic 6.5/6.0) | PASS $20,419 (5 terms) – $22,186 (6 terms); proj. ≈ $21.4k – $23.4k | PASS — no faculty supervisor ("there is no formal supervisor", 2021 proposal); caveat: student must "identify and secure" 2nd practicum site | PASS (in person) | UNCONFIRMED — "four-year health sciences bachelor's degree" + anatomy, physiology, 2 other health-science classes | **Only Regina survivor; conditional on KHS accepting BME** |
No other U of R master's at the $365.50/ch rate has a course/project/practicum route open to a BME graduate.
