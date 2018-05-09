---
title: Configure SharePoint Services logging
TOCTitle: Configure SharePoint Services logging
ms:assetid: 4b492b9b-53bf-40c6-b2e7-9ca064d4d63d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731788(v=AX.60)
ms:contentKeyID: 35132624
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure SharePoint Services logging 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, there is no limit on the disk space that diagnostic logging for SharePoint can use. If you do not specify a limit, diagnostic logging can use all of the space on the hard disk of the Enterprise Search server.

## Configure logging

Use the following procedure to specify limits for diagnostic logging.

1.  In **SharePoint Central Administration**, click **Monitoring**.

2.  Under **Reporting**, click **Configure diagnostic logging**.

3.  In the **Number of days to store log files** section, enter a number.

4.  Select the **Restrict Trace Log disk space usage** option.

5.  In the **Maximum storage space for Trace Logs (GB)** field, enter a number.

6.  Click **OK**.

7.  Under **Reporting**, click **Configure usage and health data collection**.

8.  In the **Maximum log file size** field, enter a number.

9.  Click **OK**.

## See also

[SharePoint documentation: Configure diagnostic logging](http://go.microsoft.com/fwlink/?linkid=194152)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

