# **Test Management with Excel**

## **Objectives:**

- Develop a comprehensive test plan, ensuring alignment with project goals and stakeholder expectations, for all testing activities including scope, objectives and resources.

- Develop effective and detailed test case document that cover functional and non-functional requirements, ensuring thorough test coverage and clear, reproducible steps for testing and a requirement traceability matrix report.

- Utilize Excel in the test management

- Manage defects using excel to log, prioritize and track bugs.

---

## **Projects:**

### Overview

The [Product Store](https://www.demoblaze.com/index.html) is an e-commerce platform designed to provide customers with a seamless online shopping experience. Customers can browse and purchase a variety of products available on the website. Key features include:

- **Product Browsing:** Customers can explore a wide range of products with detailed descriptions, prices, and images.

- **Shopping Cart:** Customers can add products to their cart, review their selections, and proceed to place orders.

- **Order Placement:** Once products are added to the cart, customers can complete their purchase through a secure order process.

---

## **User Stories:**

### **User Story 1: Homepage**

As a Customer, I want to visit the homepage so that I can access and browse the available products.

**Acceptance Criteria**

1. The homepage should load quickly and be accessible to all users without requiring login.

2. The homepage should display a clear and intuitive layout with navigation options such as home, contact, cart, and login.

3. Each product should display essential details, such as:

   a. Product name

   b. Price

   c. Thumbnail image

4. When a customer clicks on a product name, they should be directed to a detailed product page displaying the full description, price, images, and an "Add to Cart" button.

---

### **User Story 2: Cart**

As a Customer, I want to add products to my cart, view the total cost, and manage items in my cart so that I can prepare for checkout.

**Acceptance Criteria**

1. Customers should be able to click the "Add to Cart" button on a product page to add the product to their cart.

2. After adding a product, the system should provide immediate feedback (e.g., a notification or message like "Product added to cart").

3. The cart page should display the total cost of all products added, calculated dynamically as items are added or removed.

4. Customers should be able to add the same product to the cart multiple times, increasing the quantity of that product in the cart.

5. Customers should be able to delete a product from the cart.

6. When a product is removed, the cart should update immediately, removing the item and adjusting the total cost.

7. The cart page should include a "Place Order" button for customers ready to complete their purchase.

---

### **User Story 3: Place an Order**

As a Customer, I want to place an order after adding products to my cart so that I can complete my purchase.

**Acceptance Criteria**

1. Customers should be able to click a "Place Order" button on the cart page to initiate the order process.

2. The "Place Order" button should only be enabled if there are products in the cart. If the cart is empty, the button should be disabled or hidden.

3. Upon clicking "Place Order," a form should be displayed for the customer to fill out.

4. The form should include the following fields:

   a. Name (compulsory): Should accept only alphabetic characters (no numbers or special characters).

   b. Credit Card Information (compulsory): Should accept only numeric characters and follow standard credit card format validation of 16 digits.

   c. Optional Fields: Additional fields like shipping address, phone number, or special instructions (if applicable).

5. Credit card information should be securely processed and not stored in plain text.

6. Upon successful submission of the form, the system should display an order confirmation page.

---

## **Grading Scheme**

| **METRIC** | **SCORE** | **TOTAL** |
| --- | --- | --- |
| Develop a comprehensive Test Plan document for the project. | 15 | 100 |
| Test case development — Test Case ID, Test Scenario, Test Case, Test Data, Test Execution Steps, Expected Results, Actual Results, Status (Pass/Fail) | 50 |  |
| Requirement Traceability Matrix Report — Requirement ID, Description, Requirement Source, Test Case ID, Test Case Description, Test Status, Defect ID (where applicable) | 15 |  |
| Defect Management — Bug ID, Bug Description, Steps to Reproduce, Expected Results, Actual Results, Environment, Severity, Priority, Status, Assignee | 20 |  |
