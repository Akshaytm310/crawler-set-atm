# crawler-set-atm

CSRF Middleware Analysis, Crawler Development, and Proof of Concept (PoC)

This repository centers around a project that explores Cross-Site Request Forgery (CSRF) protections, develops a web crawler to detect CSRF vulnerabilities, and includes an HTML-based Proof of Concept (PoC) to demonstrate exploitation scenarios.


Project Breakdown

Step 1: CSRF Middleware & Protection Research
Goal: Gain a comprehensive understanding of how CSRF protection mechanisms work.

Outcome: Insights into the use of CSRF tokens, security headers, and SameSite cookie attributes for preventing unauthorized actions triggered by malicious third parties.

Step 2: CSRF Vulnerability Crawler
Goal: Build an automated crawler to scan web applications for CSRF-related weaknesses.

Features:

    Detects forms and endpoints lacking CSRF tokens or using them improperly.

    Identifies potential CSRF exposure in HTTP headers or form submissions.

Step 3: CSRF Exploitation PoC
Goal: Demonstrate a real-world CSRF vulnerability via an HTML-based PoC.

PoC Capabilities:
    Simulates unauthorized actions in a vulnerable application by crafting a malicious form that bypasses CSRF protection.

How to Use  
1. Clone the repository.  
2. Review the research materials for understanding CSRF protections.  
3. Run the crawler on target web applications to scan for vulnerabilities.  
4. Modify the PoC HTML page to simulate a CSRF attack against vulnerable targets.

Installation  
To run the crawler, install the necessary dependencies:  
```bash
pip install -r requirements.txt
```

Disclaimer  
This project is for educational purposes only. Use the crawler and PoC responsibly and only on authorized systems.

License  
This project is licensed under the MIT License.
