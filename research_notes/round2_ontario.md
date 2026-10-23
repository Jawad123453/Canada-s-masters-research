# Round 2 – Ontario verification (Guelph CDE, Algoma, Hearst, UOF, Laurier & others)
Started 23 Oct 2026. Evidence from full official pages via fetch.sh unless labelled otherwise.

## Blocked hosts / fetch errors
- www.rmc-cmr.ca and extlin9.rmc-cmr.ca: "HTTP 403 Forbidden" (curl and headless Chromium), 23 Oct 2026.
- academic-calendar.wlu.ca: HTTP 200, but the page body was only "Academic Calendar - Maintenance".
- graduatestudies.uoguelph.ca: reachable this round (HTTP 200). The prior-round ENOTFOUND is resolved.

## Summary (23 Oct 2026)
- Guelph CDE:
  - Admission bar: UNCONFIRMED. The live Lebanon row has no threshold, and the "80% or 15/20" PDF is a 2005 document. The general rule is 70% (B-) = 3.0/4.0 over the last two years.
  - IELTS: PASS (Academic 6.5).
  - Cost: $24,141 is ANNUAL tuition, not full-program. 3 semesters = 27,304.56 (fee-increase risk); 4 semesters ≥ 37,237 (FAIL).
  - Supervisor, delivery and degree fit: PASS.
- Algoma MCS: cost 28,224.53 at 2026-27 rates (PASS, fee-increase risk). But the Lebanon row is "75% or 12/20" (FAIL on the /100 scale), and the CS-related degree and prerequisites are UNCONFIRMED.
- Hearst: DÉSP only (not a master's; psychology degree and French required). UOF: no master's. Laurier: "B standing" (FAIL). MLUC, OCAD and Seneca MAI: FAIL on cost. RMC: blocked (403).

## Plan
1. Guelph Master of Capacity Development & Extension: Lebanon credential row, admission wording, IELTS, cost (tuition, compulsory fees, UHIP, semesters), supervisor, delivery, deadline.
2. Algoma MCS (12-month) + other Algoma master's.
3. Université de Hearst master's.
4. Université de l'Ontario français master's (check).
5. Laurier, Sudbury federated, WLS, Western affiliates, RMC – cost-first screen.
6. Qualifying / pre-master's year options.


## 1. University of Guelph – Master of Capacity Development & Extension (MSc CDE, coursework option)
All pages below fetched in full with curl (HTTP 200) on 23 Oct 2026. graduatestudies.uoguelph.ca was reachable this round (it was blocked last round).

### Filter 1 – admission bar: FAIL-leaning / UNCONFIRMED (needs enquiry)
- Live International Credentials Guideline, https://graduatestudies.uoguelph.ca/future/international/credential , section "L > Lebanon":
  - "Master's Minimum Admission Requirement / Bachelor`s, Licence requiring 4 years of study"
  - "Typical Degree Credits: Not available"
  - "Effective 2025-10-01"
  - **The live row has NO percentage or /20 threshold.** It only gives the degree equivalency and a link to Scholaro's Lebanon grading scale.
- The old "80% or 15/20" PDF is https://family.uoguelph.ca/sites/default/files/International%20Credential%20Evaluation%20Guidelines.pdf
  - Lebanon row: "Bachelor's degree, Licence ... 100% scale or 20 point scale / 80% or 15/20".
  - Its footer is "H:\EVALUATION STUFF\International Credential guidelines.doc 5/26/05", so it is a **2005** document. The server's Last-Modified is 2020.
  - It refers to "Graduate Program Services (GPS)", an old office name. It has been superseded by the live guideline above. Do not rely on it.
- General bar, https://graduatestudies.uoguelph.ca/future/apply/requirements , "Master's Admission":
  - "70% (B-) average is required in the last two years of full-time equivalent study."
  - Minimum degree: "an undergraduate degree/ baccalaureate, in an honours program or the equivalent".
  - International degrees: "Typically, the last 4 full-time semesters (or 6 full-time semesters for full-year education systems)".
  - Grade Conversion: "Guelph's minimum grade requirement equivalent of 70% (B -) which is 3.0 on the US 4.0 scale."
  - "Admission averages are calculated using the recently completed required credits, moving backward per credit".
  - WES: "Transcript evaluation services are not accepted for credentials assessments. However, World Education Services (WES) evaluation reports are accepted as certified copies of official transcripts." So Guelph evaluates itself; WES is accepted only as a transcript copy.
- Program page, https://www.uoguelph.ca/programs/master-capacity-development-extension/ :
  - "Admission Average B- (70% - 72%)"
  - "A four year honours degree or equivalent, with an average standing of at least second class honours (B-) in the last four semesters of full-time study or two years of professional work in a related field."
- Graduate calendar, CDE, https://calendar.uoguelph.ca/graduate-calendar/graduate-programs/capacity-development-extension/ : "A four-year honours undergraduate degree with a least B- in the last two years".
- Repeated/failed course rule: not stated on any Guelph page read (requirements page, upgrading page, calendar admission regulations). UNCONFIRMED.
- Applicant impact:
  - The Lebanese % basis is about 73% in the last two years if retakes replace failures (passes), or about 66-67% if all attempts count (fails).
  - The US-scale basis is 2.90 < 3.0 (fails).
  - The outcome depends on how Guelph converts Lebanese /100 grades and handles retakes. UNCONFIRMED: ask the program.
- Upgrading route: https://graduatestudies.uoguelph.ca/future/apply/upgrading , "Hold an Honours degree below the minimum average": "complete three senior level (3000 or 4000) undergraduate courses (1.5 course credits) in the same semester and maintain a minimum average of 70%" (taken as a non-degree student).

### Filter 2 – IELTS: PASS
- https://graduatestudies.uoguelph.ca/future/international/english lists "International English Language Testing System (Academic) (IELTS)" and computer-delivered IELTS, minimum overall "6.5". No IELTS sub-band minimum is stated; sub-band minimums are stated only for PTE and TOEFL.
- The calendar admission regulations agree: "IELTS - minimum overall score of 6.5".
- **Academic only** (the chart names "IELTS (Academic)"). If the applicant's test is General Training, it fails.

### Filter 3 – cost: FAIL for 4 semesters; borderline for 3 semesters. Corrects the prior round.
- Grad cost page, https://graduatestudies.uoguelph.ca/future/cost , "Graduate Tuition":
  - "Annual tuition includes tuition for three consecutive semesters: Fall, Winter, and Summer."
  - CDE row: "Master of Capacity Development and Extension | $7,133 | $21,946 | $24,141", with columns domestic 2026-27 | international 2026-27 | international 2027-28.
  - The note "**Program is billed per credit. The listed fee reflects cost of total required credits for program" applies only to rows marked ** (MBA, MSCM, MEM, etc.). **The CDE row has no asterisk.** So $24,141 is ANNUAL (3-semester) tuition, NOT full-program tuition. The prior round's "full-program" reading was wrong.
  - The same page says that if there is a discrepancy, the Student Financial Services figures prevail.
- Registrar, https://www.uoguelph.ca/registrar/finances-fees/tuition-fees/guelph-grad , "Fall 2026, Winter 2027 & Summer 2027":
  - CDE is not listed separately, so it falls under "Regular Masters (MA, MSC, MASC, GDIP - unless listed separately below) | $2,377.53 | $6,837.54" per semester (6,837.54 x 3 = 20,512.62).
  - The two pages disagree for 2026-27: Registrar 20,512.62 vs cost page 21,946. Use the higher figure. UNCONFIRMED which rate applies to CDE.
- Compulsory fees, full-time, 2026-27 (Registrar, same page): "Total Compulsory Fees $937.21 / $642.80 / $635.55" (Fall / Winter / Summer). Annual sum 2,215.56.
- UHIP: "(UHIP, international students only, charged annually in the fall semester) $948.00".
- Length:
  - Calendar: "a full-time course-based, professional development option, which requires three to four semesters of study."
  - Program page: "Duration Full Time: 24 months".
  - Coursework = 4.50 credits (9 courses x 0.50) plus a 12-16 week internship.
- Arithmetic (Fall 2027 entry, 2027-28 international rate $24,141/yr = $8,047/semester; compulsory fees and UHIP at 2026-27 rates, since 2027-28 is not published):
  - **3 semesters (F27-W28-S28):** 24,141 + 2,215.56 + 948 = **27,304.56**. Under 30k but at least 27k, so fee-increase risk. The 2026-27 to 2027-28 increase is +10.0% (24,141 / 21,946).
  - **4 semesters (+Fall 2028):** 27,304.56 + 8,047 (2027-28 rate, likely about 8,850 at +10%) + 937.21 + 948 (second UHIP) = **37,236.77** at minimum. **FAIL.**
  - **24 months (6 semesters):** about 2 x 27.3k = about 55k. FAIL.
- Verdict:
  - 3-semester completion: PASS (borderline).
  - 4-semester completion: FAIL.
  - Realistic length with the internship: UNCONFIRMED. Ask whether the international course-based student can finish in 3 semesters (F/W/S).

### Filter 4 – supervisor: PASS
- Program page: "you are not required to secure a faculty advisor to supervise your program."

### Filter 5 – delivery: PASS
- Program page: "Delivery On-campus".

### Filter 6 – degree fit: PASS-leaning
- Calendar: "open to qualified graduates from a wide variety of disciplines including ... health ... or related disciplines".
- "honours degree or equivalent". The ICG maps Lebanon to "Bachelor`s, Licence requiring 4 years of study", so a 5-year BME should meet "equivalent" (paraphrase).
- Work experience is "preferred", not required.

### Intake / deadline / contact
- Program page header:
  - International "Fall (September): April 15"; "Winter (January): October 25, 2026"; "Summer (May): January 31".
- The same page lower down:
  - "Applications are ongoing for international students"
  - "Note: Only Fall semester entry is available for this program."
- The two statements conflict, so confirm. Fall 2027 is presumably 15 April 2027.
- Contact: cde@uoguelph.ca (Lorena Barker, Graduate Program Assistant); program options: lewest@uoguelph.ca.
- Open questions:
  1. How is a Lebanese /100 average converted? Is 70.51% overall / ~73% last two years acceptable, and how are failed-then-passed courses counted?
  2. Is the 2027-28 international tuition $24,141 per year (3 semesters)? How many semesters do international course-based students normally pay (3 or 4)?
  3. Is Winter entry possible, and what is the Fall 2027 deadline?
  4. Is IELTS Academic required, or is General Training accepted?

## 2. Algoma University – Master of Computer Science (12-month, course-based) and other Algoma master's
Pages fetched in full on 23 Oct 2026 (HTTP 200). Email addresses on algomau.ca are Cloudflare-obfuscated; I decoded them from the page HTML (data-cfemail).
- Program page: https://algomau.ca/academics/graduate-programs/master-of-computer-science/ (identical to .../master-of-computer-science-12mth/).

### Filter 1 – admission bar: FAIL (Lebanon row)
- MCS page, "2. Check out our Admission Requirements (Beginning with the Fall 2026 intake)":
  - "a four-year computer science or closely related undergraduate degree from an accredited university, with a minimum 70% (B) average over four years, OR a minimum 75% (B+) average over the last two years".
  - "having two or more backlogs in computer science core courses will significantly decrease an applicant's chances".
- The same page's "6. Apply" checklist is stricter: "Attained a minimum 75% (B+) average over the last two years of full-time undergraduate study". This conflicts with the requirements section above.
- Graduate credential page, https://algomau.ca/students/international-students/international-credential-equivalencies-grad/ :
  - "requires a minimum Ontario equivalent grade of B or B+ ... with the required academic standing achieved in the final two years of full-time study."
  - Lebanon row: "Minimum GPA Required: 75% or 12/20"; "B Plus GPA: 80% or 14/20"; "Bachelor's Degree Equivalent: Bachelor's or Licence".
- Applicant impact:
  - On the /100 scale the applicant's 70.51% overall (~73% last two years) is below the 75% Lebanon "B". **FAIL.**
  - The /20 figures are internally inconsistent: 12/20 is far below 75%. On a /20 basis the applicant's 14.1/20 would clear even "B Plus 14/20". IUL transcripts are on /100, so the 75% applies. Worth a one-line query, but treat as FAIL.
- WES: listed as optional supplementary material: "WES (World Education Services) evaluation for institutions attended outside of North America." Algoma evaluates itself.

### Filter 2 – IELTS: PASS
- MCS page: "IELTS Academic: 6.5 overall, no band lower than 6.0".
- Academic only. Scores must be "taken within 24 months of the application submission date".

### Filter 3 – cost: PASS (borderline; fee-increase risk)
- Tuition page, https://algomau.ca/students/tuition-scholarships-financial-aid/graduate-programs-tuition-awards-and-funding/ : "The fees listed below are for the 2026/27 academic year".
  - MCS International Full-Time: "2026 Fall & 2027 Winter per semester $8,500.00* $485.51** $8,985.51".
  - The prior Spring 2026 rate was $8,049.30.
- Insurance:
  - "UHIP ... The premium for a single student is $316 per semester beginning in 26F."
  - "VIP: All full-time students require VIP Insurance coverage at the rate of $320 per year."
  - "The SSM bus pass is an additional $82.80 per semester".
- Length: "can be completed in one year (three consecutive semesters)".
- Arithmetic at 2026-27 rates:
  - 3 x 8,985.51 = 26,956.53
  - + UHIP 3 x 316 = 948
  - + VIP 320
  - = **28,224.53**
  - + SSM bus pass 3 x 82.80 = 248.40, giving 28,472.93 if at Sault Ste. Marie.
- 2027-28 rates are not published. At the latest observed increase (+5.6%, from 8,049.30 to 8,500), Fall 2027 entry is about 3 x (8,976 + 485.51) + 948 + 320 ≈ 29,652. **Fee-increase risk: very close to 30k.**

### Filter 4 – supervisor: PASS
- "This is a course-based master's program". The computing project is an elective. No supervisor is needed for admission.

### Filter 5 – delivery: PASS-leaning
- In-person: tuition footnotes refer to "full-time online" students only for other contexts.
- The MCS page does not state the campus. Faculty are listed at "Sault Ste. Marie Campus" (Dean Xu) and "Brampton Campus" (Graduate Officer Sultana and others). Campus is UNCONFIRMED; ask.

### Filter 6 – degree fit: UNCONFIRMED, leaning FAIL
- Requirements: "computer science or closely related" degree, plus "any three of the following foundational (prerequisite) courses" (list includes Introductory Programming, Microprocessor and Assembly Language Programming, Introductory Statistics, Computer Organization, ...).
- The checklist demands six: "Introductory Programming, Introductory Statistics, Computer Organization, Data Structures II, Computer Networks, Theory of Computing".
- Whether BME counts as "closely related" is not defined on the page.

### Intake / deadline / contact
- The page shows only "WINTER 2027 intake: Application opens on June 29, 2026"; international applications "accepted until December 1, 2026"; documents by December 15, 2026.
- Fall 2027 / Winter 2028 dates are not yet posted (UNCONFIRMED). The Winter 2027 pattern suggests Winter 2028 runs about June to 1 Dec 2027.
- "Email pre-screening is not available".
- Contacts: schoolofgraduatestudies@algomau.ca (general); admissions@algomau.ca (admission).

### Other Algoma master's (screened, all dropped)
- **MCS Data Science & AI**: "16 MONTH"; tuition page shows $8,985.51 per semester international. 4 x 8,985.51 = 35,942 > 30k. FAIL cost.
- **Master of Global Business and Economy**: "minimum 75% (B+) average over the last two years" (FAIL bar). "two-years (4 semesters)": 8,500 / 10,000 per semester → over 30k (FAIL cost). Winter 2027 "Applications are now closed".
- **MSc Business Analytics**: "16 months, 4 semesters"; $10,635.51 per semester international → 42.5k. FAIL cost.
- **Master of Psychotherapy**: "Total Program Cost ... $40,925.06". FAIL cost.
- **MSc Biology and MSc CS (thesis)**: thesis-based, supervisor needed. FAIL filter 4. Same 75% Lebanon bar.
- **MSW**: "designed for graduates of a Bachelor of Social Work degree"; the tuition table shows domestic only. FAIL filter 6.

Open questions for Algoma:
1. Does the Lebanon "75% or 12/20" row apply to the /100 transcript? Is 70.51% overall eligible under the MCS "70% (B) over four years" clause?
2. Is BME "closely related", and which prerequisites are mandatory?
3. Which campus offers MCS for Fall 2027 / Winter 2028, and what are the deadlines?
4. What are the 2027-28 tuition rates?

## 3. Université de Hearst – no master's. DROP.
- Programs page, https://uhearst.ca/programmes/ (fetched in full): the only graduate entry is "Diplôme d'études supérieures en psychothérapie (DÉSP)". It is a graduate diploma, not a maîtrise.
- DÉSP page, https://uhearst.ca/programmes/diplome-detudes-superieures-en-psychotherapie-desp/ :
  - "programme de deuxième cycle ... à temps plein de 45 crédits pouvant être complété à l'intérieur d'une période de 12 mois"
  - Admission: "Être titulaire d'un grade de premier cycle en psychologie (4 ans) ou dans un domaine apparenté" (FAIL filter 6 for BME)
  - Bar: "moyenne pondérée cumulative de 6 (70 %)"
  - Language: "Démontrer une maîtrise du français et une connaissance fonctionnelle de l'anglais"
  - Cost: "663 $ par tranche de 3 crédits pour l'année scolaire 2026-2027 ... 9 945 $". No international rate is shown on the page.
- Verdict: not a master's; requires a psychology degree and fluent French. DROP.

## 4. Université de l'Ontario français – no master's. DROP.
- Programs page, https://uontario.ca/english/programs (fetched in full) lists only Bachelor's degrees (Business Administration, Education, Digital Cultures, Economics and Social Innovation, Urban Environments, Human Plurality, Psychology, ...). It mentions only "Pursue your studies at the master's level in psychology" as a career path.
- This is consistent with the DLI "Grad Program No". DROP.

## 5. Other Ontario institutions (cost-first screen)

### Wilfrid Laurier University – FAIL filter 1 (plain "B")
- https://www.wlu.ca/academics/faculties/graduate-and-postdoctoral-studies/admissions/apply/index.html (fetched in full), "Master's programs":
  - "Four-year (honours) bachelor's degree, or equivalent"
  - "Minimum of second-class honours, or B standing, or equivalent."
  - No percentage is given, so under the brief's rule a plain "B" FAILS. No Lebanon graduate row was found.
- Cost would otherwise be low. https://students.wlu.ca/finances/tuition-and-fees/fees-breakdown/tuition-fees.html , "Full-Time Graduate Visa Students (per term ...) Entering All Years":
  - "MA/MEd/MES/MAP/MKin/MMus $7,861.00"; "MSc $8,236.00"; "Master of Applied Computing $9,692.00".
  - A 3-term MA would be 3 x 7,861 = 23,583 tuition before incidentals and UHIP.
- Laurier Criminology MA (one-year coursework): "minimum B+ (or better than 77%)" (search result summary of the calendar; not opened). FAIL either way.
- Laurier graduate calendar (academic-calendar.wlu.ca) returned "Academic Calendar - Maintenance" on 23 Oct 2026, so the general regulations and the Qualifying Year rules could not be read.
- Verdict: DROP. One possible enquiry: does Laurier treat a Lebanese 70.51% (~73% last two years) as "B standing"? Laurier's own B band is not quoted here (UNCONFIRMED).

### Waterloo Lutheran Seminary / Martin Luther University College (Laurier) – FAIL cost
- Same tuition page, "Full-Time Martin Luther University College Visa Students": "MA in Theology / MDiv / MA-MDiv ... General Graduate Studies $10,464.00" per term.
- Even 3 terms = 31,392 > 30k. DROP.

### OCAD University – FAIL cost
- https://gradadmissions.ocadu.ca/afford/tuition-fees : "International Tuition: $61,000 - $86,000*" ("based on the 2026-2027 tuition rates for the total duration of the programs"). DROP.

### Royal Military College of Canada – BLOCKED host; likely closed to internationals
- https://www.rmc-cmr.ca/en/registrars-office/graduate-studies-programmes-offered and /en/graduate-studies/students returned **HTTP 403 Forbidden** to both curl and headless Chromium. extlin9.rmc-cmr.ca also returned 403.
- Search snippets only (not opened):
  - "open to ... civilians who are either Canadian citizens or permanent residents"
  - The students page reportedly says "exceptional international students are also encouraged".
- UNCONFIRMED. Treat as not open. DROP.

### Seneca Polytechnic – Master of AI Design & Development – FAIL cost (bar would pass)
- https://www.senecapolytechnic.ca/programs/fulltime/MAI/costs.html : international "Semester 1 $10,000 ... Semester 4 $10,000". 4 x 10,000 = 40,000. FAIL.
- https://www.senecapolytechnic.ca/programs/fulltime/MAI/admission-requirements.html :
  - "in computer science, data science, mathematics, computer or software engineering or a related field"
  - "A minimum average of B (70%) ... overall or within the final two years"
  - Requires a WES/ICAS course-by-course evaluation.
- MAI.html: "Hybrid"; "4 Semesters (16 Months)". DROP on cost.

### Huntington / Thorneloe / University of Sudbury; King's / Huron / Brescia (Western affiliates) – DROP via DLI
- None of these appears in the DLI extract's "Grad Program = Yes" rows for Ontario. King's University College is listed with Grad Program "No".
- Any master's at the Western affiliates is a Western degree, and Western is eliminated. The Sudbury federated colleges' degrees run through Laurentian (eliminated) or are undergraduate.
- Not opened further (cost-first screen).

### Not checked (Waterloo-affiliated colleges: Conrad Grebel, St. Jerome's, St. Paul's; Victoria College U of T; Michener; Sheridan; Canadian Forces College)
- Their graduate degrees are awarded through Waterloo / U of T (both eliminated), are restricted to the military (CFC), or none was found (Sheridan).

## 6. Qualifying / pre-master's routes
- **Guelph upgrading** (https://graduatestudies.uoguelph.ca/future/apply/upgrading): an honours-degree holder below 70% does "three senior level (3000 or 4000) undergraduate courses (1.5 course credits) in the same semester and maintain a minimum average of 70%" as a non-degree student. These courses do not count toward the master's.
- Cost, from https://www.uoguelph.ca/registrar/finances-fees/tuition-fees/guelph-undergrad , "Tuition Per 1.00 Credit for International Students", Arts & Science Cohort 2026: "$8,910.44". So 1.5 x 8,910.44 = 13,365.66 for one semester.
  - 1.5 credits is part-time ("up to 1.75 credits ... per credit"), which raises a study-permit question.
  - The full-time flat rate is "$22,276.10" per semester.
- With the CDE afterwards, the total is about 40k or more. Not a cheap route.
- **Laurier Qualifying Year**: calendar under maintenance; not verifiable.
- **Algoma**: no pathway/qualifying route to the MCS found on the graduate pages read. "there is no policy or procedure for transferring into any graduate program".
