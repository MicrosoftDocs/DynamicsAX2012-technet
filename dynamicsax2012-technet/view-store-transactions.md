---
title: View store transactions
TOCTitle: View store transactions
ms:assetid: c92384eb-0a33-4b89-835a-8510c89a0c72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597242(v=AX.60)
ms:contentKeyID: 39519319
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- store transaction
- store transactions
---

# View store transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to view the transactions that have been completed in stores. You can view a list of transactions for all statements for retail stores or for a specific statement. The statement posting process is used to account for the transactions that occur in Microsoft Dynamics AX for Retail POS. The statement posting process uses Retail Scheduler to transmit a set of the point-of-sale (POS) transactions to the Microsoft Dynamics AX client so that you can view them in this form.

In Microsoft Dynamics AX 2012 R2, you can also view a list of transactions for all statements for online stores. In AX 2012 R3, you can view details about transactions that have discounts applied to them.

The following types of transaction are included in the list:

  - Logon

  - Logoff

  - Sales

  - Payment

  - Remove tender

  - Float entry

  - Change tender

  - Tender declarations

  - Voided

  - Open drawer

  - Negative adjustment

  - End of day

  - End of shift

  - Sales order

  - Sales invoice

## View transactions

There are three ways to view retail transactions, depending on which kind of transaction you want to view. You can view transactions from retail stores, online stores, and posted statements. Depending on how you want to view transactions, do one of the following:

  - To view the transactions for all statements for retail stores: Click **Retail** \> **Inquiries** \> **Retail store transactions**. Transactions are listed in the left pane in the **Retail store transactions** form.

  - In Microsoft Dynamics AX 2012 R2, to view the transactions for all statements for online stores: Click **Retail** \> **Inquiries** \> **Online store transactions**. Transactions are listed in the left pane in the **Online store transactions** form.

  - To view the transaction for a specific statement: Click **Retail** \> **Inquiries** \> **Posted statements**. In the **Statement journal** form, click **Inquiries**, and then click **Transactions**. Transactions are listed in the left pane in the **Transactions** form.

## Add or remove filters for query results

Depending on your version of the product, do one of the following:

  - In Microsoft Dynamics AX 2012 R2: In the transactions form, click in the left pane, and then press CTRL+G to set the filter parameters and filter the transactions in the list.

  - Otherwise, in the transactions form, click the filter buttons on the toolbar. To view only posted transactions or unposted transactions, use the filter in the **Entry status** column.

## View discount transactions in AX 2012 R3

To view details about transactions that have discounts applied to them, follow these steps:

1.  Do one of the following:
    
      - Click **Retail** \> **Inquiries** \> **Retail store transactions**. In the **Retail store transactions** form, click **Transactions**, and then click **Discount transactions**.
    
    –or–
    
      - Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. In the **All sales orders** list, select a sales order, and then, on the **Action Pane**, on the **Retail** tab, click **Sales transactions**. In the **Transactions** form, click **Transactions**, and then click **Discount transactions**.

2.  In the **Discount transactions** form, select a transaction, and then click **Retail transactions** to view details about the transaction.

3.  Select a transaction, and then click the **Discount** tab to view information about the transaction’s discount.

4.  Click **Discount** to view the original retail discount.

## See also

[View inquiries and reports overview](view-inquiries-and-reports-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

