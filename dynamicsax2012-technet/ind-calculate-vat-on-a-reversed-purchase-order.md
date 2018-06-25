---
title: (IND) Calculate VAT on a reversed purchase order
TOCTitle: (IND) Calculate VAT on a reversed purchase order
ms:assetid: 21ea2fb0-f422-491d-999a-3953e35dcd0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664551(v=AX.60)
ms:contentKeyID: 49385630
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Calculate VAT on a reversed purchase order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



If a returned order is posted for an item (the VAT goods type selected is **Input** or **Capital goods**) without being attached to a purchase order, the VAT amount is posted to the VAT payable account instead of being posted to the VAT recoverable or the VAT deferred account.

If capital goods are returned after the transfer of the VAT deferment installment from the VAT deferred account to the VAT recoverable account, the VAT amount that is settled is credited to the VAT payable account.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and on the **Action Pane**, in the **Purchase** group, click **Credit note**.

2.  Select the **Tax as per original invoice** check box to calculate VAT for the invoice date. The calculated VAT amount is reversed to the VAT recoverable or deferred account for purchase orders.

3.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>If the <STRONG>Tax as per original invoice</STRONG> check box is not selected, the VAT amount is calculated for the date that the credit note is created and the calculated VAT amount is reversed, and then posted to the VAT recoverable or deferred account for purchase orders.</P>
    > <P>If the VAT settlement process is already run for the period, the calculated VAT amount is posted to the VAT payable account.</P>



## See also

[(IND) Copy purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664580\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

