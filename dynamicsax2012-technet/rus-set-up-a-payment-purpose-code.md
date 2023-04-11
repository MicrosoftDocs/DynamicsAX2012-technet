---
title: (RUS) Set up a payment purpose code
TOCTitle: (RUS) Set up a payment purpose code
ms:assetid: 91e69c90-f3d6-43d1-b179-52e6ad48df4a
ms:mtpsurl: https://technet.microsoft.com/library/JJ678480(v=AX.60)
ms:contentKeyID: 49387709
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a payment purpose code 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify the payment purpose code while generating a payment order. You can then use this code when generating a foreign currency payment transaction or a currency purchase transaction.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Payment purpose codes**.

2.  Press CTRL+N to create a new line.

3.  On the **Overview** tab, in the **Central Bank Purpose Code** field, enter the payment purpose code that is used when reporting to the bank.

4.  In the **Name** field, enter the name of the payment purpose code.

5.  On the **General** tab, in the **Currency op code** field, enter the currency operation code that corresponds to the given payment purpose code.
    

    > [!NOTE]
    > <P>The value entered in this field is used to generate a currency payment order and is displayed on the corresponding line in the report.</P>



6.  In the **Purpose text** field, enter a text description for the payment purpose.
    

    > [!NOTE]
    > <P>This will be the default value for the corresponding line when generating a payment order.</P>



7.  Press CTRL+S or close the form.

  


