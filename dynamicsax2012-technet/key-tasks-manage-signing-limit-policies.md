---
title: 'Key tasks: Manage signing-limit policies'
TOCTitle: 'Key tasks: Manage signing-limit policies'
ms:assetid: b21300ed-94aa-4894-967b-8344e6ec1f50
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242748(v=AX.60)
ms:contentKeyID: 36059057
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- policies
- policy
- signing limit
- signing limits
- signing-limit
- signing-limits
---

# Key tasks: Manage signing-limit policies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A key element of financial risk management for organizations is managing expenditure. Managing expenditure includes strengthening internal controls and making sure that workers comply with these controls. Signing limits are an important part of expenditure controls and compliance.

## What do you want to do?

Learn more about...

Create a signing limit policy

Define default signing limit rules

Define a limit agreement rule

Define exceptions to a limit agreement rule

Define a limit currency rule

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About signing limit setup](about-signing-limit-setup.md)

## Create a signing limit policy

1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  On the **General** FastTab, enter a name and description for the signing limit policy.

3.  On the **Policy organizations** FastTab, in the **Select organization hierarchy** field, select an organization hierarchy.
    

    > [!NOTE]
    > <P>A policy can apply to nodes in only one organization hierarchy. You cannot add nodes to the policy for one organization hierarchy and the select another organization hierarchy and add nodes from that one.</P>



4.  In the **Available organization nodes:** list, select the organization nodes that the signing limit policy applies to.

The next steps for creating a signing-limit policy are performed on the **Policy rules** FastTab, where you define the rules for the signing limit policy. You can set up rules for the following policy rule types:

  - **Default signing limit**

  - **Limit agreement**

  - **Limit currency**

The following procedures outline how to set up rules for each signing limit policy rule type.

Back to top

## Define default signing limit rules

Default signing limit rules specify the spending and approval limits for each document type and each job or compensation level.


> [!NOTE]
> <P>You specify whether signing limits are based on job or compensation level by using the <STRONG>Signing limit parameters</STRONG> form. For more information, see <A href="set-up-signing-limit-parameters.md">Set up signing limit parameters</A>.</P>



1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  On the **Policy rules** FastTab, in the **Policy rule type:** list, click **Default signing limit**.

3.  Under **Policy rules**, click the **Create policy rule** button.

4.  In the **Default signing limit rule details** form, enter the effective date and expiration date for the default rule, and then click **New**.

5.  For each document type and job or compensation level, specify the default approval and spending limits. You can select multiple jobs or compensation levels when you create a default signing limit amount for a document type. This lets you create a single entry for all jobs or compensation levels that have the same default spending and approval amounts.

Back to top

## Define a limit agreement rule

Limit agreements define the fiduciary responsibilities of the employee when the employee makes corporate purchases or approves expenses for business-related activities. When you create a limit agreement rule, you specify the agreements that the employee must review and accept before they submit a signing limit request.


> [!NOTE]
> <P>Companies create and maintain their purchasing agreements on their corporate intranet or extranet and reference them in Microsoft Dynamics AX as limit agreements. Limit agreements are defined in the <STRONG>Signing limit parameters</STRONG> form. For more information, see <A href="set-up-signing-limit-parameters.md">Set up signing limit parameters</A>.</P>



1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  On the **Policy rules** FastTab, in the **Policy rule type:** list, click **Limit agreement**.

3.  Under **Policy rules**, click the **Create policy rule** button.

4.  In the **Limit agreement rule details** form, enter the effective date and expiration date for the limit agreement rule, and then click the **New** button.

5.  For each document type, select the limit agreements that the worker must read and confirm compliance with.

Back to top

## Define exceptions to a limit agreement rule

Some workers may be granted an exception to the limit agreement rules. For example, your organization requires company executives above compensation level 80 to have specific employment contracts that describe their spending and approval limits. These contracts are in place to meet public disclosure requirements and exist outside the Microsoft Dynamics AX signing limit policy framework. In these cases, the employees can be granted an exception to the review and renewal requirements outlined in the limit agreement rule.

1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  On the **Policy rules** FastTab, in the **Policy rule type:** list, click **Limit agreement**.

3.  Under **Policy rules**, click the **Create policy rule** button.

4.  In the **Limit agreement rule details** form, click **Exceptions**.

5.  In the **Limit agreement exceptions** form, in the **Available jobs** field, select a job or compensation level and then click the **Add \>\>** button. Repeat this step for all jobs or compensation levels that are exempt from the limit agreement rule.

Back to top

## Define a limit currency rule

Assign a base currency to the signing limit rule. This allows an organization to create signing limits that are based on a specific currency.


> [!NOTE]
> <P>The base currency that you define for the signing limit rule may not be the primary currency for the worker who requests the signing limit. To use a limit currency that differs from the primary currency that is defined for the worker, exchange rates must be set up in your system. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh209477(v=ax.60)">Currency exchange rates (form)</A>.</P>



1.  Click **Organization administration** \> **Setup** \> **Signing limits** \> **Signing limit policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  On the **Policy rules** FastTab, in the **Policy rule type:** list, click **Limit currency**.

3.  Under **Policy rules**, click the **Create policy rule** button.

4.  In the **Limit currency rule details** form, enter the effective date and expiration date for the limit currency rule.

5.  If you want the system to consider rules from the parent organization when it searches for applicable policy rules, select the **Include parent rule** check box.

6.  In the **Currency** field, select the currency to display when a worker requests a signing limit.

Back to top

## Find form help

[Signing limit parameters (form)](https://technet.microsoft.com/en-us/library/hh209378\(v=ax.60\))

[Limit currency rule details (form)](https://technet.microsoft.com/en-us/library/hh242800\(v=ax.60\))

[Limit agreement rule details (form)](https://technet.microsoft.com/en-us/library/hh208981\(v=ax.60\))

[Signing limit policy (form)](https://technet.microsoft.com/en-us/library/hh242788\(v=ax.60\))

## Find related tasks

[Set up signing limit parameters](set-up-signing-limit-parameters.md)

[Set up Organization administration workflows](set-up-organization-administration-workflows.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

