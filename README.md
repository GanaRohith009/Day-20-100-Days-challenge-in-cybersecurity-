# Day-20-100-Days-challenge-in-cybersecurity-
# 🗓️ Day 20: Automated SQL Injection with SQLMap

**Focus:** Transitioning from manual SQLi analysis to automated exploitation using standard industry tools.

## 🚀 Key Learnings
* **Manual vs. Automated:** Understood the limitations of manual payloads (time-consuming, prone to typos) vs. the scalability of automation.
* **Database Fingerprinting:** How SQLMap automatically identifies the database engine (MySQL, PostgreSQL, Oracle), OS, and web server version.
* **Exploitation Types:**
    * *Error-Based SQLi:* Extracting data via visible database errors.
    * *Blind SQLi:* Automating boolean-based and time-based queries to reconstruct data character-by-character.
* **Data Exfiltration:** Dumping database tables, columns, and user credentials.
* **System Access:** Theoretical understanding of `--os-shell` to execute system commands via the database.

## 🛠️ Tools Used
* **SQLMap:** Open-source penetration testing tool.
* **Kali Linux:** Environment for running the tool.

## 📝 Commands Explored
* `sqlmap -u [URL]` : Basic check for vulnerabilities.
* `--dbs` : List available databases.
* `--tables` : List tables in a specific database.
* `--dump` : Dump table entries (simulating data theft).
* `--batch` : Run non-interactively (default behaviors).

---
*Disclaimer: All tests were performed on a legally authorized hacking lab/CTF environment. These notes are for educational purposes only.*
