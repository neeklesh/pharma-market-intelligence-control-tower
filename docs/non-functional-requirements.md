
# Non-Functional Requirements (NFRs)

## 1. Purpose

This document defines the non-functional requirements (NFRs) for the Pharma Market Intelligence & Commercial Strategy Control Tower.

Non-functional requirements define the quality attributes, operating constraints, reliability, security, performance, maintainability and usability expectations of the analytical solution.

## 2. Non-Functional Requirements

### NFR-001: Performance

**Priority:** Must

**Requirement:**  
The system should process and display analytical datasets efficiently enough to support interactive analysis using the selected free-tier or locally installed tools.

**Acceptance Criteria:**
- Standard analytical queries on reasonably sized project datasets should ideally execute within 10 seconds.
- Dashboard pages should ideally load within 10 seconds under normal local operating conditions.
- Performance limitations caused by hardware, data volume or free-tier infrastructure should be documented.
- Performance targets are indicative and will be validated during implementation.

### NFR-002: Data Reliability

**Priority:** Must

**Requirement:**  
The data ingestion and transformation process should be repeatable and should minimise data loss, duplication and inconsistent processing.

**Acceptance Criteria:**
- Data extraction processes should capture errors and failed requests.
- Records should not be unintentionally duplicated during repeated ingestion.
- Data ingestion should be repeatable wherever the source permits.
- Failed ingestion processes should be identifiable.
- The system should retain sufficient metadata to understand the data refresh process.

### NFR-003: Data Quality

**Priority:** Must

**Requirement:**  
The analytical datasets should undergo structured data quality checks before being used for analysis or visualisation.

**Acceptance Criteria:**
- Missing values should be identified.
- Duplicate records should be identified.
- Invalid data types should be detected.
- Invalid or inconsistent values should be flagged.
- Data quality findings should be documented.
- Data quality issues should not be silently ignored.

### NFR-004: Data Traceability

**Priority:** Must

**Requirement:**  
Analytical outputs should be traceable to their underlying data sources, transformations and assumptions wherever feasible.

**Acceptance Criteria:**
- Public datasets should retain source references.
- Extraction dates should be recorded.
- Transformation logic should be documented.
- Analytical assumptions should be documented.
- Synthetic datasets should be clearly identified.
- Important analytical outputs should be explainable and reproducible.

### NFR-005: Security and Privacy

**Priority:** Must

**Requirement:**  
The project should follow basic data security and privacy principles and avoid exposing sensitive information.

**Acceptance Criteria:**
- No personal health information or patient-identifiable data should be used.
- No confidential corporate datasets should be included.
- Credentials, API keys and passwords should not be committed to GitHub.
- Environment variables or other appropriate credential-management methods should be used where credentials are required.
- Publicly accessible repository content should be reviewed before publishing.

### NFR-006: Usability

**Priority:** Must

**Requirement:**  
The dashboard and analytical outputs should be understandable to business stakeholders without requiring them to understand the underlying programming or database architecture.

**Acceptance Criteria:**
- KPI definitions should be accessible.
- Dashboard titles and labels should be clear.
- Charts should include appropriate labels and units.
- Filters should be understandable.
- The dashboard should clearly distinguish actual public information from simulated commercial data.
- Key insights should be presented in business-oriented language.

### NFR-007: Maintainability

**Priority:** Must

**Requirement:**  
The project code, database structures, documentation and analytical processes should be organised to support future changes and enhancements.

**Acceptance Criteria:**
- Code should be organised into logical notebooks, scripts and modules.
- SQL queries should be organised into appropriately named files.
- Business logic should avoid unnecessary duplication.
- Documentation should be updated when important implementation changes occur.
- Project files should follow a consistent naming convention.

### NFR-008: Scalability

**Priority:** Should

**Requirement:**  
The solution should be designed in a way that allows additional countries, products, therapeutic areas and data sources to be incorporated without requiring a complete redesign.

**Acceptance Criteria:**
- Country-specific data should follow consistent structures where feasible.
- Data models should avoid unnecessary country-specific hardcoding.
- New therapeutic areas should be capable of being incorporated through extensible data structures.
- New sources should be capable of being added through modular ingestion processes.

### NFR-009: Cost Efficiency

**Priority:** Must

**Requirement:**  
The project should be developed and operated primarily using free tools, publicly accessible data and locally available resources.

**Acceptance Criteria:**
- Core development should use free tools wherever possible.
- Paid subscriptions should not be mandatory for core functionality.
- Free-tier limitations should be documented.
- Any optional paid services should be clearly identified before use.
- The solution should be capable of being demonstrated without requiring paid cloud infrastructure.

### NFR-010: Reproducibility

**Priority:** Must

**Requirement:**  
The analytical workflow should allow the developer to repeat data processing and analytical procedures with documented inputs, logic and assumptions.

**Acceptance Criteria:**
- Python dependencies should be documented.
- Data transformation steps should be documented.
- SQL logic should be version controlled.
- Analytical assumptions should be recorded.
- Where possible, the same inputs and logic should produce consistent outputs.

### NFR-011: Availability and Resilience

**Priority:** Should

**Requirement:**  
The project should handle temporary data source failures and local environment issues without unnecessarily compromising previously processed data.

**Acceptance Criteria:**
- Source API failures should be logged where feasible.
- Previously downloaded datasets should not be unnecessarily overwritten by failed extraction attempts.
- The system should identify incomplete data refreshes.
- Data source availability limitations should be documented.
- Recovery or re-execution procedures should be documented where appropriate.

### NFR-012: Explainability of Analytical Outputs

**Priority:** Must

**Requirement:**  
Analytical scores, forecasts and AI-assisted insights should provide sufficient context for users to understand the basis of the output.

**Acceptance Criteria:**
- Market attractiveness scores should expose their underlying indicators and weights.
- Forecasts should expose assumptions and scenario definitions.
- AI-assisted summaries should reference their underlying sources wherever feasible.
- Interpretations should be distinguishable from verified facts.
- Analytical limitations should be documented.

## 3. NFR Priority Summary

| Requirement | Priority |
|---|---|
| NFR-001 Performance | Must |
| NFR-002 Data Reliability | Must |
| NFR-003 Data Quality | Must |
| NFR-004 Data Traceability | Must |
| NFR-005 Security and Privacy | Must |
| NFR-006 Usability | Must |
| NFR-007 Maintainability | Must |
| NFR-008 Scalability | Should |
| NFR-009 Cost Efficiency | Must |
| NFR-010 Reproducibility | Must |
| NFR-011 Availability and Resilience | Should |
| NFR-012 Explainability | Must |

## 4. Validation Approach

Non-functional requirements will be validated throughout development using:

- Python data quality checks.
- SQL validation queries.
- Performance testing on representative datasets.
- Dashboard usability reviews.
- Source traceability checks.
- Repository and credential security reviews.
- Reproducibility checks.
- Documentation reviews.

## 5. Project Constraints

- Development will primarily use free tools.
- The project will use publicly available data and synthetic commercial datasets.
- Analytical results should not be interpreted as actual pharmaceutical company commercial performance.
- Performance targets will be validated against the development environment.
- This project is a portfolio demonstration and not a production pharmaceutical decision-support system.
