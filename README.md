<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3>Step:1 Configure roles (for grouping permissions)</h3>

<p>

  - Go to Admin Panel -> Agents -> Roles

- Click "Add New Role"
- Name the role as  ("Supreme Admin")
- Under "Permissions", enable all check boxes and click "Add Role"
- Your new role Supreme Admin will be under the "Roles" list
![image](https://github.com/user-attachments/assets/f4014593-5974-4fe7-8138-8f2c334bb3eb)
<p>
  
![image](https://github.com/user-attachments/assets/5fea56bc-ce74-47c0-8640-7d0105e31e80)


</p>
<p>
  
<h3>Step:2 Configure Departments </h3>
<p>  
  
- Next, go to the "Admin Panel" -> Agents -> Departments
  - Click "Add New Department" then fill out the following fields:
  - Name the department "SysAdmins"
  - Select in the Parent field "Top Level Department"   
  - Click "Create Dept"
 
![image](https://github.com/user-attachments/assets/7f1f339e-32c1-4ba8-9687-dec41693fe2e)

</p>
<br />

<h3>Step:3 Configure Teams </h3>
<p>  

- Next, go back to the "Admin Panel" -> Agents -> Teams
- Click "Add New Team"
- Name the team "Online Banking" and click "Create Team"

![image](https://github.com/user-attachments/assets/040b258d-5866-4ee4-9583-87b94d4fc48d)


<p>

</p>
<p>

</p>
<br />

<h3>Step:4 Allow anyone to create a ticket </h3>
<p>  

- Next, go back to the "Admin Panel" -> Settings -> Users
- Make sure the "Registration Required" text box is unchecked, under Authentication settings
- Click "Save Changes"

![image](https://github.com/user-attachments/assets/50c7b16b-fb18-496e-8010-8bd7cff26a4c)

<p>
  

</p>
<p>

</p>
<br />

<h3>Step:5 Configure Agents </h3>
<p>  

- Go back to the, "Admin Panel" -> Agents -> Add New Agent
- For this assignment you will creating two agents
  - Agent 1
    - Name: Jane Doe
    - Email Address: Jane@lognpacific.com
    - Username: jane
    - Password: Password1
    - Department: SysAdmins
    - Role: Supreme Admin
    - Team: Online Banking



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
