# 🔐 Networkwalks Academy - Week 3
## John The Ripper - PDF Password Cracking

**Student:** Sana Ibrar
**Tool:** Johnny (John the Ripper GUI) + Networkwalks Hash Calculator
**Attack Type:** Dictionary / Wordlist Attack - 100 Passwords

## 🎯 Objective
Password protected PDF ka hash nikalna, usko John se crack karna, aur andar chhupa hua Flag capture karna.

## ✅ Final Results - 3/3 PDFs Cracked

| No | PDF File | Cracked Password | Flag Captured |
|----|----------|------------------|---------------|
| 1 | My-Locked-PDF1.pdf | password1 | nw{networkwalks_flag1_jtr_270521_1} |
| 2 | My-Locked-PDF2.pdf | 1qaz2wsx | nw{networkwalks_persistence_jtr_270521} |
| 3 | My-Locked-PDF3.pdf | 1qaz2wsx | nw{networkwalks_flag_260821_1} |

## 🔍 Step by Step Method

### Step 1: Hash Extract Karna
PDF ko Hash Calculator me upload kiya. PDF ka crackable hash mila.

### Step 2: Johnny me Attack
1. Johnny open kiya
2. Settings me john.exe ka path set kiya
3. Hash wali file JTR_default_password open ki
4. Start new attack dabaya

### Step 3: Password Crack
- PDF1 me: Trying: password1 -> MATCH password1
- PDF2 / PDF3 me: Trying: 1qaz2wsx -> MATCH 1qaz2wsx
- Johnny me 100% (1/1: 1 cracked, 0 left) aaya

### Step 4: PDF Unlock + Flag
Cracked password se PDF khola, andar Flag mila.

## 📸 Evidence - Week 3

### Lab 1 - PDF1 Password Cracked
![PDF1](./Week-3-PDF-Cracking/PDF1-Cracked.png)

### Lab 1 - Flag 1
![Flag1](./Week-3-PDF-Cracking/Flag1.png)

### Lab 2 & 3 - Password 1qaz2wsx Cracked
![PDF3](./Week-3-PDF-Cracking/PDF3-Cracked.png)

### Johnny - 100% Cracked Proof
![Johnny](./Week-3-PDF-Cracking/Johnny-100.png)

## 💡 What I Learned
- Hash kya hota hai aur PDF ka hash kaise nikalte hain
- John the Ripper se Dictionary Attack kaise chalate hain
- Weak password jaise password1 aur 1qaz2wsx kitni jaldi crack ho jate hain
