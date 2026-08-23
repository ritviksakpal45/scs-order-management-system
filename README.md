# Star Convenience Store (SCS) - Order Management System (OMS) Digital Transformation
**Lead Business Analyst:** Ritvik Sakpal  
**Project Status:** Completed / Portfolio-Ready  
**Domain:** Retail POS, Closed-Loop Replenishment, & Inventory Management  

---

[![Business Analysis](https://img.shields.io/badge/Role-Lead%20Business%20Analyst-blue.svg)](https://github.com/)
[![Project Status](https://img.shields.io/badge/Project%20Status-Completed%20%2F%20Portfolio-green.svg)](https://github.com/)
[![Methodology](https://img.shields.io/badge/Methodology-Agile%20%2F%20BDD-orange.svg)](https://github.com/)

---

## 📌 Executive Summary & Business Problem
Star Convenience Store (SCS) is an established neighborhood retailer with over 13 years of successful operation. Recently, SCS experienced an unprecedented surge in daily customer footfall, **jumping from an historical baseline of 200–250 patrons to over 1,000–1,200 daily customers.**

Because daily checkouts, sales logging, and inventory tracking were handled entirely via manual, paper-based registers, the store’s infrastructure collapsed under this increased demand:
* **Counter Friction:** Manual cash register calculations created severe bottlenecks, long wait times, and frequent human billing errors.
* **Inventory Blindness:** Real-time stock levels were completely untracked, forcing staff to rely on ad-hoc visual shelf checks.
* **Financial Loss:** High-velocity essentials (dairy, fresh bread, eggs, popular packaged snacks) frequently stocked out, leading to severe **revenue leakage** and capping quarterly growth at **exactly 4% against a 15% market potential**.
* **Labour Overhead:** Retail associates spent over **six (6) hours weekly** manually reconciling handwritten paper logs against physical shelf counts and distributor paper invoices just to catch low stock.

## 🚀 The Solution: SCS Order Management System (OMS)
This project outlines the end-to-end digital transformation of Star Convenience Store through the implementation of a centralized, real-time **Order Management System (OMS)** integrated with a barcode-enabled POS terminal. 

This modern system synchronizes front-counter checkouts with back-end inventory levels, automates low-stock notifications, and introduces a **closed-loop replenishment cycle** with local distributors. It reduces manual weekly reconciliation time from **six hours to under 30 minutes** while reclaiming the store’s 15% annual growth potential.

---

## 📂 Repository Directory Structure
This repository contains a professional, end-to-end suite of product management and business analysis artifacts, structured to mirror real-world corporate delivery lifecycles:

```text
scs-order-management-system/
│
├── README.md                                 # Project landing page and portfolio overview
│
├── 01-business-case/
│   ├── SCS-Business-Case.pdf                 # Financial justification, root cause analysis, and ROI
│   └── SCS-Business-Case.docx
│
├── 02-elicitation/
│   ├── SCS-Business-Requirements-Elicitation.pdf  # Interview notes & detailed findings with stakeholders
│   └── SCS-Business-Requirements-Elicitation.docx
│
├── 03-process-analysis/
│   ├── SCS-Current-State-L1-Flow.svg         # High-level current manual transaction flow
│   ├── SCS-Future-State-L1-Flow.svg         # High-level future automated transaction flow
│   ├── SCS-AS-IS-BPMN-Swimlane.svg          # BPMN 2.0 modeling of the manual paper bottlenecks
│   └── SCS-TO-BE-BPMN-Swimlane.svg          # BPMN 2.0 modeling of the target digital automated state
│
├── 04-use-cases/
│   ├── SCS-Use-Case-Document.pdf            # Functional actor-system boundary descriptions
│   └── SCS-Use-Case-Document.docx
│
├── 05-brd/
│   ├── SCS-Business-Requirements-Document.pdf  # Master BRD with high-level business rules & scope
│   └── SCS-Business-Requirements-Document.docx
│
└── 06-prd/
    ├── SCS-Product-Requirements-Document.pdf  # Master Agile PRD with Gherkin User Stories
    └── SCS-Product-Requirements-Document.docx
```

---

## 🛠️ Artifact Delivery Lifecycle Summary

### 📊 [01] Business Case
Provides the commercial and operational justification for the digital transformation. It performs a rigorous root-cause analysis of the store's 11% point gap, details the quantified business impacts, and establishes the "As-Is" vs. "To-Be" strategic vision.

### 🗣️ [02] Elicitation Findings
Logs the structured stakeholder interviews conducted with the Store Owner and three Retail Associates. These notes detail the day-to-day transaction workflows, visual audit methods, payment processing mechanics, and existing paper-based ledger systems.

### 🗺️ [03] Process Analysis (BPMN 2.0)
Visualizes the operational workflows using professional BPMN 2.0 swimlane diagrams:
* **AS-IS Swimlane:** Highlights the severe bottlenecks in paper-based transaction logging and manual supplier reordering.
* **TO-BE Swimlane:** Models the streamlined, automated checkout, real-time Product Master stock decrements, and automatic distributor PO routing.

### 🎭 [04] Use Cases
Bridges the gap between strategic business objectives and technical implementation. It defines the exact boundaries, primary/alternative flows, pre-conditions, and post-conditions for key actors (Store Owner, Retail Associate, and Distributor) interacting with the OMS.

### 📝 [05] Business Requirements Document
Establishes the official scope boundaries, critical business rules, and technical objectives. Highlights:
* **Scope Control:** Explicitly defines out-of-scope boundaries (e.g., active Customer Udhaar credit ledger tracking, employee payroll) to prevent scope creep.
* **Core Business Rules:** Defines `BR-01` (low-stock threshold controls), `BR-02` (checkout transaction compliance), and `BR-03` (automated closed-loop replenishment).

### 📋 [06] Product Requirements Document
Translates high-level business requirements into an executable, Agile-ready Product Backlog. It comprises **10 complete, prioritized features** documented in standard User Story format with highly detailed, executable **Gherkin (Given-When-Then) Acceptance Criteria**:
1. **Feature 1:** POS Barcode Scanning (with dirty/torn barcode fallback).
2. **Feature 2:** Variable-Weight Scale Support (integrated checkout pricing calculation).
3. **Feature 3:** Manual Product Lookup (for loose, unbarcoded goods).
4. **Feature 4:** Multi-Payment Type Logging (Cash, Card, UPI, and Udhaar stock-deductions).
5. **Feature 5:** Receipt Generation & Printing (with offline queue fallback).
6. **Feature 6:** Real-Time Stock Auto-Deductions.
7. **Feature 7:** Automated Low-Stock Notifications (Dashboard alerts & WhatsApp/SMS/Email).
8. **Feature 8:** Automated Draft PO Generation (grouped distributor-wise via `Target Max - Current Stock`).
9. **Feature 9:** Digital PO Transmission (direct vendor dispatch via WhatsApp Business API/Email/SMS).
10. **Feature 10:** Goods Receipt Note (GRN) Verification (with short delivery and damaged/rejected goods logging).

---

## 📈 Demonstrated Technical Skills
As a Lead Business Analyst, this portfolio demonstrates mastery across several critical software product ownership competencies:
* **Requirements Elicitation & Stakeholder Interviewing:** Translating raw human conversations into structured functional requirements.
* **Process Modeling (BPMN 2.0):** Visually mapping complex retail processes to identify and resolve process inefficiencies.
* **Agile Product Ownership:** Structuring backlogs, writing user stories, and establishing clear business value.
* **Behavior-Driven Development (BDD) & Gherkin:** Writing technical, standardized acceptance criteria ready for automated QA testing frameworks (e.g., Cucumber).
* **System Boundary Management:** Standardizing scope definitions, defining pre-conditions/post-conditions, and establishing technical constraints.

---

## 🤝 Let's Connect!

Thank you for exploring this project! I am always open to discussing digital transformation, retail systems architecture, agile product delivery, or potential professional opportunities. Feel free to reach out through any of the channels below:

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritviksakpal/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ritviksakpal45)
[![Email Badge](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ritviksakpal@gmail.com)

* **LinkedIn:** [linkedin.com/in/ritviksakpal](https://www.linkedin.com/in/ritviksakpal/)
* **GitHub Portfolio:** [github.com/ritviksakpal45](https://github.com/ritviksakpal45)
* **Email Direct:** [ritviksakpal@gmail.com](mailto:ritviksakpal@gmail.com)

*"Bridging the gap between manual business problems and scalable, digital product solutions."*
