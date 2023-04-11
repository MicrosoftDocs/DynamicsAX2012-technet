---
title: (BRA) Cancel an NF-e that is generated from a tax fiscal document
TOCTitle: (BRA) Cancel an NF-e that is generated from a tax fiscal document
ms:assetid: 8ca59579-b443-4e9b-a7a0-4d4f420aeed6
ms:mtpsurl: https://technet.microsoft.com/library/JJ933524(v=AX.60)
ms:contentKeyID: 50935142
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- tax fiscal document
- Cancel NF-e
- Cancel electronic fiscal document
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel an NF-e that is generated from a tax fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel an incorrect nota fiscal eletrônica (NF-e) that is generated from a tax fiscal document. You can cancel the NF-e before you submit it to the Secretaria da Fazenda (SEFAZ). Alternatively, you can cancel the NF-e after it is processed or approved by SEFAZ.


> [!NOTE]
> <P>You can cancel a tax fiscal document NF-e that was processed or approved. However, you can cancel an approved NF-e only if SEFAZ approves the cancellation.</P>



When you cancel the NF-e, a tax fiscal document that has a negative amount is created. When you post the negative tax fiscal document, the original tax fiscal document is marked as canceled, and the settlements are reversed.

1.  Click **General ledger** \> **Journals** \> **All tax fiscal documents**.

2.  Double-click the tax fiscal document that is associated with the original NF-e.

3.  In the **Tax fiscal document** form, on the **Action Pane**, click **Cancel fiscal document** to cancel the tax fiscal document. For more information, see [(BRA) Cancel an ICMS tax fiscal document](bra-cancel-an-icms-tax-fiscal-document.md).

## See also

[(BRA) Tax fiscal document (form)](https://technet.microsoft.com/library/jj710428\(v=ax.60\))

  


