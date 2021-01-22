---
title: Create or update route operations
TOCTitle: Create or update route operations
ms:assetid: 438c4750-7263-473d-bef5-3d7253e84b9a
ms:mtpsurl: https://technet.microsoft.com/library/Aa496965(v=AX.60)
ms:contentKeyID: 36056879
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create or update route operations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Production control** \> **Common** \> **Routes** \> **All routes**.

2.  Click **Route** and then press CTRL+N to create a new line.

3.  In the **Oper. No.** field, enter the operation number associated with the route.
    
    The operation number defines the sequence of the operations on the route. When you create a new operation, Microsoft Dynamics AX automatically suggests 10 as the first operation number, and the next operation in increments of 10. You can change this number manually.

4.  In the **Priority** field, select the priority you want the operation to have.
    
    Priority is used to manage simultaneous operations. Microsoft Dynamics AX uses this data when you use more than one resource at a time.

5.  In the **Operation** field, select the operation associated with the route.

6.  In the **Scrap percentage** field, enter the scrap percent that defines the expected overconsumption for the operation.

7.  The **Accumulated** field displays the calculated accumulated scrap percentage for the operation on the route.

8.  In the **Next** field, enter the next operation number in the route.

9.  In the **Link type** field, enter the kind of attachment to the next job.

10. In the **Hourly rate / piecework rate**, enter the type of pay on the jobs that use this rate.  


> [!NOTE]
> <P>Use the table at the bottom of the form to view and manage details about the operational parameters and resource requirements related to the selected operation. You change this information at any time.</P>



## See also

[About working with routes in production](about-working-with-routes-in-production.md)

  


