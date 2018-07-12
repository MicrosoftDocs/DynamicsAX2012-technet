---
title: (RUS) Print inventory transfer report (InventJournalTransTransfer)
TOCTitle: (RUS) Print inventory transfer report (InventJournalTransTransfer)
ms:assetid: 96e6c898-7228-4fe3-9dd8-5492daa5870e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn144858(v=AX.60)
ms:contentKeyID: 52225282
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.InventJournalTransTransfer
---

# (RUS) Print inventory transfer report (InventJournalTransTransfer) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the Print inventory transfer report to print information about the transfer of inventory items from one warehouse to another. The data on the report is grouped by inventory dimension.


> [!NOTE]
> <P>The fields that are described in this topic apply only to your country/region. For full documentation of this report, see the following topic:</P>&nbsp;<A href="print-inventory-transfer-report-inventjournaltranstransfer.md">Print inventory transfer report (InventJournalTransTransfer)</A>



## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p><strong>Inventory profile</strong></p></td>
<td><p>Select this check box to include the <strong>Inventory profile</strong> inventory dimension on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Owner</strong></p></td>
<td><p>Select this check box to include the <strong>Owner</strong> inventory dimension on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GTD number</strong></p></td>
<td><p>Select this check box to include the customs cargo declaration number, or <strong>GTD number</strong>, inventory dimension on the report.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>InventJournalTransTransfer</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\InventJournalTransTransfer</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>InventJournalTransTransfer</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Journals</strong> &gt; <strong>Item transactions</strong> &gt; <strong>Transfer</strong>. Select a journal, and then click <strong>Print</strong> &gt; <strong>Journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - InventDim table

  - InventJournalTrans table

  - InventJournalTransTransferHeaderTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the InventJournalTransTransferEEDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Journal lines, Inventory transfer (modified form)](https://technet.microsoft.com/en-us/library/jj665257\(v=ax.60\))

  


