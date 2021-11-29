---
title: (JPN) Settle customer consolidated invoices by using a payment proposal
TOCTitle: (JPN) Settle customer consolidated invoices by using a payment proposal
ms:assetid: 121c408e-a706-4fa1-88cd-1754f8d70aae
ms:mtpsurl: https://technet.microsoft.com/library/JJ711007(v=AX.60)
ms:contentKeyID: 49386420
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Settle customer consolidated invoices by using a payment proposal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Customer payment proposal** form to settle open transactions that are related to consolidated invoices after you have received payment from a customer. A customer consolidated invoice may include an amount from a letter of credit. You cannot delete a consolidated invoice after it has been settled. For more information, see [(JPN) Customer payment proposal (modified form)](https://technet.microsoft.com/library/jj711015\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal, and then click **Lines**.

3.  In the **Journal voucher** form, on the menu, click **Payment proposal**, and then select **Create payment proposal**.

4.  In the **Customer payment proposal** form, select the criteria for the current payment. To select a specific customer account, click **Select**. In the **CustPaymProposal** form, select the customer account, and then click **OK**.

5.  The transactions that are based on the criteria that you specify are displayed in the **Customer payment proposal** form. In the **Consolidation ID** field, select the consolidation identification number for the most recent consolidated invoice.
    
    –or–
    
    In the **Consolidation day** field, enter the date when you want the invoices to be consolidated, by using a numeric value between 1 and 31. If the consolidation day is set to 0 (zero), the customer’s invoices are not consolidated. If the last day of the month falls on a date that is lower than the numeric value that you specify, the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has 30 days, the invoices are consolidated on the last business day of that month.
    

    > [!NOTE]
    > <P>The <STRONG>From date</STRONG> and <STRONG>To date</STRONG> fields are updated with appropriate dates when the consolidation day is set.</P>



6.  In the **Journal voucher** form, click **Payment proposal**, and then select **Edit payment proposal**.

7.  In the **Edit payment proposal** form, verify the payment proposal line, and then click **Transfer** to transfer the payment to the **Journal voucher** form.

8.  In the **Journal voucher** form, click **Functions**, and then click **Generate payments**.

9.  In the **Generate payments** form, enter the required details, and then click **OK**.

10. In the **Journal voucher** form, click **Validate**, and then select **Validate**. You must validate the journal before you can post it.

11. Click **Post**, and then select **Post**.

## See also

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[(JPN) Settle customer consolidated invoices by using a payment journal](jpn-settle-customer-consolidated-invoices-by-using-a-payment-journal.md)

[Customer payment proposal - Edit (form)](https://technet.microsoft.com/library/aa554074\(v=ax.60\))

[Export letter of credit/import collection (form)](https://technet.microsoft.com/library/hh208689\(v=ax.60\))

  


