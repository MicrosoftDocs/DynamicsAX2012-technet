---
title: (IND) Configure withholding tax calculation
TOCTitle: (IND) Configure withholding tax calculation
ms:assetid: bee2e9ad-2635-423f-8d90-aa6842aeb953
ms:mtpsurl: https://technet.microsoft.com/library/Dn344874(v=AX.60)
ms:contentKeyID: 56117705
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustTable
- Forms.TaxWithholdGroup
- Forms.VendTable
audience: Application User
ms.search.region: India
---

# (IND) Configure withholding tax calculation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Follow the steps in this topic to set up withholding tax groups for tax deducted at source (TDS) and tax collected at source (TCS), and to set up the withholding tax calculation for a customer and a vendor. For more information, see [(IND) Withholding tax calculation](ind-withholding-tax-calculation.md).


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
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Select the <strong>Activate TDS</strong>, <strong>Invoice</strong>, <strong>Payment</strong>, and <strong>Service tax</strong> check boxes in the <strong>General ledger parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p>
<div class="alert">

> [!NOTE]
> <P>The <STRONG>Exclude tax for TDS or TCS calculation</STRONG> and the <STRONG>Exclude charges for TDS or TCS calculation</STRONG> fields are available in the <STRONG>Withholding tax groups</STRONG> form only if you clear the <STRONG>Activate TDS</STRONG> check box, and then select it again.</P>


</div></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up withholding tax components. For more information, see <a href="ind-set-up-withholding-tax-components-for-tds-tax-types.md">(IND) Set up withholding tax components for TDS tax types</a> and <a href="ind-set-up-withholding-tax-components-for-tcs-tax-types.md">(IND) Set up withholding tax components for TCS tax types</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Set up withholding tax codes for the TDS tax type. For more information, see <a href="ind-set-up-withholding-tax-codes-for-tds-tax-types.md">(IND) Set up withholding tax codes for TDS tax types</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up withholding tax codes for the TCS tax type. For more information, see <a href="ind-set-up-withholding-tax-codes-for-tcs-tax-types.md">(IND) Set up withholding tax codes for TCS tax types</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Create sales tax codes, sales tax groups, and item sales tax groups for indirect taxes. For more information, see <a href="ind-set-up-sales-tax-groups-for-vat.md">(IND) Set up sales tax groups for VAT</a>, <a href="ind-create-item-sales-tax-groups.md">(IND) Create item sales tax groups</a>, and <a href="https://technet.microsoft.com/library/jj664688(v=ax.60)">(IND) Sales tax groups (modified form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a withholding tax group for the TDS tax type

Use the **Withholding tax groups** from to set up a withholding tax group for the **TDS** tax type. You can set up a withholding tax group to calculate the TDS by excluding other taxes and charges.

To set up a withholding tax group for the **TDS** tax type, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax groups**.

2.  Create a withholding tax group. For more information, see [(IND) Withholding tax groups (modified form)](https://technet.microsoft.com/library/jj677874\(v=ax.60\)).

3.  In the **Tax type** field, select **TDS**.

4.  In the **Exclude tax for TDS or TCS calculation** field, select the tax to exclude from the TDS calculation, and then click **OK**. For example, to exclude service tax for the rental calculation, select **Service tax** in this field. This field is empty by default.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>TDS</STRONG> or <STRONG>TCS</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



5.  In the **Exclude charges for TDS or TCS calculation** field, select **Yes** to exclude the charges from the withholding tax calculation. The default value of this field is **No**.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>TDS</STRONG> or <STRONG>TCS</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



## 2\. Set up a withholding tax group for the TCS tax type

You can use the **Withholding tax groups** form to set up a withholding tax group for the **TCS** tax type. You can set up a withholding tax group to calculate the TCS by excluding other taxes and charges.

To set up a withholding tax group for the **TCS** tax type, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax groups**.

2.  Create a withholding tax group.

3.  In the **Tax type** field, select **TCS**.

4.  In the **Exclude tax for TDS or TCS calculation** field, select the tax to exclude from the TCS calculation, and then click **OK**. This field is empty by default.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>TCS</STRONG> or <STRONG>TDS</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



5.  In the **Exclude charges for TDS or TCS calculation** field, select **Yes** to exclude the charges from the TCS calculation. The default value in this field is **No**.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>TCS</STRONG> or <STRONG>TDS</STRONG> in the <STRONG>Tax type</STRONG> field.</P>



## 3\. Set up the withholding tax calculation for a customer

Use the **Customers** form to set up the information that is used to calculate withholding tax for a customer.

To set up the withholding tax calculation for a customer, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select or create a customer account, and then click **Edit**. For more information, see [Create a customer record](create-a-customer-record.md).

3.  In the **Customers** form, on the **Invoice and delivery** FastTab, in the **Withholding tax** field group, select the **Calculate withholding tax** check box.

4.  In the **TDS group** field, select the withholding tax group for the **TDS** tax type for the customer.
    
    –or–
    
    In the **TCS group** field, select the default withholding tax group for the **TCS** tax type for the customer. This withholding tax group is used as the default withholding tax group for all of the transactions for which the selected customer account is debited.

## 4\. Set up the withholding tax calculation for a vendor

Use the **Vendors** form to set up the information that is used to calculate withholding tax for a vendor.

To set up the withholding tax calculation for a vendor, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select or create a vendor account, and then click **Edit**. For more information, see [Create a vendor account](create-a-vendor-account.md).

3.  In the **Vendors** form, on the **Invoice and delivery** FastTab, in the **Withholding tax** field group, select the **Calculate withholding tax** check box.

4.  In the **Withholding tax group** field, select the default withholding tax group for the vendor.
    
    –or–
    
    In the **TDS group** field, select the default withholding tax group for the **TDS** tax type for the vendor. This withholding tax group is used as the default withholding tax group for all of the transactions for which the selected vendor account is credited.
    
    –or–
    
    In the **TCS group** field, select the withholding tax group for the **TCS** tax type for the vendor.

## Related tasks

[Calculate and post withholding tax](calculate-and-post-withholding-tax.md)

[(IND) Customers (modified form)](https://technet.microsoft.com/library/jj678004\(v=ax.60\))

[(IND) Vendors (modified form)](https://technet.microsoft.com/library/jj664890\(v=ax.60\))

[(IND) About recalculation of indirect taxes](ind-about-recalculation-of-indirect-taxes.md)

  


