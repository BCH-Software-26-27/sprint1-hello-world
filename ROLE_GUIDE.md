# 👑 Project Lead Ticket Creation Blueprint (Sprint 0: Hello World)

**Project Leads:** Use this document to initialize your team's workspace for Sprint 0. For each of the four departmental roles below, you must create a **New Issue** inside this GitHub repository, copy/paste the title and description text, and apply the required project tracking metadata.

## ⚙️ Mandatory Sidebar Settings for ALL Tickets:
* **Projects:** `BCH Corporate Operations Dashboard`
* **Status:** `Todo`
* **Custom Dropdowns:** Set your Class Section (Period), your unique Team Name, and set the Sprint field to `Hello World` or `Sprint 0`.

---

### 🎨 Ticket 1: Web / UX Designer
* **Title:** Hello World: Interface Ergonomics & Console Layout

**Description:**
### 🎨 Mission Directive
Interface Ergonomics & Console Layout.

### 📋 Sprint Task
Design a multi-line corporate greeting banner using standard characters (e.g., asterisks *** or hyphens ---) to serve as a structural frame.

### 🚀 Step-by-Step Action Items
1. Open the master project board, locate this card in "Todo", and move it to "In Progress".
2. Draft a clean ASCII text corporate header framework in a local text editor.
3. Open the `main.py` file in the GitHub web editor.
4. Locate the UX code stub block and paste your formatted string assets inside the designated variables.
5. Commit your changes directly to the `main` branch.
6. Hand off your variable layout string names to your team's Software Developer.

---

### 🛠️ Ticket 2: Software Developer
* **Title:** Hello World: Backend Logical Engineering

**Description:**
### 🛠️ Mission Directive
Backend Logical Engineering.

### 📋 Sprint Task
Declare the core system variables and write the active input() capture logic. You are responsible for weaving the UX Designer's layout strings into the active Python print parameters.

### 🚀 Step-by-Step Action Items
1. Move this card to "In Progress" on the master board once you begin your work block.
2. Coordinate with your UX Designer to get their layout string variable names.
3. Open `main.py` in the GitHub web editor.
4. Inside the Developer code stub, declare your variables and write the input capture function to receive user data.
5. Combine the UX layout frames with your active Python print() parameters so the application outputs a cohesive interface.
6. Commit your changes directly to the `main` branch.

---

### 🛡️ Ticket 3: Cybersecurity Specialist
* **Title:** Hello World: Input Validation & Threat Mitigation

**Description:**
### 🛡️ Mission Directive
Input Validation & Threat Mitigation.

### 📋 Sprint Task
Implement a conditional logic gate (if/else) that monitors the developer's input variable. If a user presses "Enter" without typing characters, your code block must intercept the empty string, print a secure warning message, and halt execution.

### 🚀 Step-by-Step Action Items
1. Move this card to "In Progress" on the master board.
2. Review the variable name the Software Developer used to capture user inputs in `main.py`.
3. Open `main.py` in the GitHub web editor and locate the Cybersecurity code stub block.
4. Write a defensive conditional logic statement checking if the input variable equals an empty string "".
5. Add a secure print warning message within the empty string condition.
6. Commit your changes directly to the `main` branch.

---

### 🧪 Ticket 4: Quality Assurance (QA) Engineer
* **Title:** Hello World: Operational Integrity & Stress Testing

**Description:**
### 🧪 Mission Directive
Operational Integrity & Stress Testing.

### 📋 Sprint Task
Create a manual "Boundary Test Matrix" spreadsheet. You must test the developer's active script against 3 distinct user profiles: standard alphanumeric names, symbols/numbers, and complete null (empty) inputs.

### 🚀 Step-by-Step Action Items
1. Move this card to "In Progress" on the master board.
2. Create a 3-row test spreadsheet capturing: User Profiles (alphanumeric, symbols, null), Expected Output, and Actual Output.
3. Run and test the compiled code in `main.py` against all three profiles.
4. If a bug or system crash occurs, document it on the project board and alert the developer.
5. Once all three test parameters pass cleanly without system errors, type your digital signature into the QA section of `main.py`.
6. Commit your verification to `main` and drag this card to "Done".

---

## 🐍 Target Blueprint: `main.py` Code Stubs
Note to Project Leads: Ensure your repository contains a `main.py` file populated with these starting comments so your associates can locate their production code lines.

```python
# =========================================================================
# SPRINT 1: CORE CORPORATE SYSTEM CORE (HELLO WORLD)
# =========================================================================

# [🎨 UX/WEB DESIGNER STUB] - Define your layout framing strings here
UX_HEADER_BORDER = ""
UX_FOOTER_BORDER = ""


# [🛠️ SOFTWARE DEVELOPER STUB] - Initialize logic, variables, and user input
def run_corporate_login():
    print(UX_HEADER_BORDER)
    # Write your input capture statement below:
    user_name = "" 
    
    
    # [🛡️ CYBERSECURITY SPECIALIST STUB] - Insert input validation check
    # Write an if/else conditional check to intercept blank string inputs:
    
    
    # [🛠️ DEVELOPER OUTPUT CONTINUE] - Compile layout elements with variables
    print(f"System Authorization Successful. Welcome back, {user_name}.")
    print(UX_FOOTER_BORDER)


# [🧪 QUALITY ASSURANCE SIGN-OFF]
# Type your name below once the 3-point boundary test matrix passes 100%:
QA_CERTIFICATION_SIGNATURE = "PENDING_REVIEW"

# Trigger Application Run
run_corporate_login()
