---
title: 'Key tasks: Create expense reports'
TOCTitle: 'Key tasks: Create expense reports'
ms:assetid: 742d423d-fbf4-4459-b44e-0ea5bd39ffac
ms:mtpsurl: https://technet.microsoft.com/library/Hh271566(v=AX.60)
ms:contentKeyID: 36384197
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BarcodeCoverPage
- defaultEmployeeServicesManageExpenses
- TRVExpTableNew
- TRVExpTablePrint
- TRVExpTransDistributions
- TRVGuests
- TrvLinkReceipts
- TrvExpTransAddEdit
- TrvItemization
audience: Application User
ms.search.region: Global
---

# Key tasks: Create expense reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to create expense reports and submit them for approval. When you travel or incur other expenses on behalf of your company, you create an expense report to justify money that you spent by using the company credit card. If you paid for expenses by using your own money, you use the expense report to submit those expenses for reimbursement. An expense report describes, in detail, how and where the expenses were incurred.

Depending on the type of information that you must enter, creating an expense report can include multiple steps. This topic describes the tasks that you may have to complete when you enter expense reports.

## What do you want to do?

Create an expense report and add information about expenses

Itemize expenses by line

Distribute an expense

Distribute an expense in Microsoft Dynamics AX 2012 R2

Add an intercompany expense to an expense report in Microsoft Dynamics AX 2012 R2

Return a cash advance on an expense report

Split a credit card transaction to include a personal expense

Add guests

Attach receipts to an expense report

Submit an expense report

Print a barcode cover page for an expense report

Find related tasks

## Create an expense report and add information about expenses

1.  Click **Expenses** on the top link bar, and then click **Expense reports** on the Quick Launch.

2.  On the **Expense report** page, on the **Action Pane**, on the **Expense report** tab, in the **New** group, click **Expense report**.

3.  Select any unreconciled expenses that must be added to the expense report, and then click **Continue**. If no unreconciled expenses must be added, clear the **Select all transactions by default** check box, and then click **Continue**.

4.  Select the purpose of the expense, and then enter the expense location.

5.  On the **Expense lines** tab, click **Add new expense**, and then select the type of expense that you want to add.

6.  On the **New expense line** page, enter information about the expense.
    
    Use the **Itemize**, **Distribute amount**, **Guests**, and **Link receipts** buttons in the **Maintain** group to add information.
    

    > [!NOTE]
    > <P>You can add credit card expenses to an expense report either when you first create the report, or after you have created and saved the report.</P>



Back to top

## Itemize expenses by line

For certain expenses, you can list individual charges that produce the total amount. For example, you can divide a hotel charge into a daily room rate, room service charge, and laundry charge.

If you want to add multiple itemized lines, complete the following procedure.

1.  On the **New expense report** page, select the expense that you want to itemize, and then click **Itemize**.

2.  On the **Itemize** FastTab, enter the check-in date for the expense, and select the expense category.

3.  Enter the number of nights and the rate per night, and then click **Add**.

4.  On the **Itemized line item** tab, click **Add**.

5.  Select the expense category and the date of the expense, and then enter the amount for the item.

6.  Repeat steps 1 through 5 for each remaining item for the expense. When you have finished, click **Save and close**.

If you want to add one itemized line, complete the following procedure.

1.  On the **New expense report** page, select the expense that you want to itemize, and then click **Itemize**.

2.  On the **Itemized line item** tab, click **Add**.

3.  Select the expense category and the date of the expense, and then enter the amount for the item.

4.  Select the project ID, if the project ID is necessary, and then click **Save and close**.

Back to top

## Distribute an expense

You may want to assign responsibility for an expense to more than one group, organization, or party record. The expense amount can then be distributed among those groups, organizations, or parties. For example, you travel to Germany for 10 working days. You spend six days working for legal entity A and four days working for legal entity B. When you distribute the expense amount, legal entity A is responsible for 60 percent, and legal entity B is responsible for the remaining 40 percent.

When you are distributing expenses for a project, you can view information for your projects in the project validation forms in Microsoft Dynamics AX. However, you cannot filter projects by legal entity. Regardless of the legal entity that you are logged on to, you see the same list of projects. For example, if you are logged on to LE1, you see the same list of projects that you would see if you were logged on to LE2.


> [!WARNING]
> <P>If you have to update tax related fields after you have distributed an expense between two projects, you must re-distribute the expense. If you distribute an expense between two projects and then select the tax information, the distributions that you added will be deleted and replaced with the default distribution. You will not be notified of this change.</P>



1.  On the **New expense report** page, select the expense that you want to distribute, and then click **Other** \> **Distribute amounts**.

2.  On the **Distribute amounts** page, select whether you want to distribute the expense as an amount or a percentage.

3.  Select the legal entity, project ID, and category to which you want to distribute one part of the expense.

4.  Enter the amount or percentage that you want to distribute, and then click the check mark icon to save your entry.

5.  Click **Split** to add another line. Repeat steps 3 and 4 until you have distributed the total amount of the expense.
    
    If you want to distribute the expense amount equally among the legal entities, click **Distribute equally**.

Back to top

## Distribute an expense in Microsoft Dynamics AX 2012 R2

1.  On the **New expense report** page, select the expense that you want to distribute, and then click **Other** \> **Distribute amounts**.

2.  In the **Distribute** field, select whether to distribute the expense by percentages or amounts.

3.  Click **New** to add a distribution line, and then select the legal entity to which to distribute part of the expense.

4.  Depending on whether you selected to distribute the expense by percentages or amounts, enter the distribution percentage or amount in the appropriate field.

5.  Select the main account, department, cost center, and purpose for the expense.

6.  Repeat steps 3 through 5 to distribute the expense to another legal entity.

7.  After you have completed the expense distribution, click **Save and close**.

Back to top

## Add an intercompany expense to an expense report in Microsoft Dynamics AX 2012 R2

Occasionally, you might have to assign responsibility for an expense that you have incurred to another legal entity in your organization. If your organization has enabled intercompany expenses, you can select the responsible legal entity when you enter an expense. You can assign all or part of an expense to another legal entity.

1.  On the **New expense report** page, on the **Expense report** FastTab, select the **Intercompany expense report** check box.

2.  On the **Expense lines** FastTab, click **New expense line**.

3.  Select the legal entity to which you are assigning responsibility for the expense, select the expense category, and then click **OK**.

4.  Enter information about the expense. Additionally, if this expense was related to a project, enter information about the project.
    
    Only projects that are maintained by the legal entity that you have selected are available.

5.  Click **Save and new** to save this expense and create a new one. Alternatively, click **Save and close** to return to the expense report.

6.  If expenses that you have assigned to another legal entity require additional distribution, on the **Expense lines** FastTab, click **Other** \> **Distribute amounts**.

7.  To complete the distribution, see the "Distribute an expense" procedure in this topic.

Back to top

## Return a cash advance on an expense report

If you receive a cash advance from your organization, but you do not spend the whole amount, you can create an expense line on an expense report to return the rest.

1.  On the **New expense report** page, on the **Expense lines** FastTab, click **Other** \> **Return cash advances**.

2.  Select the **Cash advance return** category, and then on the **Action Pane**, click **Add to summary**.

3.  Select the line for the returned cash advance, and then on the **Expense lines** FastTab, click **Edit**.

4.  Enter the amount that you want to return, and then click **Save and close**.

Back to top

## Split a credit card transaction to include a personal expense

Part of an expense transaction that you charge to your corporate credit card may consist of a personal expense. For example, the total expense for a meal is EUR 65, but your spouse/partner joined you for the meal. Because your spouse/partner's meal is not covered by your organization, you can split the transaction. The cost of your spouse/partner's meal is then listed as a personal expense that you owe to your organization.


> [!NOTE]
> <P>You can split a credit card transaction to include a personal expense only if the credit card transaction has been imported into Microsoft Dynamics AX. You cannot manually enter a transaction and then split it.</P>



1.  On the **New expense report** page, on the **Expense lines** tab, select the imported transaction that you want to split, and then click **Split to personal**.

2.  Enter the amount of the transaction that you want to assign as a business expense.

3.  Select **Add remaining to personal**, and then click **Save and close**.

Back to top

## Add guests

When you enter entertainment or meal expenses on an expense report, you may have to enter expenses for other people. For example, you may take a potential client to dinner. When you enter the meal expense on your expense report, you can also list your guest.

1.  On the **New expense report** page, select the expense to which you want to add guests, and then depending on the version of Microsoft Dynamics AX 2012 you are using, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Other** \> **Persons entertained**.
    
      - In Microsoft Dynamics AX 2012 R3: Click **Other** \> **Guests**.

2.  Select whether the guest is internal to your organization, a personal guest, or a contact who is external to your organization.

3.  Select the name of the guest, and then enter the guest's company or organization and title.

4.  Repeat steps 1 through 3 for each guest that you want to add to the expense line.

5.  Click **Save and close**.

Back to top

## Attach receipts to an expense report

You can attach electronic receipts for expenses to an expense report. You can also view receipts that are already attached. You can attach receipts to the expense report at any time.

1.  On the **New expense report** page, on the **Action Pane**, on the **Expense report** tab, in the **Attach** group, click **Attach receipts**.

2.  Click one of the following buttons to attach a receipt to your expense report:
    
      - **Attach receipt file** – Browse your computer to locate and attach a copy of the expense receipt.
    
      - **Attach captured receipts** – Attach a receipt that was submitted by using a mobile phone, fax, or other device.
    
      - **Add URL** – Add the URL for the location of the expense receipt.

3.  When you have finished attaching receipts to the expense report, click **Close**.

Back to top

## Submit an expense report

When you have entered all of the information that is required by your organization and attached all expense receipts, if expense receipts are required, click **Submit** on the **Edit expense report** page.

Back to top

## Print a barcode cover page for an expense report

If you must submit an expense report and receipts by fax, you can print a barcode cover page that links your expense report and receipts. You can print a cover page before you create an expense report, or you can print a cover page for an existing report.

  - On the **New expense report** page, on the **Action Pane**, on the **Expense report** tab, click **Print expense report barcode cover page**.


> [!NOTE]
> <P>If you are printing a barcode cover page for an expense report that you have not yet created, a new window opens that contains a unique barcode. When the expense report is created, the barcode and the attached receipts are associated with your worker record.</P>



Back to top

## Find related tasks

[Key tasks: Modify expense reports](key-tasks-modify-expense-reports.md)

[Add delegates](add-delegates.md)

[Reconcile a travel requisition](reconcile-a-travel-requisition.md)

  


