---
title: About using the Microsoft Dynamics AX Add-in for Excel
TOCTitle: About using the Microsoft Dynamics AX Add-in for Excel
ms:assetid: f248e63f-4191-4da5-b833-e5a0293e12f9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh801196(v=AX.60)
ms:contentKeyID: 43976732
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Add-in
- Office
- Excel
- import
- export
---

# About using the Microsoft Dynamics AX Add-in for Excel [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can export many forms, lists, and reports from Microsoft Dynamics AX and Enterprise Portal for Microsoft Dynamics AX to Microsoft Excel. If a form, list, or report has an **Export to Microsoft Excel** button on the **Action Pane**, you can export the data to Excel.

If your system administrator has installed the Office Add-ins for Microsoft Dynamics AX, a **Dynamics AX** tab is added to the ribbon in Excel. If your user role has access to data in the Microsoft Dynamics AX client and the permissions to refresh exported data, you can refresh the data that you export from Microsoft Dynamics AX into Excel.

To determine whether your role has permission to refresh exported data, follow these steps.

1.  Click **File** \> **Tools** \> **Options**.

2.  In the **Options** form, on the **Miscellaneous** FastTab, check the **Workbook supports refresh** field. If it is set to **When possible**, you can refresh data that you export to Excel.

3.  Confirm that the **Remote Desktop session exports to:** field is set to **Client Excel**. If this option is selected, you can create an Excel file that contains exported data and save the file to a local computer.

Contact your system administrator for more information about these settings.

The Office Add-in for Excel lets you perform the following tasks:

  - **Refresh the data** – Export data to Excel, and then create charts, PivotTable reports, and other conditional formatting from the data. Later, when you want to see updated data in the PivotTable reports or charts, you can refresh the Excel worksheet, and the table, formulas, and charts that are derived from the exported data are also refreshed.

  - **Choose fields to include in the exported data** – Export data to Excel, and then, in the Excel worksheet, add columns that contain related data from other forms, lists, tables, and reports.
    

    > [!NOTE]
    > <P>The data that you select in the additional columns must be linked to the exported data. Your system administrator can tell you whether the data that you want to add has a key that is linked to the exported data.</P>



  - **Change the field mapping** – Change the names of the exported columns in Excel, but still retain the dynamic connection with the original data. For example, you export the **All customers** list to Excel. You change the title of the first column from **Name** to **Customer**. When you refresh the list, the column title remains **Customer**.

  - **Update data in Microsoft Dynamics AX** – Export data to Excel, modify data and add new rows of data in the Excel worksheet, and then import the updated data to Microsoft Dynamics AX.

## See also

[Integrating Microsoft Dynamics AX with Microsoft Office](integrating-microsoft-dynamics-ax-with-microsoft-office.md)

[Update Microsoft Dynamics AX data by using Microsoft Excel](update-microsoft-dynamics-ax-data-by-using-microsoft-excel.md)

[Key tasks: Create and share an Excel template by using the Office Add-ins](key-tasks-create-and-share-an-excel-template-by-using-the-office-add-ins.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

