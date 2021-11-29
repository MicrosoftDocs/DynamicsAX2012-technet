---
title: 'Scenario: Settle a vendor payment with an invoice'
TOCTitle: 'Scenario: Settle a vendor payment with an invoice'
ms:assetid: 8f050a69-6483-4b6e-be7e-034f328ccfcf
ms:mtpsurl: https://technet.microsoft.com/library/Hh597170(v=AX.60)
ms:contentKeyID: 39519230
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- invoices
- vendors
- invoice
- vendor payment
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a vendor payment with an invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This scenario illustrates two simple examples of a settlement in which one payment is settled with one or more invoices. For more information, see [Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md), [About parameters for settlements in Accounts payable](about-parameters-for-settlements-in-accounts-payable.md), and [Accounts payable parameters (form)](https://technet.microsoft.com/library/aa596348\(v=ax.60\)).

## Prerequisites

Fabrikam has purchased products from vendor 3064 two times and has received two invoices from the vendor. As of January 26, the vendor balance is 600.00.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice number</p></th>
<th><p>Invoice date</p></th>
<th><p>Invoice amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inv_10100</p></td>
<td><p>January 15</p></td>
<td><p>100.00</p></td>
</tr>
<tr class="even">
<td><p>Inv_10200</p></td>
<td><p>January 25</p></td>
<td><p>500.00</p></td>
</tr>
</tbody>
</table>


## Option 1: Pay an invoice based on the invoice amount

On February 1, April pays the vendor for invoice Inv\_10200. There is a question about Inv\_10100, so April does not want to pay that invoice yet. April enters the payment and settles the payment with invoice Inv\_10200 by following these steps.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines.

3.  In the **Account** field, select vendor 3064.

4.  Click **Functions** \> **Settlement**.

5.  In the **Settle open transactions** form, select the **Mark** check box on the line for invoice Inv\_10200. The remaining invoice amount, minus any available cash discount, is displayed in the **Amount to settle** field. No cash discounts are available for this invoice. Therefore, the amount is 500.00.

6.  Close the **Settle open transactions** form. The payment line that has information from the invoice is displayed in the **Journal voucher** form. The payment line contains the amount from the vendor invoice. This amount is the amount that the legal entity can pay to the vendor.
    

    > [!NOTE]
    > <P>In the <STRONG>Journal voucher</STRONG> form, click <STRONG>Inquiries</STRONG> &gt; <STRONG>Balance control</STRONG> to verify that the amount of the payment that is made to the vendor does not exceed the balance of the bank account.</P>



7.  Click **Functions** \> **Generate payments**.

8.  Select an export format, and then select the bank account from which the payment is drawn.

9.  In the **Generate payments** form, click **Dialog**, enter information in the fields, and then click **Document** to specify a printer destination.

10. Click **OK** to close the **Printer setup** form, and then click **OK** to close the dialog box.

11. In the **Generate payments** form, click **OK**.

12. Click **Validate** \>**Validate voucher only** to validate the payment line, and then click **Post** \> **Post and transfer**.

The balance for vendor 3064 is now 100.00. Invoice Inv\_10200 is fully settled. Therefore, the balance for that invoice is 0.00.

## Option 2: Pay a specified amount and settle an invoice

On February 1, April makes a payment of 500.00 to vendor 3064. April settles the payment with invoice Inv\_10100 and makes a partial payment on invoice Inv\_10200 by following these steps.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines.

3.  In the **Account** field, select vendor 3064.

4.  Select the description.

5.  In the **Debit** field, enter 500.00.

6.  Click **Functions** \> **Settlement**.

7.  In the **Settle open transactions** form, select the **Mark** check box on the lines for invoices Inv\_10100 and Inv\_10200.

8.  On the line for invoice Inv\_10100, in the **Amount to settle** field, accept the default value of 100.00.

9.  On the line for invoice Inv\_10200, in the **Amount to settle** field, change the default value of 500.00 to 400.00.

10. Close the **Settle open transactions** form.

11. In the **Journal voucher** form, click **Functions** \> **Generate payments**.

12. Select an export format, and then select the bank account from which the payment is drawn.

13. Click **Dialog**, enter information in the fields, and then click **Document** to specify the printer destination.

14. Click **OK** to close the **Printer setup** form, and then click **OK** to close the dialog box.

15. In the **Generate payments** form, click **OK**.

16. Click **Validate** \> **Validate voucher only** to validate the payment line, and then click **Post** \> **Post and transfer**.

The balance for vendor 3064 is now 100.00. Invoice Inv\_10100 is fully settled. Therefore, the balance for that invoice is 0.00. For invoice Inv\_10200, 400.00 is settled, and the remaining balance is 100.00.

## See also

[Scenario: Settle vendor payments by using payment proposals](scenario-settle-vendor-payments-by-using-payment-proposals.md)

[Scenario: Settle a partial vendor payment and settle the final payment in full before the discount date](scenario-settle-a-partial-vendor-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial vendor payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-vendor-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Use the "Date to use to calculate discounts" field to control discount calculations for vendor payments](scenario-use-the-date-to-use-to-calculate-discounts-field-to-control-discount-calculations-for-vendor-payments.md)

[Scenario: Settle a partial vendor payment that has multiple discount periods](scenario-settle-a-partial-vendor-payment-that-has-multiple-discount-periods.md)

[Scenario: Settle a partial vendor payment that has discounts on vendor credit notes](scenario-settle-a-partial-vendor-payment-that-has-discounts-on-vendor-credit-notes.md)

[Scenario: Take a discount that is more than the calculated discount for a vendor payment](scenario-take-a-discount-that-is-more-than-the-calculated-discount-for-a-vendor-payment.md)

  


