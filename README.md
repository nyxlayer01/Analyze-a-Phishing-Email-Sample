# Analyze-a-Phishing-Email-Sample
A practical email security analysis project that investigates a phishing email sample by inspecting its headers, identifying spoofing tactics, and highlighting common phishing indicators.

This project focuses on identifying and documenting key phishing indicators found in a suspicious email sample. The analysis includes inspecting sender details, email headers, embedded links, and the overall structure of the message. The goal is to demonstrate how phishing emails can be identified using freely available tools and basic investigative methods.

## Key Analysis Steps

1. Opened the `.eml` file in an email client (e.g., Thunderbird)
2. Inspected sender email and domain (spoofed `paypal-security-alerts.com`)
3. Extracted and analyzed email headers using:
   - Google Message Header Analyzer
   - MXToolbox Email Header Tool
4. Identified missing SPF and DKIM authentication headers
5. Noted language, formatting, and urgency tactics in the email body

## Tools Used

- Email client (Thunderbird or similar)
- Google Admin Toolbox – Message Header Analyzer  
  https://toolbox.googleapps.com/apps/messageheader/
- MXToolbox Header Analyzer  
  https://mxtoolbox.com/EmailHeaders.aspx
- Markdown for documentation

## Conclusion

This repository demonstrates how a phishing email can be broken down and analyzed to understand the common tactics used by attackers. The project serves as a learning resource for recognizing red flags and applying basic cybersecurity hygiene when dealing with suspicious messages.
