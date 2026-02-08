# Manual Testing Assessment: E-Commerce Search & Checkout Flow

## 👤 Candidate Information
* **Name:** Adnan Rahman
* **Course:** Software Quality Assurance (SQA)
* **Domain:** E-Commerce (Manual & API Testing)

---

## 📌 Project Overview
This project demonstrates a complete manual testing lifecycle for a "Dynamic Search" feature on an e-commerce platform. It covers requirement gathering, test case design, execution on the **Evershop** demo site, and a deep-dive analysis into a critical bug discovered during the UI and API validation phases.

## 📁 Repository Structure
* **Q1:** Stakeholder Questionnaire (Requirements Gathering)
* **Q2:** Test Case Documentation
* **Q3:** Execution Report & Result Link
* **Q4:** End-to-End (E2E) Journey Analysis & Bug Logging (UI vs API)

---

## 🔍 Task Highlights

### 1. Requirements Discovery
Before testing, I prioritized 10 strategic questions to define the "Dynamic Search" scope, covering keyword logic, auto-correction, and stock status filters.

### 2. Test Execution & Reporting
Executed 10 comprehensive test cases. 
* **Full Execution Report:** [View Google Sheets Report](https://docs.google.com/spreadsheets/d/1hw3wAtnZVzPs6NcZUqjwWl6qNu6PYwVPimTgwsQJWXc/edit?usp=drive_link)

### 3. Critical Bug Analysis (Nike React Journey)
During the "Happy Path" testing for the keyword **"Nike react"**, I identified a major mismatch between user selection and cart output.

**Technical Investigation:**
* **UI Issue:** Selecting **Black/M** or **Pink/M** mistakenly renders and adds **Purple/L** to the cart.
* **API Validation:** Using Postman, I confirmed that the backend response reflects the wrong variant, indicating a data-mapping or API logic error rather than a purely visual glitch.

---

## 🐞 Bug Log: Variant Mismatch
* **Severity:** Major | **Priority:** High
* **Issue:** Selecting specific shoe variants (Black/Pink in Size M) defaults to Purple/Size L in the cart.
* **Evidence:** Detailed logs and screenshots are available in the `/Evidence` folder.
* **API Logs:** [View JSON Response](https://drive.google.com/file/d/1lyLMGt05NkL_mS12VHxIS7hqSfYZN1Pk/view?usp=sharing)

---

## 🛠 Tools Used
* **Test Management:** Google Sheets
* **API Testing:** Postman
* **Environment:** Chrome, Windows 10
* **Platform Under Test:** [Evershop Demo](https://demo.evershop.io/)
