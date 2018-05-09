---
title: (BEL) Set up Microsoft Dynamics AX to integrate with the Isabel electronic banking software
TOCTitle: (BEL) Set up Microsoft Dynamics AX to integrate with the Isabel electronic banking software
ms:assetid: 91e839bb-4317-4ce3-bf41-7726d1e74890
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232175(v=AX.60)
ms:contentKeyID: 36058566
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BEL) Set up Microsoft Dynamics AX to integrate with the Isabel electronic banking software 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up Microsoft Dynamics AX to integrate with the Isabel electronic banking software so that you can automatically upload payment files and download bank statement files.

## Installation requirements

Before you can set up the integration, you must install the Isabel electronic banking software on each computer that is used to download or upload payment files. Microsoft Dynamics AX must also be installed on each of these computers so that the two applications can integrate.

Make sure to install the Isabel electronic banking software in the following location on each computer:

C:\\Program Files\\Isabel services

For more information, see the installation instructions for the version of the Isabel electronic banking software that you are using.

## Set up parameters

You must set up certain parameters before Microsoft Dynamics AX can integrate with the Isabel electronic banking software.


> [!NOTE]
> <P>If you will be uploading payment files or downloading bank statement files, you must also create folders where these files will be stored. These folders must be available to all users who will be uploading or downloading files. This folder must also contain a subfolder named Archive, where archived payment transactions can be stored.</P>



1.  Click **Cash and bank management** \> **Setup** \> **IBS parameters**.

2.  In the **Version** field, enter the version of the Isabel electronic banking software that you use.

3.  In the **Upload folder** field, enter or select the path to the folder where the Isabel electronic banking software uploads must be saved.

4.  In the **Upload mode** field, select a mode from the following options:
    
      - **Attended mode** – The upload integration mode for the Isabel electronic banking software is active.
    
      - **None** – The upload integration mode for the Isabel electronic banking software is not active.

5.  In the **Download folder** field, enter or select the path to the folder where the Isabel electronic banking software downloads must be saved.

6.  In the **Download mode** field, select a mode from the following options:
    
      - **Attended mode** – The download integration mode for the Isabel electronic banking software is active.
    
      - **None** – The download integration mode for the Isabel electronic banking software is not active.

7.  Click the **Number sequences** tab, and then select the number sequences to use for the file IDs and request IDs that are associated with the Isabel electronic banking software. For more information, see [Number sequences (list page)](https://technet.microsoft.com/en-us/library/aa600321\(v=ax.60\)).

8.  Close the form.

## See also

[(BEL) IBS parameters (form)](https://technet.microsoft.com/en-us/library/hh209077\(v=ax.60\))

[(BEL) IBS transactions (form)](https://technet.microsoft.com/en-us/library/hh227606\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

