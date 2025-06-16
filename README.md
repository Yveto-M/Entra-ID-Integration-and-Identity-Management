# 🔐 Entra ID Integration and Identity Management
🧠 Overview: This project demonstrates how to integrate applications with Microsoft Entra ID by managing users and groups, registering applications, enforcing conditional access policies, enabling multi-factor authentication (MFA), and monitoring sign-in activity.


## 💼 Scenario

A company wants to integrate its web app with Entra ID for authentication, managing user and group roles, enforcing conditional access policies, and enabling MFA for added security.

---

## ✅ Steps Completed

### 1. Create Users and Groups in Entra ID

* Navigate to **Entra ID > Users > Create User**.
* Created multiple users with roles (e.g., Admin, Developer, Reader).
* Navigated to **Groups > Create Group** and added users to the group.

📸 *Entra ID User List*

<img width="694" alt="group creation" src="https://github.com/user-attachments/assets/91b6b638-daa2-45cb-b4c7-f10117f48ddc" />

📸 *Group with Members*
<img width="761" alt="group members" src="https://github.com/user-attachments/assets/58e99580-2804-4649-af35-ab439e9aa877" />

---

### 2. Register an Application in Entra ID

* Navigated to **App Registrations > New Registration**.
* Provided name, account types, and redirect URI.
* Configured **API Permissions** (e.g., `Microsoft Graph > User.Read`).
* Created a **Client Secret** under **Certificates & Secrets**.

📸 *App Registration Overview*
<img width="795" alt="registered web app" src="https://github.com/user-attachments/assets/a0219e5b-bf14-4369-ab54-f67a87567c25" />

📸 *API Permissions*
<img width="784" alt="user read perm" src="https://github.com/user-attachments/assets/1249d90f-2e0a-4261-8c2c-2b7fce41640e" />

📸 *Client Secret*
<img width="779" alt="cert secret" src="https://github.com/user-attachments/assets/a2eabb7f-ba5f-4831-8219-c998f4fda660" />

---

### 3. Assign Users and Groups to the Application

* Went to **Enterprise Applications** → selected the app.
* Added users/groups under **Users and Groups > Add User/Group**.

📸 *Enterprise App Users Assignment*

<img width="789" alt="enterprise app users" src="https://github.com/user-attachments/assets/db7da793-d919-4927-85cf-62d733fbd016" />


### 4. Configure Conditional Access

* Navigated to **Entra ID > Security > Conditional Access > New Policy**.
* Created a policy requiring MFA for all users.
* Applied conditions (e.g., location-based access).
* Enabled the policy and tested login flow.

📸 *Conditional Access Policy Overview*
<img width="780" alt="creating con access" src="https://github.com/user-attachments/assets/b74b3f45-01eb-4018-b52b-f18b9e9fabb3" />

---

### 5. Enable Multi-Factor Authentication (MFA)

* Went to **Entra ID > Users > Multi-Factor Authentication**.
* Enabled MFA for selected users.
* Tested sign-in process to ensure MFA prompts triggered.

📸 *MFA Configuration Panel*
<img width="781" alt="enabled mfa" src="https://github.com/user-attachments/assets/7562729a-851a-45f8-859c-dfc35f104186" />

---

### 6. Monitor Sign-In Activity

* Navigated to **Entra ID > Sign-ins**.
* Reviewed sign-in logs for success/failure insights.

📸 *Sign-In Logs Dashboard*
<img width="638" alt="moniter sign-in" src="https://github.com/user-attachments/assets/a57e4afe-c9ed-4289-9fd1-b863af23cb21" />

---

## 📘 Topics Covered

* Entra ID
* User and Group Management
* App Registration
* Conditional Access
* Multi-Factor Authentication (MFA)
