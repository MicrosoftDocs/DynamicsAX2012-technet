---
title: Update Microsoft Dynamics AX data by using Microsoft Excel
TOCTitle: Update Microsoft Dynamics AX data by using Microsoft Excel
ms:assetid: 7f52b6a8-597e-49c1-80aa-275055f0b043
ms:mtpsurl: https://technet.microsoft.com/library/Gg731845(v=AX.60)
ms:contentKeyID: 35132698
author: Khairunj
ms.date: 04/30/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Update Microsoft Dynamics AX data by using Microsoft Excel 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the Office Add-ins for Microsoft Dynamics AX to export data from Microsoft Dynamics AX to Microsoft Excel. After you export data from Microsoft Dynamics AX forms, lists, and reports to Excel, you can modify the data and import the data back into Microsoft Dynamics AX to update records.


> [!NOTE]
> <P>To use the Office Add-in for Excel, the following programs must be installed:</P>
> <UL>
> <LI>
> <P>Microsoft&nbsp;Excel 2010 or Microsoft Office Excel 2007</P>
> <LI>
> <P>Office Add-ins for Microsoft Dynamics AX. For more information about installing the Office Add-ins, see <A href="install-office-add-ins.md">Install Office Add-ins</A>.</P></LI></UL>



After you export your data from Microsoft Dynamics AX to an Excel workbook, you can use tools and features in Excel to work in more detail with the exported data. For example, you can filter the data, add formats, and use a PivotTable report to summarize your data query.

### Select data to export to Excel

1.  Start Excel.

2.  On the ribbon, on the **Dynamics AX** tab, click **Connection**, select the Microsoft Dynamics AX server to connect to, and then click **OK**.

3.  Click **Add Data**, select the check box for the data source query to use, and then click **OK**.

4.  In the left pane, select a default header value to include in your data query.
    
    You can select the header and then click **Insert value**, or you can drag the header to the appropriate cell in the Excel worksheet.
    
    Repeat this step until you have added all the header fields for this data query.

5.  In the left pane, select the field to include in your data query.
    
    You can select the field and then click **Insert column**, or you can drag the field to the appropriate cell in the Excel worksheet.
    
    Repeat this step until you have added all the fields for this data query.

6.  Click **Choose parameters**, and then select the parameters for the fields that you selected for your data query.
    
    For example, to create a data query to view all Time and material projects, select **Expense.Project.Project type = Time and material**.

7.  Click **Publish data**.

After you save the workbook, the data is updated for recent transactions the next time you open the workbook.

## See also

[Using the Microsoft Dynamics AX Add-in for Excel](using-the-microsoft-dynamics-ax-add-in-for-excel.md)

[Integrating Microsoft Dynamics AX with Microsoft Office](integrating-microsoft-dynamics-ax-with-microsoft-office.md)

[Microsoft TechNet](https://go.microsoft.com/fwlink/?linkid=275089)

  


