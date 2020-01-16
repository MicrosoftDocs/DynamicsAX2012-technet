---
title: (USA) Use logging to troubleshoot Commerce Services
TOCTitle: (USA) Use logging to troubleshoot Commerce Services
ms:assetid: 904a4e01-97ab-4c3c-ae6c-a13bf222d3f0
ms:mtpsurl: https://technet.microsoft.com/library/Hh209368(v=AX.60)
ms:contentKeyID: 36058531
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Use logging to troubleshoot Commerce Services 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can turn on operation logging when you want to troubleshoot problems with Commerce Services for Microsoft Dynamics ERP. Logging creates a log file that lists all requests from Microsoft Dynamics AX to Commerce Services. Enable logging for troubleshooting only, because logging adversely affects performance. Always turn logging off after troubleshooting.


> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



1.  Click **Organization administration** \> **Setup** \> **Commerce Services** \> **Configuration checklist**. Then, click **Enable operation logging**.
    
    \- or -
    
    Click **Organization administration** \> **Setup** \> **Commerce Services** \> **Operation log**.

2.  Select the **Enable operation logging** check box.

3.  Click **Browse**, and then select the folder in which you want to keep the log file.

4.  Perform the task that you want to troubleshoot, and then view the log file to help resolve the problem.

5.  When you finish, perform step 1 again, and then clear the **Enable operation logging** check box to turn off logging.

## See also

[(USA) View and resolve exceptions for Commerce Services](usa-view-and-resolve-exceptions-for-commerce-services.md)

  


