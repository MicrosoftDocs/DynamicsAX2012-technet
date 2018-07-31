---
title: Specify working folders for Commerce Data Exchange
TOCTitle: Specify working folders for Commerce Data Exchange
ms:assetid: 7287752d-5b02-4f95-9ff2-1fb8a3f9685d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621058(v=AX.60)
ms:contentKeyID: 62200205
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCDXFileStorageProvider
- MsDynAx060.Forms.RetailCDXFileStorageProvider
- 7287752d-5b02-4f95-9ff2-1fb8a3f9685d
- MsDynAx060.7287752d-5b02-4f95-9ff2-1fb8a3f9685d
---

# Specify working folders for Commerce Data Exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the **Working folders** form to set up the working folders for Commerce Data Exchange. Data packages are stored in the working folders during data upload and download.


> [!NOTE]
> <P>The information in this topic applies only if you are using Microsoft Dynamics AX 2012 R3.</P>



For more information about Commerce Data Exchange, see the [Commerce Data Exchange documentation](http://go.microsoft.com/fwlink/?linkid=391057) on TechNet.

1.  Create the shared folders where data packages will be stored. We recommend that you create a folder for data uploads and a folder for data downloads. The service accounts for AOS and Async Server must have permission to read and update these folders.

2.  Open the Microsoft Dynamics AX client. Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Working folders**.

3.  Click **New** to create a new set of working folders.

4.  Enter a name and description for the set of folders.

5.  Enter the path of the folder where data packages are stored for download to channels.

6.  Enter the path of the folder where data packages are stored for upload to Microsoft Dynamics AX.

7.  After you have created a set of working folders, you must associate it with a channel data group. For more information about data groups, see [Create a channel data group](create-a-channel-data-group.md).

  


