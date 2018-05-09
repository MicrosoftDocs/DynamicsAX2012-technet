---
title: (BRA) Set up parameters for Sintegra tax statements
TOCTitle: (BRA) Set up parameters for Sintegra tax statements
ms:assetid: d2ddae45-e6c0-45a1-b0e2-230c566c583f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn600281(v=AX.60)
ms:contentKeyID: 62200246
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forms.FBTaxStatementSetupParameters_BR
- MsDynAx060.forms.FBTaxStatementSetupParameters_BR
---

# (BRA) Set up parameters for Sintegra tax statements 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how the text files for Sintegra tax statements will be saved before you submit them to the federal tax authorities.

The Sintegra text files contain information about all fiscal documents that have been received and issued each month. The Sintegra system is used by federal tax authorities to verify Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) and ICMS tributary substitution (ICMS-ST) by Códigos Fiscais de Operações E Prestações (CFOP) tax payments. For more information about how to generate the monthly Sintegra text file, see [(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md).

## Set up requirements for Sintegra text files

To set up requirements for the text files for Sintegra tax statements, follow these steps:

1.  Click **Fiscal books** \> **Setup** \> **Tax statements parameters**. Click **Sintegra**. On the **Setup parameters** FastTab, click **Open**.

2.  Select the fiscal establishment ID to set up the Sintegra parameters for.
    
    The code for the company where the fiscal establishment is located is displayed in the **Company** field.

3.  In the **File location** field, select the location where the Sintegra text file will be generated.

4.  Select the version of the Sintegra text file to generate. For Microsoft Dynamics AX 2012 R3, only **Version 3 – ICMS 73/03** is supported.

5.  In **File type** field, select from the following options:
    
      - **Normal** – Select this option to generate the monthly Sintegra text file.
    
      - **Substitute** – Select this option to generate a correction to a previously submitted Sintegra text file.

6.  Repeat steps 2 through 5 for each fiscal establishment.

## See also

[(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

