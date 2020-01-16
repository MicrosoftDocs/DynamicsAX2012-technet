---
title: (BRA) Set up an electronic payment process for a complex file structure
TOCTitle: (BRA) Set up an electronic payment process for a complex file structure
ms:assetid: 19e803b1-7f74-4c42-8df8-268fb8ec7b87
ms:mtpsurl: https://technet.microsoft.com/library/JJ730965(v=AX.60)
ms:contentKeyID: 49675195
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- complex file structure
- Set up payment types
- Set up payment ways
- Set up segments
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up an electronic payment process for a complex file structure 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use a complex file structure to process an electronic payment remittance or return. The complex file structure consists of multiple headers and multiple trailer record types, such as file header, batch header, details, batch trailer, and file trailer. You can set up the payment types, payment ways, and segments for the complex file structure that is used when the legal entity makes an electronic payment to a bank.

## Set up payment types

Use this procedure to create codes for the different types of electronic payments that are used by your bank. The codes must be created based on the payment types that are specified by the bank that you work with. For more information, see [(BRA) Payment types (form)](https://technet.microsoft.com/library/jj730967\(v=ax.60\)).

1.  Click **Cash and bank management** \> **Setup** \> **Electronic payment** \> **Payment types**.

2.  Click **New** to create a payment type.

3.  In the **Payment type** field, enter a unique code for the type of payment. The code can be up to two alphanumeric characters long.

4.  In the **Description** field, enter a brief description for the payment type code.

## Set up payment ways

Use this procedure to create codes for the different ways your bank processes electronic payments. The codes must be created based on the payment ways that are specified by the bank that you work with. For more information, see the [(BRA) Payment ways (form)](https://technet.microsoft.com/library/jj730972\(v=ax.60\)).

1.  Click **Cash and bank management** \> **Setup** \> **Electronic payment** \> **Payment ways**.

2.  Click **New** to create a payment way.

3.  In the **Payment way** field, enter a unique code for the way the bank processes a payment. The code can be up to two alphanumeric characters long.

4.  In the **Description** field, enter a description for the payment way code.

## Set up segments

Use this procedure to create segments that a bank uses to generate the electronic payment files. The segments must be created based on the segments that are specified by the bank that you work with. A segment determines what information is required by bank to perform a payment. You must create a layout group in the **Configurator layout groups** form before you can use the segments. For more information, see [(BRA) Segments (form)](https://technet.microsoft.com/library/jj730973\(v=ax.60\)).

1.  Click **Cash and bank management** \> **Setup** \> **Electronic payment** \> **Segments**.

2.  Click **New** to create a segment.

3.  In the **Segment** field, enter a unique code for the segment. The code can contain only one alphabetic character.

4.  In the **Description** field, enter a description for the segment code.

5.  In the **Next segment** field, enter a unique code for the segment that is next in the sequence. The code can be up to two alphanumeric characters long.

6.  Select the **Mandatory** check box to indicate that the segment that is specified in the **Next segment** field is required to generate the electronic payment file.

## See also

[(BRA) Set up the configurator definition group](bra-set-up-the-configurator-definition-group.md)

[(BRA) Set up an electronic method of payment](bra-set-up-an-electronic-method-of-payment.md)

[(BRA) Set up an electronic payment](bra-set-up-an-electronic-payment.md)

  


