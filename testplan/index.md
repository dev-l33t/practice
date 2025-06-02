# 🧪 Test Plan for Practice Application

## 1. Introduction
This document outlines the test plan for validating a practice web application. The goal is to ensure the system functions as expected and is free from major defects prior to release.

## 2. Objectives
- Validate the functional correctness of the core modules
- Ensure usability, consistency, and stability of the system
- Detect, report, and track defects to resolution before deployment

## 3. Scope

### In Scope
- Functional Testing of:
  - User Login
  - User Registration
  - User Dashboard
  - UI Components
- Basic usability and performance validation

### Out of Scope
- Performance benchmarking under load
- Penetration or security testing

## 4. Test Items
- **Login Module**
- **Registration Module**
- **User Interface (Forms, Layouts, Navigation)**
- **Form Validations and Error Handling**

## 5. Testing Types
- Manual Functional Testing
- Regression Testing
- UI/UX Testing
- Boundary Value Analysis (BVA)
- Exploratory Testing

## 6. Testing Approach
- Test cases will be created based on the requirements/user stories
- Testing will be conducted manually with automation scripts planned for regression
- Bugs will be logged using a defect tracking tool (e.g., Jira)
- Re-testing and regression cycles will follow each build fix

## 7. Resources
- **Testing Team:** 1 QA Intern (Pratik Joshi)
- **Tools Used:**
  - Jira (Defect Tracking)
  - Postman (API Testing)
  - Selenium (Automated Testing — Future Scope)
  - Excel/Markdown (Test Documentation)

## 8. Environment Setup
- **OS:** Windows 10 / macOS
- **Browsers:** Chrome, Firefox, Edge (latest versions)
- **Devices:** Desktop only (mobile testing not in scope)
- **Test Data:** Dummy accounts and test inputs provided by QA

## 9. Deliverables
- `test-cases-login.md` — Functional test cases
- `defect-tracking.md` — Defect log/report
- `daily-status-report.md` — Execution progress report
- `traceability-matrix.md` — Requirement-to-test coverage matrix
- Final test summary report upon completion

## 10. Test Schedule

| Activity               | Start Date | End Date   |
|------------------------|------------|------------|
| Test Planning          | 2025-06-05 | 2025-06-06 |
| Test Case Design       | 2025-06-07 | 2025-06-09 |
| Test Execution         | 2025-06-10 | 2025-06-14 |
| Defect Logging & Retest| 2025-06-10 | Ongoing    |
| Test Closure           | 2025-06-15 | 2025-06-15 |

## 11. Risks & Mitigation

| Risk                          | Mitigation Strategy                                                 |
|-------------------------------|----------------------------------------------------------------------|
| Limited automation expertise  | Begin with manual testing and gradually explore Selenium basics     |
| Time constraints              | Prioritize smoke and high-impact test cases                         |
| Unclear requirements          | Raise clarifications early with stakeholders or mentors             |

---

**Prepared by:** _Pratik Joshi_  
