---
title: Set up a profile for Synch Service
TOCTitle: Set up a profile for Synch Service
ms:assetid: 2ac188f0-d94c-4852-aea3-27e89eddce63
ms:mtpsurl: https://technet.microsoft.com/library/JJ677387(v=AX.60)
ms:contentKeyID: 49384167
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up a profile for Synch Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A profile for Commerce Data Exchange: Synch Service provides the connection string that enables Microsoft Dynamics AX to communicate with a particular instance of Synch Service.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



Synch Service periodically shares data among Retail components. These components include the head office, stores, and individual point of sale (POS) registers. Instances of Synch Service run at each site.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Commerce Data Exchange: Synch Service profiles**.

2.  Press CTRL+N to create a new Synch Service profile.

3.  Complete the following information:
    
      - **Service name** – Enter the name of the service as it was specified in the Synch Service Settings at **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Commerce Data Exchange: Synch Service** \> **Synch Service Settings**.
    
      - **Server name** – Enter the name of the server where Synch Service is installed.
    
      - **Port** – Enter the port that is used by this instance of Synch Service. By default, Synch Service uses port 16750.
    
      - **Disable IPSec** – Select this check box to disable Internet Protocol security (IPsec). IPsec is a framework of open standards that helps protect communications over Internet Protocol (IP) networks by using cryptographic security services.
        

        > [!IMPORTANT]
        > <P>You should disable IPsec only if you have another way to help provide secure communication channels for Synch Service. For more information, see <A href="configure-or-bypass-ipsec-for-synch-service.md">Configure or bypass IPsec for Synch Service</A>.</P>

    
      - **Prefer IPv6** – If IPv4 and IPv6 protocols are available, use IPv6.
    
      - **Timeout (seconds):** – Type the time in seconds. If you enter 0 (zero), jobs do not time out.
    
      - **Commerce Data Exchange: Real-time Service profile** – The name of a Commerce Data Exchange: Real-time Service profile. Real-time Service facilitates the upload of status messages for Synch Service from the store to the head office. If you want to upload status messages, you must associate a Real-time Service profile with the Synch Service profile. If you do not want this instance of Synch Service to monitor status, leave this field blank.
    
      - **Commerce Data Exchange: Synch Service upload options** – Select an upload configuration to use with Synch Service. If you select an upload configuration, click **Send configuration** to post the configuration to Synch Service and restart the service.

4.  Click **Test connection** to confirm that the connection string for the selected profile is correct. For information about how to resolve connection errors, see [Troubleshoot a connection](troubleshoot-a-connection.md).

  


