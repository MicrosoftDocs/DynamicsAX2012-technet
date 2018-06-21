---
title: Tax information tasks
TOCTitle: Tax information tasks
ms:assetid: f51ff9cf-e7c8-4a08-91c3-26670ab19dac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677373(v=AX.60)
ms:contentKeyID: 49384149
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll tax
- payroll tax setup
- tax information
- tax setup
- Forms.PayrollEmployerTaxRegion
- payroll taxes
- Forms.PayrollTaxCode
- Forms.PayrollTaxRegion
- Forms.PayrollTaxGroup
- payroll tax information
- MsDynAx060.Forms.PayrollEmployerTaxRegion
- MsDynAx060.Forms.PayrollTaxCode
- MsDynAx060.Forms.PayrollTaxGroup
- MsDynAx060.Forms.PayrollTaxRegion
---

# Tax information tasks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to specify organization-wide settings for payroll taxes.

Payroll taxes are set up in two parts. The first part, which is described in this topic, covers the settings that are used throughout the organization, such as the states where you have a nexus, or the rates for unemployment taxes. The second part, which is described in [Worker and position payroll tasks](worker-and-position-payroll-tasks.md), covers the additional tax information that must be provided for each worker.

The following illustration shows the steps that are required to set up payroll taxes. The numbers correspond to the procedures later in this topic.

![Steps for setting up payroll tax information](images/JJ677373.Payroll_Set_up_tax_information(AX.60).gif "Steps for setting up payroll tax information")

For more information about payroll taxes, see [Tax codes, tax groups, and posting definitions](tax-codes-tax-groups-and-posting-definitions.md) and [Payroll data updates](payroll-data-updates.md).

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Set up tax data

2\. Set up employer tax regions for nexus

3\. Create tax regions

4\. Set up tax codes

5\. Optional: Set up tax groups

Next step

Technical information for system administrators

Find form help

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

Back to top

## Review the prerequisites

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2</p>
<p>Tax groups are not available prior to cumulative update 7 for AX 2012 R2.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


Back to top

## 1\. Set up tax data

To set up tax data, update the tax data to make tax codes and system-defined tax groups available. (Click **Payroll** \> **Setup** \> **Taxes** \> **Update tax data**.)

When you run the **Update tax data** process the first time, the full set of supported payroll taxes is loaded, and system-defined tax groups are automatically created. The supported taxes and system-defined tax groups are updated whenever you run the **Update tax data** process.

Each system-defined tax group contains tax codes of a particular type. For example, all tax codes for school districts are included in the SCHL tax group and all tax codes for state income tax are in the SIT tax group. If these system-defined tax groups meet your organization’s needs, you don’t have to create additional tax groups.

Back to top

## 2\. Set up employer tax regions for nexus

One of the most important factors in determining whether a legal entity must pay and withhold taxes in a state is whether the legal entity has a nexus, or a significant business presence, in that state. In Microsoft Dynamics AX, each state or territory where a legal entity has a nexus is defined as an employer tax region. Every legal entity must have at least one employer tax region. Legal entities that have a nexus in more than one state have multiple employer tax regions. These employer tax regions are used together with multiple-state taxation and reciprocity rules to determine when and where to withhold and pay taxes.


> [!IMPORTANT]
> <P>The question of whether a legal entity has a nexus in a particular state can be complex and difficult to answer. The determination is usually made by your legal advisors.</P>



To set up employer tax regions for a nexus, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Taxes** \> **Employer tax regions**.

2.  Click **New**.

3.  In the **State** column, select a state or territory where your organization has a nexus.

4.  When you first create an employer tax region, it is not active. Payroll taxes for the state or territory are not withheld. Select the check box in the **Active** column to withhold and pay payroll taxes according to the multiple-state taxation and reciprocity rules that apply.
    

    > [!NOTE]
    > <P>Clearing the <STRONG>Active</STRONG> check box has the same effect as deleting the tax region.</P>



Repeat these steps to add more states or territories where your organization has a nexus. When you are finished, close the form.

Back to top

## 3\. Create tax regions

*Tax regions* are geographic areas in which a specific set of payroll taxes applies. Tax regions generally correspond to the cities or towns where your workers reside or work. A *worker tax region* is a tax region that has been assigned to a specific worker. A *default tax region* is a worker tax region that is used to generate earnings for a specific position that the worker holds.

Before you begin, it is helpful to determine the county, state, and ZIP/postal code for each city that you identify as a tax region.

To create tax regions, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Taxes** \> **Tax regions**.

2.  Click **New** to open the **Tax region** form.
    
    To save time when you create tax regions, you can enter any part of the location information. For example, you can enter only the state or only the ZIP/postal code. If more than one tax region matches the location information that you entered, the **Multiple tax regions** form opens and displays a list of cities from which you can select the correct region.

3.  In the **Name or description** field, enter a name to use for this tax region. For example, you might enter CO Denver for Denver, Colorado.
    

    > [!TIP]
    > <P>If you include the name of the state as the first part of the tax region name, tax regions in the same state will be sorted together.</P>



4.  In the **ZIP/postal code** field, enter the ZIP code or postal code for this tax region. If you do not have the ZIP code, enter either the city or the county and the state in the appropriate fields.

5.  Click **OK**.
    
    If more than one tax region matches the location information that you entered, the **Multiple tax regions** form opens. Select the location for this tax region from the list, and then click **OK**.

Repeat these steps to create additional tax regions. When you are finished, close the form.

For information about how to assign tax regions to workers, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

Back to top

## 4\. Set up tax codes

You do not have to create tax codes. The codes for all payroll taxes that are supported by Microsoft Dynamics AX are provided for you. However, you must provide information about how your organization uses each tax code.

You can create as many versions of the data for each tax code as you need. Only one version can be in effect for a legal entity at any given time. The **Tax codes** form always displays the version that is currently in effect for the selected legal entity.

Tax codes are automatically assigned to workers based on their worker tax regions, position, and legal entity. You can then set up the worker tax code for each worker’s individual tax situation. For information about how to set up worker tax codes, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).


> [!IMPORTANT]
> <P>The following taxes are not supported by Microsoft Dynamics AX:</P>
> <UL>
> <LI>
> <P>Employer head taxes – Taxes that are not based on a payment, but that are calculated on the number of employees paid over a certain period of time.</P>
> <LI>
> <P>Employer percentage of payroll taxes – Taxes that are not calculated based on a payment, but that are calculated on the amount that is paid to employees over a certain period of time.</P>
> <LI>
> <P>RRTA taxes – The employee part of the Railroad Retirement tax.</P>
> <LI>
> <P>Employer RRTA taxes – The employer part of the Railroad Retirement tax.</P>
> <LI>
> <P>Employer RUIA taxes – Railroad unemployment taxes that are paid by the employer.</P>
> <LI>
> <P>SUTA surcharges – Although base state unemployment taxes are supported, individual surcharges aren’t calculated independently. You must increase the defined base SUTA rate to cover the calculation of any SUTA surcharges and list the amounts manually when you file.</P>
> <LI>
> <P>Ohio JEDD taxes – A type of local tax in the state of Ohio that is managed by the Joint Economic Development Districts.</P></LI></UL>
> <P>There might be other taxes that are not supported by Microsoft Dynamics AX. To verify whether a tax is supported, see the tax codes that are delivered with the system or contact product support. Because legislative changes can also change which taxes are supported, changes are noted in the release documentation for each tax update.</P>



To set up tax codes, follow these steps:

1.  Create a list of the payroll taxes to configure. For each tax, determine the following:
    
      - The legal entities that the tax applies to.
    
      - The main account to use for the tax.
    
      - The wage base, account ID, or rate, if the taxing authority has specified them. For example, unemployment taxes usually have a specified rate.
    
      - The reporting requirements for the tax for Form W-2.

2.  Click **Payroll** \> **Setup** \> **Taxes** \> **Tax codes**.

3.  Select a tax code to set up.
    
    The following information is built into the tax code and can’t be changed.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>More information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Tax code</strong></p>
    <p><strong>Description</strong></p>
    <p><strong>Country/region</strong></p></td>
    <td><p>The description is printed on pay statements and other reports. If this description should not be printed, enter a different description in the <strong>Report description</strong> field on the <strong>General</strong> tab.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Lock pay statement</strong></p></td>
    <td><p>If this check box is selected, tax lines that are related to this tax code can’t be modified on pay statements.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Employer tax</strong></p></td>
    <td><p>If this check box is selected, the tax is an employer tax that is paid by the employer. If this check box is cleared, the tax applies to the employee and is withheld from the employee’s gross pay.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Tax code details** FastTab, set up and select settings for each tax code that your organization uses. If a tax code is used by more than one legal entity in your organization, you must set up the tax code for each legal entity.
    

    > [!NOTE]
    > <P>For many tax codes, the fields on the <STRONG>General</STRONG> tab are blank. We recommend that you review all settings, which includes those on the <STRONG>Accounting</STRONG> tab, to verify that a tax code has been set up for a legal entity.</P>

    
    1.  Select the legal entity that the tax code applies to.
    
    2.  On the **General** tab, specify the following information.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Field</p></th>
        <th><p>Information</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p><strong>Report description</strong></p></td>
        <td><p>Optional: To overwrite the description of the tax code that appears on reports, such as printed pay statements, enter the new description here. To use the default description, leave this field blank.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Account ID</strong></p></td>
        <td><p>Enter the account number that the legal entity has with the taxing authority.</p>
        <p>State income taxes always have an account ID. If the taxing authority has not specified an account ID, leave this field blank.</p></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Wage base</strong></p></td>
        <td><p>Enter the value specified by the taxing authority.</p>
        <p>If the taxing authority does not specify a wage base, leave this field blank.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Rate</strong></p></td>
        <td><p>Enter the rate that the legal entity pays. For example, if the rate is 2.5 percent, enter 0.025.</p>
        <p>Unemployment taxes always have a specified rate. For other taxes, if the taxing authority has not specified a rate, leave this field blank.</p>
        <div class="alert">

        > [!WARNING]
        > <P>Although base state unemployment taxes are supported, individual surcharges aren’t calculated independently. You must increase the defined base SUTA rate to cover the calculation of any SUTA surcharges and list the amounts manually when you file.</P>


        </div></td>
        </tr>
        </tbody>
        </table>
    
    3.  On the **Accounting** tab, specify the following information.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th><p>Field</p></th>
        <th><p>Information</p></th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td><p><strong>Vendor</strong></p></td>
        <td><p>To automatically create invoices for the calculated tax amounts, , enter the agency that the tax is paid to.</p>
        <p>If you prefer to create tax invoices manually, leave this field blank.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Project category</strong></p></td>
        <td><p>If the tax code is used for employer tax transactions that are posted to a project instead of to the general ledger, select a project category.</p>
        <p>If a tax code must be posted to a project, you must specify a project category on the tax code line before you can generate a pay statement.</p>
        <div class="alert">

        > [!NOTE]
        > <P>This field is never used for taxes that are paid by the worker.</P>


        </div></td>
        </tr>
        <tr class="odd">
        <td><p><strong>Default financial dimensions</strong></p></td>
        <td><p>The default financial dimensions for the main account. When you select a financial dimension value, the <strong>Where the %1 dimension is used</strong> field group displays where the dimension is used in account structures and advanced rule structures.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Main account</strong></p></td>
        <td><p>Enter the main account that this tax will be posted to.</p>
        <p>For employer taxes, employer tax transaction costs are posted to the main account. For employee taxes, the withholding liability is posted to the main account. This account is used for all transactions that are related to this tax code and legal entity.</p></td>
        </tr>
        </tbody>
        </table>
    
    If the tax code is used by another legal entity, repeat this step for that legal entity.

5.  On the **Reporting** FastTab, enter any information that is required for boxes 10, 11, 12, or 14 of Form W-2.
    
    If the **Reporting** FastTab isn’t available, you might have to close the **Tax code details** FastTab.

Repeat these steps to set up additional tax codes. When you are finished, close the form.

Back to top

## 5\. Optional: Set up tax groups

You can use tax groups to help sort and select payroll taxes, and to update accounting data for all the tax codes in a tax group at the same time.

When you set up Payroll, a set of system-defined tax groups is automatically created the first time that you run the **Update tax data** process. System-defined tax groups are updated whenever you run that process. Each system-defined tax group contains tax codes of a particular type. For example, all tax codes for school districts are included in the SCHL tax group, and all tax codes for state income tax are in the SIT tax group. If these system-defined tax groups meet your organization’s needs, you don’t have to create additional tax groups.

However, if several tax codes share the same accounting data, you might want to put these tax codes in a single tax group. When you do this, if the vendor changes, you can use the tax group to change the vendor for all the tax codes in the group at the same time. This can save time and reduce the risk of errors.

To set up tax groups, follow these steps:

1.  Create a list of the tax codes to include in each tax group.
    
    In most cases, you will include all the tax codes that share the same accounting information in a single tax group. In addition, if a set of tax codes shares the same posting requirements, you can include them in a single tax group that you enable for posting definitions. A tax code can be included in multiple tax groups, as long as only one of the tax groups is enabled for posting definitions. For more information, see [Tax codes, tax groups, and posting definitions](tax-codes-tax-groups-and-posting-definitions.md).
    

    > [!TIP]
    > <P>You can set up the transaction posting definitions so that some tax codes in the group use a different posting definition than the rest of the tax codes in the group. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh242550(v=ax.60)">Transaction posting definitions (form)</A> or <A href="tax-codes-tax-groups-and-posting-definitions.md">Tax codes, tax groups, and posting definitions</A>.</P>



2.  Click **Payroll** \> **Setup** \> **Taxes** \> **Tax groups**.

3.  Click **New**, and then enter a name and description that identify the tax group.

4.  Click **Add** to open the **Add tax codes to a tax group** form.
    

    > [!NOTE]
    > <P>You can’t add tax codes to a system-defined tax group.</P>



5.  Select the tax codes to include in the tax group, and then click **Add**.
    
    A tax code can be included in multiple tax groups. In the **Tax codes** form, you can view the list of tax groups that include a specific tax code.

6.  Optional: If you plan to use this tax group in transaction posting definitions, select **Enable posting definitions**.
    
    Each tax code can be included in only one tax group that is enabled for posting definitions.

Repeat these steps to set up additional tax groups. When you are finished, close the form.

After you create tax groups that are enabled for posting definitions, you can assign those tax groups to transaction posting definitions. For more information, see [Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md) or [Transaction posting definitions (form)](https://technet.microsoft.com/en-us/library/hh242550\(v=ax.60\)).

Back to top

## Next step

The next step is to set up benefits and mandatory deductions. For more information, see [Benefit setup tasks](benefit-setup-tasks.md).

Back to top

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
<td><p><strong>Payroll - USA</strong></p>
<div class="alert">

> [!NOTE]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up payroll taxes, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Maintain payroll worker tax setup</strong> (PayrollWorkerTaxSetupMaintian)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up payroll taxes, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain payroll tax code versions</strong> (PayrollTaxCodeDateManagerMaintain)</p></li>
<li><p><strong>Maintain payroll tax codes</strong> (PayrollTaxCodeMaintain)</p></li>
<li><p><strong>Maintain payroll tax codes using mass update</strong> (PayrollTaxCodeMassUpdateMaintain)</p></li>
<li><p><strong>Maintain payroll tax codes in a tax group</strong> (PayrollTaxCodeSelectionMaintain)</p></li>
<li><p><strong>Maintain payroll tax groups</strong> (PayrollTaxGroupMaintain)</p></li>
<li><p><strong>Maintain payroll tax regions</strong> (PayrollTaxRegionMaintain)</p></li>
<li><p><strong>Update tax data</strong> (PayrollUpdateTaxDatMaintain)</p></li>
<li><p><strong>Maintain resident worker tax regions</strong> (PayrollWorkerResidentTaxRegionMaintain)</p></li>
<li><p><strong>Maintain worker tax codes</strong> (PayrollWorkerTaxCodeMaintain)</p></li>
<li><p><strong>Maintain worker tax code parameter versions</strong> (PayrollWorkerTaxCodeParamValDateMaintain)</p></li>
<li><p><strong>Maintain worker tax regions</strong> (PayrollWorkerTaxRegionMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Transaction posting definitions (form)](https://technet.microsoft.com/en-us/library/hh242550\(v=ax.60\))

## Find related tasks

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

[Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

