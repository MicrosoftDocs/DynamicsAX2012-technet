---
title: (RUS) Set up a register for the accounts receivable inventory act
TOCTitle: (RUS) Set up a register for the accounts receivable inventory act
ms:assetid: abdec5f8-6ff6-4a4c-a9a1-3e7e0879e11e
ms:mtpsurl: https://technet.microsoft.com/library/JJ711503(v=AX.60)
ms:contentKeyID: 49387828
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for the accounts receivable inventory act 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Accounts receivable inventory act** register displays the accounts receivable balance at the start of the reporting period.

Accounts receivables are created on the basis of the unsettled invoices and advance payments that were made. All unsettled invoices are split into particular debt interval categories.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The exceeded term of debt settlement is determined from the difference between the date of the inventory and the invoice date, taking into account the payment terms.

You must set up the exchange and amount difference parameters before you calculate the accounts receivable registers.

1.  Click Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Accounts receivable inventory act**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period types** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click the **Parameters** tab to set up additional parameters for the register.

10. In the **Register name** field, select **Accounts receivable inventory act**.

11. Click **Specific** to open the **Debt interval** form to set up the debt interval.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-set-up-the-debt-interval-in-accounts-receivable.md">(RUS) Set up the debt interval in Accounts receivable</A>.</P>



12. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Debt interval (form)](https://technet.microsoft.com/library/jj853236\(v=ax.60\))

[(RUS) Calculate the accounts receivable inventory act register](rus-calculate-the-accounts-receivable-inventory-act-register.md)

  


