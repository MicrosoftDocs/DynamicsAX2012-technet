---
title: Create a new Microsoft Dynamics AX configuration
TOCTitle: Create a new Microsoft Dynamics AX configuration
ms:assetid: e508dc82-d780-4eda-bf5d-200228d1c3f1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh389774(v=AX.60)
ms:contentKeyID: 36899753
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Create a new Microsoft Dynamics AX configuration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedure to create a new configuration of Microsoft Dynamics AX and to export the configuration settings to a file.

1.  Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration** to open the Microsoft Dynamics AX Configuration Utility.

2.  Click **Manage** \> **Create configuration**. The **Create Configuration** window is displayed.

3.  Enter a name for the configuration, and then click **OK**. The configuration is created.

4.  Click the **Connection** tab.

5.  Verify that the server name, instance name, and port information for the Application Object Server (AOS) are correct.

6.  Click **Refresh** to update the configuration.

7.  Click **Manage** \> **Export configuration to file**. The **Export Configuration** window is displayed.

8.  Save the configuration to a file by following these steps:
    
    1.  Name the file **Microsoft.Dynamics.AX.ReportConfiguration.axc**.
    
    2.  Save the file to the appropriate location, depending on the version of SQL Server that you are using.
        
          - If you are using SQL Server 2008, save the file to: \\Program Files\\Microsoft SQL Server\\MSRS10.\[SSRSInstanceName\]\\Reporting Services\\ReportServer\\bin.
        
          - If you are using SQL Server 2008 R2, save the file to: \\Program Files\\Microsoft SQL Server\\MSRS10\_50.\[SSRSInstanceName\]\\Reporting Services\\ReportServer\\bin.
        
          - If you are using SQL Server 2012, save the file to: \\Program Files\\Microsoft SQL Server\\MSRS11.\[SSRSInstanceName\]\\Reporting Services\\ReportServer\\bin.
        
          - If you are using SQL Server 2014, save the file to: \\Program Files\\Microsoft SQL Server\\MSRS12.\[SSRSInstanceName\]\\Reporting Services\\ReportServer\\bin.

  


