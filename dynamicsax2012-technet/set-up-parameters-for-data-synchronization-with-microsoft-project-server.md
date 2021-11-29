---
title: Set up parameters for data synchronization with Microsoft Project Server
TOCTitle: Set up parameters for data synchronization with Microsoft Project Server
ms:assetid: 3f2ed315-9ec3-4b62-8496-390275a45dbe
ms:mtpsurl: https://technet.microsoft.com/library/Hh242251(v=AX.60)
ms:contentKeyID: 36056700
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up parameters for data synchronization with Microsoft Project Server 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The parameters that you set in the **Synchronization service parameters** form determine how data is synchronized between Microsoft Project Server and Microsoft Dynamics AX.

1.  Click **System administration** \> **Setup** \> **Microsoft Project Server integration** \> **Synchronization service parameters**.

2.  In the **MSMQ server name** field, enter the name of the server where you installed the Microsoft Message Queuing (MSMQ) queues when the Synchronization Service Role was installed during the Microsoft Dynamics AX setup process.

3.  In the **Sync queue name** field, enter the name of the synchronization queue. By default, this field is populated with the name that was used when the Synchronization Service Role was installed during the Microsoft Dynamics AX setup process.

4.  In the **Number of elapsed hours to resynchronize** field, enter the number of hours that should pass before the synchronization queue automatically resets when an entity does not synchronize between Microsoft Dynamics AX and Project Server.

5.  In the **Number of elapsed hours before notification** field, enter the number of hours that should pass before you receive notification that synchronization between Microsoft Dynamics AX and Project Server was not successful.

6.  In the **Maximum number of synchronization attempts** field, enter the maximum number of times that you want the synchronization queue to try to synchronize Microsoft Dynamics AX with Project Server when synchronization is not successful.


> [!NOTE]
> <P>The <STRONG>Synchronization service user</STRONG> field reports the name of the synchronization service queue user. This field is populated from the service accounts that were created in the Microsoft Dynamics AX checklist.</P>



## See also

[Synchronization service parameters (form)](https://technet.microsoft.com/library/hh209631\(v=ax.60\))

[Configuring Microsoft Project Server integration](configuring-microsoft-project-server-integration.md)

[About Microsoft Dynamics AX integration with Microsoft Project Server](about-microsoft-dynamics-ax-integration-with-microsoft-project-server.md)

[Microsoft Project Server integration settings (form)](https://technet.microsoft.com/library/hh242729\(v=ax.60\))

[Microsoft Project Server integration global settings (form)](https://technet.microsoft.com/library/hh209389\(v=ax.60\))

  


