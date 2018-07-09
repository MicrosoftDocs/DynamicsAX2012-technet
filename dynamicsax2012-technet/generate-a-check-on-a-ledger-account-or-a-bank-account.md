---
title: Generate a check on a ledger account or a bank account
TOCTitle: Generate a check on a ledger account or a bank account
ms:assetid: 96a46db3-d914-4a12-ba5a-ac757f99be47
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498426(v=AX.60)
ms:contentKeyID: 36058638
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Generate a check on a ledger account or a bank account [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create checks and post the amounts to the ledger accounts without posting the amount to a vendor account first. This is useful when printing checks in the following situations:

  - Cash on delivery (COD) items are delivered and there is no current invoice for the item, or the supplier has not been set up in the system as a vendor. You would create a check when the items are delivered.

  - Payments to one-time vendors.

  - Payments to vendors who do not accept credit cards.

  - Payments from one bank account to another, such as funds transfers or bank loan payments.

<!-- end list -->

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Select the **Allow checks for bank or ledger accounts** check box and then close the form.

3.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

4.  Press CTRL+N and select a journal name.

5.  Click **Lines** and create a line.

6.  In the **Account type** field on the **General** tab, select **Ledger** or **Bank**, and then select the account in the **Account** field.

7.  If you selected **Ledger** in the **Account type** field, enter information in the **Recipient name** field on the **Payment** tab.

8.  When you have finished entering information for the line, click **Functions** \> **Generate payments** to process the check.

## See also

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

