---
title: (BRA) Set up fiscal books parameters per state
TOCTitle: (BRA) Set up fiscal books parameters per state
ms:assetid: 44485ac4-7ad3-430a-b594-a3d688c55a50
ms:mtpsurl: https://technet.microsoft.com/library/Dn305866(v=AX.60)
ms:contentKeyID: 54912966
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBParametersPerState_BR
- MsDynAx060.Forms.FBParametersPerState_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up fiscal books parameters per state 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can enter adjustments for Imposto sobre Circulação de Mercadorias e Serviços (ICMS) taxes that have been applied in the period that is covered by a Sistema Publico de Escrituração Digital (SPED) fiscal text file. Each state defines whether the adjustments can be made to tax amounts in general, or to tax amounts on fiscal documents. For example, Sao Paulo allows general adjustments, while Rio de Janeiro allows both general adjustments and adjustments to fiscal documents.

This topic explains how to specify default adjustment codes and CIAP options for each state by using the **Fiscal books parameters per state** form. An adjustment is automatically made for the tax assessment for the amount of the ICMS differential. This adjustment is made for a fiscal document or in general, depending on the requirements of the state.

For information about how to enter ICMS and ICMS tributary substitution (ICMS-ST) tax adjustment transactions, see [(BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes](bra-assess-pay-declare-and-adjust-icms-and-icms-st-taxes.md). For information about how to work with Controle de Crédito de ICMS do Ativo Permanente (CIAP) fixed assets, see [(BRA) Working with fiscal books for fixed assets](bra-working-with-fiscal-books-for-fixed-assets.md).


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Set up fiscal books parameters per state

1.  Click **Fiscal books** \> **Setup** \> **Fiscal books parameters per state**.

2.  Select a state.

3.  If the ICMS tax amounts can be adjusted on fiscal documents, select the **By fiscal document** check box, and then select the default adjustment code and observation code.

4.  If the ICMS tax amounts cannot be adjusted on fiscal documents, clear the **By fiscal document** check box, and then select the default adjustment code.

5.  To automatically calculate an ICMS credit installment when an outgoing transaction is created, select the **Calculate installment for outgoing transactions** check box.

6.  To set up fiscal books parameters for other states, repeat steps 2 through 5.

  


