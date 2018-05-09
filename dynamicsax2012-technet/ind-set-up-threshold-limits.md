---
title: (IND) Set up threshold limits
TOCTitle: (IND) Set up threshold limits
ms:assetid: 817d5e6c-bc8c-4232-b7c4-49cbef58ff9d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527716(v=AX.60)
ms:contentKeyID: 59626289
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- India
- calculate tax
- Forms.ThresholdReference_IN
- Forms.ThresholdDesigner_IN
- Forms.Threshold_IN
- concession certificate
- concession certificates
- tax threshold
- threshold hierarchies
- threshold
- threshold hierarchy
- thresholds
- threshold limits
- threshold value
- threshold values
- threshold limit
- calculate taxes
- tax calculation
- tax calculations
- MsDynAx060.Forms.ThresholdReference_IN
- MsDynAx060.Forms.ThresholdDesigner_IN
- MsDynAx060.Forms.Threshold_IN
---

# (IND) Set up threshold limits 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can set up thresholds and concession certificates for direct tax calculations, you must create threshold definitions and set up threshold hierarchies. Follow the steps in this topic to set up threshold limits.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## This task is part of a bigger process

The following illustration shows how threshold limits setup relates to direct tax calculation tasks.

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
</tbody>
</table>


## Set up a threshold definition

Use the **Threshold definitions** form to create a threshold definition or a copy of an existing threshold definition. You can also view the list of referencing entities that use the selected threshold.

To set up a threshold definition, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Threshold definitions**.

2.  To create a new threshold definition, follow these steps:
    
    1.  Click **New** or press CTRL+N to create a threshold definition record.
    
    2.  In the **Name** and the **Description** fields, enter a name and a description for the threshold definition record.
    
    –or–
    
    To create a copy of an existing threshold definition, follow these steps:
    
    1.  Select a threshold to copy, and then click **Copy threshold** to create a copy of the threshold definition record.
    
    2.  In the **Name** and the **Description** fields, enter a name and a description for the copied threshold definition record.

You can click **Referenced by** to open the **Threshold reference list** form, where you can view the list of referencing entities that use the selected threshold.


> [!NOTE]
> <P>You can’t delete a threshold definition that is currently referenced by an entity. You must delete the threshold from all of the referencing entities before you delete the threshold.</P>



## Design the threshold hierarchy structure

Use the **Threshold designer** form to create a hierarchy structure for a threshold definition. You can design a hierarchy structure in the following ways:

  - **Single threshold hierarchy** – This structure contains a single threshold segment.

  - **Progressive threshold hierarchy** – This structure contains multiple threshold segments. You can specify multiple segments in a single level or in multiple levels. For example, you can create a threshold hierarchy structure with the following segments.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Segment</p></th>
    <th><p>Minimum value</p></th>
    <th><p>Maximum value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Segment one</p></td>
    <td><p>0</p></td>
    <td><p>1,00,000</p></td>
    </tr>
    <tr class="even">
    <td><p>Segment two</p></td>
    <td><p>1,00,000</p></td>
    <td><p>5,00,000</p></td>
    </tr>
    <tr class="odd">
    <td><p>Segment three</p></td>
    <td><p>5,00,000</p></td>
    <td><p>-</p></td>
    </tr>
    </tbody>
    </table>


To design a hierarchy structure for a threshold definition, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Threshold definitions**.

2.  Select the threshold definition to design the threshold hierarchy for, and then click **Threshold designer**.

3.  In the **Threshold designer** form, select the node to create the segment for, and then click **New** or press CTRL+N to create a threshold segment.

4.  In the **Effective from** field, select the date from which the threshold values are effective.

5.  In the **Effective to** field, select the date until which the threshold values are effective.

6.  In the **Lower limit** and **Upper limit** fields, select the starting and ending points of the threshold segment.

7.  In the **Type** field, select the type of threshold to apply to the selected segment.
    
    Use the following table to decide what type of threshold to apply to the selected threshold.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Cumulative</strong></p></td>
    <td><p>Select this option to apply the threshold segment to cumulative transaction values.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Per transaction</strong></p></td>
    <td><p>Select this option to apply the threshold segment to individual transaction values.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Per transaction line</strong></p></td>
    <td><p>Select this option to apply the threshold segment to individual transaction line values.</p></td>
    </tr>
    </tbody>
    </table>
    
    You must specify different calculation methods for overlapping date ranges and overlapping limit ranges for threshold segments at the same hierarchy level.

8.  If the selected segment is the final level in the threshold structural hierarchy, select the **Final level** check box.

9.  Repeat steps 3 through 8 to create additional segments.


> [!NOTE]
> <P>You can't delete a parent segment for a threshold hierarchy that has child segments. You must delete the child sections before you can delete the parent.</P>



## Next step

You have finished setting up threshold limits. Continue to set up thresholds and concession certificates for tax calculations. For more information, see [(IND) Set up thresholds and concession certificates for tax calculations](ind-set-up-thresholds-and-concession-certificates-for-tax-calculations.md).

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
<td><p>To set up threshold limits, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable sales taxes process</strong> (TaxSalesTaxesProcessEnable)</p></li>
<li><p><strong>Inquire into sales tax process reference data</strong> (TaxSalesTaxProcessReferenceDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up threshold limits, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain withholding tax codes</strong> (TaxWithholdTableMaintain)</p></li>
<li><p><strong>View withholding tax codes</strong> (TaxWithholdTableView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

