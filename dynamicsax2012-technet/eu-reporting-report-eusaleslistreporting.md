---
title: EU reporting (report) EUSalesListReporting
TOCTitle: EU reporting (report) EUSalesListReporting
ms:assetid: b87abaea-c45d-4b18-b40c-c941a53ebedf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh456299(v=AX.60)
ms:contentKeyID: 36997725
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EU sales list
- SSRS_Reports.Reports.EUSalesListReporting
- EUSalesListReporting
- EU Reporting
---

# EU reporting (report) EUSalesListReporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **EU reporting** report to view and print details of the European Union (EU) sales list for legal entities that are operating in EU member states. This report is typically used by accountants, accounting managers, and accounting supervisors to inquire into the status of EU sales list transactions.

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
<td><p><strong>Reporting period</strong></p></td>
<td><p>Select the type of reporting period from the following options:</p>
<ol>
<li><p><strong>Not selected</strong> – The reporting period is not specified.</p></li>
<li><p><strong>Monthly</strong> – The EU sales list report is generated monthly.</p></li>
<li><p><strong>Quarterly</strong> – The EU sales list report is generated quarterly.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the reporting period to include in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the reporting period to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Change in periodicity</strong></p></td>
<td>Select this check box if the reporting period for the current EU sales list is different from that of the previously generated EU sales list.
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Generate file</strong></p></td>
<td><p>Select this check box to generate the EU sales list as an export file.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file name and file path of the EU sales list export file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Filing date</strong></p></td>
<td>Enter the date that the report for the reporting period specified under <strong>Date</strong> will be filed with the tax authority.
<div>

> [!NOTE]
> <P>(LAV) This control is available only to legal entities whose primary address is in Latvia.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Company manager</strong></p></td>
<td>Select the manager who is responsible for filing the report.
<div>

> [!NOTE]
> <P>(LAV) This control is available only to legal entities whose primary address is in Latvia.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Position</strong></p></td>
<td>Select the title of the person who is responsible for filing the report.
<div>

> [!NOTE]
> <P>(LAV) This control is available only to legal entities whose primary address is in Latvia.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Contact information</strong></p></td>
<td>Enter the email address or telephone number of the person who is responsible for the report.
<div>

> [!NOTE]
> <P>(LTH) This control is available only to legal entities whose primary address is in Lithuania.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Report type</strong></p></td>
<td>Select the type of report that is being created, such as <strong>Primary</strong> or <strong>Corrected</strong>.
<div>

> [!NOTE]
> <P>(LTH) This control is available only to legal entities whose primary address is in Lithuania.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Phone number</strong></p></td>
<td>Enter the telephone number of the person who is responsible for filing the report.
<div>

> [!NOTE]
> <P>(LAV) This control is available only to legal entities whose primary address is in Latvia.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Customer information</strong></p></td>
<td>Enter additional customer information to be included in the report file.
<div>

> [!NOTE]
> <P>(AUT) This control is available only to legal entities whose primary address is in Austria.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Authority</strong></p></td>
<td>Select the account number of the sales tax authority.
<div>

> [!NOTE]
> <P>(AUT) This control is available only to legal entities whose primary address is in Austria.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Document number of the declaration</strong></p></td>
<td>Enter the document number of the declaration.
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Contact ID</strong></p></td>
<td>Select the contact identification number of the auditor.
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Presentation type</strong></p></td>
<td><p>Select the media type from the following options:</p>
<ul>
<li><p><strong>Telematic</strong> – Submit the EU sales list to the tax authorities over the Internet.</p></li>
<li><p><strong>DVD</strong> – Submit the EU sales list to the tax authorities by using a DVD.</p></li>
</ul>
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Correction</strong></p></td>
<td><p>Select this check box to mark the export file for correction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Correction</strong></p></td>
<td><p>Select one of the following options if the current EU sales list is a correction or replacement to a previously-declared EU sales list:</p>
<ul>
<li><p><strong>Complementary</strong> – Specify that the current EU sales list is a correction.</p></li>
<li><p><strong>Replacement</strong> – Specify that the current EU sales list is a replacement of a previously-declared EU sales list.</p></li>
</ul>
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Corrected declaration</strong></p></td>
<td>The declaration number of the declaration to be corrected.
<div>

> [!NOTE]
> <P>(ESP) This control is available only to legal entities whose primary address is in Spain.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Official declaration</strong></p></td>
<td><p>Select this check box to create an export file that contains the details of the EU sales list.</p>
<div>

> [!NOTE]
> <P>(BEL, DEU) This control is available only to legal entities whose primary address is in Belgium or Germany.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Worker</strong></p></td>
<td>Select the name of the worker who generates the EU sales list.
<div>

> [!NOTE]
> <P>(GBR) This control is available only to legal entities whose primary address is in the United Kingdom.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Send electronically</strong></p></td>
<td>Select this check box to send the report to the tax authorities in an electronic format.
<div>

> [!NOTE]
> <P>(NLD) This control is available only to legal entities whose primary address is in the Netherlands.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Balance</strong></p></td>
<td><p>The status of the transactions that are included in the report. This field can display one of the following options:</p>
<ul>
<li><p><strong>Included</strong> – The transactions that are to be reported are included in the report.</p></li>
<li><p><strong>Reported</strong> – The transactions that have already been reported are included in the report as corrections. You must select the <strong>Corrected</strong> check box on the <strong>Correction</strong> form to include these transactions.</p></li>
<li><p><strong>Closed</strong> – Closed transactions are included in the report.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>List code</strong></p></td>
<td><p>The list code for the current invoice.</p></td>
</tr>
<tr class="even">
<td><p><strong>ID</strong></p></td>
<td>The identification of the electronic Intracommunautaire Prestaties (ICP) declaration.
<div>

> [!NOTE]
> <P>(NLD) This control is available only to legal entities whose primary address is in the Netherlands.</P>


</div></td>
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
<td><p>EUSalesListReporting</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\EUSalesListReporting</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>EUSalesListReporting</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Organization administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>EU sales list</strong>. Click <strong>Reporting</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CompanyInfo table

  - EUSalesListReportingHeader table

  - EUSalesListReportingLine table

  - LogisticsAddressCountryRegion table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[EU sales list (form)](https://technet.microsoft.com/en-us/library/aa596355\(v=ax.60\))

[Transfer transactions for EU sales list (form)](https://technet.microsoft.com/en-us/library/aa499405\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

