# CanvasSelenium
Canvas SQCM Assignment
**README.md for Selenium Test Automation Assignment**

**Purpose:**
Automate NEU portal interactions for seamless testing using Selenium with Maven, featuring data-driven testing, automated screenshot capture, and HTML report generation.

**Requirements:**
1. Use Maven and add dependencies to `pom.xml`.
2. Capture screenshots before and after each step, saving them in a folder named after the scenario.
3. Automate scenarios consecutively without manual intervention.
4. Choose Java or Python for scripting.
5. Implement correct Assertions as needed.
6. Utilize a Data-Driven Automation Framework without hard-coded values.
7. Generate an HTML report with columns for Test scenario name, Actual, Expected, and Pass/Fail.
8. For two-factor authentication, manually hit the enter key once during the session.

**Team Presentations:**
1. Upload a script copy to Canvas before the class.
2. Presentations should be under 10 minutes, demonstrating seamless script execution.
3. One representative demos the script, and all group members actively participate.
4. Ensure the script runs without interruptions or manual intervention.

**Test Scenarios:**
- **Scenario 1: Download the latest transcript**
    - NEU portal login
    - Student Hub portal launch
    - Navigate to Transcripts and download as PDF

- **Scenario 2: Add two To-Do tasks**
    - Canvas login
    - Open Calendar and iteratively add 2 events from external Excel data

- **Scenario 3: Download a classroom guide**
    - NEU service login
    - Select classroom and download Quick Guide PDF

- **Scenario 4: Download a DATASET**
    - Navigate to Digital Repository Service, open dataset, and download ZIP file

- **Scenario 5: Update the Academic calendar**
    - Navigate to NEU Student Hub
    - Open Academic Calendar, uncheck a checkbox, and verify "Add to My Calendar" button

**Instructions for Execution:**
1. Ensure Maven is installed (`mvn clean install`).
2. Execute the scripts consecutively.
3. Monitor the automated process.
4. Review HTML reports for Pass/Fail status.

**Notes:**
- Follow good coding practices, including comments in the code.
- Utilize an external data sheet (e.g., Excel) for any necessary data; avoid hard-coded values.

**Additional Comments:**
Feel free to explore alternative reporting methods. All scripts should run seamlessly during presentations with minimal manual intervention, except for the two-factor authentication, where manually hitting the enter key once is acceptable.
