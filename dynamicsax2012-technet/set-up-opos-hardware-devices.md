---
title: Set up OPOS hardware devices
TOCTitle: Set up OPOS hardware devices
ms:assetid: dc8548b0-77d5-4926-9d58-d7dd6106ab71
ms:mtpsurl: https://technet.microsoft.com/library/JJ838775(v=AX.60)
ms:contentKeyID: 50120658
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up OPOS hardware devices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes how to set up OLE for Point of Sale (OPOS) hardware devices for Microsoft Dynamics AX for Retail POS.

For information about the devices that are supported by Retail POS, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377) for Microsoft Dynamics AX.

1.  Install OPOS Common Control Objects, version 1.13, on the computer where you plan to use the device.

2.  Install OPOS service objects from device manufacturers. Consider the following information when you install devices:
    
      - After you use an installation utility that was provided by a hardware manufacturer, we recommend that you confirm that the Common Control Objects have not been overwritten by an earlier version.
    
      - To help avoid performance issues, verify that you have the correct service objects for the hardware devices that are installed on the register.
    
      - Some service objects require that you install the Visual C++ 2008 Redistributable Package.

3.  Install the hardware.

4.  If a configuration utility is provided by the manufacturer, use the utility to configure the hardware.
    

    > [!IMPORTANT]
    > <P>You must use the same device name that you specify in the hardware profile for the register. For more information, see the <A href="https://go.microsoft.com/fwlink/?linkid=237283">Implementation Guide for PCI Compliance</A>.</P>



5.  If a test utility is provided by the manufacturer, use the utility to test the hardware.

6.  Associate the hardware with a hardware profile in Microsoft Dynamics AX. For more information, see [Set up hardware profiles](set-up-hardware-profiles.md).

  


