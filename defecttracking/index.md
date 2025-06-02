# Defect Tracking Template

| Field           | Description                                                                                      |
|-----------------|------------------------------------------------------------------------------------------------|
| **Defect ID**   | Unique identifier for the defect (e.g., D001, BUG-123)                                         |
| **Summary**     | Short, clear summary/title of the defect                                                       |
| **Description** | Detailed explanation of the defect, including what is wrong                                    |
| **Steps to Reproduce** | Precise steps to replicate the issue                                                      |
| **Environment** | Information about OS, browser, app version, device, etc. where defect was found                 |
| **Severity**    | Impact level on functionality (Critical, Major, Minor, Trivial)                                |
| **Priority**    | Business urgency to fix (High, Medium, Low)                                                    |
| **Status**      | Current state (New, Open, In Progress, Fixed, Retested, Closed, Rejected)                      |
| **Assignee**    | Person or team responsible for fixing the defect                                               |
| **Reporter**    | Person who reported the defect                                                                 |
| **Date Reported** | Date defect was logged                                                                         |
| **Date Resolved** | Date defect was fixed and verified                                                            |
| **Comments**    | Additional notes, retest results, communications                                               |

---

## Sample Defect Record

| Defect ID | Summary                        | Description                             | Steps to Reproduce           | Environment        | Severity | Priority | Status   | Assignee    | Reporter   | Date Reported | Date Resolved | Comments             |
|-----------|--------------------------------|---------------------------------------|-----------------------------|--------------------|----------|----------|----------|-------------|------------|---------------|---------------|----------------------|
| D001      | Login button not responding    | Login button does not trigger submit  | 1. Go to login page          | Windows 10, Chrome  | Critical    | High     | Open     | John Doe    | Jane Smith | 2025-06-01    |               | Issue reproducible consistently |

---

# Defect Management Guidelines

### Severity Levels

- **Critical**: System crash, data loss, or major functionality completely broken. Immediate fix required.
- **Major**: Important feature malfunctioning but system remains usable.
- **Minor**: Small issue or cosmetic defect not affecting core functionality.
- **Trivial**: Very minor issue (typos, UI alignment) with no impact on functionality.

### Priority Levels

- **High**: Must be fixed immediately; blocks major functionality or release.
- **Medium**: Should be fixed soon; does not block major functionality or release.
- **Low**: Fix can be deferred; does not affect immediate release.

### Status Workflow

- **New**: Defect logged, awaiting triage.
- **Open**: Accepted and assigned for fixing.
- **In Progress**: Currently being worked on.
- **Fixed**: Developer resolved the defect.
- **Retested**: Tester verified the fix.
- **Closed**: Defect verified and closed.
- **Rejected**: Not a defect or duplicate; will not be fixed.

### Best Practices

- Provide clear, concise, and reproducible steps.
- Include environment details for better debugging.
- Assign severity and priority based on impact and urgency.
- Update status promptly to reflect current progress.
- Use comments for communication between testers and developers.

---

*Prepared by:* Pratik Joshi  
