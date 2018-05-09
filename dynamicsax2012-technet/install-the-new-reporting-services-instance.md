---
title: Install the new Reporting Services instance
TOCTitle: Install the new Reporting Services instance
ms:assetid: 4dcad543-cd17-4d98-81ac-13506d5404f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh389770(v=AX.60)
ms:contentKeyID: 36899749
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Install the new Reporting Services instance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can install multiple instances of Microsoft SQL Server Reporting Services on the same computer. Each instance will have its own report server database, configuration files, and virtual directories. One instance can be the default instance. All other instances must be named instances. A server can run multiple instances of Reporting Services at the same time, and each instance runs independently of the other instances.

Install an additional Reporting Services instance on the computer that is running Reporting Services. To install additional instances, you must run the SQL Server Setup Wizard one time for each report server instance that you want to install. You cannot install multiple instances at the same time.

This topic assumes that the new instance of Reporting Services that you install meets the version requirements that are listed in [Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md).

## Installing a default instance

The first time that you run the SQL Server Setup Wizard, you have the option of installing the first report server instance as a default installation if the computer meets the requirements. A default installation is one that uses all default values. This results in a report server that is ready to use when Setup is completed. You can have only one default instance of Reporting Services on a single SQL Server installation.

## Installing a named instance

When you install multiple report server instances on the same computer, each additional instance must be installed as a named instance. To install an additional, named instance, you must run the SQL Server Setup Wizard again. When you run Setup, keep the following points in mind:

  - On the **Installation Type** page, select the option to perform a new installation. This option lets you install an additional instance of Reporting Services.
    
    The name of the option varies, depending on the version of SQL Server that you are using. The following picture shows the **Installation Type** page of the SQL Server 2012 Setup Wizard. In this version, the option is named **Perform a new installation of SQL Server 2012**.
    
    ![Installation Type page](images/Hh389770.BI_A(AX.60).png "Installation Type page")

  - On the **Instance Configuration** page, enter a name for the new instance of Reporting Services.
    
    The following picture shows the **Instance Configuration** page of the SQL Server 2012 Setup Wizard.
    
    ![Instance Configuration page](images/Hh389770.BI_SQLSetup_InstanceConfig(AX.60).png "Instance Configuration page")

  - On the **Reporting Services Configuration** page, select the option to install—but not configure—the report server.
    
    The name of the option varies, depending on the version of SQL Server that you are using. The following picture shows the **Reporting Services Configuration** page of the SQL Server 2012 Setup Wizard. In this example, Reporting Services is running in native mode, and the option is named **Install only**.
    
    ![Reporting Services Configuration page](images/Hh389770.BI_SQLSetup_SSRSConfig(AX.60).png "Reporting Services Configuration page")

For more information about how to run the SQL Server Setup Wizard, see the SQL Server documentation on [TechNet](http://technet.microsoft.com/en-us/library/bb545450\(v=msdn.10+\).aspx) or [MSDN](http://msdn.microsoft.com/en-us/library/bb545450\(v=msdn.10+\).aspx) for the version that you are using.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

