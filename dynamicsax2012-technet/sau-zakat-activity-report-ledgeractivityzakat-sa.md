---
title: (SAU) Zakat activity report (LedgerActivityZakat_SA)
TOCTitle: (SAU) Zakat activity report (LedgerActivityZakat_SA)
ms:assetid: 9f32ba29-8e69-4b7c-b44f-629bcbb36ebb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh371728(v=AX.60)
ms:contentKeyID: 36814942
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerActivityZakat_SA
---

# (SAU) Zakat activity report (LedgerActivityZakat\_SA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Every fiscal year, companies must report Zakat deductions for the previous year. Legal entities that operate in Saudi Arabia must generate the main Zakat report and the associated reports. You must submit these reports along with balance sheets and profit-and-loss statements to the Department of Zakat and Income Tax (DZIT) within a month of the end of the fiscal year. For more information about the Zakat reports, see [(SAU) About Zakat reporting](sau-about-zakat-reporting.md). By using this Zakat activity report, you can generate the following:

  - The **Other additions** report displays a summary of miscellaneous ledger transactions that are not categorized under other Zakat reports. The report displays account information, individual amounts, and total amounts of ledger transactions.

  - The **Other adjustments** report displays a summary of all miscellaneous ledger transaction adjustments that are not categorized under other Zakat reports. The report displays account information, individual amounts, and total amounts.

  - The **Other deductions** report displays a summary of all miscellaneous deductions on ledger transactions that are not categorized under other Zakat reports. The report includes account information, individual amounts, and total amounts.

  - The **Other expenses** report displays a summary of all miscellaneous ledger transaction expenses that are not categorized under other Zakat reports. The report includes information such as the account name and expense amount.

  - The **Investments** report displays a summary of all investments and includes their account information, individual amounts, and total amounts.

  - The **Direct expenses** report displays a summary of all direct expenses with their account information, individual amounts, and total amounts.

  - The **Pre-setting up expenses** report displays a summary of all preset expenses, such as travel expenses and project expenses. This report includes information such as the account name and expense amount.

  - The **Revenue from other activity** report displays a summary of the revenue from other business activities other than the main business activity. This report includes information such as the account name and amount of revenue.


> [!NOTE]
> <P>(SAU) This report is available only to legal entities whose primary address is in Saudi Arabia.</P>



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
<td><p>LedgerActivityZakat_SA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerActivityZakat_SA</p></td>
</tr>
<tr class="odd">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Zakat</strong> &gt; <strong>Zakat reports</strong>. In the <strong>Select</strong> field, select the Zakat report type in the <strong>Zakat report type</strong> field, and then click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerActivityZakatTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerActivityZakatDP_SA.processReport class.</P>



  - LedgerZakatHeaderTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerZakatHeaderDP_SA.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


