# OpenCart Manual Testing Documentation

This repository houses the comprehensive manual software testing lifecycle artifacts, strategic planning, and defect management documentation executed for the OpenCart e-commerce platform.

---

## Deliverables and Core Artifacts

* **Test Plan (`Test-Plan(Team 5)_merged.docx`):** Defines the overall testing strategy, scope boundaries, test environments, resource allocation, and entry/exit quality gates.
* **Test Summary & Quality Gate Report (`OpenCart_Manual_Testing_Summary_Report.xlsx`):** A high-level executive dashboard summarizing overall test execution metrics, module-wise pass/fail distributions, defect density statistics, and dynamic status charts.
* **Test Cases Documentation (`Final Test case (open cart ).xlsx`):** A granular repository of 207 functional, UI, and edge-case test steps mapped against explicit preconditions, localized test data, and validated expected results.
* **Defect Log and Bug Report (`Final Bug Report( Open Cart ) .xlsx`):** A structured log tracking 20 tracked defects categorized by explicit severity levels (Blocker, Major, Minor) with detailed steps to reproduce, system states, and validation outputs.

---

## Testing Scope and Feature Coverage
The manual verification process validated the integrity of the following primary sub-systems:
* **Identity & Access Management:** Registration workflows, dynamic field validation rules, secure Login/Logout sequences, and session state retention.
* **Product Catalog & UX:** Search indexing, multi-viewport display layouts, currency conversion accuracy, dynamic filtering, and product-to-product comparison matrices.
* **Transaction Pipeline:** Shopping Cart operations (pricing calculations and boundary quantities), Checkout progression, shipping/billing address configurations, and order generation states.

---

## Key Metrics and Analytical Insights
* **Total Executed Scenarios:** 207 Test Cases
* **Global Pass Rate:** ~90.3% (187 Passed Cases)
* **Defect Footprint:** 20 Active Defects identified
  * *Critical/Blocker:* 3 Issues (requiring immediate engineering priority)
  * *Major Severity:* 6 Issues (disrupting secondary workflow paths)
  * *Minor Severity:* 11 Issues (cosmetic UI and baseline alignment adjustments)
* **Quality Gate Verdict:** Conditional Sign-Off (Platform satisfies fundamental execution workflows; remaining minor issues are logged and tracked for subsequent sprint iterations).
