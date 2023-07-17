---
title: (BRA) Set up project parameters
TOCTitle: (BRA) Set up project parameters
ms:assetid: 15ed1300-84a4-4e35-a0b4-e737209e1599
ms:mtpsurl: https://technet.microsoft.com/library/JJ853379(v=AX.60)
ms:contentKeyID: 50396748
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project transactions
- fiscal document
- fiscal
- split invoices
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up project parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can group project transactions that you create for hour, expense, on-account, or item project transactions by different criteria such as transaction text, employee, invoice type, or transaction lines before you print the fiscal document lines. You can also specify the default Código Fiscal de Operações e Prestações (CFOP) codes for the same state, a different state, or outside the country or region when you generate fiscal documents from project transactions. You can split project invoices based on service code when you post the invoice.

You can set up the default unit to use in fiscal document lines that are created for hour, expense, on-account, or item project transactions in the **Unit** field in the **Brazilian parameters** form. For more information, see [(BRA) Set up Brazilian parameters](bra-set-up-brazilian-parameters.md).

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  Click **Invoice**.

3.  In the **Invoice** area, select the **Transaction text** check box to group project transactions by transaction text to generate and print project fiscal documents.

4.  Select the **Employee** check box to group project transactions by the identification code of the person who is associated with the project transaction to generate and print project fiscal documents.

5.  Select the **Invoice type** check box to group project transactions by invoice type to generate and print project fiscal documents.

6.  Select the **Line-specific** check box to group project transactions by category, sales tax group, and item sales tax group to generate and print project fiscal documents.

7.  In the **Same state** field, select the default CFOP code to generate and print service project fiscal documents for project transactions for customers and vendors that are located in the same state as the fiscal establishment of the legal entity.

8.  In the **Other state** field, select the default CFOP code to generate and print service project fiscal documents for project transactions for customers or vendors that are located in the same country/region as the fiscal establishment of the legal entity, but in another state.

9.  In the **Outside country/region** field, select the default CFOP code to generate and print project fiscal documents for project transactions for customers and vendors that are located in a different country from the fiscal establishment of the legal entity.

10. Select the **Invoice** check box to split invoices based on service code when you post a project fiscal document.

## See also

[(BRA) Post an NF-e from a project invoice](bra-post-an-nf-e-from-a-project-invoice.md)

[(BRA) Create and post a project debit note](bra-create-and-post-a-project-debit-note.md)

[(BRA) Set up the CFOP codes](bra-set-up-the-cfop-codes.md)

[(BRA) Projects (modified form)](https://technet.microsoft.com/library/jj923389\(v=ax.60\))

[(BRA) Project management and accounting parameters (modified form)](https://technet.microsoft.com/library/jj937990\(v=ax.60\))

[(BRA) CFOP codes (form)](https://technet.microsoft.com/library/jj933522\(v=ax.60\))

  


