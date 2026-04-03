### Task 2 - Create a Security group

1. Sign in to the [Microsoft Entra Admin Center](https://entra.microsoft.com)

2. Select Groups > All groups > New Groups

3. Enter the requested information:

    | Field             | Value                                                       |
    |-------------------|-------------------------------------------------------------|
    | Group type        | Security                                                    |
    | Group name        | Guest Users                                                 |
    | Group description | This group has all the Guest users currently in the tenant. |
    | Membership type   | Dynamic User                                                |

4. Under the Dynamic user members heading, select Add dynamic query.

    <img width="798" height="489" alt="518303198-514d254d-b724-46d6-82f8-ecd4c649a3b7" src="https://github.com/user-attachments/assets/c71d91fd-e9b4-4efb-bef1-b3f8d04ed1cf" />


5. Create a dynamic query with the following values and Save.

    | Field           | Value        |
    |-----------------|--------------|
    | Property        | userType     |
    | Operator        | Equals       |
    | Value           | Guest        |
    | Membership type | Dynamic User |

    <img width="1360" height="391" alt="518304415-7d86aa62-7432-47c5-adb2-cb2846e49e4a" src="https://github.com/user-attachments/assets/16e8742e-829a-409b-8a59-54c1bc6b1605" />

6. Click on Create
    
7. From the All Groups select the Refresh item.

8. Select the Guest Users group we just created.

    <img width="1581" height="484" alt="520521360-3c098fa3-f6ab-47b1-9ebf-416774f9acd2" src="https://github.com/user-attachments/assets/52b8bbd6-2a5f-4f0f-9ab7-f36730a1d3f8" />

9. Select Members.

    <img width="1319" height="405" alt="518305538-9927eaa6-d936-4116-bdd4-0b1daa02f1c8" src="https://github.com/user-attachments/assets/38bca863-4018-4f23-8abd-38c09db5c456" />

    
