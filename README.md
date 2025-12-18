# cyber-internship-task6
# 🔐 Task 6 — Password Strength Evaluation
**Elevate Labs — Cyber Security Internship**

---

## 📌 Objective
The objective of this task is to understand how password complexity, length, and
unpredictability affect password security by evaluating multiple sample passwords
using an online password strength testing tool.

---

## 🛠 Tools Used
- Online Password Strength Testing Tool
- Web Browser
- Windows 10

---

## 🚀 Methodology
1. Created multiple **sample passwords** with varying levels of complexity.
2. Tested each password using an online password strength checker.
3. Observed password strength ratings and estimated cracking time.
4. Compared weak, medium, strong passwords, and passphrases.
5. Analyzed why certain passwords are easier or harder to crack.
6. Documented security observations and best practices.

> ⚠️ Note: All passwords used in this task are **sample/demo passwords only** and
> do not correspond to any real accounts.

---

## 🔍 Password Strength Analysis

### 1️⃣ Weak Password
**Password Tested:** `password123`

- Very common and predictable
- Found in most password dictionaries
- No special characters
- Short length

**Strength Rating:** Very Weak  
**Estimated Time to Crack:** Less than a second  

---

### 2️⃣ Medium Complexity Password
**Password Tested:** `Pass@1234`

- Includes uppercase, lowercase, numbers, and a symbol
- Still short in length
- Partially predictable pattern

**Strength Rating:** Very Weak  
**Estimated Time to Crack:** 17 minutes  

---

### 3️⃣ Strong Password
**Password Tested:** `X9@fL#2Qm!8z`

- Random combination of characters
- Includes uppercase, lowercase, numbers, and symbols
- High entropy

**Strength Rating:** Good  
**Estimated Time to Crack:** 3 years  

---

### 4️⃣ Passphrase
**Password Tested:** `Blue-Horse!River_92`

- Long and memorable
- High entropy due to length
- Resistant to brute-force and dictionary attacks

**Strength Rating:** Strong  
**Estimated Time to Crack:** Centuries  

---

## 🧠 Common Password Attacks

### 🔹 Brute Force Attack
Attempts all possible character combinations until the correct password is found.
Longer passwords significantly increase cracking time.

### 🔹 Dictionary Attack
Uses predefined wordlists containing common passwords and phrases.
Simple or commonly used passwords are cracked very quickly.

---

## 🔐 Best Practices for Creating Strong Passwords
- Use **12–16+ characters**
- Prefer **passphrases** over short complex passwords
- Combine uppercase, lowercase, numbers, and symbols
- Avoid common words, names, and patterns
- Use unique passwords for each account
- Enable **Multi-Factor Authentication (MFA)**
- Store passwords securely using a password manager

---

## 📁 Repository Structure
├── README.md

└── screenshots/

├── weak-password.png

├── medium-password.png

├── strong-password.png

└── passphrase.png

---

## 📝 Conclusion
This task demonstrates how password strength is influenced not just by complexity,
but also by **length and unpredictability**. The results clearly show that simple or
pattern-based passwords are cracked quickly, while long passphrases provide
significantly stronger security and are far more resistant to common attacks.
Even “complex-looking” passwords can still be weak if they are short or patterned.
