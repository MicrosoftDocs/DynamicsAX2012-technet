---
title: Create and maintain purchase requisitions
TOCTitle: Create and maintain purchase requisitions
ms:assetid: f570cb1a-077f-4932-b423-2b76a6927a7a
ms:mtpsurl: https://technet.microsoft.com/library/Hh299224(v=AX.60)
ms:contentKeyID: 36384330
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- BudgetCheckResults
- EPPurchReqAddItem
- EPPurchReqAddItemDetails
- EPPurchReqCreate
- EPPurchReqLineDistributions
- EPPurchReqLineEdit
- EPPurchReqLineInfo
- EPPurchReqLineInfoHistory
- EPPurchReqLineVendorProposalEdit
- EPPurchReqLineVendorProposalHistory
- EPPurchReqLineVendorProposalInfo
- EPPurchReqTableCreate
- EPPurchReqTableEdit
- EPPurchReqTableList
- PurchReqAllMyReports
- PurchReqAssignedToMe
- PurchReqMyDirectReports
- PurchReqPreparedByMe
- PurchReqTableListPage
audience: Application User
ms.search.region: Global
---

# Create and maintain purchase requisitions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Purchase requisitions** page to create purchase requisitions and submit them to workflow.


> [!IMPORTANT]
> <P>This topic is aimed at Enterprise Portal users. If you are using the Dynamics AX desktop client, see <A href="key-tasks-create-and-submit-a-purchase-requisition.md">Key tasks: Create and submit a purchase requisition</A>.</P>



You can also create a new purchase requisition by copying the header and lines from an existing purchase requisition. For more information, see [Copy a purchase requisition](copy-a-purchase-requisition.md).

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose has been introduced in order to allow for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign it one of two purposes: consumption or replenishment. Depending on the purpose of the requisition, demand can be fulfilled by a purchase order, transfer order, production order, or kanban. For more information about requisition purposes and how they affect the requisition process, see [About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md).

## Create a purchase requisition

1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  On the **Action Pane**, on the **Purchase requisition** tab, in the **New** group, click **Purchase requisition**.

3.  Enter a name for the purchase requisition.

4.  Enter the date by which you want to receive the requested items.

5.  If the requisition purpose is consumption, enter the accounting date for the purchase requisition transaction. This date is used to record the accounting entry in the general ledger, and to validate that budget funds are available.

6.  If the requisition purpose is consumption, and the purchase requisition has lines for project expenditures, select the **Select default project** check box, and then enter the following information:
    
      - In the **Buying legal entity** field, select the legal entity to which the project is assigned.
    
      - In the **Project ID** field, select the project ID to display by default on all purchase requisition lines for the project.

7.  Click **Create**.

8.  You can add items to the purchase requisition now. Alternatively, you can save and close the purchase requisition, and then add items to it later. Do one of the following:
    
      - To add items to the purchase requisition now, follow the steps in the next procedure in this topic, "Add items to a purchase requisition."
    
      - To add items to the purchase requisition later, click **Save and close**. When you are ready to add the items, follow the steps in the procedure "Modify a purchase requisition," later in this topic.

## Add items to a purchase requisition

To add items to a purchase requisition when you create it, follow the steps in this procedure. To add items to a purchase requisition after you have saved and closed it, follow the steps in "Modify a purchase requisition," later in this topic.

1.  In the purchase requisition that you just created, on the **Purchase requisition lines** FastTab, click **Add items**.

2.  On the **Add items** page, click **Catalog items** to view products that you can purchase from an internal catalog. To enter a product that you cannot find in an internal catalog, click **Non-catalog items**.
    

    > [!NOTE]
    > <P>You can only add non-catalog items when the requisition purpose is consumption.</P>



3.  For catalog items, select the check box for the products that you want to order, and then click **Select**.
    

    > [!NOTE]
    > <P>When the requisition purpose is replenishment, only products that are stocked and released to the specified legal entity are available. For more information about how to define the products available when the requisition purpose is replenishment, see “Replenishment category access policy rule (form)” in the Application User Help in the Microsoft Dynamics AX 2012 R2 client.</P>



4.  For non-catalog items, follow these steps for each product that you want to order:
    
    1.  Enter a product name and an optional description.
    
    2.  Select a procurement category for the product.
    
    3.  In the **Vendor account** field, complete one of the following actions:
        
          - Select an approved vendor.
        
          - Leave the field blank. A purchasing agent will select a vendor during the purchase requisition approval process.
        
          - Suggest a new vendor for the product. For more information, see “Suggest a vendor for a non-catalog product,” later in this topic.
    
    4.  Enter a quantity, unit price, and currency for the product, and then enter the unit of measure in which the product is purchased.
    
    5.  If the product can be ordered online, you can optionally enter an Internet address and the external item number that is assigned by the vendor.
    
    6.  Click **Select**.

5.  Repeat steps 2 through 4 to add other products to the purchase requisition.

6.  In the **Items to be added to purchase requisition** list, review the items that you selected.
    
      - To remove a product, select the check box on the row that contains the product, and then click **Remove**.
    
      - To view the product dimensions and inventory dimensions for the selected product, open the **Details** FastTab. When the requisition purpose is consumption, you can also view project dimensions.

7.  Click **OK** to add the selected products to the purchase requisition.

8.  On the **Edit purchase requisition** page, in the **Reason** field, enter a business justification for the purchase requisition. In the **Details** field, you can optionally add a description of the reason and any information about the requisition.

9.  Do one of the following:
    
      - To complete the purchase requisition later, click **Save and close**.
    
      - To submit the purchase requisition to workflow for approval, click **Submit** in the workflow message bar.

## Modify a purchase requisition

After you create a purchase requisition, you can add other items or services to it. You can modify only purchase requisitions that you created.

1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  Select the purchase requisition that you want to modify, and then on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  To add products to the purchase requisition, on the **Purchase requisition lines** FastTab, click **Add items**.

4.  On the **Add items** page, click **Catalog items** to view the products that you can purchase from an internal catalog. To enter a product that you cannot find in an internal catalog, click **Non-catalog items**.
    

    > [!NOTE]
    > <P>You can only add non-catalog items when the requisition purpose is consumption.</P>



5.  For catalog items, select the check box for the products that you want to order, and then click **Select**.
    

    > [!NOTE]
    > <P>When the requisition purpose is replenishment, only products that are stocked and released to the specified legal entity are available. For more information about how to define the products that are available when the requisition purpose is replenishment, see “Replenishment category access policy rule (form)” in the Application User Help in the Microsoft Dynamics AX 2012 R2 client.</P>



6.  For non-catalog items, follow these steps for each product that you want to order:
    
    1.  Enter a product name and an optional description.
    
    2.  Select a procurement category and a vendor for the product.
    
    3.  Enter a quantity, unit price, and currency for the product, and then enter the unit of measure in which the product is purchased.
    
    4.  If the product can be ordered online, you can optionally enter an Internet address and the external item number that is assigned by the vendor.
    
    5.  Click **Select**.

7.  Click **OK** to add the selected products to the purchase requisition.

8.  To modify the quantity and other details for a product, on the **Purchase requisition lines** FastTab, select the line, and then click **Edit**. On the **Edit purchase requisition line details** page, change the product details, and then click **Save and close**.

9.  To view the product details for a purchase requisition line, on the **Purchase requisition lines** FastTab, click **Details**. You can view information about the delivery address and inventory dimensions for the line. When the requisition purpose is consumption, you can also view other details, such as the fixed asset group, project, and financial dimensions. On the **View purchase requisition line details** page, on the Action Pane, on the **View** tab, in the **Maintain** group, click **Edit** to modify the purchase requisition line details.

10. When you have finished making your changes, click **Save and close**.

11. On the **Edit purchase requisition** page, click **Save and close**.

## Suggest a vendor for a non-catalog product

Use this procedure to suggest a new vendor for a product. This option is only available for purchase requisition lines that reference a non-catalog item or service.


> [!NOTE]
> <P>This procedure applies only when the requisition purpose is consumption.</P>



1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  Create a new purchase requisition, or select a purchase requisition in the list. Then, on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  On the **Purchase requisition lines** FastTab, add or select a line for a non-catalog item, and then click **Purchase requisition line** \> **Actions** \> **Suggest vendors**.

4.  You can select a vendor from a list of company vendors or propose a new vendor with whom you want to do business.

5.  To propose a new vendor, on the **New proposed vendors** FastTab, click **Add**. Enter the name of the proposed vendor, and add contact information such as a telephone number and e-mail address. You can add details about your suggestion in the **Notes** field.

6.  Click **Save and close**.


> [!NOTE]
> <P>When you suggest a new vendor, the reviewer of the purchase requisition may instruct you to complete a new vendor request. For more information about requests for new vendors, see <A href="create-or-update-a-new-vendor-request.md">Create or update a new vendor request</A>.</P>



## Distribute an amount on a purchase requisition line

Use this procedure to distribute an amount on a purchase requisition line to multiple financial accounts and dimensions. You can also modify the financial accounts to which the purchase of the item is recorded by default.


> [!NOTE]
> <P>This procedure applies only when the requisition purpose is consumption.</P>



1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  Create a new purchase requisition, or select a purchase requisition in the list. Then, on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  On the **Purchase requisition lines** FastTab, create or select a line, and then click **Financials** \> **Accounting** \> **Distribute amounts**.

4.  You can post the cost of the product to another financial account and dimension. On the **Distribute amount for purchase requisition line** page, modify the default information in the **Main account**, **Department**, **Cost center**, and **Expense purpose** fields. In the **Distribute** field, select the amount that you want to distribute. You can distribute the extended price, discount, and charges individually, or you can distribute the net amount of the line.

5.  If you want to distribute the cost of the product to multiple financial accounts and dimensions, follow these steps:
    
    1.  In the **Distribute** field, select the amount that you want to distribute. You can distribute the extended price, discount, and charges individually, or you can distribute the net amount of the line.
    
    2.  In the **Distribute by** field, select the method of distribution. You can distribute by percentage, amount, or quantity.
    
    3.  Click **Split** to copy the financial account to a new line.
    
    4.  On the new line, select a financial account and dimension, and then enter the amount that you want to charge to each account and dimension.

6.  To delete a distribution line, select the line, and then click **Delete**. You cannot delete the original line.

7.  To clear all distributions except the original line, click **Reset**.

8.  To split the original line amount equally among the listed financial accounts and dimensions, click **Distribute equally**.

9.  To save your changes and return to the **Edit purchase requisition** page, click **Save and close**.

## Perform a budget check for a purchase requisition line

Use this procedure to view the details about budget errors or warnings for the amounts on a purchase requisition line. If your organization uses dimensions, such as departments or cost centers, you can view the result of the budget check for a combination of financial accounts and dimensions that is assigned to a purchase requisition line.

The page that displays the budget check result is empty if the budget check passes, or if your organization has not set up a budget.

You must perform a budget check before you can view the budget check result. When you perform a budget check, the amount on the purchase requisition line is subtracted from the available budget amount. If the amount on the line exceeds the available budget amount, you receive a budget warning.


> [!NOTE]
> <P>This procedure applies only when the requisition purpose is consumption.</P>



1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  Create a new purchase requisition, or select a purchase requisition in the list. Then, on the **Action Pane**, on the **Purchase requisition** tab, click **Edit**.

3.  On the **Edit purchase requisition** page, on the **Purchase requisition lines** FastTab, select a line.

4.  To perform a budget check, click **Financials** \> **Budget** \> **Perform budget check**.

5.  To view the result of the budget check, click **Financials** \> **Budget** \> **Budget check errors or warnings**.

The result of the budget check is either **Budget check passed**, **Budget check passed but with warnings**, or **Budget check failed**. The **Budget check result detail** field displays a detailed explanation of the budget check result, and actions that you can take to manage the error or warning.

## Submit a purchase requisition to workflow

You can submit only purchase requisitions that you created to workflow. All required fields must be entered, and the purchase requisition must contain at least one line item before it can be submitted. The status of the purchase requisition must be **Draft**.

1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  On the **Purchase requisitions** page, select the purchase requisition that you want to submit to workflow, and then click **Submit**.

## See also

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

[View purchase requisition history (Enterprise Portal)](view-purchase-requisition-history-enterprise-portal.md)

[View workflow history for a purchase requisition](view-workflow-history-for-a-purchase-requisition.md)

[Delegate permissions to create purchase requisitions on your behalf](delegate-permissions-to-create-purchase-requisitions-on-your-behalf.md)

[Copy a purchase requisition](copy-a-purchase-requisition.md)

  


