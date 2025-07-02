# Exercise08 – Homework 8

This folder contains the eighth homework assignment for the Manual Tester course (GoIT). The focus of this task is to apply practical testing knowledge by documenting real test cases and bug reports using dedicated testing tools.

## Documents

- [Homework 8 – Requirements](Requirements%20for%20Homework%208.pdf)  
  Specifies the task to create 5 test cases in **Qase** and 5 bug reports in **Jira**, using examples from previous homework exercises.

# Exercise 08 – Functional and UI Testing in Qase

This repository documents the test cases created for Homework 8 of the GoIT Manual Testing course. The tests are designed and managed using [Qase.io](https://qase.io), focusing on both functional and UI aspects of the assigned application.

## Objective

The goal of this exercise was to verify the functionality and behavior of an online educational coding platform through five distinct test cases. Each test was developed based on the detailed requirements outlined in the assignment PDF.

## Test Management Tool

All test cases were created and stored using Qase, a modern test management platform that facilitates the creation, organization, and tracking of test suites and defects.

## Test Cases Overview

The following test cases were implemented:

1. **TNG-1 – Codul existent nu se poate modifica**
   - Verifies that the existing code in the editor cannot be changed.
   - Ensures proper protection of predefined code blocks.

2. **TNG-2 – Schimba întrebarea**
   - Checks if the user can switch from question 1 to question 2 using the "right arrow" button.
   - Confirms the correct rendering and flow of question switching.

3. **TNG-3 – Verifică ordinea afișării întrebărilor**
   - Ensures the questions are displayed in order, starting with question 1.
   - Validates the default UI rendering and question sequencing.

4. **TNG-4 – Ascunde teoria corespunzător**
   - Tests whether the theory and task sections can be hidden properly.
   - Confirms that only the editor and result sections are visible after clicking the "Hide Theory and Tasks" button.

5. **TNG-5 – Verifică actualizarea rezultatelor**
   - Checks if the results update correctly after clicking the "Verify" button.
   - Ensures the editor is functional and results reflect the latest code changes.

## Supporting Documentation

The full assignment and test planning documents are included below:

- 📄 [Requirements for Homework 8](../Exercise08/Requirements%20for%20Homework%208.pdf) – contains detailed instructions and testing scope.
- 📸 Screenshots of all test cases as created in Qase:
  - [Repository Overview](../Exercise08/TNG%20_%20Repository%20_%20Qase.png)
  - [TNG-1 – Codul existent nu se poate modifica](../Exercise08/TNG%20_TestCase1.png)
  - [TNG-2 – Schimba întrebarea](../Exercise08/TNG%20_TestCase2.png)
  - [TNG-3 – Verifică ordinea afișării întrebărilor](../Exercise08/TNG%20_TestCase3.png)
  - [TNG-4 – Ascunde teoria corespunzător](../Exercise08/TNG%20_TestCase4.png)
  - [TNG-5 – Verifică actualizarea rezultatelor](../Exercise08/TNG%20_TestCase5.png)

## Conclusion

All test cases were executed in Qase with the goal of validating the user interface behavior and functional correctness of the platform. The structure, severity, priority, and test steps were carefully designed to align with the assignment requirements.

---

# Exercise08 – Bug Reports

This folder contains all documented bug reports for Homework 8 of the GoIT Manual Tester course. The bugs were identified during manual testing of an educational platform using the Qase test management system and reported in detail with screenshots and video evidence.

---

## 🐞 Bug Reports Overview

A total of **5 distinct bugs** were reported. Each bug includes:

- A unique identifier (Bug 1 to Bug 5)
- Screenshots illustrating the issue
- Descriptions of expected vs actual results
- Severity, priority, and steps to reproduce
- One video file to demonstrate a dynamic bug

---

## 🗂️ Files Included

### 🔹 Bug 1 – Display Issue in Theory Section
- `List - GoIT - Tema 8 - Bug 1.1.png`
- `List - GoIT - Tema 8 - Bug 1.2.png`
- `List - GoIT - Tema 8 - Bug 1.3.png`

*Description:* The theory block does not preserve line breaks or expected layout, making content harder to read.

---

### 🔹 Bug 2 – Inconsistent Navigation Behavior
- `List - GoIT - Tema 8 - Bug 2.1.png`
- `List - GoIT - Tema 8 - Bug 2.2.png`
- `List - GoIT - Tema 8 - Bug 2.3.png`

*Description:* Switching between questions sometimes causes layout flickering or empty task content to appear.

---

### 🔹 Bug 3 – Editor and Focus Problems
- `List - GoIT - Tema 8 - Bug 3.1.png`
- `List - GoIT - Tema 8 - Bug 3.2.png`
- `List - GoIT - Tema 8 - Bug 3.3.png`

*Description:* Clicking inside the editor occasionally doesn’t activate the cursor or focus correctly.

---

### 🔹 Bug 4 – "Hide Theory and Tasks" Function Fails
- `List - GoIT - Tema 8 - Bug 4.1.png`
- `List - GoIT - Tema 8 - Bug 4.2.png`
- `List - GoIT - Tema 8 - Bug 4.3.png`

*Description:* Repeated clicks on the "Hide Theory and Tasks" button do not always hide the expected content areas.

---

### 🔹 Bug 5 – Result Panel Not Updating
- `List - GoIT - Tema 8 - Bug 5.1.png`
- `List - GoIT - Tema 8 - Bug 5.2.png`
- `List - GoIT - Tema 8 - Bug 5.3.mp4` (video)

*Description:* After pressing the "Verify" button, the results do not update correctly or show a previous output.

---

### 📌 Jira Overview Screenshot
- `List - GoIT - Tema 8 - Jira.png`  
  *Shows all five bugs reported and tracked in Jira with statuses and priorities.*

---
