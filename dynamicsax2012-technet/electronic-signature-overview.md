---
title: Electronic signature overview
TOCTitle: Electronic signature overview
ms:assetid: a25c7619-e8fc-4e23-8aa5-9836f3e55e91
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362020(v=AX.60)
ms:contentKeyID: 36058797
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- digital signature
- compliance
- e-signature
---

# Electronic signature overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of electronic signatures and describes how they can be used in Microsoft Dynamics AX.

## What is an electronic signature?

An electronic signature confirms the identity of a person who is about to start or approve a computing process. In some industries, an electronic signature is as legally binding as a handwritten one.

Electronic signatures are a regulations compliance requirement for several regulated industries, such as pharmaceuticals, food and beverage, and aerospace and defense. They are also necessary for compliance with regulations in 21 CFR Part 11 issued by the Food and Drug Administration (FDA) in the United States.


> [!NOTE]
> <P>An electronic signature by itself is not the same as a digital signature. An electronic signature is simply a substitute for a handwritten signature, while a digital signature provides additional security measures. A digital signature can help identify whether another user or process has tampered with the data. A digital signature can also be verified, and this verification cannot be refuted by the owner of the certificate that was used to sign the data. As described below, electronic signatures in Microsoft Dynamics AX have built-in digital signature functionality.</P>



## Electronic signatures in Microsoft Dynamics AX

In Microsoft Dynamics AX, you can use electronic signatures for critical business processes. Some processes have built-in electronic signature capabilities. You can also create custom signature requirements for any database table and field. For more information, see [Choose processes that require electronic signatures](choose-processes-that-require-electronic-signatures.md).

Electronic signatures in Microsoft Dynamics AX have built-in digital signature functionality. Each user who signs documents must obtain a valid cryptographic certificate. When a document is signed, the private key associated with that certificate is validated. (For more information, see [Certificates for electronic signatures](certificates-for-electronic-signatures.md).)

Microsoft Dynamics AX records electronic signature information in a log to provide an audit trail.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

