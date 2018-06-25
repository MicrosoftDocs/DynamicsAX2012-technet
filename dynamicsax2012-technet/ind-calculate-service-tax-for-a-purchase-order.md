---
title: (IND) Calculate service tax for a purchase order
TOCTitle: (IND) Calculate service tax for a purchase order
ms:assetid: e83a922e-d0bc-4d60-87c6-d35d39f4e2b6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710917(v=AX.60)
ms:contentKeyID: 49386329
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchTable
- MsDynAx060.Forms.PurchTable
---

# (IND) Calculate service tax for a purchase order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Purchase order** form to calculate the service tax for a vendor. You can specify the service code and service category for vendors and foreign vendors before you post the purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  In the **Create purchase order** form, enter the required information, and then click **OK**. For more information about this form, see [Create a purchase order](create-a-purchase-order.md).

3.  In the **Purchase order** form, in the lower pane, on the **Line details** FastTab, click the **Tax information** tab.

4.  In the **Service tax** field group, in the **STC number** field, select the service tax code (STC) number of the company. The STC number is used to identify the ledger accounts that the service tax amounts are posted to.

5.  In the **Service code** field, select the service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



6.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to specify the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit, and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories for which input tax is paid. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to indicate the category of goods transport agency (GTA) service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

7.  On the **Action Pane**, on the **Purchase** tab, in the **Tax** group, click **Sales tax** to view the calculation of the service tax.

8.  Post the purchase order.

## See also

[(IND) Calculate service tax for purchase order credit note transactions](ind-calculate-service-tax-for-purchase-order-credit-note-transactions.md)

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) About accounting distributions and subledger journals](ind-about-accounting-distributions-and-subledger-journals.md)

[(IND) Service codes (form)](https://technet.microsoft.com/en-us/library/jj664830\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

