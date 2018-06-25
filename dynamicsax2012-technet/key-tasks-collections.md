---
title: 'Key tasks: Collections'
TOCTitle: 'Key tasks: Collections'
ms:assetid: 07ca5728-3521-47d2-9426-f2c34eb5c194
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242116(v=AX.60)
ms:contentKeyID: 36055970
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- case
- balances
- collections
- activity
- activities
- balance
- collection
- customer
- age
- aging
- cases
- collect
- customers
- days to pay
- days-to-pay
- write off
- writeoff
- write-off
---

# Key tasks: Collections [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Managing and collecting for overdue transactions is a necessary function in many organizations. Most collections functionality is centralized in the **Collections** form and on the following related list pages: **Collections**, **Collections activities**, and **Collections cases**.

Sometimes one person handles a company’s collections for all customers. In other situations, a team of collections agents works together to manage collections. If your business needs require it, you can set up collections agents. Each collections agent can be assigned one or more customer pools, which is a query that contains a set of customers. For example, a collections agent might be responsible for customers 4000 through 4500.

## What do you want to do?

Learn more about...

View collections information

Manage and organize collections information for a customer

Send an email message

Write off a transaction

Process a not sufficient funds (NSF) payment

Settle transactions

Reimburse a customer

Reprint a document

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Collections and credit in Accounts receivable](collections-and-credit-in-accounts-receivable.md)

[Case management](case-management.md)

## View collections information

By default, Microsoft Dynamics AX users have access to all records that are shown on the collections list pages. If customer pools have been created, they can be used to filter the records. You can also set up collections agents, which are workers who are set up as users in the **User relations** form. Collections agents can filter information by using the customer pools that are assigned to them, or clear the filter field to view all records.

### View customer information on the Collections list page

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.
    
    The columns on the list page display customer balances and aged amounts by aging period. This information is stored in an aging snapshot. The aging periods are determined by the aging period definition that is used. The aging period definition is taken from the customer pool, if one was specified for the pool query. If the pool does not have an aging period definition, the default aging period definition that is specified in the **Accounts receivable parameters** form is used.

2.  Select a customer.

3.  On the **Collect** tab, click buttons in the **Journals** or **View** groups to view transactions, activities, or cases that are associated with the selected customer account.

4.  On the **Communicate** tab, click buttons in the **Documents** group to view documents or notes that are attached to the selected customer account.

5.  On the **General** tab, click buttons in the **Contacts**, **Setup**, or **Statistics** groups to view additional information. For example, to view average days to pay, click **Customer statistics** and view the **Days, payments** field.

### View collections activities on the Collections activities list page

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections activities**.
    
    The columns on the list page display activities that are associated with customers for whom an aging snapshot has been created. Use activities to track the work that you do related to collections.

2.  To display only open activities, on the Action Pane, click **Show activities** \> **Show open**. To display both open and closed activities, click **Show activities** \> **Show all**.

### View collections cases on the Collections cases list page

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections cases**.
    
    The columns on the list page display information for collections cases. A collections case has a case category type of **Collections**.

2.  To display only open cases, on the Action Pane, click **Show cases** \> **Open**. To display both open and closed cases, click **Show cases** \> **Open and closed**.

### View detailed customer information

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.
    
    The **Collections** form displays transactions and activities for the customer, aged amounts by aging period, and credit limit information.

3.  To view detailed transaction information, on the Action Pane, in the **View** group, click **Transactions** \> **Transactions**.

4.  To view or settle open transactions, on the Action Pane, in the **View** group, click **Transactions** \> **Settle open transactions**.

5.  To view or reverse closed transactions, on the Action Pane, in the **View** group, click **Transactions** \> **Closed transaction editing**.

6.  To view customer account information, on the Action Pane, in the **View** group, click **Customer**.

7.  To the customer’s statement in Excel, on the Action Pane, in the **View** group, click **Statement**.

8.  To view days to pay and other statistical information, on the Action Pane, in the **View** group, click **Statistics**.

Back to top

## Manage and organize collections information for a customer

You can manage and organize collections information for a customer in the **Collections** form.

### Create an action, task, appointment, or event

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  You can create actions, tasks, appointments, and events to represent the work that you do as a collections agent.
    
      - To create an action, which is a unit of work that is completed, on the Action Pane, in the **New** group, click **Action**.
    
      - To create a task, which is a unit of work that is to be done in the future, on the Action Pane, in the **New** group, click **Task**.
    
      - To create an appointment, which is a scheduled meeting, on the Action Pane, in the **New** group, click **Appointment**.
    
      - To create an event, which is something that has already occurred, on the Action Pane, in the **New** group, click **Event**.

4.  Enter the purpose of the activity. This is how the activity will be identified in lists and in the subject line if the activity is synchronized with Microsoft Outlook. Only tasks and appointments can be synchronized with Outlook.

5.  Enter additional information and then click the create button.
    
    The activity is created and is displayed on the **Activities** tab in the form.

### Add transactions and activities to a case

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.
    
    Use cases to organize collections activities and transactions. For example, if you have to collect for three transactions, you can add them to a case, and then manage activities that are related to your collections work for those three transactions together.

3.  To add transactions to a case, select the transactions on the **Open transactions** or **All transactions** tab and then click **Assign to case** in the upper pane.

4.  Select whether to assign the transactions to a new or existing case.
    
      - If this is a new case, select **New case** and then enter a description and select a case category.
    
      - If this is an existing case, select **Existing case** and then select a case ID.

5.  Click **Assign to case**.

6.  To add activities to a case, select the activities on the **Activities** tab and then click **Assign to case** in the lower pane.

7.  Select whether to assign the activities to a new or existing case.
    
      - If this is a new case, select **New case**. Enter a description, select a case category, and select whether to create an activity.
    
      - If this is an existing case, select **Existing case** and then select a case ID.

8.  Click **Assign to case**.

### Update an aging snapshot

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  To update the aged balances for the customer, on the Action Pane, in the **Manage** group, click **Update aging**.
    
    The aging snapshot is recalculated. Amounts are aged as of the current date, based on the due date of the transactions.
    

    > [!NOTE]
    > <P>For information about how to update an aging snapshot for all customers at the same time, see <A href="create-an-aging-snapshot.md">Create an aging snapshot</A>.</P>



### Calculate interest

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the Action Pane, in the **Manage** group, click **Calculate interest**.

4.  Select parameters and then click **OK**. For more information, see [Calculate interest and create interest notes](calculate-interest-and-create-interest-notes.md).

### Change the collections status for a transaction

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select one or more transactions.

4.  Click **Change status**.

5.  Select the collections status for the transaction.
    
      - **Not disputed** – No collections action has occurred for the transaction.
    
      - **Disputed** – The customer has notified you that there is a problem with the transaction. If the **Exclude disputed transactions from fee calculations** check box is selected in the **Accounts receivable parameters** form, collection letters will not be generated for transactions that have this status.
    
      - **Promised to pay** – The customer has agreed to pay the transaction.
    
      - **Resolved** – All problems with the transaction have been solved and no additional collections action is necessary.

6.  Optional: Select the **Create action** check box.

7.  Optional: Select the **Send e-mail message to salesperson** check box. This option is available only if the salesperson has an email address that is set up in the address book.

8.  Click **Change status**.

Back to top

## Send an email message

From the **Collections** form, you can send an email message through Outlook. You can also automatically attach information about selected transactions or customer statements as a Microsoft Excel attachment. For information about how to configure email settings, see [Set up collections](set-up-collections.md).

### Send an email message to a contact or salesperson

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  To send an email message to the contact for the customer, click the icon next to the **E-mail** field in the **Contact** FactBox. If no icon is displayed, the contact record does not have an email address that is set up in the address book.
    
    To send an email message to the salesperson for the sales group that is associated with the customer, click the icon next to the **Salesperson** field in the **Contact** FactBox. If no icon is displayed, the salesperson’s contact record does not have an email address that is set up in the address book.
    
    An email message is created in Outlook.

4.  Compose the message and then click **Send**.

### Send an email message with selected transactions to a customer contact or salesperson

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select one or more transactions.

4.  On the Action Pane, click the **Communicate** tab.

5.  To send an email message to the contact for the customer, click **Transactions to contact**.
    
    To send an email message to the salesperson that is associated with the sales group for the customer, click **Transactions to salesperson**.
    
    An email message is created in Outlook. Information about the transactions is included in an attachment in Excel format.

6.  Compose the message and then click **Send**.

### Send an email message with an attached statement to a contact

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the Action Pane, click the **Communicate** tab.

4.  Click **Statement to contact**.

5.  Select criteria and enter the aging date for the range of transactions to include on the statement.

6.  Optional: Select the **Include settled transactions** check box to include both open and settled transactions, and then enter a starting date for the settled transactions.

7.  Click **Open**.
    
    An email message is created in Outlook. Information about the transactions is included in an attachment in Excel format. The statement includes transactions for the same set of companies that are displayed in the **Collections** form. The statement address is used, if one is specified for the customer.

8.  Compose the message and then click **Send**.

Back to top

## Write off a transaction

If you cannot collect from a customer, you can write off the bad debt. The write-off transaction is created in a general journal and can contain up to three types of journal lines. For more information, see [Collections and credit in Accounts receivable](collections-and-credit-in-accounts-receivable.md) and [About default entries for write-off transactions](about-default-entries-for-write-off-transactions.md). For information about how to set up a journal name for write-off transactions and a write-off account, see [Set up collections](set-up-collections.md).

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select one or more transactions and then click **Write off**.

4.  Enter a write-off date.

5.  Optional: Enter a reason code and comment.

6.  Click **OK**.

7.  A user who is authorized to post transactions can post the journal.

8.  After the write-off transaction is posted, you can settle the transaction. For more information, see “Settle transactions” later in this topic.

Back to top

## Process a not sufficient funds (NSF) payment

If a payment is returned from the bank because of not sufficient funds, you can cancel the payment that is entered in Microsoft Dynamics AX. Depending on the configuration in the **Bank accounts** form for the affected bank account, a charges transaction might be created for the customer.

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select a payment transaction and then click **NSF payment**.
    
    The payment is canceled. If an NSF fee applies for the customer, a charges transaction is created in a payment journal. The fee amount is based on the settings for the automatic charges. The automatic charges that apply for NSF payments are specified by the charges group that is selected in the **Bank accounts** form for the affected bank account.
    

    > [!NOTE]
    > <P>If the payment was created in a legal entity other than the one that you are logged on to, the transactions are created in the legal entity of the payment.</P>



4.  A user who is authorized to post transactions can post the charges transaction.

Back to top

## Settle transactions

In some cases, a payment or credit note is entered for a customer and is not immediately settled with the corresponding invoice. To associate payments with invoices, you can mark transactions for settlement.

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select the transactions to settle with each other and then click **Settle**.
    
    The transactions are marked for settlement in the **Settle open transactions** form.

4.  Click **Update**. The customer’s balance is updated.

5.  Close the **Settle open transactions** form.

Back to top

## Reimburse a customer

If a customer’s balance is equal to or greater than the amount in the **Minimum reimbursement** field in the **Accounts receivable parameters** form, you can reimburse the customer for the balance.

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select one or more transactions.

4.  On the Action Pane, in the **Journals** group, click **Reimburse**.

5.  In the **Reimbursement** form, click **OK**.
    
    The credit amount is transferred to the vendor account of the customer and is processed as a typical payment. If the customer does not have a vendor account, a one-time vendor account is automatically created for the customer.

6.  To view the reimbursement transaction, use the **Reimbursement** form. (Click **Accounts receivable** \> **Reports** \> **Transactions** \> **Payments** \> **Reimbursement**.)

Back to top

## Reprint a document

If you are working on an issue with a customer, you might have to reprint an original document.

1.  Click **Accounts receivable** \> **Common** \> **Collections** \> **Collections**.

2.  Double-click a customer account.

3.  On the **Open transactions** or **All transactions** tab, select a transaction and then click **Reprint**.

4.  In the **Original document** form, click **Print preview**, and then click **OK**.

5.  In the **Journal** form, click **OK**.

6.  In the report form, click the printer icon to print the document.

Back to top

## Find form help

[Collections (form)](https://technet.microsoft.com/en-us/library/hh209726\(v=ax.60\))

## Find related tasks

[Create an aging snapshot](create-an-aging-snapshot.md)

[Calculate interest and create interest notes](calculate-interest-and-create-interest-notes.md)

[Create collection letters](create-collection-letters.md)

[Set up collections](set-up-collections.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

