---
title: Analyze source code data
TOCTitle: Analyze source code data
ms:assetid: a0eb4e16-b1e7-460f-832a-246449720448
ms:mtpsurl: https://technet.microsoft.com/library/Dn497806(v=AX.60)
ms:contentKeyID: 62200124
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- catalog revenue
- Forms.TAMPromoStatistic
- Forms.TAMPromotionAnalysisSummary
- MsDynAx060.Forms.TAMPromotionAnalysisSummary
- MsDynAx060.Forms.TAMPromoStatistic
- analyze source code
- source code analysis
- source code revenue
- source codes
audience: Application User
ms.search.region: Global
---

# Analyze source code data 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to analyze sales data that is associated with a catalog source code. After you set up a source code and create sales orders that use the source code, you can perform an analysis to compare the projected revenue and costs for the source code with the actual revenue and costs. If a campaign is associated with the source code, you can include the campaign budget in the analysis.

For more information about how to set up a source code, see [Set up catalog source codes](set-up-catalog-source-codes.md).

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Setup steps</p></td>
<td><p><a href="set-up-catalog-source-codes.md">Set up catalog source codes</a></p></td>
</tr>
</tbody>
</table>


## Analyze source code data

To analyze source code data, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  Double-click the catalog for which to view statistics.

3.  On the **Source codes** FastTab, select a source code, and then click **Details**.

4.  On the **Action Pane**, click **Source code analysis**.

5.  In the **Promotion statistics** form, specify the data to include in the analysis:
    
      - **Sales orders** – Select this check box to include revenue for invoiced sales orders that reference a campaign or source code.
    
      - **Cost** – Select this check box to include promotional costs that are associated with the campaign or source code.
    
      - **Actual vs. budget** – In the list, select whether the analysis shows actual amounts, budgeted amounts, or the deviation between the actual and budgeted amounts.

6.  On the **Action Pane**, click **Calculate**. The **Statistics** tab displays statistics for the source code, and the **Graph** tab displays the results as a graph.

7.  Close the **Promotion statistics** form.

8.  In the **Source code definition** form, click **Compare promotions** to view data for multiple source codes in chart format.

9.  Click **Select**. On the **Range** tab, in the **Field** field, select the type of data to analyze. In the **Criteria** field, select the name of the entity to analyze.

10. Repeat step 9 to add more lines to the query, if more lines are required.

11. Click **OK**, and then click **OK** again to run the comparison. A graph displays the data that you selected to include in the analysis.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Source code</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Set up catalog source codes](set-up-catalog-source-codes.md)

[Perform a catalog area analysis](perform-a-catalog-area-analysis.md)

[Create call center catalogs](create-call-center-catalogs.md)

  


