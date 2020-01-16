---
title: (IND) Verify export transaction details for an Advance Authorization incentive scheme
TOCTitle: (IND) Verify the export transaction details for the Advanced Authorization (AA) incentive scheme
ms:assetid: d150599e-73a1-4d58-8205-d66f22431a64
ms:mtpsurl: https://technet.microsoft.com/library/JJ664939(v=AX.60)
ms:contentKeyID: 49386268
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- export transaction
- (IND)
- india
- AA
- Advanced Authorization
- AA incentive scheme
audience: Application User
ms.search.region: India
---

# (IND) Verify export transaction details for an Advance Authorization incentive scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To track the export obligation for input goods that were imported under an Advance Authorization (AA) scheme, you can attach the AA incentive scheme to an export order. Use this procedure to verify the export obligation for an AA incentive scheme.

For more information about how to create an export order and attach an AA incentive scheme to it, see [(IND) Create an export order and apply the AA incentive scheme to the export order](ind-create-an-export-order-and-apply-the-aa-incentive-scheme-to-the-export-order.md).

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.

2.  On the **EXIM Authorization schemes** list page, in the **Authorization type** field, select **AA**.

3.  Open an authorization scheme.

4.  In the **EXIM Authorization schemes** form, on the **Overview** FastTab, select an authorization. Then click **Inquiry** \> **Export obligation**.

5.  In the **Export obligation** form, review the following fields:
    
      - **Obligation** – This field display the cumulative value that appears in the **Export assessable value** field on the **Lines** FastTab in the **EXIM Authorization schemes** form.
        
        The cumulative value is the sum of the assessable value for the line that has a license status of **Original**, plus the assessable value for any lines that have a license status of **Extended**.
    
      - **Achieved** – This field displays the value that appears in the **Cumulative assessable value** field in the **Export transaction details** form.
    
      - **Balance** – This field displays the difference between the values in the **Obligation** and **Achieved** fields. The calculation is as follows: obligation value – achieved value = balance.
    
    The **Item number**, **Product name**, **Quantity**, and **Assessable value** fields display the values that appear in the same fields in the **Export transaction details** form.

6.  Click **Transactions**, and then, in the **Export transaction details** form, review the export obligation transaction details for the AA incentive scheme.

7.  In the **Item number** field, select the number of the export item. Then select the **All** check box to view all export transactions for the item.
    
    The cumulative Free On Board (FOB) value of the export transactions is shown in the **Cumulative assessable value** field.

## See also

[(IND) Create an export order and apply the AA incentive scheme to the export order](ind-create-an-export-order-and-apply-the-aa-incentive-scheme-to-the-export-order.md)

[(IND) Export obligation (form)](https://technet.microsoft.com/library/jj677976\(v=ax.60\))

[(IND) Export transaction details (form)](https://technet.microsoft.com/library/jj664611\(v=ax.60\))

  


