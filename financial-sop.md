---
layout: default
title: Financial SOP
---

# SOP: EU VAT Reconciliation Process

This Standard Operating Procedure ensures that all cross-border transactions comply with EU VAT Directive 2006/112/EC.

## Workflow
* **Extract:** Download monthly sales reports from Stripe.
* **Verify:** Cross-reference VAT IDs using the VIES database.
* **Reconcile:** Match bank deposits with recorded tax liabilities.
---
## 🧠 Process & Methodology: How I Built This SOP

As a Technical Writer, my goal was to bridge the gap between complex EU financial regulations and actionable internal workflows. Here is the process I used:

### **Phase 1: Regulatory Research**
* **Legal Deep-Dive:** Researched **EU VAT Directive 2006/112/EC** to identify the specific invoicing and verification requirements for cross-border B2B transactions.
* **Tool Audit:** Investigated the **VIES (VAT Information Exchange System)** database and **Stripe Reporting** API to understand how data is actually extracted and verified in a fintech environment.

### **Phase 2: Information Architecture**
* **Workflow Mapping:** Simplified the multi-stage tax process into a logical **3-step framework** (Extract, Verify, Reconcile) to ensure zero confusion for the finance team.
* **Task Analysis:** Identified the "Reverse Charge" mechanism as a key pain point and documented it as a priority verification step.

### **Phase 3: Technical Authoring (Docs-as-Code)**
* **Authoring:** Wrote the SOP in **Markdown** to ensure it is lightweight, portable, and easy for developers to integrate into the company's internal wiki.
* **Iterative Review:** Structured the document for "skimmability" using bold UI elements and hierarchical headings to reduce cognitive load during high-pressure audit seasons.
