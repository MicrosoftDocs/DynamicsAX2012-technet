---
title: Enter parameters for Retail Scheduler
TOCTitle: Enter parameters for Retail Scheduler
ms:assetid: bfe69872-8fb9-41d9-8f61-d206055dbd87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679934(v=AX.60)
ms:contentKeyID: 49557916
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Enter parameters for Retail Scheduler 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Retail scheduler manages communications between Microsoft Dynamics AX and channels. Use the **Retail scheduler parameters** form to configure Retail scheduler.

In AX 2012 R2 and AX 2012 Feature Pack, you can use the parameters form to turn on data distribution through Retail scheduler. In addition, some parameters can be used to tune the performance of the system.

## Enter parameters for Retail scheduler in AX 2012 R3

If you are using AX 2012 R3, use the following procedure to set up parameters for Retail scheduler.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail scheduler parameters**.

2.  On the **General** FastTab, enter the following information:
    
      - **Server name** –The name of the computer that hosts the message database for Async Server.
    
      - **Database server instance** – The name of the SQL Server instance that hosts the message database for Async Server.
        

        > [!NOTE]
        > <P>If you’re using the default instance in Microsoft SQL Server Express, you must leave this field blank. If you’re using a subsequent instance in SQL Server Express, enter the instance name.</P>

    
      - **Database name**—The name of the message database for Async Server.
    
      - **Try count** – The number of times that a failed stage of the data transfer will be retried. If you enter zero, the number of retries is unlimited.
    
    The **SQL Change tracking** field indicates whether SQL Server change tracking is enabled on the Microsoft Dynamics AX database. Change tracking must be enabled to use data distribution features in Retail. Contact the database administrator if change tracking is not enabled.

3.  On the **Monitoring** FastTab, enter the number of days that upload session history, download session history, and data packages in the working folders will be retained.
    
    For more information about upload sessions and download sessions, see [View or cancel retail data distribution sessions](view-or-cancel-retail-data-distribution-sessions.md). For more information about working folders, see [Specify working folders for Commerce Data Exchange](specify-working-folders-for-commerce-data-exchange.md).

4.  Click **Sync metadata** to synchronize configuration data for Commerce Data Exchange with the message database at headquarters.
    
    This process happens automatically every time a job is run. However, if you make configuration changes to Async Server that must take effect immediately, you can run the process manually by clicking this button.

5.  Click **Close** to close the form.

## Enter parameters for Retail scheduler in AX 2012 R2 or AX 2012 Feature Pack

If you are using AX 2012 R2 or AX 2012 Feature Pack, use the following procedure to set up parameters for Retail scheduler

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail scheduler parameters**.

2.  On the **General** tab, select **System in use** to turn on the distribution system. If you clear this option, preactions are not generated.

3.  In the **Number of documents in batch task** field, enter the largest number of documents that can be processed in a single batch job.

4.  On the **Data deletion** tab, enter a number of days in the following fields:
    
      - **Days actions exist** – Enter the number of days until an action is automatically deleted. Enter 0 (zero) to prevent automatic deletion. To delete actions immediately, enter -1.
        
        Deleting actions regularly can help improve performance. However, after actions are deleted, you cannot rerun a failed A job. Make sure that you monitor and correct jobs within the number of days that you select.
    
      - **Days scheduler logs exist** – Enter the number of days until a log file for Retail Scheduler is automatically deleted. Enter 0 (zero) to prevent automatic deletion. To delete log files immediately, enter -1.
    
      - **Days messages exist** – Enter the number of days until a message for Commerce Data Exchange: Synch Service is automatically deleted. Enter 0 (zero) to prevent automatic deletion. To delete messages immediately, enter -1.
        
        You can also delete messages manually by running the **Delete messages** batch job. (Click **Retail** \> **Periodic** \> **Data distribution** \> **Delete messages**.) The batch job deletes only the messages that have been uploaded to Microsoft Dynamics AX. (Click **Retail** \> **Inquiries** \> **Commerce Data Exchange** \> **Async Server (previous version) status messages**.). The batch job does not delete messages from the message databases for Synch Service.

5.  Click **Close** to close the form.

  


