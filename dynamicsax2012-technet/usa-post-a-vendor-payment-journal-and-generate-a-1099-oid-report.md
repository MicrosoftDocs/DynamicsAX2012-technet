---
title: (USA) Post a vendor payment journal and generate a 1099 OID report
TOCTitle: (USA) Post a vendor payment journal and generate a 1099 OID report
ms:assetid: 63832dbc-c0d2-4ffe-ba89-fe2f8d4e24eb
ms:mtpsurl: https://technet.microsoft.com/library/Hh209202(v=AX.60)
ms:contentKeyID: 36057684
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- "1099"
- USA
- OID report
- vendor payment journal
audience: Application User
ms.search.region: USA
---

# (USA) Post a vendor payment journal and generate a 1099 OID report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Journal voucher** form to pay the vendors of debt instruments, such as bonds or other financial instruments, that have an original issue discount (OID). When the debt instrument reaches maturity, you can settle the payment with the vendor and generate the 1099 OID report.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. In the **Journal** form, click **Lines**.

2.  In the **Account** field, select the vendor account.

3.  In the **Debit** field, enter the amount to be paid to the vendor when the debt instrument matures or when the vendor makes an early withdrawal.

4.  In the **Offset account type** field, select the bank account type for the vendor payment.

5.  In the **Offset account** field, select the bank account number.

6.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

7.  Select the **Mark** check box to select each vendor invoice to be paid.

8.  Close the form to save your changes.

9.  Click **Validate** \> **Validate** to validate the journal.

10. Click **Post** \> **Post** to post the journal.

11. Close the forms to save your changes.

12. Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

13. Double-click a vendor line and then click **1099** \> **Vendor settlement for 1099's** to open the **Tax 1099 summary** form.

14. In the **From date** field, select the starting date for the 1099 OID report.

15. In the **To date** field, select the ending date for the report.

16. Click **Print** to print the vendor 1099 OID report.

## See also

[(USA) About year-end 1099 reporting](usa-about-year-end-1099-reporting.md)

[Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md)

[(USA) Vendor settlement for 1099s (form)](https://technet.microsoft.com/library/aa582697\(v=ax.60\))

  


