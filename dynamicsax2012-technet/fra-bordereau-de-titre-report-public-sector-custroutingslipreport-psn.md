---
title: (FRA) Bordereau de titre report (Public sector) (CustRoutingSlipReport_PSN)
TOCTitle: (FRA) Bordereau de titre report (Public sector) (CustRoutingSlipReport_PSN)
ms:assetid: 3296593d-adf2-44b7-98e4-7d98a418fc2f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450749(v=AX.60)
ms:contentKeyID: 36966694
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustRoutingSlipReport_PSN
---

# (FRA) Bordereau de titre report (Public sector) (CustRoutingSlipReport\_PSN) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this form to print a report that consists of one or more bordereaux de titre.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>&nbsp; 
> <P>This form is available only if the following conditions are met:</P>
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
<td><p><strong>Bordereau de titre numbers</strong></p></td>
<td><p>The bordereau de titre numbers that are selected for inclusion in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Director authorization status</strong></p></td>
<td><p>The director authorization status that is selected for inclusion in the report.</p>
<p>There are three possible values:</p>
<ul>
<li><p><strong>Not reviewed</strong> – The director has neither authorized the accountant to collect the amount shown on the invoice line nor rejected the titre de recette.</p></li>
<li><p><strong>Authorized</strong> – The director has authorized the accountant to collect the amount shown on the invoice line from the customer specified in the customer account.</p></li>
<li><p><strong>Rejected</strong> – The director has rejected the titre de recette.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Accountant acceptance status</strong></p></td>
<td><p>The accountant acceptance status that is selected for inclusion in the report.</p>
<p>There are three possible values:</p>
<ul>
<li><p><strong>Not reviewed</strong> – The accountant has neither accepted the invoice line for collection nor rejected the titre de recette.</p></li>
<li><p><strong>Accepted</strong> – The accountant has agreed to collect the amount shown on the invoice line from the customer specified in the customer account.</p></li>
<li><p><strong>Rejected</strong> – The accountant has rejected the titre de recette.</p></li>
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
<td><p>CustRoutingSlipReport_PSN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustRoutingSlipReport_PSN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustRoutingSlipReport_PSN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Bordereau de titre</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustRoutingSlip\_PSN

  - CustDirective\_PSN

  - CustInvoiceLine

  - CustInvoiceTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(FRA) Titre de recette report (Public sector) (CustDirective\_PSN)](fra-titre-de-recette-report-public-sector-custdirective-psn.md)

  


