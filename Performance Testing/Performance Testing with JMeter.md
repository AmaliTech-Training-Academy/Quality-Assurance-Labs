# **Performance Testing with JMeter**

## **Objective:**

The objective of this project is to assess the performance, scalability, and reliability of a web application under varying loads using JMeter. The performance test will simulate real-world scenarios to evaluate response times, throughput, and error rates. The goal is to identify bottlenecks and ensure the application meets performance requirements.

---

## **Project Scope**

- **Application Under Test (AUT):**

  [Swag Labs](https://www.saucedemo.com/) - user login, product search, product details page, cart functionality, and checkout.

- **Performance Goals:**

  - **Response Time:** Ensure response time is under 2 seconds for all critical transactions (product search, checkout, etc.).

  - **Throughput:** Ensure the application can handle 500 requests per second.

  - **Error Rate:** Ensure no more than 1% of requests result in errors under maximum load.

  - **Scalability:** Test the application under increasing loads to evaluate its scalability.

---

## **Project Phases:**

### **Test Planning and Design:**

- **Define Test Scenarios:**

  Identify the critical transactions and workflows in the application:

  - User login

  - Searching for a product

  - Viewing product details

  - Adding a product to the cart

  - Checkout process

- **Define Performance Metrics:**

  Specify the performance metrics (response time, throughput, error rate) for each scenario.

---

### **JMeter Test Setup:**

- **HTTP Request Samplers:**

  Configure HTTP Request Samplers in JMeter for each of the key scenarios identified (login, search, add to cart, and checkout).

- **Thread Groups:**

  Define thread groups to simulate different user loads:

  - Light Load (50 users)

  - Medium Load (150 users)

  - Peak Load (300 users)

- **Timers:**

  Add timers between requests to simulate real user think times between actions.

- **Assertions:**

  Set up assertions to ensure the correct response (e.g., status code 200, text verification).

- **Listeners and Reporting:**

  Configure listeners (Summary Report, Aggregate Report) and enable generation of the **HTML Dashboard** for detailed test reports.

---

### **Execution of Performance Tests:**

- **Baseline Test:**

  Run the baseline test with a light load of 50 concurrent users.

- **Load Test:**

  Increase the load to 150 and then 300 users, evaluating the application's performance under higher traffic.

- **Stress Test:**

  Push the system beyond its capacity (e.g., 500 users) to determine the breaking point.

- **Endurance Test:**

  Run the test for an extended period to assess the application's ability to handle sustained load over time.

---

### **Monitoring and Analysis - Optional:**

- **Resource Monitoring:**

  Use server monitoring tools (e.g., Grafana, Prometheus) to monitor CPU, memory, and disk usage during the tests.

- **Analyze Results:**

  Analyze the response time, throughput, and error rate from the JMeter reports. Review the HTML Dashboard for detailed metrics.

---

### **Reporting:**

- **HTML Report Generation:**

  Generate and review the **HTML Dashboard** to get insights into the performance metrics, including:

  - Response time percentiles (90th, 95th)

  - Throughput over time

  - Error rates over time

- **Detailed Report:**

  Provide a detailed report on performance bottlenecks, including root cause analysis (e.g., slow database queries, server limitations).

---

### **CI/CD Integration**

- Automating performance tests in Jenkins pipelines or GitHub actions.

---

## **Deliverables:**

- Performance Test Plan Documentation

- JMeter Test Plan (.jmx file)

- HTML Dashboard Reports for each test run (baseline, load, stress, endurance)

- Final performance report summarizing:

  - Key performance metrics (response times, throughput, error rates)

---

## **Grading Scheme**

| METRICS | SCORE | TOTAL |
| --- | --- | --- |
| Performance Test Plan Documentation | 10 | 100 |
| JMeter Test Plan (.jmx file) | 50 |  |
| HTML Dashboard Reports for each test run (baseline, load, stress, endurance) | 20 |  |
| CI/CD Integration – Jenkins or GitHub Actions | 10 |  |
| Final performance report summary | 10 |  |
