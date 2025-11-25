### Task 1 - View the SSPR properties for a specific group

1. Open the Microsoft Entra admin center at https://entra.microsoft.com.
2. Log in using the credentials for your tenant.
3. From the menu on the left, open Protection submenu and then select Password reset.
4. Find the Self service password enabled bar.

    | Value    | What it means                                      | Description                                                                     |
    |----------|----------------------------------------------------|---------------------------------------------------------------------------------|
    | None     | No users can use the SSPR feature                  | How many times can you fail to login with a password before your account locks. |
    | Selected | Only members of the selected group(s) can use SSPR | How many second the account should lock when the threshold is reached.          |
    | All      | All users can use the SSPR feature                 |                                                                                 |

5. Set the value to Selected.
6. Select the text No groups selected.
7. Mark the Project23 group we created previously.
8. Use the Select button to complete your choice.
9. Save your configuration.
