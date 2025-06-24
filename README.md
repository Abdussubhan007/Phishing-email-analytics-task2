# Phishing-email-analytics-task2
Cyber Security Internship -Task 2 Submission

# Cyber Security Internship - Task 2

##   Task Title:
**Analyze a Phishing Email Sample**

---

##   Phishing Email Used:
```
From: PayPal Support <support@paypalsecure.com>  
Subject: Your Account is Suspended!  

Dear Customer,  

Your PayPal account has been suspended due to suspicious activities. Please click the link below to verify your account immediately to avoid permanent suspension.  

👉 [Click here to verify](http://paypal-security-check.ru)  

Failure to comply will result in account termination.  

Thank you,  
PayPal Security Team
```

---

##   Phishing Indicators Identified:

1. **Fake sender address** – `support@paypalsecure.com` is not an official PayPal domain.
2. **Urgent language** – Threatens account suspension to scare the user.
3. **Suspicious link** – URL ends in `.ru` which is not associated with PayPal.
4. **Grammatical issues** – Unprofessional wording and errors.
5. **Request for personal action** – Asks user to verify via external link, which is unsafe.

---

##   Tools Used:
- Visual inspection
- Link hover method
- Common phishing knowledge

---

##   Header Analysis Note:
Header analysis could not be performed since the sample is not a real email.  
In real-world cases, tools like [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx) can help detect:
- Spoofing
- Relay IPs
- Authentication failures (SPF, DKIM, DMARC)

---

##   Files in This Repository:
- `phishing_email.txt` – The phishing email sample
- `email_analysis.txt` – Observations and phishing traits
- `README.md` – This file

---

## Status:
**Task Completed and Ready for Submission**
