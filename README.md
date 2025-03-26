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
- Fill out the empty fields for each agent

  - Agent 1
    - Name: Jane Doe
    - Email Address: Jane@lognpacific.com
    - Username: jane
    - Password: Password1
    - Department: SysAdmins
    - Role: Supreme Admin
    - Team: Online Banking

- Agent 2
    - Name: John Doe
    - Email Address: John@lognpacific.com
    - Username: john
    - Password: Password1
    - Department: Support
    - Role: View only
    - Team: Unassigned


<p>
  
![image](https://github.com/user-attachments/assets/2062343e-c2ac-4541-851c-09318d088de6)

- Next, go to the "Access" tab, assign department and role

![image](https://github.com/user-attachments/assets/9471b9d5-cff8-411e-a93a-e11ca98acc6d)

- Lastly, go to the "Teams" tab, assign team, then click "Create" to finish

![image](https://github.com/user-attachments/assets/d62e77dc-f36b-41d5-a487-8d9dc6fe763e)


</p>
<br />

<h3>Step:6 Configure Users </h3>
<p>  

- Go to the "Agent Panel", navigate to Users -> Add User
- Fill out the fields with the new user's information
- click "Add User" to finish
 
<p>
  
![image](https://github.com/user-attachments/assets/fa810bb8-3def-41c0-ab40-b4fa28d1dccb)

<p>

</p>
<br />

<h3>Step:7 Configure SLA </h3>
<p>  
  
-  Go to the "Admin Panel", navigate to "Manage" -> SLA -> Add New SLA Plan
-  We are going to create 3 SLA's 
-  Fill out the necessary fields for each SLA and click "Add Plan" to complete

<p>  

- SLA 1
  - Name: Sev-A
  - Grace Period: 1 (hr)
  - Schedule: 24/7

- SLA 2
  - Name: Sev-B
  - Grace Period: 4 (hrs)
  - Schedule: 24/7

- SLA 3
  - Name: Sev-C
  - Grace Period: 8 (hrs)
  - Schedule: Monday-Friday, 8am - 5pm

![image](https://github.com/user-attachments/assets/4cee36fb-2f7f-46fb-ba78-c5d9bf1eae31)

- Example of Sev-A

</p>
<br />

<h3>Step:7 Configure Help Topics </h3>

- In the "Admin Panel", go to Manage -> Help Topics -> Add New Help Topic
- Fill out the Topic and Parent Topic field
- Click "Add Topic" to complete
- We are going to create 5 Help Topics:
<p>  
  
![image](https://github.com/user-attachments/assets/99bfca06-ddc6-4660-8de6-a55ea82279a7)  


  
- Help Topic 1: Business Critical Outage
  - Parent Topic: Report a Problem
- Help Topic 2: Personal Computer Issues
  - Parent Topic: Report a Problem
- Help Topic 3: Equipment Request
  - Parent Topic: General Inquiry
- Help Topic 4: Password Reset
  - Parent Topic: Report a Problem
- Help Topic 5: Other
  - Parent Topic: General Inquiry

<p>  
  
![image](https://github.com/user-attachments/assets/20805373-ebf4-4338-9d67-645e9492feb1)


  
</p>
<p>

