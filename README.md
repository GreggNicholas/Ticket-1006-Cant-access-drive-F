# Introduction
This activity simulates an IT Support ticket submitted by a user. Your task is to resolve the issue and document the process, as you would using a ticketing system.  
To troubleshoot this ticket, you will need to import and launch a Virtual Machine named Ticket #1006 using VirtualBox.
# Objectives
Resolve ticket #1006 and document the process.
Equipment/Requirements
Computer with internet connection and VirtualBox installed.
The Ticket #1006 VM (Open Virtual Appliance (OVA) file).


Ticket ID #
1006
User Name
Learner01
User’s email
learner01@TechSolutions.com
Priority
High
Category
Other
Status
resolved
Subject
Can't access drive F
Asset
capstone120
Assigned to
Gregg Nicholas
Description
Hello, IT support,

I can’t access drive F on my computer. I need to save some files on this drive.
Please advise.

Thank you,
Learner01
# Tasks
I logged in as admin. Hot keyed win + R. Typed in diskmgmt.msc. Navigated to F drive. Right clicked and saw sharing is turned off. I clicked on advanced sharing. Ticked off the share this folder. Clicked on permissions. In shared permissions. I added Learner01. And gave them full control so they could save files on F drive. This didn’t solve the issue. I logged back as admin, navigated to advanced security settings for Volume :F. Here, I was able to modify permissions for learner01. I logged in as learner01 and was able to log in and see the corporate files and created a new folder. Case closed
# Resolution (Internal-facing)
To resolve Learner01’s issue with accessing drive F, I first logged in as an administrator and tried enabling sharing permissions. I opened Disk Management by pressing Windows + R, typing diskmgmt.msc, and navigating to drive F. From there, I right-clicked on the drive, selected Advanced Sharing, enabled Share this folder, and granted Full Control to Learner01 in the sharing permissions.
However, the issue was still not solved so I went back in as an admin and accessed the “Advanced Security Settings” for drive F. In this settings menu, I directly modified the NTFS permissions to ensure Learner01 had the required access.
Once I made these adjustments, I logged in as Learner01 to verify access. This time, I could open drive F, view corporate files, and even create a new folder, confirming that the permissions were correctly set.
To complete the documentation, I took a screenshot of Windows File Explorer with drive F open and accessible to Learner01.
The main issue was that sharing permissions alone weren’t enough for full local access. By adjusting both sharing and NTFS security permissions, I was able to provide the necessary access for Learner01.


# Resolution (Client-facing)
Hello Learner01,
The access issue with drive F has been resolved. Initially, the drive's permissions weren’t fully configured, which restricted your access. I adjusted both sharing and local security permissions, allowing you full control over the drive. You should now be able to save files and manage folders on drive F without any issues.
Please let me know if you experience any further issues.

Best,

Gregg Nicholas

It Support Specialist 




![Identifying lack of permissions to drive](https://github.com/GreggNicholas/Ticket-1006-Cant-access-drive-F/blob/main/Screen%20Shot%202024-12-01%20at%2022.57.26%20PM.png?raw=true)

![Assigning proper permissions](https://github.com/GreggNicholas/Ticket-1006-Cant-access-drive-F/blob/main/Screen%20Shot%202024-12-01%20at%2022.57.50%20PM.png?raw=true)

![Verifiying drive access](https://github.com/GreggNicholas/Ticket-1006-Cant-access-drive-F/blob/main/Screen%20Shot%202024-12-01%20at%2022.58.05%20PM.png?raw=true)


