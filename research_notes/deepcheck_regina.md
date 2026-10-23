# Deep check — University of Regina: (A) M.Eng. Electronic Systems Engineering (project) and (B) Master of Kinesiology (MKin)

Check date: 23 Oct 2026. Method: full re-fetch of official uregina.ca pages/PDFs and canada.ca (fetch.sh; --browser for canada.ca). Status codes: CONFIRMED / CHANGED / NEW / NOT FOUND. Quotes verbatim unless marked (paraphrase). Contains only university/IRCC rules, quotes, URLs and costs.

## Blocked hosts
(none yet)

## Plan
1. Admission (eligibility, how-to-apply, calendar, ESE/MKin pages)
2. English (ELP page, calendar application procedures, ELP list by country, Duolingo)
3. Application mechanics (fee, documents, references, deadlines, deposit)
4. Program facts
5. Fees (fee page + schedules; any new 2027 schedules)
6. PGWP / DLI (canada.ca)
7. Changes vs earlier notes

## Sources opened in full this run (all HTTP 200 via curl)
- E  Eligibility: https://www.uregina.ca/graduate-studies-research/future-students/eligibility-requirements.html
- H  How to Apply: https://www.uregina.ca/graduate-studies-research/future-students/how-to-apply.html
- AP Calendar Application Procedures (web): https://www.uregina.ca/graduate-studies-research/graduate-calendar/application-procedures.html (ELP table parsed from HTML)
- C  2026-2027 Graduate Calendar PDF (revisions "March 18, 2026 Initial publication", "March 25, 2026", "September 9, 2026 Updated deferral section and suspended programs"): https://www.uregina.ca/graduate-studies-research/assets/docs/fgsr-docs/2026-2027-graduate-calendar.pdf
- HS How to Submit Documents: https://www.uregina.ca/graduate-studies-research/future-students/how-to-submit-documents.html
- ELP ELP List by Country: https://www.uregina.ca/admissions/undergraduate/elp-list-by-country.html
- LOI Letter of Intent template PDF: https://www.uregina.ca/graduate-studies-research/assets/docs/admissions-docs/letter-of-intent.pdf
- EN Engineering Graduate Students: https://www.uregina.ca/engineering/graduate-students/Index.html
- ESE program page: https://www.uregina.ca/academics/programs/engineering/masters-phd-electronic-systems-engineering.html
- MK MKin program page: https://www.uregina.ca/academics/programs/khs/masters-kinesiology.html
- WES partner page for U of R FGSR (linked from E and H): https://www.wes.org/ca/partners/credential-evaluation-requirements-university-regina-faculty-graduate-studies-research-fgsr/

## 1. Admission (both programs unless stated)
| Item | Status | Source | Verbatim |
|---|---|---|---|
| Competitive | CONFIRMED | E "Standards of Admission" | "All graduate programs at the University of Regina are competitive." / "Students who meet the minimum criteria noted below may not be accepted" |
| 70% four-year average | CONFIRMED | E "Master's Degree"; C p.6 item 1 | "A graduating average of at least 70 per cent from a four-year baccalaureate degree (or equivalent)" |
| 70% = 2.67 WES | CONFIRMED | E "International Students" | "minimum admission standard of 70% or 2.67 on the 4 point scale"; "The equivalent score to 70% at the U of R is 2.67 out of 4.00 as per the WES calculator" |
| Rounding | NOT FOUND | E, C, AP | no rounding rule stated anywhere (grep "round" = none relevant) |
| Last-two-years fallback | CONFIRMED | E; C p.6 | "marginally lower four-year average may be accepted if their performance in the last two complete years is significantly higher (75 per cent or more)" |
| Background deficiency route | CONFIRMED (wording: E "must", C "will") | E; C p.6 item 2 | E: "background deficiencies must be addressed by taking appropriate courses either prior to or in parallel with graduate work" |
| Qualifying student definition | CONFIRMED | C p.6 "Classification of Students" | "a student with a 4-year degree who needs additional undergraduate courses in the area of specialization"; "This category will not be used for a student with a poor academic record"; "expected to be completed withing one calendar year"; "Qualifying courses may not be credited towards graduate degree programs" |
| Probationary student | NEW (not in earlier notes) | C p.6 | "A student whose academic qualifications are difficult to assess, or are marginal for admission"; "Probationary courses may be credited toward the degree program." |
| Funding only for fully-qualified | NEW | C p.6 | "Only fully-qualified students are eligible to hold funding provided by FGSR." Fully-qualified = "4-year degree with a minimum grade point average of 70% ... in a field closely related to the baccalaureate" |
| Offer validity / extensions | NEW | C p.5-6; AP | "Offers of admission are valid for one year unless specified otherwise."; "A maximum of two one-year extensions may be provided for admission offers." |
| WES ICAP mandatory - Engineering | CONFIRMED | E "Engineering and Applied Science"; H "WES ICAP"; EN | E: "Students with international credentials MUST provide all post-secondary transcripts and degree certificates through the WES ICAP course by course evaluation." Effective 202710 exemption only "Master of Applied Science or PhD programs in Electronic Systems Engineering" — M.Eng. not exempt. EN: "MUST submit post-secondary transcripts and degree certificates through WES." |
| WES ICAP mandatory - MKin | CONFIRMED | E "Kinesiology and Health Studies — All Programs" | "International students are required to submit a WES ICAP Course-by-Course evaluation report as part of their graduate application to the MSc, MKin, and PhD programs." |
| WES must come DIRECTLY from WES | CONFIRMED / NEW detail | HS; WES page | HS: "You are required to add the University of Regina – Faculty of Graduate Studies and Research as a recipient of your evaluation. The University will receive a digital copy directly from WES." Unofficial-upload route: "This option is not available for programs that require a WES evaluation." WES page: "Select Canada for your evaluation."; "Select WES ICAP Course-by-Course as the evaluation type"; "If you have a prior WES report, you must upgrade to the WES ICAP Course-by-Course evaluation report." |
| Courses in progress → updated WES | CONFIRMED | H | "an updated WES ICAP course-by-course evaluation will be required in order to be eligible for an unconditional acceptance letter" |
| ESE M.Eng. non-engineering / qualifying | CONFIRMED | C p.75-76 ESE "Admissions" | "MEng applicants from non-engineering backgrounds, or from backgrounds lacking course work normally taken by Canadian engineering undergraduates, are welcome. Applicants who lack experience in Engineering design, law, professionalism and ethics, and economics may be admitted as “qualifying students.”" |
| MKin degree + prerequisites | CONFIRMED (unchanged) | MK FAQ | "A graduating average of at least 70 per cent from a four-year health sciences bachelor’s degree is required for admission. Additionally, students much have completed classes in human anatomy, human physiology, and two other human health sciences classes." |
| MKin "or equivalent" | NOT FOUND (current) | MK, C p.115 | no "equivalent" on MK; C p.115 MKin entry = credit table only (24 KHS 8**, KHS 902 3, KHS 903 3, Total 30). Only FGSR general deficiency rule applies. |

## 2. English language proficiency (same FGSR rule for both programs; no Engineering or KHS row)
| Item | Status | Source | Verbatim |
|---|---|---|---|
| Duolingo minimum | CONFIRMED (column "Duolingo", row "FGSR Minimum") | AP table (HTML parsed); C p.5 | "125 overall, 120 each for Speaking, Writing, and Reading, 115 for Listening" (C p.5 identical apart from punctuation). Higher rows: Film Studies & Film Production / English "130 overall, 130 each ... 125 for Listening". Table names only Speaking, Writing, Reading, Listening subscores (no Literacy/Comprehension/Conversation/Production rule found). |
| IELTS | CONFIRMED | AP table, column "Academic IELTS", row "FGSR Minimum" | "6.5 overall, 6.0 each" ; other FGSR-minimum columns: CAEL 70, TOEFL iBT "4 each band", PTE 59, MET 54, U of R ESL "EAP 100/101" |
| IELTS General Training | NOT FOUND (only "Academic IELTS" named) | AP, C, E | — |
| Validity | CONFIRMED | E "Important things to note" | "ELP test scores are valid for two years from the test date." |
| Scores sent directly | CONFIRMED | H "Test Scores"; HS | H: "Official Test Scores (if applicable) must be forwarded to the Faculty of Graduate Studies and Research by the testing centre." / "A valid copy may be included with the application package." HS: "Instruct all testing institutions (English Proficiency, GRE, GMAT, etc.) to release your official results directly"; "Unofficial tests must be verified before they will be accepted." |
| Exemption criteria | CONFIRMED | AP "English Language Proficiency" | "English is considered the official language of instruction if it is listed as the only language on the World Higher Education Database or if is the primary language of instruction, as indicated on our University of Regina ELP List by Country" ; "reserves the right to require an applicant to provide evidence of English language proficiency" |
| Lebanon row (ELP list) | CONFIRMED | ELP table | Row: "Lebanon | No | American University of Beirut Lebanese American University" (column headers: "Education may be used to meet English Language Proficiency Admission Requirement – By Country" / "Institutions that may be used to meet English Language Proficiency Requirement"). Page note: "this list is for information only. Your eligibility for an exemption will be determined after you have submitted your application". |
| WHED entry, Islamic University of Lebanon | NEW | https://whed.net (detail page IAU-000751, reached via whed.net results_institutions.php search; "Updated on 07-07-2022") | "Language(s) Arabic;English;French" → English is NOT the only language → WHED route does not exempt. |
| EMI letter from home university | NOT FOUND | E, AP, C, ELP, H (grep "medium", "letter", "instruction") | No provision for a medium-of-instruction letter anywhere. Calendar PDF p.4 older wording: "International applicants, except those who attended universities where the language of instruction was English, must submit proof of English proficiency" — but the current web rule (AP) defines this only via WHED-only-language or the ELP List. → treat EMI letter as NOT accepted unless FGSR confirms in writing. |
| TA note | CONFIRMED | AP, E | "a minimum score may render an applicant ineligible for graduate teaching assistantships" |

## 3. Application mechanics
| Item | Status | Source | Verbatim |
|---|---|---|---|
| Portal opening | CONFIRMED | H "Application Deadlines" | "Fall admission (September–December): Opens the first week of August (of the previous year)"; "Winter admission (January–April): Opens the first week of February (of the previous year)" → Fall 2027 portal opened first week Aug 2026; Winter 2028 opens first week Feb 2027 |
| Engineering deadlines | CONFIRMED | H "Engineering"; EN "Deadlines" | H: "For Winter admission: July 31" / "For Fall admission: January 31" / "Late applications will not be accepted". EN: "Fall intake - apply by January 31" / "Winter intake - apply by July 31" → Fall 2027 = 31 Jan 2027; Winter 2028 = 31 Jul 2027 |
| KHS deadlines | CONFIRMED | H "Kinesiology and Health Studies" | "For Fall admission: April 15" / "For Winter admission: August 15" / "The faculty will consider applications outside of these deadlines at the unit's discretion, but the above will be used when determining scholarship distribution/eligibility" (scholarship clause NEW vs earlier quote) → Fall 2027 = 15 Apr 2027; Winter 2028 = 15 Aug 2027 (MKin Winter intake still not confirmed) |
| Complete-by-deadline rule | CONFIRMED | H | "Only complete applications with all supporting documents meet deadlines." ; "Incomplete applications will not be forwarded to academic units"; status "Complete, Awaiting Deadline" — "sent for review following the application deadline date" |
| Fee | CONFIRMED | H; F26/W27 "Other Fees" | "a non-refundable fee of $125 (CAD) for ALL domestic and international applicants (subject to change)"; "Applicants can only upload documents once the application fee has been paid."; separate application + fee per program: "a new online application and accompanying fee is required for each program" |
| Transcripts | CONFIRMED | H | "Unofficial transcripts will be accepted through the materials upload tool ... for the review process only. Any offer of admission will be conditional upon receipt of the official transcripts and/or degree certificate." Official = sealed envelope, MyCreds (mycreds@uregina.ca), or "received to graddocs@uregina.ca directly from the previous institution's registrar’s office" |
| Translations / degree certificate | CONFIRMED | H | "Transcripts in languages other than English or French must be accompanied by a certified literal translation. If the transcript does not indicate that the degree was awarded, the degree certificate is to be included." |
| WES route replaces own-document route | NEW | HS | "(This option is not available for programs that require WES evaluation.)" ; unofficial route: "This option is not available for programs that require a WES evaluation." |
| References | CONFIRMED | H; AP item 4 | "At least two official letters of recommendation ... from persons (academics, employers)"; "cannot be a closely associated person or another current graduate student"; referee "institutional email address"; official when "Received from the secure email link sent from the application portal to referee's verifiable institutional email address" (or sealed letterhead, or LOR form to GradDocs@uregina.ca from institutional address); "documents received from ... public domain e-mail addresses (e.g., gmail.com ...) are not acceptable" (AP) |
| Resume + Letter of Intent | CONFIRMED | H; LOI PDF | "A Resume and Letter of Intent outlining one’s purpose in applying to graduate studies. This is a required component of the online application." LOI PDF questions: area of interest/motivation; how past education/experience prepared you; what you hope to achieve; why this U of R program. AI warning (E): "Having someone else, or using generative AI to write your application, is also considered plagiarism." |
| Program-specific extras | CONFIRMED (none beyond WES) | E "Supplementary Material" | Engineering and KHS-MKin: only WES ICAP; KHS extras listed for PhD only. |
| Decision timeline | CONFIRMED / NEW (EN) | H "Application Status"; EN | H: FGSR completeness "one to two weeks"; "All units are given forty-five days to review applications"; Dean final review "three to seven days". EN: "Prospective students will receive a letter from FGSR regarding their application approximately 6-8 weeks after the application deadline" |
| Deposit after offer | CONFIRMED: none for these programs | C p.? JSGS "Tuition Deposit"; TF | Only JSGS: "a non-refundable tuition deposit of $1,000 CAD is required to save your seat" (asterisked JSGS programs). TF: "The Johnson Shoyama Graduate School of Public Policy requires a tuition deposit". No deposit stated for Engineering or KHS. NA page mentions "proof of tuition deposit" (for study permit) via UR Self Service — a voluntary payment proof, not a stated requirement. |
| Engineering procedure | CONFIRMED | EN | "Students apply directly to Faculty of Graduate Studies and Research."; "does not assess a student’s qualifications until they have submitted their complete application"; "Electronics MENG students do not need to contact professors, all applications are reviewed automatically by the Program" |
