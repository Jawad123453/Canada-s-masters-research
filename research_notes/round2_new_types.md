# Round 2 — new institution types (polytechnics, Waterloo affiliates, theological schools, AUArts)

Agent started 23 Oct 2026. Scope: public DLIs with Grad Program = Yes not checked in earlier rounds.
Filters per 00_agent_brief.md. Cost-first screen; drop on first clear failure with one quoted reason.

## Blocked hosts
(none yet)

## Plan
1. Polytechnics/colleges: BCIT, Olds, Sask Polytech, Seneca, Sheridan, NSCC, Michener
2. Waterloo affiliates: Conrad Grebel (MPACS), St. Paul's (MDP), St. Jerome's
3. Theological: Lutheran Theological Seminary, Horizon, Emmanuel & St Chad, St Andrew's (Saskatoon), Atlantic School of Theology, Victoria/Emmanuel College (Toronto)
4. Alberta University of the Arts

## Findings

### BCIT – all four master's FAIL cost (cheapest $46,993)
- Master's offered to internationals (from BCIT tuition estimator data, https://www.bcit.ca/admission/tuition-fees/estimator/ , backend https://www.bcit.ca/wp-json/bcit/costs/v1/r/intl/<code>/burnaby/ read 23 Oct 2026, year shown by fees page "Costs included in 2026-2027 full-time studies tuition & fees"):
  - Building Science MEng (m120meng): Term 1-3 each "$19,201.87"; "Full Program" total "$57,605.61" (tuition $55,919.79 + SA $1,286.04 + ancillary $399.78). FAIL.
  - Smart Grid Systems and Technologies MEng (m500meng): full program "$46,992.96". FAIL.
  - Applied Computing MSc (m600msc): full program "$48,944.98". FAIL.
  - Ecological Restoration MSc (m410msc): full program "$54,438.16". FAIL.
  - Building Engineering/Building Science MASc (m220masc): thesis ("comprehensive research thesis"); FAIL F4 regardless.
- Note (not needed): MEng Building Science page https://www.bcit.ca/programs/building-science-master-of-engineering-full-time-part-time-m120meng/ (Entrance requirements) has an attractive bar: "engineering field or architecture with a GPA of 2.8 out of 4.0 (70%)", "last two years of full-time study"; Path 1 "course option"; "Delivery: in person." Cost alone kills it. Also intl differential: "2026/27 7% increase", "2027/28 up to 7% increase".
- Host note: plain curl to bcit.ca returns a bot challenge ("We need to confirm you are not a robot"); headless Chromium works.

### Olds College – no master's degree found
- https://www.oldscollege.ca/programs/index.html (full program list): highest credentials are "Bachelor of Applied Science Degree - Agribusiness" and "Bachelor of Digital Agriculture Degree"; only "Master" hits are "Master Spinner Certificate" / "Master Weaver Certificate" (continuing-ed fibre arts). DROP (no master's).

### Saskatchewan Polytechnic – only master's is online Nurse Practitioner (U of Regina degree) – FAIL F5/F6
- https://uregina.ca/academics/programs/nursing/master-nurse-practitioner.html (section "Collaborative Nurse Practitioner Program (CNPP)"): "an online graduate level program offered through a joint partnership between the Saskatchewan Polytechnic and the University of Regina"; "offered online asynchronously". Degree is "Master of Nursing – Nurse Practitioner degree from the University of Regina"; leads to RN(NP) licensure (nursing licence background implied; not opened further). DROP (online >50%, nursing-only).
- Sask Polytech program index https://saskpolytech.ca/programs-and-courses/programs/ shows no other master's (paraphrase).

### Seneca Polytechnic – own master's: MAI (already FAIL cost in round2_ontario.md) + proposed Master of Psychotherapy (pending approval; no fees published)
- https://senecapolytechnic.ca/programs/bycredential/masters.html ("Pursue your Master's Degree at Seneca Polytechnic"): lists only "Master of Artificial Intelligence Design & Development" as Seneca's own; rest are partner pathways (Niagara University etc., US/other degrees).
- https://www.senecapolytechnic.ca/programs/fulltime/master-of-psychotherapy.html : "(Pending Approval)"; "currently pending ministry approval. If approved, the start date ... planned for September 2027"; Delivery "Flexible"; "4 Semesters (2 Years)"; "attend classes in person or online". No cost or admission page (MPST/costs.html 404). Seneca's comparable MAI is "$10,000" per semester international, so 4 semesters ~ $40,000 (inference, not MPST data) -> very likely FAIL cost; also flexible/online delivery is a PGWP risk; clinical psychotherapy (CRPO) track. DROP (UNCONFIRMED cost, likely fail); could be re-checked if Seneca publishes fees.

### Sheridan College – Master of Animation, Games and Immersive Experiences (MAGIE) – FAIL F6
- https://www.sheridancollege.ca/programs/master-of-animation-games-immersive-experiences (Admission requirements): "undergraduate degree in the fields of animation, VFX, game design and development, interactive, mobile, experiential design, digital communications, film, TV, computer science or computer engineering"; "Applicants are required to submit a portfolio." BME not in list + portfolio. DROP. (Bar would be "Minimum GPA of 70% within the last two years"; hybrid option "remaining courses ... will be online".)

### Nova Scotia Community College – no master's
- https://www.nscc.ca/programs-and-courses/credentials/index.asp ("Credentials"): "We offer many levels of certificate and diploma programs"; highest listed credential is "Graduate Certificates" (not degrees). No master's. DROP.
- Host note: https://www.nscc.ca/programs-and-courses/programs/index.asp returned HTTP 403 ("Access to www.nscc.ca was denied ... HTTP ERROR 403") to curl and Chromium; other nscc.ca pages load fine.

### Michener Institute – Cardiovascular Perfusion Master of Science – FAIL cost + bar + F6
- https://michener.ca/programs-courses/cardiovascular-perfusion-program/ (Tuition table, International column): Tuition "$132,938.61", total "$139,963.81" (program). FAIL F3.
- Same page (Admission requirements): "minimum CGPA of 3.0 on the OMSAS Scale"; "Minimum required CGPA is 75%"; prerequisite courses "Gross Human Anatomy", "Gross Human Physiology", Chemistry. Delivery "Hybrid". DROP.
- Michener catalogue (https://michener.ca/programs-courses?sf_paged=1..16): only other "Graduate"-tagged items are short leadership/management courses, not degrees.

### Conrad Grebel – Master of Peace and Conflict Studies (MPACS, UWaterloo degree) – FAIL cost
- https://uwaterloo.ca/master-peace-conflict-studies/fees-and-financial-aid ("Term fees - Fall 2026"): International full-time "$11,490.00" tuition + "$1,014.11" incidental per term. 16-month program (4 terms, per search snippet "16 months (full-time)", not opened) -> 4 x 12,504.11 = $50,016. Even 3 terms = $37,512. FAIL. (Bar per snippet "minimum average of at least 75% in the final 20 courses" – also fails F1; snippet not opened.)

### St. Paul's University College – Master of Development Practice (MDP, UWaterloo degree) – FAIL cost
- https://uwaterloo.ca/finance/masters-and-phd-program-tuition-fall-2026-international-0 (row "Master of Development Practice (MDP)"): "$14,354.00" tuition + "$1,047.87" per term. One term alone ~ $15,402; program is multi-term (16 months per aggregators) -> far > $30k. FAIL.

### St. Jerome's University – Master of Catholic Thought (MCT, UWaterloo degree) – FAIL F1/F4/F5
- https://uwaterloo.ca/st-jeromes/academics/master-catholic-thought : "Online synchronous and asynchronous"; "complete a 75-100 page Master's Thesis"; "minimum overall average of 75%". Fails bar, supervisor/thesis and delivery. (It is cheap – per-course fees – but irrelevant.) DROP.
- Conclusion for Waterloo affiliates: all degrees are UWaterloo graduate degrees on UW fee schedules (international ~$11.5k-$14.4k per term) and UW's 75% bar.

### Atlantic School of Theology (Halifax) – MA (Theology and Religion) FAIL F1; MDiv FAIL cost
- Fees: https://www.astheology.ns.ca/programsadmissions/tuitionadministrativefees/ ("Tuition Fees for 2026-2027"): "Tuition—One-Credit Course—Undergraduate and Graduate International Students (1 credit) $1899*"; "*The International Tuition Waiver bursary reduces tuition by $400, so tuition is currently $1499 per credit." Misc fee "$30" per credit; SIS "$150" per term.
- MDiv: https://www.astheology.ns.ca/programsadmissions/graduatestudies/master-divinity.html : "requires 30 single semester credits"; bar "a minimum of a 70% or 'B' grade average" (would PASS F1 at 70.51%). Cost: 30 x (1,499 + 30) = $45,870 even with bursary (30 x 1,929 = $57,870 without) -> FAIL F3. Also only "a minimum of 12 credits on campus in person" required (online-heavy risk). DROP.
- MA (Theology and Religion): https://www.astheology.ns.ca/programsadmissions/graduatestudies/ma-theology-religion.html : "You have maintained a minimum 'B+' average" -> FAIL F1. (Course-only first-degree stream = 18 credits -> 18 x 1,529 = $27,522 + SIS – would have been near the cap; moot.)
- Graduate Certificate in Theological Studies (10 credits) – not a master's; bar "at least 70% or a 'B' grade". Not a degree.
- Contact: astinfo@astheology.ns.ca

### Saskatoon Theological Union (STU) schools – shared course timetable is synchronous ONLINE -> F5 FAIL for LTS / St Andrew's / ESC degree courses
- STU "Course Offerings 2026-2027" PDF, linked from https://lutherantheological.ca/programs/course-offerings ("Course Offerings 2026-2027" -> https://lutherantheological.ca/all-files/7-policies?download=247:course-offerings-2026-2027 ): every Fall 2026 and Winter 2027 degree course lists "Synchronous Online" (23 entries), e.g. "FND103 Biblical Literature ... Synchronous Online", "CAP390 MTS Capstone ... Synchronous Online". Only exceptions: "AIP331 ... (onsite Saskatoon)" 2 days, and LTS formation intensives "on-site intensives" (one "Onsite in Winnipeg, MB"). An international student cannot assemble a >50% in-person master's from this. 

### College of Emmanuel & St. Chad (Saskatoon) – MTS: cheap and open bar, but FAIL F5 (online delivery)
- Programs: https://emmanuelstchad.ca/programs : MTS "a two-year program"; "must have a bachelor's degree or its equivalent"; graduate "with an overall average of not less than 60%" (no admission % stated). MDiv = 90 credits.
- MTS structure PDF https://emmanuelstchad.ca/wp-content/uploads/2026/08/MTS-Program.pdf : "Total MTS Program Credits: 60" (20 x 3-credit courses).
- Fees PDF https://emmanuelstchad.ca/wp-content/uploads/2026/09/Fees_v3_31aug2026-1.pdf (dated 31 Aug 2026): MTS "Full Course (per 3 credit course) $ 1,400.00" (no international differential shown); "Students outside Canada (Study permit) $ 200.00" application; "Program Fee (per term ... max of $100/academic year)"; "Student Union (TSS) per academic year $ 50.00"; "Academic Equivalency Assessment ... $ 250.00"; "Graduation $ 150.00".
  - Cost arithmetic: 20 x 1,400 = 28,000 + program fee 2 x 100 = 200 + TSS 2 x 50 = 100 + equivalency 250 + graduation 150 = $28,700 (+ application 200 = $28,900). Health insurance: none charged by ESC; Saskatchewan provincial coverage for study-permit holders not verified (UNCONFIRMED). Fee-increase risk (>= 27k).
- Delivery: ESC's own Fall 2026 timetable https://emmanuelstchad.ca/wp-content/uploads/2026/09/ESC-Course-Timetable-Fall-2026_v3_18sep2026.pdf : all three degree courses "Format: Online (Zoom)". Academic Policies PDF https://emmanuelstchad.ca/wp-content/uploads/2026/10/Policies_v2.pdf says "No more than half the total credits for any degree ... may be earned through a combination of on-line or cluster courses" – contradicts the actual timetable; combined with STU's all-online offerings, an in-person MTS for a study-permit student is not available. F5 FAIL (and IELTS policy not published: UNCONFIRMED). DROP. Contact: registrar@emmanuelstchad.ca (from Policies PDF).
