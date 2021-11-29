---
title: Configure an AOS to access a different bin directory
TOCTitle: Configure an AOS to access a different bin directory
ms:assetid: 4abda78d-6241-4a3d-8cd4-3847ae68a2c3
ms:mtpsurl: https://technet.microsoft.com/library/Aa569619(v=AX.60)
ms:contentKeyID: 35949291
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure an AOS to access a different bin directory 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The text that is displayed in the user interface is contained in a kernel text data file, \*.ktd. By default, Microsoft Dynamics AX reads the text from the kernel text data file that is stored in the bin directory of the Application Object Server (AOS) directory. If you want Microsoft Dynamics AX to use a different kernel text data file, you can modify a copy of the kernel text data file, select a location, and point an AOS instance to the location.

1.  Open the server configuration utility. Click **Start** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Verify that the AOS instance and configuration that you want to modify are selected.

3.  On the **Application Object Server** tab, in the **Alternate bin directory** box, type the location of the bin directory that you want to point the AOS instance to, and then click **OK**.

## See also

[Manage an AOS configuration](manage-an-aos-configuration.md)

[Configure an AOS to access a different database](configure-an-aos-to-access-a-different-database.md)

  


