---
title: (IND) Set up thresholds and concession certificates for tax calculations
TOCTitle: (IND) Set up thresholds and concession certificates for tax calculations
ms:assetid: 36b6d073-903e-41fc-90fd-5a0882bf72b5
ms:mtpsurl: https://technet.microsoft.com/library/Dn527712(v=AX.60)
ms:contentKeyID: 59626285
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxWithholdTable
- India
- Forms.ConcessionCertificateDetails_IN
- Forms.TaxValueThresholdProfile_IN
- Forms.ThresholdReference_IN
- Forms.ThresholdDesigner_IN
- concession certificate
- concession certificates
- tax thresholds
- tax threshold
- threshold hierarchies
- threshold
- threshold hierarchy
- thresholds
- threshold limits
- threshold value
- threshold values
- threshold limit
- MsDynAx060.Forms.ConcessionCertificateDetails_IN
- MsDynAx060.Forms.TaxValueThresholdProfile_IN
- MsDynAx060.Forms.ThresholdReference_IN
- MsDynAx060.Forms.ThresholdDesigner_IN
- MsDynAx060.Forms.TaxWithholdTable
audience: Application User
ms.search.region: India
---

# (IND) Set up thresholds and concession certificates for tax calculations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you create the threshold definitions and set up threshold hierarchies, you can set up thresholds and concession certificates for direct tax calculations. Microsoft Dynamics AX calculates direct taxes on transactions based on the threshold segments that you specify. Follow the steps in this topic to set up thresholds and concession certificates for direct tax calculation.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## This task is part of a bigger process

The following illustration shows how setting up thresholds and concession certificates for direct tax calculation relates to threshold limits task.

For an overview of the process, see [(IND) Tax thresholds and tax concession certificates](ind-tax-thresholds-and-tax-concession-certificates.md).

![Tax threshold and tax concession certificates](images/Dn527712.CU7_India_ThresholdReimagined(AX.60).png "Tax threshold and tax concession certificates")

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with the hotfix in KB2850782</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Create threshold definitions, and set up threshold hierarchies. For more information, see <a href="ind-set-up-threshold-limits.md">(IND) Set up threshold limits</a>.</p></li>
<li><p>Set up tax information for a legal entity in India. Activate Tax Deducted at Source (TDS) and Tax Collected at Source (TCS) calculation for a legal entity. For more information, see <a href="ind-key-tasks-tax-information-for-legal-entities.md">(IND) Key tasks: Tax information for legal entities</a>.</p></li>
<li><p>Set up withholding tax component groups for <strong>TDS</strong> and <strong>TCS</strong> tax types. For more information, see <a href="ind-set-up-withholding-tax-component-groups-for-tcs-tax-types.md">(IND) Set up withholding tax component groups for TCS tax types</a> and <a href="ind-set-up-withholding-tax-component-groups-for-tds-tax-types.md">(IND) Set up withholding tax component groups for TDS tax types</a>.</p></li>
<li><p>Set up withholding tax components for <strong>TDS</strong> and <strong>TCS</strong> tax types.</p>
<div class="alert">

> [!NOTE]
> <P>Make sure that you do not define threshold values for the tax components.</P>


</div>
<p>For more information, see <a href="ind-set-up-withholding-tax-components-for-tds-tax-types.md">(IND) Set up withholding tax components for TDS tax types</a> and <a href="ind-set-up-withholding-tax-components-for-tcs-tax-types.md">(IND) Set up withholding tax components for TCS tax types</a>.</p></li>
<li><p>Set up withholding tax codes for <strong>TDS</strong> and <strong>TCS</strong> tax types.</p>
<div class="alert">

> [!NOTE]
> <P>Make sure that you do not specify values in the <STRONG>Value</STRONG> field in the <STRONG>Withholding tax values</STRONG> form for the withholding tax code.</P>


</div>
<p>For more information, see <a href="ind-set-up-withholding-tax-codes-for-tds-tax-types.md">(IND) Set up withholding tax codes for TDS tax types</a> and <a href="ind-set-up-withholding-tax-codes-for-tcs-tax-types.md">(IND) Set up withholding tax codes for TCS tax types</a>.</p></li>
</ul>
<p></p></td>
</tr>
</tbody>
</table>


## Assign thresholds and threshold values to a withholding tax code

Use the **Withholding tax codes** form to set up a withholding tax code to use threshold limits. Use the **Threshold references** form to set up an entity to use a threshold, and then use the **Threshold designer** form to define the tax rates that apply to the final levels of the various hierarchy segments of the threshold.

To assign threshold and threshold values to a withholding tax code, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Select a withholding tax code that has a **TDS** or **TCS** tax type for which to apply the threshold.
    

    > [!NOTE]
    > <P>If you specified values in the <STRONG>Value</STRONG> field in the <STRONG>Withholding tax values</STRONG> form for the withholding tax code, remove the values.</P>



3.  Select the **Apply threshold** check box to apply threshold for the tax code.

4.  Click **Threshold references** to open the **Threshold references** form, where you can set up an entity to use a threshold by specifying the account type, account code, and threshold definition.
    
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
    <td><p><strong>Account type</strong></p></td>
    <td><p>Select the type of account to which to apply the threshold.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Customer</strong> – Apply the threshold to a customer account, a customer group, or all customers.</p></li>
    <li><p><strong>Vendor</strong> – Apply the threshold to a vendor account, a vendor group, or all vendors.</p></li>
    <li><p><strong>All</strong> – Apply the threshold to all customers and all vendors.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this option, <STRONG>All</STRONG> is updated in the <STRONG>Account code</STRONG> field, and the <STRONG>Account code</STRONG> field is not available.</P>


    </div></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account code</strong></p></td>
    <td><p>Select the account code for the selected account type.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Table</strong> – Apply the threshold for a single customer account or vendor account.</p></li>
    <li><p><strong>Group</strong> – Apply the threshold for a customer group or vendor group.</p></li>
    <li><p><strong>All</strong> – Apply the threshold for all customers or all vendors.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Account or group</strong></p></td>
    <td><p>Select the customer account, customer group, vendor account, or vendor group that the threshold applies to. This field is determined by the selections in the <strong>Account type</strong> and <strong>Account code</strong> fields.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Threshold</strong></p></td>
    <td><p>Select the threshold definition to apply to the account type, account code, and account or account groups that you selected.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Cumulative</strong> – Apply the threshold segment to cumulative transaction values.</p></li>
    <li><p><strong>Per transaction</strong> – Apply the threshold segment to individual transaction values.</p></li>
    <li><p><strong>Per transaction line</strong> – Apply the threshold segment to individual transaction line values.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


5.  After you set up the entity to use a threshold definition, click **Threshold designer** to open the **Threshold designer** form, where you can define the tax rates that apply to the final levels of the various hierarchy segments of the threshold.

6.  In the left pane, select a final level of a threshold segment, and then modify the effective dates, lower and upper limits, or type of threshold, if required.
    
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
    <td><p><strong>Effective from</strong></p></td>
    <td><p>Modify the date from which the threshold values are effective.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Effective to</strong></p></td>
    <td><p>Modify the date until which the threshold values are effective.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Lower limit</strong></p></td>
    <td><p>Modify the starting point of the threshold segment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Upper limit</strong></p></td>
    <td><p>Modify the ending point of the threshold segment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Type</strong></p></td>
    <td><p>Modify the type of threshold to apply to the selected segment.</p></td>
    </tr>
    </tbody>
    </table>


7.  In the right pane, on the **Tax value** FastTab, click **New**, and then set up a threshold value for the selected final level segment.
    
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
    <td><p><strong>Tax effective from</strong></p></td>
    <td><p>Select the starting date from which the tax values are effective.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Tax effective to</strong></p></td>
    <td><p>Select the ending date until which the tax values are effective.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>PAN Status</strong></p></td>
    <td><p>If the threshold applies to a vendor, a vendor group, or all vendors, select <strong>Not available</strong> or <strong>Received</strong> as the status of the Permanent Account Number (PAN) to apply the threshold to. For example, if you select <strong>Received</strong> in this field, the tax value will apply only to the vendors who have the PAN status set up as <strong>Received</strong> in the <strong>Vendors</strong> form.</p>
    <p>Alternatively, if the threshold applies to a customer, a customer group, or all customers, select <strong>Not applicable</strong> as the status of the PAN to apply the threshold to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Overlook threshold</strong></p></td>
    <td><p>If you select the <strong>Overlook threshold</strong> check box in the <strong>Withholding tax groups</strong> form for the withholding tax code, select this check box to use the tax value.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Value</strong></p></td>
    <td><p>The percentage that is used to calculate direct taxes for the threshold segment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reason code</strong></p></td>
    <td><p>Enter the reason for a lower deduction or no deduction. This reason will be printed on the TDS or TCS statements and electronic file.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Calculate tax</strong></p></td>
    <td><p>Select <strong>Yes</strong> or <strong>No</strong> to indicate whether the direct tax is calculated for this value.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Include in turnover base</strong></p></td>
    <td><p>Select <strong>Yes</strong> or <strong>No</strong> to indicate whether to include the value of this transaction in the overall turnover base that will be used for other transactions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Calculate previously nontaxed transactions</strong></p></td>
    <td><p>Select this check box to calculate direct tax on all previous taxable transactions for which taxes were not calculated.</p></td>
    </tr>
    </tbody>
    </table>


8.  Repeat step 7 to set up additional values for the same threshold segment.

9.  Repeat steps 6 and 7 to set up values for additional threshold segments.

10. Repeat steps 4 through 7 to set up additional entities to use the threshold.

You can click **Referenced by** to open the **Threshold reference list** form, where you can view the list of referencing entities that use the selected threshold.

## If required: Set up a tax concession certificate for a customer or vendor

If a customer or a vendor has a concession certificate, you can use the **Withholding tax concessions** form to set up the details of the tax concession certificate for the customer or vendor in Microsoft Dynamics AX. You can set up a tax concession certificate for a vendor only if you have set up the PAN status for the vendor as **Received** in the **Status** field on the **Tax information** FastTab in the **Vendors** form.


> [!NOTE]
> <P>If you change the PAN status for a vendor from <STRONG>Received</STRONG> to <STRONG>Not available</STRONG> in the <STRONG>Status</STRONG> field on the <STRONG>Tax information</STRONG> FastTab in the <STRONG>Vendors</STRONG> form, the tax concession certificate that is available for the vendor will be deleted.</P>



To set up a tax concession certificate for a customer or vendor, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

2.  Select a withholding tax code that has a **TDS** or **TCS** tax type for which threshold is applied.

3.  Click **Threshold references** to open the **Threshold references** form, and then select the threshold reference to set up the concession certificate for.

4.  Click **Threshold designer** to open the **Threshold designer** form, and then select a final level of a threshold segment to set up the concession certificate for.

5.  Click **Concession certificate** to open the **Withholding tax concessions** form.
    

    > [!NOTE]
    > <P>The <STRONG>Concession certificate</STRONG> button is available only if you set up a customer or vendor account to use the threshold by specifying <STRONG>Customer</STRONG> or <STRONG>Vendor</STRONG> in the <STRONG>Account type</STRONG> field, <STRONG>Table</STRONG> in the <STRONG>Account code</STRONG> field, and a customer or vendor account in the <STRONG>Account or group</STRONG> field in the <STRONG>Threshold references</STRONG> form.</P>



6.  In the **Certificate number** field, enter the number of the tax concession certificate that is received from the customer or vendor.

7.  In the **From date** and **To date** fields, specify the first and the last dates of the validity of the certificate.

8.  In the **Effective cancellation date** field, enter the date after which the certificate will no longer be used or will be canceled.

9.  In the **Turnover threshold** field, enter the maximum turnover amount up to which the certificate is applicable.

10. Click **OK**.

11. Repeat steps 4 through 10 to set up tax concession certificates for other segments, if required.

## Next step

You have finished setting up tax thresholds and tax concession certificates for India. To set up withholding tax groups, and to create and post transactions that use thresholds, perform the following tasks:

1.  Set up a withholding tax group that contains the withholding tax codes to which you assigned thresholds and threshold values. For more information about how to set up a withholding tax group, see [(IND) Withholding tax groups (modified form)](https://technet.microsoft.com/library/jj677874\(v=ax.60\)).

2.  Create and post transactions that use the withholding tax group for the withholding tax codes to which you assigned thresholds and threshold values. For more information about how to create and post transactions, see [Calculate and post withholding tax](calculate-and-post-withholding-tax.md) and [Enter a vendor payment that is subject to withholding tax](enter-a-vendor-payment-that-is-subject-to-withholding-tax.md).

## Related tasks

[(IND) Define withholding tax information for vendors](ind-define-withholding-tax-information-for-vendors.md)

[(IND) Withholding tax component groups (form)](https://technet.microsoft.com/library/jj678017\(v=ax.60\))

[(IND) Withholding tax components (form)](https://technet.microsoft.com/library/jj664790\(v=ax.60\))

[(IND) Withholding tax codes (modified form)](https://technet.microsoft.com/library/jj664629\(v=ax.60\))

[Withholding tax transactions report (TaxWithholdTrans)](withholding-tax-transactions-report-taxwithholdtrans.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up thresholds and concession certificates for tax calculations, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable sales taxes process</strong> (TaxSalesTaxesProcessEnable)</p></li>
<li><p><strong>Inquire into sales tax process reference data</strong> (TaxSalesTaxProcessReferenceDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up thresholds and concession certificates for tax calculations, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain withholding tax codes</strong> (TaxWithholdTableMaintain)</p></li>
<li><p><strong>View withholding tax codes</strong> (TaxWithholdTableView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


