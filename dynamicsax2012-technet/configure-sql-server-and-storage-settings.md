---
title: Configure SQL Server and storage settings
TOCTitle: Configure SQL Server and storage settings
ms:assetid: 83931d0a-2d75-4cc8-b29b-129ebd5b27e5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309734(v=AX.60)
ms:contentKeyID: 35132706
ms.date: 07/15/2015
mtps_version: v=AX.60
---

# Configure SQL Server and storage settings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about how to configure Microsoft SQL Server to support the business and model store databases for Microsoft Dynamics AX. To achieve optimal Microsoft Dynamics AX performance, you must correctly configure the database infrastructure.

This topic does not describe how to configure the infrastructure for reporting and analytics databases. For information about those features, see [Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md) and [Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md).

This information is designed for Microsoft Dynamics AX administrators and Microsoft SQL Server database administrators who are responsible for administration of the Microsoft Dynamics AX application.

To benefit from this topic, you must have knowledge in the following areas:

  - Windows Server administration.

  - SQL Server administration. Specific areas of knowledge include advanced configuration options, memory management, performance management, and troubleshooting.

  - Microsoft Dynamics AX system administration.

## Minimal SQL Server infrastructure

The configuration of Windows Server and SQL Server greatly affects the performance of the Microsoft Dynamics AX business database. This section provides detailed recommendations for the configuration of Windows Server and SQL Server.

The configuration recommendations are based on the following assumptions:

  - You are following the documented best practices for Windows Server and SQL Server.

  - You are using a dedicated server that runs SQL Server 2008 R2.

  - You are using a single instance of SQL Server that is dedicated to running the Microsoft Dynamics AX production databases.
    
    We recommend that you store your test and development databases on a separate server from the production databases.

## Configuring Windows Server

Verify that SQL Server is configured to run as a background service in Windows.

1.  In Windows Server 2008 R2, in Control Panel, click **System and Security**, and then click **System**.
    
    In Windows Server 2008, in Control Panel, double-click **System**.

2.  Click **Advanced system settings**.

3.  On the **Advanced** tab, under **Performance**, click **Settings**.

4.  On the **Advanced** tab, under **Processor scheduling**, select **Background services**, and then click **OK**.

## Configuring the server that runs SQL Server

In addition to the documented best practices for SQL Server, we recommend the following configuration settings for the SQL Server service.

  - Run the SQL Server service under an Active Directory domain account that has the minimum necessary privileges. For more information, see [SQL Server 2008 Security Overview for Database Administrators](http://go.microsoft.com/fwlink/?linkid=213202).

  - Confirm that the account for the SQL Server service has been granted the **Lock pages in memory** privilege. We recommend this setting, because it significantly affects whether other processes affect SQL Server. For instructions, see [How to: Enable the Lock Pages in Memory Option (Windows)](http://go.microsoft.com/fwlink/?linkid=213203). For more information, see the following Web pages:
    
      - The [Microsoft Customer Service and Support (CSS) SQL Server Engineers blog](http://go.microsoft.com/fwlink/?linkid=213204)
    
      - Knowledge base article 981483, [How to reduce paging of buffer pool memory in the 64-bit version of SQL Server](http://go.microsoft.com/fwlink/?linkid=213205)
    
      - [Slava Oks's WebLog](http://go.microsoft.com/fwlink/?linkid=213207)

  - Configure the account for the SQL Server service for instant file initialization. Instant file initialization is only available if the account for the SQL Server service, MSSQLSERVER, has been granted the SE\_MANAGE\_VOLUME\_NAME right. Members of the Windows Administrator group have this right and can grant it to other users by adding them to the **Perform Volume Maintenance Tasks** security policy. For more information, see [Database file initialization](http://go.microsoft.com/fwlink/?linkid=213208).

  - Enable the TCP/IP network protocol. Depending on the edition of SQL Server that you use, this protocol may be automatically installed during installation. For instructions, see [How to: Enable or Disable a Server Network Protocol (SQL Server Configuration Manager)](http://go.microsoft.com/fwlink/?linkid=213210).

  - Disable hyperthreading. This step must be performed in the BIOS settings of the server. For instructions, see the hardware documentation for your server.

## Configuring the instance of SQL Server

In addition to the documented best practices for SQL Server, we recommend the following storage settings for the instance of SQL Server.

## Configuring max degree of parallelism

The **max degree of parallelism** option is a setting that affects the entire instance of SQL Server. Microsoft Dynamics AX workloads generally perform better when intra-query parallelism is disabled. However, the upgrade process benefits from parallelism, as do activities that are used exclusively for batch jobs or maintenance. Use the following settings when the system performs maintenance activities or an upgrade:

  - Before an upgrade to a new release of Microsoft Dynamics AX, or before a large number of maintenance or batch activities, set **max degree of parallelism** to the smallest of the following values:
    
      - 8
    
      - The number of physical processor cores
    
      - The number of physical processor cores per non-uniform memory access (NUMA) node

  - When the Microsoft Dynamics AX database is used in a production environment, set **max degree of parallelism** to 1.

Use the following statements to set the value of **max degree of parallelism**.

Examine the output from the second sp\_configure 'max degree of parallelism' statement, and confirm that the value has been changed. In the following query, the first sp\_configure 'max degree of parallelism' statement sets the value of **max degree of parallelism** to 1. The second sp\_configure 'max degree of parallelism' statement returns a value of 1.

    EXEC sp_configure 'show advanced options', 1;
    RECONFIGURE; 
    GO
    EXEC sp_configure 'max degree of parallelism', 1;
    RECONFIGURE;
    GO
    EXEC sp_configure;

For more information, see [max degree of parallelism Option](http://go.microsoft.com/fwlink/?linkid=213211). For general guidelines, see Knowledge base article 329204, [General guidelines to use to configure the MAXDOP option](http://go.microsoft.com/fwlink/?linkid=213212). For tips from the SQL Server team, visit the SQL Server Relational Engine team's blog, [SQL Server Engine Tips](http://go.microsoft.com/fwlink/?linkid=213213).

## Configuring max server memory

SQL Server dynamically acquires and frees memory as required. Typically, an administrator does not have to specify how much memory is allocated to SQL Server. However, the **max server memory** option can be useful in some environments. Make sure that sufficient memory is available for the operation of Windows Server. For more information, see [Configure SQL Server and storage settings](configure-sql-server-and-storage-settings.md), later in this topic.

If you find that the dynamic allocation of memory adversely affects the operation of Windows Server, adjust the value of **max server memory** based on the available random access memory (RAM). For more information, see [Effects of min and max server memory](http://go.microsoft.com/fwlink/?linkid=213214).

## Monitoring available memory

Make sure that sufficient memory is available for the operation of Windows Server. For example, make sure that you run a dedicated instance of SQL Server on a server that has at least 4 gigabytes (GB) of memory. If the available memory for the server drops below 500 megabytes (MB) for extended periods, the performance of the server may degrade.

Use the **Memory: Available Mbytes** performance counter for the Windows Server operating system to determine whether the available memory drops below 500 MB for extended periods. If the available memory drops below 500 MB frequently or for extended periods, we recommend that you reduce the **max server memory** setting for SQL Server or increase the physical memory of the server.

Detailed guidance about memory management is beyond the scope of this topic. For more information about how to monitor memory and troubleshoot performance issues, see the Windows Server and SQL Server documentation.

## Allocating storage for tempdb

We recommend that you determine the total size of the data files and transaction log files that are required for the tempdb database, and that you set a specific value. Do not use automatic growth, or autogrow, setting for space management. Instead, use autogrow as a safety mechanism, so that tempdb can grow if tempdb files use the space that was originally allocated to them. Follow this process to determine the number and placement of data files.

  - Determine the number of processors that are available to SQL Server. Unless you are using an affinity mask, this number is same as the total number of processors that you see on the **Performance** tab of Windows Task Manager. When hyperthreading is not enabled, each processor corresponds to a processor core. Affinity masks and processor cores are beyond the scope of this topic. For more information, see the Windows Server and SQL Server documentation.

  - Based on performance testing of the OLTP workload for Microsoft Dynamics AX, we recommend that you maintain one tempdb data file per processor. For more information, see the performance benchmark reports on [PartnerSource](http://go.microsoft.com/fwlink/?linkid=143994) or [CustomerSource](http://go.microsoft.com/fwlink/?linkid=213216).

  - Isolate tempdb on dedicated storage, if you can. We recommend that you move the primary data file and log file for tempdb to high-speed storage, if high-speed storage is available. The Microsoft Dynamics AX database runs in read committed snapshot isolation (RCSI) mode. In RCSI mode, row versions are stored in tempdb. By creating multiple files for tempdb data, even if these files reside on the same storage device, you can improve the performance of tempdb operations.

  - Determine the size of the tempdb data files and log files. You must create one primary data file and one log file. Determine how many additional, secondary data files you require for the tempdb data. For best results, create data files of equal size. The total number of data files must equal the total number of processor cores. The aggregate size of the primary data file and all other data files must equal the total data size that you determined for the tempdb database.
    
    For more information, see [Optimizing tempdb performance](http://go.microsoft.com/fwlink/?linkid=213217).

  - Resize the primary data file and log file for tempdb. Move the primary data file and log file to dedicated storage, if dedicated storage is available. The primary tempdb data file cannot be moved while the instance of SQL Server is running. To complete the move, you must use an ALTER DATABASE statement and restart the instance of SQL Server. For more information, see [ALTER DATABASE](http://go.microsoft.com/fwlink/?linkid=213218).
    

    > [!NOTE]
    > <P>The data files and transaction log files for tempdb can reside on the same storage device.</P>



  - If space is available on the drive where tempdb files are allocated, do not configure the autogrow property for data files and log files as a percentage. Instead, configure the autogrow property as a specific number of megabytes. If you can, configure the data files and log files to grow by 100 to 500 MB, depending on the available space. Monitor the data files, and when they grow, adjust the original allocation to prevent automatic growth later. If the autogrow property is configured in megabytes instead of as a percentage, the allocation of space is more predictable, and the chance of extremely small or large growth increments is reduced.

  - Monitor the tempdb data files and log files to make sure that they are all sized correctly, and that all data files are of equal size. Use SQL Server Management Studio or a transact-SQL query to view the database properties. Verify that all the data files are of equal size, and that they have the same size as the value that you originally provided. If one or more files have grown, adjust the initial size of all files.

## Configuring the Microsoft Dynamics AX business database

We recommend the following settings for the Microsoft Dynamics AX business database. You can use SQL Server Management Studio or the appropriate ALTER DATABASE statement to configure these settings. For more information, see [ALTER DATABASE](http://go.microsoft.com/fwlink/?linkid=213218).

  - Set COMPATIBILITY\_LEVEL to 110 for SQL Server 2012, or to 100 for SQL Server 2008 or SQL Server 2008 R2.

  - Set READ\_COMMITTED\_SNAPSHOT to **on**. Performance testing has shown that Microsoft Dynamics AX performs better when the READ\_COMMITTED\_SNAPSHOT isolation option is set to **on**. You must use an ALTER DATABASE statement to set this option. This option cannot be set by using SQL Server Management Studio.
    
    Run the following query, where \<database name\> is the name of the Microsoft Dynamics AX database. There can be no other active connections in the database when you run this query.
    
        ALTER DATABASE <database name>
            SET READ_COMMITTED_SNAPSHOT ON;
    
    Query the sys.databases catalog view, and verify that the Microsoft Dynamics AX database contains a value of 1 in the is\_read\_committed\_snapshot\_on column. For more information, see the following Web pages:
    
      - [sys.databases](http://go.microsoft.com/fwlink/?linkid=213219)
    
      - [Choosing Row Versioning-based Isolation Levels](http://go.microsoft.com/fwlink/?linkid=213220)

  - Set AUTO\_CREATE\_STATISTICS and AUTO\_UPDATE\_STATISTICS to **on**. Set AUTO\_UPDATE\_STATISTICS\_ASYNC to **off**. Performance testing has shown that Microsoft Dynamics AX performs better when the options have these settings.

  - Make sure that the AUTO\_SHRINK option is set to **off**. When database files are automatically shrunk, performance of the database degrades. We recommend that the database administrator manually shrink the database files on a predefined schedule. For more information, see [Turn AUTO\_SHRINK OFF\!](http://go.microsoft.com/fwlink/?linkid=213221) on the SQL Server Storage Engine Team's blog.


> [!IMPORTANT]
> <P>All Microsoft Dynamics AX databases must use the same SQL collation type. These databases include the business database, model store database, Microsoft SQL Server Reporting Services database, and Microsoft SQL Server Analysis Services database.</P>



## Plan database storage

Designing a data storage solution involves multiple interrelated aspects. We recommend that you follow this process when you must complete this task.

1.  Characterize the input/output (I/O) load of the application. The I/O characteristics depend on your business requirements, and on the Microsoft Dynamics AX modules and components that you deploy. To determine your I/O characteristics, answer the following questions:
    
      - What is the read ratio versus write ratio of the application?
    
      - What is the typical I/O volume, or I/O per second (IOPs)?
    
      - How much of the I/O is sequential, and how much is random?

2.  Determine the availability and performance requirements for the database system.

3.  Determine the hardware that is required to support the analysis that you performed made in steps 1 and 2.

4.  Configure SQL Server to take advantage of the hardware that you determined in step 3.

5.  Track the performance as the workload changes.

Step-by-step guidance about database architecture and storage is beyond the scope of this topic. For more detailed recommendations from the SQL Server team, see [Microsoft SQL Server Storage Top 10 Best Practices](http://go.microsoft.com/fwlink/?linkid=213199) and [Physical Database Storage Design](http://go.microsoft.com/fwlink/?linkid=213201).

## Configuring physical storage

This section provides general recommendations for physical storage. Determine the applicability of these recommendations to your environment. Some storage area network (SAN) vendors may have alternative recommendations that take precedence. Recommendations are listed in order of priority.

  - Many factors contribute to optimal I/O performance for a disk. By default, Windows Server 2008 aligns partitions. When you upgrade to Windows Server 2008, preexisting partitions are not automatically aligned and must be manually rebuilt to guarantee optimal performance. Therefore, until you rebuild the migrated partitions, alignment of disk partitions remains a relevant technology.
    
    Check existing disks on the server, and be aware of the differences in the analysis of basic partitions and dynamic volumes. Rebuild the partitions, if you can, and appropriate and create all new partitions based on guidance from the SAN vendor. If the vendor does not provide recommendations, follow the best practices for SQL Server. See [Disk Partition Alignment Best Practices for SQL Server](http://go.microsoft.com/fwlink/?linkid=213222).
    
    The partition offset value must be a multiple of the stripe size. In other words, the expression, *partition offset / stripe size*, must resolve to an integer value.

  - Create the tempdb database files, data files for the Microsoft Dynamics AX database, and Microsoft Dynamics AX log files on disk arrays of type RAID 1, RAID 0 + 1, or RAID 10. We recommend RAID 10 for these files. Do not use RAID 5.

  - Store the data files for the Microsoft Dynamics AX database on separate physical stores from the transaction log files.

  - Store the tempdb data files on a separate physical store from the data files and log files for the Microsoft Dynamics AX database.

  - Store other database files on separate physical stores from the data files and log files for tempdb and the Microsoft Dynamics AX database.

## Summary

To help achieve optimal Microsoft Dynamics AX performance, you must correctly plan and configure and the settings for SQL Server and storage. Additionally, you may have to adjust the database configuration periodically.

## See also

[System architecture](system-architecture.md)

[Planning hardware infrastructure](planning-hardware-infrastructure.md)

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

[Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md)

[Microsoft Dynamics AX Performance Team's blog](http://go.microsoft.com/fwlink/?linkid=213223)

  


