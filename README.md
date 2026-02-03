<p align="center">
  <img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/daa445be-b28b-4116-8795-886f90dbb7ea" />
</p>

# osTicket: Ticket Lifecycle

This project focuses on the full lifecycle of working support tickets within a help desk environment. I created new help tickets to simulate common user issues, triaged them based on urgency and category, and then worked each ticket through troubleshooting and resolution until completion. This lab demonstrates practical experience with ticket management, prioritization, communication, and end-to-end support workflow execution—key skills for IT support and service desk roles.

---

## Environments and Technologies Used

- Microsoft Azure
- Azure Virtual Network
- osTicket
- Remote Desktop Protocol (RDP)

---

## Lab Objectives

- Create support tickets to simulate real-world user issues within a help desk system  
- Triage tickets by evaluating urgency, impact, category, and appropriate assignment  
- Work tickets through the full resolution process, including troubleshooting, documentation, and communication  
- Apply structured help desk workflows to ensure efficient and accurate ticket handling  
- Strengthen practical understanding of incident management and end-to-end support operations  

---

## Step-by-Step Walkthrough

### Lab Environment

- **Platform:** Microsoft Azure
- **Virtual Machine:** Windows 10 Pro
- **Ticketing System:** osTicket
- **Required osTicket Setup:**
  - [osTicket Prerequisites & Installation](https://github.com/RyanKennon/osTicket-Prerequisites-Installation)
  - [osTicket Post-Installation Configuration](https://github.com/RyanKennon/osTicket-PostInstallation-Configuration/blob/main/README.md)

<p align="center">
  <img width="1818" height="592" alt="Untitled Diagram-Page-1 drawio" src="https://github.com/user-attachments/assets/5707ad74-caf1-4f74-8372-162c5ec228a1" />
</p>

---

### 1) Create Help Tickets

1. [Login as an end user](http://localhost/osTicket) and create a ticket with the following information:
  - Ticket 1
    - **Help Topic:** General Inquiry / Other
    - **Issue Summary:** entire mobile/online banking system is down
    - **Issue Description:** When I got back from lunch, I couldn't log into the online banking system portal, and none of my tellers at the bank can either.
  
<p align="center">
  <img width="848" height="907" alt="Untitled Diagram-Page-1 drawio" src="https://github.com/user-attachments/assets/0ff6dec4-c606-4755-b445-feb651453f77" />
</p>

2. Create a second ticket with the follwing information:
  - Ticket 2
    - **Help Topic:** Personal Computer Issues
    - **Issue Summary:** Adobe Reader not working
    - **Issue Description:** Some people in the accounting department can't use adobe reader

<p align="center">
  <img width="847" height="886" alt="Untitled Diagram-Page-2 drawio" src="https://github.com/user-attachments/assets/d0848412-2819-4b97-ad53-94b8a3abc627" />
</p>

---

### 2) Triage Tickets

1. [Log into the agent portal](http://localhost/osTicket/scp/login.php)

<p align="center">
  <img width="966" height="418" alt="Untitled Diagram-Page-3 drawio" src="https://github.com/user-attachments/assets/1183249f-77cf-4992-a3a8-6b19ce02431b" />
</p>

2. Observe the **Adobe Reader not working** ticket
3. Make the following changes:
  - **Priority:** High
  - **Department:** Support
  - **SLA:** Sev-B
  - **Assigned To:** John

<p align="center">
  <img width="970" height="321" alt="Untitled Diagram-Page-4 drawio" src="https://github.com/user-attachments/assets/d1df2320-11c2-47fd-bd9b-2f098fea9e69" />
</p>

4. Close Ticket

<p align="center">
  <img width="970" height="252" alt="Untitled Diagram-Page-5 drawio" src="https://github.com/user-attachments/assets/8fd8b5e2-c054-403b-b457-553502dee969" />
</p>

5. Observe the **entire mobile/online banking system is down** ticket
6. Make the following changes:
  - **Priority:** Emergency
  - **SLA:** Sev-A
  - **Help Topic:** Business Critical Outage
  - **Assigned To:** Jane

<p align="center">
  <img width="965" height="308" alt="Untitled Diagram-Page-6 drawio" src="https://github.com/user-attachments/assets/09fe4c3f-046e-47a5-990e-6e8c71f49571" />
</p>

---

### 3) Work Ticket to Completion

1. Long into the agent portal as SysAdmin
2. Observe the **entire mobile/online banking system is down** ticket
3. Post reply to the ticket

<p align="center">
  <img width="975" height="681" alt="Untitled Diagram-Page-7 drawio" src="https://github.com/user-attachments/assets/dcc41188-2595-48d8-b5c3-c29c1f47f426" />
</p>

4. Close ticket

---

## Outcome

- Successfully created help tickets to simulate common user issues and support requests  
- Triaged tickets based on urgency, category, and required level of support  
- Worked each ticket through the full resolution process, including troubleshooting and documenting actions taken  
- Communicated updates and resolutions effectively within the ticketing system  
- Demonstrated practical understanding of help desk workflows, incident management, and end-to-end ticket handling  

---

## Skills Demonstrated

- Creating, categorizing, and managing help desk tickets  
- Triaging support requests based on urgency, impact, and required action  
- Troubleshooting user issues and applying systematic problem-solving techniques  
- Documenting steps taken during the ticket resolution process  
- Communicating effectively with users and team members through ticket updates  
- Managing end-to-end incident workflows within a ticketing system  
- Strengthening practical understanding of IT support operations and service desk best practices  
