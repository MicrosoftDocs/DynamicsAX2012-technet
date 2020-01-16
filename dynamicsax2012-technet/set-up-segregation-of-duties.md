---
title: Set up segregation of duties
TOCTitle: Set up segregation of duties
ms:assetid: e1800b9d-0679-4f0a-ade2-935cafa56459
ms:mtpsurl: https://technet.microsoft.com/library/Hh556869(v=AX.60)
ms:contentKeyID: 39509603
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up segregation of duties 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security or policies may require that specific tasks be performed by different users. For example, you might not want the same person both to acknowledge the receipt of goods and to process payment to the vendor. This concept is named segregation of duties.

Segregation of duties helps you reduce the risk of fraud, and it also helps you detect errors or irregularities. You can also use segregation of duties to enforce internal control policies.

In Microsoft Dynamics AX, when two duties in the same role conflict, or when a user is assigned to two roles that contain conflicting duties, the conflict is logged. The security administrator must approve or reject each assignment that causes a conflict.

For duties that are typically separated, separate sample roles and default duties are included with Microsoft Dynamics AX. By default, no rules are set up for segregation of duties.

Compliance with the rules for segregation of duties is not verified when you create rules. Therefore, you can create a rule that causes existing user role assignments to conflict. You can also create a rule that causes an existing role definition to have a conflict. You must validate compliance manually after you create new rules. For more information about how to identify and resolve conflicts, see [Identify and resolve conflicts in segregation of duties](identify-and-resolve-conflicts-in-segregation-of-duties.md).

Use the following procedure to set up a rule for segregation of duties.

1.  Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Segregation of duties rules**.

2.  Click **New**.

3.  Enter a name for the rule.

4.  Select the first duty that is controlled by the rule.

5.  Select the second duty that is controlled by the rule.

6.  Select the severity of the risk that occurs when the same user or role performs both duties.

7.  Enter a description of the security risk.

8.  Enter a description of the actions that you take to mitigate the security risk. For example, you can mitigate the risk by conducting more detailed reviews of the process, by conducting a monthly managerial review, or by sharing resources with other departments.

## See also

[Role-based security in Microsoft Dynamics AX](role-based-security-in-microsoft-dynamics-ax.md)

  


