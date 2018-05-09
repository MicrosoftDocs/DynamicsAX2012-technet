---
title: 'Key tasks: Create and submit a purchase requisition'
TOCTitle: 'Key tasks: Create and submit a purchase requisition'
ms:assetid: 606c8fa1-45ba-40ed-8b66-32b4a9fd921b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209152(v=AX.60)
ms:contentKeyID: 36057620
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase
- procurement
- purchase requisition
- purchase requisitions
- requisitions
- requisition
- purchases
- submission
- submissions
- submittals
- submittal
- key task
- new purchase requisition
- purchase requisition creation
---

# Key tasks: Create and submit a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use a purchase requisition to submit a request for items or services that your organization requires.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



When using purchase requisitions, you can do the following:

  - Request items and services from an internal catalog. You can also request items and services that are not listed in a catalog.

  - Request items or services on behalf of someone else, or for a legal entity or operating unit other than the one in which you hold a primary position.

  - Suggest a vendor to order an item or service from.

  - Distribute an amount on a purchase requisition line to multiple financial accounts and dimensions.

  - Perform budget-checking on the purchase requisition if your organization uses budget-checking.

  - Submit the purchase requisition for review and approval.

## What do you want to do?

Learn more about...

Create a purchase requisition

View and modify purchase requisition lines

Suggest a vendor

Distribute an amount on a purchase requisition line

Perform a budget check for a purchase requisition line

Submit a purchase requisition to workflow

Work with a requisition purpose in Microsoft Dynamics AX 2012 R2

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About purchase requisitions](about-purchase-requisitions.md)

[About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md)

[Overview of a purchase requisition workflow](overview-of-a-purchase-requisition-workflow.md)

## Create a purchase requisition

Use this procedure to create a purchase requisition to request items or services for yourself, on behalf of other people, or for other legal entities or operating units. If you create purchase requisitions on behalf of another person, the purchasing policies that apply to that person, such as spending authority or available catalog items, are applied to these purchase requisition lines. If you create purchase requisitions for other legal entities or operating units, the purchasing policies that apply to those legal entities and operation units are applied to the purchase requisition lines.


> [!NOTE]
> <P>You must have the appropriate permissions before you can enter purchase requisitions for other users or other legal entities or operating units. For more information about how to set up these permissions, see <A href="set-up-permissions-for-ordering-products-on-behalf-of-someone-else.md">Set up permissions for ordering products on behalf of someone else</A>.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, on the **Action Pane**, click **Purchase requisition**.

3.  In the **Prepare a new purchase requisition** form, enter a name for the purchase requisition, and select the requested date and accounting date for the purchase requisition. By default, these dates are copied to the purchase requisition lines. They can be changed at the line level. The requested date is the requested delivery date. The accounting date is used to record the accounting entry in the general ledger, and to validate whether budget funds are available.
    

    > [!NOTE]
    > <P>The requested date can be modified to allow for a lead time that is associated with a product on a purchase requisition line.</P>



4.  If the purchase requisition has lines for project expenditures, select the **Select default project** check box, and then enter the following information:
    
      - In the **Buying legal entity** field, select the legal entity to which the project is assigned.
    
      - In the **Project ID** field, select the project ID to display by default on all purchase requisition lines for the project.
    

    > [!NOTE]
    > <P>The project data can be deleted or changed at the purchase requisition line level, but it will only be copied to the purchase requisition lines that are assigned to the buying legal entity that the project is assigned to.</P>



5.  In the **Purchase requisitions** form, on the **Purchase requisition header** FastTab, select a business justification reason, and enter a description. By default, the business justification reason that you select appears for the purchase requisition lines, but you can change it at the line level.
    

    > [!NOTE]
    > If you want to place a purchase requisition on hold, select the <STRONG>On hold</STRONG> check box in the <STRONG>Sourcing</STRONG> area, and provide an <STRONG>Explanation</STRONG>. 
    > <P>This control is available only if Microsoft Dynamics AX 2012 R3 is installed.</P>



6.  To add line items to the purchase requisition, on the **Purchase requisition lines** FastTab, click **Add items**.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Add line</STRONG> to add a line item and manually enter the required information.</P>



7.  In the **Add items** form, on the **Catalog items** tab, select the items that you want to add to the purchase requisition, and then click **Select -\>**. You can select multiple items to add them to your purchase requisition at the same time.
    

    > [!NOTE]
    > <P>If additional details about the product, inventory, or project dimensions are required for the items or services that you selected, enter them on the <STRONG>Details</STRONG> tab in the lower pane.</P>

    
    The list of items on the **Catalog items** tab is filtered by requester, buying legal entity, and receiving operating unit. You can also filter the list by procurement category.
    

    > [!NOTE]
    > <P>If you have been granted permission to request items or services on behalf of another user or another legal entity or operating unit, you can select the requester, the buying legal entity, and the receiving operating unit for which you are authorized to request items or services.</P>



8.  To add items that are not found in a catalog, click the **Non-catalog items** tab, and follow these steps for each product that you want to order:
    
    1.  Enter a product name.
    
    2.  Select a procurement category for the product, and enter an optional description.
    
    3.  In the **Vendor account** field, do one of the following:
        
          - Select an approved vendor.
        
          - Leave the field blank. A purchasing agent will select a vendor during the purchase requisition approval process.
        
          - Suggest a new vendor for the product. For more information about how to suggest a vendor, see the “Suggest a vendor” procedure later in this topic.
    
    4.  Enter a quantity, unit price, and currency for the product, and then enter the unit of measure in which the product is purchased.
    
    5.  If the product can be ordered online, you can enter a web address and the external item number that is assigned by the vendor.
    
    6.  Click **Select -\>** to add the non-catalog item to the list of products that you want to add to the purchase requisition.

9.  Optional: You can specify a general budget reservation on a purchase requisition line.
    

    > [!NOTE]
    > <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>

    
    If you use project accounting, all project details and project distributions are copied. Because of the budget reservation reference, some of the project details are not editable. For more information, see [About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md) and [Use project accounting with general budget reservations (Public sector)](use-project-accounting-with-general-budget-reservations-public-sector.md).

10. In the selected products list, review the items that you selected.
    
      - To view or modify the product dimensions, inventory dimensions, and project dimensions for the selected product, click the **Details** tab.
    
      - To remove a product, select the check box next to it, and then click **Remove**.

11. Click **OK** to add the products to the purchase requisition.

12. View or modify the purchase requisition lines, and then submit the purchase requisition for review and approval.

Back to top

## View and modify purchase requisition lines

After you add products to the purchase requisition, you can view the purchase requisition lines and view or modify the details for each line item. You can continue to add or remove items and services as long as the purchase requisition has a status of **Draft**. If the purchase requisition has been submitted for review, you must recall it before you can remove a purchase requisition line. For more information about purchase requisition statuses, see [About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md).

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, double-click the purchase requisition that contains the lines that you want to modify.

3.  In the **Purchase requisitions** form, on the **Action Pane**, on the **Purchase requisition** tab, in the **Maintain** group, click **Edit**.

4.  On the **Purchase requisition lines** FastTab, select the line that you want to view or modify, and then click **Details**.

5.  View or modify information about the delivery address and other details, such as the fixed asset group, project, financial dimensions, and inventory dimensions for the line.

6.  If the line item qualifies as a fixed asset, on the **Fixed assets** FastTab, enter any additional information about the item. After the asset information is entered, the system evaluates the data and automatically assigns the appropriate asset group to the item. Asset groups are user–defined codes that identify the purpose for purchasing the fixed asset.

7.  After you change the purchase requisition line, on the **Action Pane**, on the **Purchase requisition line** tab, click **Line details**.

8.  If you have no additional changes to the purchase requisition lines, submit the purchase requisition for review and approval.

Back to top

 

## Suggest a vendor

Use this procedure to suggest a new vendor for a product. This option is available only for purchase requisition lines that reference a non-catalog item or service.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, select the purchase requisition for which you want to suggest a vendor, and then on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  In the **Purchase requisitions** form, on the **Purchase requisition lines** FastTab, select the line for which you want to suggest a vendor. Click **Purchase requisition line** \> **Suggest vendors**.

4.  In the **Vendor suggestions** form, select a vendor from a list of company vendors or propose a new vendor with whom you want to do business. Do one of the following:
    
      - To select a vendor from the list of company vendors, on the **Company vendors** FastTab, click **Add**. In the **Vendor account** field, select the company vendor from the list.
    
      - To propose a new vendor, on the **New proposed vendors** FastTab, click **Add**. Enter the name of the proposed vendor, and add contact information such as a telephone number and email address. You can add details about your suggestion in the **Notes** field.

Back to top

## Distribute an amount on a purchase requisition line

Use this procedure to distribute an amount on a purchase requisition line to multiple financial accounts and dimensions. You can also modify the default financial accounts where the purchase of the item is recorded.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, create a new purchase requisition or select one in the list, and then on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  In the **Purchase requisitions** form, on the **Purchase requisition lines** FastTab, create or select a purchase requisition line. Click **Financials** \> **Distribute amounts**.

4.  In the **Accounting distributions** form, you can view the default distribution for the product on the selected purchase requisition line. If you want to override the default settings and distribute the cost of the product to multiple financial accounts and dimensions, follow these steps:
    
    1.  In the **Purchase requisition lines** field, select the amount that you want to distribute. You can distribute the extended price, discount, and charges individually, or you can distribute the net amount of the line.
    
    2.  In the **Distributed by** field, select the method of distribution. You can distribute by percent, amount, or quantity.
    
    3.  Click **Split** to copy the financial account to a new line.
    
    4.  On the new line, select a ledger account and dimension, and then enter the amount that you want to charge to each account and dimension. The amount that you enter for the new line is subtracted from the amount on the original line.

5.  If you want to delete a distribution line, select the line, and then click **Delete**. You cannot delete the original line.

6.  If you want to clear all distributions except the original line, click **Reset**.

7.  If you want to split the original line amount equally among the listed financial accounts and dimensions, click **Distribute equally**.

8.  To save your changes and return to the purchase requisition, click **Close**.

Back to top

## Perform a budget check for a purchase requisition line

Use this procedure to view the details about budget errors or warnings for the amounts on a purchase requisition or a purchase requisition line. If your organization uses dimensions, such as departments or cost centers, you can view the budget check results for a combination of financial accounts and dimensions assigned to a purchase requisition line.


> [!NOTE]
> <P>The form that displays the budget check result is empty if the budget check passes, or if your organization has not set up a budget.</P>



You must perform a budget check before you can view the budget check result. When you perform a budget check, the amount on the purchase requisition line is subtracted from the available budget amount. If the amount on the line exceeds the available budget amount, you receive a warning.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, create a new purchase requisition or select one in the list. On the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  In the **Purchase requisitions** form, you can perform a budget check for all lines or for a selected line. Do one of the following:
    
      - To perform a budget check for all lines, on the **Action Pane**, on the **Financials** tab, in the **Budget** group, click **Perform budget checking**.
    
      - To perform a budget check on a specific line, on the **Purchase requisition lines** FastTab, select a line, and then click **Financials** \> **Perform budget checking**.

4.  To view the result of the budget check, on the **Purchase requisitions** form, on the **Action Pane**, on the **Financials** tab, in the **Budget** group, click **Budget check errors or warnings**.

The result of the budget check is either **Budget check passed**, **Budget check passed but with warnings**, or **Budget check failed**. The **Budget check result detail** field displays a detailed explanation of the budget check result, and suggests actions that you can take to manage the error or warning.

Back to top

## Submit a purchase requisition to workflow

To submit a purchase requisition (or replenishment requisition) to workflow, you must be the preparer. All required fields must be filled in, and the requisition must contain at least one line item before it can be submitted. The requisition must have a status of **Draft**.

The workflow process can route the requisition through the review process as a single document. Alternatively, the lines on the requisition can be routed individually to the appropriate reviewers. If the requisition lines are reviewed individually, the review process must be completed for all requisition lines before the review process for the requisition can be completed. The overall status of the requisition is controlled by the status of the requisition lines.

For more information about how to configure workflow for requisition lines, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

If you are using general budget reservations with your purchase requisitions, you can add a reservation task to your purchase requisition workflow. You can also create general budget reservation workflows.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



For more information, see [Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md).

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, select the requisition that you want to submit to workflow.

3.  In the workflow message bar, click **Submit**.

4.  In the dialog box that opens, enter a comment in the **Comment** field, and then click **Submit**.

5.  To recall a requisition that you have submitted to workflow, in the workflow message bar, click **Actions** \> **Recall**.

6.  To view the workflow history for a requisition that you have submitted to workflow, in the workflow message bar, click **Actions** \> **View history**.

Back to top

## Work with a requisition purpose in Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose has been introduced. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign one of two purposes to it: consumption or replenishment. The default purpose is consumption. This is equivalent to a purchase requisition in earlier versions of Microsoft Dynamics AX, where the replenishment purpose was not available. Depending on the requisition purpose and how your organization is set up, requisition demand can be fulfilled by a purchase order, transfer order, production order, or kanban. For more information about requisition purposes and how they affect the requisition process, see [About purchase requisitions](about-purchase-requisitions.md).

A requisition that has a purpose of replenishment represents a demand to replenish inventory, or request items or services. For example, you might want to create a requisition to replenish items so that they can be sold at a specific retail location at a specific time. The demand can be fulfilled by a purchase order, transfer order, production order, or kanban. When the requisition purpose is replenishment, demand is expressed as a quantity instead of a monetary amount. Therefore, encumbrance accounting, budgetary control, business rules for fixed asset determination (BRAD), project accounting, and any related rules do not apply. Any tasks described earlier in this topic that refer to accounting, budget, assets, financial dimensions, project, vendors, and so on do not apply. Only products that are stocked and released to the specified legal entity can fulfill replenishment requisition demand.

By using requisitions with a purpose of replenishment, you can do the following:

  - Request items and services from an internal catalog.

  - Request items or services on behalf of someone else, or for a legal entity or operating unit other than the one in which you hold a primary position.

  - Submit the purchase requisition for review and approval.

The requisition purpose **Replenishment** must be enabled for your organization before you can create a requisition with a purpose of replenishment. For more information about how to set up requisition purposes, see [Requisition purpose rule (form)](https://technet.microsoft.com/en-us/library/jj677434\(v=ax.60\)).

### Create a requisition with a purpose of replenishment

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, on the **Action Pane**, click **Purchase requisition**.

3.  In the **Prepare a new purchase requisition** form, enter a name for the purchase requisition, and select the requested date for the requisition. By default, these dates are copied to the requisition lines. They can be changed at the line level. The requested date is the requested delivery date.

4.  Select the **Replenishment** requisition purpose. The requisition purpose might be preselected if **Replenishment** is the default requisition purpose for your organization.

5.  In the **Purchase requisitions** form, on the **Purchase requisition header** FastTab, select a business justification reason, and enter a description. By default, the business justification reason that you select is displayed for the requisition lines, but you can change it at the line level.

6.  To add line items to the requisition, on the **Purchase requisition lines** FastTab, click **Add items**.
    

    > [!NOTE]
    > <P>You can also click <STRONG>Add line</STRONG> to add a line item and manually enter the required information.</P>



7.  In the **Add items** form, on the **Catalog items** tab, select the items to add to the requisition, and then click **Select -\>**. You can select multiple items so that you can add them to your requisition at the same time.
    

    > [!NOTE]
    > <P>If additional details about the product or inventory dimensions are required for the items or services that you selected, enter them on the <STRONG>Details</STRONG> tab in the lower pane.</P>

    
    The list of items on the **Catalog items** tab is filtered by requester, buying legal entity, and receiving operating unit. You can also filter the list by category.
    

    > [!NOTE]
    > <P>If you have been granted permission to request items or services on behalf of another user or another legal entity or operating unit, you can select the requester, the buying legal entity, and the receiving operating unit that you are authorized to request items or services for.</P>



8.  Click **OK** to add the products to the requisition.

9.  View or modify the requisition lines. Submit the requisition for review and approval.

After you add products to the requisition, you can view the requisition lines and view or modify the details for each line item. You can continue to add or remove items and services as long as the requisition has a status of **Draft**. If the requisition has been submitted for review, you must recall it before you can remove a requisition line. For more information about requisition statuses, see [About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md).

### View and modify replenishment requisition lines

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, double-click the requisition that contains the lines to modify.

3.  In the **Purchase requisitions** form, on the **Action Pane**, on the **Purchase requisition** tab, in the **Maintain** group, click **Edit**.

4.  On the **Purchase requisition lines** FastTab, select the requisition line to view or modify, and then click **Details**.

5.  After you modify the requisition line, on the **Action Pane**, on the **Purchase requisition line** tab, click **Line details**.

6.  If you have no additional changes to the lines, submit the requisition for review and approval.

### Submit a replenishment requisition to workflow

1.  To use requisitions that have a purpose of replenishment, Microsoft Dynamics AX 2012 R2 must be set up to include requisition demand in master scheduling.

2.  After requisition demand in master scheduling is set up, approved requisitions that have a purpose of replenishment are automatically released to master scheduling, and the fulfillment method for the demand created by these requisitions is determined. This method is determined by the supply policies that have been set up for the items in your organization and planned by using master scheduling.

3.  After a replenishment requisition has been created and approved, no additional user action is required. For more information, see [Set up master plans to include requisitions](set-up-master-plans-to-include-requisitions.md).
    
    For step-by-step instructions about how to submit a replenishment requisition to workflow, see “Submit a purchase requisition to workflow” earlier in this topic.

Back to top

## Find form help

[Purchase requisitions (form)](https://technet.microsoft.com/en-us/library/hh209453\(v=ax.60\))

[Purchase requisitions - lines (form)](https://technet.microsoft.com/en-us/library/hh209354\(v=ax.60\))

[Purchase requisitions (list page)](https://technet.microsoft.com/en-us/library/hh227485\(v=ax.60\))

[Vendor suggestions (form)](https://technet.microsoft.com/en-us/library/hh208595\(v=ax.60\))

[Business justifications (form)](https://technet.microsoft.com/en-us/library/hh242732\(v=ax.60\))

## Find related tasks

[Set up permissions for ordering products on behalf of someone else](set-up-permissions-for-ordering-products-on-behalf-of-someone-else.md)

[Set up business justification codes](set-up-business-justification-codes.md)

[View the history for a purchase requisition](view-the-history-for-a-purchase-requisition.md)

[Set up master plans to include requisitions](set-up-master-plans-to-include-requisitions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

