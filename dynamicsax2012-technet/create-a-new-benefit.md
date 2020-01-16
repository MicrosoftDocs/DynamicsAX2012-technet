---
title: Create a new benefit
TOCTitle: Create a new benefit
ms:assetid: a4d1d319-f2e3-4b36-bd86-c8ca9e63514d
ms:mtpsurl: https://technet.microsoft.com/library/JJ680905(v=AX.60)
ms:contentKeyID: 49624326
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- dependents
- benefit plan
- beneficiaries
- benefit option
- benefit type
- benefit
- benefit element
audience: Application User
ms.search.region: Global
---

# Create a new benefit 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>Use this procedure if you are using Microsoft Dynamics AX 2012 R2 or AX 2012 R3 and if you are not using the Payroll module. If you are using Payroll, see <A href="benefit-setup-tasks.md">Benefit setup tasks</A> or <A href="garnishment-and-tax-levy-setup-tasks.md">Garnishment and tax levy setup tasks</A>. If you are using a version prior to AX 2012 R2, see <A href="set-up-benefits.md">Set up benefits</A>.</P>



You can set up current and future benefits that workers and their dependents and beneficiaries can receive. Examples of benefits include medical, investments, and parking benefits.

A benefit is a combination of three benefit elements: a benefit type, plan, and option:

  - **Type** – A collection of plans for a specific benefit, such as medical or parking.

  - **Plan** – A specific benefit contracted from a provider.

  - **Option** – The coverage level, such as employee only or employee and spouse.

After you have set up benefit elements, you must create the benefits so that they can be assigned to workers. When you create a new benefit, you link an option to a benefit plan, designate a benefit period, and assign eligibility rules to the benefit.

## Set up benefit elements

Use the **Benefit elements** form to set up new benefits that you can assign to your workers.

1.  Click **Human resources** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  In the **Types** area, click **New** to create a benefit type.

3.  Type the name of the benefit type and a description.

4.  Select one of the following concurrent enrollment options:
    
      - **Multiple enrollments per type** – You can enroll a worker in multiple plans with the same benefit type, even if the enrollment is effective for the same period. For example, a worker can be enrolled in two term life insurance plans.
    
      - **One enrollment per type** – You cannot enroll a worker in more than one plan with the same benefit type for the same period. For example, if the worker already has health insurance for a specified time period, you cannot enroll the worker in another health insurance plan that covers the same period.

5.  In the **Plans** area, click **New** to create a benefit plan.

6.  Enter the name of the benefit plan, a description, and select the benefit type.

7.  In the **Options** area, click **New** to create a benefit option.

8.  Type the name of the option and a description.

9.  To allow for dependents to be covered under the benefit, select the **Allow dependent coverage** check box.

10. To allow the benefit to be designated to beneficiaries, select the **Allow beneficiary designations** check box.

11. When you have finished setting up benefit elements, close the form.

## Create a new benefit

After you have created benefit elements, you can create the benefits that you can enroll workers in.

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefits**.

2.  In the **New** group, click **Benefit** and enter the following information:
    
      - **Plan** – The name of the benefit.
    
      - **Option** – An option to add to the benefit.
    
      - **Effective** – The first date when the benefit is available to a worker.
    
      - **Expiration** – The last date when the benefit is available to a worker.

3.  Click **Create benefit**.

4.  Click **Edit** and expand the **Eligibility rules** FastTab to select the method to use to determine eligibility for this benefit.
    
      - **All workers are eligible** – The benefit is included in eligibility processing, but eligibility rules are not enforced for the benefit. All workers are always eligible.
        
        When you select this method, any worker who is included in an eligibility event can enroll in the benefit after the event is processed, but not at any other time. This lets you restrict enrollment in the benefit to appropriate enrollment periods, without otherwise limiting eligibility for the benefit.
    
      - **Rule based** – User-defined eligibility rules will be enforced for the benefit. Select the rule type to use from the **Rule type** list.
        
        This method is used for most benefits.
    
      - **Bypass eligibility process** – The benefit is not included in eligibility processing. Any worker can be enrolled in the benefit at any time. You do not have to process an eligibility event before you enroll a worker in the benefit.
        
        This method is usually used for garnishments and tax levies.

5.  Optional: If there are workers who should be allowed to enroll in this benefit, but who do not meet the criteria in the eligibility rules, assign eligibility override for those workers.
    
    1.  Expand the **Eligibility overrides** FastTab.
    
    2.  Click **Add**.
    
    3.  In the **Name** field, select the worker to add an override for.
    
    4.  In the **Override start** and **Override end** fields, enter the first and last dates when the override applies. When you determine eligibility for a benefit using a **Coverage start date** that is in the specified date range, the employee will be eligible for the benefit, regardless of the benefit eligibility rules.

6.  Close the form.

## See also

[Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\))

[Benefits (form)](https://technet.microsoft.com/library/jj680907\(v=ax.60\))

[Enroll and remove benefits for workers](enroll-and-remove-benefits-for-workers.md)

  


