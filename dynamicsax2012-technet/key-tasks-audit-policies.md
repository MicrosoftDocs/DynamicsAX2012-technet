---
title: 'Key tasks: Audit policies'
TOCTitle: 'Key tasks: Audit policies'
ms:assetid: 6f34aced-dcd8-43ab-9d0f-763f8c5e2b7a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242643(v=AX.60)
ms:contentKeyID: 36058043
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- audit policy
- auditing
- audit
- audits
- auditing policy
---

# Key tasks: Audit policies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Audit policies help you implement the compliance strategy for your organization. This topic explains how to create audit policies, audit policy rule types, and policy rules. It also explains how to modify or retire an audit policy.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## What do you want to do?

Learn more about...

Prepare to create audit policies

Create audit policy rule types

Define an audit policy

Develop policy rules

Modify an audit policy

Retire an audit policy

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About audit policy rules](about-audit-policy-rules.md)

[About audit policy violations and cases](about-audit-policy-violations-and-cases.md)

## Prepare to create audit policies

Before you can create an audit policy, you must define the policy parameters that are used by all audit policies.

1.  Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.

2.  On the **Action Pane**, click **Parameters** to open the **Policy parameters** form.

3.  The available organization types are displayed in the **Organization types:** list. Select the organization types to create policies for, and then click the **Add** button.
    

    > [!NOTE]
    > <P>Although you must select at least one organization type to use audit policies, you do not have to change the order of precedence for those organization types. When an audit policy is run, all rules in that policy are run. The system does not select which audit policy rules to run based on the order of precedence. For more information about the order of precedence for policies, see <A href="organizations-and-organizational-hierarchies.md">Organizations and organizational hierarchies</A>.</P>



Back to top

## Create audit policy rule types

Policy rule types define the document and query parameters that are used when you develop specific policy rules.

1.  Click **Compliance and internal controls** \> **Setup** \> **Audit** \> **Policy rule type**.

2.  Click **New** to create an audit policy rule type.

3.  Enter a name and a brief description of the policy rule type.

4.  In the **Query name** field, select the default Application Object Tree (AOT) query to use as the starting point for developing policy rules for this policy rule type. The query indicates the source document that the policy rule type is defined for. For more information about query names, see [Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\)).

5.  In the **Query type** field, select the type of database query that users can build when they create audit policy rules by using this policy rule type. For more information about query types, see [Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\)).

6.  In the **Document date reference** field, select the field in the source document that identifies the date to use when documents are selected for audit.

7.  Create any additional policy rule types that your organization needs, and then close the form.

Back to top

## Define an audit policy

Before you can define an audit policy, you must create the policy rule types that define the document and query parameters for the policy rules. You must also make sure that the policy parameters have been set up appropriately.

1.  Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.

2.  On the **Action Pane**, click **Policy** to create an audit policy.

3.  On the **General** FastTab, enter a name and description for the audit policy.

4.  On the **Action Pane**, click **Additional options**, and then follow these steps:
    
    1.  Enter the starting date and ending date of the document selection date range. This range determines which version of a policy rule to use, based on the effective dates of the policy rule. It also determines which organization nodes were associated with the policy during that date range. For more information, see [Additional options (form)](https://technet.microsoft.com/en-us/library/hh227519\(v=ax.60\)).
    
    2.  Each audit policy is run in batch mode. To verify or change the parameters for the batch job, click the **Batch** button.
    
    3.  In Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 R2:
        
          - If you are creating a policy rule that uses the **List search** query type to evaluate source documents for specific entities, enter the entities on the **Monitored entity** FastTab. In cumulative update 6 for Microsoft Dynamics AX 2012 R2, specify the monitored entities in the **Audit policy rule** form.
        
          - If you are creating a policy rule that uses the **Keyword search** query type to evaluate source documents to determine whether they contain certain words, enter the words on the **Prohibited words** FastTab. In cumulative update 6 for Microsoft Dynamics AX 2012 R2, specify the prohibited words in the **Audit policy rule** form.
    
    4.  Click **Close** to return to the **Audit policy** form.

5.  On the **Policy organizations** FastTab, select the organization type that the audit policy applies to.
    

    > [!TIP]
    > <P>A single policy can apply to only one organization type.</P>



6.  The organization nodes that have been created for the selected organization type are shown in the **Available organization nodes:** list. Select the nodes that are affected by this audit policy, and then click the **Add \>\>** button to move those organization nodes to the **Selected organization nodes:** list.
    

    > [!IMPORTANT]
    > <P>The association of the organization node and the audit policy is effective from the date and time that you add the organization node to the <STRONG>Selected organization nodes:</STRONG> list. The association expires when you remove the organization node from the list. Policy rules cannot be tested for any dates on which no organization node is associated with the policy.</P>



7.  On the **Policy rules** FastTab, develop the policy rules that are needed for this policy. For more information, see the “Develop policy rules” procedure.

Back to top

## Develop policy rules

An audit policy rule consists of a database query that is run against source documents. The policy rule types define the document and query parameters that are used when you develop policy rules.

1.  Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.

2.  Double-click the policy to create policy rules for.

3.  On the **Policy rules** FastTab, select the policy rule type to develop a policy rule for, and then click **Create policy rule**. The fields that are displayed in the **Audit policy rule** form depend on the selected policy rule type and its associated query.

4.  In the **Effective date** and **Expiration date** fields, enter the date range when this policy rule is effective. If you do not enter values in these fields, the policy rule is effective when it is created, and it never expires.

5.  Complete other fields as required, depending on the query type that is associated with the policy rule type.
    
    In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2:
    
      - If you are creating a policy rule that uses the **List search** query type to evaluate source documents for specific entities, enter the entities on the **Monitored entity** FastTab.
    
      - If you are creating a policy rule that uses the **Keyword search** query type to evaluate source documents to determine whether they contain certain words, enter the words on the **Prohibited words** FastTab.

6.  Click **Select** to open a query form.
    
    This button is not available for policy rules that are based on the **List search** or **Keyword search** query type.

7.  Use the query form to specify the criteria to use for this policy rule, and then click **OK**. The fields that were set up by default in the policy rule form also are set up in the query form.
    

    > [!IMPORTANT]
    > <P>If the data tables that are used in the query are shared among different legal entities, set the <STRONG>AllowCrossCompany</STRONG> property on the AOT query to <STRONG>Yes</STRONG>. This enables the policy engine to query on that table when the legal entity that is running the policy differs from the legal entity that the resulting query records belong to.</P>



8.  After the policy rule is set up, click **Test**. Enter the document selection date range to use for the test.
    

    > [!NOTE]
    > <P>The dates that you enter in this form are used only for the test. They are not saved, and they do not affect the document selection date range that is defined in the <STRONG>Additional options</STRONG> form.</P>



9.  Click **Run test**.
    
    Review the results of the test. If the results are not what you expected, modify the database query, and repeat the test.
    

    > [!IMPORTANT]
    > <P>If you do not receive results, do the following:</P>
    > <UL>
    > <LI>
    > <P>Verify that an organization node was associated with the policy during the data selection date range that you specified for the test. Policy rules cannot be tested for any dates on which no organization node is associated with the policy.</P>
    > <LI>
    > <P>Verify that source document records exist that were created on or after the policy was created. Records that existed before the policy was created cannot be audited. The only exception is for policy rules that are based on the <STRONG>Duplicate</STRONG> query type, which can audit records up to 180 days in the past.</P></LI></UL>



Back to top

## Modify an audit policy

Audit policies help you implement your organization's compliance strategy. As your organization grows or your audit policies become more complex, you might have to modify these policies. For example, if your organization has acquired another organization, you might want to add that organization to an existing audit policy. To do so, add the organization to the **Selected organization nodes:** list on the **Policy organizations** FastTab of the **Audit policy** form.

1.  Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.

2.  Double-click the policy to modify.

3.  On the **Policy organizations** FastTab, the organization nodes that are affected by this policy are shown in the **Selected organization nodes:** list. The organization nodes that can be assigned to the policy are shown in the **Available organization nodes:** list. Click the **Add \>\>** or **\<\< Remove** button to move the organization nodes to the appropriate list.

4.  On the **Policy rules** FastTab, you can modify any policy rules that belong to this audit policy. To select the policy rule to modify, select the policy rule type to display the list of policy rules that are associated with that type, and then select the policy rule.
    
      - To change the expiration date of a policy rule, click **Change date**, and then enter the new expiration date.
    
      - To retire a policy rule, click **Retire policy rule**. Policy rules are not deleted and can be reactivated at any time by changing the effective dates on the rule.
    
      - To change a policy rule, double-click the rule to open it, and then make the changes.

Back to top

## Retire an audit policy

There might come a time when you no longer need a specific audit policy. Although you cannot delete a policy, you can retire it so that it is no longer used. When you retire a policy, you also retire all the corresponding policy rules for that policy.


> [!IMPORTANT]
> <P>A retired policy cannot be reactivated.</P>



1.  Click **Compliance and internal controls** \> **Common** \> **Policies** \> **Audit policies**.

2.  Select the policy to retire.

3.  On the **Action Pane**, click **Retire policy**.

Back to top

## Find form help

[Additional options (form)](https://technet.microsoft.com/en-us/library/hh227519\(v=ax.60\))

[Audit policies (list page)](https://technet.microsoft.com/en-us/library/hh208610\(v=ax.60\))

[Audit policy (form)](https://technet.microsoft.com/en-us/library/hh242790\(v=ax.60\))

[Audit policy rule (form)](https://technet.microsoft.com/en-us/library/hh209490\(v=ax.60\))

[Policy rule type (form)](https://technet.microsoft.com/en-us/library/hh208562\(v=ax.60\))

[Policy parameters (form)](https://technet.microsoft.com/en-us/library/hh209114\(v=ax.60\))

## Find related tasks

[Set up policy parameters](set-up-policy-parameters.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

