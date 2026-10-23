# Round 2 – Ontario follow-up (Laurier deep check, Trent course-based, Algoma Lebanon row)
Started 23 Oct 2026. Evidence from full official pages via fetch.sh unless labelled otherwise.

## Blocked hosts / fetch errors
- academic-calendar.wlu.ca (all paths incl. /section.php, /archives.php, /pdfs/2025-2026-graduate-calendar.pdf): HTTP 200 but body only "Academic Calendar - Maintenance" / "temporarily unavailable while maintenance is being performed" (curl AND headless Chromium --browser), 23 Oct 2026.
- web.wlu.ca/archives/calendars/graduate/ (archived calendars): HTTP 200 but "This site has been temporarily restricted to on-campus access only."
- web.archive.org (Wayback, CDX API): "Blocked by egress policy" / curl (35) "Connection reset by peer" (agent proxy ws_closed_mid_exchange). archive.org/wayback/available returned no snapshots for the calendar.
- uhip.ca/uhip-services/plan-costs/: HTTP 404 (rates found instead at uhip.ca/important-update-on-the-university-health-insurance-plan-uhip/).

## Summary (23 Oct 2026)
- Laurier: grade scale quoted ("B 73-76", "B- 70-72"). Every master's bar is "B" (=73%+) or higher; none at B-/<=72%. FAIL filter 1 for all (borderline: applicant's last-two-years ~73% sits on the B floor). Cheapest structural fit if an enquiry is wanted: Geography MA/MES Environmental Data Analytics, 3 terms, ~27,712 at 2026-27 rates. No Lebanon/grad equivalency table exists on wlu.ca; calendar down.
- Trent: all course-based/MRP master's "Minimum B+ (77%)" (Sustainability A- 80%). DROP.
- Algoma Lebanon row verbatim "75% or 12/20" / "80% or 14/20"; internally inconsistent; /100 basis fails.

## Plan
1. Laurier: retry academic-calendar.wlu.ca (curl, --browser, archived/PDF calendars); grad admission regs, grade scale (B / B- %), international equivalency / Lebanon row, honours, years counted, repeated courses.
2. Laurier course-based / MRP master's list: tuition per term 2026-27, terms, fees, UHIP, delivery, supervisor, prerequisites, IELTS, program % bar.
3. Fully verify any Laurier program with bar <=72% and total < 30k.
4. Trent course-based master's: tuition, bar, supervisor, IELTS, delivery.
5. Algoma grad credential page: quote Lebanon row verbatim, scale.


## 1. Wilfrid Laurier University (Waterloo / Brantford) – institution-level facts
All pages below fetched in full with fetch.sh (HTTP 200) on 23 Oct 2026, except the calendar (blocked, see top).

### 1a. Grade scale (Laurier's own) – QUOTED
- https://students.wlu.ca/academics/support-and-advising/gpa-calculator/ , section "Laurier's Grade Scale": "Laurier uses a 12-point grade scale". Table: "A+ 90-100 12 | A 85-89 11 | A- 80-84 10 | B+ 77-79 9 | **B 73-76 8 | B- 70-72 7** | C+ 67-69 6 | C 63-66 5 | C- 60-62 4 | D+ 57-59 3 | D 53-56 2 | D- 50-52 1 | F 0-49 0".
- Program pages confirm the same bands for graduate admission:
  - Community Music MA: "at least a B standing (73-76%) in the final two years".
  - Music Therapy MMT: "at least a B (73-76 percent) standing in the final academic year"; "at least a B- (70-72 percent) in each course".
  - Public Safety MPS: "B average (75%) in your last five full credits".
- **So a Laurier "B" bar = 73% minimum (Laurier scale). No Laurier master's found with a B- (70-72%) overall bar.**
- Applicant: overall 70.51% = Laurier B- (FAIL vs B). Last two years ~73% (retakes replacing failures) = bottom of Laurier B, exactly at the line; ~66-67% (all attempts) = C+ (FAIL). Borderline at best; outside the brief's 65-72% band.

### 1b. General graduate admission (FGPS)
- https://www.wlu.ca/academics/faculties/graduate-and-postdoctoral-studies/admissions/apply/index.html , "International Applicants > General Admission Requirements > Master's programs": "Four-year (honours) bachelor's degree, or equivalent, from an approved university." / "Minimum of second-class honours, or B standing, or equivalent."
- Honours: "(honours) ... or equivalent" – honours in brackets, "or equivalent" allowed (paraphrase: not a strict honours-only rule). Lebanese 5-year BME presumably "equivalent" – UNCONFIRMED (no Laurier grad equivalency table).
- Which years count: not stated at FGPS level; set per program (last 2 years / final year / last 10 half-credits – see table below).
- Repeated-course rule: the only Laurier statement found is for Laurier's OWN undergraduate GPA (GPA calculator page): "If you have failed a course and repeated it ... use only the grade achieved in the second attempt". No graduate-admission rule for external transcripts found (calendar down). UNCONFIRMED.
- Lebanon / international equivalency: NONE found. FGPS International Students page (https://www.wlu.ca/academics/faculties/graduate-and-postdoctoral-studies/international-students/index.html) and Upload Documents page contain no country table; transcripts must "Include the grading scale/key/legend". Laurier evaluates itself (no WES requirement seen). UNCONFIRMED.
- Graduate Calendar "University Graduate Regulations" (admission, grading, qualifying year): NOT READABLE (maintenance, see top).

### 1c. English (FGPS)
- https://www.wlu.ca/academics/faculties/graduate-and-postdoctoral-studies/admissions/assets/resources/english-proficiency.html : "(IELTS, IELTS Online): academic – minimum score of 6.5 with no band score below 6.0". **Academic only.** Tests "taken within the last 24 months". Applicant 7.0/7.0 PASS if Academic.

### 1d. Fees 2026-27 (per term, international, "Entering All Years")
- https://students.wlu.ca/finances/tuition-and-fees/fees-breakdown/tuition-fees.html , "Full-Time Graduate Visa Students (per term unless otherwise stated)" ("2026/27 tuition rates ... effective Fall 2026. All fees are per term"):
  - "MA/MEd/MES/MAP/MKin/MMus $7,861.00"; "MSc $8,236.00"; "MMT $9,646.00"; "Master of Applied Computing $9,692.00"; "Master of Science User Experience Design $10,500.00"; "MSW $10,127.00"; "MIPP $10,241.00"; "Master of Management Analytics $18,798.00"; "MFin Waterloo* $18,893.00"; "MBA Waterloo $19,570.00".
- Incidental fees 2026-27, https://students.wlu.ca/finances/tuition-and-fees/fees-breakdown/incidental-fees.html , "All Graduate Student Incidental Fees" (full-time): CFS 21.08 (fall only); Copyright 3.31/term; Dental 252.43 (12-month, fall start); GSA 57.92/term; GSA Tech 10.72/term; Health Plan 486.74 (12-month, fall start); Media 9.01/term; ISOW 8.00/term; Comprehensive Student Services 461.40/term; LSPIRG 3.63/term; Sustainability 7.36/term; OneCard 31.00 + 15.24 (new students). Waterloo campus: U-Pass 131.14/term; Athletics 99.03/term. (Health/dental are opt-outable with proof of coverage – "unless you already have health and dental coverage".)
  - Per-term recurring (Waterloo): 3.31+57.92+10.72+9.01+8.00+461.40+3.63+7.36+131.14+99.03 = **791.52**; one-off: 21.08 + 31.00 + 15.24 = 67.32; health+dental (12-month) 739.17.
- UHIP: Laurier UHIP page (https://students.wlu.ca/wellness-and-recreation/health-and-wellness/insurance-and-health-plans/uhip.html): degree-seeking international students are "automatically enrolled ... for the 12-month period running from Sept. 1 to Aug. 31". Rate not on Laurier site; uhip.ca "Rates for September 1, 2026 to August 31, 2027": September 2026 single **$948**.
- Model 3-term MA (Waterloo, Fall 2026 rates): tuition 3 x 7,861 = 23,583; incidentals 3 x 791.52 + 67.32 = 2,441.88; GSA health+dental 739.17; UHIP 948 → **27,712.05** (25,972.88 without the opt-outable GSA health/dental is NOT safe to assume for internationals). Under 30k, fee-increase risk (>=27k). 2027-28 rates not published.

### 1e. Laurier master's – screened (bar quoted from each program page, https://www.wlu.ca/programs/<faculty>/graduate/<program>/index.html, "Admission Requirements", 23 Oct 2026)
| Program | Bar (quote) | Format / length | Tuition/term | Verdict |
|---|---|---|---|---|
| Geography MA (MRP / Environmental Data Analytics coursework) | "A minimum B average." (=73%+); "in geography or related program" | EDA: "two terms of course work (six courses) and one term of research placement"; "Full-time: Three terms (12 months)"; Waterloo | 7,861 | FAIL bar (B=73-76); degree fit (geography/related) UNCONFIRMED |
| MES Geography (EDA/MRP) | "A minimum B average." | "one-year (12 month) degree through ... Environmental Data Analytics" ; Waterloo | 7,861 | FAIL bar |
| Applied Politics MAP | "A minimum B average in your last two years" + non-poli-sci needs "minimum of two courses in political science" | "eight months or 12 months (full time)"; coursework option | 7,861 | FAIL bar; FAIL degree prereq (BME lacks poli-sci courses) |
| SJCE MA (Brantford) | "A minimum B average in your last year"; "A background in the concepts of social and environmental justice" | "12-month full-time"; coursework / MRP / creative MRP | 7,861 | FAIL bar (B); deg. fit doubtful |
| MABE (Business Economics) | "A minimum B average"; needs "Two courses in intermediate microeconomic theory and two ... macroeconomic" | 12 months | (MA rate per fee table) | FAIL bar; FAIL prereqs |
| MIPP | "A minimum B average."; micro/macro/stats/poli-sci prerequisites | 3+ terms (incl. options) | 10,241 | FAIL bar; 3 x 10,241 = 30,723 > 30k FAIL cost |
| Community Music MA | "B standing (73-76%) in the final two years"; "Foundation of musical training ... is required" | "three consecutive terms or nine months" | 7,861 | FAIL bar (73%); FAIL degree fit |
| Music Therapy MMT | "B (73-76 percent) ... final academic year"; music/music therapy degree | – | 9,646 | FAIL bar; FAIL degree |
| MEd | "A minimum \"B\" standing in your final two years of study." Full-time only "one or two spaces" (Interdisciplinary, Waterloo) | F/T: 3 terms (3+3+2 courses); otherwise part-time/online | 7,861 | FAIL bar (B=73%) |
| Public Safety MPS | "B average (75%)" | "Fully online." | – | FAIL bar; FAIL delivery |
| Criminology MA | "A minimum B+ average in your final year" | – | 7,861 | FAIL bar |
| History MA | "minimum B+ average in the last 10 full credits"; history or related | – | 7,861 | FAIL bar |
| English MA | "cumulative average of B+ in English courses" | – | 7,861 | FAIL bar/degree |
| Religion, Culture & Global Justice MA | "B average in your fourth year ... and a B+ in your major" | – | 7,861 | FAIL bar |
| Communication Studies MA | "Minimum B+ in your undergraduate major ... B+ overall for your last two years" | – | 7,861 | FAIL bar |
| CAST MA | "Minimum B+ in your final year" | – | 7,861 | FAIL bar |
| Master of Applied Computing | "final year grade point average of at least B+" | – | 9,692 | FAIL bar |
| MSc UX Design | "minimum B+ average in the last two years ... B average overall" | – | 10,500 | FAIL bar |
| MSc Management / Management Analytics / MFin / MBA | "B+" (Mgmt, MMA, MFin); MBA "B standing ... final year" | – | 18.8k-19.6k | FAIL cost (and bar) |
| MSW | "B average in your last 10 half credit courses" | – | 10,127 | FAIL bar; social-work prerequisites |
| Psychology MA/MSc (incl. Community Psychology) | "A minimum B average in your last two years" | thesis "supervised by one of our faculty members", "two years (six consecutive terms)" | 7,861 / 8,236 | FAIL bar, FAIL supervisor (thesis), FAIL cost (6 terms) |
| Kinesiology MSc, Chemistry MSc, Integrative Biology MSc, Geography MSc, Health Sciences MSc, Mathematics MSc | B (Kin, Chem, IB, Geog) / "A- average" (Health Sci) / B+ (Math) | thesis, "two years (six consecutive terms)" | 8,236 | FAIL bar; FAIL supervisor/cost (6 terms x 8,236 = 49.4k) |

**Laurier verdict: no program clears filter 1.** Lowest overall bar is "B" = Laurier 73-76% (one point above the brief's 72% ceiling). The only Laurier B- (70-72%) mention is a per-course prerequisite in MMT. Task 1c (full verification of a <=72% program) – no candidate.
- If the coordinator wants a borderline enquiry: Geography MA / MES "Environmental Data Analytics" (3 terms, Waterloo, coursework + placement, no supervisor search, "B average" with no year window stated, deadline "March 30 (international applicants)" for Fall) is the cheapest structurally-fitting option (~27.7k at 2026-27 rates). Contact: gradadmissions@wlu.ca. Open Qs: does a Lebanese 70.51% / ~73% last-two-years meet "B average"; is BME a "related program"; which years are averaged; are failed-then-passed attempts counted.

## 2. Trent University (Peterborough / Durham-GTA) – course-based / MRP master's: ALL FAIL filter 1
Program list: https://www.trentu.ca/graduatestudies/programs (fetched in full). Each program page https://www.trentu.ca/graduatestudies/program/<slug> fetched in full (HTTP 200), 23 Oct 2026; bar quoted from its "Admission Requirements".
| Program | Format (quote) | Bar (quote) | Verdict |
|---|---|---|---|
| Master of Management (M.Mgt.) – Management / Strategic Change / Health Care Mgmt streams | "Course-based: 16 months" | "Minimum B+ (77%) or equivalent in the last two years of full-time study, or last ten full academic credits" | FAIL bar; FAIL cost: node/61 "International Students ... Per Term Tuition (2026-27) ... Full-Time $12,795", "sixteen months (equal to four terms)" -> 51,180 |
| Master of Arts Management (M.AMgt.) | "Course-based: 12 months" (co-op) | "Minimum B+ (77%) ..." | FAIL bar; cost: node/148 international "Full-Time $10,150" per term x3 = 30,450 > 30k |
| Master of Instrumental Chemical Analysis (M.ICA) | "Course-based: 12 months" + 4-month co-op | "Minimum B+ (77%) ..." | FAIL bar |
| M.Sc. Forensic Science | "Course-based: 12 months" / MRP 12 months | "Minimum B+ (77%) ..." | FAIL bar |
| AMOD M.Sc. (Data Science & Analytics 12 mo; Big Data / Financial Analytics 16 mo) | "Course-based streams" | "Minimum B+ (77%) ..." | FAIL bar |
| M.Ed. (course-only / MRP / thesis) | "Course-only: 12 months" | "Minimum B+ (77%) ..." | FAIL bar |
| M.A. English (Public Texts) – internship / MRP / research-creation | "Internship: 12 months"; "Major Research Paper: 12 months" | "Minimum B+ (77%) ..." | FAIL bar |
| M.A. History (MRP) | "Major Research Paper: 12 months" | "Minimum B+ (77%) ..." | FAIL bar |
| M.A. Cultural Studies (MRP) | "Major Research Paper: 12 months" | "Minimum B+ (77%) ..." | FAIL bar |
| M.A. Canadian & Indigenous Studies (MRP) | "Major Research Paper: 12 months" | "Minimum B+ (77%) ..." | FAIL bar |
| M.A. Sustainability Studies (MRP / co-op / thesis) | "Major Research Paper: 12 months"; "Co-op: 16 months" | "Minimum A- (80%) or equivalent in the last two years" | FAIL bar |
| M.Sc.N. Nursing | "Major Research Project: 24 months"; "flexible online study" | "Minimum B (73%)" | FAIL bar, delivery (online), degree (nursing) |
| Thesis-only: Anthropology, Computer Science, Environmental & Life Sciences, Materials Science, Psychology M.Sc., Interdisciplinary Aging Studies, M.BEMA/M.Sc. | "Thesis: 24 months" | "Minimum B+ (77%) ..." (Psych also "A- (80%) in Psychology courses") | FAIL bar + supervisor |
| Psychotherapy (M.Psyt.) | – | "Minimum B+ (77%) ..." | FAIL bar |
- Cost reference (would have passed): research/MRP programs, https://www.trentu.ca/graduatestudies/node/17 ("Research and Thesis Based Graduate Programs ... 2026-27"; covers English (Public Texts), History, Cultural Studies, Canadian & Indigenous Studies, etc.): "International Master's Students" per term "$8,113" tuition + "$237" supplementary; UHIP "$948.00"; "TGSA Health & Dental Plan: $619.50 (opt out available)". 3 terms = 3 x 8,350 + 948 + 619.50 = 26,617.50.
- No Trent Lebanon row searched (moot: every master's bar is >= 77% except online Nursing at 73%). Trent general admission page URL https://www.trentu.ca/graduatestudies/future-students/admission-requirements returned "Page not found".
- **Trent verdict: DROP.** Single reason: "Minimum B+ (77%) or equivalent in the last two years of full-time study" (applicant ~73% best case).

## 3. Algoma University – graduate credential equivalencies, LEBANON row (re-opened)
- https://algomau.ca/students/international-students/international-credential-equivalencies-grad/ (fetched in full, HTTP 200, 23 Oct 2026). Live URL unchanged.
- Intro: "Algoma University requires a minimum Ontario equivalent grade of B or B+, as required by the specific program ... with the required academic standing achieved in the final two years of full-time study." / "provided as a general guideline only, as grading scales and degree structures may vary by institution."
- **Lebanon row, verbatim:** "Lebanon / Minimum GPA Required: 75% or 12/20 / B Plus GPA: 80% or 14/20 / Bachelor's Degree Equivalent: Bachelor's or Licence / English Language Test Requirement: Required".
- Scale: the row gives BOTH a /100 figure (75% / 80%) and a /20 figure (12/20 / 14/20); the two are not equivalent (12/20 = 60% linearly). Algoma's other /20 rows pair differently, e.g. "Burundi: 70% or 14/20", "Cameroon: 13/20 or 65%", "Chad: 13/20", "Côte d'Ivoire: 12/20", "Iran: 14/20 (B)" — i.e. Algoma elsewhere treats 14/20 ≈ 70%, which makes the Lebanon "75% or 12/20" internally inconsistent (likely a typo in one of the two figures).
- Applicant impact: on the /100 basis 70.51% overall (~73% last two years) < 75% → FAIL; on the /20 basis 14.1/20 clears both "12/20" (B) and "14/20" (B Plus) → PASS. IUL issues /100 averages (per brief), so the 75% figure is the one Algoma would most likely apply. Verdict unchanged: FAIL / UNCONFIRMED pending a written answer from admissions@algomau.ca / schoolofgraduatestudies@algomau.ca asking which figure applies to a /100 Lebanese transcript.
- Also English test "Required" for Lebanon (no exemption).
