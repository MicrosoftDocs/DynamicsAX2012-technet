---
title: About fiscal calendars, fiscal years, and periods
TOCTitle: About fiscal calendars, fiscal years, and periods
ms:assetid: ce1bd504-30b6-4c0c-8104-09ed92fcf410
ms:mtpsurl: https://technet.microsoft.com/library/Hh242909(v=AX.60)
ms:contentKeyID: 36059465
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- fiscal calendar
- period
- fiscal year
- period status
- ledger calendar
- fixed asset
- budget cycle
audience: Application User
ms.search.region: Global
---

# About fiscal calendars, fiscal years, and periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Fiscal calendars provide a framework for the financial activity of an organization. Each fiscal calendar contains one or more fiscal years, and each fiscal year contains multiple periods. Fiscal calendars can be based on a January 1 to December 31 calendar year, or on any dates that you select. For example, some organizations select a fiscal calendar that starts on July 1 of one year and ends on June 30 of the following year.

There is no limit to the number of fiscal calendars that you can create, and no limit to the number of fiscal years that can be created for a fiscal calendar. Each fiscal calendar is independent of your organization, and can be used by multiple legal entities in the organization. For example, an organization has eight departments and each department is a separate legal entity. Five of them share the same fiscal calendar and three use different fiscal calendars. You can create one fiscal calendar for the five legal entities that share the same fiscal calendar, and then create separate fiscal calendars for the other legal entities.

## Create fiscal calendars, fiscal years, and periods

You can create and delete fiscal calendars, fiscal years, and periods in the **Fiscal calendars** form. You can also divide existing periods and create closing periods that can be used to close a fiscal year. For more information, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).

## Select fiscal calendars for ledgers, fixed assets, and budget cycles

Fiscal calendars are used with fixed asset depreciation, financial transactions, and budget cycles. When you create a fiscal calendar, you can use it for multiple purposes. You can select a fiscal calendar for a value model or depreciation book to make it a fixed asset calendar. You can select a fiscal calendar for a ledger to make it a ledger calendar. And you can select a fiscal calendar for a budget cycle to make it a budget calendar. You can use the same fiscal calendar for all of these.

## Select a fiscal calendar for your legal entity

Select the fiscal calendar that you want to use for the ledger for your legal entity in the **Ledger** form. For more information, see [Select a fiscal calendar for a ledger](select-a-fiscal-calendar-for-a-ledger.md).

## Select a fiscal calendar for fixed assets

You can select a fiscal calendar for a value model or depreciation book, and that fiscal calendar will be used by the fixed assets that use the selected value model or depreciation book. You can select from any fiscal calendar that is defined in the **Fiscal calendars** form. For more information, see [Value models setup (form)](https://technet.microsoft.com/library/aa582567\(v=ax.60\)) or [Depreciation books setup (form)](https://technet.microsoft.com/library/aa597721\(v=ax.60\)).

## Define budget cycle time spans

Budget cycles are the length of time during which a budget is used. Budget cycles can include part of a fiscal year or multiple fiscal years, such as a biennial budget cycle of two years or a triennial budget cycle of three years. The budget cycle time span defines the number of periods that are included in the budget cycle. To specify the budget cycle time span, use the **Budget cycle time spans** form. For more information, see [Budget cycle time spans (form)](https://technet.microsoft.com/library/hh227604\(v=ax.60\)).

## Maintain periods for your organization

You can use the **Ledger calendar** form to view the details of the fiscal calendar, fiscal years, and periods used by your organization. You can also change the status of the periods and select which users can post accounting transactions to periods. For more information, see [Ledger calendar (form)](https://technet.microsoft.com/library/hh242506\(v=ax.60\)) and [Specify which users can post to a period](specify-which-users-can-post-to-a-period.md).

## Using fiscal calendars if you upgraded from a previous release of Microsoft Dynamics AX

When you upgrade to Microsoft Dynamics AX 2012, you must use the **Upgrade fixed asset calendars** form to upgrade existing fixed asset calendars to fiscal calendars that can be shared by multiple legal entities.

## See also

[Fiscal calendars (form)](https://technet.microsoft.com/library/hh209283\(v=ax.60\))

  


