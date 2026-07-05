# Sample 03 Analysis – Business Email Compromise (BEC)

## Analysis Summary

| Field | Observation |
|--------|-------------|
| Sample ID | 03 |
| Classification | Phishing (Business Email Compromise) |
| Risk Level | Critical |
| Attack Type | Financial Fraud |

---

# Objective

Analyze the email to determine whether it is a legitimate business request or an attempt to commit financial fraud.

---

# Phishing Indicators

## 1. Sender Analysis

The sender claims to be the CEO but uses a free Gmail account instead of the organization's official email domain.

**Risk:** Critical

---

## 2. Urgency

The attacker requests the transfer within one hour.

### Analysis

Urgency reduces the likelihood that employees will verify the request.

---

## 3. Authority Impersonation

The attacker pretends to be a senior executive.

Employees may hesitate to question instructions from leadership.

---

## 4. Confidentiality Request

The email asks that the transaction remain confidential.

Attackers often discourage victims from discussing requests with colleagues because verification could expose the fraud.

---

## Indicators of Compromise (IOCs)

| IOC Type | Value | Reason |
|----------|-------|--------|
| Sender | ceo.company@gmail.com | Uses a personal email instead of the company domain |
| Subject | Urgent Wire Transfer Request | Creates urgency |
| Requested Action | Wire Transfer | Financial fraud attempt |
| Attack Technique | Business Email Compromise | Executive impersonation |

---

# Overall Assessment

The email demonstrates several characteristics of a Business Email Compromise (BEC) attack, including executive impersonation, urgency, and a request for an immediate financial transaction.

---

# Final Classification

**Classification:** Phishing (Business Email Compromise)

**Risk Rating:** Critical

---

# Recommended Actions

- Verify the request using an independent communication channel (such as a phone call or Teams message).
- Do not process financial transactions based solely on email requests.
- Report the incident to the organization's security team.
- Follow the organization's financial approval procedures.

---

# Analyst's Conclusion

This email is a classic Business Email Compromise (BEC) attempt. The attacker impersonates a senior executive to pressure an employee into making an unauthorized financial transfer. Independent verification should always be performed before processing high-value payment requests.