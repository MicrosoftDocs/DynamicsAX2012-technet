---
title: Set up postdated checks
TOCTitle: Set up postdated checks
ms:assetid: 755e7cdc-9c15-403a-b565-af8552de0778
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209238(v=AX.60)
ms:contentKeyID: 36058169
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Malaysia
- Thailand
- checks
- postdated checks
- Saudi Arabia
---

# Set up postdated checks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to specify whether to post journal entries for postdated checks and which posting journals to use for clearing entries and vendor payments. You can also specify clearing accounts for issued checks, received checks, and withholding tax. Postdated checks are checks that are issued to make and receive payments on a future date. You can specify whether the check must be reflected in the accounting books before its maturity date. Before you set up postdated checks, make sure that the **Postdated checks** configuration key is selected in the **Configuration** form.

Complete the following tasks before you use postdated checks:

  - Set up postdated checks parameters.

  - Set up a method of payment for postdated checks.

## Set up postdated checks parameters

Use the **Cash and bank management parameters** form to set up postdated checks. For more information, see [Cash and bank management parameters (form)](https://technet.microsoft.com/en-us/library/aa591289\(v=ax.60\)).

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Click the **Postdated checks** link.

3.  Select the **Enable postdated checks** check box.

4.  Select the **Post journal entries for postdated checks** check box to post the financial transactions to clearing accounts for vendors and customers. This field is available only if you select the **Enable postdated checks** check box.

5.  In the **Clearing account for issued checks** field, select a clearing account for checks issued to vendors. This field is available only if you select the **Post journal entries for postdated checks** check box.
    
    A clearing account is a temporary account that contains the amounts in the postdated checks.

6.  In the **Clearing account for received checks** field, select a clearing account for checks that are received from customers. This field is available only if you select the **Post journal entries for postdated checks** check box.

7.  In the **General journal for clearing entries** field, select the journal to use to settle postdated check transactions. This field is available only if you select the **Post journal entries for postdated checks** check box.

8.  In the **Transfer postdated checks to this vendor payment journal** field, select the vendor payment journal that the postdated check transactions are transferred to.

9.  In the **Withholding tax clearing account** field, select a clearing account that the withholding tax for vendors is posted to.

## Set up a method of payment for postdated checks

Use the **Methods of payment - vendors** and **Methods of payment - customers** forms to set up a method of payment for postdated checks. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)) and [Methods of payment - customers (form)](https://technet.microsoft.com/en-us/library/aa499398\(v=ax.60\)).

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.
    
    \-or-
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  In the **Method of payment** field, enter the method of payment for a customer or a vendor. For more information, see [Set up a method of payment for checks](set-up-a-method-of-payment-for-checks.md).

3.  In the **Account type** field, select **Bank**.

4.  In the **Payment account** field, select the bank account that is used to deduct the invoice amount.

5.  Select the **Postdated check clearing posting** check box to indicate that the check amount is posted to a clearing account. (Select the clearing account in the **Clearing account for issued checks** or **Clearing account for received checks** field in the **Cash and bank management parameters** form.) The **Bridging posting** check box is selected.
    
    A bridging account or a clearing account is a temporary account that is used to post a transaction until the transaction is reconciled.

## See also

[Register and post a postdated check from a customer](register-and-post-a-postdated-check-from-a-customer.md)

[Register and post a postdated check for a vendor](register-and-post-a-postdated-check-for-a-vendor.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

