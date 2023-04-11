---
title: Deploy reports for the new Reporting Services instance
TOCTitle: Deploy reports for the new Reporting Services instance
ms:assetid: 9860b790-71ac-4aa1-9c69-7ca986fd977e
ms:mtpsurl: https://technet.microsoft.com/library/Hh389771(v=AX.60)
ms:contentKeyID: 36899750
author: tonyafehr
ms.date: 06/03/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Deploy reports for the new Reporting Services instance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes many default reports that you must deploy. You can deploy these reports by using Windows PowerShell. The following procedures can help you deploy the reports.

## Before you begin

Before you can deploy the reports by using Windows PowerShell, you must complete the following tasks:

  - Verify that Windows PowerShell 2.0 is installed on the computer that you are using.

  - Verify that your Windows domain account is a member of the Administrators group on the server that is running Microsoft SQL Server Reporting Services.
    

    > [!NOTE]
    > <P>If your Windows domain account is assigned to a group that is a member of the Administrators group, it may take some time to validate that you are a member of the Administrators group. If you experience a delay when you deploy reports, consider adding your Windows domain account directly to the Administrators group.</P>



  - If Reporting Services is running in native mode, verify that you are assigned to the System Administrator role on the Report Manager website.

  - If Reporting Services is running in SharePoint integrated mode, verify that you have been granted **Contribute** permission to the document library where you plan to deploy the reports.
    

    > [!NOTE]
    > <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>



## Open Windows PowerShell and view a list of reports

Complete the following procedure to open Windows PowerShell and view a list of the reports that are included with Microsoft Dynamics AX.

1.  Open Windows PowerShell as an administrator by following these steps.
    
    1.  Click **Start** \> **Administrative Tools**.
    
    2.  Right-click the **Microsoft Dynamics AX 2012 Management Shell** option.
    
    3.  Click **Run as administrator**.

2.  Retrieve a list of the reports that are included with Microsoft Dynamics AX, and store the list in a local variable by entering the following command:
    
    ``` powershell
    $reports = Get-AXReport -ReportName *
    ```
    
    For more information about the Get-AXReport command, see [Get-AXReport](https://go.microsoft.com/fwlink/?linkid=217546).

3.  View the list of reports by entering the following command:
    
    ``` powershell
    $reports
    ```

## Filter the list of reports

In the previous procedure, you displayed a list of all the reports that are included with Microsoft Dynamics AX. To modify and filter the list, you can use the following commands.

  - To modify the list so that only the **Name** and **ChangedDate** fields are displayed, enter the following command:
    
    ``` powershell
    $reports | Select-Object Name,ChangedDate
    ```

  - To filter the list so that only specific reports are listed, enter keywords or report names. For example, to filter the list so that only reports that contain the word *CustTrans* are listed, enter the following command:
    
    ``` powershell
    $reports | Select-Object Name,ChangedDate | Where { $_.Name -like "CustTrans*" }
    ```

## Deploy the reports

After you have retrieved a list of reports, you can deploy the reports. The Publish-AXReport command is used to deploy the reports. The following examples show how to use this command. For more information, see [Publish-AXReport](https://go.microsoft.com/fwlink/?linkid=217550).


> [!NOTE]
> <P>In the following examples, <STRONG>SSRSConfigID</STRONG> refers to a configuration ID that was defined in Microsoft Dynamics AX. To view these configuration IDs, open Microsoft Dynamics AX and then open the <STRONG>Report servers</STRONG> form. (Click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Business intelligence</STRONG> &gt; <STRONG>Reporting Services</STRONG> &gt; <STRONG>Report servers</STRONG>.) To deploy reports to the new Reporting Services instance, enter the configuration ID that is associated with that instance.</P>



  - To deploy a specific report, enter the name of the report. For example, to deploy the CustTransList report, enter the following command:
    
    ``` powershell
    Publish-AXReport –Id SSRSConfigID -ReportName CustTransList
    ```

  - To deploy two or more specific reports, enter the names of the reports. For example, to deploy the CustTransList and CustTransOpenPerDate reports, enter the following command:
    
    ``` powershell
    Publish-AXReport –Id SSRSConfigID -ReportName CustTransList, CustTransOpenPerDate
    ```

  - To deploy all reports, enter the following command:
    
    ``` powershell
    Publish-AXReport –Id SSRSConfigID –ReportName *
    ```

## See also

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

[Piping and the Pipeline in Windows PowerShell](https://go.microsoft.com/fwlink/?linkid=187808)

  


