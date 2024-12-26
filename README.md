# API-Testing-Documentary

## Overview
This repository serves as a comprehensive guide and documentation for testing APIs, focusing on common vulnerabilities and best practices for securing APIs. The topics covered align with modern security standards and address real-world scenarios.

## Folder Structure
Each folder is dedicated to a specific API vulnerability or testing methodology, containing detailed documentation, examples, and test cases.

### Topics Covered
1. [**API1 - Broken Object Level Authorization (IDOR)**](./API1%20-%20Broken%20Object%20Level%20Authorization%20IDOR)  
   Explores insecure direct object reference vulnerabilities and mitigation techniques.

2. [**API2 - Broken User Authentication**](./API2%20-%20Broken%20User%20Authentication)  
   Focuses on identifying and resolving authentication issues in APIs.

3. [**API3 - Excessive Data Exposure**](./API3%20-%20Excessive%20Data%20Exposure)  
   Discusses scenarios where APIs expose more data than necessary and how to address them.

4. [**API4 - Rate Limiting & Lack of Resources**](./API4%20-%20Rate%20Limiting%20%26%20Lack%20of%20Resources)  
   Covers rate-limiting mechanisms to protect APIs from resource exhaustion.

5. [**API5 - Broken Function Level Authorization**](./API5%20-%20Broken%20Function%20Level%20Authorization)  
   Details improper function-level authorization and how to test for it.

6. [**API6 - Mass Assignment**](./API6%20-%20Mass%20Assignment)  
   Examines vulnerabilities arising from unsanitized user input and automated tools to detect them.

7. [**API7 - Injection (NoSQL/SQL)**](./API7%20-%20Injection%20NOSQL%20Injection%20SQL%20Injection)  
   Investigates injection attacks on APIs and the best practices to prevent them.

8. [**API8 - Broken Access Control (SSRF)**](./API8%20-%20Broken%20Access%20Control%20SSRF)  
   Explains Server-Side Request Forgery vulnerabilities and mitigation techniques.

9. [**API9 - Hacking JSON Web Tokens (JWT)**](./API9%20-%20Hacking%20JSON%20Web%20Tokens%20JWT)  
   Demonstrates techniques for exploiting JWT-based authentication and securing it.

10. [**Setup**](./Setup)  
    Instructions for setting up testing environments and required tools.

## Setup
To get started:
1. Clone the repository:  
   ```bash
   git clone https://github.com/Kalashkundaliyacyber/API-Testing-Documentary.git
   ```
2. Navigate to the directory:  
   ```bash
   cd API-Testing-Documentary
   ```
3. Follow the **Setup** folder for environment configuration.

## Tools Used
- Burp Suite
- OWASP Top 10
- Docker

## How to Contribute
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit and push your changes.
4. Submit a pull request.

## Contact
For any questions or suggestions, feel free to reach out at [GitHub Profile](https://github.com/Kalashkundaliyacyber).

---