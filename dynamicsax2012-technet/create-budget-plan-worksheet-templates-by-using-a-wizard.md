---
title: Create budget plan worksheet templates by using a wizard
TOCTitle: Create budget plan worksheet templates by using a wizard
ms:assetid: 8565d393-81c5-4bfd-96ae-b7693100d5f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507085(v=AX.60)
ms:contentKeyID: 59623136
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create budget plan worksheet templates by using a wizard [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to create a Microsoft Excel template for budget plan worksheets by using a wizard in Microsoft Dynamics AX, and how to decide which fields to use for the worksheet header, which columns to include, and which matrix fields to create. Each template is specific to a legal entity and an account structure.

This feature is available only if cumulative update 7 for Microsoft Dynamics AX 2012 R2 and Office Add-ins for Microsoft Dynamics AX are installed.

Starting with Microsoft Dynamics AX 2012 R2, you can create a budget plan templates manually. For more information, see [Create budget plan templates manually](create-budget-plan-templates-manually.md).

The following illustration shows how to create a template for budget plan worksheets by using a wizard. The numbers correspond to the procedures later in this topic.

![Budget plan template wizard process](images/Dn507085.BudgetPlanTemplateWorksheetWizard(AX.60).gif "Budget plan template wizard process")

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
<td><p>Installation</p></td>
<td><p>Install the Microsoft Office Add-ins component. For more information, see <a href="install-office-add-ins.md">Install Office Add-ins</a>.</p></td>
</tr>
<tr class="even">
<td><p>Application Integration Framework (AIF)</p></td>
<td><p>Initialize AIF. For more information, see <a href="initialization-checklists.md">Initialization checklists</a> and <a href="set-up-application-integration-framework.md">Set up Application Integration Framework</a>.</p>
<p>Activate the <strong>BudgetServices</strong> inbound port. (Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Services and Application Integration Framework</strong> &gt; <strong>Inbound ports</strong>. Select the <strong>BudgetServices</strong> service, and then click <strong>Activate</strong>.) For more information, see <a href="managing-integration-ports.md">Managing integration ports</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Document management</p></td>
<td><p>Activate the <strong>BudgetPlanOfficeAddinService</strong> document data source. (Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Document management</strong> &gt; <strong>Document data sources</strong>. Select the <strong>Budget</strong> module and the <strong>BudgetPlanOfficeAddinService</strong> data source name, and then click <strong>Activate</strong>.) For more information, see <a href="set-up-integration-with-microsoft-office-add-ins.md">Set up integration with Microsoft Office Add-ins</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budgeting setup</p></td>
<td><p>Configure budget planning. For more information, see <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Decide which fields to use for the worksheet header

For the worksheet header, include fields that identify the budget plan that the worksheet template will be used for. Use the following table to help you decide which fields to include.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of worksheet header field</p></th>
<th><p>Considerations</p></th>
<th><p>Examples</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Budget plan identifiers</p></td>
<td><p>Use one or more of these fields to help identify the budget plan for the users of the worksheet template.</p></td>
<td><p><strong>Budget plan</strong></p>
<p><strong>Budget planning process</strong></p>
<p><strong>Budget planning stage</strong></p>
<p><strong>Document number</strong></p>
<p><strong>Document status</strong></p>
<p><strong>Responsibility center</strong></p></td>
</tr>
<tr class="even">
<td><p>Responsible party</p></td>
<td><p>Use this field to identify the person who is responsible for the budget plan.</p></td>
<td><p><strong>Budget plan preparer</strong></p></td>
</tr>
<tr class="odd">
<td><p>Budget plan characteristics</p></td>
<td><p>Use one or more of these fields to track information about the budget plan.</p></td>
<td><p><strong>Budget plan priority</strong></p>
<p><strong>Created by</strong></p>
<p><strong>Created date and time</strong></p>
<p><strong>Is historical</strong></p>
<p><strong>Modified by</strong></p>
<p><strong>Modified date and time</strong></p>
<p><strong>Rank</strong> (Budget plan)</p>
<p><strong>Workflow status</strong></p></td>
</tr>
</tbody>
</table>


## 2\. Decide which columns to include on the worksheet

For the worksheet columns, include fields that represent budget plan lines. Use the following table to help you decide which fields to include.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of worksheet column</p></th>
<th><p>Considerations</p></th>
<th><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Budget plan identifiers</p></td>
<td><p>Use one or more of these fields to identify the budget plan that the budget plan lines are a part of.</p></td>
<td><p>Budget plan name</p>
<p>Document number</p></td>
</tr>
<tr class="even">
<td><p>Budget plan scenario information</p></td>
<td><p>Use one or more of these fields to specify scenario information for the budget plan line.</p></td>
<td><p>Budget plan scenario</p>
<p>Budget plan scenario description</p>
<p>Scenario unit of measure class</p>
<p>Unit of measure</p></td>
</tr>
<tr class="odd">
<td><p>Budget plan line fields</p></td>
<td><p>Use one or more of these fields to specify information about the budget plan line.</p></td>
<td><p>Asset</p>
<p>Budget class</p>
<p>Budget plan estimate type</p>
<p>Comment</p>
<p>Currency</p>
<p>Dimension description</p>
<p>Dimension name</p>
<p>Effective date</p>
<p>Forecast position</p>
<p>Is recurring</p>
<p>New request</p>
<p>Project</p>
<p>Proposed asset</p>
<p>Proposed asset description</p>
<p>Proposed project</p>
<p>Proposed project description</p></td>
</tr>
</tbody>
</table>


## 3\. Decide which matrix fields to create

You can add one or more matrix fields to show totals for groups of related records on the budget plan lines. Examples of matrix fields include the following:

  - Previous year actuals

  - Previous year budgeted

  - Department request Q1

  - Approved budget January

## 4\. Create a template for a budget plan worksheet

To create a budget plan worksheet, follow these steps:

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Select the **Templates** page, and then click the **Wizard** button.

3.  On the first page of the wizard, click **Next \>**.

4.  On the **Define the template parameters** page, enter the following information, and then click **Next \>**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Template name</strong></p></td>
    <td><p>This name is displayed in the header of the worksheet template and is used for the file name of the template.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Attachment folder</strong></p></td>
    <td><p>The template file is stored in this location.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Legal entity</strong></p></td>
    <td><p>Specify the legal entity that will use this template.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account structure</strong></p></td>
    <td><p>Specify the accounting structure to use with this template.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Define the template header fields** page, select the budget plan document headers to use for the template, and then click **Next \>**.

6.  On the **Define the columns for the template** page, select the budget plan fields to use for columns in the template, and then click **Next \>**.

7.  On the **Define the matrix fields for the template** page, click the **Matrix fields** button.

8.  On the **Matrix fields for worksheet templates** page, click **New**, and then enter the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter the name for the matrix field. This field is used as a column name for the calculated amounts column.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>Enter the description for the matrix field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Measure</strong></p></td>
    <td><p>Select whether to use amount, quantity, or price for the calculation.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Read-only</strong></p></td>
    <td><p>Select this check box to prevent the calculated amount from being edited in the Excel template. You might do this for a budget plan template based which budget stage it’s in. For example, if the budget plan is at the manager approval stage, department request amounts should not be changed. Or, you might use this check box for previous year actual and budgeted amounts, which are included in the template for reference.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Filters</strong></p></td>
    <td><p>Select the filters to apply to budget plan lines when the matrix field values are calculated.</p></td>
    </tr>
    </tbody>
    </table>


9.  Repeat step 8 for each matrix field that has to be calculated in the worksheet template.
    
    You can use the **Copy** button to create a new matrix field that is based on an existing matrix field.

10. On the **Define the matrix fields for the template** page, move the matrix fields from the **Available** list to the **Selected** list, and then click **Next \>**.

11. On the **Preview the template** page, review the wizard selections. Navigate back in the wizard to change the selections as needed.

12. Click **Finish** to create the Excel template.

13. Review the worksheet template opened as an Excel file and make adjustments as needed (such as formatting, adding charts, and so on). Save the Excel file after you make changes.
    
    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Do not change the location where the file is stored.</p></td>
    </tr>
    </tbody>
    </table>


## 5\. Select the worksheet template to use for the budget planning process

To select the worksheet template to use for the budget planning process, follow these steps:

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning process**.

2.  Select the budget planning process where the template will be used.

3.  On the **Budget planning stage rules and templates** FastTab, select a budget planning workflow and budget planning stage, and then select the template that you created in the previous procedure.

## 6\. Create a budget plan and review its information by using a worksheet template

After the worksheet template has been created and added to a budget planning process, you can create a budget plan and then export it to an Excel workbook that uses the worksheet template.

To create a budget plan and review its information by using a worksheet template, follow these steps:

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **All budget plans**.

2.  On the **Action Pane**, click **Budget plan** to create a budget plan.

3.  In the **Budget planning process** field, select a process.

4.  In the **Budget plan** field, enter a name for the budget plan.

5.  Click **Create**.

6.  To add lines to the budget plan, click **Add line**. Select the accounting structure, and then enter financial dimension values and the amount for each budget plan line.

7.  In the **Budget plan** form, on the **Action Pane**, click **Worksheet**. A Microsoft Excel file, which is based on the worksheet template that you created in the previous procedure, opens.

## Next step

Work with others in your organization to add budget information to the worksheet in Excel. When you are satisfied with the information that’s in Excel, import the budget plan information back into Microsoft Dynamics AX. For more information, see “Use worksheets and justifications in budget plans” in [Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md).

## Related tasks

[Create budget plan templates manually](create-budget-plan-templates-manually.md)

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
<td><p><strong>Budget control</strong></p>
<p><strong>Budget planning configuration key</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To create a budget plan worksheet template by using a wizard, you must be a member of the <strong>Budget manager</strong> (BudgetBudgetManager) security role.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

