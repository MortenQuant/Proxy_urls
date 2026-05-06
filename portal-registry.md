# Offshore Wind Project Portal Registry — UK NSIP

Consent register URLs and proxy fallback URLs for UK offshore wind DCO projects on the Planning Inspectorate NSIP register. Covers EN010 (generating stations), EN020 (electricity lines / transmission), and EN0210 (newer transmission references).

Last refreshed: 2026-05-06

> ⚠️ **STALE WARNING.** Stage progress, latest-update text, and document URLs below are point-in-time snapshots of the NSIP project pages on the date above. The Planning Inspectorate updates these pages continuously — deadlines slip, correction orders are issued, NMC variations are applied, examinations restart. **Always re-fetch the NSIP URL before relying on a status here.** If this file is more than a few weeks old, treat every Stage / Latest-update field as potentially out of date. Reference numbers, applicants, and capacity figures change much less frequently and are usually safe.

## How to use

When `web_fetch` fails on an NSIP URL (HTTP 429), use the proxy URL below the project block:

1. `web_search` the proxy URL as the query string
2. `web_fetch` the same proxy URL

NSIP URLs are written out in full so they can be copied as-is.

## Stage vocabulary

The Planning Inspectorate runs every NSIP through this fixed pipeline. The Stage Progress table below carries the per-stage tag (`Completed` / `In progress` / `Not started` / `Current`) directly from each project's NSIP page.

`Pre-application` → `Acceptance` → `Pre-examination` → `Examination` → `Recommendation` → `Decision` → `Post-decision` ("What happens after the decision is made")

## Stage Progress — all projects at a glance

Tag values mirror the live NSIP project page exactly as displayed. Read across each row to see where the project sits. The Planning Inspectorate sometimes shows the post-decision row only for newer-format pages; for older granted projects it is implied (Decision = Completed → project is in post-decision by definition) and shown as `Current` here. Re-fetch the NSIP URL to confirm.

| Project | Reference | Proxy URL | Pre-application | Acceptance | Pre-examination | Examination | Recommendation | Decision | Post-decision |
|---|---|---|---|---|---|---|---|---|---|
| Dogger Bank D | EN010144 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010144&title=true&clean=true | In progress | Not started | Not started | Not started | Not started | Not started | Not started |
| Dogger Bank South East / West | EN010125 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010125&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | In progress | Not started |
| North Falls | EN010119 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010119&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | In progress | Not started |
| Mona | EN010137 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010137&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Morgan Offshore Wind — Generation Assets | EN010136 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010136&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Outer Dowsing | EN010130 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010130&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Morecambe Offshore Windfarm — Generation Assets | EN010121 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010121&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Rampion 2 | EN010117 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010117&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Five Estuaries | EN010115 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010115&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Awel y Môr | EN010112 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010112&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Sheringham and Dudgeon Extension | EN010109 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010109&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Hornsea Project Four | EN010098 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010098&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Norfolk Boreas | EN010087 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010087&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Thanet Extension (refused) | EN010084 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010084&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Hornsea Project Three | EN010080 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010080&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| Norfolk Vanguard | EN010079 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010079&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| East Anglia TWO | EN010078 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010078&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| East Anglia ONE North | EN010077 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010077&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current |
| East Anglia THREE | EN010056 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010056&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Hornsea Project Two | EN010053 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010053&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Sofia / Dogger Bank C | EN010051 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010051&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Hornsea Project One | EN010033 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010033&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Rampion | EN010032 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010032&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Walney Extension | EN010027 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010027&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Burbo Bank Extension | EN010026 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010026&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| East Anglia ONE | EN010025 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010025&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Dogger Bank Creyke Beck (A and B) | EN010021 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010021&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Triton Knoll | EN010005 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010005&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| Galloper | EN010003 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010003&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| **Transmission DCOs** | | | | | | | | | |
| Morgan and Morecambe — Transmission Assets | EN020032 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020032&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | In progress | Not started |
| East Irish Sea Transmission (Mooir Vannin) | EN0210008 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210008&title=true&clean=true | In progress | Not started | Not started | Not started | Not started | Not started | Not started |
| Triton Knoll Electrical System | EN020019 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020019&title=true&clean=true | Completed | Completed | Completed | Completed | Completed | Completed | Current (implied) |
| **OWF-enabling transmission corridors** | | | | | | | | | |
| Eastern Green Link 3 and 4 | EN0210003 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210003&title=true&clean=true | In progress | Not started | Not started | Not started | Not started | Not started | Not started |
| Eastern Green Link 5 | EN0210010 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210010&title=true&clean=true | In progress | Not started | Not started | Not started | Not started | Not started | Not started |
| LionLink Interconnector | EN020033 | https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020033&title=true&clean=true | In progress | Not started | Not started | Not started | Not started | Not started | Not started |

`Current (implied)` means the project page does not show a separate Post-decision row but the order has been made and the project is by definition post-decision. Newer page layouts (Mona, Morgan, Morecambe, Five Estuaries, Hornsea Four, Norfolk Vanguard / Boreas, EA1N / EA2 etc.) show `Current` explicitly. Re-fetch any project's NSIP URL to confirm the live tag.

---

## Generation DCOs — in-flight (pre-app, examination, decision)

### Dogger Bank D — EN010144

- **Stage:** Pre-application (in progress). Application submission expected June 2027.
- **Capacity:** ~2,000 MW
- **Developer:** SSE Renewables / Equinor / Vårgrønn (Doggerbank Offshore Wind Farm Project 4 Projco Limited)
- **Latest update (10 June 2025):** "The applicant's notification under section 46 of the Planning Act 2008 and Regulation 8 of the Infrastructure Planning (Environmental Impact Assessment) Regulations 2017 has been received, and an acknowledgement letter has been issued."
  - https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010144-000102-S46%20notification%20-%20Dogger%20Bank%20D%20June%202025.pdf
  - https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010144-000110-Dogger%20Bank%20D%20OWF%20-%20s46%20and%20EIA%20Reg%208%20acknowledgement%20letter%20dated%2010%20June%202025.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010144
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010144&title=true&clean=true

### Dogger Bank South East / West — EN010125

- **Stage:** Decision (in progress). Statutory deadline reset to 14 May 2026 (WMS HCWS1472 batch).
- **Capacity:** 3,000 MW
- **Developer:** RWE / Masdar (RWE Renewables UK Dogger Bank South West/East Ltd)
- **Latest update (26 March 2026):** "The Secretary of State has decided to reset the statutory deadline for this application to 14 May 2026. A statement confirming the new deadline for the decision has been made to Parliament, in accordance with section 107(7) of the Planning Act 2008."
  - https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010125-002627-Dogger%20Bank%20South%20OWFs%20Written%20statement%20made%20on%2026%20March%202026.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010125
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010125&title=true&clean=true

### North Falls — EN010119

- **Stage:** Decision (in progress). Statutory deadline reset to 14 May 2026 (WMS HCWS1472 batch).
- **Capacity:** 504 MW
- **Developer:** SSE Renewables / RWE (50:50 JV; extension to Greater Gabbard)
- **Latest update (26 March 2026):** Secretary of State reset the statutory deadline to 14 May 2026; Written Ministerial Statements issued.
  - Written Ministerial Statement: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010119-001780-Written%20Ministerial%20Statement%2026%20March%202026.pdf
  - House of Lords Statement: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010119-001781-House%20of%20Lords.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010119
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010119&title=true&clean=true

---

## Generation DCOs — granted / post-decision

### Mona — EN010137

- **Stage:** Post-decision. Application granted 4 July 2025.
- **Capacity:** 1,500 MW
- **Developer:** JERA Nex bp (acquired full ownership from EnBW, Jan 2026)
- **Latest update (24 October 2025):** "On 23 October 2025, the Secretary of State issued a Correction Order (PDF, 2MB) and a Correction Notice (PDF, 229KB) to make corrections to the Mona Offshore Wind Farm Order 2025. The Correction Order came into force on 23 October 2025."
  - Correction Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010137-002344-Mona%20OWF_Correction%20Order.pdf
  - Correction Notice: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010137-002343-Mona%20OWF_Correction%20Order%20Notice.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010137
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010137&title=true&clean=true

### Morgan Offshore Wind Project — Generation Assets — EN010136

- **Stage:** Post-decision. Application granted; project reportedly discontinued by JERA Nex bp Jan 2026.
- **Capacity:** 1,500 MW
- **Developer:** JERA Nex bp (formerly bp / EnBW)
- **Latest update (8 April 2026):** "On 8 April 2026, the Secretary of State issued a Correction Order and Correction Notice to amend The Morgan Offshore Wind Project Generation Assets Order 2025. The Correction Order becomes effective on 9 April 2026."
  - Correction Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010136-001194-The%20Morgan%20Offshore%20Wind%20Project%20Generation%20Assets%20(Correction)%20Order%202026.pdf
  - Correction Notice: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010136-001193-Correction%20Notice%20-%20Morgan%20OWF%20-%208%20April%2026.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010136
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010136&title=true&clean=true

### Outer Dowsing — EN010130

- **Stage:** Post-decision. Application decided 10 February 2026; SI 2026/138.
- **Capacity:** 1,500 MW
- **Developer:** TotalEnergies / Corio / Gulf Energy (GT R4 Limited)
- **Latest update (19 March 2026):** "The Secretary of State has issued the SI Number for the Order as made for Outer Dowsing Offshore Wind Farm 2026 (2026/138)."
  - DCO as made: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010130-002659-EN010130-002645-DCO%20as%20made%20by%20SoS.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010130
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010130&title=true&clean=true

### Morecambe Offshore Windfarm — Generation Assets — EN010121

- **Stage:** Post-decision. Application granted 12 March 2026 (decision letter signed 1 December 2025).
- **Capacity:** 480 MW
- **Developer:** CIP (Copenhagen Infrastructure Partners; took full ownership from Cobra / Flotation Energy, Feb 2025)
- **Latest update (12 March 2026):** "The Secretary of State has today granted development consent for this application."
  - Decision Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000383-Decision%20letter%20Morecambe%20OWF%20GA%20for%20Signature%20011225%20redacted.pdf
  - Examining Authority's Recommendation Report: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000382-Morecambe%20Offshore%20Windfarm%20Generation%20Assets%20Report%20&%20Appendices%20A%20B%20C%20D%20E.pdf
  - Development Consent Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000384-Morecambe%20DCO.pdf
  - Habitats Regulations Assessment: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000382-Morecambe%20OWGA%20HRA%20281125_new%20version.pdf
  - PINS Notice of Decision: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000382-PINS%20Notice%20of%20SoS%20Decision%20-%20Reg%2031%20-%20GRANTED.pdf
  - Regulation 31 Notice: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010121-000386-Regulation%2031%20Notice%20-%20Morecambe.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010121
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010121&title=true&clean=true

### Rampion 2 — EN010117

- **Stage:** Post-decision. Application granted 4 April 2025.
- **Capacity:** ~1,200 MW
- **Developer:** RWE (Rampion Extension Development Limited)
- **Latest update (23 April 2026):** "On 23 April 2026, the Secretary of State issued a Correction Order (PDF, 209KB) and a Correction Notice (PDF, 170KB) to make corrections to the Rampion 2 Offshore Wind Farm Order 2025. The Correction Order will come into force on 24 April 2026."
  - Correction Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010117-002504-Order.pdf
  - Correction Notice: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010117-002503-Notice.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010117
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010117&title=true&clean=true

### Five Estuaries — EN010115

- **Stage:** Post-decision. Application granted 17 December 2025.
- **Capacity:** 1,100 MW
- **Developer:** RWE (33.33%) / Macquarie consortium (25%) / ESB (20.83%) / Sumitomo (20.83%)
- **Latest update (17 December 2025):** "On 17 December 2025 the Secretary of State for Energy Security and Net Zero granted consent for this application."
  - PINS Notification of Decision: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002038-PINS%20Notification%20letter%20of%20Decision.pdf
  - SoS Decision Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002035-SoS%20Decision%20letter.pdf
  - DCO as made by SoS: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002032-DCO%20as%20made%20by%20SoS.pdf
  - Final Recommendation Report: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002037-Final%20Recommendation%20Report.pdf
  - Reg 31 Notice: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002034-Reg%2031%20Notice.pdf
  - HRA report from SoS: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002033-HRA%20report%20from%20SoS.pdf
  - Post-examination consultation submissions: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010115-002040-Five%20Estuaries%20-%20Post%20examination%20consultation%20submissions%20(Decision%20stage)%20-%20January%202025%20(1).pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010115
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010115&title=true&clean=true

### Awel y Môr — EN010112

- **Stage:** Post-decision. Application granted 20 September 2023.
- **Capacity:** 576 MW
- **Developer:** RWE
- **Latest update (16 July 2024):** "On 16 July 2024 the Secretary of State issued a Correction Notice (PDF, 169KB) and Correction Order (PDF, 101KB) to make corrections to the Awel Y Môr Wind Farm Order 2023."
  - Correction Notice: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010112/EN010112-001849-Correction%20Notice.pdf
  - Correction Order: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010112/EN010112-001850-Correction%20Order.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010112
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010112&title=true&clean=true

### Sheringham and Dudgeon Extension Projects — EN010109

- **Stage:** Post-decision. Sheringham Shoal & Dudgeon Extensions Order 2024 made.
- **Capacity:** 719 MW (Sheringham 317 MW + Dudgeon 402 MW)
- **Developer:** Equinor
- **Latest update (7 February 2025):** "A Decision Letter (PDF, 256KB) and Amendment Order (PDF, 107KB) have been issued by Department for Energy Security and Net Zero to make a change that is not material to the Made The Sheringham Shoal and Dudgeon Extensions Offshore Wind Farm Order 2024."
  - Decision Letter: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010109/EN010109-002393-SADEP%20NMC%20DL%20signed%20-%206%20Feb.pdf
  - Amendment Order: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010109/EN010109-002394-SADEP%20NMC%20Amendment%20Order-%206%20Feb.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010109
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010109&title=true&clean=true

### Hornsea Project Four — EN010098

- **Stage:** Post-decision.
- **Capacity:** 2,400 MW
- **Developer:** Ørsted
- **Latest update (5 May 2026):** "The Secretary of State for Energy Security and Net Zero has issued a letter inviting comments from Natural England, the States of Alderney, the RSPB and the MMO on the applicant's submission of the amended Guillemot Compensation Implementation and Monitoring Plan (CGIMP)."
  - Consultation letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010098-002441-Hornsea%204%20-%20revised%20Guillemot%20Compensation%20Implementation%20and%20Monitoring%20Plan%20consultation%20letter.pdf
  - Related GCIMP documents: https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010098/documents?stage-post_decision=Consultation%20on%20Guillemot%20Compensation%20Implementation%20and%20Monitoring%20Plan%20(GCIMP)%203&itemsPerPage=25
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010098
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010098&title=true&clean=true

### Norfolk Boreas — EN010087

- **Stage:** Post-decision. Application granted 10 December 2021.
- **Capacity:** 1,800 MW
- **Developer:** RWE (acquired Vattenfall UK projects, 2023)
- **Latest update (19 December 2025):** "A Decision Letter and Amendment Order have been issued by the Department for Energy Security and Net Zero to make a change that is not material to the Made Norfolk Boreas Offshore Wind Farm Order 2021."
  - Decision Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010087-001141-Norfolk%20Boreas%202025%20NMC%20-%20Decision%20Letter%20-%2018-12-25.pdf
  - Amendment Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010087-001142-Norfolk%20Boreas%20NMC%20Order%20-%20December%202025.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010087
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010087&title=true&clean=true

### Thanet Extension — EN010084

- **Stage:** Post-decision. **REFUSED** 2 June 2020.
- **Capacity:** 340 MW (proposed)
- **Developer:** Vattenfall
- **Latest update (2 June 2020):** "The Secretary of State has refused development consent for this application."
  - PINS Notification of Decision: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010084/EN010084-003114-TEOW%20%E2%80%93%20PINS%20Notification%20Letter%20of%20Decision.pdf
  - SoS Decision Letter: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010084/EN010084-003110-TEOW%20-%20Secretary%20of%20State%20Decision%20Letter.pdf
  - Final Recommendation Report: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010084/EN010084-003108-TEOW%20%E2%80%93%20Final%20Recommendation%20Report.pdf
  - Regulation 31 Notice: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010084/EN010084-003111-TEOW%20-%20Regulation%2031%20Notice.pdf
  - HRA Report: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010084/EN010084-003109-TEOW%20-%20HRA%20Report.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010084
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010084&title=true&clean=true

### Hornsea Project Three — EN010080

- **Stage:** Post-decision. Application granted 31 December 2020.
- **Capacity:** 2,852 MW
- **Developer:** Ørsted
- **Latest update (10 May 2024):** "A Decision Letter (PDF, 205KB) and Amendment Order (PDF, 153KB) have been issued by the Department of Energy Security and Net Zero to make a change that is not material to the Hornsea Three Offshore Wind Farm Order 2020."
  - Decision Letter: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010080/EN010080-003697-H3%20non%20material%20change%20decision%20letter%20final.pdf
  - Amendment Order: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010080/EN010080-003698-Hornsea%203%20NMC%202%20Final%20validated.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010080
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010080&title=true&clean=true

### Norfolk Vanguard — EN010079

- **Stage:** Post-decision. Application granted 11 February 2022.
- **Capacity:** 1,800 MW
- **Developer:** RWE (acquired Vattenfall UK projects, 2023)
- **Latest update (13 April 2026):** "The Secretary of State has decided to approve the use of the Marine Recovery Fund in principle, in substitution for the measures in the Benthic Implementation and Monitoring Plan."
  - Decision Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010079-004647-Norfolk%20Vanguard%20Benthic%20Compensation%20Decision%20Letter.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010079
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010079&title=true&clean=true

### East Anglia TWO — EN010078

- **Stage:** Post-decision. East Anglia TWO Offshore Wind Farm Order 2022.
- **Capacity:** 900 MW
- **Developer:** ScottishPower Renewables
- **Latest update (24 March 2026):** "On 06 October 2025 the Marine Management Organisation (MMO) received a request from Scottish Power Renewables to vary the Deemed Marine Licences contained within Schedules 13 and 14 of the East Anglia TWO Offshore Wind Farm Order 2022. Following stakeholder consultation, the MMO completed its consideration and determined to make the variations."
  - Cover Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010078-010140-Variation%201%20-%20Cover%20Letter.pdf
  - Notice of Variation, Schedule 13: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010078-010142-Notice%20of%20Variation%201%20-%20Schedule%2013.pdf
  - Notice of Variation, Schedule 14: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010078-010141-Notice%20of%20Variation%201%20-%20Schedule%2014.pdf
  - Variation 1, DML Schedule 13: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010078-010139-Variation%201%20-%20DML%20Schedule%2013%20of%20the%20EA%20TWO%20Offshore%20Wind%20Farm%20Order%202022.pdf
  - Variation 1, DML Schedule 14: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010078-010138-Variation%201%20-%20DML%20Schedule%2014%20of%20the%20EA%20TWO%20Offshore%20Wind%20Farm%20Order%202022.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010078
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010078&title=true&clean=true

### East Anglia ONE North — EN010077

- **Stage:** Post-decision. East Anglia ONE North Offshore Wind Farm Order 2022.
- **Capacity:** 800 MW
- **Developer:** ScottishPower Renewables
- **Latest update (12 February 2026):** MMO received a request from Scottish Power Renewables on 06 October 2025 to vary the Deemed Marine Licences in Schedules 13 and 14 of the East Anglia ONE North Offshore Wind Farm Order 2022; following stakeholder consultation, MMO approved the variations.
  - Variation 1 Cover Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010077-000980-EA1N%20-%20Variation%201%20-%20Cover%20Letter.pdf
  - Notice of Variation, Schedule 13: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010077-000982-EA1N%20-%20Notice%20of%20Variation%201%20-%20Schedule%2013.pdf
  - Notice of Variation, Schedule 14: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010077-000981-EA1N%20-%20Notice%20of%20Variation%201%20-%20Schedule%2014.pdf
  - Order, Schedule 13: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010077-000978-EA1N-GEN-CNS-VOR-IBR-000003_Rev01_The_East_Anglia_ONE_North_Offshore_Windfarm_Order_2022_Schedule_13_.pdf
  - Order, Schedule 14: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010077-000979-EA1N-GEN-CNS-VOR-IBR-000002_Rev01_The_East_Anglia_ONE_North_Offshore_Windfarm_Order_2022_Schedule_14.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010077
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010077&title=true&clean=true

### East Anglia THREE — EN010056

- **Stage:** Post-decision. Under construction.
- **Capacity:** 1,400 MW
- **Developer:** ScottishPower Renewables
- **Latest update (5 January 2026):** "On 5 January 2026, the Secretary of State for Energy Security & Net Zero made a decision to approve the request for discharge of Requirement 38 in Part 3 of Schedule 1 to the Order."
  - Post-decision documents index: https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010056/documents?stage-post_decision=Post-decision&itemsPerPage=25
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010056
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010056&title=true&clean=true

### Hornsea Project Two — EN010053

- **Stage:** Post-decision. Application granted 16 August 2016. Operational since 2022.
- **Capacity:** 1,386 MW
- **Developer:** Ørsted
- **Latest update:** "On 17 August 2023 the Marine Management Organisation (MMO) received a request from Ørsted to vary the Deemed Marine Licences (DML) contained within Schedules 9 and 11 of the Hornsea Two Offshore Wind Farm Order 2016. The MMO has now completed its consideration of the request and, in exercise of the powers conferred by section 72(3)(d) of the Marine and Coastal Access Act 2009, has determined to make the variations as detailed in the documentation published on the MMO website."
  - Hornsea Two Order 2016: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010053/EN010053-002077-Development%20Consent%20Order%20made%20by%20the%20Secretary%20of%20State.pdf
  - MMO Variation 6 page: https://www.gov.uk/government/publications/hornsea-two-offshore-wind-farm-variation-6
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010053
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010053&title=true&clean=true

### Sofia / Dogger Bank C (formerly Dogger Bank Teesside A & B) — EN010051

- **Stage:** Post-decision. Application granted 5 August 2015 (Dogger Bank Teesside A&B Offshore Wind Farm Order 2015).
- **Capacity:** ~2,400 MW combined (Sofia 1,400 MW + Dogger Bank C ~1,000 MW)
- **Developer:** Sofia portion (formerly Teesside B): RWE. Dogger Bank C portion (formerly Teesside A): SSE Renewables / Equinor / Eni. Both branches consent under the same DCO.
- **Latest update (3 April 2025):** "The Marine Management Organisation has issued a letter, dated 19 March 2025, to confirm its intent to defer an Environmental Impact Assessment consent decision under the Marine Works (Environmental Impact Assessment) Regulations 2007 in relation to the Sofia Offshore Wind Farm."
  - MMO defer letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010051-002621-20250319_MLA202400669_EIA%20Intent%20to%20Defer%20letter_SoS_FINAL.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010051
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010051&title=true&clean=true

### Hornsea Project One — EN010033

- **Stage:** Post-decision. Application decided 10 December 2014. Operational since 2020.
- **Capacity:** 1,218 MW
- **Developer:** Ørsted (with Global Infrastructure Partners stakes since 2018)
- **Latest update (7 November 2022):** "The Marine Management Organisation has published notices of variation to the Deemed Marine Licences."
  - MMO NSIP marine licensing collection: https://www.gov.uk/government/collections/marine-licensing-nationally-significant-infrastructure-projects
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010033
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010033&title=true&clean=true

### Rampion — EN010032

- **Stage:** Post-decision. Operational since 2018.
- **Capacity:** 400 MW
- **Developer:** RWE / Macquarie / Enbridge
- **Latest update (29 April 2021):** "A Decision Letter (PDF, 307KB) and Amendment Order (PDF, 53KB) have been issued by the Department for Business, Energy and Industrial Strategy to make a change that is not material to the Rampion (Offshore Wind Farm) Order 2014."
  - Decision Letter: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010032/EN010032-003079-Decision-letter-Rampion-NMC.pdf
  - Amendment Order: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010032/EN010032-003082-The-Rampion-Offshore-Wind-Farm-(Amendment)-Order-2021.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010032
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010032&title=true&clean=true

### Walney Extension — EN010027

- **Stage:** Post-decision. Application granted 7 November 2014. Operational since 2018.
- **Capacity:** 659 MW
- **Developer:** Ørsted (with PFA / PKA stakes)
- **Latest update (29 January 2020):** "The examination documents relating to this project have been archived and are no longer available on this site. The Secretary of State's decision and Development Consent Order can be viewed on the Documents tab. To find out where to view the Certified Documents please refer to the contact details set out in the Explanatory Note of the Development Consent Order."
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010027
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010027&title=true&clean=true

### Burbo Bank Extension — EN010026

- **Stage:** Post-decision. Application granted 26 September 2014. Operational since 2017.
- **Capacity:** 258 MW
- **Developer:** Ørsted (with PKA / KIRKBI stakes)
- **Latest update (16 October 2019):** "The examination documents relating to this project have been archived and are no longer available on this site. The Secretary of State's decision and Development Consent Order can be viewed on the Documents tab. To find out where to view the Certified Documents please refer to the contact details set out in the Explanatory Note of the Development Consent Order."
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010026
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010026&title=true&clean=true

### East Anglia ONE — EN010025

- **Stage:** Post-decision. East Anglia ONE Offshore Wind Farm Order 2014. Operational since 2020.
- **Capacity:** 714 MW
- **Developer:** ScottishPower Renewables
- **Latest update (24 September 2021):** "A Decision Letter and Amendment Order have been issued by the Department for Business, Energy and Industrial Strategy to make a change that is not material to the East Anglia ONE Offshore Wind Farm Order 2014."
  - Decision Letter: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010025/EN010025-002946-EA1%20NMC%20Decision%20Letter%201.pdf
  - Amendment Order: https://infrastructure.planninginspectorate.gov.uk/wp-content/ipc/uploads/projects/EN010025/EN010025-002945-EA1%20NMC%20Amendment%20Order%202021.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010025
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010025&title=true&clean=true

### Dogger Bank Creyke Beck (Dogger Bank A and B) — EN010021

- **Stage:** Post-decision. Dogger Bank Creyke Beck Offshore Wind Farm Order 2015 (amended 2019, 2020, 2022, 2025). Under construction / partial operation.
- **Capacity:** 2,400 MW (1,200 MW each for A and B)
- **Developer:** SSE Renewables / Equinor / Eni
- **Latest update (21 November 2025):** A Decision Letter and Amendment Order have been issued by the Secretary of State for Energy Security and Net Zero regarding a non-material change to the Development Consent Order.
  - 2025 Decision Letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010021-002510-DB%20Creyke%20Beck%20OWF%20-%20Decision%20Letter.pdf
  - 2025 Amendment Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010021-002509-DB%20Creyke%20Beck%20OFW%20-%20(Amendment)%20Order%202025.pdf
  - 2015 Order with 2025 amendments: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010021-002486-The%20Dogger%20Bank%20Creyke%20Beck%20Offshore%20Wind%20Farm%20Order%202015%20with%202025%20amendments%20(1).pdf
  - 2020 Amendment Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010021-002421-NMC%20Creyke%20Beck%20Amendment%20Order%202020.pdf
  - 2022 Amendment Order: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN010021-002458-Dogger%20Bank%20Creyke%20Beck%20Offshore%20Wind%20Farm%20Order%202015%20Amendment%20Order%20FOR%20PINS.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010021
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010021&title=true&clean=true

### Triton Knoll — EN010005

- **Stage:** Post-decision. Application granted 11 July 2013. Operational since 2022.
- **Capacity:** 857 MW
- **Developer:** RWE / J-Power / Kansai
- **Latest update (29 January 2020):** "The examination documents relating to this project have been archived and are no longer available on this site. The Secretary of State's decision and Development Consent Order can be viewed on the Documents tab."
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010005
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010005&title=true&clean=true

### Galloper — EN010003

- **Stage:** Post-decision. Application granted 24 May 2013. Operational since 2018.
- **Capacity:** 353 MW
- **Developer:** RWE / SSE / ESB / Macquarie consortium
- **Latest update (29 January 2020):** "The examination documents relating to this project have been archived and are no longer available on this site. The Secretary of State's decision and Development Consent Order can be viewed on the Documents tab."
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN010003
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN010003&title=true&clean=true

---

## Transmission DCOs (offshore wind related)

Separate transmission DCOs are issued where the offshore generating station and the onshore connection assets are consented in different orders. Track these as separate projects — deadlines, examination timetables, and applicants can differ from the linked generation DCO.

### Morgan and Morecambe Offshore Wind Farms — Transmission Assets — EN020032

- **Stage:** Decision (in progress). Statutory deadline 14 May 2026 (WMS HCWS1472 batch).
- **Linked generation:** EN010136 (Morgan gen) + EN010121 (Morecambe gen)
- **Applicant:** Morgan Offshore Wind Limited + Morecambe Offshore Windfarm Limited
- **Latest update (27 April 2026):** "The Secretary of State has decided to publish all the post-examination submissions received from 29 October 2025 to 29 January 2026."
  - Project updates page: https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN020032/project-updates
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN020032
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020032&title=true&clean=true

### East Irish Sea Transmission Project (Mooir Vannin link) — EN0210008

- **Stage:** Pre-application (in progress). Application submission expected March 2029.
- **Linked generation:** Mooir Vannin (Isle of Man territorial waters)
- **Applicant:** Ørsted East Irish Sea Transmission Limited
- **Latest update:** No dated update; project is at the pre-application stage. Contact: eastirishseata@planninginspectorate.gov.uk
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN0210008
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210008&title=true&clean=true

### Triton Knoll Electrical System — EN020019

- **Stage:** Post-decision. Operational.
- **Linked generation:** EN010005 (Triton Knoll gen)
- **Applicant:** RWE
- **Latest update (30 May 2023):** "The Examination documents relating to this project have been archived and are no longer available on this site. The Secretary of State's decision and Development Consent Order can be viewed on the Documents tab."
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN020019
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020019&title=true&clean=true

---

## OWF-enabling transmission corridors / interconnectors

Not offshore-wind generation DCOs themselves, but exist primarily to evacuate offshore wind power (Scotland → England HVDC bootstraps, GB ↔ NL interconnectors with offshore converters in OWF zones). Listed for completeness.

### Eastern Green Link 3 and Eastern Green Link 4 — EN0210003

- **Stage:** Pre-application (in progress). Application submission expected August 2026.
- **Description:** HVDC subsea + onshore converter stations in Walpole, Norfolk; Scotland → England.
- **Applicant:** National Grid Electricity Transmission / Scottish Hydro Electric Transmission
- **Latest update (13 May 2025):** Section 46 / EIA Reg 8 notification received; acknowledgement issued.
  - S46 notification: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN0210003-000007-Section%2046%20Letter%20EGL%203%20and%20EGL%204_Redacted.pdf
  - Acknowledgement letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN0210003-000006-s46%20and%20EIA%20Reg%208%20acknowledgement%2013%20May%202025.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN0210003
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210003&title=true&clean=true

### Eastern Green Link 5 — EN0210010

- **Stage:** Pre-application (in progress). Scoping Opinion published October 2025.
- **Description:** HVDC subsea cable; Scotland → Anderby Creek, Lincolnshire.
- **Applicant:** National Grid Electricity Transmission / Scottish Hydro Electric Transmission
- **Latest update (13 October 2025):** "The Planning Inspectorate has published a Scoping Opinion for Eastern Green Link 5 on 13 October 2025."
  - Scoping Opinion: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN0210010-000042-Scoping%20Opinion.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN0210010
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN0210010&title=true&clean=true

### LionLink Interconnector — EN020033

- **Stage:** Pre-application (in progress).
- **Description:** 2.0 GW GB ↔ Netherlands link with offshore converter platform in Dutch waters; connects to Dutch offshore wind.
- **Applicant:** National Grid Ventures / TenneT
- **Latest update (14 January 2026):** Section 46 / EIA Reg 8 notification received; acknowledgement issued.
  - S46 letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN020033-000152-LionLink%20S46%20Letter.pdf
  - Acknowledgement letter: https://nsip-documents.planninginspectorate.gov.uk/published-documents/EN020033-000151-Lion%20Link%20s46%20and%20EIA%20Reg%208%20acknowledgement%20letter.pdf
- **NSIP URL:** https://national-infrastructure-consenting.planninginspectorate.gov.uk/projects/EN020033
- **Proxy URL:** https://urltomarkdown.herokuapp.com/?url=https%3A%2F%2Fnational-infrastructure-consenting.planninginspectorate.gov.uk%2Fprojects%2FEN020033&title=true&clean=true

EGL1 and EGL2 went through Scottish / Ofgem consenting routes, not NSIP — no EN reference.

---

## How transmission DCOs get their own EN number

Two reference-number formats coexist for transmission / electricity-lines NSIPs:

- **EN020xxx** — original electricity-lines numbering, used since the early 2010s. Examples in this register: EN020019 (Triton Knoll Electrical), EN020032 (Morgan & Morecambe Transmission), EN020033 (LionLink).
- **EN0210xxx** — newer numbering format introduced around 2024 for transmission / interconnector projects. Examples in this register: EN0210003 (Eastern Green Link 3 & 4), EN0210008 (East Irish Sea Transmission), EN0210010 (Eastern Green Link 5). Also EN0210006 (Ossian Transmission, withdrawn).

A transmission DCO is typically filed separately from the linked generation DCO only when:

1. Two or more generation DCOs share a single transmission corridor (Morgan + Morecambe → joint EN020032).
2. The transmission asset is built well after the generation order (Triton Knoll Electrical EN020019 followed Triton Knoll gen EN010005 by several years).
3. The transmission asset is a pure grid-side bootstrap not tied to a single OWF (Eastern Green Links).
4. The OWF lease is in non-UK waters but the export cable lands in the UK (Mooir Vannin / East Irish Sea Transmission EN0210008 — Isle of Man waters).

For all other NSIPs (Hornsea 1–4, Dogger Bank A/B/C/D, Dogger Bank South, Norfolk Vanguard / Boreas, EA1 / 2 / 3 / 1N / 2, Sofia, Outer Dowsing, Five Estuaries, Mona, Awel y Môr, Sheringham & Dudgeon Extension, Rampion 2, North Falls, etc.) the gen + transmission assets sit in a single combined DCO.

---

## Out of scope

- **Scottish offshore wind generation projects** (Berwick Bank, Inch Cape, Seagreen, Neart na Gaoithe, Kincardine, Hywind Scotland, Salamander, Pentland, Ossian, Cenos, Caledonia, Bowdun, etc.) — consented via Section 36 / Marine Directorate, not NSIP. No EN reference.
- **Pre-2010 / Round 1–2 projects** consented under the older Electricity Act regime that don't have an EN0xxxxx reference (London Array, Greater Gabbard original consent, Sheringham Shoal original, Race Bank, Dudgeon original, Lincs, Westermost Rough, Humber Gateway, Gwynt y Môr, West of Duddon Sands).
- **Withdrawn / cancelled NSIPs**: Navitus Bay (EN010024, refused September 2015), Ossian Transmission (EN0210006, withdrawn March 2026).
- **EGL1 / EGL2** — Scottish / Ofgem consenting routes.
- **EN010085** — this is **Cleve Hill Solar Park**, NOT Dogger Bank C. Earlier versions of this registry mistakenly attached EN010085 to Dogger Bank C; corrected in this revision. Dogger Bank C consents under EN010051 (the original Teesside A&B Order 2015) alongside Sofia.
