---
title: (FRA) Bordereau de mandat report (Public sector) (VendRoutingSlipReport_PSN)
TOCTitle: (FRA) Bordereau de mandat report (Public sector) (VendRoutingSlipReport_PSN)
ms:assetid: 92ec4a3b-23a3-4c8b-9eb4-1432b72add02
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450752(v=AX.60)
ms:contentKeyID: 36966706
ms.date: 04/01/2015
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendRoutingSlipReport_PSN
---

# (FRA) Bordereau de mandat report (Public sector) (VendRoutingSlipReport\_PSN) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this form to print a report that consists of one or more bordereaux de mandat.

This form is available only if the following conditions are met:

  - The **Public Sector** configuration key is selected.

  - The **French regulatory** configuration subkey is selected.

  - In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the **Commitments (France)** regulatory document type is selected in the **Budget parameters** form, when the following hotfix is installed: KB3047235

  - In cumulative update 7 for Microsoft Dynamics AX 2012, the **Use French public sector accounting rules** check box is selected in the **Budget parameters** form.

In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the **Public Sector** configuration key must be selected, but the primary address of the legal entity must be in France.

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
<td><p><strong>Bordereau de mandat numbers</strong></p></td>
<td><p>The bordereau de mandat numbers that are selected for inclusion in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Director authorization status</strong></p></td>
<td><p>The director authorization status that is selected for inclusion in the report.</p>
<p>There are three possible values:</p>
<ul>
<li><p><strong>Not reviewed</strong> – The director has neither authorized the accountant to pay the amount shown on the invoice line nor rejected the mandat de paiement.</p></li>
<li><p><strong>Authorized</strong> – The director has authorized the accountant to pay the amount shown on the invoice line to the vendor specified in the invoice account.</p></li>
<li><p><strong>Rejected</strong> – The director has rejected the mandat de paiement.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Accountant acceptance status</strong></p></td>
<td><p>The accountant acceptance status that is selected for inclusion in the report.</p>
<p>There are three possible values:</p>
<ul>
<li><p><strong>Not reviewed</strong> – The accountant has neither accepted the invoice line for payment nor rejected the mandat de paiement.</p></li>
<li><p><strong>Accepted</strong> – The accountant has agreed to pay the amount shown on the invoice line to the vendor specified in the invoice account.</p></li>
<li><p><strong>Rejected</strong> – The accountant has rejected the mandat de paiement.</p></li>
</ul></td>
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
<td><p>VendRoutingSlipReport_PSN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendRoutingSlipReport_PSN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendRoutingSlipReport_PSN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Bordereau de mandat</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendRoutingSlip\_PSN table

  - VendDirective\_PSN table

  - VendInvoiceInfoTable table

  - VendInvoiceInfoLine table

  - VendInvoiceJour table

  - VendInvoiceTrans table

  - DirPartyTable table

  - DirPartyPostalAddressView table

  - PurchCommitmentLine\_PSN table

  - DimensionValueAttributeCombination table

  - MainAccount table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(FRA) Mandat de paiement report (Public sector) (VendDirective\_PSN)](fra-mandat-de-paiement-report-public-sector-venddirective-psn.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

