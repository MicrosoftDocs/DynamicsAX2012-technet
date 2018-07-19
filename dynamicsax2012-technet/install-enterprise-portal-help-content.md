---
title: Install Enterprise Portal Help content
TOCTitle: Install Enterprise Portal Help content
ms:assetid: 55371efb-f62f-46dc-866c-483ac74dd0ee
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433511(v=AX.60)
ms:contentKeyID: 36941292
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Install Enterprise Portal Help content 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The MS.EP.HC*-LanguageCode*.cab file contains Help topics for Enterprise Portal pages. The .cab file is automatically deployed and configured on the Web server when you install Enterprise Portal. If the Help does not display, use the procedure in this topic to manually install Enterprise Portal Help.

## Before you begin

  - Deploy SharePoint language packs on the Enterprise Portal server. Note the SharePoint Language IDs for each language pack you deploy.

  - Verify that the SharePoint Timer service is running. Enterprise Portal Help is installed as a job by the SharePoint Timer service.

## Install Enterprise Portal Help

1.  Locate the MS.EP.HC*-LanguageCode*.cab files on the Installation DVD. By default, the files are located in the \\Support\\EPHelp directory.

2.  Copy each of the .cab files into its corresponding language ID directory on the Web server at the following location. This path applies to SharePoint 2010 servers. For SharePoint 2013 servers, replace ‘14’ with ‘15’:
    
    *Drive*:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\HCCab\\*LanguageCode*\\
    
    For example, download the Arabic version of the MS.EP.HC-1025.cab file to this directory: C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\HCCab\\1025\\ on a SharePoint 2010 server.

3.  Open the SharePoint Management Shell on the Enterprise Portal Web server. Click **Start**, click **All Programs**, click **SharePoint Products**, and then click **SharePoint Management Shell**.

4.  In the management shell, run the following command. Remember to change the ‘14’ to ‘15’ for SharePoint 2013 servers:
    
    Install-SPHelpCollection -LiteralPath "*Drive*:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\HCCab\\\<*language\_code*\>\\MS.EP.HC*-LanguageCode*.cab"
    
    For example, to install Enterprise Portal Help for Spanish on a SharePoint 2013 server, run the following command:
    
    Install-SPHelpCollection -LiteralPath "*Drive*:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\15\\HCCab\\3082\\MS.EP.HC-3082.cab"

5.  Repeat the command for each language that you want to install. After SharePoint finishes the Timer job, you can open Enterprise Portal Help by clicking the Help icon on any Enterprise Portal page.

## See also

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

  


