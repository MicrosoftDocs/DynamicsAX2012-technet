---
title: 'Key tasks: Determine benefit eligibility'
TOCTitle: 'Key tasks: Determine benefit eligibility'
ms:assetid: 22762fd9-a19d-4899-a01e-3fa1dc4b0245
ms:mtpsurl: https://technet.microsoft.com/library/JJ680903(v=AX.60)
ms:contentKeyID: 49624324
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- benefit eligibility
- eligibility event
- open enrollment
- eligible workers
- qualified life event
audience: Application User
ms.search.region: Global
---

# Key tasks: Determine benefit eligibility 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

These tasks allow you to determine the benefits that each worker in your organization is eligible for, and to ensure that only eligible workers are allowed to enroll in benefits.

## What do you want to do?

Learn more about...

Prerequisites

Create an eligibility event

Test an eligibility event

Troubleshoot inaccurate eligibility test results

Process eligibility for benefits

Enroll workers in benefits

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Setting up Payroll: Basic topics](setting-up-payroll-basic-topics.md)

## Prerequisites

Before you can determine the benefits that workers are eligible for, the following setup tasks must have been completed.

  - The benefit eligibility policy and eligibility rules for your organization must be defined. For more information, see [Key tasks: Benefit eligibility policies](key-tasks-benefit-eligibility-policies.md).

  - The benefits must be created in the system so that they can be assigned to workers. We recommend that you pay particular attention to effective dates, eligibility rules, and eligibility overrides. For more information, see [Create a new benefit](create-a-new-benefit.md). If you are using the Payroll module, see [Benefit setup tasks](benefit-setup-tasks.md).
    

    > [!IMPORTANT]
    > <P>Mandatory deductions, such as garnishments or tax levies, are managed as benefits. However, they should not be subjected to the normal benefit eligibility process. To allow a worker to be enrolled in a mandatory deduction without eligibility processing, you must select <STRONG>Bypass eligibility process</STRONG> in the <STRONG>Eligibility</STRONG> field on the <STRONG>Eligibility rules</STRONG> FastTab in the <STRONG>Benefits</STRONG> form.</P>



  - Settings for worker characteristics that affect benefit eligibility, such as marital status or position assignment, must be kept up to date. For more information, see [Key tasks: Workers](key-tasks-workers.md).

Back to top

## Create an eligibility event

1.  Open the **Eligibility event details** form. Depending on how you open the form, some information may be entered for you when you open it.
    
      - To create an event for many workers and many benefits, such as for your annual open enrollment period, open the form from the Eligibility events list page:
        
        Click **Human resources** \> **Periodic** \> **Benefits** \> **Eligibility events**. In the **Action Pane**, in the **New** group, click **Event**. Enter a name and description for the new event, and click **Create event**.
        
        The form will be blank when you open it, but you can quickly add all workers and all benefits.
    
      - To create an event for a single worker or a small number of workers, for example, when you hire a new worker, or when a worker has a qualified life event, open the form from the Workers list page:
        
        Click **Human resources** \> **Common** \> **Workers** \> **Workers**. Select one or more workers. In the **Action Pane**, in the **Personnel actions** group, click **Create eligibility event**. Enter a name and description for the new event, and click **Create event**.
        
        The selected workers will be entered on the form for you.
    
      - To create a benefit for a single benefit or a small number of benefits, for example, if you add a new benefit mid-year, open the form from the Benefits list page:
        
        Click **Human resources** \> **Common** \> **Benefits** \> **Benefits**. Select one or more benefits. In the **Action Pane**, in the **Personnel actions** group, click **Create eligibility event**. Enter a name and description for the new event, and click **Create event**.
        
        The selected benefits will be entered on the form for you.
    

    > [!TIP]
    > <P>We recommend that you use a naming scheme that allows similar events to sort together on the <STRONG>Eligibility events</STRONG> list page. For example, your open enrollment events might be OE plus the year, such as OE2012, OE2013, OE2014, and so on.</P>



2.  Enter the following information on the **General** FastTab:
    
      - In the **Event type** field, select the type of eligibility event.
        

        > [!NOTE]
        > <P>If you are testing the event, and do not plan to enroll workers in benefits based on the results, select <STRONG>Test</STRONG>. The other event types are available for you to use when you sort events on the <STRONG>Eligibility events</STRONG> list page, but they do not affect how the event functions.</P>

    
      - In the **Coverage start date** field, select the date that will be used to determine eligibility for benefits.
        
        For example, your open enrollment event might have a coverage start date of January 1, 2015. For a worker to be eligible for a benefit, the benefit must be active on that date, and the worker must meet all the eligibility requirements for the benefit on that date. If a non-management worker will be promoted to a management position on February 1, 2015, they will not be found eligible for management-only benefits for the open enrollment event with a coverage start date of January 1, 2015.
    
      - In the **Enrollment period start date** field, select the first day of the period when a worker can enroll in benefits. For open enrollment periods, this is usually a month or more before the **Coverage start date**. For eligibility events that result from a qualified life event, it may be the same as the **Coverage start date**.
    
      - In the **Days to enroll** field, enter the number of calendar days that are in the enrollment period.

3.  On the **Workers** FastTab, click **Add** to add a single worker, or click **Add all workers** to add all workers who have an active employment, or who have an employment that is scheduled to become active in the future. Select one or more workers and click **Remove** to remove workers from the list.
    
    The listed workers will be evaluated to determine whether they are eligible for the selected benefits.

4.  On the **Benefits** FastTab, click **Add** to add a single benefit, or click **Add all benefits** to add all benefits that are active or that are scheduled to become active in the future. Select one or more benefits and click **Remove** to remove benefits from the list.
    
    The benefit eligibility rules will be used to determine which of the listed benefits the selected workers are eligible for.

Back to top

## Test an eligibility event

By testing an eligibility event, you can determine whether an eligibility rule produces the results that you expect. The results cannot be used to enroll workers in benefits, but are used only to verify that the correct workers are found eligible for each benefit.

We recommend that you run a sample test of a small number of workers and the benefits that you know those workers should be eligible for. For example, you might have a benefit that is provided only to company executives. To test eligibility for this benefit, you would select the executive-only benefit, another benefit that is not restricted to executives, and a small number of workers, some who are executives and some who are not. By analyzing the results, you can be sure that the eligibility process determines eligibility correctly.

1.  Click **Human resources** \> **Periodic** \> **Benefits** \> **Eligibility events**.

2.  Double-click the eligibility event to test.

3.  In the **Event type** field, select **Test**.

4.  Determine which benefits to test eligibility processing for.
    
      - To test an eligibility rule, select at least one benefit that uses the rule and one benefit that does not use the rule. For each benefit, on the **Benefits** FastTab, click **Add**, and then select the benefit.
    
      - To validate all benefits before an open enrollment period, on the **Benefits** FastTab, click **Add all benefits**.

5.  Determine which workers that you want to use to test the eligibility event. You will want to use a few workers whom you expect will be eligible, and a few whom you expect to be ineligible. For each worker, on the **Workers** FastTab, click **Add**, and then select the worker.

6.  In the **Action Pane**, in the **Actions** group, click **Process**.
    
    While the eligibility process is running, only the **Refresh** button on the **Action Pane** is available.

7.  When the eligibility process has completed, click **Show results**.
    
    If the results are correct, the test is finished. If the results are incorrect, see “Troubleshoot inaccurate eligibility test results” in this topic.

Back to top

## Troubleshoot inaccurate eligibility test results

Although there are ways to bypass eligibility or to provide eligibility overrides, you can protect the integrity of your benefit program by detecting and correcting the errors that caused inaccurate eligibility test results.

  - Verify that the correct eligibility rule is assigned to each benefit that had an incorrect result. To do this, on the **Benefits** FastTab, click the name of the benefit to open the details form for the benefit. If necessary, correct the settings on the **Eligibility rules** FastTab, and then close the form.

  - If you are testing a new eligibility rule, verify that the conditions on the rule have been set up correctly. For more information, see [Key tasks: Benefit eligibility policies](key-tasks-benefit-eligibility-policies.md).

  - Verify that the worker data is set up correctly for each worker who had an incorrect result. To do this, on the **Workers** FastTab, click the name of the worker to open the details form for the worker. Inspect the worker settings that are used by the eligibility rules that created incorrect results. If necessary, correct the settings, and then close the form.

  - If a worker is not eligible for a benefit based on the eligibility rules, but you want to be able to enroll the worker in the benefit, set up an override for the worker. To do this, on the **Benefits** FastTab, click the name of the benefit to open the details form for the benefit. On the **Eligibility overrides** FastTab, click **Add** to select the worker. After you have added all the workers whom should have an override, close the form.

When you have made all necessary corrections, repeat the test.


> [!NOTE]
> <P>Test results cannot be used to enroll workers in benefits.</P>



Back to top

## Process eligibility for benefits

Benefits and mandatory deductions that you have set to bypass eligibility processing will not be included in the eligibility process. You can enroll workers in those benefits at any time.

Benefits that you have set to have all workers eligible for will be included in the eligibility process. All workers will be determined to be eligible for these benefits.

1.  Click **Human resources** \> **Periodic** \> **Benefits** \> **Eligibility events**.

2.  Double-click the eligibility event to process.

3.  If the **Event type** is **Test**, change the **Event type**.

4.  Determine which benefits to process eligibility for.
    
      - For each benefit, on the **Benefits** FastTab, click **Add**, and then select the benefit.
    
      - To process eligibility for all benefits, such as for an annual open enrollment period, on the **Benefits** FastTab, click **Add all benefits**.

5.  Determine which workers to process eligibility for.
    
      - For each worker, on the **Workers** FastTab, click **Add**, and then select the worker.
    
      - To process eligibility for all workers, such as for an annual open enrollment period, on the **Workers** FastTab, click **Add all workers**.

6.  In the **Action Pane**, in the **Actions** group, click **Process**.
    
    While the eligibility process is running, only the **Refresh** button on the **Action Pane** is available.

7.  When the eligibility process is complete, click **Show results** and verify that the results are as you expected them to be.

Back to top

## Enroll workers in benefits

After you have determined eligibility, you can enroll workers in benefits.

  - To enroll many workers in benefits, as you would do after your annual open enrollment period, see [Enroll multiple workers in a benefit at the same time](enroll-multiple-workers-in-a-benefit-at-the-same-time.md).

  - To enroll a single worker in benefits, as you would do for a new hire or after a worker has a qualified life event, see [Enroll and remove benefits for workers](enroll-and-remove-benefits-for-workers.md).

Back to top

## Find form help

[Eligibility event details (form)](https://technet.microsoft.com/library/jj677453\(v=ax.60\))

[Benefits (form)](https://technet.microsoft.com/library/jj680907\(v=ax.60\))

[Workers (form)](https://technet.microsoft.com/library/aa583961\(v=ax.60\))

[Event processing results (form)](https://technet.microsoft.com/library/jj677429\(v=ax.60\))

## Find related tasks

[Key tasks: Benefit eligibility policies](key-tasks-benefit-eligibility-policies.md)

[Key tasks: Workers](key-tasks-workers.md)

[Create a new benefit](create-a-new-benefit.md)

[Enroll and remove benefits for workers](enroll-and-remove-benefits-for-workers.md)

[Enroll multiple workers in a benefit at the same time](enroll-multiple-workers-in-a-benefit-at-the-same-time.md)

  


