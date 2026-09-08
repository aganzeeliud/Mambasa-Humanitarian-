# OWR Stakeholder Map

Interactive humanitarian 5Ws/RFO stakeholder map for Mambasa Territory in Ituri Province and Wamba and Watsa Territories in Haut-Uele, Democratic Republic of the Congo. The public edition combines operational records, population planning denominators and clearly labelled WorldPop intervention scenarios.

## Public pages

- Landing page: `https://aganzeeliud.github.io/Mambasa-Humanitarian-/`
- Interactive map: `https://aganzeeliud.github.io/Mambasa-Humanitarian-/RFO_Stakeholders_Map.html`
- Final stakeholder workbook: [`RFO_Stakeholders Final.xlsx`](RFO_Stakeholders%20Final.xlsx)

## Purpose

The project supports humanitarian information management and coordination by bringing together:

- Who: organisations, agencies, local actors and coordination structures
- What: sectors, clusters, activities and projects
- Where: province, territory, chiefdom/collectivity, locality and approximate coordinates
- When: operation start, end and reporting years
- Why: humanitarian need or operational objective

The map and workbook are coordination tools. They do not replace partner confirmation, cluster reporting, government records or a formal needs assessment.

## Data coverage

The current model covers:

| Area | Province | 2024 planning population | 5Ws records |
|---|---|---:|---:|
| Mambasa | Ituri | 309,169 | 104 |
| Wamba | Haut-Uele | 561,587 | 13 |
| Watsa | Haut-Uele | 385,896 | 16 |

The operational time series contains historical records from 2018 and current public-source records through 2026. Years without a source snapshot are documented as data gaps and are not interpreted as proof of no activity.

The consolidated database contains 163 5Ws records, 28 existing stakeholder entries and a dedicated register of 10 Ebola-response organisations. All three synchronized workbooks carry the same WorldPop scenario fields, Ebola-response records and source register.

## Methodology

1. **Define the 5Ws.** Every row is structured around Who, What, Where, When and Why.
2. **Collect public data.** OCHA/HDX operational presence, historical 3W and population datasets are downloaded and recorded with their source URLs and dates.
3. **Normalise fields.** Organisation names, actor types, sectors, territories, localities, dates, funders, budgets and population fields are aligned to one model.
4. **Join geography.** Localities and territories are linked to approximate reference coordinates. Missing or approximate points are flagged.
5. **Add evidence status.** Records are labelled as verified public-source records, workbook records requiring validation, or data gaps.
6. **Validate with partners.** Partners and clusters should confirm current presence, activity, exact location, dates, beneficiaries, funder and budget.
7. **Publish an update.** Corrections are made with a source note, verification note and reporting period.

### WorldPop planning scenario

WorldPop DRC 2024 constrained population data (R2025A v1, 100 m) is used to estimate the population around each approximate locality reference point. The workbook applies a 5 km radius and a 10% planning coverage factor:

`Estimated beneficiaries per intervention = WorldPop locality population x 10%`

These values are planning scenarios only. They are not observed beneficiaries, approved targets or unique people reached. Coordinates and radius results require partner validation, and estimates must not be summed across interventions without deduplication.

### Ebola response coverage

The database includes 10 source-backed Ebola-response records. UNICEF EOC historical records document surveillance, psychosocial support, child protection and nutrition-related response activities in Mambasa and Mandima Health Zones during 2018–2019. Preliminary INSP/INRB BDBV monitoring records document surveillance, IPC/WASH, points of control, laboratory preparedness and community engagement in Mambasa and Wamba during 2026. Health zones are used as operational geography proxies for territory-level reporting. No verified Ebola-specific operation in Watsa was identified in the reviewed public sources; this is an evidence gap, not proof of no activity.

## Validation rules

- A source-backed operation date is preferred over an inferred year.
- Population estimates are planning denominators, not beneficiary counts.
- A beneficiary number is not created when the public source does not provide one.
- A budget is marked unavailable when it is not published by the source.
- Map coordinates are approximate locality or territory references, not facility-level GPS.
- A missing year or territory record is a data gap, not evidence that no organisation operated.
- Organisation presence and activity status should be reconfirmed before external reporting.

## Source register

- **OCHA DRC Operational Presence / HDX:** current operational records, project dates, territories, actors and clusters.
- **OCHA DRC 3W National - May 2018 / HDX:** historical project and activity records, including Mambasa.
- **HDX/OCHA DRC Subnational Population Statistics 2024:** health-zone projections aggregated to territory planning populations.
- **WorldPop DRC Population 2024 R2025A v1:** constrained 100 m raster used for locality planning scenarios. Dataset ID 73054; DOI `10.5258/SOTON/WP00839`; [catalogue record](https://hub.worldpop.org/geodata/summary?id=73054).
- **UNICEF EOC Ebola response datasets:** historical 2018–2019 surveillance and psychosocial response records for Mambasa/Mandima health zones.
- **INSP/INRB BDBV2026 public data:** preliminary 2026 surveillance and public-health response records for Mambasa and Wamba. [Repository](https://github.com/INRB-UMIE/BDBV2026-Data).
- **OCHA Financial Tracking Service:** published 2018–2019 Ebola response funding flows and 2026 BDBV emergency funding status. Funding flows are not disaggregated to Mambasa/Mandima unless explicitly stated.

The `Ebola Organisations` sheet identifies each response organisation, role, operation period, geographic scope, source and verification status. It includes INSP/INRB, UNICEF EOC, DRC Ministry of Health, WHO, OCHA, IOM, ALIMA, MSF, the DRC Red Cross and CDC. Organisations identified only in provincial or national response context are explicitly marked for local validation rather than treated as confirmed locality-level implementers.

The `Ebola Funding` sheet records 2018–2019 OCHA Financial Tracking Service transactions and the reviewed 2026 BDBV funding status. Published amounts are retained with the original currency basis, recipient, mechanism, date and geographic scope. The 2018–2019 transactions are province-level or regional and are not attributed to Mambasa/Mandima without a public local allocation. For 2026, no OCHA FTS transaction was returned for the BDBV emergency and no donor amount was publicly identified for Mambasa or Wamba; this is recorded as unavailable, not as proof of no funding.
- **IOM DTM Ituri / HDX:** contextual displacement and needs information, including Mambasa.
- **OpenStreetMap:** basemap tiles used by the interactive Leaflet map.

Source URLs and detailed provenance are retained in the Excel workbook sheets `Data Sources`, `Data Notes`, `Historical Coverage` and `5Ws MODEL`.

## URL rename

The intended public name is **OWR Stakeholder Map**. GitHub Pages derives its project URL from the repository name. Renaming the repository to `OWR-Stakeholder-map` requires repository-owner/admin permissions; until that administrative change is made, the active public URL remains the `Mambasa-Humanitarian-` address above.

## Files

- `index.html` - public landing page with data facts, WorldPop caveats, methodology and embedded map.
- `RFO_Stakeholders_Map.html` - standalone interactive Leaflet map.
- `RFO_Stakeholders Final.xlsx` - consolidated 5Ws stakeholder database.
- `RFO_Stackholder_db.xlsx` - standalone RFO stakeholder database.
- `Ebola Organisations` sheet - source-backed Ebola-response organisation register included in all three workbooks.
- `Mambasa_Humanitarian_3W_Matrix.xlsx` - working source workbook with historical and 5Ws sheets.

## Responsible use

Do not publish sensitive personal information or exact protection-service locations. Confirm access, consent, security and data-protection requirements before sharing operational details. Use the partner-validation workflow for every reporting cycle.
