# Bug Bounty Program

# **Introduction**

At Bravado, we take security and privacy very seriously. If you believe that you have found a security vulnerability that affects Bravado service, please report it to us. Reports that fall within scope of Bravado Bug Bounty Program are also eligible for a reward. We appreciate your efforts in helping protect customer trust and make Bravado more secure.

## Legal points

Any activities conducted in a manner consistent with this policy will be considered authorized conduct, and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will make it known that your actions were conducted in compliance with this policy. Bravado reserves all legal rights in the event of noncompliance with this policy.

We are unable to issue rewards to individuals who are resident of a country against which the United States has issued export sanctions or other trade restrictions. (e.g., Cuba, Iran, North Korea, Syria, Crimea, and the so-called Donetsk People's Republic and Luhansk People's Republic). You are responsible for any tax implications depending on your country of residency and citizenship. There may be additional restrictions on your ability to enter depending upon your local law.

## **Disclosure Policy and Confidentiality**

Any data you receive, obtain access to or collect about Bravado, Bravado affiliates or any Bravado users, customers, employees or agents in connection with the Bug Bounty Program is considered Bravado’s confidential information ("Confidential Information").

Confidential Information must be kept confidential and only used: (i) to make the disclosure to Bravado under the Bravado Bug Bounty Program; or (ii) to provide any additional information that may be required by Bravado in relation to the submitted report. No further use or exploitation of Confidential Information is allowed. Upon Bravado's request, you will permanently erase all Confidential Information for any systems and devices.

You may not use, disclose or distribute any such Confidential Information, including without limitation any information regarding your Bug Bounty submitted report, without our prior explicit consent.

## Program rules

**Do:**

- Accept and follow Bravado’s Bug Bounty Program Terms.
- Perform testing only using accounts that are your own personal/test accounts.
- Report your initial finding(s) and request authorization to continue testing, If you think you may cause, or have caused, damage with testing a vulnerability.
- By making a Submission, you represent and warrant that the Submission is original to you and you have the right to submit the Submission.
- By making a Submission, you give us the right to use your Submission for any purpose.

**Do NOT:**

- Do not leave any system in a more vulnerable state than you found it.
- Do not brute force credentials or guess credentials to gain access to systems.
- Do not participate in denial of service attacks.
- Do not upload shells or create a backdoor of any kind.
- Do not publicly disclose a Vulnerability without our explicit review and consent.
- Do not engage in any form of social engineering of Bravado employees, customers, or partners.
- Do not engage or target any Bravado’s employee, customer, or partner during your testing.
- Do not attempt to extract, download, or otherwise ex-filtrate data that may have PII or other sensitive data other than your own.
- Do not change passwords of any account that is not yours or that you do not have explicit permission to change. If ever prompted to change a password of an account you did not register yourself or an account that was not provided to you, stop and report the finding immediately.
- Do not do anything that would be considered a privacy violation, cause destruction of data, or interrupt or degrade our service.
- Do not interact with accounts you do not own.

# Focus area & Rewards

Any design or implementation issue that is reproducible and substantially affects the security of Bravado users is likely to be in scope for the program. Consider what an attack scenario would look like, and how an attacker might benefit? What are the consequences to the victim? The [Google Bug Hunters University guide](https://sites.google.com/site/bughunteruniversity/improve/writing-the-perfect-attack-scenario) may be useful in considering whether an issue has security impact.

Only reports that meet the following requirements are eligible to receive a monetary reward:

- You must be the first reporter of the vulnerability
- The vulnerability must demonstrate security impact to a site or application in scope
- You must not have compromised the privacy of our users or otherwise violated the Bravado’s Bug Bounty rules
- You must not have publicly disclosed the vulnerability prior to the report being closed
- We are not legally prohibited from rewarding you.

# Scope

- [https://dev1.bravado.co/](https://dev1.bravado.co/)

## What Qualifies?

- Remote Code Execution - **$250**
    - XXE leading to RCE, Command injection, deserialization bugs
- Unrestricted file system or database access - **$150**
    - SQL injection, XXE, SSRF
- Code execution on the client - **$50**
    - CSRF, Stored/DOM/Blind XSS, HTML injection (more than phishing)
- Logic flaw bugs leaking or bypassing significant security controls - **$80**
    - Direct object reference, account takeover, remote user impersonation, privilege escalation, IDOR, HTTP request smuggling, directory traversal, proxy misconfiguration leading to bypass of security controls
- Confidential or sensitive data - **$100**
    - Generalized access control issues leading to exposure of PII data
- Authentication flaws (website, mobile, or API) - **$150**
- Domain and subdomain takeovers - **$50**
    - DNS zone, domain, and subdomain takeovers
- Leaks with real impact will be evaluated internally and rewarded based on highest impact:
    - API tokens
    - Secrets
    - Employee Credentials

## Bugs that do NOT qualify:

- Attacks requiring physical access to a user's device
- Any physical attacks against Bravado’s property or data centers
- Forms missing CSRF tokens (we require evidence of actual CSRF vulnerability)
- Logout CSRF
- Self XSS
- CSV Injection
- Scanner Outputs
- Weak Captcha / Captcha bypass
- HTTP Trace Method
- Password and account recovery policies, such as reset link expiration or password complexity
- Issues without clearly identified security impact, such as clickjacking on a static website, missing security headers, or descriptive error messages
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS
- Issues related to software or protocols not under Bravado control
- Vulnerabilities only affecting users of outdated or unpatched browsers and platforms
- Bugs requiring unlikely user interaction or rely on social engineering
- Any activity that could lead to the disruption of our service (DoS).
- Issues relating to unlocking client-side features in modified Bravado applications, attacks requiring MITM, rooted devices, or jailbroken devices
- Open redirects unless they can demonstrate a higher security risk than phishing.
- Previously known vulnerable libraries without a working Proof of Concept.
- Missing best practices in SSL/TLS configuration.
- Rate limiting or bruteforce issues
- Missing HttpOnly or Secure flags on cookies
- Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.)
- Software version disclosure / Banner identification issues / Directory listing / Descriptive error messages or headers (e.g. stack traces, application or server errors).
- General best practices related to CSP policies, lack of specific security headers, etc.

# Submission

Submit your findings at: **security@bravado.co**

## Submission validation

- 72 hours for validation
- remediate critical and high severity submissions within 90 days.

## **Reservation of Rights**

You should understand that we can cancel the program at any time and the decision as to whether or not to pay a reward has to be entirely at our discretion.
