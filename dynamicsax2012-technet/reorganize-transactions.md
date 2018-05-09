---
title: Reorganize transactions
TOCTitle: Reorganize transactions
ms:assetid: 07d75286-c2ff-42c7-ad12-f91141d83fd3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569727(v=AX.60)
ms:contentKeyID: 36966679
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reorganize transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You or a customer might pay one invoice on multiple dates, or use multiple payment methods, such as a check and cash. In these situations, you can reorganize an invoice into several parts and assign a separate payment method to each part. After you reorganize the invoice, you can settle each new invoice line with a separate payment.

This information describes how to reorganize customer transactions that are in accounts receivable journals and vendor transactions that are in accounts payable journals.


> [!NOTE]
> <P>You can also reorganize transactions that are in the general journal and in payment journals.</P>



## Reorganize open customer transactions

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select an account.

3.  On the **Action Pane**, click the **Collect** tab, and then click **Settle open transactions**.

4.  On the **Overview** tab, select the **Mark** check box for an invoice.

5.  Click **Transaction reorganizing**.

6.  Select whether to reorganize the transaction by percentage or amount.

7.  On the **Overview** tab, create a line for each new due date. For each due date, enter the percentage or amount of the original transaction that is due on that date.
    
    To reorganize the original transaction by method of payment, enter the same due date for each line. You will select the method of payment in step 11.
    

    > [!TIP]
    > <P>Alternatively, you can reorganize the due dates by using a payment schedule. Click <STRONG>Payment schedule</STRONG>, and then select a payment schedule and a starting date. The starting date is the due date for the first invoice. Click <STRONG>OK</STRONG>. The <STRONG>Payment schedule</STRONG> configuration key must be selected if you want to reorganize transactions according to a payment schedule.</P>



8.  Verify that the percentage or amount that is shown in the **Remainder** field is 0 (zero).

9.  Click **Accept** to transfer the reorganized transactions to the **Settle open transactions** form.

10. Select a new transaction.

11. Click the **Payment** tab, and then select a method of payment and a payment specification.

12. Repeat steps 10 and 11 for each remaining new transaction.

## Reorganize open vendor transactions

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select an account.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Settle open transactions**.

4.  On the **Overview** tab, select the **Mark** check box for an invoice.

5.  Click **Transaction reorganizing**.

6.  Select whether to reorganize the transaction by percentage or amount.

7.  On the **Overview** tab, create a line for each new due date. For each due date, enter the percentage or amount of the original transaction that is due on that date.
    
    To reorganize the original transaction by method of payment, enter the same due date for each line. You will select the method of payment in step 11.
    

    > [!TIP]
    > <P>Alternatively, you can reorganize the due dates by using a payment schedule. Click <STRONG>Payment schedule</STRONG>, and then select a payment schedule and a starting date. The starting date is the due date for the first invoice. Click <STRONG>OK</STRONG>. The <STRONG>Payment schedule</STRONG> configuration key must be selected if you want to reorganize transactions according to a payment schedule.</P>



8.  Verify that the percentage or amount that is shown in the **Remainder** field is 0 (zero).

9.  Click **Accept** to transfer the reorganized transactions to the **Settle open transactions** form.

10. Select a new transaction.

11. Click the **Payment** tab, and then select a method of payment and a payment specification.

12. Repeat steps 10 and 11 for each remaining new transaction.

## See also

[Settle transactions with payments](settle-transactions-with-payments.md)

[Settle open transactions - customer (form)](https://technet.microsoft.com/en-us/library/aa558602\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

