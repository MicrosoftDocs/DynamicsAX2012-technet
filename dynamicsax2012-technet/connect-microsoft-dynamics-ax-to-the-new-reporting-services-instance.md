---
title: Connect Microsoft Dynamics AX to the new Reporting Services instance
TOCTitle: Connect Microsoft Dynamics AX to the new Reporting Services instance
ms:assetid: de984127-106d-4811-80ee-e4a1178f1541
ms:mtpsurl: https://technet.microsoft.com/library/Hh389773(v=AX.60)
ms:contentKeyID: 36899752
author: tonyafehr
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Connect Microsoft Dynamics AX to the new Reporting Services instance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedure to connect an instance of Microsoft Dynamics AX Application Object Server (AOS) to the new instance of Microsoft SQL Server Reporting Services. This topic assumes that the new instance of Reporting Services meets the version requirements that are listed in [Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md).

1.  Open Microsoft Dynamics AX.

2.  Click **System administration** \> **Setup** \> **Business intelligence** \> **Reporting Services** \> **Report servers**.

3.  In the **Configuration ID** field, enter a name that identifies the Reporting Services instance and the AOS instance that you are connecting.

4.  In the **Description** field, enter a brief description to help you identify the Reporting Services instance and the AOS instance that you are connecting.

5.  Select the **Default configuration** check box.

6.  On the **Reporting Server information** tab, complete the actions that are listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Action you should take</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Server name</strong></p></td>
    <td><p>Enter the name of the server that is running Reporting Services.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Server instance name</strong></p></td>
    <td><p>Enter the name of the new Reporting Services instance.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Report Manager URL</strong></p></td>
    <td><ul>
    <li><p>If Reporting Services is running in native mode, enter the URL of the Report Manager website. The URL is typically http://[SSRSServerName]/Reports_[SSRSInstanceName].</p></li>
    <li><p>If Reporting Services is running in SharePoint integrated mode, leave this field empty.</p>
    <div class="alert">

    > [!NOTE]
    > <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>


    </div></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Web service URL</strong></p></td>
    <td><p>Enter the URL of the Reporting Services web service. The URL is typically http://[SSRSServerName]/ReportServer_[SSRSInstanceName].</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>SharePoint integrated mode</strong></p></td>
    <td><p>Select this check box if Reporting Services is running in SharePoint integrated mode.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Microsoft Dynamics AX report folder</strong></p></td>
    <td><ul>
    <li><p>If Reporting Services is running in native mode, enter a name for a report folder. The report folder will be created for you on the Report Manager website.</p></li>
    <li><p>If Reporting Services is running in SharePoint integrated mode, enter the URL of a document library. The document library will be created for you on the SharePoint site that is integrated with Reporting Services. For example, suppose you want to create a document library that is named <em>Reports</em> on a SharePoint site that is named <em>Contoso</em>. In this case, you would enter the following URL:</p>
    <p>http://[SharePointServerName]/sites/Contoso/Reports</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


7.  On the **Application Object Server information** tab, select the name of the AOS instance.

8.  Click **Create report folder** to create the report folder or document library that is specified in the **Microsoft Dynamics AX report folder** field.

9.  Click **Validate settings** to verify that the information that you entered in this form is correct, and to verify that the report folder or document library has been created.

  


