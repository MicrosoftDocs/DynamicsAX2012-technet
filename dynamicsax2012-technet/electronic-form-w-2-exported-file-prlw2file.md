---
title: Electronic Form W-2 exported file (PRLW2File)
TOCTitle: Electronic Form W-2 exported file (PRLW2File)
ms:assetid: dabb82c6-7eaf-4ed6-82d7-1e7e25a3afa0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ713642(v=AX.60)
ms:contentKeyID: 49643136
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- SSRS_Reports.Reports.PayrollW2ElectronicDialog
- Form W-2
- Form W2
- W2
- W-2
- electronic W2
- electronic W-2
- submit W2
- submit W-2
- submit W2s
- submit W-2s
---

# Electronic Form W-2 exported file (PRLW2File) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this exported file to submit Form W-2s to the Social Security Administration.

For additional information about filing Form W-2s electronically, see the relevant publications from the Social Security Administration.


> [!NOTE]
> <P>This topic describes functionality that is available only if Payroll for Microsoft Dynamics AX 2012 is installed.</P>



## How to filter the data for this file

When you generate this file, the following default parameters are displayed. You can use these parameters to filter the data that will be exported. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p><strong>Employee PIN</strong></p></td>
<td><p>An employee in your organization must attest to the accuracy of the electronic Form W-2 when it is submitted. Enter the eight-character PIN that is assigned to this employee.</p></td>
</tr>
<tr class="even">
<td><p><strong>Resubmit</strong></p></td>
<td><p>Select this check box if the electronic Form W-2 has been submitted previously.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Resubmit WFID</strong></p></td>
<td><p>Enter the wage file identifier (WFID) that was on the notice from the Social Security Administration. The electronic Form W-2 cannot be resubmitted without the WFID.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tax year</strong></p></td>
<td><p>Enter the tax year that is covered by the electronic Form W-2.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Kind of employer</strong></p></td>
<td><p>Select one of the following options:</p>
<ul>
<li><p><strong>Federal government</strong></p></li>
<li><p><strong>State and local governmental employer</strong></p></li>
<li><p><strong>Tax exempt employer</strong></p></li>
<li><p><strong>State and local tax exempt employer</strong></p></li>
<li><p><strong>None apply</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Employment code</strong></p></td>
<td><p>Enter the employment code that applies to the organization that is submitting the electronic Form W-2.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Contact name</strong></p></td>
<td><p>Enter the name of the employee who can be contacted by the Social Security Administration about the electronic Form W-2. This can be the same person who attests to the accuracy of the electronic Form W-2, or it can be a different person.</p></td>
</tr>
<tr class="even">
<td><p><strong>Street</strong></p>
<p><strong>City</strong></p>
<p><strong>State</strong></p>
<p><strong>ZIP/postal code</strong></p></td>
<td><p>Enter the address where the contact person receives mail.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Phone number</strong></p></td>
<td><p>Enter a telephone number where the contact person can be reached.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fax number</strong></p></td>
<td><p>Enter a fax number where the contact person can receive documents.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Email address</strong></p></td>
<td><p>Enter an email address where the contact person can be reached.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Click the folder icon to browse to the electronic Form W-2 file and enter the file name and location.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker</strong></p></td>
<td><p>Click <strong>Select</strong> to specify the workers to include in the electronic Form W-2.</p></td>
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
<td><p>PRLW2File</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\Classes\PRLW2File</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Action\PayrollW2File</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Payroll</strong> &gt; <strong>Reports</strong> &gt; <strong>Tax</strong> &gt; <strong>Annual reports</strong> &gt; <strong>Electronic Form W-2</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this file comes from

The data on this report comes from the following sources:

  - LogisticsPostalAddress

  - DirPerson

  - HcmPersonIdentificationNumber

  - HcmEmployment

  - HCMWorker

  - PayrollTaxCode

  - PRLUSTaxTransactionHistory

  - PayrollTaxCodeDetail

  - PayrollPayStatement

  - PayrollPayStatementLine

  - PayrollPayStatementBenefitLine

  - PayrollPayStatementTaxLine

  - PayrollPayStatementEarningLine

  - PayrollFormW2BoxReportingAdjustment

  


