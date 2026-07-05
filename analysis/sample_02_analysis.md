# Sample 02 Analysis – Bank Account Security Alert

## Analysis Summary

| Field | Observation |
|--------|-------------|
| Sample ID | 02 |
| Classification | Phishing |
| Risk Level | High |
| Attack Type | Banking Credential Phishing |

---

# Objective

Analyze the email to identify phishing indicators and determine whether it is a legitimate banking notification or a credential phishing attempt.

---

# Phishing Indicators

## 1. Suspicious Sender

**Observed Sender**

security@secure-bank-alerts.com

### Analysis

The sender claims to represent a bank but uses a generic domain rather than an official banking domain.

Users should always verify whether the sender belongs to the legitimate organization.

**Risk:** High

---

## 2. Urgent Language

The email claims that account access has been restricted and must be verified within **12 hours**.

### Analysis

Urgency is a common psychological tactic used to pressure users into acting without carefully checking the email.

**Risk:** High

---

## 3. Suspicious Link

https://secure-bank-verification.example

### Analysis

The URL is not associated with an official banking website and appears designed to collect login credentials.

Users should never click links from unsolicited emails without verifying the destination.

**Risk:** High

---

## 4. Credential Harvesting

The email asks the user to verify their identity through a provided link.

### Analysis

This is a classic credential phishing technique intended to steal usernames, passwords, or banking information.

---

# Indicators of Compromise (IOCs)

| IOC Type | Value | Reason |
|----------|-------|--------|
| Sender Email | security@secure-bank-alerts.com | Unofficial sender domain |
| Subject | Immediate Action Required: Verify Your Bank Account | Creates urgency |
| URL | https://secure-bank-verification.example | Fake verification page |
| Attack Technique | Credential Phishing | Attempts to steal user credentials |

---

# Overall Assessment

The email contains multiple phishing indicators, including urgency, a suspicious sender, and a fake verification link.

The objective of the attack is likely to steal online banking credentials.

---

# Final Classification

**Classification:** Phishing

**Overall Risk Rating:** High

---

# Recommended Actions

- Do not click the verification link.
- Do not provide banking credentials.
- Report the email to the organization's security team.
- Access the bank's official website manually if verification is needed.

---

# Analyst's Conclusion

This email exhibits several characteristics commonly associated with banking phishing campaigns. Based on the identified indicators, it should be classified as a **High-Risk Phishing Email**.