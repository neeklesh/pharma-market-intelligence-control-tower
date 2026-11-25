## 4. Functional Requirement Prioritisation

| Requirement ID | Requirement Name | Priority |
|---|---|---|
| FR-001 | Data Source Integration | Must |
| FR-002 | Country Market Comparison | Must |
| FR-003 | Country Market Attractiveness Scoring | Must |
| FR-004 | Market Indicator Visualisation | Must |
| FR-005 | Competitor Database | Must |
| FR-006 | Competitive Intelligence Monitoring | Must |
| FR-007 | Competitive Activity Analysis | Should |
| FR-008 | Clinical Trial Integration | Must |
| FR-009 | Clinical Pipeline Analysis | Must |
| FR-010 | Regulatory Intelligence Tracking | Must |
| FR-011 | Regulatory Event Analysis | Should |
| FR-012 | Pricing Data Management | Should |
| FR-013 | Pricing and Affordability Analysis | Should |
| FR-014 | Synthetic Commercial Dataset Management | Must |
| FR-015 | Sales Performance Analysis | Must |
| FR-016 | HCP and Territory Analytics | Should |
| FR-017 | Scenario-Based Forecasting | Must |
| FR-018 | Interactive Dashboard | Must |
| FR-019 | AI-Assisted Intelligence Summarisation | Should |
| FR-020 | Data Quality Validation | Must |

. Functional Requirements — Version 1.0
We'll define 20 functional requirements for our platform. These are drafted as requirements for our simulated project, not validated requirements from a real pharmaceutical company.
FR-001 — Data Source Integration
Priority: Must

Requirement: The system shall retrieve and integrate data from selected publicly accessible sources, including healthcare, economic, clinical, regulatory and company information sources.

Acceptance criteria:
- Data can be retrieved from supported sources.
- Source metadata is captured.
- Extraction date is recorded.
- Failed extraction attempts are logged.
- Source limitations are documented.
Dependency: Source availability, API access and usage permissions.

FR-002 — Country Market Comparison
Priority: Must

Requirement: The system shall allow users to compare selected market indicators across India, Singapore, Malaysia, Thailand, China and Japan.

Acceptance criteria:
- Users can select one or more countries.
- Users can compare defined indicators.
- Users can filter by year where data is available.
- Visualisations clearly identify country and reporting period.
- Missing data is visibly identified.

FR-003 — Country Market Attractiveness Scoring
Priority: Must

Requirement: The system shall calculate a Country Market Attractiveness Score using configurable weights and documented market indicators.

Acceptance criteria:
- The score is calculated using defined components.
- Component weights can be configured.
- The total weight must equal 100%.
- Component scores and final scores are accessible.
- The methodology is documented.
- Missing data is handled transparently.

FR-004 — Market Indicator Visualisation
Priority: Must

Requirement: The system shall display selected market, healthcare, economic and demographic indicators through interactive visualisations.

Acceptance criteria:
- Users can view indicators by country.
- Users can filter by reporting period.
- Visualisations display units.
- Data source references are accessible.

FR-005 — Competitor Database
Priority: Must

Requirement: The system shall maintain structured information about relevant pharmaceutical companies and their products.

Acceptance criteria:
- Company records can be stored.
- Product records can be stored.
- Product-company relationships can be maintained.
- Relevant indications can be recorded.
- Records can be retrieved and filtered.

FR-006 — Competitive Intelligence Monitoring
Priority: Must

Requirement: The system shall maintain a structured record of relevant competitive developments.

Acceptance criteria:
- Developments can be recorded.
- Developments can be categorised.
- Developments can be associated with companies and products.
- Publication dates and source references are retained.
- Users can filter developments by category and period.

FR-007 — Competitive Activity Analysis
Priority: Should

Requirement: The system shall analyse competitive activity using defined indicators and documented scoring methodologies.

Acceptance criteria:
- Relevant events can be counted.
- Activity can be compared across companies.
- The activity index methodology is documented.
- Users can view the contributing components.

FR-008 — Clinical Trial Integration
Priority: Must

Requirement: The system shall retrieve and maintain structured clinical trial data relevant to the selected therapeutic areas.

Acceptance criteria:
- Trial identifiers are retained.
- Sponsor information is captured where available.
- Drug and indication information is captured.
- Trial phase is captured.
- Trial status is captured.
- Trial dates are retained where available.
- Source references are retained.

FR-009 — Clinical Pipeline Analysis
Priority: Must

Requirement: The system shall allow users to analyse clinical pipeline developments by company, drug, indication, phase, status and relevant geography.

Acceptance criteria:
- Users can filter pipeline records.
- Pipeline counts can be calculated.
- Trial distribution by phase can be visualised.
- Sponsor-level comparisons can be generated.
- Trial records can be traced to source information.

FR-010 — Regulatory Intelligence Tracking
Priority: Must

Requirement: The system shall maintain structured information about relevant regulatory developments from selected regulatory authorities and other approved sources.

Acceptance criteria:
- Regulatory events can be recorded.
- Country and regulatory authority can be identified.
- Event type can be categorised.
- Publication dates are retained where available.
- Source references are retained.
- Events can be filtered.

FR-011 — Regulatory Event Analysis
Priority: Should

Requirement: The system shall allow users to analyse regulatory developments by country, product, indication, event category and reporting period.

Acceptance criteria:
- Regulatory event counts can be generated.
- Events can be compared across countries.
- Events can be filtered by period.
- Relevant event trends can be visualised.

FR-012 — Pricing Data Management
Priority: Should

Requirement: The system shall maintain structured public pricing observations for selected pharmaceutical products and markets where reliable data is available.

Acceptance criteria:
- Product information is recorded.
- Country is recorded.
- Price and currency are recorded.
- Source is recorded.
- Observation date is recorded.
- Price context and limitations are documented.

FR-013 — Pricing and Affordability Analysis
Priority: Should

Requirement: The system shall support comparative pricing and affordability analysis using documented methodologies.

Acceptance criteria:
- Users can compare selected price observations.
- Currency and price units are clearly identified.
- Comparisons account for methodological limitations.
- Affordability indicators are documented.
- Source traceability is retained.

FR-014 — Synthetic Commercial Dataset Management
Priority: Must

Requirement: The system shall support structured synthetic datasets representing commercial sales, territories, HCP segments, targets and activities.

Acceptance criteria:
- Synthetic records can be created and stored.
- HCP identifiers are simulated.
- Territory identifiers are simulated.
- Sales and target values can be stored.
- Planned and completed activities can be stored.
- Synthetic data is clearly labelled.

FR-015 — Sales Performance Analysis
Priority: Must

Requirement: The system shall calculate and visualise sales performance indicators using synthetic commercial datasets.

Acceptance criteria:
- Sales achievement is calculated.
- Sales growth is calculated where applicable.
- Performance can be analysed by territory.
- Performance can be analysed by period.
- Targets and actual values can be compared.

FR-016 — HCP and Territory Analytics
Priority: Should

Requirement: The system shall support analysis of synthetic HCP segmentation, coverage, territory opportunity and commercial activity.

Acceptance criteria:
- HCP records can be segmented.
- Coverage indicators can be calculated.
- Territory performance can be analysed.
- Call-plan achievement can be calculated.
- Territory opportunity scores can be calculated using documented methodology.

FR-017 — Scenario-Based Forecasting
Priority: Must

Requirement: The system shall support scenario-based forecasting of selected market indicators using configurable assumptions.

Acceptance criteria:
- Users can select forecasting assumptions.
- Base, optimistic and pessimistic scenarios can be generated.
- Forecast periods are identified.
- Assumptions are documented.
- Forecast outputs can be compared.
- Forecast limitations are documented.

FR-018 — Interactive Dashboard
Priority: Must

Requirement: The system shall provide an interactive dashboard displaying relevant market intelligence, competitive intelligence, clinical pipeline, regulatory, pricing and commercial analytical outputs.

Acceptance criteria:
- Dashboard sections are available.
- Users can filter applicable visualisations.
- Charts and tables display relevant labels.
- KPI definitions are accessible.
- Data source information is accessible where applicable.

FR-019 — AI-Assisted Intelligence Summarisation
Priority: Should

Requirement: The system shall support AI-assisted summarisation and categorisation of selected market intelligence developments using accessible source information.

Acceptance criteria:
- Source content is provided to the summarisation process.
- A summary can be generated.
- Relevant source references are retained.
- AI-generated interpretation is distinguished from source facts.
- Unsupported conclusions are not presented as verified facts.
- Summarisation limitations are documented.

FR-020 — Data Quality Validation
Priority: Must

Requirement: The system shall validate datasets for defined data quality issues before analytical use.

Acceptance criteria:
- Duplicate records can be identified.
- Missing values can be identified.
- Invalid data types can be identified.
- Invalid values can be identified based on defined rules.
- Validation results can be recorded.
- Data quality issues can be reported.

## 5. Requirement Traceability

Functional requirements should be linked to stakeholder needs, business requirements, KPIs, data sources, development tasks and testing activities.

A detailed Requirement Traceability Matrix will be developed during subsequent project phases.

## 6. Dependencies

- Availability of relevant public data.
- API accessibility and usage restrictions.
- Data quality and completeness.
- Availability of free software and services.
- Availability of synthetic datasets for commercial analytics.
- Documented analytical methodologies.
- Technical feasibility of integrations.

## 7. Scope Considerations

The requirements will be implemented iteratively.

Requirements may be refined based on data availability, feasibility, data quality, analytical value and project constraints.

The initial implementation will prioritise the Must requirements.
