---
title: (IND) Calculate VAT for various purchase types
TOCTitle: (IND) Calculate VAT for various purchase types
ms:assetid: 48718f9a-908f-46e2-a288-fe045de36e79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664671(v=AX.60)
ms:contentKeyID: 49385734
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Calculate VAT for various purchase types [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Value Added Tax (VAT) can be calculated for various purchase types in a purchase order. If the VAT goods type is **Input goods**, the VAT amount is calculated and posted to the VAT recoverable account.

If the transaction is for capital goods, the VAT amount is calculated and posted to the VAT deferred account and the VAT deferment installments are created, based on the deferment schedule set up for the Tax Identification Number (TIN).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **New** \> **Purchase order**, or double-click a purchase order.

2.  Enter the required details.

3.  In the **Purchase type** field, select the type of purchase.

4.  Click the **Setup** FastTab.

5.  Select the sales tax group for the purchase order in the **Sales tax group** field.

6.  Select the item sales tax group for VAT for the item in the **Item sales group** field.

7.  Click **Line view**, and then enter the required details in the **Line details** FastTab.

8.  Click the **Tax information** tab and enter the details in the **VAT** field group.

9.  Select the TIN in the **Tax Identification Number (TIN)** field.

10. Select the following category of goods for the transaction in the **VAT goods type** field:
    
      - **Input** – Select this option if the goods are input goods.
    
      - **Capital** – Select this option if the goods are capital goods.

11. Enter the non-recoverable percentage for the purchase order in the **Non-recoverable pct.** field.
    

    > [!NOTE]
    > <P>Non-recoverable percentage is entered for purchased goods that are used for production or manufacturing of nontaxable goods.</P>



12. Post the purchase order.
    

    > [!NOTE]
    > <P>The percentage of tax amount defined in the <STRONG>Non-recoverable pct</STRONG> field is posted to the ledger account (debit type) or loaded on inventory. The remaining amount is posted to the deferred account or recoverable account for the specified TIN, based on the transaction.</P>



## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

