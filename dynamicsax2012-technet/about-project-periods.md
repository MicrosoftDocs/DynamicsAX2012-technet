---
title: About project periods
TOCTitle: About project periods
ms:assetid: 862945c5-31b0-4e30-a2c6-d5f995b738e4
ms:mtpsurl: https://technet.microsoft.com/library/Hh500665(v=AX.60)
ms:contentKeyID: 37822150
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About project periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Project periods are used primarily with project timesheets, but they are also used when you work with estimates and invoice subscriptions.

## Project periods for timesheets

Project periods are used to define the length of a timesheet period. They are also used to generate timesheet reports, including missing timesheet reports, and to calculate hour utilization. Workers are required to submit a timesheet at the end of a period.

It is not mandatory to assign periods to workers, but we recommend that you create and assign project periods to workers who register hour transactions. These project periods make it easier to track hour transactions that are entered for the same period.

You must assign a period type and a period frequency to each project period that you create. For example, if hours are reported weekly, create a period type, and assign the period frequency **Week** to it.

The period frequency options that you can choose from are derived from the ledger periods that are created in Microsoft Dynamics AX. You can choose from four period frequencies that can be assigned to timesheet periods:

  - Weekly

  - Bi-weekly

  - Semi-monthly

  - Monthly

## Project periods for estimates

Project periods are used by the estimate system to recognize revenue for an estimate period in Fixed-price projects. The project period that you assign to an estimate is used to specify the estimate frequency. For more information, see [About estimate periods](about-estimate-periods.md) and [About estimates](about-estimates.md).

## Project periods for invoicing subscriptions

To invoice a subscription, a project period is required. This is because invoicing does not necessarily follow the period code interval that was defined for a worker. For example, the timesheet period that is specified for workers might be one week. However, if invoicing is performed monthly, and a week spans two calendar months, that week must be split. For more information about invoicing subscription transactions, see [Invoice subscription transactions](invoice-subscription-transactions.md). For more information about splitting timesheet periods, see [Generate timesheet periods](generate-timesheet-periods.md).

## Setting up periods

Setting up periods consists of the following tasks:

1.  Create period types, and then generate periods for the period types. You can split periods as required. For example, a week that extends across two months can be split into two periods.
    

    > [!IMPORTANT]
    > <P>Periods must be split before worker periods are created.</P>



2.  Define a period code for each frequency that workers submit hours for in various projects. For example, one project might require weekly timesheets. Another project might require bi-weekly timesheets.

3.  Associate the periods that you generated with workers based on their individual period codes.

## See also

[About estimate periods](about-estimate-periods.md)

[Assign and maintain worker periods](assign-and-maintain-worker-periods.md)

[Generate timesheet periods](generate-timesheet-periods.md)

[Place a period on hold](place-a-period-on-hold.md)

[Set up pay periods for time registration workers](set-up-pay-periods-for-time-registration-workers.md)

  


