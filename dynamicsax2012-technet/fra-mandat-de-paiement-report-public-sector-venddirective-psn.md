---
title: (FRA) Mandat de paiement report (Public sector) (VendDirective_PSN)
TOCTitle: (FRA) Mandat de paiement report (Public sector) (VendDirective_PSN)
ms:assetid: b61b0d8d-d37f-44c4-bba7-1dde10b81590
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450753(v=AX.60)
ms:contentKeyID: 36966709
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendDirective_PSN
---

# (FRA) Mandat de paiement report (Public sector) (VendDirective\_PSN) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this form to print a report that consists of one or more mandats de paiement.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>&nbsp; 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



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
<td><p><strong>Accountant</strong></p></td>
<td><p>Enter the name of the accountant who is responsible for approving the payment of the amounts shown on a mandat. The value in this field appears in the <strong>Accountant</strong> field of the printed mandat. It is not used in filtering mandats for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Director</strong></p></td>
<td><p>Enter the name of the director who is responsible for authorizing the accountant to pay the amounts shown on a mandat. The value in this field appears in the <strong>Director</strong> field of the printed mandat. It is not used in filtering mandats for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Mandat numbers</strong></p></td>
<td><p>The mandat numbers that are selected for inclusion in the report.</p></td>
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
<tr class="even">
<td><p><strong>Invoice accounts</strong></p></td>
<td><p>The vendors that are selected for inclusion in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budgetary accounts</strong></p></td>
<td><p>The budgetary accounts that are selected for inclusion in the report.</p></td>
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
<td><p>VendDirective_PSN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendDirective_PSN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendDirectiveReport_PSN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Mandat de paiement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - UserInfo table

  - CustVendDirective\_PSN table

  - VendInvoiceJour table

  - VendInvoiceInfoTable table

  - DirPartyTable table

  - DirPartyPostalAddressView table

  - PurchAgreementHeader table

  - MainAccount table

  - PurchCommitmentHeader\_PSN table

  - PurchCommitmentLine\_PSN table

  - AccountingDistribution table

  - VendDirective\_PSN table

  - TaxData table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(FRA) Bordereau de mandat report (Public sector) (VendRoutingSlipReport\_PSN)](fra-bordereau-de-mandat-report-public-sector-vendroutingslipreport-psn.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

