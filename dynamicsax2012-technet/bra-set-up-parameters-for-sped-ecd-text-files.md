---
title: (BRA) Set up parameters for SPED ECD text files
TOCTitle: (BRA) Set up parameters for SPED ECD text files
ms:assetid: 639d0f43-b73e-4c0a-ae69-c753511012a3
ms:mtpsurl: https://technet.microsoft.com/library/Dn600275(v=AX.60)
ms:contentKeyID: 62200237
author: Khairunj
ms.author: daxcpft
ms.date: 05/15/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxStatementSetupParameters_BR
- MsDynAx060.Forms.FBTaxStatementSetupParameters_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up parameters for SPED ECD text files 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to specify how Sistema Publico de Escrituração Digital (SPED) fiscal text files will be saved before you submit them to the federal tax authorities.

The SPED fiscal text files contain information about general ledger transactions, profit and loss information, and balance sheet information. The SPED ECD system is used by federal tax authorities to verify taxable profits of a company. For information about how to generate the yearly SPED ECD fiscal text file, see [(BRA) Generate and validate the SPED ECD statement](bra-generate-and-validate-the-sped-ecd-statement.md).

## Set up requirements for SPED ECD tax statement

To set up requirements for SPED ECD fiscal text files, follow these steps:

1.  Click **Fiscal books** \> **Setup** \> **Tax statements parameters**. Click **SPED ECD**. On the **Setup parameters** FastTab, click **Open**.

2.  Select the company to generate the SPED ECD text file for.

3.  Select the financial dimension set that the format of the SPED ECD text file will be based on. The financial dimension set should include the main account and the cost center dimensions.

4.  Select the file location where the SPED ECD text file will be generated.

5.  The Booking type is assigned automatically depending on the type of fiscal organization. See [(BRA) Set up a fiscal organization](bra-set-up-a-fiscal-organization.md) for more information.
    
      - G – This booking is used to detail all of the ledger journal transactions.
    
      - S – This booking is used for the SCP company.

6.  Select the type of company situation from the following options, or leave the field blank to represent the regular situation:
    
      - **Division**
    
      - **Merger**
    
      - **Incorporation**
    
      - **Closing-down**
    
      - **Transformation**

7.  In the **Opening fiscal period** field, select from the following options:
    
      - **Regular**
    
      - **Opening**
    
      - **Split, Merge or Acquisition**
    
      - **Mandatory**

8.  Select the version of the SPED ECD text file format to generate.
    
    1.  For Microsoft Dynamics AX 2012 R3, Version 2.00 is supported until fiscal year 2013.
    
    2.  For Microsoft Dynamics AX 2012 R3, Version 3.00 is supported from fiscal year 2014.

9.  In the **Auditor registration number** field, enter the number of the company’s auditor.

10. Enter the auditor’s name.

11. Select the **Large company** check box if the company is a large company.
    

    > [!NOTE]
    > <P>The steps 9, 10 and 11 are not available when Version 3.0 is selected. This information has been changed and included in the configuration of fiscal organization. See <A href="bra-set-up-a-fiscal-organization.md">(BRA) Set up a fiscal organization</A> for more information.</P>



## See also

[(BRA) Generate the Sintegra tax statement](bra-generate-the-sintegra-tax-statement.md)

  


