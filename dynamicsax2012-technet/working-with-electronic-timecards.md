---
title: Working with electronic timecards
TOCTitle: Working with electronic timecards
ms:assetid: f81d7e83-8a0d-48de-9033-1625b0975a62
ms:mtpsurl: https://technet.microsoft.com/library/Hh299227(v=AX.60)
ms:contentKeyID: 36384333
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JmgEPJobRegistration
- TSTimesheetCreateTimecard
- TSTimesheetListPage
audience: Application User
ms.search.region: Global
---

# Working with electronic timecards 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the electronic timecard in Enterprise Portal to create, modify, and transfer time registrations. The following procedures describe how to work with the electronic timecard features.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## Create and transfer time registrations

1.  Click **Time and attendance** on the top link bar, and then click **Electronic timecard** on the Quick Launch.

2.  In the **Profile date** field, select a date. Click **Update** to refresh the timecard.

3.  On the **Registration** FastTab, click **Lock** to lock the specified date.
    

    > [!NOTE]
    > <P>When you lock the timecard on a specific date, other users cannot make registrations on your timecard on that date until after your registrations have been transferred.</P>



4.  To create a registration line for jobs or tasks you have worked on:
    
    1.  Click **New** to create a line.
    
    2.  In the **Journal registration type** field, select the registration type to register time for.
    
    3.  In the **Reference** field, select a reference code. This determines which jobs are available in the **Job identification** field.
    
    4.  In the **Job identification** field, select the job that you want to enter time for. This will update the **Description** field.
    
    5.  If the job is part of a project, select the category for the registration in the **Category** field.
    
    6.  In the **Start time** fields, insert the date and time that you started to work on the job.
    
    7.  In the **End time** fields, insert the date and time that you stopped your work.

5.  Repeat the previous step to create additional registration lines.

6.  On the **Action Pane**, click **Check** to verify the information on the timecard. The **Time** field is populated during this verification. A warning message displays if there are inconsistencies.
    

    > [!NOTE]
    > <P>If you have not completed your registrations, click <STRONG>Save and close</STRONG> on the <STRONG>Action Pane</STRONG> to save the registrations made to this point. Remember that you must transfer the registrations later.</P>



7.  On the **Action Pane**, click **Transfer**. The timecard registrations are transferred to the **Calculate** form in Microsoft Dynamics AX 2012. Your supervisor or team leader will use this form to calculate your work time, pay time, overtime, flex time, absence time, and so on.
    
    If your timecard is not completed, do not transfer it. You can keep the timecard in the locked status and complete it later.


> [!NOTE]
> <P>The <STRONG>Profile</STRONG> FastTab displays information about the work time profile that will be used to calculate registrations.</P>
> <P>The <STRONG>Calculation</STRONG> FastTab provides an overview of the registrations that have been calculated, approved, and transferred in Microsoft Dynamics AX 2012. Pay calculations can be based on these registrations.</P>



## Maintain time registration lines

You can modify and delete lines on the electronic timecard regardless of whether they have been transferred to Microsoft Dynamics AX 2012. However, you cannot modify or delete lines that have been calculated in the **Calculate** form. The check boxes at the top of the **Electronic Timecard** page show whether the timecard is transferred and calculated.

1.  Click **Time and attendance** on the top link bar, and then click **Electronic timecard** on the Quick Launch.

2.  In the **Profile date** field, select a date. Click **Update** to refresh the timecard.

3.  Click **Cancel transfer** if the timecard has already been transferred to Microsoft Dynamics AX 2012.

4.  To modify a timecard line, select the line, modify the necessary information, and then click **Update**.
    
    –or–
    
    To delete a timecard line, select the line, and then click **Delete**.

5.  Click **Transfer**. The timecard is transferred to the **Calculate** form in Microsoft Dynamics AX 2012.
    
    If your timecard is incomplete, do not transfer it. You can keep the timecard in the locked status and complete it later.

## See also

[About electronic timecards](about-electronic-timecards.md)

  


