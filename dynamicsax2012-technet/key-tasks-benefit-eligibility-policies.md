---
title: 'Key tasks: Benefit eligibility policies'
TOCTitle: 'Key tasks: Benefit eligibility policies'
ms:assetid: 7c5cdb65-4ccd-4ec8-94f4-0a2077f749cb
ms:mtpsurl: https://technet.microsoft.com/library/JJ677345(v=AX.60)
ms:contentKeyID: 49384119
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- policies
- policy
- benefits
- benefit eligibility
- eligibility
audience: Application User
ms.search.region: Global
---

# Key tasks: Benefit eligibility policies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Benefits eligibility policies let you define and exercise eligibility rules for each benefit your organization offers to workers. These rules allow you to identify the specific benefits that a given worker is eligible for.

## What do you want to do?

Prepare to create benefit eligibility policies

Create benefit eligibility policy rule types

Define a benefit eligibility policy

Develop policy rules

Modify a benefit eligibility policy

Retire a benefit eligibility policy

Find form help

Find related tasks

## Prepare to create benefit eligibility policies

Before you can create a benefit eligibility policy, you must first define the policy parameters that will be used by all benefit eligibility policies.

1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility**.

2.  On the **Action Pane**, click **Parameters** to open the **Policy parameters** form.

3.  The only organization type available for use with benefit eligibility policies is **Company**. In the **Organization types:** list, select **Company** and then click the **Add** button.

Back to top

## Create benefit eligibility policy rule types

Policy rule types define the document and query parameters that are used when you develop specific policy rules.

1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility policy rule types**.

2.  Click **New** to create a benefit eligibility policy rule type.

3.  Enter a name and a brief description of the policy rule type.

4.  In the **Query name** field, select the default Application Object Tree (AOT) query to use as the starting point to develop policy rules for this policy rule type. The query indicates the source document that the policy rule type is defined for.
    
    For information about query names, see [Policy rule type (form)](https://technet.microsoft.com/library/hh208562\(v=ax.60\)).

5.  Create any additional policy rule types that your organization needs, and then close the form.

Back to top

## Define a benefit eligibility policy

Before you can define a benefit eligibility policy, you must create the policy rule types that will define the document and query parameters for the policy rules. You must also make sure that the policy parameters have been set up appropriately.

1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility**.

2.  On the Action Pane, in the **New** group, click **Policy** to create a benefit eligibility policy.

3.  On the **General** FastTab, enter a name and description for the benefit eligibility policy.

4.  On the **Policy organizations** FastTab, select an organization hierarchy. This is the organization hierarchy that the benefit eligibility policy will apply to.
    

    > [!TIP]
    > <P>A single policy can apply to only one organization type.</P>



5.  The organization nodes that have been created for the selected organization type are shown in the **Available organization nodes:** list. Select the nodes to be affected by this benefit eligibility policy, and then click the **Add \>\>** button to move those organization nodes to the **Selected organization nodes:** list.

6.  On the **Policy rules** FastTab, develop the policy rules that are needed for this policy. For more information, see the next procedure.

Back to top

## Develop policy rules

A policy rule consists of a database query that is run against source documents. The policy rule types define the document and query parameters that are used when you develop policy rules. A policy rule that is used to determine worker eligibility for benefits is sometimes called a benefit eligibility rule.

1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility**.

2.  Double-click the policy to create policy rules for.

3.  On the **Policy rules** FastTab, select the policy rule type to develop a policy rule for, and then click **Create policy rule**.

4.  In the **Effective date** and **Expiration date** fields, enter the date range when this policy rule is effective. If you do not enter values in these fields, the policy rule will be effective when it is created, and it will never expire.

5.  Use the expression builder to define the conditions that will be used to evaluate worker records and determine whether the worker is eligible for benefits. For example, you can specify that **Worker employment**. **Worker type** must be **Employee**, or that **Position detail**. **Title** must be **Manager**.

Back to top

## Modify a benefit eligibility policy

Benefit eligibility policies help you implement your organization’s compensation strategy. As your organization grows or your benefit eligibility policies become more complex, you might have to modify these policies. For example, if your organization has acquired another organization, you might want to add that organization to an existing policy. To do so, add the organization to the **Selected organization nodes:** list on the **Policy organizations** FastTab of the **Benefit eligibility** policy form.

1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility**.

2.  Double-click the policy to modify.

3.  On the **Policy organizations** FastTab, the organization nodes that are affected by this policy are shown in the **Selected organization nodes:** list. The organization nodes that can be assigned to the policy are shown in the **Available organization nodes:** list. Click the **Add \>\>** or **\<\< Remove** buttons to move the organization nodes to the appropriate list.

4.  On the **Policy rules** FastTab, you can modify any of the policy rules that belong to this policy. To select the policy rule to modify, select the policy rule type to display the list of policy rules that are associated with that type, and then select the policy rule.
    
      - To change the expiration date of a policy rule, click **Change date** and enter the new expiration date.
    
      - To retire a policy rule, click **Retire policy rule**. Policy rules are not deleted and can be reactivated at any time by changing the effective dates on the rule.
    
      - To change a policy rule, double-click the rule to open it, and then make the changes.

Back to top

## Retire a benefit eligibility policy

There might come a time when you no longer need a specific benefit eligibility policy. Although you cannot delete a policy, you can retire it so that it is no longer used. When you retire a policy, you also retire all of the corresponding policy rules for that policy.


> [!IMPORTANT]
> <P>A retired policy cannot be reactivated.</P>



1.  Click **Human resources** \> **Setup** \> **Policies** \> **Benefit eligibility**.

2.  Select the policy to retire.

3.  On the **Action Pane**, click **Retire policy**.

Back to top

## Find form help

[Benefit eligibility policy (form)](https://technet.microsoft.com/library/jj680909\(v=ax.60\))

[Benefit eligibility rules (form)](https://technet.microsoft.com/library/jj680906\(v=ax.60\))

[Policy rule type (form)](https://technet.microsoft.com/library/hh208562\(v=ax.60\))

## Find related tasks

[Key tasks: Determine benefit eligibility](key-tasks-determine-benefit-eligibility.md)

  


