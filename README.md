# Phishing Email Analysis
#-----------------------------------------------------------------------------------------------------------------------------------------------------#
## Overview
This project contains the analysis of a suspicious phishing email.  
The email claimed to be from `press@wikimedia.org`, but header and content analysis confirmed it as a phishing attempt.

## Files
- `report.md` → The phishing analysis report in a simple, checklist format.  
- `README.md` → This file, explaining the project.  

## Steps Performed
1. Saved the raw phishing email as `sample.email`.  
2. Extracted and reviewed the headers (SPF, DKIM, DMARC, Received paths).  
3. Extracted links from the body and compared displayed vs real URLs.  
4. Checked for attachments (none found in this case).  
5. Documented language, urgency, and social engineering indicators.  
6. Wrote findings into `report.md`.  
7. Redacted sensitive IPs and emails before committing to GitHub.  

## Tools Used
- Linux terminal utilities (`grep`, `awk`, `sed`)  
- Text editor (`nano`)  
- WHOIS and epieos
- Markdown for documentation  

## How to View
- Open `report.md` to read the phishing analysis.  
---


