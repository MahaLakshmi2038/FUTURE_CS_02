# Sample 01 Analysis – Microsoft Account Verification Scam

## Analysis Summary

| Field | Observation |
|--------|-------------|
| Sample ID | 01 |
| Classification | Phishing |
| Risk Level | High |
| Attack Type | Credential Phishing |

---

# Objective

The objective of this analysis is to examine the email for phishing indicators, assess the level of risk, and determine whether it is legitimate or malicious.

---

# Phishing Indicators

## 1. Suspicious Sender

**Observed Sender**

support@micr0soft-security.com

### Analysis

The sender attempts to impersonate Microsoft by using a look-alike domain.

Instead of **microsoft.com**, the domain contains the number **0** in place of the letter **o**.

### Why This Matters

Attackers frequently register look-alike domains to trick users into believing an email is legitimate.

**Risk:** High

---

## 2. Reply-To Address

Reply-To:

verify@secure-login-alert.com

### Analysis

The Reply-To address belongs to a different domain than the sender.

This is commonly used to redirect responses to an attacker-controlled mailbox.

**Risk:** High

---

## 3. Urgent Language

The email claims that the Microsoft account will be disabled within 24 hours.

### Analysis

Creating urgency is a common social engineering technique that pressures users into acting without verifying the email.

**Risk:** High

---

## 4. Suspicious Link

The verification link is not an official Microsoft domain.

### Analysis

Users should always verify the destination domain before clicking links in emails.

The link appears designed to steal user credentials.

**Risk:** High

---

## 5. Brand Impersonation

The email claims to come from Microsoft Security Team.

### Analysis

Cybercriminals frequently impersonate trusted brands because users are more likely to trust and interact with emails from well-known organizations.

---

# Overall Assessment

The email contains multiple phishing indicators, including:

- Look-alike domain
- Reply-To mismatch
- Urgent language
- Suspicious verification link
- Brand impersonation

These indicators strongly suggest that the email is a phishing attempt designed to steal Microsoft account credentials.

---

# Final Classification

**Classification:** Phishing

**Overall Risk Rating:** High

---

# Recommended Actions

- Do not click any links.
- Do not enter login credentials.
- Report the email to the organization's security team.
- Delete the email.
- Verify account notifications by visiting the official Microsoft website directly.

---

# Analyst's Conclusion

Based on the observed phishing indicators, this email should be classified as a **High-Risk Phishing Email**. Users should avoid interacting with it and report it immediately to help prevent credential compromise.