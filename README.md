# NETWORKWALKS-B083-WK3-PM2-PASSWORD-CRACKING-WITH-NW-TOOLS
# 🔐 Password Cracking Lab Using NetworkWalks Tools             
## 📌 Project Overview

This project was a practical exercise on **password security and password recovery** using **NetworkWalks Tools**.

The main goal was to understand how password-protected PDF files can be assessed in an authorized lab environment. I worked with three PDF files, extracted their password hashes, used NetworkWalks Tools to perform password cracking, and then used the recovered passwords to open the original PDF files.

> ⚠️ **Ethical Notice:** This practical was performed only on files used for the authorized cybersecurity exercise. Password cracking should only be carried out on systems and files where permission has been given or where you are the owner.

---

# 🎯 Objectives

The main objectives of this practical were to:
- Use NetworkWalks Tools to recover the passwords.
- Verify the recovered passwords by opening the protected PDF files.
- Understand the basic process of password hash cracking.

---

# 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Password Cracker** | Used to crack the extracted password hashes |
| **Hash Calculator** | Used to extract password hashes from the PDF files |
| **Password-Protected PDF Files** | Used as the target files for the practical |

---

# 🔎 Practical Steps

## Step 1: Open Hash Calculator
https://networkwalks.com/hash-calculator/

![John the Ripper Installation](screenshots/01-john-installation.png)

---

## Step 2: Click PDF and Choose the PDF To Get The Hash Then Copy it

![PDF Hash Extraction](screenshots/02-pdf-hash-extraction.png)

---

## Step 3: Open Password Cracker and Paste the Hash

![Hash Files](screenshots/03-hash-files.png)

---

## Step 4: After Getting the Password Open the Document

![John the Ripper Cracking](screenshots/04-john-cracking.png)

---

# 💡 What I Learned

Through this practical, I learned how password-protected files can be assessed through their extracted password hashes.

I also learned that the password itself is not directly stored in the hash file. Instead, a hash value is extracted and then analyzed by a password-cracking tool such as John the Ripper.

The exercise helped me understand the relationship between:

**PDF File → Password Hash → NW Tools→ Recovered Password → PDF Access**

Most importantly, I learned the importance of using strong passwords. Weak and predictable passwords can be easier to recover during a password-cracking exercise, while stronger passwords are generally more difficult to guess.

---

# 🔐 Security Recommendations

Based on this practical, I recommend:

- Use long and unique passwords for sensitive files.
- Avoid common words and easily guessed information.
- Do not reuse the same password for different files or accounts.
- Use a password manager when managing many passwords.
- Keep password-protected files in secure storage.
- Perform password auditing only with proper authorization.

---

## 👤 Author

**Gasper Boniphace**  
Cybersecurity Professional — **B083**

---

## 📌 Project Information

| Item | Details |
|---|---|
| **Project** | Password Cracking with NetworkWalks Tools  |
| **Tool** | Password Cracker, Hash Calculator |
| **Files Tested** | 3 Password-Protected PDF Files |
| **Hash Extraction Tool** | PDF Hash Extractor |
| **Program** | Cybersecurity Program |
| **Batch** | B083 |

---

**End of Report**
