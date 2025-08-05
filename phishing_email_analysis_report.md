
# Phishing Email Analysis Report

## Email Summary

- Subject: Action Required: Unusual Login Attempt Detected
- From: "PayPal Support" <support@paypal-security-alerts.com>
- To: user@example.com
- Reply-To: support@paypal-security-alerts.com
- Originating IP: 185.123.45.67

---

## Identified Phishing Indicators

### 1. Spoofed Sender Address
The email appears to be from "PayPal Support", but the domain used is `paypal-security-alerts.com`, which is not affiliated with PayPal.

### 2. Suspicious IP Address
The header indicates the email originated from IP `185.123.45.67`, which traces to Russia—an unusual source for PayPal communications.

### 3. Fake Login Link
The email includes the link `https://paypal-security-center.com/login` which looks similar to a real PayPal link but redirects to a phishing website.

### 4. Urgent and Threatening Language
Phrases like “Failure to do so may result in temporary suspension” are used to scare the user into clicking the link quickly.

### 5. Missing Authentication Headers
The email lacks SPF and DKIM headers, which are typically present in legitimate emails from verified senders.

### 6. No Personalization
Generic greeting used: “Dear Customer” instead of the recipient’s actual name or details.

---

## Tools Used

- Email client (e.g., Thunderbird) to view the email and headers
- Google Message Header Analyzer
- MXToolbox Header Analyzer

---

## Conclusion

This email is a phishing attempt. It uses spoofed branding, urgency, and misleading URLs to trick users into revealing sensitive information. Additionally, it lacks standard email authentication mechanisms. It should be reported and deleted without interacting with any links or attachments.
