# Demo Web Shop — Manual Testing Project

A complete manual testing portfolio project performed on the **Demo Web Shop** (sample e-commerce application by Tricentis), built to demonstrate practical QA skills including test case design, exploratory testing, bug reporting, and requirement traceability.

---

## 📌 Project Overview

This project simulates a real-world QA engagement on an e-commerce platform. The objective was to independently plan, design, and execute manual test cases across key modules of the application, identify defects, document them professionally, and maintain full testing artifacts — the same way a QA Tester would in an actual product team.

---

## 🌐 Application Under Test (AUT)

**Application:** Demo Web Shop
**URL:** [https://demowebshop.tricentis.com](https://demowebshop.tricentis.com)
**Type:** Sample E-Commerce Web Application (built on nopCommerce)
**Provided by:** Tricentis (for public QA practice and training purposes)

---

## 🎯 Testing Scope

- Functional testing of core e-commerce flows (Browse, Cart, Checkout, Account)
- UI/UX validation and usability observations
- Cross-browser sanity checks
- Negative and boundary testing on forms and inputs
- Defect identification, classification, and reporting

**Out of Scope:** Performance testing, security/penetration testing, backend/database testing, automated test execution

---

## 🧩 Modules Tested

| Module | Description |
|---|---|
| Books | Product listing, sorting, filtering, Add to Cart |
| Computers | Category browsing, product comparison |
| Electronics | Product listing and detail pages |
| Shopping Cart | Add/remove items, quantity updates, totals |
| Checkout | Guest checkout, address, payment flow |
| Register / Login | Account creation, authentication, validation |
| Search | Store-wide search functionality |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Browser DevTools | UI inspection, responsive checks |
| Excel / Markdown | Test case and bug documentation |
| GitHub | Version control & portfolio hosting |
| Screenshots (Snipping Tool) | Visual defect evidence |
| ChatGPT / Claude AI | Assisted in structuring documentation and brainstorming test scenarios |

---

## 🔍 Key Findings and Observations

- Some product listings (Books module) do not show an **"Add to Cart"** button and provide no stock-status message — flagged as a UI/UX issue (see [Suggestions](./Suggestions/UI-UX-Improvements.md))
- Site allows further testing of form validations on Register/Login pages
- Cart and pricing calculations were verified to be accurate across tested scenarios

*(This section is updated continuously as testing progresses.)*

---

## 📁 Repository Structure

```
Demo-Web-Shop-Manual-Testing-Project/
│
├── README.md
├── Test-Scenarios/
│   └── Test-Scenarios.md
├── Test-Cases/
│   └── Test-Cases.md
├── Bug-Reports/
│   └── Bug-Reports.md
├── RTM/
│   └── Requirement-Traceability-Matrix.md
├── Suggestions/
│   └── UI-UX-Improvements.md
└── Screenshots/
    ├── Defects/
    └── Observations/
```

---

## 👩‍💻 About Me

**Monika Yadav**
QA Tester | Manual Testing | Fresher
🔗 [LinkedIn](https://www.linkedin.com/in/monikayadav10)

This project is part of my QA testing portfolio, built to apply manual testing concepts on a live application as a fresher transitioning into Quality Assurance.
