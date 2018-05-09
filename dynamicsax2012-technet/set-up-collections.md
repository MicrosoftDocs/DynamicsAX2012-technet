---
title: Set up collections
TOCTitle: Set up collections
ms:assetid: c3c9dcda-9cca-4a80-bab2-032615dbc36e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242837(v=AX.60)
ms:contentKeyID: 36059289
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- agent
- snapshot
- aging
- write off
- writeoff
- write-off
- agents
- period
- periods
- pool
- pools
- aged
- trial balance
- collection agent
- collections agents
- customer pool
- collection agents
- collections agent
- customer pools
- reimburse
- teams
- team
- reimbursement
---

# Set up collections 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following tasks to prepare to use collections functionality. For more information, see [Collections and credit in Accounts receivable](collections-and-credit-in-accounts-receivable.md).

1.  Set up aging period definitions

2.  Create an aging snapshot

3.  Optional: Set up customer pools

4.  Optional: Create a collections team

5.  Set up a collections case category

6.  Set up journal names (settlement, write-off, and NSF)

7.  Set up a reason code for write-off transactions

8.  Set up a folder for email attachments and create email templates

9.  Set up Accounts receivable parameters for collections

10. Optional: Set up collections agents

11. Set up a write-off account

12. Set up NSF information for bank accounts

13. Set up Outlook settings for users of the **Collections** form

14. Set up email settings for collections customer contacts

15. Set up email settings for salespeople

The tasks are described in the following sections.

## Set up aging period definitions

Set up an aging period definition, which defines the columns that appear on the **Collections**, **Collections activities**, and **Collections cases** list pages. It also defines the periods that are shown in the **Collections** form. If a customer pool is set up, the aging period definition for the pool is used. If no pools are set up, the default aging period definition that is specified in the **Accounts receivable parameters** form is used. If no default aging period definition is specified, the first aging period definition in the **Aging period definitions** form is used.

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Aging period definitions**.

2.  Enter a name for the aging period definition.

3.  On the **Periods** FastTab, create aging periods. For more information, see [Aging period definitions (form)](https://technet.microsoft.com/en-us/library/aa634713\(v=ax.60\)).

4.  Close the form.

## Create an aging snapshot

Create aging snapshot records for all customers or for the customers in a customer pool. Aging snapshot information is shown on the **Collections** list page and in the **Collections** form. You must create an aging snapshot before you can use the list page. The list page shows information only for customers for whom an aging snapshot has been created. For more information, see [Customer aging snapshot (form)](https://technet.microsoft.com/en-us/library/hh242719\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Customer aging snapshot**.

2.  Select an aging period definition.

3.  Optional: Select a pool.

4.  Select the type of date in the transaction records to use to assign transactions to aging periods.

5.  Select a date to base the aging snapshot calculations on. For more information, see [Customer aging snapshot (form)](https://technet.microsoft.com/en-us/library/hh242719\(v=ax.60\)).
    

    > [!NOTE]
    > <P>If the aging snapshot process will run as part of a batch, select <STRONG>Today's date</STRONG> in the <STRONG>Aging as of</STRONG> field. Otherwise, the aging snapshot is always created for the same date.</P>



6.  Optional: Click the **Company range** tab and select the legal entities to include in the aging snapshot.

7.  Optional: Click the **Batch** tab and set up batch processing.

8.  Click **OK**.

## Optional: Set up customer pools

You can set up customer pools to represent groups of customers. You can use customer pools as filters for the customer information that is displayed on collections list pages, in the **Collections** form, or when you create aging snapshots. For more information, see [Customer pools (form)](https://technet.microsoft.com/en-us/library/hh227560\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Customer pools**.

2.  Enter a pool ID and description.

3.  Select a pool type.

4.  Click **Select pool criteria** to select the query criteria, and then click **OK**.

5.  Click **Preview customer pool** to preview the customers in the pool.
    

    > [!NOTE]
    > <P>Only customers for whom an aging snapshot has been created will appear in the list.</P>



6.  Close the **Customer pools** form.

7.  Create a new aging snapshot that includes the customer pool. For more information, see [Create an aging snapshot](create-an-aging-snapshot.md).

## Optional: Create a collections team

If multiple people in your organization do collections work, you can set up a collections team. You can select the team in the **Accounts receivable parameters** form. If you do not create a collections team, one will be created automatically when you set up collections agents in the **Collections agent** form.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Teams**.

2.  In the **Teams** form, click **Team types**.

3.  Click **New** and enter a name for the team type, such as Collections.

4.  Select the **Require team members to be Microsoft Dynamics AX users** check box, and then select the people who are allowed in this type of team. This can include **Employee**, **Contractor**, or both.

5.  Close the form. Close and reopen the **Teams** form.

6.  In the **Teams** form, click **New** and enter a name for the team, such as Collections.

7.  Select the team type that you created in step 3.

8.  Enter a description for the team and select the **Active** check box.
    
    You do not have to add team members now. Instead, you will add team members in the **Collections agent** form.

9.  Close the form.

## Set up a collections case category

If you will organize your collections work by using cases, set up a case category with the category type of **Collections**. This is required only if you want to use the case function in the **Collections** form. For more information about cases, see [Case management](case-management.md).

1.  Click **Sales and marketing** \> **Setup** \> **Cases** \> **Case categories**.

2.  Click **New**, and then click **Case category**.

3.  Enter a name and description for the case category.

4.  Select **Collections** as the category type.

5.  On the **Activities** FastTab, specify options for a default activity, a default follow-up activity, or both.

6.  Optional: On the **General** FastTab, enter additional information about the case category. For more information, see [Case categories (form)](https://technet.microsoft.com/en-us/library/hh209319\(v=ax.60\)).

7.  Close the form.

## Set up journal names (settlement, write-off, and NSF)

Set up journal names to use when transactions are processed in the **Collections** form. This includes settling a transaction, writing off a transaction, or processing a not sufficient funds (NSF) payment.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create three journal names that have the following properties. Click **New** to create each journal name. For more information, see [Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\)).
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Description</strong></p></th>
    <th><p><strong>Journal type</strong></p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Settlement</p></td>
    <td><p><strong>Customer payment</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>Write-off</p></td>
    <td><p><strong>Daily</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>NSF</p></td>
    <td><p><strong>Customer payment</strong></p></td>
    </tr>
    </tbody>
    </table>


3.  Close the form.

## Set up a reason code for write-off transactions

Set up a default reason code to use when transactions are written off in the **Collections** form.

1.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer reasons**.

2.  Click **New** to create a reason code.

3.  Enter a reason code and a default comment.

4.  Select the **Customer** check box.

5.  Close the form.

## Set up a folder for email attachments and create email templates

If you will send email messages that have Microsoft Excel attachments by using the **Collections** form, set up a folder for email attachments. You can also create email templates. The folder for email attachments is required, but the email templates are optional. For more information about email templates and variables, see [E-mail templates (form)](https://technet.microsoft.com/en-us/library/aa577102\(v=ax.60\)).

1.  Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

2.  In the **Allow embedded data and attached files from** field, enter the path of a server location where email attachments are stored. When you send an email message that has an attached customer statement, the attachment is stored in this location.

3.  Close the **E-mail parameters** form.

4.  Click **Organization administration** \> **Setup** \> **E-mail templates**.

5.  Optional: Create three email templates for the following purposes:
    
      - Message to customer contact
    
      - Message to customer contact with attached statement
    
      - Message to salesperson contact
    
    For each template, follow these steps:
    
    1.  Enter an email ID and description.
    
    2.  Select a default language.
    
    3.  Enter a sender name and sender email address. These fields are required; however, they will not be used when you send email messages in the **Collections** form. The sender name and sender email address will be that of the person who is using the **Collections** form.
    
    4.  In the lower pane, select a default language for the template.
    
    5.  Enter the subject. This text will appear in the subject line of email messages that are created by using this template.
    
    6.  Click **Template**, and then enter the message body text. Save the template and close the form.
        
        You can use the following variables in the message body text:
        
          - %CustomerAccount% – The customer account that is displayed in the **Collections** form.
        
          - %CustomerName% – The customer name that is displayed in the **Collections** form.

6.  Close the **E-mail templates** form.

## Set up Accounts receivable parameters for collections

Set up Accounts receivable parameters that are related to collections.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Collections**.

3.  Optional: Select the **Exclude disputed transactions from fee calculations** check box to prevent collection letters from being generated for transactions that are disputed.

4.  In the **Aging period definition** field, select a default aging period definition to use in the **Collections** form and on the **Collections** list page.

5.  Optional: In the **Team** field, select a team. You can assign collections agents to the collections team in the **Collections agent** form.

6.  In the **Write-off journal** field, select a journal name to use for write-off transactions.

7.  In the **Reason code** field, select a default reason code to use for write-off transactions.

8.  Optional: Select the **Separate sales tax** check box to create separate journal entries for sales tax amounts that are written off. This can help you restate your sales tax liability because of the amount that was written off.

9.  Optional: On the **E-mail template** FastTab, select email templates to use for each type of message.

10. Close the form.

## Optional: Set up collections agents

If multiple people in your organization do collections work, you can set up collections agents. A collections agent is worker who is set up as a user in the **User relations** form. You can assign customer pools, which are customer queries, to collections agents to help the agents organize their work. The collections agents are added to the team that is selected in the **Accounts receivable parameters** form. If a team is not selected in that form, a new team named **Collections** is automatically created and the collections agents are added to that team.

1.  Click **System administration** \> **Common** \> **Users** \> **User relations**.

2.  Click **New** and select a worker. The worker can be either an employee or a contractor.

3.  Select the user ID that corresponds to the worker.

4.  Optional: Repeat steps 2 and 3 for additional workers, and then close the form.

5.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Collections agents**.

6.  Click **Add team members**.

7.  Select a team member and then click **Add**.

8.  Optional: Repeat steps 6 and 7 for additional collections agents.

9.  Optional: In the **Collections agent** form, assign one or more customer pools to the collections agents. For more information, see [Collections agents (form)](https://technet.microsoft.com/en-us/library/hh209479\(v=ax.60\)).

10. Close the form.

## Set up a write-off account

Set up a write-off account that is used for the general ledger write-off entry when a transaction is written off. For more information, see [About default entries for write-off transactions](about-default-entries-for-write-off-transactions.md).

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Select a posting profile and then click the **Setup** FastTab.

3.  In the **Write-off account** field, select the ledger account to post write-off transactions to.

4.  Repeat steps 2 and 3 for the remaining posting profiles that can be used for posting write-off transactions.

5.  Close the form.

## Set up NSF information for bank accounts

Use this procedure to specify information that will be used when you process NSF payments in the **Collections** form.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Double-click a bank account to open the **Bank accounts** form.

3.  On the **Action Pane**, click **Edit Record**, and then click the **Currency management** FastTab.

4.  In the **Charges group** field, select the charges group to use for fees that you charge to your customer for NSF payments.

5.  In the **NSF payment journal** field, select the payment journal name to use when canceling a payment that has been returned because of not sufficient funds.

6.  Close the form.

## Set up Outlook settings for users of the Collections form

Before workers can create activities or send email messages by using the **Collections** form, you must verify that the **Microsoft Outlook synchronization** configuration key is selected and that Outlook synchronization is set up for the worker. For more information about Outlook synchronization, see [Integrating with Microsoft Outlook](integrating-with-microsoft-outlook-and-microsoft-exchange-server.md). For more information about how to create a worker, see [Key tasks: Workers](key-tasks-workers.md).

## Set up email and address settings for collections customer contacts

Set up email addresses for customer contacts if you want to send email messages to those contacts from the **Collections** form. The collections contact is used as the default contact in the **Collections** form. You can set up a statement address for the customer if statements should have a different address from the primary address.


> [!NOTE]
> <P>If a collections contact for a customer is not specified, the primary contact for the customer is used. If a primary contact is not specified, email messages will be sent to the first address listed in the <STRONG>Contacts</STRONG> form.</P>



1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account to open the **Customers** form.

3.  On the **Action Pane**, click **Edit**.

4.  Optional: On the **Addresses** FastTab, click **Add**, and then enter a statement address. In the **Purpose** field, select **Statement**, enter address information, and then click **OK**.

5.  On the **Credit and collections** FastTab, in the **Collections contact** field, select the person in the customer organization who works with your collections agent. This contact is used as the default contact in the **Collections** form, and is the person to whom email messages are sent.

6.  Press CTRL+S.

7.  Right-click in the **Collections contact** field and select **View details**.

8.  In the **Contacts** form, click the **Contact information** FastTab.

9.  If the contact does not have an email address specified, click **Add** to add an address.

10. Select a type that uses the **E-mail address** communication method.

11. In the **Contact number/address** field, enter the primary email address for the contact. If there is no primary email address, the first email address that is listed will be displayed.

12. Repeat steps 1 through 11 for the remaining customer contacts.

13. Close the forms.

## Set up email settings for salespeople

Set up email addresses for salespeople if you want to send email messages to salespeople from the **Collections** form. Set up an email address for each sales representative in each commission sales group. The sales representative who has the **Contact** check box selected is the default salesperson to whom email messages are sent. If a sales representative is not specified, the primary salesperson for the customer organization is used. If a primary salesperson is not specified, email messages will be sent to the first salesperson listed in the form.

1.  Click **Sales and marketing** \> **Setup** \> **Commissions** \> **Sales groups**.

2.  Select a commission sales group and then click **Sales rep.**

3.  For a sales representative who has the **Contact** check box selected, right-click in the **Name** field and select **View details**.

4.  In the **Address book** form, click the **Contact information** tab.

5.  If the worker does not have an email address specified, click **Add** to add an email address.

6.  Enter a brief description of the new address. In the **Type** field, select **E-mail address**.

7.  In the **Contact number/address** field, enter the email address for the salesperson.

8.  Click **More options** \> **Advanced**.

9.  In the **Purpose** field, select a purpose. Click **Close** to close the **Edit contact information** form, and then click **Close** to close the **Address book** form.

10. Repeat steps 1 through 9 for the remaining salesperson contacts.

11. Close the forms.

## See also

[Key tasks: Collections](key-tasks-collections.md)

[Set up interest calculations](set-up-interest-calculations.md)

[Set up interest rates for an interest code](set-up-interest-rates-for-an-interest-code.md)

[Set up a collection letter sequence](set-up-a-collection-letter-sequence.md)

[Control posting and printing of collection letters](control-posting-and-printing-of-collection-letters.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

