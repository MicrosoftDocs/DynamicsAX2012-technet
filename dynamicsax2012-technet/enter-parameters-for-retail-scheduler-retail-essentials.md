---
title: Enter parameters for Retail Scheduler (Retail essentials)
TOCTitle: Enter parameters for Retail Scheduler (Retail essentials)
ms:assetid: ffff4a64-5ca8-4cfe-8906-b0146984ca70
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736985(v=AX.60)
ms:contentKeyID: 62200462
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Enter parameters for Retail Scheduler (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail scheduler manages communications between Retail essentials and stores. Use the **Retail scheduler parameters** form to configure Retail scheduler. This topic explains how to set up the parameters for Retail scheduler.

You use the **Retail scheduler parameters** form to turn on data distribution through Retail scheduler. In addition, some parameters can be used to tune the performance of the system.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Enter parameters for Retail scheduler

Use the following procedure to set up parameters for Retail scheduler.

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Retail scheduler parameters**.

2.  On the **General** link, enter the following information:
    
      - **Server name** – The name of the computer that hosts the message database for Commerce Data Exchange: Async Server.
    
      - **Database server instance** – The name of the Microsoft SQL Server instance that hosts the message database for Async Server.
    
      - **Database name** – The name of the message database for Async Server.
    
      - **Try count** – The number of times that a failed stage of the data transfer should be retried. If you enter **0** (zero), the number of retries is unlimited.
    
    The **SQL Change tracking** field indicates whether SQL Server change tracking is enabled on the Retail essentials database. Change tracking must be enabled if you want to use data distribution. Contact the database administrator if change tracking is not enabled.

3.  On the **Monitoring** link, enter the number of days that upload session history, download session history, and data packages in the working folders should be retained.
    
    For more information about upload sessions and download sessions, see [View or cancel retail data distribution sessions](view-or-cancel-retail-data-distribution-sessions.md). For more information about working folders, see [Specify working folders for Commerce Data Exchange](specify-working-folders-for-commerce-data-exchange.md).

4.  Click **Sync metadata** to synchronize configuration data for Commerce Data Exchange with the message database at headquarters.
    
    This process is performed automatically every time that a job is run. However, if you make configuration changes to Async Server that must take effect immediately, you can run the process manually by clicking this button.

5.  Click **Close** to close the form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

