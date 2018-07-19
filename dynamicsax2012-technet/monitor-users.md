---
title: Monitor users
TOCTitle: Monitor users
ms:assetid: 2d98ea0a-d3bd-42cc-a96e-6a174c3c8d1e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496469(v=AX.60)
ms:contentKeyID: 39555336
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Monitor users 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes several features to help you monitor which users are currently logged on to Microsoft Dynamics AX, how frequently a particular user has logged on, and the length of time that a user has been logged on. The procedures in this topic explain how complete the following actions:

  - View which users are currently logged on.

  - Disconnect one or more connected users.

  - View logon statistics for a specified user.

## View which users are currently logged on

Click **System administration** \> **Common** \> **Users** \> **Online users**.

## Disconnect one or more connected users

You can end one or more user sessions from the **Online users** form. Before you disconnect a user, warn that user of the impending disconnection so that you do not disrupt an important operation such as a posting.

1.  Click **System administration** \> **Common** \> **Users** \> **Online users**.

2.  Select the user who you want to disconnect. Press and hold the CTRL key to select multiple users.

3.  Click **End sessions**.
    

    > [!IMPORTANT]
    > <P>If you disconnect a user because you changed permissions for a role, restart the Microsoft Dynamics AX server after you make this change. If you do not restart the server, members of the role might keep their former permissions until the next restart.</P>



## View logon statistics for a specified user

1.  Click **System administration** \> **Common** \> **Users** \> **Users**..

2.  Select the user for whom you want to view logon statistics.

3.  Click **User log**.

<!-- end list -->

  - By default, the **Overview** tab lists every time that the user logged on during the last 100 days. You can change the time period by clicking the **Clean up** button and selecting a new duration.

  - The **General** tab includes information about the user's computer ID, client type, and more.

  - The **Statistics** tab includes details about the user's session, such as the duration.

  


