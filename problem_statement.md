# Insurance Policy Management Platform

## 1. Title

**Insurance Policy Management Platform**

## 2. Domain

**Insurance & Financial Services**

## 3. Who is the User?

The platform will mainly be used by the following users:

1. **Customer / Policyholder** – Can register, view insurance policies, purchase policies, pay premiums, and track claims.
2. **Insurance Agent** – Can manage customers, recommend suitable policies, assist with policy applications, and track customer policies.
3. **Administrator** – Manages insurance products, customers, agents, policies, payments, and claims.

## 4. What Problem Are We Solving?

Managing insurance policies manually can be time-consuming and may lead to difficulties in tracking policy details, premium payments, renewals, and claims. Customers may not have a centralized platform to view their policies and payment status. Insurance agents and administrators also need an efficient system to manage customer information and policy records.

**Real-life example:** A customer may forget the premium due date of their health insurance policy and miss the payment, resulting in policy-related issues. The proposed platform provides reminders and centralized policy information to help avoid such problems.

## 5. Proposed Solution

The **Insurance Policy Management Platform** will provide a centralized system for managing insurance policies and customer activities.

### Key Features:

* **User Registration & Login** – Secure authentication for customers, agents, and administrators.
* **Policy Management** – Add, update, view, and manage different insurance policies.
* **Policy Search & Selection** – Customers can search and compare available policies based on their requirements.
* **Policy Purchase** – Customers can apply for and purchase suitable insurance policies.
* **Premium Management** – Track premium amounts, payment status, and upcoming due dates.
* **Renewal Management** – Notify customers about upcoming policy renewals.
* **Claim Management** – Customers can submit claims and track their claim status.
* **Agent Management** – Agents can manage assigned customers and their policies.
* **Admin Dashboard** – Administrators can manage users, policies, payments, and claims.
* **Notifications & Reminders** – Send reminders for premium payments, renewals, and claim updates.
* **Reports** – Generate basic reports related to policies, customers, premiums, and claims.

## 6. Core Entities / Database Tables

The main database tables will be:

1. **Users** – Stores customer, agent, and administrator details.
2. **Insurance_Policies** – Stores policy information such as policy type, coverage, premium, and duration.
3. **Policy_Holders** – Stores the relationship between customers and their policies.
4. **Premium_Payments** – Stores premium payment details and payment status.
5. **Claims** – Stores insurance claim details and claim status.
6. **Agents** – Stores insurance agent information.
7. **Policy_Documents** – Stores policy-related document details.
8. **Notifications** – Stores reminders and notification information.

## 7. User Roles & Permissions

### 1. Customer / Policyholder

* Register and login.
* View available insurance policies.
* Apply for and purchase policies.
* View active and expired policies.
* Make and track premium payments.
* Receive renewal reminders.
* Submit and track insurance claims.
* View policy documents.

### 2. Insurance Agent

* Login to the system.
* View assigned customers.
* Add and manage customer policy applications.
* Recommend suitable insurance policies.
* Track customer policies and claims.
* View payment and renewal status.

### 3. Administrator

* Manage customers and agents.
* Add, update, and remove insurance policies.
* Manage policy applications.
* Monitor premium payments.
* Approve or reject claims.
* Manage notifications and system reports.
* View overall platform statistics.

## 8. Success Criteria

The application will be considered successful if:

* A user can **register and login within 1 minute**.
* A customer can **find and view a suitable insurance policy within 2 minutes**.
* A customer can easily **view policy and premium details from a single dashboard**.
* Premium due dates and policy renewals are **clearly displayed with reminders**.
* A customer can **submit and track a claim online** without manual processing.
* Administrators can efficiently manage policies, users, payments, and claims from a centralized dashboard.
* The system maintains **accurate and secure insurance records**.

## 9. Out of Scope

The following features will **not be included** in the initial version:

* Real-time integration with external insurance companies.
* Actual bank/payment gateway integration.
* Automated medical diagnosis or risk assessment using AI.
* Physical verification of customers or documents.
* Legal and regulatory decision-making.
* Insurance premium calculation using real-time external market data.
* Mobile application development; the initial system will focus on the web platform.
* Integration with government databases or external identity-verification services.

## 10. Chosen Track

**Java – Spring Boot**

### Technology Stack:

* **Backend:** Java, Spring Boot
* **Frontend:** HTML, CSS, JavaScript / React
* **Database:** MySQL
* **API:** REST APIs
* **Security:** Spring Security
* **Development Tools:** IntelliJ IDEA / VS Code, Git & GitHub

### Final Project Objective

The main objective of the **Insurance Policy Management Platform** is to provide a secure and centralized digital solution for managing insurance policies, customers, premiums, renewals, and claims, thereby reducing manual work and improving the overall insurance management experience.
