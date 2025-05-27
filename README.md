#  Phishing Email Analysis – Assignment Report

##  Task 2: Analyze a Phishing Email Sample

This repository contains a brief analysis of a phishing email sample, completed as part of a cybersecurity assignment. The goal of this task is to identify and document phishing characteristics present in a suspicious email.

---

##  Objective

To investigate a suspicious email and identify common phishing indicators, such as spoofed sender addresses, mismatched URLs, urgent language, and malicious attachments.

---

##  Tools Used

- Online Email Header Analyzer: [MxToolbox](https://mxtoolbox.com/EmailHeaders.aspx)
- Sample phishing email (text format)

---

## Analysis Performed

### 1. **Sender Address Inspection**
- The sender’s email was `security-update@paypa1.com`, which is a spoofed domain imitating PayPal.
- The domain uses a numeral '1' instead of the letter 'l' to deceive the recipient.

### 2. **Email Header Analysis**
- The header was analyzed using MxToolbox.
- SPF check: **Failed**
- DKIM: **Missing**
- IP address: Originated from an unusual location, not associated with PayPal's official servers.

### 3. **Links & Attachments**
- Displayed link: `https://www.paypal.com/login`
- Actual link (on hover): `http://verify-paypal-login.com`
- Attachment: `Account_Update_Form.zip` – likely a malicious file.

### 4. **Language and Tone**
- The email used urgency and threats, such as:
  - “Your account has been locked.”
  - “Verify within 24 hours or get suspended.”

### 5. **Grammar and Spelling**
- Several grammatical and spelling mistakes were present.
- Unprofessional tone, indicating it was not sent by a legitimate organization.

---

##  Summary of Phishing Indicators

| Indicator               | Description                                              |
|-------------------------|----------------------------------------------------------|
| Spoofed Email Address   | Used fake domain `paypa1.com`                            |
| Failed SPF/DKIM Checks  | No verification, possibly spoofed source                 |
| Mismatched Links        | URL points to phishing site                             |
| Suspicious Attachment   | `.zip` file, often used to deliver malware               |
| Urgent/Threatening Tone | Forces user to act quickly under pressure                |
| Poor Grammar            | Multiple writing mistakes, unprofessional presentation   |

---

##  Conclusion

This phishing email displays multiple warning signs that are commonly associated with phishing attacks. It includes a spoofed sender, mismatched URLs, a suspicious file attachment, and manipulative language. The analysis highlights the importance of careful inspection of unsolicited emails, especially those requesting sensitive information or immediate action.

---

##  Learning Outcome

This task helped me better understand how to identify phishing emails by analyzing both the content and the metadata (headers). I also learned how attackers use psychological and technical tricks to deceive users.

---


