---
title: Set up policy parameters
TOCTitle: Set up policy parameters
ms:assetid: c70691a0-73db-4410-b832-558e99f56676
ms:mtpsurl: https://technet.microsoft.com/library/Hh242846(v=AX.60)
ms:contentKeyID: 36059310
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up policy parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Policies are internal business controls that you create to enforce business rules that you have outlined for your business. You can create various types of policies, such as audit, purchasing, and expense policies. Before you can create any policies, you must set up the policy parameters for the selected policy type. For example, before you can create purchasing policies, you must set up the purchasing policy parameters.

Policy parameters define the order in which policies are resolved in Microsoft Dynamics AX. For example, when a worker goes to the shopping site on the Employee services portal, the catalog that is displayed is determined by the purchasing policy that is assigned to the worker. If three purchasing policies might apply to the worker, the policy parameters help determine which rule is applied and, ultimately, which catalog the worker sees on the site. Each policy type has its own policy parameters, and therefore, the order of precedence for resolving policies can be different for each type of policy.


> [!IMPORTANT]
> <P>Organizations can have multiple layers. You might have legal entities, cost centers, regions, departments, and other organizational units, which must be defined before they can be identified as an organization type. After the organizations are defined, you can set up the order of precedence for the policies. For more information, see <A href="organizations-and-organizational-hierarchies.md">Organizations and organizational hierarchies</A>.</P>



## What do you want to do?

Learn more about...

Set up policy precedence rules

Override policy precedence rules by rule type

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About purchasing policies](about-purchasing-policies.md)

[About audit policy rules](about-audit-policy-rules.md)

[About audit policy violations and cases](about-audit-policy-violations-and-cases.md)

## Set up policy precedence rules

1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Travel and expense** \> **Setup** \> **Policies** \> **Expense report**. On the **Action Pane** click **Parameters**.
    
    \-or-
    
    Click **Travel and expense** \> **Setup** \> **Policies** \> **Travel requisition**. On the **Action Pane** click **Parameters**.

2.  The organization types that you created are displayed in the **Organization types:** field. Select the organization types to make policies for, and then click **Add \>\>**.
    
    For example, if you have organization types of legal entity, region, department, and cost center, but you only have policy variances for legal entities, departments, and cost centers, you only select legal entity, department, and cost center.

3.  Select the organization type to list first, and then click the **Move up** button until the organization type is at the top of the list.
    

    > [!NOTE]
    > <P>When you set up audit policies, you must select at least one organization type, but you do not have to change the order of precedence for those organization types. When an audit policy is run, all rules in that policy are run, regardless of the order of precedence that you define.</P>



4.  Repeat these steps until the order of the organization types meets your needs.

Back to top

## Override policy precedence rules by rule type

You define the order of precedence for policy resolution at the policy level. However, for some policy types, you can override the order of precedence for individual policy rule types.

For example, you defined the precedence for purchasing policies in this order: cost center, department, legal entity. However, for the catalog policy rule, you want the order of precedence to be in this order: department, cost center, legal entity. You change the order of precedence for only the Catalog policy rule. When a user accesses the shopping cart in the Employee services portal, the catalog that is displayed is determined by the policies that are associated with the worker’s department, then their cost center, then their legal entity.


> [!WARNING]
> <P>Audit policies and vendor invoice policies do not allow you to override the order of precedence rules by policy rule type. For information about how to set up policy rule types for audit policies, see <A href="key-tasks-audit-policies.md">Key tasks: Audit policies</A>. For information about how to set up policy rule types for vendor invoice policies, see <A href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</A>.</P>



1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**. On the **Action Pane**, click **Parameters**.
    
    \-or-
    
    Click **Travel and expense** \> **Setup** \> **Policies** \> **Expense report**. On the **Action Pane** click **Parameters**.
    
    \-or-
    
    Click **Travel and expense** \> **Setup** \> **Policies** \> **Travel requisition**. On the **Action Pane** click **Parameters**.
    
    The policy rule types for the selected policy type are displayed in the **Policy rule type:** area.
    
    The order of precedence for resolving the policy rule type is displayed in the **Order of precedence:** area.

2.  To change the order of resolution, move the organization types up or down in the **Order of precedence:** field.

Back to top

## Find form help

[Audit policy (form)](https://technet.microsoft.com/library/hh242790\(v=ax.60\))

[Vendor invoice policy (form)](https://technet.microsoft.com/library/hh209409\(v=ax.60\))

[Signing limit policy (form)](https://technet.microsoft.com/library/hh242788\(v=ax.60\))

[Purchasing policy (form)](https://technet.microsoft.com/library/hh209627\(v=ax.60\))

[Expense policies (form)](https://technet.microsoft.com/library/hh208982\(v=ax.60\))

  


