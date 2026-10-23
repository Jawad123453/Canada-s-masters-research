# Verification — University of Regina M.Eng. (ESE/SSE) and Master of Kinesiology (MKin)

Verification date: 23 Oct 2026. Agent: verification (round 2). Method: fetch.sh re-fetch of each official page/PDF into scratchpad, then grep for verbatim strings. Status codes: CONFIRMED / CORRECTED / NOT FOUND.

## Blocked hosts
(none yet)

## Plan
1. Re-fetch FGSR eligibility, how-to-apply, application-procedures (ELP), English proficiency page, 2026-27 calendar PDF, Engineering grad page, MKin program page, KHS web calendar.
2. Re-fetch fee schedules 202630 / 202710, Student Fees page, health card page; recompute.
3. Fee increase statement, contacts, PGWP facts.

## Sources re-fetched (all HTTP 200 via curl unless noted)
- E = FGSR Eligibility: https://www.uregina.ca/graduate-studies-research/future-students/eligibility-requirements.html
- H = FGSR How to Apply: https://www.uregina.ca/graduate-studies-research/future-students/how-to-apply.html
- AP = Calendar Application Procedures (ELP table): https://www.uregina.ca/graduate-studies-research/graduate-calendar/application-procedures.html
- C = 2026-2027 Graduate Calendar PDF: https://www.uregina.ca/graduate-studies-research/assets/docs/fgsr-docs/2026-2027-graduate-calendar.pdf
- EN = Engineering Graduate Students: https://www.uregina.ca/engineering/graduate-students/Index.html
- MK = MKin program page: https://www.uregina.ca/academics/programs/khs/masters-kinesiology.html
- KC = Web calendar KHS: https://www.uregina.ca/graduate-studies-research/graduate-calendar/all-programs/khs.html
- A9 = KHS Unit Review 2021-22 Appendix 9 (historical proposal): https://uregina.ca/university-leadership/assets/docs/provost-docs/academic-unit-review-docs/2021-22/khs/appendix-9-proposed-course-master-prog.pdf
- TR = Registrar Transcripts (GPA definitions): https://www.uregina.ca/registrar/student-records/transcripts.html
- (404) https://www.uregina.ca/registrar/assets/docs/pdf/calendar/2026-2027.pdf — undergraduate 2026-27 calendar PDF not at that URL (not needed; TR used).

## Part 1 — Admission / supervision / deadlines (verbatim grep results)

| # | Item | Status | Source | Verbatim quote |
|---|---|---|---|---|
| 1 | 70% = WES 2.67 | CONFIRMED | E, "International Students" | "The equivalent score to 70% at the U of R is 2.67 out of 4.00 as per the WES calculator" (also: "minimum admission standard of 70% or 2.67 on the 4 point scale") |
| 2 | 70% four-year average | CONFIRMED | E "Master's Degree"; C p.6 | "A graduating average of at least 70 per cent from a four-year baccalaureate degree (or equivalent)" |
| 3 | Last-two-years fallback | CONFIRMED | E | "marginally lower four-year average may be accepted if their performance in the last two complete years is significantly higher (75 per cent or more)" |
| 4 | WES ICAP mandatory, Engineering | CONFIRMED | E "Engineering and Applied Science"; EN; H | E: "Students with international credentials MUST provide all post-secondary transcripts and degree certificates through the WES ICAP course by course evaluation." Exemption "Effective 202710" only for "Master of Applied Science or PhD programs in Electronic Systems Engineering" (and ISE MASc/PhD 202730) — M.Eng. NOT exempt. H: "Engineering and Applied Science (Master of Science in Electronic Systems Engineering - Thesis is exempted from this requirement)". |
| 5 | WES ICAP mandatory, MKin | CONFIRMED | E "Kinesiology and Health Studies – All Programs" | "International students are required to submit a WES ICAP Course-by-Course evaluation report as part of their graduate application to the MSc, MKin, and PhD programs." |
| 6 | IELTS 6.5 overall / 6.0 each | CONFIRMED | AP table row "FGSR Minimum"; C p.5 | column header "Academic IELTS", row "FGSR Minimum" "6.5 overall, 6.0 each". No Engineering or KHS row (rows: FGSR Minimum, JSGS, Media Studies & Media Production 7.0/7.0, English 7.5/7.5). |
| 7 | IELTS General Training | NOT FOUND (no mention anywhere) | AP, E, C | grep "general training" = 0 hits in AP, E, C. Only "Academic IELTS" named → treat GT as not accepted. E also: "ELP test scores are valid for two years from the test date." E exemption: "university at which English was the primary language of instruction, as indicated on our University of Regina ELP List by Country". |
| 8 | ESE "assigned a project supervisor" | CONFIRMED | C, ESE "Supervision" | "MEng students will normally be assigned a project supervisor just prior to starting their project or during the first semester of the MEng project course." Note wording for ESE is "The MEng degree program is a course-based program of which the project is a required course" ("effectively" is the SSE wording). |
| 9 | SSE "assigned a project supervisor" | CONFIRMED | C, SSE "Supervision" | "The MEng is effectively a course-based program of which the project is a required course. MEng students will normally be assigned a project supervisor..." |
| 10 | "Electronics MENG students do not need to contact professors" | CONFIRMED | EN "Prospective Supervisors" | "Electronics MENG students do not need to contact professors, all applications are reviewed automatically by the Program" (and general: "It is recommended that you make contact with the professors ... You may still apply if you have not made contact.") |
| 11 | ESE qualifying rule | CONFIRMED | C, ESE "Admissions" | "Applicants who lack experience in Engineering design, law, professionalism and ethics, and economics may be admitted as “qualifying students.”" + "MEng applicants from non-engineering backgrounds ... are welcome." SSE: "may be admitted conditionally as qualifying students, and may be asked to complete additional graduate courses ... may also be assigned additional undergraduate courses". |
| 12 | MKin degree requirement | CONFIRMED | MK FAQ "What are the admission requirements?" | "A graduating average of at least 70 per cent from a four-year health sciences bachelor’s degree is required for admission. Additionally, students much have completed classes in human anatomy, human physiology, and two other human health sciences classes." |
| 13 | "or equivalent" on CURRENT MKin page | NOT FOUND (absent) | MK | grep "equivalent" on MK = 0 hits. "or equivalent" exists only in A9 (2021 proposal): "Prerequisite classes (or equivalent): human anatomy, human physiology, and two from the following list: ... biomechanics, physics, ... biochemistry ..." — and FGSR general rule "four-year baccalaureate degree (or equivalent)". KC (current web calendar) has NO MKin admission text — only the credit table (KHS 8** 24, KHS 902 3, KHS 903 3, Total 30). Helpful general rule, C p.6 item 2: "Applicants who fail to meet this requirement but who otherwise meet the criteria may be admitted; however, background deficiencies will be addressed by taking appropriate courses". |
| 14 | MKin "no formal supervisor" | CONFIRMED (historical source only) | A9 "Application procedures" | "The standard application requirements are applicable, with the exception of identifying a supervisor. It is a course-based option, and there is no formal supervisor for this program." Current corroboration: E "Students who are pursuing a course-based program do not need to secure a supervisor as part of the application process."; MK "The Master of Kinesiology is a course-based, practicum-based graduate program". |
| 15 | MKin 2nd practicum | CONFIRMED | MK "Practicum placements" | "For the second practicum, students must identify and secure a supervised setting in the community" ; first practicum "completed within the Faculty of Kinesiology & Health Studies"; KHS 902 "Each 3 credit hours is equal to 240 hours ... Students must complete 6 credit hours". |
| 16 | M.Eng. deadlines | CONFIRMED | H "Engineering"; EN "Deadlines" | H: "For Winter admission: July 31" / "For Fall admission: January 31" / "Late applications will not be accepted". EN: "Fall intake - apply by January 31" / "Winter intake - apply by July 31". |
| 17 | KHS deadlines | CONFIRMED | H "Kinesiology and Health Studies" | "For Fall admission: April 15" / "For Winter admission: August 15" / "The faculty will consider applications outside of these deadlines at the unit's discretion". (Winter MKin intake itself not confirmed; A9 2021: "April 15, 2022 for Fall intake.") |
| 18 | "Late applications will not be accepted" | CONFIRMED (Engineering only) | H | appears only under Engineering. KHS has the opposite discretion clause. |
| 19 | Portal opening | CONFIRMED | H | "Fall admission (September–December): Opens the first week of August (of the previous year)"; Winter "Opens the first week of February (of the previous year)". |
| 20 | Repeated courses / graduating average | CONFIRMED (U of R's own definition; applies to U of R transcripts, no explicit rule for foreign transcripts) | TR "Grade Point Average" | "The undergraduate graduation average is a PGPA calculation." PGPA "is calculated according to UGPA rules"; UGPA: "when a course has been repeated, only the grade in the most recent approved attempt is used." CGPA (all attempts): "based on all U of R courses taken, whether passed or failed, undergraduate and graduate, repeated or not." → U of R's "graduating average" = LAST attempt only (failed attempts later repeated are excluded). Consistent with WES ICAP excluding F* attempts. Graduate calendar C has no definition of "graduating average" (grep: only the 70% sentences). |
| 21 | All programs competitive | CONFIRMED | E | "All graduate programs at the University of Regina are competitive. Students who meet the minimum criteria noted below may not be accepted" |

