---
title: (ESP) Create and post free text invoices with delivery dates
TOCTitle: (ESP) Create and post free text invoices with delivery dates
ms:assetid: 8f67a255-8ff1-48f9-8219-972860e3ea20
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933295(v=AX.60)
ms:contentKeyID: 50877509
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- free text invoice
- delivery dates
- post invoice
- post free text invoice
audience: Application User
ms.search.region: Spain
---

# (ESP) Create and post free text invoices with delivery dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you create and post free text invoices with delivery dates, you must create due date limits in the **Due date limits** form. You must also select the **Use the delivery date to calculate the payment due date** check box in the **Terms of payment** form to check the calculated invoice due date against the effective due date limit. The invoice due date is adjusted to comply with the due date limit, if necessary. For more information, see [(ESP) Set up due date limits to calculate invoice due dates](esp-set-up-due-date-limits-to-calculate-invoice-due-dates.md) and [(ESP) Assign due date limits to terms of payment to calculate invoice due dates](esp-assign-due-date-limits-to-terms-of-payment-to-calculate-invoice-due-dates.md).

Invoice due dates for free text invoices are calculated in the same way as they are calculated for customer invoices, vendor invoices, and project invoices. For more information, see [(ESP) About using delivery dates to calculate invoice due dates](esp-about-using-delivery-dates-to-calculate-invoice-due-dates.md). Free text invoice transactions are included in the payment due date compliance report. For more information, see [(ESP) Generate the payment due date compliance report](esp-generate-the-payment-due-date-compliance-report.md).

Use the following procedure to create and post free text invoices with delivery dates.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, click **Free text invoice**.

3.  In the **Customer account** field, select a customer account.

4.  In the **Invoice lines** grid, in the **Description** field, enter a description for the invoice line.

5.  In the **Main account** field, select the ledger account that the amount is posted to.

6.  In the **Quantity** and **Unit price** fields, enter a quantity and a unit price.

7.  On the **Action Pane**, click **Header view**.

8.  In the **Delivery date** field, select a delivery date for the items or services.

9.  On the **Payment** tab, in the **Terms of payment** field, select the terms of payment for the invoice.

10. On the **Action Pane**, click **Post**, and then click **OK** to post the free text invoice.

## See also

[(ESP) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj916229\(v=ax.60\))

  


