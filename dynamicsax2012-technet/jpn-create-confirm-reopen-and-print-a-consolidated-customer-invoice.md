---
title: (JPN) Create, confirm, reopen, and print a consolidated customer invoice
TOCTitle: (JPN) Create, confirm, reopen, and print a consolidated customer invoice
ms:assetid: bbd359d6-2e03-4852-9811-6ad5f254e649
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664961(v=AX.60)
ms:contentKeyID: 49386545
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Create, confirm, reopen, and print a consolidated customer invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create consolidated invoices for customer transactions for which sales revenues, such as accounts receivable and cost of goods sold, are recorded on the shipping date. Invoices for these transactions are generally printed and sent to the customer on the shipping date. However, in some cases, multiple transactions within a period are merged into a single consolidated invoice for the period. You can include invoices that are associated with letters of credit in a consolidated invoice.

When you create a consolidated invoice for a customer, you select the customer’s sales orders to include in the consolidated invoice based on the posting dates of the sales orders. The actual consolidation date is the date on which the consolidated invoice is processed, and you cannot change this date. This date must be later than the date of the most recent consolidated invoice for that customer. For more information, see [(JPN) Mark sales invoices for consolidation and calculate due dates](jpn-mark-sales-invoices-for-consolidation-and-calculate-due-dates.md).

When you create a new consolidated invoice, the status is updated to **Unconfirmed**. Confirm the new consolidated invoice before you settle it. You should confirm any consolidated invoices for the customer for the previous period before you create new consolidated invoices. Confirm consolidated invoices in chronological order, but reopen the confirmations in reverse chronological order. You can also create and settle two or more consolidated invoices for a customer on the same day.


> [!NOTE]
> <P>Before you can consolidate customer invoices, you must set up the Accounts receivable parameters for consolidated invoices. For more information, see <A href="jpn-set-up-a-consolidated-invoice-for-a-customer.md">(JPN) Set up a consolidated invoice for a customer</A>.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Consolidated invoice**.

2.  On the **Action Pane**, in the **New** group, click **Consolidated invoice**.

3.  Enter selection criteria, and then click **OK**.
    
    The open sales orders that are marked for consolidation and the transactions that are not yet consolidated have a status of **Unconfirmed**.

4.  Do one of the following:
    
      - Select a consolidated invoice, and then, on the **Action Pane**, in the **Maintain** group, click **Confirm**. After confirmation, the sum of the consolidated invoices is displayed in the **Invoice amount during consolidation period** field. The status of the selected invoices is updated to **Confirmed**.
    
      - Select a confirmed consolidated invoice, and then click **Reopen**. After you reopen the invoice, the invoice’s status is updated to **Confirmed**.
    

    > [!NOTE]
    > <P>You can modify or delete a consolidated invoice only when the invoice has a status of <STRONG>Unconfirmed</STRONG>.</P>

    
    In the **Consolidated invoice** form, on the **General** FastTab, you can view the amounts for the consolidated invoice in the following fields:
    
      - **Previous invoice amount**
    
      - **Previously paid amount**
    
      - **Adjustment amount**
    
      - **Outstanding amount**
    
      - **Invoice amount during consolidation period**
    
      - **Total invoice amount**

5.  To generate the monthly consolidated invoice report, on the **Action Pane**, in the **Print** group, click **Consolidated invoice**.

## See also

[(JPN) Consolidated invoice (form)](https://technet.microsoft.com/en-us/library/jj711205\(v=ax.60\))

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

  


