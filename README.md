# 🏛️ Procurement Management Monitoring System (PMMS)

> ** Information Technology Division**

A web-based government procurement lifecycle management system built on **AppGini**, covering the complete workflow from initial purchase request through asset registration and closure.

---

## 📋 Overview

PMMS digitises and enforces governance over the entire government procurement process in compliance with Sri Lanka Government Procurement Guidelines. It replaces manual, paper-based workflows with a centralised, auditable, and role-secured platform.

**Procurement stages tracked:**
`Request Submitted` → `Technical Review` → `Approval` → `Bid Calling` → `Bid Submission` → `Bid Opening` → `Bid Evaluation` → `Bidder Selected` → `Bond Verification` → `Agreement Signed` → `PO Issued` → `Delivered` → `Inspection` → `Payment` → `Inventory Updated` → `Closed`

---

## 🗂️ System Modules

| Module Group | Sub-Modules |
|---|---|
| **Procurement Section** | Requests, Request Items, Technical Evaluations, Approvals |
| **Tender / Bid Management** | Bid Calls, Submissions, Openings, Evaluations, Selected Bidders, Bonds, Contracts |
| **Procurement Execution** | Purchase Orders, Deliveries / GRN, Inspection, Payments |
| **Asset Section** | IT Assets, Warranty Management |
| **Administration** | Committees, Users & Roles, Audit Trail, Document Repository |

---

## 🗃️ Key Database Tables

- `procurement_requests` – Master request records with 18-stage status tracking
- `bid_calls` – Bid invitation management (Open Tender, Quotation, Direct Procurement, etc.)
- `bid_submissions` – Supplier bid records with document uploads
- `bid_openings` – Official bid opening sessions with committee minutes
- `bid_evaluations` – Technical and financial evaluation scoring
- `selected_bidders` – Final approved supplier selection records
- `performance_bonds` – Bid bonds, performance bonds, and advance payment bonds
- `contracts_agreements` – Contract lifecycle and document management
- `procurement_committees` – Government committee appointment tracking
- `audit_trail` – Immutable system-wide change log
- `documents` – Centralised document repository (bids, GRN, invoices, agreements)

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | AppGini (PHP) |
| Database | MySQL |
| Backend | PHP with custom hook system |
| Frontend | Bootstrap (Slate theme), JavaScript, Chart.js |
| Access | Role-based, browser (LAN / Intranet) |

---

## 🔐 User Roles

`Director ` · `Procurement Officer` · `Technical Evaluator` · `Finance Officer` · `Store / GRN Officer` · `Committee Member` · `System Administrator`

---

## 📊 Director IT Dashboard

Real-time KPI cards for:
- Active tenders · Pending evaluations · Unverified bonds
- Contracts expiring within 30 days · Delayed deliveries · Pending payments

---

## 📁 Document Management

Supports upload and tracking of: bid documents, opening minutes, evaluation sheets, bond copies, signed agreements, purchase orders, GRN documents, invoices, appointment letters, and inspection reports.

---

## 🏗️ Implementation Phases

| Phase | Scope | Duration |
|---|---|---|
| 1 | Core procurement (requests, approvals, suppliers) | 3 weeks |
| 2 | Tender & bid management | 4 weeks |
| 3 | Contract & bond management | 3 weeks |
| 4 | Execution (PO, GRN, inspection, payment) | 3 weeks |
| 5 | Asset & warranty registration | 2 weeks |
| 6 | Dashboard & reporting | 2 weeks |
| 7 | Audit trail, RBAC, document management | 2 weeks |
| 8 | UAT & deployment | 3 weeks |

---

*Internal use only —  Information Technology Division*
