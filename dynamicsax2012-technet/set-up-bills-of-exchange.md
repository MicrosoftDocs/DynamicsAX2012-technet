---
title: Set up bills of exchange
TOCTitle: Set up bills of exchange
ms:assetid: 422241fe-25d5-47d7-b361-0b8041ca4948
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496955(v=AX.60)
ms:contentKeyID: 36056868
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up bills of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A bill of exchange is a written or electronic order from a customer specifying that another party, usually a bank, should pay a stated amount to the company.

When you use a bill of exchange as payment for a sales order invoice or free text invoice, you credit the customer account. That credit is secured by the bill of exchange until the customer pays the bill of exchange to the bank. You will typically settle the invoice with the bill of exchange on the due date. When you receive notification from your bank that the bill of exchange has been honored, you can close the bill of exchange. In Microsoft Dynamics AX, you can use journals to manage bills of exchange.

You can draw the bill of exchange through your bank at either of the following times:

  - On the due date. This is known as *remit for collection*.

  - Before the due date, typically on the discount date specified by the terms of payment that are set up for the customer. When you post the transaction, the discount amount is posted to an expense account. The remaining amount is a liability to you until the bank receives payment from the customer. This is known as *remit for discount*.

## Set up posting profiles for bills of exchange

Use the **Customer posting profiles** form to set up posting profiles to use with bills of exchange, protest bills of exchange, remittances for collection, and remittances for discount:

  - **Bill of exchange** – Use when posting bills of exchange automatically when invoices are settled or when manually posting bills of exchange that are entered in the **Journals** form. To open the **Journals** form, click the **Draw bill of exchange journal** or **Redraw bill of exchange journal** menu item.

  - **Protest bill of exchange** – Use when posting protested bills of exchange automatically or when posting protested bills of exchange that are entered in the **Journals** form. To open the **Journals** form, click the **Protest bill of exchange journal** menu item.

  - **Remit for collection** – Use when posting remittances automatically or when posting collection remittances that are entered in the **Journals** form. To open the **Journals** form, click the **Remittance journal** menu item.

  - **Remit for discount** – Use when posting remittances automatically or when posting discount remittances that are entered in the **Journals** form. To open the **Journals** form, click the **Remittance journal** menu item.

<!-- end list -->

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Create a new customer profile.

3.  In the **Posting profile** and **Description** fields, enter an identifier, such as BOE, and a description for the posting profile, such as Bill of exchange.

4.  Click the **Table restrictions** FastTab. Specify options for the settlement, interest, collection letter, and posting profile to use when closing the transaction. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\)).

5.  Click the **Setup** FastTab, and then in the **Account code** field, select whether to use this posting profile for a single customer account, for a group of customer accounts, or for all customer accounts. In the **Account/Group number** field, select the account number or group number, if necessary.

6.  In the **Summary account** field, select the summary account to post bill of exchange amounts to. This account is debited or credited based on the type of bill of exchange transaction:
    
      - For bills of exchange, this account is debited when a bill of exchange is posted and is credited when a remittance for discount or remittance for collection is posted.
    
      - For protest bills of exchange, this account is debited when a protest bill of exchange is posted.
    
      - For remittances for collection, this account is debited when a remittance for collection is posted.
    
      - For remittances for discount, this account is debited when a remittance for discount is posted.

7.  In the **Settle account** field, select the cash account to post bill of exchange amounts to. This account is debited when a bill of exchange is settled.

8.  In the **Sales tax prepayments** field, select the summary account to post sales tax amounts to when bills of exchange are used for prepayments.

9.  In the **Liabilities for discount account** field, select the account to which you want to post the discount amount for remittances for discount. This account is credited when a remittance for discount is posted.

10. Repeat steps 2 through 9 for the remaining posting profiles.

11. Close the form.

## Set up accounts receivable parameters for bills of exchange

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Ledger and sales tax** link, and then click the **Bill of exchange** FastTab.

3.  In the **Bill of exchange** field, select the default posting profile to use when posting a bill of exchange or a redrawn bill of exchange.

4.  In the **Protest bill of exchange** field, select the default posting profile to use when posting a protested bill of exchange.

5.  In the **Remit for collection** field, select the default posting profile to use when posting a customer bank remittance that is remitted for collection.

6.  In the **Remit for discount** field, select the default posting profile to use when posting a customer bank remittance that is remitted for discount.

7.  Click the **Payment** FastTab, and then select the **Warn if payment proposal uses multiple methods of payment** check box if a message should be displayed when a payment proposal includes more than one method of payment for the same journal line.

8.  Click the **Number sequences** link.

9.  In the **Bill ID** row, select a number sequence to identify bill of exchange payment files.

10. In the **Remittance number** row, select a number sequence to identify remittance files.

11. Close the form.

## Set up journal names for bills of exchange

Create at least five journal names to use for bills of exchange. On the journal voucher form for each bill of exchange journal, enter information about the bill of exchange on the **Bill of exchange** tab. After the bill of exchange journal lines are posted, you can see them in the **Bill of exchange journal** inquiry form and in the **Bills of exchange statistics** form.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Create a new journal name. For more information, see [Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\)).

3.  In the **Journal type** field, select one of the following options:
    
      - **Customer draw bill of exchange** – Create a journal name for the **Draw bill of exchange journal**, and then create a bill of exchange journal in the **Draw bill of exchange journal** form.
    
      - **Customer protest bill of exchange**– Create a journal name for the **Protest bill of exchange journal**, and then create a protest bill of exchange journal in the **Protest bill of exchange journal** form.
    
      - **Customer redraw bill of exchange** – Create a journal name for the **Redraw bill of exchange journal**, and then create a redraw bill of exchange journal in the **Redraw bill of exchange journal** form.
    
      - **Customer bank remittance** – Create a journal name for the **Remittance journal**, and then create a remittance journal in the **Remittance journal** form.
    
      - **Customer settle bill of exchange** – Create a journal name for the **Settle bill of exchange journal**, and then create a settle bill of exchange journal in the **Settle bill of exchange journal** form.

4.  In the **Fees posting** field, specify how remittance fees are posted. This is applicable only if you have selected **Customer bank remittance** in the **Journal type** field.
    
      - **Keep fees in journal** – Retain the fees in the remittance journal. You will post the fees after the payment amounts have been posted.
    
      - **Transfer fees, keep voucher no.** – Post fees by using the same voucher number as the one used for the original payment. The remittance fees are transferred into the journal that is specified for the bank account for the remittance, and the original voucher number is retained.
    
      - **Transfer fees, new voucher no.** – Transfer the remittance fees into the fee journal that is specified for the bank account for the remittance and assign a new voucher number.

5.  Repeat steps 2 through 4 to set up at least one journal name for each journal type.

6.  Close the form.

## Set up methods of payment for bills of exchange

Set up at least one method of payment for bills of exchange. If you do business with more than one bank, set up a method of payment that corresponds to the bill of exchange remittance format required for each bank.

If you do business in more than one country/region, set up a method of payment for the bill of exchange export format that is used in each country/region. For more information, see [Country/region-specific topics for Microsoft Dynamics AX](country-region-specific-topics-for-microsoft-dynamics-ax.md) and [Methods of payment - customers (form)](https://technet.microsoft.com/en-us/library/aa499398\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment.

3.  In the **Method of payment** field, enter an identifier, such as BOE.

4.  In the **Period** field, select the period during which invoices in automatic payment proposals are combined:
    
      - **Invoice** – One payment transfer is created for each invoice.
    
      - **Date** – All invoices for a customer that have the same due date are combined.
    
      - **Week** – All invoices for a customer that have a due date in the same week are combined.
    
      - **Total** – All invoices for a customer are combined into one payment.

5.  In the **Description** field, enter a name or short description for the method of payment.

6.  In the **Grace period** field, enter the number of days that the customer is allowed a cash discount after the specified discount date, if applicable.

7.  In the **Payment status** field, select the payment status required to post a payment that is assigned this method of payment:
    
      - **Sent** – Select to indicate that the bill of exchange document must be printed or that an export file must be created before you can post a payment that uses this method of payment. Your customer does not have to approve the bill of exchange.
    
      - **Approved** – Select to indicate that your customer must approve the bill of exchange before you can post it.

8.  In the **Account type** field, select **Bank**, and then select a bank account.

9.  (FRA) If you are setting up a method of payment for French bills of exchange, click the **General** FastTab, and then in the **Type of draft** field, select **Promissory note**.

10. Click the **File formats** FastTab.

11. In the **Export format** and **Remittance format** fields, select an export format and a remittance format.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> and <STRONG>Remittance format</STRONG> field lists are empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



12. Select the **Create and post draw journal automatically when posting invoices** check box to have a payment (in this case, a bill of exchange) drawn automatically when a sales order invoice or free text invoice is posted. Clear the check box to manually draw bills of exchange in a draw bill of exchange journal.

13. Select the **Run export script** check box to automatically export the invoice and bill of exchange information to a file that you can send to your customer. This applies only if a bill of exchange is to be drawn automatically when you post an invoice. Clear the check box to create a payment file manually for each bank account.

14. In the **Name** field, select a journal name that uses the **Customer draw bill of exchange** journal type to post the payments to a draw bill of exchange journal.
    

    > [!TIP]
    > <P>Be sure to select a journal name with the correct journal type. Other payment journal types are used with different methods of payment, such as checks.</P>



15. Click the **Payment attributes** FastTab, and then select options to include when selecting invoices by using a payment proposal:
    
      - Select the **Third-party bank** check box to include the bank account for the customer.
    
      - Select the **Payment account** check box to include the bank account for the method of payment.
    
      - Select other options, if required by the export format for your bank or country/region.
    

    > [!NOTE]
    > <P>The payment attributes are used only when you select invoices by using a payment proposal.</P>



16. Click **Payment fee setup**, and then enter payment fees for the method of payment. The payment fees that you set up in this form are used as the default entries on the **Payment fee** tab when journal lines are created in a protest bill of exchange journal, remittance journal, or settle bill of exchange journal. For more information, see [Customer payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa557685\(v=ax.60\)).

17. Repeat steps 2 through 16 to set up additional methods of payment, if necessary.

18. Close the forms.

## Set up payment fees for bills of exchange

A payment fee is a charge that is associated with the process of collecting payments from customers. Each payment fee can have multiple payment fee setup lines associated with it. Use setup lines to control how default amounts for payment fees are calculated. For example, you can create setup lines for methods of payment, payment specifications, currencies, and time periods. You can also create setup lines for a percentage or amount based on day intervals, such as an interest percentage based on the length of time a payment is overdue. If the bank charges different fees for different remittance types, such as **Collection** or **Discount**, set up a separate payment fee line for each remittance type.

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Create a new payment fee. For more information, see [Customer payment fee (form)](https://technet.microsoft.com/en-us/library/aa616532\(v=ax.60\)).

3.  Click **Payment fee setup** to open the **Payment fee setup** form, and then enter information for the payment fee line. For more information, see [Customer payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa557685\(v=ax.60\)).

4.  Click the **General** tab, and then in the **Method of payment** field, select a method of payment to use for the payment fee. The method of payment for the payment fee may be different from the method of payment for the payment that the fee is based on.

5.  In the **Payment specification** field, select the payment specification to use for the method of payment.

6.  In the **Remittance type** field, select the type of remittance made to the bank.

7.  Select a currency, and then enter the minimum transaction amount that the fee applies to, the maximum transaction amount, and the dates that the fee is in effect.

8.  Click the **Interval** tab. Enter the required information if the fee amount or percentage should change based on the number of days after the due date that the customer remittance is received.

9.  Repeat steps 2 through 8 to set up additional payment fees, if necessary.

10. Close the forms.

## Set up remittance fees for bank remittance files

You can set up remittance fees that are charged by a bank for each remittance file that is generated. The remittance fees are posted when the remittance has been confirmed and the realized fee amounts are known. These fees are different from payment fees, which are collected from customers and are attached to journal lines.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Create a new bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

3.  Click the **Negotiable instrument** FastTab.

4.  In the **Fee journal** field, select a journal to use for the generated remittance fees.

5.  In the **Collection expenses fee**, **Discount interests fee**, and **Invoice remit fee** fields, enter the amounts charged by the bank for each type of remittance. For each type of fee, select a ledger account to post the fee expenses to.

6.  Close the form.

## Set up document layouts for bills of exchange

Specify the document layout required for each bank account that you will generate printed bills of exchange documents for.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select or create a bank account, and then enter the bank details.

3.  Click the **Setup** tab, and then click **Bill of exchange** to open the **Bill of exchange layout** form and set up the layout. For more information, see [Bill of exchange layout (form)](https://technet.microsoft.com/en-us/library/aa600243\(v=ax.60\)).

4.  Close the forms.

## Set up customers for bills of exchange

For each customer who has agreed to pay by using a bill of exchange, you can set up a default method of payment for bills of exchange.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account, and then click the **Payment defaults** FastTab.

3.  In the **Method of payment** field, select a method of payment that is set up for bills of exchange.

4.  In the **Payment specification** field, select a payment specification, if necessary.
    

    > [!NOTE]
    > <P>(FRA) If you are using a method of payment that uses the <STRONG>French bill of exchange</STRONG> export format, set up an address to include in French bill of exchange payment documents for the customer. Click the <STRONG>Addresses</STRONG> FastTab, and then click <STRONG>More options</STRONG> &gt; <STRONG>Advanced</STRONG>. In the <STRONG>Purpose</STRONG> field, select <STRONG>Payment</STRONG>. Click the <STRONG>Address</STRONG> FastTab, and then enter the address information.</P>



5.  Close the form.

## See also

[Draw a bill of exchange](draw-a-bill-of-exchange.md)

[Remit a bill of exchange](remit-a-bill-of-exchange.md)

[Settle a bill of exchange](settle-a-bill-of-exchange.md)

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Redraw a bill of exchange](redraw-a-bill-of-exchange.md)

[Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\))

[Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\))

[Journal voucher - Bill of exchange journal (form)](https://technet.microsoft.com/en-us/library/aa553272\(v=ax.60\))

[Bill of exchange layout (form)](https://technet.microsoft.com/en-us/library/aa600243\(v=ax.60\))

[Customer bank accounts (form)](https://technet.microsoft.com/en-us/library/aa575695\(v=ax.60\))

[Methods of payment - customers (form)](https://technet.microsoft.com/en-us/library/aa499398\(v=ax.60\))

[Customer payment fee (form)](https://technet.microsoft.com/en-us/library/aa616532\(v=ax.60\))

[Customer payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa557685\(v=ax.60\))

[Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\))

[Payment step process (form)](https://technet.microsoft.com/en-us/library/aa616132\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

