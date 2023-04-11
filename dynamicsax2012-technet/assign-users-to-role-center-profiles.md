---
title: Assign users to Role Center profiles
TOCTitle: Assign users to Role Center profiles
ms:assetid: dd7c7722-b2e2-4b7a-a268-a07ab5c7f4bb
ms:mtpsurl: https://technet.microsoft.com/library/Dd362099(v=AX.60)
ms:contentKeyID: 35133095
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Assign users to Role Center profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A user profile corresponds to a specific role in an organization, such as the controller or chief financial officer. The profile that you assign a user determines the Role Center page that is displayed when the user opens the Microsoft Dynamics AX client or Enterprise Portal for Microsoft Dynamics AX. This topic describes how to add either a single user or multiple users to a profile.


> [!NOTE]
> <P>A user can be assigned to only one user profile per company. If a user has access to multiple companies in Microsoft Dynamics AX, you can assign that user to the same profile for all companies, or you can assign the user to a different profile for each company.</P>



## Before you begin

1.  Verify that user profiles were enabled during Setup. For more information, see [Select default profiles for Role Centers](select-default-profiles-for-role-centers.md).

2.  Create a list of users and their corresponding profiles.

## Assign a single user to a profile

1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Select the profile that you want to assign the user to.

3.  Click **Add user**.

4.  Select the user in the list.

5.  Specify whether the profile applies to all of the companies that the user is assigned to in Microsoft Dynamics AX, or whether the profile applies only to specific companies.
    
      - If you select **All companies**, the user is assigned to this profile for all companies. Therefore, the user sees the same Role Center page for all companies.
    
      - If you select **Select companies**, the user is assigned to this profile only for the companies that you specify. You can assign this user to other profiles for other companies.

6.  Click **Apply** to save changes.
    
    The user must restart the Microsoft Dynamics AX client or refresh the Web browser to view the Role Center.

## Assign multiple users to a profile

1.  Click **System administration** \> **Common** \> **Users** \> **User profiles**.

2.  Select the profile that you want to assign the users to.

3.  Click **Bulk add users**.

4.  Select the users in the list.

5.  Specify whether the profile applies to all of the companies that each user is assigned to in Microsoft Dynamics AX, or whether the profile applies only to specific companies.
    
      - If you select **All companies**, the users are assigned to this profile for all companies. Therefore, the users see the same Role Center page for all companies.
    
      - If you select **Select companies**, the users are assigned to this profile only for the companies that you specify. You can assign these users to other profiles for other companies.

6.  Click **Apply** to save changes.
    
    The users must restart their Microsoft Dynamics AX clients or refresh their Web browsers to view their Role Centers.

## See also

[Manage user profiles for Role Centers](manage-user-profiles-for-role-centers.md)

[Configure Role Centers](configure-role-centers.md)

[Checklist: Configure Role Centers](checklist-configure-role-centers.md)

  


