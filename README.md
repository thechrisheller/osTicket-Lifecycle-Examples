<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket-Lifecycle-Example</h1>
This tutorial outlines the lifecycle of the open-source help desk ticketing system osTicket.<br />

<h2>Prerequisites</h2>

- [osTicket: Installation](https://github.com/thechrisheller/osTicket-Installation)
- [osTicket: Post-Installation Configuration](https://github.com/thechrisheller/osTicket-Post-Installation/tree/main)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)</b>

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>osTicket Lifecycle Example Lab</h2>

<h2>Intake</h2>

- We will begin by going to the end-user page to submit a ticket
- We go there and select "Open a New Ticket"

![osticket-lifecycle-Part 1a](https://github.com/user-attachments/assets/4085eb33-30f2-4003-9c60-7c3e0a4964b1)

- From there, we can put in the user credentials that we created from the previous lab, and I am going to use Karen for this part of the lab
- We will put in their concern/issue that Karen, as the end-user, is having with her Online Banking
- Then select create ticket

![osticket-lifecycle-Part 1b](https://github.com/user-attachments/assets/d866720c-0faf-4b17-84b3-5916ac8dd4cf)

<h2>Assignment and Communication | Working the Issue | Resolution</h2>

<h2>Example 1</h2>

- Get logged in as your admin user. For me it's Jane Admin

![osticket-lifecycle-Part 2a](https://github.com/user-attachments/assets/570e2b9a-d472-42c1-be20-561fd6c2648f)

- Click into your ticket and this is what it should look like as the admin user

![osticket-lifecycle-Part 2b-1](https://github.com/user-attachments/assets/ee0ead1d-e0c8-4c36-bf21-57fd6879f5d4)
![osticket-lifecycle-Part 2b-2](https://github.com/user-attachments/assets/a466dc27-0982-4ed4-8475-e2796039c70e)

- Notice most of the wording on the left side of the first photo above is in blue, because, as the admin user, we can edit and assign Ticket Status, Priority, Department, the SLA Plan, and the time by which it is due.
- We can also assign tickets to different users.
- Realistically, as the admin user and as part of the online banking team, Jane would be in charge of working this ticket to completion.
- Let's go ahead and do so
- The story behind this ticket is Karen can't access her online bank, as well as most/all of her coworkers as well.
- Over the weekend, there was an automatic update that affected the online banking, so as the admin user, we are going to restore the update to the previous version.
- Notice that the light yellow is an internal note, and the peach color is a note to the customer
  
![osticket-lifecycle-Part 2c](https://github.com/user-attachments/assets/717c82c4-97fa-4d4e-b468-cd0cfd304178)

- We can now close out the ticket

![osticket-lifecycle-Part 2d](https://github.com/user-attachments/assets/9567d171-f92f-4f77-af85-51aafd798322)

- We have completed our first ticket. In real life, there will be other steps we would have to do to complete the ticket, but this is all about using osTicket 

<h2>Example 2</h2>

- Let's do one more
- Ken sent in a ticket stating that his computer mouse isn't working, and wants another mouse sent and assigned to him.
- We are going to let John Support work on this ticket by assigning this ticket to him.

![osticket-lifecycle-Part 3a](https://github.com/user-attachments/assets/c2af6677-3fce-4e79-b58c-4ca0a7aa2325)

- Assigned To: John 

![osticket-lifecycle-Part 3b](https://github.com/user-attachments/assets/2c8f9ef6-d0a5-47b3-aef5-7130ee00f93c)

- As the admin user, I gave John the support role and assigned him expanded access so that he can work on the ticket.
- Go ahead and log into John and get back into the ticket

![osticket-lifecycle-Part 3c](https://github.com/user-attachments/assets/d938c974-d7a1-4ce4-ae90-f7a115e33daf)

- We have completed the ticket by delivering a new Mouse to Ken 

<h2>Conclusion</h2>
This concludes our project. We have successfully navigated through the entire osTicket lab, which includes installation, post-install, and the life cycle of a Help Desk ticket within osTicket. Since this concludes our lab, make sure to stop the VM so you don't waste your money while not using it, or if you are completely done messing with the lab, you are welcome to delete the entire resource group so you are not being charged for storage. Thank you for your time, and I look forward to completing more labs in the future with you all!
