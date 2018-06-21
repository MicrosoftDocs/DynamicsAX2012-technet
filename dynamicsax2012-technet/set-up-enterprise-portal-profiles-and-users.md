---
title: Set up Enterprise Portal profiles and users
TOCTitle: Set up Enterprise Portal profiles and users
ms:assetid: 0d8bb623-1d1f-4de1-9ca2-065d4a95a4f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580566(v=AX.60)
ms:contentKeyID: 39519044
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up Enterprise Portal profiles and users [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

If you have set up Enterprise Portal for Microsoft Dynamics AX, you must set up user profiles for the employees who access Enterprise Portal. These profiles define each user's role and specify the store information that the user has access to.

Use the following procedures to set up Enterprise Portal profiles and users. You can also view the Role Center for each profile.

## Import the retail user profiles


> [!NOTE]
> <P>You must set up a Microsoft Dynamics AX user account for each employee who requires access to Enterprise Portal. For information about how to set up user profiles, see Microsoft Dynamics AX Help.</P>



1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Click **Import**, and then click **Import from AOT**.

3.  Select the check boxes for the profiles to import, and then click **OK**.
    
    There are four retail user profiles:
    
      - Retail Merchandising Manager
    
      - Retail Operations Manager
    
      - Retail Store Inventory Clerk
    
      - Retail Store Manager

## Assign users to the retail user profiles

1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Select a retail user profile.

3.  Click **Add user**, and then, under **Select user**, select a user.

4.  Under **Select company**, click **All companies (Profile: %1)**. Alternatively, click **Select companies**, and then select the check boxes for the companies that you want.

5.  Repeat steps 2 through 4 for the other retail user profiles.

## Assign stores to the users for each retail user profile

By assigning a store to a user, you allow the user to access information for that store in Enterprise Portal.

1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Select a retail user profile, and then click the **Users** tab.

3.  Select a user, and then click **Assign stores**.

4.  Press CTRL+N to add a store to the list. Then, in the **Local store number** field, select a store.

5.  If the store is the employee's primary store, select the **Primary store** check box.

6.  Repeat step 4 for any other stores that this user requires access to.

7.  Repeat steps 2 through 6 for the other users who are assigned to the retail user profiles.

## View the Role Center for a retail user profile

1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Select a retail user profile.

3.  Click **View role center**.

## See also

[About setting up staff](about-setting-up-staff.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

