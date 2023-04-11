---
title: Troubleshoot common AOS problems
TOCTitle: Troubleshoot common AOS problems
ms:assetid: bb10d97d-e8b9-48bc-8a5c-963d87da5556
ms:mtpsurl: https://technet.microsoft.com/library/JJ680902(v=AX.60)
ms:contentKeyID: 49624321
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Troubleshoot common AOS problems 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides information about how to troubleshoot issues with an Application Object Server (AOS) instance.

## Client cannot connect to an AOS instance

One of the following may be the cause if a client cannot connect to an Application Object Server (AOS) instance.

## AOS is starting

The first time you start a client after the AOS has been installed, the AOS service may still be starting up. On the AOS computer, use the Services manager to determine whether the service has started.

## Port is not open

If the Application Object Server is installed on a computer with a firewall, be sure that the port you are trying to connect to is open. The default port is 2712, but additional instances may install on ports 2713, 2714, and so on.

## AOS instance cannot connect to new database

If you are trying to connect to a database that was not created by Setup, the AOS account (the domain account or Network Service account associated with an AOS instance) may not have appropriate rights in SQL Server. The AOS account must be a user in the database and be assigned to the database roles **db\_ddladmin**, **db\_datareader**, and **db\_datawriter**. The user account must have execute rights to the **createserversessions** and **createusersessions** stored procedures.

## AOS service does not start

If the AOS service does not start automatically, you can attempt to start the service manually in **Control Panel** \> **Administrative Tools** \> **Services**. If the service still does not start, see the Windows System Event log for error details.

By default, if a Windows service takes longer than 30 seconds to start, the system displays a message informing you that the service did not respond to a start command. The AOS Windows service can take longer than 30 seconds to start, and the lack of a response in 30 seconds can cause the service to stop. Therefore, if an AOS instance repeatedly does not start, you may want to configure the registry to give Windows services more time, such as 120 seconds, to start before the error message is displayed.


> [!WARNING]
> <P>This section describes how to modify the registry so that the AOS Windows service has enough time to start before Windows displays an error message. Be aware that serious problems can occur if you modify the registry incorrectly. We recommend that you back up the registry before you modify it. If a problem occurs, you can restore it. For more information about how to back up and restore the registry, see <A href="https://go.microsoft.com/fwlink/?linkid=214428">Backup and recovery</A>.</P>



1.  Click **Start**, click **Run**, type **regedit**, and then click **OK**.

2.  Locate and then click the following registry subkey: \\HKEY\_LOCAL\_MACHINE\\System\\CurrentControlSet\\Control

3.  Right-click **Control**, and then click **New** \> **DWORD (32-Bit) Value**.

4.  Right-click the new key, and then click **Rename**. Enter the name **ServicePipeTimeout**.

5.  Right-click the key again, and then click **Modify**.

6.  In the **Value data** text box, enter **120000**, and then click **OK**. The AOS Windows service now has 120 seconds to start before the system displays an error message.

If the AOS instance does not start after you implement this registry key, use the Microsoft Dynamics AX Server Configuration utility to verify that the AOS instance is using a unique port. Port conflicts prevent AOS from starting. For more information, see [Change AOS ports](change-aos-ports.md).

## AOS does not connect to mirrored database in failover scenario

This scenario is as follows:

1.  Your Microsoft Dynamics AX environment is configured with a primary SQL database and a mirrored database.

2.  The AOS is configured to use the primary database.

3.  The primary database goes offline and the system redirects traffic to the mirrored database.

4.  The AOS service stops.

This is a known limitation of Microsoft Dynamics AX. If the primary database goes offline, you must stop the AOS (if it is not already stopped) and change the AOS configuration to use the mirrored database. After you change the configuration, you must restart the AOS. The Microsoft Dynamics AX AOS must always point to a primary database; failover is not supported. For more information about changing an AOS configuration, see [Manage an AOS configuration](manage-an-aos-configuration.md).

## See also

[Allow debugging](allow-debugging.md)

  


