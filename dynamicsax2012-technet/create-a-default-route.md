---
title: Create a default route
TOCTitle: Create a default route
ms:assetid: 9d89b59e-4d36-40bb-8c71-42efda993eb9
ms:mtpsurl: https://technet.microsoft.com/library/Aa571712(v=AX.60)
ms:contentKeyID: 36058748
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a default route 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Default routes are used as templates to create the route of a specific product model. The operations that can be attached to a default route are the operations that have previously been defined in the **Production** module. When a product model uses a default route, any operation from the default route can be added to the modeling tree. However, the operations will always appear in the order in which they appear in the default route. Specific operations from the default route may be omitted, and new operations can be added before or after the default route operations. However, new operations cannot be inserted between the operations from the default route.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Setup** \> **Product builder** \> **Defaults** \> **Default routes**.

2.  Press CTRL+N to create a new line.

3.  Type a unique name for the default route in the **Name** field.

4.  Click **Approve**.

5.  Select the alias of the employee who approved the route, and then click **OK**.

6.  Click **Route** to add operations to the default route.

7.  In the **Operation** field of the opened form, select an operation from the list of previously created operations in the **Production** module.

8.  In the **Next operation** field, indicate the operation that will follow the current operation in the route.
    
    If the current operation is the last operation in the route, leave this field empty.

## See also

[Insert a Default node](insert-a-default-node.md)

  


