---
title: (JPN) Set up a consolidated invoice for a customer
TOCTitle: (JPN) Set up a consolidated invoice for a customer
ms:assetid: a612d01c-12c4-4d62-be8d-0ed4bfe28fb1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711218(v=AX.60)
ms:contentKeyID: 49386529
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer
- Japan
- consolidate invoice
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up a consolidated invoice for a customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can consolidate multiple sales orders into one invoice, based on a consolidation date that you specify in the **Customers** form. For more information, see [(JPN) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj711060\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **General**, and then, on the **Customer** FastTab, select the **Consolidated invoice for customer** check box.

3.  Close the form.

4.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. In the **All customers** list, open a customer record.

5.  In the **Customers** form, on the **Action Pane**, click **Edit**.

6.  On the **Payment defaults** FastTab, in the **Consolidation day** field, enter a number from 1 to 31. This number represents the day of the month on which you want the invoices to be consolidated. If the last business day of the month falls on a day that is earlier than the day that you specify, the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has 30 days, the invoices are consolidated on the last business day of the current month.
    

    > [!NOTE]
    > <P>If you enter a consolidation date of 0 (zero), the customer’s invoices are not consolidated.</P>



## See also

[(JPN) Set up the terms of payment and the cutoff day for a customer](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-customer.md)

[(JPN) Mark sales invoices for consolidation and calculate due dates](jpn-mark-sales-invoices-for-consolidation-and-calculate-due-dates.md)

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[(JPN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664964\(v=ax.60\))

  


