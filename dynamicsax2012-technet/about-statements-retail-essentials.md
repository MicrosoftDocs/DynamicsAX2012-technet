---
title: About statements (Retail essentials)
TOCTitle: About statements (Retail essentials)
ms:assetid: 7cb97e26-2cdb-43c1-ba3f-101df9e56636
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736905(v=AX.60)
ms:contentKeyID: 62200382
ms.date: 04/22/2015
mtps_version: v=AX.60
---

# About statements (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can use the statement posting process to account for point-of-sale (POS) transactions. The statement posting process uses Retail scheduler to transmit a set of transactions from the POS to the Microsoft Dynamics AX client. You can define the criteria that are used to select the transactions that you want to transmit by using the **Retail parameters** form and the **Stores** form. For more information about these forms, click the links in the “See also” section at the end of this topic.

The following diagram illustrates the statement posting process. In this process, transactions that are recorded in Retail essentials are transmitted by using the Retail scheduler. After the client receives the transactions, you can create, calculate, and post the transaction statement for the store.

![Retail statement posting process](images/Dn736905.RetailStatements_process(AX.60).gif "Retail statement posting process")

  
You can create a statement manually or by using batch processes that you set up to run periodically throughout the day. In both cases, the steps in the following sections are used to create and post statements.

## Create the statement

In this step, you identify the store that a statement is manually created for. If you configure a batch process, you can automatically create statements for all stores, based on a schedule that you define.


> [!NOTE]
> <P>Before you create statements, you must close the shifts in the statement period.</P>



## Calculate the statement

In this step, the transaction lines are selected based on criteria that are defined for each store in the **Retail parameters** and **Stores** forms. In these forms, you define the criteria and specify how the transactions are calculated. To view a list of the transactions that are included in the statement before you calculate the statement, use the **Transactions** form. The statement calculation process uses the global number sequence.

A statement calculation uses tender declarations from the registers as the counted amount. Alternatively, you can enter the counted amount manually. The statement displays the difference between the sales amount for the transactions and the actual counted amount in all payment methods. The statement is posted only if this difference is less than the maximum posting difference that is defined for the store.

When you calculate a statement, the calculation includes the following tasks:

  - Identifying transactions that were not included in a previous statement calculation for the selected date range.

  - Calculating the total amounts that were tendered in the selected transactions. The results are displayed on the statement lines, depending on the statement method.
    
      - If the statement method is **Total**, a line is created for each payment method in the selected transactions.
    
      - If the statement method is **Staff**, a line is created for each payment method in transactions that were performed by the selected staff member.
    
      - If the statement method is **POS terminal**, a line is created for each payment method in transactions that were performed on the selected register.


> [!NOTE]
> <P>In addition to being able to summarize statement lines by register number, by staff ID, or as a total, you can summarize statement lines by shift. If the <STRONG>Split by Statement method</STRONG> check box is selected in the <STRONG>Stores</STRONG> form on the <STRONG>Statement/closing</STRONG> FastTab, a separate statement is created based on the value that is selected in the <STRONG>Statement method</STRONG> field.</P>



## Post the statement

When you post a statement, sales orders and invoices are created for the retail sales in the statement.

  - Cash-and-carry sales are aggregated onto one sales order and invoiced for the default customer who is assigned to the store.

  - Retail sales for which a customer was added to the transaction in Retail essentials generate separate sales orders and invoices for each unique customer.

Payment journals are automatically created for the payments in the statement, and the inventory is updated for the POS store. If you selected the **Automatic settlement** option on the **Posting** tab in the **Retail parameters** form, payments are automatically settled against invoices.

If your store operating hours extended past midnight, you can post statements based on the end of the business day instead of the end of the calendar day.

**Example: Post a statement for a business day that extends over two calendar days**

A store is open between the hours of 8:00 A.M. and 3:00 A.M., and the store is configured with the **Post as business day** check box selected. The store records transactions between the hours of 8:00 A.M. and midnight on May 31. The store also records transactions between the hours of 12:01 A.M. and 3:00 A.M. on June 1.

When the store posts its statement for the close of the business day, a sales order is generated that includes all transactions that were recorded between the business hours of 8:00 A.M. and 3:00 A.M., even though the transactions occurred on May 31 and June 1.

If the same store is configured with the **Post as business day** check box cleared, separate sales orders are generated when the store posts its statement for the close of the business day. One sales order includes the transactions that were recorded between the business hours of 8:00 A.M. and midnight on May 31, and the second sales order includes the transactions that were recorded between the hours of 12:01 A.M. and 3:00 A.M. on June 1.

## See also

[Create and post a statement (Retail essentials)](create-and-post-a-statement-retail-essentials.md)

[View posted statements (Retail essentials)](view-posted-statements-retail-essentials.md)

[Stores (form)](https://technet.microsoft.com/en-us/library/hh580646\(v=ax.60\))

  


