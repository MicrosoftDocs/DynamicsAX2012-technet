---
title: About costing sheet setup
TOCTitle: About costing sheet setup
ms:assetid: 55bdaf4e-8a5f-4a4f-a387-ecd750df0da1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242465(v=AX.60)
ms:contentKeyID: 36057317
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- costs
- costing
- costing sheet
- costing sheets
---

# About costing sheet setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Setting up the costing sheet involves two objectives. As the first objective, you define the format for displaying cost of goods sold information about a manufactured item or production order. The formatted display is termed a costing sheet. As the second objective, you define the basis for calculating indirect costs. The costing sheet setup builds on the cost group feature for displaying information and for the indirect cost calculation formulas. The two objectives of costing sheet setup are as follows:

  - Define the format for the costing sheet. The user-defined format for a costing sheet identifies the segmentation of costs that contain a manufactured item’s cost of goods sold. The item’s cost of goods sold information, for example, could be segmented into material, labor, and overhead based on cost groups. These cost groups are assigned to items, cost categories for routing operations, and indirect cost calculation formulas. The format for the costing sheet typically requires intermediate totals when multiple cost groups have been defined, such as aggregating multiple cost groups pertaining to material. The definition of a costing sheet format is optional, but a costing sheet format must be defined if indirect costs will be calculated.

  - Define the basis for calculating indirect costs. Indirect costs reflect manufacturing overheads that are associated with producing a manufactured item. An indirect cost calculation formula can be expressed as a surcharge or a rate. A surcharge represents a percentage of value, whereas a rate represents an amount per hour for a routing operation. A cost group defines the basis for the calculation formula. For example such as a 100 percent surcharge for a labor cost group or a USD 50.00 hourly rate for a machine cost group. In order to define a calculation formula and its cost group basis, the costing sheet setup requires the identification of the cost group that represents the overhead and the selection of a surcharge or rate approach.

Each calculation formula must be entered as a cost record. The cost record consists of a specified costing version, a surcharge percentage, or a rate amount, the cost group basis, a status, and an effective date. A cost record is initially entered with a pending status and effective date. Activating the cost record updates the status (to current active) and the effective date (to the activation date). The cost record can also specify a site for a site-specific calculation formula, or indicate a company-wide calculation formula by leaving the site field blank. The cost record can optionally consist of a specified item or item group when the calculation formula has been flagged as per item.

The current active cost records for indirect cost calculation formulas will be used for estimating production order costs. They will also be used for calculating actual costs that are related to actual consumption of time and material. The pending cost records will be used in BOM calculations for a future date.

Two blocking policies for a costing version determine whether pending costs can be maintained and whether the pending cost can be started. Use the blocking policies to permit data maintenance, and then to prevent data maintenance for the cost data in a costing version.

After you define the costing sheet format and calculations for indirect costs, you must initiate a separate step to validate and save the information. The costing sheet represents a company-wide format for consistently displaying the costs of goods sold information.

The costing sheet is displayed as part of the **Calculate item cost** form. The costing sheet can be displayed for a manufactured item’s calculated cost record in the **Item price** form, or for an order-specific calculation record in the **BOM calculation results** form. It can also be displayed as part of the **Price calculation** form for a production order.

## Set up a costing sheet

  - Click **Inventory management** \> **Setup** \> **Costing** \> **Costing sheets**.

## See also

[About cost groups](about-cost-groups.md)

[Example of a costing sheet setup](example-of-a-costing-sheet-setup.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

