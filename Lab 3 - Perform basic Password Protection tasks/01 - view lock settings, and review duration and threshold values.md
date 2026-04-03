## Task 1 - View lock settings, and review duration and threshold values

1. Sign in to the [Microsoft Entra Admin Center](https://entra.microsoft.com)

2. Select Authentication methods > Password protection

   <img width="1052" height="441" alt="518531244-cf600339-ca80-40ac-ad15-17042ec4e4a6" src="https://github.com/user-attachments/assets/5308bbb3-c874-4114-9a0a-99f7611c41b0" />

3. Set the Custom smart lockout with the following values

    | Field             | Value | Description                                                                     |
    |-------------------|-------|---------------------------------------------------------------------------------|
    | Lockout threshold | 5     | How many times can you fail to login with a password before your account locks. |
    | Lockout duration  | 30    | How many second the account should lock when the threshold is reached.          |

4. Set Enforce custom list to Yes.

5. Enter the following values:
    - Contoso
    - London
    - Widget

6. Set the value for Mode to `Enforced`

7. Select the Save item at the top of the screen.

   <img width="954" height="471" alt="518530904-e3e434dc-c656-4cd0-a2a5-6578c38b8c08" src="https://github.com/user-attachments/assets/ad6ca36b-6975-4d14-a309-0d59b196505f" />


