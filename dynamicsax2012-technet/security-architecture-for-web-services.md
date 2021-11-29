---
title: Security architecture for Web services
TOCTitle: Security architecture for Web services
ms:assetid: 3f61be60-9665-4755-a4a6-be01ce62e439
ms:mtpsurl: https://technet.microsoft.com/library/Dd309651(v=AX.60)
ms:contentKeyID: 36941286
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Security architecture for Web services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Application Integration Framework (AIF) supports Web services for Windows Communication Foundation (WCF). In AIF, each document is represented by a service that can be exposed from an integration port. To consume services over the Internet, you must host services on Internet Information Services (IIS). AIF uses standard WCF processing to receive and process SOAP requests. For information about how to install Web services on IIS, see [Install web services on IIS](install-web-services-on-iis.md).

## Security architecture for Web services

Security in AIF is enforced through a combination of WCF, IIS, Active Directory, and role-based security in Microsoft Dynamics AX.

1.  The client calls a service method, such as the Customer.read method, and passes the entity key of the requested customer in a SOAP message.

2.  The request is received by the IIS where the AIF services are hosted. IIS retrieves the user credentials, depending on the authentication mechanism that is specified in the service configuration. IIS then tries to map the security credentials to a valid domain user. By default, Microsoft Dynamics AX configures WCF to use the basicHttpBinding binding and message security, so that the user credentials are contained in the message's SOAP header. IIS authenticates the user as a valid user in Active Directory.

3.  The request is passed to AIF, which performs additional authentication by verifying that the user meets the following criteria:
    
      - The user is a valid Microsoft Dynamics AX user.
    
      - The user has the appropriate permissions, through role-based security, to start the operation.

4.  After AIF determines that the user has access to the service, the message is processed. At run time, standard AIF security guarantees that the user has access to the data that is exposed by the service.

## See also

[Security best practices for services and AIF](security-best-practices-for-services-and-aif.md)

[Services and AIF security and protection](services-and-aif-security-and-protection.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

