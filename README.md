# Guru99 Banking Application – Manual Testing Project

## Project Overview

This repository contains a complete **end-to-end manual testing project** performed on the Guru99 Banking web application across multiple versions (V1 – V4).

The objective of this project was to simulate real-world QA activities following the **Software Testing Life Cycle (STLC)** including:

- Requirement Analysis
- Test Planning
- Test Case Design
- Test Execution
- Regression Testing
- Defect Tracking
- Change Request Handling
- Test Closure Activities

---

## Application Under Test

The Guru99 Banking Demo Application simulates a banking system with features such as:

- Customer registration
- Login system
- Account management
- Deposit & withdrawal
- Fund transfer
- Balance checking
 
 There are two main roles in the system:

- **Manager role**: Has access to all the modules.
- **Customer role**: Accesses only some features of the system.

This is the overall system chart:

<img src="system_chart.png" alt="Screenshot" width="750"/>


---
## Application release versions
### Version 1 – Requirement Analysis & Test Case Design

The first version of the Banking Site can be accessed via the following link:
```
http://demo.guru99.com/V1/
```

Activities performed:
- [SRS_v1](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v1/SRS_v1.docx) review
- Functional requirement analysis
- Test case design based on specifications: [TestCaseSuite_v1](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v1/TestCaseSuite_v1.xlsx)
- Positive and negative scenario identification
- Integration scenario planning: [IntegrationPlanning_v1](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v1/IntegrationPlanning_v1.xlsx)
- Test case execution
- Defects identification
- Documentation of bugs in the [BugTracker_v1](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v1/BugTracker_v1.xlsx)

### Version 2 – Integration Testing Preparation

The second version of the Banking Site can be accessed via the following link:

(Please use the login credentials generated for version 1 to access the site.
)

```
http://demo.guru99.com/V2/
```

Activities performed:
- Analysis of the updated requirements document [SRS_v2](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v2/SRS_v2.docx)
- Update and maintenance of existing test cases to align with new requirements: [TestCaseSuite_v2](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v2/TestCaseSuite_v2.xlsx)
- Creation of a Unit Test Plan for the **Balance Enquiry** module
- Re‑execution of failed test cases from Version 1
- Execution of regression test cases to ensure that existing functionalities remain unaffected
- Verification that reported defects have been correctly fixed: [BugTracker_v2](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v2/BugTracker_v2.xlsx)
- Update of the integration planning: [IntegrationPlanning_v2](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v2/IntegrationPlanning_v2.xlsx)


### Version 3 – System Testing Planning & Execution
The third version of the Banking Site can be accessed via the following link:

```
http://demo.guru99.com/V3/
```

Activities performed:
- Analysis of the updated requirements document [SRS_v3](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v3/SRS_v3.docx)
- Identification of new functional flows: **change password**, **Deposit**, **Withdrawal**, **Fund Transfer**, **Balance Enquiry**
- Test case design for the new **webservice requirement**
- Design of a system test plan: [SystemTestPlan_v3](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v3/SystemTestPlan_v3.xlsx)
- Execution of the System Test Cases
- Operate as Manager and Customer
- Defects identification and report in the [BugTracker_v3](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v3/BugTracker_v3.xlsx)

### Version 4 – Final release
The final version of the Banking Site can be accessed via the following link:

```
http://demo.guru99.com/V4/
```

Activities performed:
- Analysis of the updated requirements document [SRS_v4](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v4/SRS_v4.docx)
- Update and maintenance of the system test plan to align with new requirements: [SystemTestPlan_v4](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v4/SystemTestPlan_v4.xlsx)
- Re‑testing of previously failed cases
- Regression testing around the areas that changed
- Bug Tracker Synchronization: [BugTracker_v4](https://github.com/medrarem2704/Guru99-manual-testing-project/blob/main/v4/BugTracker_v4.xlsx)


---

## Conclusion

This project provided hands-on experience with the complete Software Testing Life Cycle (STLC) through a realistic simulation of manual testing activities on a banking application.

Throughout the different project versions, I progressively applied key QA practices including:

- Requirement analysis
- Test planning
- Test scenario identification
- Test case design
- Test execution
- Defect reporting
- Test metrics and reporting

---

## Reference

Project source: https://www.guru99.com/live-testing-project.html

---