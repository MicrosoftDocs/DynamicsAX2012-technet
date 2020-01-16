---
title: About maintaining estimates
TOCTitle: About maintaining estimates
ms:assetid: 7a3ffcbc-545a-4e1b-a4e8-2dc977015d50
ms:mtpsurl: https://technet.microsoft.com/library/Aa550068(v=AX.60)
ms:contentKeyID: 36058247
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- estimate project
- completion method
- cost to complete
- maintain estimate
- estimate
audience: Application User
ms.search.region: Global
---

# About maintaining estimates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Estimates are maintained on individual Estimate projects or on batches of Estimate projects. When Estimate projects are processed in batches by using periodic jobs, the Estimate projects that are selected for processing are grouped by period code.

You can work with estimates in the following ways:

  - To maintain estimates for individual Estimate projects, use the **Estimate** form. Depending on your version of the program, follow one of these steps:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a Fixed-price or Investment project that is associated with an Estimate project. On the **Action Pane**, in the **Related information** group, click **Estimates**.
    
      - Otherwise: Click **Project management and accounting** \> **Common** \> **Projects** \> **Estimate projects**. Select an Estimate project. On the **Action Pane**, in the **Related information** group, click **Estimates**.

  - To view the periodic features that are available for estimate maintenance, click **Project management and accounting** \> **Periodic** \> **Estimates**. The periodic jobs that are available correspond to the functions that are available in the **Estimate** form.

The **New**, **Calculate**, **Delete**, **Post**, **Reverse**, **Eliminate**, and **Reverse elimination** buttons in the **Estimate** form open dialog boxes that reflect the typical life cycle of an estimate. The following table contains information about the fields in these dialog boxes.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Description</p></th>
<th><p>Available in these dialog boxes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Period code</strong></p></td>
<td><p>The code that determines how frequently estimates are posted. A period code is defined for each Estimate project.</p></td>
<td><p>All dialog boxes</p></td>
</tr>
<tr class="even">
<td><p><strong>Estimate date</strong></p></td>
<td><p>The date on which the estimate is processed.</p></td>
<td><p>All dialog boxes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Continuous</strong></p></td>
<td><p>Select this check box to create estimates only if estimates were posted in the previous period, or if the estimate is the first estimate that has been created.</p>
<p>If this check box is not selected, estimates are created even if estimates were not posted in the previous period.</p></td>
<td><p><strong>Create estimate</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Cost to complete method</strong></p></td>
<td><p>Define how you want to estimate the remaining work on the project.</p></td>
<td><p><strong>Create estimate</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Completion method</strong></p></td>
<td><p>Select a completion method. The following options are available:</p>
<ul>
<li><p><strong>Automatic</strong> – The completion percentage is calculated automatically, based on the cost lines that are included in the calculation. The cost template defines the cost lines that are included.</p></li>
<li><p><strong>Manual</strong> – The completion percentage equals the completion percentage of the last estimate. After the estimate is created, you can change the <strong>Manual calculation</strong> field in the <strong>Estimates</strong> form.</p></li>
<li><p><strong>From cost template</strong> – A combination of the <strong>Automatic</strong> method and the <strong>Manual</strong> method. This option is set automatically or manually, depending on the default value in the cost template.</p></li>
</ul></td>
<td><p><strong>Create estimate</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Forecast model</strong></p></td>
<td><p>Select a forecast model for the estimate.</p>
<p>Forecast models apply to the Forecasting and As previous estimate cost to complete methods.</p></td>
<td><p><strong>Create estimate</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Copy from model</strong></p></td>
<td><p>Optionally select a forecast model to copy.</p></td>
<td><p><strong>Create estimate</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Update cost estimate</strong></p></td>
<td><p>Select this option if you want the estimate calculation to include hour, expense, on-account, and item transactions that were posted after the estimate was created. The estimate date is also registered for each of these transactions.</p></td>
<td><p><strong>Calculate estimate</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Delete forecast</strong></p></td>
<td><p>Select this option to delete forecast transactions if the estimate is deleted or reversed.</p></td>
<td><p><strong>Delete estimate</strong></p>
<p><strong>Reverse estimate</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Posting date</strong></p></td>
<td><p>The date when transactions are posted to the general ledger.</p></td>
<td><p><strong>Post estimate</strong></p>
<p><strong>Reverse estimate</strong></p>
<p><strong>Eliminate estimate</strong></p>
<p><strong>Reverse elimination</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Set stage to Finished</strong></p></td>
<td><p>Select this check box to set the project stage for all projects that are attached to the current Estimate project to <strong>Finished</strong>.</p></td>
<td><p><strong>Eliminate estimate</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Set stage to In process</strong></p></td>
<td><p>Select this check box to set the project stage for all projects that are attached to the current Estimate project to <strong>In process</strong>.</p></td>
<td><p><strong>Reverse elimination</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Print estimate list</strong></p></td>
<td><p>Create an estimate list, and display it on the screen. The list contains the status of the current function. You can optionally print any warnings about the estimate on the report.</p>
<p>The following options are available:</p>
<ul>
<li><p><strong>Nothing to print</strong> – No report is created, and nothing is displayed.</p></li>
<li><p><strong>Exclude warnings</strong> – A report is created, but no warnings are displayed.</p></li>
<li><p><strong>Include warnings</strong> – A report is created, and warnings are displayed.</p></li>
<li><p><strong>Only warnings</strong> – A report is created, but only warnings are displayed.</p></li>
</ul>
<p>The following conditions cause warnings to appear in the estimate list:</p>
<ul>
<li><p>A completion percentage is more than 100 percent.</p></li>
<li><p>A completion percentage is less than 0 percent.</p></li>
<li><p>A negative amount appears in the <strong>To complete</strong> column.</p></li>
<li><p>An estimate has been created that has no corresponding contract amount.</p></li>
<li><p>An estimate has been created that has no cost estimate attached.</p></li>
</ul></td>
<td><p>All dialog boxes</p></td>
</tr>
<tr class="even">
<td><p><strong>Show Infolog</strong></p></td>
<td><p>Select this option to receive a message that contains information about the Estimate projects that were processed when the job was run.</p></td>
<td><p>All dialog boxes</p></td>
</tr>
</tbody>
</table>


## See also

[About methods for calculating the cost to complete a project](about-methods-for-calculating-the-cost-to-complete-a-project.md)

[Estimate projects (form)](https://technet.microsoft.com/library/aa599196\(v=ax.60\))

[Estimate (form)](https://technet.microsoft.com/library/aa590971\(v=ax.60\))

[Calculate estimate (class form)](https://technet.microsoft.com/library/aa577136\(v=ax.60\))

[Create estimate (class form)](https://technet.microsoft.com/library/aa553468\(v=ax.60\))

[Delete estimate (class form)](https://technet.microsoft.com/library/aa556177\(v=ax.60\))

[Eliminate estimate (class form)](https://technet.microsoft.com/library/aa573041\(v=ax.60\))

[Post estimate (class form)](https://technet.microsoft.com/library/aa619839\(v=ax.60\))

[Reverse estimate (class form)](https://technet.microsoft.com/library/aa597252\(v=ax.60\))

  


