---
title: 'Key tasks: Letter of credit or import collection for the import of items'
TOCTitle: 'Key tasks: Letter of credit or import collection for the import of items'
ms:assetid: 022dec01-5141-4a3f-8936-43b12f7acef1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242097(v=AX.60)
ms:contentKeyID: 36055925
ms.date: 05/21/2016
mtps_version: v=AX.60
---

# Key tasks: Letter of credit or import collection for the import of items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the letter of credit parameters in the **General ledger**, **Accounts payable**, **Accounts receivable**, and **Cash and bank management** modules to set up and transact business functions, such as guaranteeing payments between a vendor and a buyer through a bank.

A letter of credit allows you to:

  - Generate a report of the bank facilities and their uses.

  - Generate the entries for the letter of credit.

  - Print the letter of credit application form.

  - Enter the letter of credit details.

  - Amend the letter of credit.

  - Record letter of credit margin payments.

  - Allocate a margin amount to shipments.

  - Associate a packing slip in a purchase order with the letter of credit shipment details.

  - Process a payment for the invoice.

  - View the cash flow forecast according to the letter of credit.

  - Print various reports and inquiries related to the letter of credit.

  - Generate a vendor statement.

This key task topic describes how to work with letters of credit, from the required setup to posting the invoice to make a payment.

Before you use the **General ledger parameters** form to activate the letter of credit, select the **Bank document** check box in the **Configuration** form. After you activate the letter of credit parameters, you must create the facility types, the facility groups, and the facility agreement.

After you create an agreement, you can create a purchase order for a letter of credit. In the purchase order, you can specify the letter of credit details. After you receive the shipment, you can allocate the margin amount to a particular shipment or to all the shipments related to the letter of credit. The last step for the letter of credit is to post the invoice and process the payment for the invoice.

## What do you want to do?

Learn more about...

Activate the letter of credit as a bank document

Set up the bank facilities and posting profiles

Create a bank facility agreement

Set up vendor bank accounts

Create a purchase order and enter the letter of credit details

Amend the letter of credit details

Post a margin payment for a letter of credit

Allocate the margin amount to the shipment

Post a packing slip and an invoice for the purchase order

Make a payment for the invoice

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About letters of credit and import collections](about-letters-of-credit-and-import-collections.md)

## Activate the letter of credit as a bank document

You must activate the letter of credit as a bank document before you initiate transactions that involve letters of credit.

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  On the **General** link, click the **Bank document** FastTab.

3.  Select the **Enable import letter of credit** check box to activate the letter of credit.

4.  Close the form to save your changes.

Back to top

## Set up the bank facilities and posting profiles

You can set up bank facility types and bank facility groups in the **Bank facilities** form. After the bank posting profile is set up, you can create facility agreements.

1.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank facilities**.

2.  On the **Facility groups** link, click **New** to create a new bank facility group.

3.  In the **Facility group** and **Description** fields, enter the bank facility group name and description.

4.  Click the **Facility types** link, and then click **New** to create a new facility type.

5.  Enter a unique code in the **Facility type** field, and then in the **Facility group** and **Facility nature** fields, select the group and nature of the bank facility.

6.  Close the form to save your changes.

7.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank documents posting profile**.

8.  In the **Settle account** field, select the main account for settlement. This account is used when calculating the cash flow forecast.

9.  In the **Charges account** field, select the account for expense transactions.

10. In the **Margin account** field, select the account for the margin transaction. This account is debited when the opening margin is posted and credited when the payment is posted.
    

    > [!NOTE]
    > <P>A margin is an advance payment to the bank that is adjusted by the bank when the final settlement is made by the buyer.</P>



11. Close the form to save your changes.

Back to top

## Create a bank facility agreement

You must create bank facility agreements that record various facilities provided by the bank. Bank documents can be used in transactions only after facility agreements are created. The bank assigns a limit for the letter of credit, which is recalculated every time a letter of credit transaction is recorded.

When a facility agreement ends, you can create a new version of the agreement, with new starting and ending dates, by extending the old agreement.

1.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank facility agreements**.

2.  Press CTRL+N to create a new line.

3.  In the **Agreement number**, **Bank account**, **Start date**, and **End date** fields, enter the agreement number according to the agreement with the bank, the account number at the issuing bank, and the validity period of the agreement.

4.  On the **General** FastTab, click **Add line**.
    

    > [!NOTE]
    > <P>Facility agreements cannot have overlapping dates. For example, if an agreement extends from January 01, 2011 to August 31, 2011, you cannot create another facility agreement that begins or ends within that period.</P>



5.  In the **Facility type** and **Limit** fields, select the facility type, and then enter the facility amount that was negotiated with the bank. The **Amount used** field displays the amount that is currently used for the letter of credit.

6.  Close the form to save your changes.

7.  In the **Bank facility agreements** form, select the facility agreement that is no longer active, and then click **Extend** to extend the term of the agreement.

8.  In the **New agreement number** and **End date** fields, enter the new agreement number as assigned by the bank and the desired ending date of the agreement, and then click **Extend**.
    

    > [!NOTE]
    > <P>The value in the <STRONG>Start date</STRONG> field of the extended agreement is the day after the selected agreement’s end date. The <STRONG>Amount used</STRONG> field is set to zero because this is a newly created agreement.</P>



9.  Close the form to save your changes.

Back to top

## Set up vendor bank accounts

Vendor bank accounts must be specified for the letter of credit transactions to be recorded appropriately.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor, and then on the **Vendor** tab, in the **Setup** group, click **Bank accounts**.

2.  In the **Vendor bank accounts** form, enter the **Bank account** and **Bank account number** information, along with any other details.

3.  Close the form to save your changes.

Back to top

## Create a purchase order and enter the letter of credit details

A letter of credit is associated with a purchase order to process vendor transactions with minimal manual intervention. The involved parties are the buyer (applicant), the seller (beneficiary), the issuing bank (buyer’s bank), and the advising bank (beneficiary’s bank). When a company is both the buyer and applicant for the letter of credit, the letter of credit is called an import letter of credit. Purchase orders that are associated with letters of credit are not considered for summary invoicing.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Click **Purchase order** to create a new purchase order.

3.  In the **Create purchase order** form, select the vendor account in the **Vendor account** field.

4.  In the **Bank document type** field, select **Letter of credit**, and then click **OK**.
    

    > [!NOTE]
    > <P>When the <STRONG>Bank document type</STRONG> field is set as <STRONG>Letter of credit</STRONG>, the purchase order is displayed in the list of letters of credit in the <STRONG>Cash and bank management</STRONG> module. Because the letter of credit details have not yet been added, the <STRONG>Require update</STRONG> check box on the <STRONG>Cash and bank management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Letters of credit</STRONG> &gt; <STRONG>Import letter of credit/import collection</STRONG> list page is selected.</P>



5.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Import letter of credit/import collection**. Double-click the order number associated with the letter of credit to be updated.
    
    \-or-
    
    In the **Purchase order** form, click the **Manage** tab, and then click **Letter of credit / import collection**. For more information, see [Letter of credit / import collection (form)](https://technet.microsoft.com/en-us/library/hh209538\(v=ax.60\)).

6.  Click the **General** FastTab, and in the **Bank account** field, select the bank that assigns the letter of credit. In the **Bank document number** field, enter the document number specified by the bank.

7.  Click the **Lines** FastTab, and then click **Add line** to add shipment details. Enter the necessary values in the **Amount**, **Expected maturity date**, **Actual maturity date**, and **Document status** fields.
    

    > [!NOTE]
    > <P>Click <STRONG>Fetch purchase order shipments</STRONG> to view the shipment details that are already specified in the purchase order lines or delivery schedule. Click <STRONG>Shipment margin transactions</STRONG> to open the <STRONG>Shipment margin</STRONG> form to view the shipment margin transactions for the selected shipment.</P>



8.  Optional: Click the **Bank document** FastTab, and then specify details in the **Documentary credit type**, **Documentary credit nature**, and **Expiration date** fields. A letter of credit can be either **Irrevocable** or **Revocable**. It can be **Non transferable**, **Transferable**, or **Revolving** in nature.

9.  Optional: Click the **Bank details** FastTab, and then enter the advising bank details in the **Advising bank** and **Date of issue** fields.

10. Optional: Click the **Terms** FastTab, and then specify the shipment terms and payment terms for the letter of credit.

11. Optional: Click the **Insurance** FastTab to specify details of the insurance request submitted by the vendor in the **Insurance status**, **Insurance vendor number**, and **Insurance number** fields.

12. Click **Confirm** to confirm the letter of credit. The **Facility balance** field is updated based on the value in the **LC / IC Amount** field. The **Amount used** field in the **Bank facility agreement details** form is updated with the letter of credit amount.
    
    The letter of credit details are confirmed only if the line amounts total equals the **LC / IC Amount** and it does not exceed the amount available for the particular facility type.

13. Click **Print application** to print the letter of credit application form to be submitted to the bank.

Back to top

## Amend the letter of credit details

If the purchase order details change, you must update the letter of credit details before you invoice the purchase order completely. You can modify a confirmed letter of credit only when the letter of credit has a **Confirmed** status. The bank may charge a fee for amending an existing letter of credit.

1.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Import letter of credit/import collection**. Double-click the import letter of credit or import collection to be amended.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and then on the **Manage** tab, click **Letter of credit / import collection**.

2.  Click **Amend**, and then amend the letter of credit details. You can change the letter of credit amount or number of shipments, if required.
    

    > [!NOTE]
    > <P>You can edit the shipment details only if the packing slip or invoice is not posted. If you delete a shipment line detail for which the margin was already allocated, the allocated amount is reversed to an unallocated amount in the <STRONG>Letter of credit margin transactions</STRONG> form.</P>



3.  Click **Confirm** to confirm the changes made to the letter of credit. Changes must be confirmed to be saved as amendments. Each confirmed amendment results in a new version of the letter of credit. This helps to track the revision history of the letter of credit. If shipment line details are changed, the letter of credit details are confirmed only if the total shipment amount does not exceed the letter of credit amount.

4.  Click **Inquiries** to open the **Letter of credit/import collection history** form, and then view the amendment history of the letter of credit.

5.  Close the forms to save your changes.

Back to top

## Post a margin payment for a letter of credit

When you receive letter of credit advice from the bank, you can check the margin collected by the bank and post it in a **General journal** of the type **Daily**. To post the transaction against the appropriate posting profile, the **Transaction type** field must be selected as **Margin**.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select a daily journal, and then click **Lines** to open the **Journal voucher** form.

4.  In the **Debit** field, enter the margin amount collected by the bank.

5.  Click the **Payment** tab, and then in the **Transaction type** field, select **Margin**. The values in the **Account type**, **Account**, **Offset account type**, and **Offset account** fields are displayed according to the posting profile.

6.  In the **Letter of credit / import collection** field, select the bank document number associated with the letter of credit.

7.  Click **Post** \> **Post** to post the journal.

8.  Close the form to save your changes. The margin amount for the letter of credit is recorded in the **Letter of credit margin transactions** form.

Back to top

## Allocate the margin amount to the shipment

To adjust the margin amount at the time of invoicing (partially or completely), the margin amount must be allocated to each shipment. You can use the **Letter of credit margin transactions** form to allocate the margin amount across shipments for a letter of credit.

1.  Click **Cash and bank management** \> **Common** \> **Letters of credit** \> **Import letter of credit/import collection**. Double-click the import letter of credit or import collection for which the margin amount must be allocated to the shipment.

2.  Click **Bank document margin** to open the **Letter of credit margin transactions** form.

3.  Select the margin amount line to be allocated, and then click **Allocate to shipment** to open the **Allocate on** drop dialog.

4.  In the **Allocation type** field, select **Dedicated** to allocate the margin amount to a particular shipment or select **Distributed** to allocate the margin amount proportionally among all shipments that are not invoiced. Select the shipment number in the **Shipment number** field.
    

    > [!NOTE]
    > <P>You can allocate margin amounts only if the value in the <STRONG>Balance</STRONG> field is greater than zero and the shipment that you are allocating to is not already invoiced. If you select <STRONG>Distributed</STRONG> in the <STRONG>Allocation type</STRONG> field, the shipment share of the margin amount is calculated as following:</P>
    > <P>Shipment Share = Margin amount multiplied by (Shipment amount/Letter of credit amount).</P>



5.  Click **OK** to return to the **Letter of credit margin transactions** form. The **Allocated** field is updated with the margin amount that was allocated, and the status is updated as **Posted**.

6.  Close the form to save your changes.

7.  In the **Letter of credit / import collection** form, click the **Lines** FastTab, and then click **Shipment margin transactions** to open the **Shipment margin** form and view the margin amount allocated to a shipment.

Back to top

## Post a packing slip and an invoice for the purchase order

After the margin is allocated to the shipment, you can post a packing slip and register an invoice for the purchase order. When you post a packing slip, you can specify the shipment number to map the shipment with the delivery. You cannot post the invoice or update a packing slip unless the letter of credit shipment line amount either equals the invoice amount or the shipment variation is within the tolerance limit specified in the **Tolerance percentage** field in the **Letter of credit / import collection** form.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order for the letter of credit that must be invoiced, and then double-click the purchase line to open the **Purchase order** form.

3.  Click the **Receive** tab, and then click **Product receipt** to open the **Posting product receipt** form. Select the shipment number in the **Shipment number** field, and then click **OK** to post the packing slip.

4.  Click the **Invoice** tab, and then click **Invoice** to open the **Vendor invoice** form. Select the shipment number in the **Shipment number** field, and then click **OK** to post the invoice. The invoice amount must be equal to the shipment amount. The shipment status is set as **Invoiced**.

5.  Close the forms to save your changes.

Back to top

## Make a payment for the invoice

After the purchase order is invoiced, you can make the payment and settle the accounts. The payment for the letter of credit must be equal to the amount due minus the margin amount because the margin amount is already collected by the bank. The payment must be within the tolerance limit for the letter of credit.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Name** field, select a daily journal, and then click **Lines** to open the **Journal voucher** form.

4.  Enter the required information.

5.  Click **Functions** \> **Settlement** and select the invoice. Click the **Payment** tab and select the letter of credit.

6.  In the **Letter of credit / import collection** and **Shipment number** fields, select the bank document number associated with the letter of credit and the shipment number.

7.  Click **Post** \> **Post** to post the journal. After the settlement invoice is posted, the letter of credit status is set as **Closed**.


> [!NOTE]
> <P>The bank account is credited with the amount. The shipment status is set as <STRONG>Paid</STRONG>. You can close a letter of credit only after all the lines are settled against payments.</P>



Back to top

## Find related tasks

[Letter of credit / import collection (form)](https://technet.microsoft.com/en-us/library/hh209538\(v=ax.60\))

[About letters of credit and import collections](about-letters-of-credit-and-import-collections.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

