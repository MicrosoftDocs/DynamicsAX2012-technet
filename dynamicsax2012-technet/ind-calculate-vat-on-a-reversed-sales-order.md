---
title: (IND) Calculate VAT on a reversed sales order
TOCTitle: (IND) Calculate VAT on a reversed sales order
ms:assetid: ca7d98c8-4ed2-4fae-9961-3678f3683b52
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664914(v=AX.60)
ms:contentKeyID: 49386243
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Calculate VAT on a reversed sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select the sales order, and on the **Action Pane**, in the **Sell** group, click **Credit note**.

2.  Select the **Tax as per original invoice** check box to calculate VAT for the invoice date. The calculated VAT amount is reversed to the VAT payable account for sales orders.

3.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>If the <STRONG>Tax as per original invoice</STRONG> check box is not selected, the VAT amount is calculated for the date that the credit note is created and the calculated VAT amount is reversed, and then posted to the VAT payable account for sales orders. If the VAT settlement process is already run for the period, the calculated VAT amount is posted to the VAT payable account.</P>



## See also

[(IND) Copy sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj664849\(v=ax.60\))

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) Enter VAT details in sales orders](ind-enter-vat-details-in-sales-orders.md)

[(IND) Calculate VAT for various sales order types](ind-calculate-vat-for-various-sales-order-types.md)

[(IND) Calculate VAT on a reversed purchase order](ind-calculate-vat-on-a-reversed-purchase-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

