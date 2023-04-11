---
title: Calculate interest and create interest notes
TOCTitle: Calculate interest and create interest notes
ms:assetid: a6ffdfbe-c0b2-4c3e-8af0-952ed350c785
ms:mtpsurl: https://technet.microsoft.com/library/Gg243052(v=AX.60)
ms:contentKeyID: 36058873
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- interest notes
- interest
- calculating
- finance charges
- finance charge
audience: Application User
ms.search.region: Global
---

# Calculate interest and create interest notes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to calculate interest with or without creating interest notes. You can use the second procedure to create interest notes that have fees but that do not calculate interest.

## Calculate interest and create interest notes

Use this procedure to calculate interest using the **Interest calculation** form, and then create interest notes using the **Interest note** form.

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest calculation**.

2.  Select the types of transactions to calculate interest for and the transaction dates to include.

3.  In the **Use posting profile from** field, select one of the following options:
    
      - **Account** – Use the posting profile that is assigned to the customer account for each interest note.
    
      - **Select** – Use the posting profile that you select in the **Posting profile** field. Be sure to select a posting profile that has the **Interest** check box selected on the **Table restrictions** FastTab and that has an interest code assigned on the **Setup** FastTab in the **Customer posting profiles** form.
    
      - **Transaction** – Use the individual posting profile from transactions on which interest is calculated for each interest note. Transactions that do not have an assigned posting profile will use the posting profile that is specified in the **Ledger and sales tax** area of the **Accounts receivable parameters** form.
        

        > [!NOTE]
        > <P>If the <STRONG>Public sector</STRONG> configuration key is selected, interest will be calculated for each invoice line instead of for the whole invoice.</P>



4.  Click **OK**. Interest is calculated and interest notes are created.

## Create interest notes that have fees but that do not calculate interest

Use this procedure to create interest notes that have a fee but that do not calculate interest. For example, you might charge a fee every time that you send interest notes to remind customers of overdue charges that they owe. This lets you charge fees without also calculating new interest charges.

## Create an interest code and a posting profile

The following setup steps can be omitted if they have already been completed:

1.  Open the **Interest** form and create an interest code that can be used to create interest notes that have a fee but no interest. For more information, see [Set up interest rates for an interest code](set-up-interest-rates-for-an-interest-code.md).
    
    Include the following details:
    
      - Select an interest type of **Single rate**.
    
      - On the **Earnings** tab, in the **Calculate interest every** field, select **Calendar day** and enter 1.
    
      - Select an account in the **Ledger posting debit** field. This identifies the general ledger account where the interest earnings will be posted.
    
      - Leave the **Monthly interest %** field blank.
    
      - Select a fee account where the fee will be posted to.
    
      - Enter the amount of the fee in the **Fee in currency** field.
    
      - On the **Payments** tab, select an account in the **Ledger posting credit** field. This identifies the general ledger account where interest payments will be posted.

2.  Open the **Customer posting profiles** form and create a customer posting profile that can be used to create interest notes that have a fee but no interest. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/library/aa600572\(v=ax.60\)).
    
    Include the following details:
    
      - Do not select the **Interest** check box on the **Table restrictions** FastTab.
    
      - On the **Setup** FastTab, select an account code and a summary account.
    
      - Select the interest code that you created in the **Interest** form.

## Create free text invoices

Use the **Free text invoice** form to create free text invoices for the customers to whom you want to charge a fee. Post the free text invoices that you create. For more information, see [Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\)).

## Create interest notes that have fees but no interest

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest calculation**.

2.  Select the **Invoice** check box on the **General** tab.

3.  Enter from and to dates.

4.  Select **Select** in the **Use posting profile from** field.

5.  Select the posting profile that was created for interest notes that have a fee but no interest.

6.  Click **Select** to select the customers to charge a fee to.

7.  Click **OK** to create the interest notes.

## Print and post the interest notes

1.  Open the **Interest note** form and select the interest notes that you created.

2.  Click **Print** to print the interest notes. Interest notes must be printed before they can be posted.

3.  Click **Post** to post the interest notes. For more information, see [Interest note (form)](https://technet.microsoft.com/library/aa549918\(v=ax.60\)).

## Calculate interest without creating interest notes

Use this procedure to calculate interest without creating interest notes. This is helpful if you want to view the current interest amount without generating an interest note transaction.

1.  Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Customer invoices due today**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Customer invoices past due**.

2.  On the **Action Pane**, on the **Open customer invoice** tab, click **Calculate interest**, and then select one of the following:
    
      - **Customer** – Calculate interest for all open invoices for the selected customer.
    
      - **Invoice** – Calculate interest for only the selected invoice.

3.  Select the types of transactions to calculate interest for and the transaction dates to include.

4.  In the **Use posting profile from** field, select one of the following options:
    
      - **Account** – Use the posting profile that is assigned to the customer account for each interest note.
    
      - **Select** – Use the posting profile that you select in the **Posting profile** field. Be sure to select a posting profile that has the **Interest** check box selected on the **Table restrictions** tab and that has an interest code assigned on the **Setup** FastTab in the **Customer posting profiles** form.
    
      - **Transaction** – Use the individual posting profile from transactions on which interest is calculated for each interest note. Transactions that do not have an assigned posting profile will use the posting profile that is specified in the **Ledger and sales tax** area of the **Accounts receivable parameters** form.
        

        > [!NOTE]
        > <P>If the <STRONG>Public sector</STRONG> configuration key is selected, interest will be calculated for each invoice line instead of for the whole invoice.</P>



5.  Click **OK**. Interest is calculated, but no interest notes are created. The result of the calculation is displayed in the **Unposted interest** field on the list page.
    

    > [!NOTE]
    > <P>The amount that is displayed in the <STRONG>Unposted interest</STRONG> field is temporary. When you close the list page, the value in this field returns to zero.</P>



## Create interest notes

Use this procedure to create interest notes.

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest calculation**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Open customer invoices**. On the **Action Pane**, on the **Open customer invoice** tab, click **New interest note**, and then select **Customer** or **Invoice**.

2.  Enter values in the fields in the **Parameters** section to define the transaction type and the due date limits to create interest note proposal lines for. You can also indicate a round-off value, and specify a posting profile or customer posting profile to determine the interest rate code. For more information, see [Interest calculation (class form)](https://technet.microsoft.com/library/aa600712\(v=ax.60\)).

3.  Click **OK**. The lines that fulfill the criteria that you selected in the **Interest calculation** form are created as interest note proposal lines in the **Interest note** form.

4.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest note**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Open customer invoices**. On the **Action Pane**, on the **Open customer invoice** tab, click **Print or post interest notes**.

5.  Edit the proposal lines in the **Interest note** form.

6.  When you are satisfied, print and post the lines that you want to send as interest notes to customers who have overdue accounts.

7.  To view created, canceled, and posted interest notes, use the **Interest journal** form. (Click **Accounts receivable** \> **Inquiries** \> **Collections** \> **Interest journal**.)

## Print interest notes

To review and print interest notes, select the note, and then click **Print** in the **Interest note** form. (Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest note**.)

## Post interest notes

To post an interest note, select the note, and then click **Post** in the **Interest note** form. (Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest note**.)

## (DNK) Generate and print an interest note that has a payment slip

You can print a payment slip to include the invoice number as the payment ID. To generate and print an interest note that has a payment slip, open the **Interest note** form. (Click **Accounts receivable** \> **Reports** \> **External** \> **Interest note**.) Select a payment slip, and then select one of the following options:

  - **None** – No payment slip is printed. Select this option if the payment amount is in a currency other than Danish kroner (DKK).

  - **FIK 751** – Print an FIK 751 payment slip if you intend to manually write the payment amount and due date on the payment slip.

  - **FIK 752** – Print an FIK 752 payment slip if you intend to use a computer-generated payment slip that has a preprinted payment amount and due date.

## See also

[Interest calculation (class form)](https://technet.microsoft.com/library/aa600712\(v=ax.60\))

[Set up interest calculations](set-up-interest-calculations.md)

[(DNK) Set up a payment slip format for customers](dnk-set-up-a-payment-slip-format-for-customers.md)

  


