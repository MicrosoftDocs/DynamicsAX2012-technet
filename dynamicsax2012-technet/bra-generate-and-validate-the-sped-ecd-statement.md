---
title: (BRA) Generate and validate the SPED ECD statement
TOCTitle: (BRA) Generate and validate the SPED ECD statement
ms:assetid: 8d84db97-4bf2-4e79-bef6-2c6c4b47c1d7
ms:mtpsurl: https://technet.microsoft.com/library/Dn600279(v=AX.60)
ms:contentKeyID: 62200243
author: Khairunj
ms.date: 05/07/2014
mtps_version: v=AX.60
f1_keywords:
- forms.SysOperationTemplateForm
audience: Application User
ms.search.region: Brazil
---

# (BRA) Generate and validate the SPED ECD statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to generate and validate the text file for the digital accounting bookkeeping (SPED ECD) statement.

The SPED ECD statement requires organizations to calculate and report the taxable profits based on the following types of accounting records:

  - Journal registers and supporting records

  - General ledger and subledgers

  - Daily trial balances and balance sheets

## Generate and validate a SPED ECD text file

To generate and validate the text file for the SPED ECD statement, follow these steps:

1.  Click **Fiscal books** \> **Common** \> **SPED ECD** \> **Generate SPED ECD**.

2.  Select the fiscal organization to generate the SPED ECD file for.

3.  In the **From date** and **To date** fields, select the starting and ending dates of the ledger transactions to report on.

4.  Select the **Include accounting statements** check box to generate the Block J text file in addition to the SPED ECD file.

5.  Select the time period to calculate financial statement balances for.

6.  Enter the path where the files will be saved.

7.  In the **Booking number** field, enter the accounting book number.
    
    The **Booking type** field automatically displays the value of G (Livro Diario completo sem escrituracao auxiliary).

8.  Select the type of company situation from the following options, or leave the field blank to represent the regular situation:
    
      - **Division**
    
      - **Merger**
    
      - **Incorporation**
    
      - **Closing-down**
    
      - **Transformation**

9.  In the **Opening fiscal period** field, select from the following options:
    
      - **Regular**
    
      - **Opening**
    
      - **Split, Merge or Acquisition**
    
      - **Mandatory**

10. In the **Layout version** field, select the layout of the SPED ECD file.

11. In the **File type** field, select the type of file to generate from the following options:
    
      - **Original**
    
      - **Substitute with NIRE**
    
      - **Substitute without NIRE**
    
      - **Substitute with NIRE changes**
    
    Número de Identificação no Registro de Empresas (NIRE) is entered in the **Fiscal establishment** form on the **Tax registration** FastTab.

12. Click **OK** to generate the SPED ECD file.

13. Click **Fiscal books** \> **Common** \> **SPED ECD** \> **Validate SPED ECD**.

14. Click **OK** to validate the SPED ECD file.

  


