# Shared brief for research agents (round 2, 23 Oct 2026)

## Applicant profile
- Bachelor's in Biomedical Engineering (BME), Islamic University of Lebanon (IUL), conferred Feb 2026. 5-year program; WES lists it as "Bachelor's degree (four years)", not honours.
- Official general average 70.51% (about 14.1/20). On the applicant's own transcript letter scale (70-74 = C) this is a C.
- WES ICAP cumulative GPA 2.68/4.0 over 212 credits (WES excludes failed attempts later passed, F*). Last two years (2024-25, 2025-26) ~2.90/4.0; ~73% if retakes replace failures; ~66-67% if every attempt counts.
- IELTS 7.0 overall, 7.0 in each band (L/R/W/S). Version not stated: record which versions each school accepts (Academic / General Training).
- Target intake Fall 2027; also Winter/Summer 2028. Must be PGWP-eligible.

## Six filters (a program counts only if it clears ALL)
1. Admission bar a flat PERCENTAGE ~65-72%, or "B-" (=2.67). Plain "B" / 3.0 / GPA 3.0+ FAILS. "B" or "second class" with no % = UNCONFIRMED. Find the school's own LEBANON grade-conversion row and quote it (it may be stricter, e.g. 15/20 fails since applicant is 14.1/20). Record whether the school accepts WES or evaluates itself. Record which years count (full degree / last 2 years / last 60 credits) and the rule on repeated/failed courses, and which way it cuts for the applicant.
2. IELTS overall 7.0 accepted; no overall requirement above 7.0; no sub-band above 7.0. Record Academic vs General Training.
3. Total program cost UNDER CAD 30,000 = international tuition + mandatory fees + compulsory health insurance, from the university's own fee pages, with arithmetic (per-term x terms). State fee year. Flag "fee-increase risk" if total >= CAD 27,000.
4. No faculty supervisor the applicant must find/secure. Course-based / project-based / administratively assigned supervisor only.
5. Not primarily online (>50% online disqualifies PGWP).
6. BME degree not blocked by required specific degree, honours requirement, or required work experience.

## Evidence rules (strict)
- Every claim from the university's OWN official site, page/PDF opened and read IN FULL. Aggregators only for discovering names, never evidence.
- For each fact: exact URL, page section, short VERBATIM key phrase in quotes (<15 words). Label paraphrases "(paraphrase)". Search-snippet-only quotes must be labelled "(search snippet, not opened)" — avoid these; open the page.
- If not confirmable: write UNCONFIRMED and what is missing. Never upgrade unconfirmed to confirmed.
- canada.ca only for PGWP rules / DLI list.

## How to fetch pages
- Helper: `/tmp/claude-0/-home-user-Canada-s-masters-research/a0f93c2b-d8d3-52f8-a8a8-ee572260c8de/scratchpad/tools/fetch.sh <URL> [--browser]` prints readable text of an HTML page or PDF (pdftotext). It falls back to headless Chromium if curl fails; pass `--browser` to force Chromium (needed for canada.ca and JS-rendered pages). Pipe to a file in the scratchpad and grep / read sections.
- WebSearch may be used to DISCOVER URLs (load via ToolSearch "select:WebSearch,WebFetch"). WebFetch summarises, so prefer fetch.sh for verbatim quotes.
- If a host is blocked (DNS error, proxy 403, empty page even with --browser), record the exact host and error at the top of your notes file and in your final message. Do NOT substitute snippets silently.

## Notes discipline
- Write your notes file EARLY (header + plan), then APPEND after every 2-3 programs. Do not run git commands; the coordinator commits.
- Per program record: verdict per filter (PASS / FAIL / UNCONFIRMED) with URL + section + quote; cost arithmetic; fee year; length; intakes and deadlines for Fall 2027 / Winter 2028; official program contact email; open questions for an enquiry email.
- Cap: about 15 deep checks per agent. Drop a program the moment it clearly fails a filter (record the single reason with quote).

## Already eliminated (do not re-research)
Memorial; USask engineering (all M.Eng.) and USask non-engineering (Lebanon row 15/20); Winnipeg (15/20); Laurentian, Windsor, Western, Concordia, Ottawa, Lakehead (all), Nipissing, Trent, Brock, Ontario Tech, TMU, York, Queen's, Toronto, Carleton, McMaster, Waterloo; Regina MHA/MPA/business/Computer Science; Lethbridge; TRU; VIU MBA/Community Planning/GIS/Sustainable Leisure/MEd Special Education; Royal Roads; Emily Carr; Cape Breton; Saint Mary's; UNB; UPEI MBA/engineering/applied health services research; all Quebec course-based (cost floor); Bishop's; Dalhousie; Calgary; Alberta; Manitoba; Brandon; UNBC; SFU; UVic; UBC/UBCO; UFV; MSVU; Moncton; Acadia; StFX; Athabasca; Guelph M.Eng.
