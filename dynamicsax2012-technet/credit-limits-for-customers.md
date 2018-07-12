---
title: Credit limits for customers
TOCTitle: Credit limits for customers
ms:assetid: 51bf672e-e965-4dad-b5cf-46395d685aa9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ155667(v=AX.60)
ms:contentKeyID: 47574347
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Credit limits for customers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Setting a credit limit lets you specify the maximum amount of credit to extend to your customers. If a credit limit is specified, it is checked automatically when a user attempts to update a document. If the credit limit is exceeded, a message is displayed to the user. This topic provides an overview of how credit limits work in Microsoft Dynamics AX and answers the following questions:

  - What documents and processes can I check credit limits for?

  - Where do I configure the way that the customer’s remaining credit is calculated?

  - Where is information about a customer’s remaining credit used?

  - Where do I specify whether identification is required for credit to be extended to a customer, and also the credit limit amount that requires identification?

  - Where do I specify whether to display a warning or error if the credit limit is exceeded?

  - How do I specify the credit limit for a specific customer?

  - How do I check credit limits manually on sales orders?

## What documents and processes can I check credit limits for?

Use the **Accounts receivable parameters** form to specify which documents to check credit limits for. You must be a member of the **System administrator (-SYSADMIN-)** security role to make changes in this form. You can check credit limits for the following documents and processes:

  - Invoices for sales orders, when you post the invoices

  - Packing slips for sales orders, when you update packing slips

  - Sales orders, when you add lines in the **Sales order** form

  - Sales orders, when they are created through a service

  - Free text invoices, when you post the invoices

Credit limits are automatically checked if either of the following options is set:

  - In the **Accounts receivable parameters** form, the **Credit limit type** field is set to anything other than **None**. Credit limits are checked for all customers.

  - In the **Accounts receivable parameters** form, the **Credit limit type** field is set to **None** but **Mandatory credit limit** is selected for a customer in the **Customers** form. Credit limits are checked only for specific customers.

To check credit limits for the following documents, you must specify additional settings.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Document</p></th>
<th><p>Additional setting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Free text invoice</p></td>
<td><p>In the <strong>Accounts receivable parameters</strong> form, in the <strong>Credit rating</strong> area, select <strong>Check credit limit on free text invoice</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Sales order (manually entered)</p></td>
<td><p>In the <strong>Accounts receivable parameters</strong> form, in the <strong>Credit rating</strong> area, select <strong>Check credit limit on sales order</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Sales order (electronically received)</p></td>
<td><p>In the <strong>Accounts receivable parameters</strong> form, in the <strong>AIF</strong> area, select <strong>Check credit limit for sales orders</strong>.</p></td>
</tr>
</tbody>
</table>


## Where do I configure the way that a customer’s remaining credit is calculated?

You can configure Microsoft Dynamics AX to calculate a customer’s remaining credit in any of the following ways:

  - Compare the credit limit against the customer balance.

  - Compare the credit limit against the customer balance and packing slip amounts.

  - Compare the credit limit against the customer balance and all open transaction activity. This includes packing slip amounts and sales order amounts.

Use the **Accounts receivable parameters** form to specify the information to compare to. You must be a member of the **System administrator (-SYSADMIN-)** security role to make changes in this form. In the **Credit limit type** field, select whether to perform credit limit checks and what transaction information to include when the credit limit is checked. Select from the following options:

  - **None** – Do not check credit limits. You can override this option for a specific customer by selecting the **Mandatory credit limit** check box in the **Customers** form. If you do this, the credit limit is checked against the customer balance.

  - **Balance** – The credit limit is checked against the customer balance.

  - **Balance + packing slip or product receipt** – The credit limit is checked against the customer balance and deliveries.

  - **Balance+All** – The credit limit is checked against the customer balance, deliveries, and open orders.

## Where is information about a customer’s remaining credit used?

Information about a customer’s balance and remaining credit amount is calculated and stored when you create an aging snapshot, and is displayed in the **Collections** form. The amounts that are displayed in the **Collections** form might not include all transaction activity until a new aging snapshot is created. For more information, see [Collections and credit in Accounts receivable](collections-and-credit-in-accounts-receivable.md).

Depending on the documents that are selected, information about a customer’s balance and remaining credit amount is calculated when sales orders, packing slips, and customer invoices are updated. If the amount of the document that you are working with would cause the credit limit to be exceeded, a message is displayed.

## Where do I specify whether identification is required for credit to be extended to a customer, and also the credit limit that requires identification?

Use the **Accounts receivable parameters** form to specify whether to require identification and the credit limit amount limit that requires identification. You must be a member of the **System administrator (-SYSADMIN-)** security role to make changes in this form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Require identification with credit</strong></p></td>
<td><p>Select the type of identification that must be entered for customers to whom your legal entity extends credit. The option that you select in this field determines when and what type of information is required in the <strong>Government identification</strong> fields in the <strong>Customers</strong> form:</p>
<ul>
<li><p><strong>No</strong> – No government-issued identification is required, regardless of the customer's credit limit.</p></li>
<li><p><strong>Yes</strong> – A government-issued license number or other government-issued identification is required if the customer's credit limit is higher than or equal to zero.</p></li>
<li><p><strong>Minimum limit</strong> – A government-issued license number or other government-issued identification is required if the customer's credit limit is higher than or equal to the limit that you enter in the <strong>Limit</strong> field in this form.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Limit</strong></p></td>
<td><p>Enter the credit limit at which a government-issued license number or other identification is required for customers.</p>
<p>For example, type 2000 to require that an identification number, such as a driver's license number, must be entered for customers who have a credit limit of 2,000 or higher.</p>
<p>This field is available if you selected <strong>Minimum limit</strong> in the <strong>Require identification with credit</strong> field.</p></td>
</tr>
</tbody>
</table>


## Where do I specify whether to display a warning or error if the credit limit is exceeded?

Use the **Accounts receivable parameters** form to specify whether to display a warning or error if the credit limit is exceeded. This warning or error is displayed when a user is entering or posting information, or it is included in a log if the documents are being processed by an electronic service. You must be a member of the **System administrator (-SYSADMIN-)** security role to make changes in this form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Message when exceeding credit limit</strong> (in the <strong>Credit rating</strong> area)</p></td>
<td><p>Select how messages about credit limits being exceeded are displayed to users. Select from the following options:</p>
<ul>
<li><p><strong>Error</strong> – An error message is displayed. This usually stops the current operation and the conflict must be resolved before the process can continue.</p></li>
<li><p><strong>Warning</strong> – A warning message is displayed, but the process can continue.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Message when exceeding credit limit</strong> (in the <strong>AIF</strong> area)</p></td>
<td><p>Select how messages about credit limits being exceeded are delivered in a log. Select from the following options:</p>
<ul>
<li><p><strong>Error</strong> – An error message is displayed in the <strong>Exceptions</strong> form, and the document will not be processed until the error is resolved.</p></li>
<li><p><strong>Warning</strong> – A warning message is displayed in the <strong>Exceptions</strong> form, but the process can continue.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## How do I specify the credit limit amount for a specific customer?

Use the **Customers** form to specify the credit limit amount for a specific customer. You must be a member of a security role that has the **Maintain customer master (CustCustomersMaintain)** duty assigned to it to make changes in this form.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Double-click a customer account.

2.  In the **Customers** form, on the **Action Pane**, click **Edit**.

3.  Enter a currency amount in the **Credit limit** field. This value must be higher than zero (0), and will be used as the credit limit amount.

4.  If it is required, enter a license number or other government-issued identification in the **Government identification** field.


> [!NOTE]
> <P>In the <STRONG>Accounts receivable parameters</STRONG> form, a credit limit type is typically selected. However, if the credit limit type is set to <STRONG>None</STRONG>, you must also select the <STRONG>Mandatory credit limit</STRONG> check box in the <STRONG>Customers</STRONG> form in order to check the customer’s credit limit against the customer’s balance. For more information about credit limit types, see “What documents and processes can I check credit limits for?” in this topic.</P>



## How do I manually check credit limits on sales orders?

Sometimes, you might have to manually check a customer’s credit limit. For example, you might manually check a customer’s credit limit before you start entering a sales order. You can use the **Sales order** form to manually check credit limits. You must be a member of a security role that has the **Maintain sales order (SalesOrderMaintain)** duty assigned to it to make changes in this form.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click a sales order.

2.  In the **Sales order** form, on the **Action Pane**, on the **Manage** tab, click **Check credit limit**.

## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

  


