# Digital Forensics & Incident Response (DFIR) Portfolio

Welcome to my central repository for digital forensics investigation and analysis reports. This space documents hands-on forensic acquisition, malware preservation, pattern-matching decoding, and structural parsing across various media types.

---

## 📂 Forensic Investigation Index

| Case ID | Investigation Target | Analytical Domain & Core Focus | Tools Utilized | Documentation Link |
| :--- | :--- | :--- | :--- | :--- |
| **Case 001** | 8 GB USB Flash Drive Data Recovery | Media Acquisition, Formatting Ingest, & File Carving | FTK Imager, Autopsy 4.22.1 | [View Report & Findings](./Digital%20Acquisition%20and%20Imaging%20Report.pdf) |
| **Case 002** | Password Cracking & Type Disambiguation | Hash Identification, Collision Resolution, & Dictionary Triage | Hashcat, John the Ripper, ANANSE | [View Password Lab](./Password%20Cracking%20%20Report.PDF) |
| **Case 003** | Hidden Container Objects & Mismatches | Signature Intelligence, File Structure Verification, & Hex Triage | HIVE Analyzer, HxD Hex Editor | [View Falcon Project](./_Project%20Falcon%20Forensics%20Report.pdf) |
| **Case 004** | Web Browser Artifact Analysis | Session Carving, History Timelines, & SQL Triage Extraction | Browser History Examiner (BHE) | [View Browser Forensics](./Browser_Forensics_Report.pdf) |

---

## 🛠️ Technical Skillset Demonstrated

### 1. Evidence Preservation & Media Triage
* **Physical Bit-Stream Acquisition:** Configuring structural fragment blocks, split imaging limits, and managing host write-block environments.
* **Cryptographic Parity Verification:** Confirming file and image validation integrity values across standard algorithms (`MD5`, `SHA-1`, and `SHA-256`) to maintain pristine tracking chains.

### 2. Deep Structural Analysis & Carving
* **Signature Mismatch Resolution:** Utilizing raw offset hex analysis (`OLE2` structures vs `PKZIP` magic headers like `50 4B 03 04`) to safely expose concealed system file extension wrappers.
* **Cryptographic Triage:** Identifying target string algorithms by character hex length metrics and navigating credential collision patterns (such as `MD5 vs NTLM` or `SHA-512 vs Whirlpool`).
* **Artifact Extraction Engines:** Parsing active, deleted, or orphaned metadata structures directly out of raw physical sectors.

### 3. Application & Live Triage Forensic Engineering
* **Web Database Extraction:** Reconstructing systemic timelines from local database nodes tracking user website visits, cached web page images, active sync login files, and cookie artifacts.
* **Target Index Optimization:** Executing regular expression passes and keyword array indexing sweeps to recover credential patterns and raw message variables from unallocated space segments.

---

## 📜 Professional Compliance Standards
All processing pipelines, verification logs, and timeline analyses within these cases are intentionally modeled to maintain defensive alignment with:
* **ISO/IEC 27037:2012** Guidelines for identification, collection, acquisition, and preservation of digital evidence.
* **NIST Special Publication 800-86:** Guide to Integrating Forensic Techniques into Incident Response.
