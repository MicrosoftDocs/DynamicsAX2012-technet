---
title: Set up budget control
TOCTitle: Set up budget control
ms:assetid: 65bd8e59-8c0f-40b7-864a-2c30035bcd0b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242453(v=AX.60)
ms:contentKeyID: 36057748
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- source documents
- budget control
- accounting journals
- activate budget control
- budget funds available calculation
- budget control parameters
- budget control rules
- over-budget permissions
- message levels for user groups
- calculation for budget funds available
- configure budget control
- main accounts
- budget models and budget cycles
- parameters for budget control
- budget groups
- user groups
---

# Set up budget control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Budget control is available for source documents and accounting journals. Source documents include purchase requisitions, purchase orders, vendor invoices, travel requisitions, and expense reports. Accounting journals include daily journals, allocation journals, project expense journals, and fixed asset journals. Depending on how you configure budget control, source documents and accounting journals can be prevented from additional processing when a budget check indicates that the budgeted amounts are not available.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



Set up basic budgeting before you configure budget control. For more information, see [About basic budgeting](about-basic-budgeting.md). If you plan to use Budgeting workflows, create the workflows and assign them to budget codes when you set up basic budgeting. For more information, see [Set up Budgeting workflows](set-up-budgeting-workflows.md). Set up the budget control configuration before you start submitting budget register entries.


> [!NOTE]
> <P>The budget control configuration provides an active version and a draft version. You can modify the draft version when the active version is turned on and budget control is in effect. You can click <STRONG>Restore from active</STRONG> at any time when you are working in a draft version. However, if you click <STRONG>Restore from active</STRONG>, all changes to the draft version are lost. If the budget control configuration is active, you must click <STRONG>Edit</STRONG> to modify the budget control configuration.</P>



## Define budget control parameters

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Select an account structure. If you have multiple active account structures in the chart of accounts, select the account structure that will be used for profit and loss or expense accounts. This account structure includes the main account range for expense accounts.
    
    After you select an account structure, all the financial dimensions in that account structure that were defined for budgeting are displayed in the **Budget dimensions** list.

3.  Select a financial dimension and move it to the **Budget control dimensions** list.
    
    You select the financial dimensions for budget control from the financial dimensions that you defined for budgeting. This lets you develop budgets at one level and configure budget control at another level. For example, you could select the main account, department, and cost center financial dimensions for budgeting, and then select only the department and cost center dimensions for budget control. You can also use budget control rules to specify financial dimension combinations for budget control. For more information, see the “Define budget control rules” section in this topic.

4.  Select a budget control interval, such as **Fiscal year** or **Fiscal year to date**.
    
    The budget control interval works with the budget cycle to determine how amounts are aggregated for budget checking. For example if you select **Fiscal year**, all the funds for the fiscal year are aggregated for budget checking. If you select **Fiscal year to date** or **Budget to date**, the ending date is determined from the fiscal period and the accounting date of the source document or accounting journal that is being checked.

5.  Select the budget cycle time span, which defines the length of the budget cycle. For more information, see [Define budget cycles](define-budget-cycles.md).

6.  Select a budget manager, which is a user who can approve budget workflows. Another budget manager can be defined by using a budget control rule.

7.  In the **Budget threshold** field, enter the percentage of the budget that can be spent.
    
    The threshold can be used to provide warning messages or to define budget permissions to prevent specific user groups from exceeding the budget threshold. This threshold can exceed 100 percent.

8.  Select the **Display a message when exceeding budget threshold** check box to display messages when the budget threshold is exceeded.

## Define over-budget permissions for user groups

You can let specific user groups exceed the available budget or restrict user groups from exceeding the available budget or budget thresholds. The **Prevent processing at over budget threshold** setting is applied to all users who are not in a user group. The settings in this form can be overridden by a budget control rule or budget group.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Over budget permissions**.

3.  Click **Add** and select a user group.
    

    > [!NOTE]
    > <P>If you do not have user groups defined, right-click in the <STRONG>Group</STRONG> field and select <STRONG>View details</STRONG> to open the <STRONG>User groups</STRONG> form, where you can create groups and add users.</P>



4.  In the **Over budget options** field, select the appropriate option for this user group.
    
      - **Prevent over budget processing** – Users in this group cannot process a budget register entry if the available budget balance is insufficient to cover the entry.
    
      - **Allow over budget processing** – Users in this group can process a budget register entry if the available budget balance is insufficient to cover the entry.
    
      - **Prevent processing at over budget threshold** – Users in this group cannot process a budget register entry if the financial dimension or main account will exceed its specified threshold to cover the entry.
    

    > [!NOTE]
    > <P>If the budget threshold is greater than 100 percent, the <STRONG>Prevent processing at over budget threshold</STRONG> setting is less restrictive than <STRONG>Prevent over budget processing</STRONG>.</P>



## Define the calculation that determines the budget funds that are available

In the **Budget funds available** area, you can select check boxes to determine the amounts that are added to and subtracted from the budget funds that are available. **Original budget** and **Actual expenditures** are selected by default, so that the default calculation is Budget funds available = Original budget - Actual expenditures. The budget funds calculation is displayed under the check boxes, so that you can view how the calculation changes as you select and clear the check boxes.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Budget funds available**.

3.  Select the **Include carry-forward amounts** check box to include amounts that are carried forward as part of a purchase order year-end process, and also to carry forward budget register entries that have a budget type of **Carry-forward budget**.
    
    As part of the purchase order year-end process, budget amounts from open purchase orders can be carried forward into the next fiscal year. Any budget reservations for encumbrances are also carried forward. When invoices are recorded against the purchase orders that were carried forward, budget control treats the actual expenditures as carry-forward amounts, also. Therefore, inquiries and reports can display those amounts separately from the amounts that were not carried forward.

4.  You can select the following check boxes to include amounts in the calculation.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Amounts that will be included in the calculation</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Original budget</strong></p></td>
    <td><p>Original budget register entries that have a document status of <strong>Completed</strong>. Also included are the <strong>Project</strong>, <strong>Fixed assets</strong>, <strong>Demand forecast</strong>, and <strong>Supply forecast</strong> budget types that have a document status of <strong>Completed</strong>, which are treated as original budget amounts after they are transferred from other modules.</p>
    <p>The sum of the amounts of budget register entries that have budget types of <strong>Original budget</strong>, <strong>Revision</strong>, <strong>Transfer</strong>, <strong>Carry-forward budget</strong>, <strong>Project</strong>, <strong>Fixed assets</strong>, <strong>Demand forecast</strong>, and <strong>Supply forecast</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Preliminary budget</strong></p></td>
    <td><p>Preliminary budget register entries that have a document status of <strong>Completed</strong>. These are used to create a preliminary budget when the actual budget is being reviewed and approved.</p>
    <div>

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Budget revisions</strong></p></td>
    <td><p>Budget register entries that add changes to original budgets and that have a document status of <strong>Completed</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Draft budget revisions</strong></p></td>
    <td><p>Budget register entries that add changes to original budgets and that have a document status of <strong>Draft</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Budget transfers</strong></p></td>
    <td><p>Budget register entries that transfer budget amounts from one financial dimension value to another and that have a document status of <strong>Completed</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Draft budget transfers in</strong></p></td>
    <td><p>Transfer budget register entries that increase the budget and that have a document status of <strong>Draft</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Draft budget transfers out</strong></p></td>
    <td><p>Transfer budget register entries that decrease the budget and that have a document status of <strong>Draft</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Budget apportionments</strong></p></td>
    <td><p>Budget register entries that have a document status of <strong>Completed</strong>. Apportionments are used in the public sector to show the difference between budgeted amounts and the amounts that are approved for spending. For example, a public sector organization might have an original budget of 10,000.00 for an account and use an apportionment to approve 5000 for spending. Only the amount that is apportioned can be spent.</p>
    <div>

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Actual expenditures</strong></p></td>
    <td><p>Actual expenditures that are recorded in the general ledger from expense reports, vendor invoices, and accounting journals. The amounts from the source documents or accounting journals are included in the budget check only when the source document or accounting journal is enabled for budget control.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Unposted actual expenditures</strong></p></td>
    <td><p>Actual expenditures that are not yet recorded in the general ledger from expense reports, vendor invoices, and accounting journals. The amounts from the source documents or accounting journals are included in the budget check only when the source document or accounting journal is enabled for budget control.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Budget reservations for encumbrances</strong></p></td>
    <td><p>Budget reservations that are created for confirmed purchase orders, general budget reservations, or travel requests, and budget register entries that have a document status of <strong>Completed</strong> and use the <strong>Encumbrance</strong> budget type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Budget reservations for unconfirmed encumbrances</strong></p></td>
    <td><p>Budget reservations that are created for unconfirmed purchase orders, general budget reservations, or travel requests, and budget register entries that have a document status of <strong>Draft</strong> use the <strong>Encumbrance</strong> budget type. These are manual budget reservations that are not yet included in the overall budget balance.</p>
    <div>

    > [!NOTE]
    > <P>If you do not select this check box, budget checks can still be performed on draft source documents, such as purchase orders, general budget reservations, and travel requests. However, the amount of the budget reservation is not included in the budget check for subsequent source documents. You can do this to perform a budget check on draft documents without creating a committed reservation.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reduction to budget reservations for unconfirmed encumbrances</strong></p></td>
    <td><p>Amounts that reduce the amounts that are reserved for unconfirmed obligations to pay. Since a correction to a purchase order can be reverted, this option is intended to prevent a reduction in a budget reservation amount because of a correction to a purchase order until the correction is confirmed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Budget reservations for pre-encumbrances</strong></p></td>
    <td><p>Budget reservations that are created for approved and confirmed purchase requisitions, and budget register entries that have a status of <strong>Completed</strong> and use the <strong>Pre-encumbrance</strong> budget type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Budget reservations for unconfirmed pre-encumbrances</strong></p></td>
    <td><p>Budget reservations that are created for unconfirmed and unapproved purchase requisitions, and budget register entries that have a status of <strong>Draft</strong> and use the <strong>Pre-encumbrance</strong> budget type. These manual budget reservations are created through budget register entries but are not included in the overall budget balance.</p>
    <div>

    > [!NOTE]
    > <P>If you do not select this check box, budget checks can still be performed on draft purchase requisitions. However, the amount of the budget reservation is not included in the budget check for subsequent source documents. You can do this to perform a budget check on draft documents without creating a committed reservation.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


## Select source documents for budget control

In the **Select source documents** area, you can select check boxes to determine the source documents that are subject to budget control. You can also select check boxes to enable budget checks as the lines for source documents are entered and saved.

You should match the source documents that you select with the check boxes that you selected for the budget funds available calculation in the **Budget funds available** area. For example, if you selected **Budget reservations for encumbrances** to be included in the budget funds available calculation, you might want to select the **Purchase orders** check box. When a budget check is performed for the amounts and accounts on a purchase line, the budget control category that is assigned to the reservation is **Encumbrance**.


> [!NOTE]
> <P>A budget check is performed when a source document is created but not when it is edited. A budget check is performed when a source document is submitted to workflow and when it is approved and confirmed.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Select source documents**.

3.  Select the **Purchase requisitions** check box. The **Purchase orders** and **Vendor invoices** check boxes are automatically selected.
    
    If you do not select the **Purchase requisitions** check box and you instead select the **Purchase orders** check box, the **Vendor invoices** check box is automatically selected.
    
    You can select **Vendor invoices**, **Travel requisitions**, and **Expense reports** independently of the other source documents.
    

    > [!NOTE]
    > <P>When you select <STRONG>Vendor invoices</STRONG>, invoice journals, invoice approval journals, and invoice register journals are also enabled for budget control.</P>



4.  Optional: If you are in the public sector and will be using general budget reservations, select the **General budget reservations** check box. For more information, see [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).
    

    > [!NOTE]
    > <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



5.  For each source document, you can select the **Enable budget control for line item on entry** check box to enable budget checking for each line as the line is entered and saved.
    

    > [!NOTE]
    > <P>When a purchase requisition is converted to a purchase order, a budget check is performed, even when line-level checking is not enabled. This relieves the pre-encumbrance and establishes the draft encumbrance. When an invoice is created from a purchase order, a budget check is performed, even when line-level checking is not enabled.</P>



## Select accounting journals for budget control

In the **Select accounting journals** area, you can select check boxes to determine the accounting journals that are subject to budget control. In addition, you can select check boxes to enable budget checks as the lines for accounting journals are entered and saved.


> [!NOTE]
> <P>A budget check is performed when an accounting journal is created but not when it is edited. A budget check is performed when an accounting journal is submitted to workflow and when it is approved and posted.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Select accounting journals**.

3.  Select any of the following check boxes to enable budget control for accounting journals:
    
      - **Daily journals**
    
      - **Allocation journals**
    
      - **Project expense journals**
    
      - **Fixed asset journals**

4.  For each accounting journal, you select the **Enable budget control for line item on entry** check box enable budget checking for each line as the line is entered and saved.

## Assign budget models to budget cycles

You can assign a budget model to a budget cycle to perform budget checking for the budget cycle. Only one budget model can be in use for a budget cycle. A budget check is performed when the accounting date for a source document or accounting journal that is enabled for budge control is in the budget cycle.


> [!NOTE]
> <P>The budget cycle must be defined before you associate the budget cycle with a budget model. In the <STRONG>Assign budget models</STRONG> area, you can click the <STRONG>Budget models</STRONG> link to open the <STRONG>Budget model</STRONG> form, and you can click the <STRONG>Budget cycle time spans</STRONG> link to open the <STRONG>Budget cycle time spans</STRONG> form.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Assign budget models**.

3.  Click **Add** and select a budget cycle time span.

4.  Select a budget cycle.

5.  Select a budget model. Only budget models that do not contain submodels are available for budget control.


> [!NOTE]
> <P>The budget cycle that is being used for budget control can also be determined by the budget cycle time span that is selected for a budget control rule.</P>



## Define budget control rules

Budget control rules are required for budget control. They determine the financial dimension value combinations for budget control. If you selected the department and cost center financial dimensions for budget control, you can define rules for specific combinations of departments and cost centers that are subject to budget control. For example, you could specify **Department = Sales** and **Cost Center = \*,** where **\*** is a wildcard character that will include any cost center.


> [!NOTE]
> <P>Criteria in two or more rules that cover the same financial dimension values are not allowed. If all financial dimension value combinations will be enabled for budget control, you can define a budget control rule without criteria.</P>



The budget control rules are validated against the ledger accounts that are being used on source document accounting distributions and accounting journals. If the financial dimensions in the ledger accounts match the financial dimensions in the budget control rules, a budget check occurs.

## Example: Define budget control rules to establish a different budget threshold for one department

The default budget control parameter values that you entered in the **Define parameters** area are used unless you specify a different budget cycle time span, budget interval, budget threshold, or budget manager for individual rules. For example, to assign a different budget threshold to only one department, you could define two budget control rules: one rule for the specific department and its budget threshold, and another rule for all of the other departments for their threshold.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Define budget control rules**.

3.  Define a rule where Department 010 has a budget threshold of 90.
    
    1.  Click **New** to create a rule, and then enter a rule name and description.
    
    2.  On the **Criteria** FastTab, click **Add filter**.
    
    3.  In the **Where** list, select the **Department** financial dimension.
    
    4.  In the **Operator** list, select **is**, and then enter 010 as the department number.
    
    5.  In the **Budget threshold** field, enter 90.

4.  Define a second rule where all other departments have a budget threshold of 100.
    
    1.  Click **New** to create another rule, and then enter a rule name and description.
    
    2.  On the **Criteria** FastTab, click **Add filter**.
    
    3.  In the **Where** list, select the **Department** financial dimension.
    
    4.  In the **Operator** list, select **is greater than and includes** and enter 020, which will include all departments except Department 010.
    
    5.  In the **Budget threshold** field, enter 100.

## Example: Define user group permissions for one user group for a budget control rule

You can define a budget control rule to provide unique user group permissions to budget amounts for specific financial dimension combinations. If the default over budget option for all user groups is **Prevent over budget processing**, you can define a rule that has a different over budget option for one user group for specific financial dimension combinations. For example, if you define a budget control rule that has a budget threshold of 90 for Department 010, you could define user group permissions for one user group in Department 010 to allow over budget processing for that user group.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Define budget control rules**.

3.  Define a rule where Department 010 has a budget threshold of 90.

4.  Click **User group budget permissions**.

5.  For one of the user groups in Department 010, select **Allow over budget processing** in the **Over budget options** field.
    

    > [!IMPORTANT]
    > <P>If you define budget groups, you must select the over budget options to prevent or allow budget group checking when budget funds are not available. For more information, see “Define budget groups” in this topic.</P>



6.  To override the current user group budget permissions for the budget control configuration, click **Copy**. Select a user group to copy and then edit the specific user group budget permissions.

## Select main accounts

If the main account financial dimension is not defined for budget control, you can select the main accounts that the budget control rules will be enforced for. If the main account financial dimension is defined as a budget control dimension, the main account financial dimension is included in the budget control rules, and this setup step is not required.

Only main account types of **Total**, **Profit and loss**, and **Expense** can be selected, because these are the accounts that typically are used for actual expenditures. Accounts that have a **Total** type are included because you can enter budget amounts in main accounts that have a **Total** type.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Select main accounts**.

3.  Select the check boxes to select the main accounts or click **Select all** to select all the main accounts.

4.  You can also click **Select** to define a query to filter the list of main accounts.

## Optional: Define budget groups

In the **Define budget groups** area, you can define budget groups to form a budget pool, or a collection of financial dimension values whose budgets will be pooled for a secondary budget check. The financial dimension combinations that are found in the budget control rule are always checked for budget amounts. If a financial dimension combination is also found in a budget group, a second budget check is performed at the budget group level.

For example, if there was a budget control rule for all combinations of the department and cost center financial dimensions, you could also define a budget group for Department 010, which would include all the cost centers in that department. This budget group would pool the budget of all the cost centers for Department 010. If an initial budget check failed for a cost center in Department 010, a second budget check would be performed on the aggregate budget for all cost centers in Department 010.


> [!NOTE]
> <P>Multiple criteria can be specified for a budget group. All the criteria are used to determine the financial dimension combinations for the budget group. No overlapping criteria are allowed across budget groups and budget group members.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.
    
    Click **Define budget groups**.
    
    The ledger name is displayed at the top of the hierarchy.

2.  Click **Add** to create a budget group member. Enter a budget group name and description.
    
    When you add a group member, you can add filter criteria, change user group permissions, and modify the default budget control properties.

3.  On the **Criteria** FastTab, click **Add filter**.

4.  For this example, in the **Where** list, you would select the **Department** financial dimension.

5.  In the **Operator** list, you would select **is**, and then enter 010 for the department number.
    

    > [!NOTE]
    > <P>To perform the secondary budget check, the <STRONG>Overbudget option for budget group check</STRONG> setting in the <STRONG>User group budget permissions</STRONG> form for budget control rules must be set to <STRONG>Perform budget group check when budget funds are not available</STRONG>.</P>



## Optional: Define message levels for user groups

In the **Define message levels** area, you can specify that budget control warning messages will not be displayed for selected user groups. Users in the selected user groups will continue to receive error messages based on their over budget permissions.

1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Define message levels**.

3.  Click **Select all** or select the check boxes next to the user groups that will not receive budget control warning messages.
    

    > [!NOTE]
    > <P>If a user belongs to multiple user groups and you select one user group that includes the user, no warning messages will be displayed for that user.</P>



## Activate budget control

In the **Activate budget control** area, you can make a draft budget control configuration active by clicking **Activate**. When you turn on budget control, the active budget control configuration takes effect.


> [!IMPORTANT]
> <P>If you turn off budget control, source documents and accounting journals that have a status of <STRONG>Draft</STRONG> are removed from the budget control tracking system. No additional budget checks are performed. If you turn on budget control again, you might have to manually adjust the budget to correct reserved budget amounts.</P>



1.  Click **Budgeting** \> **Setup** \> **Budget control** \> **Budget control configuration**.

2.  Click **Activate budget control**.

3.  Click **Activate** to make the draft version of the budget control configuration active.
    
    The **Date when last activated** field displays the current date, and the **Activated by** field displays your user ID.

4.  Click **Turn on** to start budget control by using the active configuration.
    
    The budget control status changes to **Turned on**, and the **Turn on** option is replaced with **Turn off**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

