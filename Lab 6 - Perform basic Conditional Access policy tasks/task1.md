### Task 1 - Review a Conditional Access policy

Open the Microsoft Entra admin center at https://entra.microsoft.com.
Log in using the credentials for your tenant.
From the menu on the left, select Protection submenu and then select Conditional access.
Review the information provided on the Conditional Access Overview page.

Note - You can see how many policies you have enabled, and how many users who have logged in recently that are not covered by a policy; along with other details.

Select the + Create new policy from the top menu.
In the Name box enter Block Bhogeswar from using Sway.
In the Assignments section select 0 users and groups selected text.

In the Include section mark the Select users and groups item.
Put a mark in the Users and groups box.
When the list of users and groups opens, select Bhogeswar Kalita from the list.
Use the Select button to add the user.
Select the word Exclude to switch tabs.
Put a mark in the Users and groups box.
When the list of users ang groups opens, select the admin user you are using from the list.
Use the Select button to exclude this user.
Lab tip - We have added a user for this policy and we have added an exclude for our admin, to make sure they are not accidentally locked out by a policy change.

Find the section Target resources section.
Select the No target resources selected text from this section.

Make sure Resources (formerly cloud apps) is chosen in the dropdown.
Put a mark in the Select resources item.
In the section titled Select chose the word None.
When the resource selection dialog opens, enter Sway into the search bar.
Put a check in the box next to Sway then use the Select button to approve the choice.
Lab tip - We have chosen the app Sway to be the resource this policy works on. You could choose multiple apps, or you could even choose to exclude apps.

Open and review the Network section, but we are not going to use that for this lab.
Open and review the Conditions section, but we are not using it for this lab.

Lab tip - Network and Conditions are powerful options in the Conditional Access policy, but they are not required for this simple policy to block access to an app. You would use them if you wanted to do things like restrict access for user working from a specific location, or block access if a user has show risky behavior. There are many granular options that you can choose from, or even combine together.

Find the section titled Access controls.
Under the word Grant select the text 0 controls selected.
When the Grant dialog opens, select the Block access item.
Use the Select button to accept the change.

Lab tip - You have not set the values needed to create a simple block access policy to the Sway app for Bhogeswar. In the Access controls section, we could have allowed access with specific conditions like MFA or a domain joined device.

At the bottom of the Conditional Access interface, find the Enable policy item.
Set the value to On.
Select the Create button.

Lab tip - You have three options to pick from, and you can change value at any time, without having to change the policy.

On = enables the policy to run
Off = turn the policy off in case you need to modify it.
Report-only = use this option to review the outcome of the policy before you fully turn it on.
