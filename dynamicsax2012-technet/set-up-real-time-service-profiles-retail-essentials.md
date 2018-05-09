---
title: Set up Real-time Service profiles (Retail essentials)
TOCTitle: Set up Real-time Service profiles (Retail essentials)
ms:assetid: 7daad3c2-0d6c-418a-a9d8-f811def67a56
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736906(v=AX.60)
ms:contentKeyID: 62200383
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- 7daad3c2-0d6c-418a-a9d8-f811def67a56
- aa670ee6-0d24-4ff5-a8db-e841fd75163c
- MsDynAx060.7daad3c2-0d6c-418a-a9d8-f811def67a56
- MsDynAx060.aa670ee6-0d24-4ff5-a8db-e841fd75163c
---

# Set up Real-time Service profiles (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

By setting up a profile for Commerce Data Exchange: Real-time Service, you enable a store to retrieve or update real-time data from Retail essentials. Real-time Service acts as an agent for a store. The store never directly accesses the remote instance of Microsoft Dynamics AX Application Object Server (AOS).

This topic explains how to set up a Real-time Service profile.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up a Real-time Service profile

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Store integration** \> **Real-time Service profiles**.

2.  Select an existing profile, or press CTRL+N to create a new profile.

3.  Enter a name and a description for the profile.

4.  On the **Connection** FastTab, enter the following information:
    
      - **Server** – Enter the server name or IP address where Real-time Service is running.
    
      - **Port** – Enter the port number that the web service for Real-time Service uses.
        
        A port number is associated with each communication protocol that is bound to the website. By default, the port number for Net.TCP is 808, and the port number for HTTPS is 9081.
    
      - **Protocol** – Select the communication protocol that Real-time Service uses.
        
        By default, the protocol is Net.TCP, but HTTPS is also supported. To use HTTPS, you must modify the web.config file for the website.
    
      - **Web application name** – Enter the name of the web application that hosts Real-time Service.
    
      - **Common name** – Enter the common name for the certificate that is used to establish an encrypted channel with Real-time Service.
    
      - **Passphrase** – Enter the passphrase that is used to authenticate the connection.
    
      - **Language** – Select the language that is used for messages. You do not have to select the same language that AOS uses. However, you must select a language for which you have a Retail essentials license.
    
      - **Real-time Service version** – If the service has a different release version than Retail essentials, select the version of this instance of the service.

5.  On the **Settings** FastTab, select the **Commerce Data Exchange: Real-time Service staff** check box to enable the point-of-sale (POS) system to validate the operator logon through the service.

## Assign a Real-time Service profile to a store

To enable POS devices to retrieve or update information from Retail essentials in real time, you must assign a Real-time Service profile to each retail store.

For more information about how to set up a retail store, see [Set up a retail store (Retail essentials)](set-up-a-retail-store-retail-essentials.md).

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  Select the store to modify, and then, on the **Action Pane**, in the **Maintain** group, click **Maintain**.

3.  In the **Stores** form, on the **General** FastTab, in the **Real-time Service profile** field, select the appropriate Real-time Service profile.

4.  To synchronize profile settings with the channel database, run either the predefined 1070 job or the job that you have set up to synchronize store data.

## See also

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

[Setting up retail stores (Retail essentials)](setting-up-retail-stores-retail-essentials.md)

[Set up registers (Retail essentials)](set-up-registers-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

