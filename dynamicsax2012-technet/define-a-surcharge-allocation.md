---
title: Define a surcharge allocation
TOCTitle: Define a surcharge allocation
ms:assetid: 820afcfc-8c8a-49cc-b806-3553f42db32d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571554(v=AX.60)
ms:contentKeyID: 36058359
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Define a surcharge allocation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To allocate costs, you must first set up a **Calculation version**. You can then select one of the following different allocation types:

  - **Allocation**

  - **Internal cost allocation**

  - **Surcharge calculation**

To allocate costs with the allocation type **Surcharge calculation**, follow these steps.

1.  Click **Cost accounting** \> **Setup** \> **Calculation** \> **Calculation versions**. Select a calculation version and then click **Allocations**.

2.  Press CTRL+N to create a new line.

3.  In the **Allocation level** field, select the current level of allocation.

4.  In the **Allocation hierarchy** field, select the hierarchy. This field is available only if you have selected **Hierarchy** in the **Allocation level** field.

5.  In the **Allocation dimension** field, select the dimension for the allocation. This field is available only if you have selected **Dimension** in the **Allocation level** field

6.  In the **Allocation reference** field, select the reference for the allocation.

7.  In the **Allocation type** field, select **Surcharge calculation**.

8.  Click the **General** tab, and in **Allocation account** and **Offset account** fields, select the ledger accounts.

9.  Click the **Surcharge calculation** tab, and select the check boxes under **Cost share** field group.

10. Complete the fields under **Value calculation** field group to specify the allocated value.

11. Select the relevant check boxes under **Offset transaction dimension** field group.

12. Click the **Dimension** tab, and select the dimensions in the **Dimensions** field group.


> [!NOTE]
> <P>The allocations are calculated in the order shown on the <STRONG>Overview</STRONG> tab in the <STRONG>Allocations</STRONG> form. The order in which allocations are calculated is essential to the result. To change the order, click the <STRONG>Up</STRONG> and <STRONG>Down</STRONG> buttons.</P>



## See also

[Define an internal cost allocation](define-an-internal-cost-allocation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

