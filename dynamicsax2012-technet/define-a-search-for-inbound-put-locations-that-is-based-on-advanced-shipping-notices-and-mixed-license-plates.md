---
title: Define a search for inbound put locations that is based on advanced shipping notices and mixed license plates
TOCTitle: Define a search for inbound put locations that is based on advanced shipping notices and mixed license plates
ms:assetid: 3444f8fa-6ab8-4437-a4d1-a5d96a7b0972
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Mt740363(v=AX.60)
ms:contentKeyID: 73212214
ms.date: 07/15/2016
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define a search for inbound put locations that is based on advanced shipping notices and mixed license plates 


To help guarantee that all the content on a license plate is put into one location, and that the system does not suggest that you split the contents into several locations for “ASN – License plate receiving” and “Mixed license plate receiving” processes, you can use the **Locate by** field on the **Location directives** page for the **Purchase order** work order type.

1.  Click **Warehouse management** \> **Setup** \> **Location directives**

2.  Select or create a location directive for the **Purchase order** work order type and the **Put** work type.

3.  In the **Locate by** field, assign a value.
    

    > [!NOTE]
    > <P>The behavior of both the query and the line and location directive actions will vary, depending on the value that you select (<STRONG>ASN</STRONG>, <STRONG>Mixed license plate</STRONG>, or <STRONG>Purchase item</STRONG>). When you use the grouping concepts for <STRONG>ASN</STRONG> and <STRONG>Mixed license plate</STRONG>, the line restrictions will not be used.</P>


  


