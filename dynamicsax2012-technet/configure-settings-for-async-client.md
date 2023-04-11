---
title: Configure settings for Async Client
TOCTitle: Configure settings for Async Client
ms:assetid: 3356c7a4-6c49-4a4d-932d-1954dfe413d6
ms:mtpsurl: https://technet.microsoft.com/library/Dn741441(v=AX.60)
ms:contentKeyID: 62219717
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure settings for Async Client 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Async Client Configuration Tool can be used to configure an instance of Commerce Data Exchange: Async Client. This tool lets you test connections and specify whether to use streaming to transfer data. The configuration data is stored in the application configuration file.

The Async Client Configuration Tool is installed together with Async Client.


> [!NOTE]
> <P>You can configure the download and upload intervals for Async Client in Microsoft Dynamics AX. For more information, see <A href="set-up-a-profile-for-async-server.md">Set up a profile for Async Server</A>.</P>



## Test connections for Async Client

Use the Async Client Configuration Tool to test connections between Async Client and other components.

1.  Start the Async Client Configuration Tool. By default, the executable file is located at C:\\Program Files\\Microsoft Dynamics AX\\60\\CDX\\Async Client\\\<DatabaseName\>\_Package. Double-click the **AsyncClientConfigurationUtility.exe** file.

2.  Test connections to other components, as shown in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Async Client connection</p></th>
    <th><p>How to verify the connection</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Commerce Data Exchange: Async Server</p></td>
    <td><p>On the <strong>Async Server connection</strong> tab, in the <strong>Authentication information</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p>Channel message database</p></td>
    <td><p>On the <strong>Channel configuration</strong> tab, in the <strong>Channel message database</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Channel database</p></td>
    <td><p>On the <strong>Channel configuration</strong> tab, in the <strong>Channel database</strong> section, click <strong>Test connection</strong>.</p></td>
    </tr>
    </tbody>
    </table>


## Configure settings for Async Client

1.  Start the Async Client Configuration Tool. By default, the executable file is located at C:\\Program Files\\Microsoft Dynamics AX\\60\\CDX\\Async Client\\\<DatabaseName\>\_Package. Double-click the **AsyncClientConfigurationUtility.exe** file.

2.  On the **Async Server connection** tab, verify or modify the information.
    
    The **Async Server connection** section contains information about how Async Client communicates with Async Server. The following fields are available:
    
      - **Server name** – The name of the server that hosts Async Server.
    
      - **Application name** – The name of the web application for Async Server.
    
      - **Https port number** – The port number that Async Server uses for secure HTTP communication.
    
      - **NetTcp port number** – The port number that Async Server uses for Net.TCP communication. Specify a Net.TCP port if you select the **Use streaming** option.
        
        By default, Async Client uses the WS-ReliableMessaging protocol. Reliable messaging helps guarantee that the data is transferred successfully. However, the confirmation actions between the source and the destination can cause data transfers to be slower. For better throughput, you can use streaming instead. Streaming is ideal for initial high-speed data synchronization or for ongoing synchronization of large amounts of data. If you have a reliable network and high data volume, we recommend that you stream data.
    
    The **Authentication information** section contains the identifier for the channel database that Async Client connects to. This section also contains the credentials that are used to authenticate Async Client with Async Server. These values are specified in the **Channel database** form. For more information, see [Set up a channel database profile](set-up-a-channel-database-profile.md).
    
    Click **Test connection** to verify that the connection to Async Server is configured correctly.

3.  On the **Channel configuration** tab, verify or modify the information.
    
      - The **Channel message database** section specifies the server and database name for the channel message database. Click **Test connection** to verify that the connection to the channel message database is configured correctly.
    
      - The **Channel database** section specifies the server and database name for the channel database. Click **Test connection** to verify that the connection to the channel database is configured correctly.

  


