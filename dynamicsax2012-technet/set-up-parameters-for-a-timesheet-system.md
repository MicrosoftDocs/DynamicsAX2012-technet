---
title: Set up parameters for a timesheet system
TOCTitle: Set up parameters for a timesheet system
ms:assetid: ee53b57f-990b-43de-a502-580a2d04f867
ms:mtpsurl: https://technet.microsoft.com/library/Hh227502(v=AX.60)
ms:contentKeyID: 36059908
author: Khairunj
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- timesheet management
- timesheet setup
- configure timesheets
audience: Application User
ms.search.region: Global
---

# Set up parameters for a timesheet system 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure options for your organization’s timesheet system by using the **General** and **Timesheet** areas in the **Project management and accounting parameters** form.

**Prerequisites**   
In addition to setting up the parameters that are described in this topic, you must make sure that each worker record is associated with a period type, and that timesheet periods are generated. For more information, see [Create and generate timesheet periods](create-and-generate-timesheet-periods.md) and [Update worker periods (class form)](https://technet.microsoft.com/library/aa620393\(v=ax.60\)).


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Set up parameters for a timesheet system

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the left pane, click **Timesheet**.

3.  If you want it to be possible for workers in one legal entity to enter timesheet hours for work performed as a loaned resource in another legal entity, select the **Enable intercompany resource scheduling and timesheets** check box.

4.  In the **Day week starts** field, specify the day of the week that you want to appear as the default in the **Day week starts** field in the **Period types** form.

5.  In the **Maximum number of timesheets per period** field, enter the maximum number of timesheets that a worker can enter for a time period. Enter 0 if you do not want to enforce a maximum number of timesheets.

6.  If you want workers to be able to save their most common projects and activities for repeated use, select the **Use favorites** check box.

7.  In the **Minimum time increment** field, enter a value to specify the minimum time increment that workers can enter for a project task. Enter the value as a fraction of an hour between 0.00 and 0.99. If you do not want to enforce the minimum time increment and want to allow any value, enter 0. This setting can be overridden at the project level.

8.  If you want to define whether the requirement for a worker to enter start and stop times is enabled by default when a new worker profile is created, select the **Require start/stop time** check box.

9.  If you selected the **Require start/stop time** check box, in the **Allow time range overlap** field, select how the system responds when a worker submits a timesheet that spans multiple timesheet periods. You can choose to accept the submission with or without a warning, or prevent these timesheets from being submitted.

10. In the **Set voucher date to** field, specify whether the transaction date for timesheet hours should be set to the end date for the project period, the end date for the ledger period, or the project date.

11. In the **Journal posting** field, select either **Manual** or **Automatic**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Manual</STRONG>, you must manually post the approved timesheet in the <STRONG>Unposted timesheets</STRONG> form. This gives you another opportunity to review the submitted hours before they are posted.</P>



## Set up parameters for a timesheet system in Microsoft Dynamics AX 2012 R2

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  Depending on the version of Microsoft Dynamics AX 2012 R2 you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: In the left pane, click **Intercompany**.
    
      - In earlier versions of Microsoft Dynamics AX 2012: In the left pane, click **General**.

3.  If you want workers from one legal entity to be able to enter timesheet hours for work performed as a loaned resource in another legal entity, select the **Enable intercompany resource scheduling and timesheets** check box.

4.  In the left pane, click **Timesheet**.

5.  In the **Day week starts** field, specify the day of the week that you want to appear as the default in the **Day week starts** field in the **Period types** form.

6.  In the **Maximum number of timesheets per period** field, enter the maximum number of timesheets that a worker can enter for a time period. Enter 0 if you do not want to enforce a maximum number of timesheets.

7.  If you want workers to be able to save their most common projects and activities for repeated use, select the **Use favorites** check box.

8.  In the **Minimum time increment** field, enter a value to specify the minimum time increment that workers can enter for a project task. Enter the value as a fraction of an hour between 0.00 and 0.99. If you do not want to enforce the minimum time increment and want allow any value, enter 0. This setting can be overridden at the project level.

9.  If you want to define whether the requirement for a worker to enter start and stop times is enabled by default when a new worker profile is created, select the **Require start/stop time** check box.

10. If you selected the **Require start/stop time** check box, in the **Allow time range overlap** field, select how the system responds when a worker submits a timesheet that spans multiple timesheet periods. You can choose to accept the submission with or without a warning, or prevent these timesheets from being submitted.

11. In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: To send an automatic reminder to workers whose timesheets have not been submitted on time, select an email template in the **E-mail ID** field.

12. In the **Approved timesheet posting** field, select either **Manual** or **Automatic**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Manual</STRONG>, you must manually post the approved timesheet in the <STRONG>Unposted timesheets</STRONG> form. This gives you another opportunity to review the submitted hours before they are posted.</P>



## Set up parameters for timesheet audit trails and absence reporting in cumulative update 7 for Microsoft Dynamics AX 2012 R2

You can set up audit trails on all timesheets that are submitted in your organization. You can also prevent workers from entering future time on timesheets, except for a known absence. When you set up timesheet audit trails, you can record all of the changes that are made to a timesheet. When a worker changes a timesheet, you can allow or require the worker to enter the reason for the changes. For example, if a worker selects the wrong project ID and then updates the timesheet with the correct project ID, you can require that the worker enter an explanation for the change when the timesheet is updated.

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the left pane, click **Timesheet**.

3.  In the **Validation** group, select the audit trail parameters that you want to enable:
    
      - **Block future timesheet entries** – Select this check box to block workers from entering future time on timesheets.
    
      - **Validate absence categories** – Select this check box to require that absence categories be validated.
    
      - **Validate absence** – Select the project category that is defined as an absence category. This field is available only if you select the **Validate absence categories** check box.
    
      - **Require timesheet audit trail** – Select this check box to require an audit trail for all timesheets.
    
      - **Allow timesheet change reason** – Select this check box to give workers the option to enter comments when they change a timesheet. This check box is available only if you select the **Require timesheet audit trail** check box.
    
      - **Require timesheet change reason** – Select this check box to require workers to add comments when they change a timesheet. This check box is available only if you select the **Allow timesheet change reason** check box.

## See also

[About intercompany timesheets](about-intercompany-timesheets.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

  


