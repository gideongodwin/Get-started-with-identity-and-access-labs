<img width="1179" height="595" alt="6" src="https://github.com/user-attachments/assets/951bb768-8957-4890-8b61-9875943f04b2" />### Task 1 - View the SSPR properties for a specific group

1. Open the Microsoft Entra admin center at https://entra.microsoft.com.
2. Log in using the credentials for your tenant.
3. From the menu on the left, select Password reset.
4. Find the Self service password enabled bar.

    | Value    | What it means                                      | Description                                                                     |
    |----------|----------------------------------------------------|---------------------------------------------------------------------------------|
    | None     | No users can use the SSPR feature                  | How many times can you fail to login with a password before your account locks. |
    | Selected | Only members of the selected group(s) can use SSPR | How many second the account should lock when the threshold is reached.          |
    | All      | All users can use the SSPR feature                 |                                                                                 |

5. Set the value to Selected.
6. Select the text No groups selected.

<img width="499" height="295" alt="1" src="https://github.com/user-attachments/assets/49fb9fda-680f-495d-a936-4d0df7acb914" />

7. Mark the Project23 group.
8. Use the Select button to complete your choice.

<img width="1364" height="598" alt="2" src="https://github.com/user-attachments/assets/917a5c1d-03a5-4d7a-bec3-8eca69707d8f" />

9. Save your configuration.

<img width="852" height="462" alt="3" src="https://github.com/user-attachments/assets/12f656a0-007a-4d0b-ab6a-791d135afbe4" />


### Subtask 1 - View SSPR authentication methods

1. Select Authentication methods from the menu within Password reset.
2. Select 1 as the value for Number of methods required to reset.
Note - this value represents how many different ways the user is required to sign-in to the password reset tool, before they are allowed to reset their password. Note that using a password is not an option.

3. Mark the Security Questions.

<img width="1100" height="599" alt="4" src="https://github.com/user-attachments/assets/9ee87c23-066a-4d76-843d-dfc8fedef696" />

4. Select the no security questions configured.

<img width="1176" height="598" alt="5" src="https://github.com/user-attachments/assets/73aff1cf-109c-4b62-af39-638f90d0660e" />

5. Selct the predefined to add Predefined Security Questions.

<img width="1179" height="595" alt="6" src="https://github.com/user-attachments/assets/fffbe5bd-fc6b-43e1-9518-760660800e22" />

6. Select Ok

<img width="1176" height="598" alt="7" src="https://github.com/user-attachments/assets/3345b7b4-f06a-4464-bba2-152a6b8b659f" />

<img width="1106" height="598" alt="8" src="https://github.com/user-attachments/assets/9128b80a-7271-4909-9ad0-1168c301d915" />


7. Click Save

<img width="1187" height="600" alt="9" src="https://github.com/user-attachments/assets/cc945ef0-86c3-4304-9559-7085f1d3d04b" />


### Subtask 2 - View SSPR registration

1. Select Registration from the menu within Password reset.
2. Make sure the Require users to register when signing in? value is set to Yes.
3. Set the Number of days before users are asked to re-confirm… to 90 days.
4. Select Save to save your changes.

<img width="1101" height="504" alt="10" src="https://github.com/user-attachments/assets/2fc20af6-4e2f-46af-a5fc-df4f8c6a7501" />

### Subtask 3 - View SSPR reset notifications

1. Select Notifications from the menu withing Password reset.
2. Leave the Notify users on password reset? at the default of Yes.
3. Change the Notify all admins when other admins reset their password? value to Yes.
4. Use the Save option to save your changes.

<img width="1120" height="504" alt="11" src="https://github.com/user-attachments/assets/ae2a0a5f-2551-4e17-9204-94618a93102a" />


