---
title: (JPN) Settle customer consolidated invoices by using a payment journal
TOCTitle: (JPN) Settle customer consolidated invoices by using a payment journal
ms:assetid: 87e4ae3b-2c12-4b50-92d8-db202198b29e
ms:mtpsurl: https://technet.microsoft.com/library/JJ711085(v=AX.60)
ms:contentKeyID: 49386495
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Settle customer consolidated invoices by using a payment journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Settle open transactions** form to settle open transactions that are related to consolidated invoices after you have received payment from a customer. A customer consolidated invoice may include an amount from a letter of credit. You cannot delete a consolidated invoice after it has been settled. For more information, see [Settle open transactions - customer (form)](https://technet.microsoft.com/library/aa558602\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines**.

3.  In the **Journal voucher** form, create a journal line.

4.  On the menu, click **Functions**, and then select **Settlement**.

5.  In the **Settle open transactions** form, click **Consolidated invoice**, and then click **Select**.

6.  In the **Select transactions** form, in the **Consolidation ID** field, select the consolidation identification number for the most recent consolidated invoice.
    
    –or–
    
    In the **Consolidation day** field, enter the date when you want the invoices to be consolidated, by using a numeric value between 1 and 31. If the consolidation day is set to 0 (zero), the customer’s invoices are not consolidated. If the last day of the month falls on a date that is less than the numeric value that you have specified, the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has 30 days, the invoices are consolidated on the last business day of that month.
    

    > [!NOTE]
    > <P>The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are updated with appropriate dates when the consolidation day is set.</P>



7.  Click **OK**.

8.  The consolidated invoice transactions are displayed in the **Settle open transactions** form. Click **Consolidated invoice**, and then select the **Mark all** check box to settle all of the invoices.

9.  In the **Journal voucher** form, click **Validate**, and then select **Validate**. You must validate the journal before you can post it.

10. Click **Post**, and then select **Post** to post the payment voucher and settle the transactions. You can settle the transactions in full or in part, based on the customer payment amount. If the payment amount is larger than the total transaction amount, the payment remains open, and the amount that has been overpaid is reimbursed.
    
    After the transactions have been fully or partially settled, the **Status** field in the **Consolidated invoice** form reflects the **Settled** or **Partially settled** status.

## See also

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[(JPN) Set up a consolidated invoice for a customer](jpn-set-up-a-consolidated-invoice-for-a-customer.md)

[(JPN) Set up the terms of payment and the cutoff day for a customer](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-customer.md)

[(JPN) Mark sales invoices for consolidation and calculate due dates](jpn-mark-sales-invoices-for-consolidation-and-calculate-due-dates.md)

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

[(JPN) Customers (modified form)](https://technet.microsoft.com/library/jj711060\(v=ax.60\))

[Export letter of credit/import collection (form)](https://technet.microsoft.com/library/hh208689\(v=ax.60\))

  


