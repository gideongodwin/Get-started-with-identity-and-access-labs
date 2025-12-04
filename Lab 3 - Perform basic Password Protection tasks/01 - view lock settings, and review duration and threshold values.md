### Task 1 - View lock settings, and review duration and threshold values

1. Open the Microsoft Entra admin center at https://entra.microsoft.com
2. Log in using the credentials for your tenant.
3. From the menu on the left, select Authentication methods.
 
4. Select Password protection from the list.

<img width="1155" height="598" alt="1" src="https://github.com/user-attachments/assets/cf600339-ca80-40ac-ad15-17042ec4e4a6" />

5. Set the Custom smart lockout with the following values

    | Field             | Value | Description                                                                     |
    |-------------------|-------|---------------------------------------------------------------------------------|
    | Lockout threshold | 5     | How many times can you fail to login with a password before your account locks. |
    | Lockout duration  | 30    | How many second the account should lock when the threshold is reached.          |

6. Set Enforce custom list to Yes.
7. Enter the following values:
    - Contoso
    - London
    - Widget

8. Set the value for Mode to Enforced.
9. Select the Save item at the top of the screen.
<img width="1191" height="599" alt="2" src="https://github.com/user-attachments/assets/e3e434dc-c656-4cd0-a2a5-6578c38b8c08" />



