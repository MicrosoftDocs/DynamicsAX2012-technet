---
title: (BRA) Set up adjustment codes to use to adjust IPI amounts
TOCTitle: (BRA) Set up adjustment codes to use to adjust IPI amounts
ms:assetid: 08fa2ce2-f90b-4e31-89a9-4fd4c04a54a8
ms:mtpsurl: https://technet.microsoft.com/library/Dn305857(v=AX.60)
ms:contentKeyID: 54912957
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBGeneralAdjustmentCodeIPI_BR
- MsDynAx060.Forms.FBGeneralAdjustmentCodeIPI_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up adjustment codes to use to adjust IPI amounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a Sistema Publico de Escrituração Digital (SPED) fiscal text file, record E530 includes information about adjustments of Imposto sobre Produtos Industrializados (IPI) taxes that have been applied in the period that is covered by the SPED fiscal text file. Before you can adjust IPI taxes, you must specify the adjustment codes that are determined by the Brazilian government depending on the adjustment criteria. This topic explains how to set up adjustment codes by using the **IPI adjustment codes table** form. For information about adjusting IPI tax, see [(BRA) Assess, pay, declare, and adjust IPI taxes](bra-assess-pay-declare-and-adjust-ipi-taxes.md).


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Set up adjustment codes for IPI taxes

1.  Click **Fiscal books** \> **Setup** \> **Setup** \> **Tax adjustment codes** \> **IPI adjustment codes table**.

2.  In the **IPI adjustment codes table** form, enter an adjustment code. The first character must be 0 for a credit adjustment or 1 for a debit adjustment.

3.  Enter a description.

4.  If the adjustment code will be used to report the reversal of a previously reported IPI tax amount, select the **Reversal adjustment code** check box.

5.  In the **Valid from** and **Valid to** fields, enter the first and last dates that the adjustment code is applicable.

6.  To create another adjustment code, click **New**, and then repeat steps 2 through 5.

  


