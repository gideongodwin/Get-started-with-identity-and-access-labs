### Task 2 - Review the Service settings for MFA

1. Open the Microsoft Entra admin center at https://entra.microsoft.com.
2. Log in using the credentials for your tenant.
3. Select Users and then select All users.
4. Select Per-user MFA item.

<img width="1247" height="405" alt="1" src="https://github.com/user-attachments/assets/37913e49-b2f9-4037-9b97-91f82eb7cf39" />

5. Select Service settings.

<img width="1123" height="492" alt="4" src="https://github.com/user-attachments/assets/beaa21d9-1525-4d62-9bd8-6abe31efdf53" />

6. Review the settings you can configure:

    | Setting                                               | What is it for                                                                                                                                                         |
    |-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | App passwords                                         | There are some legacy apps that won’t work with MFA, use this setting to allow a user to keep using them.                                                              |
    | Trusted IPs                                           | If your company has a specifc set of IP-address ranges that are always known safe, you can allow users to by-pass MFA the logging in.                                  |
    | Verification options                                  | Select the methods you are willing to allow users to use for their second factor of authentication.                                                                    |
    | Remember multifactor authentication on trusted device | If your users are using a device that you trust, like a company managed laptop; you can allow them to retain thier MFA approved status for a specified number of days. |

<img width="1174" height="597" alt="5" src="https://github.com/user-attachments/assets/98402920-e9ff-458d-9db9-2986054abb5a" />

7. Select the Discard button if you made any changes.
8. This is one method of configuring MFA for your users.
