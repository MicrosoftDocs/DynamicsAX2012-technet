---
title: Clean up user logs
TOCTitle: Clean up user logs
ms:assetid: d2fcc77b-0ef9-48c8-9ef5-d842ca254a0c
ms:mtpsurl: https://technet.microsoft.com/library/Dd362082(v=AX.60)
ms:contentKeyID: 37822174
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Clean up user logs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **User log cleanup** form to delete user log information that is no longer needed.

1.  Click **System administration** \> **Inquiries** \> **Users** \> **User log**. Click **Clean up**.

2.  Enter a value in the **History limit (days)** field to define a limit for the deletion.
    
    Only log information that is older than the given number of days is deleted.

3.  Click **Select** to open the **Select log cleanup criteria** form, which is a version of the **Inquiry** form.

4.  Select your cleanup criteria.
    
    Select a user or a range of users and, optionally, additional user information, such as date and time. For more information, see [Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\)).

5.  Click **OK** to return to the **User log cleanup** form.

6.  Click **OK** to perform the cleanup once, or click the **Batch** tab to define parameters to clean up the user log regularly.


> [!NOTE]
> <P>The cleanup process permanently deletes data.</P>


  


