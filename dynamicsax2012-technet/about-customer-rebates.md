---
title: About customer rebates
TOCTitle: About customer rebates
ms:assetid: 560f258a-e4cf-4fe8-8002-9c2adca36582
ms:mtpsurl: https://technet.microsoft.com/library/Hh208964(v=AX.60)
ms:contentKeyID: 36057320
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer rebate
- customer rebates
- rebates
audience: Application User
ms.search.region: Global
---

# About customer rebates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Rebates are payments or credits that are due to customers and that are based on pre-established agreements to purchase certain items in specific quantities or amounts. Process manufacturing production and logistics provides functionality for the following types of rebates:

  - **Rebate** ─ The Rebate type is typically processed by sending a check to the customer or by deducting the rebate amount from the customer's invoice.

  - **TMA** ─ Trade & Merchandising Allowance (TMA) rebates accrue until they are passed on to the customer, which is usually by credit note. 

  - **Freight** ─ Freight rebates accrue based on region and are not passed to the customer. They are used only for reporting.

  - **Billback** – Billback rebates are offered to wholesalers and distributors to cover the costs of a promotion. This rebate type is not available for customer rebate agreements.

You can also exclude items from rebate calculations if you specify them in the sales agreement or the sales order. This feature is available both for rebates that are based on a single invoice and on multiple invoices over time.

## Set up rebates

Use the **Rebate agreements** form to set up rebates that are based on specific customer and item relationships, or on specific customer and item groups. Rebate agreements define the conditions that a customer’s order must meet to qualify for rebates. Some of the conditions are as follows:

  - **Rebate program to apply** ─ The rebate program that you assign to a customer’s rebate agreement defines the type of rebate to apply. You set up rebate programs in the **Rebate program types** form.

  - **Item code** ─ The item code indicates the method that is used to select items that are eligible for the rebate. You can select a single product, a group of products, or all products.
    

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 R3, you can use the <STRONG>Selection</STRONG> option to select multiple items that are not part of a predefined group.</P>



  - **Unit and unit type** ─ The unit and unit type work together. The unit is the unit of measure for the rebate quantity. The unit type indicates which unit from the sales line to compare to the unit to determine whether the rebate applies.

  - **Unit of measure rebate option** ─ This option identifies the unit of measure for the rebate line. If you use the **Exact match** option, the unit of measure for the rebate line must exactly match the unit of measure specified in the sales order. If not, the rebate does not qualify. If you use the **Convert** option, the unit of measure for the rebate line is the same as the unit of measure for the rebate agreement. The rebate unit of measure is converted to the sales order unit of measure, or the catch weight unit of measure, if applicable.

  - **Minimum quantity or Minimum amount** ─ The rebate agreement must specify either a minimum quantity or a minimum amount that the customer is required to purchase to qualify for a rebate.

  - **Rebate line break type** ─ AX 2012 R3 supports the **Rebate line break type** field. This field determines whether the rebate amounts that are specified on each rebate agreement line are based on sales quantities or sales amounts. Select the **Quantity** option if you want to define rebates that are based on the number of items that are sold. Select the **Amount** option if you want to define rebates that are based on the monetary amount of the sale.

  -  **Effective date range** ─ The effective date range defines the period during which rebates are effective based on the rebate agreement.

  - **Payment type** ─ The payment type determines how the customer receives compensation under the rebate agreement. The customer can receive payment through accounts payable, customer deduction, trade spending, or freight.
    

    > [!NOTE]
    > <P>In AX 2012 R3, the <STRONG>Invoice customer deductions</STRONG> option has been added.</P>



  - **Currency type** ─ The currency type determines the currency in which rebates are remitted. You can specify a generic currency, which is converted on the order, or you can specify a specific currency for the rebate. If you use a generic currency, it must be the generic currency that is defined in the **Generic currency** field in the **Accounts receivable parameters** form.

## Cumulate rebates

Sales can be cumulated by any of the following methods: **Invoice**, **Week**, **Month**, **Year**, or by using a **Customized period**. Customized periods allow for customers to configure their own period, such as Quarterly. Customers who select **Customized period** must specify a period in the **Period type** field. You set up period types in **Organization administration** on the **Period types** form.


> [!NOTE]
> <P>AX 2012 R3 supports the <STRONG>Lifetime</STRONG> option. The <STRONG>Lifetime</STRONG> option indicates that sales are cumulated over the validity period of the rebate agreement.</P>



## Calculate rebates

When you invoice a sales order line, Process manufacturing production and logistics checks for any rebate agreements that may apply. For those that do, a rebate is created. What follows describes the rebate status values:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>To be calculated</strong></p></td>
<td><p>The final rebate amount is pending completion of the <strong>Cumulate Rebates</strong> run. This status applies to rebates that are generated from weekly, monthly, or yearly agreements.</p></td>
</tr>
<tr class="even">
<td><p><strong>Calculated</strong></p></td>
<td><p>The rebate has been calculated and is pending approval.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Approved</strong></p></td>
<td><p>The rebate has been approved if approval is required.</p></td>
</tr>
<tr class="even">
<td><p><strong>Mark</strong></p></td>
<td><p>The rebate is available for processing.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Processed</strong></p></td>
<td><p>The rebate has been processed and passed to <strong>Accounts Payable</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Free</strong></p></td>
<td><p>A TMA type rebate has been created manually for a specific customer.</p></td>
</tr>
</tbody>
</table>


The value of the rebate may be taken from the gross or net of the sales order line. It may also be calculated based on a fixed amount, a percentage, or currency per unit basis.

## Apply rebates

The following guidelines pertain when you apply customer rebates:

  - If you select **At invoicing** on the **Rebate program** FastTab in the **Accounts receivable parameters** form, rebates created at invoicing are posted to the general ledger.

  - If the rebate is cumulative, you must run the **Cumulate rebates** function, followed by **Process rebates** to post the rebate to the general ledger.

  - If the rebate requires approval, you must run **Approve rebates**, followed by **Process rebates**.

  - Once the rebate has been set to a status of **Mark**, you may pass it to **Accounts Payable** for payment or to be processed as a credit note.

## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

[Cumulate rebates (form)](https://technet.microsoft.com/library/hh328729\(v=ax.60\))

[Period types (form)](https://technet.microsoft.com/library/aa586707\(v=ax.60\))

[Product specific (form)](https://technet.microsoft.com/library/hh227369\(v=ax.60\))

[Rebate agreements (form)](https://technet.microsoft.com/library/hh328681\(v=ax.60\))

[Rebate program types (form)](https://technet.microsoft.com/library/hh352270\(v=ax.60\))

  


