# ☁️ Azure Hybrid Identity – Entra Sync Lab
<img width="1600" height="900" alt="svg" src="https://github.com/user-attachments/assets/0c52932d-51b4-475a-b046-e9e7da50ea51" />


A comprehensive hands-on lab demonstrating the implementation, comparison, and troubleshooting of **Microsoft Entra Connect Sync** and **Microsoft Entra Cloud Sync Agent** in a hybrid identity environment.

---

## 🎯 Lab Objectives & Key Features

* **Hybrid Identity Setup:** Integrated On-Premises Active Directory (`khaled.local`) with Microsoft Entra ID Tenant (`5aled.xyz`).
* **Dual Sync Mechanisms:**
  * **Microsoft Entra Connect Sync (Classic):** Configured for complex hybrid requirements and high-availability staging mode.
  * **Microsoft Entra Cloud Sync Agent:** Implemented lightweight agent model with Group Managed Service Accounts (gMSA).
* **High Availability (HA):** Configured **Staging Mode** on Entra Connect Sync for active-passive failover operations.
* **Authentication & SSO:** Configured Password Hash Synchronization (PHS) and Seamless Single Sign-On.
* **Troubleshooting:** Successfully diagnosed and resolved **AADSTS70027** client certificate expiration issues.

---

## ⚙️ Environment Configuration

| Component | Detail / Domain |
| :--- | :--- |
| **On-Prem Domain** | `khaled.local` |
| **Azure Tenant** | `5aled.xyz` |
| **Primary Sync Engine** | Microsoft Entra Connect Sync |
| **Secondary Sync Engine**| Microsoft Entra Cloud Sync Agent |
| **High Availability** | Staging Mode Server Active |

---

## 🔧 Deployment Steps

1. **Active Directory Preparation:** Set up Domain Controller (`khaled.local`), OUs, and test user accounts.
2. **Entra Connect Installation:** Deployed Azure AD Connect, mapped UPN suffixes to custom domain `5aled.xyz`.
3. **Staging Server Configuration:** Implemented a secondary staging server for High Availability testing.
4. **Cloud Sync Agent Setup:** Provisioned lightweight Cloud Sync agent using gMSA credentials for scoped identity sets.
5. **Validation & Verification:** Verified user sync, attribute flows, and seamless single sign-on behavior in Entra ID portal.

---

## 👤 Author
* **Khaled Ashraf**
* Aspiring Cloud & DevOps Engineer

---

## 📸 Lab Screenshots & Proof of Concept

![Screenshot 1](https://github.com/user-attachments/assets/9a6ff3e9-b26c-4540-abf7-4080a9aa4f87)

![Screenshot 2](https://github.com/user-attachments/assets/034dece8-2ef6-4006-a0d6-7f107a1f21e2)

<img width="1913" height="977" alt="Screenshot 2026-08-11 222545" src="https://github.com/user-attachments/assets/0a47cbfb-735e-4333-bde4-fed227ae8647" />


![Screenshot 3](https://github.com/user-attachments/assets/f8c8f919-1a8f-4215-9555-faf8103bdc36)

![Screenshot 4](https://github.com/user-attachments/assets/44a0bc64-30ad-4241-9226-fdcb420cb959)




