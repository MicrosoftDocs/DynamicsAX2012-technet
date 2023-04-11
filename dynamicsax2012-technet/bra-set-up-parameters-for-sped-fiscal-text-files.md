---
title: (BRA) Set up parameters for SPED fiscal text files
TOCTitle: (BRA) Set up parameters for SPED fiscal text files
ms:assetid: 030e469b-6b42-44e0-8389-bc5d91822071
ms:mtpsurl: https://technet.microsoft.com/library/Dn305858(v=AX.60)
ms:contentKeyID: 54912958
author: tfehr
ms.date: 06/07/2014
mtps_version: v=AX.60
f1_keywords:
- forms.FBTaxStatementSetupParameters_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up parameters for SPED fiscal text files 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Sistema Publico de Escrituração Digital (SPED) fiscal text files contain information about all fiscal documents that have been received and issued in a month for a specific fiscal establishment. The SPED system is used by federal tax authorities to verify Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) and Imposto sobre Produtos Industrializados (IPI) tax calculations. Before you can generate a SPED fiscal text file to submit to the federal tax authorities, you must specify parameters that define how the SPED fiscal text file will be saved. This topic explains how to specify these parameters by using the **SPED fiscal parameters** form. For information about how to generate the monthly SPED fiscal text file, see [(BRA) Generate the SPED fiscal export file for a month](bra-generate-the-sped-fiscal-export-file-for-a-month.md).


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Set up requirements for SPED fiscal text files

1.  Click **Fiscal books** \> **Setup** \> **Tax statements parameters**. Select **SPED Fiscal**, on the **Setup parameters** FastTab, click **Open**.

2.  In the **SPED fiscal parameters** form, select the location where the SPED fiscal text file will be saved.

3.  Select a profile presentation. For the current release, only the **A** profile presentation is supported.

4.  Select **1.06** or **1.07** as the version of the SPED fiscal text file format to generate.
    

    > [!NOTE]
    > <P>To generate the SPED fiscal text file for the year 2013, select <STRONG>1.06</STRONG>. To generate the SPED fiscal text file for the year 2014, select <STRONG>1.07</STRONG>.</P>



5.  Select the type of activity to include in the SPED fiscal text file. The following options are available:
    
      - **Industrial or equivalent** – Select this option to include information for activities related to industries, for example manufacturing of goods.
    
      - **Others** – Select this option for all other types of activities.

## See also

[(BRA) Generate the SPED fiscal export file for a month](bra-generate-the-sped-fiscal-export-file-for-a-month.md)

  


