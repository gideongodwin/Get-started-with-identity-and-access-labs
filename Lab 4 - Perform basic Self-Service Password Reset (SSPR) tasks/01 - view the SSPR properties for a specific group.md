## Task 1 - View the SSPR properties for a specific group

1. Sign in to the [Microsoft Entra Admin Center](https://entra.microsoft.com)

2. Select Password reset.

3. From the Properties page, under the option Self service password reset enabled, choose Selected.

    >  Only members of the selected group(s) can use SSPR 

4. If your group isn't visible, choose No groups selected.

    <img width="997" height="413" alt="518547233-49fb9fda-680f-495d-a936-4d0df7acb914" src="https://github.com/user-attachments/assets/0c8e91d0-9254-472d-924c-b7155021ba55" />
 
5. Select the `Project23` group.
 
6. Save your configuration.

## Subtask 1 - View SSPR authentication methods

1. Select Password reset > Authentication methods

2. Select 1 as the value for Number of methods required to reset.

    > This value represents how many different ways the user is required to sign-in to the password reset tool, before they are allowed to reset their password. Note that using a password is not an option

3. Mark the Security Questions.

    <img width="1003" height="326" alt="518567083-9ee87c23-066a-4d76-843d-dfc8fedef696" src="https://github.com/user-attachments/assets/b559c102-17b7-45a3-a8f9-b809ef9a9ae2" />

4. Select the no security questions configured.

    <img width="1001" height="445" alt="518567775-73aff1cf-109c-4b62-af39-638f90d0660e" src="https://github.com/user-attachments/assets/ddafa1ae-1030-437a-91f7-0e4fd8874f31" />

5. Selct the predefined to add Predefined Security Questions.

    <img width="845" height="561" alt="518568658-3345b7b4-f06a-4464-bba2-152a6b8b659f" src="https://github.com/user-attachments/assets/0ae152a4-b6cf-438d-80f1-e22628a96503" />

6. Save your configuration

    <img width="1003" height="468" alt="518569087-cc945ef0-86c3-4304-9559-7085f1d3d04b" src="https://github.com/user-attachments/assets/460c8da3-3d02-436f-af07-fe7c79606c9c" />

## Subtask 2 - View SSPR registration

1. Select Password reset > Registration

2. Make sure the Require users to register when signing in? value is set to `Yes`

3. Set the Number of days before users are asked to re-confirm… to `90 days`

4. Save your changes.

    <img width="1017" height="302" alt="518569842-2fc20af6-4e2f-46af-a5fc-df4f8c6a7501" src="https://github.com/user-attachments/assets/023daf1c-afb8-49bd-9a5b-fa4517da4d45" />


## Subtask 3 - View SSPR reset notifications

1. Select Password reset > Notifications

2. Leave the Notify users on password reset? at the default of `Yes`

3. Change the Notify all admins when other admins reset their password? value to `Yes`

4. Save your changes.

    <img width="751" height="296" alt="518570152-ae2a0a5f-2551-4e17-9204-94618a93102a" src="https://github.com/user-attachments/assets/e0a24759-fd78-4833-87b8-cca9e0ccff9a" />

