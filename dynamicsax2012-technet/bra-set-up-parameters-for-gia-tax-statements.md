---
title: (BRA) Set up parameters for GIA tax statements
TOCTitle: (BRA) Set up parameters for GIA tax statements
ms:assetid: e6e649f3-6e57-4544-b8fa-b56d92ce69b5
ms:mtpsurl: https://technet.microsoft.com/library/Dn600282(v=AX.60)
ms:contentKeyID: 62200247
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxStatementSetupParameters_BR
- MsDynAx060.Forms.FBTaxStatementSetupParameters_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up parameters for GIA tax statements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how the text files for Guia de Informação e Apuração (GIA) tax statements will be saved before you submit them to the São Paulo tax authorities.

The GIA text file contains information about all fiscal documents that have been received and issued each month for fiscal establishments that are located in São Paulo. The GIA system is used by the São Paulo state tax authorities to verify the Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) and ICMS tributary substitution (ICMS-ST) amounts by Códigos Fiscais de Operações E Prestações (CFOP) and the details of operations with Duty free zone (Zona Franca de Manaos). For more information about how to generate monthly GIA tax statements, see [(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md).

## Set up requirements for GIA fiscal text files

To set up requirements for the text files for GIA tax statements, follow these steps:

1.  Click **Fiscal books** \> **Setup** \> **Tax statements parameters**. Select **GIA**. On the **Setup parameters** FastTab, click **Open**.

2.  In the **GIA setup parameters** form, select the location where the GIA text file will be saved.

3.  In the **Layout version** field, select the layout of the GIA text file to generate. In Microsoft Dynamics AX 2012 R3, only version **0210** is supported.

4.  In the **Tributary regime** field, select from the following options:
    
      - **RPA**
    
      - **RPA-Exempt**

5.  In the **GIA type** field, select from the following options:
    
      - **Normal** – Select this option to generate the monthly GIA-ST text file.
    
      - **Substitute** – Select this option to generate a correction to a previously submitted GIA-ST text file.

6.  Repeat steps 2 through 5 for each fiscal establishment.

## See also

[(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md)

  


