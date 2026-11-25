
# Requirement Traceability Matrix (RTM)

## 1. Purpose

The Requirement Traceability Matrix (RTM) establishes traceability between business requirements, functional requirements, analytical outputs and validation test cases for the Pharma Market Intelligence & Commercial Strategy Control Tower.

The RTM will help ensure that:
- Every business requirement is addressed through system functionality.
- Functional requirements are linked to measurable analytical outputs wherever applicable.
- Analytical outputs can be validated.
- Requirements can be tracked throughout the project lifecycle.
- Gaps between business expectations and system implementation can be identified.

## 2. Requirement Traceability Matrix

| BR ID | Business Requirement | FR ID | Functional Requirement | KPI / Analytical Output | Test Case ID |
|---|---|---|---|---|---|
| BR-01 | Market Intelligence | FR-002, FR-003, FR-004 | Country Market Comparison, Market Attractiveness Scoring and Visualisation | Country Market Attractiveness Score, Disease Burden, Population Opportunity, Healthcare Access, Market Growth Potential | TBD |
| BR-02 | Competitive Intelligence | FR-005, FR-006, FR-007 | Competitor Database, Competitive Monitoring and Competitive Activity Analysis | Active Competitor Count, Competitive Activity Index, Competitive Developments, Sponsor Distribution | TBD |
| BR-03 | Clinical Pipeline Intelligence | FR-008, FR-009 | Clinical Trial Integration and Clinical Pipeline Analysis | Active Trial Count, Phase 3 Trial Count, Pipeline Stage Distribution, Sponsor Distribution | TBD |
| BR-04 | Regulatory Intelligence | FR-010, FR-011 | Regulatory Intelligence Tracking and Regulatory Event Analysis | Regulatory Event Count, Approval Event Count, Indication Expansion Count, Regulatory Event Trend | TBD |
| BR-05 | Pricing and Market Access | FR-012, FR-013 | Pricing Data Management and Pricing/Affordability Analysis | Public Price Observation, Price Comparison Index, Affordability Indicator, Access Event Count | TBD |
| BR-06 | Commercial Analytics | FR-014, FR-015, FR-016 | Synthetic Commercial Dataset Management, Sales Performance and HCP/Territory Analytics | Sales Achievement %, Sales Growth %, HCP Coverage %, Call Plan Achievement %, Territory Performance, Territory Opportunity Score | TBD |
| BR-07 | Forecasting and Scenario Planning | FR-017 | Scenario-Based Forecasting | Forecast Market Size, Forecast Growth %, Scenario Variance, Forecast Sensitivity | TBD |
| BR-08 | AI-Assisted Market Intelligence | FR-019 | AI-Assisted Intelligence Summarisation | Source-linked summaries, key developments, intelligence categorisation and synthesis | TBD |
| BR-09 | Interactive Analytics Dashboard | FR-018 | Interactive Dashboard | Market, competitive, clinical, regulatory, pricing and commercial dashboard views | TBD |
| BR-10 | Data Quality and Reliability | FR-001, FR-020 | Data Source Integration and Data Quality Validation | Missing Data Report, Duplicate Records, Validation Results, Source Refresh Status | TBD |

## 3. Functional Requirement Traceability

| FR ID | Requirement | Related BR | Validation Approach |
|---|---|---|---|
| FR-001 | Data Source Integration | BR-10 | Validate source retrieval, metadata capture and extraction error handling |
| FR-002 | Country Market Comparison | BR-01 | Compare selected countries and indicators across available years |
| FR-003 | Country Market Attractiveness Scoring | BR-01 | Validate score calculation, component weights and missing-data handling |
| FR-004 | Market Indicator Visualisation | BR-01 | Validate visualisation, indicator labels, filters and source information |
| FR-005 | Competitor Database | BR-02 | Validate competitor records, product relationships and indication mappings |
| FR-006 | Competitive Intelligence Monitoring | BR-02 | Validate event records, categorisation, dates and source references |
| FR-007 | Competitive Activity Analysis | BR-02 | Validate event aggregation and documented activity scoring |
| FR-008 | Clinical Trial Integration | BR-03 | Validate clinical trial extraction and key trial attributes |
| FR-009 | Clinical Pipeline Analysis | BR-03 | Validate pipeline filtering, aggregation and sponsor analysis |
| FR-010 | Regulatory Intelligence Tracking | BR-04 | Validate regulatory event records and source traceability |
| FR-011 | Regulatory Event Analysis | BR-04 | Validate regulatory event aggregations and trends |
| FR-012 | Pricing Data Management | BR-05 | Validate pricing observation structure, currency and source metadata |
| FR-013 | Pricing and Affordability Analysis | BR-05 | Validate price comparison logic and documented affordability methodology |
| FR-014 | Synthetic Commercial Dataset Management | BR-06 | Validate dataset structure and synthetic data identification |
| FR-015 | Sales Performance Analysis | BR-06 | Validate sales achievement, growth and territory calculations |
| FR-016 | HCP and Territory Analytics | BR-06 | Validate synthetic HCP segmentation, coverage and activity analysis |
| FR-017 | Scenario-Based Forecasting | BR-07 | Validate assumptions, scenario calculations and outputs |
| FR-018 | Interactive Dashboard | BR-09 | Validate dashboard filters, visuals, KPI outputs and usability |
| FR-019 | AI-Assisted Intelligence Summarisation | BR-08 | Validate source references, factual grounding and output limitations |
| FR-020 | Data Quality Validation | BR-10 | Validate missing values, duplicates, invalid values and quality reporting |

## 4. KPI Traceability

| KPI / Analytical Output | Business Requirement | Related FR | Validation Status |
|---|---|---|---|
| Country Market Attractiveness Score | BR-01 | FR-003 | Pending |
| Disease Burden | BR-01 | FR-002, FR-004 | Pending |
| Population Opportunity | BR-01 | FR-002, FR-004 | Pending |
| Healthcare Access | BR-01 | FR-002, FR-004 | Pending |
| Market Growth Potential | BR-01 | FR-002, FR-003 | Pending |
| Competitive Activity Index | BR-02 | FR-007 | Pending |
| Active Competitor Count | BR-02 | FR-005, FR-007 | Pending |
| Pipeline Stage Distribution | BR-03 | FR-009 | Pending |
| Phase 3 Trial Count | BR-03 | FR-009 | Pending |
| Regulatory Event Count | BR-04 | FR-011 | Pending |
| Approval Event Count | BR-04 | FR-011 | Pending |
| Price Comparison Index | BR-05 | FR-013 | Pending |
| Affordability Indicator | BR-05 | FR-013 | Pending |
| Sales Achievement Percentage | BR-06 | FR-015 | Pending |
| Sales Growth Percentage | BR-06 | FR-015 | Pending |
| HCP Coverage Percentage | BR-06 | FR-016 | Pending |
| Call Plan Achievement Percentage | BR-06 | FR-016 | Pending |
| Territory Opportunity Score | BR-06 | FR-016 | Pending |
| Forecast Market Size | BR-07 | FR-017 | Pending |
| Forecast Growth Percentage | BR-07 | FR-017 | Pending |
| Scenario Variance | BR-07 | FR-017 | Pending |

## 5. Test Case Traceability

Test cases will be created during the implementation and testing phases.

Each test case should contain:

- Test Case ID
- Requirement ID
- Test Scenario
- Test Objective
- Test Data
- Preconditions
- Test Steps
- Expected Result
- Actual Result
- Status
- Defect Reference, if applicable

### Proposed Test Case ID Convention

| Prefix | Description |
|---|---|
| TC-MI | Market Intelligence Test Cases |
| TC-CI | Competitive Intelligence Test Cases |
| TC-CT | Clinical Trial Test Cases |
| TC-RI | Regulatory Intelligence Test Cases |
| TC-PA | Pricing and Access Test Cases |
| TC-CA | Commercial Analytics Test Cases |
| TC-FC | Forecasting Test Cases |
| TC-AI | AI Intelligence Test Cases |
| TC-DQ | Data Quality Test Cases |
| TC-DB | Dashboard Test Cases |

Example:

TC-MI-001: Validate Country Market Attractiveness Score calculation.

TC-CT-001: Validate clinical trial records retrieved from the source API.

TC-CA-001: Validate Sales Achievement Percentage calculation using synthetic data.

## 6. Traceability Governance

- Each business requirement should map to at least one functional requirement.
- Functional requirements should be validated before they are considered completed.
- KPIs should have documented definitions and calculation logic.
- Test cases should reference the requirements they validate.
- Requirement changes should be reviewed for their impact on related functionality, KPIs, datasets and tests.
- Requirements that cannot be implemented due to data limitations should be documented.
- The RTM should be updated as implementation progresses.

## 7. Traceability Limitations and Assumptions

- This RTM is based on simulated stakeholder requirements and project assumptions.
- The stakeholder requirements are not based on formal interviews with actual pharmaceutical company stakeholders.
- KPI availability depends on the accessibility, quality and comparability of public data.
- Commercial analytics will use synthetic datasets.
- Forecasts and attractiveness scores are analytical demonstrations, not validated commercial decision models.
- AI-generated summaries will require source validation and should not be treated as independently verified conclusions.

## 8. RTM Status

| Component | Status |
|---|---|
| Business Requirements Mapping | Defined |
| Functional Requirements Mapping | Defined |
| KPI Mapping | Initial Mapping Completed |
| Test Case Mapping | Pending Implementation |
| Test Execution | Not Started |
| Defect Tracking | Not Started |
| RTM Maintenance | Ongoing |
