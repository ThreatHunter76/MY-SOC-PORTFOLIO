# OSINT Domain Risk Assessment – SOC Project

## Overview
This project demonstrates a hands-on SOC-style investigation of a target domain using
Open-Source Intelligence (OSINT) techniques to assess cybersecurity, scam, and fraud risk.

The assessment focuses on domain reputation, historical infrastructure behavior,
and trust indicators rather than relying solely on real-time malware detections.

---

## Objective
To determine whether a target domain presents indicators of malicious, scam, or
high-risk behavior by analyzing:
- Domain reputation
- Hosting and infrastructure history
- DNS and SSL trust indicators
- Presence in intelligence datasets

---

## Tools & Techniques
- *VirusTotal* – reputation analysis and malware detection
- *Passive DNS* – historical IP and hosting behavior analysis
- *DNS analysis* – infrastructure and stability review
- *SSL/TLS inspection* – certificate trust evaluation
- *OSINT methodology* – correlation of open-source intelligence indicators

---

## Key Findings
- No current malware detections on VirusTotal, highlighting the limitation of
  signature-based detection alone
- Historical DNS and hosting data revealed infrastructure reuse and association
  with previously flagged IP addresses
- Low-reputation DNS and email infrastructure commonly linked to phishing and
  short-lived malicious operations
- Presence in intelligence datasets suggests prior investigative interest and
  elevated risk

---

## Risk Assessment Summary
| Category | Assessment |
|--------|------------|
| Current malware detection | Low |
| Historical infrastructure risk | High |
| DNS and hosting reputation | Low trust |
| Domain stability and usage | Suspicious |
| Overall scam and fraud risk | *High* |

---

## Conclusion
Despite the absence of active malware detections, historical infrastructure behavior,
poor reputation indicators, and intelligence dataset presence strongly suggest that
the domain represents a *high-risk and untrustworthy environment*.

This reinforces the importance of historical and contextual analysis in SOC operations.

---

## Recommendations
- Avoid using the domain for financial transactions
- Do not submit personal or sensitive information
- Do not rely on SSL presence as proof of legitimacy
- Continue monitoring for infrastructure or reputation changes

---

## Analyst Takeaways
- A clean VirusTotal score does not guarantee safety
- Passive DNS history is a strong indicator of malicious behavior
- SSL certificates validate encryption, not legitimacy
- Infrastructure quality often reveals malicious intent
- Domain history is a key predictor of scam activity

---

## Skills Demonstrated
- Threat intelligence analysis
- OSINT investigations
- Domain and infrastructure analysis
- Risk assessment and reporting
- SOC-style analytical documentation

---

## Report
📄 *OSINT_Domain_Risk_Assessment_Report.pdf*
