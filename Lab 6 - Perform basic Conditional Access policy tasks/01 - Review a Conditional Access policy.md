## Task 1 - Review a Conditional Access policy

1. Sign in to the [Microsoft Entra Admin Center](https://entra.microsoft.com)

2. Select Conditional access >  `+ Create new policy`

    <img width="1191" height="384" alt="519122085-96358af1-d079-4b43-9f2b-27a6bf203df8" src="https://github.com/user-attachments/assets/933bab2a-55ab-4a34-bd8f-dd267ce8d8f4" />

3. In the Name box enter `Block Bhogeswar from using Sway`

4. In the Assignments section select `0 users and groups selected` text.

5. In the Include section, select the `Users and groups` 

6. Put a mark in the Users and groups box.

7. When the list of users and groups opens, select Bhogeswar Kalita from the list.

    <img width="1366" height="602" alt="3" src="https://github.com/user-attachments/assets/c25df966-ea67-473f-87a2-f6b53ea86def" />

8. In the Exclude Section, select the `Users and groups` 

9. Select the admin user you are using from the list to exclude this user

    <img width="1122" height="599" alt="4" src="https://github.com/user-attachments/assets/8cd1df81-f337-43e4-a991-a30f5b850840" />

10. Find the section Target resources section.

11. Select the No target resources selected text from this section.

    <img width="1103" height="598" alt="5" src="https://github.com/user-attachments/assets/4aebdcbc-2251-43d4-bea3-956a61fdd3c3" />

12. Select Resources (formerly cloud apps) from the dropdown.

13. On the Select specific resources item > click on `None`

14. Select the `Sway` resource

    <img width="1366" height="599" alt="6" src="https://github.com/user-attachments/assets/69e35c2f-7bf9-4398-b763-353f2eb9972f" />

15. Open and review the Network section, but we are not going to use that for this lab.

16. Open and review the Conditions section, but we are not using it for this lab.

17. Find the section titled Access controls.

18. Under the word Grant select the text `0 controls selected`

19. When the Grant dialog opens, select the `Block access` item.

    <img width="1366" height="596" alt="10" src="https://github.com/user-attachments/assets/6579a056-e4ba-46d1-8297-395737c1139d" />

20. At the bottom of the Conditional Access page, find the Enable policy item.

21. Set the value to `On`, then create

    <img width="1128" height="599" alt="7" src="https://github.com/user-attachments/assets/52b79ec1-b082-4c2b-91fe-34a79f987422" />
    
    <img width="1366" height="601" alt="8" src="https://github.com/user-attachments/assets/4a31d719-ce01-4787-a5a9-5c3410cc51b1" />





