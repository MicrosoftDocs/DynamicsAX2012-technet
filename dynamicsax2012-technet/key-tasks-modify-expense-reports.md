---
title: 'Key tasks: Modify expense reports'
TOCTitle: 'Key tasks: Modify expense reports'
ms:assetid: 7e9026d4-36b7-4762-b3e8-af7840a3c8ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271577(v=AX.60)
ms:contentKeyID: 36384208
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- TrvExpTableEdit
- TrvExpTrans
---

# Key tasks: Modify expense reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to change or update an expense report in Enterprise Portal for Microsoft Dynamics AX. You might need to update an expense report for a variety of reasons, including the following:

  - To remove intercompany expenses that should not be included in the report

  - To remove personal expenses from the report

  - To add names of all guests for an entertainment expense

  - To return an unused portion of a cash advance

  - To attach missing receipts to the report


> [!IMPORTANT]
> <P>After an expense report is submitted for approval, you can modify the line items only if the approver returns the expense report for changes or the submitter recalls the expense report.</P>



## What do you want to do?

Modify an expense report

Modify expense line items on an expense report

Add expense line items

Itemize expenses by line

Distribute an expense

Add an intercompany expense to an expense report in Microsoft Dynamics AX 2012 R2

Split a credit card transaction to include a personal expense

Return a cash advance on an expense report

Add guests

Attach receipts to an expense report

Submit an expense report

Print an expense report or a bar-coded cover page

Find related tasks

## Modify an expense report

1.  Click **Expenses** on the top link bar, and then click **Expense reports** on the Quick Launch.

2.  In the **Expense report number** column, select the expense report that you want to modify.

3.  Modify the expense report and the line items by using the procedures in this topic.

Back to top

## Modify expense line items on an expense report

1.  On the **Edit expense report** page, select the line item that you want to modify, and then on the **Expense lines** FastTab, click **Edit**.

2.  When you have finished making changes, click **Save and close**.

Back to top

## Add expense line items

After you create and save an expense report, you can add expense line items, provided that you have not submitted the expense report for approval.

1.  On the **Edit expense report** page, on the **Expense lines** tab, click **Add new expense**, and then select the type of expense that you want to add.

2.  On the **New expense line** page, enter information about the expense.
    
    Use the **Itemize**, **Distribute amount**, **Guests**, and **Link receipts** buttons in the **Maintain** group to add more detailed information or required information.

Back to top

## Itemize expenses by line

For certain expenses, you can list individual charges that produce the total amount. For example, you can divide a hotel charge into a daily room rate, room service charge, and laundry charge.

If you want to add multiple itemized lines, complete the following procedure.

1.  On the **Edit expense report** page, select the expense that you want to itemize, and then click **Itemize**.

2.  On the **Itemize** FastTab, enter the check-in date for the expense, and select the expense category.

3.  Enter the number of nights and the rate per night, and then click **Add**.

4.  On the **Itemized line item** tab, click **Add**.

5.  Select the expense category and the date of the expense, and then enter the amount that you want to itemize.

6.  Repeat steps 1 through 5 until you have added all of the itemizations for the expense. When you have finished, click **Save and close**.

If you want to add one itemized line, complete the following procedure.

1.  On the **Edit expense report** page, select the expense that you want to itemize, and then click **Itemize**.

2.  On the **Itemized line item** tab, click **Add**.

3.  Select the expense category and the date of the expense, and then enter the amount for the item.

4.  Select the project ID, if a project ID is necessary, and then click **Save and close**.

Back to top

## Distribute an expense

You may want to assign responsibility for an expense to more than one group, organization, or party record. The expense amount can then be distributed among those groups, organizations, or parties. For example, you travel to Germany for 10 working days. You spend six days working for legal entity A and four days working for legal entity B. When you distribute the expense amount, legal entity A is responsible for 60 percent of the expenses, and legal entity B is responsible for the remaining 40 percent.

When you are distributing expenses for a project, you can view information for your projects in the project validation forms in Microsoft Dynamics AX. However, you cannot filter projects by legal entity. Regardless of the legal entity that you are logged on to, you see the same list of projects. For example, if you are logged on to LE1, you see the same list of projects that you would see if you were logged on to LE2.

1.  On the **Edit expense report** page, select the expense that you want to distribute, and then click **Other** \> **Distribute amounts**.

2.  On the **Distribute amounts** page, select whether you want to distribute the expense as an amount or a percentage.

3.  Select the legal entity, project ID, and category to which you are distributing one part of the expense.

4.  Enter the amount or percentage that you want to distribute, and then click the check mark icon to save your entry.

5.  Click **Split** to add another line. Repeat steps 3 and 4 until you have distributed the total expense.
    
    If you want to distribute the expense amount equally among the legal entities, click **Distribute equally**.

Back to top

## Add an intercompany expense to an expense report in Microsoft Dynamics AX 2012 R2

You can add intercompany expenses to an existing expense report. For more information about how to add intercompany expenses to an expense report, see [Key tasks: Create expense reports](key-tasks-create-expense-reports.md).

If you have created an intercompany expense report and the expense report should not include intercompany expenses, on the **Expense lines** FastTab, remove all intercompany expenses, and then on the **Expense report** FastTab, clear the **Intercompany expense report** check box.

Back to top

## Split a credit card transaction to include a personal expense

Part of an expense transaction that you charge to your corporate credit card may consist of a personal expense. For example, the total expense for a meal is EUR 65, but your spouse/partner joined you for the meal. Because your spouse/partner's meal is not covered by your organization, you can split the transaction. The cost of your spouse/partner's meal is then listed as a personal expense that you owe to your organization.


> [!NOTE]
> <P>You can split a credit card transaction to include a personal expense only if the credit card transaction has been imported into Microsoft Dynamics AX. You cannot manually enter a transaction and then split it.</P>



1.  On the **Edit expense report** page, on the **Expense lines** tab, select the imported transaction that you want to split, and then click **Split to personal**.

2.  Enter the amount of the transaction that you want to assign as a business expense.

3.  Select **Add remaining to personal**, and then click **Save and close**.

Back to top

## Return a cash advance on an expense report

If you receive a cash advance from your organization, but you do not spend the whole amount, you can create an expense line on an expense report to return the rest.

1.  On the **Edit expense report** page, on the **Expense lines** FastTab, click **Other** \> **Return cash advances**.

2.  Select the category for the returned cash advance, and then on the **Action Pane**, select **Add to summary**.

3.  Select the line for the returned cash advance, and then on the **Expense lines** FastTab, click **Edit**.

4.  Enter the cash advance amount that you want to return, and then click **Save and close**.

Back to top

## Add guests

When you enter entertainment or meal expenses on an expense report, you may have to enter expenses for other people. For example, you may take a potential client to dinner. When you enter the meal expense on your expense report, you can also list your guest.

1.  On the **Edit expense report** page, select the expense to which you want to add guests, and then depending on the version of Microsoft Dynamics AX 2012 you are using, do one of the following:.
    
      - In Microsoft Dynamics AX 2012 R2: Click **Other** \> **Persons entertained**.
    
      - In Microsoft Dynamics AX 2012 R3: Click **Other** \> **Guests**.

2.  Select whether the guest is internal to your organization, a personal guest, or a contact that is external to your organization.

3.  Select the name of the guest, and then enter the guest's company or organization and title.

4.  Repeat steps 1 through 3 for each guest that you want to add to the expense line.

5.  Click **Save and close**.

Back to top

## Attach receipts to an expense report

You can attach electronic receipts for expenses to an expense report. You can also view receipts that are already attached. You can attach receipts to the expense report at any time.

1.  On the **Edit expense report** page, on the **Action Pane**, on the **Expense report** tab, in the **Attach** group, click **Receipts**.

2.  Click one of the following buttons to attach a receipt to your expense report:
    
      - **Attach receipt file** – Browse your computer to locate and attach a copy of the expense receipt.
    
      - **Attach captured receipts** – Attach a receipt that was submitted by using a mobile phone, fax, or other device.
    
      - **Add URL** – Add the URL for the location of the expense receipt.

3.  When you have finished attaching receipts to the expense report, click **Close**.

Back to top

## Submit an expense report

For information about how to submit an expense report, see [Key tasks: Create expense reports](key-tasks-create-expense-reports.md).

Back to top

## Print an expense report or a bar-coded cover page

For information about how to print an expense report or a bar-coded cover page, see [Key tasks: Create expense reports](key-tasks-create-expense-reports.md).

Back to top

## Find related tasks

[Key tasks: Create expense reports](key-tasks-create-expense-reports.md)

[Add delegates](add-delegates.md)

[Reconcile a travel requisition](reconcile-a-travel-requisition.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

