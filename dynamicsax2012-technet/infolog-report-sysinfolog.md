---
title: Infolog report (SysInfoLog)
TOCTitle: Infolog report (SysInfoLog)
ms:assetid: 61aad186-afb1-45f0-bfa4-4598d55039a4
ms:mtpsurl: https://technet.microsoft.com/library/Hh801189(v=AX.60)
ms:contentKeyID: 43976708
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SysInfoLog
---

# Infolog report (SysInfoLog) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Infolog** report lists the errors that are displayed in the **Infolog** form.

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
<td><p>SysInfoLog</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SysInfoLog</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SysInfoLog</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>From the <strong>Infolog</strong> form, right-click in the top <strong>Message</strong> box, and then click <strong>Print...</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SysInfoLogTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the SysInfoLogDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Infolog (form)](https://technet.microsoft.com/library/aa673799\(v=ax.60\))

  


