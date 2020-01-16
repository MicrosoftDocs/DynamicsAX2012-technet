---
title: Retail Modern POS architecture
TOCTitle: Retail Modern POS architecture
ms:assetid: cb89a6b8-0c34-46d7-88dc-ce6c87898060
ms:mtpsurl: https://technet.microsoft.com/library/Dn741454(v=AX.60)
ms:contentKeyID: 62219731
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Retail Modern POS architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The topic describes the architecture of Microsoft Dynamics AX Retail Modern point of sale (POS).


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>



## Retail Modern POS topology

On supported laptops, tablets, and phones, Retail Modern POS users can perform a variety of retail tasks. These include processing sales transactions, viewing customer orders, managing daily operations and inventory, or viewing role-based reports. The Microsoft Dynamics AX Retail Modern POS device is a client. It does not perform business functions or data processing. All business functions are provided by Microsoft Dynamics AX Retail Server. Retail Modern POS clients can communicate with Retail Servers that are deployed in your store or in a data center. Retail Modern POS clients can also communicate with peripheral devices such as cash drawers, credit card readers, and printers by using Microsoft Dynamics AX Hardware Station. Hardware Station must be deployed in your store and all Retail Modern POS clients can connect to the same Hardware Station.

Figure 1: Retail Modern POS high-level topology

![Topology of Modern POS](images/Dn741454.ModernPOS(en-us,AX.60).gif "Topology of Modern POS")

As of AX 2012 R3 CU8, Retail Modern POS can either connect to a channel database directly, or through Retail Server.

Figure 2: Retail Modern POS connected to a channel database

![Retail Modern POS with direct database connection](images/JJ991928.RetailModernDirect(en-us,AX.60).png "Retail Modern POS with direct database connection")

Figure 3: Retail Modern POS connected to a Retail Server

![Retail Modern POS with Retail Server](images/JJ991928.RetailModernPOSRetailServer(en-us,AX.60).png "Retail Modern POS with Retail Server")

## Retail Modern POS architecture

The view, view-controller, and devices layers depend on the operating system (for example, Windows Surface) on which you plan to deploy Retail Modern POS. The other layers are operating system independent and use TypeScript classes and modules to perform Retail Modern POS functionality such as workflows and entities.

Figure 4: Retail Modern POS technical architecture diagram

![The Retail Modern POS techincal architecture](images/Dn741454.ModernPOS2(en-us,AX.60).gif "The Retail Modern POS techincal architecture")

## Retail Modern POS offline architecture

Figure 5 describes the architecture of Retail Modern POS offline.

![Retail Modern POS Offline Architecture](images/Dn741454.RetailOfflineArchitecture(en-us,AX.60).png "Retail Modern POS Offline Architecture")

## See also

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

[Microsoft Dynamics AX Retail Server](microsoft-dynamics-ax-retail-server.md)

[Microsoft Dynamics AX Retail Hardware Station](microsoft-dynamics-ax-retail-hardware-station.md)

  


