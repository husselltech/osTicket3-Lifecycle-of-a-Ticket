# osTicket3-Lifecycle-of-a-Ticket

## osTicket: Lifecycle of a Ticket

The final phase of this tutorial will show how a ticket is submitted from the perspective of the end user, and what happens to a ticket from the side of the IT Helpdesk. 

## Ticket Number 1

Go to localhost/osTicket in Microsoft Edge to get to the Support Ticket System homepage. Click Open a New Ticket.

![image](https://user-images.githubusercontent.com/114452968/231210206-600e4862-7c96-4e5a-9669-3c0b36b21cf5.png)

Enter one of the previously used email addresses and users. Leia Solo will our first user to fill out a ticket. Select a help topic; in this simulation we will be selecting Business Critical Outage. In the Issue Summary we will say that the company’s mobile and online (website) banking system is down. Our user will describe the situation saying that she is getting a 404 error and that no transactions can be completed. Click Create Ticket. Great! Mrs. Solo’s ticket has been submitted and the IT Helpdesk will act on it in due time.
 
![image](https://user-images.githubusercontent.com/114452968/231210293-33420b39-5294-4231-80bf-1b8e2b4a2003.png)

## Ticket Number 2

Let’s do another! Open a New Ticket. Enter a user with their information. This time Padme Skywalker is having a personal computer issue. Mrs. Skywalker says that the issue is Adobe Reader is not working for her and others in the Accounting Department, and that they noticed the issue only after that morning’s system software updates. Click Create Ticket. Great! Mrs. Skywalker’s ticket has been submitted and the IT Helpdesk will act on it in due time.
 
![image](https://user-images.githubusercontent.com/114452968/231210388-ace34d12-66f0-4049-90f2-c86131321b62.png)

##Ticket Number 3

Time for one more! Open a New Ticket. It looks like Mrs. Solo has another inquiry. This time she is making an equipment request. She wants to know when she will be eligible for an upgrade to her company laptop. Click Create Ticket. Great! Mrs. Solo’s second ticket has been submitted and the IT Helpdesk will act on it in due time.

![image](https://user-images.githubusercontent.com/114452968/231210618-d7b4d8f1-9fb1-4e5b-a1e7-93131826993c.png)
 
## IT Helpdesk Actions

Our tickets have been submitted so now it is time for the IT Helpdesk team to get to work. First, we are going to log into Supreme Administrator Han Solo’s account to have him assist with these tickets.
 
![image](https://user-images.githubusercontent.com/114452968/231210801-99fbd5d3-c27e-46d0-83d7-7e8925ca566a.png)

On Han’s screen he sees all the tickets that have been submitted. 
 
![image](https://user-images.githubusercontent.com/114452968/231210847-4edc35de-c8f6-4e09-ab79-00cf2aaaea9f.png)

We will begin with the laptop upgrade ticket. The Priority will be set to Low since the user is just asking a question. More critical issues will be given a higher priority. Since this issue is low-priority we will set the SLA to Severity 3. The Support department is the correct department to answer this, and we will assign this to Ben Kenobi because he works in Support. Since Ben can close this ticket on his own after he answers the employee’s question we are done with this ticket and will return to the open tickets.
 
![image](https://user-images.githubusercontent.com/114452968/231210883-581e05a8-43ad-4cce-941e-c9659ef58c9e.png)

The next ticket we will look at will be the mobile and online(website) banking system down ticket submitted by Leia Solo. This issue will get emergency priority since it affects critical business happening at the company. Since it is so critical, we are only allowing System Administrators to act on this ticket and will set the SLA to Severity 1. Navigate back to open tickets, the System Administrators will get to work.

![image](https://user-images.githubusercontent.com/114452968/231210975-dd702efb-3e1f-43f0-8382-fdc710f8f0ee.png)
 
Final ticket! Han can handle Mrs. Skywalker in the Accounting Department and their issue with Adobe reader. This is a high priority ticket because the accounting department needs this program in order to do their job. The SLA is Severity 2 because it is not an emergency, but it is also something cannot that be postponed. For now, Han will send a response that in the meantime he will install an older version of adobe while he investigates the issue.
 
![image](https://user-images.githubusercontent.com/114452968/231211068-9a57ff09-552d-479c-8bec-a2a793438b9b.png)

After some time passes Han lets the user know there are news reports online that the latest version of Adobe has been patched and is working.

![image](https://user-images.githubusercontent.com/114452968/231211143-943583e5-a095-4bea-97bd-dee1f0fa808f.png)
 
Finally, it is good practice to verify continuing function and satisfaction so Han will send a final message and close the ticket.

![image](https://user-images.githubusercontent.com/114452968/231211227-209b996c-4992-4852-b6be-79b90cc41761.png)
 
Let’s go and see our remaining open tickets. We will check in the on the progress of the work on the mobile and online banking platform. Luckily our engineers got right to work and found the problem and restored service! This ticket is now resolved.
 
![image](https://user-images.githubusercontent.com/114452968/231211306-104c77d6-c596-4597-bffd-218ed70b365a.png)
![image](https://user-images.githubusercontent.com/114452968/231211363-188b532d-bb71-4c01-91ec-ec4c1f27804e.png)
 
Ben logs in to check his tickets and sees the question about laptop upgrades. Since this is a low priority ticket, he decides to shift his focus, but makes sure to address the ticket by the end of the business day. Ben knows that procurement handles purchasing new laptops and lets the user know that the procurement department will be in touch by the end of the month. Ben closes the ticket.
 
![image](https://user-images.githubusercontent.com/114452968/231211412-1f48b754-08af-4eb0-982d-03170e324d06.png)
![image](https://user-images.githubusercontent.com/114452968/231211476-571cf115-29fd-4c6e-bc27-4ebdee837407.png)
 
Now we can take a look at all our closed tickets. Great! We have addressed all tickets that were submitted to our osTicket IT Helpdesk.
 
![image](https://user-images.githubusercontent.com/114452968/231211562-363f767f-d179-4194-bfa1-e0b54e23ba80.png)

## Summary

We submitted three tickets to our osTicket IT Helpdesk System running on Micrsoft Azure, triaged those tickets according to SLA’s, and then the tickets were then resolved according to their severity with a follow-up with the end-users to ensure satisfaction and system functionality. 
