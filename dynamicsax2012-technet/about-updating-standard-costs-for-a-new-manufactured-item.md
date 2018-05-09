---
title: About updating standard costs for a new manufactured item
TOCTitle: About updating standard costs for a new manufactured item
ms:assetid: 60902a19-39a3-4568-973e-1aeaf2f80939
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231515(v=AX.60)
ms:contentKeyID: 36057629
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About updating standard costs for a new manufactured item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufacturing environments involve maintaining standard costs for new manufactured items. A typical scenario involves a new manufactured item that has a new bill of materials (BOM) that contains new purchased items and new manufactured items as components. The following guidelines focus on this typical scenario.

The following guidelines assume use of a two-version approach to standard cost updates. In this approach, one costing version contains the first defined standard costs for the frozen period, and the second costing version contains the incremental updates that pertain to the new manufactured items. The incremental updates are entered as cost records in the second costing version and, ultimately, enabled.

The two-version approach requires the definition of a second costing version. The guidelines for defining this costing version include the following:

  - Assign a costing type of standard costs.

  - Assign a significant identifier to the costing version that communicates the contents, such as 2008-UPDATES.

  - Ensure that the content includes cost records.

  - Allow the entry of cost records for all sites. Entering a site limits the entry of cost records to the specified site.

  - Use a fallback principle of active costs.

To add new manufacturing items throughout the frozen period, follow these steps:

1.  Use the **Costing version setup** form to allow the entry of cost records into the second costing version that contains the incremental updates. Prevent the activation of pending costs, where activation is allowed after pending costs have been completely and accurately defined. Indicate a blank from-date as a policy in the costing version, and then enter the from-date when you enter each cost record. The from-date should represent a date before the new items are purchased or manufactured.

2.  Use the **Price** form to enter cost records for new purchased items. For each cost record, enter the costing version that contains incremental updates, and use a from-date that comes before the expected manufacturing date for new manufactured items.

3.  Calculate the cost of new manufactured items by using the **Calculation** form. You can open the **Calculation** form from the **Costing version maintenance** form and then selecting the costing version that contains the incremental updates. Use the selection criteria to selectively identify the new manufactured item and any one of its manufactured components. In a multilevel product structure, you might also have to selectively identify any parent item that contains the new manufactured items as a component.
    
    Enter a from-date for the BOM calculation that corresponds to the start of manufacturing for the new manufactured items. The from-date should be in the effective dates for the item’s BOM version and route version.
    

    > [!NOTE]
    > <P>A missing cost record can indicate a new manufactured item. BOM calculations can be limited to items that have missing costs.</P>

    
    Verify the calculated costs for new manufactured items for completeness and accuracy. Use the **Complete** form to review the calculated costs for each item-cost record and any Infolog of warning messages. Alternatively, use the **Calculation** form to review the calculated costs.

4.  Change the blocking flag to allow the activation of pending-cost records in the second costing version by using the **Costing version setup** form.

5.  Enable all pending-cost records in the second costing version by using the **Activate prices** form, which you can open from the **Costing version maintenance** form. You can also enable the pending-cost records for individual items by opening the **Price** form and then clicking the **Activate** button.

6.  Use the **Costing version setup** form to change the blocking flags in the second costing version to prevent additional data maintenance. The blocking policies prevent the entry of new pending costs and the activation of pending costs.

## See also

[Set up initial standard costs in a manufacturing environment](set-up-initial-standard-costs-in-a-manufacturing-environment.md)

[Update standard costs in a manufacturing environment](update-standard-costs-in-a-manufacturing-environment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

