---
title: (RUS) Set up a register for accounts payable movement
TOCTitle: (RUS) Set up a register for accounts payable movement
ms:assetid: 674bcaac-50ca-4bf1-9847-0fb359355377
ms:mtpsurl: https://technet.microsoft.com/library/JJ665463(v=AX.60)
ms:contentKeyID: 49387550
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for accounts payable movement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Accounts payable movement** register is a summary of information about an accounts payable movement that is considered to be an expense under the RF tax code. You must set up the exchange and amount difference parameters before you calculate the accounts payable registers.

The register entries reflect all of the taxpayer's accounts payable transactions made between the beginning of the tax reporting period and the reporting date. Entries are created for each instance of debt revaluation for vouchers in a foreign currency. The taxpayer's accounts payable amounts at various levels budgets are not displayed in this register. The register should be maintained to allow grouping of information about the object and naming (type) of vouchers that result in the occurrence of accounts payable, creating an unsettled accounts payable amount at the reporting date, and specifying all accounts payable that have an expired claim term or are subject to amortization for other reasons on the accounting date.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Accounts payable movement**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

10. Click **General ledger** \> **Setup** \> **Profit tax** \> **Register parameters** to set up additional parameters for the register.

11. In the **Register name** field, select **Accounts payable movement**.

12. Click **Specific** to open the **Debt interval** form to set up the debt interval.
    

    > [!NOTE]
    > <P>For more information, see.</P>



13. Press CTRL+S or close the form.

## See also

[(RUS) Calculate the accounts payable movement register](rus-calculate-the-accounts-payable-movement-register.md)

  


