---
title: Define an internal cost allocation
TOCTitle: Define an internal cost allocation
ms:assetid: fd3c0d2b-ea93-413d-acc5-5bdc85a0b53f
ms:mtpsurl: https://technet.microsoft.com/library/Aa500114(v=AX.60)
ms:contentKeyID: 36060104
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define an internal cost allocation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To allocate costs, you must first set up a calculation version. You can then select among the following three allocation types:

  - **Allocation**

  - **Internal cost allocation**

  - **Surcharge calculation**

To allocate costs by using the **Internal cost allocation** allocation type:

1.  Click **Cost accounting** \> **Setup** \> **Calculation** \> **Calculation versions**. Click **Allocations**.

2.  Press CTRL+N to create a new line.

3.  In the **Allocation level** field, select the allocation level. If you select **Hierarchy**, specify the allocation hierarchy in the **Allocation hierarchy** field.

4.  In the **Allocation reference** field, type a reference.

5.  In the **Allocation dimension** field, select an allocation dimension. The allocation dimension can be either a dimension or a division. This field is available only if you selected **Dimension** in the **Allocation level** field.

6.  In the **Allocation type** field, select **Internal cost allocation**.

7.  On the **General** tab, select **Allocation account** and **Offset account**.

8.  On the **Internal cost allocation** tab, select the check boxes under **Cost share**.

9.  In the **Service category** field, select the service category that you want to allocate. You can select only service categories for which the **Use of service category** field in the **Cost categories** form is set to **Internal cost allocation**.

10. In the **Cost rate type** field, select the type of cost rate for each value type.


> [!NOTE]
> <P>The allocations are calculated in the order shown on the <STRONG>Overview</STRONG> tab of the <STRONG>Allocations</STRONG> form. The order in which the calculations are run affects the result. To change the order, click the <STRONG>Up</STRONG> and <STRONG>Down</STRONG> buttons.</P>



## See also

[Define a surcharge allocation](define-a-surcharge-allocation.md)

  


