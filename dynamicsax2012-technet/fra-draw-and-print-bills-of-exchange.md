---
title: (FRA) Draw and print bills of exchange
TOCTitle: (FRA) Draw and print bills of exchange
ms:assetid: 5c06df45-d2ca-4740-b8a6-74e14869d44b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242502(v=AX.60)
ms:contentKeyID: 36057566
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# (FRA) Draw and print bills of exchange [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can draw and print bills of exchange, you must perform the following setup tasks:

  - Set up a method of payment for bills of exchange by selecting **French bill of exchange** in the **Export format** field and **French bill of exchange remittance** in the **Remittance format** field in the **Methods of payment - customers** form. For more information, see [Set up bills of exchange](set-up-bills-of-exchange.md) and [Methods of payment - customers (form)](https://technet.microsoft.com/en-us/library/aa499398\(v=ax.60\)).

  - Set up a bank account for a customer. For more information, see [Set up a bank account for a customer account](set-up-a-bank-account-for-a-customer-account.md).

  - Set up a customer address that has a purpose of **Payment** to use for bills of exchange. For more information, see [Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\)) and [Manage addresses (form)](https://technet.microsoft.com/en-us/library/hh370713\(v=ax.60\)).

Use this procedure to draw and print bills of exchange.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Draw bill of exchange journal**.

2.  Select a journal that contains posted transactions, and then click **Lines**. You can draw a bill of exchange only when invoices for a payment are settled.

3.  Click **Functions** \> **Generate payments**.

4.  In the **Payment method** field, select a method of payment that uses the **French bill of exchange** format, and then click **Dialog** to open the **French bill of exchange** form.

5.  In the **City** field, enter the customer’s city, and then click **OK**. The city is printed on the French bill of exchange draft.

6.  In the **Generate payments** form, click **OK**. The bills of exchange are displayed. Verify that they are correct, and then print them.

Depending on the method of payment that you selected for each journal line, one or more French bill of exchange remittance files are generated automatically. If the draft type for a journal line is **Bill with acceptance**, the status of that journal line must be **Approved** before a bill of exchange remittance file can be generated for that line.

## See also

[Generate payments - customer (class form)](https://technet.microsoft.com/en-us/library/aa554105\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

