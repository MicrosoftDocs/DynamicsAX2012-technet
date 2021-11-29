---
title: (USA) Use logging for troubleshooting Sites Services
TOCTitle: (USA) Use logging for troubleshooting Sites Services
ms:assetid: f51e1c05-7306-4a46-be3d-00ce8548cff1
ms:mtpsurl: https://technet.microsoft.com/library/Hh227539(v=AX.60)
ms:contentKeyID: 36059998
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Use logging for troubleshooting Sites Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can turn on operation logging when you want to troubleshoot problems with Sites Services for Microsoft Dynamics ERP. Logging creates a log file that lists all requests from Microsoft Dynamics AX to Sites Services. Enable logging for troubleshooting only, because logging adversely affects performance. Always turn logging off after troubleshooting.

1.  Click **Organization administration** \> **Setup** \> **Sites Services** \> **Configuration checklist**. Then, click **Enable operation logging**.
    
    \- or -
    
    Click **Organization administration** \> **Setup** \> **Sites Services** \> **Operation log**.

2.  Select the **Enable operation logging** check box.

3.  Click **Browse**, and then select the folder in which you want to keep the log file.

4.  Perform the task that you want to troubleshoot, and then view the log file to help resolve the problem.

5.  When you finish, perform step 1 again, and then clear the **Enable operation logging** check box to turn off logging.

## See also

[(USA) View and resolve exceptions for Sites Services](usa-view-and-resolve-exceptions-for-sites-services.md)

  


