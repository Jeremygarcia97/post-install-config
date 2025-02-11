#<p align="center">
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

- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/65287c18-b4c5-4f76-9406-94777e28823d)

<p>
Get Login into osTicket with the credentials that you made during the intall procces.
</p>
<br />

![image](https://github.com/user-attachments/assets/d5da0bc5-498e-4242-8366-58e2266dc533)
![image](https://github.com/user-attachments/assets/f7662db2-3196-4648-9b74-f50e4e859431)
![image](https://github.com/user-attachments/assets/d2df6ebf-f031-4f31-9132-18362a3d5151)



<p>
Make sure that you are in the admin panel, you can check the top right of the screen to see what panel you are in. If it says "Agent" then you are in admin panel.

Select the Agent tab then Roles then add New Role. Name the new role Surpreme Admin, select the permisson tab and check every box under the "Tickets,"Task","Knowledgebase" sections. Then Select Add Role. 
</p>
<br />

![image](https://github.com/user-attachments/assets/bbb49889-00d4-4b56-9723-226da49d33f9)
![image](https://github.com/user-attachments/assets/5e230c10-cdd0-4483-a800-6fedb031d8c0)


<p>
Configure Departmens- Select Agent > Deparments> Add New Departments, select "Top-Level Department and name "SysAdmins" and then hit "Create Dept".
  
</p>
<br /> osTicket---Post-Install-Configuration

![image](https://github.com/user-attachments/assets/8fdc5688-0ed8-4bf9-b553-b0e5aabad595)

<p>
Configure Teams- Select Agent tab > Teams> Add New Team> name the new team Online Banking and then select Create Team
</p>

![image](https://github.com/user-attachments/assets/238b45fb-916e-44a5-84c9-b3912ef58f1f)

<p>
Allow Anyone to Create Tickets- Select Settings > User Settings and make sure the following box is unchecked and then hit save changes.  
</p>

![image](https://github.com/user-attachments/assets/8614ac7d-be99-4cab-80b5-40cba8e4b077)
<p>
Configure Agents- Select the Agent tab then click Add New Agents.
</p>

![image](https://github.com/user-attachments/assets/ed62a7b2-69f7-4faf-a7b7-6e2da0bd2f28)
![image](https://github.com/user-attachments/assets/a9aea54d-d983-417a-a552-8f43bd48e439)
![image](https://github.com/user-attachments/assets/98179b95-3a8e-46c2-952f-272288682ca9)
![image](https://github.com/user-attachments/assets/6a40ed2d-04b4-4999-ae82-480427a15797)

First Agent- Name: Jane Doe, Email: Jane@loginpacific.com, Username: jane. Click Set password and unckeck the box where it says "send the agent a Password Reset Email", set the password to what you like and uncheck the bix that says "Require Password Change at Next Login" and then hit Set. 

Select the Access Tab, under Primary Departmen give jane SysAdmins and then Surpreme Admin, Click the tab thats says team and assigned jane to online banking and select create. 

![image](https://github.com/user-attachments/assets/7f4356bd-731f-4caa-962a-a453b28864af)
![image](https://github.com/user-attachments/assets/c0e13b11-6477-4e85-abab-54339c338ca6)

-Second Agent- Replace jane with john.
-follow the same steps with make janes account, The only thing that is change is when you choose his deparments you sill select "support" and "view only" and hit create. 


![image](https://github.com/user-attachments/assets/90885544-023e-4377-8d71-7a812f25cb16)
![image](https://github.com/user-attachments/assets/9c4414b9-f2de-4899-86f1-a2db96d43453)

Configure User- Select User tab to create a user, Email-karen@lognpacific.com, name- Karen and select add User.

![image](https://github.com/user-attachments/assets/d7ae20bc-70d8-4c05-b3e4-9bf86726c58d)
![image](https://github.com/user-attachments/assets/45d61242-d0eb-4cb0-8bb6-5f8fea1b1083)

<p>
Configure Service Level Agreements(SLA)- We will create three SLAs, Select Manage tab> SLA> Add New SLA Plan. Name: Sev-A. Grace Period:1,Schedule: 24/7. 
</p>

![image](https://github.com/user-attachments/assets/7f44343f-e3a7-45f5-b34f-f7faefb26522)
<p>
- Name: SEV-B
- Grace Period: 4
- Schedule dropdown menu: 24/7
- Select Add Plan.
</p>

![image](https://github.com/user-attachments/assets/0983f55f-8c7f-49a1-af0f-c259246c8a40)

<p>
- Name: SEV-C 
- Grace Period: 8
- Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S. Holidays
- Select Add Plan.
</p>

![image](https://github.com/user-attachments/assets/6504434d-70f8-458f-afc6-35eaea826f2d)

<p>
Configure Help topics- Create 5 hlep topics. Select Manage tab> Help Tpoics> Add New Help Topics. Business Critical Outage,
Personal Computer Issues,
Equipment Request,
Password Reset,
Other. Select Add topic for each topic.
</p>

<p> Now we have completed Configured osTicket.</p>

