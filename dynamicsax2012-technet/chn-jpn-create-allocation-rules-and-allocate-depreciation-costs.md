---
title: (CHN, JPN) Create allocation rules and allocate depreciation costs
TOCTitle: (CHN, JPN) Create allocation rules and allocate depreciation costs
ms:assetid: c90c3c2f-6a62-4020-8e5f-f2fa8e74bcd1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn269134(v=AX.60)
ms:contentKeyID: 54920086
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Rule
- Forms.AssetPosting
- Fixed assets
- Forms.LedgerJournalTable
- Depreciation
- Forms.AssetAllocationRuleSetup_CN
- Allocation rule
- Depreciation cost
- Depreciation expense
audience: Application User
ms.search.region: China (PRC)
---

# (CHN, JPN) Create allocation rules and allocate depreciation costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Microsoft Dynamics AX to set up an allocation rule to allocate the depreciation cost of a fixed asset to multiple cost accounts instead of the main cost account of your legal entity. An allocation rule can determine the percentage of the depreciation cost to assign to a cost account, and which cost account this percentage is assigned to. When you depreciate a fixed asset that is put into service for multiple operation units, such as departments or cost centers, Microsoft Dynamics AX can use the allocation rule to automatically calculate and allocate percentages of the depreciation cost to the individual cost accounts of the operation units


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
<td><p><strong>Company information</strong></p></td>
<td><p>Ensure that you have created a legal entity record for your organization. For more information, see <a href="create-or-modify-a-legal-entity.md">Create or modify a legal entity</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounting</strong></p></td>
<td><p>Create ledger accounts that the depreciation costs for operation units must be posted to. For more information, see <a href="about-main-accounts-for-fixed-assets.md">About main accounts for fixed assets</a> and <a href="https://technet.microsoft.com/en-us/library/hh209695(v=ax.60)">Main accounts - chart of accounts (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up value models for the fixed assets that you want to depreciate. For more information, see <a href="set-up-value-models.md">Set up value models</a> and <a href="https://technet.microsoft.com/en-us/library/aa590830(v=ax.60)">Value models (form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up allocation rules

You can use Microsoft Dynamics AX to create allocation rules that are used to calculate and allocate a percentage of the total depreciation cost of a fixed asset. You can also specify ledger accounts to which the depreciation costs can be posted.

To create the allocation rules, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset allocation rules**.

2.  Create an allocation rule.

3.  In the **Rule Id** field, enter an identification code for the allocation rule.

4.  In the **Description** field, enter a description for the allocation rule.

5.  On the **Allocation rules** FastTab, in the **Dimension name** field, select the type of operating unit that you want to allocate the depreciation cost percentage to, and click **Add**.
    

    > [!NOTE]
    > <P>The dimension name that you select determines the field name that is displayed in the Asset allocation rule line table. For example, if you select CostCenter, the CostCenter field is displayed in the allocation table.</P>



6.  In the **Percentage** field, enter the percentage of the depreciation cost to allocate to the operation unit.

7.  In the **Offset account** field, select the cost account that the depreciation cost must be posted to. You can assign this allocation rule to a fixed asset posting profile.

By assigning an allocation rule to a fixed asset posting profile, you enable Microsoft Dynamics AX to determine which fixed asset uses the parameters of the allocation rule that you set up. You can assign an allocation rule to a fixed asset posting profile of type **Depreciation** or **Extraordinary depreciation**.

To assign an allocation rule to a fixed asset posting profile, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Create a fixed asset posting profile or select an existing posting profile of type **Depreciation** or **Extraordinary depreciation**. For more information, see [Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md) and [Fixed asset posting profiles (form)](https://technet.microsoft.com/en-us/library/aa571467\(v=ax.60\)).

3.  Select the **Depreciation** check box, then on the **Allocation rules** FastTab, in the **Asset allocation rule for depreciation** field, select the allocation rule that you created.
    
    –or–
    
    Select the **Extraordinary depreciation** check box, then on the **Allocation rules** FastTab, in the **Asset allocation rule for extraordinary depreciation** field, select the allocation rule that you created.

## 2\. Calculate and allocate depreciation costs

You have set up allocation rules and assigned them to a fixed asset posting profile. When you post the fixed asset journal voucher, and when the depreciation proposal takes effect, the depreciation costs are calculated and allocated to the operation unit cost accounts.

To calculate and allocate depreciation costs, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Select or create a journal, and then click **Lines**.

3.  In the **Journal voucher** form, click **Proposals**, and then click **Depreciation proposal** to open the **Depreciation proposal** form.

4.  Select the criteria to create the depreciation proposal, and then click **OK**. For more information, see [Post fixed asset journals](post-fixed-asset-journals.md).


> [!NOTE]
> <P>You can also use the allocation rules for consumption depreciation proposals and extraordinary depreciation proposals.</P>



## Related tasks

[Create a fixed asset](create-a-fixed-asset.md)

[(CHN, JPN) Allocation rules for fixed assets](chn-jpn-allocation-rules-for-fixed-assets.md)

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
<td><ol>
<li><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>.</p></li>
<li><p>Select the <strong>Fixed assets</strong> and <strong>Fixed asset depreciation books</strong> configuration keys.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Accounting supervisor, accounting manager, accountant</p></td>
</tr>
</tbody>
</table>


## See also

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

  


