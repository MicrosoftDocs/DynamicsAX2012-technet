---
title: Run multiple instances of Synch Service
TOCTitle: Run multiple instances of Synch Service
ms:assetid: 07c47aa8-3be8-4b63-b2d6-5d942b03a8be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679906(v=AX.60)
ms:contentKeyID: 49557889
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Run multiple instances of Synch Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can run multiple instances of Commerce Data Exchange: Synch Service in an environment. Use either an additional primary instance or a forwarder instance, based on the requirements of the business.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



## Run an additional primary instance of Synch Service

To help balance the load and to help improve the performance of Synch Service, you can install additional primary instances of Synch Service at the head office. For example, you can set up each instance to process transactions for a single store. The following diagram shows a configuration with two primary instances of Synch Service.

![Multiple instances of Synch Service at headquarter](images/JJ679906.RetailMultipleSynchService(en-us,AX.60).gif "Multiple instances of Synch Service at headquarter")

Use the following procedure to configure an additional primary instance of Synch Service.

1.  Install and configure the new instance of Synch Service as described in [Install Commerce Data Exchange: Synch Service (Retail Store Connect)](install-commerce-data-exchange-synch-service-retail-store-connect.md). When you configure the new instance, use a different port number, so that there is no conflict between instances.

2.  Create an Application Object Server (AOS) profile for each instance of Synch Service. For more information, see [Set up an AOS profile](set-up-an-aos-profile.md).

3.  Set up a separate distribution schedule for each AOS profile. For more information, see [Configure and schedule retail data distribution](configure-and-schedule-retail-data-distribution.md).

## Set up a forwarder instance of Synch Service

A second instance of Synch Service that operates in forwarder mode can be used to reduce the processing load on the primary Synch Service server. When your topology includes a forwarder, data packages are cached in the database and working directory. The forwarder then collects the cached data packages and transmits them to their destination. This setup does not tie up resources on the primary Synch Service instance. Therefore, you may want to use this setup if the network route to a destination store is slow, or if you want to multicast identical data packages to several stores. A forwarder instance is also known as Second Stage Synch Service.

To use Synch Service in forwarder mode, you must run two instances of Synch Service at the head office, one as the primary instance and the other as the secondary or forwarder instance. Set up the forwarder instance on a separate computer, and confirm that the message database where the incoming and outgoing message tables are stored can be accessed from that computer. Also confirm that the working folder can be accessed.

The forwarder instance handles communication in only one direction, from the head office to the store locations.

The following diagram shows a configuration with a forwarder instance of Synch Service.

![Forwarder configuration of Synch Service](images/JJ679906.RetailForwarderConfiguration(en-us,AX.60).gif "Forwarder configuration of Synch Service")

Use the following procedure to configure a forwarder instance.

1.  Install and configure the forwarder instance of Synch Service as described in [Install Commerce Data Exchange: Synch Service (Retail Store Connect)](install-commerce-data-exchange-synch-service-retail-store-connect.md). When you configure the new instance, use a different port number, so that there is no conflict between instances.

2.  Create a Synch Service profile for each instance. In the **Service name** field, enter a value in the following format:
    
    \<Forwarder service name\>;\<receiver service name\>
    
    Entering the value in this format ensures that the forwarder send packages to the specified receiver location.
    
    For more information about how to create a Synch Service profile, see [Set up a profile for Synch Service](set-up-a-profile-for-synch-service.md).

3.  Create database profiles for store databases. To indicate which forwarder handles a particular location, select the appropriate Synch Service profile in the **Database profiles** form. For more information about how to create a database profile, see [Set up a store database profile](set-up-a-store-database-profile.md).

4.  Confirm that the user that Synch Service is running as has read/write permissions to the working directory and its contents.

  


