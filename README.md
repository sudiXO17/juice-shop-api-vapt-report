# OWASP Juice Shop API Vulnerabilities

This repository contains proof-of-concept examples of vulnerabilities found in the **OWASP Juice Shop API** during manual testing.  
Each directory contains the request data and response screenshots.

| #  | Vulnerability Title                              | Severity |
|----|--------------------------------------------------|----------|
| 01 | Unauthorized Basket Access                       | High     |
| 02 | Unauthorized Access to Delivery Address          | High     |
| 03 | Admin Configuration Exposure                     | Critical |
| 04 | Unauthorized User Profile Access (`/whoami`)    | High     |
| 05 | JWT Token Disclosure & Forgery                   | Critical |
| 06 | Unauthorized Feedback Access                     | Medium   |
| 07 | Review Ownership Modification                    | Medium   |
| 08 | Unprotected Save Login IP API                    | High     |
| 09 | Verbose Error Messages                           | Low      |
| 10 | Product Listing Endpoint Abuse                   | Medium   |

---

## 📂 Structure

Each folder includes:
- `*.txt`: crafted API request(s)
- `*.png`: response screenshot(s)

