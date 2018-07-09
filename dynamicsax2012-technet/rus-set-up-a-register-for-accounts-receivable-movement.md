---
title: (RUS) Set up a register for accounts receivable movement
TOCTitle: (RUS) Set up a register for accounts receivable movement
ms:assetid: 53445531-7a79-4e89-99f4-a546c618a6cd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665387(v=AX.60)
ms:contentKeyID: 49387475
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for accounts receivable movement [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Accounts receivable movement** register is created to summarize the information about accounts receivable movement operations for the purpose of revealing bad debt amounts. This account is necessary when a taxpayer creates bad debt reserves and unrecoverable debts that are considered in the breakdown of the taxpayer's expenses, as specified under Section 25 of the RF Tax Code.

Entries are created in the register for all events of an occurrence or settlement (write-off) by the taxpayer of accounts receivable on any grounds from the start of the tax period until the reporting date. Overpayment amounts to budgets of various levels are not displayed in this register.

Entries are also created for every event of debt revaluation for foreign currency vouchers.

Register maintenance should ensure the possibility of:

  - Grouping information on the object and name (type) of the vouchers resulting in the occurrence of accounts receivable.

  - Grouping the debt on the basis of the periods of its appearance.

  - Creating amounts of unsettled accounts receivable at the reporting date.

  - Determining at the reporting date the unrecoverable debt total to be included in the list of expenses for the tax purposes.

You must set up the exchange and amount difference parameters before you calculate the accounts receivable registers.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Accounts receivable movement**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate the accounts receivable movement register](rus-calculate-the-accounts-receivable-movement-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

