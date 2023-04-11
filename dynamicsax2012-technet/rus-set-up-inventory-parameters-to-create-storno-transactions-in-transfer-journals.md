---
title: (RUS) Set up inventory parameters to create storno transactions in transfer journals
TOCTitle: (RUS) Set up inventory parameters to create storno transactions in transfer journals
ms:assetid: 7b8fc675-3c13-4608-b439-715603c6237f
ms:mtpsurl: https://technet.microsoft.com/library/JJ678388(v=AX.60)
ms:contentKeyID: 49387617
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up inventory parameters to create storno transactions in transfer journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the parameters in the **Inventory and warehouse management parameters** form to create storno transactions for the transfer journal.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **General** area, select the **Transfer journals and transfer orders** check box to enable financial posting for transfer journals and transfer orders.

3.  In the left pane, click **Journals**.

4.  In the **Journals** area, select the **Extended verification** check box to enable verification when you create inventory storno transactions. Verification helps guarantee that all inventory and financial dimensions of the storno transaction match the dimensions of the original transaction.
    

    > [!NOTE]
    > <P>If you do not select the <STRONG>Extended verification</STRONG> check box, you can post storno inventory transactions with dimensions that differ from the original transaction.</P>



## See also

[(RUS) Set up credit correction for transfer orders](rus-set-up-credit-correction-for-transfer-orders.md)

  


