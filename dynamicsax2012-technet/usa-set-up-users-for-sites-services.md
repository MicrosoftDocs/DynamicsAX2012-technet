---
title: (USA) Set up users for Sites Services
TOCTitle: (USA) Set up users for Sites Services
ms:assetid: 2f064a94-0bca-4075-8032-3e2b7f5fe465
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208541(v=AX.60)
ms:contentKeyID: 36056293
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (USA) Set up users for Sites Services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

All users in online services for Microsoft Dynamics ERP have one or more roles with respect to their organization and the particular online service. Each user has access to specific services and actions as authorized by their roles. For example, someone with the Sites-Administrators role can set up and maintain Sites Services for Microsoft Dynamics ERP, while someone with the Sites-Users role can use Sites Services, but not administer it.

When you sign up for a new online service, you are automatically added to the organization and the online service. You are also assigned a service administrator role for that service, so you can add other users and maintain their roles.

## Add a user and assign roles

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Configuration checklist**.

2.  Click **Set up users** to open the **User management** page in Customer Portal.

3.  Click **New**.

4.  Specify the following information about the user:
    
      - First and last name.
    
      - Windows Live™ ID.
        

        > [!NOTE]
        > <P>If the user is a member of CustomerSource, PartnerSource, or the Microsoft Dynamics Community, use the same Windows Live ID as for those sites.</P>

    
      - Primary e-mail address.

5.  Under **Services and roles**, in the **Available roles** list, select a role for the user, and then click the single arrow to add the role to the **Selected roles** list.
    

    > [!TIP]
    > <P>You can click the double arrow to add all roles.</P>



6.  Click **Save**.

7.  In the list of users, select the check box for the user whom you just added, and then click **Send invitation**.
    
    The user will receive an e-mail message with a link to complete his or her association with the online service. The user must use the same Windows Live ID to sign in to the service that you specified in step 4.

8.  Repeat steps 3 through 7 for each user that you want to add.

9.  When you are finished, click **Sign out**.

## Edit a user's profile

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Configuration checklist**.

2.  Click **Set up users** to open the **User management** page in Customer Portal.

3.  Select the check box for the user whose profile you want to edit, and then click **Edit**.

4.  Edit the user’s name, e-mail address, or roles, as necessary.
    

    > [!NOTE]
    > <P>You cannot edit the user’s Windows Live ID. If you need to change it, you must delete the profile and create a new one with the new Windows Live ID.</P>



5.  Click **Save**.

6.  When you finish, click **Sign out**.

## Delete a user's profile

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Configuration checklist**.

2.  Click **Set up users** to open the **User management** page on Customer Portal.

3.  Select the check box for the user that you want to delete, and then click **Edit**.

4.  Under **Services and roles**, remove all roles from the **Selected roles** list.
    
    You can click the double arrow to remove all roles.

5.  Click **Save**.

6.  Select the check box for the user whose profile you want to delete, and then click **Delete**.

7.  When you finish, click **Sign out**, and then close the browser.

## See also

[(USA) Set up and maintain a Sites Services account](usa-set-up-and-maintain-a-sites-services-account.md)

[(USA) Activate or deactivate a solution](usa-activate-or-deactivate-a-solution.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

