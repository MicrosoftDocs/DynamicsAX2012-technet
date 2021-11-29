---
title: (JPN) Bank payment fees for vendors
TOCTitle: (JPN) Bank payment fees for vendors
ms:assetid: 7fbe7e21-0998-4bcf-943e-4b8bf2a5bda6
ms:mtpsurl: https://technet.microsoft.com/library/Dn313056(v=AX.60)
ms:contentKeyID: 54936307
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Bank payment fees for vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012_

When you make payments to a vendor, the bank payment fees can be paid by you or by the vendor. When the vendor pays the bank payment fees, you can set up Microsoft Dynamics AX so that each time the company pays the vendor, the bank payment fees are automatically deducted from the payment. Perform the following tasks to set up and calculate the bank payment fees for a vendor:

  - Indicate that the vendor pays the bank payment fees.

  - Create a payment rule to be used to calculate bank payment fees that are deducted from the payment that the company makes to the vendor.

  - Set up a payment fee by using the payment rule.

  - Create and post a payment for the vendor who pays the bank payment fees.

  - Generate the payment file.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## Can I specify criteria that I can use to calculate bank payment fees?

Yes. You can use the **Bank rules for payment fee** form to create a bank rule to set up criteria that you can use to calculate payment fees. After you create the bank rule, you can use the bank rule to set up a payment fee in the **Payment fee** form.

For example, you can create the following rules for bank accounts.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Condition for the rule</strong></p></th>
<th><p><strong>ID</strong></p></th>
<th><p><strong>Third party bank group</strong></p></th>
<th><p><strong>Relationship</strong></p></th>
<th><p><strong>Company bank group</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Bank accounts in the same bank</p></td>
<td><p>Bank_Same</p></td>
<td><p><strong>Bank code</strong></p></td>
<td><p><strong>=</strong></p></td>
<td><p><strong>Bank code</strong></p></td>
</tr>
<tr class="even">
<td><p>Bank accounts in different branches of the same bank</p></td>
<td><p>Branch_Different</p></td>
<td><p><strong>Bank code</strong></p></td>
<td><p><strong>=</strong></p></td>
<td><p><strong>Bank code</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p><strong>Branch code</strong></p></td>
<td><p><strong>&lt;&gt;</strong></p></td>
<td><p><strong>Branch code</strong></p></td>
</tr>
<tr class="even">
<td><p>Bank accounts in different banks</p></td>
<td><p>Bank_Diff</p></td>
<td><p><strong>Bank code</strong></p></td>
<td><p><strong>&lt;&gt;</strong></p></td>
<td><p><strong>Bank code</strong></p></td>
</tr>
</tbody>
</table>


## Can I set up a rule to compare values?

Yes. You can set up a rule to compare the value that you specify in the **Value** field against the filter value you select in the **Third party bank group** field in the **Bank rules for payment fee** form. For example, to create a bank rule that applies to a particular bank that has a bank code of 001, select **Bank code** in the **Third party bank group** field, select **=** in the **Relationship** field, and then enter 001 in the **Value** field.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Condition for the rule</strong></p></th>
<th><p><strong>Third party bank group</strong></p></th>
<th><p><strong>Relationship</strong></p></th>
<th><p><strong>Value</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A bank account that is assigned to a value</p></td>
<td><p><strong>Bank code</strong></p></td>
<td><p><strong>=</strong></p></td>
<td><p>001</p></td>
</tr>
</tbody>
</table>


## How can I calculate the consumption tax on the bank payment fees?

To calculate the consumption tax on the bank payment fees, you can set up the following information on the **General** tab, in the **Payment fee setup** form:

  - Specify whether the payment amounts include taxes in the **Fee amount** field. To include sales tax in the fee amount, you can select **Amounts include sales tax** check box on the **Setup** tab in the **Payment journal** form.

  - Select the method of payment in the **Method of payment** field.

  - Select **Percent** in the **Percentage/Amount** field.

  - Specify the payment fee percentage in the **Fee amount** field.

  - Set the payment threshold in the **Minimum** and **Maximum** fields.

For more information, see [Vendor payment fee setup (form)](https://technet.microsoft.com/library/aa598976\(v=ax.60\)).

## How can I differentiate between bank accounts from the same bank?

To differentiate between two different bank accounts within the same bank, you can use the bank group as a filter for the bank rule. In the **Bank rules for payment fee** form, select **Bank groups** in the **Third party bank group** field and **Company bank group** fields, and then select **\<\>** in the **Relationship** field.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(JPN) Set up and calculate the bank payment fees for a vendor](jpn-set-up-and-calculate-the-bank-payment-fees-for-a-vendor.md)

  


