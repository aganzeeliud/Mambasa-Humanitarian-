# OWR Stakeholder Map

Interactive humanitarian 5Ws stakeholder map for Mambasa Territory in Ituri Province and Wamba and Watsa Territories in Haut-Uele, Democratic Republic of the Congo.

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

## Methodology

1. **Define the 5Ws.** Every row is structured around Who, What, Where, When and Why.
2. **Collect public data.** OCHA/HDX operational presence, historical 3W and population datasets are downloaded and recorded with their source URLs and dates.
3. **Normalise fields.** Organisation names, actor types, sectors, territories, localities, dates, funders, budgets and population fields are aligned to one model.
4. **Join geography.** Localities and territories are linked to approximate reference coordinates. Missing or approximate points are flagged.
5. **Add evidence status.** Records are labelled as verified public-source records, workbook records requiring validation, or data gaps.
6. **Validate with partners.** Partners and clusters should confirm current presence, activity, exact location, dates, beneficiaries, funder and budget.
7. **Publish an update.** Corrections are made with a source note, verification note and reporting period.

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
- **IOM DTM Ituri / HDX:** contextual displacement and needs information, including Mambasa.
- **OpenStreetMap:** basemap tiles used by the interactive Leaflet map.

Source URLs and detailed provenance are retained in the Excel workbook sheets `Data Sources`, `Data Notes`, `Historical Coverage` and `5Ws MODEL`.

## URL rename

The intended public name is **OWR Stakeholder Map**. GitHub Pages derives its project URL from the repository name. Renaming the repository to `OWR-Stakeholder-map` requires repository-owner/admin permissions; until that administrative change is made, the active public URL remains the `Mambasa-Humanitarian-` address above.

## Files

- `index.html` - public landing page with data facts, methodology and embedded map.
- `RFO_Stakeholders_Map.html` - standalone interactive Leaflet map.
- `RFO_Stakeholders Final.xlsx` - consolidated 5Ws stakeholder database.
- `Mambasa_Humanitarian_3W_Matrix.xlsx` - working source workbook with historical and 5Ws sheets.

## Responsible use

Do not publish sensitive personal information or exact protection-service locations. Confirm access, consent, security and data-protection requirements before sharing operational details. Use the partner-validation workflow for every reporting cycle.
