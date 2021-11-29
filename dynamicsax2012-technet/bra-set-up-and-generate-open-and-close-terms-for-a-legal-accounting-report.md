---
title: (BRA) Set up and generate open and close terms for a legal accounting report
TOCTitle: (BRA) Set up and generate open and close terms for a legal accounting report
ms:assetid: ac85b0cb-b5f5-4989-bd8a-dbfa12adea83
ms:mtpsurl: https://technet.microsoft.com/library/JJ710590(v=AX.60)
ms:contentKeyID: 49384480
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- open and close terms
- generate open and close terms
- legal accounting
- legal accounting report
- set up open and close terms
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up and generate open and close terms for a legal accounting report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Open or close term** form to set up open and close terms for a legal accounting report. You can enter information for the open and close terms in the **Text** field by using defined variables. The variables are replaced with the corresponding values when the open and close terms are printed. You can use the following variables to set up texts for the open and close terms:

  - %1 – The accounting book number

  - %2 – The number of pages in the accounting book

  - %3 – The name of the company

  - %4 – The address of the company

  - %5 – The Cadastro Nacional da Pessoa Jurídica (CNPJ) number of the company

  - %6 – The Inscrição Estadual (IE) number of the company

For more information, see [(BRA) Page and book control for legal accounting reports](bra-page-and-book-control-for-legal-accounting-reports.md).

Use the following procedure to set up and generate open and close terms for a legal accounting report:

1.  Click **General ledger** \> **Setup** \> **Open or close term**.

2.  Create an open or close term.

3.  In the **Term code** and **Description** fields, enter a term code and a brief description of the term code.

4.  Click the **Text** FastTab, and then in the **Text** field, enter one or more of the variables %1, %2, %3, %4, %5, and %6.

5.  Close the form.

6.  Click **General ledger** \> **Reports** \> **Transactions** \> **Print open or close term**.

7.  In the **Term code** field, select a term code.

8.  In the **Book number** and **Page number** fields, enter the book number and page number that are displayed in the report.
    

    > [!NOTE]
    > <P>The page number must be lower than 500. In a 500 page report, page 500 is the close term page.</P>



9.  Click **OK** to generate the report.

## See also

[(BRA) Open or close term (form)](https://technet.microsoft.com/library/jj710478\(v=ax.60\))

[(BRA) Generate and print financial statements](bra-generate-and-print-financial-statements.md)

[(BRA) Print open or close term report (LedgerOpenCloseTermReport\_BR)](https://technet.microsoft.com/library/jj710402\(v=ax.60\))

  


