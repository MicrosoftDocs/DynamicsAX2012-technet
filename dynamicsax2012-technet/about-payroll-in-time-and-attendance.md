---
title: About payroll in Time and attendance
TOCTitle: About payroll in Time and attendance
ms:assetid: fc0eb584-b49c-4cc4-88f0-8709d072d5ce
ms:mtpsurl: https://technet.microsoft.com/library/Aa499883(v=AX.60)
ms:contentKeyID: 44081063
author: tfehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About payroll in Time and attendance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To use registrations in **Time and attendance** as the basis for salary payments, you must set up payroll integration.

## Pay types

You use pay types when you set up pay agreements. Examples of pay types include hourly wage and overtime bonus, but you can set up many types of bonuses and premiums.

You can set up a pay type as a fixed amount or as a percentage of another pay type. For example, you can set up an overtime bonus as a percentage of the hourly wage.

Workers can have specific rates for each pay type, and rates can also be set up so that they are valid for only a limited period.

When you set up parameters in **Time and attendance**, you select whether pay rates are used to calculate costs. If pay rates are not used, costs are calculated based on cost categories.

## Pay agreements

Set up a pay agreement for each group of workers that are paid according to the same general agreement.

Workers may be paid according to the same pay agreement but receive different rates or bonuses. For example, a bonus can be related to seniority, a specific operation, or an activity.

Use pay agreements to define the pay types that you want to use for the work hours that are specified for profile types. Typical types of work hours, or profile types, are standard time, overtime, and premiums. You can also allow for flexible hours in pay agreements by setting up pay agreement lines that use the **Flex+** and **Flex-** wage types. Pay is not automatically generated for these wage types.

Pay calculations also relate to how calculation parameters are set up. For more information, see [About parameters for calculations](about-parameters-for-calculations.md).

## Issues to consider

Before you set up a pay agreement, you should consider some important issues. The following list contains examples of relevant considerations.

  - **Basic pay** – What is the hourly wage? Do you want to consider evening and night bonuses?

  - **Overtime** – Does your company use more than one overtime bonus rate? Is overtime calculated per day, week, or month?

  - **Flextime** – How does flextime influence pay? Do you want to transfer flex registrations to the payroll system?

  - **Automatic premiums** – Are specific bonuses required for operations, specific shifts, special skills, or seniority?

  - **Manual premiums** – Are special forms of compensation added manually when workers’ registrations are approved? For example, compensation for mileage.

## Pay adjustment

You can use pay adjustments to calculate the correct wages. In **Time and attendance**, pay time is calculated every day. But in some cases, pay time cannot be calculated until the end of the week.

For example, if a worker worked overtime on Monday, but is late for work on Tuesday, the worker may receive reduced overtime pay for Monday. The pay adjustment feature is intended for such a scenario. For more information about pay adjustments, see [About pay adjustments and count units](about-pay-adjustments-and-count-units.md).

## Count units

You can delimit a pay agreement line by creating a count unit and adding that count unit to the pay agreement line.

For example, a premium is paid only when a worker has worked on a specific operation for more than 12 hours in the same week. The count unit counts every hour on this operation and pays a premium only if the worker works more than 12 hours in one week. For more information about count units, see [About pay adjustments and count units](about-pay-adjustments-and-count-units.md).

## Automatic premiums

In a pay agreement, you can set up automatic premiums. For example, an automatic premium or bonus can be set up for workers who work on a specific operation.

## Manual premiums

You can add manual premiums, such as mileage, to a worker’s registrations when you approve the registrations. Manual premiums can be based on a pay type. For information about how to add manual premiums, see [Modify registrations before or after approval](modify-registrations-before-or-after-approval.md).

## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[Create pay types in time and attendance](create-pay-types-in-time-and-attendance.md)

  


