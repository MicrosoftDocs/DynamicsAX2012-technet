---
title: (BRA) Page and book control for legal accounting reports
TOCTitle: (BRA) Page and book control for legal accounting reports
ms:assetid: b8b3e611-ac01-41ee-9316-54bba2a720ed
ms:mtpsurl: https://technet.microsoft.com/library/JJ710607(v=AX.60)
ms:contentKeyID: 49384497
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- accounting reports
- book control
- legal accounting reports
- page and book control
- BR - 00019
audience: Application User
ms.search.region: Brazil
---

# (BRA) Page and book control for legal accounting reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Day book report, which is the primary legal accounting report, contains the daily transactions sorted by date for a specified period. The Day book, Financial statement, and Chart of accounts reports are generated for a legal entity that has made an actual profit. For a legal entity that has made a presumed profit, the Financial statement report for statements of changes in equity and the Trial balance summary report are generated, in addition to the previous reports.

Each day book report can contain only 500 pages. If a report contains more than 500 pages, the remaining pages, up to 500, are printed in a second book. For example, a report has 20 pages and the first page of the report starts on page 496 of book 1. The report is generated up to page 499 of book 1, and the remaining 17 pages are generated in book 2, starting from page 2.


> [!NOTE]
> <P>There are 17 pages remaining instead of 16 because page 496 in this scenario contains only the open term, and does not count as one of the 20 pages of the report.</P>



A day book report must contain open and close terms, book numbers, and page numbers. An open term is the first page of the report, and a close term is the last page. You can create open and close terms for day books and define page numbers and book numbers for the following reports:

  - **Day book**

  - **Financial statement**

  - **Chart of accounts**

  - **Trial balance summary**

## See also

[(BRA) Set up and generate open and close terms for a legal accounting report](bra-set-up-and-generate-open-and-close-terms-for-a-legal-accounting-report.md)

  


