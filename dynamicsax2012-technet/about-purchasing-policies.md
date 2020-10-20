---
title: About purchasing policies
TOCTitle: About purchasing policies
ms:assetid: a1a6647e-dabd-4c96-a0e2-2dd5a4e0b54c
ms:mtpsurl: https://technet.microsoft.com/library/Hh209455(v=AX.60)
ms:contentKeyID: 36058791
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About purchasing policies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A purchasing policy is a collection of rules that control the requisition process. Purchasing policies help procurement administrators implement their procurement strategy by creating a policy structure that aligns with the organization’s strategic purchasing needs.


> [!NOTE]
> <P>Purchasing policies are part of a larger policy framework introduced in Microsoft Dynamics AX 2012. For more information, see <A href="https://go.microsoft.com/fwlink/?linkid=213137%26clcid=0x409">Using the Policy Framework in Microsoft Dynamics AX 2012</A>.</P>




> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Rules

A purchasing policy consists of a set of policy rules. When you define a policy rule, you first select a rule type. Then, you create a rule for the rule type by defining the settings, the start date, and the end date for the rule. Rules are at the core of any policy.

For example, an administrator creates a policy, selects the **Catalog policy rule** type, and then adds a catalog policy rule to the policy. This catalog policy rule specifies that the Adventure Catalog must be used for internal procurement. After the purchasing policy is associated with a particular organization, employees of that organization see the Adventure Catalog on the internal procurement site.

## Assigning policies to organizations

Before a policy can take effect, it must be associated with an organization. Purchasing policies are associated with the **Procurement internal control** hierarchy purpose. This means that purchasing policies can only apply to organizations in hierarchies that have the hierarchy purpose of **Procurement internal control**. You can also select organizations from the flat list of legal entities in the CompanyInfo table. These legal entities are designated in the policy framework as “Companies.”

## Determining which rule to apply

Depending on how you configure your purchasing policies, multiple rules can affect users in an organization. The following examples illustrate different ways in which you can configure purchasing policies and specify how policies are applied when a transaction occurs.

## Example 1: Simple purchasing policy configuration

Small and less complex organizations can set up purchasing policies by legal entity, and use only the **Companies** organization hierarchy.

Fabrikam, a small business, has little variance in its purchasing needs across the organization. Purchasing rules vary only among their legal entities. For example, employees of Fabrikam Canada and employees of Fabrikam U.S. purchase goods and services from different catalogs and from different vendors. Fabrikam will set up its purchasing policies at the legal-entity level.

Fabrikam creates two purchasing policies. Policy A applies to their U.S. legal entity 1111. Policy B applies to their Canadian legal entity 2222.

When an employee in the U.S. legal entity 1111 creates a purchase requisition, the policy rules are derived from policy A. For example, the product catalog that the employee sees on the procurement site is the catalog that is specified in the catalog policy rule for policy A. When an employee in the Canadian legal entity 2222 creates a purchase requisition, the policy rules are derived from policy B.


> [!NOTE]
> <P>If an employee of legal entity 1111 purchases an item on behalf of an employee of legal entity 2222, the policy rules specified for legal entity 2222, policy B, are applied.</P>



## Example 2: Complex purchasing policy configuration

In the previous example, all purchasing rules were defined in a single organizational hierarchy, in this case the **Companies** organizational hierarchy. A complex organization may define policies for multiple organizational hierarchies.

Contoso is a large company that requires complex purchasing rules to control the requisition process. They have defined rules for two different organizational hierarchies: the “Department” organizational hierarchy and the “Global purchasing control” organizational hierarchy.

Policy 123 is defined for the “Department” organizational hierarchy for the Sales UK – Sales department. In policy 123, the “Purchase requisition control” rule specifies that restrictions on minimum order quantities must be enforced. In this rule, the **Enforce minimum order quantity restrictions** check box is selected.

Policy 456 is defined for the “Global purchasing control” organizational hierarchy for the Sales and Marketing department. In policy 456, the “Purchase requisition control” rule does not specify that minimum order quantity restrictions must be enforced. In this rule, the **Enforce minimum order quantity restrictions** check box is cleared.

Sam works in the Sales UK – Sales department in Contoso’s United Kingdom office. The policies for the “Department” organizational hierarchy and the “Global purchasing control” organizational hierarchy both apply to his department. When Sam creates a purchase requisition, the system must determine which policy to apply.

The system administrator set up the purchasing policy parameters to specify that purchasing policies must be applied in the following order of precedence:

1.  Global purchasing control

2.  Department

3.  Companies

Therefore, policy 456 is applied to the purchase requisition that Sam creates. No minimum order quantity is required for the purchase requisition.

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the following new purchasing policy rule types are available:

  - **Re-approval rule for purchase orders** – An optional rule that defines the criteria for requiring reapproval when changes are made to a purchase order. For more information, see [Re-approval rule for purchase orders (form)](https://technet.microsoft.com/library/jj680083\(v=ax.60\)).

  - **Requisition purpose rule** – An optional rule that determines the type of requisition purpose allowed for a specific legal entity. Unless it is otherwise indicated in this rule, requisitions will automatically have a purpose of consumption when they are created. For more information about how to control the requisition purposes that are available when a requisition is created for your organization, see [Requisition purpose rule (form)](https://technet.microsoft.com/library/jj677434\(v=ax.60\)).

  - **Replenishment category access policy rule** – An optional rule that determines the products that are available to fulfill requisition demand for a specific legal entity when the requisition purpose is replenishment. For more information, see [Replenishment category access policy rule (form)](https://technet.microsoft.com/library/jj677448\(v=ax.60\)).

  - **Replenishment control rule** – An optional rule that defines the fields on the requisition line that must be entered for the requisition to be submitted for approval when the requisition purpose is replenishment. For more information, see [Replenishment control rule (form)](https://technet.microsoft.com/library/jj677424\(v=ax.60\)).

The **Requisition purpose rule**, **Replenishment category access policy rule**, and **Replenishment control rule** apply to the new concept of a requisition purpose in Microsoft Dynamics AX 2012 R2, specifically the replenishment requisition purpose. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign one of two purposes to it: consumption or replenishment. If your organization does not require requisitions that have a purpose of replenishment, these three new policy rule types are not applicable. The default purpose in Microsoft Dynamics AX 2012 R2 is consumption. This is equivalent to a purchase requisition in earlier versions of Microsoft Dynamics AX, where the replenishment purpose was not available. For more information about requisition purposes and how they affect the requisition process, see [About purchase requisitions](about-purchase-requisitions.md).

## See also

[Set up policy parameters](set-up-policy-parameters.md)

[Key tasks: Create purchasing policies](key-tasks-create-purchasing-policies.md)

  


