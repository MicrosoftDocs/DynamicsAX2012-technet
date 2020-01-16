---
title: (BRA) Generate the GIA ST tax file
TOCTitle: (BRA) Generate the GIA ST tax file
ms:assetid: a842ff4e-0806-4c22-b3ad-c238b25f9cfc
ms:mtpsurl: https://technet.microsoft.com/library/Dn600280(v=AX.60)
ms:contentKeyID: 62200244
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forms.FBBookingPeriodListPage_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Generate the GIA ST tax file 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to generate a Guia de Informação e Apuração Substituição Tributária (GIA ST) text file by using the **Booking period** list page.

The GIA ST text file contains information about all fiscal documents that have been received and issued each month for each fiscal establishment that has an IE registration for that state. This information is used by the tax authorities.

## Generate the GIA ST text file

To generate text files for GIA ST, follow these steps:

1.  **Booking period** On the **Action Pane**, click the **Tax statements** tab.

2.  Select a booking period, and then click **GIA ST**.

3.  Specify the location and name of the file. The default location is specified in the **GIA ST setup parameters** form, and the default file name is automatically generated. In most cases, you should accept the default entry.

4.  Select either **Normal** or **Substitute** for the GIA type.

5.  Select the layout version. The default entry is specified in the **GIA ST setup parameters** form.

6.  Select the state to generate the GIA ST text file for.

7.  Optional: Click the **Batch** tab and specify options for batch processing. You might use batch processing if the file should be generated later or on a server instead of on your computer.

8.  Click **OK**.

## See also

[(BRA) Set up parameters for GIA ST tax statements](bra-set-up-parameters-for-gia-st-tax-statements.md)

  


