---
title: About cost accounting integration
TOCTitle: About cost accounting integration
ms:assetid: 75d4a648-2c4a-4d4e-8993-1479db5e876b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550032(v=AX.60)
ms:contentKeyID: 36058179
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About cost accounting integration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

**Cost accounting** integrates with the following modules:

  - **General ledger**

  - **Production control**

  - **Project management and accounting**

## Cost accounting and General ledger

The **General ledger** module is the main link to **Cost accounting**. All financial values in Microsoft Dynamics AX pass from **General ledger** to **Cost accounting**.

When you first set up **Cost accounting** and set the parameters in the **Cost accounting parameters** form, you must make several decisions regarding integration. Base your decisions on the following issues:

  - The dimensions to use in **Cost accounting**

  - Whether the cost categories in **Cost accounting** should be identical to the ledger accounts in **General ledger**

  - The posting layers that are important for **Cost accounting**

There are additional potential integration points for budgeting between **Cost accounting** and ledger accounts in **General ledger**. For example, you can import financial budget values from **Cost accounting** or transfer **Cost accounting** budgets to the ledger accounts in **General ledger**.

## Cost accounting and Production

Integrate **Cost accounting** and **Production control** by importing production hours from production orders to the **Service category** tab in the **Cost categories** form. You define the integration in the **Service transactions** field group. You must select dimensions in the **Debit dimension** and the **Credit dimension** fields to determine how to credit and how to debit the service quantity.

## Cost accounting and Project

You can also integrate **Project** by setting up the **Service category** tab in the **Cost categories** form. You must select the dimension to credit and the dimension to debit.

## See also

[Setting up and maintaining cost accounting](setting-up-and-maintaining-cost-accounting.md)

  


