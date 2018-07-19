---
title: About analyzing variances for a completed production order
TOCTitle: About analyzing variances for a completed production order
ms:assetid: 88509f5b-119e-4fcf-8c5d-a2c1fcd16e4a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242850(v=AX.60)
ms:contentKeyID: 37822151
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About analyzing variances for a completed production order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Production variances are calculated after you end a production order for a standard cost item. The variances reflect a comparison between the reported production activities and the calculation of standard costs for the production item. The variances do not reflect a comparison to the production order's estimated costs. The production activities that are reported include the consumption of material and routing operations, together with the associated indirect costs, and the quantity that is reported as finished. The following four types of variances are calculated:

  - Lot size variance

  - Production quantity variance

  - Production price variance

  - Production substitution variance

The following diagram identifies the four variances that account for the difference between a production order's actual costs and the calculated costs within the item's cost record when the production order is ended.

![Diagrams for Control](images/Gg242850.Control(AX.60).jpg "Diagrams for Control")

Analyze the production variances by using the **Variance** form or the **Production variance** report. Use the display options to view detailed variances by item and operations resource, or by cost group. You can also use the display options to view summarized variances. These display options are called single, multi, and total. The policy for cost breakdown in the inventory parameters determines whether the variances are tracked by cost group.

The information about detailed variances can help you understand the source of each variance. To predict variances before you end a production order, analyze the detailed information that is provided in the **Cost estimates and costings** report.

## See also

[About analyzing common sources of production variances](about-analyzing-common-sources-of-production-variances.md)

  


