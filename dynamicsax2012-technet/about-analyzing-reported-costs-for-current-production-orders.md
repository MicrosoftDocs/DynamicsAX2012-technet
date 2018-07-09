---
title: About analyzing reported costs for current production orders
TOCTitle: About analyzing reported costs for current production orders
ms:assetid: 2dfc7e5e-fda7-44bd-b19a-61dc82ae07f5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231020(v=AX.60)
ms:contentKeyID: 36056271
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About analyzing reported costs for current production orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reported production activities can be grouped into four types of transactions. Three types of transactions represent the reported consumption of material, routing operations and indirect costs, and one type of transaction represents the reported production activities as finished items. Separate reports provide information about each type of transaction. Use these reports to analyze costs for reported production activities. Information is only displayed for current production orders that have a status of started or reported as finished.

  - **Raw materials in process** report − the report lists the picking list transactions that are reported against the current production orders as of a specified transaction date. The report indicates the component’s quantity that is issued and the cost amount for each transaction. Use the selection criteria for a single component item, for example, to print information about the component’s issued quantity against applicable production orders. The quantity that was issued is not updated by the report-as-finished quantities for the parent item. Therefore, the actual quantity of raw materials in process may be overstated.

  - **Work in process** report − the report lists route (or job) transactions reported against the current production orders as of a specified transaction date. The report indicates the hours, amount and quantity (both good and error) reported for each transaction, and information such as the operation number, operation ID, and operations resource. The report also displays the total time and amount for all transactions against the production order, and the reported as finished quantity.

  - **Indirect costs in process** report − the report lists the indirect costs that have been incurred against production orders. This data is based on reported consumption of routing operations and components as of a specified transaction date. The report indicates the type of indirect cost (surcharge or rate), the costing sheet code for the indirect cost, and the cost amount for each transaction. The report does not provide information about the route card or pick list transaction that generated the indirect cost.

  - **In process production costing** report − the report lists the combined consumption of material, routing operations, and indirect cost against the production orders as of a specified transaction date.

  - **Finished items in process** report − the report lists current production orders and the report-as-finished transactions as of a specified transaction date.

## See also

[About analyzing costs for a production order](about-analyzing-costs-for-a-production-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

