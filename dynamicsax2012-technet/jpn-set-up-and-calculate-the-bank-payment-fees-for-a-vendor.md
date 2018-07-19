---
title: (JPN) Set up and calculate the bank payment fees for a vendor
TOCTitle: (JPN) Set up and calculate the bank payment fees for a vendor
ms:assetid: a1c51150-2032-4083-877f-30b30ae02ea0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn313058(v=AX.60)
ms:contentKeyID: 54936304
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.VendPaymFee
- Forms.VendPaymModeFee
- Forms.LedgerJournalTransVendPaym
- Forms.LedgerJournalTable
- Forms.VendTable
- Forms.PaymFeeBankRule_JP
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up and calculate the bank payment fees for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012_

When a company makes a payment to a vendor, the bank payment fees can be paid by the company or by the vendor. You can set up Microsoft Dynamics AX so that each time the company pays the vendor, the bank payment fees are automatically deducted from the payment. Follow the steps in this topic to set up and calculate the bank payment fees for a vendor.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up bank groups. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj664976(v=ax.60)">(JPN) Bank groups (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Ensure that you have set up bank codes and branch codes. For more information, see <a href="jpn-set-up-bank-codes-and-branch-codes-for-a-bank-group.md">(JPN) Set up bank codes and branch codes for a bank group</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Indicate that the vendor pays the bank payment fees

Use the **Vendors** form to set up a vendor account so that the vendor pays the bank payment fees. When the vendor pays the bank payment fees, the bank payment fee amount is automatically deducted from the amount that is paid to the vendor.

To set up a vendor account so that the vendor pays the bank payment fees, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account or create a vendor account. For more information, see [Create a vendor account](create-a-vendor-account.md) and [(JPN) Vendors (modified form)](https://technet.microsoft.com/en-us/library/jj711083\(v=ax.60\)).

3.  On the **Payment** FastTab, select the **Vendor pays payment fee** check box.
    

    > [!NOTE]
    > <P>If you do not select the <STRONG>Vendor pays payment fee</STRONG> check box, the bank payment fees are paid by the company.</P>



## 2\. Create a rule to calculate bank payment fees

Use the **Bank rules for payment fee** form to create a payment rule to be used to calculate bank payment fees that are deducted from the payment that the company makes to the vendor.

To create a bank rule, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Bank rules for payment fee**.

2.  Press Ctrl+N or click **New** to create a bank rule.

3.  In the **ID** field, type a short descriptor that identifies the bank rule. You select this descriptor when you set up the payment fee in the **Payment fee setup** form.

4.  In the **Name** field, type a description for the bank rule.

5.  On the **General** FastTab, add one or more of the following filters to create the bank rule.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Third party bank group</strong></p></td>
    <td><p>Select a filter value for the third-party bank group that is used in the bank rule. For example, you can select the bank code or the branch code for the third-party group.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Relationship</strong></p></td>
    <td><p>Select the operator that indicates the relationship between the third-party bank group and the company bank group.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Value</strong></p></td>
    <td><p>Assign a filter to compare the value in the <strong>Value</strong> field against the value that is selected in the <strong>Third party bank group</strong> field when calculating the bank payment fees. For example, to create a bank rule that applies to a particular bank that has a bank code of 001, select <strong>Bank code</strong> in the <strong>Third party bank group</strong> field, select <strong>=</strong> in the <strong>Relationship</strong> field, and then enter 001 in the <strong>Value</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Company bank group</strong></p></td>
    <td><p>Select a filter value for the company bank group that is used in the bank rule. For example, to apply this rule when your bank and the vendor bank are different, select <strong>Bank code</strong> in the <strong>Third party bank group</strong> and <strong>Company bank group</strong> fields, and then select <strong>&lt;&gt;</strong> in the <strong>Relationship</strong> field.</p></td>
    </tr>
    </tbody>
    </table>


## 3\. Set up a payment fee

After creating the bank rule, use the bank rule to set up a payment fee in the **Payment fee** form. The payment fee amounts are set up for banks, methods of payment, payment specifications, calculation methods, and consumption tax.

To set up a payment fee, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Create a payment fee record. For more information see [Vendor payment fee (form)](https://technet.microsoft.com/en-us/library/aa573151\(v=ax.60\)).

3.  In the **Account** field, select the ledger account that is used to post the bank payment fee that is paid by the company.

4.  In the **Payment fee account** field, update the ledger account that is used to post the bank payment fee that is paid by a vendor.

5.  Click **Payment fee setup** to open the **Payment fee setup** form, where you can set up banks, methods of payment, payment specifications, calculation methods, and consumption tax. For more information, see [Vendor payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa598976\(v=ax.60\)).

6.  On the **Overview** tab, in the **Bank rule ID for payment fee** field, select the identification code for the bank rule to apply to the bank payment fee.

7.  On the **General** tab, in the **Fee** field group, in the **Percentage/Amount** field, select **Amount**.

8.  In the **Fee amount** field, enter the bank payment fee amount.

9.  In the **Currency** field, enter the currency code for the fee amount.

10. In the **Method of payment** field, specify the payment method for managing electronic payments.

11. In the **Administration** field group, in the **Currency** field, enter the currency for the payment.

12. On the **General** tab, in the **Minimum** field, enter the minimum transaction amount on which the bank payment fee is calculated.

13. In the **Maximum** field, enter the maximum transaction amount on which the bank payment fee is calculated.

14. Specify other details, if required.

## 4\. Create and post a payment journal for the vendor who pays the bank payment fees

Use the **Payment journal** form to create and post a payment for the vendor who pays the bank payment fees.

To create a payment journal, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal, and then create a payment journal line for the payment amount to pay to the vendor. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md) and [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)).

3.  In the **Offset account** field, enter the offset account for the transaction.

4.  In the **Method of payment** field, select a method of payment.

5.  On the **Bank** tab, in the **Account identification** field, enter the vendor bank account. On the **Payment fee** tab, the bank fee amount is automatically calculated based on the values in the **Method of payment**, **Offset account**, and **Account identification** fields.
    

    > [!NOTE]
    > <P>The <STRONG>Vendor pays payment fee</STRONG> check box is selected for the vendor. A selected check box indicates that the bank payment fees are paid by the vendor.</P>



6.  On the **Bank** tab, in the **Account identification** field, select a different vendor bank account, if required. The bank fee is recalculated based on the payment fee amount for the new vendor bank account.

7.  Click **Inquiries** \> **Payment fee summary** to open the **Vendor payment fee** form, where you can view a summary of the payment amount. You can also view the total payment amount and the bank payment fee amount for each voucher.
    

    > [!NOTE]
    > <P>If the invoice amount is less than the payment fee, you can clear the <STRONG>Vendor pays payment fee</STRONG> check box on the <STRONG>Payment fee</STRONG> tab in the <STRONG>Journal voucher</STRONG> form so that you can pay the payment fees to the bank. Alternatively, you can remove the payment from the payment journal.</P>



8.  Click **Functions** \> **Generate payments** to generate the payment for the vendor.

9.  Click **Post** \> **Post** to post the payment.

## Related tasks

[(JPN) Generate payments with JBA export format](jpn-generate-payments-with-jba-export-format.md)

[(JPN) Bank payment fees for vendors](jpn-bank-payment-fees-for-vendors.md)

  


