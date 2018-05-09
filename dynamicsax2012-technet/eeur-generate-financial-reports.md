---
title: (EEUR) Generate financial reports
TOCTitle: (EEUR) Generate financial reports
ms:assetid: 13c03b3d-4462-47c1-a1ee-274f80a6d3cf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910961(v=AX.60)
ms:contentKeyID: 52075291
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reports
- financial reports
- generate reports
---

# (EEUR) Generate financial reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Financial reports are generated for a specified reporting period. You can select a first, last, or arbitrary date for the reporting period, depending on the length, or date interval, of the reporting period. When you generate the report, the starting and ending dates for the reporting period are calculated by using the selected date interval.

When the report is generated, cell values are calculated for the selected period. The report is generated in either Microsoft Word or Microsoft Excel, depending on the report template that is selected. The report is saved by using the file path that is specified in the **File name** field on the **General** tab in the **Report** form. The file is automatically named in the following format: Template name1. For example, if the template is named Balance.xls, the report that is generated is named Balance1.xls. The completed report can be saved and modified as a regular Word or Excel file.

1.  Click **General ledger** \> **Reports** \> **External** \> **Financial reports generator**.

2.  Select a line, and then click **Print**.

3.  In the **Base date** field, select a date. The reporting period is determined by using this date.

4.  Click **OK** to generate the report.

## See also

[(EEUR) Base date (form)](https://technet.microsoft.com/en-us/library/jj910978\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

