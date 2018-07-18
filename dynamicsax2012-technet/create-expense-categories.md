---
title: Create expense categories
TOCTitle: Create expense categories
ms:assetid: ec2de76d-d50b-4608-a7ee-9d85de2d8721
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243253(v=AX.60)
ms:contentKeyID: 36059892
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create expense categories 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Employees must assign their expenses to predefined categories when they are working with expense reports. You can create two types of expense categories:

  - Categories for use by a single company – This type of category includes information about payment methods, expense types, cost splitting, and subcategories. These expense types can be used only for expenses that are charged to the company that they are created in. For example, if you create an expense category for car rental in company DAT, you cannot use the same category when creating an expense report for company DIR. A separate car rental expense category needs to be created for company DIR.

  - Shared categories – Shared expense categories can be used in any company in your enterprise. Shared categories let an employee incur an expense on behalf of a company he or she does not work for. For example, if an employee works for company DAT but incurs an expense attending a company DIR conference, company DIR pays company DAT for the expense.


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Create expense categories for a single company

1.  Click **Travel and expense** \> **Setup** \> **Travel and expense entry** \> **Expense categories**.

2.  Press CTRL+N to create a new line.

3.  Select a category ID, and enter a name for the category.
    

    > [!NOTE]
    > <P>Categories, and their IDs, must be created in the <STRONG>Categories</STRONG> form before expense categories can be created.</P>



4.  Select whether to use the expense category in **Project**.

5.  To create subcategories for the expense category, press CTRL+N on the **Subcategories** tab.
    
    Only the following expense types include subcategories:
    
      - Meals
    
      - Airline
    
      - Hotel
    
      - Miscellaneous
    
      - Car rental
    
      - Conference
    
      - Entertainment

6.  Enter a name and a brief description for the subcategory, and select the default payment method.

7.  If you are using the expense category in **Project**, enter information about the category on the **Project** tab.

## Create shared expense categories

1.  Click **Organization administration** \> **Setup** \> **Categories** \> **Shared categories**.

2.  Press CTRL+N to create a new line.

3.  Enter a category ID and a name for the shared category. For example, the ID might be **Airfare**, and the name might be **Flight** expenses.

4.  Select the corresponding check boxes to indicate whether this expense can be used in **Project**, **Expense management**, or **Production**.

5.  If you are using the category in **Expense management**, select the expense type.

## Create shared expense subcategories

1.  Click **Organization administration** \> **Setup** \> **Categories** \> **Shared categories**.

2.  Select the shared category that you want to create subcategories for.
    
    You can create new shared categories for the following expense types:
    
      - Meals
    
      - Airline
    
      - Hotel
    
      - Miscellaneous
    
      - Car rental
    
      - Conference
    
      - Entertainment

3.  On the **Subcategories** tab, press CTRL+N to create a new line.

4.  Enter a name and a description for the subcategory.

5.  Select the **Exclude from tax recovery** check box if this subcategory is not eligible for tax recovery, such as value-added tax (VAT) recovery.

## Inactivate expense categories and subcategories in Microsoft Dynamics AX 2012 R2

## Inactivate an expense category

1.  Click **Travel and expense** \> **Setup** \> **Travel and expense entry** \> **Expense categories**.

2.  Select the expense category to inactivate, and then, on the **Expense** FastTab, select the **Inactive** check box.

## Inactivate an expense subcategory

1.  Click **Travel and expense** \> **Setup** \> **Travel and expense entry** \> **Expense categories**.

2.  Select the active expense category that includes the subcategories to inactivate.

3.  On the **Subcategories** FastTab, select the subcategories to inactivate, and then select the **Inactive** check box.

## See also

[About integrating Travel and expense categories with Project management and accounting](about-integrating-travel-and-expense-categories-with-project-management-and-accounting.md)

  


