### Task 2 - Create a Security group

1. Open the Microsoft Entra admin center at https://entra.microsoft.com.
2. Log in using the credentials for your tenant.
3. From the menu on the left, select Groups and then All groups.
4. Select New group option.
5. Enter the requested information:

    | Field             | Value                                                       |
    |-------------------|-------------------------------------------------------------|
    | Group type        | Security                                                    |
    | Group name        | Guest Users                                                 |
    | Group description | This group has all the Guest users currently in the tenant. |
    | Membership type   | Dynamic User                                                |

6. Under the Dynamic user members heading, select Add dynamic query.

<img width="1188" height="599" alt="5" src="https://github.com/user-attachments/assets/514d254d-b724-46d6-82f8-ecd4c649a3b7" />

7. Create a dynamic query with the following values:

    | Field           | Value        |
    |-----------------|--------------|
    | Property        | userType     |
    | Operator        | Equals       |
    | Value           | Guest        |
    | Membership type | Dynamic User |

   <img width="1373" height="598" alt="6" src="https://github.com/user-attachments/assets/7d86aa62-7432-47c5-adb2-cb2846e49e4a" />
   
8. Select the Save item from the top of the page.
9. Select the Create button.
    
<img width="1187" height="597" alt="7" src="https://github.com/user-attachments/assets/f17cf546-8487-443f-9dd1-c6e23efb3368" />

10. From the All Groups select the Refresh item.
11. Select the Guest Users group we just created.

<img width="1581" height="869" alt="8" src="https://github.com/user-attachments/assets/a954d49c-980d-4164-8fec-d6efe40a8550" />

12. Select Members.

<img width="1696" height="805" alt="9" src="https://github.com/user-attachments/assets/9927eaa6-d936-4116-bdd4-0b1daa02f1c8" />

    
