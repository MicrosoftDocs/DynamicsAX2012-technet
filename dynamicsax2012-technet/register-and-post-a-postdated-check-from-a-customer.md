---
title: Register and post a postdated check from a customer
TOCTitle: Register and post a postdated check from a customer
ms:assetid: 539c21ed-e0ca-4a51-aac5-1ad4145efa6e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208953(v=AX.60)
ms:contentKeyID: 36057299
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- checks
- postdated checks
- post postdated checks for a customer
- register postdated checks for a customer
---

# Register and post a postdated check from a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can register details of a postdated check received from a customer using the **Journal voucher** form. You can also post the postdated check and generate financial transactions if you have selected the **Post journal entries for postdated checks** check box in the **Cash and bank management parameters** form.

Complete the following tasks before you register and post a postdated check received from a customer:

  - Set up postdated checks in the **Cash and bank management parameters** form.

  - Set up a method of payment for postdated checks in the **Methods of payment - customers** form.

<!-- end list -->

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal.

3.  Click **Lines**, and then in the **Date** field, select the posting date.

4.  In the **Credit** field, enter the amount specified in the postdated check. The credit amount is updated in the **Amount** field on the **Postdated checks** tab.

5.  In the **Method of payment** field, select the method of payment for the postdated check.

6.  In the **Payment specification** field, select the payment specification.

7.  In the **Currency** field, select the currency used in the postdated check. The currency is updated in the **Currency** field on the **Postdated checks** tab.

8.  Click the **Postdated checks** tab, and then in the **Maturity date** field, enter the date when the postdated check is due for payment, in MM/DD/YYYY format.

9.  In the **Received date** field, enter the date when the postdated check was received, in MM/DD/YYYY format.

10. In the **Check number** field, enter or modify the postdated check number.

11. In the **Cashier** and **Salesperson** fields, select the identification codes of the cashier and the salesperson responsible for the postdated check transaction.

12. In the **Issuing bank branch** and **Issuing bank name** fields, enter the bank details of the postdated check.

13. Click **Post** \> **Post** to post the amount in the postdated check. You can post a postdated check if you select the **Post journal entries for postdated checks** check box in the **Cash and bank management parameters** form.

14. Close the forms to save your changes.

You can view the posted postdated checks in the **Customer postdated checks** form. Click **Accounts receivable** \> **Common** \> **Postdated checks** \> **Customer postdated checks**.

## See also

[Set up postdated checks](set-up-postdated-checks.md)

[Register and post a replacement postdated check from a customer](register-and-post-a-replacement-postdated-check-from-a-customer.md)

[Settle a postdated check from a customer](settle-a-postdated-check-from-a-customer.md)

[Customer postdated checks (form)](https://technet.microsoft.com/en-us/library/hh227493\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

