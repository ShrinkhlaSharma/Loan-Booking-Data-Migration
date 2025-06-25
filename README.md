# Loan-Booking Data Migration

## About the Project
This mock Business Analyst engagement simulates the end-to-end migration of loan-booking data from a legacy MS Access database into an Oracle Data Warehouse. It covers:

- **As-Is vs To-Be Analysis:** Identifying current manual processes and designing an automated, rules-driven ETL pipeline.  
- **Requirements Documentation:** Crafting BRD and FRD artifacts to capture business objectives, scope, field-level mappings, and validation rules.  
- **Data Migration Mapping:** Defining source→target transformations (date parsing, numeric cleanup, code mapping) and handling exceptions.  
- **UAT & Reconciliation:** Planning and executing user acceptance tests, then reconciling row counts and sums to achieve ≥ 99.9% data accuracy.

## Contents

- **docs/BRD_FRD.md**  
  Business Requirements (BRD) & Functional Requirements (FRD) with MoSCoW prioritization and gap analysis.

- **docs/Data_Migration_Mapping.md**  
  Field-level mapping matrix, transformation rules, error-handling logic, and reconciliation plan.

- **docs/UAT_Plan.md**  
  UAT approach, entry/exit criteria, environment setup, test management, and BA responsibilities.

- **docs/UAT_Test_Cases.md**  
  Positive and negative test cases detailing preconditions, steps, and expected results for nightly ETL validation.

Clone or fork to review professional BA deliverables and templates.  
