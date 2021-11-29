---
title: Retail Salt Utility
TOCTitle: Retail Salt Utility
ms:assetid: 6221bd2e-0dc1-4c10-80bb-be6f7f5ba1fb
ms:mtpsurl: https://technet.microsoft.com/library/Dn859553(v=AX.60)
ms:contentKeyID: 63817136
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Retail Salt Utility 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Retail Salt Utility can be used to hash user passwords, which provides additional security beyond standard encryption. Hashing passwords is a way of taking a variable-length password and creating a cryptic, fixed-length password from it. You do this by generating and using a salt value. A salt value is a random value that you use to generate a hashed password.

Retail Salt Utility is installed with the following components:

  - Commerce Data Exchange: Real-time Service

  - Microsoft Dynamics AX for Retail POS

  - Retail Server

## How to use the Retail Salt Utility

We recommend that you change the hash value each time you use the utility. The utility uses the text to create an additional randomized element for the encryption key.

1.  Start the Retail Salt Utility.

2.  Select the check boxes for the types of credentials that you want to provide additional security for. You can select Windows Live ID credentials, cashier passwords, or the Real-time Service passphrase.

3.  In the text boxes next to the credentials that you selected, type a string value that is between 10 and 50 characters long. Spaces and special characters are allowed.

4.  Click **Apply**.

  


