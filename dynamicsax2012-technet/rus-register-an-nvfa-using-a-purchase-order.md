---
title: (RUS) Register an NVFA using a purchase order
TOCTitle: (RUS) Register an NVFA using a purchase order
ms:assetid: fd12db27-cfa5-4ef4-b8fd-baa7f8d3327e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853249(v=AX.60)
ms:contentKeyID: 50396529
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register an NVFA using a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to register a not valuable fixed asset (NVFA) by using a purchase order.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **New** \> **Purchase order**.

2.  In the **Vendor account** field, select the vendor account that you require, and then click **OK**. For more information, see [Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\)).

3.  Create a new purchase order line.

4.  In the **Item number** field, select an item number. The item must be a fixed asset item and must have an NVFA posting profile.

5.  In the **Quantity** field, enter the quantity of the item that is ordered.

6.  In the **Unit price** field, enter the purchase price for an item unit.

7.  In the **Net amount** field, enter the amount. This amount includes any discounts that are applied.

8.  Post the vendor invoice. For more information, see [Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\)) and [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).
    

    > [!NOTE]
    > <P>The cost price of the item cannot be more than the limit that is specified in the <STRONG>Fixed asset parameters</STRONG> form. The posting profile that is displayed for the item must differ from the posting profile that is selected in the <STRONG>Fixed asset parameters</STRONG> form.</P>



## See also

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/en-us/library/jj721462\(v=ax.60\))

  


