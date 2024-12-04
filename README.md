# BountyLoot JSON Summary

The `bountyLoot.json` file is an organized collection of bug bounty and vulnerability write-ups across multiple categories. Each category represents a target organization or a type of exploit, with individual write-ups detailing successful bug bounties, vulnerability exploits, and other security research stories. Below is a detailed description of each category:

## Categories

### 1. Apple
Contains write-ups on vulnerabilities related to Apple products, focusing on remote code execution and other security flaws.

- **Finding 0day to hack Apple**: A guide to discovering zero-day vulnerabilities in Apple systems.

### 2. Microsoft
Features multiple vulnerabilities in Microsoft products including Office 365, Teams, and Edge. The exploits cover remote code execution (RCE), privilege escalation, cross-site scripting (XSS), and unauthorized data access.

- **Microsoft Office 365 RCE**: Details on exploiting remote code execution vulnerabilities in Office 365.
- **Microsoft Teams Zero-click RCE**: Write-ups on how to achieve RCE via spoofing in Microsoft Teams.
- **Microsoft Edge Privilege Escalation via XSS**: Exploiting XSS vulnerabilities for privilege escalation.

### 3. Google
Includes exploits for various Google platforms such as Google Cloud, App Engine, and JupyterLab. Vulnerabilities range from RCE to DNS information leaks and bug tracking exposure.

- **Google Cloud RCE**: Several write-ups on remote code execution in Google Cloud environments.
- **Bug Tracker Vulnerability Exposure**: Finding vulnerabilities through Google’s internal bug tracker.

### 4. Facebook
This section includes remote code execution vulnerabilities in Facebook's infrastructure, SSRF exploits, and API misconfigurations leading to data exposure.

- **MobileIron MDM RCE**: Details of an unauthenticated remote code execution vulnerability.
- **Facebook Ads API Source Code Disclosure**: How source code was disclosed through improper API security.
- **$10,000 SSRF Bug**: A detailed story of a successful SSRF bug bounty on Facebook.

### 5. Samsung
Covers RCE vulnerabilities related to Samsung products, including their Galaxy Store app and production repositories.

- **Samsung S20 RCE via Galaxy Store App**: Write-ups on remote code execution vulnerabilities through the Samsung Galaxy Store.

### 6. GitHub
Includes multiple write-ups of vulnerabilities found on GitHub, covering topics such as SSRF, insecure configurations, and remote code execution.

- **GitHub Pages RCE via Kramdown**: A vulnerability involving insecure configurations in GitHub Pages.
- **SSRF Execution Chain to RCE**: Details on chaining vulnerabilities to achieve RCE on GitHub Enterprise.

### 7. Discord
One write-up on a remote code execution vulnerability in the Discord Desktop app.

### 8. E-commerce
Focuses on vulnerabilities in e-commerce platforms, including privilege escalation, data leaks, and source code disclosure.

- **PII Information Dump**: How personally identifiable information (PII) was exposed through a vulnerability in an e-commerce platform.

### 9. SQL Injection (SQLI)
Write-ups describing various SQL injection exploits leading to data extraction, account takeovers, and other security impacts.

- **Interesting Case of SQLi**: A detailed walkthrough of a specific SQL injection exploit.
- **Blind SQL Injection to Account Takeover**: Exploiting blind SQL injections to gain unauthorized access.

### 10. Server Side Request Forgery (SSRF)
This category includes stories of SSRF vulnerabilities exploited in Facebook, Google, and other platforms, leading to sensitive data exposure.

- **$10,000 Facebook SSRF**: A detailed story of how SSRF was used to gain access to internal services.
- **Google Cloud Monitoring SSRF**: Exploiting SSRF to access metadata in Google Cloud environments.

### 11. Cross Site Scripting (XSS)
XSS vulnerabilities that led to account takeover, data leaks, and other forms of exploitation.

- **Stored XSS via File Upload**: How an XSS vulnerability was introduced via a file upload feature.
- **Blind XSS in Google Analytics**: Leveraging blind XSS to gain access to user information in Google Analytics.

### 12. Insecure Direct Object Reference (IDOR)
Includes write-ups about IDOR vulnerabilities leading to account takeovers, data leaks, and privilege escalation.

- **Critical IDOR in Starbucks**: How an IDOR vulnerability was used to take over accounts in Starbucks Singapore.
- **Chaining IDOR with Business Logic Flaw**: Chaining IDOR vulnerabilities to gain critical impact.

### 13. Injection Attacks
A compilation of different types of injection attacks such as SQL, Host Header, and Spreadsheet injections.

- **SQL Injection in Nokia Sites**: Exploiting SQL injection vulnerabilities in Nokia's websites.
- **Server-side Spreadsheet Injection**: A unique injection leading to remote code execution through spreadsheet manipulation.

### 14. General Bug Bounty Write-ups
General bug bounty write-ups that do not fit into a specific company or type but provide valuable insights into finding and exploiting vulnerabilities.

- **Facebook Bug Bounty Writeup**: A compilation of several Facebook-related bug bounty exploits.
- **Bug Bounty Journey - LFI to Stored XSS**: One hacker's journey from finding a local file inclusion vulnerability to exploiting it for stored XSS.
- **IDOR and CSRF Combined Attack**: The story of combining IDOR and CSRF vulnerabilities to achieve a more significant impact.

## Purpose
The `bountyLoot.json` file serves as a comprehensive resource for security researchers, ethical hackers, and bug bounty hunters. It aggregates knowledge from real-world write-ups to aid in learning from successful exploit scenarios, understanding vulnerability impact, and honing hacking skills for different platforms and systems.

## Structure
The JSON file is organized by categories, each containing an array of write-ups. Each entry in an array includes:
- **Title**: The name of the write-up, giving a brief indication of the vulnerability or scenario discussed.
- **Link**: A URL to the original write-up for further reading and exploration.

## Usage
This collection can be used as:
- **Educational Material**: To study different types of vulnerabilities and their exploitation.
- **Reference for Bug Bounty Hunting**: To gain insights into where to look for vulnerabilities, especially for new bug bounty hunters.
- **Skill Development**: To practice and learn from real-life examples provided by experienced security researchers.
