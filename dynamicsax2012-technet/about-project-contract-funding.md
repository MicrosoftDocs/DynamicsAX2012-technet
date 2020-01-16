---
title: About project contract funding
TOCTitle: About project contract funding
ms:assetid: 23d5abea-c4b6-431e-853a-dd010d34c524
ms:mtpsurl: https://technet.microsoft.com/library/Hh208479(v=AX.60)
ms:contentKeyID: 36056185
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced funding
- funding rules
- funding source
- shared funding
audience: Application User
ms.search.region: Global
---

# About project contract funding 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some project contracts might specify that more than one party will share funding responsibilities for the project costs. For example, a large customer might request split funding of a project by its multiple divisions, or your company can share the costs of a large project with an external organization. For example, a road might be co-funded by two municipalities, or a bridge might be funded by a government grant and a private corporation. Microsoft Dynamics AX makes it possible for you to split the billing for a single transaction or an entire project among multiple customers, grants, or organizations.

In projects that have multiple funders, all parties that contribute to the funding of an advanced funding project are called funding sources. After a customer, organization, or grant is defined as a funding source, it can then be assigned to one or more funding rules. Funding rules contain the criteria for how to allocate charges to different funding sources for a project.


> [!IMPORTANT]
> <P>Stocked items, such as those that appear on purchase requisitions and purchase orders, cannot be split. As a result, at the time of distribution, the cost amount also cannot be split among multiple funding sources. Therefore, the funding source value remains at zero until the inventory issue is posted. At that time, the cost amount is distributed according to the account distribution rules for the project.</P>



To help facilitate split billing among multiple funding sources, you can do the following:

  - Specify that all transactions that are entered for a project use the same sales currency as the project contract.

  - Set up funding limits so that a funding source is not invoiced more than a specified amount toward a project.

  - Configure funding rules and funding limits for each worker, item, category, category group, and transaction type (or for all transaction types).

  - Choose optional start and end dates to define the period of time for which each funding rule is valid.

  - Specify the percentage that each funding source is responsible for.

  - Specify which funding source is responsible for rounding differences that result from funding allocation calculations.

  - Set up rules for how project costs are invoiced to external customers and charged to internal organizations.

  - Record transactions in an on-hold funding account until additional funding can be obtained or you decide to bear the costs internally.

To determine which tax group to associate with a transaction, Microsoft Dynamics AX searches the project for a tax group assignment. If no tax group assignment has been made at the project level, Microsoft Dynamics AX searches the project contract.

## See also

[Create a project contract](create-a-project-contract.md)

[Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md)

[Set up funding limits for funding sources in a project contract](set-up-funding-limits-for-funding-sources-in-a-project-contract.md)

[Set up funding rules for a project contract](set-up-funding-rules-for-a-project-contract.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

  


