---
title: 'Commerce Data Exchange: Real-time Service'
TOCTitle: 'Commerce Data Exchange: Real-time Service'
ms:assetid: 7dc09b26-47ba-403e-9b69-a61601d46bae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679919(v=AX.60)
ms:contentKeyID: 49557901
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Data Exchange: Real-time Service 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Commerce Data Exchange: Real-time Service is an integrated service that provides real-time communication between Microsoft Dynamics AX and retail channels. Real-time Service enables individual point of sale (POS) computers and online stores to retrieve certain data from Microsoft Dynamics AX in real time.

Although most key operations can be performed in the local channel database, the following scenarios require direct access to the data that is stored in Microsoft Dynamics AX:

  - Issue and redeem gift cards

  - Redeem loyalty points

  - Issue and redeem credit memos

  - Create and update customer records

  - Create, update, and complete sales orders

  - Receive inventory against a purchase order or transfer order

  - Perform inventory counts

  - Retrieve sales transactions across stores and complete return transactions

The following diagram shows how data moves from Microsoft Dynamics AX through Real-time Service and then to the physical or online store.

![Flow of Real-time Service in R3](images/JJ679919.Retail_Real-timeService_R3(en-us,AX.60).gif "Flow of Real-time Service in R3")

In AX 2012 R3 and AX 2012 R2, Real-time Service is a Windows Communication Foundation (WCF) service that must be installed on a website in Internet Information Services (IIS).

In AX 2012 Feature Pack, Real-time Service is a Windows service that is called Retail Transaction Service.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

