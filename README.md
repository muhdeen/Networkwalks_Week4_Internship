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



<img width="705" height="433" alt="Screenshot 2026-10-02 compress" src="https://github.com/user-attachments/assets/1d9806fd-c130-47b6-a92f-dbe7c834a38d" />
<img width="885" height="397" alt="Screenshot 2026-10-02 hash" src="https://github.com/user-attachments/assets/41e51f07-7d72-436d-8f4a-e87c961dfd39" />
<img width="691" height="399" alt="Screenshot 2026-10-02 cracking" src="https://github.com/user-attachments/assets/bcdecd0a-a695-439e-bc48-24faa743bef0" />
<img width="443" height="350" alt="Screenshot 2026-10-02 jtr" src="https://github.com/user-attachments/assets/0b6cdcc5-4358-4301-8d82-85765e614a79" />
<img width="860" height="406" alt="Screenshot 2026-10-02 LOGIN" src="https://github.com/user-attachments/assets/09f40231-3fba-4f2b-8e21-0da1adb7bf85" />
<img width="832" height="454" alt="Screenshot 2026-10-02 MEDIROZA " src="https://github.com/user-attachments/assets/aeaef15f-61e7-4c9b-acea-a26580238e53" />
<img width="676" height="454" alt="Screenshot 2026-10-02 proof pdf-1" src="https://github.com/user-attachments/assets/91b0032d-b39a-48bc-ae19-74e193eaff48" />
<img width="681" height="432" alt="Screenshot 2026-10-02 pdf 2" src="https://github.com/user-attachments/assets/1146ddb2-f57b-49c7-909f-0db4c53b8f47" />
<img width="723" height="457" alt="Screenshot 2026-09-29 192443" src="https://github.com/user-attachments/assets/5b48a7d1-8881-4e79-8ccf-45846066e636" />
<img width="383" height="232" alt="Screenshot 2026-10-02 tsk3" src="https://github.com/user-attachments/assets/8c70a2b5-338c-4ccc-bc3e-bda0506804a7" />

