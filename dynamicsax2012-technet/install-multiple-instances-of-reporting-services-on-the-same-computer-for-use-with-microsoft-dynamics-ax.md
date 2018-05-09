---
title: Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)
TOCTitle: Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)
ms:assetid: 0aca4bf4-aac9-4acd-9323-7547a8583c9f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh389760(v=AX.60)
ms:contentKeyID: 36899738
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can install multiple instances of Microsoft SQL Server Reporting Services on the same computer. In this kind of deployment environment, each instance of Reporting Services is connected to an independent Microsoft Dynamics AX installation. You may want to install multiple instances of Reporting Services on the same computer for the following reasons:

  - To support development and production installations of Microsoft Dynamics AX
    
    For example, in the following sample diagram, assume that *AOS instance 1* is a development installation of Microsoft Dynamics AX, and *AOS instance 2* is the production installation of Microsoft Dynamics AX.

  - To support multiple production installations of Microsoft Dynamics AX
    
    For example, if you are a Microsoft Dynamics AX solution provider, you may have to support multiple production installations of Microsoft Dynamics AX. For this scenario, assume that *AOS instance 1* (in the sample diagram) is a production installation of Microsoft Dynamics AX for one client, Northwind Traders. Assume that *AOS instance 2* is a production installation of Microsoft Dynamics AX for another client, Contoso Pharmaceuticals.

![Multiple SSRS instances installed on one computer](images/Hh389760.BI_MultiSSRS_TwoEnvironments(AX.60).gif "Multiple SSRS instances installed on one computer")

## Supported versions of Reporting Services

To install multiple instances of Reporting Services on the same computer, you must use one of the following versions of Reporting Services:

  - Reporting Services 2008 in native mode

  - Reporting Services 2008 in SharePoint integrated mode

  - Reporting Services 2008 R2 in native mode

  - Reporting Services 2008 R2 in SharePoint integrated mode

  - Reporting Services 2012 in native mode

  - Reporting Services 2014 in native mode


> [!NOTE]
> <P>You cannot install multiple instances of Reporting Services 2012 or 2014—that run in SharePoint integrated mode—on the same computer.</P>



For more information about the service packs and updates that must be installed with each version of Reporting Services, see the [Microsoft Dynamics AX system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

## How to install multiple instances of Reporting Services on the same computer

To set up an environment that has multiple Reporting Services instances on the same computer, use the following procedure.

1.  Configure the initial instance of Reporting Services and integrate it with Microsoft Dynamics AX. To do this, complete the procedures in [Checklist: Install the Reporting Services extensions and deploy reports](checklist-install-the-reporting-services-extensions-and-deploy-reports.md).

2.  Configure the next instance of Reporting Services and integrate it with Microsoft Dynamics AX. To do this, complete the following steps:
    
    1.  [Install the new Reporting Services instance](install-the-new-reporting-services-instance.md)
    
    2.  [Configure the new Reporting Services instance](configure-the-new-reporting-services-instance.md)
    
    3.  The action you should take in this step depends on which version of Microsoft Dynamics AX 2012 that you are using.
        
          - **If you are using cumulative update 7 for Microsoft Dynamics AX 2012 R2 or a later version of AX:** [Run the Install-AXReportInstanceExtensions command](run-the-install-axreportinstanceextensions-command.md)
            
            The Install-AXReportInstanceExtensions command is a Windows PowerShell command that modifies Reporting Services configuration files. If you do not run this command, you must *manually* modify the configuration files.
        
          - **If you are NOT using cumulative update 7 for Microsoft Dynamics AX 2012 R2 or a later version of AX:** [Modify Reporting Services configuration files](modify-reporting-services-configuration-files.md)
    
    4.  [Restart the new Reporting Services instance](restart-the-new-reporting-services-instance.md)
    
    5.  [Create a new Microsoft Dynamics AX configuration](create-a-new-microsoft-dynamics-ax-configuration.md)
    
    6.  [Connect Microsoft Dynamics AX to the new Reporting Services instance](connect-microsoft-dynamics-ax-to-the-new-reporting-services-instance.md)
    
    7.  [Deploy reports for the new Reporting Services instance](deploy-reports-for-the-new-reporting-services-instance.md)
    
    8.  [Revert to the original Microsoft Dynamics AX configuration](revert-to-the-original-microsoft-dynamics-ax-configuration.md)

3.  Repeat step 2 for each additional instance of Reporting Services.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

