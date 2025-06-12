# crawler-set-atm

CSRF Middleware and Protections Research, Crawler, and PoC

This repository contains a project focused on researching Cross-Site Request Forgery (CSRF) middleware and protections, creating a crawler to identify CSRF vulnerabilities, and developing an HTML form Proof of Concept (PoC) to demonstrate these vulnerabilities.

Project Breakdown

Step 1: Research CSRF Middleware and Protections  
- Objective: Understand how CSRF middleware and protections function.  
- Outcome: A thorough understanding of how CSRF tokens are used for preventing unauthorized actions and how applications mitigate CSRF attacks using headers, tokens, or SameSite cookie attributes.

Step 2: CSRF Vulnerability Crawler  
- Objective: Develop a crawler to scan web applications for CSRF vulnerabilities.  
- Key Features:  
  - Scans for missing or improperly implemented CSRF tokens in forms or HTTP headers.  
  - Identifies web applications that may be susceptible to CSRF attacks.

Step 3: CSRF Proof of Concept (PoC)  
- Objective: Create an HTML page demonstrating a CSRF vulnerability.  
- PoC Features:  
  - An HTML form designed to trigger an unauthorized action in a target application, exploiting a missing or faulty CSRF token.

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
