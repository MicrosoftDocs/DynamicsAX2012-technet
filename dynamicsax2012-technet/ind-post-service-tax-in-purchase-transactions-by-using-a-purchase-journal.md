---
title: (IND) Post service tax in purchase transactions by using a Purchase journal
TOCTitle: (IND) Post service tax in purchase transactions by using a Purchase journal
ms:assetid: d6f98db8-4b05-4a57-bfa4-58834f731631
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664954(v=AX.60)
ms:contentKeyID: 49386283
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchTable
- MsDynAx060.Forms.PurchTable
---

# (IND) Post service tax in purchase transactions by using a Purchase journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

You can create a purchase order to record details about goods, and then calculate service tax for the purchase transaction in a purchase journal. When you post the service tax in a purchase journal, the service tax amount is posted to a ledger account. You can also specify the service codes and service categories for vendors and foreign vendors before you post the journal.

Use the **Purchase order** form to identify the ledger accounts that the service tax amounts are posted to.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  In the **Create purchase order** form, enter the required information, and then click **OK**. For more information about this form, see [Create a purchase order](create-a-purchase-order.md).

3.  In the **Purchase order** form, on the **Line details** FastTab, click the **Tax information** tab.

4.  In the **STC number** field, select the service tax code (STC) number of the legal entity. The ledger accounts for posting the service tax amounts are identified by the STC number.

5.  In the **Service code** field, select the service code for the transaction line.

6.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, specify a service category. The following options are available:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select the Goods Transport Agency (GTA) service category for a GTA vendor.

## See also

[(IND) Calculate service tax for a purchase order](ind-calculate-service-tax-for-a-purchase-order.md)

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

