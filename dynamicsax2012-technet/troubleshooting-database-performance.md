---
title: Troubleshooting database performance
TOCTitle: Troubleshooting database performance
ms:assetid: 4dc713d4-18ef-461f-920e-2c5f199166b8
ms:mtpsurl: https://technet.microsoft.com/library/Hh699644(v=AX.60)
ms:contentKeyID: 42520741
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshooting database performance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to troubleshoot database performance.

## Identifying a user session in SQL Server

In previous versions of Microsoft Dynamics AX, the **Online users** form contained a column that provided a session process ID (SPID) for each client session. This column was useful for debugging blocked sessions. Specifically, the SPID column was used to find a user session that corresponded to a specific SPID. In Microsoft Dynamics AX 2012, the SPID column is no longer available in the **Online users** form.

In Microsoft Dynamics AX 2012, information about the user session can be included in the connection context for Microsoft SQL Server. because the inclusion of this information has a small effect on performance, the functionality is not turned on by default.


> [!IMPORTANT]
> <P>This topic contains steps that describe how to modify the registry. However, serious problems might occur if you modify the registry incorrectly. Therefore, make sure that you follow these steps carefully. For additional protection, back up the registry before you modify it. You can then restore the registry if a problem occurs. For more information, see <A href="https://windows.microsoft.com/en-us/windows7/back-up-the-registry">Back up the registry</A>.</P>



### Include session information in the SQL Server connection context

1.  Click **Start**, click **Run**, type **regedit** in the **Open** box, and then click **OK**.

2.  Locate the following registry key:
    
    HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\services\\Dynamics Server\\6.0\\01\\Original (installed configuration)
    
    The Original (installed configuration) key is the key name for the current server configuration, if the configuration has not been changed from the default. If your system uses a configuration other than the configuration that was originally installed, locate the configuration that is currently active.

3.  Right-click the key, point to **New**, and then point to **String value**. Name the new value **connectioncontext**, and set the value to 1.

4.  Close the registry editor.

5.  Start the **Services** snap-in, and then restart the Application Object Server (AOS) service.

### Find session information

1.  Open Microsoft SQL Server Management Studio.

2.  Run the following query to view all sessions that are related to Microsoft Dynamics AX:
    
    select cast(context\_info as varchar(128)) as ci,\* from sys.dm\_exec\_sessions where program\_name like '%Dynamics%'
    
    The first two items in the ci (connection information) column are the Microsoft Dynamics AX user ID and the session ID.

3.  In the **Online users** form, you can now identify each session.

  


