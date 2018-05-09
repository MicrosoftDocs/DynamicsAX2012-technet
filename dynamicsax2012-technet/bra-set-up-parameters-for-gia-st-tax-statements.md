---
title: (BRA) Set up parameters for GIA ST tax statements
TOCTitle: (BRA) Set up parameters for GIA ST tax statements
ms:assetid: 82fe042c-3996-4a06-acf1-a9458500aae5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn600277(v=AX.60)
ms:contentKeyID: 62200241
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxStatementSetupParameters_BR
- MsDynAx060.Forms.FBTaxStatementSetupParameters_BR
---

# (BRA) Set up parameters for GIA ST tax statements 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to specify how the text files for Guia de Informação e Apuração tributary substitution (GIA ST) statements will be saved before you submit them to the state tax authorities.

The GIA ST text file contains information about all fiscal documents that have been received and issued each month for each fiscal establishment that has an IE registration for that state. The GIA ST text file is issued to state tax authorities to verify the Imposto Sobre Circulação de Mercadorias e Serviços Substituição Tributária (ICMS-ST) and Imposto sobre Produtos Industrializados (IPI) tax calculations. For more information about how to generate the monthly GIA ST text file, see [(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md).

## Set up requirements for GIA ST text files

To set up requirements for the text files for GIA ST tax statements, follow these steps:

1.  Click **Fiscal books** \> **Setup** \> **Tax statements parameters**. Select **GIA ST**. On the **Setup parameters** FastTab, click **Open** to open the **GIA ST setup parameters** form.

2.  In the **File location** field, enter the location where the GIA ST text file will be saved.

3.  In the **GIA layout version** field, select the layout of the GIA ST text file to generate. For Microsoft Dynamics AX 2012 R3, only the **02** layout version is supported.

4.  In the **GIA type** field, select from the following options:
    
      - **Normal** – Select this option to generate the monthly GIA ST text file.
    
      - **Substitute** – Select this option to generate a correction to a previously submitted GIA ST text file.

5.  Repeat steps 2 through 4 for each fiscal establishment.

## See also

[(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

