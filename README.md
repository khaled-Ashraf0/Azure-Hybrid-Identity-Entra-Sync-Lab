```text
[ On-Premises Active Directory ]             [ Microsoft Entra ID Tenant ]
         (khaled.local)                               (5aled.xyz)
               |                                           ^
               +--> [ Entra Connect Sync (Classic) ] ------+ (Heavy Engine / Staging Mode)
               |                                           |
               +--> [ Entra Cloud Sync Agent ] ------------+ (Lightweight / gMSA)
```
<img width="1918" height="1030" alt="Screenshot 2026-08-10 200848" src="https://github.com/user-attachments/assets/9a6ff3e9-b26c-4540-abf7-4080a9aa4f87" />
<img width="1911" height="1018" alt="Screenshot 2026-08-10 212039" src="https://github.com/user-attachments/assets/034dece8-2ef6-4006-a0d6-7f107a1f21e2" />
<img width="1918" height="177" alt="Screenshot 2026-08-10 211908" src="https://github.com/user-attachments/assets/f8c8f919-1a8f-4215-9555-faf8103bdc36" />
<img width="857" height="602" alt="Screenshot 2026-08-10 212651" src="https://github.com/user-attachments/assets/44a0bc64-30ad-4241-9226-fdcb420cb959" />




