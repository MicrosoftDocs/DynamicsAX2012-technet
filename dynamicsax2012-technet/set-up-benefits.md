---
title: Set up benefits
TOCTitle: Set up benefits
ms:assetid: ec44f6f5-97f5-4b2f-be82-c6d079d4b238
ms:mtpsurl: https://technet.microsoft.com/library/Hh227496(v=AX.60)
ms:contentKeyID: 36059893
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- how to
- howto
- how-to
- provider
- benefits
- benefit options
- coverage
- medical
- benefit plan
- create benefit
- setup benefits
- set up benefits
audience: Application User
ms.search.region: Global
---

# Set up benefits 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic only applies to versions that were released prior to Microsoft Dynamics AX 2012 R2. If you are using AX 2012 R2 or AX 2012 R3, see <A href="create-a-new-benefit.md">Create a new benefit</A>. If you are using the Payroll module, see <A href="benefit-setup-tasks.md">Benefit setup tasks</A> or <A href="garnishment-and-tax-levy-setup-tasks.md">Garnishment and tax levy setup tasks</A>.</P>



You can set up current and future benefits that workers and their dependents and beneficiaries can receive. Examples of benefits include medical, investments, and parking benefits.

Benefits are defined by benefit types, plans, and options:

  - Type – A collection of plans for a specific benefit, such as medical or parking.

  - Plan – A specific benefit contracted from a provider.

  - Option – The coverage level, such as employee only or employee and spouse.

## Set up a new benefit

Use the **Benefits** form to set up new benefits to assign to your workers.

1.  Click **Human resources** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  In the **Types** area, click **New** to create a benefit type.

3.  Type the name of the benefit type and a description.

4.  Select one of the following options:
    
      - **Multiple enrollments per type** – You can enroll a worker in multiple plans with the same benefit type, even if the enrollment is effective for the same period. For example, two term life insurance plans.
    
      - **One enrollment per type** – You cannot enroll a worker in more than one plan with the same benefit type for the same period. For example, if the worker already has health insurance for a specified time period, you cannot assign another health insurance that covers the same period.

5.  In the **Plans** area, click **New** to create a benefit plan.

6.  Enter the name of the benefit plan, a description, and select the benefit type.

7.  In the **Options** area, click **New** to create a benefit option.

8.  Type the name of the option and a description.

9.  To allow dependents to be covered under the benefit, select the **Allow dependent coverage** check box.

10. To allow beneficiaries to be designated to the benefit, select the **Allow beneficiary designations** check box.

11. To add an option to the benefit plan, in the **Plans** area, click **Add**.

12. In the **Option** field, select a benefit option to add to the benefit plan.

13. In the **Effective** field, enter the first date when the option is available to the worker.

14. In the **Expiration** field, enter the last date when the option is available to the worker.

15. To view options effective for a specific date, click **Date options** and enter the dates to view.

## See also

[Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\))

[Benefits (list page)](https://technet.microsoft.com/library/hh242723\(v=ax.60\))

[Enroll and remove benefits for workers](enroll-and-remove-benefits-for-workers.md)

  


