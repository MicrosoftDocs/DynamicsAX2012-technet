---
title: (IND) Set up and use a sales tax hierarchy
TOCTitle: (IND) Set up and use a sales tax hierarchy
ms:assetid: 85f0f5b0-7968-49d9-823a-656c4a83b7f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn528665(v=AX.60)
ms:contentKeyID: 59636749
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax
- Forms.TaxReportVoucher
- Forms.LedgerParameters
- Forms.TaxComponentTable_IN
- sales tax hierarchy
- sales tax hierarchy structure
- sales tax payment
- sales tax settlement
- Classes.TaxSalesTaxPayment_IN
- Forms.TaxReportHierarchyDesigner_IN
- Forms.TaxReportHierarchyList_IN
- Forms.TaxReportHierarchySetOffRules_IN
- Forms.TaxReportSetOffHierarchySetup_IN
- Forms.TaxSalesTaxPaymentHistory_IN
- MsDynAx060.Forms.LedgerParameters
- MsDynAx060.Forms.TaxReportVoucher
- MsDynAx060.Forms.TaxComponentTable_IN
- MsDynAx060.Forms.TaxReportHierarchyDesigner_IN
- MsDynAx060.Forms.TaxReportHierarchyList_IN
- MsDynAx060.Forms.TaxSalesTaxPaymentHistory_IN
- MsDynAx060.Forms.TaxReportHierarchySetOffRules_IN
- MsDynAx060.Forms.TaxReportSetOffHierarchySetup_IN
---

# (IND) Set up and use a sales tax hierarchy 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Set up a sales tax hierarchy and then use the sales tax hierarchy to set up a tax setoff rule, set up a sales tax hierarchy profile, and settle sales tax transactions. For an overview of sales tax hierarchies, see [(IND) Sales tax hierarchies](ind-sales-tax-hierarchies.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



The following illustration shows how to set up and use a sales tax hierarchy. The numbers correspond to the procedures later in this topic.

![The process to set up and use a sales tax hierarch](images/Dn528665.Salestaxhierarchy(AX.60).jpg "The process to set up and use a sales tax hierarch")

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
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up the parameter for India sales tax. For more information, see <a href="ind-activate-sales-tax-parameters.md">(IND) Activate sales tax parameters</a>.</p>
<p></p>
<p>Set up sales tax codes, sales tax groups, and item sales tax groups. For more information, see <a href="ind-set-up-sales-tax-codes.md">(IND) Set up sales tax codes</a>, <a href="ind-set-up-sales-tax-groups-for-vat.md">(IND) Set up sales tax groups for VAT</a>, and <a href="ind-create-item-sales-tax-groups.md">(IND) Create item sales tax groups</a>.</p>
<p>Set up tax components for sales tax. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj664734(v=ax.60)">(IND) Tax components (form)</a>.</p>
<p>Set up service codes. For more information, see <a href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up the parameter to use the sales tax hierarchy

Use the **General ledger parameters** form to set up the parameter to use the sales tax hierarchy.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**, and then in the **Sales tax** area, on the **General** FastTab, select the **Use the sales tax hierarchy framework** check box to process sales tax payments using the sales tax hierarchy.

## 2\. Set up a sales tax hierarchy

Microsoft Dynamics AX provides a default hierarchical structure that you can use to set up a sales tax hierarchy based on your requirements. Use the **Sales tax hierarchies** form to set up a sales tax hierarchy based on the default hierarchical structure.

To set up a sales tax hierarchy, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Sales tax hierarchies**.

2.  In the **Sales tax hierarchies** form, click **New** to create a sales tax hierarchy record based on the default hierarchical structure.

3.  In the **Create a sales tax hierarchy** dialog box, in the **Name** field, enter a name for the sales tax hierarchy.

4.  In the **Structure** field, specify the structure for the sales tax hierarchy, and then click **OK**. The name and the structure of the sales tax hierarchy are updated in the **Sales tax hierarchies** form.
    
    The **Use a sales tax hierarchy for tax setoff** check box is selected by default based on the default hierarchical structure. The **Structure schematic diagram** FastTab provides a visual representation of the sales tax hierarchy. A default hierarchy version is created on the **Versions** FastTab when you create the sales tax hierarchy.
    

    > [!NOTE]
    > <P>You cannot modify the structure type for the sales tax hierarchy in the <STRONG>Sales tax hierarchies</STRONG> form.</P>



5.  Optional: On the **Versions** FastTab, click **Add** to create an additional version of the sales tax hierarchy. The version number is updated with the next number in the sequence based on the time and date when the hierarchy version is created.
    
    –or–
    
    Optional: On the **Versions** FastTab, click **Copy** to copy a selected sales tax hierarchy version to use as the template for a new hierarchy version.
    

    > [!NOTE]
    > <P>Click <STRONG>Remove</STRONG> to delete the selected version of the sales tax hierarchy. You cannot delete a sales tax hierarchy version that is referenced by a transaction or used in a sales tax hierarchy profile.</P>



6.  On the **Versions** FastTab, in the **Description** field, enter a description for the sales tax hierarchy version.

7.  Click **Synchronize** to synchronize the tax components and service codes that you configured with the nodes in the structure of the sales tax hierarchy.

8.  To activate the selected sales tax hierarchy version, click **Activate**.

9.  To deactivate the selected sales tax hierarchy version, click **Deactivate**.
    

    > [!NOTE]
    > <P>You cannot deactivate a sales tax hierarchy version that is used in a sales tax hierarchy profile.</P>



10. Click **View** to open the **Sales tax hierarchy designer** form, where you can modify the selected sales tax hierarchy.

## 3\. Manage a sales tax hierarchy

After you set up the sales tax hierarchy based on the default hierarchical structure, you can manage the sales tax hierarchy based on your requirements. Use the **Sales tax hierarchy designer** form to manage the selected sales tax hierarchy version.

To manage the sales tax hierarchy, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Sales tax hierarchies**.

2.  In the **Sales tax hierarchies** form, on the **Versions** FastTab, select a sales tax hierarchy version, and then click **View** to open the **Sales tax hierarchy designer** form.

3.  On the **Action Pane**, on the **Hierarchy designer** tab, click **Edit** to modify the default sales tax hierarchy.

4.  To enable a selected node for the sales tax hierarchy, click **Enable**. You can use the hierarchy node to create tax setoff rules.

5.  To disable a selected node for the sales tax hierarchy, click **Disable**.

6.  Click **Synchronize** to synchronize the tax components and service codes that you configured with the nodes in the sales tax hierarchy.

7.  Optional: To make a hierarchy node the focus of the sales tax hierarchy, click the button on the node. The sales tax hierarchy is updated to display only the selected node and its child nodes.

8.  Optional: Click **Hierarchy details** to open the **Sales tax hierarchies** form, where you can view the structure type and version details about the sales tax hierarchy.

9.  Optional: Select a tax component, a service code, or a tax record type node for the sales tax hierarchy, and then click **Node details** to open the **Tax components** form, where you can view the tax component details.

## 4\. Set up a tax setoff rule

Use the **Setoff rules for sales tax hierarchies** form to set up a tax setoff rule that is used to set off the input tax for one tax component in the sales tax hierarchy with the output tax of another tax component.

To set up a tax setoff rule, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Sales tax hierarchies**.

2.  In the **Sales tax hierarchies** form, click **View** to open the **Sales tax hierarchy designer** form.

3.  On the **Action Pane**, on the **Hierarchy designer** tab, click **Setoff rules for sales tax hierarchies** to open the **Setoff rules for sales tax hierarchies** form.

4.  Click **New** to create a setoff rule. The priority that determines how the tax setoff rules are applied to the sales tax hierarchy is automatically updated in the **Priority** field.

5.  In the **Name** field, enter a name for the tax setoff rule.

6.  On the **Recoverable** FastTab, in the right pane, select the tax types, service codes, tax components, and tax record types that are used to set off taxes.

7.  On the **Payable** FastTab, in the right pane, select the tax types, service codes, tax components, and tax record types that are set off against the recoverable tax nodes. For example, you can set off service tax against excise duty by selecting **Service tax** on the **Recoverable** FastTab and **Excise** on the **Payable** FastTab.
    

    > [!NOTE]
    > <P>The path of the selected service code, tax component, and tax record type from the root node of the sales tax hierarchy to the selected node on the <STRONG>Recoverable</STRONG> FastTab and the <STRONG>Payable</STRONG> FastTab is updated in the <STRONG>Path of the selected node</STRONG> field.</P>



## 5\. Create a sales tax hierarchy profile

Use the **Maintain setoff hierarchy profiles** form to create a sales tax hierarchy profile. You can create multiple versions of the sales tax hierarchy for different reporting periods based on your requirements.

To create a sales tax hierarchy profile, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Maintain setoff hierarchy profiles**.

2.  Click **New**, and then in the **Create a setoff hierarchy profile** dialog box, in the **Effective date** field, select the date from which the sales tax hierarchy is effective.

3.  In the **Hierarchy** field, select the sales tax hierarchy that is applied to set off taxes, and then click **OK**. You can only select a sales tax hierarchy that is active, and for which the **Use a sales tax hierarchy for tax setoff** check box is selected in the **Sales tax hierarchies** form.
    

    > [!NOTE]
    > <P>The version number and the description of the sales tax hierarchy from the <STRONG>Sales tax hierarchies</STRONG> form are updated in the <STRONG>Version</STRONG> field and the <STRONG>Description</STRONG> field based on the hierarchy that you select in the <STRONG>Hierarchy</STRONG> field.</P>



## 6\. Activate a setoff hierarchy profile

After you create a sales tax hierarchy profile or modify an existing profile, you can activate the sales tax hierarchy. When you activate a setoff hierarchy, all of the unsettled transactions are validated and updated against the active hierarchy and version. For example, if an unsettled transaction contains service tax, then the service tax information, such as service code and accounting code information, is validated based on the active sales tax hierarchy.

To activate a setoff hierarchy profile, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Maintain setoff hierarchy profiles**.

2.  Select a profile, and then click **Activate**.

Click **History** to open the **Setoff hierarchy revision history** form, where you can view the number of changes that you made to an activated hierarchy profile. You can view the date when the hierarchy is activated and the name of the person who activated the hierarchy profile for each version.

## 7\. Optional: Discard the changes in the setoff hierarchy profile

Complete this procedure to reject the changes to the setoff hierarchy profile that have not been activated.

To discard the setoff hierarchy profile changes, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Maintain setoff hierarchy profiles**.

2.  Select a profile, and then click **Discard**.

## 8\. Settle sales tax transactions using a sales tax hierarchy

Use the **Sales tax payment balances** form to use the setoff rules that you created based on the sales tax hierarchy to process sales tax payments.

To settle sales tax transactions, follow these steps:

1.  Click **General ledger** \> **Reports** \> **External** \> **Sales tax payments**.

2.  In the **Sales tax payments** form, select a sales tax transaction, and then click **Sales tax payment balances**. You can view the recoverable and payable information that is used to settle each tax type.
    
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
    <td><p><strong>Registration number</strong></p></td>
    <td><p>The tax registration number for the tax type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Path of the selected node</strong></p></td>
    <td><p>The path from the root node of the sales tax hierarchy to the selected node for the selected tax type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Recoverable amount</strong></p></td>
    <td><p>The recoverable tax amount of the tax type for the transaction.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Recoverable amount to settle</strong></p></td>
    <td><p>Modify the recoverable tax amount that is used to settle the payable tax amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Adjustment</strong></p></td>
    <td><p>The amount that is adjusted for the tax type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payable amount</strong></p></td>
    <td><p>The payable tax amount of the transaction for the selected tax type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payable amount to settle</strong></p></td>
    <td><p>Modify the payable tax amount that is used in the tax settlement process.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Subtotal amount</strong></p></td>
    <td><p>The balance amount for the tax type after tax settlement.</p></td>
    </tr>
    </tbody>
    </table>


When you run the sales tax settlement process, you can view the details of each tax component in the **Payment journal** form. In the **Journal voucher** form of the vendor payment journal, click **Functions** \> **Settlement**. The component-related tax details are displayed for the voucher that is generated on the **Overview** tab in the **Settle open transactions** form.

## Related tasks

[(IND) Set up sales taxes for multiple taxation transactions](ind-set-up-sales-taxes-for-multiple-taxation-transactions.md)

[(IND) Define a service tax component and the tax setoff](ind-define-a-service-tax-component-and-the-tax-setoff.md)

[(IND) Define ledger posting groups for tax components](ind-define-ledger-posting-groups-for-tax-components.md)

[(IND) Calculate sales tax settlements](ind-calculate-sales-tax-settlements.md)

[(IND) View transactions with sales tax](ind-view-transactions-with-sales-tax.md)

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
<td><p>To set up and use a sales tax hierarchy, you must be a member of a security role that includes the duties that are described in the following table:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable sales taxes process</strong></p></td>
<td><p>TaxSalesTaxesProcessEnable</p></td>
<td><p>Perform sales tax payments.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review sales taxes process performance</strong></p></td>
<td><p>TaxSalesTaxesProcessPerfReview</p></td>
<td><p>View the sales tax payment report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain sales tax transactions</strong></p></td>
<td><p>TaxSalesTaxTransactionsMaintain</p></td>
<td><p>Set up sales tax hierarchies.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up and use a sales tax hierarchy, you must be a member of a security role that includes the privileges that are described in the following table:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Settle sales taxes due</strong></p></td>
<td><p>TaxReportProcess</p></td>
<td><p>Perform sales tax payments.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain indirect tax transactions</strong></p></td>
<td><p>TaxIndirectTransactionMaintain_IN</p></td>
<td><p>Set up sales tax hierarchies.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View sales tax payments information</strong></p></td>
<td><p>TaxReportVoucherView</p></td>
<td><p>View sales tax payment reports.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

