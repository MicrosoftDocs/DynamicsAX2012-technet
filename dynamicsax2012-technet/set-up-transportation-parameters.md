---
title: Set up transportation parameters
TOCTitle: Set up transportation parameters
ms:assetid: 528afd63-fbe2-4076-8b80-22b6aef65520
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553163(v=AX.60)
ms:contentKeyID: 62524895
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# Set up transportation parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Before you start using **Transportation management**, you can set up default values to reduce the data that must be entered when you perform transportation tasks. For example, you can create text for the default freight bill transaction that always appears on the journal line that is generated for freight bills.

This topic describes the parameter setup for tasks such as appointment scheduling, vendor invoicing, transit planning, inbound or outbound load processing, and shipping. You can also set up parameters for reports and unique number sequence codes.

## Set up general transportation parameters

1.  Click **Transportation management** \> **Setup** \> **Transportation management parameters**.

2.  In the **Transportation management parameters** form, click the **General** link.

The following table shows the general parameters that are on the FastTabs in the **Transportation management parameters** form.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>FastTab</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Default duration</strong></p></td>
<td><p><strong>Appointment scheduling</strong></p></td>
<td><p>The number of minutes for each appointment. You can change the default number of minutes depending on what the carrier will collect and deliver.</p></td>
</tr>
<tr class="even">
<td><p><strong>Alert interval</strong></p></td>
<td><p><strong>Driver check-in and check-out</strong></p></td>
<td><p>The number of minutes before an appointment alert.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Write vendor invoice journal</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>Select this check box if you want to apply freight reconciliation to pay vendors.</p>
<p>Clear this check box if you want to match the freight bill with the invoice amount in Microsoft Dynamics AX 2012, and then copy the results to a system outside AX 2012.</p></td>
</tr>
<tr class="even">
<td><p><strong>Post journal</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>Select this check box to automatically post the invoice journal after the invoice has been approved.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor journal name</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The journal name that is selected in <strong>General ledger</strong> under <strong>Setup</strong> &gt; <strong>Journals</strong> &gt; <strong>Journal names</strong>. This is the template where you maintain journal settings, such as posting restrictions, for selected users or user groups.</p></td>
</tr>
<tr class="even">
<td><p><strong>Freight bill transaction text</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The text that appears on the general ledger journal line that is generated for a freight bill.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor journal name</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The vendor journal name that is selected in <strong>General ledger</strong> under <strong>Setup</strong> &gt; <strong>Journals</strong> &gt; <strong>Journal names</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Default note type</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The note type that is used for invoice line reconciliation.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Automatically match and pay the freight invoice</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>Select this check box to have the freight bill automatically matched with the invoice amount and paid to the vendor.</p>
<p>Clear this check box if you must manually complete the matching and payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Match interval</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The number of seconds between searches when matching freight invoices and invoice journal lines.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Enable invoice workflow</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>Select this check box to process the vendor invoice through a workflow approval process when the invoice is submitted for approval. You can create workflows for vendor invoicing in <strong>Accounts payable</strong> in the <strong>Accounts payable workflows</strong> form under <strong>Setup</strong>. The invoice process uses a workflow of the type <strong>Vendor invoice workflow</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Workflow user</strong></p></td>
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>The user who can process the vendor invoice workflow.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Port hub type</strong></p></td>
<td><p><strong>Hub type</strong></p></td>
<td><p>The type of hub master that is associated with the accessorial assignment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Plan by shipment</strong></p></td>
<td><p><strong>Shipment</strong></p></td>
<td><p>Select this check box to plan by shipment. You can plan by load or by shipment. Planning by shipment is more detailed than planning by load.</p>
<p>Clear this check box to plan by load.</p></td>
</tr>
<tr class="odd">
<td><p><strong>In transit planning</strong></p></td>
<td><p><strong>In transit planning</strong></p></td>
<td><p>Select this check box to enable dynamic route planning where any segment of a route can be assigned a distinct route.</p></td>
</tr>
<tr class="even">
<td><p><strong>Automatically create at sales order entry</strong></p></td>
<td><p><strong>Loads</strong></p></td>
<td><p>Select this check box to automatically create a load when you create a sales order line.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Automatically create at purchase order entry</strong></p></td>
<td><p><strong>Loads</strong></p></td>
<td><p>Select this check box to automatically create a load when you create a purchase order line.</p></td>
</tr>
<tr class="even">
<td><p><strong>Automatically create at transfer order entry</strong></p></td>
<td><p><strong>Loads</strong></p></td>
<td><p>Select this check box to automatically create a load when you create a transfer order entry.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Override outbound shipped confirmation date</strong></p></td>
<td><p><strong>Loads</strong></p></td>
<td><p>Select this check box to override the outbound ship confirm date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Create customer charges for direct delivery</strong></p></td>
<td><p><strong>Direct delivery</strong></p></td>
<td><p>Select this check box to create customer charges when you rate the load.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Initialize base engine data</strong></p></td>
<td><p><strong>Engines</strong></p></td>
<td><p>Click <strong>Initialize base engine data</strong> to run a data initialization job for the base engine.</p></td>
</tr>
<tr class="even">
<td><p><strong>Enable freight reconciliation</strong></p></td>
<td><p><strong>Freight reconciliation</strong></p></td>
<td><p>Select this checkbox to enable the use of freight reconciliation. Clear this box if you are not using freight reconciliation and do not want freight bills to be created.</p>
<div>

> [!NOTE]
> <P>This parameter is included in Microsoft Dynamics AX 2012 R3 Cumulative Update 9.</P>


</div></td>
</tr>
</tbody>
</table>


## Set up parameters for reports and number sequences

Use the **Reports** and **Number sequences** tabs to set up the following information:

  - A note type that will be the default for load reports.

  - The type of load that the report applies to.

  - Number sequences for documents, such as internal invoices and transportation orders.

<!-- end list -->

1.  In the left pane, click **Reports**.

2.  On the **Load report** FastTab, in the **Load report note type** field, select the default document type to be printed on the load report.

3.  On the **Bill of lading** FastTab, in the **Carrier purpose** field, select the carrier purpose to be printed on the bill of lading (BOL).

4.  In the left pane, click **Number sequences**, and then select unique number sequence codes for the items in the list.

## Related tasks

[Create or modify an inbound load](create-or-modify-an-inbound-load.md)

[Plan appointments for a load](plan-appointments-for-a-load.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>


## See also

[Generate a freight invoice and perform freight reconciliation](generate-a-freight-invoice-and-perform-freight-reconciliation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

