<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<img width="80%" height="80%" alt="1" src="https://github.com/user-attachments/assets/f9b2c2be-a7d5-49ad-8319-e050ea706cb9" />

- In this lab, we will be creating tickets as end users.
- Observing all the ticket properties and responding to them as help desk professionals.
- First step is to log in.
</p>
<br />

<img width="80%" height="80%" alt="2" src="https://github.com/user-attachments/assets/6c084779-fa9c-4a8b-abe8-0d6a014dd6b3" />

- In the Admin Panel click "Agents" > "Departments".
- Check "Maintenance" then delete it.
</p>
<br />

<img width="80%" height="80%" alt="3" src="https://github.com/user-attachments/assets/d08363c6-f106-4805-9621-cf63508ddd0b" />

- Open the end users osTicket URL: http://localhost/osTicket/
- Click "Open New Ticket".
</p>
<br />

<img width="80%" height="80%" alt="4" src="https://github.com/user-attachments/assets/f4d60688-a2c8-4f44-8a61-6842709409f7" />

- Fill out the ticket with an email and name.
- Explain the nature of the issue.
- Click "Create Ticket".
</p>
<br />

<img width="80%" height="80%" alt="5" src="https://github.com/user-attachments/assets/fdb06c54-fa56-4b2b-b3f6-cf07244c6883" />

- You will see this screen when ticket is correctly created.
</p>
<br />

<img width="80%" height="80%" alt="6" src="https://github.com/user-attachments/assets/00fd76b2-1b90-419b-a08b-1002f43cbbe6" />

- Log into the Admin/Analyst page as John
</p>
<br />

<img width="80%" height="80%" alt="7" src="https://github.com/user-attachments/assets/499e180a-0f18-41a9-8cc0-fa3f490cee44" />

- Under tickets you can see the ticket that was just created.
- Click on it.
</p>
<br />

<img width="80%" height="80%" alt="8" src="https://github.com/user-attachments/assets/996d9960-36d1-40be-9d69-bc9e26533488" />

- Once you open the ticket you will notice John only has read access and can only leave notes.
- Leave a note then log out of Johns account.
</p>
<br />

<img width="80%" height="80%" alt="9" src="https://github.com/user-attachments/assets/d05e664d-3352-44be-b84f-107e591ed227" />

- Log into the Admin User account so we can change Johns access rights.
</p>
<br />

<img width="80%" height="80%" alt="10" src="https://github.com/user-attachments/assets/0d4c6b1c-abaf-4ea0-8b13-392c56a6d3b1" />

- Under "Admin Panel" click "Agents"
- Select John
</p>
<br />

<img width="80%" height="80%" alt="11" src="https://github.com/user-attachments/assets/47c1c5cc-9cb3-4360-a2d1-24927886f567" />

- Change his access rights from "Read Only" to "Access All".
- Click "Save Changes".
</p>
<br />

<img width="80%" height="80%" alt="12" src="https://github.com/user-attachments/assets/cb1c0164-0579-415d-81b9-794bd6ea019b" />

- Log back into Johns account and open the ticket again.
- Now John can make changes to the ticket.
</p>
<br />

<img width="80%" height="80%" alt="13" src="https://github.com/user-attachments/assets/69893abb-c0d7-4007-98ce-ac1192ef6748" />

- Click priority level and change it to "Emergency".
</p>
<br />

<img width="80%" height="80%" alt="14" src="https://github.com/user-attachments/assets/7d164bc7-4d81-4c98-9708-4ed12f535f23" />

- Click SLA Plan and select "SEV-A".
</p>
<br />

<img width="80%" height="80%" alt="15" src="https://github.com/user-attachments/assets/e8dcf940-6941-453c-85c0-428da21e511a" />

- Click "Help Topic" and choose "Bussiness Critical Outage".
</p>
<br />

<img width="80%" height="80%" alt="16" src="https://github.com/user-attachments/assets/ae4cb017-eed9-4b4b-be35-8b9421814c09" />

- All the changes you make should appear in the "Ticket Thread".
- Type in the thread that you will be escalating the ticket to the Sysadmin.
</p>
<br />

<img width="80%" height="80%" alt="17" src="https://github.com/user-attachments/assets/90344c62-0680-484a-b137-a3a68430cb39" />

- Under "Assigned To" change the name to "Jane Doe".
</p>
<br />

<img width="80%" height="80%" alt="18" src="https://github.com/user-attachments/assets/17eff8cc-dbc6-432a-a90e-0aed4f443366" />

- Log out of John's account.
- Log into Jane's account.
</p>
<br />

<img width="80%" height="80%" alt="19" src="https://github.com/user-attachments/assets/ccc99ef6-7323-4892-ab09-533186f45ee6" />

- Now you should see the ticket that has been escalated.
- Click on it.
</p>
<br />

<img width="80%" height="80%" alt="20" src="https://github.com/user-attachments/assets/1a1aa242-1676-46af-b013-b4b11276d531" />

- Type out a possible solution for the issue.
- Post reply
</p>
<br />

<img width="80%" height="80%" alt="21" src="https://github.com/user-attachments/assets/aa1ec499-bb99-4ae3-af88-1a0b3ba02610" />

- When the issue is confirmed to be dealt with post a reply confirming the tickets completion.
- Let them know you will be closing the ticket.
</p>
<br />

<img width="80%" height="80%" alt="22" src="https://github.com/user-attachments/assets/36aaf3f7-f6df-40a3-89ba-d4815c86818f" />

- Under "Status" click "Open" then "Resolved" to close the ticket.
</p>
<br />

<img width="80%" height="80%" alt="23" src="https://github.com/user-attachments/assets/8068e123-8545-48d0-beb2-7ce165b05c03" />

- To create another ticket go back to the end users osTicket portal.
- Click create new ticket.
</p>
<br />

<img width="80%" height="80%" alt="24" src="https://github.com/user-attachments/assets/13b4389f-4e53-429a-89ec-0254d5861e95" />

- Create the following ticket by filling in the required info.
- Click "Create Ticket"
</p>
<br />

<img width="80%" height="80%" alt="25" src="https://github.com/user-attachments/assets/2f4cc788-793b-4f0b-b5c7-3d7e16c6f048" />

- Log into John's account.
</p>
<br />

<img width="80%" height="80%" alt="26" src="https://github.com/user-attachments/assets/4c86b93a-364e-41fc-bc73-9a5007405444" />

- Click on the ticket that was just created.
</p>
<br />

<img width="80%" height="80%" alt="27" src="https://github.com/user-attachments/assets/b3c92e6d-cb32-4e7c-9590-609dad9e7096" />


- Lets say you called the end user to get more info.
- Post that in the thread and let them know you are going to investigate.
</p>
<br />

<img width="80%" height="80%" alt="28" src="https://github.com/user-attachments/assets/65f90362-f2fa-49c3-81fb-3450bb6a8236" />

- Set priority to "High".
</p>
<br />

<img width="80%" height="80%" alt="29" src="https://github.com/user-attachments/assets/e83274da-e4cc-4b19-aa76-549db919dfab" />

- Set the SLA Plan to "SEV-B".
- give a reason why.
</p>
<br />

<img width="80%" height="80%" alt="30" src="https://github.com/user-attachments/assets/06462fd0-4de0-4c55-9949-69c44423a760" />

- Type out your analysis of the situation and any troubleshooting you plan on doing.
</p>
<br />

<img width="80%" height="80%" alt="32" src="https://github.com/user-attachments/assets/db644e4f-24a2-49b7-939d-7bc6e73e4fcf" />

- Close the ticket.
</p>
<br />
