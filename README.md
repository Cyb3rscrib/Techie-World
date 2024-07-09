**Techie-World.xyz Penetration Test Report**

**Overview**

In April 2024, a comprehensive penetration test was conducted on Techie-World.xyz by Orr Amsalem. The goal was to identify and address security vulnerabilities across the website's systems, applications, and components.


**Background**

The penetration test aimed to:
• Uncover vulnerabilities that could compromise the security of Techie-World.xyz.
• Simulate real-world attack scenarios to evaluate the security posture.
• Provide detailed findings, Proof of Concept demonstrations, and actionable recommendations to enhance security.


**Scope & Targets**

**Target Address:** www.techie-world.xyz
**Goal:** Identify as many vulnerabilities as possible using various infrastructural and applicative methodologies.


**Test Findings**

The assessment revealed multiple vulnerabilities, ranging from high to low risk:

**High Risk Vulnerabilities**

• **Code Injection Vulnerability:** Unauthorized code execution.

• **Reverse Shell Vulnerability:** Allows remote control of the system.

• **Privilege Escalation Vulnerability:** Gain higher privileges within the system."

• **Local File Inclusion (LFI) Vulnerability:** Access local files on the server.

• **Known Apache 2.4.52 CVEs:**  Includes SSRF, CSRF, and request smuggling vulnerabilities.



**Medium Risk Vulnerabilities**

• **Cookie Manipulation Vulnerability:** Altering cookies to affect application behavior.

• **Reflected XSS via Contact Form Vulnerability:** Injecting scripts through the contact form.

•**Phishing** **- Clickjacking via Iframe Vulnerability:** Deceptive UI techniques to trick users.

• **Missing Critical Security Headers:** Lacking headers like X-Content-Type-Options, Referrer-Policy, Strict-Transport-Security, Content-Security-Policy.



**Low Risk Vulnerabilities**

• **Directory Listing Enabled:** Exposing directory contents.

• **Brute Force Attack on User's Login:** Attempt to crack user credentials.

• **Weak Password Policy:** Insufficient password requirements.

• **User Enumeration Vulnerability:** Identifying valid usernames.

• **Exposure of Robots.txt File:** Disclosing sensitive file paths.

• **Apache Server Disclosure:** Revealing server information.



**Test Limitations**

**Scope Constraints:** Only systems within the agreed scope were tested.

**Time Constraints:** Limited timeframe may have left some vulnerabilities undetected.

**Resource Limitations:** Testing was conducted with available resources and tools.

**Assessment Environment:** Testing environment may differ from the production environment.

**Dynamic Security Landscape:** Findings reflect the security posture at the test time.

**Limited Impact Assessment:** Further investigation required for detailed impact analysis.



**Methodologies Used**

**Web Testing Vulnerabilities:** Followed OWASP Top 10 guidelines.

**Various Code Injection Techniques:** Assessed both client and server levels.

**System Bug Checks:** Identified bugs leading to malicious actions at the user level.

**Scanning Techniques:** Detected known weaknesses in customer systems.

**Network Attacks:** Performed to obtain high permissions and take over the network.



**Conclusion** 

The penetration test on Techie-World.xyz identified significant vulnerabilities that pose a high risk to the system's security. Addressing these vulnerabilities is critical to enhance the organization's security posture and protect against potential threats. This report provides detailed findings and recommendations to assist in mitigating identified risks.

For more details, refer to the full penetration test report.
