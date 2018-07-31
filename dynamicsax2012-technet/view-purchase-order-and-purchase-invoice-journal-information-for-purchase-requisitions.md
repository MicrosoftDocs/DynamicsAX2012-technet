---
title: View purchase order and purchase invoice journal information for purchase requisitions
TOCTitle: View purchase order and purchase invoice journal information for purchase requisitions
ms:assetid: 91cf879c-fadf-4deb-b046-ecd4f2e849af
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232170(v=AX.60)
ms:contentKeyID: 36687397
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approved purchase requisitions
- invoice journal
- purchase order confirmation
audience: Application User
ms.search.region: Global
---

# View purchase order and purchase invoice journal information for purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to view information about purchase orders and invoices that were created from purchase requisitions.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** page, select the following filters to view the purchase requisitions:
    
      - In the **Requester** field, select the name of the user whose purchase requisitions you want to view.
    
      - In the filter pane, select **Status** and then enter **Approved** to view only approved purchase requisitions.
        

        > [!NOTE]
        > <P>You cannot modify a purchase requisition after it has been approved.</P>



3.  In the list, double-click the purchase requisition for which you want to view the details.

4.  In the **Purchase requisitions** form, on the **Purchase requisition lines** FastTab, select a purchase requisition line. Then click **Purchase requisition line** \> **Purchase order confirmations** to open the **Purchase order confirmations** form.
    
    The **Purchase order confirmations** form displays the purchase order that was generated for the purchase requisition. Every time the purchase order is sent to the vendor and marked as confirmed, an entry is created in the form. If the purchase order has not been confirmed, no entries appear in the form.

5.  To open the **Invoice journal** form, in the **Purchase requisitions** form, on the **Purchase requisition lines** FastTab, select a purchase requisition line, and then click **Purchase requisition line** \> **Invoice journals**.
    
    The invoice journal displays a list of any invoices that have been generated for the purchase order.

## See also

[Vendor invoice journal (form)](https://technet.microsoft.com/en-us/library/aa587621\(v=ax.60\))

  


