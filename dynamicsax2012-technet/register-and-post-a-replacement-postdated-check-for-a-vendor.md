---
title: Register and post a replacement postdated check for a vendor
TOCTitle: Register and post a replacement postdated check for a vendor
ms:assetid: 72544658-da80-40fc-b192-12acaeded93b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242675(v=AX.60)
ms:contentKeyID: 36058122
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- register
- replacement
- postdated check
---

# Register and post a replacement postdated check for a vendor [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your original check to a vendor is lost or damaged, you can issue a replacement postdated check to the vendor. When you register the check details, provide a reference to the original check and indicate that the new check is a replacement for the original. You can also post the replacement check.

You must reverse the check transaction if the status of the original check is **Posted** or **Paid** in the **Postdated check status** field in the **Journal voucher** form:

  - **Posted** – Use the **Transaction reversal** form to reverse a posted transaction. For more information, see [Reverse a transaction](reverse-a-transaction.md).

  - **Paid** – Use the **Closed transaction editing in several currencies** form to reverse a paid transaction. For more information, see [Reverse settlements](reverse-settlements.md).

<!-- end list -->

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal.

3.  Click **Lines**, and then in the **Date** field, select the posting date for the replacement check.

4.  In the **Debit** field, enter the amount specified in the replacement check. The debit amount is updated in the **Amount** field on the **Postdated checks** tab.

5.  In the **Currency** field, select the currency used in the replacement check. The currency is updated in the **Currency** field on the **Postdated checks** tab.

6.  In the **Method of payment** field, select the method of payment for the postdated check.

7.  In the **Payment specification** field, select the payment specification.

8.  Click the **Postdated checks** tab, and then in the **Maturity date** field, enter the date when the replacement check is due for payment, in MM/DD/YYYY format.

9.  In the **Received date** field, enter the date when the replacement check was issued, in MM/DD/YYYY format.

10. In the **Check number** field, enter the replacement check number.

11. In the **Cashier** and **Salesperson** fields, select the identification codes of the cashier and the salesperson responsible for the check transaction.

12. In the **Issuing bank branch** and **Issuing bank name** fields, enter the bank details.

13. Select the check box, **Replacement check**, to indicate that the check is a replacement for an original check that is lost or damaged.

14. In the **Comments** field, enter the reasons for the replacement check.

15. In the **Original check** field, select the original postdated check details such as check number, maturity date, and vendor account.

16. Click **Post** \> **Post** to post the amount in the replacement check. You can post a postdated check if you select the **Post journal entries for postdated checks** check box in the **Cash and bank management parameters** form.

17. Close the forms to save your changes.

You can view the postdated checks in the **Vendor postdated checks** form. Click **Accounts payable** \> **Common** \> **Postdated checks** \> **Vendor postdated checks**.

## See also

[Set up postdated checks](set-up-postdated-checks.md)

[Register and post a postdated check for a vendor](register-and-post-a-postdated-check-for-a-vendor.md)

[Settle a postdated check for a vendor](settle-a-postdated-check-for-a-vendor.md)

[Vendor postdated checks (form)](https://technet.microsoft.com/en-us/library/hh242868\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

