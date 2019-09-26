
# UiPath Security Training

https://www.uipath.com/ja/academy/training#menu

## Quiz

---

### 1) User access to the Orchestrator web app is protected using the following features
- [-] a) session cookies are avoided; b) only registered users can access Orchestrator - they can request access using a Registration form; c) User account is automatically locked after 30 minutes of inactivity
- [-] a) communication between client and Orchestrator is encrypted with HTTPS; b) Password complexity is very strong and cannot be lowered; c) the account is locked after 3 unsuccessful attempts and can only be unlocked by system admin
- [o] a) communication between client and Orchestrator is encrypted with HTTPS; b) Password complexity is configurable; c) the account is locked after a configurable number of unsuccessful attempts

---

### 2) Access to a local package that is executed by the robot is granted to:
- [-] Robot executor and local admin
- [o] Robot service and local admin
- [-] Robot service only

---

### 3) A robot receives the login credentials along with the start command.
- [o] False
- [-] True

---

### 4) What are the most common security threats that a code reviewer can cover?
- [-] a) not sending email from the workflow; b) not storing sensitive data in local files; c) not using hardcoded URLs, accounts or email addresses
- [-] a) not sending information to outside systems; b) not storing the result of the workflow execution; c) not using email addresses written in the code
- [o] a) not sending email to private accounts, from the workflow; b) not storing sensitive data in local files; c) not using hardcoded URLs, accounts or email addresses

---

### 5) Passwords in Orchestrator platform:
- [o] must be changed on the first login
- [o] can be set to expire after a certain numbers of days
- [-] cannot be changed without a direct request to your platform administrator
- [-] are stored in plain text in the SQL DB

---

### 6) Account Lockout settings are configurable per:
- [-] User
- [-] Orchestrator
- [o] Tenant

---

### 7) Password History allows administrators to prevent the users from reusing old password, unless it is beyond the password history length.
- [-] False
- [-] True

---

### 8) Security risks can appear in:
- [-] Development phase only
- [o] Both development and production phases
- [-] Production phase only

---

### 9) Is Package Securing a feature or a guideline?
- [-] Guideline
- [-] None
- [o] Feature

---

### 10) The version control system is just recommended and not mandatory, because Orchestrator offers version control of the XAML files.
- [-] True
- [o] False

---

### 11) What are the basic security measures, already implemented, concerning the Robot-Orchestrator connection?
- [?] a) A Robot must be provisioned in Orchestrator before it can connect to it. b) A user must have local admin rights on the robot machine in order to connect to Orchestrator
- [-] a) Each provisioned robot has a unique key; b) The robot automatically connects to Orchestrator once the robot key is provided
- [?] a) Robots use machine name and Robot Key provided by Orchestrator to authenticate first; b) Any user logged into the robot machine can connect / disconnect it from Orchestrator.

---

### 12) Packages uploaded into Orchestrator (either manually or published from Studio) are automatically uploaded by Orchestrator to all robots that can execute these packages.
- [o] False
- [-] True

---

### 13) The Account Lockout security feature provided by the Orchestrator platform ensures:
- [-] Protection against User impersonation.
- [o] Protection against Brute Force attacs.
- [-] Protection against phishing attacks.

---

### 14) The Multitenancy feature in Orchestrator offers the possibility to isolate between tenants the following entities:
- [-] Robots, Assets, Processes, and Queues only
- [o] All entities, including logs, users, audit trail, settings, in addition to robots, assets, queues, etc
- [-] Users, Roles and Schedules only

---

### 15) What are the main differences between guidelines and security features?
- [-] Security features are implemented by RPA developers, while guidelines are implemented by business analysts
- [o] Guidelines are recommended general best practices, while security features are already implemented in the product
