---
title: 'Key tasks: Letter of credit for the export of goods'
TOCTitle: 'Key tasks: Letter of credit for the export of goods'
ms:assetid: 38f64566-5d72-4891-85cf-e237c72fed41
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242208(v=AX.60)
ms:contentKeyID: 36056628
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Letter of credit for the export of goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use letters of credit in the **Accounts payable**, **Accounts receivable**, and **Cash and bank management** modules to set up and transact bank-operated guarantees of payment between vendors and buyers that conduct business across international borders.

This key task topic describes how to work with letters of credit for export transactions, from the required setup to recording the payment and closing the letter of credit. For a detailed description of how to work with letters of credit for import transactions, including import collections, see [Key tasks: Letter of credit or import collection for the import of items](key-tasks-letter-of-credit-or-import-collection-for-the-import-of-items.md).

After the international parties and their banks reach an agreement to process an export transaction by using a letter of credit, you can create a sales order for the letter of credit. In the sales order, you can specify and amend the letter of credit details that you receive from the buyer and advising bank. After you dispatch the shipment, you can record a packing slip that indicates that the materials were dispatched according to the letter of credit agreement. Finally, you can post the invoice, receive payment for the invoice, and settle the transactions for the letter of credit.

## What do you want to do?

Learn more about...

Activate export letters of credit

Set up customer bank accounts

Create a letter of credit sales order

Enter letter of credit details

Amend letter of credit details

Issue the bank document and post the packing slip

Invoice the sales order and mark the documents as submitted

Record the payment for the letter of credit invoice

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About letters of credit and import collections](about-letters-of-credit-and-import-collections.md)

## Activate export letters of credit

You must activate the letter of credit as a bank document before you can initiate transactions that involve the letter of credit.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Ledger** link, and then click the **Bank document** FastTab.

3.  Select the **Enable export letter of credit** check box to activate the letter of credit.

4.  Close the form to save your changes.

Back to top

## Set up customer bank accounts

Customer bank accounts must be specified for letter of credit transactions to be recorded correctly.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer, and then on the **Customer** tab, in the **Set up** group, click **Bank accounts**.

3.  In the **Customer bank accounts** form, enter the appropriate information in the **Bank account** field, the **Bank account number** field, and other fields.

4.  Close the form to save your changes.

Back to top

## Create a letter of credit sales order

You can create a sales order to associate with the letter of credit request.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Click **Sales order** to create a new sales order.

3.  In the **Create sales order** form, in the **Customer account** field, select the customer account.

4.  Click the **General** FastTab.

5.  In the **Bank document type** field, select **Letter of credit**, and then click **OK**.

6.  Add lines and items to your sales order.

7.  Close the form to save your changes.

Back to top

## Enter letter of credit details

After you have created a letter of credit sales order, you can enter the specific details related to the letter of credit.

1.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Export letter of credit/import collection**. Double-click the letter of credit that you want to amend.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click the **Manage** tab, and then click **Letter of credit**. For more information, see [Export letter of credit/import collection (form)](https://technet.microsoft.com/en-us/library/hh208689\(v=ax.60\)).

2.  In the **Bank document number** field, enter the document number specified by the bank.

3.  Click the **Bank details** FastTab, and then in the **Bank document number** field, select the bank that issued the letter of credit.

4.  In the **Advising bank** field, select the advising bank.

5.  Click the **Bank document** FastTab, and then in the **Documentary credit type** and **Documentary credit nature** informational fields, select the appropriate values, if required. The documentary credit type can be **Irrevocable** or **Revocable**. The documentary credit nature can be **Non transferable**, **Transferable**, or **Revolving**.

6.  In the **Expiration date** field, enter an expiration date for the letter of credit sales order.
    
    You can also enter information about tolerance and maturity on this FastTab.

7.  Click the **Lines** FastTab, and then click **Add line** to add shipment details. In the **Amount**, **Actual maturity date**, and **Documents submitted** fields, enter the necessary values.
    

    > [!NOTE]
    > <P>You can click <STRONG>Fetch sales order shipments</STRONG> to display the shipment details that are already specified in the sales order lines or delivery schedule.</P>



8.  Click the **Terms** FastTab, and then specify the shipment terms and payment terms for the letter of credit.
    

    > [!NOTE]
    > <P>You can click <STRONG>Print details</STRONG> to print the letter of credit details. You can click <STRONG>Attachments</STRONG> to attach a document or file to the letter of credit record.</P>



9.  Close the form to save your changes.
    

    > [!NOTE]
    > <P>You must confirm the sales order before you continue. Click <STRONG>Sales and marketing</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Sales orders</STRONG> &gt; <STRONG>All sales orders</STRONG>. On the <STRONG>Sell</STRONG> tab, in the <STRONG>Generate</STRONG> area, click <STRONG>Sales order confirmation</STRONG>, and then click <STRONG>OK</STRONG> in the <STRONG>Confirm sales order</STRONG> window.</P>



Back to top

## Amend letter of credit details

If the sales order details change, you must update the letter of credit details before you submit an invoice. You can modify a confirmed letter of credit only when the letter of credit is in the **Open** status. The bank may charge a fee for amending an existing letter of credit.

1.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Export letter of credit/import collection**. Double-click the letter of credit that you want to amend.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click the **Manage** tab, and then click **Letter of credit**.

2.  Click **Edit**, and then make changes to the letter of credit details. You can change the letter of credit amount or number of shipments, if required.
    

    > [!NOTE]
    > <P>You can modify the shipment details only if the packing slip or invoice has not been posted against that shipment.</P>



3.  In the **Amendment number** field, enter a value to indicate how many times the sales order has been amended.

4.  Close the form to save your changes.

Back to top

## Issue the bank document and post the packing slip

After you have amended your letter of credit transaction information, you can issue the bank document and post the packing slip. When you post a packing slip, you can specify the shipment number to map the shipment with the delivery. You cannot update a packing slip unless the letter of credit amount is equal to the sales order amount.

1.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Export letter of credit/import collection**. Double-click the letter of credit that you want to issue.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click the **Manage** tab, and then click **Letter of credit**.

2.  Click **Issue bank document** to issue the letter of credit.

3.  In the **Sales order** form, select the line for your letter of credit sales order, click the **Pick and pack** tab, and then click **Picking list**.

4.  Click **OK** to post the picking list.

5.  Click **Packing slip**.

6.  Click the **Overview** FastTab, and then in the **Shipment number** field, select a shipment number.

7.  Click the **Parameters** tab, and then in the **Quantity** field, select **All**.

8.  Select the **Print packing slip** check box, and then click **OK** to post the packing slip.

9.  Close the form to save your changes.

Back to top

## Invoice the sales order and mark the documents as submitted

After the packing slip is posted, you can register an invoice for the sales order. You cannot post the invoice unless the letter of credit amount is equal to the sales order amount.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the appropriate record, and then click the **Invoice** tab.

3.  In the **Generate** area, click **Invoice**.

4.  Click the **Overview** FastTab, and then in the **Shipment number** field, select a shipment number.

5.  Click the **Parameters** tab, and then in the **Quantity** field, select **All**.

6.  Select the **Print invoice** check box, and then click **OK** to post the invoice.

7.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Export letter of credit/import collection**. Double-click the letter of credit that you want to amend.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Click the **Manage** tab, and then click **Letter of credit**.

8.  On the **Lines** FastTab, change the value in the **Documents submitted** column to **Yes** for each line item.

9.  Close the form to save your changes.

Back to top

## Record the payment for the letter of credit invoice

After the sales order is invoiced and the documents are marked as submitted, you can receive the payment from the customer and settle the accounts. For more information, see [Receive and enter customer payments](receive-and-enter-customer-payments.md).

Back to top

## Find form help

[Export letter of credit/import collection (form)](https://technet.microsoft.com/en-us/library/hh208689\(v=ax.60\))

## Find related tasks

[Key tasks: Letter of credit or import collection for the import of items](key-tasks-letter-of-credit-or-import-collection-for-the-import-of-items.md)

  


