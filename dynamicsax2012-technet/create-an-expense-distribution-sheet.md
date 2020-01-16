---
title: Create an expense distribution sheet
TOCTitle: Create an expense distribution sheet
ms:assetid: c588d46e-856b-454b-8540-c953901ebe28
ms:mtpsurl: https://technet.microsoft.com/library/Aa550756(v=AX.60)
ms:contentKeyID: 36059301
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create an expense distribution sheet 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must create an expense distribution sheet (EDS) before you can run an EDS report. In the EDS, you must set up the report lines and report columns that will appear in the report.

## Types of EDS

There are two types of EDS: dimension statement and cost statement.

  - Dimensions statement – Use this EDS to report and compare results of different dimensions. Each column corresponds to one dimension.

  - Cost statement – Use this EDS to create a report for one or more dimensions or divisions. However, results for each dimension or division appear on a separate page, and columns compare actual and budget costs for each dimension or division.

## Setup of EDS

To create a new EDS:

1.  Set up a line structure. The line structure is the basis for report lines.

2.  Set up a calculation type. The calculation type determines the cost balances that are considered for the report. Select from among the following calculation types:
    
      - Period calculation
    
      - Special calculation
    
      - Plan calculation

3.  Set up a report type. The report type determines the type of EDS report, whether it is a dimension statement or a cost statement.

4.  Set up a hierarchy. You must select a hierarchy if you want to use the cost statement for hierarchies.

## Report lines

You can manually or automatically define lines that you want to view in the report by using the transfer lines function.

Report lines are identical to cost lines for the selected line structure.

If the lines are entered automatically, you can still modify them by deleting or changing their position in the report. Change their position in the report by using the up and down buttons.

## Report columns

You can define columns that you want to view in the report.

## See also

[Cost accounting report (form)](https://technet.microsoft.com/library/aa548502\(v=ax.60\))

[Expense distribution sheet](expense-distribution-sheet.md)

[Run a report](run-a-report.md)

  


