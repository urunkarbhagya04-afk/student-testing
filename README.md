
 Student Testing Project — Manual Testing using HerokuApp

This repository contains **manual testing work** performed on the sample web application  

It includes detailed test cases, screenshots, and a professional QA report to demonstrate real-world manual testing workflow.

 Project Structure

student-testing/
│
├── manual_testing/
│   ├── screenshots/          # Screenshots for all 10 test cases (TC001–TC010)
│   ├── manual_test_cases.csv # Test case list with execution results
│   ├── QA_Report.md          # Summary QA report and analysis
│
└── README.md                 # Project overview (this file)


Objective

The objective of this project is to perform **manual testing** on a web application  
to verify both positive and negative user flows.

The main areas tested include:
- Login and authentication
- Registration and form validation
- Navigation and UI checks
- Error message handling
- Access control and URL security


Tools & Environment

| Tool / Component | Description |
|------------------|--------------|
| **Operating System** | Ubuntu (Linux) |
| **Browser** | Google Chrome |
| **Application** | [https://the-internet.herokuapp.com](https://the-internet.herokuapp.com) |
| **Testing Type** | Manual Functional Testing |
| **Test Management** | CSV file tracking |
| **Evidence** | Screenshots |
| **Version Control** | Git & GitHub |
 Test Case Summary

| TC ID | Test Case Description                   | Result | Screenshot |
| ----- | --------------------------------------- | ------ | ---------- |
| TC001 | Verify valid login                      |  PASS | TC001.png  |
| TC002 | Verify invalid password                 |  PASS | TC002.png  |
| TC003 | Verify empty login fields               |  PASS | TC003.png  |
| TC004 | Verify registration with valid data     |  N/A | -          |
| TC005 | Verify registration with existing email |  N/A | -          |
| TC006 | Verify logout functionality             |  PASS | TC006.png  |
| TC007 | Verify form field validation            |  PASS | TC007.png  |
| TC008 | Verify navigation links                 |  PASS | TC008.png  |
| TC009 | Verify page load and UI alignment       |  PASS | TC009.png  |
| TC010 | Verify security for restricted URL      |  PASS | TC010.png  |



📋 QA Summary

Total Test Cases: 10
Passed: 8
Not Applicable (Registration pages not available)
Defects Found:** Minor UI alignment issue on homepage
Status: Overall Application Passed Basic Functional Checks


Author

Bhagyashree Urunkar
Manual Testing Practice Project
📧 Email: [urunkarbhagya04@gmail.com](mailto:urunkarbhagya04@gmail.com)
🗓️ Created: November 2025


