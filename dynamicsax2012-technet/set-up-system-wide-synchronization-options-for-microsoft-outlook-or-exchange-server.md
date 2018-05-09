---
title: Set up system-wide synchronization options for Microsoft Outlook or Exchange Server
TOCTitle: Set up system-wide synchronization options for Microsoft Outlook or Exchange Server
ms:assetid: fce482b0-1966-421f-b378-31ba5fea9eb8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn879706(v=AX.60)
ms:contentKeyID: 63836100
ms.date: 12/19/2014
mtps_version: v=AX.60
---

# Set up system-wide synchronization options for Microsoft Outlook or Exchange Server 


This topic describes how to set up the contact and synchronization details mapping between Microsoft Dynamics AX and Microsoft Outlook or Exchange Server.

## Set up Microsoft Outlook or Exchange Server parameters

Use this procedure to set up the permissions and synchronization rules between Microsoft Dynamics AX and Microsoft Outlook or Exchange Server for all users.

1.  Click **Organization administration** \> **Setup** \> **Microsoft Outlook or Exchange Server synchronization** \> **Microsoft Outlook parameters**.

2.  In the **Microsoft Outlook or Exchange Server parameters** form, in the **Synchronization rights** field, select whether to assign synchronization rights to all users or to the administrator only.

3.  In the **Synchronization type** field group, select whether users who have synchronization rights can view or edit synchronized contact information. If you select that users can modify the information, select the default action.
    
    In the **Contacts delete action** field, select whether contact information is cleared or deleted from Microsoft Dynamics AX when a contact is deleted.

4.  In the **Program to synchronize** field, select whether you are synchronizing Microsoft Dynamics AX with Microsoft Outlook or Exchange Server.
    
    If you are synchronizing with Exchange Server, enter the URL.

## View synchronized information

Use the **Microsoft Outlook or Exchange Server administration** form to view which contacts are synchronized and who they are synchronized with. You can also use this form to add or delete synchronizations.

  - Click **Organization administration** \> **Setup** \> **Microsoft Outlook or Exchange Server synchronization** \> **Microsoft Outlook administration**.

## View synchronization set up

Use the **Microsoft Outlook or Exchange Server mapping** form to view the synchronization structure of contacts, appointments, and tasks between Microsoft Dynamics AX and Microsoft Outlook or Exchange Server. You can also use this form to update the synchronization structure.

  - Click **Organization administration** \> **Setup** \> **Microsoft Outlook or Exchange Server synchronization** \> **Microsoft Outlook mapping**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

