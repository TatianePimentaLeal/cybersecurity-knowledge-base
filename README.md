# Cybersecurity Knowledge Base Organization

Curation of a knowledge base containing cybersecurity terms, tools, and their definitions.

This repository is organized with the Dewey Decimal Classification system:

├── 000_Generalities_&Computer_Science/

│ ├── 003_Systems/

│ │ └── 003.54_Information_Theory&Cryptography/

│ ├── 004_Data_Processing&Computer_Science/

│ │ ├── 004.62_Network_Protocols/

│ │ └── 004.678_Internet&Network_Security/

│ └── 005_Computer_Programming_Programs&Data/

│ ├── 005.1_Software_Engineering&AppSec/

│ ├── 005.8_Data_Security&Hacking/

│ └── 005.84_Malware&Reverse_Engineering/

├── 300_Social_Sciences&Law/

│ ├── 343_Military_Commercial&Industrial_Law/

│ │ └── 343.0999_Cyber_Law&Regulations/

│ └── 355_Military_Science/

│ └── 355.02_Cyber_Warfare/

├── 400_Language&Linguistics/

│ └── 413_Dictionaries&_Terminologies/

└── [INDEX.md](https://github.com/TatianePimentaLeal/cybersecurity-knowledge-base/blob/main/INDEX.md)

## General Information Organization Rules

### **1 Data Mapping Overview**

- **004.62 (Protocols):** Articles and PDFs about HTTP/2, WebSockets, DNS, TLS/SSL, and network infrastructure failures.

- **005.1 (AppSec):** Books about the software secure development lifecycle (SDLC), OWASP Top 10 and OWASP API Top 10 guidelines, code review methodologies and pipeline, and DevSecOps security for CI/CD.  

- **005.8 (Bug Bounty & Hacking):** Vulnerability write-ups (XSS, SQLi, SSRF), recon methodologies (reconnaissance), script automation, and platform reports (as HackerOne, Bugcrowd, etc.).  

- **343.0999 (Legislation and Regulation):** PDFs and URL sources about international laws (LGPD, GDPR, HIPAA, PCI-DSS, “Marco Civil da Internet” - Brazil).  

- **413 (Terminologies):**  Glossary of technical terms, payload dictionaries, acronym lists (eg. SIEM, EDR, WAF), and vulnerability taxonomy (eg. CWE, CVE).

### 

### **2 File Naming Patterns**

To keep the PDFs, URL/link, and notes properly organized inside each DDC folder, standardized suffixes are used to identify each media type:  

- **005.8_book_web-hacking-101.md** (For abstracts or book recommendations)  

- **005.8_article_ssrf-analysis.pdf** (For local PRD files)  

- **005.1_link_owasp-asvs.md** (For centralized external links about specific topics)  

- **343.0999_law_lgpd-updated.md** (For transcriptions or legislation notes)

#### 2.1 File Type Prefixes

Use of lowercase and uniform prefixes for media types ensuring clean alphabetical sorting inside the DDC folders:

- book_ recommendations, notes, and reviews

- paper_ academic journal articles

- law_ international regulations and legal compliance text

- writeup_ bug bounty reports and vulnerability analyses

- term_ items definitions and quick information reference
