Test Plan
QA Brains Practice Site Testing

Project Name: QA Brains Practice Site Testing

Application Under Test (AUT): QA Brains Practice Website

Version: 1.0

Prepared By: Mahbubul Islam

Document Version: 1.0

Test Type: Manual Testing

Date: July 2026

1. Introduction
Purpose

The purpose of this Test Plan is to define the testing strategy, objectives, scope, resources, schedule, and deliverables for the QA Brains Practice Site. The goal is to ensure that all core functionalities operate according to the specified requirements while providing a secure, reliable, and user-friendly experience.

2. Objectives

The objectives of testing are to:

Verify all functional requirements.
Validate UI consistency.
Ensure proper input validation.
Verify business workflows.
Detect defects before production.
Ensure compatibility across browsers.
Validate responsiveness on multiple screen sizes.
Improve overall application quality.
3. Scope
In Scope
Login
User Registration
Forgot Password
Form Submission
Drag & Drop
Product Listing
Product Details
Shopping Cart
Checkout
Order Summary
Navigation
Responsive Design
UI Validation
Error Messages
Browser Compatibility
Out of Scope
Production Deployment
Performance Testing
Penetration Testing
Database Performance
Third-party Payment Gateway Security
4. Test Items
Module	Testing Type
Login	Functional
Registration	Functional
Forgot Password	Functional
Forms	Functional + Validation
Product Module	Functional
Cart	Functional
Checkout	Functional
UI Components	UI Testing
Navigation	Usability
Responsive Layout	Compatibility
5. Test Strategy

The following testing types will be performed:

Functional Testing

Validate all business functionalities.

Smoke Testing

Verify critical functionalities before executing the full test suite.

Regression Testing

Ensure new updates do not break existing features.

UI Testing

Verify:

Alignment
Fonts
Colors
Buttons
Icons
Images
Labels
Responsive layouts
Usability Testing

Validate:

Navigation
Accessibility
Ease of use
User experience
Compatibility Testing

Browsers:

Google Chrome
Mozilla Firefox
Microsoft Edge

Devices:

Desktop
Tablet
Mobile
Validation Testing

Verify:

Required fields
Email format
Password rules
Boundary values
Invalid inputs
Exploratory Testing

Perform unscripted testing to identify hidden defects.

6. Test Environment
Item	Value
OS	Windows 11
Browser	Chrome, Firefox, Edge
Testing Type	Manual
Bug Tracking	Excel / GitHub Issues
Documentation	Microsoft Excel
Test Case Tool	Excel
Repository	GitHub
7. Entry Criteria

Testing begins when:

Requirements are available.
Application is deployed.
Test environment is ready.
Test cases are approved.
Required test data is available.
8. Exit Criteria

Testing will be completed when:

All planned test cases executed.
Critical defects resolved.
No blocker defects remain.
Test Summary Report completed.
Stakeholder approval received.
9. Test Deliverables
Test Plan
Test Scenarios
Test Cases
Requirement Traceability Matrix (RTM)
Bug Report
Test Execution Report
Test Summary Report
Screenshots
Defect Log
10. Roles & Responsibilities
Role	Responsibility
QA Engineer	Test planning, execution, reporting
Developer	Fix defects
Reviewer	Review test artifacts
Project Owner	Final approval
11. Test Data

Sample data includes:

Login
Valid Email
Invalid Email
Valid Password
Invalid Password
Registration
New User
Existing User
Invalid Email
Weak Password
Checkout
Valid Customer
Invalid Address
Empty Fields
12. Defect Management Process

Defects will be classified based on severity.

Severity	Description
Critical	System crash / Data loss
High	Major functionality broken
Medium	Partial functionality affected
Low	Cosmetic/UI issue

Bug Lifecycle:

New → Assigned → In Progress → Fixed → Retest → Closed

13. Risks
Risk	Mitigation
Requirement changes	Update test cases
Environment instability	Re-test after stabilization
Time constraints	Prioritize high-risk features
Browser inconsistencies	Cross-browser testing
14. Assumptions
Application is accessible.
Test environment remains stable.
Test data is available.
Stakeholders provide timely feedback.
15. Test Schedule
Activity	Status
Test Planning	Completed
Test Scenario Design	Completed
Test Case Writing	Completed
Test Execution	In Progress
Bug Reporting	Ongoing
Regression Testing	Planned
Test Closure	Pending
16. Test Metrics

The following metrics will be tracked:

Total Test Cases
Executed Test Cases
Passed Test Cases
Failed Test Cases
Blocked Test Cases
Pass Percentage
Defect Density
Defect Leakage
Test Coverage
17. Entry & Exit Summary

Entry Criteria

Approved requirements
Stable test environment
Prepared test data
Reviewed test cases

Exit Criteria

100% planned tests executed
No Critical or High severity defects open
Test Summary Report approved