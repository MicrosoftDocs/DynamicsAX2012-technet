---
title: 'Key tasks: Create purchasing policies'
TOCTitle: 'Key tasks: Create purchasing policies'
ms:assetid: dade94d0-0e46-4d9d-a78f-6c3a14d4bf49
ms:mtpsurl: https://technet.microsoft.com/library/Hh227404(v=AX.60)
ms:contentKeyID: 36059662
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- procurement
- purchasing policies
- purchasing policy
audience: Application User
ms.search.region: Global
---

# Key tasks: Create purchasing policies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Purchasing policies are business rules that you define to help control the procure-to-pay process and enforce your overall procurement business strategy. You can view a list of your purchasing policies on the **Purchasing policies** list page. Information on the list page includes the name, description, and status (active or retired) of each policy.

## What do you want to do?

Learn more about...

Create a purchasing policy

Modify a purchasing policy

Retire a purchasing policy

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About purchasing policies](about-purchasing-policies.md)

## Create a purchasing policy

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  On the **Action Pane**, in the **New** group, click **Policy**.

3.  In the **Purchasing policy** form, on the **General** FastTab, enter a name and description for the purchasing policy.

4.  On the **Policy organizations** FastTab, select the organization that this purchasing policy applies to.
    

    > [!NOTE]
    > <P>A single purchasing policy can apply to only one organization hierarchy. For example, you create two organization hierarchies which are assigned the purpose of <STRONG>Procurement internal control</STRONG>. One is called “Geographic” and another is called “Department.” When you create a purchasing policy you can only reference one of the two organization hierarchies. For more information, see <A href="about-purchasing-policies.md">About purchasing policies</A>.</P>



5.  On the **Policy rules** FastTab, select the **Policy rule type:**, and click the **Create policy rule** button to create individual rules. Specify the effective date and expiration date for each rule. Repeat this step for each policy rule type.
    
    Effective dates and expiration dates for rules in a rule type cannot overlap. Only one rule at a time can be in effect for a policy rule type.
    

    > [!NOTE]
    > <P>Effective and expiration dates are handled differently for the <STRONG>Spending thresholds by category</STRONG> policy rule. This policy rule is available only for public sector entities in France. For more information, see <A href="fra-set-up-a-policy-rule-for-spending-thresholds-by-category-public-sector.md">(FRA) Set up a policy rule for spending thresholds by category (Public sector)</A>.</P>



Back to top

## Modify a purchasing policy

As your organization grows or your purchasing policies become more complex, you can update your policies. For example, you might want to update a purchasing policy to apply to a company that your company acquires.

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  Open the purchasing policy that you want to modify.

3.  To add more organizations to your existing policy, on the **Policy organizations** tab, select an organization in the **Available organization nodes:** box, and then click the **Add \>\>** button to move it to the **Selected organization nodes:** box.

4.  To change a rule for the policy, on the **Policy rules** FastTab, modify any of the specific policy rules that belong to this purchasing policy.
    

    > [!NOTE]
    > <P>If the expiration date for a rule is set to December 31, 2154 you can only change the expiration date for the policy rule. Change the expiration date to a date prior to December 31, 2154 to edit the policy rule details.</P>



Back to top

## Retire a purchasing policy

When you retire a purchasing policy, you also retire all of the rules for that policy.

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  On the **Purchasing policies** list page, select the purchasing policy that you want to retire.

3.  Under **Policy rules**, click **Retire policy**.

Back to top

## Find form help

[Purchasing policy (form)](https://technet.microsoft.com/library/hh209627\(v=ax.60\))

[Policy parameters (form)](https://technet.microsoft.com/library/hh209114\(v=ax.60\))

## Find related tasks

[Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md)

  


