---
title: Deploy updates to Enterprise Portal
TOCTitle: Deploy updates to Enterprise Portal
ms:assetid: d64915fb-0fe3-46c0-8ee9-15ee5368b62e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538462(v=AX.60)
ms:contentKeyID: 39508891
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deploy updates to Enterprise Portal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedures describe how to apply updates to an installation of Enterprise Portal for Microsoft Dynamics AX.

## Update an existing Enterprise Portal deployment

1.  Install the update on the Microsoft Dynamics AX database, Application Object Server (AOS), and the Microsoft Dynamics AX client, and complete the Software update checklist.

2.  Install the update on all Enterprise Portal servers.

3.  Run the Enterprise Portal update utility, AXUpdatePortal.exe, on all Enterprise Portal web servers. The utility deploys web-related items from the Application Object Tree (AOT) to all Enterprise Portal sites on a web server. For more information, see [AxUpdatePortal Utility](https://technet.microsoft.com/en-us/library/dd261467\(v=ax.60\)).
    
    1.  Open a Command Prompt window.
    
    2.  Change the working directory by entering the following command.
        
            cd C:\Program Files\Microsoft Dynamics AX\60\Setup
    
    3.  Run the Enterprise Portal update utility by entering the following command.
        
            AxUpdatePortal -updateWebSites -iisreset -verbose > "C:\EPUpdate.log"

## Initialize Role Center profiles

You must complete this procedure from a computer that is running a Microsoft Dynamics AX client.

1.  Open the **Initialize user profiles** form. Click **Organizational administration** \> **Setup** \> **Role center** \> **Initialize role center profiles**.

2.  Select the profiles that your organization uses, and then click **OK**.

3.  When you are asked whether you want to overwrite a profile record, click **No to all**.

4.  When you are asked whether you want to overwrite a cue, click **No to all**.

5.  When you are asked whether you want to overwrite a quick link, click **No to all**.

6.  When you are asked whether you want to overwrite a time period, click **No to all**.

  


