---
title: Register and post a postdated check for a vendor
TOCTitle: Register and post a postdated check for a vendor
ms:assetid: dd15a592-2f31-4ba3-a372-d3a414a5e99b
ms:mtpsurl: https://technet.microsoft.com/library/Hh227408(v=AX.60)
ms:contentKeyID: 36059679
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- checks
- postdated checks
- Post a postdated check
- Register a postdated check
audience: Application User
ms.search.region: Global
---

# Register and post a postdated check for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Journal voucher** form to register the details of a postdated check before you issue the check to a vendor. You can post the postdated check and generate financial transactions after you select the **Post journal entries for postdated checks** check box in the **Cash and bank management parameters** form.

You must complete the following tasks to register and post a postdated check issued to a vendor:

  - Set up postdated checks in the **Cash and bank management parameters** form.

  - Set up a method of payment for postdated checks in the **Methods of payment - vendors** form.

<!-- end list -->

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new payment journal.

3.  Click **Lines**, and then in the **Date** field, select the posting date.

4.  In the **Debit** field, enter the amount specified in the check. The amount is updated in the **Amount** field on the **Postdated checks** tab.

5.  In the **Method of payment** field, select the method of payment for the postdated check.

6.  In the **Payment specification** field, select the payment specification.

7.  In the **Currency** field, select the currency. The currency is updated in the **Currency** field on the **Postdated checks** tab.

8.  Click the **Postdated checks** tab, and then in the **Maturity date** field, enter the date when the postdated check is due for payment, in MM/DD/YYYY format.

9.  In the **Received date** field, enter the date when the postdated check was issued, in MM/DD/YYYY format.

10. In the **Check number** field, enter or modify the number of the postdated check.

11. In the **Cashier** and **Salesperson** fields, select the identification codes of the cashier and the salesperson responsible for the postdated check transaction.

12. In the **Issuing bank branch** and **Issuing bank name** fields, enter the bank details.

13. Click **Post** \> **Post** to post the amount in the postdated check.

14. Close the forms to save your changes.

You can view the posted postdated checks in the **Vendor postdated checks** form. Click **Accounts payable** \> **Common** \> **Postdated checks** \> **Vendor postdated checks**.

## See also

[Set up postdated checks](set-up-postdated-checks.md)

[Register and post a replacement postdated check for a vendor](register-and-post-a-replacement-postdated-check-for-a-vendor.md)

[Settle a postdated check for a vendor](settle-a-postdated-check-for-a-vendor.md)

[Vendor postdated checks (form)](https://technet.microsoft.com/library/hh242868\(v=ax.60\))

  


