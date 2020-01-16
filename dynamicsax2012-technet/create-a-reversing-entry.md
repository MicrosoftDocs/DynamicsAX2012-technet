---
title: Create a reversing entry
TOCTitle: Create a reversing entry
ms:assetid: 4f88d335-9d75-4e07-b6cb-f372ec45f3f5
ms:mtpsurl: https://technet.microsoft.com/library/Gg212760(v=AX.60)
ms:contentKeyID: 36057223
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a reversing entry 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create reversing transactions, which are transactions that are automatically reversed on a specified date, for the purpose of accruals.


> [!NOTE]
> <P>For accruals that occur on a consistent basis, you should set up accrual schemes. For more information, see <A href="create-accrual-schemes.md">Create accrual schemes</A>.</P>



If you enter a general journal transaction with a reversing date, when the transaction is posted, the original transaction is posted using the transaction date and the reversal transaction is posted using the reversing date.

For example, a company that pays its employees every two weeks might have a pay period that spans multiple fiscal periods, such as March 26 through April 9 for a company that uses monthly fiscal periods. If payroll costs must be reported on the financial statement for the period in which they occur, a transaction is entered to record the costs incurred in the actual fiscal period. In this example, a reversing transaction is entered in March to reflect the payroll amounts for March 26 through March 31, so that the March financial statements accurately reflect this information. This transaction is set to reverse on the first day of the next fiscal period, April 1, because the actual pay run will occur in April, and the transactions will then be created.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Select a journal or press CTRL+N to create a journal.

3.  Select the **Reversing entry** check box.

4.  Enter the default date when the transactions should be reversed in the **Reversing date** field. The default date will be applied to the transactions entered in the **Journal voucher** form for the selected journal.

5.  To change the reversing date of an individual transaction in this journal, click the **Lines** button to open the **Journal voucher** form. Enter a new date in the **Reversing date** field.
    

    > [!NOTE]
    > <P>The same reversing date is assigned to all entries in a voucher. If you modify the reversing date for an entry in a voucher, all other entries in that voucher automatically will be modified to use the same date. A reversing voucher is generated for each voucher that contains entries with a reversing date at posting time.</P>



## See also

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Journal voucher - General journal (form)](https://technet.microsoft.com/library/aa591466\(v=ax.60\))

  


