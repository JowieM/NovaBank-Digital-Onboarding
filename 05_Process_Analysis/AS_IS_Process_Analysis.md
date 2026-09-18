# AS-IS Process Analysis

## 1. Overview

The AS-IS analysis documents the current customer account-opening and onboarding process at NovaBank.

The current process relies on branch-based customer interaction and several manual activities.

The purpose of this analysis is to understand the current workflow, identify process participants and document pain points that may be addressed through the proposed digital onboarding solution.

---

## 2. Current Process

The current account-opening process follows these major steps:

1. Customer decides to open a bank account.
2. Customer visits a NovaBank branch.
3. Customer requests to open an account.
4. Customer receives an application form.
5. Customer completes the application form.
6. Customer provides required supporting documents.
7. Bank employee checks the submitted information.
8. Bank employee captures customer information into the banking system.
9. KYC Analyst verifies customer information and supporting documents.
10. Application is reviewed.
11. A decision is made.
12. If approved, the customer's account is created.
13. Customer is notified of the outcome.

---

## 3. AS-IS Process Participants

| Participant | Responsibility |
|---|---|
| Customer | Provides information and supporting documents |
| Customer Service Agent | Assists with account application |
| Bank Employee | Captures customer information |
| KYC Analyst | Performs customer verification |
| Branch Manager | Reviews and oversees applications |
| Compliance Officer | Provides compliance oversight |
| Banking System | Stores customer and account information |

---

## 4. Current Process Flow

```text
START
  |
  v
Customer wants to open account
  |
  v
Customer visits branch
  |
  v
Customer requests account
  |
  v
Application form provided
  |
  v
Customer completes form
  |
  v
Customer submits documents
  |
  v
Bank employee checks documents
  |
  v
Customer information captured
  |
  v
KYC verification
  |
  v
Application review
  |
  +-------------------+
  |                   |
  v                   v
Rejected            Approved
  |                   |
  v                   v
Customer            Account
notified            created
                      |
                      v
                  Customer
                   notified
                      |
                      v
                     END
