# Elevate_Labs-Task2-Phishing-Email-Analysis
# 🛡️ Task 2: Phishing Email Analysis

## 📌 Objective
Analyze a phishing email and identify red flags that indicate malicious intent.

---

## 📨 Sample Email Summary

The email claims to be from LinkedIn, requesting the user to "upgrade" their account by submitting personal information.

---

## 🚩 Phishing Indicators Found

| Indicator | Description |
|----------|-------------|
| **Generic greeting** | "Dear LINKEDIN Customer" — real emails use your name |
| **Urgency & Threats** | "FAIL TO UPGRADE YOUR ACCOUNT, IT WILL BE AUTOMATICALLY CLOSED" |
| **Request for sensitive info** | Asks for email, password, and confirm password |
| **Spelling/grammar issues** | “this upgrade your account” / “information requested .” |
| **Spoofed branding** | Uses LinkedIn logo and name to gain trust |
| **Suspicious CTA** | "Reply to UPGRADE" instead of legitimate LinkedIn flow |
| **Outdated copyright** | Says "© 2015 LINKEDIN" — outdated for 2025 |

---

## 🔐 Why This Is Dangerous

- Could **harvest login credentials** (email + password)
- May lead to **account takeover** or further scams
- Uses **social engineering tactics** (fear, urgency, trust)

---

## 📁 Repository Contents

- `phishing_email.txt` – Raw email content
- `README.md` – Analysis of the email and red flags

---

## ✅ Conclusion

This email is a **phishing attempt** that tries to steal credentials by pretending to be a security upgrade from LinkedIn. It uses urgency, fake branding, and social engineering to manipulate the user.

