---
title: Generate a freight invoice and perform freight reconciliation
TOCTitle: Generate a freight invoice and perform freight reconciliation
ms:assetid: 9dc5d9ed-2bc5-4e54-80da-d35362546ff0
ms:mtpsurl: https://technet.microsoft.com/library/Dn770234(v=AX.60)
ms:contentKeyID: 62524896
author: Khairunj
ms.date: 06/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Generate a freight invoice and perform freight reconciliation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to match freight bills with freight invoices, and how to perform reconciliation if there are any differences between these documents.

You can generate a freight invoice from freight bills, and update the generated freight invoice with the details from the carrier invoice that is received from a freight vendor. Use the following tasks to match or reconcile freight invoices:

  - Match the updated invoice lines with freight bills.

  - Reconcile the unmatched invoice lines with a reconciliation reason code.

  - Submit the invoice lines for payment approval.

You can discard unmatched freight bills or freight bills that do not have a carrier invoice. These freight bills are discarded with a reconciliation reason code.

The following illustration shows how to generate a freight invoice and perform freight reconciliation.

![Process flow for freight reconciliation](images/Dn770234.Processflowforfreightreconciliation(AX.60).jpg "Process flow for freight reconciliation")

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
<td><p>Precondition</p></td>
<td><ul>
<li><p>Set up freight bill types, freight bill type assignments, and reconciliation reason codes for freight reconciliation. For more information, see <a href="set-up-freight-reconciliation-parameters.md">Set up freight reconciliation parameters</a>.</p></li>
<li><p>In the <strong>Transportation management parameters</strong> form, select the <strong>Enable invoice workflow</strong> check box to process the vendor invoice through a workflow approval when the invoice is submitted for approval.</p></li>
<li><p>Create or modify an outbound or inbound load for shipping. For more information, see <a href="create-or-modify-an-outbound-load.md">Create or modify an outbound load</a> and <a href="create-or-modify-an-inbound-load.md">Create or modify an inbound load</a>.</p></li>
<li><p>Set up the rate and route for a load to generate a freight bill. For more information, see <a href="assign-a-rate-and-route-to-a-load.md">Assign a rate and route to a load</a>.</p></li>
<li><p>In the <strong>Transportation management parameters</strong> form, clear the <strong>Automatically match and pay the freight invoice</strong> check box to manually match or reconcile the freight invoice.</p></li>
<li><p>Set the tolerance limits to approve or reject the freight invoice during automatic freight reconciliation. For more information, see <a href="set-up-an-audit-master-for-freight-reconciliation.md">Set up an audit master for freight reconciliation</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Generate a freight invoice from a freight bill and update the invoice with carrier invoice details

Use the **Freight bill details** form to generate a freight invoice from a freight bill. After you receive a carrier invoice from a freight vendor, update the generated freight invoice with details from the carrier invoice. Alternatively, you can create a freight invoice in the **Freight invoice details** form that is based on the details from the carrier invoice that is received from the freight vendor.

To generate and update a freight invoice, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load planning workbench**.
    
    –or–
    
    Click **Warehouse management** \> **Common** \> **Load planning workbench**.

2.  On the **Loads** FastTab, select a load line. On the **Related information** menu, click **Freight bill details** to verify the freight bill details for the load line.

3.  In the **Freight bill details** form, click **Generate an invoice** to generate a freight invoice.

4.  In the **Freight invoice details** form, in the **Invoice** field, enter the invoice number that is received from the freight vendor.
    

    > [!NOTE]
    > <P>Alternatively, in the upper pane, click <STRONG>New</STRONG> to create a freight invoice based on the invoice details received from the freight vendor.</P>



5.  In the lower pane, update the freight invoice details based on the invoice that is received from the freight vendor.

## Match a freight invoice with a freight bill

After the generated freight invoice is updated with carrier invoice details received from the freight vendor, the freight invoice is matched with the freight bill. After the matching process, if the amount in the freight bill and freight invoice is same, the freight invoice is matched and submitted for payment approval. If there’s an unmatched amount, this is reconciled before submitting for payment approval.

To match the freight invoice lines with the freight bills, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Freight invoice details**.

2.  In the **Freight invoice details** form, select the updated freight invoice, and then click **Match freight bills and invoices** to open the **Freight bill and invoice matching** form.
    

    > [!NOTE]
    > <P>Select the <STRONG>Invoice is ready for automatic matching</STRONG> check box to match the freight invoice automatically. If a freight invoice is rejected during automatic freight reconciliation, you can reconcile the freight invoice manually.</P>



3.  On the **Unmatched freight bill details** FastTab, select a freight bill line, and then click **Match** to match line details of the freight invoice with the freight bills.

4.  Optional: On the **Matched freight bill details** FastTab, you can select a matched freight bill, and then click **Unmatch** to move the matched freight bill to the **Unmatched freight bill details** FastTab.

5.  On the **Invoice details** FastTab, select the freight invoice line.

6.  Click **Submit for approval** to submit the invoice line for approval. In the lower pane, click **Detail line reconciliation** to view the matched freight invoice.

## Reconcile unmatched freight invoice and freight bills with a reconciliation reason code

During the matching process, if all or part of freight invoice does not match with the freight bill details, you must reconcile the freight invoice line with a reconciliation reason code, such as approve or reject, and then submit it for payment approval. The freight invoice is submitted for payment approval only when all the freight invoice lines are assigned a reconciliation reason code.

## Reconcile an unmatched freight invoice

To reconcile the freight invoice manually when the freight invoice amount differs from the freight bill, follow these steps:

1.  In the **Freight bill and invoice matching** form, on the **Invoice details** FastTab, select the unmatched invoice line, and then click **Submit for approval** to open the **Reconcile invoice** form.

2.  Select a reconciliation reason code to reconcile the freight invoice line.

3.  Optional: Click **Split invoice amount** and split the amount to be reconciled. You can approve or reject the split amounts with reconciliation reason codes.

4.  In the **Freight bill and invoice matching** form, select the freight invoice line, and then click **Submit for approval** to submit the freight invoice line for approval.

## Discard unmatched freight bills

To discard unmatched freight bills when the freight bills do not have a carrier invoice to match with, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Match freight bills and invoices**. Specify the criteria for the freight bills, and then click **OK**.
    
    –or–
    
    Click **Transportation management** \> **Inquiries** \> **Freight invoice details**. Select the freight invoice, and then click **Match freight bills and invoices**.

2.  In the **Freight bill and invoice matching** form, on the **Unmatched freight bill details** FastTab, select the unmatched freight bills, and then click **Discard** to open the **Freight bill reconciliation** form.

3.  In the **Freight bill reconciliation** form, select a reconciliation reason code, and then click **OK** to discard the selected freight bill.

## Next step

[Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md)

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

  


