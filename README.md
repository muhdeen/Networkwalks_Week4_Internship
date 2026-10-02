# Networkwalks_Week4_Internship

# Mediroza General Hospital – Penetration Testing Report (Week 4 Internship)

## Author
Shamsuddeen Muhammad

## Summary
- Discovered unauthenticated SQL backup exposure (30 staff + 10 shareholder records).
- Bypassed patient login via SQL injection (`admin' -- `).
- Retrieved and decrypted three encrypted patient pathology reports.
- Overall risk rating: **High**.

## Tools
- Kali Linux
- curl, grep, cat
- Networkwalks Password Cracker
- PDF Hash Extractor
- John the Ripper

## Findings
- SQL Backup Exposure – High
- Directory Indexing – Low
- Patient Login SQL Injection – High

## Milestones
- M1: Retrieved all patient PDFs
- M2: Cracked all PDF passwords
- M3: Extracted staff/shareholder records
- M4: Produced professional report

## Remediation
- Remove SQL backups from web root
- Fix patient login query construction
- Disable directory indexing
- Review backup processes
