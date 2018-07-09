---
title: Premium earning setup tasks
TOCTitle: Premium earning setup tasks
ms:assetid: caae8bcc-6b43-44c3-8e1c-f730c7a497aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876709(v=AX.60)
ms:contentKeyID: 63385355
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- Overtime
- Forms.SysPolicyListPage
- Forms.SysPolicy
- Payroll
- Menu_Items.Display.PayrollPremiumEarningGenerationRuleType
- Premium earning code
- Fair Labor Standards Act
- FLSA
- Regular rate of pay
- Forms.PayrollPremiumEarningCode
- Forms.PayrollPremiumEarningGenerationPolicy
- Overtime adjustment
- Premium code
- Premium earnings
- Overtime premium
- Overtime premiums
- Premium earning codes
- Premium codes
- Premium earning policy
- Premium earning policies
- Premium pay
- Premium policies
- Premium policy
- Shift differential
- Shift differentials
---

# Premium earning setup tasks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the tasks related to setting up premium earnings.

Premium earnings are extra earnings that are paid to workers when specified conditions are met. For example, your organization might offer annual bonuses, overtime premiums, a differential for hours worked on the second or third shift, or additional pay to workers who hold a certificate for advanced training or qualifications.

To set up and pay simple premiums, such as annual bonuses, all you need to do is create an earning code for the premium and add it to earnings statements when it’s time to pay the premium. For more information, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md) or [Earning code examples](earning-code-examples.md).

Other premiums are based on other earnings or on characteristics of the worker or position. This topic explains how to set up the more complex types of premiums that are provided for in Microsoft Dynamics AX.

**Premiums based on earning codes**

These premiums are used for shift differentials and similar premiums that should be paid any time that specified earning codes are included on an earnings statement. These premiums require this information to be set up:

  - A premium earning policy. Most often, an organization has a single premium earning policy that is shared by all legal entities.

  - Policy rule types to define the document and query parameters that are used when you develop specific policy rules.

  - An earning code group that contains all earning codes that qualify for the premium.

  - An earning code that uses a rate basis of **Percent of earnings** or **Hours of earnings** to calculate and pay the premium amount.

  - Policy rules that specify the earning codes that must be present on the earnings statement for the premium earning to be generated.

  - Premium codes to link the policy rule type that specifies the rules for the premium and the earning code that specifies how to calculate the premium.

**Premiums based on characteristics of the worker or position**

These premiums are used to provide additional pay based on characteristics of the worker or position, such as certificates for advanced training or positions that are based in certain locations. These premiums require this information to be set up:

  - A premium earning policy. Most often, an organization has a single premium earning policy that is shared by all legal entities.

  - Policy rule types to define the document and query parameters that are used when you develop specific policy rules.

  - An earning code that uses a rate basis of **Flat amount** to pay the premium amount.

  - Policy rules that specify the conditions that must be true for the premium earning to be generated.

  - Premium codes to link the policy rule type that specifies the rules for the premium and the earning code that specifies how to calculate the premium.


> [!TIP]
> <P>A premium can be based on a combination of earning codes and the worker or position. If that occurs, follow the instructions for setting up a premium based on earning codes. In the policy rules, include all earning codes that must be present and all conditions that must be true for the premium earning to be generated.</P>



**Regular rate of pay premiums**

These premiums are most often used for overtime earnings that are paid in addition to the base earnings. This includes any adjustments that are required by the Fair Labor Standards Act (FLSA). These premiums require this information to be set up:

  - Work cycles and work periods.

  - An earning code group that contains all earning codes for all nondiscretionary earnings.

  - Earning codes that use a rate basis of **Regular rate of pay** to calculate and pay the premium amount.

A single earning code group can be shared by all earning codes that are used to calculate FLSA overtime premiums.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Organization hierarchy purposes</p></td>
<td><p>In the <strong>Organization hierarchy purposes</strong> form, <strong>Legal entity</strong> must be selected as the only allowed organization type for premium earnings.</p></td>
</tr>
<tr class="even">
<td><p>Policy parameters</p></td>
<td><p>In the <strong>Policy parameters</strong> form, <strong>Companies</strong> must be added to the <strong>Order of precedence</strong> list.</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p>Complete the basic setup of Payroll before you set up premiums. For an overview of the basic setup process, see <a href="setting-up-payroll-basic-topics.md">Setting up payroll: Basic topics</a>.</p>
<p>Note that work cycles and work periods are required for regular-rate-of-pay premiums. For more information, see <a href="work-cycle-and-work-period-tasks.md">Work cycle and work period tasks</a>.</p></td>
</tr>
</tbody>
</table>


## Define premium earning policies

Each legal entity that pays premium earnings based on earning codes or on characteristics of the worker or position must be assigned to a premium earning policy. You can create one policy that is shared by all legal entities, or you can create a separate policy for each legal entity. You can also use a combined approach.


> [!TIP]
> <P>You usually don’t have to do anything to maintain a premium earning policy after you create it. You manage the premiums that your organization pays by maintaining the policy rules and earning codes.</P>



To define premium earning policies, follow these steps:

1.  Click **Payroll \> Setup \> Earnings \> Premium earning policies**.

2.  On the **Action Pane**, in the **New** group, click **Policy** to create a premium earning policy.

3.  On the **General** FastTab, enter a name and description for the premium earning policy.

4.  On the **Policy organizations** FastTab, the organization nodes that have been created for the selected organization type are shown in the **Available organization nodes:** list. For premium earning policies, each node represents a legal entity. Select the legal entities that will use this premium earning policy, and then click **Add \>\>** to move those legal entities to the **Selected organization nodes:** list.

5.  If other legal entities require separate policies, create the additional policies that your organization needs.

Later in this process, you will define policy rule types and create policy rules for this policy. The policy rules specify the conditions that must be true for the premium to be paid. The policy rule types are used on the premium codes to connect the policy rules together with the earning codes that are used to calculate the premium amount.


> [!TIP]
> <P>You can’t delete policies or policy rules, but you can retire them so that they are no longer used. When you retire a policy, you also retire all the corresponding policy rules for that policy.</P>
> <P>You can’t reactivate a retired policy. You can reactivate a retired policy rule by changing the effective dates on the rule.</P>



## Set up premiums that are based on earning codes

These premiums are used for shift differentials and similar premiums that should be paid any time that specified earning codes are included on an earnings statement.

To set up premiums that are based on earning codes, follow these steps:

1.  Review the earning codes that you created during the basic Payroll setup process to make sure that all earning codes that qualify for premiums have been created.
    
    **Example**
    
    You pay a premium for hours worked on the second shift. Earnings for the first shift and the second shift are identical, but only the hours on the second shift qualify for the premium. You must have a separate earning code for first-shift and second-shift earnings to correctly apply the premium.
    
    If necessary, create additional earning codes before you go on to the next step. Be sure to add these earning codes to the earning code group that was created for regular-rate-of-pay premiums.

2.  Identify the different premiums that your organization pays and that are based on other earnings. For example, you might pay a differential for work on the second and third shifts. The premium might differ for union and non-union workers. In that situation, you would need four different earning codes to calculate and pay these premiums.

3.  Create a premium policy rule type for each premium that you identified in the previous step. Policy rule types define the document and query parameters that are used when you develop specific policy rules.
    
    To create a premium policy rule type for a premium, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium earning policy rule types**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the policy rule type. For example, for a second shift differential, you might enter 2nd Shift and Second shift differential.
    
    4.  In the **Query name** field, select **Premium earnings**. This is the default Application Object Tree (AOT) query to use as the starting point to develop policy rules for this policy rule type.
    
    5.  Create any additional policy rule types that your organization needs, and then close the form.

4.  Set up the earning code groups that are used to identify earnings that qualify for the premium. To do so, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Earning code groups**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the earning code group. For example, you might enter 2nd shift differential and All 2nd shift earnings.
    
    4.  Click **Add** and select an earning code.
        
        Repeat this step until you have added all the earning codes that qualify for the premium.
    
    5.  Create any additional earning code groups to correctly identify the earnings for all your premiums based on earnings. An earning code group can be used by more than one premium. For example, if you have different shift differentials for union and non-union workers, those premiums would most likely use the same earning code group.
    
    6.  When you have created all the earning code groups you need, close the form.

5.  Create an earning code to calculate and pay the premium amounts for each premium that is based on other earnings.
    
    These earning codes use a rate basis of **Percent of earnings** when the premium is defined as a percentage of the eligible earning amount. They use a rate basis of **Hours of earnings** when the premium is defined as an amount per hour. For more information, see [Earning code examples](earning-code-examples.md).

6.  Set up policy rules for premium earnings.
    
    A policy rule consists of a database query that is run against source documents. It specifies the conditions that must be true for the premium to be paid. The policy rule types are used on premium codes to connect the policy rules together with the earning codes that are used to calculate the premium amount.
    
    A policy rule that is used to generate premium earnings for workers might be called a premium earning rule.
    
    You usually create one policy rule for each policy rule type that you create.
    
    To set up policy rules for premium earnings, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium earning policies**.
    
    2.  Double-click the policy to create policy rules for.
    
    3.  On the **Policy rules** FastTab, select the policy rule type to develop a policy rule for, and then click **Create policy rule**.
        
        Each policy rule specifies an earning code that must be present on an earnings statement for the associated premium earning to be generated.
    
    4.  In the **Effective date** and **Expiration date** fields, enter the date range when this policy rule is effective. If you don’t enter values in these fields, the policy rule is effective when it is created and it never expires.
        

        > [!TIP]
        > <P>If you know that the requirements for the premium earning will change in the future, you can create future-dated versions of the rule in addition to the current version.</P>

    
    5.  Use the expression builder to add a line for each earning code that qualifies for the premium earning.
        
        If there are other conditions that must be met in addition to the earning code, add a line for each condition that must be true to pay the premium.
    
    6.  Create as many additional policy rules as you need, and then close the form.

7.  Set up premium codes.
    
    Premium codes contain the information that is required to generate premium earnings. They link the policy rule type that specifies the rules for the premium and the earning code that specifies how to calculate the premium.
    
    To set up premium codes, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium codes**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the premium code. It is a good idea to use the same name and description that you used for the policy rule type. For example, for the second shift differential, you could enter 2nd Shift and Second shift differential.
    
    4.  Specify values for the fields on the **General** tab. These field values define which rule triggers this premium, which earning code to use, whether to create earnings based on earning lines or the earning statement, and which calculation frequency to use:
        
          - Select the payroll calculation frequency that includes the pay periods that this premium code should be used in. Premium earnings are generated only in the pay periods that are included in the payroll calculation frequency that you select. For example, certain premium earnings might be generated only in the first pay period of each month.
        
          - Select the policy rule type that determines whether to create earnings statement lines for this premium code. For example, select 2nd Shift.
        
          - In the **Payout basis** field, select **Earnings statement**.
            

            > [!WARNING]
            > <P>The earning code that is used to pay the premium aggregates hours and earnings to determine the line total. If you select <STRONG>Earning line</STRONG>, the aggregate line is created one time for each earning code that is in the <STRONG>Basis earning code group</STRONG>. This results in significantly overstated earnings.</P>

        
          - In the **Earning code** field, select the earning code that is used to pay the premium. This earning code appears on the premium lines that are added to earnings statements.
        
          - On the **Active interval** tab, click **New**, and then enter the first and last dates that the premium code can be used.
            

            > [!IMPORTANT]
            > <P>Active intervals can’t overlap. Therefore, if an existing interval for the selected premium code is active on the date a new interval takes effect, the existing interval is automatically expired on that date. In the same way, if you change the date when an existing interval starts or ends, any existing intervals that are active during the new interval are expired to prevent the intervals from overlapping.</P>

    
    5.  Repeat these steps to create as many premium codes as you need.

## Set up premiums based on characteristics of the worker or position

These premiums are used when workers are entitled to extra pay because of characteristics related to the worker or position.

To set up premiums based on characteristics of the worker or position, follow these steps:

1.  Identify the premiums that your organization pays and that are based on characteristics of the worker or position. For example, many organizations pay a premium to workers who hold advanced certifications.

2.  Create a premium policy rule type for each premium that you identified in the previous step. Policy rule types define the document and query parameters that are used when you develop specific policy rules.
    
    To create a premium policy rule type for a premium, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium earning policy rule types**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the policy rule type. For example, you might enter Certification premium and Licenses and certificates.
    
    4.  In the **Query name** field, select **Premium earnings**. This is the default AOT query to use as the starting point to develop policy rules for this policy rule type.
    
    5.  Create any additional policy rule types that your organization needs, and then close the form.

3.  Create an earning code to pay the premium amounts for each premium that is based on characteristics of the worker or position.
    
    These earning codes use a rate basis of **Flat amount**. For more information, see [Earning code examples](earning-code-examples.md).

4.  Set up policy rules for your premium earnings.
    
    A policy rule consists of a database query that is run against source documents. It specifies the conditions that must be true for the premium to be paid. The policy rule types are used on premium codes to connect the policy rules together with the earning codes that are used to calculate the premium amount.
    
    A policy rule that is used to generate premium earnings for workers might be called a premium earning rule.
    
    You usually create one policy rule for each policy rule type that you create.
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium earning policies**.
    
    2.  Double-click the policy to create policy rules for.
    
    3.  On the **Policy rules** FastTab, select the policy rule type to develop a policy rule for, and then click **Create policy rule**.
        
        Each policy rule specifies a characteristic of the worker or position that must be true for the associated premium earning to be generated.
    
    4.  In the **Effective date** and **Expiration date** fields, enter the date range when this policy rule is effective. If you don’t enter values in these fields, the policy rule is effective when it is created and it never expires.
        

        > [!TIP]
        > <P>If you know that the requirements for the premium earning will change in the future, you can create future-dated versions of the rule in addition to the current version.</P>

    
    5.  Use the expression builder to add a line for each condition that must be true to pay the premium.
    
    6.  Create as many additional policy rules as you need, and then close the form.

5.  Set up premium codes.
    
    Premium codes contain the information that is required to generate premium earnings. They link the policy rule type that specifies the rules for the premium and the earning code that specifies how to calculate the premium.
    
    To set up premium codes, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Premium codes**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the premium code. It is a good idea to use the same name and description that you used for the policy rule type. For example, for the second shift differential, you could enter Certification premium and Licenses and certificates.
    
    4.  Specify values for the fields on the **General** tab, These field values define which rule triggers this premium, which earning code to use, whether to create earnings based on earning lines or the earning statement, and which calculation frequency to use:
        
          - Select the payroll calculation frequency that includes the pay periods that this premium code should be used in. Premium earnings are generated only in the pay periods that are included in the payroll calculation frequency that you select. For example, certain premium earnings might be generated only on the first pay period of each month.
        
          - Select the policy rule type that determines whether to create earnings statement lines for this premium code. For example, select certification premium.
        
          - In the **Payout basis** field, select how the premium is paid:
            
              - To add one premium line for each earnings statement line that qualifies for the premium, select **Earning line**.
            
              - To add one premium line for each earnings statement that qualifies for the premium, select **Earnings statement**.
        
          - In the **Earning code** field, select the earning code that is used to pay the premium. This earning code appears on the premium lines that are added to earnings statements.
        
          - On the **Active interval** tab, click **New**, and then enter the first and last dates that the premium code can be used.
            

            > [!IMPORTANT]
            > <P>Active intervals can’t overlap. Therefore, if an existing interval for the selected premium code is active on the date a new interval takes effect, the existing interval is automatically expired on that date. In the same way, if you change the date when an existing interval starts or ends, any existing intervals that are active during the new interval are expired to prevent the intervals from overlapping.</P>

    
    5.  Repeat these steps to create as many premium codes as you need.

## Set up regular-rate-of-pay premiums

Regular-rate-of-pay premiums are most often used for overtime earnings that are paid in addition to the base earning rate. This includes any adjustments that are required by the Fair Labor Standards Act (FLSA).

To set up regular-rate-of-pay premiums, follow these steps:

1.  Review the earning codes that you created during the basic payroll setup process to make sure that all earning codes that are required for nondiscretionary earnings have been created.

2.  Make sure that work cycles and work periods have been set up. For more information, see [Work cycle and work period tasks](work-cycle-and-work-period-tasks.md).

3.  Identify the different overtime earnings that your organization pays. For example, your organization might pay both time-and-a-half and double-time for overtime hours worked on first, second, and third shifts. That combination would require six earning codes to correctly calculate and pay all overtime premiums. Union contracts, location differentials, or other factors also might require additional earning codes.

4.  Set up the earning code group for nondiscretionary earnings. To do so, follow these steps:
    
    1.  Click **Payroll \> Setup \> Earnings \> Earning code groups**.
    
    2.  Click **New**.
    
    3.  Enter a name and a brief description of the earning code group. For example, you might enter FLSA earnings and All nondiscretionary earnings.
    
    4.  Click **Add**, and then select an earning code.
        
        Repeat this step until you have added all the earning codes for nondiscretionary earnings.
        

        > [!WARNING]
        > <P>If any earning codes for nondiscretionary earnings are omitted from this earning code group, the overtime premium won’t be calculated correctly.</P>

    
    5.  Close the form.

5.  Create an earning code to calculate and pay the premium amounts for each type of overtime earnings that you identified.
    
    These earning codes all use a rate basis of **Regular rate of pay**. For more information, see [Earning code examples](earning-code-examples.md).

## Related tasks

[Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Payroll - USA</strong></p>
<div class="alert">

> [!IMPORTANT]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up premium earnings, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Inquire into compensation process</strong> (HcmCompensationInquire)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
<li><p><strong>Review organizational information</strong> (HcmOrganizationalReview)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up premium earnings, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain earning codes</strong> (PayrollEarningCodeMaintain)</p></li>
<li><p><strong>Maintain payroll earning code groups</strong> (PayrollEarningCodeGroupMaintain)</p></li>
<li><p><strong>Maintain premium earnings setup</strong> (PayrollPremiumEarningSetupMaintain)</p></li>
<li><p><strong>Maintain premium earning policy</strong> (PayrollPremiumGenerationPolicyMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

