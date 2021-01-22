---
title: About the Delete close-of-year transactions during transfer check box
TOCTitle: About the Delete close-of-year transactions during transfer check box
ms:assetid: b66364a9-053b-4cdd-b111-86a199191d82
ms:mtpsurl: https://technet.microsoft.com/library/Gg232433(v=AX.60)
ms:contentKeyID: 36059092
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About the Delete close-of-year transactions during transfer check box 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If the **Delete close-of-year transactions during transfer** check box is selected in the **General ledger parameters** form, opening transactions and system-generated closing transactions that exist for the year to be closed are deleted when the transfer is processed again in the **Opening transactions** form.

After you post the final closing adjustments, you can use the **Opening transactions** form to generate new opening balances that contain the sum of the original opening balances. Several opening transactions now can exist on a single account:

  - One opening transaction regarding the time of the transfer.

  - Several opening transactions regarding closing adjustments and corrections, depending of the number of times closing transactions are created.

Every time that you update opening balances for the new fiscal year in the **Opening transactions** form, the previously generated opening transactions and closing transactions are deleted.

  


