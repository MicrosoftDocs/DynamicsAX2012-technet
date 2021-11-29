---
title: (BRA) Print the DANFE in contingency mode
TOCTitle: (BRA) Print the DANFE in contingency mode
ms:assetid: 37e1b4b0-9e29-4f7c-b0a6-df2d97571d55
ms:mtpsurl: https://technet.microsoft.com/library/JJ937985(v=AX.60)
ms:contentKeyID: 50950774
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Print DANFE
- DANFE
- Documento Auxiliar da Nota Fiscal Eletrônica
audience: Application User
ms.search.region: Brazil
---

# (BRA) Print the DANFE in contingency mode 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Fiscal document** form to print a contingency Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) when there is a communication issue between Microsoft Dynamics AX and the Secretaria da Fazenda (SEFAZ).

Before you can print the DANFE in contingency mode, you must turn on contingency mode in the **Contingency mode** form. For more information, see [(BRA) Turn on or turn off contingency mode](bra-turn-on-or-turn-off-contingency-mode.md).

1.  Click **General ledger** \> **Inquiries** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.

2.  Select the fiscal document to print the DANFE for. Verify that the status of the NF-e is updated to **Created** in the **Status** field, and that the message status is updated to **Waiting to send**.

3.  On the **Action Pane**, on the **NF-e federal** tab, click **Security form contingency** to print the DANFE in contingency mode. This button is available only if you turn on the **FS - security form contingency** or **FS-DA security form contingency (auxiliary document)** contingency mode. For more information, see [(BRA) Contingency mode (form)](https://technet.microsoft.com/library/jj933511\(v=ax.60\)).

4.  When communication is re-established, you can turn off contingency mode and send the NF-e to SEFAZ. For more information, see [(BRA) Set up the export or import process for NF-e](bra-set-up-the-export-or-import-process-for-nf-e.md).

## See also

[(BRA) All fiscal documents (list page)](https://technet.microsoft.com/library/jj710567\(v=ax.60\))

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


