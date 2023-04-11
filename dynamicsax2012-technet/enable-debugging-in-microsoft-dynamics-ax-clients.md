---
title: Enable debugging in Microsoft Dynamics AX clients
TOCTitle: Enable debugging in Microsoft Dynamics AX clients
ms:assetid: bd7f8809-1a8e-4918-8bba-d8692caead90
ms:mtpsurl: https://technet.microsoft.com/library/Hh202098(v=AX.60)
ms:contentKeyID: 35949352
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Enable debugging in Microsoft Dynamics AX clients 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about how to enable breakpoints by using the Microsoft Dynamics AX 2012 Configuration utility. After you enable breakpoints, you can debug a Microsoft Dynamics AX client or an instance of .NET Business Connector.

## Debugging options

The Microsoft Dynamics AX 2012 Configuration utility includes the following options that enable breakpoints:

  - **Enable user breakpoints to debug code in the Business Connector** – X++ code that runs in .NET Business Connector can be interrupted by breakpoints. This option applies to individual sessions of .NET Business Connector.

  - **Enable global breakpoints to debug code running in the Business Connector or client** – X++ code that runs in .NET Business Connector or a client can be interrupted by global breakpoints. This option applies to all users. After this option is set, breakpoints appear in sessions that are currently active.

To debug .NET Business Connector, you must select both debug options. To debug a client, select only the second option.

## Enable breakpoints for an instance of .NET Business Connector

1.  Open the configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  On the **Developer** tab, select **Enable user breakpoints to debug code in the Business Connector**.

3.  Select **Enable global breakpoints to debug code running in the Business Connector or client**, and then click **OK**.

## Enable breakpoints for a client

1.  Open the configuration utility. Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.

2.  On the **Developer** tab, select **Enable global breakpoints to debug code running in the Business Connector or client**, and then click **OK**.

## See also

[Debugging in Microsoft Dynamics AX 2012](https://technet.microsoft.com/library/gg860898\(v=ax.60\))

[Edit code at a customer site](edit-code-at-a-customer-site.md)

[Manage development configuration settings](manage-development-configuration-settings.md)

[.NET Business Connector](net-business-connector.md)

  


