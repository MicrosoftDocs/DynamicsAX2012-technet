---
title: About Lean manufacturing migration
TOCTitle: About Lean manufacturing migration
ms:assetid: 14304458-7557-4e3f-97a9-db7365c4ad05
ms:mtpsurl: https://technet.microsoft.com/library/Gg188980(v=AX.60)
ms:contentKeyID: 35410559
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- lean manufacturing upgrade
- upgrade lean manufacturing
- migrate lean manufacturing data
- upgrade lean
---

# About Lean manufacturing migration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the migration scenario for Microsoft Dynamics AX 2012 Lean manufacturing. There is a new data model, so there is no code upgrade needed. However, before you upgrade to Microsoft Dynamics AX 2012, you must migrate the Lean manufacturing for Microsoft Dynamics AX 2009 data to the new model. This scenario requires that you complete the following pre-upgrade tasks:

1.  Create the Microsoft Dynamics AX 2012 Lean manufacturing framework and set up the necessary base data.

2.  Prepare the current version data for migration to the Microsoft Dynamics AX 2012 Lean manufacturing framework.

You perform these tasks in the following forms:

  - **Convert kanbans to next version kanban rules** form – Use this form to convert the current version kanban rules to the next version. To open the form, click **Preprocessing upgrade checklist** \> **Prepare application data for preprocessing** \> **Prepare kanbans for migration**. See [Convert kanbans to next version kanban rules (form)](https://technet.microsoft.com/library/hh202074\(v=ax.60\)) for more information.

  - **Convert LOS-BTO schedules to next version kanban rules** form – Use this form to convert the current version LOS schedules to the next version. To open the form, click **Preprocessing upgrade checklist** \> **Prepare application data for preprocessing** \> **Prepare LOS schedules for migration**. See [Convert LOS-BTO schedules to next version kanban rules (form)](https://technet.microsoft.com/library/hh202116\(v=ax.60\)) for more information.

## Create the Lean manufacturing framework

The Microsoft Dynamics AX 2012 Lean manufacturing data structures consist of production flows and production flow activities. To create these and set up the associated data, complete the following tasks. In the **Convert kanbans to next version kanban rules** form, or alternatively, in the **Convert LOS-BTO schedules to next version kanban rules** form, click **Next version base data**, and then select the appropriate form.

  - In the **Production flow model** form, create and configure production flow models. These models define: the capacity settings for work cells and the display settings that are used in the kanban boards. See [Production flow model upgrade (form)](https://technet.microsoft.com/library/hh202123\(v=ax.60\)) for more information.

  - In the **Lean manufacturing next version value streams** form, define the value streams that are used to classify and aggregate lean financial transactions. Each new production flow references a value stream. During the upgrade process, the value streams are converted to operating units. See [Lean manufacturing next version value streams (form)](https://technet.microsoft.com/library/hh202037\(v=ax.60\)) for more information.

  - In the **Standard workdays for calendar** form, define the length of a standard work day, in hours, for the current calendars. To measure work cell capacity in periods that consist of hours and minutes, you must define this in the calendars. See [Standard work days for calendar (form)](https://technet.microsoft.com/library/hh202046\(v=ax.60\)) for more information.

  - In the **Work cells migration** form, define additional settings for current work cells that are to be upgraded. The additional, mandatory settings to define are as follows: input warehouse and location, output warehouse and location, and production flow model. See [Work cells migration (form)](https://technet.microsoft.com/library/hh202084\(v=ax.60\)) for more information.

  - In the **Production flows** form, create production flows and production flow activities that identify and describe your company’s basic business processes and product families. You can define process activities and you can define transfer activities. Create activity relations to link activities and establish a production flow sequence. See [Production flows upgrade (form)](https://technet.microsoft.com/library/hh202104\(v=ax.60\)) for more information.

  - In the **Lean manufacturing next version parameters** form, define the additional production parameters for Lean manufacturing. These parameters are used to create production flows and generate kanban jobs during the upgrade process. See [Lean manufacturing next version parameters (form)](https://technet.microsoft.com/library/hh202114\(v=ax.60\)) for more information.

  - In the **Lean schedule groups** form, define the lean schedule groups that are used to aggregate items for production at a particular work cell. See [Lean schedule groups upgrade (form)](https://technet.microsoft.com/library/hh202110\(v=ax.60\)) for more information.

## Prepare the current version data for migration

When the Microsoft Dynamics AX 2012 Lean manufacturing framework is created and the base data is set up, you prepare the current version data for migration to the next version. Use the **Convert kanbans to next version kanban rules** form to prepare the current version kanban rules. Alternatively, use the **Convert LOS-BTO schedules to next version kanban rules** form to prepare the current version LOS-BTO schedules.

Review the current rules and map them to the Microsoft Dynamics AX 2012 Lean manufacturing framework. The following table gives an overview of the core concepts in Lean manufacturing for Microsoft Dynamics AX 2009 and the corresponding concepts in Microsoft Dynamics AX 2012 Lean manufacturing. Use this information to guide you when you map the current kanban rules.

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
<th><p>Microsoft Dynamics AX 2009 feature</p></th>
<th><p>Microsoft Dynamics AX 2012 feature</p></th>
<th><p>Conversion of business rules</p></th>
<th><p>Conversion of active transactions</p></th>
<th><p>Conversion of handling units</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fixed quantity kanban</p></td>
<td><p>Fixed quantity kanban</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="even">
<td><p>Subcontracting kanban</p></td>
<td><p>Fixed or scheduled kanban</p></td>
<td><p>Convert to manufacturing kanban</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="odd">
<td><p>Purchase kanban</p></td>
<td><p>Withdrawal kanban from a warehouse location that has the item coverage type, Purchase order</p></td>
<td><p>Convert to withdrawal kanban</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="even">
<td><p>PTO (pull-to-order) kanban</p>
<ul>
<li><p>Sales</p></li>
<li><p>Kanban</p></li>
</ul></td>
<td><p>Event kanban</p>
<ul>
<li><p>Sales event</p></li>
<li><p>Kanban line</p></li>
</ul></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="odd">
<td><p>Target kanban</p></td>
<td><p>Scheduled kanban</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="even">
<td><p>Phased target kanban</p></td>
<td><p>Scheduled kanban</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
</tr>
<tr class="odd">
<td><p>Family grouping and item grouping</p></td>
<td><p>Item allocation key</p></td>
<td><p>Supported</p></td>
<td><p>Not applicable</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="even">
<td><p>Family grouping and item grouping</p></td>
<td><p>Lean schedule group</p></td>
<td><p>Supported</p></td>
<td><p>Not applicable</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="odd">
<td><p>Kanban group code</p></td>
<td><p>Kanban card number sequence</p></td>
<td><p>Supported</p></td>
<td><p>Not applicable</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="even">
<td><p>Kanban template</p></td>
<td><p>All kanban types</p></td>
<td><p>Through item allocation key</p></td>
<td><p>As kanban type</p></td>
<td><p>As kanban type</p></td>
</tr>
<tr class="odd">
<td><p>Generic kanban</p></td>
<td><p>Not applicable. Use the Product configurator for configurable items.</p></td>
<td><p>Upgraded as a normal kanban rule without extended data.</p></td>
<td><p>Kanban is upgraded as normal fixed quantity kanban.</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="even">
<td><p>LOS – BTO schedule</p>
<ul>
<li><p>First level</p></li>
<li><p>Level 2-n</p></li>
</ul></td>
<td><p>Event kanban</p>
<ul>
<li><p>Sales event kanban</p></li>
<li><p>Kanban line event</p></li>
</ul></td>
<td><p>Supported</p></td>
<td><p>Supported</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="odd">
<td><p>LOS cumulative schedule</p></td>
<td><p>Production schedule and <strong>Supply schedule</strong> form</p></td>
<td><p>No specific setup is required to use the <strong>Supply schedule</strong> form and work with planned orders</p></td>
<td><p>Not applicable. The schedule is established during the next master planning run.</p></td>
<td><p>Not applicable</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>During the bulk upgrade process, the Microsoft Dynamics AX 2012 Lean manufacturing kanban rules are generated.</P>



## See also

[Production flow model upgrade (form)](https://technet.microsoft.com/library/hh202123\(v=ax.60\))

[Lean manufacturing next version value streams (form)](https://technet.microsoft.com/library/hh202037\(v=ax.60\))

[Standard work days for calendar (form)](https://technet.microsoft.com/library/hh202046\(v=ax.60\))

[Work cells migration (form)](https://technet.microsoft.com/library/hh202084\(v=ax.60\))

[Production flows upgrade (form)](https://technet.microsoft.com/library/hh202104\(v=ax.60\))

[Lean manufacturing next version parameters (form)](https://technet.microsoft.com/library/hh202114\(v=ax.60\))

[Lean schedule groups upgrade (form)](https://technet.microsoft.com/library/hh202110\(v=ax.60\))

[Convert kanbans to next version kanban rules (form)](https://technet.microsoft.com/library/hh202074\(v=ax.60\))

[Convert LOS-BTO schedules to next version kanban rules (form)](https://technet.microsoft.com/library/hh202116\(v=ax.60\))

  


