---
title: Set up electronic signature parameters
TOCTitle: Set up electronic signature parameters
ms:assetid: 4a0275c4-e903-408e-a8b0-b3037ac9002f
ms:mtpsurl: https://technet.microsoft.com/library/Dd309665(v=AX.60)
ms:contentKeyID: 36056949
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- compliance
- e-signature
audience: Application User
ms.search.region: Global
---

# Set up electronic signature parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up general parameters for electronic signatures.

1.  Click **Organization administration** \> **Setup** \> **Electronic signature** \> **Electronic signature parameters**.

2.  Enter the notice that signers will receive when a signature is requested. You can enter any text. Typically, this text tells the user what it means to sign a document electronically.
    
    Click the **Translations** button to enter notice text in additional languages.

3.  If signers are required to include comments when they provide a signature, select **Require comments**.

4.  Enter a time limit in seconds. If a signature that is required is not provided in the time limit, the **Sign document** form will close, and the tried change will be canceled.

5.  In the **Signature alert recipient** field, select the person who will receive an email alert if the validation process fails for a signature.

## See also

[Choose processes that require electronic signatures](choose-processes-that-require-electronic-signatures.md)

[Set up users to sign documents electronically](set-up-users-to-sign-documents-electronically.md)

[Certificates for electronic signatures](certificates-for-electronic-signatures.md)

  


