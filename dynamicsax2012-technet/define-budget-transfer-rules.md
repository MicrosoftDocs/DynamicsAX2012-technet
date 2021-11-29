---
title: Define budget transfer rules
TOCTitle: Define budget transfer rules
ms:assetid: 18c5412b-79c5-4783-82c3-d26d6970c0d8
ms:mtpsurl: https://technet.microsoft.com/library/Hh208446(v=AX.60)
ms:contentKeyID: 36056104
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget transfers
- budget transfers and workflows
- transfer budget amounts
- workflow and budget transfers
audience: Application User
ms.search.region: Global
---

# Define budget transfer rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Budget transfer rules** form to define budget transfer rules to determine when budget transfers are allowed between financial dimension values. For example, budget transfers in a specific department might be allowed without approval, but transfers across departments might have to be reviewed and approved before the budget balance is adjusted. If a budget register entry is submitted and it violates the budget transfer rules, the transfer can be completed only if it is approved through a Budgeting workflow. For more information, see [Set up Budgeting workflows](set-up-budgeting-workflows.md).

1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget transfer rules**.

2.  Click **New** and enter an identifier and a description for the budget transfer rule.

3.  Select an account structure.

4.  Click **Add** to define the financial dimension criteria for a rule member.
    
    For example, you could define criteria for the Sales department. If a transfer was entered that had budget account entries that did not contain the Sales department financial dimension, the rule would stop the transfer. If workflow was activated for the budget code that is associated with the budget type, the transfer would be submitted for approval.

5.  You can click **Add** again to add multiple rule members to the same rule. You cannot specify the same financial dimension criteria in more than one rule member for a transfer rule. However, you can have overlaps in financial dimension criteria across budget transfer rules so that the same financial dimension value can belong to multiple budget transfer rules.

6.  To enable the budget transfer rules that you defined, select **Use rules for budget transfers** in the **Budget parameters** form.

## See also

[Budget transfer rules (form)](https://technet.microsoft.com/library/hh209073\(v=ax.60\))

  


