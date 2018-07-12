---
title: 'Key tasks: Vendor invoice policies'
TOCTitle: 'Key tasks: Vendor invoice policies'
ms:assetid: cece6b77-79c6-43d1-9970-413da5f82465
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242911(v=AX.60)
ms:contentKeyID: 36059472
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- policies
- invoices
- vendors
- policy
- vendor invoice policy
audience: Application User
ms.search.region: Global
---

# Key tasks: Vendor invoice policies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendor invoice policies let you evaluate vendor invoices for compliance with policy rules that you create.

Vendor invoice policies are run when you post a vendor invoice by using the **Vendor invoice** form and when you open the vendor invoice **Policy violations** form. You can also configure the vendor invoice workflow to run vendor invoice policies every time that you submit an invoice to workflow.


> [!IMPORTANT]
> <UL>
> <LI>
> <P>Vendor invoice policies do not apply to invoices that were created in the invoice register or invoice journal.</P>
> <LI>
> <P>Invoice matching validation does not use vendor invoice policies, but is instead set up in the <STRONG>Accounts payable parameters</STRONG> form. This includes invoice totals matching, charges tolerances, and price and quantity matching. For more information, see <A href="about-accounts-payable-invoice-matching.md">About Accounts payable invoice matching</A>.</P></LI></UL>



## What do you want to do?

Learn more about...

Prepare to create vendor invoice policies

Create policy rule types for vendor invoices

Define a vendor invoice policy

Develop policy rules

Modify a vendor invoice policy

Retire a vendor invoice policy

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Handle policy rule violations](handle-policy-rule-violations.md)

## Prepare to create vendor invoice policies

Before you can create a vendor invoice policy, you must first enable invoice matching validation and define the policy parameters for vendor invoices.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.
    
    In the **Invoice validation** area, select the **Enable invoice matching validation** check box.

2.  In the **Post invoice with discrepancies** field, select how to handle invoices that have policy violations.
    
      - If you are using workflow, select **Allow with warning**. This allows for invoices that have policy violations to be posted.
    
      - If you are not using workflow, select **Require approval**. This prevents invoices that have policy violations from being posted.

3.  Close the form.

4.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**.

5.  On the Action Pane, click **Parameters** to open the **Policy parameters** form.
    
    The available organization types are displayed in the **Organization types:** list. Select the organization types to make policies for. Click the **Add** button.

6.  The policy framework will resolve vendor invoice policy rules starting with the first organization type that is listed in the **Order of precedence:** list. Select the organization type to be listed first and then click the **Move up** button until the organization type is listed first in the list. Continue moving organization types up and down in the list until the order of the organization types meets your needs.
    

    > [!NOTE]
    > <P>Regardless of priority, invoices will be validated against all valid vendor invoice policy rules.</P>



Back to top

## Create policy rule types for vendor invoices

Policy rule types define the document and query parameters that are used when you develop specific policy rules.

1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policy rule types**.

2.  Click **New** to create a vendor invoice policy rule type.

3.  Enter a name and a brief description of the policy rule type.

4.  In the **Query name** field, select the default Application Object Tree (AOT) query to use as the starting point for developing policy rules for this policy rule type. The query indicates the source document that the policy rule type is defined for.
    
    For information about query names, see [Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\)).

5.  Create any additional policy rule types that your organization needs, and then close the form.

Back to top

## Define a vendor invoice policy

Before you can define a vendor invoice policy, you must create the policy rule types that will define the document and query parameters for the policy rules. You must also make sure that the policy parameters have been set up appropriately.

1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**.

2.  On the Action Pane, click **Policy** to create a vendor invoice policy.

3.  On the **General** FastTab, enter a name and description for the vendor invoice policy.

4.  On the **Policy organizations** FastTab, select an organization type. This is the organization type that the vendor invoice policy will apply to.
    

    > [!TIP]
    > <P>A single policy can apply to only one organization type.</P>



5.  The organization nodes that have been created for the selected organization type are shown in the **Available organization nodes:** list. Select the nodes to be affected by this vendor invoice policy and then click the **Add \>\>** button to move those organization nodes to the **Selected organization nodes:** list.

6.  On the **Policy rules** FastTab, develop the policy rules that are needed for this policy. For more information, see the next procedure.

Back to top

## Develop policy rules

A vendor invoice policy rule consists of a database query that is run against source documents. The policy rule types define the document and query parameters that are used when you develop policy rules.

1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**.

2.  Double-click the policy to create policy rules for.

3.  On the **Policy rules** FastTab, select the policy rule type to develop a policy rule for, and then click **Create policy rule**. The fields that are displayed in the **Policy rules** form depend on the selected policy rule type and its associated query.

4.  Click **Select** to open a query form. Use this form to specify the criteria to use for this policy rule, and then click **OK**. The fields that were set up by default on the policy rule form will also be set up in the query form.

5.  In the **Effective date** and **Expiration date** fields, enter the date range when this policy rule is effective. If you do not enter values in these fields, the policy rule will be effective when it is created, and it will never expire.

6.  In the **Policy rule description** field, enter an explanation of the policy rule violation or a description of the policy rule to display to users when a policy rule violation occurs.
    
    To enter translations of this message, click the **Translate** icon button.

Back to top

## Modify a vendor invoice policy

Vendor invoice policies help you implement your organization’s business strategy. As your organization grows or your vendor invoice policies become more complex, you might have to modify these policies. For example, if your organization has acquired another organization, you might want to add that organization to an existing vendor invoice policy. To do so, add the organization to the **Selected organization nodes:** list on the **Policy organizations** FastTab of the **Vendor invoice policy** form.

1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**.

2.  Double-click the policy to modify.

3.  On the **Policy organizations** FastTab, the organization nodes that are affected by this policy are shown in the **Selected organization nodes:** list. The organization nodes that can be assigned to the policy are shown in the **Available organization nodes:** list. Click the **Add \>\>** or **\<\< Remove** buttons to move the organization nodes to the appropriate list.

4.  On the **Policy rules** FastTab, you can modify any of the policy rules that belong to this purchasing policy. To select the policy rule to modify, select the policy rule type to display the list of policy rules that are associated with that type, and then select the policy rule.
    
      - To change the expiration date of a policy rule, click **Change date** and enter the new expiration date.
    
      - To retire a policy rule, click **Retire policy rule**. Policy rules are not deleted and can be reactivated at any time by changing the effective dates on the rule.
    
      - To change a policy rule, double-click the rule to open it, and then make the changes.

Back to top

## Retire a vendor invoice policy

There might come a time when you no longer need a specific vendor invoice policy. Although you cannot delete a policy, you can retire it so that it is no longer used. When you retire a policy, you also retire all of the corresponding policy rules for that policy.


> [!IMPORTANT]
> <P>A retired policy cannot be reactivated.</P>



1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice policies**.

2.  Select the policy to retire.

3.  On the Action Pane, click **Retire policy**.

Back to top

## Find form help

[Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\))

[Vendor invoice policies (list page)](https://technet.microsoft.com/en-us/library/hh209411\(v=ax.60\))

[Vendor invoice policy (form)](https://technet.microsoft.com/en-us/library/hh209409\(v=ax.60\))

[Policy rule: Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209566\(v=ax.60\))

[Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\))

[Policy parameters (form)](https://technet.microsoft.com/en-us/library/hh209114\(v=ax.60\))

## Find related tasks

[Set up policy parameters](set-up-policy-parameters.md)

[Handle policy rule violations](handle-policy-rule-violations.md)

  


