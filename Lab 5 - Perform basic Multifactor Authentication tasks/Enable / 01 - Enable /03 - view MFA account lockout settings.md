### Task 3 - View MFA account lockout settings

1. Open the Microsoft Entra admin center at https://entra.microsoft.com.
2. Search for Account Lockout on the search bar
3. Select Account lockout from the menu.

<img width="1099" height="455" alt="6" src="https://github.com/user-attachments/assets/bf3c442d-3115-451f-acfe-ac9502d5b21a" />

4. Set the following lockout values:

    | Field                                            | Value |
    |--------------------------------------------------|-------|
    | Number of MFA denials to trigger account lockout | 3     |
    | Minutes until account lockout counter is reset   | 180   |
    | Minutes until account is automatically unblocked | 15    |

5. Select the Save option at the top of your screen.

<img width="1366" height="467" alt="7" src="https://github.com/user-attachments/assets/c3484494-16b1-4866-93b8-076ce2912317" />

6. Review some of the other configuration options you have on MFA like:
  - Fraud alert
  - Block / unblock users 
  - Notifications                                                  
