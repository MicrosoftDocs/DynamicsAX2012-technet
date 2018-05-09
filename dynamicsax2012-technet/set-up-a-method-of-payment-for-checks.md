---
title: Set up a method of payment for checks
TOCTitle: Set up a method of payment for checks
ms:assetid: 193c74e0-ea2e-434a-b1bc-0be2efbce875
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569914(v=AX.60)
ms:contentKeyID: 36056110
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bank checks
- method of payments
- methods of payment
---

# Set up a method of payment for checks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Follow these steps to set up methods of payments for checks.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** to create a line.

3.  In the **Method of payment** field, enter an identifier, such as Check.

4.  In the **Period** field, select the period for which invoices in automatic payment proposals are combined:
    
      - **Invoice** – One payment transfer is created for each invoice.
    
      - **Date** – All invoices for a vendor or customer that have the same due date are combined.
    
      - **Week** – All invoices for a vendor or customer that have a due date in the same week are combined.
    
      - **Total** – All invoices for a vendor or customer are combined into one payment.

5.  In the **Description** field, enter a name or short description for the method of payment.

6.  In the **Grace period** field, if applicable, enter the number of days after the specified period when the vendor or customer is eligible for a cash discount.

7.  In the **Payment status** field, select the payment status that must be fulfilled to post a payment that is assigned this method of payment. For a method that uses checks, the status is often **Received** or **Sent**.

8.  Click the **File formats** FastTab. In the **Export format** field, select the export format for this method of payment.

9.  Click **Close** to close the form and save the changes.

## See also

[Make a payment by check](make-a-payment-by-check.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

