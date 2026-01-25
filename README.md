# Active-Directory-User-Management
Creating a new domain user in Active Directory Users and Computers (ADUC), setting password options, and verifying the account in the domain.
# Creating a User in Active Directory (ADUC)

## 🎥 Watch me build this lab here
**Watch me build this lab here:** [LOOM VIDEO LINK](https://www.loom.com/share/7f76cc5fd3294dacac963a14ead1a864) 

---

## 🧭 Objective
Create a new domain user in **Active Directory Users and Computers (ADUC)** and apply basic account security settings (strong password + password policy selection).

## 🧠 Skills Practiced
- Navigating **Active Directory Users and Computers (ADUC)**
- Creating a new user object in a domain
- Applying password/security options (e.g., password policy choices)
- Verifying successful user creation

## 🧰 Tools Used
- Windows Server (Domain Controller)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)

---

## 🪜 Steps Performed (with screenshots)

### 1) Start user creation in ADUC (Users container)
Created a new user under the domain container and entered the user’s identity fields (name + username).
![Create User - Details](images/createuserAD1.png)

### 2) Set a strong password + account options
Configured a secure password and selected the appropriate password/account settings for the lab.
![Create User - Password](images/createuserAD2.png)

### 3) Verify successful creation of the user
Confirmed the user was created and is visible in ADUC (and/or reviewed properties to validate the account).
![Create User - Verified](images/createuserAD3.png)

---

## ✅ Outcome
Successfully created a new Active Directory user account and verified it exists in the domain, demonstrating basic identity administration and account security awareness.

## 🔁 Next Improvements
- Create a dedicated **OU** (e.g., `IT`, `Students`, `Staff`) and place users accordingly  
- Add the user to a security group (least privilege)  
- Enforce password policies via **Group Policy** and test login behavior
