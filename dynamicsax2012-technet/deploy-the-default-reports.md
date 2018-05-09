---
title: Deploy the default reports
TOCTitle: Deploy the default reports
ms:assetid: 6a34674a-f68c-4d67-8bcb-3159f9089d4c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309703(v=AX.60)
ms:contentKeyID: 28119372
ms.date: 06/04/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Deploy the default reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes many default reports that you must deploy. If you did not deploy the reports when you installed the Microsoft SQL Server Reporting Services extensions, you can deploy them by using Windows PowerShell. The following procedures can help you deploy the reports.

## Before you begin

Before you can deploy the reports by using Windows PowerShell, you must complete the following tasks:

  - Verify that Windows PowerShell 2.0 is installed on the computer that you are using.

  - Verify that your Windows domain account is a member of the Administrators group on the server that is running Reporting Services.
    

    > [!NOTE]
    > <P>If your Windows domain account is assigned to a group that is a member of the Administrators group, it may take some time to validate that you are a member of the Administrators group. If you experience a delay when you deploy reports, consider adding your Windows domain account directly to the Administrators group.</P>



  - If Reporting Services is running in native mode, verify that you are assigned to the System Administrator role on the Report Manager website.

  - If Reporting Services is running in SharePoint integrated mode, verify that you have been granted **Contribute** permission to the document library where you plan to deploy the reports.
    

    > [!NOTE]
    > <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>



## Open Windows PowerShell and view a list of reports

Complete the following procedure to open Windows PowerShell and view a list of the reports that are included with Microsoft Dynamics AX.

1.  Open Windows PowerShell as an administrator by following these steps:
    
    1.  Click **Start** \> **Administrative Tools**.
    
    2.  Right-click the **Microsoft Dynamics AX 2012 Management Shell** option.
    
    3.  Click **Run as administrator**.

2.  Retrieve a list of the reports that are included with Microsoft Dynamics AX, and store the list in a local variable by entering the following command:
    
    ``` powershell
    $reports = Get-AXReport -ReportName *
    ```
    
    For more information about the Get-AXReport command, see [Get-AXReport](http://go.microsoft.com/fwlink/?linkid=217546).

3.  View the list of reports by entering the following command:
    
    ``` powershell
    $reports
    ```

## Filter the list of reports

In the previous procedure, you displayed a list of all the reports that are included with Microsoft Dynamics AX. To modify and filter the list, you can use the following commands:

  - To modify the list so that only the **Name** and **ChangedDate** fields are displayed, enter the following command:
    
    ``` powershell
    $reports | Select-Object Name,ChangedDate
    ```

  - To filter the list so that only specific reports are listed, enter keywords or report names. For example, to filter the list so that only reports that contain the word *CustTrans* are listed, enter the following command:
    
    ``` powershell
    $reports | Select-Object Name,ChangedDate | Where { $_.Name -like "CustTrans*" }
    ```

## Deploy the reports

After you have retrieved a list of reports, you can deploy the reports. The Publish-AXReport command is used to deploy the reports. The following examples show how to use this command. For more information, see [Publish-AXReport](http://go.microsoft.com/fwlink/?linkid=217550).

  - To deploy a specific report, enter the name of the report. For example, to deploy the CustTransList report, enter the following command:
    
    ``` powershell
    Publish-AXReport -ReportName CustTransList
    ```

  - To deploy two or more specific reports, enter the names of the reports. For example, to deploy the CustTransList and CustTransOpenPerDate reports, enter the following command:
    
    ``` powershell
    Publish-AXReport -ReportName CustTransList, CustTransOpenPerDate
    ```

  - To deploy all reports, enter the following command:
    
    ``` powershell
    Publish-AXReport –ReportName *
    ```

## Redeploy the reports

If you have modified a report’s data source or parameters, you must redeploy the report in order for the changes to take effect. To redeploy a report, follow the previous procedures in this topic.

After you redeploy a report, complete the following tasks.

## Restart the Reporting Services service

If you’re running Reporting Services 2008 (in either native or SharePoint integrated mode) or Reporting Services 2012 or 2014 in native mode, restart the service by following these steps:

1.  Click **Start** \> **Administrative Tools** \> **Services** to open the **Services** management console.

2.  Right-click the **SQL Server Reporting Services** service and choose **Restart**.

If you’re running Reporting Services 2012 or 2014 in SharePoint integrated mode, restart the service by following these steps:

1.  Go to the SharePoint Central Administration site.

2.  Click **System Settings** \> **Manage services on server**.

3.  Stop the SQL Server Reporting Services service.

4.  Start the SQL Server Reporting Services service.

## Refresh the AOD cache

Complete the following steps to refresh the application object directory (AOD) cache. This will clear cached application object information for all items in the application object tree (AOT) of Microsoft Dynamics AX.

1.  Open the Microsoft Dynamics AX client.

2.  Open the development workspace.

3.  Click **Tools** \> **Caches** \> **Refresh elements**.
    
    After the cache has been cleared, the Infolog displays a message indicating that AOD elements have been refreshed.

## Instruct users to delete usage data

Instruct Microsoft Dynamics AX users to delete usage data. Selections that users make while Microsoft Dynamics AX is running are saved as usage data. This data is used to improve the users’ experiences the next time that they run Microsoft Dynamics AX.

Instruct users to delete usage data by following these steps:

1.  Open the Microsoft Dynamics AX client.

2.  Click **File** \> **Tools** \> **Options**. The **Options** form is displayed.

3.  Click **Usage data**.

4.  On the **General** tab, click **Reset**.

## See also

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

[Piping and the Pipeline in Windows PowerShell](http://go.microsoft.com/fwlink/?linkid=187808)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

