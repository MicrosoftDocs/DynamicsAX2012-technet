---
title: Register and post a replacement postdated check from a customer
TOCTitle: Register and post a replacement postdated check from a customer
ms:assetid: 20f182b8-3fb4-47a9-96b3-3b4bc7e3ae5c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208470(v=AX.60)
ms:contentKeyID: 36056161
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- register
- post dated checks
- replacement
---

# Register and post a replacement postdated check from a customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a customer’s original check for payment is lost or damaged, you can accept a replacement postdated check and register the check details. When you register the check details, provide a reference to the original check and indicate that the new check is a replacement for the original. You can also post the replacement check.

You must reverse the check transaction if the status of the original check is **Posted** or **Paid** in the **Postdated check status** field in the **Journal voucher** form:

  - **Posted** – Use the **Transaction reversal** form to reverse a posted transaction. For more information, see [Reverse a transaction](reverse-a-transaction.md).

  - **Paid** – Use the **Closed transaction editing in several currencies** form to reverse a paid transaction. For more information, see [Reverse settlements](reverse-settlements.md).

<!-- end list -->

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal.

3.  Click **Lines**, and then in the **Date** field, select the posting date for the replacement check.

4.  In the **Credit** field, enter the amount specified in the replacement check. The credit amount is updated in the **Amount** field on the **Postdated checks** tab.

5.  In the **Currency** field, select the currency used in the replacement check. The currency is updated in the **Currency** field on the **Postdated checks** tab.

6.  In the **Method of payment** field, select the method of payment as postdated check.

7.  In the **Payment specification** field, select the payment specification.

8.  Click the **Postdated checks** tab. This tab is available only if you select the **Enable postdated checks** check box in the **General ledger parameters** form. For more information, see [General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\)).

9.  In the **Maturity date** field, enter the date when the replacement check is due for payment, in MM/DD/YYYY format.

10. In the **Received date** field, enter the date when the replacement check was received, in MM/DD/YYYY format.

11. In the **Check number** field, enter the replacement check number.

12. In the **Cashier** and **Salesperson** fields, select the identification codes of the cashier and the salesperson responsible for the check transaction.

13. In the **Issuing bank branch** and **Issuing bank name** fields, enter the bank details.

14. Select the check box, **Replacement check**, to indicate that the check is a replacement for an original check that was lost or damaged.

15. In the **Comments** field, enter the reasons for the replacement check.

16. In the **Original check** field, select the original postdated check details, such as check number, maturity date, and customer account.

17. Click **Post** \> **Post** to post the replacement check. This button is available only if you select the **Post journal entries for postdated checks** check box in the **General ledger parameters** form.

18. Close the form to save your changes.

You can view the posted postdated checks in the **Customer postdated checks** form. Click **Accounts receivable** \> **Common** \> **Postdated checks** \> **Customer postdated checks**.

## See also

[Set up postdated checks](set-up-postdated-checks.md)

[Register and post a postdated check from a customer](register-and-post-a-postdated-check-from-a-customer.md)

[Settle a postdated check from a customer](settle-a-postdated-check-from-a-customer.md)

[Customer postdated checks (form)](https://technet.microsoft.com/en-us/library/hh227493\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

