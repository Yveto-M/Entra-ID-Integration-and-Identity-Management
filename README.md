# 🔐 Entra ID Integration and Identity Management
🧠 Overview: This project demonstrates how to integrate applications with Microsoft Entra ID by managing users and groups, registering applications, enforcing conditional access policies, enabling multi-factor authentication (MFA), and monitoring sign-in activity.


## 💼 Scenario

A company wants to integrate their web app with Entra ID for authentication, manage user and group roles, enforce conditional access policies, and enable MFA for added security.

---

## ✅ Steps Completed

### 1. Create Users and Groups in Entra ID

* Navigate to **Entra ID > Users > Create User**.
* Created multiple users with roles (e.g., Admin, Developer, Reader).
* Navigated to **Groups > Create Group** and added users to the group.

📸 *Screenshot: Entra ID User List*
📸 *Screenshot: Group with Members*

---

### 2. Register an Application in Entra ID

* Navigated to **App Registrations > New Registration**.
* Provided name, account types, and redirect URI.
* Configured **API Permissions** (e.g., `Microsoft Graph > User.Read`).
* Created a **Client Secret** under **Certificates & Secrets**.

📸 *Screenshot: App Registration Overview*
📸 *Screenshot: API Permissions*
📸 *Screenshot: Client Secret*

---

### 3. Assign Users and Groups to the Application

* Went to **Enterprise Applications** → selected the app.
* Added users/groups under **Users and Groups > Add User/Group**.

📸 *Screenshot: Enterprise App Users Assignment*

---

### 4. Configure Conditional Access

* Navigated to **Entra ID > Security > Conditional Access > New Policy**.
* Created a policy requiring MFA for all users.
* Applied conditions (e.g., location-based access).
* Enabled the policy and tested login flow.

📸 *Screenshot: Conditional Access Policy Overview*

---

### 5. Enable Multi-Factor Authentication (MFA)

* Went to **Entra ID > Users > Multi-Factor Authentication**.
* Enabled MFA for selected users.
* Tested sign-in process to ensure MFA prompts triggered.

📸 *Screenshot: MFA Configuration Panel*

---

### 6. Monitor Sign-In Activity

* Navigated to **Entra ID > Sign-ins**.
* Reviewed sign-in logs for success/failure insights.

📸 *Screenshot: Sign-In Logs Dashboard*

---

## 📘 Topics Covered

* Entra ID
* User and Group Management
* App Registration
* Conditional Access
* Multi-Factor Authentication (MFA)
