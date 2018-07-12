---
title: Create and post a statement
TOCTitle: Create and post a statement
ms:assetid: 1cbc6eea-2988-482c-8142-3c55a227b0cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580579(v=AX.60)
ms:contentKeyID: 39519059
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and post a statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In Microsoft Dynamics AX 2012 for Retail, after all transactions from the registers have been uploaded from a retail store, a statement can be created, calculated, and then posted. The statement calculates the total amount of all transactions that have been created since the last store statement was created, within the statement period that you define. The statement also calculates the payment methods that are counted.

The statement is calculated by using the settings for statements and posting in the **Retail parameters** form and the **Stores** form. After the statement is created, you can review the transactions. Then, if the transactions are ready to be posted, you can post the statement. When you post the statement, the system creates accounting entries, updates customer accounts and taxes, and generates sales orders and invoices. Inventory is also updated, so that your point of sale (POS) system always has current inventory information.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Create and calculate the statement

1.  Click **Retail** \> **Journals** \> **Open statements**.

2.  On the **Open statements** list page, on the **Action Pane**, in the **New** group, click **New statement**.

3.  In the dialog box, in the **Store number** field, select the store to create a statement for.

4.  In the **Statements** form, on the **Action Pane**, in the **Function** group, click **Calculate statement**.

5.  Click **Yes** to confirm that you want to calculate the statement.
    
    When a statement is calculated for a specific period, information is updated for the transactions that are included in the statement calculation. These transactions include items that are not on file, blocked items, and blocked customers.
    

    > [!NOTE]
    > <P>In the <STRONG>Stores</STRONG> form, if the <STRONG>Staff/register</STRONG> check box is selected and a value is set in the <STRONG>Statement method</STRONG> field, a separate statement is created based on the value that is selected in the <STRONG>Statement method</STRONG> field when the statement calculation process is run.</P>



## Post a statement

After you calculate a statement, the statement lines that the system has included in the statement are displayed on the **Lines** FastTab in the **Statements** form. Depending on the calculation criteria that were defined for the statement in the **Stores** form, the lines may be displayed by terminal number, by staff ID, or as a total. The lines are always separated by payment method.

In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: The statement lines can also be displayed by shift. In the **Stores** form, if the **Statement method** is set to **Shift** and the **Split by Statement method** check box is selected, a separate statement is created per shift when the statement calculation is run.

The statement lines include the transaction currency, transaction amount, and any difference between the transaction sales amount and the actual counted amount for all payment methods.


> [!NOTE]
> <P>You must assign financial accounts to items, stores, and payment methods before you can post the calculated values in statements to the general ledger, item ledger, customer ledger, and other related tables.</P>



1.  Click **Retail** \> **Journals** \> **Open statements**.

2.  On the **Open statements** list page, select a statement to post.

3.  On the **Action Pane**, in the **Function** group, click **Post statement**.

4.  Click **Yes** to confirm that you want to post the statement.
    
    The statement is posted only if the difference between the transaction sales amount and the actual counted amount is below the maximum posting difference that is defined for the store.

## View a posted statement

After a statement is posted, you can view details about the posted transactions. You can also print the posted statement.

1.  Click **Retail** \> **Inquiries** \> **Posted statements**.

2.  In the **Statement journal** form, select a statement to view.

3.  Click **Reports** \> **Statement** to print the statement.

4.  To view the details about transactions in the posted statement, click individual transactions in the lower pane. Alternatively, you can click **Transactions**, and then select the transaction types to view.

## Configure batch processes to create statements

To run the statement processes for your stores automatically, based on a schedule, configure the batch process for each stage of the statement process:

  - Configure the calculate statement process to calculate the transaction sets for one store or all stores.

  - Configure the post statement process to post the calculated statements.

  - Configure the post inventory process to update the inventory for the stores when the statements are posted.

<!-- end list -->

1.  Click **Retail** \> **Periodic** \> **POS posting** \> **Calculate statement**.

2.  In the **Calculate statement** form, on the **General** tab, in the **Store number** field, enter a store number to configure the calculate statement batch process for a single store or a range of stores. To run the batch process for all stores in your organization, leave the field blank.

3.  Click the **Batch** tab to configure the frequency of the batch process.

4.  Click **Retail** \> **Periodic** \> **POS posting** \> **Post statement**.

5.  In the **Post statement** form, on the **General** tab, in the **Store number** field, enter a store number to configure the post statement batch process for a single store. To run the batch process for all stores in your organization, leave the field blank.

6.  Click the **Batch** tab to configure the frequency of the batch process.

7.  Click **Retail** \> **Periodic** \> **POS posting** \> **Post inventory**.

8.  In the **Transactions** form, on the **General** tab, in the **Store number** field, enter a store number to configure the post inventory batch process for a single store or a range of stores. To run the batch process for all stores in your organization, leave the field blank.
    

    > [!NOTE]
    > <P>To keep your on-hand inventory accurate, you should run this batch job frequently. For example, you can set the frequency to match the frequency with which you run the distribution schedule for job P-0001 for each store.</P>



9.  Click the **Batch** tab to configure the frequency of the batch process.

## See also

[Create and post statements overview](create-and-post-statements-overview.md)

[About statements](about-statements.md)

[Statements (form)](https://technet.microsoft.com/en-us/library/hh597288\(v=ax.60\))

  


