---
title: About depreciation
TOCTitle: About depreciation
ms:assetid: c18a10c4-fdf5-4122-ab67-9c3754e1594b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550702(v=AX.60)
ms:contentKeyID: 36676410
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- depreciation
- fixed asset depreciaton
- fixed assets depreciation
audience: Application User
ms.search.region: Global
---

# About depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depreciation is a periodic transaction that typically reduces the value of the fixed asset on the balance sheet, and is charged as an expenditure to a profit and loss account.

Therefore, a main account is usually used for crediting the periodic depreciation on the balance sheet. An offset account is an account in the profit and loss part of the chart of accounts.

## Depreciation adjustment

Usually, only a correction to a posted depreciation transaction is posted as a depreciation adjustment. Therefore, both the main account and offset account are set up just like the accounts for depreciation. A depreciation adjustment can be a positive or a negative amount, but the functionality of the main account (as a balance sheet account) and the offset account (usually as a profit and loss account) remains the same.

## Extraordinary depreciation

Extraordinary depreciation functions like basic depreciation does, which means that a main account is used to credit the depreciation amount to the balance sheet and reduce the value of the fixed asset. An offset account is a profit and loss account, where the depreciation that is calculated for the fiscal period is charged as an expenditure.

Extraordinary depreciation works independently from the basic depreciation. Having extraordinary depreciation as a separate transaction type lets you post and report the extraordinary depreciation separately from the basic depreciation.

## Special allowance depreciation

You can use special allowance depreciation to take extra depreciation amounts during the first year that an asset is placed in service and depreciated. Special allowance depreciation is available only for depreciation books, not value models, and always is taken before any other depreciation calculations.

You can create an unlimited number of special allowance depreciation records. After you assign them to an asset group depreciation book, the special allowance depreciation records are applied to the asset depreciation book.

Special allowance depreciation is entered as a percentage or a fixed amount. When you post depreciation proposals, special allowance depreciation transactions are posted to the depreciation book as transactions that are separate from the depreciation transactions.

## Depreciation calendars

Each depreciation book must have a fiscal calendar that is used when you depreciate fixed assets. You must also select a fiscal calendar for a value model when the associated depreciation method has a fiscal depreciation year, and you use a depreciation method. For more information, see [Depreciation books setup (form)](https://technet.microsoft.com/en-us/library/aa597721\(v=ax.60\)) and [Value models setup (form)](https://technet.microsoft.com/en-us/library/aa582567\(v=ax.60\)).

You can create shared calendars using the **Fiscal calendars** form. (Click **General ledger** \> **Setup** \> **Fiscal calendars**.) For more information, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).

## See also

[Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md)

[Depreciation methods and conventions](depreciation-methods-and-conventions.md)

[Fiscal calendars (form)](https://technet.microsoft.com/en-us/library/hh209283\(v=ax.60\))

  


