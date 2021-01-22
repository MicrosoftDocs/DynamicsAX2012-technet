---
title: (BRA) Set up a fiscal organization
TOCTitle: (BRA) Set up a fiscal organization
ms:assetid: 31f180fc-09c4-4f1e-b0a3-88ea29185b22
ms:mtpsurl: https://technet.microsoft.com/library/Dn305863(v=AX.60)
ms:contentKeyID: 54912963
author: Khairunj
ms.author: daxcpft
ms.date: 05/15/2015
mtps_version: v=AX.60
f1_keywords:
- forms.FiscalOrganization_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a fiscal organization 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up a fiscal organization, which is a group of fiscal establishments that belong to different fiscal entities but that have the same root fiscal establishment.

The SPED EFD - Contributions statement is centralized by the root fiscal establishment. All fiscal establishments are created in the **Fiscal establishments** form. Use the **Fiscal organization** form to select a root fiscal establishment, and then group fiscal establishments that belong to different fiscal entities but that have the same root fiscal establishment. You can add more fiscal establishments to the **Fiscal establishments** form if the first nine digits of the CNPJ/CPF number of the root fiscal establishment are the same for the fiscal establishments that are created in the **Fiscal establishments** form.


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Set up a fiscal organization

To set up a fiscal organization, follow these steps:

1.  Click **Fiscal books** \> **Setup** \> **Fiscal organization**.

2.  In the **Root fiscal establishment** field, select a fiscal organization that is used for SPED contributions.

3.  On the **Fiscal establishment** FastTab, fiscal establishments are automatically added to the list if they have the same nine digits of the CNPJ/CPF number as the fiscal organization that is selected in the **Root fiscal establishment** field.
    
      - To remove a fiscal establishment that has been added to the list, click **Remove**.
    
      - To add other fiscal establishments from other legal entities, click **Add**.

4.  On the **Company social contract** FastTab, enter the archive date of the company’s constitution contract and the company’s conversion.

5.  On the **SCP** FastTab, select the type of SCP company.
    
      - **Not participant as SCP partner**
    
      - **Participant as SCP partner**
    
      - **SCP**

6.  Introduce the SCP code when you selected SCP company type.

7.  On the **Related SCP** FastTab, click **Add** to enter the name and code of SCP related company.
    

    > [!NOTE]
    > <P>This information is enabled if you selected <STRONG>Participant as SCP partner</STRONG>.</P>



8.  On the **Legal representative** FastTab, click **Add** to enter the name of the company’s legal representative.

9.  Enter the CPF registration number and the role of the legal representative.
    
      - To add another legal representative, click **Add**.
    
      - To remove a legal representative that has been added to the list, click **Remove**.

10. On the **Independent auditors** FastTab, click **Add** to enter the name of the auditor and the registration number.

11. To remove an independent auditor that has been added to the list, click **Remove**.
    

    > [!NOTE]
    > <P>This option is available when the Large company check box has been selected.</P>


  


