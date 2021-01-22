---
title: (BEL) About CIS
TOCTitle: (BEL) About CIS
ms:assetid: 192c025a-df87-49d8-af6d-b1c98847296d
ms:mtpsurl: https://technet.microsoft.com/library/Hh208448(v=AX.60)
ms:contentKeyID: 36056108
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- IBS
- Isabel
- CIS
audience: Application User
ms.search.region: Belgium
---

# (BEL) About CIS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Belgian companies exchange information with their banks electronically using Isabel 6. Isabel 6 allows you to transfer payment files to the bank and receive electronic bank statements in accordance with the Isabel electronic banking standards. Isabel 6 uses only known formats such as Isabel, Swift, Dom, SEPA, and CODA. For more information about Isabel 6, see [Isabel – Beyond Banking](http://www.isabel.be/) on the Isabel website.

Isabel Go module, as part of Isabel 6, allows you to send payments to the Isabel 6 portal directly from Microsoft Dynamics AX given that the application request originates from an Isabel Software Partner, and is Isabel certified.

## CIS

Isabel 6 supports two synchronization modes: Server Isabel Synchronizer (SIS), or Unattended Integration Mode; and Client Isabel Synchronizer (CIS), or Attended Integration Mode. CIS lets you to upload bank statement files from Microsoft Dynamics AX 2012 through Isabel 6 and download the bank statement files for processing in the **Bank statement** form. In Microsoft Dynamics AX 2012 CIS is handled through an extension of the existing electronic banking component.

Previously, companies logged on to the Isabel platform to upload payment files and download bank statements manually; however this can now be carried out from Microsoft Dynamics AX 2012. Isabel 6 must be installed and running on your local system before Microsoft Dynamics AX 2012 can communicate with the Isabel 6 Application Program Interface (API) to upload and download banking files using CIS. When downloading bank statements, Microsoft Dynamics AX 2012 can verify the files on the server and then download those on demand.

The rest of the flow, including syntax and semantic validations, signing, inviting signers, controllers, and releasers, is completely incorporated into the Isabel 6 platform. In order to upload or download using CIS, you must establish a link using your PIN code in Isabel 6. While uploading payment files, you can enter an email address to receive feedback on the status of transactions.

The CIS platform consists of a client component and a server-side broker that uses Isabel Office Sign (IOS) and the Single Sign-on (SSO) infrastructure. The CIS client component exposes a high-level exchange API allowing third-party applications or components to exchange data using the Isabel 6 platform. The CIS client component is deployed as a Dynamic Link Library (DLL) on your system, which integrates with IOS and the Isabel SSO infrastructure, allowing secure data exchange. The CIS broker is a server component that maps document exchange requests on the Isabel portal.

Each service that Isabel 6 provides using the CIS channel is described by an input XML document (request) and an output XML document (response). Schema element descriptions are available for each document type. The request document and attachments are passed by Microsoft Dynamics AX 2012 to the CIS client component, which then establishes a secure connection through the Isabel SSO infrastructure to the CIS broker. The CIS broker analyzes the request and maps it to the appropriate Isabel business service. The result of the service call is consolidated into a response XML document by the CIS broker and returned to the CIS client. The client component uses known file formats, such as CODA, to extract data from the response XML document for insertion into Microsoft Dynamics AX 2012.

  


