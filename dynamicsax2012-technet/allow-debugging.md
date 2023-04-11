---
title: Allow debugging
TOCTitle: Allow debugging
ms:assetid: d25fadc8-e945-4814-abba-ec0c851aa547
ms:mtpsurl: https://technet.microsoft.com/library/Aa569630(v=AX.60)
ms:contentKeyID: 35949364
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Allow debugging 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to enable debugging on an instance of Microsoft Dynamics AX Application Object Server (AOS).

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the AOS instance and configuration that you want to modify are selected.

3.  On the **Application Object Server** tab, click **Enable breakpoints to debug X++ code running on this server**. When this option is enabled, clients can trace their interactions with the AOS instance.

4.  Click **Enable global breakpoints**. When this option is enabled, clients can debug X++ code that is invoked by using Query Services. For more information about this option, see [Microsoft Dynamics AX 2012 Server Configuration (form)](https://technet.microsoft.com/library/aa569635\(v=ax.60\)).

5.  Click **OK**.

## See also

[Debugging in Microsoft Dynamics AX 2012](https://technet.microsoft.com/library/gg860898\(v=ax.60\))

[Enable debugging in Microsoft Dynamics AX clients](enable-debugging-in-microsoft-dynamics-ax-clients.md)

  


