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
