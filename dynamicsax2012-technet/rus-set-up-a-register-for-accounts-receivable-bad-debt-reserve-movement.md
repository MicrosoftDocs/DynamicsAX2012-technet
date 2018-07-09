---
title: (RUS) Set up a register for accounts receivable bad debt reserve movement
TOCTitle: (RUS) Set up a register for accounts receivable bad debt reserve movement
ms:assetid: 77b6b1fd-c597-430a-86b2-88e75bef26dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678372(v=AX.60)
ms:contentKeyID: 49387602
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for accounts receivable bad debt reserve movement [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Accounts receivable - bad debt reserve movement** register is created for summarizing the information about the bad debt reserve movement, its use, and the comparison of the reserve with the indicators of the reporting period. The register is calculated on the basis of the results of creating and using the bad debt reserve and contains the following information:


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



  - Reserve creation date.

  - Bad debt reserve for a previous period.

  - Bad debt amount.

  - Bad debt reserve that is used at the reporting period to settle unrecoverable debts.

  - Unusable remainder at the reporting date.

  - Unrecoverable debts total exceeding the bad debt reserve total on the reporting date

You must set up the exchange and amount difference parameters before you calculate the accounts receivable registers.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Accounts receivable - bad debt reserve movement**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate the accounts receivable bad debt reserve movement register](rus-calculate-the-accounts-receivable-bad-debt-reserve-movement-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

