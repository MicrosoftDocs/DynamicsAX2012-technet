---
title: (RUS) About tax liabilities and asset calculation registers
TOCTitle: (RUS) About tax liabilities and asset calculation registers
ms:assetid: 2980075e-9191-4075-a5a3-bcd2220e1aa6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ839657(v=AX.60)
ms:contentKeyID: 50396804
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- register
- asset calculation register
- tax liabilities
---

# (RUS) About tax liabilities and asset calculation registers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Expense registers and revenue registers are used to calculate the tax base for profit tax. A constant tax difference is the accounting profit or loss that is excluded from the tax base when tax is calculated on profit. Some accounting expenses or revenues do not contribute to tax base creation for profit tax in either the current or subsequent reporting periods. A constant difference is a constant tax liability or constant tax asset.

Temporary tax differences occur if expenses or revenues generate an accounting profit in one reporting period and a taxable base in other reporting periods, which results in a deferred tax on profit.

Based on the impact on taxable profit, temporary differences are classified as deductible or taxable. Therefore, a deferred tax on profit is created either as a deferred tax asset or a deferred tax duty.

You can specify the grouping level for the tax difference transactions in the **General ledger parameters** form. For more information, see [(RUS) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj923603\(v=ax.60\))

The constant tax and temporary tax difference amounts are displayed in the accounting records as follows:

  - **CTA** – The tax amount is a constant tax asset (CTA).

  - **CTL** – The tax amount is a constant tax liability (CTL).

  - **DTA** – The tax amount is a deferred tax asset (DTA).

  - **DTL** – The tax amount is a deferred tax liability (DTL).

  - **Writing off DTL** – The tax amount is a DTL that is written off.

  - **Writing off DTA** – The tax amount is a DTA that is written off.

## See also

[(RUS) Set up a register for the calculation of constant tax differences](rus-set-up-a-register-for-the-calculation-of-constant-tax-differences.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

