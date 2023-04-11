---
title: (BRA) Turn on or turn off contingency mode
TOCTitle: (BRA) Turn on or turn off contingency mode
ms:assetid: 26590a7a-7da2-4880-b9f0-84e5db693bb0
ms:mtpsurl: https://technet.microsoft.com/library/JJ933500(v=AX.60)
ms:contentKeyID: 50935115
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- contingency mode
audience: Application User
ms.search.region: Brazil
---

# (BRA) Turn on or turn off contingency mode 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can turn on contingency mode when communication problems occur between Microsoft Dynamics AX and the Secretaria da Fazenda (SEFAZ). You can turn off contingency mode when the communication problem is resolved, and the contingency mode is no longer required.

## Turn on contingency mode

Use the following procedure to turn on contingency mode.

1.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Contingency**.

2.  In the left pane, select the fiscal establishment to turn the contingency mode on for.

3.  In the right pane, click **On** to open the **Active contingency** form.

4.  In the **Contingency mode** field, select one of the following options to indicate the contingency mode for the Nota Fiscal eletrônica (NF-e):
    
      - **FS - security form contingency** – Activate the Formulário de Segurança (FS) contingency mode.
    
      - **FS-DA security form contingency (auxiliary document)** – Activate the Formulario de Securança - Documento Auxiliar (FS – DA) contingency mode.

5.  In the **Contingency reason** field, enter the reason to activate the contingency mode.

6.  Click **OK** to turn on contingency mode. A transaction is recorded in the **Contingency mode** form.

## Turn off contingency mode

Use the following procedure to turn off contingency mode.

1.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Contingency**.

2.  In the left pane, select the fiscal establishment to turn the contingency mode off for.

3.  In the right pane, click **Off** to turn off contingency mode. A transaction is recorded in the **Contingency mode** form.

## See also

[(BRA) Contingency mode (form)](https://technet.microsoft.com/library/jj933511\(v=ax.60\))

[(BRA) Fiscal documents pending an update to contingency mode (list page)](https://technet.microsoft.com/library/jj937991\(v=ax.60\))

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


