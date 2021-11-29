---
title: Recover a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager
TOCTitle: Recover an AX 2012 R2 environment with DPM
ms:assetid: 6016640f-782d-489e-983b-9cb9b33badbe
ms:mtpsurl: https://technet.microsoft.com/library/Dn527685(v=AX.60)
ms:contentKeyID: 59626216
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Recover a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the Create New Protection Group wizard for Microsoft System Center 2012 Data Protection Manager (DPM) to recover Microsoft Dynamics AX 2012 R2.

You must first use the Volume Shadow Copy Service writer for Microsoft Dynamics AX (AX VSS writer) and DPM to help protect your AX 2012 R2 environment. For more information, see [Protect a Microsoft Dynamics AX 2012 R2 environment with System Center 2012 Data Protection Manager](protect-a-microsoft-dynamics-ax-2012-r2-environment-with-system-center-2012-data-protection-manager.md).

For an overview of what you can help protect and recover by using the AX VSS writer and DPM, see [Protecting Microsoft Dynamics AX environments with System Center 2012 Data Protection Manager (DPM)](protecting-microsoft-dynamics-ax-environments-with-system-center-2012-data-protection-manager-dpm.md).

The following list describes some of the limitations of the AX VSS writer when it is used for recovery:

  - The restoration environment is assumed to be a newly installed Microsoft Dynamics AX environment that uses a temporary name and is connected to a temporary database. You must restore the database, AOS, and then Microsoft SQL Server Reporting Services or Microsoft SQL Server Analysis Services, in that order.

  - The same service accounts that were previously used must be available in the environment.

  - After you restore the Microsoft Dynamics AX database, AOS instances must be restarted manually.

## Recover an AX 2012 R2 environment

1.  In the System Center 2012 DPM Administration Console, click **Recovery**. In the list of recoverable data, select the component to recover, and then select a recovery point to restore to.

2.  Click **Recover** to open the Review Recovery Selection wizard.

3.  On the **Select Recovery Type** page, click **Recover to original instance**.
    

    > [!NOTE]
    > <P>Although the <STRONG>Copy to a network folder</STRONG> option is available, this option is not supported for Microsoft Dynamics AX 2012.</P>



4.  On the **Specify Recovery Options** page, select the appropriate recovery options for your environment, and then click **Next**.

5.  Review the information on the **Summary** page, and then click **Recover**.

## Troubleshoot issues when you recover an environment by using DPM

This section describes issues that you might encounter and how you can recover from them.

## DPM encounters error 52, "Couldn’t communicate with DPM agent"

**Symptom:** Replica creation, recovery point creation, or the consistency check failed, and an error 52 was generated.

**Resolution:** Enable throttling for the DPM agent that experiences communication issues. For more information, see [Using Network Bandwidth Usage Throttling](https://technet.microsoft.com/library/hh758159.aspx). For backups, if you continue to receive this error, a consistency check usually transfers the last bits of data and produces a replica in the **OK** state. We use 3 Mbps as the throttling default. You might want to adjust throttling based on your network bandwidth.

  


