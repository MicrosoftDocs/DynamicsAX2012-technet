---
title: (MEX) Configure the digital certificate in Microsoft Windows Server 2008
TOCTitle: (MEX) Configure the digital certificate in Microsoft Windows Server 2008
ms:assetid: bd3fadf8-3543-49a9-8707-e180adba8c55
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242774(v=AX.60)
ms:contentKeyID: 36059149
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Configure
- (MEX)
- "2008"
- Microsoft windows server
- digital certificate
audience: Application User
ms.search.region: Mexico
---

# (MEX) Configure the digital certificate in Microsoft Windows Server 2008 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must configure and grant access to the digital certificate to sign the generated XML message for a batch of electronic invoices. To grant access to the digital certificate private key and configure the Windows Communication Foundation (WCF) client to use the certificate as an authentication, you must import the digital certificate to the computer where Application Object Server (AOS) is running.


> [!NOTE]
> <P>Before you begin the import process, convert the digital certificate provided by the Servicio de Administración Tributaria (SAT) to a Personal Information Exchange (.pfx) file, and then save the .pfx file to your computer. For information about how to convert the digital certificate private key, visit the DICTAMEX website.</P>



To grant an AOS user access to the digital certificate private key in the Windows Server® 2008 operating system, follow these steps:

1.  On the taskbar, click **Start** \> **Run**, and then type System 32.

2.  Double-click the **certmgr** file.

3.  Right-click the **Certificates** folder, and then click **All tasks** \> **Import** to open the Certificate Import Wizard.
    

    > [!NOTE]
    > <P>The Certificate Import Wizard is an .msc file.</P>



4.  Close the wizard.

## See also

[(MEX) Customize Microsoft Dynamics AX to include the XML addenda element for a customer](mex-customize-microsoft-dynamics-ax-to-include-the-xml-addenda-element-for-a-customer.md)

  


