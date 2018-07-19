---
title: Add the packing unit and quantity to a sales order lines
TOCTitle: Add the packing unit and quantity to a sales order lines
ms:assetid: 7affc7ab-6b42-4c1b-aa2d-3e0180c6b4c8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550076(v=AX.60)
ms:contentKeyID: 36058253
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add the packing unit and quantity to a sales order lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order.

3.  Select the sales order line to which you want to add a packing unit and quantity, click the **Line details** FastTab, and then click the **Packing** tab.

4.  Select a packing unit in the **Packing unit** field.

5.  Enter the packing unit quantity in the **Packing unit quantity** field.

When sales order line is invoiced, packaging material transactions are created and the packaging material weights are calculated. Packaging material fees are not calculated when the invoice is posted nor are they invoiced.


> [!NOTE]
> <P>If a packing unit has been assigned to the item in the selected sales order line, the packing unit and packing unit quantity are loaded automatically. In this case, the quantity is calculated based on the ordered quantity (in inventory units) divided by the packing unit factor.</P>
> <P>- When the sales order line is posted, the packing unit and packing unit quantity is taken from the sales order line. However, you can change the values in the <STRONG>Update, print, edit, and inquire about an invoice</STRONG> form. This form is found on the <STRONG>Line details</STRONG> tab. This is relevant when the sales order is partly invoiced.</P>



## See also

[Print packing material weights on invoices](print-packing-material-weights-on-invoices.md)

  


