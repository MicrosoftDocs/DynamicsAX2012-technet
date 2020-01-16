---
title: (RUS) Allocate charges to other item invoices to include allocations to an item cost price
TOCTitle: (RUS) Allocate charges to other item invoices to include allocations to an item cost price
ms:assetid: 2f75fa31-ac2f-46f0-8b9f-9d7650ba78b2
ms:mtpsurl: https://technet.microsoft.com/library/JJ733195(v=AX.60)
ms:contentKeyID: 49685163
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Allocate charges to other item invoices to include allocations to an item cost price 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can allocate charges that are incurred from one vendor invoice to the cost of items in another vendor invoice. You can allocate expenses from a vendor invoice line to a non-stocked or category-based purchase order line. You can also allocate non-stocked or category-based vendor invoice lines to purchase items as expenses.

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select a vendor invoice, and then click **Charges** \> **Allocation**.

3.  In the **Charges allocation** field, select the method to use to allocate the charges, from the following options:
    
      - **Net amount** – Charges are allocated according to each line amount relative to the total net amount of the service invoice.
    
      - **Quantity** – Charges are allocated according to the number of units for each line relative to the total number of units for the service invoice.
    
      - **Gross weight** – Charges are allocated equally, according to the gross weight of the items that are received.
    
      - **Volume** – Charges are allocated equally, according to the volume of the items that are received.

4.  In the **Posting date** field, select the date of the allocation transaction.

5.  Select the **Select** check box to select a posted invoice that includes charges.

6.  In the **Allocation mode** field, verify that **Include to the cost price** is selected. **Include to the cost price** is the default allocation mode.

7.  In the lower pane, click **Choose** to specify the selection criteria that are used to transfer the invoice lines to the **Allocation base** grid.

8.  Select the **Select** check box to select the invoice lines that the charges are allocated to.

9.  Click **Allocation** to allocate the charges. The allocation amount and the charges code are displayed in the right pane of the **Allocation base** grid.

10. In the right pane, in the **Amount** field, modify the amount to allocate to the selected invoice, if a different amount is required.

11. Click **Post** to post the allocation transaction.

## See also

[Vendor invoice journal (form)](https://technet.microsoft.com/library/aa587621\(v=ax.60\))

  


