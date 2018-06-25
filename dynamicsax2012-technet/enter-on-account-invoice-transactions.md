---
title: Enter on-account invoice transactions
TOCTitle: Enter on-account invoice transactions
ms:assetid: c0ac38ea-e927-4f01-81ef-078d358fc77a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550672(v=AX.60)
ms:contentKeyID: 36966738
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- on-account
- invoice setup
- offset transaction
---

# Enter on-account invoice transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to enter on-account invoice transactions for projects. Use an on-account invoice to bill a customer for some or all of the contract value of a project. The amount that you enter in an on-account invoice for a project is based on the timing, percentage of completion, and other conditions that are specified in the project contract. The amount in an on-account invoice is not calculated based on the hours, items, or other transactions that are posted to a project.

The information that you enter in the form depends on the project type that you are using:

  - For Fixed-price projects, on-account transactions are based on an agreed-upon milestone billing schedule, and one line is created for each payment that is to be received from the project customer. No deductions are needed.

  - For Time and material projects, on-account transactions are entered as one line. Optionally, you can enter additional lines as deductions to offset any prepayments that have been made. You can create deduction lines by entering an amount preceded by a minus sign. The sum of the deductions and the on-account transactions should correspond to the original on-account amount.

To enter on-account invoice transactions, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Select or open the project or project contract that you want to work with.

3.  On the **Action Pane**, on the **Manage** or **Maintain** tab, in the **Bill** group, click **On-account transactions**.

4.  In the **On-account** form, click **New**, and then enter the on-account amount or deduction on the new line.

In Microsoft Dynamics AX 2012 R3, you can create on-account transaction invoices automatically based on billing rules. Billing rules are based on the terms and conditions in project contracts. When you are ready to invoice a project customer, the amount to invoice for the project is calculated based on the billing rules. For more information, see [About billing rules](about-billing-rules.md).

## See also

[Create an invoice for on-account transactions](create-an-invoice-for-on-account-transactions.md)

[Create invoice proposals for projects with and without billing rules](create-invoice-proposals-for-projects-with-and-without-billing-rules.md)

[On-account transactions (form)](https://technet.microsoft.com/en-us/library/aa557380\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

