# WebApp-Security-Lab

## Disclaimer
This project is for educational and research purposes only. All testing was conducted in a controlled environment on intentionally vulnerable applications. No real systems or users were affected.

## Tools Used
- Virtual Machine
- Firefox on Virtual Machine
- Burp Suite

## Learning Outcomes
This project provided practical experience in identifying and exploiting common web application vulnerabilities, including Cross-Site Scripting (XSS), Insecure Direct Object References (IDOR), and SQL Injection. It reinforced the importance of secure development practices such as input validation, output encoding, access control enforcement, and secure database query handling.

## Overview
This project demonstrates the identification, exploitation, and mitigation of common web application security vulnerabilities. The focus is on practical testing of input handling, access control, and database interaction within a controlled and intentionally vulnerable environment.

## Task 1 – Reflected Cross-Site Scripting (XSS)
This task examines reflected XSS vulnerabilities caused by improper input validation and output encoding.

The analysis includes:
- Testing user input fields for reflected script execution
- Identifying pages that reflect unsanitized input
- Demonstrating potential impacts such as session data exposure
- Discussing mitigation techniques including input validation, output encoding, and Content Security Policy (CSP)

## Task 2 – Insecure Direct Object Reference (IDOR)
This task investigates authorization flaws that allow authenticated users to access unauthorized resources.

The analysis includes:
- Intercepting and modifying HTTP requests
- Manipulating object identifiers to access another user’s private data
- Identifying missing server-side authorization checks
- Recommending ownership validation and access control enforcement

## Task 3A – SQL Injection in Authentication
This task explores an SQL injection vulnerability in the authentication process caused by unsanitized user input.

The analysis includes:
- Using UNION-based SQL injection to extract sensitive user data
- Enumerating database tables and identifying the database name
- Demonstrating unauthorized data disclosure
- Discussing the use of prepared statements and input validation as mitigations

## Task 3B – SQL Injection in Profile Update Functionality
This task examines an SQL injection vulnerability in an UPDATE query used for profile modification.

The analysis includes:
- Injecting malicious SQL through a profile update field
- Modifying unintended database fields
- Identifying improper validation and query construction
- Recommending parameterized queries and strict server-side validation
