# w7-activator

# w7 activator

How to use it: first, download the repository or the release.

Run activate-test.bat to activate Windows 7, but please do not use this activator for piracy.

## 📌 About the project
This repository aims to **demonstrate and study** the concepts behind Windows 7 activation mechanisms, exploring:
- How software licensing works
- The role of `slmgr.vbs` as a license management tool
- The concept of KMS (Key Management Service) servers in corporate environments

⚠️ **Important notice**:
This project is **for educational purposes only**. this repositor contains instructions for illegal software activation but please do not use for piracy. Misuse of piracy techniques is against the law and can pose security risks and legal consequences.

---

## 🚀 Goals
- Understand how Windows manages licenses and activations
- Explore how KMS works in legitimate corporate environments
- Discuss ethical and legal implications of software piracy
- Serve as a basis for studies in security and system administration

---

## 📂 Repository chapters






Chapter 1 – slmgr.vbs /dli
What it does Displays basic license information.

Details

Edition of Windows (e.g., Professional).

Partial product key (last 5 characters).

Activation status.

Analogy Like looking at the cover of a book: you see the title but not all details.

Chapter 2 – slmgr.vbs /dlv
What it does Shows detailed license information.

Details

Activation ID, Installation ID.

Renewal intervals.

Activation status.

Analogy Like reading the fine print of a contract.

Chapter 3 – slmgr.vbs /xpr
What it does Displays whether activation is permanent or temporary.

Details

Retail licenses: “Permanently activated.”

KMS: Shows expiration date (usually 180 days).

Analogy Like checking the expiration date on food.

Chapter 4 – slmgr.vbs /ipk <valid-key>
What it does Installs a purchased product key.

Details

Required before online activation.

Replaces any previous key.

Analogy Like entering the correct password to access an account.

Chapter 5 – slmgr.vbs /ato
What it does Activates Windows online with Microsoft servers.

Details

Requires internet.

Validates installed key.

Analogy Like calling the bank to confirm your card is active.

Chapter 6 – slmgr.vbs /skms kms.company.com
What it does Sets the KMS server manually.

Details

Overrides DNS discovery.

Useful in enterprises.

Analogy Like manually setting the address of a doctor instead of searching.

Chapter 7 – slmgr.vbs /ckms
What it does Clears the KMS server setting.

Details

Client returns to automatic discovery.

Analogy Like deleting an old contact address.

Chapter 8 – slmgr.vbs /rearm
What it does Resets activation timer (evaluation mode).

Details

Usually allowed 3 times.

Analogy Like pressing the snooze button before buying a license.

Chapter 9 – slmgr.vbs /upk
What it does Uninstalls the current product key.

Details

Needed before transferring license.

Analogy Like removing the license plate from a car before selling.

Chapter 10 – slmgr.vbs /cpky
What it does Clears product key from registry.

Details

Prevents exposure of sensitive info.

Analogy Like shredding a confidential document.

Chapter 11 – slmgr.vbs /ilc license.xrm-ms
Installs a license file. Analogy: Adding an extra clause to a contract.

Chapter 12 – slmgr.vbs /rilc license.xrm-ms
Reinstalls a license file. Analogy: Reinstalling a digital certificate.

Chapter 13 – slmgr.vbs /dti
Displays installation ID for phone activation. Analogy: Receiving a protocol number.

Chapter 14 – slmgr.vbs /atp <confirmation-ID>
Activates with phone confirmation. Analogy: Entering a code sent by SMS.

Chapter 15 – slmgr.vbs /arm
Shows remaining rearm count. Analogy: Checking how many times you can hit snooze.

Chapter 16 – slmgr.vbs /skms kms.company.com
Sets KMS server manually. Analogy: Defining a manual address.

Chapter 17 – slmgr.vbs /ckms
Clears manual KMS server. Analogy: Removing an old address.

Chapter 18 – slmgr.vbs /sprt 1688
Sets KMS port. Analogy: Choosing which gate to enter.

Chapter 19 – slmgr.vbs /sdns kms.company.com
Configures DNS publishing for KMS. Analogy: Registering a store on Google Maps.

Chapter 20 – slmgr.vbs /ckdns
Clears DNS publishing. Analogy: Removing a business from the map.

Chapter 21 – slmgr.vbs /sai 30
Sets activation interval to 30 minutes. Analogy: Setting an alarm every half hour.

Chapter 22 – slmgr.vbs /sri 120
Sets renewal interval to 120 minutes. Analogy: Scheduling appointments every 2 hours.

Chapter 23 – slmgr.vbs /sprt 1700
Changes KMS port to 1700. Analogy: Changing the door of a house.

Chapter 24 – slmgr.vbs /sai 60
Activation interval 60 minutes. Analogy: Taking medicine every hour.

Chapter 25 – slmgr.vbs /sri 240
Renewal interval 240 minutes. Analogy: Checking emails every 4 hours.

Chapter 26 – slmgr.vbs /spri
Sets renewal interval for KMS clients. Analogy: Deciding how often to call a friend.

Chapter 27 – slmgr.vbs /dli all
Displays info for all licenses. Analogy: Listing all books you own.

Chapter 28 – slmgr.vbs /dlv all
Detailed info for all licenses. Analogy: Reading all contracts at once.

Chapter 29 – slmgr.vbs /xpr all
Shows expiration for all licenses. Analogy: Checking expiration dates in the fridge.

Chapter 30 – slmgr.vbs /ipk <Office-key>
Installs Office product key. Analogy: Entering the password for a safe.

Chapter 31 – slmgr.vbs /ato Office
Activates Office online. Analogy: Calling to confirm subscription.

Chapter 32 – slmgr.vbs /skms kms.office.company.com
Sets Office KMS server. Analogy: Defining a branch address.

Chapter 33 – slmgr.vbs /ckms Office
Clears Office KMS server. Analogy: Removing an old branch address.

Chapter 34 – slmgr.vbs /rearm Office
Resets Office activation timer. Analogy: Extending a trial period.

Chapter 35 – slmgr.vbs /upk Office
Uninstalls Office key. Analogy: Removing a property tag.

Chapter 36 – slmgr.vbs /cpky Office
Clears Office key from registry. Analogy: Shredding a confidential paper.

Chapter 37 – slmgr.vbs /dti Office
Displays Office installation ID. Analogy: Receiving a support ticket number.

Chapter 38 – slmgr.vbs /atp Office <confirmation-ID>
Activates Office by phone. Analogy: Entering a confirmation code.

Chapter 39 – slmgr.vbs /ilc office-license.xrm-ms
Installs Office license file. Analogy: Adding a contract clause.

Chapter 40 – slmgr.vbs /rilc office-license.xrm-ms
Reinstalls Office license file. Analogy: Reinstalling a certificate.

Chapter 41 – slmgr.vbs /arm Office
Shows Office rearm count. Analogy: Checking how many trial extensions remain.

Chapter 42 – slmgr.vbs /sprt 1689
Sets Office KMS port. Analogy: Choosing a different entrance.

Chapter 43 – slmgr.vbs /sai 45
Sets Office activation interval. Analogy: Setting a reminder every 45 minutes.

Chapter 44 – slmgr.vbs /sri 180
Sets Office renewal interval. Analogy: Scheduling check-ins every 3 hours.

Chapter 45 – slmgr.vbs /skhc Office
Sets Office host caching. Analogy: Saving a shortcut address.

Chapter 46 – slmgr.vbs /ckhc Office
Clears Office host caching. Analogy: Deleting a shortcut.

Chapter 47 – slmgr.vbs /sdns Office
Configures Office DNS publishing. Analogy: Registering a **branch on
