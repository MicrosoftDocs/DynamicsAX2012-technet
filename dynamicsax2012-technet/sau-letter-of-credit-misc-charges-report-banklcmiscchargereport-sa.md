---
title: (SAU) Letter of credit misc charges report (BankLCMiscChargeReport_SA)
TOCTitle: (SAU) Letter of credit misc charges report (BankLCMiscChargeReport_SA)
ms:assetid: 40cb2567-31b7-4b5d-a647-e24de57ebdb4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433489(v=AX.60)
ms:contentKeyID: 36941250
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankLCMiscChargeReport_SA
---

# (SAU) Letter of credit misc charges report (BankLCMiscChargeReport\_SA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Letter of credit misc charges** report is used to display the miscellaneous charges that are applicable to a letter of credit. This report is typically used by chief financial officers, accountants, accounting managers, and accounting supervisors to maintain and inquire into the status of import letters of credit.


> [!NOTE]
> <P>(SAU) This report is available only to legal entities whose primary address is in Saudi Arabia.</P>



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
<td><p><strong>Bank document number</strong></p></td>
<td><p>Select the bank document number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank account</strong></p></td>
<td><p>Select the bank account number that corresponds to the letter of credit document.</p></td>
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
<td><p>BankLCMiscChargeReport_SA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankLCMiscChargeReport_SA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankLCMiscCharge_SA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>Letters of credit/guarantee</strong> &gt; <strong>Letter of credit misc charges</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankDocumentFacilityView table

  - BankLC table

  - BankLCImport table

  - BankLCImportCharge\_SA table

  - BankLCImportChargeAllocation table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

