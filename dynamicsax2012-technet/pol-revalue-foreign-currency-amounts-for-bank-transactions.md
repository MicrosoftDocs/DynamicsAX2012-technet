---
title: (POL) Revalue foreign currency amounts for bank transactions
TOCTitle: (POL) Revalue foreign currency amounts for bank transactions
ms:assetid: e4ee8a37-2cfd-4de2-8d09-53d83b3a0c59
ms:mtpsurl: https://technet.microsoft.com/library/JJ711314(v=AX.60)
ms:contentKeyID: 49387132
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Revalue foreign currency amounts for bank transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can revalue foreign currency amounts for bank transactions, and you can create a report to view the bank transactions that have adjustments for foreign currency revaluations.

## Revalue foreign currency amounts for bank transactions

1.  Click **Cash and bank management** \> **Periodic** \> **Bank** \> **Bank - Exchange adjustment (FIFO/LIFO)**.

2.  In the **On date** field, enter an end date for the revaluation.
    
    Only transactions that have a date that is before the date that is specified here are included in the calculation.

3.  Click **Select**, and then click **Add** to add a bank account.
    
    If you do not specify a bank account, amounts are revaluated for all bank accounts.

4.  Click **OK** to close the query form. In the **Foreign currency revaluation** form, select the **Recalculation** check box to revalue foreign currency amounts for all open periods.

## Create a report to view bank transactions that have adjustments for foreign currency revaluations

1.  Click **Cash and bank management** \> **Reports** \> **Transactions** \> **Bank - Exchange adjustment**.

2.  Click **Select** to select one or more bank accounts to view information for.
    
    If you leave the **Bank account** field blank, you can view the bank transaction details for all bank accounts.

3.  Click **OK** to generate the report.

  


