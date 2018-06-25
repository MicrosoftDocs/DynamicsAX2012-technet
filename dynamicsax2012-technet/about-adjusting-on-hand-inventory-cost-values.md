---
title: About adjusting on-hand inventory cost values
TOCTitle: About adjusting on-hand inventory cost values
ms:assetid: eeb40d83-97b7-43de-b89e-e2002023cc91
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243266(v=AX.60)
ms:contentKeyID: 36059913
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About adjusting on-hand inventory cost values [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Adjustment of on-hand inventory** form to adjust the cost value of the on-hand inventory quantities after an inventory close process is run.


> [!NOTE]
> <P>The <STRONG>Adjustment of on-hand inventory</STRONG> form is available only when you first select the record of a completed inventory close process.</P>



**Example**

You have the following transactions in February:

  - February 1: An inventory financial receipt for a quantity of 2 at a cost of USD 10.00

  - February 5: An inventory financial receipt for a quantity of 1 at a cost of USD 13.00

  - February 19: An inventory financial issue for a quantity of 1 at a running average cost of USD 11.00

This item was set up with the first in, first out (FIFO) inventory model, and inventory close was performed as of February 28. The financial issue transaction of USD 11.00 will be settled to the financial receipt dated February 1, and an adjustment of USD 1.00 will be made.

The following inventory receipts will then contain open inventory quantities:

  - February 1: A quantity of 1 at a cost of USD 10.00

  - February 5: A quantity of 1 at a cost of USD 13.00

To set the cost of these two items to USD 15.00, use the on-hand adjustment option to adjust the open on-hand quantities as of the last inventory close period.


> [!NOTE]
> <P>The posting date of the on-hand adjustment transaction will be the date of the last inventory close. This date value cannot be modified.</P>



## See also

[Adjustment of on-hand inventory (form)](https://technet.microsoft.com/en-us/library/aa553861\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

