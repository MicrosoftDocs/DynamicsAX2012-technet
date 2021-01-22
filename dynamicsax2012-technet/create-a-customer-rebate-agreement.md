---
title: Create a customer rebate agreement
TOCTitle: Create a customer rebate agreement
ms:assetid: 9046ad1a-226c-4c2b-ad31-c3840834aa43
ms:mtpsurl: https://technet.microsoft.com/library/Hh352289(v=AX.60)
ms:contentKeyID: 36687917
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer rebate
- customer rebate agreement
audience: Application User
ms.search.region: Global
---

# Create a customer rebate agreement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a rebate agreement for a customer.

1.  Click **Sales and marketing** \> **Common** \> **Rebates** \> **Rebate agreements**.

2.  Press CTRL+N to create a new rebate agreement.

3.  In the **Rebate program ID** field, select the program to use for this rebate agreement. You can select from the following types:
    
      - **Rebate** ─ Rebates are processed by sending a check to the customer or by deducting the rebate amount from the customer’s invoice.
    
      - **Freight** ─ Rebates are accrued based on the region and are typically not passed to the customer.
    
      - **TMA** ─ Rebates are accrued until they are passed to the customer, usually as a credit note.

4.  In the **Customer code** and **Customer selection** fields, specify the customer or customer group that qualifies for this rebate agreement. You can also select the customer code **All** if the agreement applies to all customers.

5.  In the **Item code** and **Item selection** fields, specify the item or item group that qualifies for this rebate agreement. You can select the item code **All** if the agreement applies to all items.
    

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 R3, you can use the <STRONG>Selection</STRONG> item code to select multiple items that are not part of a predefined group.</P>



6.  In the **Unit** field, select the unit of measure for the rebate quantity.

7.  In the **Unit type** field, specify whether the unit type is an inventory unit or catch weight unit.

8.  In the **Payment type** field, select the payment type by which customers will receive compensation under the rebate agreement. The available options include **Pay using Accounts payable**, **Customer deductions**, **Invoice customer deductions**, **Trade spending**, and **Freight**.

9.  In the **Cumulate sales by** field, select the option to cumulate customer sales for calculating rebates. The options include **Invoice**, **Week**, **Month**, **Year**, and **Customer Period**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Customized period</STRONG>, you must specify a period type to use in the <STRONG>Period type</STRONG> field. The <STRONG>Period type</STRONG> must be defined in the <STRONG>Period types</STRONG> form.</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Calendars</STRONG> &gt; <STRONG>Period types</STRONG>.</P></LI></UL>

    

    > [!NOTE]
    > <P>In AX 2012 R3, you can also select the <STRONG>Lifetime</STRONG> option to cumulate sales over the validity period of the rebate agreement.</P>



10. In the **Accounts** field group, select the accounts to use for rebate program accrual and rebate program expense.

11. Optionally, enter the remaining information in the upper pane of the form.
    

    > [!NOTE]
    > <P>AX 2012 R3 supports the <STRONG>Rebate line break type</STRONG> field. This field determines whether the rebate amounts that are specified on each rebate agreement line are based on sales quantities or sales amounts. Select the <STRONG>Quantity</STRONG> option if you want to define rebates that are based on the number of items that are sold. Select the <STRONG>Amount</STRONG> option if you want to define rebates that are based on the monetary amount of the sale.</P>



12. On the **Lines** FastTab, click **Add line**.

13. In the **From qty.** and **To qty** fields, enter the range of values that qualify for the rebate amount for the new line.

14. In the **Value** field, enter the amount of the rebate for the line.

15. In the **Amount type** field, select one of the following options:
    
      - **Amount per unit** – The rebate amount in the **Value** field is applied per unit that is purchased.
    
      - **Fixed amount** – The rebate amount in the **Value** field is a fixed amount.
    
      - **Percentage** – The rebate amount in the **Value** field is a percentage off amount.
    

    > [!NOTE]
    > <P>In AX 2012 R3, if there is a value in the <STRONG>To qty</STRONG> or <STRONG>To amount</STRONG> field, and the total sales quantity or amount exceeds that value, some combinations of <STRONG>Rebate line break type</STRONG> and <STRONG>Amount type</STRONG> values can cause incorrect calculation of rebate amounts. Therefore, the following combinations are not allowed, and you receive a message if you try to enter them into the agreement:</P>
    > <UL>
    > <LI>
    > <P>The <STRONG>Rebate line break type</STRONG> field is set to <STRONG>Quantity</STRONG>, and the <STRONG>Amount type</STRONG> field is set to <STRONG>Percentage</STRONG>.</P>
    > <LI>
    > <P>The <STRONG>Rebate line break type</STRONG> field is set to <STRONG>Amount</STRONG>, and the <STRONG>Amount type</STRONG> field is set to <STRONG>Amount per unit</STRONG>.</P></LI></UL>



16. Repeat steps 12 through 15 to add a line for each range of values to include in the rebate calculation.

17. To add special comments or instructions for this rebate agreement, type your comments in the **Note** field on the **Note** tab.

## See also

[About customer rebates](about-customer-rebates.md)

[Period types (form)](https://technet.microsoft.com/library/aa586707\(v=ax.60\))

[Rebate agreements (form)](https://technet.microsoft.com/library/hh328681\(v=ax.60\))

  


