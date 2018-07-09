---
title: Generate and print vendor checks
TOCTitle: Generate and print vendor checks
ms:assetid: 937d3843-755e-408c-b700-38cd437f46d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232194(v=AX.60)
ms:contentKeyID: 36966735
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Generate and print vendor checks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to generate and print checks, and if your bank requires it, how to generate positive pay files and recall positive pay files.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Generate and print checks

Use this procedure to generate and print checks for vendors. This procedure assumes that you have already selected invoices to pay and settled them. For more information, see [Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md).

Checks are printed by using the remit-to address that is specified for each vendor. If a remit-to address is not specified, the vendor’s primary address is used.

To generate and print checks, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**.

4.  In the **Generate payments** form, select **Export format**, and then select the **Check** export file format from the list.
    

    > [!NOTE]
    > <P>Alternatively, select <STRONG>Payment method</STRONG>. In the <STRONG>Method of payment</STRONG> field, select a method of payment that uses the <STRONG>Check</STRONG> export file format.</P>



5.  Click **Select**, select the vendors to print checks for, and then click **OK**.

6.  Click **Dialog**.

7.  In the **Payment by check** form, enter the starting check number and the number of checks to print, and then select whether to print a payment advice report.

8.  Click **Document**, specify printer information for the checks, and then click **OK**.

9.  If you are printing a payment advice report, click **Payment advice**, specify printer information for the report, and then click **OK**.

10. In the **Payment by check** form, click **OK**.

11. In the **Generate payments** form, click **OK** to create the checks.

## Generate a positive pay file for a bank account

If your bank requires it, you can generate an electronic list of checks that is provided to the bank. Use this procedure to generate a positive pay file for a single bank account. To generate a positive pay file for multiple bank accounts or multiple legal entities, see [Create a positive pay file for multiple legal entities and bank accounts](create-a-positive-pay-file-for-multiple-legal-entities-and-bank-accounts.md).

This procedure applies only if cumulative update 6 for Microsoft Dynamics AX 2012 R2 is installed.

To generate a positive pay file for a bank account, follow these steps:

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Double-click a bank account.

3.  On the **Action Pane**, click **Edit**, and then click the **Manage payments** tab.

4.  Click **Positive pay file**.

5.  In the **Cut-off date** field, enter the last check date to include in the positive pay file. All checks that haven’t been included in a positive pay file through this check date are included in the file.

6.  Click **OK**.

## Recall a positive pay file

If you have to make a change to a positive pay file, you can recall it. Recalling a positive pay file resets the field for each check that indicates whether the check has been included in a positive pay file. Then, you can include the check in a new positive pay file.

This procedure applies only if cumulative update 6 for Microsoft Dynamics AX 2012 R2 is installed.

To recall a positive pay file, follow these steps:

1.  Click **Cash and bank management** \> **Inquiries** \> **Positive pay file summary**.

2.  Select a positive pay file that has a status of **Created**.

3.  Click **Recall**.

## See also

[Vendor payment by check (form)](https://technet.microsoft.com/en-us/library/bb220751\(v=ax.60\))

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

[Reimburse customers](reimburse-customers.md)

[Create a positive pay file for multiple legal entities and bank accounts](create-a-positive-pay-file-for-multiple-legal-entities-and-bank-accounts.md)

[Issue worker payments](issue-worker-payments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

