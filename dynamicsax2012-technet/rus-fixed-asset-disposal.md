---
title: (RUS) Fixed asset disposal
TOCTitle: (RUS) Fixed asset disposal
ms:assetid: 3b264589-94c1-409e-aa54-e41131a507ca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665298(v=AX.60)
ms:contentKeyID: 49387387
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Fixed asset disposal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can dispose of fixed assets for any of the following reasons:

  - An asset is sold to other legal entities or private individuals.

  - An asset is transferred and used as a deposit in joint activities or as a charter capital.

  - An asset is donated or used as another type of non-compensated transfer.

  - An asset is liquidated because of an accident or natural disaster.

  - An asset is exchanged through an exchange agreement.


> [!NOTE]
> <P>Depreciation must be calculated until the month of disposal.</P>



There are three ways to create a disposal transaction:

  - **Leaving (sale)** – This transaction represents a fixed asset sale and can be entered in Accounts receivable or in the fixed assets journal. Several transactions are created in the ledger, based on the posting profile configuration. The status of the asset changes to **Written off (sale)**.

  - **Leaving (dismantlement)** – This transaction is entered in the fixed assets journal. Transactions are created in the ledger, and the remaining value of the asset after it has been dismantled is transferred to the warehouse. The status of the asset changes to **Written off (dismantlement)**.

  - **Fixed Assets write-off** – This transaction is entered in the fixed assets journal, and the write-off transactions for the booked value and booked depreciation for the asset are created. The status of the asset changes to **Written off**


> [!NOTE]
> <P>When you create a transaction for the partial write-off or disposal of a fixed asset, if the transaction accrues a loss, the transaction details are posted to a deferral account. This account contains the values of the calculated loss and the write-off time. The write-off time is calculated by using the fixed asset depreciation factor and the difference between the useful life of the depreciated asset and the actual period that the asset is used before its disposal.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

