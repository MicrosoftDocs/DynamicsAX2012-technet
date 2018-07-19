---
title: Best practices for upgrade
TOCTitle: Best practices for upgrade
ms:assetid: 9f6adbf0-98ec-4e6f-a859-26f6e9ac7149
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715950(v=AX.60)
ms:contentKeyID: 62200025
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Best practices for upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes practices that can help improve your upgrade experience and minimize the possibility of problems during the upgrade process. We recommend that you review and follow these practices before you start your upgrade.

For detailed recommendations for best practices that are related to data upgrade, see the [Upgrade best practices](http://go.microsoft.com/fwlink/?linkid=238709) white paper.

## Clean up your data

Before you start your upgrade, we recommend that you run the Intelligent Data Management Framework (IDMF) against your source Microsoft Dynamics AX database. The IDMF is a tool that simplifies the removal of redundant and unnecessary data. A clean database can reduce the processing time that is required during the upgrade.

For information about how to download, install, and use the IDMF, see the TechNet topic [Intelligent Data Management Framework for Microsoft Dynamics AX \[AX 2012\]](http://go.microsoft.com/fwlink/?linkid=230455).

## Back up your data and customizations

Before you upgrade, back up the following information:

  - Back up your data. See the [Microsoft SQL Server documentation](http://go.microsoft.com/fwlink/?linkid=28107) or consult your Oracle documentation.
    

    > [!IMPORTANT]
    > <P>Oracle users should note that Microsoft Dynamics AX 2012 supports only Microsoft SQL Server. You will need to migrate your Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 data to SQL Server before upgrading. For more information, see <A href="supported-upgrade-paths.md">Supported upgrade paths</A>.</P>



  - Back up application files that contain your customizations. These include the \*.aod, \*.add, \*.ald, \*.ahd, and \*.khd files from all layers above the DIS layer (LOS, BUS, VAR, CUS, USR) on your existing system. For example, on a Microsoft Dynamics AX 4.0 system, copy the application files from \\Microsoft Dynamics\\4.0\\Application\\Appl\\Standard. These layers exist only if customizations have been made.

## Upgrade in a test environment first

Upgrade to Microsoft Dynamics AX 2012 in a test environment before you upgrade in your production environment.

Confirm that both the source and target test systems are working correctly before you start to upgrade in your production environment. For more information about testing, see [Test the system after upgrade](test-the-system-after-upgrade.md).


> [!TIP]
> <P>Microsoft Dynamics AX 2012 lets you preserve and reuse the preprocessed data that is created on a test source system. Therefore, you can reduce preprocessing time on your production source system. For more information, see <A href="using-the-preprocessing-upgrade-state-transfer-tool.md">Using the preprocessing upgrade state transfer tool</A>.</P>



## Verify that disk space and log size are sufficient

Verify that you have an appropriate amount of space on your target system's hard disk and in your database transaction log.

## Optimize the configuration of the database server

Make sure that Microsoft SQL Server is configured for the highest possible performance and throughput.

We recommend that you complete the upgrade process on a dedicated database server. If other applications are running on the server, they will compete with the upgrade process for resources.

Review the performance benchmarks of the existing database server, and determine whether you have to add more resources. For example, you might have to upgrade server components such as processors, memory, or storage. After you upgrade or change server components, we recommend that you test the server for optimum performance before you start the upgrade process for Microsoft Dynamics AX.

  


