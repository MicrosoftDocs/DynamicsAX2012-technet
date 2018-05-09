---
title: Update the OLAP data source
TOCTitle: Update the OLAP data source
ms:assetid: d19dbb45-bf32-4f36-b7d2-722c149df5ae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh202068(v=AX.60)
ms:contentKeyID: 35949310
ms.date: 06/03/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Update the OLAP data source 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, when you deploy the cubes that are included with Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, the database that is created in Microsoft SQL Server Analysis Services is named *Dynamics AX*. If you entered a new name for the Analysis Services database when you deployed the cubes, you must modify the DynamicsAXOLAP data source. To modify the data source, complete the following procedures on the server that runs Microsoft SQL Server Reporting Services.


> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R2 or later, the following procedures do not apply to you.</P>



## Modify the DynamicsAXOLAP data source in Report Manager

Follow these steps to modify the DynamicsAXOLAP data source on the Report Manager website.

1.  Open Report Manager. By default, the URL is http://\[SSRSServerName\]:80/Reports.

2.  Click the **DynamicsAX** folder.

3.  Click the **DynamicsAXOLAP** data source.

4.  In the **Connection string** field, locate the text **Initial Catalog=Dynamics AX**.

5.  Change **Dynamics AX** to the new name of the Analysis Services database.

## Modify the DynamicsAXOLAP data source in the AOT

Follow these steps to use Windows PowerShell to modify the DynamicsAXOLAP data source in the Application Object Tree (AOT) of Microsoft Dynamics AX.

1.  Open Windows PowerShell as an administrator by following these steps:
    
      - Click **Start** \> **Administrative Tools**.
    
      - Right-click the **Microsoft Dynamics AX 2012 Management Shell** option.
    
      - Click **Run as administrator**.

2.  Enter the following command. In this command, note the following information:
    
      - *\[SSASServerName\]* is the name of the server that runs Analysis Services. If you have a named instance of Analysis Services, enter *\[SSASServerName\\InstanceName\]*.
    
      - *\[DatabaseName\]* is the name of the Analysis Services database.
    
    <!-- end list -->
    
    ``` powershell
    Set-AXReportDataSource -DataSourceName DynamicsAXOLAP -ConnectionString “Provider=MSOLAP.4;Integrated Security=SSPI;Persist Security Info=True;Data Source=[SSASServerName];Initial Catalog=[DatabaseName]”
    ```
    
    For more information about the Set-AXReportDataSource command, see [Set-AXReportDataSource](http://go.microsoft.com/fwlink/?linkid=217552).

## See also

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

