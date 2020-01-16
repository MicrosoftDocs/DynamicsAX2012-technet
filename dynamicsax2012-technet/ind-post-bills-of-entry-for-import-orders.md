---
title: (IND) Post bills of entry for import orders
TOCTitle: (IND) Post bills of entry for import orders
ms:assetid: cc4613d7-fd2a-4f94-8f4d-8fe26f91d78d
ms:mtpsurl: https://technet.microsoft.com/library/JJ733171(v=AX.60)
ms:contentKeyID: 49685139
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- import order
- bills of entry
- Post bills
audience: Application User
ms.search.region: India
---

# (IND) Post bills of entry for import orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Bill of entry** form to post a bill of entry and attach the bill of entry number to an import order. The bill of entry number is provided by the customs authority.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select the import purchase order to post a bill of entry for.

2.  On the **Action Pane**, on the **Customs** tab, click **Invoice registration**.

3.  In the **Invoice registration** form, select the import invoice number to associate with the import purchase order, and then click **Update**. Close the form.

4.  On the **All purchase orders** list page, on the **Action Pane**, on the **Customs** tab, click **Bill of entry**.

5.  Optional: In the **Bill of entry** form, select the **Bill of entry** check box, and then select the bill of entry number.
    
    Bill of entry numbers are maintained in the **Bill of entry number** form. For more information, see [(IND) Set up a bill of entry number for import orders](ind-set-up-a-bill-of-entry-number-for-import-orders.md).

6.  In the lower pane, on the **Overview** tab, in the **Import invoice number** field, select the import invoice that is associated with the bill of entry and the import purchase order.

7.  In the **Number** field, select the bill of entry number.
    

    > [!NOTE]
    > <P>The <STRONG>Number</STRONG> field is not available on the <STRONG>Overview</STRONG> tab if you select the <STRONG>Bill of entry</STRONG> check box on the <STRONG>Parameters</STRONG> tab in the upper pane.</P>



8.  On the **Setup** tab, in the **Bill of entry date** field, view or update the bill of entry date.
    
    The customs duty is calculated based on the bill of entry date.

9.  On the **Lines** tab, verify that the information for the import purchase order is correct.
    
      - The net amount is for the selected bill of entry quantity. The unit price of an item is multiplied by the quantity of the item to calculate the net amount.
    
      - The assessable value is based on the calculation of customs duty. The unit price of the item is multiplied by the quantity of the item and the charge is added to calculate the assessable value.

10. In the **Bill of entry** form, click **OK** to post the bill of entry.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

[(IND) Bill of entry number (form)](https://technet.microsoft.com/library/jj664729\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Import invoice number (form)](https://technet.microsoft.com/library/jj677885\(v=ax.60\))

  


