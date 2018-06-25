---
title: About production parameters in Manufacturing execution
TOCTitle: About production parameters in Manufacturing execution
ms:assetid: 3a93e761-7fa5-47b3-8887-91a23e191eff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570152(v=AX.60)
ms:contentKeyID: 36056641
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- production
- manufacturing execution
---

# About production parameters in Manufacturing execution [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Manufacturing execution** module is primarily targeted at manufacturing companies. It can be used to register time and item consumption on production jobs or projects. Before you start to use the module for job registrations, you must first set up various production parameters that define how and when registrations are posted in the production process. Production parameter settings affect inventory management, production management, and cost calculation.

You should carefully consider all settings in the **Production parameters** form before workers start making registrations on production jobs. Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**. If your company uses the multisite functionality, you may want to set up different production parameters by site. For more information, see [Manufacturing execution production parameters (form)](https://technet.microsoft.com/en-us/library/hh208822\(v=ax.60\)).

The parameters for integrating to the **Production** module are set up on the following tabs in the **Production parameters** form:

  - **General** - General parameter settings for production jobs in **Manufacturing execution**.

  - **Start** - Parameters that are used when production operations are started.

  - **Operations** - Parameters that are applied to production operations and feedback on operations during the production process.

  - **Report as finished** - Parameters that are applied when items are reported as finished on the last operation of a production order.

  - **Quantity validation** - Parameters for validating start and feedback quantities on production orders.

## Types of production jobs

On the **Operations** tab, you select which types of production jobs require registration in the **Job registration** form.

Typically, workers make registrations on setup jobs and process jobs. But if job scheduling is applied, you can select other job types, for example transport jobs, on which workers must also make registrations when processing a production order.


> [!IMPORTANT]
> <P>Make sure that all relevant job types are selected. Otherwise, jobs may not be available for registration in the <STRONG>Job registration</STRONG> form. Align your selections with selections made in the <STRONG>Job management</STRONG> column in the <STRONG>Route groups</STRONG> form. Click <STRONG>Production control</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Routes</STRONG> &gt; <STRONG>Route groups</STRONG>. Then select the <STRONG>Setup</STRONG> tab.</P>



If **Job management** is selected on the route group, this job type will be reported as finished on the production order. This will occur when the job is reported as finished in **Manufacturing execution**. When all job types for which **Job management** is selected have been reported as finished on an operation, **Manufacturing execution** will also report the operation as finished.


> [!NOTE]
> <P>Some job types may be reported manually through production journals. If that is the case, select <STRONG>Job management</STRONG> for this job type, but do not select the job type for registration on the <STRONG>Operations</STRONG> tab in the <STRONG>Production parameters</STRONG> form in <STRONG>Manufacturing execution</STRONG>.</P>



## BOM consumption and picking list journals

It is important that the BOM consumption setup is consistent to make sure that inventory management is efficient. For example, if BOM consumption parameters are not set up correctly in **Manufacturing execution**, it may result in materials deducted from inventory two times or not at all.

In the **Production parameters** form, **Automatic BOM consumption** is set up in three stages:

  - At the start of a production. Set this up on the **Start** tab.

  - During the production process when an operation is completed. Set this up on the **Operations** tab.

  - When a production order is reported as finished. Set this up on the **Report as finished** tab.

For each of the three stages, there are three methods for picking items for a production order in the **Automatic BOM consumption** field:

1.  **Flushing principle** – This option is used in combination with an option defined in the BOM in the Production module. Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. From the **All production orders** form, select a production order from the list and in the **Action Pane**, click the **BOM** button. From the **BOM** form, click the **Setup** tab, **Flushing principle** field. The **Flushing principle** options in **Production** are as follows:
    
      - **Start**
    
      - **Finish**
    
      - **Manual**
    
      - Blank – No option is selected.
    
    In the **Manufacturing execution** module, if **Flushing principle** is selected on the **Start** tab in the **Automatic BOM consumption** field, it means that all materials set to the **Start** value in the BOM will be deducted from inventory when the operation is started.
    

    > [!NOTE]
    > <P>If the <STRONG>Flushing principle</STRONG> field is selected on the <STRONG>Start</STRONG> tab in <STRONG>Manufacturing execution</STRONG>, you must also select that same principle on either the <STRONG>Operations</STRONG> tab or the <STRONG>Report as finished</STRONG> tab. This is to make sure that materials are deducted from inventory on the BOMs that use <STRONG>Finish</STRONG> as a flushing principle on the production order. It is important that either the <STRONG>Operations</STRONG> tab or the <STRONG>Report as finished</STRONG> tab – contains the <STRONG>Flushing principle</STRONG> selection. This is to prevent materials from being deducted two times from inventory.</P>

    
    In the BOM, the deduction of materials from inventory is based on the value set on every item. This value is mandatory for all items created in Microsoft Dynamics AX. This occurs when the **Flushing principle** is set to “blank”, and you have selected **Flushing principle** on, for example, the **Start** tab and the **Operations** tab in the **Production parameters** form in **Manufacturing execution**.

2.  **Always** – If you select this option at a particular stage, materials are always deducted from inventory at that stage. For example, materials for the production will be deducted when the production order is started. This setting requires a “Never” selection on the **Operations** and **Report as finished** tabs. This will prevent items from being deducted two times from inventory.

3.  **Never** – This means no BOM consumption occurs at a particular stage. For example, if “Never” is selected on all three **Start**, **Operations**, and **Report as finished** tabs, materials must be deducted manually from inventory.


> [!IMPORTANT]
> <P>Carefully consider your production parameter setup and make sure that the parameters selected on different tabs in the <STRONG>Production parameters</STRONG> form do not contradict each other.</P>



The following examples illustrate parameter settings that support different BOM consumption principles. The parameters are set up in the **Production parameters** form in **Manufacturing execution**.

## Example 1 - Backflushing on operations

Use the following settings if picking list journals and BOM item consumption should be generated when items are reported as finished on an operation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab / Field</p></th>
<th><p>Setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Start</strong> /</p>
<p><strong>Update start on-line</strong></p></td>
<td><p><strong>Status</strong> or <strong>Status + quantity</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Start</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Operations</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Always</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Update finished report on-line</strong></p></td>
<td><p><strong>Status + quantity</strong></p></td>
</tr>
</tbody>
</table>


## Example 2 - Backflushing on production

Use the following settings if picking list journals and BOM item consumption should be generated when items are reported as finished on the production order.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab / Field</p></th>
<th><p>Setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Start</strong> /</p>
<p><strong>Update start on-line</strong></p></td>
<td><p><strong>Status</strong> or <strong>Status + quantity</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Start</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Operations</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Always</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Update finished report on-line</strong></p></td>
<td><p><strong>Status + quantity</strong></p></td>
</tr>
</tbody>
</table>


## Example 3 - Flushing principle

Use the following settings if picking list journals and BOM item consumption should be generated according to the flushing principle setting of the BOM items.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab / Field</p></th>
<th><p>Setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Start</strong> /</p>
<p><strong>Update start on-line</strong></p></td>
<td><p><strong>Status + quantity</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Start</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Flushing principle</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Operations</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Flushing principle</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Update finished report on-line</strong></p></td>
<td><p><strong>Status + quantity</strong></p></td>
</tr>
</tbody>
</table>


## Example 4 – Deducting materials during start-up of a production order

Use the following settings if picking list journals and BOM item consumption should be generated when a production is started.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab / Field</p></th>
<th><p>Setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Start</strong> /</p>
<p><strong>Update start on-line</strong></p></td>
<td><p><strong>Status + quantity</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Start</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Always</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Operations</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Update finished report on-line</strong></p></td>
<td><p><strong>Status</strong> or <strong>Status + quantity</strong></p></td>
</tr>
</tbody>
</table>

  
Based on the selections described earlier in this section, picking list journals are posted at various stages of the production order process:

  - When an operation is started.

  - When quantity feedback is reported on an operation.

  - When items are reported as finished on the production order.

## Example 5 – Manual BOM consumption

The following settings can be used if materials should always be deducted from inventory manually. In this case, picking list journals are not posted.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tab / Field</p></th>
<th><p>Setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Start</strong> /</p>
<p><strong>Update start on-line</strong></p></td>
<td><p><strong>Status</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Start</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Operations</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Automatic BOM consumption</strong></p></td>
<td><p><strong>Never</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Report as finished</strong> /</p>
<p><strong>Update finished report on-line</strong></p></td>
<td><p><strong>Status</strong></p></td>
</tr>
</tbody>
</table>


## See also

[Key tasks: Set up manufacturing execution](key-tasks-set-up-manufacturing-execution.md)

[About sites and the multisite functionality](about-sites-and-the-multisite-functionality.md)

[About production feedback](about-production-feedback.md)

[About job scheduling](about-job-scheduling.md)

[About operations scheduling](about-operations-scheduling.md)

[Create route groups](create-route-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

