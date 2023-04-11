---
title: Security best practices for services and AIF
TOCTitle: Security best practices for services and AIF
ms:assetid: ab145079-5dcd-43da-8f4a-5d27a54c0f7c
ms:mtpsurl: https://technet.microsoft.com/library/Aa834425(v=AX.60)
ms:contentKeyID: 36941317
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Security best practices for services and AIF 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

It is very important that you maintain data security when you use services and Application Integration Framework (AIF) to exchange data with other systems. Follow the security-related recommendations in this topic when you configure AIF. For more information about security and web services in AIF, see [Security architecture for Web services](security-architecture-for-web-services.md).

## Security best practices

  - When configuring your system to accept data by using the file system adapter, make sure that only trusted users authorized by the system administrator have the right to take ownership of the files containing inbound messages.
    
    For asynchronous requests that use the file system adapter, AIF uses the file owner as the submitting user to process the request. The service is executed in the context of the submitting user if a separate logon user is not specified on the **Inbound ports** form. Windows Server 2008 allows a user with sufficient user rights to change the owner of a file to some other user. The service request will then be executed as the other user.
    
    To prevent this elevation of privilege, you should not grant the user right of **Take ownership of files or other objects** and **Restore files and directories** to non-administrator users in your production environment.
    

    > [!NOTE]
    > <P>You can avoid any change in file ownership by using a Uniform Naming Convention (UNC) path to specify the location of the file adapter. Ownership of files cannot be changed if you use a UNC path.</P>

    
    For more information, see [Configure addresses for enhanced integration ports](configure-addresses-for-enhanced-integration-ports.md) and [Managing Object Ownership](https://go.microsoft.com/fwlink/?linkid=396920&clcid=0x40).

  - Make sure that data that is sent to and from AIF integration ports is encrypted and can be accessed only by authenticated and authorized users. All data transmissions must be secured, so that no one can read or modify the data during transmission. Authentication and encryption are especially important for business-to-business scenarios in which data is transmitted over the public Internet. For HTTP ports, you can add HTTPS settings through Internet Information Services (IIS).

  - When you transmit messages by using the file system adapter or the MSMQ adapter, make sure that the file shares and queues themselves are secured and can be accessed only by authorized users. You can help secure the file shares and queues by using specialized security software that encrypts data and guarantees that only authorized users can access a file location.

  - The Microsoft Dynamics AX system administrator must restrict access to AIF by assigning users only to the roles that those users require. See [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md).

  - Be aware that all actions in Microsoft Dynamics AX that involve inbound documents are performed in the context of a valid Microsoft Dynamics AX user. For information about how AIF determines the submitting user, see [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md).

  - Be sure to help secure the location on the file system to which you export messages from the **Queue manager** form. These messages may contain confidential information.

  - Restrict the use of integration ports to authorized users and companies. In this way, an integration port can send or receive data only for specific customers, vendors, or warehouses, and you can avoid spoofing attacks. Trusted intermediary users can submit AIF requests on behalf of authorized port users. See [Configure security for integration ports](configure-security-for-integration-ports.md).
    
    In Microsoft Dynamics AX 2012 R2, you must restrict an inbound port to a partition before you can restrict the port to a company. Each company in Microsoft Dynamics AX 2012 R2 exists in one data partition, although one data partition can contain more than one company. For more information about data partitions, see [Data partitioning architecture](data-partitioning-architecture.md).

  - To restrict the data fields that can be read or modified through an integration port, use data policies. For information about how to configure data policies, see [Customize service contracts](customize-service-contracts.md).

  - Add external components only from a trusted and reliable source, such as a Microsoft Partner or an independent software vendor (ISV). External components include document classes, adapter classes, and pipeline components. Pipeline components are X++ classes that are called during processing of the AIF pipeline.

  - Before you add an Extensible Stylesheet Language Transformation (XSLT) as part of pipeline processing, make sure that the XSLT is secured. Also make sure that the XSLT can handle documents that contain incorrect or malicious data. Thoroughly test any transformations to make sure that they do not contain code that can run and cause exploitable errors on the system.

  - By default, scripting is disabled on the component that is used for XSLT transforms, to help protect the system against scripting attacks. For information about how to enable scripting, see [Configure processing options](configure-processing-options.md).

## Security best practices for web services

Follow these additional security-related recommendations when you configure AIF web services:

  - By default, AIF web services implement the basicHttpBinding binding. This binding is configured to use the message-level security that is offered through Windows Communication Foundation (WCF). We recommend that administrators follow the standard WCF configuration in IIS. For more information about security in WCF, see [Securing Services](https://go.microsoft.com/fwlink/?linkid=102986).

  - Restrict access to the files for AIF web services. When AIF web services are installed, Setup creates a network share to the content directory where the files for AIF web services are located. We recommend that you restrict access to this network share.
    
    1.  Open the Computer Management application. Click **Start** \> **Administrative Tools** \> **Computer Management**.
    
    2.  Under **Local Users and Groups**, click the **Groups** folder.
    
    3.  Right-click the **Microsoft Dynamics AX Web Service Administrators** local group, and then select **Properties**.
    
    4.  In the **Members** field, verify that only accounts for Application Object Server (AOS) are members of the group.
    
    5.  If you are using the default permissions in Windows Server 2008, all domain users have Read and Execute permissions for the content directory where the web services are installed. For more information, see the [Default local groups](https://go.microsoft.com/fwlink/?linkid=227787) article on TechNet. If you are not using default permissions, you may have to grant access to the share by using one of the following methods:
        
          - Create a local Windows group that has access to the directory, and then add users of AIF web services to this group.
        
          - Add users of AIF web services to the local **Users** group of the computer.

  - All data that is exchanged with external web services must be exchanged over secure channels to prevent tampering, spoofing, and so on. Data is exchanged with external web services when, for example, an external web service is consumed from X++. We recommend that confidential and business-critical information be exchanged with external web services only through communication channels that provide secure authentication, message confidentiality, and integrity.

  - Never consume unknown or untrusted external web services. When you consume a web service, always make sure that the service that is consumed is the correct service. To verify the identity of web services that you consume, use a secure identification and authentication mechanism.

## See also

[Services and AIF security and protection](services-and-aif-security-and-protection.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

