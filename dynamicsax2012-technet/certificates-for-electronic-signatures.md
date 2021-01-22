---
title: Certificates for electronic signatures
TOCTitle: Certificates for electronic signatures
ms:assetid: dcad68bf-4019-4c6e-ad22-380651c55f2f
ms:mtpsurl: https://technet.microsoft.com/library/Dd362096(v=AX.60)
ms:contentKeyID: 36059675
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- compliance
- e-signatures
audience: Application User
ms.search.region: Global
---

# Certificates for electronic signatures 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you sign documents electronically in Microsoft Dynamics AX, you must request a certificate.


> [!NOTE]
> <P>Microsoft Dynamics AX uses Microsoft SQL Server features to create certificates and enable electronic signing. No additional certificate or public-key infrastructure is required.</P>



When you request a certificate, a public key and a private key are created for you in the Microsoft Dynamics AX database. The private key is encrypted by using a password that is known only to you. When you sign a document electronically, your identity is verified when you enter the password.

## Get a certificate

1.  Click **File** \> **Tools** \> **Options...**.

2.  Click the **Miscellaneous** FastTab.

3.  Click **Electronic signature** \> **Get certificate**.

4.  Enter and confirm the password that you will use for signing. The password is used to protect your private key and authorize the use of your certificate.
    
    This password is not stored in the database and is not available to anyone else. This includes the Microsoft Dynamics AX administrator.

5.  Click **OK** to save the password, and then close the **Options** form.
    

    > [!NOTE]
    > <P>If your password does not meet Windows policy requirements, you must repeat steps 3 through 5 and provide a stronger password.</P>



## Reset your certificate

If you forget the password that is connected to your certificate, that certificate must be reset. Resetting the certificate does not affect documents that you signed with the previous certificate.

1.  Click **File** \> **Tools** \> **Options...**.

2.  Click the **Miscellaneous** FastTab.

3.  Click **Electronic signature** \> **Reset certificate**. When you select this option, your certificate is revoked.

4.  To get a new certificate, click **Electronic signature** \> **Get certificate**.

5.  Enter and confirm the password that you will use for signing. The password is used to protect your private key and authorize the use of your certificate.
    
    This password is not stored in the database and is not available to anyone else. This includes the Microsoft Dynamics AX administrator.

6.  Click **OK** to save the password, and then close the **Options** form.
    

    > [!NOTE]
    > <P>If your password does not meet Windows policy requirements, you must repeat steps 4 through 6 and provide a stronger password.</P>


  


