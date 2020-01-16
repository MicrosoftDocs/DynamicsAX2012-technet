---
title: Configure clients to access data in a partition
TOCTitle: Configure clients to access data in a partition
ms:assetid: 084c6e0f-d9e5-4b2c-872f-8e2b2c3867bb
ms:mtpsurl: https://technet.microsoft.com/library/JJ670112(v=AX.60)
ms:contentKeyID: 49478230
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure clients to access data in a partition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 enables data isolation by using data partitions. Data partitions provide a logical separation of data in the Microsoft Dynamics AX database. Partitions are defined in the **Partitions** form, where the system administrator creates the partition and provides a partition key. A partition key identifies a partition by using a unique string value that the system administrator specifies. Microsoft Dynamics AX displays the partition key in the title bar of the client application. For more information about partitions, see [Data partitioning architecture](data-partitioning-architecture.md).

This topic describes two ways to configure Microsoft Dynamics AX clients to access data in a specific partition.

## Before you begin

Before you configure clients to access data in a partition, verify the following.

1.  You are an administrator in Microsoft Dynamics AX.

2.  You are an administrator on the local client computer where you will create a configuration by using the Microsoft Dynamics AX 2012 Configuration utility. This requirement is only necessary if you use the configuration file procedure later in this section.

3.  You have the partition key(s) from the **System administration** \> **Setup** \> **Partitions** form.

4.  All users who require access to a designated partition are listed on the **Users** form for that partition.

## Configure clients to access data in a partition by using a configuration file

This procedure describes how to configure clients to access data in a partition by using a Microsoft Dynamics AX client configuration file. If your business or organization has only one partition, you can create a partition-specific configuration and then deploy the configuration by using a shared-configuration file. For more information, see [Configure clients to use a shared configuration](configure-clients-to-use-a-shared-configuration.md). If your business or organization has multiple partitions, you can create multiple client configurations and then deploy those configurations by using the system tools available for mass-client deployments. For more information, see [Mass deployment of the Microsoft Dynamics AX Windows client](mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md). For multiple partitions, you can also configure clients to access data in a partition by creating multiple client shortcuts as described in the next procedure in this topic.

1.  Open the configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  In the **Configuration target** list, select **Local client**.

3.  Click **Manage**, and then click **Create configuration**.

4.  In the **Create configuration** dialog box, in the **Name** box, type a name.

5.  You can copy settings from either the active configuration or the original configuration, which is the default configuration. Select the configuration that you want to copy settings from, and then click **OK**.

6.  On the **General** tab, enter a partition key in the **Partition** field. Click **OK** to save your changes or save your changes to a file for shared-configuration client deployments.

7.  Open the Microsoft Dynamics AX client and verify that you see the partition key in the title bar.

## Configure clients to access data in a partition by using a Windows shortcut

You can also configure clients to access data in a specific partition by adding the –partition= *key* argument to the Microsoft Dynamics AX client shortcut.

1.  On a computer where the Microsoft Dynamics AX client is installed, click **Start** \> **All Programs**, and then right-click the **Microsoft Dynamics AX 2012** shortcut.

2.  Click **Properties**.

3.  In the **Target** field, add the –partition= *key* argument to the end of the path.
    
    For example: "C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Client\\Bin\\Ax32.exe" -partition=test

4.  Click **OK**, and then double-click the shortcut to verify that the client opens in the specified partition.

5.  Repeat this procedure to create shortcuts to different partitions.

  


