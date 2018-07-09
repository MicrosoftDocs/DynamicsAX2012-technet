---
title: Set up vendor rebate agreements
TOCTitle: Set up vendor rebate agreements
ms:assetid: 8ac9f85e-cd6b-4a39-b806-0ab3e4b24fd0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497800(v=AX.60)
ms:contentKeyID: 62200113
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- rebate agreement
- Forms.TAMItemVendRebateGroup
- Forms.TAMVendRebate
- Forms.TAMVendRebateAgreement
- Forms.TAMVendRebateGroup
- MsDynAx060.Forms.TAMItemVendRebateGroup
- MsDynAx060.Forms.TAMVendRebateGroup
- MsDynAx060.Forms.TAMVendRebateAgreement
- MsDynAx060.Forms.TAMVendRebate
- cumulate
- purchase order rebate
- vendor rebate
---

# Set up vendor rebate agreements [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A business can set up an agreement with one of its vendors to specify that the vendor provides a rebate for purchases. This topic describes how to create a vendor rebate agreement to store details of the rebate offer.

After you create a rebate agreement, you can create purchase orders that are eligible for the rebate, generate rebate claims, and process the claims. For more information, see [Work with vendor rebates](work-with-vendor-rebates.md).

## 1\. Set vendor rebate parameters

Set the relevant parameters for vendor rebates in the **Procurement and sourcing parameters** form.

To set vendor rebate parameters, follow these steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the left pane, click **Rebate program**, and then fill in the following fields.
    
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
    <td><p><strong>Accrual account</strong></p></td>
    <td><p>Specify the main account to which the rebate accrual is posted.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Interim expense account</strong></p></td>
    <td><p>Specify the main account to which the rebate expense is posted. This account is used for interim postings that are made when a rebate is manually approved, if manual approval is required.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Starting day of week</strong></p></td>
    <td><p>Specify the starting day of the week to use when the <strong>Cumulate by week</strong> option is selected.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>At invoicing</strong></p></td>
    <td><p>Select this check box to create a rebate claim when the purchase order is invoiced. If this check box is cleared, no rebate claims are created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Procurement category</strong></p></td>
    <td><p>Specify the procurement category to use in the lines of a vendor invoice that is created for a processed rebate. The system automatically creates a vendor invoice to debit the vendor liability after the rebate is processed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accrual journal name</strong></p></td>
    <td><p>Specify the journal to use for rebate accrual. This journal is used for interim postings that are made when a rebate is manually approved, if manual approval is required.</p></td>
    </tr>
    </tbody>
    </table>


## 2\. Create a rebate program type, vendor group, and item group

You must define a type of rebate program to represent vendor rebates. You can also optionally create a vendor group, if you want a rebate agreement to apply to a group of vendors, or an item group, if you want a rebate agreement to apply to a group of products.

To create a rebate program type, follow these steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Rebate program** \> **Rebate program types**.

2.  Click **New**, and enter an ID and description for the program type.

3.  Select a default accrual account and expense account.

Optional: To create a vendor rebate group, follow these steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Rebate program** \> **Vendor rebate groups**.

2.  Click **New**, and enter a name and description for the vendor rebate group.

3.  Close the **Vendor rebate groups** form.

4.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

5.  For each vendor that is part of the vendor rebate group, open the vendor record, and then, on the **Action Pane**, click **Edit**. On the **Miscellaneous details** FastTab, in the **Vendor rebate group** field, select the vendor rebate group that you created earlier.

Optional: To create an item rebate group, follow these steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Rebate program** \> **Item rebate groups**.

2.  Click **New**, and enter a name and description for the item rebate group.

3.  Close the **Item rebate groups** form.

4.  Click **Product information management** \> **Common** \> **Released products**.

5.  For each product that is part of the item rebate group, open the product record, and then, on the **Action Pane**, click **Edit**. On the **Purchase** FastTab, in the **Vendor rebate item group** field, select the item rebate group that you created earlier.

## 3\. Create a rebate agreement

The rebate agreement defines which products are included in the rebate offer, which vendors offer the rebate, and how the rebate is calculated. Rebates can be based on the quantity (number of products) or the amount (monetary amount) that is purchased.

The rebate agreement also specifies how purchases are cumulated. For cumulation, the purchases from a particular vendor over a specified period of time are added together, and then the rebate amount or quantity criteria are applied to the sum. This method makes it easier to meet the minimum purchase requirements for each line of the rebate agreement.

To create a rebate agreement, follow these steps.

1.  Click **Procurement and sourcing** \> **Common** \> **Rebates** \> **Rebate agreements**.

2.  Click **New**, and then, on the **Overview** tab, fill in the following fields.
    
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
    <td><p><strong>Rebate program ID</strong></p></td>
    <td><p>Specify the ID of the type of rebate program.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor code</strong></p></td>
    <td><p>Specify the vendor selection method.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Table</strong> – Select an individual vendor in a list.</p></li>
    <li><p><strong>Group</strong> – Select a vendor rebate group in a list.</p></li>
    <li><p><strong>All</strong> – The rebate is valid for all vendors.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor selection</strong></p></td>
    <td><p>Specify the ID of the vendor account or vendor rebate group that is offering the rebate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Item code</strong></p></td>
    <td><p>Specify the product selection method.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Table</strong> – Select an individual item in a list.</p></li>
    <li><p><strong>Group</strong> – Select an item rebate group in a list.</p></li>
    <li><p><strong>All</strong> – The rebate is valid for all items.</p></li>
    <li><p><strong>Selection</strong> – Use a tab on the agreement header to select multiple items that are not part of a predefined group. For example, you can select items by category.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Item selection</strong></p></td>
    <td><p>Specify the ID of an item or item rebate group that is eligible for the rebate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Unit</strong></p></td>
    <td><p>Specify the unit of measure that is used for item quantities.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Minimum quantity</strong></p></td>
    <td><p>Specify the minimum quantity of items that you must purchase to qualify for the rebate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Minimum amount</strong></p></td>
    <td><p>Specify the minimum amount that you must spend on items to qualify for the rebate.</p></td>
    </tr>
    </tbody>
    </table>


3.  Beneath the list, fill in the following fields.
    
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
    <td><p><strong>Cumulate purchases by</strong></p></td>
    <td>Specify the method by which purchases will be cumulated.
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Invoice</strong> – The rebate amount is calculated for individual invoices when those invoices are posted. Purchases are not cumulated.</p></li>
    <li><p><strong>Week</strong>, <strong>Month</strong>, <strong>Year</strong>, <strong>Lifetime</strong>, or <strong>Customized period</strong> – The rebate amount is first calculated for individual invoices. Then purchases are cumulated over the specified period, and the rebate is recalculated for the purchase total.</p>
    <p>If you select the <strong>Customized period</strong> option, you must specify the period in the <strong>Period type</strong> field.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Taken from</strong></p></td>
    <td><p>Specify the basis for the rebate calculation.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Gross</strong> – The rebate is calculated based on the gross price of the item.</p></li>
    <li><p><strong>Net</strong> – The rebate is calculated based on the net price of the item (the price after other discounts have been applied).</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rebate program accrual account</strong></p></td>
    <td><p>Specify the account to which the rebate accrual is posted.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rebate program expense account</strong></p></td>
    <td><p>Specify the account to which the rebate expense is posted.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Currency</strong></p></td>
    <td><p>Specify the code for the current currency.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Approval required</strong></p></td>
    <td><p>Select this check box to require that the rebate claim be approved before it can be accrued or paid out.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rebate line break type</strong></p></td>
    <td><p>Specify the purchase criteria to use to determine rebate amounts.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Quantity</strong> – The rebate amount is determined by the number of items that you purchase.</p></li>
    <li><p><strong>Amount</strong> – The rebate amount is determined by the monetary amount that you purchase (the unit price of items multiplied by the quantity).</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  On the **General** tab, under **Unit**, select one of the following options for the **Unit of measure rebate option** field:
    
      - **Exact match** – The unit of measure for the rebate line must exactly match the unit of measure that is specified in the purchase order. Otherwise, the rebate does not qualify.
    
      - **Convert** –The unit of measure for the rebate line is converted to the purchase order unit of measure, or to the catch weight unit of measure if catch weight is applicable.

5.  On the **General** tab, under **Date**, select one of the following options for the **Calculation date type** field:
    
      - **Created** – Use the creation date of the purchase order to determine whether the purchase falls in the validity period of the rebate agreement.
    
      - **Requested delivery** – Use the requested delivery date on the purchase order line to determine whether the purchase falls in the validity period of the rebate agreement.

6.  On the **Lines** FastTab, click **Add line**.

7.  Optional: To add other dimensions to the **Lines** list, so that you can further define rebate lines, click **Inventory**, and then click **Dimensions display**. Select the check box next to each dimension to include in the **Lines** list, and then click **OK**.

8.  In the **From value** and **To value** fields, enter the range of values that qualify for the rebate amount for that line.
    

    > [!NOTE]
    > <P>The <STRONG>From</STRONG> value is inclusive, and the <STRONG>To</STRONG> value is exclusive. For example, if the <STRONG>Rebate line break type</STRONG> field is set to <STRONG>Quantity</STRONG>, and you enter <STRONG>1</STRONG> in the <STRONG>From value</STRONG> field and <STRONG>3</STRONG> in the <STRONG>To value</STRONG> field, the rebate amount applies when you purchase one or two items, but not when you purchase three items.</P>



9.  In the **Value** field, enter the amount of the rebate for that line.

10. In the **Amount type** field, select one of the following options:
    
      - **Amount per unit** – The rebate amount in the **Value** field is applied per unit that is purchased.
    
      - **Fixed amount** – The rebate amount in the **Value** field is a fixed amount.
    
      - **Percentage** – The rebate amount in the **Value** field is a percentage off amount.
    

    > [!NOTE]
    > <P>If there is a value in the <STRONG>To value</STRONG> field, and the total purchase quantity or amount exceeds that value, some combinations of <STRONG>Rebate line break type</STRONG> and <STRONG>Amount type</STRONG> values can cause incorrect calculation of rebate amounts. Therefore, the following combinations are not allowed, and you receive a message if you try to enter them into the agreement:</P>
    > <UL>
    > <LI>
    > <P>The <STRONG>Rebate line break type</STRONG> field is set to <STRONG>Quantity</STRONG>, and the <STRONG>Amount type</STRONG> field is set to <STRONG>Percentage</STRONG>.</P>
    > <LI>
    > <P>The <STRONG>Rebate line break type</STRONG> field is set to <STRONG>Amount</STRONG>, and the <STRONG>Amount type</STRONG> field is set to <STRONG>Amount per unit</STRONG>.</P></LI></UL>



11. Repeat steps 6 through 10 to add a line for each range of values that you want to include in the rebate calculation.
    
    For example, after you create a rebate line that applies when you purchase one or two items, you can add a second line that applies a different rebate amount when you purchase three to 10 items.

12. Validate the agreement: On the **Action Pane**, click **Validation**, enter the name of the user who validated the agreement, and then click **OK**. Review any messages that describe errors in the agreement data, and fix the errors as required.

You can optionally set up a workflow to create and approve vendor rebate agreements.

## Next step

After you create a rebate agreement, you can create purchase orders that are eligible for the rebate, generate rebate claims, and process vendor rebate claims. For more information, see [Work with vendor rebates](work-with-vendor-rebates.md).

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
<td><p><strong>Trade agreements</strong> configuration key</p>
<p><strong>Vendor rebates</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>Purchasing manager</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

