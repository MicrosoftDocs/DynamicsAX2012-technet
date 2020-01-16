---
title: (IND) Allocate charges to purchase order lines
TOCTitle: (IND) Allocate charges to purchase order lines
ms:assetid: 706feeb0-38b7-4714-9b72-fd2d68ea2e19
ms:mtpsurl: https://technet.microsoft.com/library/JJ677925(v=AX.60)
ms:contentKeyID: 49385889
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Allocate
- miscellaneous charges
- (IND)
- India
audience: Application User
ms.search.region: India
---

# (IND) Allocate charges to purchase order lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this information to allocate a charge, such as freight, to the lines on a purchase order.


> [!NOTE]
> <P>Charges are allocated to all lines based on the criteria that you select. You can exclude specific lines that otherwise meet the criteria, as explained in the following steps. To allocate charges only to selected lines, define the charges manually for each line.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **New** \> **Purchase order**, or double-click a purchase order.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **New** \> **Purchase order**, or double-click a purchase order.

2.  On the **Action Pane**, click the **Purchase** tab and select **Allocate charges** in the **Charges** group to allocate the charges to the purchase order lines.

3.  Select the allocation method from the **Charges allocation** list.
    

    > [!NOTE]
    > <P>This step applies only if the charge is a fixed amount.</P>

    
      - Select **Net amount** to allocate charges according to each line amount relative to the total net amount for the purchase order or invoice.
    
      - Select **Quantity** to allocate charge according to the number of units for each line relative to the total number of units for the purchase order or invoice.
    
      - Select **Per line** to allocate charges equally among the total number of lines.
    
      - Select **Whole amount** to allocate the whole amount of charges to the selected purchase order lines or invoice lines.

4.  In the **Allocate charges to lines** field, specify whether to allocate charges to **All lines**, **Positive lines**, or **Negative lines**.

5.  Select **Allocate all** to allocate charges to purchase order lines, even if the charge code has a debit type other than **Item**.

6.  Select **Received** to allocate charges only to received order lines.

7.  Select **Stocked** to allocate charges only to inventoried order lines.

8.  Optional: Select **Show selections and clear specific lines** to exclude specific lines from this allocation.
    

    > [!NOTE]
    > <P>This check box is not available if charges have not been set up.</P>

    
    When you select this check box, it opens a grid that includes only lines that match the criteria in the **Allocate charges to lines** and the **Stocked** fields. For example, if you select **Positive lines** and **Stocked**, only lines that are both positive and inventoried are shown in the grid. In addition, the grid automatically filters out any lines for which the full quantity has already been received.
    
    When the grid is open, you can clear the **Include** check box for each line that should be excluded from allocation.
    

    > [!IMPORTANT]
    > <P>Be sure to leave the grid open when you click <STRONG>OK</STRONG>. If you close the grid before you click <STRONG>OK</STRONG>, charges will be allocated based on the criteria that you previously selected.</P>



## See also

[(IND) Allocate charges (modified form)](https://technet.microsoft.com/library/jj677929\(v=ax.60\))

  


