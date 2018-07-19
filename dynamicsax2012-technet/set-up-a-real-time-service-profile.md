---
title: Set up a Real-time Service profile
TOCTitle: Set up a Real-time Service profile
ms:assetid: 4abdd0b8-813d-4216-8bae-0b66de66e5d3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580631(v=AX.60)
ms:contentKeyID: 39519122
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a Real-time Service profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

By setting up a profile for Commerce Data Exchange: Real-time Service, you enable a point of sale (POS) device or a store to retrieve or update real-time data from Microsoft Dynamics AX.

Real-time Service acts as an agent for a device or a store. The POS device and the store never access the remote AOS instance itself.

In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack, Real-time Service is also used by Commerce Data Exchange: Synch Service to upload status messages to Microsoft Dynamics AX.

The following information is included in this topic:

  - Set up a Real-time Service profile

  - Assign a Real-time Service profile to a retail store (AX 2012 R3)

  - Assign a Real-time Service profile to an online store

  - Assign a Real-time Service profile to a register (AX 2012 R2 and AX 2012 Feature Pack)

## Set up a Real-time Service profile

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Real-time Service profiles**.

2.  Select an existing profile, or press CTRL+N to create a new profile.

3.  Enter a name and a description for the profile.

4.  On the **Connection** FastTab, enter the following information:
    
      - **Server** – Enter the server name or IP address where Real-time Service is running.
    
      - **Port** – Enter the port number that the web service for Real-time Service uses.
        
        A port number is associated with each communication protocol that is bound to the web site. By default, the port number for the net.tcp protocol is 808 and the port number for the https protocol is 9081.
    
      - **Protocol** – Select the communication protocol that Real-time Service uses.
        
        By default, the protocol is net.tcp, but the https protocol is also supported. To use the https protocol, you must modify the web.config file for the web site.
    
      - **Web application name** – Enter the name of the web application that hosts Real-time Service.
    
      - **Common name** – Enter the common name for the certificate that is used to establish an encrypted channel with Real-time Service.
        
        To find the common name, right-click the server certificate in IIS Manager and choose **View**. The common name for the certificate is displayed on the **Details** tab, in the **Subject** field. This is usually the name of the domain for which the certificate was issued. If you’re using a self-signed certificate, the common name is usually the name of the computer for which the certificate was issued.
    
      - **Passphrase** – Enter the passphrase that is used to authenticate the connection.
    
      - **Language** – Select the language that will be used for error messages. You do not have to select the same language as the AOS uses. However, you must select a language for which you have a Microsoft Dynamics AX license.
    
      - **Real-time Service version** – If the service has a different release version than Microsoft Dynamics AX, select the version of this instance of the service.

5.  On the **Settings** FastTab, select the **Commerce Data Exchange: Real-time Service staff** check box to enable the POS system to validate the operator logon through the service.

## Assign a Real-time Service profile to a retail store (AX 2012 R3)

So that point of sale devices can retrieve or update information from Microsoft Dynamics AX in real time, you must assign each retail store a Real-time Service profile.


> [!NOTE]
> <P>The following procedure applies only to AX 2012 R3.</P>



For more information about how to set up a retail store, see [Set up a retail store](set-up-a-retail-store.md).

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  Double-click the store to modify, and then click the **Maintain** button.

3.  In the **Stores** form, click the **General** FastTab.

4.  Under **Profiles**, in the **Real-time Service profile** field, select the appropriate Real-time Service profile.

5.  To synchronize profile settings with the channel database, run the predefined 1070 job, or run the job that you have set up to synchronize store data.

## Assign a Real-time Service profile to an online store

So that online stores can retrieve or update information from Microsoft Dynamics AX in real time, you must assign each online store a Real-time Service profile.

For more information about how to set up an online store, see [Set up an online store](set-up-an-online-store.md).

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**.

2.  Double-click the online store to modify, and then click the **Maintain** button.

3.  In the **Online store** form, click the **General** FastTab.

4.  Under **Profiles**, in the **Real-time Service profile** field, select the appropriate Real-time Service profile.

5.  To synchronize profile settings with the channel database in Microsoft Dynamics AX 2012 R3, run the predefined 1070 job, or run the job that you have set up to synchronize online channel data.
    
    To synchronize profile settings with the channel database in Microsoft Dynamics AX 2012 R2, run the predefined A-1075\_OC job, or run the job that you have set up to synchronize online channel data.

## Assign a Real-time Service profile to a register (AX 2012 R2 and AX 2012 Feature Pack)

So that POS registers can retrieve or update information from Microsoft Dynamics AX in real time, you must assign each POS register a Real-time Service profile.


> [!NOTE]
> <P>The following procedure applies only to AX 2012 R2 and AX 2012 Feature Pack.</P>



For more information about how to set up a POS register, see [Set up registers](set-up-registers.md).

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  Double-click the register to modify, and then click the **Maintain** button.

3.  In the **POS registers** form, click the **General** FastTab.

4.  Under **Profiles**, in the **Real-time Service profile** field, select the appropriate Real-time Service profile.

5.  To synchronize profile settings with the channel database, run the predefined A-1090 job, or run the job that you have set up to synchronize register data.

## See also

[Commerce Data Exchange: Real-time Service profile (form)](https://technet.microsoft.com/en-us/library/hh597331\(v=ax.60\))

[About setting up Retail POS](about-setting-up-retail-pos.md)

[About online stores](about-online-stores.md)

[Setting up retail stores](setting-up-retail-stores.md)

[Online store (form)](https://technet.microsoft.com/en-us/library/jj713630\(v=ax.60\))

[POS registers (form)](https://technet.microsoft.com/en-us/library/hh597141\(v=ax.60\))

  


