# SER216_Final_Project_RahmatullohToirov
## Digital Parking Permit System
A university wants a digital parking permit system. Students and staff can register vehicles, request parking permits, check available parking zones, and report parking issues. Security staff can verify permits and update violation records.
---
## Project Description
This repository contains the final practical project for SER216, covering software engineering requirements, workflow design, test planning, and defect analysis for a **Digital Parking Permit System**.
---
## Tools Used
| Tool          | Purpose                              |
|---------------|--------------------------------------|
| Google Docs   | Writing the final report             |
| Google Sheets | Creating the test case table         |
| diagrams.net  | Drawing the workflow diagram         |
| GitHub        | Version control and project hosting  |
---
## Repository Structure
```
SER216_Final_Project_RahmatullohToirov/
│
├── README.md                          ← Project overview and instructions
├── final_report.pdf                   ← Final project report (all tasks)
├── diagrams/
│   └── workflow_diagram.png           ← Vehicle registration workflow diagram
├── tables/
│   └── test_cases.csv                 ← 6 test cases (system, acceptance, regression)
├── screenshots/
│   ├── repo_homepage.png              ← Screenshot of repository homepage
│   ├── commits.png                    ← Screenshot of commit history
│   ├── branch.png                     ← Screenshot of feature branch
│   └── pull_request.png              ← Screenshot of pull request
└── notes/
    └── tools_used.md                  ← Detailed notes on tools and workflow
```
---
## Project Tasks Summary
### Task 1 – Requirements
**Functional Requirements:**
1. The system shall allow students and staff to register their vehicles using a student/staff ID and vehicle details.
2. The system shall allow registered users to request a parking permit for a specified zone and duration.
3. The system shall display available parking zones and their current occupancy status in real time.
4. The system shall allow security staff to verify the validity of a parking permit by scanning or entering the permit ID.
**Non-Functional Requirements:**
1. The system shall process permit verification requests within 2 seconds under normal load.
2. The system shall be available 99.9% of the time during university operating hours.
---
### Task 2 – Workflow Diagram
See `diagrams/workflow_diagram.png` for the full diagram.
**Workflow:**
```
Vehicle Registration → Permit Request → Zone Check → Permit Approval → Parking Verification
```
---
### Task 3 – Test Cases
See `tables/test_cases.csv` for the full test case table.
Six test cases covering:
- 2 System test cases
- 2 Acceptance test cases
- 2 Regression test cases
---
### Task 4 – Defect Analysis
**Defect:** "A valid parking permit is shown as expired during security verification."
| Item              | Answer                                                                                   |
|-------------------|------------------------------------------------------------------------------------------|
| Defect Category   | Logic / Data Synchronization Error                                                       |
| Severity          | High                                                                                     |
| Priority          | High                                                                                     |
| Possible Root Cause | The permit expiry date is not being correctly read or compared; possible timezone mismatch or date format inconsistency in the verification module |
| Regression Test   | After fix, re-run permit verification with a valid permit created today and one expiring tomorrow to confirm they show as valid |
---
### Task 5 – GitHub Evidence
All required GitHub activities have been completed:
- ✅ Repository created: `SER216_Final_Project_RahmatullohToirov`
- ✅ README.md added
- ✅ Project files uploaded
- ✅ Feature branch created: `feature/upload-project-files`
- ✅ At least 3 meaningful commits made
- ✅ Pull request created from feature branch to main
- ✅ Pull request merged
- ✅ Final PDF uploaded to repository
---
## Workflow
1. Clone the repository
2. Review `final_report.pdf` for the complete project write-up
3. View `diagrams/workflow_diagram.png` for the system workflow
4. Review `tables/test_cases.csv` for all test cases
---
## Author
**Rahmatulloh Toirov**  
SER216 – Software Quality Assurance  
