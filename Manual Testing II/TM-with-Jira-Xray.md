# **Test Management with Jira - Xray**

## **Project Overview**

The XYZ Bank app is a digital banking platform designed to serve two primary user groups: **customers** and **bank managers**.

- **For Customers**: The app provides essential banking functionalities, including the ability to log in securely, deposit funds, withdraw money, and access other account-related services. This ensures a convenient and efficient banking experience for users.

- **For Bank Managers**: The app offers administrative capabilities, allowing managers to add new customers, create accounts, and delete accounts as needed. This streamlines customer management and enhances operational efficiency.

---

## **Project Objectives**

- Develop a comprehensive test plan, ensuring alignment with project goals and stakeholder expectations, for all testing activities including scope, objectives and resources.

- Develop effective and detailed test case document that cover functional and non-functional requirements, ensuring thorough test coverage and clear, reproducible steps for testing.

- Utilize Jira - Xray in the test management

- Manage defects using Jira - Xray to log, prioritize and track bugs.

---

## **Requirements:**

- Develop a test plan for the project.

- Perform manual test on the application.

- Manage your test using Jira - Xray.

Access the bank app here: [XYZ Bank App](https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login)

---

## **User Stories:**

### **User Story 1:**

**As a Bank Manager, I want to add customers, create accounts, and delete accounts so that I can manage customer accounts efficiently.**

**Acceptance Criteria:**

- **Adding Customers:**

  - The system should allow bank managers to add new customers.

  - Customer names should only contain alphabetic characters (no numbers or special characters).

  - Postal codes should only contain numeric characters.

- **Creating Accounts:**

  - Bank managers should be able to create accounts for customers who have been added to the system.

  - Customers should not be able to access their accounts until an account has been created by a bank manager.

- **Deleting Accounts:**

  - Bank managers should be able to delete customer accounts.

  - When an account is deleted, the associated customer should no longer be able to access the account.

---

### **User Story 2:**

**As a Customer, I want to view my transactions, deposit funds, and withdraw money so that I can manage my finances effectively.**

**Acceptance Criteria:**

- **Viewing Transactions:**

  - Customers should be able to view a list of their recent transactions.

- **Depositing Funds:**

  - The system should allow customers to enter the deposit amount.

  - The system should validate the deposit amount (e.g., positive value).

  - Upon successful deposit, the system should update the account balance.

- **Withdrawing Money:**

  - Customers should be able to withdraw money from their account.

  - The system should allow customers to enter the withdrawal amount.

  - The system should validate the withdrawal amount (e.g., positive value, sufficient balance).

  - Upon successful withdrawal, the system should update the account balance.

- **Transaction Security:**

  - Customers should not be able to reset or alter their transaction history.

---

## **Grading Scheme**

| **METRIC** | **SCORE** | **TOTAL** |
| --- | --- | --- |
| Test plan document | 15 | 100 |
| Test case development — Use Jira Xray to generate test cases and link them appropriately. | 50 |  |
| Generate a Requirement Traceability Matrix Report using JIRA XRAY | 15 |  |
| Defect Management — Use Jira Xray to create bug issues and link them appropriately. | 20 |  |
