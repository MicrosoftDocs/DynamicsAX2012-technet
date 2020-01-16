---
title: Protect a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager
TOCTitle: Protect an AX 2012 R2 environment with DPM
ms:assetid: b5b01674-f894-4dd6-9694-ab5bc1a8351a
ms:mtpsurl: https://technet.microsoft.com/library/Dn527686(v=AX.60)
ms:contentKeyID: 59626219
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Protect a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the Create New Protection Group wizard for Microsoft System Center 2012 Data Protection Manager (DPM) to help protect Microsoft Dynamics AX 2012 R2.

You must first install the Volume Shadow Copy Service writer for Microsoft Dynamics AX (AX VSS writer) and a DPM Protection Agent on the computer that runs the instance of Microsoft Dynamics AX Application Object Server (AOS) that you want to help protect. For more information, see [Install the VSS writer for Microsoft Dynamics AX](install-the-vss-writer-for-microsoft-dynamics-ax.md).

For an overview of what you can help protect and recover by using the AX VSS writer and DPM, see [Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md).

## Protect an AX 2012 R2 environment

1.  In the System Center 2012 DPM Administration Console, click **Protection**, and then click **New**.

2.  In the Create New Protection Group wizard, if the **Welcome** page appears, click **Next**.

3.  On the **Select Protection Group Type** page, click **Servers**.

4.  On the **Select Group Members** page, expand the server on which the AOS instance that links your environment is installed, select the Microsoft Dynamics AX components to help protect, and then click **Next**.

5.  On the **Select Data Protection Method** page, enter a name for the protection group, select the protection method to use, and then click **Next**.

6.  On the **Specify Short-Term Goals** page, specify how long to retain backups and when to run backups, and then click **Next**.

7.  On the **Review Disk Allocation** page, define how to allocate space for backups, and then click **Next**.

8.  On the **Choose Replica Creation Method** page, select how to create replicas, and then click **Next**.

9.  On the **Consistency Check Options** page, select when to run consistency checks, and then click **Next**.

10. On the **Summary** page, review the options that you selected, and then click **Create Group**.

## Troubleshoot issues when you protect an environment by using DPM

This section describes issues that you might encounter and how you can recover from them.

## DPM encounters error 52, "Couldn’t communicate with DPM agent"

**Symptom:** Replica creation, recovery point creation, or the consistency check failed, and an error 52 was generated.

**Resolution:** Enable throttling for the DPM agent that experiences communication issues. For more information, see [Using Network Bandwidth Usage Throttling](http://technet.microsoft.com/en-us/library/hh758159.aspx). For backups, if you continue to receive this error, a consistency check usually transfers the last bits of data and produces a replica in the **OK** state. We use 3 Mbps as the throttling default. You might want to adjust throttling, based on your network bandwidth.

## Transient registry export error

**Symptom:** Backup takes longer than you expected.

**Resolution:** Log on to the computer that is taking a long time to be backed up. If a message box for the registry export error is visible, check the temporary backup directory. If the backup file has been created, you can safely click **OK** in the message box for the registry export error and continue with the backup.

## See also

[Recover a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](recover-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md)

  


