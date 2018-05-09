---
title: Create and post a statement (Retail essentials)
TOCTitle: Create and post a statement (Retail essentials)
ms:assetid: 737de1cf-38a8-4dc2-9d91-469a514b46b1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736897(v=AX.60)
ms:contentKeyID: 62200373
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.RetailStatementListPage
---

# Create and post a statement (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create, calculate, and post a statement after all transactions from the registers have been uploaded from a retail store. The statement calculates the total amount of all transactions that have been created since the last store statement was created, in the statement period that you define. The statement also calculates the payment methods that are counted.


> [!TIP]
> <P>If your store operating hours extend past midnight, you can post statements based on the end of the business day instead of the end of the calendar day.</P>
> <P>In the <STRONG>Stores</STRONG> form, on the <STRONG>Statement/closing</STRONG> FastTab, in the <STRONG>End of business day</STRONG> field, enter the time that the last transaction must be recorded to be included in the statement for the business day. Select the <STRONG>Post as business day</STRONG> check box to post the transactions in the same business day. When the statement is posted, transactions that are recorded in the same business day can be included on the same sales order, even if they occur before and after midnight.</P>
> <P>For more information, see <A href="about-statements-retail-essentials.md">About statements (Retail essentials)</A>.</P>



The statement is calculated by using the settings for statements and posting in the **Retail parameters** form and the **Stores** form. After the statement is created, you can review the transactions. Then, if the transactions are ready to be posted, you can post the statement.

When you post the statement, the system creates accounting entries, updates customer accounts and taxes, and generates sales orders and invoices. Inventory is also updated, so that your point of sale (POS) system always has current inventory information.

## Create and calculate the statement

1.  Click **Retail essentials** \> **Financials** \> **Open statements**.

2.  On the **Open statements** list page, on the **Action Pane**, in the **New** group, click **New statement**.

3.  In the dialog box, in the **Store number** field, select the store to create a statement for, and then click **OK**.

4.  In the **Statements** form, on the **Setup** FastTab, in the **Staff/register** field, select a worker or register.
    

    > [!NOTE]
    > <P>The <STRONG>Statement method</STRONG> field is prefilled with the value from the <STRONG>Statement method</STRONG> field in the <STRONG>Stores</STRONG> form.</P>



5.  On the **Action Pane**, in the **Function** group, click **Calculate statement**.

6.  Click **Yes** to confirm that you want to calculate the statement.
    
    When a statement is calculated for a specific period, information is updated for the transactions that are included in the statement calculation. These transactions include items that are not on file, blocked items, and blocked customers.

## Post a statement

After you calculate a statement, the statement lines that the system has included in the statement are displayed on the **Lines** FastTab in the **Statements** form. Depending on the calculation criteria that were defined for the statement in the **Stores** form, the lines are displayed by register number, by operator ID, or as a total. The lines are separated by payment method.

The statement lines can also be displayed by shift. In the **Stores** form, if the **Statement method** field is set to **Shift** and the **Split by Statement method** check box is selected, a separate statement is created per shift when the statement calculation is run.

The statement lines include the transaction currency, transaction amount, and any difference between the transaction sales amount and the actual counted amount for all payment methods.


> [!NOTE]
> <P>You must assign financial accounts to items, stores, and payment methods before you can post the calculated values in statements to the general ledger, item ledger, customer ledger, and other related tables.</P>



1.  Click **Retail essentials** \> **Financials** \> **Open statements**.

2.  On the **Open statements** list page, select a statement to post.

3.  On the **Action Pane**, in the **Function** group, click **Post statement**.

4.  Click **Yes** to confirm that you want to post the statement.
    
    The statement is posted only if the difference between the transaction sales amount and the actual counted amount is less than the maximum posting difference that is defined for the store.

## View a posted statement

After a statement is posted, you can view details about the posted transactions. You can also print the posted statement.

1.  Click **Retail essentials** \> **Financials** \> **Posted statements**.

2.  In the **Statement journal** form, select a statement to view.

3.  To print the selected statement, click **Reports** \> **Statement**.

4.  To view the details about transactions in the posted statement, click individual transactions in the lower pane. Alternatively, you can click **Transactions** and then select the transaction type to view.

## Configure batch processes to create statements

To run the statement processes for your stores automatically, based on a schedule, configure the batch process for each stage of the statement process:

1.  Configure the statement calculation process.

2.  Configure the statement posting process to post the calculated statements.

3.  Configure the inventory posting process to update the inventory for the stores when the statements are posted.

<!-- end list -->

1.  Click **Retail essentials** \> **Financials** \> **POS posting** \> **Calculate statement**.

2.  In the **Choose organization nodes** form, on the **General** tab, in the **Available organization nodes:** field, select the organization to calculate statements for, and then click **Add \>\>**.

3.  On the **Batch** tab, configure the frequency of the batch process.

4.  Click **OK**. Statements will be calculated according to the frequency that you specified.

5.  Click **Retail essentials** \> **Financials** \> **POS posting** \> **Post statement**.

6.  In the **Choose organization nodes** form, on the **General** tab, in the **Available organization nodes:** field, select the organization to post statements for, and then click **Add \>\>**.

7.  On the **Batch** tab, configure the frequency of the batch process.

8.  Click **OK**. Statements will be posted according to the frequency that you specified.

9.  Click **Retail essentials** \> **Financials** \> **POS posting** \> **Post inventory**.

10. In the **Choose organization nodes** form, on the **General** tab, in the **Available organization nodes:** field, select the organization to post inventory for, and then click **Add \>\>**.

11. On the **Batch** tab, configure the frequency of the batch process.
    

    > [!NOTE]
    > <P>To keep your on-hand inventory accurate, you should run this batch job frequently. For example, you can set the frequency to match the frequency with which you replenish inventory.</P>



12. Click **OK**. Inventory will be updated according to the frequency that you specified.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

