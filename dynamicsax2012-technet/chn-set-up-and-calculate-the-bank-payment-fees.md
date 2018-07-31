---
title: (CHN) Set up and calculate the bank payment fees
TOCTitle: (CHN) Set up and calculate the bank payment fees
ms:assetid: cf8b1bc1-9bc1-47d3-9901-443175a27d06
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn364501(v=AX.60)
ms:contentKeyID: 56472064
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.VendPaymFee
- Forms.VendPaymModeFee
- Forms.LedgerJournalTransVendPaym
- Forms.LedgerJournalTable
- Forms.PaymFeeBankRule_JP
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Set up and calculate the bank payment fees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up and calculate the bank payment fees that you pay when you make a payment to a vendor.


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
<td><p>Set up bank groups. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa571457(v=ax.60)">Bank groups (form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create a rule to calculate bank payment fees

Use the **Bank rules for payment fee** form to create a payment rule to be used to calculate bank payment fees that are deducted from the payment that the legal entity makes to the vendor. You can create a bank rule to track bank accounts that are located in different cities.

To create a bank rule, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Bank rules for payment fee**.

2.  Create a bank rule.

3.  In the **ID** field, type a short descriptor that identifies the bank rule. You select this descriptor when you set up the payment fee in the **Payment fee setup** form.

4.  In the **Name** field, type a name or description for the bank rule.

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
    <td><p>Select a field for the third party bank group that is used in the bank rule. For example, you can select the city of the third party group.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Relationship</strong></p></td>
    <td><p>Select the operator that indicates the relationship between the third party bank group and the company bank group.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Value</strong></p></td>
    <td><p>Assign a filter to compare the value in the <strong>Value</strong> field against the value that is selected in the <strong>Third party bank group</strong> field or the <strong>Company bank group</strong> field when calculating the bank payment fees. For example, to create a bank rule that applies to a particular bank that has a bank code of 001, select <strong>Bank code</strong> in the <strong>Third party bank group</strong> field, <strong>=</strong> in the <strong>Relationship</strong> field, and 001 in the <strong>Value</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Company bank group</strong></p></td>
    <td><p>Select a filter value for the company bank group that is used in the bank rule. For example, to apply this rule when your bank and the vendor bank are located in different cities, select <strong>City</strong> in the <strong>Third party bank group</strong> field, <strong>&lt;&gt;</strong> in the <strong>Relationship</strong> field, and <strong>City</strong> in the <strong>Company bank group</strong> field.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Set up a payment fee

After you create the bank rule, use the bank rule to set up a payment fee in the **Payment fee** form. You can set up the payment fee amounts for banks, methods of payment, payment specifications, calculation methods, and currencies.

To set up a payment fee, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Create a payment fee record. For more information see [Vendor payment fee (form)](https://technet.microsoft.com/en-us/library/aa573151\(v=ax.60\)).

3.  In the **Main account** field, select the ledger account that is used to post the bank payment fee that you pay.

4.  Click **Payment fee setup** to open the **Payment fee setup** form, where you can set up banks, methods of payment, payment specifications, calculation methods, and currencies. For more information, see [Vendor payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa598976\(v=ax.60\)).

5.  On the **Overview** tab, in the **Bank rule ID for payment fee** field, select the identification code for the bank rule to apply the bank payment fee to.

6.  In the **Method of payment** field, specify the applicable payment method.

7.  On the **General** tab, in the **Administration** field group, in the **Currency** field, enter the currency for the payment.

8.  In the **Minimum** field, enter the minimum transaction amount on which the bank payment fee is calculated. The bank payment fee can be a fixed amount or a percentage of the transaction amount, as illustrated in the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p><strong>Minimum transaction amount</strong></p></td>
    <td><p><strong>Amount</strong> or <strong>Percent</strong></p></td>
    <td><p><strong>Bank payment fees</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>5000 RMB</p></td>
    <td><p>50 RMB or 1 percent</p></td>
    <td><p>50 RMB</p></td>
    </tr>
    </tbody>
    </table>


9.  In the **Maximum** field, enter the maximum transaction amount on which the bank payment fee is calculated.

10. In the **Fee** field group, in the **Percentage/Amount** field, select **Amount** or **Percent**.

11. In the **Fee amount** field, enter the bank payment fee amount or percentage depending on what you select in the **Percentage/Amount** field.

12. In the **Currency** field, select the currency code for the fee amount.

13. Specify other details, if required.

## 3\. Create and post a payment journal for a vendor

Use the **Payment journal** form to create and post a payment for a vendor. Microsoft Dynamics AX calculates the bank payment fees based on the association that you create between the bank payment rule and the payment fee.

To create a payment journal, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal, and then create a payment journal line for the payment amount. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md) and [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)).

3.  On the **Overview** tab, in the **Account** field, select the account number for the vendor.

4.  In the **Offset account** field, select the offset account for the transaction.

5.  In the **Method of payment** field, select a method of payment.

6.  On the **Bank** tab, in the **Account identification** field, enter the vendor bank account. Specify other details, if required.

7.  On the **Payment fee** tab, the bank fee amount is automatically calculated based on the values in the **Method of payment**, **Offset account**, and **Account identification** fields.
    

    > [!NOTE]
    > <P>If you modify the vendor bank account in the <STRONG>Account identification</STRONG> field on the <STRONG>Bank</STRONG> tab, the bank fee is recalculated.</P>



8.  Click **Functions** \> **Generate payments** to generate the payment.

9.  Click **Post** \> **Post** to post the payment.

When you post the payment, the bank payment fees are deducted from the vendor payment.

## Related tasks

[Generate payments - vendor (class form)](https://technet.microsoft.com/en-us/library/aa586980\(v=ax.60\))

  


