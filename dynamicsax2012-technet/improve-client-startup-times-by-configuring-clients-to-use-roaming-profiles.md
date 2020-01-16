---
title: Improve client startup times by configuring clients to use roaming profiles
TOCTitle: Improve client startup times by configuring clients to use roaming profiles
ms:assetid: 56f7b7b2-dbfc-4a08-b262-43f85fbd792f
ms:mtpsurl: https://technet.microsoft.com/library/Dn479031(v=AX.60)
ms:contentKeyID: 59632399
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Improve client startup times by configuring clients to use roaming profiles 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to configure the Microsoft Dynamics AX client for roaming user profiles in a Remote Desktop Services farm. A roaming user profile can improve client startup times.

## About roaming user profiles and Microsoft Dynamics AX

When a user logs onto a Windows-based computer, the system creates a directory with the user’s name or alias and stores data about that user’s session in the directory. This directory and the stored data are called a user profile. The first time a user logs onto a computer the system can take 30 seconds or more to create the user profile. If a user connects to computers or RemoteApp applications in a Windows Desktop Services farm, the system will create a new user profile for each server the user connects to in the farm unless the administrator configures roaming user profiles.

A roaming user profile is a copy of the local user profile that is stored on a server share. When a user logs onto a computer in the Remote Desktop Services farm, the system does not have to create a new profile. Instead, the system downloads the roaming profile from the share and uses it for the current session. Changes made to a roaming user profile are synchronized with the server copy when the user logs off.

When a user first opens the Microsoft Dynamics AX client, the system creates a .auc file and stores it in the user profile. The .auc file caches AOT information and user-specific details. When a user exits and restarts their Microsoft Dynamics AX client, the system reads the details in the .auc file and restores some aspects of the user’s session.

Users in a Remote Desktop Services farm can wait longer than 30 seconds if the system must create a new user profile *and* a new .auc file when a user first logs onto a server. If you configure the server farm for roaming user profiles, and then create a Microsoft Dynamics AX client configuration that has roaming user profiles enabled, users can experience much shorter wait times when they first connect to the server farm.


> [!IMPORTANT]
> <P>Administrators can configure Remote Desktop Services farms to clean out user profiles on logout. This configuration preserves disk space, but it can create slower startup times in environments with poor network infrastructure because the shared profile and all stored data for that profile must be sent across the network each time the user logs on. Before you configure roaming profiles, verify that your network infrastructure can quickly download the necessary amount of data (typically multiple megabytes) from a shared user profile. If the network cannot handle this traffic, users might experience better startup times if the system recreates the user profile during each logon.</P>



## Before you begin

Before you create a client configuration that enables roaming user profiles in Microsoft Dynamics AX, you must deploy a Remote Desktop Services farm and then configure roaming user profiles in the server farm. For more information, see [Deploy Roaming User Profiles](https://go.microsoft.com/fwlink/?linkid=328609) \[Windows Server 2012\] or [User Profiles on Windows Server 2008 R2 Remote Desktop Services](https://go.microsoft.com/fwlink/?linkid=328608).

## Create a roaming user profile client configuration

Use the following procedure to create a roaming user profile client configuration by using the Microsoft Dynamics AX client configuration utility.


> [!NOTE]
> <P>You can also start a Microsoft Dynamics AX client session with roaming user profiles enabled by using the Ax32.exe –roamingprofile command. For more information about this command, see <A href="client-configuration-commands.md">Client configuration commands</A>. For more information about how to execute commands, see <A href="execute-configuration-commands.md">Execute configuration commands</A>.</P>



1.  Open the configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  In the **Configuration target** list, select **Local client**.

3.  Click **Manage**, and then click **Create configuration**.

4.  In the **Create configuration** dialog box, in the **Name** box, type a name.

5.  You can copy settings from either the active configuration or the original configuration, which is the default configuration. Select the configuration that you want to copy settings from, and then click **OK**.
    

    > [!NOTE]
    > <P>You cannot delete or rename the original configuration. You can only rename or delete configurations that you create.</P>



6.  Click the **Connection** tab, and then click **Use roaming user profiles**.

7.  Save your changes and then deploy the new configuration as a new shared configuration file. For more information about how to deploy a shared configuration file, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md).

## See also

[Manage a client configuration](manage-a-client-configuration.md)

[Manage client startup settings](manage-client-startup-settings.md)

[Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md)

  


