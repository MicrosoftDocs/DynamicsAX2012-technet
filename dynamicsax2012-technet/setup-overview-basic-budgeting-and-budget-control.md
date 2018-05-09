---
title: 'Setup overview: basic budgeting and budget control'
TOCTitle: 'Setup overview: basic budgeting and budget control'
ms:assetid: 0c8ccfa4-c583-40b4-ac5f-c11c0112cd4a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242128(v=AX.60)
ms:contentKeyID: 36055999
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- basic budgeting
- budget configuration key
- budget control configuration
- budget control configuration key
- configuring budget control
- public sector configuration key
---

# Setup overview: basic budgeting and budget control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains information that will help you get ready to set up basic budgeting and budget control.

If you’re in the public sector and use general budget reservations, see also [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>




> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



## Budgeting configuration keys

Budgeting includes three primary configuration keys.

  - The **Budget** configuration key enables basic budgeting. Basic budgeting includes financial dimensions that are defined for budgeting, budget register entries, and Budgeting workflows.

  - The **Budget control** configuration key adds budget control to basic budgeting. Budget control includes the following features:
    
      - Budget types for pre-encumbrances and encumbrances
    
      - Budget checking for source documents and accounting journals
    
      - Over budget permissions for user groups
    
      - Budget funds available calculation
    
      - Additional features such as financial dimensions that are defined for budget control

  - The **Public Sector** configuration key adds two budget types to basic budgeting that are used by public sector organizations: the **Preliminary budget** and **Apportionments** budget types.


> [!NOTE]
> <P>Other configuration keys might implement additional budgeting features and features that are related to budgeting requirements in specific countries/regions.</P>



To use budget control, you must set up basic budgeting. If you are using the public sector configuration, you set it up at the same time as you set up basic budgeting.

The following sections describe the information that you need to gather before you set up basic budgeting and budget control. These sections also contain links to topics that you can view for additional details.

## Basic budgeting or budget control

Before you set up basic budgeting or budget control, gather the information described in the following table. For more information, see [About basic budgeting and budget control setup](about-basic-budgeting-and-budget-control-setup.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Information</p></th>
<th><p>Additional details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The financial dimensions and main accounts that will be used for budgeting and that can have amounts transferred either to or from them.</p></td>
<td><p>For more information, see <a href="define-financial-dimensions-for-budgeting.md">Define financial dimensions for Budgeting</a>.</p></td>
</tr>
<tr class="even">
<td><p>The currency exchange rates that must be defined and what those exchange rates are.</p></td>
<td><p>For more information, see <a href="define-budget-exchange-rates.md">Define budget exchange rates</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The budget codes that must be set up for each budget type and the code that you want to use as the default budget code.</p></td>
<td><p>At least one budget code is required for each budget type that you want to use.</p>
<p>For more information, see <a href="define-budget-codes.md">Define budget codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>The budget register entries that will use workflows.</p></td>
<td><p>You assign workflows to budget codes. The budget register entries that are associated with a budget code that has an assigned workflow are automatically submitted to workflow.</p>
<p>For more information, see <a href="create-budget-register-entries.md">Create budget register entries</a> and <a href="set-up-budgeting-workflows.md">Set up Budgeting workflows</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The name of each budget model.</p></td>
<td><p>For more information, see <a href="create-budget-models.md">Create budget models</a>.</p></td>
</tr>
<tr class="even">
<td><p>How the budget cycles will be set up.</p></td>
<td><p>For more information, see <a href="define-budget-cycles.md">Define budget cycles</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The amounts that will be allocated across periods or to other financial dimension values.</p></td>
<td><p>You can use a budget register entry to allocate a yearly budget amount across budget periods, or to allocate budget amounts to financial dimension values.</p>
<p>For more information, see <a href="create-budget-register-entries.md">Create budget register entries</a>.</p></td>
</tr>
<tr class="even">
<td><p>The financial dimensions that will have recurring amounts.</p></td>
<td><p>You can use a recurring budget account entry to copy an amount to multiple periods for recurring expenses, such as rent.</p>
<p>For more information, see <a href="create-budget-register-entries.md">Create budget register entries</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The budget models that will be used in cash flow forecasts.</p></td>
<td><p>For more information, see <a href="create-budget-models.md">Create budget models</a>.</p></td>
</tr>
</tbody>
</table>


## Budget control only

If you use budget control, gather the information in the following table in addition to the information in the previous section. For more information, see [About basic budgeting and budget control setup](about-basic-budgeting-and-budget-control-setup.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Information</p></th>
<th><p>Additional details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The financial dimensions that should be included in budget control rules.</p></td>
<td><p>For more information, see “Define budget control parameters” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
<tr class="even">
<td><p>The user groups that can post entries that exceed the remaining balance for a budget.</p></td>
<td><p>For more information, see “Define over-budget permissions for user groups” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The source documents and accounting journals that you want to configure for budget checking.</p></td>
<td><p>For more information, see “Select source documents for budget control” and “Select accounting journals for budget control” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
<tr class="even">
<td><p>The financial dimensions and accounts that must have a budget threshold, and what that threshold is.</p></td>
<td><p>A budget threshold is the level of budget usage at which you can prevent posting or display warnings. For example, if the threshold is 80, you can warn a user during entry that 80 percent of the budget for the selected account has been used.</p>
<p>For more information, see “Define budget control parameters” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The formula for calculating the remaining balance of a budget.</p></td>
<td><p>The <strong>Budget funds available</strong> calculation can be defined for each legal entity instead of always using the following calculation: Original budget - Actual expenses.</p>
<p>For more information, see “Define the calculation that determines the budget funds that are available” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
<tr class="even">
<td><p>The interval, such as monthly, quarterly, or yearly, that is used to determine whether the available budget balance is sufficient to cover transactions.</p></td>
<td><p>For more information, see “Define budget control parameters” in <a href="set-up-budget-control.md">Set up budget control</a>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

