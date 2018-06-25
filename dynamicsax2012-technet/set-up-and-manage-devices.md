---
title: Set up and manage devices
TOCTitle: Set up and manage devices
ms:assetid: 4b09662f-414a-489f-92d2-b936bab88260
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn793607(v=AX.60)
ms:contentKeyID: 62629942
ms.date: 07/25/2014
mtps_version: v=AX.60
---

# Set up and manage devices [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up and manage devices, such as Windows computers and Windows tablets, in Microsoft Dynamics AX so they can be used with Retail POS or Modern POS. You can create, deactivate, and disable devices in Microsoft Dynamics AX. You can also activate a device from the device itself.

Windows computers can use Retail POS or Modern POS. Windows tablets can use Modern POS.

## Create a device in Microsoft Dynamics AX

1.  Click **Retail** \> **Setup** \> **Devices**.

2.  In the **Devices** form, click **New** to create a new device.

3.  In the **Device ID** field, enter a unique identifier for the device.

4.  In the **Application** field, select the type of point-of-sale program that the device uses.

5.  In the **Description** field, enter a brief description of the device.

6.  In the **Register number** field, select a POS register to assign to the device.

7.  In the **Activation status** field, select **Pending**.

8.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

9.  In the **Name** column, select **1090** (**Registers**), and then click **Run now**. Information about the new device is sent to the stores.

## Activate a device from the device

1.  Start Retail POS or Modern POS on the computer or tablet.

2.  In the **Device activation** form, enter the following information:
    
      - In the **Service URL** field, enter the URL of the computer where Retail Server is installed. The format of the service URL is https://host:port/path/v1. For example, https://machinename:35080/retailserver/v1.
    
      - In the **Device number** field, enter the device ID, which is the unique identifier for the device that you entered in step 3 of the previous procedure.
    
      - In the **Register number** field, enter the register number, which is the register number that you entered in step 6 of the previous procedure.
    
      - In the **Operator ID** field, enter your operator ID.
    
      - In the **Password** field, enter your password.

3.  Click **Activate**.

## Deactivate or disable a device in Microsoft Dynamics AX

1.  Click **Retail** \> **Setup** \> **Devices**.

2.  In the **Devices** form, select a device, and then, in the **Activation status** field, do one of the following:
    
      - Select **Deactivated** to deactivate the device. Retail POS or Modern POS can be started, but no operations can be performed until it is activated.
    
      - Select **Disabled** to disable the device. Retail POS or Modern POS cannot be started or activated.


> [!NOTE]
> <P>You can also deactivate a device from the device itself.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

