---
title: Create budget plan templates manually
TOCTitle: Create budget plan templates manually
ms:assetid: 897f68e4-799b-4e6c-a267-0415ce5c182f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677347(v=AX.60)
ms:contentKeyID: 49384121
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create budget plan templates manually 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create budget plan templates for Microsoft Excel and Microsoft Word. After you create budget plan templates, users can create Excel worksheets and Word justification documents that are linked to the budget plan tables in Microsoft Dynamics AX. For information about how to set up template folders and templates, see [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md). For information about how to work with worksheets and justifications in budget plans, see [Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md).

This feature is available only if Microsoft Dynamics AX 2012 R2 and Office Add-ins for Microsoft Dynamics AX are installed.

Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can create Excel templates for budget plan worksheets by using a wizard in Microsoft Dynamics AX. For more information, see [Create budget plan worksheet templates by using a wizard](create-budget-plan-worksheet-templates-by-using-a-wizard.md).

## Set up data sources for budget plan templates

Before you can create budget plan templates for the first time, you must set up the data sources for the templates.

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document data sources**.

2.  To select a data source for Excel templates, click **New**, and then follow these steps:
    
    1.  In the **Module** field, select **Budget**.
    
    2.  In the **Data source type** field, select **Service**.
    
    3.  In the **Data source name** field, select the name of the service.
    
    4.  Click **Activate**.

3.  To select a data source for Word templates, click **New**, and then follow these steps:
    
    1.  In the **Module** field, select **Budget**.
    
    2.  In the **Data source type** field, select **Query reference**.
    
    3.  In the **Data source name** field, select the name of the query.
    
    4.  Click **Activate**.

## About creating worksheet templates

When you open Excel, the pages in the worksheet template are identified as numbered sheets, such as Sheet1 and Sheet2. Each sheet or page in the worksheet template has a different purpose. The following table describes the sheets in a typical worksheet template.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sheet</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sheet1 (entry page)</p></td>
<td><p>The page that the user sees and works with. This page should have the focus when you close the template file.</p></td>
</tr>
<tr class="even">
<td><p>Sheet2 (backing page)</p></td>
<td><p>A required page that must contain all the required fields, key fields, optional fields, and any fields that are used in the matrix fields but that are not already included. This page can be hidden.</p></td>
</tr>
<tr class="odd">
<td><p>Sheet3 (<strong>Dynamics AX Status</strong> page)</p></td>
<td><p>The page that displays the publishing status and details when information is published back to the budget plan from the worksheet. The details on this page include any errors that occurred.</p></td>
</tr>
</tbody>
</table>


When you create a worksheet from the template, an additional hidden page named **BudgetPlanText** is added to the worksheet to support the budget plan header fields. You can right-click a sheet tab to display the **BudgetPlanText** page.

When you create worksheet templates, consider the following best practices:

  - Focus on the purpose of the template. Make sure that the template shows only the information that users need. For example, one template might show summarized details in one stage for a high-level manager, and another template might show more details in another stage for a budget manager.

  - Use a base template. Build a basic template on a test computer, and make sure that this base template works correctly before you create working versions of it.

  - Use conditional formatting to emphasize the characteristics of the data. For example, you can emphasize important fields by using another color.

  - Manage matrix fields. Many calculations are processed in the background for matrix fields, and these calculations can slow performance. Create all the matrix fields in the base template. Then, in each version of the base template, remove the matrix fields that are not required.
    

    > [!NOTE]
    > <P>A matrix field contains the values that you use to put related records into groups. For more information, see <A href="https://technet.microsoft.com/library/jj677288(v=ax.60)">Using the Office Add-ins API</A>.</P>



  - Microsoft Visual Studio Tools for Office is used to enter, manage, and display the data for Office Add-ins. Use formulas and macros to best use Visual Studio Tools for Office.

### Create a worksheet template

1.  In Excel, on the **Dynamics AX** tab, click **Add data**.

2.  In the **Add data** form, select the data source. Multiple budget plan data sources are displayed. Hold the pointer over a data source to display the name of that data source.

3.  On the **Dynamics AX** tab, click **Fields** to open **Field chooser**.

4.  On the entry page, or Sheet1, select a cell. Then, in **Field chooser**, double-click a field to add that field to the entry page, next to the cell that you selected.

5.  You can add one or more matrix fields to show totals for groups of related records on the budget plan lines. To add a matrix field, follow these steps:
    
    1.  On the entry page, select a cell to provide a location for the matrix field.
    
    2.  In **Field chooser**, right-click **Budget plan lines**, and then select **Create Matrix Field**.
    
    3.  Enter a name for the matrix field.
    
    4.  Select or enter the **Where** conditions for the filter. When you enter the **Where** condition, use **Budget plan lines.Budget plan scenario**, not **Budget plan lines.Budget plan scenario (scenarioName)**.

6.  To add header fields, follow these steps:
    
    1.  On the entry page, select a cell to provide a location for the header field.
    
    2.  In **Field chooser**, double-click the field for the header. For example, to select the **Document number** header field, double-click **Document number** under **Budget plans**.
        
        In **Field chooser**, you can hold the pointer over a field to determine whether it is a header field. For example, when you hold the pointer over the **Document number** field, **BudgetPlanHeader.DocumentNumber** is displayed.
    
    3.  In the cell under the header field in the template, enter the text that was displayed in the previous step. For example, if you selected the **Document number** field, enter BudgetPlanHeader.DocumentNumber.
    
    4.  You can change the caption for the field. For example, you can change Document number to Budget plan number.
    
    5.  Click a worksheet cell to create at least one named cell, which provides support for the header fields in the template. In the **Name box**, enter a name for the cell.

7.  Click the backing page, or Sheet2. Add all the key fields, required fields, and any additional fields that were used on the entry page and in the matrix fields. In **Field chooser**, a red asterisk (\*) is displayed next to the required fields and key fields. Make sure that the following required fields and key fields are included on the backing page:
    
      - **Document number**
    
      - **Parent budget plan.Document number**
    
      - **Scenario.Budget plan scenario**
    
      - **Line number**
    
      - Ledger dimensions that are selected on the entry page
    
      - **Effective date**
    
      - **Amount**
    
      - **Quantity**

8.  Close **Field chooser**.

9.  On the **Dynamics AX** tab, click **Options**, and then select the legal entity and the default account structure.

10. On the **Dynamics AX** tab, click **Refresh** to load and test the data.

11. Click the entry page before you save and close the file. This step guarantees that the entry page is displayed when a user first opens a worksheet from the template.

12. Save the .xlsx file to the folder for budget plan templates. When you configure budget planning, select the template file name and the template folder in the **Templates** area of the **Budget planning configuration** form.

## Create a justification template

1.  In Word, on the **Dynamics AX** tab, click **Add data**.

2.  In the **Add data** form, select the query reference. Hold the pointer over a data source to display the name of that data source.

3.  On the **Dynamics AX** tab, click **Fields**.

4.  Drag fields from **Field chooser** to the template. Include all required fields.

5.  Close **Field chooser**.

6.  On the **Dynamics AX** tab, click **Options**, and then select the legal entity.

7.  On the **Dynamics AX** tab, click **Merge** to load and test the data.

8.  Save the .docx file to the folder for budget plan templates. When you configure budget planning, select the template file name and the template folder in the **Templates** area of the **Budget planning configuration** form.

## See also

[Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md)

  


