---
title: About allocation rules
TOCTitle: About allocation rules
ms:assetid: f562dbeb-3d11-4a93-b22d-5595ffb5bc54
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ff395364(v=AX.60)
ms:contentKeyID: 36059999
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About allocation rules [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains the difference between fixed and variable allocations, the allocation methods that are available for allocations, the components of each allocation, and how ledger allocation rules are used in budget planning. Allocation is the distribution of monetary amounts to one or more accounts or account and dimension combinations based on allocation rules.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Fixed and variable allocations

There are two types of allocations: fixed and variable.

Fixed allocation is used to distribute specified percentages of a transaction amount to distribution accounts and dimensions. For example, corporate advertising expenses might be shared across specific departments. Department A would get 70 percent of the advertising expense, Department B would get 20 percent, and Department C would get 10 percent.

Variable allocation is used to distribute fluctuating percentages of a transaction amount to various accounts and dimensions. For example, you could allocate corporate advertising costs based on each department's sales in proportion to the total departmental sales.

## Allocation methods

The following allocation methods are available:

  - **Basis**

  - **Fixed percentage**

  - **Fixed weight**

  - **Distribute the source document amount equally**

If the allocation method for an allocation rule is **Basis**, you must also define a separate basis rule for ledger allocations. The following section describes the components of those rules.

## Components of allocation rules

Each allocation rule has four primary components: general, source, destination, and offset. Each component provides a critical piece of the information that is required to process allocations.

  - The general component is where the user specifies options including, but not limited to, allocation method, intercompany rule settings, and whether the rule is active. General settings dictate which fields are available on the subsequent rule tabs.

  - The source component is where the user specifies the source data for the allocation, and is also named the allocation pool or “bucket.” Amounts can come from the general ledger, or you can specify a fixed value for the source of the allocation.

  - The destination defines how the result of the allocation calculation should be distributed to the destination distribution lines.

  - The offset defines offset entries that balance the destination distribution lines. These entries typically are used instead of the accounts and dimensions that are specified in the source.

  - The basis describes what the allocation calculation is based on and defines in what proportion the source amounts are allocated to the destination distribution lines. References to basis are used only when the allocation method is **Basis**, because that is the only method that requires basis-type information.

## Ledger allocation rules in budget planning

Beginning with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can use ledger allocation rules for budget plans. When you use ledger allocation rules in budget planning, the allocation rules work the same way they would in the ledger, but the source data and destination data comes from the budget plan.

You can manually select ledger allocation rules to use for budget plans. For more information, see [Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md). Alternatively, you can use an allocation schedule that runs as part of a workflow process. For information about how to set up an allocation schedule, see [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md).


> [!NOTE]
> <P>You can’t use intercompany ledger allocation rules for budget planning.</P>



## See also

[Create an allocation rule](create-an-allocation-rule.md)

[Create allocation rule source and destination information](create-allocation-rule-source-and-destination-information.md)

[Create an allocation journal](create-an-allocation-journal.md)

[Process an allocation request](process-an-allocation-request.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

