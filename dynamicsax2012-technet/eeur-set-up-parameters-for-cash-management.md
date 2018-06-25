---
title: (EEUR) Set up parameters for cash management
TOCTitle: (EEUR) Set up parameters for cash management
ms:assetid: f49668e5-c1fe-4e57-9b5a-4e7604f6a594
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710653(v=AX.60)
ms:contentKeyID: 49385052
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Set up parameters for cash management [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In accordance with Eastern Europe accounting requirements, you can set up operations for cash accounts to automate the processes for receipts and expenditures. You can also set up automation processes to create cash documents and print reports.

You can perform the following cash operations:

  - Account for the receipt and expenditure of available cash assets.

  - Create and store cash reimbursement slips, cash disbursement slips, and a journal of registrations for cash slips.

  - Control the maximum amount of cash for operations that have counteragents.

  - Create cash operations in various currencies.

  - Convert the amounts of cash operations in foreign currencies to the accounting currency to provide reporting for accounting.

  - Generate cashbook reports and cashier’s reports.

<!-- end list -->

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  In the **Cash** area, in the **Exchange differences type** field, select the method to use to settle exchange differences. Exchange differences are settled for bank transactions that have the same registration currency code.
    
      - **FIFO** – Settle expenditure transactions that have an earlier transaction date with receipt transactions that have an earlier transaction date, based on the principle of first in, first out (FIFO).
    
      - **LIFO** – Settle expenditure transactions that have a later transaction date with receipt transactions that have a later transaction date, based on the principle of last in, first out (LIFO).

3.  In the **Cash** field, select the code for the default cash account. In the **Cash posting** field, select the code for the default cash posting profile.

4.  In the **Check for voucher used** field, select the method to use to process cash documents that have duplicate numbers.

5.  In the **Check operations limit** field, specify the type of message to display when the limit for operations that have counteragents is exceeded:
    
      - **Accept duplicates** – The limit can be exceeded.
    
      - **Warning** – The limit can be exceeded, but a message is displayed. The operation is posted.
    
      - **Error** – The limit cannot be exceeded, and a message is displayed. The operation is not posted.

6.  In the **Validation method** field, select the validation method to use to control how limits for operations are exceeded:
    
      - **Operation** – Validation is performed for each transaction.
    
      - **Agreement** – Validation is performed for each transaction for which a contract exists that has a counteragent.

7.  In the **Operations limit** field, enter the maximum cash amount for operations that have counteragents.

8.  Select the **Posting on earlier date** check box to allow for cash transactions to be posted on a date that is before than the date of the last cash transaction.

9.  Select the **Use confirm status** check box to use an additional confirmed status when you approve the procedures for the cash documents.

10. On the **Number sequences** tab, select a number sequence code for the following references:
    
      - **Cash - exchange adjustment**
    
      - **Cash reimbursement slips**
    
      - **Cash disbursement slips**
    
      - **Report number**
    
      - **Cash correction voucher**

## See also

[(LTU) Generate a cash disbursement slip](ltu-generate-a-cash-disbursement-slip.md)

[Cash and bank management parameters (form)](https://technet.microsoft.com/en-us/library/aa591289\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

