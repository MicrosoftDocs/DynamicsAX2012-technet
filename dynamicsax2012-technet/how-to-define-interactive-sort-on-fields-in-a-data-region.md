---
title: 'How to: Define Interactive Sort on Fields in a Data Region'
TOCTitle: 'How to: Define Interactive Sort on Fields in a Data Region'
ms:assetid: 108acf7b-2404-4003-bf37-151d481bfb38
ms:mtpsurl: https://technet.microsoft.com/library/Ee873246(v=AX.60)
ms:contentKeyID: 28119310
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Define Interactive Sort on Fields in a Data Region 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can sort the data on a report at runtime when you set the **Interactive Sorting** property for a field to **True**. Using this property, you can sort by column A and then later by column B. Interactive sorting is different from static sorting where a specific sort order is set when the report is built. For more information on static sorting, see [How to: Define a Sorted Data Region](how-to-define-a-sorted-data-region.md).

### To Define Interactive Sort on Fields

1.  In Model Editor, expand the auto design node for the report for which you want to add interactive sorting. You can set interactive sort on fields in a list, matrix, or table data region.

2.  Expand the node for the data region, and then expand the **Data** node.

3.  Select the field for which you want to add interactive sorting. You can sort individual fields or fields that have been grouped in your report.

4.  In the **Properties** window, set the **Interactive Sorting** property to **True**.

5.  Select the auto design node for the report and click the **Preview** button.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to true, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.
    
    The report displays and you can sort the report by the data for which you set interactive sorting. You can set multiple fields with sort functionality. The sort will also update based on the grouping you set in your report. For more information on how to group data in your report, see [How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md). If you have aggregated fields on a grouped data region the sort will update the aggregated values. For information on aggregated fields, see [How to: Display Aggregate Values in a Data Region](how-to-display-aggregate-values-in-a-data-region.md).

## See also

[Adding Interactive Features to Reports](adding-interactive-features-to-reports.md)

[Working with Data Regions](working-with-data-regions.md)

