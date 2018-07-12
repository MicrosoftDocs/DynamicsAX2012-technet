---
title: Set up parameters to calculate invoice issue due dates
TOCTitle: Set up parameters to calculate invoice issue due dates
ms:assetid: cae7bc57-e3e9-41a4-bb45-699d64f3603d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn751509(v=AX.60)
ms:contentKeyID: 62378988
ms.date: 05/26/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustParameters
- Forms.LedgerInvoiceIssueDueDateSetup_W
audience: Application User
ms.search.region: Global
---

# Set up parameters to calculate invoice issue due dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up parameters to calculate the due dates for issuing customer invoices and vendor invoices.

You can set up a date interval code, and then set up an invoice issue date calculation rule by assigning the date interval code to a country/region type. The calculation rule is used to calculate the due date for issuing invoices for the following transactions:

  - Intra-European Union (EU) shipments

  - Domestic shipments within an EU member state

You can also set up date controls to ensure that customer invoices and credit notes for customer transactions are generated within the specified time period after the delivery is made.

## Example

To set up Microsoft Dynamics AX to calculate invoice issue due dates for Intra-EU shipments on the 15th day of the next month after the supply is delivered, create a date interval code and a calculation rule with the following settings:

  - **Date interval code**
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Date interval code</strong></p></td>
    <td><p>15-NM</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>15th day of the next month</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Before</strong> <br />
    (In the <strong>To date</strong> field group)</p></td>
    <td><p><strong>Month</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start/End</strong> <br />
    (In the <strong>To date</strong> field group)</p></td>
    <td><p><strong>End</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>+/-</strong> <br />
    (In the <strong>To date</strong> field group)</p></td>
    <td><p>15</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Days, months, years or periods</strong> <br />
    (In the <strong>To date</strong> field group)</p></td>
    <td><p><strong>Days</strong></p></td>
    </tr>
    </tbody>
    </table>


  - **Invoice issue due date calculation rule**
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Country/region type</strong></p></td>
    <td><p><strong>EU</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Set up the date from which the current setup line is valid.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date interval code</strong></p></td>
    <td><p>15-NM</p></td>
    </tr>
    </tbody>
    </table>


## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: EU member state</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up a date interval that is used to calculate the invoice issue due date. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa558459(v=ax.60)">Date intervals (form)</a>.</p></li>
<li><p>Set up foreign trade properties for various countries or regions in the <strong>Foreign trade parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa620385(v=ax.60)">Foreign trade parameters (form)</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Set up an invoice issue due date calculation rule

Use the **Set up calculation for invoice issue due date** form to set up an invoice issue due date calculation rule by assigning a date interval code to a country/region type.

To perform this task, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Set up calculation for invoice issue due date**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Country/region type** field, select one of the following options for the country/region type:
    
      - **EU** – The calculation rule applies to shipments within the EU.
    
      - **Domestic** – The calculation rule applies to the domestic deliveries within a single EU member state.
    
      - **EFTA** – The calculation rule applies to countries in the European Free Trade Association (EFTA).
    
      - **Third country/region** – The calculation rule applies to a country/region that is not domestic, a member of the EU, nor a member of the EFTA.

4.  In the **Start date** field, enter the starting date from which the calculation rule is valid.

5.  In the **Date interval code** field, select the date interval code that is used to calculate the invoice issue due dates for the selected country/region type.

## Set up date control for customer invoices and credit notes

Use this procedure to set up date control parameters that are used to ensure that customer invoices and credit notes for customer transactions are generated within the specified time period after the delivery is made.


> [!NOTE]
> <P>This procedure applies only if the primary address of your legal entity is in an EU member state other than Poland or Hungary.</P>



To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, click **Updates**.

3.  In the **Updates** area, specify the date control for customer invoices and credit notes.
    
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
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the document date on a customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to display a message when the document date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No message is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  Optional: In the left pane, click **Summary update**.

5.  Optional: In the **Summary update** area, select the **Delivery information** check box for the **Packing slip** to produce one packing slip per sales order line delivery address when posting.

## (POL) Set up date control parameters for customer invoices and credit notes

Use this procedure to set up date control parameters that are used to ensure that customer invoices and credit notes for customer transactions are generated within the specified time period after the delivery is made.


> [!NOTE]
> <P>This procedure applies only if the primary address of your legal entity is in Poland.</P>



To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, click **Updates**.

3.  In the **Updates** area, specify the date control for customer invoices and credit notes.
    
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
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select an option to indicate the date control that is applied for the following conditions:</p>
    <ul>
    <li><p>The document date on a customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice.</p></li>
    <li><p>The document date is later than the sales date plus the number of days that you specified in the <strong>+/-</strong> field for the date interval.</p></li>
    </ul>
    <p>The options for this field are:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to display a message when the document date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No message is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  Optional: In the left pane, click **Summary update**.

5.  Optional: In the **Summary update** area, select the **Delivery information** check box for the **Packing slip** to produce one packing slip per sales order line delivery address when posting.

## (HUN) Set up date control parameters for customer invoices and credit notes

Use this procedure to set up date control parameters that are used to ensure that customer invoices and credit notes for customer transactions are generated within the specified time period after the delivery is made.


> [!NOTE]
> <P>This procedure applies only if the primary address of your legal entity is in Hungary.</P>



To perform this task, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, click **Updates**.

3.  In the **Updates** area, specify the date control for customer invoices and credit notes.
    
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
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Invoice dates control</strong> field group)</p></td>
    <td><p>Select an option to indicate the date control that is applied for the following conditions:</p>
    <ul>
    <li><p>The document date on a customer invoice is later than the invoice issue due date on the packing slips that are included in the invoice.</p></li>
    <li><p>The document date is later than the sales date plus the number of days that you specified in the <strong>+/-</strong> field for the date interval.</p></li>
    </ul>
    <p>The options for this field are:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Invoice date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to indicate the date control that is applied when the invoice date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No date control is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date control</strong> <br />
    (In the <strong>Credit note dates control</strong> field group)</p></td>
    <td><p>Select one of the following options to display a message when the document date on the credit note is later than the invoice issue due date on the packing slips that are included in the credit note:</p>
    <ul>
    <li><p><strong>None</strong> – No message is displayed.</p></li>
    <li><p><strong>Warning</strong> – A warning message is displayed when you attempt to post the customer invoice. However, you can complete the posting process.</p></li>
    <li><p><strong>Error</strong> – An error message is displayed when you attempt to post the customer invoice. In this case, you cannot complete the posting process.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  Optional: In the left pane, click **Summary update**.

5.  Optional: In the **Summary update** area, select the **Delivery information** check box for the **Packing slip** to produce one packing slip per sales order line delivery address when posting.

## Next step

After you have finished setting up the parameters to calculate invoice issue due dates, you can create and post the following transactions to automatically calculate and update the due dates to issue invoices:

  - **Sales orders** – When you create a sales order and post a packing slip, the due date for issuing the invoice is calculated and updated on the packing slip. The due date is calculated based on the date interval that is associated with the country that is specified in the delivery address of the sales order. You can post the packing slip, and then verify the invoice issue due date in the **Invoice issue due date** field in the **Packing slip journal** form. (Click **Sales and marketing** \> **Inquiries** \> **Journals** \> **Packing slip**.) For more information, see [Packing slip journal (form)](https://technet.microsoft.com/en-us/library/aa548967\(v=ax.60\)), [Create or edit a sales order](create-or-edit-a-sales-order.md), and [Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\)).
    
    You can view all of the packing slips that are not invoiced and their invoice issue due dates in the **Packing slips not invoiced** form. (Click **Sales and marketing** \> **Inquiries** \> **Journals** \> **Packing slips not invoiced**.)

  - **Purchase orders** – When you create a purchase order and post a product receipt, the due date for issuing the invoice is calculated and updated on the product receipt. The due date is calculated based on the date interval that is associated with the country that is specified in the primary address of the vendor. You can post the product receipt, and then verify the invoice issue due date in the **Invoice issue due date** field in the **Product receipt journal** form. (Click **Procurement and sourcing** \> **Inquiries** \> **Journals** \> **Product receipt**.) For more information, see [Product receipt journal (form)](https://technet.microsoft.com/en-us/library/aa572107\(v=ax.60\)) and [Create a purchase order](create-a-purchase-order.md).
    
    You can view all of the product receipts that are not invoiced and their invoice issue due dates in the **Product receipts not invoiced** form. (Click **Procurement and sourcing** \> **Inquiries** \> **Journals** \> **Product receipts not invoiced**.)

## Related tasks

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

[Key tasks: Customer invoices](key-tasks-customer-invoices.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Click the <strong>General ledger</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>CustInvoiceInvoiceAndCashProcessEnable</strong> (Enable invoice and cash process)</p></li>
<li><p><strong>VendInvoiceInvoicePaymentProcessEnable</strong> (Enable invoice and payment process)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>CustPackingSlipJournalView</strong> (View sales packing slips)</p></li>
<li><p><strong>VendPackingSlipJournalView</strong> (View product receipt journal from purchase order)</p></li>
<li><p><strong>LedgerInvoiceIssueDueDateSetupMaintain_W</strong> (Calculate invoice issue due dates)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


