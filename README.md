# Bug Bounty

# **Introduction**

At Bravado, we take security and privacy very seriously. If you believe that you have found a security vulnerability that affects Bravado service, please report it to us. Reports that fall within scope of the Bravado Bug Bounty Program are also eligible for a reward. We appreciate your efforts in helping protect customer trust and make Bravado more secure.

## Legal points

This page represents a legal document with terms and conditions applicable to all individuals who are participating in the Bravado Bug Bounty Program (the “Bug Bounty Terms”). By participating in the Bravado Bug Bounty Program, you agree to be bound by the Bug Bounty Terms. If you don’t agree to be bound by the Bug Bounty Terms, then you may not participate in the Bravado Bug Bounty Program. Our general terms of service (the “Standard Terms”), accessible at https://info.bravado.co/general-terms-of-service, are also incorporated herein by reference and apply to your use of our website and services generally.  In the event of any conflict between the Bug Bounty Terms and the Standard Terms, the Bug Bounty Terms shall control solely with regards to your participation in the Bravado Bug Bounty Program.

Any activities conducted in a manner consistent with the Bug Bounty Terms will be considered authorized conduct, and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under the Bug Bounty Terms, we will make it known that your actions were conducted in compliance with the Bug Bounty Terms. Bravado reserves all legal rights in the event of noncompliance with the Bug Bounty Terms.

We are unable to issue rewards to individuals who are resident of a country against which the United States has issued export sanctions or other trade restrictions. (e.g., Cuba, Iran, North Korea, Syria, Crimea, and the so-called Donetsk People's Republic and Luhansk People's Republic). You are responsible for any tax implications depending on your country of residency and citizenship. There may be additional restrictions on your ability to enter depending upon your local law.

## **Disclosure Policy and Confidentiality**

Any non-public data you receive, obtain access to or collect about Bravado, Bravado affiliates or any Bravado users, customers, employees or agents in connection with the Bug Bounty Program is considered Bravado’s confidential information ("Confidential Information"). Our Confidential Information also includes any information that is marked or otherwise designated as confidential at the time of disclosure or that a reasonable person would consider confidential based on the circumstances and content of the disclosure. Confidential Information does not include information that: (i) is or becomes known to the receiving party from a source other than one having an obligation of confidentiality to the disclosing party; (ii) is or becomes publicly known or otherwise ceases to be confidential, except through a breach of this Agreement; or (iii) is independently developed by the receiving party.

Confidential Information must be kept confidential and only used: (i) in furtherance of the Bravado Bug Bounty Program in accordance with the Bug Bounty Terms, (ii) to make disclosures to Bravado under the Bravado Bug Bounty Program; or (iii) to provide any additional information that may be required by Bravado in relation to the submitted report. No further use or exploitation of Confidential Information is allowed. Upon Bravado's request, you will permanently erase all Confidential Information for any systems and devices.

You may not use, disclose or distribute any such Confidential Information, including without limitation any information regarding your Bug Bounty submitted report, without our prior explicit consent.

## Ownership of Results

For the purposes of this section, “Results” means any information about vulnerabilities that you find, discover, observe, or identify within the scope of your participation in the Bravado Bug Bounty Program. By reporting or disclosing any Results to us, you hereby assign to Bravado and agree to assign to Bravado any and all of your rights with respect to such Results. To the extent any rights in your Results are not assignable, you shall grant and agree to grant to Bravado under any and all such rights an irrevocable, paid-up, royalty free, perpetual, exclusive, sub-licensable, transferable, and worldwide license to use and permit others to use such Results in any manner desired by us (and/or our customers and sponsors) without restriction or accounting to you, including, without limitation, the right to make, have made, sell, offer for sale, use, rent, lease, import, copy, prepare derivative works, publicly display, publicly perform, and distribute all or any part of such Results and modifications and combinations thereof and to sublicense or transfer any and all such rights. Further, you shall waive and agree to waive in favor of Bravado any moral right or other right or claim that is contrary to the intent of a complete transfer of rights to Bravado in your Results.


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

Any design or implementation issue that is reproducible and substantially affects the security of Bravado users is likely to be in scope for the Bravado Bug Bounty Program. Consider what an attack scenario would look like, and how an attacker might benefit? What are the consequences to the victim? The [Google Bug Hunters University guide](https://sites.google.com/site/bughunteruniversity/improve/writing-the-perfect-attack-scenario) may be useful in considering whether an issue has security impact.

Only reports that meet the following requirements are eligible to receive a monetary reward:

- You must be the first reporter of the vulnerability
- The vulnerability must demonstrate security impact to a site or application in scope
- You must not have compromised the privacy of our users or otherwise violated the Bravado’s Bug Bounty Terms
- You must not have publicly disclosed the vulnerability prior to the report being closed
- We are not legally prohibited from rewarding you.

# Scope

- https://dev1.bravado.co/*

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

You should understand that we can cancel the Bravado Bug Bounty Program at any time and the decision as to whether or not to pay a reward is entirely at our discretion.
