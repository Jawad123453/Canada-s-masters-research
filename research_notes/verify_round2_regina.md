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

## Part 2 — Fees (re-fetched and recomputed)
Sources (HTTP 200): 
- F26 = Fall 2026 FGS schedule "Fall 2026 (202630) SEMESTER as of May 15, 2026 (subject to change)": https://www.uregina.ca/financial-services/assets/pdf/fee-schedules/202630-grad-studies-tuition-schedule-may-15.pdf
- W27 = Winter 2027 FGS schedule "Winter 2027 (202710) SEMESTER as of October 16, 2026 (subject to change)": https://www.uregina.ca/financial-services/assets/202710-grad-studies-tuition-schedule-oct-16.pdf
- S26 = Spring-Summer 2026 FGS schedule "(202620) SEMESTER as of February 2, 2026": https://www.uregina.ca/financial-services/assets/pdf/fee-schedules/202620-grad-studies-tuition-schedule-feb-2.pdf
- SF = Student Fees page ("Information Last Updated: October 19, 2026" for 2027 Winter schedules): https://www.uregina.ca/financial-services/fees.html

| Item | Status | Verbatim / figure |
|---|---|---|
| M.Eng. $597.75/ch | CONFIRMED (F26 and W27) | column "Master of Engineering (Including MCERT) (All Students)", 1 ch = 597.75; 6 ch 3,586.50; 9 ch 5,379.75 |
| Masters Programs $365.50/ch | CONFIRMED (F26, W27) | column "Masters Programs (Including MCERT)", 1 ch = 365.50 |
| International Surcharge $1,487.25/term | CONFIRMED (F26, W27) | same 1,487.25 at every credit load 1-12 ch; GRST maintenance rows also carry 1,487.25 |
| Surcharge in Spring/Summer | CONFIRMED | S26: "International Surcharge" 1,443.75 at every load (2025-26 rate). Calendar C: "All students studying on a valid Study Permit will be charged an International Surcharge each term" |
| Students' fees | CONFIRMED | "*Students' fees will be assessed as $44.60/student plus $5.70/credit hour." |
| SSHW $117.65 | CONFIRMED | column "Student Services, Health & Wellness Fee^^" 117.65; "This fee is mandatory even if the student does not access facilities" |
| Academic Technologies $26.80 | CONFIRMED | "Academic Technologies Fee of $26.80 per semester will be assessed to all students" |
| U-Pass $90 | CONFIRMED | "U-Pass and the $90.00 fee are mandatory, but students can opt-out if they meet the opt-out criteria." (S26 includes U-Pass in its Students' fees column: 1 ch 140.30 = 44.60+5.70+90) |
| Health & Dental $225.85 | CONFIRMED | F26: "graduate students enrolled in 6 or more credit hours ... are assessed an additional $225.85"; "only assessed in the fall semester for health and dental coverage for 12 months beginning September 1"; "The Plan and the $225.85 fee are mandatory." (opt-out only with "comparative alternative" coverage). W27: Winter starters are "not automatically charged"; optional opt-in "$150.58" for Jan–Aug 2027. |
| Schedule per-term intl totals | CONFIRMED | M.Eng. F26 6 ch 5,612.85; 9 ch 7,423.20; W27 6 ch 5,387.00; 9 ch 7,197.35; 3 ch 3,576.65. Masters F26 6 ch 4,219.35; W27 6 ch 3,993.50; 3 ch 2,879.90. Maintenance GRST 995AA intl 3,903.50; 995AB 2,789.90. |

### Recomputed totals (2026-27 rates; Winter rate used as proxy for Spring/Summer — S26 6 ch M.Eng. 5,234.25 ×1.03 = 5,391.28 ≈ W27 5,387.00, so proxy is sound)
Per-term formula: tuition + 44.60 + 5.70×ch + 117.65 + 26.80 + 90.00 + 1,487.25 (+225.85 in Fall if ≥6 ch). Script reproduces every schedule total to the cent.
- M.Eng. 4 terms (F9, W9, [S/S break], F6, W6): 7,423.20 + 7,197.35 + 5,612.85 + 5,387.00 = **$25,620.40** = tuition 30×597.75 17,932.50 + surcharge 4×1,487.25 5,949.00 + Students' fees 4×44.60+30×5.70 349.40 + (117.65+26.80+90)×4 937.80 + H&D 2×225.85 451.70. CONFIRMED.
- M.Eng. 5 terms (F6, W6, S/S6, F6, W6): 2×5,612.85 + 3×5,387.00 = **$27,386.70** = 17,932.50 + 7,436.25 + 394.00 + 1,172.25 + 451.70. CONFIRMED. ≥$27k → fee-increase risk.
- M.Eng. 6 terms (F6, W6, S/S3, F6, W6, S/S3): 2×5,612.85 + 2×5,387.00 + 2×3,576.65 = **$29,153.00** (new figure).
- MKin 5 terms (6 ch × 5): 2×4,219.35 + 3×3,993.50 = **$20,419.20** = 10,965.00 + 7,436.25 + 394.00 + 1,172.25 + 451.70. CONFIRMED.
- MKin 6 terms: 2×4,219.35 + 2×3,993.50 + 2×2,879.90 = **$22,185.50** = 10,965.00 + 8,923.50 + 438.60 + 1,406.70 + 451.70. CONFIRMED. CAVEAT: the prior pattern (…, W3, S/S3) breaks the rule "Three credit hours does not meet the definition of full-time registration unless these credit hours pertain to the last requirements of the program" (C, International Students and Registration) — a compliant 6-term pattern is F6, W6, S/S3, F6, W6, S/S3 (S/S "minimally part-time"), same total $22,185.50.
- +3%/yr projection, Fall 2027 entry, fee years per calendar convention (S/S belongs to the next fee year; F27+W28 ×1.03, S/S28+F28+W29 ×1.0609, S/S29 ×1.0927):
  - M.Eng. 4-term: (7,423.20+7,197.35)×1.03 + (5,612.85+5,387.00)×1.0609 = **$26,728.91** (CONFIRMED ≈ $26,729).
  - M.Eng. 5-term: (5,612.85+5,387.00)×1.03 + (5,387.00+5,612.85+5,387.00)×1.0609 = **$28,714.65** — CORRECTED (prior $28,548 put S/S 2028 in the 2027-28 fee year).
  - M.Eng. 6-term: **$30,702.36** → would EXCEED $30k. M.Eng. must be finished in ≤5 terms.
  - MKin 5-term **$21,408.95**; MKin 6-term **$23,374.48** (CONFIRMED).

### Health coverage
- CONFIRMED, UR International Saskatchewan Health Card page https://www.uregina.ca/ur-international/student-services/health-card.html: "International students who hold a valid study permit are eligible for the Saskatchewan Health Card." and "The Saskatchewan Health Card is a free and valuable personal identification card". No separate compulsory international insurance found; U of R Plan $225.85 is the only compulsory health line.

## Part 3 — Fee increase / 2027-28 rates
- CONFIRMED (SF, "Information on International Tuition Fees for Fall 2026 (202630)"): "Beginning in Fall 2026, tuition for all students will increase by 3.0%." and "As part of the University’s approved 2026–2027 budget, tuition for all students will increase by 3.0%. In addition, the undergraduate international tuition multiplier will increase from 3.0 to 3.5." (multiplier change is undergraduate only; "Currently, the reimbursement initiative applies only to eligible international undergraduate students.")
- 2027-28 rates: NOT PUBLISHED. SF lists only "2027 Winter Fee Schedules" (202710) as newest; grep for 202720/202730/2027-28 = 0 hits. Check: F26 ($597.75) vs S26 2025-26 ($580.25) = +3.0%; surcharge 1,443.75 → 1,487.25 = +3.0%.

## Part 4 — Contacts
| Email | Status | Page | Quote |
|---|---|---|---|
| engg.grad@uregina.ca | CONFIRMED (calendar only; not on Engineering Graduate Students page) | C, ESE and other Engineering sections | "For more information about Graduate programs, contact engg.grad@uregina.ca." |
| grad.studies@uregina.ca | CONFIRMED | H | "If you have further questions, you may e-mail our office at grad.studies@uregina.ca" |
| KHS.GSR-AssocDean@uregina.ca | CONFIRMED | KC | "Interim Associate Dean (Graduate Studies, Research & Special Projects): Cory Kulczycki" mailto:KHS.GSR-AssocDean@uregina.ca |
| Better KHS contact | NOT FOUND | — | MK, KHS graduate-students page and KHS home show no email. Old "MKin Special Case" page (uregina.ca/kinesiology/graduate-program/future-graduate-students/MKin.html) now redirects to https://www.uregina.ca/kinesiology-health-studies/ (no MKin content). KHS.AcademicServices@uregina.ca / kinesiology@uregina.ca appear only in search snippets (not opened) — UNCONFIRMED. Use KHS.GSR-AssocDean@uregina.ca. |

## Part 5 — PGWP-relevant facts (uregina.ca)
- Length: ESE program page https://www.uregina.ca/academics/programs/engineering/masters-phd-electronic-systems-engineering.html Quick Facts "Master of Engineering – Project: 2 years" (CONFIRMED); SSE page same "Master of Engineering – Project: 2 years". MK Quick Facts "Length: 2 years" (CONFIRMED). Calendar: "in full-time study, approximately two years for a Master's degree"; non-thesis time limit "maximum six (6) years from first registration".
- Full-time rule (C, "International Students and Registration", CONFIRMED): "New international graduate students are required to register for a minimum of 6 credit hours in their first term." "Master's students must be registered full-time in the fall and winter terms and minimally part-time in the Spring/Summer term, unless they are a new international graduate student. Three credit hours does not meet the definition of full-time registration unless these credit hours pertain to the last requirements of the program." "Spring/Summer may be a scheduled break for graduate students in Masters". Course load: "maximum course load one can self-register for is 6 credit hours per term; Approval to register for additional credit hours will be reviewed by the academic unit to a maximum of 12" (9-ch terms need unit approval). TR: "full-time enrolment is 6 credit hours" for graduate students.
- On-campus delivery: no explicit "on campus" statement on ESE/SSE/MKin pages; no online option mentioned on any of them (grep "online" = only site-menu links). Indirect: fee schedules assess U-Pass to students "enrolled in at least one on-campus course"; MKin practicums in KHS facilities and community. → PASS (inference; no online version exists), not an explicit quote.
- Co-op/work permit (C): "International students who wish to participate in a Co-operative Education experience must apply for a Work Permit as well as a Study Permit" — relevant to the MKin community practicum question (unresolved; ask KHS / UR International).
- Note: ESE page markets M.Eng. Project as "focusing on growth for practicing engineers" — descriptive only; no work-experience requirement in calendar or eligibility page.

## Filter-verdict changes
- None of the PASS/FAIL verdicts change. Corrections: (1) M.Eng. 5-term projection $28,715 (not $28,548); (2) new: a 6-term M.Eng. would be $29,153 now / ≈$30,702 projected → over $30k, so M.Eng. must finish in ≤5 terms (add to enquiry); (3) MKin 6-term pattern must keep Fall/Winter at 6 ch (3 ch only in S/S or final term) — total unchanged; (4) "or equivalent" is absent on the current MKin page and the current calendar has no MKin admission text — F6 stays UNCONFIRMED; (5) U of R "graduating average" = PGPA, last approved attempt only (TR) — favourable, consistent with WES F*; (6) better KHS contact not found.

## Blocked hosts (final)
- None blocked this run. 404: https://www.uregina.ca/registrar/assets/docs/pdf/calendar/2026-2027.pdf (HTTP 404; not needed). Redirect: old MKin Special Case page → KHS home.
