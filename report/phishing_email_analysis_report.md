# Phishing Email Detection & Awareness System

## Future Interns – Cyber Security Internship

**Project:** Task 02 – Phishing Email Detection & Awareness System

**Prepared by:** Maha Lakshmi

**Date:** July 2026

---

# Executive Summary

Phishing remains one of the most common cyber threats targeting individuals and organizations. Attackers exploit social engineering techniques to deceive users into revealing sensitive information, downloading malware, or performing unauthorized financial transactions.

This project analyzes five simulated phishing email samples representing different attack techniques, including credential phishing, banking scams, business email compromise (BEC), malware delivery, and prize scams.

Each email was examined for common phishing indicators such as suspicious sender addresses, fake domains, urgent language, malicious links, attachments, and social engineering tactics. Based on the findings, every sample was classified according to its risk level, and appropriate mitigation strategies were documented.

In addition to technical analysis, this project includes security awareness resources to educate users on recognizing and reporting phishing attempts.

---

# Project Objectives

The objectives of this project are to:

- Understand common phishing attack techniques.
- Identify phishing indicators in email messages.
- Classify emails based on risk.
- Document investigation findings using a structured methodology.
- Promote cybersecurity awareness through educational resources.
- Develop practical documentation skills aligned with SOC analyst responsibilities.
---

# Introduction

Email remains one of the most widely used communication methods for businesses and individuals. Due to its widespread use and the trust users place in email communication, it has become one of the primary targets for cybercriminals.

Phishing is a form of social engineering in which attackers attempt to deceive users into revealing sensitive information, downloading malicious software, or performing unauthorized actions. These attacks often imitate trusted organizations such as banks, technology companies, government agencies, or senior executives.

Because phishing attacks continue to evolve in sophistication, users and organizations must understand how to recognize suspicious emails and respond appropriately.

This project demonstrates the practical analysis of phishing emails using a structured investigation approach similar to that followed by Security Operations Center (SOC) analysts.

---

# Background Theory

## What is Phishing?

Phishing is a cyberattack in which an attacker sends fraudulent emails or messages that appear to come from a legitimate source. The objective is typically to steal sensitive information, install malware, or manipulate victims into performing unauthorized actions.

### Common Phishing Techniques

- Credential Phishing
- Business Email Compromise (BEC)
- Malware Delivery
- Brand Impersonation
- Financial Fraud
- Social Engineering

### Common Phishing Indicators

During email analysis, security analysts commonly examine:

- Suspicious sender addresses
- Look-alike or fake domains
- Urgent or threatening language
- Unexpected attachments
- Suspicious hyperlinks
- Requests for sensitive information
- Executive impersonation
- Unusual payment requests

---

# Analysis Methodology

The following investigation process was followed for each email sample:

1. Review the sender's email address.
2. Examine the subject line and email content.
3. Identify signs of urgency or psychological manipulation.
4. Inspect embedded links and attachments.
5. Determine whether the sender appears legitimate.
6. Identify Indicators of Compromise (IOCs).
7. Assess the overall risk level.
8. Classify the email as Safe, Suspicious, or Phishing.
9. Recommend appropriate mitigation measures.
10. Document the findings using a structured investigation format.

---

# Analysis Results

The following table summarizes the findings from the five phishing email investigations conducted during this project.

| Sample | Attack Type | Classification | Risk Level | Key Indicators |
|--------|-------------|----------------|------------|----------------|
| Sample 01 | Microsoft Credential Phishing | Phishing | High | Look-alike domain, Reply-To mismatch, Suspicious link, Urgent language |
| Sample 02 | Banking Credential Phishing | Phishing | High | Fake sender, Credential harvesting, Suspicious verification link |
| Sample 03 | Business Email Compromise (BEC) | Phishing | Critical | Executive impersonation, Financial request, Personal email address |
| Sample 04 | Malware Delivery | Phishing | High | ZIP attachment, Unknown sender, Urgent payment request |
| Sample 05 | Prize Scam | Phishing | High | Fake reward, Sensitive information request, Suspicious link |

---

# Risk Assessment

Based on the analysis, all five email samples were determined to be phishing attacks. Although each sample used a different technique, they shared several common characteristics designed to manipulate users into taking unsafe actions.

The most frequently observed phishing indicators were:

- Urgent or threatening language
- Suspicious or unofficial sender domains
- Requests for sensitive information
- Suspicious hyperlinks
- Social engineering techniques
- Financial manipulation
- Executive or brand impersonation

Among the analyzed samples, the Business Email Compromise (BEC) attack presented the highest level of risk because it attempted to manipulate an employee into transferring company funds by impersonating a senior executive.

---

# Key Findings

The investigation identified several important observations:

- Attackers rely heavily on psychological manipulation rather than technical exploits.
- Urgency was present in almost every phishing email.
- Trusted organizations and senior executives are commonly impersonated.
- Unexpected links and attachments remain common delivery methods.
- Careful inspection of sender information can prevent many phishing attacks.
- Security awareness plays an important role in reducing phishing success.

---

# Recommendations

To reduce the risk of phishing attacks, organizations should:

- Conduct regular cybersecurity awareness training.
- Verify sender email addresses before responding.
- Avoid clicking links from unsolicited emails.
- Scan email attachments before opening them.
- Enable Multi-Factor Authentication (MFA).
- Implement SPF, DKIM, and DMARC for email authentication.
- Establish a clear process for reporting suspicious emails.
- Verify financial requests using an independent communication channel.
---

# User Awareness Tips

Users can significantly reduce the risk of phishing attacks by following these best practices:

- Verify the sender's email address before responding.
- Avoid clicking links from unsolicited or unexpected emails.
- Inspect URLs carefully before entering credentials.
- Never share passwords or sensitive information through email.
- Be cautious of urgent requests that create pressure to act immediately.
- Verify financial or sensitive requests through an independent communication channel.
- Report suspicious emails to the organization's IT or Security team.
- Keep operating systems and antivirus software up to date.

---

# Incident Response

If a phishing email is identified, the following response process is recommended:

1. Do not interact with the email.
2. Avoid clicking links or opening attachments.
3. Report the email to the IT/Security team.
4. Delete or quarantine the email.
5. If credentials were entered, change passwords immediately.
6. Enable Multi-Factor Authentication (MFA) if not already enabled.
7. Monitor accounts for suspicious activity.
8. Conduct a security review to identify similar phishing attempts.

---

# Future Improvements

This project can be expanded further by incorporating:

- Analysis of real-world phishing email headers.
- SPF, DKIM, and DMARC authentication verification.
- URL reputation analysis using threat intelligence platforms.
- Automated phishing detection using Python.
- Integration with SIEM platforms for alert generation.
- Email threat intelligence and IOC enrichment.

---

# Conclusion

Phishing continues to be one of the most successful cyberattack techniques because it targets human behavior rather than technical vulnerabilities.

Throughout this project, five simulated phishing email samples were analyzed using a structured investigation methodology. Each sample demonstrated different attack techniques, including credential theft, business email compromise, malware delivery, and financial fraud.

The investigation showed that identifying phishing indicators such as suspicious sender addresses, fake domains, malicious links, urgent language, and social engineering techniques can significantly reduce the likelihood of successful attacks.

In addition to technical analysis, this project emphasizes the importance of cybersecurity awareness, proper incident reporting, and defensive best practices.

Developing both technical investigation skills and user awareness is essential for strengthening an organization's overall security posture.

---

# References

- Microsoft Security – Email and Phishing Protection
- Google Safe Browsing
- OWASP Phishing Guidance
- CISA – Avoiding Social Engineering and Phishing Attacks
- MITRE ATT&CK Framework