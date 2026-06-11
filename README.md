# 🚀 BCHSoftware Internal microservice: Operation Hello World
### Project Code: S1-HW-01
**Department Deployment Pipeline | Sprint 1 (2 Weeks)**

Welcome to your first engineering assignment at BCHSoftware. Management has commissioned your project team to develop a secure, user-validated terminal greeting interface. This tool will lay the foundation for our future internal telemetry and clock-in systems.

---

## 📋 1. Project Objective & Requirements

Your team must collaborate asynchronously to ship a single, stable Python program named `main.py`. The final script must run without throwing runtime syntax exceptions or crashing when handled by a standard user.

### Functional Acceptance Criteria:
1. **System Initialization:** The program must display a clear, professional visual interface to the user immediately upon boot.
2. **Data Capture:** The system must prompt the user to input their name and securely store it in a system memory variable.
3. **Identity Verification:** The system must analyze the input. If the field is left entirely empty (null entry), the program must intercept the request, flag an error, and prevent a database system crash.
4. **Console Payout Report:** If the data is valid, the program must generate a clean, formatted confirmation printout acknowledging the employee.

---

## 💼 2. Departmental Assignment Tickets

Every associate must check the project board, claim their respective department card, and deliver their specific technical artifact into the `main.py` code stubs.

### 🎨 Web / UX Designer
* **Mission Directive:** Interface Ergonomics & Console Layout.
* **Sprint Task:** Design a multi-line corporate greeting banner using standard characters (e.g., asterisks `***` or hyphens `---`) to serve as an structural frame. 
* **Deliverable:** Provide the formatted string assets and layout design text to your team's Software Developer.

### 🛠️ Software Developer
* **Mission Directive:** Backend Logical Engineering.
* **Sprint Task:** Declare the core system variables and write the active `input()` capture logic. You are responsible for weaving the UX Designer's layout strings into the active Python print parameters.
* **Deliverable:** Build the foundational input/output codebase framework within `main.py`.

### 🛡️ Cybersecurity Specialist
* **Mission Directive:** Input Validation & Threat Mitigation.
* **Sprint Task:** Implement a conditional logic gate (`if/else`) that monitors the developer's input variable. If a user presses "Enter" without typing characters, your code block must intercept the empty string, print a secure warning message, and halt execution.
* **Deliverable:** Complete the defensive validation block to secure the variable pipeline.

### 🧪 Quality Assurance (QA) Engineer
* **Mission Directive:** Operational Integrity & Stress Testing.
* **Sprint Task:** Create a manual "Boundary Test Matrix" spreadsheet. You must test the developer's active script against 3 distinct user profiles: standard alphanumeric names, symbols/numbers, and complete null (empty) inputs. 
* **Deliverable:** Log any script bugs on the PM's project board, and issue a formal Quality Certification signature once all test parameters pass cleanly.

### 💼 Project Manager (PM)
* **Mission Directive:** Sprint Velocity & Blockade Resolution.
* **Sprint Task:** Initialize your team's Kanban board. Translate these README requirements into role-specific issue cards, monitor branch activity, and manage the team's internal documentation updates.
* **Deliverable:** Coordinate the daily team standup logs and submit the finalized repository URL to the Instructor once QA clears the build.

---

## 🛠️ 3. Standard Operating Procedures (SOP)

To maintain codebase compliance, teams are strictly forbidden from writing code directly on the `main` production branch. 

1. **Branch Isolation:** Before writing code, checkout a unique feature branch named with your role prefix and Employee ID:
   ```bash
   git checkout -b feature/UX-ID1009
