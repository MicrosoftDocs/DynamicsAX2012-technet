---
title: Set up permissions and operations
TOCTitle: Set up permissions and operations
ms:assetid: 99d0bf8d-f3e8-479e-8120-3ecf9d07b085
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597187(v=AX.60)
ms:contentKeyID: 39519252
ms.date: 07/29/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up permissions and operations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Every time that a staff member performs an operation in Retail POS, Microsoft Dynamics AX validates that the staff member has permission to perform the operation. This topic explains how to set up POS permission groups and assign operations to permissions.

You can link permissions to operations that can be performed at the point of sale (POS). Operations are the tasks that a staff member can perform. Each permission is typically linked to one operation. However, you can also link a single permission to multiple operations.

Staff members can be assigned to POS permission groups. Permissions for staff members can be modified after the staff members are assigned to a POS permission group.

Note that not all operations are available in all countries/regions.

## Set up a POS permission group

1.  Click **Retail** \> **Setup** \> **POS** \> **Permission groups**.

2.  Press CTRL+N to create a new permission group. Then, enter an ID number and a description for the POS permission group.

3.  On the **Permissions** FastTab, select the check box for each permission to assign.

4.  Specify the maximum discount amounts and percentages.

5.  Select the type of price override to allow.

## Set up operations

1.  Click **Retail** \> **Setup** \> **POS** \> **Operations**.

2.  In the **Operations** form, select an existing operation. Alternatively, click **New** to add a new operation, and then enter an ID number and a name for the operation.

3.  In the **Permission ID** column, select the permissions to link the operation to.

4.  In the **Check user access** column, select the check box to indicate that Microsoft Dynamics AX checks a user's permissions before the operation is performed.

5.  In the **User operation** column, select the check box to indicate that the operation can be added to a button.

6.  In the **Action lookup** column, select one of the following options:
    
      - **Retail product** – The operation can be used only for retail products.
    
      - **Payment method** – The operation can be used only for payment methods.
    
      - **Menu** – The operation can be used only for menus.
    
      - **None** – Use of the operation is not limited.

## Operations

The following table lists the operations that a staff member can perform in Retail POS. The table is sorted alphabetically.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Activate device</strong></p></td>
<td><p>Activate a device with Microsoft Dynamics AX if you are using a mobile device, such as a tablet or smartphone to run Retail POS.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Add affiliation</strong></p></td>
<td><p>Add a preselected affiliation to a transaction. Select the affiliation in the <strong>Button properties</strong> form. The affiliation must have been set up previously in Microsoft Dynamics AX.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Add affiliation from list</strong></p></td>
<td><p>Add an affiliation to a transaction by selecting from a list. The list of affiliations must have been set up previously in Microsoft Dynamics AX.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Add loyalty card</strong></p></td>
<td><p>Enter the customer's loyalty card number. The cashier can also start this operation by swiping a loyalty card.</p>
<p>The loyalty request can be performed at any point during the transaction. Retail POS calculates loyalty points at the end of the transaction.</p>
<p>The number of loyalty points that are awarded for the items in the transaction depends on the setup of the loyalty program in Microsoft Dynamics AX.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Add shipping address</strong></p></td>
<td><p>Add a shipping address for the customer on the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Add to gift card</strong></p></td>
<td><p>Add money to the specified gift card.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank drop</strong></p></td>
<td><p>Record the amount of money that is sent to the bank and other information, such as the number of the bank bag.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank totals verification</strong></p></td>
<td><p>Generate a report that contains all of the bank operations that are performed during the current shift. This operation is performed when closing the shift.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Blank operation</strong></p></td>
<td><p>This operation represents a customizable button that can be programmatically changed by a software developer for any specialized operation that the business requires.</p></td>
</tr>
<tr class="even">
<td><p><strong>Blind close shift</strong></p></td>
<td><p>Set the current shift to blind close, and log off the cashier.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Change password</strong></p></td>
<td><p>Display a form that an employee can use to change his or her password.</p>
<p>This control is available only if Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Change unit of measure</strong></p></td>
<td><p>Change the scanned item's unit of measure.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Clear quantity</strong></p></td>
<td><p>Reset the quantity of an item to 1.</p></td>
</tr>
<tr class="even">
<td><p><strong>Clear salesperson</strong></p></td>
<td><p>This operation is not implemented in this release and may not appear in future releases.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Close shift</strong></p></td>
<td><p>Close the current shift.</p></td>
</tr>
<tr class="even">
<td><p><strong>Copy the bank check</strong></p></td>
<td><p>Generate a report that contains information about all of the operations that are performed on the current register and during the current shift.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Create customer order</strong></p></td>
<td><p>Display a form to create a new customer order or quotation.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer</strong></p></td>
<td><p>Open a form where the cashier can type a customer ID to search for the customer. If a customer is found, the customer is added to the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer account deposit</strong></p></td>
<td><p>Make a payment to a customer's account.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer add</strong></p></td>
<td><p>Open the <strong>Add customer</strong> form, where the cashier can enter information about a new customer. When the information is saved, the new customer is added to the customer list.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer clear</strong></p></td>
<td><p>Clear a customer from the transaction. If any price agreements apply to the customer, prices and discounts in the transaction might change.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer search</strong></p></td>
<td><p>Open a form where the cashier can search for a customer. The cashier can then add the customer to the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer transactions</strong></p></td>
<td><p>Display the transactions for the selected customer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Database connection status</strong></p></td>
<td><p>Switch the database that Retail POS uses from the store database to the register's offline database, or from the offline database to the store database.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Declare start amount</strong></p></td>
<td><p>Declare the amount that is in the cash drawer when the day or shift starts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deposit override</strong></p></td>
<td><p>Override the default deposit for customer orders.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Design mode disable</strong></p></td>
<td><p>Prevent changes to the screen layout of the terminal. The functionality profile of the terminal specifies whether the cashier has access to this operation.</p></td>
</tr>
<tr class="even">
<td><p><strong>Design mode enable</strong></p></td>
<td><p>Allow changes to the screen layout of the terminal. The functionality profile of the terminal specifies whether the cashier has access to this operation.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Disassemble kits</strong></p></td>
<td><p>Disassemble a kit into its component products.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Display total</strong></p></td>
<td><p>Display the balance of the transaction on the customer display.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Edit customer</strong></p></td>
<td><p>Open the <strong>Customer details</strong> form, where you can view or edit information about the customer that has been added to the transaction.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Edit customer order</strong></p></td>
<td><p>Display a form to edit a customer order or quotation.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expense accounts</strong></p></td>
<td><p>Record money that is removed from the cash drawer for occasional expenses.</p></td>
</tr>
<tr class="even">
<td><p><strong>Extended log on</strong></p></td>
<td><p>Assign or remove permission to log on by scanning a bar code or by swiping a card.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Float entry</strong></p></td>
<td><p>Register a float entry to the cash drawer, such as an addition or a change.</p></td>
</tr>
<tr class="even">
<td><p><strong>Gift card balance</strong></p></td>
<td><p>Display the balance of a gift card.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inactivate device</strong></p></td>
<td><p>Inactivate the device in Microsoft Dynamics AX if you’re using a mobile device, such as a tablet or smartphone to run Retail POS.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Income accounts</strong></p></td>
<td><p>Record money that is put into the cash drawer for a reason other than a sale.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory lookup</strong></p></td>
<td><p>Look up on-hand inventory for the current store and other available locations.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice comment</strong></p></td>
<td><p>Enter a comment about the transaction. The comment is saved together with the transaction, and appears on the receipt or invoice.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Issue credit memo</strong></p></td>
<td><p>Issue a central credit memo through Commerce Data Exchange: Real-time Service, and print a copy.</p></td>
</tr>
<tr class="even">
<td><p><strong>Issue gift card</strong></p></td>
<td><p>Issue a gift card through Real-time Service, and print a copy.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Issue loyalty card</strong></p></td>
<td><p>Issue a loyalty card to a customer so the customer can participate in the store’s loyalty program.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Line discount amount</strong></p></td>
<td><p>Enter a discount amount for a line item in the transaction. This operation is used only for discountable items and only in specified discount limits.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Line discount percent</strong></p></td>
<td><p>Enter a discount percentage for a line item in the transaction. This operation is used only for discountable items and only in specified discount limits.</p></td>
</tr>
<tr class="even">
<td><p><strong>Lock register</strong></p></td>
<td><p>Lock the register when the cashier must leave the register. The cashier unlocks the register by logging on.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Log off</strong></p></td>
<td><p>Log off the register, and suspend all sales until the next logon.</p></td>
</tr>
<tr class="even">
<td><p><strong>Loyalty card points balance</strong></p></td>
<td><p>Display the currant balance of points on a customer’s loyalty card.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimize pos window</strong></p></td>
<td><p>Minimize the Retail POS window.</p></td>
</tr>
<tr class="even">
<td><p><strong>Open drawer</strong></p></td>
<td><p>Open the cash drawer when a sale is not made. This operation is recorded in the database.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Override line product tax</strong></p></td>
<td><p>Override the tax on the selected line item, and use a different tax. The new tax must previously be specified in <strong>Retail</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Override line product tax from list</strong></p></td>
<td><p>Override the tax on the selected line item, and use a tax that the cashier selects from a list. The list of taxes must previously be specified in <strong>Retail</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Override transaction tax</strong></p></td>
<td><p>Override the tax on the transaction, and use a different tax. The new tax must previously be specified in <strong>Retail</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Override transaction tax from list</strong></p></td>
<td><p>Override the tax on the transaction, and use a tax that the cashier selects in a list. The list of taxes must previously be specified in <strong>Retail</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Packing slip</strong></p></td>
<td><p>Print a packing slip for a sales order.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay card</strong></p></td>
<td><p>Accept a credit card or debit card as payment. The cashier types the card’s number and expiration date. The cashier can also specify overpayment or underpayment, if the store allows overpayment or underpayment.</p>
<p>The cashier can also start this operation by swiping a credit card or debit card. In this case, Retail POS automatically completes the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay cash</strong></p></td>
<td><p>Accept cash as payment. The cashier can specify that the customer pays the transaction’s total. The cashier can also specify overpayment or underpayment, if the store allows overpayment or underpayment.</p>
<p>If overpayment is allowed, Retail POS displays the amount that exceeds the transaction's total.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay cash quick</strong></p></td>
<td><p>Complete the transaction in &quot;one touch,&quot; provided that the customer pays the exact amount of the transaction’s total in cash.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay check</strong></p></td>
<td><p>Accept a check as payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay corporate card</strong></p></td>
<td><p>This operation is not implemented in this release and may not appear in future releases.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay credit memo</strong></p></td>
<td><p>Accept a credit memo that was issued by the store.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay currency</strong></p></td>
<td><p>Accept payment in various currencies. The cashier selects the payment currency, and Retail POS calculates the transaction’s total in that currency.</p>
<p>The cashier can also specify overpayment or underpayment, if the store allows overpayment or underpayment.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pay customer account</strong></p></td>
<td><p>Charge the transaction to a customer’s account. The cashier can also specify overpayment or underpayment, if the store allows overpayment or underpayment. Retail POS also checks whether the customer is blocked.</p>
<p>If the customer has not already been added to the transaction, the customer can add the customer at this point.</p>
<p>You can also check a customer’s credit before you allow the payment, if credit checking has been set up in <strong>Retail</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pay gift card</strong></p></td>
<td><p>Accept a gift certificate or gift card that was issued by the store.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Accept a loyalty card for payment.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pharmacy prescription cancel</strong></p></td>
<td><p>This operation is not implemented in this release and may not appear in future releases.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pharmacy prescriptions</strong></p></td>
<td><p>This operation is not implemented in this release and may not appear in future releases.</p></td>
</tr>
<tr class="even">
<td><p><strong>Picking and receiving</strong></p></td>
<td><p>Open the <strong>Picking and receiving</strong> form, where you can select a purchase order or transfer order to receive or pick merchandise for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Popup menu</strong></p></td>
<td><p>Select a button grid that is associated with the button. When the button is clicked, Retail POS displays the selected button grid in a separate window.</p></td>
</tr>
<tr class="even">
<td><p><strong>Price check</strong></p></td>
<td><p>Check the price of a product. Retail POS asks for the item number. The cashier can scan the product or search for it.</p>
<p>When the item is found, Retail POS displays the price of the product, and the cashier can add the product to the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Price override</strong></p></td>
<td><p>Override the price of a product, if the product has been set up to allow price overrides. Retail POS displays a number pad that the cashier can use to enter the new price.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print X</strong></p></td>
<td><p>Print an X report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Product comment</strong></p></td>
<td><p>Add a comment to the selected line item in the transaction. The comment is saved together with the transaction and appears on the receipt.</p></td>
</tr>
<tr class="even">
<td><p><strong>Product sale</strong></p></td>
<td><p>Add a product to the transaction. The button must be configured specifically for the product.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Product search</strong></p></td>
<td><p>Search for a product by item number, product description, or category. Search results can be sorted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Recall order</strong></p></td>
<td><p>Open the <strong>Sales order</strong> form, where you can search for a customer, and the customer's sales orders and quotations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Recall transaction</strong></p></td>
<td><p>Recall a suspended transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reprint Z</strong></p></td>
<td><p>Reprint a Z report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Reset password</strong></p></td>
<td><p>Display a form that someone who has password-reset permission can use to reset an employee's password by using a temporary password.</p>
<p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</p></td>
</tr>
<tr class="even">
<td><p><strong>Return product</strong></p></td>
<td><p>Perform a return of individual products. The next scanned product is displayed as a returned product that has a negative quantity and price.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Return transaction</strong></p></td>
<td><p>Perform a return of a whole transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Safe drop</strong></p></td>
<td><p>Perform a safe drop to move money from the register to a safe.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales invoice</strong></p></td>
<td><p>Display information about a sales invoice for a specific customer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Search</strong></p></td>
<td><p>Displays a form where you can search for the following:</p>
<ul>
<li><p>Products, by product name or product number</p></li>
<li><p>Customers, by name, address, or phone number</p></li>
<li><p>Categories, by name</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Search shipping address</strong></p></td>
<td><p>Open a form where you can search for a shipping address.</p></td>
</tr>
<tr class="even">
<td><p><strong>Select hardware station</strong></p></td>
<td><p>Display a list of available hardware stations from the channel profile. You can select a hardware station, and then pair it with a device.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Set quantity</strong></p></td>
<td><p>Change the quantity of a line item in the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Show blind closed shifts</strong></p></td>
<td><p>View a list of shifts that have been blind closed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Show journal</strong></p></td>
<td><p>View the register’s journal. You can then view transactions, reprint receipts, or print invoices.</p></td>
</tr>
<tr class="even">
<td><p><strong>Stock count</strong></p></td>
<td><p>Open the <strong>Stock counting</strong> form, where you can scan or enter bar codes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sub menu</strong></p></td>
<td><p>Select a button grid that is associated with the button.</p>
<p>When the button is clicked, Retail POS displays the selected button grid instead of the existing button grid.</p></td>
</tr>
<tr class="even">
<td><p><strong>Suspend shift</strong></p></td>
<td><p>Suspend the current shift. The shift can be logged on to later.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Suspend transaction</strong></p></td>
<td><p>Suspend a transaction. The transaction can be recalled later.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tender declaration</strong></p></td>
<td><p>Open the <strong>Tender declaration</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Tender removal</strong></p></td>
<td><p>Record the removal of money from the cash drawer.</p></td>
</tr>
<tr class="even">
<td><p><strong>Time clock</strong></p></td>
<td><p>Display the time clock to clock in, clock out, record breaks and lunch breaks, and view time clock entries.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Total discount amount</strong></p></td>
<td><p>Enter a total discount amount. This amount is divided among all items in the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Total discount percent</strong></p></td>
<td><p>Enter a total discount percentage. This percentage is divided among all items in the transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transaction comment</strong></p></td>
<td><p>Add a comment to the transaction. The comment is saved together with the transaction and appears on the receipt.</p></td>
</tr>
<tr class="even">
<td><p><strong>View product details</strong></p></td>
<td><p>View details about the product in the selected line item.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View reports</strong></p></td>
<td><p>View reports about the store’s sales.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
<tr class="even">
<td><p><strong>View time clock entries</strong></p></td>
<td><p>View the time clock entries for all workers at the store.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Void payment</strong></p></td>
<td><p>Void all payment methods that have been applied to the transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Void product</strong></p></td>
<td><p>Void a line item in the transaction. The line item is removed from the transaction’s total and appears marked as voided.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Void transaction</strong></p></td>
<td><p>Void the transaction. Voided transactions are saved in the database and have a voided status.</p></td>
</tr>
<tr class="even">
<td><p><strong>Windows workflow foundation</strong></p></td>
<td><p>Initiate custom operations and workflows.</p></td>
</tr>
<tr class="odd">
<td><p><strong>X report for bank cards</strong></p></td>
<td><p>Generate an X report that contains information about all of the bank card operations that are performed during the current shift. You can perform this operation without closing the shift.</p>
<p>This control is available only if <strong>Retail</strong> in Microsoft Dynamics AX 2012 R3 is installed.</p></td>
</tr>
</tbody>
</table>


## See also

[About setting up staff](about-setting-up-staff.md)

  


