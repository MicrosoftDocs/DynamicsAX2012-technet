---
title: (ESP) Assign due date limits to terms of payment to calculate invoice due dates
TOCTitle: (ESP) Assign due date limits to terms of payment to calculate invoice due dates
ms:assetid: dd04736b-9669-4602-b279-a30a103cc1bd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923622(v=AX.60)
ms:contentKeyID: 50934003
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Spain
---

# (ESP) Assign due date limits to terms of payment to calculate invoice due dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create and post sales invoices or purchase invoices, the invoice due date is calculated based on the terms of payment that are specified for the invoices. The invoice due date that is calculated is verified against the due date limit. The invoice due date is then adjusted, if adjustment is required, to comply with the due date limit. For more information, see [(ESP) About using delivery dates to calculate invoice due dates](esp-about-using-delivery-dates-to-calculate-invoice-due-dates.md). If no due date limit is specified, the invoice due date that is calculated is used as the final invoice due date.

Use the **Terms of payment** form to specify a due date limit, so that you can make sure that the invoice due date that is calculated is in the specified due date limit.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Terms of payment**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Terms of payment**.

2.  Press CTRL+N to create terms of payment, or select a terms of payment line. For more information, see [(ESP) Terms of payment (modified form)](https://technet.microsoft.com/en-us/library/jj910987\(v=ax.60\)).

3.  On the **Setup** FastTab, select the **Use the delivery date to calculate the payment due date** check box to calculate the due date by applying terms of payment to the delivery date instead of the invoice date.

4.  In the **Due date limit** field, select a due date limit.

## See also

[(ESP) Due date limits (form)](https://technet.microsoft.com/en-us/library/jj923623\(v=ax.60\))

  


