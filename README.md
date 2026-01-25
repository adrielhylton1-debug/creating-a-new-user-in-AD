# Active-Directory-User-Management
Creating a new domain user in Active Directory Users and Computers (ADUC), setting password options, and verifying the account in the domain.
# Creating a User in Active Directory (ADUC)

## Watch me build this lab here
- Loom walkthrough: https://www.loom.com/share/7f76cc5fd3294dacac963a14ead1a864

---

## Objective
Create a new domain user in **Active Directory Users and Computers (ADUC)** and verify the account was created successfully.

## Skills Practiced
- Navigating **ADUC** (domain tree, Users container)
- Creating a new user object
- Applying password options (basic security awareness)
- Verifying account creation via user listing / properties

## Tools Used
- Windows Server (Domain Controller)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)

---

## Steps Performed

### 1) Start user creation in ADUC (Users container)
Opened **ADUC → domain → Users**, then initiated **New → User** and entered the user’s identity fields.
  
![Create user wizard (identity fields)](images/createuserAD1.png)

---

### 2) Set password + account options
Configured a strong password and selected the appropriate options (ex: password behavior) for the lab scenario.

![Create user wizard (password + options)](images/createuserAD2.png)

---

### 3) Verify successful user creation
Confirmed the user appears in the **Users** container and reviewed properties to validate the account exists and is configured.

![User successfully created (verification/properties)](images/createuserAD3.png)

---

## Outcome
A new domain user was successfully created in Active Directory and verified in ADUC.

## Notes
- If images don’t render, it’s almost always a **path/filename mismatch** (GitHub is case-sensitive).
  - Confirm your repo has: `images/createuserAD1.png`, `images/createuserAD2.png`, `images/createuserAD3.png`
  - If your files are named like `CreateUserAD1.png`, update the links above to match **exactly**.
