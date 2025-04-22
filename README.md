<p align="center">
  <img src="https://github.com/user-attachments/assets/c5e63582-2943-460b-90dd-0e5a9f658655"/>
</p>

<h1>Active Directory: Practical Scenario Simulation</h1>
 This project will simulate various scenarios to enhance understanding of user provisioning, administration, and problem-solving within Active Directory.
 <br />

<h2>Key Objectives</h2>

__Scenario Simulation__
- <b>Engange in practical simulations of diverse scenarios, such as password resets, group membership changes, and account deactivations. </b>

__Troubleshooting Scenarios__
- <b>Develop troubleshooting skills by simulating scenarios where users encounter access issues, and learn to identify and resolve these challenges effectively.</b>

 <h2>Environment and Technologies Used</h2>
 
- <b>Microsoft Azure (Virtual Machines)</b> 
- <b>Remote Desktop</b>
- <b>Active Directory Domain Services</b>

<h2>Operating Systems Used</h2>

- <b>Windows 10</b> 
- <b>Windows Server 2022</b>

<h1>Scenarios</h1>

<h3>① User Account Creation</h3>

__Background:__

A new software developer, John Smith, has been hired to join the IT department at your company. As part of the onboarding process, the IT help desk needs to create a new user account for John in Active Directory.

First create a new user account named "John Smith" with the username "john_smith" and a temporary password.

![john smith](https://github.com/user-attachments/assets/5209a51f-d29a-4da3-b846-a692489a8731)
NOTE: Set the account to require a password change at the next login.

Assign John to the "Developers" security group in Active Directory.

![select groups](https://github.com/user-attachments/assets/124741f3-74b3-463f-a8f1-da5d360c1c63)

Then ensure that John's account is located in the appropriate Organizational Unit (OU) for IT staff.

![ou departments](https://github.com/user-attachments/assets/d28b9089-6dba-49bc-8d47-edbb254ec761)

- <b>Communicate the login credentials and temporary password to John through a secure channel.</b> 
- <b>Document the date and time of account creation for auditing purposes.</b>

__Considerations:__

- <b>The temporary password should meet the company's password policy requirements.</b> 
- <b>Ensure that John has the necessary permissions and group memberships to access the resources required for his role.</b>

<h3>② Password Reset</h3>

__Background:__

Sarah Thompson, a marketing executive, contacts the IT help desk reporting that she has forgotten her password and is unable to access her computer and email. The help desk needs to assist Sarah in resetting her password in Active Directory.

Locate Sarah's user account and initiate a password reset.

![sarah pw reset](https://github.com/user-attachments/assets/1845d7cf-1423-402b-83a9-43be074b4402)

Set a temporary password for Sarah that complies with the company's password policy.

![sarah new pw](https://github.com/user-attachments/assets/2aa927c9-14b2-44af-ab7a-e1f5fba8a91e)
NOTE: Make sure to click the highlighted boxes to ensure the user’s account is unlocked and enable them to set their own password.

- <b>Communicate the temporary password to Sarah through a secure channel and instruct her to change it immediately upon login.</b> 
- <b>Provide guidance on how to change the password using the company's self-service password reset tool if available.</b>
- <b>Document the date and time of account creation for auditing purposes.</b>

__Considerations:__

- <b>Ensure that the chosen temporary password is strong and complies with the company's password policy.</b> 
- <b>Remind Sarah to update the password on any additional devices or applications where the old password was saved.</b>

<h3>③ Group Membership Update</h3>

__Background:__

Emma Rodriguez, a systems analyst, has recently been promoted to a managerial role within the IT department. As part of her new responsibilities, Emma now requires access to specific network resources and project folders. The IT help desk needs to update Emma's group memberships in Active Directory accordingly.

Locate Emma's user account and review her current group memberships.

![emma r](https://github.com/user-attachments/assets/9286a76f-384f-424f-9e6d-b7fd9a7cf919)

Remove Emma from the "Systems Analysts" group and add her to the "IT Managers" group.

![emma properties](https://github.com/user-attachments/assets/3e81cff2-bd3c-4f9a-a6f6-67b936aedf25)

Confirm that Emma now has the necessary access rights to project folders and relevant network resources.

![it managers](https://github.com/user-attachments/assets/abd89508-14a9-485e-999c-36fcf9b0605d)

- <b>Communicate the group membership update to Emma, along with any additional instructions or changes in access.</b> 
- <b>Document the whole process</b>

__Considerations:__

- <b>Ensure that Emma's new group memberships align with her managerial responsibilities.</b> 
- <b>Communicate the changes to other relevant parties, such as the IT security team, to maintain awareness.</b>
- <b>Verify that Emma's access permissions are correctly configured after the group membership update.</b>

<h3>④ Account Deactivation</h3>

__Background:__

Mark Johnson, a network administrator, has recently resigned from the company. The IT help desk needs to deactivate Mark's user account in Active Directory to prevent unauthorized access and ensure the security of company resources.

Locate Mark's user account and initiate the account deactivation process.

![mark j](https://github.com/user-attachments/assets/8127c204-e022-4f93-b507-956dbb296f95)

Disable Mark's account to prevent further logins while retaining the account details for reference.

![mark j disable](https://github.com/user-attachments/assets/826cf918-2a58-4924-ba6c-d40d1f3c898b)

Remove Mark from all security groups to revoke his access to network resources.

![mar j employee](https://github.com/user-attachments/assets/fdf6e5a2-cad8-40a9-9f88-5b46c99bb8e7)

Confirm with other relevant departments (e.g., HR) that Mark's departure aligns with company policies and document the whole process.

__Considerations:__

- <b>Ensure a smooth transition of Mark's responsibilities to other team members.</b> 
- <b>Communicate the account deactivation to other departments, such as HR and security, for coordinated efforts.</b>
- <b>Retain Mark's user account details for historical records and potential future reference.</b>
- <b>Conduct a review of Mark's access rights to identify and update any shared resources associated with his account.</b>

<h3>⑤ Organizational Unit (OU) Management</h3>

__Background:__

The Sales department has recently undergone a reorganization, resulting in the creation of a new team focused on international sales. The IT help desk needs to reflect this change in the Active Directory structure by creating a new Organizational Unit (OU) for the International Sales team and moving relevant user accounts into the new OU.

Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.

![ou internaltional sales](https://github.com/user-attachments/assets/95747880-eb8e-4c77-967f-d38078ff4eaa)

Move the user accounts of team members, such as Alex Turner and Maria Sanchez, to the newly created OU.

![alex t maria s](https://github.com/user-attachments/assets/5ee36d64-0784-45a6-812f-1c708266a87f)

Verify that the users now appear under the "International Sales" OU in Active Directory.

![ou alex maria](https://github.com/user-attachments/assets/131cd55d-f38a-4345-9e01-5635c596bbd1)

Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.

__Considerations:__

- <b>Ensure that the new OU structure aligns with the company's organizational hierarchy.</b> 
- <b>Confirm that the appropriate Group Policy settings apply to the users within the new OU.</b>
- <b>Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.</b>

<h2>Final Thoughts</h2>

In summary, Active Directory is crucial for managing user accounts and network resources. The scenarios provided cover common IT help desk tasks, such as creating user accounts, resetting passwords, updating group memberships, and handling account deactivation. These scenarios serve as practical exercises for training IT personnel and highlight the importance of Active Directory in maintaining a secure and organized digital environment.
