# NETWORKWALKS-B084-WK3-PM1-PSWWORD-CRACKING-WITH-JTR
CYBERSECURITY AND ETHICAL HACKING PROJECT    

### Cybersecurity Internship – Batch B084
 
**Week:** 03  
**Project Modules:** PM1 & PM2  
**Topic:** PDF Password Cracking using John the Ripper and Networkwalks Tools

---

## 📌 Project Overview

This repository contains the practical implementation of Week 3, Project Modules 1 and 2, completed as part of the **Networkwalks Cybersecurity Internship (Batch B084)**.      


The objective of this project was to recover the password of a password-protected PDF file (`My Locked PDF1.pdf`) using two different password-cracking approaches:

1. **John the Ripper (JTR) and Johnny GUI**
2. **Networkwalks Hash Calculator and Password Cracker**

Both methods demonstrate how password hashes can be extracted and tested against dictionary-based password attacks.

---

# 🛠️ WK3-PM1: Password Cracking Using John the Ripper

### 🎯 Objective
To extract the password hash of a protected PDF and recover its password using John the Ripper (JTR) and its graphical interface, Johnny.

### 🔧 Tools Used
- John the Ripper (JTR)
- Johnny GUI
- Online HashCrack PDF Hash Extractor
- Password-protected PDF file

### ⚙️ Steps Performed

**Step 1: Extract PDF Hash**

Uploaded the protected PDF to the Online HashCrack PDF Hash Extractor and generated its password hash in `$pdf$...` format.

The extracted hash was saved in a file named `hash1.txt`.    

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 3 07 05 pm" src="https://github.com/user-attachments/assets/b1941a48-242e-4e36-9ca8-db7e9231195d" />          


----    




**Step 2: Configure Johnny**

Opened Johnny, the graphical interface of John the Ripper, configured the John executable path, and loaded `hash1.txt` using the Open Password File option.

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 2 55 38 pm" src="https://github.com/user-attachments/assets/ebc9ad10-a6d4-4726-ba73-28211c8182b1" />      


----      

**Step 3: Perform Password Cracking**

Started the password-cracking process using Johnny.

The tool successfully recovered the password.

<details>
<summary>🔑 View Cracked Password</summary>

**Recovered Password:** `good-luck`

**Result:** 1 password cracked (100%).

</details>      

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 3 12 33 pm" src="https://github.com/user-attachments/assets/53bb3fea-25b5-4451-a1c9-bf3f146b2220" />      

-----        


**Step 4: Verify the Password**

Opened the protected PDF using the recovered password to confirm that the password-cracking process was successful.    

<img width="764" height="589" alt="Screenshot 2026-11-20 at 3 17 50 pm" src="https://github.com/user-attachments/assets/226cac30-8c11-4204-8822-e6007f9b4640" />       


----


### ✅ PM1 Result

Successfully recovered and verified the PDF password using John the Ripper and Johnny GUI.


--------    

# 🌐 WK3-PM2: Password Cracking Using Networkwalks Tools

### 🎯 Objective
To recover the password of the same protected PDF using Networkwalks' browser-based Hash Calculator and Password Cracker.

### 🔧 Tools Used
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Password-protected PDF file

### ⚙️ Steps Performed

**Step 1: Generate PDF Hash**

Uploaded the protected PDF to the Networkwalks Hash Calculator.

The tool extracted the PDF password hash in `$pdf$...` format.    

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 5 03 49 pm" src="https://github.com/user-attachments/assets/5cb69bf6-2483-4a97-811e-80c6a7040159" />    


----    


**Step 2: Perform Dictionary Attack**

Copied the extracted hash and pasted it into the Networkwalks Password Cracker.

Selected the dictionary attack method and started the cracking process.

The tool successfully recovered the password.

<details>
<summary>🔑 View Cracked Password</summary>

**Recovered Password:** `password1`

</details>

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 5 40 13 pm" src="https://github.com/user-attachments/assets/8fc6cb40-9fff-43d7-bfee-5bee4be78819" />      


----        
**Step 3: Verify the Password**

Used the recovered password to open the protected PDF and confirmed that the file was successfully unlocked.

<img width="1440" height="900" alt="Screenshot 2026-11-20 at 5 40 13 pm" src="https://github.com/user-attachments/assets/4ecd3a51-04f6-40fa-9097-ea529b55a317" />      

-----        


<img width="1440" height="900" alt="Screenshot 2026-11-20 at 5 44 06 pm" src="https://github.com/user-attachments/assets/48760a0f-bb68-467f-9e8d-1fba52830a13" />


### ✅ PM2 Result

Successfully recovered and verified the PDF password using the Networkwalks online password-cracking tools.

---    

# 📊 Comparison: PM1 vs PM2

| Feature | PM1 – JTR | PM2 – Networkwalks |
|---|---|---|
| Tools | John the Ripper & Johnny | Networkwalks Online Tools |
| Interface | Desktop GUI | Web-based |
| Hash Extraction | Online HashCrack | Hash Calculator |
| Attack Method | Password cracking | Dictionary attack |
| Installation | Required | Not required |
| Recovered Password | `good-luck` | `password1` |

---

# 💡 Key Learnings

Through these practical exercises, I learned:

- How to extract password hashes from protected PDF files.
- How PDF password hashes are represented in `$pdf$...` format.
- How to configure and use John the Ripper with Johnny GUI.
- How to perform dictionary-based password attacks.
- How to use browser-based password-cracking tools.
- How to verify recovered passwords by opening protected files.
- Why short and predictable passwords are vulnerable to dictionary attacks.

### 🔐 Security Takeaway

Weak and predictable passwords can be recovered quickly using publicly available password-cracking tools.

Using long, unique, and complex passwords helps improve security and reduces the risk of unauthorized access.


### ⚠️ Disclaimer

This project was conducted strictly for educational and cybersecurity training purposes as part of the     












