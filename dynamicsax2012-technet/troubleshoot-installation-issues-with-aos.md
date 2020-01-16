---
title: Troubleshoot installation issues with AOS
TOCTitle: Troubleshoot installation issues with AOS
ms:assetid: e5b619c0-a99c-4841-bfc4-5d78ac5e1975
ms:mtpsurl: https://technet.microsoft.com/library/Hh575257(v=AX.60)
ms:contentKeyID: 39555424
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshoot installation issues with AOS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following section provides information that can help you troubleshoot issues that you may encounter when you install Application Object Server (AOS).

## An error occurred during the install custom action step within the AOS Server installer

If the AOS installation fails, you may receive the following message: “An error occurred during the install custom action step within the AOS Server installer.” This error may indicate that the event logs on the computer have conflicting names. In this case, the following message also appears in the log file: “Only the first eight characters of a custom log name are significant, and there is already another log on the system using the first eight characters of the name given.”

When AOS is installed, an event log that is named **Microsoft Dynamics AX Workflow** is created for the Workflow service. The custom action in Windows Installer that creates the Workflow event log does not verify whether an event log already exists that has the same first eight characters in the name. If another application has already created an event log that has the same first eight characters in the name, the operation to create the Workflow event log may fail. Therefore, the custom action fails, and Windows Installer rolls back the installation.

To work around this issue, you can rename the conflicting event log and attempt to install AOS again. Event logs are listed as subkeys under the following registry key: *HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\Eventlog*. After AOS is successfully installed, you can rename the conflicting registry key to its original name.


> [!WARNING]
> <P>This section describes how to modify the registry. Be aware that serious problems can occur if you modify the registry incorrectly. We recommend that you back up the registry before you modify it. Then, if a problem occurs, you can restore the registry. For more information about how to back up and restore the registry, see Microsoft Knowledge Base article number <A href="https://support.microsoft.com/kb/256986">256986</A>.</P>


  


