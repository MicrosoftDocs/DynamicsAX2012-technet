---
title: Set up funding rules for a project contract
TOCTitle: Set up funding rules for a project contract
ms:assetid: b194fea3-9cfc-474e-860d-3fda41eceb5d
ms:mtpsurl: https://technet.microsoft.com/library/Hh242721(v=AX.60)
ms:contentKeyID: 36058981
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced funding
- funding rules
- project contract
- funding rule allocation
audience: Application User
ms.search.region: Global
---

# Set up funding rules for a project contract 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Funding rules define how to allocate charges for project contracts that have multiple funders. Each funding rule consists of a combination of one or more of the following values:

  - Priority

  - Project

  - Activity

  - Transaction type

  - Category group

  - Category

  - Worker

  - Item

Only the priority and transaction type values are required for a funding rule. All others, in addition to start and end dates, are optional. Additionally, the type of transaction that you are creating the funding rule for determines which of the other fields can be configured. For example, the **Item number** field is available only if you select **All** or **Item transactions** in the **Transaction type** field.

### Create a funding rule

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Create a project contract that has multiple funding sources, or open an existing project contract that has multiple funding sources, and then select the **Funding limits** FastTab.

3.  Click the **Add** button.

4.  Select the criteria for this funding rule.

5.  Repeat steps 3 and 4 for each funding rule that you want to create for the project contract.

6.  On the **Funding rules** FastTab, in the **Priority** column, assign a priority number to the funding rules. These priority numbers can be useful when you want one type of transaction in a project to be funded before another type of transaction in the same project contract. For example, hour transactions might be assigned a priority of 1, but expense transactions a priority of 2. This would help make sure that workers are paid before material purchases are funded.

After you create the funding rules, assign a percentage to each funding source in a funding rule to indicate the portion of the project that the funder should be invoiced for.

### Assign invoicing percentages to funding sources

1.  Click the **Funding rules** FastTab, and then select a funding rule.

2.  Click the **Allocation** button.

3.  In the **Specify funding rule allocations** form, select a funder or click **New** button to add another funder to the allocation plan.

4.  In the **Allocation percent** field, enter a number to represent the percentage of funding that you want the selected funding source to be responsible for with this rule.
    

    > [!NOTE]
    > <P>The total of all allocation percentages that you enter must equal 100 before you can save the rule.</P>



5.  If rounding differences in the funding calculation should be assigned to this funding source, select the **Rounding** check box. Only one source can be selected if there are multiple funding sources in this rule.

## See also

[Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md)

[About project contract funding](about-project-contract-funding.md)

[Set up project contract funding](set-up-project-contract-funding.md)

[Set up funding limits for funding sources in a project contract](set-up-funding-limits-for-funding-sources-in-a-project-contract.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

  


