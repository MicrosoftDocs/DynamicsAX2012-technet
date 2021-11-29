---
title: Create a document library to store reports
TOCTitle: Create a document library to store reports
ms:assetid: e04173fd-30fb-438c-bcd5-057e87d6544d
ms:mtpsurl: https://technet.microsoft.com/library/JJ677281(v=AX.60)
ms:contentKeyID: 49384052
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Create a document library to store reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If you are using Microsoft Dynamics AX 2012 R2 or later, and if Microsoft SQL Server Reporting Services is running in SharePoint integrated mode, create a document library in SharePoint to store your reports. Complete this procedure before you deploy the default reports that are included with Microsoft Dynamics AX.


> [!NOTE]
> <P>This procedure does not apply to you if you are running Reporting Services in native mode.</P>



## Create a document library

Create a document library on your SharePoint site to store reports. For information about how to create a document library, see the SharePoint documentation.

After you create the document library, add Reporting Services content types to the library. For more information, see [Add Report Server Content Types to a Library (Reporting Services in SharePoint Integrated Mode)](https://technet.microsoft.com/library/bb326289\(v=sql.110\).aspx) in the SQL Server documentation.

## Specify the URL of the document library

After you have created the document library, complete the following procedure to specify the URL of the document library in the **Report servers** form in Microsoft Dynamics AX.

1.  Open Microsoft Dynamics AX.

2.  Click **System administration** \> **Setup** \> **Business intelligence** \> **Reporting Services** \> **Report servers**.

3.  In the **Configuration ID** field, enter a name that identifies the Reporting Services instance and the Application Object Server (AOS) instance that you are connecting.

4.  In the **Description** field, enter a brief description to help you identify the Reporting Services instance and the AOS instance that you are connecting.

5.  Select the **Default configuration** check box to make the Reporting Services and AOS instances that are specified in this record the active connection.

6.  On the **Reporting Server information** tab, enter the following information:
    
    1.  In the **Server name** field, enter the name of the server that is running Reporting Services.
    
    2.  In the **Server instance name** field, enter the name of the Reporting Services instance.
        

        > [!NOTE]
        > <P>If you are using Reporting Services 2012 or 2014, enter <STRONG>@Sharepoint</STRONG>.</P>

    
    3.  Leave the **Report Manager URL** field blank. This field becomes unavailable when you select the **SharePoint integrated mode** check box in a later step.
    
    4.  In the **Web service URL** field, enter the URL of the Reporting Services web service.
        
          - If you are using Reporting Services 2008, the URL is typically http://\[SSRSServerName\]/ReportServer.
        
          - If you are using Reporting Services 2012 or 2014, the URL is typically http://\[SharePointServerName\]/\_vti\_bin/ReportServer or http:\[SharePointServerName\]/sites/\[SiteName\]/\_vti\_bin/ReportServer.
    
    5.  Select the **SharePoint integrated mode** check box.
    
    6.  In the **Microsoft Dynamics AX report folder** field, enter the URL of the document library that you created to store reports.
        
        For example, suppose that you have created a document library that is named *Reports* on a SharePoint site that is named *Contoso*. In this example, the URL is as follows:
        
        http://\[SharePointServerName\]/sites/Contoso/Reports

7.  On the **Application Object Server information** tab, select the name of the AOS instance.

  


