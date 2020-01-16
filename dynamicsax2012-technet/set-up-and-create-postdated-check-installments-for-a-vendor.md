---
title: Set up and create postdated check installments for a vendor
TOCTitle: Set up and create postdated check installments for a vendor
ms:assetid: 17953331-c42a-442d-beab-831f2a1e42c6
ms:mtpsurl: https://technet.microsoft.com/library/Hh242151(v=AX.60)
ms:contentKeyID: 36056085
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- check
- postdated
- checks
audience: Application User
ms.search.region: Global
---

# Set up and create postdated check installments for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can pay a vendor in multiple installments using postdated checks. Set up an installment schedule for the payment and divide the total invoice amount into installments. You can use postdated check installments to pay a payment journal line or an open invoice. However, you can set up only one installment schedule for the invoice amount or the journal amount. The amount of each check is calculated based on the number of installments, the number of checks, and the time period for payment. Withholding tax is deducted from the invoice amount.

## Set up and create postdated check installments in a payment journal line

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Create a new vendor payment line.

5.  In the **Debit** field, enter the debit amount.

6.  In the **Method of payment** field, select the method of payment for the postdated check.

7.  Click the **Postdated checks** tab to register a postdated check. For more information, see [Register and post a postdated check for a vendor](register-and-post-a-postdated-check-for-a-vendor.md).

8.  Click **Functions** \> **Create postdated check installments**.

9.  In the **Number of installments** field, enter the number of installments to be created for the payment journal line.

10. In the **Period interval** field, select the interval for the installments as **Days**, **Months**, or **Years**.

11. In the **Number of units** field, enter the number of units for the checks.

12. Click **OK** to create postdated checks to pay the vendor in installments.

13. Close the forms to save your changes.

## Set up and create postdated check installments in an open invoice

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Select a vendor payment line, and then in the **Account** field, select the vendor account.

5.  In the **Method of payment** field, select the method of payment for the postdated check.

6.  Click **Functions** \> **Settlement**.

7.  In the **Settle open transactions** form, select the **Mark** check box to select an open invoice. The amount to be settled is updated in the **Debit** field in the **Journal voucher** form.

8.  Close the form to save your changes.

9.  Click **Functions** \> **Create postdated check installments**.

10. In the **Number of installments** field, enter the number of installments to be created for the open invoice.

11. In the **Period interval** field, select the unit for the installments as **Days**, **Months**, or **Years**.

12. In the **Number of units** field, enter the number of units for the checks.

13. Click **OK** to create postdated checks to pay the vendor in installments.

14. Close the forms to save your changes.

  


