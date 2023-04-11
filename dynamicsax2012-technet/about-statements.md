---
title: About statements
TOCTitle: About statements
ms:assetid: c83d5d89-d8b2-4624-9f88-1f20f7d67378
ms:mtpsurl: https://technet.microsoft.com/library/Hh597240(v=AX.60)
ms:contentKeyID: 39519316
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- statement
- retail statements
- statements process
audience: Application User
ms.search.region: Global
---

# About statements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In Microsoft Dynamics AX 2012 for Retail, you can use the statement posting process to account for the transactions that occur in Microsoft Dynamics AX for Retail POS. The statement posting process uses Retail scheduler to transmit a set of the point-of-sale (POS) transactions to the Microsoft Dynamics AX client. You can define the criteria that are used to select transactions by using the **Retail parameters** form and the **Stores** form. (For more information about these forms, click the links in the “See also” section at the end of this topic.)


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



The following diagram illustrates the statement posting process. In this process, transactions that are recorded in Retail POS are transmitted to the client by using the Retail scheduler. After the client receives the transactions, you can create, calculate and post the transaction statement for the store.

![Retail statement posting process](images/Hh597240.RetailStatements_process(AX.60).gif "Retail statement posting process")

## Creating and posting statements

You can create a statement manually or by using batch processes that you set up to run periodically throughout the day. In both cases, the following steps are used to create and post statements.

## Create the statement

This step identifies the store that the statement is manually created for. If you configure a batch process, you can automatically create statements for all stores, based on a schedule that you define.

## Calculate the statement

In this step, the transaction lines are selected based on criteria that are defined for each store in the **Retail parameters** and **Stores** forms. In these forms, you define the criteria and specify how the transactions are calculated. To view a list of the transactions that are included in the statement before you calculate the statement, use the **Transactions** form.

A statement calculation uses tender declarations from the registers as the counted amount. Alternatively, you can enter the counted amount manually. The statement displays the difference between the sales amount for the transactions and the actual counted amount in all payment methods. The statement is posted only if this difference is less than the maximum posting difference that is defined for the store.


> [!NOTE]
> <P>The statement calculation process uses the global number sequence.</P>



When you calculate a statement, the calculation includes the following tasks:

  - Marking transactions that were not included in a previous statement calculation, for the selected date range.

  - Calculating the total amounts that were tendered in the selected transactions. The results are displayed on the statement lines, depending on the statement method:
    
      - If the statement method is **Total**, a line is created for each payment method in the selected transactions.
    
      - If the statement method is **Staff**, a line is created for each payment method in transactions that were performed by the selected staff member.
    
      - If the statement method is **POS terminal**, a line is created for each payment method in transactions that were performed on the selected register.


> [!NOTE]
> <P>Before you can create statements, you should close the shifts in the statement period.</P>



## Post the statement

When you post a statement, sales orders and invoices are created for the retail sales in the statement.

  - Cash and carry sales are aggregated onto one sales order and invoiced for the default customer who is assigned to the store.

  - Retail sales for which a customer was added to the transaction in Microsoft Dynamics AX for Retail POS generate separate sales orders and invoices, one for each unique customer.

Payment journals are automatically created for the payments in the statement, and the inventory is updated for the POS store. If you selected the **Automatic settlement** option on the **Posting** tab in the **Retail parameters** form, payments are automatically settled against invoices.

## More about statements in cumulative update 7 for Microsoft Dynamics AX 2012 R2

In cumulative update 7 for Microsoft Dynamics AX 2012 R2, the following options were added to provide more flexibility when posting statements:

  - In addition to being able to summarize statement lines by register number, by staff ID, or as a total, you can now summarize statement lines by shift. If the **Split by Statement method** check box is selected in the **Stores** form, a separate statement is created based on the value that is selected in the **Statement method** field.

  - If your store operating hours extended past midnight, you can post statements based on the end of the business day instead of the end of the calendar day.
    
    In the **Stores** form, on the **Statement/closing** FastTab, in the **End of business day** field, enter the time that the last transaction must be recorded to be included in the business day’s statement. Select the **Post as business day** check box to post the transactions within the same business day. When the statement is posted, transactions that are recorded within the same business day can be included on the same sales order, even if they occur before and after midnight.

**Example: Post a statement for a business day that extends over two calendar days**

A store is open between the hours of 8:00 A.M. and 3:00 A.M., and the store is configured with the **Post as business day** check box selected. The store records transactions between the hours of 8:00 A.M. and midnight on May 31. The store also records transactions between the hours of 12:01 A.M. and 3:00 A.M. on June 1.

When the store posts its statement for the close of the business day, a sales order is generated that includes all transactions that were recorded between the business hours of 8:00 A.M. and 3:00 A.M., even though the transactions occurred on May 31 and June 1.

If the same store is configured with the **Post as business day** check box cleared, separate sales orders are generated when the store posts its statement for the close of the business day. One sales order includes the transactions that were recorded between the business hours of 8:00 A.M. and midnight on May 31, and the second sales order includes the transactions that were recorded between the hours of 12:01 A.M. and 3:00 A.M. on June 1.

## See also

[Create and post a statement](create-and-post-a-statement.md)

[Retail parameters (form)](https://technet.microsoft.com/library/hh597194\(v=ax.60\))

[Stores (form)](https://technet.microsoft.com/library/hh580646\(v=ax.60\))

  


